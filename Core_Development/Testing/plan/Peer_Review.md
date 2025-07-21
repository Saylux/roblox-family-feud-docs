# Peer Review – Testing

## Tech Lead Review Comments
- [2024-07-21] Tech Lead: Are we missing coverage for integration or scenario tests that span multiple services/modules?
- [2024-07-21] Tech Lead: Is the test suite fast enough to support rapid iteration, or are there slowdowns as the codebase grows?
- [2024-07-21] Tech Lead: How do we ensure test reliability and avoid flaky tests, especially with agent-based or scenario tests?

## Staff Software Engineer Responses
- [2024-07-21] Staff SE: We are expanding scenario tests using TestEZ and TestService; coverage is tracked and reviewed each milestone.
- [2024-07-21] Staff SE: Test runs are monitored for duration; slow tests are flagged and optimized or parallelized.
- [2024-07-21] Staff SE: Flaky tests are quarantined and must be fixed before merging; we use deterministic data and mocks where possible.

## Action Log
- [2024-07-21] Added scenario test coverage tracking to test plan.
- [2024-07-21] Set up test duration monitoring in CI.

## Review Frequency
- Next scheduled review: 2024-10-21
- Last reviewed: 2024-07-21

## Reviewer Rotation
- Tech Lead: Samir Patel
- Staff Software Engineer: Morgan Lee 