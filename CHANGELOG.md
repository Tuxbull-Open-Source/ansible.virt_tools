# Changelog

## v1.0.0 - 2026-10-27

### Changed

- Migrate to `tuxbull.virt_tools` metadata and modern Ansible modules.
- Align the task dispatcher with `joe-speedboat/ansible.template`.
- Select KVM or VMware guest tools from Ansible virtualization facts.

### Verified

- Disposable Rocky Linux 10 KVM lab install, service verification, and
  no-change second converge.
