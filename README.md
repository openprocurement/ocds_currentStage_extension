# Current Stage
The extension shows current stage of tender.

## Overview
The field introduced by this extension is:
- `tender/currentStage` - The current stage of tender.
It should be one of these values: `draft`, `active.enquiries`, 
`active.tendering`, `active.auction`, `active.pre-qualification`,
`active.pre-qualification.stand-still`, `active.qualification`,
`active.awarded`, `active.stage2.pending`, `active.stage2.waiting`,
`complete`,`cancelled`, `unsuccessful`.
## Examples
The following extract illustrates this property in use within the `tender` block.
```.env
{
    "tender": {
        "id": "ocds-213czf-lots-00001-01-tender",
        "title": "Architecture and engineering services",
        "currentStage": "active.pre-qualification"
    }
}
```