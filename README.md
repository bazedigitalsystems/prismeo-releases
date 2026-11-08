# Prismeo releases

This repository holds **release downloads only** for Prismeo, a clinic
management app by Baze Digital Systems. It contains no source code.

- Every file is published as a GitHub release asset. Releases are immutable:
  once published, their files cannot be changed or replaced.
- Each release lists the file's size and SHA-256 checksum. GitHub shows the
  same checksum as the asset's digest.
- Prismeo checks the checksum, the package name and the signing certificate
  before it offers to install anything. A file that fails any check is
  deleted and never installed.
- Installation always needs the person's confirmation on the phone.
  Nothing is installed silently.

Releases whose name starts with `test-` are **development test files only**.
They are not Prismeo and must not be installed.

Questions: contact Baze Digital Systems directly. Issues are turned off here.
