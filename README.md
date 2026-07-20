# NebCLI

The command-line tool for the NebCore platform. Sign in once; NebCLI brokers
short-lived credentials for `aws`, `kubectl`, `helm`, and `git`, validates Helm
charts, and bootstraps clusters.

This repository hosts the signed `nebcli` release binaries. Installation,
signature verification, authentication, and commands all live in the docs:

- Install: <https://docs.nebcore.ai/installation>
- Authenticate: <https://docs.nebcore.ai/nebcli/authentication>
- Commands: <https://docs.nebcore.ai/nebcli/commands>

Every release is cosign-signed and recorded in the public Sigstore Rekor
transparency log. To report a suspected integrity issue, open a security
advisory from this repository's Security tab.
