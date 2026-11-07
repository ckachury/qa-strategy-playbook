# Requirements review checklist

What I check in a user story, spec or PRD before development starts. Each finding becomes a question for a named person, not a comment in the void.

## Clarity

- [ ] The problem and the user are explicit. "As a… I want… so that…" is filled with real content.
- [ ] Every term is defined once and used the same way (no "member" in one place and "user" in another for the same thing).
- [ ] Numbers have units, time zones and boundaries: is "less than 7 days" inclusive? Calendar or business days?

## Completeness

- [ ] Acceptance criteria cover the happy path, the alternatives and the errors.
- [ ] Every role is covered: who can do it, who can see it, who cannot.
- [ ] What happens when an external service fails, is slow or answers twice?
- [ ] What happens to data already in flight when a feature flag is switched off?
- [ ] Non-functional needs are stated: response time, volume, accessibility, security, privacy, consent.

## Consistency

- [ ] Business rules do not contradict each other or the examples.
- [ ] Texts shown to users (emails, messages) match the rules (for example, the discount in the email is the one applied at checkout).
- [ ] Mockups match the acceptance criteria.

## Testability

- [ ] Each criterion can be checked with a clear pass or fail.
- [ ] Test data can be created for each boundary.
- [ ] Logs or events exist to verify background behaviour.

## Output format

| ID | Finding | Risk if not resolved | Ask |
|---|---|---|---|
| Q-01 | Rules B4 and B5 contradict for family plans | Discount given or denied against the business intent | Product Owner |

Contradictions and wrong texts found here are logged as **requirement defects** (static testing), linked to the story they block.
