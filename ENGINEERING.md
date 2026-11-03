# Rivo engineering

## Dictation and actions

Literal dictation is a separate mode. A phrase such as “open Chrome” remains text in that mode. If the target field changes or is protected, the implementation uses a clipboard fallback instead of an unintended send.

## Structured intent, explicit execution

Model-assisted classification returns typed intent and parameters. The application retains target validation, cancellation, permissions and duplicate prevention. Ambiguous targets and changed windows stop an operation.

## Screen context

Windows accessibility, local detections, selected screen regions and optional cloud visual requests provide different information. Control names are not a complete image of the desktop. Copying context as text is distinct from attaching an actual screenshot.

## Delivery

Packaging includes the application runtime while user configuration stays separate. Public release files, update metadata and native QA serve different roles; publishing an installer does not certify all Windows applications or its code-signing status.

[Overview and releases](README.md)
