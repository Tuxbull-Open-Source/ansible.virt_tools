# Ansible virtual guest tools role

Install and enable guest tools for KVM or VMware virtual machines.

## Variables

| Variable | Default | Description |
| --- | --- | --- |
| `virt_tools_install` | `true` | Install and enable guest tools. |
| `virt_tools_hypervisor` | `auto` | `auto`, `kvm`, `vmware`, or `none`. |

In `auto` mode the role selects KVM for Ansible KVM facts and VMware for
VMware facts. Set `none` to make no guest-tool changes.

## Example

```yaml
- hosts: virtual_machines
  become: true
  roles:
    - role: tuxbull.virt_tools
```

## Limitations

The role manages guest packages and services only. It does not install a
hypervisor, configure virtual hardware, or validate host-to-guest integration.
