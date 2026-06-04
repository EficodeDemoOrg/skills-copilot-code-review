---
description: Perform a thorough code review
agent: ask
---

# Code Review

Perform a thorough code review of the currently selected code.

## Code to Review

${selection}

## Review Checklist

### 1. Correctness
- Does the code do what it's supposed to?
- Are there any logical errors?
- Are edge cases handled?

### 2. Security
- Is user input validated and sanitized?
- Are there SQL injection or XSS vulnerabilities?
- Is sensitive data handled properly?

### 3. Performance
- Are there any N+1 query issues?
- Is there unnecessary computation?

### 4. Readability
- Are names descriptive and consistent?
- Is the code self-documenting?

## Output Format

For each issue found, provide:
- **Severity**: 🔴 Critical / 🟡 Warning / 🔵 Suggestion
- **Line(s)**: Where the issue is
- **Issue**: What's wrong
- **Fix**: How to fix it

End with a summary of the overall code quality.