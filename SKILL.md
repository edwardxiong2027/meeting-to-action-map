---
name: meeting-to-action-map
description: Transform messy meeting notes into decisions, owners, dates, and unresolved issues that people can follow. Use when: Notes are long, vague, or missing clear next steps.
license: MIT
metadata:
  author: Edward Xiong
  version: 1.0.0
---

# Meeting to Action Map

Transform messy meeting notes into decisions, owners, dates, and unresolved issues that people can follow.

## When to use

Notes are long, vague, or missing clear next steps.

## Workflow

1. Separate decisions from discussion and proposals.
2. Extract actions with explicit owners and dates.
3. Keep unknown owners or deadlines marked as unknown.
4. Create a short follow-up note ready to share.

## Output

Return a usable result for the user’s actual task. State assumptions, evidence, and uncertainty where they affect the result. Keep the output format suited to the job: working HTML, a storyboard, a decision brief, a draft, code, or a short answer. Do not claim that a result was tested, published, or verified unless that action was completed.

## Starter prompt

> Turn these meeting notes into a useful record. Return: purpose, decisions made, action items (task, owner, due date, evidence in notes), open questions, and a concise follow-up message. Label any missing owner/date “unassigned” or “not stated.” Separate a suggestion from an agreed decision. Do not invent commitments. Preserve names and numbers exactly, and flag anything that could change the meaning.

## Quality check

Before delivery, check that the result answers the stated need, follows the requested format, and makes any important limitation visible. Invite the user to adjust the result when taste or judgment belongs to them.
