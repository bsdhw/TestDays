BSD in Brazil - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for BSD in Brazil.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
  - [ OS                       ](#os)
  - [ OS Family                ](#os-family)
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

Total: 84

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T61 7661GY9        | [7ab5339eee](https://bsd-hardware.info/?probe=7ab5339eee) | Jul 30, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [e2a5a65135](https://bsd-hardware.info/?probe=e2a5a65135) | Jul 23, 2022 |
| Dell          | Inspiron MP061              | [56a7002cc5](https://bsd-hardware.info/?probe=56a7002cc5) | Jul 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [b09ba0c799](https://bsd-hardware.info/?probe=b09ba0c799) | Jul 12, 2022 |
| Acer          | Aspire E5-571G              | [56fae2295e](https://bsd-hardware.info/?probe=56fae2295e) | Jul 08, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [ba96a05e5c](https://bsd-hardware.info/?probe=ba96a05e5c) | Jul 08, 2022 |
| Lenovo        | ThinkPad T410 2522CS7       | [a1561dacb2](https://bsd-hardware.info/?probe=a1561dacb2) | Jun 26, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 82BU      | [6a6450f264](https://bsd-hardware.info/?probe=6a6450f264) | May 30, 2022 |
| Acer          | Aspire 5742                 | [b0ea5e7a5e](https://bsd-hardware.info/?probe=b0ea5e7a5e) | May 19, 2022 |
| Dell          | Inspiron 5437               | [830ea686ab](https://bsd-hardware.info/?probe=830ea686ab) | Apr 24, 2022 |
| Gateway       | NE56R                       | [87d177b9da](https://bsd-hardware.info/?probe=87d177b9da) | Mar 20, 2022 |
| Acer          | Aspire E1-421               | [cc83218496](https://bsd-hardware.info/?probe=cc83218496) | Mar 10, 2022 |
| Itautec       | Infoway w7535               | [b55f9d1bfb](https://bsd-hardware.info/?probe=b55f9d1bfb) | Mar 09, 2022 |
| Apple         | MacBookPro8,1               | [aa484c30a8](https://bsd-hardware.info/?probe=aa484c30a8) | Feb 12, 2022 |
| Gateway       | NE56R                       | [a5aa8aa49a](https://bsd-hardware.info/?probe=a5aa8aa49a) | Jan 18, 2022 |
| Acer          | Aspire ES1-533              | [a9d2458de5](https://bsd-hardware.info/?probe=a9d2458de5) | Jan 13, 2022 |
| Sony          | VPCYB45JB                   | [cd18905620](https://bsd-hardware.info/?probe=cd18905620) | Jan 09, 2022 |
| Lenovo        | G550 2958                   | [21407195e3](https://bsd-hardware.info/?probe=21407195e3) | Jan 07, 2022 |
| Samsung       | 530XBB                      | [fe0adb59d8](https://bsd-hardware.info/?probe=fe0adb59d8) | Dec 20, 2021 |
| Philco        | 10B                         | [a27148f35d](https://bsd-hardware.info/?probe=a27148f35d) | Dec 06, 2021 |
| Positivo      | C14CR01                     | [a33c158f9f](https://bsd-hardware.info/?probe=a33c158f9f) | Dec 05, 2021 |
| Samsung       | 530XBB                      | [8387645312](https://bsd-hardware.info/?probe=8387645312) | Dec 03, 2021 |
| Samsung       | 530XBB                      | [41d5f95889](https://bsd-hardware.info/?probe=41d5f95889) | Dec 03, 2021 |
| Samsung       | 530XBB                      | [e1983c2353](https://bsd-hardware.info/?probe=e1983c2353) | Dec 03, 2021 |
| Samsung       | 530XBB                      | [b344605891](https://bsd-hardware.info/?probe=b344605891) | Dec 02, 2021 |
| Dell          | Inspiron 5566               | [7c6b2f2013](https://bsd-hardware.info/?probe=7c6b2f2013) | Nov 14, 2021 |
| Toshiba       | STI NA 1401                 | [bbbf661ee8](https://bsd-hardware.info/?probe=bbbf661ee8) | Nov 14, 2021 |
| HP            | 14                          | [e0c8e95e52](https://bsd-hardware.info/?probe=e0c8e95e52) | Nov 07, 2021 |
| HP            | EliteBook 840 G3            | [03be88ded4](https://bsd-hardware.info/?probe=03be88ded4) | Nov 02, 2021 |
| Dell          | Inspiron 7460               | [3dbc09a4df](https://bsd-hardware.info/?probe=3dbc09a4df) | Oct 13, 2021 |
| Lenovo        | ThinkPad X250 20CLS2A11K    | [e47f4113bf](https://bsd-hardware.info/?probe=e47f4113bf) | Oct 08, 2021 |
| Itautec       | Infoway w7530               | [a376201681](https://bsd-hardware.info/?probe=a376201681) | Oct 05, 2021 |
| Dell          | Latitude 5490               | [f0f4370a9c](https://bsd-hardware.info/?probe=f0f4370a9c) | Sep 27, 2021 |
| Itautec       | Infoway w7530               | [d91ec24ce0](https://bsd-hardware.info/?probe=d91ec24ce0) | Aug 29, 2021 |
| Itautec       | Infoway w7530               | [fe69db32c8](https://bsd-hardware.info/?probe=fe69db32c8) | Aug 27, 2021 |
| Acer          | Aspire 5750                 | [2bc72bf29e](https://bsd-hardware.info/?probe=2bc72bf29e) | Aug 23, 2021 |
| Avell High... | A60 MUV                     | [85f5c972a5](https://bsd-hardware.info/?probe=85f5c972a5) | Aug 21, 2021 |
| Samsung       | 300E5M/300E5L               | [ae874102c3](https://bsd-hardware.info/?probe=ae874102c3) | Aug 04, 2021 |
| Dell          | Inspiron 3442               | [6283cb4190](https://bsd-hardware.info/?probe=6283cb4190) | Aug 01, 2021 |
| Avell High... | A62 LIV                     | [5983302b1d](https://bsd-hardware.info/?probe=5983302b1d) | Jul 21, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [daa7e68a1f](https://bsd-hardware.info/?probe=daa7e68a1f) | Jul 21, 2021 |
| Acer          | Aspire A515-54G             | [08cafd05b1](https://bsd-hardware.info/?probe=08cafd05b1) | Jul 06, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [128c08e60f](https://bsd-hardware.info/?probe=128c08e60f) | Jul 04, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [ceb18e38a3](https://bsd-hardware.info/?probe=ceb18e38a3) | Jun 28, 2021 |
| Acer          | Aspire 5750                 | [d59f20f88a](https://bsd-hardware.info/?probe=d59f20f88a) | Jun 22, 2021 |
| Acer          | Aspire 5750                 | [cc6dc71d37](https://bsd-hardware.info/?probe=cc6dc71d37) | Jun 21, 2021 |
| Gateway       | NE56R                       | [cc65e24aea](https://bsd-hardware.info/?probe=cc65e24aea) | Jun 20, 2021 |
| Gateway       | NE56R                       | [932f5d03f3](https://bsd-hardware.info/?probe=932f5d03f3) | Jun 13, 2021 |
| Dell          | Vostro 5490                 | [cf3508718c](https://bsd-hardware.info/?probe=cf3508718c) | Jun 11, 2021 |
| Lenovo        | ThinkPad X220 4291ON5       | [66743a51cc](https://bsd-hardware.info/?probe=66743a51cc) | Jun 04, 2021 |
| Acer          | Aspire A515-51G             | [53a69aa8c1](https://bsd-hardware.info/?probe=53a69aa8c1) | Jun 04, 2021 |
| Lenovo        | ThinkPad X270 20HM004JBR    | [88c27e65d7](https://bsd-hardware.info/?probe=88c27e65d7) | May 23, 2021 |
| Dell          | Inspiron 3442               | [0d1d75a914](https://bsd-hardware.info/?probe=0d1d75a914) | May 23, 2021 |
| Dell          | Inspiron 3442               | [076dc91b26](https://bsd-hardware.info/?probe=076dc91b26) | May 13, 2021 |
| Lenovo        | ThinkPad E490 20N9001SBR    | [852a900303](https://bsd-hardware.info/?probe=852a900303) | Apr 22, 2021 |
| Gateway       | NE56R                       | [bbbc827581](https://bsd-hardware.info/?probe=bbbc827581) | Apr 16, 2021 |
| Gateway       | NE56R                       | [f4031498db](https://bsd-hardware.info/?probe=f4031498db) | Apr 15, 2021 |
| Gateway       | NE56R                       | [af262c2350](https://bsd-hardware.info/?probe=af262c2350) | Apr 11, 2021 |
| Avell High... | A62                         | [df77dd6562](https://bsd-hardware.info/?probe=df77dd6562) | Mar 22, 2021 |
| Notebook      | N85_N87HCHNHZ               | [e84b5b6e5f](https://bsd-hardware.info/?probe=e84b5b6e5f) | Mar 22, 2021 |
| Lenovo        | ThinkPad X220 4291ON5       | [8d81204137](https://bsd-hardware.info/?probe=8d81204137) | Mar 22, 2021 |
| Dell          | Inspiron 7520               | [599d3e84d7](https://bsd-hardware.info/?probe=599d3e84d7) | Mar 16, 2021 |
| Dell          | Inspiron 3442               | [f156951052](https://bsd-hardware.info/?probe=f156951052) | Mar 14, 2021 |
| Dell          | Inspiron 3543               | [525eeec663](https://bsd-hardware.info/?probe=525eeec663) | Mar 12, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [5211d36066](https://bsd-hardware.info/?probe=5211d36066) | Feb 25, 2021 |
| Unknown       | Unknown                     | [d11ec93413](https://bsd-hardware.info/?probe=d11ec93413) | Feb 23, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [467a915fc7](https://bsd-hardware.info/?probe=467a915fc7) | Feb 23, 2021 |
| LG Electro... | 14Z980-G.BH51P1             | [d8ee6bc4e3](https://bsd-hardware.info/?probe=d8ee6bc4e3) | Feb 22, 2021 |
| Lenovo        | ThinkPad X240 20AMS4V000    | [cbfa45fe44](https://bsd-hardware.info/?probe=cbfa45fe44) | Feb 22, 2021 |
| ASUSTek       | K46CA                       | [f286c1e784](https://bsd-hardware.info/?probe=f286c1e784) | Feb 21, 2021 |
| Dell          | Venue 11 Pro 7140           | [1a49b7921a](https://bsd-hardware.info/?probe=1a49b7921a) | Feb 17, 2021 |
| Lenovo        | ThinkPad T430 2349PMP       | [23de6449ad](https://bsd-hardware.info/?probe=23de6449ad) | Feb 17, 2021 |
| Dell          | Inspiron 3421               | [c5f6880081](https://bsd-hardware.info/?probe=c5f6880081) | Feb 15, 2021 |
| Dell          | Inspiron 3442               | [411797b4dc](https://bsd-hardware.info/?probe=411797b4dc) | Feb 13, 2021 |
| Clevo         | C41X0                       | [81c48d156a](https://bsd-hardware.info/?probe=81c48d156a) | Feb 12, 2021 |
| Apple         | MacBook6,1                  | [3a9335691f](https://bsd-hardware.info/?probe=3a9335691f) | Feb 11, 2021 |
| Samsung       | 300E5M/300E5L               | [a667296c17](https://bsd-hardware.info/?probe=a667296c17) | Feb 03, 2021 |
| Lenovo        | ThinkPad T450s 20BWS05G0... | [bc2855974c](https://bsd-hardware.info/?probe=bc2855974c) | Dec 06, 2020 |
| Unknown       | Unknown                     | [6953b9a9e4](https://bsd-hardware.info/?probe=6953b9a9e4) | Nov 22, 2020 |
| Dell          | Latitude 3490               | [b28cc12aeb](https://bsd-hardware.info/?probe=b28cc12aeb) | Sep 20, 2020 |
| Lenovo        | ThinkPad T490 20N30029BR    | [41dbfb6fdc](https://bsd-hardware.info/?probe=41dbfb6fdc) | Aug 06, 2020 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | [1b84bffd9b](https://bsd-hardware.info/?probe=1b84bffd9b) | Jul 24, 2020 |
| Sony          | VPCEG17FB                   | [7d48bd3606](https://bsd-hardware.info/?probe=7d48bd3606) | Jul 13, 2020 |
| Lenovo        | ThinkPad X250 20CLS18S0Z    | [f668ce4e5b](https://bsd-hardware.info/?probe=f668ce4e5b) | Jul 05, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| helloSystem 0.6.0    | 10        | 13.89%  |
| helloSystem 0.4.0    | 10        | 13.89%  |
| helloSystem 0.7.0    | 9         | 12.5%   |
| helloSystem 0.5.0    | 9         | 12.5%   |
| FreeBSD 13.0         | 6         | 8.33%   |
| helloSystem 0.8.0    | 3         | 4.17%   |
| FreeBSD 14.0-CURRENT | 3         | 4.17%   |
| FreeBSD 13.0-p3      | 3         | 4.17%   |
| FreeBSD 13.0-STABLE  | 2         | 2.78%   |
| FreeBSD 12.1         | 2         | 2.78%   |
| OS108 9.99.68        | 1         | 1.39%   |
| OpenBSD 7.0          | 1         | 1.39%   |
| OpenBSD 6.9          | 1         | 1.39%   |
| helloSystem 0.3.0    | 1         | 1.39%   |
| GhostBSD 22.07.10    | 1         | 1.39%   |
| GhostBSD 20.04.02    | 1         | 1.39%   |
| FreeBSD 13.0-RC2     | 1         | 1.39%   |
| FreeBSD 13.0-p7      | 1         | 1.39%   |
| FreeBSD 13.0-p4      | 1         | 1.39%   |
| FreeBSD 13.0-CURRENT | 1         | 1.39%   |
| FreeBSD 12.2-p3      | 1         | 1.39%   |
| FreeBSD 12.2         | 1         | 1.39%   |
| FreeBSD 12.1-p7      | 1         | 1.39%   |
| FreeBSD 12.1-p11     | 1         | 1.39%   |
| DragonFly 5.8        | 1         | 1.39%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| helloSystem | 39        | 56.52%  |
| FreeBSD     | 24        | 34.78%  |
| OpenBSD     | 2         | 2.9%    |
| GhostBSD    | 2         | 2.9%    |
| OS108       | 1         | 1.45%   |
| DragonFly   | 1         | 1.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 66        | 98.51%  |
| i386  | 1         | 1.49%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 38        | 55.07%  |
| XFCE         | 5         | 7.25%   |
| MATE         | 5         | 7.25%   |
| Console      | 5         | 7.25%   |
| KDE5         | 4         | 5.8%    |
| GNOME        | 4         | 5.8%    |
| i3           | 2         | 2.9%    |
| fvwm         | 2         | 2.9%    |
| TWM          | 1         | 1.45%   |
| spectrwm     | 1         | 1.45%   |
| Openbox      | 1         | 1.45%   |
| LXQt         | 1         | 1.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 63        | 94.03%  |
| Console | 4         | 5.97%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 44        | 63.77%  |
| Console | 10        | 14.49%  |
| LightDM | 6         | 8.7%    |
| SDDM    | 4         | 5.8%    |
| XDM     | 3         | 4.35%   |
| GDM     | 2         | 2.9%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| en_US           | 43        | 62.32%  |
| C               | 11        | 15.94%  |
| Unknown         | 8         | 11.59%  |
| pt_BR           | 5         | 7.25%   |
| en_US.ISO8859-1 | 1         | 1.45%   |
| en_GB           | 1         | 1.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 56        | 83.58%  |
| BIOS | 11        | 16.42%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Zfs     | 50        | 71.43%  |
| Ufs     | 10        | 14.29%  |
| Cd9660  | 7         | 10%     |
| Ffs     | 2         | 2.86%   |
| Hammer2 | 1         | 1.43%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 65        | 97.01%  |
| MBR     | 1         | 1.49%   |
| Unknown | 1         | 1.49%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 16        | 23.88%  |
| Dell                   | 14        | 20.9%   |
| Acer                   | 8         | 11.94%  |
| Samsung Electronics    | 6         | 8.96%   |
| Avell High Performance | 3         | 4.48%   |
| Sony                   | 2         | 2.99%   |
| Itautec                | 2         | 2.99%   |
| Hewlett-Packard        | 2         | 2.99%   |
| Gateway                | 2         | 2.99%   |
| ASUSTek Computer       | 2         | 2.99%   |
| Apple                  | 2         | 2.99%   |
| Unknown                | 2         | 2.99%   |
| Semp Toshiba           | 1         | 1.49%   |
| Positivo               | 1         | 1.49%   |
| Philco                 | 1         | 1.49%   |
| Notebook               | 1         | 1.49%   |
| LG Electronics         | 1         | 1.49%   |
| Clevo                  | 1         | 1.49%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Dell Inspiron 3442                          | 3         | 4.48%   |
| Samsung 340XAA/350XAA/550XAA                | 2         | 2.99%   |
| Gateway NE56R                               | 2         | 2.99%   |
| Acer Aspire 5750                            | 2         | 2.99%   |
| Unknown                                     | 2         | 2.99%   |
| Sony VPCYB45JB                              | 1         | 1.49%   |
| Sony VPCEG17FB                              | 1         | 1.49%   |
| Semp Toshiba STI NA 1401                    | 1         | 1.49%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 1         | 1.49%   |
| Samsung 530XBB                              | 1         | 1.49%   |
| Samsung 300E5M/300E5L                       | 1         | 1.49%   |
| Samsung 270E5K/270E5Q/271E5K/2570EK         | 1         | 1.49%   |
| Positivo C14CR01                            | 1         | 1.49%   |
| Philco 10B                                  | 1         | 1.49%   |
| Notebook N85_N87HCHNHZ                      | 1         | 1.49%   |
| LG 14Z980-G.BH51P1                          | 1         | 1.49%   |
| Lenovo ThinkPad X270 20HM004JBR             | 1         | 1.49%   |
| Lenovo ThinkPad X250 20CLS2A11K             | 1         | 1.49%   |
| Lenovo ThinkPad X250 20CLS18S0Z             | 1         | 1.49%   |
| Lenovo ThinkPad X240 20AMS4V000             | 1         | 1.49%   |
| Lenovo ThinkPad X220 4291ON5                | 1         | 1.49%   |
| Lenovo ThinkPad T61 7661GY9                 | 1         | 1.49%   |
| Lenovo ThinkPad T490 20N30029BR             | 1         | 1.49%   |
| Lenovo ThinkPad T450s 20BWS05G0T            | 1         | 1.49%   |
| Lenovo ThinkPad T430 2349PMP                | 1         | 1.49%   |
| Lenovo ThinkPad T410 2522CS7                | 1         | 1.49%   |
| Lenovo ThinkPad E490 20N9001SBR             | 1         | 1.49%   |
| Lenovo IdeaPad S145-15IWL 81S9              | 1         | 1.49%   |
| Lenovo IdeaPad S145-15IWL 81MV              | 1         | 1.49%   |
| Lenovo IdeaPad S145-15API 81V7              | 1         | 1.49%   |
| Lenovo IdeaPad 3 15IGL05 82BU               | 1         | 1.49%   |
| Lenovo G550 2958                            | 1         | 1.49%   |
| Itautec Infoway w7535                       | 1         | 1.49%   |
| Itautec Infoway w7530                       | 1         | 1.49%   |
| HP EliteBook 840 G3                         | 1         | 1.49%   |
| HP 14                                       | 1         | 1.49%   |
| Dell Vostro 5490                            | 1         | 1.49%   |
| Dell Venue 11 Pro 7140                      | 1         | 1.49%   |
| Dell Latitude 5490                          | 1         | 1.49%   |
| Dell Latitude 3490                          | 1         | 1.49%   |
| Dell Inspiron MP061                         | 1         | 1.49%   |
| Dell Inspiron 7520                          | 1         | 1.49%   |
| Dell Inspiron 7460                          | 1         | 1.49%   |
| Dell Inspiron 5566                          | 1         | 1.49%   |
| Dell Inspiron 5437                          | 1         | 1.49%   |
| Dell Inspiron 3543                          | 1         | 1.49%   |
| Dell Inspiron 3421                          | 1         | 1.49%   |
| Clevo C41X0                                 | 1         | 1.49%   |
| Avell High Performance A62 LIV              | 1         | 1.49%   |
| Avell High Performance A62                  | 1         | 1.49%   |
| Avell High Performance A60 MUV              | 1         | 1.49%   |
| ASUS VivoBook_ASUSLaptop X515JA_X515JA      | 1         | 1.49%   |
| ASUS K46CA                                  | 1         | 1.49%   |
| Apple MacBookPro8,1                         | 1         | 1.49%   |
| Apple MacBook6,1                            | 1         | 1.49%   |
| Acer Aspire ES1-533                         | 1         | 1.49%   |
| Acer Aspire E5-571G                         | 1         | 1.49%   |
| Acer Aspire E1-421                          | 1         | 1.49%   |
| Acer Aspire A515-54G                        | 1         | 1.49%   |
| Acer Aspire A515-51G                        | 1         | 1.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 11        | 16.42%  |
| Dell Inspiron              | 10        | 14.93%  |
| Acer Aspire                | 8         | 11.94%  |
| Lenovo IdeaPad             | 4         | 5.97%   |
| Samsung 340XAA             | 2         | 2.99%   |
| Itautec Infoway            | 2         | 2.99%   |
| Gateway NE56R              | 2         | 2.99%   |
| Dell Latitude              | 2         | 2.99%   |
| Avell High Performance A62 | 2         | 2.99%   |
| Unknown                    | 2         | 2.99%   |
| Sony VPCYB45JB             | 1         | 1.49%   |
| Sony VPCEG17FB             | 1         | 1.49%   |
| Semp Toshiba STI           | 1         | 1.49%   |
| Samsung RV411              | 1         | 1.49%   |
| Samsung 530XBB             | 1         | 1.49%   |
| Samsung 300E5M             | 1         | 1.49%   |
| Samsung 270E5K             | 1         | 1.49%   |
| Positivo C14CR01           | 1         | 1.49%   |
| Philco 10B                 | 1         | 1.49%   |
| Notebook N85               | 1         | 1.49%   |
| LG 14Z980-G.BH51P1         | 1         | 1.49%   |
| Lenovo G550                | 1         | 1.49%   |
| HP EliteBook               | 1         | 1.49%   |
| HP 14                      | 1         | 1.49%   |
| Dell Vostro                | 1         | 1.49%   |
| Dell Venue                 | 1         | 1.49%   |
| Clevo C41X0                | 1         | 1.49%   |
| Avell High Performance A60 | 1         | 1.49%   |
| ASUS VivoBook              | 1         | 1.49%   |
| ASUS K46CA                 | 1         | 1.49%   |
| Apple MacBookPro8          | 1         | 1.49%   |
| Apple MacBook6             | 1         | 1.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2013    | 10        | 14.93%  |
| 2019    | 8         | 11.94%  |
| 2018    | 8         | 11.94%  |
| 2020    | 7         | 10.45%  |
| 2011    | 7         | 10.45%  |
| 2016    | 4         | 5.97%   |
| 2017    | 3         | 4.48%   |
| 2015    | 3         | 4.48%   |
| 2014    | 3         | 4.48%   |
| 2009    | 3         | 4.48%   |
| 2021    | 2         | 2.99%   |
| 2012    | 2         | 2.99%   |
| 2010    | 2         | 2.99%   |
| 2007    | 2         | 2.99%   |
| Unknown | 2         | 2.99%   |
| 2022    | 1         | 1.49%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 67        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 67        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 27        | 40.3%   |
| 8.01-16.0  | 25        | 37.31%  |
| 16.01-24.0 | 8         | 11.94%  |
| 32.01-64.0 | 2         | 2.99%   |
| 3.01-4.0   | 2         | 2.99%   |
| 24.01-32.0 | 2         | 2.99%   |
| 2.01-3.0   | 1         | 1.49%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 44        | 64.71%  |
| 0.51-1.0   | 19        | 27.94%  |
| 32.01-64.0 | 1         | 1.47%   |
| 24.01-32.0 | 1         | 1.47%   |
| 2.01-3.0   | 1         | 1.47%   |
| 1.01-2.0   | 1         | 1.47%   |
| Unknown    | 1         | 1.47%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 43        | 63.24%  |
| 2      | 21        | 30.88%  |
| 0      | 4         | 5.88%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 42        | 62.69%  |
| Yes       | 25        | 37.31%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 60        | 89.55%  |
| No        | 7         | 10.45%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 64        | 95.52%  |
| No        | 3         | 4.48%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 47        | 70.15%  |
| No        | 20        | 29.85%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Brazil  | 67        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Curitiba                  | 5         | 6.94%   |
| SГЈo Paulo              | 4         | 5.56%   |
| Rio de Janeiro            | 4         | 5.56%   |
| Manaus                    | 3         | 4.17%   |
| SÃ£o Paulo              | 2         | 2.78%   |
| Maraba                    | 2         | 2.78%   |
| JoГЈo Pessoa            | 2         | 2.78%   |
| Ipojuca                   | 2         | 2.78%   |
| Campinas                  | 2         | 2.78%   |
| Belo Horizonte            | 2         | 2.78%   |
| Visconde do Rio Branco    | 1         | 1.39%   |
| Uberaba                   | 1         | 1.39%   |
| Teresopolis               | 1         | 1.39%   |
| Teresina                  | 1         | 1.39%   |
| Tangara                   | 1         | 1.39%   |
| SГЈo JosГ© dos Campos | 1         | 1.39%   |
| Sao Vicente               | 1         | 1.39%   |
| Sao Paulo                 | 1         | 1.39%   |
| Sao Jeronimo da Serra     | 1         | 1.39%   |
| Sao Bernardo do Campo     | 1         | 1.39%   |
| Santa Maria               | 1         | 1.39%   |
| Rio das Ostras            | 1         | 1.39%   |
| Porto UniГЈo            | 1         | 1.39%   |
| Porto Alegre              | 1         | 1.39%   |
| Piloezinhos               | 1         | 1.39%   |
| Paracuru                  | 1         | 1.39%   |
| Osasco                    | 1         | 1.39%   |
| Monte Belo                | 1         | 1.39%   |
| Marica                    | 1         | 1.39%   |
| Maracanau                 | 1         | 1.39%   |
| Mage                      | 1         | 1.39%   |
| Londrina                  | 1         | 1.39%   |
| Lavras                    | 1         | 1.39%   |
| Lajeado                   | 1         | 1.39%   |
| Juiz de Fora              | 1         | 1.39%   |
| Ibiuna                    | 1         | 1.39%   |
| Guapimirim                | 1         | 1.39%   |
| Goiatuba                  | 1         | 1.39%   |
| Franca                    | 1         | 1.39%   |
| Fortaleza                 | 1         | 1.39%   |
| Domingos Martins          | 1         | 1.39%   |
| Diamantino                | 1         | 1.39%   |
| Diadema                   | 1         | 1.39%   |
| Coimbra                   | 1         | 1.39%   |
| ChapecÃ³                | 1         | 1.39%   |
| Caxias do Sul             | 1         | 1.39%   |
| Cabo de Santo Agostinho   | 1         | 1.39%   |
| BrasГ­lia               | 1         | 1.39%   |
| Boa Vista do Jauato       | 1         | 1.39%   |
| Bacabal                   | 1         | 1.39%   |
| Araruama                  | 1         | 1.39%   |
| Aracaju                   | 1         | 1.39%   |
| Aparecida de Goiania      | 1         | 1.39%   |
| Alfenas                   | 1         | 1.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 16        | 17     | 19.05%  |
| Seagate             | 12        | 14     | 14.29%  |
| Kingston            | 12        | 12     | 14.29%  |
| Toshiba             | 9         | 9      | 10.71%  |
| Samsung Electronics | 6         | 6      | 7.14%   |
| Crucial             | 5         | 6      | 5.95%   |
| A-DATA Technology   | 5         | 5      | 5.95%   |
| LITEON              | 4         | 4      | 4.76%   |
| SK hynix            | 3         | 3      | 3.57%   |
| SSSTC               | 2         | 2      | 2.38%   |
| Hitachi             | 2         | 2      | 2.38%   |
| Smart               | 1         | 1      | 1.19%   |
| Silicon Motion      | 1         | 1      | 1.19%   |
| SanDisk             | 1         | 1      | 1.19%   |
| Phison              | 1         | 1      | 1.19%   |
| Patriot             | 1         | 4      | 1.19%   |
| KingSpec            | 1         | 1      | 1.19%   |
| Hikvision           | 1         | 1      | 1.19%   |
| China               | 1         | 1      | 1.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB              | 3         | 3.49%   |
| WDC WDS480G2G0B-00EPW0 480GB        | 2         | 2.33%   |
| WDC WDS240G2G0A-00JH30 240GB        | 2         | 2.33%   |
| Seagate ST1000LM048-2E7172 1TB      | 2         | 2.33%   |
| Seagate ST1000LM035-1RK172 1TB      | 2         | 2.33%   |
| Kingston SA400S37960G 960GB         | 2         | 2.33%   |
| Kingston SA400S37480G 480GB         | 2         | 2.33%   |
| Kingston SA400S37240G 240GB         | 2         | 2.33%   |
| WDC WD800BEVS-00RST0 80GB           | 1         | 1.16%   |
| WDC WD6400BEVT-22A0RT0 640GB        | 1         | 1.16%   |
| WDC WD5000LPCX-35VHAT0 500GB        | 1         | 1.16%   |
| WDC WD5000B 500GB                   | 1         | 1.16%   |
| WDC WD20SPZX-22UA7T0 2TB            | 1         | 1.16%   |
| WDC WD1600BPVT-11JJ5T0 160GB        | 1         | 1.16%   |
| WDC WD1600BEVS-60RST0 160GB         | 1         | 1.16%   |
| WDC WD10SPZX-75Z10T1 1TB            | 1         | 1.16%   |
| WDC WD10SPZX-24Z10 1TB              | 1         | 1.16%   |
| WDC WD10JPVX-75JC3T0 1TB            | 1         | 1.16%   |
| WDC WD10JPVX-35JC3T0 1TB            | 1         | 1.16%   |
| WDC WD10JPVX-22JC3T0 1TB            | 1         | 1.16%   |
| WDC WD10JPCX-24UE4T0 1TB            | 1         | 1.16%   |
| Toshiba MQ01ABD100V 1TB             | 1         | 1.16%   |
| Toshiba MK6034GSX 64GB              | 1         | 1.16%   |
| Toshiba MK3261GSYN 320GB            | 1         | 1.16%   |
| Toshiba MK2555GSXF 250GB            | 1         | 1.16%   |
| Toshiba MK1252GSX 120GB             | 1         | 1.16%   |
| Toshiba KBG30ZMV256G 256GB          | 1         | 1.16%   |
| SSSTC CL1-4D256 256GB               | 1         | 1.16%   |
| SSSTC CL1-4D128 128GB               | 1         | 1.16%   |
| Smart SSD XceedValue2 mSATA 32GB    | 1         | 1.16%   |
| SK hynix HFS128G39TND-N210A 128GB   | 1         | 1.16%   |
| SK hynix BC511 NVMe 256GB           | 1         | 1.16%   |
| SK hynix 120GB SSD                  | 1         | 1.16%   |
| Silicon Motion NE-256 256GB         | 1         | 1.16%   |
| Seagate ST9320325ASG 320GB          | 1         | 1.16%   |
| Seagate ST9250315AS 250GB           | 1         | 1.16%   |
| Seagate ST9120821AS 118GB           | 1         | 1.16%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 1.16%   |
| Seagate ST500LT012-9WS142 500GB     | 1         | 1.16%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1.16%   |
| Seagate ST2000LM007-1R8174 2TB      | 1         | 1.16%   |
| Seagate ST1000LM025 HN-M101ABB 1TB  | 1         | 1.16%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1         | 1.16%   |
| SanDisk SDSSDP256G 256GB            | 1         | 1.16%   |
| Samsung SSD 970 EVO Plus 500GB      | 1         | 1.16%   |
| Samsung SG9MSM6D024GPM00 22GB       | 1         | 1.16%   |
| Samsung HM500JJ 500GB               | 1         | 1.16%   |
| Samsung HM500JI 500GB               | 1         | 1.16%   |
| Samsung HM321HI 320GB               | 1         | 1.16%   |
| Samsung HM320II 320GB               | 1         | 1.16%   |
| Phison SWG256G-112HI 256GB          | 1         | 1.16%   |
| Patriot Burst 120GB                 | 1         | 1.16%   |
| LITEON LJH-64V2G-11 M.2 2260 64GB   | 1         | 1.16%   |
| LITEON LCH-256V2S 256GB             | 1         | 1.16%   |
| LITEON CV8-8E256-11 SATA 256GB      | 1         | 1.16%   |
| LITEON CV8-8E256 256GB              | 1         | 1.16%   |
| Kingston SUV500M8240G 240GB         | 1         | 1.16%   |
| Kingston SUV400S37120G 120GB        | 1         | 1.16%   |
| Kingston SUV300S37A120G 120GB       | 1         | 1.16%   |
| Kingston SKC300S37A240G 240GB       | 1         | 1.16%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 13        | 13     | 33.33%  |
| Seagate             | 12        | 14     | 30.77%  |
| Toshiba             | 8         | 8      | 20.51%  |
| Samsung Electronics | 4         | 4      | 10.26%  |
| Hitachi             | 2         | 2      | 5.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 11        | 11     | 33.33%  |
| WDC                 | 4         | 4      | 12.12%  |
| LITEON              | 4         | 4      | 12.12%  |
| Crucial             | 4         | 5      | 12.12%  |
| SK hynix            | 2         | 2      | 6.06%   |
| Smart               | 1         | 1      | 3.03%   |
| SanDisk             | 1         | 1      | 3.03%   |
| Samsung Electronics | 1         | 1      | 3.03%   |
| Patriot             | 1         | 4      | 3.03%   |
| KingSpec            | 1         | 1      | 3.03%   |
| Hikvision           | 1         | 1      | 3.03%   |
| China               | 1         | 1      | 3.03%   |
| A-DATA Technology   | 1         | 1      | 3.03%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 34        | 41     | 44.16%  |
| SSD  | 30        | 37     | 38.96%  |
| NVMe | 13        | 13     | 16.88%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 54        | 78     | 80.6%   |
| NVMe | 13        | 13     | 19.4%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 41        | 53     | 65.08%  |
| 0.51-1.0   | 19        | 22     | 30.16%  |
| 1.01-2.0   | 3         | 3      | 4.76%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 22        | 30.99%  |
| 101-250    | 16        | 22.54%  |
| 251-500    | 14        | 19.72%  |
| 501-1000   | 7         | 9.86%   |
| 51-100     | 4         | 5.63%   |
| 21-50      | 3         | 4.23%   |
| 1001-2000  | 3         | 4.23%   |
| 2001-3000  | 1         | 1.41%   |
| Unknown    | 1         | 1.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 54        | 79.41%  |
| 21-50    | 7         | 10.29%  |
| 501-1000 | 3         | 4.41%   |
| 101-250  | 2         | 2.94%   |
| 51-100   | 1         | 1.47%   |
| Unknown  | 1         | 1.47%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB             | 2         | 2      | 10%     |
| WDC WD5000B 500GB                  | 1         | 1      | 5%      |
| WDC WD1600BEVS-60RST0 160GB        | 1         | 1      | 5%      |
| WDC WD10JPVX-75JC3T0 1TB           | 1         | 1      | 5%      |
| Toshiba MK6034GSX 64GB             | 1         | 1      | 5%      |
| Toshiba MK3261GSYN 320GB           | 1         | 1      | 5%      |
| Toshiba MK2555GSXF 250GB           | 1         | 1      | 5%      |
| Toshiba MK1252GSX 120GB            | 1         | 1      | 5%      |
| SK hynix HFS128G39TND-N210A 128GB  | 1         | 1      | 5%      |
| Seagate ST9320325ASG 320GB         | 1         | 1      | 5%      |
| Seagate ST9250315AS 250GB          | 1         | 1      | 5%      |
| Seagate ST9120821AS 118GB          | 1         | 1      | 5%      |
| Seagate ST500LT012-9WS142 500GB    | 1         | 1      | 5%      |
| Seagate ST1000LM048-2E7172 1TB     | 1         | 1      | 5%      |
| Seagate ST1000LM025 HN-M101ABB 1TB | 1         | 1      | 5%      |
| Samsung Electronics HM321HI 320GB  | 1         | 1      | 5%      |
| LITEON LJH-64V2G-11 M.2 2260 64GB  | 1         | 1      | 5%      |
| Hitachi HTS547550A9E384 500GB      | 1         | 1      | 5%      |
| Hitachi HTS545050B9A300 500GB      | 1         | 1      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 6         | 6      | 30%     |
| Seagate             | 6         | 6      | 30%     |
| WDC                 | 3         | 3      | 15%     |
| Hitachi             | 2         | 2      | 10%     |
| SK hynix            | 1         | 1      | 5%      |
| Samsung Electronics | 1         | 1      | 5%      |
| LITEON              | 1         | 1      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 6         | 6      | 33.33%  |
| Seagate             | 6         | 6      | 33.33%  |
| WDC                 | 3         | 3      | 16.67%  |
| Hitachi             | 2         | 2      | 11.11%  |
| Samsung Electronics | 1         | 1      | 5.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 18     | 88.24%  |
| SSD  | 2         | 2      | 11.76%  |

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


| Status  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Works   | 54        | 71     | 76.06%  |
| Malfunc | 17        | 20     | 23.94%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 61        | 78.21%  |
| AMD                            | 3         | 3.85%   |
| ADATA Technology               | 3         | 3.85%   |
| Solid State Storage Technology | 2         | 2.56%   |
| Toshiba                        | 1         | 1.28%   |
| SK hynix                       | 1         | 1.28%   |
| Silicon Motion                 | 1         | 1.28%   |
| Samsung Electronics            | 1         | 1.28%   |
| Realtek Semiconductor          | 1         | 1.28%   |
| Phison Electronics             | 1         | 1.28%   |
| Nvidia                         | 1         | 1.28%   |
| Micron/Crucial Technology      | 1         | 1.28%   |
| Kingston Technology Company    | 1         | 1.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 11        | 13.75%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 8         | 10%     |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 7         | 8.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 6         | 7.5%    |
| Unknown                                                                      | 6         | 7.5%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 5         | 6.25%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                            | 3         | 3.75%   |
| Intel Comet Lake SATA AHCI Controller                                        | 2         | 2.5%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 2         | 2.5%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 2         | 2.5%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                | 2         | 2.5%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 2         | 2.5%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 2         | 2.5%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                         | 2         | 2.5%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                            | 2         | 2.5%    |
| Toshiba BG3 NVMe SSD Controller                                              | 1         | 1.25%   |
| SK hynix BC511                                                               | 1         | 1.25%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                              | 1         | 1.25%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 1         | 1.25%   |
| Phison PS5013 E13 NVMe Controller                                            | 1         | 1.25%   |
| Nvidia MCP79 AHCI Controller                                                 | 1         | 1.25%   |
| Micron/Crucial P1 NVMe PCIe SSD                                              | 1         | 1.25%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                        | 1         | 1.25%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                           | 1         | 1.25%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 1         | 1.25%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller     | 1         | 1.25%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 1         | 1.25%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                | 1         | 1.25%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 1         | 1.25%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]              | 1         | 1.25%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]              | 1         | 1.25%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller               | 1         | 1.25%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 1         | 1.25%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 60        | 75.95%  |
| NVMe | 13        | 16.46%  |
| IDE  | 4         | 5.06%   |
| RAID | 2         | 2.53%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 63        | 94.03%  |
| AMD    | 4         | 5.97%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 4.48%   |
| Intel CPU Version                             | 2         | 2.99%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 2.99%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 2.99%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 2         | 2.99%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 2.99%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 2.99%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 2.99%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 2.99%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 2.99%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 2         | 2.99%   |
| Intel Pentium M                               | 1         | 1.49%   |
| Intel Pentium CPU 5405U @ 2.30GHz             | 1         | 1.49%   |
| Intel Genuine CPU                             | 1         | 1.49%   |
| Intel Core M-5Y10c CPU @ 0.80GHz              | 1         | 1.49%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 1.49%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 1.49%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 1.49%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 1.49%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 1.49%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 1.49%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 1.49%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 1.49%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 1         | 1.49%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 1.49%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 1.49%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 1         | 1.49%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 1.49%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 1.49%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 1.49%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 1         | 1.49%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 1.49%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 1.49%   |
| Intel Core i5-2415M CPU @ 2.30GHz             | 1         | 1.49%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 1.49%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 1.49%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 1.49%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 1.49%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 1.49%   |
| Intel Core i3-3227U CPU @ 1.90GHz             | 1         | 1.49%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 1         | 1.49%   |
| Intel Core 2 Duo CPU T9300 @ 2.50GHz          | 1         | 1.49%   |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz          | 1         | 1.49%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 1         | 1.49%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 1         | 1.49%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 1         | 1.49%   |
| Intel Celeron CPU B830 @ 1.80GHz              | 1         | 1.49%   |
| Intel Celeron CPU 847 @ 1.10GHz               | 1         | 1.49%   |
| Intel Celeron CPU 3865U @ 1.80GHz             | 1         | 1.49%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 1         | 1.49%   |
| Intel Atom CPU D425 @ 1.80GHz                 | 1         | 1.49%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 1.49%   |
| AMD E1-1200 APU with Radeon HD Graphics       | 1         | 1.49%   |
| AMD E-450 APU with Radeon HD Graphics         | 1         | 1.49%   |
| AMD C-60 APU with Radeon HD Graphics          | 1         | 1.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 24        | 35.82%  |
| Intel Core i7    | 16        | 23.88%  |
| Intel Core i3    | 7         | 10.45%  |
| Intel Celeron    | 6         | 8.96%   |
| Other            | 2         | 2.99%   |
| Intel Core 2 Duo | 2         | 2.99%   |
| Intel Atom       | 2         | 2.99%   |
| Intel Pentium M  | 1         | 1.49%   |
| Intel Pentium    | 1         | 1.49%   |
| Intel Genuine    | 1         | 1.49%   |
| Intel Core M     | 1         | 1.49%   |
| AMD Ryzen 5      | 1         | 1.49%   |
| AMD E1           | 1         | 1.49%   |
| AMD E            | 1         | 1.49%   |
| AMD C-60         | 1         | 1.49%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 46        | 68.66%  |
| 4       | 13        | 19.4%   |
| 6       | 3         | 4.48%   |
| Unknown | 3         | 4.48%   |
| 8       | 1         | 1.49%   |
| 1       | 1         | 1.49%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 66        | 98.51%  |
| 2      | 1         | 1.49%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 49        | 73.13%  |
| 1       | 15        | 22.39%  |
| Unknown | 3         | 4.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 17        | 25.37%  |
| SandyBridge   | 9         | 13.43%  |
| Broadwell     | 7         | 10.45%  |
| IvyBridge     | 6         | 8.96%   |
| Haswell       | 5         | 7.46%   |
| Penryn        | 4         | 5.97%   |
| Westmere      | 3         | 4.48%   |
| Skylake       | 3         | 4.48%   |
| Bobcat        | 3         | 4.48%   |
| Goldmont plus | 2         | 2.99%   |
| CometLake     | 2         | 2.99%   |
| Bonnell       | 2         | 2.99%   |
| Zen+          | 1         | 1.49%   |
| IceLake       | 1         | 1.49%   |
| Goldmont      | 1         | 1.49%   |
| Core          | 1         | 1.49%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 60        | 72.29%  |
| Nvidia | 16        | 19.28%  |
| AMD    | 7         | 8.43%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 8         | 9.41%   |
| Intel HD Graphics 5500                                                        | 6         | 7.06%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 6         | 7.06%   |
| Intel UHD Graphics 620                                                        | 5         | 5.88%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 5         | 5.88%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 3         | 3.53%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 3         | 3.53%   |
| Intel HD Graphics 620                                                         | 3         | 3.53%   |
| Intel Core Processor Integrated Graphics Controller                           | 3         | 3.53%   |
| Nvidia TU117M                                                                 | 2         | 2.35%   |
| Nvidia GP108M [GeForce MX250]                                                 | 2         | 2.35%   |
| Nvidia GM108M [GeForce MX130]                                                 | 2         | 2.35%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 2         | 2.35%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 2         | 2.35%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 2         | 2.35%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 2         | 2.35%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 1         | 1.18%   |
| Nvidia GP108M [GeForce MX230]                                                 | 1         | 1.18%   |
| Nvidia GM108M [GeForce MX110]                                                 | 1         | 1.18%   |
| Nvidia GM108M [GeForce 940MX]                                                 | 1         | 1.18%   |
| Nvidia GM107M [GeForce GTX 950M]                                              | 1         | 1.18%   |
| Nvidia GK208M [GeForce GT 740M]                                               | 1         | 1.18%   |
| Nvidia GK208BM [GeForce 920M]                                                 | 1         | 1.18%   |
| Nvidia GF119M [GeForce 410M]                                                  | 1         | 1.18%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 1         | 1.18%   |
| Nvidia C79 [GeForce 9400M]                                                    | 1         | 1.18%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 1         | 1.18%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 1         | 1.18%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 1.18%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 1         | 1.18%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                          | 1         | 1.18%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 1         | 1.18%   |
| Intel HD Graphics 630                                                         | 1         | 1.18%   |
| Intel HD Graphics 5300                                                        | 1         | 1.18%   |
| Intel HD Graphics 500                                                         | 1         | 1.18%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 1         | 1.18%   |
| Intel Coffee Lake UHD 610 Graphics Controller                                 | 1         | 1.18%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 1         | 1.18%   |
| AMD Wrestler [Radeon HD 7310]                                                 | 1         | 1.18%   |
| AMD Wrestler [Radeon HD 6320]                                                 | 1         | 1.18%   |
| AMD Wrestler [Radeon HD 6290]                                                 | 1         | 1.18%   |
| AMD RV515/M54 [Mobility Radeon X1400]                                         | 1         | 1.18%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 1         | 1.18%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                    | 1         | 1.18%   |
| AMD Chelsea LP [Radeon HD 7730M]                                              | 1         | 1.18%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 39        | 58.21%  |
| Intel + Nvidia | 14        | 20.9%   |
| 2 x Intel      | 5         | 7.46%   |
| 1 x AMD        | 5         | 7.46%   |
| 1 x Nvidia     | 2         | 2.99%   |
| Intel + AMD    | 2         | 2.99%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 63        | 94.03%  |
| Proprietary | 3         | 4.48%   |
| Unknown     | 1         | 1.49%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 60        | 89.55%  |
| 0.01-0.5   | 4         | 5.97%   |
| 3.01-4.0   | 2         | 2.99%   |
| 1.01-2.0   | 1         | 1.49%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 19        | 30.65%  |
| LG Display          | 10        | 16.13%  |
| BOE                 | 7         | 11.29%  |
| Chimei Innolux      | 6         | 9.68%   |
| Samsung Electronics | 4         | 6.45%   |
| Lenovo              | 3         | 4.84%   |
| InfoVision          | 3         | 4.84%   |
| Dell                | 3         | 4.84%   |
| AOC                 | 2         | 3.23%   |
| Philips             | 1         | 1.61%   |
| PANDA               | 1         | 1.61%   |
| Hewlett-Packard     | 1         | 1.61%   |
| Goldstar            | 1         | 1.61%   |
| Apple               | 1         | 1.61%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch         | 4         | 6.45%   |
| LG Display LCD Monitor LGD0385 1366x768 310x170mm 13.9-inch           | 3         | 4.84%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch          | 2         | 3.23%   |
| BOE LCD Monitor BOE0757 1366x768 340x190mm 15.3-inch                  | 2         | 3.23%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch         | 2         | 3.23%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 340x190mm 15.3-inch         | 2         | 3.23%   |
| AU Optronics LCD Monitor AUO303C 1366x768 310x170mm 13.9-inch         | 2         | 3.23%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 330x210mm 15.4-inch  | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SEC414C 1366x768 310x170mm 13.9-inch  | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 310x170mm 13.9-inch  | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch | 1         | 1.61%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                | 1         | 1.61%   |
| PANDA LCD Monitor NCP0004 1920x1080 290x170mm 13.2-inch               | 1         | 1.61%   |
| LG Display LCD Monitor LGD05B1 1920x1080 310x170mm 13.9-inch          | 1         | 1.61%   |
| LG Display LCD Monitor LGD053C 1920x1080 310x170mm 13.9-inch          | 1         | 1.61%   |
| LG Display LCD Monitor LGD0458 1366x768 310x170mm 13.9-inch           | 1         | 1.61%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch           | 1         | 1.61%   |
| LG Display LCD Monitor LGD0230 1366x768 340x190mm 15.3-inch           | 1         | 1.61%   |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                 | 1         | 1.61%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch               | 1         | 1.61%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch               | 1         | 1.61%   |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch          | 1         | 1.61%   |
| InfoVision LCD Monitor IVO0579 1366x768 310x170mm 13.9-inch           | 1         | 1.61%   |
| InfoVision LCD Monitor IVO03F4 1024x600 220x130mm 10.1-inch           | 1         | 1.61%   |
| Hewlett-Packard L200hx HWP298F 1600x900 450x250mm 20.3-inch           | 1         | 1.61%   |
| Goldstar LCD Monitor GSM580D 1920x1080 510x290mm 23.1-inch            | 1         | 1.61%   |
| Dell S2419HGF DELD0E1 1920x1080 530x300mm 24.0-inch                   | 1         | 1.61%   |
| Dell P2419H DELD0D9 1920x1080 530x300mm 24.0-inch                     | 1         | 1.61%   |
| Dell P2418D DELD0C1 2560x1440 530x300mm 24.0-inch                     | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 340x190mm 15.3-inch      | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 340x190mm 15.3-inch       | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 340x190mm 15.3-inch       | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN1496 1366x768 310x170mm 13.9-inch       | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 310x170mm 13.9-inch       | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN1119 1366x768 260x140mm 11.6-inch       | 1         | 1.61%   |
| BOE LCD Monitor BOE0747 1920x1080 340x190mm 15.3-inch                 | 1         | 1.61%   |
| BOE LCD Monitor BOE0698 1366x768 310x170mm 13.9-inch                  | 1         | 1.61%   |
| BOE LCD Monitor BOE0690 1920x1080 340x190mm 15.3-inch                 | 1         | 1.61%   |
| BOE LCD Monitor BOE05E0 1366x768 280x160mm 12.7-inch                  | 1         | 1.61%   |
| BOE LCD Monitor BOE05B1 1366x768 310x170mm 13.9-inch                  | 1         | 1.61%   |
| AU Optronics LCD Monitor AUO45ED 1920x1080 340x190mm 15.3-inch        | 1         | 1.61%   |
| AU Optronics LCD Monitor AUO44EC 1366x768 340x190mm 15.3-inch         | 1         | 1.61%   |
| AU Optronics LCD Monitor AUO423D 1920x1080 310x170mm 13.9-inch        | 1         | 1.61%   |
| AU Optronics LCD Monitor AUO323C 1366x768 310x170mm 13.9-inch         | 1         | 1.61%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 310x170mm 13.9-inch         | 1         | 1.61%   |
| AU Optronics LCD Monitor AUO263D 1920x1080 310x170mm 13.9-inch        | 1         | 1.61%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 340x190mm 15.3-inch         | 1         | 1.61%   |
| AU Optronics LCD Monitor AUO183C 1366x768 310x170mm 13.9-inch         | 1         | 1.61%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch        | 1         | 1.61%   |
| Apple LCD Monitor APP9CC5 1280x800 290x180mm 13.4-inch                | 1         | 1.61%   |
| AOC T2242we AOC2242 1920x1080 480x270mm 21.7-inch                     | 1         | 1.61%   |
| AOC 936W AOC1936 1366x768 410x230mm 18.5-inch                         | 1         | 1.61%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1366x768 (WXGA) | 36        | 61.02%  |
| 1920x1080 (FHD) | 17        | 28.81%  |
| 1280x800 (WXGA) | 3         | 5.08%   |
| 2560x1440 (QHD) | 1         | 1.69%   |
| 1600x900 (HD+)  | 1         | 1.69%   |
| 1024x600        | 1         | 1.69%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 23        | 37.1%   |
| 15     | 22        | 35.48%  |
| 24     | 4         | 6.45%   |
| 12     | 4         | 6.45%   |
| 18     | 2         | 3.23%   |
| 14     | 2         | 3.23%   |
| 23     | 1         | 1.61%   |
| 21     | 1         | 1.61%   |
| 20     | 1         | 1.61%   |
| 11     | 1         | 1.61%   |
| 10     | 1         | 1.61%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 43        | 69.35%  |
| 201-300     | 10        | 16.13%  |
| 501-600     | 5         | 8.06%   |
| 401-500     | 4         | 6.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 50        | 92.59%  |
| 16/10 | 4         | 7.41%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 24        | 38.71%  |
| 91-100         | 21        | 33.87%  |
| 201-250        | 6         | 9.68%   |
| 61-70          | 4         | 6.45%   |
| 141-150        | 2         | 3.23%   |
| 71-80          | 1         | 1.61%   |
| 51-60          | 1         | 1.61%   |
| 41-50          | 1         | 1.61%   |
| 151-200        | 1         | 1.61%   |
| 101-110        | 1         | 1.61%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 35        | 58.33%  |
| 121-160 | 14        | 23.33%  |
| 51-100  | 8         | 13.33%  |
| 161-240 | 3         | 5%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 49        | 73.13%  |
| 0     | 10        | 14.93%  |
| 2     | 8         | 11.94%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 35        | 31.82%  |
| Qualcomm Atheros      | 28        | 25.45%  |
| Intel                 | 25        | 22.73%  |
| Broadcom              | 10        | 9.09%   |
| JMicron Technology    | 5         | 4.55%   |
| Samsung Electronics   | 3         | 2.73%   |
| TP-Link               | 1         | 0.91%   |
| Ralink Technology     | 1         | 0.91%   |
| Nvidia                | 1         | 0.91%   |
| MediaTek              | 1         | 0.91%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 12.31%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 10.77%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 8         | 6.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 5.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 6         | 4.62%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 4         | 3.08%   |
| Intel Wireless 8265 / 8275                                        | 4         | 3.08%   |
| Intel Wireless 7265                                               | 4         | 3.08%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 3         | 2.31%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 3         | 2.31%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 2.31%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 2.31%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.54%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 1.54%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 1.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.54%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 2         | 1.54%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 2         | 1.54%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.54%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 1.54%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 1.54%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.54%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.77%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.77%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.77%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                            | 1         | 0.77%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.77%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1         | 0.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.77%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.77%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.77%   |
| MediaTek USB Ethernet-RNDIS                                       | 1         | 0.77%   |
| Intel Wireless 8260                                               | 1         | 0.77%   |
| Intel Wireless 7260                                               | 1         | 0.77%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 0.77%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 1         | 0.77%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 1         | 0.77%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 1         | 0.77%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.77%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.77%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.77%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1         | 0.77%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 0.77%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 0.77%   |
| Intel Centrino Advanced-N 6200                                    | 1         | 0.77%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 0.77%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.77%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 0.77%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.77%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 0.77%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.77%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 0.77%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 1         | 0.77%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 1         | 0.77%   |
| Broadcom BCM43225 802.11b/g/n                                     | 1         | 0.77%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 1         | 0.77%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Qualcomm Atheros      | 27        | 40.3%   |
| Intel                 | 25        | 37.31%  |
| Realtek Semiconductor | 9         | 13.43%  |
| Broadcom              | 4         | 5.97%   |
| TP-Link               | 1         | 1.49%   |
| Ralink Technology     | 1         | 1.49%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 8         | 11.76%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 7         | 10.29%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 6         | 8.82%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 4         | 5.88%   |
| Intel Wireless 8265 / 8275                                     | 4         | 5.88%   |
| Intel Wireless 7265                                            | 4         | 5.88%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 3         | 4.41%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 2.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 2.94%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 2         | 2.94%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 2.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 2.94%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 1.47%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 1.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.47%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                         | 1         | 1.47%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 1.47%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 1.47%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.47%   |
| Intel Wireless 8260                                            | 1         | 1.47%   |
| Intel Wireless 7260                                            | 1         | 1.47%   |
| Intel Wi-Fi 6 AX200                                            | 1         | 1.47%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 1         | 1.47%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 1.47%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 1         | 1.47%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 1.47%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 1.47%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 1.47%   |
| Intel Centrino Advanced-N 6200                                 | 1         | 1.47%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 1.47%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 1         | 1.47%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 1         | 1.47%   |
| Broadcom BCM43225 802.11b/g/n                                  | 1         | 1.47%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 1         | 1.47%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 30        | 49.18%  |
| Intel                 | 12        | 19.67%  |
| Broadcom              | 7         | 11.48%  |
| JMicron Technology    | 5         | 8.2%    |
| Samsung Electronics   | 3         | 4.92%   |
| Qualcomm Atheros      | 3         | 4.92%   |
| Nvidia                | 1         | 1.64%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 26.23%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 22.95%  |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 3         | 4.92%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 4.92%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 4.92%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 3.28%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 3.28%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 2         | 3.28%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 3.28%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 3.28%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.64%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.64%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.64%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.64%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.64%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.64%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.64%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.64%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.64%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 1.64%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.64%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 1.64%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 64        | 51.2%   |
| Ethernet | 60        | 48%     |
| Modem    | 1         | 0.8%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 52        | 52.53%  |
| WiFi     | 47        | 47.47%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 55        | 82.09%  |
| 1     | 12        | 17.91%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 64        | 95.52%  |
| Yes  | 3         | 4.48%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 17        | 36.17%  |
| Qualcomm Atheros Communications | 14        | 29.79%  |
| Broadcom                        | 4         | 8.51%   |
| Lite-On Technology              | 3         | 6.38%   |
| Apple                           | 3         | 6.38%   |
| Realtek Semiconductor           | 2         | 4.26%   |
| Foxconn / Hon Hai               | 2         | 4.26%   |
| IMC Networks                    | 1         | 2.13%   |
| Dell                            | 1         | 2.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 8         | 17.02%  |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 5         | 10.64%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 5         | 10.64%  |
| Qualcomm Atheros AR9462 Bluetooth                           | 4         | 8.51%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 2         | 4.26%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 2         | 4.26%   |
| Intel AX201 Bluetooth                                       | 2         | 4.26%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 4.26%   |
| Apple Bluetooth Host Controller                             | 2         | 4.26%   |
| Realtek  Bluetooth Adapter                                  | 1         | 2.13%   |
| Realtek CSR Bluetooth Chip                                  | 1         | 2.13%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 2.13%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 2.13%   |
| Lite-On Atheros Bluetooth                                   | 1         | 2.13%   |
| Lite-On Atheros AR3012 Bluetooth                            | 1         | 2.13%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 2.13%   |
| Intel AX200 Bluetooth                                       | 1         | 2.13%   |
| IMC Networks Bluetooth Module                               | 1         | 2.13%   |
| Foxconn / Hon Hai Qualcomm Atheros Bluetooth 4.0            | 1         | 2.13%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 2.13%   |
| Dell Wireless 355 Bluetooth                                 | 1         | 2.13%   |
| Broadcom BCM2046 Bluetooth Device                           | 1         | 2.13%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 1         | 2.13%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 1         | 2.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Intel    | 62        | 83.78%  |
| Nvidia   | 5         | 6.76%   |
| AMD      | 4         | 5.41%   |
| M-Audio  | 1         | 1.35%   |
| Logitech | 1         | 1.35%   |
| Lenovo   | 1         | 1.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 12        | 13.48%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9         | 10.11%  |
| Intel Broadwell-U Audio Controller                                         | 7         | 7.87%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 6         | 6.74%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6         | 6.74%   |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 5.62%   |
| Intel 8 Series HD Audio Controller                                         | 5         | 5.62%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 4.49%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 3.37%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 3.37%   |
| AMD Wrestler HDMI Audio                                                    | 3         | 3.37%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 2.25%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 2.25%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 2.25%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 2.25%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 2.25%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 2.25%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 1.12%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 1.12%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 1.12%   |
| M-Audio M-Audio Fast Track Pro                                             | 1         | 1.12%   |
| Logitech H390 headset with microphone                                      | 1         | 1.12%   |
| Lenovo Realtek USB Audio                                                   | 1         | 1.12%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 1.12%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.12%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 1.12%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.12%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 1.12%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 1.12%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.12%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1         | 1.12%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Smart               | 18        | 23.38%  |
| Samsung Electronics | 10        | 12.99%  |
| SK hynix            | 8         | 10.39%  |
| Kingston            | 8         | 10.39%  |
| Unknown             | 6         | 7.79%   |
| Teikon              | 6         | 7.79%   |
| A-DATA Technology   | 5         | 6.49%   |
| Smart Brazil        | 4         | 5.19%   |
| High Bridge         | 3         | 3.9%    |
| Micron Technology   | 2         | 2.6%    |
| Crucial             | 2         | 2.6%    |
| Apacer              | 2         | 2.6%    |
| Unknown (ABCD)      | 1         | 1.3%    |
| PNY                 | 1         | 1.3%    |
| Nanya Technology    | 1         | 1.3%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s                       | 4         | 5%      |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s                       | 3         | 3.75%   |
| Smart RAM SH564128FJ8NZRNSDG 4GB SODIMM DDR3 1600MT/s                       | 2         | 2.5%    |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s                       | 2         | 2.5%    |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s                       | 2         | 2.5%    |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s                       | 2         | 2.5%    |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2400MT/s                | 2         | 2.5%    |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s                       | 2         | 2.5%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s                       | 2         | 2.5%    |
| Unknown SODIMM 2048MB SODIMM DDR2 667MT/s                                   | 1         | 1.25%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                                 | 1         | 1.25%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                                 | 1         | 1.25%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                                 | 1         | 1.25%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                                  | 1         | 1.25%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                  | 1         | 1.25%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2133MT/s            | 1         | 1.25%   |
| Teikon RAM TMT451S6BFR8A-PBSC 4096MB SODIMM DDR3 1600MT/s                   | 1         | 1.25%   |
| Teikon RAM TMT451S6BFR8A-PBHC 4GB SODIMM DDR3 1333MT/s                      | 1         | 1.25%   |
| Teikon RAM TMT41GS6BFR8A-PBSC 8GB SODIMM DDR3 1600MT/s                      | 1         | 1.25%   |
| Teikon RAM TMT225S6FR8C-H9HC 2GB SODIMM DDR3 1334MT/s                       | 1         | 1.25%   |
| Teikon RAM TML251S6EFR8A-PBHC 4096MB SODIMM DDR3 1600MT/s                   | 1         | 1.25%   |
| Teikon RAM TMA81GS6AFR8N-UHSC 8GB SODIMM DDR4 2400MT/s                      | 1         | 1.25%   |
| Smart RAM SH564568FH8NWPHSFR 2GB SODIMM DDR3 1333MT/s                       | 1         | 1.25%   |
| Smart RAM SH564128FJ8NZRNSDR 4GB SODIMM DDR3 1600MT/s                       | 1         | 1.25%   |
| Smart RAM SF4641G8CK8IWGKSEG 8GB SODIMM DDR4 2133MT/s                       | 1         | 1.25%   |
| Smart RAM SF464128CKHIWDFSEG 4GB SODIMM DDR4 2133MT/s                       | 1         | 1.25%   |
| Smart Brazil RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2133MT/s                | 1         | 1.25%   |
| Smart Brazil RAM Module 4GB Row Of Chips DDR4 2400MT/s                      | 1         | 1.25%   |
| SK hynix RAM HYMP512S64CP8-C4 1GB SODIMM DDR 533MT/s                        | 1         | 1.25%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s                       | 1         | 1.25%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 800MT/s                       | 1         | 1.25%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                      | 1         | 1.25%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                      | 1         | 1.25%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                      | 1         | 1.25%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s                      | 1         | 1.25%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s                      | 1         | 1.25%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s                     | 1         | 1.25%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s                       | 1         | 1.25%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 1067MT/s                       | 1         | 1.25%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                       | 1         | 1.25%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                       | 1         | 1.25%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2400MT/s                      | 1         | 1.25%   |
| Samsung RAM K4E6E304EB-EGCG 4096MB SODIMM DDR3 1600MT/s                     | 1         | 1.25%   |
| Samsung RAM K4B8G1646B-MYK0 4GB SODIMM DDR3 1600MT/s                        | 1         | 1.25%   |
| PNY RAM 16GU2X16LIII43-12-K 16GB SODIMM DDR4 2667MT/s                       | 1         | 1.25%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s                        | 1         | 1.25%   |
| Micron RAM A0B4CDD4C6B2B5B6B6B4C8DAADB1C7B6C5B1 2048MB SODIMM DDR3 1600MT/s | 1         | 1.25%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                        | 1         | 1.25%   |
| Kingston RAM Module 4GB SODIMM DDR3 1333MT/s                                | 1         | 1.25%   |
| Kingston RAM Module 2048MB SODIMM DDR3 1333MT/s                             | 1         | 1.25%   |
| Kingston RAM KHX2400C14S4/16G 16GB SODIMM DDR4 2400MT/s                     | 1         | 1.25%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s                       | 1         | 1.25%   |
| Kingston RAM KF2666C16S4/16G 16GB SODIMM DDR4 2667MT/s                      | 1         | 1.25%   |
| Kingston RAM 99U5428-040.A01LF 4GB SODIMM DDR3 1333MT/s                     | 1         | 1.25%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.25%   |
| Kingston RAM 9905428-416.A00LF 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.25%   |
| High Bridge RAM HB3SU002GFM8MMD33 2GB SODIMM DDR3 1333MT/s                  | 1         | 1.25%   |
| High Bridge RAM HB3SU002GFM8MMB33. 2048MB SODIMM DDR3 1334MT/s              | 1         | 1.25%   |
| High Bridge RAM HB3SU002GFM8DMA33. 2GB SODIMM DDR3 1333MT/s                 | 1         | 1.25%   |
| Crucial RAM CT16G4SFS8266.C8FB 16GB SODIMM DDR4 2667MT/s                    | 1         | 1.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 34        | 55.74%  |
| DDR4   | 20        | 32.79%  |
| DDR2   | 5         | 8.2%    |
| LPDDR4 | 1         | 1.64%   |
| DDR    | 1         | 1.64%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 59        | 98.33%  |
| Row Of Chips | 1         | 1.67%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 30        | 42.25%  |
| 2048  | 18        | 25.35%  |
| 8192  | 14        | 19.72%  |
| 16384 | 8         | 11.27%  |
| 1024  | 1         | 1.41%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 20        | 28.99%  |
| 2400  | 10        | 14.49%  |
| 1333  | 10        | 14.49%  |
| 2667  | 9         | 13.04%  |
| 1334  | 8         | 11.59%  |
| 2133  | 4         | 5.8%    |
| 800   | 2         | 2.9%    |
| 667   | 2         | 2.9%    |
| 533   | 2         | 2.9%    |
| 1067  | 1         | 1.45%   |
| 975   | 1         | 1.45%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| ELGIN  | 2         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model        | Notebooks | Percent |
|--------------|-----------|---------|
| ELGIN L42PRO | 2         | 100%    |

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


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 14        | 24.14%  |
| Acer                          | 8         | 13.79%  |
| Realtek Semiconductor         | 7         | 12.07%  |
| Silicon Motion                | 5         | 8.62%   |
| Microdia                      | 5         | 8.62%   |
| IMC Networks                  | 3         | 5.17%   |
| Syntek                        | 2         | 3.45%   |
| Suyin                         | 2         | 3.45%   |
| Sunplus Innovation Technology | 2         | 3.45%   |
| Logitech                      | 2         | 3.45%   |
| Alcor Micro                   | 2         | 3.45%   |
| Unknown                       | 1         | 1.72%   |
| Quanta                        | 1         | 1.72%   |
| Luxvisions Innotech Limited   | 1         | 1.72%   |
| Lite-On Technology            | 1         | 1.72%   |
| Lenovo                        | 1         | 1.72%   |
| Apple                         | 1         | 1.72%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Silicon Motion Web Camera                     | 4         | 6.78%   |
| Chicony HD WebCam                             | 4         | 6.78%   |
| Acer Integrated Camera                        | 4         | 6.78%   |
| Realtek Integrated_Webcam_HD                  | 3         | 5.08%   |
| Syntek EasyCamera                             | 2         | 3.39%   |
| Realtek Integrated Webcam                     | 2         | 3.39%   |
| Microdia Dell Laptop Integrated Webcam HD     | 2         | 3.39%   |
| Chicony Sony Visual Communication Camera      | 2         | 3.39%   |
| Alcor Micro Acer Integrated Webcam            | 2         | 3.39%   |
| Acer HD Webcam                                | 2         | 3.39%   |
| Unknown Realtek PC Camera                     | 1         | 1.69%   |
| Suyin USB 2.0 UVC 1.3M WebCam                 | 1         | 1.69%   |
| Suyin Integrated_Webcam_HD                    | 1         | 1.69%   |
| Sunplus Integrated_Webcam_HD                  | 1         | 1.69%   |
| Sunplus HD WebCam                             | 1         | 1.69%   |
| Silicon Motion WebCam SCX Series              | 1         | 1.69%   |
| Realtek LG Camera                             | 1         | 1.69%   |
| Realtek Integrated_Webcam_FHD                 | 1         | 1.69%   |
| Realtek Integrated_Webcam_8M                  | 1         | 1.69%   |
| Quanta HD Webcam                              | 1         | 1.69%   |
| Microdia Laptop_Integrated_Webcam_HD          | 1         | 1.69%   |
| Microdia Integrated_Webcam_HD                 | 1         | 1.69%   |
| Microdia Integrated Webcam HD                 | 1         | 1.69%   |
| Luxvisions Innotech Limited Integrated Camera | 1         | 1.69%   |
| Logitech Webcam C270                          | 1         | 1.69%   |
| Logitech C922 Pro Stream Webcam               | 1         | 1.69%   |
| Lite-On Integrated Camera                     | 1         | 1.69%   |
| Lenovo Integrated Webcam [R5U877]             | 1         | 1.69%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 1         | 1.69%   |
| IMC Networks USB Camera                       | 1         | 1.69%   |
| IMC Networks EasyCamera                       | 1         | 1.69%   |
| Chicony Webcam                                | 1         | 1.69%   |
| Chicony Sonix ST50220 USB Video Camera        | 1         | 1.69%   |
| Chicony Lenovo Integrated Camera (0.3MP)      | 1         | 1.69%   |
| Chicony Integrated Camera                     | 1         | 1.69%   |
| Chicony HP HD Webcam [Fixed]                  | 1         | 1.69%   |
| Chicony HP HD Camera                          | 1         | 1.69%   |
| Chicony EasyCamera                            | 1         | 1.69%   |
| Chicony 1.3M Webcam                           | 1         | 1.69%   |
| Apple FaceTime HD Camera                      | 1         | 1.69%   |
| Acer SunplusIT Integrated Camera              | 1         | 1.69%   |
| Acer Lenovo EasyCamera                        | 1         | 1.69%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 40%     |
| Upek                       | 2         | 20%     |
| Synaptics                  | 2         | 20%     |
| Shenzhen Goodix Technology | 1         | 10%     |
| Samsung Electronics        | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor      | 2         | 20%     |
| Validity Sensors VFS495 Fingerprint Reader                  | 1         | 10%     |
| Validity Sensors VFS 5011 fingerprint sensor                | 1         | 10%     |
| Validity Sensors Synaptics WBDI                             | 1         | 10%     |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor | 1         | 10%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader           | 1         | 10%     |
| Synaptics Metallica MOH Touch Fingerprint Reader            | 1         | 10%     |
| Shenzhen Goodix Fingerprint Reader                          | 1         | 10%     |
| Samsung Fingerprint Device                                  | 1         | 10%     |

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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 19        | 27.94%  |
| 1     | 18        | 26.47%  |
| 3     | 12        | 17.65%  |
| 0     | 10        | 14.71%  |
| 5     | 5         | 7.35%   |
| 4     | 4         | 5.88%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 55        | 44.72%  |
| Card reader              | 25        | 20.33%  |
| Net/wireless             | 16        | 13.01%  |
| Bluetooth                | 15        | 12.2%   |
| Fingerprint reader       | 10        | 8.13%   |
| Sound                    | 2         | 1.63%   |

