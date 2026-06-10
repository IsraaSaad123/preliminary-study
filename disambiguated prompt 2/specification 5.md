# Regulatory Obligation Specification

**Feature:** Voice-based maths numeracy practice with spoken-answer recognition and response history logging.

## Data processed

| Data element | Description |
|---|---|
| Raw voice audio | Microphone input captured per answer attempt |
| Transcribed numerical response | Text output produced by speech recognition from the audio |
| Response history | Per-student log of attempts, transcribed answers, and correctness feedback |

Students are assumed to be school-age children. Voice audio is processed solely to extract spoken numerical content; it is not processed to identify or distinguish individual speakers and therefore does not constitute biometric data processed for the purpose of uniquely identifying a natural person (Art. 9). OB4 therefore does not apply.

## Applicable provisions

OB1, OB2, OB3, OB5, OB6, OB7, OB8, OB9, OB10

## Obligations

OB1: Identify and document a lawful basis under Art. 6 for each distinct processing activity before the feature is deployed: (a) processing of voice audio for speech recognition, and (b) logging and retention of response history. The lawful basis must be assessed separately for each activity and recorded in the controller's records of processing activities.

OB2: Where consent is chosen as the lawful basis for any processing activity, implement a consent mechanism that is freely given, specific, informed, and unambiguous; record evidence of each consent; and provide a withdrawal mechanism that is no more difficult to use than the consent mechanism itself.

OB3: Because the feature is directed at students who are likely children, gate consent-based processing on age verification. Where a student is below the applicable age threshold (16 years, or as lowered by the relevant Member State to not below 13), do not commence processing until consent has been given or explicitly authorised by the holder of parental responsibility; apply reasonable technical measures to verify that such parental authorisation has been obtained.

OB5: Define and document the explicit, specified, and legitimate purpose for each processing activity: (a) voice audio is collected and processed solely to recognise the numerical content of the student's spoken answer; (b) response history is logged solely to enable the student to review past attempts and replay lessons. Voice audio must not be further processed in any manner incompatible with purpose (a), including speaker identification, behavioural profiling, or any secondary analytics.

OB6: Limit the personal data collected and retained to what is strictly necessary for each defined purpose. Raw voice audio must not be stored beyond the moment of transcription. Response history records must contain only the transcribed answer, the associated question identifier, the correctness outcome, and the timestamp; voice characteristics, speaker embeddings, and any superfluous metadata must not be retained.

OB7: Define and enforce a retention schedule: raw voice audio must be deleted immediately upon successful transcription; transcribed response history must be retained for no longer than 12 months from the date of collection, after which it must be deleted or rendered non-identifiable. [retention: raw voice audio — deleted immediately after transcription; response history — 12 months from date of collection]

OB8: At the point of data collection, provide the student (and, where OB3 applies, the parent or guardian) with the following information: the identity and contact details of the controller; the purpose of processing voice audio (numerical answer recognition) and the purpose of logging response history (progress review and lesson replay); the lawful basis relied upon for each activity; any recipients or categories of recipients of the data; and the applicable retention periods (raw voice audio deleted immediately after transcription; response history retained for 12 months from date of collection). [retention: raw voice audio — deleted immediately after transcription; response history — 12 months from date of collection]

OB9: Provide students (and, where applicable, parents or guardians) with a mechanism to request erasure of their response history without undue delay; erasure must be carried out where the data are no longer necessary for the stated purpose, where consent is withdrawn and no alternative lawful basis exists, or where the student account is closed.

OB10: Implement appropriate technical and organisational security measures commensurate with the risk of processing children's voice audio and response history, including: encryption of voice audio in transit and in any transient buffer; immediate secure deletion of audio data after transcription such that it cannot be recovered; access controls ensuring that response history is accessible only to the individual student and authorised personnel; and regular review of security measures.
