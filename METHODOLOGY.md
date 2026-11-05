# Outbound design review and methodology

This page develops the reasoning used to evaluate the located LinkedIn workflow reference. Personal authorship, customisation and execution remain unverified. The methodology below is an assessment framework and proposed development direction; it is not evidence that these controls are implemented in the reference.

## Begin with relevance rather than activity

An outbound system should help a salesperson explain why a particular person might be worth contacting. Producing more profiles or more messages does not answer that question.

The starting point is a specific audience and a reason that audience might care about the offering. Public job titles and company descriptions may help narrow research, but they do not establish a person's authority, current priorities or interest in a conversation.

## Treat the audience description as a hypothesis

The located reference begins with a plain-English audience description. This can make a workflow approachable for a sales user, but it also creates interpretation risk: a broad or ambiguous description can produce a target list that looks plausible while missing the intended market.

A sound evaluation would compare the resulting audience with the original commercial intention. The operator needs to understand why the suggested profiles belong in the list, not only whether the search returned results.

## Separate target selection from message quality

A well-written message can still target the wrong person. Conversely, a relevant person may receive a generic message that gives no reason to respond. These are separate problems and should be tested separately.

For selection, the questions concern audience fit, identity, source quality and relevance. For drafting, the questions concern whether the message uses verified context, assumes an unconfirmed problem or asks something the recipient could usefully answer.

Calling a message personalised is not sufficient. Adding a name or a company reference does not establish that the underlying question is commercially meaningful.

## Keep assumptions visible

Role descriptions and public information are incomplete. They may not reveal the person's responsibilities, buying process or current need. Those gaps should become qualification questions rather than confident claims in a message.

An evaluation should look for invented pain, unsupported urgency and claims about systems or priorities that have not been established. The aim is a credible reason to start a conversation, not to manufacture evidence that someone wants to buy.

## Inspect the action boundary

The located file includes a handoff to an external outreach agent. Its presence changes the risk of the workflow: preparation may lead to an external action. No verified approval gate or draft-only operating mode has been established for this reference.

Before operation could be presented as a completed personal project, the operator would need to establish exactly what the handoff does, what permissions it uses and how review and stopping controls work. This review has not operated or modified that handoff.

That limitation is deliberately retained in the portfolio rather than replaced with an unsupported claim of safe automation.

## Evaluate the commercial outcome in stages

A useful test sequence would first check that the intended audience is represented, then inspect the relevance and factual support of draft messages, and finally verify any external action under separately authorised conditions. Structural inspection of a workflow export establishes none of those outcomes by itself.

| Evaluation question | Why it matters | Current evidence |
|---|---|---|
| Does the audience match the commercial intention? | Prevents irrelevant targeting | Not tested |
| Is each draft grounded in verified context? | Avoids misleading personalisation | Not tested |
| Is the external action understood and controlled? | Establishes the preparation-to-action boundary | External-agent reference found; controls unverified |
| What was personally changed or built? | Makes attribution defensible | Not established |
| Did the workflow improve replies or meetings? | Distinguishes technical activity from commercial value | No outcome evidence found |

## What can currently be claimed

A reference file was located and its high-level structure was inspected. Its intended path covers audience input, search preparation, profile retrieval, message drafting, spreadsheet recording and an external-agent handoff.

The next step is to establish provenance and personal contribution, then obtain implementation and test evidence. Until then, this is a transparent design review within the portfolio, rather than proof of a completed original outreach system.

[Project status](README.md) · [Conceptual architecture](architecture.md)
