# PROJECT_RULES.md

> Less Code. More Impact.

## Mission

Build software that is simple, sustainable, and easy to evolve.

The goal is not to write more code.

The goal is to solve problems with the least amount of complexity possible.

---

# Mindset

Before implementing any solution:

* Understand the problem.
* Understand the context.
* Understand the business requirements.
* Understand the existing architecture.

Never start by coding.

Start by understanding.

---

# Decision Order

Before creating something new, follow this order:

1. Does this really need to exist?
2. Does it already exist in the project?
3. Can I reuse an existing solution?
4. Can the language solve it natively?
5. Can the framework solve it natively?
6. Can a dependency solve it?
7. Can it be simplified?
8. Only then implement it.

---

# Reuse

Always prefer:

* Reuse
* Adapt
* Extend

Before:

* Creating
* Duplicating
* Rewriting

---

# Dependencies

Every dependency adds:

* Cost
* Complexity
* Risk
* Maintenance

Before installing a dependency, ask:

> Can I solve this without it?

---

# YAGNI

You Aren't Gonna Need It.

Do not implement:

* Future features
* Speculative abstractions
* Generic systems without a real need
* Premature optimizations

Build only what is necessary.

---

# KISS

Keep It Simple.

Prefer:

* Explicit code
* Simple flows
* Small structures
* Predictable components

Avoid:

* Unnecessary layers
* Excessive abstractions
* Accidental complexity

---

# Functions

Every function should:

* Have a clear responsibility
* Be easy to understand
* Be easy to test

If it's difficult to explain, it's probably too complex.

---

# Naming

Names should reveal intent.

Bad:

```js
a()
b()
data2()
```

Good:

```js
calculateInvoice()
getUserProfile()
sendNotification()
```

---

# Comments

Do not explain obvious code.

Only comment:

* Business rules
* Architectural decisions
* Important constraints
* Temporary workarounds

---

# Security

Never trust user input.

Always validate:

* Inputs
* APIs
* Files
* Parameters
* External data

Security is not optional.

---

# Accessibility

Every interface should consider:

* Keyboard navigation
* Screen readers
* Proper contrast
* Correct labels

Accessibility is part of quality.

---

# Performance

Do not optimize based on assumptions.

First:

* Measure
* Identify bottlenecks
* Prove the problem exists

Then:

* Optimize

---

# Database

Before creating:

* Tables
* Columns
* Indexes

Check whether existing structures can be reused.

Avoid duplication.

---

# APIs

APIs should be:

* Consistent
* Predictable
* Versionable
* Well documented

Do not break consumers without a valid reason.

---

# Testing

Validate:

* Main flow
* Error scenarios
* Edge cases
* Business rules

Do not assume it works.

Verify it.

---

# Documentation

Every significant change should explain:

* The problem
* The solution
* The impact
* Added dependencies
* Architectural changes

---

# Checklist Before Coding

* Do I understand the problem?
* Do I understand the context?
* Do I understand the architecture?
* Does this really need to exist?
* Does something similar already exist?
* Can I reuse it?
* Can I simplify it?
* Can I avoid dependencies?

If any answer is "I don't know":

Stop.

Investigate first.

---

# Checklist Before Finishing

* Does it solve the problem?
* Is it simple?
* Is it readable?
* Is it secure?
* Is it accessible?
* Is it documented?
* Is it easy to maintain?

---

# Golden Rule

The best solution is not the one with the fewest lines of code.

The best solution is the simplest one that solves the problem correctly and remains easy to maintain one year from now.

---

# Final Question

If you remove half of this code, does the system still work?

If the answer is yes, consider removing it.
