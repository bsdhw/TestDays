FreeBSD 14.0-CURRENT - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------------

A project to collect tested hardware configurations for FreeBSD 14.0-CURRENT.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://bsd-hardware.info/?view=trends&rel=freebsd-14.0-CURRENT

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

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Framework     | Laptop                      | [e5aca4b7d0](https://bsd-hardware.info/?probe=e5aca4b7d0) | Oct 02, 2021 |
| HP            | EliteBook 8570p             | [646148fc25](https://bsd-hardware.info/?probe=646148fc25) | Sep 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [0b73df29bf](https://bsd-hardware.info/?probe=0b73df29bf) | Sep 15, 2021 |
| HP            | EliteBook 8570p             | [5a4e53da56](https://bsd-hardware.info/?probe=5a4e53da56) | Sep 12, 2021 |
| Lenovo        | ThinkPad X395 20NL000GPG    | [d7812a2905](https://bsd-hardware.info/?probe=d7812a2905) | Sep 10, 2021 |
| Lenovo        | ThinkPad X395 20NL000GPG    | [cdde22fb04](https://bsd-hardware.info/?probe=cdde22fb04) | Sep 10, 2021 |
| HP            | EliteBook 8570p             | [7a289e8d1b](https://bsd-hardware.info/?probe=7a289e8d1b) | Sep 06, 2021 |
| HP            | EliteBook 8570p             | [fae9e84f60](https://bsd-hardware.info/?probe=fae9e84f60) | Aug 27, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [76f004bd26](https://bsd-hardware.info/?probe=76f004bd26) | Aug 26, 2021 |
| HP            | EliteBook 8570p             | [a98c6adb40](https://bsd-hardware.info/?probe=a98c6adb40) | Aug 22, 2021 |
| HP            | EliteBook 8570p             | [71092e78e2](https://bsd-hardware.info/?probe=71092e78e2) | Aug 17, 2021 |
| HP            | EliteBook 8570p             | [6e97c9a59e](https://bsd-hardware.info/?probe=6e97c9a59e) | Aug 14, 2021 |
| Lenovo        | Unknown                     | [e16ce5e864](https://bsd-hardware.info/?probe=e16ce5e864) | Aug 08, 2021 |
| HP            | ZBook 17 G2                 | [f2d911563a](https://bsd-hardware.info/?probe=f2d911563a) | Aug 07, 2021 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [6d5e1a13d0](https://bsd-hardware.info/?probe=6d5e1a13d0) | Aug 07, 2021 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | [bf56b2a81a](https://bsd-hardware.info/?probe=bf56b2a81a) | Aug 05, 2021 |
| HP            | ZBook 17 G2                 | [2faf8af7be](https://bsd-hardware.info/?probe=2faf8af7be) | Jul 30, 2021 |
| HP            | ZBook 17 G2                 | [c7fb9e9dee](https://bsd-hardware.info/?probe=c7fb9e9dee) | Jul 27, 2021 |
| HP            | ZBook 17 G2                 | [50c349b7b5](https://bsd-hardware.info/?probe=50c349b7b5) | Jul 27, 2021 |
| HP            | ZBook 17 G2                 | [6149ab50a8](https://bsd-hardware.info/?probe=6149ab50a8) | Jul 24, 2021 |
| Dell          | G5 5505                     | [9933a09c4f](https://bsd-hardware.info/?probe=9933a09c4f) | Jul 24, 2021 |
| HP            | ZBook 17 G2                 | [1ef99f31dd](https://bsd-hardware.info/?probe=1ef99f31dd) | Jul 23, 2021 |
| Avell High... | A62 LIV                     | [5983302b1d](https://bsd-hardware.info/?probe=5983302b1d) | Jul 21, 2021 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | [e0e6f62814](https://bsd-hardware.info/?probe=e0e6f62814) | Jul 19, 2021 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | [b0da42c20d](https://bsd-hardware.info/?probe=b0da42c20d) | Jul 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [9c9d4cc782](https://bsd-hardware.info/?probe=9c9d4cc782) | Jul 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [3d5e512e18](https://bsd-hardware.info/?probe=3d5e512e18) | Jul 18, 2021 |
| HP            | ProBook 440 G7              | [63dc88528c](https://bsd-hardware.info/?probe=63dc88528c) | Jul 17, 2021 |
| HP            | ProBook 440 G7              | [7138e2a9e7](https://bsd-hardware.info/?probe=7138e2a9e7) | Jul 17, 2021 |
| HP            | ProBook 440 G7              | [b73eb50747](https://bsd-hardware.info/?probe=b73eb50747) | Jul 16, 2021 |
| HP            | EliteBook 8570p             | [462fc329a9](https://bsd-hardware.info/?probe=462fc329a9) | Jul 16, 2021 |
| HP            | ProBook 440 G7              | [d2866f01b5](https://bsd-hardware.info/?probe=d2866f01b5) | Jul 16, 2021 |
| HP            | EliteBook 8570p             | [cc24e867fc](https://bsd-hardware.info/?probe=cc24e867fc) | Jun 19, 2021 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | [3d50ba4d85](https://bsd-hardware.info/?probe=3d50ba4d85) | Jun 13, 2021 |
| Dell          | G5 5505                     | [97319295ee](https://bsd-hardware.info/?probe=97319295ee) | Jun 13, 2021 |
| Dell          | Vostro 5490                 | [cf3508718c](https://bsd-hardware.info/?probe=cf3508718c) | Jun 11, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [4ac6c9b3eb](https://bsd-hardware.info/?probe=4ac6c9b3eb) | Jun 08, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [8fc867cfae](https://bsd-hardware.info/?probe=8fc867cfae) | Jun 06, 2021 |
| HP            | EliteBook 8570p             | [52ba4e835f](https://bsd-hardware.info/?probe=52ba4e835f) | Jun 03, 2021 |
| Lenovo        | ThinkPad X270 20HM004JBR    | [88c27e65d7](https://bsd-hardware.info/?probe=88c27e65d7) | May 23, 2021 |
| HP            | EliteBook 8570p             | [062fe5ec40](https://bsd-hardware.info/?probe=062fe5ec40) | May 09, 2021 |
| Dell          | G5 5505                     | [ba74d8eee0](https://bsd-hardware.info/?probe=ba74d8eee0) | May 08, 2021 |
| Dell          | G5 5505                     | [23ae99e489](https://bsd-hardware.info/?probe=23ae99e489) | May 08, 2021 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | [2be8cf963c](https://bsd-hardware.info/?probe=2be8cf963c) | May 02, 2021 |
| Dell          | Inspiron 3793               | [c2d56fc369](https://bsd-hardware.info/?probe=c2d56fc369) | Apr 29, 2021 |
| HP            | EliteBook 8570p             | [e90abb54c9](https://bsd-hardware.info/?probe=e90abb54c9) | Apr 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [4993ad0feb](https://bsd-hardware.info/?probe=4993ad0feb) | Apr 25, 2021 |
| HUAWEI        | HN-WX9X                     | [d776625073](https://bsd-hardware.info/?probe=d776625073) | Apr 11, 2021 |
| HP            | EliteBook 8570p             | [d9ec051372](https://bsd-hardware.info/?probe=d9ec051372) | Apr 06, 2021 |
| HP            | EliteBook 8570p             | [cdeafa0952](https://bsd-hardware.info/?probe=cdeafa0952) | Apr 02, 2021 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [342e914968](https://bsd-hardware.info/?probe=342e914968) | Mar 29, 2021 |
| HP            | EliteBook 8570p             | [ed80dc9019](https://bsd-hardware.info/?probe=ed80dc9019) | Mar 27, 2021 |
| HP            | ProBook 455 G7              | [dd877e6c6c](https://bsd-hardware.info/?probe=dd877e6c6c) | Mar 27, 2021 |
| Lenovo        | ThinkPad X395 20NL001SMX    | [cd016e96ee](https://bsd-hardware.info/?probe=cd016e96ee) | Mar 17, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [9fed35d792](https://bsd-hardware.info/?probe=9fed35d792) | Mar 10, 2021 |
| HP            | ProBook 455 G7              | [1fcde7c0e1](https://bsd-hardware.info/?probe=1fcde7c0e1) | Mar 09, 2021 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | [f2c2e5345a](https://bsd-hardware.info/?probe=f2c2e5345a) | Feb 27, 2021 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | [aacafb6ace](https://bsd-hardware.info/?probe=aacafb6ace) | Feb 24, 2021 |
| A-DATA Tec... | XENIA159GENI72060           | [be88e8f865](https://bsd-hardware.info/?probe=be88e8f865) | Feb 15, 2021 |
| Lenovo        | ThinkPad T495s 20QKS1812... | [0e5e228d18](https://bsd-hardware.info/?probe=0e5e228d18) | Feb 13, 2021 |
| Lenovo        | ThinkPad T495s 20QKS1812... | [2d93a6bebc](https://bsd-hardware.info/?probe=2d93a6bebc) | Feb 13, 2021 |
| Matsushita... | CF-T2BW1AXR                 | [f6ec2858a5](https://bsd-hardware.info/?probe=f6ec2858a5) | Feb 10, 2021 |
| HP            | EliteBook 8570p             | [72137c63f8](https://bsd-hardware.info/?probe=72137c63f8) | Feb 09, 2021 |
| Dell          | Latitude E5430 vPro         | [bee421a110](https://bsd-hardware.info/?probe=bee421a110) | Feb 06, 2021 |
| Dell          | Latitude E5430 vPro         | [e8157ac6a3](https://bsd-hardware.info/?probe=e8157ac6a3) | Feb 06, 2021 |
| Lenovo        | ThinkPad T430 2349H2G       | [229db16a93](https://bsd-hardware.info/?probe=229db16a93) | Feb 05, 2021 |
| HP            | EliteBook 8570p             | [46c938b853](https://bsd-hardware.info/?probe=46c938b853) | Feb 01, 2021 |
| Matsushita... | CF-T2BW1AXR                 | [c16cd20c42](https://bsd-hardware.info/?probe=c16cd20c42) | Jan 25, 2021 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 29        | 96.67%  |
| i386  | 1         | 3.33%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KDE5          | 8         | 24.24%  |
| XFCE          | 4         | 12.12%  |
| Console       | 4         | 12.12%  |
| MATE          | 3         | 9.09%   |
| GNOME         | 3         | 9.09%   |
| Cinnamon      | 3         | 9.09%   |
| i3            | 2         | 6.06%   |
| TWM           | 1         | 3.03%   |
| LXQt          | 1         | 3.03%   |
| LXDE          | 1         | 3.03%   |
| Lumina        | 1         | 3.03%   |
| Fluxbox       | 1         | 3.03%   |
| Enlightenment | 1         | 3.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 26        | 81.25%  |
| Console | 6         | 18.75%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 11        | 35.48%  |
| SDDM    | 7         | 22.58%  |
| XDM     | 4         | 12.9%   |
| SLiM    | 4         | 12.9%   |
| GDM     | 4         | 12.9%   |
| LightDM | 1         | 3.23%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Notebooks | Percent |
|------------------|-----------|---------|
| C                | 22        | 68.75%  |
| en_US            | 2         | 6.25%   |
| en_GB            | 2         | 6.25%   |
| zh_CN            | 1         | 3.13%   |
| pt_PT            | 1         | 3.13%   |
| pl_PL            | 1         | 3.13%   |
| it_IT.ISO8859-15 | 1         | 3.13%   |
| fr_FR            | 1         | 3.13%   |
| Unknown          | 1         | 3.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 28        | 93.33%  |
| BIOS | 2         | 6.67%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Zfs  | 25        | 83.33%  |
| Ufs  | 5         | 16.67%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 29        | 96.67%  |
| MBR  | 1         | 3.33%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 14        | 46.67%  |
| Hewlett-Packard                | 6         | 20%     |
| Dell                           | 4         | 13.33%  |
| Matsushita Electric Industrial | 1         | 3.33%   |
| HUAWEI                         | 1         | 3.33%   |
| Framework                      | 1         | 3.33%   |
| Avell High Performance         | 1         | 3.33%   |
| ASUSTek Computer               | 1         | 3.33%   |
| A-DATA Technology              | 1         | 3.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| HP EliteBook 8570p                         | 3         | 10%     |
| Matsushita Electric Industrial CF-T2BW1AXR | 1         | 3.33%   |
| Lenovo XiaoXinPro-13ARE 2020 82DM          | 1         | 3.33%   |
| Lenovo ThinkPad X395 20NL001SMX            | 1         | 3.33%   |
| Lenovo ThinkPad X395 20NL000GPG            | 1         | 3.33%   |
| Lenovo ThinkPad X270 20HM004JBR            | 1         | 3.33%   |
| Lenovo ThinkPad X1 Extreme 20MF000BUS      | 1         | 3.33%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS1QC00   | 1         | 3.33%   |
| Lenovo ThinkPad T495s 20QKS1812F           | 1         | 3.33%   |
| Lenovo ThinkPad T430 2349H2G               | 1         | 3.33%   |
| Lenovo ThinkPad P15 Gen 1 20ST005VRT       | 1         | 3.33%   |
| Lenovo ThinkPad E14 20RBCTO1WW             | 1         | 3.33%   |
| Lenovo Legion 5P 15IMH05H 82AW             | 1         | 3.33%   |
| Lenovo Legion 5 15IMH05 82AU               | 1         | 3.33%   |
| Lenovo IdeaPad 330-15ARR 81D2              | 1         | 3.33%   |
| HUAWEI HN-WX9X                             | 1         | 3.33%   |
| HP ZBook 17 G2                             | 1         | 3.33%   |
| HP ProBook 455 G7                          | 1         | 3.33%   |
| HP ProBook 440 G7                          | 1         | 3.33%   |
| Framework Laptop                           | 1         | 3.33%   |
| Dell Vostro 5490                           | 1         | 3.33%   |
| Dell Latitude E5430 vPro                   | 1         | 3.33%   |
| Dell Inspiron 3793                         | 1         | 3.33%   |
| Dell G5 5505                               | 1         | 3.33%   |
| Avell High Performance A62 LIV             | 1         | 3.33%   |
| ASUS VivoBook_ASUSLaptop X512DA_F512DA     | 1         | 3.33%   |
| A-DATA XENIA159GENI72060                   | 1         | 3.33%   |
| Unknown                                    | 1         | 3.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo ThinkPad                            | 9         | 30%     |
| HP EliteBook                               | 3         | 10%     |
| Lenovo Legion                              | 2         | 6.67%   |
| HP ProBook                                 | 2         | 6.67%   |
| Matsushita Electric Industrial CF-T2BW1AXR | 1         | 3.33%   |
| Lenovo XiaoXinPro-13ARE                    | 1         | 3.33%   |
| Lenovo IdeaPad                             | 1         | 3.33%   |
| HUAWEI HN-WX9X                             | 1         | 3.33%   |
| HP ZBook                                   | 1         | 3.33%   |
| Framework Laptop                           | 1         | 3.33%   |
| Dell Vostro                                | 1         | 3.33%   |
| Dell Latitude                              | 1         | 3.33%   |
| Dell Inspiron                              | 1         | 3.33%   |
| Dell G5                                    | 1         | 3.33%   |
| Avell High Performance A62                 | 1         | 3.33%   |
| ASUS VivoBook                              | 1         | 3.33%   |
| A-DATA XENIA159GENI72060                   | 1         | 3.33%   |
| Unknown                                    | 1         | 3.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 15        | 50%     |
| 2019 | 5         | 16.67%  |
| 2021 | 3         | 10%     |
| 2018 | 2         | 6.67%   |
| 2017 | 2         | 6.67%   |
| 2015 | 1         | 3.33%   |
| 2013 | 1         | 3.33%   |
| 2003 | 1         | 3.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 30        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 30        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 15        | 48.39%  |
| 8.01-16.0   | 7         | 22.58%  |
| 32.01-64.0  | 4         | 12.9%   |
| 64.01-256.0 | 3         | 9.68%   |
| 4.01-8.0    | 1         | 3.23%   |
| 1.01-2.0    | 1         | 3.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.51-1.0   | 14        | 46.67%  |
| 2.01-3.0   | 6         | 20%     |
| 1.01-2.0   | 4         | 13.33%  |
| 3.01-4.0   | 2         | 6.67%   |
| 0.01-0.5   | 2         | 6.67%   |
| 24.01-32.0 | 1         | 3.33%   |
| 8.01-16.0  | 1         | 3.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 18        | 56.25%  |
| 2      | 13        | 40.63%  |
| 3      | 1         | 3.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 25        | 80.65%  |
| Yes       | 6         | 19.35%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 26        | 86.67%  |
| No        | 4         | 13.33%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 22        | 70.97%  |
| No        | 9         | 29.03%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| UK          | 6         | 20%     |
| Russia      | 4         | 13.33%  |
| Brazil      | 3         | 10%     |
| USA         | 2         | 6.67%   |
| Portugal    | 2         | 6.67%   |
| Poland      | 2         | 6.67%   |
| China       | 2         | 6.67%   |
| Switzerland | 1         | 3.33%   |
| Sweden      | 1         | 3.33%   |
| Peru        | 1         | 3.33%   |
| Japan       | 1         | 3.33%   |
| Italy       | 1         | 3.33%   |
| India       | 1         | 3.33%   |
| Germany     | 1         | 3.33%   |
| Croatia     | 1         | 3.33%   |
| Bangladesh  | 1         | 3.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Brighton       | 5         | 14.29%  |
| Moscow         | 2         | 5.71%   |
| London         | 2         | 5.71%   |
| Ōta-ku        | 1         | 2.86%   |
| Zurich         | 1         | 2.86%   |
| Wuhan          | 1         | 2.86%   |
| Wieliczka      | 1         | 2.86%   |
| Vancouver      | 1         | 2.86%   |
| Trosa          | 1         | 2.86%   |
| Thrissur       | 1         | 2.86%   |
| St Petersburg  | 1         | 2.86%   |
| Slavonski Brod | 1         | 2.86%   |
| Seattle        | 1         | 2.86%   |
| Resana         | 1         | 2.86%   |
| Poulsbo        | 1         | 2.86%   |
| Pobiedziska    | 1         | 2.86%   |
| Milan          | 1         | 2.86%   |
| Maia           | 1         | 2.86%   |
| Lima           | 1         | 2.86%   |
| Khabarovsk     | 1         | 2.86%   |
| João Pessoa   | 1         | 2.86%   |
| Ilhavo         | 1         | 2.86%   |
| Fuchu          | 1         | 2.86%   |
| Farnham        | 1         | 2.86%   |
| Eilenburg      | 1         | 2.86%   |
| Dhaka          | 1         | 2.86%   |
| Brasília      | 1         | 2.86%   |
| Beijing        | 1         | 2.86%   |
| Araruama       | 1         | 2.86%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 12     | 21.95%  |
| WDC                 | 7         | 11     | 17.07%  |
| Toshiba             | 5         | 8      | 12.2%   |
| HGST                | 5         | 12     | 12.2%   |
| SK Hynix            | 3         | 3      | 7.32%   |
| Crucial             | 2         | 4      | 4.88%   |
| A-DATA Technology   | 2         | 2      | 4.88%   |
| Solid State Storage | 1         | 1      | 2.44%   |
| Silicon Motion      | 1         | 1      | 2.44%   |
| Seagate             | 1         | 1      | 2.44%   |
| SanDisk             | 1         | 1      | 2.44%   |
| LITEON              | 1         | 1      | 2.44%   |
| Kingston            | 1         | 2      | 2.44%   |
| Intel               | 1         | 1      | 2.44%   |
| Fujitsu             | 1         | 2      | 2.44%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB                           | 5         | 11.36%  |
| HGST HTS725050A7E630 500GB                         | 4         | 9.09%   |
| WDC PC SN730 NVMe 1024GB                           | 2         | 4.55%   |
| Samsung HM251JX 250GB                              | 2         | 4.55%   |
| HGST HTS721010A9E630 1TB                           | 2         | 4.55%   |
| WDC WDS100T3X0C-00SJG0 1TB                         | 1         | 2.27%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB               | 1         | 2.27%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB               | 1         | 2.27%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB               | 1         | 2.27%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB               | 1         | 2.27%   |
| Solid State Storage CL1-3D128-Q11 NVMe SSSTC 128GB | 1         | 2.27%   |
| SK Hynix PC300 HFS512GD9MND-5510A 512GB            | 1         | 2.27%   |
| SK Hynix BC511 NVMe 256GB                          | 1         | 2.27%   |
| SK Hynix BC511 HFM256GDJTNI-82A0A 256GB            | 1         | 2.27%   |
| Silicon Motion NE-256 256GB                        | 1         | 2.27%   |
| Seagate ST1000LM035-1RK172 1TB                     | 1         | 2.27%   |
| SanDisk SDSSDH3500G 500GB                          | 1         | 2.27%   |
| Samsung SSD 970 EVO 1TB                            | 1         | 2.27%   |
| Samsung SSD 860 EVO 500GB                          | 1         | 2.27%   |
| Samsung SSD 850 EVO 250GB                          | 1         | 2.27%   |
| Samsung MZVLB512HBJQ-000L7 512GB                   | 1         | 2.27%   |
| Samsung MZVLB512HBJQ-000L2 512GB                   | 1         | 2.27%   |
| Samsung MZVLB256HBHQ-000L7 256GB                   | 1         | 2.27%   |
| Samsung MZVLB256HAHQ-00000 256GB                   | 1         | 2.27%   |
| Samsung MZVLB1T0HBLR-000L2 1TB                     | 1         | 2.27%   |
| Samsung MZMTD128HAFV-000L1 128GB                   | 1         | 2.27%   |
| LITEON LCH-256V2S 256GB                            | 1         | 2.27%   |
| Kingston RBUSNS8154P3256GJ3 256GB                  | 1         | 2.27%   |
| Intel SSDPEKNW512G8H 512GB                         | 1         | 2.27%   |
| Fujitsu MHS2040AT D 40GB                           | 1         | 2.27%   |
| Crucial CT480BX500SSD1 480GB                       | 1         | 2.27%   |
| Crucial CT2000P5SSD8 2TB                           | 1         | 2.27%   |
| A-DATA SX8200PNP 1TB                               | 1         | 2.27%   |
| A-DATA IM2P33F8BR2-512GB                           | 1         | 2.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 5         | 8      | 35.71%  |
| HGST                | 5         | 12     | 35.71%  |
| Samsung Electronics | 2         | 2      | 14.29%  |
| Seagate             | 1         | 1      | 7.14%   |
| Fujitsu             | 1         | 2      | 7.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 3      | 40%     |
| SanDisk             | 1         | 1      | 20%     |
| LITEON              | 1         | 1      | 20%     |
| Crucial             | 1         | 1      | 20%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 21        | 31     | 60%     |
| HDD  | 9         | 25     | 25.71%  |
| SSD  | 5         | 6      | 14.29%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 21        | 31     | 60%     |
| SATA | 14        | 31     | 40%     |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 12        | 27     | 80%     |
| 0.51-1.0   | 3         | 4      | 20%     |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 10        | 32.26%  |
| 101-250    | 8         | 25.81%  |
| 501-1000   | 5         | 16.13%  |
| 51-100     | 3         | 9.68%   |
| 21-50      | 2         | 6.45%   |
| 1-20       | 2         | 6.45%   |
| 1001-2000  | 1         | 3.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 16        | 51.61%  |
| 21-50   | 12        | 38.71%  |
| 101-250 | 3         | 9.68%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                      | Notebooks | Drives | Percent |
|----------------------------|-----------|--------|---------|
| HGST HTS725050A7E630 500GB | 4         | 9      | 66.67%  |
| HGST HTS721010A9E630 1TB   | 1         | 1      | 16.67%  |
| Fujitsu MHS2040AT D 40GB   | 1         | 2      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HGST    | 4         | 10     | 80%     |
| Fujitsu | 1         | 2      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HGST    | 4         | 10     | 80%     |
| Fujitsu | 1         | 2      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 12     | 100%    |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 29        | 48     | 80.56%  |
| Malfunc  | 5         | 12     | 13.89%  |
| Detected | 2         | 2      | 5.56%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 18        | 41.86%  |
| Sandisk                        | 7         | 16.28%  |
| Samsung Electronics            | 5         | 11.63%  |
| AMD                            | 4         | 9.3%    |
| SK Hynix                       | 3         | 6.98%   |
| ADATA Technology               | 2         | 4.65%   |
| Solid State Storage Technology | 1         | 2.33%   |
| Silicon Motion                 | 1         | 2.33%   |
| Micron Technology              | 1         | 2.33%   |
| Kingston Technology Company    | 1         | 2.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 6         | 13.95%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 11.63%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 5         | 11.63%  |
| AMD FCH SATA Controller [AHCI mode]                                            | 4         | 9.3%    |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 6.98%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3         | 6.98%   |
| Unknown                                                                        | 3         | 6.98%   |
| SK Hynix BC511                                                                 | 2         | 4.65%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 4.65%   |
| SK Hynix PC300 NVMe Solid State Drive 512GB                                    | 1         | 2.33%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1         | 2.33%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1         | 2.33%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 1         | 2.33%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 1         | 2.33%   |
| Intel SSD 660P Series                                                          | 1         | 2.33%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 2.33%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 2.33%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 1         | 2.33%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 1         | 2.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 21        | 50%     |
| SATA | 20        | 47.62%  |
| IDE  | 1         | 2.38%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 21        | 70%     |
| AMD    | 9         | 30%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i7-3520M CPU @ 2.90GHz               | 4         | 13.33%  |
| Intel Core i5-10210U CPU @ 1.60GHz              | 3         | 10%     |
| Intel Core i7-7600U CPU @ 2.80GHz               | 2         | 6.67%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 2         | 6.67%   |
| AMD Ryzen 5 PRO 3500U w/ Radeon Vega Mobile Gfx | 2         | 6.67%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 2         | 6.67%   |
| Intel Xeon W-10885M CPU @ 2.40GHz               | 1         | 3.33%   |
| Intel Pentium M processor 1000MHz               | 1         | 3.33%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 1         | 3.33%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 1         | 3.33%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz              | 1         | 3.33%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz              | 1         | 3.33%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz              | 1         | 3.33%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 1         | 3.33%   |
| Intel Core i5-10300H CPU @ 2.50GHz              | 1         | 3.33%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 1         | 3.33%   |
| AMD Ryzen 7 PRO 3700U w/ Radeon Vega Mobile Gfx | 1         | 3.33%   |
| AMD Ryzen 7 4800U with Radeon Graphics          | 1         | 3.33%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 1         | 3.33%   |
| AMD Ryzen 7 4700U with Radeon Graphics          | 1         | 3.33%   |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx   | 1         | 3.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel Core i7   | 13        | 43.33%  |
| Intel Core i5   | 5         | 16.67%  |
| AMD Ryzen 7     | 3         | 10%     |
| AMD Ryzen 5 PRO | 2         | 6.67%   |
| AMD Ryzen 5     | 2         | 6.67%   |
| Other           | 1         | 3.33%   |
| Intel Xeon      | 1         | 3.33%   |
| Intel Pentium M | 1         | 3.33%   |
| AMD Ryzen 7 PRO | 1         | 3.33%   |
| AMD Ryzen 3     | 1         | 3.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 9         | 30%     |
| 8      | 7         | 23.33%  |
| 2      | 7         | 23.33%  |
| 6      | 4         | 13.33%  |
| 16     | 2         | 6.67%   |
| 1      | 1         | 3.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 30        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 20        | 66.67%  |
| 1       | 9         | 30%     |
| Unknown | 1         | 3.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| KabyLake  | 7         | 23.33%  |
| Zen+      | 5         | 16.67%  |
| IvyBridge | 5         | 16.67%  |
| CometLake | 4         | 13.33%  |
| Zen 2     | 3         | 10%     |
| Haswell   | 2         | 6.67%   |
| Zen       | 1         | 3.33%   |
| TigerLake | 1         | 3.33%   |
| P6        | 1         | 3.33%   |
| IceLake   | 1         | 3.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 16        | 42.11%  |
| AMD    | 12        | 31.58%  |
| Nvidia | 10        | 26.32%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| AMD Picasso                                                      | 5         | 12.82%  |
| Intel CometLake-U GT2 [UHD Graphics]                             | 3         | 7.69%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                         | 3         | 7.69%   |
| AMD Renoir                                                       | 3         | 7.69%   |
| Nvidia TU117M                                                    | 2         | 5.13%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                       | 2         | 5.13%   |
| Nvidia GP108M [GeForce MX230]                                    | 2         | 5.13%   |
| Intel HD Graphics 620                                            | 2         | 5.13%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                        | 2         | 5.13%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller      | 2         | 5.13%   |
| Intel 3rd Gen Core processor Graphics Controller                 | 2         | 5.13%   |
| Nvidia TU104GLM [Quadro RTX 5000 Mobile / Max-Q]                 | 1         | 2.56%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                       | 1         | 2.56%   |
| Nvidia GM107M [GeForce GTX 860M]                                 | 1         | 2.56%   |
| Nvidia GK107GLM [Quadro K1100M]                                  | 1         | 2.56%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                        | 1         | 2.56%   |
| Intel Iris Plus Graphics G7                                      | 1         | 2.56%   |
| Intel CometLake-H GT2 [UHD Graphics]                             | 1         | 2.56%   |
| Intel Comet Lake-H WS GT2 Integrated UHD Graphics Controller     | 1         | 2.56%   |
| Intel 82852/855GM Integrated Graphics Device                     | 1         | 2.56%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series] | 1         | 2.56%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]          | 1         | 2.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 11        | 35.48%  |
| Intel + Nvidia | 8         | 25.81%  |
| 1 x Intel      | 8         | 25.81%  |
| 1 x Nvidia     | 3         | 9.68%   |
| 2 x AMD        | 1         | 3.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 25        | 83.33%  |
| Proprietary | 5         | 16.67%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 65.63%  |
| 1.01-2.0   | 4         | 12.5%   |
| 0.51-1.0   | 3         | 9.38%   |
| 0.01-0.5   | 3         | 9.38%   |
| 3.01-4.0   | 1         | 3.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 8         | 22.22%  |
| BOE                 | 5         | 13.89%  |
| Philips             | 3         | 8.33%   |
| Hewlett-Packard     | 3         | 8.33%   |
| Chimei Innolux      | 3         | 8.33%   |
| AU Optronics        | 3         | 8.33%   |
| SDC                 | 1         | 2.78%   |
| Samsung Electronics | 1         | 2.78%   |
| PANDA               | 1         | 2.78%   |
| LGD                 | 1         | 2.78%   |
| Lenovo              | 1         | 2.78%   |
| InfoVision          | 1         | 2.78%   |
| Iiyama              | 1         | 2.78%   |
| HJW                 | 1         | 2.78%   |
| Dell                | 1         | 2.78%   |
| CSO                 | 1         | 2.78%   |
| Apple               | 1         | 2.78%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0258 1600x900 350x190mm 15.7-inch          | 3         | 8.11%   |
| Philips LCD Monitor PHL08C3 1920x1080 600x340mm 27.2-inch            | 2         | 5.41%   |
| SDC LCD Monitor 3520x1080                                            | 1         | 2.7%    |
| Samsung Electronics LCD Monitor SDC3754 1600x900 380x210mm 17.1-inch | 1         | 2.7%    |
| Philips LCD Monitor 271P4 3520x1080                                  | 1         | 2.7%    |
| Philips LCD Monitor 271P4                                            | 1         | 2.7%    |
| PANDA LCD Monitor NCP004F 1920x1080 310x170mm 13.9-inch              | 1         | 2.7%    |
| LGD LCD Monitor 1920x1080                                            | 1         | 2.7%    |
| LG Display LCD Monitor LGD062E 1920x1080 340x190mm 15.3-inch         | 1         | 2.7%    |
| LG Display LCD Monitor LGD060A 1920x1080 290x170mm 13.2-inch         | 1         | 2.7%    |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch         | 1         | 2.7%    |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch         | 1         | 2.7%    |
| LG Display LCD Monitor LGD033E 1366x768 310x170mm 13.9-inch          | 1         | 2.7%    |
| Lenovo LEN P44w-10 LEN61D5 3840x1200 1050x330mm 43.3-inch            | 1         | 2.7%    |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch         | 1         | 2.7%    |
| Iiyama PL2474H IVM6146 1920x1080 520x290mm 23.4-inch                 | 1         | 2.7%    |
| HJW HDMI TO USB HJW0001 1920x1080 700x390mm 31.5-inch                | 1         | 2.7%    |
| Hewlett-Packard LCD Monitor LA2306 3520x1080                         | 1         | 2.7%    |
| Hewlett-Packard LA2306 HWP2949 1920x1080 510x290mm 23.1-inch         | 1         | 2.7%    |
| Hewlett-Packard E242 HWP326E 1920x1200 520x320mm 24.0-inch           | 1         | 2.7%    |
| Dell U2718Q DELA0EC 3840x2160 610x350mm 27.7-inch                    | 1         | 2.7%    |
| CSO LCD Monitor CSO1500 3840x2160 340x190mm 15.3-inch                | 1         | 2.7%    |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 280x180mm 13.1-inch     | 1         | 2.7%    |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 340x190mm 15.3-inch     | 1         | 2.7%    |
| Chimei Innolux LCD Monitor CMN13A2 1920x1080 290x170mm 13.2-inch     | 1         | 2.7%    |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                | 1         | 2.7%    |
| BOE LCD Monitor BOE084D 1920x1080 340x190mm 15.3-inch                | 1         | 2.7%    |
| BOE LCD Monitor BOE07F1 1920x1080 340x190mm 15.3-inch                | 1         | 2.7%    |
| BOE LCD Monitor BOE0792 1920x1080 340x190mm 15.3-inch                | 1         | 2.7%    |
| BOE LCD Monitor BOE0747 1920x1080 340x190mm 15.3-inch                | 1         | 2.7%    |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch        | 1         | 2.7%    |
| AU Optronics LCD Monitor AUO2026 2560x1600 290x180mm 13.4-inch       | 1         | 2.7%    |
| AU Optronics LCD Monitor AUO139D 1920x1080 380x210mm 17.1-inch       | 1         | 2.7%    |
| Apple Cinema HD APP9223 1920x1200 490x310mm 22.8-inch                | 1         | 2.7%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 18        | 52.94%  |
| 1600x900 (HD+)    | 5         | 14.71%  |
| 3840x2160 (4K)    | 2         | 5.88%   |
| 1920x1200 (WUXGA) | 2         | 5.88%   |
| 3840x1200         | 1         | 2.94%   |
| 3520x1080         | 1         | 2.94%   |
| 2560x1600         | 1         | 2.94%   |
| 2256x1504         | 1         | 2.94%   |
| 2160x1440         | 1         | 2.94%   |
| 1366x768 (WXGA)   | 1         | 2.94%   |
| Unknown           | 1         | 2.94%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 10        | 29.41%  |
| 13      | 10        | 29.41%  |
| 27      | 3         | 8.82%   |
| 23      | 2         | 5.88%   |
| 17      | 2         | 5.88%   |
| Unknown | 2         | 5.88%   |
| 43      | 1         | 2.94%   |
| 31      | 1         | 2.94%   |
| 24      | 1         | 2.94%   |
| 22      | 1         | 2.94%   |
| 12      | 1         | 2.94%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 15        | 45.45%  |
| 201-300     | 6         | 18.18%  |
| 501-600     | 4         | 12.12%  |
| 601-700     | 2         | 6.06%   |
| 351-400     | 2         | 6.06%   |
| Unknown     | 2         | 6.06%   |
| 401-500     | 1         | 3.03%   |
| 1001-1500   | 1         | 3.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 21        | 72.41%  |
| 16/10   | 4         | 13.79%  |
| Unknown | 2         | 6.9%    |
| 3/2     | 1         | 3.45%   |
| 3.18    | 1         | 3.45%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 7         | 20.59%  |
| 91-100         | 7         | 20.59%  |
| 71-80          | 3         | 8.82%   |
| 301-350        | 3         | 8.82%   |
| 201-250        | 3         | 8.82%   |
| 101-110        | 3         | 8.82%   |
| 121-130        | 2         | 5.88%   |
| Unknown        | 2         | 5.88%   |
| 61-70          | 1         | 2.94%   |
| 351-500        | 1         | 2.94%   |
| 251-300        | 1         | 2.94%   |
| 501-1000       | 1         | 2.94%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 12        | 36.36%  |
| 51-100        | 7         | 21.21%  |
| 161-240       | 6         | 18.18%  |
| 101-120       | 5         | 15.15%  |
| Unknown       | 2         | 6.06%   |
| More than 240 | 1         | 3.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 17        | 54.84%  |
| 2     | 7         | 22.58%  |
| 0     | 6         | 19.35%  |
| 3     | 1         | 3.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 27        | 48.21%  |
| Realtek Semiconductor | 17        | 30.36%  |
| TP-Link               | 3         | 5.36%   |
| Hewlett-Packard       | 3         | 5.36%   |
| D-Link System         | 2         | 3.57%   |
| Ralink Technology     | 1         | 1.79%   |
| Qualcomm Atheros      | 1         | 1.79%   |
| Lenovo                | 1         | 1.79%   |
| BUFFALO               | 1         | 1.79%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 14        | 20%     |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 5         | 7.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 5         | 7.14%   |
| Intel Wireless-AC 9260                                                     | 4         | 5.71%   |
| Intel Comet Lake PCH CNVi WiFi                                             | 4         | 5.71%   |
| Intel Wireless 8265 / 8275                                                 | 3         | 4.29%   |
| Intel Wi-Fi 6 AX200                                                        | 3         | 4.29%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                          | 3         | 4.29%   |
| HP hs2350 HSPA+ Mobile Broadband Module Network Adapter                    | 3         | 4.29%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 2         | 2.86%   |
| Intel Wireless 7260                                                        | 2         | 2.86%   |
| Intel Ethernet Connection (4) I219-LM                                      | 2         | 2.86%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 2         | 2.86%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]        | 1         | 1.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 1.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 1.43%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                     | 1         | 1.43%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 1         | 1.43%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 1         | 1.43%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 1         | 1.43%   |
| Ralink MT7601U Wireless Adapter                                            | 1         | 1.43%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 1         | 1.43%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                           | 1         | 1.43%   |
| Intel Wi-Fi 6 AX201                                                        | 1         | 1.43%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                  | 1         | 1.43%   |
| Intel Ethernet Connection I217-LM                                          | 1         | 1.43%   |
| Intel Ethernet Connection (7) I219-V                                       | 1         | 1.43%   |
| Intel Ethernet Connection (11) I219-LM                                     | 1         | 1.43%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 1         | 1.43%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller          | 1         | 1.43%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]                   | 1         | 1.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 27        | 69.23%  |
| Realtek Semiconductor | 4         | 10.26%  |
| TP-Link               | 3         | 7.69%   |
| D-Link System         | 2         | 5.13%   |
| Ralink Technology     | 1         | 2.56%   |
| Qualcomm Atheros      | 1         | 2.56%   |
| BUFFALO               | 1         | 2.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 5         | 12.82%  |
| Intel Wireless-AC 9260                                                     | 4         | 10.26%  |
| Intel Comet Lake PCH CNVi WiFi                                             | 4         | 10.26%  |
| Intel Wireless 8265 / 8275                                                 | 3         | 7.69%   |
| Intel Wi-Fi 6 AX200                                                        | 3         | 7.69%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                          | 3         | 7.69%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 2         | 5.13%   |
| Intel Wireless 7260                                                        | 2         | 5.13%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 2         | 5.13%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]        | 1         | 2.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 2.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 2.56%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                     | 1         | 2.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 1         | 2.56%   |
| Ralink MT7601U Wireless Adapter                                            | 1         | 2.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 1         | 2.56%   |
| Intel Wi-Fi 6 AX201                                                        | 1         | 2.56%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                  | 1         | 2.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 1         | 2.56%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]                   | 1         | 2.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 16        | 59.26%  |
| Intel                 | 10        | 37.04%  |
| Lenovo                | 1         | 3.7%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 14        | 51.85%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 18.52%  |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 7.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 3.7%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 3.7%    |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                  | 1         | 3.7%    |
| Intel Ethernet Connection I217-LM                                 | 1         | 3.7%    |
| Intel Ethernet Connection (7) I219-V                              | 1         | 3.7%    |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 3.7%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 30        | 50%     |
| Ethernet | 26        | 43.33%  |
| Modem    | 4         | 6.67%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 25        | 55.56%  |
| WiFi     | 18        | 40%     |
| Modem    | 2         | 4.44%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 26        | 86.67%  |
| 1     | 4         | 13.33%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 27        | 81.82%  |
| Yes  | 6         | 18.18%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 19        | 86.36%  |
| Realtek Semiconductor | 1         | 4.55%   |
| Realtek               | 1         | 4.55%   |
| Broadcom              | 1         | 4.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                          | 6         | 27.27%  |
| Intel Bluetooth wireless interface             | 4         | 18.18%  |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 3         | 13.64%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 3         | 13.64%  |
| Intel AX200 Bluetooth                          | 3         | 13.64%  |
| Realtek  Bluetooth Adapter                     | 1         | 4.55%   |
| Realtek Bluetooth Radio                        | 1         | 4.55%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 1         | 4.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Intel       | 21        | 48.84%  |
| AMD         | 12        | 27.91%  |
| Nvidia      | 7         | 16.28%  |
| Lenovo      | 2         | 4.65%   |
| CMX Systems | 1         | 2.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                 | 9         | 16.67%  |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 6         | 11.11%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 5         | 9.26%   |
| Intel Comet Lake PCH cAVS                                           | 4         | 7.41%   |
| Intel Comet Lake PCH-LP cAVS                                        | 3         | 5.56%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]           | 3         | 5.56%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 3         | 5.56%   |
| Nvidia TU116 High Definition Audio Controller                       | 2         | 3.7%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller      | 2         | 3.7%    |
| Intel Sunrise Point-LP HD Audio                                     | 2         | 3.7%    |
| Intel Cannon Lake PCH cAVS                                          | 2         | 3.7%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 2         | 3.7%    |
| Nvidia TU104 HD Audio Controller                                    | 1         | 1.85%   |
| Nvidia GP107GL High Definition Audio Controller                     | 1         | 1.85%   |
| Nvidia GK107 HDMI Audio Controller                                  | 1         | 1.85%   |
| Lenovo ThinkPad Dock Audio                                          | 1         | 1.85%   |
| Lenovo Realtek USB Audio                                            | 1         | 1.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 1         | 1.85%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller         | 1         | 1.85%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller           | 1         | 1.85%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller   | 1         | 1.85%   |
| CMX Systems USB PnP Audio Device                                    | 1         | 1.85%   |
| AMD Navi 10 HDMI Audio                                              | 1         | 1.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 10        | 28.57%  |
| SK Hynix            | 6         | 17.14%  |
| Micron Technology   | 5         | 14.29%  |
| Kingston            | 5         | 14.29%  |
| Smart               | 2         | 5.71%   |
| Crucial             | 2         | 5.71%   |
| Unknown             | 1         | 2.86%   |
| Ramaxel Technology  | 1         | 2.86%   |
| PNY                 | 1         | 2.86%   |
| GOODRAM             | 1         | 2.86%   |
| A-DATA Technology   | 1         | 2.86%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s        | 4         | 11.43%  |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 5.71%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s       | 2         | 5.71%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s        | 2         | 5.71%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s         | 2         | 5.71%   |
| Crucial RAM BL32G32C16S4B.M16FB1 32GB SODIMM DDR4 2667MT/s   | 2         | 5.71%   |
| Unknown RAM Module 1GB SODIMM DDR                            | 1         | 2.86%   |
| Smart RAM SF4641G8CK8IWGKSEG 8GB SODIMM DDR4 2133MT/s        | 1         | 2.86%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s        | 1         | 2.86%   |
| SK Hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s      | 1         | 2.86%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 2.86%   |
| Samsung RAM M474A4G43AB1-CVF 32GB SODIMM DDR4 2933MT/s       | 1         | 2.86%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s       | 1         | 2.86%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 2.86%   |
| Samsung RAM K4EBE304EB-EGCF 8GB Row Of Chips LPDDR3 1867MT/s | 1         | 2.86%   |
| Ramaxel RAM RMSA3320MJ78HAF-3200 8GB SODIMM DDR4 3200MT/s    | 1         | 2.86%   |
| PNY RAM 16GU2X16LIII43-12-K 16GB SODIMM DDR4 2667MT/s        | 1         | 2.86%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                   | 1         | 2.86%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s   | 1         | 2.86%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s        | 1         | 2.86%   |
| Kingston RAM Module 16GB SODIMM DDR4 2667MT/s                | 1         | 2.86%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 2933MT/s         | 1         | 2.86%   |
| Kingston RAM KHX2400C14S4/4G 4GB SODIMM DDR4 2400MT/s        | 1         | 2.86%   |
| Kingston RAM 99U5428-063.A00LF 8GB SODIMM DDR3 1600MT/s      | 1         | 2.86%   |
| Kingston RAM 9905428-196.A00LF 8GB SODIMM DDR3 1333MT/s      | 1         | 2.86%   |
| GOODRAM RAM GR1600S364L11/8G 8GB SODIMM DDR3 1600MT/s        | 1         | 2.86%   |
| A-DATA RAM DDR4 3200 16GB SODIMM DDR4 2667MT/s               | 1         | 2.86%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 21        | 70%     |
| DDR3   | 7         | 23.33%  |
| LPDDR3 | 1         | 3.33%   |
| DDR    | 1         | 3.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 28        | 93.33%  |
| Row Of Chips | 2         | 6.67%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 18        | 60%     |
| 16384 | 5         | 16.67%  |
| 32768 | 3         | 10%     |
| 4096  | 3         | 10%     |
| 1024  | 1         | 3.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 14        | 45.16%  |
| 1600    | 6         | 19.35%  |
| 3200    | 3         | 9.68%   |
| 2933    | 2         | 6.45%   |
| 2400    | 2         | 6.45%   |
| 2133    | 1         | 3.23%   |
| 1867    | 1         | 3.23%   |
| 1333    | 1         | 3.23%   |
| Unknown | 1         | 3.23%   |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 8         | 25.81%  |
| IMC Networks                           | 7         | 22.58%  |
| Lite-On Technology                     | 4         | 12.9%   |
| Realtek Semiconductor                  | 3         | 9.68%   |
| Logitech                               | 3         | 9.68%   |
| Acer                                   | 2         | 6.45%   |
| Syntek                                 | 1         | 3.23%   |
| Sunplus Innovation Technology          | 1         | 3.23%   |
| Microdia                               | 1         | 3.23%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.23%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                           | 4         | 12.5%   |
| Chicony Integrated HP HD Webcam                                          | 3         | 9.38%   |
| Chicony Integrated Camera                                                | 3         | 9.38%   |
| Logitech Webcam C270                                                     | 2         | 6.25%   |
| Lite-On Integrated Camera                                                | 2         | 6.25%   |
| Lite-On HP HD Camera                                                     | 2         | 6.25%   |
| Syntek Lenovo EasyCamera                                                 | 1         | 3.13%   |
| Sunplus Integrated_Webcam_HD                                             | 1         | 3.13%   |
| Realtek USB 2 Webcam                                                     | 1         | 3.13%   |
| Realtek Laptop Camera                                                    | 1         | 3.13%   |
| Realtek Integrated_Webcam_HD                                             | 1         | 3.13%   |
| Microdia Dell Integrated HD Webcam                                       | 1         | 3.13%   |
| Logitech HD Pro Webcam C920                                              | 1         | 3.13%   |
| IMC Networks USB2.0 HD UVC WebCam                                        | 1         | 3.13%   |
| IMC Networks HD Camera                                                   | 1         | 3.13%   |
| IMC Networks EasyCamera                                                  | 1         | 3.13%   |
| Chicony ThinkPad T490 Webcam                                             | 1         | 3.13%   |
| Chicony Integrated IR Camera                                             | 1         | 3.13%   |
| Chicony HD Webcam                                                        | 1         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 1         | 3.13%   |
| Acer Integrated Camera                                                   | 1         | 3.13%   |
| Acer HD Webcam                                                           | 1         | 3.13%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 6         | 50%     |
| Shenzhen Goodix Technology | 3         | 25%     |
| Validity Sensors           | 2         | 16.67%  |
| AuthenTec                  | 1         | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 3         | 25%     |
| Validity Sensors Synaptics WBDI                           | 2         | 16.67%  |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 16.67%  |
| Shenzhen Goodix Fingerprint Reader                        | 2         | 16.67%  |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 1         | 8.33%   |
| Shenzhen Goodix  FingerPrint Device                       | 1         | 8.33%   |
| AuthenTec AES2810                                         | 1         | 8.33%   |

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
| 2     | 9         | 29.03%  |
| 4     | 7         | 22.58%  |
| 3     | 5         | 16.13%  |
| 1     | 5         | 16.13%  |
| 5     | 3         | 9.68%   |
| 9     | 1         | 3.23%   |
| 0     | 1         | 3.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 23        | 31.94%  |
| Net/wireless             | 14        | 19.44%  |
| Bluetooth                | 13        | 18.06%  |
| Fingerprint reader       | 12        | 16.67%  |
| Card reader              | 5         | 6.94%   |
| Sound                    | 2         | 2.78%   |
| Firewire controller      | 2         | 2.78%   |
| Modem                    | 1         | 1.39%   |

