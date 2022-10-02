FreeBSD 13.1 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for FreeBSD 13.1.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Acer          | Swift SF313-52              | [6339e6b468](https://bsd-hardware.info/?probe=6339e6b468) | Sep 25, 2022 |
| System76      | Gazelle                     | [d087321049](https://bsd-hardware.info/?probe=d087321049) | Sep 24, 2022 |
| ASUSTek       | X455LJ                      | [431ad10ab2](https://bsd-hardware.info/?probe=431ad10ab2) | Sep 17, 2022 |
| Lenovo        | ThinkPad L420 7829WDY       | [a697be2aa9](https://bsd-hardware.info/?probe=a697be2aa9) | Sep 16, 2022 |
| Google        | Peppy                       | [80ffa77224](https://bsd-hardware.info/?probe=80ffa77224) | Sep 15, 2022 |
| Dell          | Latitude 5310               | [6edf4d34fe](https://bsd-hardware.info/?probe=6edf4d34fe) | Sep 07, 2022 |
| Dell          | Vostro 5415                 | [ef6d4ee660](https://bsd-hardware.info/?probe=ef6d4ee660) | Sep 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [cffed92600](https://bsd-hardware.info/?probe=cffed92600) | Sep 06, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [72757feb65](https://bsd-hardware.info/?probe=72757feb65) | Sep 03, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [5d575c85d0](https://bsd-hardware.info/?probe=5d575c85d0) | Sep 03, 2022 |
| Toshiba       | Satellite A300              | [ac185c104b](https://bsd-hardware.info/?probe=ac185c104b) | Aug 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [0466d87f04](https://bsd-hardware.info/?probe=0466d87f04) | Aug 25, 2022 |
| HP            | Pavilion g6                 | [c146b538e1](https://bsd-hardware.info/?probe=c146b538e1) | Aug 20, 2022 |
| ASUSTek       | ZenBook 14 UX410UFR         | [2bf0f0ef08](https://bsd-hardware.info/?probe=2bf0f0ef08) | Aug 19, 2022 |
| Google        | Peppy                       | [e2e0a1953d](https://bsd-hardware.info/?probe=e2e0a1953d) | Aug 18, 2022 |
| MSI           | GF63 Thin 9SC               | [dacea7c6be](https://bsd-hardware.info/?probe=dacea7c6be) | Aug 14, 2022 |
| Dell          | Inspiron 3581               | [f31cc32515](https://bsd-hardware.info/?probe=f31cc32515) | Aug 04, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | [f603e648c7](https://bsd-hardware.info/?probe=f603e648c7) | Aug 01, 2022 |
| Lenovo        | ThinkPad T480 20L6S29E0T    | [546fa8380b](https://bsd-hardware.info/?probe=546fa8380b) | Aug 01, 2022 |
| Dell          | Inspiron 5559               | [13baedb59b](https://bsd-hardware.info/?probe=13baedb59b) | Jul 31, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [7b130fb168](https://bsd-hardware.info/?probe=7b130fb168) | Jul 27, 2022 |
| Dell          | Precision 5560              | [3dc82c6d91](https://bsd-hardware.info/?probe=3dc82c6d91) | Jul 23, 2022 |
| Lenovo        | G40-45 80E1                 | [6e31b5f45b](https://bsd-hardware.info/?probe=6e31b5f45b) | Jul 23, 2022 |
| Dell          | Studio XPS 1340             | [642da98e96](https://bsd-hardware.info/?probe=642da98e96) | Jul 21, 2022 |
| Dell          | Inspiron 5559               | [321d3333dd](https://bsd-hardware.info/?probe=321d3333dd) | Jul 19, 2022 |
| Dell          | Inspiron 5559               | [6308d8da4f](https://bsd-hardware.info/?probe=6308d8da4f) | Jul 19, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [9af051c79f](https://bsd-hardware.info/?probe=9af051c79f) | Jul 17, 2022 |
| Lenovo        | ThinkPad T480 20L6SB2N00    | [6c5c9eefc0](https://bsd-hardware.info/?probe=6c5c9eefc0) | Jul 17, 2022 |
| Lenovo        | ThinkPad T420 4236C92       | [4067ce2036](https://bsd-hardware.info/?probe=4067ce2036) | Jul 16, 2022 |
| Lenovo        | ThinkPad X260 20F6S0KA00    | [117014d55f](https://bsd-hardware.info/?probe=117014d55f) | Jul 14, 2022 |
| Toshiba       | Satellite L305D             | [b0311b8175](https://bsd-hardware.info/?probe=b0311b8175) | Jul 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [7081ddd59c](https://bsd-hardware.info/?probe=7081ddd59c) | Jul 11, 2022 |
| Dell          | Inspiron 5559               | [7bad2fce01](https://bsd-hardware.info/?probe=7bad2fce01) | Jul 07, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [66543e9280](https://bsd-hardware.info/?probe=66543e9280) | Jul 07, 2022 |
| Dell          | Latitude E6420              | [c41c8ff4f4](https://bsd-hardware.info/?probe=c41c8ff4f4) | Jul 07, 2022 |
| Fujitsu       | LIFEBOOK A555               | [d9fd7e54cf](https://bsd-hardware.info/?probe=d9fd7e54cf) | Jul 06, 2022 |
| Unknown       | Unknown                     | [584ecf8423](https://bsd-hardware.info/?probe=584ecf8423) | Jul 05, 2022 |
| HP            | Laptop 15-bs1xx             | [b697848727](https://bsd-hardware.info/?probe=b697848727) | Jul 05, 2022 |
| Dell          | Inspiron 5559               | [452aabec42](https://bsd-hardware.info/?probe=452aabec42) | Jul 02, 2022 |
| LG Electro... | 17Z990-R.AAC9U1             | [5777cb6dc6](https://bsd-hardware.info/?probe=5777cb6dc6) | Jul 01, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | [f573327012](https://bsd-hardware.info/?probe=f573327012) | Jun 29, 2022 |
| Acer          | Aspire A114-33              | [d3659c85e9](https://bsd-hardware.info/?probe=d3659c85e9) | Jun 28, 2022 |
| Samsung       | R530/R730/R540              | [a4cd230718](https://bsd-hardware.info/?probe=a4cd230718) | Jun 27, 2022 |
| Dell          | Inspiron 5559               | [e0c49be06e](https://bsd-hardware.info/?probe=e0c49be06e) | Jun 27, 2022 |
| Dell          | Inspiron 5559               | [5b7a6bf8f8](https://bsd-hardware.info/?probe=5b7a6bf8f8) | Jun 19, 2022 |
| Fujitsu Si... | AMILO Li3710                | [6d4bc39638](https://bsd-hardware.info/?probe=6d4bc39638) | Jun 18, 2022 |
| Sony          | VGN-NS21M_S                 | [c9701a7ff5](https://bsd-hardware.info/?probe=c9701a7ff5) | Jun 18, 2022 |
| Dell          | Inspiron 5559               | [3344e5152d](https://bsd-hardware.info/?probe=3344e5152d) | Jun 16, 2022 |
| Dell          | Inspiron 5559               | [9f630c894a](https://bsd-hardware.info/?probe=9f630c894a) | Jun 16, 2022 |
| Dell          | Latitude E5420              | [524ab094e1](https://bsd-hardware.info/?probe=524ab094e1) | Jun 13, 2022 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | [8825a49f37](https://bsd-hardware.info/?probe=8825a49f37) | Jun 13, 2022 |
| HP            | Laptop 15s-fq1xxx           | [380218b2c1](https://bsd-hardware.info/?probe=380218b2c1) | Jun 12, 2022 |
| Fujitsu Si... | AMILO Li3710                | [387bf3d18f](https://bsd-hardware.info/?probe=387bf3d18f) | Jun 12, 2022 |
| Dell          | Inspiron 5559               | [e7017b0ea5](https://bsd-hardware.info/?probe=e7017b0ea5) | Jun 12, 2022 |
| Fujitsu Si... | AMILO Li3710                | [edebcb2719](https://bsd-hardware.info/?probe=edebcb2719) | Jun 12, 2022 |
| Fujitsu       | LIFEBOOK A555               | [23d96bc669](https://bsd-hardware.info/?probe=23d96bc669) | Jun 11, 2022 |
| Dell          | Latitude E5420              | [aca711c5ec](https://bsd-hardware.info/?probe=aca711c5ec) | Jun 09, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [9f33082ffa](https://bsd-hardware.info/?probe=9f33082ffa) | Jun 08, 2022 |
| Dell          | Precision M4800             | [4d77bb0082](https://bsd-hardware.info/?probe=4d77bb0082) | Jun 08, 2022 |
| Dell          | Precision M4800             | [b9169c863c](https://bsd-hardware.info/?probe=b9169c863c) | Jun 08, 2022 |
| Dell          | Inspiron 5559               | [1a9b85f6c5](https://bsd-hardware.info/?probe=1a9b85f6c5) | Jun 07, 2022 |
| Dell          | Latitude E5420              | [a3a9820968](https://bsd-hardware.info/?probe=a3a9820968) | Jun 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | [56111732fd](https://bsd-hardware.info/?probe=56111732fd) | Jun 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | [aeec87e07f](https://bsd-hardware.info/?probe=aeec87e07f) | Jun 06, 2022 |
| Lenovo        | ThinkPad X220 4286CTO       | [cb98f3014e](https://bsd-hardware.info/?probe=cb98f3014e) | Jun 05, 2022 |
| Dell          | Latitude 7490               | [18215740d1](https://bsd-hardware.info/?probe=18215740d1) | Jun 05, 2022 |
| Dell          | Inspiron 5559               | [0f0c2bcf67](https://bsd-hardware.info/?probe=0f0c2bcf67) | Jun 04, 2022 |
| Dell          | Latitude E5500              | [b1cb5de914](https://bsd-hardware.info/?probe=b1cb5de914) | Jun 03, 2022 |
| ASUSTek       | X441UV                      | [c8906b438b](https://bsd-hardware.info/?probe=c8906b438b) | Jun 03, 2022 |
| Apple         | MacBookPro11,4              | [29f1ef0cdc](https://bsd-hardware.info/?probe=29f1ef0cdc) | Jun 02, 2022 |
| Lenovo        | ThinkPad W520 4282AD4       | [40198abaa2](https://bsd-hardware.info/?probe=40198abaa2) | Jun 02, 2022 |
| Acer          | Nitro AN515-55              | [0cf6981a98](https://bsd-hardware.info/?probe=0cf6981a98) | Jun 02, 2022 |
| GPD           | MicroPC                     | [a448570ff9](https://bsd-hardware.info/?probe=a448570ff9) | May 31, 2022 |
| Dell          | Inspiron 5559               | [ca9f2125af](https://bsd-hardware.info/?probe=ca9f2125af) | May 31, 2022 |
| Dell          | Inspiron 5559               | [283a074737](https://bsd-hardware.info/?probe=283a074737) | May 31, 2022 |
| GPD           | MicroPC                     | [0046ab7c9b](https://bsd-hardware.info/?probe=0046ab7c9b) | May 31, 2022 |
| HP            | Pavilion g6                 | [32854b73a5](https://bsd-hardware.info/?probe=32854b73a5) | May 30, 2022 |
| System76      | Galago Pro                  | [126ebc1522](https://bsd-hardware.info/?probe=126ebc1522) | May 29, 2022 |
| Dell          | G5 5590                     | [86bac52410](https://bsd-hardware.info/?probe=86bac52410) | May 29, 2022 |
| Dell          | Latitude E6430              | [d7ced37bac](https://bsd-hardware.info/?probe=d7ced37bac) | May 29, 2022 |
| Lenovo        | ThinkPad X250 20CMS0FA00    | [5afeac632d](https://bsd-hardware.info/?probe=5afeac632d) | May 28, 2022 |
| Unknown       | Unknown                     | [3ff577e111](https://bsd-hardware.info/?probe=3ff577e111) | May 26, 2022 |
| Unknown       | Unknown                     | [9e2f16664a](https://bsd-hardware.info/?probe=9e2f16664a) | May 26, 2022 |
| Dell          | Inspiron 3505               | [cddd786b51](https://bsd-hardware.info/?probe=cddd786b51) | May 26, 2022 |
| Notebook      | N7x0WU                      | [37242aa9a3](https://bsd-hardware.info/?probe=37242aa9a3) | May 25, 2022 |
| TUXEDO        | Aura 15 Gen1                | [727f9708b4](https://bsd-hardware.info/?probe=727f9708b4) | May 24, 2022 |
| Dell          | Latitude E6540              | [70871cf070](https://bsd-hardware.info/?probe=70871cf070) | May 24, 2022 |
| Dell          | Precision M4800             | [6a703b66f8](https://bsd-hardware.info/?probe=6a703b66f8) | May 22, 2022 |
| Dell          | Latitude E7240              | [970234b430](https://bsd-hardware.info/?probe=970234b430) | May 22, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [cf5f498572](https://bsd-hardware.info/?probe=cf5f498572) | May 21, 2022 |
| Dell          | Latitude 5520               | [cbc2c03fa1](https://bsd-hardware.info/?probe=cbc2c03fa1) | May 20, 2022 |
| Dell          | XPS 13 9343                 | [44abecc1ef](https://bsd-hardware.info/?probe=44abecc1ef) | May 20, 2022 |
| ASUSTek       | 1001P                       | [6ffa9529a3](https://bsd-hardware.info/?probe=6ffa9529a3) | May 20, 2022 |
| TUXEDO        | Aura 15 Gen1                | [a4b6a40758](https://bsd-hardware.info/?probe=a4b6a40758) | May 19, 2022 |
| TUXEDO        | Aura 15 Gen1                | [1c84f0f722](https://bsd-hardware.info/?probe=1c84f0f722) | May 19, 2022 |
| Lenovo        | ThinkPad L420 7854CTO       | [56cf502c2f](https://bsd-hardware.info/?probe=56cf502c2f) | May 18, 2022 |
| Lenovo        | ThinkPad T420s 41732AU      | [9d9ddcc409](https://bsd-hardware.info/?probe=9d9ddcc409) | May 18, 2022 |
| Lenovo        | ThinkPad X270 20HMCTO1WW    | [2d3de77101](https://bsd-hardware.info/?probe=2d3de77101) | May 18, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [86866ce217](https://bsd-hardware.info/?probe=86866ce217) | May 17, 2022 |
| TUXEDO        | InfinityBook13V3            | [fd081a3636](https://bsd-hardware.info/?probe=fd081a3636) | May 17, 2022 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 71        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| KDE5       | 16        | 22.54%  |
| XFCE       | 13        | 18.31%  |
| GNOME      | 11        | 15.49%  |
| Console    | 9         | 12.68%  |
| TWM        | 4         | 5.63%   |
| Openbox    | 4         | 5.63%   |
| i3         | 4         | 5.63%   |
| MATE       | 3         | 4.23%   |
| Cinnamon   | 2         | 2.82%   |
| X-Cinnamon | 1         | 1.41%   |
| LXQt       | 1         | 1.41%   |
| LXDE       | 1         | 1.41%   |
| IceWM      | 1         | 1.41%   |
| dwm        | 1         | 1.41%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 58        | 81.69%  |
| Console | 10        | 14.08%  |
| Wayland | 3         | 4.23%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 25        | 35.21%  |
| SDDM    | 17        | 23.94%  |
| SLiM    | 12        | 16.9%   |
| GDM     | 7         | 9.86%   |
| XDM     | 5         | 7.04%   |
| LightDM | 4         | 5.63%   |
| PCDM    | 1         | 1.41%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| C               | 49        | 68.06%  |
| en_US           | 10        | 13.89%  |
| zh_CN           | 4         | 5.56%   |
| ru_RU           | 3         | 4.17%   |
| Unknown         | 3         | 4.17%   |
| fr_FR           | 1         | 1.39%   |
| en_US.ISO8859-1 | 1         | 1.39%   |
| en_AU           | 1         | 1.39%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 58        | 81.69%  |
| BIOS | 13        | 18.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Zfs  | 50        | 69.44%  |
| Ufs  | 22        | 30.56%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 64        | 90.14%  |
| MBR     | 5         | 7.04%   |
| BSD     | 1         | 1.41%   |
| Unknown | 1         | 1.41%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 19        | 26.76%  |
| Dell                | 18        | 25.35%  |
| ASUSTek Computer    | 9         | 12.68%  |
| Hewlett-Packard     | 4         | 5.63%   |
| TUXEDO              | 2         | 2.82%   |
| Toshiba             | 2         | 2.82%   |
| System76            | 2         | 2.82%   |
| Google              | 2         | 2.82%   |
| Acer                | 2         | 2.82%   |
| Unknown             | 2         | 2.82%   |
| Sony                | 1         | 1.41%   |
| Samsung Electronics | 1         | 1.41%   |
| Notebook            | 1         | 1.41%   |
| MSI                 | 1         | 1.41%   |
| LG Electronics      | 1         | 1.41%   |
| GPD                 | 1         | 1.41%   |
| Fujitsu Siemens     | 1         | 1.41%   |
| Fujitsu             | 1         | 1.41%   |
| Apple               | 1         | 1.41%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| HP EliteBook 850 G7 Notebook PC             | 2         | 2.82%   |
| Google Peppy                                | 2         | 2.82%   |
| Unknown                                     | 2         | 2.82%   |
| TUXEDO InfinityBook13V3                     | 1         | 1.41%   |
| TUXEDO Aura 15 Gen1                         | 1         | 1.41%   |
| Toshiba Satellite L305D                     | 1         | 1.41%   |
| Toshiba Satellite A300                      | 1         | 1.41%   |
| System76 Gazelle                            | 1         | 1.41%   |
| System76 Galago Pro                         | 1         | 1.41%   |
| Sony VGN-NS21M_S                            | 1         | 1.41%   |
| Samsung R530/R730/R540                      | 1         | 1.41%   |
| Notebook N7x0WU                             | 1         | 1.41%   |
| MSI GF63 Thin 9SC                           | 1         | 1.41%   |
| LG 17Z990-R.AAC9U1                          | 1         | 1.41%   |
| Lenovo ThinkPad X270 20HMCTO1WW             | 1         | 1.41%   |
| Lenovo ThinkPad X260 20F6S0KA00             | 1         | 1.41%   |
| Lenovo ThinkPad X250 20CMS0FA00             | 1         | 1.41%   |
| Lenovo ThinkPad X220 4286CTO                | 1         | 1.41%   |
| Lenovo ThinkPad X13 Gen 1 20UF000QRT        | 1         | 1.41%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TKS0QB00 | 1         | 1.41%   |
| Lenovo ThinkPad W520 4282AD4                | 1         | 1.41%   |
| Lenovo ThinkPad T480 20L6SB2N00             | 1         | 1.41%   |
| Lenovo ThinkPad T480 20L6S29E0T             | 1         | 1.41%   |
| Lenovo ThinkPad T420s 41732AU               | 1         | 1.41%   |
| Lenovo ThinkPad T420 4236C92                | 1         | 1.41%   |
| Lenovo ThinkPad T14 Gen 1 20S0CTO1WW        | 1         | 1.41%   |
| Lenovo ThinkPad L420 7854CTO                | 1         | 1.41%   |
| Lenovo ThinkPad L420 7829WDY                | 1         | 1.41%   |
| Lenovo ThinkPad E490 20N8CTO1WW             | 1         | 1.41%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5            | 1         | 1.41%   |
| Lenovo IdeaPad 330-15ARR 81D2               | 1         | 1.41%   |
| Lenovo IdeaPad 130-15AST 81H5               | 1         | 1.41%   |
| Lenovo G40-45 80E1                          | 1         | 1.41%   |
| HP Pavilion g6                              | 1         | 1.41%   |
| HP Laptop 15s-fq1xxx                        | 1         | 1.41%   |
| GPD MicroPC                                 | 1         | 1.41%   |
| Fujitsu Siemens AMILO Li3710                | 1         | 1.41%   |
| Fujitsu LIFEBOOK A555                       | 1         | 1.41%   |
| Dell XPS 13 9343                            | 1         | 1.41%   |
| Dell Vostro 5415                            | 1         | 1.41%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 15        | 21.13%  |
| Dell Latitude           | 9         | 12.68%  |
| Lenovo IdeaPad          | 3         | 4.23%   |
| Dell Inspiron           | 3         | 4.23%   |
| ASUS ZenBook            | 3         | 4.23%   |
| ASUS VivoBook           | 3         | 4.23%   |
| Toshiba Satellite       | 2         | 2.82%   |
| HP EliteBook            | 2         | 2.82%   |
| Google Peppy            | 2         | 2.82%   |
| Dell Precision          | 2         | 2.82%   |
| Unknown                 | 2         | 2.82%   |
| TUXEDO InfinityBook13V3 | 1         | 1.41%   |
| TUXEDO Aura             | 1         | 1.41%   |
| System76 Gazelle        | 1         | 1.41%   |
| System76 Galago         | 1         | 1.41%   |
| Sony VGN-NS21M          | 1         | 1.41%   |
| Samsung R530            | 1         | 1.41%   |
| Notebook N7x0WU         | 1         | 1.41%   |
| MSI GF63                | 1         | 1.41%   |
| LG 17Z990-R.AAC9U1      | 1         | 1.41%   |
| Lenovo G40-45           | 1         | 1.41%   |
| HP Pavilion             | 1         | 1.41%   |
| HP Laptop               | 1         | 1.41%   |
| GPD MicroPC             | 1         | 1.41%   |
| Fujitsu Siemens AMILO   | 1         | 1.41%   |
| Fujitsu LIFEBOOK        | 1         | 1.41%   |
| Dell XPS                | 1         | 1.41%   |
| Dell Vostro             | 1         | 1.41%   |
| Dell Studio             | 1         | 1.41%   |
| Dell G5                 | 1         | 1.41%   |
| ASUS X455LJ             | 1         | 1.41%   |
| ASUS X441UV             | 1         | 1.41%   |
| ASUS 1001P              | 1         | 1.41%   |
| Apple MacBookPro11      | 1         | 1.41%   |
| Acer Nitro              | 1         | 1.41%   |
| Acer Aspire             | 1         | 1.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 10        | 14.08%  |
| 2020 | 10        | 14.08%  |
| 2022 | 8         | 11.27%  |
| 2018 | 8         | 11.27%  |
| 2019 | 6         | 8.45%   |
| 2011 | 6         | 8.45%   |
| 2016 | 5         | 7.04%   |
| 2012 | 4         | 5.63%   |
| 2015 | 3         | 4.23%   |
| 2017 | 2         | 2.82%   |
| 2013 | 2         | 2.82%   |
| 2010 | 2         | 2.82%   |
| 2009 | 2         | 2.82%   |
| 2008 | 2         | 2.82%   |
| 2014 | 1         | 1.41%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 71        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 68        | 95.77%  |
| Yes  | 3         | 4.23%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 26        | 36.62%  |
| 8.01-16.0   | 22        | 30.99%  |
| 4.01-8.0    | 12        | 16.9%   |
| 32.01-64.0  | 4         | 5.63%   |
| 64.01-256.0 | 3         | 4.23%   |
| 24.01-32.0  | 2         | 2.82%   |
| 2.01-3.0    | 2         | 2.82%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 28        | 39.44%  |
| 0.51-1.0  | 22        | 30.99%  |
| 1.01-2.0  | 14        | 19.72%  |
| 2.01-3.0  | 6         | 8.45%   |
| 8.01-16.0 | 1         | 1.41%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 50        | 70.42%  |
| 2      | 17        | 23.94%  |
| 0      | 3         | 4.23%   |
| 3      | 1         | 1.41%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 52        | 73.24%  |
| Yes       | 19        | 26.76%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 74.65%  |
| No        | 18        | 25.35%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 70        | 98.59%  |
| No        | 1         | 1.41%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 49        | 69.01%  |
| No        | 22        | 30.99%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 17        | 23.61%  |
| Russia      | 8         | 11.11%  |
| China       | 5         | 6.94%   |
| India       | 4         | 5.56%   |
| UK          | 3         | 4.17%   |
| Japan       | 3         | 4.17%   |
| France      | 3         | 4.17%   |
| Austria     | 3         | 4.17%   |
| Turkey      | 2         | 2.78%   |
| Thailand    | 2         | 2.78%   |
| Spain       | 2         | 2.78%   |
| Philippines | 2         | 2.78%   |
| Netherlands | 2         | 2.78%   |
| Germany     | 2         | 2.78%   |
| Czechia     | 2         | 2.78%   |
| Uruguay     | 1         | 1.39%   |
| South Korea | 1         | 1.39%   |
| Slovenia    | 1         | 1.39%   |
| Norway      | 1         | 1.39%   |
| Malaysia    | 1         | 1.39%   |
| Italy       | 1         | 1.39%   |
| Israel      | 1         | 1.39%   |
| Hong Kong   | 1         | 1.39%   |
| Guadeloupe  | 1         | 1.39%   |
| Greece      | 1         | 1.39%   |
| Canada      | 1         | 1.39%   |
| Australia   | 1         | 1.39%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 4         | 5.56%   |
| Vienna            | 3         | 4.17%   |
| Paris             | 2         | 2.78%   |
| Brno              | 2         | 2.78%   |
| Zhumadian         | 1         | 1.39%   |
| Yangcheon-gu      | 1         | 1.39%   |
| Xiamen            | 1         | 1.39%   |
| Xi'an             | 1         | 1.39%   |
| Woerdense Verlaat | 1         | 1.39%   |
| Wheatland         | 1         | 1.39%   |
| Trivandrum        | 1         | 1.39%   |
| Thousand Oaks     | 1         | 1.39%   |
| Thessaloniki      | 1         | 1.39%   |
| Tel Aviv          | 1         | 1.39%   |
| Taito             | 1         | 1.39%   |
| Stratford         | 1         | 1.39%   |
| St Petersburg     | 1         | 1.39%   |
| Shinjuku          | 1         | 1.39%   |
| Shah Alam         | 1         | 1.39%   |
| Sandefjord        | 1         | 1.39%   |
| San Pablo City    | 1         | 1.39%   |
| San Antonio       | 1         | 1.39%   |
| Riverside         | 1         | 1.39%   |
| Qinnan            | 1         | 1.39%   |
| Ozersk            | 1         | 1.39%   |
| Oswego            | 1         | 1.39%   |
| Omaha             | 1         | 1.39%   |
| Newbury Park      | 1         | 1.39%   |
| New York          | 1         | 1.39%   |
| Nakano            | 1         | 1.39%   |
| Munich            | 1         | 1.39%   |
| Mumbai            | 1         | 1.39%   |
| Montevideo        | 1         | 1.39%   |
| Manassas          | 1         | 1.39%   |
| Madrid            | 1         | 1.39%   |
| Lübeck           | 1         | 1.39%   |
| London            | 1         | 1.39%   |
| Legazpi           | 1         | 1.39%   |
| Le Gosier         | 1         | 1.39%   |
| Krasnodar         | 1         | 1.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 16        | 18     | 19.05%  |
| Samsung Electronics | 16        | 17     | 19.05%  |
| Crucial             | 7         | 9      | 8.33%   |
| Seagate             | 6         | 7      | 7.14%   |
| Toshiba             | 5         | 5      | 5.95%   |
| Kingston            | 5         | 5      | 5.95%   |
| SK hynix            | 4         | 4      | 4.76%   |
| Hitachi             | 3         | 3      | 3.57%   |
| Transcend           | 2         | 2      | 2.38%   |
| Silicon Motion      | 2         | 2      | 2.38%   |
| SanDisk             | 2         | 2      | 2.38%   |
| KIOXIA              | 2         | 2      | 2.38%   |
| Gigabyte Technology | 2         | 2      | 2.38%   |
| A-DATA Technology   | 2         | 5      | 2.38%   |
| Micron Technology   | 1         | 1      | 1.19%   |
| Lexar               | 1         | 2      | 1.19%   |
| Lenovo              | 1         | 1      | 1.19%   |
| Hikvision           | 1         | 1      | 1.19%   |
| Hewlett-Packard     | 1         | 1      | 1.19%   |
| EAGET               | 1         | 1      | 1.19%   |
| CFD                 | 1         | 1      | 1.19%   |
| BR                  | 1         | 1      | 1.19%   |
| BIWIN               | 1         | 1      | 1.19%   |
| Apple               | 1         | 1      | 1.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| SK hynix BC511 HFM512GDJTNI-82A0A 512GB         | 2         | 2.27%   |
| Samsung SSD 970 EVO Plus 2TB                    | 2         | 2.27%   |
| Crucial CT1000MX500SSD1 1TB                     | 2         | 2.27%   |
| WDC WDS500G3X0C-00SJG0 500GB                    | 1         | 1.14%   |
| WDC WDS480G2G0A-00JH30 480GB                    | 1         | 1.14%   |
| WDC WDS250G2B0B-00YS70 250GB                    | 1         | 1.14%   |
| WDC WDS120G2G0B-00EPW0 120GB                    | 1         | 1.14%   |
| WDC WD3200BPVT-22JJ5T0 320GB                    | 1         | 1.14%   |
| WDC WD3200BEKT-60PVMT0 320GB                    | 1         | 1.14%   |
| WDC WD2500BEVT-24A23T0 250GB                    | 1         | 1.14%   |
| WDC WD20SPZX-00UA7T0 2TB                        | 1         | 1.14%   |
| WDC WD1600BEVT-80A23T0 160GB                    | 1         | 1.14%   |
| WDC WD1600BEVT-75ZCT2 160GB                     | 1         | 1.14%   |
| WDC WD1600BEVT-22ZCT0 160GB                     | 1         | 1.14%   |
| WDC WD10SPZX-75Z10T3 1TB                        | 1         | 1.14%   |
| WDC WD10SPZX-17Z10T1 1TB                        | 1         | 1.14%   |
| WDC WD10JPVX-22JC3T0 1TB                        | 1         | 1.14%   |
| WDC WD10EZEX-60WN4A0 1TB                        | 1         | 1.14%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB              | 1         | 1.14%   |
| WDC PC SN530 SDBPNPZ-256G-1014 256GB            | 1         | 1.14%   |
| WDC PC SN530 NVMe 256GB                         | 1         | 1.14%   |
| Transcend TS1TMTE110S 1TB                       | 1         | 1.14%   |
| Transcend TS128GMTS430S 128GB                   | 1         | 1.14%   |
| Toshiba MQ04ABF100 1TB                          | 1         | 1.14%   |
| Toshiba MQ01ABF050 500GB                        | 1         | 1.14%   |
| Toshiba MQ01ABD100 1TB                          | 1         | 1.14%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB             | 1         | 1.14%   |
| Toshiba KBG30ZMT512G 512GB                      | 1         | 1.14%   |
| SK hynix HFM512GD3JX013N 512GB                  | 1         | 1.14%   |
| SK hynix BC501 NVMe 512GB                       | 1         | 1.14%   |
| Silicon Motion Asgard AN2+ 256NVMe-M.2-80 256GB | 1         | 1.14%   |
| Silicon Motion 512GB MEGA S3 512GB              | 1         | 1.14%   |
| Seagate ST500LT012-1DG142 500GB                 | 1         | 1.14%   |
| Seagate ST500LM012 HN-M500MBB 500GB             | 1         | 1.14%   |
| Seagate ST2000LM007-1R8174 2TB                  | 1         | 1.14%   |
| Seagate ST1000LM049-2GH172 1TB                  | 1         | 1.14%   |
| Seagate ST1000LM035-1RK172 1TB                  | 1         | 1.14%   |
| Seagate ST1000LM024 HN-M101MBB 1TB              | 1         | 1.14%   |
| SanDisk SSD PLUS 240GB                          | 1         | 1.14%   |
| SanDisk SDSSDH3 1T02 1TB                        | 1         | 1.14%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 10        | 11     | 45.45%  |
| Seagate | 6         | 7      | 27.27%  |
| Toshiba | 3         | 3      | 13.64%  |
| Hitachi | 3         | 3      | 13.64%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 6      | 18.18%  |
| Crucial             | 6         | 8      | 18.18%  |
| WDC                 | 3         | 3      | 9.09%   |
| Kingston            | 3         | 3      | 9.09%   |
| SanDisk             | 2         | 2      | 6.06%   |
| A-DATA Technology   | 2         | 5      | 6.06%   |
| Transcend           | 1         | 1      | 3.03%   |
| Toshiba             | 1         | 1      | 3.03%   |
| Lexar               | 1         | 2      | 3.03%   |
| Lenovo              | 1         | 1      | 3.03%   |
| Hikvision           | 1         | 1      | 3.03%   |
| Hewlett-Packard     | 1         | 1      | 3.03%   |
| Gigabyte Technology | 1         | 1      | 3.03%   |
| CFD                 | 1         | 1      | 3.03%   |
| BR                  | 1         | 1      | 3.03%   |
| BIWIN               | 1         | 1      | 3.03%   |
| Apple               | 1         | 1      | 3.03%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 29        | 31     | 36.71%  |
| SSD  | 29        | 39     | 36.71%  |
| HDD  | 21        | 24     | 26.58%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 47        | 63     | 61.84%  |
| NVMe | 29        | 31     | 38.16%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 31        | 40     | 62%     |
| 0.51-1.0   | 15        | 19     | 30%     |
| 1.01-2.0   | 4         | 4      | 8%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 26        | 36.62%  |
| 251-500    | 19        | 26.76%  |
| 501-1000   | 12        | 16.9%   |
| 51-100     | 6         | 8.45%   |
| 1001-2000  | 4         | 5.63%   |
| 21-50      | 3         | 4.23%   |
| 1-20       | 1         | 1.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 55        | 76.39%  |
| 21-50   | 12        | 16.67%  |
| 101-250 | 2         | 2.78%   |
| 51-100  | 2         | 2.78%   |
| 251-500 | 1         | 1.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD3200BEKT-60PVMT0 320GB                 | 1         | 1      | 8.33%   |
| WDC WD2500BEVT-24A23T0 250GB                 | 1         | 1      | 8.33%   |
| Toshiba MQ01ABF050 500GB                     | 1         | 1      | 8.33%   |
| Toshiba MQ01ABD100 1TB                       | 1         | 1      | 8.33%   |
| Seagate ST500LT012-1DG142 500GB              | 1         | 1      | 8.33%   |
| Seagate ST500LM012 HN-M500MBB 500GB          | 1         | 1      | 8.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 2      | 8.33%   |
| Samsung Electronics SSD PM810 2.5-inch 128GB | 1         | 1      | 8.33%   |
| Kingston SNS4151S316GD 16GB                  | 1         | 1      | 8.33%   |
| Hitachi HTS721080G9SA00 80GB                 | 1         | 1      | 8.33%   |
| Hitachi HTS543232L9SA00 320GB                | 1         | 1      | 8.33%   |
| A-DATA Technology SU630 240GB                | 1         | 2      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 4      | 27.27%  |
| Toshiba             | 2         | 2      | 18.18%  |
| Hitachi             | 2         | 2      | 18.18%  |
| WDC                 | 1         | 2      | 9.09%   |
| Samsung Electronics | 1         | 1      | 9.09%   |
| Kingston            | 1         | 1      | 9.09%   |
| A-DATA Technology   | 1         | 2      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 4      | 37.5%   |
| Toshiba | 2         | 2      | 25%     |
| Hitachi | 2         | 2      | 25%     |
| WDC     | 1         | 2      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 7         | 10     | 70%     |
| SSD  | 3         | 4      | 30%     |

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
| Works    | 58        | 77     | 82.86%  |
| Malfunc  | 10        | 14     | 14.29%  |
| Detected | 2         | 3      | 2.86%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 44        | 52.38%  |
| Samsung Electronics         | 11        | 13.1%   |
| AMD                         | 9         | 10.71%  |
| SanDisk                     | 4         | 4.76%   |
| SK hynix                    | 3         | 3.57%   |
| Silicon Motion              | 3         | 3.57%   |
| KIOXIA                      | 2         | 2.38%   |
| Kingston Technology Company | 2         | 2.38%   |
| Toshiba                     | 1         | 1.19%   |
| Phison Electronics          | 1         | 1.19%   |
| Nvidia                      | 1         | 1.19%   |
| Micron/Crucial Technology   | 1         | 1.19%   |
| Micron Technology           | 1         | 1.19%   |
| Unknown                     | 1         | 1.19%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 8         | 9.3%    |
| AMD FCH SATA Controller [AHCI mode]                                            | 8         | 9.3%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 6         | 6.98%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 6.98%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 6         | 6.98%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 4.65%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 4.65%   |
| Unknown                                                                        | 4         | 4.65%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 3         | 3.49%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 3.49%   |
| SK hynix BC511                                                                 | 2         | 2.33%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 2.33%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 2         | 2.33%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 2.33%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 2.33%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 2.33%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 2.33%   |
| Toshiba BG3 NVMe SSD Controller                                                | 1         | 1.16%   |
| SK hynix Gold P31 SSD                                                          | 1         | 1.16%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1         | 1.16%   |
| SanDisk unknown                                                                | 1         | 1.16%   |
| Samsung SM951 AHCI                                                             | 1         | 1.16%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1         | 1.16%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1         | 1.16%   |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 1.16%   |
| Kingston Company SNVS2000G [NV1 NVMe PCIe SSD 2TB]                             | 1         | 1.16%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 1.16%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 1         | 1.16%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 1.16%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 1.16%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.16%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 1         | 1.16%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 1         | 1.16%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.16%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 1.16%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 1.16%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 1         | 1.16%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 48        | 57.14%  |
| NVMe | 28        | 33.33%  |
| RAID | 6         | 7.14%   |
| IDE  | 2         | 2.38%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 59        | 83.1%   |
| AMD    | 12        | 16.9%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz      | 3         | 4.23%   |
| Intel Core i7-8565U CPU @ 1.80GHz      | 3         | 4.23%   |
| Intel Core i7-6500U CPU @ 2.50GHz      | 3         | 4.23%   |
| Intel Core i7-10510U CPU @ 1.80GHz     | 2         | 2.82%   |
| Intel Core i5-8350U CPU @ 1.70GHz      | 2         | 2.82%   |
| Intel Core i5-5200U CPU @ 2.20GHz      | 2         | 2.82%   |
| Intel Core i5-2520M CPU @ 2.50GHz      | 2         | 2.82%   |
| Intel Core i5-10310U CPU @ 1.70GHz     | 2         | 2.82%   |
| Intel Pentium Silver N6000 @ 1.10GHz   | 1         | 1.41%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz | 1         | 1.41%   |
| Intel Genuine CPU                      | 1         | 1.41%   |
| Intel Core i7-8550U CPU @ 1.80GHz      | 1         | 1.41%   |
| Intel Core i7-5600U CPU @ 2.60GHz      | 1         | 1.41%   |
| Intel Core i7-4980HQ CPU @ 2.80GHz     | 1         | 1.41%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz     | 1         | 1.41%   |
| Intel Core i7-4610M CPU @ 3.00GHz      | 1         | 1.41%   |
| Intel Core i7-4600U CPU @ 2.10GHz      | 1         | 1.41%   |
| Intel Core i7-3537U CPU @ 2.00GHz      | 1         | 1.41%   |
| Intel Core i7-2760QM CPU @ 2.40GHz     | 1         | 1.41%   |
| Intel Core i7-2640M CPU @ 2.80GHz      | 1         | 1.41%   |
| Intel Core i7-2620M CPU @ 2.70GHz      | 1         | 1.41%   |
| Intel Core i7-10750H CPU @ 2.60GHz     | 1         | 1.41%   |
| Intel Core i7-10610U CPU @ 1.80GHz     | 1         | 1.41%   |
| Intel Core i5-7300U CPU @ 2.60GHz      | 1         | 1.41%   |
| Intel Core i5-7200U CPU @ 2.50GHz      | 1         | 1.41%   |
| Intel Core i5-3320M CPU @ 2.60GHz      | 1         | 1.41%   |
| Intel Core i5-3230M CPU @ 2.60GHz      | 1         | 1.41%   |
| Intel Core i5-2540M CPU @ 2.60GHz      | 1         | 1.41%   |
| Intel Core i5-2540M CPU @ 2.60GH       | 1         | 1.41%   |
| Intel Core i5-2520M CPU @ 2.50GH       | 1         | 1.41%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz     | 1         | 1.41%   |
| Intel Core i5-10300H CPU @ 2.50GHz     | 1         | 1.41%   |
| Intel Core i3-8130U CPU @ 2.20GHz      | 1         | 1.41%   |
| Intel Core i3-7020U CPU @ 2.30GHz      | 1         | 1.41%   |
| Intel Core i3-6006U CPU @ 2.00GHz      | 1         | 1.41%   |
| Intel Core i3-5005U CPU @ 2.00GHz      | 1         | 1.41%   |
| Intel Core 2 Duo CPU T6400 @ 2.00GHz   | 1         | 1.41%   |
| Intel Core 2 Duo CPU T5800 @ 2.00GHz   | 1         | 1.41%   |
| Intel Core 2 Duo CPU P9500 @ 2.53GHz   | 1         | 1.41%   |
| Intel Core 2 Duo                       | 1         | 1.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i7        | 23        | 32.39%  |
| Intel Core i5        | 17        | 23.94%  |
| Intel Celeron        | 5         | 7.04%   |
| Intel Core i3        | 4         | 5.63%   |
| Intel Core 2 Duo     | 4         | 5.63%   |
| AMD Ryzen 7          | 3         | 4.23%   |
| AMD Ryzen 3          | 3         | 4.23%   |
| Other                | 2         | 2.82%   |
| AMD Ryzen 5          | 2         | 2.82%   |
| Intel Pentium Silver | 1         | 1.41%   |
| Intel Pentium Dual   | 1         | 1.41%   |
| Intel Genuine        | 1         | 1.41%   |
| Intel Atom           | 1         | 1.41%   |
| AMD Ryzen 7 PRO      | 1         | 1.41%   |
| AMD E2               | 1         | 1.41%   |
| AMD Athlon X2        | 1         | 1.41%   |
| AMD A8               | 1         | 1.41%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 33        | 46.48%  |
| 4       | 23        | 32.39%  |
| 8       | 5         | 7.04%   |
| 6       | 4         | 5.63%   |
| 16      | 3         | 4.23%   |
| Unknown | 2         | 2.82%   |
| 1       | 1         | 1.41%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 71        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 48        | 67.61%  |
| 1       | 21        | 29.58%  |
| Unknown | 2         | 2.82%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 18        | 25.35%  |
| SandyBridge     | 8         | 11.27%  |
| Haswell         | 6         | 8.45%   |
| Skylake         | 4         | 5.63%   |
| Broadwell       | 4         | 5.63%   |
| Unknown         | 4         | 5.63%   |
| IvyBridge       | 3         | 4.23%   |
| Core            | 3         | 4.23%   |
| Zen+            | 2         | 2.82%   |
| Zen 2           | 2         | 2.82%   |
| Zen             | 2         | 2.82%   |
| Penryn          | 2         | 2.82%   |
| Goldmont plus   | 2         | 2.82%   |
| CometLake       | 2         | 2.82%   |
| Zen 3           | 1         | 1.41%   |
| Westmere        | 1         | 1.41%   |
| TigerLake       | 1         | 1.41%   |
| Puma            | 1         | 1.41%   |
| K8 & K10 hybrid | 1         | 1.41%   |
| IceLake         | 1         | 1.41%   |
| Goldmont        | 1         | 1.41%   |
| Excavator       | 1         | 1.41%   |
| Bonnell         | 1         | 1.41%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 56        | 65.88%  |
| AMD    | 16        | 18.82%  |
| Nvidia | 13        | 15.29%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 8         | 9.2%    |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 5         | 5.75%   |
| Intel UHD Graphics 620                                                    | 4         | 4.6%    |
| Intel Skylake GT2 [HD Graphics 520]                                       | 4         | 4.6%    |
| Intel HD Graphics 5500                                                    | 4         | 4.6%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 3         | 3.45%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 3         | 3.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 3         | 3.45%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 3         | 3.45%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 2         | 2.3%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 2         | 2.3%    |
| Intel HD Graphics 620                                                     | 2         | 2.3%    |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 2.3%    |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 2         | 2.3%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 2         | 2.3%    |
| Intel 3rd Gen Core processor Graphics Controller                          | 2         | 2.3%    |
| AMD Renoir                                                                | 2         | 2.3%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 2.3%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 2         | 2.3%    |
| AMD Lucienne                                                              | 2         | 2.3%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 1.15%   |
| Nvidia TU117M                                                             | 1         | 1.15%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 1.15%   |
| Nvidia GM108M [GeForce MX130]                                             | 1         | 1.15%   |
| Nvidia GM108M [GeForce 920MX]                                             | 1         | 1.15%   |
| Nvidia GK208BM [GeForce 920M]                                             | 1         | 1.15%   |
| Nvidia GF108GLM [NVS 5200M]                                               | 1         | 1.15%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                        | 1         | 1.15%   |
| Nvidia G98M [GeForce 9200M GS]                                            | 1         | 1.15%   |
| Nvidia C79 [GeForce 9400M G]                                              | 1         | 1.15%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 1         | 1.15%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 1         | 1.15%   |
| Intel Kaby Lake-U GT2f HD 620 Graphics Controller                         | 1         | 1.15%   |
| Intel JasperLake [UHD Graphics]                                           | 1         | 1.15%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 1         | 1.15%   |
| Intel HD Graphics 500                                                     | 1         | 1.15%   |
| Intel Crystal Well Integrated Graphics Controller                         | 1         | 1.15%   |
| Intel Core Processor Integrated Graphics Controller                       | 1         | 1.15%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller   | 1         | 1.15%   |
| AMD Venus XT [Radeon HD 8870M / R9 M270X/M370X]                           | 1         | 1.15%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 40        | 56.34%  |
| 1 x AMD        | 10        | 14.08%  |
| Intel + Nvidia | 9         | 12.68%  |
| 2 x Intel      | 4         | 5.63%   |
| Intel + AMD    | 3         | 4.23%   |
| AMD + Nvidia   | 2         | 2.82%   |
| 2 x Nvidia     | 1         | 1.41%   |
| 2 x AMD        | 1         | 1.41%   |
| 1 x Nvidia     | 1         | 1.41%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 67        | 94.37%  |
| Proprietary | 4         | 5.63%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 61        | 85.92%  |
| 0.01-0.5   | 5         | 7.04%   |
| 1.01-2.0   | 2         | 2.82%   |
| 5.01-6.0   | 1         | 1.41%   |
| 3.01-4.0   | 1         | 1.41%   |
| 0.51-1.0   | 1         | 1.41%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 13        | 20.31%  |
| BOE                 | 11        | 17.19%  |
| AU Optronics        | 9         | 14.06%  |
| Chimei Innolux      | 8         | 12.5%   |
| Samsung Electronics | 7         | 10.94%  |
| BenQ                | 2         | 3.13%   |
| YTH                 | 1         | 1.56%   |
| ViewSonic           | 1         | 1.56%   |
| USR                 | 1         | 1.56%   |
| Unknown (XXX)       | 1         | 1.56%   |
| Toshiba             | 1         | 1.56%   |
| Sharp               | 1         | 1.56%   |
| Sceptre Tech        | 1         | 1.56%   |
| LG Philips          | 1         | 1.56%   |
| Lenovo              | 1         | 1.56%   |
| JDI                 | 1         | 1.56%   |
| HannStar            | 1         | 1.56%   |
| CSO                 | 1         | 1.56%   |
| Apple               | 1         | 1.56%   |
| Acer                | 1         | 1.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD064C 1920x1080 340x190mm 15.3-inch          | 2         | 3.13%   |
| BenQ BL2480 BNQ802C 1920x1080 530x300mm 24.0-inch                     | 2         | 3.13%   |
| YTH HS133PC YTH1330 1920x1080 250x220mm 13.1-inch                     | 1         | 1.56%   |
| ViewSonic LCD Monitor VSCD22B 1920x1080 520x290mm 23.4-inch           | 1         | 1.56%   |
| USR LCD Monitor USR0100 1920x1080 510x290mm 23.1-inch                 | 1         | 1.56%   |
| Unknown (XXX) SMART TV XXX2851 3840x2160                              | 1         | 1.56%   |
| Toshiba TV TSB0200 1360x768 530x300mm 24.0-inch                       | 1         | 1.56%   |
| Sharp LCD Monitor SHP1421 3200x1800 290x170mm 13.2-inch               | 1         | 1.56%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch        | 1         | 1.56%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch     | 1         | 1.56%   |
| Samsung Electronics LS24A40xU SAM71D1 1920x1080 530x300mm 24.0-inch   | 1         | 1.56%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 330x210mm 15.4-inch  | 1         | 1.56%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 330x210mm 15.4-inch  | 1         | 1.56%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 340x190mm 15.3-inch  | 1         | 1.56%   |
| Samsung Electronics LCD Monitor SDC8B4F 1920x1080 340x190mm 15.3-inch | 1         | 1.56%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 290x170mm 13.2-inch | 1         | 1.56%   |
| LG Philips LCD Monitor LPL0120 1280x800 330x210mm 15.4-inch           | 1         | 1.56%   |
| LG Display LCD Monitor LGD6E01 1366x768 340x190mm 15.3-inch           | 1         | 1.56%   |
| LG Display LCD Monitor LGD060A 1920x1080 290x170mm 13.2-inch          | 1         | 1.56%   |
| LG Display LCD Monitor LGD05F8 2560x1600 370x230mm 17.2-inch          | 1         | 1.56%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch          | 1         | 1.56%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch          | 1         | 1.56%   |
| LG Display LCD Monitor LGD0408 1920x1080 280x160mm 12.7-inch          | 1         | 1.56%   |
| LG Display LCD Monitor LGD03DD 1366x768 340x190mm 15.3-inch           | 1         | 1.56%   |
| LG Display LCD Monitor LGD0353 1366x768 350x190mm 15.7-inch           | 1         | 1.56%   |
| LG Display LCD Monitor LGD02EB 1366x768 310x170mm 13.9-inch           | 1         | 1.56%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x170mm 13.9-inch           | 1         | 1.56%   |
| LG Display LCD Monitor LGD02D3 1366x768 280x160mm 12.7-inch           | 1         | 1.56%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch              | 1         | 1.56%   |
| JDI LCD Monitor JDI385A 3840x2160 290x170mm 13.2-inch                 | 1         | 1.56%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch             | 1         | 1.56%   |
| CSO LCD Monitor CSO1400 3840x2160 310x170mm 13.9-inch                 | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 340x190mm 15.3-inch      | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch      | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 310x170mm 13.9-inch      | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch      | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 310x170mm 13.9-inch       | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN1343 1920x1080 280x160mm 12.7-inch      | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 280x160mm 12.7-inch      | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch       | 1         | 1.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 33        | 53.23%  |
| 1366x768 (WXGA)  | 14        | 22.58%  |
| 3840x2160 (4K)   | 4         | 6.45%   |
| 1600x900 (HD+)   | 2         | 3.23%   |
| 1280x800 (WXGA)  | 2         | 3.23%   |
| 3200x1800 (QHD+) | 1         | 1.61%   |
| 2880x1800        | 1         | 1.61%   |
| 2560x1600        | 1         | 1.61%   |
| 2560x1440 (QHD)  | 1         | 1.61%   |
| 2560x1080        | 1         | 1.61%   |
| 1360x768         | 1         | 1.61%   |
| 1024x600         | 1         | 1.61%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 25        | 39.06%  |
| 13      | 21        | 32.81%  |
| 12      | 5         | 7.81%   |
| 24      | 4         | 6.25%   |
| 27      | 2         | 3.13%   |
| 23      | 2         | 3.13%   |
| 29      | 1         | 1.56%   |
| 17      | 1         | 1.56%   |
| 11      | 1         | 1.56%   |
| 10      | 1         | 1.56%   |
| Unknown | 1         | 1.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 40        | 63.49%  |
| 201-300     | 12        | 19.05%  |
| 501-600     | 7         | 11.11%  |
| 601-700     | 2         | 3.17%   |
| 351-400     | 1         | 1.59%   |
| Unknown     | 1         | 1.59%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 49        | 87.5%   |
| 16/10 | 5         | 8.93%   |
| 21/9  | 1         | 1.79%   |
| 11/10 | 1         | 1.79%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 19        | 29.69%  |
| 81-90          | 16        | 25%     |
| 201-250        | 6         | 9.38%   |
| 101-110        | 6         | 9.38%   |
| 71-80          | 5         | 7.81%   |
| 61-70          | 5         | 7.81%   |
| 301-350        | 3         | 4.69%   |
| 51-60          | 1         | 1.56%   |
| 41-50          | 1         | 1.56%   |
| 131-140        | 1         | 1.56%   |
| Unknown        | 1         | 1.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 26        | 41.94%  |
| 101-120       | 12        | 19.35%  |
| 51-100        | 11        | 17.74%  |
| 161-240       | 9         | 14.52%  |
| More than 240 | 3         | 4.84%   |
| Unknown       | 1         | 1.61%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 47        | 66.2%   |
| 0     | 15        | 21.13%  |
| 2     | 9         | 12.68%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 45        | 37.82%  |
| Realtek Semiconductor    | 34        | 28.57%  |
| Qualcomm Atheros         | 18        | 15.13%  |
| Broadcom                 | 6         | 5.04%   |
| Xiaomi                   | 2         | 1.68%   |
| Samsung Electronics      | 2         | 1.68%   |
| Ralink Technology        | 2         | 1.68%   |
| Marvell Technology Group | 2         | 1.68%   |
| TP-Link                  | 1         | 0.84%   |
| Qualcomm                 | 1         | 0.84%   |
| Nvidia                   | 1         | 0.84%   |
| MediaTek                 | 1         | 0.84%   |
| Huawei Technologies      | 1         | 0.84%   |
| HMD Global               | 1         | 0.84%   |
| Google                   | 1         | 0.84%   |
| Arduino SA               | 1         | 0.84%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 17        | 12.32%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 10        | 7.25%   |
| Intel Wireless 8265 / 8275                                              | 7         | 5.07%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 6         | 4.35%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 3.62%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 2.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 2.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 2.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 2.17%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 3         | 2.17%   |
| Intel Wireless 7265                                                     | 3         | 2.17%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 2         | 1.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 1.45%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 1.45%   |
| Intel Wireless-AC 9260                                                  | 2         | 1.45%   |
| Intel Wireless 8260                                                     | 2         | 1.45%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 1.45%   |
| Intel Ethernet Connection I217-LM                                       | 2         | 1.45%   |
| Intel Ethernet Connection (4) I219-LM                                   | 2         | 1.45%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.45%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 1.45%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 1.45%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 0.72%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                    | 1         | 0.72%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 1         | 0.72%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1         | 0.72%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.72%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.72%   |
| Realtek Realtek Bluetooth Adapter                                       | 1         | 0.72%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                        | 1         | 0.72%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                        | 1         | 0.72%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.72%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.72%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 0.72%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.72%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 0.72%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 1         | 0.72%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.72%   |
| Qualcomm Atheros AR2427 802.11bg Wireless Network Adapter (PCI-Express) | 1         | 0.72%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 41        | 53.95%  |
| Qualcomm Atheros      | 18        | 23.68%  |
| Realtek Semiconductor | 8         | 10.53%  |
| Broadcom              | 5         | 6.58%   |
| Ralink Technology     | 2         | 2.63%   |
| TP-Link               | 1         | 1.32%   |
| MediaTek              | 1         | 1.32%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 7         | 9.21%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 6.58%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 5.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 5.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 3.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 3.95%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 3         | 3.95%   |
| Intel Wireless 7265                                                     | 3         | 3.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 2.63%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 2.63%   |
| Intel Wireless-AC 9260                                                  | 2         | 2.63%   |
| Intel Wireless 8260                                                     | 2         | 2.63%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 2.63%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 2.63%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 2.63%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 2.63%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 2.63%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 1         | 1.32%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1         | 1.32%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 1.32%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.32%   |
| Realtek Realtek Bluetooth Adapter                                       | 1         | 1.32%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 1.32%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 1.32%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 1.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.32%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 1.32%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.32%   |
| Qualcomm Atheros AR2427 802.11bg Wireless Network Adapter (PCI-Express) | 1         | 1.32%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 1.32%   |
| Intel Wireless 7260                                                     | 1         | 1.32%   |
| Intel Wireless 3160                                                     | 1         | 1.32%   |
| Intel WiFi Link 5100                                                    | 1         | 1.32%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 1         | 1.32%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 1.32%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1         | 1.32%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 1.32%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 1.32%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 1.32%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 1.32%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 29        | 48.33%  |
| Intel                    | 18        | 30%     |
| Xiaomi                   | 2         | 3.33%   |
| Samsung Electronics      | 2         | 3.33%   |
| Marvell Technology Group | 2         | 3.33%   |
| Broadcom                 | 2         | 3.33%   |
| Qualcomm Atheros         | 1         | 1.67%   |
| Qualcomm                 | 1         | 1.67%   |
| Nvidia                   | 1         | 1.67%   |
| HMD Global               | 1         | 1.67%   |
| Google                   | 1         | 1.67%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 17        | 28.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 16.67%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 10%     |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 3.33%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 3.33%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 3.33%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.67%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 1.67%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.67%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 1.67%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.67%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 1         | 1.67%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.67%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 1.67%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.67%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.67%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.67%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.67%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.67%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.67%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.67%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.67%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 1.67%   |
| HMD Global Nokia 5.3 RNDIS Control RNDIS Ethernet Data            | 1         | 1.67%   |
| Google Nexus/Pixel Device (tether+ debug)                         | 1         | 1.67%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                 | 1         | 1.67%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 1.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 70        | 56%     |
| Ethernet | 53        | 42.4%   |
| Modem    | 2         | 1.6%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 39        | 61.9%   |
| Ethernet | 24        | 38.1%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 52        | 73.24%  |
| 1     | 18        | 25.35%  |
| 0     | 1         | 1.41%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 60        | 83.33%  |
| Yes  | 12        | 16.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 29        | 58%     |
| Qualcomm Atheros Communications | 4         | 8%      |
| Dell                            | 4         | 8%      |
| IMC Networks                    | 3         | 6%      |
| Foxconn / Hon Hai               | 3         | 6%      |
| Realtek Semiconductor           | 2         | 4%      |
| Broadcom                        | 2         | 4%      |
| Lite-On Technology              | 1         | 2%      |
| Cambridge Silicon Radio         | 1         | 2%      |
| Apple                           | 1         | 2%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 10        | 20%     |
| Intel AX201 Bluetooth                                       | 9         | 18%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 6         | 12%     |
| Realtek  Bluetooth Adapter                                  | 2         | 4%      |
| Intel AX200 Bluetooth                                       | 2         | 4%      |
| Foxconn / Hon Hai Bluetooth USB Module                      | 2         | 4%      |
| Dell DW375 Bluetooth Module                                 | 2         | 4%      |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 4%      |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 2%      |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 2%      |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 2%      |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 2%      |
| Lite-On BCM43142A0 Bluetooth Module                         | 1         | 2%      |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 2%      |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 2%      |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 2%      |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 1         | 2%      |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 2%      |
| Foxconn / Hon Hai Wireless_Device                           | 1         | 2%      |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 1         | 2%      |
| Dell Broadcom BCM20702A0 Bluetooth                          | 1         | 2%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 1         | 2%      |
| Apple Bluetooth Host Controller                             | 1         | 2%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel           | 58        | 69.88%  |
| AMD             | 14        | 16.87%  |
| Nvidia          | 6         | 7.23%   |
| Plantronics     | 2         | 2.41%   |
| SteelSeries ApS | 1         | 1.2%    |
| Sony            | 1         | 1.2%    |
| Lenovo          | 1         | 1.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 11        | 10.68%  |
| AMD Family 17h/19h HD Audio Controller                                     | 9         | 8.74%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 8         | 7.77%   |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 4.85%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 5         | 4.85%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 3.88%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 3.88%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 3.88%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 2.91%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 2.91%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 2.91%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 2.91%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 2.91%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 2.91%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 2.91%   |
| Plantronics Plantronics Blackwire 315.1                                    | 2         | 1.94%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 1.94%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 1.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 1.94%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.94%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.94%   |
| SteelSeries ApS SteelSeries Siberia 350                                    | 1         | 0.97%   |
| Sony UAB-80                                                                | 1         | 0.97%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.97%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.97%   |
| Lenovo Realtek USB Audio                                                   | 1         | 0.97%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 0.97%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 0.97%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 0.97%   |
| Intel Jasper Lake HD Audio                                                 | 1         | 0.97%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 0.97%   |
| Intel Crystal Well HD Audio Controller                                     | 1         | 0.97%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 0.97%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 0.97%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 0.97%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 1         | 0.97%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1         | 0.97%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 0.97%   |
| AMD High Definition Audio Controller                                       | 1         | 0.97%   |
| AMD FCH Azalia Controller                                                  | 1         | 0.97%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| SK hynix              | 28        | 32.94%  |
| Samsung Electronics   | 19        | 22.35%  |
| Kingston              | 6         | 7.06%   |
| Crucial               | 5         | 5.88%   |
| Unknown               | 5         | 5.88%   |
| Micron Technology     | 4         | 4.71%   |
| Unknown               | 3         | 3.53%   |
| Elpida                | 3         | 3.53%   |
| Unknown (ABCD)        | 2         | 2.35%   |
| KomputerBay           | 2         | 2.35%   |
| Transcend             | 1         | 1.18%   |
| Ramaxel Technology    | 1         | 1.18%   |
| PNY                   | 1         | 1.18%   |
| Nanya Technology      | 1         | 1.18%   |
| Kingmax Semiconductor | 1         | 1.18%   |
| Corsair               | 1         | 1.18%   |
| Apacer                | 1         | 1.18%   |
| A-DATA Technology     | 1         | 1.18%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                   | 5         | 5.49%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 3         | 3.3%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 2         | 2.2%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2133MT/s          | 2         | 2.2%    |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                             | 2         | 2.2%    |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s                     | 2         | 2.2%    |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s                    | 2         | 2.2%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s                    | 2         | 2.2%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s                    | 2         | 2.2%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s                    | 2         | 2.2%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 2         | 2.2%    |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s                    | 2         | 2.2%    |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s                    | 2         | 2.2%    |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s                    | 2         | 2.2%    |
| KomputerBay RAM KB_8G_D3_1333_C9 8GB SODIMM DDR3 1334MT/s                 | 2         | 2.2%    |
| Unknown RAM Module 2GB SODIMM DDR2                                        | 1         | 1.1%    |
| Transcend RAM TS2GSH64V1B 16GB SODIMM DDR4 2133MT/s                       | 1         | 1.1%    |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                              | 1         | 1.1%    |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 1.1%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 1.1%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 1         | 1.1%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 1         | 1.1%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s                    | 1         | 1.1%    |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s                   | 1         | 1.1%    |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s                   | 1         | 1.1%    |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s                   | 1         | 1.1%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 1         | 1.1%    |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s                    | 1         | 1.1%    |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s                | 1         | 1.1%    |
| SK hynix RAM 161616161616161616161616161616161616 2GB SODIMM DDR2 800MT/s | 1         | 1.1%    |
| SK hynix RAM 080808080808080808080808080808080808 2GB SODIMM DDR2 800MT/s | 1         | 1.1%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s                     | 1         | 1.1%    |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s                     | 1         | 1.1%    |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 1067MT/s                     | 1         | 1.1%    |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 1.1%    |
| Samsung RAM M471B5273CH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 1.1%    |
| Samsung RAM M471A5244BB0-CWE 4GB SODIMM DDR4 3200MT/s                     | 1         | 1.1%    |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s                    | 1         | 1.1%    |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s                    | 1         | 1.1%    |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s                    | 1         | 1.1%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 35        | 49.3%   |
| DDR3    | 25        | 35.21%  |
| DDR2    | 6         | 8.45%   |
| LPDDR4  | 3         | 4.23%   |
| LPDDR3  | 1         | 1.41%   |
| Unknown | 1         | 1.41%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 68        | 95.77%  |
| Row Of Chips | 2         | 2.82%   |
| Chip         | 1         | 1.41%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 29        | 39.73%  |
| 4096  | 17        | 23.29%  |
| 16384 | 12        | 16.44%  |
| 2048  | 11        | 15.07%  |
| 32768 | 4         | 5.48%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 17        | 22.08%  |
| 1600    | 14        | 18.18%  |
| 2400    | 11        | 14.29%  |
| 2667    | 8         | 10.39%  |
| 2133    | 7         | 9.09%   |
| 1334    | 5         | 6.49%   |
| 667     | 3         | 3.9%    |
| 1333    | 2         | 2.6%    |
| 975     | 2         | 2.6%    |
| 800     | 2         | 2.6%    |
| 4266    | 1         | 1.3%    |
| 2666    | 1         | 1.3%    |
| 1866    | 1         | 1.3%    |
| 1067    | 1         | 1.3%    |
| 1066    | 1         | 1.3%    |
| Unknown | 1         | 1.3%    |

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


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 16        | 30.77%  |
| IMC Networks                  | 9         | 17.31%  |
| Microdia                      | 6         | 11.54%  |
| Sunplus Innovation Technology | 5         | 9.62%   |
| Acer                          | 5         | 9.62%   |
| Realtek Semiconductor         | 3         | 5.77%   |
| Sonix Technology              | 1         | 1.92%   |
| Ricoh                         | 1         | 1.92%   |
| Quanta                        | 1         | 1.92%   |
| Logitech                      | 1         | 1.92%   |
| Intel                         | 1         | 1.92%   |
| Genesys Logic                 | 1         | 1.92%   |
| DigiTech                      | 1         | 1.92%   |
| Alcor Micro                   | 1         | 1.92%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD            | 4         | 7.55%   |
| Chicony Integrated Camera                | 4         | 7.55%   |
| Acer Integrated Camera                   | 4         | 7.55%   |
| IMC Networks EasyCamera                  | 3         | 5.66%   |
| Sunplus Laptop_Integrated_Webcam_FHD     | 2         | 3.77%   |
| Realtek Integrated_Webcam_HD             | 2         | 3.77%   |
| Microdia Integrated Webcam               | 2         | 3.77%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 2         | 3.77%   |
| IMC Networks USB2.0 HD UVC WebCam        | 2         | 3.77%   |
| Chicony USB2.0 VGA UVC WebCam            | 2         | 3.77%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 2         | 3.77%   |
| Chicony HP HD Camera                     | 2         | 3.77%   |
| Sunplus Laptop Integrated Webcam HD      | 1         | 1.89%   |
| Sunplus Integrated_Webcam_HD             | 1         | 1.89%   |
| Sunplus HD WebCam                        | 1         | 1.89%   |
| Sonix USB2.0 HD UVC WebCam               | 1         | 1.89%   |
| Ricoh Integrated Webcam                  | 1         | 1.89%   |
| Realtek Integrated Webcam HD             | 1         | 1.89%   |
| Quanta VGA WebCam                        | 1         | 1.89%   |
| Logitech HD Pro Webcam C920              | 1         | 1.89%   |
| Intel RealSense 3D Camera (Front F200)   | 1         | 1.89%   |
| IMC Networks Integrated Webcam           | 1         | 1.89%   |
| IMC Networks HP TrueVision HD Camera     | 1         | 1.89%   |
| Genesys Logic Camera                     | 1         | 1.89%   |
| DigiTech WebCam SCB-0350M                | 1         | 1.89%   |
| Chicony USB2.0 HD UVC WebCam             | 1         | 1.89%   |
| Chicony USB 2.0 Camera                   | 1         | 1.89%   |
| Chicony LG Camera                        | 1         | 1.89%   |
| Chicony HD WebCam                        | 1         | 1.89%   |
| Chicony Chicony USB2.0 Camera            | 1         | 1.89%   |
| Chicony Camera                           | 1         | 1.89%   |
| Alcor Micro USB 2.0 Camera               | 1         | 1.89%   |
| Acer ThinkPad P50 Integrated Camera      | 1         | 1.89%   |
| Acer SunplusIT Integrated Camera         | 1         | 1.89%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 4         | 57.14%  |
| Validity Sensors           | 2         | 28.57%  |
| Shenzhen Goodix Technology | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 28.57%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 2         | 28.57%  |
| Validity Sensors VFS 5011 fingerprint sensor              | 1         | 14.29%  |
| Validity Sensors Synaptics WBDI                           | 1         | 14.29%  |
| Shenzhen Goodix Fingerprint Reader                        | 1         | 14.29%  |

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
| 1     | 26        | 36.62%  |
| 2     | 24        | 33.8%   |
| 3     | 12        | 16.9%   |
| 4     | 4         | 5.63%   |
| 0     | 4         | 5.63%   |
| 5     | 1         | 1.41%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 52        | 43.7%   |
| Bluetooth                | 26        | 21.85%  |
| Net/wireless             | 13        | 10.92%  |
| Card reader              | 9         | 7.56%   |
| Firewire controller      | 7         | 5.88%   |
| Fingerprint reader       | 6         | 5.04%   |
| Storage                  | 2         | 1.68%   |
| Net/ethernet             | 2         | 1.68%   |
| Sound                    | 1         | 0.84%   |
| Network                  | 1         | 0.84%   |

