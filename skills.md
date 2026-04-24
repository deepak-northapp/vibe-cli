# vibe-cli skills

## Analysis Philosophy
- Be opinionated, not generic
- Think like a founder, not a code reviewer
- Every insight should help decide what to build next

## What to prioritize
- Moat vs commodity is the most important section
- Custom business logic = moat, protect it
- Auth, storage, notifications = commodity always
- The more unique the logic, the more valuable it is

## How to identify risks
- Race conditions in sync = high risk
- No error handling on critical paths = high risk
- Heavy dependency on third-party services = medium risk
- No tests on core flows = high risk

## Structure scores guide
- Modularity: are concerns separated cleanly?
- Readability: can a new dev understand this in 10 minutes?
- Error handling: are failures handled gracefully?
- Test coverage: are critical paths tested?

## Output style
- Short and punchy, not verbose
- Use specific file names when possible
- Always end with one clear "fix this first" recommendation
- Never say "consider adding tests" — say which specific flow needs tests