# Implementation Specification: Restore Canonical Terminology
**Spec ID:** IMPL-2026-02-22-canonical-restoration
**Target:** portussophia-founder/ public files
**Steward:** PeterGate → Peter
**Status:** Ready for execution

---

## Context

Academic usage of "canon" and "canonical" is appropriate and standard. The founder files have frontmatter references but lack body text usage where academically appropriate.

**Academic Definition:**
- **Canon** = authoritative, formally recognized body of work
- **Canonical** = standard form, reference quality, formally verified

Used throughout PortusSophia™ governance layer correctly. Public-facing founder files should align.

---

## Implementation Plan

### File 1: founder-statement.md

**Location 1: Section "Long-Term Intent"**

**Current text:**
```markdown
## Long-Term Intent

The long-term objective is structural durability.

If the architecture cannot scale beyond a single founder without collapsing into authority concentration or symbolic inflation, it has failed.
```

**Replace with:**
```markdown
## Long-Term Intent

The long-term objective is structural durability and canonical integrity.

If the architecture cannot scale beyond a single founder without collapsing into authority concentration or symbolic inflation, it has failed. The canon must remain inspectable, revisable, and resistant to drift.
```

**Rationale:** Reinforces that "canon" means the authoritative body of work, not doctrine. Academically standard.

---

**Location 2: Section "Closing"**

**Current text:**
```markdown
## Closing

I offer this framework not as doctrine, but as disciplined inquiry.

It stands or falls on coherence, constraint integrity, and practical applicability.
```

**Replace with:**
```markdown
## Closing

I offer this framework not as doctrine, but as disciplined inquiry.

The canon stands or falls on coherence, constraint integrity, and practical applicability—not on rhetorical force or symbolic weight.
```

**Rationale:** Explicitly names the canon as the evaluated object. Distinguishes from doctrine.

---

### File 2: problem-statement.md

**Location 1: Section "Verifiable Traceability"**

**Current text:**
```markdown
### 3. Verifiable Traceability

Critical artifacts are version-controlled and cryptographically hash-verifiable.

Auditability is designed into the workflow rather than added post-hoc.
```

**Replace with:**
```markdown
### 3. Verifiable Traceability

Critical artifacts are version-controlled and cryptographically hash-verifiable in their canonical forms.

Auditability is designed into the workflow rather than added post-hoc.
```

**Rationale:** "Canonical forms" is standard academic terminology for reference versions. Aligns with hash verification posture.

---

**Location 2: Section "Evaluation Criteria"**

**Current text:**
```markdown
## Evaluation Criteria

PortusSophia™ should be evaluated on:

- Conceptual coherence
- Structural integrity
- Detectability of drift
- Practical applicability
- Transparency of revision

Not on symbolic density.
```

**Replace with:**
```markdown
## Evaluation Criteria

PortusSophia™ should be evaluated on:

- Conceptual coherence
- Structural integrity
- Canonical traceability
- Detectability of drift
- Practical applicability
- Transparency of revision

Not on symbolic density or rhetorical force.
```

**Rationale:** Adds "canonical traceability" as explicit criterion—academically appropriate for hash-verified work.

---

## Verification Checklist

After implementation, verify:

- [ ] "Canon" and "canonical" usage is academically appropriate
- [ ] No confusion with religious doctrine
- [ ] Terminology aligns with governance layer usage
- [ ] Frontmatter classification ("Canon (Public-Aligned)") remains consistent
- [ ] File hashes updated if tracked

---

## Approval Gate

**Requires explicit user approval before Peter executes.**

---

## Peter Execution Instructions

When approved:

1. Apply replacements using `multi_replace_string_in_file`
2. Include 3-5 lines context before/after for precise matching
3. Update canonical hashes if tracked in ledger
4. Report completion with changed line counts

---

**Specification Complete**
**Awaiting approval for Peter execution**
