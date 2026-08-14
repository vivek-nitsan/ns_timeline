# AI Issue Resolver Rules

## General

- Never modify main directly.
- Always work on an issue-specific branch.
- Keep changes minimal.
- Do not make unrelated changes.
- Do not perform unrelated refactoring.
- Follow the existing project architecture and coding style.

## Issue Triage

Before changing code:

1. Read the complete GitHub Issue.
2. Read AGENTS.md.
3. Inspect the relevant repository code.
4. Determine whether the reported behavior is actually incorrect.
5. Do not guess when information is missing.

## Classification

Every issue must be classified as exactly one of:

### VALID_ISSUE

A real bug, defect, regression, or valid development request requiring a code change.

### NOT_AN_ISSUE

The current behavior is correct, or the request is a question, support request, or documentation request.

Do not modify code.

### NEEDS_INFORMATION

The issue may be valid, but there is not enough information to safely investigate or implement a fix.

Do not modify code.

## VALID_ISSUE

When the issue is valid:

1. Identify the root cause.
2. Implement the smallest correct solution.
3. Follow the existing architecture and coding style.
4. Add or update tests when appropriate.
5. Run relevant tests.
6. Fix failures caused by your changes.
7. Review the final diff.

## Git

- Never modify main directly.
- Never merge a Pull Request.
- Never push unrelated changes.
- Work only on the issue-specific branch.

## Pull Request

The PR should contain:

- Problem
- Root cause
- Files changed
- Changes made
- Tests executed
- Test results

## Issue

Never modify the original GitHub Issue title or description.

Only add comments when communication with the reporter is required.