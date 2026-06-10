# Regulatory Obligation Specification

## Feature

Maths numeracy practice using device microphone input. Students pronounce answers aloud; a speech-recognition service transcribes responses; the application provides immediate feedback and stores a persistent session history that students can review and replay.

## Personal Data Processed

| Data element | Description |
|---|---|
| Voice audio | Raw audio captured from the device microphone during each practice session |
| Transcriptions | Text produced by speech recognition from the voice audio |
| Session history | Timestamped records of questions, transcribed answers, and feedback outcomes, linked to an identified student |

Voice audio constitutes biometric data because it encodes physical and behavioural characteristics of the speaker. Session history constitutes personal data because it is linked to an identifiable student.

## Applicable Provisions

The following provisions from the Data Protection Provisions (GDPR) file apply to this feature. Each obligation is expressed once, one per line, in the form required.

---

OB1: The system must identify and document a specific lawful basis under Art. 6 for each distinct processing activity: capturing voice input via the microphone, transmitting audio to a speech-recognition service, storing transcriptions, and maintaining and replaying session history linked to an identified student.

OB2: Where consent is the chosen lawful basis for any processing activity, the system must obtain freely given, specific, informed, and unambiguous consent before activating the microphone or before writing any session record; a withdrawal mechanism must be presented and must be no more burdensome to use than the original consent action.

OB3: Because the feature is directed at students who may be under 16 (and potentially under 13), where consent is the lawful basis the system must obtain consent given or authorised by the holder of parental responsibility for any student below the applicable age threshold, and must make reasonable efforts to verify that such parental authorisation has been obtained before processing begins.

OB4: Voice recordings are biometric data within the meaning of Art. 9; the system must not capture, transmit, or process audio unless a specific Art. 9 exception applies (for example, explicit consent from the data subject or, for a child below the relevant age threshold, from their parent or guardian), and must document which exception is relied upon.

OB5: Personal data collected by this feature must be used solely for the purposes of enabling maths numeracy practice, generating immediate feedback, and maintaining a personal session history for the student's own review; the data must not be used for any purpose incompatible with those stated purposes, including but not limited to behavioural profiling, advertising, or training third-party machine-learning models.

OB6: The system must collect and retain only the minimum data necessary for the defined purposes: transcriptions and feedback outcomes are sufficient for session history; raw audio recordings must be deleted immediately after the transcription step is complete and must not be stored in session history or transmitted beyond what is required for the transcription service call.

OB7: Session history records (transcriptions, questions, feedback outcomes) must be retained for no longer than 12 months from the date of each session, or until the student's account is closed or the student withdraws from the service, whichever is earlier; deletion must be enforced automatically and must extend to all copies, including backups. [retention: 12 months from the date of each session, or until account closure or student withdrawal, whichever is earlier]

OB8: Before the microphone is activated for the first time, the system must present the student (and, where OB3 applies, their parent or guardian) with a privacy notice that states: the identity and contact details of the controller; the purposes of processing (practice, feedback, and personal history review); the lawful basis relied upon; whether voice audio is transmitted to a third-party speech-recognition service and, if so, its identity; and the retention period. [retention: 12 months from the date of each session, or until account closure or student withdrawal, whichever is earlier]

OB9: The system must provide students, and parents or guardians acting on behalf of students below the applicable age threshold, with a clearly accessible mechanism to request erasure of all stored session history and any associated personal data; the system must carry out erasure without undue delay and must confirm completion to the requester.

OB10: All personal data processed by the feature must be protected by appropriate technical and organisational measures proportionate to the risk, including: encryption of audio in transit to any speech-recognition service; encryption of stored transcriptions and session history at rest; access controls that restrict retrieval of a student's history to that student (and their parent or guardian where applicable) and to authorised personnel only; and audit logging of any access to session history records.

---

## Provision Codes That Apply

OB1, OB2, OB3, OB4, OB5, OB6, OB7, OB8, OB9, OB10
