# ADR-003: The Household Is the Primary Entity

## Status

Accepted

## Context

Most apps are organised around individual accounts. FamilyOS needs to support shared responsibilities, shared finances, shared events, shared care, shared documents and shared decisions.

The core unit of value is often the household rather than a single user.

## Decision

FamilyOS will treat Household as the primary entity.

People can belong to one or more households and permissions will be scoped around household roles, relationships and shared objects.

## Consequences

- The data model starts with Household.
- People, pets, assets, events, budgets and documents connect to households.
- Permissions must support shared, private and limited-access objects.
- The product must support non-traditional household structures.
