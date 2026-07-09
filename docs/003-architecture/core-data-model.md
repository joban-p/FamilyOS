# Core Data Model

FamilyOS should be designed around relationships rather than isolated records.

## Core Entity Types

### Person

Any human connected to the household.

Examples: parent, child, partner, grandparent, teacher, doctor, neighbour, carer.

### Household

The primary container for shared life.

A person can belong to more than one household.

### Pet

A first-class household member with care, health, expenses, documents, and memories.

### Place

A reusable location.

Examples: home, school, work, vet, hospital, airport, holiday destination.

### Thing

A physical or digital item.

Examples: car, passport, boiler, mortgage, TV, insurance policy, birth certificate, warranty.

### Event

Anything happening across time.

Examples: appointment, bill, trip, birthday, school event, vet visit, renewal, project deadline.

### Commitment

Something that creates a future obligation.

Examples: bill due, passport renewal, school form, medication, pet vaccination, savings goal.

### Memory

A meaningful record of family life.

Examples: photos, trips, milestones, achievements, birthdays, renovations.

## Principle

Every entity should be able to connect to people, places, things, events, commitments, documents, money, tasks, and memories.
