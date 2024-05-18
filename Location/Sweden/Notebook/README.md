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

Total: 47

| Vendor    | Model                       | Probe                                                     | Date         |
|-----------|-----------------------------|-----------------------------------------------------------|--------------|
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
| helloSystem 0.5.0    | 4         | 10%     |
| OpenBSD 7.0          | 3         | 7.5%    |
| helloSystem 0.8.0    | 3         | 7.5%    |
| OpenBSD 6.9          | 2         | 5%      |
| helloSystem 0.7.0    | 2         | 5%      |
| helloSystem 0.4.0    | 2         | 5%      |
| FreeBSD 13.1-p5      | 2         | 5%      |
| FreeBSD 12.1-p8      | 2         | 5%      |
| OPNsense 22.10       | 1         | 2.5%    |
| OPNsense 21.1        | 1         | 2.5%    |
| OpenBSD 7.2          | 1         | 2.5%    |
| OpenBSD 6.8          | 1         | 2.5%    |
| OpenBSD 6.7          | 1         | 2.5%    |
| NomadBSD 20221130    | 1         | 2.5%    |
| helloSystem 0.9.0    | 1         | 2.5%    |
| helloSystem 0.8.1    | 1         | 2.5%    |
| GhostBSD 22.08.27    | 1         | 2.5%    |
| GhostBSD 21.08.27    | 1         | 2.5%    |
| GhostBSD 20.04.02    | 1         | 2.5%    |
| FreeBSD 14.0-p6      | 1         | 2.5%    |
| FreeBSD 14.0-p2      | 1         | 2.5%    |
| FreeBSD 14.0-CURRENT | 1         | 2.5%    |
| FreeBSD 14.0         | 1         | 2.5%    |
| FreeBSD 13.2-p4      | 1         | 2.5%    |
| FreeBSD 13.1-p7      | 1         | 2.5%    |
| FreeBSD 13.0-p7      | 1         | 2.5%    |
| FreeBSD 13.0-p10     | 1         | 2.5%    |
| FreeBSD 13.0         | 1         | 2.5%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| helloSystem | 13        | 33.33%  |
| FreeBSD     | 13        | 33.33%  |
| OpenBSD     | 7         | 17.95%  |
| GhostBSD    | 3         | 7.69%   |
| OPNsense    | 2         | 5.13%   |
| NomadBSD    | 1         | 2.56%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 39        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 14        | 35%     |
| fvwm         | 6         | 15%     |
| Console      | 5         | 12.5%   |
| KDE5         | 4         | 10%     |
| MATE         | 3         | 7.5%    |
| i3           | 2         | 5%      |
| GNOME        | 2         | 5%      |
| XFCE         | 1         | 2.5%    |
| Openbox      | 1         | 2.5%    |
| Mutter       | 1         | 2.5%    |
| LXQt         | 1         | 2.5%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 33        | 84.62%  |
| Console | 6         | 15.38%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 14        | 35.9%   |
| Console | 13        | 33.33%  |
| LightDM | 6         | 15.38%  |
| SDDM    | 3         | 7.69%   |
| GDM     | 2         | 5.13%   |
| XDM     | 1         | 2.56%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 12        | 30.77%  |
| Unknown | 11        | 28.21%  |
| C       | 10        | 25.64%  |
| sv_SE   | 2         | 5.13%   |
| sv      | 1         | 2.56%   |
| en_GB   | 1         | 2.56%   |
| en_BE   | 1         | 2.56%   |
| en      | 1         | 2.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 33        | 82.5%   |
| BIOS | 7         | 17.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 23        | 58.97%  |
| Ffs    | 7         | 17.95%  |
| Cd9660 | 5         | 12.82%  |
| Ufs    | 4         | 10.26%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 36        | 87.8%   |
| MBR  | 5         | 12.2%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 15        | 38.46%  |
| Hewlett-Packard  | 5         | 12.82%  |
| Dell             | 5         | 12.82%  |
| ASUSTek Computer | 3         | 7.69%   |
| Toshiba          | 2         | 5.13%   |
| Star Labs        | 2         | 5.13%   |
| Apple            | 2         | 5.13%   |
| Sony             | 1         | 2.56%   |
| Razer            | 1         | 2.56%   |
| Google           | 1         | 2.56%   |
| Deciso           | 1         | 2.56%   |
| Acer             | 1         | 2.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Star Labs StarBook                     | 2         | 5.13%   |
| Toshiba TECRA Z40-C-12Z                | 1         | 2.56%   |
| Toshiba Satellite L450                 | 1         | 2.56%   |
| Sony SVP1322M1EBI                      | 1         | 2.56%   |
| Razer Blade 14 (2022) - RZ09-0427      | 1         | 2.56%   |
| Lenovo V130-15IGM 81HL                 | 1         | 2.56%   |
| Lenovo ThinkPad X395 20NL001SMX        | 1         | 2.56%   |
| Lenovo ThinkPad X250 20CLS4JH00        | 1         | 2.56%   |
| Lenovo ThinkPad X201 3680FAG           | 1         | 2.56%   |
| Lenovo ThinkPad W520 4284GN2           | 1         | 2.56%   |
| Lenovo ThinkPad T530 23942U1           | 1         | 2.56%   |
| Lenovo ThinkPad T480 20L6SDA400        | 1         | 2.56%   |
| Lenovo ThinkPad T470s W10DG 20JTS0W800 | 1         | 2.56%   |
| Lenovo ThinkPad T460s 20FAS4KH02       | 1         | 2.56%   |
| Lenovo ThinkPad T420 4236MBG           | 1         | 2.56%   |
| Lenovo ThinkPad T400 2767WSB           | 1         | 2.56%   |
| Lenovo ThinkPad L560 20F10032MS        | 1         | 2.56%   |
| Lenovo Legion Y530-15ICH 81FV          | 1         | 2.56%   |
| Lenovo IdeaPad L340-17IWL 81M0         | 1         | 2.56%   |
| Lenovo IdeaPad 3 14IML05 81WA          | 1         | 2.56%   |
| HP ProBook 4730s                       | 1         | 2.56%   |
| HP Pavilion Laptop 14-bf0xx            | 1         | 2.56%   |
| HP Laptop 15-dw0xxx                    | 1         | 2.56%   |
| HP EliteBook 8440p                     | 1         | 2.56%   |
| Google Grunt                           | 1         | 2.56%   |
| Dell XPS 13 7390                       | 1         | 2.56%   |
| Dell Latitude E7250                    | 1         | 2.56%   |
| Dell Latitude E7240                    | 1         | 2.56%   |
| Dell Latitude E5530 non-vPro           | 1         | 2.56%   |
| Dell Latitude 5500                     | 1         | 2.56%   |
| Deciso NetBoard-A10                    | 1         | 2.56%   |
| ASUS UX305UA                           | 1         | 2.56%   |
| ASUS S551LN                            | 1         | 2.56%   |
| ASUS K52Jc                             | 1         | 2.56%   |
| Apple MacBookPro6,2                    | 1         | 2.56%   |
| Apple MacBookAir6,1                    | 1         | 2.56%   |
| Acer Aspire A315-56                    | 1         | 2.56%   |
| Unknown                                | 1         | 2.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 11        | 28.21%  |
| Dell Latitude       | 4         | 10.26%  |
| Star Labs StarBook  | 2         | 5.13%   |
| Lenovo IdeaPad      | 2         | 5.13%   |
| Toshiba TECRA       | 1         | 2.56%   |
| Toshiba Satellite   | 1         | 2.56%   |
| Sony SVP1322M1EBI   | 1         | 2.56%   |
| Razer Blade         | 1         | 2.56%   |
| Lenovo V130-15IGM   | 1         | 2.56%   |
| Lenovo Legion       | 1         | 2.56%   |
| HP ProBook          | 1         | 2.56%   |
| HP Pavilion         | 1         | 2.56%   |
| HP Laptop           | 1         | 2.56%   |
| HP EliteBook        | 1         | 2.56%   |
| Google Grunt        | 1         | 2.56%   |
| Dell XPS            | 1         | 2.56%   |
| Deciso NetBoard-A10 | 1         | 2.56%   |
| ASUS UX305UA        | 1         | 2.56%   |
| ASUS S551LN         | 1         | 2.56%   |
| ASUS K52Jc          | 1         | 2.56%   |
| Apple MacBookPro6   | 1         | 2.56%   |
| Apple MacBookAir6   | 1         | 2.56%   |
| Acer Aspire         | 1         | 2.56%   |
| Unknown             | 1         | 2.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 6         | 15.38%  |
| 2023 | 3         | 7.69%   |
| 2022 | 3         | 7.69%   |
| 2021 | 3         | 7.69%   |
| 2019 | 3         | 7.69%   |
| 2018 | 3         | 7.69%   |
| 2017 | 3         | 7.69%   |
| 2014 | 3         | 7.69%   |
| 2009 | 3         | 7.69%   |
| 2016 | 2         | 5.13%   |
| 2015 | 2         | 5.13%   |
| 2010 | 2         | 5.13%   |
| 2013 | 1         | 2.56%   |
| 2012 | 1         | 2.56%   |
| 2011 | 1         | 2.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 39        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 35        | 89.74%  |
| Yes  | 4         | 10.26%  |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 15        | 38.46%  |
| 4.01-8.0   | 11        | 28.21%  |
| 16.01-24.0 | 7         | 17.95%  |
| 32.01-64.0 | 4         | 10.26%  |
| 3.01-4.0   | 1         | 2.56%   |
| 24.01-32.0 | 1         | 2.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 24        | 61.54%  |
| 0.51-1.0 | 9         | 23.08%  |
| 1.01-2.0 | 5         | 12.82%  |
| 2.01-3.0 | 1         | 2.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 30        | 76.92%  |
| 2      | 6         | 15.38%  |
| 0      | 2         | 5.13%   |
| 3      | 1         | 2.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 29        | 74.36%  |
| Yes       | 10        | 25.64%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 74.36%  |
| No        | 10        | 25.64%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 92.31%  |
| No        | 3         | 7.69%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 62.5%   |
| No        | 15        | 37.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Sweden  | 39        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Stockholm      | 6         | 14.63%  |
| Malmo          | 4         | 9.76%   |
| Henan          | 3         | 7.32%   |
| VÃ¤sterÃ¥s | 2         | 4.88%   |
| Varekil        | 1         | 2.44%   |
| Vallingby      | 1         | 2.44%   |
| Trosa          | 1         | 2.44%   |
| Staffanstorp   | 1         | 2.44%   |
| Solna          | 1         | 2.44%   |
| Sollentuna     | 1         | 2.44%   |
| Sollebrunn     | 1         | 2.44%   |
| Södertälje   | 1         | 2.44%   |
| SkellefteÃ¥  | 1         | 2.44%   |
| OEvertornea    | 1         | 2.44%   |
| OEverlida      | 1         | 2.44%   |
| LuleÃ¥       | 1         | 2.44%   |
| Lidkoeping     | 1         | 2.44%   |
| Kungsbacka     | 1         | 2.44%   |
| Klagshamn      | 1         | 2.44%   |
| Hultsfred      | 1         | 2.44%   |
| Hoeviksnaes    | 1         | 2.44%   |
| Hoerby         | 1         | 2.44%   |
| GГ¤vle       | 1         | 2.44%   |
| Gothenburg     | 1         | 2.44%   |
| Falkenberg     | 1         | 2.44%   |
| Faergelanda    | 1         | 2.44%   |
| Eskilstuna     | 1         | 2.44%   |
| Enebyberg      | 1         | 2.44%   |
| Borensberg     | 1         | 2.44%   |
| Bastad         | 1         | 2.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 12     | 25%     |
| Seagate             | 5         | 5      | 12.5%   |
| WDC                 | 4         | 4      | 10%     |
| Kingston            | 4         | 4      | 10%     |
| SanDisk             | 3         | 3      | 7.5%    |
| Micron Technology   | 2         | 2      | 5%      |
| Intel               | 2         | 2      | 5%      |
| Transcend           | 1         | 1      | 2.5%    |
| Toshiba             | 1         | 1      | 2.5%    |
| Star Drive          | 1         | 1      | 2.5%    |
| SK hynix            | 1         | 1      | 2.5%    |
| NVMe                | 1         | 1      | 2.5%    |
| Hitachi             | 1         | 1      | 2.5%    |
| Dogfish             | 1         | 1      | 2.5%    |
| Crucial             | 1         | 1      | 2.5%    |
| Apple               | 1         | 1      | 2.5%    |
| A-DATA Technology   | 1         | 1      | 2.5%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 250GB            | 2         | 4.88%   |
| Kingston SA400S37120G 120GB          | 2         | 4.88%   |
| WDC WD6400BPVT-60HXZT1 640GB         | 1         | 2.44%   |
| WDC WD3200BEKT-08PVMT1 320GB         | 1         | 2.44%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 1         | 2.44%   |
| WDC PC SN520 NVMe 256GB              | 1         | 2.44%   |
| Transcend TS256GMTE652T2 256GB       | 1         | 2.44%   |
| Toshiba KSG60ZMV256G 256GB           | 1         | 2.44%   |
| Star Drive PCIe SSD 960GB            | 1         | 2.44%   |
| SK hynix HFS128G32TNF-N3A0A 128GB    | 1         | 2.44%   |
| Seagate ST9640320AS 640GB            | 1         | 2.44%   |
| Seagate ST9500420AS 500GB            | 1         | 2.44%   |
| Seagate ST9320423AS 320GB            | 1         | 2.44%   |
| Seagate ST750LM022 HN-M750MBB 752GB  | 1         | 2.44%   |
| Seagate ST1000LM049-2GH172 1TB       | 1         | 2.44%   |
| SanDisk SDSSDHP256G 256GB            | 1         | 2.44%   |
| SanDisk SD8TN8U256G1001 256GB        | 1         | 2.44%   |
| SanDisk SD8SN8U-256G-1006 256GB      | 1         | 2.44%   |
| Samsung SSD PM851 mSATA 256GB        | 1         | 2.44%   |
| Samsung SSD PM830 2.5-inch 7mm 128GB | 1         | 2.44%   |
| Samsung SSD 860 PRO 256GB            | 1         | 2.44%   |
| Samsung PM981a NVMe 512GB            | 1         | 2.44%   |
| Samsung PM981 NVMe 256GB             | 1         | 2.44%   |
| Samsung MZVLW256HEHP-000L7 256GB     | 1         | 2.44%   |
| Samsung MZNTE128HMGR-000SO 128GB     | 1         | 2.44%   |
| Samsung MZNLN128HAHQ-000L2 128GB     | 1         | 2.44%   |
| Samsung Flash Drive FIT 32GB         | 1         | 2.44%   |
| NVMe INTEL SSDPEKNW51 512GB          | 1         | 2.44%   |
| Micron M600_MTFDDAV256MBF 256GB      | 1         | 2.44%   |
| Micron C400-MTFDDAK256MAM 256GB      | 1         | 2.44%   |
| Kingston SV300S37A120G 120GB         | 1         | 2.44%   |
| Kingston SNV2S500G 500GB             | 1         | 2.44%   |
| Intel SSDSA2M080G2GC 80GB            | 1         | 2.44%   |
| Intel SSDPEKNW512G8 512GB            | 1         | 2.44%   |
| Hitachi HTS725025A9A364 250GB        | 1         | 2.44%   |
| Dogfish SSD 2TB                      | 1         | 2.44%   |
| Crucial CT1000MX500SSD1 1TB          | 1         | 2.44%   |
| Apple SSD SD0128F 121GB              | 1         | 2.44%   |
| A-DATA SX6000NP 128GB                | 1         | 2.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 55.56%  |
| WDC                 | 2         | 2      | 22.22%  |
| Samsung Electronics | 1         | 2      | 11.11%  |
| Hitachi             | 1         | 1      | 11.11%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 7      | 28.57%  |
| SanDisk             | 3         | 3      | 14.29%  |
| Kingston            | 3         | 3      | 14.29%  |
| Micron Technology   | 2         | 2      | 9.52%   |
| Toshiba             | 1         | 1      | 4.76%   |
| SK hynix            | 1         | 1      | 4.76%   |
| NVMe                | 1         | 1      | 4.76%   |
| Intel               | 1         | 1      | 4.76%   |
| Dogfish             | 1         | 1      | 4.76%   |
| Crucial             | 1         | 1      | 4.76%   |
| Apple               | 1         | 1      | 4.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 20        | 22     | 51.28%  |
| NVMe | 10        | 10     | 25.64%  |
| HDD  | 9         | 10     | 23.08%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 28        | 32     | 73.68%  |
| NVMe | 10        | 10     | 26.32%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 22        | 25     | 75.86%  |
| 0.51-1.0   | 6         | 6      | 20.69%  |
| 1.01-2.0   | 1         | 1      | 3.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 17        | 42.5%   |
| 1-20       | 9         | 22.5%   |
| 501-1000   | 5         | 12.5%   |
| 251-500    | 4         | 10%     |
| 51-100     | 3         | 7.5%    |
| 21-50      | 2         | 5%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 34        | 87.18%  |
| 21-50   | 3         | 7.69%   |
| 51-100  | 2         | 5.13%   |

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
| Works    | 29        | 32     | 74.36%  |
| Malfunc  | 9         | 9      | 23.08%  |
| Detected | 1         | 1      | 2.56%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 29        | 70.73%  |
| Samsung Electronics         | 3         | 7.32%   |
| Phison Electronics          | 3         | 7.32%   |
| SanDisk                     | 2         | 4.88%   |
| Transcend                   | 1         | 2.44%   |
| Realtek Semiconductor       | 1         | 2.44%   |
| Marvell Technology Group    | 1         | 2.44%   |
| Kingston Technology Company | 1         | 2.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 5         | 10.87%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 3         | 6.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 3         | 6.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 2         | 4.35%   |
| Phison E18 PCIe4 NVMe Controller                                             | 2         | 4.35%   |
| Intel SSD 660P Series                                                        | 2         | 4.35%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                            | 2         | 4.35%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 2         | 4.35%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 2         | 4.35%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 2         | 4.35%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 2         | 4.35%   |
| Transcend NVMe PCIe SSD 110S/112S/120S/MTE300S/MTE400S/MTE652T2 (DRAM-less)  | 1         | 2.17%   |
| SanDisk PC SN520 x2 M.2 2230 NVMe SSD                                        | 1         | 2.17%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD         | 1         | 2.17%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                | 1         | 2.17%   |
| Realtek RTS5763DL x2 NVMe SSD Controller                                     | 1         | 2.17%   |
| Phison E12 NVMe Controller                                                   | 1         | 2.17%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                   | 1         | 2.17%   |
| Kingston Company NV2 NVMe SSD SM2267XT (DRAM-less)                           | 1         | 2.17%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 1         | 2.17%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                | 1         | 2.17%   |
| Intel Comet Lake SATA AHCI Controller                                        | 1         | 2.17%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 1         | 2.17%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 1         | 2.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                | 1         | 2.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 1         | 2.17%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                   | 1         | 2.17%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller               | 1         | 2.17%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                | 1         | 2.17%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                | 1         | 2.17%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 26        | 57.78%  |
| NVMe | 13        | 28.89%  |
| RAID | 3         | 6.67%   |
| IDE  | 3         | 6.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 35        | 89.74%  |
| AMD    | 4         | 10.26%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-8265U CPU @ 1.60GHz               | 2         | 5.13%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 2         | 5.13%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 2         | 5.13%   |
| Intel Core i5-4200U CPU @ 1.60GHz               | 2         | 5.13%   |
| Intel Core i5 CPU M 540 @ 2.53GHz               | 2         | 5.13%   |
| Intel 12th Gen Core i7-1260P                    | 2         | 5.13%   |
| Intel Pentium CPU 6405U @ 2.40GHz               | 1         | 2.56%   |
| Intel CPU Version                               | 1         | 2.56%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 1         | 2.56%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 1         | 2.56%   |
| Intel Core i7-6600U CPU @ 2.60GHz               | 1         | 2.56%   |
| Intel Core i7-2760QM CPU @ 2.40GHz              | 1         | 2.56%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 1         | 2.56%   |
| Intel Core i7 CPU M 620 @ 2.67GHz               | 1         | 2.56%   |
| Intel Core i5-8365U CPU @ 1.60GHz               | 1         | 2.56%   |
| Intel Core i5-5300U CPU @ 2.30GHz               | 1         | 2.56%   |
| Intel Core i5-5200U CPU @ 2.20GHz               | 1         | 2.56%   |
| Intel Core i5-4260U CPU @ 1.40GHz               | 1         | 2.56%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 1         | 2.56%   |
| Intel Core i5-3340M CPU @ 2.70GHz               | 1         | 2.56%   |
| Intel Core i5-3230M CPU @ 2.60GHz               | 1         | 2.56%   |
| Intel Core i5-2540M CPU @ 2.60GHz               | 1         | 2.56%   |
| Intel Core i5-2410M CPU @ 2.30GHz               | 1         | 2.56%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz              | 1         | 2.56%   |
| Intel Core i3-7100U CPU @ 2.40GHz               | 1         | 2.56%   |
| Intel Core i3 CPU M 350 @ 2.27GH                | 1         | 2.56%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz            | 1         | 2.56%   |
| Intel Core 2 Duo CPU P9700 @ 2.80GHz            | 1         | 2.56%   |
| Intel Celeron N4000 CPU @ 1.10GHz               | 1         | 2.56%   |
| AMD Ryzen Embedded V1500B                       | 1         | 2.56%   |
| AMD Ryzen 9 6900HX with Radeon Graphics         | 1         | 2.56%   |
| AMD Ryzen 5 PRO 3500U w/ Radeon Vega Mobile Gfx | 1         | 2.56%   |
| AMD A4-9120C RADEON R4, 5 COMPUTE CORES 2C+3G   | 1         | 2.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 20        | 51.28%  |
| Intel Core i7      | 6         | 15.38%  |
| Other              | 3         | 7.69%   |
| Intel Core i3      | 2         | 5.13%   |
| Intel Core 2 Duo   | 2         | 5.13%   |
| Intel Pentium      | 1         | 2.56%   |
| Intel Celeron      | 1         | 2.56%   |
| AMD Ryzen Embedded | 1         | 2.56%   |
| AMD Ryzen 9        | 1         | 2.56%   |
| AMD Ryzen 5 PRO    | 1         | 2.56%   |
| AMD A4             | 1         | 2.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 24        | 61.54%  |
| 4       | 7         | 17.95%  |
| 16      | 3         | 7.69%   |
| 8       | 2         | 5.13%   |
| Unknown | 2         | 5.13%   |
| 6       | 1         | 2.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 38        | 97.44%  |
| Unknown | 1         | 2.56%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 29        | 74.36%  |
| 1       | 8         | 20.51%  |
| Unknown | 2         | 5.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 8         | 20.51%  |
| Skylake       | 5         | 12.82%  |
| Westmere      | 4         | 10.26%  |
| Haswell       | 4         | 10.26%  |
| SandyBridge   | 3         | 7.69%   |
| Unknown       | 3         | 7.69%   |
| Penryn        | 2         | 5.13%   |
| IvyBridge     | 2         | 5.13%   |
| Broadwell     | 2         | 5.13%   |
| Zen+          | 1         | 2.56%   |
| Zen           | 1         | 2.56%   |
| IceLake       | 1         | 2.56%   |
| Goldmont plus | 1         | 2.56%   |
| Excavator     | 1         | 2.56%   |
| Core          | 1         | 2.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 34        | 75.56%  |
| Nvidia | 7         | 15.56%  |
| AMD    | 4         | 8.89%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                       | 5         | 10.87%  |
| Intel Haswell-ULT Integrated Graphics Controller                          | 4         | 8.7%    |
| Intel Core Processor Integrated Graphics Controller                       | 4         | 8.7%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 3         | 6.52%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 2         | 4.35%   |
| Intel HD Graphics 5500                                                    | 2         | 4.35%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                 | 2         | 4.35%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 2         | 4.35%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2         | 4.35%   |
| Nvidia GT216M [GeForce GT 330M]                                           | 1         | 2.17%   |
| Nvidia GP108M [GeForce MX230]                                             | 1         | 2.17%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 2.17%   |
| Nvidia GM108M [GeForce 840M]                                              | 1         | 2.17%   |
| Nvidia GF108M [NVS 5400M]                                                 | 1         | 2.17%   |
| Nvidia GF106GLM [Quadro 2000M]                                            | 1         | 2.17%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                             | 1         | 2.17%   |
| Intel UHD Graphics 620                                                    | 1         | 2.17%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 1         | 2.17%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 1         | 2.17%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 1         | 2.17%   |
| Intel HD Graphics 620                                                     | 1         | 2.17%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 1         | 2.17%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 1         | 2.17%   |
| Intel Comet Lake-U GT2 [UHD Graphics 620]                                 | 1         | 2.17%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 1         | 2.17%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 1         | 2.17%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                | 1         | 2.17%   |
| AMD Rembrandt [Radeon 680M]                                               | 1         | 2.17%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 1         | 2.17%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 25        | 64.1%   |
| Intel + Nvidia | 5         | 12.82%  |
| 2 x Intel      | 3         | 7.69%   |
| 1 x AMD        | 2         | 5.13%   |
| Other          | 1         | 2.56%   |
| 1 x Nvidia     | 1         | 2.56%   |
| Intel + AMD    | 1         | 2.56%   |
| AMD + Nvidia   | 1         | 2.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 34        | 87.18%  |
| Unknown     | 3         | 7.69%   |
| Proprietary | 2         | 5.13%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 36        | 92.31%  |
| 1.01-2.0   | 2         | 5.13%   |
| 0.01-0.5   | 1         | 2.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 7         | 24.14%  |
| LG Display              | 6         | 20.69%  |
| AU Optronics            | 4         | 13.79%  |
| Lenovo                  | 2         | 6.9%    |
| TMX                     | 1         | 3.45%   |
| Samsung Electronics     | 1         | 3.45%   |
| Panasonic               | 1         | 3.45%   |
| Lenovo Group Limited    | 1         | 3.45%   |
| InfoVision              | 1         | 3.45%   |
| Hewlett-Packard         | 1         | 3.45%   |
| Gigabyte Technology     | 1         | 3.45%   |
| Dell                    | 1         | 3.45%   |
| Chi Mei Optoelectronics | 1         | 3.45%   |
| Ancor Communications    | 1         | 3.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x170mm 13.9-inch                  | 1         | 3.45%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 300x170mm 13.6-inch     | 1         | 3.45%   |
| Panasonic LCD Monitor MEI96A2 3840x2160 380x210mm 17.1-inch              | 1         | 3.45%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch             | 1         | 3.45%   |
| LG Display LCD Monitor LGD0569 1920x1080 310x170mm 13.9-inch             | 1         | 3.45%   |
| LG Display LCD Monitor LGD04A7 1920x1080 340x190mm 15.3-inch             | 1         | 3.45%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x170mm 13.9-inch              | 1         | 3.45%   |
| LG Display LCD Monitor LGD027B 1600x900 380x210mm 17.1-inch              | 1         | 3.45%   |
| LG Display LCD Monitor LGD0213 1600x900 310x170mm 13.9-inch              | 1         | 3.45%   |
| Lenovo LCD Monitor LEN40B1 1600x900 350x190mm 15.7-inch                  | 1         | 3.45%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch                  | 1         | 3.45%   |
| Lenovo Group Limited LCD Monitor 1920x1080                               | 1         | 3.45%   |
| InfoVision LCD Monitor IVO04E3 1366x768 280x160mm 12.7-inch              | 1         | 3.45%   |
| Hewlett-Packard E242 HWP326E 1920x1200 520x320mm 24.0-inch               | 1         | 3.45%   |
| Gigabyte Technology M28U GBT2800 3840x2160 630x360mm 28.6-inch           | 1         | 3.45%   |
| Dell U2718Q DELA0EC 3840x2160 610x350mm 27.7-inch                        | 1         | 3.45%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 340x190mm 15.3-inch         | 1         | 3.45%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 340x190mm 15.3-inch          | 1         | 3.45%   |
| Chimei Innolux LCD Monitor CMN15B1 1920x1080 340x190mm 15.3-inch         | 1         | 3.45%   |
| Chimei Innolux LCD Monitor CMN1509 1920x1080 340x190mm 15.3-inch         | 1         | 3.45%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch         | 1         | 3.45%   |
| Chimei Innolux LCD Monitor CMN13A2 1920x1080 290x170mm 13.2-inch         | 1         | 3.45%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch          | 1         | 3.45%   |
| Chi Mei Optoelectronics LCD Monitor CMO1593 1366x768 340x190mm 15.3-inch | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO47EC 1366x768 340x190mm 15.3-inch            | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO282B 3840x2160 290x170mm 13.2-inch           | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO219E 1600x900 380x210mm 17.1-inch            | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 1         | 3.45%   |
| Ancor Communications VG248 ACI24A5 1920x1080 530x300mm 24.0-inch         | 1         | 3.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 10        | 34.48%  |
| 1366x768 (WXGA)   | 7         | 24.14%  |
| 1600x900 (HD+)    | 5         | 17.24%  |
| 3840x2160 (4K)    | 4         | 13.79%  |
| 2560x1440 (QHD)   | 1         | 3.45%   |
| 1920x1200 (WUXGA) | 1         | 3.45%   |
| 1440x900 (WXGA+)  | 1         | 3.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 9         | 31.03%  |
| 13      | 7         | 24.14%  |
| 17      | 3         | 10.34%  |
| 24      | 2         | 6.9%    |
| 14      | 2         | 6.9%    |
| 12      | 2         | 6.9%    |
| 28      | 1         | 3.45%   |
| 27      | 1         | 3.45%   |
| 11      | 1         | 3.45%   |
| Unknown | 1         | 3.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 14        | 48.28%  |
| 201-300     | 7         | 24.14%  |
| 351-400     | 3         | 10.34%  |
| 601-700     | 2         | 6.9%    |
| 501-600     | 2         | 6.9%    |
| Unknown     | 1         | 3.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 22        | 84.62%  |
| 16/10   | 3         | 11.54%  |
| Unknown | 1         | 3.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 8         | 27.59%  |
| 81-90          | 7         | 24.14%  |
| 121-130        | 3         | 10.34%  |
| 71-80          | 2         | 6.9%    |
| 61-70          | 2         | 6.9%    |
| 51-60          | 1         | 3.45%   |
| 351-500        | 1         | 3.45%   |
| 301-350        | 1         | 3.45%   |
| 251-300        | 1         | 3.45%   |
| 201-250        | 1         | 3.45%   |
| 101-110        | 1         | 3.45%   |
| Unknown        | 1         | 3.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 14        | 50%     |
| 101-120       | 7         | 25%     |
| More than 240 | 2         | 7.14%   |
| 161-240       | 2         | 7.14%   |
| 51-100        | 2         | 7.14%   |
| Unknown       | 1         | 3.57%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 29        | 72.5%   |
| 0     | 9         | 22.5%   |
| 3     | 1         | 2.5%    |
| 2     | 1         | 2.5%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 30        | 55.56%  |
| Realtek Semiconductor | 11        | 20.37%  |
| Qualcomm Atheros      | 4         | 7.41%   |
| Broadcom              | 2         | 3.7%    |
| Sierra Wireless       | 1         | 1.85%   |
| Ralink Technology     | 1         | 1.85%   |
| JMicron Technology    | 1         | 1.85%   |
| Google                | 1         | 1.85%   |
| Edimax Technology     | 1         | 1.85%   |
| Dell                  | 1         | 1.85%   |
| AMD                   | 1         | 1.85%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller           | 9         | 12.33%  |
| Intel Wireless 8260                                                              | 4         | 5.48%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                              | 3         | 4.11%   |
| Intel Wireless 7265                                                              | 3         | 4.11%   |
| Intel Wireless 7260                                                              | 3         | 4.11%   |
| Intel Ethernet Connection I219-LM                                                | 3         | 4.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                     | 3         | 4.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                            | 3         | 4.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                         | 2         | 2.74%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                   | 2         | 2.74%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                        | 2         | 2.74%   |
| Intel Wi-Fi 6 AX200                                                              | 2         | 2.74%   |
| Intel Ethernet Connection (3) I218-LM                                            | 2         | 2.74%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                  | 2         | 2.74%   |
| Intel Centrino Advanced-N 6200                                                   | 2         | 2.74%   |
| Intel 82577LM Gigabit Network Connection                                         | 2         | 2.74%   |
| Sierra Wireless EM7345 4G LTE                                                    | 1         | 1.37%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                           | 1         | 1.37%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                            | 1         | 1.37%   |
| Ralink RT5370 Wireless Adapter                                                   | 1         | 1.37%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                       | 1         | 1.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                 | 1         | 1.37%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                           | 1         | 1.37%   |
| Intel WiFi Link 5100                                                             | 1         | 1.37%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                          | 1         | 1.37%   |
| Intel I211 Gigabit Network Connection                                            | 1         | 1.37%   |
| Intel Ethernet Connection I219-V                                                 | 1         | 1.37%   |
| Intel Ethernet Connection I218-LM                                                | 1         | 1.37%   |
| Intel Ethernet Connection (6) I219-LM                                            | 1         | 1.37%   |
| Intel Ethernet Connection (4) I219-V                                             | 1         | 1.37%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                 | 1         | 1.37%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                | 1         | 1.37%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                         | 1         | 1.37%   |
| Intel 82567LM Gigabit Network Connection                                         | 1         | 1.37%   |
| Intel 82566MM Gigabit Network Connection                                         | 1         | 1.37%   |
| Google Pixel 7 CDC Network Control Model (NCM) CDC Network Data CDC Network Data | 1         | 1.37%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                   | 1         | 1.37%   |
| Dell Wireless 5809e Gobi 4G LTE Mobile Broadband DM Port                         | 1         | 1.37%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                                | 1         | 1.37%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                     | 1         | 1.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 26        | 63.41%  |
| Realtek Semiconductor | 5         | 12.2%   |
| Qualcomm Atheros      | 4         | 9.76%   |
| Broadcom              | 2         | 4.88%   |
| Sierra Wireless       | 1         | 2.44%   |
| Ralink Technology     | 1         | 2.44%   |
| Edimax Technology     | 1         | 2.44%   |
| Dell                  | 1         | 2.44%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                            | 4         | 9.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 3         | 7.14%   |
| Intel Wireless 7265                                            | 3         | 7.14%   |
| Intel Wireless 7260                                            | 3         | 7.14%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 7.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 4.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 4.76%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 2         | 4.76%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 4.76%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 4.76%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 4.76%   |
| Sierra Wireless EM7345 4G LTE                                  | 1         | 2.38%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 2.38%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 2.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 2.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 2.38%   |
| Intel WiFi Link 5100                                           | 1         | 2.38%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 1         | 2.38%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 2.38%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 2.38%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 2.38%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 1         | 2.38%   |
| Dell Wireless 5809e Gobi 4G LTE Mobile Broadband DM Port       | 1         | 2.38%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 1         | 2.38%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 1         | 2.38%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 17        | 56.67%  |
| Realtek Semiconductor | 10        | 33.33%  |
| JMicron Technology    | 1         | 3.33%   |
| Broadcom              | 1         | 3.33%   |
| AMD                   | 1         | 3.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 9         | 30%     |
| Intel Ethernet Connection I219-LM                                      | 3         | 10%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 10%     |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 6.67%   |
| Intel 82577LM Gigabit Network Connection                               | 2         | 6.67%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1         | 3.33%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 1         | 3.33%   |
| Intel I211 Gigabit Network Connection                                  | 1         | 3.33%   |
| Intel Ethernet Connection I219-V                                       | 1         | 3.33%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 3.33%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 3.33%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 3.33%   |
| Intel 82567LM Gigabit Network Connection                               | 1         | 3.33%   |
| Intel 82566MM Gigabit Network Connection                               | 1         | 3.33%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 1         | 3.33%   |
| AMD XGMAC 10GbE Controller                                             | 1         | 3.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 36        | 54.55%  |
| Ethernet | 29        | 43.94%  |
| Unknown  | 1         | 1.52%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 28        | 62.22%  |
| Ethernet | 17        | 37.78%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 24        | 61.54%  |
| 1     | 14        | 35.9%   |
| 5     | 1         | 2.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 38        | 97.44%  |
| Yes  | 1         | 2.56%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 15        | 57.69%  |
| Realtek Semiconductor | 2         | 7.69%   |
| Hewlett-Packard       | 2         | 7.69%   |
| Broadcom              | 2         | 7.69%   |
| Apple                 | 2         | 7.69%   |
| Lite-On Technology    | 1         | 3.85%   |
| IMC Networks          | 1         | 3.85%   |
| Dell                  | 1         | 3.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                      | 7         | 26.92%  |
| Realtek Bluetooth Adapter                               | 2         | 7.69%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 2         | 7.69%   |
| Intel AX210 Bluetooth                                   | 2         | 7.69%   |
| Intel AX200 Bluetooth                                   | 2         | 7.69%   |
| Broadcom BCM2045B (BDC-2.1)                             | 2         | 7.69%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth              | 1         | 3.85%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                | 1         | 3.85%   |
| Intel Wireless-AC 3168 Bluetooth                        | 1         | 3.85%   |
| IMC Networks Qualcomm Atheros AR3012 Bluetooth 4.0 + HS | 1         | 3.85%   |
| HP Broadcom 2070 Bluetooth Combo                        | 1         | 3.85%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter              | 1         | 3.85%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module             | 1         | 3.85%   |
| Apple Broadcom Built-in Bluetooth                       | 1         | 3.85%   |
| Apple Bluetooth Host Controller                         | 1         | 3.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 35        | 79.55%  |
| AMD                   | 4         | 9.09%   |
| Nvidia                | 3         | 6.82%   |
| Realtek Semiconductor | 1         | 2.27%   |
| Lenovo                | 1         | 2.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 7         | 13.46%  |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 7.69%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 7.69%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 7.69%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 5.77%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 5.77%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3         | 5.77%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 3.85%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 3.85%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 3.85%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 2         | 3.85%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 3.85%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2         | 3.85%   |
| Realtek Semiconductor USB Audio                                            | 1         | 1.92%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 1.92%   |
| Nvidia GF106 High Definition Audio Controller                              | 1         | 1.92%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 1.92%   |
| Lenovo Realtek USB Audio                                                   | 1         | 1.92%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 1.92%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.92%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.92%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 1.92%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 1         | 1.92%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 1.92%   |
| AMD High Definition Audio Controller                                       | 1         | 1.92%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 12        | 28.57%  |
| SK hynix            | 9         | 21.43%  |
| Micron Technology   | 5         | 11.9%   |
| Kingston            | 4         | 9.52%   |
| Unknown             | 2         | 4.76%   |
| Transcend           | 2         | 4.76%   |
| GSkill              | 2         | 4.76%   |
| Elpida              | 2         | 4.76%   |
| Toshiba             | 1         | 2.38%   |
| Crucial             | 1         | 2.38%   |
| Corsair             | 1         | 2.38%   |
| Unknown             | 1         | 2.38%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 2         | 4.35%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s         | 2         | 4.35%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s         | 2         | 4.35%   |
| Micron RAM 16KTF51264HZ-1G4M1 4GB SODIMM DDR3 1333MT/s        | 2         | 4.35%   |
| GSkill RAM F4-3200C22-16GRS 16GB SODIMM DDR4 3200MT/s         | 2         | 4.35%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                   | 1         | 2.17%   |
| Unknown RAM Module 2GB SODIMM DDR3                            | 1         | 2.17%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s           | 1         | 2.17%   |
| Transcend RAM Module 2GB SODIMM DDR3 1067MT/s                 | 1         | 2.17%   |
| Toshiba RAM 8HTF12864HDY-800G1 2048MB SODIMM 800MT/s          | 1         | 2.17%   |
| Toshiba RAM 64T128020EDL2.5C2 2048MB SODIMM 800MT/s           | 1         | 2.17%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1067MT/s                  | 1         | 2.17%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 2.17%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 2.17%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 2.17%   |
| SK hynix RAM HMT125S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s     | 1         | 2.17%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s        | 1         | 2.17%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s       | 1         | 2.17%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s         | 1         | 2.17%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s         | 1         | 2.17%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s         | 1         | 2.17%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s   | 1         | 2.17%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s         | 1         | 2.17%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s         | 1         | 2.17%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s        | 1         | 2.17%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s         | 1         | 2.17%   |
| Samsung RAM M425R1GB4BB0-CQKOD 8GB Row Of Chips DDR5 4800MT/s | 1         | 2.17%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s  | 1         | 2.17%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                 | 1         | 2.17%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s          | 1         | 2.17%   |
| Micron RAM 16HTF25664HY-800J1 2GB SODIMM DDR2 800MT/s         | 1         | 2.17%   |
| Kingston RAM Module 4GB SODIMM DDR4 2667MT/s                  | 1         | 2.17%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s       | 1         | 2.17%   |
| Kingston RAM KCRXJ6-MIE 16GB SODIMM DDR4 2667MT/s             | 1         | 2.17%   |
| Kingston RAM ASU1333D3S9DR8/2G 2GB SODIMM DDR3 1333MT/s       | 1         | 2.17%   |
| Kingston RAM 9905428-417.A00LF 8GB SODIMM DDR3 1600MT/s       | 1         | 2.17%   |
| Elpida RAM Module 4GB SODIMM LPDDR3 1600MT/s                  | 1         | 2.17%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s         | 1         | 2.17%   |
| Crucial RAM CT16G4SFD8266.C16FD1 16GB SODIMM DDR4 2666MT/s    | 1         | 2.17%   |
| Corsair RAM CMSO8GX3M1A1333C9 8GB SODIMM DDR3 1333MT/s        | 1         | 2.17%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 14        | 42.42%  |
| DDR3    | 14        | 42.42%  |
| LPDDR3  | 2         | 6.06%   |
| DDR5    | 1         | 3.03%   |
| DDR2    | 1         | 3.03%   |
| Unknown | 1         | 3.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 31        | 88.57%  |
| Row Of Chips | 3         | 8.57%   |
| Chip         | 1         | 2.86%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 12        | 34.29%  |
| 8192  | 11        | 31.43%  |
| 16384 | 6         | 17.14%  |
| 2048  | 6         | 17.14%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 9         | 25%     |
| 2667    | 7         | 19.44%  |
| 3200    | 4         | 11.11%  |
| 1333    | 4         | 11.11%  |
| 2400    | 2         | 5.56%   |
| 2133    | 2         | 5.56%   |
| 1334    | 2         | 5.56%   |
| 800     | 2         | 5.56%   |
| 4800    | 1         | 2.78%   |
| 2666    | 1         | 2.78%   |
| 1067    | 1         | 2.78%   |
| Unknown | 1         | 2.78%   |

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
| Chicony Electronics           | 9         | 31.03%  |
| Bison Electronics             | 5         | 17.24%  |
| Microdia                      | 4         | 13.79%  |
| IMC Networks                  | 3         | 10.34%  |
| Realtek Semiconductor         | 2         | 6.9%    |
| Syntek                        | 1         | 3.45%   |
| Suyin                         | 1         | 3.45%   |
| Sunplus Innovation Technology | 1         | 3.45%   |
| Quanta                        | 1         | 3.45%   |
| Logitech                      | 1         | 3.45%   |
| Lenovo                        | 1         | 3.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Bison Integrated Camera                  | 4         | 13.79%  |
| Microdia USB 2.0 Camera                  | 2         | 6.9%    |
| Microdia Integrated Webcam               | 2         | 6.9%    |
| Syntek EasyCamera                        | 1         | 3.45%   |
| Suyin Asus Integrated Webcam             | 1         | 3.45%   |
| Sunplus Laptop Integrated Webcam HD      | 1         | 3.45%   |
| Realtek Integrated_Webcam_HD             | 1         | 3.45%   |
| Realtek Front Camera                     | 1         | 3.45%   |
| Quanta VGA WebCam                        | 1         | 3.45%   |
| Logitech Webcam C270                     | 1         | 3.45%   |
| Lenovo Integrated Webcam                 | 1         | 3.45%   |
| IMC Networks Integrated RGB Camera       | 1         | 3.45%   |
| IMC Networks HP TrueVision HD Camera     | 1         | 3.45%   |
| IMC Networks EasyCamera                  | 1         | 3.45%   |
| Chicony USB2.0 HD UVC WebCam             | 1         | 3.45%   |
| Chicony USB 2.0 VGA UVC WebCam           | 1         | 3.45%   |
| Chicony TOSHIBA Web Camera - FHD         | 1         | 3.45%   |
| Chicony ThinkPad T490 Webcam             | 1         | 3.45%   |
| Chicony Realtek DMFT RGB                 | 1         | 3.45%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 1         | 3.45%   |
| Chicony Integrated HP HD Webcam          | 1         | 3.45%   |
| Chicony Integrated Camera                | 1         | 3.45%   |
| Chicony Camera                           | 1         | 3.45%   |
| Bison ThinkPad P50 Integrated Camera     | 1         | 3.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 27.27%  |
| Upek                       | 2         | 18.18%  |
| Broadcom                   | 2         | 18.18%  |
| AuthenTec                  | 2         | 18.18%  |
| Synaptics                  | 1         | 9.09%   |
| Shenzhen Goodix Technology | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 2         | 18.18%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 18.18%  |
| Validity Sensors VFS471 Fingerprint Reader                                   | 1         | 9.09%   |
| Validity Sensors VFS451 Fingerprint Reader                                   | 1         | 9.09%   |
| Validity Sensors VFS Fingerprint sensor                                      | 1         | 9.09%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 1         | 9.09%   |
| Shenzhen Goodix Fingerprint Reader                                           | 1         | 9.09%   |
| AuthenTec AES2810                                                            | 1         | 9.09%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 1         | 9.09%   |

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
| 2     | 19        | 47.5%   |
| 1     | 10        | 25%     |
| 3     | 6         | 15%     |
| 0     | 3         | 7.5%    |
| 5     | 1         | 2.5%    |
| 4     | 1         | 2.5%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 32        | 47.76%  |
| Fingerprint reader       | 8         | 11.94%  |
| Card reader              | 7         | 10.45%  |
| Firewire controller      | 5         | 7.46%   |
| Bluetooth                | 5         | 7.46%   |
| Net/wireless             | 4         | 5.97%   |
| Network                  | 2         | 2.99%   |
| Graphics card            | 2         | 2.99%   |
| Storage/ata              | 1         | 1.49%   |
| Sound                    | 1         | 1.49%   |

