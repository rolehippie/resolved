# resolved

[![Build Status](https://cloud.drone.io/api/badges/rolehippie/resolved/status.svg)](https://cloud.drone.io/rolehippie/resolved)

Ansible role to configure resolved

## Table of content

* [Default Variables](#default-variables)
  * [resolved_dhcp_mask](#resolved_dhcp_mask)
  * [resolved_dhcp_name](#resolved_dhcp_name)
  * [resolved_domains](#resolved_domains)
  * [resolved_nameservers](#resolved_nameservers)
  * [resolved_read_etc_hosts](#resolved_read_etc_hosts)
  * [resolved_stub_listener](#resolved_stub_listener)
* [Dependencies](#dependencies)
* [License](#license)
* [Author](#author)

---

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
resolved_read_etc_hosts: yes
```

### resolved_stub_listener

Enable a listening stub resolver

#### Default value

```YAML
resolved_stub_listener: yes
```

## Dependencies

* None

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)
