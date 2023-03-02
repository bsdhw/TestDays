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

Total: 130

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| amd64 | 107       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| XFCE          | 21        | 19.63%  |
| KDE5          | 20        | 18.69%  |
| Console       | 17        | 15.89%  |
| GNOME         | 15        | 14.02%  |
| TWM           | 9         | 8.41%   |
| MATE          | 8         | 7.48%   |
| i3            | 5         | 4.67%   |
| Openbox       | 4         | 3.74%   |
| Cinnamon      | 2         | 1.87%   |
| X-Cinnamon    | 1         | 0.93%   |
| LXQt          | 1         | 0.93%   |
| LXDE          | 1         | 0.93%   |
| IceWM         | 1         | 0.93%   |
| Enlightenment | 1         | 0.93%   |
| dwm           | 1         | 0.93%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 84        | 78.5%   |
| Console | 15        | 14.02%  |
| Wayland | 8         | 7.48%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 37        | 34.58%  |
| SDDM    | 24        | 22.43%  |
| SLiM    | 14        | 13.08%  |
| LightDM | 11        | 10.28%  |
| GDM     | 11        | 10.28%  |
| XDM     | 7         | 6.54%   |
| Ly      | 2         | 1.87%   |
| PCDM    | 1         | 0.93%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| C               | 74        | 68.52%  |
| en_US           | 17        | 15.74%  |
| Unknown         | 5         | 4.63%   |
| zh_CN           | 4         | 3.7%    |
| ru_RU           | 3         | 2.78%   |
| ko_KR           | 1         | 0.93%   |
| fr_FR           | 1         | 0.93%   |
| es_ES           | 1         | 0.93%   |
| en_US.ISO8859-1 | 1         | 0.93%   |
| en_AU           | 1         | 0.93%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 87        | 81.31%  |
| BIOS | 20        | 18.69%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Zfs  | 75        | 69.44%  |
| Ufs  | 33        | 30.56%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 98        | 91.59%  |
| MBR     | 7         | 6.54%   |
| BSD     | 1         | 0.93%   |
| Unknown | 1         | 0.93%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 34        | 31.78%  |
| Dell                | 25        | 23.36%  |
| ASUSTek Computer    | 10        | 9.35%   |
| Hewlett-Packard     | 8         | 7.48%   |
| Acer                | 5         | 4.67%   |
| TUXEDO              | 3         | 2.8%    |
| Samsung Electronics | 3         | 2.8%    |
| Google              | 3         | 2.8%    |
| Toshiba             | 2         | 1.87%   |
| System76            | 2         | 1.87%   |
| Unknown             | 2         | 1.87%   |
| Sony                | 1         | 0.93%   |
| Panasonic           | 1         | 0.93%   |
| Notebook            | 1         | 0.93%   |
| MSI                 | 1         | 0.93%   |
| LG Electronics      | 1         | 0.93%   |
| GPD                 | 1         | 0.93%   |
| Fujitsu Siemens     | 1         | 0.93%   |
| Fujitsu             | 1         | 0.93%   |
| Apple               | 1         | 0.93%   |
| Alienware           | 1         | 0.93%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| HP EliteBook 850 G7 Notebook PC             | 2         | 1.87%   |
| Google Peppy                                | 2         | 1.87%   |
| Dell Precision M4500                        | 2         | 1.87%   |
| Dell Latitude E6420                         | 2         | 1.87%   |
| Unknown                                     | 2         | 1.87%   |
| TUXEDO InfinityBook13V3                     | 1         | 0.93%   |
| TUXEDO InfinityBook Pro 14 Gen6             | 1         | 0.93%   |
| TUXEDO Aura 15 Gen1                         | 1         | 0.93%   |
| Toshiba Satellite L305D                     | 1         | 0.93%   |
| Toshiba Satellite A300                      | 1         | 0.93%   |
| System76 Gazelle                            | 1         | 0.93%   |
| System76 Galago Pro                         | 1         | 0.93%   |
| Sony VGN-NS21M_S                            | 1         | 0.93%   |
| Samsung R530/R730/R540                      | 1         | 0.93%   |
| Samsung 750TDA                              | 1         | 0.93%   |
| Samsung 700T1C                              | 1         | 0.93%   |
| Panasonic CF-30KAPAXAM                      | 1         | 0.93%   |
| Notebook N7x0WU                             | 1         | 0.93%   |
| MSI GF63 Thin 9SC                           | 1         | 0.93%   |
| LG 17Z990-R.AAC9U1                          | 1         | 0.93%   |
| Lenovo XiaoXinPro-13API 2019 81XD           | 1         | 0.93%   |
| Lenovo ThinkPad X270 20HMCTO1WW             | 1         | 0.93%   |
| Lenovo ThinkPad X260 20F6S0KA00             | 1         | 0.93%   |
| Lenovo ThinkPad X250 20CMS0FA00             | 1         | 0.93%   |
| Lenovo ThinkPad X220 4291LF6                | 1         | 0.93%   |
| Lenovo ThinkPad X220 4286CTO                | 1         | 0.93%   |
| Lenovo ThinkPad X13 Gen 1 20UF000QRT        | 1         | 0.93%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TKS0QB00 | 1         | 0.93%   |
| Lenovo ThinkPad X1 Carbon Gen 10 21CBCTO1WW | 1         | 0.93%   |
| Lenovo ThinkPad X1 Carbon 7th 20QES53R00    | 1         | 0.93%   |
| Lenovo ThinkPad X1 Carbon 5th 20HR002MAT    | 1         | 0.93%   |
| Lenovo ThinkPad W520 4282AD4                | 1         | 0.93%   |
| Lenovo ThinkPad T480s 20L7002CUS            | 1         | 0.93%   |
| Lenovo ThinkPad T480 20L6SB2N00             | 1         | 0.93%   |
| Lenovo ThinkPad T480 20L6S29E0T             | 1         | 0.93%   |
| Lenovo ThinkPad T440p 20AWS0Y40T            | 1         | 0.93%   |
| Lenovo ThinkPad T420s 41732AU               | 1         | 0.93%   |
| Lenovo ThinkPad T420 4236C92                | 1         | 0.93%   |
| Lenovo ThinkPad T14 Gen 1 20S0CTO1WW        | 1         | 0.93%   |
| Lenovo ThinkPad P14s Gen 3 21AK000GUK       | 1         | 0.93%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 22        | 20.56%  |
| Dell Latitude           | 10        | 9.35%   |
| Lenovo IdeaPad          | 6         | 5.61%   |
| Dell Precision          | 5         | 4.67%   |
| Dell Inspiron           | 5         | 4.67%   |
| ASUS ZenBook            | 4         | 3.74%   |
| HP ProBook              | 3         | 2.8%    |
| ASUS VivoBook           | 3         | 2.8%    |
| Acer Aspire             | 3         | 2.8%    |
| Toshiba Satellite       | 2         | 1.87%   |
| Lenovo Legion           | 2         | 1.87%   |
| HP EliteBook            | 2         | 1.87%   |
| Google Peppy            | 2         | 1.87%   |
| Dell Vostro             | 2         | 1.87%   |
| Unknown                 | 2         | 1.87%   |
| TUXEDO InfinityBook13V3 | 1         | 0.93%   |
| TUXEDO InfinityBook     | 1         | 0.93%   |
| TUXEDO Aura             | 1         | 0.93%   |
| System76 Gazelle        | 1         | 0.93%   |
| System76 Galago         | 1         | 0.93%   |
| Sony VGN-NS21M          | 1         | 0.93%   |
| Samsung R530            | 1         | 0.93%   |
| Samsung 750TDA          | 1         | 0.93%   |
| Samsung 700T1C          | 1         | 0.93%   |
| Panasonic CF-30KAPAXAM  | 1         | 0.93%   |
| Notebook N7x0WU         | 1         | 0.93%   |
| MSI GF63                | 1         | 0.93%   |
| LG 17Z990-R.AAC9U1      | 1         | 0.93%   |
| Lenovo XiaoXinPro-13API | 1         | 0.93%   |
| Lenovo ThinkBook        | 1         | 0.93%   |
| Lenovo G40-45           | 1         | 0.93%   |
| Lenovo B590             | 1         | 0.93%   |
| HP Pavilion             | 1         | 0.93%   |
| HP Laptop               | 1         | 0.93%   |
| HP ENVY                 | 1         | 0.93%   |
| GPD MicroPC             | 1         | 0.93%   |
| Google Lars             | 1         | 0.93%   |
| Fujitsu Siemens AMILO   | 1         | 0.93%   |
| Fujitsu LIFEBOOK        | 1         | 0.93%   |
| Dell XPS                | 1         | 0.93%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2022 | 18        | 16.82%  |
| 2020 | 15        | 14.02%  |
| 2021 | 12        | 11.21%  |
| 2018 | 10        | 9.35%   |
| 2019 | 9         | 8.41%   |
| 2011 | 8         | 7.48%   |
| 2016 | 6         | 5.61%   |
| 2012 | 6         | 5.61%   |
| 2015 | 5         | 4.67%   |
| 2017 | 4         | 3.74%   |
| 2010 | 4         | 3.74%   |
| 2013 | 3         | 2.8%    |
| 2009 | 3         | 2.8%    |
| 2014 | 2         | 1.87%   |
| 2008 | 2         | 1.87%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 107       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 103       | 96.26%  |
| Yes  | 4         | 3.74%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 37        | 34.58%  |
| 16.01-24.0  | 35        | 32.71%  |
| 4.01-8.0    | 18        | 16.82%  |
| 32.01-64.0  | 9         | 8.41%   |
| 24.01-32.0  | 3         | 2.8%    |
| 64.01-256.0 | 3         | 2.8%    |
| 2.01-3.0    | 2         | 1.87%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 41        | 38.32%  |
| 0.51-1.0  | 35        | 32.71%  |
| 1.01-2.0  | 23        | 21.5%   |
| 2.01-3.0  | 7         | 6.54%   |
| 8.01-16.0 | 1         | 0.93%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 80        | 74.77%  |
| 2      | 21        | 19.63%  |
| 0      | 5         | 4.67%   |
| 3      | 1         | 0.93%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 80        | 74.77%  |
| Yes       | 27        | 25.23%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 76        | 71.03%  |
| No        | 31        | 28.97%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 106       | 99.07%  |
| No        | 1         | 0.93%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 79        | 73.83%  |
| No        | 28        | 26.17%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 23        | 21.3%   |
| Russia      | 10        | 9.26%   |
| China       | 7         | 6.48%   |
| France      | 6         | 5.56%   |
| UK          | 5         | 4.63%   |
| India       | 5         | 4.63%   |
| Spain       | 4         | 3.7%    |
| Czechia     | 4         | 3.7%    |
| Austria     | 4         | 3.7%    |
| Japan       | 3         | 2.78%   |
| Germany     | 3         | 2.78%   |
| Turkey      | 2         | 1.85%   |
| Thailand    | 2         | 1.85%   |
| South Korea | 2         | 1.85%   |
| Philippines | 2         | 1.85%   |
| Netherlands | 2         | 1.85%   |
| Italy       | 2         | 1.85%   |
| Canada      | 2         | 1.85%   |
| Venezuela   | 1         | 0.93%   |
| Uruguay     | 1         | 0.93%   |
| Slovenia    | 1         | 0.93%   |
| Poland      | 1         | 0.93%   |
| Norway      | 1         | 0.93%   |
| Mexico      | 1         | 0.93%   |
| Malaysia    | 1         | 0.93%   |
| Lithuania   | 1         | 0.93%   |
| Israel      | 1         | 0.93%   |
| Iraq        | 1         | 0.93%   |
| Hungary     | 1         | 0.93%   |
| Hong Kong   | 1         | 0.93%   |
| Guadeloupe  | 1         | 0.93%   |
| Greece      | 1         | 0.93%   |
| Finland     | 1         | 0.93%   |
| Chile       | 1         | 0.93%   |
| Bulgaria    | 1         | 0.93%   |
| Belarus     | 1         | 0.93%   |
| Australia   | 1         | 0.93%   |
| Argentina   | 1         | 0.93%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Moscow             | 6         | 5.56%   |
| Vienna             | 4         | 3.7%    |
| Paris              | 2         | 1.85%   |
| Fayetteville       | 2         | 1.85%   |
| Carry-le-Rouet     | 2         | 1.85%   |
| Brno               | 2         | 1.85%   |
| Barcelona          | 2         | 1.85%   |
| Zhumadian          | 1         | 0.93%   |
| Yangcheon-gu       | 1         | 0.93%   |
| Xiamen             | 1         | 0.93%   |
| Xi'an              | 1         | 0.93%   |
| Woerdense Verlaat  | 1         | 0.93%   |
| Wheatland          | 1         | 0.93%   |
| Vilnius            | 1         | 0.93%   |
| Villapresente      | 1         | 0.93%   |
| Uiwang-si          | 1         | 0.93%   |
| Turku              | 1         | 0.93%   |
| Trivandrum         | 1         | 0.93%   |
| Tlalnepantla       | 1         | 0.93%   |
| Thousand Oaks      | 1         | 0.93%   |
| Thessaloniki       | 1         | 0.93%   |
| Tel Aviv           | 1         | 0.93%   |
| Taito              | 1         | 0.93%   |
| Stratford          | 1         | 0.93%   |
| St Petersburg      | 1         | 0.93%   |
| Shinjuku           | 1         | 0.93%   |
| Shah Alam          | 1         | 0.93%   |
| Santiago           | 1         | 0.93%   |
| Sandefjord         | 1         | 0.93%   |
| San Pablo City     | 1         | 0.93%   |
| San Antonio        | 1         | 0.93%   |
| Samokov            | 1         | 0.93%   |
| Ruislip            | 1         | 0.93%   |
| Riverside          | 1         | 0.93%   |
| Queens             | 1         | 0.93%   |
| Qiqihar            | 1         | 0.93%   |
| Qinnan             | 1         | 0.93%   |
| Ozersk             | 1         | 0.93%   |
| Oswego             | 1         | 0.93%   |
| Ostrozska Nova Ves | 1         | 0.93%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 23        | 25     | 19.17%  |
| Samsung Electronics | 23        | 24     | 19.17%  |
| Kingston            | 9         | 10     | 7.5%    |
| Seagate             | 7         | 8      | 5.83%   |
| Crucial             | 7         | 8      | 5.83%   |
| Toshiba             | 6         | 7      | 5%      |
| SK hynix            | 6         | 6      | 5%      |
| Transcend           | 4         | 4      | 3.33%   |
| A-DATA Technology   | 4         | 7      | 3.33%   |
| KIOXIA              | 3         | 3      | 2.5%    |
| Intel               | 3         | 3      | 2.5%    |
| Hitachi             | 3         | 3      | 2.5%    |
| Gigabyte Technology | 3         | 3      | 2.5%    |
| Silicon Motion      | 2         | 2      | 1.67%   |
| SanDisk             | 2         | 2      | 1.67%   |
| XPG                 | 1         | 1      | 0.83%   |
| UMIS                | 1         | 1      | 0.83%   |
| SSSTC               | 1         | 1      | 0.83%   |
| PNY                 | 1         | 1      | 0.83%   |
| Micron Technology   | 1         | 1      | 0.83%   |
| Lexar               | 1         | 2      | 0.83%   |
| Lenovo              | 1         | 1      | 0.83%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.83%   |
| Hikvision           | 1         | 1      | 0.83%   |
| Hewlett-Packard     | 1         | 1      | 0.83%   |
| EAGET               | 1         | 1      | 0.83%   |
| CFD                 | 1         | 1      | 0.83%   |
| BR                  | 1         | 1      | 0.83%   |
| BIWIN               | 1         | 1      | 0.83%   |
| Apple               | 1         | 1      | 0.83%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB             | 3         | 2.4%    |
| WDC WDS100T2B0C-00PXH0 1TB              | 2         | 1.6%    |
| WDC WD3200BPVT-80JJ5T0 320GB            | 2         | 1.6%    |
| WDC PC SN530 SDBPNPZ-256G-1014 256GB    | 2         | 1.6%    |
| SK hynix BC511 HFM512GDJTNI-82A0A 512GB | 2         | 1.6%    |
| Samsung SSD 970 EVO Plus 2TB            | 2         | 1.6%    |
| KIOXIA KBG40ZNS512G NVMe 512GB          | 2         | 1.6%    |
| Crucial CT1000MX500SSD1 1TB             | 2         | 1.6%    |
| XPG GAMMIX S5 1TB                       | 1         | 0.8%    |
| WDC WDS500G3X0C-00SJG0 500GB            | 1         | 0.8%    |
| WDC WDS480G2G0A-00JH30 480GB            | 1         | 0.8%    |
| WDC WDS250G2B0B-00YS70 250GB            | 1         | 0.8%    |
| WDC WDS240G2G0A-00JH30 240GB            | 1         | 0.8%    |
| WDC WDS120G2G0B-00EPW0 120GB            | 1         | 0.8%    |
| WDC WD3200BPVT-22JJ5T0 320GB            | 1         | 0.8%    |
| WDC WD3200BEKT-60PVMT0 320GB            | 1         | 0.8%    |
| WDC WD2500BEVT-24A23T0 250GB            | 1         | 0.8%    |
| WDC WD20SPZX-00UA7T0 2TB                | 1         | 0.8%    |
| WDC WD1600BEVT-80A23T0 160GB            | 1         | 0.8%    |
| WDC WD1600BEVT-75ZCT2 160GB             | 1         | 0.8%    |
| WDC WD1600BEVT-22ZCT0 160GB             | 1         | 0.8%    |
| WDC WD10SPZX-75Z10T3 1TB                | 1         | 0.8%    |
| WDC WD10SPZX-17Z10T1 1TB                | 1         | 0.8%    |
| WDC WD10JPVX-22JC3T0 1TB                | 1         | 0.8%    |
| WDC WD10JPCX-24UE4T0 1TB                | 1         | 0.8%    |
| WDC WD10EZEX-60WN4A0 1TB                | 1         | 0.8%    |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB      | 1         | 0.8%    |
| WDC PC SN530 NVMe 256GB                 | 1         | 0.8%    |
| UMIS RPJTJ256MEE1OWX 256GB              | 1         | 0.8%    |
| Transcend TS512GSSD230S 512GB           | 1         | 0.8%    |
| Transcend TS256GMTS430S 256GB           | 1         | 0.8%    |
| Transcend TS1TMTE110S 1TB               | 1         | 0.8%    |
| Transcend TS128GMTS430S 128GB           | 1         | 0.8%    |
| Toshiba MQ04ABF100 1TB                  | 1         | 0.8%    |
| Toshiba MQ01ABF050 500GB                | 1         | 0.8%    |
| Toshiba MQ01ABD100 1TB                  | 1         | 0.8%    |
| Toshiba KXG50ZNV1T02 NVMe 1024GB        | 1         | 0.8%    |
| Toshiba KSG60ZMV256G M.2 2280 256GB     | 1         | 0.8%    |
| Toshiba KBG30ZMT512G 512GB              | 1         | 0.8%    |
| SSSTC CL1-8D256-HP 256GB                | 1         | 0.8%    |

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
| Samsung Electronics | 8         | 8      | 18.18%  |
| Kingston            | 6         | 7      | 13.64%  |
| Crucial             | 6         | 7      | 13.64%  |
| WDC                 | 4         | 4      | 9.09%   |
| Transcend           | 3         | 3      | 6.82%   |
| A-DATA Technology   | 3         | 6      | 6.82%   |
| SanDisk             | 2         | 2      | 4.55%   |
| Toshiba             | 1         | 1      | 2.27%   |
| PNY                 | 1         | 1      | 2.27%   |
| Lexar               | 1         | 2      | 2.27%   |
| Lenovo              | 1         | 1      | 2.27%   |
| KIOXIA-EXCERIA      | 1         | 1      | 2.27%   |
| Hikvision           | 1         | 1      | 2.27%   |
| Hewlett-Packard     | 1         | 1      | 2.27%   |
| Gigabyte Technology | 1         | 1      | 2.27%   |
| CFD                 | 1         | 1      | 2.27%   |
| BR                  | 1         | 1      | 2.27%   |
| BIWIN               | 1         | 1      | 2.27%   |
| Apple               | 1         | 1      | 2.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 49        | 53     | 42.98%  |
| SSD  | 40        | 50     | 35.09%  |
| HDD  | 25        | 28     | 21.93%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 62        | 78     | 55.86%  |
| NVMe | 49        | 53     | 44.14%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 42        | 52     | 64.62%  |
| 0.51-1.0   | 19        | 22     | 29.23%  |
| 1.01-2.0   | 4         | 4      | 6.15%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 42        | 39.25%  |
| 251-500    | 30        | 28.04%  |
| 501-1000   | 18        | 16.82%  |
| 51-100     | 8         | 7.48%   |
| 21-50      | 4         | 3.74%   |
| 1001-2000  | 4         | 3.74%   |
| 1-20       | 1         | 0.93%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 84        | 77.78%  |
| 21-50   | 15        | 13.89%  |
| 101-250 | 4         | 3.7%    |
| 51-100  | 4         | 3.7%    |
| 251-500 | 1         | 0.93%   |

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
| Works    | 87        | 108    | 83.65%  |
| Malfunc  | 15        | 20     | 14.42%  |
| Detected | 2         | 3      | 1.92%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 66        | 51.56%  |
| Samsung Electronics            | 16        | 12.5%   |
| AMD                            | 12        | 9.38%   |
| SanDisk                        | 8         | 6.25%   |
| SK hynix                       | 5         | 3.91%   |
| Silicon Motion                 | 3         | 2.34%   |
| KIOXIA                         | 3         | 2.34%   |
| Kingston Technology Company    | 3         | 2.34%   |
| Toshiba                        | 2         | 1.56%   |
| Phison Electronics             | 2         | 1.56%   |
| Union Memory (Shenzhen)        | 1         | 0.78%   |
| Transcend                      | 1         | 0.78%   |
| Solid State Storage Technology | 1         | 0.78%   |
| Realtek Semiconductor          | 1         | 0.78%   |
| Nvidia                         | 1         | 0.78%   |
| Micron/Crucial Technology      | 1         | 0.78%   |
| Micron Technology              | 1         | 0.78%   |
| ADATA Technology               | 1         | 0.78%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 11        | 8.21%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 10        | 7.46%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 8         | 5.97%   |
| Unknown                                                                        | 8         | 5.97%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 7         | 5.22%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 5.22%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 4.48%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 3.73%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 5         | 3.73%   |
| Samsung NVMe SSD Controller 980                                                | 4         | 2.99%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 2.99%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 3         | 2.24%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 3         | 2.24%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 3         | 2.24%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 2.24%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 3         | 2.24%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 2.24%   |
| SK hynix BC511                                                                 | 2         | 1.49%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 1.49%   |
| SanDisk unknown                                                                | 2         | 1.49%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2         | 1.49%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 1.49%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.49%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 1.49%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2         | 1.49%   |
| Toshiba XG5 NVMe SSD Controller                                                | 1         | 0.75%   |
| Toshiba BG3 NVMe SSD Controller                                                | 1         | 0.75%   |
| SanDisk WD Blue SN570 NVMe SSD                                                 | 1         | 0.75%   |
| Samsung SM951 AHCI                                                             | 1         | 0.75%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1         | 0.75%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 0.75%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1         | 0.75%   |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 0.75%   |
| Kingston Company SNVS2000G [NV1 NVMe PCIe SSD 2TB]                             | 1         | 0.75%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 1         | 0.75%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1         | 0.75%   |
| Intel SSD 660P Series                                                          | 1         | 0.75%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 0.75%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 0.75%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 1         | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 69        | 53.08%  |
| NVMe | 48        | 36.92%  |
| RAID | 11        | 8.46%   |
| IDE  | 2         | 1.54%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 91        | 85.05%  |
| AMD    | 16        | 14.95%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz       | 4         | 3.74%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 3         | 2.8%    |
| Intel Core i7-6500U CPU @ 2.50GHz       | 3         | 2.8%    |
| Intel Core i5-8350U CPU @ 1.70GHz       | 3         | 2.8%    |
| Intel Core i5-5200U CPU @ 2.20GHz       | 3         | 2.8%    |
| Intel Core i5-2520M CPU @ 2.50GHz       | 3         | 2.8%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 3         | 2.8%    |
| Intel Core i7-8750H CPU @ 2.20GHz       | 2         | 1.87%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 2         | 1.87%   |
| Intel Core i5-2540M CPU @ 2.60GHz       | 2         | 1.87%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 2         | 1.87%   |
| Intel Core i5-10310U CPU @ 1.70GHz      | 2         | 1.87%   |
| Intel Core i5 CPU M 560 @ 2.67GH        | 2         | 1.87%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 2         | 1.87%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz | 2         | 1.87%   |
| AMD Ryzen 3 5300U with Radeon Graphics  | 2         | 1.87%   |
| Intel Pentium Silver N6000 @ 1.10GHz    | 1         | 0.93%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz  | 1         | 0.93%   |
| Intel Genuine CPU                       | 1         | 0.93%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 0.93%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 1         | 0.93%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 1         | 0.93%   |
| Intel Core i7-4980HQ CPU @ 2.80GHz      | 1         | 0.93%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz      | 1         | 0.93%   |
| Intel Core i7-4712MQ CPU @ 2.30GHz      | 1         | 0.93%   |
| Intel Core i7-4610M CPU @ 3.00GHz       | 1         | 0.93%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 1         | 0.93%   |
| Intel Core i7-3632QM CPU @ 2.20GHz      | 1         | 0.93%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 1         | 0.93%   |
| Intel Core i7-3537U CPU @ 2.00GHz       | 1         | 0.93%   |
| Intel Core i7-2760QM CPU @ 2.40GHz      | 1         | 0.93%   |
| Intel Core i7-2640M CPU @ 2.80GHz       | 1         | 0.93%   |
| Intel Core i7-2620M CPU @ 2.70GHz       | 1         | 0.93%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 1         | 0.93%   |
| Intel Core i7-10610U CPU @ 1.80GHz      | 1         | 0.93%   |
| Intel Core i5-8365U CPU @ 1.60GHz       | 1         | 0.93%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 1         | 0.93%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 1         | 0.93%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 1         | 0.93%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 1         | 0.93%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i7        | 30        | 28.04%  |
| Intel Core i5        | 30        | 28.04%  |
| Other                | 10        | 9.35%   |
| Intel Celeron        | 7         | 6.54%   |
| Intel Core i3        | 5         | 4.67%   |
| Intel Core 2 Duo     | 5         | 4.67%   |
| AMD Ryzen 7          | 4         | 3.74%   |
| AMD Ryzen 3          | 4         | 3.74%   |
| AMD Ryzen 5          | 3         | 2.8%    |
| AMD A8               | 2         | 1.87%   |
| Intel Pentium Silver | 1         | 0.93%   |
| Intel Pentium Dual   | 1         | 0.93%   |
| Intel Genuine        | 1         | 0.93%   |
| Intel Atom           | 1         | 0.93%   |
| AMD Ryzen 7 PRO      | 1         | 0.93%   |
| AMD E2               | 1         | 0.93%   |
| AMD Athlon X2        | 1         | 0.93%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 44        | 41.12%  |
| 4       | 40        | 37.38%  |
| 8       | 7         | 6.54%   |
| 6       | 6         | 5.61%   |
| 16      | 5         | 4.67%   |
| Unknown | 3         | 2.8%    |
| 20      | 1         | 0.93%   |
| 1       | 1         | 0.93%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 107       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 74        | 69.16%  |
| 1       | 30        | 28.04%  |
| Unknown | 3         | 2.8%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 26        | 24.3%   |
| SandyBridge     | 11        | 10.28%  |
| Unknown         | 8         | 7.48%   |
| TigerLake       | 7         | 6.54%   |
| IvyBridge       | 7         | 6.54%   |
| Haswell         | 7         | 6.54%   |
| Skylake         | 6         | 5.61%   |
| Broadwell       | 5         | 4.67%   |
| Zen+            | 3         | 2.8%    |
| Zen 2           | 3         | 2.8%    |
| Westmere        | 3         | 2.8%    |
| Penryn          | 3         | 2.8%    |
| Core            | 3         | 2.8%    |
| Zen             | 2         | 1.87%   |
| Puma            | 2         | 1.87%   |
| IceLake         | 2         | 1.87%   |
| Goldmont plus   | 2         | 1.87%   |
| CometLake       | 2         | 1.87%   |
| Zen 3           | 1         | 0.93%   |
| K8 & K10 hybrid | 1         | 0.93%   |
| Goldmont        | 1         | 0.93%   |
| Excavator       | 1         | 0.93%   |
| Bonnell         | 1         | 0.93%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 86        | 65.65%  |
| Nvidia | 23        | 17.56%  |
| AMD    | 22        | 16.79%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 11        | 8.21%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 7         | 5.22%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 6         | 4.48%   |
| Intel UHD Graphics 620                                                    | 6         | 4.48%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 6         | 4.48%   |
| Intel HD Graphics 5500                                                    | 5         | 3.73%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 5         | 3.73%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 5         | 3.73%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 4         | 2.99%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 4         | 2.99%   |
| Intel HD Graphics 620                                                     | 4         | 2.99%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 3         | 2.24%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 3         | 2.24%   |
| AMD Renoir                                                                | 3         | 2.24%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 3         | 2.24%   |
| AMD Lucienne                                                              | 3         | 2.24%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 2         | 1.49%   |
| Nvidia TU117M                                                             | 2         | 1.49%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 2         | 1.49%   |
| Nvidia GT216GLM [Quadro FX 880M]                                          | 2         | 1.49%   |
| Nvidia GP108BM [GeForce MX250]                                            | 2         | 1.49%   |
| Intel JasperLake [UHD Graphics]                                           | 2         | 1.49%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 2         | 1.49%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 1.49%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 2         | 1.49%   |
| Intel Alder Lake-P Integrated Graphics Controller                         | 2         | 1.49%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 1.49%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                       | 2         | 1.49%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 0.75%   |
| Nvidia TU117GLM [T550 Laptop GPU]                                         | 1         | 0.75%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 0.75%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 0.75%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                   | 1         | 0.75%   |
| Nvidia GM108M [GeForce MX130]                                             | 1         | 0.75%   |
| Nvidia GM108M [GeForce 920MX]                                             | 1         | 0.75%   |
| Nvidia GM107GLM [Quadro M1000M]                                           | 1         | 0.75%   |
| Nvidia GK208BM [GeForce 920M]                                             | 1         | 0.75%   |
| Nvidia GK107M [GeForce GT 650M]                                           | 1         | 0.75%   |
| Nvidia GF108GLM [NVS 5200M]                                               | 1         | 0.75%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                        | 1         | 0.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 59        | 55.14%  |
| Intel + Nvidia | 16        | 14.95%  |
| 1 x AMD        | 13        | 12.15%  |
| 2 x Intel      | 6         | 5.61%   |
| Intel + AMD    | 5         | 4.67%   |
| 1 x Nvidia     | 3         | 2.8%    |
| AMD + Nvidia   | 3         | 2.8%    |
| 2 x Nvidia     | 1         | 0.93%   |
| 2 x AMD        | 1         | 0.93%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 98        | 91.59%  |
| Proprietary | 9         | 8.41%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 92        | 85.98%  |
| 0.51-1.0   | 5         | 4.67%   |
| 0.01-0.5   | 5         | 4.67%   |
| 1.01-2.0   | 2         | 1.87%   |
| 7.01-8.0   | 1         | 0.93%   |
| 5.01-6.0   | 1         | 0.93%   |
| 3.01-4.0   | 1         | 0.93%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 16        | 18.82%  |
| BOE                     | 13        | 15.29%  |
| Chimei Innolux          | 11        | 12.94%  |
| AU Optronics            | 11        | 12.94%  |
| Samsung Electronics     | 7         | 8.24%   |
| Toshiba                 | 2         | 2.35%   |
| Sharp                   | 2         | 2.35%   |
| LGD                     | 2         | 2.35%   |
| Lenovo                  | 2         | 2.35%   |
| CSO                     | 2         | 2.35%   |
| BenQ                    | 2         | 2.35%   |
| AOC                     | 2         | 2.35%   |
| YTH                     | 1         | 1.18%   |
| ViewSonic               | 1         | 1.18%   |
| USR                     | 1         | 1.18%   |
| Unknown (XXX)           | 1         | 1.18%   |
| Sceptre Tech            | 1         | 1.18%   |
| Mi                      | 1         | 1.18%   |
| LG Philips              | 1         | 1.18%   |
| JDI                     | 1         | 1.18%   |
| HannStar                | 1         | 1.18%   |
| Chi Mei Optoelectronics | 1         | 1.18%   |
| ASUSTek Computer        | 1         | 1.18%   |
| Apple                   | 1         | 1.18%   |
| Acer                    | 1         | 1.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LGD LCD Monitor 1600x900                                              | 2         | 2.35%   |
| LG Display LCD Monitor LGD064C 1920x1080 340x190mm 15.3-inch          | 2         | 2.35%   |
| LG Display LCD Monitor LGD02EB 1366x768 310x170mm 13.9-inch           | 2         | 2.35%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch      | 2         | 2.35%   |
| BenQ BL2480 BNQ802C 1920x1080 530x300mm 24.0-inch                     | 2         | 2.35%   |
| YTH HS133PC YTH1330 1920x1080 250x220mm 13.1-inch                     | 1         | 1.18%   |
| ViewSonic LCD Monitor VSCD22B 1920x1080 520x290mm 23.4-inch           | 1         | 1.18%   |
| USR LCD Monitor USR0100 1920x1080 510x290mm 23.1-inch                 | 1         | 1.18%   |
| Unknown (XXX) SMART TV XXX2851 3840x2160                              | 1         | 1.18%   |
| Toshiba TV TSB0200 1920x1080 530x300mm 24.0-inch                      | 1         | 1.18%   |
| Toshiba ScreenXpert- TSB8888 1080x2160 60x130mm 5.6-inch              | 1         | 1.18%   |
| Sharp LCD Monitor SHP143E 3840x2160 350x190mm 15.7-inch               | 1         | 1.18%   |
| Sharp LCD Monitor SHP1421 3200x1800 290x170mm 13.2-inch               | 1         | 1.18%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch        | 1         | 1.18%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch     | 1         | 1.18%   |
| Samsung Electronics LS24A40xU SAM71D1 1920x1080 530x300mm 24.0-inch   | 1         | 1.18%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch  | 1         | 1.18%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 330x210mm 15.4-inch  | 1         | 1.18%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 340x190mm 15.3-inch  | 1         | 1.18%   |
| Samsung Electronics LCD Monitor SDC8B4F 1920x1080 340x190mm 15.3-inch | 1         | 1.18%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 290x170mm 13.2-inch | 1         | 1.18%   |
| Mi 27 NFGL XMIB004 1920x1080 600x330mm 27.0-inch                      | 1         | 1.18%   |
| LG Philips LCD Monitor LPL0120 1280x800 330x210mm 15.4-inch           | 1         | 1.18%   |
| LG Display LCD Monitor LGD6E01 1366x768 340x190mm 15.3-inch           | 1         | 1.18%   |
| LG Display LCD Monitor LGD060A 1920x1080 290x170mm 13.2-inch          | 1         | 1.18%   |
| LG Display LCD Monitor LGD05F8 2560x1600 370x230mm 17.2-inch          | 1         | 1.18%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch          | 1         | 1.18%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch          | 1         | 1.18%   |
| LG Display LCD Monitor LGD0408 1920x1080 280x160mm 12.7-inch          | 1         | 1.18%   |
| LG Display LCD Monitor LGD03DD 1366x768 340x190mm 15.3-inch           | 1         | 1.18%   |
| LG Display LCD Monitor LGD0395 1366x768 340x190mm 15.3-inch           | 1         | 1.18%   |
| LG Display LCD Monitor LGD0353 1366x768 350x190mm 15.7-inch           | 1         | 1.18%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x170mm 13.9-inch           | 1         | 1.18%   |
| LG Display LCD Monitor LGD02DA 1920x1080 380x210mm 17.1-inch          | 1         | 1.18%   |
| LG Display LCD Monitor LGD02D3 1366x768 280x160mm 12.7-inch           | 1         | 1.18%   |
| Lenovo LEN T32h-20 LEN61F1 2560x1440 700x390mm 31.5-inch              | 1         | 1.18%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch              | 1         | 1.18%   |
| JDI LCD Monitor JDI385A 3840x2160 290x170mm 13.2-inch                 | 1         | 1.18%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch             | 1         | 1.18%   |
| CSO LCD Monitor CSO1400 3840x2160 310x170mm 13.9-inch                 | 1         | 1.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 41        | 50.62%  |
| 1366x768 (WXGA)  | 18        | 22.22%  |
| 3840x2160 (4K)   | 5         | 6.17%   |
| 2560x1440 (QHD)  | 4         | 4.94%   |
| 1600x900 (HD+)   | 4         | 4.94%   |
| 2560x1600        | 2         | 2.47%   |
| 1280x800 (WXGA)  | 2         | 2.47%   |
| 3200x1800 (QHD+) | 1         | 1.23%   |
| 2880x1800        | 1         | 1.23%   |
| 2560x1080        | 1         | 1.23%   |
| 1080x2160        | 1         | 1.23%   |
| 1024x600         | 1         | 1.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 31        | 36.47%  |
| 13      | 27        | 31.76%  |
| 12      | 5         | 5.88%   |
| 27      | 4         | 4.71%   |
| 24      | 4         | 4.71%   |
| Unknown | 4         | 4.71%   |
| 23      | 3         | 3.53%   |
| 17      | 2         | 2.35%   |
| 31      | 1         | 1.18%   |
| 29      | 1         | 1.18%   |
| 11      | 1         | 1.18%   |
| 10      | 1         | 1.18%   |
| 5       | 1         | 1.18%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 50        | 59.52%  |
| 201-300     | 14        | 16.67%  |
| 501-600     | 10        | 11.9%   |
| Unknown     | 4         | 4.76%   |
| 601-700     | 3         | 3.57%   |
| 351-400     | 2         | 2.38%   |
| 1-100       | 1         | 1.19%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 62        | 83.78%  |
| 16/10   | 6         | 8.11%   |
| Unknown | 3         | 4.05%   |
| 21/9    | 1         | 1.35%   |
| 11/10   | 1         | 1.35%   |
| 0.46    | 1         | 1.35%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 23        | 27.06%  |
| 81-90          | 21        | 24.71%  |
| 101-110        | 8         | 9.41%   |
| 201-250        | 7         | 8.24%   |
| 71-80          | 6         | 7.06%   |
| 61-70          | 5         | 5.88%   |
| 301-350        | 5         | 5.88%   |
| Unknown        | 4         | 4.71%   |
| 51-60          | 1         | 1.18%   |
| 351-500        | 1         | 1.18%   |
| 41-50          | 1         | 1.18%   |
| 1-40           | 1         | 1.18%   |
| 131-140        | 1         | 1.18%   |
| 121-130        | 1         | 1.18%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 32        | 38.55%  |
| 101-120       | 16        | 19.28%  |
| 51-100        | 15        | 18.07%  |
| 161-240       | 11        | 13.25%  |
| More than 240 | 5         | 6.02%   |
| Unknown       | 4         | 4.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 64        | 59.81%  |
| 0     | 30        | 28.04%  |
| 2     | 13        | 12.15%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 71        | 40.57%  |
| Realtek Semiconductor    | 48        | 27.43%  |
| Qualcomm Atheros         | 24        | 13.71%  |
| Broadcom                 | 9         | 5.14%   |
| Ralink Technology        | 3         | 1.71%   |
| Xiaomi                   | 2         | 1.14%   |
| TP-Link                  | 2         | 1.14%   |
| Samsung Electronics      | 2         | 1.14%   |
| MediaTek                 | 2         | 1.14%   |
| Marvell Technology Group | 2         | 1.14%   |
| Google                   | 2         | 1.14%   |
| Sierra Wireless          | 1         | 0.57%   |
| Sagem                    | 1         | 0.57%   |
| Ralink                   | 1         | 0.57%   |
| Qualcomm                 | 1         | 0.57%   |
| Nvidia                   | 1         | 0.57%   |
| Huawei Technologies      | 1         | 0.57%   |
| HMD Global               | 1         | 0.57%   |
| Arduino SA               | 1         | 0.57%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 28        | 13.73%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 5.88%   |
| Intel Wireless 8265 / 8275                                        | 9         | 4.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 3.92%   |
| Intel Wi-Fi 6 AX201                                               | 6         | 2.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 2.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 2.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 2.45%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 2.45%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 5         | 2.45%   |
| Intel Wireless 7265                                               | 4         | 1.96%   |
| Intel Wi-Fi 6 AX200                                               | 4         | 1.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.47%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 3         | 1.47%   |
| Intel Wireless-AC 9260                                            | 3         | 1.47%   |
| Intel Wireless 8260                                               | 3         | 1.47%   |
| Intel Wireless 7260                                               | 3         | 1.47%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.47%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.47%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.98%   |
| Ralink RT5370 Wireless Adapter                                    | 2         | 0.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 0.98%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.98%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 0.98%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.98%   |
| Intel WiFi Link 5100                                              | 2         | 0.98%   |
| Intel Wi-Fi 6 AX201 160MHz                                        | 2         | 0.98%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 0.98%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.98%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 0.98%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 0.98%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 0.98%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 2         | 0.98%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 2         | 0.98%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.49%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.49%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1         | 0.49%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.49%   |
| Sierra Wireless EM7455                                            | 1         | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 67        | 56.3%   |
| Qualcomm Atheros      | 23        | 19.33%  |
| Realtek Semiconductor | 11        | 9.24%   |
| Broadcom              | 8         | 6.72%   |
| Ralink Technology     | 3         | 2.52%   |
| TP-Link               | 2         | 1.68%   |
| MediaTek              | 2         | 1.68%   |
| Sierra Wireless       | 1         | 0.84%   |
| Sagem                 | 1         | 0.84%   |
| Ralink                | 1         | 0.84%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 9         | 7.56%   |
| Intel Wi-Fi 6 AX201                                            | 6         | 5.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 6         | 5.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 5         | 4.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 4.2%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 4.2%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 5         | 4.2%    |
| Intel Wireless 7265                                            | 4         | 3.36%   |
| Intel Wi-Fi 6 AX200                                            | 4         | 3.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 3         | 2.52%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 3         | 2.52%   |
| Intel Wireless-AC 9260                                         | 3         | 2.52%   |
| Intel Wireless 8260                                            | 3         | 2.52%   |
| Intel Wireless 7260                                            | 3         | 2.52%   |
| Ralink RT5370 Wireless Adapter                                 | 2         | 1.68%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 1.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2         | 1.68%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 1.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 1.68%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 1.68%   |
| Intel WiFi Link 5100                                           | 2         | 1.68%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 2         | 1.68%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 1.68%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 1.68%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 1.68%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 2         | 1.68%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 1.68%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 2         | 1.68%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 0.84%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.84%   |
| Sierra Wireless EM7455                                         | 1         | 0.84%   |
| Sagem XG-76NA 802.11bg                                         | 1         | 0.84%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.84%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 0.84%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.84%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 0.84%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 0.84%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.84%   |
| Realtek Realtek Bluetooth Adapter                              | 1         | 0.84%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 0.84%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 42        | 50.6%   |
| Intel                    | 26        | 31.33%  |
| Xiaomi                   | 2         | 2.41%   |
| Samsung Electronics      | 2         | 2.41%   |
| Qualcomm Atheros         | 2         | 2.41%   |
| Marvell Technology Group | 2         | 2.41%   |
| Google                   | 2         | 2.41%   |
| Broadcom                 | 2         | 2.41%   |
| Qualcomm                 | 1         | 1.2%    |
| Nvidia                   | 1         | 1.2%    |
| HMD Global               | 1         | 1.2%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 28        | 33.73%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 14.46%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 9.64%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 3.61%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 3.61%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 2.41%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 2.41%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.2%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 1.2%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.2%    |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 1.2%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.2%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.2%    |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 1         | 1.2%    |
| Nvidia MCP79 Ethernet                                             | 1         | 1.2%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 1.2%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.2%    |
| Intel Ethernet Connection I219-V                                  | 1         | 1.2%    |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.2%    |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.2%    |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.2%    |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.2%    |
| Intel Ethernet Connection (16) I219-V                             | 1         | 1.2%    |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.2%    |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.2%    |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 1.2%    |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.2%    |
| HMD Global Nokia 5.3 RNDIS Control RNDIS Ethernet Data            | 1         | 1.2%    |
| Google Nexus/Pixel Device (tether+ debug)                         | 1         | 1.2%    |
| Google Nexus/Pixel Device (tether)                                | 1         | 1.2%    |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                 | 1         | 1.2%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 1.2%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 106       | 57.61%  |
| Ethernet | 76        | 41.3%   |
| Modem    | 2         | 1.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 62        | 65.26%  |
| Ethernet | 33        | 34.74%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 74        | 69.16%  |
| 1     | 32        | 29.91%  |
| 0     | 1         | 0.93%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 92        | 85.19%  |
| Yes  | 16        | 14.81%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 50        | 60.98%  |
| Qualcomm Atheros Communications | 8         | 9.76%   |
| IMC Networks                    | 4         | 4.88%   |
| Dell                            | 4         | 4.88%   |
| Realtek Semiconductor           | 3         | 3.66%   |
| Foxconn / Hon Hai               | 3         | 3.66%   |
| Broadcom                        | 3         | 3.66%   |
| Lite-On Technology              | 2         | 2.44%   |
| Ralink                          | 1         | 1.22%   |
| Creative Technology             | 1         | 1.22%   |
| Cambridge Silicon Radio         | 1         | 1.22%   |
| Apple                           | 1         | 1.22%   |
| Alps Electric                   | 1         | 1.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 15        | 18.29%  |
| Intel AX201 Bluetooth                                       | 15        | 18.29%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 9         | 10.98%  |
| Intel AX200 Bluetooth                                       | 4         | 4.88%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 3         | 3.66%   |
| Realtek  Bluetooth Adapter                                  | 2         | 2.44%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 2         | 2.44%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 2         | 2.44%   |
| Intel Intel Wireless Bluetooth                              | 2         | 2.44%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 2.44%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 2         | 2.44%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 2         | 2.44%   |
| Dell DW375 Bluetooth Module                                 | 2         | 2.44%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 1         | 1.22%   |
| Ralink RT3290 Bluetooth                                     | 1         | 1.22%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 1.22%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 1.22%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 1.22%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 1.22%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 1.22%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 1.22%   |
| Lite-On Wireless_Device                                     | 1         | 1.22%   |
| Lite-On BCM43142A0 Bluetooth Module                         | 1         | 1.22%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 1.22%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 1.22%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 1         | 1.22%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 1         | 1.22%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 1         | 1.22%   |
| Dell Broadcom BCM20702A0 Bluetooth                          | 1         | 1.22%   |
| Creative Creative Bluetooth Audio W2                        | 1         | 1.22%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 1         | 1.22%   |
| Apple Bluetooth Host Controller                             | 1         | 1.22%   |
| Alps Electric UGTZ4 Bluetooth                               | 1         | 1.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel           | 90        | 73.17%  |
| AMD             | 18        | 14.63%  |
| Nvidia          | 9         | 7.32%   |
| Plantronics     | 2         | 1.63%   |
| SteelSeries ApS | 1         | 0.81%   |
| Sony            | 1         | 0.81%   |
| Lenovo          | 1         | 0.81%   |
| GN Netcom       | 1         | 0.81%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 15        | 10.14%  |
| AMD Family 17h/19h HD Audio Controller                                     | 12        | 8.11%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11        | 7.43%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 7         | 4.73%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 4.73%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 6         | 4.05%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6         | 4.05%   |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 3.38%   |
| Intel Cannon Lake PCH cAVS                                                 | 5         | 3.38%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 3.38%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 3.38%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 3.38%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 2.7%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 2.7%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 2.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 2.03%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 2.03%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 2.03%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 2.03%   |
| Plantronics Plantronics Blackwire 315.1                                    | 2         | 1.35%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 1.35%   |
| Nvidia GT216 HDMI Audio Controller                                         | 2         | 1.35%   |
| Intel Jasper Lake HD Audio                                                 | 2         | 1.35%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 1.35%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.35%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.35%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 2         | 1.35%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 1.35%   |
| AMD FCH Azalia Controller                                                  | 2         | 1.35%   |
| SteelSeries ApS SteelSeries Siberia 350                                    | 1         | 0.68%   |
| Sony UAB-80                                                                | 1         | 0.68%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.68%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.68%   |
| Lenovo Realtek USB Audio                                                   | 1         | 0.68%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 0.68%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 0.68%   |
| Intel Crystal Well HD Audio Controller                                     | 1         | 0.68%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 0.68%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 0.68%   |
| GN Netcom Jabra SPEAK 510 USB                                              | 1         | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| SK hynix              | 39        | 30.95%  |
| Samsung Electronics   | 34        | 26.98%  |
| Micron Technology     | 11        | 8.73%   |
| Kingston              | 7         | 5.56%   |
| Crucial               | 6         | 4.76%   |
| Unknown               | 5         | 3.97%   |
| Unknown               | 5         | 3.97%   |
| Elpida                | 3         | 2.38%   |
| Unknown (ABCD)        | 2         | 1.59%   |
| Ramaxel Technology    | 2         | 1.59%   |
| KomputerBay           | 2         | 1.59%   |
| A-DATA Technology     | 2         | 1.59%   |
| Transcend             | 1         | 0.79%   |
| PUSKILL               | 1         | 0.79%   |
| PNY                   | 1         | 0.79%   |
| Nanya Technology      | 1         | 0.79%   |
| Kingmax Semiconductor | 1         | 0.79%   |
| G.Skill               | 1         | 0.79%   |
| Corsair               | 1         | 0.79%   |
| Apacer                | 1         | 0.79%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 5         | 3.7%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 2.96%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 2.22%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 1.48%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 1.48%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2133MT/s | 2         | 1.48%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                    | 2         | 1.48%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s            | 2         | 1.48%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 2         | 1.48%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 2         | 1.48%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.48%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 2         | 1.48%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.48%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.48%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 2         | 1.48%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 1.48%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.48%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s            | 2         | 1.48%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1333MT/s           | 2         | 1.48%   |
| KomputerBay RAM KB_8G_D3_1333_C9 8GB SODIMM DDR3 1334MT/s        | 2         | 1.48%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                      | 1         | 0.74%   |
| Transcend RAM TS2GSH64V1B 16GB SODIMM DDR4 2133MT/s              | 1         | 0.74%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.74%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s             | 1         | 0.74%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.74%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.74%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.74%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.74%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.74%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 0.74%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s     | 1         | 0.74%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.74%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 1         | 0.74%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 1         | 0.74%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s          | 1         | 0.74%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 0.74%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 0.74%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.74%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 1         | 0.74%   |
| SK hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 1         | 0.74%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 51        | 47.22%  |
| DDR3    | 37        | 34.26%  |
| DDR2    | 7         | 6.48%   |
| LPDDR4  | 5         | 4.63%   |
| LPDDR3  | 5         | 4.63%   |
| SDRAM   | 1         | 0.93%   |
| LPDDR5  | 1         | 0.93%   |
| Unknown | 1         | 0.93%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 96        | 88.89%  |
| Row Of Chips | 10        | 9.26%   |
| Chip         | 1         | 0.93%   |
| Unknown      | 1         | 0.93%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 42        | 37.5%   |
| 4096  | 33        | 29.46%  |
| 16384 | 19        | 16.96%  |
| 2048  | 14        | 12.5%   |
| 32768 | 4         | 3.57%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 25        | 21.74%  |
| 1600    | 22        | 19.13%  |
| 2667    | 15        | 13.04%  |
| 2400    | 14        | 12.17%  |
| 2133    | 9         | 7.83%   |
| 1334    | 7         | 6.09%   |
| 1333    | 4         | 3.48%   |
| 4267    | 2         | 1.74%   |
| 1867    | 2         | 1.74%   |
| 975     | 2         | 1.74%   |
| 800     | 2         | 1.74%   |
| 667     | 2         | 1.74%   |
| Unknown | 2         | 1.74%   |
| 6400    | 1         | 0.87%   |
| 4266    | 1         | 0.87%   |
| 2666    | 1         | 0.87%   |
| 2048    | 1         | 0.87%   |
| 1866    | 1         | 0.87%   |
| 1067    | 1         | 0.87%   |
| 1066    | 1         | 0.87%   |

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
| Chicony Electronics           | 22        | 27.85%  |
| IMC Networks                  | 14        | 17.72%  |
| Sunplus Innovation Technology | 9         | 11.39%  |
| Microdia                      | 7         | 8.86%   |
| Bison Electronics             | 5         | 6.33%   |
| Syntek                        | 4         | 5.06%   |
| Realtek Semiconductor         | 4         | 5.06%   |
| Luxvisions Innotech Limited   | 3         | 3.8%    |
| Lite-On Technology            | 2         | 2.53%   |
| Sonix Technology              | 1         | 1.27%   |
| Silicon Motion                | 1         | 1.27%   |
| Ricoh                         | 1         | 1.27%   |
| Quanta                        | 1         | 1.27%   |
| Logitech                      | 1         | 1.27%   |
| Intel                         | 1         | 1.27%   |
| Genesys Logic                 | 1         | 1.27%   |
| DigiTech                      | 1         | 1.27%   |
| Alcor Micro                   | 1         | 1.27%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                         | 5         | 6.17%   |
| Microdia Integrated_Webcam_HD                     | 4         | 4.94%   |
| IMC Networks EasyCamera                           | 4         | 4.94%   |
| Bison Integrated Camera                           | 4         | 4.94%   |
| Sunplus Laptop_Integrated_Webcam_FHD              | 3         | 3.7%    |
| Realtek Integrated_Webcam_HD                      | 3         | 3.7%    |
| Chicony Lenovo Integrated Camera (0.3MP)          | 3         | 3.7%    |
| Syntek Integrated Camera                          | 2         | 2.47%   |
| Syntek EasyCamera                                 | 2         | 2.47%   |
| Sunplus Integrated_Webcam_HD                      | 2         | 2.47%   |
| Microdia Integrated Webcam                        | 2         | 2.47%   |
| IMC Networks USB2.0 VGA UVC WebCam                | 2         | 2.47%   |
| IMC Networks USB2.0 HD UVC WebCam                 | 2         | 2.47%   |
| Chicony USB2.0 VGA UVC WebCam                     | 2         | 2.47%   |
| Chicony HP HD Camera                              | 2         | 2.47%   |
| Chicony HD WebCam                                 | 2         | 2.47%   |
| Sunplus Laptop Integrated Webcam HD               | 1         | 1.23%   |
| Sunplus Integrated_Webcam_FHD                     | 1         | 1.23%   |
| Sunplus HP HD Webcam [Fixed]                      | 1         | 1.23%   |
| Sunplus HD WebCam                                 | 1         | 1.23%   |
| Sonix USB2.0 HD UVC WebCam                        | 1         | 1.23%   |
| Silicon Motion WebCam SC-50AFL11C54N              | 1         | 1.23%   |
| Silicon Motion Realtek USB2.0 PC Camera           | 1         | 1.23%   |
| Ricoh Integrated Webcam                           | 1         | 1.23%   |
| Realtek Integrated Webcam HD                      | 1         | 1.23%   |
| Quanta VGA WebCam                                 | 1         | 1.23%   |
| Microdia Laptop_Integrated_Webcam_HD              | 1         | 1.23%   |
| Luxvisions Innotech Limited Integrated RGB Camera | 1         | 1.23%   |
| Luxvisions Innotech Limited Integrated Camera     | 1         | 1.23%   |
| Luxvisions Innotech Limited HP HD Camera          | 1         | 1.23%   |
| Logitech HD Pro Webcam C920                       | 1         | 1.23%   |
| Lite-On Integrated Camera                         | 1         | 1.23%   |
| Lite-On HP Wide Vision HD Camera                  | 1         | 1.23%   |
| Intel RealSense 3D Camera (Front F200)            | 1         | 1.23%   |
| IMC Networks USB2.0 HD IR UVC WebCam              | 1         | 1.23%   |
| IMC Networks SunplusIT Integrated Camera          | 1         | 1.23%   |
| IMC Networks Integrated Webcam                    | 1         | 1.23%   |
| IMC Networks Integrated Camera                    | 1         | 1.23%   |
| IMC Networks HP TrueVision HD Camera              | 1         | 1.23%   |
| IMC Networks HD Camera                            | 1         | 1.23%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 6         | 50%     |
| Validity Sensors           | 3         | 25%     |
| Upek                       | 1         | 8.33%   |
| Shenzhen Goodix Technology | 1         | 8.33%   |
| LighTuning Technology      | 1         | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 16.67%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 2         | 16.67%  |
| Validity Sensors VFS5011 Fingerprint Reader               | 1         | 8.33%   |
| Validity Sensors VFS 5011 fingerprint sensor              | 1         | 8.33%   |
| Validity Sensors Synaptics WBDI                           | 1         | 8.33%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor    | 1         | 8.33%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 1         | 8.33%   |
| Shenzhen Goodix Fingerprint Reader                        | 1         | 8.33%   |
| LighTuning EgisTec EH575                                  | 1         | 8.33%   |
| Unknown                                                   | 1         | 8.33%   |

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
| 2     | 38        | 35.19%  |
| 1     | 35        | 32.41%  |
| 3     | 22        | 20.37%  |
| 4     | 7         | 6.48%   |
| 0     | 5         | 4.63%   |
| 5     | 1         | 0.93%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 80        | 42.78%  |
| Bluetooth                | 43        | 22.99%  |
| Net/wireless             | 21        | 11.23%  |
| Card reader              | 14        | 7.49%   |
| Fingerprint reader       | 11        | 5.88%   |
| Firewire controller      | 10        | 5.35%   |
| Storage                  | 3         | 1.6%    |
| Network                  | 2         | 1.07%   |
| Net/ethernet             | 2         | 1.07%   |
| Sound                    | 1         | 0.53%   |

