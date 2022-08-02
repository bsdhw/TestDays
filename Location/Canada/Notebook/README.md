BSD in Canada - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for BSD in Canada.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
  - [ OS                       ](#os)
  - [ OS Family                ](#os-family)
  - [ Arch                     ](#arch)
  - [ DE                       ](#de)
  - [ Display Server           ](#display-server)
  - [ Display Manager          ](#display-manager)
  - [ OS Lang                  ](#os-lang)
  - [ Boot Mode                ](#boot-mode)
  - [ Filesystem               ](#filesystem)
  - [ Part. scheme             ](#part-scheme)

* [ Board ](#board)
  - [ Vendor                   ](#vendor)
  - [ Model                    ](#model)
  - [ Model Family             ](#model-family)
  - [ MFG Year                 ](#mfg-year)
  - [ Form Factor              ](#form-factor)
  - [ Coreboot                 ](#coreboot)
  - [ RAM Size                 ](#ram-size)
  - [ RAM Used                 ](#ram-used)
  - [ Total Drives             ](#total-drives)
  - [ Has CD-ROM               ](#has-cd-rom)
  - [ Has Ethernet             ](#has-ethernet)
  - [ Has WiFi                 ](#has-wifi)
  - [ Has Bluetooth            ](#has-bluetooth)

* [ Location ](#location)
  - [ Country                  ](#country)
  - [ City                     ](#city)

* [ Drives ](#drives)
  - [ Drive Vendor             ](#drive-vendor)
  - [ Drive Model              ](#drive-model)
  - [ HDD Vendor               ](#hdd-vendor)
  - [ SSD Vendor               ](#ssd-vendor)
  - [ Drive Kind               ](#drive-kind)
  - [ Drive Connector          ](#drive-connector)
  - [ Drive Size               ](#drive-size)
  - [ Space Total              ](#space-total)
  - [ Space Used               ](#space-used)
  - [ Malfunc. Drives          ](#malfunc-drives)
  - [ Malfunc. Drive Vendor    ](#malfunc-drive-vendor)
  - [ Malfunc. HDD Vendor      ](#malfunc-hdd-vendor)
  - [ Malfunc. Drive Kind      ](#malfunc-drive-kind)
  - [ Failed Drives            ](#failed-drives)
  - [ Failed Drive Vendor      ](#failed-drive-vendor)
  - [ Drive Status             ](#drive-status)

* [ Storage controller ](#storage-controller)
  - [ Storage Vendor           ](#storage-vendor)
  - [ Storage Model            ](#storage-model)
  - [ Storage Kind             ](#storage-kind)

* [ Processor ](#processor)
  - [ CPU Vendor               ](#cpu-vendor)
  - [ CPU Model                ](#cpu-model)
  - [ CPU Model Family         ](#cpu-model-family)
  - [ CPU Cores                ](#cpu-cores)
  - [ CPU Sockets              ](#cpu-sockets)
  - [ CPU Threads              ](#cpu-threads)
  - [ CPU Microarch            ](#cpu-microarch)

* [ Graphics ](#graphics)
  - [ GPU Vendor               ](#gpu-vendor)
  - [ GPU Model                ](#gpu-model)
  - [ GPU Combo                ](#gpu-combo)
  - [ GPU Driver               ](#gpu-driver)
  - [ GPU Memory               ](#gpu-memory)

* [ Monitor ](#monitor)
  - [ Monitor Vendor           ](#monitor-vendor)
  - [ Monitor Model            ](#monitor-model)
  - [ Monitor Resolution       ](#monitor-resolution)
  - [ Monitor Diagonal         ](#monitor-diagonal)
  - [ Monitor Width            ](#monitor-width)
  - [ Aspect Ratio             ](#aspect-ratio)
  - [ Monitor Area             ](#monitor-area)
  - [ Pixel Density            ](#pixel-density)
  - [ Multiple Monitors        ](#multiple-monitors)

* [ Network ](#network)
  - [ Net Controller Vendor    ](#net-controller-vendor)
  - [ Net Controller Model     ](#net-controller-model)
  - [ Wireless Vendor          ](#wireless-vendor)
  - [ Wireless Model           ](#wireless-model)
  - [ Ethernet Vendor          ](#ethernet-vendor)
  - [ Ethernet Model           ](#ethernet-model)
  - [ Net Controller Kind      ](#net-controller-kind)
  - [ Used Controller          ](#used-controller)
  - [ NICs                     ](#nics)
  - [ IPv6                     ](#ipv6)

* [ Bluetooth ](#bluetooth)
  - [ Bluetooth Vendor         ](#bluetooth-vendor)
  - [ Bluetooth Model          ](#bluetooth-model)

* [ Sound ](#sound)
  - [ Sound Vendor             ](#sound-vendor)
  - [ Sound Model              ](#sound-model)

* [ Memory ](#memory)
  - [ Memory Vendor            ](#memory-vendor)
  - [ Memory Model             ](#memory-model)
  - [ Memory Kind              ](#memory-kind)
  - [ Memory Form Factor       ](#memory-form-factor)
  - [ Memory Size              ](#memory-size)
  - [ Memory Speed             ](#memory-speed)

* [ Printers & scanners ](#printers--scanners)
  - [ Printer Vendor           ](#printer-vendor)
  - [ Printer Model            ](#printer-model)
  - [ Scanner Vendor           ](#scanner-vendor)
  - [ Scanner Model            ](#scanner-model)

* [ Camera ](#camera)
  - [ Camera Vendor            ](#camera-vendor)
  - [ Camera Model             ](#camera-model)

* [ Security ](#security)
  - [ Fingerprint Vendor       ](#fingerprint-vendor)
  - [ Fingerprint Model        ](#fingerprint-model)
  - [ Chipcard Vendor          ](#chipcard-vendor)
  - [ Chipcard Model           ](#chipcard-model)

* [ Unsupported ](#unsupported)
  - [ Unsupported Devices      ](#unsupported-devices)
  - [ Unsupported Device Types ](#unsupported-device-types)


Test Cases
----------

Total: 85

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Intel         | H81U                        | [8f50dbe259](https://bsd-hardware.info/?probe=8f50dbe259) | Aug 01, 2022 |
| Dell          | Latitude E7440              | [03497b7b2a](https://bsd-hardware.info/?probe=03497b7b2a) | Jul 27, 2022 |
| Lenovo        | IdeaPad Y580 20132          | [3df3bd2f62](https://bsd-hardware.info/?probe=3df3bd2f62) | Jul 22, 2022 |
| Dell          | Studio 1747                 | [7ae292b282](https://bsd-hardware.info/?probe=7ae292b282) | May 21, 2022 |
| Dell          | Inspiron 5559               | [a7111b84cb](https://bsd-hardware.info/?probe=a7111b84cb) | May 08, 2022 |
| Fujitsu       | LIFEBOOK E752               | [3e60a82218](https://bsd-hardware.info/?probe=3e60a82218) | May 06, 2022 |
| ASUSTek       | 1000HE                      | [a6393754b4](https://bsd-hardware.info/?probe=a6393754b4) | May 05, 2022 |
| Matsushita... | CF-48V4KNDQM                | [774cab5326](https://bsd-hardware.info/?probe=774cab5326) | May 03, 2022 |
| Matsushita... | CF-51RCVDNLM                | [4b1abdd507](https://bsd-hardware.info/?probe=4b1abdd507) | May 03, 2022 |
| Lenovo        | ThinkPad T410 2537N24       | [2884106c6b](https://bsd-hardware.info/?probe=2884106c6b) | May 03, 2022 |
| Lenovo        | ThinkPad T430 2347GZU       | [00ba6ca9f8](https://bsd-hardware.info/?probe=00ba6ca9f8) | May 03, 2022 |
| Lenovo        | ThinkPad T420s 41742BU      | [6b77fe651f](https://bsd-hardware.info/?probe=6b77fe651f) | May 03, 2022 |
| Lenovo        | ThinkPad X220 429043U       | [f3c30a6190](https://bsd-hardware.info/?probe=f3c30a6190) | May 02, 2022 |
| Panasonic     | CF-53AAGHYDM                | [abd8754907](https://bsd-hardware.info/?probe=abd8754907) | May 01, 2022 |
| Panasonic     | CF-52PFPBSFQ                | [1ce63e2214](https://bsd-hardware.info/?probe=1ce63e2214) | Apr 29, 2022 |
| Toshiba       | Satellite Pro T130          | [62dd51afcf](https://bsd-hardware.info/?probe=62dd51afcf) | Apr 11, 2022 |
| Intel         | H81U                        | [71068a0577](https://bsd-hardware.info/?probe=71068a0577) | Mar 01, 2022 |
| Lenovo        | ThinkPad X250 20CL001GUS    | [4ae2360503](https://bsd-hardware.info/?probe=4ae2360503) | Jan 11, 2022 |
| Toshiba       | TECRA Z40-B                 | [d498fcd3f8](https://bsd-hardware.info/?probe=d498fcd3f8) | Jan 02, 2022 |
| ASUSTek       | U31SD                       | [a07366611d](https://bsd-hardware.info/?probe=a07366611d) | Jan 02, 2022 |
| ASUSTek       | TUF GAMING FX504GD_FX80G... | [259b5cc7b2](https://bsd-hardware.info/?probe=259b5cc7b2) | Dec 28, 2021 |
| Lenovo        | ThinkPad X280 20KF001UUS    | [5b9001009e](https://bsd-hardware.info/?probe=5b9001009e) | Dec 20, 2021 |
| Lenovo        | ThinkPad T420s 41742BU      | [a86326d049](https://bsd-hardware.info/?probe=a86326d049) | Dec 11, 2021 |
| Lenovo        | ThinkPad X220 429043U       | [339779baad](https://bsd-hardware.info/?probe=339779baad) | Nov 26, 2021 |
| Dell          | Studio 1747                 | [b0a51ac0af](https://bsd-hardware.info/?probe=b0a51ac0af) | Nov 11, 2021 |
| Dell          | Studio 1747                 | [7ab6b58d69](https://bsd-hardware.info/?probe=7ab6b58d69) | Nov 11, 2021 |
| Panasonic     | CF-53AAGHYDM                | [721ef0235c](https://bsd-hardware.info/?probe=721ef0235c) | Oct 30, 2021 |
| Matsushita... | CF-48V4KNDQM                | [9e254ab443](https://bsd-hardware.info/?probe=9e254ab443) | Oct 23, 2021 |
| ASUSTek       | 1000HE                      | [1d5e3e5bc3](https://bsd-hardware.info/?probe=1d5e3e5bc3) | Oct 22, 2021 |
| Lenovo        | ThinkPad T430 2347GZU       | [3337c00433](https://bsd-hardware.info/?probe=3337c00433) | Oct 22, 2021 |
| Dell          | Studio 1747                 | [ed704cde92](https://bsd-hardware.info/?probe=ed704cde92) | Oct 20, 2021 |
| Dell          | Studio 1747                 | [ca939fbe2f](https://bsd-hardware.info/?probe=ca939fbe2f) | Oct 19, 2021 |
| Matsushita... | CF-51RCVDNLM                | [b20953f2f4](https://bsd-hardware.info/?probe=b20953f2f4) | Oct 18, 2021 |
| Panasonic     | CF-52PFPBSFQ                | [bbdfde368b](https://bsd-hardware.info/?probe=bbdfde368b) | Oct 18, 2021 |
| Lenovo        | ThinkPad T410 2537N24       | [1a5bae2227](https://bsd-hardware.info/?probe=1a5bae2227) | Oct 15, 2021 |
| HP            | Notebook                    | [a3c3297cd2](https://bsd-hardware.info/?probe=a3c3297cd2) | Aug 08, 2021 |
| HP            | Notebook                    | [0c316107a4](https://bsd-hardware.info/?probe=0c316107a4) | Aug 08, 2021 |
| Gigabyte      | MMLP3AP-00                  | [168e674b55](https://bsd-hardware.info/?probe=168e674b55) | Jul 03, 2021 |
| Dell          | Inspiron 15-7579            | [4b8b5f7918](https://bsd-hardware.info/?probe=4b8b5f7918) | Jun 19, 2021 |
| LG Electro... | E500-GP01A9                 | [7db1345e97](https://bsd-hardware.info/?probe=7db1345e97) | Jun 17, 2021 |
| LG Electro... | E500-GP01A9                 | [cbade775b6](https://bsd-hardware.info/?probe=cbade775b6) | Jun 17, 2021 |
| LG Electro... | E500-GP01A9                 | [80052d6cdc](https://bsd-hardware.info/?probe=80052d6cdc) | Jun 15, 2021 |
| Dell          | Inspiron 15-3567            | [d239ee4916](https://bsd-hardware.info/?probe=d239ee4916) | Jun 12, 2021 |
| Apple         | PowerBook5,2                | [8cc0aab53c](https://bsd-hardware.info/?probe=8cc0aab53c) | May 31, 2021 |
| Panasonic     | CF-53AAGHYDM                | [ef5e9ec095](https://bsd-hardware.info/?probe=ef5e9ec095) | May 18, 2021 |
| Panasonic     | CF-52PFPBSFQ                | [65f5931910](https://bsd-hardware.info/?probe=65f5931910) | May 18, 2021 |
| Lenovo        | ThinkPad T430 2347GZU       | [1e9f399d73](https://bsd-hardware.info/?probe=1e9f399d73) | May 17, 2021 |
| Lenovo        | ThinkPad T410 2537N24       | [109f3afa21](https://bsd-hardware.info/?probe=109f3afa21) | May 17, 2021 |
| ASUSTek       | 1000HE                      | [f92f43bc54](https://bsd-hardware.info/?probe=f92f43bc54) | May 17, 2021 |
| Matsushita... | CF-51RCVDNLM                | [33bc82e701](https://bsd-hardware.info/?probe=33bc82e701) | May 17, 2021 |
| Matsushita... | CF-48V4KNDQM                | [bf76401b74](https://bsd-hardware.info/?probe=bf76401b74) | May 17, 2021 |
| Dell          | Latitude 3440               | [3c8d21772a](https://bsd-hardware.info/?probe=3c8d21772a) | May 01, 2021 |
| Dell          | Latitude 3440               | [7e85a38390](https://bsd-hardware.info/?probe=7e85a38390) | Apr 04, 2021 |
| ASUSTek       | G75VW                       | [9b84d1e7e6](https://bsd-hardware.info/?probe=9b84d1e7e6) | Mar 24, 2021 |
| ASUSTek       | G75VW                       | [cf4b3e0c6f](https://bsd-hardware.info/?probe=cf4b3e0c6f) | Mar 23, 2021 |
| ASUSTek       | G75VW                       | [4a59793120](https://bsd-hardware.info/?probe=4a59793120) | Mar 23, 2021 |
| Dell          | Inspiron 7370               | [7e2328dda3](https://bsd-hardware.info/?probe=7e2328dda3) | Mar 20, 2021 |
| Apple         | MacBookPro5,5               | [f46146b79e](https://bsd-hardware.info/?probe=f46146b79e) | Mar 11, 2021 |
| Apple         | MacBookPro5,5               | [c1ed4c02b8](https://bsd-hardware.info/?probe=c1ed4c02b8) | Mar 11, 2021 |
| Alienware     | 14                          | [0e0cdf952a](https://bsd-hardware.info/?probe=0e0cdf952a) | Mar 06, 2021 |
| Toshiba       | Satellite U500              | [feae098542](https://bsd-hardware.info/?probe=feae098542) | Feb 20, 2021 |
| Lenovo        | ThinkPad T410 253722U       | [219e9cb1d7](https://bsd-hardware.info/?probe=219e9cb1d7) | Feb 10, 2021 |
| Intel         | H81U                        | [efb1f9d207](https://bsd-hardware.info/?probe=efb1f9d207) | Feb 07, 2021 |
| Alienware     | 14                          | [dd2cc000a7](https://bsd-hardware.info/?probe=dd2cc000a7) | Jan 07, 2021 |
| Alienware     | 14                          | [48f61623f2](https://bsd-hardware.info/?probe=48f61623f2) | Jan 07, 2021 |
| HP            | EliteBook 840 G3            | [11011ecee1](https://bsd-hardware.info/?probe=11011ecee1) | Jan 02, 2021 |
| Lenovo        | ThinkPad T440 20B7S0A800    | [d3474f1ca3](https://bsd-hardware.info/?probe=d3474f1ca3) | Nov 18, 2020 |
| Lenovo        | ThinkPad T490 20N3S8PB00    | [6a0f910601](https://bsd-hardware.info/?probe=6a0f910601) | Nov 10, 2020 |
| Lenovo        | ThinkPad T490 20N3S8PB00    | [6dca4cdd18](https://bsd-hardware.info/?probe=6dca4cdd18) | Nov 10, 2020 |
| Lenovo        | ThinkPad T430 2347GZU       | [f287de215c](https://bsd-hardware.info/?probe=f287de215c) | Oct 20, 2020 |
| Lenovo        | ThinkPad T410 2537N24       | [f846609c80](https://bsd-hardware.info/?probe=f846609c80) | Oct 20, 2020 |
| Panasonic     | CF-52PFPBSFQ                | [feb1da0406](https://bsd-hardware.info/?probe=feb1da0406) | Oct 20, 2020 |
| Matsushita... | CF-51RCVDNLM                | [efece2abf7](https://bsd-hardware.info/?probe=efece2abf7) | Oct 20, 2020 |
| ASUSTek       | 1000HE                      | [621df26e0c](https://bsd-hardware.info/?probe=621df26e0c) | Oct 19, 2020 |
| Lenovo        | ThinkPad T460 20FMS1BC01    | [bf6d6d155b](https://bsd-hardware.info/?probe=bf6d6d155b) | Oct 19, 2020 |
| Lenovo        | ThinkPad E495 20NE0001US    | [a1fc75a9b7](https://bsd-hardware.info/?probe=a1fc75a9b7) | Oct 09, 2020 |
| HP            | Pavilion dv6500             | [316ffb0740](https://bsd-hardware.info/?probe=316ffb0740) | Sep 04, 2020 |
| Acer          | AOD270                      | [41d2974f13](https://bsd-hardware.info/?probe=41d2974f13) | Aug 20, 2020 |
| HP            | Compaq Mini 110c-1100       | [515042ff2d](https://bsd-hardware.info/?probe=515042ff2d) | Aug 20, 2020 |
| Lenovo        | ThinkPad T510 4313CTO       | [7f6095b266](https://bsd-hardware.info/?probe=7f6095b266) | Aug 20, 2020 |
| HP            | EliteBook 840 G3            | [e568f0f32e](https://bsd-hardware.info/?probe=e568f0f32e) | Aug 04, 2020 |
| ASUSTek       | K52JK                       | [d5d32f1334](https://bsd-hardware.info/?probe=d5d32f1334) | Jun 29, 2020 |
| Lenovo        | ThinkPad T420 4180B39       | [05ed5eb1e4](https://bsd-hardware.info/?probe=05ed5eb1e4) | May 25, 2020 |
| Lenovo        | ThinkPad X270 20HNCTO1WW    | [7def094afb](https://bsd-hardware.info/?probe=7def094afb) | May 23, 2020 |
| ASUSTek       | K52JK                       | [6a6b06fc67](https://bsd-hardware.info/?probe=6a6b06fc67) | May 23, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| OpenBSD 7.1         | 10        | 13.7%   |
| OpenBSD 7.0         | 9         | 12.33%  |
| OpenBSD 6.9         | 9         | 12.33%  |
| OpenBSD 6.8         | 7         | 9.59%   |
| helloSystem 0.4.0   | 4         | 5.48%   |
| FreeBSD 13.0-p5     | 3         | 4.11%   |
| helloSystem 0.8.0   | 2         | 2.74%   |
| helloSystem 0.5.0   | 2         | 2.74%   |
| FreeBSD 13.0        | 2         | 2.74%   |
| FreeBSD 12.2        | 2         | 2.74%   |
| OPNsense 22.7       | 1         | 1.37%   |
| OPNsense 22.1.1     | 1         | 1.37%   |
| OPNsense 21.1.5     | 1         | 1.37%   |
| OPNsense 21.1.4     | 1         | 1.37%   |
| OPNsense 21.1       | 1         | 1.37%   |
| NetBSD 8.99.51      | 1         | 1.37%   |
| helloSystem 0.7.0   | 1         | 1.37%   |
| helloSystem 0.6.0   | 1         | 1.37%   |
| GhostBSD 22.06.18   | 1         | 1.37%   |
| GhostBSD 21.08.27   | 1         | 1.37%   |
| FreeBSD 13.0-p3     | 1         | 1.37%   |
| FreeBSD 13.0-p2     | 1         | 1.37%   |
| FreeBSD 12.1-STABLE | 1         | 1.37%   |
| FreeBSD 12.1-p8     | 1         | 1.37%   |
| FreeBSD 12.1-p5     | 1         | 1.37%   |
| FreeBSD 12.1-p10    | 1         | 1.37%   |
| FreeBSD 12.1        | 1         | 1.37%   |
| FreeBSD 12.0-p3     | 1         | 1.37%   |
| FreeBSD 12.0-p13    | 1         | 1.37%   |
| FreeBSD 11.4-p8     | 1         | 1.37%   |
| FreeBSD 11.4-p7     | 1         | 1.37%   |
| FreeBSD 11.4-p6     | 1         | 1.37%   |
| FreeBSD 11.3-p12    | 1         | 1.37%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 18        | 38.3%   |
| OpenBSD     | 14        | 29.79%  |
| helloSystem | 9         | 19.15%  |
| OPNsense    | 3         | 6.38%   |
| GhostBSD    | 2         | 4.26%   |
| NetBSD      | 1         | 2.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| amd64  | 42        | 89.36%  |
| i386   | 4         | 8.51%   |
| macppc | 1         | 2.13%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 18        | 32.14%  |
| fvwm         | 12        | 21.43%  |
| XFCE         | 7         | 12.5%   |
| Console      | 6         | 10.71%  |
| TWM          | 3         | 5.36%   |
| i3           | 2         | 3.57%   |
| Openbox      | 1         | 1.79%   |
| MATE         | 1         | 1.79%   |
| LXQt         | 1         | 1.79%   |
| Lumina       | 1         | 1.79%   |
| KDE5         | 1         | 1.79%   |
| GNOME        | 1         | 1.79%   |
| Fluxbox      | 1         | 1.79%   |
| Cinnamon     | 1         | 1.79%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 41        | 87.23%  |
| Console | 6         | 12.77%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 27        | 57.45%  |
| SLiM    | 9         | 19.15%  |
| XDM     | 7         | 14.89%  |
| LightDM | 2         | 4.26%   |
| SDDM    | 1         | 2.13%   |
| GDM     | 1         | 2.13%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 27        | 57.45%  |
| en_US   | 10        | 21.28%  |
| C       | 4         | 8.51%   |
| fr_FR   | 2         | 4.26%   |
| en_CA   | 2         | 4.26%   |
| fr_CA   | 1         | 2.13%   |
| en_NL   | 1         | 2.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 26        | 54.17%  |
| BIOS | 22        | 45.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 17        | 36.17%  |
| Ufs    | 15        | 31.91%  |
| Ffs    | 14        | 29.79%  |
| Cd9660 | 1         | 2.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 33        | 70.21%  |
| MBR     | 13        | 27.66%  |
| Unknown | 1         | 2.13%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 15        | 31.91%  |
| Dell                           | 7         | 14.89%  |
| ASUSTek Computer               | 5         | 10.64%  |
| Hewlett-Packard                | 4         | 8.51%   |
| Toshiba                        | 3         | 6.38%   |
| Panasonic                      | 2         | 4.26%   |
| Matsushita Electric Industrial | 2         | 4.26%   |
| Intel                          | 2         | 4.26%   |
| Apple                          | 2         | 4.26%   |
| LG Electronics                 | 1         | 2.13%   |
| Gigabyte Technology            | 1         | 2.13%   |
| Fujitsu                        | 1         | 2.13%   |
| Alienware                      | 1         | 2.13%   |
| Acer                           | 1         | 2.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel H81U                                  | 2         | 4.26%   |
| Toshiba TECRA Z40-B                         | 1         | 2.13%   |
| Toshiba Satellite U500                      | 1         | 2.13%   |
| Toshiba Satellite Pro T130                  | 1         | 2.13%   |
| Panasonic CF-53AAGHYDM                      | 1         | 2.13%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 2.13%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 2.13%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 2.13%   |
| LG E500-GP01A9                              | 1         | 2.13%   |
| Lenovo ThinkPad X280 20KF001UUS             | 1         | 2.13%   |
| Lenovo ThinkPad X270 20HNCTO1WW             | 1         | 2.13%   |
| Lenovo ThinkPad X250 20CL001GUS             | 1         | 2.13%   |
| Lenovo ThinkPad X220 429043U                | 1         | 2.13%   |
| Lenovo ThinkPad T510 4313CTO                | 1         | 2.13%   |
| Lenovo ThinkPad T490 20N3S8PB00             | 1         | 2.13%   |
| Lenovo ThinkPad T460 20FMS1BC01             | 1         | 2.13%   |
| Lenovo ThinkPad T440 20B7S0A800             | 1         | 2.13%   |
| Lenovo ThinkPad T430 2347GZU                | 1         | 2.13%   |
| Lenovo ThinkPad T420s 41742BU               | 1         | 2.13%   |
| Lenovo ThinkPad T420 4180B39                | 1         | 2.13%   |
| Lenovo ThinkPad T410 2537N24                | 1         | 2.13%   |
| Lenovo ThinkPad T410 253722U                | 1         | 2.13%   |
| Lenovo ThinkPad E495 20NE0001US             | 1         | 2.13%   |
| Lenovo IdeaPad Y580 20132                   | 1         | 2.13%   |
| HP Pavilion dv6500                          | 1         | 2.13%   |
| HP Notebook                                 | 1         | 2.13%   |
| HP EliteBook 840 G3                         | 1         | 2.13%   |
| HP Compaq Mini 110c-1100                    | 1         | 2.13%   |
| Gigabyte MMLP3AP-00                         | 1         | 2.13%   |
| Fujitsu LIFEBOOK E752                       | 1         | 2.13%   |
| Dell Studio 1747                            | 1         | 2.13%   |
| Dell Latitude E7440                         | 1         | 2.13%   |
| Dell Latitude 3440                          | 1         | 2.13%   |
| Dell Inspiron 7370                          | 1         | 2.13%   |
| Dell Inspiron 5559                          | 1         | 2.13%   |
| Dell Inspiron 15-7579                       | 1         | 2.13%   |
| Dell Inspiron 15-3567                       | 1         | 2.13%   |
| ASUS U31SD                                  | 1         | 2.13%   |
| ASUS TUF GAMING FX504GD_FX80GD              | 1         | 2.13%   |
| ASUS K52JK                                  | 1         | 2.13%   |
| ASUS G75VW                                  | 1         | 2.13%   |
| ASUS 1000HE                                 | 1         | 2.13%   |
| Apple PowerBook5,2                          | 1         | 2.13%   |
| Apple MacBookPro5,5                         | 1         | 2.13%   |
| Alienware 14                                | 1         | 2.13%   |
| Acer AOD270                                 | 1         | 2.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad                             | 14        | 29.79%  |
| Dell Inspiron                               | 4         | 8.51%   |
| Toshiba Satellite                           | 2         | 4.26%   |
| Intel H81U                                  | 2         | 4.26%   |
| Dell Latitude                               | 2         | 4.26%   |
| Toshiba TECRA                               | 1         | 2.13%   |
| Panasonic CF-53AAGHYDM                      | 1         | 2.13%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 2.13%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 2.13%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 2.13%   |
| LG E500-GP01A9                              | 1         | 2.13%   |
| Lenovo IdeaPad                              | 1         | 2.13%   |
| HP Pavilion                                 | 1         | 2.13%   |
| HP Notebook                                 | 1         | 2.13%   |
| HP EliteBook                                | 1         | 2.13%   |
| HP Compaq                                   | 1         | 2.13%   |
| Gigabyte MMLP3AP-00                         | 1         | 2.13%   |
| Fujitsu LIFEBOOK                            | 1         | 2.13%   |
| Dell Studio                                 | 1         | 2.13%   |
| ASUS U31SD                                  | 1         | 2.13%   |
| ASUS TUF                                    | 1         | 2.13%   |
| ASUS K52JK                                  | 1         | 2.13%   |
| ASUS G75VW                                  | 1         | 2.13%   |
| ASUS 1000HE                                 | 1         | 2.13%   |
| Apple PowerBook5                            | 1         | 2.13%   |
| Apple MacBookPro5                           | 1         | 2.13%   |
| Alienware 14                                | 1         | 2.13%   |
| Acer AOD270                                 | 1         | 2.13%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2010    | 8         | 17.02%  |
| 2019    | 6         | 12.77%  |
| 2011    | 6         | 12.77%  |
| 2016    | 3         | 6.38%   |
| 2015    | 3         | 6.38%   |
| 2012    | 3         | 6.38%   |
| 2009    | 3         | 6.38%   |
| 2020    | 2         | 4.26%   |
| 2018    | 2         | 4.26%   |
| 2017    | 2         | 4.26%   |
| 2014    | 2         | 4.26%   |
| 2013    | 2         | 4.26%   |
| 2021    | 1         | 2.13%   |
| 2008    | 1         | 2.13%   |
| 2006    | 1         | 2.13%   |
| 2002    | 1         | 2.13%   |
| Unknown | 1         | 2.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 47        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 47        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 22        | 46.81%  |
| 4.01-8.0   | 7         | 14.89%  |
| 16.01-24.0 | 6         | 12.77%  |
| 3.01-4.0   | 4         | 8.51%   |
| 2.01-3.0   | 4         | 8.51%   |
| 32.01-64.0 | 2         | 4.26%   |
| 1.01-2.0   | 1         | 2.13%   |
| 0.51-1.0   | 1         | 2.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 33        | 68.75%  |
| 0.51-1.0 | 9         | 18.75%  |
| 1.01-2.0 | 2         | 4.17%   |
| 0        | 2         | 4.17%   |
| 3.01-4.0 | 1         | 2.08%   |
| Unknown  | 1         | 2.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 38        | 79.17%  |
| 2      | 7         | 14.58%  |
| 0      | 3         | 6.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 34        | 72.34%  |
| Yes       | 13        | 27.66%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 45        | 95.74%  |
| No        | 2         | 4.26%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 45        | 95.74%  |
| No        | 2         | 4.26%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 28        | 59.57%  |
| No        | 19        | 40.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Canada  | 47        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Montreal         | 13        | 20.63%  |
| Saint-Laurent    | 9         | 14.29%  |
| QuГ©bec        | 5         | 7.94%   |
| Vancouver        | 4         | 6.35%   |
| Ottawa           | 3         | 4.76%   |
| Calgary          | 3         | 4.76%   |
| Victoria         | 2         | 3.17%   |
| Toronto          | 2         | 3.17%   |
| Sainte-Julie     | 2         | 3.17%   |
| Peterborough     | 2         | 3.17%   |
| Winnipeg         | 1         | 1.59%   |
| Vaudreuil-Dorion | 1         | 1.59%   |
| Surrey           | 1         | 1.59%   |
| Sechelt          | 1         | 1.59%   |
| Québec          | 1         | 1.59%   |
| Niagara Falls    | 1         | 1.59%   |
| Mississauga      | 1         | 1.59%   |
| Mission          | 1         | 1.59%   |
| Maple Ridge      | 1         | 1.59%   |
| Lloydminster     | 1         | 1.59%   |
| Laval            | 1         | 1.59%   |
| Langley          | 1         | 1.59%   |
| Lamont           | 1         | 1.59%   |
| Hamilton         | 1         | 1.59%   |
| Halifax          | 1         | 1.59%   |
| Guelph           | 1         | 1.59%   |
| Gatineau         | 1         | 1.59%   |
| Beloeil          | 1         | 1.59%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 14        | 31     | 28.57%  |
| Toshiba             | 6         | 7      | 12.24%  |
| Seagate             | 5         | 8      | 10.2%   |
| Samsung Electronics | 4         | 6      | 8.16%   |
| Hitachi             | 4         | 6      | 8.16%   |
| Lexar               | 2         | 2      | 4.08%   |
| Intel               | 2         | 2      | 4.08%   |
| Crucial             | 2         | 2      | 4.08%   |
| A-DATA Technology   | 2         | 4      | 4.08%   |
| Transcend           | 1         | 1      | 2.04%   |
| SK hynix            | 1         | 1      | 2.04%   |
| SanDisk             | 1         | 1      | 2.04%   |
| OCZ                 | 1         | 1      | 2.04%   |
| NVMe                | 1         | 1      | 2.04%   |
| Micron Technology   | 1         | 1      | 2.04%   |
| Kston               | 1         | 2      | 2.04%   |
| Fujitsu             | 1         | 1      | 2.04%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| WDC WDS500G2B0A-00SM50 500GB       | 2         | 4%      |
| WDC WDS500G2B0A 500GB              | 1         | 2%      |
| WDC WDS200T2B0A 2TB                | 1         | 2%      |
| WDC WD7500BPKX-75HPJT0 752GB       | 1         | 2%      |
| WDC WD7500BPKX-00HPJT0 752GB       | 1         | 2%      |
| WDC WD7500BPKT-75PK4T0 752GB       | 1         | 2%      |
| WDC WD7500BPKT-00PK4T0 752GB       | 1         | 2%      |
| WDC WD6400BEVT-22A0RT0 640GB       | 1         | 2%      |
| WDC WD5000LPLX-00ZNTT0 500GB       | 1         | 2%      |
| WDC WD3200BEVE-00A0HT0 320GB       | 1         | 2%      |
| WDC WD10JPVX-75JC3T0 1TB           | 1         | 2%      |
| WDC WD10JPVT-00A1YT0 1TB           | 1         | 2%      |
| WDC WD10JPLX-00MBPT0 1TB           | 1         | 2%      |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB | 1         | 2%      |
| Transcend TSA 240GB                | 1         | 2%      |
| Toshiba THNSNJ128GCSU 128GB        | 1         | 2%      |
| Toshiba MQ04ABF100 1TB             | 1         | 2%      |
| Toshiba MQ01ABF032 320GB           | 1         | 2%      |
| Toshiba MK8025GAS 80GB             | 1         | 2%      |
| Toshiba MK5061GSYN 500GB           | 1         | 2%      |
| Toshiba MK3259GSXP 320GB           | 1         | 2%      |
| SK hynix SC308 SATA 256GB          | 1         | 2%      |
| Seagate ST9500420AS 500GB          | 1         | 2%      |
| Seagate ST9160821A 160GB           | 1         | 2%      |
| Seagate ST500LT032-1E9142 500GB    | 1         | 2%      |
| Seagate ST2000LM003 HN-M201RAD 2TB | 1         | 2%      |
| Seagate ST1000LM035-1RK172 1TB     | 1         | 2%      |
| SanDisk SSD U100 16GB              | 1         | 2%      |
| Samsung SSD 860 EVO 500GB          | 1         | 2%      |
| Samsung SSD 850 PRO 256GB          | 1         | 2%      |
| Samsung MZ7TE128HMGR-000L1 128GB   | 1         | 2%      |
| Samsung MZ7PC128HAFU-000L1 128GB   | 1         | 2%      |
| OCZ VERTEX3 120GB                  | 1         | 2%      |
| NVMe WDC PC SN730 SDB 256GB        | 1         | 2%      |
| Micron 1100 SATA 256GB             | 1         | 2%      |
| Lexar USB Flash Drive 64GB         | 1         | 2%      |
| Lexar 256GB SSD                    | 1         | 2%      |
| Kston SSD 64GB                     | 1         | 2%      |
| Intel SSDSC2CW120A3 120GB          | 1         | 2%      |
| Intel SSDSC2BW240A4 240GB          | 1         | 2%      |
| Hitachi HTS727550A9E364 500GB      | 1         | 2%      |
| Hitachi HTS723232A7A364 320GB      | 1         | 2%      |
| Hitachi HTS723220L9A360 200GB      | 1         | 2%      |
| Hitachi HTS541612J9SA00 120GB      | 1         | 2%      |
| Fujitsu MJA2160BH G2 160GB         | 1         | 2%      |
| Crucial CT120M500SSD3 120GB        | 1         | 2%      |
| Crucial CT120BX500SSD1 120GB       | 1         | 2%      |
| A-DATA SX6000LNP 512GB             | 1         | 2%      |
| A-DATA SP550 480GB                 | 1         | 2%      |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 10        | 26     | 37.04%  |
| Toshiba | 5         | 6      | 18.52%  |
| Seagate | 5         | 8      | 18.52%  |
| Hitachi | 4         | 6      | 14.81%  |
| NVMe    | 1         | 1      | 3.7%    |
| Lexar   | 1         | 1      | 3.7%    |
| Fujitsu | 1         | 1      | 3.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 19.05%  |
| Samsung Electronics | 4         | 6      | 19.05%  |
| Intel               | 2         | 2      | 9.52%   |
| Crucial             | 2         | 2      | 9.52%   |
| Transcend           | 1         | 1      | 4.76%   |
| Toshiba             | 1         | 1      | 4.76%   |
| SK hynix            | 1         | 1      | 4.76%   |
| SanDisk             | 1         | 1      | 4.76%   |
| OCZ                 | 1         | 1      | 4.76%   |
| Micron Technology   | 1         | 1      | 4.76%   |
| Lexar               | 1         | 1      | 4.76%   |
| Kston               | 1         | 2      | 4.76%   |
| A-DATA Technology   | 1         | 3      | 4.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 26        | 49     | 55.32%  |
| SSD  | 19        | 26     | 40.43%  |
| NVMe | 2         | 2      | 4.26%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 43        | 75     | 95.56%  |
| NVMe | 2         | 2      | 4.44%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 33        | 53     | 73.33%  |
| 0.51-1.0   | 10        | 20     | 22.22%  |
| 1.01-2.0   | 2         | 2      | 4.44%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 21-50      | 13        | 25.49%  |
| 101-250    | 13        | 25.49%  |
| 1-20       | 8         | 15.69%  |
| 251-500    | 7         | 13.73%  |
| 51-100     | 5         | 9.8%    |
| 501-1000   | 4         | 7.84%   |
| 1001-2000  | 1         | 1.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 38        | 79.17%  |
| 21-50   | 6         | 12.5%   |
| 51-100  | 3         | 6.25%   |
| 251-500 | 1         | 2.08%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| WDC WDS200T2B0A 2TB           | 1         | 1      | 16.67%  |
| WDC WD6400BEVT-22A0RT0 640GB  | 1         | 1      | 16.67%  |
| Seagate ST9500420AS 500GB     | 1         | 2      | 16.67%  |
| Intel SSDSC2CW120A3 120GB     | 1         | 1      | 16.67%  |
| Hitachi HTS541612J9SA00 120GB | 1         | 1      | 16.67%  |
| A-DATA Technology SP550 480GB | 1         | 3      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 2         | 2      | 33.33%  |
| Seagate           | 1         | 2      | 16.67%  |
| Intel             | 1         | 1      | 16.67%  |
| Hitachi           | 1         | 1      | 16.67%  |
| A-DATA Technology | 1         | 3      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 33.33%  |
| Seagate | 1         | 2      | 33.33%  |
| Hitachi | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 3         | 5      | 50%     |
| HDD  | 3         | 4      | 50%     |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 38        | 65     | 80.85%  |
| Malfunc  | 6         | 9      | 12.77%  |
| Detected | 3         | 3      | 6.38%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 41        | 87.23%  |
| SanDisk               | 2         | 4.26%   |
| Samsung Electronics   | 1         | 2.13%   |
| Realtek Semiconductor | 1         | 2.13%   |
| Nvidia                | 1         | 2.13%   |
| AMD                   | 1         | 2.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 6         | 12%     |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 5         | 10%     |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 5         | 10%     |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 4         | 8%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 4         | 8%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 3         | 6%      |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 2         | 4%      |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 2         | 4%      |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 2         | 4%      |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 2         | 4%      |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 2         | 4%      |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 2         | 4%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 1         | 2%      |
| Nvidia MCP79 AHCI Controller                                                           | 1         | 2%      |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 1         | 2%      |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 1         | 2%      |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 1         | 2%      |
| Intel 82801CAM IDE U100 Controller                                                     | 1         | 2%      |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 2%      |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 2%      |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 1         | 2%      |
| AMD FCH SATA Controller [AHCI mode]                                                    | 1         | 2%      |
| Unknown                                                                                | 1         | 2%      |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 37        | 75.51%  |
| IDE  | 6         | 12.24%  |
| NVMe | 4         | 8.16%   |
| RAID | 2         | 4.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 45        | 95.74%  |
| AMD     | 1         | 2.13%   |
| Unknown | 1         | 2.13%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz                             | 4         | 8%      |
| Intel Core i5 CPU M 520 @ 2.40GHz                             | 3         | 6%      |
| Intel CPU Version                                             | 2         | 4%      |
| Intel Core i7-3630QM CPU @ 2.40GHz                            | 2         | 4%      |
| Intel Core i5-6300U CPU @ 2.40GHz                             | 2         | 4%      |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz                   | 1         | 2%      |
| Intel Pentium 4 Mobile CPU 1.60GHz ("GenuineIntel" 686-class) | 1         | 2%      |
| Intel Pentium 4 Mobile CPU 1.60GHz                            | 1         | 2%      |
| Intel Genuine CPU T2300 @ 1.66GHz                             | 1         | 2%      |
| Intel CPU T2300 @ 1.66GHz ("GenuineIntel" 686-class)          | 1         | 2%      |
| Intel Core i7-8750H CPU @ 2.20GHz                             | 1         | 2%      |
| Intel Core i7-8650U CPU @ 1.90GHz                             | 1         | 2%      |
| Intel Core i7-7600U CPU @ 2.80GHz                             | 1         | 2%      |
| Intel Core i7-5500U CPU @ 2.40GHz                             | 1         | 2%      |
| Intel Core i7-4700MQ CPU @ 2.40GHz                            | 1         | 2%      |
| Intel Core i7-3520M CPU @ 2.90GHz                             | 1         | 2%      |
| Intel Core i5-8265U CPU @ 1.60GHz                             | 1         | 2%      |
| Intel Core i5-8250U CPU @ 1.60GHz                             | 1         | 2%      |
| Intel Core i5-7200U CPU @ 2.50GHz                             | 1         | 2%      |
| Intel Core i5-6200U CPU @ 2.30GHz                             | 1         | 2%      |
| Intel Core i5-5300U CPU @ 2.30GHz                             | 1         | 2%      |
| Intel Core i5-5200U CPU @ 2.20GHz                             | 1         | 2%      |
| Intel Core i5-4310U CPU @ 2.00GHz                             | 1         | 2%      |
| Intel Core i5-4300U CPU @ 1.90GHz                             | 1         | 2%      |
| Intel Core i5-4210U CPU @ 1.70GHz                             | 1         | 2%      |
| Intel Core i5-3320M CPU @ 2.60GHz                             | 1         | 2%      |
| Intel Core i5 CPU M 540 @ 2.53GHz                             | 1         | 2%      |
| Intel Core i5 CPU M 430 @ 2.27GH                              | 1         | 2%      |
| Intel Core i3-7100U CPU @ 2.40GHz                             | 1         | 2%      |
| Intel Core i3-5020U CPU @ 2.20GHz                             | 1         | 2%      |
| Intel Core i3-5005U CPU @ 2.00GHz                             | 1         | 2%      |
| Intel Core i3-4010U CPU @ 1.70GHz                             | 1         | 2%      |
| Intel Core i3-2310M CPU @ 2.10GHz                             | 1         | 2%      |
| Intel Core 2 Duo CPU T8100                                    | 1         | 2%      |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz                          | 1         | 2%      |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz                          | 1         | 2%      |
| Intel Atom CPU N280 @ 1.66GHz ("GenuineIntel" 686-class)      | 1         | 2%      |
| Intel Atom CPU N280 @ 1.66GHz                                 | 1         | 2%      |
| Intel Atom CPU N270 @ 1.60GHz                                 | 1         | 2%      |
| Intel Atom CPU N2600 @ 1.60GHz                                | 1         | 2%      |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx                 | 1         | 2%      |
|                                                               | 1         | 2%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 21        | 43.75%  |
| Intel Core i7           | 8         | 16.67%  |
| Intel Core i3           | 5         | 10.42%  |
| Other                   | 4         | 8.33%   |
| Intel Core 2 Duo        | 3         | 6.25%   |
| Intel Atom              | 3         | 6.25%   |
| Intel Pentium Dual-Core | 1         | 2.08%   |
| Intel Pentium 4         | 1         | 2.08%   |
| Intel Genuine           | 1         | 2.08%   |
| AMD Ryzen 7             | 1         | 2.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 30        | 63.83%  |
| 4       | 7         | 14.89%  |
| Unknown | 7         | 14.89%  |
| 8       | 1         | 2.13%   |
| 6       | 1         | 2.13%   |
| 1       | 1         | 2.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 45        | 90%     |
| Unknown | 4         | 8%      |
| 2       | 1         | 2%      |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 36        | 76.6%   |
| Unknown | 8         | 17.02%  |
| 1       | 3         | 6.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 7         | 14.29%  |
| SandyBridge | 5         | 10.2%   |
| Haswell     | 5         | 10.2%   |
| Broadwell   | 5         | 10.2%   |
| Westmere    | 4         | 8.16%   |
| Penryn      | 4         | 8.16%   |
| IvyBridge   | 4         | 8.16%   |
| Unknown     | 4         | 8.16%   |
| Skylake     | 3         | 6.12%   |
| Bonnell     | 3         | 6.12%   |
| Zen+        | 1         | 2.04%   |
| P6          | 1         | 2.04%   |
| NetBurst    | 1         | 2.04%   |
| Nehalem     | 1         | 2.04%   |
| Core        | 1         | 2.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 38        | 74.51%  |
| Nvidia | 8         | 15.69%  |
| AMD    | 5         | 9.8%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 5500                                                        | 5         | 9.09%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 5         | 9.09%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 4         | 7.27%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 3         | 5.45%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 3         | 5.45%   |
| Intel HD Graphics 620                                                         | 3         | 5.45%   |
| Intel Core Processor Integrated Graphics Controller                           | 3         | 5.45%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 3         | 5.45%   |
| Nvidia GK107M [GeForce GTX 660M]                                              | 2         | 3.64%   |
| Intel UHD Graphics 620                                                        | 2         | 3.64%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 2         | 3.64%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 2         | 3.64%   |
| Nvidia GT218M [NVS 3100M]                                                     | 1         | 1.82%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 1         | 1.82%   |
| Nvidia GK106M [GeForce GTX 765M]                                              | 1         | 1.82%   |
| Nvidia GF119M [GeForce GT 520M]                                               | 1         | 1.82%   |
| Nvidia G86M [GeForce 8400M GS]                                                | 1         | 1.82%   |
| Nvidia C79 [GeForce 9400M]                                                    | 1         | 1.82%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 1         | 1.82%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 1         | 1.82%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 1         | 1.82%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 1         | 1.82%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 1         | 1.82%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller               | 1         | 1.82%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 1         | 1.82%   |
| AMD RV730/M96 [Mobility Radeon HD 4650/5165]                                  | 1         | 1.82%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                             | 1         | 1.82%   |
| AMD RV350/M10 / RV360/M11 [Mobility Radeon 9600 (PRO) / 9700]                 | 1         | 1.82%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 1         | 1.82%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 1         | 1.82%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 28        | 59.57%  |
| 2 x Intel      | 6         | 12.77%  |
| 1 x AMD        | 5         | 10.64%  |
| 1 x Nvidia     | 4         | 8.51%   |
| Intel + Nvidia | 4         | 8.51%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 43        | 91.49%  |
| Proprietary | 3         | 6.38%   |
| Unknown     | 1         | 2.13%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 40        | 83.33%  |
| 3.01-4.0   | 2         | 4.17%   |
| 1.01-2.0   | 2         | 4.17%   |
| 0.51-1.0   | 2         | 4.17%   |
| 0.01-0.5   | 2         | 4.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 6         | 18.18%  |
| Chimei Innolux          | 6         | 18.18%  |
| Samsung Electronics     | 4         | 12.12%  |
| BOE                     | 4         | 12.12%  |
| AU Optronics            | 4         | 12.12%  |
| Chi Mei Optoelectronics | 3         | 9.09%   |
| Lenovo                  | 2         | 6.06%   |
| Goldstar                | 2         | 6.06%   |
| Toshiba                 | 1         | 3.03%   |
| Apple                   | 1         | 3.03%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Toshiba LCD Monitor LCD0905 1366x768 290x170mm 13.2-inch                  | 1         | 3.03%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 470x300mm 22.0-inch      | 1         | 3.03%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 330x210mm 15.4-inch      | 1         | 3.03%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch      | 1         | 3.03%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 350x200mm 15.9-inch      | 1         | 3.03%   |
| LG Display LCD Monitor LGD0484 1366x768 340x190mm 15.3-inch               | 1         | 3.03%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch               | 1         | 3.03%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x170mm 13.9-inch               | 1         | 3.03%   |
| LG Display LCD Monitor LGD021D 1600x900 380x210mm 17.1-inch               | 1         | 3.03%   |
| LG Display LCD Monitor LGD0215 1920x1080 350x190mm 15.7-inch              | 1         | 3.03%   |
| LG Display LCD Monitor LGD01E9 1920x1080 350x190mm 15.7-inch              | 1         | 3.03%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch                   | 1         | 3.03%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch                   | 1         | 3.03%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch                | 1         | 3.03%   |
| Goldstar L1920P GSM4A7B 1280x1024 380x300mm 19.1-inch                     | 1         | 3.03%   |
| Chimei Innolux LCD Monitor CMN15F4 1920x1080 340x190mm 15.3-inch          | 1         | 3.03%   |
| Chimei Innolux LCD Monitor CMN14B7 1366x768 310x170mm 13.9-inch           | 1         | 3.03%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 310x170mm 13.9-inch          | 1         | 3.03%   |
| Chimei Innolux LCD Monitor CMN1492 1366x768 310x170mm 13.9-inch           | 1         | 3.03%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 310x170mm 13.9-inch           | 1         | 3.03%   |
| Chimei Innolux LCD Monitor CMN1367 1920x1080 290x170mm 13.2-inch          | 1         | 3.03%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 380x210mm 17.1-inch | 1         | 3.03%   |
| Chi Mei Optoelectronics LCD Monitor CMO1333 1366x768 290x160mm 13.0-inch  | 1         | 3.03%   |
| Chi Mei Optoelectronics LCD Monitor CMO1312 1280x800 290x180mm 13.4-inch  | 1         | 3.03%   |
| BOE LCD Monitor BOE0817 1366x768 340x190mm 15.3-inch                      | 1         | 3.03%   |
| BOE LCD Monitor BOE07C9 1920x1080 300x170mm 13.6-inch                     | 1         | 3.03%   |
| BOE LCD Monitor BOE0742 1920x1080 310x170mm 13.9-inch                     | 1         | 3.03%   |
| BOE LCD Monitor BOE06C2 1366x768 340x190mm 15.3-inch                      | 1         | 3.03%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch            | 1         | 3.03%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 310x170mm 13.9-inch            | 1         | 3.03%   |
| AU Optronics LCD Monitor AUO10ED 1920x1080 340x190mm 15.3-inch            | 1         | 3.03%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch             | 1         | 3.03%   |
| Apple Color LCD APP9C20 1280x854 320x220mm 15.3-inch                      | 1         | 3.03%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 11        | 33.33%  |
| 1366x768 (WXGA)    | 10        | 30.3%   |
| 1600x900 (HD+)     | 5         | 15.15%  |
| 1280x800 (WXGA)    | 3         | 9.09%   |
| 2560x1080          | 1         | 3.03%   |
| 1680x1050 (WSXGA+) | 1         | 3.03%   |
| 1280x854           | 1         | 3.03%   |
| 1280x1024 (SXGA)   | 1         | 3.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 13        | 39.39%  |
| 15     | 11        | 33.33%  |
| 12     | 3         | 9.09%   |
| 17     | 2         | 6.06%   |
| 34     | 1         | 3.03%   |
| 22     | 1         | 3.03%   |
| 19     | 1         | 3.03%   |
| 14     | 1         | 3.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 19        | 57.58%  |
| 201-300     | 9         | 27.27%  |
| 351-400     | 3         | 9.09%   |
| 701-800     | 1         | 3.03%   |
| 401-500     | 1         | 3.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 26        | 78.79%  |
| 16/10 | 4         | 12.12%  |
| 5/4   | 1         | 3.03%   |
| 3/2   | 1         | 3.03%   |
| 21/9  | 1         | 3.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 10        | 30.3%   |
| 101-110        | 6         | 18.18%  |
| 91-100         | 5         | 15.15%  |
| 71-80          | 4         | 12.12%  |
| 61-70          | 3         | 9.09%   |
| 121-130        | 2         | 6.06%   |
| 351-500        | 1         | 3.03%   |
| 201-250        | 1         | 3.03%   |
| 151-200        | 1         | 3.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 14        | 42.42%  |
| 101-120 | 11        | 33.33%  |
| 51-100  | 5         | 15.15%  |
| 161-240 | 3         | 9.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 37        | 77.08%  |
| 0     | 10        | 20.83%  |
| 2     | 1         | 2.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 31        | 45.59%  |
| Realtek Semiconductor             | 14        | 20.59%  |
| Qualcomm Atheros                  | 13        | 19.12%  |
| Broadcom                          | 4         | 5.88%   |
| Ralink Technology                 | 1         | 1.47%   |
| Nvidia                            | 1         | 1.47%   |
| Marvell Technology Group          | 1         | 1.47%   |
| JMicron Technology                | 1         | 1.47%   |
| Ericsson Business Mobile Networks | 1         | 1.47%   |
| Apple                             | 1         | 1.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 7         | 7.45%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 6         | 6.38%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 6         | 6.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 6         | 6.38%   |
| Intel 82577LM Gigabit Network Connection                                    | 4         | 4.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 3         | 3.19%   |
| Intel Wireless 8265 / 8275                                                  | 3         | 3.19%   |
| Intel Wireless 7260                                                         | 3         | 3.19%   |
| Intel Centrino Advanced-N 6200                                              | 3         | 3.19%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 2         | 2.13%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                               | 2         | 2.13%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                       | 2         | 2.13%   |
| Intel Wireless 8260                                                         | 2         | 2.13%   |
| Intel Wireless 7265                                                         | 2         | 2.13%   |
| Intel Ethernet Connection I219-LM                                           | 2         | 2.13%   |
| Intel Ethernet Connection I218-LM                                           | 2         | 2.13%   |
| Intel Ethernet Connection (4) I219-LM                                       | 2         | 2.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 1         | 1.06%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                             | 1         | 1.06%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                       | 1         | 1.06%   |
| Ralink RT2870/RT3070 Wireless Adapter                                       | 1         | 1.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 1         | 1.06%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                   | 1         | 1.06%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                            | 1         | 1.06%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 1         | 1.06%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                    | 1         | 1.06%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet              | 1         | 1.06%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                       | 1         | 1.06%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 1         | 1.06%   |
| Nvidia MCP79 Ethernet                                                       | 1         | 1.06%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                     | 1         | 1.06%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                      | 1         | 1.06%   |
| Intel Wireless-AC 9260                                                      | 1         | 1.06%   |
| Intel Wireless 3165                                                         | 1         | 1.06%   |
| Intel Wireless 3160                                                         | 1         | 1.06%   |
| Intel WiMAX Connection 2400m                                                | 1         | 1.06%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection               | 1         | 1.06%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 1         | 1.06%   |
| Intel Ethernet Connection (6) I219-V                                        | 1         | 1.06%   |
| Intel Ethernet Connection (3) I218-V                                        | 1         | 1.06%   |
| Intel Ethernet Connection (3) I218-LM                                       | 1         | 1.06%   |
| Intel Centrino Wireless-N 2200                                              | 1         | 1.06%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                | 1         | 1.06%   |
| Intel Centrino Wireless-N 100                                               | 1         | 1.06%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                        | 1         | 1.06%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                    | 1         | 1.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                             | 1         | 1.06%   |
| Intel 82580 Gigabit Network Connection                                      | 1         | 1.06%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III | 1         | 1.06%   |
| Broadcom BCM43225 802.11b/g/n                                               | 1         | 1.06%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                      | 1         | 1.06%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                           | 1         | 1.06%   |
| Broadcom BCM4306 802.11b/g Wireless LAN Controller                          | 1         | 1.06%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                             | 1         | 1.06%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 30        | 65.22%  |
| Qualcomm Atheros      | 9         | 19.57%  |
| Broadcom              | 4         | 8.7%    |
| Realtek Semiconductor | 2         | 4.35%   |
| Ralink Technology     | 1         | 2.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 12.77%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 6.38%   |
| Intel Wireless 8265 / 8275                                              | 3         | 6.38%   |
| Intel Wireless 7260                                                     | 3         | 6.38%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 6.38%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 4.26%   |
| Intel Wireless 8260                                                     | 2         | 4.26%   |
| Intel Wireless 7265                                                     | 2         | 4.26%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 2.13%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 2.13%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 2.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 2.13%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 2.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 2.13%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 1         | 2.13%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 2.13%   |
| Intel Wireless-AC 9260                                                  | 1         | 2.13%   |
| Intel Wireless 3165                                                     | 1         | 2.13%   |
| Intel Wireless 3160                                                     | 1         | 2.13%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 2.13%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 2.13%   |
| Intel Centrino Wireless-N 2200                                          | 1         | 2.13%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 2.13%   |
| Intel Centrino Wireless-N 100                                           | 1         | 2.13%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                    | 1         | 2.13%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 2.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1         | 2.13%   |
| Broadcom BCM43225 802.11b/g/n                                           | 1         | 2.13%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 1         | 2.13%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 1         | 2.13%   |
| Broadcom BCM4306 802.11b/g Wireless LAN Controller                      | 1         | 2.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 20        | 44.44%  |
| Realtek Semiconductor    | 14        | 31.11%  |
| Qualcomm Atheros         | 7         | 15.56%  |
| Nvidia                   | 1         | 2.22%   |
| Marvell Technology Group | 1         | 2.22%   |
| JMicron Technology       | 1         | 2.22%   |
| Apple                    | 1         | 2.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 15.56%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 13.33%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 13.33%  |
| Intel 82577LM Gigabit Network Connection                          | 4         | 8.89%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 4.44%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 4.44%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 4.44%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 4.44%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 4.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 2.22%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 2.22%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 2.22%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 2.22%   |
| Nvidia MCP79 Ethernet                                             | 1         | 2.22%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 2.22%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 2.22%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 2.22%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 2.22%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 2.22%   |
| Intel 82580 Gigabit Network Connection                            | 1         | 2.22%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                   | 1         | 2.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 45        | 48.91%  |
| Ethernet | 45        | 48.91%  |
| Unknown  | 2         | 2.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 40        | 54.05%  |
| Ethernet | 34        | 45.95%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 41        | 87.23%  |
| 1     | 3         | 6.38%   |
| 3     | 2         | 4.26%   |
| 4     | 1         | 2.13%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 44        | 89.8%   |
| Yes  | 5         | 10.2%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 10        | 35.71%  |
| Broadcom                        | 3         | 10.71%  |
| Qualcomm Atheros Communications | 2         | 7.14%   |
| IMC Networks                    | 2         | 7.14%   |
| Cambridge Silicon Radio         | 2         | 7.14%   |
| Alps Electric                   | 2         | 7.14%   |
| Toshiba                         | 1         | 3.57%   |
| Realtek Semiconductor           | 1         | 3.57%   |
| Lite-On Technology              | 1         | 3.57%   |
| Hewlett-Packard                 | 1         | 3.57%   |
| Foxconn / Hon Hai               | 1         | 3.57%   |
| ASUSTek Computer                | 1         | 3.57%   |
| Apple                           | 1         | 3.57%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 8         | 28.57%  |
| Broadcom BCM2045B (BDC-2.1)                                 | 3         | 10.71%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2         | 7.14%   |
| Alps Electric UGTZ4 Bluetooth                               | 2         | 7.14%   |
| Toshiba ASKEY Bluetooth Controller BTU1030                  | 1         | 3.57%   |
| Realtek  Bluetooth 4.0 Adapter                              | 1         | 3.57%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 3.57%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 3.57%   |
| Lite-On Broadcom Bluetooth 4.0 USB                          | 1         | 3.57%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 3.57%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 1         | 3.57%   |
| IMC Networks Bluetooth                                      | 1         | 3.57%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 1         | 3.57%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 3.57%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device    | 1         | 3.57%   |
| ASUS Broadcom Bluetooth 2.1                                 | 1         | 3.57%   |
| Apple Bluetooth Host Controller                             | 1         | 3.57%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 44        | 86.27%  |
| Nvidia | 3         | 5.88%   |
| AMD    | 3         | 5.88%   |
| XMOS   | 1         | 1.96%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 8         | 12.9%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 9.68%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 8.06%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 8.06%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 8.06%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 6.45%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 6.45%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 6.45%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 4.84%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 3.23%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 3.23%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 2         | 3.23%   |
| XMOS retrieving string failed                                              | 1         | 1.61%   |
| XMOS iFi (by AMR) HD USB Audio                                             | 1         | 1.61%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 1.61%   |
| Nvidia High Definition Audio Controller                                    | 1         | 1.61%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 1.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.61%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.61%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.61%   |
| Intel 82801CA/CAM AC'97 Audio Controller                                   | 1         | 1.61%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 1.61%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 1.61%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1         | 1.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 11        | 23.4%   |
| Samsung Electronics | 11        | 23.4%   |
| Unknown             | 9         | 19.15%  |
| Kingston            | 6         | 12.77%  |
| Micron Technology   | 3         | 6.38%   |
| Corsair             | 3         | 6.38%   |
| Ramaxel Technology  | 1         | 2.13%   |
| Nanya Technology    | 1         | 2.13%   |
| A-DATA Technology   | 1         | 2.13%   |
| Unknown             | 1         | 2.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s           | 3         | 6.25%   |
| Unknown RAM Module 1GB SODIMM DDR2                              | 2         | 4.17%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 2         | 4.17%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s           | 2         | 4.17%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                     | 1         | 2.08%   |
| Unknown RAM Module 512MB SODIMM SDRAM                           | 1         | 2.08%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                     | 1         | 2.08%   |
| Unknown RAM Module 4096MB SODIMM DDR2                           | 1         | 2.08%   |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s                     | 1         | 2.08%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                          | 1         | 2.08%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                   | 1         | 2.08%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 1         | 2.08%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s       | 1         | 2.08%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 2.08%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 2.08%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s          | 1         | 2.08%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s          | 1         | 2.08%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s          | 1         | 2.08%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB Row Of Chips DDR4 2400MT/s | 1         | 2.08%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s         | 1         | 2.08%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s           | 1         | 2.08%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 1067MT/s           | 1         | 2.08%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s           | 1         | 2.08%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s           | 1         | 2.08%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s           | 1         | 2.08%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s           | 1         | 2.08%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s           | 1         | 2.08%   |
| Ramaxel RAM RMT3020EF48E8W1333 2GB SODIMM DDR3 1334MT/s         | 1         | 2.08%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s            | 1         | 2.08%   |
| Micron RAM MT36KSF2G72PZ-1G6E 8GB SODIMM DDR3 1600MT/s          | 1         | 2.08%   |
| Micron RAM 8ATF1G64HZ-2G3H1R 8GB SODIMM DDR4 2400MT/s           | 1         | 2.08%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s           | 1         | 2.08%   |
| Kingston RAM KNWMX1-ETB 4GB SODIMM DDR3 1600MT/s                | 1         | 2.08%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s         | 1         | 2.08%   |
| Kingston RAM 9905744-023.A00G 16384MB SODIMM DDR4 2133MT/s      | 1         | 2.08%   |
| Kingston RAM 9905428-417.A00LF 8GB Chip DDR3 1600MT/s           | 1         | 2.08%   |
| Kingston RAM 9905428-012.A00LF 4GB SODIMM DDR3 1333MT/s         | 1         | 2.08%   |
| Kingston RAM 9905428-005.A02LF 4096MB SODIMM DDR3 533MT/s       | 1         | 2.08%   |
| Corsair RAM Module 4096MB SODIMM DDR3 1067MT/s                  | 1         | 2.08%   |
| Corsair RAM CMSO8GX3M1C1600C11 8GB SODIMM DDR3 1600MT/s         | 1         | 2.08%   |
| Corsair RAM CMSO4GX3M1C1333C9 4GB SODIMM DDR3 1333MT/s          | 1         | 2.08%   |
| A-DATA RAM Module 16384MB SODIMM DDR4 2400MT/s                  | 1         | 2.08%   |
| Unknown                                                         | 1         | 2.08%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind  | Notebooks | Percent |
|-------|-----------|---------|
| DDR3  | 28        | 65.12%  |
| DDR4  | 8         | 18.6%   |
| DDR2  | 4         | 9.3%    |
| SDRAM | 3         | 6.98%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 41        | 95.35%  |
| Row Of Chips | 1         | 2.33%   |
| Chip         | 1         | 2.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 18        | 40.91%  |
| 8192  | 10        | 22.73%  |
| 2048  | 9         | 20.45%  |
| 16384 | 4         | 9.09%   |
| 1024  | 2         | 4.55%   |
| 512   | 1         | 2.27%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 14        | 32.56%  |
| Unknown | 6         | 13.95%  |
| 2400    | 5         | 11.63%  |
| 1333    | 5         | 11.63%  |
| 1334    | 4         | 9.3%    |
| 1067    | 4         | 9.3%    |
| 2667    | 2         | 4.65%   |
| 2133    | 1         | 2.33%   |
| 667     | 1         | 2.33%   |
| 533     | 1         | 2.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Samsung ML-1610 Mono Laser Printer | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 11        | 36.67%  |
| Microdia                      | 4         | 13.33%  |
| Realtek Semiconductor         | 3         | 10%     |
| Acer                          | 3         | 10%     |
| Sunplus Innovation Technology | 2         | 6.67%   |
| Lite-On Technology            | 2         | 6.67%   |
| IMC Networks                  | 2         | 6.67%   |
| Syntek                        | 1         | 3.33%   |
| Quanta                        | 1         | 3.33%   |
| Lenovo                        | 1         | 3.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Chicony integrated camera                | 3         | 10%     |
| Lite-On Integrated Camera                | 2         | 6.67%   |
| Acer Integrated Camera                   | 2         | 6.67%   |
| Syntek Lenovo EasyCamera                 | 1         | 3.33%   |
| Sunplus Laptop_Integrated_Webcam_FHD     | 1         | 3.33%   |
| Sunplus ASUS Webcam                      | 1         | 3.33%   |
| Realtek Realtek USB2.0 PC Camera         | 1         | 3.33%   |
| Realtek Integrated Webcam HD             | 1         | 3.33%   |
| Realtek Integrated Webcam                | 1         | 3.33%   |
| Quanta USB2.0 HD UVC WebCam              | 1         | 3.33%   |
| Microdia Sonix USB 2.0 Camera            | 1         | 3.33%   |
| Microdia Laptop_Integrated_Webcam_2M     | 1         | 3.33%   |
| Microdia Integrated Webcam HD            | 1         | 3.33%   |
| Microdia Integrated Webcam               | 1         | 3.33%   |
| Lenovo Integrated Webcam [R5U877]        | 1         | 3.33%   |
| IMC Networks UVC VGA Webcam              | 1         | 3.33%   |
| IMC Networks Integrated Webcam           | 1         | 3.33%   |
| Chicony WebCam                           | 1         | 3.33%   |
| Chicony VGA 24fps UVC Webcam             | 1         | 3.33%   |
| Chicony TOSHIBA Web Camera - FHD         | 1         | 3.33%   |
| Chicony Sonix ST50220 USB Video Camera   | 1         | 3.33%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 1         | 3.33%   |
| Chicony HP HD Camera                     | 1         | 3.33%   |
| Chicony FJ Camera                        | 1         | 3.33%   |
| Chicony 2.0M UVC Webcam / CNF7129        | 1         | 3.33%   |
| Acer SunplusIT Integrated Camera         | 1         | 3.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 2         | 28.57%  |
| Upek             | 2         | 28.57%  |
| AuthenTec        | 2         | 28.57%  |
| Synaptics        | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 28.57%  |
| Validity Sensors VFS Fingerprint sensor                | 1         | 14.29%  |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 14.29%  |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 14.29%  |
| AuthenTec AuthenTec Inc. AES2660                       | 1         | 14.29%  |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 14.29%  |

Chipcard Vendor
---------------

Chipcard module vendors

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart_bsd/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 24        | 50%     |
| 2     | 12        | 25%     |
| 3     | 7         | 14.58%  |
| 0     | 3         | 6.25%   |
| 5     | 1         | 2.08%   |
| 4     | 1         | 2.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 34        | 45.95%  |
| Firewire controller      | 8         | 10.81%  |
| Card reader              | 8         | 10.81%  |
| Bluetooth                | 7         | 9.46%   |
| Fingerprint reader       | 5         | 6.76%   |
| Net/wireless             | 4         | 5.41%   |
| Storage                  | 2         | 2.7%    |
| Graphics card            | 2         | 2.7%    |
| Storage/ata              | 1         | 1.35%   |
| Sound                    | 1         | 1.35%   |
| Network                  | 1         | 1.35%   |
| Net/ethernet             | 1         | 1.35%   |

