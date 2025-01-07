OpenBSD 7.5 - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for OpenBSD 7.5.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/OpenBSD_7.5/Desktop/README.md) and [notebooks](/Dist/OpenBSD_7.5/Notebook/README.md).

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

Total: 101

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| IGEL Techn... | IGEL-D220                   | Desktop     | [9d3ca29f8a](https://bsd-hardware.info/?probe=9d3ca29f8a) | Dec 30, 2024 |
| BOSGAME       | Ecolite Series              | Desktop     | [c1083a8777](https://bsd-hardware.info/?probe=c1083a8777) | Dec 28, 2024 |
| Unknown       | Cubietech Cubietruck        | Desktop     | [4b4a38865a](https://bsd-hardware.info/?probe=4b4a38865a) | Oct 21, 2024 |
| HP            | 240 G3                      | Desktop     | [7e732aa2d4](https://bsd-hardware.info/?probe=7e732aa2d4) | Oct 13, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [7fef5366cf](https://bsd-hardware.info/?probe=7fef5366cf) | Oct 10, 2024 |
| Panasonic     | CFSZ6-2                     | Notebook    | [52aa021161](https://bsd-hardware.info/?probe=52aa021161) | Oct 03, 2024 |
| Panasonic     | CFSZ6-2                     | Notebook    | [3c534a62ac](https://bsd-hardware.info/?probe=3c534a62ac) | Oct 03, 2024 |
| MSI           | MS-7D16                     | Desktop     | [e9bddb011d](https://bsd-hardware.info/?probe=e9bddb011d) | Oct 01, 2024 |
| Dell          | Latitude E7250              | Notebook    | [025ea9ef12](https://bsd-hardware.info/?probe=025ea9ef12) | Sep 30, 2024 |
| Dell          | Latitude E7250              | Notebook    | [2dfb20ed35](https://bsd-hardware.info/?probe=2dfb20ed35) | Sep 27, 2024 |
| Lenovo        | ThinkPad X230 2325WMM       | Notebook    | [06cb50192c](https://bsd-hardware.info/?probe=06cb50192c) | Sep 27, 2024 |
| Framework     | Laptop                      | Notebook    | [db5ecf38bc](https://bsd-hardware.info/?probe=db5ecf38bc) | Sep 25, 2024 |
| SJRC          | ADLN-6L                     | Desktop     | [6b77a00921](https://bsd-hardware.info/?probe=6b77a00921) | Sep 25, 2024 |
| Lenovo        | ThinkPad T420 41786UU       | Notebook    | [81062d2bf1](https://bsd-hardware.info/?probe=81062d2bf1) | Sep 17, 2024 |
| ASRock        | B360M Pro4                  | Desktop     | [64d222278e](https://bsd-hardware.info/?probe=64d222278e) | Sep 06, 2024 |
| Panasonic     | CF-C1BT02EGE                | Notebook    | [e2dcfb8821](https://bsd-hardware.info/?probe=e2dcfb8821) | Sep 06, 2024 |
| ASUSTek       | PRIME B650M-A WIFI II       | Desktop     | [9b18fc2e82](https://bsd-hardware.info/?probe=9b18fc2e82) | Sep 01, 2024 |
| ASRock        | Z87M Pro4                   | Desktop     | [dbbdcc1fe6](https://bsd-hardware.info/?probe=dbbdcc1fe6) | Aug 31, 2024 |
| Intel         | Q3XXG4-P                    | Desktop     | [072a3b6857](https://bsd-hardware.info/?probe=072a3b6857) | Aug 29, 2024 |
| ASUSTek       | UX305FA                     | Notebook    | [8f27558fdf](https://bsd-hardware.info/?probe=8f27558fdf) | Aug 29, 2024 |
| Acer          | Aspire 5551                 | Notebook    | [861d3a83cc](https://bsd-hardware.info/?probe=861d3a83cc) | Aug 27, 2024 |
| ASRock        | Z87M Pro4                   | Desktop     | [2ddfd242d0](https://bsd-hardware.info/?probe=2ddfd242d0) | Aug 27, 2024 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [1be0ff70bb](https://bsd-hardware.info/?probe=1be0ff70bb) | Aug 21, 2024 |
| ' '           | Unknown                     | Notebook    | [ad1210fffc](https://bsd-hardware.info/?probe=ad1210fffc) | Aug 21, 2024 |
| Lenovo        | ThinkPad T480s 20L8S6JH0... | Notebook    | [5f5e0baa4e](https://bsd-hardware.info/?probe=5f5e0baa4e) | Aug 05, 2024 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | Notebook    | [ed6539c0d5](https://bsd-hardware.info/?probe=ed6539c0d5) | Aug 03, 2024 |
| Panasonic     | CFSX4-1                     | Notebook    | [78d6d40878](https://bsd-hardware.info/?probe=78d6d40878) | Aug 02, 2024 |
| Supermicro    | X11SDV-4C-TLN2F             | Desktop     | [b2bd066528](https://bsd-hardware.info/?probe=b2bd066528) | Aug 02, 2024 |
| Supermicro    | X11SDV-4C-TLN2F             | Desktop     | [be116a0073](https://bsd-hardware.info/?probe=be116a0073) | Aug 02, 2024 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [240e3487f6](https://bsd-hardware.info/?probe=240e3487f6) | Jul 28, 2024 |
| Lenovo        | ThinkPad X260 20F6005LUS    | Notebook    | [e23e2f1aaa](https://bsd-hardware.info/?probe=e23e2f1aaa) | Jul 26, 2024 |
| HP            | ProBook 6470b               | Notebook    | [80be308f90](https://bsd-hardware.info/?probe=80be308f90) | Jul 24, 2024 |
| Dell          | OptiPlex 3050               | Desktop     | [0cffdab939](https://bsd-hardware.info/?probe=0cffdab939) | Jul 19, 2024 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [42ada28689](https://bsd-hardware.info/?probe=42ada28689) | Jul 19, 2024 |
| Lenovo        | ThinkPad T400 6475FA4       | Notebook    | [ebe23829a9](https://bsd-hardware.info/?probe=ebe23829a9) | Jul 18, 2024 |
| Lenovo        | Yoga Slim 7 14Q8X9 83ED     | Desktop     | [3a770b9efd](https://bsd-hardware.info/?probe=3a770b9efd) | Jul 15, 2024 |
| Lenovo        | Yoga Slim 7 14Q8X9 83ED     | Desktop     | [cb9978d493](https://bsd-hardware.info/?probe=cb9978d493) | Jul 15, 2024 |
| Lenovo        | ThinkPad X220 429137G       | Notebook    | [f6d3e4a448](https://bsd-hardware.info/?probe=f6d3e4a448) | Jul 13, 2024 |
| Gigabyte      | H170M-D3H                   | Desktop     | [7fc1b74405](https://bsd-hardware.info/?probe=7fc1b74405) | Jul 11, 2024 |
| Lenovo        | ThinkPad X220 429137G       | Notebook    | [1e0500cb46](https://bsd-hardware.info/?probe=1e0500cb46) | Jul 09, 2024 |
| Apple         | PowerBook6,8                | Notebook    | [91910550d4](https://bsd-hardware.info/?probe=91910550d4) | Jul 09, 2024 |
| Panasonic     | CFSX4-1                     | Notebook    | [2bba859d5a](https://bsd-hardware.info/?probe=2bba859d5a) | Jul 06, 2024 |
| Lenovo        | ThinkPad X220 429137G       | Notebook    | [2d398edd49](https://bsd-hardware.info/?probe=2d398edd49) | Jul 02, 2024 |
| Lenovo        | ThinkPad X220 429137G       | Notebook    | [c78a57178a](https://bsd-hardware.info/?probe=c78a57178a) | Jul 02, 2024 |
| AZW           | SER                         | Desktop     | [e226d0b9f4](https://bsd-hardware.info/?probe=e226d0b9f4) | Jul 01, 2024 |
| AZW           | SER                         | Desktop     | [f7be2f6fd7](https://bsd-hardware.info/?probe=f7be2f6fd7) | Jul 01, 2024 |
| Intel(R) C... | NUC13ANKi5                  | Mini pc     | [17f7122809](https://bsd-hardware.info/?probe=17f7122809) | Jul 01, 2024 |
| Gigabyte      | X670 GAMING X AX V2         | Desktop     | [4ba8f14215](https://bsd-hardware.info/?probe=4ba8f14215) | Jun 23, 2024 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [a74ac046b0](https://bsd-hardware.info/?probe=a74ac046b0) | Jun 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [0d82249e6b](https://bsd-hardware.info/?probe=0d82249e6b) | Jun 18, 2024 |
| Maibenben     | MaiBook M                   | Notebook    | [e6ab2b3bf7](https://bsd-hardware.info/?probe=e6ab2b3bf7) | Jun 18, 2024 |
| Intel(R) C... | NUC6CAYH                    | Mini pc     | [dbe33d4967](https://bsd-hardware.info/?probe=dbe33d4967) | Jun 18, 2024 |
| Acer          | TravelMate P214-52          | Notebook    | [6ff322bb68](https://bsd-hardware.info/?probe=6ff322bb68) | Jun 15, 2024 |
| Acer          | TravelMate P214-52          | Notebook    | [2ecfeb9814](https://bsd-hardware.info/?probe=2ecfeb9814) | Jun 15, 2024 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [863d61d71e](https://bsd-hardware.info/?probe=863d61d71e) | Jun 12, 2024 |
| Intel         | S2600WT2R                   | Desktop     | [406818a434](https://bsd-hardware.info/?probe=406818a434) | Jun 03, 2024 |
| Lenovo        | ThinkPad T460 20FMA09CGE    | Notebook    | [f65532b888](https://bsd-hardware.info/?probe=f65532b888) | Jun 01, 2024 |
| Acer          | Aspire X3-780               | Desktop     | [65c4e9c26d](https://bsd-hardware.info/?probe=65c4e9c26d) | May 27, 2024 |
| Lenovo        | G560 0679                   | Notebook    | [50faff095e](https://bsd-hardware.info/?probe=50faff095e) | May 27, 2024 |
| Lenovo        | ThinkPad YOGA260 20FES2X... | Notebook    | [e49d3164c9](https://bsd-hardware.info/?probe=e49d3164c9) | May 26, 2024 |
| Matsushita... | CF-48V4KNDQM                | Notebook    | [9297aa94a7](https://bsd-hardware.info/?probe=9297aa94a7) | May 24, 2024 |
| Dell          | Inspiron 1545               | Notebook    | [84bb977e77](https://bsd-hardware.info/?probe=84bb977e77) | May 22, 2024 |
| Dell          | Inspiron 1545               | Notebook    | [6fa29eb23c](https://bsd-hardware.info/?probe=6fa29eb23c) | May 22, 2024 |
| Matsushita... | CF-51RCVDNLM                | Notebook    | [c20eb22761](https://bsd-hardware.info/?probe=c20eb22761) | May 21, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [9d43b94e3a](https://bsd-hardware.info/?probe=9d43b94e3a) | May 19, 2024 |
| Panasonic     | CFSX4-1                     | Notebook    | [0032ef2a58](https://bsd-hardware.info/?probe=0032ef2a58) | May 18, 2024 |
| Gigabyte      | Z790 EAGLE AX               | Desktop     | [011ed158e0](https://bsd-hardware.info/?probe=011ed158e0) | May 18, 2024 |
| Gigabyte      | Z790 EAGLE AX               | Desktop     | [d96abdd063](https://bsd-hardware.info/?probe=d96abdd063) | May 17, 2024 |
| Apple         | PowerBook6,8                | Notebook    | [d0f3a361a3](https://bsd-hardware.info/?probe=d0f3a361a3) | May 13, 2024 |
| Apple         | PowerBook6,8                | Notebook    | [272fd15611](https://bsd-hardware.info/?probe=272fd15611) | May 12, 2024 |
| Supermicro    | Super Server                | Server      | [700eedf3f6](https://bsd-hardware.info/?probe=700eedf3f6) | May 11, 2024 |
| ASUSTek       | 1000HE                      | Notebook    | [65db5ea354](https://bsd-hardware.info/?probe=65db5ea354) | May 11, 2024 |
| Panasonic     | CF-54-1                     | Notebook    | [00de332c2c](https://bsd-hardware.info/?probe=00de332c2c) | May 04, 2024 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [3e01e5ffbf](https://bsd-hardware.info/?probe=3e01e5ffbf) | May 03, 2024 |
| Panasonic     | CF-52PFPBSFQ                | Notebook    | [48423bbece](https://bsd-hardware.info/?probe=48423bbece) | May 03, 2024 |
| Apple         | PowerBook6,8                | Notebook    | [fa66040f75](https://bsd-hardware.info/?probe=fa66040f75) | May 02, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [49d6f53542](https://bsd-hardware.info/?probe=49d6f53542) | Apr 30, 2024 |
| Lenovo        | ThinkPad T470 20HES18R05    | Notebook    | [9b76000646](https://bsd-hardware.info/?probe=9b76000646) | Apr 30, 2024 |
| ASRock        | Z87M Pro4                   | Desktop     | [91a487bad5](https://bsd-hardware.info/?probe=91a487bad5) | Apr 29, 2024 |
| Lenovo        | ThinkPad T410 2537N24       | Notebook    | [04370189ed](https://bsd-hardware.info/?probe=04370189ed) | Apr 29, 2024 |
| Lenovo        | ThinkPad T430 2347GZU       | Notebook    | [f49f1b3ac2](https://bsd-hardware.info/?probe=f49f1b3ac2) | Apr 28, 2024 |
| Panasonic     | CFSX4-1                     | Notebook    | [58c0214ae8](https://bsd-hardware.info/?probe=58c0214ae8) | Apr 25, 2024 |
| Dell          | Latitude 7490               | Notebook    | [510590d1c7](https://bsd-hardware.info/?probe=510590d1c7) | Apr 24, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [bf89bc5c69](https://bsd-hardware.info/?probe=bf89bc5c69) | Apr 24, 2024 |
| ASRock        | A320M Pro4-F                | Desktop     | [b02849b872](https://bsd-hardware.info/?probe=b02849b872) | Apr 23, 2024 |
| Lenovo        | ThinkPad X260 20F5S2GM00    | Notebook    | [8a37e6930f](https://bsd-hardware.info/?probe=8a37e6930f) | Apr 23, 2024 |
| Panasonic     | CF-53AAGHYDM                | Notebook    | [3eac3d5a68](https://bsd-hardware.info/?probe=3eac3d5a68) | Apr 23, 2024 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [bf1d7a54d1](https://bsd-hardware.info/?probe=bf1d7a54d1) | Apr 22, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [44758d3d74](https://bsd-hardware.info/?probe=44758d3d74) | Apr 16, 2024 |
| Unknown       | QDNV01                      | Desktop     | [0cb0009f73](https://bsd-hardware.info/?probe=0cb0009f73) | Apr 15, 2024 |
| Dell          | Latitude 7490               | Notebook    | [e2af0367f5](https://bsd-hardware.info/?probe=e2af0367f5) | Apr 11, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS (W... | Desktop     | [1257111a5f](https://bsd-hardware.info/?probe=1257111a5f) | Apr 10, 2024 |
| Lenovo        | ThinkPad T470 20HES18R05    | Notebook    | [e081ad3727](https://bsd-hardware.info/?probe=e081ad3727) | Apr 08, 2024 |
| Intel         | NUC7i3BNHX                  | Mini pc     | [be1566e796](https://bsd-hardware.info/?probe=be1566e796) | Apr 07, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [435faeda9e](https://bsd-hardware.info/?probe=435faeda9e) | Apr 07, 2024 |
| Gigabyte      | G431-MM0-OT                 | Desktop     | [16c58f7ccb](https://bsd-hardware.info/?probe=16c58f7ccb) | Apr 07, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [d0ce6ee00b](https://bsd-hardware.info/?probe=d0ce6ee00b) | Apr 05, 2024 |
| Lenovo        | ThinkPad T420 4236JY2       | Notebook    | [0111e4442e](https://bsd-hardware.info/?probe=0111e4442e) | Mar 11, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [637e2678c5](https://bsd-hardware.info/?probe=637e2678c5) | Mar 09, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [f6e67c7e6e](https://bsd-hardware.info/?probe=f6e67c7e6e) | Mar 09, 2024 |
| Panasonic     | CFSX4-1                     | Notebook    | [5821783809](https://bsd-hardware.info/?probe=5821783809) | Mar 01, 2024 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| amd64  | 69        | 92%     |
| i386   | 3         | 4%      |
| macppc | 1         | 1.33%   |
| armv7  | 1         | 1.33%   |
| arm64  | 1         | 1.33%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 63        | 84%     |
| XFCE         | 8         | 10.67%  |
| StumpWM      | 1         | 1.33%   |
| LXQt         | 1         | 1.33%   |
| KDE5         | 1         | 1.33%   |
| GNOME        | 1         | 1.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 60        | 80%     |
| Console | 15        | 20%     |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 75        | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 66        | 88%     |
| en_US   | 6         | 8%      |
| pt_PT   | 1         | 1.33%   |
| pl_PL   | 1         | 1.33%   |
| de.DE   | 1         | 1.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 55        | 73.33%  |
| BIOS | 20        | 26.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ffs  | 75        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 52        | 69.33%  |
| MBR  | 23        | 30.67%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 21        | 28%     |
| ASUSTek Computer               | 8         | 10.67%  |
| Panasonic                      | 5         | 6.67%   |
| Gigabyte Technology            | 4         | 5.33%   |
| Dell                           | 4         | 5.33%   |
| Intel                          | 3         | 4%      |
| ASRock                         | 3         | 4%      |
| Apple                          | 3         | 4%      |
| Acer                           | 3         | 4%      |
| Supermicro                     | 2         | 2.67%   |
| Matsushita Electric Industrial | 2         | 2.67%   |
| Intel(R) Client Systems        | 2         | 2.67%   |
| Hewlett-Packard                | 2         | 2.67%   |
| Unknown                        | 2         | 2.67%   |
| TUXEDO                         | 1         | 1.33%   |
| SJRC                           | 1         | 1.33%   |
| Notebook                       | 1         | 1.33%   |
| MSI                            | 1         | 1.33%   |
| Maibenben                      | 1         | 1.33%   |
| IGEL Technology                | 1         | 1.33%   |
| Fujitsu                        | 1         | 1.33%   |
| Framework                      | 1         | 1.33%   |
| BOSGAME                        | 1         | 1.33%   |
| AZW                            | 1         | 1.33%   |
| ' '                            | 1         | 1.33%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 3         | 4%      |
| TUXEDO Pulse 15 Gen1                        | 1         | 1.33%   |
| Supermicro SYS-E300-9D                      | 1         | 1.33%   |
| Supermicro Super Server                     | 1         | 1.33%   |
| SJRC ADLN-6L                                | 1         | 1.33%   |
| Panasonic CFSX4-1                           | 1         | 1.33%   |
| Panasonic CF-C1BT02EGE                      | 1         | 1.33%   |
| Panasonic CF-54-1                           | 1         | 1.33%   |
| Panasonic CF-53AAGHYDM                      | 1         | 1.33%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 1.33%   |
| Notebook NV4XMB,ME,MZ                       | 1         | 1.33%   |
| MSI MS-7D16                                 | 1         | 1.33%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 1.33%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 1.33%   |
| Maibenben MaiBook M                         | 1         | 1.33%   |
| Lenovo Yoga Slim 7 14Q8X9 83ED              | 1         | 1.33%   |
| Lenovo ThinkPad YOGA260 20FES2XD00          | 1         | 1.33%   |
| Lenovo ThinkPad X270 W10DG 20K5S0TT1N       | 1         | 1.33%   |
| Lenovo ThinkPad X260 20F6005LUS             | 1         | 1.33%   |
| Lenovo ThinkPad X260 20F5S2GM00             | 1         | 1.33%   |
| Lenovo ThinkPad X260 20F5S10W0H             | 1         | 1.33%   |
| Lenovo ThinkPad X230 2325WMM                | 1         | 1.33%   |
| Lenovo ThinkPad X220 429137G                | 1         | 1.33%   |
| Lenovo ThinkPad X1 Extreme 2nd 20QVCTO1WW   | 1         | 1.33%   |
| Lenovo ThinkPad X1 Carbon Gen 11 21HM002FUS | 1         | 1.33%   |
| Lenovo ThinkPad X1 Carbon 6th 20KH0035UK    | 1         | 1.33%   |
| Lenovo ThinkPad T480s 20L8S6JH00            | 1         | 1.33%   |
| Lenovo ThinkPad T470 W10DG 20JNS0L300       | 1         | 1.33%   |
| Lenovo ThinkPad T470 20HES18R05             | 1         | 1.33%   |
| Lenovo ThinkPad T460 20FMA09CGE             | 1         | 1.33%   |
| Lenovo ThinkPad T430 2347GZU                | 1         | 1.33%   |
| Lenovo ThinkPad T420 4236JY2                | 1         | 1.33%   |
| Lenovo ThinkPad T420 41786UU                | 1         | 1.33%   |
| Lenovo ThinkPad T410 2537N24                | 1         | 1.33%   |
| Lenovo ThinkPad T400 6475FA4                | 1         | 1.33%   |
| Lenovo G560 0679                            | 1         | 1.33%   |
| Intel(R) Client Systems NUC6CAYH            | 1         | 1.33%   |
| Intel(R) Client Systems NUC13ANKi5          | 1         | 1.33%   |
| Intel S2600WT2R                             | 1         | 1.33%   |
| Intel Q3XXG4-P                              | 1         | 1.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad                             | 19        | 25.33%  |
| Unknown                                     | 3         | 4%      |
| Dell Latitude                               | 2         | 2.67%   |
| ASUS TUF                                    | 2         | 2.67%   |
| ASUS PRIME                                  | 2         | 2.67%   |
| Acer Aspire                                 | 2         | 2.67%   |
| TUXEDO Pulse                                | 1         | 1.33%   |
| Supermicro SYS-E300-9D                      | 1         | 1.33%   |
| Supermicro Super                            | 1         | 1.33%   |
| SJRC ADLN-6L                                | 1         | 1.33%   |
| Panasonic CFSX4-1                           | 1         | 1.33%   |
| Panasonic CF-C1BT02EGE                      | 1         | 1.33%   |
| Panasonic CF-54-1                           | 1         | 1.33%   |
| Panasonic CF-53AAGHYDM                      | 1         | 1.33%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 1.33%   |
| Notebook NV4XMB                             | 1         | 1.33%   |
| MSI MS-7D16                                 | 1         | 1.33%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 1.33%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 1.33%   |
| Maibenben MaiBook                           | 1         | 1.33%   |
| Lenovo Yoga                                 | 1         | 1.33%   |
| Lenovo G560                                 | 1         | 1.33%   |
| Intel(R) Client Systems NUC6CAYH            | 1         | 1.33%   |
| Intel(R) Client Systems NUC13ANKi5          | 1         | 1.33%   |
| Intel S2600WT2R                             | 1         | 1.33%   |
| Intel Q3XXG4-P                              | 1         | 1.33%   |
| Intel NUC7i3BNHX                            | 1         | 1.33%   |
| IGEL IGEL-D220                              | 1         | 1.33%   |
| HP ProBook                                  | 1         | 1.33%   |
| HP 240                                      | 1         | 1.33%   |
| Gigabyte Z790                               | 1         | 1.33%   |
| Gigabyte X670                               | 1         | 1.33%   |
| Gigabyte H170M-D3H                          | 1         | 1.33%   |
| Gigabyte G431-MM0-OT                        | 1         | 1.33%   |
| Fujitsu LIFEBOOK                            | 1         | 1.33%   |
| Framework Laptop                            | 1         | 1.33%   |
| Dell OptiPlex                               | 1         | 1.33%   |
| Dell Inspiron                               | 1         | 1.33%   |
| BOSGAME Ecolite                             | 1         | 1.33%   |
| AZW SER                                     | 1         | 1.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2023    | 8         | 10.67%  |
| 2011    | 8         | 10.67%  |
| 2024    | 7         | 9.33%   |
| 2018    | 7         | 9.33%   |
| 2016    | 6         | 8%      |
| 2022    | 5         | 6.67%   |
| 2021    | 5         | 6.67%   |
| 2019    | 5         | 6.67%   |
| 2020    | 4         | 5.33%   |
| 2017    | 3         | 4%      |
| 2015    | 3         | 4%      |
| 2009    | 3         | 4%      |
| 2014    | 2         | 2.67%   |
| 2012    | 2         | 2.67%   |
| 2010    | 2         | 2.67%   |
| Unknown | 2         | 2.67%   |
| 2013    | 1         | 1.33%   |
| 2006    | 1         | 1.33%   |
| 2002    | 1         | 1.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 45        | 60%     |
| Desktop  | 26        | 34.67%  |
| Mini pc  | 3         | 4%      |
| Server   | 1         | 1.33%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 75        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 27        | 35.53%  |
| 16.01-24.0  | 15        | 19.74%  |
| 32.01-64.0  | 12        | 15.79%  |
| 4.01-8.0    | 6         | 7.89%   |
| 3.01-4.0    | 5         | 6.58%   |
| 64.01-256.0 | 3         | 3.95%   |
| 24.01-32.0  | 2         | 2.63%   |
| 2.01-3.0    | 2         | 2.63%   |
| 1.01-2.0    | 2         | 2.63%   |
| 0.51-1.0    | 2         | 2.63%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 53        | 70.67%  |
| 0.51-1.0 | 14        | 18.67%  |
| 0        | 4         | 5.33%   |
| 4.01-8.0 | 2         | 2.67%   |
| 2.01-3.0 | 1         | 1.33%   |
| 1.01-2.0 | 1         | 1.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 37        | 48.68%  |
| 2      | 26        | 34.21%  |
| 3      | 7         | 9.21%   |
| 4      | 3         | 3.95%   |
| 8      | 1         | 1.32%   |
| 5      | 1         | 1.32%   |
| 0      | 1         | 1.32%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 73        | 97.33%  |
| Yes       | 2         | 2.67%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 68        | 90.67%  |
| No        | 7         | 9.33%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 58        | 77.33%  |
| No        | 17        | 22.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 41        | 54.67%  |
| No        | 34        | 45.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 17        | 22.67%  |
| Canada      | 15        | 20%     |
| UK          | 6         | 8%      |
| Germany     | 6         | 8%      |
| Italy       | 5         | 6.67%   |
| Poland      | 4         | 5.33%   |
| France      | 3         | 4%      |
| Switzerland | 2         | 2.67%   |
| Russia      | 2         | 2.67%   |
| Brazil      | 2         | 2.67%   |
| Sweden      | 1         | 1.33%   |
| Spain       | 1         | 1.33%   |
| Netherlands | 1         | 1.33%   |
| Malaysia    | 1         | 1.33%   |
| Lithuania   | 1         | 1.33%   |
| Japan       | 1         | 1.33%   |
| India       | 1         | 1.33%   |
| Finland     | 1         | 1.33%   |
| Denmark     | 1         | 1.33%   |
| Czechia     | 1         | 1.33%   |
| Croatia     | 1         | 1.33%   |
| Australia   | 1         | 1.33%   |
| Argentina   | 1         | 1.33%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Saint-Laurent               | 8         | 10.26%  |
| Montreal                    | 4         | 5.13%   |
| Milan                       | 3         | 3.85%   |
| Hoffman Estates             | 3         | 3.85%   |
| Mount Prospect              | 2         | 2.56%   |
| Lodz                        | 2         | 2.56%   |
| Lambeth                     | 2         | 2.56%   |
| Belo Horizonte              | 2         | 2.56%   |
| Ashburn                     | 2         | 2.56%   |
| Zuben                       | 1         | 1.28%   |
| Zagreb                      | 1         | 1.28%   |
| Winnipeg                    | 1         | 1.28%   |
| West Valley City            | 1         | 1.28%   |
| Waynesboro                  | 1         | 1.28%   |
| Voelklingen                 | 1         | 1.28%   |
| Vilnius                     | 1         | 1.28%   |
| Valmorea                    | 1         | 1.28%   |
| Valencia                    | 1         | 1.28%   |
| Tuchenbach                  | 1         | 1.28%   |
| Sunderland                  | 1         | 1.28%   |
| St Petersburg               | 1         | 1.28%   |
| San Nicolás de los Arroyos | 1         | 1.28%   |
| Rheda-Wiedenbrueck          | 1         | 1.28%   |
| Putten                      | 1         | 1.28%   |
| Prudhoe                     | 1         | 1.28%   |
| Princeton Junction          | 1         | 1.28%   |
| Prague                      | 1         | 1.28%   |
| Portage                     | 1         | 1.28%   |
| Paris                       | 1         | 1.28%   |
| Ottawa                      | 1         | 1.28%   |
| Oldenburg                   | 1         | 1.28%   |
| Nishishinjuku               | 1         | 1.28%   |
| New York                    | 1         | 1.28%   |
| Moscow                      | 1         | 1.28%   |
| Morden                      | 1         | 1.28%   |
| Minneapolis                 | 1         | 1.28%   |
| Meyrin                      | 1         | 1.28%   |
| Melbourne                   | 1         | 1.28%   |
| Martignas-sur-Jalle         | 1         | 1.28%   |
| Malmo                       | 1         | 1.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor                             | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| NVMe                               | 25        | 26     | 24.51%  |
| WDC                                | 11        | 16     | 10.78%  |
| Samsung Electronics                | 10        | 16     | 9.8%    |
| Seagate                            | 5         | 6      | 4.9%    |
| SanDisk                            | 5         | 5      | 4.9%    |
| Kingston                           | 4         | 4      | 3.92%   |
| A-DATA Technology                  | 4         | 4      | 3.92%   |
| Product:              USB DISK 2.0 | 3         | 3      | 2.94%   |
| PNY                                | 3         | 6      | 2.94%   |
| OPENBSD                            | 3         | 3      | 2.94%   |
| Intel                              | 3         | 4      | 2.94%   |
| Toshiba                            | 2         | 2      | 1.96%   |
| LITEONIT                           | 2         | 2      | 1.96%   |
| Hitachi                            | 2         | 2      | 1.96%   |
| Crucial                            | 2         | 2      | 1.96%   |
| China                              | 2         | 2      | 1.96%   |
| Apple                              | 2         | 2      | 1.96%   |
| Transcend                          | 1         | 1      | 0.98%   |
| SK hynix                           | 1         | 1      | 0.98%   |
| Patriot                            | 1         | 1      | 0.98%   |
| Micron Technology                  | 1         | 1      | 0.98%   |
| KingSpec                           | 1         | 1      | 0.98%   |
| Kingchuxing                        | 1         | 2      | 0.98%   |
| JetFlash                           | 1         | 1      | 0.98%   |
| Intenso                            | 1         | 1      | 0.98%   |
| HGST                               | 1         | 1      | 0.98%   |
| Hewlett-Packard                    | 1         | 1      | 0.98%   |
| BIWIN                              | 1         | 1      | 0.98%   |
| ASMT                               | 1         | 1      | 0.98%   |
| Apacer                             | 1         | 1      | 0.98%   |
| Acer                               | 1         | 1      | 0.98%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung SSD 870 EVO 250GB                            | 3         | 2.83%   |
| Product:              USB DISK 2.0 USB DISK 2.0 16GB | 3         | 2.83%   |
| NVMe Samsung SSD 980 1TB                             | 3         | 2.83%   |
| WDC WD5003ABYZ-011FA0 500GB                          | 2         | 1.89%   |
| WDC WD10EZEX-00BN5A0 1TB                             | 2         | 1.89%   |
| Seagate ST320LT007-9ZV142 320GB                      | 2         | 1.89%   |
| PNY CS900 1TB SSD                                    | 2         | 1.89%   |
| OPENBSD SR RAID 1 128GB                              | 2         | 1.89%   |
| NVMe SAMSUNG MZVLW256 256GB                          | 2         | 1.89%   |
| Kingston SA400S37240G 240GB                          | 2         | 1.89%   |
| A-DATA SU900 256GB                                   | 2         | 1.89%   |
| WDC WD7500BPKX-00HPJT0 752GB                         | 1         | 0.94%   |
| WDC WD7500BPKT-75PK4T0 752GB                         | 1         | 0.94%   |
| WDC WD7500BPKT-00PK4T0 752GB                         | 1         | 0.94%   |
| WDC WD5000LPLX-00ZNTT0 500GB                         | 1         | 0.94%   |
| WDC WD3200BEVE-00A0HT0 320GB                         | 1         | 0.94%   |
| WDC WD10JPLX-00MBPT0 1TB                             | 1         | 0.94%   |
| WDC WD10EZEX-21WN4A0 1TB                             | 1         | 0.94%   |
| WDC WD10EZEX-08WN4A0 1TB                             | 1         | 0.94%   |
| WDC PC SN520 SDAPNUW-128G-1014 128GB                 | 1         | 0.94%   |
| Transcend TSITHSD512-004G                            | 1         | 0.94%   |
| Toshiba MK6465GSX 640GB                              | 1         | 0.94%   |
| Toshiba External USB 3.0 1TB                         | 1         | 0.94%   |
| SK hynix HFS128G39TND-N210A 128GB                    | 1         | 0.94%   |
| Seagate ST9500420AS 500GB                            | 1         | 0.94%   |
| Seagate ST9160821A 160GB                             | 1         | 0.94%   |
| Seagate ST750LM022 HN-M750MBB 752GB                  | 1         | 0.94%   |
| Seagate ST2000DM008-2FR102 2TB                       | 1         | 0.94%   |
| SanDisk SSD PLUS 120 GB                              | 1         | 0.94%   |
| SanDisk SDSSDA480G 480GB                             | 1         | 0.94%   |
| SanDisk SD8SN8U-256G-1006 256GB                      | 1         | 0.94%   |
| SanDisk Cruzer Blade 16GB                            | 1         | 0.94%   |
| SanDisk 3.2 Gen1 128GB                               | 1         | 0.94%   |
| Samsung SSD PM871 mSATA 256GB                        | 1         | 0.94%   |
| Samsung SSD PM871 mSATA 128GB                        | 1         | 0.94%   |
| Samsung SSD 960 EVO 500GB                            | 1         | 0.94%   |
| Samsung SSD 870 QVO 2TB                              | 1         | 0.94%   |
| Samsung SSD 860 QVO 1TB                              | 1         | 0.94%   |
| Samsung SSD 860 EVO 1TB                              | 1         | 0.94%   |
| Samsung SSD 840 EVO 250GB                            | 1         | 0.94%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                             | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| NVMe                               | 14        | 15     | 32.56%  |
| WDC                                | 10        | 15     | 23.26%  |
| Seagate                            | 5         | 6      | 11.63%  |
| Product:              USB DISK 2.0 | 3         | 3      | 6.98%   |
| OPENBSD                            | 3         | 3      | 6.98%   |
| Toshiba                            | 2         | 2      | 4.65%   |
| Hitachi                            | 2         | 2      | 4.65%   |
| JetFlash                           | 1         | 1      | 2.33%   |
| Intenso                            | 1         | 1      | 2.33%   |
| HGST                               | 1         | 1      | 2.33%   |
| ASMT                               | 1         | 1      | 2.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| NVMe                | 11        | 11     | 19.64%  |
| Samsung Electronics | 9         | 15     | 16.07%  |
| SanDisk             | 5         | 5      | 8.93%   |
| Kingston            | 4         | 4      | 7.14%   |
| A-DATA Technology   | 4         | 4      | 7.14%   |
| PNY                 | 3         | 6      | 5.36%   |
| Intel               | 3         | 4      | 5.36%   |
| LITEONIT            | 2         | 2      | 3.57%   |
| China               | 2         | 2      | 3.57%   |
| Apple               | 2         | 2      | 3.57%   |
| Transcend           | 1         | 1      | 1.79%   |
| SK hynix            | 1         | 1      | 1.79%   |
| Patriot             | 1         | 1      | 1.79%   |
| Micron Technology   | 1         | 1      | 1.79%   |
| KingSpec            | 1         | 1      | 1.79%   |
| Kingchuxing         | 1         | 2      | 1.79%   |
| Hewlett-Packard     | 1         | 1      | 1.79%   |
| Crucial             | 1         | 1      | 1.79%   |
| BIWIN               | 1         | 1      | 1.79%   |
| Apacer              | 1         | 1      | 1.79%   |
| Acer                | 1         | 1      | 1.79%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 49        | 67     | 53.85%  |
| HDD  | 39        | 50     | 42.86%  |
| NVMe | 3         | 3      | 3.3%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 71        | 117    | 95.95%  |
| NVMe | 3         | 3      | 4.05%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 54        | 74     | 63.53%  |
| 0.51-1.0   | 23        | 30     | 27.06%  |
| 1.01-2.0   | 5         | 10     | 5.88%   |
| 3.01-4.0   | 1         | 1      | 1.18%   |
| 2.01-3.0   | 1         | 1      | 1.18%   |
| 4.01-10.0  | 1         | 1      | 1.18%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 26        | 34.67%  |
| 251-500        | 20        | 26.67%  |
| 21-50          | 10        | 13.33%  |
| 51-100         | 8         | 10.67%  |
| 1001-2000      | 4         | 5.33%   |
| 501-1000       | 3         | 4%      |
| More than 3000 | 2         | 2.67%   |
| 1-20           | 2         | 2.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 52        | 69.33%  |
| 51-100    | 7         | 9.33%   |
| 21-50     | 6         | 8%      |
| 101-250   | 5         | 6.67%   |
| 501-1000  | 3         | 4%      |
| 251-500   | 1         | 1.33%   |
| 1001-2000 | 1         | 1.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                  | Computers | Drives | Percent |
|----------------------------------------|-----------|--------|---------|
| Seagate ST320LT007-9ZV142 320GB        | 2         | 2      | 18.18%  |
| Toshiba MK6465GSX 640GB                | 1         | 1      | 9.09%   |
| SK hynix HFS128G39TND-N210A 128GB      | 1         | 1      | 9.09%   |
| Seagate ST9500420AS 500GB              | 1         | 1      | 9.09%   |
| Seagate ST750LM022 HN-M750MBB 752GB    | 1         | 1      | 9.09%   |
| Seagate ST2000DM008-2FR102 2TB         | 1         | 1      | 9.09%   |
| Samsung Electronics SSD 840 EVO 250GB  | 1         | 1      | 9.09%   |
| LITEONIT LCM-128M3S 2.5-inch 7mm 128GB | 1         | 1      | 9.09%   |
| Hitachi HTS541060G9AT00 64GB           | 1         | 1      | 9.09%   |
| A-DATA Technology SP550 480GB          | 1         | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 5      | 40%     |
| Toshiba             | 1         | 1      | 10%     |
| SK hynix            | 1         | 1      | 10%     |
| Samsung Electronics | 1         | 1      | 10%     |
| LITEONIT            | 1         | 1      | 10%     |
| Hitachi             | 1         | 1      | 10%     |
| A-DATA Technology   | 1         | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 5      | 66.67%  |
| Toshiba | 1         | 1      | 16.67%  |
| Hitachi | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 7      | 60%     |
| SSD  | 4         | 4      | 40%     |

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
| Works    | 50        | 74     | 56.18%  |
| Detected | 29        | 35     | 32.58%  |
| Malfunc  | 10        | 11     | 11.24%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 49        | 53.85%  |
| Samsung Electronics         | 13        | 14.29%  |
| AMD                         | 10        | 10.99%  |
| SanDisk                     | 6         | 6.59%   |
| Micron/Crucial Technology   | 3         | 3.3%    |
| Phison Electronics          | 2         | 2.2%    |
| Kingston Technology Company | 2         | 2.2%    |
| Silicon Motion              | 1         | 1.1%    |
| Realtek Semiconductor       | 1         | 1.1%    |
| Micron Technology           | 1         | 1.1%    |
| MAXIO Technology (Hangzhou) | 1         | 1.1%    |
| Marvell Technology Group    | 1         | 1.1%    |
| JMicron Technology          | 1         | 1.1%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 7.22%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 5.15%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 5         | 5.15%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 4.12%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 4         | 4.12%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 3.09%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 3.09%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 3.09%   |
| AMD 600 Series Chipset SATA Controller                                         | 3         | 3.09%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 2         | 2.06%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 2         | 2.06%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 2.06%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 2.06%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 2.06%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 2         | 2.06%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 2.06%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2         | 2.06%   |
| AMD 500 Series Chipset SATA Controller                                         | 2         | 2.06%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 1         | 1.03%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 1.03%   |
| Sandisk WD PC SN540 / Green SN350 NVMe SSD 1 TB (DRAM-less)                    | 1         | 1.03%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 1         | 1.03%   |
| Sandisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 1         | 1.03%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 1         | 1.03%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                             | 1         | 1.03%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 1         | 1.03%   |
| Samsung NVMe SSD Controller PM9C1a (DRAM-less)                                 | 1         | 1.03%   |
| Realtek RTS5772DL NVMe SSD Controller (DRAM-less)                              | 1         | 1.03%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 1         | 1.03%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1         | 1.03%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                      | 1         | 1.03%   |
| Micron 2550 NVMe SSD (DRAM-less)                                               | 1         | 1.03%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 1         | 1.03%   |
| Marvell Group 88SE9123 PCIe SATA 6.0 Gb/s controller                           | 1         | 1.03%   |
| Kingston Company NV2 NVMe SSD [TC2200] (DRAM-less)                             | 1         | 1.03%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD [E18]                           | 1         | 1.03%   |
| JMicron JMB362 SATA Controller                                                 | 1         | 1.03%   |
| Intel SSD 660P Series                                                          | 1         | 1.03%   |
| Intel Raptor Lake SATA AHCI Controller                                         | 1         | 1.03%   |
| Intel NVMe Optane Memory Series                                                | 1         | 1.03%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 57        | 62.64%  |
| NVMe | 29        | 31.87%  |
| IDE  | 5         | 5.49%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 59        | 78.67%  |
| AMD     | 12        | 16%     |
| PowerPC | 1         | 1.33%   |
| ARM     | 1         | 1.33%   |
| 11th    | 1         | 1.33%   |
| Unknown | 1         | 1.33%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz       | 5         | 6.67%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 5         | 6.67%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 3         | 4%      |
| Intel N100                              | 2         | 2.67%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 2         | 2.67%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 2         | 2.67%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 2         | 2.67%   |
| AMD Ryzen 7 7700X 8-Core Processor      | 2         | 2.67%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 2         | 2.67%   |
| PowerPC 7447A (Revision 0x102)          | 1         | 1.33%   |
| Intel Xeon D-2123IT CPU @ 2.20GHz       | 1         | 1.33%   |
| Intel Xeon CPU E5-2667 v4 @ 3.20GHz     | 1         | 1.33%   |
| Intel Processor 5Y10 CPU @ 0.80GHz      | 1         | 1.33%   |
| Intel Pentium CPU P6100 @ 2.00GHz       | 1         | 1.33%   |
| Intel Pentium CPU G4560 @ 3.50GHz       | 1         | 1.33%   |
| Intel Pentium 4 Mobile CPU 1.60GHz      | 1         | 1.33%   |
| Intel Genuine CPU T2300 @ 1.66GHz       | 1         | 1.33%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 1         | 1.33%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 1         | 1.33%   |
| Intel Core i7-8086K CPU @ 4.00GHz       | 1         | 1.33%   |
| Intel Core i7-6700K CPU @ 4.00GHz       | 1         | 1.33%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz      | 1         | 1.33%   |
| Intel Core i7-4770 CPU @ 3.40GHz        | 1         | 1.33%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 1         | 1.33%   |
| Intel Core i7 CPU 960 @ 3.20GHz         | 1         | 1.33%   |
| Intel Core i5-8500 CPU @ 3.00GHz        | 1         | 1.33%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 1         | 1.33%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 1         | 1.33%   |
| Intel Core i5-7400 CPU @ 3.00GHz        | 1         | 1.33%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 1         | 1.33%   |
| Intel Core i5-5350U CPU @ 1.80GHz       | 1         | 1.33%   |
| Intel Core i5-5250U CPU @ 1.60GHz       | 1         | 1.33%   |
| Intel Core i5-4288U CPU @ 2.60GHz       | 1         | 1.33%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 1         | 1.33%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 1         | 1.33%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 1         | 1.33%   |
| Intel Core i3-7100U CPU @ 2.40GHz       | 1         | 1.33%   |
| Intel Core i3-4005U CPU @ 1.70GHz       | 1         | 1.33%   |
| Intel Core i3-10110U CPU @ 2.10GHz      | 1         | 1.33%   |
| Intel Core 2 Duo CPU T6400 @ 2.00GHz    | 1         | 1.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 28        | 37.33%  |
| Other            | 11        | 14.67%  |
| Intel Core i7    | 8         | 10.67%  |
| AMD Ryzen 7      | 7         | 9.33%   |
| Intel Core i3    | 3         | 4%      |
| Intel Atom       | 3         | 4%      |
| Intel Xeon       | 2         | 2.67%   |
| Intel Pentium    | 2         | 2.67%   |
| Intel Core 2 Duo | 2         | 2.67%   |
| AMD Ryzen 9      | 2         | 2.67%   |
| Intel Pentium 4  | 1         | 1.33%   |
| Intel Genuine    | 1         | 1.33%   |
| Intel Celeron    | 1         | 1.33%   |
| ARM Cortex       | 1         | 1.33%   |
| AMD Ryzen 5      | 1         | 1.33%   |
| AMD EPYC         | 1         | 1.33%   |
| AMD Athlon II    | 1         | 1.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 32        | 42.67%  |
| 4       | 16        | 21.33%  |
| Unknown | 7         | 9.33%   |
| 16      | 6         | 8%      |
| 6       | 5         | 6.67%   |
| 8       | 4         | 5.33%   |
| 1       | 3         | 4%      |
| 32      | 2         | 2.67%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 69        | 92%     |
| Unknown | 6         | 8%      |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 46        | 61.33%  |
| 1       | 20        | 26.67%  |
| Unknown | 9         | 12%     |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Unknown     | 12        | 16%     |
| KabyLake    | 11        | 14.67%  |
| Skylake     | 9         | 12%     |
| Broadwell   | 7         | 9.33%   |
| SandyBridge | 5         | 6.67%   |
| Zen 2       | 4         | 5.33%   |
| IvyBridge   | 4         | 5.33%   |
| Haswell     | 4         | 5.33%   |
| Westmere    | 3         | 4%      |
| Zen 3       | 2         | 2.67%   |
| TigerLake   | 2         | 2.67%   |
| Penryn      | 2         | 2.67%   |
| Goldmont    | 2         | 2.67%   |
| Zen+        | 1         | 1.33%   |
| Zen         | 1         | 1.33%   |
| Silvermont  | 1         | 1.33%   |
| P6          | 1         | 1.33%   |
| NetBurst    | 1         | 1.33%   |
| Nehalem     | 1         | 1.33%   |
| K10         | 1         | 1.33%   |
| Bonnell     | 1         | 1.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 51        | 65.38%  |
| AMD                        | 18        | 23.08%  |
| Nvidia                     | 4         | 5.13%   |
| ASPEED Technology          | 4         | 5.13%   |
| Matrox Electronics Systems | 1         | 1.28%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                           | 7         | 8.54%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 5         | 6.1%    |
| Intel 3rd Gen Core processor Graphics Controller                              | 4         | 4.88%   |
| ASPEED Technology ASPEED Graphics Family                                      | 4         | 4.88%   |
| Intel UHD Graphics 620                                                        | 3         | 3.66%   |
| Intel HD Graphics 5500                                                        | 3         | 3.66%   |
| Intel Core Processor Integrated Graphics Controller                           | 3         | 3.66%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                 | 3         | 3.66%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 2         | 2.44%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 2         | 2.44%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 2         | 2.44%   |
| Intel HD Graphics 620                                                         | 2         | 2.44%   |
| Intel HD Graphics 6000                                                        | 2         | 2.44%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 2         | 2.44%   |
| Intel Alder Lake-N [UHD Graphics]                                             | 2         | 2.44%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                   | 2         | 2.44%   |
| AMD Raphael                                                                   | 2         | 2.44%   |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                    | 2         | 2.44%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                    | 2         | 2.44%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 1         | 1.22%   |
| Nvidia NV34M [GeForce FX Go5200]                                              | 1         | 1.22%   |
| Nvidia GP108M [GeForce MX150]                                                 | 1         | 1.22%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 1         | 1.22%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)             | 1         | 1.22%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 1         | 1.22%   |
| Intel Raptor Lake-P [UHD Graphics]                                            | 1         | 1.22%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                        | 1         | 1.22%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 1.22%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 1         | 1.22%   |
| Intel HD Graphics 630                                                         | 1         | 1.22%   |
| Intel HD Graphics 610                                                         | 1         | 1.22%   |
| Intel HD Graphics 5300                                                        | 1         | 1.22%   |
| Intel HD Graphics 500                                                         | 1         | 1.22%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 1         | 1.22%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 1         | 1.22%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 1         | 1.22%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                     | 1         | 1.22%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 1         | 1.22%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 1         | 1.22%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                     | 1         | 1.22%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 44        | 57.89%  |
| 1 x AMD        | 14        | 18.42%  |
| 2 x Intel      | 4         | 5.26%   |
| 1 x ASPEED     | 4         | 5.26%   |
| Other          | 2         | 2.63%   |
| 2 x AMD        | 2         | 2.63%   |
| 1 x Nvidia     | 2         | 2.63%   |
| Intel + Nvidia | 2         | 2.63%   |
| 1 x Matrox     | 1         | 1.32%   |
| Intel + AMD    | 1         | 1.32%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 68        | 90.67%  |
| Unknown | 7         | 9.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 75        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| LG Display          | 10        | 18.18%  |
| BOE                 | 7         | 12.73%  |
| AU Optronics        | 6         | 10.91%  |
| Samsung Electronics | 5         | 9.09%   |
| Philips             | 3         | 5.45%   |
| Goldstar            | 3         | 5.45%   |
| Chimei Innolux      | 3         | 5.45%   |
| Lenovo              | 2         | 3.64%   |
| Dell                | 2         | 3.64%   |
| BenQ                | 2         | 3.64%   |
| Apple               | 2         | 3.64%   |
| ViewSonic           | 1         | 1.82%   |
| InfoVision          | 1         | 1.82%   |
| Iiyama              | 1         | 1.82%   |
| Huion               | 1         | 1.82%   |
| Eizo                | 1         | 1.82%   |
| CSO                 | 1         | 1.82%   |
| CMT                 | 1         | 1.82%   |
| ASUSTek Computer    | 1         | 1.82%   |
| AOC                 | 1         | 1.82%   |
| Acer                | 1         | 1.82%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                | 3         | 5.45%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch    | 2         | 3.64%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch          | 2         | 3.64%   |
| AU Optronics LCD Monitor AUO103D 1920x1080 310x170mm 13.9-inch       | 2         | 3.64%   |
| ViewSonic VA2026w VSC5020 1680x1050 430x270mm 20.0-inch              | 1         | 1.82%   |
| Samsung Electronics SyncMaster SAM026F 1280x1024 380x300mm 19.1-inch | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 310x170mm 13.9-inch | 1         | 1.82%   |
| Samsung Electronics C27F398 SAM0D44 1920x1080 600x340mm 27.2-inch    | 1         | 1.82%   |
| LG Display LCD Monitor LGD6E01 1366x768 340x190mm 15.3-inch          | 1         | 1.82%   |
| LG Display LCD Monitor LGD40A0 1366x768 310x170mm 13.9-inch          | 1         | 1.82%   |
| LG Display LCD Monitor LGD05A2 1920x1080 310x170mm 13.9-inch         | 1         | 1.82%   |
| LG Display LCD Monitor LGD045E 1366x768 310x170mm 13.9-inch          | 1         | 1.82%   |
| LG Display LCD Monitor LGD0395 1366x768 340x190mm 15.3-inch          | 1         | 1.82%   |
| LG Display LCD Monitor LGD0386 1366x768 310x170mm 13.9-inch          | 1         | 1.82%   |
| LG Display LCD Monitor LGD02D3 1366x768 280x160mm 12.7-inch          | 1         | 1.82%   |
| LG Display LCD Monitor LGD0215 1920x1080 350x190mm 15.7-inch         | 1         | 1.82%   |
| Lenovo LEN L174 LEN240B 1280x1024 340x270mm 17.1-inch                | 1         | 1.82%   |
| Lenovo LCD Monitor LEN4033 1440x900 300x190mm 14.0-inch              | 1         | 1.82%   |
| InfoVision LCD Monitor IVO04E3 1366x768 280x160mm 12.7-inch          | 1         | 1.82%   |
| Iiyama PL3294Q IVM762D 2560x1440 700x390mm 31.5-inch                 | 1         | 1.82%   |
| Huion GS1562 HAT1560 1920x1080 340x200mm 15.5-inch                   | 1         | 1.82%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 580x240mm 24.7-inch          | 1         | 1.82%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch         | 1         | 1.82%   |
| Goldstar LG FHD GSM5BCA 1920x1080 600x340mm 27.2-inch                | 1         | 1.82%   |
| Eizo EV2795 ENC3149 2560x1440 600x340mm 27.2-inch                    | 1         | 1.82%   |
| Dell P2419H DELD0DA 1920x1080 530x300mm 24.0-inch                    | 1         | 1.82%   |
| Dell P190S DEL405A 1280x1024 380x300mm 19.1-inch                     | 1         | 1.82%   |
| CSO LCD Monitor CSO1404 1920x1200 300x190mm 14.0-inch                | 1         | 1.82%   |
| CMT GP27-FUS CMT2704 3840x2160 600x340mm 27.2-inch                   | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 340x190mm 15.3-inch     | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch     | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 280x160mm 12.7-inch     | 1         | 1.82%   |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                | 1         | 1.82%   |
| BOE LCD Monitor BOE0900 1920x1080 340x190mm 15.3-inch                | 1         | 1.82%   |
| BOE LCD Monitor BOE0853 1920x1080 340x190mm 15.3-inch                | 1         | 1.82%   |
| BOE LCD Monitor BOE0718 1920x1080 310x170mm 13.9-inch                | 1         | 1.82%   |
| BOE LCD Monitor BOE0700 1920x1080 340x190mm 15.3-inch                | 1         | 1.82%   |
| BOE LCD Monitor BOE06DF 1920x1080 310x170mm 13.9-inch                | 1         | 1.82%   |
| BOE LCD Monitor BOE05F4 1366x768 280x160mm 12.7-inch                 | 1         | 1.82%   |
| BenQ PJ BNQ4102 1920x1080                                            | 1         | 1.82%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 25        | 47.17%  |
| 1366x768 (WXGA)    | 13        | 24.53%  |
| 3840x2160 (4K)     | 3         | 5.66%   |
| 1280x1024 (SXGA)   | 3         | 5.66%   |
| 2560x1440 (QHD)    | 2         | 3.77%   |
| 1440x900 (WXGA+)   | 2         | 3.77%   |
| 2560x1600          | 1         | 1.89%   |
| 2560x1080          | 1         | 1.89%   |
| 2256x1504          | 1         | 1.89%   |
| 1920x1200 (WUXGA)  | 1         | 1.89%   |
| 1680x1050 (WSXGA+) | 1         | 1.89%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 15        | 27.78%  |
| 15      | 9         | 16.67%  |
| 12      | 7         | 12.96%  |
| 27      | 5         | 9.26%   |
| 21      | 4         | 7.41%   |
| 23      | 3         | 5.56%   |
| 19      | 2         | 3.7%    |
| 14      | 2         | 3.7%    |
| 34      | 1         | 1.85%   |
| 32      | 1         | 1.85%   |
| 31      | 1         | 1.85%   |
| 24      | 1         | 1.85%   |
| 20      | 1         | 1.85%   |
| 17      | 1         | 1.85%   |
| Unknown | 1         | 1.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 21        | 38.89%  |
| 201-300     | 13        | 24.07%  |
| 501-600     | 9         | 16.67%  |
| 401-500     | 5         | 9.26%   |
| 701-800     | 2         | 3.7%    |
| 351-400     | 2         | 3.7%    |
| 601-700     | 1         | 1.85%   |
| Unknown     | 1         | 1.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 43        | 81.13%  |
| 16/10 | 5         | 9.43%   |
| 5/4   | 3         | 5.66%   |
| 3/2   | 1         | 1.89%   |
| 21/9  | 1         | 1.89%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 16        | 30.19%  |
| 201-250        | 8         | 15.09%  |
| 61-70          | 7         | 13.21%  |
| 91-100         | 6         | 11.32%  |
| 301-350        | 5         | 9.43%   |
| 151-200        | 3         | 5.66%   |
| 101-110        | 3         | 5.66%   |
| 351-500        | 2         | 3.77%   |
| 71-80          | 1         | 1.89%   |
| 141-150        | 1         | 1.89%   |
| Unknown        | 1         | 1.89%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 22        | 41.51%  |
| 51-100  | 12        | 22.64%  |
| 101-120 | 11        | 20.75%  |
| 161-240 | 7         | 13.21%  |
| Unknown | 1         | 1.89%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 54        | 72%     |
| 0     | 16        | 21.33%  |
| 2     | 4         | 5.33%   |
| 3     | 1         | 1.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 57        | 55.88%  |
| Realtek Semiconductor    | 23        | 22.55%  |
| Broadcom                 | 7         | 6.86%   |
| Sierra Wireless          | 3         | 2.94%   |
| Qualcomm Atheros         | 3         | 2.94%   |
| Marvell Technology Group | 2         | 1.96%   |
| Apple                    | 2         | 1.96%   |
| Samsung Electronics      | 1         | 0.98%   |
| Ralink                   | 1         | 0.98%   |
| Qualcomm Technologies    | 1         | 0.98%   |
| Dell                     | 1         | 0.98%   |
| American Megatrends      | 1         | 0.98%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 11        | 7.91%   |
| Realtek RTL8125 2.5GbE Controller                                      | 8         | 5.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8         | 5.76%   |
| Intel Wireless 8260                                                    | 7         | 5.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 7         | 5.04%   |
| Intel Wireless 8265 / 8275                                             | 5         | 3.6%    |
| Intel Wireless 7265                                                    | 5         | 3.6%    |
| Intel Ethernet Connection I219-LM                                      | 5         | 3.6%    |
| Intel Wi-Fi 6 AX200                                                    | 4         | 2.88%   |
| Intel I210 Gigabit Network Connection                                  | 3         | 2.16%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 2.16%   |
| Intel Ethernet Connection (3) I218-LM                                  | 3         | 2.16%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 3         | 2.16%   |
| Sierra Wireless EM7455                                                 | 2         | 1.44%   |
| Intel Wireless 7260                                                    | 2         | 1.44%   |
| Intel Wi-Fi 6 AX201                                                    | 2         | 1.44%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 2         | 1.44%   |
| Intel Ethernet Controller I226-V                                       | 2         | 1.44%   |
| Intel Ethernet Connection I219-V                                       | 2         | 1.44%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 1.44%   |
| Intel Centrino Advanced-N 6200                                         | 2         | 1.44%   |
| Intel 82577LM Gigabit Network Connection                               | 2         | 1.44%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 2         | 1.44%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 2         | 1.44%   |
| Sierra Wireless EM7305 Modem                                           | 1         | 0.72%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 0.72%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller            | 1         | 0.72%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 1         | 0.72%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                             | 1         | 0.72%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1         | 0.72%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                | 1         | 0.72%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1         | 0.72%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 1         | 0.72%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 0.72%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 1         | 0.72%   |
| Qualcomm WCN785x Wi-Fi 7(802.11be) 320MHz 2x2 [FastConnect 7800]       | 1         | 0.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 1         | 0.72%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 1         | 0.72%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.72%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 1         | 0.72%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 46        | 73.02%  |
| Broadcom              | 6         | 9.52%   |
| Realtek Semiconductor | 5         | 7.94%   |
| Sierra Wireless       | 2         | 3.17%   |
| Qualcomm Atheros      | 2         | 3.17%   |
| Ralink                | 1         | 1.59%   |
| Dell                  | 1         | 1.59%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                            | 7         | 10.94%  |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 7         | 10.94%  |
| Intel Wireless 8265 / 8275                                     | 5         | 7.81%   |
| Intel Wireless 7265                                            | 5         | 7.81%   |
| Intel Wi-Fi 6 AX200                                            | 4         | 6.25%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 4.69%   |
| Sierra Wireless EM7455                                         | 2         | 3.13%   |
| Intel Wireless 7260                                            | 2         | 3.13%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 3.13%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 2         | 3.13%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 3.13%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 2         | 3.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 3.13%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller    | 1         | 1.56%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 1         | 1.56%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 1         | 1.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 1.56%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 1.56%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 1.56%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 1.56%   |
| Intel WiFi Link 5100                                           | 1         | 1.56%   |
| Intel Ultimate N WiFi Link 5300                                | 1         | 1.56%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 1.56%   |
| Intel Raptor Lake-S PCH CNVi WiFi                              | 1         | 1.56%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 1.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 1.56%   |
| Intel CNVi: Wi-Fi                                              | 1         | 1.56%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 1         | 1.56%   |
| Dell Wireless 5809e Gobi 4G LTE Mobile Broadband DM Port       | 1         | 1.56%   |
| Broadcom BCM43225 802.11b/g/n                                  | 1         | 1.56%   |
| Broadcom BCM4306 802.11b/g Wireless LAN Controller             | 1         | 1.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 39        | 54.93%  |
| Realtek Semiconductor    | 22        | 30.99%  |
| Qualcomm Atheros         | 2         | 2.82%   |
| Marvell Technology Group | 2         | 2.82%   |
| Broadcom                 | 2         | 2.82%   |
| Apple                    | 2         | 2.82%   |
| Samsung Electronics      | 1         | 1.41%   |
| American Megatrends      | 1         | 1.41%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 11        | 15.07%  |
| Realtek RTL8125 2.5GbE Controller                                      | 8         | 10.96%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8         | 10.96%  |
| Intel Ethernet Connection I219-LM                                      | 5         | 6.85%   |
| Intel I210 Gigabit Network Connection                                  | 3         | 4.11%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 4.11%   |
| Intel Ethernet Connection (3) I218-LM                                  | 3         | 4.11%   |
| Intel Ethernet Controller I226-V                                       | 2         | 2.74%   |
| Intel Ethernet Connection I219-V                                       | 2         | 2.74%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 2.74%   |
| Intel 82577LM Gigabit Network Connection                               | 2         | 2.74%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 1.37%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1         | 1.37%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 1         | 1.37%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 1.37%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 1.37%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 1         | 1.37%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1         | 1.37%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 1         | 1.37%   |
| Intel I350 Gigabit Network Connection                                  | 1         | 1.37%   |
| Intel I211 Gigabit Network Connection                                  | 1         | 1.37%   |
| Intel Ethernet Controller I225-V                                       | 1         | 1.37%   |
| Intel Ethernet Connection X722 for 10GBASE-T                           | 1         | 1.37%   |
| Intel Ethernet Connection X553 Backplane                               | 1         | 1.37%   |
| Intel Ethernet Connection X553 10 GbE SFP+                             | 1         | 1.37%   |
| Intel Ethernet Connection I217-V                                       | 1         | 1.37%   |
| Intel Ethernet Connection (7) I219-V                                   | 1         | 1.37%   |
| Intel Ethernet Connection (2) I219-V                                   | 1         | 1.37%   |
| Intel 82579V Gigabit Network Connection                                | 1         | 1.37%   |
| Intel 82567LM Gigabit Network Connection                               | 1         | 1.37%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                       | 1         | 1.37%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1         | 1.37%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                        | 1         | 1.37%   |
| Apple Ethernet Adapter [A1277]                                         | 1         | 1.37%   |
| American Megatrends Virtual Ethernet                                   | 1         | 1.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 68        | 53.13%  |
| WiFi     | 58        | 45.31%  |
| Unknown  | 2         | 1.56%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 40        | 53.33%  |
| Ethernet | 35        | 46.67%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 52        | 69.33%  |
| 1     | 17        | 22.67%  |
| 6     | 2         | 2.67%   |
| 9     | 1         | 1.33%   |
| 4     | 1         | 1.33%   |
| 3     | 1         | 1.33%   |
| 0     | 1         | 1.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 73        | 97.33%  |
| Yes  | 2         | 2.67%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 29        | 69.05%  |
| Broadcom              | 3         | 7.14%   |
| IMC Networks          | 2         | 4.76%   |
| Apple                 | 2         | 4.76%   |
| Alps Electric         | 2         | 4.76%   |
| Realtek Semiconductor | 1         | 2.38%   |
| Ralink                | 1         | 2.38%   |
| Foxconn / Hon Hai     | 1         | 2.38%   |
| ASUSTek Computer      | 1         | 2.38%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                       | 16        | 38.1%   |
| Intel AX201 Bluetooth                                    | 5         | 11.9%   |
| Intel Wireless-AC 3168 Bluetooth                         | 3         | 7.14%   |
| Intel AX200 Bluetooth                                    | 3         | 7.14%   |
| Intel AX211 Bluetooth                                    | 2         | 4.76%   |
| Alps Electric UGTZ4 Bluetooth                            | 2         | 4.76%   |
| Realtek Bluetooth Adapter                                | 1         | 2.38%   |
| Ralink RT3290 Bluetooth                                  | 1         | 2.38%   |
| IMC Networks Realtek Bluetooth Adapter                   | 1         | 2.38%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1              | 1         | 2.38%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device | 1         | 2.38%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 1         | 2.38%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]               | 1         | 2.38%   |
| Broadcom BCM2045B (BDC-2.1)                              | 1         | 2.38%   |
| ASUS Broadcom Bluetooth 2.1                              | 1         | 2.38%   |
| Apple Broadcom Built-in Bluetooth                        | 1         | 2.38%   |
| Apple Bluetooth Host Controller                          | 1         | 2.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 55        | 68.75%  |
| AMD                 | 18        | 22.5%   |
| Nvidia              | 2         | 2.5%    |
| C-Media Electronics | 2         | 2.5%    |
| Samson Technologies | 1         | 1.25%   |
| Logitech            | 1         | 1.25%   |
| Creative Technology | 1         | 1.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 12        | 11.65%  |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 7         | 6.8%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 6         | 5.83%   |
| Intel Broadwell-U Audio Controller                                         | 6         | 5.83%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 6         | 5.83%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 4.85%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 3.88%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 2.91%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3         | 2.91%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 2.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 1.94%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 1.94%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 2         | 1.94%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 1.94%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.94%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 1.94%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                    | 2         | 1.94%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 1.94%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 1.94%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.94%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 1.94%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 2         | 1.94%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2         | 1.94%   |
| Samson Technologies GoMic compact condenser mic                            | 1         | 0.97%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.97%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 0.97%   |
| Logitech [G533 Wireless Headset Dongle]                                    | 1         | 0.97%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 0.97%   |
| Intel Raptor Lake High Definition Audio Controller                         | 1         | 0.97%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 0.97%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 0.97%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 0.97%   |
| Intel 82801CA/CAM AC'97 Audio Controller                                   | 1         | 0.97%   |
| Intel 200 Series PCH HD Audio                                              | 1         | 0.97%   |
| Creative Technology Sound BlasterX G6                                      | 1         | 0.97%   |
| C-Media Electronics C-Media USB Audio Device                               | 1         | 0.97%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1         | 0.97%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 0.97%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 1         | 0.97%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 0.97%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 5         | 23.81%  |
| Samsung Electronics | 5         | 23.81%  |
| SK hynix            | 4         | 19.05%  |
| Micron Technology   | 2         | 9.52%   |
| Kingston            | 2         | 9.52%   |
| Unknown             | 2         | 9.52%   |
| Smart               | 1         | 4.76%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s            | 2         | 8.33%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s  | 2         | 8.33%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s  | 2         | 8.33%   |
| Unknown                                                | 2         | 8.33%   |
| Unknown RAM Module 512MB SODIMM SDRAM                  | 1         | 4.17%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s            | 1         | 4.17%   |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s            | 1         | 4.17%   |
| Unknown RAM Module 1GB SODIMM DDR2                     | 1         | 4.17%   |
| Smart RAM SH564568FH8NZPHSCG 2GB SODIMM DDR3 1066MT/s  | 1         | 4.17%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s  | 1         | 4.17%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s | 1         | 4.17%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s | 1         | 4.17%   |
| SK hynix RAM HMA84GR7DJR4N-XN 32GB DIMM DDR4 3200MT/s  | 1         | 4.17%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s  | 1         | 4.17%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 1067MT/s  | 1         | 4.17%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s  | 1         | 4.17%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s  | 1         | 4.17%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s | 1         | 4.17%   |
| Kingston RAM KF560C36-16 16GB DIMM DDR5 4800MT/s       | 1         | 4.17%   |
| Kingston RAM KF3600C18D4/32GX 32GB DIMM DDR4 3000MT/s  | 1         | 4.17%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 9         | 45%     |
| DDR4    | 5         | 25%     |
| SDRAM   | 2         | 10%     |
| DDR2    | 2         | 10%     |
| DDR5    | 1         | 5%      |
| Unknown | 1         | 5%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 16        | 80%     |
| DIMM   | 4         | 20%     |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 7         | 30.43%  |
| 8192  | 6         | 26.09%  |
| 4096  | 5         | 21.74%  |
| 32768 | 2         | 8.7%    |
| 16384 | 1         | 4.35%   |
| 1024  | 1         | 4.35%   |
| 512   | 1         | 4.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| Unknown | 4         | 20%     |
| 1600    | 3         | 15%     |
| 1333    | 3         | 15%     |
| 2133    | 2         | 10%     |
| 1067    | 2         | 10%     |
| 4800    | 1         | 5%      |
| 3200    | 1         | 5%      |
| 3000    | 1         | 5%      |
| 2667    | 1         | 5%      |
| 1066    | 1         | 5%      |
| 975     | 1         | 5%      |

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

![Scanner Vendor](./All/images/pie_chart_bsd/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart_bsd/scanner_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO] | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart_bsd/camera_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 9         | 29.03%  |
| Bison Electronics             | 6         | 19.35%  |
| Lite-On Technology            | 3         | 9.68%   |
| IMC Networks                  | 3         | 9.68%   |
| Sunplus Innovation Technology | 2         | 6.45%   |
| Realtek Semiconductor         | 2         | 6.45%   |
| Trust                         | 1         | 3.23%   |
| Silicon Motion                | 1         | 3.23%   |
| Quanta                        | 1         | 3.23%   |
| Logitech                      | 1         | 3.23%   |
| Lenovo                        | 1         | 3.23%   |
| ALi                           | 1         | 3.23%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony integrated camera                | 4         | 12.12%  |
| Lite-On Integrated Camera                | 3         | 9.09%   |
| Chicony Integrated IR Camera             | 3         | 9.09%   |
| Bison Integrated Camera                  | 3         | 9.09%   |
| Trust Trust QHD Webcam                   | 1         | 3.03%   |
| Sunplus LTD, NexiGo N930AF FHD Webcam    | 1         | 3.03%   |
| Sunplus Laptop Integrated Webcam HD      | 1         | 3.03%   |
| Silicon Motion Lenovo EasyCamera         | 1         | 3.03%   |
| Realtek Laptop Camera                    | 1         | 3.03%   |
| Realtek Integrated Webcam HD             | 1         | 3.03%   |
| Quanta USB HD Webcam                     | 1         | 3.03%   |
| Logitech Webcam C270                     | 1         | 3.03%   |
| Lenovo Integrated Webcam                 | 1         | 3.03%   |
| IMC Networks Realtek PC Camera           | 1         | 3.03%   |
| IMC Networks Integrated Camera           | 1         | 3.03%   |
| IMC Networks EasyCamera                  | 1         | 3.03%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 1         | 3.03%   |
| Chicony Integrated HP HD Webcam          | 1         | 3.03%   |
| Chicony FJ Camera                        | 1         | 3.03%   |
| Chicony 2.0M UVC Webcam / CNF7129        | 1         | 3.03%   |
| Bison USB HD Webcam                      | 1         | 3.03%   |
| Bison ThinkPad P50 Integrated Camera     | 1         | 3.03%   |
| Bison ThinkPad Integrated Camera         | 1         | 3.03%   |
| ALi Gateway Webcam                       | 1         | 3.03%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 6         | 60%     |
| Synaptics        | 2         | 20%     |
| AuthenTec        | 2         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor      | 3         | 30%     |
| Validity Sensors Synaptics WBDI                   | 2         | 20%     |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 2         | 20%     |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 10%     |
| AuthenTec AES2810                                 | 1         | 10%     |
| AuthenTec AES2660                                 | 1         | 10%     |

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
| 1     | 45        | 60%     |
| 2     | 11        | 14.67%  |
| 0     | 10        | 13.33%  |
| 3     | 5         | 6.67%   |
| 5     | 2         | 2.67%   |
| 4     | 2         | 2.67%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 53        | 61.63%  |
| Graphics card            | 11        | 12.79%  |
| Net/wireless             | 9         | 10.47%  |
| Firewire controller      | 7         | 8.14%   |
| Storage/ata              | 2         | 2.33%   |
| Sound                    | 1         | 1.16%   |
| Network                  | 1         | 1.16%   |
| Net/ethernet             | 1         | 1.16%   |
| Bluetooth                | 1         | 1.16%   |

