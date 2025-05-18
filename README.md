# WiFi access point Ansible role v. 0.0.1

[![CI](https://github.com/sv0/ansible-radicale/actions/workflows/ci.yml/badge.svg)](https://github.com/sv0/ansible-radicale/actions/workflows/ci.yml)

- [Getting Started](#getting-started)
- [Prerequisities](#prerequisities)
- [Installing](#installing)
- [Usage](#usage)
- [Testing](#testing)
- [Authors](#authors)
- [License](#license)
- [Useful links](#useful-links)

## Getting Started

This ansible role installs and configures WiFi access point on Debian PC/laptop.

It has been tested for the following Linux distributions:

- Debian Bookworm
- Debian Trixie

## Prerequisities

Ansible 2.14 version installed.

## Installing

```shell

    ansible-galaxy role install sv0.wifiap

```

## Usage

### Variables

Look at [defaults](defaults/main.yml) variables file to see the
possible configuration properties.

```yaml

    # specify network interface
    wifiap_interface: wlan0
    wifiap_bridge: br0
    wifiap_ssid: FreeWiFi  # AP name
    wifiap_password: 'jachcutoheslo'

```

## Testing

```shell

    molecule test

```

## Authors

- [Slavik Svyrydiuk](https://slavik.svyrydiuk.eu/about.html)

## Useful links

TBD
