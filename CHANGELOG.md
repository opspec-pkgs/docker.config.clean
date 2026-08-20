## [Unreleased]

## [1.1.1] - 2026-08-20

### Changed

- Pin the jq docker image to `backplane/jq:20260603` rather than tracking `latest`, so runs of this op are
  reproducible and unaffected by upstream rebuilds of the image.

## [1.1.0] - 2024-05-15

### Changed

- Default jq docker image to backplane/jq
