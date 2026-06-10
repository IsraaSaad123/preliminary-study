# Regulatory Obligation Specification

## Feature: Microphone-Based Maths Numeracy Practice with Response History

### Applicable Provisions and Obligations

OB1: The application must identify and document a valid legal basis for each processing activity before processing begins, covering: microphone audio capture, speech-to-text transcription, immediate feedback generation, and persistent logging of student responses in the history store. [retention: n/a]

OB2: Where consent is relied upon as the legal basis, the application must obtain freely given, specific, informed, and unambiguous consent from the student (or their parent/guardian where OB3 applies) before activating the microphone or writing any response record; a mechanism to withdraw consent at any time, with equal ease to giving it, must be provided, and withdrawal must stop all further processing and trigger the erasure right under OB9. [retention: n/a]

OB3: Because the application is an information society service directed at students who may be below 16 years of age (or such lower age as the applicable Member State has set, but not below 13), the application must determine each student's age at registration; where a student is below the applicable age threshold, consent must be obtained from or authorised by the holder of parental responsibility, and the application must make reasonable efforts to verify that such authorisation has been given before any microphone access or response logging is permitted. [retention: n/a]

OB4: Voice recordings captured via the microphone may constitute biometric data capable of uniquely identifying a student and are therefore a special category of personal data under Art. 9; the application must not process such data unless a specific Art. 9 exception applies (for example, the student's explicit consent), and that exception must be identified and documented before microphone use begins. [retention: n/a]

OB5: All personal data collected through the microphone and stored in the response history must be processed solely for the purpose of supporting the student's maths numeracy practice and self-review of previous attempts; the application must not reuse voice recordings, transcriptions, or response logs for any purpose incompatible with that stated purpose (for example, behavioural profiling, third-party analytics, or voice-model training) without a fresh legal basis. [retention: n/a]

OB6: The application must capture and retain only the minimum data necessary for maths numeracy practice: audio should be processed transiently for transcription and not stored as raw audio beyond the duration of a session unless strictly necessary; the response history log must record only the transcribed answer, the associated question, the feedback outcome, and the timestamp, and must not collect extraneous acoustic metadata, device identifiers, or other data unnecessary for the educational purpose. [retention: n/a]

OB7: Response history records must not be retained for longer than 12 months from the date on which each record was created; records that have reached this limit must be automatically deleted; if a student's account is closed before that limit is reached, all associated records must be deleted within 30 days of account closure. [retention: 12 months from the date of each response record, or 30 days after account closure, whichever is earlier]

OB8: At or before the point at which the microphone is first activated and response logging begins, the application must present the student (and, where OB3 applies, the parent or guardian) with a clear privacy notice stating: the identity and contact details of the controller; the purposes of processing (maths practice and response history review); the legal basis relied upon; whether voice recordings constitute special-category data and the Art. 9 exception relied upon; any recipients or categories of recipients; the retention period (12 months from each record's creation date, or 30 days after account closure, whichever is earlier); and the existence of the rights to access, rectification, erasure, and withdrawal of consent. [retention: 12 months from each response record's creation date, or 30 days after account closure, whichever is earlier]

OB9: The application must provide a mechanism by which a student (or their parent/guardian where the student is a minor) can request erasure of all or part of their response history without undue delay; upon a valid erasure request, or upon withdrawal of consent, all associated voice recordings, transcriptions, and response log entries must be deleted; the application must not retain any record that has been the subject of a valid erasure request beyond the time strictly necessary to process that request. [retention: n/a]

OB10: The application must implement appropriate technical and organisational security measures commensurate with the risk posed by processing children's voice data and response history, including: encryption of response history records at rest and in transit; access controls limiting history access to the individual student and authorised personnel; secure deletion procedures ensuring that records purged under OB7 or OB9 cannot be recovered; and a documented assessment of the risks specific to microphone-based capture of children's data. [retention: n/a]

---

### Provision Codes That Apply

OB1, OB2, OB3, OB4, OB5, OB6, OB7, OB8, OB9, OB10
