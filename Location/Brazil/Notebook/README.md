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

Total: 78

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| helloSystem 0.6.0    | 10        | 15.15%  |
| helloSystem 0.4.0    | 10        | 15.15%  |
| helloSystem 0.5.0    | 9         | 13.64%  |
| helloSystem 0.7.0    | 6         | 9.09%   |
| FreeBSD 13.0         | 5         | 7.58%   |
| FreeBSD 14.0-CURRENT | 3         | 4.55%   |
| FreeBSD 13.0-p3      | 3         | 4.55%   |
| helloSystem 0.8.0    | 2         | 3.03%   |
| FreeBSD 13.0-STABLE  | 2         | 3.03%   |
| FreeBSD 12.1         | 2         | 3.03%   |
| OS108 9.99.68        | 1         | 1.52%   |
| OpenBSD 7.0          | 1         | 1.52%   |
| OpenBSD 6.9          | 1         | 1.52%   |
| helloSystem 0.3.0    | 1         | 1.52%   |
| GhostBSD 20.04.02    | 1         | 1.52%   |
| FreeBSD 13.0-RC2     | 1         | 1.52%   |
| FreeBSD 13.0-p7      | 1         | 1.52%   |
| FreeBSD 13.0-p4      | 1         | 1.52%   |
| FreeBSD 13.0-CURRENT | 1         | 1.52%   |
| FreeBSD 12.2-p3      | 1         | 1.52%   |
| FreeBSD 12.2         | 1         | 1.52%   |
| FreeBSD 12.1-p7      | 1         | 1.52%   |
| FreeBSD 12.1-p11     | 1         | 1.52%   |
| DragonFly 5.8        | 1         | 1.52%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| helloSystem | 35        | 55.56%  |
| FreeBSD     | 23        | 36.51%  |
| OpenBSD     | 2         | 3.17%   |
| OS108       | 1         | 1.59%   |
| GhostBSD    | 1         | 1.59%   |
| DragonFly   | 1         | 1.59%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 60        | 98.36%  |
| i386  | 1         | 1.64%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 34        | 53.97%  |
| Console      | 5         | 7.94%   |
| XFCE         | 4         | 6.35%   |
| MATE         | 4         | 6.35%   |
| KDE5         | 4         | 6.35%   |
| GNOME        | 4         | 6.35%   |
| i3           | 2         | 3.17%   |
| fvwm         | 2         | 3.17%   |
| TWM          | 1         | 1.59%   |
| spectrwm     | 1         | 1.59%   |
| Openbox      | 1         | 1.59%   |
| LXQt         | 1         | 1.59%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 57        | 93.44%  |
| Console | 4         | 6.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 39        | 61.9%   |
| Console | 10        | 15.87%  |
| LightDM | 5         | 7.94%   |
| SDDM    | 4         | 6.35%   |
| XDM     | 3         | 4.76%   |
| GDM     | 2         | 3.17%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| en_US           | 39        | 61.9%   |
| C               | 10        | 15.87%  |
| Unknown         | 8         | 12.7%   |
| pt_BR           | 4         | 6.35%   |
| en_US.ISO8859-1 | 1         | 1.59%   |
| en_GB           | 1         | 1.59%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 50        | 81.97%  |
| BIOS | 11        | 18.03%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Zfs     | 48        | 75%     |
| Ufs     | 9         | 14.06%  |
| Cd9660  | 4         | 6.25%   |
| Ffs     | 2         | 3.13%   |
| Hammer2 | 1         | 1.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 59        | 96.72%  |
| MBR     | 1         | 1.64%   |
| Unknown | 1         | 1.64%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 14        | 22.95%  |
| Dell                   | 13        | 21.31%  |
| Acer                   | 7         | 11.48%  |
| Samsung Electronics    | 5         | 8.2%    |
| Avell High Performance | 3         | 4.92%   |
| Sony                   | 2         | 3.28%   |
| Itautec                | 2         | 3.28%   |
| Hewlett-Packard        | 2         | 3.28%   |
| Gateway                | 2         | 3.28%   |
| Apple                  | 2         | 3.28%   |
| Unknown                | 2         | 3.28%   |
| Semp Toshiba           | 1         | 1.64%   |
| Positivo               | 1         | 1.64%   |
| Philco                 | 1         | 1.64%   |
| Notebook               | 1         | 1.64%   |
| LG Electronics         | 1         | 1.64%   |
| Clevo                  | 1         | 1.64%   |
| ASUSTek Computer       | 1         | 1.64%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Dell Inspiron 3442                          | 3         | 4.92%   |
| Gateway NE56R                               | 2         | 3.28%   |
| Acer Aspire 5750                            | 2         | 3.28%   |
| Unknown                                     | 2         | 3.28%   |
| Sony VPCYB45JB                              | 1         | 1.64%   |
| Sony VPCEG17FB                              | 1         | 1.64%   |
| Semp Toshiba STI NA 1401                    | 1         | 1.64%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 1         | 1.64%   |
| Samsung 530XBB                              | 1         | 1.64%   |
| Samsung 340XAA/350XAA/550XAA                | 1         | 1.64%   |
| Samsung 300E5M/300E5L                       | 1         | 1.64%   |
| Samsung 270E5K/270E5Q/271E5K/2570EK         | 1         | 1.64%   |
| Positivo C14CR01                            | 1         | 1.64%   |
| Philco 10B                                  | 1         | 1.64%   |
| Notebook N85_N87HCHNHZ                      | 1         | 1.64%   |
| LG 14Z980-G.BH51P1                          | 1         | 1.64%   |
| Lenovo ThinkPad X270 20HM004JBR             | 1         | 1.64%   |
| Lenovo ThinkPad X250 20CLS2A11K             | 1         | 1.64%   |
| Lenovo ThinkPad X250 20CLS18S0Z             | 1         | 1.64%   |
| Lenovo ThinkPad X240 20AMS4V000             | 1         | 1.64%   |
| Lenovo ThinkPad X220 4291ON5                | 1         | 1.64%   |
| Lenovo ThinkPad T490 20N30029BR             | 1         | 1.64%   |
| Lenovo ThinkPad T450s 20BWS05G0T            | 1         | 1.64%   |
| Lenovo ThinkPad T430 2349PMP                | 1         | 1.64%   |
| Lenovo ThinkPad T410 2522CS7                | 1         | 1.64%   |
| Lenovo ThinkPad E490 20N9001SBR             | 1         | 1.64%   |
| Lenovo IdeaPad S145-15IWL 81S9              | 1         | 1.64%   |
| Lenovo IdeaPad S145-15IWL 81MV              | 1         | 1.64%   |
| Lenovo IdeaPad 3 15IGL05 82BU               | 1         | 1.64%   |
| Lenovo G550 2958                            | 1         | 1.64%   |
| Itautec Infoway w7535                       | 1         | 1.64%   |
| Itautec Infoway w7530                       | 1         | 1.64%   |
| HP EliteBook 840 G3                         | 1         | 1.64%   |
| HP 14                                       | 1         | 1.64%   |
| Dell Vostro 5490                            | 1         | 1.64%   |
| Dell Venue 11 Pro 7140                      | 1         | 1.64%   |
| Dell Latitude 5490                          | 1         | 1.64%   |
| Dell Latitude 3490                          | 1         | 1.64%   |
| Dell Inspiron 7520                          | 1         | 1.64%   |
| Dell Inspiron 7460                          | 1         | 1.64%   |
| Dell Inspiron 5566                          | 1         | 1.64%   |
| Dell Inspiron 5437                          | 1         | 1.64%   |
| Dell Inspiron 3543                          | 1         | 1.64%   |
| Dell Inspiron 3421                          | 1         | 1.64%   |
| Clevo C41X0                                 | 1         | 1.64%   |
| Avell High Performance A62 LIV              | 1         | 1.64%   |
| Avell High Performance A62                  | 1         | 1.64%   |
| Avell High Performance A60 MUV              | 1         | 1.64%   |
| ASUS K46CA                                  | 1         | 1.64%   |
| Apple MacBookPro8,1                         | 1         | 1.64%   |
| Apple MacBook6,1                            | 1         | 1.64%   |
| Acer Aspire ES1-533                         | 1         | 1.64%   |
| Acer Aspire E1-421                          | 1         | 1.64%   |
| Acer Aspire A515-54G                        | 1         | 1.64%   |
| Acer Aspire A515-51G                        | 1         | 1.64%   |
| Acer Aspire 5742                            | 1         | 1.64%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 10        | 16.39%  |
| Dell Inspiron              | 9         | 14.75%  |
| Acer Aspire                | 7         | 11.48%  |
| Lenovo IdeaPad             | 3         | 4.92%   |
| Itautec Infoway            | 2         | 3.28%   |
| Gateway NE56R              | 2         | 3.28%   |
| Dell Latitude              | 2         | 3.28%   |
| Avell High Performance A62 | 2         | 3.28%   |
| Unknown                    | 2         | 3.28%   |
| Sony VPCYB45JB             | 1         | 1.64%   |
| Sony VPCEG17FB             | 1         | 1.64%   |
| Semp Toshiba STI           | 1         | 1.64%   |
| Samsung RV411              | 1         | 1.64%   |
| Samsung 530XBB             | 1         | 1.64%   |
| Samsung 340XAA             | 1         | 1.64%   |
| Samsung 300E5M             | 1         | 1.64%   |
| Samsung 270E5K             | 1         | 1.64%   |
| Positivo C14CR01           | 1         | 1.64%   |
| Philco 10B                 | 1         | 1.64%   |
| Notebook N85               | 1         | 1.64%   |
| LG 14Z980-G.BH51P1         | 1         | 1.64%   |
| Lenovo G550                | 1         | 1.64%   |
| HP EliteBook               | 1         | 1.64%   |
| HP 14                      | 1         | 1.64%   |
| Dell Vostro                | 1         | 1.64%   |
| Dell Venue                 | 1         | 1.64%   |
| Clevo C41X0                | 1         | 1.64%   |
| Avell High Performance A60 | 1         | 1.64%   |
| ASUS K46CA                 | 1         | 1.64%   |
| Apple MacBookPro8          | 1         | 1.64%   |
| Apple MacBook6             | 1         | 1.64%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2013    | 10        | 16.39%  |
| 2019    | 8         | 13.11%  |
| 2020    | 7         | 11.48%  |
| 2018    | 7         | 11.48%  |
| 2011    | 7         | 11.48%  |
| 2016    | 4         | 6.56%   |
| 2017    | 3         | 4.92%   |
| 2014    | 3         | 4.92%   |
| 2009    | 3         | 4.92%   |
| 2015    | 2         | 3.28%   |
| 2012    | 2         | 3.28%   |
| 2010    | 2         | 3.28%   |
| Unknown | 2         | 3.28%   |
| 2022    | 1         | 1.64%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 61        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 61        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 25        | 40.98%  |
| 8.01-16.0  | 23        | 37.7%   |
| 16.01-24.0 | 7         | 11.48%  |
| 32.01-64.0 | 2         | 3.28%   |
| 24.01-32.0 | 2         | 3.28%   |
| 3.01-4.0   | 1         | 1.64%   |
| 2.01-3.0   | 1         | 1.64%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 40        | 64.52%  |
| 0.51-1.0   | 18        | 29.03%  |
| 32.01-64.0 | 1         | 1.61%   |
| 24.01-32.0 | 1         | 1.61%   |
| 1.01-2.0   | 1         | 1.61%   |
| Unknown    | 1         | 1.61%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 39        | 62.9%   |
| 2      | 20        | 32.26%  |
| 0      | 3         | 4.84%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 39        | 63.93%  |
| Yes       | 22        | 36.07%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 54        | 88.52%  |
| No        | 7         | 11.48%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 58        | 95.08%  |
| No        | 3         | 4.92%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 41        | 67.21%  |
| No        | 20        | 32.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Brazil  | 61        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Curitiba                  | 5         | 7.58%   |
| SГЈo Paulo              | 4         | 6.06%   |
| Rio de Janeiro            | 4         | 6.06%   |
| Manaus                    | 3         | 4.55%   |
| SÃ£o Paulo              | 2         | 3.03%   |
| Maraba                    | 2         | 3.03%   |
| JoГЈo Pessoa            | 2         | 3.03%   |
| Ipojuca                   | 2         | 3.03%   |
| Visconde do Rio Branco    | 1         | 1.52%   |
| Uberaba                   | 1         | 1.52%   |
| Teresopolis               | 1         | 1.52%   |
| Teresina                  | 1         | 1.52%   |
| Tangara                   | 1         | 1.52%   |
| SГЈo JosГ© dos Campos | 1         | 1.52%   |
| Sao Vicente               | 1         | 1.52%   |
| Sao Jeronimo da Serra     | 1         | 1.52%   |
| Santa Maria               | 1         | 1.52%   |
| Rio das Ostras            | 1         | 1.52%   |
| Porto UniГЈo            | 1         | 1.52%   |
| Porto Alegre              | 1         | 1.52%   |
| Piloezinhos               | 1         | 1.52%   |
| Paracuru                  | 1         | 1.52%   |
| Osasco                    | 1         | 1.52%   |
| Monte Belo                | 1         | 1.52%   |
| Marica                    | 1         | 1.52%   |
| Mage                      | 1         | 1.52%   |
| Londrina                  | 1         | 1.52%   |
| Lavras                    | 1         | 1.52%   |
| Lajeado                   | 1         | 1.52%   |
| Juiz de Fora              | 1         | 1.52%   |
| Ibiuna                    | 1         | 1.52%   |
| Guapimirim                | 1         | 1.52%   |
| Goiatuba                  | 1         | 1.52%   |
| Franca                    | 1         | 1.52%   |
| Fortaleza                 | 1         | 1.52%   |
| Domingos Martins          | 1         | 1.52%   |
| Diamantino                | 1         | 1.52%   |
| Diadema                   | 1         | 1.52%   |
| Coimbra                   | 1         | 1.52%   |
| ChapecÃ³                | 1         | 1.52%   |
| Caxias do Sul             | 1         | 1.52%   |
| Campinas                  | 1         | 1.52%   |
| Cabo de Santo Agostinho   | 1         | 1.52%   |
| BrasГ­lia               | 1         | 1.52%   |
| Boa Vista do Jauato       | 1         | 1.52%   |
| Belo Horizonte            | 1         | 1.52%   |
| Araruama                  | 1         | 1.52%   |
| Aracaju                   | 1         | 1.52%   |
| Aparecida de Goiania      | 1         | 1.52%   |
| Alfenas                   | 1         | 1.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 14        | 15     | 17.95%  |
| Kingston            | 12        | 12     | 15.38%  |
| Seagate             | 11        | 13     | 14.1%   |
| Toshiba             | 8         | 8      | 10.26%  |
| Samsung Electronics | 6         | 6      | 7.69%   |
| Crucial             | 5         | 6      | 6.41%   |
| A-DATA Technology   | 5         | 5      | 6.41%   |
| LITEON              | 4         | 4      | 5.13%   |
| SK hynix            | 3         | 3      | 3.85%   |
| Hitachi             | 2         | 2      | 2.56%   |
| SSSTC               | 1         | 1      | 1.28%   |
| Smart               | 1         | 1      | 1.28%   |
| Silicon Motion      | 1         | 1      | 1.28%   |
| SanDisk             | 1         | 1      | 1.28%   |
| Patriot             | 1         | 4      | 1.28%   |
| KingSpec            | 1         | 1      | 1.28%   |
| Hikvision           | 1         | 1      | 1.28%   |
| China               | 1         | 1      | 1.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB              | 3         | 3.75%   |
| WDC WDS480G2G0B-00EPW0 480GB        | 2         | 2.5%    |
| WDC WDS240G2G0A-00JH30 240GB        | 2         | 2.5%    |
| Seagate ST1000LM048-2E7172 1TB      | 2         | 2.5%    |
| Seagate ST1000LM035-1RK172 1TB      | 2         | 2.5%    |
| Kingston SA400S37960G 960GB         | 2         | 2.5%    |
| Kingston SA400S37480G 480GB         | 2         | 2.5%    |
| Kingston SA400S37240G 240GB         | 2         | 2.5%    |
| WDC WD800BEVS-00RST0 80GB           | 1         | 1.25%   |
| WDC WD6400BEVT-22A0RT0 640GB        | 1         | 1.25%   |
| WDC WD5000B 500GB                   | 1         | 1.25%   |
| WDC WD20SPZX-22UA7T0 2TB            | 1         | 1.25%   |
| WDC WD1600BPVT-11JJ5T0 160GB        | 1         | 1.25%   |
| WDC WD1600BEVS-60RST0 160GB         | 1         | 1.25%   |
| WDC WD10SPZX-75Z10T1 1TB            | 1         | 1.25%   |
| WDC WD10SPZX-24Z10 1TB              | 1         | 1.25%   |
| WDC WD10JPVX-75JC3T0 1TB            | 1         | 1.25%   |
| WDC WD10JPVX-35JC3T0 1TB            | 1         | 1.25%   |
| WDC WD10JPCX-24UE4T0 1TB            | 1         | 1.25%   |
| Toshiba MQ01ABD100V 1TB             | 1         | 1.25%   |
| Toshiba MK3261GSYN 320GB            | 1         | 1.25%   |
| Toshiba MK2555GSXF 250GB            | 1         | 1.25%   |
| Toshiba MK1252GSX 120GB             | 1         | 1.25%   |
| Toshiba KBG30ZMV256G 256GB          | 1         | 1.25%   |
| SSSTC CL1-4D128 128GB               | 1         | 1.25%   |
| Smart SSD XceedValue2 mSATA 32GB    | 1         | 1.25%   |
| SK hynix HFS128G39TND-N210A 128GB   | 1         | 1.25%   |
| SK hynix BC511 NVMe 256GB           | 1         | 1.25%   |
| SK hynix 120GB SSD                  | 1         | 1.25%   |
| Silicon Motion NE-256 256GB         | 1         | 1.25%   |
| Seagate ST9320325ASG 320GB          | 1         | 1.25%   |
| Seagate ST9250315AS 250GB           | 1         | 1.25%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 1.25%   |
| Seagate ST500LT012-9WS142 500GB     | 1         | 1.25%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1.25%   |
| Seagate ST2000LM007-1R8174 2TB      | 1         | 1.25%   |
| Seagate ST1000LM025 HN-M101ABB 1TB  | 1         | 1.25%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1         | 1.25%   |
| SanDisk SDSSDP256G 256GB            | 1         | 1.25%   |
| Samsung SSD 970 EVO Plus 500GB      | 1         | 1.25%   |
| Samsung SG9MSM6D024GPM00 22GB       | 1         | 1.25%   |
| Samsung HM500JJ 500GB               | 1         | 1.25%   |
| Samsung HM500JI 500GB               | 1         | 1.25%   |
| Samsung HM321HI 320GB               | 1         | 1.25%   |
| Samsung HM320II 320GB               | 1         | 1.25%   |
| Patriot Burst 120GB                 | 1         | 1.25%   |
| LITEON LJH-64V2G-11 M.2 2260 64GB   | 1         | 1.25%   |
| LITEON LCH-256V2S 256GB             | 1         | 1.25%   |
| LITEON CV8-8E256-11 SATA 256GB      | 1         | 1.25%   |
| LITEON CV8-8E256 256GB              | 1         | 1.25%   |
| Kingston SUV500M8240G 240GB         | 1         | 1.25%   |
| Kingston SUV400S37120G 120GB        | 1         | 1.25%   |
| Kingston SUV300S37A120G 120GB       | 1         | 1.25%   |
| Kingston SKC300S37A240G 240GB       | 1         | 1.25%   |
| Kingston SA400S37120G 120GB         | 1         | 1.25%   |
| Kingston RBUSNS8154P3512GJ1 512GB   | 1         | 1.25%   |
| KingSpec NT-256 256GB               | 1         | 1.25%   |
| Hitachi HTS547550A9E384 500GB       | 1         | 1.25%   |
| Hitachi HTS545050B9A300 500GB       | 1         | 1.25%   |
| Hikvision HS-SSD-C100 120G          | 1         | 1.25%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 11        | 11     | 31.43%  |
| Seagate             | 11        | 13     | 31.43%  |
| Toshiba             | 7         | 7      | 20%     |
| Samsung Electronics | 4         | 4      | 11.43%  |
| Hitachi             | 2         | 2      | 5.71%   |

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
| HDD  | 31        | 37     | 43.06%  |
| SSD  | 30        | 37     | 41.67%  |
| NVMe | 11        | 11     | 15.28%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 51        | 74     | 82.26%  |
| NVMe | 11        | 11     | 17.74%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 39        | 50     | 65%     |
| 0.51-1.0   | 18        | 21     | 30%     |
| 1.01-2.0   | 3         | 3      | 5%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 20        | 30.77%  |
| 251-500    | 14        | 21.54%  |
| 101-250    | 13        | 20%     |
| 501-1000   | 7         | 10.77%  |
| 51-100     | 4         | 6.15%   |
| 1001-2000  | 3         | 4.62%   |
| 21-50      | 2         | 3.08%   |
| 2001-3000  | 1         | 1.54%   |
| Unknown    | 1         | 1.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 49        | 79.03%  |
| 21-50    | 6         | 9.68%   |
| 501-1000 | 3         | 4.84%   |
| 101-250  | 2         | 3.23%   |
| 51-100   | 1         | 1.61%   |
| Unknown  | 1         | 1.61%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB             | 2         | 2      | 11.11%  |
| WDC WD5000B 500GB                  | 1         | 1      | 5.56%   |
| WDC WD1600BEVS-60RST0 160GB        | 1         | 1      | 5.56%   |
| WDC WD10JPVX-75JC3T0 1TB           | 1         | 1      | 5.56%   |
| Toshiba MK3261GSYN 320GB           | 1         | 1      | 5.56%   |
| Toshiba MK2555GSXF 250GB           | 1         | 1      | 5.56%   |
| Toshiba MK1252GSX 120GB            | 1         | 1      | 5.56%   |
| SK hynix HFS128G39TND-N210A 128GB  | 1         | 1      | 5.56%   |
| Seagate ST9320325ASG 320GB         | 1         | 1      | 5.56%   |
| Seagate ST9250315AS 250GB          | 1         | 1      | 5.56%   |
| Seagate ST500LT012-9WS142 500GB    | 1         | 1      | 5.56%   |
| Seagate ST1000LM048-2E7172 1TB     | 1         | 1      | 5.56%   |
| Seagate ST1000LM025 HN-M101ABB 1TB | 1         | 1      | 5.56%   |
| Samsung Electronics HM321HI 320GB  | 1         | 1      | 5.56%   |
| LITEON LJH-64V2G-11 M.2 2260 64GB  | 1         | 1      | 5.56%   |
| Hitachi HTS547550A9E384 500GB      | 1         | 1      | 5.56%   |
| Hitachi HTS545050B9A300 500GB      | 1         | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 5         | 5      | 27.78%  |
| Seagate             | 5         | 5      | 27.78%  |
| WDC                 | 3         | 3      | 16.67%  |
| Hitachi             | 2         | 2      | 11.11%  |
| SK hynix            | 1         | 1      | 5.56%   |
| Samsung Electronics | 1         | 1      | 5.56%   |
| LITEON              | 1         | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 5         | 5      | 31.25%  |
| Seagate             | 5         | 5      | 31.25%  |
| WDC                 | 3         | 3      | 18.75%  |
| Hitachi             | 2         | 2      | 12.5%   |
| Samsung Electronics | 1         | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 16     | 87.5%   |
| SSD  | 2         | 2      | 12.5%   |

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
| Works   | 50        | 67     | 75.76%  |
| Malfunc | 16        | 18     | 24.24%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 56        | 78.87%  |
| AMD                            | 3         | 4.23%   |
| ADATA Technology               | 3         | 4.23%   |
| Toshiba                        | 1         | 1.41%   |
| Solid State Storage Technology | 1         | 1.41%   |
| SK hynix                       | 1         | 1.41%   |
| Silicon Motion                 | 1         | 1.41%   |
| Samsung Electronics            | 1         | 1.41%   |
| Realtek Semiconductor          | 1         | 1.41%   |
| Nvidia                         | 1         | 1.41%   |
| Micron/Crucial Technology      | 1         | 1.41%   |
| Kingston Technology Company    | 1         | 1.41%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 10        | 13.89%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 8         | 11.11%  |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 6         | 8.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 6         | 8.33%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 5         | 6.94%   |
| Unknown                                                                      | 5         | 6.94%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                            | 3         | 4.17%   |
| Intel Comet Lake SATA AHCI Controller                                        | 2         | 2.78%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 2         | 2.78%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 2         | 2.78%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 2         | 2.78%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                         | 2         | 2.78%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                            | 2         | 2.78%   |
| Toshiba BG3 NVMe SSD Controller                                              | 1         | 1.39%   |
| SK hynix BC511                                                               | 1         | 1.39%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                              | 1         | 1.39%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 1         | 1.39%   |
| Nvidia MCP79 AHCI Controller                                                 | 1         | 1.39%   |
| Micron/Crucial P1 NVMe PCIe SSD                                              | 1         | 1.39%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                        | 1         | 1.39%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                           | 1         | 1.39%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 1         | 1.39%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller     | 1         | 1.39%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 1         | 1.39%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                | 1         | 1.39%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 1         | 1.39%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]              | 1         | 1.39%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]              | 1         | 1.39%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller               | 1         | 1.39%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 1         | 1.39%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 57        | 80.28%  |
| NVMe | 11        | 15.49%  |
| IDE  | 2         | 2.82%   |
| RAID | 1         | 1.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 58        | 95.08%  |
| AMD    | 3         | 4.92%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz       | 3         | 4.92%   |
| Intel CPU Version                       | 2         | 3.28%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 2         | 3.28%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 2         | 3.28%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 2         | 3.28%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 2         | 3.28%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 2         | 3.28%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 2         | 3.28%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 2         | 3.28%   |
| Intel Core i3-4005U CPU @ 1.70GHz       | 2         | 3.28%   |
| Intel Core i3-2330M CPU @ 2.20GHz       | 2         | 3.28%   |
| Intel Pentium CPU 5405U @ 2.30GHz       | 1         | 1.64%   |
| Intel Genuine CPU                       | 1         | 1.64%   |
| Intel Core M-5Y10c CPU @ 0.80GHz        | 1         | 1.64%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 1         | 1.64%   |
| Intel Core i7-8665U CPU @ 1.90GHz       | 1         | 1.64%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 1         | 1.64%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 1.64%   |
| Intel Core i7-7600U CPU @ 2.80GHz       | 1         | 1.64%   |
| Intel Core i7-3632QM CPU @ 2.20GHz      | 1         | 1.64%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 1         | 1.64%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz      | 1         | 1.64%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 1         | 1.64%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 1         | 1.64%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 1         | 1.64%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 1         | 1.64%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 1         | 1.64%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 1         | 1.64%   |
| Intel Core i5-3317U CPU @ 1.70GHz       | 1         | 1.64%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 1         | 1.64%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 1         | 1.64%   |
| Intel Core i5-2415M CPU @ 2.30GHz       | 1         | 1.64%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 1         | 1.64%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 1         | 1.64%   |
| Intel Core i5 CPU M 460 @ 2.53GHz       | 1         | 1.64%   |
| Intel Core i3-6006U CPU @ 2.00GHz       | 1         | 1.64%   |
| Intel Core i3-3227U CPU @ 1.90GHz       | 1         | 1.64%   |
| Intel Core i3-2310M CPU @ 2.10GHz       | 1         | 1.64%   |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz    | 1         | 1.64%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 1         | 1.64%   |
| Intel Celeron N4000 CPU @ 1.10GHz       | 1         | 1.64%   |
| Intel Celeron CPU N3350 @ 1.10GHz       | 1         | 1.64%   |
| Intel Celeron CPU B830 @ 1.80GHz        | 1         | 1.64%   |
| Intel Celeron CPU 847 @ 1.10GHz         | 1         | 1.64%   |
| Intel Atom CPU N270 @ 1.60GHz           | 1         | 1.64%   |
| Intel Atom CPU D425 @ 1.80GHz           | 1         | 1.64%   |
| AMD E1-1200 APU with Radeon HD Graphics | 1         | 1.64%   |
| AMD E-450 APU with Radeon HD Graphics   | 1         | 1.64%   |
| AMD C-60 APU with Radeon HD Graphics    | 1         | 1.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 23        | 37.7%   |
| Intel Core i7    | 15        | 24.59%  |
| Intel Core i3    | 7         | 11.48%  |
| Intel Celeron    | 5         | 8.2%    |
| Other            | 2         | 3.28%   |
| Intel Atom       | 2         | 3.28%   |
| Intel Pentium    | 1         | 1.64%   |
| Intel Genuine    | 1         | 1.64%   |
| Intel Core M     | 1         | 1.64%   |
| Intel Core 2 Duo | 1         | 1.64%   |
| AMD E1           | 1         | 1.64%   |
| AMD E            | 1         | 1.64%   |
| AMD C-60         | 1         | 1.64%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 43        | 70.49%  |
| 4       | 12        | 19.67%  |
| 6       | 3         | 4.92%   |
| Unknown | 2         | 3.28%   |
| 1       | 1         | 1.64%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 60        | 98.36%  |
| 2      | 1         | 1.64%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 47        | 77.05%  |
| 1       | 12        | 19.67%  |
| Unknown | 2         | 3.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 16        | 26.23%  |
| SandyBridge   | 9         | 14.75%  |
| IvyBridge     | 6         | 9.84%   |
| Broadwell     | 6         | 9.84%   |
| Haswell       | 5         | 8.2%    |
| Westmere      | 3         | 4.92%   |
| Skylake       | 3         | 4.92%   |
| Penryn        | 3         | 4.92%   |
| Bobcat        | 3         | 4.92%   |
| Goldmont plus | 2         | 3.28%   |
| CometLake     | 2         | 3.28%   |
| Bonnell       | 2         | 3.28%   |
| Goldmont      | 1         | 1.64%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 56        | 73.68%  |
| Nvidia | 15        | 19.74%  |
| AMD    | 5         | 6.58%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 8         | 10.39%  |
| Intel 3rd Gen Core processor Graphics Controller                              | 6         | 7.79%   |
| Intel UHD Graphics 620                                                        | 5         | 6.49%   |
| Intel HD Graphics 5500                                                        | 5         | 6.49%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 5         | 6.49%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 3         | 3.9%    |
| Intel Skylake GT2 [HD Graphics 520]                                           | 3         | 3.9%    |
| Intel HD Graphics 620                                                         | 3         | 3.9%    |
| Intel Core Processor Integrated Graphics Controller                           | 3         | 3.9%    |
| Nvidia TU117M                                                                 | 2         | 2.6%    |
| Nvidia GP108M [GeForce MX250]                                                 | 2         | 2.6%    |
| Nvidia GM108M [GeForce MX130]                                                 | 2         | 2.6%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 2         | 2.6%    |
| Intel GeminiLake [UHD Graphics 600]                                           | 2         | 2.6%    |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 2         | 2.6%    |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 2         | 2.6%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 1         | 1.3%    |
| Nvidia GP108M [GeForce MX230]                                                 | 1         | 1.3%    |
| Nvidia GM108M [GeForce MX110]                                                 | 1         | 1.3%    |
| Nvidia GM108M [GeForce 940MX]                                                 | 1         | 1.3%    |
| Nvidia GM107M [GeForce GTX 950M]                                              | 1         | 1.3%    |
| Nvidia GK208M [GeForce GT 740M]                                               | 1         | 1.3%    |
| Nvidia GK208BM [GeForce 920M]                                                 | 1         | 1.3%    |
| Nvidia GF119M [GeForce 410M]                                                  | 1         | 1.3%    |
| Nvidia C79 [GeForce 9400M]                                                    | 1         | 1.3%    |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 1.3%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 1         | 1.3%    |
| Intel HD Graphics 630                                                         | 1         | 1.3%    |
| Intel HD Graphics 5300                                                        | 1         | 1.3%    |
| Intel HD Graphics 500                                                         | 1         | 1.3%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 1         | 1.3%    |
| Intel Coffee Lake UHD 610 Graphics Controller                                 | 1         | 1.3%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 1         | 1.3%    |
| AMD Wrestler [Radeon HD 7310]                                                 | 1         | 1.3%    |
| AMD Wrestler [Radeon HD 6320]                                                 | 1         | 1.3%    |
| AMD Wrestler [Radeon HD 6290]                                                 | 1         | 1.3%    |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                    | 1         | 1.3%    |
| AMD Chelsea LP [Radeon HD 7730M]                                              | 1         | 1.3%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 37        | 60.66%  |
| Intel + Nvidia | 13        | 21.31%  |
| 2 x Intel      | 4         | 6.56%   |
| 1 x AMD        | 3         | 4.92%   |
| 1 x Nvidia     | 2         | 3.28%   |
| Intel + AMD    | 2         | 3.28%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 57        | 93.44%  |
| Proprietary | 3         | 4.92%   |
| Unknown     | 1         | 1.64%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 56        | 91.8%   |
| 0.01-0.5   | 3         | 4.92%   |
| 3.01-4.0   | 2         | 3.28%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 17        | 30.36%  |
| LG Display          | 10        | 17.86%  |
| BOE                 | 6         | 10.71%  |
| Chimei Innolux      | 5         | 8.93%   |
| Samsung Electronics | 4         | 7.14%   |
| InfoVision          | 3         | 5.36%   |
| Dell                | 3         | 5.36%   |
| Lenovo              | 2         | 3.57%   |
| AOC                 | 2         | 3.57%   |
| Philips             | 1         | 1.79%   |
| PANDA               | 1         | 1.79%   |
| Hewlett-Packard     | 1         | 1.79%   |
| Apple               | 1         | 1.79%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch         | 4         | 7.14%   |
| LG Display LCD Monitor LGD0385 1366x768 310x170mm 13.9-inch           | 3         | 5.36%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch          | 2         | 3.57%   |
| AU Optronics LCD Monitor AUO303C 1366x768 310x170mm 13.9-inch         | 2         | 3.57%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 330x210mm 15.4-inch  | 1         | 1.79%   |
| Samsung Electronics LCD Monitor SEC414C 1366x768 310x170mm 13.9-inch  | 1         | 1.79%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 310x170mm 13.9-inch  | 1         | 1.79%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch | 1         | 1.79%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                | 1         | 1.79%   |
| PANDA LCD Monitor NCP0004 1920x1080 290x170mm 13.2-inch               | 1         | 1.79%   |
| LG Display LCD Monitor LGD05B1 1920x1080 310x170mm 13.9-inch          | 1         | 1.79%   |
| LG Display LCD Monitor LGD053C 1920x1080 310x170mm 13.9-inch          | 1         | 1.79%   |
| LG Display LCD Monitor LGD0458 1366x768 310x170mm 13.9-inch           | 1         | 1.79%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch           | 1         | 1.79%   |
| LG Display LCD Monitor LGD0230 1366x768 340x190mm 15.3-inch           | 1         | 1.79%   |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                 | 1         | 1.79%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch               | 1         | 1.79%   |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch          | 1         | 1.79%   |
| InfoVision LCD Monitor IVO0579 1366x768 310x170mm 13.9-inch           | 1         | 1.79%   |
| InfoVision LCD Monitor IVO03F4 1024x600 220x130mm 10.1-inch           | 1         | 1.79%   |
| Hewlett-Packard L200hx HWP298F 1600x900 450x250mm 20.3-inch           | 1         | 1.79%   |
| Dell S2419HGF DELD0E1 1920x1080 530x300mm 24.0-inch                   | 1         | 1.79%   |
| Dell P2419H DELD0D9 1920x1080 530x300mm 24.0-inch                     | 1         | 1.79%   |
| Dell P2418D DELD0C1 2560x1440 530x300mm 24.0-inch                     | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 340x190mm 15.3-inch       | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 340x190mm 15.3-inch       | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN1496 1366x768 310x170mm 13.9-inch       | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 310x170mm 13.9-inch       | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN1119 1366x768 260x140mm 11.6-inch       | 1         | 1.79%   |
| BOE LCD Monitor BOE0757 1366x768 340x190mm 15.3-inch                  | 1         | 1.79%   |
| BOE LCD Monitor BOE0747 1920x1080 340x190mm 15.3-inch                 | 1         | 1.79%   |
| BOE LCD Monitor BOE0698 1366x768 310x170mm 13.9-inch                  | 1         | 1.79%   |
| BOE LCD Monitor BOE0690 1920x1080 340x190mm 15.3-inch                 | 1         | 1.79%   |
| BOE LCD Monitor BOE05E0 1366x768 280x160mm 12.7-inch                  | 1         | 1.79%   |
| BOE LCD Monitor BOE05B1 1366x768 310x170mm 13.9-inch                  | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch         | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO45ED 1920x1080 340x190mm 15.3-inch        | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO44EC 1366x768 340x190mm 15.3-inch         | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO423D 1920x1080 310x170mm 13.9-inch        | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 340x190mm 15.3-inch         | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO323C 1366x768 310x170mm 13.9-inch         | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 310x170mm 13.9-inch         | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO263D 1920x1080 310x170mm 13.9-inch        | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 340x190mm 15.3-inch         | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO183C 1366x768 310x170mm 13.9-inch         | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch        | 1         | 1.79%   |
| Apple LCD Monitor APP9CC5 1280x800 290x180mm 13.4-inch                | 1         | 1.79%   |
| AOC T2242we AOC2242 1920x1080 480x270mm 21.7-inch                     | 1         | 1.79%   |
| AOC 936W AOC1936 1366x768 410x230mm 18.5-inch                         | 1         | 1.79%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1366x768 (WXGA) | 33        | 61.11%  |
| 1920x1080 (FHD) | 16        | 29.63%  |
| 1280x800 (WXGA) | 2         | 3.7%    |
| 2560x1440 (QHD) | 1         | 1.85%   |
| 1600x900 (HD+)  | 1         | 1.85%   |
| 1024x600        | 1         | 1.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 23        | 41.07%  |
| 15     | 18        | 32.14%  |
| 24     | 4         | 7.14%   |
| 12     | 4         | 7.14%   |
| 18     | 2         | 3.57%   |
| 21     | 1         | 1.79%   |
| 20     | 1         | 1.79%   |
| 14     | 1         | 1.79%   |
| 11     | 1         | 1.79%   |
| 10     | 1         | 1.79%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 39        | 69.64%  |
| 201-300     | 9         | 16.07%  |
| 501-600     | 4         | 7.14%   |
| 401-500     | 4         | 7.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 46        | 93.88%  |
| 16/10 | 3         | 6.12%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 23        | 41.07%  |
| 91-100         | 17        | 30.36%  |
| 201-250        | 5         | 8.93%   |
| 61-70          | 4         | 7.14%   |
| 141-150        | 2         | 3.57%   |
| 71-80          | 1         | 1.79%   |
| 51-60          | 1         | 1.79%   |
| 41-50          | 1         | 1.79%   |
| 151-200        | 1         | 1.79%   |
| 101-110        | 1         | 1.79%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 31        | 57.41%  |
| 121-160 | 13        | 24.07%  |
| 51-100  | 7         | 12.96%  |
| 161-240 | 3         | 5.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 44        | 72.13%  |
| 0     | 10        | 16.39%  |
| 2     | 7         | 11.48%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 33        | 33.67%  |
| Qualcomm Atheros      | 25        | 25.51%  |
| Intel                 | 22        | 22.45%  |
| Broadcom              | 9         | 9.18%   |
| JMicron Technology    | 5         | 5.1%    |
| TP-Link               | 1         | 1.02%   |
| Ralink Technology     | 1         | 1.02%   |
| Nvidia                | 1         | 1.02%   |
| MediaTek              | 1         | 1.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 15        | 12.82%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 11.11%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 8         | 6.84%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 5.13%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 4         | 3.42%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 3.42%   |
| Intel Wireless 8265 / 8275                                        | 4         | 3.42%   |
| Intel Wireless 7265                                               | 4         | 3.42%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 3         | 2.56%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 3         | 2.56%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 2.56%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 2.56%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 1.71%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 1.71%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.71%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 2         | 1.71%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 2         | 1.71%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.71%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 1.71%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 1.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.71%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.85%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.85%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                            | 1         | 0.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.85%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1         | 0.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.85%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.85%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.85%   |
| MediaTek USB Ethernet-RNDIS                                       | 1         | 0.85%   |
| Intel Wireless 8260                                               | 1         | 0.85%   |
| Intel Wireless 7260                                               | 1         | 0.85%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 0.85%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.85%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.85%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1         | 0.85%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 0.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 0.85%   |
| Intel Centrino Advanced-N 6200                                    | 1         | 0.85%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 0.85%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.85%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.85%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 0.85%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.85%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 1         | 0.85%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 1         | 0.85%   |
| Broadcom BCM43225 802.11b/g/n                                     | 1         | 0.85%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 1         | 0.85%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Qualcomm Atheros      | 24        | 39.34%  |
| Intel                 | 22        | 36.07%  |
| Realtek Semiconductor | 9         | 14.75%  |
| Broadcom              | 4         | 6.56%   |
| TP-Link               | 1         | 1.64%   |
| Ralink Technology     | 1         | 1.64%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 8         | 12.9%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 6         | 9.68%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 4         | 6.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4         | 6.45%   |
| Intel Wireless 8265 / 8275                                     | 4         | 6.45%   |
| Intel Wireless 7265                                            | 4         | 6.45%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 3         | 4.84%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 3.23%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 3.23%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 2         | 3.23%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 3.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 3.23%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 1.61%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 1.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.61%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                         | 1         | 1.61%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 1.61%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 1.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.61%   |
| Intel Wireless 8260                                            | 1         | 1.61%   |
| Intel Wireless 7260                                            | 1         | 1.61%   |
| Intel Wi-Fi 6 AX200                                            | 1         | 1.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 1.61%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 1.61%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 1.61%   |
| Intel Centrino Advanced-N 6200                                 | 1         | 1.61%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 1.61%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 1         | 1.61%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 1         | 1.61%   |
| Broadcom BCM43225 802.11b/g/n                                  | 1         | 1.61%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 1         | 1.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 28        | 51.85%  |
| Intel                 | 11        | 20.37%  |
| Broadcom              | 6         | 11.11%  |
| JMicron Technology    | 5         | 9.26%   |
| Qualcomm Atheros      | 3         | 5.56%   |
| Nvidia                | 1         | 1.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 15        | 27.78%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 24.07%  |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 3         | 5.56%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 5.56%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 5.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 3.7%    |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 2         | 3.7%    |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 3.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 3.7%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.85%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.85%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.85%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.85%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.85%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.85%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.85%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 1.85%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.85%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 58        | 51.33%  |
| Ethernet | 54        | 47.79%  |
| Modem    | 1         | 0.88%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 50        | 52.08%  |
| WiFi     | 46        | 47.92%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 51        | 83.61%  |
| 1     | 10        | 16.39%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 58        | 95.08%  |
| Yes  | 3         | 4.92%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 16        | 39.02%  |
| Qualcomm Atheros Communications | 12        | 29.27%  |
| Broadcom                        | 3         | 7.32%   |
| Apple                           | 3         | 7.32%   |
| Realtek Semiconductor           | 2         | 4.88%   |
| Lite-On Technology              | 2         | 4.88%   |
| Foxconn / Hon Hai               | 2         | 4.88%   |
| IMC Networks                    | 1         | 2.44%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 8         | 19.51%  |
| Qualcomm Atheros AR9462 Bluetooth                           | 4         | 9.76%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 4         | 9.76%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 3         | 7.32%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 2         | 4.88%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 2         | 4.88%   |
| Intel AX201 Bluetooth                                       | 2         | 4.88%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 4.88%   |
| Apple Bluetooth Host Controller                             | 2         | 4.88%   |
| Realtek  Bluetooth Adapter                                  | 1         | 2.44%   |
| Realtek CSR Bluetooth Chip                                  | 1         | 2.44%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 2.44%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 2.44%   |
| Lite-On Atheros Bluetooth                                   | 1         | 2.44%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 2.44%   |
| Intel AX200 Bluetooth                                       | 1         | 2.44%   |
| IMC Networks Bluetooth Module                               | 1         | 2.44%   |
| Foxconn / Hon Hai Qualcomm Atheros Bluetooth 4.0            | 1         | 2.44%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 2.44%   |
| Broadcom BCM2046 Bluetooth Device                           | 1         | 2.44%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 1         | 2.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Intel    | 57        | 83.82%  |
| Nvidia   | 5         | 7.35%   |
| AMD      | 3         | 4.41%   |
| M-Audio  | 1         | 1.47%   |
| Logitech | 1         | 1.47%   |
| Lenovo   | 1         | 1.47%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 11        | 13.58%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9         | 11.11%  |
| Intel Broadwell-U Audio Controller                                         | 6         | 7.41%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6         | 7.41%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 6.17%   |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 6.17%   |
| Intel 8 Series HD Audio Controller                                         | 5         | 6.17%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 4.94%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 3.7%    |
| AMD Wrestler HDMI Audio                                                    | 3         | 3.7%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 2.47%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 2.47%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 2.47%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 2.47%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 2.47%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 2.47%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 2.47%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 1.23%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 1.23%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 1.23%   |
| M-Audio M-Audio Fast Track Pro                                             | 1         | 1.23%   |
| Logitech H390 headset with microphone                                      | 1         | 1.23%   |
| Lenovo Realtek USB Audio                                                   | 1         | 1.23%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.23%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 1.23%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.23%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.23%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Smart               | 17        | 23.94%  |
| Samsung Electronics | 9         | 12.68%  |
| SK hynix            | 7         | 9.86%   |
| Kingston            | 7         | 9.86%   |
| Teikon              | 6         | 8.45%   |
| A-DATA Technology   | 5         | 7.04%   |
| Unknown             | 5         | 7.04%   |
| Smart Brazil        | 3         | 4.23%   |
| High Bridge         | 3         | 4.23%   |
| Micron Technology   | 2         | 2.82%   |
| Crucial             | 2         | 2.82%   |
| Apacer              | 2         | 2.82%   |
| Unknown (ABCD)      | 1         | 1.41%   |
| PNY                 | 1         | 1.41%   |
| Nanya Technology    | 1         | 1.41%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                     | 5         | 6.85%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s                       | 4         | 5.48%   |
| Smart RAM SH564128FJ8NZRNSDG 4GB SODIMM DDR3 1600MT/s                       | 2         | 2.74%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s                       | 2         | 2.74%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s                       | 2         | 2.74%   |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s                       | 2         | 2.74%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s                       | 2         | 2.74%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s                       | 2         | 2.74%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2133MT/s            | 1         | 1.37%   |
| Teikon RAM TMT451S6BFR8A-PBSC 4096MB SODIMM DDR3 1600MT/s                   | 1         | 1.37%   |
| Teikon RAM TMT451S6BFR8A-PBHC 4GB SODIMM DDR3 1333MT/s                      | 1         | 1.37%   |
| Teikon RAM TMT41GS6BFR8A-PBSC 8GB SODIMM DDR3 1600MT/s                      | 1         | 1.37%   |
| Teikon RAM TMT225S6FR8C-H9HC 2GB SODIMM DDR3 1334MT/s                       | 1         | 1.37%   |
| Teikon RAM TML251S6EFR8A-PBHC 4096MB SODIMM DDR3 1600MT/s                   | 1         | 1.37%   |
| Teikon RAM TMA81GS6AFR8N-UHSC 8GB SODIMM DDR4 2400MT/s                      | 1         | 1.37%   |
| Smart RAM SH564568FH8NWPHSFR 2GB SODIMM DDR3 1333MT/s                       | 1         | 1.37%   |
| Smart RAM SH564128FJ8NZRNSDR 4GB SODIMM DDR3 1600MT/s                       | 1         | 1.37%   |
| Smart RAM SF4641G8CK8IWGKSEG 8GB SODIMM DDR4 2133MT/s                       | 1         | 1.37%   |
| Smart RAM SF464128CKHIWDFSEG 4GB SODIMM DDR4 2133MT/s                       | 1         | 1.37%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4096MB SODIMM DDR4 2400MT/s             | 1         | 1.37%   |
| Smart Brazil RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2133MT/s                | 1         | 1.37%   |
| Smart Brazil RAM Module 4GB Row Of Chips DDR4 2400MT/s                      | 1         | 1.37%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 800MT/s                       | 1         | 1.37%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                      | 1         | 1.37%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                      | 1         | 1.37%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                      | 1         | 1.37%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s                      | 1         | 1.37%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s                      | 1         | 1.37%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s                     | 1         | 1.37%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s                       | 1         | 1.37%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 1067MT/s                       | 1         | 1.37%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                       | 1         | 1.37%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                       | 1         | 1.37%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s                       | 1         | 1.37%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2400MT/s                      | 1         | 1.37%   |
| Samsung RAM K4E6E304EB-EGCG 4096MB SODIMM DDR3 1600MT/s                     | 1         | 1.37%   |
| Samsung RAM K4B8G1646B-MYK0 4GB SODIMM DDR3 1600MT/s                        | 1         | 1.37%   |
| PNY RAM 16GU2X16LIII43-12-K 16GB SODIMM DDR4 2667MT/s                       | 1         | 1.37%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s                        | 1         | 1.37%   |
| Micron RAM A0B4CDD4C6B2B5B6B6B4C8DAADB1C7B6C5B1 2048MB SODIMM DDR3 1600MT/s | 1         | 1.37%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                        | 1         | 1.37%   |
| Kingston RAM Module 4GB SODIMM DDR3 1333MT/s                                | 1         | 1.37%   |
| Kingston RAM Module 2048MB SODIMM DDR3 1333MT/s                             | 1         | 1.37%   |
| Kingston RAM KHX2400C14S4/16G 16GB SODIMM DDR4 2400MT/s                     | 1         | 1.37%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s                       | 1         | 1.37%   |
| Kingston RAM 99U5428-040.A01LF 4GB SODIMM DDR3 1333MT/s                     | 1         | 1.37%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.37%   |
| Kingston RAM 9905428-416.A00LF 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.37%   |
| High Bridge RAM HB3SU002GFM8MMD33 2GB SODIMM DDR3 1333MT/s                  | 1         | 1.37%   |
| High Bridge RAM HB3SU002GFM8MMB33. 2048MB SODIMM DDR3 1334MT/s              | 1         | 1.37%   |
| High Bridge RAM HB3SU002GFM8DMA33. 2GB SODIMM DDR3 1333MT/s                 | 1         | 1.37%   |
| Crucial RAM CT16G4SFS8266.C8FB 16GB SODIMM DDR4 2667MT/s                    | 1         | 1.37%   |
| Crucial RAM CT16G4SFD824A.C16FHD 16GB SODIMM DDR4 2400MT/s                  | 1         | 1.37%   |
| Apacer RAM 76.B346G.C280C 4GB SODIMM DDR3 1333MT/s                          | 1         | 1.37%   |
| Apacer RAM 76.A346G.C270C 2GB SODIMM DDR3 1334MT/s                          | 1         | 1.37%   |
| A-DATA RAM Module 2GB SODIMM DDR2 533MT/s                                   | 1         | 1.37%   |
| A-DATA RAM AM1P26KCST2-BABS 16384MB SODIMM DDR4 2667MT/s                    | 1         | 1.37%   |
| A-DATA RAM AM1P26KC8T1-BAAS 8GB SODIMM DDR4 2667MT/s                        | 1         | 1.37%   |
| A-DATA RAM AM1P26KC4U1-BACS 4GB SODIMM DDR4 2667MT/s                        | 1         | 1.37%   |
| A-DATA RAM 11111111 4GB SODIMM DDR4 2400MT/s                                | 1         | 1.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 33        | 61.11%  |
| DDR4   | 17        | 31.48%  |
| DDR2   | 3         | 5.56%   |
| LPDDR4 | 1         | 1.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 53        | 98.15%  |
| Row Of Chips | 1         | 1.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 27        | 42.19%  |
| 2048  | 16        | 25%     |
| 8192  | 14        | 21.88%  |
| 16384 | 7         | 10.94%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 19        | 30.65%  |
| 1333  | 10        | 16.13%  |
| 2667  | 8         | 12.9%   |
| 2400  | 8         | 12.9%   |
| 1334  | 8         | 12.9%   |
| 2133  | 4         | 6.45%   |
| 800   | 2         | 3.23%   |
| 1067  | 1         | 1.61%   |
| 667   | 1         | 1.61%   |
| 533   | 1         | 1.61%   |

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
| Chicony Electronics           | 13        | 24.07%  |
| Realtek Semiconductor         | 7         | 12.96%  |
| Acer                          | 7         | 12.96%  |
| Microdia                      | 5         | 9.26%   |
| Silicon Motion                | 4         | 7.41%   |
| Syntek                        | 2         | 3.7%    |
| Suyin                         | 2         | 3.7%    |
| Sunplus Innovation Technology | 2         | 3.7%    |
| Logitech                      | 2         | 3.7%    |
| IMC Networks                  | 2         | 3.7%    |
| Alcor Micro                   | 2         | 3.7%    |
| Quanta                        | 1         | 1.85%   |
| Luxvisions Innotech Limited   | 1         | 1.85%   |
| Lite-On Technology            | 1         | 1.85%   |
| Lenovo                        | 1         | 1.85%   |
| Apple                         | 1         | 1.85%   |
| Unknown                       | 1         | 1.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Silicon Motion Web Camera                     | 3         | 5.45%   |
| Realtek Integrated_Webcam_HD                  | 3         | 5.45%   |
| Chicony HD WebCam                             | 3         | 5.45%   |
| Acer Integrated Camera                        | 3         | 5.45%   |
| Syntek EasyCamera                             | 2         | 3.64%   |
| Realtek Integrated Webcam                     | 2         | 3.64%   |
| Microdia Dell Laptop Integrated Webcam HD     | 2         | 3.64%   |
| Chicony Sony Visual Communication Camera      | 2         | 3.64%   |
| Alcor Micro Acer Integrated Webcam            | 2         | 3.64%   |
| Acer HD Webcam                                | 2         | 3.64%   |
| Suyin USB 2.0 UVC 1.3M WebCam                 | 1         | 1.82%   |
| Suyin Integrated_Webcam_HD                    | 1         | 1.82%   |
| Sunplus Integrated_Webcam_HD                  | 1         | 1.82%   |
| Sunplus HD WebCam                             | 1         | 1.82%   |
| Silicon Motion WebCam SCX Series              | 1         | 1.82%   |
| Realtek LG Camera                             | 1         | 1.82%   |
| Realtek Integrated_Webcam_FHD                 | 1         | 1.82%   |
| Realtek Integrated_Webcam_8M                  | 1         | 1.82%   |
| Quanta HD Webcam                              | 1         | 1.82%   |
| Microdia Laptop_Integrated_Webcam_HD          | 1         | 1.82%   |
| Microdia Integrated_Webcam_HD                 | 1         | 1.82%   |
| Microdia Integrated Webcam HD                 | 1         | 1.82%   |
| Luxvisions Innotech Limited Integrated Camera | 1         | 1.82%   |
| Logitech Webcam C270                          | 1         | 1.82%   |
| Logitech C922 Pro Stream Webcam               | 1         | 1.82%   |
| Lite-On Integrated Camera                     | 1         | 1.82%   |
| Lenovo Integrated Webcam [R5U877]             | 1         | 1.82%   |
| IMC Networks USB Camera                       | 1         | 1.82%   |
| IMC Networks EasyCamera                       | 1         | 1.82%   |
| Chicony Webcam                                | 1         | 1.82%   |
| Chicony Sonix ST50220 USB Video Camera        | 1         | 1.82%   |
| Chicony Lenovo Integrated Camera (0.3MP)      | 1         | 1.82%   |
| Chicony Integrated Camera                     | 1         | 1.82%   |
| Chicony HP HD Webcam [Fixed]                  | 1         | 1.82%   |
| Chicony HP HD Camera                          | 1         | 1.82%   |
| Chicony EasyCamera                            | 1         | 1.82%   |
| Chicony 1.3M Webcam                           | 1         | 1.82%   |
| Apple FaceTime HD Camera                      | 1         | 1.82%   |
| Acer SunplusIT Integrated Camera              | 1         | 1.82%   |
| Acer Lenovo EasyCamera                        | 1         | 1.82%   |
| Unknown                                       | 1         | 1.82%   |

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
| 2     | 17        | 27.42%  |
| 1     | 15        | 24.19%  |
| 3     | 12        | 19.35%  |
| 0     | 9         | 14.52%  |
| 5     | 5         | 8.06%   |
| 4     | 4         | 6.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 52        | 44.44%  |
| Card reader              | 24        | 20.51%  |
| Bluetooth                | 15        | 12.82%  |
| Net/wireless             | 14        | 11.97%  |
| Fingerprint reader       | 10        | 8.55%   |
| Sound                    | 2         | 1.71%   |

