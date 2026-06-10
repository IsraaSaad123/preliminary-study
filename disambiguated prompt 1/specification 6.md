# Regulatory Obligation Specification
## Feature: Maths Numeracy Speech Practice

### Feature Summary

Students practise basic maths numeracy by speaking answers aloud into their device microphone. A speech recognition system transcribes each spoken response, provides immediate feedback, and stores only the transcribed text so that students can review previous attempts and replay lessons. Raw audio is processed transiently for transcription and is not retained.

### Data in Scope

| Data element | Nature | Stored? |
|---|---|---|
| Transcribed text of spoken response | Personal data linked to student identity | Yes |
| Raw microphone audio | Personal data (voice) | No — transient processing only |

### Users

Students, expected to include children below the age of 16.

---

### Obligations

**OB1:** The processing of transcribed student responses constitutes personal data processing and must be supported by an identified lawful legal basis (e.g. consent, contract, or legitimate interests) before any data is collected or stored.

**OB2:** Where consent is the chosen legal basis for processing transcribed responses, the controller must be able to demonstrate that each student's consent was freely given, specific, informed, and unambiguous, and must provide a withdrawal mechanism that is as easy to use as the consent mechanism itself.

**OB3:** Where a student is below the applicable age threshold (16 years, or the lower national threshold if a Member State has set one, not below 13), consent to processing transcribed responses must be given or authorised by the holder of parental responsibility, and the controller must make reasonable efforts to verify that such authorisation has been obtained.

**OB5:** Transcribed student responses must be collected solely for the specified purposes of enabling students to review previous attempts and replay lessons; they must not be further processed in any manner incompatible with those purposes.

**OB6:** Storage must be limited to the transcribed text of each response; raw audio must not be retained, and no additional personal data beyond what is strictly necessary for lesson review and replay may be collected or stored.

**OB7:** Transcribed student responses must be kept for no longer than is necessary for their stated purposes. [retention: 12 months from the date of collection, after which records must be securely deleted]

**OB8:** At the point at which transcribed responses are collected, the controller must provide students (and, where the student is below the applicable age threshold, their parent or guardian) with the purposes of processing, the legal basis, any recipients of the data, and the retention period. [retention: 12 months from the date of collection]

**OB9:** Students, and parents or guardians acting on behalf of students below the applicable age threshold, must be able to obtain erasure of stored transcribed responses without undue delay in circumstances where, for example, the data are no longer necessary or consent is withdrawn.

**OB10:** Appropriate technical and organisational measures must be implemented to secure transcribed student responses against unauthorised access, loss, or disclosure, taking into account the sensitivity of processing personal data of children in an educational context.

---

### Provision Not Applied

**OB4** — The audio is processed transiently solely to extract spoken content (speech-to-text), not to uniquely identify or authenticate the student. Neither the transient audio processing nor the stored transcribed text constitutes biometric data processed for the purpose of uniquely identifying a natural person under Art. 9.

---

### Source

Obligations derived exclusively from the data protection provisions listed in `gdpr_provisions.md` (OB1–OB10), reflecting EU GDPR (Regulation (EU) 2016/679) and the UK GDPR.
