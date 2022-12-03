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

Total: 105

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| ASUSTek       | ZenBook UX434FL_UX434FL     | [56bc3b04fd](https://bsd-hardware.info/?probe=56bc3b04fd) | Nov 21, 2022 |
| HP            | ProBook 4540s               | [6dce896f40](https://bsd-hardware.info/?probe=6dce896f40) | Nov 20, 2022 |
| Dell          | Vostro 3550                 | [2aeadb4dfc](https://bsd-hardware.info/?probe=2aeadb4dfc) | Nov 14, 2022 |
| HP            | ProBook 4540s               | [9c4be9deab](https://bsd-hardware.info/?probe=9c4be9deab) | Nov 07, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [c4fd2595e6](https://bsd-hardware.info/?probe=c4fd2595e6) | Nov 06, 2022 |
| HP            | ProBook 4540s               | [7596b602c6](https://bsd-hardware.info/?probe=7596b602c6) | Nov 05, 2022 |
| Samsung       | 750TDA                      | [a880b1f616](https://bsd-hardware.info/?probe=a880b1f616) | Nov 02, 2022 |
| Dell          | Inspiron 7720               | [6911e08b7e](https://bsd-hardware.info/?probe=6911e08b7e) | Oct 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [caad4323ba](https://bsd-hardware.info/?probe=caad4323ba) | Oct 23, 2022 |
| Dell          | Precision M4500             | [66ded228ea](https://bsd-hardware.info/?probe=66ded228ea) | Oct 20, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | [bc229efed9](https://bsd-hardware.info/?probe=bc229efed9) | Oct 18, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | [0a8b1f727f](https://bsd-hardware.info/?probe=0a8b1f727f) | Oct 17, 2022 |
| Acer          | Aspire A514-54              | [e057b613a0](https://bsd-hardware.info/?probe=e057b613a0) | Oct 17, 2022 |
| Lenovo        | XiaoXinPro-13API 2019 81... | [dfa08657fd](https://bsd-hardware.info/?probe=dfa08657fd) | Oct 16, 2022 |
| Dell          | Inspiron 15 5510            | [22881028bc](https://bsd-hardware.info/?probe=22881028bc) | Oct 16, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | [601029d3fc](https://bsd-hardware.info/?probe=601029d3fc) | Oct 06, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [ce9cfa77aa](https://bsd-hardware.info/?probe=ce9cfa77aa) | Oct 05, 2022 |
| Dell          | Precision 5510              | [f69c9fb0ea](https://bsd-hardware.info/?probe=f69c9fb0ea) | Oct 04, 2022 |
| Dell          | Precision M4500             | [6b987b43b1](https://bsd-hardware.info/?probe=6b987b43b1) | Oct 03, 2022 |
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
| ASUSTek       | ZenBook UX325UA_UM325UA     | [9af051c79f](https://bsd-hardware.info/?probe=9af051c79f) | Jul 17, 2022 |
| Lenovo        | ThinkPad T480 20L6SB2N00    | [6c5c9eefc0](https://bsd-hardware.info/?probe=6c5c9eefc0) | Jul 17, 2022 |
| Lenovo        | ThinkPad T420 4236C92       | [4067ce2036](https://bsd-hardware.info/?probe=4067ce2036) | Jul 16, 2022 |
| Lenovo        | ThinkPad X260 20F6S0KA00    | [117014d55f](https://bsd-hardware.info/?probe=117014d55f) | Jul 14, 2022 |
| Toshiba       | Satellite L305D             | [b0311b8175](https://bsd-hardware.info/?probe=b0311b8175) | Jul 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [7081ddd59c](https://bsd-hardware.info/?probe=7081ddd59c) | Jul 11, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [66543e9280](https://bsd-hardware.info/?probe=66543e9280) | Jul 07, 2022 |
| Dell          | Latitude E6420              | [c41c8ff4f4](https://bsd-hardware.info/?probe=c41c8ff4f4) | Jul 07, 2022 |
| Fujitsu       | LIFEBOOK A555               | [d9fd7e54cf](https://bsd-hardware.info/?probe=d9fd7e54cf) | Jul 06, 2022 |
| Unknown       | Unknown                     | [584ecf8423](https://bsd-hardware.info/?probe=584ecf8423) | Jul 05, 2022 |
| HP            | Laptop 15-bs1xx             | [b697848727](https://bsd-hardware.info/?probe=b697848727) | Jul 05, 2022 |
| LG Electro... | 17Z990-R.AAC9U1             | [5777cb6dc6](https://bsd-hardware.info/?probe=5777cb6dc6) | Jul 01, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | [f573327012](https://bsd-hardware.info/?probe=f573327012) | Jun 29, 2022 |
| Acer          | Aspire A114-33              | [d3659c85e9](https://bsd-hardware.info/?probe=d3659c85e9) | Jun 28, 2022 |
| Samsung       | R530/R730/R540              | [a4cd230718](https://bsd-hardware.info/?probe=a4cd230718) | Jun 27, 2022 |
| Fujitsu Si... | AMILO Li3710                | [6d4bc39638](https://bsd-hardware.info/?probe=6d4bc39638) | Jun 18, 2022 |
| Sony          | VGN-NS21M_S                 | [c9701a7ff5](https://bsd-hardware.info/?probe=c9701a7ff5) | Jun 18, 2022 |
| Dell          | Latitude E5420              | [524ab094e1](https://bsd-hardware.info/?probe=524ab094e1) | Jun 13, 2022 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | [8825a49f37](https://bsd-hardware.info/?probe=8825a49f37) | Jun 13, 2022 |
| HP            | Laptop 15s-fq1xxx           | [380218b2c1](https://bsd-hardware.info/?probe=380218b2c1) | Jun 12, 2022 |
| Fujitsu Si... | AMILO Li3710                | [387bf3d18f](https://bsd-hardware.info/?probe=387bf3d18f) | Jun 12, 2022 |
| Fujitsu Si... | AMILO Li3710                | [edebcb2719](https://bsd-hardware.info/?probe=edebcb2719) | Jun 12, 2022 |
| Fujitsu       | LIFEBOOK A555               | [23d96bc669](https://bsd-hardware.info/?probe=23d96bc669) | Jun 11, 2022 |
| Dell          | Latitude E5420              | [aca711c5ec](https://bsd-hardware.info/?probe=aca711c5ec) | Jun 09, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [9f33082ffa](https://bsd-hardware.info/?probe=9f33082ffa) | Jun 08, 2022 |
| Dell          | Precision M4800             | [4d77bb0082](https://bsd-hardware.info/?probe=4d77bb0082) | Jun 08, 2022 |
| Dell          | Latitude E5420              | [a3a9820968](https://bsd-hardware.info/?probe=a3a9820968) | Jun 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | [56111732fd](https://bsd-hardware.info/?probe=56111732fd) | Jun 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | [aeec87e07f](https://bsd-hardware.info/?probe=aeec87e07f) | Jun 06, 2022 |
| Lenovo        | ThinkPad X220 4286CTO       | [cb98f3014e](https://bsd-hardware.info/?probe=cb98f3014e) | Jun 05, 2022 |
| Dell          | Latitude 7490               | [18215740d1](https://bsd-hardware.info/?probe=18215740d1) | Jun 05, 2022 |
| Dell          | Latitude E5500              | [b1cb5de914](https://bsd-hardware.info/?probe=b1cb5de914) | Jun 03, 2022 |
| ASUSTek       | X441UV                      | [c8906b438b](https://bsd-hardware.info/?probe=c8906b438b) | Jun 03, 2022 |
| Apple         | MacBookPro11,4              | [29f1ef0cdc](https://bsd-hardware.info/?probe=29f1ef0cdc) | Jun 02, 2022 |
| Lenovo        | ThinkPad W520 4282AD4       | [40198abaa2](https://bsd-hardware.info/?probe=40198abaa2) | Jun 02, 2022 |
| Acer          | Nitro AN515-55              | [0cf6981a98](https://bsd-hardware.info/?probe=0cf6981a98) | Jun 02, 2022 |
| GPD           | MicroPC                     | [a448570ff9](https://bsd-hardware.info/?probe=a448570ff9) | May 31, 2022 |
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
| amd64 | 86        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| KDE5       | 20        | 23.26%  |
| XFCE       | 15        | 17.44%  |
| GNOME      | 13        | 15.12%  |
| Console    | 12        | 13.95%  |
| TWM        | 8         | 9.3%    |
| Openbox    | 4         | 4.65%   |
| i3         | 4         | 4.65%   |
| MATE       | 3         | 3.49%   |
| Cinnamon   | 2         | 2.33%   |
| X-Cinnamon | 1         | 1.16%   |
| LXQt       | 1         | 1.16%   |
| LXDE       | 1         | 1.16%   |
| IceWM      | 1         | 1.16%   |
| dwm        | 1         | 1.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 69        | 80.23%  |
| Console | 12        | 13.95%  |
| Wayland | 5         | 5.81%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 32        | 37.21%  |
| SDDM    | 23        | 26.74%  |
| SLiM    | 12        | 13.95%  |
| GDM     | 9         | 10.47%  |
| XDM     | 5         | 5.81%   |
| LightDM | 4         | 4.65%   |
| PCDM    | 1         | 1.16%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| C               | 61        | 70.11%  |
| en_US           | 13        | 14.94%  |
| zh_CN           | 4         | 4.6%    |
| ru_RU           | 3         | 3.45%   |
| Unknown         | 3         | 3.45%   |
| fr_FR           | 1         | 1.15%   |
| en_US.ISO8859-1 | 1         | 1.15%   |
| en_AU           | 1         | 1.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 70        | 81.4%   |
| BIOS | 16        | 18.6%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Zfs  | 59        | 67.82%  |
| Ufs  | 28        | 32.18%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 78        | 90.7%   |
| MBR     | 6         | 6.98%   |
| BSD     | 1         | 1.16%   |
| Unknown | 1         | 1.16%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 24        | 27.91%  |
| Lenovo              | 23        | 26.74%  |
| ASUSTek Computer    | 10        | 11.63%  |
| Hewlett-Packard     | 6         | 6.98%   |
| Acer                | 3         | 3.49%   |
| TUXEDO              | 2         | 2.33%   |
| Toshiba             | 2         | 2.33%   |
| System76            | 2         | 2.33%   |
| Samsung Electronics | 2         | 2.33%   |
| Google              | 2         | 2.33%   |
| Unknown             | 2         | 2.33%   |
| Sony                | 1         | 1.16%   |
| Notebook            | 1         | 1.16%   |
| MSI                 | 1         | 1.16%   |
| LG Electronics      | 1         | 1.16%   |
| GPD                 | 1         | 1.16%   |
| Fujitsu Siemens     | 1         | 1.16%   |
| Fujitsu             | 1         | 1.16%   |
| Apple               | 1         | 1.16%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| HP EliteBook 850 G7 Notebook PC             | 2         | 2.33%   |
| Google Peppy                                | 2         | 2.33%   |
| Dell Precision M4500                        | 2         | 2.33%   |
| Unknown                                     | 2         | 2.33%   |
| TUXEDO InfinityBook13V3                     | 1         | 1.16%   |
| TUXEDO Aura 15 Gen1                         | 1         | 1.16%   |
| Toshiba Satellite L305D                     | 1         | 1.16%   |
| Toshiba Satellite A300                      | 1         | 1.16%   |
| System76 Gazelle                            | 1         | 1.16%   |
| System76 Galago Pro                         | 1         | 1.16%   |
| Sony VGN-NS21M_S                            | 1         | 1.16%   |
| Samsung R530/R730/R540                      | 1         | 1.16%   |
| Samsung 750TDA                              | 1         | 1.16%   |
| Notebook N7x0WU                             | 1         | 1.16%   |
| MSI GF63 Thin 9SC                           | 1         | 1.16%   |
| LG 17Z990-R.AAC9U1                          | 1         | 1.16%   |
| Lenovo XiaoXinPro-13API 2019 81XD           | 1         | 1.16%   |
| Lenovo ThinkPad X270 20HMCTO1WW             | 1         | 1.16%   |
| Lenovo ThinkPad X260 20F6S0KA00             | 1         | 1.16%   |
| Lenovo ThinkPad X250 20CMS0FA00             | 1         | 1.16%   |
| Lenovo ThinkPad X220 4286CTO                | 1         | 1.16%   |
| Lenovo ThinkPad X13 Gen 1 20UF000QRT        | 1         | 1.16%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TKS0QB00 | 1         | 1.16%   |
| Lenovo ThinkPad X1 Carbon Gen 10 21CBCTO1WW | 1         | 1.16%   |
| Lenovo ThinkPad W520 4282AD4                | 1         | 1.16%   |
| Lenovo ThinkPad T480 20L6SB2N00             | 1         | 1.16%   |
| Lenovo ThinkPad T480 20L6S29E0T             | 1         | 1.16%   |
| Lenovo ThinkPad T420s 41732AU               | 1         | 1.16%   |
| Lenovo ThinkPad T420 4236C92                | 1         | 1.16%   |
| Lenovo ThinkPad T14 Gen 1 20S0CTO1WW        | 1         | 1.16%   |
| Lenovo ThinkPad L420 7854CTO                | 1         | 1.16%   |
| Lenovo ThinkPad L420 7829WDY                | 1         | 1.16%   |
| Lenovo ThinkPad E490 20N8CTO1WW             | 1         | 1.16%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5            | 1         | 1.16%   |
| Lenovo IdeaPad 330-15ARR 81D2               | 1         | 1.16%   |
| Lenovo IdeaPad 3 15ALC6 82KU                | 1         | 1.16%   |
| Lenovo IdeaPad 130-15AST 81H5               | 1         | 1.16%   |
| Lenovo IdeaPad 110-15ACL 80TJ               | 1         | 1.16%   |
| Lenovo G40-45 80E1                          | 1         | 1.16%   |
| HP ProBook 4540s                            | 1         | 1.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 16        | 18.6%   |
| Dell Latitude           | 9         | 10.47%  |
| Lenovo IdeaPad          | 5         | 5.81%   |
| Dell Precision          | 5         | 5.81%   |
| Dell Inspiron           | 5         | 5.81%   |
| ASUS ZenBook            | 4         | 4.65%   |
| ASUS VivoBook           | 3         | 3.49%   |
| Toshiba Satellite       | 2         | 2.33%   |
| HP EliteBook            | 2         | 2.33%   |
| Google Peppy            | 2         | 2.33%   |
| Dell Vostro             | 2         | 2.33%   |
| Acer Aspire             | 2         | 2.33%   |
| Unknown                 | 2         | 2.33%   |
| TUXEDO InfinityBook13V3 | 1         | 1.16%   |
| TUXEDO Aura             | 1         | 1.16%   |
| System76 Gazelle        | 1         | 1.16%   |
| System76 Galago         | 1         | 1.16%   |
| Sony VGN-NS21M          | 1         | 1.16%   |
| Samsung R530            | 1         | 1.16%   |
| Samsung 750TDA          | 1         | 1.16%   |
| Notebook N7x0WU         | 1         | 1.16%   |
| MSI GF63                | 1         | 1.16%   |
| LG 17Z990-R.AAC9U1      | 1         | 1.16%   |
| Lenovo XiaoXinPro-13API | 1         | 1.16%   |
| Lenovo G40-45           | 1         | 1.16%   |
| HP ProBook              | 1         | 1.16%   |
| HP Pavilion             | 1         | 1.16%   |
| HP Laptop               | 1         | 1.16%   |
| HP ENVY                 | 1         | 1.16%   |
| GPD MicroPC             | 1         | 1.16%   |
| Fujitsu Siemens AMILO   | 1         | 1.16%   |
| Fujitsu LIFEBOOK        | 1         | 1.16%   |
| Dell XPS                | 1         | 1.16%   |
| Dell Studio             | 1         | 1.16%   |
| Dell G5                 | 1         | 1.16%   |
| ASUS X455LJ             | 1         | 1.16%   |
| ASUS X441UV             | 1         | 1.16%   |
| ASUS 1001P              | 1         | 1.16%   |
| Apple MacBookPro11      | 1         | 1.16%   |
| Acer Nitro              | 1         | 1.16%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2022 | 12        | 13.95%  |
| 2020 | 12        | 13.95%  |
| 2021 | 11        | 12.79%  |
| 2019 | 8         | 9.3%    |
| 2018 | 8         | 9.3%    |
| 2016 | 6         | 6.98%   |
| 2012 | 6         | 6.98%   |
| 2011 | 6         | 6.98%   |
| 2015 | 4         | 4.65%   |
| 2010 | 4         | 4.65%   |
| 2017 | 2         | 2.33%   |
| 2013 | 2         | 2.33%   |
| 2009 | 2         | 2.33%   |
| 2008 | 2         | 2.33%   |
| 2014 | 1         | 1.16%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 86        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 83        | 96.51%  |
| Yes  | 3         | 3.49%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 32        | 37.21%  |
| 16.01-24.0  | 28        | 32.56%  |
| 4.01-8.0    | 13        | 15.12%  |
| 32.01-64.0  | 6         | 6.98%   |
| 64.01-256.0 | 3         | 3.49%   |
| 24.01-32.0  | 2         | 2.33%   |
| 2.01-3.0    | 2         | 2.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 33        | 38.37%  |
| 0.51-1.0  | 26        | 30.23%  |
| 1.01-2.0  | 19        | 22.09%  |
| 2.01-3.0  | 7         | 8.14%   |
| 8.01-16.0 | 1         | 1.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 63        | 73.26%  |
| 2      | 19        | 22.09%  |
| 0      | 3         | 3.49%   |
| 3      | 1         | 1.16%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 61        | 70.93%  |
| Yes       | 25        | 29.07%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 59        | 68.6%   |
| No        | 27        | 31.4%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 85        | 98.84%  |
| No        | 1         | 1.16%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 62        | 72.09%  |
| No        | 24        | 27.91%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 19        | 21.84%  |
| Russia      | 8         | 9.2%    |
| China       | 6         | 6.9%    |
| India       | 5         | 5.75%   |
| France      | 5         | 5.75%   |
| UK          | 4         | 4.6%    |
| Japan       | 3         | 3.45%   |
| Austria     | 3         | 3.45%   |
| Turkey      | 2         | 2.3%    |
| Thailand    | 2         | 2.3%    |
| Spain       | 2         | 2.3%    |
| Philippines | 2         | 2.3%    |
| Netherlands | 2         | 2.3%    |
| Italy       | 2         | 2.3%    |
| Germany     | 2         | 2.3%    |
| Czechia     | 2         | 2.3%    |
| Venezuela   | 1         | 1.15%   |
| Uruguay     | 1         | 1.15%   |
| South Korea | 1         | 1.15%   |
| Slovenia    | 1         | 1.15%   |
| Norway      | 1         | 1.15%   |
| Mexico      | 1         | 1.15%   |
| Malaysia    | 1         | 1.15%   |
| Lithuania   | 1         | 1.15%   |
| Israel      | 1         | 1.15%   |
| Hong Kong   | 1         | 1.15%   |
| Guadeloupe  | 1         | 1.15%   |
| Greece      | 1         | 1.15%   |
| Finland     | 1         | 1.15%   |
| Canada      | 1         | 1.15%   |
| Bulgaria    | 1         | 1.15%   |
| Belarus     | 1         | 1.15%   |
| Australia   | 1         | 1.15%   |
| Argentina   | 1         | 1.15%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 4         | 4.6%    |
| Vienna            | 3         | 3.45%   |
| Paris             | 2         | 2.3%    |
| Carry-le-Rouet    | 2         | 2.3%    |
| Brno              | 2         | 2.3%    |
| Zhumadian         | 1         | 1.15%   |
| Yangcheon-gu      | 1         | 1.15%   |
| Xiamen            | 1         | 1.15%   |
| Xi'an             | 1         | 1.15%   |
| Woerdense Verlaat | 1         | 1.15%   |
| Wheatland         | 1         | 1.15%   |
| Vilnius           | 1         | 1.15%   |
| Turku             | 1         | 1.15%   |
| Trivandrum        | 1         | 1.15%   |
| Tlalnepantla      | 1         | 1.15%   |
| Thousand Oaks     | 1         | 1.15%   |
| Thessaloniki      | 1         | 1.15%   |
| Tel Aviv          | 1         | 1.15%   |
| Taito             | 1         | 1.15%   |
| Stratford         | 1         | 1.15%   |
| St Petersburg     | 1         | 1.15%   |
| Shinjuku          | 1         | 1.15%   |
| Shah Alam         | 1         | 1.15%   |
| Sandefjord        | 1         | 1.15%   |
| San Pablo City    | 1         | 1.15%   |
| San Antonio       | 1         | 1.15%   |
| Samokov           | 1         | 1.15%   |
| Riverside         | 1         | 1.15%   |
| Queens            | 1         | 1.15%   |
| Qinnan            | 1         | 1.15%   |
| Ozersk            | 1         | 1.15%   |
| Oswego            | 1         | 1.15%   |
| Omaha             | 1         | 1.15%   |
| Newbury Park      | 1         | 1.15%   |
| New York          | 1         | 1.15%   |
| New Delhi         | 1         | 1.15%   |
| Nakano            | 1         | 1.15%   |
| Munich            | 1         | 1.15%   |
| Mumbai            | 1         | 1.15%   |
| Montevideo        | 1         | 1.15%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 22        | 24     | 22%     |
| Samsung Electronics | 18        | 19     | 18%     |
| Seagate             | 7         | 8      | 7%      |
| Kingston            | 7         | 8      | 7%      |
| Crucial             | 7         | 8      | 7%      |
| Toshiba             | 5         | 5      | 5%      |
| SK hynix            | 5         | 5      | 5%      |
| KIOXIA              | 3         | 3      | 3%      |
| Hitachi             | 3         | 3      | 3%      |
| A-DATA Technology   | 3         | 6      | 3%      |
| Transcend           | 2         | 2      | 2%      |
| Silicon Motion      | 2         | 2      | 2%      |
| SanDisk             | 2         | 2      | 2%      |
| Gigabyte Technology | 2         | 2      | 2%      |
| UMIS                | 1         | 1      | 1%      |
| Micron Technology   | 1         | 1      | 1%      |
| Lexar               | 1         | 2      | 1%      |
| Lenovo              | 1         | 1      | 1%      |
| Intel               | 1         | 1      | 1%      |
| Hikvision           | 1         | 1      | 1%      |
| Hewlett-Packard     | 1         | 1      | 1%      |
| EAGET               | 1         | 1      | 1%      |
| CFD                 | 1         | 1      | 1%      |
| BR                  | 1         | 1      | 1%      |
| BIWIN               | 1         | 1      | 1%      |
| Apple               | 1         | 1      | 1%      |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| WDC WDS100T2B0C-00PXH0 1TB                      | 2         | 1.9%    |
| WDC WD3200BPVT-80JJ5T0 320GB                    | 2         | 1.9%    |
| SK hynix BC511 HFM512GDJTNI-82A0A 512GB         | 2         | 1.9%    |
| Samsung SSD 970 EVO Plus 2TB                    | 2         | 1.9%    |
| KIOXIA KBG40ZNS512G NVMe 512GB                  | 2         | 1.9%    |
| Crucial CT1000MX500SSD1 1TB                     | 2         | 1.9%    |
| WDC WDS500G3X0C-00SJG0 500GB                    | 1         | 0.95%   |
| WDC WDS480G2G0A-00JH30 480GB                    | 1         | 0.95%   |
| WDC WDS250G2B0B-00YS70 250GB                    | 1         | 0.95%   |
| WDC WDS240G2G0A-00JH30 240GB                    | 1         | 0.95%   |
| WDC WDS120G2G0B-00EPW0 120GB                    | 1         | 0.95%   |
| WDC WD3200BPVT-22JJ5T0 320GB                    | 1         | 0.95%   |
| WDC WD3200BEKT-60PVMT0 320GB                    | 1         | 0.95%   |
| WDC WD2500BEVT-24A23T0 250GB                    | 1         | 0.95%   |
| WDC WD20SPZX-00UA7T0 2TB                        | 1         | 0.95%   |
| WDC WD1600BEVT-80A23T0 160GB                    | 1         | 0.95%   |
| WDC WD1600BEVT-75ZCT2 160GB                     | 1         | 0.95%   |
| WDC WD1600BEVT-22ZCT0 160GB                     | 1         | 0.95%   |
| WDC WD10SPZX-75Z10T3 1TB                        | 1         | 0.95%   |
| WDC WD10SPZX-17Z10T1 1TB                        | 1         | 0.95%   |
| WDC WD10JPVX-22JC3T0 1TB                        | 1         | 0.95%   |
| WDC WD10JPCX-24UE4T0 1TB                        | 1         | 0.95%   |
| WDC WD10EZEX-60WN4A0 1TB                        | 1         | 0.95%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB              | 1         | 0.95%   |
| WDC PC SN530 SDBPNPZ-256G-1014 256GB            | 1         | 0.95%   |
| WDC PC SN530 NVMe 256GB                         | 1         | 0.95%   |
| UMIS RPJTJ256MEE1OWX 256GB                      | 1         | 0.95%   |
| Transcend TS1TMTE110S 1TB                       | 1         | 0.95%   |
| Transcend TS128GMTS430S 128GB                   | 1         | 0.95%   |
| Toshiba MQ04ABF100 1TB                          | 1         | 0.95%   |
| Toshiba MQ01ABF050 500GB                        | 1         | 0.95%   |
| Toshiba MQ01ABD100 1TB                          | 1         | 0.95%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB             | 1         | 0.95%   |
| Toshiba KBG30ZMT512G 512GB                      | 1         | 0.95%   |
| SK hynix SKHynix_HFS256GDE9X081N 256GB          | 1         | 0.95%   |
| SK hynix HFM512GD3JX013N 512GB                  | 1         | 0.95%   |
| SK hynix BC501 NVMe 512GB                       | 1         | 0.95%   |
| Silicon Motion Asgard AN2+ 256NVMe-M.2-80 256GB | 1         | 0.95%   |
| Silicon Motion 512GB MEGA S3 512GB              | 1         | 0.95%   |
| Seagate ST9750420AS 752GB                       | 1         | 0.95%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 13        | 14     | 50%     |
| Seagate | 7         | 8      | 26.92%  |
| Toshiba | 3         | 3      | 11.54%  |
| Hitachi | 3         | 3      | 11.54%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 6      | 16.67%  |
| Crucial             | 6         | 7      | 16.67%  |
| WDC                 | 4         | 4      | 11.11%  |
| Kingston            | 4         | 5      | 11.11%  |
| A-DATA Technology   | 3         | 6      | 8.33%   |
| SanDisk             | 2         | 2      | 5.56%   |
| Transcend           | 1         | 1      | 2.78%   |
| Toshiba             | 1         | 1      | 2.78%   |
| Lexar               | 1         | 2      | 2.78%   |
| Lenovo              | 1         | 1      | 2.78%   |
| Hikvision           | 1         | 1      | 2.78%   |
| Hewlett-Packard     | 1         | 1      | 2.78%   |
| Gigabyte Technology | 1         | 1      | 2.78%   |
| CFD                 | 1         | 1      | 2.78%   |
| BR                  | 1         | 1      | 2.78%   |
| BIWIN               | 1         | 1      | 2.78%   |
| Apple               | 1         | 1      | 2.78%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 38        | 40     | 40%     |
| SSD  | 32        | 42     | 33.68%  |
| HDD  | 25        | 28     | 26.32%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 54        | 70     | 58.7%   |
| NVMe | 38        | 40     | 41.3%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 36        | 46     | 63.16%  |
| 0.51-1.0   | 17        | 20     | 29.82%  |
| 1.01-2.0   | 4         | 4      | 7.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 33        | 38.37%  |
| 251-500    | 23        | 26.74%  |
| 501-1000   | 15        | 17.44%  |
| 51-100     | 7         | 8.14%   |
| 1001-2000  | 4         | 4.65%   |
| 21-50      | 3         | 3.49%   |
| 1-20       | 1         | 1.16%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 67        | 77.01%  |
| 21-50   | 13        | 14.94%  |
| 101-250 | 4         | 4.6%    |
| 51-100  | 2         | 2.3%    |
| 251-500 | 1         | 1.15%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD3200BPVT-80JJ5T0 320GB                 | 2         | 2      | 11.11%  |
| WDC WD3200BEKT-60PVMT0 320GB                 | 1         | 1      | 5.56%   |
| WDC WD2500BEVT-24A23T0 250GB                 | 1         | 1      | 5.56%   |
| Toshiba MQ01ABF050 500GB                     | 1         | 1      | 5.56%   |
| Toshiba MQ01ABD100 1TB                       | 1         | 1      | 5.56%   |
| Seagate ST9750420AS 752GB                    | 1         | 1      | 5.56%   |
| Seagate ST500LT012-1DG142 500GB              | 1         | 1      | 5.56%   |
| Seagate ST500LM012 HN-M500MBB 500GB          | 1         | 1      | 5.56%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 2      | 5.56%   |
| Samsung Electronics SSD PM810 2.5-inch 128GB | 1         | 1      | 5.56%   |
| Kingston SVP200S37A120G 120GB                | 1         | 1      | 5.56%   |
| Kingston SNS4151S316GD 16GB                  | 1         | 1      | 5.56%   |
| Kingston SH103S3240G 240GB                   | 1         | 1      | 5.56%   |
| Hitachi HTS721080G9SA00 80GB                 | 1         | 1      | 5.56%   |
| Hitachi HTS543232L9SA00 320GB                | 1         | 1      | 5.56%   |
| A-DATA Technology SU650 120GB                | 1         | 1      | 5.56%   |
| A-DATA Technology SU630 240GB                | 1         | 2      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 5      | 25%     |
| WDC                 | 3         | 4      | 18.75%  |
| Toshiba             | 2         | 2      | 12.5%   |
| Kingston            | 2         | 3      | 12.5%   |
| Hitachi             | 2         | 2      | 12.5%   |
| A-DATA Technology   | 2         | 3      | 12.5%   |
| Samsung Electronics | 1         | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 5      | 36.36%  |
| WDC     | 3         | 4      | 27.27%  |
| Toshiba | 2         | 2      | 18.18%  |
| Hitachi | 2         | 2      | 18.18%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 13     | 66.67%  |
| SSD  | 5         | 7      | 33.33%  |

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
| Works    | 68        | 87     | 80%     |
| Malfunc  | 15        | 20     | 17.65%  |
| Detected | 2         | 3      | 2.35%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 52        | 50.49%  |
| Samsung Electronics         | 13        | 12.62%  |
| AMD                         | 11        | 10.68%  |
| SanDisk                     | 7         | 6.8%    |
| SK hynix                    | 4         | 3.88%   |
| Silicon Motion              | 3         | 2.91%   |
| KIOXIA                      | 3         | 2.91%   |
| Kingston Technology Company | 3         | 2.91%   |
| Union Memory (Shenzhen)     | 1         | 0.97%   |
| Transcend                   | 1         | 0.97%   |
| Toshiba                     | 1         | 0.97%   |
| Phison Electronics          | 1         | 0.97%   |
| Nvidia                      | 1         | 0.97%   |
| Micron/Crucial Technology   | 1         | 0.97%   |
| Micron Technology           | 1         | 0.97%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 10        | 9.35%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 9         | 8.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 7         | 6.54%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 7         | 6.54%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 5.61%   |
| Unknown                                                                        | 5         | 4.67%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 3.74%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 3.74%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 3.74%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 3         | 2.8%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 2.8%    |
| KIOXIA NVMe SSD Controller BG4                                                 | 3         | 2.8%    |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 2         | 1.87%   |
| SK hynix BC511                                                                 | 2         | 1.87%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 1.87%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 1.87%   |
| SanDisk unknown                                                                | 2         | 1.87%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 1.87%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 1.87%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 1.87%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2         | 1.87%   |
| Toshiba BG3 NVMe SSD Controller                                                | 1         | 0.93%   |
| SanDisk WD Blue SN570 NVMe SSD                                                 | 1         | 0.93%   |
| Samsung SM951 AHCI                                                             | 1         | 0.93%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1         | 0.93%   |
| Samsung NVMe SSD Controller 980                                                | 1         | 0.93%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1         | 0.93%   |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 0.93%   |
| Kingston Company SNVS2000G [NV1 NVMe PCIe SSD 2TB]                             | 1         | 0.93%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 1         | 0.93%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1         | 0.93%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 0.93%   |
| Intel SSD 660P Series                                                          | 1         | 0.93%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 0.93%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 0.93%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 1         | 0.93%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 0.93%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 0.93%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 0.93%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 1         | 0.93%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 57        | 54.81%  |
| NVMe | 37        | 35.58%  |
| RAID | 8         | 7.69%   |
| IDE  | 2         | 1.92%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 71        | 82.56%  |
| AMD    | 15        | 17.44%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz       | 4         | 4.65%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 3         | 3.49%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 3         | 3.49%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 3         | 3.49%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 2         | 2.33%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 2         | 2.33%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 2         | 2.33%   |
| Intel Core i5-10310U CPU @ 1.70GHz      | 2         | 2.33%   |
| Intel Core i5 CPU M 560 @ 2.67GH        | 2         | 2.33%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 2         | 2.33%   |
| AMD Ryzen 3 5300U with Radeon Graphics  | 2         | 2.33%   |
| Intel Pentium Silver N6000 @ 1.10GHz    | 1         | 1.16%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz  | 1         | 1.16%   |
| Intel Genuine CPU                       | 1         | 1.16%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 1.16%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 1         | 1.16%   |
| Intel Core i7-4980HQ CPU @ 2.80GHz      | 1         | 1.16%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz      | 1         | 1.16%   |
| Intel Core i7-4610M CPU @ 3.00GHz       | 1         | 1.16%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 1         | 1.16%   |
| Intel Core i7-3632QM CPU @ 2.20GHz      | 1         | 1.16%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 1         | 1.16%   |
| Intel Core i7-3537U CPU @ 2.00GHz       | 1         | 1.16%   |
| Intel Core i7-2760QM CPU @ 2.40GHz      | 1         | 1.16%   |
| Intel Core i7-2640M CPU @ 2.80GHz       | 1         | 1.16%   |
| Intel Core i7-2620M CPU @ 2.70GHz       | 1         | 1.16%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 1         | 1.16%   |
| Intel Core i7-10610U CPU @ 1.80GHz      | 1         | 1.16%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 1         | 1.16%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 1         | 1.16%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 1         | 1.16%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz      | 1         | 1.16%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 1         | 1.16%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 1         | 1.16%   |
| Intel Core i5-2540M CPU @ 2.60GHz       | 1         | 1.16%   |
| Intel Core i5-2540M CPU @ 2.60GH        | 1         | 1.16%   |
| Intel Core i5-2520M CPU @ 2.50GH        | 1         | 1.16%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 1         | 1.16%   |
| Intel Core i5-10300H CPU @ 2.50GHz      | 1         | 1.16%   |
| Intel Core i3-8130U CPU @ 2.20GHz       | 1         | 1.16%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i7        | 26        | 30.23%  |
| Intel Core i5        | 22        | 25.58%  |
| Other                | 6         | 6.98%   |
| Intel Celeron        | 5         | 5.81%   |
| Intel Core i3        | 4         | 4.65%   |
| Intel Core 2 Duo     | 4         | 4.65%   |
| AMD Ryzen 3          | 4         | 4.65%   |
| AMD Ryzen 7          | 3         | 3.49%   |
| AMD Ryzen 5          | 3         | 3.49%   |
| AMD A8               | 2         | 2.33%   |
| Intel Pentium Silver | 1         | 1.16%   |
| Intel Pentium Dual   | 1         | 1.16%   |
| Intel Genuine        | 1         | 1.16%   |
| Intel Atom           | 1         | 1.16%   |
| AMD Ryzen 7 PRO      | 1         | 1.16%   |
| AMD E2               | 1         | 1.16%   |
| AMD Athlon X2        | 1         | 1.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 36        | 41.86%  |
| 4       | 32        | 37.21%  |
| 8       | 7         | 8.14%   |
| 6       | 4         | 4.65%   |
| 16      | 3         | 3.49%   |
| Unknown | 2         | 2.33%   |
| 20      | 1         | 1.16%   |
| 1       | 1         | 1.16%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 86        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 58        | 67.44%  |
| 1       | 26        | 30.23%  |
| Unknown | 2         | 2.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 20        | 23.26%  |
| SandyBridge     | 9         | 10.47%  |
| Haswell         | 6         | 6.98%   |
| Unknown         | 6         | 6.98%   |
| Skylake         | 5         | 5.81%   |
| IvyBridge       | 5         | 5.81%   |
| TigerLake       | 4         | 4.65%   |
| Broadwell       | 4         | 4.65%   |
| Zen+            | 3         | 3.49%   |
| Westmere        | 3         | 3.49%   |
| Core            | 3         | 3.49%   |
| Zen 2           | 2         | 2.33%   |
| Zen             | 2         | 2.33%   |
| Puma            | 2         | 2.33%   |
| Penryn          | 2         | 2.33%   |
| Goldmont plus   | 2         | 2.33%   |
| CometLake       | 2         | 2.33%   |
| Zen 3           | 1         | 1.16%   |
| K8 & K10 hybrid | 1         | 1.16%   |
| IceLake         | 1         | 1.16%   |
| Goldmont        | 1         | 1.16%   |
| Excavator       | 1         | 1.16%   |
| Bonnell         | 1         | 1.16%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 66        | 62.26%  |
| AMD    | 21        | 19.81%  |
| Nvidia | 19        | 17.92%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 9         | 8.26%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 5         | 4.59%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 5         | 4.59%   |
| Intel UHD Graphics 620                                                    | 4         | 3.67%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 4         | 3.67%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 4         | 3.67%   |
| Intel HD Graphics 5500                                                    | 4         | 3.67%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 4         | 3.67%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 3         | 2.75%   |
| Intel HD Graphics 620                                                     | 3         | 2.75%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 3         | 2.75%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 3         | 2.75%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 3         | 2.75%   |
| AMD Lucienne                                                              | 3         | 2.75%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 2         | 1.83%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 2         | 1.83%   |
| Nvidia GT216GLM [Quadro FX 880M]                                          | 2         | 1.83%   |
| Nvidia GP108BM [GeForce MX250]                                            | 2         | 1.83%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 1.83%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 2         | 1.83%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 2         | 1.83%   |
| AMD Renoir                                                                | 2         | 1.83%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 1.83%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                       | 2         | 1.83%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 0.92%   |
| Nvidia TU117M                                                             | 1         | 0.92%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 0.92%   |
| Nvidia GM108M [GeForce MX130]                                             | 1         | 0.92%   |
| Nvidia GM108M [GeForce 920MX]                                             | 1         | 0.92%   |
| Nvidia GM107GLM [Quadro M1000M]                                           | 1         | 0.92%   |
| Nvidia GK208BM [GeForce 920M]                                             | 1         | 0.92%   |
| Nvidia GK107M [GeForce GT 650M]                                           | 1         | 0.92%   |
| Nvidia GF108GLM [NVS 5200M]                                               | 1         | 0.92%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                        | 1         | 0.92%   |
| Nvidia G98M [GeForce 9200M GS]                                            | 1         | 0.92%   |
| Nvidia C79 [GeForce 9400M G]                                              | 1         | 0.92%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 1         | 0.92%   |
| Intel JasperLake [UHD Graphics]                                           | 1         | 0.92%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 1         | 0.92%   |
| Intel HD Graphics 530                                                     | 1         | 0.92%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 43        | 50%     |
| Intel + Nvidia | 13        | 15.12%  |
| 1 x AMD        | 13        | 15.12%  |
| 2 x Intel      | 5         | 5.81%   |
| Intel + AMD    | 5         | 5.81%   |
| 1 x Nvidia     | 3         | 3.49%   |
| AMD + Nvidia   | 2         | 2.33%   |
| 2 x Nvidia     | 1         | 1.16%   |
| 2 x AMD        | 1         | 1.16%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 78        | 90.7%   |
| Proprietary | 8         | 9.3%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 72        | 83.72%  |
| 0.51-1.0   | 5         | 5.81%   |
| 0.01-0.5   | 5         | 5.81%   |
| 1.01-2.0   | 2         | 2.33%   |
| 5.01-6.0   | 1         | 1.16%   |
| 3.01-4.0   | 1         | 1.16%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 15        | 19.23%  |
| BOE                 | 13        | 16.67%  |
| AU Optronics        | 11        | 14.1%   |
| Chimei Innolux      | 9         | 11.54%  |
| Samsung Electronics | 7         | 8.97%   |
| Toshiba             | 2         | 2.56%   |
| Sharp               | 2         | 2.56%   |
| LGD                 | 2         | 2.56%   |
| Lenovo              | 2         | 2.56%   |
| CSO                 | 2         | 2.56%   |
| BenQ                | 2         | 2.56%   |
| YTH                 | 1         | 1.28%   |
| ViewSonic           | 1         | 1.28%   |
| USR                 | 1         | 1.28%   |
| Unknown (XXX)       | 1         | 1.28%   |
| Sceptre Tech        | 1         | 1.28%   |
| LG Philips          | 1         | 1.28%   |
| JDI                 | 1         | 1.28%   |
| HannStar            | 1         | 1.28%   |
| Apple               | 1         | 1.28%   |
| AOC                 | 1         | 1.28%   |
| Acer                | 1         | 1.28%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LGD LCD Monitor 1600x900                                              | 2         | 2.56%   |
| LG Display LCD Monitor LGD064C 1920x1080 340x190mm 15.3-inch          | 2         | 2.56%   |
| BenQ BL2480 BNQ802C 1920x1080 530x300mm 24.0-inch                     | 2         | 2.56%   |
| YTH HS133PC YTH1330 1920x1080 250x220mm 13.1-inch                     | 1         | 1.28%   |
| ViewSonic LCD Monitor VSCD22B 1920x1080 520x290mm 23.4-inch           | 1         | 1.28%   |
| USR LCD Monitor USR0100 1920x1080 510x290mm 23.1-inch                 | 1         | 1.28%   |
| Unknown (XXX) SMART TV XXX2851 3840x2160                              | 1         | 1.28%   |
| Toshiba TV TSB0200 1920x1080 530x300mm 24.0-inch                      | 1         | 1.28%   |
| Toshiba ScreenXpert- TSB8888 1080x2160 60x130mm 5.6-inch              | 1         | 1.28%   |
| Sharp LCD Monitor SHP143E 3840x2160 350x190mm 15.7-inch               | 1         | 1.28%   |
| Sharp LCD Monitor SHP1421 3200x1800 290x170mm 13.2-inch               | 1         | 1.28%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch        | 1         | 1.28%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch     | 1         | 1.28%   |
| Samsung Electronics LS24A40xU SAM71D1 1920x1080 530x300mm 24.0-inch   | 1         | 1.28%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 300x170mm 13.6-inch  | 1         | 1.28%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 330x210mm 15.4-inch  | 1         | 1.28%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 340x190mm 15.3-inch  | 1         | 1.28%   |
| Samsung Electronics LCD Monitor SDC8B4F 1920x1080 340x190mm 15.3-inch | 1         | 1.28%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 290x170mm 13.2-inch | 1         | 1.28%   |
| LG Philips LCD Monitor LPL0120 1280x800 330x210mm 15.4-inch           | 1         | 1.28%   |
| LG Display LCD Monitor LGD6E01 1366x768 340x190mm 15.3-inch           | 1         | 1.28%   |
| LG Display LCD Monitor LGD060A 1920x1080 290x170mm 13.2-inch          | 1         | 1.28%   |
| LG Display LCD Monitor LGD05F8 2560x1600 370x230mm 17.2-inch          | 1         | 1.28%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch          | 1         | 1.28%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch          | 1         | 1.28%   |
| LG Display LCD Monitor LGD0408 1920x1080 280x160mm 12.7-inch          | 1         | 1.28%   |
| LG Display LCD Monitor LGD03DD 1366x768 340x190mm 15.3-inch           | 1         | 1.28%   |
| LG Display LCD Monitor LGD0395 1366x768 340x190mm 15.3-inch           | 1         | 1.28%   |
| LG Display LCD Monitor LGD0353 1366x768 350x190mm 15.7-inch           | 1         | 1.28%   |
| LG Display LCD Monitor LGD02EB 1366x768 310x170mm 13.9-inch           | 1         | 1.28%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x170mm 13.9-inch           | 1         | 1.28%   |
| LG Display LCD Monitor LGD02DA 1920x1080 380x210mm 17.1-inch          | 1         | 1.28%   |
| LG Display LCD Monitor LGD02D3 1366x768 280x160mm 12.7-inch           | 1         | 1.28%   |
| Lenovo LEN T32h-20 LEN61F1 2560x1440 700x390mm 31.5-inch              | 1         | 1.28%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch              | 1         | 1.28%   |
| JDI LCD Monitor JDI385A 3840x2160 290x170mm 13.2-inch                 | 1         | 1.28%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch             | 1         | 1.28%   |
| CSO LCD Monitor CSO1400 3840x2160 310x170mm 13.9-inch                 | 1         | 1.28%   |
| CSO LCD Monitor CSO076D 2560x1600 290x180mm 13.4-inch                 | 1         | 1.28%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 340x190mm 15.3-inch      | 1         | 1.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 39        | 52.7%   |
| 1366x768 (WXGA)  | 15        | 20.27%  |
| 3840x2160 (4K)   | 5         | 6.76%   |
| 1600x900 (HD+)   | 4         | 5.41%   |
| 2560x1600        | 2         | 2.7%    |
| 2560x1440 (QHD)  | 2         | 2.7%    |
| 1280x800 (WXGA)  | 2         | 2.7%    |
| 3200x1800 (QHD+) | 1         | 1.35%   |
| 2880x1800        | 1         | 1.35%   |
| 2560x1080        | 1         | 1.35%   |
| 1080x2160        | 1         | 1.35%   |
| 1024x600         | 1         | 1.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 29        | 37.18%  |
| 13      | 25        | 32.05%  |
| 12      | 5         | 6.41%   |
| 24      | 4         | 5.13%   |
| 23      | 3         | 3.85%   |
| Unknown | 3         | 3.85%   |
| 27      | 2         | 2.56%   |
| 17      | 2         | 2.56%   |
| 31      | 1         | 1.28%   |
| 29      | 1         | 1.28%   |
| 11      | 1         | 1.28%   |
| 10      | 1         | 1.28%   |
| 5       | 1         | 1.28%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 46        | 59.74%  |
| 201-300     | 14        | 18.18%  |
| 501-600     | 8         | 10.39%  |
| 601-700     | 3         | 3.9%    |
| Unknown     | 3         | 3.9%    |
| 351-400     | 2         | 2.6%    |
| 1-100       | 1         | 1.3%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 58        | 84.06%  |
| 16/10   | 6         | 8.7%    |
| Unknown | 2         | 2.9%    |
| 21/9    | 1         | 1.45%   |
| 11/10   | 1         | 1.45%   |
| 0.46    | 1         | 1.45%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 22        | 28.21%  |
| 81-90          | 19        | 24.36%  |
| 201-250        | 7         | 8.97%   |
| 101-110        | 7         | 8.97%   |
| 71-80          | 6         | 7.69%   |
| 61-70          | 5         | 6.41%   |
| 301-350        | 3         | 3.85%   |
| Unknown        | 3         | 3.85%   |
| 51-60          | 1         | 1.28%   |
| 351-500        | 1         | 1.28%   |
| 41-50          | 1         | 1.28%   |
| 1-40           | 1         | 1.28%   |
| 131-140        | 1         | 1.28%   |
| 121-130        | 1         | 1.28%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 31        | 40.79%  |
| 101-120       | 13        | 17.11%  |
| 51-100        | 13        | 17.11%  |
| 161-240       | 11        | 14.47%  |
| More than 240 | 5         | 6.58%   |
| Unknown       | 3         | 3.95%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 56        | 65.12%  |
| 0     | 19        | 22.09%  |
| 2     | 11        | 12.79%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 53        | 36.81%  |
| Realtek Semiconductor    | 40        | 27.78%  |
| Qualcomm Atheros         | 22        | 15.28%  |
| Broadcom                 | 8         | 5.56%   |
| Xiaomi                   | 2         | 1.39%   |
| TP-Link                  | 2         | 1.39%   |
| Samsung Electronics      | 2         | 1.39%   |
| Ralink Technology        | 2         | 1.39%   |
| MediaTek                 | 2         | 1.39%   |
| Marvell Technology Group | 2         | 1.39%   |
| Google                   | 2         | 1.39%   |
| Sagem                    | 1         | 0.69%   |
| Ralink                   | 1         | 0.69%   |
| Qualcomm                 | 1         | 0.69%   |
| Nvidia                   | 1         | 0.69%   |
| Huawei Technologies      | 1         | 0.69%   |
| HMD Global               | 1         | 0.69%   |
| Arduino SA               | 1         | 0.69%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 20        | 12.27%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 7.36%   |
| Intel Wireless 8265 / 8275                                        | 7         | 4.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 3.68%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 3.07%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 3.07%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 2.45%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 2.45%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 2.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.84%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 3         | 1.84%   |
| Intel Wireless 8260                                               | 3         | 1.84%   |
| Intel Wireless 7265                                               | 3         | 1.84%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 1.84%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 1.84%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.23%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 1.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 1.23%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 1.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 1.23%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 1.23%   |
| Intel Wireless-AC 9260                                            | 2         | 1.23%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.23%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.23%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 1.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 1.23%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 2         | 1.23%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 2         | 1.23%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.61%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.61%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1         | 0.61%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.61%   |
| Sagem XG-76NA 802.11bg                                            | 1         | 0.61%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1         | 0.61%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.61%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 0.61%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.61%   |
| Realtek Realtek Bluetooth Adapter                                 | 1         | 0.61%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.61%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 49        | 51.58%  |
| Qualcomm Atheros      | 22        | 23.16%  |
| Realtek Semiconductor | 9         | 9.47%   |
| Broadcom              | 7         | 7.37%   |
| TP-Link               | 2         | 2.11%   |
| Ralink Technology     | 2         | 2.11%   |
| MediaTek              | 2         | 2.11%   |
| Sagem                 | 1         | 1.05%   |
| Ralink                | 1         | 1.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 7         | 7.37%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 5.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 5.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 4.21%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 4.21%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 4.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 3.16%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 3         | 3.16%   |
| Intel Wireless 8260                                                     | 3         | 3.16%   |
| Intel Wireless 7265                                                     | 3         | 3.16%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 3.16%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 3.16%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 2.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 2.11%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 2.11%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 2.11%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 2.11%   |
| Intel Wireless-AC 9260                                                  | 2         | 2.11%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 2.11%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 2.11%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 2.11%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 2.11%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 1.05%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 1         | 1.05%   |
| Sagem XG-76NA 802.11bg                                                  | 1         | 1.05%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1         | 1.05%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 1.05%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 1.05%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.05%   |
| Realtek Realtek Bluetooth Adapter                                       | 1         | 1.05%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 1.05%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 1.05%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 1.05%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.05%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.05%   |
| Qualcomm Atheros AR2427 802.11bg Wireless Network Adapter (PCI-Express) | 1         | 1.05%   |
| Intel Wireless 7260                                                     | 1         | 1.05%   |
| Intel Wireless 3160                                                     | 1         | 1.05%   |
| Intel WiFi Link 5100                                                    | 1         | 1.05%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 1         | 1.05%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 34        | 51.52%  |
| Intel                    | 18        | 27.27%  |
| Xiaomi                   | 2         | 3.03%   |
| Samsung Electronics      | 2         | 3.03%   |
| Marvell Technology Group | 2         | 3.03%   |
| Google                   | 2         | 3.03%   |
| Broadcom                 | 2         | 3.03%   |
| Qualcomm Atheros         | 1         | 1.52%   |
| Qualcomm                 | 1         | 1.52%   |
| Nvidia                   | 1         | 1.52%   |
| HMD Global               | 1         | 1.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 20        | 30.3%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 18.18%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 9.09%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 3.03%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 3.03%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 3.03%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.52%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 1.52%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.52%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 1.52%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.52%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 1         | 1.52%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.52%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 1.52%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.52%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.52%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.52%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.52%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.52%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.52%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.52%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.52%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 1.52%   |
| HMD Global Nokia 5.3 RNDIS Control RNDIS Ethernet Data            | 1         | 1.52%   |
| Google Nexus/Pixel Device (tether+ debug)                         | 1         | 1.52%   |
| Google Nexus/Pixel Device (tether)                                | 1         | 1.52%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                 | 1         | 1.52%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 1.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 85        | 58.22%  |
| Ethernet | 59        | 40.41%  |
| Modem    | 2         | 1.37%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 49        | 63.64%  |
| Ethernet | 28        | 36.36%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 57        | 66.28%  |
| 1     | 28        | 32.56%  |
| 0     | 1         | 1.16%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 74        | 85.06%  |
| Yes  | 13        | 14.94%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 37        | 57.81%  |
| Qualcomm Atheros Communications | 7         | 10.94%  |
| IMC Networks                    | 4         | 6.25%   |
| Dell                            | 4         | 6.25%   |
| Foxconn / Hon Hai               | 3         | 4.69%   |
| Realtek Semiconductor           | 2         | 3.13%   |
| Lite-On Technology              | 2         | 3.13%   |
| Broadcom                        | 2         | 3.13%   |
| Ralink                          | 1         | 1.56%   |
| Cambridge Silicon Radio         | 1         | 1.56%   |
| Apple                           | 1         | 1.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 11        | 17.19%  |
| Intel AX201 Bluetooth                                       | 11        | 17.19%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 8         | 12.5%   |
| Intel AX200 Bluetooth                                       | 3         | 4.69%   |
| Realtek  Bluetooth Adapter                                  | 2         | 3.13%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 2         | 3.13%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 2         | 3.13%   |
| Dell DW375 Bluetooth Module                                 | 2         | 3.13%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 3.13%   |
| Ralink RT3290 Bluetooth                                     | 1         | 1.56%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 1         | 1.56%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 1.56%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 1.56%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 1.56%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 1.56%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 1.56%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 1.56%   |
| Lite-On Wireless_Device                                     | 1         | 1.56%   |
| Lite-On BCM43142A0 Bluetooth Module                         | 1         | 1.56%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 1.56%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 1.56%   |
| Intel Intel Wireless Bluetooth                              | 1         | 1.56%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 1.56%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 1.56%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 1         | 1.56%   |
| Foxconn / Hon Hai Wireless_Device                           | 1         | 1.56%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 1         | 1.56%   |
| Dell Broadcom BCM20702A0 Bluetooth                          | 1         | 1.56%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 1         | 1.56%   |
| Apple Bluetooth Host Controller                             | 1         | 1.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel           | 70        | 69.31%  |
| AMD             | 17        | 16.83%  |
| Nvidia          | 8         | 7.92%   |
| Plantronics     | 2         | 1.98%   |
| SteelSeries ApS | 1         | 0.99%   |
| Sony            | 1         | 0.99%   |
| Lenovo          | 1         | 0.99%   |
| GN Netcom       | 1         | 0.99%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 11        | 8.87%   |
| AMD Family 17h/19h HD Audio Controller                                     | 11        | 8.87%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 9         | 7.26%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6         | 4.84%   |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 4.03%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 5         | 4.03%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 4.03%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 4.03%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 3.23%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 3.23%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 3.23%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 2.42%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 2.42%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 2.42%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 2.42%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 2.42%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 2.42%   |
| Plantronics Plantronics Blackwire 315.1                                    | 2         | 1.61%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 1.61%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 1.61%   |
| Nvidia GT216 HDMI Audio Controller                                         | 2         | 1.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 1.61%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.61%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.61%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 1.61%   |
| AMD FCH Azalia Controller                                                  | 2         | 1.61%   |
| SteelSeries ApS SteelSeries Siberia 350                                    | 1         | 0.81%   |
| Sony UAB-80                                                                | 1         | 0.81%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.81%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.81%   |
| Lenovo Realtek USB Audio                                                   | 1         | 0.81%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 0.81%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 0.81%   |
| Intel Jasper Lake HD Audio                                                 | 1         | 0.81%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 0.81%   |
| Intel Crystal Well HD Audio Controller                                     | 1         | 0.81%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 0.81%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 1         | 0.81%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 0.81%   |
| GN Netcom Jabra SPEAK 510 USB                                              | 1         | 0.81%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| SK hynix              | 35        | 34.31%  |
| Samsung Electronics   | 24        | 23.53%  |
| Micron Technology     | 7         | 6.86%   |
| Kingston              | 7         | 6.86%   |
| Crucial               | 5         | 4.9%    |
| Unknown               | 5         | 4.9%    |
| Unknown               | 3         | 2.94%   |
| Elpida                | 3         | 2.94%   |
| Unknown (ABCD)        | 2         | 1.96%   |
| Ramaxel Technology    | 2         | 1.96%   |
| KomputerBay           | 2         | 1.96%   |
| Transcend             | 1         | 0.98%   |
| PNY                   | 1         | 0.98%   |
| Nanya Technology      | 1         | 0.98%   |
| Kingmax Semiconductor | 1         | 0.98%   |
| Corsair               | 1         | 0.98%   |
| Apacer                | 1         | 0.98%   |
| A-DATA Technology     | 1         | 0.98%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                   | 5         | 4.59%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 3         | 2.75%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s                    | 3         | 2.75%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 2         | 1.83%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2133MT/s          | 2         | 1.83%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                             | 2         | 1.83%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s                     | 2         | 1.83%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s                    | 2         | 1.83%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s                    | 2         | 1.83%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s                    | 2         | 1.83%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s                    | 2         | 1.83%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 1600MT/s                     | 2         | 1.83%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 2         | 1.83%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s                    | 2         | 1.83%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s                    | 2         | 1.83%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s                    | 2         | 1.83%   |
| KomputerBay RAM KB_8G_D3_1333_C9 8GB SODIMM DDR3 1334MT/s                 | 2         | 1.83%   |
| Unknown RAM Module 2GB SODIMM DDR2                                        | 1         | 0.92%   |
| Transcend RAM TS2GSH64V1B 16GB SODIMM DDR4 2133MT/s                       | 1         | 0.92%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                              | 1         | 0.92%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 0.92%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 0.92%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 1         | 0.92%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 1         | 0.92%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 0.92%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s                    | 1         | 0.92%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s              | 1         | 0.92%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s                    | 1         | 0.92%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s              | 1         | 0.92%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s                    | 1         | 0.92%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s                   | 1         | 0.92%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s                   | 1         | 0.92%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s                   | 1         | 0.92%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 1         | 0.92%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s                    | 1         | 0.92%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s                | 1         | 0.92%   |
| SK hynix RAM 161616161616161616161616161616161616 2GB SODIMM DDR2 800MT/s | 1         | 0.92%   |
| SK hynix RAM 080808080808080808080808080808080808 2GB SODIMM DDR2 800MT/s | 1         | 0.92%   |
| Samsung RAM U6E3S4AA-MGCR 1GB Row Of Chips LPDDR4 4267MT/s                | 1         | 0.92%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s                     | 1         | 0.92%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 41        | 47.67%  |
| DDR3    | 31        | 36.05%  |
| DDR2    | 6         | 6.98%   |
| LPDDR4  | 4         | 4.65%   |
| LPDDR3  | 2         | 2.33%   |
| LPDDR5  | 1         | 1.16%   |
| Unknown | 1         | 1.16%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 79        | 90.8%   |
| Row Of Chips | 7         | 8.05%   |
| Chip         | 1         | 1.15%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 33        | 36.67%  |
| 4096  | 27        | 30%     |
| 16384 | 13        | 14.44%  |
| 2048  | 12        | 13.33%  |
| 32768 | 4         | 4.44%   |
| 1024  | 1         | 1.11%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 20        | 21.74%  |
| 1600    | 17        | 18.48%  |
| 2400    | 12        | 13.04%  |
| 2667    | 10        | 10.87%  |
| 2133    | 8         | 8.7%    |
| 1334    | 7         | 7.61%   |
| 1333    | 3         | 3.26%   |
| 667     | 3         | 3.26%   |
| 975     | 2         | 2.17%   |
| 800     | 2         | 2.17%   |
| 6400    | 1         | 1.09%   |
| 4267    | 1         | 1.09%   |
| 4266    | 1         | 1.09%   |
| 2666    | 1         | 1.09%   |
| 1866    | 1         | 1.09%   |
| 1067    | 1         | 1.09%   |
| 1066    | 1         | 1.09%   |
| Unknown | 1         | 1.09%   |

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
| Chicony Electronics           | 17        | 26.56%  |
| IMC Networks                  | 11        | 17.19%  |
| Sunplus Innovation Technology | 8         | 12.5%   |
| Microdia                      | 7         | 10.94%  |
| Acer                          | 5         | 7.81%   |
| Realtek Semiconductor         | 4         | 6.25%   |
| Syntek                        | 2         | 3.13%   |
| Sonix Technology              | 1         | 1.56%   |
| Ricoh                         | 1         | 1.56%   |
| Quanta                        | 1         | 1.56%   |
| Luxvisions Innotech Limited   | 1         | 1.56%   |
| Logitech                      | 1         | 1.56%   |
| Lite-On Technology            | 1         | 1.56%   |
| Intel                         | 1         | 1.56%   |
| Genesys Logic                 | 1         | 1.56%   |
| DigiTech                      | 1         | 1.56%   |
| Alcor Micro                   | 1         | 1.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 5         | 7.69%   |
| Microdia Integrated_Webcam_HD                 | 4         | 6.15%   |
| Acer Integrated Camera                        | 4         | 6.15%   |
| Sunplus Laptop_Integrated_Webcam_FHD          | 3         | 4.62%   |
| Realtek Integrated_Webcam_HD                  | 3         | 4.62%   |
| IMC Networks EasyCamera                       | 3         | 4.62%   |
| Sunplus Integrated_Webcam_HD                  | 2         | 3.08%   |
| Microdia Integrated Webcam                    | 2         | 3.08%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 2         | 3.08%   |
| IMC Networks USB2.0 HD UVC WebCam             | 2         | 3.08%   |
| Chicony USB2.0 VGA UVC WebCam                 | 2         | 3.08%   |
| Chicony Lenovo Integrated Camera (0.3MP)      | 2         | 3.08%   |
| Chicony HP HD Camera                          | 2         | 3.08%   |
| Syntek Integrated Camera                      | 1         | 1.54%   |
| Syntek EasyCamera                             | 1         | 1.54%   |
| Sunplus Laptop Integrated Webcam HD           | 1         | 1.54%   |
| Sunplus HP HD Webcam [Fixed]                  | 1         | 1.54%   |
| Sunplus HD WebCam                             | 1         | 1.54%   |
| Sonix USB2.0 HD UVC WebCam                    | 1         | 1.54%   |
| Ricoh Integrated Webcam                       | 1         | 1.54%   |
| Realtek Integrated Webcam HD                  | 1         | 1.54%   |
| Quanta VGA WebCam                             | 1         | 1.54%   |
| Microdia Laptop_Integrated_Webcam_HD          | 1         | 1.54%   |
| Luxvisions Innotech Limited Integrated Camera | 1         | 1.54%   |
| Logitech HD Pro Webcam C920                   | 1         | 1.54%   |
| Lite-On HP Wide Vision HD Camera              | 1         | 1.54%   |
| Intel RealSense 3D Camera (Front F200)        | 1         | 1.54%   |
| IMC Networks USB2.0 HD IR UVC WebCam          | 1         | 1.54%   |
| IMC Networks Integrated Webcam                | 1         | 1.54%   |
| IMC Networks HP TrueVision HD Camera          | 1         | 1.54%   |
| IMC Networks HD Camera                        | 1         | 1.54%   |
| Genesys Logic Camera                          | 1         | 1.54%   |
| DigiTech WebCam SCB-0350M                     | 1         | 1.54%   |
| Chicony USB2.0 HD UVC WebCam                  | 1         | 1.54%   |
| Chicony USB 2.0 Camera                        | 1         | 1.54%   |
| Chicony LG Camera                             | 1         | 1.54%   |
| Chicony HD WebCam                             | 1         | 1.54%   |
| Chicony Chicony USB2.0 Camera                 | 1         | 1.54%   |
| Chicony Camera                                | 1         | 1.54%   |
| Alcor Micro USB 2.0 Camera                    | 1         | 1.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 5         | 55.56%  |
| Validity Sensors           | 3         | 33.33%  |
| Shenzhen Goodix Technology | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 22.22%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 2         | 22.22%  |
| Validity Sensors VFS5011 Fingerprint Reader               | 1         | 11.11%  |
| Validity Sensors VFS 5011 fingerprint sensor              | 1         | 11.11%  |
| Validity Sensors Synaptics WBDI                           | 1         | 11.11%  |
| Shenzhen Goodix Fingerprint Reader                        | 1         | 11.11%  |
| Unknown                                                   | 1         | 11.11%  |

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
| 2     | 30        | 34.48%  |
| 1     | 30        | 34.48%  |
| 3     | 17        | 19.54%  |
| 0     | 5         | 5.75%   |
| 4     | 4         | 4.6%    |
| 5     | 1         | 1.15%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 62        | 42.47%  |
| Bluetooth                | 32        | 21.92%  |
| Net/wireless             | 17        | 11.64%  |
| Card reader              | 12        | 8.22%   |
| Firewire controller      | 9         | 6.16%   |
| Fingerprint reader       | 8         | 5.48%   |
| Storage                  | 2         | 1.37%   |
| Net/ethernet             | 2         | 1.37%   |
| Sound                    | 1         | 0.68%   |
| Network                  | 1         | 0.68%   |

