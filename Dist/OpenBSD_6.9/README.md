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
| ASUSTek       | X555LB                      | Notebook    | [e3443d9f27](https://bsd-hardware.info/?probe=e3443d9f27) | Oct 02, 2021 |
| IBM           | ThinkPad H 1846AQG          | Notebook    | [5e5c7247ca](https://bsd-hardware.info/?probe=5e5c7247ca) | Oct 01, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [838a177f57](https://bsd-hardware.info/?probe=838a177f57) | Sep 30, 2021 |
| ASUSTek       | UX305FA                     | Notebook    | [decf219ff2](https://bsd-hardware.info/?probe=decf219ff2) | Sep 30, 2021 |
| HP            | Pro3500 Series              | Desktop     | [abf3223f32](https://bsd-hardware.info/?probe=abf3223f32) | Sep 19, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [7a800aec88](https://bsd-hardware.info/?probe=7a800aec88) | Sep 15, 2021 |
| Dell          | XPS 13 7390 2-in-1          | Notebook    | [577e0ed7fe](https://bsd-hardware.info/?probe=577e0ed7fe) | Sep 13, 2021 |
| NF541         | Unknown                     | Desktop     | [deb29af749](https://bsd-hardware.info/?probe=deb29af749) | Sep 11, 2021 |
| MSI           | MS-7A34                     | Desktop     | [decfe43121](https://bsd-hardware.info/?probe=decfe43121) | Sep 10, 2021 |
| HP            | 250 G5 Notebook PC          | Notebook    | [6e50039406](https://bsd-hardware.info/?probe=6e50039406) | Sep 09, 2021 |
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
| Unknown       | Unknown                     | Desktop     | [cfb0e172cb](https://bsd-hardware.info/?probe=cfb0e172cb) | Jun 27, 2021 |
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

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| amd64  | 71        | 82.56%  |
| i386   | 12        | 13.95%  |
| arm64  | 2         | 2.33%   |
| macppc | 1         | 1.16%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| fvwm    | 67        | 77.91%  |
| Console | 18        | 20.93%  |
| i3      | 1         | 1.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 66        | 76.74%  |
| Console | 20        | 23.26%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 76        | 88.37%  |
| SLiM    | 9         | 10.47%  |
| GDM     | 1         | 1.16%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 68        | 79.07%  |
| en_US   | 12        | 13.95%  |
| ru_RU   | 3         | 3.49%   |
| en_EN   | 1         | 1.16%   |
| de_DE   | 1         | 1.16%   |
| C       | 1         | 1.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 49        | 56.32%  |
| BIOS | 38        | 43.68%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ffs  | 86        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 46        | 52.87%  |
| MBR  | 41        | 47.13%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 23        | 26.74%  |
| Hewlett-Packard                | 11        | 12.79%  |
| ASUSTek Computer               | 9         | 10.47%  |
| Supermicro                     | 5         | 5.81%   |
| Acer                           | 4         | 4.65%   |
| Unknown                        | 4         | 4.65%   |
| PC Engines                     | 3         | 3.49%   |
| Dell                           | 3         | 3.49%   |
| Apple                          | 3         | 3.49%   |
| Panasonic                      | 2         | 2.33%   |
| MSI                            | 2         | 2.33%   |
| Matsushita Electric Industrial | 2         | 2.33%   |
| IBM                            | 2         | 2.33%   |
| Gigabyte Technology            | 2         | 2.33%   |
| ASRock                         | 2         | 2.33%   |
| Standard                       | 1         | 1.16%   |
| Sony                           | 1         | 1.16%   |
| Shuttle                        | 1         | 1.16%   |
| Samsung Electronics            | 1         | 1.16%   |
| NF541                          | 1         | 1.16%   |
| Microsoft                      | 1         | 1.16%   |
| Foxconn                        | 1         | 1.16%   |
| Clevo                          | 1         | 1.16%   |
| Alienware                      | 1         | 1.16%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 5         | 5.81%   |
| Supermicro Super Server                     | 2         | 2.33%   |
| Supermicro X8STi                            | 1         | 1.16%   |
| Supermicro X8DTH-i/6/iF/6F                  | 1         | 1.16%   |
| Supermicro X10SLH-N6-ST031                  | 1         | 1.16%   |
| Standard TF                                 | 1         | 1.16%   |
| Sony VGN-P698E                              | 1         | 1.16%   |
| Shuttle DS77U                               | 1         | 1.16%   |
| Samsung 3570R/370R/470R/450R/510R/4450RV    | 1         | 1.16%   |
| PC Engines apu4                             | 1         | 1.16%   |
| PC Engines APU2                             | 1         | 1.16%   |
| PC Engines apu1                             | 1         | 1.16%   |
| Panasonic CF-53AAGHYDM                      | 1         | 1.16%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 1.16%   |
| MSI MS-7A34                                 | 1         | 1.16%   |
| MSI MS-1613                                 | 1         | 1.16%   |
| Microsoft Surface Pro 7                     | 1         | 1.16%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 1.16%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 1.16%   |
| Lenovo Yoga 6 13ARE05 82FN                  | 1         | 1.16%   |
| Lenovo Yoga 330-11IGM 81A6                  | 1         | 1.16%   |
| Lenovo ThinkPad X280 20KESA000B             | 1         | 1.16%   |
| Lenovo ThinkPad X270 20HNA006ID             | 1         | 1.16%   |
| Lenovo ThinkPad X250 20CM0046US             | 1         | 1.16%   |
| Lenovo ThinkPad X250 20CLS7WY04             | 1         | 1.16%   |
| Lenovo ThinkPad X230 232578G                | 1         | 1.16%   |
| Lenovo ThinkPad X220 4291ON5                | 1         | 1.16%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD00KTMH    | 1         | 1.16%   |
| Lenovo ThinkPad T430 23511A6                | 1         | 1.16%   |
| Lenovo ThinkPad T430 2349U2B                | 1         | 1.16%   |
| Lenovo ThinkPad T430 2347GZU                | 1         | 1.16%   |
| Lenovo ThinkPad T420 4236MBG                | 1         | 1.16%   |
| Lenovo ThinkPad T410 2537N24                | 1         | 1.16%   |
| Lenovo ThinkPad T400 6475P1G                | 1         | 1.16%   |
| Lenovo ThinkPad T400 6475K43                | 1         | 1.16%   |
| Lenovo ThinkPad T400 2767WSB                | 1         | 1.16%   |
| Lenovo ThinkPad T14 Gen 1 20S1S07800        | 1         | 1.16%   |
| Lenovo ThinkPad Edge 05796AU                | 1         | 1.16%   |
| Lenovo ThinkPad E490 20N8CTO1WW             | 1         | 1.16%   |
| Lenovo IdeaPad S210 Touch 20257             | 1         | 1.16%   |
| Lenovo IdeaPad 1 11IGL05 81VT               | 1         | 1.16%   |
| Lenovo FLEX 3-1120 80LX                     | 1         | 1.16%   |
| IBM ThinkPad T42 2374K46                    | 1         | 1.16%   |
| IBM ThinkPad H 1846AQG                      | 1         | 1.16%   |
| HP ProLiant DL360e Gen8                     | 1         | 1.16%   |
| HP ProLiant DL360 Gen9                      | 1         | 1.16%   |
| HP ProLiant DL320 G5                        | 1         | 1.16%   |
| HP ProBook 450 G2                           | 1         | 1.16%   |
| HP Pro3500 Series                           | 1         | 1.16%   |
| HP Pavilion Gaming Laptop 15-ec1xxx         | 1         | 1.16%   |
| HP Pavilion dm1                             | 1         | 1.16%   |
| HP Notebook                                 | 1         | 1.16%   |
| HP EliteDesk 800 G5 SFF                     | 1         | 1.16%   |
| HP 530 Notebook PC(KP477AA#ACB)             | 1         | 1.16%   |
| HP 250 G5 Notebook PC                       | 1         | 1.16%   |
| Gigabyte GA-7VT600                          | 1         | 1.16%   |
| Gigabyte B550I AORUS PRO AX                 | 1         | 1.16%   |
| Foxconn AT-7000 Series                      | 1         | 1.16%   |
| Dell XPS 13 9360                            | 1         | 1.16%   |
| Dell XPS 13 7390 2-in-1                     | 1         | 1.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad                             | 18        | 20.93%  |
| Unknown                                     | 5         | 5.81%   |
| HP ProLiant                                 | 3         | 3.49%   |
| Supermicro Super                            | 2         | 2.33%   |
| Lenovo Yoga                                 | 2         | 2.33%   |
| Lenovo IdeaPad                              | 2         | 2.33%   |
| IBM ThinkPad                                | 2         | 2.33%   |
| HP Pavilion                                 | 2         | 2.33%   |
| Dell XPS                                    | 2         | 2.33%   |
| ASUS ROG                                    | 2         | 2.33%   |
| Supermicro X8STi                            | 1         | 1.16%   |
| Supermicro X8DTH-i                          | 1         | 1.16%   |
| Supermicro X10SLH-N6-ST031                  | 1         | 1.16%   |
| Standard TF                                 | 1         | 1.16%   |
| Sony VGN-P698E                              | 1         | 1.16%   |
| Shuttle DS77U                               | 1         | 1.16%   |
| Samsung 3570R                               | 1         | 1.16%   |
| PC Engines apu4                             | 1         | 1.16%   |
| PC Engines APU2                             | 1         | 1.16%   |
| PC Engines apu1                             | 1         | 1.16%   |
| Panasonic CF-53AAGHYDM                      | 1         | 1.16%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 1.16%   |
| MSI MS-7A34                                 | 1         | 1.16%   |
| MSI MS-1613                                 | 1         | 1.16%   |
| Microsoft Surface                           | 1         | 1.16%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 1.16%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 1.16%   |
| Lenovo FLEX                                 | 1         | 1.16%   |
| HP ProBook                                  | 1         | 1.16%   |
| HP Pro3500                                  | 1         | 1.16%   |
| HP Notebook                                 | 1         | 1.16%   |
| HP EliteDesk                                | 1         | 1.16%   |
| HP 530                                      | 1         | 1.16%   |
| HP 250                                      | 1         | 1.16%   |
| Gigabyte GA-7VT600                          | 1         | 1.16%   |
| Gigabyte B550I                              | 1         | 1.16%   |
| Foxconn AT-7000                             | 1         | 1.16%   |
| Dell Latitude                               | 1         | 1.16%   |
| Clevo W240EU                                | 1         | 1.16%   |
| ASUS X555LB                                 | 1         | 1.16%   |
| ASUS UX430UNR                               | 1         | 1.16%   |
| ASUS UX305FA                                | 1         | 1.16%   |
| ASUS PRIME                                  | 1         | 1.16%   |
| ASUS P10S-I                                 | 1         | 1.16%   |
| ASUS B202                                   | 1         | 1.16%   |
| ASUS 1000HE                                 | 1         | 1.16%   |
| ASRock Z68                                  | 1         | 1.16%   |
| ASRock X570M                                | 1         | 1.16%   |
| Apple PowerBook5                            | 1         | 1.16%   |
| Apple MacBookPro6                           | 1         | 1.16%   |
| Apple MacBookAir6                           | 1         | 1.16%   |
| Alienware Aurora                            | 1         | 1.16%   |
| Acer Spin                                   | 1         | 1.16%   |
| Acer Aspire                                 | 1         | 1.16%   |
| Acer AOA150                                 | 1         | 1.16%   |
| Acer AO531h                                 | 1         | 1.16%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 17        | 19.77%  |
| 2021    | 12        | 13.95%  |
| 2019    | 11        | 12.79%  |
| 2018    | 8         | 9.3%    |
| 2008    | 5         | 5.81%   |
| Unknown | 5         | 5.81%   |
| 2013    | 4         | 4.65%   |
| 2012    | 4         | 4.65%   |
| 2017    | 3         | 3.49%   |
| 2010    | 3         | 3.49%   |
| 2015    | 2         | 2.33%   |
| 2014    | 2         | 2.33%   |
| 2011    | 2         | 2.33%   |
| 2009    | 2         | 2.33%   |
| 2006    | 2         | 2.33%   |
| 2016    | 1         | 1.16%   |
| 2005    | 1         | 1.16%   |
| 2003    | 1         | 1.16%   |
| 2002    | 1         | 1.16%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 55        | 63.95%  |
| Desktop  | 28        | 32.56%  |
| Server   | 2         | 2.33%   |
| Tablet   | 1         | 1.16%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 81        | 94.19%  |
| Yes  | 5         | 5.81%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 21        | 24.42%  |
| 16.01-24.0  | 17        | 19.77%  |
| 4.01-8.0    | 16        | 18.6%   |
| 3.01-4.0    | 8         | 9.3%    |
| 2.01-3.0    | 8         | 9.3%    |
| 32.01-64.0  | 4         | 4.65%   |
| 1.01-2.0    | 4         | 4.65%   |
| 0.51-1.0    | 4         | 4.65%   |
| 24.01-32.0  | 2         | 2.33%   |
| 64.01-256.0 | 2         | 2.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 70        | 81.4%   |
| 0        | 6         | 6.98%   |
| 0.51-1.0 | 5         | 5.81%   |
| 1.01-2.0 | 2         | 2.33%   |
| Unknown  | 2         | 2.33%   |
| 4.01-8.0 | 1         | 1.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 49        | 56.32%  |
| 2      | 23        | 26.44%  |
| 3      | 5         | 5.75%   |
| 4      | 4         | 4.6%    |
| 6      | 2         | 2.3%    |
| 5      | 2         | 2.3%    |
| 7      | 1         | 1.15%   |
| 0      | 1         | 1.15%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 86        | 100%    |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 73        | 84.88%  |
| No        | 13        | 15.12%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 64        | 74.42%  |
| No        | 22        | 25.58%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 47        | 54.65%  |
| Yes       | 39        | 45.35%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 23        | 26.74%  |
| Germany      | 11        | 12.79%  |
| Canada       | 9         | 10.47%  |
| Russia       | 7         | 8.14%   |
| France       | 6         | 6.98%   |
| Netherlands  | 5         | 5.81%   |
| Ukraine      | 3         | 3.49%   |
| Sweden       | 3         | 3.49%   |
| UK           | 2         | 2.33%   |
| Spain        | 2         | 2.33%   |
| Portugal     | 2         | 2.33%   |
| Latvia       | 2         | 2.33%   |
| Turkey       | 1         | 1.16%   |
| Taiwan       | 1         | 1.16%   |
| Switzerland  | 1         | 1.16%   |
| Saudi Arabia | 1         | 1.16%   |
| Poland       | 1         | 1.16%   |
| Philippines  | 1         | 1.16%   |
| Norway       | 1         | 1.16%   |
| Malaysia     | 1         | 1.16%   |
| Indonesia    | 1         | 1.16%   |
| Chile        | 1         | 1.16%   |
| Brazil       | 1         | 1.16%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Saint-Laurent         | 7         | 8.05%   |
| Moscow                | 4         | 4.6%    |
| Yekaterinburg         | 2         | 2.3%    |
| Riga                  | 2         | 2.3%    |
| Papillion             | 2         | 2.3%    |
| Los Angeles           | 2         | 2.3%    |
| Brooklyn              | 2         | 2.3%    |
| Bielefeld             | 2         | 2.3%    |
| Berlin                | 2         | 2.3%    |
| Barneveld             | 2         | 2.3%    |
| 's-Hertogenbosch      | 2         | 2.3%    |
| Wolfsburg             | 1         | 1.15%   |
| Wittersham            | 1         | 1.15%   |
| Watford               | 1         | 1.15%   |
| Victoria              | 1         | 1.15%   |
| Vechta                | 1         | 1.15%   |
| Van Nuys              | 1         | 1.15%   |
| Valdivia              | 1         | 1.15%   |
| Vacaville             | 1         | 1.15%   |
| Teriang               | 1         | 1.15%   |
| São Paulo            | 1         | 1.15%   |
| Syeverodonets'k       | 1         | 1.15%   |
| Surabaya              | 1         | 1.15%   |
| Spokane               | 1         | 1.15%   |
| Solna                 | 1         | 1.15%   |
| Soeraker              | 1         | 1.15%   |
| Sedavi                | 1         | 1.15%   |
| Sechelt               | 1         | 1.15%   |
| Sammamish             | 1         | 1.15%   |
| Saint-Martin-d'Hères | 1         | 1.15%   |
| Roubaix               | 1         | 1.15%   |
| Roseville             | 1         | 1.15%   |
| Rodgau                | 1         | 1.15%   |
| Riyadh                | 1         | 1.15%   |
| Quezon City           | 1         | 1.15%   |
| Plainfield            | 1         | 1.15%   |
| Onalaska              | 1         | 1.15%   |
| Oensingen             | 1         | 1.15%   |
| Oeiras                | 1         | 1.15%   |
| New York              | 1         | 1.15%   |
| New Taipei            | 1         | 1.15%   |
| Neuilly-sur-Marne     | 1         | 1.15%   |
| Monts                 | 1         | 1.15%   |
| Miedziana Gora        | 1         | 1.15%   |
| McLeod                | 1         | 1.15%   |
| Madrid                | 1         | 1.15%   |
| Kyiv                  | 1         | 1.15%   |
| Korolyov              | 1         | 1.15%   |
| Independence          | 1         | 1.15%   |
| Hoeviksnaes           | 1         | 1.15%   |
| Hockenheim            | 1         | 1.15%   |
| Heilbronn             | 1         | 1.15%   |
| Hamilton              | 1         | 1.15%   |
| Greensburg            | 1         | 1.15%   |
| Frankfurt am Main     | 1         | 1.15%   |
| Estoril               | 1         | 1.15%   |
| Donetsk               | 1         | 1.15%   |
| Dallas                | 1         | 1.15%   |
| Covington             | 1         | 1.15%   |
| Corbarieu             | 1         | 1.15%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| NVMe                | 18        | 20     | 16.82%  |
| WDC                 | 15        | 16     | 14.02%  |
| Samsung Electronics | 15        | 20     | 14.02%  |
| Seagate             | 8         | 14     | 7.48%   |
| Toshiba             | 5         | 5      | 4.67%   |
| SanDisk             | 4         | 4      | 3.74%   |
| OPENBSD             | 4         | 4      | 3.74%   |
| HGST                | 4         | 5      | 3.74%   |
| Crucial             | 4         | 4      | 3.74%   |
| Intel               | 3         | 4      | 2.8%    |
| Hitachi             | 3         | 3      | 2.8%    |
| SK Hynix            | 2         | 2      | 1.87%   |
| Kingston            | 2         | 2      | 1.87%   |
| Hewlett-Packard     | 2         | 6      | 1.87%   |
| Zheino              | 1         | 1      | 0.93%   |
| USB                 | 1         | 1      | 0.93%   |
| UDinfo              | 1         | 1      | 0.93%   |
| Transcend           | 1         | 4      | 0.93%   |
| Team                | 1         | 1      | 0.93%   |
| SPCC                | 1         | 1      | 0.93%   |
| Product:            | 1         | 1      | 0.93%   |
| Phison              | 1         | 1      | 0.93%   |
| Patriot             | 1         | 1      | 0.93%   |
| Netac               | 1         | 1      | 0.93%   |
| Multiple            | 1         | 1      | 0.93%   |
| Micron Technology   | 1         | 1      | 0.93%   |
| MEMXPRO             | 1         | 1      | 0.93%   |
| LSI                 | 1         | 1      | 0.93%   |
| Fujitsu             | 1         | 1      | 0.93%   |
| asmedia             | 1         | 1      | 0.93%   |
| Apple               | 1         | 1      | 0.93%   |
| A-DATA Technology   | 1         | 1      | 0.93%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| OPENBSD SR RAID 1 240GB           | 4         | 3.36%   |
| WDC WD1600BEVT-22ZCT0 160GB       | 3         | 2.52%   |
| Samsung SSD 850 EVO 250GB         | 3         | 2.52%   |
| NVMe Samsung SSD 960 500GB        | 3         | 2.52%   |
| NVMe WDC PC SN730 SDB 1TB         | 2         | 1.68%   |
| NVMe Samsung SSD 970 250GB        | 2         | 1.68%   |
| NVMe SAMSUNG MZVLB256 256GB       | 2         | 1.68%   |
| HGST HUS724020ALA640 2TB          | 2         | 1.68%   |
| Zheino CHN-mSATAQ3-120 120GB      | 1         | 0.84%   |
| WDC WDS500G2B0A-00SM50 500GB      | 1         | 0.84%   |
| WDC WD80EFAX-68KNBN0 8TB          | 1         | 0.84%   |
| WDC WD7500BPKX-00HPJT0 752GB      | 1         | 0.84%   |
| WDC WD7500BPKT-00PK4T0 752GB      | 1         | 0.84%   |
| WDC WD60EFRX-68L0BN1 6TB          | 1         | 0.84%   |
| WDC WD5000LPLX-00ZNTT0 500GB      | 1         | 0.84%   |
| WDC WD5000LPCX-24C6HT0 500GB      | 1         | 0.84%   |
| WDC WD3200BEVE-00A0HT0 320GB      | 1         | 0.84%   |
| WDC WD3200BEKT-08PVMT1 320GB      | 1         | 0.84%   |
| WDC WD20PURX-64P6ZY0 2TB          | 1         | 0.84%   |
| WDC WD10SPCX-24HWST1 1TB          | 1         | 0.84%   |
| WDC WD10JPLX-00MBPT0 1TB          | 1         | 0.84%   |
| WDC WD Elements 25A3 4TB          | 1         | 0.84%   |
| USB SanDisk 3.2Gen1 16GB          | 1         | 0.84%   |
| UDinfo M2S 120GB                  | 1         | 0.84%   |
| Transcend 3E128-TS2-550B01 100GB  | 1         | 0.84%   |
| Toshiba MQ04ABF100 1TB            | 1         | 0.84%   |
| Toshiba MK8025GAS 80GB            | 1         | 0.84%   |
| Toshiba MK3256GSY 320GB           | 1         | 0.84%   |
| Toshiba MK1665GSX 160GB           | 1         | 0.84%   |
| Toshiba DT01ACA100 1TB            | 1         | 0.84%   |
| Team T253X2001T 1TB               | 1         | 0.84%   |
| SPCC Solid State Disk 128GB       | 1         | 0.84%   |
| SK Hynix SC311 SATA 256GB         | 1         | 0.84%   |
| SK Hynix HFS128G39TND-N210A 128GB | 1         | 0.84%   |
| Seagate ST950032 5AS 500GB        | 1         | 0.84%   |
| Seagate ST9160821A 160GB          | 1         | 0.84%   |
| Seagate ST9160310AS 160GB         | 1         | 0.84%   |
| Seagate ST500LT012-9WS142 500GB   | 1         | 0.84%   |
| Seagate ST3808110AS 80GB          | 1         | 0.84%   |
| Seagate ST380011A 80GB            | 1         | 0.84%   |
| Seagate ST3160212ACE 160GB        | 1         | 0.84%   |
| Seagate ST2000LX001-1RG174 2TB    | 1         | 0.84%   |
| Seagate ST1000LM048-2E7172 1TB    | 1         | 0.84%   |
| Seagate ST1000DM003-9YN162 1TB    | 1         | 0.84%   |
| Seagate ST1000DM003-1CH162 1TB    | 1         | 0.84%   |
| Seagate Backup+ SL 1TB            | 1         | 0.84%   |
| SanDisk Ultra Fit 16GB            | 1         | 0.84%   |
| SanDisk Ultra 32GB                | 1         | 0.84%   |
| SanDisk SSD PLUS 120GB            | 1         | 0.84%   |
| SanDisk SD7SN3Q128G1002 128GB     | 1         | 0.84%   |
| Samsung SSD 860 PRO 256GB         | 1         | 0.84%   |
| Samsung SSD 860 EVO M.2 2TB       | 1         | 0.84%   |
| Samsung SSD 860 EVO M.2 250GB     | 1         | 0.84%   |
| Samsung SSD 860 EVO M.2 1TB       | 1         | 0.84%   |
| Samsung SSD 860 EVO 2TB           | 1         | 0.84%   |
| Samsung SSD 860 EVO 1TB           | 1         | 0.84%   |
| Samsung SSD 850 PRO 256GB         | 1         | 0.84%   |
| Samsung SSD 850 EVO 500GB         | 1         | 0.84%   |
| Samsung SSD 850 EVO 120GB         | 1         | 0.84%   |
| Samsung SSD 840 Series 120GB      | 1         | 0.84%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 14        | 15     | 23.73%  |
| NVMe                | 12        | 13     | 20.34%  |
| Seagate             | 8         | 14     | 13.56%  |
| Toshiba             | 5         | 5      | 8.47%   |
| OPENBSD             | 4         | 4      | 6.78%   |
| HGST                | 4         | 5      | 6.78%   |
| Hitachi             | 3         | 3      | 5.08%   |
| Samsung Electronics | 2         | 2      | 3.39%   |
| Hewlett-Packard     | 2         | 6      | 3.39%   |
| USB                 | 1         | 1      | 1.69%   |
| Product:            | 1         | 1      | 1.69%   |
| Multiple            | 1         | 1      | 1.69%   |
| LSI                 | 1         | 1      | 1.69%   |
| Fujitsu             | 1         | 1      | 1.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 14        | 18     | 28.57%  |
| NVMe                | 6         | 6      | 12.24%  |
| SanDisk             | 4         | 4      | 8.16%   |
| Crucial             | 4         | 4      | 8.16%   |
| Intel               | 3         | 4      | 6.12%   |
| SK Hynix            | 2         | 2      | 4.08%   |
| Kingston            | 2         | 2      | 4.08%   |
| Zheino              | 1         | 1      | 2.04%   |
| WDC                 | 1         | 1      | 2.04%   |
| UDinfo              | 1         | 1      | 2.04%   |
| Transcend           | 1         | 4      | 2.04%   |
| Team                | 1         | 1      | 2.04%   |
| SPCC                | 1         | 1      | 2.04%   |
| Phison              | 1         | 1      | 2.04%   |
| Patriot             | 1         | 1      | 2.04%   |
| Netac               | 1         | 1      | 2.04%   |
| Micron Technology   | 1         | 1      | 2.04%   |
| MEMXPRO             | 1         | 1      | 2.04%   |
| asmedia             | 1         | 1      | 2.04%   |
| Apple               | 1         | 1      | 2.04%   |
| A-DATA Technology   | 1         | 1      | 2.04%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 48        | 72     | 51.61%  |
| SSD  | 44        | 57     | 47.31%  |
| NVMe | 1         | 1      | 1.08%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 81        | 129    | 98.78%  |
| NVMe | 1         | 1      | 1.22%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 64        | 89     | 69.57%  |
| 0.51-1.0        | 16        | 23     | 17.39%  |
| 1.01-2.0        | 8         | 12     | 8.7%    |
| 4.01-10.0       | 2         | 3      | 2.17%   |
| More than 100.0 | 1         | 1      | 1.09%   |
| 3.01-4.0        | 1         | 1      | 1.09%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 32        | 37.21%  |
| 251-500        | 23        | 26.74%  |
| 51-100         | 10        | 11.63%  |
| 21-50          | 8         | 9.3%    |
| 1-20           | 6         | 6.98%   |
| More than 3000 | 4         | 4.65%   |
| 501-1000       | 2         | 2.33%   |
| 1001-2000      | 1         | 1.16%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 64        | 73.56%  |
| 21-50     | 7         | 8.05%   |
| 51-100    | 6         | 6.9%    |
| 101-250   | 5         | 5.75%   |
| 251-500   | 2         | 2.3%    |
| 1001-2000 | 2         | 2.3%    |
| 501-1000  | 1         | 1.15%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| WDC WD1600BEVT-22ZCT0 160GB      | 1         | 1      | 11.11%  |
| Transcend 3E128-TS2-550B01 100GB | 1         | 4      | 11.11%  |
| Seagate ST9160310AS 160GB        | 1         | 2      | 11.11%  |
| Seagate ST500LT012-9WS142 500GB  | 1         | 1      | 11.11%  |
| Seagate ST1000DM003-1CH162 1TB   | 1         | 1      | 11.11%  |
| HGST HTS541010A7E630 1TB         | 1         | 2      | 11.11%  |
| HGST HTE725032A7E630 320GB       | 1         | 1      | 11.11%  |
| Apple SSD SD0128F 121GB          | 1         | 1      | 11.11%  |
| A-DATA Technology SP550 480GB    | 1         | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 3         | 4      | 33.33%  |
| HGST              | 2         | 3      | 22.22%  |
| WDC               | 1         | 1      | 11.11%  |
| Transcend         | 1         | 4      | 11.11%  |
| Apple             | 1         | 1      | 11.11%  |
| A-DATA Technology | 1         | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 4      | 50%     |
| HGST    | 2         | 3      | 33.33%  |
| WDC     | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 8      | 66.67%  |
| SSD  | 3         | 6      | 33.33%  |

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

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 60        | 86     | 65.22%  |
| Detected | 23        | 30     | 25%     |
| Malfunc  | 9         | 14     | 9.78%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 59        | 60.82%  |
| AMD                      | 12        | 12.37%  |
| Samsung Electronics      | 8         | 8.25%   |
| Sandisk                  | 4         | 4.12%   |
| KIOXIA                   | 3         | 3.09%   |
| Marvell Technology Group | 2         | 2.06%   |
| Hewlett-Packard          | 2         | 2.06%   |
| Broadcom / LSI           | 2         | 2.06%   |
| VIA Technologies         | 1         | 1.03%   |
| Toshiba                  | 1         | 1.03%   |
| SK Hynix                 | 1         | 1.03%   |
| Silicon Image            | 1         | 1.03%   |
| Phison Electronics       | 1         | 1.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 8         | 7.48%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 7         | 6.54%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 6         | 5.61%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 5         | 4.67%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 5         | 4.67%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 3         | 2.8%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3         | 2.8%    |
| KIOXIA unknown                                                                          | 3         | 2.8%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 3         | 2.8%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 3         | 2.8%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3         | 2.8%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 3         | 2.8%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 2         | 1.87%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2         | 1.87%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 2         | 1.87%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2         | 1.87%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2         | 1.87%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 2         | 1.87%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 2         | 1.87%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2         | 1.87%   |
| AMD 400 Series Chipset SATA Controller                                                  | 2         | 1.87%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 1         | 0.93%   |
| Toshiba BG3 NVMe SSD Controller                                                         | 1         | 0.93%   |
| SK Hynix BC511                                                                          | 1         | 0.93%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                        | 1         | 0.93%   |
| Sandisk WD Black SN850                                                                  | 1         | 0.93%   |
| Phison E12 NVMe Controller                                                              | 1         | 0.93%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                              | 1         | 0.93%   |
| Marvell Group 88SE912x SATA 6Gb/s Controller [IDE mode]                                 | 1         | 0.93%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                              | 1         | 0.93%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                 | 1         | 0.93%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1         | 0.93%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1         | 0.93%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1         | 0.93%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 1         | 0.93%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1         | 0.93%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 1         | 0.93%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 1         | 0.93%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1         | 0.93%   |
| Intel Atom Processor C3000 Series SATA Controller 1                                     | 1         | 0.93%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 1         | 0.93%   |
| Intel 82801FBM (ICH6M) SATA Controller                                                  | 1         | 0.93%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                                  | 1         | 0.93%   |
| Intel 82801CAM IDE U100 Controller                                                      | 1         | 0.93%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 1         | 0.93%   |
| Intel 7 Series/C210 Series Chipset Family IDE-r Controller                              | 1         | 0.93%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                              | 1         | 0.93%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 0.93%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 0.93%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1         | 0.93%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1         | 0.93%   |
| HP Smart Array Gen9 Controllers                                                         | 1         | 0.93%   |
| HP Smart Array G6 controllers                                                           | 1         | 0.93%   |
| Broadcom / LSI SSS6200 PCI-Express Flash SSD                                            | 1         | 0.93%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 1         | 0.93%   |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                          | 1         | 0.93%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1         | 0.93%   |
| AMD 300 Series Chipset SATA Controller                                                  | 1         | 0.93%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 59        | 59%     |
| NVMe | 18        | 18%     |
| IDE  | 17        | 17%     |
| RAID | 4         | 4%      |
| SAS  | 2         | 2%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 69        | 80.23%  |
| AMD     | 14        | 16.28%  |
| ARM     | 2         | 2.33%   |
| Unknown | 1         | 1.16%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Core i5-3320M CPU @ 2.60GHz                             | 3         | 3.49%   |
| Intel Atom CPU N270 @ 1.60GHz ("GenuineIntel" 686-class)      | 3         | 3.49%   |
| Intel Core i7-8565U CPU @ 1.80GHz                             | 2         | 2.33%   |
| Intel Core i7-7500U CPU @ 2.70GHz                             | 2         | 2.33%   |
| Intel Core i5-5300U CPU @ 2.30GHz                             | 2         | 2.33%   |
| Intel Core i5-2520M CPU @ 2.50GHz                             | 2         | 2.33%   |
| Intel Core i5 CPU M 520 @ 2.40GHz                             | 2         | 2.33%   |
| Intel Core i3-5005U CPU @ 2.00GHz                             | 2         | 2.33%   |
| ARM Cortex-A53 r0p4                                           | 2         | 2.33%   |
| AMD GX-412TC SOC                                              | 2         | 2.33%   |
| Intel Xeon CPU X5675 @ 3.07GHz                                | 1         | 1.16%   |
| Intel Xeon CPU W3530 @ 2.80GHz                                | 1         | 1.16%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz                           | 1         | 1.16%   |
| Intel Xeon CPU E5-2407 0 @ 2.20GHz                            | 1         | 1.16%   |
| Intel Xeon CPU E3-1270 v3 @ 3.50GHz                           | 1         | 1.16%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz                           | 1         | 1.16%   |
| Intel Xeon CPU D-1521 @ 2.40GHz                               | 1         | 1.16%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz                      | 1         | 1.16%   |
| Intel Pentium M processor 2.00GHz ("GenuineIntel" 686-class)  | 1         | 1.16%   |
| Intel Pentium M processor 1.86GHz ("GenuineIntel" 686-class)  | 1         | 1.16%   |
| Intel Pentium CPU N4200 @ 1.10GHz                             | 1         | 1.16%   |
| Intel Pentium 4 Mobile CPU 1.60GHz ("GenuineIntel" 686-class) | 1         | 1.16%   |
| Intel CPU T2300 @ 1.66GHz ("GenuineIntel" 686-class)          | 1         | 1.16%   |
| Intel Core M-5Y10c CPU @ 0.80GHz                              | 1         | 1.16%   |
| Intel Core i7-8750H CPU @ 2.20GHz                             | 1         | 1.16%   |
| Intel Core i7-8550U CPU @ 1.80GHz                             | 1         | 1.16%   |
| Intel Core i7-3520M CPU @ 2.90GHz                             | 1         | 1.16%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz                            | 1         | 1.16%   |
| Intel Core i7-10510U CPU @ 1.80GHz                            | 1         | 1.16%   |
| Intel Core i7 CPU M 620 @ 2.67GHz                             | 1         | 1.16%   |
| Intel Core i5-9500 CPU @ 3.00GHz                              | 1         | 1.16%   |
| Intel Core i5-8350U CPU @ 1.70GHz                             | 1         | 1.16%   |
| Intel Core i5-8265U CPU @ 1.60GHz                             | 1         | 1.16%   |
| Intel Core i5-6300U CPU @ 2.40GHz                             | 1         | 1.16%   |
| Intel Core i5-5200U CPU @ 2.20GHz                             | 1         | 1.16%   |
| Intel Core i5-4250U CPU @ 1.30GHz                             | 1         | 1.16%   |
| Intel Core i5-3470 CPU @ 3.20GHz                              | 1         | 1.16%   |
| Intel Core i5-3230M CPU @ 2.60GHz                             | 1         | 1.16%   |
| Intel Core i5-2540M CPU @ 2.60GHz                             | 1         | 1.16%   |
| Intel Core i5-2500K CPU @ 3.30GHz                             | 1         | 1.16%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz                            | 1         | 1.16%   |
| Intel Core i3-4005U CPU @ 1.70GHz                             | 1         | 1.16%   |
| Intel Core i3-3217U CPU @ 1.80GHz                             | 1         | 1.16%   |
| Intel Core i3-3130M CPU @ 2.60GHz                             | 1         | 1.16%   |
| Intel Core i3-2375M CPU @ 1.50GHz                             | 1         | 1.16%   |
| Intel Core i3 CPU M 380 @ 2.53GHz                             | 1         | 1.16%   |
| Intel Core Duo CPU T2600 @ 2.16GHz ("GenuineIntel" 686-class) | 1         | 1.16%   |
| Intel Core 2 Duo CPU T9900 @ 3.06GHz                          | 1         | 1.16%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz                          | 1         | 1.16%   |
| Intel Core 2 Duo CPU P9700 @ 2.80GHz                          | 1         | 1.16%   |
| Intel Celeron N4020 CPU @ 1.10GHz                             | 1         | 1.16%   |
| Intel Celeron M CPU 430 @ 1.73GHz ("GenuineIntel" 686-class)  | 1         | 1.16%   |
| Intel Celeron D CPU 3.20GHz                                   | 1         | 1.16%   |
| Intel Celeron CPU N3350 @ 1.10GHz                             | 1         | 1.16%   |
| Intel Celeron CPU N2840 @ 2.16GHz                             | 1         | 1.16%   |
| Intel Celeron CPU J1900 @ 1.99GHz                             | 1         | 1.16%   |
| Intel Celeron CPU 3865U @ 1.80GHz                             | 1         | 1.16%   |
| Intel Atom CPU Z530 @ 1.60GHz ("GenuineIntel" 686-class)      | 1         | 1.16%   |
| Intel Atom CPU N280 @ 1.66GHz ("GenuineIntel" 686-class)      | 1         | 1.16%   |
| Intel Atom CPU C3558 @ 2.20GHz                                | 1         | 1.16%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 20        | 23.26%  |
| Intel Core i7        | 10        | 11.63%  |
| Intel Xeon           | 7         | 8.14%   |
| Intel Core i3        | 7         | 8.14%   |
| Intel Atom           | 6         | 6.98%   |
| AMD Ryzen 7          | 6         | 6.98%   |
| Intel Celeron        | 5         | 5.81%   |
| Other                | 3         | 3.49%   |
| Intel Core 2 Duo     | 3         | 3.49%   |
| Intel Pentium M      | 2         | 2.33%   |
| ARM Cortex           | 2         | 2.33%   |
| AMD GX               | 2         | 2.33%   |
| Intel Pentium Silver | 1         | 1.16%   |
| Intel Pentium 4      | 1         | 1.16%   |
| Intel Pentium        | 1         | 1.16%   |
| Intel Core M         | 1         | 1.16%   |
| Intel Core Duo       | 1         | 1.16%   |
| Intel Celeron M      | 1         | 1.16%   |
| Intel Celeron D      | 1         | 1.16%   |
| AMD Ryzen 7 PRO      | 1         | 1.16%   |
| AMD Ryzen 5 PRO      | 1         | 1.16%   |
| AMD Ryzen 5          | 1         | 1.16%   |
| AMD G                | 1         | 1.16%   |
| AMD Athlon XP        | 1         | 1.16%   |
| AMD Athlon II Neo    | 1         | 1.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 32        | 37.21%  |
| 4       | 21        | 24.42%  |
| Unknown | 14        | 16.28%  |
| 16      | 6         | 6.98%   |
| 1       | 6         | 6.98%   |
| 6       | 5         | 5.81%   |
| 12      | 2         | 2.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 67        | 77.91%  |
| Unknown | 19        | 22.09%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 41        | 47.67%  |
| 1       | 26        | 30.23%  |
| Unknown | 19        | 22.09%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 11        | 12.79%  |
| IvyBridge     | 8         | 9.3%    |
| Broadwell     | 7         | 8.14%   |
| SandyBridge   | 6         | 6.98%   |
| Unknown       | 6         | 6.98%   |
| Zen 2         | 5         | 5.81%   |
| Westmere      | 5         | 5.81%   |
| Bonnell       | 5         | 5.81%   |
| P6            | 4         | 4.65%   |
| Haswell       | 4         | 4.65%   |
| Penryn        | 3         | 3.49%   |
| Goldmont      | 3         | 3.49%   |
| Zen 3         | 2         | 2.33%   |
| Skylake       | 2         | 2.33%   |
| Silvermont    | 2         | 2.33%   |
| Puma          | 2         | 2.33%   |
| IceLake       | 2         | 2.33%   |
| Goldmont plus | 2         | 2.33%   |
| Zen+          | 1         | 1.16%   |
| Zen           | 1         | 1.16%   |
| NetBurst      | 1         | 1.16%   |
| Nehalem       | 1         | 1.16%   |
| K6            | 1         | 1.16%   |
| K10           | 1         | 1.16%   |
| Bobcat        | 1         | 1.16%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 56        | 61.54%  |
| AMD                        | 18        | 19.78%  |
| Nvidia                     | 9         | 9.89%   |
| Matrox Electronics Systems | 4         | 4.4%    |
| ASPEED Technology          | 4         | 4.4%    |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                              | Computers | Percent |
|------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller      | 7         | 7.07%   |
| Intel 3rd Gen Core processor Graphics Controller                                   | 7         | 7.07%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                         | 5         | 5.05%   |
| Intel HD Graphics 5500                                                             | 5         | 5.05%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller          | 5         | 5.05%   |
| Intel Core Processor Integrated Graphics Controller                                | 4         | 4.04%   |
| ASPEED Technology ASPEED Graphics Family                                           | 4         | 4.04%   |
| AMD Renoir                                                                         | 4         | 4.04%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                         | 3         | 3.03%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                       | 3         | 3.03%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                      | 2         | 2.02%   |
| Matrox Electronics Systems MGA G200EH                                              | 2         | 2.02%   |
| Intel UHD Graphics 620                                                             | 2         | 2.02%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller          | 2         | 2.02%   |
| Intel HD Graphics 620                                                              | 2         | 2.02%   |
| Intel Haswell-ULT Integrated Graphics Controller                                   | 2         | 2.02%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                       | 2         | 2.02%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                                | 2         | 2.02%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                            | 2         | 2.02%   |
| Nvidia TU117M                                                                      | 1         | 1.01%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                             | 1         | 1.01%   |
| Nvidia GT216M [GeForce GT 330M]                                                    | 1         | 1.01%   |
| Nvidia GP108M [GeForce MX330]                                                      | 1         | 1.01%   |
| Nvidia GP108M [GeForce MX150]                                                      | 1         | 1.01%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                            | 1         | 1.01%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                | 1         | 1.01%   |
| Nvidia GM204 [GeForce GTX 970]                                                     | 1         | 1.01%   |
| Nvidia GM108M [GeForce 940M]                                                       | 1         | 1.01%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                   | 1         | 1.01%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                | 1         | 1.01%   |
| Intel Skylake GT2 [HD Graphics 520]                                                | 1         | 1.01%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                               | 1         | 1.01%   |
| Intel Iris Plus Graphics G7                                                        | 1         | 1.01%   |
| Intel Iris Plus Graphics G4 (Ice Lake)                                             | 1         | 1.01%   |
| Intel HD Graphics 5300                                                             | 1         | 1.01%   |
| Intel HD Graphics 500                                                              | 1         | 1.01%   |
| Intel GeminiLake [UHD Graphics 605]                                                | 1         | 1.01%   |
| Intel GeminiLake [UHD Graphics 600]                                                | 1         | 1.01%   |
| Intel CometLake-U GT2 [UHD Graphics]                                               | 1         | 1.01%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                           | 1         | 1.01%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                          | 1         | 1.01%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller | 1         | 1.01%   |
| AMD RV370/M22 [Mobility Radeon X300]                                               | 1         | 1.01%   |
| AMD RV350/M10 / RV360/M11 [Mobility Radeon 9600 (PRO) / 9700]                      | 1         | 1.01%   |
| AMD RV280 [Radeon 9200 PRO] (Secondary)                                            | 1         | 1.01%   |
| AMD RV280 [Radeon 9200 PRO / 9250]                                                 | 1         | 1.01%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                          | 1         | 1.01%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                   | 1         | 1.01%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                         | 1         | 1.01%   |
| AMD ES1000                                                                         | 1         | 1.01%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                            | 1         | 1.01%   |
| AMD Cezanne                                                                        | 1         | 1.01%   |
| AMD Caicos PRO [Radeon HD 7450]                                                    | 1         | 1.01%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 38        | 44.19%  |
| 1 x AMD        | 13        | 15.12%  |
| 2 x Intel      | 10        | 11.63%  |
| Intel + Nvidia | 6         | 6.98%   |
| Other          | 5         | 5.81%   |
| 1 x ASPEED     | 4         | 4.65%   |
| 1 x Matrox     | 3         | 3.49%   |
| 1 x Nvidia     | 2         | 2.33%   |
| Intel + AMD    | 2         | 2.33%   |
| 2 x AMD        | 1         | 1.16%   |
| AMD + Nvidia   | 1         | 1.16%   |
| AMD + Matrox   | 1         | 1.16%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 71        | 82.56%  |
| Unknown | 15        | 17.44%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 86        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 10        | 20.83%  |
| LG Display              | 7         | 14.58%  |
| BOE                     | 5         | 10.42%  |
| Dell                    | 4         | 8.33%   |
| Samsung Electronics     | 3         | 6.25%   |
| Lenovo                  | 3         | 6.25%   |
| Sharp                   | 2         | 4.17%   |
| Chimei Innolux          | 2         | 4.17%   |
| Apple                   | 2         | 4.17%   |
| Vizio                   | 1         | 2.08%   |
| Philips                 | 1         | 2.08%   |
| LG Philips              | 1         | 2.08%   |
| InfoVision              | 1         | 2.08%   |
| Goldstar                | 1         | 2.08%   |
| Eizo                    | 1         | 2.08%   |
| Chi Mei Optoelectronics | 1         | 2.08%   |
| ASUSTek Computer        | 1         | 2.08%   |
| AOC                     | 1         | 2.08%   |
| Ancor Communications    | 1         | 2.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 2         | 4.17%   |
| Vizio E320i-A0 VIZ0091 1366x768 700x390mm 31.5-inch                      | 1         | 2.08%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 340x190mm 15.3-inch                  | 1         | 2.08%   |
| Sharp LCD Monitor SHP1449 1920x1080 290x170mm 13.2-inch                  | 1         | 2.08%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch     | 1         | 2.08%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 310x170mm 13.9-inch     | 1         | 2.08%   |
| Samsung Electronics LCD Monitor SDC374A 3200x1800 290x170mm 13.2-inch    | 1         | 2.08%   |
| Philips PHL 276E8V PHLC18F 3840x2160 600x340mm 27.2-inch                 | 1         | 2.08%   |
| LG Philips LCD Monitor LPLDB00 1280x800 330x210mm 15.4-inch              | 1         | 2.08%   |
| LG Display LCD Monitor LGD05D8 1920x1080 340x190mm 15.3-inch             | 1         | 2.08%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x170mm 12.2-inch             | 1         | 2.08%   |
| LG Display LCD Monitor LGD04E2 1366x768 340x190mm 15.3-inch              | 1         | 2.08%   |
| LG Display LCD Monitor LGD0450 1366x768 280x160mm 12.7-inch              | 1         | 2.08%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch              | 1         | 2.08%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x170mm 13.9-inch              | 1         | 2.08%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 1         | 2.08%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch                  | 1         | 2.08%   |
| Lenovo LCD Monitor LEN4033 1440x900 300x190mm 14.0-inch                  | 1         | 2.08%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch                  | 1         | 2.08%   |
| InfoVision M116NWR1 R0  IVO0489 1366x768 260x140mm 11.6-inch             | 1         | 2.08%   |
| Goldstar L1715S GSM436F 1280x1024 340x270mm 17.1-inch                    | 1         | 2.08%   |
| Eizo EV2450 ENC2530 1920x1080 530x300mm 24.0-inch                        | 1         | 2.08%   |
| Dell U4919DW DELA107 3840x1080 1200x340mm 49.1-inch                      | 1         | 2.08%   |
| Dell U2715H DELD065 2560x1440 600x340mm 27.2-inch                        | 1         | 2.08%   |
| Dell P2317H DEL40F3 1920x1080 480x270mm 21.7-inch                        | 1         | 2.08%   |
| Dell 1909W DELA03D 1440x900 410x260mm 19.1-inch                          | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 340x190mm 15.3-inch         | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch          | 1         | 2.08%   |
| Chi Mei Optoelectronics LCD Monitor CMO1107 1366x768 250x140mm 11.3-inch | 1         | 2.08%   |
| BOE LCD Monitor BOE0817 1366x768 340x190mm 15.3-inch                     | 1         | 2.08%   |
| BOE LCD Monitor BOE07C8 3840x2160 310x170mm 13.9-inch                    | 1         | 2.08%   |
| BOE LCD Monitor BOE0731 1366x768 260x140mm 11.6-inch                     | 1         | 2.08%   |
| BOE LCD Monitor BOE0718 1920x1080 310x170mm 13.9-inch                    | 1         | 2.08%   |
| BOE LCD Monitor BOE06A5 1366x768 340x190mm 15.3-inch                     | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO5F2D 1920x1080 290x170mm 13.2-inch           | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 310x170mm 13.9-inch           | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 340x190mm 15.3-inch            | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch            | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch            | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO235C 1366x768 260x140mm 11.6-inch            | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch           | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO11C2 1024x600 200x110mm 9.0-inch             | 1         | 2.08%   |
| ASUSTek Computer VP247 AUS24CA 1920x1080 520x290mm 23.4-inch             | 1         | 2.08%   |
| Apple Color LCD APP9CDF 1440x900 290x180mm 13.4-inch                     | 1         | 2.08%   |
| Apple Color LCD APP9C20 1280x854 320x220mm 15.3-inch                     | 1         | 2.08%   |
| AOC 2270W AOC2270 1920x1080 480x270mm 21.7-inch                          | 1         | 2.08%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 520x290mm 23.4-inch    | 1         | 2.08%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 18        | 38.3%   |
| 1920x1080 (FHD)  | 12        | 25.53%  |
| 1440x900 (WXGA+) | 4         | 8.51%   |
| 3840x2160 (4K)   | 2         | 4.26%   |
| 1600x900 (HD+)   | 2         | 4.26%   |
| 1280x800 (WXGA)  | 2         | 4.26%   |
| 3840x1080        | 1         | 2.13%   |
| 3200x1800 (QHD+) | 1         | 2.13%   |
| 2736x1824        | 1         | 2.13%   |
| 2560x1440 (QHD)  | 1         | 2.13%   |
| 1280x854         | 1         | 2.13%   |
| 1280x1024 (SXGA) | 1         | 2.13%   |
| 1024x600         | 1         | 2.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 13     | 11        | 22.92%  |
| 15     | 9         | 18.75%  |
| 12     | 7         | 14.58%  |
| 11     | 6         | 12.5%   |
| 14     | 3         | 6.25%   |
| 27     | 2         | 4.17%   |
| 23     | 2         | 4.17%   |
| 21     | 2         | 4.17%   |
| 49     | 1         | 2.08%   |
| 31     | 1         | 2.08%   |
| 24     | 1         | 2.08%   |
| 19     | 1         | 2.08%   |
| 17     | 1         | 2.08%   |
| 9      | 1         | 2.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 201-300     | 20        | 41.67%  |
| 301-350     | 17        | 35.42%  |
| 501-600     | 5         | 10.42%  |
| 401-500     | 3         | 6.25%   |
| 601-700     | 1         | 2.08%   |
| 101-200     | 1         | 2.08%   |
| 1001-1500   | 1         | 2.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 37        | 78.72%  |
| 16/10 | 6         | 12.77%  |
| 3/2   | 2         | 4.26%   |
| 5/4   | 1         | 2.13%   |
| 32/9  | 1         | 2.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 11        | 22.92%  |
| 61-70          | 7         | 14.58%  |
| 91-100         | 7         | 14.58%  |
| 51-60          | 6         | 12.5%   |
| 201-250        | 5         | 10.42%  |
| 71-80          | 3         | 6.25%   |
| 301-350        | 2         | 4.17%   |
| 101-110        | 2         | 4.17%   |
| 351-500        | 1         | 2.08%   |
| 1-40           | 1         | 2.08%   |
| 151-200        | 1         | 2.08%   |
| 141-150        | 1         | 2.08%   |
| 501-1000       | 1         | 2.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 22        | 45.83%  |
| 101-120       | 11        | 22.92%  |
| 51-100        | 7         | 14.58%  |
| 161-240       | 4         | 8.33%   |
| More than 240 | 3         | 6.25%   |
| 1-50          | 1         | 2.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 60        | 69.77%  |
| 0     | 25        | 29.07%  |
| 2     | 1         | 1.16%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 60        | 51.72%  |
| Realtek Semiconductor           | 28        | 24.14%  |
| Qualcomm Atheros                | 10        | 8.62%   |
| Broadcom                        | 7         | 6.03%   |
| Marvell Technology Group        | 2         | 1.72%   |
| Xiaomi                          | 1         | 0.86%   |
| TP-Link                         | 1         | 0.86%   |
| Ralink Technology               | 1         | 0.86%   |
| Ralink                          | 1         | 0.86%   |
| Qualcomm Atheros Communications | 1         | 0.86%   |
| Micro Star International        | 1         | 0.86%   |
| Fibocom                         | 1         | 0.86%   |
| Edimax Technology               | 1         | 0.86%   |
| Apple                           | 1         | 0.86%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 19        | 12.67%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 7         | 4.67%   |
| Intel Wi-Fi 6 AX200                                                           | 6         | 4%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 6         | 4%      |
| Intel Wireless 8265 / 8275                                                    | 5         | 3.33%   |
| Intel I211 Gigabit Network Connection                                         | 5         | 3.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 4         | 2.67%   |
| Intel Wireless 7265                                                           | 3         | 2%      |
| Intel I210 Gigabit Network Connection                                         | 3         | 2%      |
| Intel 82567LM Gigabit Network Connection                                      | 3         | 2%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2         | 1.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 2         | 1.33%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 1.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 2         | 1.33%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 2         | 1.33%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 2         | 1.33%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                       | 2         | 1.33%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 2         | 1.33%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                               | 2         | 1.33%   |
| Intel I350 Gigabit Network Connection                                         | 2         | 1.33%   |
| Intel Ethernet Connection I219-LM                                             | 2         | 1.33%   |
| Intel Ethernet Connection (3) I218-LM                                         | 2         | 1.33%   |
| Intel Centrino Wireless-N 2200                                                | 2         | 1.33%   |
| Intel Centrino Advanced-N 6200                                                | 2         | 1.33%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 2         | 1.33%   |
| Intel 82577LM Gigabit Network Connection                                      | 2         | 1.33%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 1         | 0.67%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 1         | 0.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1         | 0.67%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 1         | 0.67%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 1         | 0.67%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1         | 0.67%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 1         | 0.67%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 0.67%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                              | 1         | 0.67%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1         | 0.67%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                     | 1         | 0.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1         | 0.67%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1         | 0.67%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 0.67%   |
| Micro Star International RT2573                                               | 1         | 0.67%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                       | 1         | 0.67%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 1         | 0.67%   |
| Intel Wireless-AC 9260                                                        | 1         | 0.67%   |
| Intel Wireless 8260                                                           | 1         | 0.67%   |
| Intel Wireless 3165                                                           | 1         | 0.67%   |
| Intel Wireless 3160                                                           | 1         | 0.67%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 0.67%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 1         | 0.67%   |
| Intel Ethernet Controller I225-V                                              | 1         | 0.67%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 1         | 0.67%   |
| Intel Ethernet Connection X553 1GbE                                           | 1         | 0.67%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                              | 1         | 0.67%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1         | 0.67%   |
| Intel Ethernet Connection (6) I219-V                                          | 1         | 0.67%   |
| Intel Ethernet Connection (4) I219-V                                          | 1         | 0.67%   |
| Intel Ethernet Connection (14) I219-V                                         | 1         | 0.67%   |
| Intel Ethernet Connection (10) I219-V                                         | 1         | 0.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 0.67%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 43        | 63.24%  |
| Qualcomm Atheros                | 10        | 14.71%  |
| Realtek Semiconductor           | 6         | 8.82%   |
| Broadcom                        | 3         | 4.41%   |
| TP-Link                         | 1         | 1.47%   |
| Ralink Technology               | 1         | 1.47%   |
| Ralink                          | 1         | 1.47%   |
| Qualcomm Atheros Communications | 1         | 1.47%   |
| Micro Star International        | 1         | 1.47%   |
| Edimax Technology               | 1         | 1.47%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                           | 6         | 8.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 6         | 8.82%   |
| Intel Wireless 8265 / 8275                                                    | 5         | 7.35%   |
| Intel Wireless 7265                                                           | 3         | 4.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 2         | 2.94%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 2.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 2         | 2.94%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 2         | 2.94%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                       | 2         | 2.94%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 2         | 2.94%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                               | 2         | 2.94%   |
| Intel Centrino Wireless-N 2200                                                | 2         | 2.94%   |
| Intel Centrino Advanced-N 6200                                                | 2         | 2.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 2         | 2.94%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 1         | 1.47%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1         | 1.47%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 1         | 1.47%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 1         | 1.47%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1         | 1.47%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 1         | 1.47%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1         | 1.47%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                     | 1         | 1.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1         | 1.47%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1         | 1.47%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 1.47%   |
| Micro Star International RT2573                                               | 1         | 1.47%   |
| Intel Wireless-AC 9260                                                        | 1         | 1.47%   |
| Intel Wireless 8260                                                           | 1         | 1.47%   |
| Intel Wireless 3165                                                           | 1         | 1.47%   |
| Intel Wireless 3160                                                           | 1         | 1.47%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 1.47%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 1.47%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 1         | 1.47%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 1         | 1.47%   |
| Intel Centrino Wireless-N 2230                                                | 1         | 1.47%   |
| Intel Centrino Advanced-N 6235                                                | 1         | 1.47%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 1         | 1.47%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                | 1         | 1.47%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 1         | 1.47%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 1         | 1.47%   |
| Broadcom BCM4306 802.11b/g Wireless LAN Controller                            | 1         | 1.47%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 39        | 50.65%  |
| Realtek Semiconductor    | 27        | 35.06%  |
| Broadcom                 | 5         | 6.49%   |
| Qualcomm Atheros         | 2         | 2.6%    |
| Marvell Technology Group | 2         | 2.6%    |
| Xiaomi                   | 1         | 1.3%    |
| Apple                    | 1         | 1.3%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 19        | 24.05%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 7         | 8.86%   |
| Intel I211 Gigabit Network Connection                                | 5         | 6.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 4         | 5.06%   |
| Intel I210 Gigabit Network Connection                                | 3         | 3.8%    |
| Intel 82567LM Gigabit Network Connection                             | 3         | 3.8%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                | 2         | 2.53%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet       | 2         | 2.53%   |
| Intel I350 Gigabit Network Connection                                | 2         | 2.53%   |
| Intel Ethernet Connection I219-LM                                    | 2         | 2.53%   |
| Intel Ethernet Connection (3) I218-LM                                | 2         | 2.53%   |
| Intel 82577LM Gigabit Network Connection                             | 2         | 2.53%   |
| Xiaomi Mi/Redmi series (RNDIS)                                       | 1         | 1.27%   |
| Realtek RTL8125 2.5GbE Controller                                    | 1         | 1.27%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                     | 1         | 1.27%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller              | 1         | 1.27%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller              | 1         | 1.27%   |
| Intel I210 Gigabit Fiber Network Connection                          | 1         | 1.27%   |
| Intel Ethernet Controller I225-V                                     | 1         | 1.27%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                        | 1         | 1.27%   |
| Intel Ethernet Connection X553 1GbE                                  | 1         | 1.27%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                     | 1         | 1.27%   |
| Intel Ethernet Connection (7) I219-LM                                | 1         | 1.27%   |
| Intel Ethernet Connection (6) I219-V                                 | 1         | 1.27%   |
| Intel Ethernet Connection (4) I219-V                                 | 1         | 1.27%   |
| Intel Ethernet Connection (14) I219-V                                | 1         | 1.27%   |
| Intel Ethernet Connection (10) I219-V                                | 1         | 1.27%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                 | 1         | 1.27%   |
| Intel 82576 Gigabit Network Connection                               | 1         | 1.27%   |
| Intel 82574L Gigabit Network Connection                              | 1         | 1.27%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller Mobile | 1         | 1.27%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                   | 1         | 1.27%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                    | 1         | 1.27%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express             | 1         | 1.27%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                     | 1         | 1.27%   |
| Broadcom NetXtreme BCM5714 Gigabit Ethernet                          | 1         | 1.27%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                      | 1         | 1.27%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                      | 1         | 1.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 73        | 52.14%  |
| WiFi     | 64        | 45.71%  |
| Modem    | 2         | 1.43%   |
| Unknown  | 1         | 0.71%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 46        | 58.23%  |
| Ethernet | 33        | 41.77%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 53        | 61.63%  |
| 1     | 21        | 24.42%  |
| 3     | 5         | 5.81%   |
| 4     | 3         | 3.49%   |
| 12    | 1         | 1.16%   |
| 7     | 1         | 1.16%   |
| 6     | 1         | 1.16%   |
| 0     | 1         | 1.16%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 86        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 23        | 57.5%   |
| Broadcom                        | 3         | 7.5%    |
| Alps Electric                   | 3         | 7.5%    |
| Realtek Semiconductor           | 2         | 5%      |
| Qualcomm Atheros Communications | 2         | 5%      |
| ASUSTek Computer                | 2         | 5%      |
| Apple                           | 2         | 5%      |
| IMC Networks                    | 1         | 2.5%    |
| Creative Technology             | 1         | 2.5%    |
| Cambridge Silicon Radio         | 1         | 2.5%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 8         | 20%     |
| Intel AX200 Bluetooth                               | 6         | 15%     |
| Intel AX201 Bluetooth                               | 3         | 7.5%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 5%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 5%      |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 5%      |
| Alps Electric UGTZ4 Bluetooth                       | 2         | 5%      |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 2.5%    |
| Realtek  Bluetooth 4.0 Adapter                      | 1         | 2.5%    |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1             | 1         | 2.5%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 2.5%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 2.5%    |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2.5%    |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS    | 1         | 2.5%    |
| Creative Creative Bluetooth Audio W2                | 1         | 2.5%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.5%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 2.5%    |
| ASUS Broadcom Bluetooth 2.1                         | 1         | 2.5%    |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 2.5%    |
| Apple Bluetooth Host Controller                     | 1         | 2.5%    |
| Apple Apple Broadcom Built-in Bluetooth             | 1         | 2.5%    |
| Alps Electric BCM2046 Bluetooth Device              | 1         | 2.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 59        | 72.84%  |
| AMD                    | 12        | 14.81%  |
| Nvidia                 | 5         | 6.17%   |
| VIA Technologies       | 1         | 1.23%   |
| Logitech               | 1         | 1.23%   |
| JMTek                  | 1         | 1.23%   |
| Generalplus Technology | 1         | 1.23%   |
| Creative Labs          | 1         | 1.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 8         | 8.33%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 7         | 7.29%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 6         | 6.25%   |
| Intel Sunrise Point-LP HD Audio                                                   | 6         | 6.25%   |
| Intel Broadwell-U Audio Controller                                                | 6         | 6.25%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 5         | 5.21%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                               | 5         | 5.21%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 4         | 4.17%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 4         | 4.17%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 3         | 3.13%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 3         | 3.13%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                         | 2         | 2.08%   |
| Intel Haswell-ULT HD Audio Controller                                             | 2         | 2.08%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 2         | 2.08%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                 | 2         | 2.08%   |
| Intel Cannon Lake PCH cAVS                                                        | 2         | 2.08%   |
| Intel 8 Series HD Audio Controller                                                | 2         | 2.08%   |
| AMD Starship/Matisse HD Audio Controller                                          | 2         | 2.08%   |
| AMD Navi 10 HDMI Audio                                                            | 2         | 2.08%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 2         | 2.08%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                         | 1         | 1.04%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1         | 1.04%   |
| Nvidia TU104 HD Audio Controller                                                  | 1         | 1.04%   |
| Nvidia GT216 HDMI Audio Controller                                                | 1         | 1.04%   |
| Nvidia GP106 High Definition Audio Controller                                     | 1         | 1.04%   |
| Nvidia GM204 High Definition Audio Controller                                     | 1         | 1.04%   |
| Logitech H390 headset with microphone                                             | 1         | 1.04%   |
| JMTek USB PnP Audio Device                                                        | 1         | 1.04%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                   | 1         | 1.04%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 1         | 1.04%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 1         | 1.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 1         | 1.04%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                  | 1         | 1.04%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                 | 1         | 1.04%   |
| Intel 82801CA/CAM AC'97 Audio Controller                                          | 1         | 1.04%   |
| Generalplus Technology USB Audio Device                                           | 1         | 1.04%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                     | 1         | 1.04%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 1         | 1.04%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                      | 1         | 1.04%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 1         | 1.04%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1         | 1.04%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


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

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


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

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 8         | 66.67%  |
| DDR4    | 2         | 16.67%  |
| DDR2    | 1         | 8.33%   |
| Unknown | 1         | 8.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 10        | 83.33%  |
| DIMM   | 2         | 16.67%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


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

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


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

![Camera Vendor](./All/images/pie_chart_bsd/camera_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Chicony Electronics   | 11        | 32.35%  |
| Acer                  | 6         | 17.65%  |
| IMC Networks          | 3         | 8.82%   |
| Suyin                 | 2         | 5.88%   |
| Quanta                | 2         | 5.88%   |
| Microdia              | 2         | 5.88%   |
| Lite-On Technology    | 2         | 5.88%   |
| Syntek                | 1         | 2.94%   |
| Silicon Motion        | 1         | 2.94%   |
| Ricoh                 | 1         | 2.94%   |
| Realtek Semiconductor | 1         | 2.94%   |
| Logitech              | 1         | 2.94%   |
| Lenovo                | 1         | 2.94%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 3         | 8.82%   |
| Lite-On Integrated Camera                | 2         | 5.88%   |
| Chicony Ltd., VGA Webcam                 | 2         | 5.88%   |
| Acer Integrated Camera                   | 2         | 5.88%   |
| Acer EasyCamera                          | 2         | 5.88%   |
| Syntek Lenovo EasyCamera                 | 1         | 2.94%   |
| Suyin Asus Integrated Webcam             | 1         | 2.94%   |
| Suyin Acer/Lenovo Webcam [CN0316]        | 1         | 2.94%   |
| Silicon Motion Realtek USB2.0 PC Camera  | 1         | 2.94%   |
| Ricoh Sony Visual Communication Camera   | 1         | 2.94%   |
| Realtek Integrated_Webcam_HD             | 1         | 2.94%   |
| Quanta HP Webcam-50                      | 1         | 2.94%   |
| Quanta HP TrueVision HD Camera           | 1         | 2.94%   |
| Microdia Sonix USB 2.0 Camera            | 1         | 2.94%   |
| Microdia Integrated Webcam HD            | 1         | 2.94%   |
| Logitech HD Pro Webcam C920              | 1         | 2.94%   |
| Lenovo Integrated Webcam                 | 1         | 2.94%   |
| IMC Networks USB2.0 HD UVC WebCam        | 1         | 2.94%   |
| IMC Networks Lenovo EasyCamera           | 1         | 2.94%   |
| IMC Networks Integrated Camera           | 1         | 2.94%   |
| Chicony thinkpad t430s camera            | 1         | 2.94%   |
| Chicony Ltd., Integrated Camera          | 1         | 2.94%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 1         | 2.94%   |
| Chicony Integrated Camera [ThinkPad]     | 1         | 2.94%   |
| Chicony HD Webcam                        | 1         | 2.94%   |
| Chicony 2.0M UVC Webcam / CNF7129        | 1         | 2.94%   |
| Acer SunplusIT Integrated Camera         | 1         | 2.94%   |
| Acer Lenovo Integrated Webcam            | 1         | 2.94%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Synaptics             | 4         | 40%     |
| Upek                  | 2         | 20%     |
| Validity Sensors      | 1         | 10%     |
| STMicroelectronics    | 1         | 10%     |
| Elan Microelectronics | 1         | 10%     |
| AuthenTec             | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 20%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 20%     |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 10%     |
| Synaptics product 0x00be                               | 1         | 10%     |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 10%     |
| STMicroelectronics Fingerprint Reader                  | 1         | 10%     |
| Elan ELAN WBF Fingerprint Sensor                       | 1         | 10%     |
| AuthenTec AES2810                                      | 1         | 10%     |

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

![Unsupported Devices](./All/images/pie_chart_bsd/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 38        | 44.19%  |
| 2     | 21        | 24.42%  |
| 0     | 17        | 19.77%  |
| 3     | 5         | 5.81%   |
| 4     | 2         | 2.33%   |
| 7     | 1         | 1.16%   |
| 6     | 1         | 1.16%   |
| 5     | 1         | 1.16%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 48        | 44.04%  |
| Graphics card            | 27        | 24.77%  |
| Firewire controller      | 10        | 9.17%   |
| Net/wireless             | 9         | 8.26%   |
| Storage/ata              | 4         | 3.67%   |
| Net/ethernet             | 4         | 3.67%   |
| Sound                    | 3         | 2.75%   |
| Modem                    | 2         | 1.83%   |
| Storage/ide              | 1         | 0.92%   |
| Network                  | 1         | 0.92%   |

