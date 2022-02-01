FreeBSD 14.0-CURRENT - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------------

A project to collect tested hardware configurations for FreeBSD 14.0-CURRENT.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://bsd-hardware.info/?view=trends

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
| Dell          | G3 3500                     | [536a7a1b38](https://bsd-hardware.info/?probe=536a7a1b38) | Jan 31, 2022 |
| HP            | EliteBook 8570p             | [f47789d894](https://bsd-hardware.info/?probe=f47789d894) | Jan 29, 2022 |
| MSI           | GE76 Raider 10UG            | [b48b628936](https://bsd-hardware.info/?probe=b48b628936) | Jan 27, 2022 |
| HP            | EliteBook 8570p             | [61406080a7](https://bsd-hardware.info/?probe=61406080a7) | Jan 18, 2022 |
| HP            | EliteBook 8570p             | [1520fece28](https://bsd-hardware.info/?probe=1520fece28) | Jan 17, 2022 |
| HP            | EliteBook 8570p             | [5f106ee686](https://bsd-hardware.info/?probe=5f106ee686) | Jan 15, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20T20... | [6836fc60f6](https://bsd-hardware.info/?probe=6836fc60f6) | Jan 09, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [6c208c85a5](https://bsd-hardware.info/?probe=6c208c85a5) | Jan 06, 2022 |
| HP            | EliteBook 8570p             | [1bbb37d4c6](https://bsd-hardware.info/?probe=1bbb37d4c6) | Jan 03, 2022 |
| HP            | EliteBook 8570p             | [0a180d834c](https://bsd-hardware.info/?probe=0a180d834c) | Jan 03, 2022 |
| HP            | EliteBook 8570p             | [b956c2a933](https://bsd-hardware.info/?probe=b956c2a933) | Dec 28, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [42b4bcbcc2](https://bsd-hardware.info/?probe=42b4bcbcc2) | Dec 27, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [695d7201d4](https://bsd-hardware.info/?probe=695d7201d4) | Dec 27, 2021 |
| HP            | EliteBook 8570p             | [44d3e7366c](https://bsd-hardware.info/?probe=44d3e7366c) | Dec 20, 2021 |
| HP            | EliteBook Folio 9470m       | [b872e9b044](https://bsd-hardware.info/?probe=b872e9b044) | Dec 18, 2021 |
| HP            | ProBook 440 G6              | [7a8a66430a](https://bsd-hardware.info/?probe=7a8a66430a) | Dec 13, 2021 |
| HP            | ProBook 440 G6              | [f3c014b120](https://bsd-hardware.info/?probe=f3c014b120) | Dec 12, 2021 |
| HP            | EliteBook 8570p             | [045ffeb9b3](https://bsd-hardware.info/?probe=045ffeb9b3) | Dec 12, 2021 |
| ASUSTek       | 1215B                       | [6dbcac684f](https://bsd-hardware.info/?probe=6dbcac684f) | Dec 04, 2021 |
| HP            | EliteBook 8570p             | [92fc69392b](https://bsd-hardware.info/?probe=92fc69392b) | Nov 27, 2021 |
| HP            | EliteBook 8570p             | [d3888a4c7d](https://bsd-hardware.info/?probe=d3888a4c7d) | Nov 21, 2021 |
| HP            | EliteBook 8570p             | [822a2481bb](https://bsd-hardware.info/?probe=822a2481bb) | Nov 17, 2021 |
| HP            | EliteBook 8570p             | [ea51e03be6](https://bsd-hardware.info/?probe=ea51e03be6) | Nov 13, 2021 |
| HP            | EliteBook 8570p             | [28a264a128](https://bsd-hardware.info/?probe=28a264a128) | Nov 09, 2021 |
| HP            | EliteBook 8570p             | [d0b487888a](https://bsd-hardware.info/?probe=d0b487888a) | Nov 08, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [e54d79065e](https://bsd-hardware.info/?probe=e54d79065e) | Nov 02, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [a71d3392eb](https://bsd-hardware.info/?probe=a71d3392eb) | Nov 02, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0PM0... | [7a61d90a55](https://bsd-hardware.info/?probe=7a61d90a55) | Oct 28, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [d910c79d75](https://bsd-hardware.info/?probe=d910c79d75) | Oct 24, 2021 |
| HP            | EliteBook 8570p             | [86613b04d3](https://bsd-hardware.info/?probe=86613b04d3) | Oct 17, 2021 |
| HP            | EliteBook 8570p             | [1b48acadd5](https://bsd-hardware.info/?probe=1b48acadd5) | Oct 10, 2021 |
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
| amd64 | 40        | 97.56%  |
| i386  | 1         | 2.44%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KDE5          | 12        | 27.27%  |
| XFCE          | 6         | 13.64%  |
| MATE          | 4         | 9.09%   |
| GNOME         | 4         | 9.09%   |
| Console       | 4         | 9.09%   |
| TWM           | 3         | 6.82%   |
| Cinnamon      | 3         | 6.82%   |
| i3            | 2         | 4.55%   |
| Picom         | 1         | 2.27%   |
| LXQt          | 1         | 2.27%   |
| LXDE          | 1         | 2.27%   |
| Lumina        | 1         | 2.27%   |
| Fluxbox       | 1         | 2.27%   |
| Enlightenment | 1         | 2.27%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 34        | 79.07%  |
| Console | 8         | 18.6%   |
| Wayland | 1         | 2.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 15        | 35.71%  |
| SDDM    | 12        | 28.57%  |
| GDM     | 6         | 14.29%  |
| XDM     | 4         | 9.52%   |
| SLiM    | 4         | 9.52%   |
| LightDM | 1         | 2.38%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Notebooks | Percent |
|------------------|-----------|---------|
| C                | 29        | 67.44%  |
| en_US            | 5         | 11.63%  |
| zh_CN            | 2         | 4.65%   |
| en_GB            | 2         | 4.65%   |
| pt_PT            | 1         | 2.33%   |
| pl_PL            | 1         | 2.33%   |
| it_IT.ISO8859-15 | 1         | 2.33%   |
| fr_FR            | 1         | 2.33%   |
| Unknown          | 1         | 2.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 38        | 92.68%  |
| BIOS | 3         | 7.32%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Zfs  | 33        | 80.49%  |
| Ufs  | 8         | 19.51%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 39        | 95.12%  |
| MBR  | 2         | 4.88%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 20        | 48.78%  |
| Hewlett-Packard                | 8         | 19.51%  |
| Dell                           | 5         | 12.2%   |
| ASUSTek Computer               | 2         | 4.88%   |
| MSI                            | 1         | 2.44%   |
| Matsushita Electric Industrial | 1         | 2.44%   |
| HUAWEI                         | 1         | 2.44%   |
| Framework                      | 1         | 2.44%   |
| Avell High Performance         | 1         | 2.44%   |
| A-DATA Technology              | 1         | 2.44%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| HP EliteBook 8570p                          | 3         | 7.32%   |
| MSI GE76 Raider 10UG                        | 1         | 2.44%   |
| Matsushita Electric Industrial CF-T2BW1AXR  | 1         | 2.44%   |
| Lenovo XiaoXinPro-13ARE 2020 82DM           | 1         | 2.44%   |
| Lenovo ThinkPad X395 20NL001SMX             | 1         | 2.44%   |
| Lenovo ThinkPad X395 20NL000GPG             | 1         | 2.44%   |
| Lenovo ThinkPad X270 20HM004JBR             | 1         | 2.44%   |
| Lenovo ThinkPad X13 Gen 1 20T2003PRT        | 1         | 2.44%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TLA055CD | 1         | 2.44%   |
| Lenovo ThinkPad X1 Extreme 20MF000BUS       | 1         | 2.44%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS1QC00    | 1         | 2.44%   |
| Lenovo ThinkPad T495s 20QKS1812F            | 1         | 2.44%   |
| Lenovo ThinkPad T470p 20J7S0PM00            | 1         | 2.44%   |
| Lenovo ThinkPad T430 2349H2G                | 1         | 2.44%   |
| Lenovo ThinkPad P15 Gen 1 20ST005VRT        | 1         | 2.44%   |
| Lenovo ThinkPad P14s Gen 1 20Y1CTO1WW       | 1         | 2.44%   |
| Lenovo ThinkPad E14 Gen 3 20Y7003SGE        | 1         | 2.44%   |
| Lenovo ThinkPad E14 20RBCTO1WW              | 1         | 2.44%   |
| Lenovo ThinkBook 14 G3 ACL 21A2             | 1         | 2.44%   |
| Lenovo Legion 5P 15IMH05H 82AW              | 1         | 2.44%   |
| Lenovo Legion 5 15IMH05 82AU                | 1         | 2.44%   |
| Lenovo IdeaPad 330-15ARR 81D2               | 1         | 2.44%   |
| HUAWEI HN-WX9X                              | 1         | 2.44%   |
| HP ZBook 17 G2                              | 1         | 2.44%   |
| HP ProBook 455 G7                           | 1         | 2.44%   |
| HP ProBook 440 G7                           | 1         | 2.44%   |
| HP ProBook 440 G6                           | 1         | 2.44%   |
| HP EliteBook Folio 9470m                    | 1         | 2.44%   |
| Framework Laptop                            | 1         | 2.44%   |
| Dell Vostro 5490                            | 1         | 2.44%   |
| Dell Latitude E5430 vPro                    | 1         | 2.44%   |
| Dell Inspiron 3793                          | 1         | 2.44%   |
| Dell G5 5505                                | 1         | 2.44%   |
| Dell G3 3500                                | 1         | 2.44%   |
| Avell High Performance A62 LIV              | 1         | 2.44%   |
| ASUS VivoBook_ASUSLaptop X512DA_F512DA      | 1         | 2.44%   |
| ASUS 1215B                                  | 1         | 2.44%   |
| A-DATA XENIA159GENI72060                    | 1         | 2.44%   |
| Unknown                                     | 1         | 2.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo ThinkPad                            | 14        | 34.15%  |
| HP EliteBook                               | 4         | 9.76%   |
| HP ProBook                                 | 3         | 7.32%   |
| Lenovo Legion                              | 2         | 4.88%   |
| MSI GE76                                   | 1         | 2.44%   |
| Matsushita Electric Industrial CF-T2BW1AXR | 1         | 2.44%   |
| Lenovo XiaoXinPro-13ARE                    | 1         | 2.44%   |
| Lenovo ThinkBook                           | 1         | 2.44%   |
| Lenovo IdeaPad                             | 1         | 2.44%   |
| HUAWEI HN-WX9X                             | 1         | 2.44%   |
| HP ZBook                                   | 1         | 2.44%   |
| Framework Laptop                           | 1         | 2.44%   |
| Dell Vostro                                | 1         | 2.44%   |
| Dell Latitude                              | 1         | 2.44%   |
| Dell Inspiron                              | 1         | 2.44%   |
| Dell G5                                    | 1         | 2.44%   |
| Dell G3                                    | 1         | 2.44%   |
| Avell High Performance A62                 | 1         | 2.44%   |
| ASUS VivoBook                              | 1         | 2.44%   |
| ASUS 1215B                                 | 1         | 2.44%   |
| A-DATA XENIA159GENI72060                   | 1         | 2.44%   |
| Unknown                                    | 1         | 2.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 15        | 36.59%  |
| 2021 | 8         | 19.51%  |
| 2019 | 6         | 14.63%  |
| 2013 | 4         | 9.76%   |
| 2017 | 3         | 7.32%   |
| 2018 | 2         | 4.88%   |
| 2015 | 1         | 2.44%   |
| 2011 | 1         | 2.44%   |
| 2003 | 1         | 2.44%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 41        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 41        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 21        | 50%     |
| 8.01-16.0   | 8         | 19.05%  |
| 32.01-64.0  | 6         | 14.29%  |
| 64.01-256.0 | 3         | 7.14%   |
| 4.01-8.0    | 2         | 4.76%   |
| 24.01-32.0  | 1         | 2.38%   |
| 1.01-2.0    | 1         | 2.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.51-1.0   | 19        | 46.34%  |
| 1.01-2.0   | 10        | 24.39%  |
| 2.01-3.0   | 6         | 14.63%  |
| 3.01-4.0   | 2         | 4.88%   |
| 0.01-0.5   | 2         | 4.88%   |
| 24.01-32.0 | 1         | 2.44%   |
| 8.01-16.0  | 1         | 2.44%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 27        | 62.79%  |
| 2      | 16        | 37.21%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 36        | 85.71%  |
| Yes       | 6         | 14.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 87.8%   |
| No        | 5         | 12.2%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 41        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 33        | 78.57%  |
| No        | 9         | 21.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| UK          | 6         | 14.63%  |
| Russia      | 5         | 12.2%   |
| China       | 4         | 9.76%   |
| USA         | 3         | 7.32%   |
| Germany     | 3         | 7.32%   |
| Brazil      | 3         | 7.32%   |
| Portugal    | 2         | 4.88%   |
| Poland      | 2         | 4.88%   |
| Austria     | 2         | 4.88%   |
| Turkey      | 1         | 2.44%   |
| Switzerland | 1         | 2.44%   |
| Sweden      | 1         | 2.44%   |
| Spain       | 1         | 2.44%   |
| Peru        | 1         | 2.44%   |
| Japan       | 1         | 2.44%   |
| Italy       | 1         | 2.44%   |
| India       | 1         | 2.44%   |
| Croatia     | 1         | 2.44%   |
| Belarus     | 1         | 2.44%   |
| Bangladesh  | 1         | 2.44%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Brighton       | 5         | 10.42%  |
| London         | 3         | 6.25%   |
| Moscow         | 2         | 4.17%   |
| Ōta-ku        | 1         | 2.08%   |
| Zurich         | 1         | 2.08%   |
| Wuhan          | 1         | 2.08%   |
| Worthing       | 1         | 2.08%   |
| Wieliczka      | 1         | 2.08%   |
| Vienna         | 1         | 2.08%   |
| Vancouver      | 1         | 2.08%   |
| Trosa          | 1         | 2.08%   |
| Thrissur       | 1         | 2.08%   |
| Stuttgart      | 1         | 2.08%   |
| St Petersburg  | 1         | 2.08%   |
| Slavonski Brod | 1         | 2.08%   |
| Seattle        | 1         | 2.08%   |
| Rostov-on-Don  | 1         | 2.08%   |
| Resana         | 1         | 2.08%   |
| Poulsbo        | 1         | 2.08%   |
| Pobiedziska    | 1         | 2.08%   |
| Montclair      | 1         | 2.08%   |
| Minsk          | 1         | 2.08%   |
| Milan          | 1         | 2.08%   |
| Maia           | 1         | 2.08%   |
| Madrid         | 1         | 2.08%   |
| Lima           | 1         | 2.08%   |
| Khabarovsk     | 1         | 2.08%   |
| João Pessoa   | 1         | 2.08%   |
| Istanbul       | 1         | 2.08%   |
| Ilhavo         | 1         | 2.08%   |
| Hangzhou       | 1         | 2.08%   |
| Guangzhou Shi  | 1         | 2.08%   |
| Graz           | 1         | 2.08%   |
| Fuchu          | 1         | 2.08%   |
| Farnham        | 1         | 2.08%   |
| Eilenburg      | 1         | 2.08%   |
| Dhaka          | 1         | 2.08%   |
| Brasília      | 1         | 2.08%   |
| Berlin         | 1         | 2.08%   |
| Beijing        | 1         | 2.08%   |
| Araruama       | 1         | 2.08%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 18     | 27.78%  |
| WDC                 | 10        | 15     | 18.52%  |
| Toshiba             | 6         | 13     | 11.11%  |
| HGST                | 5         | 16     | 9.26%   |
| SK Hynix            | 3         | 3      | 5.56%   |
| Kingston            | 3         | 5      | 5.56%   |
| Crucial             | 2         | 4      | 3.7%    |
| A-DATA Technology   | 2         | 2      | 3.7%    |
| Solid State Storage | 1         | 1      | 1.85%   |
| Silicon Motion      | 1         | 1      | 1.85%   |
| Seagate             | 1         | 1      | 1.85%   |
| SanDisk             | 1         | 1      | 1.85%   |
| LITEON              | 1         | 1      | 1.85%   |
| KIOXIA              | 1         | 1      | 1.85%   |
| Intel               | 1         | 1      | 1.85%   |
| Fujitsu             | 1         | 2      | 1.85%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB                           | 5         | 8.47%   |
| HGST HTS725050A7E630 500GB                         | 4         | 6.78%   |
| Samsung HM251JX 250GB                              | 3         | 5.08%   |
| WDC WDS100T3X0C-00SJG0 1TB                         | 2         | 3.39%   |
| WDC PC SN730 NVMe 1024GB                           | 2         | 3.39%   |
| Samsung MZVLB512HBJQ-000L7 512GB                   | 2         | 3.39%   |
| HGST HTS721010A9E630 1TB                           | 2         | 3.39%   |
| WDC WD10SPZX-60Z10T0 1TB                           | 1         | 1.69%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB               | 1         | 1.69%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB               | 1         | 1.69%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB                 | 1         | 1.69%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB               | 1         | 1.69%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB               | 1         | 1.69%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB               | 1         | 1.69%   |
| Toshiba KXG6APNV2T04 2TB                           | 1         | 1.69%   |
| Solid State Storage CL1-3D128-Q11 NVMe SSSTC 128GB | 1         | 1.69%   |
| SK Hynix PC300 HFS512GD9MND-5510A 512GB            | 1         | 1.69%   |
| SK Hynix BC511 NVMe 256GB                          | 1         | 1.69%   |
| SK Hynix BC511 HFM256GDJTNI-82A0A 256GB            | 1         | 1.69%   |
| Silicon Motion NE-256 256GB                        | 1         | 1.69%   |
| Seagate ST1000LM035-1RK172 1TB                     | 1         | 1.69%   |
| SanDisk SDSSDH3500G 500GB                          | 1         | 1.69%   |
| Samsung SSD 970 EVO 1TB                            | 1         | 1.69%   |
| Samsung SSD 860 EVO 500GB                          | 1         | 1.69%   |
| Samsung SSD 850 EVO 250GB                          | 1         | 1.69%   |
| Samsung SSD 840 PRO Series 128GB                   | 1         | 1.69%   |
| Samsung MZVLW256HEHP-000L7 256GB                   | 1         | 1.69%   |
| Samsung MZVLB512HBJQ-000L2 512GB                   | 1         | 1.69%   |
| Samsung MZVLB2T0HMLB-00000 2TB                     | 1         | 1.69%   |
| Samsung MZVLB256HBHQ-000L7 256GB                   | 1         | 1.69%   |
| Samsung MZVLB256HAHQ-00000 256GB                   | 1         | 1.69%   |
| Samsung MZVLB1T0HBLR-000L2 1TB                     | 1         | 1.69%   |
| Samsung MZMTD128HAFV-000L1 128GB                   | 1         | 1.69%   |
| Samsung MZALQ512HBLU-00BL1 512GB                   | 1         | 1.69%   |
| LITEON LCH-256V2S 256GB                            | 1         | 1.69%   |
| KIOXIA KBG40ZNS256G NVMe 256GB                     | 1         | 1.69%   |
| Kingston SUV500MS480G 480GB                        | 1         | 1.69%   |
| Kingston SUV500MS120G 120GB                        | 1         | 1.69%   |
| Kingston RBUSNS8154P3256GJ3 256GB                  | 1         | 1.69%   |
| Kingston OM8PCP3512F-AA 512GB                      | 1         | 1.69%   |
| Intel SSDPEKNW512G8H 512GB                         | 1         | 1.69%   |
| Fujitsu MHS2040AT D 40GB                           | 1         | 1.69%   |
| Crucial CT480BX500SSD1 480GB                       | 1         | 1.69%   |
| Crucial CT2000P5SSD8 2TB                           | 1         | 1.69%   |
| A-DATA SX8200PNP 1TB                               | 1         | 1.69%   |
| A-DATA IM2P33F8BR2-512GB                           | 1         | 1.69%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 5         | 12     | 31.25%  |
| HGST                | 5         | 16     | 31.25%  |
| Samsung Electronics | 3         | 3      | 18.75%  |
| WDC                 | 1         | 1      | 6.25%   |
| Seagate             | 1         | 1      | 6.25%   |
| Fujitsu             | 1         | 2      | 6.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 4      | 42.86%  |
| SanDisk             | 1         | 1      | 14.29%  |
| LITEON              | 1         | 1      | 14.29%  |
| Kingston            | 1         | 2      | 14.29%  |
| Crucial             | 1         | 1      | 14.29%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 30        | 41     | 63.83%  |
| HDD  | 10        | 35     | 21.28%  |
| SSD  | 7         | 9      | 14.89%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 30        | 41     | 63.83%  |
| SATA | 17        | 44     | 36.17%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 14        | 35     | 77.78%  |
| 0.51-1.0   | 4         | 9      | 22.22%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 13        | 30.23%  |
| 101-250    | 10        | 23.26%  |
| 501-1000   | 8         | 18.6%   |
| 51-100     | 4         | 9.3%    |
| 21-50      | 3         | 6.98%   |
| 1001-2000  | 3         | 6.98%   |
| 1-20       | 2         | 4.65%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 24        | 57.14%  |
| 21-50   | 14        | 33.33%  |
| 101-250 | 4         | 9.52%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| HGST HTS725050A7E630 500GB        | 4         | 9      | 50%     |
| WDC WD10SPZX-60Z10T0 1TB          | 1         | 1      | 12.5%   |
| Samsung Electronics HM251JX 250GB | 1         | 1      | 12.5%   |
| HGST HTS721010A9E630 1TB          | 1         | 5      | 12.5%   |
| Fujitsu MHS2040AT D 40GB          | 1         | 2      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 4         | 14     | 57.14%  |
| WDC                 | 1         | 1      | 14.29%  |
| Samsung Electronics | 1         | 1      | 14.29%  |
| Fujitsu             | 1         | 2      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 4         | 14     | 57.14%  |
| WDC                 | 1         | 1      | 14.29%  |
| Samsung Electronics | 1         | 1      | 14.29%  |
| Fujitsu             | 1         | 2      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 18     | 100%    |

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
| Works    | 40        | 65     | 83.33%  |
| Malfunc  | 6         | 18     | 12.5%   |
| Detected | 2         | 2      | 4.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 21        | 36.21%  |
| Sandisk                        | 10        | 17.24%  |
| Samsung Electronics            | 9         | 15.52%  |
| AMD                            | 6         | 10.34%  |
| SK Hynix                       | 3         | 5.17%   |
| Kingston Technology Company    | 2         | 3.45%   |
| ADATA Technology               | 2         | 3.45%   |
| Toshiba                        | 1         | 1.72%   |
| Solid State Storage Technology | 1         | 1.72%   |
| Silicon Motion                 | 1         | 1.72%   |
| Micron Technology              | 1         | 1.72%   |
| KIOXIA                         | 1         | 1.72%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 8         | 13.33%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 7         | 11.67%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 5         | 8.33%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 5         | 8.33%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 4         | 6.67%   |
| Unknown                                                                        | 4         | 6.67%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 5%      |
| SK Hynix BC511                                                                 | 2         | 3.33%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 3.33%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 2         | 3.33%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 2         | 3.33%   |
| Toshiba XG6 NVMe SSD Controller                                                | 1         | 1.67%   |
| SK Hynix PC300 NVMe Solid State Drive 512GB                                    | 1         | 1.67%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1         | 1.67%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1         | 1.67%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 1.67%   |
| Samsung NVMe SSD Controller 980                                                | 1         | 1.67%   |
| KIOXIA unknown                                                                 | 1         | 1.67%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 1         | 1.67%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 1         | 1.67%   |
| Intel SSD 660P Series                                                          | 1         | 1.67%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 1.67%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 1.67%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.67%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 1         | 1.67%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 1.67%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 1         | 1.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 30        | 52.63%  |
| SATA | 24        | 42.11%  |
| IDE  | 3         | 5.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 28        | 68.29%  |
| AMD    | 13        | 31.71%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i7-3520M CPU @ 2.90GHz               | 4         | 9.76%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 3         | 7.32%   |
| Intel Core i5-10210U CPU @ 1.60GHz              | 3         | 7.32%   |
| Intel Core i7-7600U CPU @ 2.80GHz               | 2         | 4.88%   |
| Intel Core i5-10300H CPU @ 2.50GHz              | 2         | 4.88%   |
| AMD Ryzen 5 PRO 3500U w/ Radeon Vega Mobile Gfx | 2         | 4.88%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 2         | 4.88%   |
| Intel Xeon W-10885M CPU @ 2.40GHz               | 1         | 2.44%   |
| Intel Pentium M processor 1000MHz               | 1         | 2.44%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 1         | 2.44%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 1         | 2.44%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 2.44%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 2.44%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz              | 1         | 2.44%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz              | 1         | 2.44%   |
| Intel Core i7-3687U CPU @ 2.10GHz               | 1         | 2.44%   |
| Intel Core i7-10870H CPU @ 2.20GHz              | 1         | 2.44%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz              | 1         | 2.44%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 1         | 2.44%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 1         | 2.44%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 1         | 2.44%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics      | 1         | 2.44%   |
| AMD Ryzen 7 PRO 3700U w/ Radeon Vega Mobile Gfx | 1         | 2.44%   |
| AMD Ryzen 7 5700U with Radeon Graphics          | 1         | 2.44%   |
| AMD Ryzen 7 4800U with Radeon Graphics          | 1         | 2.44%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 1         | 2.44%   |
| AMD Ryzen 7 4700U with Radeon Graphics          | 1         | 2.44%   |
| AMD Ryzen 5 5500U with Radeon Graphics          | 1         | 2.44%   |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx   | 1         | 2.44%   |
| AMD E-450 APU with Radeon HD Graphics           | 1         | 2.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel Core i7   | 19        | 46.34%  |
| Intel Core i5   | 6         | 14.63%  |
| AMD Ryzen 7     | 4         | 9.76%   |
| AMD Ryzen 5     | 3         | 7.32%   |
| AMD Ryzen 7 PRO | 2         | 4.88%   |
| AMD Ryzen 5 PRO | 2         | 4.88%   |
| Other           | 1         | 2.44%   |
| Intel Xeon      | 1         | 2.44%   |
| Intel Pentium M | 1         | 2.44%   |
| AMD Ryzen 3     | 1         | 2.44%   |
| AMD E           | 1         | 2.44%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 13        | 31.71%  |
| 2      | 9         | 21.95%  |
| 8      | 8         | 19.51%  |
| 6      | 5         | 12.2%   |
| 16     | 4         | 9.76%   |
| 12     | 1         | 2.44%   |
| 1      | 1         | 2.44%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 41        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 27        | 65.85%  |
| 1       | 13        | 31.71%  |
| Unknown | 1         | 2.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| KabyLake  | 10        | 24.39%  |
| CometLake | 7         | 17.07%  |
| IvyBridge | 6         | 14.63%  |
| Zen+      | 5         | 12.2%   |
| Zen 2     | 4         | 9.76%   |
| Haswell   | 2         | 4.88%   |
| Unknown   | 2         | 4.88%   |
| Zen       | 1         | 2.44%   |
| TigerLake | 1         | 2.44%   |
| P6        | 1         | 2.44%   |
| IceLake   | 1         | 2.44%   |
| Bobcat    | 1         | 2.44%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 23        | 42.59%  |
| AMD    | 16        | 29.63%  |
| Nvidia | 15        | 27.78%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series] | 5         | 9.09%   |
| Intel CometLake-U GT2 [UHD Graphics]                                 | 4         | 7.27%   |
| Intel CometLake-H GT2 [UHD Graphics]                                 | 4         | 7.27%   |
| AMD Renoir                                                           | 4         | 7.27%   |
| Nvidia TU117M                                                        | 3         | 5.45%   |
| Intel 3rd Gen Core processor Graphics Controller                     | 3         | 5.45%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                             | 3         | 5.45%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                           | 2         | 3.64%   |
| Nvidia GP108M [GeForce MX230]                                        | 2         | 3.64%   |
| Intel HD Graphics 620                                                | 2         | 3.64%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                            | 2         | 3.64%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller          | 2         | 3.64%   |
| AMD Lucienne                                                         | 2         | 3.64%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                           | 1         | 1.82%   |
| Nvidia TU104GLM [Quadro RTX 5000 Mobile / Max-Q]                     | 1         | 1.82%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                           | 1         | 1.82%   |
| Nvidia GM108M [GeForce MX130]                                        | 1         | 1.82%   |
| Nvidia GM108M [GeForce 940MX]                                        | 1         | 1.82%   |
| Nvidia GM107M [GeForce GTX 860M]                                     | 1         | 1.82%   |
| Nvidia GK107GLM [Quadro K1100M]                                      | 1         | 1.82%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                      | 1         | 1.82%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                           | 1         | 1.82%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                            | 1         | 1.82%   |
| Intel Iris Plus Graphics G7                                          | 1         | 1.82%   |
| Intel HD Graphics 630                                                | 1         | 1.82%   |
| Intel Comet Lake-H WS GT2 Integrated UHD Graphics Controller         | 1         | 1.82%   |
| Intel 82852/855GM Integrated Graphics Device                         | 1         | 1.82%   |
| AMD Wrestler [Radeon HD 6320]                                        | 1         | 1.82%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]     | 1         | 1.82%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]              | 1         | 1.82%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 15        | 35.71%  |
| Intel + Nvidia | 13        | 30.95%  |
| 1 x Intel      | 10        | 23.81%  |
| 1 x Nvidia     | 3         | 7.14%   |
| 2 x AMD        | 1         | 2.38%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 32        | 78.05%  |
| Proprietary | 9         | 21.95%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 31        | 72.09%  |
| 1.01-2.0   | 4         | 9.3%    |
| 0.51-1.0   | 4         | 9.3%    |
| 0.01-0.5   | 3         | 6.98%   |
| 3.01-4.0   | 1         | 2.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 9         | 21.43%  |
| BOE                 | 6         | 14.29%  |
| AU Optronics        | 5         | 11.9%   |
| Chimei Innolux      | 4         | 9.52%   |
| Philips             | 3         | 7.14%   |
| Hewlett-Packard     | 3         | 7.14%   |
| Sharp               | 1         | 2.38%   |
| SDC                 | 1         | 2.38%   |
| Samsung Electronics | 1         | 2.38%   |
| PANDA               | 1         | 2.38%   |
| LGD                 | 1         | 2.38%   |
| Lenovo              | 1         | 2.38%   |
| InfoVision          | 1         | 2.38%   |
| Iiyama              | 1         | 2.38%   |
| HJW                 | 1         | 2.38%   |
| Dell                | 1         | 2.38%   |
| CSO                 | 1         | 2.38%   |
| Apple               | 1         | 2.38%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0258 1600x900 350x190mm 15.7-inch          | 3         | 6.98%   |
| Philips LCD Monitor PHL08C3 1920x1080 600x340mm 27.2-inch            | 2         | 4.65%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 380x210mm 17.1-inch              | 1         | 2.33%   |
| SDC LCD Monitor 3520x1080                                            | 1         | 2.33%   |
| Samsung Electronics LCD Monitor SDC3754 1600x900 380x210mm 17.1-inch | 1         | 2.33%   |
| Philips LCD Monitor 271P4 3520x1080                                  | 1         | 2.33%   |
| Philips LCD Monitor 271P4                                            | 1         | 2.33%   |
| PANDA LCD Monitor NCP004F 1920x1080 310x170mm 13.9-inch              | 1         | 2.33%   |
| LGD LCD Monitor 1920x1080                                            | 1         | 2.33%   |
| LG Display LCD Monitor LGD062E 1920x1080 340x190mm 15.3-inch         | 1         | 2.33%   |
| LG Display LCD Monitor LGD060A 1920x1080 290x170mm 13.2-inch         | 1         | 2.33%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch         | 1         | 2.33%   |
| LG Display LCD Monitor LGD05F1 1920x1080 310x170mm 13.9-inch         | 1         | 2.33%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch         | 1         | 2.33%   |
| LG Display LCD Monitor LGD033E 1366x768 310x170mm 13.9-inch          | 1         | 2.33%   |
| Lenovo LEN P44w-10 LEN61D5 3840x1200 1050x330mm 43.3-inch            | 1         | 2.33%   |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch         | 1         | 2.33%   |
| Iiyama PL2474H IVM6146 1920x1080 520x290mm 23.4-inch                 | 1         | 2.33%   |
| HJW HDMI TO USB HJW0001 1920x1080 700x390mm 31.5-inch                | 1         | 2.33%   |
| Hewlett-Packard LCD Monitor LA2306 3520x1080                         | 1         | 2.33%   |
| Hewlett-Packard LA2306 HWP2949 1920x1080 510x290mm 23.1-inch         | 1         | 2.33%   |
| Hewlett-Packard E242 HWP326E 1920x1200 520x320mm 24.0-inch           | 1         | 2.33%   |
| Dell U2718Q DELA0EC 3840x2160 610x350mm 27.7-inch                    | 1         | 2.33%   |
| CSO LCD Monitor CSO1500 3840x2160 340x190mm 15.3-inch                | 1         | 2.33%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 280x180mm 13.1-inch     | 1         | 2.33%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 340x190mm 15.3-inch     | 1         | 2.33%   |
| Chimei Innolux LCD Monitor CMN1484 1600x900 310x170mm 13.9-inch      | 1         | 2.33%   |
| Chimei Innolux LCD Monitor CMN13A2 1920x1080 290x170mm 13.2-inch     | 1         | 2.33%   |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                | 1         | 2.33%   |
| BOE LCD Monitor BOE08D7 1920x1080 310x170mm 13.9-inch                | 1         | 2.33%   |
| BOE LCD Monitor BOE084D 1920x1080 340x190mm 15.3-inch                | 1         | 2.33%   |
| BOE LCD Monitor BOE07F1 1920x1080 340x190mm 15.3-inch                | 1         | 2.33%   |
| BOE LCD Monitor BOE0792 1920x1080 340x190mm 15.3-inch                | 1         | 2.33%   |
| BOE LCD Monitor BOE0747 1920x1080 340x190mm 15.3-inch                | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO5A2D 1920x1080 290x170mm 13.2-inch       | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch       | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch        | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO2026 2560x1600 290x180mm 13.4-inch       | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO139D 1920x1080 380x210mm 17.1-inch       | 1         | 2.33%   |
| Apple Cinema HD APP9223 1920x1200 490x310mm 22.8-inch                | 1         | 2.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 23        | 57.5%   |
| 1600x900 (HD+)    | 6         | 15%     |
| 3840x2160 (4K)    | 2         | 5%      |
| 1920x1200 (WUXGA) | 2         | 5%      |
| 3840x1200         | 1         | 2.5%    |
| 3520x1080         | 1         | 2.5%    |
| 2560x1600         | 1         | 2.5%    |
| 2256x1504         | 1         | 2.5%    |
| 2160x1440         | 1         | 2.5%    |
| 1366x768 (WXGA)   | 1         | 2.5%    |
| Unknown           | 1         | 2.5%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 13      | 15        | 37.5%   |
| 15      | 10        | 25%     |
| 27      | 3         | 7.5%    |
| 17      | 3         | 7.5%    |
| 23      | 2         | 5%      |
| Unknown | 2         | 5%      |
| 43      | 1         | 2.5%    |
| 31      | 1         | 2.5%    |
| 24      | 1         | 2.5%    |
| 22      | 1         | 2.5%    |
| 12      | 1         | 2.5%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 19        | 48.72%  |
| 201-300     | 7         | 17.95%  |
| 501-600     | 4         | 10.26%  |
| 351-400     | 3         | 7.69%   |
| 601-700     | 2         | 5.13%   |
| Unknown     | 2         | 5.13%   |
| 401-500     | 1         | 2.56%   |
| 1001-1500   | 1         | 2.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 27        | 77.14%  |
| 16/10   | 4         | 11.43%  |
| Unknown | 2         | 5.71%   |
| 3/2     | 1         | 2.86%   |
| 3.18    | 1         | 2.86%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 11        | 27.5%   |
| 91-100         | 7         | 17.5%   |
| 71-80          | 4         | 10%     |
| 301-350        | 3         | 7.5%    |
| 201-250        | 3         | 7.5%    |
| 121-130        | 3         | 7.5%    |
| 101-110        | 3         | 7.5%    |
| Unknown        | 2         | 5%      |
| 61-70          | 1         | 2.5%    |
| 351-500        | 1         | 2.5%    |
| 251-300        | 1         | 2.5%    |
| 501-1000       | 1         | 2.5%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 17        | 43.59%  |
| 161-240       | 7         | 17.95%  |
| 51-100        | 7         | 17.95%  |
| 101-120       | 5         | 12.82%  |
| Unknown       | 2         | 5.13%   |
| More than 240 | 1         | 2.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 23        | 54.76%  |
| 0     | 11        | 26.19%  |
| 2     | 7         | 16.67%  |
| 3     | 1         | 2.38%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 35        | 46.67%  |
| Realtek Semiconductor | 22        | 29.33%  |
| Hewlett-Packard       | 4         | 5.33%   |
| TP-Link               | 3         | 4%      |
| Ralink Technology     | 2         | 2.67%   |
| Qualcomm Atheros      | 2         | 2.67%   |
| D-Link System         | 2         | 2.67%   |
| Broadcom              | 2         | 2.67%   |
| Lenovo                | 1         | 1.33%   |
| Edimax Technology     | 1         | 1.33%   |
| BUFFALO               | 1         | 1.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 19        | 20.21%  |
| Intel Comet Lake PCH CNVi WiFi                                             | 6         | 6.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 6         | 6.38%   |
| Intel Wi-Fi 6 AX200                                                        | 5         | 5.32%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 5         | 5.32%   |
| Intel Wireless-AC 9260                                                     | 4         | 4.26%   |
| Intel Wireless 8265 / 8275                                                 | 4         | 4.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                          | 4         | 4.26%   |
| HP hs2350 HSPA+ Mobile Broadband Module Network Adapter                    | 4         | 4.26%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 2         | 2.13%   |
| Ralink MT7601U Wireless Adapter                                            | 2         | 2.13%   |
| Intel Wireless 7260                                                        | 2         | 2.13%   |
| Intel Ethernet Connection (4) I219-LM                                      | 2         | 2.13%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 2         | 2.13%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]        | 1         | 1.06%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                   | 1         | 1.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 1.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 1.06%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                     | 1         | 1.06%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 1         | 1.06%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 1         | 1.06%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 1         | 1.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 1         | 1.06%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 1         | 1.06%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                           | 1         | 1.06%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                     | 1         | 1.06%   |
| Intel Wi-Fi 6 AX201                                                        | 1         | 1.06%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                  | 1         | 1.06%   |
| Intel Ethernet Connection I217-LM                                          | 1         | 1.06%   |
| Intel Ethernet Connection (7) I219-V                                       | 1         | 1.06%   |
| Intel Ethernet Connection (5) I219-V                                       | 1         | 1.06%   |
| Intel Ethernet Connection (11) I219-LM                                     | 1         | 1.06%   |
| Intel Ethernet Connection (10) I219-V                                      | 1         | 1.06%   |
| Intel Centrino Advanced-N 6235                                             | 1         | 1.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 1         | 1.06%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller          | 1         | 1.06%   |
| Edimax EW-7711MAC 802.11ac Wireless Adapter                                | 1         | 1.06%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]                   | 1         | 1.06%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                         | 1         | 1.06%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                        | 1         | 1.06%   |
| Unknown                                                                    | 1         | 1.06%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 35        | 67.31%  |
| Realtek Semiconductor | 5         | 9.62%   |
| TP-Link               | 3         | 5.77%   |
| Ralink Technology     | 2         | 3.85%   |
| D-Link System         | 2         | 3.85%   |
| Broadcom              | 2         | 3.85%   |
| Qualcomm Atheros      | 1         | 1.92%   |
| Edimax Technology     | 1         | 1.92%   |
| BUFFALO               | 1         | 1.92%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Comet Lake PCH CNVi WiFi                                             | 6         | 11.54%  |
| Intel Wi-Fi 6 AX200                                                        | 5         | 9.62%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 5         | 9.62%   |
| Intel Wireless-AC 9260                                                     | 4         | 7.69%   |
| Intel Wireless 8265 / 8275                                                 | 4         | 7.69%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                          | 4         | 7.69%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 2         | 3.85%   |
| Ralink MT7601U Wireless Adapter                                            | 2         | 3.85%   |
| Intel Wireless 7260                                                        | 2         | 3.85%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 2         | 3.85%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]        | 1         | 1.92%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                   | 1         | 1.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 1.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 1.92%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                     | 1         | 1.92%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 1         | 1.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 1         | 1.92%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                     | 1         | 1.92%   |
| Intel Wi-Fi 6 AX201                                                        | 1         | 1.92%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                  | 1         | 1.92%   |
| Intel Centrino Advanced-N 6235                                             | 1         | 1.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 1         | 1.92%   |
| Edimax EW-7711MAC 802.11ac Wireless Adapter                                | 1         | 1.92%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]                   | 1         | 1.92%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                         | 1         | 1.92%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                        | 1         | 1.92%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 21        | 56.76%  |
| Intel                 | 14        | 37.84%  |
| Qualcomm Atheros      | 1         | 2.7%    |
| Lenovo                | 1         | 2.7%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19        | 51.35%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 16.22%  |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 5.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 2.7%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 2.7%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 2.7%    |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                  | 1         | 2.7%    |
| Intel Ethernet Connection I217-LM                                 | 1         | 2.7%    |
| Intel Ethernet Connection (7) I219-V                              | 1         | 2.7%    |
| Intel Ethernet Connection (5) I219-V                              | 1         | 2.7%    |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 2.7%    |
| Intel Ethernet Connection (10) I219-V                             | 1         | 2.7%    |
| Unknown                                                           | 1         | 2.7%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 41        | 50%     |
| Ethernet | 36        | 43.9%   |
| Modem    | 5         | 6.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 34        | 56.67%  |
| WiFi     | 23        | 38.33%  |
| Modem    | 3         | 5%      |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 35        | 85.37%  |
| 1     | 5         | 12.2%   |
| 3     | 1         | 2.44%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 36        | 80%     |
| Yes  | 9         | 20%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 27        | 81.82%  |
| Realtek Semiconductor | 2         | 6.06%   |
| Realtek               | 1         | 3.03%   |
| IMC Networks          | 1         | 3.03%   |
| Broadcom              | 1         | 3.03%   |
| Apple                 | 1         | 3.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                          | 9         | 27.27%  |
| Intel Bluetooth wireless interface             | 5         | 15.15%  |
| Intel AX200 Bluetooth                          | 5         | 15.15%  |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 3         | 9.09%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 3         | 9.09%   |
| Realtek  Bluetooth Adapter                     | 1         | 3.03%   |
| Realtek Bluetooth Radio                        | 1         | 3.03%   |
| Realtek Bluetooth Radio                        | 1         | 3.03%   |
| Intel Centrino Bluetooth Wireless Transceiver  | 1         | 3.03%   |
| Intel AX210 Bluetooth                          | 1         | 3.03%   |
| IMC Networks Bluetooth module                  | 1         | 3.03%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 1         | 3.03%   |
| Apple Apple Broadcom Built-in Bluetooth        | 1         | 3.03%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel           | 28        | 48.28%  |
| AMD             | 16        | 27.59%  |
| Nvidia          | 10        | 17.24%  |
| Lenovo          | 2         | 3.45%   |
| SteelSeries ApS | 1         | 1.72%   |
| CMX Systems     | 1         | 1.72%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                 | 12        | 16.44%  |
| Intel Comet Lake PCH cAVS                                           | 7         | 9.59%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 6         | 8.22%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 6         | 8.22%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 6         | 8.22%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller      | 4         | 5.48%   |
| Intel Comet Lake PCH-LP cAVS                                        | 4         | 5.48%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]           | 3         | 4.11%   |
| Nvidia TU116 High Definition Audio Controller                       | 2         | 2.74%   |
| Intel Sunrise Point-LP HD Audio                                     | 2         | 2.74%   |
| Intel Cannon Lake PCH cAVS                                          | 2         | 2.74%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 2         | 2.74%   |
| SteelSeries ApS SteelSeries Siberia 350                             | 1         | 1.37%   |
| Nvidia TU104 HD Audio Controller                                    | 1         | 1.37%   |
| Nvidia GP107GL High Definition Audio Controller                     | 1         | 1.37%   |
| Nvidia GK107 HDMI Audio Controller                                  | 1         | 1.37%   |
| Nvidia GA104 High Definition Audio Controller                       | 1         | 1.37%   |
| Lenovo ThinkPad Dock Audio                                          | 1         | 1.37%   |
| Lenovo Realtek USB Audio                                            | 1         | 1.37%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 1         | 1.37%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller         | 1         | 1.37%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller           | 1         | 1.37%   |
| Intel CM238 HD Audio Controller                                     | 1         | 1.37%   |
| Intel Cannon Point-LP High Definition Audio Controller              | 1         | 1.37%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller   | 1         | 1.37%   |
| CMX Systems USB PnP Audio Device                                    | 1         | 1.37%   |
| AMD Wrestler HDMI Audio                                             | 1         | 1.37%   |
| AMD SBx00 Azalia (Intel HDA)                                        | 1         | 1.37%   |
| AMD Navi 10 HDMI Audio                                              | 1         | 1.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 15        | 31.25%  |
| SK Hynix            | 9         | 18.75%  |
| Micron Technology   | 8         | 16.67%  |
| Kingston            | 6         | 12.5%   |
| Smart               | 2         | 4.17%   |
| Ramaxel Technology  | 2         | 4.17%   |
| Crucial             | 2         | 4.17%   |
| Unknown             | 1         | 2.08%   |
| PNY                 | 1         | 2.08%   |
| GOODRAM             | 1         | 2.08%   |
| A-DATA Technology   | 1         | 2.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s        | 4         | 8.16%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 4.08%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 2         | 4.08%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s       | 2         | 4.08%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s        | 2         | 4.08%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s         | 2         | 4.08%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s         | 2         | 4.08%   |
| Crucial RAM BL32G32C16S4B.M16FB1 32GB SODIMM DDR4 2667MT/s   | 2         | 4.08%   |
| Unknown RAM Module 1GB SODIMM DDR                            | 1         | 2.04%   |
| Smart RAM SF4641G8CK8IWGKSEG 8GB SODIMM DDR4 2133MT/s        | 1         | 2.04%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s        | 1         | 2.04%   |
| SK Hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 2.04%   |
| SK Hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s      | 1         | 2.04%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 2.04%   |
| Samsung RAM M474A4G43AB1-CVF 32GB SODIMM DDR4 2933MT/s       | 1         | 2.04%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s        | 1         | 2.04%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 1         | 2.04%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s        | 1         | 2.04%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s       | 1         | 2.04%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s       | 1         | 2.04%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s  | 1         | 2.04%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 2.04%   |
| Samsung RAM K4EBE304EB-EGCF 8GB Row Of Chips LPDDR3 1867MT/s | 1         | 2.04%   |
| Ramaxel RAM RMSA3320MJ78HAF-3200 8GB SODIMM DDR4 3200MT/s    | 1         | 2.04%   |
| Ramaxel RAM RMSA3300MH78HBF-2666 16GB SODIMM DDR4 2400MT/s   | 1         | 2.04%   |
| PNY RAM 16GU2X16LIII43-12-K 16GB SODIMM DDR4 2667MT/s        | 1         | 2.04%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                   | 1         | 2.04%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s        | 1         | 2.04%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s   | 1         | 2.04%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s        | 1         | 2.04%   |
| Kingston RAM Module 8GB SODIMM DDR4 2667MT/s                 | 1         | 2.04%   |
| Kingston RAM Module 16GB SODIMM DDR4 2667MT/s                | 1         | 2.04%   |
| Kingston RAM Module 16GB SODIMM DDR4 2400MT/s                | 1         | 2.04%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 2933MT/s         | 1         | 2.04%   |
| Kingston RAM KHX2400C14S4/4G 4GB SODIMM DDR4 2400MT/s        | 1         | 2.04%   |
| Kingston RAM 99U5428-063.A00LF 8GB SODIMM DDR3 1600MT/s      | 1         | 2.04%   |
| Kingston RAM 9905428-196.A00LF 8GB SODIMM DDR3 1333MT/s      | 1         | 2.04%   |
| GOODRAM RAM GR1600S364L11/8G 8GB SODIMM DDR3 1600MT/s        | 1         | 2.04%   |
| A-DATA RAM DDR4 3200 16GB SODIMM DDR4 2667MT/s               | 1         | 2.04%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 30        | 73.17%  |
| DDR3   | 9         | 21.95%  |
| LPDDR3 | 1         | 2.44%   |
| DDR    | 1         | 2.44%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 39        | 92.86%  |
| Row Of Chips | 3         | 7.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 23        | 54.76%  |
| 16384 | 10        | 23.81%  |
| 4096  | 4         | 9.52%   |
| 32768 | 3         | 7.14%   |
| 2048  | 1         | 2.38%   |
| 1024  | 1         | 2.38%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 15        | 34.88%  |
| 3200    | 10        | 23.26%  |
| 1600    | 7         | 16.28%  |
| 2400    | 4         | 9.3%    |
| 2933    | 2         | 4.65%   |
| 2133    | 1         | 2.33%   |
| 1867    | 1         | 2.33%   |
| 1334    | 1         | 2.33%   |
| 1333    | 1         | 2.33%   |
| Unknown | 1         | 2.33%   |

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
| Chicony Electronics                    | 12        | 28.57%  |
| IMC Networks                           | 10        | 23.81%  |
| Lite-On Technology                     | 4         | 9.52%   |
| Realtek Semiconductor                  | 3         | 7.14%   |
| Logitech                               | 3         | 7.14%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 7.14%   |
| Acer                                   | 3         | 7.14%   |
| Sunplus Innovation Technology          | 2         | 4.76%   |
| Syntek                                 | 1         | 2.38%   |
| Microdia                               | 1         | 2.38%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                             | 7         | 16.28%  |
| Chicony Integrated Camera                                                  | 6         | 13.95%  |
| Chicony Integrated HP HD Webcam                                            | 3         | 6.98%   |
| Sunplus Integrated_Webcam_HD                                               | 2         | 4.65%   |
| Logitech Webcam C270                                                       | 2         | 4.65%   |
| Lite-On Integrated Camera                                                  | 2         | 4.65%   |
| Lite-On HP HD Camera                                                       | 2         | 4.65%   |
| Acer Integrated Camera                                                     | 2         | 4.65%   |
| Syntek Lenovo EasyCamera                                                   | 1         | 2.33%   |
| Realtek USB 2 Webcam                                                       | 1         | 2.33%   |
| Realtek Laptop Camera                                                      | 1         | 2.33%   |
| Realtek Integrated_Webcam_HD                                               | 1         | 2.33%   |
| Microdia Dell Integrated HD Webcam                                         | 1         | 2.33%   |
| Logitech HD Pro Webcam C920                                                | 1         | 2.33%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 1         | 2.33%   |
| IMC Networks HD Camera                                                     | 1         | 2.33%   |
| IMC Networks EasyCamera                                                    | 1         | 2.33%   |
| Chicony USB2.0 0.3M UVC WebCam                                             | 1         | 2.33%   |
| Chicony ThinkPad T490 Webcam                                               | 1         | 2.33%   |
| Chicony Integrated IR Camera                                               | 1         | 2.33%   |
| Chicony HD Webcam                                                          | 1         | 2.33%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 2.33%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed]                | 1         | 2.33%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam   | 1         | 2.33%   |
| Acer HD Webcam                                                             | 1         | 2.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 8         | 50%     |
| Shenzhen Goodix Technology | 4         | 25%     |
| Validity Sensors           | 3         | 18.75%  |
| AuthenTec                  | 1         | 6.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 31.25%  |
| Validity Sensors Synaptics WBDI                                            | 2         | 12.5%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 12.5%   |
| Shenzhen Goodix  FingerPrint Device                                        | 2         | 12.5%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 12.5%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 6.25%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 6.25%   |
| AuthenTec AES2810                                                          | 1         | 6.25%   |

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
| 4     | 12        | 28.57%  |
| 2     | 12        | 28.57%  |
| 1     | 7         | 16.67%  |
| 3     | 6         | 14.29%  |
| 5     | 3         | 7.14%   |
| 9     | 1         | 2.38%   |
| 0     | 1         | 2.38%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 31        | 31%     |
| Net/wireless             | 20        | 20%     |
| Bluetooth                | 20        | 20%     |
| Fingerprint reader       | 16        | 16%     |
| Card reader              | 7         | 7%      |
| Sound                    | 2         | 2%      |
| Firewire controller      | 2         | 2%      |
| Net/ethernet             | 1         | 1%      |
| Modem                    | 1         | 1%      |

