OpenBSD 7.3 - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for OpenBSD 7.3.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/OpenBSD_7.3/Desktop/README.md) and [notebooks](/Dist/OpenBSD_7.3/Notebook/README.md).

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

Total: 100

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| PC Engines    | APU                         | Desktop     | [ca9bc2faa7](https://bsd-hardware.info/?probe=ca9bc2faa7) | Sep 29, 2023 |
| PC Engines    | APU                         | Desktop     | [067872c1f5](https://bsd-hardware.info/?probe=067872c1f5) | Sep 29, 2023 |
| ASUSTek       | PRIME A520M-A II            | Desktop     | [29bcb3ca3e](https://bsd-hardware.info/?probe=29bcb3ca3e) | Sep 29, 2023 |
| GPD           | G1619-04                    | Notebook    | [30ad9b72b5](https://bsd-hardware.info/?probe=30ad9b72b5) | Sep 23, 2023 |
| Dell          | Latitude E7470              | Notebook    | [11cf3b211c](https://bsd-hardware.info/?probe=11cf3b211c) | Sep 22, 2023 |
| Apple         | MacPro4,1                   | Desktop     | [c368087050](https://bsd-hardware.info/?probe=c368087050) | Sep 20, 2023 |
| Dell          | XPS 9320                    | Notebook    | [d80b3d5a54](https://bsd-hardware.info/?probe=d80b3d5a54) | Sep 14, 2023 |
| Dell          | Latitude E6420              | Notebook    | [b90b748742](https://bsd-hardware.info/?probe=b90b748742) | Sep 14, 2023 |
| Huanan        | X99-F8D PLUS V1.3           | Desktop     | [53d31a28bf](https://bsd-hardware.info/?probe=53d31a28bf) | Sep 14, 2023 |
| Lenovo        | ThinkPad X140e 20BMS03E0... | Notebook    | [54b04ea958](https://bsd-hardware.info/?probe=54b04ea958) | Sep 12, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS (W... | Desktop     | [89a601d720](https://bsd-hardware.info/?probe=89a601d720) | Sep 12, 2023 |
| Supermicro    | X8DTH-i/6/iF/6F             | Desktop     | [df114e1b94](https://bsd-hardware.info/?probe=df114e1b94) | Sep 09, 2023 |
| Apple         | PowerMac3,6                 | Desktop     | [36daf7ce75](https://bsd-hardware.info/?probe=36daf7ce75) | Sep 09, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [8f54654916](https://bsd-hardware.info/?probe=8f54654916) | Sep 01, 2023 |
| VIA Techno... | VT8623-8235                 | Desktop     | [3274cd095e](https://bsd-hardware.info/?probe=3274cd095e) | Aug 31, 2023 |
| MSI           | MS-7125                     | Desktop     | [3dfb767d80](https://bsd-hardware.info/?probe=3dfb767d80) | Aug 30, 2023 |
| Dell          | Latitude 7280               | Notebook    | [c858f191cf](https://bsd-hardware.info/?probe=c858f191cf) | Aug 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [c8e95f3772](https://bsd-hardware.info/?probe=c8e95f3772) | Aug 26, 2023 |
| Getac         | V110G2                      | Notebook    | [884803a6bd](https://bsd-hardware.info/?probe=884803a6bd) | Aug 25, 2023 |
| ASUSTek       | P5M2-R                      | Desktop     | [73135bf26d](https://bsd-hardware.info/?probe=73135bf26d) | Aug 25, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [27cf2b3e46](https://bsd-hardware.info/?probe=27cf2b3e46) | Aug 19, 2023 |
| MSI           | MS-7721                     | Desktop     | [a577019634](https://bsd-hardware.info/?probe=a577019634) | Aug 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [9beb5f6126](https://bsd-hardware.info/?probe=9beb5f6126) | Aug 17, 2023 |
| Fujitsu Si... | LIFEBOOK P1610              | Notebook    | [bb055a94f0](https://bsd-hardware.info/?probe=bb055a94f0) | Aug 12, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [63c10b6ae5](https://bsd-hardware.info/?probe=63c10b6ae5) | Aug 11, 2023 |
| Apple         | MacBookAir4,2               | Notebook    | [b1c97a3a9d](https://bsd-hardware.info/?probe=b1c97a3a9d) | Aug 09, 2023 |
| MSI           | MS-7623                     | Desktop     | [189fb4d7cc](https://bsd-hardware.info/?probe=189fb4d7cc) | Aug 08, 2023 |
| Apple         | MacBookAir4,2               | Notebook    | [4fdd124b61](https://bsd-hardware.info/?probe=4fdd124b61) | Aug 07, 2023 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [e74d459c5a](https://bsd-hardware.info/?probe=e74d459c5a) | Jul 28, 2023 |
| Lenovo        | ThinkPad T410 2522NP6       | Notebook    | [194b8efa98](https://bsd-hardware.info/?probe=194b8efa98) | Jul 25, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [d4a26f9214](https://bsd-hardware.info/?probe=d4a26f9214) | Jul 24, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [461ad23cc9](https://bsd-hardware.info/?probe=461ad23cc9) | Jul 24, 2023 |
| Lenovo        | B590 20208                  | Notebook    | [ce1aade2c0](https://bsd-hardware.info/?probe=ce1aade2c0) | Jul 24, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [1ac1ddd084](https://bsd-hardware.info/?probe=1ac1ddd084) | Jul 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [173fe60308](https://bsd-hardware.info/?probe=173fe60308) | Jul 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [26e44ab6e6](https://bsd-hardware.info/?probe=26e44ab6e6) | Jul 23, 2023 |
| ASUSTek       | 900                         | Notebook    | [2e55f5d4cc](https://bsd-hardware.info/?probe=2e55f5d4cc) | Jul 20, 2023 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | Notebook    | [386a80104d](https://bsd-hardware.info/?probe=386a80104d) | Jul 19, 2023 |
| IBM           | ThinkPad T43 1871F1G        | Notebook    | [d6fbc6ebfb](https://bsd-hardware.info/?probe=d6fbc6ebfb) | Jul 18, 2023 |
| Lenovo        | B590 20208                  | Notebook    | [f734b93999](https://bsd-hardware.info/?probe=f734b93999) | Jul 16, 2023 |
| Sony          | VPCX115KX                   | Notebook    | [9dab449a23](https://bsd-hardware.info/?probe=9dab449a23) | Jul 15, 2023 |
| Tactus        | GeoBook 140                 | Notebook    | [4b7383c876](https://bsd-hardware.info/?probe=4b7383c876) | Jul 11, 2023 |
| Sony          | VGC-RB41M                   | Desktop     | [95804a1f40](https://bsd-hardware.info/?probe=95804a1f40) | Jun 28, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS (W... | Desktop     | [4d99bc4b63](https://bsd-hardware.info/?probe=4d99bc4b63) | Jun 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS (W... | Desktop     | [8866724f46](https://bsd-hardware.info/?probe=8866724f46) | Jun 27, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [ff83a965d2](https://bsd-hardware.info/?probe=ff83a965d2) | Jun 15, 2023 |
| Lenovo        | ThinkPad T430 2344BZU       | Notebook    | [01df487b47](https://bsd-hardware.info/?probe=01df487b47) | Jun 14, 2023 |
| Gigabyte      | G41MT-S2                    | Desktop     | [355202536f](https://bsd-hardware.info/?probe=355202536f) | Jun 07, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [9f18b1b304](https://bsd-hardware.info/?probe=9f18b1b304) | Jun 06, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [85c18dbbb5](https://bsd-hardware.info/?probe=85c18dbbb5) | Jun 06, 2023 |
| Toshiba       | NB250                       | Notebook    | [62c572e895](https://bsd-hardware.info/?probe=62c572e895) | May 27, 2023 |
| Tactus        | GeoFlex 110                 | Notebook    | [df93ad7e83](https://bsd-hardware.info/?probe=df93ad7e83) | May 27, 2023 |
| Lenovo        | ThinkPad X140e 20BMS03E0... | Notebook    | [580c52399f](https://bsd-hardware.info/?probe=580c52399f) | May 25, 2023 |
| Lenovo        | ThinkPad X140e 20BMS03E0... | Notebook    | [84e3ac62d5](https://bsd-hardware.info/?probe=84e3ac62d5) | May 23, 2023 |
| Unknown       | Apple MacBook Pro (13-in... | Notebook    | [5e25a49c65](https://bsd-hardware.info/?probe=5e25a49c65) | May 20, 2023 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [4c8047dca3](https://bsd-hardware.info/?probe=4c8047dca3) | May 19, 2023 |
| VIA Techno... | VT82C597                    | Desktop     | [d73db58e48](https://bsd-hardware.info/?probe=d73db58e48) | May 19, 2023 |
| Lenovo        | ThinkPad X201 3323BBG       | Notebook    | [7b529b0888](https://bsd-hardware.info/?probe=7b529b0888) | May 17, 2023 |
| HP            | 0A60h                       | Desktop     | [98e9deff3d](https://bsd-hardware.info/?probe=98e9deff3d) | May 16, 2023 |
| Lenovo        | ThinkPad T61 7659AS5        | Notebook    | [7732b2cfa7](https://bsd-hardware.info/?probe=7732b2cfa7) | May 15, 2023 |
| PC Engines    | APU2                        | Desktop     | [62fef2616b](https://bsd-hardware.info/?probe=62fef2616b) | May 15, 2023 |
| Lenovo        | ThinkPad T61 7659AS5        | Notebook    | [b6071c549a](https://bsd-hardware.info/?probe=b6071c549a) | May 15, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [2ce057e389](https://bsd-hardware.info/?probe=2ce057e389) | May 14, 2023 |
| ASUSTek       | M3A78-EMH HDMI              | Desktop     | [b4bf04ac2f](https://bsd-hardware.info/?probe=b4bf04ac2f) | May 13, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | Desktop     | [fa87f4741a](https://bsd-hardware.info/?probe=fa87f4741a) | May 13, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | Desktop     | [bd81294acc](https://bsd-hardware.info/?probe=bd81294acc) | May 13, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [cace71018f](https://bsd-hardware.info/?probe=cace71018f) | May 11, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [4353bb0195](https://bsd-hardware.info/?probe=4353bb0195) | May 09, 2023 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [be83fbb0f2](https://bsd-hardware.info/?probe=be83fbb0f2) | May 09, 2023 |
| Lenovo        | ThinkPad T410 2537N24       | Notebook    | [6cd0f02045](https://bsd-hardware.info/?probe=6cd0f02045) | May 08, 2023 |
| Matsushita... | CF-48V4KNDQM                | Notebook    | [79f10d24d6](https://bsd-hardware.info/?probe=79f10d24d6) | May 07, 2023 |
| ASUSTek       | 1000HE                      | Notebook    | [36214f8bed](https://bsd-hardware.info/?probe=36214f8bed) | May 07, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [d2bd7a8764](https://bsd-hardware.info/?probe=d2bd7a8764) | May 07, 2023 |
| Lenovo        | ThinkPad T500 205663G       | Notebook    | [d706da9400](https://bsd-hardware.info/?probe=d706da9400) | May 06, 2023 |
| Lenovo        | ThinkPad T480s 20L8A00KC... | Notebook    | [44ddee0eec](https://bsd-hardware.info/?probe=44ddee0eec) | May 06, 2023 |
| Matsushita... | CF-51RCVDNLM                | Notebook    | [105a885451](https://bsd-hardware.info/?probe=105a885451) | May 05, 2023 |
| Lenovo        | ThinkPad T420s 41742BU      | Notebook    | [161fe49de4](https://bsd-hardware.info/?probe=161fe49de4) | May 05, 2023 |
| Lenovo        | ThinkPad X230 2325T4T       | Notebook    | [00303b7a59](https://bsd-hardware.info/?probe=00303b7a59) | May 05, 2023 |
| Lenovo        | ThinkPad X220 429043U       | Notebook    | [bb714a4350](https://bsd-hardware.info/?probe=bb714a4350) | May 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [28e76d5531](https://bsd-hardware.info/?probe=28e76d5531) | May 04, 2023 |
| Lenovo        | ThinkPad T430 2347GZU       | Notebook    | [8c3f486dbc](https://bsd-hardware.info/?probe=8c3f486dbc) | May 03, 2023 |
| Panasonic     | CF-52PFPBSFQ                | Notebook    | [e2c3df29b5](https://bsd-hardware.info/?probe=e2c3df29b5) | May 03, 2023 |
| Panasonic     | CF-53AAGHYDM                | Notebook    | [c7daf17edb](https://bsd-hardware.info/?probe=c7daf17edb) | May 02, 2023 |
| Lenovo        | ThinkPad X260 20F5S2GM00    | Notebook    | [c4af168c4a](https://bsd-hardware.info/?probe=c4af168c4a) | May 01, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [cf504f51df](https://bsd-hardware.info/?probe=cf504f51df) | May 01, 2023 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [44ea9fb6ae](https://bsd-hardware.info/?probe=44ea9fb6ae) | Apr 30, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [247810c987](https://bsd-hardware.info/?probe=247810c987) | Apr 24, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | Desktop     | [827308827b](https://bsd-hardware.info/?probe=827308827b) | Apr 24, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [243a9c2f22](https://bsd-hardware.info/?probe=243a9c2f22) | Apr 22, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [c26c1111c6](https://bsd-hardware.info/?probe=c26c1111c6) | Apr 21, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | Desktop     | [a6141b809a](https://bsd-hardware.info/?probe=a6141b809a) | Apr 21, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [0ebba481d1](https://bsd-hardware.info/?probe=0ebba481d1) | Apr 14, 2023 |
| Lenovo        | ThinkPad T440s 20ARA07PL... | Notebook    | [04ddab3620](https://bsd-hardware.info/?probe=04ddab3620) | Apr 14, 2023 |
| Lenovo        | ThinkPad X230 23257EP       | Notebook    | [e94085cd2d](https://bsd-hardware.info/?probe=e94085cd2d) | Apr 12, 2023 |
| ASUSTek       | P10S-I Series               | Desktop     | [5084c2b77f](https://bsd-hardware.info/?probe=5084c2b77f) | Apr 11, 2023 |
| Apple         | MacPro1,1                   | Desktop     | [6843822d8c](https://bsd-hardware.info/?probe=6843822d8c) | Apr 11, 2023 |
| PC Engines    | APU2                        | Desktop     | [cdcdfe6e0b](https://bsd-hardware.info/?probe=cdcdfe6e0b) | Apr 10, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [a149d0b4b5](https://bsd-hardware.info/?probe=a149d0b4b5) | Apr 10, 2023 |
| Lenovo        | ThinkPad T450s 20BW001KL... | Notebook    | [4f6a7e2739](https://bsd-hardware.info/?probe=4f6a7e2739) | Apr 02, 2023 |
| Elpitech      | ET101-A1                    | Desktop     | [0172697883](https://bsd-hardware.info/?probe=0172697883) | Mar 10, 2023 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| amd64  | 64        | 81.01%  |
| i386   | 12        | 15.19%  |
| arm64  | 2         | 2.53%   |
| macppc | 1         | 1.27%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 67        | 84.81%  |
| GNOME        | 8         | 10.13%  |
| XFCE         | 3         | 3.8%    |
| MATE         | 1         | 1.27%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 69        | 87.34%  |
| Console | 10        | 12.66%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 79        | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 64        | 81.01%  |
| en_US   | 8         | 10.13%  |
| C       | 2         | 2.53%   |
| zh_TW   | 1         | 1.27%   |
| ru_RU   | 1         | 1.27%   |
| pl_PL   | 1         | 1.27%   |
| es_ES   | 1         | 1.27%   |
| en_EN   | 1         | 1.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 41        | 51.25%  |
| EFI  | 39        | 48.75%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ffs  | 79        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| MBR  | 43        | 53.75%  |
| GPT  | 37        | 46.25%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 25        | 31.65%  |
| ASUSTek Computer               | 12        | 15.19%  |
| MSI                            | 4         | 5.06%   |
| Hewlett-Packard                | 4         | 5.06%   |
| Dell                           | 4         | 5.06%   |
| Apple                          | 4         | 5.06%   |
| PC Engines                     | 3         | 3.8%    |
| Panasonic                      | 3         | 3.8%    |
| VIA Technologies               | 2         | 2.53%   |
| Tactus                         | 2         | 2.53%   |
| Sony                           | 2         | 2.53%   |
| Matsushita Electric Industrial | 2         | 2.53%   |
| Gigabyte Technology            | 2         | 2.53%   |
| Toshiba                        | 1         | 1.27%   |
| Supermicro                     | 1         | 1.27%   |
| IBM                            | 1         | 1.27%   |
| Huanan                         | 1         | 1.27%   |
| GPD                            | 1         | 1.27%   |
| Getac                          | 1         | 1.27%   |
| Fujitsu Siemens                | 1         | 1.27%   |
| Fujitsu                        | 1         | 1.27%   |
| Elpitech                       | 1         | 1.27%   |
| Unknown                        | 1         | 1.27%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| PC Engines APU2                             | 2         | 2.53%   |
| ASUS PRIME B650-PLUS                        | 2         | 2.53%   |
| VIA VT8623-8235                             | 1         | 1.27%   |
| VIA VT82C597                                | 1         | 1.27%   |
| Toshiba NB250                               | 1         | 1.27%   |
| Tactus GeoFlex 110                          | 1         | 1.27%   |
| Tactus GeoBook 140                          | 1         | 1.27%   |
| Supermicro X8DTH-i/6/iF/6F                  | 1         | 1.27%   |
| Sony VPCX115KX                              | 1         | 1.27%   |
| Sony VGC-RB41M                              | 1         | 1.27%   |
| PC Engines APU                              | 1         | 1.27%   |
| Panasonic CFSX4-1                           | 1         | 1.27%   |
| Panasonic CF-53AAGHYDM                      | 1         | 1.27%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 1.27%   |
| MSI MS-7721                                 | 1         | 1.27%   |
| MSI MS-7623                                 | 1         | 1.27%   |
| MSI MS-7592                                 | 1         | 1.27%   |
| MSI MS-7125                                 | 1         | 1.27%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 1.27%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 1.27%   |
| Lenovo V14 G2 ITL 82NM                      | 1         | 1.27%   |
| Lenovo ThinkPad X270 W10DG 20K5S0TT1N       | 1         | 1.27%   |
| Lenovo ThinkPad X260 20F5S2GM00             | 1         | 1.27%   |
| Lenovo ThinkPad X260 20F5S10W0H             | 1         | 1.27%   |
| Lenovo ThinkPad X230 2325T4T                | 1         | 1.27%   |
| Lenovo ThinkPad X230 23257EP                | 1         | 1.27%   |
| Lenovo ThinkPad X220 429043U                | 1         | 1.27%   |
| Lenovo ThinkPad X201 3323BBG                | 1         | 1.27%   |
| Lenovo ThinkPad X140e 20BMS03E00            | 1         | 1.27%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD001UUS    | 1         | 1.27%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS13H00    | 1         | 1.27%   |
| Lenovo ThinkPad T61 7659AS5                 | 1         | 1.27%   |
| Lenovo ThinkPad T500 205663G                | 1         | 1.27%   |
| Lenovo ThinkPad T480s 20L8A00KCL            | 1         | 1.27%   |
| Lenovo ThinkPad T450s 20BW001KLM            | 1         | 1.27%   |
| Lenovo ThinkPad T440s 20ARA07PLM            | 1         | 1.27%   |
| Lenovo ThinkPad T430 2347GZU                | 1         | 1.27%   |
| Lenovo ThinkPad T430 2344BZU                | 1         | 1.27%   |
| Lenovo ThinkPad T420s 41742BU               | 1         | 1.27%   |
| Lenovo ThinkPad T410 2537N24                | 1         | 1.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad                             | 22        | 27.85%  |
| ASUS PRIME                                  | 4         | 5.06%   |
| Dell Latitude                               | 3         | 3.8%    |
| PC Engines APU2                             | 2         | 2.53%   |
| HP Pavilion                                 | 2         | 2.53%   |
| ASUS TUF                                    | 2         | 2.53%   |
| VIA VT8623-8235                             | 1         | 1.27%   |
| VIA VT82C597                                | 1         | 1.27%   |
| Toshiba NB250                               | 1         | 1.27%   |
| Tactus GeoFlex                              | 1         | 1.27%   |
| Tactus GeoBook                              | 1         | 1.27%   |
| Supermicro X8DTH-i                          | 1         | 1.27%   |
| Sony VPCX115KX                              | 1         | 1.27%   |
| Sony VGC-RB41M                              | 1         | 1.27%   |
| PC Engines APU                              | 1         | 1.27%   |
| Panasonic CFSX4-1                           | 1         | 1.27%   |
| Panasonic CF-53AAGHYDM                      | 1         | 1.27%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 1.27%   |
| MSI MS-7721                                 | 1         | 1.27%   |
| MSI MS-7623                                 | 1         | 1.27%   |
| MSI MS-7592                                 | 1         | 1.27%   |
| MSI MS-7125                                 | 1         | 1.27%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 1.27%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 1.27%   |
| Lenovo V14                                  | 1         | 1.27%   |
| Lenovo G570                                 | 1         | 1.27%   |
| Lenovo B590                                 | 1         | 1.27%   |
| IBM ThinkPad                                | 1         | 1.27%   |
| Huanan X99-F8D                              | 1         | 1.27%   |
| HP ProLiant                                 | 1         | 1.27%   |
| HP Compaq                                   | 1         | 1.27%   |
| GPD G1619-04                                | 1         | 1.27%   |
| Gigabyte G41MT-S2                           | 1         | 1.27%   |
| Gigabyte B250M-Gaming                       | 1         | 1.27%   |
| Getac V110G2                                | 1         | 1.27%   |
| Fujitsu Siemens LIFEBOOK                    | 1         | 1.27%   |
| Fujitsu LIFEBOOK                            | 1         | 1.27%   |
| Elpitech ET101-A1                           | 1         | 1.27%   |
| Dell XPS                                    | 1         | 1.27%   |
| ASUS VivoBook                               | 1         | 1.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2023    | 8         | 10.13%  |
| 2010    | 8         | 10.13%  |
| 2011    | 6         | 7.59%   |
| 2022    | 5         | 6.33%   |
| 2019    | 5         | 6.33%   |
| 2016    | 5         | 6.33%   |
| 2006    | 5         | 6.33%   |
| 2020    | 4         | 5.06%   |
| 2013    | 4         | 5.06%   |
| 2012    | 4         | 5.06%   |
| 2009    | 4         | 5.06%   |
| 2021    | 3         | 3.8%    |
| 2018    | 3         | 3.8%    |
| 2015    | 3         | 3.8%    |
| 2007    | 3         | 3.8%    |
| Unknown | 3         | 3.8%    |
| 2014    | 2         | 2.53%   |
| 2017    | 1         | 1.27%   |
| 2005    | 1         | 1.27%   |
| 2004    | 1         | 1.27%   |
| 2002    | 1         | 1.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 49        | 62.03%  |
| Desktop  | 29        | 36.71%  |
| Server   | 1         | 1.27%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 75        | 94.94%  |
| Yes  | 4         | 5.06%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 21        | 25.93%  |
| 4.01-8.0    | 18        | 22.22%  |
| 16.01-24.0  | 11        | 13.58%  |
| 3.01-4.0    | 7         | 8.64%   |
| 2.01-3.0    | 6         | 7.41%   |
| 64.01-256.0 | 5         | 6.17%   |
| 32.01-64.0  | 4         | 4.94%   |
| 0.51-1.0    | 3         | 3.7%    |
| 0.01-0.5    | 3         | 3.7%    |
| 24.01-32.0  | 2         | 2.47%   |
| 1.01-2.0    | 1         | 1.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 61        | 77.22%  |
| 0        | 7         | 8.86%   |
| 1.01-2.0 | 4         | 5.06%   |
| 0.51-1.0 | 4         | 5.06%   |
| 4.01-8.0 | 3         | 3.8%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 44        | 54.32%  |
| 2      | 22        | 27.16%  |
| 3      | 8         | 9.88%   |
| 0      | 4         | 4.94%   |
| 8      | 1         | 1.23%   |
| 6      | 1         | 1.23%   |
| 4      | 1         | 1.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 79        | 100%    |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 69        | 87.34%  |
| No        | 10        | 12.66%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 50        | 63.29%  |
| No        | 29        | 36.71%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 44        | 54.32%  |
| Yes       | 37        | 45.68%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| Russia             | 21        | 26.58%  |
| Canada             | 14        | 17.72%  |
| USA                | 8         | 10.13%  |
| Germany            | 6         | 7.59%   |
| Brazil             | 6         | 7.59%   |
| Uruguay            | 3         | 3.8%    |
| Poland             | 3         | 3.8%    |
| Mexico             | 3         | 3.8%    |
| Italy              | 3         | 3.8%    |
| Spain              | 2         | 2.53%   |
| Romania            | 2         | 2.53%   |
| Colombia           | 2         | 2.53%   |
| Ukraine            | 1         | 1.27%   |
| Taiwan             | 1         | 1.27%   |
| Switzerland        | 1         | 1.27%   |
| France             | 1         | 1.27%   |
| Dominican Republic | 1         | 1.27%   |
| China              | 1         | 1.27%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Saint-Laurent           | 14        | 17.72%  |
| St Petersburg           | 13        | 16.46%  |
| Blumenau                | 5         | 6.33%   |
| Sun Prairie             | 3         | 3.8%    |
| Puebla City             | 3         | 3.8%    |
| Moscow                  | 3         | 3.8%    |
| Montevideo              | 3         | 3.8%    |
| Milan                   | 3         | 3.8%    |
| Nuremberg               | 2         | 2.53%   |
| Montería               | 2         | 2.53%   |
| Lübeck                 | 2         | 2.53%   |
| Cherepovets             | 2         | 2.53%   |
| Austin                  | 2         | 2.53%   |
| Wroclaw                 | 1         | 1.27%   |
| Taipei                  | 1         | 1.27%   |
| Swilcza                 | 1         | 1.27%   |
| Sao Paulo               | 1         | 1.27%   |
| Santo Domingo           | 1         | 1.27%   |
| San Francisco           | 1         | 1.27%   |
| Roswell                 | 1         | 1.27%   |
| Podolsk                 | 1         | 1.27%   |
| Piaseczno               | 1         | 1.27%   |
| Oltenita                | 1         | 1.27%   |
| Novosibirsk             | 1         | 1.27%   |
| Navalcarnero            | 1         | 1.27%   |
| Monheim am Rhein        | 1         | 1.27%   |
| Les Pavillons-sous-Bois | 1         | 1.27%   |
| Krasnodar               | 1         | 1.27%   |
| Kansas City             | 1         | 1.27%   |
| Harbin                  | 1         | 1.27%   |
| Hamburg                 | 1         | 1.27%   |
| Brovary                 | 1         | 1.27%   |
| Brasov                  | 1         | 1.27%   |
| Belp                    | 1         | 1.27%   |
| Barcelona               | 1         | 1.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| NVMe                | 18        | 25     | 18.37%  |
| Samsung Electronics | 12        | 18     | 12.24%  |
| WDC                 | 10        | 10     | 10.2%   |
| Seagate             | 7         | 9      | 7.14%   |
| SanDisk             | 6         | 8      | 6.12%   |
| Kingston            | 6         | 6      | 6.12%   |
| Intel               | 6         | 6      | 6.12%   |
| Hitachi             | 6         | 6      | 6.12%   |
| Crucial             | 3         | 4      | 3.06%   |
| Apacer              | 3         | 3      | 3.06%   |
| Toshiba             | 2         | 2      | 2.04%   |
| OPENBSD             | 2         | 2      | 2.04%   |
| Intenso             | 2         | 2      | 2.04%   |
| Fujitsu             | 2         | 2      | 2.04%   |
| A-DATA Technology   | 2         | 2      | 2.04%   |
| Verbatim            | 1         | 1      | 1.02%   |
| Union Memory        | 1         | 1      | 1.02%   |
| SMI                 | 1         | 1      | 1.02%   |
| PNY                 | 1         | 2      | 1.02%   |
| LSI                 | 1         | 1      | 1.02%   |
| KIOXIA-EXCERIA      | 1         | 1      | 1.02%   |
| JetFlash            | 1         | 1      | 1.02%   |
| HGST                | 1         | 1      | 1.02%   |
| ASUSTek Computer    | 1         | 2      | 1.02%   |
| Apple               | 1         | 1      | 1.02%   |
| AMD                 | 1         | 1      | 1.02%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Intel SSDSC2BW480H6 480GB           | 5         | 4.81%   |
| SanDisk SSD PLUS 120GB              | 2         | 1.92%   |
| SanDisk Extreme SSD 500GB           | 2         | 1.92%   |
| Samsung SSD 840 EVO 250GB           | 2         | 1.92%   |
| NVMe Samsung SSD 980 500GB          | 2         | 1.92%   |
| NVMe SAMSUNG MZVLW256 256GB         | 2         | 1.92%   |
| Kingston SA400S37480G 480GB         | 2         | 1.92%   |
| Intenso SSD 256GB                   | 2         | 1.92%   |
| WDC WD7500BPKX-00HPJT0 752GB        | 1         | 0.96%   |
| WDC WD7500BPKT-75PK4T0 752GB        | 1         | 0.96%   |
| WDC WD7500BPKT-00PK4T0 752GB        | 1         | 0.96%   |
| WDC WD5000LPLX-00ZNTT0 500GB        | 1         | 0.96%   |
| WDC WD5000AZLX-00K2TA0 500GB        | 1         | 0.96%   |
| WDC WD3201ABYS-01B9A0 320GB         | 1         | 0.96%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 1         | 0.96%   |
| WDC WD3200BEVE-00A0HT0 320GB        | 1         | 0.96%   |
| WDC WD20PURX-64P6ZY0 2TB            | 1         | 0.96%   |
| WDC WD10JPLX-00MBPT0 1TB            | 1         | 0.96%   |
| Verbatim STORE N GO 64GB            | 1         | 0.96%   |
| Union Memory RTOTJ128VGD2EYX 128GB  | 1         | 0.96%   |
| Toshiba MK8007GAH 80GB              | 1         | 0.96%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB | 1         | 0.96%   |
| SMI USB DISK 18302PB                | 1         | 0.96%   |
| Seagate USB 480GB                   | 1         | 0.96%   |
| Seagate ST9160821A 160GB            | 1         | 0.96%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 0.96%   |
| Seagate ST3500630AS 500GB           | 1         | 0.96%   |
| Seagate ST3500414CS 500GB           | 1         | 0.96%   |
| Seagate ST3250824AS P 250GB         | 1         | 0.96%   |
| Seagate ST3250318AS 250GB           | 1         | 0.96%   |
| Seagate ST320011A 20GB              | 1         | 0.96%   |
| SanDisk X400 M.2 2280 512GB         | 1         | 0.96%   |
| SanDisk SSD PLUS 240GB              | 1         | 0.96%   |
| SanDisk Cruzer Blade 64GB           | 1         | 0.96%   |
| Samsung SSD 870 QVO 2TB             | 1         | 0.96%   |
| Samsung SSD 870 EVO 500GB           | 1         | 0.96%   |
| Samsung SSD 870 EVO 250GB           | 1         | 0.96%   |
| Samsung SSD 860 EVO M.2 1TB         | 1         | 0.96%   |
| Samsung SSD 850 EVO 500GB           | 1         | 0.96%   |
| Samsung MZ7TD128HAFV-000L1 128GB    | 1         | 0.96%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| NVMe                | 12        | 18     | 25.53%  |
| WDC                 | 10        | 10     | 21.28%  |
| Seagate             | 7         | 9      | 14.89%  |
| Hitachi             | 6         | 6      | 12.77%  |
| Samsung Electronics | 2         | 2      | 4.26%   |
| OPENBSD             | 2         | 2      | 4.26%   |
| Fujitsu             | 2         | 2      | 4.26%   |
| Verbatim            | 1         | 1      | 2.13%   |
| Toshiba             | 1         | 1      | 2.13%   |
| SMI                 | 1         | 1      | 2.13%   |
| LSI                 | 1         | 1      | 2.13%   |
| JetFlash            | 1         | 1      | 2.13%   |
| HGST                | 1         | 1      | 2.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 16     | 19.61%  |
| SanDisk             | 6         | 8      | 11.76%  |
| NVMe                | 6         | 6      | 11.76%  |
| Kingston            | 6         | 6      | 11.76%  |
| Intel               | 6         | 6      | 11.76%  |
| Crucial             | 3         | 4      | 5.88%   |
| Apacer              | 3         | 3      | 5.88%   |
| Intenso             | 2         | 2      | 3.92%   |
| A-DATA Technology   | 2         | 2      | 3.92%   |
| Union Memory        | 1         | 1      | 1.96%   |
| Toshiba             | 1         | 1      | 1.96%   |
| PNY                 | 1         | 2      | 1.96%   |
| KIOXIA-EXCERIA      | 1         | 1      | 1.96%   |
| ASUSTek Computer    | 1         | 2      | 1.96%   |
| Apple               | 1         | 1      | 1.96%   |
| AMD                 | 1         | 1      | 1.96%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 47        | 62     | 54.02%  |
| HDD  | 39        | 55     | 44.83%  |
| NVMe | 1         | 1      | 1.15%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 74        | 117    | 98.67%  |
| NVMe | 1         | 1      | 1.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 62        | 87     | 76.54%  |
| 0.51-1.0        | 10        | 11     | 12.35%  |
| 1.01-2.0        | 7         | 17     | 8.64%   |
| More than 100.0 | 1         | 1      | 1.23%   |
| 4.01-10.0       | 1         | 1      | 1.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 24        | 29.63%  |
| 251-500        | 21        | 25.93%  |
| 21-50          | 15        | 18.52%  |
| 1-20           | 7         | 8.64%   |
| 51-100         | 7         | 8.64%   |
| 501-1000       | 3         | 3.7%    |
| More than 3000 | 2         | 2.47%   |
| 1001-2000      | 2         | 2.47%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 61        | 75.31%  |
| 21-50          | 10        | 12.35%  |
| 101-250        | 4         | 4.94%   |
| 51-100         | 3         | 3.7%    |
| More than 3000 | 1         | 1.23%   |
| 251-500        | 1         | 1.23%   |
| 2001-3000      | 1         | 1.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Intel SSDSC2BW480H6 480GB             | 5         | 5      | 41.67%  |
| SanDisk SSD PLUS 240GB                | 1         | 1      | 8.33%   |
| Samsung Electronics SSD 870 EVO 500GB | 1         | 1      | 8.33%   |
| Samsung Electronics SSD 840 EVO 250GB | 1         | 2      | 8.33%   |
| Samsung Electronics HD161HJ 160GB     | 1         | 1      | 8.33%   |
| Hitachi HDS722516VLAT80 164GB         | 1         | 1      | 8.33%   |
| A-DATA Technology SP550 480GB         | 1         | 1      | 8.33%   |
| A-DATA Technology SP550 240GB         | 1         | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Intel               | 5         | 5      | 41.67%  |
| Samsung Electronics | 3         | 4      | 25%     |
| A-DATA Technology   | 2         | 2      | 16.67%  |
| SanDisk             | 1         | 1      | 8.33%   |
| Hitachi             | 1         | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 50%     |
| Hitachi             | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 10        | 11     | 83.33%  |
| HDD  | 2         | 2      | 16.67%  |

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
| Works    | 52        | 72     | 61.18%  |
| Detected | 21        | 33     | 24.71%  |
| Malfunc  | 12        | 13     | 14.12%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 51        | 59.3%   |
| AMD                            | 12        | 13.95%  |
| Samsung Electronics            | 6         | 6.98%   |
| Kingston Technology Company    | 3         | 3.49%   |
| VIA Technologies               | 2         | 2.33%   |
| SanDisk                        | 2         | 2.33%   |
| Phison Electronics             | 2         | 2.33%   |
| Toshiba                        | 1         | 1.16%   |
| Solid State Storage Technology | 1         | 1.16%   |
| Silicon Motion                 | 1         | 1.16%   |
| Nvidia                         | 1         | 1.16%   |
| Hewlett-Packard                | 1         | 1.16%   |
| Broadcom / LSI                 | 1         | 1.16%   |
| Biwin Storage Technology       | 1         | 1.16%   |
| Artop Electronic               | 1         | 1.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 6         | 6.25%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 6         | 6.25%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 5         | 5.21%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 5         | 5.21%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                | 4         | 4.17%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 3         | 3.13%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 3         | 3.13%   |
| Intel 82801G (ICH7 Family) IDE Controller                                     | 3         | 3.13%   |
| AMD 500 Series Chipset SATA Controller                                        | 3         | 3.13%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                   | 2         | 2.08%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                    | 2         | 2.08%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 2         | 2.08%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                             | 2         | 2.08%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 2         | 2.08%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                 | 2         | 2.08%   |
| Intel 82801FBM (ICH6M) SATA Controller                                        | 2         | 2.08%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 2         | 2.08%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                          | 2         | 2.08%   |
| AMD FCH SATA Controller [IDE mode]                                            | 2         | 2.08%   |
| Toshiba BG3 NVMe SSD Controller                                               | 1         | 1.04%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                | 1         | 1.04%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers             | 1         | 1.04%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                   | 1         | 1.04%   |
| Phison PS5013 E13 NVMe Controller                                             | 1         | 1.04%   |
| Phison E16 PCIe4 NVMe Controller                                              | 1         | 1.04%   |
| Nvidia CK804 Serial ATA Controller                                            | 1         | 1.04%   |
| Nvidia CK804 IDE                                                              | 1         | 1.04%   |
| Kingston Company unknown                                                      | 1         | 1.04%   |
| Kingston Company NVMe Controller                                              | 1         | 1.04%   |
| Kingston Company NV1 NVMe SSD                                                 | 1         | 1.04%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                    | 1         | 1.04%   |
| Intel Tiger Lake-LP SATA Controller                                           | 1         | 1.04%   |
| Intel SSD 670p Series [Keystone Harbor]                                       | 1         | 1.04%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1         | 1.04%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                            | 1         | 1.04%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 1         | 1.04%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]              | 1         | 1.04%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                             | 1         | 1.04%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]         | 1         | 1.04%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]           | 1         | 1.04%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 48        | 55.17%  |
| IDE  | 20        | 22.99%  |
| NVMe | 16        | 18.39%  |
| RAID | 2         | 2.3%    |
| SCSI | 1         | 1.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 57        | 72.15%  |
| AMD     | 18        | 22.78%  |
| Unknown | 2         | 2.53%   |
| VIA     | 1         | 1.27%   |
| ARM     | 1         | 1.27%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz                               | 5         | 6.33%   |
| Intel Core i5-3320M CPU @ 2.60GHz                               | 4         | 5.06%   |
| Intel Core i5-2520M CPU @ 2.50GHz                               | 3         | 3.8%    |
| Intel Core i5 CPU M 520 @ 2.40GHz                               | 3         | 3.8%    |
| Intel Core i5-5300U CPU @ 2.30GHz                               | 2         | 2.53%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz                           | 2         | 2.53%   |
| Intel Celeron N4020 CPU @ 1.10GHz                               | 2         | 2.53%   |
| AMD GX-412TC SOC                                                | 2         | 2.53%   |
|                                                                 | 2         | 2.53%   |
| VIA C3                                                          | 1         | 1.27%   |
| Intel Xeon CPU X5675 @ 3.07GHz                                  | 1         | 1.27%   |
| Intel Xeon CPU X5550 @ 2.67GHz                                  | 1         | 1.27%   |
| Intel Xeon CPU E5-2697 v4 @ 2.30GHz                             | 1         | 1.27%   |
| Intel Xeon CPU E5-2690 v4 @ 2.60GHz                             | 1         | 1.27%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz                             | 1         | 1.27%   |
| Intel Xeon CPU 5150 @ 2.66GHz                                   | 1         | 1.27%   |
| Intel Pentium M processor                                       | 1         | 1.27%   |
| Intel Pentium 4 Mobile CPU 1.60GHz                              | 1         | 1.27%   |
| Intel Pentium 4 CPU 3.00GHz ("GenuineIntel" 686-class)          | 1         | 1.27%   |
| Intel Genuine CPU U1400                                         | 1         | 1.27%   |
| Intel Genuine CPU T2300 @ 1.66GHz                               | 1         | 1.27%   |
| Intel Core i7-8650U CPU @ 1.90GHz                               | 1         | 1.27%   |
| Intel Core i7-6600U CPU @ 2.60GHz                               | 1         | 1.27%   |
| Intel Core i7-3520M CPU @ 2.90GHz                               | 1         | 1.27%   |
| Intel Core i5-8300H CPU @ 2.30GHz                               | 1         | 1.27%   |
| Intel Core i5-8265U CPU @ 1.60GHz                               | 1         | 1.27%   |
| Intel Core i5-7400 CPU @ 3.00GHz                                | 1         | 1.27%   |
| Intel Core i5-6200U CPU @ 2.30GHz                               | 1         | 1.27%   |
| Intel Core i5-5200U CPU @ 2.20GHz                               | 1         | 1.27%   |
| Intel Core i5-4300U CPU @ 1.90GHz                               | 1         | 1.27%   |
| Intel Core i5-2557M CPU @ 1.70GHz                               | 1         | 1.27%   |
| Intel Core i5-2540M CPU @ 2.60GHz                               | 1         | 1.27%   |
| Intel Core i5-2410M CPU @ 2.30GHz                               | 1         | 1.27%   |
| Intel Core i3-3120M CPU @ 2.50GHz                               | 1         | 1.27%   |
| Intel Core i3-10100 CPU @ 3.60GHz                               | 1         | 1.27%   |
| Intel Core i3 CPU M 350 @ 2.27GHz                               | 1         | 1.27%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz                           | 1         | 1.27%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz                            | 1         | 1.27%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz ("GenuineIntel" 686-class) | 1         | 1.27%   |
| Intel Core 2 CPU 6420 @ 2.13GHz                                 | 1         | 1.27%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i5     | 26        | 32.91%  |
| Other             | 6         | 7.59%   |
| Intel Xeon        | 6         | 7.59%   |
| AMD Ryzen 7       | 5         | 6.33%   |
| Intel Core i7     | 3         | 3.8%    |
| Intel Core i3     | 3         | 3.8%    |
| Intel Core 2 Quad | 3         | 3.8%    |
| Intel Atom        | 3         | 3.8%    |
| Intel Pentium 4   | 2         | 2.53%   |
| Intel Genuine     | 2         | 2.53%   |
| Intel Core 2 Duo  | 2         | 2.53%   |
| Intel Celeron     | 2         | 2.53%   |
| AMD Ryzen 9       | 2         | 2.53%   |
| AMD GX            | 2         | 2.53%   |
| Intel Pentium M   | 1         | 1.27%   |
| Intel Core 2      | 1         | 1.27%   |
| Intel Celeron M   | 1         | 1.27%   |
| ARM Cortex        | 1         | 1.27%   |
| AMD Ryzen 5 PRO   | 1         | 1.27%   |
| AMD Ryzen 5       | 1         | 1.27%   |
| AMD Phenom        | 1         | 1.27%   |
| AMD G             | 1         | 1.27%   |
| AMD E1            | 1         | 1.27%   |
| AMD Athlon X4     | 1         | 1.27%   |
| AMD Athlon II X2  | 1         | 1.27%   |
| AMD Athlon 64     | 1         | 1.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 33        | 41.77%  |
| Unknown | 14        | 17.72%  |
| 4       | 12        | 15.19%  |
| 1       | 6         | 7.59%   |
| 16      | 5         | 6.33%   |
| 32      | 2         | 2.53%   |
| 12      | 2         | 2.53%   |
| 8       | 2         | 2.53%   |
| 36      | 1         | 1.27%   |
| 14      | 1         | 1.27%   |
| 6       | 1         | 1.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 66        | 83.54%  |
| Unknown | 10        | 12.66%  |
| 2       | 3         | 3.8%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 37        | 46.84%  |
| 1       | 23        | 29.11%  |
| Unknown | 19        | 24.05%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Skylake       | 8         | 10.13%  |
| Unknown       | 8         | 10.13%  |
| SandyBridge   | 6         | 7.59%   |
| IvyBridge     | 6         | 7.59%   |
| Westmere      | 5         | 6.33%   |
| Core          | 5         | 6.33%   |
| Broadwell     | 5         | 6.33%   |
| Zen 2         | 4         | 5.06%   |
| P6            | 4         | 5.06%   |
| KabyLake      | 4         | 5.06%   |
| Bonnell       | 3         | 3.8%    |
| Zen 3         | 2         | 2.53%   |
| Puma          | 2         | 2.53%   |
| Penryn        | 2         | 2.53%   |
| NetBurst      | 2         | 2.53%   |
| K10           | 2         | 2.53%   |
| Goldmont plus | 2         | 2.53%   |
| TigerLake     | 1         | 1.27%   |
| Steamroller   | 1         | 1.27%   |
| Nehalem       | 1         | 1.27%   |
| K8 Hammer     | 1         | 1.27%   |
| Jaguar        | 1         | 1.27%   |
| Haswell       | 1         | 1.27%   |
| Geode         | 1         | 1.27%   |
| CometLake     | 1         | 1.27%   |
| Bobcat        | 1         | 1.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 47        | 59.49%  |
| AMD                        | 17        | 21.52%  |
| Nvidia                     | 11        | 13.92%  |
| Matrox Electronics Systems | 2         | 2.53%   |
| VIA Technologies           | 1         | 1.27%   |
| ASPEED Technology          | 1         | 1.27%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                           | 7         | 8.43%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 6         | 7.23%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 6         | 7.23%   |
| Intel Core Processor Integrated Graphics Controller                           | 4         | 4.82%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 3         | 3.61%   |
| Intel HD Graphics 5500                                                        | 3         | 3.61%   |
| AMD Renoir                                                                    | 3         | 3.61%   |
| Nvidia GK208B [GeForce GT 710]                                                | 2         | 2.41%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 2         | 2.41%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                     | 2         | 2.41%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 2         | 2.41%   |
| AMD Raphael                                                                   | 2         | 2.41%   |
| VIA Technologies VT8623 [Apollo CLE266] integrated CastleRock graphics        | 1         | 1.2%    |
| Nvidia GT200 [GeForce GTX 260]                                                | 1         | 1.2%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 1         | 1.2%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                           | 1         | 1.2%    |
| Nvidia GK208B [GeForce GT 730]                                                | 1         | 1.2%    |
| Nvidia GA104GL [RTX A4000]                                                    | 1         | 1.2%    |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                                | 1         | 1.2%    |
| Nvidia G96C [GeForce 9500 GT]                                                 | 1         | 1.2%    |
| Nvidia G73 [GeForce 7300 GT]                                                  | 1         | 1.2%    |
| Nvidia G72 [GeForce 7300 LE]                                                  | 1         | 1.2%    |
| Matrox Electronics Systems MGA G200eW WPCM450                                 | 1         | 1.2%    |
| Matrox Electronics Systems MGA G200EH                                         | 1         | 1.2%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 1         | 1.2%    |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                           | 1         | 1.2%    |
| Intel UHD Graphics 620                                                        | 1         | 1.2%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 1         | 1.2%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 1         | 1.2%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 1         | 1.2%    |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 1.2%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 1         | 1.2%    |
| Intel HD Graphics 630                                                         | 1         | 1.2%    |
| Intel Haswell-ULT Integrated Graphics Controller                              | 1         | 1.2%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                      | 1         | 1.2%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 1         | 1.2%    |
| Intel Alder Lake-P Integrated Graphics Controller                             | 1         | 1.2%    |
| Intel 82Q963/Q965 Integrated Graphics Controller                              | 1         | 1.2%    |
| Intel 82915G/GV/910GL Integrated Graphics Controller                          | 1         | 1.2%    |
| Intel 4 Series Chipset Integrated Graphics Controller                         | 1         | 1.2%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 37        | 46.84%  |
| 1 x AMD        | 13        | 16.46%  |
| 2 x Intel      | 7         | 8.86%   |
| 1 x Nvidia     | 7         | 8.86%   |
| Other          | 6         | 7.59%   |
| Intel + Nvidia | 2         | 2.53%   |
| AMD + Nvidia   | 2         | 2.53%   |
| 1 x VIA        | 1         | 1.27%   |
| 1 x Matrox     | 1         | 1.27%   |
| Intel + AMD    | 1         | 1.27%   |
| 1 x ASPEED     | 1         | 1.27%   |
| AMD + Matrox   | 1         | 1.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 67        | 84.81%  |
| Unknown | 12        | 15.19%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 79        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 8         | 19.05%  |
| Samsung Electronics  | 6         | 14.29%  |
| Philips              | 6         | 14.29%  |
| Chimei Innolux       | 3         | 7.14%   |
| ViewSonic            | 2         | 4.76%   |
| LG Display           | 2         | 4.76%   |
| BOE                  | 2         | 4.76%   |
| BenQ                 | 2         | 4.76%   |
| Apple                | 2         | 4.76%   |
| TRU                  | 1         | 2.38%   |
| MSI                  | 1         | 2.38%   |
| Lenovo               | 1         | 2.38%   |
| JDI                  | 1         | 2.38%   |
| Iiyama               | 1         | 2.38%   |
| Goldstar             | 1         | 2.38%   |
| ASUSTek Computer     | 1         | 2.38%   |
| AOC                  | 1         | 2.38%   |
| Ancor Communications | 1         | 2.38%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Philips 170S PHL0839 1280x1024 340x270mm 17.1-inch                    | 3         | 7.14%   |
| Samsung Electronics SyncMaster SAM03CF 1280x1024 340x270mm 17.1-inch  | 2         | 4.76%   |
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                 | 2         | 4.76%   |
| ViewSonic VA703-4SERIES VSC6A1E 1280x1024 340x270mm 17.1-inch         | 1         | 2.38%   |
| ViewSonic VA2418-FHD VSCD739 1920x1080 530x300mm 24.0-inch            | 1         | 2.38%   |
| TRU LCD Monitor TRU235C 1366x768 260x140mm 11.6-inch                  | 1         | 2.38%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch  | 1         | 2.38%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 310x170mm 13.9-inch  | 1         | 2.38%   |
| Samsung Electronics LCD Monitor SDC4163 3456x2160 290x180mm 13.4-inch | 1         | 2.38%   |
| Samsung Electronics LCD Monitor SAM0669 1920x1080                     | 1         | 2.38%   |
| Philips PHL 247E6 PHLC0E7 1920x1080 520x290mm 23.4-inch               | 1         | 2.38%   |
| MSI MP242 MSI30A1 1920x1080 530x300mm 24.0-inch                       | 1         | 2.38%   |
| LG Display LCD Monitor LGD02EB 1366x768 310x170mm 13.9-inch           | 1         | 2.38%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch           | 1         | 2.38%   |
| Lenovo LCD Monitor LEN4053 1680x1050 330x210mm 15.4-inch              | 1         | 2.38%   |
| JDI GPD1001H JDI0031 2560x1600 890x500mm 40.2-inch                    | 1         | 2.38%   |
| Iiyama PL2530H IVM6131 1920x1080 540x300mm 24.3-inch                  | 1         | 2.38%   |
| Goldstar LG ULTRAWIDE GSM76F9 2560x1080 800x340mm 34.2-inch           | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 340x190mm 15.3-inch      | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 310x170mm 13.9-inch      | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch      | 1         | 2.38%   |
| BOE LCD Monitor BOE08E2 1920x1080 340x190mm 15.3-inch                 | 1         | 2.38%   |
| BOE LCD Monitor BOE0653 1920x1080 310x170mm 13.9-inch                 | 1         | 2.38%   |
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                    | 1         | 2.38%   |
| BenQ GL2450 BNQ78A5 1920x1080 530x300mm 24.0-inch                     | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 310x170mm 13.9-inch        | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch         | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 310x170mm 13.9-inch         | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO2336 2560x1440 310x170mm 13.9-inch        | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch         | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO173D 1920x1080 310x170mm 13.9-inch        | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO1147 1440x900 300x190mm 14.0-inch         | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch         | 1         | 2.38%   |
| ASUSTek Computer PA279 AUS2768 3840x2160 600x340mm 27.2-inch          | 1         | 2.38%   |
| Apple Color LCD APPA010 1366x768 260x140mm 11.6-inch                  | 1         | 2.38%   |
| Apple Color LCD APP9CDF 1440x900 290x180mm 13.4-inch                  | 1         | 2.38%   |
| AOC 27V2G5 AOC2702 1920x1080 600x340mm 27.2-inch                      | 1         | 2.38%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 520x290mm 23.4-inch | 1         | 2.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 17        | 41.46%  |
| 1366x768 (WXGA)    | 8         | 19.51%  |
| 1280x1024 (SXGA)   | 6         | 14.63%  |
| 1600x900 (HD+)     | 2         | 4.88%   |
| 1440x900 (WXGA+)   | 2         | 4.88%   |
| 3840x2160 (4K)     | 1         | 2.44%   |
| 3456x2160          | 1         | 2.44%   |
| 2560x1600          | 1         | 2.44%   |
| 2560x1440 (QHD)    | 1         | 2.44%   |
| 2560x1080          | 1         | 2.44%   |
| 1680x1050 (WSXGA+) | 1         | 2.44%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 12        | 28.57%  |
| 17      | 6         | 14.29%  |
| 24      | 5         | 11.9%   |
| 15      | 4         | 9.52%   |
| 11      | 3         | 7.14%   |
| 27      | 2         | 4.76%   |
| 23      | 2         | 4.76%   |
| 21      | 2         | 4.76%   |
| 12      | 2         | 4.76%   |
| 40      | 1         | 2.38%   |
| 34      | 1         | 2.38%   |
| 14      | 1         | 2.38%   |
| Unknown | 1         | 2.38%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 20        | 47.62%  |
| 501-600     | 9         | 21.43%  |
| 201-300     | 8         | 19.05%  |
| 401-500     | 2         | 4.76%   |
| 801-900     | 1         | 2.38%   |
| 701-800     | 1         | 2.38%   |
| Unknown     | 1         | 2.38%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 30        | 73.17%  |
| 5/4   | 6         | 14.63%  |
| 16/10 | 4         | 9.76%   |
| 21/9  | 1         | 2.44%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 13        | 30.95%  |
| 201-250        | 8         | 19.05%  |
| 141-150        | 6         | 14.29%  |
| 51-60          | 3         | 7.14%   |
| 61-70          | 2         | 4.76%   |
| 301-350        | 2         | 4.76%   |
| 101-110        | 2         | 4.76%   |
| 91-100         | 2         | 4.76%   |
| 351-500        | 1         | 2.38%   |
| 251-300        | 1         | 2.38%   |
| 501-1000       | 1         | 2.38%   |
| Unknown        | 1         | 2.38%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 17        | 40.48%  |
| 51-100        | 17        | 40.48%  |
| 101-120       | 4         | 9.52%   |
| 161-240       | 2         | 4.76%   |
| More than 240 | 1         | 2.38%   |
| Unknown       | 1         | 2.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 61        | 77.22%  |
| 0     | 16        | 20.25%  |
| 2     | 2         | 2.53%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 47        | 48.96%  |
| Realtek Semiconductor             | 22        | 22.92%  |
| Qualcomm Atheros                  | 7         | 7.29%   |
| Broadcom                          | 6         | 6.25%   |
| Marvell Technology Group          | 3         | 3.13%   |
| Ericsson Business Mobile Networks | 2         | 2.08%   |
| VIA Technologies                  | 1         | 1.04%   |
| TP-Link                           | 1         | 1.04%   |
| Sierra Wireless                   | 1         | 1.04%   |
| Ralink Technology                 | 1         | 1.04%   |
| Huawei Technologies               | 1         | 1.04%   |
| Edimax Technology                 | 1         | 1.04%   |
| D-Link System                     | 1         | 1.04%   |
| ASUSTek Computer                  | 1         | 1.04%   |
| Apple                             | 1         | 1.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 11        | 8.46%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 9         | 6.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 9         | 6.92%   |
| Intel Wireless 8260                                                     | 5         | 3.85%   |
| Intel Ethernet Connection I219-LM                                       | 5         | 3.85%   |
| Realtek RTL8125 2.5GbE Controller                                       | 4         | 3.08%   |
| Intel Wireless 7265                                                     | 4         | 3.08%   |
| Intel 82577LM Gigabit Network Connection                                | 4         | 3.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 2.31%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 2.31%   |
| Intel I210 Gigabit Network Connection                                   | 3         | 2.31%   |
| Intel Ethernet Connection (3) I218-LM                                   | 3         | 2.31%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 2         | 1.54%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 2         | 1.54%   |
| Intel Wireless 8265 / 8275                                              | 2         | 1.54%   |
| Intel Wireless 7260                                                     | 2         | 1.54%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 1.54%   |
| Intel Ethernet Connection (4) I219-LM                                   | 2         | 1.54%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 1.54%   |
| VIA VT6102/VT6103 [Rhine-II]                                            | 1         | 0.77%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 0.77%   |
| Sierra Wireless EM7455                                                  | 1         | 0.77%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 1         | 0.77%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.77%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 1         | 0.77%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.77%   |
| Ralink RT2501/RT2573 Wireless Adapter                                   | 1         | 0.77%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                              | 1         | 0.77%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.77%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 0.77%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                           | 1         | 0.77%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 1         | 0.77%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 1         | 0.77%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.77%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                 | 1         | 0.77%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 1         | 0.77%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                 | 1         | 0.77%   |
| Intel Wireless 3160                                                     | 1         | 0.77%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 0.77%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 38        | 70.37%  |
| Qualcomm Atheros      | 5         | 9.26%   |
| Realtek Semiconductor | 4         | 7.41%   |
| Broadcom              | 2         | 3.7%    |
| TP-Link               | 1         | 1.85%   |
| Sierra Wireless       | 1         | 1.85%   |
| Ralink Technology     | 1         | 1.85%   |
| Edimax Technology     | 1         | 1.85%   |
| ASUSTek Computer      | 1         | 1.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 9         | 16.36%  |
| Intel Wireless 8260                                                     | 5         | 9.09%   |
| Intel Wireless 7265                                                     | 4         | 7.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 5.45%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 5.45%   |
| Intel Wireless 8265 / 8275                                              | 2         | 3.64%   |
| Intel Wireless 7260                                                     | 2         | 3.64%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 3.64%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 3.64%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 1.82%   |
| Sierra Wireless EM7455                                                  | 1         | 1.82%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 1         | 1.82%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 1.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.82%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 1         | 1.82%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 1.82%   |
| Ralink RT2501/RT2573 Wireless Adapter                                   | 1         | 1.82%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 1.82%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.82%   |
| Intel Wireless 3160                                                     | 1         | 1.82%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 1.82%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 1.82%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 1.82%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection               | 1         | 1.82%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 1.82%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 1.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1         | 1.82%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 1         | 1.82%   |
| Edimax AC600 Wireless LAN USB Adapter                                   | 1         | 1.82%   |
| Broadcom BRCM4378 Wireless Network Adapter                              | 1         | 1.82%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 1         | 1.82%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                                     | 1         | 1.82%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 35        | 50.72%  |
| Realtek Semiconductor    | 19        | 27.54%  |
| Qualcomm Atheros         | 5         | 7.25%   |
| Broadcom                 | 4         | 5.8%    |
| Marvell Technology Group | 3         | 4.35%   |
| VIA Technologies         | 1         | 1.45%   |
| D-Link System            | 1         | 1.45%   |
| Apple                    | 1         | 1.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 15.71%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 12.86%  |
| Intel Ethernet Connection I219-LM                                 | 5         | 7.14%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 5.71%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 5.71%   |
| Intel I210 Gigabit Network Connection                             | 3         | 4.29%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 4.29%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 2.86%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 2.86%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.86%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 1.43%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 1.43%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.43%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 1.43%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.43%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 1.43%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 1.43%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 1.43%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 1.43%   |
| Intel I350 Gigabit Network Connection                             | 1         | 1.43%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.43%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.43%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.43%   |
| Intel 82576 Gigabit Network Connection                            | 1         | 1.43%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.43%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.43%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.43%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller     | 1         | 1.43%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 1         | 1.43%   |
| D-Link System DGE-560T PCI Express Gigabit Ethernet Adapter       | 1         | 1.43%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 1         | 1.43%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 1         | 1.43%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express           | 1         | 1.43%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 1         | 1.43%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                   | 1         | 1.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 69        | 55.65%  |
| WiFi     | 50        | 40.32%  |
| Unknown  | 3         | 2.42%   |
| Modem    | 2         | 1.61%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 39        | 55.71%  |
| Ethernet | 31        | 44.29%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 46        | 58.23%  |
| 1     | 25        | 31.65%  |
| 3     | 4         | 5.06%   |
| 4     | 2         | 2.53%   |
| 0     | 2         | 2.53%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 79        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 19        | 51.35%  |
| Broadcom                | 5         | 13.51%  |
| Alps Electric           | 3         | 8.11%   |
| Realtek Semiconductor   | 2         | 5.41%   |
| Foxconn / Hon Hai       | 2         | 5.41%   |
| Apple                   | 2         | 5.41%   |
| Taiyo Yuden             | 1         | 2.7%    |
| IMC Networks            | 1         | 2.7%    |
| Cambridge Silicon Radio | 1         | 2.7%    |
| ASUSTek Computer        | 1         | 2.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                       | 13        | 35.14%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 3         | 8.11%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]               | 3         | 8.11%   |
| Realtek Bluetooth Adapter                                | 2         | 5.41%   |
| Intel AX200 Bluetooth                                    | 2         | 5.41%   |
| Broadcom BCM2045B (BDC-2.1)                              | 2         | 5.41%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                     | 2         | 5.41%   |
| Alps Electric UGTZ4 Bluetooth                            | 2         | 5.41%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)                  | 1         | 2.7%    |
| Intel AX210 Bluetooth                                    | 1         | 2.7%    |
| IMC Networks Realtek Bluetooth Adapter                   | 1         | 2.7%    |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device          | 1         | 2.7%    |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device | 1         | 2.7%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 1         | 2.7%    |
| ASUS Broadcom Bluetooth 2.1                              | 1         | 2.7%    |
| Alps Electric BCM2046 Bluetooth Device                   | 1         | 2.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Intel            | 51        | 67.11%  |
| AMD              | 15        | 19.74%  |
| Nvidia           | 7         | 9.21%   |
| VIA Technologies | 1         | 1.32%   |
| Logitech         | 1         | 1.32%   |
| JMTek            | 1         | 1.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 8         | 8.89%   |
| AMD Family 17h/19h HD Audio Controller                                     | 7         | 7.78%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6         | 6.67%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6         | 6.67%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 5.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 4.44%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4         | 4.44%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3         | 3.33%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 3.33%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 3.33%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 3         | 3.33%   |
| Nvidia GA104 High Definition Audio Controller                              | 2         | 2.22%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 2.22%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 2.22%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller | 2         | 2.22%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2         | 2.22%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 2.22%   |
| AMD FCH Azalia Controller                                                  | 2         | 2.22%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 1         | 1.11%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 1.11%   |
| Nvidia CK804 AC'97 Audio Controller                                        | 1         | 1.11%   |
| Logitech [G533 Wireless Headset Dongle]                                    | 1         | 1.11%   |
| JMTek USB PnP Audio Device                                                 | 1         | 1.11%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 1         | 1.11%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 1.11%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 1.11%   |
| Intel Comet Lake PCH-V cAVS                                                | 1         | 1.11%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.11%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.11%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1         | 1.11%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1         | 1.11%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.11%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1         | 1.11%   |
| Intel 82801CA/CAM AC'97 Audio Controller                                   | 1         | 1.11%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 1.11%   |
| Intel 631xESB/632xESB High Definition Audio Controller                     | 1         | 1.11%   |
| Intel 200 Series PCH HD Audio                                              | 1         | 1.11%   |
| AMD RV770 HDMI Audio [Radeon HD 4850/4870]                                 | 1         | 1.11%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 1         | 1.11%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.11%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 11        | 29.73%  |
| Unknown             | 7         | 18.92%  |
| Unknown             | 6         | 16.22%  |
| SK hynix            | 5         | 13.51%  |
| Kingston            | 3         | 8.11%   |
| Crucial             | 2         | 5.41%   |
| Micron Technology   | 1         | 2.7%    |
| Hewlett-Packard     | 1         | 2.7%    |
| A-DATA Technology   | 1         | 2.7%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Unknown                                                 | 6         | 14.63%  |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s   | 3         | 7.32%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM 1067MT/s        | 2         | 4.88%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s   | 2         | 4.88%   |
| Crucial RAM CT8G3S1339M 8GB SODIMM DDR3 1333MT/s        | 2         | 4.88%   |
| Unknown RAM Module 512MB SODIMM SDRAM                   | 1         | 2.44%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s             | 1         | 2.44%   |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s             | 1         | 2.44%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s              | 1         | 2.44%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                | 1         | 2.44%   |
| Unknown RAM Module 1GB SODIMM DDR2                      | 1         | 2.44%   |
| Unknown RAM Module 1GB SODIMM DDR                       | 1         | 2.44%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 1         | 2.44%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 1         | 2.44%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s  | 1         | 2.44%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s | 1         | 2.44%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB SODIMM LPDDR3 1867MT/s  | 1         | 2.44%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB Chip LPDDR3 1867MT/s    | 1         | 2.44%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s   | 1         | 2.44%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM 1067MT/s        | 1         | 2.44%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s   | 1         | 2.44%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s   | 1         | 2.44%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s   | 1         | 2.44%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s   | 1         | 2.44%   |
| Samsung RAM M393A4K40CB1-CRC 32GB DIMM DDR4 2400MT/s    | 1         | 2.44%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s   | 1         | 2.44%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s       | 1         | 2.44%   |
| Kingston RAM KF3600C18D4/32GX 32GB DIMM DDR4 2400MT/s   | 1         | 2.44%   |
| Kingston RAM 9905316-005.A04LF 1GB DIMM DDR2 667MT/s    | 1         | 2.44%   |
| HP RAM 809083-091 32GB DIMM DDR4 2400MT/s               | 1         | 2.44%   |
| A-DATA RAM AM1L16BC4R1-B1PS 4GB SODIMM DDR3 1600MT/s    | 1         | 2.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 14        | 41.18%  |
| DDR4    | 7         | 20.59%  |
| DDR2    | 6         | 17.65%  |
| SDRAM   | 3         | 8.82%   |
| Unknown | 2         | 5.88%   |
| LPDDR3  | 1         | 2.94%   |
| DDR     | 1         | 2.94%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 25        | 71.43%  |
| DIMM   | 9         | 25.71%  |
| Chip   | 1         | 2.86%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 10        | 26.32%  |
| 4096  | 9         | 23.68%  |
| 8192  | 8         | 21.05%  |
| 1024  | 5         | 13.16%  |
| 32768 | 3         | 7.89%   |
| 512   | 2         | 5.26%   |
| 16384 | 1         | 2.63%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 6         | 16.22%  |
| Unknown | 6         | 16.22%  |
| 2400    | 4         | 10.81%  |
| 1334    | 4         | 10.81%  |
| 1333    | 4         | 10.81%  |
| 1067    | 3         | 8.11%   |
| 667     | 3         | 8.11%   |
| 3200    | 1         | 2.7%    |
| 2667    | 1         | 2.7%    |
| 2133    | 1         | 2.7%    |
| 1867    | 1         | 2.7%    |
| 800     | 1         | 2.7%    |
| 400     | 1         | 2.7%    |
| 266     | 1         | 2.7%    |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 13        | 35.14%  |
| Lite-On Technology                     | 5         | 13.51%  |
| Bison Electronics                      | 5         | 13.51%  |
| Tripath Technology                     | 2         | 5.41%   |
| Lenovo                                 | 2         | 5.41%   |
| IMC Networks                           | 2         | 5.41%   |
| SunplusIT                              | 1         | 2.7%    |
| Ricoh                                  | 1         | 2.7%    |
| Realtek Semiconductor                  | 1         | 2.7%    |
| Jiangxi Shinetech Optical              | 1         | 2.7%    |
| Genesys Logic                          | 1         | 2.7%    |
| Generalplus Technology                 | 1         | 2.7%    |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.7%    |
| Apple                                  | 1         | 2.7%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Lite-On Integrated Camera                                | 4         | 10.81%  |
| Chicony Integrated Camera                                | 3         | 8.11%   |
| Bison Integrated Camera                                  | 3         | 8.11%   |
| Tripath USB Camera                                       | 2         | 5.41%   |
| IMC Networks Integrated Camera                           | 2         | 5.41%   |
| Chicony Integrated Camera [ThinkPad]                     | 2         | 5.41%   |
| SunplusIT USB camera                                     | 1         | 2.7%    |
| Ricoh Laptop_Integrated_Webcam_FHD                       | 1         | 2.7%    |
| Realtek Integrated Webcam HD                             | 1         | 2.7%    |
| Lite-On Realtek DMFT RGB                                 | 1         | 2.7%    |
| Lenovo Integrated Webcam [R5U877]                        | 1         | 2.7%    |
| Lenovo Integrated Webcam                                 | 1         | 2.7%    |
| Jiangxi Shinetech Optical Realtek PC Camera              | 1         | 2.7%    |
| Genesys Logic ASUS USB 2.0 UVC 1.3M WebCam               | 1         | 2.7%    |
| Generalplus HD Webcam                                    | 1         | 2.7%    |
| Chicony thinkpad t430s camera                            | 1         | 2.7%    |
| Chicony Sonix ST50220 USB Video Camera                   | 1         | 2.7%    |
| Chicony Ltd., USB 2.0 Camera                             | 1         | 2.7%    |
| Chicony Lenovo Integrated Camera (0.3MP)                 | 1         | 2.7%    |
| Chicony Lenovo EasyCamera                                | 1         | 2.7%    |
| Chicony Integrated Camera (1280x720@30)                  | 1         | 2.7%    |
| Chicony FJ Camera                                        | 1         | 2.7%    |
| Chicony 2.0M UVC Webcam / CNF7129                        | 1         | 2.7%    |
| Cheng Uei Precision Industry (Foxlink) Realtek PC Camera | 1         | 2.7%    |
| Bison USB HD Webcam                                      | 1         | 2.7%    |
| Bison Lenovo Integrated Webcam                           | 1         | 2.7%    |
| Apple FaceTime Camera                                    | 1         | 2.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 4         | 28.57%  |
| Synaptics             | 3         | 21.43%  |
| AuthenTec             | 3         | 21.43%  |
| Upek                  | 2         | 14.29%  |
| STMicroelectronics    | 1         | 7.14%   |
| LighTuning Technology | 1         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 3         | 21.43%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 14.29%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 14.29%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 7.14%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 7.14%   |
| STMicroelectronics Fingerprint Reader                  | 1         | 7.14%   |
| LighTuning ES603 Swipe Fingerprint Sensor              | 1         | 7.14%   |
| AuthenTec AES2810                                      | 1         | 7.14%   |
| AuthenTec AES2660                                      | 1         | 7.14%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 7.14%   |

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
| 1     | 39        | 49.37%  |
| 0     | 22        | 27.85%  |
| 2     | 10        | 12.66%  |
| 3     | 4         | 5.06%   |
| 5     | 3         | 3.8%    |
| 4     | 1         | 1.27%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 39        | 45.35%  |
| Graphics card            | 16        | 18.6%   |
| Firewire controller      | 10        | 11.63%  |
| Net/wireless             | 5         | 5.81%   |
| Storage/ata              | 4         | 4.65%   |
| Sound                    | 4         | 4.65%   |
| Network                  | 4         | 4.65%   |
| Storage                  | 1         | 1.16%   |
| Net/ethernet             | 1         | 1.16%   |
| Modem                    | 1         | 1.16%   |
| Card reader              | 1         | 1.16%   |

