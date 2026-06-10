# Regulatory Obligation Specification
## Feature: Voice-Based Maths Numeracy Practice

### Feature Summary

Students practise basic maths numeracy by speaking answers aloud. The application
captures microphone audio, uses speech recognition to transcribe the spoken numerical
content, and provides immediate feedback. Voice audio is processed solely to recognise
spoken numerical answers; it is not used to identify or distinguish individual speakers.
Transcribed responses and feedback are logged in app history so students can review
previous attempts and replay lessons.

### Applicable Provisions and Obligations

The following obligations are derived exclusively from the provisions in
`gdpr_provisions.md` (OB1–OB10).

---

OB1: The application must identify and document a lawful basis under Art. 6 for each
distinct processing activity before it begins: (a) capturing and transcribing voice
audio to recognise spoken numerical answers, and (b) storing transcribed responses,
questions, and feedback in app history for student review.

OB2: Where consent is adopted as the lawful basis, the application must obtain consent
that is freely given, specific, informed, and unambiguous before the microphone is
activated or any response is logged; the application must also provide a withdrawal
mechanism that is as easy to use as the consent mechanism itself.

OB3: Because the application is directed at students who may be below the applicable
age threshold (16 years, or a lower Member State minimum of not below 13), where
processing relies on consent the application must determine each student's age before
processing commences; where the student is below that threshold, consent must be given
or authorised by the holder of parental responsibility, and the application must make
reasonable efforts to verify that such authorisation has been obtained.

OB5: Voice audio may be processed only for the purpose of recognising spoken numerical
answers and generating immediate feedback; transcribed responses may be retained in app
history only for the purpose of enabling students to review their previous attempts and
replay lessons. No further processing incompatible with those defined purposes is
permitted.

OB6: The application must collect and retain only the data necessary for its stated
purposes: raw voice audio must not be stored once transcription is complete; response
logs must be limited to the transcribed answer, the question presented, the feedback
given, and a timestamp — no speaker-identifying audio features or metadata beyond these
fields may be retained.

OB7: Raw voice audio must be deleted immediately upon successful transcription and must
not be persisted to any storage layer. Transcribed response logs must be kept for no
longer than 12 months from the date of collection, after which they must be permanently
deleted or irreversibly anonymised. [retention: raw audio — deleted immediately on
transcription; response logs — 12 months from date of collection]

OB8: At the point of data collection — before the microphone is first activated and
before response logging begins — the application must present students (and, where the
student is a child, their parent or guardian) with: the purposes of processing, the
lawful basis relied upon, any recipients of the data, and the applicable retention
periods (raw audio deleted immediately on transcription; response logs retained for
12 months). [retention: raw audio — deleted immediately on transcription; response
logs — 12 months from date of collection]

OB9: The application must provide a mechanism through which students (or their parents
or guardians where the student is a child) can request erasure of stored response logs
without undue delay; where consent is withdrawn and no alternative lawful basis applies,
all associated logs must be erased.

OB10: The application must implement appropriate technical and organisational measures
to secure voice audio during capture and transmission (e.g. encrypted in-transit
processing) and to protect stored response logs at rest, proportionate to the risk
arising from processing personal data of student minors.

---

### Provision Codes Applied

OB1, OB2, OB3, OB5, OB6, OB7, OB8, OB9, OB10

### Provisions Not Applied

OB4 (Art. 9 — special categories): Voice audio is processed solely to recognise
spoken numerical content and is not processed for the purpose of uniquely identifying
a natural person; accordingly, the processing does not constitute biometric processing
within the meaning of Art. 9 and OB4 does not apply.
