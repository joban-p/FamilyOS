# 08 User Flows

## Purpose

This document defines the core flows for the Today surface.

Each flow should be simple, fast and designed to reduce mental load.

## Flow 1: Morning briefing

### Trigger

User opens FamilyOS in the morning.

### Goal

Understand the day quickly.

### Flow

1. User opens FamilyOS.
2. Today loads cached and live household context.
3. The Daily Brief is generated or retrieved.
4. Focus Card appears with the most important item.
5. Timeline shows today's commitments.
6. AI Priorities surface up to three useful actions.
7. User either takes action, captures something or closes the app.

### Success state

User leaves the app feeling prepared.

### Failure risks

- Too much information.
- Irrelevant suggestions.
- Slow loading.
- Summary feels generic.
- Important item is buried.

## Flow 2: Mark preparation item complete

### Trigger

Today surfaces a preparation item such as school kit, packing, paperwork or renewal admin.

### Goal

Complete a small task quickly.

### Flow

1. User sees preparation item.
2. User taps the item.
3. Detail card opens with context.
4. User taps Mark Done.
5. Item completes with subtle feedback.
6. Timeline and Focus Card update if needed.

### Success state

Task is complete with no ambiguity.

### UX rule

Completion should be reversible.

## Flow 3: Capture from Today

### Trigger

User remembers something or receives new information.

### Goal

Capture in under five seconds.

### Flow

1. User taps the persistent capture action.
2. User chooses voice, photo, scan, receipt, note or task.
3. FamilyOS stores the capture immediately.
4. Processing happens in the background.
5. If confidence is high, the item is organised automatically.
6. If confidence is low, it appears in Inbox for review.

### Success state

User trusts that the item is no longer their responsibility to remember.

## Flow 4: Act on AI suggestion

### Trigger

Today presents an AI suggestion.

### Goal

Take a useful next action quickly.

### Flow

1. User reads AI suggestion.
2. Suggestion explains why it matters if needed.
3. User taps primary action or dismisses.
4. FamilyOS updates the relevant module.
5. User receives confirmation.

### Success state

The suggestion feels useful, timely and easy to act on.

### UX rule

Every suggestion must be dismissible.

## Flow 5: Review household activity

### Trigger

User wants to see what changed since they last opened the app.

### Goal

Understand recent updates without reading a noisy feed.

### Flow

1. User scrolls to Recent Activity.
2. Activity is grouped by meaningful updates.
3. User taps an item for details if needed.
4. User returns to Today without losing scroll position.

### Success state

User understands what changed without feeling distracted.

## Flow 6: Quiet day

### Trigger

There are no urgent or important items.

### Goal

Reassure the user rather than fill space.

### Flow

1. User opens Today.
2. Today shows a calm empty state.
3. Optional low-pressure suggestions appear.
4. User may capture, review tomorrow or close the app.

### Success state

User feels everything is under control.

## Flow 7: Urgent item

### Trigger

A high-priority household commitment requires attention.

Examples:

- Pickup conflict.
- Time-sensitive bill.
- Travel delay.
- Important appointment.
- Missing preparation item.

### Goal

Make the urgent item impossible to miss without causing panic.

### Flow

1. User opens Today or receives a heads-up.
2. Urgent item appears as the Focus Card.
3. Clear action is shown.
4. User acts, assigns, reschedules or dismisses with reason.
5. FamilyOS updates household state.

### Success state

User understands the issue and the next action.

## Flow 8: Evening wrap-up

### Trigger

User opens FamilyOS in the evening.

### Goal

Review unfinished items and prepare for tomorrow.

### Flow

1. Today adapts to evening mode.
2. Completed items are summarised lightly.
3. Unfinished items are grouped.
4. User can move tasks to tomorrow, mark done or dismiss.
5. Tomorrow preview appears.

### Success state

User ends the day with fewer loose ends.

## Cross-flow principles

- Never require unnecessary typing.
- Keep primary actions obvious.
- Always preserve context when navigating.
- Support undo for meaningful actions.
- Avoid creating more tasks than necessary.
- Prioritise clarity over feature depth.
