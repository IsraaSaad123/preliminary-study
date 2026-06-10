# Regulatory Obligation Specification
## Feature: Voice-Based Maths Numeracy Practice with Response History

### Feature Summary

Students practise basic maths numeracy by speaking answers aloud. The device microphone captures audio, which is processed by a speech-recognition component solely to transcribe the spoken numerical content of each answer. The transcription result is compared against the expected answer and immediate feedback is provided. All responses (question, transcribed answer, outcome) are logged in an in-app history so that students can review previous attempts and replay lessons. Audio is not used to identify or distinguish individual speakers.

---

### Applicable Provisions and Obligations

OB1: The controller must identify and document a lawful basis under Art. 6 for each processing activity in this feature: (a) capturing and processing voice audio for speech recognition, (b) storing the transcribed numerical responses, and (c) retaining the response history log for student review.

OB2: Where processing of voice audio or response history relies on consent as its lawful basis, the controller must be able to demonstrate that each student (or, where applicable, their parent or guardian) gave consent that was freely given, specific, informed, and unambiguous; the mechanism for withdrawing consent must be as simple as the mechanism for giving it.

OB3: Because this feature is an information society service offered directly to children (students learning basic numeracy), where processing is based on consent the controller must make reasonable efforts to verify that children below the applicable age threshold (16, or a lower Member State threshold no less than 13) have obtained consent given or authorised by the holder of parental responsibility before any voice audio is captured or response data is stored.

OB5: The purposes for which voice audio and response data are collected must be specified, explicit, and legitimate — namely, real-time speech recognition for answer transcription and storage of response history for student self-review — and the data must not be further processed in a manner incompatible with those purposes (for example, the audio or transcripts must not be used for speaker profiling, advertising, or any purpose beyond numeracy practice support).

OB6: Data collected must be limited to what is necessary for the stated purposes: only the transcribed numerical answer (not raw audio beyond the instant of transcription), together with the associated question identifier, outcome, and timestamp, should be retained; any intermediate audio buffers must be discarded immediately after transcription.

OB7: Response history records must be kept for no longer than is necessary for the purpose of student self-review of numeracy practice. The retention period for response history logs is 12 months from the date each record is created, after which records must be deleted or irreversibly anonymised. [retention: 12 months from date of creation]

OB8: At or before the point at which voice audio is first captured, students (and, where OB3 applies, their parents or guardians) must be provided with the following information: the identity and contact details of the controller; the purposes of processing (speech recognition for answer transcription; storage of response history for self-review); the legal basis relied upon; any recipients or categories of recipients of the data; and the retention period of 12 months for response history records. [retention: 12 months from date of creation]

OB9: Students (or, where applicable, their parents or guardians) must be able to obtain erasure of their response history records without undue delay where those records are no longer necessary for the purposes for which they were collected, or where consent is withdrawn and no other lawful basis applies; the application must provide a mechanism for submitting and fulfilling such erasure requests.

OB10: The controller must implement appropriate technical and organisational measures to protect voice audio during processing and response history records in storage, including measures commensurate with the risk posed by processing audio data from children, such as encryption of data in transit and at rest, access controls restricting history records to the individual student, and secure deletion of audio buffers immediately after transcription.
