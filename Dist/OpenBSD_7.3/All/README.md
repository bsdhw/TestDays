OpenBSD 7.3 - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for OpenBSD 7.3.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/OpenBSD_7.3/Desktop/README.md) and [notebooks](/Dist/OpenBSD_7.3/Notebook/README.md).

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 76

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| HP            | ProLiant DL360 Gen9         | Server      | [63c10b6ae5](https://bsd-hardware.info/?probe=63c10b6ae5) | Aug 11, 2023 |
| Apple         | MacBookAir4,2               | Notebook    | [b1c97a3a9d](https://bsd-hardware.info/?probe=b1c97a3a9d) | Aug 09, 2023 |
| MSI           | MS-7623                     | Desktop     | [189fb4d7cc](https://bsd-hardware.info/?probe=189fb4d7cc) | Aug 08, 2023 |
| Apple         | MacBookAir4,2               | Notebook    | [4fdd124b61](https://bsd-hardware.info/?probe=4fdd124b61) | Aug 07, 2023 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [e74d459c5a](https://bsd-hardware.info/?probe=e74d459c5a) | Jul 28, 2023 |
| Lenovo        | ThinkPad T410 2522NP6       | Notebook    | [194b8efa98](https://bsd-hardware.info/?probe=194b8efa98) | Jul 25, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [d4a26f9214](https://bsd-hardware.info/?probe=d4a26f9214) | Jul 24, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [461ad23cc9](https://bsd-hardware.info/?probe=461ad23cc9) | Jul 24, 2023 |
| Lenovo        | B590 20208                  | Notebook    | [ce1aade2c0](https://bsd-hardware.info/?probe=ce1aade2c0) | Jul 24, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [1ac1ddd084](https://bsd-hardware.info/?probe=1ac1ddd084) | Jul 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [173fe60308](https://bsd-hardware.info/?probe=173fe60308) | Jul 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [26e44ab6e6](https://bsd-hardware.info/?probe=26e44ab6e6) | Jul 23, 2023 |
| ASUSTek       | 900                         | Notebook    | [2e55f5d4cc](https://bsd-hardware.info/?probe=2e55f5d4cc) | Jul 20, 2023 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | Notebook    | [386a80104d](https://bsd-hardware.info/?probe=386a80104d) | Jul 19, 2023 |
| IBM           | ThinkPad T43 1871F1G        | Notebook    | [d6fbc6ebfb](https://bsd-hardware.info/?probe=d6fbc6ebfb) | Jul 18, 2023 |
| Lenovo        | B590 20208                  | Notebook    | [f734b93999](https://bsd-hardware.info/?probe=f734b93999) | Jul 16, 2023 |
| Sony          | VPCX115KX                   | Notebook    | [9dab449a23](https://bsd-hardware.info/?probe=9dab449a23) | Jul 15, 2023 |
| Tactus        | GeoBook 140                 | Notebook    | [4b7383c876](https://bsd-hardware.info/?probe=4b7383c876) | Jul 11, 2023 |
| Sony          | VGC-RB41M                   | Desktop     | [95804a1f40](https://bsd-hardware.info/?probe=95804a1f40) | Jun 28, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS (W... | Desktop     | [4d99bc4b63](https://bsd-hardware.info/?probe=4d99bc4b63) | Jun 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS (W... | Desktop     | [8866724f46](https://bsd-hardware.info/?probe=8866724f46) | Jun 27, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [ff83a965d2](https://bsd-hardware.info/?probe=ff83a965d2) | Jun 15, 2023 |
| Lenovo        | ThinkPad T430 2344BZU       | Notebook    | [01df487b47](https://bsd-hardware.info/?probe=01df487b47) | Jun 14, 2023 |
| Gigabyte      | G41MT-S2                    | Desktop     | [355202536f](https://bsd-hardware.info/?probe=355202536f) | Jun 07, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [9f18b1b304](https://bsd-hardware.info/?probe=9f18b1b304) | Jun 06, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [85c18dbbb5](https://bsd-hardware.info/?probe=85c18dbbb5) | Jun 06, 2023 |
| Toshiba       | NB250                       | Notebook    | [62c572e895](https://bsd-hardware.info/?probe=62c572e895) | May 27, 2023 |
| Tactus        | GeoFlex 110                 | Notebook    | [df93ad7e83](https://bsd-hardware.info/?probe=df93ad7e83) | May 27, 2023 |
| Lenovo        | ThinkPad X140e 20BMS03E0... | Notebook    | [580c52399f](https://bsd-hardware.info/?probe=580c52399f) | May 25, 2023 |
| Lenovo        | ThinkPad X140e 20BMS03E0... | Notebook    | [84e3ac62d5](https://bsd-hardware.info/?probe=84e3ac62d5) | May 23, 2023 |
| Unknown       | Apple MacBook Pro (13-in... | Notebook    | [5e25a49c65](https://bsd-hardware.info/?probe=5e25a49c65) | May 20, 2023 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [4c8047dca3](https://bsd-hardware.info/?probe=4c8047dca3) | May 19, 2023 |
| VIA Techno... | VT82C597                    | Desktop     | [d73db58e48](https://bsd-hardware.info/?probe=d73db58e48) | May 19, 2023 |
| Lenovo        | ThinkPad X201 3323BBG       | Notebook    | [7b529b0888](https://bsd-hardware.info/?probe=7b529b0888) | May 17, 2023 |
| HP            | 0A60h                       | Desktop     | [98e9deff3d](https://bsd-hardware.info/?probe=98e9deff3d) | May 16, 2023 |
| Lenovo        | ThinkPad T61 7659AS5        | Notebook    | [7732b2cfa7](https://bsd-hardware.info/?probe=7732b2cfa7) | May 15, 2023 |
| PC Engines    | APU2                        | Desktop     | [62fef2616b](https://bsd-hardware.info/?probe=62fef2616b) | May 15, 2023 |
| Lenovo        | ThinkPad T61 7659AS5        | Notebook    | [b6071c549a](https://bsd-hardware.info/?probe=b6071c549a) | May 15, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [2ce057e389](https://bsd-hardware.info/?probe=2ce057e389) | May 14, 2023 |
| ASUSTek       | M3A78-EMH HDMI              | Desktop     | [b4bf04ac2f](https://bsd-hardware.info/?probe=b4bf04ac2f) | May 13, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | Desktop     | [fa87f4741a](https://bsd-hardware.info/?probe=fa87f4741a) | May 13, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | Desktop     | [bd81294acc](https://bsd-hardware.info/?probe=bd81294acc) | May 13, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [cace71018f](https://bsd-hardware.info/?probe=cace71018f) | May 11, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [4353bb0195](https://bsd-hardware.info/?probe=4353bb0195) | May 09, 2023 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [be83fbb0f2](https://bsd-hardware.info/?probe=be83fbb0f2) | May 09, 2023 |
| Lenovo        | ThinkPad T410 2537N24       | Notebook    | [6cd0f02045](https://bsd-hardware.info/?probe=6cd0f02045) | May 08, 2023 |
| Matsushita... | CF-48V4KNDQM                | Notebook    | [79f10d24d6](https://bsd-hardware.info/?probe=79f10d24d6) | May 07, 2023 |
| ASUSTek       | 1000HE                      | Notebook    | [36214f8bed](https://bsd-hardware.info/?probe=36214f8bed) | May 07, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [d2bd7a8764](https://bsd-hardware.info/?probe=d2bd7a8764) | May 07, 2023 |
| Lenovo        | ThinkPad T500 205663G       | Notebook    | [d706da9400](https://bsd-hardware.info/?probe=d706da9400) | May 06, 2023 |
| Lenovo        | ThinkPad T480s 20L8A00KC... | Notebook    | [44ddee0eec](https://bsd-hardware.info/?probe=44ddee0eec) | May 06, 2023 |
| Matsushita... | CF-51RCVDNLM                | Notebook    | [105a885451](https://bsd-hardware.info/?probe=105a885451) | May 05, 2023 |
| Lenovo        | ThinkPad T420s 41742BU      | Notebook    | [161fe49de4](https://bsd-hardware.info/?probe=161fe49de4) | May 05, 2023 |
| Lenovo        | ThinkPad X230 2325T4T       | Notebook    | [00303b7a59](https://bsd-hardware.info/?probe=00303b7a59) | May 05, 2023 |
| Lenovo        | ThinkPad X220 429043U       | Notebook    | [bb714a4350](https://bsd-hardware.info/?probe=bb714a4350) | May 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [28e76d5531](https://bsd-hardware.info/?probe=28e76d5531) | May 04, 2023 |
| Lenovo        | ThinkPad T430 2347GZU       | Notebook    | [8c3f486dbc](https://bsd-hardware.info/?probe=8c3f486dbc) | May 03, 2023 |
| Panasonic     | CF-52PFPBSFQ                | Notebook    | [e2c3df29b5](https://bsd-hardware.info/?probe=e2c3df29b5) | May 03, 2023 |
| Panasonic     | CF-53AAGHYDM                | Notebook    | [c7daf17edb](https://bsd-hardware.info/?probe=c7daf17edb) | May 02, 2023 |
| Lenovo        | ThinkPad X260 20F5S2GM00    | Notebook    | [c4af168c4a](https://bsd-hardware.info/?probe=c4af168c4a) | May 01, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [cf504f51df](https://bsd-hardware.info/?probe=cf504f51df) | May 01, 2023 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [44ea9fb6ae](https://bsd-hardware.info/?probe=44ea9fb6ae) | Apr 30, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [247810c987](https://bsd-hardware.info/?probe=247810c987) | Apr 24, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | Desktop     | [827308827b](https://bsd-hardware.info/?probe=827308827b) | Apr 24, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [243a9c2f22](https://bsd-hardware.info/?probe=243a9c2f22) | Apr 22, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [c26c1111c6](https://bsd-hardware.info/?probe=c26c1111c6) | Apr 21, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | Desktop     | [a6141b809a](https://bsd-hardware.info/?probe=a6141b809a) | Apr 21, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [0ebba481d1](https://bsd-hardware.info/?probe=0ebba481d1) | Apr 14, 2023 |
| Lenovo        | ThinkPad T440s 20ARA07PL... | Notebook    | [04ddab3620](https://bsd-hardware.info/?probe=04ddab3620) | Apr 14, 2023 |
| Lenovo        | ThinkPad X230 23257EP       | Notebook    | [e94085cd2d](https://bsd-hardware.info/?probe=e94085cd2d) | Apr 12, 2023 |
| ASUSTek       | P10S-I Series               | Desktop     | [5084c2b77f](https://bsd-hardware.info/?probe=5084c2b77f) | Apr 11, 2023 |
| Apple         | MacPro1,1                   | Desktop     | [6843822d8c](https://bsd-hardware.info/?probe=6843822d8c) | Apr 11, 2023 |
| PC Engines    | APU2                        | Desktop     | [cdcdfe6e0b](https://bsd-hardware.info/?probe=cdcdfe6e0b) | Apr 10, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [a149d0b4b5](https://bsd-hardware.info/?probe=a149d0b4b5) | Apr 10, 2023 |
| Lenovo        | ThinkPad T450s 20BW001KL... | Notebook    | [4f6a7e2739](https://bsd-hardware.info/?probe=4f6a7e2739) | Apr 02, 2023 |
| Elpitech      | ET101-A1                    | Desktop     | [0172697883](https://bsd-hardware.info/?probe=0172697883) | Mar 10, 2023 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 48        | 80%     |
| i386  | 10        | 16.67%  |
| arm64 | 2         | 3.33%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 51        | 85%     |
| GNOME        | 6         | 10%     |
| XFCE         | 2         | 3.33%   |
| MATE         | 1         | 1.67%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 51        | 85%     |
| Console | 9         | 15%     |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 60        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 50        | 83.33%  |
| en_US   | 4         | 6.67%   |
| C       | 2         | 3.33%   |
| zh_TW   | 1         | 1.67%   |
| ru_RU   | 1         | 1.67%   |
| pl_PL   | 1         | 1.67%   |
| es_ES   | 1         | 1.67%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 31        | 51.67%  |
| EFI  | 29        | 48.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ffs  | 60        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| MBR  | 33        | 55%     |
| GPT  | 27        | 45%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 24        | 40%     |
| ASUSTek Computer               | 9         | 15%     |
| Hewlett-Packard                | 4         | 6.67%   |
| Panasonic                      | 3         | 5%      |
| Tactus                         | 2         | 3.33%   |
| Sony                           | 2         | 3.33%   |
| PC Engines                     | 2         | 3.33%   |
| MSI                            | 2         | 3.33%   |
| Matsushita Electric Industrial | 2         | 3.33%   |
| Gigabyte Technology            | 2         | 3.33%   |
| Apple                          | 2         | 3.33%   |
| VIA Technologies               | 1         | 1.67%   |
| Toshiba                        | 1         | 1.67%   |
| IBM                            | 1         | 1.67%   |
| Fujitsu                        | 1         | 1.67%   |
| Elpitech                       | 1         | 1.67%   |
| Unknown                        | 1         | 1.67%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| PC Engines APU2                             | 2         | 3.33%   |
| ASUS PRIME B650-PLUS                        | 2         | 3.33%   |
| VIA VT82C597                                | 1         | 1.67%   |
| Toshiba NB250                               | 1         | 1.67%   |
| Tactus GeoFlex 110                          | 1         | 1.67%   |
| Tactus GeoBook 140                          | 1         | 1.67%   |
| Sony VPCX115KX                              | 1         | 1.67%   |
| Sony VGC-RB41M                              | 1         | 1.67%   |
| Panasonic CFSX4-1                           | 1         | 1.67%   |
| Panasonic CF-53AAGHYDM                      | 1         | 1.67%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 1.67%   |
| MSI MS-7623                                 | 1         | 1.67%   |
| MSI MS-7592                                 | 1         | 1.67%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 1.67%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 1.67%   |
| Lenovo V14 G2 ITL 82NM                      | 1         | 1.67%   |
| Lenovo ThinkPad X270 W10DG 20K5S0TT1N       | 1         | 1.67%   |
| Lenovo ThinkPad X260 20F5S2GM00             | 1         | 1.67%   |
| Lenovo ThinkPad X260 20F5S10W0H             | 1         | 1.67%   |
| Lenovo ThinkPad X230 2325T4T                | 1         | 1.67%   |
| Lenovo ThinkPad X230 23257EP                | 1         | 1.67%   |
| Lenovo ThinkPad X220 429043U                | 1         | 1.67%   |
| Lenovo ThinkPad X201 3323BBG                | 1         | 1.67%   |
| Lenovo ThinkPad X140e 20BMS03E00            | 1         | 1.67%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS13H00    | 1         | 1.67%   |
| Lenovo ThinkPad T61 7659AS5                 | 1         | 1.67%   |
| Lenovo ThinkPad T500 205663G                | 1         | 1.67%   |
| Lenovo ThinkPad T480s 20L8A00KCL            | 1         | 1.67%   |
| Lenovo ThinkPad T450s 20BW001KLM            | 1         | 1.67%   |
| Lenovo ThinkPad T440s 20ARA07PLM            | 1         | 1.67%   |
| Lenovo ThinkPad T430 2347GZU                | 1         | 1.67%   |
| Lenovo ThinkPad T430 2344BZU                | 1         | 1.67%   |
| Lenovo ThinkPad T420s 41742BU               | 1         | 1.67%   |
| Lenovo ThinkPad T410 2537N24                | 1         | 1.67%   |
| Lenovo ThinkPad T410 2522NP6                | 1         | 1.67%   |
| Lenovo ThinkPad T14 Gen 1 20UES5NW00        | 1         | 1.67%   |
| Lenovo ThinkPad E15 Gen 4 21EDCTO1WW        | 1         | 1.67%   |
| Lenovo G570 20079                           | 1         | 1.67%   |
| Lenovo B590 20208                           | 1         | 1.67%   |
| IBM ThinkPad T43 1871F1G                    | 1         | 1.67%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad                             | 21        | 35%     |
| ASUS PRIME                                  | 3         | 5%      |
| PC Engines APU2                             | 2         | 3.33%   |
| HP Pavilion                                 | 2         | 3.33%   |
| ASUS TUF                                    | 2         | 3.33%   |
| VIA VT82C597                                | 1         | 1.67%   |
| Toshiba NB250                               | 1         | 1.67%   |
| Tactus GeoFlex                              | 1         | 1.67%   |
| Tactus GeoBook                              | 1         | 1.67%   |
| Sony VPCX115KX                              | 1         | 1.67%   |
| Sony VGC-RB41M                              | 1         | 1.67%   |
| Panasonic CFSX4-1                           | 1         | 1.67%   |
| Panasonic CF-53AAGHYDM                      | 1         | 1.67%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 1.67%   |
| MSI MS-7623                                 | 1         | 1.67%   |
| MSI MS-7592                                 | 1         | 1.67%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 1.67%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 1.67%   |
| Lenovo V14                                  | 1         | 1.67%   |
| Lenovo G570                                 | 1         | 1.67%   |
| Lenovo B590                                 | 1         | 1.67%   |
| IBM ThinkPad                                | 1         | 1.67%   |
| HP ProLiant                                 | 1         | 1.67%   |
| HP Compaq                                   | 1         | 1.67%   |
| Gigabyte G41MT-S2                           | 1         | 1.67%   |
| Gigabyte B250M-Gaming                       | 1         | 1.67%   |
| Fujitsu LIFEBOOK                            | 1         | 1.67%   |
| Elpitech ET101-A1                           | 1         | 1.67%   |
| ASUS P10S-I                                 | 1         | 1.67%   |
| ASUS M3A78-EMH                              | 1         | 1.67%   |
| ASUS 900                                    | 1         | 1.67%   |
| ASUS 1000HE                                 | 1         | 1.67%   |
| Apple MacPro1                               | 1         | 1.67%   |
| Apple MacBookAir4                           | 1         | 1.67%   |
| Unknown                                     | 1         | 1.67%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2010    | 8         | 13.33%  |
| 2011    | 5         | 8.33%   |
| 2023    | 4         | 6.67%   |
| 2022    | 4         | 6.67%   |
| 2019    | 4         | 6.67%   |
| 2016    | 4         | 6.67%   |
| 2013    | 4         | 6.67%   |
| 2021    | 3         | 5%      |
| 2018    | 3         | 5%      |
| 2015    | 3         | 5%      |
| 2012    | 3         | 5%      |
| 2009    | 3         | 5%      |
| 2006    | 3         | 5%      |
| 2007    | 2         | 3.33%   |
| Unknown | 2         | 3.33%   |
| 2020    | 1         | 1.67%   |
| 2017    | 1         | 1.67%   |
| 2014    | 1         | 1.67%   |
| 2005    | 1         | 1.67%   |
| 2002    | 1         | 1.67%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 40        | 66.67%  |
| Desktop  | 19        | 31.67%  |
| Server   | 1         | 1.67%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 57        | 95%     |
| Yes  | 3         | 5%      |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 16        | 26.23%  |
| 4.01-8.0    | 15        | 24.59%  |
| 3.01-4.0    | 7         | 11.48%  |
| 2.01-3.0    | 5         | 8.2%    |
| 64.01-256.0 | 5         | 8.2%    |
| 16.01-24.0  | 5         | 8.2%    |
| 32.01-64.0  | 2         | 3.28%   |
| 0.51-1.0    | 2         | 3.28%   |
| 0.01-0.5    | 2         | 3.28%   |
| 24.01-32.0  | 1         | 1.64%   |
| 1.01-2.0    | 1         | 1.64%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 47        | 78.33%  |
| 0        | 5         | 8.33%   |
| 4.01-8.0 | 3         | 5%      |
| 1.01-2.0 | 3         | 5%      |
| 0.51-1.0 | 2         | 3.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 36        | 60%     |
| 2      | 12        | 20%     |
| 3      | 8         | 13.33%  |
| 0      | 2         | 3.33%   |
| 8      | 1         | 1.67%   |
| 6      | 1         | 1.67%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 60        | 100%    |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 88.33%  |
| No        | 7         | 11.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 41        | 68.33%  |
| No        | 19        | 31.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 31        | 50.82%  |
| Yes       | 30        | 49.18%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country  | Computers | Percent |
|----------|-----------|---------|
| Canada   | 14        | 23.33%  |
| Russia   | 13        | 21.67%  |
| Germany  | 5         | 8.33%   |
| Brazil   | 5         | 8.33%   |
| USA      | 4         | 6.67%   |
| Uruguay  | 3         | 5%      |
| Mexico   | 3         | 5%      |
| Spain    | 2         | 3.33%   |
| Romania  | 2         | 3.33%   |
| Poland   | 2         | 3.33%   |
| Italy    | 2         | 3.33%   |
| Colombia | 2         | 3.33%   |
| Ukraine  | 1         | 1.67%   |
| Taiwan   | 1         | 1.67%   |
| China    | 1         | 1.67%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Saint-Laurent    | 14        | 23.33%  |
| St Petersburg    | 8         | 13.33%  |
| Blumenau         | 5         | 8.33%   |
| Sun Prairie      | 3         | 5%      |
| Puebla City      | 3         | 5%      |
| Montevideo       | 3         | 5%      |
| Nuremberg        | 2         | 3.33%   |
| Moscow           | 2         | 3.33%   |
| Montería        | 2         | 3.33%   |
| Milan            | 2         | 3.33%   |
| Lübeck          | 2         | 3.33%   |
| Wroclaw          | 1         | 1.67%   |
| Taipei           | 1         | 1.67%   |
| Swilcza          | 1         | 1.67%   |
| Podolsk          | 1         | 1.67%   |
| Oltenita         | 1         | 1.67%   |
| Navalcarnero     | 1         | 1.67%   |
| Monheim am Rhein | 1         | 1.67%   |
| Krasnodar        | 1         | 1.67%   |
| Harbin           | 1         | 1.67%   |
| Cherepovets      | 1         | 1.67%   |
| Brovary          | 1         | 1.67%   |
| Brasov           | 1         | 1.67%   |
| Barcelona        | 1         | 1.67%   |
| Austin           | 1         | 1.67%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| NVMe                | 13        | 17     | 17.11%  |
| Samsung Electronics | 10        | 15     | 13.16%  |
| WDC                 | 8         | 8      | 10.53%  |
| Kingston            | 6         | 6      | 7.89%   |
| Hitachi             | 6         | 6      | 7.89%   |
| Seagate             | 5         | 6      | 6.58%   |
| SanDisk             | 4         | 6      | 5.26%   |
| Apacer              | 3         | 3      | 3.95%   |
| OPENBSD             | 2         | 2      | 2.63%   |
| Intenso             | 2         | 2      | 2.63%   |
| Intel               | 2         | 2      | 2.63%   |
| Fujitsu             | 2         | 2      | 2.63%   |
| Crucial             | 2         | 3      | 2.63%   |
| A-DATA Technology   | 2         | 2      | 2.63%   |
| Verbatim            | 1         | 1      | 1.32%   |
| Union Memory        | 1         | 1      | 1.32%   |
| SMI                 | 1         | 1      | 1.32%   |
| PNY                 | 1         | 2      | 1.32%   |
| KIOXIA-EXCERIA      | 1         | 1      | 1.32%   |
| HGST                | 1         | 1      | 1.32%   |
| ASUSTek Computer    | 1         | 2      | 1.32%   |
| Apple               | 1         | 1      | 1.32%   |
| AMD                 | 1         | 1      | 1.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| SanDisk SSD PLUS 120GB              | 2         | 2.47%   |
| SanDisk Extreme SSD 500GB           | 2         | 2.47%   |
| NVMe Samsung SSD 980 500GB          | 2         | 2.47%   |
| NVMe SAMSUNG MZVLW256 256GB         | 2         | 2.47%   |
| Kingston SA400S37480G 480GB         | 2         | 2.47%   |
| Intenso SSD 256GB                   | 2         | 2.47%   |
| Intel SSDSC2BW480H6 480GB           | 2         | 2.47%   |
| WDC WD7500BPKX-00HPJT0 752GB        | 1         | 1.23%   |
| WDC WD7500BPKT-75PK4T0 752GB        | 1         | 1.23%   |
| WDC WD7500BPKT-00PK4T0 752GB        | 1         | 1.23%   |
| WDC WD5000LPLX-00ZNTT0 500GB        | 1         | 1.23%   |
| WDC WD5000AZLX-00K2TA0 500GB        | 1         | 1.23%   |
| WDC WD3200BEVE-00A0HT0 320GB        | 1         | 1.23%   |
| WDC WD20PURX-64P6ZY0 2TB            | 1         | 1.23%   |
| WDC WD10JPLX-00MBPT0 1TB            | 1         | 1.23%   |
| Verbatim STORE N GO 64GB            | 1         | 1.23%   |
| Union Memory RTOTJ128VGD2EYX 128GB  | 1         | 1.23%   |
| SMI USB DISK 18302PB                | 1         | 1.23%   |
| Seagate USB 480GB                   | 1         | 1.23%   |
| Seagate ST9160821A 160GB            | 1         | 1.23%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1.23%   |
| Seagate ST3500414CS 500GB           | 1         | 1.23%   |
| Seagate ST3250824AS P 250GB         | 1         | 1.23%   |
| Seagate ST3250318AS 250GB           | 1         | 1.23%   |
| SanDisk Cruzer Blade 64GB           | 1         | 1.23%   |
| Samsung SSD 870 QVO 2TB             | 1         | 1.23%   |
| Samsung SSD 870 EVO 500GB           | 1         | 1.23%   |
| Samsung SSD 860 EVO M.2 1TB         | 1         | 1.23%   |
| Samsung SSD 850 EVO 500GB           | 1         | 1.23%   |
| Samsung SSD 840 EVO 250GB           | 1         | 1.23%   |
| Samsung MZ7TD128HAFV-000L1 128GB    | 1         | 1.23%   |
| Samsung MZ7PC128HAFU-000L1 128GB    | 1         | 1.23%   |
| Samsung MMCRE28GFMXP-MVB 128GB      | 1         | 1.23%   |
| Samsung HD161HJ 160GB               | 1         | 1.23%   |
| Samsung Flash Drive FIT 32GB        | 1         | 1.23%   |
| PNY CS900 1TB SSD                   | 1         | 1.23%   |
| OPENBSD SR RAID 5 9.9TB             | 1         | 1.23%   |
| OPENBSD SR RAID 1 2TB               | 1         | 1.23%   |
| NVMe WDBRPG5000ANC-WR 500GB         | 1         | 1.23%   |
| NVMe TOSHIBA-RC100 240GB            | 1         | 1.23%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| NVMe                | 9         | 13     | 24.32%  |
| WDC                 | 8         | 8      | 21.62%  |
| Hitachi             | 6         | 6      | 16.22%  |
| Seagate             | 5         | 6      | 13.51%  |
| Samsung Electronics | 2         | 2      | 5.41%   |
| OPENBSD             | 2         | 2      | 5.41%   |
| Fujitsu             | 2         | 2      | 5.41%   |
| Verbatim            | 1         | 1      | 2.7%    |
| SMI                 | 1         | 1      | 2.7%    |
| HGST                | 1         | 1      | 2.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 13     | 20.51%  |
| Kingston            | 6         | 6      | 15.38%  |
| SanDisk             | 4         | 6      | 10.26%  |
| NVMe                | 4         | 4      | 10.26%  |
| Apacer              | 3         | 3      | 7.69%   |
| Intenso             | 2         | 2      | 5.13%   |
| Intel               | 2         | 2      | 5.13%   |
| Crucial             | 2         | 3      | 5.13%   |
| A-DATA Technology   | 2         | 2      | 5.13%   |
| Union Memory        | 1         | 1      | 2.56%   |
| PNY                 | 1         | 2      | 2.56%   |
| KIOXIA-EXCERIA      | 1         | 1      | 2.56%   |
| ASUSTek Computer    | 1         | 2      | 2.56%   |
| Apple               | 1         | 1      | 2.56%   |
| AMD                 | 1         | 1      | 2.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 37        | 49     | 55.22%  |
| HDD  | 30        | 42     | 44.78%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 57        | 91     | 100%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 49        | 66     | 77.78%  |
| 1.01-2.0        | 6         | 16     | 9.52%   |
| 0.51-1.0        | 6         | 7      | 9.52%   |
| More than 100.0 | 1         | 1      | 1.59%   |
| 4.01-10.0       | 1         | 1      | 1.59%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 20        | 32.79%  |
| 21-50          | 15        | 24.59%  |
| 251-500        | 11        | 18.03%  |
| 51-100         | 6         | 9.84%   |
| 1-20           | 3         | 4.92%   |
| More than 3000 | 2         | 3.28%   |
| 1001-2000      | 2         | 3.28%   |
| 501-1000       | 2         | 3.28%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 46        | 75.41%  |
| 21-50          | 6         | 9.84%   |
| 101-250        | 3         | 4.92%   |
| 51-100         | 3         | 4.92%   |
| More than 3000 | 1         | 1.64%   |
| 251-500        | 1         | 1.64%   |
| 2001-3000      | 1         | 1.64%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Intel SSDSC2BW480H6 480GB             | 2         | 2      | 25%     |
| Samsung Electronics SSD 870 EVO 500GB | 1         | 1      | 12.5%   |
| Samsung Electronics SSD 840 EVO 250GB | 1         | 1      | 12.5%   |
| Samsung Electronics HD161HJ 160GB     | 1         | 1      | 12.5%   |
| Hitachi HDS722516VLAT80 164GB         | 1         | 1      | 12.5%   |
| A-DATA Technology SP550 480GB         | 1         | 1      | 12.5%   |
| A-DATA Technology SP550 240GB         | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 37.5%   |
| Intel               | 2         | 2      | 25%     |
| A-DATA Technology   | 2         | 2      | 25%     |
| Hitachi             | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 50%     |
| Hitachi             | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 6         | 6      | 75%     |
| HDD  | 2         | 2      | 25%     |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 42        | 59     | 64.62%  |
| Detected | 15        | 24     | 23.08%  |
| Malfunc  | 8         | 8      | 12.31%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 42        | 61.76%  |
| AMD                            | 9         | 13.24%  |
| Samsung Electronics            | 5         | 7.35%   |
| Kingston Technology Company    | 3         | 4.41%   |
| Phison Electronics             | 2         | 2.94%   |
| VIA Technologies               | 1         | 1.47%   |
| Toshiba                        | 1         | 1.47%   |
| Solid State Storage Technology | 1         | 1.47%   |
| Silicon Motion                 | 1         | 1.47%   |
| SanDisk                        | 1         | 1.47%   |
| Hewlett-Packard                | 1         | 1.47%   |
| Artop Electronic               | 1         | 1.47%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 6         | 8%      |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 4         | 5.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 4         | 5.33%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                | 4         | 5.33%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 3         | 4%      |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 2         | 2.67%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 2         | 2.67%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 2         | 2.67%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                             | 2         | 2.67%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 2         | 2.67%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                 | 2         | 2.67%   |
| Intel 82801FBM (ICH6M) SATA Controller                                        | 2         | 2.67%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                          | 2         | 2.67%   |
| AMD FCH SATA Controller [IDE mode]                                            | 2         | 2.67%   |
| AMD 500 Series Chipset SATA Controller                                        | 2         | 2.67%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                   | 1         | 1.33%   |
| Toshiba BG3 NVMe SSD Controller                                               | 1         | 1.33%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                | 1         | 1.33%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers             | 1         | 1.33%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                    | 1         | 1.33%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                   | 1         | 1.33%   |
| Phison PS5013 E13 NVMe Controller                                             | 1         | 1.33%   |
| Phison E16 PCIe4 NVMe Controller                                              | 1         | 1.33%   |
| Kingston Company unknown                                                      | 1         | 1.33%   |
| Kingston Company NVMe Controller                                              | 1         | 1.33%   |
| Kingston Company NV1 NVMe SSD                                                 | 1         | 1.33%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                    | 1         | 1.33%   |
| Intel Tiger Lake-LP SATA Controller                                           | 1         | 1.33%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1         | 1.33%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 1         | 1.33%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]         | 1         | 1.33%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]           | 1         | 1.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                 | 1         | 1.33%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                  | 1         | 1.33%   |
| Intel 82801G (ICH7 Family) IDE Controller                                     | 1         | 1.33%   |
| Intel 82801FB/FW (ICH6/ICH6W) SATA Controller                                 | 1         | 1.33%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                      | 1         | 1.33%   |
| Intel 82801CAM IDE U100 Controller                                            | 1         | 1.33%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 1         | 1.33%   |
| Intel 631xESB/632xESB/3100 Chipset SATA IDE Controller                        | 1         | 1.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 38        | 55.88%  |
| IDE  | 16        | 23.53%  |
| NVMe | 12        | 17.65%  |
| RAID | 1         | 1.47%   |
| SCSI | 1         | 1.47%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 46        | 76.67%  |
| AMD     | 12        | 20%     |
| ARM     | 1         | 1.67%   |
| Unknown | 1         | 1.67%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz                               | 4         | 6.67%   |
| Intel Core i5-3320M CPU @ 2.60GHz                               | 4         | 6.67%   |
| Intel Core i5-2520M CPU @ 2.50GHz                               | 3         | 5%      |
| Intel Core i5 CPU M 520 @ 2.40GHz                               | 3         | 5%      |
| Intel Core i5-5300U CPU @ 2.30GHz                               | 2         | 3.33%   |
| Intel Celeron N4020 CPU @ 1.10GHz                               | 2         | 3.33%   |
| AMD GX-412TC SOC                                                | 2         | 3.33%   |
| Intel Xeon CPU E5-2697 v4 @ 2.30GHz                             | 1         | 1.67%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz                             | 1         | 1.67%   |
| Intel Xeon CPU 5150 @ 2.66GHz                                   | 1         | 1.67%   |
| Intel Pentium M processor                                       | 1         | 1.67%   |
| Intel Pentium 4 Mobile CPU 1.60GHz                              | 1         | 1.67%   |
| Intel Pentium 4 CPU 3.00GHz ("GenuineIntel" 686-class)          | 1         | 1.67%   |
| Intel Genuine CPU T2300 @ 1.66GHz                               | 1         | 1.67%   |
| Intel Core i7-8650U CPU @ 1.90GHz                               | 1         | 1.67%   |
| Intel Core i7-3520M CPU @ 2.90GHz                               | 1         | 1.67%   |
| Intel Core i5-8300H CPU @ 2.30GHz                               | 1         | 1.67%   |
| Intel Core i5-7400 CPU @ 3.00GHz                                | 1         | 1.67%   |
| Intel Core i5-6200U CPU @ 2.30GHz                               | 1         | 1.67%   |
| Intel Core i5-4300U CPU @ 1.90GHz                               | 1         | 1.67%   |
| Intel Core i5-2557M CPU @ 1.70GHz                               | 1         | 1.67%   |
| Intel Core i5-2410M CPU @ 2.30GHz                               | 1         | 1.67%   |
| Intel Core i3-3120M CPU @ 2.50GHz                               | 1         | 1.67%   |
| Intel Core i3-10100 CPU @ 3.60GHz                               | 1         | 1.67%   |
| Intel Core i3 CPU M 350 @ 2.27GHz                               | 1         | 1.67%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz                           | 1         | 1.67%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz                           | 1         | 1.67%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz                            | 1         | 1.67%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz ("GenuineIntel" 686-class) | 1         | 1.67%   |
| Intel Core 2 CPU 6420 @ 2.13GHz                                 | 1         | 1.67%   |
| Intel Celeron M processor                                       | 1         | 1.67%   |
| Intel Atom CPU Z550 @ 2.00GHz ("GenuineIntel" 686-class)        | 1         | 1.67%   |
| Intel Atom CPU N455 @ 1.66GHz ("GenuineIntel" 686-class)        | 1         | 1.67%   |
| Intel Atom CPU N280 @ 1.66GHz                                   | 1         | 1.67%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz                         | 1         | 1.67%   |
| ARM Cortex-A57 r1p3                                             | 1         | 1.67%   |
| AMD Ryzen 9 7950X 16-Core Processor                             | 1         | 1.67%   |
| AMD Ryzen 9 5950X 16-Core Processor                             | 1         | 1.67%   |
| AMD Ryzen 7 7700X 8-Core Processor                              | 1         | 1.67%   |
| AMD Ryzen 7 5825U with Radeon Graphics                          | 1         | 1.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i5     | 22        | 36.67%  |
| Other             | 3         | 5%      |
| Intel Xeon        | 3         | 5%      |
| Intel Core i3     | 3         | 5%      |
| Intel Atom        | 3         | 5%      |
| AMD Ryzen 7       | 3         | 5%      |
| Intel Pentium 4   | 2         | 3.33%   |
| Intel Core i7     | 2         | 3.33%   |
| Intel Core 2 Quad | 2         | 3.33%   |
| Intel Core 2 Duo  | 2         | 3.33%   |
| Intel Celeron     | 2         | 3.33%   |
| AMD Ryzen 9       | 2         | 3.33%   |
| AMD GX            | 2         | 3.33%   |
| Intel Pentium M   | 1         | 1.67%   |
| Intel Genuine     | 1         | 1.67%   |
| Intel Core 2      | 1         | 1.67%   |
| Intel Celeron M   | 1         | 1.67%   |
| ARM Cortex        | 1         | 1.67%   |
| AMD Ryzen 5 PRO   | 1         | 1.67%   |
| AMD Phenom        | 1         | 1.67%   |
| AMD E1            | 1         | 1.67%   |
| AMD Athlon II X2  | 1         | 1.67%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 28        | 46.67%  |
| Unknown | 11        | 18.33%  |
| 4       | 10        | 16.67%  |
| 1       | 4         | 6.67%   |
| 16      | 3         | 5%      |
| 32      | 2         | 3.33%   |
| 36      | 1         | 1.67%   |
| 12      | 1         | 1.67%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 49        | 81.67%  |
| Unknown | 9         | 15%     |
| 2       | 2         | 3.33%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 28        | 46.67%  |
| 1       | 18        | 30%     |
| Unknown | 14        | 23.33%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Skylake       | 6         | 10%     |
| IvyBridge     | 6         | 10%     |
| SandyBridge   | 5         | 8.33%   |
| Westmere      | 4         | 6.67%   |
| Core          | 4         | 6.67%   |
| Unknown       | 4         | 6.67%   |
| P6            | 3         | 5%      |
| KabyLake      | 3         | 5%      |
| Broadwell     | 3         | 5%      |
| Bonnell       | 3         | 5%      |
| Zen 3         | 2         | 3.33%   |
| Zen 2         | 2         | 3.33%   |
| Puma          | 2         | 3.33%   |
| Penryn        | 2         | 3.33%   |
| NetBurst      | 2         | 3.33%   |
| K10           | 2         | 3.33%   |
| Goldmont plus | 2         | 3.33%   |
| TigerLake     | 1         | 1.67%   |
| Jaguar        | 1         | 1.67%   |
| Haswell       | 1         | 1.67%   |
| Geode         | 1         | 1.67%   |
| CometLake     | 1         | 1.67%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 40        | 66.67%  |
| AMD                        | 10        | 16.67%  |
| Nvidia                     | 8         | 13.33%  |
| Matrox Electronics Systems | 1         | 1.67%   |
| ASPEED Technology          | 1         | 1.67%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 6         | 9.52%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 5         | 7.94%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 5         | 7.94%   |
| Intel Core Processor Integrated Graphics Controller                           | 4         | 6.35%   |
| Nvidia GK208B [GeForce GT 710]                                                | 2         | 3.17%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 2         | 3.17%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                     | 2         | 3.17%   |
| Intel HD Graphics 5500                                                        | 2         | 3.17%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 2         | 3.17%   |
| AMD Raphael                                                                   | 2         | 3.17%   |
| Nvidia GT200 [GeForce GTX 260]                                                | 1         | 1.59%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 1         | 1.59%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                           | 1         | 1.59%   |
| Nvidia GA104GL [RTX A4000]                                                    | 1         | 1.59%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                                | 1         | 1.59%   |
| Nvidia G73 [GeForce 7300 GT]                                                  | 1         | 1.59%   |
| Matrox Electronics Systems MGA G200EH                                         | 1         | 1.59%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                           | 1         | 1.59%   |
| Intel UHD Graphics 620                                                        | 1         | 1.59%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 1         | 1.59%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 1         | 1.59%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 1         | 1.59%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 1.59%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 1         | 1.59%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 1         | 1.59%   |
| Intel HD Graphics 630                                                         | 1         | 1.59%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 1         | 1.59%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                      | 1         | 1.59%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 1         | 1.59%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                              | 1         | 1.59%   |
| Intel 82915G/GV/910GL Integrated Graphics Controller                          | 1         | 1.59%   |
| Intel 4 Series Chipset Integrated Graphics Controller                         | 1         | 1.59%   |
| ASPEED Technology ASPEED Graphics Family                                      | 1         | 1.59%   |
| AMD RV770 [Radeon HD 4850]                                                    | 1         | 1.59%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 1         | 1.59%   |
| AMD RV200 [Radeon 7500/7500 LE]                                               | 1         | 1.59%   |
| AMD Robson CE [Radeon HD 6370M/7370M]                                         | 1         | 1.59%   |
| AMD Renoir                                                                    | 1         | 1.59%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                 | 1         | 1.59%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                       | 1         | 1.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 31        | 51.67%  |
| 1 x AMD        | 7         | 11.67%  |
| 2 x Intel      | 6         | 10%     |
| Other          | 5         | 8.33%   |
| 1 x Nvidia     | 4         | 6.67%   |
| Intel + Nvidia | 2         | 3.33%   |
| AMD + Nvidia   | 2         | 3.33%   |
| 1 x Matrox     | 1         | 1.67%   |
| Intel + AMD    | 1         | 1.67%   |
| 1 x ASPEED     | 1         | 1.67%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 50        | 83.33%  |
| Unknown | 10        | 16.67%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 60        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 7         | 25%     |
| Samsung Electronics | 4         | 14.29%  |
| Philips             | 3         | 10.71%  |
| ViewSonic           | 2         | 7.14%   |
| Chimei Innolux      | 2         | 7.14%   |
| TRU                 | 1         | 3.57%   |
| MSI                 | 1         | 3.57%   |
| LG Display          | 1         | 3.57%   |
| Lenovo              | 1         | 3.57%   |
| Iiyama              | 1         | 3.57%   |
| Goldstar            | 1         | 3.57%   |
| BOE                 | 1         | 3.57%   |
| BenQ                | 1         | 3.57%   |
| ASUSTek Computer    | 1         | 3.57%   |
| Apple               | 1         | 3.57%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| ViewSonic VA703-4SERIES VSC6A1E 1280x1024 340x270mm 17.1-inch        | 1         | 3.57%   |
| ViewSonic VA2418-FHD VSCD739 1920x1080 530x300mm 24.0-inch           | 1         | 3.57%   |
| TRU LCD Monitor TRU235C 1366x768 260x140mm 11.6-inch                 | 1         | 3.57%   |
| Samsung Electronics SyncMaster SAM03CF 1280x1024 340x270mm 17.1-inch | 1         | 3.57%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch | 1         | 3.57%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 310x170mm 13.9-inch | 1         | 3.57%   |
| Samsung Electronics LCD Monitor SAM0669 1920x1080                    | 1         | 3.57%   |
| Philips PHL 247E6 PHLC0E7 1920x1080 520x290mm 23.4-inch              | 1         | 3.57%   |
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                | 1         | 3.57%   |
| Philips 170S PHL0839 1280x1024 340x270mm 17.1-inch                   | 1         | 3.57%   |
| MSI MP242 MSI30A1 1920x1080 530x300mm 24.0-inch                      | 1         | 3.57%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch          | 1         | 3.57%   |
| Lenovo LCD Monitor LEN4053 1680x1050 330x210mm 15.4-inch             | 1         | 3.57%   |
| Iiyama PL2530H IVM6131 1920x1080 540x300mm 24.3-inch                 | 1         | 3.57%   |
| Goldstar LG ULTRAWIDE GSM76F9 2560x1080 800x340mm 34.2-inch          | 1         | 3.57%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 310x170mm 13.9-inch     | 1         | 3.57%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch     | 1         | 3.57%   |
| BOE LCD Monitor BOE08E2 1920x1080 340x190mm 15.3-inch                | 1         | 3.57%   |
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                   | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 310x170mm 13.9-inch       | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch        | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 310x170mm 13.9-inch        | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch        | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO173D 1920x1080 310x170mm 13.9-inch       | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO1147 1440x900 300x190mm 14.0-inch        | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch        | 1         | 3.57%   |
| ASUSTek Computer PA279 AUS2768 3840x2160 600x340mm 27.2-inch         | 1         | 3.57%   |
| Apple Color LCD APP9CDF 1440x900 290x180mm 13.4-inch                 | 1         | 3.57%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 11        | 40.74%  |
| 1366x768 (WXGA)    | 6         | 22.22%  |
| 1280x1024 (SXGA)   | 3         | 11.11%  |
| 1600x900 (HD+)     | 2         | 7.41%   |
| 1440x900 (WXGA+)   | 2         | 7.41%   |
| 3840x2160 (4K)     | 1         | 3.7%    |
| 2560x1080          | 1         | 3.7%    |
| 1680x1050 (WSXGA+) | 1         | 3.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 8         | 28.57%  |
| 24      | 4         | 14.29%  |
| 17      | 3         | 10.71%  |
| 15      | 3         | 10.71%  |
| 12      | 2         | 7.14%   |
| 11      | 2         | 7.14%   |
| 34      | 1         | 3.57%   |
| 27      | 1         | 3.57%   |
| 23      | 1         | 3.57%   |
| 21      | 1         | 3.57%   |
| 14      | 1         | 3.57%   |
| Unknown | 1         | 3.57%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 13        | 46.43%  |
| 501-600     | 6         | 21.43%  |
| 201-300     | 6         | 21.43%  |
| 701-800     | 1         | 3.57%   |
| 401-500     | 1         | 3.57%   |
| Unknown     | 1         | 3.57%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 20        | 74.07%  |
| 5/4   | 3         | 11.11%  |
| 16/10 | 3         | 11.11%  |
| 21/9  | 1         | 3.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 9         | 32.14%  |
| 201-250        | 5         | 17.86%  |
| 141-150        | 3         | 10.71%  |
| 61-70          | 2         | 7.14%   |
| 51-60          | 2         | 7.14%   |
| 101-110        | 2         | 7.14%   |
| 351-500        | 1         | 3.57%   |
| 301-350        | 1         | 3.57%   |
| 251-300        | 1         | 3.57%   |
| 91-100         | 1         | 3.57%   |
| Unknown        | 1         | 3.57%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 14        | 50%     |
| 51-100  | 10        | 35.71%  |
| 101-120 | 2         | 7.14%   |
| 161-240 | 1         | 3.57%   |
| Unknown | 1         | 3.57%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 45        | 75%     |
| 0     | 13        | 21.67%  |
| 2     | 2         | 3.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 37        | 49.33%  |
| Realtek Semiconductor             | 17        | 22.67%  |
| Qualcomm Atheros                  | 7         | 9.33%   |
| Broadcom                          | 5         | 6.67%   |
| Marvell Technology Group          | 2         | 2.67%   |
| Ericsson Business Mobile Networks | 2         | 2.67%   |
| Sierra Wireless                   | 1         | 1.33%   |
| Ralink Technology                 | 1         | 1.33%   |
| Huawei Technologies               | 1         | 1.33%   |
| Edimax Technology                 | 1         | 1.33%   |
| ASUSTek Computer                  | 1         | 1.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 8         | 7.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 8         | 7.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 8         | 7.77%   |
| Intel Wireless 8260                                                     | 4         | 3.88%   |
| Intel Ethernet Connection I219-LM                                       | 4         | 3.88%   |
| Intel 82577LM Gigabit Network Connection                                | 4         | 3.88%   |
| Realtek RTL8125 2.5GbE Controller                                       | 3         | 2.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 2.91%   |
| Intel Wireless 7265                                                     | 3         | 2.91%   |
| Intel I210 Gigabit Network Connection                                   | 3         | 2.91%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 2         | 1.94%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 2         | 1.94%   |
| Intel Wireless 7260                                                     | 2         | 1.94%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 1.94%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 1.94%   |
| Intel Ethernet Connection (3) I218-LM                                   | 2         | 1.94%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 1.94%   |
| Sierra Wireless EM7455                                                  | 1         | 0.97%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.97%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 1         | 0.97%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.97%   |
| Ralink RT2501/RT2573 Wireless Adapter                                   | 1         | 0.97%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                              | 1         | 0.97%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.97%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 0.97%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                           | 1         | 0.97%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 1         | 0.97%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 1         | 0.97%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.97%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                 | 1         | 0.97%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                 | 1         | 0.97%   |
| Intel Wireless 8265 / 8275                                              | 1         | 0.97%   |
| Intel Wireless 3160                                                     | 1         | 0.97%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 0.97%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 0.97%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection               | 1         | 0.97%   |
| Intel Ethernet Connection I218-LM                                       | 1         | 0.97%   |
| Intel Ethernet Connection (4) I219-LM                                   | 1         | 0.97%   |
| Intel Ethernet Connection (2) I219-V                                    | 1         | 0.97%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 30        | 68.18%  |
| Qualcomm Atheros      | 5         | 11.36%  |
| Realtek Semiconductor | 3         | 6.82%   |
| Broadcom              | 2         | 4.55%   |
| Sierra Wireless       | 1         | 2.27%   |
| Ralink Technology     | 1         | 2.27%   |
| Edimax Technology     | 1         | 2.27%   |
| ASUSTek Computer      | 1         | 2.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 8         | 17.78%  |
| Intel Wireless 8260                                                     | 4         | 8.89%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 6.67%   |
| Intel Wireless 7265                                                     | 3         | 6.67%   |
| Intel Wireless 7260                                                     | 2         | 4.44%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 4.44%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 4.44%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 4.44%   |
| Sierra Wireless EM7455                                                  | 1         | 2.22%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 2.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 2.22%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 1         | 2.22%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 2.22%   |
| Ralink RT2501/RT2573 Wireless Adapter                                   | 1         | 2.22%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 2.22%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 2.22%   |
| Intel Wireless 8265 / 8275                                              | 1         | 2.22%   |
| Intel Wireless 3160                                                     | 1         | 2.22%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 2.22%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 2.22%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection               | 1         | 2.22%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 2.22%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1         | 2.22%   |
| Edimax AC600 Wireless LAN USB Adapter                                   | 1         | 2.22%   |
| Broadcom BRCM4378 Wireless Network Adapter                              | 1         | 2.22%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 1         | 2.22%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                                     | 1         | 2.22%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 28        | 52.83%  |
| Realtek Semiconductor    | 15        | 28.3%   |
| Qualcomm Atheros         | 5         | 9.43%   |
| Broadcom                 | 3         | 5.66%   |
| Marvell Technology Group | 2         | 3.77%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8         | 15.09%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 15.09%  |
| Intel Ethernet Connection I219-LM                                 | 4         | 7.55%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 7.55%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 5.66%   |
| Intel I210 Gigabit Network Connection                             | 3         | 5.66%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 3.77%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 3.77%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 3.77%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 1.89%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.89%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 1.89%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.89%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 1.89%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 1.89%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 1.89%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.89%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.89%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.89%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.89%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.89%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller     | 1         | 1.89%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 1         | 1.89%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 1         | 1.89%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 1         | 1.89%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 1         | 1.89%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 53        | 53.54%  |
| WiFi     | 41        | 41.41%  |
| Unknown  | 3         | 3.03%   |
| Modem    | 2         | 2.02%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 30        | 54.55%  |
| Ethernet | 25        | 45.45%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 37        | 61.67%  |
| 1     | 17        | 28.33%  |
| 3     | 3         | 5%      |
| 0     | 2         | 3.33%   |
| 4     | 1         | 1.67%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 60        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 15        | 50%     |
| Broadcom                | 5         | 16.67%  |
| Alps Electric           | 3         | 10%     |
| Realtek Semiconductor   | 2         | 6.67%   |
| Foxconn / Hon Hai       | 2         | 6.67%   |
| Cambridge Silicon Radio | 1         | 3.33%   |
| ASUSTek Computer        | 1         | 3.33%   |
| Apple                   | 1         | 3.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                       | 11        | 36.67%  |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]               | 3         | 10%     |
| Realtek Bluetooth Adapter                                | 2         | 6.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 2         | 6.67%   |
| Intel AX200 Bluetooth                                    | 2         | 6.67%   |
| Broadcom BCM2045B (BDC-2.1)                              | 2         | 6.67%   |
| Alps Electric UGTZ4 Bluetooth                            | 2         | 6.67%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device          | 1         | 3.33%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device | 1         | 3.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 1         | 3.33%   |
| ASUS Broadcom Bluetooth 2.1                              | 1         | 3.33%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                     | 1         | 3.33%   |
| Alps Electric BCM2046 Bluetooth Device                   | 1         | 3.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 43        | 71.67%  |
| AMD      | 10        | 16.67%  |
| Nvidia   | 5         | 8.33%   |
| Logitech | 1         | 1.67%   |
| JMTek    | 1         | 1.67%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 6         | 8.7%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6         | 8.7%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 7.25%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 5.8%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 5.8%    |
| AMD Family 17h/19h HD Audio Controller                                     | 4         | 5.8%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 2.9%    |
| Nvidia GA104 High Definition Audio Controller                              | 2         | 2.9%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 2.9%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 2.9%    |
| Intel Broadwell-U Audio Controller                                         | 2         | 2.9%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 2.9%    |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller | 2         | 2.9%    |
| AMD Starship/Matisse HD Audio Controller                                   | 2         | 2.9%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 2.9%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 2.9%    |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 2         | 2.9%    |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 1.45%   |
| Logitech [G533 Wireless Headset Dongle]                                    | 1         | 1.45%   |
| JMTek USB PnP Audio Device                                                 | 1         | 1.45%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 1         | 1.45%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 1.45%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 1.45%   |
| Intel Comet Lake PCH-V cAVS                                                | 1         | 1.45%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.45%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.45%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1         | 1.45%   |
| Intel 82801CA/CAM AC'97 Audio Controller                                   | 1         | 1.45%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 1.45%   |
| Intel 631xESB/632xESB High Definition Audio Controller                     | 1         | 1.45%   |
| Intel 200 Series PCH HD Audio                                              | 1         | 1.45%   |
| AMD RV770 HDMI Audio [Radeon HD 4850/4870]                                 | 1         | 1.45%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 1         | 1.45%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.45%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 10        | 33.33%  |
| Unknown             | 6         | 20%     |
| SK hynix            | 5         | 16.67%  |
| Kingston            | 3         | 10%     |
| Unknown             | 3         | 10%     |
| Micron Technology   | 1         | 3.33%   |
| Hewlett-Packard     | 1         | 3.33%   |
| Crucial             | 1         | 3.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s   | 3         | 8.82%   |
| Unknown                                                 | 3         | 8.82%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM 1067MT/s        | 2         | 5.88%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s   | 2         | 5.88%   |
| Unknown RAM Module 512MB SODIMM SDRAM                   | 1         | 2.94%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s             | 1         | 2.94%   |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s             | 1         | 2.94%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s              | 1         | 2.94%   |
| Unknown RAM Module 1GB SODIMM DDR2                      | 1         | 2.94%   |
| Unknown RAM Module 1GB SODIMM DDR                       | 1         | 2.94%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 1         | 2.94%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 1         | 2.94%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s  | 1         | 2.94%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s | 1         | 2.94%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB SODIMM LPDDR3 1867MT/s  | 1         | 2.94%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB Chip LPDDR3 1867MT/s    | 1         | 2.94%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s   | 1         | 2.94%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM 1067MT/s        | 1         | 2.94%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s   | 1         | 2.94%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s   | 1         | 2.94%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s   | 1         | 2.94%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s   | 1         | 2.94%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s   | 1         | 2.94%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s       | 1         | 2.94%   |
| Kingston RAM KF3600C18D4/32GX 32GB DIMM DDR4 2400MT/s   | 1         | 2.94%   |
| Kingston RAM 9905316-005.A04LF 1GB DIMM DDR2 667MT/s    | 1         | 2.94%   |
| HP RAM 809083-091 32GB DIMM DDR4 2400MT/s               | 1         | 2.94%   |
| Crucial RAM CT8G3S1339M 8GB SODIMM DDR3 800MT/s         | 1         | 2.94%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR3   | 14        | 48.28%  |
| DDR4   | 6         | 20.69%  |
| DDR2   | 4         | 13.79%  |
| SDRAM  | 3         | 10.34%  |
| LPDDR3 | 1         | 3.45%   |
| DDR    | 1         | 3.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 24        | 80%     |
| DIMM   | 5         | 16.67%  |
| Chip   | 1         | 3.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 9         | 29.03%  |
| 2048  | 9         | 29.03%  |
| 8192  | 6         | 19.35%  |
| 1024  | 3         | 9.68%   |
| 32768 | 2         | 6.45%   |
| 16384 | 1         | 3.23%   |
| 512   | 1         | 3.23%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 6         | 19.35%  |
| 1334    | 4         | 12.9%   |
| Unknown | 4         | 12.9%   |
| 2400    | 3         | 9.68%   |
| 1067    | 3         | 9.68%   |
| 1333    | 2         | 6.45%   |
| 800     | 2         | 6.45%   |
| 667     | 2         | 6.45%   |
| 3200    | 1         | 3.23%   |
| 2667    | 1         | 3.23%   |
| 2133    | 1         | 3.23%   |
| 1867    | 1         | 3.23%   |
| 400     | 1         | 3.23%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Chicony Electronics | 12        | 41.38%  |
| Lite-On Technology  | 5         | 17.24%  |
| Bison Electronics   | 5         | 17.24%  |
| Lenovo              | 2         | 6.9%    |
| Tripath Technology  | 1         | 3.45%   |
| SunplusIT           | 1         | 3.45%   |
| IMC Networks        | 1         | 3.45%   |
| Genesys Logic       | 1         | 3.45%   |
| Apple               | 1         | 3.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lite-On Integrated Camera                  | 4         | 13.79%  |
| Chicony Integrated Camera                  | 3         | 10.34%  |
| Bison Integrated Camera                    | 3         | 10.34%  |
| Chicony Integrated Camera [ThinkPad]       | 2         | 6.9%    |
| Tripath PC Camera                          | 1         | 3.45%   |
| SunplusIT USB camera                       | 1         | 3.45%   |
| Lite-On Realtek DMFT RGB                   | 1         | 3.45%   |
| Lenovo Integrated Webcam [R5U877]          | 1         | 3.45%   |
| Lenovo Integrated Webcam                   | 1         | 3.45%   |
| IMC Networks Integrated Camera             | 1         | 3.45%   |
| Genesys Logic ASUS USB 2.0 UVC 1.3M WebCam | 1         | 3.45%   |
| Chicony thinkpad t430s camera              | 1         | 3.45%   |
| Chicony Sonix ST50220 USB Video Camera     | 1         | 3.45%   |
| Chicony Lenovo Integrated Camera (0.3MP)   | 1         | 3.45%   |
| Chicony Lenovo EasyCamera                  | 1         | 3.45%   |
| Chicony Integrated Camera (1280x720@30)    | 1         | 3.45%   |
| Chicony FJ Camera                          | 1         | 3.45%   |
| Chicony 2.0M UVC Webcam / CNF7129          | 1         | 3.45%   |
| Bison USB HD Webcam                        | 1         | 3.45%   |
| Bison Lenovo Integrated Webcam             | 1         | 3.45%   |
| Apple FaceTime Camera                      | 1         | 3.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Validity Sensors   | 4         | 36.36%  |
| Upek               | 2         | 18.18%  |
| Synaptics          | 2         | 18.18%  |
| AuthenTec          | 2         | 18.18%  |
| STMicroelectronics | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 3         | 27.27%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 18.18%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 9.09%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 9.09%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 9.09%   |
| STMicroelectronics Fingerprint Reader                  | 1         | 9.09%   |
| AuthenTec AES2810                                      | 1         | 9.09%   |
| AuthenTec AES2660                                      | 1         | 9.09%   |

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


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 31        | 51.67%  |
| 0     | 16        | 26.67%  |
| 2     | 7         | 11.67%  |
| 5     | 3         | 5%      |
| 3     | 3         | 5%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 32        | 47.76%  |
| Graphics card            | 12        | 17.91%  |
| Firewire controller      | 7         | 10.45%  |
| Network                  | 4         | 5.97%   |
| Net/wireless             | 4         | 5.97%   |
| Storage/ata              | 3         | 4.48%   |
| Sound                    | 3         | 4.48%   |
| Modem                    | 1         | 1.49%   |
| Card reader              | 1         | 1.49%   |

