# soren-loop-e2e

Sandbox-only home of the nightly end-to-end smoke test for
[soren-loop](https://github.com/sorenai-dev/soren-loop).

The test runs against the private `sorenai-dev-sandbox/soren-loop-demo` app. Its workflow runs only on
a schedule or a manual trigger, never on pull requests, and every run waits for owner approval in the
protected `e2e` environment before it can read the Claude credential.

Nothing here is published or used outside the sandbox.
