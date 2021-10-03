FreeBSD 14.0-CURRENT - Tested Hardware & Statistics
---------------------------------------------------

A project to collect tested hardware configurations for FreeBSD 14.0-CURRENT.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/FreeBSD_14.0-CURRENT/Desktop/README.md) and [notebooks](/Dist/FreeBSD_14.0-CURRENT/Notebook/README.md).

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

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Framework     | Laptop                      | Notebook    | [e5aca4b7d0](https://bsd-hardware.info/?probe=e5aca4b7d0) | Oct 02, 2021 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [1aa5ced5a0](https://bsd-hardware.info/?probe=1aa5ced5a0) | Sep 23, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [646148fc25](https://bsd-hardware.info/?probe=646148fc25) | Sep 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [0b73df29bf](https://bsd-hardware.info/?probe=0b73df29bf) | Sep 15, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [5a4e53da56](https://bsd-hardware.info/?probe=5a4e53da56) | Sep 12, 2021 |
| Lenovo        | ThinkPad X395 20NL000GPG    | Notebook    | [d7812a2905](https://bsd-hardware.info/?probe=d7812a2905) | Sep 10, 2021 |
| Lenovo        | ThinkPad X395 20NL000GPG    | Notebook    | [cdde22fb04](https://bsd-hardware.info/?probe=cdde22fb04) | Sep 10, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [7a289e8d1b](https://bsd-hardware.info/?probe=7a289e8d1b) | Sep 06, 2021 |
| Gigabyte      | X399 DESIGNARE EX-CF        | Desktop     | [a78cc6a11b](https://bsd-hardware.info/?probe=a78cc6a11b) | Sep 04, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [fae9e84f60](https://bsd-hardware.info/?probe=fae9e84f60) | Aug 27, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [76f004bd26](https://bsd-hardware.info/?probe=76f004bd26) | Aug 26, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [a98c6adb40](https://bsd-hardware.info/?probe=a98c6adb40) | Aug 22, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [71092e78e2](https://bsd-hardware.info/?probe=71092e78e2) | Aug 17, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [6e97c9a59e](https://bsd-hardware.info/?probe=6e97c9a59e) | Aug 14, 2021 |
| Lenovo        | Unknown                     | Notebook    | [e16ce5e864](https://bsd-hardware.info/?probe=e16ce5e864) | Aug 08, 2021 |
| HP            | ZBook 17 G2                 | Notebook    | [f2d911563a](https://bsd-hardware.info/?probe=f2d911563a) | Aug 07, 2021 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [6d5e1a13d0](https://bsd-hardware.info/?probe=6d5e1a13d0) | Aug 07, 2021 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | Notebook    | [bf56b2a81a](https://bsd-hardware.info/?probe=bf56b2a81a) | Aug 05, 2021 |
| HP            | ZBook 17 G2                 | Notebook    | [2faf8af7be](https://bsd-hardware.info/?probe=2faf8af7be) | Jul 30, 2021 |
| HP            | ZBook 17 G2                 | Notebook    | [c7fb9e9dee](https://bsd-hardware.info/?probe=c7fb9e9dee) | Jul 27, 2021 |
| HP            | ZBook 17 G2                 | Notebook    | [50c349b7b5](https://bsd-hardware.info/?probe=50c349b7b5) | Jul 27, 2021 |
| HP            | ZBook 17 G2                 | Notebook    | [6149ab50a8](https://bsd-hardware.info/?probe=6149ab50a8) | Jul 24, 2021 |
| Dell          | G5 5505                     | Notebook    | [9933a09c4f](https://bsd-hardware.info/?probe=9933a09c4f) | Jul 24, 2021 |
| HP            | ZBook 17 G2                 | Notebook    | [1ef99f31dd](https://bsd-hardware.info/?probe=1ef99f31dd) | Jul 23, 2021 |
| Avell High... | A62 LIV                     | Notebook    | [5983302b1d](https://bsd-hardware.info/?probe=5983302b1d) | Jul 21, 2021 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | Notebook    | [e0e6f62814](https://bsd-hardware.info/?probe=e0e6f62814) | Jul 19, 2021 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | Notebook    | [b0da42c20d](https://bsd-hardware.info/?probe=b0da42c20d) | Jul 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [9c9d4cc782](https://bsd-hardware.info/?probe=9c9d4cc782) | Jul 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [3d5e512e18](https://bsd-hardware.info/?probe=3d5e512e18) | Jul 18, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [63dc88528c](https://bsd-hardware.info/?probe=63dc88528c) | Jul 17, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [7138e2a9e7](https://bsd-hardware.info/?probe=7138e2a9e7) | Jul 17, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [b73eb50747](https://bsd-hardware.info/?probe=b73eb50747) | Jul 16, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [462fc329a9](https://bsd-hardware.info/?probe=462fc329a9) | Jul 16, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [d2866f01b5](https://bsd-hardware.info/?probe=d2866f01b5) | Jul 16, 2021 |
| Unknown       | Unknown                     | Desktop     | [4a3836de00](https://bsd-hardware.info/?probe=4a3836de00) | Jul 08, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [cc24e867fc](https://bsd-hardware.info/?probe=cc24e867fc) | Jun 19, 2021 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | Notebook    | [3d50ba4d85](https://bsd-hardware.info/?probe=3d50ba4d85) | Jun 13, 2021 |
| Dell          | G5 5505                     | Notebook    | [97319295ee](https://bsd-hardware.info/?probe=97319295ee) | Jun 13, 2021 |
| Dell          | Vostro 5490                 | Notebook    | [cf3508718c](https://bsd-hardware.info/?probe=cf3508718c) | Jun 11, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [4ac6c9b3eb](https://bsd-hardware.info/?probe=4ac6c9b3eb) | Jun 08, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [8fc867cfae](https://bsd-hardware.info/?probe=8fc867cfae) | Jun 06, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [edebe87739](https://bsd-hardware.info/?probe=edebe87739) | Jun 04, 2021 |
| Intel         | S2600WTTR G92187-372        | Server      | [289d61b1b2](https://bsd-hardware.info/?probe=289d61b1b2) | Jun 04, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [52ba4e835f](https://bsd-hardware.info/?probe=52ba4e835f) | Jun 03, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [4e4f164625](https://bsd-hardware.info/?probe=4e4f164625) | May 29, 2021 |
| Unknown       | Unknown                     | Soc         | [d96ade87e5](https://bsd-hardware.info/?probe=d96ade87e5) | May 29, 2021 |
| Lenovo        | ThinkPad X270 20HM004JBR    | Notebook    | [88c27e65d7](https://bsd-hardware.info/?probe=88c27e65d7) | May 23, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [62b9ea2794](https://bsd-hardware.info/?probe=62b9ea2794) | May 14, 2021 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [b3acafeb1a](https://bsd-hardware.info/?probe=b3acafeb1a) | May 09, 2021 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [86cec3b874](https://bsd-hardware.info/?probe=86cec3b874) | May 09, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [062fe5ec40](https://bsd-hardware.info/?probe=062fe5ec40) | May 09, 2021 |
| Dell          | G5 5505                     | Notebook    | [ba74d8eee0](https://bsd-hardware.info/?probe=ba74d8eee0) | May 08, 2021 |
| Dell          | G5 5505                     | Notebook    | [23ae99e489](https://bsd-hardware.info/?probe=23ae99e489) | May 08, 2021 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | Notebook    | [2be8cf963c](https://bsd-hardware.info/?probe=2be8cf963c) | May 02, 2021 |
| Dell          | Inspiron 3793               | Notebook    | [c2d56fc369](https://bsd-hardware.info/?probe=c2d56fc369) | Apr 29, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [e90abb54c9](https://bsd-hardware.info/?probe=e90abb54c9) | Apr 25, 2021 |
| pine64        | pinebook-pro-rk3399         | Desktop     | [79713a2668](https://bsd-hardware.info/?probe=79713a2668) | Apr 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [4993ad0feb](https://bsd-hardware.info/?probe=4993ad0feb) | Apr 25, 2021 |
| pine64        | pinebook-pro-rk3399         | Desktop     | [0f04e5f048](https://bsd-hardware.info/?probe=0f04e5f048) | Apr 11, 2021 |
| HUAWEI        | HN-WX9X                     | Notebook    | [d776625073](https://bsd-hardware.info/?probe=d776625073) | Apr 11, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [d9ec051372](https://bsd-hardware.info/?probe=d9ec051372) | Apr 06, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [325186171a](https://bsd-hardware.info/?probe=325186171a) | Apr 02, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [cdeafa0952](https://bsd-hardware.info/?probe=cdeafa0952) | Apr 02, 2021 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [342e914968](https://bsd-hardware.info/?probe=342e914968) | Mar 29, 2021 |
| pine64        | pinebook-pro-rk3399         | Desktop     | [ea524ab4c4](https://bsd-hardware.info/?probe=ea524ab4c4) | Mar 28, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [ed80dc9019](https://bsd-hardware.info/?probe=ed80dc9019) | Mar 27, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [dd877e6c6c](https://bsd-hardware.info/?probe=dd877e6c6c) | Mar 27, 2021 |
| pine64        | pinebook-pro-rk3399         | Desktop     | [835da13d39](https://bsd-hardware.info/?probe=835da13d39) | Mar 18, 2021 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [cc3151bc6f](https://bsd-hardware.info/?probe=cc3151bc6f) | Mar 17, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [e3f20f8770](https://bsd-hardware.info/?probe=e3f20f8770) | Mar 17, 2021 |
| Lenovo        | ThinkPad X395 20NL001SMX    | Notebook    | [cd016e96ee](https://bsd-hardware.info/?probe=cd016e96ee) | Mar 17, 2021 |
| MSI           | B450 GAMING PLUS            | Desktop     | [547fd655f0](https://bsd-hardware.info/?probe=547fd655f0) | Mar 13, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [9fed35d792](https://bsd-hardware.info/?probe=9fed35d792) | Mar 10, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [1fcde7c0e1](https://bsd-hardware.info/?probe=1fcde7c0e1) | Mar 09, 2021 |
| pine64        | pinebook-pro-rk3399         | Desktop     | [c00bcdcc87](https://bsd-hardware.info/?probe=c00bcdcc87) | Mar 06, 2021 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | Notebook    | [f2c2e5345a](https://bsd-hardware.info/?probe=f2c2e5345a) | Feb 27, 2021 |
| pine64        | pinebook-pro-rk3399         | Desktop     | [3abcd73d48](https://bsd-hardware.info/?probe=3abcd73d48) | Feb 26, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [29936dd1c0](https://bsd-hardware.info/?probe=29936dd1c0) | Feb 25, 2021 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | Notebook    | [aacafb6ace](https://bsd-hardware.info/?probe=aacafb6ace) | Feb 24, 2021 |
| Unknown       | Unknown                     | Desktop     | [74b11992d7](https://bsd-hardware.info/?probe=74b11992d7) | Feb 20, 2021 |
| Raspberry ... | rpi                         | Desktop     | [92ee9b3619](https://bsd-hardware.info/?probe=92ee9b3619) | Feb 18, 2021 |
| pine64        | pinebook-pro-rk3399         | Desktop     | [b750f83194](https://bsd-hardware.info/?probe=b750f83194) | Feb 17, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [a601b10377](https://bsd-hardware.info/?probe=a601b10377) | Feb 16, 2021 |
| A-DATA Tec... | XENIA159GENI72060           | Notebook    | [be88e8f865](https://bsd-hardware.info/?probe=be88e8f865) | Feb 15, 2021 |
| Lenovo        | ThinkPad T495s 20QKS1812... | Notebook    | [0e5e228d18](https://bsd-hardware.info/?probe=0e5e228d18) | Feb 13, 2021 |
| Lenovo        | ThinkPad T495s 20QKS1812... | Notebook    | [2d93a6bebc](https://bsd-hardware.info/?probe=2d93a6bebc) | Feb 13, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [ba7f82b343](https://bsd-hardware.info/?probe=ba7f82b343) | Feb 12, 2021 |
| Matsushita... | CF-T2BW1AXR                 | Notebook    | [f6ec2858a5](https://bsd-hardware.info/?probe=f6ec2858a5) | Feb 10, 2021 |
| pine64        | pinebook-pro-rk3399         | Desktop     | [2befc5e754](https://bsd-hardware.info/?probe=2befc5e754) | Feb 10, 2021 |
| pine64        | pinebook-pro-rk3399         | Desktop     | [5a55b22f44](https://bsd-hardware.info/?probe=5a55b22f44) | Feb 09, 2021 |
| Dell          | 0D9JG3 A00                  | Desktop     | [65dd4083c5](https://bsd-hardware.info/?probe=65dd4083c5) | Feb 09, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [72137c63f8](https://bsd-hardware.info/?probe=72137c63f8) | Feb 09, 2021 |
| pine64        | pinebook-pro-rk3399         | Desktop     | [97e72f0066](https://bsd-hardware.info/?probe=97e72f0066) | Feb 06, 2021 |
| Dell          | Latitude E5430 vPro         | Notebook    | [bee421a110](https://bsd-hardware.info/?probe=bee421a110) | Feb 06, 2021 |
| Dell          | Latitude E5430 vPro         | Notebook    | [e8157ac6a3](https://bsd-hardware.info/?probe=e8157ac6a3) | Feb 06, 2021 |
| Lenovo        | ThinkPad T430 2349H2G       | Notebook    | [229db16a93](https://bsd-hardware.info/?probe=229db16a93) | Feb 05, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [46c938b853](https://bsd-hardware.info/?probe=46c938b853) | Feb 01, 2021 |
| pine64        | pinebook-pro-rk3399         | Desktop     | [1720175648](https://bsd-hardware.info/?probe=1720175648) | Jan 27, 2021 |
| Matsushita... | CF-T2BW1AXR                 | Notebook    | [c16cd20c42](https://bsd-hardware.info/?probe=c16cd20c42) | Jan 25, 2021 |
| pine64        | pinebook-pro-rk3399         | Desktop     | [2338de9efc](https://bsd-hardware.info/?probe=2338de9efc) | Jan 24, 2021 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 42        | 85.71%  |
| arm64 | 5         | 10.2%   |
| riscv | 1         | 2.04%   |
| i386  | 1         | 2.04%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KDE5          | 16        | 30.19%  |
| Console       | 10        | 18.87%  |
| XFCE          | 7         | 13.21%  |
| MATE          | 4         | 7.55%   |
| i3            | 3         | 5.66%   |
| GNOME         | 3         | 5.66%   |
| Cinnamon      | 3         | 5.66%   |
| TWM           | 2         | 3.77%   |
| LXQt          | 1         | 1.89%   |
| LXDE          | 1         | 1.89%   |
| Lumina        | 1         | 1.89%   |
| Fluxbox       | 1         | 1.89%   |
| Enlightenment | 1         | 1.89%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 39        | 75%     |
| Console | 13        | 25%     |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 19        | 37.25%  |
| SDDM    | 12        | 23.53%  |
| SLiM    | 7         | 13.73%  |
| GDM     | 7         | 13.73%  |
| XDM     | 5         | 9.8%    |
| LightDM | 1         | 1.96%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang             | Computers | Percent |
|------------------|-----------|---------|
| C                | 31        | 60.78%  |
| en_US            | 6         | 11.76%  |
| Unknown          | 3         | 5.88%   |
| en_GB            | 2         | 3.92%   |
| zh_CN            | 1         | 1.96%   |
| sv_SE            | 1         | 1.96%   |
| ru_RU            | 1         | 1.96%   |
| pt_PT            | 1         | 1.96%   |
| pl_PL            | 1         | 1.96%   |
| it_IT.ISO8859-15 | 1         | 1.96%   |
| fr_FR            | 1         | 1.96%   |
| de_DE            | 1         | 1.96%   |
| de_CH            | 1         | 1.96%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 45        | 91.84%  |
| BIOS | 4         | 8.16%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 38        | 77.55%  |
| Ufs  | 11        | 22.45%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 46        | 93.88%  |
| MBR  | 3         | 6.12%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 14        | 28.57%  |
| Hewlett-Packard                | 6         | 12.24%  |
| Gigabyte Technology            | 5         | 10.2%   |
| Dell                           | 5         | 10.2%   |
| ASUSTek Computer               | 5         | 10.2%   |
| Unknown                        | 5         | 10.2%   |
| Raspberry Pi Foundation        | 1         | 2.04%   |
| pine64                         | 1         | 2.04%   |
| MSI                            | 1         | 2.04%   |
| Matsushita Electric Industrial | 1         | 2.04%   |
| Intel                          | 1         | 2.04%   |
| HUAWEI                         | 1         | 2.04%   |
| Framework                      | 1         | 2.04%   |
| Avell High Performance         | 1         | 2.04%   |
| A-DATA Technology              | 1         | 2.04%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 6         | 12.24%  |
| HP EliteBook 8570p                         | 3         | 6.12%   |
| RPi rpi                                    | 1         | 2.04%   |
| pine64 pinebook-pro-rk3399                 | 1         | 2.04%   |
| MSI MS-7B86                                | 1         | 2.04%   |
| Matsushita Electric Industrial CF-T2BW1AXR | 1         | 2.04%   |
| Lenovo XiaoXinPro-13ARE 2020 82DM          | 1         | 2.04%   |
| Lenovo ThinkPad X395 20NL001SMX            | 1         | 2.04%   |
| Lenovo ThinkPad X395 20NL000GPG            | 1         | 2.04%   |
| Lenovo ThinkPad X270 20HM004JBR            | 1         | 2.04%   |
| Lenovo ThinkPad X1 Extreme 20MF000BUS      | 1         | 2.04%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS1QC00   | 1         | 2.04%   |
| Lenovo ThinkPad T495s 20QKS1812F           | 1         | 2.04%   |
| Lenovo ThinkPad T430 2349H2G               | 1         | 2.04%   |
| Lenovo ThinkPad P15 Gen 1 20ST005VRT       | 1         | 2.04%   |
| Lenovo ThinkPad E14 20RBCTO1WW             | 1         | 2.04%   |
| Lenovo Legion 5P 15IMH05H 82AW             | 1         | 2.04%   |
| Lenovo Legion 5 15IMH05 82AU               | 1         | 2.04%   |
| Lenovo IdeaPad 330-15ARR 81D2              | 1         | 2.04%   |
| Intel S2600WTTR                            | 1         | 2.04%   |
| HUAWEI HN-WX9X                             | 1         | 2.04%   |
| HP ZBook 17 G2                             | 1         | 2.04%   |
| HP ProBook 455 G7                          | 1         | 2.04%   |
| HP ProBook 440 G7                          | 1         | 2.04%   |
| Gigabyte X570 AORUS MASTER                 | 1         | 2.04%   |
| Gigabyte X570 AORUS ELITE                  | 1         | 2.04%   |
| Gigabyte X399 DESIGNARE EX                 | 1         | 2.04%   |
| Gigabyte B550I AORUS PRO AX                | 1         | 2.04%   |
| Gigabyte 970A-UD3P                         | 1         | 2.04%   |
| Framework Laptop                           | 1         | 2.04%   |
| Dell Vostro 5490                           | 1         | 2.04%   |
| Dell OptiPlex 5080                         | 1         | 2.04%   |
| Dell Latitude E5430 vPro                   | 1         | 2.04%   |
| Dell Inspiron 3793                         | 1         | 2.04%   |
| Dell G5 5505                               | 1         | 2.04%   |
| Avell High Performance A62 LIV             | 1         | 2.04%   |
| ASUS VivoBook_ASUSLaptop X512DA_F512DA     | 1         | 2.04%   |
| ASUS PRIME Z590-A                          | 1         | 2.04%   |
| ASUS PRIME B450M-GAMING/BR                 | 1         | 2.04%   |
| ASUS PRIME B450M-A                         | 1         | 2.04%   |
| ASUS P8H77-M PRO                           | 1         | 2.04%   |
| A-DATA XENIA159GENI72060                   | 1         | 2.04%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo ThinkPad                            | 9         | 18.37%  |
| Unknown                                    | 6         | 12.24%  |
| HP EliteBook                               | 3         | 6.12%   |
| ASUS PRIME                                 | 3         | 6.12%   |
| Lenovo Legion                              | 2         | 4.08%   |
| HP ProBook                                 | 2         | 4.08%   |
| Gigabyte X570                              | 2         | 4.08%   |
| RPi rpi                                    | 1         | 2.04%   |
| pine64 pinebook-pro-rk3399                 | 1         | 2.04%   |
| MSI MS-7B86                                | 1         | 2.04%   |
| Matsushita Electric Industrial CF-T2BW1AXR | 1         | 2.04%   |
| Lenovo XiaoXinPro-13ARE                    | 1         | 2.04%   |
| Lenovo IdeaPad                             | 1         | 2.04%   |
| Intel S2600WTTR                            | 1         | 2.04%   |
| HUAWEI HN-WX9X                             | 1         | 2.04%   |
| HP ZBook                                   | 1         | 2.04%   |
| Gigabyte X399                              | 1         | 2.04%   |
| Gigabyte B550I                             | 1         | 2.04%   |
| Gigabyte 970A-UD3P                         | 1         | 2.04%   |
| Framework Laptop                           | 1         | 2.04%   |
| Dell Vostro                                | 1         | 2.04%   |
| Dell OptiPlex                              | 1         | 2.04%   |
| Dell Latitude                              | 1         | 2.04%   |
| Dell Inspiron                              | 1         | 2.04%   |
| Dell G5                                    | 1         | 2.04%   |
| Avell High Performance A62                 | 1         | 2.04%   |
| ASUS VivoBook                              | 1         | 2.04%   |
| ASUS P8H77-M                               | 1         | 2.04%   |
| A-DATA XENIA159GENI72060                   | 1         | 2.04%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 21        | 42.86%  |
| 2021    | 7         | 14.29%  |
| 2019    | 6         | 12.24%  |
| 2018    | 4         | 8.16%   |
| Unknown | 4         | 8.16%   |
| 2017    | 2         | 4.08%   |
| 2016    | 1         | 2.04%   |
| 2015    | 1         | 2.04%   |
| 2014    | 1         | 2.04%   |
| 2013    | 1         | 2.04%   |
| 2003    | 1         | 2.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 30        | 61.22%  |
| Desktop        | 15        | 30.61%  |
| System on chip | 3         | 6.12%   |
| Server         | 1         | 2.04%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 49        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 22        | 44%     |
| 32.01-64.0      | 8         | 16%     |
| 8.01-16.0       | 8         | 16%     |
| 64.01-256.0     | 7         | 14%     |
| 4.01-8.0        | 3         | 6%      |
| More than 256.0 | 1         | 2%      |
| 1.01-2.0        | 1         | 2%      |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.51-1.0   | 20        | 40.82%  |
| 1.01-2.0   | 9         | 18.37%  |
| 2.01-3.0   | 6         | 12.24%  |
| 0.01-0.5   | 6         | 12.24%  |
| 3.01-4.0   | 3         | 6.12%   |
| 4.01-8.0   | 1         | 2.04%   |
| 32.01-64.0 | 1         | 2.04%   |
| 24.01-32.0 | 1         | 2.04%   |
| 16.01-24.0 | 1         | 2.04%   |
| 8.01-16.0  | 1         | 2.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 21        | 41.18%  |
| 2      | 16        | 31.37%  |
| 3      | 5         | 9.8%    |
| 0      | 4         | 7.84%   |
| 6      | 3         | 5.88%   |
| 5      | 1         | 1.96%   |
| 4      | 1         | 1.96%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 39        | 78%     |
| Yes       | 11        | 22%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 41        | 83.67%  |
| No        | 8         | 16.33%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 73.47%  |
| No        | 13        | 26.53%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 26        | 52%     |
| No        | 24        | 48%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| UK           | 7         | 14.29%  |
| USA          | 6         | 12.24%  |
| Russia       | 5         | 10.2%   |
| Brazil       | 5         | 10.2%   |
| Japan        | 3         | 6.12%   |
| Germany      | 3         | 6.12%   |
| Switzerland  | 2         | 4.08%   |
| Sweden       | 2         | 4.08%   |
| Portugal     | 2         | 4.08%   |
| Poland       | 2         | 4.08%   |
| China        | 2         | 4.08%   |
| Austria      | 2         | 4.08%   |
| Ukraine      | 1         | 2.04%   |
| Saudi Arabia | 1         | 2.04%   |
| Peru         | 1         | 2.04%   |
| Italy        | 1         | 2.04%   |
| India        | 1         | 2.04%   |
| France       | 1         | 2.04%   |
| Croatia      | 1         | 2.04%   |
| Bangladesh   | 1         | 2.04%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Brighton                | 5         | 8.93%   |
| Ōta-ku                 | 3         | 5.36%   |
| Moscow                  | 3         | 5.36%   |
| Zurich                  | 2         | 3.57%   |
| Seattle                 | 2         | 3.57%   |
| London                  | 2         | 3.57%   |
| Fuchu                   | 2         | 3.57%   |
| Zaporizhzhya            | 1         | 1.79%   |
| Wuhan                   | 1         | 1.79%   |
| Wieliczka               | 1         | 1.79%   |
| Vienna                  | 1         | 1.79%   |
| Vancouver               | 1         | 1.79%   |
| Trosa                   | 1         | 1.79%   |
| Thrissur                | 1         | 1.79%   |
| St Petersburg           | 1         | 1.79%   |
| Sollentuna              | 1         | 1.79%   |
| Slavonski Brod          | 1         | 1.79%   |
| Santa Monica            | 1         | 1.79%   |
| San Francisco           | 1         | 1.79%   |
| Riyadh                  | 1         | 1.79%   |
| Rio de Janeiro          | 1         | 1.79%   |
| Resana                  | 1         | 1.79%   |
| Poulsbo                 | 1         | 1.79%   |
| Pobiedziska             | 1         | 1.79%   |
| Northeim                | 1         | 1.79%   |
| Milan                   | 1         | 1.79%   |
| Maia                    | 1         | 1.79%   |
| Lima                    | 1         | 1.79%   |
| Lake Forest             | 1         | 1.79%   |
| Kunitachi               | 1         | 1.79%   |
| Khabarovsk              | 1         | 1.79%   |
| João Pessoa            | 1         | 1.79%   |
| Jaboatao dos Guararapes | 1         | 1.79%   |
| Ilhavo                  | 1         | 1.79%   |
| Graz                    | 1         | 1.79%   |
| Farnham                 | 1         | 1.79%   |
| Eilenburg               | 1         | 1.79%   |
| Dhaka                   | 1         | 1.79%   |
| Claix                   | 1         | 1.79%   |
| Cambridge               | 1         | 1.79%   |
| Brasília               | 1         | 1.79%   |
| Berlin                  | 1         | 1.79%   |
| Beijing                 | 1         | 1.79%   |
| Araruama                | 1         | 1.79%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 14        | 22     | 20.29%  |
| Samsung Electronics | 13        | 21     | 18.84%  |
| Toshiba             | 7         | 10     | 10.14%  |
| HGST                | 6         | 14     | 8.7%    |
| Seagate             | 5         | 9      | 7.25%   |
| Crucial             | 5         | 12     | 7.25%   |
| SK Hynix            | 4         | 4      | 5.8%    |
| Kingston            | 3         | 5      | 4.35%   |
| Micron Technology   | 2         | 3      | 2.9%    |
| Intel               | 2         | 3      | 2.9%    |
| A-DATA Technology   | 2         | 2      | 2.9%    |
| Solid State Storage | 1         | 1      | 1.45%   |
| Silicon Motion      | 1         | 1      | 1.45%   |
| SanDisk             | 1         | 1      | 1.45%   |
| LITEON              | 1         | 1      | 1.45%   |
| GOODRAM             | 1         | 1      | 1.45%   |
| Fujitsu             | 1         | 2      | 1.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB                           | 5         | 6.41%   |
| HGST HTS725050A7E630 500GB                         | 4         | 5.13%   |
| HGST HTS721010A9E630 1TB                           | 3         | 3.85%   |
| WDC PC SN730 NVMe 1024GB                           | 2         | 2.56%   |
| Toshiba MQ04ABF100 1TB                             | 2         | 2.56%   |
| Samsung SSD 850 EVO 250GB                          | 2         | 2.56%   |
| Samsung HM251JX 250GB                              | 2         | 2.56%   |
| WDC WDS250G2B0C-00PXH0 250GB                       | 1         | 1.28%   |
| WDC WDS100T3X0C-00SJG0 1TB                         | 1         | 1.28%   |
| WDC WDS100T2B0A-00SM50 1TB                         | 1         | 1.28%   |
| WDC WD5002ABYS-18B1B0 500GB                        | 1         | 1.28%   |
| WDC WD40EZRZ-75GXCB0 4TB                           | 1         | 1.28%   |
| WDC WD30EFRX-68EUZN0 3TB                           | 1         | 1.28%   |
| WDC WD120EFAX-68UNTN0 12TB                         | 1         | 1.28%   |
| WDC WD10SPZX-21Z10T0 1TB                           | 1         | 1.28%   |
| WDC WD10JMVW-11AJGS3 1TB                           | 1         | 1.28%   |
| WDC WD10EZEX-00RKKA0 1TB                           | 1         | 1.28%   |
| WDC WD10EARX-00N0YB0 1TB                           | 1         | 1.28%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB               | 1         | 1.28%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB               | 1         | 1.28%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB               | 1         | 1.28%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB               | 1         | 1.28%   |
| Solid State Storage CL1-3D128-Q11 NVMe SSSTC 128GB | 1         | 1.28%   |
| SK Hynix PC300 HFS512GD9MND-5510A 512GB            | 1         | 1.28%   |
| SK Hynix HFS128G39TND-N210A 128GB                  | 1         | 1.28%   |
| SK Hynix BC511 NVMe 256GB                          | 1         | 1.28%   |
| SK Hynix BC511 HFM256GDJTNI-82A0A 256GB            | 1         | 1.28%   |
| Silicon Motion NE-256 256GB                        | 1         | 1.28%   |
| Seagate ST5000LM000-2AN170 5TB                     | 1         | 1.28%   |
| Seagate ST4000DM000-1F2168 4TB                     | 1         | 1.28%   |
| Seagate ST32000641AS 2TB                           | 1         | 1.28%   |
| Seagate ST3000DM007-1WY10G 3TB                     | 1         | 1.28%   |
| Seagate ST3000DM001-1ER166 3TB                     | 1         | 1.28%   |
| Seagate ST1000LM035-1RK172 1TB                     | 1         | 1.28%   |
| SanDisk SDSSDH3500G 500GB                          | 1         | 1.28%   |
| Samsung SSD 970 EVO 1TB                            | 1         | 1.28%   |
| Samsung SSD 870 QVO 1TB                            | 1         | 1.28%   |
| Samsung SSD 860 EVO 500GB                          | 1         | 1.28%   |
| Samsung SSD 860 EVO 4TB                            | 1         | 1.28%   |
| Samsung SSD 860 EVO 250GB                          | 1         | 1.28%   |
| Samsung SSD 850 EVO 500GB                          | 1         | 1.28%   |
| Samsung MZVLB512HBJQ-000L7 512GB                   | 1         | 1.28%   |
| Samsung MZVLB512HBJQ-000L2 512GB                   | 1         | 1.28%   |
| Samsung MZVLB256HBHQ-000L7 256GB                   | 1         | 1.28%   |
| Samsung MZVLB256HAHQ-00000 256GB                   | 1         | 1.28%   |
| Samsung MZVLB1T0HBLR-000L2 1TB                     | 1         | 1.28%   |
| Samsung MZMTD128HAFV-000L1 128GB                   | 1         | 1.28%   |
| Samsung HM250HI 250GB                              | 1         | 1.28%   |
| Micron 5200_MTFDDAK480TDC 480GB                    | 1         | 1.28%   |
| Micron 2300_MTFDHBA512TDV 512GB                    | 1         | 1.28%   |
| LITEON LCH-256V2S 256GB                            | 1         | 1.28%   |
| Kingston SA400S37240G 240GB                        | 1         | 1.28%   |
| Kingston SA2000M81000G 1TB                         | 1         | 1.28%   |
| Kingston RBUSNS8154P3256GJ3 256GB                  | 1         | 1.28%   |
| Intel SSDSC2KB240G8 240GB                          | 1         | 1.28%   |
| Intel SSDPEKNW512G8H 512GB                         | 1         | 1.28%   |
| GOODRAM SSDPR-CX400-256-G2 256GB                   | 1         | 1.28%   |
| Fujitsu MHS2040AT D 40GB                           | 1         | 1.28%   |
| Crucial CT500P1SSD8 500GB                          | 1         | 1.28%   |
| Crucial CT480BX500SSD1 480GB                       | 1         | 1.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 7         | 10     | 25.93%  |
| HGST                | 6         | 14     | 22.22%  |
| WDC                 | 5         | 8      | 18.52%  |
| Seagate             | 5         | 9      | 18.52%  |
| Samsung Electronics | 3         | 6      | 11.11%  |
| Fujitsu             | 1         | 2      | 3.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 8      | 31.25%  |
| Crucial             | 3         | 8      | 18.75%  |
| WDC                 | 1         | 2      | 6.25%   |
| SK Hynix            | 1         | 1      | 6.25%   |
| SanDisk             | 1         | 1      | 6.25%   |
| Micron Technology   | 1         | 1      | 6.25%   |
| LITEON              | 1         | 1      | 6.25%   |
| Kingston            | 1         | 2      | 6.25%   |
| Intel               | 1         | 2      | 6.25%   |
| GOODRAM             | 1         | 1      | 6.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 25        | 36     | 41.67%  |
| HDD  | 19        | 49     | 31.67%  |
| SSD  | 16        | 27     | 26.67%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 27        | 76     | 51.92%  |
| NVMe | 25        | 36     | 48.08%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 21        | 48     | 55.26%  |
| 0.51-1.0   | 10        | 16     | 26.32%  |
| 3.01-4.0   | 2         | 3      | 5.26%   |
| 2.01-3.0   | 2         | 3      | 5.26%   |
| 10.01-20.0 | 1         | 1      | 2.63%   |
| 1.01-2.0   | 1         | 1      | 2.63%   |
| 4.01-10.0  | 1         | 4      | 2.63%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 13        | 26%     |
| 101-250        | 13        | 26%     |
| 501-1000       | 9         | 18%     |
| 1-20           | 4         | 8%      |
| 51-100         | 4         | 8%      |
| 21-50          | 3         | 6%      |
| 2001-3000      | 2         | 4%      |
| More than 3000 | 1         | 2%      |
| 1001-2000      | 1         | 2%      |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 27        | 52.94%  |
| 21-50     | 18        | 35.29%  |
| 101-250   | 3         | 5.88%   |
| 251-500   | 1         | 1.96%   |
| 1001-2000 | 1         | 1.96%   |
| 501-1000  | 1         | 1.96%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                       | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| HGST HTS725050A7E630 500GB  | 4         | 9      | 57.14%  |
| WDC WD5002ABYS-18B1B0 500GB | 1         | 1      | 14.29%  |
| HGST HTS721010A9E630 1TB    | 1         | 1      | 14.29%  |
| Fujitsu MHS2040AT D 40GB    | 1         | 2      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HGST    | 4         | 10     | 66.67%  |
| WDC     | 1         | 1      | 16.67%  |
| Fujitsu | 1         | 2      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HGST    | 4         | 10     | 66.67%  |
| WDC     | 1         | 1      | 16.67%  |
| Fujitsu | 1         | 2      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 13     | 100%    |

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
| Works    | 44        | 97     | 84.62%  |
| Malfunc  | 6         | 13     | 11.54%  |
| Detected | 2         | 2      | 3.85%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 24        | 36.92%  |
| AMD                            | 12        | 18.46%  |
| Sandisk                        | 9         | 13.85%  |
| Samsung Electronics            | 7         | 10.77%  |
| SK Hynix                       | 3         | 4.62%   |
| Micron Technology              | 2         | 3.08%   |
| Kingston Technology Company    | 2         | 3.08%   |
| ADATA Technology               | 2         | 3.08%   |
| Solid State Storage Technology | 1         | 1.54%   |
| Silicon Motion                 | 1         | 1.54%   |
| Micron/Crucial Technology      | 1         | 1.54%   |
| Marvell Technology Group       | 1         | 1.54%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 10        | 14.08%  |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 6         | 8.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 6         | 8.45%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 5         | 7.04%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 5.63%   |
| Unknown                                                                        | 4         | 5.63%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3         | 4.23%   |
| AMD 400 Series Chipset SATA Controller                                         | 3         | 4.23%   |
| SK Hynix BC511                                                                 | 2         | 2.82%   |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 2         | 2.82%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 2.82%   |
| SK Hynix PC300 NVMe Solid State Drive 512GB                                    | 1         | 1.41%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1         | 1.41%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1         | 1.41%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 1.41%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 1         | 1.41%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                          | 1         | 1.41%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 1         | 1.41%   |
| Kingston Company A2000 NVMe SSD                                                | 1         | 1.41%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 1         | 1.41%   |
| Intel SSD 660P Series                                                          | 1         | 1.41%   |
| Intel NVMe Optane Memory Series                                                | 1         | 1.41%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 1.41%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.41%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 1         | 1.41%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 1         | 1.41%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 1         | 1.41%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 1         | 1.41%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]    | 1         | 1.41%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]    | 1         | 1.41%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1         | 1.41%   |
| AMD X399 Series Chipset SATA Controller                                        | 1         | 1.41%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                       | 1         | 1.41%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 1.41%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 1         | 1.41%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 31        | 49.21%  |
| NVMe | 29        | 46.03%  |
| IDE  | 2         | 3.17%   |
| RAID | 1         | 1.59%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 26        | 52%     |
| AMD     | 17        | 34%     |
| Unknown | 4         | 8%      |
| ARM     | 3         | 6%      |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i7-3520M CPU @ 2.90GHz               | 4         | 8%      |
|                                                 | 4         | 8%      |
| Intel Core i5-10210U CPU @ 1.60GHz              | 3         | 6%      |
| Intel Core i7-8750H CPU @ 2.20GHz               | 2         | 4%      |
| Intel Core i7-7600U CPU @ 2.80GHz               | 2         | 4%      |
| Intel Core i7-10750H CPU @ 2.60GHz              | 2         | 4%      |
| ARM Cortex-A72 r0p2                             | 2         | 4%      |
| AMD Ryzen 5 PRO 3500U w/ Radeon Vega Mobile Gfx | 2         | 4%      |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 2         | 4%      |
| Intel Xeon W-10885M CPU @ 2.40GHz               | 1         | 2%      |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz             | 1         | 2%      |
| Intel Pentium M processor 1000MHz               | 1         | 2%      |
| Intel Core i7-9750H CPU @ 2.60GHz               | 1         | 2%      |
| Intel Core i7-4710MQ CPU @ 2.50GHz              | 1         | 2%      |
| Intel Core i7-4710HQ CPU @ 2.50GHz              | 1         | 2%      |
| Intel Core i7-3770 CPU @ 3.40GHz                | 1         | 2%      |
| Intel Core i7-10700 CPU @ 2.90GHz               | 1         | 2%      |
| Intel Core i7-1065G7 CPU @ 1.30GHz              | 1         | 2%      |
| Intel Core i5-3320M CPU @ 2.60GHz               | 1         | 2%      |
| Intel Core i5-10500T CPU @ 2.30GHz              | 1         | 2%      |
| Intel Core i5-10300H CPU @ 2.50GHz              | 1         | 2%      |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 1         | 2%      |
| ARM Cortex-A72 r0p3                             | 1         | 2%      |
| AMD Ryzen Threadripper 1950X 16-Core Processor  | 1         | 2%      |
| AMD Ryzen 9 5900X 12-Core Processor             | 1         | 2%      |
| AMD Ryzen 9 3950X 16-Core Processor             | 1         | 2%      |
| AMD Ryzen 9 3900X 12-Core Processor             | 1         | 2%      |
| AMD Ryzen 7 PRO 3700U w/ Radeon Vega Mobile Gfx | 1         | 2%      |
| AMD Ryzen 7 4800U with Radeon Graphics          | 1         | 2%      |
| AMD Ryzen 7 4800H with Radeon Graphics          | 1         | 2%      |
| AMD Ryzen 7 4700U with Radeon Graphics          | 1         | 2%      |
| AMD Ryzen 7 2700X Eight-Core Processor          | 1         | 2%      |
| AMD Ryzen 5 2600X Six-Core Processor            | 1         | 2%      |
| AMD Ryzen 5 2600 Six-Core Processor             | 1         | 2%      |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx   | 1         | 2%      |
| AMD FX-8320E Eight-Core Processor               | 1         | 2%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 16        | 32%     |
| Intel Core i5          | 6         | 12%     |
| Other                  | 5         | 10%     |
| AMD Ryzen 7            | 4         | 8%      |
| AMD Ryzen 5            | 4         | 8%      |
| ARM Cortex             | 3         | 6%      |
| AMD Ryzen 9            | 3         | 6%      |
| Intel Xeon             | 2         | 4%      |
| AMD Ryzen 5 PRO        | 2         | 4%      |
| Intel Pentium M        | 1         | 2%      |
| AMD Ryzen Threadripper | 1         | 2%      |
| AMD Ryzen 7 PRO        | 1         | 2%      |
| AMD Ryzen 3            | 1         | 2%      |
| AMD FX                 | 1         | 2%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 10        | 20.41%  |
| 8       | 9         | 18.37%  |
| 2       | 7         | 14.29%  |
| 6       | 6         | 12.24%  |
| Unknown | 6         | 12.24%  |
| 16      | 4         | 8.16%   |
| 32      | 2         | 4.08%   |
| 24      | 2         | 4.08%   |
| 12      | 2         | 4.08%   |
| 1       | 1         | 2.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 44        | 88%     |
| Unknown | 5         | 10%     |
| 2       | 1         | 2%      |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 25        | 51.02%  |
| 1       | 17        | 34.69%  |
| Unknown | 7         | 14.29%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Zen+       | 8         | 16.33%  |
| KabyLake   | 8         | 16.33%  |
| IvyBridge  | 6         | 12.24%  |
| CometLake  | 6         | 12.24%  |
| Unknown    | 6         | 12.24%  |
| Zen 2      | 5         | 10.2%   |
| Zen        | 2         | 4.08%   |
| Haswell    | 2         | 4.08%   |
| Zen 3      | 1         | 2.04%   |
| TigerLake  | 1         | 2.04%   |
| Piledriver | 1         | 2.04%   |
| P6         | 1         | 2.04%   |
| IceLake    | 1         | 2.04%   |
| Broadwell  | 1         | 2.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 19        | 35.85%  |
| Nvidia                     | 18        | 33.96%  |
| AMD                        | 14        | 26.42%  |
| Matrox Electronics Systems | 1         | 1.89%   |
| ASPEED Technology          | 1         | 1.89%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| AMD Picasso                                                         | 5         | 9.26%   |
| Intel CometLake-U GT2 [UHD Graphics]                                | 3         | 5.56%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                           | 3         | 5.56%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                            | 3         | 5.56%   |
| AMD Renoir                                                          | 3         | 5.56%   |
| Nvidia TU117M                                                       | 2         | 3.7%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                          | 2         | 3.7%    |
| Nvidia GP108M [GeForce MX230]                                       | 2         | 3.7%    |
| Nvidia GK208B [GeForce GT 710]                                      | 2         | 3.7%    |
| Intel HD Graphics 620                                               | 2         | 3.7%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller         | 2         | 3.7%    |
| Intel 3rd Gen Core processor Graphics Controller                    | 2         | 3.7%    |
| Nvidia TU104GLM [Quadro RTX 5000 Mobile / Max-Q]                    | 1         | 1.85%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                          | 1         | 1.85%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                             | 1         | 1.85%   |
| Nvidia GP107GL [Quadro P620]                                        | 1         | 1.85%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                  | 1         | 1.85%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                 | 1         | 1.85%   |
| Nvidia GM206 [GeForce GTX 960]                                      | 1         | 1.85%   |
| Nvidia GM107M [GeForce GTX 860M]                                    | 1         | 1.85%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                   | 1         | 1.85%   |
| Nvidia GK107GLM [Quadro K1100M]                                     | 1         | 1.85%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)   | 1         | 1.85%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller    | 1         | 1.85%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                           | 1         | 1.85%   |
| Intel Iris Plus Graphics G7                                         | 1         | 1.85%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                            | 1         | 1.85%   |
| Intel CometLake-H GT2 [UHD Graphics]                                | 1         | 1.85%   |
| Intel Comet Lake-H WS GT2 Integrated UHD Graphics Controller        | 1         | 1.85%   |
| Intel 82852/855GM Integrated Graphics Device                        | 1         | 1.85%   |
| ASPEED Technology ASPEED Graphics Family                            | 1         | 1.85%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]    | 1         | 1.85%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]             | 1         | 1.85%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]             | 1         | 1.85%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X] | 1         | 1.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 13        | 26%     |
| 1 x Nvidia     | 10        | 20%     |
| 1 x Intel      | 10        | 20%     |
| Intel + Nvidia | 9         | 18%     |
| Other          | 5         | 10%     |
| 2 x AMD        | 1         | 2%      |
| 1 x Matrox     | 1         | 2%      |
| 1 x ASPEED     | 1         | 2%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 32        | 65.31%  |
| Proprietary | 12        | 24.49%  |
| Unknown     | 5         | 10.2%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 31        | 60.78%  |
| 1.01-2.0   | 6         | 11.76%  |
| 0.51-1.0   | 5         | 9.8%    |
| 3.01-4.0   | 4         | 7.84%   |
| 0.01-0.5   | 3         | 5.88%   |
| 7.01-8.0   | 1         | 1.96%   |
| 2.01-3.0   | 1         | 1.96%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| LG Display          | 8         | 16.67%  |
| BOE                 | 5         | 10.42%  |
| Philips             | 4         | 8.33%   |
| Hewlett-Packard     | 3         | 6.25%   |
| Goldstar            | 3         | 6.25%   |
| Chimei Innolux      | 3         | 6.25%   |
| AU Optronics        | 3         | 6.25%   |
| Samsung Electronics | 2         | 4.17%   |
| LG Electronics      | 2         | 4.17%   |
| Dell                | 2         | 4.17%   |
| Sony                | 1         | 2.08%   |
| SDC                 | 1         | 2.08%   |
| PANDA               | 1         | 2.08%   |
| LGD                 | 1         | 2.08%   |
| Lenovo              | 1         | 2.08%   |
| InfoVision          | 1         | 2.08%   |
| Iiyama              | 1         | 2.08%   |
| HJW                 | 1         | 2.08%   |
| Eizo                | 1         | 2.08%   |
| CSO                 | 1         | 2.08%   |
| BenQ                | 1         | 2.08%   |
| Apple               | 1         | 2.08%   |
| AOC                 | 1         | 2.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0258 1600x900 350x190mm 15.7-inch          | 3         | 6%      |
| Philips LCD Monitor PHL08C3 1920x1080 600x340mm 27.2-inch            | 2         | 4%      |
| Sony TV SNY4B03 1920x1080 930x520mm 41.9-inch                        | 1         | 2%      |
| SDC LCD Monitor 3520x1080                                            | 1         | 2%      |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                     | 1         | 2%      |
| Samsung Electronics LCD Monitor SDC3754 1600x900 380x210mm 17.1-inch | 1         | 2%      |
| Philips PHL 273V7 PHLC156 1920x1080 600x340mm 27.2-inch              | 1         | 2%      |
| Philips LCD Monitor 271P4 3520x1080                                  | 1         | 2%      |
| Philips LCD Monitor 271P4                                            | 1         | 2%      |
| PANDA LCD Monitor NCP004F 1920x1080 310x170mm 13.9-inch              | 1         | 2%      |
| LGD LCD Monitor 1920x1080                                            | 1         | 2%      |
| LG Electronics LCD Monitor LX20D 1600x1200                           | 1         | 2%      |
| LG Electronics LCD Monitor LG Ultra HD 11520x2160                    | 1         | 2%      |
| LG Electronics LCD Monitor LG Ultra HD                               | 1         | 2%      |
| LG Display LCD Monitor LGD062E 1920x1080 340x190mm 15.3-inch         | 1         | 2%      |
| LG Display LCD Monitor LGD060A 1920x1080 290x170mm 13.2-inch         | 1         | 2%      |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch         | 1         | 2%      |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch         | 1         | 2%      |
| LG Display LCD Monitor LGD033E 1366x768 310x170mm 13.9-inch          | 1         | 2%      |
| Lenovo LEN P44w-10 LEN61D5 3840x1200 1050x330mm 43.3-inch            | 1         | 2%      |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch         | 1         | 2%      |
| Iiyama PL2474H IVM6146 1920x1080 520x290mm 23.4-inch                 | 1         | 2%      |
| HJW HDMI TO USB HJW0001 1920x1080 700x390mm 31.5-inch                | 1         | 2%      |
| Hewlett-Packard LCD Monitor LA2306 3520x1080                         | 1         | 2%      |
| Hewlett-Packard LA2306 HWP2949 1920x1080 510x290mm 23.1-inch         | 1         | 2%      |
| Hewlett-Packard E242 HWP326E 1920x1200 520x320mm 24.0-inch           | 1         | 2%      |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch           | 1         | 2%      |
| Goldstar 27GK750F GSM770F 1920x1080 600x340mm 27.2-inch              | 1         | 2%      |
| Goldstar 23EA53 GSM59A8 1920x1080 510x290mm 23.1-inch                | 1         | 2%      |
| Eizo FX2431 ENC2036 1920x1200 520x330mm 24.2-inch                    | 1         | 2%      |
| Dell U2718Q DELA0EC 3840x2160 610x350mm 27.7-inch                    | 1         | 2%      |
| Dell U2518D DEL413C 2560x1440 550x310mm 24.9-inch                    | 1         | 2%      |
| CSO LCD Monitor CSO1500 3840x2160 340x190mm 15.3-inch                | 1         | 2%      |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 280x180mm 13.1-inch     | 1         | 2%      |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 340x190mm 15.3-inch     | 1         | 2%      |
| Chimei Innolux LCD Monitor CMN13A2 1920x1080 290x170mm 13.2-inch     | 1         | 2%      |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                | 1         | 2%      |
| BOE LCD Monitor BOE084D 1920x1080 340x190mm 15.3-inch                | 1         | 2%      |
| BOE LCD Monitor BOE07F1 1920x1080 340x190mm 15.3-inch                | 1         | 2%      |
| BOE LCD Monitor BOE0792 1920x1080 340x190mm 15.3-inch                | 1         | 2%      |
| BOE LCD Monitor BOE0747 1920x1080 340x190mm 15.3-inch                | 1         | 2%      |
| BenQ GW2280 BNQ78E8 1920x1080 480x270mm 21.7-inch                    | 1         | 2%      |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch        | 1         | 2%      |
| AU Optronics LCD Monitor AUO2026 2560x1600 290x180mm 13.4-inch       | 1         | 2%      |
| AU Optronics LCD Monitor AUO139D 1920x1080 380x210mm 17.1-inch       | 1         | 2%      |
| Apple Cinema HD APP9223 1920x1200 490x310mm 22.8-inch                | 1         | 2%      |
| AOC Q3277 AOC3277 2560x1440 710x400mm 32.1-inch                      | 1         | 2%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 24        | 51.06%  |
| 1600x900 (HD+)    | 5         | 10.64%  |
| 3840x2160 (4K)    | 4         | 8.51%   |
| 1920x1200 (WUXGA) | 3         | 6.38%   |
| Unknown           | 2         | 4.26%   |
| 3840x1200         | 1         | 2.13%   |
| 3520x1080         | 1         | 2.13%   |
| 2560x1600         | 1         | 2.13%   |
| 2560x1440 (QHD)   | 1         | 2.13%   |
| 2256x1504         | 1         | 2.13%   |
| 2160x1440         | 1         | 2.13%   |
| 1600x1200         | 1         | 2.13%   |
| 1366x768 (WXGA)   | 1         | 2.13%   |
| 11520x2160        | 1         | 2.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 10        | 21.74%  |
| 13      | 10        | 21.74%  |
| 27      | 6         | 13.04%  |
| Unknown | 5         | 10.87%  |
| 24      | 3         | 6.52%   |
| 23      | 3         | 6.52%   |
| 17      | 2         | 4.35%   |
| 43      | 1         | 2.17%   |
| 41      | 1         | 2.17%   |
| 32      | 1         | 2.17%   |
| 31      | 1         | 2.17%   |
| 22      | 1         | 2.17%   |
| 21      | 1         | 2.17%   |
| 12      | 1         | 2.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 15        | 33.33%  |
| 501-600     | 10        | 22.22%  |
| 201-300     | 6         | 13.33%  |
| Unknown     | 5         | 11.11%  |
| 601-700     | 2         | 4.44%   |
| 401-500     | 2         | 4.44%   |
| 351-400     | 2         | 4.44%   |
| 701-800     | 1         | 2.22%   |
| 1001-1500   | 1         | 2.22%   |
| 901-1000    | 1         | 2.22%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 29        | 72.5%   |
| 16/10   | 5         | 12.5%   |
| Unknown | 4         | 10%     |
| 3/2     | 1         | 2.5%    |
| 3.18    | 1         | 2.5%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 7         | 15.22%  |
| 91-100         | 7         | 15.22%  |
| 301-350        | 6         | 13.04%  |
| 201-250        | 5         | 10.87%  |
| Unknown        | 5         | 10.87%  |
| 71-80          | 3         | 6.52%   |
| 251-300        | 3         | 6.52%   |
| 101-110        | 3         | 6.52%   |
| 351-500        | 2         | 4.35%   |
| 121-130        | 2         | 4.35%   |
| 501-1000       | 2         | 4.35%   |
| 61-70          | 1         | 2.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 13        | 29.55%  |
| 121-160       | 12        | 27.27%  |
| 161-240       | 7         | 15.91%  |
| 101-120       | 6         | 13.64%  |
| Unknown       | 5         | 11.36%  |
| More than 240 | 1         | 2.27%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 26        | 52%     |
| 0     | 14        | 28%     |
| 2     | 9         | 18%     |
| 3     | 1         | 2%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 37        | 46.25%  |
| Realtek Semiconductor | 26        | 32.5%   |
| TP-Link               | 4         | 5%      |
| Hewlett-Packard       | 3         | 3.75%   |
| Ralink Technology     | 2         | 2.5%    |
| D-Link System         | 2         | 2.5%    |
| Qualcomm Atheros      | 1         | 1.25%   |
| Mellanox Technologies | 1         | 1.25%   |
| Lenovo                | 1         | 1.25%   |
| Emulex                | 1         | 1.25%   |
| BUFFALO               | 1         | 1.25%   |
| Arduino SA            | 1         | 1.25%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 21        | 21.65%  |
| Intel Wireless-AC 9260                                                     | 5         | 5.15%   |
| Intel Wi-Fi 6 AX200                                                        | 5         | 5.15%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 5         | 5.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 5         | 5.15%   |
| Intel Wireless 8265 / 8275                                                 | 4         | 4.12%   |
| Intel Comet Lake PCH CNVi WiFi                                             | 4         | 4.12%   |
| Intel I211 Gigabit Network Connection                                      | 3         | 3.09%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                          | 3         | 3.09%   |
| HP hs2350 HSPA+ Mobile Broadband Module Network Adapter                    | 3         | 3.09%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 2         | 2.06%   |
| Realtek RTL8125 2.5GbE Controller                                          | 2         | 2.06%   |
| Intel Wireless 7260                                                        | 2         | 2.06%   |
| Intel Ethernet Connection (4) I219-LM                                      | 2         | 2.06%   |
| Intel Ethernet Connection (11) I219-LM                                     | 2         | 2.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 2         | 2.06%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 2         | 2.06%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                     | 1         | 1.03%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]        | 1         | 1.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 1.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 1.03%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                     | 1         | 1.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 1         | 1.03%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 1         | 1.03%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 1         | 1.03%   |
| Ralink RT2870/RT3070 Wireless Adapter                                      | 1         | 1.03%   |
| Ralink MT7601U Wireless Adapter                                            | 1         | 1.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 1         | 1.03%   |
| Mellanox MT27710 Family [ConnectX-4 Lx]                                    | 1         | 1.03%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                           | 1         | 1.03%   |
| Intel Wi-Fi 6 AX201                                                        | 1         | 1.03%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                  | 1         | 1.03%   |
| Intel I210 Gigabit Network Connection                                      | 1         | 1.03%   |
| Intel Ethernet Controller I225-V                                           | 1         | 1.03%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                              | 1         | 1.03%   |
| Intel Ethernet Connection I217-LM                                          | 1         | 1.03%   |
| Intel Ethernet Connection (7) I219-V                                       | 1         | 1.03%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller          | 1         | 1.03%   |
| Intel 82574L Gigabit Network Connection                                    | 1         | 1.03%   |
| Emulex OneConnect 10Gb NIC (be3)                                           | 1         | 1.03%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]                   | 1         | 1.03%   |
| Arduino SA Uno R3 (CDC ACM)                                                | 1         | 1.03%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 32        | 69.57%  |
| TP-Link               | 4         | 8.7%    |
| Realtek Semiconductor | 4         | 8.7%    |
| Ralink Technology     | 2         | 4.35%   |
| D-Link System         | 2         | 4.35%   |
| Qualcomm Atheros      | 1         | 2.17%   |
| BUFFALO               | 1         | 2.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Wireless-AC 9260                                                     | 5         | 10.87%  |
| Intel Wi-Fi 6 AX200                                                        | 5         | 10.87%  |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 5         | 10.87%  |
| Intel Wireless 8265 / 8275                                                 | 4         | 8.7%    |
| Intel Comet Lake PCH CNVi WiFi                                             | 4         | 8.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                          | 3         | 6.52%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 2         | 4.35%   |
| Intel Wireless 7260                                                        | 2         | 4.35%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 2         | 4.35%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 2         | 4.35%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                     | 1         | 2.17%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]        | 1         | 2.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 2.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 2.17%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                     | 1         | 2.17%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 1         | 2.17%   |
| Ralink RT2870/RT3070 Wireless Adapter                                      | 1         | 2.17%   |
| Ralink MT7601U Wireless Adapter                                            | 1         | 2.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 1         | 2.17%   |
| Intel Wi-Fi 6 AX201                                                        | 1         | 2.17%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                  | 1         | 2.17%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]                   | 1         | 2.17%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 25        | 55.56%  |
| Intel                 | 18        | 40%     |
| Lenovo                | 1         | 2.22%   |
| Emulex                | 1         | 2.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 21        | 46.67%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 11.11%  |
| Intel I211 Gigabit Network Connection                             | 3         | 6.67%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 4.44%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 4.44%   |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 4.44%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 2.22%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 2.22%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                  | 1         | 2.22%   |
| Intel I210 Gigabit Network Connection                             | 1         | 2.22%   |
| Intel Ethernet Controller I225-V                                  | 1         | 2.22%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1         | 2.22%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 2.22%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 2.22%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 2.22%   |
| Emulex OneConnect 10Gb NIC (be3)                                  | 1         | 2.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 41        | 49.4%   |
| WiFi     | 36        | 43.37%  |
| Modem    | 5         | 6.02%   |
| Unknown  | 1         | 1.2%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 39        | 63.93%  |
| WiFi     | 20        | 32.79%  |
| Modem    | 2         | 3.28%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 32        | 65.31%  |
| 1     | 10        | 20.41%  |
| 0     | 4         | 8.16%   |
| 3     | 2         | 4.08%   |
| 7     | 1         | 2.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 43        | 82.69%  |
| Yes  | 9         | 17.31%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 23        | 88.46%  |
| Realtek Semiconductor | 1         | 3.85%   |
| Realtek               | 1         | 3.85%   |
| Broadcom              | 1         | 3.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                          | 6         | 23.08%  |
| Intel Bluetooth wireless interface             | 5         | 19.23%  |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 4         | 15.38%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 4         | 15.38%  |
| Intel AX200 Bluetooth                          | 4         | 15.38%  |
| Realtek  Bluetooth Adapter                     | 1         | 3.85%   |
| Realtek Bluetooth Radio                        | 1         | 3.85%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 1         | 3.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 24        | 35.82%  |
| AMD                     | 20        | 29.85%  |
| Nvidia                  | 15        | 22.39%  |
| Lenovo                  | 2         | 2.99%   |
| Yamaha                  | 1         | 1.49%   |
| GN Netcom               | 1         | 1.49%   |
| CMX Systems             | 1         | 1.49%   |
| C-Media Electronics     | 1         | 1.49%   |
| AudioQuest              | 1         | 1.49%   |
| AKAI  Professional M.I. | 1         | 1.49%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                 | 9         | 11.25%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 6         | 7.5%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 6         | 7.5%    |
| Intel Comet Lake PCH cAVS                                           | 5         | 6.25%   |
| Nvidia GP107GL High Definition Audio Controller                     | 4         | 5%      |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                 | 4         | 5%      |
| Intel Comet Lake PCH-LP cAVS                                        | 3         | 3.75%   |
| Intel Cannon Lake PCH cAVS                                          | 3         | 3.75%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]           | 3         | 3.75%   |
| AMD Starship/Matisse HD Audio Controller                            | 3         | 3.75%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 3         | 3.75%   |
| Nvidia TU116 High Definition Audio Controller                       | 2         | 2.5%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller      | 2         | 2.5%    |
| Nvidia GK208 HDMI/DP Audio Controller                               | 2         | 2.5%    |
| Intel Sunrise Point-LP HD Audio                                     | 2         | 2.5%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 2         | 2.5%    |
| Yamaha Steinberg UR12                                               | 1         | 1.25%   |
| Nvidia TU104 HD Audio Controller                                    | 1         | 1.25%   |
| Nvidia GP106 High Definition Audio Controller                       | 1         | 1.25%   |
| Nvidia GM206 High Definition Audio Controller                       | 1         | 1.25%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]       | 1         | 1.25%   |
| Nvidia GK107 HDMI Audio Controller                                  | 1         | 1.25%   |
| Lenovo ThinkPad Dock Audio                                          | 1         | 1.25%   |
| Lenovo Realtek USB Audio                                            | 1         | 1.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 1         | 1.25%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller         | 1         | 1.25%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller           | 1         | 1.25%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller   | 1         | 1.25%   |
| GN Netcom Jabra SPEAK 410 USB                                       | 1         | 1.25%   |
| CMX Systems USB PnP Audio Device                                    | 1         | 1.25%   |
| C-Media Electronics BIRD UM1                                        | 1         | 1.25%   |
| AudioQuest DragonFly                                                | 1         | 1.25%   |
| AMD SBx00 Azalia (Intel HDA)                                        | 1         | 1.25%   |
| AMD Navi 10 HDMI Audio                                              | 1         | 1.25%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]          | 1         | 1.25%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]        | 1         | 1.25%   |
| AKAI  Professional M.I. LPK25 MIDI Keyboard                         | 1         | 1.25%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 11        | 22.45%  |
| SK Hynix            | 8         | 16.33%  |
| Micron Technology   | 8         | 16.33%  |
| Kingston            | 8         | 16.33%  |
| Crucial             | 4         | 8.16%   |
| Unknown             | 2         | 4.08%   |
| Smart               | 2         | 4.08%   |
| Corsair             | 2         | 4.08%   |
| Ramaxel Technology  | 1         | 2.04%   |
| PNY                 | 1         | 2.04%   |
| GOODRAM             | 1         | 2.04%   |
| A-DATA Technology   | 1         | 2.04%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s        | 4         | 8.16%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 4.08%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s       | 2         | 4.08%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s        | 2         | 4.08%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s         | 2         | 4.08%   |
| Crucial RAM BL32G32C16S4B.M16FB1 32GB SODIMM DDR4 2667MT/s   | 2         | 4.08%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                    | 1         | 2.04%   |
| Unknown RAM Module 1GB SODIMM DDR                            | 1         | 2.04%   |
| Smart RAM SF4641G8CK8IWGKSEG 8GB SODIMM DDR4 2133MT/s        | 1         | 2.04%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s        | 1         | 2.04%   |
| SK Hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 2.04%   |
| SK Hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s      | 1         | 2.04%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 2.04%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 2.04%   |
| Samsung RAM M474A4G43AB1-CVF 32GB SODIMM DDR4 2933MT/s       | 1         | 2.04%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s       | 1         | 2.04%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 2.04%   |
| Samsung RAM M378A4G43MB1-CTD 32GB DIMM DDR4 2666MT/s         | 1         | 2.04%   |
| Samsung RAM K4EBE304EB-EGCF 8GB Row Of Chips LPDDR3 1867MT/s | 1         | 2.04%   |
| Ramaxel RAM RMSA3320MJ78HAF-3200 8GB SODIMM DDR4 3200MT/s    | 1         | 2.04%   |
| PNY RAM 16GU2X16LIII43-12-K 16GB SODIMM DDR4 2667MT/s        | 1         | 2.04%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                   | 1         | 2.04%   |
| Micron RAM Module 16GB DIMM DDR4 2400MT/s                    | 1         | 2.04%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s   | 1         | 2.04%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s        | 1         | 2.04%   |
| Micron RAM 16ATF2G64HZ-2G6J1 16GB SODIMM DDR4 2667MT/s       | 1         | 2.04%   |
| Micron RAM 16ATF2G64AZ-3G2J1 16GB DIMM DDR4 3200MT/s         | 1         | 2.04%   |
| Kingston RAM Module 16GB SODIMM DDR4 2667MT/s                | 1         | 2.04%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 2933MT/s         | 1         | 2.04%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 2666MT/s          | 1         | 2.04%   |
| Kingston RAM KHX2400C14S4/4G 4GB SODIMM DDR4 2400MT/s        | 1         | 2.04%   |
| Kingston RAM KHX1600C10D3/ 8GB DIMM DDR3 1600MT/s            | 1         | 2.04%   |
| Kingston RAM 99U5428-063.A00LF 8GB SODIMM DDR3 1600MT/s      | 1         | 2.04%   |
| Kingston RAM 9905713-030.A00G 8GB DIMM DDR4 2666MT/s         | 1         | 2.04%   |
| Kingston RAM 9905428-196.A00LF 8GB SODIMM DDR3 1333MT/s      | 1         | 2.04%   |
| GOODRAM RAM GR1600S364L11/8G 8GB SODIMM DDR3 1600MT/s        | 1         | 2.04%   |
| Crucial RAM CT16G4DFD832A.C16FP 16GB DIMM DDR4 3200MT/s      | 1         | 2.04%   |
| Crucial RAM BL16G36C16U4B.M8FB1 16GB DIMM DDR4 3600MT/s      | 1         | 2.04%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s        | 1         | 2.04%   |
| Corsair RAM CMD128GX4M8A2400C14 16GB DIMM DDR4 2133MT/s      | 1         | 2.04%   |
| A-DATA RAM DDR4 3200 16GB SODIMM DDR4 2667MT/s               | 1         | 2.04%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 32        | 74.42%  |
| DDR3   | 9         | 20.93%  |
| LPDDR3 | 1         | 2.33%   |
| DDR    | 1         | 2.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 30        | 69.77%  |
| DIMM         | 11        | 25.58%  |
| Row Of Chips | 2         | 4.65%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 23        | 53.49%  |
| 16384 | 12        | 27.91%  |
| 32768 | 4         | 9.3%    |
| 4096  | 3         | 6.98%   |
| 1024  | 1         | 2.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 16        | 35.56%  |
| 1600    | 8         | 17.78%  |
| 3200    | 7         | 15.56%  |
| 2666    | 3         | 6.67%   |
| 2400    | 3         | 6.67%   |
| 2933    | 2         | 4.44%   |
| 2133    | 2         | 4.44%   |
| 3600    | 1         | 2.22%   |
| 1867    | 1         | 2.22%   |
| 1333    | 1         | 2.22%   |
| Unknown | 1         | 2.22%   |

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
| Chicony Electronics                    | 8         | 22.22%  |
| IMC Networks                           | 7         | 19.44%  |
| Logitech                               | 6         | 16.67%  |
| Lite-On Technology                     | 4         | 11.11%  |
| Realtek Semiconductor                  | 3         | 8.33%   |
| Microdia                               | 2         | 5.56%   |
| Acer                                   | 2         | 5.56%   |
| Syntek                                 | 1         | 2.78%   |
| Sunplus Innovation Technology          | 1         | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.78%   |
| Aveo Technology                        | 1         | 2.78%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                           | 4         | 10.81%  |
| Logitech Webcam C270                                                     | 3         | 8.11%   |
| Chicony Integrated HP HD Webcam                                          | 3         | 8.11%   |
| Chicony Integrated Camera                                                | 3         | 8.11%   |
| Logitech HD Pro Webcam C920                                              | 2         | 5.41%   |
| Lite-On Integrated Camera                                                | 2         | 5.41%   |
| Lite-On HP HD Camera                                                     | 2         | 5.41%   |
| Syntek Lenovo EasyCamera                                                 | 1         | 2.7%    |
| Sunplus Integrated_Webcam_HD                                             | 1         | 2.7%    |
| Realtek USB 2 Webcam                                                     | 1         | 2.7%    |
| Realtek Laptop Camera                                                    | 1         | 2.7%    |
| Realtek Integrated_Webcam_HD                                             | 1         | 2.7%    |
| Microdia HP Integrated Webcam                                            | 1         | 2.7%    |
| Microdia Dell Integrated HD Webcam                                       | 1         | 2.7%    |
| Logitech Webcam C170                                                     | 1         | 2.7%    |
| IMC Networks USB2.0 HD UVC WebCam                                        | 1         | 2.7%    |
| IMC Networks HD Camera                                                   | 1         | 2.7%    |
| IMC Networks EasyCamera                                                  | 1         | 2.7%    |
| Chicony ThinkPad T490 Webcam                                             | 1         | 2.7%    |
| Chicony Integrated IR Camera                                             | 1         | 2.7%    |
| Chicony HD Webcam                                                        | 1         | 2.7%    |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 1         | 2.7%    |
| Aveo USB2.0 Camera                                                       | 1         | 2.7%    |
| Acer Integrated Camera                                                   | 1         | 2.7%    |
| Acer HD Webcam                                                           | 1         | 2.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 6         | 50%     |
| Shenzhen Goodix Technology | 3         | 25%     |
| Validity Sensors           | 2         | 16.67%  |
| AuthenTec                  | 1         | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
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

![Unsupported Devices](./All/images/pie_chart_bsd/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 12        | 24%     |
| 0     | 12        | 24%     |
| 4     | 9         | 18%     |
| 1     | 8         | 16%     |
| 3     | 5         | 10%     |
| 5     | 3         | 6%      |
| 9     | 1         | 2%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 28        | 33.33%  |
| Net/wireless             | 17        | 20.24%  |
| Bluetooth                | 15        | 17.86%  |
| Fingerprint reader       | 12        | 14.29%  |
| Card reader              | 5         | 5.95%   |
| Sound                    | 3         | 3.57%   |
| Firewire controller      | 2         | 2.38%   |
| Network                  | 1         | 1.19%   |
| Modem                    | 1         | 1.19%   |

