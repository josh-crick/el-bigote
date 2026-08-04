# Project Decisions

A record of important technical and design decisions.

---

## Decision 001 - Use Next.js

Date: 2026-08-01

Decision: Build the website using Next.js rather than WordPress or a website builder.

Reason:

- Learn modern react development
- Build reusable skills
- Greater control over performance
- Strong foundation for future projects

Trade-offs:

- Requires more development knowledge
- More responsibility for maintenance

---

## Decision 002 - Avoid unnecessary tooling

Date: 2026-08-03

Decision: Do not install tools unless they provide clear value.

Example: Prettier was considered but not installed initially.

Reason: The project is being developed by one person who values manual formatting and understanding the code, and keeping the toolchain lightweight.

Trade-offs:

- Formatting consistency relies on developer discipline
- Some automated workflow benefits are not used

---

## Decision 003 - Component-based architecture

Date: 2026-08-03

Decision: Build the website using reusable React components.

Reason:

- Easier maintenance
- Cleaner code organisation
- Allows future expansion
- Creates clear separation of responsibilities

---

## Decision 004 - Prioritise foundations before UI

Date: 2026-08-03

Decision: Create documentation and architecture before building visual components.

Reason:

- Improve consistency
- Reduce rework
- Create a clearer development process