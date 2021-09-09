OpenBSD 6.9 - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for OpenBSD 6.9.

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
| PC Engines    | apu4                        | Desktop     | [9557835b54](https://bsd-hardware.info/?probe=9557835b54) | Sep 09, 2021 |
| Apple         | MacBookPro6,2               | Notebook    | [4632683b4b](https://bsd-hardware.info/?probe=4632683b4b) | Sep 08, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [f860e13b6b](https://bsd-hardware.info/?probe=f860e13b6b) | Sep 08, 2021 |
| Lenovo        | ThinkPad X250 20CM0046US    | Notebook    | [1ed50b75f1](https://bsd-hardware.info/?probe=1ed50b75f1) | Sep 08, 2021 |
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
| amd64  | 63        | 81.82%  |
| i386   | 11        | 14.29%  |
| arm64  | 2         | 2.6%    |
| macppc | 1         | 1.3%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| fvwm    | 60        | 77.92%  |
| Console | 16        | 20.78%  |
| i3      | 1         | 1.3%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 59        | 76.62%  |
| Console | 18        | 23.38%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 68        | 88.31%  |
| SLiM    | 9         | 11.69%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 60        | 77.92%  |
| en_US   | 12        | 15.58%  |
| ru_RU   | 3         | 3.9%    |
| en_EN   | 1         | 1.3%    |
| C       | 1         | 1.3%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 43        | 55.13%  |
| BIOS | 35        | 44.87%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ffs  | 77        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 40        | 51.28%  |
| MBR  | 38        | 48.72%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 23        | 29.87%  |
| Hewlett-Packard                | 9         | 11.69%  |
| ASUSTek Computer               | 6         | 7.79%   |
| Supermicro                     | 5         | 6.49%   |
| Acer                           | 5         | 6.49%   |
| PC Engines                     | 3         | 3.9%    |
| Apple                          | 3         | 3.9%    |
| Unknown                        | 3         | 3.9%    |
| Panasonic                      | 2         | 2.6%    |
| Matsushita Electric Industrial | 2         | 2.6%    |
| Gigabyte Technology            | 2         | 2.6%    |
| Dell                           | 2         | 2.6%    |
| ASRock                         | 2         | 2.6%    |
| Standard                       | 1         | 1.3%    |
| Sony                           | 1         | 1.3%    |
| Shuttle                        | 1         | 1.3%    |
| Samsung Electronics            | 1         | 1.3%    |
| MSI                            | 1         | 1.3%    |
| Microsoft                      | 1         | 1.3%    |
| IBM                            | 1         | 1.3%    |
| Foxconn                        | 1         | 1.3%    |
| Clevo                          | 1         | 1.3%    |
| Alienware                      | 1         | 1.3%    |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 3         | 3.9%    |
| Supermicro Super Server                     | 2         | 2.6%    |
| Supermicro X8STi                            | 1         | 1.3%    |
| Supermicro X8DTH-i/6/iF/6F                  | 1         | 1.3%    |
| Supermicro X10SLH-N6-ST031                  | 1         | 1.3%    |
| Standard TF                                 | 1         | 1.3%    |
| Sony VGN-P698E                              | 1         | 1.3%    |
| Shuttle DS77U                               | 1         | 1.3%    |
| Samsung 3570R/370R/470R/450R/510R/4450RV    | 1         | 1.3%    |
| PC Engines apu4                             | 1         | 1.3%    |
| PC Engines APU2                             | 1         | 1.3%    |
| PC Engines apu1                             | 1         | 1.3%    |
| Panasonic CF-53AAGHYDM                      | 1         | 1.3%    |
| Panasonic CF-52PFPBSFQ                      | 1         | 1.3%    |
| MSI MS-1613                                 | 1         | 1.3%    |
| Microsoft Surface Pro 7                     | 1         | 1.3%    |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 1.3%    |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 1.3%    |
| Lenovo Yoga 6 13ARE05 82FN                  | 1         | 1.3%    |
| Lenovo Yoga 330-11IGM 81A6                  | 1         | 1.3%    |
| Lenovo ThinkPad X280 20KESA000B             | 1         | 1.3%    |
| Lenovo ThinkPad X270 20HNA006ID             | 1         | 1.3%    |
| Lenovo ThinkPad X250 20CM0046US             | 1         | 1.3%    |
| Lenovo ThinkPad X250 20CLS7WY04             | 1         | 1.3%    |
| Lenovo ThinkPad X230 232578G                | 1         | 1.3%    |
| Lenovo ThinkPad X220 4291ON5                | 1         | 1.3%    |
| Lenovo ThinkPad X1 Carbon 7th 20QD00KTMH    | 1         | 1.3%    |
| Lenovo ThinkPad T430 23511A6                | 1         | 1.3%    |
| Lenovo ThinkPad T430 2349U2B                | 1         | 1.3%    |
| Lenovo ThinkPad T430 2347GZU                | 1         | 1.3%    |
| Lenovo ThinkPad T420 4236MBG                | 1         | 1.3%    |
| Lenovo ThinkPad T410 2537N24                | 1         | 1.3%    |
| Lenovo ThinkPad T400 6475P1G                | 1         | 1.3%    |
| Lenovo ThinkPad T400 6475K43                | 1         | 1.3%    |
| Lenovo ThinkPad T400 2767WSB                | 1         | 1.3%    |
| Lenovo ThinkPad T14 Gen 1 20S1S07800        | 1         | 1.3%    |
| Lenovo ThinkPad Edge 05796AU                | 1         | 1.3%    |
| Lenovo ThinkPad E490 20N8CTO1WW             | 1         | 1.3%    |
| Lenovo IdeaPad S210 Touch 20257             | 1         | 1.3%    |
| Lenovo IdeaPad 1 11IGL05 81VT               | 1         | 1.3%    |
| Lenovo FLEX 3-1120 80LX                     | 1         | 1.3%    |
| IBM ThinkPad T42 2374K46                    | 1         | 1.3%    |
| HP ProLiant DL360e Gen8                     | 1         | 1.3%    |
| HP ProLiant DL360 Gen9                      | 1         | 1.3%    |
| HP ProLiant DL320 G5                        | 1         | 1.3%    |
| HP ProBook 450 G2                           | 1         | 1.3%    |
| HP Pavilion Gaming Laptop 15-ec1xxx         | 1         | 1.3%    |
| HP Pavilion dm1                             | 1         | 1.3%    |
| HP Notebook                                 | 1         | 1.3%    |
| HP EliteDesk 800 G5 SFF                     | 1         | 1.3%    |
| HP 530 Notebook PC(KP477AA#ACB)             | 1         | 1.3%    |
| Gigabyte GA-7VT600                          | 1         | 1.3%    |
| Gigabyte B550I AORUS PRO AX                 | 1         | 1.3%    |
| Foxconn AT-7000 Series                      | 1         | 1.3%    |
| Dell XPS 13 9360                            | 1         | 1.3%    |
| Dell Latitude E7270                         | 1         | 1.3%    |
| Clevo W240EU/W250EUQ/W270EUQ                | 1         | 1.3%    |
| ASUS UX430UNR                               | 1         | 1.3%    |
| ASUS ROG STRIX B550-I GAMING                | 1         | 1.3%    |
| ASUS PRIME B560M-A                          | 1         | 1.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad                             | 18        | 23.38%  |
| HP ProLiant                                 | 3         | 3.9%    |
| Unknown                                     | 3         | 3.9%    |
| Supermicro Super                            | 2         | 2.6%    |
| Lenovo Yoga                                 | 2         | 2.6%    |
| Lenovo IdeaPad                              | 2         | 2.6%    |
| HP Pavilion                                 | 2         | 2.6%    |
| Supermicro X8STi                            | 1         | 1.3%    |
| Supermicro X8DTH-i                          | 1         | 1.3%    |
| Supermicro X10SLH-N6-ST031                  | 1         | 1.3%    |
| Standard TF                                 | 1         | 1.3%    |
| Sony VGN-P698E                              | 1         | 1.3%    |
| Shuttle DS77U                               | 1         | 1.3%    |
| Samsung 3570R                               | 1         | 1.3%    |
| PC Engines apu4                             | 1         | 1.3%    |
| PC Engines APU2                             | 1         | 1.3%    |
| PC Engines apu1                             | 1         | 1.3%    |
| Panasonic CF-53AAGHYDM                      | 1         | 1.3%    |
| Panasonic CF-52PFPBSFQ                      | 1         | 1.3%    |
| MSI MS-1613                                 | 1         | 1.3%    |
| Microsoft Surface                           | 1         | 1.3%    |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 1.3%    |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 1.3%    |
| Lenovo FLEX                                 | 1         | 1.3%    |
| IBM ThinkPad                                | 1         | 1.3%    |
| HP ProBook                                  | 1         | 1.3%    |
| HP Notebook                                 | 1         | 1.3%    |
| HP EliteDesk                                | 1         | 1.3%    |
| HP 530                                      | 1         | 1.3%    |
| Gigabyte GA-7VT600                          | 1         | 1.3%    |
| Gigabyte B550I                              | 1         | 1.3%    |
| Foxconn AT-7000                             | 1         | 1.3%    |
| Dell XPS                                    | 1         | 1.3%    |
| Dell Latitude                               | 1         | 1.3%    |
| Clevo W240EU                                | 1         | 1.3%    |
| ASUS UX430UNR                               | 1         | 1.3%    |
| ASUS ROG                                    | 1         | 1.3%    |
| ASUS PRIME                                  | 1         | 1.3%    |
| ASUS P10S-I                                 | 1         | 1.3%    |
| ASUS B202                                   | 1         | 1.3%    |
| ASUS 1000HE                                 | 1         | 1.3%    |
| ASRock Z68                                  | 1         | 1.3%    |
| ASRock X570M                                | 1         | 1.3%    |
| Apple PowerBook5                            | 1         | 1.3%    |
| Apple MacBookPro6                           | 1         | 1.3%    |
| Apple MacBookAir6                           | 1         | 1.3%    |
| Alienware Aurora                            | 1         | 1.3%    |
| Acer Spin                                   | 1         | 1.3%    |
| Acer Nitro                                  | 1         | 1.3%    |
| Acer Aspire                                 | 1         | 1.3%    |
| Acer AOA150                                 | 1         | 1.3%    |
| Acer AO531h                                 | 1         | 1.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 15        | 19.48%  |
| 2021    | 11        | 14.29%  |
| 2019    | 9         | 11.69%  |
| 2018    | 8         | 10.39%  |
| 2008    | 5         | 6.49%   |
| 2013    | 4         | 5.19%   |
| 2012    | 4         | 5.19%   |
| Unknown | 4         | 5.19%   |
| 2017    | 3         | 3.9%    |
| 2010    | 3         | 3.9%    |
| 2014    | 2         | 2.6%    |
| 2011    | 2         | 2.6%    |
| 2009    | 2         | 2.6%    |
| 2006    | 2         | 2.6%    |
| 2015    | 1         | 1.3%    |
| 2003    | 1         | 1.3%    |
| 2002    | 1         | 1.3%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 51        | 66.23%  |
| Desktop  | 23        | 29.87%  |
| Server   | 2         | 2.6%    |
| Tablet   | 1         | 1.3%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 72        | 93.51%  |
| Yes  | 5         | 6.49%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 17        | 22.08%  |
| 4.01-8.0    | 15        | 19.48%  |
| 16.01-24.0  | 14        | 18.18%  |
| 3.01-4.0    | 8         | 10.39%  |
| 2.01-3.0    | 7         | 9.09%   |
| 32.01-64.0  | 4         | 5.19%   |
| 1.01-2.0    | 4         | 5.19%   |
| 0.51-1.0    | 4         | 5.19%   |
| 24.01-32.0  | 2         | 2.6%    |
| 64.01-256.0 | 2         | 2.6%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 62        | 80.52%  |
| 0        | 6         | 7.79%   |
| 0.51-1.0 | 5         | 6.49%   |
| 1.01-2.0 | 2         | 2.6%    |
| 4.01-8.0 | 1         | 1.3%    |
| Unknown  | 1         | 1.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 42        | 53.85%  |
| 2      | 21        | 26.92%  |
| 3      | 5         | 6.41%   |
| 4      | 4         | 5.13%   |
| 6      | 2         | 2.56%   |
| 5      | 2         | 2.56%   |
| 7      | 1         | 1.28%   |
| 0      | 1         | 1.28%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 77        | 100%    |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 66        | 85.71%  |
| No        | 11        | 14.29%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 57        | 74.03%  |
| No        | 20        | 25.97%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 43        | 55.84%  |
| Yes       | 34        | 44.16%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 18        | 23.38%  |
| Germany      | 9         | 11.69%  |
| Canada       | 9         | 11.69%  |
| Russia       | 6         | 7.79%   |
| France       | 6         | 7.79%   |
| Netherlands  | 5         | 6.49%   |
| Ukraine      | 3         | 3.9%    |
| Sweden       | 3         | 3.9%    |
| UK           | 2         | 2.6%    |
| Spain        | 2         | 2.6%    |
| Portugal     | 2         | 2.6%    |
| Latvia       | 2         | 2.6%    |
| Turkey       | 1         | 1.3%    |
| Taiwan       | 1         | 1.3%    |
| Switzerland  | 1         | 1.3%    |
| Saudi Arabia | 1         | 1.3%    |
| Philippines  | 1         | 1.3%    |
| Norway       | 1         | 1.3%    |
| Malaysia     | 1         | 1.3%    |
| Indonesia    | 1         | 1.3%    |
| Chile        | 1         | 1.3%    |
| Brazil       | 1         | 1.3%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Saint-Laurent         | 7         | 8.97%   |
| Moscow                | 4         | 5.13%   |
| Riga                  | 2         | 2.56%   |
| Papillion             | 2         | 2.56%   |
| Los Angeles           | 2         | 2.56%   |
| Brooklyn              | 2         | 2.56%   |
| Bielefeld             | 2         | 2.56%   |
| Berlin                | 2         | 2.56%   |
| Barneveld             | 2         | 2.56%   |
| 's-Hertogenbosch      | 2         | 2.56%   |
| Yekaterinburg         | 1         | 1.28%   |
| Wittersham            | 1         | 1.28%   |
| Watford               | 1         | 1.28%   |
| Victoria              | 1         | 1.28%   |
| Van Nuys              | 1         | 1.28%   |
| Valdivia              | 1         | 1.28%   |
| Vacaville             | 1         | 1.28%   |
| Teriang               | 1         | 1.28%   |
| São Paulo            | 1         | 1.28%   |
| Syeverodonets'k       | 1         | 1.28%   |
| Surabaya              | 1         | 1.28%   |
| Spokane               | 1         | 1.28%   |
| Solna                 | 1         | 1.28%   |
| Soeraker              | 1         | 1.28%   |
| Sedavi                | 1         | 1.28%   |
| Sechelt               | 1         | 1.28%   |
| Saint-Martin-d'Hères | 1         | 1.28%   |
| Roubaix               | 1         | 1.28%   |
| Roseville             | 1         | 1.28%   |
| Rodgau                | 1         | 1.28%   |
| Riyadh                | 1         | 1.28%   |
| Quezon City           | 1         | 1.28%   |
| Plainfield            | 1         | 1.28%   |
| Oensingen             | 1         | 1.28%   |
| Oeiras                | 1         | 1.28%   |
| New York              | 1         | 1.28%   |
| New Taipei            | 1         | 1.28%   |
| Neuilly-sur-Marne     | 1         | 1.28%   |
| Monts                 | 1         | 1.28%   |
| McLeod                | 1         | 1.28%   |
| Madrid                | 1         | 1.28%   |
| Kyiv                  | 1         | 1.28%   |
| Korolyov              | 1         | 1.28%   |
| Independence          | 1         | 1.28%   |
| Hoeviksnaes           | 1         | 1.28%   |
| Hockenheim            | 1         | 1.28%   |
| Heilbronn             | 1         | 1.28%   |
| Hamilton              | 1         | 1.28%   |
| Greensburg            | 1         | 1.28%   |
| Frankfurt am Main     | 1         | 1.28%   |
| Estoril               | 1         | 1.28%   |
| Donetsk               | 1         | 1.28%   |
| Corbarieu             | 1         | 1.28%   |
| Commack               | 1         | 1.28%   |
| Clearwater            | 1         | 1.28%   |
| Bordeaux              | 1         | 1.28%   |
| Bloomfield            | 1         | 1.28%   |
| Arendal               | 1         | 1.28%   |
| Ankara                | 1         | 1.28%   |
| Amsterdam             | 1         | 1.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| NVMe                | 16        | 18     | 16.49%  |
| WDC                 | 15        | 16     | 15.46%  |
| Samsung Electronics | 14        | 19     | 14.43%  |
| Seagate             | 6         | 11     | 6.19%   |
| Toshiba             | 5         | 5      | 5.15%   |
| OPENBSD             | 4         | 4      | 4.12%   |
| HGST                | 4         | 5      | 4.12%   |
| SanDisk             | 3         | 3      | 3.09%   |
| Intel               | 3         | 4      | 3.09%   |
| Crucial             | 3         | 3      | 3.09%   |
| SK Hynix            | 2         | 2      | 2.06%   |
| Kingston            | 2         | 2      | 2.06%   |
| Hitachi             | 2         | 2      | 2.06%   |
| Hewlett-Packard     | 2         | 6      | 2.06%   |
| Zheino              | 1         | 1      | 1.03%   |
| USB                 | 1         | 1      | 1.03%   |
| UDinfo              | 1         | 1      | 1.03%   |
| Transcend           | 1         | 4      | 1.03%   |
| Team                | 1         | 1      | 1.03%   |
| SPCC                | 1         | 1      | 1.03%   |
| Product:            | 1         | 1      | 1.03%   |
| Phison              | 1         | 1      | 1.03%   |
| Patriot             | 1         | 1      | 1.03%   |
| Multiple            | 1         | 1      | 1.03%   |
| Micron Technology   | 1         | 1      | 1.03%   |
| LSI                 | 1         | 1      | 1.03%   |
| Fujitsu             | 1         | 1      | 1.03%   |
| asmedia             | 1         | 1      | 1.03%   |
| Apple               | 1         | 1      | 1.03%   |
| A-DATA Technology   | 1         | 1      | 1.03%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| OPENBSD SR RAID 1 240GB           | 4         | 3.7%    |
| WDC WD1600BEVT-22ZCT0 160GB       | 3         | 2.78%   |
| NVMe Samsung SSD 960 500GB        | 3         | 2.78%   |
| Samsung SSD 850 EVO 250GB         | 2         | 1.85%   |
| NVMe WDC PC SN730 SDB 1TB         | 2         | 1.85%   |
| NVMe SAMSUNG MZVLB256 256GB       | 2         | 1.85%   |
| HGST HUS724020ALA640 2TB          | 2         | 1.85%   |
| Zheino CHN-mSATAQ3-120 120GB      | 1         | 0.93%   |
| WDC WDS500G2B0A-00SM50 500GB      | 1         | 0.93%   |
| WDC WD80EFAX-68KNBN0 8TB          | 1         | 0.93%   |
| WDC WD7500BPKX-00HPJT0 752GB      | 1         | 0.93%   |
| WDC WD7500BPKT-00PK4T0 752GB      | 1         | 0.93%   |
| WDC WD60EFRX-68L0BN1 6TB          | 1         | 0.93%   |
| WDC WD5000LPLX-00ZNTT0 500GB      | 1         | 0.93%   |
| WDC WD5000LPCX-24C6HT0 500GB      | 1         | 0.93%   |
| WDC WD3200BEVE-00A0HT0 320GB      | 1         | 0.93%   |
| WDC WD3200BEKT-08PVMT1 320GB      | 1         | 0.93%   |
| WDC WD20PURX-64P6ZY0 2TB          | 1         | 0.93%   |
| WDC WD10SPCX-24HWST1 1TB          | 1         | 0.93%   |
| WDC WD10JPLX-00MBPT0 1TB          | 1         | 0.93%   |
| WDC WD Elements 25A3 4TB          | 1         | 0.93%   |
| USB SanDisk 3.2Gen1 16GB          | 1         | 0.93%   |
| UDinfo M2S 120GB                  | 1         | 0.93%   |
| Transcend 3E128-TS2-550B01 100GB  | 1         | 0.93%   |
| Toshiba MQ04ABF100 1TB            | 1         | 0.93%   |
| Toshiba MK8025GAS 80GB            | 1         | 0.93%   |
| Toshiba MK3256GSY 320GB           | 1         | 0.93%   |
| Toshiba MK1665GSX 160GB           | 1         | 0.93%   |
| Toshiba DT01ACA100 1TB            | 1         | 0.93%   |
| Team T253X2001T 1TB               | 1         | 0.93%   |
| SPCC Solid State Disk 128GB       | 1         | 0.93%   |
| SK Hynix SC311 SATA 256GB         | 1         | 0.93%   |
| SK Hynix HFS128G39TND-N210A 128GB | 1         | 0.93%   |
| Seagate ST950032 5AS 500GB        | 1         | 0.93%   |
| Seagate ST9160821A 160GB          | 1         | 0.93%   |
| Seagate ST9160310AS 160GB         | 1         | 0.93%   |
| Seagate ST500LT012-9WS142 500GB   | 1         | 0.93%   |
| Seagate ST3808110AS 80GB          | 1         | 0.93%   |
| Seagate ST380011A 80GB            | 1         | 0.93%   |
| Seagate ST3160212ACE 160GB        | 1         | 0.93%   |
| Seagate ST2000LX001-1RG174 2TB    | 1         | 0.93%   |
| Seagate Backup+ SL 1TB            | 1         | 0.93%   |
| SanDisk Ultra Fit 16GB            | 1         | 0.93%   |
| SanDisk Ultra 64GB                | 1         | 0.93%   |
| SanDisk SSD PLUS 120GB            | 1         | 0.93%   |
| Samsung SSD 860 PRO 256GB         | 1         | 0.93%   |
| Samsung SSD 860 EVO M.2 2TB       | 1         | 0.93%   |
| Samsung SSD 860 EVO M.2 250GB     | 1         | 0.93%   |
| Samsung SSD 860 EVO M.2 1TB       | 1         | 0.93%   |
| Samsung SSD 860 EVO 2TB           | 1         | 0.93%   |
| Samsung SSD 860 EVO 1TB           | 1         | 0.93%   |
| Samsung SSD 850 PRO 256GB         | 1         | 0.93%   |
| Samsung SSD 850 EVO 500GB         | 1         | 0.93%   |
| Samsung SSD 850 EVO 120GB         | 1         | 0.93%   |
| Samsung SSD 840 Series 120GB      | 1         | 0.93%   |
| Samsung MZ7TD256HAFV-000L7 256GB  | 1         | 0.93%   |
| Samsung MZ7LH240HAHQ-00005 240GB  | 1         | 0.93%   |
| Samsung MMCQE28GFMUP-MVA 128GB    | 1         | 0.93%   |
| Samsung Flash Drive FIT 32GB      | 1         | 0.93%   |
| Samsung Flash Drive 64GB          | 1         | 0.93%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 14        | 15     | 25.45%  |
| NVMe                | 11        | 12     | 20%     |
| Seagate             | 6         | 11     | 10.91%  |
| Toshiba             | 5         | 5      | 9.09%   |
| OPENBSD             | 4         | 4      | 7.27%   |
| HGST                | 4         | 5      | 7.27%   |
| Samsung Electronics | 2         | 2      | 3.64%   |
| Hitachi             | 2         | 2      | 3.64%   |
| Hewlett-Packard     | 2         | 6      | 3.64%   |
| USB                 | 1         | 1      | 1.82%   |
| Product:            | 1         | 1      | 1.82%   |
| Multiple            | 1         | 1      | 1.82%   |
| LSI                 | 1         | 1      | 1.82%   |
| Fujitsu             | 1         | 1      | 1.82%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 17     | 30.23%  |
| NVMe                | 5         | 5      | 11.63%  |
| SanDisk             | 3         | 3      | 6.98%   |
| Intel               | 3         | 4      | 6.98%   |
| Crucial             | 3         | 3      | 6.98%   |
| SK Hynix            | 2         | 2      | 4.65%   |
| Kingston            | 2         | 2      | 4.65%   |
| Zheino              | 1         | 1      | 2.33%   |
| WDC                 | 1         | 1      | 2.33%   |
| UDinfo              | 1         | 1      | 2.33%   |
| Transcend           | 1         | 4      | 2.33%   |
| Team                | 1         | 1      | 2.33%   |
| SPCC                | 1         | 1      | 2.33%   |
| Phison              | 1         | 1      | 2.33%   |
| Patriot             | 1         | 1      | 2.33%   |
| Micron Technology   | 1         | 1      | 2.33%   |
| asmedia             | 1         | 1      | 2.33%   |
| Apple               | 1         | 1      | 2.33%   |
| A-DATA Technology   | 1         | 1      | 2.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 44        | 67     | 53.01%  |
| SSD  | 38        | 51     | 45.78%  |
| NVMe | 1         | 1      | 1.2%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 72        | 118    | 98.63%  |
| NVMe | 1         | 1      | 1.37%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 56        | 81     | 68.29%  |
| 0.51-1.0        | 14        | 20     | 17.07%  |
| 1.01-2.0        | 8         | 12     | 9.76%   |
| 4.01-10.0       | 2         | 3      | 2.44%   |
| More than 100.0 | 1         | 1      | 1.22%   |
| 3.01-4.0        | 1         | 1      | 1.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 28        | 36.36%  |
| 251-500        | 20        | 25.97%  |
| 51-100         | 9         | 11.69%  |
| 21-50          | 7         | 9.09%   |
| 1-20           | 6         | 7.79%   |
| More than 3000 | 4         | 5.19%   |
| 501-1000       | 2         | 2.6%    |
| 1001-2000      | 1         | 1.3%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 55        | 70.51%  |
| 21-50     | 7         | 8.97%   |
| 51-100    | 6         | 7.69%   |
| 101-250   | 5         | 6.41%   |
| 251-500   | 2         | 2.56%   |
| 1001-2000 | 2         | 2.56%   |
| 501-1000  | 1         | 1.28%   |

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
| Works    | 52        | 78     | 64.2%   |
| Detected | 21        | 28     | 25.93%  |
| Malfunc  | 8         | 13     | 9.88%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 53        | 61.63%  |
| AMD                      | 10        | 11.63%  |
| Samsung Electronics      | 7         | 8.14%   |
| Sandisk                  | 4         | 4.65%   |
| Marvell Technology Group | 2         | 2.33%   |
| KIOXIA                   | 2         | 2.33%   |
| Hewlett-Packard          | 2         | 2.33%   |
| Broadcom / LSI           | 2         | 2.33%   |
| VIA Technologies         | 1         | 1.16%   |
| Toshiba                  | 1         | 1.16%   |
| SK Hynix                 | 1         | 1.16%   |
| Phison Electronics       | 1         | 1.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 8         | 8.51%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 5         | 5.32%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 5         | 5.32%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4         | 4.26%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 3         | 3.19%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3         | 3.19%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 3         | 3.19%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 3         | 3.19%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 3         | 3.19%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3         | 3.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 3         | 3.19%   |
| KIOXIA unknown                                                                          | 2         | 2.13%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 2         | 2.13%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 2         | 2.13%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2         | 2.13%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2         | 2.13%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 2         | 2.13%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 2         | 2.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2         | 2.13%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 1         | 1.06%   |
| Toshiba BG3 NVMe SSD Controller                                                         | 1         | 1.06%   |
| SK Hynix BC511                                                                          | 1         | 1.06%   |
| Sandisk WD Black SN850                                                                  | 1         | 1.06%   |
| Phison E12 NVMe Controller                                                              | 1         | 1.06%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                              | 1         | 1.06%   |
| Marvell Group 88SE912x SATA 6Gb/s Controller [IDE mode]                                 | 1         | 1.06%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                              | 1         | 1.06%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                 | 1         | 1.06%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1         | 1.06%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1         | 1.06%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1         | 1.06%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 1         | 1.06%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1         | 1.06%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 1         | 1.06%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 1         | 1.06%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1         | 1.06%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1         | 1.06%   |
| Intel Atom Processor C3000 Series SATA Controller 1                                     | 1         | 1.06%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 1         | 1.06%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                                  | 1         | 1.06%   |
| Intel 82801CAM IDE U100 Controller                                                      | 1         | 1.06%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 1         | 1.06%   |
| Intel 7 Series/C210 Series Chipset Family IDE-r Controller                              | 1         | 1.06%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                              | 1         | 1.06%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 1.06%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 1.06%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1         | 1.06%   |
| HP Smart Array Gen9 Controllers                                                         | 1         | 1.06%   |
| HP Smart Array G6 controllers                                                           | 1         | 1.06%   |
| Broadcom / LSI SSS6200 PCI-Express Flash SSD                                            | 1         | 1.06%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 1         | 1.06%   |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                          | 1         | 1.06%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1         | 1.06%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1         | 1.06%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 52        | 58.43%  |
| NVMe | 16        | 17.98%  |
| IDE  | 16        | 17.98%  |
| RAID | 3         | 3.37%   |
| SAS  | 2         | 2.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 62        | 80.52%  |
| AMD     | 12        | 15.58%  |
| ARM     | 2         | 2.6%    |
| Unknown | 1         | 1.3%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Core i5-3320M CPU @ 2.60GHz                             | 3         | 3.9%    |
| Intel Atom CPU N270 @ 1.60GHz ("GenuineIntel" 686-class)      | 3         | 3.9%    |
| Intel Core i7-8565U CPU @ 1.80GHz                             | 2         | 2.6%    |
| Intel Core i7-7500U CPU @ 2.70GHz                             | 2         | 2.6%    |
| Intel Core i5-5300U CPU @ 2.30GHz                             | 2         | 2.6%    |
| Intel Core i5-2520M CPU @ 2.50GHz                             | 2         | 2.6%    |
| Intel Core i5 CPU M 520 @ 2.40GHz                             | 2         | 2.6%    |
| ARM Cortex-A53 r0p4                                           | 2         | 2.6%    |
| AMD GX-412TC SOC                                              | 2         | 2.6%    |
| Intel Xeon CPU X5675 @ 3.07GHz                                | 1         | 1.3%    |
| Intel Xeon CPU W3530 @ 2.80GHz                                | 1         | 1.3%    |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz                           | 1         | 1.3%    |
| Intel Xeon CPU E5-2407 0 @ 2.20GHz                            | 1         | 1.3%    |
| Intel Xeon CPU E3-1270 v3 @ 3.50GHz                           | 1         | 1.3%    |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz                           | 1         | 1.3%    |
| Intel Xeon CPU D-1521 @ 2.40GHz                               | 1         | 1.3%    |
| Intel Pentium Silver N5000 CPU @ 1.10GHz                      | 1         | 1.3%    |
| Intel Pentium M processor 2.00GHz ("GenuineIntel" 686-class)  | 1         | 1.3%    |
| Intel Pentium CPU N4200 @ 1.10GHz                             | 1         | 1.3%    |
| Intel Pentium 4 Mobile CPU 1.60GHz ("GenuineIntel" 686-class) | 1         | 1.3%    |
| Intel CPU T2300 @ 1.66GHz ("GenuineIntel" 686-class)          | 1         | 1.3%    |
| Intel Core i7-8750H CPU @ 2.20GHz                             | 1         | 1.3%    |
| Intel Core i7-8550U CPU @ 1.80GHz                             | 1         | 1.3%    |
| Intel Core i7-3520M CPU @ 2.90GHz                             | 1         | 1.3%    |
| Intel Core i7-10510U CPU @ 1.80GHz                            | 1         | 1.3%    |
| Intel Core i7 CPU M 620 @ 2.67GHz                             | 1         | 1.3%    |
| Intel Core i5-9500 CPU @ 3.00GHz                              | 1         | 1.3%    |
| Intel Core i5-8350U CPU @ 1.70GHz                             | 1         | 1.3%    |
| Intel Core i5-8265U CPU @ 1.60GHz                             | 1         | 1.3%    |
| Intel Core i5-6300U CPU @ 2.40GHz                             | 1         | 1.3%    |
| Intel Core i5-4250U CPU @ 1.30GHz                             | 1         | 1.3%    |
| Intel Core i5-3230M CPU @ 2.60GHz                             | 1         | 1.3%    |
| Intel Core i5-2540M CPU @ 2.60GHz                             | 1         | 1.3%    |
| Intel Core i5-2500K CPU @ 3.30GHz                             | 1         | 1.3%    |
| Intel Core i5-1035G4 CPU @ 1.10GHz                            | 1         | 1.3%    |
| Intel Core i3-5005U CPU @ 2.00GHz                             | 1         | 1.3%    |
| Intel Core i3-4005U CPU @ 1.70GHz                             | 1         | 1.3%    |
| Intel Core i3-3217U CPU @ 1.80GHz                             | 1         | 1.3%    |
| Intel Core i3-3130M CPU @ 2.60GHz                             | 1         | 1.3%    |
| Intel Core i3-2375M CPU @ 1.50GHz                             | 1         | 1.3%    |
| Intel Core i3 CPU M 380 @ 2.53GHz                             | 1         | 1.3%    |
| Intel Core Duo CPU T2600 @ 2.16GHz ("GenuineIntel" 686-class) | 1         | 1.3%    |
| Intel Core 2 Duo CPU T9900 @ 3.06GHz                          | 1         | 1.3%    |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz                          | 1         | 1.3%    |
| Intel Core 2 Duo CPU P9700 @ 2.80GHz                          | 1         | 1.3%    |
| Intel Celeron N4020 CPU @ 1.10GHz                             | 1         | 1.3%    |
| Intel Celeron M CPU 430 @ 1.73GHz ("GenuineIntel" 686-class)  | 1         | 1.3%    |
| Intel Celeron D CPU 3.20GHz                                   | 1         | 1.3%    |
| Intel Celeron CPU N3350 @ 1.10GHz                             | 1         | 1.3%    |
| Intel Celeron CPU N2840 @ 2.16GHz                             | 1         | 1.3%    |
| Intel Celeron CPU 3865U @ 1.80GHz                             | 1         | 1.3%    |
| Intel Atom CPU Z530 @ 1.60GHz ("GenuineIntel" 686-class)      | 1         | 1.3%    |
| Intel Atom CPU N280 @ 1.66GHz ("GenuineIntel" 686-class)      | 1         | 1.3%    |
| Intel Atom CPU C3558 @ 2.20GHz                                | 1         | 1.3%    |
| Intel 11th Gen Core i5-11600K @ 3.90GHz                       | 1         | 1.3%    |
| AMD Ryzen 7 PRO 4750G with Radeon Graphics                    | 1         | 1.3%    |
| AMD Ryzen 7 5800X 8-Core Processor                            | 1         | 1.3%    |
| AMD Ryzen 7 5700G with Radeon Graphics                        | 1         | 1.3%    |
| AMD Ryzen 7 4800H with Radeon Graphics                        | 1         | 1.3%    |
| AMD Ryzen 7 3700X 8-Core Processor                            | 1         | 1.3%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 18        | 23.38%  |
| Intel Core i7        | 9         | 11.69%  |
| Intel Xeon           | 7         | 9.09%   |
| Intel Core i3        | 6         | 7.79%   |
| Intel Atom           | 6         | 7.79%   |
| Intel Celeron        | 4         | 5.19%   |
| AMD Ryzen 7          | 4         | 5.19%   |
| Other                | 3         | 3.9%    |
| Intel Core 2 Duo     | 3         | 3.9%    |
| ARM Cortex           | 2         | 2.6%    |
| AMD GX               | 2         | 2.6%    |
| Intel Pentium Silver | 1         | 1.3%    |
| Intel Pentium M      | 1         | 1.3%    |
| Intel Pentium 4      | 1         | 1.3%    |
| Intel Pentium        | 1         | 1.3%    |
| Intel Core Duo       | 1         | 1.3%    |
| Intel Celeron M      | 1         | 1.3%    |
| Intel Celeron D      | 1         | 1.3%    |
| AMD Ryzen 7 PRO      | 1         | 1.3%    |
| AMD Ryzen 5 PRO      | 1         | 1.3%    |
| AMD Ryzen 5          | 1         | 1.3%    |
| AMD G                | 1         | 1.3%    |
| AMD Athlon XP        | 1         | 1.3%    |
| AMD Athlon II Neo    | 1         | 1.3%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 29        | 37.66%  |
| 4       | 18        | 23.38%  |
| Unknown | 13        | 16.88%  |
| 16      | 5         | 6.49%   |
| 6       | 5         | 6.49%   |
| 1       | 5         | 6.49%   |
| 12      | 2         | 2.6%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 60        | 77.92%  |
| Unknown | 17        | 22.08%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 37        | 48.05%  |
| 1       | 23        | 29.87%  |
| Unknown | 17        | 22.08%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 11        | 14.29%  |
| IvyBridge     | 7         | 9.09%   |
| SandyBridge   | 6         | 7.79%   |
| Unknown       | 6         | 7.79%   |
| Zen 2         | 5         | 6.49%   |
| Westmere      | 5         | 6.49%   |
| Bonnell       | 5         | 6.49%   |
| Haswell       | 4         | 5.19%   |
| Broadwell     | 4         | 5.19%   |
| Penryn        | 3         | 3.9%    |
| P6            | 3         | 3.9%    |
| Goldmont      | 3         | 3.9%    |
| Zen 3         | 2         | 2.6%    |
| Skylake       | 2         | 2.6%    |
| Puma          | 2         | 2.6%    |
| Goldmont plus | 2         | 2.6%    |
| Silvermont    | 1         | 1.3%    |
| NetBurst      | 1         | 1.3%    |
| Nehalem       | 1         | 1.3%    |
| K6            | 1         | 1.3%    |
| K10           | 1         | 1.3%    |
| IceLake       | 1         | 1.3%    |
| Bobcat        | 1         | 1.3%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 50        | 62.5%   |
| AMD                        | 16        | 20%     |
| Nvidia                     | 6         | 7.5%    |
| Matrox Electronics Systems | 4         | 5%      |
| ASPEED Technology          | 4         | 5%      |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                              | Computers | Percent |
|------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller      | 7         | 7.95%   |
| Intel 3rd Gen Core processor Graphics Controller                                   | 7         | 7.95%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                         | 5         | 5.68%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller          | 5         | 5.68%   |
| Intel Core Processor Integrated Graphics Controller                                | 4         | 4.55%   |
| ASPEED Technology ASPEED Graphics Family                                           | 4         | 4.55%   |
| AMD Renoir                                                                         | 4         | 4.55%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                         | 3         | 3.41%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                       | 3         | 3.41%   |
| Intel HD Graphics 5500                                                             | 3         | 3.41%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                      | 2         | 2.27%   |
| Matrox Electronics Systems MGA G200EH                                              | 2         | 2.27%   |
| Intel UHD Graphics 620                                                             | 2         | 2.27%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller          | 2         | 2.27%   |
| Intel HD Graphics 620                                                              | 2         | 2.27%   |
| Intel Haswell-ULT Integrated Graphics Controller                                   | 2         | 2.27%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                                | 2         | 2.27%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                            | 2         | 2.27%   |
| Nvidia TU117M                                                                      | 1         | 1.14%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                             | 1         | 1.14%   |
| Nvidia GT216M [GeForce GT 330M]                                                    | 1         | 1.14%   |
| Nvidia GP108M [GeForce MX330]                                                      | 1         | 1.14%   |
| Nvidia GP108M [GeForce MX150]                                                      | 1         | 1.14%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                            | 1         | 1.14%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                | 1         | 1.14%   |
| Intel Skylake GT2 [HD Graphics 520]                                                | 1         | 1.14%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                               | 1         | 1.14%   |
| Intel Iris Plus Graphics G4 (Ice Lake)                                             | 1         | 1.14%   |
| Intel HD Graphics 500                                                              | 1         | 1.14%   |
| Intel GeminiLake [UHD Graphics 605]                                                | 1         | 1.14%   |
| Intel GeminiLake [UHD Graphics 600]                                                | 1         | 1.14%   |
| Intel CometLake-U GT2 [UHD Graphics]                                               | 1         | 1.14%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                           | 1         | 1.14%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                          | 1         | 1.14%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller | 1         | 1.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                       | 1         | 1.14%   |
| AMD RV350/M10 / RV360/M11 [Mobility Radeon 9600 (PRO) / 9700]                      | 1         | 1.14%   |
| AMD RV280 [Radeon 9200 PRO] (Secondary)                                            | 1         | 1.14%   |
| AMD RV280 [Radeon 9200 PRO / 9250]                                                 | 1         | 1.14%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                          | 1         | 1.14%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                   | 1         | 1.14%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                         | 1         | 1.14%   |
| AMD ES1000                                                                         | 1         | 1.14%   |
| AMD Cezanne                                                                        | 1         | 1.14%   |
| AMD Caicos PRO [Radeon HD 7450]                                                    | 1         | 1.14%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 34        | 44.16%  |
| 1 x AMD        | 11        | 14.29%  |
| 2 x Intel      | 10        | 12.99%  |
| Other          | 5         | 6.49%   |
| Intel + Nvidia | 4         | 5.19%   |
| 1 x ASPEED     | 4         | 5.19%   |
| 1 x Matrox     | 3         | 3.9%    |
| Intel + AMD    | 2         | 2.6%    |
| 2 x AMD        | 1         | 1.3%    |
| 1 x Nvidia     | 1         | 1.3%    |
| AMD + Nvidia   | 1         | 1.3%    |
| AMD + Matrox   | 1         | 1.3%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 64        | 83.12%  |
| Unknown | 13        | 16.88%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 77        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 10        | 23.26%  |
| LG Display              | 6         | 13.95%  |
| BOE                     | 4         | 9.3%    |
| Lenovo                  | 3         | 6.98%   |
| Dell                    | 3         | 6.98%   |
| Sharp                   | 2         | 4.65%   |
| Samsung Electronics     | 2         | 4.65%   |
| Chimei Innolux          | 2         | 4.65%   |
| Apple                   | 2         | 4.65%   |
| Vizio                   | 1         | 2.33%   |
| Philips                 | 1         | 2.33%   |
| LG Philips              | 1         | 2.33%   |
| InfoVision              | 1         | 2.33%   |
| Goldstar                | 1         | 2.33%   |
| Eizo                    | 1         | 2.33%   |
| Chi Mei Optoelectronics | 1         | 2.33%   |
| AOC                     | 1         | 2.33%   |
| Ancor Communications    | 1         | 2.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 2         | 4.65%   |
| Vizio E320i-A0 VIZ0091 1366x768 700x390mm 31.5-inch                      | 1         | 2.33%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 340x190mm 15.3-inch                  | 1         | 2.33%   |
| Sharp LCD Monitor SHP1449 1920x1080 290x170mm 13.2-inch                  | 1         | 2.33%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch     | 1         | 2.33%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 310x170mm 13.9-inch     | 1         | 2.33%   |
| Philips PHL 276E8V PHLC18F 3840x2160 600x340mm 27.2-inch                 | 1         | 2.33%   |
| LG Philips LCD Monitor LPLDB00 1280x800 330x210mm 15.4-inch              | 1         | 2.33%   |
| LG Display LCD Monitor LGD05D8 1920x1080 340x190mm 15.3-inch             | 1         | 2.33%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x170mm 12.2-inch             | 1         | 2.33%   |
| LG Display LCD Monitor LGD0450 1366x768 280x160mm 12.7-inch              | 1         | 2.33%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch              | 1         | 2.33%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x170mm 13.9-inch              | 1         | 2.33%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 1         | 2.33%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch                  | 1         | 2.33%   |
| Lenovo LCD Monitor LEN4033 1440x900 300x190mm 14.0-inch                  | 1         | 2.33%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch                  | 1         | 2.33%   |
| InfoVision M116NWR1 R0  IVO0489 1366x768 260x140mm 11.6-inch             | 1         | 2.33%   |
| Goldstar L1715S GSM436F 1280x1024 340x270mm 17.1-inch                    | 1         | 2.33%   |
| Eizo EV2450 ENC2530 1920x1080 530x300mm 24.0-inch                        | 1         | 2.33%   |
| Dell U4919DW DELA107 3840x1080 1200x340mm 49.1-inch                      | 1         | 2.33%   |
| Dell U2715H DELD065 2560x1440 600x340mm 27.2-inch                        | 1         | 2.33%   |
| Dell P2317H DEL40F3 1920x1080 480x270mm 21.7-inch                        | 1         | 2.33%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 340x190mm 15.3-inch         | 1         | 2.33%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch          | 1         | 2.33%   |
| Chi Mei Optoelectronics LCD Monitor CMO1107 1366x768 250x140mm 11.3-inch | 1         | 2.33%   |
| BOE LCD Monitor BOE0817 1366x768 340x190mm 15.3-inch                     | 1         | 2.33%   |
| BOE LCD Monitor BOE07C8 3840x2160 310x170mm 13.9-inch                    | 1         | 2.33%   |
| BOE LCD Monitor BOE0731 1366x768 260x140mm 11.6-inch                     | 1         | 2.33%   |
| BOE LCD Monitor BOE0718 1920x1080 310x170mm 13.9-inch                    | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO5F2D 1920x1080 290x170mm 13.2-inch           | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 310x170mm 13.9-inch           | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 340x190mm 15.3-inch            | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch            | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch            | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO235C 1366x768 260x140mm 11.6-inch            | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch           | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO11C2 1024x600 200x110mm 9.0-inch             | 1         | 2.33%   |
| Apple Color LCD APP9CDF 1440x900 290x180mm 13.4-inch                     | 1         | 2.33%   |
| Apple Color LCD APP9C20 1280x854 320x220mm 15.3-inch                     | 1         | 2.33%   |
| AOC 2270W AOC2270 1920x1080 480x270mm 21.7-inch                          | 1         | 2.33%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 520x290mm 23.4-inch    | 1         | 2.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 16        | 38.1%   |
| 1920x1080 (FHD)  | 11        | 26.19%  |
| 1440x900 (WXGA+) | 3         | 7.14%   |
| 3840x2160 (4K)   | 2         | 4.76%   |
| 1600x900 (HD+)   | 2         | 4.76%   |
| 1280x800 (WXGA)  | 2         | 4.76%   |
| 3840x1080        | 1         | 2.38%   |
| 2736x1824        | 1         | 2.38%   |
| 2560x1440 (QHD)  | 1         | 2.38%   |
| 1280x854         | 1         | 2.38%   |
| 1280x1024 (SXGA) | 1         | 2.38%   |
| 1024x600         | 1         | 2.38%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 13     | 10        | 23.26%  |
| 15     | 7         | 16.28%  |
| 12     | 7         | 16.28%  |
| 11     | 6         | 13.95%  |
| 14     | 3         | 6.98%   |
| 27     | 2         | 4.65%   |
| 21     | 2         | 4.65%   |
| 49     | 1         | 2.33%   |
| 31     | 1         | 2.33%   |
| 24     | 1         | 2.33%   |
| 23     | 1         | 2.33%   |
| 17     | 1         | 2.33%   |
| 9      | 1         | 2.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 201-300     | 19        | 44.19%  |
| 301-350     | 15        | 34.88%  |
| 501-600     | 4         | 9.3%    |
| 401-500     | 2         | 4.65%   |
| 601-700     | 1         | 2.33%   |
| 101-200     | 1         | 2.33%   |
| 1001-1500   | 1         | 2.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 33        | 78.57%  |
| 16/10 | 5         | 11.9%   |
| 3/2   | 2         | 4.76%   |
| 5/4   | 1         | 2.38%   |
| 32/9  | 1         | 2.38%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 11        | 25.58%  |
| 61-70          | 7         | 16.28%  |
| 51-60          | 6         | 13.95%  |
| 91-100         | 5         | 11.63%  |
| 201-250        | 4         | 9.3%    |
| 71-80          | 2         | 4.65%   |
| 301-350        | 2         | 4.65%   |
| 101-110        | 2         | 4.65%   |
| 351-500        | 1         | 2.33%   |
| 1-40           | 1         | 2.33%   |
| 141-150        | 1         | 2.33%   |
| 501-1000       | 1         | 2.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 22        | 51.16%  |
| 101-120       | 9         | 20.93%  |
| 51-100        | 5         | 11.63%  |
| 161-240       | 4         | 9.3%    |
| More than 240 | 2         | 4.65%   |
| 1-50          | 1         | 2.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 54        | 70.13%  |
| 0     | 22        | 28.57%  |
| 2     | 1         | 1.3%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 54        | 52.43%  |
| Realtek Semiconductor    | 24        | 23.3%   |
| Qualcomm Atheros         | 9         | 8.74%   |
| Broadcom                 | 6         | 5.83%   |
| Marvell Technology Group | 2         | 1.94%   |
| Xiaomi                   | 1         | 0.97%   |
| TP-Link                  | 1         | 0.97%   |
| Ralink Technology        | 1         | 0.97%   |
| Ralink                   | 1         | 0.97%   |
| Micro Star International | 1         | 0.97%   |
| Fibocom                  | 1         | 0.97%   |
| Edimax Technology        | 1         | 0.97%   |
| Apple                    | 1         | 0.97%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 15        | 11.19%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 7         | 5.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 4.48%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 3.73%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 4         | 2.99%   |
| Intel Wireless 8265 / 8275                                              | 4         | 2.99%   |
| Intel Wireless 7265                                                     | 3         | 2.24%   |
| Intel I211 Gigabit Network Connection                                   | 3         | 2.24%   |
| Intel I210 Gigabit Network Connection                                   | 3         | 2.24%   |
| Intel 82567LM Gigabit Network Connection                                | 3         | 2.24%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 2         | 1.49%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 1.49%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 1.49%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 2         | 1.49%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.49%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 1.49%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 1.49%   |
| Intel I350 Gigabit Network Connection                                   | 2         | 1.49%   |
| Intel Ethernet Connection I219-LM                                       | 2         | 1.49%   |
| Intel Ethernet Connection (3) I218-LM                                   | 2         | 1.49%   |
| Intel Centrino Wireless-N 2200                                          | 2         | 1.49%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 1.49%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.49%   |
| Intel 82577LM Gigabit Network Connection                                | 2         | 1.49%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 0.75%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 0.75%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.75%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.75%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 0.75%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.75%   |
| Realtek RTL8125 2.5GbE Controller                                       | 1         | 0.75%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                        | 1         | 0.75%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.75%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                               | 1         | 0.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 0.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 0.75%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 1         | 0.75%   |
| Micro Star International RT2573                                         | 1         | 0.75%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                 | 1         | 0.75%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                 | 1         | 0.75%   |
| Intel Wireless-AC 9260                                                  | 1         | 0.75%   |
| Intel Wireless 8260                                                     | 1         | 0.75%   |
| Intel Wireless 3160                                                     | 1         | 0.75%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 0.75%   |
| Intel I210 Gigabit Fiber Network Connection                             | 1         | 0.75%   |
| Intel Ethernet Controller I225-V                                        | 1         | 0.75%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                           | 1         | 0.75%   |
| Intel Ethernet Connection X553 1GbE                                     | 1         | 0.75%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                        | 1         | 0.75%   |
| Intel Ethernet Connection (7) I219-LM                                   | 1         | 0.75%   |
| Intel Ethernet Connection (6) I219-V                                    | 1         | 0.75%   |
| Intel Ethernet Connection (4) I219-V                                    | 1         | 0.75%   |
| Intel Ethernet Connection (14) I219-V                                   | 1         | 0.75%   |
| Intel Ethernet Connection (10) I219-V                                   | 1         | 0.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 0.75%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 0.75%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 0.75%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 0.75%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 0.75%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 38        | 63.33%  |
| Qualcomm Atheros         | 9         | 15%     |
| Realtek Semiconductor    | 5         | 8.33%   |
| Broadcom                 | 3         | 5%      |
| TP-Link                  | 1         | 1.67%   |
| Ralink Technology        | 1         | 1.67%   |
| Ralink                   | 1         | 1.67%   |
| Micro Star International | 1         | 1.67%   |
| Edimax Technology        | 1         | 1.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 10%     |
| Intel Wi-Fi 6 AX200                                                     | 5         | 8.33%   |
| Intel Wireless 8265 / 8275                                              | 4         | 6.67%   |
| Intel Wireless 7265                                                     | 3         | 5%      |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 3.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 3.33%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 3.33%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 3.33%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 3.33%   |
| Intel Centrino Wireless-N 2200                                          | 2         | 3.33%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 3.33%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 3.33%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 1.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.67%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 1.67%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 1.67%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.67%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 1.67%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                               | 1         | 1.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 1.67%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 1         | 1.67%   |
| Micro Star International RT2573                                         | 1         | 1.67%   |
| Intel Wireless-AC 9260                                                  | 1         | 1.67%   |
| Intel Wireless 8260                                                     | 1         | 1.67%   |
| Intel Wireless 3160                                                     | 1         | 1.67%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 1.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 1.67%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 1.67%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 1.67%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 1.67%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 1.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1         | 1.67%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 1         | 1.67%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 1         | 1.67%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 1         | 1.67%   |
| Broadcom BCM4306 802.11b/g Wireless LAN Controller                      | 1         | 1.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 37        | 52.86%  |
| Realtek Semiconductor    | 23        | 32.86%  |
| Broadcom                 | 4         | 5.71%   |
| Qualcomm Atheros         | 2         | 2.86%   |
| Marvell Technology Group | 2         | 2.86%   |
| Xiaomi                   | 1         | 1.43%   |
| Apple                    | 1         | 1.43%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 15        | 20.83%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 7         | 9.72%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 4         | 5.56%   |
| Intel I211 Gigabit Network Connection                                | 3         | 4.17%   |
| Intel I210 Gigabit Network Connection                                | 3         | 4.17%   |
| Intel 82567LM Gigabit Network Connection                             | 3         | 4.17%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                | 2         | 2.78%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet       | 2         | 2.78%   |
| Intel I350 Gigabit Network Connection                                | 2         | 2.78%   |
| Intel Ethernet Connection I219-LM                                    | 2         | 2.78%   |
| Intel Ethernet Connection (3) I218-LM                                | 2         | 2.78%   |
| Intel 82577LM Gigabit Network Connection                             | 2         | 2.78%   |
| Xiaomi Mi/Redmi series (RNDIS)                                       | 1         | 1.39%   |
| Realtek RTL8125 2.5GbE Controller                                    | 1         | 1.39%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                     | 1         | 1.39%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller              | 1         | 1.39%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller              | 1         | 1.39%   |
| Intel I210 Gigabit Fiber Network Connection                          | 1         | 1.39%   |
| Intel Ethernet Controller I225-V                                     | 1         | 1.39%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                        | 1         | 1.39%   |
| Intel Ethernet Connection X553 1GbE                                  | 1         | 1.39%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                     | 1         | 1.39%   |
| Intel Ethernet Connection (7) I219-LM                                | 1         | 1.39%   |
| Intel Ethernet Connection (6) I219-V                                 | 1         | 1.39%   |
| Intel Ethernet Connection (4) I219-V                                 | 1         | 1.39%   |
| Intel Ethernet Connection (14) I219-V                                | 1         | 1.39%   |
| Intel Ethernet Connection (10) I219-V                                | 1         | 1.39%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                 | 1         | 1.39%   |
| Intel 82576 Gigabit Network Connection                               | 1         | 1.39%   |
| Intel 82574L Gigabit Network Connection                              | 1         | 1.39%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller Mobile | 1         | 1.39%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                   | 1         | 1.39%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                    | 1         | 1.39%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                     | 1         | 1.39%   |
| Broadcom NetXtreme BCM5714 Gigabit Ethernet                          | 1         | 1.39%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                      | 1         | 1.39%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                      | 1         | 1.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 66        | 52.8%   |
| WiFi     | 57        | 45.6%   |
| Modem    | 1         | 0.8%    |
| Unknown  | 1         | 0.8%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 40        | 55.56%  |
| Ethernet | 32        | 44.44%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 48        | 62.34%  |
| 1     | 18        | 23.38%  |
| 3     | 5         | 6.49%   |
| 4     | 3         | 3.9%    |
| 12    | 1         | 1.3%    |
| 7     | 1         | 1.3%    |
| 0     | 1         | 1.3%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 77        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 19        | 54.29%  |
| Broadcom                        | 3         | 8.57%   |
| Alps Electric                   | 3         | 8.57%   |
| Realtek Semiconductor           | 2         | 5.71%   |
| Qualcomm Atheros Communications | 2         | 5.71%   |
| ASUSTek Computer                | 2         | 5.71%   |
| Apple                           | 2         | 5.71%   |
| Creative Technology             | 1         | 2.86%   |
| Cambridge Silicon Radio         | 1         | 2.86%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 6         | 17.14%  |
| Intel AX200 Bluetooth                               | 5         | 14.29%  |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 5.71%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 5.71%   |
| Intel AX201 Bluetooth                               | 2         | 5.71%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 5.71%   |
| Alps Electric UGTZ4 Bluetooth                       | 2         | 5.71%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 2.86%   |
| Realtek  Bluetooth 4.0 Adapter                      | 1         | 2.86%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1             | 1         | 2.86%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 2.86%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 2.86%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2.86%   |
| Creative Creative Bluetooth Audio W2                | 1         | 2.86%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.86%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 2.86%   |
| ASUS Broadcom Bluetooth 2.1                         | 1         | 2.86%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 2.86%   |
| Apple Bluetooth Host Controller                     | 1         | 2.86%   |
| Apple Apple Broadcom Built-in Bluetooth             | 1         | 2.86%   |
| Alps Electric BCM2046 Bluetooth Device              | 1         | 2.86%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 53        | 75.71%  |
| AMD                    | 10        | 14.29%  |
| Nvidia                 | 3         | 4.29%   |
| VIA Technologies       | 1         | 1.43%   |
| JMTek                  | 1         | 1.43%   |
| Generalplus Technology | 1         | 1.43%   |
| Creative Labs          | 1         | 1.43%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 8         | 9.88%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 7         | 8.64%   |
| Intel Sunrise Point-LP HD Audio                                                   | 6         | 7.41%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                               | 5         | 6.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 4         | 4.94%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 4         | 4.94%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 4         | 4.94%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 3         | 3.7%    |
| Intel Cannon Point-LP High Definition Audio Controller                            | 3         | 3.7%    |
| Intel Broadwell-U Audio Controller                                                | 3         | 3.7%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 3         | 3.7%    |
| Intel Haswell-ULT HD Audio Controller                                             | 2         | 2.47%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 2         | 2.47%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                 | 2         | 2.47%   |
| Intel Cannon Lake PCH cAVS                                                        | 2         | 2.47%   |
| Intel 8 Series HD Audio Controller                                                | 2         | 2.47%   |
| AMD Starship/Matisse HD Audio Controller                                          | 2         | 2.47%   |
| AMD Navi 10 HDMI Audio                                                            | 2         | 2.47%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                         | 1         | 1.23%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1         | 1.23%   |
| Nvidia TU104 HD Audio Controller                                                  | 1         | 1.23%   |
| Nvidia GT216 HDMI Audio Controller                                                | 1         | 1.23%   |
| JMTek USB PnP Audio Device                                                        | 1         | 1.23%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                   | 1         | 1.23%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 1         | 1.23%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                         | 1         | 1.23%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 1         | 1.23%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 1         | 1.23%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                 | 1         | 1.23%   |
| Intel 82801CA/CAM AC'97 Audio Controller                                          | 1         | 1.23%   |
| Generalplus Technology USB Audio Device                                           | 1         | 1.23%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                     | 1         | 1.23%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 1         | 1.23%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                      | 1         | 1.23%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1         | 1.23%   |

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
| Chicony Electronics   | 11        | 33.33%  |
| Acer                  | 6         | 18.18%  |
| IMC Networks          | 3         | 9.09%   |
| Quanta                | 2         | 6.06%   |
| Microdia              | 2         | 6.06%   |
| Lite-On Technology    | 2         | 6.06%   |
| Syntek                | 1         | 3.03%   |
| Suyin                 | 1         | 3.03%   |
| Silicon Motion        | 1         | 3.03%   |
| Ricoh                 | 1         | 3.03%   |
| Realtek Semiconductor | 1         | 3.03%   |
| Logitech              | 1         | 3.03%   |
| Lenovo                | 1         | 3.03%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 3         | 9.09%   |
| Lite-On Integrated Camera                | 2         | 6.06%   |
| Chicony Ltd., VGA Webcam                 | 2         | 6.06%   |
| Acer Integrated Camera                   | 2         | 6.06%   |
| Acer EasyCamera                          | 2         | 6.06%   |
| Syntek Lenovo EasyCamera                 | 1         | 3.03%   |
| Suyin Acer/Lenovo Webcam [CN0316]        | 1         | 3.03%   |
| Silicon Motion Realtek USB2.0 PC Camera  | 1         | 3.03%   |
| Ricoh Sony Visual Communication Camera   | 1         | 3.03%   |
| Realtek Integrated_Webcam_HD             | 1         | 3.03%   |
| Quanta HP Webcam-50                      | 1         | 3.03%   |
| Quanta HP TrueVision HD Camera           | 1         | 3.03%   |
| Microdia Sonix USB 2.0 Camera            | 1         | 3.03%   |
| Microdia Integrated Webcam HD            | 1         | 3.03%   |
| Logitech HD Pro Webcam C920              | 1         | 3.03%   |
| Lenovo Integrated Webcam                 | 1         | 3.03%   |
| IMC Networks USB2.0 HD UVC WebCam        | 1         | 3.03%   |
| IMC Networks Lenovo EasyCamera           | 1         | 3.03%   |
| IMC Networks Integrated Camera           | 1         | 3.03%   |
| Chicony thinkpad t430s camera            | 1         | 3.03%   |
| Chicony Ltd., Integrated Camera          | 1         | 3.03%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 1         | 3.03%   |
| Chicony Integrated Camera [ThinkPad]     | 1         | 3.03%   |
| Chicony HD Webcam                        | 1         | 3.03%   |
| Chicony 2.0M UVC Webcam / CNF7129        | 1         | 3.03%   |
| Acer SunplusIT Integrated Camera         | 1         | 3.03%   |
| Acer Lenovo Integrated Webcam            | 1         | 3.03%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Synaptics             | 4         | 44.44%  |
| Upek                  | 2         | 22.22%  |
| Validity Sensors      | 1         | 11.11%  |
| Elan Microelectronics | 1         | 11.11%  |
| AuthenTec             | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 22.22%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 22.22%  |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 11.11%  |
| Synaptics product 0x00be                               | 1         | 11.11%  |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 11.11%  |
| Elan ELAN WBF Fingerprint Sensor                       | 1         | 11.11%  |
| AuthenTec AES2810                                      | 1         | 11.11%  |

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
| 1     | 34        | 44.16%  |
| 2     | 20        | 25.97%  |
| 0     | 16        | 20.78%  |
| 3     | 3         | 3.9%    |
| 4     | 2         | 2.6%    |
| 6     | 1         | 1.3%    |
| 5     | 1         | 1.3%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 43        | 45.74%  |
| Graphics card            | 24        | 25.53%  |
| Firewire controller      | 9         | 9.57%   |
| Net/wireless             | 7         | 7.45%   |
| Storage/ata              | 3         | 3.19%   |
| Net/ethernet             | 3         | 3.19%   |
| Sound                    | 2         | 2.13%   |
| Storage/ide              | 1         | 1.06%   |
| Network                  | 1         | 1.06%   |
| Modem                    | 1         | 1.06%   |

