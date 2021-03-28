# Events for session

* Status: accepted 

## Context and Problem Statement

Some commands are only relevant for the current user on the current system. For example, any settings  what to display and how to filter. As of now, any event triggering a change in the domain object is persisted in the db and replicated to all connected users.

## Decision Outcome

Commands / Object events have an additional field "isTransient". In case this is true, the event is only applied to the domain object but not sent to the server.

### Negative Consequences
The user has to learn that some commands are not persisted and not replicated to other users. Before this ADR, all commands behaved identical.

## Links 

* Refines [0004-event-structure](0004-event-structure-11-01-2021.md)
