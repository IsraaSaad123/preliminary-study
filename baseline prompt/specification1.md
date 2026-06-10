# Regulatory Obligation Specification — Maths Numeracy Speech-Recognition Feature

The following obligations are derived solely from the data protection provisions in
`gdpr_provisions.md`. Each obligation references its provision code (OB1–OB10).

---

OB1: Identify and document a lawful basis under Art. 6 before processing any student
voice audio or response-log data; the applicable basis (e.g., consent or legitimate
educational interest) must be recorded in the controller's processing register and
reviewed if the nature of processing changes.

OB2: Where processing relies on consent, obtain consent that is freely given, specific,
informed, and unambiguous from each student; provide a consent-withdrawal mechanism
that is no more burdensome than the original consent action, and maintain auditable
records of each consent event.

OB3: Because the feature is directed at students who may be below the applicable age
threshold (16 years, or as low as 13 if the relevant Member State has exercised that
derogation), consent for students below that threshold must be given or authorised by
the holder of parental responsibility; the controller must make reasonable technical
efforts to verify such authorisation before any voice or log data are collected.

OB4: Voice audio captured via the device microphone constitutes data with biometric
characteristics; do not process it unless a specific exception under Art. 9(2) applies
(such as the data subject's explicit consent); document the applicable exception in the
processing register, and ensure that audio is not retained or re-used for any
identification purpose.

OB5: Define the purposes of processing voice audio and response logs as (a) real-time
transcription and feedback on maths answers and (b) in-app history review by the
student; do not further process either data type for any purpose incompatible with
those defined purposes (e.g., profiling, advertising, or cross-feature analytics).

OB6: Collect and retain only the data necessary for the stated purposes: the
transcribed answer, the associated question identifier, and a timestamp sufficient for
ordering the history; do not retain raw audio beyond the moment transcription is
complete unless a specific and documented justification exists.

OB7: Retain response-log records (transcribed answers, question identifiers,
timestamps) for no longer than 12 months from the date of creation, after which they
must be deleted or irreversibly anonymised. [retention: 12 months]

OB8: At the point of first microphone activation (and, where OB3 applies, before
obtaining parental authorisation), provide the student and, where required, the holder
of parental responsibility with: (a) the purposes of processing, (b) the lawful basis,
(c) any recipients or processors of the data, and (d) the 12-month retention period
applicable to response logs. [retention: 12 months]

OB9: Provide students and, where applicable, their parents or guardians with a clear
mechanism to request erasure of all stored response-log data; honour valid erasure
requests without undue delay and cease processing where the data are no longer
necessary or where consent is withdrawn and no other lawful basis applies.

OB10: Apply appropriate technical and organisational security measures to voice audio
during transmission and to response logs at rest and in transit, including encryption,
role-based access controls limiting who may view student history, and audit logging of
access to student data.
