# Regulatory Obligation Specification
## Feature: Spoken-Answer Maths Numeracy Practice

### Feature Summary

Students practise basic maths numeracy by speaking answers aloud. The device microphone captures voice audio, which is processed transiently by a speech-recognition component to produce a text transcription. The transcription is used to provide immediate feedback and is stored in the student's in-app history so that students can review previous attempts and replay lessons. Raw audio is not stored.

### Personal Data in Scope

| Data element | How processed | Stored? |
|---|---|---|
| Voice audio | Captured and transcribed transiently | No |
| Transcribed text response | Written to app history per attempt | Yes |
| Student identity (account association) | Implicit in history ownership | Yes |

Students using a school numeracy application are likely to be children, engaging the child-consent provisions.

---

### Applicable Obligations

OB1: The controller must identify and document a valid legal basis under Art. 6 for each processing activity: transient processing of voice audio for speech recognition, and persistent storage of transcribed text in the student's practice history.

OB2: Where consent is the chosen legal basis, the controller must be able to demonstrate that each student (or their parent/guardian where OB3 applies) has given freely given, specific, informed, and unambiguous consent prior to microphone access or transcription storage being activated; the controller must provide a mechanism to withdraw consent that is as easy to use as the mechanism to give it.

OB3: Because the feature is offered as an information society service directed at students who may be below 16, where consent is the legal basis the controller must verify the student's age; for students below the applicable age threshold (16 under EU/UK GDPR, or a lower age permitted by applicable Member State law, but not below 13), consent must be given or authorised by a holder of parental responsibility, and the controller must make reasonable efforts to verify that authorisation before processing commences.

OB5: The controller must define the specified, explicit, and legitimate purpose for which transcribed responses are collected (enabling student practice review and lesson replay); transcribed text must not be further processed in a manner incompatible with that purpose.

OB6: The controller must ensure that only the transcribed text of each spoken response is retained; raw voice audio must not be stored, and no personal data beyond what is necessary to support practice review and lesson replay may be collected or held.

OB7: The controller must define a retention period for stored transcribed responses; transcribed text must be deleted no later than 12 months after the date of the student's last activity on the platform, or upon account deletion if that occurs earlier. [retention: 12 months from the student's last platform activity]

OB8: At the point of first microphone access or account creation (whichever is earlier), the controller must provide the student and, where OB3 applies, their parent or guardian, with the following information: the purpose of processing transcribed responses, the legal basis relied upon, any recipients or categories of recipients of the data, and the retention period. [retention: 12 months from the student's last platform activity]

OB9: The controller must provide a mechanism through which a student or their parent/guardian can request erasure of stored transcriptions without undue delay, and must fulfil such requests where the conditions of Art. 17 are met, including where the data are no longer necessary for the stated purpose or where consent is withdrawn and no other legal basis applies.

OB10: The controller must implement appropriate technical and organisational measures to protect voice audio during transient processing and to secure stored transcribed text against unauthorised access, disclosure, alteration, or loss, with measures calibrated to the risk to data subjects who are children.

---

### Provisions Assessed as Not Applicable

**OB4 (Art. 9 — Special categories):** Voice audio is captured solely as a medium for extracting the semantic content of a spoken answer (speech-to-text transcription); it is not processed to uniquely identify the student. The processing therefore does not constitute processing of biometric data to uniquely identify a natural person within the meaning of Art. 9, and the raw audio is not stored. OB4 does not apply to this feature on the facts described.

---

### Provision Codes That Apply

OB1, OB2, OB3, OB5, OB6, OB7, OB8, OB9, OB10
