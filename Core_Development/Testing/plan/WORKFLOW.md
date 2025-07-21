# Testing Workflow: Coverage, Duration, and Flaky Test Handling

## Scenario Test Coverage Tracking
- Scenario and integration tests are tracked in a test matrix (see TEST_MATRIX.md).
- Coverage is reviewed at each milestone; gaps are prioritized for new tests.

## Test Duration Monitoring
- CI records the duration of each test run.
- Slow tests are flagged in CI output; contributors are notified to optimize or parallelize.
- Threshold: Any test exceeding 2x the median duration is flagged for review.

## Flaky Test Handling
- Flaky tests are automatically quarantined (excluded from required checks).
- Contributors must fix or remove flaky tests before merging.
- Use deterministic data and mocks to reduce flakiness. 