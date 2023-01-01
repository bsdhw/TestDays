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

Total: 114

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | IdeaPad 330-15IKB 81DE      | [956499202e](https://bsd-hardware.info/?probe=956499202e) | Dec 30, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [883dbf15e4](https://bsd-hardware.info/?probe=883dbf15e4) | Dec 25, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [527bf6bbe4](https://bsd-hardware.info/?probe=527bf6bbe4) | Dec 22, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [babe4bb620](https://bsd-hardware.info/?probe=babe4bb620) | Dec 13, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0Y40... | [ce2b20b3a9](https://bsd-hardware.info/?probe=ce2b20b3a9) | Dec 13, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0Y40... | [7463e05c88](https://bsd-hardware.info/?probe=7463e05c88) | Dec 12, 2022 |
| Acer          | Swift SF114-34              | [2c560bad00](https://bsd-hardware.info/?probe=2c560bad00) | Dec 05, 2022 |
| Google        | Lick                        | [9eb2abcdcc](https://bsd-hardware.info/?probe=9eb2abcdcc) | Dec 03, 2022 |
| Google        | Lars                        | [4130b19cfa](https://bsd-hardware.info/?probe=4130b19cfa) | Dec 03, 2022 |
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
| amd64 | 92        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| KDE5       | 20        | 21.74%  |
| XFCE       | 15        | 16.3%   |
| GNOME      | 15        | 16.3%   |
| Console    | 13        | 14.13%  |
| TWM        | 8         | 8.7%    |
| MATE       | 5         | 5.43%   |
| i3         | 5         | 5.43%   |
| Openbox    | 4         | 4.35%   |
| Cinnamon   | 2         | 2.17%   |
| X-Cinnamon | 1         | 1.09%   |
| LXQt       | 1         | 1.09%   |
| LXDE       | 1         | 1.09%   |
| IceWM      | 1         | 1.09%   |
| dwm        | 1         | 1.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 74        | 80.43%  |
| Console | 13        | 14.13%  |
| Wayland | 5         | 5.43%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 33        | 35.87%  |
| SDDM    | 24        | 26.09%  |
| SLiM    | 13        | 14.13%  |
| GDM     | 11        | 11.96%  |
| XDM     | 6         | 6.52%   |
| LightDM | 4         | 4.35%   |
| PCDM    | 1         | 1.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| C               | 65        | 69.89%  |
| en_US           | 14        | 15.05%  |
| zh_CN           | 4         | 4.3%    |
| ru_RU           | 3         | 3.23%   |
| Unknown         | 3         | 3.23%   |
| fr_FR           | 1         | 1.08%   |
| es_ES           | 1         | 1.08%   |
| en_US.ISO8859-1 | 1         | 1.08%   |
| en_AU           | 1         | 1.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 75        | 81.52%  |
| BIOS | 17        | 18.48%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Zfs  | 63        | 67.74%  |
| Ufs  | 30        | 32.26%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 84        | 91.3%   |
| MBR     | 6         | 6.52%   |
| BSD     | 1         | 1.09%   |
| Unknown | 1         | 1.09%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 26        | 28.26%  |
| Dell                | 24        | 26.09%  |
| ASUSTek Computer    | 10        | 10.87%  |
| Hewlett-Packard     | 7         | 7.61%   |
| Acer                | 4         | 4.35%   |
| Google              | 3         | 3.26%   |
| TUXEDO              | 2         | 2.17%   |
| Toshiba             | 2         | 2.17%   |
| System76            | 2         | 2.17%   |
| Samsung Electronics | 2         | 2.17%   |
| Unknown             | 2         | 2.17%   |
| Sony                | 1         | 1.09%   |
| Notebook            | 1         | 1.09%   |
| MSI                 | 1         | 1.09%   |
| LG Electronics      | 1         | 1.09%   |
| GPD                 | 1         | 1.09%   |
| Fujitsu Siemens     | 1         | 1.09%   |
| Fujitsu             | 1         | 1.09%   |
| Apple               | 1         | 1.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| HP EliteBook 850 G7 Notebook PC             | 2         | 2.17%   |
| Google Peppy                                | 2         | 2.17%   |
| Dell Precision M4500                        | 2         | 2.17%   |
| Unknown                                     | 2         | 2.17%   |
| TUXEDO InfinityBook13V3                     | 1         | 1.09%   |
| TUXEDO Aura 15 Gen1                         | 1         | 1.09%   |
| Toshiba Satellite L305D                     | 1         | 1.09%   |
| Toshiba Satellite A300                      | 1         | 1.09%   |
| System76 Gazelle                            | 1         | 1.09%   |
| System76 Galago Pro                         | 1         | 1.09%   |
| Sony VGN-NS21M_S                            | 1         | 1.09%   |
| Samsung R530/R730/R540                      | 1         | 1.09%   |
| Samsung 750TDA                              | 1         | 1.09%   |
| Notebook N7x0WU                             | 1         | 1.09%   |
| MSI GF63 Thin 9SC                           | 1         | 1.09%   |
| LG 17Z990-R.AAC9U1                          | 1         | 1.09%   |
| Lenovo XiaoXinPro-13API 2019 81XD           | 1         | 1.09%   |
| Lenovo ThinkPad X270 20HMCTO1WW             | 1         | 1.09%   |
| Lenovo ThinkPad X260 20F6S0KA00             | 1         | 1.09%   |
| Lenovo ThinkPad X250 20CMS0FA00             | 1         | 1.09%   |
| Lenovo ThinkPad X220 4286CTO                | 1         | 1.09%   |
| Lenovo ThinkPad X13 Gen 1 20UF000QRT        | 1         | 1.09%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TKS0QB00 | 1         | 1.09%   |
| Lenovo ThinkPad X1 Carbon Gen 10 21CBCTO1WW | 1         | 1.09%   |
| Lenovo ThinkPad W520 4282AD4                | 1         | 1.09%   |
| Lenovo ThinkPad T480 20L6SB2N00             | 1         | 1.09%   |
| Lenovo ThinkPad T480 20L6S29E0T             | 1         | 1.09%   |
| Lenovo ThinkPad T440p 20AWS0Y40T            | 1         | 1.09%   |
| Lenovo ThinkPad T420s 41732AU               | 1         | 1.09%   |
| Lenovo ThinkPad T420 4236C92                | 1         | 1.09%   |
| Lenovo ThinkPad T14 Gen 1 20S0CTO1WW        | 1         | 1.09%   |
| Lenovo ThinkPad L420 7854CTO                | 1         | 1.09%   |
| Lenovo ThinkPad L420 7829WDY                | 1         | 1.09%   |
| Lenovo ThinkPad E490 20N8CTO1WW             | 1         | 1.09%   |
| Lenovo Legion Y530-15ICH 81FV               | 1         | 1.09%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5            | 1         | 1.09%   |
| Lenovo IdeaPad 330-15IKB 81DE               | 1         | 1.09%   |
| Lenovo IdeaPad 330-15ARR 81D2               | 1         | 1.09%   |
| Lenovo IdeaPad 3 15ALC6 82KU                | 1         | 1.09%   |
| Lenovo IdeaPad 130-15AST 81H5               | 1         | 1.09%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 17        | 18.48%  |
| Dell Latitude           | 9         | 9.78%   |
| Lenovo IdeaPad          | 6         | 6.52%   |
| Dell Precision          | 5         | 5.43%   |
| Dell Inspiron           | 5         | 5.43%   |
| ASUS ZenBook            | 4         | 4.35%   |
| ASUS VivoBook           | 3         | 3.26%   |
| Toshiba Satellite       | 2         | 2.17%   |
| HP ProBook              | 2         | 2.17%   |
| HP EliteBook            | 2         | 2.17%   |
| Google Peppy            | 2         | 2.17%   |
| Dell Vostro             | 2         | 2.17%   |
| Acer Aspire             | 2         | 2.17%   |
| Unknown                 | 2         | 2.17%   |
| TUXEDO InfinityBook13V3 | 1         | 1.09%   |
| TUXEDO Aura             | 1         | 1.09%   |
| System76 Gazelle        | 1         | 1.09%   |
| System76 Galago         | 1         | 1.09%   |
| Sony VGN-NS21M          | 1         | 1.09%   |
| Samsung R530            | 1         | 1.09%   |
| Samsung 750TDA          | 1         | 1.09%   |
| Notebook N7x0WU         | 1         | 1.09%   |
| MSI GF63                | 1         | 1.09%   |
| LG 17Z990-R.AAC9U1      | 1         | 1.09%   |
| Lenovo XiaoXinPro-13API | 1         | 1.09%   |
| Lenovo Legion           | 1         | 1.09%   |
| Lenovo G40-45           | 1         | 1.09%   |
| HP Pavilion             | 1         | 1.09%   |
| HP Laptop               | 1         | 1.09%   |
| HP ENVY                 | 1         | 1.09%   |
| GPD MicroPC             | 1         | 1.09%   |
| Google Lars             | 1         | 1.09%   |
| Fujitsu Siemens AMILO   | 1         | 1.09%   |
| Fujitsu LIFEBOOK        | 1         | 1.09%   |
| Dell XPS                | 1         | 1.09%   |
| Dell Studio             | 1         | 1.09%   |
| Dell G5                 | 1         | 1.09%   |
| ASUS X455LJ             | 1         | 1.09%   |
| ASUS X441UV             | 1         | 1.09%   |
| ASUS 1001P              | 1         | 1.09%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2022 | 14        | 15.22%  |
| 2020 | 13        | 14.13%  |
| 2021 | 12        | 13.04%  |
| 2019 | 9         | 9.78%   |
| 2018 | 8         | 8.7%    |
| 2016 | 6         | 6.52%   |
| 2012 | 6         | 6.52%   |
| 2011 | 6         | 6.52%   |
| 2015 | 5         | 5.43%   |
| 2010 | 4         | 4.35%   |
| 2017 | 2         | 2.17%   |
| 2013 | 2         | 2.17%   |
| 2009 | 2         | 2.17%   |
| 2008 | 2         | 2.17%   |
| 2014 | 1         | 1.09%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 92        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 88        | 95.65%  |
| Yes  | 4         | 4.35%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 35        | 38.04%  |
| 16.01-24.0  | 29        | 31.52%  |
| 4.01-8.0    | 15        | 16.3%   |
| 32.01-64.0  | 6         | 6.52%   |
| 64.01-256.0 | 3         | 3.26%   |
| 24.01-32.0  | 2         | 2.17%   |
| 2.01-3.0    | 2         | 2.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 37        | 40.22%  |
| 0.51-1.0  | 28        | 30.43%  |
| 1.01-2.0  | 19        | 20.65%  |
| 2.01-3.0  | 7         | 7.61%   |
| 8.01-16.0 | 1         | 1.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 68        | 73.91%  |
| 2      | 19        | 20.65%  |
| 0      | 4         | 4.35%   |
| 3      | 1         | 1.09%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 66        | 71.74%  |
| Yes       | 26        | 28.26%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 63        | 68.48%  |
| No        | 29        | 31.52%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 91        | 98.91%  |
| No        | 1         | 1.09%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 68        | 73.91%  |
| No        | 24        | 26.09%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 20        | 21.51%  |
| Russia      | 9         | 9.68%   |
| France      | 6         | 6.45%   |
| China       | 6         | 6.45%   |
| India       | 5         | 5.38%   |
| UK          | 4         | 4.3%    |
| Spain       | 3         | 3.23%   |
| Japan       | 3         | 3.23%   |
| Austria     | 3         | 3.23%   |
| Turkey      | 2         | 2.15%   |
| Thailand    | 2         | 2.15%   |
| Philippines | 2         | 2.15%   |
| Netherlands | 2         | 2.15%   |
| Italy       | 2         | 2.15%   |
| Germany     | 2         | 2.15%   |
| Czechia     | 2         | 2.15%   |
| Canada      | 2         | 2.15%   |
| Venezuela   | 1         | 1.08%   |
| Uruguay     | 1         | 1.08%   |
| South Korea | 1         | 1.08%   |
| Slovenia    | 1         | 1.08%   |
| Poland      | 1         | 1.08%   |
| Norway      | 1         | 1.08%   |
| Mexico      | 1         | 1.08%   |
| Malaysia    | 1         | 1.08%   |
| Lithuania   | 1         | 1.08%   |
| Israel      | 1         | 1.08%   |
| Hong Kong   | 1         | 1.08%   |
| Guadeloupe  | 1         | 1.08%   |
| Greece      | 1         | 1.08%   |
| Finland     | 1         | 1.08%   |
| Bulgaria    | 1         | 1.08%   |
| Belarus     | 1         | 1.08%   |
| Australia   | 1         | 1.08%   |
| Argentina   | 1         | 1.08%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 5         | 5.38%   |
| Vienna            | 3         | 3.23%   |
| Paris             | 2         | 2.15%   |
| Carry-le-Rouet    | 2         | 2.15%   |
| Brno              | 2         | 2.15%   |
| Barcelona         | 2         | 2.15%   |
| Zhumadian         | 1         | 1.08%   |
| Yangcheon-gu      | 1         | 1.08%   |
| Xiamen            | 1         | 1.08%   |
| Xi'an             | 1         | 1.08%   |
| Woerdense Verlaat | 1         | 1.08%   |
| Wheatland         | 1         | 1.08%   |
| Vilnius           | 1         | 1.08%   |
| Turku             | 1         | 1.08%   |
| Trivandrum        | 1         | 1.08%   |
| Tlalnepantla      | 1         | 1.08%   |
| Thousand Oaks     | 1         | 1.08%   |
| Thessaloniki      | 1         | 1.08%   |
| Tel Aviv          | 1         | 1.08%   |
| Taito             | 1         | 1.08%   |
| Stratford         | 1         | 1.08%   |
| St Petersburg     | 1         | 1.08%   |
| Shinjuku          | 1         | 1.08%   |
| Shah Alam         | 1         | 1.08%   |
| Sandefjord        | 1         | 1.08%   |
| San Pablo City    | 1         | 1.08%   |
| San Antonio       | 1         | 1.08%   |
| Samokov           | 1         | 1.08%   |
| Riverside         | 1         | 1.08%   |
| Queens            | 1         | 1.08%   |
| Qinnan            | 1         | 1.08%   |
| Ozersk            | 1         | 1.08%   |
| Oswego            | 1         | 1.08%   |
| Omaha             | 1         | 1.08%   |
| North York        | 1         | 1.08%   |
| Newbury Park      | 1         | 1.08%   |
| New York          | 1         | 1.08%   |
| New Delhi         | 1         | 1.08%   |
| Nakano            | 1         | 1.08%   |
| Munich            | 1         | 1.08%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 23        | 25     | 21.9%   |
| Samsung Electronics | 18        | 19     | 17.14%  |
| Kingston            | 8         | 9      | 7.62%   |
| Seagate             | 7         | 8      | 6.67%   |
| Crucial             | 7         | 8      | 6.67%   |
| Toshiba             | 5         | 5      | 4.76%   |
| SK hynix            | 5         | 5      | 4.76%   |
| Transcend           | 3         | 3      | 2.86%   |
| KIOXIA              | 3         | 3      | 2.86%   |
| Hitachi             | 3         | 3      | 2.86%   |
| A-DATA Technology   | 3         | 6      | 2.86%   |
| Silicon Motion      | 2         | 2      | 1.9%    |
| SanDisk             | 2         | 2      | 1.9%    |
| Gigabyte Technology | 2         | 2      | 1.9%    |
| UMIS                | 1         | 1      | 0.95%   |
| SSSTC               | 1         | 1      | 0.95%   |
| PNY                 | 1         | 1      | 0.95%   |
| Micron Technology   | 1         | 1      | 0.95%   |
| Lexar               | 1         | 2      | 0.95%   |
| Lenovo              | 1         | 1      | 0.95%   |
| Intel               | 1         | 1      | 0.95%   |
| Hikvision           | 1         | 1      | 0.95%   |
| Hewlett-Packard     | 1         | 1      | 0.95%   |
| EAGET               | 1         | 1      | 0.95%   |
| CFD                 | 1         | 1      | 0.95%   |
| BR                  | 1         | 1      | 0.95%   |
| BIWIN               | 1         | 1      | 0.95%   |
| Apple               | 1         | 1      | 0.95%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| WDC WDS100T2B0C-00PXH0 1TB              | 2         | 1.82%   |
| WDC WD3200BPVT-80JJ5T0 320GB            | 2         | 1.82%   |
| WDC PC SN530 SDBPNPZ-256G-1014 256GB    | 2         | 1.82%   |
| SK hynix BC511 HFM512GDJTNI-82A0A 512GB | 2         | 1.82%   |
| Samsung SSD 970 EVO Plus 2TB            | 2         | 1.82%   |
| KIOXIA KBG40ZNS512G NVMe 512GB          | 2         | 1.82%   |
| Kingston SA400S37240G 240GB             | 2         | 1.82%   |
| Crucial CT1000MX500SSD1 1TB             | 2         | 1.82%   |
| WDC WDS500G3X0C-00SJG0 500GB            | 1         | 0.91%   |
| WDC WDS480G2G0A-00JH30 480GB            | 1         | 0.91%   |
| WDC WDS250G2B0B-00YS70 250GB            | 1         | 0.91%   |
| WDC WDS240G2G0A-00JH30 240GB            | 1         | 0.91%   |
| WDC WDS120G2G0B-00EPW0 120GB            | 1         | 0.91%   |
| WDC WD3200BPVT-22JJ5T0 320GB            | 1         | 0.91%   |
| WDC WD3200BEKT-60PVMT0 320GB            | 1         | 0.91%   |
| WDC WD2500BEVT-24A23T0 250GB            | 1         | 0.91%   |
| WDC WD20SPZX-00UA7T0 2TB                | 1         | 0.91%   |
| WDC WD1600BEVT-80A23T0 160GB            | 1         | 0.91%   |
| WDC WD1600BEVT-75ZCT2 160GB             | 1         | 0.91%   |
| WDC WD1600BEVT-22ZCT0 160GB             | 1         | 0.91%   |
| WDC WD10SPZX-75Z10T3 1TB                | 1         | 0.91%   |
| WDC WD10SPZX-17Z10T1 1TB                | 1         | 0.91%   |
| WDC WD10JPVX-22JC3T0 1TB                | 1         | 0.91%   |
| WDC WD10JPCX-24UE4T0 1TB                | 1         | 0.91%   |
| WDC WD10EZEX-60WN4A0 1TB                | 1         | 0.91%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB      | 1         | 0.91%   |
| WDC PC SN530 NVMe 256GB                 | 1         | 0.91%   |
| UMIS RPJTJ256MEE1OWX 256GB              | 1         | 0.91%   |
| Transcend TS256GMTS430S 256GB           | 1         | 0.91%   |
| Transcend TS1TMTE110S 1TB               | 1         | 0.91%   |
| Transcend TS128GMTS430S 128GB           | 1         | 0.91%   |
| Toshiba MQ04ABF100 1TB                  | 1         | 0.91%   |
| Toshiba MQ01ABF050 500GB                | 1         | 0.91%   |
| Toshiba MQ01ABD100 1TB                  | 1         | 0.91%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB     | 1         | 0.91%   |
| Toshiba KBG30ZMT512G 512GB              | 1         | 0.91%   |
| SSSTC CL1-8D256-HP 256GB                | 1         | 0.91%   |
| SK hynix SKHynix_HFS256GDE9X081N 256GB  | 1         | 0.91%   |
| SK hynix HFM512GD3JX013N 512GB          | 1         | 0.91%   |
| SK hynix BC501 NVMe 512GB               | 1         | 0.91%   |

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
| Samsung Electronics | 6         | 6      | 15.38%  |
| Crucial             | 6         | 7      | 15.38%  |
| Kingston            | 5         | 6      | 12.82%  |
| WDC                 | 4         | 4      | 10.26%  |
| A-DATA Technology   | 3         | 6      | 7.69%   |
| Transcend           | 2         | 2      | 5.13%   |
| SanDisk             | 2         | 2      | 5.13%   |
| Toshiba             | 1         | 1      | 2.56%   |
| PNY                 | 1         | 1      | 2.56%   |
| Lexar               | 1         | 2      | 2.56%   |
| Lenovo              | 1         | 1      | 2.56%   |
| Hikvision           | 1         | 1      | 2.56%   |
| Hewlett-Packard     | 1         | 1      | 2.56%   |
| Gigabyte Technology | 1         | 1      | 2.56%   |
| CFD                 | 1         | 1      | 2.56%   |
| BR                  | 1         | 1      | 2.56%   |
| BIWIN               | 1         | 1      | 2.56%   |
| Apple               | 1         | 1      | 2.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 40        | 42     | 40%     |
| SSD  | 35        | 45     | 35%     |
| HDD  | 25        | 28     | 25%     |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 57        | 73     | 58.76%  |
| NVMe | 40        | 42     | 41.24%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 38        | 48     | 63.33%  |
| 0.51-1.0   | 18        | 21     | 30%     |
| 1.01-2.0   | 4         | 4      | 6.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 36        | 39.13%  |
| 251-500    | 23        | 25%     |
| 501-1000   | 16        | 17.39%  |
| 51-100     | 8         | 8.7%    |
| 21-50      | 4         | 4.35%   |
| 1001-2000  | 4         | 4.35%   |
| 1-20       | 1         | 1.09%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 71        | 76.34%  |
| 21-50   | 13        | 13.98%  |
| 101-250 | 4         | 4.3%    |
| 51-100  | 4         | 4.3%    |
| 251-500 | 1         | 1.08%   |

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
| Works    | 73        | 92     | 81.11%  |
| Malfunc  | 15        | 20     | 16.67%  |
| Detected | 2         | 3      | 2.22%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 56        | 51.38%  |
| Samsung Electronics            | 13        | 11.93%  |
| AMD                            | 11        | 10.09%  |
| SanDisk                        | 8         | 7.34%   |
| SK hynix                       | 4         | 3.67%   |
| Silicon Motion                 | 3         | 2.75%   |
| KIOXIA                         | 3         | 2.75%   |
| Kingston Technology Company    | 3         | 2.75%   |
| Union Memory (Shenzhen)        | 1         | 0.92%   |
| Transcend                      | 1         | 0.92%   |
| Toshiba                        | 1         | 0.92%   |
| Solid State Storage Technology | 1         | 0.92%   |
| Phison Electronics             | 1         | 0.92%   |
| Nvidia                         | 1         | 0.92%   |
| Micron/Crucial Technology      | 1         | 0.92%   |
| Micron Technology              | 1         | 0.92%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 10        | 8.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 9         | 7.96%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 7         | 6.19%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 6.19%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 7         | 6.19%   |
| Unknown                                                                        | 6         | 5.31%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 3.54%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 3.54%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 3.54%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 3         | 2.65%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 3         | 2.65%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 2.65%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 3         | 2.65%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 2.65%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 2         | 1.77%   |
| SK hynix BC511                                                                 | 2         | 1.77%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 1.77%   |
| SanDisk unknown                                                                | 2         | 1.77%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 1.77%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 1.77%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.77%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 1.77%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2         | 1.77%   |
| Toshiba BG3 NVMe SSD Controller                                                | 1         | 0.88%   |
| SanDisk WD Blue SN570 NVMe SSD                                                 | 1         | 0.88%   |
| Samsung SM951 AHCI                                                             | 1         | 0.88%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1         | 0.88%   |
| Samsung NVMe SSD Controller 980                                                | 1         | 0.88%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1         | 0.88%   |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 0.88%   |
| Kingston Company SNVS2000G [NV1 NVMe PCIe SSD 2TB]                             | 1         | 0.88%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 1         | 0.88%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 0.88%   |
| Intel SSD 660P Series                                                          | 1         | 0.88%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 0.88%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 0.88%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 1         | 0.88%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 0.88%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 0.88%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 1         | 0.88%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 60        | 54.55%  |
| NVMe | 39        | 35.45%  |
| RAID | 9         | 8.18%   |
| IDE  | 2         | 1.82%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 77        | 83.7%   |
| AMD    | 15        | 16.3%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz       | 4         | 4.35%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 3         | 3.26%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 3         | 3.26%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 3         | 3.26%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 3         | 3.26%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 2         | 2.17%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 2         | 2.17%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 2         | 2.17%   |
| Intel Core i5-10310U CPU @ 1.70GHz      | 2         | 2.17%   |
| Intel Core i5 CPU M 560 @ 2.67GH        | 2         | 2.17%   |
| AMD Ryzen 3 5300U with Radeon Graphics  | 2         | 2.17%   |
| Intel Pentium Silver N6000 @ 1.10GHz    | 1         | 1.09%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz  | 1         | 1.09%   |
| Intel Genuine CPU                       | 1         | 1.09%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 1         | 1.09%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 1.09%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 1         | 1.09%   |
| Intel Core i7-4980HQ CPU @ 2.80GHz      | 1         | 1.09%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz      | 1         | 1.09%   |
| Intel Core i7-4712MQ CPU @ 2.30GHz      | 1         | 1.09%   |
| Intel Core i7-4610M CPU @ 3.00GHz       | 1         | 1.09%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 1         | 1.09%   |
| Intel Core i7-3632QM CPU @ 2.20GHz      | 1         | 1.09%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 1         | 1.09%   |
| Intel Core i7-3537U CPU @ 2.00GHz       | 1         | 1.09%   |
| Intel Core i7-2760QM CPU @ 2.40GHz      | 1         | 1.09%   |
| Intel Core i7-2640M CPU @ 2.80GHz       | 1         | 1.09%   |
| Intel Core i7-2620M CPU @ 2.70GHz       | 1         | 1.09%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 1         | 1.09%   |
| Intel Core i7-10610U CPU @ 1.80GHz      | 1         | 1.09%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 1         | 1.09%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 1         | 1.09%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 1         | 1.09%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 1         | 1.09%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz      | 1         | 1.09%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 1         | 1.09%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 1         | 1.09%   |
| Intel Core i5-2540M CPU @ 2.60GHz       | 1         | 1.09%   |
| Intel Core i5-2540M CPU @ 2.60GH        | 1         | 1.09%   |
| Intel Core i5-2520M CPU @ 2.50GH        | 1         | 1.09%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i7        | 28        | 30.43%  |
| Intel Core i5        | 23        | 25%     |
| Other                | 7         | 7.61%   |
| Intel Celeron        | 7         | 7.61%   |
| Intel Core i3        | 4         | 4.35%   |
| Intel Core 2 Duo     | 4         | 4.35%   |
| AMD Ryzen 3          | 4         | 4.35%   |
| AMD Ryzen 7          | 3         | 3.26%   |
| AMD Ryzen 5          | 3         | 3.26%   |
| AMD A8               | 2         | 2.17%   |
| Intel Pentium Silver | 1         | 1.09%   |
| Intel Pentium Dual   | 1         | 1.09%   |
| Intel Genuine        | 1         | 1.09%   |
| Intel Atom           | 1         | 1.09%   |
| AMD Ryzen 7 PRO      | 1         | 1.09%   |
| AMD E2               | 1         | 1.09%   |
| AMD Athlon X2        | 1         | 1.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 38        | 41.3%   |
| 4       | 35        | 38.04%  |
| 8       | 7         | 7.61%   |
| 6       | 5         | 5.43%   |
| 16      | 3         | 3.26%   |
| Unknown | 2         | 2.17%   |
| 20      | 1         | 1.09%   |
| 1       | 1         | 1.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 92        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 62        | 67.39%  |
| 1       | 28        | 30.43%  |
| Unknown | 2         | 2.17%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 22        | 23.91%  |
| SandyBridge     | 9         | 9.78%   |
| Haswell         | 7         | 7.61%   |
| Unknown         | 7         | 7.61%   |
| Skylake         | 6         | 6.52%   |
| TigerLake       | 5         | 5.43%   |
| IvyBridge       | 5         | 5.43%   |
| Broadwell       | 4         | 4.35%   |
| Zen+            | 3         | 3.26%   |
| Westmere        | 3         | 3.26%   |
| Core            | 3         | 3.26%   |
| Zen 2           | 2         | 2.17%   |
| Zen             | 2         | 2.17%   |
| Puma            | 2         | 2.17%   |
| Penryn          | 2         | 2.17%   |
| Goldmont plus   | 2         | 2.17%   |
| CometLake       | 2         | 2.17%   |
| Zen 3           | 1         | 1.09%   |
| K8 & K10 hybrid | 1         | 1.09%   |
| IceLake         | 1         | 1.09%   |
| Goldmont        | 1         | 1.09%   |
| Excavator       | 1         | 1.09%   |
| Bonnell         | 1         | 1.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 72        | 63.72%  |
| AMD    | 21        | 18.58%  |
| Nvidia | 20        | 17.7%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 9         | 7.76%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 5         | 4.31%   |
| Intel UHD Graphics 620                                                    | 5         | 4.31%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 5         | 4.31%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 5         | 4.31%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 4         | 3.45%   |
| Intel HD Graphics 5500                                                    | 4         | 3.45%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 4         | 3.45%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 4         | 3.45%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 3         | 2.59%   |
| Intel HD Graphics 620                                                     | 3         | 2.59%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 3         | 2.59%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 3         | 2.59%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 3         | 2.59%   |
| AMD Lucienne                                                              | 3         | 2.59%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 2         | 1.72%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 2         | 1.72%   |
| Nvidia GT216GLM [Quadro FX 880M]                                          | 2         | 1.72%   |
| Nvidia GP108BM [GeForce MX250]                                            | 2         | 1.72%   |
| Intel JasperLake [UHD Graphics]                                           | 2         | 1.72%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 1.72%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 2         | 1.72%   |
| AMD Renoir                                                                | 2         | 1.72%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 1.72%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                       | 2         | 1.72%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 0.86%   |
| Nvidia TU117M                                                             | 1         | 0.86%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 0.86%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 0.86%   |
| Nvidia GM108M [GeForce MX130]                                             | 1         | 0.86%   |
| Nvidia GM108M [GeForce 920MX]                                             | 1         | 0.86%   |
| Nvidia GM107GLM [Quadro M1000M]                                           | 1         | 0.86%   |
| Nvidia GK208BM [GeForce 920M]                                             | 1         | 0.86%   |
| Nvidia GK107M [GeForce GT 650M]                                           | 1         | 0.86%   |
| Nvidia GF108GLM [NVS 5200M]                                               | 1         | 0.86%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                        | 1         | 0.86%   |
| Nvidia G98M [GeForce 9200M GS]                                            | 1         | 0.86%   |
| Nvidia C79 [GeForce 9400M G]                                              | 1         | 0.86%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 1         | 0.86%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 1         | 0.86%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 48        | 52.17%  |
| Intel + Nvidia | 14        | 15.22%  |
| 1 x AMD        | 13        | 14.13%  |
| 2 x Intel      | 5         | 5.43%   |
| Intel + AMD    | 5         | 5.43%   |
| 1 x Nvidia     | 3         | 3.26%   |
| AMD + Nvidia   | 2         | 2.17%   |
| 2 x Nvidia     | 1         | 1.09%   |
| 2 x AMD        | 1         | 1.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 84        | 91.3%   |
| Proprietary | 8         | 8.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 78        | 84.78%  |
| 0.51-1.0   | 5         | 5.43%   |
| 0.01-0.5   | 5         | 5.43%   |
| 1.01-2.0   | 2         | 2.17%   |
| 5.01-6.0   | 1         | 1.09%   |
| 3.01-4.0   | 1         | 1.09%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 15        | 18.29%  |
| BOE                 | 13        | 15.85%  |
| Chimei Innolux      | 11        | 13.41%  |
| AU Optronics        | 11        | 13.41%  |
| Samsung Electronics | 7         | 8.54%   |
| Toshiba             | 2         | 2.44%   |
| Sharp               | 2         | 2.44%   |
| LGD                 | 2         | 2.44%   |
| Lenovo              | 2         | 2.44%   |
| CSO                 | 2         | 2.44%   |
| BenQ                | 2         | 2.44%   |
| YTH                 | 1         | 1.22%   |
| ViewSonic           | 1         | 1.22%   |
| USR                 | 1         | 1.22%   |
| Unknown (XXX)       | 1         | 1.22%   |
| Sceptre Tech        | 1         | 1.22%   |
| Mi                  | 1         | 1.22%   |
| LG Philips          | 1         | 1.22%   |
| JDI                 | 1         | 1.22%   |
| HannStar            | 1         | 1.22%   |
| ASUSTek Computer    | 1         | 1.22%   |
| Apple               | 1         | 1.22%   |
| AOC                 | 1         | 1.22%   |
| Acer                | 1         | 1.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LGD LCD Monitor 1600x900                                              | 2         | 2.44%   |
| LG Display LCD Monitor LGD064C 1920x1080 340x190mm 15.3-inch          | 2         | 2.44%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch      | 2         | 2.44%   |
| BenQ BL2480 BNQ802C 1920x1080 530x300mm 24.0-inch                     | 2         | 2.44%   |
| YTH HS133PC YTH1330 1920x1080 250x220mm 13.1-inch                     | 1         | 1.22%   |
| ViewSonic LCD Monitor VSCD22B 1920x1080 520x290mm 23.4-inch           | 1         | 1.22%   |
| USR LCD Monitor USR0100 1920x1080 510x290mm 23.1-inch                 | 1         | 1.22%   |
| Unknown (XXX) SMART TV XXX2851 3840x2160                              | 1         | 1.22%   |
| Toshiba TV TSB0200 1920x1080 530x300mm 24.0-inch                      | 1         | 1.22%   |
| Toshiba ScreenXpert- TSB8888 1080x2160 60x130mm 5.6-inch              | 1         | 1.22%   |
| Sharp LCD Monitor SHP143E 3840x2160 350x190mm 15.7-inch               | 1         | 1.22%   |
| Sharp LCD Monitor SHP1421 3200x1800 290x170mm 13.2-inch               | 1         | 1.22%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch        | 1         | 1.22%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch     | 1         | 1.22%   |
| Samsung Electronics LS24A40xU SAM71D1 1920x1080 530x300mm 24.0-inch   | 1         | 1.22%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch  | 1         | 1.22%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 330x210mm 15.4-inch  | 1         | 1.22%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 340x190mm 15.3-inch  | 1         | 1.22%   |
| Samsung Electronics LCD Monitor SDC8B4F 1920x1080 340x190mm 15.3-inch | 1         | 1.22%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 290x170mm 13.2-inch | 1         | 1.22%   |
| Mi 27 NFGL XMIB004 1920x1080 600x330mm 27.0-inch                      | 1         | 1.22%   |
| LG Philips LCD Monitor LPL0120 1280x800 330x210mm 15.4-inch           | 1         | 1.22%   |
| LG Display LCD Monitor LGD6E01 1366x768 340x190mm 15.3-inch           | 1         | 1.22%   |
| LG Display LCD Monitor LGD060A 1920x1080 290x170mm 13.2-inch          | 1         | 1.22%   |
| LG Display LCD Monitor LGD05F8 2560x1600 370x230mm 17.2-inch          | 1         | 1.22%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch          | 1         | 1.22%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch          | 1         | 1.22%   |
| LG Display LCD Monitor LGD0408 1920x1080 280x160mm 12.7-inch          | 1         | 1.22%   |
| LG Display LCD Monitor LGD03DD 1366x768 340x190mm 15.3-inch           | 1         | 1.22%   |
| LG Display LCD Monitor LGD0395 1366x768 340x190mm 15.3-inch           | 1         | 1.22%   |
| LG Display LCD Monitor LGD0353 1366x768 350x190mm 15.7-inch           | 1         | 1.22%   |
| LG Display LCD Monitor LGD02EB 1366x768 310x170mm 13.9-inch           | 1         | 1.22%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x170mm 13.9-inch           | 1         | 1.22%   |
| LG Display LCD Monitor LGD02DA 1920x1080 380x210mm 17.1-inch          | 1         | 1.22%   |
| LG Display LCD Monitor LGD02D3 1366x768 280x160mm 12.7-inch           | 1         | 1.22%   |
| Lenovo LEN T32h-20 LEN61F1 2560x1440 700x390mm 31.5-inch              | 1         | 1.22%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch              | 1         | 1.22%   |
| JDI LCD Monitor JDI385A 3840x2160 290x170mm 13.2-inch                 | 1         | 1.22%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch             | 1         | 1.22%   |
| CSO LCD Monitor CSO1400 3840x2160 310x170mm 13.9-inch                 | 1         | 1.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 41        | 52.56%  |
| 1366x768 (WXGA)  | 16        | 20.51%  |
| 3840x2160 (4K)   | 5         | 6.41%   |
| 1600x900 (HD+)   | 4         | 5.13%   |
| 2560x1440 (QHD)  | 3         | 3.85%   |
| 2560x1600        | 2         | 2.56%   |
| 1280x800 (WXGA)  | 2         | 2.56%   |
| 3200x1800 (QHD+) | 1         | 1.28%   |
| 2880x1800        | 1         | 1.28%   |
| 2560x1080        | 1         | 1.28%   |
| 1080x2160        | 1         | 1.28%   |
| 1024x600         | 1         | 1.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 30        | 36.59%  |
| 13      | 26        | 31.71%  |
| 12      | 5         | 6.1%    |
| 27      | 4         | 4.88%   |
| 24      | 4         | 4.88%   |
| 23      | 3         | 3.66%   |
| Unknown | 3         | 3.66%   |
| 17      | 2         | 2.44%   |
| 31      | 1         | 1.22%   |
| 29      | 1         | 1.22%   |
| 11      | 1         | 1.22%   |
| 10      | 1         | 1.22%   |
| 5       | 1         | 1.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 48        | 59.26%  |
| 201-300     | 14        | 17.28%  |
| 501-600     | 10        | 12.35%  |
| 601-700     | 3         | 3.7%    |
| Unknown     | 3         | 3.7%    |
| 351-400     | 2         | 2.47%   |
| 1-100       | 1         | 1.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 60        | 84.51%  |
| 16/10   | 6         | 8.45%   |
| Unknown | 2         | 2.82%   |
| 21/9    | 1         | 1.41%   |
| 11/10   | 1         | 1.41%   |
| 0.46    | 1         | 1.41%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 23        | 28.05%  |
| 81-90          | 20        | 24.39%  |
| 201-250        | 7         | 8.54%   |
| 101-110        | 7         | 8.54%   |
| 71-80          | 6         | 7.32%   |
| 61-70          | 5         | 6.1%    |
| 301-350        | 5         | 6.1%    |
| Unknown        | 3         | 3.66%   |
| 51-60          | 1         | 1.22%   |
| 351-500        | 1         | 1.22%   |
| 41-50          | 1         | 1.22%   |
| 1-40           | 1         | 1.22%   |
| 131-140        | 1         | 1.22%   |
| 121-130        | 1         | 1.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 32        | 40%     |
| 101-120       | 15        | 18.75%  |
| 51-100        | 14        | 17.5%   |
| 161-240       | 11        | 13.75%  |
| More than 240 | 5         | 6.25%   |
| Unknown       | 3         | 3.75%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 56        | 60.87%  |
| 0     | 23        | 25%     |
| 2     | 13        | 14.13%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 57        | 37.25%  |
| Realtek Semiconductor    | 43        | 28.1%   |
| Qualcomm Atheros         | 23        | 15.03%  |
| Broadcom                 | 8         | 5.23%   |
| Ralink Technology        | 3         | 1.96%   |
| Xiaomi                   | 2         | 1.31%   |
| TP-Link                  | 2         | 1.31%   |
| Samsung Electronics      | 2         | 1.31%   |
| MediaTek                 | 2         | 1.31%   |
| Marvell Technology Group | 2         | 1.31%   |
| Google                   | 2         | 1.31%   |
| Sagem                    | 1         | 0.65%   |
| Ralink                   | 1         | 0.65%   |
| Qualcomm                 | 1         | 0.65%   |
| Nvidia                   | 1         | 0.65%   |
| Huawei Technologies      | 1         | 0.65%   |
| HMD Global               | 1         | 0.65%   |
| Arduino SA               | 1         | 0.65%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 23        | 13.22%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 6.9%    |
| Intel Wireless 8265 / 8275                                        | 7         | 4.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 3.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 2.87%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 2.87%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 2.87%   |
| Intel Wireless 7265                                               | 4         | 2.3%    |
| Intel Wi-Fi 6 AX201                                               | 4         | 2.3%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 2.3%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 2.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.72%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 3         | 1.72%   |
| Intel Wireless 8260                                               | 3         | 1.72%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 1.72%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.72%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.15%   |
| Ralink RT5370 Wireless Adapter                                    | 2         | 1.15%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 1.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 1.15%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 1.15%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 1.15%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 1.15%   |
| Intel Wireless-AC 9260                                            | 2         | 1.15%   |
| Intel Wireless 7260                                               | 2         | 1.15%   |
| Intel Wi-Fi 6 AX201 160MHz                                        | 2         | 1.15%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.15%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 1.15%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 1.15%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 2         | 1.15%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 2         | 1.15%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.57%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.57%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1         | 0.57%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.57%   |
| Sagem XG-76NA 802.11bg                                            | 1         | 0.57%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.57%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1         | 0.57%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.57%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 53        | 51.96%  |
| Qualcomm Atheros      | 23        | 22.55%  |
| Realtek Semiconductor | 10        | 9.8%    |
| Broadcom              | 7         | 6.86%   |
| Ralink Technology     | 3         | 2.94%   |
| TP-Link               | 2         | 1.96%   |
| MediaTek              | 2         | 1.96%   |
| Sagem                 | 1         | 0.98%   |
| Ralink                | 1         | 0.98%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 7         | 6.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 4.9%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 4.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 4.9%    |
| Intel Wireless 7265                                                     | 4         | 3.92%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 3.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 3.92%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 3.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 2.94%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 3         | 2.94%   |
| Intel Wireless 8260                                                     | 3         | 2.94%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 2.94%   |
| Ralink RT5370 Wireless Adapter                                          | 2         | 1.96%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 1.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 1.96%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 1.96%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 1.96%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 1.96%   |
| Intel Wireless-AC 9260                                                  | 2         | 1.96%   |
| Intel Wireless 7260                                                     | 2         | 1.96%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 2         | 1.96%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 1.96%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 1.96%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 1.96%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 0.98%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 1         | 0.98%   |
| Sagem XG-76NA 802.11bg                                                  | 1         | 0.98%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.98%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1         | 0.98%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.98%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 0.98%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.98%   |
| Realtek Realtek Bluetooth Adapter                                       | 1         | 0.98%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.98%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 0.98%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.98%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.98%   |
| Qualcomm Atheros AR2427 802.11bg Wireless Network Adapter (PCI-Express) | 1         | 0.98%   |
| Intel Wireless 3160                                                     | 1         | 0.98%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 37        | 52.86%  |
| Intel                    | 19        | 27.14%  |
| Xiaomi                   | 2         | 2.86%   |
| Samsung Electronics      | 2         | 2.86%   |
| Marvell Technology Group | 2         | 2.86%   |
| Google                   | 2         | 2.86%   |
| Broadcom                 | 2         | 2.86%   |
| Qualcomm Atheros         | 1         | 1.43%   |
| Qualcomm                 | 1         | 1.43%   |
| Nvidia                   | 1         | 1.43%   |
| HMD Global               | 1         | 1.43%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 23        | 32.86%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 17.14%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 8.57%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 4.29%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 2.86%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.86%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.43%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 1.43%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.43%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 1.43%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.43%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 1         | 1.43%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.43%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 1.43%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.43%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.43%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.43%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.43%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.43%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.43%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.43%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.43%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 1.43%   |
| HMD Global Nokia 5.3 RNDIS Control RNDIS Ethernet Data            | 1         | 1.43%   |
| Google Nexus/Pixel Device (tether+ debug)                         | 1         | 1.43%   |
| Google Nexus/Pixel Device (tether)                                | 1         | 1.43%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                 | 1         | 1.43%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 1.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 91        | 58.33%  |
| Ethernet | 63        | 40.38%  |
| Modem    | 2         | 1.28%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 52        | 63.41%  |
| Ethernet | 30        | 36.59%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 61        | 66.3%   |
| 1     | 30        | 32.61%  |
| 0     | 1         | 1.09%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 79        | 84.95%  |
| Yes  | 14        | 15.05%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 41        | 57.75%  |
| Qualcomm Atheros Communications | 8         | 11.27%  |
| IMC Networks                    | 4         | 5.63%   |
| Dell                            | 4         | 5.63%   |
| Realtek Semiconductor           | 3         | 4.23%   |
| Foxconn / Hon Hai               | 3         | 4.23%   |
| Lite-On Technology              | 2         | 2.82%   |
| Broadcom                        | 2         | 2.82%   |
| Ralink                          | 1         | 1.41%   |
| Creative Technology             | 1         | 1.41%   |
| Cambridge Silicon Radio         | 1         | 1.41%   |
| Apple                           | 1         | 1.41%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 13        | 18.31%  |
| Intel AX201 Bluetooth                                       | 13        | 18.31%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 8         | 11.27%  |
| Intel AX200 Bluetooth                                       | 3         | 4.23%   |
| Realtek  Bluetooth Adapter                                  | 2         | 2.82%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 2         | 2.82%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 2         | 2.82%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 2         | 2.82%   |
| Dell DW375 Bluetooth Module                                 | 2         | 2.82%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 2.82%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 1         | 1.41%   |
| Ralink RT3290 Bluetooth                                     | 1         | 1.41%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 1.41%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 1.41%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 1.41%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 1.41%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 1.41%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 1.41%   |
| Lite-On Wireless_Device                                     | 1         | 1.41%   |
| Lite-On BCM43142A0 Bluetooth Module                         | 1         | 1.41%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 1.41%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 1.41%   |
| Intel Intel Wireless Bluetooth                              | 1         | 1.41%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 1.41%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 1.41%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 1         | 1.41%   |
| Foxconn / Hon Hai Wireless_Device                           | 1         | 1.41%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 1         | 1.41%   |
| Dell Broadcom BCM20702A0 Bluetooth                          | 1         | 1.41%   |
| Creative Creative Bluetooth Audio W2                        | 1         | 1.41%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 1         | 1.41%   |
| Apple Bluetooth Host Controller                             | 1         | 1.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel           | 76        | 71.03%  |
| AMD             | 17        | 15.89%  |
| Nvidia          | 8         | 7.48%   |
| Plantronics     | 2         | 1.87%   |
| SteelSeries ApS | 1         | 0.93%   |
| Sony            | 1         | 0.93%   |
| Lenovo          | 1         | 0.93%   |
| GN Netcom       | 1         | 0.93%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 13        | 9.92%   |
| AMD Family 17h/19h HD Audio Controller                                     | 11        | 8.4%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 9         | 6.87%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6         | 4.58%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 5         | 3.82%   |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 3.82%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 5         | 3.82%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 3.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 3.82%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 3.05%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 3.05%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 3.05%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 3.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 2.29%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 2.29%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 2.29%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 2.29%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 2.29%   |
| Plantronics Plantronics Blackwire 315.1                                    | 2         | 1.53%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 1.53%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 1.53%   |
| Nvidia GT216 HDMI Audio Controller                                         | 2         | 1.53%   |
| Intel Jasper Lake HD Audio                                                 | 2         | 1.53%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.53%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.53%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 1.53%   |
| AMD FCH Azalia Controller                                                  | 2         | 1.53%   |
| SteelSeries ApS SteelSeries Siberia 350                                    | 1         | 0.76%   |
| Sony UAB-80                                                                | 1         | 0.76%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.76%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.76%   |
| Lenovo Realtek USB Audio                                                   | 1         | 0.76%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 0.76%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 0.76%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 0.76%   |
| Intel Crystal Well HD Audio Controller                                     | 1         | 0.76%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 0.76%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 1         | 0.76%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 0.76%   |
| GN Netcom Jabra SPEAK 510 USB                                              | 1         | 0.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| SK hynix              | 37        | 34.26%  |
| Samsung Electronics   | 27        | 25%     |
| Micron Technology     | 8         | 7.41%   |
| Kingston              | 7         | 6.48%   |
| Crucial               | 5         | 4.63%   |
| Unknown               | 5         | 4.63%   |
| Unknown               | 3         | 2.78%   |
| Elpida                | 3         | 2.78%   |
| Unknown (ABCD)        | 2         | 1.85%   |
| Ramaxel Technology    | 2         | 1.85%   |
| KomputerBay           | 2         | 1.85%   |
| Transcend             | 1         | 0.93%   |
| PNY                   | 1         | 0.93%   |
| Nanya Technology      | 1         | 0.93%   |
| Kingmax Semiconductor | 1         | 0.93%   |
| Corsair               | 1         | 0.93%   |
| Apacer                | 1         | 0.93%   |
| A-DATA Technology     | 1         | 0.93%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                   | 5         | 4.31%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 3         | 2.59%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s                    | 3         | 2.59%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 2         | 1.72%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2133MT/s          | 2         | 1.72%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                             | 2         | 1.72%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s                     | 2         | 1.72%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s                    | 2         | 1.72%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s                    | 2         | 1.72%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s                    | 2         | 1.72%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s                    | 2         | 1.72%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 1600MT/s                     | 2         | 1.72%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 2         | 1.72%   |
| Samsung RAM M471A4G43MB1-CTD 0kB SODIMM DDR4 2667MT/s                     | 2         | 1.72%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s                    | 2         | 1.72%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s                    | 2         | 1.72%   |
| KomputerBay RAM KB_8G_D3_1333_C9 8GB SODIMM DDR3 1334MT/s                 | 2         | 1.72%   |
| Unknown RAM Module 2GB SODIMM DDR2                                        | 1         | 0.86%   |
| Transcend RAM TS2GSH64V1B 16GB SODIMM DDR4 2133MT/s                       | 1         | 0.86%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                              | 1         | 0.86%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 0.86%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 0.86%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 1         | 0.86%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 1         | 0.86%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 0.86%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s                    | 1         | 0.86%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s              | 1         | 0.86%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s                    | 1         | 0.86%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s              | 1         | 0.86%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s                    | 1         | 0.86%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s                   | 1         | 0.86%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s                   | 1         | 0.86%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s                   | 1         | 0.86%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 1         | 0.86%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s                    | 1         | 0.86%   |
| SK hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s            | 1         | 0.86%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s                | 1         | 0.86%   |
| SK hynix RAM H9CCNNN8JTBLAR-NUD 2GB LPDDR3 1867MT/s                       | 1         | 0.86%   |
| SK hynix RAM 161616161616161616161616161616161616 2GB SODIMM DDR2 800MT/s | 1         | 0.86%   |
| SK hynix RAM 080808080808080808080808080808080808 2GB SODIMM DDR2 800MT/s | 1         | 0.86%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 44        | 47.83%  |
| DDR3    | 32        | 34.78%  |
| DDR2    | 6         | 6.52%   |
| LPDDR4  | 5         | 5.43%   |
| LPDDR3  | 3         | 3.26%   |
| LPDDR5  | 1         | 1.09%   |
| Unknown | 1         | 1.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 83        | 89.25%  |
| Row Of Chips | 8         | 8.6%    |
| Chip         | 1         | 1.08%   |
| Unknown      | 1         | 1.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 36        | 37.5%   |
| 4096  | 30        | 31.25%  |
| 16384 | 13        | 13.54%  |
| 2048  | 13        | 13.54%  |
| 32768 | 4         | 4.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 21        | 21.21%  |
| 1600    | 18        | 18.18%  |
| 2400    | 13        | 13.13%  |
| 2667    | 12        | 12.12%  |
| 2133    | 8         | 8.08%   |
| 1334    | 7         | 7.07%   |
| 1333    | 3         | 3.03%   |
| 667     | 3         | 3.03%   |
| 4267    | 2         | 2.02%   |
| 975     | 2         | 2.02%   |
| 800     | 2         | 2.02%   |
| 6400    | 1         | 1.01%   |
| 4266    | 1         | 1.01%   |
| 2666    | 1         | 1.01%   |
| 1867    | 1         | 1.01%   |
| 1866    | 1         | 1.01%   |
| 1067    | 1         | 1.01%   |
| 1066    | 1         | 1.01%   |
| Unknown | 1         | 1.01%   |

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
| Chicony Electronics           | 18        | 26.09%  |
| IMC Networks                  | 12        | 17.39%  |
| Sunplus Innovation Technology | 8         | 11.59%  |
| Microdia                      | 7         | 10.14%  |
| Acer                          | 5         | 7.25%   |
| Realtek Semiconductor         | 4         | 5.8%    |
| Syntek                        | 3         | 4.35%   |
| Luxvisions Innotech Limited   | 2         | 2.9%    |
| Lite-On Technology            | 2         | 2.9%    |
| Sonix Technology              | 1         | 1.45%   |
| Ricoh                         | 1         | 1.45%   |
| Quanta                        | 1         | 1.45%   |
| Logitech                      | 1         | 1.45%   |
| Intel                         | 1         | 1.45%   |
| Genesys Logic                 | 1         | 1.45%   |
| DigiTech                      | 1         | 1.45%   |
| Alcor Micro                   | 1         | 1.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 5         | 7.14%   |
| Microdia Integrated_Webcam_HD                 | 4         | 5.71%   |
| IMC Networks EasyCamera                       | 4         | 5.71%   |
| Acer Integrated Camera                        | 4         | 5.71%   |
| Sunplus Laptop_Integrated_Webcam_FHD          | 3         | 4.29%   |
| Realtek Integrated_Webcam_HD                  | 3         | 4.29%   |
| Syntek EasyCamera                             | 2         | 2.86%   |
| Sunplus Integrated_Webcam_HD                  | 2         | 2.86%   |
| Microdia Integrated Webcam                    | 2         | 2.86%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 2         | 2.86%   |
| IMC Networks USB2.0 HD UVC WebCam             | 2         | 2.86%   |
| Chicony USB2.0 VGA UVC WebCam                 | 2         | 2.86%   |
| Chicony Lenovo Integrated Camera (0.3MP)      | 2         | 2.86%   |
| Chicony HP HD Camera                          | 2         | 2.86%   |
| Chicony HD WebCam                             | 2         | 2.86%   |
| Syntek Integrated Camera                      | 1         | 1.43%   |
| Sunplus Laptop Integrated Webcam HD           | 1         | 1.43%   |
| Sunplus HP HD Webcam [Fixed]                  | 1         | 1.43%   |
| Sunplus HD WebCam                             | 1         | 1.43%   |
| Sonix USB2.0 HD UVC WebCam                    | 1         | 1.43%   |
| Ricoh Integrated Webcam                       | 1         | 1.43%   |
| Realtek Integrated Webcam HD                  | 1         | 1.43%   |
| Quanta VGA WebCam                             | 1         | 1.43%   |
| Microdia Laptop_Integrated_Webcam_HD          | 1         | 1.43%   |
| Luxvisions Innotech Limited Integrated Camera | 1         | 1.43%   |
| Luxvisions Innotech Limited HP HD Camera      | 1         | 1.43%   |
| Logitech HD Pro Webcam C920                   | 1         | 1.43%   |
| Lite-On Integrated Camera                     | 1         | 1.43%   |
| Lite-On HP Wide Vision HD Camera              | 1         | 1.43%   |
| Intel RealSense 3D Camera (Front F200)        | 1         | 1.43%   |
| IMC Networks USB2.0 HD IR UVC WebCam          | 1         | 1.43%   |
| IMC Networks Integrated Webcam                | 1         | 1.43%   |
| IMC Networks HP TrueVision HD Camera          | 1         | 1.43%   |
| IMC Networks HD Camera                        | 1         | 1.43%   |
| Genesys Logic Camera                          | 1         | 1.43%   |
| DigiTech WebCam SCB-0350M                     | 1         | 1.43%   |
| Chicony USB2.0 HD UVC WebCam                  | 1         | 1.43%   |
| Chicony USB 2.0 Camera                        | 1         | 1.43%   |
| Chicony LG Camera                             | 1         | 1.43%   |
| Chicony Chicony USB2.0 Camera                 | 1         | 1.43%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 5         | 50%     |
| Validity Sensors           | 3         | 30%     |
| Shenzhen Goodix Technology | 1         | 10%     |
| LighTuning Technology      | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 20%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 2         | 20%     |
| Validity Sensors VFS5011 Fingerprint Reader               | 1         | 10%     |
| Validity Sensors VFS 5011 fingerprint sensor              | 1         | 10%     |
| Validity Sensors Synaptics WBDI                           | 1         | 10%     |
| Shenzhen Goodix Fingerprint Reader                        | 1         | 10%     |
| LighTuning EgisTec EH575                                  | 1         | 10%     |
| Unknown                                                   | 1         | 10%     |

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
| 1     | 32        | 34.41%  |
| 2     | 31        | 33.33%  |
| 3     | 19        | 20.43%  |
| 4     | 5         | 5.38%   |
| 0     | 5         | 5.38%   |
| 5     | 1         | 1.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 67        | 42.41%  |
| Bluetooth                | 35        | 22.15%  |
| Net/wireless             | 19        | 12.03%  |
| Card reader              | 13        | 8.23%   |
| Firewire controller      | 9         | 5.7%    |
| Fingerprint reader       | 9         | 5.7%    |
| Storage                  | 2         | 1.27%   |
| Net/ethernet             | 2         | 1.27%   |
| Sound                    | 1         | 0.63%   |
| Network                  | 1         | 0.63%   |

