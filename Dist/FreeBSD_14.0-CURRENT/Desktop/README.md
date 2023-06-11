FreeBSD 14.0-CURRENT - Tested Hardware & Statistics (Desktops)
--------------------------------------------------------------

A project to collect tested hardware configurations for FreeBSD 14.0-CURRENT.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 64

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Gigabyte      | H170-D3HP-CF                | [d5fdf2ff2c](https://bsd-hardware.info/?probe=d5fdf2ff2c) | May 28, 2023 |
| Unknown       | Unknown                     | [990b3eb510](https://bsd-hardware.info/?probe=990b3eb510) | May 12, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [dcea67b6a6](https://bsd-hardware.info/?probe=dcea67b6a6) | May 08, 2023 |
| Unknown       | Unknown                     | [c801b9e5af](https://bsd-hardware.info/?probe=c801b9e5af) | Apr 03, 2023 |
| Unknown       | Unknown                     | [9b2420726f](https://bsd-hardware.info/?probe=9b2420726f) | Apr 03, 2023 |
| Unknown       | Unknown                     | [414cbf5935](https://bsd-hardware.info/?probe=414cbf5935) | Apr 03, 2023 |
| Unknown       | Unknown                     | [6b79c64c73](https://bsd-hardware.info/?probe=6b79c64c73) | Apr 03, 2023 |
| SolidRun      | CEX7 Platform               | [8e2e4d6686](https://bsd-hardware.info/?probe=8e2e4d6686) | Mar 31, 2023 |
| ASRockRack    | EPYCD8-2T                   | [75f414997a](https://bsd-hardware.info/?probe=75f414997a) | Mar 31, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [e55635df08](https://bsd-hardware.info/?probe=e55635df08) | Feb 23, 2023 |
| ASRock        | A520M-ITX/ac                | [dd083df1a2](https://bsd-hardware.info/?probe=dd083df1a2) | Feb 16, 2023 |
| ASUSTek       | PRIME H410M-K               | [d2edba8775](https://bsd-hardware.info/?probe=d2edba8775) | Feb 11, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [87e25e2abd](https://bsd-hardware.info/?probe=87e25e2abd) | Jan 26, 2023 |
| Unknown       | Unknown                     | [3afbfc6cea](https://bsd-hardware.info/?probe=3afbfc6cea) | Jan 20, 2023 |
| Unknown       | Unknown                     | [e13627df1a](https://bsd-hardware.info/?probe=e13627df1a) | Jan 20, 2023 |
| ASUSTek       | PRIME Z390-P                | [3126dc27f1](https://bsd-hardware.info/?probe=3126dc27f1) | Jan 12, 2023 |
| Unknown       | Unknown                     | [d702dfcde2](https://bsd-hardware.info/?probe=d702dfcde2) | Dec 23, 2022 |
| ASRock        | 4X4-4000 Series             | [009ef73bd1](https://bsd-hardware.info/?probe=009ef73bd1) | Dec 20, 2022 |
| Unknown       | Unknown                     | [7c644cc639](https://bsd-hardware.info/?probe=7c644cc639) | Dec 15, 2022 |
| MSI           | B450M MORTAR MAX            | [15657b37e2](https://bsd-hardware.info/?probe=15657b37e2) | Nov 15, 2022 |
| MSI           | B450M MORTAR MAX            | [f4a8c42773](https://bsd-hardware.info/?probe=f4a8c42773) | Nov 15, 2022 |
| Unknown       | Unknown                     | [20ff21d751](https://bsd-hardware.info/?probe=20ff21d751) | Oct 18, 2022 |
| MSI           | Z490-A PRO                  | [dbda136daa](https://bsd-hardware.info/?probe=dbda136daa) | Sep 24, 2022 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [98dff45d54](https://bsd-hardware.info/?probe=98dff45d54) | Sep 09, 2022 |
| Dell          | 0VG93V A00                  | [8de9fa2319](https://bsd-hardware.info/?probe=8de9fa2319) | Aug 18, 2022 |
| Unknown       | Unknown                     | [3208aefb72](https://bsd-hardware.info/?probe=3208aefb72) | Aug 17, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | [3dc5a6f7d2](https://bsd-hardware.info/?probe=3dc5a6f7d2) | May 24, 2022 |
| Unknown       | Unknown                     | [f3ab857e43](https://bsd-hardware.info/?probe=f3ab857e43) | May 13, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [224614e9ab](https://bsd-hardware.info/?probe=224614e9ab) | May 10, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [76eef59920](https://bsd-hardware.info/?probe=76eef59920) | May 10, 2022 |
| Gigabyte      | B450M S2H                   | [ee73e0cddb](https://bsd-hardware.info/?probe=ee73e0cddb) | Apr 07, 2022 |
| HP            | 83E1                        | [d8e995126f](https://bsd-hardware.info/?probe=d8e995126f) | Feb 10, 2022 |
| Gigabyte      | B450M DS3H-CF               | [825d20fcf7](https://bsd-hardware.info/?probe=825d20fcf7) | Jan 14, 2022 |
| Gigabyte      | B450M DS3H-CF               | [b953d9d2e6](https://bsd-hardware.info/?probe=b953d9d2e6) | Jan 13, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [2cc4698cbc](https://bsd-hardware.info/?probe=2cc4698cbc) | Jan 09, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [2481037b2a](https://bsd-hardware.info/?probe=2481037b2a) | Jan 09, 2022 |
| ASUSTek       | TUF GAMING B550-PLUS        | [ea4719600a](https://bsd-hardware.info/?probe=ea4719600a) | Jan 05, 2022 |
| ASRock        | B450 Steel Legend           | [e67007df20](https://bsd-hardware.info/?probe=e67007df20) | Jan 01, 2022 |
| friendlyel... | nanopi-m4                   | [bb29e50061](https://bsd-hardware.info/?probe=bb29e50061) | Dec 27, 2021 |
| khadas        | edge-v                      | [42c428aac0](https://bsd-hardware.info/?probe=42c428aac0) | Dec 26, 2021 |
| Unknown       | Unknown                     | [b726a1b3e3](https://bsd-hardware.info/?probe=b726a1b3e3) | Dec 11, 2021 |
| ASUSTek       | PRIME X570-PRO              | [9a8d19aa04](https://bsd-hardware.info/?probe=9a8d19aa04) | Dec 11, 2021 |
| Unknown       | Unknown                     | [7633cb9296](https://bsd-hardware.info/?probe=7633cb9296) | Dec 11, 2021 |
| Beckhoff A... | CX51x0 G3                   | [6db720018b](https://bsd-hardware.info/?probe=6db720018b) | Oct 25, 2021 |
| Beckhoff A... | CX20x3 G1                   | [a49fbd5ce3](https://bsd-hardware.info/?probe=a49fbd5ce3) | Oct 25, 2021 |
| ASUSTek       | PRIME Z590-A                | [1aa5ced5a0](https://bsd-hardware.info/?probe=1aa5ced5a0) | Sep 23, 2021 |
| Gigabyte      | X399 DESIGNARE EX-CF        | [a78cc6a11b](https://bsd-hardware.info/?probe=a78cc6a11b) | Sep 04, 2021 |
| Unknown       | Unknown                     | [4a3836de00](https://bsd-hardware.info/?probe=4a3836de00) | Jul 08, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [edebe87739](https://bsd-hardware.info/?probe=edebe87739) | Jun 04, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [62b9ea2794](https://bsd-hardware.info/?probe=62b9ea2794) | May 14, 2021 |
| ASUSTek       | P8H77-M PRO                 | [b3acafeb1a](https://bsd-hardware.info/?probe=b3acafeb1a) | May 09, 2021 |
| ASUSTek       | P8H77-M PRO                 | [86cec3b874](https://bsd-hardware.info/?probe=86cec3b874) | May 09, 2021 |
| pine64        | pinebook-pro-rk3399         | [79713a2668](https://bsd-hardware.info/?probe=79713a2668) | Apr 25, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [325186171a](https://bsd-hardware.info/?probe=325186171a) | Apr 02, 2021 |
| Gigabyte      | 970A-UD3P                   | [cc3151bc6f](https://bsd-hardware.info/?probe=cc3151bc6f) | Mar 17, 2021 |
| MSI           | B450 GAMING PLUS            | [547fd655f0](https://bsd-hardware.info/?probe=547fd655f0) | Mar 13, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [29936dd1c0](https://bsd-hardware.info/?probe=29936dd1c0) | Feb 25, 2021 |
| Unknown       | Unknown                     | [74b11992d7](https://bsd-hardware.info/?probe=74b11992d7) | Feb 20, 2021 |
| Raspberry ... | rpi                         | [92ee9b3619](https://bsd-hardware.info/?probe=92ee9b3619) | Feb 18, 2021 |
| ASUSTek       | PRIME B450M-A               | [ba7f82b343](https://bsd-hardware.info/?probe=ba7f82b343) | Feb 12, 2021 |
| pine64        | pinebook-pro-rk3399         | [5a55b22f44](https://bsd-hardware.info/?probe=5a55b22f44) | Feb 09, 2021 |
| Dell          | 0D9JG3 A00                  | [65dd4083c5](https://bsd-hardware.info/?probe=65dd4083c5) | Feb 09, 2021 |
| pine64        | pinebook-pro-rk3399         | [97e72f0066](https://bsd-hardware.info/?probe=97e72f0066) | Feb 06, 2021 |
| pine64        | pinebook-pro-rk3399         | [2338de9efc](https://bsd-hardware.info/?probe=2338de9efc) | Jan 24, 2021 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 38       | 67.86%  |
| arm64 | 15       | 26.79%  |
| arm   | 2        | 3.57%   |
| riscv | 1        | 1.79%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| Console  | 26       | 45.61%  |
| KDE5     | 16       | 28.07%  |
| XFCE     | 5        | 8.77%   |
| Openbox  | 3        | 5.26%   |
| GNOME    | 2        | 3.51%   |
| TWM      | 1        | 1.75%   |
| spectrwm | 1        | 1.75%   |
| MATE     | 1        | 1.75%   |
| LXQt     | 1        | 1.75%   |
| i3       | 1        | 1.75%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 32       | 56.14%  |
| Console | 23       | 40.35%  |
| Wayland | 2        | 3.51%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 34       | 59.65%  |
| SDDM    | 10       | 17.54%  |
| SLiM    | 5        | 8.77%   |
| GDM     | 4        | 7.02%   |
| XDM     | 2        | 3.51%   |
| Ly      | 1        | 1.75%   |
| LightDM | 1        | 1.75%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| C       | 27       | 48.21%  |
| en_US   | 14       | 25%     |
| de_DE   | 4        | 7.14%   |
| Unknown | 4        | 7.14%   |
| uk_UA   | 3        | 5.36%   |
| sv_SE   | 1        | 1.79%   |
| ru_RU   | 1        | 1.79%   |
| en_CA   | 1        | 1.79%   |
| de_CH   | 1        | 1.79%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 50       | 89.29%  |
| BIOS | 6        | 10.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Zfs  | 38       | 67.86%  |
| Ufs  | 18       | 32.14%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 52       | 92.86%  |
| MBR  | 4        | 7.14%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Unknown                 | 15       | 26.79%  |
| ASUSTek Computer        | 12       | 21.43%  |
| Gigabyte Technology     | 9        | 16.07%  |
| ASRock                  | 5        | 8.93%   |
| MSI                     | 4        | 7.14%   |
| Dell                    | 2        | 3.57%   |
| Beckhoff Automation     | 2        | 3.57%   |
| SolidRun                | 1        | 1.79%   |
| Raspberry Pi Foundation | 1        | 1.79%   |
| pine64                  | 1        | 1.79%   |
| khadas                  | 1        | 1.79%   |
| Hewlett-Packard         | 1        | 1.79%   |
| friendlyelec            | 1        | 1.79%   |
| ASRockRack              | 1        | 1.79%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 15       | 26.79%  |
| SolidRun CEX7 Platform             | 1        | 1.79%   |
| RPi rpi                            | 1        | 1.79%   |
| pine64 pinebook-pro-rk3399         | 1        | 1.79%   |
| MSI MS-7C79                        | 1        | 1.79%   |
| MSI MS-7C75                        | 1        | 1.79%   |
| MSI MS-7B89                        | 1        | 1.79%   |
| MSI MS-7B86                        | 1        | 1.79%   |
| khadas edge-v                      | 1        | 1.79%   |
| HP EliteDesk 800 G4 SFF            | 1        | 1.79%   |
| Gigabyte X670E AORUS MASTER        | 1        | 1.79%   |
| Gigabyte X570 AORUS MASTER         | 1        | 1.79%   |
| Gigabyte X570 AORUS ELITE          | 1        | 1.79%   |
| Gigabyte X399 DESIGNARE EX         | 1        | 1.79%   |
| Gigabyte H170-D3HP                 | 1        | 1.79%   |
| Gigabyte B550I AORUS PRO AX        | 1        | 1.79%   |
| Gigabyte B450M S2H                 | 1        | 1.79%   |
| Gigabyte B450M DS3H                | 1        | 1.79%   |
| Gigabyte 970A-UD3P                 | 1        | 1.79%   |
| friendlyelec nanopi-m4             | 1        | 1.79%   |
| Dell OptiPlex 5090                 | 1        | 1.79%   |
| Dell OptiPlex 5080                 | 1        | 1.79%   |
| Beckhoff Automation CX2033-0185    | 1        | 1.79%   |
| Beckhoff Automation CBxx63         | 1        | 1.79%   |
| ASUS TUF GAMING B550-PLUS          | 1        | 1.79%   |
| ASUS ROG STRIX X670E-F GAMING WIFI | 1        | 1.79%   |
| ASUS ROG STRIX X570-E GAMING       | 1        | 1.79%   |
| ASUS ROG STRIX B550-I GAMING       | 1        | 1.79%   |
| ASUS PRIME Z590-A                  | 1        | 1.79%   |
| ASUS PRIME Z390-P                  | 1        | 1.79%   |
| ASUS PRIME X570-PRO                | 1        | 1.79%   |
| ASUS PRIME H410M-K                 | 1        | 1.79%   |
| ASUS PRIME B550-PLUS               | 1        | 1.79%   |
| ASUS PRIME B450M-GAMING/BR         | 1        | 1.79%   |
| ASUS PRIME B450M-A                 | 1        | 1.79%   |
| ASUS P8H77-M PRO                   | 1        | 1.79%   |
| ASRockRack EPYCD8-2T               | 1        | 1.79%   |
| ASRock X570 Phantom Gaming 4       | 1        | 1.79%   |
| ASRock B550 Phantom Gaming-ITX/ax  | 1        | 1.79%   |
| ASRock B450 Steel Legend           | 1        | 1.79%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| Unknown                         | 15       | 26.79%  |
| ASUS PRIME                      | 7        | 12.5%   |
| ASUS ROG                        | 3        | 5.36%   |
| Gigabyte X570                   | 2        | 3.57%   |
| Gigabyte B450M                  | 2        | 3.57%   |
| Dell OptiPlex                   | 2        | 3.57%   |
| SolidRun CEX7                   | 1        | 1.79%   |
| RPi rpi                         | 1        | 1.79%   |
| pine64 pinebook-pro-rk3399      | 1        | 1.79%   |
| MSI MS-7C79                     | 1        | 1.79%   |
| MSI MS-7C75                     | 1        | 1.79%   |
| MSI MS-7B89                     | 1        | 1.79%   |
| MSI MS-7B86                     | 1        | 1.79%   |
| khadas edge-v                   | 1        | 1.79%   |
| HP EliteDesk                    | 1        | 1.79%   |
| Gigabyte X670E                  | 1        | 1.79%   |
| Gigabyte X399                   | 1        | 1.79%   |
| Gigabyte H170-D3HP              | 1        | 1.79%   |
| Gigabyte B550I                  | 1        | 1.79%   |
| Gigabyte 970A-UD3P              | 1        | 1.79%   |
| friendlyelec nanopi-m4          | 1        | 1.79%   |
| Beckhoff Automation CX2033-0185 | 1        | 1.79%   |
| Beckhoff Automation CBxx63      | 1        | 1.79%   |
| ASUS TUF                        | 1        | 1.79%   |
| ASUS P8H77-M                    | 1        | 1.79%   |
| ASRockRack EPYCD8-2T            | 1        | 1.79%   |
| ASRock X570                     | 1        | 1.79%   |
| ASRock B550                     | 1        | 1.79%   |
| ASRock B450                     | 1        | 1.79%   |
| ASRock A520M-ITX                | 1        | 1.79%   |
| ASRock 4X4                      | 1        | 1.79%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 13       | 23.21%  |
| 2021    | 12       | 21.43%  |
| 2020    | 11       | 19.64%  |
| 2019    | 7        | 12.5%   |
| 2018    | 5        | 8.93%   |
| 2023    | 3        | 5.36%   |
| 2022    | 2        | 3.57%   |
| 2017    | 1        | 1.79%   |
| 2016    | 1        | 1.79%   |
| 2012    | 1        | 1.79%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 56       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 56       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 64.01-256.0 | 14       | 25%     |
| 16.01-24.0  | 14       | 25%     |
| 32.01-64.0  | 8        | 14.29%  |
| 3.01-4.0    | 7        | 12.5%   |
| 4.01-8.0    | 5        | 8.93%   |
| 8.01-16.0   | 5        | 8.93%   |
| 0.51-1.0    | 2        | 3.57%   |
| 0.01-0.5    | 1        | 1.79%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 16       | 28.57%  |
| 0.01-0.5    | 15       | 26.79%  |
| 0.51-1.0    | 12       | 21.43%  |
| 2.01-3.0    | 6        | 10.71%  |
| 3.01-4.0    | 3        | 5.36%   |
| 0           | 2        | 3.57%   |
| 64.01-256.0 | 1        | 1.79%   |
| 16.01-24.0  | 1        | 1.79%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 0      | 18       | 32.14%  |
| 1      | 13       | 23.21%  |
| 2      | 9        | 16.07%  |
| 3      | 7        | 12.5%   |
| 6      | 3        | 5.36%   |
| 4      | 3        | 5.36%   |
| 15     | 1        | 1.79%   |
| 7      | 1        | 1.79%   |
| 5      | 1        | 1.79%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 46       | 82.14%  |
| Yes       | 10       | 17.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 45       | 80.36%  |
| No        | 11       | 19.64%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 35       | 62.5%   |
| Yes       | 21       | 37.5%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 42       | 75%     |
| Yes       | 14       | 25%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Russia       | 14       | 25%     |
| Germany      | 8        | 14.29%  |
| USA          | 5        | 8.93%   |
| UK           | 5        | 8.93%   |
| Ukraine      | 4        | 7.14%   |
| Brazil       | 3        | 5.36%   |
| Romania      | 2        | 3.57%   |
| Japan        | 2        | 3.57%   |
| Canada       | 2        | 3.57%   |
| Turkey       | 1        | 1.79%   |
| Switzerland  | 1        | 1.79%   |
| Sweden       | 1        | 1.79%   |
| Saudi Arabia | 1        | 1.79%   |
| Portugal     | 1        | 1.79%   |
| Poland       | 1        | 1.79%   |
| Netherlands  | 1        | 1.79%   |
| France       | 1        | 1.79%   |
| Denmark      | 1        | 1.79%   |
| Czechia      | 1        | 1.79%   |
| Austria      | 1        | 1.79%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                        | Desktops | Percent |
|-----------------------------|----------|---------|
| Krasnodar                   | 7        | 12.28%  |
| Moscow                      | 4        | 7.02%   |
| Kyiv                        | 3        | 5.26%   |
| St Petersburg               | 2        | 3.51%   |
| Rio de Janeiro              | 2        | 3.51%   |
| Rietberg                    | 2        | 3.51%   |
| Egham                       | 2        | 3.51%   |
| Cambridge                   | 2        | 3.51%   |
| ЕЊta-ku                   | 1        | 1.75%   |
| Zurich                      | 1        | 1.75%   |
| Zaporizhzhya                | 1        | 1.75%   |
| Vila Real de Santo António | 1        | 1.75%   |
| Stolberg                    | 1        | 1.75%   |
| St. Albert                  | 1        | 1.75%   |
| Sollentuna                  | 1        | 1.75%   |
| Satu Mare                   | 1        | 1.75%   |
| Santa Monica                | 1        | 1.75%   |
| Ruislip                     | 1        | 1.75%   |
| Riyadh                      | 1        | 1.75%   |
| Radzionkow                  | 1        | 1.75%   |
| Orenburg                    | 1        | 1.75%   |
| Northeim                    | 1        | 1.75%   |
| Ludwigsburg                 | 1        | 1.75%   |
| Lake Forest                 | 1        | 1.75%   |
| Kongens Lyngby              | 1        | 1.75%   |
| Jaboatao dos Guararapes     | 1        | 1.75%   |
| Istanbul                    | 1        | 1.75%   |
| Innisfil                    | 1        | 1.75%   |
| Graz                        | 1        | 1.75%   |
| Göttingen                  | 1        | 1.75%   |
| Fuchu                       | 1        | 1.75%   |
| Fremont                     | 1        | 1.75%   |
| Cologne                     | 1        | 1.75%   |
| Claix                       | 1        | 1.75%   |
| Chicago                     | 1        | 1.75%   |
| Bunkyo-ku                   | 1        | 1.75%   |
| Brno                        | 1        | 1.75%   |
| Berlin                      | 1        | 1.75%   |
| Arad                        | 1        | 1.75%   |
| Amsterdam                   | 1        | 1.75%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 15       | 21     | 22.39%  |
| Samsung Electronics | 12       | 22     | 17.91%  |
| Seagate             | 8        | 20     | 11.94%  |
| Crucial             | 7        | 14     | 10.45%  |
| Toshiba             | 5        | 9      | 7.46%   |
| Kingston            | 5        | 6      | 7.46%   |
| Intel               | 4        | 4      | 5.97%   |
| A-DATA Technology   | 3        | 3      | 4.48%   |
| SK hynix            | 2        | 2      | 2.99%   |
| PNY                 | 1        | 1      | 1.49%   |
| Micron Technology   | 1        | 2      | 1.49%   |
| HGST                | 1        | 2      | 1.49%   |
| GOODRAM             | 1        | 1      | 1.49%   |
| FORESEE             | 1        | 1      | 1.49%   |
| Apacer              | 1        | 1      | 1.49%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Samsung SSD 870 EVO 1TB               | 3        | 3.85%   |
| Samsung SSD 860 EVO 250GB             | 3        | 3.85%   |
| WDC WD30EFRX-68EUZN0 3TB              | 2        | 2.56%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB  | 2        | 2.56%   |
| Toshiba MQ04ABF100 1TB                | 2        | 2.56%   |
| Samsung SSD 980 PRO 1TB               | 2        | 2.56%   |
| Kingston SA2000M81000G 1TB            | 2        | 2.56%   |
| Crucial CT750MX300SSD1 752GB          | 2        | 2.56%   |
| WDC WDS250G2B0C-00PXH0 250GB          | 1        | 1.28%   |
| WDC WDS100T2B0A-00SM50 1TB            | 1        | 1.28%   |
| WDC WD60EFRX-68TGBN1 6TB              | 1        | 1.28%   |
| WDC WD5002ABYS-18B1B0 500GB           | 1        | 1.28%   |
| WDC WD40EZRZ-75GXCB0 4TB              | 1        | 1.28%   |
| WDC WD20EZRZ-00Z5HB0 2TB              | 1        | 1.28%   |
| WDC WD120EFAX-68UNTN0 12TB            | 1        | 1.28%   |
| WDC WD10SPZX-21Z10T0 1TB              | 1        | 1.28%   |
| WDC WD10JMVW-11AJGS3 1TB              | 1        | 1.28%   |
| WDC WD10EZEX-60WN4A0 1TB              | 1        | 1.28%   |
| WDC WD10EZEX-21WN4A0 1TB              | 1        | 1.28%   |
| WDC WD10EZEX-00RKKA0 1TB              | 1        | 1.28%   |
| WDC WD10EARX-00N0YB0 1TB              | 1        | 1.28%   |
| WDC WD10EALX-759BA1 1TB               | 1        | 1.28%   |
| Toshiba MG09ACA18TE 18TB              | 1        | 1.28%   |
| Toshiba MG06ACA800E 8TB               | 1        | 1.28%   |
| Toshiba DT01ACA200 2TB                | 1        | 1.28%   |
| SK hynix PC801 NVMe 2TB               | 1        | 1.28%   |
| SK hynix HFS128G39TND-N210A 128GB     | 1        | 1.28%   |
| Seagate ST8000VN0022-2EL112 8TB       | 1        | 1.28%   |
| Seagate ST5000LM000-2U8170 5TB        | 1        | 1.28%   |
| Seagate ST4000DM000-1F2168 4TB        | 1        | 1.28%   |
| Seagate ST3750640AS 752GB             | 1        | 1.28%   |
| Seagate ST32000641AS 2TB              | 1        | 1.28%   |
| Seagate ST3000DM007-1WY10G 3TB        | 1        | 1.28%   |
| Seagate ST3000DM001-1ER166 3TB        | 1        | 1.28%   |
| Seagate ST2000VN000-1H3164 2TB        | 1        | 1.28%   |
| Seagate ST1000DM003-1CH162 1TB        | 1        | 1.28%   |
| Samsung SSD 980 PRO with Heatsink 2TB | 1        | 1.28%   |
| Samsung SSD 980 1TB                   | 1        | 1.28%   |
| Samsung SSD 970 EVO Plus 500GB        | 1        | 1.28%   |
| Samsung SSD 970 EVO Plus 1TB          | 1        | 1.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 11       | 16     | 42.31%  |
| Seagate             | 8        | 20     | 30.77%  |
| Toshiba             | 5        | 9      | 19.23%  |
| Samsung Electronics | 1        | 2      | 3.85%   |
| HGST                | 1        | 2      | 3.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 8        | 12     | 32%     |
| Crucial             | 6        | 11     | 24%     |
| Kingston            | 3        | 4      | 12%     |
| A-DATA Technology   | 3        | 3      | 12%     |
| WDC                 | 1        | 2      | 4%      |
| SK hynix            | 1        | 1      | 4%      |
| Intel               | 1        | 1      | 4%      |
| GOODRAM             | 1        | 1      | 4%      |
| Apacer              | 1        | 1      | 4%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 24       | 36     | 38.1%   |
| HDD  | 20       | 49     | 31.75%  |
| NVMe | 19       | 24     | 30.16%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 32       | 85     | 62.75%  |
| NVMe | 19       | 24     | 37.25%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.51-1.0   | 17       | 25     | 34.69%  |
| 0.01-0.5   | 16       | 23     | 32.65%  |
| 1.01-2.0   | 5        | 7      | 10.2%   |
| 4.01-10.0  | 4        | 20     | 8.16%   |
| 2.01-3.0   | 3        | 4      | 6.12%   |
| 3.01-4.0   | 2        | 3      | 4.08%   |
| 10.01-20.0 | 2        | 3      | 4.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 16       | 28.57%  |
| 251-500        | 13       | 23.21%  |
| 1-20           | 8        | 14.29%  |
| 501-1000       | 7        | 12.5%   |
| 21-50          | 4        | 7.14%   |
| 2001-3000      | 3        | 5.36%   |
| More than 3000 | 2        | 3.57%   |
| 51-100         | 2        | 3.57%   |
| 1001-2000      | 1        | 1.79%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 38       | 66.67%  |
| 21-50          | 10       | 17.54%  |
| 101-250        | 2        | 3.51%   |
| 1001-2000      | 2        | 3.51%   |
| More than 3000 | 1        | 1.75%   |
| 251-500        | 1        | 1.75%   |
| 501-1000       | 1        | 1.75%   |
| 51-100         | 1        | 1.75%   |
| 0              | 1        | 1.75%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Samsung Electronics SSD 870 EVO 1TB | 3        | 5      | 33.33%  |
| WDC WD60EFRX-68TGBN1 6TB            | 1        | 3      | 11.11%  |
| WDC WD5002ABYS-18B1B0 500GB         | 1        | 1      | 11.11%  |
| Seagate ST1000DM003-1CH162 1TB      | 1        | 1      | 11.11%  |
| Samsung Electronics HD154UI 1.5TB   | 1        | 2      | 11.11%  |
| Kingston SHPM2280P2H-240G           | 1        | 1      | 11.11%  |
| Kingston SA400S37120G 120GB         | 1        | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 4        | 7      | 44.44%  |
| WDC                 | 2        | 4      | 22.22%  |
| Kingston            | 2        | 2      | 22.22%  |
| Seagate             | 1        | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 2        | 4      | 50%     |
| Seagate             | 1        | 1      | 25%     |
| Samsung Electronics | 1        | 2      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 4        | 7      | 50%     |
| HDD  | 4        | 7      | 50%     |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 37       | 92     | 82.22%  |
| Malfunc  | 7        | 14     | 15.56%  |
| Detected | 1        | 3      | 2.22%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| AMD                         | 24       | 33.33%  |
| Intel                       | 15       | 20.83%  |
| Samsung Electronics         | 8        | 11.11%  |
| Silicon Motion              | 6        | 8.33%   |
| SanDisk                     | 5        | 6.94%   |
| Kingston Technology Company | 4        | 5.56%   |
| Micron/Crucial Technology   | 2        | 2.78%   |
| Marvell Technology Group    | 2        | 2.78%   |
| ASMedia Technology          | 2        | 2.78%   |
| SK hynix                    | 1        | 1.39%   |
| Phison Electronics          | 1        | 1.39%   |
| Micron Technology           | 1        | 1.39%   |
| Broadcom / LSI              | 1        | 1.39%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 16       | 19.05%  |
| AMD 400 Series Chipset SATA Controller                                        | 7        | 8.33%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                               | 6        | 7.14%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 6        | 7.14%   |
| AMD 500 Series Chipset SATA Controller                                        | 5        | 5.95%   |
| Intel Comet Lake SATA AHCI Controller                                         | 4        | 4.76%   |
| Kingston Company A2000 NVMe SSD                                               | 3        | 3.57%   |
| SanDisk WD Blue SN550 NVMe SSD                                                | 2        | 2.38%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                    | 2        | 2.38%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 2        | 2.38%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                       | 2        | 2.38%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                    | 2        | 2.38%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                          | 2        | 2.38%   |
| SK hynix Platinum P41 NVMe Solid State Drive 2TB                              | 1        | 1.19%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 1        | 1.19%   |
| Samsung NVMe SSD Controller 980                                               | 1        | 1.19%   |
| Phison E12 NVMe Controller                                                    | 1        | 1.19%   |
| Micron/Crucial P2 NVMe PCIe SSD                                               | 1        | 1.19%   |
| Micron/Crucial P1 NVMe PCIe SSD                                               | 1        | 1.19%   |
| Micron NVMe Storage Controller                                                | 1        | 1.19%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                         | 1        | 1.19%   |
| Marvell Group 88SE9170 PCIe 2.0 x1 2-port SATA 6 Gb/s Controller              | 1        | 1.19%   |
| Kingston Company HyperX Predator PCIe AHCI SSD                                | 1        | 1.19%   |
| Intel SSD 660P Series                                                         | 1        | 1.19%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1        | 1.19%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                        | 1        | 1.19%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 1        | 1.19%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]   | 1        | 1.19%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]   | 1        | 1.19%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                          | 1        | 1.19%   |
| Broadcom / LSI SAS3008 PCI-Express Fusion-MPT SAS-3                           | 1        | 1.19%   |
| ASMedia ASM1166 Serial ATA Controller                                         | 1        | 1.19%   |
| ASMedia ASM1062 Serial ATA Controller                                         | 1        | 1.19%   |
| AMD X399 Series Chipset SATA Controller                                       | 1        | 1.19%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 1        | 1.19%   |
| AMD FCH SATA Controller [RAID Bottom]                                         | 1        | 1.19%   |
| AMD FCH RAID Controller                                                       | 1        | 1.19%   |
| Unknown                                                                       | 1        | 1.19%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 35       | 50.72%  |
| NVMe | 30       | 43.48%  |
| RAID | 2        | 2.9%    |
| SAS  | 1        | 1.45%   |
| IDE  | 1        | 1.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| AMD      | 25       | 43.86%  |
| Intel    | 13       | 22.81%  |
| ARM      | 11       | 19.3%   |
| Unknown  | 6        | 10.53%  |
| Research | 1        | 1.75%   |
| NXP      | 1        | 1.75%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| ARM Cortex-A55 r2p0                            | 7        | 12.28%  |
|                                                | 6        | 10.53%  |
| AMD Ryzen 5 5600G with Radeon Graphics         | 4        | 7.02%   |
| Intel Core i5-10400 CPU @ 2.90GHz              | 2        | 3.51%   |
| ARM Cortex-A53 r0p4                            | 2        | 3.51%   |
| AMD Ryzen 9 7950X 16-Core Processor            | 2        | 3.51%   |
| AMD Ryzen 9 5950X 16-Core Processor            | 2        | 3.51%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 2        | 3.51%   |
| Research Morello SoC r0p0                      | 1        | 1.75%   |
| NXP Cortex-A72                                 | 1        | 1.75%   |
| Intel Core i7-8750H CPU @ 2.20GHz              | 1        | 1.75%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 1        | 1.75%   |
| Intel Core i7-6700 CPU @ 3.40GHz               | 1        | 1.75%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 1        | 1.75%   |
| Intel Core i7-10700K CPU @ 3.80GHz             | 1        | 1.75%   |
| Intel Core i7-10700 CPU @ 2.90GHz              | 1        | 1.75%   |
| Intel Core i5-9600K CPU @ 3.70GHz              | 1        | 1.75%   |
| Intel Core i5-10500T CPU @ 2.30GHz             | 1        | 1.75%   |
| Intel Atom CPU E3827 @ 1.74GHz                 | 1        | 1.75%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz         | 1        | 1.75%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz         | 1        | 1.75%   |
| ARM Cortex-A72 r0p2                            | 1        | 1.75%   |
| ARM ARM1176 r0p7 (ECO: 0x00000000)             | 1        | 1.75%   |
| AMD Ryzen Threadripper 1950X 16-Core Processor | 1        | 1.75%   |
| AMD Ryzen Embedded V1202B with Radeon Vega Gfx | 1        | 1.75%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 1        | 1.75%   |
| AMD Ryzen 9 3950X 16-Core Processor            | 1        | 1.75%   |
| AMD Ryzen 7 5800X 8-Core Processor             | 1        | 1.75%   |
| AMD Ryzen 7 4800U with Radeon Graphics         | 1        | 1.75%   |
| AMD Ryzen 7 2700X Eight-Core Processor         | 1        | 1.75%   |
| AMD Ryzen 5 5600H with Radeon Graphics         | 1        | 1.75%   |
| AMD Ryzen 5 4600G with Radeon Graphics         | 1        | 1.75%   |
| AMD Ryzen 5 2600X Six-Core Processor           | 1        | 1.75%   |
| AMD Ryzen 5 2600 Six-Core Processor            | 1        | 1.75%   |
| AMD Ryzen 5 2400GE with Radeon Vega Graphics   | 1        | 1.75%   |
| AMD FX-8320E Eight-Core Processor              | 1        | 1.75%   |
| AMD EPYC 7601 32-Core Processor                | 1        | 1.75%   |
| AMD Athlon 3000G with Radeon Vega Graphics     | 1        | 1.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Other                  | 11       | 19.3%   |
| ARM Cortex             | 10       | 17.54%  |
| AMD Ryzen 5            | 9        | 15.79%  |
| AMD Ryzen 9            | 8        | 14.04%  |
| Intel Core i7          | 6        | 10.53%  |
| Intel Core i5          | 4        | 7.02%   |
| AMD Ryzen 7            | 3        | 5.26%   |
| Intel Atom             | 1        | 1.75%   |
| AMD Ryzen Threadripper | 1        | 1.75%   |
| AMD Ryzen Embedded     | 1        | 1.75%   |
| AMD FX                 | 1        | 1.75%   |
| AMD EPYC               | 1        | 1.75%   |
| AMD Athlon             | 1        | 1.75%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 18       | 32.14%  |
| 12      | 8        | 14.29%  |
| 6       | 7        | 12.5%   |
| 32      | 6        | 10.71%  |
| 8       | 5        | 8.93%   |
| 24      | 3        | 5.36%   |
| 16      | 3        | 5.36%   |
| 4       | 3        | 5.36%   |
| 2       | 2        | 3.57%   |
| 64      | 1        | 1.79%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 43       | 75.44%  |
| Unknown | 14       | 24.56%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 27       | 48.21%  |
| Unknown | 18       | 32.14%  |
| 2       | 11       | 19.64%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 22       | 39.29%  |
| Zen 3      | 9        | 16.07%  |
| Zen 2      | 5        | 8.93%   |
| CometLake  | 5        | 8.93%   |
| Zen+       | 4        | 7.14%   |
| Zen        | 4        | 7.14%   |
| KabyLake   | 3        | 5.36%   |
| Skylake    | 1        | 1.79%   |
| Silvermont | 1        | 1.79%   |
| Piledriver | 1        | 1.79%   |
| IvyBridge  | 1        | 1.79%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 19       | 44.19%  |
| Nvidia | 17       | 39.53%  |
| Intel  | 7        | 16.28%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]          | 5        | 11.36%  |
| Nvidia GP108 [GeForce GT 1030]                                        | 2        | 4.55%   |
| Nvidia GK208B [GeForce GT 710]                                        | 2        | 4.55%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                              | 2        | 4.55%   |
| AMD Renoir                                                            | 2        | 4.55%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]      | 2        | 4.55%   |
| AMD Raphael                                                           | 2        | 4.55%   |
| Nvidia TU117 [GeForce GTX 1650]                                       | 1        | 2.27%   |
| Nvidia TU116 [GeForce GTX 1660]                                       | 1        | 2.27%   |
| Nvidia GT218 [GeForce 210]                                            | 1        | 2.27%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                               | 1        | 2.27%   |
| Nvidia GP107GL [Quadro P620]                                          | 1        | 2.27%   |
| Nvidia GP107 [GeForce GTX 1050]                                       | 1        | 2.27%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                    | 1        | 2.27%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                   | 1        | 2.27%   |
| Nvidia GP104 [GeForce GTX 1080]                                       | 1        | 2.27%   |
| Nvidia GM206 [GeForce GTX 960]                                        | 1        | 2.27%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                     | 1        | 2.27%   |
| Nvidia GA104 [GeForce RTX 3060 Ti GDDR6X]                             | 1        | 2.27%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                    | 1        | 2.27%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                             | 1        | 2.27%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                | 1        | 2.27%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                             | 1        | 2.27%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                             | 1        | 2.27%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display          | 1        | 2.27%   |
| AMD RV630 XT [Radeon HD 2600 XT]                                      | 1        | 2.27%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]  | 1        | 2.27%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM] | 1        | 2.27%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX]                              | 1        | 2.27%   |
| AMD Navi 23 [Radeon RX 6650 XT / 6700S / 6800S]                       | 1        | 2.27%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                            | 1        | 2.27%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]               | 1        | 2.27%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                    | 1        | 2.27%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]   | 1        | 2.27%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| Other          | 18       | 32.14%  |
| 1 x AMD        | 15       | 26.79%  |
| 1 x Nvidia     | 14       | 25%     |
| 1 x Intel      | 4        | 7.14%   |
| Intel + Nvidia | 2        | 3.57%   |
| 2 x AMD        | 1        | 1.79%   |
| Intel + AMD    | 1        | 1.79%   |
| AMD + Nvidia   | 1        | 1.79%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 23       | 41.07%  |
| Unknown     | 18       | 32.14%  |
| Proprietary | 15       | 26.79%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 34       | 60.71%  |
| 1.01-2.0   | 7        | 12.5%   |
| 7.01-8.0   | 4        | 7.14%   |
| 3.01-4.0   | 4        | 7.14%   |
| 0.51-1.0   | 3        | 5.36%   |
| 5.01-6.0   | 1        | 1.79%   |
| 2.01-3.0   | 1        | 1.79%   |
| 8.01-16.0  | 1        | 1.79%   |
| 0.01-0.5   | 1        | 1.79%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Goldstar            | 5        | 17.86%  |
| Dell                | 5        | 17.86%  |
| LG Electronics      | 3        | 10.71%  |
| Sony                | 2        | 7.14%   |
| Samsung Electronics | 2        | 7.14%   |
| RTK                 | 2        | 7.14%   |
| BenQ                | 2        | 7.14%   |
| Philips             | 1        | 3.57%   |
| Lenovo              | 1        | 3.57%   |
| Idek Iiyama         | 1        | 3.57%   |
| Hewlett-Packard     | 1        | 3.57%   |
| Eizo                | 1        | 3.57%   |
| BOE                 | 1        | 3.57%   |
| AOC                 | 1        | 3.57%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| RTK WCS Display RTK1A1B 1920x1080 344x195mm 15.6-inch                  | 2        | 6.9%    |
| Sony TV SNY4B03 1920x1080 930x520mm 41.9-inch                          | 1        | 3.45%   |
| Sony TV  *30 SNY05D1 3840x2160 1660x930mm 74.9-inch                    | 1        | 3.45%   |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                       | 1        | 3.45%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1020x570mm 46.0-inch | 1        | 3.45%   |
| Philips PHL 273V7 PHLC156 1920x1080 600x340mm 27.2-inch                | 1        | 3.45%   |
| LG Electronics LCD Monitor LX20D 1600x1200                             | 1        | 3.45%   |
| LG Electronics LCD Monitor LG Ultra HD 11520x2160                      | 1        | 3.45%   |
| LG Electronics LCD Monitor LG Ultra HD                                 | 1        | 3.45%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                        | 1        | 3.45%   |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                  | 1        | 3.45%   |
| Idek Iiyama LCD Monitor PL2792UH 3840x2160                             | 1        | 3.45%   |
| Hewlett-Packard E233 HPN345F 1920x1080 510x290mm 23.1-inch             | 1        | 3.45%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch             | 1        | 3.45%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch             | 1        | 3.45%   |
| Goldstar 27GL650F GSM5B71 1920x1080 530x300mm 24.0-inch                | 1        | 3.45%   |
| Goldstar 27GK750F GSM770F 1920x1080 600x340mm 27.2-inch                | 1        | 3.45%   |
| Goldstar 23EA53 GSM59A8 1920x1080 510x290mm 23.1-inch                  | 1        | 3.45%   |
| Eizo FX2431 ENC2036 1920x1200 520x330mm 24.2-inch                      | 1        | 3.45%   |
| Dell U2719DC DEL417C 2560x1440 600x340mm 27.2-inch                     | 1        | 3.45%   |
| Dell U2518D DEL413C 2560x1440 550x310mm 24.9-inch                      | 1        | 3.45%   |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                      | 1        | 3.45%   |
| Dell LCD Monitor U2715H 2560x1440                                      | 1        | 3.45%   |
| Dell LCD Monitor S2422HG 1920x1080                                     | 1        | 3.45%   |
| BOE LCD Monitor BOE06E2 1920x1080 310x170mm 13.9-inch                  | 1        | 3.45%   |
| BenQ LCD Monitor BNQ78CA 1920x1080 600x340mm 27.2-inch                 | 1        | 3.45%   |
| BenQ GW2280 BNQ78E8 1920x1080 480x270mm 21.7-inch                      | 1        | 3.45%   |
| AOC U3277WB AOC3277 3840x2160 700x390mm 31.5-inch                      | 1        | 3.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 16       | 55.17%  |
| 3840x2160 (4K)    | 5        | 17.24%  |
| 2560x1440 (QHD)   | 3        | 10.34%  |
| 1920x1200 (WUXGA) | 2        | 6.9%    |
| 1600x1200         | 1        | 3.45%   |
| 11520x2160        | 1        | 3.45%   |
| Unknown           | 1        | 3.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 7        | 25%     |
| 27      | 6        | 21.43%  |
| 24      | 5        | 17.86%  |
| 23      | 2        | 7.14%   |
| 15      | 2        | 7.14%   |
| 74      | 1        | 3.57%   |
| 46      | 1        | 3.57%   |
| 41      | 1        | 3.57%   |
| 32      | 1        | 3.57%   |
| 21      | 1        | 3.57%   |
| 13      | 1        | 3.57%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 13       | 46.43%  |
| Unknown     | 7        | 25%     |
| 301-350     | 3        | 10.71%  |
| 701-800     | 1        | 3.57%   |
| 401-500     | 1        | 3.57%   |
| 1501-2000   | 1        | 3.57%   |
| 1001-1500   | 1        | 3.57%   |
| 901-1000    | 1        | 3.57%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 19       | 70.37%  |
| Unknown | 6        | 22.22%  |
| 16/10   | 2        | 7.41%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 7        | 25%     |
| 301-350        | 6        | 21.43%  |
| 201-250        | 5        | 17.86%  |
| 251-300        | 3        | 10.71%  |
| 101-110        | 2        | 7.14%   |
| 501-1000       | 2        | 7.14%   |
| More than 1000 | 1        | 3.57%   |
| 81-90          | 1        | 3.57%   |
| 351-500        | 1        | 3.57%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 12       | 44.44%  |
| Unknown | 7        | 25.93%  |
| 121-160 | 3        | 11.11%  |
| 161-240 | 2        | 7.41%   |
| 101-120 | 2        | 7.41%   |
| 1-50    | 1        | 3.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 28       | 50%     |
| 1     | 26       | 46.43%  |
| 2     | 2        | 3.57%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 30       | 44.78%  |
| Intel                           | 27       | 40.3%   |
| Qualcomm Atheros                | 2        | 2.99%   |
| Xiaomi                          | 1        | 1.49%   |
| TP-Link                         | 1        | 1.49%   |
| Ralink Technology               | 1        | 1.49%   |
| Qualcomm Atheros Communications | 1        | 1.49%   |
| Mellanox Technologies           | 1        | 1.49%   |
| MediaTek                        | 1        | 1.49%   |
| ASUSTek Computer                | 1        | 1.49%   |
| Arduino SA                      | 1        | 1.49%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 17       | 20.99%  |
| Realtek RTL8125 2.5GbE Controller                                             | 13       | 16.05%  |
| Intel Wi-Fi 6 AX200                                                           | 6        | 7.41%   |
| Intel I211 Gigabit Network Connection                                         | 6        | 7.41%   |
| Intel Ethernet Controller I225-V                                              | 5        | 6.17%   |
| Intel 82574L Gigabit Network Connection                                       | 4        | 4.94%   |
| Intel I210 Gigabit Network Connection                                         | 3        | 3.7%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                          | 1        | 1.23%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1        | 1.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 1.23%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1        | 1.23%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1        | 1.23%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 1        | 1.23%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 1.23%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1        | 1.23%   |
| Mellanox MT27500 Family [ConnectX-3]                                          | 1        | 1.23%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                 | 1        | 1.23%   |
| Intel Wireless-AC 9260                                                        | 1        | 1.23%   |
| Intel Wireless 8265 / 8275                                                    | 1        | 1.23%   |
| Intel Wireless 7265                                                           | 1        | 1.23%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 1        | 1.23%   |
| Intel I350 Gigabit Network Connection                                         | 1        | 1.23%   |
| Intel Ethernet Controller X550                                                | 1        | 1.23%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1        | 1.23%   |
| Intel Ethernet Connection (2) I219-V                                          | 1        | 1.23%   |
| Intel Ethernet Connection (14) I219-LM                                        | 1        | 1.23%   |
| Intel Ethernet Connection (11) I219-V                                         | 1        | 1.23%   |
| Intel Ethernet Connection (11) I219-LM                                        | 1        | 1.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1        | 1.23%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 1        | 1.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 1        | 1.23%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 1.23%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                                           | 1        | 1.23%   |
| Arduino SA Uno R3 (CDC ACM)                                                   | 1        | 1.23%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 13       | 59.09%  |
| Realtek Semiconductor           | 2        | 9.09%   |
| Qualcomm Atheros                | 2        | 9.09%   |
| TP-Link                         | 1        | 4.55%   |
| Ralink Technology               | 1        | 4.55%   |
| Qualcomm Atheros Communications | 1        | 4.55%   |
| MediaTek                        | 1        | 4.55%   |
| ASUSTek Computer                | 1        | 4.55%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                           | 6        | 27.27%  |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1        | 4.55%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 4.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1        | 4.55%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1        | 4.55%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 1        | 4.55%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 4.55%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1        | 4.55%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                 | 1        | 4.55%   |
| Intel Wireless-AC 9260                                                        | 1        | 4.55%   |
| Intel Wireless 8265 / 8275                                                    | 1        | 4.55%   |
| Intel Wireless 7265                                                           | 1        | 4.55%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 1        | 4.55%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1        | 4.55%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 1        | 4.55%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 1        | 4.55%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                                           | 1        | 4.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 27       | 52.94%  |
| Intel                 | 23       | 45.1%   |
| Xiaomi                | 1        | 1.96%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 17       | 30.36%  |
| Realtek RTL8125 2.5GbE Controller                                             | 12       | 21.43%  |
| Intel I211 Gigabit Network Connection                                         | 6        | 10.71%  |
| Intel Ethernet Controller I225-V                                              | 5        | 8.93%   |
| Intel 82574L Gigabit Network Connection                                       | 4        | 7.14%   |
| Intel I210 Gigabit Network Connection                                         | 3        | 5.36%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                          | 1        | 1.79%   |
| Intel I350 Gigabit Network Connection                                         | 1        | 1.79%   |
| Intel Ethernet Controller X550                                                | 1        | 1.79%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1        | 1.79%   |
| Intel Ethernet Connection (2) I219-V                                          | 1        | 1.79%   |
| Intel Ethernet Connection (14) I219-LM                                        | 1        | 1.79%   |
| Intel Ethernet Connection (11) I219-V                                         | 1        | 1.79%   |
| Intel Ethernet Connection (11) I219-LM                                        | 1        | 1.79%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 1.79%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 45       | 65.22%  |
| WiFi     | 21       | 30.43%  |
| Unknown  | 2        | 2.9%    |
| Modem    | 1        | 1.45%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 41       | 87.23%  |
| WiFi     | 6        | 12.77%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 19       | 33.93%  |
| 2     | 18       | 32.14%  |
| 0     | 10       | 17.86%  |
| 3     | 5        | 8.93%   |
| 4     | 3        | 5.36%   |
| 7     | 1        | 1.79%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 49       | 87.5%   |
| Yes  | 7        | 12.5%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 10       | 71.43%  |
| IMC Networks            | 1        | 7.14%   |
| Foxconn / Hon Hai       | 1        | 7.14%   |
| Cambridge Silicon Radio | 1        | 7.14%   |
| Broadcom                | 1        | 7.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 4        | 28.57%  |
| Intel Bluetooth wireless interface                  | 2        | 14.29%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 7.14%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 7.14%   |
| Intel AX210 Bluetooth                               | 1        | 7.14%   |
| Intel AX201 Bluetooth                               | 1        | 7.14%   |
| IMC Networks Realtek Bluetooth Adapter              | 1        | 7.14%   |
| Foxconn / Hon Hai RZ616 Bluetooth Adapter           | 1        | 7.14%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 7.14%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 7.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| AMD                     | 26       | 40%     |
| Nvidia                  | 17       | 26.15%  |
| Intel                   | 11       | 16.92%  |
| C-Media Electronics     | 2        | 3.08%   |
| Yamaha                  | 1        | 1.54%   |
| RODE Microphones        | 1        | 1.54%   |
| JMTek                   | 1        | 1.54%   |
| GN Netcom               | 1        | 1.54%   |
| Creative Labs           | 1        | 1.54%   |
| Blue Microphones        | 1        | 1.54%   |
| AudioQuest              | 1        | 1.54%   |
| ASUSTek Computer        | 1        | 1.54%   |
| AKAI  Professional M.I. | 1        | 1.54%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                           | Desktops | Percent |
|-------------------------------------------------------------------------------------------------|----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                          | 10       | 12.5%   |
| AMD Renoir Radeon High Definition Audio Controller                                              | 7        | 8.75%   |
| AMD Starship/Matisse HD Audio Controller                                                        | 6        | 7.5%    |
| Nvidia GP107GL High Definition Audio Controller                                                 | 4        | 5%      |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                             | 4        | 5%      |
| Intel Comet Lake PCH cAVS                                                                       | 3        | 3.75%   |
| Intel Cannon Lake PCH cAVS                                                                      | 3        | 3.75%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                             | 3        | 3.75%   |
| Nvidia GP108 High Definition Audio Controller                                                   | 2        | 2.5%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                           | 2        | 2.5%    |
| AMD Rembrandt Radeon High Definition Audio Controller                                           | 2        | 2.5%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                         | 2        | 2.5%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                         | 2        | 2.5%    |
| Yamaha Steinberg UR12                                                                           | 1        | 1.25%   |
| RODE Microphones RODE AI-1                                                                      | 1        | 1.25%   |
| Nvidia TU116 High Definition Audio Controller                                                   | 1        | 1.25%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                  | 1        | 1.25%   |
| Nvidia High Definition Audio Controller                                                         | 1        | 1.25%   |
| Nvidia GP106 High Definition Audio Controller                                                   | 1        | 1.25%   |
| Nvidia GP104 High Definition Audio Controller                                                   | 1        | 1.25%   |
| Nvidia GM206 High Definition Audio Controller                                                   | 1        | 1.25%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                   | 1        | 1.25%   |
| Nvidia GA104 High Definition Audio Controller                                                   | 1        | 1.25%   |
| Nvidia GA102 High Definition Audio Controller                                                   | 1        | 1.25%   |
| JMTek Lioncast USB Gaming Headset                                                               | 1        | 1.25%   |
| Intel Tiger Lake-H HD Audio Controller                                                          | 1        | 1.25%   |
| Intel HD Graphics SGPC                                                                          | 1        | 1.25%   |
| Intel Comet Lake PCH-V cAVS                                                                     | 1        | 1.25%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                      | 1        | 1.25%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 1        | 1.25%   |
| GN Netcom Jabra SPEAK 410 USB                                                                   | 1        | 1.25%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 1        | 1.25%   |
| C-Media Electronics USB PnP Audio Device                                                        | 1        | 1.25%   |
| C-Media Electronics CM108 Audio Controller                                                      | 1        | 1.25%   |
| Blue Microphones Yeti Stereo Microphone                                                         | 1        | 1.25%   |
| AudioQuest DragonFly                                                                            | 1        | 1.25%   |
| ASUSTek Computer Realtek USB Audio                                                              | 1        | 1.25%   |
| AMD SBx00 Azalia (Intel HDA)                                                                    | 1        | 1.25%   |
| AMD RV630 HDMI Audio [Radeon HD 2600 PRO/XT / HD 3610]                                          | 1        | 1.25%   |
| AMD Navi 31 [Radeon RX 7000 HDMI Audio]                                                         | 1        | 1.25%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 9        | 21.43%  |
| Corsair             | 6        | 14.29%  |
| SK hynix            | 4        | 9.52%   |
| Samsung Electronics | 4        | 9.52%   |
| Micron Technology   | 4        | 9.52%   |
| Crucial             | 4        | 9.52%   |
| Unknown             | 3        | 7.14%   |
| G.Skill             | 2        | 4.76%   |
| Transcend           | 1        | 2.38%   |
| Team                | 1        | 2.38%   |
| Smart               | 1        | 2.38%   |
| Golden Empire       | 1        | 2.38%   |
| A-DATA Technology   | 1        | 2.38%   |
| Unknown             | 1        | 2.38%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Corsair RAM CMK32GX4M2D3200C16 16GB DIMM DDR4 3200MT/s   | 2        | 4.26%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                | 1        | 2.13%   |
| Unknown RAM 3000 C16 Series 4096MB DIMM DDR4 2933MT/s    | 1        | 2.13%   |
| Unknown RAM 2G-08-10-12-1333 2GB DIMM DDR3 1333MT/s      | 1        | 2.13%   |
| Transcend RAM JM2666HLE-32G 32GB DIMM DDR4 2666MT/s      | 1        | 2.13%   |
| Team RAM TEAMGROUP-UD4-4133 8GB DIMM DDR4 4133MT/s       | 1        | 2.13%   |
| Smart RAM Module 8GB DIMM DDR4 2667MT/s                  | 1        | 2.13%   |
| SK hynix RAM HMAA4GU6CJR8N-XN 32GB DIMM DDR4 3200MT/s    | 1        | 2.13%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s  | 1        | 2.13%   |
| SK hynix RAM HMA82GR7JJR8N-VK 16GB DIMM DDR4 2667MT/s    | 1        | 2.13%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s   | 1        | 2.13%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s   | 1        | 2.13%   |
| Samsung RAM M393A2K40CB2-CTD 16GB DIMM DDR4 2666MT/s     | 1        | 2.13%   |
| Samsung RAM M393A2K40BB2-CTD 16GB DIMM DDR4 2667MT/s     | 1        | 2.13%   |
| Samsung RAM M378A4G43MB1-CTD 32GB DIMM DDR4 2666MT/s     | 1        | 2.13%   |
| Samsung RAM FRD4AA8Z3Z1ABZZ02 16GB DIMM DDR4 2667MT/s    | 1        | 2.13%   |
| Micron RAM 36ASF2G72PZ-2G6E1 16GB DIMM DDR4 2666MT/s     | 1        | 2.13%   |
| Micron RAM 18ASF4G72AZ-3G2B1 32GB DIMM DDR4 3200MT/s     | 1        | 2.13%   |
| Micron RAM 18ASF2G72PZ-2G6D1 16GB DIMM DDR4 2666MT/s     | 1        | 2.13%   |
| Micron RAM 18ASF2G72PDZ-2G6D1 16GB DIMM DDR4 2666MT/s    | 1        | 2.13%   |
| Micron RAM 16ATF2G64HZ-2G6J1 16GB SODIMM DDR4 2667MT/s   | 1        | 2.13%   |
| Micron RAM 16ATF2G64AZ-3G2J1 16GB DIMM DDR4 3200MT/s     | 1        | 2.13%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s   | 1        | 2.13%   |
| Kingston RAM KHX2933C15D4/8GX 8GB DIMM DDR4 2400MT/s     | 1        | 2.13%   |
| Kingston RAM KHX2666C16D4/16GX 16GB DIMM DDR4 2667MT/s   | 1        | 2.13%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 2666MT/s      | 1        | 2.13%   |
| Kingston RAM KHX2133C14/16G 16GB DIMM DDR4 2133MT/s      | 1        | 2.13%   |
| Kingston RAM KHX1600C10D3/ 8GB DIMM DDR3 1866MT/s        | 1        | 2.13%   |
| Kingston RAM KF556C40-32 32GB DIMM DDR5 5200MT/s         | 1        | 2.13%   |
| Kingston RAM 99P5700-016.A00G 16GB SODIMM DDR4 3200MT/s  | 1        | 2.13%   |
| Kingston RAM 9965745-020.A00G 32GB DIMM DDR4 3200MT/s    | 1        | 2.13%   |
| Kingston RAM 9965745-017.A00G 16GB DIMM DDR4 3200MT/s    | 1        | 2.13%   |
| Kingston RAM 9905713-030.A00G 8GB DIMM DDR4 2666MT/s     | 1        | 2.13%   |
| Golden Empire RAM D4U0830160B 8GB DIMM DDR4 2400MT/s     | 1        | 2.13%   |
| G.Skill RAM F4-3200C16-32GTZN 32GB DIMM DDR4 3200MT/s    | 1        | 2.13%   |
| G.Skill RAM F4-2400C17-8GNT 8GB DIMM DDR4 2400MT/s       | 1        | 2.13%   |
| Crucial RAM CT16G4DFD832A.C16FP 16GB DIMM DDR4 3200MT/s  | 1        | 2.13%   |
| Crucial RAM BL8G24C16U4B.8FB 8GB DIMM DDR4 2400MT/s      | 1        | 2.13%   |
| Crucial RAM BL16G36C16U4RL.M16FE 16GB DIMM DDR4 3600MT/s | 1        | 2.13%   |
| Crucial RAM BL16G36C16U4B.M8FB1 16GB DIMM DDR4 3600MT/s  | 1        | 2.13%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 33       | 86.84%  |
| DDR3 | 3        | 7.89%   |
| DDR5 | 2        | 5.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 33       | 86.84%  |
| SODIMM | 5        | 13.16%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 15       | 38.46%  |
| 8192  | 12       | 30.77%  |
| 32768 | 10       | 25.64%  |
| 4096  | 1        | 2.56%   |
| 2048  | 1        | 2.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 14       | 34.15%  |
| 2667  | 7        | 17.07%  |
| 2666  | 5        | 12.2%   |
| 2400  | 3        | 7.32%   |
| 3600  | 2        | 4.88%   |
| 2133  | 2        | 4.88%   |
| 5200  | 1        | 2.44%   |
| 4800  | 1        | 2.44%   |
| 4133  | 1        | 2.44%   |
| 3000  | 1        | 2.44%   |
| 2933  | 1        | 2.44%   |
| 1866  | 1        | 2.44%   |
| 1600  | 1        | 2.44%   |
| 1333  | 1        | 2.44%   |

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


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Logitech        | 6        | 54.55%  |
| Microdia        | 3        | 27.27%  |
| Trust           | 1        | 9.09%   |
| Aveo Technology | 1        | 9.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Microdia HP Integrated Webcam | 2        | 18.18%  |
| Logitech C920 PRO HD Webcam   | 2        | 18.18%  |
| Trust Canyon CNS-CWC6 Webcam  | 1        | 9.09%   |
| Microdia USB 2.0 Camera       | 1        | 9.09%   |
| Logitech Webcam C270          | 1        | 9.09%   |
| Logitech Webcam C170          | 1        | 9.09%   |
| Logitech C505 HD Webcam       | 1        | 9.09%   |
| Logitech BRIO Ultra HD Webcam | 1        | 9.09%   |
| Aveo USB2.0 Camera            | 1        | 9.09%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| FocalTech Systems | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| FocalTech Systems Fingerprint Reader | 1        | 100%    |

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


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 31       | 55.36%  |
| 1     | 15       | 26.79%  |
| 2     | 5        | 8.93%   |
| 4     | 3        | 5.36%   |
| 3     | 2        | 3.57%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 13       | 36.11%  |
| Net/wireless             | 7        | 19.44%  |
| Bluetooth                | 5        | 13.89%  |
| Sound                    | 3        | 8.33%   |
| Network                  | 3        | 8.33%   |
| Net/ethernet             | 3        | 8.33%   |
| Storage/raid             | 1        | 2.78%   |
| Fingerprint reader       | 1        | 2.78%   |

