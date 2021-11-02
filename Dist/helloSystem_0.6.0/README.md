helloSystem 0.6.0 - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for helloSystem 0.6.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/helloSystem_0.6.0/Desktop/README.md) and [notebooks](/Dist/helloSystem_0.6.0/Notebook/README.md).

Full-feature report is available here: https://bsd-hardware.info/?view=trends&rel=hellosystem-0.6.0

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
| Apple         | MacBookAir5,1               | Notebook    | [b354b2bd4e](https://bsd-hardware.info/?probe=b354b2bd4e) | Oct 31, 2021 |
| HP            | Presario CQ43               | Notebook    | [b97d9ff563](https://bsd-hardware.info/?probe=b97d9ff563) | Oct 30, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [e25f042400](https://bsd-hardware.info/?probe=e25f042400) | Oct 30, 2021 |
| Unknown       | Intel X79                   | Desktop     | [044908e7c3](https://bsd-hardware.info/?probe=044908e7c3) | Oct 30, 2021 |
| Chuwi         | MiniBook                    | Notebook    | [4ce05f93a8](https://bsd-hardware.info/?probe=4ce05f93a8) | Oct 28, 2021 |
| Dell          | Precision M4600             | Notebook    | [2f848fd2c0](https://bsd-hardware.info/?probe=2f848fd2c0) | Oct 27, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [9f8010bdbe](https://bsd-hardware.info/?probe=9f8010bdbe) | Oct 25, 2021 |
| Sony          | SVS1511AJB                  | Notebook    | [a366b5fab3](https://bsd-hardware.info/?probe=a366b5fab3) | Oct 24, 2021 |
| Sony          | SVS1511AJB                  | Notebook    | [2333f62192](https://bsd-hardware.info/?probe=2333f62192) | Oct 24, 2021 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [9959c0900a](https://bsd-hardware.info/?probe=9959c0900a) | Oct 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [9996e06a3d](https://bsd-hardware.info/?probe=9996e06a3d) | Oct 22, 2021 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [b106820e47](https://bsd-hardware.info/?probe=b106820e47) | Oct 21, 2021 |
| Acer          | RS880M05                    | Desktop     | [4718f0cb0c](https://bsd-hardware.info/?probe=4718f0cb0c) | Oct 21, 2021 |
| Dell          | Studio 1747                 | Notebook    | [ed704cde92](https://bsd-hardware.info/?probe=ed704cde92) | Oct 20, 2021 |
| Apple         | MacBookPro4,1               | Notebook    | [10861818b2](https://bsd-hardware.info/?probe=10861818b2) | Oct 20, 2021 |
| Apple         | Mac-F221BEC8                | Desktop     | [cb2cc35e6c](https://bsd-hardware.info/?probe=cb2cc35e6c) | Oct 19, 2021 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [3cf20ca77c](https://bsd-hardware.info/?probe=3cf20ca77c) | Oct 19, 2021 |
| Dell          | 0VRWRC A00                  | Desktop     | [9b4defb194](https://bsd-hardware.info/?probe=9b4defb194) | Oct 19, 2021 |
| HP            | Unknown                     | Notebook    | [ad95186d17](https://bsd-hardware.info/?probe=ad95186d17) | Oct 19, 2021 |
| Dell          | Studio 1747                 | Notebook    | [ca939fbe2f](https://bsd-hardware.info/?probe=ca939fbe2f) | Oct 19, 2021 |
| HP            | 3398                        | Desktop     | [892f19c9bd](https://bsd-hardware.info/?probe=892f19c9bd) | Oct 18, 2021 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [0cdd3497f6](https://bsd-hardware.info/?probe=0cdd3497f6) | Oct 18, 2021 |
| HP            | 15                          | Notebook    | [e3f26d7245](https://bsd-hardware.info/?probe=e3f26d7245) | Oct 18, 2021 |
| Gigabyte      | G41MT-S2                    | Desktop     | [2847d63db0](https://bsd-hardware.info/?probe=2847d63db0) | Oct 18, 2021 |
| ASUSTek       | P5P43TD PRO                 | Desktop     | [2870e26de1](https://bsd-hardware.info/?probe=2870e26de1) | Oct 17, 2021 |
| Acidanther... | Mac-42FD25EABCABB274 iMa... | All in one  | [951eb91342](https://bsd-hardware.info/?probe=951eb91342) | Oct 17, 2021 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [48169f1d3c](https://bsd-hardware.info/?probe=48169f1d3c) | Oct 16, 2021 |
| Intel         | NUC8BEB J72688-308          | Mini pc     | [f2f7fc6463](https://bsd-hardware.info/?probe=f2f7fc6463) | Oct 15, 2021 |
| Lenovo        | SHARKBAY No DPK             | Desktop     | [14dcd924b5](https://bsd-hardware.info/?probe=14dcd924b5) | Oct 13, 2021 |
| Lenovo        | ThinkPad L440 20ASS0FP00    | Notebook    | [d92e6e3c21](https://bsd-hardware.info/?probe=d92e6e3c21) | Oct 11, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [abf8bb08a6](https://bsd-hardware.info/?probe=abf8bb08a6) | Oct 11, 2021 |
| ASUSTek       | U33Jc                       | Notebook    | [07f11b6604](https://bsd-hardware.info/?probe=07f11b6604) | Oct 10, 2021 |
| Medion        | H61H2-LM3                   | Desktop     | [67ed0f639c](https://bsd-hardware.info/?probe=67ed0f639c) | Oct 10, 2021 |
| MSI           | MS-16F1                     | Notebook    | [72b9db306a](https://bsd-hardware.info/?probe=72b9db306a) | Oct 09, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [e24f67a603](https://bsd-hardware.info/?probe=e24f67a603) | Oct 08, 2021 |
| Lenovo        | S20-30 Touch 20434          | Notebook    | [141a393d54](https://bsd-hardware.info/?probe=141a393d54) | Oct 08, 2021 |
| MSI           | G41M-P25                    | Desktop     | [21eec496b4](https://bsd-hardware.info/?probe=21eec496b4) | Oct 08, 2021 |
| Lenovo        | ThinkPad X250 20CLS2A11K    | Notebook    | [e47f4113bf](https://bsd-hardware.info/?probe=e47f4113bf) | Oct 08, 2021 |
| ASRock        | A320M-DGS                   | Desktop     | [11cf5c923a](https://bsd-hardware.info/?probe=11cf5c923a) | Oct 08, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [d09f63f257](https://bsd-hardware.info/?probe=d09f63f257) | Oct 07, 2021 |
| Acer          | Aspire 5741                 | Notebook    | [fd4e40a8d9](https://bsd-hardware.info/?probe=fd4e40a8d9) | Oct 07, 2021 |
| Intel         | H61                         | Desktop     | [6ce71c1b9e](https://bsd-hardware.info/?probe=6ce71c1b9e) | Oct 06, 2021 |
| Lenovo        | ThinkPad R500 2718W92       | Notebook    | [384f10861a](https://bsd-hardware.info/?probe=384f10861a) | Oct 05, 2021 |
| ASUSTek       | UX21A                       | Notebook    | [fe08d28d4c](https://bsd-hardware.info/?probe=fe08d28d4c) | Oct 05, 2021 |
| Itautec       | Infoway w7530               | Notebook    | [a376201681](https://bsd-hardware.info/?probe=a376201681) | Oct 05, 2021 |
| HP            | 3397                        | Desktop     | [4c71aae5bf](https://bsd-hardware.info/?probe=4c71aae5bf) | Oct 05, 2021 |
| HP            | 81BA                        | All in one  | [c2204a3dd2](https://bsd-hardware.info/?probe=c2204a3dd2) | Oct 04, 2021 |
| ASRock        | B365M-ITX/ac                | Desktop     | [1c8820a6d0](https://bsd-hardware.info/?probe=1c8820a6d0) | Oct 04, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f02ef8c047](https://bsd-hardware.info/?probe=f02ef8c047) | Oct 04, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [43388a27a4](https://bsd-hardware.info/?probe=43388a27a4) | Oct 04, 2021 |
| Dell          | Latitude E4300              | Notebook    | [fdb3de3036](https://bsd-hardware.info/?probe=fdb3de3036) | Oct 03, 2021 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [bd312d1c88](https://bsd-hardware.info/?probe=bd312d1c88) | Oct 03, 2021 |
| HP            | ProLiant ML350 G5           | Desktop     | [4d525cba3e](https://bsd-hardware.info/?probe=4d525cba3e) | Oct 03, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [748b6d14f4](https://bsd-hardware.info/?probe=748b6d14f4) | Oct 02, 2021 |
| Toshiba       | dynabook RX3 SM240E/3HD     | Notebook    | [2fe863dff4](https://bsd-hardware.info/?probe=2fe863dff4) | Oct 01, 2021 |
| Toshiba       | Satellite S55t-B            | Notebook    | [445fe665b8](https://bsd-hardware.info/?probe=445fe665b8) | Oct 01, 2021 |
| HP            | Pavilion dm4                | Notebook    | [bb5a564a50](https://bsd-hardware.info/?probe=bb5a564a50) | Sep 30, 2021 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [9b14548c15](https://bsd-hardware.info/?probe=9b14548c15) | Sep 21, 2021 |
| Sapphire      | EDGE-FT1M1 E450 1AOVU044    | Desktop     | [ea8fefdf4e](https://bsd-hardware.info/?probe=ea8fefdf4e) | Sep 20, 2021 |
| Dell          | 0MGK50 A02                  | Desktop     | [9d2959b4f1](https://bsd-hardware.info/?probe=9d2959b4f1) | Sep 20, 2021 |
| HP            | 81B4 01                     | Desktop     | [179504116d](https://bsd-hardware.info/?probe=179504116d) | Sep 20, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [790d020ebe](https://bsd-hardware.info/?probe=790d020ebe) | Sep 19, 2021 |
| Lenovo        | G500s 20245                 | Notebook    | [88cd1ca7bd](https://bsd-hardware.info/?probe=88cd1ca7bd) | Sep 18, 2021 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [9b046b157e](https://bsd-hardware.info/?probe=9b046b157e) | Sep 17, 2021 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [0f6e7e26fc](https://bsd-hardware.info/?probe=0f6e7e26fc) | Sep 11, 2021 |
| HP            | 3397                        | Desktop     | [5d95b75768](https://bsd-hardware.info/?probe=5d95b75768) | Sep 06, 2021 |
| Kraftway      | KW10T                       | Notebook    | [4810842d82](https://bsd-hardware.info/?probe=4810842d82) | Sep 06, 2021 |
| Medion        | H61H2-LM3                   | Desktop     | [eb81abe401](https://bsd-hardware.info/?probe=eb81abe401) | Sep 02, 2021 |
| ASRock        | Z390 Pro4                   | Desktop     | [ecbf097bc5](https://bsd-hardware.info/?probe=ecbf097bc5) | Sep 02, 2021 |
| Dell          | Latitude 3540               | Notebook    | [2583b22e8d](https://bsd-hardware.info/?probe=2583b22e8d) | Aug 29, 2021 |
| Dell          | Latitude 3540               | Notebook    | [de97e0b2fc](https://bsd-hardware.info/?probe=de97e0b2fc) | Aug 29, 2021 |
| ASUSTek       | TUF B360M-PLUS GAMING S     | Desktop     | [33ba0b7c38](https://bsd-hardware.info/?probe=33ba0b7c38) | Aug 29, 2021 |
| Itautec       | Infoway w7530               | Notebook    | [d91ec24ce0](https://bsd-hardware.info/?probe=d91ec24ce0) | Aug 29, 2021 |
| Toshiba       | Satellite S55t-B            | Notebook    | [5aaacec4ad](https://bsd-hardware.info/?probe=5aaacec4ad) | Aug 23, 2021 |
| Toshiba       | Satellite S55t-B            | Notebook    | [d74035a8e7](https://bsd-hardware.info/?probe=d74035a8e7) | Aug 23, 2021 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [5fe1a9e521](https://bsd-hardware.info/?probe=5fe1a9e521) | Aug 16, 2021 |
| ASUSTek       | Q505UAR                     | Convertible | [b745dee7d6](https://bsd-hardware.info/?probe=b745dee7d6) | Aug 14, 2021 |
| Lenovo        | ThinkPad X230 23062S2       | Notebook    | [bceadf5c66](https://bsd-hardware.info/?probe=bceadf5c66) | Aug 05, 2021 |
| PCPartner     | MILANO-P Rev.00             | Desktop     | [ef8217ac30](https://bsd-hardware.info/?probe=ef8217ac30) | Aug 01, 2021 |
| Intel         | NUC5i3RYB K23918-501        | Mini pc     | [1c3ec31075](https://bsd-hardware.info/?probe=1c3ec31075) | Jul 28, 2021 |
| Lenovo        | ThinkPad SL 2746M3C         | Notebook    | [aa10433581](https://bsd-hardware.info/?probe=aa10433581) | Jul 28, 2021 |
| ASUSTek       | H110M-PLUS                  | Desktop     | [d0f2da9c41](https://bsd-hardware.info/?probe=d0f2da9c41) | Jul 21, 2021 |
| Lenovo        | ThinkPad X230 2325IG2       | Notebook    | [158ecc5e0b](https://bsd-hardware.info/?probe=158ecc5e0b) | Jul 14, 2021 |
| Gigabyte      | H110-D3A-CF                 | Desktop     | [2c390b4301](https://bsd-hardware.info/?probe=2c390b4301) | Jul 09, 2021 |
| Gigabyte      | H110-D3A-CF                 | Desktop     | [aea3a11daf](https://bsd-hardware.info/?probe=aea3a11daf) | Jul 08, 2021 |
| eMachines     | eM350                       | Notebook    | [94579b896e](https://bsd-hardware.info/?probe=94579b896e) | Jul 04, 2021 |
| eMachines     | eM350                       | Notebook    | [c268dd82de](https://bsd-hardware.info/?probe=c268dd82de) | Jul 04, 2021 |
| Lenovo        | B590 62743PG                | Notebook    | [2400297995](https://bsd-hardware.info/?probe=2400297995) | Jul 03, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [6cf3337855](https://bsd-hardware.info/?probe=6cf3337855) | Jul 01, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [e7a0dfcecf](https://bsd-hardware.info/?probe=e7a0dfcecf) | Jun 28, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [ceb18e38a3](https://bsd-hardware.info/?probe=ceb18e38a3) | Jun 28, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [1a35d2f6ab](https://bsd-hardware.info/?probe=1a35d2f6ab) | Jun 26, 2021 |
| eMachines     | eM350                       | Notebook    | [52198cfd80](https://bsd-hardware.info/?probe=52198cfd80) | Jun 22, 2021 |
| eMachines     | eM350                       | Notebook    | [60b4338ace](https://bsd-hardware.info/?probe=60b4338ace) | Jun 22, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [bb13e61de1](https://bsd-hardware.info/?probe=bb13e61de1) | Jun 21, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [0e448af5f5](https://bsd-hardware.info/?probe=0e448af5f5) | Jun 18, 2021 |
| Dell          | Latitude 7280               | Notebook    | [8fd335f46f](https://bsd-hardware.info/?probe=8fd335f46f) | Jun 18, 2021 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [b0b67667d3](https://bsd-hardware.info/?probe=b0b67667d3) | Jun 16, 2021 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 81        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 80        | 97.56%  |
| XFCE         | 1         | 1.22%   |
| GNOME        | 1         | 1.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 81        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| SLiM | 81        | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 79        | 97.53%  |
| ru_RU   | 1         | 1.23%   |
| Unknown | 1         | 1.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 67        | 82.72%  |
| BIOS | 14        | 17.28%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 81        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 81        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 15        | 18.52%  |
| ASUSTek Computer    | 13        | 16.05%  |
| Hewlett-Packard     | 9         | 11.11%  |
| Dell                | 9         | 11.11%  |
| ASRock              | 6         | 7.41%   |
| Gigabyte Technology | 5         | 6.17%   |
| MSI                 | 4         | 4.94%   |
| Intel               | 3         | 3.7%    |
| Apple               | 3         | 3.7%    |
| Toshiba             | 2         | 2.47%   |
| Acer                | 2         | 2.47%   |
| Sony                | 1         | 1.23%   |
| Sapphire            | 1         | 1.23%   |
| PCPartner           | 1         | 1.23%   |
| Medion              | 1         | 1.23%   |
| Kraftway            | 1         | 1.23%   |
| Itautec             | 1         | 1.23%   |
| eMachines           | 1         | 1.23%   |
| Chuwi               | 1         | 1.23%   |
| Acidanthera         | 1         | 1.23%   |
| Unknown             | 1         | 1.23%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 2         | 2.47%   |
| Toshiba Satellite S55t-B                   | 1         | 1.23%   |
| Toshiba dynabook RX3 SM240E/3HD            | 1         | 1.23%   |
| Sony SVS1511AJB                            | 1         | 1.23%   |
| Sapphire EDGE-FT1M1 E450 1AOVU044          | 1         | 1.23%   |
| PCPartner DREAMSYS                         | 1         | 1.23%   |
| MSI MS-7B93                                | 1         | 1.23%   |
| MSI MS-7A40                                | 1         | 1.23%   |
| MSI MS-7592                                | 1         | 1.23%   |
| MSI MS-16F1                                | 1         | 1.23%   |
| Medion H61H2-LM3                           | 1         | 1.23%   |
| Lenovo Yoga 3 Pro-1370 80HE                | 1         | 1.23%   |
| Lenovo ThinkPad Yoga 11e 20DAS0AE00        | 1         | 1.23%   |
| Lenovo ThinkPad X250 20CLS2A11K            | 1         | 1.23%   |
| Lenovo ThinkPad X230 2325IG2               | 1         | 1.23%   |
| Lenovo ThinkPad X230 23062S2               | 1         | 1.23%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWA003CD | 1         | 1.23%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A70066UK   | 1         | 1.23%   |
| Lenovo ThinkPad SL 2746M3C                 | 1         | 1.23%   |
| Lenovo ThinkPad R500 2718W92               | 1         | 1.23%   |
| Lenovo ThinkPad L440 20ASS0FP00            | 1         | 1.23%   |
| Lenovo ThinkCentre M83 10AHS35Q00          | 1         | 1.23%   |
| Lenovo S20-30 Touch 20434                  | 1         | 1.23%   |
| Lenovo IdeaPad S145-15IWL 81MV             | 1         | 1.23%   |
| Lenovo G500s 20245                         | 1         | 1.23%   |
| Lenovo B590 62743PG                        | 1         | 1.23%   |
| Kraftway KW10T                             | 1         | 1.23%   |
| Itautec Infoway w7530                      | 1         | 1.23%   |
| Intel NUC8i7BEH                            | 1         | 1.23%   |
| Intel NUC5i3RYH                            | 1         | 1.23%   |
| Intel H61                                  | 1         | 1.23%   |
| HP ProLiant ML350 G5                       | 1         | 1.23%   |
| HP Presario CQ43                           | 1         | 1.23%   |
| HP Pavilion dm4                            | 1         | 1.23%   |
| HP Compaq Elite 8300 USDT                  | 1         | 1.23%   |
| HP Compaq Elite 8300 SFF                   | 1         | 1.23%   |
| HP 260-p026                                | 1         | 1.23%   |
| HP 24-g038ur                               | 1         | 1.23%   |
| HP 15                                      | 1         | 1.23%   |
| Gigabyte H410M S2 V2                       | 1         | 1.23%   |
| Gigabyte H270M-DS3H                        | 1         | 1.23%   |
| Gigabyte G41MT-S2                          | 1         | 1.23%   |
| Gigabyte B450 AORUS M                      | 1         | 1.23%   |
| Gigabyte 990FXA-UD3                        | 1         | 1.23%   |
| eMachines eM350                            | 1         | 1.23%   |
| Dell Studio 1747                           | 1         | 1.23%   |
| Dell Precision M4600                       | 1         | 1.23%   |
| Dell OptiPlex 3040                         | 1         | 1.23%   |
| Dell OptiPlex 3020M                        | 1         | 1.23%   |
| Dell Latitude E4300                        | 1         | 1.23%   |
| Dell Latitude 7280                         | 1         | 1.23%   |
| Dell Latitude 3540                         | 1         | 1.23%   |
| Dell Inspiron 3542                         | 1         | 1.23%   |
| Dell Inspiron 3521                         | 1         | 1.23%   |
| Chuwi MiniBook                             | 1         | 1.23%   |
| ASUS UX21A                                 | 1         | 1.23%   |
| ASUS U33Jc                                 | 1         | 1.23%   |
| ASUS TUF GAMING X570-PLUS                  | 1         | 1.23%   |
| ASUS TUF B450M-PRO GAMING                  | 1         | 1.23%   |
| ASUS TUF B360M-PLUS GAMING S               | 1         | 1.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 9         | 11.11%  |
| Dell Latitude       | 3         | 3.7%    |
| ASUS TUF            | 3         | 3.7%    |
| HP Compaq           | 2         | 2.47%   |
| Dell OptiPlex       | 2         | 2.47%   |
| Dell Inspiron       | 2         | 2.47%   |
| Unknown             | 2         | 2.47%   |
| Toshiba Satellite   | 1         | 1.23%   |
| Toshiba dynabook    | 1         | 1.23%   |
| Sony SVS1511AJB     | 1         | 1.23%   |
| Sapphire EDGE-FT1M1 | 1         | 1.23%   |
| PCPartner DREAMSYS  | 1         | 1.23%   |
| MSI MS-7B93         | 1         | 1.23%   |
| MSI MS-7A40         | 1         | 1.23%   |
| MSI MS-7592         | 1         | 1.23%   |
| MSI MS-16F1         | 1         | 1.23%   |
| Medion H61H2-LM3    | 1         | 1.23%   |
| Lenovo Yoga         | 1         | 1.23%   |
| Lenovo ThinkCentre  | 1         | 1.23%   |
| Lenovo S20-30       | 1         | 1.23%   |
| Lenovo IdeaPad      | 1         | 1.23%   |
| Lenovo G500s        | 1         | 1.23%   |
| Lenovo B590         | 1         | 1.23%   |
| Kraftway KW10T      | 1         | 1.23%   |
| Itautec Infoway     | 1         | 1.23%   |
| Intel NUC8i7BEH     | 1         | 1.23%   |
| Intel NUC5i3RYH     | 1         | 1.23%   |
| Intel H61           | 1         | 1.23%   |
| HP ProLiant         | 1         | 1.23%   |
| HP Presario         | 1         | 1.23%   |
| HP Pavilion         | 1         | 1.23%   |
| HP 260-p026         | 1         | 1.23%   |
| HP 24-g038ur        | 1         | 1.23%   |
| HP 15               | 1         | 1.23%   |
| Gigabyte H410M      | 1         | 1.23%   |
| Gigabyte H270M-DS3H | 1         | 1.23%   |
| Gigabyte G41MT-S2   | 1         | 1.23%   |
| Gigabyte B450       | 1         | 1.23%   |
| Gigabyte 990FXA-UD3 | 1         | 1.23%   |
| eMachines eM350     | 1         | 1.23%   |
| Dell Studio         | 1         | 1.23%   |
| Dell Precision      | 1         | 1.23%   |
| Chuwi MiniBook      | 1         | 1.23%   |
| ASUS UX21A          | 1         | 1.23%   |
| ASUS U33Jc          | 1         | 1.23%   |
| ASUS Q505UAR        | 1         | 1.23%   |
| ASUS P7H55-M        | 1         | 1.23%   |
| ASUS P5P43TD        | 1         | 1.23%   |
| ASUS M5A97          | 1         | 1.23%   |
| ASUS H110M-PLUS     | 1         | 1.23%   |
| ASUS exone          | 1         | 1.23%   |
| ASUS CROSSHAIR      | 1         | 1.23%   |
| ASUS All            | 1         | 1.23%   |
| ASRock Z390         | 1         | 1.23%   |
| ASRock X570         | 1         | 1.23%   |
| ASRock X300M-STX    | 1         | 1.23%   |
| ASRock B450         | 1         | 1.23%   |
| ASRock B365M-ITX    | 1         | 1.23%   |
| ASRock A320M-DGS    | 1         | 1.23%   |
| Apple MacPro5       | 1         | 1.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 12        | 14.81%  |
| 2021 | 11        | 13.58%  |
| 2020 | 9         | 11.11%  |
| 2011 | 8         | 9.88%   |
| 2018 | 6         | 7.41%   |
| 2012 | 6         | 7.41%   |
| 2010 | 6         | 7.41%   |
| 2015 | 5         | 6.17%   |
| 2014 | 5         | 6.17%   |
| 2013 | 4         | 4.94%   |
| 2017 | 3         | 3.7%    |
| 2016 | 3         | 3.7%    |
| 2009 | 2         | 2.47%   |
| 2008 | 1         | 1.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 38        | 46.91%  |
| Notebook    | 38        | 46.91%  |
| Mini pc     | 2         | 2.47%   |
| All in one  | 2         | 2.47%   |
| Convertible | 1         | 1.23%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 81        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 28        | 34.57%  |
| 4.01-8.0    | 24        | 29.63%  |
| 16.01-24.0  | 18        | 22.22%  |
| 32.01-64.0  | 7         | 8.64%   |
| 64.01-256.0 | 3         | 3.7%    |
| 2.01-3.0    | 1         | 1.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 44        | 54.32%  |
| 0.51-1.0 | 29        | 35.8%   |
| 1.01-2.0 | 7         | 8.64%   |
| 3.01-4.0 | 1         | 1.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 53        | 64.63%  |
| 2      | 12        | 14.63%  |
| 3      | 9         | 10.98%  |
| 4      | 5         | 6.1%    |
| 0      | 2         | 2.44%   |
| 5      | 1         | 1.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 47        | 58.02%  |
| Yes       | 34        | 41.98%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 74        | 91.36%  |
| No        | 7         | 8.64%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 55        | 67.9%   |
| No        | 26        | 32.1%   |

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


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Russia      | 11        | 13.58%  |
| USA         | 9         | 11.11%  |
| Germany     | 5         | 6.17%   |
| China       | 5         | 6.17%   |
| Brazil      | 5         | 6.17%   |
| Spain       | 4         | 4.94%   |
| Ukraine     | 3         | 3.7%    |
| UK          | 3         | 3.7%    |
| South Korea | 3         | 3.7%    |
| Mexico      | 3         | 3.7%    |
| Italy       | 3         | 3.7%    |
| Canada      | 3         | 3.7%    |
| New Zealand | 2         | 2.47%   |
| Netherlands | 2         | 2.47%   |
| Chile       | 2         | 2.47%   |
| Venezuela   | 1         | 1.23%   |
| Turkey      | 1         | 1.23%   |
| Thailand    | 1         | 1.23%   |
| Syria       | 1         | 1.23%   |
| Switzerland | 1         | 1.23%   |
| Poland      | 1         | 1.23%   |
| Peru        | 1         | 1.23%   |
| Lithuania   | 1         | 1.23%   |
| Libya       | 1         | 1.23%   |
| Japan       | 1         | 1.23%   |
| India       | 1         | 1.23%   |
| Hungary     | 1         | 1.23%   |
| Hong Kong   | 1         | 1.23%   |
| Guatemala   | 1         | 1.23%   |
| Greece      | 1         | 1.23%   |
| Denmark     | 1         | 1.23%   |
| Czechia     | 1         | 1.23%   |
| Australia   | 1         | 1.23%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Santiago           | 2         | 2.44%   |
| Marlborough        | 2         | 2.44%   |
| Guangzhou          | 2         | 2.44%   |
| Barcelona          | 2         | 2.44%   |
| Yeongdong-gun      | 1         | 1.22%   |
| Yekaterinburg      | 1         | 1.22%   |
| Xiamen             | 1         | 1.22%   |
| Wellington         | 1         | 1.22%   |
| Voronezh           | 1         | 1.22%   |
| Ufa                | 1         | 1.22%   |
| Tyumen             | 1         | 1.22%   |
| Tula de Allende    | 1         | 1.22%   |
| Tripoli            | 1         | 1.22%   |
| Torre del Mar      | 1         | 1.22%   |
| The Hague          | 1         | 1.22%   |
| Tampa              | 1         | 1.22%   |
| Taito              | 1         | 1.22%   |
| Stuttgart          | 1         | 1.22%   |
| St Petersburg      | 1         | 1.22%   |
| Sherwood Park      | 1         | 1.22%   |
| Shepetivka         | 1         | 1.22%   |
| Seoul              | 1         | 1.22%   |
| Seattle            | 1         | 1.22%   |
| Rostov-on-Don      | 1         | 1.22%   |
| Rio de Janeiro     | 1         | 1.22%   |
| Riehen             | 1         | 1.22%   |
| Richmond           | 1         | 1.22%   |
| Reriutaba          | 1         | 1.22%   |
| Redmond            | 1         | 1.22%   |
| Qingdao            | 1         | 1.22%   |
| Pistoia            | 1         | 1.22%   |
| Pilsen             | 1         | 1.22%   |
| Olympia            | 1         | 1.22%   |
| Odessa             | 1         | 1.22%   |
| Obninsk            | 1         | 1.22%   |
| Nughedu San Nicolo | 1         | 1.22%   |
| Nieuwegein         | 1         | 1.22%   |
| Newtownabbey       | 1         | 1.22%   |
| New Plymouth       | 1         | 1.22%   |
| Moscow             | 1         | 1.22%   |
| Monterrey          | 1         | 1.22%   |
| Monte Belo         | 1         | 1.22%   |
| Mission            | 1         | 1.22%   |
| Maracaibo          | 1         | 1.22%   |
| Lima               | 1         | 1.22%   |
| La Paz             | 1         | 1.22%   |
| Kyiv               | 1         | 1.22%   |
| Krasnodar          | 1         | 1.22%   |
| Kosekoy            | 1         | 1.22%   |
| Kaunas             | 1         | 1.22%   |
| Katowice           | 1         | 1.22%   |
| Irkutsk            | 1         | 1.22%   |
| Ipojuca            | 1         | 1.22%   |
| Inhapim            | 1         | 1.22%   |
| Hong Kong          | 1         | 1.22%   |
| Hicksville         | 1         | 1.22%   |
| Heidelberg         | 1         | 1.22%   |
| Gy?�r              | 1         | 1.22%   |
| Gwangyang          | 1         | 1.22%   |
| Guatemala City     | 1         | 1.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 22        | 27     | 19.82%  |
| WDC                 | 19        | 23     | 17.12%  |
| Samsung Electronics | 14        | 16     | 12.61%  |
| Toshiba             | 8         | 11     | 7.21%   |
| Hitachi             | 5         | 6      | 4.5%    |
| SanDisk             | 4         | 4      | 3.6%    |
| Kingston            | 4         | 7      | 3.6%    |
| Crucial             | 4         | 6      | 3.6%    |
| A-DATA Technology   | 3         | 5      | 2.7%    |
| SPCC                | 2         | 2      | 1.8%    |
| Smartbuy            | 2         | 2      | 1.8%    |
| PLEXTOR             | 2         | 2      | 1.8%    |
| Intel               | 2         | 2      | 1.8%    |
| HGST                | 2         | 2      | 1.8%    |
| Corsair             | 2         | 2      | 1.8%    |
| China               | 2         | 2      | 1.8%    |
| Apacer              | 2         | 2      | 1.8%    |
| Verbatim            | 1         | 1      | 0.9%    |
| Patriot             | 1         | 1      | 0.9%    |
| OCZ                 | 1         | 1      | 0.9%    |
| LITEONIT            | 1         | 1      | 0.9%    |
| LITEON              | 1         | 1      | 0.9%    |
| Lexar               | 1         | 1      | 0.9%    |
| Leven               | 1         | 1      | 0.9%    |
| Hewlett-Packard     | 1         | 1      | 0.9%    |
| Gigabyte Technology | 1         | 1      | 0.9%    |
| FORESEE             | 1         | 1      | 0.9%    |
| Apple               | 1         | 1      | 0.9%    |
| AMD                 | 1         | 1      | 0.9%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST9500325AS 500GB           | 3         | 2.38%   |
| WDC WDS100T2B0C-00PXH0 1TB          | 2         | 1.59%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 2         | 1.59%   |
| Toshiba MQ01ABF050 500GB            | 2         | 1.59%   |
| Toshiba DT01ACA100 1TB              | 2         | 1.59%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 2         | 1.59%   |
| SanDisk SDSSDA240G 240GB            | 2         | 1.59%   |
| Samsung SSD 860 EVO 500GB           | 2         | 1.59%   |
| Samsung SSD 850 EVO 250GB           | 2         | 1.59%   |
| Samsung HD322HJ 320GB               | 2         | 1.59%   |
| China SATA SSD 120GB                | 2         | 1.59%   |
| WDC WDS250G2X0C-00L350 250GB        | 1         | 0.79%   |
| WDC WD5000LPCX-00VHAT0 500GB        | 1         | 0.79%   |
| WDC WD5000BEKT-60KA9T0 500GB        | 1         | 0.79%   |
| WDC WD5000AAVS-00ZTB0 500GB         | 1         | 0.79%   |
| WDC WD5000AAKS-00V1A0 500GB         | 1         | 0.79%   |
| WDC WD40EZRZ-22GXCB0 4TB            | 1         | 0.79%   |
| WDC WD3200BEVT-80A0RT0 320GB        | 1         | 0.79%   |
| WDC WD3200AAKS-00UU3A0 320GB        | 1         | 0.79%   |
| WDC WD30EZRZ-00WN9B0 3TB            | 1         | 0.79%   |
| WDC WD3003FZEX-00Z4SA0 3TB          | 1         | 0.79%   |
| WDC WD2500BEVS-08VAT2 250GB         | 1         | 0.79%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 1         | 0.79%   |
| WDC WD1600AAJS-00WAA0 160GB         | 1         | 0.79%   |
| WDC WD1600AAJS-00V4A0 160GB         | 1         | 0.79%   |
| WDC WD10SPZX-22Z10T0 1TB            | 1         | 0.79%   |
| WDC WD10JMVW-11AJGS0 1TB            | 1         | 0.79%   |
| WDC WD10EZRX-00A8LB0 1TB            | 1         | 0.79%   |
| WDC WD10EZEX-75WN4A1 1TB            | 1         | 0.79%   |
| WDC WD1002FAEX-00Y9A0 1TB           | 1         | 0.79%   |
| Verbatim Vi550 S3 SSD 256GB         | 1         | 0.79%   |
| Toshiba MQ02ABD100H 1TB             | 1         | 0.79%   |
| Toshiba MQ01UBD100 1TB              | 1         | 0.79%   |
| Toshiba MQ01ABD100 1TB              | 1         | 0.79%   |
| Toshiba MK5061GSYN 500GB            | 1         | 0.79%   |
| Toshiba DT01ACA050 500GB            | 1         | 0.79%   |
| SPCC Solid State Disk 1TB           | 1         | 0.79%   |
| SPCC M.2 PCIe SSD 256GB             | 1         | 0.79%   |
| Smartbuy SSD 240GB                  | 1         | 0.79%   |
| Smartbuy SSD 120GB                  | 1         | 0.79%   |
| Seagate ST9320325AS 320GB           | 1         | 0.79%   |
| Seagate ST9160412ASG 160GB          | 1         | 0.79%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 0.79%   |
| Seagate ST500LT012-1DG142 500GB     | 1         | 0.79%   |
| Seagate ST500LM021-1KJ152 500GB     | 1         | 0.79%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 0.79%   |
| Seagate ST500LM000-1EJ162 500GB     | 1         | 0.79%   |
| Seagate ST500DM002-1SB10A 500GB     | 1         | 0.79%   |
| Seagate ST4000DM004-2CV104 4TB      | 1         | 0.79%   |
| Seagate ST3500413AS 500GB           | 1         | 0.79%   |
| Seagate ST3500312CS 500GB           | 1         | 0.79%   |
| Seagate ST3250318AS 250GB           | 1         | 0.79%   |
| Seagate ST3160813AS 160GB           | 1         | 0.79%   |
| Seagate ST31000524AS 1TB            | 1         | 0.79%   |
| Seagate ST3000DM001-1CH166 3TB      | 1         | 0.79%   |
| Seagate ST2000DX001-1CM164 2TB      | 1         | 0.79%   |
| Seagate ST2000DL003-9VT166 2TB      | 1         | 0.79%   |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 0.79%   |
| Seagate ST1000LM014-1EJ164 1TB      | 1         | 0.79%   |
| Seagate ST1000DM010-2EP102 1TB      | 1         | 0.79%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 22        | 27     | 38.6%   |
| WDC                 | 17        | 20     | 29.82%  |
| Toshiba             | 8         | 11     | 14.04%  |
| Hitachi             | 5         | 6      | 8.77%   |
| Samsung Electronics | 2         | 3      | 3.51%   |
| HGST                | 2         | 2      | 3.51%   |
| Hewlett-Packard     | 1         | 1      | 1.75%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 9      | 20.45%  |
| SanDisk             | 4         | 4      | 9.09%   |
| Kingston            | 4         | 7      | 9.09%   |
| Crucial             | 4         | 6      | 9.09%   |
| Smartbuy            | 2         | 2      | 4.55%   |
| PLEXTOR             | 2         | 2      | 4.55%   |
| Intel               | 2         | 2      | 4.55%   |
| China               | 2         | 2      | 4.55%   |
| Apacer              | 2         | 2      | 4.55%   |
| Verbatim            | 1         | 1      | 2.27%   |
| SPCC                | 1         | 1      | 2.27%   |
| Patriot             | 1         | 1      | 2.27%   |
| OCZ                 | 1         | 1      | 2.27%   |
| LITEONIT            | 1         | 1      | 2.27%   |
| LITEON              | 1         | 1      | 2.27%   |
| Lexar               | 1         | 1      | 2.27%   |
| Leven               | 1         | 1      | 2.27%   |
| FORESEE             | 1         | 1      | 2.27%   |
| Corsair             | 1         | 1      | 2.27%   |
| Apple               | 1         | 1      | 2.27%   |
| AMD                 | 1         | 1      | 2.27%   |
| A-DATA Technology   | 1         | 2      | 2.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 45        | 70     | 46.88%  |
| SSD  | 39        | 50     | 40.63%  |
| NVMe | 12        | 13     | 12.5%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 74        | 120    | 86.05%  |
| NVMe | 12        | 13     | 13.95%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 65        | 84     | 67.01%  |
| 0.51-1.0   | 22        | 24     | 22.68%  |
| 1.01-2.0   | 5         | 5      | 5.15%   |
| 2.01-3.0   | 3         | 5      | 3.09%   |
| 3.01-4.0   | 2         | 2      | 2.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 49        | 59.04%  |
| 101-250    | 19        | 22.89%  |
| 251-500    | 10        | 12.05%  |
| 501-1000   | 3         | 3.61%   |
| 21-50      | 1         | 1.2%    |
| 51-100     | 1         | 1.2%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 81        | 100%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Samsung Electronics HD322HJ 320GB   | 2         | 2      | 9.52%   |
| WDC WD5000AAKS-00V1A0 500GB         | 1         | 1      | 4.76%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 1         | 1      | 4.76%   |
| WDC WD3200BEVT-80A0RT0 320GB        | 1         | 1      | 4.76%   |
| WDC WD3200AAKS-00UU3A0 320GB        | 1         | 1      | 4.76%   |
| WDC WD10JMVW-11AJGS0 1TB            | 1         | 1      | 4.76%   |
| Toshiba MQ01UBD100 1TB              | 1         | 1      | 4.76%   |
| Toshiba MQ01ABF050 500GB            | 1         | 2      | 4.76%   |
| Toshiba MK5061GSYN 500GB            | 1         | 1      | 4.76%   |
| Toshiba DT01ACA100 1TB              | 1         | 2      | 4.76%   |
| Seagate ST9500325AS 500GB           | 1         | 1      | 4.76%   |
| Seagate ST9320325AS 320GB           | 1         | 1      | 4.76%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 1      | 4.76%   |
| Seagate ST500LM021-1KJ152 500GB     | 1         | 1      | 4.76%   |
| Seagate ST3500413AS 500GB           | 1         | 1      | 4.76%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1         | 1      | 4.76%   |
| SanDisk SDSSDA240G 240GB            | 1         | 1      | 4.76%   |
| Samsung Electronics HD161HJ 160GB   | 1         | 1      | 4.76%   |
| Hitachi HTS541080G9SA00 80GB        | 1         | 1      | 4.76%   |
| HGST HTS541010A9E680 1TB            | 1         | 1      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 30%     |
| WDC                 | 5         | 5      | 25%     |
| Toshiba             | 4         | 6      | 20%     |
| Samsung Electronics | 2         | 3      | 10%     |
| SanDisk             | 1         | 1      | 5%      |
| Hitachi             | 1         | 1      | 5%      |
| HGST                | 1         | 1      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 31.58%  |
| WDC                 | 5         | 5      | 26.32%  |
| Toshiba             | 4         | 6      | 21.05%  |
| Samsung Electronics | 2         | 3      | 10.53%  |
| Hitachi             | 1         | 1      | 5.26%   |
| HGST                | 1         | 1      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 18        | 22     | 94.74%  |
| SSD  | 1         | 1      | 5.26%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart_bsd/drive_failed.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Hitachi HTS545025B9A300 250GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 69        | 108    | 76.67%  |
| Malfunc  | 19        | 23     | 21.11%  |
| Detected | 1         | 1      | 1.11%   |
| Failed   | 1         | 1      | 1.11%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 64        | 68.09%  |
| AMD                        | 13        | 13.83%  |
| Samsung Electronics        | 4         | 4.26%   |
| Sandisk                    | 3         | 3.19%   |
| Phison Electronics         | 3         | 3.19%   |
| ASMedia Technology         | 2         | 2.13%   |
| Realtek Semiconductor      | 1         | 1.06%   |
| Lite-On IT Corp. / Plextor | 1         | 1.06%   |
| JMicron Technology         | 1         | 1.06%   |
| Hewlett-Packard            | 1         | 1.06%   |
| ADATA Technology           | 1         | 1.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 9         | 8.57%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 7         | 6.67%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 3.81%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 4         | 3.81%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 3.81%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 3.81%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 4         | 3.81%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4         | 3.81%   |
| AMD 400 Series Chipset SATA Controller                                         | 4         | 3.81%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 2.86%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 2.86%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3         | 2.86%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 2.86%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 2.86%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3         | 2.86%   |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 2         | 1.9%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2         | 1.9%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 1.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2         | 1.9%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2         | 1.9%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2         | 1.9%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 2         | 1.9%    |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1         | 0.95%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 0.95%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 0.95%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1         | 0.95%   |
| Phison E12 NVMe Controller                                                     | 1         | 0.95%   |
| Lite-On IT Corp. / Plextor M6e PCI Express SSD [Marvell 88SS9183]              | 1         | 0.95%   |
| JMicron JMB361 AHCI/IDE                                                        | 1         | 0.95%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 0.95%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 0.95%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 0.95%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 1         | 0.95%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 1         | 0.95%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 1         | 0.95%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 1         | 0.95%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 1         | 0.95%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1         | 0.95%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]  | 1         | 0.95%   |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile     | 1         | 0.95%   |
| Intel 631xESB/632xESB IDE Controller                                           | 1         | 0.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 0.95%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 1         | 0.95%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 1         | 0.95%   |
| HP Smart Array E200i (SAS Controller)                                          | 1         | 0.95%   |
| HP Smart Array Controller                                                      | 1         | 0.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 1         | 0.95%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 1         | 0.95%   |
| AMD FCH SATA Controller D                                                      | 1         | 0.95%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 1         | 0.95%   |
| Unknown                                                                        | 1         | 0.95%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 67        | 73.63%  |
| NVMe | 12        | 13.19%  |
| IDE  | 8         | 8.79%   |
| RAID | 4         | 4.4%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 67        | 82.72%  |
| AMD    | 14        | 17.28%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel Core i5-4210U CPU @ 1.70GHz     | 2         | 2.47%   |
| Intel Core i3-6100T CPU @ 3.20GHz     | 2         | 2.47%   |
| Intel Core i3-3110M CPU @ 2.40GHz     | 2         | 2.47%   |
| AMD Ryzen 9 3900X 12-Core Processor   | 2         | 2.47%   |
| Intel Xeon CPU W3680 @ 3.33GHz        | 1         | 1.23%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz    | 1         | 1.23%   |
| Intel Xeon                            | 1         | 1.23%   |
| Intel Processor 5Y70 CPU @ 1.10GHz    | 1         | 1.23%   |
| Intel Pentium CPU N3530 @ 2.16GHz     | 1         | 1.23%   |
| Intel Pentium CPU G3420 @ 3.20GHz     | 1         | 1.23%   |
| Intel Pentium CPU 5405U @ 2.30GHz     | 1         | 1.23%   |
| Intel CPU Version                     | 1         | 1.23%   |
| Intel Core m3-8100Y CPU @ 1.10GHz     | 1         | 1.23%   |
| Intel Core i7-9700F CPU @ 3.00GHz     | 1         | 1.23%   |
| Intel Core i7-8700K CPU @ 3.70GHz     | 1         | 1.23%   |
| Intel Core i7-8559U CPU @ 2.70GHz     | 1         | 1.23%   |
| Intel Core i7-7700 CPU @ 3.60GHz      | 1         | 1.23%   |
| Intel Core i7-3770 CPU @ 3.40GHz      | 1         | 1.23%   |
| Intel Core i7-3632QM CPU @ 2.20GHz    | 1         | 1.23%   |
| Intel Core i7-3520M CPU @ 2.90GHz     | 1         | 1.23%   |
| Intel Core i7-3517U CPU @ 1.90GHz     | 1         | 1.23%   |
| Intel Core i7-2640M CPU @ 2.80GH      | 1         | 1.23%   |
| Intel Core i7-10700 CPU @ 2.90GHz     | 1         | 1.23%   |
| Intel Core i5-9600K CPU @ 3.70GHz     | 1         | 1.23%   |
| Intel Core i5-8250U CPU @ 1.60GHz     | 1         | 1.23%   |
| Intel Core i5-7500 CPU @ 3.40GHz      | 1         | 1.23%   |
| Intel Core i5-7300U CPU @ 2.60GHz     | 1         | 1.23%   |
| Intel Core i5-5300U CPU @ 2.30GHz     | 1         | 1.23%   |
| Intel Core i5-5200U CPU @ 2.20GHz     | 1         | 1.23%   |
| Intel Core i5-4570 CPU @ 3.20GHz      | 1         | 1.23%   |
| Intel Core i5-4460 CPU @ 3.20GHz      | 1         | 1.23%   |
| Intel Core i5-4300U CPU @ 1.90GHz     | 1         | 1.23%   |
| Intel Core i5-4300M CPU @ 2.60GHz     | 1         | 1.23%   |
| Intel Core i5-3317U CPU @ 1.70GHz     | 1         | 1.23%   |
| Intel Core i5-3230M CPU @ 2.60GHz     | 1         | 1.23%   |
| Intel Core i5-3210M CPU @ 2.50GHz     | 1         | 1.23%   |
| Intel Core i5-2320 CPU @ 3.00GHz      | 1         | 1.23%   |
| Intel Core i5 CPU M 520 @ 2.40GHz     | 1         | 1.23%   |
| Intel Core i5 CPU M 460 @ 2.53GHz     | 1         | 1.23%   |
| Intel Core i5 CPU M 450 @ 2.40GHz     | 1         | 1.23%   |
| Intel Core i5 CPU 661 @ 3.33GHz       | 1         | 1.23%   |
| Intel Core i3-8100 CPU @ 3.60GHz      | 1         | 1.23%   |
| Intel Core i3-6100U CPU @ 2.30GHz     | 1         | 1.23%   |
| Intel Core i3-5005U CPU @ 2.00GHz     | 1         | 1.23%   |
| Intel Core i3-4170 CPU @ 3.70GHz      | 1         | 1.23%   |
| Intel Core i3-4150T CPU @ 3.00GHz     | 1         | 1.23%   |
| Intel Core i3-4005U CPU @ 1.70GHz     | 1         | 1.23%   |
| Intel Core i3-3240 CPU @ 3.40GHz      | 1         | 1.23%   |
| Intel Core i3-3227U CPU @ 1.90GHz     | 1         | 1.23%   |
| Intel Core i3-2120 CPU @ 3.30GHz      | 1         | 1.23%   |
| Intel Core i3 CPU M 370 @ 2.40GH      | 1         | 1.23%   |
| Intel Core i3 CPU M 330 @ 2.13GHz     | 1         | 1.23%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz | 1         | 1.23%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz  | 1         | 1.23%   |
| Intel Core 2 Duo CPU T5870 @ 2.00GHz  | 1         | 1.23%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz  | 1         | 1.23%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz  | 1         | 1.23%   |
| Intel Core 2 Duo CPU                  | 1         | 1.23%   |
| Intel Core 2 Duo                      | 1         | 1.23%   |
| Intel Celeron CPU N2930 @ 1.83GHz     | 1         | 1.23%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i5     | 20        | 24.69%  |
| Intel Core i3     | 15        | 18.52%  |
| Intel Core i7     | 10        | 12.35%  |
| Intel Core 2 Duo  | 6         | 7.41%   |
| Other             | 3         | 3.7%    |
| Intel Xeon        | 3         | 3.7%    |
| Intel Pentium     | 3         | 3.7%    |
| Intel Celeron     | 3         | 3.7%    |
| AMD Ryzen 9       | 3         | 3.7%    |
| AMD FX            | 3         | 3.7%    |
| Intel Atom        | 2         | 2.47%   |
| AMD Ryzen 7       | 2         | 2.47%   |
| AMD Ryzen 5       | 2         | 2.47%   |
| Intel Core m3     | 1         | 1.23%   |
| Intel Core 2 Quad | 1         | 1.23%   |
| AMD Ryzen 5 PRO   | 1         | 1.23%   |
| AMD Ryzen 3       | 1         | 1.23%   |
| AMD Phenom II X6  | 1         | 1.23%   |
| AMD E             | 1         | 1.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 41        | 50.62%  |
| 4       | 17        | 20.99%  |
| 6       | 6         | 7.41%   |
| 8       | 4         | 4.94%   |
| Unknown | 4         | 4.94%   |
| 24      | 3         | 3.7%    |
| 12      | 3         | 3.7%    |
| 16      | 2         | 2.47%   |
| 1       | 1         | 1.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 79        | 97.53%  |
| 2      | 2         | 2.47%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 46        | 56.79%  |
| 1       | 31        | 38.27%  |
| Unknown | 4         | 4.94%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 11        | 13.58%  |
| IvyBridge   | 11        | 13.58%  |
| Haswell     | 10        | 12.35%  |
| Westmere    | 7         | 8.64%   |
| Penryn      | 7         | 8.64%   |
| SandyBridge | 6         | 7.41%   |
| Zen 2       | 4         | 4.94%   |
| Broadwell   | 4         | 4.94%   |
| Zen+        | 3         | 3.7%    |
| Skylake     | 3         | 3.7%    |
| Silvermont  | 3         | 3.7%    |
| Piledriver  | 2         | 2.47%   |
| Zen 3       | 1         | 1.23%   |
| Zen         | 1         | 1.23%   |
| TigerLake   | 1         | 1.23%   |
| Nehalem     | 1         | 1.23%   |
| K10         | 1         | 1.23%   |
| Core        | 1         | 1.23%   |
| CometLake   | 1         | 1.23%   |
| Bulldozer   | 1         | 1.23%   |
| Bonnell     | 1         | 1.23%   |
| Bobcat      | 1         | 1.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 46        | 52.87%  |
| Nvidia | 26        | 29.89%  |
| AMD    | 15        | 17.24%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                            | 9         | 10.34%  |
| Intel Haswell-ULT Integrated Graphics Controller                            | 4         | 4.6%    |
| Intel HD Graphics 5500                                                      | 3         | 3.45%   |
| Intel Core Processor Integrated Graphics Controller                         | 3         | 3.45%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 3         | 3.45%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3         | 3.45%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2         | 2.3%    |
| Nvidia GM206 [GeForce GTX 950]                                              | 2         | 2.3%    |
| Nvidia GK208B [GeForce GT 710]                                              | 2         | 2.3%    |
| Nvidia GF119 [GeForce GT 610]                                               | 2         | 2.3%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 2         | 2.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 2.3%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 2         | 2.3%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2         | 2.3%    |
| AMD Oland PRO [Radeon R7 240/340]                                           | 2         | 2.3%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2         | 2.3%    |
| Nvidia GT218M [GeForce 310M]                                                | 1         | 1.15%   |
| Nvidia GT215 [GeForce GT 220]                                               | 1         | 1.15%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1         | 1.15%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1         | 1.15%   |
| Nvidia GP104 [GeForce GTX 1060 3GB]                                         | 1         | 1.15%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1         | 1.15%   |
| Nvidia GK107M [GeForce GT 640M LE]                                          | 1         | 1.15%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1         | 1.15%   |
| Nvidia GK104 [GeForce GTX 680]                                              | 1         | 1.15%   |
| Nvidia GF108GLM [Quadro 1000M]                                              | 1         | 1.15%   |
| Nvidia GF108 [GeForce GT 530]                                               | 1         | 1.15%   |
| Nvidia GF108 [GeForce GT 440]                                               | 1         | 1.15%   |
| Nvidia GF106M [GeForce GTX 460M]                                            | 1         | 1.15%   |
| Nvidia G98M [GeForce G 105M]                                                | 1         | 1.15%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 1         | 1.15%   |
| Nvidia G84M [GeForce 8600M GT]                                              | 1         | 1.15%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1         | 1.15%   |
| Intel UHD Graphics 620                                                      | 1         | 1.15%   |
| Intel UHD Graphics 615                                                      | 1         | 1.15%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 1         | 1.15%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 1         | 1.15%   |
| Intel HD Graphics 630                                                       | 1         | 1.15%   |
| Intel HD Graphics 620                                                       | 1         | 1.15%   |
| Intel HD Graphics 5300                                                      | 1         | 1.15%   |
| Intel HD Graphics 530                                                       | 1         | 1.15%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1         | 1.15%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                            | 1         | 1.15%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1         | 1.15%   |
| Intel Coffee Lake UHD 610 Graphics Controller                               | 1         | 1.15%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller     | 1         | 1.15%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 1         | 1.15%   |
| AMD Wrestler [Radeon HD 6320]                                               | 1         | 1.15%   |
| AMD Venus PRO [Radeon HD 8850M / R9 M265X]                                  | 1         | 1.15%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 1         | 1.15%   |
| AMD RV730/M96 [Mobility Radeon HD 4650/5165]                                | 1         | 1.15%   |
| AMD RS880 [Radeon HD 4250]                                                  | 1         | 1.15%   |
| AMD Renoir                                                                  | 1         | 1.15%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 1         | 1.15%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 1         | 1.15%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1         | 1.15%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 1         | 1.15%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 1         | 1.15%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 37        | 45.68%  |
| 1 x Nvidia     | 22        | 27.16%  |
| 1 x AMD        | 13        | 16.05%  |
| Intel + Nvidia | 4         | 4.94%   |
| 2 x Intel      | 3         | 3.7%    |
| Intel + AMD    | 2         | 2.47%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 64        | 79.01%  |
| Proprietary | 9         | 11.11%  |
| Unknown     | 8         | 9.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 63        | 77.78%  |
| 1.01-2.0   | 6         | 7.41%   |
| 3.01-4.0   | 3         | 3.7%    |
| 0.01-0.5   | 3         | 3.7%    |
| 7.01-8.0   | 2         | 2.47%   |
| 5.01-6.0   | 2         | 2.47%   |
| 0.51-1.0   | 2         | 2.47%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| LG Display           | 9         | 15.25%  |
| Samsung Electronics  | 8         | 13.56%  |
| AU Optronics         | 6         | 10.17%  |
| BOE                  | 5         | 8.47%   |
| Chimei Innolux       | 4         | 6.78%   |
| Iiyama               | 3         | 5.08%   |
| Hewlett-Packard      | 3         | 5.08%   |
| Lenovo               | 2         | 3.39%   |
| Dell                 | 2         | 3.39%   |
| BenQ                 | 2         | 3.39%   |
| Ancor Communications | 2         | 3.39%   |
| Acer                 | 2         | 3.39%   |
| Vizio                | 1         | 1.69%   |
| ViewSonic            | 1         | 1.69%   |
| Philips              | 1         | 1.69%   |
| Medion               | 1         | 1.69%   |
| InfoVision           | 1         | 1.69%   |
| Haier                | 1         | 1.69%   |
| Goldstar             | 1         | 1.69%   |
| Eizo                 | 1         | 1.69%   |
| Apple                | 1         | 1.69%   |
| AOC                  | 1         | 1.69%   |
| ALP                  | 1         | 1.69%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch           | 2         | 3.39%   |
| Iiyama PLE2407HDS IVM560D 1920x1080 520x300mm 23.6-inch               | 2         | 3.39%   |
| Vizio LCD Monitor VIZ0022 1920x540 480x270mm 21.7-inch                | 1         | 1.69%   |
| ViewSonic VX2458-mhd VSC0437 1920x1080 520x290mm 23.4-inch            | 1         | 1.69%   |
| Samsung Electronics T22D390 SAM0B69 1920x1080 480x270mm 21.7-inch     | 1         | 1.69%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                      | 1         | 1.69%   |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                      | 1         | 1.69%   |
| Samsung Electronics LCD Monitor SEC5742 1366x768 310x170mm 13.9-inch  | 1         | 1.69%   |
| Samsung Electronics LCD Monitor SEC414C 1366x768 310x170mm 13.9-inch  | 1         | 1.69%   |
| Samsung Electronics LCD Monitor SEC3942 1366x768 310x170mm 13.9-inch  | 1         | 1.69%   |
| Samsung Electronics LCD Monitor SDC434A 3200x1800 290x170mm 13.2-inch | 1         | 1.69%   |
| Samsung Electronics LCD Monitor SAM4A75 1024x768 300x230mm 14.9-inch  | 1         | 1.69%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                | 1         | 1.69%   |
| Medion MD21281 MED3947 1366x768 410x230mm 18.5-inch                   | 1         | 1.69%   |
| LG Display LCD Monitor LGD11F9 1280x800 290x180mm 13.4-inch           | 1         | 1.69%   |
| LG Display LCD Monitor LGD0470 1920x1080 350x190mm 15.7-inch          | 1         | 1.69%   |
| LG Display LCD Monitor LGD0419 2560x1440 310x170mm 13.9-inch          | 1         | 1.69%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch           | 1         | 1.69%   |
| LG Display LCD Monitor LGD03AB 1366x768 340x190mm 15.3-inch           | 1         | 1.69%   |
| LG Display LCD Monitor LGD0323 1920x1080 350x190mm 15.7-inch          | 1         | 1.69%   |
| LG Display LCD Monitor LGD021D 1600x900 380x210mm 17.1-inch           | 1         | 1.69%   |
| Lenovo LEN-M73Z-D LEN00A0 1600x900 440x240mm 19.7-inch                | 1         | 1.69%   |
| Lenovo LCD Monitor LEN4050 1280x800 330x210mm 15.4-inch               | 1         | 1.69%   |
| InfoVision LCD Monitor IVO03F4 1024x600 220x130mm 10.1-inch           | 1         | 1.69%   |
| Iiyama PL2409HD IVM560C 1920x1080 520x290mm 23.4-inch                 | 1         | 1.69%   |
| Hewlett-Packard LCD Monitor HWP4267 1920x1080 530x300mm 24.0-inch     | 1         | 1.69%   |
| Hewlett-Packard E243m HPN3465 1920x1080 530x300mm 24.0-inch           | 1         | 1.69%   |
| Hewlett-Packard 2310 HWP288F 1920x1080 510x290mm 23.1-inch            | 1         | 1.69%   |
| Haier HT-20216B(C) HAI2031 1920x1080 480x270mm 21.7-inch              | 1         | 1.69%   |
| Goldstar L1553S GSM3BB0 1024x768 300x230mm 14.9-inch                  | 1         | 1.69%   |
| Eizo EV2316W ENC2394 1920x1080 510x290mm 23.1-inch                    | 1         | 1.69%   |
| Dell U3415W DELA0AA 3440x1440 800x330mm 34.1-inch                     | 1         | 1.69%   |
| Dell 1708FP DEL4024 1280x1024 340x270mm 17.1-inch                     | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 340x190mm 15.3-inch      | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch       | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN1492 1366x768 310x170mm 13.9-inch       | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN1124 1920x1080 260x140mm 11.6-inch      | 1         | 1.69%   |
| BOE LCD Monitor BOE0757 1366x768 340x190mm 15.3-inch                  | 1         | 1.69%   |
| BOE LCD Monitor BOE06D3 1366x768 340x190mm 15.3-inch                  | 1         | 1.69%   |
| BOE LCD Monitor BOE06C8 1366x768 280x160mm 12.7-inch                  | 1         | 1.69%   |
| BOE LCD Monitor BOE0615 1366x768 340x190mm 15.3-inch                  | 1         | 1.69%   |
| BOE LCD Monitor BOE05E9 1366x768 250x140mm 11.3-inch                  | 1         | 1.69%   |
| BenQ GW2765 BNQ78D6 2560x1440 600x340mm 27.2-inch                     | 1         | 1.69%   |
| BenQ G925HDA BNQ7843 1366x768 410x230mm 18.5-inch                     | 1         | 1.69%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 340x190mm 15.3-inch         | 1         | 1.69%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 340x190mm 15.3-inch         | 1         | 1.69%   |
| AU Optronics LCD Monitor AUO4100 1920x1200 220x140mm 10.3-inch        | 1         | 1.69%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch         | 1         | 1.69%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 340x190mm 15.3-inch         | 1         | 1.69%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 340x190mm 15.3-inch        | 1         | 1.69%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                  | 1         | 1.69%   |
| AOC LE19W037 AOC1907 1360x768 410x230mm 18.5-inch                     | 1         | 1.69%   |
| Ancor Communications VS248 ACI2498 1920x1080 530x300mm 24.0-inch      | 1         | 1.69%   |
| Ancor Communications MW221 ACI22B1 1680x1050 470x300mm 22.0-inch      | 1         | 1.69%   |
| ALP 2476 IPS ALP2476 1920x1080 530x300mm 24.0-inch                    | 1         | 1.69%   |
| Acer ET430K ACR0558 3840x2160 940x530mm 42.5-inch                     | 1         | 1.69%   |
| Acer B223W ACR0018 1680x1050 470x300mm 22.0-inch                      | 1         | 1.69%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 22        | 37.29%  |
| 1920x1080 (FHD)    | 19        | 32.2%   |
| 2560x1440 (QHD)    | 2         | 3.39%   |
| 1680x1050 (WSXGA+) | 2         | 3.39%   |
| 1600x900 (HD+)     | 2         | 3.39%   |
| 1280x800 (WXGA)    | 2         | 3.39%   |
| 1024x768 (XGA)     | 2         | 3.39%   |
| 3840x2160 (4K)     | 1         | 1.69%   |
| 3440x1440          | 1         | 1.69%   |
| 3200x1800 (QHD+)   | 1         | 1.69%   |
| 1920x540           | 1         | 1.69%   |
| 1920x1200 (WUXGA)  | 1         | 1.69%   |
| 1360x768           | 1         | 1.69%   |
| 1280x1024 (SXGA)   | 1         | 1.69%   |
| 1024x600           | 1         | 1.69%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 13        | 22.03%  |
| 13      | 7         | 11.86%  |
| 23      | 6         | 10.17%  |
| 24      | 4         | 6.78%   |
| 18      | 4         | 6.78%   |
| 12      | 4         | 6.78%   |
| 11      | 4         | 6.78%   |
| 21      | 3         | 5.08%   |
| 22      | 2         | 3.39%   |
| 17      | 2         | 3.39%   |
| 14      | 2         | 3.39%   |
| 10      | 2         | 3.39%   |
| Unknown | 2         | 3.39%   |
| 42      | 1         | 1.69%   |
| 34      | 1         | 1.69%   |
| 27      | 1         | 1.69%   |
| 19      | 1         | 1.69%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 19        | 32.2%   |
| 201-300     | 14        | 23.73%  |
| 501-600     | 11        | 18.64%  |
| 401-500     | 10        | 16.95%  |
| Unknown     | 2         | 3.39%   |
| 701-800     | 1         | 1.69%   |
| 351-400     | 1         | 1.69%   |
| 901-1000    | 1         | 1.69%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 50        | 84.75%  |
| 16/10 | 5         | 8.47%   |
| 4/3   | 2         | 3.39%   |
| 5/4   | 1         | 1.69%   |
| 21/9  | 1         | 1.69%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 15        | 25.42%  |
| 91-100         | 9         | 15.25%  |
| 81-90          | 6         | 10.17%  |
| 101-110        | 6         | 10.17%  |
| 141-150        | 5         | 8.47%   |
| 61-70          | 4         | 6.78%   |
| 51-60          | 4         | 6.78%   |
| 41-50          | 2         | 3.39%   |
| Unknown        | 2         | 3.39%   |
| 71-80          | 1         | 1.69%   |
| 351-500        | 1         | 1.69%   |
| 301-350        | 1         | 1.69%   |
| 151-200        | 1         | 1.69%   |
| 121-130        | 1         | 1.69%   |
| 501-1000       | 1         | 1.69%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 23        | 38.98%  |
| 101-120       | 19        | 32.2%   |
| 121-160       | 11        | 18.64%  |
| 161-240       | 3         | 5.08%   |
| Unknown       | 2         | 3.39%   |
| More than 240 | 1         | 1.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 57        | 70.37%  |
| 0     | 23        | 28.4%   |
| 2     | 1         | 1.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 41        | 35.04%  |
| Intel                             | 39        | 33.33%  |
| Broadcom                          | 13        | 11.11%  |
| Qualcomm Atheros                  | 10        | 8.55%   |
| Ralink Technology                 | 2         | 1.71%   |
| Ralink                            | 2         | 1.71%   |
| Marvell Technology Group          | 2         | 1.71%   |
| Huawei Technologies               | 2         | 1.71%   |
| Sierra Wireless                   | 1         | 0.85%   |
| IMC Networks                      | 1         | 0.85%   |
| Google                            | 1         | 0.85%   |
| Ericsson Business Mobile Networks | 1         | 0.85%   |
| ASUSTek Computer                  | 1         | 0.85%   |
| Aquantia                          | 1         | 0.85%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 30        | 21.58%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 7         | 5.04%   |
| Intel Wireless 7265                                                            | 6         | 4.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 5         | 3.6%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 3         | 2.16%   |
| Intel Wireless 7260                                                            | 3         | 2.16%   |
| Intel I211 Gigabit Network Connection                                          | 3         | 2.16%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 2.16%   |
| Intel Ethernet Connection (7) I219-V                                           | 3         | 2.16%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 2         | 1.44%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 2         | 1.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 2         | 1.44%   |
| Intel Wireless 8265 / 8275                                                     | 2         | 1.44%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 2         | 1.44%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                   | 2         | 1.44%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                             | 2         | 1.44%   |
| Broadcom BCM43142 802.11b/g/n                                                  | 2         | 1.44%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                                  | 1         | 0.72%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                       | 1         | 0.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 0.72%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 1         | 0.72%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 1         | 0.72%   |
| Ralink RT3072 Wireless Adapter                                                 | 1         | 0.72%   |
| Ralink MT7601U Wireless Adapter                                                | 1         | 0.72%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                      | 1         | 0.72%   |
| Ralink RT2561/RT61 rev B 802.11g                                               | 1         | 0.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 1         | 0.72%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.72%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 1         | 0.72%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 1         | 0.72%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 1         | 0.72%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.72%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.72%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1         | 0.72%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 1         | 0.72%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.72%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.72%   |
| Intel Wireless 3160                                                            | 1         | 0.72%   |
| Intel WiFi Link 5100                                                           | 1         | 0.72%   |
| Intel Wi-Fi 6 AX201                                                            | 1         | 0.72%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                        | 1         | 0.72%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.72%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.72%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.72%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 0.72%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 0.72%   |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 0.72%   |
| Intel Ethernet Connection (11) I219-V                                          | 1         | 0.72%   |
| Intel Centrino Wireless-N 6150                                                 | 1         | 0.72%   |
| Intel Centrino Wireless-N 2200                                                 | 1         | 0.72%   |
| Intel Centrino Wireless-N 135                                                  | 1         | 0.72%   |
| Intel Centrino WiMAX 6150                                                      | 1         | 0.72%   |
| Intel Centrino Ultimate-N 6300                                                 | 1         | 0.72%   |
| Intel Centrino Advanced-N 6235                                                 | 1         | 0.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 1         | 0.72%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 1         | 0.72%   |
| Intel 82583V Gigabit Network Connection                                        | 1         | 0.72%   |
| Intel 82577LC Gigabit Network Connection                                       | 1         | 0.72%   |
| Intel 82574L Gigabit Network Connection                                        | 1         | 0.72%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 0.72%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 26        | 44.07%  |
| Realtek Semiconductor | 10        | 16.95%  |
| Broadcom              | 10        | 16.95%  |
| Qualcomm Atheros      | 6         | 10.17%  |
| Ralink Technology     | 2         | 3.39%   |
| Ralink                | 2         | 3.39%   |
| Sierra Wireless       | 1         | 1.69%   |
| IMC Networks          | 1         | 1.69%   |
| ASUSTek Computer      | 1         | 1.69%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                                         | 6         | 9.84%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 3         | 4.92%   |
| Intel Wireless 7260                                                         | 3         | 4.92%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 2         | 3.28%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 2         | 3.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 2         | 3.28%   |
| Intel Wireless 8265 / 8275                                                  | 2         | 3.28%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                            | 2         | 3.28%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                | 2         | 3.28%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                          | 2         | 3.28%   |
| Broadcom BCM43142 802.11b/g/n                                               | 2         | 3.28%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                               | 1         | 1.64%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                    | 1         | 1.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 1         | 1.64%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                       | 1         | 1.64%   |
| Realtek RTL8188EE Wireless Network Adapter                                  | 1         | 1.64%   |
| Ralink RT3072 Wireless Adapter                                              | 1         | 1.64%   |
| Ralink MT7601U Wireless Adapter                                             | 1         | 1.64%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                   | 1         | 1.64%   |
| Ralink RT2561/RT61 rev B 802.11g                                            | 1         | 1.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 1         | 1.64%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 1         | 1.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 1         | 1.64%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 1         | 1.64%   |
| Intel Wireless 3160                                                         | 1         | 1.64%   |
| Intel WiFi Link 5100                                                        | 1         | 1.64%   |
| Intel Wi-Fi 6 AX201                                                         | 1         | 1.64%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                     | 1         | 1.64%   |
| Intel Centrino Wireless-N 6150                                              | 1         | 1.64%   |
| Intel Centrino Wireless-N 2200                                              | 1         | 1.64%   |
| Intel Centrino Wireless-N 135                                               | 1         | 1.64%   |
| Intel Centrino WiMAX 6150                                                   | 1         | 1.64%   |
| Intel Centrino Ultimate-N 6300                                              | 1         | 1.64%   |
| Intel Centrino Advanced-N 6235                                              | 1         | 1.64%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 1         | 1.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                    | 1         | 1.64%   |
| IMC Networks Realtek RTL8191SU Wireless LAN 802.11n USB 2.0 Network Adapter | 1         | 1.64%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                          | 1         | 1.64%   |
| Broadcom BCM43228 802.11a/b/g/n                                             | 1         | 1.64%   |
| Broadcom BCM43225 802.11b/g/n                                               | 1         | 1.64%   |
| Broadcom BCM43224 802.11a/b/g/n                                             | 1         | 1.64%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                      | 1         | 1.64%   |
| Broadcom BCM4321 802.11a/b/g/n                                              | 1         | 1.64%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                   | 1         | 1.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 37        | 48.68%  |
| Intel                    | 25        | 32.89%  |
| Qualcomm Atheros         | 5         | 6.58%   |
| Broadcom                 | 4         | 5.26%   |
| Marvell Technology Group | 2         | 2.63%   |
| Huawei Technologies      | 1         | 1.32%   |
| Google                   | 1         | 1.32%   |
| Aquantia                 | 1         | 1.32%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 30        | 39.47%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 7         | 9.21%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 5         | 6.58%   |
| Intel I211 Gigabit Network Connection                                          | 3         | 3.95%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 3.95%   |
| Intel Ethernet Connection (7) I219-V                                           | 3         | 3.95%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 1.32%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 1         | 1.32%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 1.32%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 1.32%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1         | 1.32%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.32%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 1.32%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 1.32%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 1.32%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 1.32%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 1.32%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 1.32%   |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 1.32%   |
| Intel Ethernet Connection (11) I219-V                                          | 1         | 1.32%   |
| Intel 82583V Gigabit Network Connection                                        | 1         | 1.32%   |
| Intel 82577LC Gigabit Network Connection                                       | 1         | 1.32%   |
| Intel 82574L Gigabit Network Connection                                        | 1         | 1.32%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 1.32%   |
| Huawei USB Composite Device                                                    | 1         | 1.32%   |
| Google Nexus/Pixel Device (tether)                                             | 1         | 1.32%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                 | 1         | 1.32%   |
| Broadcom NetXtreme BCM5705_2 Gigabit Ethernet                                  | 1         | 1.32%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 1         | 1.32%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 1         | 1.32%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]              | 1         | 1.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 74        | 56.06%  |
| WiFi     | 56        | 42.42%  |
| Modem    | 2         | 1.52%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 72        | 63.16%  |
| WiFi     | 41        | 35.96%  |
| Modem    | 1         | 0.88%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 44        | 54.32%  |
| 1     | 36        | 44.44%  |
| 3     | 1         | 1.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 81        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 15        | 40.54%  |
| Realtek Semiconductor           | 5         | 13.51%  |
| Broadcom                        | 5         | 13.51%  |
| Apple                           | 5         | 13.51%  |
| Foxconn / Hon Hai               | 2         | 5.41%   |
| Cambridge Silicon Radio         | 2         | 5.41%   |
| Ralink                          | 1         | 2.7%    |
| Qualcomm Atheros Communications | 1         | 2.7%    |
| ASUSTek Computer                | 1         | 2.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 9         | 24.32%  |
| Realtek  Bluetooth 4.0 Adapter                      | 2         | 5.41%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 5.41%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 5.41%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 2         | 5.41%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 5.41%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 5.41%   |
| Apple Apple Broadcom Built-in Bluetooth             | 2         | 5.41%   |
| Realtek RTL8723B Bluetooth                          | 1         | 2.7%    |
| Realtek  Bluetooth Adapter                          | 1         | 2.7%    |
| Realtek Bluetooth Radio                             | 1         | 2.7%    |
| Ralink RT3290 Bluetooth                             | 1         | 2.7%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 2.7%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 2.7%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 2.7%    |
| Intel AX201 Bluetooth                               | 1         | 2.7%    |
| Intel AX200 Bluetooth                               | 1         | 2.7%    |
| Foxconn / Hon Hai Broadcom Bluetooth 4.0 USB        | 1         | 2.7%    |
| Foxconn / Hon Hai Atheros AR3012 Bluetooth          | 1         | 2.7%    |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter    | 1         | 2.7%    |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 2.7%    |
| Apple Bluetooth HCI                                 | 1         | 2.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 65        | 55.56%  |
| Nvidia                  | 20        | 17.09%  |
| AMD                     | 19        | 16.24%  |
| C-Media Electronics     | 4         | 3.42%   |
| Texas Instruments       | 2         | 1.71%   |
| Logitech                | 2         | 1.71%   |
| XMOS                    | 1         | 0.85%   |
| Plantronics             | 1         | 0.85%   |
| Hewlett-Packard         | 1         | 0.85%   |
| Creative Labs           | 1         | 0.85%   |
| BEHRINGER International | 1         | 0.85%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 13        | 9.49%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 7         | 5.11%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 4.38%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5         | 3.65%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 2.92%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 2.92%   |
| Intel Sunrise Point-LP HD Audio                                            | 4         | 2.92%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 2.92%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 2.92%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 2.92%   |
| AMD Starship/Matisse HD Audio Controller                                   | 4         | 2.92%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 2.19%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 2.19%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 2.19%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 2.19%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 2.19%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 2.19%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3         | 2.19%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3         | 2.19%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3         | 2.19%   |
| Texas Instruments PCM2902 Audio Codec                                      | 2         | 1.46%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 1.46%   |
| Nvidia High Definition Audio Controller                                    | 2         | 1.46%   |
| Nvidia GM206 High Definition Audio Controller                              | 2         | 1.46%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 1.46%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2         | 1.46%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2         | 1.46%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 1.46%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 1.46%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2         | 1.46%   |
| Intel 200 Series PCH HD Audio                                              | 2         | 1.46%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 2         | 1.46%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2         | 1.46%   |
| XMOS retrieving string failed                                              | 1         | 0.73%   |
| Plantronics Plantronics Blackwire 325.1                                    | 1         | 0.73%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 0.73%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.73%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.73%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1         | 0.73%   |
| Nvidia GF106 High Definition Audio Controller                              | 1         | 0.73%   |
| Logitech HD Webcam C910                                                    | 1         | 0.73%   |
| Logitech HD Webcam C510                                                    | 1         | 0.73%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 0.73%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 0.73%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 0.73%   |
| Hewlett-Packard E243m                                                      | 1         | 0.73%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 1         | 0.73%   |
| C-Media Electronics CM108 Audio Controller                                 | 1         | 0.73%   |
| C-Media Electronics CM102-A+/102S+ Audio Controller                        | 1         | 0.73%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1         | 0.73%   |
| C-Media Electronics Audio Adapter                                          | 1         | 0.73%   |
| BEHRINGER International UMC202HD 192k                                      | 1         | 0.73%   |
| AMD Wrestler HDMI Audio                                                    | 1         | 0.73%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1         | 0.73%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1         | 0.73%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 1         | 0.73%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 0.73%   |
| AMD Navi 21 HDMI Audio [Radeon RX 6800/6800 XT / 6900 XT]                  | 1         | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 16        | 16.16%  |
| Samsung Electronics | 14        | 14.14%  |
| Kingston            | 13        | 13.13%  |
| Unknown             | 11        | 11.11%  |
| Micron Technology   | 9         | 9.09%   |
| Crucial             | 9         | 9.09%   |
| Team                | 5         | 5.05%   |
| Unknown             | 4         | 4.04%   |
| Corsair             | 3         | 3.03%   |
| Teikon              | 2         | 2.02%   |
| Nanya Technology    | 2         | 2.02%   |
| Elpida              | 2         | 2.02%   |
| A-DATA Technology   | 2         | 2.02%   |
| Transcend           | 1         | 1.01%   |
| Smart Brazil        | 1         | 1.01%   |
| Smart               | 1         | 1.01%   |
| Ramaxel Technology  | 1         | 1.01%   |
| PKI/Kingston        | 1         | 1.01%   |
| Patriot             | 1         | 1.01%   |
| ASint Technology    | 1         | 1.01%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown                                                      | 4         | 3.92%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 2         | 1.96%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s          | 2         | 1.96%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 1.96%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 1.96%   |
| Micron RAM 8ATF1G64HZ-2G3H1 8GB SODIMM DDR4 2400MT/s         | 2         | 1.96%   |
| Crucial RAM CT8G4DFS8266.M8FD 8GB DIMM DDR4 2667MT/s         | 2         | 1.96%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                  | 1         | 0.98%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                  | 1         | 0.98%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                  | 1         | 0.98%   |
| Unknown RAM Module 4GB SODIMM DDR3                           | 1         | 0.98%   |
| Unknown RAM Module 4GB FB-DIMM DDR2 667MT/s                  | 1         | 0.98%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                    | 1         | 0.98%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                     | 1         | 0.98%   |
| Unknown RAM Module 4GB DIMM 400MT/s                          | 1         | 0.98%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                         | 1         | 0.98%   |
| Transcend RAM JM1333KSN-4G 4GB DIMM DDR3 1333MT/s            | 1         | 0.98%   |
| Teikon RAM TMT451S6BFR8A-PBHC 4GB SODIMM DDR3 1333MT/s       | 1         | 0.98%   |
| Teikon RAM TMT41GS6BFR8A-PBSC 8GB SODIMM DDR3 1600MT/s       | 1         | 0.98%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2667MT/s           | 1         | 0.98%   |
| Team RAM TEAMGROUP-SD3-1066 4GB SODIMM DDR3 1067MT/s         | 1         | 0.98%   |
| Team RAM Elite-1333 4GB SODIMM DDR3 1333MT/s                 | 1         | 0.98%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s        | 1         | 0.98%   |
| Smart Brazil RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2133MT/s | 1         | 0.98%   |
| SK Hynix RAM Module 8GB Row Of Chips LPDDR3 1600MT/s         | 1         | 0.98%   |
| SK Hynix RAM Module 2GB SODIMM DDR3 1600MT/s                 | 1         | 0.98%   |
| SK Hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s         | 1         | 0.98%   |
| SK Hynix RAM HMT451S6BCFR8A-PB 4GB DIMM DDR3                 | 1         | 0.98%   |
| SK Hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.98%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.98%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 0.98%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 0.98%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.98%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 1         | 0.98%   |
| SK Hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.98%   |
| SK Hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1333MT/s       | 1         | 0.98%   |
| SK Hynix RAM HMA81GS6MFR8N-UH 8GB SODIMM DDR4 2400MT/s       | 1         | 0.98%   |
| Samsung RAM Module 2GB DIMM DDR3 400MT/s                     | 1         | 0.98%   |
| Samsung RAM Module 16GB DIMM DDR3 1333MT/s                   | 1         | 0.98%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s        | 1         | 0.98%   |
| Samsung RAM M471B5674-H0-YK0--- 4GB Chip DDR3 1600MT/s       | 1         | 0.98%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1333MT/s        | 1         | 0.98%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s        | 1         | 0.98%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1333MT/s        | 1         | 0.98%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 0.98%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 1         | 0.98%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s        | 1         | 0.98%   |
| Samsung RAM M393B1K70DH0 8GB DIMM DDR3 1600MT/s              | 1         | 0.98%   |
| Samsung RAM M378B5773QB0-CK0 2GB DIMM DDR3 1600MT/s          | 1         | 0.98%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3                   | 1         | 0.98%   |
| Samsung RAM M378B5173BH0-CK0 4GB DIMM DDR3 1600MT/s          | 1         | 0.98%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 1600MT/s          | 1         | 0.98%   |
| Ramaxel RAM RMR5030MN68F9F1600 4GB DIMM DDR3 1600MT/s        | 1         | 0.98%   |
| PKI/Kingston RAM 9905428-043.A00LF 4GB SODIMM DDR3 1067MT/s  | 1         | 0.98%   |
| Patriot RAM 1600 CL9 Series 4GB DIMM DDR3 1600MT/s           | 1         | 0.98%   |
| Nanya RAM NT2GC64B8HA1NS-BE 2GB SODIMM DDR3 1066MT/s         | 1         | 0.98%   |
| Nanya RAM M2F4G64CB8HG5N-CG 4GB DIMM DDR3 1333MT/s           | 1         | 0.98%   |
| Nanya RAM M2F2G64CB88G7N-CG 2GB DIMM DDR3 1333MT/s           | 1         | 0.98%   |
| Micron RAM Module 2GB SODIMM DDR3 1333MT/s                   | 1         | 0.98%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s        | 1         | 0.98%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 48        | 58.54%  |
| DDR4    | 23        | 28.05%  |
| DDR2    | 4         | 4.88%   |
| LPDDR3  | 2         | 2.44%   |
| Unknown | 2         | 2.44%   |
| SDRAM   | 1         | 1.22%   |
| LPDDR4  | 1         | 1.22%   |
| DDR     | 1         | 1.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 42        | 51.22%  |
| DIMM         | 36        | 43.9%   |
| Row Of Chips | 2         | 2.44%   |
| FB-DIMM      | 1         | 1.22%   |
| Chip         | 1         | 1.22%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 36        | 39.13%  |
| 8192  | 27        | 29.35%  |
| 2048  | 20        | 21.74%  |
| 16384 | 8         | 8.7%    |
| 32768 | 1         | 1.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 30        | 34.48%  |
| 1333    | 17        | 19.54%  |
| 2667    | 7         | 8.05%   |
| 2400    | 7         | 8.05%   |
| 3200    | 4         | 4.6%    |
| 1067    | 4         | 4.6%    |
| 667     | 4         | 4.6%    |
| 2133    | 3         | 3.45%   |
| 1066    | 3         | 3.45%   |
| 2666    | 2         | 2.3%    |
| 400     | 2         | 2.3%    |
| Unknown | 2         | 2.3%    |
| 4267    | 1         | 1.15%   |
| 1334    | 1         | 1.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart_bsd/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Lexmark International | 1         | 50%     |
| Brother Industries    | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart_bsd/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Lexmark International SINDOH A603_A608 Print | 1         | 50%     |
| Brother DCP-J100                             | 1         | 50%     |

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
| Chicony Electronics                    | 7         | 19.44%  |
| Sunplus Innovation Technology          | 3         | 8.33%   |
| Realtek Semiconductor                  | 3         | 8.33%   |
| IMC Networks                           | 3         | 8.33%   |
| Acer                                   | 3         | 8.33%   |
| Suyin                                  | 2         | 5.56%   |
| Microdia                               | 2         | 5.56%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 5.56%   |
| Z-Star Microelectronics                | 1         | 2.78%   |
| Tripath Technology                     | 1         | 2.78%   |
| Syntek                                 | 1         | 2.78%   |
| Logitech                               | 1         | 2.78%   |
| Lite-On Technology                     | 1         | 2.78%   |
| Lenovo                                 | 1         | 2.78%   |
| Importek                               | 1         | 2.78%   |
| Hewlett-Packard                        | 1         | 2.78%   |
| Foxconn / Hon Hai                      | 1         | 2.78%   |
| Apple                                  | 1         | 2.78%   |
| ALi                                    | 1         | 2.78%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 4         | 11.11%  |
| Realtek Realtek USB2.0 PC Camera                            | 2         | 5.56%   |
| Z-Star A4 TECH USB2.0 PC Camera J                           | 1         | 2.78%   |
| Tripath 2M Front Camera                                     | 1         | 2.78%   |
| Syntek EasyCamera                                           | 1         | 2.78%   |
| Suyin Integrated_Webcam_HD                                  | 1         | 2.78%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 2.78%   |
| Sunplus Lenovo EasyCamera                                   | 1         | 2.78%   |
| Sunplus Laptop_Integrated_Webcam_FHD                        | 1         | 2.78%   |
| Sunplus Integrated Camera                                   | 1         | 2.78%   |
| Realtek Integrated_Webcam_HD                                | 1         | 2.78%   |
| Microdia Laptop_Integrated_Webcam_2M                        | 1         | 2.78%   |
| Microdia Dell Laptop Integrated Webcam HD                   | 1         | 2.78%   |
| Logitech Webcam C270                                        | 1         | 2.78%   |
| Lite-On Integrated Camera                                   | 1         | 2.78%   |
| Lenovo Integrated Webcam                                    | 1         | 2.78%   |
| Importek HP Webcam                                          | 1         | 2.78%   |
| IMC Networks XHC Camera                                     | 1         | 2.78%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 1         | 2.78%   |
| IMC Networks 2M Integrated Webcam                           | 1         | 2.78%   |
| HP Premium Starter Webcam                                   | 1         | 2.78%   |
| Foxconn / Hon Hai USB2.0 Camera                             | 1         | 2.78%   |
| Chicony TOSHIBA Web Camera - HD                             | 1         | 2.78%   |
| Chicony HP Display Camera                                   | 1         | 2.78%   |
| Chicony Asus 720p CMOS webcam                               | 1         | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam-101        | 1         | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) HP Integrated Webcam | 1         | 2.78%   |
| Apple FaceTime HD Camera (Built-in)                         | 1         | 2.78%   |
| ALi WebCam                                                  | 1         | 2.78%   |
| Acer ThinkPad Integrated Camera                             | 1         | 2.78%   |
| Acer Lenovo EasyCamera                                      | 1         | 2.78%   |
| Acer Integrated Camera                                      | 1         | 2.78%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 3         | 50%     |
| AuthenTec             | 2         | 33.33%  |
| Elan Microelectronics | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor | 2         | 33.33%  |
| Validity Sensors VFS301 Fingerprint Reader   | 1         | 16.67%  |
| Elan ELAN WBF Fingerprint Sensor             | 1         | 16.67%  |
| AuthenTec AuthenTec Inc. AES1660             | 1         | 16.67%  |
| AuthenTec AES2810                            | 1         | 16.67%  |

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
| 1     | 32        | 39.51%  |
| 2     | 21        | 25.93%  |
| 0     | 18        | 22.22%  |
| 3     | 9         | 11.11%  |
| 4     | 1         | 1.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 51        | 50.5%   |
| Net/wireless             | 16        | 15.84%  |
| Card reader              | 13        | 12.87%  |
| Fingerprint reader       | 6         | 5.94%   |
| Firewire controller      | 5         | 4.95%   |
| Sound                    | 3         | 2.97%   |
| Bluetooth                | 3         | 2.97%   |
| Storage                  | 2         | 1.98%   |
| Network                  | 1         | 0.99%   |
| Net/ethernet             | 1         | 0.99%   |

