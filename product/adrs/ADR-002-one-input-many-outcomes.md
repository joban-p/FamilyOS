# ADR-002: One Input, Many Outcomes

## Status

Accepted

## Context

Household information often has multiple uses. A receipt may affect spending, budgets, warranty storage and asset history. A school letter may affect calendars, reminders, payments, documents and child profiles.

Traditional software often asks users to enter information separately into multiple places.

## Decision

FamilyOS will follow the principle: one input, many outcomes.

When a user captures something once, FamilyOS should extract every useful outcome that can be produced safely and transparently.

## Consequences

- Capture becomes a core platform capability.
- Automation rules must support multiple downstream actions.
- AI confidence thresholds are required.
- Users should be able to review and reverse important automated actions.
- The Knowledge Graph must store relationships between outcomes.
