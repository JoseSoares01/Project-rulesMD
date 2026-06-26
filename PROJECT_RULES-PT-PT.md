# AGENT.md

> Good software starts long before the first line of code.

---

# Mission

Your objective is **not** to generate as much code as possible.

Your objective is to make the best engineering decision possible.

Optimize for:

* Simplicity
* Correctness
* Maintainability
* Readability
* Security
* Long-term sustainability

Never optimize for:

* Number of files
* Number of classes
* Cleverness
* Abstractions
* Premature optimization
* "Looks more professional"

Software quality is determined before implementation begins.

---

# Development Lifecycle

Every task follows this order.

```
Understand
    ↓
Validate
    ↓
Decide
    ↓
Reuse
    ↓
Simplify
    ↓
Implement
    ↓
Verify
    ↓
Document
    ↓
Review
```

Never skip steps.

---

# Step 1 — Understand

Before making **any** change:

Understand:

* the problem
* the business goal
* the existing architecture
* affected files
* existing patterns
* constraints

Never assume.

Ask questions if necessary.

---

# Step 2 — Validate

Confirm that the problem actually exists.

Never solve hypothetical problems.

Never optimize without evidence.

Never abstract for future possibilities.

Evidence beats assumptions.

---

# Step 3 — Decision Ladder

Before creating something new, stop at the first rule that solves the problem.

1. Does this need to exist?
2. Can it be removed?
3. Can existing code be reused?
4. Can existing architecture solve it?
5. Can the language solve it?
6. Can the framework solve it?
7. Can an installed dependency solve it?
8. Can it be simplified?
9. Only then implement the minimum solution.

Never skip steps.

---

# Simplicity

Prefer:

* explicit code
* readable code
* boring code
* predictable behavior

Avoid:

* clever code
* magic
* unnecessary abstractions
* hidden behavior

Simple beats smart.

---

# Architecture

Architecture should emerge from complexity.

Never create architecture anticipating complexity.

Don't create:

* repositories
* services
* factories
* builders
* adapters
* interfaces
* DTOs

unless they solve an existing problem.

---

# Dependencies

Every dependency has a permanent cost.

Before installing one ask:

* Can the standard library solve it?
* Can existing code solve it?
* Is this dependency worth maintaining for years?

Prefer removing dependencies.

---

# Reuse

Always prefer:

Reuse

↓

Adapt

↓

Extend

↓

Create

Creation is the last option.

---

# Deletion First

The best refactoring is often deletion.

Whenever possible:

* remove
* simplify
* merge
* consolidate

Instead of:

* adding
* duplicating
* expanding

Every line has a maintenance cost.

---

# Evidence-Based Engineering

Never optimize because you think.

Optimize because you measured.

Never abstract because you might need.

Abstract because you already needed it twice.

Never redesign because it looks cleaner.

Redesign because the current solution became insufficient.

---

# Naming

Names should explain intent.

Good names eliminate comments.

---

# Comments

Do not explain code.

Explain decisions.

Comment:

* business rules
* architectural decisions
* temporary workarounds
* technical debt

Never comment obvious code.

---

# Security

Never trust external input.

Always validate:

* user input
* API payloads
* uploaded files
* external systems

Security is mandatory.

---

# Accessibility

Accessibility is part of quality.

Every UI should support:

* keyboard navigation
* screen readers
* proper labels
* sufficient contrast

---

# Performance

Measure first.

Optimize second.

Never optimize based on assumptions.

---

# Testing

Critical logic must prove itself.

For non-trivial logic leave one runnable verification:

* assertion
* demo
* self-check
* unit test

The smallest possible verification is preferred.

---

# Documentation

Every important change should explain:

* why
* trade-offs
* rejected alternatives
* architectural impact

Future developers should understand the decision.

---

# Review Checklist

Before finishing ask:

✓ Does this solve the real problem?

✓ Can code be removed?

✓ Can complexity be reduced?

✓ Can files be merged?

✓ Can dependencies be avoided?

✓ Is this understandable in one minute?

✓ Would another senior developer write less?

If yes,

simplify again.

---

# Golden Rules

The best code is the code that never had to be written.

The second best code is the code everyone understands.

The best architecture is the one that naturally emerged from real complexity.

The best optimization is deleting unnecessary code.

The best abstraction is the one you never needed.

---

# Final Question

If another experienced developer reads this in two years:

Will they immediately understand why it exists?

If not,

improve the design before writing more code.
