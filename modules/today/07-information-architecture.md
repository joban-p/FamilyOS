# 07 Information Architecture

## Purpose

This document defines how information is structured inside the Today surface.

Today should not present all available information. It should organise the most relevant household context into a calm, prioritised daily briefing.

## Primary information goal

Answer this question:

What do I need to know right now?

## Core hierarchy

Today uses a dynamic hierarchy.

### Priority 1: Needs attention now

Examples:

- School handover in 30 minutes.
- Medication due.
- Bill due today.
- Travel delay.
- Appointment requiring preparation.
- Unconfirmed care responsibility.

### Priority 2: Helps today go smoothly

Examples:

- Weather change.
- Traffic suggestion.
- Shopping reminder.
- Packing item.
- Budget update.
- Family availability.

### Priority 3: Improves the future

Examples:

- Savings progress.
- Upcoming renewal.
- Habit nudge.
- Family memory.
- Goal progress.

## Surface sections

### 1. Greeting

A short, time-aware greeting.

Examples:

- Good morning.
- Good afternoon.
- Good evening.

The greeting should never feel forced or overly familiar.

### 2. Daily Brief

A short AI-generated summary of the day.

Rules:

- Maximum three sentences.
- Plain English.
- Prioritise practical value.
- Avoid generic encouragement.
- Explain important context when useful.

### 3. Focus Card

One main item that matters most right now.

Only one Focus Card should appear at a time.

Examples:

- School trip today.
- Hospital appointment.
- Mortgage payment due tomorrow.
- Holiday countdown.
- Co-parenting handover.

### 4. Timeline

A chronological view of today's commitments.

Combines:

- Calendar events.
- Tasks.
- Bills.
- Care responsibilities.
- Travel time.
- School events.
- Pet reminders.
- Weather windows.

### 5. AI Priorities

A maximum of three recommended actions or concerns.

Examples:

- Leave 10 minutes earlier.
- Add PE kit to Oliver's bag.
- Review energy bill tomorrow.

### 6. Family Pulse

Small glanceable cards showing household state.

Possible cards:

- Money.
- Tasks.
- Weather.
- Family availability.
- Mood.
- Pets.
- Goals.
- Upcoming birthdays.

### 7. Quick Capture

A persistent capture entry point.

Supports:

- Voice.
- Photo.
- Scan.
- Receipt.
- Task.
- Note.
- Document.
- Idea.

### 8. Continue

Active workspaces that are not complete.

Examples:

- Holiday planning.
- Insurance renewal.
- Kitchen renovation.
- Birthday party.

### 9. Recent Activity

A calm activity summary, not a social feed.

Examples:

- Alex added milk.
- Energy bill was paid.
- School letter scanned.
- Vet appointment confirmed.

## Adaptive hierarchy by time of day

### Morning

Prioritise preparation, travel, school, work, weather, money and urgent tasks.

### Afternoon

Prioritise tasks, pickup, shopping, appointments, care and schedule changes.

### Evening

Prioritise wrap-up, tomorrow, family time, money and unfinished responsibilities.

### Night

Prioritise calm, minimal display, tomorrow preview and urgent-only items.

## Household state influence

Today should adapt to household state.

Possible states:

- Calm.
- Busy.
- Travel.
- Financial focus.
- Care focus.
- Emergency.
- Celebration.

The state influences ordering, tone, notifications and recommended actions.

## Content suppression rules

Do not show information simply because it exists.

Suppress content when:

- It is not relevant today.
- It has low confidence.
- It duplicates another item.
- It can wait until a weekly review.
- It creates anxiety without clear action.

## Product implication

Today is an editorial surface. It curates, ranks and explains information. It should feel designed, not assembled.
