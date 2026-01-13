BSD in Austria - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for BSD in Austria.

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

Total: 66

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Deciso        | NetBoard-A20                | [06217f37f3](https://bsd-hardware.info/?probe=06217f37f3) | Dec 22, 2025 |
| Lenovo        | ThinkPad T420 4236PGG       | [a29d54028d](https://bsd-hardware.info/?probe=a29d54028d) | Sep 12, 2025 |
| Deciso        | NetBoard-A20                | [29c55af4bd](https://bsd-hardware.info/?probe=29c55af4bd) | Aug 13, 2025 |
| Apple         | MacBookPro9,2               | [99124c137a](https://bsd-hardware.info/?probe=99124c137a) | Aug 04, 2025 |
| Lenovo        | ThinkPad T430 2347H76       | [84bb1f6dc9](https://bsd-hardware.info/?probe=84bb1f6dc9) | Aug 02, 2025 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [afc0b4763b](https://bsd-hardware.info/?probe=afc0b4763b) | Jul 12, 2025 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [353a524eb8](https://bsd-hardware.info/?probe=353a524eb8) | Jul 10, 2025 |
| Lenovo        | ThinkPad T430 2347H76       | [74c977c0d0](https://bsd-hardware.info/?probe=74c977c0d0) | Jul 06, 2025 |
| Deciso        | DEC2700 - OPNsense Appli... | [df09b5c1ba](https://bsd-hardware.info/?probe=df09b5c1ba) | Jun 22, 2025 |
| Deciso        | NetBoard-A10 Gen.3          | [023b220776](https://bsd-hardware.info/?probe=023b220776) | Jun 21, 2025 |
| Lenovo        | ThinkPad T440p 20AWS4FB0... | [e04c5c639b](https://bsd-hardware.info/?probe=e04c5c639b) | Jun 09, 2025 |
| Unknown       | Unknown                     | [125098edef](https://bsd-hardware.info/?probe=125098edef) | Jun 01, 2025 |
| Deciso        | NetBoard-A20                | [c25601af23](https://bsd-hardware.info/?probe=c25601af23) | May 01, 2025 |
| Unknown       | Unknown                     | [1d7ea0d455](https://bsd-hardware.info/?probe=1d7ea0d455) | Jan 02, 2025 |
| Lenovo        | ThinkPad T490 20N3S61A13    | [150320a6b1](https://bsd-hardware.info/?probe=150320a6b1) | Dec 15, 2024 |
| Shuttle       | DS57U                       | [32c044d7d9](https://bsd-hardware.info/?probe=32c044d7d9) | Nov 10, 2024 |
| Unknown       | Unknown                     | [ac12463cc2](https://bsd-hardware.info/?probe=ac12463cc2) | Apr 08, 2024 |
| Unknown       | Unknown                     | [8854b07e12](https://bsd-hardware.info/?probe=8854b07e12) | Nov 15, 2023 |
| Shuttle       | DS437                       | [45c2e3460c](https://bsd-hardware.info/?probe=45c2e3460c) | Oct 30, 2023 |
| Deciso        | NetBoard-A10                | [12b5a57360](https://bsd-hardware.info/?probe=12b5a57360) | Oct 10, 2023 |
| Deciso        | DEC2700 - OPNsense Appli... | [aedd3a8255](https://bsd-hardware.info/?probe=aedd3a8255) | Jun 28, 2023 |
| Lenovo        | ThinkPad T480 20L6S2S800    | [722403df31](https://bsd-hardware.info/?probe=722403df31) | Jun 15, 2023 |
| HP            | ProBook 640 G4              | [7b44e1591f](https://bsd-hardware.info/?probe=7b44e1591f) | Apr 29, 2023 |
| Shuttle       | DS437                       | [284decb573](https://bsd-hardware.info/?probe=284decb573) | Apr 25, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [278a2a11cd](https://bsd-hardware.info/?probe=278a2a11cd) | Mar 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [ef85735453](https://bsd-hardware.info/?probe=ef85735453) | Mar 09, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [0f4dd9a9bc](https://bsd-hardware.info/?probe=0f4dd9a9bc) | Feb 15, 2023 |
| Lenovo        | ThinkPad X220 4291WF5       | [24544f4a94](https://bsd-hardware.info/?probe=24544f4a94) | Jan 24, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [78327c664e](https://bsd-hardware.info/?probe=78327c664e) | Jan 16, 2023 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | [247370372d](https://bsd-hardware.info/?probe=247370372d) | Jan 15, 2023 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | [683591700f](https://bsd-hardware.info/?probe=683591700f) | Dec 19, 2022 |
| Intel         | H81U                        | [fab3eecc66](https://bsd-hardware.info/?probe=fab3eecc66) | Dec 15, 2022 |
| Intel         | H81U                        | [fe1c3cb754](https://bsd-hardware.info/?probe=fe1c3cb754) | Dec 14, 2022 |
| Deciso        | NetBoard-A10                | [aefb2f4660](https://bsd-hardware.info/?probe=aefb2f4660) | Aug 24, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | [f603e648c7](https://bsd-hardware.info/?probe=f603e648c7) | Aug 01, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | [f573327012](https://bsd-hardware.info/?probe=f573327012) | Jun 29, 2022 |
| Fujitsu       | LIFEBOOK A555               | [23d96bc669](https://bsd-hardware.info/?probe=23d96bc669) | Jun 11, 2022 |
| BESSTAR Te... | U820                        | [6f2aa2d02a](https://bsd-hardware.info/?probe=6f2aa2d02a) | May 07, 2022 |
| Lenovo        | ThinkPad T410 2537WEE       | [973ade9e4a](https://bsd-hardware.info/?probe=973ade9e4a) | Mar 07, 2022 |
| Lenovo        | ThinkPad T510 4384AJ6       | [70a56029e7](https://bsd-hardware.info/?probe=70a56029e7) | Jan 31, 2022 |
| Lenovo        | Y50-70 20378                | [1feb455e8c](https://bsd-hardware.info/?probe=1feb455e8c) | Jan 25, 2022 |
| Dell          | Precision 7530              | [498bfe852c](https://bsd-hardware.info/?probe=498bfe852c) | Jan 07, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [6c208c85a5](https://bsd-hardware.info/?probe=6c208c85a5) | Jan 06, 2022 |
| Unknown       | Unknown                     | [db4d12babd](https://bsd-hardware.info/?probe=db4d12babd) | Dec 23, 2021 |
| HP            | EliteBook Folio 9470m       | [b872e9b044](https://bsd-hardware.info/?probe=b872e9b044) | Dec 18, 2021 |
| Unknown       | Unknown                     | [eab0d6c6d3](https://bsd-hardware.info/?probe=eab0d6c6d3) | Dec 12, 2021 |
| Unknown       | Unknown                     | [6d1fb7b4bb](https://bsd-hardware.info/?probe=6d1fb7b4bb) | Nov 27, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [087d40ba7c](https://bsd-hardware.info/?probe=087d40ba7c) | Oct 19, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [bf9b083102](https://bsd-hardware.info/?probe=bf9b083102) | Sep 08, 2021 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [62f9376847](https://bsd-hardware.info/?probe=62f9376847) | Sep 04, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [5147f5734d](https://bsd-hardware.info/?probe=5147f5734d) | Sep 04, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [2e8b641cc4](https://bsd-hardware.info/?probe=2e8b641cc4) | Sep 04, 2021 |
| HP            | EliteBook Folio 9470m       | [e1837571df](https://bsd-hardware.info/?probe=e1837571df) | Apr 15, 2021 |
| HP            | EliteBook Folio 9470m       | [57de8a523c](https://bsd-hardware.info/?probe=57de8a523c) | Mar 29, 2021 |
| Panasonic     | CF-30KTP48NL                | [119b4875e9](https://bsd-hardware.info/?probe=119b4875e9) | Mar 12, 2021 |
| Dell          | Vostro V131                 | [897616d9c8](https://bsd-hardware.info/?probe=897616d9c8) | Jan 31, 2021 |
| Dell          | Vostro V131                 | [630822a6a1](https://bsd-hardware.info/?probe=630822a6a1) | Jan 25, 2021 |
| HP            | ZBook 17 G4                 | [40ad0612de](https://bsd-hardware.info/?probe=40ad0612de) | Jan 02, 2021 |
| Lenovo        | ThinkPad T410 2537AT1       | [4e693bfcb2](https://bsd-hardware.info/?probe=4e693bfcb2) | Oct 29, 2020 |
| Dell          | Latitude E7440              | [acd2735dc4](https://bsd-hardware.info/?probe=acd2735dc4) | Aug 07, 2020 |
| HP            | EliteBook 840 G3            | [71c35a9cc2](https://bsd-hardware.info/?probe=71c35a9cc2) | Aug 06, 2020 |
| HP            | EliteBook 840 G3            | [6c7374d0ab](https://bsd-hardware.info/?probe=6c7374d0ab) | May 29, 2020 |
| Lenovo        | ThinkPad T60 2007J3G        | [ee60eb3dc8](https://bsd-hardware.info/?probe=ee60eb3dc8) | May 25, 2020 |
| Dell          | XPS 13 9360                 | [152f5cda4c](https://bsd-hardware.info/?probe=152f5cda4c) | May 23, 2020 |
| Dell          | XPS 13 9360                 | [d350b44569](https://bsd-hardware.info/?probe=d350b44569) | May 23, 2020 |
| Dell          | XPS 13 9360                 | [4199e37b56](https://bsd-hardware.info/?probe=4199e37b56) | May 23, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| FreeBSD 13.1           | 4         | 7.27%   |
| FreeBSD 13.1-p5        | 3         | 5.45%   |
| OPNsense 21.7.7        | 2         | 3.64%   |
| GhostBSD 25.01-R14.2p3 | 2         | 3.64%   |
| FreeBSD 14.2           | 2         | 3.64%   |
| FreeBSD 14.0-CURRENT   | 2         | 3.64%   |
| FreeBSD 13.0-p4        | 2         | 3.64%   |
| FreeBSD 12.1-p8        | 2         | 3.64%   |
| FreeBSD 12.1-p5        | 2         | 3.64%   |
| OPNsense 25.4.2        | 1         | 1.82%   |
| OPNsense 25.4.1        | 1         | 1.82%   |
| OPNsense 25.4          | 1         | 1.82%   |
| OPNsense 25.10.1       | 1         | 1.82%   |
| OPNsense 25.1.9        | 1         | 1.82%   |
| OPNsense 25.1.7        | 1         | 1.82%   |
| OPNsense 24.7.8        | 1         | 1.82%   |
| OPNsense 24.7.11       | 1         | 1.82%   |
| OPNsense 24.1.5        | 1         | 1.82%   |
| OPNsense 23.7.8        | 1         | 1.82%   |
| OPNsense 23.7.7        | 1         | 1.82%   |
| OPNsense 23.7.5        | 1         | 1.82%   |
| OPNsense 23.1.6        | 1         | 1.82%   |
| OPNsense 23.1.10       | 1         | 1.82%   |
| OPNsense 22.7.9        | 1         | 1.82%   |
| OPNsense 22.4.3        | 1         | 1.82%   |
| OPNsense 22.1.6        | 1         | 1.82%   |
| OPNsense 22.1.2        | 1         | 1.82%   |
| OPNsense 21.7.6        | 1         | 1.82%   |
| OpenBSD 6.8            | 1         | 1.82%   |
| NomadBSD 20240711      | 1         | 1.82%   |
| helloSystem 0.9.0      | 1         | 1.82%   |
| helloSystem 0.8.2      | 1         | 1.82%   |
| helloSystem 0.7.0      | 1         | 1.82%   |
| helloSystem 0.5.0      | 1         | 1.82%   |
| GhostBSD 25.02-R14.3p2 | 1         | 1.82%   |
| FreeBSD 13.2           | 1         | 1.82%   |
| FreeBSD 13.0-CURRENT   | 1         | 1.82%   |
| FreeBSD 13.0           | 1         | 1.82%   |
| FreeBSD 12.3           | 1         | 1.82%   |
| FreeBSD 12.2-p5        | 1         | 1.82%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 23        | 52.27%  |
| OPNsense    | 12        | 27.27%  |
| helloSystem | 4         | 9.09%   |
| GhostBSD    | 3         | 6.82%   |
| OpenBSD     | 1         | 2.27%   |
| NomadBSD    | 1         | 2.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 43        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Console      | 13        | 29.55%  |
| KDE5         | 8         | 18.18%  |
| XFCE         | 6         | 13.64%  |
| MATE         | 5         | 11.36%  |
| helloDesktop | 4         | 9.09%   |
| Cinnamon     | 3         | 6.82%   |
| i3           | 2         | 4.55%   |
| LXQt         | 1         | 2.27%   |
| GNOME        | 1         | 2.27%   |
| fvwm         | 1         | 2.27%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 29        | 65.91%  |
| Console | 14        | 31.82%  |
| Wayland | 1         | 2.27%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 19        | 42.22%  |
| SDDM    | 13        | 28.89%  |
| SLiM    | 6         | 13.33%  |
| LightDM | 5         | 11.11%  |
| XDM     | 1         | 2.22%   |
| GDM     | 1         | 2.22%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 17        | 36.96%  |
| C       | 13        | 28.26%  |
| en_US   | 8         | 17.39%  |
| de_DE   | 4         | 8.7%    |
| de_AT   | 2         | 4.35%   |
| cs_CZ   | 2         | 4.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 39        | 88.64%  |
| BIOS | 5         | 11.36%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Zfs  | 30        | 66.67%  |
| Ufs  | 14        | 31.11%  |
| Ffs  | 1         | 2.22%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 40        | 90.91%  |
| MBR     | 3         | 6.82%   |
| Unknown | 1         | 2.27%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Lenovo          | 19        | 44.19%  |
| Hewlett-Packard | 6         | 13.95%  |
| Dell            | 4         | 9.3%    |
| Deciso          | 4         | 9.3%    |
| Shuttle         | 2         | 4.65%   |
| Unknown         | 2         | 4.65%   |
| TUXEDO          | 1         | 2.33%   |
| Panasonic       | 1         | 2.33%   |
| Intel           | 1         | 2.33%   |
| Fujitsu         | 1         | 2.33%   |
| BESSTAR Tech    | 1         | 2.33%   |
| Apple           | 1         | 2.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Lenovo ThinkPad T490 20N2CTO1WW          | 2         | 4.65%   |
| HP EliteBook 850 G7 Notebook PC          | 2         | 4.65%   |
| Unknown                                  | 2         | 4.65%   |
| TUXEDO InfinityBook Pro 14 Gen6          | 1         | 2.33%   |
| Shuttle DS57U                            | 1         | 2.33%   |
| Shuttle DS437                            | 1         | 2.33%   |
| Panasonic CF-30KTP48NL                   | 1         | 2.33%   |
| Lenovo Y50-70 20378                      | 1         | 2.33%   |
| Lenovo ThinkPad X220 4291WF5             | 1         | 2.33%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BS006DGE | 1         | 2.33%   |
| Lenovo ThinkPad T60 2007J3G              | 1         | 2.33%   |
| Lenovo ThinkPad T510 4384AJ6             | 1         | 2.33%   |
| Lenovo ThinkPad T490 20N3S61A13          | 1         | 2.33%   |
| Lenovo ThinkPad T480 20L6S2S800          | 1         | 2.33%   |
| Lenovo ThinkPad T440p 20AWS4FB00         | 1         | 2.33%   |
| Lenovo ThinkPad T430 2347H76             | 1         | 2.33%   |
| Lenovo ThinkPad T420 4236PGG             | 1         | 2.33%   |
| Lenovo ThinkPad T410 2537WEE             | 1         | 2.33%   |
| Lenovo ThinkPad T410 2537AT1             | 1         | 2.33%   |
| Lenovo ThinkPad E15 Gen 3 20YG006GGE     | 1         | 2.33%   |
| Lenovo ThinkPad E14 Gen 3 20Y7003SGE     | 1         | 2.33%   |
| Lenovo ThinkPad A485 20MVS0LG00          | 1         | 2.33%   |
| Lenovo IdeaPad 5 14ALC05 82LM            | 1         | 2.33%   |
| Lenovo IdeaPad 110S-11IBR 80WG           | 1         | 2.33%   |
| Intel H81U                               | 1         | 2.33%   |
| HP ZBook 17 G4                           | 1         | 2.33%   |
| HP ProBook 640 G4                        | 1         | 2.33%   |
| HP EliteBook Folio 9470m                 | 1         | 2.33%   |
| HP EliteBook 840 G3                      | 1         | 2.33%   |
| Fujitsu LIFEBOOK A555                    | 1         | 2.33%   |
| Dell XPS 13 9360                         | 1         | 2.33%   |
| Dell Vostro V131                         | 1         | 2.33%   |
| Dell Precision 7530                      | 1         | 2.33%   |
| Dell Latitude E7440                      | 1         | 2.33%   |
| Deciso NetBoard-A20                      | 1         | 2.33%   |
| Deciso NetBoard-A10 Gen.3                | 1         | 2.33%   |
| Deciso NetBoard-A10                      | 1         | 2.33%   |
| Deciso DEC2700 - OPNsense Appliance      | 1         | 2.33%   |
| BESSTAR Tech U820                        | 1         | 2.33%   |
| Apple MacBookPro9,2                      | 1         | 2.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 16        | 37.21%  |
| HP EliteBook           | 4         | 9.3%    |
| Lenovo IdeaPad         | 2         | 4.65%   |
| Deciso NetBoard-A10    | 2         | 4.65%   |
| Unknown                | 2         | 4.65%   |
| TUXEDO InfinityBook    | 1         | 2.33%   |
| Shuttle DS57U          | 1         | 2.33%   |
| Shuttle DS437          | 1         | 2.33%   |
| Panasonic CF-30KTP48NL | 1         | 2.33%   |
| Lenovo Y50-70          | 1         | 2.33%   |
| Intel H81U             | 1         | 2.33%   |
| HP ZBook               | 1         | 2.33%   |
| HP ProBook             | 1         | 2.33%   |
| Fujitsu LIFEBOOK       | 1         | 2.33%   |
| Dell XPS               | 1         | 2.33%   |
| Dell Vostro            | 1         | 2.33%   |
| Dell Precision         | 1         | 2.33%   |
| Dell Latitude          | 1         | 2.33%   |
| Deciso NetBoard-A20    | 1         | 2.33%   |
| Deciso DEC2700         | 1         | 2.33%   |
| BESSTAR Tech U820      | 1         | 2.33%   |
| Apple MacBookPro9      | 1         | 2.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 7         | 16.28%  |
| 2019 | 6         | 13.95%  |
| 2018 | 5         | 11.63%  |
| 2022 | 4         | 9.3%    |
| 2015 | 4         | 9.3%    |
| 2013 | 3         | 6.98%   |
| 2011 | 3         | 6.98%   |
| 2010 | 3         | 6.98%   |
| 2016 | 2         | 4.65%   |
| 2025 | 1         | 2.33%   |
| 2020 | 1         | 2.33%   |
| 2017 | 1         | 2.33%   |
| 2014 | 1         | 2.33%   |
| 2009 | 1         | 2.33%   |
| 2006 | 1         | 2.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 43        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 43        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 17        | 39.53%  |
| 16.01-24.0  | 13        | 30.23%  |
| 32.01-64.0  | 5         | 11.63%  |
| 4.01-8.0    | 2         | 4.65%   |
| 3.01-4.0    | 2         | 4.65%   |
| 2.01-3.0    | 2         | 4.65%   |
| 64.01-256.0 | 2         | 4.65%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 18        | 41.86%  |
| 1.01-2.0 | 12        | 27.91%  |
| 0.51-1.0 | 11        | 25.58%  |
| 2.01-3.0 | 2         | 4.65%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 31        | 68.89%  |
| 0      | 8         | 17.78%  |
| 2      | 4         | 8.89%   |
| 3      | 2         | 4.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 40        | 93.02%  |
| Yes       | 3         | 6.98%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 83.72%  |
| No        | 7         | 16.28%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 37        | 86.05%  |
| No        | 6         | 13.95%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 27        | 61.36%  |
| No        | 17        | 38.64%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Austria | 43        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Vienna                  | 30        | 62.5%   |
| Graz                    | 3         | 6.25%   |
| Wels                    | 1         | 2.08%   |
| Weidlingbach            | 1         | 2.08%   |
| Vorchdorf               | 1         | 2.08%   |
| Schörfling             | 1         | 2.08%   |
| Pirching am Traubenberg | 1         | 2.08%   |
| Parndorf                | 1         | 2.08%   |
| Neulengbach             | 1         | 2.08%   |
| Mattersburg             | 1         | 2.08%   |
| Maria Enzersdorf        | 1         | 2.08%   |
| Linz                    | 1         | 2.08%   |
| Innsbruck               | 1         | 2.08%   |
| Grosspertholz           | 1         | 2.08%   |
| Grossgmain              | 1         | 2.08%   |
| Deutschlandsberg        | 1         | 2.08%   |
| Bruck an der Mur        | 1         | 2.08%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 19     | 35.56%  |
| WDC                 | 4         | 4      | 8.89%   |
| Intel               | 4         | 5      | 8.89%   |
| Transcend           | 3         | 5      | 6.67%   |
| SanDisk             | 3         | 3      | 6.67%   |
| Kingston            | 3         | 6      | 6.67%   |
| SK hynix            | 2         | 2      | 4.44%   |
| Crucial             | 2         | 2      | 4.44%   |
| Seagate             | 1         | 1      | 2.22%   |
| Qunion              | 1         | 2      | 2.22%   |
| LITEONIT            | 1         | 2      | 2.22%   |
| Intenso             | 1         | 1      | 2.22%   |
| Hitachi             | 1         | 1      | 2.22%   |
| HGST                | 1         | 1      | 2.22%   |
| FORESEE             | 1         | 1      | 2.22%   |
| A-DATA Technology   | 1         | 2      | 2.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Transcend TS256GMTE652T2 256GB          | 2         | 4.17%   |
| SK hynix BC511 HFM512GDJTNI-82A0A 512GB | 2         | 4.17%   |
| SanDisk SSD PLUS 240GB                  | 2         | 4.17%   |
| Samsung SSD 860 EVO 250GB               | 2         | 4.17%   |
| Samsung MZALQ512HBLU-00BL1 512GB        | 2         | 4.17%   |
| Kingston SKC600MS256G 256GB             | 2         | 4.17%   |
| Intel SSDPEKKF512G8L 512GB              | 2         | 4.17%   |
| WDC WDS100T1R0A-68A4W0 1TB              | 1         | 2.08%   |
| WDC WD3200BEVT-22ZCT0 320GB             | 1         | 2.08%   |
| WDC WD20SPZX-22CRAT0 2TB                | 1         | 2.08%   |
| WDC WD10JPLX-00MBPT0 1TB                | 1         | 2.08%   |
| Transcend TS2TMTE220S 2TB               | 1         | 2.08%   |
| Seagate ST1000LX015-1U7172 1TB          | 1         | 2.08%   |
| SanDisk SD7TB3Q-128G-1006 128GB         | 1         | 2.08%   |
| Samsung SSD PM851 mSATA 256GB           | 1         | 2.08%   |
| Samsung SSD PM841 2.5-inch 7mm 256GB    | 1         | 2.08%   |
| Samsung SSD 980 500GB                   | 1         | 2.08%   |
| Samsung SSD 860 EVO 500GB               | 1         | 2.08%   |
| Samsung SSD 850 EVO 250GB               | 1         | 2.08%   |
| Samsung MZVLB256HAHQ-000L7 256GB        | 1         | 2.08%   |
| Samsung MZVKW512HMJP-000H1 512GB        | 1         | 2.08%   |
| Samsung MZHPV512HDGL-000L1 512GB        | 1         | 2.08%   |
| Samsung MZALQ512HBLU-00BL2 512GB        | 1         | 2.08%   |
| Samsung MZ7TE512HMHP-000L2 512GB        | 1         | 2.08%   |
| Samsung MZ7PA128HMCD-010H1 128GB        | 1         | 2.08%   |
| Samsung MZ7LN128HCHP-000H1 128GB        | 1         | 2.08%   |
| Samsung HM320JI 320GB                   | 1         | 2.08%   |
| Qunion P20A 64G                         | 1         | 2.08%   |
| LITEONIT LCS-128M6S 2.5 7mm 128GB       | 1         | 2.08%   |
| Kingston SUV500MS480G 480GB             | 1         | 2.08%   |
| Kingston SUV500MS120G 120GB             | 1         | 2.08%   |
| Intenso JAJM600M256C 256GB              | 1         | 2.08%   |
| Intel SSDSCKKF256G8H 256GB              | 1         | 2.08%   |
| Intel SSDPEKNW020T8 2TB                 | 1         | 2.08%   |
| Hitachi HTS541040G9SA00 40GB            | 1         | 2.08%   |
| HGST HTS545050A7E680 500GB              | 1         | 2.08%   |
| FORESEE 64GB SSD                        | 1         | 2.08%   |
| Crucial CT275MX300SSD4 275GB            | 1         | 2.08%   |
| Crucial CT1000MX500SSD1 1TB             | 1         | 2.08%   |
| A-DATA SU650 240GB                      | 1         | 2.08%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 3      | 42.86%  |
| Seagate             | 1         | 1      | 14.29%  |
| Samsung Electronics | 1         | 1      | 14.29%  |
| Hitachi             | 1         | 1      | 14.29%  |
| HGST                | 1         | 1      | 14.29%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 10     | 37.5%   |
| SanDisk             | 3         | 3      | 12.5%   |
| Kingston            | 3         | 6      | 12.5%   |
| Crucial             | 2         | 2      | 8.33%   |
| WDC                 | 1         | 1      | 4.17%   |
| Qunion              | 1         | 2      | 4.17%   |
| LITEONIT            | 1         | 2      | 4.17%   |
| Intenso             | 1         | 1      | 4.17%   |
| Intel               | 1         | 2      | 4.17%   |
| FORESEE             | 1         | 1      | 4.17%   |
| A-DATA Technology   | 1         | 2      | 4.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 21        | 32     | 52.5%   |
| NVMe | 13        | 18     | 32.5%   |
| HDD  | 6         | 7      | 15%     |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 24        | 39     | 64.86%  |
| NVMe | 13        | 18     | 35.14%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 20        | 32     | 74.07%  |
| 0.51-1.0   | 6         | 6      | 22.22%  |
| 1.01-2.0   | 1         | 1      | 3.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 19        | 42.22%  |
| 251-500    | 16        | 35.56%  |
| 51-100     | 4         | 8.89%   |
| 21-50      | 2         | 4.44%   |
| 1-20       | 2         | 4.44%   |
| 501-1000   | 2         | 4.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 36        | 80%     |
| 21-50   | 6         | 13.33%  |
| 251-500 | 1         | 2.22%   |
| 101-250 | 1         | 2.22%   |
| 51-100  | 1         | 2.22%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD3200BEVT-22ZCT0 320GB                  | 1         | 1      | 16.67%  |
| SanDisk SSD PLUS 240GB                       | 1         | 1      | 16.67%  |
| Samsung Electronics MZ7PA128HMCD-010H1 128GB | 1         | 1      | 16.67%  |
| Intel SSDSCKKF256G8H 256GB                   | 1         | 2      | 16.67%  |
| Hitachi HTS541040G9SA00 40GB                 | 1         | 1      | 16.67%  |
| A-DATA Technology SU630 240GB                | 1         | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 16.67%  |
| SanDisk             | 1         | 1      | 16.67%  |
| Samsung Electronics | 1         | 1      | 16.67%  |
| Intel               | 1         | 2      | 16.67%  |
| Hitachi             | 1         | 1      | 16.67%  |
| A-DATA Technology   | 1         | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Hitachi | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 4         | 5      | 66.67%  |
| HDD  | 2         | 2      | 33.33%  |

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


| Status  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Works   | 34        | 50     | 85%     |
| Malfunc | 6         | 7      | 15%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 29        | 61.7%   |
| Samsung Electronics | 7         | 14.89%  |
| Transcend           | 4         | 8.51%   |
| SK hynix            | 2         | 4.26%   |
| AMD                 | 2         | 4.26%   |
| Toshiba             | 1         | 2.13%   |
| Silicon Motion      | 1         | 2.13%   |
| SanDisk             | 1         | 2.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 4         | 7.84%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 4         | 7.84%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 3         | 5.88%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 3         | 5.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 3         | 5.88%   |
| Transcend NVMe PCIe SSD 220S/240S/MTE710T                                        | 2         | 3.92%   |
| Transcend NVMe PCIe SSD 110S/112S/120S/MTE300S/MTE400S/MTE652T2 (DRAM-less)      | 2         | 3.92%   |
| SK hynix BC511 NVMe SSD                                                          | 2         | 3.92%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 3.92%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                 | 2         | 3.92%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 3.92%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 3.92%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 2         | 3.92%   |
| Toshiba XG4 NVMe SSD Controller                                                  | 1         | 1.96%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 1         | 1.96%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 1         | 1.96%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                       | 1         | 1.96%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 1.96%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 1.96%   |
| Intel SSD 660P Series                                                            | 1         | 1.96%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 1.96%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 1.96%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 1.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.96%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 1         | 1.96%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 1         | 1.96%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 1.96%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 1         | 1.96%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 1         | 1.96%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 1         | 1.96%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 1         | 1.96%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 27        | 56.25%  |
| NVMe | 17        | 35.42%  |
| IDE  | 4         | 8.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 35        | 81.4%   |
| AMD    | 8         | 18.6%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| AMD Ryzen Embedded V1500B                       | 3         | 6.98%   |
| AMD Ryzen 5 5500U with Radeon Graphics          | 3         | 6.98%   |
| Intel Core i7-8665U CPU @ 1.90GHz               | 2         | 4.65%   |
| Intel Core i5-10310U CPU @ 1.70GHz              | 2         | 4.65%   |
| Intel Core i5 CPU M 520 @ 2.40GHz               | 2         | 4.65%   |
| Intel Core i7-8850H CPU @ 2.60GHz               | 1         | 2.33%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 2.33%   |
| Intel Core i7-5500U CPU @ 2.40GHz               | 1         | 2.33%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz              | 1         | 2.33%   |
| Intel Core i7-3687U CPU @ 2.10GHz               | 1         | 2.33%   |
| Intel Core i7-2670QM CPU @ 2.20GHz              | 1         | 2.33%   |
| Intel Core i5-8365U CPU @ 1.60GHz               | 1         | 2.33%   |
| Intel Core i5-8350U CPU @ 1.70GHz               | 1         | 2.33%   |
| Intel Core i5-8279U CPU @ 2.40GHz               | 1         | 2.33%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 1         | 2.33%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 1         | 2.33%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 1         | 2.33%   |
| Intel Core i5-4310U CPU @ 2.00GHz               | 1         | 2.33%   |
| Intel Core i5-4300M CPU @ 2.60GHz               | 1         | 2.33%   |
| Intel Core i5-4200U CPU @ 1.60GHz               | 1         | 2.33%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 1         | 2.33%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 1         | 2.33%   |
| Intel Core i5-2520M CPU @ 2.50GHz               | 1         | 2.33%   |
| Intel Core i5 CPU M 560 @ 2.67GHz               | 1         | 2.33%   |
| Intel Core i3-5005U CPU @ 2.00GHz               | 1         | 2.33%   |
| Intel Core i3-2350M CPU @ 2.30GHz               | 1         | 2.33%   |
| Intel Core 2 Duo CPU L9300 @ 1.60GHz            | 1         | 2.33%   |
| Intel Core 2 CPU                                | 1         | 2.33%   |
| Intel Celeron CPU N3060 @ 1.60GHz               | 1         | 2.33%   |
| Intel Celeron CPU 867 @ 1.30GHz                 | 1         | 2.33%   |
| Intel Celeron CPU 1037U @ 1.80GHz               | 1         | 2.33%   |
| Intel Celeron 3205U @ 1.50GHz                   | 1         | 2.33%   |
| Intel Celeron 2955U @ 1.40GHz                   | 1         | 2.33%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz         | 1         | 2.33%   |
| AMD Ryzen 5 PRO 2500U w/ Radeon Vega Mobile Gfx | 1         | 2.33%   |
| AMD EPYC 3201 8-Core Processor                  | 1         | 2.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 17        | 39.53%  |
| Intel Core i7      | 8         | 18.6%   |
| Intel Celeron      | 5         | 11.63%  |
| AMD Ryzen Embedded | 3         | 6.98%   |
| AMD Ryzen 5        | 3         | 6.98%   |
| Intel Core i3      | 2         | 4.65%   |
| Other              | 1         | 2.33%   |
| Intel Core 2 Duo   | 1         | 2.33%   |
| Intel Core 2       | 1         | 2.33%   |
| AMD Ryzen 5 PRO    | 1         | 2.33%   |
| AMD EPYC           | 1         | 2.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 20        | 45.45%  |
| 4       | 14        | 31.82%  |
| 8       | 4         | 9.09%   |
| 12      | 3         | 6.82%   |
| Unknown | 2         | 4.55%   |
| 6       | 1         | 2.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 42        | 97.67%  |
| Unknown | 1         | 2.33%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 29        | 65.91%  |
| 1       | 13        | 29.55%  |
| Unknown | 2         | 4.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 11        | 25.58%  |
| Zen         | 5         | 11.63%  |
| Haswell     | 5         | 11.63%  |
| SandyBridge | 4         | 9.3%    |
| IvyBridge   | 4         | 9.3%    |
| Westmere    | 3         | 6.98%   |
| Broadwell   | 3         | 6.98%   |
| Unknown     | 3         | 6.98%   |
| TigerLake   | 1         | 2.33%   |
| Skylake     | 1         | 2.33%   |
| Silvermont  | 1         | 2.33%   |
| Penryn      | 1         | 2.33%   |
| Core        | 1         | 2.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 32        | 80%     |
| AMD    | 5         | 12.5%   |
| Nvidia | 3         | 7.5%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 10%     |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 10%     |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 7.5%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 7.5%    |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 7.5%    |
| AMD Lucienne                                                                             | 3         | 7.5%    |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 2         | 5%      |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 5%      |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 2         | 5%      |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 5%      |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                    | 1         | 2.5%    |
| Nvidia GP104GLM [Quadro P4000 Mobile]                                                    | 1         | 2.5%    |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 2.5%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 2.5%    |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 1         | 2.5%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 2.5%    |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 1         | 2.5%    |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 1         | 2.5%    |
| Intel Broadwell-U GT1 [HD Graphics]                                                      | 1         | 2.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.5%    |
| AMD RV515/M52 [Mobility Radeon X1300]                                                    | 1         | 2.5%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 2.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 30        | 69.77%  |
| 1 x AMD        | 5         | 11.63%  |
| Other          | 4         | 9.3%    |
| 1 x Nvidia     | 2         | 4.65%   |
| 2 x Intel      | 1         | 2.33%   |
| Intel + Nvidia | 1         | 2.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 37        | 86.05%  |
| Unknown     | 4         | 9.3%    |
| Proprietary | 2         | 4.65%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 39        | 86.67%  |
| 0.51-1.0   | 2         | 4.44%   |
| 7.01-8.0   | 1         | 2.22%   |
| 3.01-4.0   | 1         | 2.22%   |
| 1.01-2.0   | 1         | 2.22%   |
| 0.01-0.5   | 1         | 2.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| LG Display           | 6         | 18.75%  |
| AU Optronics         | 6         | 18.75%  |
| Lenovo               | 4         | 12.5%   |
| Chimei Innolux       | 3         | 9.38%   |
| BOE                  | 3         | 9.38%   |
| Samsung Electronics  | 2         | 6.25%   |
| BenQ                 | 2         | 6.25%   |
| Unknown              | 1         | 3.13%   |
| InfoVision           | 1         | 3.13%   |
| Hewlett-Packard      | 1         | 3.13%   |
| Dell                 | 1         | 3.13%   |
| Apple                | 1         | 3.13%   |
| Ancor Communications | 1         | 3.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics C34J79x SAM0F1E 3440x1440 800x330mm 34.1-inch     | 2         | 6.25%   |
| LG Display LCD Monitor LGD064C 1920x1080 340x190mm 15.3-inch          | 2         | 6.25%   |
| AU Optronics LCD Monitor AUO2036 2560x1440 310x170mm 13.9-inch        | 2         | 6.25%   |
| Unknown LCD Monitor Sharp 3840x2160                                   | 1         | 3.13%   |
| LG Display LCD Monitor LGD0419 2560x1440 310x170mm 13.9-inch          | 1         | 3.13%   |
| LG Display LCD Monitor LGD03FC 1600x900 310x170mm 13.9-inch           | 1         | 3.13%   |
| LG Display LCD Monitor LGD0353 1366x768 350x190mm 15.7-inch           | 1         | 3.13%   |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch           | 1         | 3.13%   |
| Lenovo P24h-10 LEN61AE 2560x1440 530x300mm 24.0-inch                  | 1         | 3.13%   |
| Lenovo LCD Monitor LEN40B0 1366x768 350x190mm 15.7-inch               | 1         | 3.13%   |
| Lenovo LCD Monitor LEN4043 1400x1050 300x230mm 14.9-inch              | 1         | 3.13%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch               | 1         | 3.13%   |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch          | 1         | 3.13%   |
| Hewlett-Packard E273 HPN3470 1920x1080 600x340mm 27.2-inch            | 1         | 3.13%   |
| Dell P2719H DEL4185 1920x1080 600x340mm 27.2-inch                     | 1         | 3.13%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch      | 1         | 3.13%   |
| Chimei Innolux LCD Monitor CMN1484 1600x900 310x170mm 13.9-inch       | 1         | 3.13%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch       | 1         | 3.13%   |
| BOE LCD Monitor BOE08D7 1920x1080 310x170mm 13.9-inch                 | 1         | 3.13%   |
| BOE LCD Monitor BOE0791 1920x1080 310x170mm 13.9-inch                 | 1         | 3.13%   |
| BOE LCD Monitor BOE0714 1920x1080 310x170mm 13.9-inch                 | 1         | 3.13%   |
| BenQ GW2765 BNQ78D6 2560x1440 600x340mm 27.2-inch                     | 1         | 3.13%   |
| BenQ BL2405 BNQ8016 1920x1080 530x300mm 24.0-inch                     | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO408D 1920x1080 310x170mm 13.9-inch        | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch         | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch        | 1         | 3.13%   |
| AU Optronics LCD Monitor 1920x1080                                    | 1         | 3.13%   |
| Apple Color LCD APP9CC7 1280x800 290x180mm 13.4-inch                  | 1         | 3.13%   |
| Ancor Communications ASUS MG278 ACI27A8 2560x1440 600x340mm 27.2-inch | 1         | 3.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 11        | 36.67%  |
| 2560x1440 (QHD)  | 6         | 20%     |
| 1366x768 (WXGA)  | 4         | 13.33%  |
| 1600x900 (HD+)   | 3         | 10%     |
| 3440x1440        | 2         | 6.67%   |
| 3840x2160 (4K)   | 1         | 3.33%   |
| 1440x900 (WXGA+) | 1         | 3.33%   |
| 1400x1050        | 1         | 3.33%   |
| 1280x800 (WXGA)  | 1         | 3.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 13      | 15        | 46.88%  |
| 27      | 4         | 12.5%   |
| 15      | 4         | 12.5%   |
| 34      | 2         | 6.25%   |
| 24      | 2         | 6.25%   |
| 14      | 2         | 6.25%   |
| Unknown | 2         | 6.25%   |
| 11      | 1         | 3.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 18        | 58.06%  |
| 501-600     | 5         | 16.13%  |
| 201-300     | 4         | 12.9%   |
| 701-800     | 2         | 6.45%   |
| Unknown     | 2         | 6.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 19        | 73.08%  |
| 21/9    | 2         | 7.69%   |
| 16/10   | 2         | 7.69%   |
| Unknown | 2         | 7.69%   |
| 4/3     | 1         | 3.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 16        | 50%     |
| 301-350        | 4         | 12.5%   |
| 101-110        | 3         | 9.38%   |
| 351-500        | 2         | 6.25%   |
| 201-250        | 2         | 6.25%   |
| 91-100         | 2         | 6.25%   |
| Unknown        | 2         | 6.25%   |
| 51-60          | 1         | 3.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 14        | 46.67%  |
| 101-120 | 7         | 23.33%  |
| 51-100  | 4         | 13.33%  |
| 161-240 | 3         | 10%     |
| Unknown | 2         | 6.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 20        | 45.45%  |
| 0     | 17        | 38.64%  |
| 2     | 6         | 13.64%  |
| 3     | 1         | 2.27%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 37        | 64.91%  |
| Realtek Semiconductor             | 11        | 19.3%   |
| AMD                               | 4         | 7.02%   |
| Hewlett-Packard                   | 1         | 1.75%   |
| Ericsson Business Mobile Networks | 1         | 1.75%   |
| Dell                              | 1         | 1.75%   |
| Broadcom                          | 1         | 1.75%   |
| Apple                             | 1         | 1.75%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 8         | 9.41%   |
| Intel I211 Gigabit Network Connection                                  | 5         | 5.88%   |
| Intel Wireless 8265 / 8275                                             | 4         | 4.71%   |
| Intel Wireless 7260                                                    | 4         | 4.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 4.71%   |
| AMD XGMAC 10GbE Controller                                             | 4         | 4.71%   |
| Intel Wireless 7265                                                    | 3         | 3.53%   |
| Intel Centrino Ultimate-N 6300                                         | 3         | 3.53%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 3         | 3.53%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 3.53%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 2         | 2.35%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 2         | 2.35%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 2         | 2.35%   |
| Intel Ethernet Controller I226-V                                       | 2         | 2.35%   |
| Intel Ethernet Connection (6) I219-LM                                  | 2         | 2.35%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 2         | 2.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 1         | 1.18%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 1         | 1.18%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 1         | 1.18%   |
| Intel Wireless 8260                                                    | 1         | 1.18%   |
| Intel WiFi Link 5100                                                   | 1         | 1.18%   |
| Intel Wi-Fi 6 AX201                                                    | 1         | 1.18%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 1         | 1.18%   |
| Intel I210 Gigabit Network Connection                                  | 1         | 1.18%   |
| Intel Ethernet Controller I225-V                                       | 1         | 1.18%   |
| Intel Ethernet Controller I225-LM                                      | 1         | 1.18%   |
| Intel Ethernet Connection I219-V                                       | 1         | 1.18%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 1.18%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 1.18%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1         | 1.18%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 1.18%   |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 1.18%   |
| Intel Ethernet Connection (3) I218-V                                   | 1         | 1.18%   |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 1.18%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 1.18%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                          | 1         | 1.18%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                           | 1         | 1.18%   |
| Intel Centrino Advanced-N 6235                                         | 1         | 1.18%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 1         | 1.18%   |
| Intel Centrino Advanced-N 6200                                         | 1         | 1.18%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 30        | 78.95%  |
| Realtek Semiconductor | 6         | 15.79%  |
| Dell                  | 1         | 2.63%   |
| Broadcom              | 1         | 2.63%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                               | 4         | 10.26%  |
| Intel Wireless 7260                                      | 4         | 10.26%  |
| Intel Wireless 7265                                      | 3         | 7.69%   |
| Intel Centrino Ultimate-N 6300                           | 3         | 7.69%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                 | 3         | 7.69%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter | 2         | 5.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter      | 2         | 5.13%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]  | 2         | 5.13%   |
| Intel Comet Lake PCH-LP CNVi WiFi                        | 2         | 5.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter | 1         | 2.56%   |
| Realtek RTL8188EE Wireless Network Adapter               | 1         | 2.56%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter               | 1         | 2.56%   |
| Intel Wireless 8260                                      | 1         | 2.56%   |
| Intel WiFi Link 5100                                     | 1         | 2.56%   |
| Intel Wi-Fi 6 AX201                                      | 1         | 2.56%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection    | 1         | 2.56%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]            | 1         | 2.56%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]             | 1         | 2.56%   |
| Intel Centrino Advanced-N 6235                           | 1         | 2.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]             | 1         | 2.56%   |
| Intel Centrino Advanced-N 6200                           | 1         | 2.56%   |
| Dell Wireless 5550 HSPA+ Mini-Card Network Adapter       | 1         | 2.56%   |
| Broadcom BCM4331 802.11a/b/g/n                           | 1         | 2.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 28        | 66.67%  |
| Realtek Semiconductor | 8         | 19.05%  |
| AMD                   | 4         | 9.52%   |
| Broadcom              | 1         | 2.38%   |
| Apple                 | 1         | 2.38%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 8         | 18.18%  |
| Intel I211 Gigabit Network Connection                                  | 5         | 11.36%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 9.09%   |
| AMD XGMAC 10GbE Controller                                             | 4         | 9.09%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 6.82%   |
| Intel Ethernet Controller I226-V                                       | 2         | 4.55%   |
| Intel Ethernet Connection (6) I219-LM                                  | 2         | 4.55%   |
| Intel I210 Gigabit Network Connection                                  | 1         | 2.27%   |
| Intel Ethernet Controller I225-V                                       | 1         | 2.27%   |
| Intel Ethernet Controller I225-LM                                      | 1         | 2.27%   |
| Intel Ethernet Connection I219-V                                       | 1         | 2.27%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 2.27%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 2.27%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1         | 2.27%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 2.27%   |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 2.27%   |
| Intel Ethernet Connection (3) I218-V                                   | 1         | 2.27%   |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 2.27%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 2.27%   |
| Intel 82573L Gigabit Ethernet Controller                               | 1         | 2.27%   |
| Intel 82567LM Gigabit Network Connection                               | 1         | 2.27%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 1         | 2.27%   |
| Apple Ethernet Adapter [A1277]                                         | 1         | 2.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 37        | 49.33%  |
| Ethernet | 36        | 48%     |
| Modem    | 1         | 1.33%   |
| Unknown  | 1         | 1.33%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 28        | 54.9%   |
| WiFi     | 22        | 43.14%  |
| Modem    | 1         | 1.96%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 25        | 58.14%  |
| 1     | 6         | 13.95%  |
| 3     | 5         | 11.63%  |
| 6     | 3         | 6.98%   |
| 5     | 2         | 4.65%   |
| 9     | 1         | 2.33%   |
| 0     | 1         | 2.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 40        | 90.91%  |
| Yes  | 4         | 9.09%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 19        | 67.86%  |
| Broadcom              | 4         | 14.29%  |
| Realtek Semiconductor | 3         | 10.71%  |
| Apple                 | 1         | 3.57%   |
| Alps Electric         | 1         | 3.57%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface               | 9         | 32.14%  |
| Realtek Bluetooth Adapter                        | 3         | 10.71%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 3         | 10.71%  |
| Intel AX201 Bluetooth                            | 3         | 10.71%  |
| Broadcom BCM2045B (BDC-2.1)                      | 3         | 10.71%  |
| Intel Wireless-AC 9260 Bluetooth Adapter         | 2         | 7.14%   |
| Intel Centrino Bluetooth Wireless Transceiver    | 1         | 3.57%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter | 1         | 3.57%   |
| Broadcom BCM2035 Bluetooth dongle                | 1         | 3.57%   |
| Apple Broadcom Built-in Bluetooth                | 1         | 3.57%   |
| Alps Electric UGTZ4 Bluetooth                    | 1         | 3.57%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 33        | 68.75%  |
| AMD                 | 7         | 14.58%  |
| Plantronics         | 4         | 8.33%   |
| Lenovo              | 2         | 4.17%   |
| Nvidia              | 1         | 2.08%   |
| Kingston Technology | 1         | 2.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                                                     | 7         | 11.67%  |
| Plantronics Plantronics Blackwire 315.1                                                           | 4         | 6.67%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 4         | 6.67%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 6.67%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 5%      |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 5%      |
| Intel Broadwell-U Audio Controller                                                                | 3         | 5%      |
| Intel 8 Series HD Audio Controller                                                                | 3         | 5%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 3         | 5%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 5%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 5%      |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 3         | 5%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 3.33%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 3.33%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 3.33%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.67%   |
| Lenovo ThinkPad OneLink Pro Dock                                                                  | 1         | 1.67%   |
| Lenovo Realtek USB Audio                                                                          | 1         | 1.67%   |
| Kingston Technology HyperX QuadCast                                                               | 1         | 1.67%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 1.67%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 1.67%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 1.67%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.67%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 1.67%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 1.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 16        | 32.65%  |
| SK hynix            | 9         | 18.37%  |
| Micron Technology   | 6         | 12.24%  |
| Kingston            | 6         | 12.24%  |
| Transcend           | 4         | 8.16%   |
| Crucial             | 3         | 6.12%   |
| Nanya Technology    | 2         | 4.08%   |
| Unknown             | 1         | 2.04%   |
| Elpida              | 1         | 2.04%   |
| Corsair             | 1         | 2.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s            | 3         | 5.77%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                  | 2         | 3.85%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                 | 2         | 3.85%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s         | 2         | 3.85%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s         | 2         | 3.85%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s           | 2         | 3.85%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s          | 2         | 3.85%   |
| Unknown RAM Module 2048MB SODIMM DDR2                          | 1         | 1.92%   |
| Unknown RAM Module 1024MB SODIMM DDR2                          | 1         | 1.92%   |
| Transcend RAM TS2GLH64V2B 16GB SODIMM DDR4 1600MT/s            | 1         | 1.92%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 1         | 1.92%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 1.92%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s         | 1         | 1.92%   |
| SK hynix RAM HMT351S6AFR8C-PB 8GB SODIMM DDR3 1333MT/s         | 1         | 1.92%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s         | 1         | 1.92%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s         | 1         | 1.92%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 1         | 1.92%   |
| Samsung RAM Module 8GB SODIMM DDR3 1067MT/s                    | 1         | 1.92%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                    | 1         | 1.92%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s          | 1         | 1.92%   |
| Samsung RAM M471B5674-M0-YK0 4GB Chip DDR3 1600MT/s            | 1         | 1.92%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 1         | 1.92%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s          | 1         | 1.92%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s          | 1         | 1.92%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s          | 1         | 1.92%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s         | 1         | 1.92%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s          | 1         | 1.92%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s          | 1         | 1.92%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s          | 1         | 1.92%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1334MT/s           | 1         | 1.92%   |
| Nanya RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 1.92%   |
| Micron RAM MT52L512M32D2PF-10 4GB Row Of Chips LPDDR3 1867MT/s | 1         | 1.92%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s          | 1         | 1.92%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s     | 1         | 1.92%   |
| Micron RAM 16JTF51264HZ-1G4M1 4GB SODIMM DDR3 1333MT/s         | 1         | 1.92%   |
| Kingston RAM Module 8GB SODIMM DDR4 2400MT/s                   | 1         | 1.92%   |
| Kingston RAM KCRXJ6-MIE 16GB SODIMM DDR4 2667MT/s              | 1         | 1.92%   |
| Kingston RAM CBD26D4S9S8K1C-8 8GB SODIMM DDR4 3200MT/s         | 1         | 1.92%   |
| Kingston RAM 99U5417-030.A00G 4GB SODIMM DDR3 1600MT/s         | 1         | 1.92%   |
| Elpida RAM EBJ21UE8BDS0-AE-F 2GB SODIMM DDR3 1067MT/s          | 1         | 1.92%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 20        | 48.78%  |
| DDR3   | 19        | 46.34%  |
| LPDDR3 | 1         | 2.44%   |
| DDR2   | 1         | 2.44%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 38        | 92.68%  |
| Row Of Chips | 2         | 4.88%   |
| Chip         | 1         | 2.44%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 20        | 45.45%  |
| 16384 | 8         | 18.18%  |
| 4096  | 8         | 18.18%  |
| 2048  | 5         | 11.36%  |
| 32768 | 2         | 4.55%   |
| 1024  | 1         | 2.27%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 14        | 33.33%  |
| 3200    | 9         | 21.43%  |
| 2667    | 7         | 16.67%  |
| 1334    | 3         | 7.14%   |
| 2133    | 2         | 4.76%   |
| 1333    | 2         | 4.76%   |
| 1067    | 2         | 4.76%   |
| 2400    | 1         | 2.38%   |
| 1867    | 1         | 2.38%   |
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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 11        | 44%     |
| Microdia                               | 3         | 12%     |
| Bison Electronics                      | 3         | 12%     |
| Realtek Semiconductor                  | 2         | 8%      |
| Cheng Uei Precision Industry (Foxlink) | 2         | 8%      |
| Lite-On Technology                     | 1         | 4%      |
| Lenovo                                 | 1         | 4%      |
| IMC Networks                           | 1         | 4%      |
| Apple                                  | 1         | 4%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony ThinkPad T490 Webcam                                | 3         | 12%     |
| Chicony integrated camera                                   | 3         | 12%     |
| Realtek USB 2.0 PC Camera                                   | 2         | 8%      |
| Chicony HP HD Camera                                        | 2         | 8%      |
| Microdia Laptop_Integrated_Webcam_HD                        | 1         | 4%      |
| Microdia Integrated Webcam HD                               | 1         | 4%      |
| Microdia Integrated Webcam                                  | 1         | 4%      |
| Lite-On HP HD Camera                                        | 1         | 4%      |
| Lenovo Integrated Webcam [R5U877]                           | 1         | 4%      |
| IMC Networks Integrated Camera                              | 1         | 4%      |
| Chicony Integrated IR Camera                                | 1         | 4%      |
| Chicony Integrated Camera (1280x720@30)                     | 1         | 4%      |
| Chicony HP Universal Camera                                 | 1         | 4%      |
| Cheng Uei Precision Industry (Foxlink) Webcam               | 1         | 4%      |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed] | 1         | 4%      |
| Bison SunplusIT Integrated Camera                           | 1         | 4%      |
| Bison Lenovo EasyCamera                                     | 1         | 4%      |
| Bison Integrated Camera                                     | 1         | 4%      |
| Apple FaceTime HD Camera                                    | 1         | 4%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 36.84%  |
| Upek                       | 4         | 21.05%  |
| Synaptics                  | 4         | 21.05%  |
| Shenzhen Goodix Technology | 2         | 10.53%  |
| STMicroelectronics         | 1         | 5.26%   |
| Elan Microelectronics      | 1         | 5.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 4         | 21.05%  |
| Validity Sensors VFS495 Fingerprint Reader               | 3         | 15.79%  |
| Validity Sensors VFS 5011 fingerprint sensor             | 2         | 10.53%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 2         | 10.53%  |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 10.53%  |
| Shenzhen Goodix Fingerprint Reader                       | 2         | 10.53%  |
| Validity Sensors VFS5011 Fingerprint Reader              | 1         | 5.26%   |
| Validity Sensors VFS491                                  | 1         | 5.26%   |
| STMicroelectronics Fingerprint Reader                    | 1         | 5.26%   |
| Elan Fingerprint Sensor                                  | 1         | 5.26%   |

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
| 2     | 16        | 34.78%  |
| 1     | 13        | 28.26%  |
| 3     | 9         | 19.57%  |
| 0     | 5         | 10.87%  |
| 4     | 3         | 6.52%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 32        | 42.67%  |
| Fingerprint reader       | 19        | 25.33%  |
| Bluetooth                | 9         | 12%     |
| Card reader              | 8         | 10.67%  |
| Firewire controller      | 3         | 4%      |
| Net/wireless             | 2         | 2.67%   |
| Net/ethernet             | 1         | 1.33%   |
| Graphics card            | 1         | 1.33%   |

