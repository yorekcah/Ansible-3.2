# Changelog

## 3.2.0
- Added RKE2 SELinux RPM staging for RHEL 9 air-gapped nodes.
- Added strict Helm dependency-build failure handling.
- Reworked connected-side image discovery to render charts with deployment-aligned values.
- Added bootstrap image archive completeness validation.
- Added Harbor readiness, `library` project validation/creation, seed push validation, and pull-back validation.
- Added offline preflight checks.
- Fixed bundle validator regex and required-RPM checks.
