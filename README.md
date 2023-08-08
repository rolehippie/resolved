# resolved

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&amp;logoColor=white)](https://github.com/rolehippie/resolved)
[![General Workflow](https://github.com/rolehippie/resolved/actions/workflows/general.yml/badge.svg)](https://github.com/rolehippie/resolved/actions/workflows/general.yml)
[![Readme Workflow](https://github.com/rolehippie/resolved/actions/workflows/readme.yml/badge.svg)](https://github.com/rolehippie/resolved/actions/workflows/readme.yml)
[![Galaxy Workflow](https://github.com/rolehippie/resolved/actions/workflows/galaxy.yml/badge.svg)](https://github.com/rolehippie/resolved/actions/workflows/galaxy.yml)
[![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/resolved)](https://github.com/rolehippie/resolved/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/badge/role-rolehippie.resolved-blue)](https://galaxy.ansible.com/rolehippie/resolved)

Ansible role to configure systemd-resolved name resolver.

## Sponsor

Building and improving this Ansible role have been sponsored by my current and previous employers like **[Cloudpunks GmbH](https://cloudpunks.de)** and **[Proact Deutschland GmbH](https://www.proact.eu)**.

## Table of content

- [Requirements](#requirements)
- [Default Variables](#default-variables)
  - [resolved_dhcp_mask](#resolved_dhcp_mask)
  - [resolved_dhcp_name](#resolved_dhcp_name)
  - [resolved_domains](#resolved_domains)
  - [resolved_nameservers](#resolved_nameservers)
  - [resolved_read_etc_hosts](#resolved_read_etc_hosts)
  - [resolved_stub_listener](#resolved_stub_listener)
- [Discovered Tags](#discovered-tags)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Requirements

- Minimum Ansible version: `2.10`


## Default Variables

### resolved_dhcp_mask

Mask DHCP config file

#### Default value

```YAML
resolved_dhcp_mask: true
```

### resolved_dhcp_name

DHCP config file

#### Default value

```YAML
resolved_dhcp_name: isc-dhcp-v4-eth0.conf
```

### resolved_domains

List of search domains

#### Default value

```YAML
resolved_domains: []
```

### resolved_nameservers

List of nameservers

#### Default value

```YAML
resolved_nameservers: []
```

### resolved_read_etc_hosts

Read hosts from /etc/hosts

#### Default value

```YAML
resolved_read_etc_hosts: true
```

### resolved_stub_listener

Enable a listening stub resolver

#### Default value

```YAML
resolved_stub_listener: true
```

## Discovered Tags

**_resolved_**


## Dependencies

- None

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)
