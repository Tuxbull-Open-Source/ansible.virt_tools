# Repository instructions

This repository provides `tuxbull.virt_tools`. Keep it focused on guest package
and service management. Do not commit inventories, private hypervisor details,
credentials, or lab artifacts. Validate package/service behavior and idempotency
in the default disposable Linux lab. README is usage documentation; CHANGELOG is
release history. After review/merge create an immutable SemVer tag and GitHub
Release, then import and verify pinned/unpinned Galaxy installation.
