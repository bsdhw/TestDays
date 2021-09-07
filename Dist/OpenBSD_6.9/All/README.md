OpenBSD 6.9 - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for OpenBSD 6.9 (Beta test).

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/OpenBSD_6.9/Desktop/README.md) and [notebooks](/Dist/OpenBSD_6.9/Notebook/README.md).

Full-feature report is available here: https://bsd-hardware.info/?view=trends&rel=openbsd-6.9

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

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [1b6bf4666c](https://bsd-hardware.info/?probe=1b6bf4666c) | Sep 05, 2021 |
| Sony          | VGN-P698E                   | Notebook    | [c8274e858d](https://bsd-hardware.info/?probe=c8274e858d) | Aug 30, 2021 |
| Lenovo        | FLEX 3-1120 80LX            | Notebook    | [2f1a1a42b8](https://bsd-hardware.info/?probe=2f1a1a42b8) | Aug 29, 2021 |
| Gigabyte      | GA-7VT600                   | Desktop     | [83b86f3e8c](https://bsd-hardware.info/?probe=83b86f3e8c) | Aug 23, 2021 |
| Acer          | Aspire ES1-132              | Notebook    | [43c82b1b16](https://bsd-hardware.info/?probe=43c82b1b16) | Aug 22, 2021 |
| IBM           | ThinkPad T42 2374K46        | Notebook    | [d93b6d68fa](https://bsd-hardware.info/?probe=d93b6d68fa) | Aug 18, 2021 |
| Lenovo        | IdeaPad 1 11IGL05 81VT      | Notebook    | [f7725f06df](https://bsd-hardware.info/?probe=f7725f06df) | Aug 18, 2021 |
| Lenovo        | Yoga 6 13ARE05 82FN         | Notebook    | [6f7976c329](https://bsd-hardware.info/?probe=6f7976c329) | Aug 16, 2021 |
| Standard      | TF                          | Notebook    | [c7995f2022](https://bsd-hardware.info/?probe=c7995f2022) | Aug 12, 2021 |
| HP            | Notebook                    | Notebook    | [a3c3297cd2](https://bsd-hardware.info/?probe=a3c3297cd2) | Aug 08, 2021 |
| HP            | Notebook                    | Notebook    | [0c316107a4](https://bsd-hardware.info/?probe=0c316107a4) | Aug 08, 2021 |
| Unknown       | FriendlyElec NanoPi R4S     | Desktop     | [ac10928ac3](https://bsd-hardware.info/?probe=ac10928ac3) | Aug 05, 2021 |
| Lenovo        | ThinkPad T430 2349U2B       | Notebook    | [90d85e011f](https://bsd-hardware.info/?probe=90d85e011f) | Jul 31, 2021 |
| Lenovo        | Yoga 330-11IGM 81A6         | Notebook    | [5404f763dd](https://bsd-hardware.info/?probe=5404f763dd) | Jul 26, 2021 |
| Lenovo        | ThinkPad T400 2767WSB       | Notebook    | [36ce1d1e00](https://bsd-hardware.info/?probe=36ce1d1e00) | Jul 24, 2021 |
| Unknown       | Pine64 Rock64               | Desktop     | [0df3f7572c](https://bsd-hardware.info/?probe=0df3f7572c) | Jul 23, 2021 |
| MSI           | MS-1613                     | Notebook    | [795e61c1a3](https://bsd-hardware.info/?probe=795e61c1a3) | Jul 21, 2021 |
| ASUSTek       | B202                        | Desktop     | [9f5f0a4117](https://bsd-hardware.info/?probe=9f5f0a4117) | Jul 21, 2021 |
| Lenovo        | ThinkPad X270 20HNA006ID    | Notebook    | [6fc7c972a5](https://bsd-hardware.info/?probe=6fc7c972a5) | Jul 19, 2021 |
| Lenovo        | ThinkPad T420 4236MBG       | Notebook    | [5b43300a93](https://bsd-hardware.info/?probe=5b43300a93) | Jul 13, 2021 |
| Unknown       | Pine64 Rock64               | Desktop     | [83c18360fc](https://bsd-hardware.info/?probe=83c18360fc) | Jul 12, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [740c5182d3](https://bsd-hardware.info/?probe=740c5182d3) | Jul 11, 2021 |
| HP            | ProLiant DL360e Gen8        | Desktop     | [30eeb098b0](https://bsd-hardware.info/?probe=30eeb098b0) | Jul 10, 2021 |
| HP            | ProLiant DL320 G5           | Desktop     | [3b4ee33976](https://bsd-hardware.info/?probe=3b4ee33976) | Jul 10, 2021 |
| Foxconn       | AT-7000 Series              | Desktop     | [3802fb98b5](https://bsd-hardware.info/?probe=3802fb98b5) | Jul 10, 2021 |
| Unknown       | Pine64 Rock64               | Desktop     | [106c7823a8](https://bsd-hardware.info/?probe=106c7823a8) | Jul 10, 2021 |
| Lenovo        | ThinkPad X230 232578G       | Notebook    | [a8c497b58b](https://bsd-hardware.info/?probe=a8c497b58b) | Jul 09, 2021 |
| Unknown       | Pine64 Rock64               | Desktop     | [9cffa29c69](https://bsd-hardware.info/?probe=9cffa29c69) | Jul 08, 2021 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [55f46bc85d](https://bsd-hardware.info/?probe=55f46bc85d) | Jul 07, 2021 |
| HP            | Pavilion dm1                | Notebook    | [a863347147](https://bsd-hardware.info/?probe=a863347147) | Jul 03, 2021 |
| Lenovo        | Yoga 330-11IGM 81A6         | Notebook    | [72e208aa92](https://bsd-hardware.info/?probe=72e208aa92) | Jul 02, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [cfb0e172cb](https://bsd-hardware.info/?probe=cfb0e172cb) | Jun 27, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [443817737d](https://bsd-hardware.info/?probe=443817737d) | Jun 24, 2021 |
| Microsoft     | Surface Pro 7               | Tablet      | [1b8d66e5f0](https://bsd-hardware.info/?probe=1b8d66e5f0) | Jun 22, 2021 |
| Dell          | 0GTK4K A02                  | Desktop     | [bb610333d0](https://bsd-hardware.info/?probe=bb610333d0) | Jun 22, 2021 |
| Unknown       | Unknown                     | Notebook    | [f37bf77853](https://bsd-hardware.info/?probe=f37bf77853) | Jun 20, 2021 |
| Supermicro    | X8DTH-i/6/iF/6F             | Desktop     | [1e8ac47693](https://bsd-hardware.info/?probe=1e8ac47693) | Jun 08, 2021 |
| Supermicro    | X8DTH-i/6/iF/6F             | Desktop     | [bd4a74c5e5](https://bsd-hardware.info/?probe=bd4a74c5e5) | Jun 08, 2021 |
| Supermicro    | X10SLH-N6-ST031             | Desktop     | [e54175f99f](https://bsd-hardware.info/?probe=e54175f99f) | Jun 06, 2021 |
| Lenovo        | ThinkPad X250 20CLS7WY04    | Notebook    | [b60f4a19ee](https://bsd-hardware.info/?probe=b60f4a19ee) | Jun 06, 2021 |
| ASRock        | Z68 Extreme4 Gen3           | Desktop     | [58c8cdc060](https://bsd-hardware.info/?probe=58c8cdc060) | Jun 05, 2021 |
| Lenovo        | ThinkPad T430 23511A6       | Notebook    | [89fb2aa493](https://bsd-hardware.info/?probe=89fb2aa493) | Jun 05, 2021 |
| Lenovo        | ThinkPad T400 6475K43       | Notebook    | [1b3e80e2e9](https://bsd-hardware.info/?probe=1b3e80e2e9) | Jun 03, 2021 |
| Supermicro    | Super Server                | Server      | [68579d4660](https://bsd-hardware.info/?probe=68579d4660) | Jun 03, 2021 |
| Lenovo        | IdeaPad S210 Touch 20257    | Notebook    | [392df069bd](https://bsd-hardware.info/?probe=392df069bd) | Jun 02, 2021 |
| Apple         | PowerBook5,2                | Notebook    | [8cc0aab53c](https://bsd-hardware.info/?probe=8cc0aab53c) | May 31, 2021 |
| Shuttle       | DS77U                       | Desktop     | [5d1c78145e](https://bsd-hardware.info/?probe=5d1c78145e) | May 30, 2021 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [ca05acd52f](https://bsd-hardware.info/?probe=ca05acd52f) | May 30, 2021 |
| HP            | 530 Notebook PC(KP477AA#... | Notebook    | [9c7b85c190](https://bsd-hardware.info/?probe=9c7b85c190) | May 30, 2021 |
| ASRock        | X570M Pro4                  | Desktop     | [1d1a5afcfb](https://bsd-hardware.info/?probe=1d1a5afcfb) | May 28, 2021 |
| Alienware     | Aurora Ryzen Edition        | Desktop     | [b9dc8b182c](https://bsd-hardware.info/?probe=b9dc8b182c) | May 28, 2021 |
| ASUSTek       | B202                        | Desktop     | [0b66a5fd20](https://bsd-hardware.info/?probe=0b66a5fd20) | May 21, 2021 |
| Unknown       | Unknown                     | Notebook    | [b296fb35e2](https://bsd-hardware.info/?probe=b296fb35e2) | May 19, 2021 |
| Unknown       | Unknown                     | Notebook    | [750e01de05](https://bsd-hardware.info/?probe=750e01de05) | May 19, 2021 |
| Panasonic     | CF-53AAGHYDM                | Notebook    | [ef5e9ec095](https://bsd-hardware.info/?probe=ef5e9ec095) | May 18, 2021 |
| Panasonic     | CF-52PFPBSFQ                | Notebook    | [65f5931910](https://bsd-hardware.info/?probe=65f5931910) | May 18, 2021 |
| Lenovo        | ThinkPad T430 2347GZU       | Notebook    | [1e9f399d73](https://bsd-hardware.info/?probe=1e9f399d73) | May 17, 2021 |
| Lenovo        | ThinkPad T410 2537N24       | Notebook    | [109f3afa21](https://bsd-hardware.info/?probe=109f3afa21) | May 17, 2021 |
| ASUSTek       | 1000HE                      | Notebook    | [f92f43bc54](https://bsd-hardware.info/?probe=f92f43bc54) | May 17, 2021 |
| Matsushita... | CF-51RCVDNLM                | Notebook    | [33bc82e701](https://bsd-hardware.info/?probe=33bc82e701) | May 17, 2021 |
| Matsushita... | CF-48V4KNDQM                | Notebook    | [bf76401b74](https://bsd-hardware.info/?probe=bf76401b74) | May 17, 2021 |
| PC Engines    | APU2                        | Desktop     | [c99a0b0e4d](https://bsd-hardware.info/?probe=c99a0b0e4d) | May 05, 2021 |
| Supermicro    | X8STi                       | Desktop     | [c615ef1edf](https://bsd-hardware.info/?probe=c615ef1edf) | May 04, 2021 |
| ASUSTek       | UX430UNR                    | Notebook    | [bfe7ec0975](https://bsd-hardware.info/?probe=bfe7ec0975) | May 03, 2021 |
| PC Engines    | apu1                        | Desktop     | [7b4678c7ef](https://bsd-hardware.info/?probe=7b4678c7ef) | May 03, 2021 |
| Acer          | AO531h                      | Notebook    | [614326a3d3](https://bsd-hardware.info/?probe=614326a3d3) | May 03, 2021 |
| Acer          | AO531h                      | Notebook    | [9de7465352](https://bsd-hardware.info/?probe=9de7465352) | May 03, 2021 |
| ASUSTek       | P10S-I Series               | Desktop     | [6548ae7d88](https://bsd-hardware.info/?probe=6548ae7d88) | May 01, 2021 |
| PC Engines    | apu1                        | Desktop     | [c5ae3337e7](https://bsd-hardware.info/?probe=c5ae3337e7) | May 01, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [6e8891f184](https://bsd-hardware.info/?probe=6e8891f184) | Apr 24, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [403a237513](https://bsd-hardware.info/?probe=403a237513) | Apr 14, 2021 |
| Lenovo        | ThinkPad Edge 05796AU       | Notebook    | [4a094815c0](https://bsd-hardware.info/?probe=4a094815c0) | Mar 24, 2021 |
| Lenovo        | ThinkPad X220 4291ON5       | Notebook    | [8d81204137](https://bsd-hardware.info/?probe=8d81204137) | Mar 22, 2021 |
| Dell          | Latitude E7270              | Notebook    | [5ba79f9aa5](https://bsd-hardware.info/?probe=5ba79f9aa5) | Mar 19, 2021 |
| HP            | ProLiant DL360 Gen9         | Desktop     | [b283b34881](https://bsd-hardware.info/?probe=b283b34881) | Mar 17, 2021 |
| Supermicro    | Super Server                | Server      | [ec1e532ea9](https://bsd-hardware.info/?probe=ec1e532ea9) | Mar 17, 2021 |
| Lenovo        | ThinkPad X280 20KESA000B    | Notebook    | [e2b586d597](https://bsd-hardware.info/?probe=e2b586d597) | Mar 17, 2021 |
| HP            | ProLiant DL360 Gen9         | Desktop     | [bf440e72a1](https://bsd-hardware.info/?probe=bf440e72a1) | Mar 17, 2021 |
| HP            | EliteDesk 800 G5 SFF        | Desktop     | [aaf9bc1c12](https://bsd-hardware.info/?probe=aaf9bc1c12) | Mar 17, 2021 |
| Apple         | MacBookAir6,2               | Notebook    | [52584aaa97](https://bsd-hardware.info/?probe=52584aaa97) | Mar 14, 2021 |
| Apple         | MacBookAir6,2               | Notebook    | [fb136a79e7](https://bsd-hardware.info/?probe=fb136a79e7) | Mar 13, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [9f4a3cd83d](https://bsd-hardware.info/?probe=9f4a3cd83d) | Mar 08, 2021 |
| Lenovo        | ThinkPad T400 6475P1G       | Notebook    | [6a0907b5e8](https://bsd-hardware.info/?probe=6a0907b5e8) | Mar 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [7d1ff5416d](https://bsd-hardware.info/?probe=7d1ff5416d) | Mar 01, 2021 |
| Acer          | Spin SP111-32N              | Notebook    | [9f44af71aa](https://bsd-hardware.info/?probe=9f44af71aa) | Feb 28, 2021 |
| Acer          | AOA150                      | Notebook    | [91e5ec60b9](https://bsd-hardware.info/?probe=91e5ec60b9) | Feb 21, 2021 |
| Dell          | XPS 13 9360                 | Notebook    | [c2dded2160](https://bsd-hardware.info/?probe=c2dded2160) | Feb 19, 2021 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | Notebook    | [4f646f53e9](https://bsd-hardware.info/?probe=4f646f53e9) | Feb 14, 2021 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| amd64  | 59        | 80.82%  |
| i386   | 11        | 15.07%  |
| arm64  | 2         | 2.74%   |
| macppc | 1         | 1.37%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| fvwm    | 57        | 78.08%  |
| Console | 15        | 20.55%  |
| i3      | 1         | 1.37%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 56        | 76.71%  |
| Console | 17        | 23.29%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 64        | 87.67%  |
| SLiM    | 9         | 12.33%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 57        | 78.08%  |
| en_US   | 11        | 15.07%  |
| ru_RU   | 3         | 4.11%   |
| en_EN   | 1         | 1.37%   |
| C       | 1         | 1.37%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 41        | 55.41%  |
| BIOS | 33        | 44.59%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ffs  | 73        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 38        | 51.35%  |
| MBR  | 36        | 48.65%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 22        | 30.14%  |
| Hewlett-Packard                | 9         | 12.33%  |
| ASUSTek Computer               | 6         | 8.22%   |
| Supermicro                     | 5         | 6.85%   |
| Acer                           | 5         | 6.85%   |
| Unknown                        | 3         | 4.11%   |
| PC Engines                     | 2         | 2.74%   |
| Panasonic                      | 2         | 2.74%   |
| Matsushita Electric Industrial | 2         | 2.74%   |
| Dell                           | 2         | 2.74%   |
| ASRock                         | 2         | 2.74%   |
| Apple                          | 2         | 2.74%   |
| Standard                       | 1         | 1.37%   |
| Sony                           | 1         | 1.37%   |
| Shuttle                        | 1         | 1.37%   |
| Samsung Electronics            | 1         | 1.37%   |
| MSI                            | 1         | 1.37%   |
| Microsoft                      | 1         | 1.37%   |
| IBM                            | 1         | 1.37%   |
| Gigabyte Technology            | 1         | 1.37%   |
| Foxconn                        | 1         | 1.37%   |
| Clevo                          | 1         | 1.37%   |
| Alienware                      | 1         | 1.37%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 3         | 4.11%   |
| Supermicro Super Server                     | 2         | 2.74%   |
| Supermicro X8STi                            | 1         | 1.37%   |
| Supermicro X8DTH-i/6/iF/6F                  | 1         | 1.37%   |
| Supermicro X10SLH-N6-ST031                  | 1         | 1.37%   |
| Standard TF                                 | 1         | 1.37%   |
| Sony VGN-P698E                              | 1         | 1.37%   |
| Shuttle DS77U                               | 1         | 1.37%   |
| Samsung 3570R/370R/470R/450R/510R/4450RV    | 1         | 1.37%   |
| PC Engines APU2                             | 1         | 1.37%   |
| PC Engines apu1                             | 1         | 1.37%   |
| Panasonic CF-53AAGHYDM                      | 1         | 1.37%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 1.37%   |
| MSI MS-1613                                 | 1         | 1.37%   |
| Microsoft Surface Pro 7                     | 1         | 1.37%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 1.37%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 1.37%   |
| Lenovo Yoga 6 13ARE05 82FN                  | 1         | 1.37%   |
| Lenovo Yoga 330-11IGM 81A6                  | 1         | 1.37%   |
| Lenovo ThinkPad X280 20KESA000B             | 1         | 1.37%   |
| Lenovo ThinkPad X270 20HNA006ID             | 1         | 1.37%   |
| Lenovo ThinkPad X250 20CLS7WY04             | 1         | 1.37%   |
| Lenovo ThinkPad X230 232578G                | 1         | 1.37%   |
| Lenovo ThinkPad X220 4291ON5                | 1         | 1.37%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD00KTMH    | 1         | 1.37%   |
| Lenovo ThinkPad T430 23511A6                | 1         | 1.37%   |
| Lenovo ThinkPad T430 2349U2B                | 1         | 1.37%   |
| Lenovo ThinkPad T430 2347GZU                | 1         | 1.37%   |
| Lenovo ThinkPad T420 4236MBG                | 1         | 1.37%   |
| Lenovo ThinkPad T410 2537N24                | 1         | 1.37%   |
| Lenovo ThinkPad T400 6475P1G                | 1         | 1.37%   |
| Lenovo ThinkPad T400 6475K43                | 1         | 1.37%   |
| Lenovo ThinkPad T400 2767WSB                | 1         | 1.37%   |
| Lenovo ThinkPad T14 Gen 1 20S1S07800        | 1         | 1.37%   |
| Lenovo ThinkPad Edge 05796AU                | 1         | 1.37%   |
| Lenovo ThinkPad E490 20N8CTO1WW             | 1         | 1.37%   |
| Lenovo IdeaPad S210 Touch 20257             | 1         | 1.37%   |
| Lenovo IdeaPad 1 11IGL05 81VT               | 1         | 1.37%   |
| Lenovo FLEX 3-1120 80LX                     | 1         | 1.37%   |
| IBM ThinkPad T42 2374K46                    | 1         | 1.37%   |
| HP ProLiant DL360e Gen8                     | 1         | 1.37%   |
| HP ProLiant DL360 Gen9                      | 1         | 1.37%   |
| HP ProLiant DL320 G5                        | 1         | 1.37%   |
| HP ProBook 450 G2                           | 1         | 1.37%   |
| HP Pavilion Gaming Laptop 15-ec1xxx         | 1         | 1.37%   |
| HP Pavilion dm1                             | 1         | 1.37%   |
| HP Notebook                                 | 1         | 1.37%   |
| HP EliteDesk 800 G5 SFF                     | 1         | 1.37%   |
| HP 530 Notebook PC(KP477AA#ACB)             | 1         | 1.37%   |
| Gigabyte GA-7VT600                          | 1         | 1.37%   |
| Foxconn AT-7000 Series                      | 1         | 1.37%   |
| Dell XPS 13 9360                            | 1         | 1.37%   |
| Dell Latitude E7270                         | 1         | 1.37%   |
| Clevo W240EU/W250EUQ/W270EUQ                | 1         | 1.37%   |
| ASUS UX430UNR                               | 1         | 1.37%   |
| ASUS ROG STRIX B550-I GAMING                | 1         | 1.37%   |
| ASUS PRIME B560M-A                          | 1         | 1.37%   |
| ASUS P10S-I Series                          | 1         | 1.37%   |
| ASUS B202                                   | 1         | 1.37%   |
| ASUS 1000HE                                 | 1         | 1.37%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad                             | 17        | 23.29%  |
| HP ProLiant                                 | 3         | 4.11%   |
| Unknown                                     | 3         | 4.11%   |
| Supermicro Super                            | 2         | 2.74%   |
| Lenovo Yoga                                 | 2         | 2.74%   |
| Lenovo IdeaPad                              | 2         | 2.74%   |
| HP Pavilion                                 | 2         | 2.74%   |
| Supermicro X8STi                            | 1         | 1.37%   |
| Supermicro X8DTH-i                          | 1         | 1.37%   |
| Supermicro X10SLH-N6-ST031                  | 1         | 1.37%   |
| Standard TF                                 | 1         | 1.37%   |
| Sony VGN-P698E                              | 1         | 1.37%   |
| Shuttle DS77U                               | 1         | 1.37%   |
| Samsung 3570R                               | 1         | 1.37%   |
| PC Engines APU2                             | 1         | 1.37%   |
| PC Engines apu1                             | 1         | 1.37%   |
| Panasonic CF-53AAGHYDM                      | 1         | 1.37%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 1.37%   |
| MSI MS-1613                                 | 1         | 1.37%   |
| Microsoft Surface                           | 1         | 1.37%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 1.37%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 1.37%   |
| Lenovo FLEX                                 | 1         | 1.37%   |
| IBM ThinkPad                                | 1         | 1.37%   |
| HP ProBook                                  | 1         | 1.37%   |
| HP Notebook                                 | 1         | 1.37%   |
| HP EliteDesk                                | 1         | 1.37%   |
| HP 530                                      | 1         | 1.37%   |
| Gigabyte GA-7VT600                          | 1         | 1.37%   |
| Foxconn AT-7000                             | 1         | 1.37%   |
| Dell XPS                                    | 1         | 1.37%   |
| Dell Latitude                               | 1         | 1.37%   |
| Clevo W240EU                                | 1         | 1.37%   |
| ASUS UX430UNR                               | 1         | 1.37%   |
| ASUS ROG                                    | 1         | 1.37%   |
| ASUS PRIME                                  | 1         | 1.37%   |
| ASUS P10S-I                                 | 1         | 1.37%   |
| ASUS B202                                   | 1         | 1.37%   |
| ASUS 1000HE                                 | 1         | 1.37%   |
| ASRock Z68                                  | 1         | 1.37%   |
| ASRock X570M                                | 1         | 1.37%   |
| Apple PowerBook5                            | 1         | 1.37%   |
| Apple MacBookAir6                           | 1         | 1.37%   |
| Alienware Aurora                            | 1         | 1.37%   |
| Acer Spin                                   | 1         | 1.37%   |
| Acer Nitro                                  | 1         | 1.37%   |
| Acer Aspire                                 | 1         | 1.37%   |
| Acer AOA150                                 | 1         | 1.37%   |
| Acer AO531h                                 | 1         | 1.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 14        | 19.18%  |
| 2021    | 9         | 12.33%  |
| 2019    | 8         | 10.96%  |
| 2018    | 8         | 10.96%  |
| 2008    | 5         | 6.85%   |
| 2013    | 4         | 5.48%   |
| 2012    | 4         | 5.48%   |
| Unknown | 4         | 5.48%   |
| 2017    | 3         | 4.11%   |
| 2010    | 3         | 4.11%   |
| 2014    | 2         | 2.74%   |
| 2011    | 2         | 2.74%   |
| 2009    | 2         | 2.74%   |
| 2006    | 2         | 2.74%   |
| 2015    | 1         | 1.37%   |
| 2003    | 1         | 1.37%   |
| 2002    | 1         | 1.37%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 49        | 67.12%  |
| Desktop  | 21        | 28.77%  |
| Server   | 2         | 2.74%   |
| Tablet   | 1         | 1.37%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 69        | 94.52%  |
| Yes  | 4         | 5.48%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 15        | 20.55%  |
| 4.01-8.0    | 14        | 19.18%  |
| 16.01-24.0  | 14        | 19.18%  |
| 3.01-4.0    | 8         | 10.96%  |
| 2.01-3.0    | 7         | 9.59%   |
| 32.01-64.0  | 4         | 5.48%   |
| 1.01-2.0    | 4         | 5.48%   |
| 0.51-1.0    | 4         | 5.48%   |
| 24.01-32.0  | 2         | 2.74%   |
| 64.01-256.0 | 1         | 1.37%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 59        | 80.82%  |
| 0        | 6         | 8.22%   |
| 0.51-1.0 | 5         | 6.85%   |
| 4.01-8.0 | 1         | 1.37%   |
| 1.01-2.0 | 1         | 1.37%   |
| Unknown  | 1         | 1.37%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 41        | 55.41%  |
| 2      | 20        | 27.03%  |
| 3      | 5         | 6.76%   |
| 4      | 4         | 5.41%   |
| 6      | 2         | 2.7%    |
| 7      | 1         | 1.35%   |
| 5      | 1         | 1.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 73        | 100%    |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 62        | 84.93%  |
| No        | 11        | 15.07%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 54        | 73.97%  |
| No        | 19        | 26.03%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 42        | 57.53%  |
| Yes       | 31        | 42.47%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 16        | 21.92%  |
| Germany      | 9         | 12.33%  |
| Canada       | 9         | 12.33%  |
| Russia       | 6         | 8.22%   |
| France       | 6         | 8.22%   |
| Netherlands  | 5         | 6.85%   |
| Ukraine      | 3         | 4.11%   |
| Sweden       | 3         | 4.11%   |
| Spain        | 2         | 2.74%   |
| Portugal     | 2         | 2.74%   |
| Latvia       | 2         | 2.74%   |
| UK           | 1         | 1.37%   |
| Turkey       | 1         | 1.37%   |
| Taiwan       | 1         | 1.37%   |
| Saudi Arabia | 1         | 1.37%   |
| Philippines  | 1         | 1.37%   |
| Norway       | 1         | 1.37%   |
| Malaysia     | 1         | 1.37%   |
| Indonesia    | 1         | 1.37%   |
| Chile        | 1         | 1.37%   |
| Brazil       | 1         | 1.37%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Saint-Laurent         | 7         | 9.46%   |
| Moscow                | 4         | 5.41%   |
| Riga                  | 2         | 2.7%    |
| Los Angeles           | 2         | 2.7%    |
| Brooklyn              | 2         | 2.7%    |
| Bielefeld             | 2         | 2.7%    |
| Berlin                | 2         | 2.7%    |
| Barneveld             | 2         | 2.7%    |
| 's-Hertogenbosch      | 2         | 2.7%    |
| Yekaterinburg         | 1         | 1.35%   |
| Watford               | 1         | 1.35%   |
| Victoria              | 1         | 1.35%   |
| Van Nuys              | 1         | 1.35%   |
| Valdivia              | 1         | 1.35%   |
| Teriang               | 1         | 1.35%   |
| São Paulo            | 1         | 1.35%   |
| Syeverodonets'k       | 1         | 1.35%   |
| Surabaya              | 1         | 1.35%   |
| Spokane               | 1         | 1.35%   |
| Solna                 | 1         | 1.35%   |
| Soeraker              | 1         | 1.35%   |
| Sedavi                | 1         | 1.35%   |
| Sechelt               | 1         | 1.35%   |
| Saint-Martin-d'Hères | 1         | 1.35%   |
| Roubaix               | 1         | 1.35%   |
| Roseville             | 1         | 1.35%   |
| Rodgau                | 1         | 1.35%   |
| Riyadh                | 1         | 1.35%   |
| Quezon City           | 1         | 1.35%   |
| Plainfield            | 1         | 1.35%   |
| Papillion             | 1         | 1.35%   |
| Oeiras                | 1         | 1.35%   |
| New York              | 1         | 1.35%   |
| New Taipei            | 1         | 1.35%   |
| Neuilly-sur-Marne     | 1         | 1.35%   |
| Monts                 | 1         | 1.35%   |
| McLeod                | 1         | 1.35%   |
| Madrid                | 1         | 1.35%   |
| Kyiv                  | 1         | 1.35%   |
| Korolyov              | 1         | 1.35%   |
| Independence          | 1         | 1.35%   |
| Hoeviksnaes           | 1         | 1.35%   |
| Hockenheim            | 1         | 1.35%   |
| Heilbronn             | 1         | 1.35%   |
| Hamilton              | 1         | 1.35%   |
| Greensburg            | 1         | 1.35%   |
| Frankfurt am Main     | 1         | 1.35%   |
| Estoril               | 1         | 1.35%   |
| Donetsk               | 1         | 1.35%   |
| Corbarieu             | 1         | 1.35%   |
| Commack               | 1         | 1.35%   |
| Clearwater            | 1         | 1.35%   |
| Bordeaux              | 1         | 1.35%   |
| Bloomfield            | 1         | 1.35%   |
| Arendal               | 1         | 1.35%   |
| Ankara                | 1         | 1.35%   |
| Amsterdam             | 1         | 1.35%   |
| Aachen                | 1         | 1.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| NVMe                | 16        | 18     | 17.78%  |
| WDC                 | 14        | 15     | 15.56%  |
| Samsung Electronics | 13        | 18     | 14.44%  |
| Seagate             | 6         | 11     | 6.67%   |
| Toshiba             | 5         | 5      | 5.56%   |
| HGST                | 4         | 5      | 4.44%   |
| SanDisk             | 3         | 3      | 3.33%   |
| OPENBSD             | 3         | 3      | 3.33%   |
| SK Hynix            | 2         | 2      | 2.22%   |
| Kingston            | 2         | 2      | 2.22%   |
| Intel               | 2         | 3      | 2.22%   |
| Hitachi             | 2         | 2      | 2.22%   |
| Hewlett-Packard     | 2         | 6      | 2.22%   |
| Crucial             | 2         | 2      | 2.22%   |
| Zheino              | 1         | 1      | 1.11%   |
| USB                 | 1         | 1      | 1.11%   |
| UDinfo              | 1         | 1      | 1.11%   |
| Transcend           | 1         | 4      | 1.11%   |
| Team                | 1         | 1      | 1.11%   |
| SPCC                | 1         | 1      | 1.11%   |
| Product:            | 1         | 1      | 1.11%   |
| Phison              | 1         | 1      | 1.11%   |
| Multiple            | 1         | 1      | 1.11%   |
| LSI                 | 1         | 1      | 1.11%   |
| Fujitsu             | 1         | 1      | 1.11%   |
| asmedia             | 1         | 1      | 1.11%   |
| Apple               | 1         | 1      | 1.11%   |
| A-DATA Technology   | 1         | 1      | 1.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| WDC WD1600BEVT-22ZCT0 160GB       | 3         | 2.97%   |
| OPENBSD SR RAID 1 304GB           | 3         | 2.97%   |
| NVMe Samsung SSD 960 500GB        | 3         | 2.97%   |
| Samsung SSD 850 EVO 250GB         | 2         | 1.98%   |
| NVMe WDC PC SN730 SDB 512GB       | 2         | 1.98%   |
| NVMe SAMSUNG MZVLB256 256GB       | 2         | 1.98%   |
| HGST HUS724020ALA640 2TB          | 2         | 1.98%   |
| Zheino CHN-mSATAQ3-120 120GB      | 1         | 0.99%   |
| WDC WDS500G2B0A-00SM50 500GB      | 1         | 0.99%   |
| WDC WD80EFAX-68KNBN0 8TB          | 1         | 0.99%   |
| WDC WD7500BPKX-00HPJT0 752GB      | 1         | 0.99%   |
| WDC WD7500BPKT-00PK4T0 752GB      | 1         | 0.99%   |
| WDC WD60EFRX-68L0BN1 6TB          | 1         | 0.99%   |
| WDC WD5000LPLX-00ZNTT0 500GB      | 1         | 0.99%   |
| WDC WD5000LPCX-24C6HT0 500GB      | 1         | 0.99%   |
| WDC WD3200BEVE-00A0HT0 320GB      | 1         | 0.99%   |
| WDC WD3200BEKT-08PVMT1 320GB      | 1         | 0.99%   |
| WDC WD20PURX-64P6ZY0 2TB          | 1         | 0.99%   |
| WDC WD10JPLX-00MBPT0 1TB          | 1         | 0.99%   |
| WDC WD Elements 25A3 4TB          | 1         | 0.99%   |
| USB SanDisk 3.2Gen1 16GB          | 1         | 0.99%   |
| UDinfo M2S 120GB                  | 1         | 0.99%   |
| Transcend 3E128-TS2-550B01 100GB  | 1         | 0.99%   |
| Toshiba MQ04ABF100 1TB            | 1         | 0.99%   |
| Toshiba MK8025GAS 80GB            | 1         | 0.99%   |
| Toshiba MK3256GSY 320GB           | 1         | 0.99%   |
| Toshiba MK1665GSX 160GB           | 1         | 0.99%   |
| Toshiba DT01ACA100 1TB            | 1         | 0.99%   |
| Team T253X2001T 1TB               | 1         | 0.99%   |
| SPCC Solid State Disk 128GB       | 1         | 0.99%   |
| SK Hynix SC311 SATA 256GB         | 1         | 0.99%   |
| SK Hynix HFS128G39TND-N210A 128GB | 1         | 0.99%   |
| Seagate ST950032 5AS 500GB        | 1         | 0.99%   |
| Seagate ST9160821A 160GB          | 1         | 0.99%   |
| Seagate ST9160310AS 160GB         | 1         | 0.99%   |
| Seagate ST500LT012-9WS142 500GB   | 1         | 0.99%   |
| Seagate ST3808110AS 80GB          | 1         | 0.99%   |
| Seagate ST380011A 80GB            | 1         | 0.99%   |
| Seagate ST3160212ACE 160GB        | 1         | 0.99%   |
| Seagate ST2000LX001-1RG174 2TB    | 1         | 0.99%   |
| Seagate Backup+ SL 1TB            | 1         | 0.99%   |
| SanDisk Ultra Fit 16GB            | 1         | 0.99%   |
| SanDisk Ultra 64GB                | 1         | 0.99%   |
| SanDisk SSD PLUS 120GB            | 1         | 0.99%   |
| Samsung SSD 860 PRO 256GB         | 1         | 0.99%   |
| Samsung SSD 860 EVO M.2 2TB       | 1         | 0.99%   |
| Samsung SSD 860 EVO M.2 250GB     | 1         | 0.99%   |
| Samsung SSD 860 EVO M.2 1TB       | 1         | 0.99%   |
| Samsung SSD 860 EVO 2TB           | 1         | 0.99%   |
| Samsung SSD 860 EVO 1TB           | 1         | 0.99%   |
| Samsung SSD 850 PRO 256GB         | 1         | 0.99%   |
| Samsung SSD 850 EVO 500GB         | 1         | 0.99%   |
| Samsung SSD 850 EVO 120GB         | 1         | 0.99%   |
| Samsung SSD 840 Series 120GB      | 1         | 0.99%   |
| Samsung MZ7TD256HAFV-000L7 256GB  | 1         | 0.99%   |
| Samsung MMCQE28GFMUP-MVA 128GB    | 1         | 0.99%   |
| Samsung Flash Drive FIT 32GB      | 1         | 0.99%   |
| Samsung Flash Drive 64GB          | 1         | 0.99%   |
| Samsung 870 QVO 8TB               | 1         | 0.99%   |
| Product: Revision: 1100 18302PB   | 1         | 0.99%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 13        | 14     | 24.53%  |
| NVMe                | 11        | 12     | 20.75%  |
| Seagate             | 6         | 11     | 11.32%  |
| Toshiba             | 5         | 5      | 9.43%   |
| HGST                | 4         | 5      | 7.55%   |
| OPENBSD             | 3         | 3      | 5.66%   |
| Samsung Electronics | 2         | 2      | 3.77%   |
| Hitachi             | 2         | 2      | 3.77%   |
| Hewlett-Packard     | 2         | 6      | 3.77%   |
| USB                 | 1         | 1      | 1.89%   |
| Product:            | 1         | 1      | 1.89%   |
| Multiple            | 1         | 1      | 1.89%   |
| LSI                 | 1         | 1      | 1.89%   |
| Fujitsu             | 1         | 1      | 1.89%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 16     | 31.58%  |
| NVMe                | 5         | 5      | 13.16%  |
| SanDisk             | 3         | 3      | 7.89%   |
| SK Hynix            | 2         | 2      | 5.26%   |
| Kingston            | 2         | 2      | 5.26%   |
| Intel               | 2         | 3      | 5.26%   |
| Crucial             | 2         | 2      | 5.26%   |
| Zheino              | 1         | 1      | 2.63%   |
| WDC                 | 1         | 1      | 2.63%   |
| UDinfo              | 1         | 1      | 2.63%   |
| Transcend           | 1         | 4      | 2.63%   |
| Team                | 1         | 1      | 2.63%   |
| SPCC                | 1         | 1      | 2.63%   |
| Phison              | 1         | 1      | 2.63%   |
| asmedia             | 1         | 1      | 2.63%   |
| Apple               | 1         | 1      | 2.63%   |
| A-DATA Technology   | 1         | 1      | 2.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 43        | 65     | 54.43%  |
| SSD  | 35        | 46     | 44.3%   |
| NVMe | 1         | 1      | 1.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 69        | 111    | 98.57%  |
| NVMe | 1         | 1      | 1.43%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 53        | 75     | 67.95%  |
| 0.51-1.0        | 15        | 22     | 19.23%  |
| 1.01-2.0        | 6         | 9      | 7.69%   |
| 4.01-10.0       | 2         | 3      | 2.56%   |
| More than 100.0 | 1         | 1      | 1.28%   |
| 3.01-4.0        | 1         | 1      | 1.28%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 26        | 35.62%  |
| 251-500        | 19        | 26.03%  |
| 51-100         | 9         | 12.33%  |
| 21-50          | 7         | 9.59%   |
| 1-20           | 5         | 6.85%   |
| More than 3000 | 4         | 5.48%   |
| 501-1000       | 2         | 2.74%   |
| 1001-2000      | 1         | 1.37%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 51        | 68.92%  |
| 21-50     | 7         | 9.46%   |
| 51-100    | 6         | 8.11%   |
| 101-250   | 5         | 6.76%   |
| 251-500   | 2         | 2.7%    |
| 1001-2000 | 2         | 2.7%    |
| 501-1000  | 1         | 1.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| WDC WD1600BEVT-22ZCT0 160GB      | 1         | 1      | 12.5%   |
| Transcend 3E128-TS2-550B01 100GB | 1         | 4      | 12.5%   |
| Seagate ST9160310AS 160GB        | 1         | 2      | 12.5%   |
| Seagate ST500LT012-9WS142 500GB  | 1         | 1      | 12.5%   |
| HGST HTS541010A7E630 1TB         | 1         | 2      | 12.5%   |
| HGST HTE725032A7E630 320GB       | 1         | 1      | 12.5%   |
| Apple SSD SD0128F 121GB          | 1         | 1      | 12.5%   |
| A-DATA Technology SP550 480GB    | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 2         | 3      | 25%     |
| HGST              | 2         | 3      | 25%     |
| WDC               | 1         | 1      | 12.5%   |
| Transcend         | 1         | 4      | 12.5%   |
| Apple             | 1         | 1      | 12.5%   |
| A-DATA Technology | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 3      | 40%     |
| HGST    | 2         | 3      | 40%     |
| WDC     | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 7      | 62.5%   |
| SSD  | 3         | 6      | 37.5%   |

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
| Works    | 49        | 72     | 63.64%  |
| Detected | 20        | 27     | 25.97%  |
| Malfunc  | 8         | 13     | 10.39%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 51        | 62.2%   |
| AMD                      | 8         | 9.76%   |
| Samsung Electronics      | 7         | 8.54%   |
| Sandisk                  | 4         | 4.88%   |
| Marvell Technology Group | 2         | 2.44%   |
| KIOXIA                   | 2         | 2.44%   |
| Hewlett-Packard          | 2         | 2.44%   |
| Broadcom / LSI           | 2         | 2.44%   |
| VIA Technologies         | 1         | 1.22%   |
| Toshiba                  | 1         | 1.22%   |
| SK Hynix                 | 1         | 1.22%   |
| Phison Electronics       | 1         | 1.22%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 8         | 8.89%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 5         | 5.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4         | 4.44%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 4         | 4.44%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 3         | 3.33%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3         | 3.33%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 3         | 3.33%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 3         | 3.33%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3         | 3.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 3         | 3.33%   |
| KIOXIA unknown                                                                          | 2         | 2.22%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 2         | 2.22%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 2         | 2.22%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 2         | 2.22%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2         | 2.22%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2         | 2.22%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2         | 2.22%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 1         | 1.11%   |
| Toshiba BG3 NVMe SSD Controller                                                         | 1         | 1.11%   |
| SK Hynix BC511                                                                          | 1         | 1.11%   |
| Sandisk WD Black SN850                                                                  | 1         | 1.11%   |
| Phison E12 NVMe Controller                                                              | 1         | 1.11%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                              | 1         | 1.11%   |
| Marvell Group 88SE912x SATA 6Gb/s Controller [IDE mode]                                 | 1         | 1.11%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                              | 1         | 1.11%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                 | 1         | 1.11%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1         | 1.11%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1         | 1.11%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1         | 1.11%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 1         | 1.11%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1         | 1.11%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 1         | 1.11%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 1         | 1.11%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1         | 1.11%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1         | 1.11%   |
| Intel Atom Processor C3000 Series SATA Controller 1                                     | 1         | 1.11%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 1         | 1.11%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                                  | 1         | 1.11%   |
| Intel 82801CAM IDE U100 Controller                                                      | 1         | 1.11%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 1         | 1.11%   |
| Intel 7 Series/C210 Series Chipset Family IDE-r Controller                              | 1         | 1.11%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                              | 1         | 1.11%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 1.11%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 1.11%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1         | 1.11%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 1         | 1.11%   |
| HP Smart Array Gen9 Controllers                                                         | 1         | 1.11%   |
| HP Smart Array G6 controllers                                                           | 1         | 1.11%   |
| Broadcom / LSI SSS6200 PCI-Express Flash SSD                                            | 1         | 1.11%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 1         | 1.11%   |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                          | 1         | 1.11%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 1         | 1.11%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1         | 1.11%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1         | 1.11%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 48        | 56.47%  |
| NVMe | 16        | 18.82%  |
| IDE  | 16        | 18.82%  |
| RAID | 3         | 3.53%   |
| SAS  | 2         | 2.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 60        | 82.19%  |
| AMD     | 10        | 13.7%   |
| ARM     | 2         | 2.74%   |
| Unknown | 1         | 1.37%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Core i5-3320M CPU @ 2.60GHz                             | 3         | 4.11%   |
| Intel Atom CPU N270 @ 1.60GHz ("GenuineIntel" 686-class)      | 3         | 4.11%   |
| Intel Core i7-8565U CPU @ 1.80GHz                             | 2         | 2.74%   |
| Intel Core i7-7500U CPU @ 2.70GHz                             | 2         | 2.74%   |
| Intel Core i5-2520M CPU @ 2.50GHz                             | 2         | 2.74%   |
| Intel Core i5 CPU M 520 @ 2.40GHz                             | 2         | 2.74%   |
| ARM Cortex-A53 r0p4                                           | 2         | 2.74%   |
| Intel Xeon CPU X5675 @ 3.07GHz                                | 1         | 1.37%   |
| Intel Xeon CPU W3530 @ 2.80GHz                                | 1         | 1.37%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz                           | 1         | 1.37%   |
| Intel Xeon CPU E5-2407 0 @ 2.20GHz                            | 1         | 1.37%   |
| Intel Xeon CPU E3-1270 v3 @ 3.50GHz                           | 1         | 1.37%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz                           | 1         | 1.37%   |
| Intel Xeon CPU D-1521 @ 2.40GHz                               | 1         | 1.37%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz                      | 1         | 1.37%   |
| Intel Pentium M processor 2.00GHz ("GenuineIntel" 686-class)  | 1         | 1.37%   |
| Intel Pentium CPU N4200 @ 1.10GHz                             | 1         | 1.37%   |
| Intel Pentium 4 Mobile CPU 1.60GHz ("GenuineIntel" 686-class) | 1         | 1.37%   |
| Intel CPU T2300 @ 1.66GHz ("GenuineIntel" 686-class)          | 1         | 1.37%   |
| Intel Core i7-8750H CPU @ 2.20GHz                             | 1         | 1.37%   |
| Intel Core i7-8550U CPU @ 1.80GHz                             | 1         | 1.37%   |
| Intel Core i7-3520M CPU @ 2.90GHz                             | 1         | 1.37%   |
| Intel Core i7-10510U CPU @ 1.80GHz                            | 1         | 1.37%   |
| Intel Core i5-9500 CPU @ 3.00GHz                              | 1         | 1.37%   |
| Intel Core i5-8350U CPU @ 1.70GHz                             | 1         | 1.37%   |
| Intel Core i5-8265U CPU @ 1.60GHz                             | 1         | 1.37%   |
| Intel Core i5-6300U CPU @ 2.40GHz                             | 1         | 1.37%   |
| Intel Core i5-5300U CPU @ 2.30GHz                             | 1         | 1.37%   |
| Intel Core i5-4250U CPU @ 1.30GHz                             | 1         | 1.37%   |
| Intel Core i5-3230M CPU @ 2.60GHz                             | 1         | 1.37%   |
| Intel Core i5-2540M CPU @ 2.60GHz                             | 1         | 1.37%   |
| Intel Core i5-2500K CPU @ 3.30GHz                             | 1         | 1.37%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz                            | 1         | 1.37%   |
| Intel Core i3-5005U CPU @ 2.00GHz                             | 1         | 1.37%   |
| Intel Core i3-4005U CPU @ 1.70GHz                             | 1         | 1.37%   |
| Intel Core i3-3217U CPU @ 1.80GHz                             | 1         | 1.37%   |
| Intel Core i3-3130M CPU @ 2.60GHz                             | 1         | 1.37%   |
| Intel Core i3-2375M CPU @ 1.50GHz                             | 1         | 1.37%   |
| Intel Core i3 CPU M 380 @ 2.53GHz                             | 1         | 1.37%   |
| Intel Core Duo CPU T2600 @ 2.16GHz ("GenuineIntel" 686-class) | 1         | 1.37%   |
| Intel Core 2 Duo CPU T9900 @ 3.06GHz                          | 1         | 1.37%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz                          | 1         | 1.37%   |
| Intel Core 2 Duo CPU P9700 @ 2.80GHz                          | 1         | 1.37%   |
| Intel Celeron N4020 CPU @ 1.10GHz                             | 1         | 1.37%   |
| Intel Celeron M CPU 430 @ 1.73GHz ("GenuineIntel" 686-class)  | 1         | 1.37%   |
| Intel Celeron D CPU 3.20GHz                                   | 1         | 1.37%   |
| Intel Celeron CPU N3350 @ 1.10GHz                             | 1         | 1.37%   |
| Intel Celeron CPU N2840 @ 2.16GHz                             | 1         | 1.37%   |
| Intel Celeron CPU 3865U @ 1.80GHz                             | 1         | 1.37%   |
| Intel Atom CPU Z530 @ 1.60GHz ("GenuineIntel" 686-class)      | 1         | 1.37%   |
| Intel Atom CPU N280 @ 1.66GHz ("GenuineIntel" 686-class)      | 1         | 1.37%   |
| Intel Atom CPU C3558 @ 2.20GHz                                | 1         | 1.37%   |
| Intel 11th Gen Core i5-11600K @ 3.90GHz                       | 1         | 1.37%   |
| AMD Ryzen 7 5800X 8-Core Processor                            | 1         | 1.37%   |
| AMD Ryzen 7 5700G with Radeon Graphics                        | 1         | 1.37%   |
| AMD Ryzen 7 4800H with Radeon Graphics                        | 1         | 1.37%   |
| AMD Ryzen 7 3700X 8-Core Processor                            | 1         | 1.37%   |
| AMD Ryzen 5 PRO 4650U with Radeon Graphics                    | 1         | 1.37%   |
| AMD Ryzen 5 4600H with Radeon Graphics                        | 1         | 1.37%   |
| AMD GX-412TC SOC                                              | 1         | 1.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 17        | 23.29%  |
| Intel Core i7        | 8         | 10.96%  |
| Intel Xeon           | 7         | 9.59%   |
| Intel Core i3        | 6         | 8.22%   |
| Intel Atom           | 6         | 8.22%   |
| Intel Celeron        | 4         | 5.48%   |
| AMD Ryzen 7          | 4         | 5.48%   |
| Other                | 3         | 4.11%   |
| Intel Core 2 Duo     | 3         | 4.11%   |
| ARM Cortex           | 2         | 2.74%   |
| Intel Pentium Silver | 1         | 1.37%   |
| Intel Pentium M      | 1         | 1.37%   |
| Intel Pentium 4      | 1         | 1.37%   |
| Intel Pentium        | 1         | 1.37%   |
| Intel Core Duo       | 1         | 1.37%   |
| Intel Celeron M      | 1         | 1.37%   |
| Intel Celeron D      | 1         | 1.37%   |
| AMD Ryzen 5 PRO      | 1         | 1.37%   |
| AMD Ryzen 5          | 1         | 1.37%   |
| AMD GX               | 1         | 1.37%   |
| AMD G                | 1         | 1.37%   |
| AMD Athlon XP        | 1         | 1.37%   |
| AMD Athlon II Neo    | 1         | 1.37%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 27        | 36.99%  |
| 4       | 17        | 23.29%  |
| Unknown | 13        | 17.81%  |
| 6       | 5         | 6.85%   |
| 1       | 5         | 6.85%   |
| 16      | 4         | 5.48%   |
| 12      | 2         | 2.74%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 56        | 76.71%  |
| Unknown | 17        | 23.29%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 35        | 47.95%  |
| 1       | 21        | 28.77%  |
| Unknown | 17        | 23.29%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 11        | 15.07%  |
| IvyBridge     | 7         | 9.59%   |
| SandyBridge   | 6         | 8.22%   |
| Unknown       | 6         | 8.22%   |
| Bonnell       | 5         | 6.85%   |
| Zen 2         | 4         | 5.48%   |
| Westmere      | 4         | 5.48%   |
| Haswell       | 4         | 5.48%   |
| Penryn        | 3         | 4.11%   |
| P6            | 3         | 4.11%   |
| Goldmont      | 3         | 4.11%   |
| Broadwell     | 3         | 4.11%   |
| Zen 3         | 2         | 2.74%   |
| Skylake       | 2         | 2.74%   |
| Goldmont plus | 2         | 2.74%   |
| Silvermont    | 1         | 1.37%   |
| Puma          | 1         | 1.37%   |
| NetBurst      | 1         | 1.37%   |
| Nehalem       | 1         | 1.37%   |
| K6            | 1         | 1.37%   |
| K10           | 1         | 1.37%   |
| IceLake       | 1         | 1.37%   |
| Bobcat        | 1         | 1.37%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 48        | 63.16%  |
| AMD                        | 15        | 19.74%  |
| Nvidia                     | 5         | 6.58%   |
| Matrox Electronics Systems | 4         | 5.26%   |
| ASPEED Technology          | 4         | 5.26%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                              | Computers | Percent |
|------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller      | 7         | 8.33%   |
| Intel 3rd Gen Core processor Graphics Controller                                   | 7         | 8.33%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                         | 5         | 5.95%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller          | 5         | 5.95%   |
| ASPEED Technology ASPEED Graphics Family                                           | 4         | 4.76%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                         | 3         | 3.57%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                       | 3         | 3.57%   |
| Intel Core Processor Integrated Graphics Controller                                | 3         | 3.57%   |
| AMD Renoir                                                                         | 3         | 3.57%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                      | 2         | 2.38%   |
| Matrox Electronics Systems MGA G200EH                                              | 2         | 2.38%   |
| Intel UHD Graphics 620                                                             | 2         | 2.38%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller          | 2         | 2.38%   |
| Intel HD Graphics 620                                                              | 2         | 2.38%   |
| Intel HD Graphics 5500                                                             | 2         | 2.38%   |
| Intel Haswell-ULT Integrated Graphics Controller                                   | 2         | 2.38%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                                | 2         | 2.38%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                            | 2         | 2.38%   |
| Nvidia TU117M                                                                      | 1         | 1.19%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                             | 1         | 1.19%   |
| Nvidia GP108M [GeForce MX330]                                                      | 1         | 1.19%   |
| Nvidia GP108M [GeForce MX150]                                                      | 1         | 1.19%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                            | 1         | 1.19%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                | 1         | 1.19%   |
| Intel Skylake GT2 [HD Graphics 520]                                                | 1         | 1.19%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                               | 1         | 1.19%   |
| Intel Iris Plus Graphics G4 (Ice Lake)                                             | 1         | 1.19%   |
| Intel HD Graphics 500                                                              | 1         | 1.19%   |
| Intel GeminiLake [UHD Graphics 605]                                                | 1         | 1.19%   |
| Intel GeminiLake [UHD Graphics 600]                                                | 1         | 1.19%   |
| Intel CometLake-U GT2 [UHD Graphics]                                               | 1         | 1.19%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                           | 1         | 1.19%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                          | 1         | 1.19%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller | 1         | 1.19%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                       | 1         | 1.19%   |
| AMD RV350/M10 / RV360/M11 [Mobility Radeon 9600 (PRO) / 9700]                      | 1         | 1.19%   |
| AMD RV280 [Radeon 9200 PRO] (Secondary)                                            | 1         | 1.19%   |
| AMD RV280 [Radeon 9200 PRO / 9250]                                                 | 1         | 1.19%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                          | 1         | 1.19%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                   | 1         | 1.19%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                         | 1         | 1.19%   |
| AMD ES1000                                                                         | 1         | 1.19%   |
| AMD Cezanne                                                                        | 1         | 1.19%   |
| AMD Caicos PRO [Radeon HD 7450]                                                    | 1         | 1.19%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 33        | 45.21%  |
| 2 x Intel      | 10        | 13.7%   |
| 1 x AMD        | 10        | 13.7%   |
| Other          | 4         | 5.48%   |
| 1 x ASPEED     | 4         | 5.48%   |
| 1 x Matrox     | 3         | 4.11%   |
| Intel + Nvidia | 3         | 4.11%   |
| Intel + AMD    | 2         | 2.74%   |
| 2 x AMD        | 1         | 1.37%   |
| 1 x Nvidia     | 1         | 1.37%   |
| AMD + Nvidia   | 1         | 1.37%   |
| AMD + Matrox   | 1         | 1.37%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 61        | 83.56%  |
| Unknown | 12        | 16.44%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 73        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 10        | 24.39%  |
| LG Display              | 5         | 12.2%   |
| BOE                     | 4         | 9.76%   |
| Lenovo                  | 3         | 7.32%   |
| Sharp                   | 2         | 4.88%   |
| Samsung Electronics     | 2         | 4.88%   |
| Dell                    | 2         | 4.88%   |
| Chimei Innolux          | 2         | 4.88%   |
| Apple                   | 2         | 4.88%   |
| Vizio                   | 1         | 2.44%   |
| Philips                 | 1         | 2.44%   |
| LG Philips              | 1         | 2.44%   |
| InfoVision              | 1         | 2.44%   |
| Goldstar                | 1         | 2.44%   |
| Eizo                    | 1         | 2.44%   |
| Chi Mei Optoelectronics | 1         | 2.44%   |
| AOC                     | 1         | 2.44%   |
| Ancor Communications    | 1         | 2.44%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 2         | 4.88%   |
| Vizio E320i-A0 VIZ0091 1366x768 700x390mm 31.5-inch                      | 1         | 2.44%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 340x190mm 15.3-inch                  | 1         | 2.44%   |
| Sharp LCD Monitor SHP1449 1920x1080 290x170mm 13.2-inch                  | 1         | 2.44%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch     | 1         | 2.44%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 310x170mm 13.9-inch     | 1         | 2.44%   |
| Philips PHL 276E8V PHLC18F 3840x2160 600x340mm 27.2-inch                 | 1         | 2.44%   |
| LG Philips LCD Monitor LPLDB00 1280x800 330x210mm 15.4-inch              | 1         | 2.44%   |
| LG Display LCD Monitor LGD05D8 1920x1080 340x190mm 15.3-inch             | 1         | 2.44%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x170mm 12.2-inch             | 1         | 2.44%   |
| LG Display LCD Monitor LGD0450 1366x768 280x160mm 12.7-inch              | 1         | 2.44%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x170mm 13.9-inch              | 1         | 2.44%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 1         | 2.44%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch                  | 1         | 2.44%   |
| Lenovo LCD Monitor LEN4033 1440x900 300x190mm 14.0-inch                  | 1         | 2.44%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch                  | 1         | 2.44%   |
| InfoVision M116NWR1 R0  IVO0489 1366x768 260x140mm 11.6-inch             | 1         | 2.44%   |
| Goldstar L1715S GSM436F 1280x1024 340x270mm 17.1-inch                    | 1         | 2.44%   |
| Eizo EV2450 ENC2530 1920x1080 530x300mm 24.0-inch                        | 1         | 2.44%   |
| Dell U2715H DELD065 2560x1440 600x340mm 27.2-inch                        | 1         | 2.44%   |
| Dell P2317H DEL40F3 1920x1080 480x270mm 21.7-inch                        | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 340x190mm 15.3-inch         | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch          | 1         | 2.44%   |
| Chi Mei Optoelectronics LCD Monitor CMO1107 1366x768 250x140mm 11.3-inch | 1         | 2.44%   |
| BOE LCD Monitor BOE0817 1366x768 340x190mm 15.3-inch                     | 1         | 2.44%   |
| BOE LCD Monitor BOE07C8 3840x2160 310x170mm 13.9-inch                    | 1         | 2.44%   |
| BOE LCD Monitor BOE0731 1366x768 260x140mm 11.6-inch                     | 1         | 2.44%   |
| BOE LCD Monitor BOE0718 1920x1080 310x170mm 13.9-inch                    | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO5F2D 1920x1080 290x170mm 13.2-inch           | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 310x170mm 13.9-inch           | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 340x190mm 15.3-inch            | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch            | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch            | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO235C 1366x768 260x140mm 11.6-inch            | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch           | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO11C2 1024x600 200x110mm 9.0-inch             | 1         | 2.44%   |
| Apple Color LCD APP9CDF 1440x900 290x180mm 13.4-inch                     | 1         | 2.44%   |
| Apple Color LCD APP9C20 1280x854 320x220mm 15.3-inch                     | 1         | 2.44%   |
| AOC 2270W AOC2270 1920x1080 480x270mm 21.7-inch                          | 1         | 2.44%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 520x290mm 23.4-inch    | 1         | 2.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 15        | 37.5%   |
| 1920x1080 (FHD)  | 11        | 27.5%   |
| 1440x900 (WXGA+) | 3         | 7.5%    |
| 3840x2160 (4K)   | 2         | 5%      |
| 1600x900 (HD+)   | 2         | 5%      |
| 1280x800 (WXGA)  | 2         | 5%      |
| 2736x1824        | 1         | 2.5%    |
| 2560x1440 (QHD)  | 1         | 2.5%    |
| 1280x854         | 1         | 2.5%    |
| 1280x1024 (SXGA) | 1         | 2.5%    |
| 1024x600         | 1         | 2.5%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 13     | 10        | 24.39%  |
| 15     | 7         | 17.07%  |
| 12     | 6         | 14.63%  |
| 11     | 6         | 14.63%  |
| 14     | 3         | 7.32%   |
| 27     | 2         | 4.88%   |
| 21     | 2         | 4.88%   |
| 31     | 1         | 2.44%   |
| 24     | 1         | 2.44%   |
| 23     | 1         | 2.44%   |
| 17     | 1         | 2.44%   |
| 9      | 1         | 2.44%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 201-300     | 18        | 43.9%   |
| 301-350     | 15        | 36.59%  |
| 501-600     | 4         | 9.76%   |
| 401-500     | 2         | 4.88%   |
| 601-700     | 1         | 2.44%   |
| 101-200     | 1         | 2.44%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 32        | 80%     |
| 16/10 | 5         | 12.5%   |
| 3/2   | 2         | 5%      |
| 5/4   | 1         | 2.5%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 11        | 26.83%  |
| 61-70          | 6         | 14.63%  |
| 51-60          | 6         | 14.63%  |
| 91-100         | 5         | 12.2%   |
| 201-250        | 4         | 9.76%   |
| 71-80          | 2         | 4.88%   |
| 301-350        | 2         | 4.88%   |
| 101-110        | 2         | 4.88%   |
| 351-500        | 1         | 2.44%   |
| 1-40           | 1         | 2.44%   |
| 141-150        | 1         | 2.44%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 21        | 51.22%  |
| 101-120       | 9         | 21.95%  |
| 161-240       | 4         | 9.76%   |
| 51-100        | 4         | 9.76%   |
| More than 240 | 2         | 4.88%   |
| 1-50          | 1         | 2.44%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 52        | 71.23%  |
| 0     | 20        | 27.4%   |
| 2     | 1         | 1.37%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 51        | 52.58%  |
| Realtek Semiconductor    | 23        | 23.71%  |
| Qualcomm Atheros         | 9         | 9.28%   |
| Broadcom                 | 5         | 5.15%   |
| Marvell Technology Group | 2         | 2.06%   |
| Xiaomi                   | 1         | 1.03%   |
| Ralink Technology        | 1         | 1.03%   |
| Ralink                   | 1         | 1.03%   |
| Micro Star International | 1         | 1.03%   |
| Fibocom                  | 1         | 1.03%   |
| Edimax Technology        | 1         | 1.03%   |
| Apple                    | 1         | 1.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 15        | 12%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 7         | 5.6%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 4.8%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 4         | 3.2%    |
| Intel Wireless 8265 / 8275                                              | 4         | 3.2%    |
| Intel Wi-Fi 6 AX200                                                     | 4         | 3.2%    |
| Intel I210 Gigabit Network Connection                                   | 3         | 2.4%    |
| Intel 82567LM Gigabit Network Connection                                | 3         | 2.4%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 2         | 1.6%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 1.6%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 1.6%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 2         | 1.6%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.6%    |
| Intel Wireless 7265                                                     | 2         | 1.6%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 1.6%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 1.6%    |
| Intel I350 Gigabit Network Connection                                   | 2         | 1.6%    |
| Intel I211 Gigabit Network Connection                                   | 2         | 1.6%    |
| Intel Ethernet Connection I219-LM                                       | 2         | 1.6%    |
| Intel Centrino Wireless-N 2200                                          | 2         | 1.6%    |
| Intel Centrino Advanced-N 6200                                          | 2         | 1.6%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.6%    |
| Intel 82577LM Gigabit Network Connection                                | 2         | 1.6%    |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 0.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.8%    |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.8%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 0.8%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.8%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                        | 1         | 0.8%    |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.8%    |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                               | 1         | 0.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 0.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 0.8%    |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 1         | 0.8%    |
| Micro Star International RT2573                                         | 1         | 0.8%    |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                 | 1         | 0.8%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                 | 1         | 0.8%    |
| Intel Wireless-AC 9260                                                  | 1         | 0.8%    |
| Intel Wireless 8260                                                     | 1         | 0.8%    |
| Intel Wireless 3160                                                     | 1         | 0.8%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 0.8%    |
| Intel Ethernet Controller I225-V                                        | 1         | 0.8%    |
| Intel Ethernet Controller 10-Gigabit X540-AT2                           | 1         | 0.8%    |
| Intel Ethernet Connection X553 1GbE                                     | 1         | 0.8%    |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                        | 1         | 0.8%    |
| Intel Ethernet Connection (7) I219-LM                                   | 1         | 0.8%    |
| Intel Ethernet Connection (6) I219-V                                    | 1         | 0.8%    |
| Intel Ethernet Connection (4) I219-V                                    | 1         | 0.8%    |
| Intel Ethernet Connection (3) I218-LM                                   | 1         | 0.8%    |
| Intel Ethernet Connection (14) I219-V                                   | 1         | 0.8%    |
| Intel Ethernet Connection (10) I219-V                                   | 1         | 0.8%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 0.8%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 0.8%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 0.8%    |
| Intel Centrino Wireless-N 2230                                          | 1         | 0.8%    |
| Intel Centrino Advanced-N 6235                                          | 1         | 0.8%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1         | 0.8%    |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 1         | 0.8%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                    | 1         | 0.8%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 36        | 64.29%  |
| Qualcomm Atheros         | 9         | 16.07%  |
| Realtek Semiconductor    | 5         | 8.93%   |
| Broadcom                 | 2         | 3.57%   |
| Ralink Technology        | 1         | 1.79%   |
| Ralink                   | 1         | 1.79%   |
| Micro Star International | 1         | 1.79%   |
| Edimax Technology        | 1         | 1.79%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 10.71%  |
| Intel Wireless 8265 / 8275                                              | 4         | 7.14%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 7.14%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 3.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 3.57%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 3.57%   |
| Intel Wireless 7265                                                     | 2         | 3.57%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 3.57%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 3.57%   |
| Intel Centrino Wireless-N 2200                                          | 2         | 3.57%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 3.57%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 3.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.79%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.79%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 1.79%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 1.79%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.79%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 1.79%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                               | 1         | 1.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 1.79%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 1         | 1.79%   |
| Micro Star International RT2573                                         | 1         | 1.79%   |
| Intel Wireless-AC 9260                                                  | 1         | 1.79%   |
| Intel Wireless 8260                                                     | 1         | 1.79%   |
| Intel Wireless 3160                                                     | 1         | 1.79%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 1.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 1.79%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 1.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 1.79%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 1.79%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 1.79%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1         | 1.79%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 1         | 1.79%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 1         | 1.79%   |
| Broadcom BCM4306 802.11b/g Wireless LAN Controller                      | 1         | 1.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 34        | 52.31%  |
| Realtek Semiconductor    | 22        | 33.85%  |
| Broadcom                 | 3         | 4.62%   |
| Qualcomm Atheros         | 2         | 3.08%   |
| Marvell Technology Group | 2         | 3.08%   |
| Xiaomi                   | 1         | 1.54%   |
| Apple                    | 1         | 1.54%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 15        | 22.39%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 7         | 10.45%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 4         | 5.97%   |
| Intel I210 Gigabit Network Connection                                | 3         | 4.48%   |
| Intel 82567LM Gigabit Network Connection                             | 3         | 4.48%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                | 2         | 2.99%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet       | 2         | 2.99%   |
| Intel I350 Gigabit Network Connection                                | 2         | 2.99%   |
| Intel I211 Gigabit Network Connection                                | 2         | 2.99%   |
| Intel Ethernet Connection I219-LM                                    | 2         | 2.99%   |
| Intel 82577LM Gigabit Network Connection                             | 2         | 2.99%   |
| Xiaomi Mi/Redmi series (RNDIS)                                       | 1         | 1.49%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                     | 1         | 1.49%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller              | 1         | 1.49%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller              | 1         | 1.49%   |
| Intel Ethernet Controller I225-V                                     | 1         | 1.49%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                        | 1         | 1.49%   |
| Intel Ethernet Connection X553 1GbE                                  | 1         | 1.49%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                     | 1         | 1.49%   |
| Intel Ethernet Connection (7) I219-LM                                | 1         | 1.49%   |
| Intel Ethernet Connection (6) I219-V                                 | 1         | 1.49%   |
| Intel Ethernet Connection (4) I219-V                                 | 1         | 1.49%   |
| Intel Ethernet Connection (3) I218-LM                                | 1         | 1.49%   |
| Intel Ethernet Connection (14) I219-V                                | 1         | 1.49%   |
| Intel Ethernet Connection (10) I219-V                                | 1         | 1.49%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                 | 1         | 1.49%   |
| Intel 82576 Gigabit Network Connection                               | 1         | 1.49%   |
| Intel 82574L Gigabit Network Connection                              | 1         | 1.49%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller Mobile | 1         | 1.49%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                   | 1         | 1.49%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                     | 1         | 1.49%   |
| Broadcom NetXtreme BCM5714 Gigabit Ethernet                          | 1         | 1.49%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                      | 1         | 1.49%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                      | 1         | 1.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 62        | 52.54%  |
| WiFi     | 54        | 45.76%  |
| Modem    | 1         | 0.85%   |
| Unknown  | 1         | 0.85%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 38        | 55.88%  |
| Ethernet | 30        | 44.12%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 46        | 63.01%  |
| 1     | 18        | 24.66%  |
| 3     | 4         | 5.48%   |
| 4     | 2         | 2.74%   |
| 12    | 1         | 1.37%   |
| 7     | 1         | 1.37%   |
| 0     | 1         | 1.37%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 73        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 17        | 53.13%  |
| Broadcom                        | 3         | 9.38%   |
| Alps Electric                   | 3         | 9.38%   |
| Realtek Semiconductor           | 2         | 6.25%   |
| Qualcomm Atheros Communications | 2         | 6.25%   |
| ASUSTek Computer                | 2         | 6.25%   |
| Creative Technology             | 1         | 3.13%   |
| Cambridge Silicon Radio         | 1         | 3.13%   |
| Apple                           | 1         | 3.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 5         | 15.63%  |
| Intel AX200 Bluetooth                               | 4         | 12.5%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 6.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 6.25%   |
| Intel AX201 Bluetooth                               | 2         | 6.25%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 6.25%   |
| Alps Electric UGTZ4 Bluetooth                       | 2         | 6.25%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 3.13%   |
| Realtek  Bluetooth 4.0 Adapter                      | 1         | 3.13%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1             | 1         | 3.13%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 3.13%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 3.13%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 3.13%   |
| Creative Creative Bluetooth Audio W2                | 1         | 3.13%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.13%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 3.13%   |
| ASUS Broadcom Bluetooth 2.1                         | 1         | 3.13%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 3.13%   |
| Apple Apple Broadcom Built-in Bluetooth             | 1         | 3.13%   |
| Alps Electric BCM2046 Bluetooth Device              | 1         | 3.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 51        | 77.27%  |
| AMD                    | 9         | 13.64%  |
| Nvidia                 | 2         | 3.03%   |
| VIA Technologies       | 1         | 1.52%   |
| JMTek                  | 1         | 1.52%   |
| Generalplus Technology | 1         | 1.52%   |
| Creative Labs          | 1         | 1.52%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 8         | 10.67%  |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 7         | 9.33%   |
| Intel Sunrise Point-LP HD Audio                                                   | 6         | 8%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 4         | 5.33%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                               | 4         | 5.33%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 3         | 4%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 3         | 4%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 3         | 4%      |
| AMD Renoir Radeon High Definition Audio Controller                                | 3         | 4%      |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 2         | 2.67%   |
| Intel Haswell-ULT HD Audio Controller                                             | 2         | 2.67%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 2         | 2.67%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                 | 2         | 2.67%   |
| Intel Cannon Lake PCH cAVS                                                        | 2         | 2.67%   |
| Intel Broadwell-U Audio Controller                                                | 2         | 2.67%   |
| Intel 8 Series HD Audio Controller                                                | 2         | 2.67%   |
| AMD Starship/Matisse HD Audio Controller                                          | 2         | 2.67%   |
| AMD Navi 10 HDMI Audio                                                            | 2         | 2.67%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                         | 1         | 1.33%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1         | 1.33%   |
| Nvidia TU104 HD Audio Controller                                                  | 1         | 1.33%   |
| JMTek USB PnP Audio Device                                                        | 1         | 1.33%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                   | 1         | 1.33%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 1         | 1.33%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                         | 1         | 1.33%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 1         | 1.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 1         | 1.33%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                 | 1         | 1.33%   |
| Intel 82801CA/CAM AC'97 Audio Controller                                          | 1         | 1.33%   |
| Generalplus Technology USB Audio Device                                           | 1         | 1.33%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                     | 1         | 1.33%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 1         | 1.33%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                      | 1         | 1.33%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1         | 1.33%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 4         | 28.57%  |
| Samsung Electronics | 4         | 28.57%  |
| SK Hynix            | 3         | 21.43%  |
| Micron Technology   | 1         | 7.14%   |
| Kingston            | 1         | 7.14%   |
| Elpida              | 1         | 7.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s              | 2         | 11.11%  |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s   | 2         | 11.11%  |
| Unknown RAM Module 512MB DIMM 400MT/s                    | 1         | 5.56%   |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s              | 1         | 5.56%   |
| Unknown RAM Module 256MB DIMM 333MT/s                    | 1         | 5.56%   |
| Unknown RAM Module 1GB DIMM 400MT/s                      | 1         | 5.56%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 1         | 5.56%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM 1066MT/s         | 1         | 5.56%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 1067MT/s    | 1         | 5.56%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s    | 1         | 5.56%   |
| Samsung RAM M471B5173BH0-CK0 4096MB SODIMM DDR3 1600MT/s | 1         | 5.56%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s   | 1         | 5.56%   |
| Micron RAM 8JSF12864HZ-1G1F1 1GB SODIMM DDR3 800MT/s     | 1         | 5.56%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 2400MT/s      | 1         | 5.56%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s        | 1         | 5.56%   |
| Elpida RAM Module 1GB SODIMM DDR2 533MT/s                | 1         | 5.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 8         | 66.67%  |
| DDR4    | 2         | 16.67%  |
| DDR2    | 1         | 8.33%   |
| Unknown | 1         | 8.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 10        | 83.33%  |
| DIMM   | 2         | 16.67%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 7         | 43.75%  |
| 1024  | 3         | 18.75%  |
| 2048  | 2         | 12.5%   |
| 16384 | 1         | 6.25%   |
| 8192  | 1         | 6.25%   |
| 512   | 1         | 6.25%   |
| 256   | 1         | 6.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 3         | 20%     |
| 1333  | 2         | 13.33%  |
| 1067  | 2         | 13.33%  |
| 3200  | 1         | 6.67%   |
| 2400  | 1         | 6.67%   |
| 1334  | 1         | 6.67%   |
| 1066  | 1         | 6.67%   |
| 800   | 1         | 6.67%   |
| 533   | 1         | 6.67%   |
| 400   | 1         | 6.67%   |
| 333   | 1         | 6.67%   |

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


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Chicony Electronics   | 11        | 35.48%  |
| Acer                  | 6         | 19.35%  |
| IMC Networks          | 3         | 9.68%   |
| Quanta                | 2         | 6.45%   |
| Microdia              | 2         | 6.45%   |
| Syntek                | 1         | 3.23%   |
| Suyin                 | 1         | 3.23%   |
| Silicon Motion        | 1         | 3.23%   |
| Ricoh                 | 1         | 3.23%   |
| Realtek Semiconductor | 1         | 3.23%   |
| Lite-On Technology    | 1         | 3.23%   |
| Lenovo                | 1         | 3.23%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 3         | 9.68%   |
| Chicony Ltd., VGA Webcam                 | 2         | 6.45%   |
| Acer Integrated Camera                   | 2         | 6.45%   |
| Acer EasyCamera                          | 2         | 6.45%   |
| Syntek Lenovo EasyCamera                 | 1         | 3.23%   |
| Suyin Acer/Lenovo Webcam [CN0316]        | 1         | 3.23%   |
| Silicon Motion Realtek USB2.0 PC Camera  | 1         | 3.23%   |
| Ricoh Sony Visual Communication Camera   | 1         | 3.23%   |
| Realtek Integrated_Webcam_HD             | 1         | 3.23%   |
| Quanta HP Webcam-50                      | 1         | 3.23%   |
| Quanta HP TrueVision HD Camera           | 1         | 3.23%   |
| Microdia Sonix USB 2.0 Camera            | 1         | 3.23%   |
| Microdia Integrated Webcam HD            | 1         | 3.23%   |
| Lite-On Integrated Camera                | 1         | 3.23%   |
| Lenovo Integrated Webcam                 | 1         | 3.23%   |
| IMC Networks USB2.0 HD UVC WebCam        | 1         | 3.23%   |
| IMC Networks Lenovo EasyCamera           | 1         | 3.23%   |
| IMC Networks Integrated Camera           | 1         | 3.23%   |
| Chicony thinkpad t430s camera            | 1         | 3.23%   |
| Chicony Ltd., Integrated Camera          | 1         | 3.23%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 1         | 3.23%   |
| Chicony Integrated Camera [ThinkPad]     | 1         | 3.23%   |
| Chicony HD Webcam                        | 1         | 3.23%   |
| Chicony 2.0M UVC Webcam / CNF7129        | 1         | 3.23%   |
| Acer SunplusIT Integrated Camera         | 1         | 3.23%   |
| Acer Lenovo Integrated Webcam            | 1         | 3.23%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Synaptics             | 4         | 50%     |
| Upek                  | 2         | 25%     |
| Elan Microelectronics | 1         | 12.5%   |
| AuthenTec             | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 25%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 25%     |
| Synaptics product 0x00be                               | 1         | 12.5%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 12.5%   |
| Elan ELAN WBF Fingerprint Sensor                       | 1         | 12.5%   |
| AuthenTec AES2810                                      | 1         | 12.5%   |

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
| 1     | 33        | 45.21%  |
| 2     | 20        | 27.4%   |
| 0     | 14        | 19.18%  |
| 4     | 2         | 2.74%   |
| 3     | 2         | 2.74%   |
| 6     | 1         | 1.37%   |
| 5     | 1         | 1.37%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 42        | 46.67%  |
| Graphics card            | 23        | 25.56%  |
| Firewire controller      | 8         | 8.89%   |
| Net/wireless             | 6         | 6.67%   |
| Storage/ata              | 3         | 3.33%   |
| Net/ethernet             | 3         | 3.33%   |
| Sound                    | 2         | 2.22%   |
| Storage/ide              | 1         | 1.11%   |
| Network                  | 1         | 1.11%   |
| Modem                    | 1         | 1.11%   |

