# Regulatory Obligation Specification

**Feature:** Speech-Based Maths Numeracy Practice with Response History  
**Regulatory framework:** EU GDPR (Regulation (EU) 2016/679) / UK GDPR  
**Source of provisions:** `gdpr_provisions.md`

---

## Applicable Provisions and Obligations

OB1: The application must identify and document a lawful basis for each processing activity before processing begins: (a) capture of audio via the device microphone, (b) transcription of spoken responses, and (c) storage of response history. [retention: not applicable]

OB2: Where processing relies on consent, the application must obtain freely given, specific, informed, and unambiguous consent from the data subject (or their parent or guardian where OB3 applies) before activating the microphone or storing response history, and must provide an equally prominent mechanism to withdraw consent at any time. [retention: not applicable]

OB3: Because the application is an information society service offered directly to students who may be children, where processing is based on consent the application must verify the age of each student and, for any student below 16 years of age (or the lower Member State threshold, not below 13), obtain consent given or authorised by the holder of parental responsibility before any personal data are collected. [retention: not applicable]

OB4: Voice recordings captured via the microphone constitute biometric data; the application must not process such data unless a specific exception under Article 9(2) applies, such as explicit consent from the data subject or, where the data subject is a child below the applicable age threshold, explicit consent given or authorised by the holder of parental responsibility. [retention: not applicable]

OB5: The application must define the purposes of processing — specifically (a) speech-to-text transcription to evaluate a student's answer, (b) delivery of immediate feedback, and (c) storage of response history to allow students to review past attempts — and must not process personal data in any manner incompatible with those stated purposes. [retention: not applicable]

OB6: The application must limit data collection to what is strictly necessary: raw audio recordings must not be retained once transcription is complete; response history must record only the information required to support review of past attempts (e.g., question, transcribed answer, correctness, timestamp) and must not capture or retain extraneous audio metadata or device identifiers beyond what is necessary. [retention: not applicable]

OB7: Raw audio recordings must be deleted immediately upon successful transcription and in any event no later than 24 hours after capture. Transcribed response history records must be retained for no longer than 12 months from the date of each attempt, after which they must be deleted automatically. [retention: audio — deleted within 24 hours of capture; response history — 12 months from the date of each recorded attempt]

OB8: At the point of first microphone activation and before any personal data are collected, the application must present the student (and, where OB3 applies, the parent or guardian) with clear information comprising: the identity of the data controller, the purposes of processing, the legal basis, any recipients of the data, the retention periods specified in OB7, and the existence of the rights described in OB9. [retention: not applicable]

OB9: The application must provide students and, where applicable, their parents or guardians with a mechanism to request erasure of all personal data — including response history records and any retained audio — without undue delay, and must honour such requests where no overriding legal basis for continued processing exists, including where consent is withdrawn. [retention: not applicable]

OB10: The application must implement appropriate technical and organisational security measures commensurate with the risk, including: encrypted storage and transmission of audio recordings and response history, access controls restricting data to authorised parties only, and secure deletion of audio recordings in accordance with the retention period in OB7. [retention: not applicable]
