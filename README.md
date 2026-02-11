# skills-repo

A collection of practical skills for Claude Code.

## Skills

### feedback (critical-acceptance)

Critically evaluate code review feedback with objective principles rather than subjective opinions.

- **Accept**: feedback that aligns with Clean Code, SOLID, and architecture principles
- **Reject**: feedback based on subjective preference with clear rationale
- **Negotiate**: propose alternatives when feedback is partially valid

Uses a structured 6-step evaluation process with reference materials for objective principles, evaluation criteria, and worked examples.

### backend-handoff

Generate structured integration documents from backend code for frontend AI agents.

- Analyzes backend code (routes, models, middleware, config) across any framework
- Outputs a Markdown spec with API endpoints, TypeScript data models, auth flow, error handling, and pagination
- Targets AI agents as readers — goal-oriented, unambiguous, immediately actionable

4-phase workflow: Code Discovery → User Feedback → Document Generation → Validation

## Installation

```bash
claude plugin add -- jhleee/skills-repo
```

## Usage

```
/feedback          # Evaluate code review feedback
/backend-handoff   # Generate frontend integration doc from backend code
```

Skills also trigger automatically when Claude detects matching context.

## Author

jhleee
