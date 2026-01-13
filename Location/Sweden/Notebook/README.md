BSD in Sweden - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for BSD in Sweden.

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

Total: 65

| Vendor    | Model                       | Probe                                                     | Date         |
|-----------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo    | ThinkPad W510 431924G       | [688ad4ad19](https://bsd-hardware.info/?probe=688ad4ad19) | Oct 23, 2025 |
| Lenovo    | ThinkPad T440s 20AQ007SM... | [52687cfcbb](https://bsd-hardware.info/?probe=52687cfcbb) | Sep 06, 2025 |
| Lenovo    | ThinkPad X260 20F5S6BN00    | [84c5ccc6dd](https://bsd-hardware.info/?probe=84c5ccc6dd) | Jun 29, 2025 |
| Lenovo    | ThinkPad T470s 20HGS0W10... | [c343ca991e](https://bsd-hardware.info/?probe=c343ca991e) | May 30, 2025 |
| Unknown   | Unknown                     | [a217858f6e](https://bsd-hardware.info/?probe=a217858f6e) | May 23, 2025 |
| Apple     | MacBookPro7,1               | [8f97a3434e](https://bsd-hardware.info/?probe=8f97a3434e) | Mar 11, 2025 |
| Apple     | MacBookPro7,1               | [cb36bb789a](https://bsd-hardware.info/?probe=cb36bb789a) | Mar 11, 2025 |
| Fujitsu   | CELSIUS H7510               | [8dbaa0bbaa](https://bsd-hardware.info/?probe=8dbaa0bbaa) | Mar 02, 2025 |
| Lenovo    | IdeaPad 3 14ALC6 82KT       | [fdf531586e](https://bsd-hardware.info/?probe=fdf531586e) | Feb 17, 2025 |
| Fujitsu   | LIFEBOOK E549               | [2afbf7fe2f](https://bsd-hardware.info/?probe=2afbf7fe2f) | Jan 23, 2025 |
| Dell      | Latitude 5480               | [e52c59a599](https://bsd-hardware.info/?probe=e52c59a599) | Jan 21, 2025 |
| Lenovo    | ThinkPad X201 3626HMG       | [9fe06419eb](https://bsd-hardware.info/?probe=9fe06419eb) | Dec 21, 2024 |
| Lenovo    | ThinkPad X201 3626HMG       | [86efb87e9e](https://bsd-hardware.info/?probe=86efb87e9e) | Dec 21, 2024 |
| HP        | Pavilion g6                 | [25f47fd8d4](https://bsd-hardware.info/?probe=25f47fd8d4) | Nov 24, 2024 |
| Framework | Laptop 13 (AMD Ryzen 704... | [854819dc14](https://bsd-hardware.info/?probe=854819dc14) | Sep 10, 2024 |
| Lenovo    | IdeaPad 5 14ALC05 82LM      | [b8dc419264](https://bsd-hardware.info/?probe=b8dc419264) | Jun 08, 2024 |
| Apple     | MacBookPro11,1              | [9ee71f878e](https://bsd-hardware.info/?probe=9ee71f878e) | May 23, 2024 |
| Apple     | MacBookPro11,1              | [1a6b006807](https://bsd-hardware.info/?probe=1a6b006807) | May 23, 2024 |
| Lenovo    | ThinkPad T530 23942U1       | [a3b075c680](https://bsd-hardware.info/?probe=a3b075c680) | Apr 21, 2024 |
| Dell      | Latitude E7250              | [ffc8dcf395](https://bsd-hardware.info/?probe=ffc8dcf395) | Feb 22, 2024 |
| Lenovo    | ThinkPad T480 20L6SDA400    | [4934e88205](https://bsd-hardware.info/?probe=4934e88205) | Feb 07, 2024 |
| Razer     | Blade 14 (2022) - RZ09-0... | [a2d3483ef9](https://bsd-hardware.info/?probe=a2d3483ef9) | Jan 30, 2024 |
| Star Labs | StarBook                    | [1e903acb93](https://bsd-hardware.info/?probe=1e903acb93) | Jan 16, 2024 |
| Apple     | MacBookPro6,2               | [85e94bd511](https://bsd-hardware.info/?probe=85e94bd511) | Oct 06, 2023 |
| Dell      | XPS 13 7390                 | [6bb6186f22](https://bsd-hardware.info/?probe=6bb6186f22) | Sep 19, 2023 |
| Lenovo    | ThinkPad T470s W10DG 20J... | [692df89c1f](https://bsd-hardware.info/?probe=692df89c1f) | Apr 26, 2023 |
| Lenovo    | IdeaPad 3 14IML05 81WA      | [d04d402809](https://bsd-hardware.info/?probe=d04d402809) | Feb 21, 2023 |
| Apple     | MacBookAir6,1               | [96fa5325d1](https://bsd-hardware.info/?probe=96fa5325d1) | Feb 11, 2023 |
| HP        | Pavilion Laptop 14-bf0xx    | [a98d28355d](https://bsd-hardware.info/?probe=a98d28355d) | Feb 05, 2023 |
| Star Labs | StarBook                    | [d222f381b0](https://bsd-hardware.info/?probe=d222f381b0) | Jan 23, 2023 |
| Star Labs | StarBook                    | [045d4bb6e8](https://bsd-hardware.info/?probe=045d4bb6e8) | Jan 23, 2023 |
| Deciso    | NetBoard-A10                | [21c60a4db8](https://bsd-hardware.info/?probe=21c60a4db8) | Jan 04, 2023 |
| Lenovo    | IdeaPad L340-17IWL 81M0     | [22c4a06468](https://bsd-hardware.info/?probe=22c4a06468) | Dec 31, 2022 |
| Toshiba   | TECRA Z40-C-12Z             | [149e5c3de3](https://bsd-hardware.info/?probe=149e5c3de3) | Nov 28, 2022 |
| HP        | Unknown                     | [7bd69ee984](https://bsd-hardware.info/?probe=7bd69ee984) | Aug 29, 2022 |
| HP        | ProBook 4730s               | [e70725dd32](https://bsd-hardware.info/?probe=e70725dd32) | Jul 23, 2022 |
| ASUSTek   | UX305UA                     | [3fb1786193](https://bsd-hardware.info/?probe=3fb1786193) | Apr 04, 2022 |
| Lenovo    | ThinkPad T460s 20FAS4KH0... | [dbb0e378d5](https://bsd-hardware.info/?probe=dbb0e378d5) | Mar 17, 2022 |
| Lenovo    | V130-15IGM 81HL             | [e0e7b21668](https://bsd-hardware.info/?probe=e0e7b21668) | Jan 09, 2022 |
| Lenovo    | ThinkPad T420 4236MBG       | [0391bf9ea4](https://bsd-hardware.info/?probe=0391bf9ea4) | Nov 14, 2021 |
| ASUSTek   | K52Jc                       | [92b975763f](https://bsd-hardware.info/?probe=92b975763f) | Nov 08, 2021 |
| ASUSTek   | K52Jc                       | [fc919c73e3](https://bsd-hardware.info/?probe=fc919c73e3) | Nov 07, 2021 |
| Google    | Grunt                       | [aa07a1dd40](https://bsd-hardware.info/?probe=aa07a1dd40) | Nov 05, 2021 |
| Google    | Grunt                       | [c87e033731](https://bsd-hardware.info/?probe=c87e033731) | Nov 01, 2021 |
| Google    | Grunt                       | [e6d4421a4d](https://bsd-hardware.info/?probe=e6d4421a4d) | Oct 16, 2021 |
| Google    | Grunt                       | [ee9b2d7ad3](https://bsd-hardware.info/?probe=ee9b2d7ad3) | Oct 15, 2021 |
| Google    | Grunt                       | [e76c73d9a3](https://bsd-hardware.info/?probe=e76c73d9a3) | Oct 11, 2021 |
| Acer      | Aspire A315-56              | [03ca802f4b](https://bsd-hardware.info/?probe=03ca802f4b) | Oct 02, 2021 |
| Dell      | Latitude E5530 non-vPro     | [bd4b0f0700](https://bsd-hardware.info/?probe=bd4b0f0700) | Aug 17, 2021 |
| Lenovo    | ThinkPad X250 20CLS4JH00    | [89a74889ae](https://bsd-hardware.info/?probe=89a74889ae) | Aug 02, 2021 |
| Lenovo    | ThinkPad T400 2767WSB       | [36ce1d1e00](https://bsd-hardware.info/?probe=36ce1d1e00) | Jul 24, 2021 |
| Lenovo    | ThinkPad T420 4236MBG       | [5b43300a93](https://bsd-hardware.info/?probe=5b43300a93) | Jul 13, 2021 |
| Sony      | SVP1322M1EBI                | [23316d0f2b](https://bsd-hardware.info/?probe=23316d0f2b) | May 29, 2021 |
| Dell      | Latitude 5500               | [2538b038ed](https://bsd-hardware.info/?probe=2538b038ed) | May 08, 2021 |
| Lenovo    | ThinkPad X395 20NL001SMX    | [cd016e96ee](https://bsd-hardware.info/?probe=cd016e96ee) | Mar 17, 2021 |
| Dell      | Latitude E7240              | [e42e579971](https://bsd-hardware.info/?probe=e42e579971) | Feb 22, 2021 |
| HP        | EliteBook 8440p             | [7968c7d2dd](https://bsd-hardware.info/?probe=7968c7d2dd) | Feb 16, 2021 |
| Lenovo    | Legion Y530-15ICH 81FV      | [f8bdec0105](https://bsd-hardware.info/?probe=f8bdec0105) | Feb 14, 2021 |
| ASUSTek   | S551LN                      | [42792115e3](https://bsd-hardware.info/?probe=42792115e3) | Feb 11, 2021 |
| Toshiba   | Satellite L450              | [eb44256bfe](https://bsd-hardware.info/?probe=eb44256bfe) | Feb 11, 2021 |
| Lenovo    | ThinkPad X201 3680FAG       | [1ba69078df](https://bsd-hardware.info/?probe=1ba69078df) | Dec 06, 2020 |
| HP        | Laptop 15-dw0xxx            | [547b36ea62](https://bsd-hardware.info/?probe=547b36ea62) | Aug 19, 2020 |
| Lenovo    | ThinkPad W520 4284GN2       | [acb3ad955f](https://bsd-hardware.info/?probe=acb3ad955f) | Aug 06, 2020 |
| Lenovo    | ThinkPad L560 20F10032MS    | [bf2b792b64](https://bsd-hardware.info/?probe=bf2b792b64) | Aug 06, 2020 |
| Lenovo    | ThinkPad L560 20F10032MS    | [0aa6a9a921](https://bsd-hardware.info/?probe=0aa6a9a921) | Aug 06, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| FreeBSD 14.2         | 5         | 9.09%   |
| helloSystem 0.9.0    | 4         | 7.27%   |
| helloSystem 0.5.0    | 4         | 7.27%   |
| OpenBSD 7.0          | 3         | 5.45%   |
| helloSystem 0.8.0    | 3         | 5.45%   |
| OpenBSD 6.9          | 2         | 3.64%   |
| helloSystem 0.7.0    | 2         | 3.64%   |
| helloSystem 0.4.0    | 2         | 3.64%   |
| FreeBSD 15.0-CURRENT | 2         | 3.64%   |
| FreeBSD 14.0         | 2         | 3.64%   |
| FreeBSD 13.1-p5      | 2         | 3.64%   |
| FreeBSD 12.1-p8      | 2         | 3.64%   |
| OPNsense 25.1.7      | 1         | 1.82%   |
| OPNsense 24.7.9      | 1         | 1.82%   |
| OPNsense 22.10       | 1         | 1.82%   |
| OPNsense 21.1        | 1         | 1.82%   |
| OpenBSD 7.2          | 1         | 1.82%   |
| OpenBSD 6.8          | 1         | 1.82%   |
| OpenBSD 6.7          | 1         | 1.82%   |
| NomadBSD 20221130    | 1         | 1.82%   |
| helloSystem 0.8.1    | 1         | 1.82%   |
| GhostBSD 22.08.27    | 1         | 1.82%   |
| GhostBSD 21.08.27    | 1         | 1.82%   |
| GhostBSD 20.04.02    | 1         | 1.82%   |
| FreeBSD 14.3         | 1         | 1.82%   |
| FreeBSD 14.1         | 1         | 1.82%   |
| FreeBSD 14.0-p6      | 1         | 1.82%   |
| FreeBSD 14.0-p2      | 1         | 1.82%   |
| FreeBSD 14.0-CURRENT | 1         | 1.82%   |
| FreeBSD 13.2-p4      | 1         | 1.82%   |
| FreeBSD 13.1-p7      | 1         | 1.82%   |
| FreeBSD 13.0-p7      | 1         | 1.82%   |
| FreeBSD 13.0-p10     | 1         | 1.82%   |
| FreeBSD 13.0         | 1         | 1.82%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 23        | 42.59%  |
| helloSystem | 16        | 29.63%  |
| OpenBSD     | 7         | 12.96%  |
| OPNsense    | 4         | 7.41%   |
| GhostBSD    | 3         | 5.56%   |
| NomadBSD    | 1         | 1.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 54        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 17        | 30.91%  |
| Console      | 7         | 12.73%  |
| fvwm         | 6         | 10.91%  |
| KDE5         | 5         | 9.09%   |
| TWM          | 4         | 7.27%   |
| MATE         | 3         | 5.45%   |
| i3           | 3         | 5.45%   |
| GNOME        | 3         | 5.45%   |
| XFCE         | 2         | 3.64%   |
| LXQt         | 2         | 3.64%   |
| Openbox      | 1         | 1.82%   |
| Mutter       | 1         | 1.82%   |
| KDE6         | 1         | 1.82%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 46        | 85.19%  |
| Console | 8         | 14.81%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 18        | 33.33%  |
| SLiM    | 17        | 31.48%  |
| SDDM    | 8         | 14.81%  |
| LightDM | 6         | 11.11%  |
| GDM     | 3         | 5.56%   |
| XDM     | 2         | 3.7%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| C       | 18        | 33.33%  |
| Unknown | 16        | 29.63%  |
| en_US   | 14        | 25.93%  |
| sv_SE   | 2         | 3.7%    |
| sv      | 1         | 1.85%   |
| en_GB   | 1         | 1.85%   |
| en_BE   | 1         | 1.85%   |
| en      | 1         | 1.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 48        | 87.27%  |
| BIOS | 7         | 12.73%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 34        | 62.96%  |
| Ufs    | 8         | 14.81%  |
| Ffs    | 7         | 12.96%  |
| Cd9660 | 5         | 9.26%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 51        | 91.07%  |
| MBR  | 5         | 8.93%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 22        | 40.74%  |
| Hewlett-Packard  | 6         | 11.11%  |
| Dell             | 6         | 11.11%  |
| Apple            | 4         | 7.41%   |
| ASUSTek Computer | 3         | 5.56%   |
| Toshiba          | 2         | 3.7%    |
| Star Labs        | 2         | 3.7%    |
| Fujitsu          | 2         | 3.7%    |
| Sony             | 1         | 1.85%   |
| Razer            | 1         | 1.85%   |
| Google           | 1         | 1.85%   |
| Framework        | 1         | 1.85%   |
| Deciso           | 1         | 1.85%   |
| Acer             | 1         | 1.85%   |
| Unknown          | 1         | 1.85%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Star Labs StarBook                         | 2         | 3.7%    |
| Unknown                                    | 2         | 3.7%    |
| Toshiba TECRA Z40-C-12Z                    | 1         | 1.85%   |
| Toshiba Satellite L450                     | 1         | 1.85%   |
| Sony SVP1322M1EBI                          | 1         | 1.85%   |
| Razer Blade 14 (2022) - RZ09-0427          | 1         | 1.85%   |
| Lenovo V130-15IGM 81HL                     | 1         | 1.85%   |
| Lenovo ThinkPad X395 20NL001SMX            | 1         | 1.85%   |
| Lenovo ThinkPad X260 20F5S6BN00            | 1         | 1.85%   |
| Lenovo ThinkPad X250 20CLS4JH00            | 1         | 1.85%   |
| Lenovo ThinkPad X201 3680FAG               | 1         | 1.85%   |
| Lenovo ThinkPad X201 3626HMG               | 1         | 1.85%   |
| Lenovo ThinkPad W520 4284GN2               | 1         | 1.85%   |
| Lenovo ThinkPad W510 431924G               | 1         | 1.85%   |
| Lenovo ThinkPad T530 23942U1               | 1         | 1.85%   |
| Lenovo ThinkPad T480 20L6SDA400            | 1         | 1.85%   |
| Lenovo ThinkPad T470s W10DG 20JTS0W800     | 1         | 1.85%   |
| Lenovo ThinkPad T470s 20HGS0W10Q           | 1         | 1.85%   |
| Lenovo ThinkPad T460s 20FAS4KH02           | 1         | 1.85%   |
| Lenovo ThinkPad T440s 20AQ007SMS           | 1         | 1.85%   |
| Lenovo ThinkPad T420 4236MBG               | 1         | 1.85%   |
| Lenovo ThinkPad T400 2767WSB               | 1         | 1.85%   |
| Lenovo ThinkPad L560 20F10032MS            | 1         | 1.85%   |
| Lenovo Legion Y530-15ICH 81FV              | 1         | 1.85%   |
| Lenovo IdeaPad L340-17IWL 81M0             | 1         | 1.85%   |
| Lenovo IdeaPad 5 14ALC05 82LM              | 1         | 1.85%   |
| Lenovo IdeaPad 3 14IML05 81WA              | 1         | 1.85%   |
| Lenovo IdeaPad 3 14ALC6 82KT               | 1         | 1.85%   |
| HP ProBook 4730s                           | 1         | 1.85%   |
| HP Pavilion Laptop 14-bf0xx                | 1         | 1.85%   |
| HP Pavilion g6                             | 1         | 1.85%   |
| HP Laptop 15-dw0xxx                        | 1         | 1.85%   |
| HP EliteBook 8440p                         | 1         | 1.85%   |
| Google Grunt                               | 1         | 1.85%   |
| Fujitsu LIFEBOOK E549                      | 1         | 1.85%   |
| Fujitsu CELSIUS H7510                      | 1         | 1.85%   |
| Framework Laptop 13 (AMD Ryzen 7040Series) | 1         | 1.85%   |
| Dell XPS 13 7390                           | 1         | 1.85%   |
| Dell Latitude E7250                        | 1         | 1.85%   |
| Dell Latitude E7240                        | 1         | 1.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 16        | 29.63%  |
| Dell Latitude       | 5         | 9.26%   |
| Lenovo IdeaPad      | 4         | 7.41%   |
| Star Labs StarBook  | 2         | 3.7%    |
| HP Pavilion         | 2         | 3.7%    |
| Unknown             | 2         | 3.7%    |
| Toshiba TECRA       | 1         | 1.85%   |
| Toshiba Satellite   | 1         | 1.85%   |
| Sony SVP1322M1EBI   | 1         | 1.85%   |
| Razer Blade         | 1         | 1.85%   |
| Lenovo V130-15IGM   | 1         | 1.85%   |
| Lenovo Legion       | 1         | 1.85%   |
| HP ProBook          | 1         | 1.85%   |
| HP Laptop           | 1         | 1.85%   |
| HP EliteBook        | 1         | 1.85%   |
| Google Grunt        | 1         | 1.85%   |
| Fujitsu LIFEBOOK    | 1         | 1.85%   |
| Fujitsu CELSIUS     | 1         | 1.85%   |
| Framework Laptop    | 1         | 1.85%   |
| Dell XPS            | 1         | 1.85%   |
| Deciso NetBoard-A10 | 1         | 1.85%   |
| ASUS UX305UA        | 1         | 1.85%   |
| ASUS S551LN         | 1         | 1.85%   |
| ASUS K52Jc          | 1         | 1.85%   |
| Apple MacBookPro7   | 1         | 1.85%   |
| Apple MacBookPro6   | 1         | 1.85%   |
| Apple MacBookPro11  | 1         | 1.85%   |
| Apple MacBookAir6   | 1         | 1.85%   |
| Acer Aspire         | 1         | 1.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 6         | 11.11%  |
| 2020 | 6         | 11.11%  |
| 2017 | 5         | 9.26%   |
| 2022 | 4         | 7.41%   |
| 2014 | 4         | 7.41%   |
| 2010 | 4         | 7.41%   |
| 2024 | 3         | 5.56%   |
| 2023 | 3         | 5.56%   |
| 2019 | 3         | 5.56%   |
| 2018 | 3         | 5.56%   |
| 2016 | 3         | 5.56%   |
| 2011 | 3         | 5.56%   |
| 2009 | 3         | 5.56%   |
| 2015 | 2         | 3.7%    |
| 2012 | 2         | 3.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 54        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 50        | 92.59%  |
| Yes  | 4         | 7.41%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 21        | 38.89%  |
| 4.01-8.0    | 12        | 22.22%  |
| 16.01-24.0  | 12        | 22.22%  |
| 32.01-64.0  | 5         | 9.26%   |
| 24.01-32.0  | 2         | 3.7%    |
| 3.01-4.0    | 1         | 1.85%   |
| 64.01-256.0 | 1         | 1.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 28        | 51.85%  |
| 0.51-1.0 | 16        | 29.63%  |
| 1.01-2.0 | 7         | 12.96%  |
| 2.01-3.0 | 2         | 3.7%    |
| 4.01-8.0 | 1         | 1.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 37        | 68.52%  |
| 0      | 9         | 16.67%  |
| 2      | 7         | 12.96%  |
| 3      | 1         | 1.85%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 42        | 77.78%  |
| Yes       | 12        | 22.22%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 41        | 75.93%  |
| No        | 13        | 24.07%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 50        | 92.59%  |
| No        | 4         | 7.41%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 70.91%  |
| No        | 16        | 29.09%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Sweden  | 54        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Stockholm      | 9         | 16.07%  |
| Malmo          | 5         | 8.93%   |
| Henan          | 3         | 5.36%   |
| Gothenburg     | 3         | 5.36%   |
| VÃ¤sterÃ¥s | 2         | 3.57%   |
| Sollentuna     | 2         | 3.57%   |
| Skellefteå    | 2         | 3.57%   |
| Visby          | 1         | 1.79%   |
| Varekil        | 1         | 1.79%   |
| Vallingby      | 1         | 1.79%   |
| Trosa          | 1         | 1.79%   |
| Staffanstorp   | 1         | 1.79%   |
| Solna          | 1         | 1.79%   |
| Sollebrunn     | 1         | 1.79%   |
| Södertälje   | 1         | 1.79%   |
| SkellefteÃ¥  | 1         | 1.79%   |
| OEvertornea    | 1         | 1.79%   |
| OEverlida      | 1         | 1.79%   |
| Lund           | 1         | 1.79%   |
| LuleÃ¥       | 1         | 1.79%   |
| Lidkoeping     | 1         | 1.79%   |
| Kungsbacka     | 1         | 1.79%   |
| Klagshamn      | 1         | 1.79%   |
| Kalmar         | 1         | 1.79%   |
| Jaerbo         | 1         | 1.79%   |
| Hultsfred      | 1         | 1.79%   |
| Hoeviksnaes    | 1         | 1.79%   |
| Hoerby         | 1         | 1.79%   |
| GГ¤vle       | 1         | 1.79%   |
| Falkenberg     | 1         | 1.79%   |
| Faergelanda    | 1         | 1.79%   |
| Eskilstuna     | 1         | 1.79%   |
| Enebyberg      | 1         | 1.79%   |
| Bromma         | 1         | 1.79%   |
| Borensberg     | 1         | 1.79%   |
| Bastad         | 1         | 1.79%   |
| Astorp         | 1         | 1.79%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 13     | 22.45%  |
| Seagate             | 6         | 6      | 12.24%  |
| WDC                 | 5         | 5      | 10.2%   |
| Kingston            | 5         | 5      | 10.2%   |
| Toshiba             | 3         | 3      | 6.12%   |
| SanDisk             | 3         | 3      | 6.12%   |
| Micron Technology   | 2         | 2      | 4.08%   |
| Intel               | 2         | 2      | 4.08%   |
| Hitachi             | 2         | 2      | 4.08%   |
| Apple               | 2         | 2      | 4.08%   |
| Transcend           | 1         | 1      | 2.04%   |
| Star Drive          | 1         | 1      | 2.04%   |
| SK hynix            | 1         | 1      | 2.04%   |
| NVMe                | 1         | 1      | 2.04%   |
| HGST                | 1         | 1      | 2.04%   |
| Dogfish             | 1         | 1      | 2.04%   |
| Crucial             | 1         | 1      | 2.04%   |
| A-DATA Technology   | 1         | 1      | 2.04%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 250GB                 | 2         | 4%      |
| Kingston SV300S37A120G 120GB              | 2         | 4%      |
| Kingston SA400S37120G 120GB               | 2         | 4%      |
| WDC WD6400BPVT-60HXZT1 640GB              | 1         | 2%      |
| WDC WD3200BEKT-08PVMT1 320GB              | 1         | 2%      |
| WDC WD10S12X-55JTET0 1TB                  | 1         | 2%      |
| WDC PC SN730 SDBQNTY-256G-1001 256GB      | 1         | 2%      |
| WDC PC SN520 NVMe 256GB                   | 1         | 2%      |
| Transcend TS256GMTE652T2 256GB            | 1         | 2%      |
| Toshiba MK1676GSX 160GB                   | 1         | 2%      |
| Toshiba KSG60ZMV256G M.2 2280 256GB       | 1         | 2%      |
| Toshiba KSG60ZMV256G 256GB                | 1         | 2%      |
| Star Drive PCIe SSD 960GB                 | 1         | 2%      |
| SK hynix HFS128G32TNF-N3A0A 128GB         | 1         | 2%      |
| Seagate ST9640320AS 640GB                 | 1         | 2%      |
| Seagate ST9500420AS 500GB                 | 1         | 2%      |
| Seagate ST9320423AS 320GB                 | 1         | 2%      |
| Seagate ST750LM022 HN-M750MBB 752GB       | 1         | 2%      |
| Seagate ST1000LM049-2GH172 1TB            | 1         | 2%      |
| Seagate FireCuda SE SSD ZA1000GM10011 1TB | 1         | 2%      |
| SanDisk SDSSDHP256G 256GB                 | 1         | 2%      |
| SanDisk SD8TN8U256G1001 256GB             | 1         | 2%      |
| SanDisk SD8SN8U-256G-1006 256GB           | 1         | 2%      |
| Samsung SSD PM851 mSATA 256GB             | 1         | 2%      |
| Samsung SSD PM830 2.5-inch 7mm 128GB      | 1         | 2%      |
| Samsung SSD 860 PRO 256GB                 | 1         | 2%      |
| Samsung PM981a NVMe 512GB                 | 1         | 2%      |
| Samsung PM981 NVMe 256GB                  | 1         | 2%      |
| Samsung MZVLW256HEHP-000L7 256GB          | 1         | 2%      |
| Samsung MZNTE128HMGR-000SO 128GB          | 1         | 2%      |
| Samsung MZNLN128HAHQ-000L2 128GB          | 1         | 2%      |
| Samsung MZ7TE256HMHP-000L7 256GB          | 1         | 2%      |
| Samsung Flash Drive FIT 32GB              | 1         | 2%      |
| NVMe INTEL SSDPEKNW51 512GB               | 1         | 2%      |
| Micron M600_MTFDDAV256MBF 256GB           | 1         | 2%      |
| Micron C400-MTFDDAK256MAM 256GB           | 1         | 2%      |
| Kingston SNV2S500G 500GB                  | 1         | 2%      |
| Intel SSDSA2M080G2GC 80GB                 | 1         | 2%      |
| Intel SSDPEKNW512G8 512GB                 | 1         | 2%      |
| Hitachi HTS725025A9A364 250GB             | 1         | 2%      |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 38.46%  |
| WDC                 | 3         | 3      | 23.08%  |
| Hitachi             | 2         | 2      | 15.38%  |
| Toshiba             | 1         | 1      | 7.69%   |
| Samsung Electronics | 1         | 2      | 7.69%   |
| HGST                | 1         | 1      | 7.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 8      | 26.92%  |
| Kingston            | 4         | 4      | 15.38%  |
| SanDisk             | 3         | 3      | 11.54%  |
| Toshiba             | 2         | 2      | 7.69%   |
| Micron Technology   | 2         | 2      | 7.69%   |
| Apple               | 2         | 2      | 7.69%   |
| SK hynix            | 1         | 1      | 3.85%   |
| Seagate             | 1         | 1      | 3.85%   |
| NVMe                | 1         | 1      | 3.85%   |
| Intel               | 1         | 1      | 3.85%   |
| Dogfish             | 1         | 1      | 3.85%   |
| Crucial             | 1         | 1      | 3.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 25        | 27     | 53.19%  |
| HDD  | 12        | 14     | 25.53%  |
| NVMe | 10        | 10     | 21.28%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 36        | 41     | 78.26%  |
| NVMe | 10        | 10     | 21.74%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 28        | 31     | 73.68%  |
| 0.51-1.0   | 8         | 8      | 21.05%  |
| 1.01-2.0   | 2         | 2      | 5.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 22        | 40%     |
| 251-500    | 9         | 16.36%  |
| 1-20       | 9         | 16.36%  |
| 501-1000   | 7         | 12.73%  |
| 51-100     | 5         | 9.09%   |
| 21-50      | 2         | 3.64%   |
| 1001-2000  | 1         | 1.82%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 47        | 87.04%  |
| 21-50   | 5         | 9.26%   |
| 51-100  | 2         | 3.7%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Toshiba KSG60ZMV256G M.2 2280 256GB          | 1         | 1      | 9.09%   |
| Seagate ST9640320AS 640GB                    | 1         | 1      | 9.09%   |
| Seagate ST9500420AS 500GB                    | 1         | 1      | 9.09%   |
| Seagate ST9320423AS 320GB                    | 1         | 1      | 9.09%   |
| Seagate ST750LM022 HN-M750MBB 752GB          | 1         | 1      | 9.09%   |
| Seagate ST1000LM049-2GH172 1TB               | 1         | 1      | 9.09%   |
| Samsung Electronics MZNTE128HMGR-000SO 128GB | 1         | 1      | 9.09%   |
| Samsung Electronics MZ7TE256HMHP-000L7 256GB | 1         | 1      | 9.09%   |
| Kingston SV300S37A120G 120GB                 | 1         | 1      | 9.09%   |
| Intel SSDSA2M080G2GC 80GB                    | 1         | 1      | 9.09%   |
| Hitachi HTS725025A9A364 250GB                | 1         | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 45.45%  |
| Samsung Electronics | 2         | 2      | 18.18%  |
| Toshiba             | 1         | 1      | 9.09%   |
| Kingston            | 1         | 1      | 9.09%   |
| Intel               | 1         | 1      | 9.09%   |
| Hitachi             | 1         | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 83.33%  |
| Hitachi | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 6      | 54.55%  |
| SSD  | 5         | 5      | 45.45%  |

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
| Works    | 35        | 39     | 74.47%  |
| Malfunc  | 11        | 11     | 23.4%   |
| Detected | 1         | 1      | 2.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 39        | 65%     |
| Samsung Electronics         | 8         | 13.33%  |
| SanDisk                     | 3         | 5%      |
| Phison Electronics          | 3         | 5%      |
| AMD                         | 2         | 3.33%   |
| Transcend                   | 1         | 1.67%   |
| Realtek Semiconductor       | 1         | 1.67%   |
| Nvidia                      | 1         | 1.67%   |
| Marvell Technology Group    | 1         | 1.67%   |
| Kingston Technology Company | 1         | 1.67%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 7         | 10.77%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 6         | 9.23%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                            | 3         | 4.62%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 3         | 4.62%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 3         | 4.62%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 3         | 4.62%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 3         | 4.62%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller               | 3         | 4.62%   |
| Phison E18 PCIe4 NVMe Controller                                             | 2         | 3.08%   |
| Intel SSD 660P Series                                                        | 2         | 3.08%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 2         | 3.08%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 2         | 3.08%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 2         | 3.08%   |
| Transcend NVMe PCIe SSD 110S/112S/120S/MTE300S/MTE400S/MTE652T2 (DRAM-less)  | 1         | 1.54%   |
| Sandisk WD Black SN850X NVMe SSD                                             | 1         | 1.54%   |
| SanDisk PC SN520 x2 M.2 2230 NVMe SSD                                        | 1         | 1.54%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD         | 1         | 1.54%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                           | 1         | 1.54%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                | 1         | 1.54%   |
| Realtek RTS5763DL x2 NVMe SSD Controller                                     | 1         | 1.54%   |
| Phison E12 NVMe Controller                                                   | 1         | 1.54%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                     | 1         | 1.54%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                   | 1         | 1.54%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                         | 1         | 1.54%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 1         | 1.54%   |
| Intel SSD 670p Series [Keystone Harbor]                                      | 1         | 1.54%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                | 1         | 1.54%   |
| Intel Comet Lake SATA AHCI Controller                                        | 1         | 1.54%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 1         | 1.54%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 1         | 1.54%   |
| Intel Alder Lake-N SATA AHCI Controller                                      | 1         | 1.54%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                | 1         | 1.54%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 1         | 1.54%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                   | 1         | 1.54%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                | 1         | 1.54%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                | 1         | 1.54%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                         | 1         | 1.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 39        | 60.94%  |
| NVMe | 19        | 29.69%  |
| RAID | 3         | 4.69%   |
| IDE  | 3         | 4.69%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 47        | 87.04%  |
| AMD    | 7         | 12.96%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5-8265U CPU @ 1.60GHz    | 3         | 5.56%   |
| Intel Core i5-6300U CPU @ 2.40GHz    | 3         | 5.56%   |
| Intel Core i5-6200U CPU @ 2.30GHz    | 2         | 3.7%    |
| Intel Core i5-4200U CPU @ 1.60GHz    | 2         | 3.7%    |
| Intel Core i5 CPU M 540 @ 2.53GHz    | 2         | 3.7%    |
| Intel 12th Gen Core i7-1260P         | 2         | 3.7%    |
| Intel Pentium CPU 6405U @ 2.40GHz    | 1         | 1.85%   |
| Intel N150                           | 1         | 1.85%   |
| Intel CPU Version                    | 1         | 1.85%   |
| Intel Core i7-8750H CPU @ 2.20GHz    | 1         | 1.85%   |
| Intel Core i7-8550U CPU @ 1.80GHz    | 1         | 1.85%   |
| Intel Core i7-7600U CPU @ 2.80GHz    | 1         | 1.85%   |
| Intel Core i7-6600U CPU @ 2.60GHz    | 1         | 1.85%   |
| Intel Core i7-4600U CPU @ 2.10GHz    | 1         | 1.85%   |
| Intel Core i7-4558U CPU @ 2.80GHz    | 1         | 1.85%   |
| Intel Core i7-2760QM CPU @ 2.40GHz   | 1         | 1.85%   |
| Intel Core i7-2630QM CPU @ 2.00GHz   | 1         | 1.85%   |
| Intel Core i7-10850H CPU @ 2.70GHz   | 1         | 1.85%   |
| Intel Core i7-10510U CPU @ 1.80GHz   | 1         | 1.85%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz    | 1         | 1.85%   |
| Intel Core i7 CPU M 620 @ 2.67GHz    | 1         | 1.85%   |
| Intel Core i5-8365U CPU @ 1.60GHz    | 1         | 1.85%   |
| Intel Core i5-7200U CPU @ 2.50GHz    | 1         | 1.85%   |
| Intel Core i5-5300U CPU @ 2.30GHz    | 1         | 1.85%   |
| Intel Core i5-5200U CPU @ 2.20GHz    | 1         | 1.85%   |
| Intel Core i5-4260U CPU @ 1.40GHz    | 1         | 1.85%   |
| Intel Core i5-4210U CPU @ 1.70GHz    | 1         | 1.85%   |
| Intel Core i5-3340M CPU @ 2.70GHz    | 1         | 1.85%   |
| Intel Core i5-3230M CPU @ 2.60GHz    | 1         | 1.85%   |
| Intel Core i5-2540M CPU @ 2.60GHz    | 1         | 1.85%   |
| Intel Core i5-2410M CPU @ 2.30GHz    | 1         | 1.85%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz   | 1         | 1.85%   |
| Intel Core i5 CPU M 520 @ 2.40GHz    | 1         | 1.85%   |
| Intel Core i3-7100U CPU @ 2.40GHz    | 1         | 1.85%   |
| Intel Core i3 CPU M 350 @ 2.27GH     | 1         | 1.85%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz | 1         | 1.85%   |
| Intel Core 2 Duo CPU P9700 @ 2.80GHz | 1         | 1.85%   |
| Intel Core 2 Duo CPU P8800 @ 2.66GHz | 1         | 1.85%   |
| Intel Celeron N4000 CPU @ 1.10GHz    | 1         | 1.85%   |
| AMD Ryzen Embedded V1500B            | 1         | 1.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 24        | 44.44%  |
| Intel Core i7      | 12        | 22.22%  |
| Other              | 4         | 7.41%   |
| Intel Core 2 Duo   | 3         | 5.56%   |
| Intel Core i3      | 2         | 3.7%    |
| AMD Ryzen 7        | 2         | 3.7%    |
| Intel Pentium      | 1         | 1.85%   |
| Intel Celeron      | 1         | 1.85%   |
| AMD Ryzen Embedded | 1         | 1.85%   |
| AMD Ryzen 9        | 1         | 1.85%   |
| AMD Ryzen 5 PRO    | 1         | 1.85%   |
| AMD Ryzen 5        | 1         | 1.85%   |
| AMD A4             | 1         | 1.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 30        | 55.56%  |
| 4       | 11        | 20.37%  |
| 16      | 4         | 7.41%   |
| 8       | 3         | 5.56%   |
| 6       | 3         | 5.56%   |
| Unknown | 3         | 5.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 52        | 96.3%   |
| 2       | 1         | 1.85%   |
| Unknown | 1         | 1.85%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 41        | 75.93%  |
| 1       | 10        | 18.52%  |
| Unknown | 3         | 5.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 11        | 20.37%  |
| Unknown       | 7         | 12.96%  |
| Skylake       | 6         | 11.11%  |
| Haswell       | 6         | 11.11%  |
| Westmere      | 5         | 9.26%   |
| SandyBridge   | 4         | 7.41%   |
| Penryn        | 3         | 5.56%   |
| IvyBridge     | 2         | 3.7%    |
| Broadwell     | 2         | 3.7%    |
| Zen+          | 1         | 1.85%   |
| Zen           | 1         | 1.85%   |
| Nehalem       | 1         | 1.85%   |
| IceLake       | 1         | 1.85%   |
| Goldmont plus | 1         | 1.85%   |
| Excavator     | 1         | 1.85%   |
| Core          | 1         | 1.85%   |
| CometLake     | 1         | 1.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 43        | 71.67%  |
| Nvidia | 10        | 16.67%  |
| AMD    | 7         | 11.67%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Skylake-U GT2 [HD Graphics 520]                                     | 6         | 9.84%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 6         | 9.84%   |
| Intel Core Processor Integrated Graphics Controller                       | 5         | 8.2%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 4         | 6.56%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                   | 3         | 4.92%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 3         | 4.92%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 2         | 3.28%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                  | 2         | 3.28%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                 | 2         | 3.28%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 2         | 3.28%   |
| AMD Lucienne                                                              | 2         | 3.28%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                     | 1         | 1.64%   |
| Nvidia MCP89 [GeForce 320M]                                               | 1         | 1.64%   |
| Nvidia GT216M [GeForce GT 330M]                                           | 1         | 1.64%   |
| Nvidia GT216GLM [Quadro FX 880M]                                          | 1         | 1.64%   |
| Nvidia GP108M [GeForce MX230]                                             | 1         | 1.64%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 1.64%   |
| Nvidia GM108M [GeForce 840M]                                              | 1         | 1.64%   |
| Nvidia GF108M [NVS 5400M]                                                 | 1         | 1.64%   |
| Nvidia GF106GLM [Quadro 2000M]                                            | 1         | 1.64%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                             | 1         | 1.64%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 1         | 1.64%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 1         | 1.64%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                  | 1         | 1.64%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 1         | 1.64%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 1         | 1.64%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 1         | 1.64%   |
| Intel Comet Lake-U GT2 [UHD Graphics 620]                                 | 1         | 1.64%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 1         | 1.64%   |
| Intel Alder Lake-N [Intel Graphics]                                       | 1         | 1.64%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 1         | 1.64%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                | 1         | 1.64%   |
| AMD Rembrandt [Radeon 680M]                                               | 1         | 1.64%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 1         | 1.64%   |
| AMD Phoenix1                                                              | 1         | 1.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 34        | 62.96%  |
| Intel + Nvidia | 5         | 9.26%   |
| 1 x AMD        | 5         | 9.26%   |
| 1 x Nvidia     | 4         | 7.41%   |
| 2 x Intel      | 3         | 5.56%   |
| Other          | 1         | 1.85%   |
| Intel + AMD    | 1         | 1.85%   |
| AMD + Nvidia   | 1         | 1.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 47        | 87.04%  |
| Proprietary | 4         | 7.41%   |
| Unknown     | 3         | 5.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 46        | 85.19%  |
| 1.01-2.0   | 4         | 7.41%   |
| 0.01-0.5   | 2         | 3.7%    |
| 3.01-4.0   | 1         | 1.85%   |
| 0.51-1.0   | 1         | 1.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 10        | 24.39%  |
| Chimei Innolux          | 8         | 19.51%  |
| AU Optronics            | 5         | 12.2%   |
| Lenovo                  | 4         | 9.76%   |
| Samsung Electronics     | 2         | 4.88%   |
| TMX                     | 1         | 2.44%   |
| Panasonic               | 1         | 2.44%   |
| Lenovo Group Limited    | 1         | 2.44%   |
| InfoVision              | 1         | 2.44%   |
| Hewlett-Packard         | 1         | 2.44%   |
| Goldstar                | 1         | 2.44%   |
| Gigabyte Technology     | 1         | 2.44%   |
| Dell                    | 1         | 2.44%   |
| Chi Mei Optoelectronics | 1         | 2.44%   |
| BOE                     | 1         | 2.44%   |
| Apple                   | 1         | 2.44%   |
| Ancor Communications    | 1         | 2.44%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch                  | 2         | 4.88%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x170mm 13.9-inch                  | 1         | 2.44%   |
| Samsung Electronics S27R35x SAM1053 1920x1080 600x340mm 27.2-inch        | 1         | 2.44%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 300x170mm 13.6-inch     | 1         | 2.44%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 340x190mm 15.3-inch              | 1         | 2.44%   |
| LG Display LCD Monitor LGD070B 1920x1080 310x170mm 13.9-inch             | 1         | 2.44%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch             | 1         | 2.44%   |
| LG Display LCD Monitor LGD05B6 1920x1080 310x170mm 13.9-inch             | 1         | 2.44%   |
| LG Display LCD Monitor LGD0569 1920x1080 310x170mm 13.9-inch             | 1         | 2.44%   |
| LG Display LCD Monitor LGD04A7 1920x1080 340x190mm 15.3-inch             | 1         | 2.44%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch             | 1         | 2.44%   |
| LG Display LCD Monitor LGD040A 1920x1080 310x170mm 13.9-inch             | 1         | 2.44%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x170mm 13.9-inch              | 1         | 2.44%   |
| LG Display LCD Monitor LGD027B 1600x900 380x210mm 17.1-inch              | 1         | 2.44%   |
| LG Display LCD Monitor LGD0213 1600x900 310x170mm 13.9-inch              | 1         | 2.44%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch                  | 1         | 2.44%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch                  | 1         | 2.44%   |
| Lenovo Group Limited LCD Monitor 1920x1080                               | 1         | 2.44%   |
| InfoVision LCD Monitor IVO04E3 1366x768 280x160mm 12.7-inch              | 1         | 2.44%   |
| Hewlett-Packard E242 HWP326E 1920x1200 520x320mm 24.0-inch               | 1         | 2.44%   |
| Goldstar LG HDR WQHD+ GSM774C 3840x1600 880x370mm 37.6-inch              | 1         | 2.44%   |
| Gigabyte Technology M28U GBT2800 3840x2160 630x360mm 28.6-inch           | 1         | 2.44%   |
| Dell U2718Q DELA0EC 3840x2160 610x350mm 27.7-inch                        | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 340x190mm 15.3-inch         | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 340x190mm 15.3-inch          | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN15B1 1920x1080 340x190mm 15.3-inch         | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN1509 1920x1080 340x190mm 15.3-inch         | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch         | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 310x170mm 13.9-inch         | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN13A2 1920x1080 290x170mm 13.2-inch         | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch          | 1         | 2.44%   |
| Chi Mei Optoelectronics LCD Monitor CMO1593 1366x768 340x190mm 15.3-inch | 1         | 2.44%   |
| BOE NE135A1M-NY1 BOE0CB4 2880x1920 290x190mm 13.6-inch                   | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO47EC 1366x768 340x190mm 15.3-inch            | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO282B 3840x2160 290x170mm 13.2-inch           | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO219E 1600x900 380x210mm 17.1-inch            | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO103D 1920x1080 310x170mm 13.9-inch           | 1         | 2.44%   |
| Apple Color LCD APPA020 2560x1600 290x180mm 13.4-inch                    | 1         | 2.44%   |
| Ancor Communications VG248 ACI24A5 1920x1080 530x300mm 24.0-inch         | 1         | 2.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 16        | 40%     |
| 1366x768 (WXGA)   | 7         | 17.5%   |
| 1600x900 (HD+)    | 6         | 15%     |
| 3840x2160 (4K)    | 4         | 10%     |
| 3840x1600         | 1         | 2.5%    |
| 2880x1920         | 1         | 2.5%    |
| 2560x1600         | 1         | 2.5%    |
| 2560x1440 (QHD)   | 1         | 2.5%    |
| 1920x1200 (WUXGA) | 1         | 2.5%    |
| 1440x900 (WXGA+)  | 1         | 2.5%    |
| 1280x800 (WXGA)   | 1         | 2.5%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 13      | 14        | 34.15%  |
| 15      | 11        | 26.83%  |
| 17      | 3         | 7.32%   |
| 12      | 3         | 7.32%   |
| 27      | 2         | 4.88%   |
| 24      | 2         | 4.88%   |
| 14      | 2         | 4.88%   |
| 37      | 1         | 2.44%   |
| 28      | 1         | 2.44%   |
| 11      | 1         | 2.44%   |
| Unknown | 1         | 2.44%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 21        | 51.22%  |
| 201-300     | 10        | 24.39%  |
| 501-600     | 3         | 7.32%   |
| 351-400     | 3         | 7.32%   |
| 601-700     | 2         | 4.88%   |
| 801-900     | 1         | 2.44%   |
| Unknown     | 1         | 2.44%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 29        | 78.38%  |
| 16/10   | 4         | 10.81%  |
| 3/2     | 2         | 5.41%   |
| 21/9    | 1         | 2.7%    |
| Unknown | 1         | 2.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 14        | 34.15%  |
| 91-100         | 8         | 19.51%  |
| 61-70          | 3         | 7.32%   |
| 121-130        | 3         | 7.32%   |
| 101-110        | 3         | 7.32%   |
| 71-80          | 2         | 4.88%   |
| 301-350        | 2         | 4.88%   |
| 51-60          | 1         | 2.44%   |
| 351-500        | 1         | 2.44%   |
| 251-300        | 1         | 2.44%   |
| 201-250        | 1         | 2.44%   |
| 501-1000       | 1         | 2.44%   |
| Unknown        | 1         | 2.44%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 21        | 52.5%   |
| 101-120       | 9         | 22.5%   |
| More than 240 | 3         | 7.5%    |
| 161-240       | 3         | 7.5%    |
| 51-100        | 3         | 7.5%    |
| Unknown       | 1         | 2.5%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 37        | 67.27%  |
| 0     | 14        | 25.45%  |
| 2     | 3         | 5.45%   |
| 3     | 1         | 1.82%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 40        | 54.05%  |
| Realtek Semiconductor | 15        | 20.27%  |
| Sierra Wireless       | 4         | 5.41%   |
| Qualcomm Atheros      | 4         | 5.41%   |
| Broadcom              | 4         | 5.41%   |
| Ralink Technology     | 1         | 1.35%   |
| MediaTek              | 1         | 1.35%   |
| JMicron Technology    | 1         | 1.35%   |
| Google                | 1         | 1.35%   |
| Edimax Technology     | 1         | 1.35%   |
| Dell                  | 1         | 1.35%   |
| AMD                   | 1         | 1.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 10        | 9.8%    |
| Intel Wireless 8260                                                    | 5         | 4.9%    |
| Intel Wireless 7260                                                    | 4         | 3.92%   |
| Intel Ethernet Connection I219-LM                                      | 4         | 3.92%   |
| Intel 82577LM Gigabit Network Connection                               | 4         | 3.92%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 3         | 2.94%   |
| Intel Wireless 8265 / 8275                                             | 3         | 2.94%   |
| Intel Wireless 7265                                                    | 3         | 2.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 3         | 2.94%   |
| Intel Centrino Advanced-N 6200                                         | 3         | 2.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 2.94%   |
| Sierra Wireless EM7345 4G LTE                                          | 2         | 1.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2         | 1.96%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2         | 1.96%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 2         | 1.96%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 2         | 1.96%   |
| Intel Wi-Fi 6 AX200                                                    | 2         | 1.96%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 1.96%   |
| Intel Ethernet Connection (6) I219-LM                                  | 2         | 1.96%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 1.96%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 1.96%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 2         | 1.96%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 2         | 1.96%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 2         | 1.96%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 2         | 1.96%   |
| Sierra Wireless EM7565 USB Device                                      | 1         | 0.98%   |
| Sierra Wireless EM7455                                                 | 1         | 0.98%   |
| Realtek USB 2.5GbE Controller                                          | 1         | 0.98%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 1         | 0.98%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 1         | 0.98%   |
| Ralink RT5370 Wireless Adapter                                         | 1         | 0.98%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 1         | 0.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 1         | 0.98%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 1         | 0.98%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 1         | 0.98%   |
| Intel WiFi Link 5100                                                   | 1         | 0.98%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 1         | 0.98%   |
| Intel I211 Gigabit Network Connection                                  | 1         | 0.98%   |
| Intel Ethernet Connection I219-V                                       | 1         | 0.98%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 0.98%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 36        | 62.07%  |
| Realtek Semiconductor | 6         | 10.34%  |
| Sierra Wireless       | 4         | 6.9%    |
| Qualcomm Atheros      | 4         | 6.9%    |
| Broadcom              | 4         | 6.9%    |
| Ralink Technology     | 1         | 1.72%   |
| MediaTek              | 1         | 1.72%   |
| Edimax Technology     | 1         | 1.72%   |
| Dell                  | 1         | 1.72%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                            | 5         | 8.47%   |
| Intel Wireless 7260                                            | 4         | 6.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 3         | 5.08%   |
| Intel Wireless 8265 / 8275                                     | 3         | 5.08%   |
| Intel Wireless 7265                                            | 3         | 5.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 5.08%   |
| Intel Centrino Advanced-N 6200                                 | 3         | 5.08%   |
| Sierra Wireless EM7345 4G LTE                                  | 2         | 3.39%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 3.39%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 3.39%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 2         | 3.39%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 3.39%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 3.39%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 3.39%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 2         | 3.39%   |
| Sierra Wireless EM7565 USB Device                              | 1         | 1.69%   |
| Sierra Wireless EM7455                                         | 1         | 1.69%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 1.69%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 1.69%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 1.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 1.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 1.69%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 1         | 1.69%   |
| Intel WiFi Link 5100                                           | 1         | 1.69%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 1         | 1.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 1.69%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 1.69%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 1.69%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 1.69%   |
| Intel Alder Lake-N PCH CNVi WiFi                               | 1         | 1.69%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 1         | 1.69%   |
| Dell Wireless 5809e Gobi 4G LTE Mobile Broadband DM Port       | 1         | 1.69%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 1         | 1.69%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 1         | 1.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 25        | 59.52%  |
| Realtek Semiconductor | 13        | 30.95%  |
| Broadcom              | 2         | 4.76%   |
| JMicron Technology    | 1         | 2.38%   |
| AMD                   | 1         | 2.38%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 10        | 23.81%  |
| Intel Ethernet Connection I219-LM                                      | 4         | 9.52%   |
| Intel 82577LM Gigabit Network Connection                               | 4         | 9.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 7.14%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2         | 4.76%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 4.76%   |
| Intel Ethernet Connection (6) I219-LM                                  | 2         | 4.76%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 4.76%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 4.76%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 2         | 4.76%   |
| Realtek USB 2.5GbE Controller                                          | 1         | 2.38%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 1         | 2.38%   |
| Intel I211 Gigabit Network Connection                                  | 1         | 2.38%   |
| Intel Ethernet Connection I219-V                                       | 1         | 2.38%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 2.38%   |
| Intel Ethernet Connection (11) I219-LM                                 | 1         | 2.38%   |
| Intel 82567LM Gigabit Network Connection                               | 1         | 2.38%   |
| Intel 82566MM Gigabit Network Connection                               | 1         | 2.38%   |
| AMD XGMAC 10GbE Controller                                             | 1         | 2.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 50        | 54.35%  |
| Ethernet | 41        | 44.57%  |
| Unknown  | 1         | 1.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 37        | 62.71%  |
| Ethernet | 22        | 37.29%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 33        | 61.11%  |
| 1     | 19        | 35.19%  |
| 5     | 1         | 1.85%   |
| 3     | 1         | 1.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 52        | 96.3%   |
| Yes  | 2         | 3.7%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 23        | 57.5%   |
| Broadcom              | 4         | 10%     |
| Apple                 | 4         | 10%     |
| Realtek Semiconductor | 3         | 7.5%    |
| Hewlett-Packard       | 2         | 5%      |
| MediaTek              | 1         | 2.5%    |
| Lite-On Technology    | 1         | 2.5%    |
| IMC Networks          | 1         | 2.5%    |
| Dell                  | 1         | 2.5%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                      | 12        | 30%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 4         | 10%     |
| Broadcom BCM2045B (BDC-2.1)                             | 4         | 10%     |
| Realtek Bluetooth Adapter                               | 3         | 7.5%    |
| Apple Bluetooth Host Controller                         | 3         | 7.5%    |
| Intel AX210 Bluetooth                                   | 2         | 5%      |
| Intel AX200 Bluetooth                                   | 2         | 5%      |
| MediaTek Wireless_Device                                | 1         | 2.5%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth              | 1         | 2.5%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                | 1         | 2.5%    |
| Intel Wireless-AC 3168 Bluetooth                        | 1         | 2.5%    |
| Intel AX201 Bluetooth                                   | 1         | 2.5%    |
| IMC Networks Qualcomm Atheros AR3012 Bluetooth 4.0 + HS | 1         | 2.5%    |
| HP Broadcom 2070 Bluetooth Combo                        | 1         | 2.5%    |
| HP Atheros AR9285 Malbec Bluetooth Adapter              | 1         | 2.5%    |
| Dell Dell Wireless 380 Bluetooth 4.0 Module             | 1         | 2.5%    |
| Apple Broadcom Built-in Bluetooth                       | 1         | 2.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 46        | 73.02%  |
| AMD                                          | 7         | 11.11%  |
| Nvidia                                       | 6         | 9.52%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 1.59%   |
| Realtek Semiconductor                        | 1         | 1.59%   |
| Lenovo                                       | 1         | 1.59%   |
| GN Netcom                                    | 1         | 1.59%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 10        | 13.16%  |
| Intel Haswell-ULT HD Audio Controller                                      | 6         | 7.89%   |
| Intel 8 Series HD Audio Controller                                         | 6         | 7.89%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 7.89%   |
| AMD Ryzen HD Audio Controller                                              | 6         | 7.89%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 5.26%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 3.95%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 3.95%   |
| Nvidia GT216 HDMI Audio Controller                                         | 2         | 2.63%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 2.63%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 2.63%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 2.63%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 2         | 2.63%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 2.63%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 2         | 2.63%   |
| AMD Radeon High Definition Audio Controller                                | 2         | 2.63%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID             | 1         | 1.32%   |
| Realtek Semiconductor USB Audio                                            | 1         | 1.32%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 1.32%   |
| Nvidia MCP89 High Definition Audio                                         | 1         | 1.32%   |
| Nvidia GF106 High Definition Audio Controller                              | 1         | 1.32%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 1.32%   |
| Lenovo Realtek USB Audio                                                   | 1         | 1.32%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 1.32%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.32%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.32%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.32%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                    | 1         | 1.32%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 1.32%   |
| GN Netcom Jabra Evolve 75                                                  | 1         | 1.32%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 1.32%   |
| AMD High Definition Audio Controller                                       | 1         | 1.32%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 16        | 26.23%  |
| SK hynix            | 15        | 24.59%  |
| Micron Technology   | 9         | 14.75%  |
| Kingston            | 5         | 8.2%    |
| Elpida              | 4         | 6.56%   |
| Unknown             | 2         | 3.28%   |
| Transcend           | 2         | 3.28%   |
| GSkill              | 2         | 3.28%   |
| Toshiba             | 1         | 1.64%   |
| Ramaxel Technology  | 1         | 1.64%   |
| Crucial             | 1         | 1.64%   |
| Corsair             | 1         | 1.64%   |
| A-DATA Technology   | 1         | 1.64%   |
| Unknown             | 1         | 1.64%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 2         | 3.03%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s         | 2         | 3.03%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s         | 2         | 3.03%   |
| Micron RAM 16KTF51264HZ-1G4M1 4GB SODIMM DDR3 1333MT/s        | 2         | 3.03%   |
| GSkill RAM F4-3200C22-16GRS 16GB SODIMM DDR4 3200MT/s         | 2         | 3.03%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3                  | 2         | 3.03%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                   | 1         | 1.52%   |
| Unknown RAM Module 2GB SODIMM DDR3                            | 1         | 1.52%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s           | 1         | 1.52%   |
| Transcend RAM Module 2GB SODIMM DDR3 1067MT/s                 | 1         | 1.52%   |
| Toshiba RAM 8HTF12864HDY-800G1 2048MB SODIMM 800MT/s          | 1         | 1.52%   |
| Toshiba RAM 64T128020EDL2.5C2 2048MB SODIMM 800MT/s           | 1         | 1.52%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                  | 1         | 1.52%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1067MT/s                  | 1         | 1.52%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1067MT/s                  | 1         | 1.52%   |
| SK hynix RAM HMT851S6AMR6A-PB 4GB Chip DDR3 1600MT/s          | 1         | 1.52%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 1.52%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 1.52%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 1.52%   |
| SK hynix RAM HMT125S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s     | 1         | 1.52%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s  | 1         | 1.52%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s        | 1         | 1.52%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s       | 1         | 1.52%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 1         | 1.52%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s        | 1         | 1.52%   |
| Samsung RAM Module 3GB Row Of Chips LPDDR5 6400MT/s           | 1         | 1.52%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s         | 1         | 1.52%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s         | 1         | 1.52%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s         | 1         | 1.52%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s         | 1         | 1.52%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3200MT/s         | 1         | 1.52%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s   | 1         | 1.52%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s         | 1         | 1.52%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2400MT/s         | 1         | 1.52%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s         | 1         | 1.52%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s        | 1         | 1.52%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s        | 1         | 1.52%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s         | 1         | 1.52%   |
| Samsung RAM M425R1GB4BB0-CQKOD 8GB Row Of Chips DDR5 4800MT/s | 1         | 1.52%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s  | 1         | 1.52%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 22        | 44.9%   |
| DDR3    | 20        | 40.82%  |
| LPDDR3  | 2         | 4.08%   |
| DDR5    | 2         | 4.08%   |
| LPDDR5  | 1         | 2.04%   |
| DDR2    | 1         | 2.04%   |
| Unknown | 1         | 2.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 44        | 84.62%  |
| Row Of Chips | 6         | 11.54%  |
| Chip         | 2         | 3.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 19        | 35.19%  |
| 8192  | 18        | 33.33%  |
| 16384 | 8         | 14.81%  |
| 2048  | 7         | 12.96%  |
| 32768 | 1         | 1.85%   |
| 3072  | 1         | 1.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 11        | 19.3%   |
| 1600    | 11        | 19.3%   |
| 3200    | 9         | 15.79%  |
| 2400    | 5         | 8.77%   |
| 1334    | 5         | 8.77%   |
| 1333    | 4         | 7.02%   |
| 2133    | 2         | 3.51%   |
| 1067    | 2         | 3.51%   |
| 800     | 2         | 3.51%   |
| 6400    | 1         | 1.75%   |
| 5600    | 1         | 1.75%   |
| 4800    | 1         | 1.75%   |
| 1867    | 1         | 1.75%   |
| 1066    | 1         | 1.75%   |
| Unknown | 1         | 1.75%   |

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


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 12        | 30.77%  |
| Bison Electronics             | 6         | 15.38%  |
| Microdia                      | 5         | 12.82%  |
| IMC Networks                  | 4         | 10.26%  |
| Lenovo                        | 3         | 7.69%   |
| Syntek                        | 2         | 5.13%   |
| Realtek Semiconductor         | 2         | 5.13%   |
| Suyin                         | 1         | 2.56%   |
| Sunplus Innovation Technology | 1         | 2.56%   |
| Quanta                        | 1         | 2.56%   |
| Logitech                      | 1         | 2.56%   |
| Framework                     | 1         | 2.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Bison Integrated Camera                  | 4         | 10.26%  |
| Chicony Integrated Camera                | 3         | 7.69%   |
| Microdia USB  Live camera                | 2         | 5.13%   |
| Microdia Integrated Webcam               | 2         | 5.13%   |
| Lenovo Integrated Webcam                 | 2         | 5.13%   |
| Bison ThinkPad P50 Integrated Camera     | 2         | 5.13%   |
| Syntek Integrated Camera                 | 1         | 2.56%   |
| Syntek EasyCamera                        | 1         | 2.56%   |
| Suyin Asus Integrated Webcam             | 1         | 2.56%   |
| Sunplus Laptop Integrated Webcam HD      | 1         | 2.56%   |
| Realtek Integrated_Webcam_HD             | 1         | 2.56%   |
| Realtek Front Camera                     | 1         | 2.56%   |
| Quanta VGA WebCam                        | 1         | 2.56%   |
| Microdia Integrated_Webcam_HD            | 1         | 2.56%   |
| Logitech Webcam C270                     | 1         | 2.56%   |
| Lenovo Integrated Webcam [R5U877]        | 1         | 2.56%   |
| IMC Networks Integrated RGB Camera       | 1         | 2.56%   |
| IMC Networks Integrated Camera           | 1         | 2.56%   |
| IMC Networks HP TrueVision HD Camera     | 1         | 2.56%   |
| IMC Networks EasyCamera                  | 1         | 2.56%   |
| Framework Laptop Webcam Module (2nd Gen) | 1         | 2.56%   |
| Chicony USB2.0 HD UVC WebCam             | 1         | 2.56%   |
| Chicony USB 2.0 VGA UVC WebCam           | 1         | 2.56%   |
| Chicony TOSHIBA Web Camera - FHD         | 1         | 2.56%   |
| Chicony ThinkPad T490 Webcam             | 1         | 2.56%   |
| Chicony Realtek DMFT RGB                 | 1         | 2.56%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 1         | 2.56%   |
| Chicony Integrated HP HD Webcam          | 1         | 2.56%   |
| Chicony FJ Camera                        | 1         | 2.56%   |
| Chicony Camera                           | 1         | 2.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 5         | 31.25%  |
| Upek                       | 3         | 18.75%  |
| Elan Microelectronics      | 2         | 12.5%   |
| Broadcom                   | 2         | 12.5%   |
| AuthenTec                  | 2         | 12.5%   |
| Synaptics                  | 1         | 6.25%   |
| Shenzhen Goodix Technology | 1         | 6.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 3         | 18.75%  |
| Elan Fingerprint Sensor                                                      | 2         | 12.5%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 12.5%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 1         | 6.25%   |
| Validity Sensors VFS451 Fingerprint Reader                                   | 1         | 6.25%   |
| Validity Sensors VFS Fingerprint sensor                                      | 1         | 6.25%   |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 1         | 6.25%   |
| Validity Sensors Synaptics WBDI                                              | 1         | 6.25%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 1         | 6.25%   |
| Shenzhen Goodix Fingerprint Reader                                           | 1         | 6.25%   |
| AuthenTec AES2810                                                            | 1         | 6.25%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 1         | 6.25%   |

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
| 2     | 24        | 43.64%  |
| 1     | 15        | 27.27%  |
| 3     | 9         | 16.36%  |
| 4     | 3         | 5.45%   |
| 0     | 3         | 5.45%   |
| 5     | 1         | 1.82%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 43        | 44.33%  |
| Fingerprint reader       | 13        | 13.4%   |
| Card reader              | 12        | 12.37%  |
| Bluetooth                | 10        | 10.31%  |
| Firewire controller      | 7         | 7.22%   |
| Net/wireless             | 5         | 5.15%   |
| Network                  | 3         | 3.09%   |
| Graphics card            | 2         | 2.06%   |
| Storage/ata              | 1         | 1.03%   |
| Sound                    | 1         | 1.03%   |

