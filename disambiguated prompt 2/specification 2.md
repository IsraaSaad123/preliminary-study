# Regulatory Obligation Specification

## Feature: Voice-Based Maths Numeracy Practice

### Feature Description

Students practise basic maths numeracy by speaking answers aloud. The device microphone
captures audio, which is processed by a speech-recognition component solely to transcribe
the spoken numerical content of each answer. Audio is not used to identify or distinguish
individual speakers. All student responses are logged in an in-app history so that
students can review previous attempts and replay lessons.

### Data Processed

| Data item | Source | Purpose |
|---|---|---|
| Raw voice audio | Device microphone | Speech-to-text transcription of numerical answer |
| Transcribed numerical response | Speech recognition output | Immediate feedback; history logging |
| Response history records | Application log | Student self-review of previous attempts |

### Applicable Provisions and Obligations

OB1: The application must identify and document a lawful legal basis (e.g. consent, or
legitimate educational interest) for each processing activity — capture of voice audio,
transcription of spoken answers, and retention of response history — before processing
begins. [retention: n/a]

OB2: Where the chosen legal basis for any processing activity is consent, the application
must obtain freely given, specific, informed, and unambiguous consent from the data
subject prior to processing, record evidence of that consent, and provide a mechanism to
withdraw consent that is as easy to use as the mechanism to give it. [retention: n/a]

OB3: Because the application is directed at students, who may be children, where
processing relies on consent the application must verify the age of the user; for any
user below the age of 16 (or the lower national threshold, which must not be below 13),
consent must be given or explicitly authorised by the holder of parental responsibility,
and the application must make reasonable efforts to verify that such authorisation has
been obtained. [retention: n/a]

OB5: The purposes of processing must be specified, explicit, and legitimate before
collection begins. Voice audio must be processed only for the purpose of transcribing
spoken numerical answers to provide immediate feedback and log responses for student
review; it must not be further processed in a manner incompatible with those stated
purposes. [retention: n/a]

OB6: Only the personal data that is adequate, relevant, and strictly necessary for the
stated purposes may be collected and retained. In particular, raw voice audio must not
be stored beyond the duration required for in-session transcription; only the transcribed
numerical response and associated response-history record may be persisted. [retention: n/a]

OB7: Response history records (transcribed answers, timestamps, and any associated
student identifiers) must be retained for no longer than is necessary for the purpose of
student self-review. Response history records must be deleted no later than 12 months
from the date of collection. [retention: 12 months from the date of collection]

OB8: At the point of data collection (prior to first microphone use and history logging),
the application must provide students and, where OB3 applies, their parent or guardian
with the following information: the identity of the controller; the purposes of
processing; the legal basis for processing; any recipients or categories of recipient;
and the retention period (12 months from the date of collection for response history
records). [retention: 12 months from the date of collection]

OB9: The application must implement a mechanism by which a student, or their parent or
guardian where OB3 applies, can request erasure of all personal data held about them
(including response history records) without undue delay, in particular where consent is
withdrawn or where the data are no longer necessary for the stated purposes. [retention: n/a]

OB10: The application must implement appropriate technical and organisational measures to
protect voice audio during in-session processing and response history records at rest and
in transit, commensurate with the risk to data subjects, including access controls,
encryption, and measures to prevent unauthorised disclosure of student response data.
[retention: n/a]

### Provision Codes Applied

OB1, OB2, OB3, OB5, OB6, OB7, OB8, OB9, OB10

### Provision Codes Not Applied

OB4 — Voice audio in this feature is processed solely to recognise spoken numerical
content and is explicitly not processed to uniquely identify or distinguish individual
speakers. The processing therefore does not constitute processing of biometric data for
the purpose of uniquely identifying a natural person within the meaning of Art. 9, and
the special-category prohibition does not apply.
