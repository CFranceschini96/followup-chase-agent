# Follow-up & Chase Tracker
*Built in Microsoft Copilot Studio*

## The problem
Across a 14+ market network with 10+ active technology partnerships, I'm constantly waiting on replies — from vendors, legal teams, local market leads, and senior stakeholders. Keeping track of who hadn't responded, and when to chase, was eating mental energy and occasionally falling through the cracks.

## What it does
This agent monitors open email threads and flags anything that meets a chase threshold:

- **24-hour flag** — time-sensitive threads (contract approvals, event logistics, partner onboarding steps)
- **48-hour flag** — standard follow-ups (meeting confirmations, feedback requests, information gathering)

When a thread hits the threshold without a reply, I get a Teams notification with the thread summary and a suggested chase message. I review and send manually — the agent handles the memory, I handle the judgment call on whether and how to chase.

## Why it works
I don't want to automate the chase itself — tone matters, especially with senior stakeholders. But I do want to automate the tracking. This separates the memory problem (which the agent solves) from the relationship problem (which I solve).

## Tools used
- Microsoft Copilot Studio
- Outlook (thread monitoring)
- Microsoft Teams (notification output)

## What I learned
The categorisation of urgency matters more than the timing. Early versions flagged everything at the same threshold, which created noise. Building in urgency tiers — based on who sent it and what it's about — made the output actually useful rather than just another thing to manage.
