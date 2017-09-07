# ansible-windows-powercli

An [Ansible](https://www.ansible.com) role to install [VMware PowerCLI](https://blogs.vmware.com/PowerCLI/2017/05/powercli-6-5-1-install-walkthrough.html) on `Windows`.

## Requirements

## Role Variables

## Dependencies

## Example Playbook

```yaml
---
- hosts: test_nodes
  vars:
    pri_domain_name: test.vagrant.local
  roles:
    - role: ansible-windows-powercli
```

## License

MIT

## Author Information

Larry Smith Jr.

-   [@mrlesmithjr](https://www.twitter.com/mrlesmithjr)
-   [EverythingShouldBeVirtual](http://www.everythingshouldbevirtual.com)
-   [mrlesmithjr.com](http://mrlesmithjr.com)
-   mrlesmithjr [at] gmail.com
