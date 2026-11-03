# Engineering notes

## Literal dictation is a separate mode

The implementation documentation separates inserting literal text from planning desktop actions. A dictated phrase that happens to name an application must not automatically become an instruction to open it. Protected or ambiguous fields need a safe fallback rather than an unintended send.

## Typed decisions and explicit execution policy

Model-assisted classification returns structured intent and parameters. Application code retains responsibility for target validation, cancellation, permissions and duplicate prevention. A model proposal alone is not evidence that the requested action completed.

## Context has several sources

Windows accessibility, local visual detections, user-selected screen regions and optional cloud visual requests provide different information. Control names and positions are not equivalent to understanding every screen pixel. A copied text description is not an image attachment.

## Packaging is part of delivery

The private project includes packaging and native QA material, synthetic interaction fixtures and optional provider checks. A passing source test, a published installer and a verified clean-machine installation establish different things. This portfolio update changed documentation only and did not replace release binaries or update metadata.

## Review boundary

The case is based on reviewed private implementation documentation and public release metadata on 2026-11-03. It does not assert unrestricted desktop capability, a measured latency target, current binary-signature verification or successful execution in every Windows application.

[Releases and overview](README.md)
