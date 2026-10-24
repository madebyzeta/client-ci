# client-ci

A reusable GitHub Actions CI gate for projects consuming `@madebyzeta/zta-infrastructure`. See [`.github/workflows/client-ci.yml`](.github/workflows/client-ci.yml) for the full design notes, and `engineering-wiki/ci/client-ci-gate.mdx` (in the `zta-infrastructure` repo) for how to consume it.

This repo is public only so that GitHub's `workflow_call` mechanism can be used from repositories outside the `madebyzeta` organization (client project repos). See `LICENSE` and `COPYRIGHT` -- this is not an open-source release.
