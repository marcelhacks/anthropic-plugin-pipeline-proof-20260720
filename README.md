# Controlled plugin-pipeline proof

This repository exercises Anthropic's pinned public bump, policy-scan, and
validation actions against a harmless upstream plugin. The upstream Git LFS
server serves the bump clone, denies the next clone, and serves the following
clone. No production Anthropic identity, API key, repository, or user is used.
