## As-Is Process Map

https://miro.com/app/board/uXjVGl71cSk=/?share_link_id=926618515590

## Current-state analysis summary

The agent
Agents start the day juggling three systems—spreadsheet trackers, the legacy database, and email threads—just to figure out what already happened on an account. The activity tracker shows in just the first 50 records ~25% is duplicated. Outcomes like next_action_unclear leave no usable handoff; each agent starts from scratch. Missing customer data and inconsistent status naming (promise_due, promise due, Awaiting Follow Up) makes even routine cases slow. Escalated cases come back without context, further eroding efficiency and trust in the process.

The customer
Customers get repeatedly contacted from multiple agents who may not know the prior agreements with other agents. Accounts like ACC-10002 show five activity records over two weeks with four different agents. No-reply loops and unstructured follow-ups create persistent pressure. Preferences for SMS, email, or phone are inconsistently applied. The journey is slow, frustrating, and customers cannot see what they owe or what actions are being taken.

The Team Leader
Managers cannot trust the data, statuses are inconsistent across spreadsheets and the legacy system. Follow-ups are often missing and next_action_unclear is common. Cross-referencing activity and account tables (e.g., ACC-10002) exposes these contradictions: resolved in one place, unclear in another. There is no single source of data, making reporting unreliable, decisions slow, and reduces leadership confidence.

## Automation Opportunity List

1. Self-serve account summary

- What it introduces: A portal where customers immediately see their balance, account history, and next steps without contacting an agent.
- Why it works: Reduces agent workload by removing repetitive balance inquiries. Customers get clarity on their accounts and engage agents only when intervention is needed, speeding up recovery.
- Pain points solved: PP1 (Duplicate status checks), PP3 (Missed or delayed follow-up), PP4 (Manual promise-to-pay tracking)

2. Digital promise-to-pay capture

- What it introduces: Automatically generates a structured promise-to-pay agreement (e.g., $10/month for 100 months) and sends it to the customer via email. Signed or acknowledged commitments are recorded automatically.
- Why it works: Eliminates free-text tracking, ensures commitments are actionable, and gives managers real-time visibility. Missed or unclear follow-ups are reduced.
- Pain points solved: PP4 (Manual promise-to-pay tracking), PP3 (Missed or delayed follow-up)

3. Eligible payment-plan selection

- What it introduces: Customers see automated payment options based on outstanding balances: under $1k → balance page, $1–10k → standard plan, above $10k → agent review.
- Why it works: Prioritizes agent time for complex cases, reduces repetitive low-value interactions, and gives customers clear self-service options.
- Pain points solved: PP1 (Duplicate status checks), PP3 (Missed or delayed follow-up), PP4 (Manual promise-to-pay tracking)

4. Contact detail update request

- What it introduces: The portal prompts customers to confirm or update missing/incorrect email, phone, or preferred channel before progressing their case.
- Why it works: Ensures complete case information, reducing failed contacts, missed follow-ups, and manual investigation. Agents can act immediately.
- Pain points solved: PP3 (Missed or delayed follow-up), PP5 (Poor visibility at escalation)

5. Rules-based routing

- What it introduces: Cases are routed automatically based on balance, complexity, and completeness. Incomplete cases cannot escalate.
- Why it works: Prevents managers from receiving unsupported cases, reduces duplication, and ensures resources are used efficiently. Escalation decisions become consistent and reliable.
- Pain points solved: PP1 (Duplicate status checks), PP3 (Missed or delayed follow-up), PP5 (Poor visibility at escalation)

6. Case validation

- What it introduces: A system check that ensures all required context, activity history, and key data fields are complete before escalation.
- Why it works: Eliminates rework loops and frustration caused by incomplete cases. Agents keep control over steps requiring judgment, while the portal removes ambiguity and enforces completeness.
- Pain points solved: PP5 (Poor visibility at escalation), PP3 (Missed or delayed follow-up)

## Traceability Table

https://docs.google.com/spreadsheets/d/1WMvG-gkriVAwclM_JGt-qRjfmiJkDx-UxxG0HQgvLCk/edit?usp=sharing

