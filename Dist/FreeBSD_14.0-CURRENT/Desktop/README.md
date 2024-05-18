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

Total: 74

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| SolidRun      | CEX7 Platform               | [4d51e18ce4](https://bsd-hardware.info/?probe=4d51e18ce4) | Aug 25, 2023 |
| MSI           | A520M-A PRO                 | [cc946b2a89](https://bsd-hardware.info/?probe=cc946b2a89) | Aug 15, 2023 |
| ASRock        | Z690 PG Riptide             | [813e46e924](https://bsd-hardware.info/?probe=813e46e924) | Jul 10, 2023 |
| ASRock        | Z690 PG Riptide             | [364cf5800b](https://bsd-hardware.info/?probe=364cf5800b) | Jul 06, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [705c750691](https://bsd-hardware.info/?probe=705c750691) | Jun 17, 2023 |
| Dell          | 053CWD A00                  | [7a5418ac7e](https://bsd-hardware.info/?probe=7a5418ac7e) | Jun 16, 2023 |
| Unknown       | Unknown                     | [6b4f214b72](https://bsd-hardware.info/?probe=6b4f214b72) | Jun 15, 2023 |
| Unknown       | Unknown                     | [615e7cbf52](https://bsd-hardware.info/?probe=615e7cbf52) | Jun 15, 2023 |
| Unknown       | Unknown                     | [8357f0f72e](https://bsd-hardware.info/?probe=8357f0f72e) | Jun 15, 2023 |
| Unknown       | Unknown                     | [f41e1f2b83](https://bsd-hardware.info/?probe=f41e1f2b83) | Jun 14, 2023 |
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
| amd64 | 42       | 67.74%  |
| arm64 | 17       | 27.42%  |
| arm   | 2        | 3.23%   |
| riscv | 1        | 1.61%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| Console  | 29       | 46.03%  |
| KDE5     | 18       | 28.57%  |
| XFCE     | 5        | 7.94%   |
| Openbox  | 3        | 4.76%   |
| i3       | 2        | 3.17%   |
| GNOME    | 2        | 3.17%   |
| TWM      | 1        | 1.59%   |
| spectrwm | 1        | 1.59%   |
| MATE     | 1        | 1.59%   |
| LXQt     | 1        | 1.59%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 35       | 55.56%  |
| Console | 26       | 41.27%  |
| Wayland | 2        | 3.17%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 39       | 61.9%   |
| SDDM    | 11       | 17.46%  |
| SLiM    | 5        | 7.94%   |
| GDM     | 4        | 6.35%   |
| XDM     | 2        | 3.17%   |
| Ly      | 1        | 1.59%   |
| LightDM | 1        | 1.59%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| C       | 30       | 48.39%  |
| en_US   | 15       | 24.19%  |
| Unknown | 5        | 8.06%   |
| de_DE   | 4        | 6.45%   |
| uk_UA   | 3        | 4.84%   |
| sv_SE   | 1        | 1.61%   |
| ru_RU   | 1        | 1.61%   |
| pl_PL   | 1        | 1.61%   |
| en_CA   | 1        | 1.61%   |
| de_CH   | 1        | 1.61%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 56       | 90.32%  |
| BIOS | 6        | 9.68%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Zfs  | 41       | 66.13%  |
| Ufs  | 21       | 33.87%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 58       | 93.55%  |
| MBR  | 4        | 6.45%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Unknown                 | 17       | 27.42%  |
| ASUSTek Computer        | 12       | 19.35%  |
| Gigabyte Technology     | 9        | 14.52%  |
| ASRock                  | 7        | 11.29%  |
| MSI                     | 5        | 8.06%   |
| Dell                    | 3        | 4.84%   |
| Beckhoff Automation     | 2        | 3.23%   |
| SolidRun                | 1        | 1.61%   |
| Raspberry Pi Foundation | 1        | 1.61%   |
| pine64                  | 1        | 1.61%   |
| khadas                  | 1        | 1.61%   |
| Hewlett-Packard         | 1        | 1.61%   |
| friendlyelec            | 1        | 1.61%   |
| ASRockRack              | 1        | 1.61%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 17       | 27.42%  |
| ASRock X570 Phantom Gaming 4       | 2        | 3.23%   |
| SolidRun CEX7 Platform             | 1        | 1.61%   |
| RPi rpi                            | 1        | 1.61%   |
| pine64 pinebook-pro-rk3399         | 1        | 1.61%   |
| MSI MS-7C79                        | 1        | 1.61%   |
| MSI MS-7C75                        | 1        | 1.61%   |
| MSI MS-7B89                        | 1        | 1.61%   |
| MSI MS-7B86                        | 1        | 1.61%   |
| MSI 520A5GE                        | 1        | 1.61%   |
| khadas edge-v                      | 1        | 1.61%   |
| HP EliteDesk 800 G4 SFF            | 1        | 1.61%   |
| Gigabyte X670E AORUS MASTER        | 1        | 1.61%   |
| Gigabyte X570 AORUS MASTER         | 1        | 1.61%   |
| Gigabyte X570 AORUS ELITE          | 1        | 1.61%   |
| Gigabyte X399 DESIGNARE EX         | 1        | 1.61%   |
| Gigabyte H170-D3HP                 | 1        | 1.61%   |
| Gigabyte B550I AORUS PRO AX        | 1        | 1.61%   |
| Gigabyte B450M S2H                 | 1        | 1.61%   |
| Gigabyte B450M DS3H                | 1        | 1.61%   |
| Gigabyte 970A-UD3P                 | 1        | 1.61%   |
| friendlyelec nanopi-m4             | 1        | 1.61%   |
| Dell Vostro 3681                   | 1        | 1.61%   |
| Dell OptiPlex 5090                 | 1        | 1.61%   |
| Dell OptiPlex 5080                 | 1        | 1.61%   |
| Beckhoff Automation CX2033-0185    | 1        | 1.61%   |
| Beckhoff Automation CBxx63         | 1        | 1.61%   |
| ASUS TUF GAMING B550-PLUS          | 1        | 1.61%   |
| ASUS ROG STRIX X670E-F GAMING WIFI | 1        | 1.61%   |
| ASUS ROG STRIX X570-E GAMING       | 1        | 1.61%   |
| ASUS ROG STRIX B550-I GAMING       | 1        | 1.61%   |
| ASUS PRIME Z590-A                  | 1        | 1.61%   |
| ASUS PRIME Z390-P                  | 1        | 1.61%   |
| ASUS PRIME X570-PRO                | 1        | 1.61%   |
| ASUS PRIME H410M-K                 | 1        | 1.61%   |
| ASUS PRIME B550-PLUS               | 1        | 1.61%   |
| ASUS PRIME B450M-GAMING/BR         | 1        | 1.61%   |
| ASUS PRIME B450M-A                 | 1        | 1.61%   |
| ASUS P8H77-M PRO                   | 1        | 1.61%   |
| ASRockRack EPYCD8-2T               | 1        | 1.61%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| Unknown                         | 17       | 27.42%  |
| ASUS PRIME                      | 7        | 11.29%  |
| ASUS ROG                        | 3        | 4.84%   |
| Gigabyte X570                   | 2        | 3.23%   |
| Gigabyte B450M                  | 2        | 3.23%   |
| Dell OptiPlex                   | 2        | 3.23%   |
| ASRock X570                     | 2        | 3.23%   |
| SolidRun CEX7                   | 1        | 1.61%   |
| RPi rpi                         | 1        | 1.61%   |
| pine64 pinebook-pro-rk3399      | 1        | 1.61%   |
| MSI MS-7C79                     | 1        | 1.61%   |
| MSI MS-7C75                     | 1        | 1.61%   |
| MSI MS-7B89                     | 1        | 1.61%   |
| MSI MS-7B86                     | 1        | 1.61%   |
| MSI 520A5GE                     | 1        | 1.61%   |
| khadas edge-v                   | 1        | 1.61%   |
| HP EliteDesk                    | 1        | 1.61%   |
| Gigabyte X670E                  | 1        | 1.61%   |
| Gigabyte X399                   | 1        | 1.61%   |
| Gigabyte H170-D3HP              | 1        | 1.61%   |
| Gigabyte B550I                  | 1        | 1.61%   |
| Gigabyte 970A-UD3P              | 1        | 1.61%   |
| friendlyelec nanopi-m4          | 1        | 1.61%   |
| Dell Vostro                     | 1        | 1.61%   |
| Beckhoff Automation CX2033-0185 | 1        | 1.61%   |
| Beckhoff Automation CBxx63      | 1        | 1.61%   |
| ASUS TUF                        | 1        | 1.61%   |
| ASUS P8H77-M                    | 1        | 1.61%   |
| ASRockRack EPYCD8-2T            | 1        | 1.61%   |
| ASRock Z690                     | 1        | 1.61%   |
| ASRock B550                     | 1        | 1.61%   |
| ASRock B450                     | 1        | 1.61%   |
| ASRock A520M-ITX                | 1        | 1.61%   |
| ASRock 4X4                      | 1        | 1.61%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 15       | 24.19%  |
| 2021    | 12       | 19.35%  |
| 2020    | 11       | 17.74%  |
| 2019    | 7        | 11.29%  |
| 2018    | 5        | 8.06%   |
| 2023    | 4        | 6.45%   |
| 2022    | 4        | 6.45%   |
| 2017    | 1        | 1.61%   |
| 2016    | 1        | 1.61%   |
| 2012    | 1        | 1.61%   |
| 2011    | 1        | 1.61%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 62       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 62       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 64.01-256.0 | 15       | 24.19%  |
| 16.01-24.0  | 15       | 24.19%  |
| 32.01-64.0  | 10       | 16.13%  |
| 3.01-4.0    | 7        | 11.29%  |
| 4.01-8.0    | 5        | 8.06%   |
| 8.01-16.0   | 5        | 8.06%   |
| 0.51-1.0    | 4        | 6.45%   |
| 0.01-0.5    | 1        | 1.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 17       | 27.42%  |
| 0.01-0.5    | 17       | 27.42%  |
| 0.51-1.0    | 13       | 20.97%  |
| 2.01-3.0    | 7        | 11.29%  |
| 3.01-4.0    | 3        | 4.84%   |
| 0           | 2        | 3.23%   |
| 4.01-8.0    | 1        | 1.61%   |
| 64.01-256.0 | 1        | 1.61%   |
| 16.01-24.0  | 1        | 1.61%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 0      | 21       | 33.87%  |
| 1      | 14       | 22.58%  |
| 2      | 9        | 14.52%  |
| 3      | 8        | 12.9%   |
| 6      | 3        | 4.84%   |
| 4      | 3        | 4.84%   |
| 5      | 2        | 3.23%   |
| 15     | 1        | 1.61%   |
| 7      | 1        | 1.61%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 51       | 82.26%  |
| Yes       | 11       | 17.74%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 49       | 79.03%  |
| No        | 13       | 20.97%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 41       | 66.13%  |
| Yes       | 21       | 33.87%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 48       | 76.19%  |
| Yes       | 15       | 23.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Russia       | 16       | 25.81%  |
| Germany      | 8        | 12.9%   |
| USA          | 6        | 9.68%   |
| UK           | 5        | 8.06%   |
| Ukraine      | 4        | 6.45%   |
| Brazil       | 4        | 6.45%   |
| Poland       | 3        | 4.84%   |
| Romania      | 2        | 3.23%   |
| Japan        | 2        | 3.23%   |
| Canada       | 2        | 3.23%   |
| Turkey       | 1        | 1.61%   |
| Switzerland  | 1        | 1.61%   |
| Sweden       | 1        | 1.61%   |
| Saudi Arabia | 1        | 1.61%   |
| Portugal     | 1        | 1.61%   |
| Netherlands  | 1        | 1.61%   |
| France       | 1        | 1.61%   |
| Denmark      | 1        | 1.61%   |
| Czechia      | 1        | 1.61%   |
| Austria      | 1        | 1.61%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                        | Desktops | Percent |
|-----------------------------|----------|---------|
| Krasnodar                   | 7        | 11.11%  |
| St Petersburg               | 4        | 6.35%   |
| Moscow                      | 4        | 6.35%   |
| Kyiv                        | 3        | 4.76%   |
| Rio de Janeiro              | 2        | 3.17%   |
| Rietberg                    | 2        | 3.17%   |
| Egham                       | 2        | 3.17%   |
| Choroszcz                   | 2        | 3.17%   |
| Cambridge                   | 2        | 3.17%   |
| ЕЊta-ku                   | 1        | 1.59%   |
| Zurich                      | 1        | 1.59%   |
| Zaporizhzhya                | 1        | 1.59%   |
| Vila Real de Santo António | 1        | 1.59%   |
| Stolberg                    | 1        | 1.59%   |
| St. Albert                  | 1        | 1.59%   |
| Sollentuna                  | 1        | 1.59%   |
| Satu Mare                   | 1        | 1.59%   |
| Santa Monica                | 1        | 1.59%   |
| Ruislip                     | 1        | 1.59%   |
| Riyadh                      | 1        | 1.59%   |
| Radzionkow                  | 1        | 1.59%   |
| Orenburg                    | 1        | 1.59%   |
| Northeim                    | 1        | 1.59%   |
| Ludwigsburg                 | 1        | 1.59%   |
| Lake Forest                 | 1        | 1.59%   |
| Kongens Lyngby              | 1        | 1.59%   |
| Jaboatao dos Guararapes     | 1        | 1.59%   |
| Istanbul                    | 1        | 1.59%   |
| Innisfil                    | 1        | 1.59%   |
| Graz                        | 1        | 1.59%   |
| Göttingen                  | 1        | 1.59%   |
| Fuchu                       | 1        | 1.59%   |
| Fremont                     | 1        | 1.59%   |
| Cordeiropolis               | 1        | 1.59%   |
| Cologne                     | 1        | 1.59%   |
| Claix                       | 1        | 1.59%   |
| Chicago                     | 1        | 1.59%   |
| Bunkyo-ku                   | 1        | 1.59%   |
| Brno                        | 1        | 1.59%   |
| Bessemer                    | 1        | 1.59%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 16       | 22     | 21.33%  |
| Samsung Electronics | 14       | 28     | 18.67%  |
| Seagate             | 9        | 21     | 12%     |
| Crucial             | 7        | 14     | 9.33%   |
| Kingston            | 6        | 7      | 8%      |
| Toshiba             | 5        | 9      | 6.67%   |
| Intel               | 4        | 4      | 5.33%   |
| A-DATA Technology   | 3        | 3      | 4%      |
| SK hynix            | 2        | 2      | 2.67%   |
| HGST                | 2        | 4      | 2.67%   |
| SPCC                | 1        | 1      | 1.33%   |
| PNY                 | 1        | 1      | 1.33%   |
| Phison              | 1        | 2      | 1.33%   |
| Micron Technology   | 1        | 2      | 1.33%   |
| GOODRAM             | 1        | 1      | 1.33%   |
| FORESEE             | 1        | 1      | 1.33%   |
| Apacer              | 1        | 1      | 1.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Samsung SSD 870 EVO 1TB              | 3        | 3.49%   |
| Samsung SSD 860 EVO 250GB            | 3        | 3.49%   |
| WDC WD30EFRX-68EUZN0 3TB             | 2        | 2.33%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 2        | 2.33%   |
| Toshiba MQ04ABF100 1TB               | 2        | 2.33%   |
| Samsung SSD 980 PRO 1TB              | 2        | 2.33%   |
| Samsung SSD 870 QVO 1TB              | 2        | 2.33%   |
| Kingston SA2000M81000G 1TB           | 2        | 2.33%   |
| Crucial CT750MX300SSD1 752GB         | 2        | 2.33%   |
| WDC WDS250G2B0C-00PXH0 250GB         | 1        | 1.16%   |
| WDC WDS100T2B0A-00SM50 1TB           | 1        | 1.16%   |
| WDC WD60EFRX-68TGBN1 6TB             | 1        | 1.16%   |
| WDC WD5002ABYS-18B1B0 500GB          | 1        | 1.16%   |
| WDC WD40EZRZ-75GXCB0 4TB             | 1        | 1.16%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 1        | 1.16%   |
| WDC WD2003FZEX-00SRLA0 2TB           | 1        | 1.16%   |
| WDC WD120EFAX-68UNTN0 12TB           | 1        | 1.16%   |
| WDC WD10SPZX-21Z10T0 1TB             | 1        | 1.16%   |
| WDC WD10JMVW-11AJGS3 1TB             | 1        | 1.16%   |
| WDC WD10EZEX-60WN4A0 1TB             | 1        | 1.16%   |
| WDC WD10EZEX-21WN4A0 1TB             | 1        | 1.16%   |
| WDC WD10EZEX-00RKKA0 1TB             | 1        | 1.16%   |
| WDC WD10EARX-00N0YB0 1TB             | 1        | 1.16%   |
| WDC WD10EALX-759BA1 1TB              | 1        | 1.16%   |
| Toshiba MG09ACA18TE 18TB             | 1        | 1.16%   |
| Toshiba MG06ACA800E 8TB              | 1        | 1.16%   |
| Toshiba DT01ACA200 2TB               | 1        | 1.16%   |
| SPCC Solid State Disk 240GB          | 1        | 1.16%   |
| SK hynix PC801 NVMe 2TB              | 1        | 1.16%   |
| SK hynix HFS128G39TND-N210A 128GB    | 1        | 1.16%   |
| Seagate ST8000VN0022-2EL112 8TB      | 1        | 1.16%   |
| Seagate ST5000LM000-2U8170 5TB       | 1        | 1.16%   |
| Seagate ST4000DM000-1F2168 4TB       | 1        | 1.16%   |
| Seagate ST3750640AS 752GB            | 1        | 1.16%   |
| Seagate ST32000641AS 2TB             | 1        | 1.16%   |
| Seagate ST3000DM007-1WY10G 3TB       | 1        | 1.16%   |
| Seagate ST3000DM001-1ER166 3TB       | 1        | 1.16%   |
| Seagate ST2000VN000-1H3164 2TB       | 1        | 1.16%   |
| Seagate ST2000DM008-2FR102 2TB       | 1        | 1.16%   |
| Seagate ST1000DM003-1CH162 1TB       | 1        | 1.16%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 17     | 41.38%  |
| Seagate             | 9        | 21     | 31.03%  |
| Toshiba             | 5        | 9      | 17.24%  |
| HGST                | 2        | 4      | 6.9%    |
| Samsung Electronics | 1        | 2      | 3.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 10       | 18     | 34.48%  |
| Crucial             | 6        | 11     | 20.69%  |
| Kingston            | 4        | 5      | 13.79%  |
| A-DATA Technology   | 3        | 3      | 10.34%  |
| WDC                 | 1        | 2      | 3.45%   |
| SPCC                | 1        | 1      | 3.45%   |
| SK hynix            | 1        | 1      | 3.45%   |
| Intel               | 1        | 1      | 3.45%   |
| GOODRAM             | 1        | 1      | 3.45%   |
| Apacer              | 1        | 1      | 3.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 28       | 44     | 40%     |
| HDD  | 22       | 53     | 31.43%  |
| NVMe | 20       | 26     | 28.57%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 36       | 97     | 64.29%  |
| NVMe | 20       | 26     | 35.71%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.51-1.0   | 18       | 26     | 32.73%  |
| 0.01-0.5   | 18       | 25     | 32.73%  |
| 1.01-2.0   | 6        | 9      | 10.91%  |
| 4.01-10.0  | 6        | 27     | 10.91%  |
| 2.01-3.0   | 3        | 4      | 5.45%   |
| 3.01-4.0   | 2        | 3      | 3.64%   |
| 10.01-20.0 | 2        | 3      | 3.64%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 18       | 29.03%  |
| 251-500        | 14       | 22.58%  |
| 1-20           | 8        | 12.9%   |
| 501-1000       | 8        | 12.9%   |
| 21-50          | 6        | 9.68%   |
| 2001-3000      | 3        | 4.84%   |
| More than 3000 | 2        | 3.23%   |
| 51-100         | 2        | 3.23%   |
| 1001-2000      | 1        | 1.61%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 43       | 68.25%  |
| 21-50          | 11       | 17.46%  |
| 101-250        | 2        | 3.17%   |
| 1001-2000      | 2        | 3.17%   |
| More than 3000 | 1        | 1.59%   |
| 251-500        | 1        | 1.59%   |
| 501-1000       | 1        | 1.59%   |
| 51-100         | 1        | 1.59%   |
| 0              | 1        | 1.59%   |

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
| Works    | 41       | 106    | 83.67%  |
| Malfunc  | 7        | 14     | 14.29%  |
| Detected | 1        | 3      | 2.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| AMD                         | 26       | 32.91%  |
| Intel                       | 17       | 21.52%  |
| Samsung Electronics         | 8        | 10.13%  |
| Silicon Motion              | 6        | 7.59%   |
| SanDisk                     | 5        | 6.33%   |
| Kingston Technology Company | 4        | 5.06%   |
| SK hynix                    | 2        | 2.53%   |
| Phison Electronics          | 2        | 2.53%   |
| Micron/Crucial Technology   | 2        | 2.53%   |
| Marvell Technology Group    | 2        | 2.53%   |
| ASMedia Technology          | 2        | 2.53%   |
| Micron Technology           | 1        | 1.27%   |
| MAXIO Technology (Hangzhou) | 1        | 1.27%   |
| Broadcom / LSI              | 1        | 1.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 16       | 17.58%  |
| AMD 400 Series Chipset SATA Controller                                        | 7        | 7.69%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers             | 6        | 6.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 6        | 6.59%   |
| AMD 500 Series Chipset SATA Controller                                        | 6        | 6.59%   |
| Intel Comet Lake SATA AHCI Controller                                         | 4        | 4.4%    |
| Kingston Company A2000 NVMe SSD SM2263EN                                      | 3        | 3.3%    |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                     | 2        | 2.2%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD          | 2        | 2.2%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 2        | 2.2%    |
| Phison E12 NVMe Controller                                                    | 2        | 2.2%    |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                              | 2        | 2.2%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                    | 2        | 2.2%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                          | 2        | 2.2%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                          | 2        | 2.2%    |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                            | 1        | 1.1%    |
| SK hynix BC511 NVMe SSD                                                       | 1        | 1.1%    |
| Sandisk WD PC SN540 / Green SN350 NVMe SSD 1 TB (DRAM-less)                   | 1        | 1.1%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 1        | 1.1%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                   | 1        | 1.1%    |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)          | 1        | 1.1%    |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                     | 1        | 1.1%    |
| Micron 2300 NVMe SSD [Santana]                                                | 1        | 1.1%    |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                      | 1        | 1.1%    |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                         | 1        | 1.1%    |
| Marvell Group 88SE9170 PCIe 2.0 x1 2-port SATA 6 Gb/s Controller              | 1        | 1.1%    |
| Kingston Company HyperX Predator PCIe AHCI SSD                                | 1        | 1.1%    |
| Intel SSD 660P Series                                                         | 1        | 1.1%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1        | 1.1%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                        | 1        | 1.1%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                            | 1        | 1.1%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 1        | 1.1%    |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]   | 1        | 1.1%    |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]   | 1        | 1.1%    |
| Broadcom / LSI SAS3008 PCI-Express Fusion-MPT SAS-3                           | 1        | 1.1%    |
| ASMedia ASM1166 Serial ATA Controller                                         | 1        | 1.1%    |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                 | 1        | 1.1%    |
| AMD X399 Series Chipset SATA Controller                                       | 1        | 1.1%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 1        | 1.1%    |
| AMD FCH SATA Controller [RAID Bottom]                                         | 1        | 1.1%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 39       | 51.32%  |
| NVMe | 33       | 43.42%  |
| RAID | 2        | 2.63%   |
| SAS  | 1        | 1.32%   |
| IDE  | 1        | 1.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| AMD      | 27       | 42.86%  |
| Intel    | 15       | 23.81%  |
| ARM      | 13       | 20.63%  |
| Unknown  | 6        | 9.52%   |
| Research | 1        | 1.59%   |
| NXP      | 1        | 1.59%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| ARM Cortex-A55 r2p0                            | 9        | 14.29%  |
|                                                | 6        | 9.52%   |
| AMD Ryzen 5 5600G with Radeon Graphics         | 5        | 7.94%   |
| Intel Core i5-10400 CPU @ 2.90GHz              | 3        | 4.76%   |
| ARM Cortex-A53 r0p4                            | 2        | 3.17%   |
| AMD Ryzen 9 7950X 16-Core Processor            | 2        | 3.17%   |
| AMD Ryzen 9 5950X 16-Core Processor            | 2        | 3.17%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 2        | 3.17%   |
| AMD Ryzen 7 2700X Eight-Core Processor         | 2        | 3.17%   |
| Research Morello SoC r0p0                      | 1        | 1.59%   |
| NXP Cortex-A72                                 | 1        | 1.59%   |
| Intel Core i7-8750H CPU @ 2.20GHz              | 1        | 1.59%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 1        | 1.59%   |
| Intel Core i7-6700 CPU @ 3.40GHz               | 1        | 1.59%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 1        | 1.59%   |
| Intel Core i7-10700K CPU @ 3.80GHz             | 1        | 1.59%   |
| Intel Core i7-10700 CPU @ 2.90GHz              | 1        | 1.59%   |
| Intel Core i5-9600K CPU @ 3.70GHz              | 1        | 1.59%   |
| Intel Core i5-10500T CPU @ 2.30GHz             | 1        | 1.59%   |
| Intel Atom CPU E3827 @ 1.74GHz                 | 1        | 1.59%   |
| Intel 12th Gen Core i3-12100                   | 1        | 1.59%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz         | 1        | 1.59%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz         | 1        | 1.59%   |
| ARM Cortex-A72 r0p2                            | 1        | 1.59%   |
| ARM ARM1176 r0p7 (ECO: 0x00000000)             | 1        | 1.59%   |
| AMD Ryzen Threadripper 1950X 16-Core Processor | 1        | 1.59%   |
| AMD Ryzen Embedded V1202B with Radeon Vega Gfx | 1        | 1.59%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 1        | 1.59%   |
| AMD Ryzen 9 3950X 16-Core Processor            | 1        | 1.59%   |
| AMD Ryzen 7 5800X 8-Core Processor             | 1        | 1.59%   |
| AMD Ryzen 7 4800U with Radeon Graphics         | 1        | 1.59%   |
| AMD Ryzen 5 5600H with Radeon Graphics         | 1        | 1.59%   |
| AMD Ryzen 5 4600G with Radeon Graphics         | 1        | 1.59%   |
| AMD Ryzen 5 2600X Six-Core Processor           | 1        | 1.59%   |
| AMD Ryzen 5 2600 Six-Core Processor            | 1        | 1.59%   |
| AMD Ryzen 5 2400GE with Radeon Vega Graphics   | 1        | 1.59%   |
| AMD FX-8320E Eight-Core Processor              | 1        | 1.59%   |
| AMD EPYC 7601 32-Core Processor                | 1        | 1.59%   |
| AMD Athlon 3000G with Radeon Vega Graphics     | 1        | 1.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Other                  | 12       | 19.05%  |
| ARM Cortex             | 12       | 19.05%  |
| AMD Ryzen 5            | 10       | 15.87%  |
| AMD Ryzen 9            | 8        | 12.7%   |
| Intel Core i7          | 6        | 9.52%   |
| Intel Core i5          | 5        | 7.94%   |
| AMD Ryzen 7            | 4        | 6.35%   |
| Intel Atom             | 1        | 1.59%   |
| AMD Ryzen Threadripper | 1        | 1.59%   |
| AMD Ryzen Embedded     | 1        | 1.59%   |
| AMD FX                 | 1        | 1.59%   |
| AMD EPYC               | 1        | 1.59%   |
| AMD Athlon             | 1        | 1.59%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 20       | 32.26%  |
| 12      | 9        | 14.52%  |
| 6       | 8        | 12.9%   |
| 32      | 6        | 9.68%   |
| 8       | 5        | 8.06%   |
| 16      | 4        | 6.45%   |
| 4       | 4        | 6.45%   |
| 24      | 3        | 4.84%   |
| 2       | 2        | 3.23%   |
| 64      | 1        | 1.61%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 47       | 74.6%   |
| Unknown | 16       | 25.4%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 29       | 46.77%  |
| Unknown | 20       | 32.26%  |
| 2       | 13       | 20.97%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 25       | 40.32%  |
| Zen 3      | 10       | 16.13%  |
| CometLake  | 6        | 9.68%   |
| Zen+       | 5        | 8.06%   |
| Zen 2      | 5        | 8.06%   |
| Zen        | 4        | 6.45%   |
| KabyLake   | 3        | 4.84%   |
| Skylake    | 1        | 1.61%   |
| Silvermont | 1        | 1.61%   |
| Piledriver | 1        | 1.61%   |
| IvyBridge  | 1        | 1.61%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 21       | 44.68%  |
| Nvidia | 17       | 36.17%  |
| Intel  | 9        | 19.15%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]          | 6        | 12.5%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                              | 3        | 6.25%   |
| Nvidia GP108 [GeForce GT 1030]                                        | 2        | 4.17%   |
| Nvidia GK208B [GeForce GT 710]                                        | 2        | 4.17%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]         | 2        | 4.17%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]      | 2        | 4.17%   |
| AMD Raphael                                                           | 2        | 4.17%   |
| Nvidia TU117 [GeForce GTX 1650]                                       | 1        | 2.08%   |
| Nvidia TU116 [GeForce GTX 1660]                                       | 1        | 2.08%   |
| Nvidia GT218 [GeForce 210]                                            | 1        | 2.08%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                               | 1        | 2.08%   |
| Nvidia GP107GL [Quadro P620]                                          | 1        | 2.08%   |
| Nvidia GP107 [GeForce GTX 1050]                                       | 1        | 2.08%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                    | 1        | 2.08%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                   | 1        | 2.08%   |
| Nvidia GP104 [GeForce GTX 1080]                                       | 1        | 2.08%   |
| Nvidia GM206 [GeForce GTX 960]                                        | 1        | 2.08%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                     | 1        | 2.08%   |
| Nvidia GA104 [GeForce RTX 3060 Ti GDDR6X]                             | 1        | 2.08%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                    | 1        | 2.08%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                             | 1        | 2.08%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                | 1        | 2.08%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                             | 1        | 2.08%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                             | 1        | 2.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display          | 1        | 2.08%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                             | 1        | 2.08%   |
| AMD RV630 XT [Radeon HD 2600 XT]                                      | 1        | 2.08%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]  | 1        | 2.08%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM] | 1        | 2.08%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900M]                        | 1        | 2.08%   |
| AMD Navi 23 [Radeon RX 6650 XT / 6700S / 6800S]                       | 1        | 2.08%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                            | 1        | 2.08%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]         | 1        | 2.08%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]               | 1        | 2.08%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                    | 1        | 2.08%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]   | 1        | 2.08%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| Other          | 20       | 32.26%  |
| 1 x AMD        | 17       | 27.42%  |
| 1 x Nvidia     | 14       | 22.58%  |
| 1 x Intel      | 6        | 9.68%   |
| Intel + Nvidia | 2        | 3.23%   |
| 2 x AMD        | 1        | 1.61%   |
| Intel + AMD    | 1        | 1.61%   |
| AMD + Nvidia   | 1        | 1.61%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 27       | 43.55%  |
| Unknown     | 20       | 32.26%  |
| Proprietary | 15       | 24.19%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 38       | 61.29%  |
| 1.01-2.0   | 7        | 11.29%  |
| 3.01-4.0   | 5        | 8.06%   |
| 7.01-8.0   | 4        | 6.45%   |
| 0.51-1.0   | 3        | 4.84%   |
| 8.01-16.0  | 2        | 3.23%   |
| 5.01-6.0   | 1        | 1.61%   |
| 2.01-3.0   | 1        | 1.61%   |
| 0.01-0.5   | 1        | 1.61%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Goldstar            | 6        | 19.35%  |
| Dell                | 5        | 16.13%  |
| LG Electronics      | 3        | 9.68%   |
| BenQ                | 3        | 9.68%   |
| Sony                | 2        | 6.45%   |
| Samsung Electronics | 2        | 6.45%   |
| RTK                 | 2        | 6.45%   |
| AOC                 | 2        | 6.45%   |
| Philips             | 1        | 3.23%   |
| Lenovo              | 1        | 3.23%   |
| Idek Iiyama         | 1        | 3.23%   |
| Hewlett-Packard     | 1        | 3.23%   |
| Eizo                | 1        | 3.23%   |
| BOE                 | 1        | 3.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| RTK WCS Display RTK1A1B 1920x1080 344x195mm 15.6-inch                  | 2        | 6.25%   |
| Sony TV SNY4B03 1920x1080 930x520mm 41.9-inch                          | 1        | 3.13%   |
| Sony TV  *30 SNY05D1 3840x2160 1660x930mm 74.9-inch                    | 1        | 3.13%   |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                       | 1        | 3.13%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1020x570mm 46.0-inch | 1        | 3.13%   |
| Philips PHL 273V7 PHLC156 1920x1080 600x340mm 27.2-inch                | 1        | 3.13%   |
| LG Electronics LCD Monitor LX20D 1600x1200                             | 1        | 3.13%   |
| LG Electronics LCD Monitor LG Ultra HD 11520x2160                      | 1        | 3.13%   |
| LG Electronics LCD Monitor LG Ultra HD                                 | 1        | 3.13%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                        | 1        | 3.13%   |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                  | 1        | 3.13%   |
| Idek Iiyama LCD Monitor PL2792UH 3840x2160                             | 1        | 3.13%   |
| Hewlett-Packard E233 HPN345F 1920x1080 510x290mm 23.1-inch             | 1        | 3.13%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch             | 1        | 3.13%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch             | 1        | 3.13%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch             | 1        | 3.13%   |
| Goldstar 27GL650F GSM5B71 1920x1080 530x300mm 24.0-inch                | 1        | 3.13%   |
| Goldstar 27GK750F GSM770F 1920x1080 600x340mm 27.2-inch                | 1        | 3.13%   |
| Goldstar 23EA53 GSM59A8 1920x1080 510x290mm 23.1-inch                  | 1        | 3.13%   |
| Eizo FX2431 ENC2036 1920x1200 520x330mm 24.2-inch                      | 1        | 3.13%   |
| Dell U2719DC DEL417C 2560x1440 600x340mm 27.2-inch                     | 1        | 3.13%   |
| Dell U2518D DEL413C 2560x1440 550x310mm 24.9-inch                      | 1        | 3.13%   |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                      | 1        | 3.13%   |
| Dell LCD Monitor U2715H 2560x1440                                      | 1        | 3.13%   |
| Dell LCD Monitor S2422HG 1920x1080                                     | 1        | 3.13%   |
| BOE LCD Monitor BOE06E2 1920x1080 310x170mm 13.9-inch                  | 1        | 3.13%   |
| BenQ PD3200Q BNQ8026 2560x1440 710x400mm 32.1-inch                     | 1        | 3.13%   |
| BenQ LCD Monitor BNQ78CA 1920x1080 600x340mm 27.2-inch                 | 1        | 3.13%   |
| BenQ GW2280 BNQ78E8 1920x1080 480x270mm 21.7-inch                      | 1        | 3.13%   |
| AOC U3277WB AOC3277 3840x2160 700x390mm 31.5-inch                      | 1        | 3.13%   |
| AOC U2790B AOC2790 3840x2160 600x340mm 27.2-inch                       | 1        | 3.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 16       | 50%     |
| 3840x2160 (4K)    | 6        | 18.75%  |
| 2560x1440 (QHD)   | 4        | 12.5%   |
| 1920x1200 (WUXGA) | 2        | 6.25%   |
| 2560x1080         | 1        | 3.13%   |
| 1600x1200         | 1        | 3.13%   |
| 11520x2160        | 1        | 3.13%   |
| Unknown           | 1        | 3.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 7        | 22.58%  |
| Unknown | 7        | 22.58%  |
| 24      | 5        | 16.13%  |
| 32      | 2        | 6.45%   |
| 23      | 2        | 6.45%   |
| 15      | 2        | 6.45%   |
| 74      | 1        | 3.23%   |
| 46      | 1        | 3.23%   |
| 41      | 1        | 3.23%   |
| 34      | 1        | 3.23%   |
| 21      | 1        | 3.23%   |
| 13      | 1        | 3.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 14       | 45.16%  |
| Unknown     | 7        | 22.58%  |
| 701-800     | 3        | 9.68%   |
| 301-350     | 3        | 9.68%   |
| 401-500     | 1        | 3.23%   |
| 1501-2000   | 1        | 3.23%   |
| 1001-1500   | 1        | 3.23%   |
| 901-1000    | 1        | 3.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 21       | 70%     |
| Unknown | 6        | 20%     |
| 16/10   | 2        | 6.67%   |
| 21/9    | 1        | 3.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 301-350        | 7        | 22.58%  |
| Unknown        | 7        | 22.58%  |
| 201-250        | 5        | 16.13%  |
| 351-500        | 3        | 9.68%   |
| 251-300        | 3        | 9.68%   |
| 101-110        | 2        | 6.45%   |
| 501-1000       | 2        | 6.45%   |
| More than 1000 | 1        | 3.23%   |
| 81-90          | 1        | 3.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 14       | 46.67%  |
| Unknown | 7        | 23.33%  |
| 161-240 | 3        | 10%     |
| 121-160 | 3        | 10%     |
| 101-120 | 2        | 6.67%   |
| 1-50    | 1        | 3.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 31       | 50%     |
| 1     | 29       | 46.77%  |
| 2     | 2        | 3.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 33       | 45.21%  |
| Intel                           | 29       | 39.73%  |
| Qualcomm Atheros                | 2        | 2.74%   |
| Xiaomi                          | 1        | 1.37%   |
| TP-Link                         | 1        | 1.37%   |
| Ralink Technology               | 1        | 1.37%   |
| Ralink                          | 1        | 1.37%   |
| Qualcomm Atheros Communications | 1        | 1.37%   |
| Mellanox Technologies           | 1        | 1.37%   |
| MediaTek                        | 1        | 1.37%   |
| ASUSTek Computer                | 1        | 1.37%   |
| Arduino SA                      | 1        | 1.37%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 19       | 21.59%  |
| Realtek RTL8125 2.5GbE Controller                                             | 13       | 14.77%  |
| Intel I211 Gigabit Network Connection                                         | 7        | 7.95%   |
| Intel Wi-Fi 6 AX200                                                           | 6        | 6.82%   |
| Intel Ethernet Controller I225-V                                              | 5        | 5.68%   |
| Intel 82574L Gigabit Network Connection                                       | 5        | 5.68%   |
| Intel I210 Gigabit Network Connection                                         | 3        | 3.41%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                          | 1        | 1.14%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1        | 1.14%   |
| Realtek USB 2.5GbE Controller                                                 | 1        | 1.14%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 1.14%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1        | 1.14%   |
| Realtek Killer E3000 2.5GbE Controller                                        | 1        | 1.14%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1        | 1.14%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                     | 1        | 1.14%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 1        | 1.14%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 1.14%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1        | 1.14%   |
| Mellanox MT27500 Family [ConnectX-3]                                          | 1        | 1.14%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                 | 1        | 1.14%   |
| Intel Wireless 8265 / 8275                                                    | 1        | 1.14%   |
| Intel Wireless 7265                                                           | 1        | 1.14%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                     | 1        | 1.14%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                       | 1        | 1.14%   |
| Intel I350 Gigabit Network Connection                                         | 1        | 1.14%   |
| Intel Ethernet Controller X550                                                | 1        | 1.14%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1        | 1.14%   |
| Intel Ethernet Connection (2) I219-V                                          | 1        | 1.14%   |
| Intel Ethernet Connection (14) I219-LM                                        | 1        | 1.14%   |
| Intel Ethernet Connection (11) I219-V                                         | 1        | 1.14%   |
| Intel Ethernet Connection (11) I219-LM                                        | 1        | 1.14%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1        | 1.14%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 1        | 1.14%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 1        | 1.14%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 1.14%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                                           | 1        | 1.14%   |
| Arduino SA Uno R3 (CDC ACM)                                                   | 1        | 1.14%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 13       | 56.52%  |
| Realtek Semiconductor           | 2        | 8.7%    |
| Qualcomm Atheros                | 2        | 8.7%    |
| TP-Link                         | 1        | 4.35%   |
| Ralink Technology               | 1        | 4.35%   |
| Ralink                          | 1        | 4.35%   |
| Qualcomm Atheros Communications | 1        | 4.35%   |
| MediaTek                        | 1        | 4.35%   |
| ASUSTek Computer                | 1        | 4.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                           | 6        | 26.09%  |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1        | 4.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 4.35%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1        | 4.35%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1        | 4.35%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                     | 1        | 4.35%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 1        | 4.35%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 4.35%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1        | 4.35%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                 | 1        | 4.35%   |
| Intel Wireless 8265 / 8275                                                    | 1        | 4.35%   |
| Intel Wireless 7265                                                           | 1        | 4.35%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                     | 1        | 4.35%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                       | 1        | 4.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1        | 4.35%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 1        | 4.35%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 1        | 4.35%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                                           | 1        | 4.35%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 30       | 53.57%  |
| Intel                 | 25       | 44.64%  |
| Xiaomi                | 1        | 1.79%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 19       | 30.65%  |
| Realtek RTL8125 2.5GbE Controller                                             | 12       | 19.35%  |
| Intel I211 Gigabit Network Connection                                         | 7        | 11.29%  |
| Intel Ethernet Controller I225-V                                              | 5        | 8.06%   |
| Intel 82574L Gigabit Network Connection                                       | 5        | 8.06%   |
| Intel I210 Gigabit Network Connection                                         | 3        | 4.84%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                          | 1        | 1.61%   |
| Realtek USB 2.5GbE Controller                                                 | 1        | 1.61%   |
| Realtek Killer E3000 2.5GbE Controller                                        | 1        | 1.61%   |
| Intel I350 Gigabit Network Connection                                         | 1        | 1.61%   |
| Intel Ethernet Controller X550                                                | 1        | 1.61%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1        | 1.61%   |
| Intel Ethernet Connection (2) I219-V                                          | 1        | 1.61%   |
| Intel Ethernet Connection (14) I219-LM                                        | 1        | 1.61%   |
| Intel Ethernet Connection (11) I219-V                                         | 1        | 1.61%   |
| Intel Ethernet Connection (11) I219-LM                                        | 1        | 1.61%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 1.61%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 49       | 67.12%  |
| WiFi     | 21       | 28.77%  |
| Unknown  | 2        | 2.74%   |
| Modem    | 1        | 1.37%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 45       | 88.24%  |
| WiFi     | 6        | 11.76%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 22       | 35.48%  |
| 2     | 19       | 30.65%  |
| 0     | 12       | 19.35%  |
| 3     | 5        | 8.06%   |
| 4     | 3        | 4.84%   |
| 7     | 1        | 1.61%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 55       | 88.71%  |
| Yes  | 7        | 11.29%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 10       | 66.67%  |
| Ralink                  | 1        | 6.67%   |
| IMC Networks            | 1        | 6.67%   |
| Foxconn / Hon Hai       | 1        | 6.67%   |
| Cambridge Silicon Radio | 1        | 6.67%   |
| Broadcom                | 1        | 6.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 4        | 26.67%  |
| Intel Bluetooth wireless interface                  | 2        | 13.33%  |
| Ralink RT3290 Bluetooth                             | 1        | 6.67%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 6.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 6.67%   |
| Intel AX210 Bluetooth                               | 1        | 6.67%   |
| Intel AX201 Bluetooth                               | 1        | 6.67%   |
| IMC Networks Realtek Bluetooth Adapter              | 1        | 6.67%   |
| Foxconn / Hon Hai RZ616 Bluetooth Adapter           | 1        | 6.67%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 6.67%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 6.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| AMD                     | 28       | 40.58%  |
| Nvidia                  | 17       | 24.64%  |
| Intel                   | 13       | 18.84%  |
| C-Media Electronics     | 2        | 2.9%    |
| Yamaha                  | 1        | 1.45%   |
| RODE Microphones        | 1        | 1.45%   |
| JMTek                   | 1        | 1.45%   |
| GN Netcom               | 1        | 1.45%   |
| Creative Labs           | 1        | 1.45%   |
| Blue Microphones        | 1        | 1.45%   |
| AudioQuest              | 1        | 1.45%   |
| ASUSTek Computer        | 1        | 1.45%   |
| AKAI  Professional M.I. | 1        | 1.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                           | Desktops | Percent |
|-------------------------------------------------------------------------------------------------|----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                          | 11       | 12.79%  |
| AMD Renoir Radeon High Definition Audio Controller                                              | 8        | 9.3%    |
| AMD Starship/Matisse HD Audio Controller                                                        | 6        | 6.98%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                             | 5        | 5.81%   |
| Nvidia GP107GL High Definition Audio Controller                                                 | 4        | 4.65%   |
| Intel Comet Lake PCH cAVS                                                                       | 3        | 3.49%   |
| Intel Cannon Lake PCH cAVS                                                                      | 3        | 3.49%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                             | 3        | 3.49%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                         | 3        | 3.49%   |
| Nvidia GP108 High Definition Audio Controller                                                   | 2        | 2.33%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                           | 2        | 2.33%   |
| Intel Comet Lake PCH-V cAVS                                                                     | 2        | 2.33%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                           | 2        | 2.33%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                         | 2        | 2.33%   |
| Yamaha Steinberg UR12                                                                           | 1        | 1.16%   |
| RODE Microphones RODE AI-1                                                                      | 1        | 1.16%   |
| Nvidia TU116 High Definition Audio Controller                                                   | 1        | 1.16%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                  | 1        | 1.16%   |
| Nvidia High Definition Audio Controller                                                         | 1        | 1.16%   |
| Nvidia GP106 High Definition Audio Controller                                                   | 1        | 1.16%   |
| Nvidia GP104 High Definition Audio Controller                                                   | 1        | 1.16%   |
| Nvidia GM206 High Definition Audio Controller                                                   | 1        | 1.16%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                   | 1        | 1.16%   |
| Nvidia GA104 High Definition Audio Controller                                                   | 1        | 1.16%   |
| Nvidia GA102 High Definition Audio Controller                                                   | 1        | 1.16%   |
| JMTek Lioncast USB Gaming Headset                                                               | 1        | 1.16%   |
| Intel Tiger Lake-H HD Audio Controller                                                          | 1        | 1.16%   |
| Intel HD Graphics SGPC                                                                          | 1        | 1.16%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                      | 1        | 1.16%   |
| Intel Alder Lake-S HD Audio Controller                                                          | 1        | 1.16%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 1        | 1.16%   |
| GN Netcom Jabra SPEAK 410 USB                                                                   | 1        | 1.16%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 1        | 1.16%   |
| C-Media Electronics TONOR TC-777 Audio Device                                                   | 1        | 1.16%   |
| C-Media Electronics CM108 Audio Controller                                                      | 1        | 1.16%   |
| Blue Microphones Yeti Stereo Microphone                                                         | 1        | 1.16%   |
| AudioQuest DragonFly                                                                            | 1        | 1.16%   |
| ASUSTek Computer Realtek USB Audio                                                              | 1        | 1.16%   |
| AMD SBx00 Azalia (Intel HDA)                                                                    | 1        | 1.16%   |
| AMD RV630 HDMI Audio [Radeon HD 2600 PRO/XT / HD 3610]                                          | 1        | 1.16%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 10       | 21.28%  |
| Corsair                      | 6        | 12.77%  |
| SK hynix                     | 4        | 8.51%   |
| Samsung Electronics          | 4        | 8.51%   |
| Micron Technology            | 4        | 8.51%   |
| Crucial                      | 4        | 8.51%   |
| Unknown                      | 3        | 6.38%   |
| G.Skill                      | 3        | 6.38%   |
| Unknown                      | 2        | 4.26%   |
| Transcend                    | 1        | 2.13%   |
| Team                         | 1        | 2.13%   |
| Smart                        | 1        | 2.13%   |
| Patriot Memory (PDP Systems) | 1        | 2.13%   |
| Golden Empire                | 1        | 2.13%   |
| Apacer                       | 1        | 2.13%   |
| A-DATA Technology            | 1        | 2.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Corsair RAM CMK32GX4M2D3200C16 16GB DIMM DDR4 3200MT/s                 | 2        | 3.85%   |
| Unknown                                                                | 2        | 3.85%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                              | 1        | 1.92%   |
| Unknown RAM 3000 C16 Series 4096MB DIMM DDR4 2933MT/s                  | 1        | 1.92%   |
| Unknown RAM 2G-08-10-12-1333 2GB DIMM DDR3 1333MT/s                    | 1        | 1.92%   |
| Transcend RAM JM2666HLE-32G 32GB DIMM DDR4 2666MT/s                    | 1        | 1.92%   |
| Team RAM TEAMGROUP-UD4-4133 8GB DIMM DDR4 4133MT/s                     | 1        | 1.92%   |
| Smart RAM Module 8GB DIMM DDR4 2667MT/s                                | 1        | 1.92%   |
| SK hynix RAM HMAA4GU6CJR8N-XN 32GB DIMM DDR4 3200MT/s                  | 1        | 1.92%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s                | 1        | 1.92%   |
| SK hynix RAM HMA82GR7JJR8N-VK 16GB DIMM DDR4 2667MT/s                  | 1        | 1.92%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s                 | 1        | 1.92%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s                 | 1        | 1.92%   |
| Samsung RAM M393A2K40CB2-CTD 16GB DIMM DDR4 2666MT/s                   | 1        | 1.92%   |
| Samsung RAM M393A2K40BB2-CTD 16GB DIMM DDR4 2667MT/s                   | 1        | 1.92%   |
| Samsung RAM M378A4G43MB1-CTD 32GB DIMM DDR4 2666MT/s                   | 1        | 1.92%   |
| Samsung RAM FRD4AA8Z3Z1ABZZ02 16GB DIMM DDR4 2667MT/s                  | 1        | 1.92%   |
| Patriot Memory (PDP Systems) RAM PSD416G320081 16GB DIMM DDR4 3200MT/s | 1        | 1.92%   |
| Micron RAM 36ASF2G72PZ-2G6E1 16GB DIMM DDR4 2666MT/s                   | 1        | 1.92%   |
| Micron RAM 18ASF4G72AZ-3G2B1 32GB DIMM DDR4 3200MT/s                   | 1        | 1.92%   |
| Micron RAM 18ASF2G72PZ-2G6D1 16GB DIMM DDR4 2666MT/s                   | 1        | 1.92%   |
| Micron RAM 18ASF2G72PDZ-2G6D1 16GB DIMM DDR4 2666MT/s                  | 1        | 1.92%   |
| Micron RAM 16ATF2G64HZ-2G6J1 16GB SODIMM DDR4 2667MT/s                 | 1        | 1.92%   |
| Micron RAM 16ATF2G64AZ-3G2J1 16GB DIMM DDR4 3200MT/s                   | 1        | 1.92%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s                 | 1        | 1.92%   |
| Kingston RAM KHX2933C15D4/8GX 8GB DIMM DDR4 2400MT/s                   | 1        | 1.92%   |
| Kingston RAM KHX2666C16D4/16GX 16GB DIMM DDR4 2667MT/s                 | 1        | 1.92%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 2666MT/s                    | 1        | 1.92%   |
| Kingston RAM KHX2133C14/16G 16GB DIMM DDR4 2133MT/s                    | 1        | 1.92%   |
| Kingston RAM KHX1600C10D3/ 4GB DIMM DDR3 1866MT/s                      | 1        | 1.92%   |
| Kingston RAM KF556C40-32 32GB DIMM DDR5 5200MT/s                       | 1        | 1.92%   |
| Kingston RAM KF3000C16D4/32GX 32GB DIMM DDR4 2400MT/s                  | 1        | 1.92%   |
| Kingston RAM 99P5700-016.A00G 16GB SODIMM DDR4 3200MT/s                | 1        | 1.92%   |
| Kingston RAM 9965745-020.A00G 32GB DIMM DDR4 3200MT/s                  | 1        | 1.92%   |
| Kingston RAM 9965745-017.A00G 16GB DIMM DDR4 3200MT/s                  | 1        | 1.92%   |
| Kingston RAM 9905713-030.A00G 8GB DIMM DDR4 2933MT/s                   | 1        | 1.92%   |
| Golden Empire RAM D4U0830160B 8GB DIMM DDR4 2400MT/s                   | 1        | 1.92%   |
| G.Skill RAM F4-3200C16-8GVGB 8GB DIMM DDR4 3200MT/s                    | 1        | 1.92%   |
| G.Skill RAM F4-3200C16-32GTZN 32GB DIMM DDR4 3200MT/s                  | 1        | 1.92%   |
| G.Skill RAM F4-2400C17-8GNT 8GB DIMM DDR4 2400MT/s                     | 1        | 1.92%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 37       | 88.1%   |
| DDR3 | 3        | 7.14%   |
| DDR5 | 2        | 4.76%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 37       | 88.1%   |
| SODIMM | 5        | 11.9%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 17       | 39.53%  |
| 8192  | 13       | 30.23%  |
| 32768 | 11       | 25.58%  |
| 4096  | 1        | 2.33%   |
| 2048  | 1        | 2.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 17       | 36.96%  |
| 2667  | 7        | 15.22%  |
| 2666  | 4        | 8.7%    |
| 2400  | 4        | 8.7%    |
| 2133  | 3        | 6.52%   |
| 3600  | 2        | 4.35%   |
| 2933  | 2        | 4.35%   |
| 5200  | 1        | 2.17%   |
| 4800  | 1        | 2.17%   |
| 4133  | 1        | 2.17%   |
| 3000  | 1        | 2.17%   |
| 1866  | 1        | 2.17%   |
| 1600  | 1        | 2.17%   |
| 1333  | 1        | 2.17%   |

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
| 0     | 35       | 55.56%  |
| 1     | 17       | 26.98%  |
| 2     | 6        | 9.52%   |
| 4     | 3        | 4.76%   |
| 3     | 2        | 3.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 15       | 38.46%  |
| Net/wireless             | 7        | 17.95%  |
| Bluetooth                | 6        | 15.38%  |
| Sound                    | 3        | 7.69%   |
| Network                  | 3        | 7.69%   |
| Net/ethernet             | 3        | 7.69%   |
| Storage/raid             | 1        | 2.56%   |
| Fingerprint reader       | 1        | 2.56%   |

