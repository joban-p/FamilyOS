# ADR-004: Capture Before Organisation

## Status

Accepted

## Context

People often lose information because apps ask them to categorise, tag or file an item before it is safely stored.

This creates friction at the worst possible moment: when the user is busy and only needs to avoid forgetting something.

## Decision

FamilyOS will always prioritise capture before organisation.

The user should be able to save information first. FamilyOS should organise it afterwards using AI, rules and review queues.

## Consequences

- Capture actions must be fast.
- Mandatory forms should be avoided before initial save.
- Inbox Review exists for uncertain items.
- AI classification happens after the original item is safely stored.
- Original captured content should remain available.
