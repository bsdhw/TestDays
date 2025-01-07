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

Total: 54

| Vendor    | Model                       | Probe                                                     | Date         |
|-----------|-----------------------------|-----------------------------------------------------------|--------------|
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
| helloSystem 0.5.0    | 4         | 8.89%   |
| OpenBSD 7.0          | 3         | 6.67%   |
| helloSystem 0.8.0    | 3         | 6.67%   |
| OpenBSD 6.9          | 2         | 4.44%   |
| helloSystem 0.9.0    | 2         | 4.44%   |
| helloSystem 0.7.0    | 2         | 4.44%   |
| helloSystem 0.4.0    | 2         | 4.44%   |
| FreeBSD 14.0         | 2         | 4.44%   |
| FreeBSD 13.1-p5      | 2         | 4.44%   |
| FreeBSD 12.1-p8      | 2         | 4.44%   |
| OPNsense 24.7.9      | 1         | 2.22%   |
| OPNsense 22.10       | 1         | 2.22%   |
| OPNsense 21.1        | 1         | 2.22%   |
| OpenBSD 7.2          | 1         | 2.22%   |
| OpenBSD 6.8          | 1         | 2.22%   |
| OpenBSD 6.7          | 1         | 2.22%   |
| NomadBSD 20221130    | 1         | 2.22%   |
| helloSystem 0.8.1    | 1         | 2.22%   |
| GhostBSD 22.08.27    | 1         | 2.22%   |
| GhostBSD 21.08.27    | 1         | 2.22%   |
| GhostBSD 20.04.02    | 1         | 2.22%   |
| FreeBSD 15.0-CURRENT | 1         | 2.22%   |
| FreeBSD 14.1         | 1         | 2.22%   |
| FreeBSD 14.0-p6      | 1         | 2.22%   |
| FreeBSD 14.0-p2      | 1         | 2.22%   |
| FreeBSD 14.0-CURRENT | 1         | 2.22%   |
| FreeBSD 13.2-p4      | 1         | 2.22%   |
| FreeBSD 13.1-p7      | 1         | 2.22%   |
| FreeBSD 13.0-p7      | 1         | 2.22%   |
| FreeBSD 13.0-p10     | 1         | 2.22%   |
| FreeBSD 13.0         | 1         | 2.22%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 16        | 36.36%  |
| helloSystem | 14        | 31.82%  |
| OpenBSD     | 7         | 15.91%  |
| OPNsense    | 3         | 6.82%   |
| GhostBSD    | 3         | 6.82%   |
| NomadBSD    | 1         | 2.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 44        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 15        | 33.33%  |
| fvwm         | 6         | 13.33%  |
| Console      | 6         | 13.33%  |
| KDE5         | 5         | 11.11%  |
| MATE         | 3         | 6.67%   |
| XFCE         | 2         | 4.44%   |
| i3           | 2         | 4.44%   |
| GNOME        | 2         | 4.44%   |
| TWM          | 1         | 2.22%   |
| Openbox      | 1         | 2.22%   |
| Mutter       | 1         | 2.22%   |
| LXQt         | 1         | 2.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 37        | 84.09%  |
| Console | 7         | 15.91%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 15        | 34.09%  |
| Console | 14        | 31.82%  |
| LightDM | 6         | 13.64%  |
| SDDM    | 5         | 11.36%  |
| XDM     | 2         | 4.55%   |
| GDM     | 2         | 4.55%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| C       | 13        | 29.55%  |
| Unknown | 13        | 29.55%  |
| en_US   | 12        | 27.27%  |
| sv_SE   | 2         | 4.55%   |
| sv      | 1         | 2.27%   |
| en_GB   | 1         | 2.27%   |
| en_BE   | 1         | 2.27%   |
| en      | 1         | 2.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 38        | 84.44%  |
| BIOS | 7         | 15.56%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 27        | 61.36%  |
| Ffs    | 7         | 15.91%  |
| Ufs    | 5         | 11.36%  |
| Cd9660 | 5         | 11.36%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 41        | 89.13%  |
| MBR  | 5         | 10.87%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 17        | 38.64%  |
| Hewlett-Packard  | 6         | 13.64%  |
| Dell             | 5         | 11.36%  |
| ASUSTek Computer | 3         | 6.82%   |
| Apple            | 3         | 6.82%   |
| Toshiba          | 2         | 4.55%   |
| Star Labs        | 2         | 4.55%   |
| Sony             | 1         | 2.27%   |
| Razer            | 1         | 2.27%   |
| Google           | 1         | 2.27%   |
| Framework        | 1         | 2.27%   |
| Deciso           | 1         | 2.27%   |
| Acer             | 1         | 2.27%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Star Labs StarBook                         | 2         | 4.55%   |
| Toshiba TECRA Z40-C-12Z                    | 1         | 2.27%   |
| Toshiba Satellite L450                     | 1         | 2.27%   |
| Sony SVP1322M1EBI                          | 1         | 2.27%   |
| Razer Blade 14 (2022) - RZ09-0427          | 1         | 2.27%   |
| Lenovo V130-15IGM 81HL                     | 1         | 2.27%   |
| Lenovo ThinkPad X395 20NL001SMX            | 1         | 2.27%   |
| Lenovo ThinkPad X250 20CLS4JH00            | 1         | 2.27%   |
| Lenovo ThinkPad X201 3680FAG               | 1         | 2.27%   |
| Lenovo ThinkPad X201 3626HMG               | 1         | 2.27%   |
| Lenovo ThinkPad W520 4284GN2               | 1         | 2.27%   |
| Lenovo ThinkPad T530 23942U1               | 1         | 2.27%   |
| Lenovo ThinkPad T480 20L6SDA400            | 1         | 2.27%   |
| Lenovo ThinkPad T470s W10DG 20JTS0W800     | 1         | 2.27%   |
| Lenovo ThinkPad T460s 20FAS4KH02           | 1         | 2.27%   |
| Lenovo ThinkPad T420 4236MBG               | 1         | 2.27%   |
| Lenovo ThinkPad T400 2767WSB               | 1         | 2.27%   |
| Lenovo ThinkPad L560 20F10032MS            | 1         | 2.27%   |
| Lenovo Legion Y530-15ICH 81FV              | 1         | 2.27%   |
| Lenovo IdeaPad L340-17IWL 81M0             | 1         | 2.27%   |
| Lenovo IdeaPad 5 14ALC05 82LM              | 1         | 2.27%   |
| Lenovo IdeaPad 3 14IML05 81WA              | 1         | 2.27%   |
| HP ProBook 4730s                           | 1         | 2.27%   |
| HP Pavilion Laptop 14-bf0xx                | 1         | 2.27%   |
| HP Pavilion g6                             | 1         | 2.27%   |
| HP Laptop 15-dw0xxx                        | 1         | 2.27%   |
| HP EliteBook 8440p                         | 1         | 2.27%   |
| Google Grunt                               | 1         | 2.27%   |
| Framework Laptop 13 (AMD Ryzen 7040Series) | 1         | 2.27%   |
| Dell XPS 13 7390                           | 1         | 2.27%   |
| Dell Latitude E7250                        | 1         | 2.27%   |
| Dell Latitude E7240                        | 1         | 2.27%   |
| Dell Latitude E5530 non-vPro               | 1         | 2.27%   |
| Dell Latitude 5500                         | 1         | 2.27%   |
| Deciso NetBoard-A10                        | 1         | 2.27%   |
| ASUS UX305UA                               | 1         | 2.27%   |
| ASUS S551LN                                | 1         | 2.27%   |
| ASUS K52Jc                                 | 1         | 2.27%   |
| Apple MacBookPro6,2                        | 1         | 2.27%   |
| Apple MacBookPro11,1                       | 1         | 2.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 12        | 27.27%  |
| Dell Latitude       | 4         | 9.09%   |
| Lenovo IdeaPad      | 3         | 6.82%   |
| Star Labs StarBook  | 2         | 4.55%   |
| HP Pavilion         | 2         | 4.55%   |
| Toshiba TECRA       | 1         | 2.27%   |
| Toshiba Satellite   | 1         | 2.27%   |
| Sony SVP1322M1EBI   | 1         | 2.27%   |
| Razer Blade         | 1         | 2.27%   |
| Lenovo V130-15IGM   | 1         | 2.27%   |
| Lenovo Legion       | 1         | 2.27%   |
| HP ProBook          | 1         | 2.27%   |
| HP Laptop           | 1         | 2.27%   |
| HP EliteBook        | 1         | 2.27%   |
| Google Grunt        | 1         | 2.27%   |
| Framework Laptop    | 1         | 2.27%   |
| Dell XPS            | 1         | 2.27%   |
| Deciso NetBoard-A10 | 1         | 2.27%   |
| ASUS UX305UA        | 1         | 2.27%   |
| ASUS S551LN         | 1         | 2.27%   |
| ASUS K52Jc          | 1         | 2.27%   |
| Apple MacBookPro6   | 1         | 2.27%   |
| Apple MacBookPro11  | 1         | 2.27%   |
| Apple MacBookAir6   | 1         | 2.27%   |
| Acer Aspire         | 1         | 2.27%   |
| Unknown             | 1         | 2.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 6         | 13.64%  |
| 2021 | 5         | 11.36%  |
| 2023 | 3         | 6.82%   |
| 2022 | 3         | 6.82%   |
| 2019 | 3         | 6.82%   |
| 2018 | 3         | 6.82%   |
| 2017 | 3         | 6.82%   |
| 2014 | 3         | 6.82%   |
| 2010 | 3         | 6.82%   |
| 2009 | 3         | 6.82%   |
| 2016 | 2         | 4.55%   |
| 2015 | 2         | 4.55%   |
| 2011 | 2         | 4.55%   |
| 2024 | 1         | 2.27%   |
| 2013 | 1         | 2.27%   |
| 2012 | 1         | 2.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 44        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 40        | 90.91%  |
| Yes  | 4         | 9.09%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 16        | 36.36%  |
| 4.01-8.0    | 12        | 27.27%  |
| 16.01-24.0  | 9         | 20.45%  |
| 32.01-64.0  | 4         | 9.09%   |
| 3.01-4.0    | 1         | 2.27%   |
| 24.01-32.0  | 1         | 2.27%   |
| 64.01-256.0 | 1         | 2.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 26        | 59.09%  |
| 0.51-1.0 | 10        | 22.73%  |
| 1.01-2.0 | 6         | 13.64%  |
| 4.01-8.0 | 1         | 2.27%   |
| 2.01-3.0 | 1         | 2.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 33        | 75%     |
| 2      | 6         | 13.64%  |
| 0      | 4         | 9.09%   |
| 3      | 1         | 2.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 33        | 75%     |
| Yes       | 11        | 25%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 72.73%  |
| No        | 12        | 27.27%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 40        | 90.91%  |
| No        | 4         | 9.09%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 64.44%  |
| No        | 16        | 35.56%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Sweden  | 44        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Stockholm      | 8         | 17.39%  |
| Malmo          | 4         | 8.7%    |
| Henan          | 3         | 6.52%   |
| VÃ¤sterÃ¥s | 2         | 4.35%   |
| Gothenburg     | 2         | 4.35%   |
| Varekil        | 1         | 2.17%   |
| Vallingby      | 1         | 2.17%   |
| Trosa          | 1         | 2.17%   |
| Staffanstorp   | 1         | 2.17%   |
| Solna          | 1         | 2.17%   |
| Sollentuna     | 1         | 2.17%   |
| Sollebrunn     | 1         | 2.17%   |
| Södertälje   | 1         | 2.17%   |
| SkellefteÃ¥  | 1         | 2.17%   |
| Skellefteå    | 1         | 2.17%   |
| OEvertornea    | 1         | 2.17%   |
| OEverlida      | 1         | 2.17%   |
| Lund           | 1         | 2.17%   |
| LuleÃ¥       | 1         | 2.17%   |
| Lidkoeping     | 1         | 2.17%   |
| Kungsbacka     | 1         | 2.17%   |
| Klagshamn      | 1         | 2.17%   |
| Hultsfred      | 1         | 2.17%   |
| Hoeviksnaes    | 1         | 2.17%   |
| Hoerby         | 1         | 2.17%   |
| GГ¤vle       | 1         | 2.17%   |
| Falkenberg     | 1         | 2.17%   |
| Faergelanda    | 1         | 2.17%   |
| Eskilstuna     | 1         | 2.17%   |
| Enebyberg      | 1         | 2.17%   |
| Borensberg     | 1         | 2.17%   |
| Bastad         | 1         | 2.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 12     | 23.26%  |
| Seagate             | 5         | 5      | 11.63%  |
| Kingston            | 5         | 5      | 11.63%  |
| WDC                 | 4         | 4      | 9.3%    |
| SanDisk             | 3         | 3      | 6.98%   |
| Micron Technology   | 2         | 2      | 4.65%   |
| Intel               | 2         | 2      | 4.65%   |
| Hitachi             | 2         | 2      | 4.65%   |
| Apple               | 2         | 2      | 4.65%   |
| Transcend           | 1         | 1      | 2.33%   |
| Toshiba             | 1         | 1      | 2.33%   |
| Star Drive          | 1         | 1      | 2.33%   |
| SK hynix            | 1         | 1      | 2.33%   |
| NVMe                | 1         | 1      | 2.33%   |
| Dogfish             | 1         | 1      | 2.33%   |
| Crucial             | 1         | 1      | 2.33%   |
| A-DATA Technology   | 1         | 1      | 2.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 250GB            | 2         | 4.55%   |
| Kingston SV300S37A120G 120GB         | 2         | 4.55%   |
| Kingston SA400S37120G 120GB          | 2         | 4.55%   |
| WDC WD6400BPVT-60HXZT1 640GB         | 1         | 2.27%   |
| WDC WD3200BEKT-08PVMT1 320GB         | 1         | 2.27%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 1         | 2.27%   |
| WDC PC SN520 NVMe 256GB              | 1         | 2.27%   |
| Transcend TS256GMTE652T2 256GB       | 1         | 2.27%   |
| Toshiba KSG60ZMV256G 256GB           | 1         | 2.27%   |
| Star Drive PCIe SSD 960GB            | 1         | 2.27%   |
| SK hynix HFS128G32TNF-N3A0A 128GB    | 1         | 2.27%   |
| Seagate ST9640320AS 640GB            | 1         | 2.27%   |
| Seagate ST9500420AS 500GB            | 1         | 2.27%   |
| Seagate ST9320423AS 320GB            | 1         | 2.27%   |
| Seagate ST750LM022 HN-M750MBB 752GB  | 1         | 2.27%   |
| Seagate ST1000LM049-2GH172 1TB       | 1         | 2.27%   |
| SanDisk SDSSDHP256G 256GB            | 1         | 2.27%   |
| SanDisk SD8TN8U256G1001 256GB        | 1         | 2.27%   |
| SanDisk SD8SN8U-256G-1006 256GB      | 1         | 2.27%   |
| Samsung SSD PM851 mSATA 256GB        | 1         | 2.27%   |
| Samsung SSD PM830 2.5-inch 7mm 128GB | 1         | 2.27%   |
| Samsung SSD 860 PRO 256GB            | 1         | 2.27%   |
| Samsung PM981a NVMe 512GB            | 1         | 2.27%   |
| Samsung PM981 NVMe 256GB             | 1         | 2.27%   |
| Samsung MZVLW256HEHP-000L7 256GB     | 1         | 2.27%   |
| Samsung MZNTE128HMGR-000SO 128GB     | 1         | 2.27%   |
| Samsung MZNLN128HAHQ-000L2 128GB     | 1         | 2.27%   |
| Samsung Flash Drive FIT 32GB         | 1         | 2.27%   |
| NVMe INTEL SSDPEKNW51 512GB          | 1         | 2.27%   |
| Micron M600_MTFDDAV256MBF 256GB      | 1         | 2.27%   |
| Micron C400-MTFDDAK256MAM 256GB      | 1         | 2.27%   |
| Kingston SNV2S500G 500GB             | 1         | 2.27%   |
| Intel SSDSA2M080G2GC 80GB            | 1         | 2.27%   |
| Intel SSDPEKNW512G8 512GB            | 1         | 2.27%   |
| Hitachi HTS725025A9A364 250GB        | 1         | 2.27%   |
| Hitachi HTS545032B9A300 320GB        | 1         | 2.27%   |
| Dogfish SSD 2TB                      | 1         | 2.27%   |
| Crucial CT1000MX500SSD1 1TB          | 1         | 2.27%   |
| Apple SSD SM0256F 256GB              | 1         | 2.27%   |
| Apple SSD SD0128F 121GB              | 1         | 2.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 50%     |
| WDC                 | 2         | 2      | 20%     |
| Hitachi             | 2         | 2      | 20%     |
| Samsung Electronics | 1         | 2      | 10%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 7      | 26.09%  |
| Kingston            | 4         | 4      | 17.39%  |
| SanDisk             | 3         | 3      | 13.04%  |
| Micron Technology   | 2         | 2      | 8.7%    |
| Apple               | 2         | 2      | 8.7%    |
| Toshiba             | 1         | 1      | 4.35%   |
| SK hynix            | 1         | 1      | 4.35%   |
| NVMe                | 1         | 1      | 4.35%   |
| Intel               | 1         | 1      | 4.35%   |
| Dogfish             | 1         | 1      | 4.35%   |
| Crucial             | 1         | 1      | 4.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 22        | 24     | 52.38%  |
| NVMe | 10        | 10     | 23.81%  |
| HDD  | 10        | 11     | 23.81%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 31        | 35     | 75.61%  |
| NVMe | 10        | 10     | 24.39%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 25        | 28     | 78.13%  |
| 0.51-1.0   | 6         | 6      | 18.75%  |
| 1.01-2.0   | 1         | 1      | 3.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 18        | 40%     |
| 1-20       | 9         | 20%     |
| 251-500    | 6         | 13.33%  |
| 501-1000   | 5         | 11.11%  |
| 51-100     | 4         | 8.89%   |
| 21-50      | 2         | 4.44%   |
| 1001-2000  | 1         | 2.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 39        | 88.64%  |
| 21-50   | 3         | 6.82%   |
| 51-100  | 2         | 4.55%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST9640320AS 640GB                    | 1         | 1      | 11.11%  |
| Seagate ST9500420AS 500GB                    | 1         | 1      | 11.11%  |
| Seagate ST9320423AS 320GB                    | 1         | 1      | 11.11%  |
| Seagate ST750LM022 HN-M750MBB 752GB          | 1         | 1      | 11.11%  |
| Seagate ST1000LM049-2GH172 1TB               | 1         | 1      | 11.11%  |
| Samsung Electronics MZNTE128HMGR-000SO 128GB | 1         | 1      | 11.11%  |
| Kingston SV300S37A120G 120GB                 | 1         | 1      | 11.11%  |
| Intel SSDSA2M080G2GC 80GB                    | 1         | 1      | 11.11%  |
| Hitachi HTS725025A9A364 250GB                | 1         | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 55.56%  |
| Samsung Electronics | 1         | 1      | 11.11%  |
| Kingston            | 1         | 1      | 11.11%  |
| Intel               | 1         | 1      | 11.11%  |
| Hitachi             | 1         | 1      | 11.11%  |

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
| HDD  | 6         | 6      | 66.67%  |
| SSD  | 3         | 3      | 33.33%  |

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
| Works    | 32        | 35     | 76.19%  |
| Malfunc  | 9         | 9      | 21.43%  |
| Detected | 1         | 1      | 2.38%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 31        | 65.96%  |
| Samsung Electronics         | 5         | 10.64%  |
| SanDisk                     | 3         | 6.38%   |
| Phison Electronics          | 3         | 6.38%   |
| Transcend                   | 1         | 2.13%   |
| Realtek Semiconductor       | 1         | 2.13%   |
| Marvell Technology Group    | 1         | 2.13%   |
| Kingston Technology Company | 1         | 2.13%   |
| AMD                         | 1         | 2.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 5         | 9.62%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 3         | 5.77%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 3         | 5.77%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 3         | 5.77%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 3         | 5.77%   |
| Phison E18 PCIe4 NVMe Controller                                             | 2         | 3.85%   |
| Intel SSD 660P Series                                                        | 2         | 3.85%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                            | 2         | 3.85%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 2         | 3.85%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 2         | 3.85%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller               | 2         | 3.85%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 2         | 3.85%   |
| Transcend NVMe PCIe SSD 110S/112S/120S/MTE300S/MTE400S/MTE652T2 (DRAM-less)  | 1         | 1.92%   |
| Sandisk WD Black SN850X NVMe SSD                                             | 1         | 1.92%   |
| SanDisk PC SN520 x2 M.2 2230 NVMe SSD                                        | 1         | 1.92%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD         | 1         | 1.92%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                           | 1         | 1.92%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                | 1         | 1.92%   |
| Realtek RTS5763DL x2 NVMe SSD Controller                                     | 1         | 1.92%   |
| Phison E12 NVMe Controller                                                   | 1         | 1.92%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                   | 1         | 1.92%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                         | 1         | 1.92%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 1         | 1.92%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                | 1         | 1.92%   |
| Intel Comet Lake SATA AHCI Controller                                        | 1         | 1.92%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 1         | 1.92%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 1         | 1.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                | 1         | 1.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 1         | 1.92%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                   | 1         | 1.92%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                | 1         | 1.92%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                | 1         | 1.92%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 1         | 1.92%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 30        | 58.82%  |
| NVMe | 15        | 29.41%  |
| RAID | 3         | 5.88%   |
| IDE  | 3         | 5.88%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 38        | 86.36%  |
| AMD    | 6         | 13.64%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-8265U CPU @ 1.60GHz               | 2         | 4.55%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 2         | 4.55%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 2         | 4.55%   |
| Intel Core i5-4200U CPU @ 1.60GHz               | 2         | 4.55%   |
| Intel Core i5 CPU M 540 @ 2.53GHz               | 2         | 4.55%   |
| Intel 12th Gen Core i7-1260P                    | 2         | 4.55%   |
| Intel Pentium CPU 6405U @ 2.40GHz               | 1         | 2.27%   |
| Intel CPU Version                               | 1         | 2.27%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 1         | 2.27%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 1         | 2.27%   |
| Intel Core i7-6600U CPU @ 2.60GHz               | 1         | 2.27%   |
| Intel Core i7-4558U CPU @ 2.80GHz               | 1         | 2.27%   |
| Intel Core i7-2760QM CPU @ 2.40GHz              | 1         | 2.27%   |
| Intel Core i7-2630QM CPU @ 2.00GHz              | 1         | 2.27%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 1         | 2.27%   |
| Intel Core i7 CPU M 620 @ 2.67GHz               | 1         | 2.27%   |
| Intel Core i5-8365U CPU @ 1.60GHz               | 1         | 2.27%   |
| Intel Core i5-5300U CPU @ 2.30GHz               | 1         | 2.27%   |
| Intel Core i5-5200U CPU @ 2.20GHz               | 1         | 2.27%   |
| Intel Core i5-4260U CPU @ 1.40GHz               | 1         | 2.27%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 1         | 2.27%   |
| Intel Core i5-3340M CPU @ 2.70GHz               | 1         | 2.27%   |
| Intel Core i5-3230M CPU @ 2.60GHz               | 1         | 2.27%   |
| Intel Core i5-2540M CPU @ 2.60GHz               | 1         | 2.27%   |
| Intel Core i5-2410M CPU @ 2.30GHz               | 1         | 2.27%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz              | 1         | 2.27%   |
| Intel Core i5 CPU M 520 @ 2.40GHz               | 1         | 2.27%   |
| Intel Core i3-7100U CPU @ 2.40GHz               | 1         | 2.27%   |
| Intel Core i3 CPU M 350 @ 2.27GH                | 1         | 2.27%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz            | 1         | 2.27%   |
| Intel Core 2 Duo CPU P9700 @ 2.80GHz            | 1         | 2.27%   |
| Intel Celeron N4000 CPU @ 1.10GHz               | 1         | 2.27%   |
| AMD Ryzen Embedded V1500B                       | 1         | 2.27%   |
| AMD Ryzen 9 6900HX with Radeon Graphics         | 1         | 2.27%   |
| AMD Ryzen 7 7840U w/ Radeon 780M Graphics       | 1         | 2.27%   |
| AMD Ryzen 7 5700U with Radeon Graphics          | 1         | 2.27%   |
| AMD Ryzen 5 PRO 3500U w/ Radeon Vega Mobile Gfx | 1         | 2.27%   |
| AMD A4-9120C RADEON R4, 5 COMPUTE CORES 2C+3G   | 1         | 2.27%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 21        | 47.73%  |
| Intel Core i7      | 8         | 18.18%  |
| Other              | 3         | 6.82%   |
| Intel Core i3      | 2         | 4.55%   |
| Intel Core 2 Duo   | 2         | 4.55%   |
| AMD Ryzen 7        | 2         | 4.55%   |
| Intel Pentium      | 1         | 2.27%   |
| Intel Celeron      | 1         | 2.27%   |
| AMD Ryzen Embedded | 1         | 2.27%   |
| AMD Ryzen 9        | 1         | 2.27%   |
| AMD Ryzen 5 PRO    | 1         | 2.27%   |
| AMD A4             | 1         | 2.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 26        | 59.09%  |
| 4       | 8         | 18.18%  |
| 16      | 4         | 9.09%   |
| 8       | 3         | 6.82%   |
| Unknown | 2         | 4.55%   |
| 6       | 1         | 2.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 43        | 97.73%  |
| Unknown | 1         | 2.27%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 33        | 75%     |
| 1       | 9         | 20.45%  |
| Unknown | 2         | 4.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 8         | 18.18%  |
| Westmere      | 5         | 11.36%  |
| Skylake       | 5         | 11.36%  |
| Haswell       | 5         | 11.36%  |
| Unknown       | 5         | 11.36%  |
| SandyBridge   | 4         | 9.09%   |
| Penryn        | 2         | 4.55%   |
| IvyBridge     | 2         | 4.55%   |
| Broadwell     | 2         | 4.55%   |
| Zen+          | 1         | 2.27%   |
| Zen           | 1         | 2.27%   |
| IceLake       | 1         | 2.27%   |
| Goldmont plus | 1         | 2.27%   |
| Excavator     | 1         | 2.27%   |
| Core          | 1         | 2.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 37        | 74%     |
| Nvidia | 7         | 14%     |
| AMD    | 6         | 12%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                       | 5         | 9.8%    |
| Intel Haswell-ULT Integrated Graphics Controller                          | 5         | 9.8%    |
| Intel Core Processor Integrated Graphics Controller                       | 5         | 9.8%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 3         | 5.88%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 3         | 5.88%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 2         | 3.92%   |
| Intel HD Graphics 5500                                                    | 2         | 3.92%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                 | 2         | 3.92%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 2         | 3.92%   |
| Nvidia GT216M [GeForce GT 330M]                                           | 1         | 1.96%   |
| Nvidia GP108M [GeForce MX230]                                             | 1         | 1.96%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 1.96%   |
| Nvidia GM108M [GeForce 840M]                                              | 1         | 1.96%   |
| Nvidia GF108M [NVS 5400M]                                                 | 1         | 1.96%   |
| Nvidia GF106GLM [Quadro 2000M]                                            | 1         | 1.96%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                             | 1         | 1.96%   |
| Intel UHD Graphics 620                                                    | 1         | 1.96%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 1         | 1.96%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 1         | 1.96%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 1         | 1.96%   |
| Intel HD Graphics 620                                                     | 1         | 1.96%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 1         | 1.96%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 1         | 1.96%   |
| Intel Comet Lake-U GT2 [UHD Graphics 620]                                 | 1         | 1.96%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 1         | 1.96%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 1         | 1.96%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                | 1         | 1.96%   |
| AMD Rembrandt [Radeon 680M]                                               | 1         | 1.96%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 1         | 1.96%   |
| AMD Phoenix1                                                              | 1         | 1.96%   |
| AMD Lucienne                                                              | 1         | 1.96%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 28        | 63.64%  |
| Intel + Nvidia | 5         | 11.36%  |
| 1 x AMD        | 4         | 9.09%   |
| 2 x Intel      | 3         | 6.82%   |
| Other          | 1         | 2.27%   |
| 1 x Nvidia     | 1         | 2.27%   |
| Intel + AMD    | 1         | 2.27%   |
| AMD + Nvidia   | 1         | 2.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 39        | 88.64%  |
| Unknown     | 3         | 6.82%   |
| Proprietary | 2         | 4.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 39        | 88.64%  |
| 1.01-2.0   | 3         | 6.82%   |
| 0.01-0.5   | 2         | 4.55%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 8         | 24.24%  |
| LG Display              | 6         | 18.18%  |
| AU Optronics            | 4         | 12.12%  |
| Lenovo                  | 3         | 9.09%   |
| TMX                     | 1         | 3.03%   |
| Samsung Electronics     | 1         | 3.03%   |
| Panasonic               | 1         | 3.03%   |
| Lenovo Group Limited    | 1         | 3.03%   |
| InfoVision              | 1         | 3.03%   |
| Hewlett-Packard         | 1         | 3.03%   |
| Gigabyte Technology     | 1         | 3.03%   |
| Dell                    | 1         | 3.03%   |
| Chi Mei Optoelectronics | 1         | 3.03%   |
| BOE                     | 1         | 3.03%   |
| Apple                   | 1         | 3.03%   |
| Ancor Communications    | 1         | 3.03%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x170mm 13.9-inch                  | 1         | 3.03%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 300x170mm 13.6-inch     | 1         | 3.03%   |
| Panasonic LCD Monitor MEI96A2 3840x2160 380x210mm 17.1-inch              | 1         | 3.03%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch             | 1         | 3.03%   |
| LG Display LCD Monitor LGD0569 1920x1080 310x170mm 13.9-inch             | 1         | 3.03%   |
| LG Display LCD Monitor LGD04A7 1920x1080 340x190mm 15.3-inch             | 1         | 3.03%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x170mm 13.9-inch              | 1         | 3.03%   |
| LG Display LCD Monitor LGD027B 1600x900 380x210mm 17.1-inch              | 1         | 3.03%   |
| LG Display LCD Monitor LGD0213 1600x900 310x170mm 13.9-inch              | 1         | 3.03%   |
| Lenovo LCD Monitor LEN40B1 1600x900 350x190mm 15.7-inch                  | 1         | 3.03%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch                  | 1         | 3.03%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch                  | 1         | 3.03%   |
| Lenovo Group Limited LCD Monitor 1920x1080                               | 1         | 3.03%   |
| InfoVision LCD Monitor IVO04E3 1366x768 280x160mm 12.7-inch              | 1         | 3.03%   |
| Hewlett-Packard E242 HWP326E 1920x1200 520x320mm 24.0-inch               | 1         | 3.03%   |
| Gigabyte Technology M28U GBT2800 3840x2160 630x360mm 28.6-inch           | 1         | 3.03%   |
| Dell U2718Q DELA0EC 3840x2160 610x350mm 27.7-inch                        | 1         | 3.03%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 340x190mm 15.3-inch         | 1         | 3.03%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 340x190mm 15.3-inch          | 1         | 3.03%   |
| Chimei Innolux LCD Monitor CMN15B1 1920x1080 340x190mm 15.3-inch         | 1         | 3.03%   |
| Chimei Innolux LCD Monitor CMN1509 1920x1080 340x190mm 15.3-inch         | 1         | 3.03%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch         | 1         | 3.03%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 310x170mm 13.9-inch         | 1         | 3.03%   |
| Chimei Innolux LCD Monitor CMN13A2 1920x1080 290x170mm 13.2-inch         | 1         | 3.03%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch          | 1         | 3.03%   |
| Chi Mei Optoelectronics LCD Monitor CMO1593 1366x768 340x190mm 15.3-inch | 1         | 3.03%   |
| BOE NE135A1M-NY1 BOE0CB4 2880x1920 290x190mm 13.6-inch                   | 1         | 3.03%   |
| AU Optronics LCD Monitor AUO47EC 1366x768 340x190mm 15.3-inch            | 1         | 3.03%   |
| AU Optronics LCD Monitor AUO282B 3840x2160 290x170mm 13.2-inch           | 1         | 3.03%   |
| AU Optronics LCD Monitor AUO219E 1600x900 380x210mm 17.1-inch            | 1         | 3.03%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 1         | 3.03%   |
| Apple Color LCD APPA020 2560x1600 290x180mm 13.4-inch                    | 1         | 3.03%   |
| Ancor Communications VG248 ACI24A5 1920x1080 530x300mm 24.0-inch         | 1         | 3.03%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 11        | 33.33%  |
| 1366x768 (WXGA)   | 7         | 21.21%  |
| 1600x900 (HD+)    | 5         | 15.15%  |
| 3840x2160 (4K)    | 4         | 12.12%  |
| 2880x1920         | 1         | 3.03%   |
| 2560x1600         | 1         | 3.03%   |
| 2560x1440 (QHD)   | 1         | 3.03%   |
| 1920x1200 (WUXGA) | 1         | 3.03%   |
| 1440x900 (WXGA+)  | 1         | 3.03%   |
| 1280x800 (WXGA)   | 1         | 3.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 13      | 10        | 30.3%   |
| 15      | 9         | 27.27%  |
| 17      | 3         | 9.09%   |
| 12      | 3         | 9.09%   |
| 24      | 2         | 6.06%   |
| 14      | 2         | 6.06%   |
| 28      | 1         | 3.03%   |
| 27      | 1         | 3.03%   |
| 11      | 1         | 3.03%   |
| Unknown | 1         | 3.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 15        | 45.45%  |
| 201-300     | 10        | 30.3%   |
| 351-400     | 3         | 9.09%   |
| 601-700     | 2         | 6.06%   |
| 501-600     | 2         | 6.06%   |
| Unknown     | 1         | 3.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 23        | 76.67%  |
| 16/10   | 4         | 13.33%  |
| 3/2     | 2         | 6.67%   |
| Unknown | 1         | 3.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 10        | 30.3%   |
| 91-100         | 8         | 24.24%  |
| 61-70          | 3         | 9.09%   |
| 121-130        | 3         | 9.09%   |
| 71-80          | 2         | 6.06%   |
| 51-60          | 1         | 3.03%   |
| 351-500        | 1         | 3.03%   |
| 301-350        | 1         | 3.03%   |
| 251-300        | 1         | 3.03%   |
| 201-250        | 1         | 3.03%   |
| 101-110        | 1         | 3.03%   |
| Unknown        | 1         | 3.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 16        | 50%     |
| 101-120       | 7         | 21.88%  |
| More than 240 | 3         | 9.38%   |
| 161-240       | 3         | 9.38%   |
| 51-100        | 2         | 6.25%   |
| Unknown       | 1         | 3.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 33        | 73.33%  |
| 0     | 10        | 22.22%  |
| 3     | 1         | 2.22%   |
| 2     | 1         | 2.22%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 32        | 53.33%  |
| Realtek Semiconductor | 13        | 21.67%  |
| Qualcomm Atheros      | 4         | 6.67%   |
| Broadcom              | 3         | 5%      |
| Sierra Wireless       | 1         | 1.67%   |
| Ralink Technology     | 1         | 1.67%   |
| MediaTek              | 1         | 1.67%   |
| JMicron Technology    | 1         | 1.67%   |
| Google                | 1         | 1.67%   |
| Edimax Technology     | 1         | 1.67%   |
| Dell                  | 1         | 1.67%   |
| AMD                   | 1         | 1.67%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 9         | 11.25%  |
| Intel Wireless 8260                                                    | 4         | 5%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 3         | 3.75%   |
| Intel Wireless 7265                                                    | 3         | 3.75%   |
| Intel Wireless 7260                                                    | 3         | 3.75%   |
| Intel Ethernet Connection I219-LM                                      | 3         | 3.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 3         | 3.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 3.75%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 3.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2         | 2.5%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2         | 2.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 2         | 2.5%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 2         | 2.5%    |
| Intel Wi-Fi 6 AX200                                                    | 2         | 2.5%    |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 2.5%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 2         | 2.5%    |
| Intel Centrino Advanced-N 6200                                         | 2         | 2.5%    |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 2         | 2.5%    |
| Sierra Wireless EM7345 4G LTE                                          | 1         | 1.25%   |
| Realtek USB 2.5GbE Controller                                          | 1         | 1.25%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 1         | 1.25%   |
| Ralink RT5370 Wireless Adapter                                         | 1         | 1.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 1         | 1.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 1         | 1.25%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 1         | 1.25%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 1         | 1.25%   |
| Intel Wireless 8265 / 8275                                             | 1         | 1.25%   |
| Intel WiFi Link 5100                                                   | 1         | 1.25%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 1         | 1.25%   |
| Intel I211 Gigabit Network Connection                                  | 1         | 1.25%   |
| Intel Ethernet Connection I219-V                                       | 1         | 1.25%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 1.25%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 1.25%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 1.25%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 1         | 1.25%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 1         | 1.25%   |
| Intel Centrino Ultimate-N 6300                                         | 1         | 1.25%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 1         | 1.25%   |
| Intel 82567LM Gigabit Network Connection                               | 1         | 1.25%   |
| Intel 82566MM Gigabit Network Connection                               | 1         | 1.25%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 28        | 62.22%  |
| Realtek Semiconductor | 5         | 11.11%  |
| Qualcomm Atheros      | 4         | 8.89%   |
| Broadcom              | 3         | 6.67%   |
| Sierra Wireless       | 1         | 2.22%   |
| Ralink Technology     | 1         | 2.22%   |
| MediaTek              | 1         | 2.22%   |
| Edimax Technology     | 1         | 2.22%   |
| Dell                  | 1         | 2.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                            | 4         | 8.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 3         | 6.52%   |
| Intel Wireless 7265                                            | 3         | 6.52%   |
| Intel Wireless 7260                                            | 3         | 6.52%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 6.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 4.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 4.35%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 2         | 4.35%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 4.35%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 4.35%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 4.35%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 2         | 4.35%   |
| Sierra Wireless EM7345 4G LTE                                  | 1         | 2.17%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 2.17%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 2.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 2.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 2.17%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 1         | 2.17%   |
| Intel Wireless 8265 / 8275                                     | 1         | 2.17%   |
| Intel WiFi Link 5100                                           | 1         | 2.17%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 1         | 2.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 2.17%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 2.17%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 2.17%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 2.17%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 1         | 2.17%   |
| Dell Wireless 5809e Gobi 4G LTE Mobile Broadband DM Port       | 1         | 2.17%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 1         | 2.17%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 18        | 54.55%  |
| Realtek Semiconductor | 12        | 36.36%  |
| JMicron Technology    | 1         | 3.03%   |
| Broadcom              | 1         | 3.03%   |
| AMD                   | 1         | 3.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 9         | 27.27%  |
| Intel Ethernet Connection I219-LM                                      | 3         | 9.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 9.09%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 9.09%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2         | 6.06%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 6.06%   |
| Realtek USB 2.5GbE Controller                                          | 1         | 3.03%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 1         | 3.03%   |
| Intel I211 Gigabit Network Connection                                  | 1         | 3.03%   |
| Intel Ethernet Connection I219-V                                       | 1         | 3.03%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 3.03%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 3.03%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 3.03%   |
| Intel 82567LM Gigabit Network Connection                               | 1         | 3.03%   |
| Intel 82566MM Gigabit Network Connection                               | 1         | 3.03%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 1         | 3.03%   |
| AMD XGMAC 10GbE Controller                                             | 1         | 3.03%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 40        | 54.79%  |
| Ethernet | 32        | 43.84%  |
| Unknown  | 1         | 1.37%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 31        | 63.27%  |
| Ethernet | 18        | 36.73%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 25        | 56.82%  |
| 1     | 18        | 40.91%  |
| 5     | 1         | 2.27%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 42        | 95.45%  |
| Yes  | 2         | 4.55%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 16        | 53.33%  |
| Broadcom              | 3         | 10%     |
| Apple                 | 3         | 10%     |
| Realtek Semiconductor | 2         | 6.67%   |
| Hewlett-Packard       | 2         | 6.67%   |
| MediaTek              | 1         | 3.33%   |
| Lite-On Technology    | 1         | 3.33%   |
| IMC Networks          | 1         | 3.33%   |
| Dell                  | 1         | 3.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                      | 8         | 26.67%  |
| Broadcom BCM2045B (BDC-2.1)                             | 3         | 10%     |
| Realtek Bluetooth Adapter                               | 2         | 6.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 2         | 6.67%   |
| Intel AX210 Bluetooth                                   | 2         | 6.67%   |
| Intel AX200 Bluetooth                                   | 2         | 6.67%   |
| Apple Bluetooth Host Controller                         | 2         | 6.67%   |
| MediaTek Wireless_Device                                | 1         | 3.33%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth              | 1         | 3.33%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                | 1         | 3.33%   |
| Intel Wireless-AC 3168 Bluetooth                        | 1         | 3.33%   |
| IMC Networks Qualcomm Atheros AR3012 Bluetooth 4.0 + HS | 1         | 3.33%   |
| HP Broadcom 2070 Bluetooth Combo                        | 1         | 3.33%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter              | 1         | 3.33%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module             | 1         | 3.33%   |
| Apple Broadcom Built-in Bluetooth                       | 1         | 3.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 38        | 77.55%  |
| AMD                   | 6         | 12.24%  |
| Nvidia                | 3         | 6.12%   |
| Realtek Semiconductor | 1         | 2.04%   |
| Lenovo                | 1         | 2.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 7         | 11.67%  |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 8.33%   |
| Intel 8 Series HD Audio Controller                                         | 5         | 8.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 8.33%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 5         | 8.33%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 5%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 5%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 5%      |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 3.33%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 3.33%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 3.33%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 2         | 3.33%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 3.33%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 2         | 3.33%   |
| Realtek Semiconductor USB Audio                                            | 1         | 1.67%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 1.67%   |
| Nvidia GF106 High Definition Audio Controller                              | 1         | 1.67%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 1.67%   |
| Lenovo Realtek USB Audio                                                   | 1         | 1.67%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 1.67%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.67%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.67%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 1.67%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 1.67%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 1.67%   |
| AMD High Definition Audio Controller                                       | 1         | 1.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 12        | 25%     |
| SK hynix            | 10        | 20.83%  |
| Micron Technology   | 7         | 14.58%  |
| Kingston            | 4         | 8.33%   |
| Elpida              | 4         | 8.33%   |
| Unknown             | 2         | 4.17%   |
| Transcend           | 2         | 4.17%   |
| GSkill              | 2         | 4.17%   |
| Toshiba             | 1         | 2.08%   |
| Crucial             | 1         | 2.08%   |
| Corsair             | 1         | 2.08%   |
| A-DATA Technology   | 1         | 2.08%   |
| Unknown             | 1         | 2.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 2         | 3.85%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s         | 2         | 3.85%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s         | 2         | 3.85%   |
| Micron RAM 16KTF51264HZ-1G4M1 4GB SODIMM DDR3 1333MT/s        | 2         | 3.85%   |
| GSkill RAM F4-3200C22-16GRS 16GB SODIMM DDR4 3200MT/s         | 2         | 3.85%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s         | 2         | 3.85%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                   | 1         | 1.92%   |
| Unknown RAM Module 2GB SODIMM DDR3                            | 1         | 1.92%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s           | 1         | 1.92%   |
| Transcend RAM Module 2GB SODIMM DDR3 1067MT/s                 | 1         | 1.92%   |
| Toshiba RAM 8HTF12864HDY-800G1 2048MB SODIMM 800MT/s          | 1         | 1.92%   |
| Toshiba RAM 64T128020EDL2.5C2 2048MB SODIMM 800MT/s           | 1         | 1.92%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                  | 1         | 1.92%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1067MT/s                  | 1         | 1.92%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 1.92%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 1.92%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 1.92%   |
| SK hynix RAM HMT125S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s     | 1         | 1.92%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s        | 1         | 1.92%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s       | 1         | 1.92%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s         | 1         | 1.92%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s         | 1         | 1.92%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s         | 1         | 1.92%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s   | 1         | 1.92%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s         | 1         | 1.92%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s         | 1         | 1.92%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s        | 1         | 1.92%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s         | 1         | 1.92%   |
| Samsung RAM M425R1GB4BB0-CQKOD 8GB Row Of Chips DDR5 4800MT/s | 1         | 1.92%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s  | 1         | 1.92%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                 | 1         | 1.92%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s          | 1         | 1.92%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s    | 1         | 1.92%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s        | 1         | 1.92%   |
| Micron RAM 16HTF25664HY-800J1 2GB SODIMM DDR2 800MT/s         | 1         | 1.92%   |
| Kingston RAM Module 4GB SODIMM DDR4 2667MT/s                  | 1         | 1.92%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s       | 1         | 1.92%   |
| Kingston RAM KCRXJ6-MIE 16GB SODIMM DDR4 2667MT/s             | 1         | 1.92%   |
| Kingston RAM ASU1333D3S9DR8/2G 2GB SODIMM DDR3 1333MT/s       | 1         | 1.92%   |
| Kingston RAM 9905428-417.A00LF 8GB SODIMM DDR3 1600MT/s       | 1         | 1.92%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 17        | 44.74%  |
| DDR4    | 15        | 39.47%  |
| LPDDR3  | 2         | 5.26%   |
| DDR5    | 2         | 5.26%   |
| DDR2    | 1         | 2.63%   |
| Unknown | 1         | 2.63%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 35        | 87.5%   |
| Row Of Chips | 4         | 10%     |
| Chip         | 1         | 2.5%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 14        | 35%     |
| 8192  | 12        | 30%     |
| 2048  | 7         | 17.5%   |
| 16384 | 6         | 15%     |
| 32768 | 1         | 2.5%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 10        | 23.81%  |
| 2667    | 8         | 19.05%  |
| 3200    | 5         | 11.9%   |
| 1334    | 4         | 9.52%   |
| 1333    | 4         | 9.52%   |
| 2400    | 2         | 4.76%   |
| 2133    | 2         | 4.76%   |
| 800     | 2         | 4.76%   |
| 5600    | 1         | 2.38%   |
| 4800    | 1         | 2.38%   |
| 1067    | 1         | 2.38%   |
| 1066    | 1         | 2.38%   |
| Unknown | 1         | 2.38%   |

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
| Chicony Electronics           | 9         | 28.13%  |
| Bison Electronics             | 5         | 15.63%  |
| Microdia                      | 4         | 12.5%   |
| IMC Networks                  | 3         | 9.38%   |
| Syntek                        | 2         | 6.25%   |
| Realtek Semiconductor         | 2         | 6.25%   |
| Lenovo                        | 2         | 6.25%   |
| Suyin                         | 1         | 3.13%   |
| Sunplus Innovation Technology | 1         | 3.13%   |
| Quanta                        | 1         | 3.13%   |
| Logitech                      | 1         | 3.13%   |
| Framework                     | 1         | 3.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Bison Integrated Camera                  | 4         | 12.5%   |
| Microdia USB  Live camera                | 2         | 6.25%   |
| Microdia Integrated Webcam               | 2         | 6.25%   |
| Lenovo Integrated Webcam                 | 2         | 6.25%   |
| Syntek Integrated Camera                 | 1         | 3.13%   |
| Syntek EasyCamera                        | 1         | 3.13%   |
| Suyin Asus Integrated Webcam             | 1         | 3.13%   |
| Sunplus Laptop Integrated Webcam HD      | 1         | 3.13%   |
| Realtek Integrated_Webcam_HD             | 1         | 3.13%   |
| Realtek Front Camera                     | 1         | 3.13%   |
| Quanta VGA WebCam                        | 1         | 3.13%   |
| Logitech Webcam C270                     | 1         | 3.13%   |
| IMC Networks Integrated RGB Camera       | 1         | 3.13%   |
| IMC Networks HP TrueVision HD Camera     | 1         | 3.13%   |
| IMC Networks EasyCamera                  | 1         | 3.13%   |
| Framework Laptop Webcam Module (2nd Gen) | 1         | 3.13%   |
| Chicony USB2.0 HD UVC WebCam             | 1         | 3.13%   |
| Chicony USB 2.0 VGA UVC WebCam           | 1         | 3.13%   |
| Chicony TOSHIBA Web Camera - FHD         | 1         | 3.13%   |
| Chicony ThinkPad T490 Webcam             | 1         | 3.13%   |
| Chicony Realtek DMFT RGB                 | 1         | 3.13%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 1         | 3.13%   |
| Chicony Integrated HP HD Webcam          | 1         | 3.13%   |
| Chicony Integrated Camera                | 1         | 3.13%   |
| Chicony Camera                           | 1         | 3.13%   |
| Bison ThinkPad P50 Integrated Camera     | 1         | 3.13%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 23.08%  |
| Upek                       | 3         | 23.08%  |
| Broadcom                   | 2         | 15.38%  |
| AuthenTec                  | 2         | 15.38%  |
| Synaptics                  | 1         | 7.69%   |
| Shenzhen Goodix Technology | 1         | 7.69%   |
| Elan Microelectronics      | 1         | 7.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 3         | 23.08%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 15.38%  |
| Validity Sensors VFS471 Fingerprint Reader                                   | 1         | 7.69%   |
| Validity Sensors VFS451 Fingerprint Reader                                   | 1         | 7.69%   |
| Validity Sensors VFS Fingerprint sensor                                      | 1         | 7.69%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 1         | 7.69%   |
| Shenzhen Goodix Fingerprint Reader                                           | 1         | 7.69%   |
| Elan Fingerprint Sensor                                                      | 1         | 7.69%   |
| AuthenTec AES2810                                                            | 1         | 7.69%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 1         | 7.69%   |

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
| 2     | 21        | 46.67%  |
| 1     | 13        | 28.89%  |
| 3     | 6         | 13.33%  |
| 0     | 3         | 6.67%   |
| 5     | 1         | 2.22%   |
| 4     | 1         | 2.22%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 35        | 47.3%   |
| Fingerprint reader       | 10        | 13.51%  |
| Card reader              | 7         | 9.46%   |
| Bluetooth                | 6         | 8.11%   |
| Net/wireless             | 5         | 6.76%   |
| Firewire controller      | 5         | 6.76%   |
| Network                  | 2         | 2.7%    |
| Graphics card            | 2         | 2.7%    |
| Storage/ata              | 1         | 1.35%   |
| Sound                    | 1         | 1.35%   |

