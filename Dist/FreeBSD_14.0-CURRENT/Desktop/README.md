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

| Vendor        | Model                 | Probe                                                     | Date         |
|---------------|-----------------------|-----------------------------------------------------------|--------------|
| friendlyel... | nanopi-m4             | [bb29e50061](https://bsd-hardware.info/?probe=bb29e50061) | Dec 27, 2021 |
| khadas        | edge-v                | [42c428aac0](https://bsd-hardware.info/?probe=42c428aac0) | Dec 26, 2021 |
| Unknown       | Unknown               | [b726a1b3e3](https://bsd-hardware.info/?probe=b726a1b3e3) | Dec 11, 2021 |
| ASUSTek       | PRIME X570-PRO        | [9a8d19aa04](https://bsd-hardware.info/?probe=9a8d19aa04) | Dec 11, 2021 |
| Unknown       | Unknown               | [7633cb9296](https://bsd-hardware.info/?probe=7633cb9296) | Dec 11, 2021 |
| Unknown       | Unknown               | [d05fb15725](https://bsd-hardware.info/?probe=d05fb15725) | Nov 22, 2021 |
| Beckhoff A... | CX51x0 G3             | [6db720018b](https://bsd-hardware.info/?probe=6db720018b) | Oct 25, 2021 |
| Beckhoff A... | CX20x3 G1             | [a49fbd5ce3](https://bsd-hardware.info/?probe=a49fbd5ce3) | Oct 25, 2021 |
| ASUSTek       | PRIME Z590-A          | [1aa5ced5a0](https://bsd-hardware.info/?probe=1aa5ced5a0) | Sep 23, 2021 |
| Gigabyte      | X399 DESIGNARE EX-CF  | [a78cc6a11b](https://bsd-hardware.info/?probe=a78cc6a11b) | Sep 04, 2021 |
| Unknown       | Unknown               | [4a3836de00](https://bsd-hardware.info/?probe=4a3836de00) | Jul 08, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR | [edebe87739](https://bsd-hardware.info/?probe=edebe87739) | Jun 04, 2021 |
| Gigabyte      | B550I AORUS PRO AX    | [62b9ea2794](https://bsd-hardware.info/?probe=62b9ea2794) | May 14, 2021 |
| ASUSTek       | P8H77-M PRO           | [b3acafeb1a](https://bsd-hardware.info/?probe=b3acafeb1a) | May 09, 2021 |
| ASUSTek       | P8H77-M PRO           | [86cec3b874](https://bsd-hardware.info/?probe=86cec3b874) | May 09, 2021 |
| pine64        | pinebook-pro-rk3399   | [79713a2668](https://bsd-hardware.info/?probe=79713a2668) | Apr 25, 2021 |
| pine64        | pinebook-pro-rk3399   | [0f04e5f048](https://bsd-hardware.info/?probe=0f04e5f048) | Apr 11, 2021 |
| Gigabyte      | X570 AORUS ELITE      | [325186171a](https://bsd-hardware.info/?probe=325186171a) | Apr 02, 2021 |
| pine64        | pinebook-pro-rk3399   | [ea524ab4c4](https://bsd-hardware.info/?probe=ea524ab4c4) | Mar 28, 2021 |
| pine64        | pinebook-pro-rk3399   | [835da13d39](https://bsd-hardware.info/?probe=835da13d39) | Mar 18, 2021 |
| Gigabyte      | 970A-UD3P             | [cc3151bc6f](https://bsd-hardware.info/?probe=cc3151bc6f) | Mar 17, 2021 |
| MSI           | B450 GAMING PLUS      | [547fd655f0](https://bsd-hardware.info/?probe=547fd655f0) | Mar 13, 2021 |
| pine64        | pinebook-pro-rk3399   | [c00bcdcc87](https://bsd-hardware.info/?probe=c00bcdcc87) | Mar 06, 2021 |
| pine64        | pinebook-pro-rk3399   | [3abcd73d48](https://bsd-hardware.info/?probe=3abcd73d48) | Feb 26, 2021 |
| Gigabyte      | X570 AORUS MASTER     | [29936dd1c0](https://bsd-hardware.info/?probe=29936dd1c0) | Feb 25, 2021 |
| Unknown       | Unknown               | [74b11992d7](https://bsd-hardware.info/?probe=74b11992d7) | Feb 20, 2021 |
| Raspberry ... | rpi                   | [92ee9b3619](https://bsd-hardware.info/?probe=92ee9b3619) | Feb 18, 2021 |
| pine64        | pinebook-pro-rk3399   | [b750f83194](https://bsd-hardware.info/?probe=b750f83194) | Feb 17, 2021 |
| ASUSTek       | PRIME B450M-A         | [ba7f82b343](https://bsd-hardware.info/?probe=ba7f82b343) | Feb 12, 2021 |
| pine64        | pinebook-pro-rk3399   | [2befc5e754](https://bsd-hardware.info/?probe=2befc5e754) | Feb 10, 2021 |
| pine64        | pinebook-pro-rk3399   | [5a55b22f44](https://bsd-hardware.info/?probe=5a55b22f44) | Feb 09, 2021 |
| Dell          | 0D9JG3 A00            | [65dd4083c5](https://bsd-hardware.info/?probe=65dd4083c5) | Feb 09, 2021 |
| pine64        | pinebook-pro-rk3399   | [97e72f0066](https://bsd-hardware.info/?probe=97e72f0066) | Feb 06, 2021 |
| pine64        | pinebook-pro-rk3399   | [1720175648](https://bsd-hardware.info/?probe=1720175648) | Jan 27, 2021 |
| pine64        | pinebook-pro-rk3399   | [2338de9efc](https://bsd-hardware.info/?probe=2338de9efc) | Jan 24, 2021 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 15       | 65.22%  |
| arm64 | 6        | 26.09%  |
| riscv | 1        | 4.35%   |
| arm   | 1        | 4.35%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| KDE5    | 8        | 33.33%  |
| Console | 8        | 33.33%  |
| XFCE    | 2        | 8.33%   |
| Openbox | 2        | 8.33%   |
| MATE    | 2        | 8.33%   |
| TWM     | 1        | 4.17%   |
| i3      | 1        | 4.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 16       | 66.67%  |
| Console | 8        | 33.33%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 12       | 50%     |
| SDDM    | 5        | 20.83%  |
| SLiM    | 4        | 16.67%  |
| GDM     | 3        | 12.5%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| C       | 9        | 39.13%  |
| en_US   | 4        | 17.39%  |
| uk_UA   | 3        | 13.04%  |
| de_DE   | 3        | 13.04%  |
| Unknown | 2        | 8.7%    |
| sv_SE   | 1        | 4.35%   |
| de_CH   | 1        | 4.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 20       | 86.96%  |
| BIOS | 3        | 13.04%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Zfs  | 18       | 78.26%  |
| Ufs  | 5        | 21.74%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 20       | 86.96%  |
| MBR  | 3        | 13.04%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Gigabyte Technology     | 5        | 21.74%  |
| ASUSTek Computer        | 5        | 21.74%  |
| Unknown                 | 5        | 21.74%  |
| Beckhoff Automation     | 2        | 8.7%    |
| Raspberry Pi Foundation | 1        | 4.35%   |
| pine64                  | 1        | 4.35%   |
| MSI                     | 1        | 4.35%   |
| khadas                  | 1        | 4.35%   |
| friendlyelec            | 1        | 4.35%   |
| Dell                    | 1        | 4.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| Unknown                         | 5        | 21.74%  |
| RPi rpi                         | 1        | 4.35%   |
| pine64 pinebook-pro-rk3399      | 1        | 4.35%   |
| MSI MS-7B86                     | 1        | 4.35%   |
| khadas edge-v                   | 1        | 4.35%   |
| Gigabyte X570 AORUS MASTER      | 1        | 4.35%   |
| Gigabyte X570 AORUS ELITE       | 1        | 4.35%   |
| Gigabyte X399 DESIGNARE EX      | 1        | 4.35%   |
| Gigabyte B550I AORUS PRO AX     | 1        | 4.35%   |
| Gigabyte 970A-UD3P              | 1        | 4.35%   |
| friendlyelec nanopi-m4          | 1        | 4.35%   |
| Dell OptiPlex 5080              | 1        | 4.35%   |
| Beckhoff Automation CX2033-0185 | 1        | 4.35%   |
| Beckhoff Automation CBxx63      | 1        | 4.35%   |
| ASUS PRIME Z590-A               | 1        | 4.35%   |
| ASUS PRIME X570-PRO             | 1        | 4.35%   |
| ASUS PRIME B450M-GAMING/BR      | 1        | 4.35%   |
| ASUS PRIME B450M-A              | 1        | 4.35%   |
| ASUS P8H77-M PRO                | 1        | 4.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| Unknown                         | 5        | 21.74%  |
| ASUS PRIME                      | 4        | 17.39%  |
| Gigabyte X570                   | 2        | 8.7%    |
| RPi rpi                         | 1        | 4.35%   |
| pine64 pinebook-pro-rk3399      | 1        | 4.35%   |
| MSI MS-7B86                     | 1        | 4.35%   |
| khadas edge-v                   | 1        | 4.35%   |
| Gigabyte X399                   | 1        | 4.35%   |
| Gigabyte B550I                  | 1        | 4.35%   |
| Gigabyte 970A-UD3P              | 1        | 4.35%   |
| friendlyelec nanopi-m4          | 1        | 4.35%   |
| Dell OptiPlex                   | 1        | 4.35%   |
| Beckhoff Automation CX2033-0185 | 1        | 4.35%   |
| Beckhoff Automation CBxx63      | 1        | 4.35%   |
| ASUS P8H77-M                    | 1        | 4.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2021    | 8        | 34.78%  |
| 2020    | 5        | 21.74%  |
| Unknown | 4        | 17.39%  |
| 2018    | 3        | 13.04%  |
| 2019    | 1        | 4.35%   |
| 2016    | 1        | 4.35%   |
| 2014    | 1        | 4.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 23       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 23       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 6        | 26.09%  |
| 4.01-8.0    | 4        | 17.39%  |
| 32.01-64.0  | 4        | 17.39%  |
| 64.01-256.0 | 4        | 17.39%  |
| 8.01-16.0   | 2        | 8.7%    |
| 0.51-1.0    | 2        | 8.7%    |
| 2.01-3.0    | 1        | 4.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 7        | 30.43%  |
| 0.51-1.0   | 7        | 30.43%  |
| 0.01-0.5   | 6        | 26.09%  |
| 3.01-4.0   | 1        | 4.35%   |
| 16.01-24.0 | 1        | 4.35%   |
| 0          | 1        | 4.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 0      | 8        | 34.78%  |
| 1      | 5        | 21.74%  |
| 3      | 4        | 17.39%  |
| 6      | 2        | 8.7%    |
| 2      | 2        | 8.7%    |
| 5      | 1        | 4.35%   |
| 4      | 1        | 4.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 18       | 78.26%  |
| Yes       | 5        | 21.74%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 16       | 69.57%  |
| No        | 7        | 30.43%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 15       | 65.22%  |
| Yes       | 8        | 34.78%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 19       | 82.61%  |
| Yes       | 4        | 17.39%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Ukraine      | 4        | 17.39%  |
| Germany      | 4        | 17.39%  |
| USA          | 2        | 8.7%    |
| UK           | 2        | 8.7%    |
| Russia       | 2        | 8.7%    |
| Japan        | 2        | 8.7%    |
| Brazil       | 2        | 8.7%    |
| Switzerland  | 1        | 4.35%   |
| Sweden       | 1        | 4.35%   |
| Saudi Arabia | 1        | 4.35%   |
| France       | 1        | 4.35%   |
| Austria      | 1        | 4.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Kyiv                    | 3        | 12%     |
| Ōta-ku                 | 2        | 8%      |
| Rietberg                | 2        | 8%      |
| Moscow                  | 2        | 8%      |
| Zurich                  | 1        | 4%      |
| Zaporizhzhya            | 1        | 4%      |
| Sollentuna              | 1        | 4%      |
| Santa Monica            | 1        | 4%      |
| Riyadh                  | 1        | 4%      |
| Rio de Janeiro          | 1        | 4%      |
| Northeim                | 1        | 4%      |
| Lake Forest             | 1        | 4%      |
| Kunitachi               | 1        | 4%      |
| Jaboatao dos Guararapes | 1        | 4%      |
| Graz                    | 1        | 4%      |
| Fuchu                   | 1        | 4%      |
| Claix                   | 1        | 4%      |
| Cambridge               | 1        | 4%      |
| Berlin                  | 1        | 4%      |
| Beckton                 | 1        | 4%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 11     | 25.93%  |
| Seagate             | 4        | 5      | 14.81%  |
| Samsung Electronics | 3        | 5      | 11.11%  |
| Crucial             | 3        | 8      | 11.11%  |
| Toshiba             | 2        | 2      | 7.41%   |
| Kingston            | 2        | 3      | 7.41%   |
| SK Hynix            | 1        | 1      | 3.7%    |
| Micron Technology   | 1        | 2      | 3.7%    |
| HGST                | 1        | 2      | 3.7%    |
| GOODRAM             | 1        | 1      | 3.7%    |
| Apacer              | 1        | 1      | 3.7%    |
| A-DATA Technology   | 1        | 1      | 3.7%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Toshiba MQ04ABF100 1TB            | 2        | 6.06%   |
| WDC WDS250G2B0C-00PXH0 250GB      | 1        | 3.03%   |
| WDC WDS100T2B0A-00SM50 1TB        | 1        | 3.03%   |
| WDC WD5002ABYS-18B1B0 500GB       | 1        | 3.03%   |
| WDC WD40EZRZ-75GXCB0 4TB          | 1        | 3.03%   |
| WDC WD30EFRX-68EUZN0 3TB          | 1        | 3.03%   |
| WDC WD120EFAX-68UNTN0 12TB        | 1        | 3.03%   |
| WDC WD10SPZX-21Z10T0 1TB          | 1        | 3.03%   |
| WDC WD10JMVW-11AJGS3 1TB          | 1        | 3.03%   |
| WDC WD10EZEX-00RKKA0 1TB          | 1        | 3.03%   |
| WDC WD10EARX-00N0YB0 1TB          | 1        | 3.03%   |
| SK Hynix HFS128G39TND-N210A 128GB | 1        | 3.03%   |
| Seagate ST4000DM000-1F2168 4TB    | 1        | 3.03%   |
| Seagate ST3750640AS 752GB         | 1        | 3.03%   |
| Seagate ST32000641AS 2TB          | 1        | 3.03%   |
| Seagate ST3000DM007-1WY10G 3TB    | 1        | 3.03%   |
| Seagate ST3000DM001-1ER166 3TB    | 1        | 3.03%   |
| Samsung SSD 870 QVO 1TB           | 1        | 3.03%   |
| Samsung SSD 860 EVO 4TB           | 1        | 3.03%   |
| Samsung SSD 860 EVO 250GB         | 1        | 3.03%   |
| Samsung SSD 850 EVO 500GB         | 1        | 3.03%   |
| Samsung SSD 850 EVO 250GB         | 1        | 3.03%   |
| Micron 2300_MTFDHBA512TDV 512GB   | 1        | 3.03%   |
| Kingston SA400S37240G 240GB       | 1        | 3.03%   |
| Kingston SA2000M81000G 1TB        | 1        | 3.03%   |
| HGST HTS721010A9E630 1TB          | 1        | 3.03%   |
| GOODRAM SSDPR-CX400-256-G2 256GB  | 1        | 3.03%   |
| Crucial CT500P1SSD8 500GB         | 1        | 3.03%   |
| Crucial CT250MX500SSD1 250GB      | 1        | 3.03%   |
| Crucial CT1000MX500SSD4 1TB       | 1        | 3.03%   |
| Apacer 16GB SATA Flash Drive      | 1        | 3.03%   |
| A-DATA ICFS332-016GW 16GB         | 1        | 3.03%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 5        | 8      | 41.67%  |
| Seagate | 4        | 5      | 33.33%  |
| Toshiba | 2        | 2      | 16.67%  |
| HGST    | 1        | 2      | 8.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 5      | 27.27%  |
| Crucial             | 2        | 7      | 18.18%  |
| WDC                 | 1        | 2      | 9.09%   |
| SK Hynix            | 1        | 1      | 9.09%   |
| Kingston            | 1        | 2      | 9.09%   |
| GOODRAM             | 1        | 1      | 9.09%   |
| Apacer              | 1        | 1      | 9.09%   |
| A-DATA Technology   | 1        | 1      | 9.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 11       | 20     | 45.83%  |
| HDD  | 9        | 17     | 37.5%   |
| NVMe | 4        | 5      | 16.67%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 13       | 37     | 76.47%  |
| NVMe | 4        | 5      | 23.53%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 9        | 16     | 39.13%  |
| 0.51-1.0   | 8        | 13     | 34.78%  |
| 3.01-4.0   | 2        | 3      | 8.7%    |
| 2.01-3.0   | 2        | 3      | 8.7%    |
| 10.01-20.0 | 1        | 1      | 4.35%   |
| 1.01-2.0   | 1        | 1      | 4.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 251-500    | 5        | 21.74%  |
| 101-250    | 5        | 21.74%  |
| 1-20       | 5        | 21.74%  |
| 501-1000   | 4        | 17.39%  |
| 2001-3000  | 2        | 8.7%    |
| 21-50      | 1        | 4.35%   |
| 51-100     | 1        | 4.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 15       | 62.5%   |
| 21-50     | 6        | 25%     |
| 251-500   | 1        | 4.17%   |
| 1001-2000 | 1        | 4.17%   |
| 501-1000  | 1        | 4.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                       | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC WD5002ABYS-18B1B0 500GB | 1        | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 1        | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 1        | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 1        | 1      | 100%    |

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
| Works   | 15       | 41     | 93.75%  |
| Malfunc | 1        | 1      | 6.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| AMD                         | 10       | 37.04%  |
| Intel                       | 5        | 18.52%  |
| Samsung Electronics         | 3        | 11.11%  |
| Silicon Motion              | 2        | 7.41%   |
| Sandisk                     | 2        | 7.41%   |
| VMware                      | 1        | 3.7%    |
| Micron/Crucial Technology   | 1        | 3.7%    |
| Micron Technology           | 1        | 3.7%    |
| Marvell Technology Group    | 1        | 3.7%    |
| Kingston Technology Company | 1        | 3.7%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                         | 8        | 24.24%  |
| AMD 400 Series Chipset SATA Controller                                      | 3        | 9.09%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                             | 2        | 6.06%   |
| Sandisk WD Blue SN550 NVMe SSD                                              | 2        | 6.06%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                               | 2        | 6.06%   |
| Unknown                                                                     | 2        | 6.06%   |
| VMware SATA AHCI controller                                                 | 1        | 3.03%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                               | 1        | 3.03%   |
| Micron/Crucial P1 NVMe PCIe SSD                                             | 1        | 3.03%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                       | 1        | 3.03%   |
| Kingston Company A2000 NVMe SSD                                             | 1        | 3.03%   |
| Intel Comet Lake SATA AHCI Controller                                       | 1        | 3.03%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                      | 1        | 3.03%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                              | 1        | 3.03%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode] | 1        | 3.03%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode] | 1        | 3.03%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                        | 1        | 3.03%   |
| AMD X399 Series Chipset SATA Controller                                     | 1        | 3.03%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                    | 1        | 3.03%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                           | 1        | 3.03%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 14       | 51.85%  |
| NVMe | 11       | 40.74%  |
| RAID | 1        | 3.7%    |
| IDE  | 1        | 3.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| AMD     | 10       | 41.67%  |
| Unknown | 7        | 29.17%  |
| Intel   | 5        | 20.83%  |
| ARM     | 2        | 8.33%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
|                                                | 7        | 29.17%  |
| Intel Core i7-8750H CPU @ 2.20GHz              | 1        | 4.17%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 1        | 4.17%   |
| Intel Core i7-10700 CPU @ 2.90GHz              | 1        | 4.17%   |
| Intel Core i5-10500T CPU @ 2.30GHz             | 1        | 4.17%   |
| Intel Atom CPU E3827 @ 1.74GHz                 | 1        | 4.17%   |
| ARM Cortex-A72 r0p2                            | 1        | 4.17%   |
| ARM Cortex-A53 r0p4                            | 1        | 4.17%   |
| AMD Ryzen Threadripper 1950X 16-Core Processor | 1        | 4.17%   |
| AMD Ryzen Embedded V1202B with Radeon Vega Gfx | 1        | 4.17%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 1        | 4.17%   |
| AMD Ryzen 9 3950X 16-Core Processor            | 1        | 4.17%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 1        | 4.17%   |
| AMD Ryzen 7 5800X 8-Core Processor             | 1        | 4.17%   |
| AMD Ryzen 7 2700X Eight-Core Processor         | 1        | 4.17%   |
| AMD Ryzen 5 2600X Six-Core Processor           | 1        | 4.17%   |
| AMD Ryzen 5 2600 Six-Core Processor            | 1        | 4.17%   |
| AMD FX-8320E Eight-Core Processor              | 1        | 4.17%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Other                  | 7        | 29.17%  |
| Intel Core i7          | 3        | 12.5%   |
| AMD Ryzen 9            | 3        | 12.5%   |
| ARM Cortex             | 2        | 8.33%   |
| AMD Ryzen 7            | 2        | 8.33%   |
| AMD Ryzen 5            | 2        | 8.33%   |
| Intel Core i5          | 1        | 4.17%   |
| Intel Atom             | 1        | 4.17%   |
| AMD Ryzen Threadripper | 1        | 4.17%   |
| AMD Ryzen Embedded     | 1        | 4.17%   |
| AMD FX                 | 1        | 4.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 8        | 34.78%  |
| 32      | 2        | 8.7%    |
| 24      | 2        | 8.7%    |
| 16      | 2        | 8.7%    |
| 12      | 2        | 8.7%    |
| 8       | 2        | 8.7%    |
| 6       | 2        | 8.7%    |
| 2       | 2        | 8.7%    |
| 4       | 1        | 4.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 19       | 79.17%  |
| Unknown | 5        | 20.83%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 11       | 47.83%  |
| Unknown | 8        | 34.78%  |
| 2       | 4        | 17.39%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 8        | 34.78%  |
| Zen+       | 3        | 13.04%  |
| Zen 3      | 2        | 8.7%    |
| Zen 2      | 2        | 8.7%    |
| Zen        | 2        | 8.7%    |
| CometLake  | 2        | 8.7%    |
| Silvermont | 1        | 4.35%   |
| Piledriver | 1        | 4.35%   |
| KabyLake   | 1        | 4.35%   |
| IvyBridge  | 1        | 4.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 8        | 47.06%  |
| Intel  | 4        | 23.53%  |
| AMD    | 4        | 23.53%  |
| VMware | 1        | 5.88%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Nvidia GK208B [GeForce GT 710]                                      | 2        | 11.76%  |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                             | 1        | 5.88%   |
| Nvidia GP107GL [Quadro P620]                                        | 1        | 5.88%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                  | 1        | 5.88%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                 | 1        | 5.88%   |
| Nvidia GM206 [GeForce GTX 960]                                      | 1        | 5.88%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                   | 1        | 5.88%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                              | 1        | 5.88%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                            | 1        | 5.88%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                           | 1        | 5.88%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display        | 1        | 5.88%   |
| AMD RV630 XT [Radeon HD 2600 XT]                                    | 1        | 5.88%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]    | 1        | 5.88%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]             | 1        | 5.88%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X] | 1        | 5.88%   |
| Unknown                                                             | 1        | 5.88%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| Other          | 7        | 30.43%  |
| 1 x Nvidia     | 7        | 30.43%  |
| 1 x AMD        | 4        | 17.39%  |
| 1 x Intel      | 3        | 13.04%  |
| 1 x VMware     | 1        | 4.35%   |
| Intel + Nvidia | 1        | 4.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 9        | 39.13%  |
| Proprietary | 7        | 30.43%  |
| Unknown     | 7        | 30.43%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 14       | 60.87%  |
| 3.01-4.0   | 3        | 13.04%  |
| 1.01-2.0   | 2        | 8.7%    |
| 0.51-1.0   | 2        | 8.7%    |
| 7.01-8.0   | 1        | 4.35%   |
| 2.01-3.0   | 1        | 4.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Goldstar            | 3        | 21.43%  |
| RTK                 | 2        | 14.29%  |
| LG Electronics      | 2        | 14.29%  |
| Sony                | 1        | 7.14%   |
| Samsung Electronics | 1        | 7.14%   |
| Philips             | 1        | 7.14%   |
| Eizo                | 1        | 7.14%   |
| Dell                | 1        | 7.14%   |
| BenQ                | 1        | 7.14%   |
| AOC                 | 1        | 7.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| RTK WCS Display RTK1A1B 1920x1080 344x195mm 15.6-inch      | 2        | 13.33%  |
| Sony TV SNY4B03 1920x1080 930x520mm 41.9-inch              | 1        | 6.67%   |
| Samsung Electronics SyncMaster SAM05FC 1920x1080           | 1        | 6.67%   |
| Philips PHL 273V7 PHLC156 1920x1080 600x340mm 27.2-inch    | 1        | 6.67%   |
| LG Electronics LCD Monitor LX20D 1600x1200                 | 1        | 6.67%   |
| LG Electronics LCD Monitor LG Ultra HD 11520x2160          | 1        | 6.67%   |
| LG Electronics LCD Monitor LG Ultra HD                     | 1        | 6.67%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch | 1        | 6.67%   |
| Goldstar 27GK750F GSM770F 1920x1080 600x340mm 27.2-inch    | 1        | 6.67%   |
| Goldstar 23EA53 GSM59A8 1920x1080 510x290mm 23.1-inch      | 1        | 6.67%   |
| Eizo FX2431 ENC2036 1920x1200 520x330mm 24.2-inch          | 1        | 6.67%   |
| Dell U2518D DEL413C 2560x1440 550x310mm 24.9-inch          | 1        | 6.67%   |
| BenQ GW2280 BNQ78E8 1920x1080 480x270mm 21.7-inch          | 1        | 6.67%   |
| AOC Q3277 AOC3277 2560x1440 710x400mm 32.1-inch            | 1        | 6.67%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 8        | 53.33%  |
| 3840x2160 (4K)    | 2        | 13.33%  |
| 2560x1440 (QHD)   | 1        | 6.67%   |
| 1920x1200 (WUXGA) | 1        | 6.67%   |
| 1600x1200         | 1        | 6.67%   |
| 11520x2160        | 1        | 6.67%   |
| Unknown           | 1        | 6.67%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 3        | 21.43%  |
| Unknown | 3        | 21.43%  |
| 24      | 2        | 14.29%  |
| 15      | 2        | 14.29%  |
| 41      | 1        | 7.14%   |
| 32      | 1        | 7.14%   |
| 23      | 1        | 7.14%   |
| 21      | 1        | 7.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 6        | 42.86%  |
| Unknown     | 3        | 21.43%  |
| 301-350     | 2        | 14.29%  |
| 701-800     | 1        | 7.14%   |
| 401-500     | 1        | 7.14%   |
| 901-1000    | 1        | 7.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 10       | 76.92%  |
| Unknown | 2        | 15.38%  |
| 16/10   | 1        | 7.69%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 301-350        | 3        | 21.43%  |
| Unknown        | 3        | 21.43%  |
| 251-300        | 2        | 14.29%  |
| 201-250        | 2        | 14.29%  |
| 101-110        | 2        | 14.29%  |
| 351-500        | 1        | 7.14%   |
| 501-1000       | 1        | 7.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 6        | 46.15%  |
| Unknown | 3        | 23.08%  |
| 121-160 | 2        | 15.38%  |
| 161-240 | 1        | 7.69%   |
| 101-120 | 1        | 7.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 11       | 47.83%  |
| 0     | 10       | 43.48%  |
| 2     | 2        | 8.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 12       | 46.15%  |
| Realtek Semiconductor | 10       | 38.46%  |
| TP-Link               | 1        | 3.85%   |
| Ralink Technology     | 1        | 3.85%   |
| ASUSTek Computer      | 1        | 3.85%   |
| Arduino SA            | 1        | 3.85%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7        | 23.33%  |
| Intel I211 Gigabit Network Connection                             | 4        | 13.33%  |
| Intel 82574L Gigabit Network Connection                           | 3        | 10%     |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 6.67%   |
| Intel Wi-Fi 6 AX200                                               | 2        | 6.67%   |
| Intel I210 Gigabit Network Connection                             | 2        | 6.67%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1        | 3.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1        | 3.33%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1        | 3.33%   |
| Intel Wireless-AC 9260                                            | 1        | 3.33%   |
| Intel Wireless 8265 / 8275                                        | 1        | 3.33%   |
| Intel Ethernet Controller I225-V                                  | 1        | 3.33%   |
| Intel Ethernet Connection (11) I219-LM                            | 1        | 3.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1        | 3.33%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                               | 1        | 3.33%   |
| Arduino SA Uno R3 (CDC ACM)                                       | 1        | 3.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 5        | 55.56%  |
| TP-Link               | 1        | 11.11%  |
| Realtek Semiconductor | 1        | 11.11%  |
| Ralink Technology     | 1        | 11.11%  |
| ASUSTek Computer      | 1        | 11.11%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                 | 2        | 22.22%  |
| TP-Link Archer T3U [Realtek RTL8812BU]              | 1        | 11.11%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter | 1        | 11.11%  |
| Ralink RT2870/RT3070 Wireless Adapter               | 1        | 11.11%  |
| Intel Wireless-AC 9260                              | 1        | 11.11%  |
| Intel Wireless 8265 / 8275                          | 1        | 11.11%  |
| Intel Cannon Lake PCH CNVi WiFi                     | 1        | 11.11%  |
| ASUS Realtek 8188EUS [USB-N10 Nano]                 | 1        | 11.11%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 10       | 52.63%  |
| Realtek Semiconductor | 9        | 47.37%  |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7        | 35%     |
| Intel I211 Gigabit Network Connection                             | 4        | 20%     |
| Intel 82574L Gigabit Network Connection                           | 3        | 15%     |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 10%     |
| Intel I210 Gigabit Network Connection                             | 2        | 10%     |
| Intel Ethernet Controller I225-V                                  | 1        | 5%      |
| Intel Ethernet Connection (11) I219-LM                            | 1        | 5%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 16       | 64%     |
| WiFi     | 8        | 32%     |
| Modem    | 1        | 4%      |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 15       | 83.33%  |
| WiFi     | 3        | 16.67%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 8        | 34.78%  |
| 0     | 7        | 30.43%  |
| 2     | 5        | 21.74%  |
| 7     | 1        | 4.35%   |
| 4     | 1        | 4.35%   |
| 3     | 1        | 4.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 21       | 91.3%   |
| Yes  | 2        | 8.7%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 4        | 100%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Wireless-AC 9260 Bluetooth Adapter       | 1        | 25%     |
| Intel Bluetooth wireless interface             | 1        | 25%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 1        | 25%     |
| Intel AX200 Bluetooth                          | 1        | 25%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| AMD                     | 10       | 35.71%  |
| Nvidia                  | 8        | 28.57%  |
| Intel                   | 4        | 14.29%  |
| Yamaha                  | 1        | 3.57%   |
| VMware                  | 1        | 3.57%   |
| GN Netcom               | 1        | 3.57%   |
| C-Media Electronics     | 1        | 3.57%   |
| AudioQuest              | 1        | 3.57%   |
| AKAI  Professional M.I. | 1        | 3.57%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 4        | 12.5%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4        | 12.5%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3        | 9.38%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 6.25%   |
| Yamaha Steinberg UR12                                                      | 1        | 3.13%   |
| VMware HD Audio Controller                                                 | 1        | 3.13%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 3.13%   |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 3.13%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 3.13%   |
| Intel Comet Lake PCH cAVS                                                  | 1        | 3.13%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 3.13%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1        | 3.13%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1        | 3.13%   |
| GN Netcom Jabra SPEAK 410 USB                                              | 1        | 3.13%   |
| C-Media Electronics BIRD UM1                                               | 1        | 3.13%   |
| AudioQuest DragonFly                                                       | 1        | 3.13%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1        | 3.13%   |
| AMD RV630 HDMI Audio [Radeon HD 2600 PRO/XT / HD 3610]                     | 1        | 3.13%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1        | 3.13%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 1        | 3.13%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1        | 3.13%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1        | 3.13%   |
| AKAI  Professional M.I. LPK25 MIDI Keyboard                                | 1        | 3.13%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Micron Technology   | 3        | 18.75%  |
| Kingston            | 3        | 18.75%  |
| Unknown             | 2        | 12.5%   |
| SK Hynix            | 2        | 12.5%   |
| Crucial             | 2        | 12.5%   |
| Corsair             | 2        | 12.5%   |
| Samsung Electronics | 1        | 6.25%   |
| Unknown             | 1        | 6.25%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s               | 1        | 6.25%   |
| Unknown RAM 2G-08-10-12-1333 2GB DIMM DDR3 1333MT/s     | 1        | 6.25%   |
| SK Hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s | 1        | 6.25%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s  | 1        | 6.25%   |
| Samsung RAM M378A4G43MB1-CTD 32GB DIMM DDR4 2666MT/s    | 1        | 6.25%   |
| Micron RAM 18ASF4G72AZ-3G2B1 32GB DIMM DDR4 3200MT/s    | 1        | 6.25%   |
| Micron RAM 16ATF2G64HZ-2G6J1 16GB SODIMM DDR4 2667MT/s  | 1        | 6.25%   |
| Micron RAM 16ATF2G64AZ-3G2J1 16GB DIMM DDR4 3200MT/s    | 1        | 6.25%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 2666MT/s     | 1        | 6.25%   |
| Kingston RAM KHX1600C10D3/ 8GB DIMM DDR3 1600MT/s       | 1        | 6.25%   |
| Kingston RAM 9905713-030.A00G 8GB DIMM DDR4 2666MT/s    | 1        | 6.25%   |
| Crucial RAM CT16G4DFD832A.C16FP 16GB DIMM DDR4 3200MT/s | 1        | 6.25%   |
| Crucial RAM BL16G36C16U4B.M8FB1 16GB DIMM DDR4 3600MT/s | 1        | 6.25%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s   | 1        | 6.25%   |
| Corsair RAM CMD128GX4M8A2400C14 16GB DIMM DDR4 2133MT/s | 1        | 6.25%   |
| Unknown                                                 | 1        | 6.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 12       | 80%     |
| DDR3 | 3        | 20%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 12       | 80%     |
| SODIMM | 3        | 20%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 6        | 40%     |
| 8192  | 5        | 33.33%  |
| 32768 | 2        | 13.33%  |
| 4096  | 1        | 6.67%   |
| 2048  | 1        | 6.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 5        | 31.25%  |
| 2666  | 3        | 18.75%  |
| 2667  | 2        | 12.5%   |
| 1600  | 2        | 12.5%   |
| 3600  | 1        | 6.25%   |
| 2933  | 1        | 6.25%   |
| 2133  | 1        | 6.25%   |
| 1333  | 1        | 6.25%   |

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
| 0     | 15       | 65.22%  |
| 1     | 4        | 17.39%  |
| 4     | 2        | 8.7%    |
| 2     | 2        | 8.7%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 4        | 33.33%  |
| Net/wireless             | 3        | 25%     |
| Sound                    | 2        | 16.67%  |
| Bluetooth                | 2        | 16.67%  |
| Network                  | 1        | 8.33%   |

