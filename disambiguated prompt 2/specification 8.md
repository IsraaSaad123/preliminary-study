# Regulatory Obligation Specification
## Feature: Voice-Based Maths Numeracy Practice

### Feature Summary

Students practise basic maths numeracy by speaking answers aloud into their device microphone. A speech-recognition component transcribes the spoken numerical content and provides immediate feedback. Voice audio is processed solely to recognise numerical answers; it is not used to identify or distinguish individual speakers. All student responses are logged in app history so that students can review previous attempts and replay lessons.

### Personal Data in Scope

| Data element | Nature |
|---|---|
| Voice audio captured during an answer | Personal data (captured from an identified or identifiable student) |
| Transcribed numerical response | Personal data linked to a student session |
| App-history log (responses, timestamps, lesson context) | Personal data retained for student review |

> **Note on Art. 9 / OB4:** The system statement that voice audio is processed solely to recognise spoken numerical content — and is not used to identify or distinguish individual speakers — means the audio is not processed as biometric data for the purpose of uniquely identifying a natural person (Art. 9(1)). OB4 therefore does not apply. If the processing purpose or technical pipeline changes such that voice characteristics are used for speaker identification, OB4 must be reassessed.

---

### Applicable Obligations

OB1: The controller must identify and document a lawful legal basis under Art. 6 for each processing activity: (a) real-time capture and processing of voice audio for numerical speech recognition, and (b) retention of student response logs in app history. [retention: n/a]

OB2: Where consent is selected as the legal basis for any processing activity, the controller must obtain and record freely given, specific, informed, and unambiguous consent from the student (or their parent or guardian where OB3 applies), and must provide an equally simple mechanism for withdrawing consent at any time. [retention: n/a]

OB3: Because basic maths numeracy practice is directed at students who are likely below 16 years of age, and the service is offered directly to children via an information society service, consent for any consent-based processing is lawful only if given or authorised by the holder of parental responsibility; the controller must make reasonable efforts to verify that authorisation before processing commences. [retention: n/a]

OB5: Voice audio must be collected and processed only for the specified, explicit, and legitimate purpose of recognising the spoken numerical content of student answers and logging those answers for student review; the audio and derived data must not be further processed in any manner incompatible with that purpose (for example, behavioural profiling or speaker recognition). [retention: n/a]

OB6: Data collected must be limited to what is strictly necessary for the defined purposes: only the transcribed numerical response and the minimum session metadata required to support the review history should be retained; raw voice audio must not be stored beyond the instant required for real-time transcription unless replay functionality is the explicit, stated purpose and no less privacy-intrusive alternative exists. [retention: n/a]

OB7: Student response logs held in app history must be kept in identifiable form for no longer than is necessary for the purpose of enabling student review of previous attempts; a defined retention period must be established and enforced. [retention: 12 months from the date of each recorded response, after which response logs must be deleted or irreversibly anonymised]

OB8: At the point of first data collection (before the microphone is activated), the controller must provide students (and, where OB3 applies, their parents or guardians) with all required information, including: the identity and contact details of the controller; the purposes and legal basis for processing voice audio and response logs; any recipients or categories of recipients; and the retention period for response logs. [retention: 12 months from the date of each recorded response]

OB9: Students (and, where applicable, their parents or guardians) must be able to exercise the right to erasure of their response logs and any other retained personal data without undue delay in circumstances where, for example, the data are no longer necessary for the review purpose or consent is withdrawn; the controller must provide a clear mechanism for submitting such requests and must act on them within the statutory period. [retention: n/a]

OB10: The controller must implement appropriate technical and organisational security measures for all personal data processed by this feature, including voice audio in transit, transcribed responses in transit, and stored response logs, taking into account the sensitivity of data relating to children and the risks of unauthorised access or accidental loss. [retention: n/a]
