# CivicOS

**CivicOS is a Question Simulation Room for democratic representatives.**

CivicOS helps local representatives turn public records, policy documents, budget materials, council minutes, statistics, and citizen concerns into better questions, stronger follow-ups, alternative viewpoints, and public-facing policy explanations.

> Give every representative an AI policy team.

## Repository description

Question Simulation Room for democratic representatives — an AI policy aide that drafts council questions, predicts government answers, generates follow-ups, and surfaces unasked policy issues.

## Why CivicOS

Democratic representatives are expected to understand complex local issues, read dense administrative documents, question the executive branch, respond to citizens, and explain policy trade-offs to the public.

But many local representatives do not have a policy staff, research team, or data analyst.

CivicOS starts as an AI policy aide for local representatives and grows toward a broader civic intelligence infrastructure for parliamentary democracy.

## Phase 1: Local Representative Aide

The first product is designed for local representatives and policy staff.

A representative uploads documents such as:

- council minutes
- budget documents
- administrative plans
- committee materials
- citizen consultation notes
- local statistics
- policy reports

Then they enter a policy theme, such as:

> How should we strengthen support for children who are not attending school?

CivicOS generates a structured policy workflow:

1. **Question Draft** — a grounded council question with background, evidence, and proposed framing.
2. **Expected Answer** — a simulated answer from the executive or administrative side.
3. **Follow-up Questions** — sharper follow-ups based on the expected answer.
4. **Counterarguments and Risks** — fiscal, operational, legal, ethical, and political risks.
5. **Unasked Questions** — issues that have not yet been sufficiently raised in council discussions.
6. **Alternative Viewpoints** — perspectives from affected residents, frontline staff, fiscal officers, future generations, and dissenting voices.
7. **Policy Memo** — a structured internal memo for decision-making.
8. **Public Report** — resident-facing explanations, newsletter drafts, and social media copy.

## Long-term vision

CivicOS is not intended to replace representatives, councils, or parliaments.

It is designed to help democratic institutions ask better questions.

The long-term roadmap is:

### Phase 1: Local Representative Aide

An AI policy aide for local representatives, helping them prepare questions, follow-ups, policy memos, and public reports.

### Phase 2: Caucus / Party Intelligence

A policy knowledge OS for caucuses, parties, and policy teams, turning past questions, answers, documents, and local evidence into shared policy intelligence.

### Phase 3: Alternative Parliament Layer

An alternative policy intelligence layer for parliaments, think tanks, civil society, and the public — surfacing overlooked issues, minority perspectives, future-generation viewpoints, and alternative policy options.

## Core principles

- **Human-in-the-loop**: AI drafts, humans decide.
- **Explainability**: Outputs should distinguish source-grounded facts from AI reasoning.
- **Auditability**: Every output should be traceable to documents, prompts, models, and agent runs.
- **Political neutrality**: CivicOS supports policy work and democratic accountability, not electioneering.
- **Non-replacement of democracy**: The product augments representatives and public deliberation; it does not replace them.
- **Privacy and safety**: Sensitive citizen information must be handled with caution, minimization, and masking where possible.

## Initial technical direction

The initial implementation is expected to use:

- Next.js App Router
- React
- TypeScript
- PostgreSQL
- pgvector
- Prisma
- Supabase Auth / Storage or local storage adapter
- OpenAI API
- RAG pipeline with citations
- auditable agent pipeline

## Planned product modules

- Document upload and extraction
- Chunking and embeddings
- Vector retrieval
- Question Simulation Room
- Citation side panel
- AI reasoning labels
- Audit Trail
- Editable and approvable generated artifacts

## Pitch demo scenario

A demo scenario may use a fictional municipality, **Sakuragaoka City**, and the policy theme:

> Strengthening support systems for children who are not attending school.

The demo should show a representative uploading education committee materials, budget documents, past council minutes, citizen consultation notes, local statistics, and nearby municipality examples. CivicOS then generates a council question, expected answer, follow-up questions, unasked questions, alternative viewpoints, a policy memo, and a public report with citations and audit logs.

## Status

Early-stage product exploration.

This repository is currently being prepared for the CivicOS Phase 1 prototype.
