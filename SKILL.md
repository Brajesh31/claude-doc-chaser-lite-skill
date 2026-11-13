---
name: doc-chaser-lite
description: Draft one polite, accurate client document-request reminder from a supplied practice profile and a single client brief. Use for professional document follow-ups, not for sending messages or giving tax, legal, or accounting advice.
---

# Document Follow-Up Drafting

## Purpose
Create one concise, courteous document-request email for one client at a time. The output is a draft for human review, never an automatically sent message.

## Required inputs
Read the practice profile template and one client brief. Required fields:
- Practice name and sender name.
- Sender role or credential, if the user wants it displayed.
- Approved contact details for the signature.
- Client name, initials, or internal case reference.
- Engagement type.
- Exact outstanding document list.
- Due date supplied by the user or practice.

If a required field is missing, ask one concise clarification round. Never infer a deadline, document requirement, client status, fee, penalty, or consequence.

## Drafting rules
1. Draft one email for one client per request.
2. Use a calm, professional, helpful tone.
3. Keep the subject specific and concise.
4. Preserve document names and due dates exactly as supplied.
5. Make the requested next action obvious.
6. Use only contact details present in the practice profile.
7. Do not include legal, tax, or accounting conclusions.
8. Do not claim that a document was received, reviewed, filed, or approved unless the brief confirms it.
9. Do not threaten consequences or invent escalation language.
10. Do not send the email. Return a draft only.

## Output format
Return:
- Subject
- Email body
- A short internal review note listing missing or ambiguous details, or stating that none were identified.

Keep the client-facing email separate from internal notes. Do not expose internal notes in the email body.

## Privacy and safety
Treat client briefs as confidential. Use only the minimum identifying information needed. Prefer initials or a case ID when a full name is unnecessary. Do not reproduce bank details, tax identifiers, passwords, or other sensitive data in the email unless the user explicitly requires it and it is essential.

## Supporting files
- guard.md: final safety and accuracy checks.
- brief-template.md: one-client input format.
- profile-template.md: practice identity and signature details.
- examples/: illustrative input and output.

If the requested task requires batch reminders, formal notices, legal explanations, or professional advice, explain that this skill only drafts a single routine reminder and ask how the user wants to proceed.