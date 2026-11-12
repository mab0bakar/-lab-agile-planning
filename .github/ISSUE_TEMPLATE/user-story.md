---
name: User Story
about: Created a user story template
title: Need a service that has a counter
labels: enhancement
assignees: 'Me'
---

**As a** user
**I need** a service that has a counter
**So that** I can keep track of how many times something has been done

### Details and Assumptions
* The counter service runs separately and persists counts across sessions.
* Users have access to view and update their counter progress.

### Acceptance Criteria
```gherkin
Given a user can view their progress
When the user wants to update the count
Then the application should add to or subtract from the count
