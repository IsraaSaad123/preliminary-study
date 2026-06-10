# Generated specifications

Each `specification x.md` file under `baseline/`, `disambiguated prompt 1/`, and `disambiguated prompt 2/` is the `specification.md` produced by the agent in one independent run.

---

## The regulatory source (`gdpr_provisions.md`)

The provision file contains ten coded data‑protection obligations (OB1–OB10), summarised by the researcher from specific GDPR articles. The provisions are materially equivalent under the EU and UK GDPR and are not framed as specific to either jurisdiction. They were selected as those governing the processing activities the feature performs.

---

## The three conditions

All three prompts share the same feature description and the same regulatory source (`gdpr_provisions.md`). They differ only in whether, and how, a single underspecified regulatory context element is resolved.

### Condition 1: Baseline (context ambiguity present)

The data type to be logged ("responses") and the processing purpose are left unspecified.

> **Prompt:**
> 
> I want to build a feature that allows students to practice basic maths numeracy using their device's microphone. Students should be able to pronounce their answers aloud, and the application should use speech recognition to transcribe the spoken responses and provide immediate feedback. The system should log all students' responses in the app history so that students can review their previous attempts and replay lessons. Using only the data protection provisions listed in the file `gdpr_provisions.md` provided in the repository, identify which provisions apply to this feature and produce a regulatory obligation specification. For each applicable provision, output one obligation in the form `OBx: <obligation text> [retention: <period if applicable>]`, one per line. List only the provision codes that apply, and do not introduce provisions or codes that are not in the provided file. Where a retention period is relevant (OB7, OB8), state a specific retention period.

### Condition 2: Data type disambiguation

The element resolved is what data is stored: only transcribed text is stored; raw audio is not retained. (Targets the retention obligation, OB7.) Specificatoins generated from this prompt are stored under `disambiguated prompt 1/`. 

> **Prompt:**
> 
> I want to build a feature that allows students to practice basic maths numeracy using their device's microphone. Students should be able to pronounce their answers aloud, and the application should use speech recognition to transcribe the spoken responses and provide immediate feedback. **The system should store only the transcribed text of each response in the app history (raw audio is processed transiently for transcription and not stored)**, so that students can review their previous attempts and replay lessons. Using only the data protection provisions listed in the file `gdpr_provisions.md` provided in the repository, identify which provisions apply to this feature and produce a regulatory obligation specification. For each applicable provision, output one obligation in the form `OBx: <obligation text> [retention: <period if applicable>]`, one per line. List only the provision codes that apply, and do not introduce provisions or codes that are not in the provided file. Where a retention period is relevant (OB7, OB8), state a specific retention period.

### Condition 3: Processing purpose disambiguation

The element resolved is the processing purpose: the voice audio is processed only to recognise numerical content, not to identify speakers. (Targets the special‑category obligation, OB4.) The data type to be logged is left ambiguous. Specificatoins generated from this prompt are stored under `disambiguated prompt 2/`. 

> **Prompt:**
> 
> I want to build a feature that allows students to practice basic maths numeracy using their device's microphone. Students should be able to pronounce their answers aloud, and the application should use speech recognition to transcribe the spoken responses and provide immediate feedback. **The voice audio is processed solely to recognise the spoken numerical content of each answer; it is not used to identify or distinguish individual speakers**. The system should log all students' responses in the app history so that students can review their previous attempts and replay lessons. Using only the data protection provisions listed in the file `gdpr_provisions.md` provided in the repository, identify which provisions apply to this feature and produce a regulatory obligation specification. For each applicable provision, output one obligation in the form `OBx: <obligation text> [retention: <period if applicable>]`, one per line. List only the provision codes that apply, and do not introduce provisions or codes that are not in the provided file. Where a retention period is relevant (OB7, OB8), state a specific retention period.
