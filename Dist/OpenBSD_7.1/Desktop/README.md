OpenBSD 7.1 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------

A project to collect tested hardware configurations for OpenBSD 7.1.

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

Total: 45

| Vendor     | Model                       | Probe                                                     | Date         |
|------------|-----------------------------|-----------------------------------------------------------|--------------|
| ASUSTek    | All Series                  | [ab3b339cf0](https://bsd-hardware.info/?probe=ab3b339cf0) | Sep 24, 2022 |
| Gigabyte   | H81M-S1                     | [fe9eecb935](https://bsd-hardware.info/?probe=fe9eecb935) | Sep 18, 2022 |
| CncTion    | N5105-4L                    | [2a34dc3fe0](https://bsd-hardware.info/?probe=2a34dc3fe0) | Sep 05, 2022 |
| ASUSTek    | PRIME B460M-A               | [21fed03fa2](https://bsd-hardware.info/?probe=21fed03fa2) | Aug 24, 2022 |
| ASUSTek    | PRIME B460M-A               | [48210e4d2a](https://bsd-hardware.info/?probe=48210e4d2a) | Aug 24, 2022 |
| Fujitsu    | PRIMERGY RX200 S6           | [9267873961](https://bsd-hardware.info/?probe=9267873961) | Aug 13, 2022 |
| Biostar    | TA880GU3+                   | [8b0c8541b3](https://bsd-hardware.info/?probe=8b0c8541b3) | Aug 06, 2022 |
| ASRock     | A320M-DVS R4.0              | [77f61a8711](https://bsd-hardware.info/?probe=77f61a8711) | Aug 01, 2022 |
| Gigabyte   | H87-HD3                     | [e6a9b0dd8b](https://bsd-hardware.info/?probe=e6a9b0dd8b) | Jul 25, 2022 |
| ASUSTek    | M4A785TD-M EVO              | [def87ec245](https://bsd-hardware.info/?probe=def87ec245) | Jul 18, 2022 |
| ASUSTek    | PRIME H410M-A               | [7b6faf5301](https://bsd-hardware.info/?probe=7b6faf5301) | Jul 14, 2022 |
| ASUSTek    | PRIME H410M-A               | [ba243fa7c4](https://bsd-hardware.info/?probe=ba243fa7c4) | Jul 09, 2022 |
| Dell       | OptiPlex 580                | [620888d077](https://bsd-hardware.info/?probe=620888d077) | Jul 02, 2022 |
| ASUSTek    | TUF Gaming B550-PLUS        | [77acc9f5cf](https://bsd-hardware.info/?probe=77acc9f5cf) | Jul 01, 2022 |
| ASUSTek    | TUF Gaming B550-PLUS        | [ffa0086c70](https://bsd-hardware.info/?probe=ffa0086c70) | Jul 01, 2022 |
| Gigabyte   | G41MT-S2                    | [0563158740](https://bsd-hardware.info/?probe=0563158740) | Jun 28, 2022 |
| MSI        | MS-7C02                     | [65265eea62](https://bsd-hardware.info/?probe=65265eea62) | Jun 20, 2022 |
| Lenovo     | ThinkPad T530 24292VG       | [6f744019ce](https://bsd-hardware.info/?probe=6f744019ce) | Jun 19, 2022 |
| Apple      | MacPro4,1                   | [65380f3847](https://bsd-hardware.info/?probe=65380f3847) | Jun 06, 2022 |
| ASUSTek    | PRIME H410M-E               | [8099e7abaf](https://bsd-hardware.info/?probe=8099e7abaf) | Jun 03, 2022 |
| MSI        | MS-6788                     | [f750cb83e3](https://bsd-hardware.info/?probe=f750cb83e3) | May 31, 2022 |
| Unknown    | Raspberry Pi 4 Model B R... | [ade09344b8](https://bsd-hardware.info/?probe=ade09344b8) | May 26, 2022 |
| Unknown    | Raspberry Pi 4 Model B R... | [cc37ea1b7d](https://bsd-hardware.info/?probe=cc37ea1b7d) | May 26, 2022 |
| Unknown    | Raspberry Pi 4 Model B R... | [abacee12a9](https://bsd-hardware.info/?probe=abacee12a9) | May 26, 2022 |
| Unknown    | Raspberry Pi 3 Model B P... | [21fa41e4c1](https://bsd-hardware.info/?probe=21fa41e4c1) | May 26, 2022 |
| Gigabyte   | H81M-S2PV                   | [1937e77b97](https://bsd-hardware.info/?probe=1937e77b97) | May 22, 2022 |
| Biostar    | G31-M7 TE                   | [5c7af4b143](https://bsd-hardware.info/?probe=5c7af4b143) | May 21, 2022 |
| ASUSTek    | PRIME B550M-K               | [ce5ddde5ad](https://bsd-hardware.info/?probe=ce5ddde5ad) | May 18, 2022 |
| MSI        | MS-7C82                     | [2ad883afec](https://bsd-hardware.info/?probe=2ad883afec) | May 15, 2022 |
| ASUSTek    | PRIME X470-PRO              | [9f6b4f114d](https://bsd-hardware.info/?probe=9f6b4f114d) | May 11, 2022 |
| Unknown    | Raspberry Pi 4 Model B R... | [154799d7fa](https://bsd-hardware.info/?probe=154799d7fa) | May 08, 2022 |
| Intel      | Q3XXG4-P                    | [ed04988a23](https://bsd-hardware.info/?probe=ed04988a23) | May 03, 2022 |
| MSI        | MS-7C37                     | [aaab7cf22a](https://bsd-hardware.info/?probe=aaab7cf22a) | Apr 28, 2022 |
| ASUSTek    | M4A88TD-V EVO/USB3          | [12cc40cc60](https://bsd-hardware.info/?probe=12cc40cc60) | Apr 23, 2022 |
| PC Engines | APU2                        | [04a6549c99](https://bsd-hardware.info/?probe=04a6549c99) | Apr 23, 2022 |
| Intel      | DH67BL                      | [3c3c9e12da](https://bsd-hardware.info/?probe=3c3c9e12da) | Apr 22, 2022 |
| KOHJINSHA  | SH series                   | [3136a0ca03](https://bsd-hardware.info/?probe=3136a0ca03) | Apr 22, 2022 |
| Lenovo     | ThinkPad X240 20ALA0AHRT    | [062a08c811](https://bsd-hardware.info/?probe=062a08c811) | Apr 22, 2022 |
| Sony       | VPCL22Z1R                   | [f199d57905](https://bsd-hardware.info/?probe=f199d57905) | Apr 22, 2022 |
| ASUSTek    | Z170-K                      | [b16705bbbd](https://bsd-hardware.info/?probe=b16705bbbd) | Apr 22, 2022 |
| ASUSTek    | P10S-I Series               | [aca13dba36](https://bsd-hardware.info/?probe=aca13dba36) | Apr 22, 2022 |
| Dell       | G5 5090                     | [8b24170852](https://bsd-hardware.info/?probe=8b24170852) | Apr 17, 2022 |
| Lenovo     | ThinkCentre M93p 10AAS25... | [32d27b9404](https://bsd-hardware.info/?probe=32d27b9404) | Mar 19, 2022 |
| Lenovo     | ThinkCentre M93p 10AAS25... | [7361628ed9](https://bsd-hardware.info/?probe=7361628ed9) | Mar 19, 2022 |
| Unknown    | LeMaker Banana Pi           | [37e7d1912b](https://bsd-hardware.info/?probe=37e7d1912b) | Mar 05, 2022 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 34       | 80.95%  |
| arm64 | 5        | 11.9%   |
| i386  | 2        | 4.76%   |
| armv7 | 1        | 2.38%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| helloDesktop | 36       | 85.71%  |
| XFCE         | 4        | 9.52%   |
| GNOME        | 1        | 2.38%   |
| Console      | 1        | 2.38%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 27       | 64.29%  |
| Console | 15       | 35.71%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 42       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 36       | 85.71%  |
| ru_RU   | 4        | 9.52%   |
| en_US   | 1        | 2.38%   |
| C       | 1        | 2.38%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 23       | 54.76%  |
| EFI  | 19       | 45.24%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ffs  | 42       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| MBR  | 28       | 66.67%  |
| GPT  | 14       | 33.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 12       | 28.57%  |
| Unknown             | 6        | 14.29%  |
| MSI                 | 4        | 9.52%   |
| Gigabyte Technology | 4        | 9.52%   |
| Lenovo              | 3        | 7.14%   |
| Intel               | 2        | 4.76%   |
| Dell                | 2        | 4.76%   |
| Biostar             | 2        | 4.76%   |
| Sony                | 1        | 2.38%   |
| PC Engines          | 1        | 2.38%   |
| KOHJINSHA           | 1        | 2.38%   |
| Fujitsu             | 1        | 2.38%   |
| CncTion             | 1        | 2.38%   |
| ASRock              | 1        | 2.38%   |
| Apple               | 1        | 2.38%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 6        | 14.29%  |
| ASUS PRIME H410M-A                 | 2        | 4.76%   |
| Sony VPCL22Z1R                     | 1        | 2.38%   |
| PC Engines APU2                    | 1        | 2.38%   |
| MSI MS-7C82                        | 1        | 2.38%   |
| MSI MS-7C37                        | 1        | 2.38%   |
| MSI MS-7C02                        | 1        | 2.38%   |
| MSI MS-6788                        | 1        | 2.38%   |
| Lenovo ThinkPad X240 20ALA0AHRT    | 1        | 2.38%   |
| Lenovo ThinkPad T530 24292VG       | 1        | 2.38%   |
| Lenovo ThinkCentre M93p 10AAS25M00 | 1        | 2.38%   |
| KOHJINSHA SH series                | 1        | 2.38%   |
| Intel Q3XXG4-P                     | 1        | 2.38%   |
| Intel DH67BL                       | 1        | 2.38%   |
| Gigabyte H87-HD3                   | 1        | 2.38%   |
| Gigabyte H81M-S2PV                 | 1        | 2.38%   |
| Gigabyte H81M-S1                   | 1        | 2.38%   |
| Gigabyte G41MT-S2                  | 1        | 2.38%   |
| Fujitsu PRIMERGY RX200 S6          | 1        | 2.38%   |
| Dell OptiPlex 580                  | 1        | 2.38%   |
| Dell G5 5090                       | 1        | 2.38%   |
| CncTion N5105-4L                   | 1        | 2.38%   |
| Biostar TA880GU3+                  | 1        | 2.38%   |
| Biostar G31-M7 TE                  | 1        | 2.38%   |
| ASUS Z170-K                        | 1        | 2.38%   |
| ASUS TUF Gaming B550-PLUS          | 1        | 2.38%   |
| ASUS PRIME X470-PRO                | 1        | 2.38%   |
| ASUS PRIME H410M-E                 | 1        | 2.38%   |
| ASUS PRIME B550M-K                 | 1        | 2.38%   |
| ASUS PRIME B460M-A                 | 1        | 2.38%   |
| ASUS P10S-I Series                 | 1        | 2.38%   |
| ASUS M4A88TD-V EVO/USB3            | 1        | 2.38%   |
| ASUS M4A785TD-M EVO                | 1        | 2.38%   |
| ASUS All Series                    | 1        | 2.38%   |
| ASRock A320M-DVS R4.0              | 1        | 2.38%   |
| Apple MacPro4,1                    | 1        | 2.38%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ASUS PRIME         | 6        | 14.29%  |
| Unknown            | 6        | 14.29%  |
| Lenovo ThinkPad    | 2        | 4.76%   |
| Sony VPCL22Z1R     | 1        | 2.38%   |
| PC Engines APU2    | 1        | 2.38%   |
| MSI MS-7C82        | 1        | 2.38%   |
| MSI MS-7C37        | 1        | 2.38%   |
| MSI MS-7C02        | 1        | 2.38%   |
| MSI MS-6788        | 1        | 2.38%   |
| Lenovo ThinkCentre | 1        | 2.38%   |
| KOHJINSHA SH       | 1        | 2.38%   |
| Intel Q3XXG4-P     | 1        | 2.38%   |
| Intel DH67BL       | 1        | 2.38%   |
| Gigabyte H87-HD3   | 1        | 2.38%   |
| Gigabyte H81M-S2PV | 1        | 2.38%   |
| Gigabyte H81M-S1   | 1        | 2.38%   |
| Gigabyte G41MT-S2  | 1        | 2.38%   |
| Fujitsu PRIMERGY   | 1        | 2.38%   |
| Dell OptiPlex      | 1        | 2.38%   |
| Dell G5            | 1        | 2.38%   |
| CncTion N5105-4L   | 1        | 2.38%   |
| Biostar TA880GU3+  | 1        | 2.38%   |
| Biostar G31-M7     | 1        | 2.38%   |
| ASUS Z170-K        | 1        | 2.38%   |
| ASUS TUF           | 1        | 2.38%   |
| ASUS P10S-I        | 1        | 2.38%   |
| ASUS M4A88TD-V     | 1        | 2.38%   |
| ASUS M4A785TD-M    | 1        | 2.38%   |
| ASUS All           | 1        | 2.38%   |
| ASRock A320M-DVS   | 1        | 2.38%   |
| Apple MacPro4      | 1        | 2.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 7        | 16.67%  |
| 2021    | 5        | 11.9%   |
| 2010    | 5        | 11.9%   |
| 2020    | 4        | 9.52%   |
| 2018    | 4        | 9.52%   |
| 2022    | 3        | 7.14%   |
| 2019    | 3        | 7.14%   |
| 2016    | 2        | 4.76%   |
| 2015    | 2        | 4.76%   |
| 2014    | 2        | 4.76%   |
| 2011    | 2        | 4.76%   |
| 2012    | 1        | 2.38%   |
| 2009    | 1        | 2.38%   |
| 2007    | 1        | 2.38%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 42       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 41       | 97.62%  |
| Yes  | 1        | 2.38%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 14       | 33.33%  |
| 16.01-24.0  | 9        | 21.43%  |
| 4.01-8.0    | 8        | 19.05%  |
| 3.01-4.0    | 2        | 4.76%   |
| 2.01-3.0    | 2        | 4.76%   |
| 64.01-256.0 | 2        | 4.76%   |
| 1.01-2.0    | 2        | 4.76%   |
| 0.51-1.0    | 2        | 4.76%   |
| 24.01-32.0  | 1        | 2.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.01-0.5 | 37       | 88.1%   |
| 0        | 2        | 4.76%   |
| 4.01-8.0 | 1        | 2.38%   |
| 3.01-4.0 | 1        | 2.38%   |
| 0.51-1.0 | 1        | 2.38%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 23       | 54.76%  |
| 4      | 7        | 16.67%  |
| 3      | 5        | 11.9%   |
| 2      | 4        | 9.52%   |
| 8      | 1        | 2.38%   |
| 6      | 1        | 2.38%   |
| 5      | 1        | 2.38%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 41       | 97.62%  |
| Yes       | 1        | 2.38%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 35       | 83.33%  |
| No        | 7        | 16.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 32       | 76.19%  |
| Yes       | 10       | 23.81%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 36       | 85.71%  |
| Yes       | 6        | 14.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Russia      | 10       | 23.81%  |
| Italy       | 6        | 14.29%  |
| Netherlands | 4        | 9.52%   |
| Germany     | 4        | 9.52%   |
| USA         | 3        | 7.14%   |
| Spain       | 2        | 4.76%   |
| Poland      | 2        | 4.76%   |
| Canada      | 2        | 4.76%   |
| Austria     | 2        | 4.76%   |
| UK          | 1        | 2.38%   |
| Norway      | 1        | 2.38%   |
| Lithuania   | 1        | 2.38%   |
| India       | 1        | 2.38%   |
| Egypt       | 1        | 2.38%   |
| Czechia     | 1        | 2.38%   |
| Argentina   | 1        | 2.38%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City               | Desktops | Percent |
|--------------------|----------|---------|
| Poortugaal         | 4        | 9.52%   |
| Milan              | 4        | 9.52%   |
| Vladivostok        | 3        | 7.14%   |
| Vienna             | 2        | 4.76%   |
| Wolverhampton      | 1        | 2.38%   |
| Tambov             | 1        | 2.38%   |
| St. Albert         | 1        | 2.38%   |
| Sarnia             | 1        | 2.38%   |
| Reutov             | 1        | 2.38%   |
| Pozzuolo Martesana | 1        | 2.38%   |
| Paderborn          | 1        | 2.38%   |
| Oslo               | 1        | 2.38%   |
| Orenburg           | 1        | 2.38%   |
| Oakland            | 1        | 2.38%   |
| Nuremberg          | 1        | 2.38%   |
| Moscow             | 1        | 2.38%   |
| Memmingen          | 1        | 2.38%   |
| Ludwigsburg        | 1        | 2.38%   |
| Lodz               | 1        | 2.38%   |
| Krasnodar          | 1        | 2.38%   |
| Kolomna            | 1        | 2.38%   |
| Gianico            | 1        | 2.38%   |
| Gdansk             | 1        | 2.38%   |
| Delhi              | 1        | 2.38%   |
| Columbus           | 1        | 2.38%   |
| Cherepovets        | 1        | 2.38%   |
| Český Těšín   | 1        | 2.38%   |
| Cairo              | 1        | 2.38%   |
| Buenos Aires       | 1        | 2.38%   |
| Brooklyn           | 1        | 2.38%   |
| Bilbao             | 1        | 2.38%   |
| Barcelona          | 1        | 2.38%   |
| Alytus             | 1        | 2.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 11       | 12     | 15.94%  |
| Seagate             | 10       | 14     | 14.49%  |
| NVMe                | 9        | 11     | 13.04%  |
| Samsung Electronics | 7        | 12     | 10.14%  |
| Toshiba             | 4        | 8      | 5.8%    |
| Kingston            | 3        | 3      | 4.35%   |
| Hitachi             | 3        | 4      | 4.35%   |
| Crucial             | 3        | 3      | 4.35%   |
| OPENBSD             | 2        | 2      | 2.9%    |
| Corsair             | 2        | 2      | 2.9%    |
| XPG                 | 1        | 1      | 1.45%   |
| StoreJet            | 1        | 1      | 1.45%   |
| SPCC                | 1        | 1      | 1.45%   |
| SanDisk             | 1        | 1      | 1.45%   |
| PNY                 | 1        | 1      | 1.45%   |
| OCZ                 | 1        | 1      | 1.45%   |
| LSI                 | 1        | 1      | 1.45%   |
| KingSpec            | 1        | 1      | 1.45%   |
| Intel               | 1        | 1      | 1.45%   |
| Hoodisk             | 1        | 1      | 1.45%   |
| HGST                | 1        | 1      | 1.45%   |
| GOODRAM             | 1        | 1      | 1.45%   |
| Generic             | 1        | 1      | 1.45%   |
| AMD                 | 1        | 1      | 1.45%   |
| A-DATA Technology   | 1        | 1      | 1.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Toshiba HDWG440 4TB             | 2        | 2.74%   |
| Seagate ST1000DM010-2EP102 1TB  | 2        | 2.74%   |
| OPENBSD SR RAID 1 752GB         | 2        | 2.74%   |
| NVMe Samsung SSD 980 1TB        | 2        | 2.74%   |
| XPG SX950U 240GB                | 1        | 1.37%   |
| WDC WD800JD-60LSA5 80GB         | 1        | 1.37%   |
| WDC WD6400AARS-00Y5B1 640GB     | 1        | 1.37%   |
| WDC WD6400AAKS-22A7B0 640GB     | 1        | 1.37%   |
| WDC WD5003AZEX-00K1GA0 500GB    | 1        | 1.37%   |
| WDC WD5003ABYX-01WERA2 500GB    | 1        | 1.37%   |
| WDC WD5000AZLX-00K2TA0 500GB    | 1        | 1.37%   |
| WDC WD5000AAKX-60U6AA0 500GB    | 1        | 1.37%   |
| WDC WD40EFZX-68AWUN0 4TB        | 1        | 1.37%   |
| WDC WD20PURX-64P6ZY0 2TB        | 1        | 1.37%   |
| WDC WD10JPVT-75A1YT0 1TB        | 1        | 1.37%   |
| WDC WD10EZEX-00MFCA0 1TB        | 1        | 1.37%   |
| Toshiba MG06ACA800E 8TB         | 1        | 1.37%   |
| Toshiba DT01ACA050 500GB        | 1        | 1.37%   |
| StoreJet Transcend 120GB        | 1        | 1.37%   |
| SPCC Solid State Disk 256GB     | 1        | 1.37%   |
| Seagate ST500DM002-1BD142 500GB | 1        | 1.37%   |
| Seagate ST380815AS 80GB         | 1        | 1.37%   |
| Seagate ST3750640NS 752GB       | 1        | 1.37%   |
| Seagate ST3250318AS 250GB       | 1        | 1.37%   |
| Seagate ST3250310AS 250GB       | 1        | 1.37%   |
| Seagate ST3160212SCE 160GB      | 1        | 1.37%   |
| Seagate ST250DM000-1BD141 250GB | 1        | 1.37%   |
| Seagate ST2000DM006-2DM164 2TB  | 1        | 1.37%   |
| Seagate ST1000VX000-1CU162 1TB  | 1        | 1.37%   |
| Seagate ST1000DM003-1CH162 1TB  | 1        | 1.37%   |
| Seagate Expansion 320GB         | 1        | 1.37%   |
| SanDisk Extreme Pro 128GB       | 1        | 1.37%   |
| Samsung SSD 870 QVO 2TB         | 1        | 1.37%   |
| Samsung SSD 860 EVO 500GB       | 1        | 1.37%   |
| Samsung SSD 860 EVO 250GB       | 1        | 1.37%   |
| Samsung Portable SSD T3 250GB   | 1        | 1.37%   |
| Samsung HD753LJ 752GB           | 1        | 1.37%   |
| Samsung HD161HJ 160GB           | 1        | 1.37%   |
| Samsung Flash Drive FIT 32GB    | 1        | 1.37%   |
| PNY CS900 120GB SSD             | 1        | 1.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 11       | 12     | 26.19%  |
| Seagate             | 10       | 14     | 23.81%  |
| NVMe                | 5        | 6      | 11.9%   |
| Toshiba             | 4        | 8      | 9.52%   |
| Samsung Electronics | 3        | 3      | 7.14%   |
| Hitachi             | 3        | 4      | 7.14%   |
| OPENBSD             | 2        | 2      | 4.76%   |
| StoreJet            | 1        | 1      | 2.38%   |
| LSI                 | 1        | 1      | 2.38%   |
| HGST                | 1        | 1      | 2.38%   |
| Generic             | 1        | 1      | 2.38%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 4        | 9      | 15.38%  |
| NVMe                | 3        | 4      | 11.54%  |
| Kingston            | 3        | 3      | 11.54%  |
| Crucial             | 3        | 3      | 11.54%  |
| Corsair             | 2        | 2      | 7.69%   |
| XPG                 | 1        | 1      | 3.85%   |
| SPCC                | 1        | 1      | 3.85%   |
| SanDisk             | 1        | 1      | 3.85%   |
| PNY                 | 1        | 1      | 3.85%   |
| OCZ                 | 1        | 1      | 3.85%   |
| KingSpec            | 1        | 1      | 3.85%   |
| Intel               | 1        | 1      | 3.85%   |
| Hoodisk             | 1        | 1      | 3.85%   |
| GOODRAM             | 1        | 1      | 3.85%   |
| AMD                 | 1        | 1      | 3.85%   |
| A-DATA Technology   | 1        | 1      | 3.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 25       | 53     | 54.35%  |
| SSD  | 20       | 32     | 43.48%  |
| NVMe | 1        | 1      | 2.17%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 39       | 85     | 97.5%   |
| NVMe | 1        | 1      | 2.5%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 31       | 44     | 57.41%  |
| 0.51-1.0   | 15       | 21     | 27.78%  |
| 1.01-2.0   | 4        | 11     | 7.41%   |
| 3.01-4.0   | 3        | 6      | 5.56%   |
| 4.01-10.0  | 1        | 3      | 1.85%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 13       | 30.95%  |
| 251-500        | 11       | 26.19%  |
| 21-50          | 6        | 14.29%  |
| 51-100         | 4        | 9.52%   |
| 1-20           | 3        | 7.14%   |
| 501-1000       | 3        | 7.14%   |
| More than 3000 | 2        | 4.76%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 36       | 85.71%  |
| 51-100    | 3        | 7.14%   |
| 21-50     | 2        | 4.76%   |
| 2001-3000 | 1        | 2.38%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| XPG SX950U 240GB                  | 1        | 1      | 8.33%   |
| WDC WD6400AAKS-22A7B0 640GB       | 1        | 1      | 8.33%   |
| WDC WD5000AAKX-60U6AA0 500GB      | 1        | 1      | 8.33%   |
| Seagate ST500DM002-1BD142 500GB   | 1        | 1      | 8.33%   |
| Seagate ST380815AS 80GB           | 1        | 1      | 8.33%   |
| Seagate ST3750640NS 752GB         | 1        | 2      | 8.33%   |
| Seagate ST3160212SCE 160GB        | 1        | 1      | 8.33%   |
| Seagate ST250DM000-1BD141 250GB   | 1        | 1      | 8.33%   |
| Seagate ST2000DM006-2DM164 2TB    | 1        | 1      | 8.33%   |
| Samsung Electronics HD753LJ 752GB | 1        | 1      | 8.33%   |
| Samsung Electronics HD161HJ 160GB | 1        | 1      | 8.33%   |
| OCZ VERTEX3 120GB                 | 1        | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 7      | 45.45%  |
| WDC                 | 2        | 2      | 18.18%  |
| Samsung Electronics | 2        | 2      | 18.18%  |
| XPG                 | 1        | 1      | 9.09%   |
| OCZ                 | 1        | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 7      | 55.56%  |
| WDC                 | 2        | 2      | 22.22%  |
| Samsung Electronics | 2        | 2      | 22.22%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 9        | 11     | 81.82%  |
| SSD  | 2        | 2      | 18.18%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                       | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC WD6400AARS-00Y5B1 640GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 30       | 57     | 56.6%   |
| Detected | 12       | 15     | 22.64%  |
| Malfunc  | 10       | 13     | 18.87%  |
| Failed   | 1        | 1      | 1.89%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 25       | 51.02%  |
| AMD                          | 11       | 22.45%  |
| Samsung Electronics          | 3        | 6.12%   |
| SanDisk                      | 2        | 4.08%   |
| VIA Technologies             | 1        | 2.04%   |
| Toshiba                      | 1        | 2.04%   |
| Shenzhen Longsys Electronics | 1        | 2.04%   |
| Marvell Technology Group     | 1        | 2.04%   |
| KIOXIA                       | 1        | 2.04%   |
| Broadcom / LSI               | 1        | 2.04%   |
| ASMedia Technology           | 1        | 2.04%   |
| ADATA Technology             | 1        | 2.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5        | 8.77%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 5        | 8.77%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4        | 7.02%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3        | 5.26%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 3        | 5.26%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2        | 3.51%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2        | 3.51%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2        | 3.51%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2        | 3.51%   |
| AMD 500 Series Chipset SATA Controller                                         | 2        | 3.51%   |
| AMD 400 Series Chipset SATA Controller                                         | 2        | 3.51%   |
| VIA VT6415 PATA IDE Host Controller                                            | 1        | 1.75%   |
| Toshiba BG3 NVMe SSD Controller                                                | 1        | 1.75%   |
| Shenzhen Longsys unknown                                                       | 1        | 1.75%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1        | 1.75%   |
| SanDisk unknown                                                                | 1        | 1.75%   |
| SanDisk PC SN520 NVMe SSD                                                      | 1        | 1.75%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1        | 1.75%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller               | 1        | 1.75%   |
| KIOXIA NVMe SSD                                                                | 1        | 1.75%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1        | 1.75%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 1        | 1.75%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 1.75%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 1        | 1.75%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 1        | 1.75%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 1        | 1.75%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 1        | 1.75%   |
| Intel 82801EB (ICH5) SATA Controller                                           | 1        | 1.75%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1        | 1.75%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1        | 1.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1        | 1.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1        | 1.75%   |
| Broadcom / LSI MegaRAID SAS 2008 [Falcon]                                      | 1        | 1.75%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 1        | 1.75%   |
| AMD FCH SATA Controller D                                                      | 1        | 1.75%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 1        | 1.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 31       | 62%     |
| NVMe | 9        | 18%     |
| IDE  | 9        | 18%     |
| RAID | 1        | 2%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 25       | 59.52%  |
| AMD    | 11       | 26.19%  |
| ARM    | 6        | 14.29%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| ARM Cortex-A72 r0p3                                       | 4        | 9.52%   |
| Intel Core i5-4570 CPU @ 3.20GHz                          | 2        | 4.76%   |
| Intel Core i3-10100F CPU @ 3.60GHz                        | 2        | 4.76%   |
| Intel Core i3-10100 CPU @ 3.60GHz                         | 2        | 4.76%   |
| Intel Xeon CPU X5690 @ 3.47GHz                            | 1        | 2.38%   |
| Intel Xeon CPU E5520 @ 2.27GHz                            | 1        | 2.38%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz                       | 1        | 2.38%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz               | 1        | 2.38%   |
| Intel Pentium 4 CPU 2.40GHz ("GenuineIntel" 686-class)    | 1        | 2.38%   |
| Intel Genuine processor 600MHz ("GenuineIntel" 686-class) | 1        | 2.38%   |
| Intel Core i7-9700K CPU @ 3.60GHz                         | 1        | 2.38%   |
| Intel Core i7-6700 CPU @ 3.40GHz                          | 1        | 2.38%   |
| Intel Core i7-4790 CPU @ 3.60GHz                          | 1        | 2.38%   |
| Intel Core i7-3610QM CPU @ 2.30GHz                        | 1        | 2.38%   |
| Intel Core i7-2670QM CPU @ 2.20GHz                        | 1        | 2.38%   |
| Intel Core i5-4570T CPU @ 2.90GHz                         | 1        | 2.38%   |
| Intel Core i5-10400F CPU @ 2.90GHz                        | 1        | 2.38%   |
| Intel Core i3-5010U CPU @ 2.10GHz                         | 1        | 2.38%   |
| Intel Core i3-4010U CPU @ 1.70GHz                         | 1        | 2.38%   |
| Intel Core i3-3225 CPU @ 3.30GHz                          | 1        | 2.38%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz                     | 1        | 2.38%   |
| Intel Celeron N5105 @ 2.00GHz                             | 1        | 2.38%   |
| Intel Celeron CPU G1820 @ 2.70GHz                         | 1        | 2.38%   |
| ARM Cortex-A7 r0p4                                        | 1        | 2.38%   |
| ARM Cortex-A53 r0p4                                       | 1        | 2.38%   |
| AMD Ryzen 9 5950X 16-Core Processor                       | 1        | 2.38%   |
| AMD Ryzen 7 5800X 8-Core Processor                        | 1        | 2.38%   |
| AMD Ryzen 5 5600X 6-Core Processor                        | 1        | 2.38%   |
| AMD Ryzen 5 3600 6-Core Processor                         | 1        | 2.38%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics               | 1        | 2.38%   |
| AMD Processor model unknown                               | 1        | 2.38%   |
| AMD Phenom II X4 965 Processor                            | 1        | 2.38%   |
| AMD GX-412TC SOC                                          | 1        | 2.38%   |
| AMD Athlon II X4 640 Processor                            | 1        | 2.38%   |
| AMD Athlon II X2 B26 Processor                            | 1        | 2.38%   |
| AMD Athlon 3000G with Radeon Vega Graphics                | 1        | 2.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i3           | 7        | 16.67%  |
| ARM Cortex              | 6        | 14.29%  |
| Intel Core i7           | 5        | 11.9%   |
| Intel Core i5           | 4        | 9.52%   |
| Intel Xeon              | 3        | 7.14%   |
| Intel Celeron           | 2        | 4.76%   |
| AMD Ryzen 5             | 2        | 4.76%   |
| Other                   | 1        | 2.38%   |
| Intel Pentium Dual-Core | 1        | 2.38%   |
| Intel Pentium 4         | 1        | 2.38%   |
| Intel Genuine           | 1        | 2.38%   |
| Intel Core 2 Quad       | 1        | 2.38%   |
| AMD Ryzen 9             | 1        | 2.38%   |
| AMD Ryzen 7             | 1        | 2.38%   |
| AMD Ryzen 3             | 1        | 2.38%   |
| AMD Phenom II X4        | 1        | 2.38%   |
| AMD GX                  | 1        | 2.38%   |
| AMD Athlon II X4        | 1        | 2.38%   |
| AMD Athlon II X2        | 1        | 2.38%   |
| AMD Athlon              | 1        | 2.38%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 17       | 40.48%  |
| Unknown | 10       | 23.81%  |
| 2       | 6        | 14.29%  |
| 1       | 3        | 7.14%   |
| 12      | 2        | 4.76%   |
| 8       | 2        | 4.76%   |
| 32      | 1        | 2.38%   |
| 6       | 1        | 2.38%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 27       | 64.29%  |
| Unknown | 13       | 30.95%  |
| 2       | 2        | 4.76%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 15       | 35.71%  |
| 2       | 14       | 33.33%  |
| Unknown | 13       | 30.95%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Unknown     | 9        | 21.43%  |
| Haswell     | 6        | 14.29%  |
| K10         | 4        | 9.52%   |
| CometLake   | 4        | 9.52%   |
| Zen 3       | 2        | 4.76%   |
| Skylake     | 2        | 4.76%   |
| Penryn      | 2        | 4.76%   |
| IvyBridge   | 2        | 4.76%   |
| Zen+        | 1        | 2.38%   |
| Zen 2       | 1        | 2.38%   |
| Zen         | 1        | 2.38%   |
| Westmere    | 1        | 2.38%   |
| SandyBridge | 1        | 2.38%   |
| Puma        | 1        | 2.38%   |
| P6          | 1        | 2.38%   |
| NetBurst    | 1        | 2.38%   |
| Nehalem     | 1        | 2.38%   |
| KabyLake    | 1        | 2.38%   |
| Broadwell   | 1        | 2.38%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| AMD                        | 17       | 47.22%  |
| Intel                      | 12       | 33.33%  |
| Nvidia                     | 5        | 13.89%  |
| Matrox Electronics Systems | 1        | 2.78%   |
| ASPEED Technology          | 1        | 2.78%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 4        | 10.81%  |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                            | 3        | 8.11%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                      | 2        | 5.41%   |
| AMD RS880 [Radeon HD 4200]                                                    | 2        | 5.41%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                       | 2        | 5.41%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                              | 2        | 5.41%   |
| Nvidia NV28 [GeForce4 Ti 4200 AGP 8x]                                         | 1        | 2.7%    |
| Nvidia GK208B [GeForce GT 710]                                                | 1        | 2.7%    |
| Nvidia GF108M [NVS 5400M]                                                     | 1        | 2.7%    |
| Nvidia GF108M [GeForce GT 540M]                                               | 1        | 2.7%    |
| Nvidia G96C [GeForce 9500 GT]                                                 | 1        | 2.7%    |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)             | 1        | 2.7%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 1        | 2.7%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 1        | 2.7%    |
| Intel JasperLake [UHD Graphics]                                               | 1        | 2.7%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                        | 1        | 2.7%    |
| Intel HD Graphics 5500                                                        | 1        | 2.7%    |
| Intel HD Graphics 530                                                         | 1        | 2.7%    |
| Intel Haswell-ULT Integrated Graphics Controller                              | 1        | 2.7%    |
| ASPEED Technology ASPEED Graphics Family                                      | 1        | 2.7%    |
| AMD RV770 [Radeon HD 4850]                                                    | 1        | 2.7%    |
| AMD RV710/M92 [Mobility Radeon HD 4350/4550]                                  | 1        | 2.7%    |
| AMD RS880 [Radeon HD 4250]                                                    | 1        | 2.7%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 1        | 2.7%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 1        | 2.7%    |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                | 1        | 2.7%    |
| AMD Juniper XT [Radeon HD 6770]                                               | 1        | 2.7%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 1        | 2.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| 1 x AMD     | 16       | 38.1%   |
| 1 x Intel   | 10       | 23.81%  |
| Other       | 7        | 16.67%  |
| 1 x Nvidia  | 5        | 11.9%   |
| 2 x Intel   | 1        | 2.38%   |
| 1 x Matrox  | 1        | 2.38%   |
| Intel + AMD | 1        | 2.38%   |
| 1 x ASPEED  | 1        | 2.38%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Desktops | Percent |
|---------|----------|---------|
| Free    | 31       | 73.81%  |
| Unknown | 11       | 26.19%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 42       | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Philips              | 7        | 30.43%  |
| Dell                 | 3        | 13.04%  |
| Samsung Electronics  | 2        | 8.7%    |
| MSI                  | 2        | 8.7%    |
| ViewSonic            | 1        | 4.35%   |
| Lenovo               | 1        | 4.35%   |
| InfoVision           | 1        | 4.35%   |
| Hewlett-Packard      | 1        | 4.35%   |
| Goldstar             | 1        | 4.35%   |
| BenQ                 | 1        | 4.35%   |
| AOC                  | 1        | 4.35%   |
| Ancor Communications | 1        | 4.35%   |
| Acer                 | 1        | 4.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                  | 6        | 26.09%  |
| ViewSonic LCD Monitor VSCC42B 1920x1080 480x270mm 21.7-inch            | 1        | 4.35%   |
| Samsung Electronics SyncMaster SAM03CF 1280x1024 340x270mm 17.1-inch   | 1        | 4.35%   |
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1210x680mm 54.6-inch | 1        | 4.35%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                | 1        | 4.35%   |
| MSI MP242 MSI30A1 1920x1080 530x300mm 24.0-inch                        | 1        | 4.35%   |
| MSI MAG241C MSI3EA2 1920x1080 520x290mm 23.4-inch                      | 1        | 4.35%   |
| Lenovo LEN S24e-10 LEN61CA 1920x1080 530x300mm 24.0-inch               | 1        | 4.35%   |
| InfoVision LCD Monitor IVO04E3 1366x768 280x160mm 12.7-inch            | 1        | 4.35%   |
| Hewlett-Packard x23LED HWP2912 1920x1080 510x290mm 23.1-inch           | 1        | 4.35%   |
| Goldstar L1752T GSM4434 1280x1024 340x270mm 17.1-inch                  | 1        | 4.35%   |
| Dell LCD Monitor DELF003 1440x900 410x260mm 19.1-inch                  | 1        | 4.35%   |
| Dell E1916H DELF064 1366x768 410x230mm 18.5-inch                       | 1        | 4.35%   |
| Dell 2001FP DELA007 1600x1200 410x310mm 20.2-inch                      | 1        | 4.35%   |
| BenQ G2255 BNQ78B7 1920x1080 480x270mm 21.7-inch                       | 1        | 4.35%   |
| AOC 2269WM AOC2269 1920x1080 480x270mm 21.7-inch                       | 1        | 4.35%   |
| Ancor Communications ASUS VW199 ACI19ED 1440x900 410x260mm 19.1-inch   | 1        | 4.35%   |
| Acer XZ342CK ACR078B 3440x1440 800x330mm 34.1-inch                     | 1        | 4.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Desktops | Percent |
|------------------|----------|---------|
| 1920x1080 (FHD)  | 12       | 57.14%  |
| 1440x900 (WXGA+) | 2        | 9.52%   |
| 1366x768 (WXGA)  | 2        | 9.52%   |
| 1280x1024 (SXGA) | 2        | 9.52%   |
| 3840x2160 (4K)   | 1        | 4.76%   |
| 3440x1440        | 1        | 4.76%   |
| 1600x1200        | 1        | 4.76%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 21     | 8        | 36.36%  |
| 24     | 3        | 13.64%  |
| 23     | 2        | 9.09%   |
| 19     | 2        | 9.09%   |
| 17     | 2        | 9.09%   |
| 54     | 1        | 4.55%   |
| 34     | 1        | 4.55%   |
| 20     | 1        | 4.55%   |
| 18     | 1        | 4.55%   |
| 12     | 1        | 4.55%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 12       | 54.55%  |
| 501-600     | 5        | 22.73%  |
| 301-350     | 2        | 9.09%   |
| 701-800     | 1        | 4.55%   |
| 201-300     | 1        | 4.55%   |
| 1001-1500   | 1        | 4.55%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 15       | 71.43%  |
| 5/4   | 2        | 9.52%   |
| 16/10 | 2        | 9.52%   |
| 4/3   | 1        | 4.76%   |
| 21/9  | 1        | 4.76%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 12       | 57.14%  |
| 151-200        | 3        | 14.29%  |
| 141-150        | 3        | 14.29%  |
| More than 1000 | 1        | 4.76%   |
| 61-70          | 1        | 4.76%   |
| 351-500        | 1        | 4.76%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 11       | 52.38%  |
| 101-120 | 9        | 42.86%  |
| 121-160 | 1        | 4.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 22       | 52.38%  |
| 0     | 18       | 42.86%  |
| 3     | 1        | 2.38%   |
| 2     | 1        | 2.38%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 23       | 51.11%  |
| Intel                             | 14       | 31.11%  |
| Qualcomm Atheros Communications   | 2        | 4.44%   |
| Qualcomm Atheros                  | 2        | 4.44%   |
| Qcom                              | 1        | 2.22%   |
| Ericsson Business Mobile Networks | 1        | 2.22%   |
| Broadcom                          | 1        | 2.22%   |
| AVM                               | 1        | 2.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 17       | 32.08%  |
| Intel I210 Gigabit Network Connection                                         | 3        | 5.66%   |
| Intel 82574L Gigabit Network Connection                                       | 3        | 5.66%   |
| Realtek RTL8125 2.5GbE Controller                                             | 2        | 3.77%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2        | 3.77%   |
| Qualcomm Atheros AR9271 802.11n                                               | 2        | 3.77%   |
| Intel I211 Gigabit Network Connection                                         | 2        | 3.77%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 1        | 1.89%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 1.89%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 1        | 1.89%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 1        | 1.89%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                 | 1        | 1.89%   |
| Qcom RT73 USB Wireless LAN Card                                               | 1        | 1.89%   |
| Intel Wireless 7260                                                           | 1        | 1.89%   |
| Intel Wi-Fi 6 AX200                                                           | 1        | 1.89%   |
| Intel Ethernet Controller I225-V                                              | 1        | 1.89%   |
| Intel Ethernet Connection I218-LM                                             | 1        | 1.89%   |
| Intel Ethernet Connection I217-LM                                             | 1        | 1.89%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1        | 1.89%   |
| Intel Centrino Advanced-N 6235                                                | 1        | 1.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 1        | 1.89%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1        | 1.89%   |
| Intel 82579V Gigabit Network Connection                                       | 1        | 1.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 1        | 1.89%   |
| Intel 82575EB Gigabit Network Connection                                      | 1        | 1.89%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 1.89%   |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module            | 1        | 1.89%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                        | 1        | 1.89%   |
| AVM A1 ISDN [Fritz]                                                           | 1        | 1.89%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 4        | 40%     |
| Qualcomm Atheros Communications | 2        | 20%     |
| Realtek Semiconductor           | 1        | 10%     |
| Qualcomm Atheros                | 1        | 10%     |
| Qcom                            | 1        | 10%     |
| Broadcom                        | 1        | 10%     |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR9271 802.11n                                | 2        | 20%     |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1        | 10%     |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1        | 10%     |
| Qcom RT73 USB Wireless LAN Card                                | 1        | 10%     |
| Intel Wireless 7260                                            | 1        | 10%     |
| Intel Wi-Fi 6 AX200                                            | 1        | 10%     |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1        | 10%     |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 1        | 10%     |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 1        | 10%     |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 23       | 62.16%  |
| Intel                 | 13       | 35.14%  |
| Qualcomm Atheros      | 1        | 2.7%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 17       | 42.5%   |
| Intel I210 Gigabit Network Connection                                         | 3        | 7.5%    |
| Intel 82574L Gigabit Network Connection                                       | 3        | 7.5%    |
| Realtek RTL8125 2.5GbE Controller                                             | 2        | 5%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2        | 5%      |
| Intel I211 Gigabit Network Connection                                         | 2        | 5%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 2.5%    |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 1        | 2.5%    |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                 | 1        | 2.5%    |
| Intel Ethernet Controller I225-V                                              | 1        | 2.5%    |
| Intel Ethernet Connection I218-LM                                             | 1        | 2.5%    |
| Intel Ethernet Connection I217-LM                                             | 1        | 2.5%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1        | 2.5%    |
| Intel 82579V Gigabit Network Connection                                       | 1        | 2.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 1        | 2.5%    |
| Intel 82575EB Gigabit Network Connection                                      | 1        | 2.5%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 2.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 35       | 72.92%  |
| WiFi     | 10       | 20.83%  |
| Unknown  | 2        | 4.17%   |
| Modem    | 1        | 2.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 27       | 81.82%  |
| WiFi     | 6        | 18.18%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 19       | 45.24%  |
| 2     | 9        | 21.43%  |
| 0     | 7        | 16.67%  |
| 3     | 4        | 9.52%   |
| 4     | 2        | 4.76%   |
| 5     | 1        | 2.38%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 42       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Intel             | 4        | 66.67%  |
| Foxconn / Hon Hai | 1        | 16.67%  |
| Apple             | 1        | 16.67%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Intel Wireless-AC 3168 Bluetooth                            | 1        | 16.67%  |
| Intel Centrino Bluetooth Wireless Transceiver               | 1        | 16.67%  |
| Intel Bluetooth wireless interface                          | 1        | 16.67%  |
| Intel AX200 Bluetooth                                       | 1        | 16.67%  |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1        | 16.67%  |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1        | 16.67%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 21       | 47.73%  |
| AMD                 | 18       | 40.91%  |
| Nvidia              | 3        | 6.82%   |
| Creative Labs       | 1        | 2.27%   |
| C-Media Electronics | 1        | 2.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 5        | 8.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 4        | 6.9%    |
| Intel Comet Lake PCH-V cAVS                                                       | 4        | 6.9%    |
| AMD Starship/Matisse HD Audio Controller                                          | 4        | 6.9%    |
| AMD SBx00 Azalia (Intel HDA)                                                      | 4        | 6.9%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 3        | 5.17%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3        | 5.17%   |
| Nvidia GF108 High Definition Audio Controller                                     | 2        | 3.45%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 2        | 3.45%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                      | 2        | 3.45%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 2        | 3.45%   |
| AMD Navi 10 HDMI Audio                                                            | 2        | 3.45%   |
| AMD Family 17h/19h HD Audio Controller                                            | 2        | 3.45%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 2        | 3.45%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 1        | 1.72%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 1        | 1.72%   |
| Intel Jasper Lake HD Audio                                                        | 1        | 1.72%   |
| Intel Haswell-ULT HD Audio Controller                                             | 1        | 1.72%   |
| Intel Cannon Lake PCH cAVS                                                        | 1        | 1.72%   |
| Intel Broadwell-U Audio Controller                                                | 1        | 1.72%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 1        | 1.72%   |
| Intel 8 Series HD Audio Controller                                                | 1        | 1.72%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 1        | 1.72%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 1        | 1.72%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                                | 1        | 1.72%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                     | 1        | 1.72%   |
| AMD RV770 HDMI Audio [Radeon HD 4850/4870]                                        | 1        | 1.72%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 1        | 1.72%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 1        | 1.72%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                    | 1        | 1.72%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 1        | 1.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Kingston | 1        | 50%     |
| Corsair  | 1        | 50%     |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Kingston RAM KF3600C18D4/32GX 32GB DIMM DDR4 2400MT/s | 1        | 50%     |
| Corsair RAM CML16GX3M2A1600C9 8GB DIMM DDR3 1600MT/s  | 1        | 50%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 1        | 50%     |
| DDR3 | 1        | 50%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 2        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 32768 | 1        | 50%     |
| 8192  | 1        | 50%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 2400  | 1        | 50%     |
| 1600  | 1        | 50%     |

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


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Ricoh               | 1        | 50%     |
| Chicony Electronics | 1        | 50%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Ricoh USB2.0 Camera                  | 1        | 50%     |
| Chicony Integrated Camera [ThinkPad] | 1        | 50%     |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Validity Sensors | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor | 1        | 100%    |

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
| 1     | 18       | 42.86%  |
| 0     | 16       | 38.1%   |
| 2     | 6        | 14.29%  |
| 3     | 2        | 4.76%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 19       | 54.29%  |
| Graphics card            | 5        | 14.29%  |
| Firewire controller      | 5        | 14.29%  |
| Net/wireless             | 2        | 5.71%   |
| Storage/ide              | 1        | 2.86%   |
| Storage                  | 1        | 2.86%   |
| Sound                    | 1        | 2.86%   |
| Network                  | 1        | 2.86%   |

