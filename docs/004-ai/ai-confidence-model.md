# AI Confidence Model

FamilyOS should only automate when confidence is high and user permission exists.

## Confidence Thresholds

### 95 to 100 percent

Automate silently where the user has already granted permission.

Example: classify a receipt and attach it to an existing grocery budget.

### 90 to 95 percent

Recommend with one-tap confirmation.

Example: this looks like a school trip letter. Add it to Saachi’s calendar?

### 70 to 90 percent

Ask a clarifying question.

Example: should this document be saved as a warranty or an invoice?

### Below 70 percent

Take no action beyond safe storage.

## Rules

- Never automate irreversible actions.
- Never expose private information without permission.
- Always explain important decisions.
- Always allow users to correct AI.
- Use corrections to improve future behaviour.
