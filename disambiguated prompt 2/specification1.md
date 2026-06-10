# Regulatory Obligation Specification
## Feature: Microphone-Based Maths Numeracy Practice with Response History

### Feature Summary

Students practise basic maths numeracy by speaking answers aloud. The application captures voice audio via the device microphone, uses speech recognition to transcribe spoken numerical answers in real time, and provides immediate feedback. Voice audio is processed solely to recognise the spoken numerical content of each answer; it is not used to identify or distinguish individual speakers. All student responses are logged in an in-app history so that students can review previous attempts and replay lessons.

### Applicable Provisions and Obligations

OB1: The controller must identify and document a lawful legal basis for each distinct processing activity — specifically for the transient processing of voice audio for speech-recognition transcription and for the persistent logging of student response history in the application.

OB2: Where consent is relied upon as the legal basis for collecting voice audio via the device microphone, the controller must obtain consent that is freely given, specific, informed, and unambiguous, and must provide a mechanism for withdrawing consent that is as easy to use as the mechanism for giving it.

OB3: Because the application is an information society service offered directly to students who may be under 16, where processing of a student's personal data relies on consent, the controller must make reasonable efforts to verify that consent is given or authorised by the holder of parental responsibility for any student below the applicable age threshold (16 years, or the lower age adopted by the relevant Member State, but not below 13 years).

OB5: The controller must define and document the purpose of each processing activity: voice audio is processed solely to transcribe spoken numerical answers during an active session; student response history is logged solely to enable students to review previous attempts and replay lessons. Neither activity may be further processed in a manner incompatible with those defined purposes.

OB6: The controller must limit collected data to what is strictly necessary for each purpose: raw voice audio must not be retained beyond the completion of real-time transcription within the current session; only the transcribed textual answer and the minimum session metadata required for lesson review (for example, question identifier, answer, timestamp) may be stored in the response history log.

OB7: The controller must define and enforce a retention period for personal data held in the response history log. [retention: response history records must be deleted no later than 12 months from the date of the session in which they were recorded, or upon closure of the student's account, whichever is sooner; raw voice audio must not be retained beyond the end of the session in which it is captured]

OB8: At the point at which personal data are collected — specifically when microphone access is first requested and when response logging is initiated — the controller must provide each student (and, where OB3 applies, the holder of parental responsibility) with the following information: the purposes for which voice audio and response history data are processed, the legal basis relied upon, the recipients of the data if any, and the applicable retention period. [retention: the retention period disclosed must be consistent with OB7 — 12 months from session date, or account closure, whichever is sooner]

OB9: The controller must provide each student with a readily accessible mechanism to request erasure of their response history without undue delay, and must honour such requests where the data are no longer necessary for the stated logging purpose or where consent is withdrawn and no other legal basis applies.

OB10: The controller must implement appropriate technical and organisational security measures for both the transient voice audio stream and the persistent response history, proportionate to the risk, including measures to prevent unauthorised access to microphone input during a session and to stored response records between sessions.

### Provision Codes Applied

OB1, OB2, OB3, OB5, OB6, OB7, OB8, OB9, OB10

### Provision Codes Not Applied

OB4 — The voice audio is processed solely to recognise spoken numerical content and is not processed to uniquely identify or distinguish individual speakers. Processing does not therefore constitute processing of biometric data for the purpose of unique identification within the meaning of Article 9, and no other special-category data (such as health data) is collected. OB4 does not apply.
