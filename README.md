# Emergency Net Toolkit

**An open-source framework for building emergency internet networks using locally available hardware and open software.**

Developed by [Jangala](https://janga.la) in collaboration with [SOLE Colombia](https://solecolombia.org) and [Jumpstarting Hope for Gaza](https://jumpstartinghopegaza.org/). This repository provides the practical tools, documentation, and guidance needed to deploy managed internet access in resource-constrained or post-disaster settings, where importing dedicated connectivity hardware is not possible.

---

## Overview

In many crisis zones and underserved areas, access to the internet can be a matter of life, safety, and dignity. Traditional solutions often depend on specialised equipment and global supply chains – both of which are unreliable or unavailable in emergencies.

This project enables communities and responders to build localised, managed Wi-Fi networks using:

- Existing laptop computers as virtual routers
- Surviving or scavenged networking hardware (eg. switches, access points)
- Fabricated directional antennas where needed
- Open-source software (OpenWrt + Jangala’s DeviceCode)

---

## Who Is This For?

- Humanitarian and development actors operating in constrained or conflict settings
- Technically capable local organisations and community networks
- Educators, trainers, and open technology advocates
- Volunteer engineers and digital resilience practitioners

---

## What’s in This Repository

This repository is structured for clarity and usability. Each folder contains materials for a particular aspect of the system:

| Folder | Purpose |
|--------|---------|
| `virtual-router/` | Pre-built virtual machine images and setup guides for using laptops as OpenWrt routers |
| `hardware-guides/` | Instructions for working with VLAN switches, access points, power, and antenna fabrication |
| `site-deployment/` | Step-by-step guidance for planning and rolling out a site-level network |
| `training-materials/` | Slides, printable guides, and training videos for field teams |
| `translations/` | Multilingual versions of key materials (Arabic, Spanish, others as needed) |
| `partners/` | Background on core partners and collaboration notes |
| `devicecode/` | Git submodule linking to Jangala's core router software (DeviceCode) |

---

## Quick Start

1. **Identify local hardware**: You will need at minimum a laptop, switch, and Wi-Fi access point.
2. **Download and load the virtual router**: Use the OpenWrt OVF image from `/virtual-router/openwrt-ovf/`.
3. **Follow the configuration guides**:
   - Set up VLANs and SSIDs
   - Apply shaping and access rules
   - Connect your backhaul (eg. fibre, mobile signal)
4. **Deploy and test**: Use site checklists and troubleshooting forms to validate the setup.

---

## Pedagogical and Field Use

Many elements are designed to support community education and capacity-building:

- Antenna fabrication guides using everyday materials
- Simple diagrams and offline-first resources
- Examples of educational use cases (eg. schools, learning hubs)
- Multilingual video and text-based training content

---

## Contributing

We welcome contributions from the community. This includes:

- Improvements to documentation
- Translations
- New configurations for different hardware types
- Bug reports and field deployment feedback

Please see [`CONTRIBUTING.md`](CONTRIBUTING.md) for details.

---

## Roadmap

Upcoming priorities include:

- Expansion of offline training materials
- Arabic and Spanish full documentation sets
- Integration with CloudControl (for monitoring)
- Sample configurations for mesh and community networks
- Inclusion of localised intranet tools for use during uplink outages

---

## Licence and Attribution

This repository is licensed under the [GPL Licence](LICENSE). All hardware and instructional content is open source, and may be used, adapted, and redistributed under the terms of that licence.

Please credit Jangala, SOLE Colombia, and other contributors where appropriate.

---

## Contacts

- **Jangala** (lead technical partner): [info@janga.la](mailto:info@janga.la)
- **SOLE Colombia** (pedagogical and hardware collaboration): [info@solecolombia.org](mailto:info@solecolombia.org)
- **Jumpstarting Hope for Gaza** (in-Gaza implementation): [TBC]
- **Arava Institute** (coordination): [TBC]

For general enquiries or if you are considering replicating this approach in your own context, we encourage you to [open an issue](https://github.com/jangala-dev/emergency-net-toolkit/issues) or contact us directly.

---

*Last updated: 1 Jul 2025*
