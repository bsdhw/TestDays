FreeBSD 14.0-CURRENT - Tested Hardware & Statistics (Desktops)
--------------------------------------------------------------

A project to collect tested hardware configurations for FreeBSD 14.0-CURRENT.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://bsd-hardware.info/?view=trends

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

| Vendor        | Model                   | Probe                                                     | Date         |
|---------------|-------------------------|-----------------------------------------------------------|--------------|
| HP            | 83E1                    | [d8e995126f](https://bsd-hardware.info/?probe=d8e995126f) | Feb 10, 2022 |
| Gigabyte      | B450M DS3H-CF           | [825d20fcf7](https://bsd-hardware.info/?probe=825d20fcf7) | Jan 14, 2022 |
| Gigabyte      | B450M DS3H-CF           | [b953d9d2e6](https://bsd-hardware.info/?probe=b953d9d2e6) | Jan 13, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING | [2cc4698cbc](https://bsd-hardware.info/?probe=2cc4698cbc) | Jan 09, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING | [2481037b2a](https://bsd-hardware.info/?probe=2481037b2a) | Jan 09, 2022 |
| ASUSTek       | TUF GAMING B550-PLUS    | [ea4719600a](https://bsd-hardware.info/?probe=ea4719600a) | Jan 05, 2022 |
| ASRock        | B450 Steel Legend       | [e67007df20](https://bsd-hardware.info/?probe=e67007df20) | Jan 01, 2022 |
| friendlyel... | nanopi-m4               | [bb29e50061](https://bsd-hardware.info/?probe=bb29e50061) | Dec 27, 2021 |
| khadas        | edge-v                  | [42c428aac0](https://bsd-hardware.info/?probe=42c428aac0) | Dec 26, 2021 |
| Unknown       | Unknown                 | [b726a1b3e3](https://bsd-hardware.info/?probe=b726a1b3e3) | Dec 11, 2021 |
| ASUSTek       | PRIME X570-PRO          | [9a8d19aa04](https://bsd-hardware.info/?probe=9a8d19aa04) | Dec 11, 2021 |
| Unknown       | Unknown                 | [7633cb9296](https://bsd-hardware.info/?probe=7633cb9296) | Dec 11, 2021 |
| Unknown       | Unknown                 | [d05fb15725](https://bsd-hardware.info/?probe=d05fb15725) | Nov 22, 2021 |
| Beckhoff A... | CX51x0 G3               | [6db720018b](https://bsd-hardware.info/?probe=6db720018b) | Oct 25, 2021 |
| Beckhoff A... | CX20x3 G1               | [a49fbd5ce3](https://bsd-hardware.info/?probe=a49fbd5ce3) | Oct 25, 2021 |
| ASUSTek       | PRIME Z590-A            | [1aa5ced5a0](https://bsd-hardware.info/?probe=1aa5ced5a0) | Sep 23, 2021 |
| Gigabyte      | X399 DESIGNARE EX-CF    | [a78cc6a11b](https://bsd-hardware.info/?probe=a78cc6a11b) | Sep 04, 2021 |
| Unknown       | Unknown                 | [4a3836de00](https://bsd-hardware.info/?probe=4a3836de00) | Jul 08, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR   | [edebe87739](https://bsd-hardware.info/?probe=edebe87739) | Jun 04, 2021 |
| Gigabyte      | B550I AORUS PRO AX      | [62b9ea2794](https://bsd-hardware.info/?probe=62b9ea2794) | May 14, 2021 |
| ASUSTek       | P8H77-M PRO             | [b3acafeb1a](https://bsd-hardware.info/?probe=b3acafeb1a) | May 09, 2021 |
| ASUSTek       | P8H77-M PRO             | [86cec3b874](https://bsd-hardware.info/?probe=86cec3b874) | May 09, 2021 |
| pine64        | pinebook-pro-rk3399     | [79713a2668](https://bsd-hardware.info/?probe=79713a2668) | Apr 25, 2021 |
| pine64        | pinebook-pro-rk3399     | [0f04e5f048](https://bsd-hardware.info/?probe=0f04e5f048) | Apr 11, 2021 |
| Gigabyte      | X570 AORUS ELITE        | [325186171a](https://bsd-hardware.info/?probe=325186171a) | Apr 02, 2021 |
| pine64        | pinebook-pro-rk3399     | [ea524ab4c4](https://bsd-hardware.info/?probe=ea524ab4c4) | Mar 28, 2021 |
| pine64        | pinebook-pro-rk3399     | [835da13d39](https://bsd-hardware.info/?probe=835da13d39) | Mar 18, 2021 |
| Gigabyte      | 970A-UD3P               | [cc3151bc6f](https://bsd-hardware.info/?probe=cc3151bc6f) | Mar 17, 2021 |
| MSI           | B450 GAMING PLUS        | [547fd655f0](https://bsd-hardware.info/?probe=547fd655f0) | Mar 13, 2021 |
| pine64        | pinebook-pro-rk3399     | [c00bcdcc87](https://bsd-hardware.info/?probe=c00bcdcc87) | Mar 06, 2021 |
| pine64        | pinebook-pro-rk3399     | [3abcd73d48](https://bsd-hardware.info/?probe=3abcd73d48) | Feb 26, 2021 |
| Gigabyte      | X570 AORUS MASTER       | [29936dd1c0](https://bsd-hardware.info/?probe=29936dd1c0) | Feb 25, 2021 |
| Unknown       | Unknown                 | [74b11992d7](https://bsd-hardware.info/?probe=74b11992d7) | Feb 20, 2021 |
| Raspberry ... | rpi                     | [92ee9b3619](https://bsd-hardware.info/?probe=92ee9b3619) | Feb 18, 2021 |
| pine64        | pinebook-pro-rk3399     | [b750f83194](https://bsd-hardware.info/?probe=b750f83194) | Feb 17, 2021 |
| ASUSTek       | PRIME B450M-A           | [ba7f82b343](https://bsd-hardware.info/?probe=ba7f82b343) | Feb 12, 2021 |
| pine64        | pinebook-pro-rk3399     | [2befc5e754](https://bsd-hardware.info/?probe=2befc5e754) | Feb 10, 2021 |
| pine64        | pinebook-pro-rk3399     | [5a55b22f44](https://bsd-hardware.info/?probe=5a55b22f44) | Feb 09, 2021 |
| Dell          | 0D9JG3 A00              | [65dd4083c5](https://bsd-hardware.info/?probe=65dd4083c5) | Feb 09, 2021 |
| pine64        | pinebook-pro-rk3399     | [97e72f0066](https://bsd-hardware.info/?probe=97e72f0066) | Feb 06, 2021 |
| pine64        | pinebook-pro-rk3399     | [1720175648](https://bsd-hardware.info/?probe=1720175648) | Jan 27, 2021 |
| pine64        | pinebook-pro-rk3399     | [2338de9efc](https://bsd-hardware.info/?probe=2338de9efc) | Jan 24, 2021 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 20       | 71.43%  |
| arm64 | 6        | 21.43%  |
| riscv | 1        | 3.57%   |
| arm   | 1        | 3.57%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| KDE5    | 10       | 34.48%  |
| Console | 10       | 34.48%  |
| XFCE    | 2        | 6.9%    |
| Openbox | 2        | 6.9%    |
| MATE    | 2        | 6.9%    |
| TWM     | 1        | 3.45%   |
| i3      | 1        | 3.45%   |
| GNOME   | 1        | 3.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 19       | 65.52%  |
| Console | 10       | 34.48%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 14       | 48.28%  |
| SDDM    | 7        | 24.14%  |
| SLiM    | 4        | 13.79%  |
| GDM     | 3        | 10.34%  |
| XDM     | 1        | 3.45%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| C       | 13       | 46.43%  |
| en_US   | 4        | 14.29%  |
| uk_UA   | 3        | 10.71%  |
| de_DE   | 3        | 10.71%  |
| Unknown | 3        | 10.71%  |
| sv_SE   | 1        | 3.57%   |
| de_CH   | 1        | 3.57%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 25       | 89.29%  |
| BIOS | 3        | 10.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Zfs  | 21       | 75%     |
| Ufs  | 7        | 25%     |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 25       | 89.29%  |
| MBR  | 3        | 10.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUSTek Computer        | 7        | 25%     |
| Gigabyte Technology     | 6        | 21.43%  |
| Unknown                 | 5        | 17.86%  |
| Beckhoff Automation     | 2        | 7.14%   |
| Raspberry Pi Foundation | 1        | 3.57%   |
| pine64                  | 1        | 3.57%   |
| MSI                     | 1        | 3.57%   |
| khadas                  | 1        | 3.57%   |
| Hewlett-Packard         | 1        | 3.57%   |
| friendlyelec            | 1        | 3.57%   |
| Dell                    | 1        | 3.57%   |
| ASRock                  | 1        | 3.57%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| Unknown                         | 5        | 17.86%  |
| RPi rpi                         | 1        | 3.57%   |
| pine64 pinebook-pro-rk3399      | 1        | 3.57%   |
| MSI MS-7B86                     | 1        | 3.57%   |
| khadas edge-v                   | 1        | 3.57%   |
| HP EliteDesk 800 G4 SFF         | 1        | 3.57%   |
| Gigabyte X570 AORUS MASTER      | 1        | 3.57%   |
| Gigabyte X570 AORUS ELITE       | 1        | 3.57%   |
| Gigabyte X399 DESIGNARE EX      | 1        | 3.57%   |
| Gigabyte B550I AORUS PRO AX     | 1        | 3.57%   |
| Gigabyte B450M DS3H             | 1        | 3.57%   |
| Gigabyte 970A-UD3P              | 1        | 3.57%   |
| friendlyelec nanopi-m4          | 1        | 3.57%   |
| Dell OptiPlex 5080              | 1        | 3.57%   |
| Beckhoff Automation CX2033-0185 | 1        | 3.57%   |
| Beckhoff Automation CBxx63      | 1        | 3.57%   |
| ASUS TUF GAMING B550-PLUS       | 1        | 3.57%   |
| ASUS ROG STRIX B550-I GAMING    | 1        | 3.57%   |
| ASUS PRIME Z590-A               | 1        | 3.57%   |
| ASUS PRIME X570-PRO             | 1        | 3.57%   |
| ASUS PRIME B450M-GAMING/BR      | 1        | 3.57%   |
| ASUS PRIME B450M-A              | 1        | 3.57%   |
| ASUS P8H77-M PRO                | 1        | 3.57%   |
| ASRock B450 Steel Legend        | 1        | 3.57%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| Unknown                         | 5        | 17.86%  |
| ASUS PRIME                      | 4        | 14.29%  |
| Gigabyte X570                   | 2        | 7.14%   |
| RPi rpi                         | 1        | 3.57%   |
| pine64 pinebook-pro-rk3399      | 1        | 3.57%   |
| MSI MS-7B86                     | 1        | 3.57%   |
| khadas edge-v                   | 1        | 3.57%   |
| HP EliteDesk                    | 1        | 3.57%   |
| Gigabyte X399                   | 1        | 3.57%   |
| Gigabyte B550I                  | 1        | 3.57%   |
| Gigabyte B450M                  | 1        | 3.57%   |
| Gigabyte 970A-UD3P              | 1        | 3.57%   |
| friendlyelec nanopi-m4          | 1        | 3.57%   |
| Dell OptiPlex                   | 1        | 3.57%   |
| Beckhoff Automation CX2033-0185 | 1        | 3.57%   |
| Beckhoff Automation CBxx63      | 1        | 3.57%   |
| ASUS TUF                        | 1        | 3.57%   |
| ASUS ROG                        | 1        | 3.57%   |
| ASUS P8H77-M                    | 1        | 3.57%   |
| ASRock B450                     | 1        | 3.57%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2021    | 9        | 32.14%  |
| 2019    | 5        | 17.86%  |
| 2020    | 4        | 14.29%  |
| 2018    | 4        | 14.29%  |
| Unknown | 4        | 14.29%  |
| 2016    | 1        | 3.57%   |
| 2012    | 1        | 3.57%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 28       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 28       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 10       | 35.71%  |
| 64.01-256.0 | 5        | 17.86%  |
| 4.01-8.0    | 4        | 14.29%  |
| 32.01-64.0  | 4        | 14.29%  |
| 8.01-16.0   | 2        | 7.14%   |
| 0.51-1.0    | 2        | 7.14%   |
| 2.01-3.0    | 1        | 3.57%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 9        | 32.14%  |
| 0.51-1.0    | 9        | 32.14%  |
| 0.01-0.5    | 6        | 21.43%  |
| 3.01-4.0    | 1        | 3.57%   |
| 64.01-256.0 | 1        | 3.57%   |
| 16.01-24.0  | 1        | 3.57%   |
| 0           | 1        | 3.57%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 8        | 28.57%  |
| 0      | 8        | 28.57%  |
| 3      | 4        | 14.29%  |
| 6      | 3        | 10.71%  |
| 2      | 3        | 10.71%  |
| 5      | 1        | 3.57%   |
| 4      | 1        | 3.57%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 21       | 75%     |
| Yes       | 7        | 25%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 21       | 75%     |
| No        | 7        | 25%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 18       | 64.29%  |
| Yes       | 10       | 35.71%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 23       | 82.14%  |
| Yes       | 5        | 17.86%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Germany      | 5        | 17.86%  |
| Ukraine      | 4        | 14.29%  |
| UK           | 4        | 14.29%  |
| USA          | 3        | 10.71%  |
| Brazil       | 3        | 10.71%  |
| Russia       | 2        | 7.14%   |
| Japan        | 2        | 7.14%   |
| Switzerland  | 1        | 3.57%   |
| Sweden       | 1        | 3.57%   |
| Saudi Arabia | 1        | 3.57%   |
| France       | 1        | 3.57%   |
| Austria      | 1        | 3.57%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Kyiv                    | 3        | 10%     |
| ЕЊta-ku               | 2        | 6.67%   |
| Rio de Janeiro          | 2        | 6.67%   |
| Rietberg                | 2        | 6.67%   |
| Moscow                  | 2        | 6.67%   |
| Egham                   | 2        | 6.67%   |
| Zurich                  | 1        | 3.33%   |
| Zaporizhzhya            | 1        | 3.33%   |
| Sollentuna              | 1        | 3.33%   |
| Santa Monica            | 1        | 3.33%   |
| Riyadh                  | 1        | 3.33%   |
| Northeim                | 1        | 3.33%   |
| Lake Forest             | 1        | 3.33%   |
| Kunitachi               | 1        | 3.33%   |
| Jaboatao dos Guararapes | 1        | 3.33%   |
| Graz                    | 1        | 3.33%   |
| Fuchu                   | 1        | 3.33%   |
| Cologne                 | 1        | 3.33%   |
| Claix                   | 1        | 3.33%   |
| Chicago                 | 1        | 3.33%   |
| Cambridge               | 1        | 3.33%   |
| Berlin                  | 1        | 3.33%   |
| Beckton                 | 1        | 3.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 11       | 17     | 31.43%  |
| Seagate             | 4        | 5      | 11.43%  |
| Toshiba             | 3        | 4      | 8.57%   |
| Samsung Electronics | 3        | 5      | 8.57%   |
| Crucial             | 3        | 8      | 8.57%   |
| Kingston            | 2        | 3      | 5.71%   |
| A-DATA Technology   | 2        | 2      | 5.71%   |
| SK Hynix            | 1        | 1      | 2.86%   |
| PNY                 | 1        | 1      | 2.86%   |
| Micron Technology   | 1        | 2      | 2.86%   |
| Intel               | 1        | 1      | 2.86%   |
| HGST                | 1        | 2      | 2.86%   |
| GOODRAM             | 1        | 1      | 2.86%   |
| Apacer              | 1        | 1      | 2.86%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 2        | 4.88%   |
| Toshiba MQ04ABF100 1TB               | 2        | 4.88%   |
| WDC WDS250G2B0C-00PXH0 250GB         | 1        | 2.44%   |
| WDC WDS100T2B0A-00SM50 1TB           | 1        | 2.44%   |
| WDC WD60EFRX-68TGBN1 6TB             | 1        | 2.44%   |
| WDC WD5002ABYS-18B1B0 500GB          | 1        | 2.44%   |
| WDC WD40EZRZ-75GXCB0 4TB             | 1        | 2.44%   |
| WDC WD30EFRX-68EUZN0 3TB             | 1        | 2.44%   |
| WDC WD120EFAX-68UNTN0 12TB           | 1        | 2.44%   |
| WDC WD10SPZX-21Z10T0 1TB             | 1        | 2.44%   |
| WDC WD10JMVW-11AJGS3 1TB             | 1        | 2.44%   |
| WDC WD10EZEX-60WN4A0 1TB             | 1        | 2.44%   |
| WDC WD10EZEX-00RKKA0 1TB             | 1        | 2.44%   |
| WDC WD10EARX-00N0YB0 1TB             | 1        | 2.44%   |
| Toshiba MG09ACA18TE 18TB             | 1        | 2.44%   |
| SK Hynix HFS128G39TND-N210A 128GB    | 1        | 2.44%   |
| Seagate ST4000DM000-1F2168 4TB       | 1        | 2.44%   |
| Seagate ST3750640AS 752GB            | 1        | 2.44%   |
| Seagate ST32000641AS 2TB             | 1        | 2.44%   |
| Seagate ST3000DM007-1WY10G 3TB       | 1        | 2.44%   |
| Seagate ST3000DM001-1ER166 3TB       | 1        | 2.44%   |
| Samsung SSD 870 QVO 1TB              | 1        | 2.44%   |
| Samsung SSD 860 EVO 4TB              | 1        | 2.44%   |
| Samsung SSD 860 EVO 250GB            | 1        | 2.44%   |
| Samsung SSD 850 EVO 500GB            | 1        | 2.44%   |
| Samsung SSD 850 EVO 250GB            | 1        | 2.44%   |
| PNY CS3030 1TB SSD                   | 1        | 2.44%   |
| Micron 2300_MTFDHBA512TDV 512GB      | 1        | 2.44%   |
| Kingston SA400S37240G 240GB          | 1        | 2.44%   |
| Kingston SA2000M81000G 1TB           | 1        | 2.44%   |
| Intel SSDPEKKW256G8 256GB            | 1        | 2.44%   |
| HGST HTS721010A9E630 1TB             | 1        | 2.44%   |
| GOODRAM SSDPR-CX400-256-G2 256GB     | 1        | 2.44%   |
| Crucial CT500P1SSD8 500GB            | 1        | 2.44%   |
| Crucial CT250MX500SSD1 250GB         | 1        | 2.44%   |
| Crucial CT1000MX500SSD4 1TB          | 1        | 2.44%   |
| Apacer 16GB SATA Flash Drive         | 1        | 2.44%   |
| A-DATA SU760 1TB                     | 1        | 2.44%   |
| A-DATA ICFS332-016GW 16GB            | 1        | 2.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 7        | 12     | 46.67%  |
| Seagate | 4        | 5      | 26.67%  |
| Toshiba | 3        | 4      | 20%     |
| HGST    | 1        | 2      | 6.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 5      | 25%     |
| Crucial             | 2        | 7      | 16.67%  |
| A-DATA Technology   | 2        | 2      | 16.67%  |
| WDC                 | 1        | 2      | 8.33%   |
| SK Hynix            | 1        | 1      | 8.33%   |
| Kingston            | 1        | 2      | 8.33%   |
| GOODRAM             | 1        | 1      | 8.33%   |
| Apacer              | 1        | 1      | 8.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 12       | 21     | 38.71%  |
| HDD  | 11       | 23     | 35.48%  |
| NVMe | 8        | 9      | 25.81%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 16       | 44     | 66.67%  |
| NVMe | 8        | 9      | 33.33%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.51-1.0   | 9        | 14     | 33.33%  |
| 0.01-0.5   | 9        | 16     | 33.33%  |
| 3.01-4.0   | 2        | 3      | 7.41%   |
| 2.01-3.0   | 2        | 3      | 7.41%   |
| 10.01-20.0 | 2        | 3      | 7.41%   |
| 1.01-2.0   | 2        | 2      | 7.41%   |
| 4.01-10.0  | 1        | 3      | 3.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 8        | 28.57%  |
| 1-20           | 6        | 21.43%  |
| 251-500        | 5        | 17.86%  |
| 501-1000       | 4        | 14.29%  |
| 2001-3000      | 2        | 7.14%   |
| More than 3000 | 1        | 3.57%   |
| 21-50          | 1        | 3.57%   |
| 51-100         | 1        | 3.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 18       | 62.07%  |
| 21-50     | 7        | 24.14%  |
| 251-500   | 1        | 3.45%   |
| 1001-2000 | 1        | 3.45%   |
| 501-1000  | 1        | 3.45%   |
| 0         | 1        | 3.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                       | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC WD60EFRX-68TGBN1 6TB    | 1        | 3      | 50%     |
| WDC WD5002ABYS-18B1B0 500GB | 1        | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 2        | 4      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 2        | 4      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 2        | 4      | 100%    |

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


| Status  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Works   | 20       | 49     | 90.91%  |
| Malfunc | 2        | 4      | 9.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| AMD                         | 14       | 37.84%  |
| Intel                       | 7        | 18.92%  |
| Sandisk                     | 4        | 10.81%  |
| Samsung Electronics         | 3        | 8.11%   |
| Silicon Motion              | 2        | 5.41%   |
| VMware                      | 1        | 2.7%    |
| Phison Electronics          | 1        | 2.7%    |
| Micron/Crucial Technology   | 1        | 2.7%    |
| Micron Technology           | 1        | 2.7%    |
| Marvell Technology Group    | 1        | 2.7%    |
| Kingston Technology Company | 1        | 2.7%    |
| ASMedia Technology          | 1        | 2.7%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                         | 10       | 22.22%  |
| AMD 400 Series Chipset SATA Controller                                      | 5        | 11.11%  |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                    | 3        | 6.67%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                             | 2        | 4.44%   |
| Sandisk WD Blue SN550 NVMe SSD                                              | 2        | 4.44%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                  | 2        | 4.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                               | 2        | 4.44%   |
| Unknown                                                                     | 2        | 4.44%   |
| VMware SATA AHCI controller                                                 | 1        | 2.22%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                               | 1        | 2.22%   |
| Phison E12 NVMe Controller                                                  | 1        | 2.22%   |
| Micron/Crucial P1 NVMe PCIe SSD                                             | 1        | 2.22%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                       | 1        | 2.22%   |
| Kingston Company A2000 NVMe SSD                                             | 1        | 2.22%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                     | 1        | 2.22%   |
| Intel Comet Lake SATA AHCI Controller                                       | 1        | 2.22%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                  | 1        | 2.22%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                      | 1        | 2.22%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                              | 1        | 2.22%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode] | 1        | 2.22%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode] | 1        | 2.22%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                        | 1        | 2.22%   |
| ASMedia ASM1062 Serial ATA Controller                                       | 1        | 2.22%   |
| AMD X399 Series Chipset SATA Controller                                     | 1        | 2.22%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                           | 1        | 2.22%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 19       | 52.78%  |
| NVMe | 15       | 41.67%  |
| RAID | 1        | 2.78%   |
| IDE  | 1        | 2.78%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| AMD     | 14       | 48.28%  |
| Unknown | 7        | 24.14%  |
| Intel   | 6        | 20.69%  |
| ARM     | 2        | 6.9%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
|                                                | 7        | 24.14%  |
| AMD Ryzen 5 5600G with Radeon Graphics         | 3        | 10.34%  |
| Intel Core i7-8750H CPU @ 2.20GHz              | 1        | 3.45%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 1        | 3.45%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 1        | 3.45%   |
| Intel Core i7-10700 CPU @ 2.90GHz              | 1        | 3.45%   |
| Intel Core i5-10500T CPU @ 2.30GHz             | 1        | 3.45%   |
| Intel Atom CPU E3827 @ 1.74GHz                 | 1        | 3.45%   |
| ARM Cortex-A72 r0p2                            | 1        | 3.45%   |
| ARM Cortex-A53 r0p4                            | 1        | 3.45%   |
| AMD Ryzen Threadripper 1950X 16-Core Processor | 1        | 3.45%   |
| AMD Ryzen Embedded V1202B with Radeon Vega Gfx | 1        | 3.45%   |
| AMD Ryzen 9 5950X 16-Core Processor            | 1        | 3.45%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 1        | 3.45%   |
| AMD Ryzen 9 3950X 16-Core Processor            | 1        | 3.45%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 1        | 3.45%   |
| AMD Ryzen 7 5800X 8-Core Processor             | 1        | 3.45%   |
| AMD Ryzen 7 2700X Eight-Core Processor         | 1        | 3.45%   |
| AMD Ryzen 5 2600X Six-Core Processor           | 1        | 3.45%   |
| AMD Ryzen 5 2600 Six-Core Processor            | 1        | 3.45%   |
| AMD FX-8320E Eight-Core Processor              | 1        | 3.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Other                  | 7        | 24.14%  |
| AMD Ryzen 5            | 5        | 17.24%  |
| Intel Core i7          | 4        | 13.79%  |
| AMD Ryzen 9            | 4        | 13.79%  |
| ARM Cortex             | 2        | 6.9%    |
| AMD Ryzen 7            | 2        | 6.9%    |
| Intel Core i5          | 1        | 3.45%   |
| Intel Atom             | 1        | 3.45%   |
| AMD Ryzen Threadripper | 1        | 3.45%   |
| AMD Ryzen Embedded     | 1        | 3.45%   |
| AMD FX                 | 1        | 3.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 8        | 28.57%  |
| 12      | 5        | 17.86%  |
| 32      | 3        | 10.71%  |
| 6       | 3        | 10.71%  |
| 24      | 2        | 7.14%   |
| 16      | 2        | 7.14%   |
| 8       | 2        | 7.14%   |
| 2       | 2        | 7.14%   |
| 4       | 1        | 3.57%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 24       | 82.76%  |
| Unknown | 5        | 17.24%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 15       | 53.57%  |
| Unknown | 8        | 28.57%  |
| 2       | 5        | 17.86%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 8        | 28.57%  |
| Zen 3      | 6        | 21.43%  |
| Zen+       | 3        | 10.71%  |
| Zen 2      | 2        | 7.14%   |
| Zen        | 2        | 7.14%   |
| KabyLake   | 2        | 7.14%   |
| CometLake  | 2        | 7.14%   |
| Silvermont | 1        | 3.57%   |
| Piledriver | 1        | 3.57%   |
| IvyBridge  | 1        | 3.57%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 9        | 37.5%   |
| AMD    | 9        | 37.5%   |
| Intel  | 5        | 20.83%  |
| VMware | 1        | 4.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| AMD Cezanne                                                           | 3        | 12.5%   |
| Nvidia GK208B [GeForce GT 710]                                        | 2        | 8.33%   |
| Nvidia GT218 [GeForce 210]                                            | 1        | 4.17%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                               | 1        | 4.17%   |
| Nvidia GP107GL [Quadro P620]                                          | 1        | 4.17%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                    | 1        | 4.17%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                   | 1        | 4.17%   |
| Nvidia GM206 [GeForce GTX 960]                                        | 1        | 4.17%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                     | 1        | 4.17%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                | 1        | 4.17%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                              | 1        | 4.17%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                             | 1        | 4.17%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                             | 1        | 4.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display          | 1        | 4.17%   |
| AMD RV630 XT [Radeon HD 2600 XT]                                      | 1        | 4.17%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]      | 1        | 4.17%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM] | 1        | 4.17%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]               | 1        | 4.17%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                    | 1        | 4.17%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]   | 1        | 4.17%   |
| Unknown                                                               | 1        | 4.17%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 8        | 28.57%  |
| Other          | 7        | 25%     |
| 1 x AMD        | 7        | 25%     |
| 1 x Intel      | 3        | 10.71%  |
| 1 x VMware     | 1        | 3.57%   |
| Intel + Nvidia | 1        | 3.57%   |
| Intel + AMD    | 1        | 3.57%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 14       | 50%     |
| Proprietary | 7        | 25%     |
| Unknown     | 7        | 25%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 17       | 60.71%  |
| 3.01-4.0   | 3        | 10.71%  |
| 1.01-2.0   | 3        | 10.71%  |
| 0.51-1.0   | 2        | 7.14%   |
| 7.01-8.0   | 1        | 3.57%   |
| 2.01-3.0   | 1        | 3.57%   |
| 0.01-0.5   | 1        | 3.57%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Goldstar            | 4        | 23.53%  |
| RTK                 | 2        | 11.76%  |
| LG Electronics      | 2        | 11.76%  |
| Sony                | 1        | 5.88%   |
| Samsung Electronics | 1        | 5.88%   |
| Philips             | 1        | 5.88%   |
| Lenovo              | 1        | 5.88%   |
| Hewlett-Packard     | 1        | 5.88%   |
| Eizo                | 1        | 5.88%   |
| Dell                | 1        | 5.88%   |
| BenQ                | 1        | 5.88%   |
| AOC                 | 1        | 5.88%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| RTK WCS Display RTK1A1B 1920x1080 344x195mm 15.6-inch      | 2        | 11.11%  |
| Sony TV SNY4B03 1920x1080 930x520mm 41.9-inch              | 1        | 5.56%   |
| Samsung Electronics SyncMaster SAM05FC 1920x1080           | 1        | 5.56%   |
| Philips PHL 273V7 PHLC156 1920x1080 600x340mm 27.2-inch    | 1        | 5.56%   |
| LG Electronics LCD Monitor LX20D 1600x1200                 | 1        | 5.56%   |
| LG Electronics LCD Monitor LG Ultra HD 11520x2160          | 1        | 5.56%   |
| LG Electronics LCD Monitor LG Ultra HD                     | 1        | 5.56%   |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch      | 1        | 5.56%   |
| Hewlett-Packard E233 HPN345F 1920x1080 510x290mm 23.1-inch | 1        | 5.56%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch | 1        | 5.56%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch | 1        | 5.56%   |
| Goldstar 27GK750F GSM770F 1920x1080 600x340mm 27.2-inch    | 1        | 5.56%   |
| Goldstar 23EA53 GSM59A8 1920x1080 510x290mm 23.1-inch      | 1        | 5.56%   |
| Eizo FX2431 ENC2036 1920x1200 520x330mm 24.2-inch          | 1        | 5.56%   |
| Dell U2518D DEL413C 2560x1440 550x310mm 24.9-inch          | 1        | 5.56%   |
| BenQ GW2280 BNQ78E8 1920x1080 480x270mm 21.7-inch          | 1        | 5.56%   |
| AOC Q3277 AOC3277 2560x1440 710x400mm 32.1-inch            | 1        | 5.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 10       | 55.56%  |
| 3840x2160 (4K)    | 3        | 16.67%  |
| 2560x1440 (QHD)   | 1        | 5.56%   |
| 1920x1200 (WUXGA) | 1        | 5.56%   |
| 1600x1200         | 1        | 5.56%   |
| 11520x2160        | 1        | 5.56%   |
| Unknown           | 1        | 5.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 4        | 23.53%  |
| 24      | 3        | 17.65%  |
| Unknown | 3        | 17.65%  |
| 23      | 2        | 11.76%  |
| 15      | 2        | 11.76%  |
| 41      | 1        | 5.88%   |
| 32      | 1        | 5.88%   |
| 21      | 1        | 5.88%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 9        | 52.94%  |
| Unknown     | 3        | 17.65%  |
| 301-350     | 2        | 11.76%  |
| 701-800     | 1        | 5.88%   |
| 401-500     | 1        | 5.88%   |
| 901-1000    | 1        | 5.88%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 13       | 81.25%  |
| Unknown | 2        | 12.5%   |
| 16/10   | 1        | 6.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 301-350        | 4        | 23.53%  |
| 201-250        | 4        | 23.53%  |
| Unknown        | 3        | 17.65%  |
| 251-300        | 2        | 11.76%  |
| 101-110        | 2        | 11.76%  |
| 351-500        | 1        | 5.88%   |
| 501-1000       | 1        | 5.88%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 8        | 50%     |
| Unknown | 3        | 18.75%  |
| 161-240 | 2        | 12.5%   |
| 121-160 | 2        | 12.5%   |
| 101-120 | 1        | 6.25%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 14       | 50%     |
| 0     | 12       | 42.86%  |
| 2     | 2        | 7.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 15       | 46.88%  |
| Realtek Semiconductor | 13       | 40.63%  |
| TP-Link               | 1        | 3.13%   |
| Ralink Technology     | 1        | 3.13%   |
| ASUSTek Computer      | 1        | 3.13%   |
| Arduino SA            | 1        | 3.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10       | 25.64%  |
| Intel I211 Gigabit Network Connection                             | 4        | 10.26%  |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 7.69%   |
| Intel Wi-Fi 6 AX200                                               | 3        | 7.69%   |
| Intel I210 Gigabit Network Connection                             | 3        | 7.69%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 7.69%   |
| Intel Ethernet Controller I225-V                                  | 2        | 5.13%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1        | 2.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1        | 2.56%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1        | 2.56%   |
| Intel Wireless-AC 9260                                            | 1        | 2.56%   |
| Intel Wireless 8265 / 8275                                        | 1        | 2.56%   |
| Intel Wireless 7265                                               | 1        | 2.56%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 2.56%   |
| Intel Ethernet Connection (11) I219-LM                            | 1        | 2.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1        | 2.56%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                               | 1        | 2.56%   |
| Arduino SA Uno R3 (CDC ACM)                                       | 1        | 2.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 7        | 63.64%  |
| TP-Link               | 1        | 9.09%   |
| Realtek Semiconductor | 1        | 9.09%   |
| Ralink Technology     | 1        | 9.09%   |
| ASUSTek Computer      | 1        | 9.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                 | 3        | 27.27%  |
| TP-Link Archer T3U [Realtek RTL8812BU]              | 1        | 9.09%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter | 1        | 9.09%   |
| Ralink RT2870/RT3070 Wireless Adapter               | 1        | 9.09%   |
| Intel Wireless-AC 9260                              | 1        | 9.09%   |
| Intel Wireless 8265 / 8275                          | 1        | 9.09%   |
| Intel Wireless 7265                                 | 1        | 9.09%   |
| Intel Cannon Lake PCH CNVi WiFi                     | 1        | 9.09%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                 | 1        | 9.09%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 13       | 52%     |
| Realtek Semiconductor | 12       | 48%     |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10       | 37.04%  |
| Intel I211 Gigabit Network Connection                             | 4        | 14.81%  |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 11.11%  |
| Intel I210 Gigabit Network Connection                             | 3        | 11.11%  |
| Intel 82574L Gigabit Network Connection                           | 3        | 11.11%  |
| Intel Ethernet Controller I225-V                                  | 2        | 7.41%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 3.7%    |
| Intel Ethernet Connection (11) I219-LM                            | 1        | 3.7%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 21       | 65.63%  |
| WiFi     | 10       | 31.25%  |
| Modem    | 1        | 3.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 20       | 80%     |
| WiFi     | 5        | 20%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 10       | 35.71%  |
| 2     | 7        | 25%     |
| 0     | 7        | 25%     |
| 3     | 2        | 7.14%   |
| 7     | 1        | 3.57%   |
| 4     | 1        | 3.57%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 25       | 89.29%  |
| Yes  | 3        | 10.71%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 5        | 100%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface             | 2        | 40%     |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 1        | 20%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 1        | 20%     |
| Intel AX200 Bluetooth                          | 1        | 20%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| AMD                     | 15       | 42.86%  |
| Nvidia                  | 9        | 25.71%  |
| Intel                   | 5        | 14.29%  |
| Yamaha                  | 1        | 2.86%   |
| VMware                  | 1        | 2.86%   |
| GN Netcom               | 1        | 2.86%   |
| C-Media Electronics     | 1        | 2.86%   |
| AudioQuest              | 1        | 2.86%   |
| AKAI  Professional M.I. | 1        | 2.86%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 5        | 11.63%  |
| AMD Family 17h/19h HD Audio Controller                                     | 4        | 9.3%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4        | 9.3%    |
| Nvidia GP107GL High Definition Audio Controller                            | 3        | 6.98%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3        | 6.98%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 4.65%   |
| Intel Cannon Lake PCH cAVS                                                 | 2        | 4.65%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 4.65%   |
| Yamaha Steinberg UR12                                                      | 1        | 2.33%   |
| VMware HD Audio Controller                                                 | 1        | 2.33%   |
| Nvidia High Definition Audio Controller                                    | 1        | 2.33%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 2.33%   |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 2.33%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 2.33%   |
| Intel Comet Lake PCH cAVS                                                  | 1        | 2.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1        | 2.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1        | 2.33%   |
| GN Netcom Jabra SPEAK 410 USB                                              | 1        | 2.33%   |
| C-Media Electronics BIRD UM1                                               | 1        | 2.33%   |
| AudioQuest DragonFly                                                       | 1        | 2.33%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1        | 2.33%   |
| AMD RV630 HDMI Audio [Radeon HD 2600 PRO/XT / HD 3610]                     | 1        | 2.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1        | 2.33%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1        | 2.33%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1        | 2.33%   |
| AKAI  Professional M.I. LPK25 MIDI Keyboard                                | 1        | 2.33%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 4        | 19.05%  |
| Corsair             | 4        | 19.05%  |
| Micron Technology   | 3        | 14.29%  |
| Unknown             | 2        | 9.52%   |
| SK Hynix            | 2        | 9.52%   |
| Crucial             | 2        | 9.52%   |
| Team                | 1        | 4.76%   |
| SMART               | 1        | 4.76%   |
| Samsung Electronics | 1        | 4.76%   |
| Unknown             | 1        | 4.76%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Corsair RAM CMK32GX4M2D3200C16 16GB DIMM DDR4 3200MT/s  | 2        | 9.09%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s               | 1        | 4.55%   |
| Unknown RAM 2G-08-10-12-1333 2GB DIMM DDR3 1333MT/s     | 1        | 4.55%   |
| Team RAM TEAMGROUP-UD4-4133 8GB DIMM DDR4 4133MT/s      | 1        | 4.55%   |
| SMART RAM Module 8GB DIMM DDR4 2667MT/s                 | 1        | 4.55%   |
| SK Hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s | 1        | 4.55%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s  | 1        | 4.55%   |
| Samsung RAM M378A4G43MB1-CTD 32GB DIMM DDR4 2666MT/s    | 1        | 4.55%   |
| Micron RAM 18ASF4G72AZ-3G2B1 32GB DIMM DDR4 3200MT/s    | 1        | 4.55%   |
| Micron RAM 16ATF2G64HZ-2G6J1 16GB SODIMM DDR4 2667MT/s  | 1        | 4.55%   |
| Micron RAM 16ATF2G64AZ-3G2J1 16GB DIMM DDR4 3200MT/s    | 1        | 4.55%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 2666MT/s     | 1        | 4.55%   |
| Kingston RAM KHX1600C10D3/ 8GB DIMM DDR3 1600MT/s       | 1        | 4.55%   |
| Kingston RAM 9965745-020.A00G 32GB DIMM DDR4 3200MT/s   | 1        | 4.55%   |
| Kingston RAM 9965745-017.A00G 16GB DIMM DDR4 3200MT/s   | 1        | 4.55%   |
| Kingston RAM 9905713-030.A00G 8GB DIMM DDR4 2666MT/s    | 1        | 4.55%   |
| Crucial RAM CT16G4DFD832A.C16FP 16GB DIMM DDR4 3200MT/s | 1        | 4.55%   |
| Crucial RAM BL16G36C16U4B.M8FB1 16GB DIMM DDR4 3600MT/s | 1        | 4.55%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s   | 1        | 4.55%   |
| Corsair RAM CMD128GX4M8A2400C14 16GB DIMM DDR4 2133MT/s | 1        | 4.55%   |
| Unknown                                                 | 1        | 4.55%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 17       | 85%     |
| DDR3 | 3        | 15%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 17       | 85%     |
| SODIMM | 3        | 15%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 9        | 42.86%  |
| 8192  | 7        | 33.33%  |
| 32768 | 3        | 14.29%  |
| 4096  | 1        | 4.76%   |
| 2048  | 1        | 4.76%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 8        | 38.1%   |
| 2667  | 3        | 14.29%  |
| 2666  | 3        | 14.29%  |
| 1600  | 2        | 9.52%   |
| 4133  | 1        | 4.76%   |
| 3600  | 1        | 4.76%   |
| 2933  | 1        | 4.76%   |
| 2133  | 1        | 4.76%   |
| 1333  | 1        | 4.76%   |

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
| Logitech        | 3        | 60%     |
| Microdia        | 1        | 20%     |
| Aveo Technology | 1        | 20%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Microdia HP Integrated Webcam | 1        | 20%     |
| Logitech Webcam C270          | 1        | 20%     |
| Logitech Webcam C170          | 1        | 20%     |
| Logitech C920 PRO HD Webcam   | 1        | 20%     |
| Aveo USB2.0 Camera            | 1        | 20%     |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

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
| 0     | 18       | 64.29%  |
| 1     | 4        | 14.29%  |
| 2     | 3        | 10.71%  |
| 4     | 2        | 7.14%   |
| 3     | 1        | 3.57%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 5        | 31.25%  |
| Sound                    | 4        | 25%     |
| Net/wireless             | 3        | 18.75%  |
| Bluetooth                | 2        | 12.5%   |
| Network                  | 1        | 6.25%   |
| Net/ethernet             | 1        | 6.25%   |

