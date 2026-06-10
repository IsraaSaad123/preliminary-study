# Regulatory Obligation Specification
## Feature: Spoken Maths Numeracy Practice with Response History

The following obligations are derived solely from the data protection provisions
listed in `gdpr_provisions.md` (OB1–OB10). Only provisions that apply to this
feature are listed.

---

OB1: The system must identify and document a lawful basis under Art. 6 for each
distinct processing activity: capturing spoken responses via the device microphone,
performing speech-to-text transcription of those responses, and storing response
history records for student review and lesson replay.

OB2: Where the lawful basis for any processing activity is consent, the system must
obtain freely given, specific, informed, and unambiguous consent from each student
before capturing voice input or storing response history, and must provide a mechanism
to withdraw that consent that is as easy to use as the mechanism by which it was given.

OB3: Because the service is offered directly to students who may be under 16, where
processing relies on consent the system must obtain consent given or authorised by the
holder of parental responsibility for any student below the applicable age threshold
(16 years, or as low as 13 where the relevant Member State has exercised that
derogation), and must make reasonable efforts to verify that such parental authorisation
has been granted before any voice capture or history logging begins.

OB5: Voice recordings, transcriptions, and response-history logs must be collected
solely for the specified purpose of supporting maths numeracy practice and enabling
student self-review of previous attempts; they must not be further processed in any
manner incompatible with that purpose.

OB6: Data collection must be limited to what is adequate and necessary for maths
practice feedback and student review; in particular, raw audio recordings must not be
retained beyond the immediate speech-recognition step unless lesson replay is a
documented functional requirement, in which case only the minimum recording needed
for that replay may be kept.

OB7: Response-history records, including any retained audio recordings and
transcriptions, must be deleted no later than 12 months after the close of the academic
year in which the records were created, or upon closure of the student's account,
whichever is the earlier. [retention: 12 months from the end of the academic year in
which the data were collected, or on account closure, whichever is earlier]

OB8: At the point at which voice input is first collected, the system must provide the
student (and, for students below the consent age, their parent or guardian) with clear
information covering: the purposes of processing, the lawful basis relied upon, any
recipients or categories of recipients of the data, and the applicable retention period.
[retention: 12 months from the end of the academic year in which the data were
collected, or on account closure, whichever is earlier]

OB9: The system must provide a mechanism by which a student, or a parent or guardian
acting on behalf of a student below the consent age, can request erasure of that
student's response-history records and any stored audio recordings; such requests must
be fulfilled without undue delay.

OB10: Voice recordings, transcriptions, and response-history logs must be protected by
appropriate technical and organisational measures commensurate with the nature and
sensitivity of the data and the risk to students, including encryption of data at rest
and in transit and controls restricting access to authorised parties only.
