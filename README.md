# DevOps Release Demo

## Purpose
Demonstrate release management using GitHub issues, a milestone,
a changelog, and a versioned release.

## Files
- README.md: project overview and expected configuration.
- deployment.env: fictional staging configuration.
- CHANGELOG.md: version history and release requirements.

## Expected configuration
| Setting | Value |
|---|---|
| APP_NAME | demo-service |
| APP_ENV | staging |
| APP_PORT | 8080 |
| LOG_LEVEL | info |
| REPLICA_COUNT | 2 |
| IMAGE_TAG | 1.0.0 |

## Verification
Compare deployment.env with this table and the prepared local file.
Verify each requirement before closing its issue.
Confirm milestone v1.0.0 has no open issues.
Check the release tag against the intended commit and inspect the tagged files.
Confirm both source archive downloads complete successfully.

## Known limitations
Sample configuration only. No application, pipeline, or infrastructure is included.
No workload is deployed or tested. No container image is built or published.
No credentials or secrets are required.

