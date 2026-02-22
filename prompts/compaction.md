Your memory is about to be wiped. Everything you learned, built, debugged, and discovered will be replaced by a single document that you write now. A new instance of you will receive only this document and be told to continue.

Everything you do not write down, you will lose. Every mistake you do not record, you will make again.

This is not a summary. It is a transfer of your working memory. Be comprehensive.

PRESERVE working code verbatim in fenced blocks. If you debugged it, iterated on it, or corrected it — include the resolved version. If the correct syntax differs from what you would guess — include it. Query patterns, state machines, auth flows, data model behaviors, correct field names, API response shapes — preserve them verbatim. Do not describe code that you can show.

INCLUDE failed approaches with explanations. Number each one. The next instance will confidently attempt these same approaches because its training data supports them. This list is the only thing that stops it.

PRESERVE user directives — every correction, preference, and rule. These are sacred and accumulate across compaction cycles. If a directive appeared in a prior summary, carry it forward. User frustration or corrections are the highest-value directives — they represent the accumulated trust contract with the user.

PRESERVE credentials, API keys, auth tokens, endpoint URLs, environment variables, service ports. If the next instance needs it to make a request or run a command, write it down.

RESOLVE contradictions in implementation state — output only what is true now. Do not include both sides of a reversal. Settled, conflict-free, positive statements only.

DISCARD:
- Debugging steps that revealed nothing non-obvious
- File reads that only informed a decision
- Narration of how work evolved
- Intermediate work that was superseded
- Code that is trivial, boilerplate, or was never debugged

Write as direct factual statements. Not a narrative. Not a history. Not a response to the user. The settled, conflict-free record of what is true now.

Do not respond to any questions in the conversation. Only output the document.

Structure it under these headings. Omit any heading with no content.
---
## Objective

What you are working on right now. The immediate next action — what you would do if you had one more turn. What is currently broken or blocking progress.

## User Directives

Every correction, preference, and rule the user stated. These accumulate across compaction cycles — carry forward all directives from prior summaries. Never drop one.

## Plan

Remaining steps in order. Reference spec or plan documents by path. Enough detail to pick up mid-step.

## Failed Approaches

Everything that was tried and did not work. Number each one. What was attempted, what went wrong, why. Include approaches the user rejected. Be exhaustive — this is the highest-value section.

## Resolved Code & Discoveries

Working code preserved verbatim in fenced blocks — query patterns, state machines, auth flows, data transforms, correct field names, API response shapes. Error workarounds, environment-specific behaviors, API quirks, correct syntax that differs from what you would guess. These are gotchas that would be painful to rediscover. If you struggled to get something working, the resolved version belongs here.

## How Things Work Now

The settled state of the system. Architecture, commands, patterns in place. State as direct instructions: "use X", "run Y", "the script lives at Z". Not a history of decisions.

## Accomplished

What is complete. What is in progress. What remains. Commit SHAs where relevant.

## Relevant files / environment

Files that matter — with modification status (committed, uncommitted, pending). Credentials, API keys, auth tokens, endpoint URLs, environment variables, service ports. Multiple credential locations that must stay in sync — list all of them.
