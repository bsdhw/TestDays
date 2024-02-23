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

Total: 139

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Dell          | Precision 7510              | [b5d52d8750](https://bsd-hardware.info/?probe=b5d52d8750) | Jan 16, 2024 |
| NOBLEX        | SF20BA                      | [a6a17eb5ca](https://bsd-hardware.info/?probe=a6a17eb5ca) | Jul 21, 2023 |
| Lenovo        | G50-30 80G0                 | [911a1723a2](https://bsd-hardware.info/?probe=911a1723a2) | Apr 02, 2023 |
| Google        | Stout                       | [d8346bb5da](https://bsd-hardware.info/?probe=d8346bb5da) | Mar 29, 2023 |
| Acer          | Nitro AN515-53              | [a46e065fac](https://bsd-hardware.info/?probe=a46e065fac) | Mar 23, 2023 |
| OEGStone      | W54_55SU1,SUW               | [64316408f0](https://bsd-hardware.info/?probe=64316408f0) | Mar 15, 2023 |
| Google        | Kohaku                      | [88491d298e](https://bsd-hardware.info/?probe=88491d298e) | Mar 12, 2023 |
| Lenovo        | ThinkPad X230 2324A14       | [124b3bdb95](https://bsd-hardware.info/?probe=124b3bdb95) | Mar 08, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [9466e6d4f4](https://bsd-hardware.info/?probe=9466e6d4f4) | Mar 07, 2023 |
| Lenovo        | ThinkPad T480s 20L7002CU... | [0e051e7291](https://bsd-hardware.info/?probe=0e051e7291) | Feb 27, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [0f4dd9a9bc](https://bsd-hardware.info/?probe=0f4dd9a9bc) | Feb 15, 2023 |
| Panasonic     | CF-30KAPAXAM                | [f686e3756c](https://bsd-hardware.info/?probe=f686e3756c) | Feb 13, 2023 |
| Alienware     | m15                         | [3ab3e4b671](https://bsd-hardware.info/?probe=3ab3e4b671) | Feb 12, 2023 |
| HP            | ProBook 450 G2              | [acff807555](https://bsd-hardware.info/?probe=acff807555) | Feb 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [8d49d50738](https://bsd-hardware.info/?probe=8d49d50738) | Feb 11, 2023 |
| Acer          | Aspire A315-58              | [81827ccbca](https://bsd-hardware.info/?probe=81827ccbca) | Feb 10, 2023 |
| Samsung       | 700T1C                      | [91d5c568d1](https://bsd-hardware.info/?probe=91d5c568d1) | Feb 05, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [b7a491a010](https://bsd-hardware.info/?probe=b7a491a010) | Feb 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [0b48f96d1e](https://bsd-hardware.info/?probe=0b48f96d1e) | Jan 31, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [21398109dc](https://bsd-hardware.info/?probe=21398109dc) | Jan 29, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [2098b8808d](https://bsd-hardware.info/?probe=2098b8808d) | Jan 29, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [afeb216c1e](https://bsd-hardware.info/?probe=afeb216c1e) | Jan 25, 2023 |
| Lenovo        | B590 20208                  | [e4c2272546](https://bsd-hardware.info/?probe=e4c2272546) | Jan 15, 2023 |
| Dell          | Latitude E6420              | [cb7b02c421](https://bsd-hardware.info/?probe=cb7b02c421) | Jan 11, 2023 |
| Lenovo        | ThinkPad X220 4291LF6       | [25cddb26c3](https://bsd-hardware.info/?probe=25cddb26c3) | Jan 11, 2023 |
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
| amd64 | 115       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| XFCE          | 23        | 20%     |
| KDE5          | 21        | 18.26%  |
| Console       | 17        | 14.78%  |
| GNOME         | 16        | 13.91%  |
| TWM           | 9         | 7.83%   |
| MATE          | 8         | 6.96%   |
| Openbox       | 5         | 4.35%   |
| i3            | 5         | 4.35%   |
| Cinnamon      | 2         | 1.74%   |
| X-Cinnamon    | 1         | 0.87%   |
| Window Maker  | 1         | 0.87%   |
| LXQt          | 1         | 0.87%   |
| LXDE          | 1         | 0.87%   |
| Lumina        | 1         | 0.87%   |
| IceWM         | 1         | 0.87%   |
| Enlightenment | 1         | 0.87%   |
| dwm           | 1         | 0.87%   |
| AwesomeWM     | 1         | 0.87%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 92        | 80%     |
| Console | 15        | 13.04%  |
| Wayland | 8         | 6.96%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 40        | 34.78%  |
| SDDM    | 25        | 21.74%  |
| SLiM    | 15        | 13.04%  |
| GDM     | 12        | 10.43%  |
| LightDM | 11        | 9.57%   |
| XDM     | 8         | 6.96%   |
| Ly      | 3         | 2.61%   |
| PCDM    | 1         | 0.87%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| C               | 76        | 65.52%  |
| en_US           | 18        | 15.52%  |
| Unknown         | 8         | 6.9%    |
| zh_CN           | 5         | 4.31%   |
| ru_RU           | 3         | 2.59%   |
| en_US.ISO8859-1 | 2         | 1.72%   |
| ko_KR           | 1         | 0.86%   |
| fr_FR           | 1         | 0.86%   |
| es_ES           | 1         | 0.86%   |
| en_AU           | 1         | 0.86%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 95        | 82.61%  |
| BIOS | 20        | 17.39%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Zfs  | 80        | 68.97%  |
| Ufs  | 36        | 31.03%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 106       | 92.17%  |
| MBR     | 7         | 6.09%   |
| BSD     | 1         | 0.87%   |
| Unknown | 1         | 0.87%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 37        | 32.17%  |
| Dell                | 26        | 22.61%  |
| ASUSTek Computer    | 10        | 8.7%    |
| Hewlett-Packard     | 8         | 6.96%   |
| Acer                | 6         | 5.22%   |
| Google              | 5         | 4.35%   |
| TUXEDO              | 3         | 2.61%   |
| Samsung Electronics | 3         | 2.61%   |
| Toshiba             | 2         | 1.74%   |
| System76            | 2         | 1.74%   |
| Unknown             | 2         | 1.74%   |
| Sony                | 1         | 0.87%   |
| Panasonic           | 1         | 0.87%   |
| Notebook            | 1         | 0.87%   |
| NOBLEX              | 1         | 0.87%   |
| MSI                 | 1         | 0.87%   |
| LG Electronics      | 1         | 0.87%   |
| GPD                 | 1         | 0.87%   |
| Fujitsu Siemens     | 1         | 0.87%   |
| Fujitsu             | 1         | 0.87%   |
| Apple               | 1         | 0.87%   |
| Alienware           | 1         | 0.87%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| HP EliteBook 850 G7 Notebook PC             | 2         | 1.74%   |
| Google Peppy                                | 2         | 1.74%   |
| Dell Precision M4500                        | 2         | 1.74%   |
| Dell Latitude E6420                         | 2         | 1.74%   |
| Unknown                                     | 2         | 1.74%   |
| TUXEDO InfinityBook13V3                     | 1         | 0.87%   |
| TUXEDO InfinityBook Pro 14 Gen6             | 1         | 0.87%   |
| TUXEDO Aura 15 Gen1                         | 1         | 0.87%   |
| Toshiba Satellite L305D                     | 1         | 0.87%   |
| Toshiba Satellite A300                      | 1         | 0.87%   |
| System76 Gazelle                            | 1         | 0.87%   |
| System76 Galago Pro                         | 1         | 0.87%   |
| Sony VGN-NS21M_S                            | 1         | 0.87%   |
| Samsung R530/R730/R540                      | 1         | 0.87%   |
| Samsung 750TDA                              | 1         | 0.87%   |
| Samsung 700T1C                              | 1         | 0.87%   |
| Panasonic CF-30KAPAXAM                      | 1         | 0.87%   |
| Notebook N7x0WU                             | 1         | 0.87%   |
| NOBLEX SF20BA                               | 1         | 0.87%   |
| MSI GF63 Thin 9SC                           | 1         | 0.87%   |
| LG 17Z990-R.AAC9U1                          | 1         | 0.87%   |
| Lenovo XiaoXinPro-13API 2019 81XD           | 1         | 0.87%   |
| Lenovo ThinkPad X270 20HMCTO1WW             | 1         | 0.87%   |
| Lenovo ThinkPad X260 20F6S0KA00             | 1         | 0.87%   |
| Lenovo ThinkPad X250 20CMS0FA00             | 1         | 0.87%   |
| Lenovo ThinkPad X230 2324A14                | 1         | 0.87%   |
| Lenovo ThinkPad X220 4291LF6                | 1         | 0.87%   |
| Lenovo ThinkPad X220 4286CTO                | 1         | 0.87%   |
| Lenovo ThinkPad X13 Gen 1 20UF000QRT        | 1         | 0.87%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TKS0QB00 | 1         | 0.87%   |
| Lenovo ThinkPad X1 Carbon Gen 10 21CBCTO1WW | 1         | 0.87%   |
| Lenovo ThinkPad X1 Carbon 7th 20QES53R00    | 1         | 0.87%   |
| Lenovo ThinkPad X1 Carbon 5th 20HR002MAT    | 1         | 0.87%   |
| Lenovo ThinkPad W520 4282AD4                | 1         | 0.87%   |
| Lenovo ThinkPad T480s 20L7002CUS            | 1         | 0.87%   |
| Lenovo ThinkPad T480 20L6SB2N00             | 1         | 0.87%   |
| Lenovo ThinkPad T480 20L6S29E0T             | 1         | 0.87%   |
| Lenovo ThinkPad T440p 20AWS0Y40T            | 1         | 0.87%   |
| Lenovo ThinkPad T420s 41732AU               | 1         | 0.87%   |
| Lenovo ThinkPad T420 4236C92                | 1         | 0.87%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 23        | 20%     |
| Dell Latitude           | 10        | 8.7%    |
| Lenovo IdeaPad          | 7         | 6.09%   |
| Dell Precision          | 6         | 5.22%   |
| Dell Inspiron           | 5         | 4.35%   |
| ASUS ZenBook            | 4         | 3.48%   |
| HP ProBook              | 3         | 2.61%   |
| ASUS VivoBook           | 3         | 2.61%   |
| Acer Aspire             | 3         | 2.61%   |
| Toshiba Satellite       | 2         | 1.74%   |
| Lenovo Legion           | 2         | 1.74%   |
| HP EliteBook            | 2         | 1.74%   |
| Google Peppy            | 2         | 1.74%   |
| Dell Vostro             | 2         | 1.74%   |
| Acer Nitro              | 2         | 1.74%   |
| Unknown                 | 2         | 1.74%   |
| TUXEDO InfinityBook13V3 | 1         | 0.87%   |
| TUXEDO InfinityBook     | 1         | 0.87%   |
| TUXEDO Aura             | 1         | 0.87%   |
| System76 Gazelle        | 1         | 0.87%   |
| System76 Galago         | 1         | 0.87%   |
| Sony VGN-NS21M          | 1         | 0.87%   |
| Samsung R530            | 1         | 0.87%   |
| Samsung 750TDA          | 1         | 0.87%   |
| Samsung 700T1C          | 1         | 0.87%   |
| Panasonic CF-30KAPAXAM  | 1         | 0.87%   |
| Notebook N7x0WU         | 1         | 0.87%   |
| NOBLEX SF20BA           | 1         | 0.87%   |
| MSI GF63                | 1         | 0.87%   |
| LG 17Z990-R.AAC9U1      | 1         | 0.87%   |
| Lenovo XiaoXinPro-13API | 1         | 0.87%   |
| Lenovo ThinkBook        | 1         | 0.87%   |
| Lenovo G50-30           | 1         | 0.87%   |
| Lenovo G40-45           | 1         | 0.87%   |
| Lenovo B590             | 1         | 0.87%   |
| HP Pavilion             | 1         | 0.87%   |
| HP Laptop               | 1         | 0.87%   |
| HP ENVY                 | 1         | 0.87%   |
| GPD MicroPC             | 1         | 0.87%   |
| Google Stout            | 1         | 0.87%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2022 | 19        | 16.52%  |
| 2020 | 16        | 13.91%  |
| 2021 | 13        | 11.3%   |
| 2018 | 12        | 10.43%  |
| 2019 | 8         | 6.96%   |
| 2011 | 8         | 6.96%   |
| 2012 | 7         | 6.09%   |
| 2016 | 6         | 5.22%   |
| 2017 | 5         | 4.35%   |
| 2015 | 4         | 3.48%   |
| 2013 | 4         | 3.48%   |
| 2010 | 4         | 3.48%   |
| 2014 | 3         | 2.61%   |
| 2009 | 3         | 2.61%   |
| 2008 | 2         | 1.74%   |
| 2023 | 1         | 0.87%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 115       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 109       | 94.78%  |
| Yes  | 6         | 5.22%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 41        | 35.65%  |
| 16.01-24.0  | 37        | 32.17%  |
| 4.01-8.0    | 19        | 16.52%  |
| 32.01-64.0  | 9         | 7.83%   |
| 24.01-32.0  | 3         | 2.61%   |
| 2.01-3.0    | 3         | 2.61%   |
| 64.01-256.0 | 3         | 2.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 46        | 40%     |
| 0.51-1.0  | 38        | 33.04%  |
| 1.01-2.0  | 23        | 20%     |
| 2.01-3.0  | 7         | 6.09%   |
| 8.01-16.0 | 1         | 0.87%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 83        | 72.17%  |
| 2      | 25        | 21.74%  |
| 0      | 6         | 5.22%   |
| 3      | 1         | 0.87%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 88        | 76.52%  |
| Yes       | 27        | 23.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 81        | 70.43%  |
| No        | 34        | 29.57%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 114       | 99.13%  |
| No        | 1         | 0.87%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 87        | 75.65%  |
| No        | 28        | 24.35%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 25        | 21.55%  |
| Russia      | 10        | 8.62%   |
| China       | 9         | 7.76%   |
| France      | 7         | 6.03%   |
| UK          | 6         | 5.17%   |
| India       | 5         | 4.31%   |
| Spain       | 4         | 3.45%   |
| Czechia     | 4         | 3.45%   |
| Austria     | 4         | 3.45%   |
| Japan       | 3         | 2.59%   |
| Germany     | 3         | 2.59%   |
| Turkey      | 2         | 1.72%   |
| Thailand    | 2         | 1.72%   |
| South Korea | 2         | 1.72%   |
| Philippines | 2         | 1.72%   |
| Netherlands | 2         | 1.72%   |
| Italy       | 2         | 1.72%   |
| Canada      | 2         | 1.72%   |
| Argentina   | 2         | 1.72%   |
| Venezuela   | 1         | 0.86%   |
| Uruguay     | 1         | 0.86%   |
| Slovenia    | 1         | 0.86%   |
| Romania     | 1         | 0.86%   |
| Poland      | 1         | 0.86%   |
| Norway      | 1         | 0.86%   |
| Mexico      | 1         | 0.86%   |
| Malaysia    | 1         | 0.86%   |
| Lithuania   | 1         | 0.86%   |
| Israel      | 1         | 0.86%   |
| Iraq        | 1         | 0.86%   |
| Hungary     | 1         | 0.86%   |
| Hong Kong   | 1         | 0.86%   |
| Guadeloupe  | 1         | 0.86%   |
| Greece      | 1         | 0.86%   |
| Finland     | 1         | 0.86%   |
| Chile       | 1         | 0.86%   |
| Bulgaria    | 1         | 0.86%   |
| Belarus     | 1         | 0.86%   |
| Australia   | 1         | 0.86%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 6         | 5.17%   |
| Vienna            | 4         | 3.45%   |
| Paris             | 3         | 2.59%   |
| Fayetteville      | 2         | 1.72%   |
| Carry-le-Rouet    | 2         | 1.72%   |
| Brno              | 2         | 1.72%   |
| Barcelona         | 2         | 1.72%   |
| Zhumadian         | 1         | 0.86%   |
| Yangcheon-gu      | 1         | 0.86%   |
| Xiamen            | 1         | 0.86%   |
| Xi'an             | 1         | 0.86%   |
| Woerdense Verlaat | 1         | 0.86%   |
| Wheatland         | 1         | 0.86%   |
| Vilnius           | 1         | 0.86%   |
| Villapresente     | 1         | 0.86%   |
| Uiwang-si         | 1         | 0.86%   |
| Turku             | 1         | 0.86%   |
| Trivandrum        | 1         | 0.86%   |
| Tlalnepantla      | 1         | 0.86%   |
| Thousand Oaks     | 1         | 0.86%   |
| Thessaloniki      | 1         | 0.86%   |
| Tel Aviv          | 1         | 0.86%   |
| Taito             | 1         | 0.86%   |
| Stratford         | 1         | 0.86%   |
| St Petersburg     | 1         | 0.86%   |
| Shinjuku          | 1         | 0.86%   |
| Shanghai          | 1         | 0.86%   |
| Shah Alam         | 1         | 0.86%   |
| Santiago          | 1         | 0.86%   |
| Sandefjord        | 1         | 0.86%   |
| San Pablo City    | 1         | 0.86%   |
| San Miguel        | 1         | 0.86%   |
| San Antonio       | 1         | 0.86%   |
| Samokov           | 1         | 0.86%   |
| Ruislip           | 1         | 0.86%   |
| Riverside         | 1         | 0.86%   |
| Queens            | 1         | 0.86%   |
| Qiqihar           | 1         | 0.86%   |
| Qinnan            | 1         | 0.86%   |
| Ozersk            | 1         | 0.86%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 25        | 27     | 19.38%  |
| WDC                 | 23        | 25     | 17.83%  |
| Seagate             | 9         | 10     | 6.98%   |
| Kingston            | 9         | 10     | 6.98%   |
| Crucial             | 7         | 8      | 5.43%   |
| Toshiba             | 6         | 7      | 4.65%   |
| SK hynix            | 6         | 6      | 4.65%   |
| Transcend           | 4         | 4      | 3.1%    |
| Intel               | 4         | 4      | 3.1%    |
| A-DATA Technology   | 4         | 7      | 3.1%    |
| KIOXIA              | 3         | 3      | 2.33%   |
| Hitachi             | 3         | 3      | 2.33%   |
| Gigabyte Technology | 3         | 3      | 2.33%   |
| UMIS                | 2         | 2      | 1.55%   |
| SSSTC               | 2         | 2      | 1.55%   |
| Silicon Motion      | 2         | 2      | 1.55%   |
| SanDisk             | 2         | 2      | 1.55%   |
| XPG                 | 1         | 1      | 0.78%   |
| PNY                 | 1         | 1      | 0.78%   |
| Patriot             | 1         | 1      | 0.78%   |
| Micron Technology   | 1         | 1      | 0.78%   |
| Lexar               | 1         | 2      | 0.78%   |
| Lenovo              | 1         | 1      | 0.78%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.78%   |
| Hikvision           | 1         | 1      | 0.78%   |
| Hewlett-Packard     | 1         | 1      | 0.78%   |
| Fanxiang            | 1         | 2      | 0.78%   |
| EAGET               | 1         | 1      | 0.78%   |
| CFD                 | 1         | 1      | 0.78%   |
| BR                  | 1         | 1      | 0.78%   |
| BIWIN               | 1         | 1      | 0.78%   |
| Apple               | 1         | 1      | 0.78%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB             | 3         | 2.21%   |
| WDC WDS100T2B0C-00PXH0 1TB              | 2         | 1.47%   |
| WDC WD3200BPVT-80JJ5T0 320GB            | 2         | 1.47%   |
| WDC PC SN530 SDBPNPZ-256G-1014 256GB    | 2         | 1.47%   |
| SK hynix BC511 HFM512GDJTNI-82A0A 512GB | 2         | 1.47%   |
| Samsung SSD 970 EVO Plus 2TB            | 2         | 1.47%   |
| KIOXIA KBG40ZNS512G NVMe 512GB          | 2         | 1.47%   |
| Crucial CT1000MX500SSD1 1TB             | 2         | 1.47%   |
| XPG GAMMIX S5 1TB                       | 1         | 0.74%   |
| WDC WDS500G3X0C-00SJG0 500GB            | 1         | 0.74%   |
| WDC WDS480G2G0A-00JH30 480GB            | 1         | 0.74%   |
| WDC WDS250G2B0B-00YS70 250GB            | 1         | 0.74%   |
| WDC WDS240G2G0A-00JH30 240GB            | 1         | 0.74%   |
| WDC WDS120G2G0B-00EPW0 120GB            | 1         | 0.74%   |
| WDC WD3200BPVT-22JJ5T0 320GB            | 1         | 0.74%   |
| WDC WD3200BEKT-60PVMT0 320GB            | 1         | 0.74%   |
| WDC WD2500BEVT-24A23T0 250GB            | 1         | 0.74%   |
| WDC WD20SPZX-00UA7T0 2TB                | 1         | 0.74%   |
| WDC WD1600BEVT-80A23T0 160GB            | 1         | 0.74%   |
| WDC WD1600BEVT-75ZCT2 160GB             | 1         | 0.74%   |
| WDC WD1600BEVT-22ZCT0 160GB             | 1         | 0.74%   |
| WDC WD10SPZX-75Z10T3 1TB                | 1         | 0.74%   |
| WDC WD10SPZX-17Z10T1 1TB                | 1         | 0.74%   |
| WDC WD10JPVX-22JC3T0 1TB                | 1         | 0.74%   |
| WDC WD10JPCX-24UE4T0 1TB                | 1         | 0.74%   |
| WDC WD10EZEX-60WN4A0 1TB                | 1         | 0.74%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB      | 1         | 0.74%   |
| WDC PC SN530 NVMe 256GB                 | 1         | 0.74%   |
| UMIS RPJTJ512MEE1OWX 512GB              | 1         | 0.74%   |
| UMIS RPJTJ256MEE1OWX 256GB              | 1         | 0.74%   |
| Transcend TS512GSSD230S 512GB           | 1         | 0.74%   |
| Transcend TS256GMTS430S 256GB           | 1         | 0.74%   |
| Transcend TS1TMTE110S 1TB               | 1         | 0.74%   |
| Transcend TS128GMTS430S 128GB           | 1         | 0.74%   |
| Toshiba MQ04ABF100 1TB                  | 1         | 0.74%   |
| Toshiba MQ01ABF050 500GB                | 1         | 0.74%   |
| Toshiba MQ01ABD100 1TB                  | 1         | 0.74%   |
| Toshiba KXG50ZNV1T02 NVMe 1024GB        | 1         | 0.74%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB     | 1         | 0.74%   |
| Toshiba KBG30ZMT512G 512GB              | 1         | 0.74%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 13        | 14     | 48.15%  |
| Seagate | 8         | 9      | 29.63%  |
| Toshiba | 3         | 3      | 11.11%  |
| Hitachi | 3         | 3      | 11.11%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 10     | 20%     |
| Kingston            | 6         | 7      | 12%     |
| Crucial             | 6         | 7      | 12%     |
| WDC                 | 4         | 4      | 8%      |
| Transcend           | 3         | 3      | 6%      |
| A-DATA Technology   | 3         | 6      | 6%      |
| SanDisk             | 2         | 2      | 4%      |
| Toshiba             | 1         | 1      | 2%      |
| Seagate             | 1         | 1      | 2%      |
| PNY                 | 1         | 1      | 2%      |
| Patriot             | 1         | 1      | 2%      |
| Lexar               | 1         | 2      | 2%      |
| Lenovo              | 1         | 1      | 2%      |
| KIOXIA-EXCERIA      | 1         | 1      | 2%      |
| Intel               | 1         | 1      | 2%      |
| Hikvision           | 1         | 1      | 2%      |
| Hewlett-Packard     | 1         | 1      | 2%      |
| Gigabyte Technology | 1         | 1      | 2%      |
| Fanxiang            | 1         | 2      | 2%      |
| CFD                 | 1         | 1      | 2%      |
| BR                  | 1         | 1      | 2%      |
| BIWIN               | 1         | 1      | 2%      |
| Apple               | 1         | 1      | 2%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 52        | 56     | 42.28%  |
| SSD  | 45        | 57     | 36.59%  |
| HDD  | 26        | 29     | 21.14%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 68        | 86     | 56.67%  |
| NVMe | 52        | 56     | 43.33%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 46        | 57     | 63.89%  |
| 0.51-1.0   | 20        | 23     | 27.78%  |
| 1.01-2.0   | 6         | 6      | 8.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 47        | 40.87%  |
| 251-500    | 30        | 26.09%  |
| 501-1000   | 19        | 16.52%  |
| 51-100     | 8         | 6.96%   |
| 1001-2000  | 6         | 5.22%   |
| 21-50      | 4         | 3.48%   |
| 1-20       | 1         | 0.87%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 90        | 77.59%  |
| 21-50   | 16        | 13.79%  |
| 101-250 | 5         | 4.31%   |
| 51-100  | 4         | 3.45%   |
| 251-500 | 1         | 0.86%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD3200BPVT-80JJ5T0 320GB                 | 2         | 2      | 10%     |
| WDC WD3200BEKT-60PVMT0 320GB                 | 1         | 1      | 5%      |
| WDC WD2500BEVT-24A23T0 250GB                 | 1         | 1      | 5%      |
| Toshiba MQ01ABF050 500GB                     | 1         | 1      | 5%      |
| Toshiba MQ01ABD100 1TB                       | 1         | 1      | 5%      |
| Seagate ST9750420AS 752GB                    | 1         | 1      | 5%      |
| Seagate ST500LT012-1DG142 500GB              | 1         | 1      | 5%      |
| Seagate ST500LM012 HN-M500MBB 500GB          | 1         | 1      | 5%      |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 2      | 5%      |
| Samsung Electronics SSD PM810 2.5-inch 128GB | 1         | 1      | 5%      |
| Kingston SVP200S37A120G 120GB                | 1         | 1      | 5%      |
| Kingston SNS4151S316GD 16GB                  | 1         | 1      | 5%      |
| Kingston SH103S3240G 240GB                   | 1         | 1      | 5%      |
| Intel SSDSA2M160G2LE 160GB                   | 1         | 1      | 5%      |
| Hitachi HTS721080G9SA00 80GB                 | 1         | 1      | 5%      |
| Hitachi HTS543232L9SA00 320GB                | 1         | 1      | 5%      |
| Fanxiang S101-240GB                          | 1         | 1      | 5%      |
| A-DATA Technology SU650 120GB                | 1         | 1      | 5%      |
| A-DATA Technology SU630 240GB                | 1         | 2      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 5      | 22.22%  |
| WDC                 | 3         | 4      | 16.67%  |
| Toshiba             | 2         | 2      | 11.11%  |
| Kingston            | 2         | 3      | 11.11%  |
| Hitachi             | 2         | 2      | 11.11%  |
| A-DATA Technology   | 2         | 3      | 11.11%  |
| Samsung Electronics | 1         | 1      | 5.56%   |
| Intel               | 1         | 1      | 5.56%   |
| Fanxiang            | 1         | 1      | 5.56%   |

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
| HDD  | 10        | 13     | 58.82%  |
| SSD  | 7         | 9      | 41.18%  |

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
| Works    | 94        | 117    | 83.19%  |
| Malfunc  | 17        | 22     | 15.04%  |
| Detected | 2         | 3      | 1.77%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 72        | 52.17%  |
| Samsung Electronics                     | 17        | 12.32%  |
| AMD                                     | 13        | 9.42%   |
| SanDisk                                 | 8         | 5.8%    |
| SK hynix                                | 5         | 3.62%   |
| Silicon Motion                          | 3         | 2.17%   |
| KIOXIA                                  | 3         | 2.17%   |
| Kingston Technology Company             | 3         | 2.17%   |
| Toshiba                                 | 2         | 1.45%   |
| Solid State Storage Technology          | 2         | 1.45%   |
| Phison Electronics                      | 2         | 1.45%   |
| Union Memory (Shenzhen)                 | 1         | 0.72%   |
| Transcend                               | 1         | 0.72%   |
| Shenzhen Unionmemory Information System | 1         | 0.72%   |
| Realtek Semiconductor                   | 1         | 0.72%   |
| Nvidia                                  | 1         | 0.72%   |
| Micron/Crucial Technology               | 1         | 0.72%   |
| Micron Technology                       | 1         | 0.72%   |
| ADATA Technology                        | 1         | 0.72%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 12        | 8.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 10        | 6.94%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 9         | 6.25%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 8         | 5.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 7         | 4.86%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 4.86%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 3.47%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 5         | 3.47%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 4         | 2.78%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 2.78%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 3         | 2.08%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 3         | 2.08%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 3         | 2.08%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 2.08%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 3         | 2.08%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 2.08%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                 | 2         | 1.39%   |
| SK hynix BC511 NVMe SSD                                                        | 2         | 1.39%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 2         | 1.39%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2         | 1.39%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 1.39%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 1.39%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 1.39%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.39%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 1.39%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2         | 1.39%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 256GB                          | 1         | 0.69%   |
| Transcend NVMe PCIe SSD 110S/112S/120S/MTE300S/MTE400S/MTE652T2 (DRAM-less)    | 1         | 0.69%   |
| Toshiba XG5 NVMe SSD Controller                                                | 1         | 0.69%   |
| Toshiba BG3 x2 NVMe SSD Controller (DRAM-less)                                 | 1         | 0.69%   |
| Shenzhen Unionmemory Information System AM620 PCIe 3.0 NVMe SSD 512GB          | 1         | 0.69%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                     | 1         | 0.69%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 1         | 0.69%   |
| SanDisk IX SN530 NVMe SSD (DRAM-less)                                          | 1         | 0.69%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 1         | 0.69%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1         | 0.69%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 0.69%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                              | 1         | 0.69%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 1         | 0.69%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1         | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 75        | 53.57%  |
| NVMe | 51        | 36.43%  |
| RAID | 12        | 8.57%   |
| IDE  | 2         | 1.43%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 98        | 85.22%  |
| AMD    | 17        | 14.78%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz       | 4         | 3.48%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 3         | 2.61%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 3         | 2.61%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 3         | 2.61%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 3         | 2.61%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 3         | 2.61%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 3         | 2.61%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 2         | 1.74%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 2         | 1.74%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 2         | 1.74%   |
| Intel Core i5-2540M CPU @ 2.60GHz       | 2         | 1.74%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 2         | 1.74%   |
| Intel Core i5-10310U CPU @ 1.70GHz      | 2         | 1.74%   |
| Intel Core i5 CPU M 560 @ 2.67GH        | 2         | 1.74%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 2         | 1.74%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz | 2         | 1.74%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 2         | 1.74%   |
| AMD Ryzen 3 5300U with Radeon Graphics  | 2         | 1.74%   |
| Intel Pentium Silver N6000 @ 1.10GHz    | 1         | 0.87%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz  | 1         | 0.87%   |
| Intel Genuine CPU                       | 1         | 0.87%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 0.87%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 1         | 0.87%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 1         | 0.87%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 1         | 0.87%   |
| Intel Core i7-4980HQ CPU @ 2.80GHz      | 1         | 0.87%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz      | 1         | 0.87%   |
| Intel Core i7-4712MQ CPU @ 2.30GHz      | 1         | 0.87%   |
| Intel Core i7-4610M CPU @ 3.00GHz       | 1         | 0.87%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 1         | 0.87%   |
| Intel Core i7-3632QM CPU @ 2.20GHz      | 1         | 0.87%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 1         | 0.87%   |
| Intel Core i7-3537U CPU @ 2.00GHz       | 1         | 0.87%   |
| Intel Core i7-2760QM CPU @ 2.40GHz      | 1         | 0.87%   |
| Intel Core i7-2640M CPU @ 2.80GHz       | 1         | 0.87%   |
| Intel Core i7-2620M CPU @ 2.70GHz       | 1         | 0.87%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 1         | 0.87%   |
| Intel Core i7-10610U CPU @ 1.80GHz      | 1         | 0.87%   |
| Intel Core i5-8365U CPU @ 1.60GHz       | 1         | 0.87%   |
| Intel Core i5-8300H CPU @ 2.30GHz       | 1         | 0.87%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 33        | 28.7%   |
| Intel Core i7        | 31        | 26.96%  |
| Other                | 10        | 8.7%    |
| Intel Celeron        | 10        | 8.7%    |
| Intel Core i3        | 5         | 4.35%   |
| Intel Core 2 Duo     | 5         | 4.35%   |
| AMD Ryzen 7          | 5         | 4.35%   |
| AMD Ryzen 3          | 4         | 3.48%   |
| AMD Ryzen 5          | 3         | 2.61%   |
| AMD A8               | 2         | 1.74%   |
| Intel Pentium Silver | 1         | 0.87%   |
| Intel Pentium Dual   | 1         | 0.87%   |
| Intel Genuine        | 1         | 0.87%   |
| Intel Atom           | 1         | 0.87%   |
| AMD Ryzen 7 PRO      | 1         | 0.87%   |
| AMD E2               | 1         | 0.87%   |
| AMD Athlon X2        | 1         | 0.87%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 48        | 41.74%  |
| 4       | 43        | 37.39%  |
| 8       | 7         | 6.09%   |
| 16      | 6         | 5.22%   |
| 6       | 6         | 5.22%   |
| Unknown | 3         | 2.61%   |
| 20      | 1         | 0.87%   |
| 1       | 1         | 0.87%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 115       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 78        | 67.83%  |
| 1       | 34        | 29.57%  |
| Unknown | 3         | 2.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 28        | 24.35%  |
| SandyBridge     | 11        | 9.57%   |
| IvyBridge       | 9         | 7.83%   |
| Unknown         | 9         | 7.83%   |
| TigerLake       | 7         | 6.09%   |
| Skylake         | 7         | 6.09%   |
| Haswell         | 7         | 6.09%   |
| Broadwell       | 5         | 4.35%   |
| Zen+            | 3         | 2.61%   |
| Zen 2           | 3         | 2.61%   |
| Westmere        | 3         | 2.61%   |
| Penryn          | 3         | 2.61%   |
| Core            | 3         | 2.61%   |
| Zen             | 2         | 1.74%   |
| Silvermont      | 2         | 1.74%   |
| Puma            | 2         | 1.74%   |
| IceLake         | 2         | 1.74%   |
| Goldmont plus   | 2         | 1.74%   |
| CometLake       | 2         | 1.74%   |
| Zen 3           | 1         | 0.87%   |
| K8 & K10 hybrid | 1         | 0.87%   |
| Goldmont        | 1         | 0.87%   |
| Excavator       | 1         | 0.87%   |
| Bonnell         | 1         | 0.87%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 92        | 65.71%  |
| Nvidia | 25        | 17.86%  |
| AMD    | 23        | 16.43%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 11        | 7.69%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 8         | 5.59%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 7         | 4.9%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 6         | 4.2%    |
| Intel UHD Graphics 620                                                    | 6         | 4.2%    |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 6         | 4.2%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 6         | 4.2%    |
| Intel HD Graphics 5500                                                    | 5         | 3.5%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 4         | 2.8%    |
| Intel Skylake GT2 [HD Graphics 520]                                       | 4         | 2.8%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 4         | 2.8%    |
| Intel HD Graphics 620                                                     | 4         | 2.8%    |
| AMD Lucienne                                                              | 4         | 2.8%    |
| Intel Haswell-ULT Integrated Graphics Controller                          | 3         | 2.1%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 3         | 2.1%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]             | 3         | 2.1%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 3         | 2.1%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 2         | 1.4%    |
| Nvidia GT216GLM [Quadro FX 880M]                                          | 2         | 1.4%    |
| Nvidia GP108BM [GeForce MX250]                                            | 2         | 1.4%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 2         | 1.4%    |
| Intel JasperLake [UHD Graphics]                                           | 2         | 1.4%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 2         | 1.4%    |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 1.4%    |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 2         | 1.4%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 1.4%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                       | 2         | 1.4%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 0.7%    |
| Nvidia TU117GLM [T550 Laptop GPU]                                         | 1         | 0.7%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 0.7%    |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                   | 1         | 0.7%    |
| Nvidia GM108M [GeForce MX130]                                             | 1         | 0.7%    |
| Nvidia GM108M [GeForce 920MX]                                             | 1         | 0.7%    |
| Nvidia GM107GLM [Quadro M2000M]                                           | 1         | 0.7%    |
| Nvidia GM107GLM [Quadro M1000M]                                           | 1         | 0.7%    |
| Nvidia GK208BM [GeForce 920M]                                             | 1         | 0.7%    |
| Nvidia GK107M [GeForce GT 650M]                                           | 1         | 0.7%    |
| Nvidia GF108GLM [NVS 5200M]                                               | 1         | 0.7%    |
| Nvidia GA107GLM [RTX A2000 Mobile]                                        | 1         | 0.7%    |
| Nvidia G98M [GeForce 9200M GS]                                            | 1         | 0.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 64        | 55.65%  |
| Intel + Nvidia | 17        | 14.78%  |
| 1 x AMD        | 14        | 12.17%  |
| 2 x Intel      | 6         | 5.22%   |
| Intel + AMD    | 5         | 4.35%   |
| 1 x Nvidia     | 4         | 3.48%   |
| AMD + Nvidia   | 3         | 2.61%   |
| 2 x Nvidia     | 1         | 0.87%   |
| 2 x AMD        | 1         | 0.87%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 105       | 91.3%   |
| Proprietary | 10        | 8.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 99        | 86.09%  |
| 0.51-1.0   | 5         | 4.35%   |
| 0.01-0.5   | 5         | 4.35%   |
| 3.01-4.0   | 2         | 1.74%   |
| 1.01-2.0   | 2         | 1.74%   |
| 7.01-8.0   | 1         | 0.87%   |
| 5.01-6.0   | 1         | 0.87%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 16        | 18.18%  |
| BOE                     | 14        | 15.91%  |
| Chimei Innolux          | 11        | 12.5%   |
| AU Optronics            | 11        | 12.5%   |
| Samsung Electronics     | 7         | 7.95%   |
| Toshiba                 | 2         | 2.27%   |
| Sharp                   | 2         | 2.27%   |
| LGD                     | 2         | 2.27%   |
| Lenovo                  | 2         | 2.27%   |
| CSO                     | 2         | 2.27%   |
| BenQ                    | 2         | 2.27%   |
| AOC                     | 2         | 2.27%   |
| YTH                     | 1         | 1.14%   |
| ViewSonic               | 1         | 1.14%   |
| USR                     | 1         | 1.14%   |
| Unknown (XXX)           | 1         | 1.14%   |
| Sceptre Tech            | 1         | 1.14%   |
| Mi                      | 1         | 1.14%   |
| LG Philips              | 1         | 1.14%   |
| KDC                     | 1         | 1.14%   |
| JDI                     | 1         | 1.14%   |
| HannStar                | 1         | 1.14%   |
| Dell                    | 1         | 1.14%   |
| Chi Mei Optoelectronics | 1         | 1.14%   |
| ASUSTek Computer        | 1         | 1.14%   |
| Apple                   | 1         | 1.14%   |
| Acer                    | 1         | 1.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LGD LCD Monitor 1600x900                                              | 2         | 2.27%   |
| LG Display LCD Monitor LGD064C 1920x1080 340x190mm 15.3-inch          | 2         | 2.27%   |
| LG Display LCD Monitor LGD02EB 1366x768 310x170mm 13.9-inch           | 2         | 2.27%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch      | 2         | 2.27%   |
| BenQ BL2480 BNQ802C 1920x1080 530x300mm 24.0-inch                     | 2         | 2.27%   |
| YTH HS133PC YTH1330 1920x1080 250x220mm 13.1-inch                     | 1         | 1.14%   |
| ViewSonic VG2439 Series VSCD22B 1920x1080 520x290mm 23.4-inch         | 1         | 1.14%   |
| USR LCD Monitor USR0100 1920x1080 510x290mm 23.1-inch                 | 1         | 1.14%   |
| Unknown (XXX) SMART TV XXX2851 3840x2160                              | 1         | 1.14%   |
| Toshiba TV TSB0200 1920x1080 530x300mm 24.0-inch                      | 1         | 1.14%   |
| Toshiba ScreenXpert- TSB8888 1080x2160 60x130mm 5.6-inch              | 1         | 1.14%   |
| Sharp LCD Monitor SHP143E 3840x2160 350x190mm 15.7-inch               | 1         | 1.14%   |
| Sharp LCD Monitor SHP1421 3200x1800 290x170mm 13.2-inch               | 1         | 1.14%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch        | 1         | 1.14%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch     | 1         | 1.14%   |
| Samsung Electronics LS24A40xU SAM71D1 1920x1080 530x300mm 24.0-inch   | 1         | 1.14%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch  | 1         | 1.14%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 330x210mm 15.4-inch  | 1         | 1.14%   |
| Samsung Electronics LCD Monitor SEC3245 1280x800 330x210mm 15.4-inch  | 1         | 1.14%   |
| Samsung Electronics LCD Monitor SDC8B4F 1920x1080 340x190mm 15.3-inch | 1         | 1.14%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 290x170mm 13.2-inch | 1         | 1.14%   |
| Mi 27 NFGL XMIB004 1920x1080 600x330mm 27.0-inch                      | 1         | 1.14%   |
| LG Philips LCD Monitor LPL0120 1280x800 330x210mm 15.4-inch           | 1         | 1.14%   |
| LG Display LCD Monitor LGD6E01 1366x768 340x190mm 15.3-inch           | 1         | 1.14%   |
| LG Display LCD Monitor LGD060A 1920x1080 290x170mm 13.2-inch          | 1         | 1.14%   |
| LG Display LCD Monitor LGD05F8 2560x1600 370x230mm 17.2-inch          | 1         | 1.14%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch          | 1         | 1.14%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch          | 1         | 1.14%   |
| LG Display LCD Monitor LGD0408 1920x1080 280x160mm 12.7-inch          | 1         | 1.14%   |
| LG Display LCD Monitor LGD03DD 1366x768 340x190mm 15.3-inch           | 1         | 1.14%   |
| LG Display LCD Monitor LGD0395 1366x768 340x190mm 15.3-inch           | 1         | 1.14%   |
| LG Display LCD Monitor LGD0353 1366x768 350x190mm 15.7-inch           | 1         | 1.14%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x170mm 13.9-inch           | 1         | 1.14%   |
| LG Display LCD Monitor LGD02DA 1920x1080 380x210mm 17.1-inch          | 1         | 1.14%   |
| LG Display LCD Monitor LGD02D3 1366x768 280x160mm 12.7-inch           | 1         | 1.14%   |
| Lenovo LEN T32h-20 LEN61F1 2560x1440 700x390mm 31.5-inch              | 1         | 1.14%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch              | 1         | 1.14%   |
| KDC LCD Monitor KDC05F1 1366x768 280x170mm 12.9-inch                  | 1         | 1.14%   |
| JDI LCD Monitor JDI385A 3840x2160 290x170mm 13.2-inch                 | 1         | 1.14%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch             | 1         | 1.14%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 42        | 50.6%   |
| 1366x768 (WXGA)  | 19        | 22.89%  |
| 3840x2160 (4K)   | 5         | 6.02%   |
| 2560x1440 (QHD)  | 4         | 4.82%   |
| 1600x900 (HD+)   | 4         | 4.82%   |
| 2560x1600        | 2         | 2.41%   |
| 1280x800 (WXGA)  | 2         | 2.41%   |
| 3200x1800 (QHD+) | 1         | 1.2%    |
| 2880x1800        | 1         | 1.2%    |
| 2560x1080        | 1         | 1.2%    |
| 1080x2160        | 1         | 1.2%    |
| 1024x600         | 1         | 1.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 32        | 36.36%  |
| 13      | 27        | 30.68%  |
| 12      | 6         | 6.82%   |
| 27      | 4         | 4.55%   |
| 24      | 4         | 4.55%   |
| Unknown | 4         | 4.55%   |
| 23      | 3         | 3.41%   |
| 17      | 2         | 2.27%   |
| 31      | 1         | 1.14%   |
| 29      | 1         | 1.14%   |
| 21      | 1         | 1.14%   |
| 11      | 1         | 1.14%   |
| 10      | 1         | 1.14%   |
| 5       | 1         | 1.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 51        | 58.62%  |
| 201-300     | 15        | 17.24%  |
| 501-600     | 10        | 11.49%  |
| Unknown     | 4         | 4.6%    |
| 601-700     | 3         | 3.45%   |
| 351-400     | 2         | 2.3%    |
| 401-500     | 1         | 1.15%   |
| 1-100       | 1         | 1.15%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 62        | 81.58%  |
| 16/10   | 8         | 10.53%  |
| Unknown | 3         | 3.95%   |
| 21/9    | 1         | 1.32%   |
| 11/10   | 1         | 1.32%   |
| 0.46    | 1         | 1.32%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 23        | 26.14%  |
| 81-90          | 21        | 23.86%  |
| 101-110        | 9         | 10.23%  |
| 201-250        | 8         | 9.09%   |
| 71-80          | 7         | 7.95%   |
| 61-70          | 5         | 5.68%   |
| 301-350        | 5         | 5.68%   |
| Unknown        | 4         | 4.55%   |
| 51-60          | 1         | 1.14%   |
| 351-500        | 1         | 1.14%   |
| 41-50          | 1         | 1.14%   |
| 1-40           | 1         | 1.14%   |
| 131-140        | 1         | 1.14%   |
| 121-130        | 1         | 1.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 34        | 39.53%  |
| 101-120       | 16        | 18.6%   |
| 51-100        | 16        | 18.6%   |
| 161-240       | 11        | 12.79%  |
| More than 240 | 5         | 5.81%   |
| Unknown       | 4         | 4.65%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 70        | 60.87%  |
| 0     | 31        | 26.96%  |
| 2     | 14        | 12.17%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 77        | 41.4%   |
| Realtek Semiconductor    | 52        | 27.96%  |
| Qualcomm Atheros         | 25        | 13.44%  |
| Broadcom                 | 9         | 4.84%   |
| Ralink Technology        | 3         | 1.61%   |
| Xiaomi                   | 2         | 1.08%   |
| TP-Link                  | 2         | 1.08%   |
| Samsung Electronics      | 2         | 1.08%   |
| MediaTek                 | 2         | 1.08%   |
| Marvell Technology Group | 2         | 1.08%   |
| Google                   | 2         | 1.08%   |
| Sierra Wireless          | 1         | 0.54%   |
| Sagem                    | 1         | 0.54%   |
| Ralink                   | 1         | 0.54%   |
| Qualcomm                 | 1         | 0.54%   |
| Nvidia                   | 1         | 0.54%   |
| Huawei Technologies      | 1         | 0.54%   |
| HMD Global               | 1         | 0.54%   |
| Arduino SA               | 1         | 0.54%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 31        | 14.29%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 12        | 5.53%   |
| Intel Wireless 8265 / 8275                                             | 9         | 4.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 9         | 4.15%   |
| Intel Wi-Fi 6 AX201                                                    | 6         | 2.76%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 6         | 2.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 6         | 2.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 5         | 2.3%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 5         | 2.3%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 5         | 2.3%    |
| Intel Wireless 8260                                                    | 4         | 1.84%   |
| Intel Wireless 7265                                                    | 4         | 1.84%   |
| Intel Wi-Fi 6 AX200                                                    | 4         | 1.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 3         | 1.38%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 3         | 1.38%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 3         | 1.38%   |
| Intel Wireless 7260                                                    | 3         | 1.38%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 3         | 1.38%   |
| Intel Ethernet Connection I217-LM                                      | 3         | 1.38%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 1.38%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 3         | 1.38%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 0.92%   |
| Ralink RT5370 Wireless Adapter                                         | 2         | 0.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 2         | 0.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 2         | 0.92%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 2         | 0.92%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 2         | 0.92%   |
| Intel Wireless 3160                                                    | 2         | 0.92%   |
| Intel WiFi Link 5100                                                   | 2         | 0.92%   |
| Intel Wi-Fi 6 AX201 160MHz                                             | 2         | 0.92%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 2         | 0.92%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 0.92%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 2         | 0.92%   |
| Intel Centrino Ultimate-N 6300                                         | 2         | 0.92%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 2         | 0.92%   |
| Broadcom BCM43228 802.11a/b/g/n                                        | 2         | 0.92%   |
| Broadcom BCM43224 802.11a/b/g/n                                        | 2         | 0.92%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.46%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 1         | 0.46%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 1         | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 73        | 57.48%  |
| Qualcomm Atheros      | 24        | 18.9%   |
| Realtek Semiconductor | 12        | 9.45%   |
| Broadcom              | 8         | 6.3%    |
| Ralink Technology     | 3         | 2.36%   |
| TP-Link               | 2         | 1.57%   |
| MediaTek              | 2         | 1.57%   |
| Sierra Wireless       | 1         | 0.79%   |
| Sagem                 | 1         | 0.79%   |
| Ralink                | 1         | 0.79%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 9         | 7.09%   |
| Intel Wi-Fi 6 AX201                                            | 6         | 4.72%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 6         | 4.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 6         | 4.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 5         | 3.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 3.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 5         | 3.94%   |
| Intel Wireless 8260                                            | 4         | 3.15%   |
| Intel Wireless 7265                                            | 4         | 3.15%   |
| Intel Wi-Fi 6 AX200                                            | 4         | 3.15%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 3         | 2.36%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3         | 2.36%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 3         | 2.36%   |
| Intel Wireless 7260                                            | 3         | 2.36%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 3         | 2.36%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 2.36%   |
| Ralink RT5370 Wireless Adapter                                 | 2         | 1.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 1.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2         | 1.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 1.57%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 1.57%   |
| Intel Wireless 3160                                            | 2         | 1.57%   |
| Intel WiFi Link 5100                                           | 2         | 1.57%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 2         | 1.57%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 1.57%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 1.57%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 1.57%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 2         | 1.57%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 1.57%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 2         | 1.57%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 0.79%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.79%   |
| Sierra Wireless EM7455                                         | 1         | 0.79%   |
| Sagem XG-76NA 802.11bg                                         | 1         | 0.79%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.79%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.79%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 0.79%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.79%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 0.79%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 0.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 45        | 51.14%  |
| Intel                    | 28        | 31.82%  |
| Xiaomi                   | 2         | 2.27%   |
| Samsung Electronics      | 2         | 2.27%   |
| Qualcomm Atheros         | 2         | 2.27%   |
| Marvell Technology Group | 2         | 2.27%   |
| Google                   | 2         | 2.27%   |
| Broadcom                 | 2         | 2.27%   |
| Qualcomm                 | 1         | 1.14%   |
| Nvidia                   | 1         | 1.14%   |
| HMD Global               | 1         | 1.14%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 31        | 35.23%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 12        | 13.64%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 9         | 10.23%  |
| Intel Ethernet Connection I217-LM                                      | 3         | 3.41%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 3.41%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 2.27%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 2.27%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 1.14%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 1         | 1.14%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 1.14%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                       | 1         | 1.14%   |
| Qualcomm FP3                                                           | 1         | 1.14%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 1.14%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 1.14%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 1.14%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1         | 1.14%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 1         | 1.14%   |
| Intel Ethernet Connection I219-V                                       | 1         | 1.14%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 1.14%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 1.14%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 1.14%   |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 1.14%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 1.14%   |
| Intel Ethernet Connection (16) I219-V                                  | 1         | 1.14%   |
| Intel Ethernet Connection (13) I219-V                                  | 1         | 1.14%   |
| Intel Ethernet Connection (10) I219-V                                  | 1         | 1.14%   |
| Intel Ethernet Connection (10) I219-LM                                 | 1         | 1.14%   |
| Intel 82567LM Gigabit Network Connection                               | 1         | 1.14%   |
| HMD Global Nokia 5.3 RNDIS Control RNDIS Ethernet Data                 | 1         | 1.14%   |
| Google Nexus/Pixel Device (tether+ debug)                              | 1         | 1.14%   |
| Google Nexus/Pixel Device (tether)                                     | 1         | 1.14%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                      | 1         | 1.14%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 1         | 1.14%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 114       | 57.87%  |
| Ethernet | 81        | 41.12%  |
| Modem    | 2         | 1.02%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 68        | 65.38%  |
| Ethernet | 36        | 34.62%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 79        | 68.7%   |
| 1     | 35        | 30.43%  |
| 0     | 1         | 0.87%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 97        | 83.62%  |
| Yes  | 19        | 16.38%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 55        | 61.11%  |
| Qualcomm Atheros Communications | 9         | 10%     |
| Realtek Semiconductor           | 4         | 4.44%   |
| IMC Networks                    | 4         | 4.44%   |
| Dell                            | 4         | 4.44%   |
| Broadcom                        | 4         | 4.44%   |
| Foxconn / Hon Hai               | 3         | 3.33%   |
| Lite-On Technology              | 2         | 2.22%   |
| Ralink                          | 1         | 1.11%   |
| Creative Technology             | 1         | 1.11%   |
| Cambridge Silicon Radio         | 1         | 1.11%   |
| Apple                           | 1         | 1.11%   |
| Alps Electric                   | 1         | 1.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 18        | 20%     |
| Intel AX201 Bluetooth                                       | 16        | 17.78%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 10        | 11.11%  |
| Intel AX200 Bluetooth                                       | 4         | 4.44%   |
| Realtek Bluetooth Adapter                                   | 3         | 3.33%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 3         | 3.33%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 2         | 2.22%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 2         | 2.22%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 2.22%   |
| Intel AX211 Bluetooth                                       | 2         | 2.22%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 2         | 2.22%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 2         | 2.22%   |
| Dell DW375 Bluetooth Module                                 | 2         | 2.22%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 1         | 1.11%   |
| Ralink RT3290 Bluetooth                                     | 1         | 1.11%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 1.11%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 1.11%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 1.11%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 1.11%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 1.11%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 1.11%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 1.11%   |
| Lite-On MediaTek Bluetooth MT7921                           | 1         | 1.11%   |
| Lite-On BCM43142A0 Bluetooth Module                         | 1         | 1.11%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 1.11%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 1.11%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 1         | 1.11%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 1         | 1.11%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 1         | 1.11%   |
| Dell Broadcom BCM20702A0 Bluetooth                          | 1         | 1.11%   |
| Creative Creative Bluetooth Audio W2                        | 1         | 1.11%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 1         | 1.11%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 1         | 1.11%   |
| Apple Bluetooth Host Controller                             | 1         | 1.11%   |
| Alps Electric UGTZ4 Bluetooth                               | 1         | 1.11%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel           | 97        | 72.93%  |
| AMD             | 19        | 14.29%  |
| Nvidia          | 11        | 8.27%   |
| Plantronics     | 2         | 1.5%    |
| SteelSeries ApS | 1         | 0.75%   |
| Sony            | 1         | 0.75%   |
| Lenovo          | 1         | 0.75%   |
| GN Netcom       | 1         | 0.75%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 15        | 9.43%   |
| AMD Family 17h/19h HD Audio Controller                                     | 13        | 8.18%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11        | 6.92%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9         | 5.66%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 7         | 4.4%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 7         | 4.4%    |
| Intel Comet Lake PCH-LP cAVS                                               | 6         | 3.77%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 6         | 3.77%   |
| Intel Cannon Lake PCH cAVS                                                 | 6         | 3.77%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 3.14%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 3.14%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 3.14%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 2.52%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 2.52%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 1.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 1.89%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 1.89%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 1.89%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 1.89%   |
| Plantronics Plantronics Blackwire 315.1                                    | 2         | 1.26%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 1.26%   |
| Nvidia GT216 HDMI Audio Controller                                         | 2         | 1.26%   |
| Intel Jasper Lake HD Audio                                                 | 2         | 1.26%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 1.26%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.26%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.26%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 2         | 1.26%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 1.26%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 1.26%   |
| AMD FCH Azalia Controller                                                  | 2         | 1.26%   |
| SteelSeries ApS SteelSeries Siberia 350                                    | 1         | 0.63%   |
| Sony UAB-80                                                                | 1         | 0.63%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.63%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.63%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.63%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.63%   |
| Lenovo Realtek USB Audio                                                   | 1         | 0.63%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 0.63%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 0.63%   |
| Intel Crystal Well HD Audio Controller                                     | 1         | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| SK hynix              | 39        | 29.1%   |
| Samsung Electronics   | 37        | 27.61%  |
| Micron Technology     | 13        | 9.7%    |
| Kingston              | 8         | 5.97%   |
| Crucial               | 6         | 4.48%   |
| Unknown               | 6         | 4.48%   |
| Unknown               | 5         | 3.73%   |
| Elpida                | 3         | 2.24%   |
| Unknown (ABCD)        | 2         | 1.49%   |
| Ramaxel Technology    | 2         | 1.49%   |
| KomputerBay           | 2         | 1.49%   |
| A-DATA Technology     | 2         | 1.49%   |
| Transcend             | 1         | 0.75%   |
| PUSKILL               | 1         | 0.75%   |
| PNY                   | 1         | 0.75%   |
| Nanya Technology      | 1         | 0.75%   |
| Kingmax Semiconductor | 1         | 0.75%   |
| Goldkey               | 1         | 0.75%   |
| G.Skill               | 1         | 0.75%   |
| Corsair               | 1         | 0.75%   |
| Apacer                | 1         | 0.75%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 6         | 4.2%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 2.8%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 2.1%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 1.4%    |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 1.4%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.4%    |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                    | 2         | 1.4%    |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s            | 2         | 1.4%    |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 2         | 1.4%    |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 2         | 1.4%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.4%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 2         | 1.4%    |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.4%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.4%    |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 2         | 1.4%    |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 1.4%    |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.4%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s            | 2         | 1.4%    |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1333MT/s           | 2         | 1.4%    |
| KomputerBay RAM KB_8G_D3_1333_C9 8GB SODIMM DDR3 1334MT/s        | 2         | 1.4%    |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s          | 2         | 1.4%    |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                      | 1         | 0.7%    |
| Transcend RAM TS2GSH64V1B 16GB SODIMM DDR4 2133MT/s              | 1         | 0.7%    |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.7%    |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s             | 1         | 0.7%    |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.7%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.7%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.7%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.7%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.7%    |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 0.7%    |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s     | 1         | 0.7%    |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.7%    |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 1         | 0.7%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 1         | 0.7%    |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s          | 1         | 0.7%    |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 0.7%    |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 0.7%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.7%    |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 1         | 0.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 54        | 46.55%  |
| DDR3    | 41        | 35.34%  |
| DDR2    | 7         | 6.03%   |
| LPDDR3  | 6         | 5.17%   |
| LPDDR4  | 5         | 4.31%   |
| SDRAM   | 1         | 0.86%   |
| LPDDR5  | 1         | 0.86%   |
| Unknown | 1         | 0.86%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 102       | 87.93%  |
| Row Of Chips | 12        | 10.34%  |
| Chip         | 1         | 0.86%   |
| Unknown      | 1         | 0.86%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 46        | 38.33%  |
| 4096  | 37        | 30.83%  |
| 16384 | 19        | 15.83%  |
| 2048  | 14        | 11.67%  |
| 32768 | 4         | 3.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 26        | 21.14%  |
| 1600    | 25        | 20.33%  |
| 2667    | 17        | 13.82%  |
| 2400    | 16        | 13.01%  |
| 2133    | 9         | 7.32%   |
| 1334    | 7         | 5.69%   |
| 1333    | 4         | 3.25%   |
| 4267    | 2         | 1.63%   |
| 1867    | 2         | 1.63%   |
| 975     | 2         | 1.63%   |
| 800     | 2         | 1.63%   |
| 667     | 2         | 1.63%   |
| Unknown | 2         | 1.63%   |
| 6400    | 1         | 0.81%   |
| 4266    | 1         | 0.81%   |
| 2048    | 1         | 0.81%   |
| 1866    | 1         | 0.81%   |
| 1596    | 1         | 0.81%   |
| 1067    | 1         | 0.81%   |
| 1066    | 1         | 0.81%   |

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
| Chicony Electronics           | 24        | 27.59%  |
| IMC Networks                  | 14        | 16.09%  |
| Sunplus Innovation Technology | 9         | 10.34%  |
| Microdia                      | 8         | 9.2%    |
| Bison Electronics             | 7         | 8.05%   |
| Syntek                        | 5         | 5.75%   |
| Realtek Semiconductor         | 5         | 5.75%   |
| Luxvisions Innotech Limited   | 3         | 3.45%   |
| Quanta                        | 2         | 2.3%    |
| Lite-On Technology            | 2         | 2.3%    |
| Supreme Electronics           | 1         | 1.15%   |
| Silicon Motion                | 1         | 1.15%   |
| Ricoh                         | 1         | 1.15%   |
| Logitech                      | 1         | 1.15%   |
| Intel                         | 1         | 1.15%   |
| Genesys Logic                 | 1         | 1.15%   |
| DigiTech                      | 1         | 1.15%   |
| Alcor Micro                   | 1         | 1.15%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                       | 5         | 5.56%   |
| Realtek Integrated_Webcam_HD                    | 4         | 4.44%   |
| Microdia Integrated_Webcam_HD                   | 4         | 4.44%   |
| IMC Networks EasyCamera                         | 4         | 4.44%   |
| Bison Integrated Camera                         | 4         | 4.44%   |
| Syntek Integrated Camera                        | 3         | 3.33%   |
| Sunplus Laptop_Integrated_Webcam_FHD            | 3         | 3.33%   |
| Chicony Lenovo Integrated Camera (0.3MP)        | 3         | 3.33%   |
| Syntek EasyCamera                               | 2         | 2.22%   |
| Sunplus Integrated_Webcam_HD                    | 2         | 2.22%   |
| Microdia Integrated Webcam                      | 2         | 2.22%   |
| Luxvisions Innotech Limited Integrated Camera   | 2         | 2.22%   |
| IMC Networks Realtek PC Camera                  | 2         | 2.22%   |
| IMC Networks Realtek DMFT RGB                   | 2         | 2.22%   |
| Chicony USB2.0 VGA UVC WebCam                   | 2         | 2.22%   |
| Chicony HP HD Camera                            | 2         | 2.22%   |
| Chicony HD WebCam                               | 2         | 2.22%   |
| Supreme Integrated Camera                       | 1         | 1.11%   |
| Sunplus Laptop Integrated Webcam HD             | 1         | 1.11%   |
| Sunplus Integrated_Webcam_FHD                   | 1         | 1.11%   |
| Sunplus HP HD Webcam [Fixed]                    | 1         | 1.11%   |
| Sunplus HD WebCam                               | 1         | 1.11%   |
| Silicon Motion WebCam SC-50AFL11C54N            | 1         | 1.11%   |
| Silicon Motion Realtek USB 2.0 PC Camera        | 1         | 1.11%   |
| Ricoh Integrated Webcam                         | 1         | 1.11%   |
| Realtek Integrated Webcam HD                    | 1         | 1.11%   |
| Quanta VGA WebCam                               | 1         | 1.11%   |
| Quanta HD Webcam                                | 1         | 1.11%   |
| Microdia Lenovo EasyCamera                      | 1         | 1.11%   |
| Microdia Laptop_Integrated_Webcam_HD            | 1         | 1.11%   |
| Luxvisions Innotech Limited HP Universal Camera | 1         | 1.11%   |
| Logitech HD Pro Webcam C920                     | 1         | 1.11%   |
| Lite-On Integrated Camera                       | 1         | 1.11%   |
| Lite-On HP Wide Vision HD Camera                | 1         | 1.11%   |
| Intel RealSense 3D Camera (Front F200)          | 1         | 1.11%   |
| IMC Networks USB2.0 HD UVC WebCam               | 1         | 1.11%   |
| IMC Networks SunplusIT Integrated Camera        | 1         | 1.11%   |
| IMC Networks Integrated Webcam                  | 1         | 1.11%   |
| IMC Networks Integrated Camera                  | 1         | 1.11%   |
| IMC Networks HP TrueVision HD Camera            | 1         | 1.11%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 6         | 42.86%  |
| Validity Sensors           | 3         | 21.43%  |
| Elan Microelectronics      | 2         | 14.29%  |
| Upek                       | 1         | 7.14%   |
| Shenzhen Goodix Technology | 1         | 7.14%   |
| LighTuning Technology      | 1         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 2         | 14.29%  |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 14.29%  |
| Elan Fingerprint Sensor                                  | 2         | 14.29%  |
| Validity Sensors VFS5011 Fingerprint Reader              | 1         | 7.14%   |
| Validity Sensors VFS 5011 fingerprint sensor             | 1         | 7.14%   |
| Validity Sensors Synaptics WBDI                          | 1         | 7.14%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 1         | 7.14%   |
| Synaptics UWP WBDI                                       | 1         | 7.14%   |
| Synaptics Metallica MIS Touch Fingerprint Reader         | 1         | 7.14%   |
| Shenzhen Goodix Fingerprint Reader                       | 1         | 7.14%   |
| LighTuning EgisTec Touch Fingerprint Sensor              | 1         | 7.14%   |

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
| 2     | 40        | 34.48%  |
| 1     | 36        | 31.03%  |
| 3     | 25        | 21.55%  |
| 4     | 7         | 6.03%   |
| 0     | 7         | 6.03%   |
| 5     | 1         | 0.86%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 84        | 42%     |
| Bluetooth                | 48        | 24%     |
| Net/wireless             | 22        | 11%     |
| Card reader              | 15        | 7.5%    |
| Fingerprint reader       | 13        | 6.5%    |
| Firewire controller      | 10        | 5%      |
| Storage                  | 3         | 1.5%    |
| Network                  | 2         | 1%      |
| Net/ethernet             | 2         | 1%      |
| Sound                    | 1         | 0.5%    |

