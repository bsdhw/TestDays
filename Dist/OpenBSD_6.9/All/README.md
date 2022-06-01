OpenBSD 6.9 - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for OpenBSD 6.9.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/OpenBSD_6.9/Desktop/README.md) and [notebooks](/Dist/OpenBSD_6.9/Notebook/README.md).

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

Total: 107

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| HP            | ProDesk 600 G1 SFF          | Desktop     | [7f19a8a566](https://bsd-hardware.info/?probe=7f19a8a566) | Oct 26, 2021 |
| Supermicro    | X7SBL                       | Desktop     | [f5b4e8e7ab](https://bsd-hardware.info/?probe=f5b4e8e7ab) | Oct 23, 2021 |
| Google        | Grunt                       | Notebook    | [e76c73d9a3](https://bsd-hardware.info/?probe=e76c73d9a3) | Oct 11, 2021 |
| Gigabyte      | B450M DS3H                  | Desktop     | [50e4e13ee0](https://bsd-hardware.info/?probe=50e4e13ee0) | Oct 07, 2021 |
| MSI           | MS-7B53                     | Desktop     | [c7104d301e](https://bsd-hardware.info/?probe=c7104d301e) | Oct 05, 2021 |
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

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| amd64  | 74        | 83.15%  |
| i386   | 12        | 13.48%  |
| arm64  | 2         | 2.25%   |
| macppc | 1         | 1.12%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| fvwm    | 68        | 76.4%   |
| Console | 20        | 22.47%  |
| i3      | 1         | 1.12%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 67        | 75.28%  |
| Console | 22        | 24.72%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 78        | 87.64%  |
| SLiM    | 9         | 10.11%  |
| GDM     | 2         | 2.25%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 71        | 79.78%  |
| en_US   | 12        | 13.48%  |
| ru_RU   | 3         | 3.37%   |
| en_EN   | 1         | 1.12%   |
| de_DE   | 1         | 1.12%   |
| C       | 1         | 1.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 50        | 55.56%  |
| BIOS | 40        | 44.44%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ffs  | 89        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 46        | 51.11%  |
| MBR  | 44        | 48.89%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 23        | 25.84%  |
| Hewlett-Packard                | 12        | 13.48%  |
| ASUSTek Computer               | 9         | 10.11%  |
| Supermicro                     | 6         | 6.74%   |
| Acer                           | 4         | 4.49%   |
| Unknown                        | 4         | 4.49%   |
| PC Engines                     | 3         | 3.37%   |
| MSI                            | 3         | 3.37%   |
| Dell                           | 3         | 3.37%   |
| Apple                          | 3         | 3.37%   |
| Panasonic                      | 2         | 2.25%   |
| Matsushita Electric Industrial | 2         | 2.25%   |
| IBM                            | 2         | 2.25%   |
| Gigabyte Technology            | 2         | 2.25%   |
| ASRock                         | 2         | 2.25%   |
| Standard                       | 1         | 1.12%   |
| Sony                           | 1         | 1.12%   |
| Shuttle                        | 1         | 1.12%   |
| Samsung Electronics            | 1         | 1.12%   |
| NF541                          | 1         | 1.12%   |
| Microsoft                      | 1         | 1.12%   |
| Foxconn                        | 1         | 1.12%   |
| Clevo                          | 1         | 1.12%   |
| Alienware                      | 1         | 1.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 5         | 5.62%   |
| Supermicro Super Server                     | 2         | 2.25%   |
| Supermicro X8STi                            | 1         | 1.12%   |
| Supermicro X8DTH-i/6/iF/6F                  | 1         | 1.12%   |
| Supermicro X7SBL                            | 1         | 1.12%   |
| Supermicro X10SLH-N6-ST031                  | 1         | 1.12%   |
| Standard TF                                 | 1         | 1.12%   |
| Sony VGN-P698E                              | 1         | 1.12%   |
| Shuttle DS77U                               | 1         | 1.12%   |
| Samsung 3570R/370R/470R/450R/510R/4450RV    | 1         | 1.12%   |
| PC Engines apu4                             | 1         | 1.12%   |
| PC Engines APU2                             | 1         | 1.12%   |
| PC Engines apu1                             | 1         | 1.12%   |
| Panasonic CF-53AAGHYDM                      | 1         | 1.12%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 1.12%   |
| MSI MS-7B53                                 | 1         | 1.12%   |
| MSI MS-7A34                                 | 1         | 1.12%   |
| MSI MS-1613                                 | 1         | 1.12%   |
| Microsoft Surface Pro 7                     | 1         | 1.12%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 1.12%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 1.12%   |
| Lenovo Yoga 6 13ARE05 82FN                  | 1         | 1.12%   |
| Lenovo Yoga 330-11IGM 81A6                  | 1         | 1.12%   |
| Lenovo ThinkPad X280 20KESA000B             | 1         | 1.12%   |
| Lenovo ThinkPad X270 20HNA006ID             | 1         | 1.12%   |
| Lenovo ThinkPad X250 20CM0046US             | 1         | 1.12%   |
| Lenovo ThinkPad X250 20CLS7WY04             | 1         | 1.12%   |
| Lenovo ThinkPad X230 232578G                | 1         | 1.12%   |
| Lenovo ThinkPad X220 4291ON5                | 1         | 1.12%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD00KTMH    | 1         | 1.12%   |
| Lenovo ThinkPad T430 23511A6                | 1         | 1.12%   |
| Lenovo ThinkPad T430 2349U2B                | 1         | 1.12%   |
| Lenovo ThinkPad T430 2347GZU                | 1         | 1.12%   |
| Lenovo ThinkPad T420 4236MBG                | 1         | 1.12%   |
| Lenovo ThinkPad T410 2537N24                | 1         | 1.12%   |
| Lenovo ThinkPad T400 6475P1G                | 1         | 1.12%   |
| Lenovo ThinkPad T400 6475K43                | 1         | 1.12%   |
| Lenovo ThinkPad T400 2767WSB                | 1         | 1.12%   |
| Lenovo ThinkPad T14 Gen 1 20S1S07800        | 1         | 1.12%   |
| Lenovo ThinkPad Edge 05796AU                | 1         | 1.12%   |
| Lenovo ThinkPad E490 20N8CTO1WW             | 1         | 1.12%   |
| Lenovo IdeaPad S210 Touch 20257             | 1         | 1.12%   |
| Lenovo IdeaPad 1 11IGL05 81VT               | 1         | 1.12%   |
| Lenovo FLEX 3-1120 80LX                     | 1         | 1.12%   |
| IBM ThinkPad T42 2374K46                    | 1         | 1.12%   |
| IBM ThinkPad H 1846AQG                      | 1         | 1.12%   |
| HP ProLiant DL360e Gen8                     | 1         | 1.12%   |
| HP ProLiant DL360 Gen9                      | 1         | 1.12%   |
| HP ProLiant DL320 G5                        | 1         | 1.12%   |
| HP ProDesk 600 G1 SFF                       | 1         | 1.12%   |
| HP ProBook 450 G2                           | 1         | 1.12%   |
| HP Pro3500 Series                           | 1         | 1.12%   |
| HP Pavilion Gaming Laptop 15-ec1xxx         | 1         | 1.12%   |
| HP Pavilion dm1                             | 1         | 1.12%   |
| HP Notebook                                 | 1         | 1.12%   |
| HP EliteDesk 800 G5 SFF                     | 1         | 1.12%   |
| HP 530 Notebook PC(KP477AA#ACB)             | 1         | 1.12%   |
| HP 250 G5 Notebook PC                       | 1         | 1.12%   |
| Gigabyte GA-7VT600                          | 1         | 1.12%   |
| Gigabyte B550I AORUS PRO AX                 | 1         | 1.12%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad                             | 18        | 20.22%  |
| Unknown                                     | 5         | 5.62%   |
| HP ProLiant                                 | 3         | 3.37%   |
| Supermicro Super                            | 2         | 2.25%   |
| Lenovo Yoga                                 | 2         | 2.25%   |
| Lenovo IdeaPad                              | 2         | 2.25%   |
| IBM ThinkPad                                | 2         | 2.25%   |
| HP Pavilion                                 | 2         | 2.25%   |
| Dell XPS                                    | 2         | 2.25%   |
| ASUS ROG                                    | 2         | 2.25%   |
| Supermicro X8STi                            | 1         | 1.12%   |
| Supermicro X8DTH-i                          | 1         | 1.12%   |
| Supermicro X7SBL                            | 1         | 1.12%   |
| Supermicro X10SLH-N6-ST031                  | 1         | 1.12%   |
| Standard TF                                 | 1         | 1.12%   |
| Sony VGN-P698E                              | 1         | 1.12%   |
| Shuttle DS77U                               | 1         | 1.12%   |
| Samsung 3570R                               | 1         | 1.12%   |
| PC Engines apu4                             | 1         | 1.12%   |
| PC Engines APU2                             | 1         | 1.12%   |
| PC Engines apu1                             | 1         | 1.12%   |
| Panasonic CF-53AAGHYDM                      | 1         | 1.12%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 1.12%   |
| MSI MS-7B53                                 | 1         | 1.12%   |
| MSI MS-7A34                                 | 1         | 1.12%   |
| MSI MS-1613                                 | 1         | 1.12%   |
| Microsoft Surface                           | 1         | 1.12%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 1.12%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 1.12%   |
| Lenovo FLEX                                 | 1         | 1.12%   |
| HP ProDesk                                  | 1         | 1.12%   |
| HP ProBook                                  | 1         | 1.12%   |
| HP Pro3500                                  | 1         | 1.12%   |
| HP Notebook                                 | 1         | 1.12%   |
| HP EliteDesk                                | 1         | 1.12%   |
| HP 530                                      | 1         | 1.12%   |
| HP 250                                      | 1         | 1.12%   |
| Gigabyte GA-7VT600                          | 1         | 1.12%   |
| Gigabyte B550I                              | 1         | 1.12%   |
| Foxconn AT-7000                             | 1         | 1.12%   |
| Dell Latitude                               | 1         | 1.12%   |
| Clevo W240EU                                | 1         | 1.12%   |
| ASUS X555LB                                 | 1         | 1.12%   |
| ASUS UX430UNR                               | 1         | 1.12%   |
| ASUS UX305FA                                | 1         | 1.12%   |
| ASUS PRIME                                  | 1         | 1.12%   |
| ASUS P10S-I                                 | 1         | 1.12%   |
| ASUS B202                                   | 1         | 1.12%   |
| ASUS 1000HE                                 | 1         | 1.12%   |
| ASRock Z68                                  | 1         | 1.12%   |
| ASRock X570M                                | 1         | 1.12%   |
| Apple PowerBook5                            | 1         | 1.12%   |
| Apple MacBookPro6                           | 1         | 1.12%   |
| Apple MacBookAir6                           | 1         | 1.12%   |
| Alienware Aurora                            | 1         | 1.12%   |
| Acer Spin                                   | 1         | 1.12%   |
| Acer Aspire                                 | 1         | 1.12%   |
| Acer AOA150                                 | 1         | 1.12%   |
| Acer AO531h                                 | 1         | 1.12%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 14        | 15.73%  |
| 2019    | 12        | 13.48%  |
| 2018    | 8         | 8.99%   |
| 2021    | 6         | 6.74%   |
| 2013    | 6         | 6.74%   |
| 2008    | 6         | 6.74%   |
| 2009    | 5         | 5.62%   |
| Unknown | 5         | 5.62%   |
| 2015    | 4         | 4.49%   |
| 2011    | 4         | 4.49%   |
| 2010    | 4         | 4.49%   |
| 2017    | 3         | 3.37%   |
| 2012    | 3         | 3.37%   |
| 2016    | 2         | 2.25%   |
| 2014    | 2         | 2.25%   |
| 2006    | 2         | 2.25%   |
| 2005    | 1         | 1.12%   |
| 2003    | 1         | 1.12%   |
| 2002    | 1         | 1.12%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 55        | 61.8%   |
| Desktop  | 31        | 34.83%  |
| Server   | 2         | 2.25%   |
| Tablet   | 1         | 1.12%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 84        | 94.38%  |
| Yes  | 5         | 5.62%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 21        | 23.6%   |
| 16.01-24.0  | 18        | 20.22%  |
| 4.01-8.0    | 17        | 19.1%   |
| 3.01-4.0    | 8         | 8.99%   |
| 2.01-3.0    | 8         | 8.99%   |
| 0.51-1.0    | 5         | 5.62%   |
| 32.01-64.0  | 4         | 4.49%   |
| 1.01-2.0    | 4         | 4.49%   |
| 24.01-32.0  | 2         | 2.25%   |
| 64.01-256.0 | 2         | 2.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 72        | 80.9%   |
| 0        | 7         | 7.87%   |
| 0.51-1.0 | 5         | 5.62%   |
| 1.01-2.0 | 2         | 2.25%   |
| Unknown  | 2         | 2.25%   |
| 4.01-8.0 | 1         | 1.12%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 49        | 54.44%  |
| 2      | 24        | 26.67%  |
| 3      | 7         | 7.78%   |
| 4      | 4         | 4.44%   |
| 6      | 2         | 2.22%   |
| 5      | 2         | 2.22%   |
| 7      | 1         | 1.11%   |
| 0      | 1         | 1.11%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 89        | 100%    |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 76        | 85.39%  |
| No        | 13        | 14.61%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 65        | 73.03%  |
| No        | 24        | 26.97%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 50        | 56.18%  |
| Yes       | 39        | 43.82%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 23        | 25.84%  |
| Germany      | 11        | 12.36%  |
| Canada       | 9         | 10.11%  |
| Russia       | 7         | 7.87%   |
| France       | 6         | 6.74%   |
| Netherlands  | 5         | 5.62%   |
| Ukraine      | 3         | 3.37%   |
| Sweden       | 3         | 3.37%   |
| UK           | 2         | 2.25%   |
| Spain        | 2         | 2.25%   |
| Portugal     | 2         | 2.25%   |
| Poland       | 2         | 2.25%   |
| Latvia       | 2         | 2.25%   |
| Turkey       | 1         | 1.12%   |
| Taiwan       | 1         | 1.12%   |
| Switzerland  | 1         | 1.12%   |
| Saudi Arabia | 1         | 1.12%   |
| Romania      | 1         | 1.12%   |
| Philippines  | 1         | 1.12%   |
| Norway       | 1         | 1.12%   |
| Malaysia     | 1         | 1.12%   |
| Jamaica      | 1         | 1.12%   |
| Indonesia    | 1         | 1.12%   |
| Chile        | 1         | 1.12%   |
| Brazil       | 1         | 1.12%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Saint-Laurent           | 7         | 7.78%   |
| Moscow                  | 4         | 4.44%   |
| Yekaterinburg           | 2         | 2.22%   |
| Riga                    | 2         | 2.22%   |
| Papillion               | 2         | 2.22%   |
| Miedziana Gora          | 2         | 2.22%   |
| Los Angeles             | 2         | 2.22%   |
| Brooklyn                | 2         | 2.22%   |
| Bielefeld               | 2         | 2.22%   |
| Berlin                  | 2         | 2.22%   |
| Barneveld               | 2         | 2.22%   |
| 's-Hertogenbosch        | 2         | 2.22%   |
| Wolfsburg               | 1         | 1.11%   |
| Wittersham              | 1         | 1.11%   |
| Watford                 | 1         | 1.11%   |
| Victoria                | 1         | 1.11%   |
| Vechta                  | 1         | 1.11%   |
| Van Nuys                | 1         | 1.11%   |
| Valdivia                | 1         | 1.11%   |
| Vacaville               | 1         | 1.11%   |
| Teriang                 | 1         | 1.11%   |
| SГЈo Paulo            | 1         | 1.11%   |
| Syeverodonets'k         | 1         | 1.11%   |
| Surabaya                | 1         | 1.11%   |
| Spokane                 | 1         | 1.11%   |
| Solna                   | 1         | 1.11%   |
| Soeraker                | 1         | 1.11%   |
| Sedavi                  | 1         | 1.11%   |
| Sechelt                 | 1         | 1.11%   |
| Sammamish               | 1         | 1.11%   |
| Saint-Martin-d'HГЁres | 1         | 1.11%   |
| Roubaix                 | 1         | 1.11%   |
| Roseville               | 1         | 1.11%   |
| Rodgau                  | 1         | 1.11%   |
| Riyadh                  | 1         | 1.11%   |
| Quezon City             | 1         | 1.11%   |
| Plainfield              | 1         | 1.11%   |
| Onalaska                | 1         | 1.11%   |
| Oensingen               | 1         | 1.11%   |
| Oeiras                  | 1         | 1.11%   |
| New York                | 1         | 1.11%   |
| New Taipei              | 1         | 1.11%   |
| Neuilly-sur-Marne       | 1         | 1.11%   |
| Monts                   | 1         | 1.11%   |
| McLeod                  | 1         | 1.11%   |
| Madrid                  | 1         | 1.11%   |
| Kyiv                    | 1         | 1.11%   |
| Korolyov                | 1         | 1.11%   |
| Kingston                | 1         | 1.11%   |
| Independence            | 1         | 1.11%   |
| Hoeviksnaes             | 1         | 1.11%   |
| Hockenheim              | 1         | 1.11%   |
| Heilbronn               | 1         | 1.11%   |
| Hamilton                | 1         | 1.11%   |
| Greensburg              | 1         | 1.11%   |
| Frankfurt am Main       | 1         | 1.11%   |
| Estoril                 | 1         | 1.11%   |
| Donetsk                 | 1         | 1.11%   |
| Dallas                  | 1         | 1.11%   |
| Covington               | 1         | 1.11%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| NVMe                | 18        | 20     | 15.93%  |
| WDC                 | 16        | 18     | 14.16%  |
| Samsung Electronics | 16        | 21     | 14.16%  |
| Seagate             | 9         | 15     | 7.96%   |
| Toshiba             | 6         | 6      | 5.31%   |
| OPENBSD             | 5         | 5      | 4.42%   |
| SanDisk             | 4         | 4      | 3.54%   |
| HGST                | 4         | 5      | 3.54%   |
| Crucial             | 4         | 4      | 3.54%   |
| Intel               | 3         | 4      | 2.65%   |
| Hitachi             | 3         | 3      | 2.65%   |
| SK Hynix            | 2         | 2      | 1.77%   |
| Kingston            | 2         | 2      | 1.77%   |
| Hewlett-Packard     | 2         | 6      | 1.77%   |
| Zheino              | 1         | 1      | 0.88%   |
| USB                 | 1         | 1      | 0.88%   |
| UDinfo              | 1         | 1      | 0.88%   |
| Transcend           | 1         | 4      | 0.88%   |
| Team                | 1         | 1      | 0.88%   |
| SPCC                | 1         | 1      | 0.88%   |
| Product:            | 1         | 1      | 0.88%   |
| Phison              | 1         | 1      | 0.88%   |
| Patriot             | 1         | 1      | 0.88%   |
| Netac               | 1         | 1      | 0.88%   |
| Multiple            | 1         | 1      | 0.88%   |
| Micron Technology   | 1         | 1      | 0.88%   |
| MEMXPRO             | 1         | 1      | 0.88%   |
| LSI                 | 1         | 1      | 0.88%   |
| GLOWAY              | 1         | 1      | 0.88%   |
| Fujitsu             | 1         | 1      | 0.88%   |
| asmedia             | 1         | 1      | 0.88%   |
| Apple               | 1         | 1      | 0.88%   |
| A-DATA Technology   | 1         | 1      | 0.88%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| OPENBSD SR RAID 1 752GB           | 5         | 4%      |
| WDC WD1600BEVT-22ZCT0 160GB       | 3         | 2.4%    |
| Samsung SSD 850 EVO 250GB         | 3         | 2.4%    |
| NVMe Samsung SSD 960 500GB        | 3         | 2.4%    |
| Toshiba MQ04ABF100 1TB            | 2         | 1.6%    |
| NVMe WDC PC SN730 SDB 256GB       | 2         | 1.6%    |
| NVMe Samsung SSD 970 250GB        | 2         | 1.6%    |
| NVMe SAMSUNG MZVLB256 256GB       | 2         | 1.6%    |
| HGST HUS724020ALA640 2TB          | 2         | 1.6%    |
| Zheino CHN-mSATAQ3-120 120GB      | 1         | 0.8%    |
| WDC WDS500G2B0A-00SM50 500GB      | 1         | 0.8%    |
| WDC WD80EFAX-68KNBN0 8TB          | 1         | 0.8%    |
| WDC WD7500BPKX-00HPJT0 752GB      | 1         | 0.8%    |
| WDC WD7500BPKT-00PK4T0 752GB      | 1         | 0.8%    |
| WDC WD60EFRX-68L0BN1 6TB          | 1         | 0.8%    |
| WDC WD5000LPLX-00ZNTT0 500GB      | 1         | 0.8%    |
| WDC WD5000LPCX-24C6HT0 500GB      | 1         | 0.8%    |
| WDC WD3200BEVE-00A0HT0 320GB      | 1         | 0.8%    |
| WDC WD3200BEKT-08PVMT1 320GB      | 1         | 0.8%    |
| WDC WD20PURX-64P6ZY0 2TB          | 1         | 0.8%    |
| WDC WD10SPCX-24HWST1 1TB          | 1         | 0.8%    |
| WDC WD10JPLX-00MBPT0 1TB          | 1         | 0.8%    |
| WDC WD1005FBYZ-01YCBB3 1TB        | 1         | 0.8%    |
| WDC WD Elements 25A3 4TB          | 1         | 0.8%    |
| USB SanDisk 3.2Gen1 64GB          | 1         | 0.8%    |
| UDinfo M2S 120GB                  | 1         | 0.8%    |
| Transcend 3E128-TS2-550B01 100GB  | 1         | 0.8%    |
| Toshiba MK8025GAS 80GB            | 1         | 0.8%    |
| Toshiba MK3256GSY 320GB           | 1         | 0.8%    |
| Toshiba MK1665GSX 160GB           | 1         | 0.8%    |
| Toshiba DT01ACA100 1TB            | 1         | 0.8%    |
| Team T253X2001T 1TB               | 1         | 0.8%    |
| SPCC Solid State Disk 128GB       | 1         | 0.8%    |
| SK Hynix SC311 SATA 256GB         | 1         | 0.8%    |
| SK Hynix HFS128G39TND-N210A 128GB | 1         | 0.8%    |
| Seagate ST950032 5AS 500GB        | 1         | 0.8%    |
| Seagate ST9160821A 160GB          | 1         | 0.8%    |
| Seagate ST9160310AS 160GB         | 1         | 0.8%    |
| Seagate ST500LT012-9WS142 500GB   | 1         | 0.8%    |
| Seagate ST3808110AS 80GB          | 1         | 0.8%    |
| Seagate ST380011A 80GB            | 1         | 0.8%    |
| Seagate ST3160212ACE 160GB        | 1         | 0.8%    |
| Seagate ST2000LX001-1RG174 2TB    | 1         | 0.8%    |
| Seagate ST1000LM048-2E7172 1TB    | 1         | 0.8%    |
| Seagate ST1000LM035-1RK172 1TB    | 1         | 0.8%    |
| Seagate ST1000DM003-9YN162 1TB    | 1         | 0.8%    |
| Seagate ST1000DM003-1CH162 1TB    | 1         | 0.8%    |
| Seagate Backup+ SL 1TB            | 1         | 0.8%    |
| SanDisk Ultra Fit 16GB            | 1         | 0.8%    |
| SanDisk Ultra 32GB                | 1         | 0.8%    |
| SanDisk SSD PLUS 120GB            | 1         | 0.8%    |
| SanDisk SD7SN3Q128G1002 128GB     | 1         | 0.8%    |
| Samsung SSD 860 PRO 256GB         | 1         | 0.8%    |
| Samsung SSD 860 EVO M.2 2TB       | 1         | 0.8%    |
| Samsung SSD 860 EVO M.2 250GB     | 1         | 0.8%    |
| Samsung SSD 860 EVO M.2 1TB       | 1         | 0.8%    |
| Samsung SSD 860 EVO 2TB           | 1         | 0.8%    |
| Samsung SSD 860 EVO 250GB         | 1         | 0.8%    |
| Samsung SSD 860 EVO 1TB           | 1         | 0.8%    |
| Samsung SSD 850 PRO 256GB         | 1         | 0.8%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 15        | 17     | 23.81%  |
| NVMe                | 12        | 13     | 19.05%  |
| Seagate             | 9         | 15     | 14.29%  |
| Toshiba             | 6         | 6      | 9.52%   |
| OPENBSD             | 5         | 5      | 7.94%   |
| HGST                | 4         | 5      | 6.35%   |
| Hitachi             | 3         | 3      | 4.76%   |
| Samsung Electronics | 2         | 2      | 3.17%   |
| Hewlett-Packard     | 2         | 6      | 3.17%   |
| USB                 | 1         | 1      | 1.59%   |
| Product:            | 1         | 1      | 1.59%   |
| Multiple            | 1         | 1      | 1.59%   |
| LSI                 | 1         | 1      | 1.59%   |
| Fujitsu             | 1         | 1      | 1.59%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 19     | 29.41%  |
| NVMe                | 6         | 6      | 11.76%  |
| SanDisk             | 4         | 4      | 7.84%   |
| Crucial             | 4         | 4      | 7.84%   |
| Intel               | 3         | 4      | 5.88%   |
| SK Hynix            | 2         | 2      | 3.92%   |
| Kingston            | 2         | 2      | 3.92%   |
| Zheino              | 1         | 1      | 1.96%   |
| WDC                 | 1         | 1      | 1.96%   |
| UDinfo              | 1         | 1      | 1.96%   |
| Transcend           | 1         | 4      | 1.96%   |
| Team                | 1         | 1      | 1.96%   |
| SPCC                | 1         | 1      | 1.96%   |
| Phison              | 1         | 1      | 1.96%   |
| Patriot             | 1         | 1      | 1.96%   |
| Netac               | 1         | 1      | 1.96%   |
| Micron Technology   | 1         | 1      | 1.96%   |
| MEMXPRO             | 1         | 1      | 1.96%   |
| GLOWAY              | 1         | 1      | 1.96%   |
| asmedia             | 1         | 1      | 1.96%   |
| Apple               | 1         | 1      | 1.96%   |
| A-DATA Technology   | 1         | 1      | 1.96%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 50        | 77     | 51.55%  |
| SSD  | 46        | 59     | 47.42%  |
| NVMe | 1         | 1      | 1.03%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 84        | 136    | 98.82%  |
| NVMe | 1         | 1      | 1.18%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 68        | 90     | 68.69%  |
| 0.51-1.0        | 21        | 32     | 21.21%  |
| 1.01-2.0        | 6         | 9      | 6.06%   |
| 4.01-10.0       | 2         | 3      | 2.02%   |
| More than 100.0 | 1         | 1      | 1.01%   |
| 3.01-4.0        | 1         | 1      | 1.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 33        | 37.08%  |
| 251-500        | 24        | 26.97%  |
| 51-100         | 11        | 12.36%  |
| 21-50          | 8         | 8.99%   |
| 1-20           | 6         | 6.74%   |
| More than 3000 | 4         | 4.49%   |
| 501-1000       | 2         | 2.25%   |
| 1001-2000      | 1         | 1.12%   |

