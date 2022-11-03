FreeBSD - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------

A project to collect tested hardware configurations for FreeBSD.

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

Total: 1183

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Samsung       | 750TDA                      | [a880b1f616](https://bsd-hardware.info/?probe=a880b1f616) | Nov 02, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0BR0... | [2776d8c350](https://bsd-hardware.info/?probe=2776d8c350) | Oct 30, 2022 |
| Lenovo        | ThinkPad T460 20FMS10N00    | [04ce25bd7f](https://bsd-hardware.info/?probe=04ce25bd7f) | Oct 29, 2022 |
| Dell          | Inspiron 7720               | [6911e08b7e](https://bsd-hardware.info/?probe=6911e08b7e) | Oct 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [caad4323ba](https://bsd-hardware.info/?probe=caad4323ba) | Oct 23, 2022 |
| Dell          | Precision M4500             | [66ded228ea](https://bsd-hardware.info/?probe=66ded228ea) | Oct 20, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | [bc229efed9](https://bsd-hardware.info/?probe=bc229efed9) | Oct 18, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | [0a8b1f727f](https://bsd-hardware.info/?probe=0a8b1f727f) | Oct 17, 2022 |
| Acer          | Aspire A514-54              | [e057b613a0](https://bsd-hardware.info/?probe=e057b613a0) | Oct 17, 2022 |
| Lenovo        | XiaoXinPro-13API 2019 81... | [dfa08657fd](https://bsd-hardware.info/?probe=dfa08657fd) | Oct 16, 2022 |
| Dell          | Inspiron 15 5510            | [22881028bc](https://bsd-hardware.info/?probe=22881028bc) | Oct 16, 2022 |
| Lenovo        | ThinkPad T430 23446FP       | [6b15856d20](https://bsd-hardware.info/?probe=6b15856d20) | Oct 15, 2022 |
| Lenovo        | ThinkPad T440s 20AR003SM... | [df62882c3b](https://bsd-hardware.info/?probe=df62882c3b) | Oct 12, 2022 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | [442a743538](https://bsd-hardware.info/?probe=442a743538) | Oct 08, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | [601029d3fc](https://bsd-hardware.info/?probe=601029d3fc) | Oct 06, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [ce9cfa77aa](https://bsd-hardware.info/?probe=ce9cfa77aa) | Oct 05, 2022 |
| HP            | Compaq 6735s                | [f61208cfea](https://bsd-hardware.info/?probe=f61208cfea) | Oct 05, 2022 |
| HP            | Compaq 6735s                | [718126149c](https://bsd-hardware.info/?probe=718126149c) | Oct 05, 2022 |
| Acer          | TravelMate B115-M           | [86289a60aa](https://bsd-hardware.info/?probe=86289a60aa) | Oct 05, 2022 |
| Acer          | TravelMate B115-M           | [9f4642f6a5](https://bsd-hardware.info/?probe=9f4642f6a5) | Oct 05, 2022 |
| Dell          | Precision 5510              | [f69c9fb0ea](https://bsd-hardware.info/?probe=f69c9fb0ea) | Oct 04, 2022 |
| Lenovo        | Legion 5 15IMH05 82AU       | [d89559e5c2](https://bsd-hardware.info/?probe=d89559e5c2) | Oct 03, 2022 |
| Toshiba       | NB300                       | [c18ae50101](https://bsd-hardware.info/?probe=c18ae50101) | Oct 03, 2022 |
| TUXEDO        | Aura 15 Gen1                | [e83d522905](https://bsd-hardware.info/?probe=e83d522905) | Oct 03, 2022 |
| Dell          | Precision M4500             | [6b987b43b1](https://bsd-hardware.info/?probe=6b987b43b1) | Oct 03, 2022 |
| Dell          | Precision M4800             | [0fcbdeeeb7](https://bsd-hardware.info/?probe=0fcbdeeeb7) | Oct 02, 2022 |
| HP            | 255 G8 Notebook PC          | [f9851a3257](https://bsd-hardware.info/?probe=f9851a3257) | Oct 01, 2022 |
| IBM           | ThinkPad T43 18714AG        | [5fd9a63834](https://bsd-hardware.info/?probe=5fd9a63834) | Sep 30, 2022 |
| Acer          | Swift SF313-52              | [83516dabac](https://bsd-hardware.info/?probe=83516dabac) | Sep 28, 2022 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | [b2024820d1](https://bsd-hardware.info/?probe=b2024820d1) | Sep 26, 2022 |
| Acer          | Swift SF313-52              | [6339e6b468](https://bsd-hardware.info/?probe=6339e6b468) | Sep 25, 2022 |
| Gigabyte      | GB-BSi5A-6200               | [c947635b8f](https://bsd-hardware.info/?probe=c947635b8f) | Sep 25, 2022 |
| Gigabyte      | GB-BSi5A-6200               | [533c7f35f1](https://bsd-hardware.info/?probe=533c7f35f1) | Sep 25, 2022 |
| IBM           | ThinkPad T40 23737CG        | [dfc9b64da2](https://bsd-hardware.info/?probe=dfc9b64da2) | Sep 25, 2022 |
| System76      | Gazelle                     | [d087321049](https://bsd-hardware.info/?probe=d087321049) | Sep 24, 2022 |
| Dell          | System Vostro 3750          | [166fbacd73](https://bsd-hardware.info/?probe=166fbacd73) | Sep 24, 2022 |
| System76      | Gazelle                     | [6d5d4f5021](https://bsd-hardware.info/?probe=6d5d4f5021) | Sep 24, 2022 |
| Acer          | Aspire E5-771               | [0a58077c49](https://bsd-hardware.info/?probe=0a58077c49) | Sep 20, 2022 |
| Toshiba       | PORTEGE R700                | [10b85eccae](https://bsd-hardware.info/?probe=10b85eccae) | Sep 19, 2022 |
| HP            | EliteBook 840 G3            | [322c8947b6](https://bsd-hardware.info/?probe=322c8947b6) | Sep 19, 2022 |
| HP            | EliteBook 840 G3            | [0307c109b5](https://bsd-hardware.info/?probe=0307c109b5) | Sep 19, 2022 |
| Lenovo        | ThinkPad X250 20CL001GUS    | [2f1f82558e](https://bsd-hardware.info/?probe=2f1f82558e) | Sep 18, 2022 |
| Fujitsu       | LIFEBOOK A532               | [91e0f723ea](https://bsd-hardware.info/?probe=91e0f723ea) | Sep 18, 2022 |
| ASUSTek       | X455LJ                      | [431ad10ab2](https://bsd-hardware.info/?probe=431ad10ab2) | Sep 17, 2022 |
| Lenovo        | ThinkPad L420 7829WDY       | [a697be2aa9](https://bsd-hardware.info/?probe=a697be2aa9) | Sep 16, 2022 |
| IBM           | ThinkPad T43 18714AG        | [15a7e37cbf](https://bsd-hardware.info/?probe=15a7e37cbf) | Sep 15, 2022 |
| Google        | Peppy                       | [80ffa77224](https://bsd-hardware.info/?probe=80ffa77224) | Sep 15, 2022 |
| Dell          | Inspiron 15 3511            | [5abbba28de](https://bsd-hardware.info/?probe=5abbba28de) | Sep 11, 2022 |
| Toshiba       | Satellite A200              | [860aea3ce4](https://bsd-hardware.info/?probe=860aea3ce4) | Sep 08, 2022 |
| Dell          | Precision 7540              | [f39c0f4d92](https://bsd-hardware.info/?probe=f39c0f4d92) | Sep 08, 2022 |
| Dell          | Latitude 5310               | [6edf4d34fe](https://bsd-hardware.info/?probe=6edf4d34fe) | Sep 07, 2022 |
| Dell          | Latitude E5470              | [9e798cbfc8](https://bsd-hardware.info/?probe=9e798cbfc8) | Sep 07, 2022 |
| HP            | EliteBook 8570p             | [7c6751649b](https://bsd-hardware.info/?probe=7c6751649b) | Sep 07, 2022 |
| Dell          | Vostro 5415                 | [ef6d4ee660](https://bsd-hardware.info/?probe=ef6d4ee660) | Sep 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [cffed92600](https://bsd-hardware.info/?probe=cffed92600) | Sep 06, 2022 |
| Dell          | Precision 7550              | [d2bf200529](https://bsd-hardware.info/?probe=d2bf200529) | Sep 06, 2022 |
| Dell          | XPS 13 9343                 | [ec74af083f](https://bsd-hardware.info/?probe=ec74af083f) | Sep 04, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [72757feb65](https://bsd-hardware.info/?probe=72757feb65) | Sep 03, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [5d575c85d0](https://bsd-hardware.info/?probe=5d575c85d0) | Sep 03, 2022 |
| Valve         | Jupiter                     | [4e58d828cc](https://bsd-hardware.info/?probe=4e58d828cc) | Sep 01, 2022 |
| Toshiba       | Satellite A300              | [ac185c104b](https://bsd-hardware.info/?probe=ac185c104b) | Aug 31, 2022 |
| Dell          | Latitude 7390               | [bc5eb8e237](https://bsd-hardware.info/?probe=bc5eb8e237) | Aug 29, 2022 |
| Dell          | Precision 7550              | [71f615178f](https://bsd-hardware.info/?probe=71f615178f) | Aug 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [0466d87f04](https://bsd-hardware.info/?probe=0466d87f04) | Aug 25, 2022 |
| HP            | ENVY Notebook               | [7e33273132](https://bsd-hardware.info/?probe=7e33273132) | Aug 25, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [fcfa6205d8](https://bsd-hardware.info/?probe=fcfa6205d8) | Aug 23, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [cc2a81fc1b](https://bsd-hardware.info/?probe=cc2a81fc1b) | Aug 21, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [6184507a45](https://bsd-hardware.info/?probe=6184507a45) | Aug 21, 2022 |
| HP            | Pavilion g6                 | [c146b538e1](https://bsd-hardware.info/?probe=c146b538e1) | Aug 20, 2022 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [560213a2d6](https://bsd-hardware.info/?probe=560213a2d6) | Aug 19, 2022 |
| ASUSTek       | ZenBook 14 UX410UFR         | [2bf0f0ef08](https://bsd-hardware.info/?probe=2bf0f0ef08) | Aug 19, 2022 |
| Google        | Peppy                       | [e2e0a1953d](https://bsd-hardware.info/?probe=e2e0a1953d) | Aug 18, 2022 |
| Acer          | Aspire 4552G                | [a8f8e41c91](https://bsd-hardware.info/?probe=a8f8e41c91) | Aug 14, 2022 |
| Sony          | VGN-UX1XRN                  | [312df080a7](https://bsd-hardware.info/?probe=312df080a7) | Aug 14, 2022 |
| MSI           | GF63 Thin 9SC               | [dacea7c6be](https://bsd-hardware.info/?probe=dacea7c6be) | Aug 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [2da32e59b0](https://bsd-hardware.info/?probe=2da32e59b0) | Aug 14, 2022 |
| Lenovo        | ThinkPad R60e 0658W2M       | [45e44ad953](https://bsd-hardware.info/?probe=45e44ad953) | Aug 10, 2022 |
| Dell          | Inspiron 3581               | [f31cc32515](https://bsd-hardware.info/?probe=f31cc32515) | Aug 04, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [d5e9213bb5](https://bsd-hardware.info/?probe=d5e9213bb5) | Aug 01, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | [f603e648c7](https://bsd-hardware.info/?probe=f603e648c7) | Aug 01, 2022 |
| Lenovo        | ThinkPad T480 20L6S29E0T    | [546fa8380b](https://bsd-hardware.info/?probe=546fa8380b) | Aug 01, 2022 |
| Dell          | Inspiron 5559               | [13baedb59b](https://bsd-hardware.info/?probe=13baedb59b) | Jul 31, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [7b130fb168](https://bsd-hardware.info/?probe=7b130fb168) | Jul 27, 2022 |
| Dell          | Precision 5560              | [3dc82c6d91](https://bsd-hardware.info/?probe=3dc82c6d91) | Jul 23, 2022 |
| Lenovo        | G40-45 80E1                 | [6e31b5f45b](https://bsd-hardware.info/?probe=6e31b5f45b) | Jul 23, 2022 |
| Dell          | Studio XPS 1340             | [642da98e96](https://bsd-hardware.info/?probe=642da98e96) | Jul 21, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [9af051c79f](https://bsd-hardware.info/?probe=9af051c79f) | Jul 17, 2022 |
| Lenovo        | ThinkPad T480 20L6SB2N00    | [6c5c9eefc0](https://bsd-hardware.info/?probe=6c5c9eefc0) | Jul 17, 2022 |
| Sony          | VGN-NS21M_S                 | [c78caf8215](https://bsd-hardware.info/?probe=c78caf8215) | Jul 16, 2022 |
| HP            | EliteBook 8570p             | [978f01c546](https://bsd-hardware.info/?probe=978f01c546) | Jul 16, 2022 |
| Lenovo        | ThinkPad T420 4236C92       | [4067ce2036](https://bsd-hardware.info/?probe=4067ce2036) | Jul 16, 2022 |
| HP            | Laptop 15-bs1xx             | [fe84e9fda5](https://bsd-hardware.info/?probe=fe84e9fda5) | Jul 15, 2022 |
| Lenovo        | ThinkPad X260 20F6S0KA00    | [117014d55f](https://bsd-hardware.info/?probe=117014d55f) | Jul 14, 2022 |
| Lenovo        | ThinkPad T495 20NJ0010PB    | [078888676a](https://bsd-hardware.info/?probe=078888676a) | Jul 13, 2022 |
| Apple         | MacBookAir5,2               | [894b6f82cf](https://bsd-hardware.info/?probe=894b6f82cf) | Jul 13, 2022 |
| Toshiba       | Satellite L305D             | [b0311b8175](https://bsd-hardware.info/?probe=b0311b8175) | Jul 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [7081ddd59c](https://bsd-hardware.info/?probe=7081ddd59c) | Jul 11, 2022 |
| Toshiba       | Satellite L305D             | [ed950787b0](https://bsd-hardware.info/?probe=ed950787b0) | Jul 10, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [ba96a05e5c](https://bsd-hardware.info/?probe=ba96a05e5c) | Jul 08, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [66543e9280](https://bsd-hardware.info/?probe=66543e9280) | Jul 07, 2022 |
| Dell          | Latitude E6420              | [c41c8ff4f4](https://bsd-hardware.info/?probe=c41c8ff4f4) | Jul 07, 2022 |
| Fujitsu       | LIFEBOOK A555               | [d9fd7e54cf](https://bsd-hardware.info/?probe=d9fd7e54cf) | Jul 06, 2022 |
| Unknown       | Unknown                     | [584ecf8423](https://bsd-hardware.info/?probe=584ecf8423) | Jul 05, 2022 |
| HP            | Laptop 15-bs1xx             | [b697848727](https://bsd-hardware.info/?probe=b697848727) | Jul 05, 2022 |
| LG Electro... | 17Z990-R.AAC9U1             | [5777cb6dc6](https://bsd-hardware.info/?probe=5777cb6dc6) | Jul 01, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | [f573327012](https://bsd-hardware.info/?probe=f573327012) | Jun 29, 2022 |
| Acer          | Aspire A114-33              | [d3659c85e9](https://bsd-hardware.info/?probe=d3659c85e9) | Jun 28, 2022 |
| Samsung       | R530/R730/R540              | [a4cd230718](https://bsd-hardware.info/?probe=a4cd230718) | Jun 27, 2022 |
| Lenovo        | ThinkPad X270 20HN001HUS    | [139e4817d7](https://bsd-hardware.info/?probe=139e4817d7) | Jun 21, 2022 |
| Lenovo        | ThinkPad R60e 0658W2M       | [8ad937beaa](https://bsd-hardware.info/?probe=8ad937beaa) | Jun 21, 2022 |
| Dell          | Latitude 5521               | [2c9d24a69e](https://bsd-hardware.info/?probe=2c9d24a69e) | Jun 19, 2022 |
| Fujitsu Si... | AMILO Li3710                | [6d4bc39638](https://bsd-hardware.info/?probe=6d4bc39638) | Jun 18, 2022 |
| Toshiba       | Satellite A300              | [e057898546](https://bsd-hardware.info/?probe=e057898546) | Jun 18, 2022 |
| Sony          | VGN-NS21M_S                 | [c9701a7ff5](https://bsd-hardware.info/?probe=c9701a7ff5) | Jun 18, 2022 |
| Dell          | Latitude E5420              | [524ab094e1](https://bsd-hardware.info/?probe=524ab094e1) | Jun 13, 2022 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | [8825a49f37](https://bsd-hardware.info/?probe=8825a49f37) | Jun 13, 2022 |
| Dell          | Latitude 7390               | [2b888ed291](https://bsd-hardware.info/?probe=2b888ed291) | Jun 12, 2022 |
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
| Dell          | Latitude 5410               | [3334ff3727](https://bsd-hardware.info/?probe=3334ff3727) | Jun 06, 2022 |
| Lenovo        | ThinkPad X220 4286CTO       | [cb98f3014e](https://bsd-hardware.info/?probe=cb98f3014e) | Jun 05, 2022 |
| Dell          | Latitude 7490               | [18215740d1](https://bsd-hardware.info/?probe=18215740d1) | Jun 05, 2022 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | [f3ad761457](https://bsd-hardware.info/?probe=f3ad761457) | Jun 04, 2022 |
| Dell          | Latitude E5500              | [b1cb5de914](https://bsd-hardware.info/?probe=b1cb5de914) | Jun 03, 2022 |
| ASUSTek       | X441UV                      | [c8906b438b](https://bsd-hardware.info/?probe=c8906b438b) | Jun 03, 2022 |
| HP            | EliteBook 8570p             | [1067f6ab27](https://bsd-hardware.info/?probe=1067f6ab27) | Jun 03, 2022 |
| Apple         | MacBookPro11,4              | [29f1ef0cdc](https://bsd-hardware.info/?probe=29f1ef0cdc) | Jun 02, 2022 |
| Lenovo        | ThinkPad W520 4282AD4       | [40198abaa2](https://bsd-hardware.info/?probe=40198abaa2) | Jun 02, 2022 |
| Acer          | Nitro AN515-55              | [0cf6981a98](https://bsd-hardware.info/?probe=0cf6981a98) | Jun 02, 2022 |
| GPD           | MicroPC                     | [a448570ff9](https://bsd-hardware.info/?probe=a448570ff9) | May 31, 2022 |
| Dell          | Inspiron 5559               | [283a074737](https://bsd-hardware.info/?probe=283a074737) | May 31, 2022 |
| Acer          | Aspire E5-576               | [138e9fdeb4](https://bsd-hardware.info/?probe=138e9fdeb4) | May 31, 2022 |
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
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [1cc5f44e4a](https://bsd-hardware.info/?probe=1cc5f44e4a) | May 25, 2022 |
| Lenovo        | IdeaPad S510p 20298         | [c41aea0ea7](https://bsd-hardware.info/?probe=c41aea0ea7) | May 24, 2022 |
| TUXEDO        | Aura 15 Gen1                | [727f9708b4](https://bsd-hardware.info/?probe=727f9708b4) | May 24, 2022 |
| Dell          | Latitude E6540              | [70871cf070](https://bsd-hardware.info/?probe=70871cf070) | May 24, 2022 |
| Dell          | Precision M4800             | [6a703b66f8](https://bsd-hardware.info/?probe=6a703b66f8) | May 22, 2022 |
| Dell          | Latitude E7240              | [970234b430](https://bsd-hardware.info/?probe=970234b430) | May 22, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [ddaca5356c](https://bsd-hardware.info/?probe=ddaca5356c) | May 21, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [cf5f498572](https://bsd-hardware.info/?probe=cf5f498572) | May 21, 2022 |
| Dell          | Latitude 5520               | [cbc2c03fa1](https://bsd-hardware.info/?probe=cbc2c03fa1) | May 20, 2022 |
| Dell          | XPS 13 9343                 | [44abecc1ef](https://bsd-hardware.info/?probe=44abecc1ef) | May 20, 2022 |
| ASUSTek       | 1001P                       | [6ffa9529a3](https://bsd-hardware.info/?probe=6ffa9529a3) | May 20, 2022 |
| ASUSTek       | 1001P                       | [2820584223](https://bsd-hardware.info/?probe=2820584223) | May 20, 2022 |
| HP            | ProBook 455 G7              | [c6944afe69](https://bsd-hardware.info/?probe=c6944afe69) | May 19, 2022 |
| TUXEDO        | Aura 15 Gen1                | [1c84f0f722](https://bsd-hardware.info/?probe=1c84f0f722) | May 19, 2022 |
| Acer          | Aspire 5742                 | [b0ea5e7a5e](https://bsd-hardware.info/?probe=b0ea5e7a5e) | May 19, 2022 |
| Lenovo        | ThinkPad L420 7854CTO       | [56cf502c2f](https://bsd-hardware.info/?probe=56cf502c2f) | May 18, 2022 |
| Lenovo        | ThinkPad T420s 41732AU      | [9d9ddcc409](https://bsd-hardware.info/?probe=9d9ddcc409) | May 18, 2022 |
| Lenovo        | ThinkPad X270 20HMCTO1WW    | [2d3de77101](https://bsd-hardware.info/?probe=2d3de77101) | May 18, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [86866ce217](https://bsd-hardware.info/?probe=86866ce217) | May 17, 2022 |
| TUXEDO        | InfinityBook13V3            | [fd081a3636](https://bsd-hardware.info/?probe=fd081a3636) | May 17, 2022 |
| Dell          | Precision M4800             | [6dc325b553](https://bsd-hardware.info/?probe=6dc325b553) | May 15, 2022 |
| Acer          | Aspire A715-42G             | [991f67362f](https://bsd-hardware.info/?probe=991f67362f) | May 12, 2022 |
| Lenovo        | ThinkPad T495s 20QKS1812... | [89db84f7ec](https://bsd-hardware.info/?probe=89db84f7ec) | May 10, 2022 |
| Dell          | Latitude 2100               | [40406069ee](https://bsd-hardware.info/?probe=40406069ee) | May 09, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [5259bc1933](https://bsd-hardware.info/?probe=5259bc1933) | May 08, 2022 |
| Lenovo        | ThinkPad X250 20CLS02V00    | [7e2771b8f6](https://bsd-hardware.info/?probe=7e2771b8f6) | May 08, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [a69f0fefca](https://bsd-hardware.info/?probe=a69f0fefca) | May 07, 2022 |
| Dell          | Inspiron 15-7568            | [850df51257](https://bsd-hardware.info/?probe=850df51257) | May 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [015bf0fea4](https://bsd-hardware.info/?probe=015bf0fea4) | May 06, 2022 |
| Lenovo        | ThinkPad X220 42872WU       | [e99738632d](https://bsd-hardware.info/?probe=e99738632d) | May 06, 2022 |
| Dell          | Vostro 5590                 | [1f23973fb4](https://bsd-hardware.info/?probe=1f23973fb4) | May 04, 2022 |
| Acer          | Aspire ES1-132              | [18426698ad](https://bsd-hardware.info/?probe=18426698ad) | May 02, 2022 |
| Dell          | Latitude E5570              | [c214ce4ab0](https://bsd-hardware.info/?probe=c214ce4ab0) | May 01, 2022 |
| Toshiba       | Satellite P25               | [6a920e9c8a](https://bsd-hardware.info/?probe=6a920e9c8a) | May 01, 2022 |
| Lenovo        | B50-30 20382                | [5701dac149](https://bsd-hardware.info/?probe=5701dac149) | Apr 30, 2022 |
| HP            | Laptop 15-dw1xxx            | [7a212b5833](https://bsd-hardware.info/?probe=7a212b5833) | Apr 29, 2022 |
| Lenovo        | ThinkPad T470 20HES0ES1F    | [f1f0676663](https://bsd-hardware.info/?probe=f1f0676663) | Apr 28, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [30e267dd51](https://bsd-hardware.info/?probe=30e267dd51) | Apr 27, 2022 |
| Notebook      | N7x0WU                      | [b7c06932a3](https://bsd-hardware.info/?probe=b7c06932a3) | Apr 27, 2022 |
| Framework     | Laptop                      | [5d6cb039ea](https://bsd-hardware.info/?probe=5d6cb039ea) | Apr 25, 2022 |
| Apple         | MacBookPro8,3               | [e588c93d54](https://bsd-hardware.info/?probe=e588c93d54) | Apr 24, 2022 |
| Dell          | Latitude E6520              | [c4ae703add](https://bsd-hardware.info/?probe=c4ae703add) | Apr 23, 2022 |
| Lenovo        | B570 1068FQG                | [a0d1f01226](https://bsd-hardware.info/?probe=a0d1f01226) | Apr 22, 2022 |
| System76      | Lemur Pro                   | [bbeb7d48fa](https://bsd-hardware.info/?probe=bbeb7d48fa) | Apr 17, 2022 |
| HUAWEI        | NBLL-WXX9                   | [d259128717](https://bsd-hardware.info/?probe=d259128717) | Apr 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [eda0880c67](https://bsd-hardware.info/?probe=eda0880c67) | Apr 15, 2022 |
| Dell          | Latitude E6440              | [eea29a3895](https://bsd-hardware.info/?probe=eea29a3895) | Apr 12, 2022 |
| Lenovo        | ThinkPad X201 3680MG1       | [a2b9975fe2](https://bsd-hardware.info/?probe=a2b9975fe2) | Apr 11, 2022 |
| Lenovo        | ThinkPad T460p 20FXS09D1... | [edbde611c3](https://bsd-hardware.info/?probe=edbde611c3) | Apr 11, 2022 |
| Toshiba       | Satellite Pro T130          | [62dd51afcf](https://bsd-hardware.info/?probe=62dd51afcf) | Apr 11, 2022 |
| Lenovo        | ThinkPad X220 42872WU       | [3b7da460a2](https://bsd-hardware.info/?probe=3b7da460a2) | Apr 10, 2022 |
| Lenovo        | ThinkPad T495 20NJ0000US    | [c626b32508](https://bsd-hardware.info/?probe=c626b32508) | Apr 09, 2022 |
| Acer          | Swift SF114-32              | [7bc748ce7c](https://bsd-hardware.info/?probe=7bc748ce7c) | Apr 08, 2022 |
| Dell          | Vostro 1400                 | [7e0964d31d](https://bsd-hardware.info/?probe=7e0964d31d) | Apr 08, 2022 |
| Deciso        | Netboard A20                | [0829d5a85d](https://bsd-hardware.info/?probe=0829d5a85d) | Apr 06, 2022 |
| Dell          | Precision M4800             | [7a7968204a](https://bsd-hardware.info/?probe=7a7968204a) | Apr 06, 2022 |
| Timi          | TM1612                      | [0389c8d487](https://bsd-hardware.info/?probe=0389c8d487) | Apr 05, 2022 |
| ASUSTek       | UX305UA                     | [3fb1786193](https://bsd-hardware.info/?probe=3fb1786193) | Apr 04, 2022 |
| HP            | EliteBook 8570p             | [0c73871c49](https://bsd-hardware.info/?probe=0c73871c49) | Apr 04, 2022 |
| VIT           | M2420                       | [108b4d79a6](https://bsd-hardware.info/?probe=108b4d79a6) | Apr 03, 2022 |
| MSI           | Bravo 15 A4DDR              | [1868573e9a](https://bsd-hardware.info/?probe=1868573e9a) | Apr 02, 2022 |
| Deciso        | OPNsense Appliance          | [cdd056df79](https://bsd-hardware.info/?probe=cdd056df79) | Mar 31, 2022 |
| Lenovo        | ThinkPad X260 20F5A28AUK    | [f53c625efd](https://bsd-hardware.info/?probe=f53c625efd) | Mar 30, 2022 |
| HUAWEI        | CREM-WXX9                   | [e750905413](https://bsd-hardware.info/?probe=e750905413) | Mar 29, 2022 |
| Fujitsu       | LIFEBOOK A544               | [e363c95c1c](https://bsd-hardware.info/?probe=e363c95c1c) | Mar 29, 2022 |
| Deciso        | Netboard A20                | [835d6c060f](https://bsd-hardware.info/?probe=835d6c060f) | Mar 25, 2022 |
| Deciso        | Netboard A20                | [5a6b66aa01](https://bsd-hardware.info/?probe=5a6b66aa01) | Mar 24, 2022 |
| Lenovo        | ThinkPad R60e 0658W2M       | [315573b63e](https://bsd-hardware.info/?probe=315573b63e) | Mar 24, 2022 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | [859a429ad0](https://bsd-hardware.info/?probe=859a429ad0) | Mar 24, 2022 |
| Lenovo        | ThinkPad X230 2325BV9       | [d2a16f6102](https://bsd-hardware.info/?probe=d2a16f6102) | Mar 23, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [693d365311](https://bsd-hardware.info/?probe=693d365311) | Mar 23, 2022 |
| Gateway       | NV55C                       | [a63381d681](https://bsd-hardware.info/?probe=a63381d681) | Mar 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [6858ad2b12](https://bsd-hardware.info/?probe=6858ad2b12) | Mar 22, 2022 |
| HP            | EliteBook 8570p             | [7e1e137c8f](https://bsd-hardware.info/?probe=7e1e137c8f) | Mar 20, 2022 |
| Acer          | Swift SF314-42              | [6a579dca44](https://bsd-hardware.info/?probe=6a579dca44) | Mar 20, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [0dbac1ca61](https://bsd-hardware.info/?probe=0dbac1ca61) | Mar 19, 2022 |
| Dell          | Latitude E7440              | [a776ebf7f4](https://bsd-hardware.info/?probe=a776ebf7f4) | Mar 19, 2022 |
| Toshiba       | Satellite Pro L40           | [5ff92a5bb3](https://bsd-hardware.info/?probe=5ff92a5bb3) | Mar 19, 2022 |
| Toshiba       | Satellite Pro L40           | [71a7b43ec6](https://bsd-hardware.info/?probe=71a7b43ec6) | Mar 19, 2022 |
| Lenovo        | ThinkPad T460s 20FAS4KH0... | [dbb0e378d5](https://bsd-hardware.info/?probe=dbb0e378d5) | Mar 17, 2022 |
| Acer          | Aspire 4820T                | [1617262a28](https://bsd-hardware.info/?probe=1617262a28) | Mar 16, 2022 |
| Acer          | Aspire A315-23              | [7fb743c654](https://bsd-hardware.info/?probe=7fb743c654) | Mar 15, 2022 |
| ASUSTek       | N50Vc                       | [883ded6cb1](https://bsd-hardware.info/?probe=883ded6cb1) | Mar 15, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [dd57366224](https://bsd-hardware.info/?probe=dd57366224) | Mar 15, 2022 |
| Acer          | Aspire A114-33              | [6e7384f4cc](https://bsd-hardware.info/?probe=6e7384f4cc) | Mar 15, 2022 |
| Lenovo        | ThinkPad T420 4236MBU       | [8bd2318fb6](https://bsd-hardware.info/?probe=8bd2318fb6) | Mar 15, 2022 |
| Gateway       | LT27                        | [6d1c6f8215](https://bsd-hardware.info/?probe=6d1c6f8215) | Mar 14, 2022 |
| Dell          | Inspiron 5502               | [9e440b5500](https://bsd-hardware.info/?probe=9e440b5500) | Mar 13, 2022 |
| Apple         | MacBookPro12,1              | [e04a1b354c](https://bsd-hardware.info/?probe=e04a1b354c) | Mar 11, 2022 |
| Apple         | MacBookPro12,1              | [ac59621182](https://bsd-hardware.info/?probe=ac59621182) | Mar 10, 2022 |
| Lenovo        | ThinkPad E580 20KSCTO1WW    | [be311b6a34](https://bsd-hardware.info/?probe=be311b6a34) | Mar 10, 2022 |
| Dell          | G5 5590                     | [0871c1269b](https://bsd-hardware.info/?probe=0871c1269b) | Mar 07, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [20cdc9d999](https://bsd-hardware.info/?probe=20cdc9d999) | Mar 06, 2022 |
| Framework     | Laptop                      | [1f58e0594f](https://bsd-hardware.info/?probe=1f58e0594f) | Mar 01, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1JN0... | [cba9255f4a](https://bsd-hardware.info/?probe=cba9255f4a) | Feb 27, 2022 |
| Dell          | Latitude E5440              | [b0314f9200](https://bsd-hardware.info/?probe=b0314f9200) | Feb 26, 2022 |
| Dell          | Inspiron 5559               | [c34e21ffd5](https://bsd-hardware.info/?probe=c34e21ffd5) | Feb 26, 2022 |
| Dell          | Latitude E6430              | [fdde41404d](https://bsd-hardware.info/?probe=fdde41404d) | Feb 24, 2022 |
| Dell          | Latitude 7480               | [f0e8e4a30a](https://bsd-hardware.info/?probe=f0e8e4a30a) | Feb 21, 2022 |
| Acer          | Aspire A114-33              | [da786acd84](https://bsd-hardware.info/?probe=da786acd84) | Feb 20, 2022 |
| Apple         | MacBookPro10,1              | [64ccf1e6a0](https://bsd-hardware.info/?probe=64ccf1e6a0) | Feb 18, 2022 |
| Lenovo        | V145-15AST 81MT             | [bc5296ee7d](https://bsd-hardware.info/?probe=bc5296ee7d) | Feb 16, 2022 |
| Acer          | Aspire A114-33              | [06887b10fd](https://bsd-hardware.info/?probe=06887b10fd) | Feb 15, 2022 |
| Dell          | Latitude 3420               | [f1796d75ed](https://bsd-hardware.info/?probe=f1796d75ed) | Feb 14, 2022 |
| WOOKING       | X5                          | [1099e6c574](https://bsd-hardware.info/?probe=1099e6c574) | Feb 14, 2022 |
| Apple         | MacBookPro8,1               | [aa484c30a8](https://bsd-hardware.info/?probe=aa484c30a8) | Feb 12, 2022 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | [e4f43cfcad](https://bsd-hardware.info/?probe=e4f43cfcad) | Feb 10, 2022 |
| ASUSTek       | 1215B                       | [1ccf85f60d](https://bsd-hardware.info/?probe=1ccf85f60d) | Feb 10, 2022 |
| ASUSTek       | A9T                         | [2962e2b02f](https://bsd-hardware.info/?probe=2962e2b02f) | Feb 09, 2022 |
| Notebook      | N7x0WU                      | [5063e8f546](https://bsd-hardware.info/?probe=5063e8f546) | Feb 08, 2022 |
| HP            | ProBook 445 G7              | [494195b923](https://bsd-hardware.info/?probe=494195b923) | Feb 08, 2022 |
| Lenovo        | ThinkPad X250 20CMCTO1WW    | [4ba527dc9b](https://bsd-hardware.info/?probe=4ba527dc9b) | Feb 06, 2022 |
| System76      | Lemur Pro                   | [713b33351f](https://bsd-hardware.info/?probe=713b33351f) | Feb 06, 2022 |
| Notebook      | NS50_70MU                   | [3b3ff8b95d](https://bsd-hardware.info/?probe=3b3ff8b95d) | Feb 05, 2022 |
| Lenovo        | Yoga S730-13IWL 81J0        | [f333ed9201](https://bsd-hardware.info/?probe=f333ed9201) | Feb 05, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [e660899158](https://bsd-hardware.info/?probe=e660899158) | Feb 03, 2022 |
| Dell          | Latitude E7450              | [8a3867f171](https://bsd-hardware.info/?probe=8a3867f171) | Feb 03, 2022 |
| HUAWEI        | MACHD-WXX9                  | [3debf6433b](https://bsd-hardware.info/?probe=3debf6433b) | Feb 02, 2022 |
| Lenovo        | Yoga S730-13IWL 81J0        | [c03bfe6a21](https://bsd-hardware.info/?probe=c03bfe6a21) | Feb 01, 2022 |
| Dell          | Vostro 3550                 | [97ef0862c2](https://bsd-hardware.info/?probe=97ef0862c2) | Feb 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [cb0ebb96d5](https://bsd-hardware.info/?probe=cb0ebb96d5) | Feb 01, 2022 |
| Dell          | G3 3500                     | [536a7a1b38](https://bsd-hardware.info/?probe=536a7a1b38) | Jan 31, 2022 |
| Lenovo        | ThinkPad T480s 20L8S1GX0... | [556fcb7e5e](https://bsd-hardware.info/?probe=556fcb7e5e) | Jan 31, 2022 |
| MSI           | Summit E13FlipEvo A11MT     | [61e3f35ee8](https://bsd-hardware.info/?probe=61e3f35ee8) | Jan 31, 2022 |
| ASUSTek       | 1015PEM                     | [efea0efb2b](https://bsd-hardware.info/?probe=efea0efb2b) | Jan 31, 2022 |
| GPD           | G1621-02                    | [1970f517fd](https://bsd-hardware.info/?probe=1970f517fd) | Jan 30, 2022 |
| HP            | Notebook                    | [b0e0bc12c8](https://bsd-hardware.info/?probe=b0e0bc12c8) | Jan 30, 2022 |
| HP            | EliteBook 8570p             | [f47789d894](https://bsd-hardware.info/?probe=f47789d894) | Jan 29, 2022 |
| MSI           | GE76 Raider 10UG            | [b48b628936](https://bsd-hardware.info/?probe=b48b628936) | Jan 27, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [652e2e284f](https://bsd-hardware.info/?probe=652e2e284f) | Jan 26, 2022 |
| Dell          | Inspiron 5555               | [e54be582a7](https://bsd-hardware.info/?probe=e54be582a7) | Jan 25, 2022 |
| MSI           | GT75VR 7RF                  | [db276eaa53](https://bsd-hardware.info/?probe=db276eaa53) | Jan 25, 2022 |
| Fujitsu Si... | AMILO Li 2727               | [268e1621eb](https://bsd-hardware.info/?probe=268e1621eb) | Jan 18, 2022 |
| HP            | EliteBook 8570p             | [61406080a7](https://bsd-hardware.info/?probe=61406080a7) | Jan 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1763a44db9](https://bsd-hardware.info/?probe=1763a44db9) | Jan 18, 2022 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | [2aea9384ac](https://bsd-hardware.info/?probe=2aea9384ac) | Jan 17, 2022 |
| ASUSTek       | N50Vc                       | [468a2d7ab8](https://bsd-hardware.info/?probe=468a2d7ab8) | Jan 17, 2022 |
| Acer          | TravelMate 8481TG           | [fae71f7e35](https://bsd-hardware.info/?probe=fae71f7e35) | Jan 15, 2022 |
| Lenovo        | ThinkPad T460p 20FXS09D1... | [3ef1595af6](https://bsd-hardware.info/?probe=3ef1595af6) | Jan 13, 2022 |
| Lenovo        | ThinkPad E480 20KN0048IA    | [1a2f28f5cc](https://bsd-hardware.info/?probe=1a2f28f5cc) | Jan 11, 2022 |
| Lenovo        | ThinkPad X250 20CL001GUS    | [4ae2360503](https://bsd-hardware.info/?probe=4ae2360503) | Jan 11, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [6c895cb96f](https://bsd-hardware.info/?probe=6c895cb96f) | Jan 10, 2022 |
| Dell          | Latitude E6430              | [e18a4bc564](https://bsd-hardware.info/?probe=e18a4bc564) | Jan 10, 2022 |
| Dell          | Latitude E5430 non-vPro     | [877bb1b29f](https://bsd-hardware.info/?probe=877bb1b29f) | Jan 10, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20T20... | [6836fc60f6](https://bsd-hardware.info/?probe=6836fc60f6) | Jan 09, 2022 |
| MSI           | GT75VR 7RF                  | [cca6cc3c0b](https://bsd-hardware.info/?probe=cca6cc3c0b) | Jan 07, 2022 |
| Dell          | Precision 7530              | [498bfe852c](https://bsd-hardware.info/?probe=498bfe852c) | Jan 07, 2022 |
| TUXEDO        | N14xWU                      | [4ac0707c49](https://bsd-hardware.info/?probe=4ac0707c49) | Jan 06, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [6c208c85a5](https://bsd-hardware.info/?probe=6c208c85a5) | Jan 06, 2022 |
| Apple         | MacBook5,1                  | [f0aeeb7f3c](https://bsd-hardware.info/?probe=f0aeeb7f3c) | Jan 05, 2022 |
| Dell          | XPS 15 9575                 | [e7925aa387](https://bsd-hardware.info/?probe=e7925aa387) | Jan 05, 2022 |
| Dell          | Latitude E5450              | [a05fbe1c26](https://bsd-hardware.info/?probe=a05fbe1c26) | Jan 05, 2022 |
| HP            | EliteBook 8570p             | [1bbb37d4c6](https://bsd-hardware.info/?probe=1bbb37d4c6) | Jan 03, 2022 |
| Toshiba       | TECRA Z40-B                 | [d498fcd3f8](https://bsd-hardware.info/?probe=d498fcd3f8) | Jan 02, 2022 |
| ASUSTek       | U31SD                       | [a07366611d](https://bsd-hardware.info/?probe=a07366611d) | Jan 02, 2022 |
| Dell          | Inspiron 5558               | [3a239ea97a](https://bsd-hardware.info/?probe=3a239ea97a) | Jan 02, 2022 |
| Framework     | Laptop                      | [9c201bb573](https://bsd-hardware.info/?probe=9c201bb573) | Jan 01, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [87c8ee9b4c](https://bsd-hardware.info/?probe=87c8ee9b4c) | Dec 31, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [42b4bcbcc2](https://bsd-hardware.info/?probe=42b4bcbcc2) | Dec 27, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [695d7201d4](https://bsd-hardware.info/?probe=695d7201d4) | Dec 27, 2021 |
| Lenovo        | ThinkPad X270 20HMCTO1WW    | [efccc9b019](https://bsd-hardware.info/?probe=efccc9b019) | Dec 21, 2021 |
| Lenovo        | ThinkPad X280 20KF001UUS    | [5b9001009e](https://bsd-hardware.info/?probe=5b9001009e) | Dec 20, 2021 |
| TOXIC by B... | 15CL872 1050TI              | [0a1683170a](https://bsd-hardware.info/?probe=0a1683170a) | Dec 20, 2021 |
| Lenovo        | IdeaPad 320S-13IKB 81AK     | [66b8fc8279](https://bsd-hardware.info/?probe=66b8fc8279) | Dec 18, 2021 |
| HP            | EliteBook Folio 9470m       | [b872e9b044](https://bsd-hardware.info/?probe=b872e9b044) | Dec 18, 2021 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | [4147a5824d](https://bsd-hardware.info/?probe=4147a5824d) | Dec 16, 2021 |
| HP            | ProBook 650 G5              | [d4ffc24c6f](https://bsd-hardware.info/?probe=d4ffc24c6f) | Dec 15, 2021 |
| Lenovo        | ThinkPad L470 20J40013US    | [32080a81c5](https://bsd-hardware.info/?probe=32080a81c5) | Dec 15, 2021 |
| Lenovo        | ThinkPad L470 20J40013US    | [e517ae0a82](https://bsd-hardware.info/?probe=e517ae0a82) | Dec 15, 2021 |
| ASUSTek       | 1005P                       | [4c43bd561f](https://bsd-hardware.info/?probe=4c43bd561f) | Dec 14, 2021 |
| HP            | ProBook 440 G6              | [7a8a66430a](https://bsd-hardware.info/?probe=7a8a66430a) | Dec 13, 2021 |
| Lenovo        | ThinkPad A285 20MW000JMH    | [ff53f0763c](https://bsd-hardware.info/?probe=ff53f0763c) | Dec 12, 2021 |
| HP            | ProBook 440 G6              | [f3c014b120](https://bsd-hardware.info/?probe=f3c014b120) | Dec 12, 2021 |
| Lenovo        | ThinkPad Edge E430 3254A... | [990e05c219](https://bsd-hardware.info/?probe=990e05c219) | Dec 11, 2021 |
| HUAWEI        | KLVL-WXX9                   | [b7841e03f5](https://bsd-hardware.info/?probe=b7841e03f5) | Dec 11, 2021 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | [eb69e83fbf](https://bsd-hardware.info/?probe=eb69e83fbf) | Dec 09, 2021 |
| Framework     | Laptop                      | [46dec0c088](https://bsd-hardware.info/?probe=46dec0c088) | Dec 08, 2021 |
| Framework     | Laptop                      | [a8cd4dc680](https://bsd-hardware.info/?probe=a8cd4dc680) | Dec 08, 2021 |
| Lenovo        | ThinkPad X220 42915CG       | [088facef28](https://bsd-hardware.info/?probe=088facef28) | Dec 08, 2021 |
| Toshiba       | Satellite P755              | [44818070a2](https://bsd-hardware.info/?probe=44818070a2) | Dec 08, 2021 |
| Lenovo        | ThinkPad T470s 20HGS18V0... | [a7b9f4a7f8](https://bsd-hardware.info/?probe=a7b9f4a7f8) | Dec 06, 2021 |
| TOXIC by B... | 15CL872 1050TI              | [4fbb430947](https://bsd-hardware.info/?probe=4fbb430947) | Dec 05, 2021 |
| ASUSTek       | 1215B                       | [6dbcac684f](https://bsd-hardware.info/?probe=6dbcac684f) | Dec 04, 2021 |
| Samsung       | 530XBB                      | [8387645312](https://bsd-hardware.info/?probe=8387645312) | Dec 03, 2021 |
| Samsung       | 530XBB                      | [e1983c2353](https://bsd-hardware.info/?probe=e1983c2353) | Dec 03, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [8f9e9ddde5](https://bsd-hardware.info/?probe=8f9e9ddde5) | Dec 02, 2021 |
| Samsung       | 530XBB                      | [b344605891](https://bsd-hardware.info/?probe=b344605891) | Dec 02, 2021 |
| ASUSTek       | 1015BX                      | [9e57263095](https://bsd-hardware.info/?probe=9e57263095) | Nov 29, 2021 |
| Lenovo        | ThinkPad R60e 0658W2M       | [91d67ba784](https://bsd-hardware.info/?probe=91d67ba784) | Nov 27, 2021 |
| Lenovo        | ThinkPad W530 2447AV9       | [4e7fc367bc](https://bsd-hardware.info/?probe=4e7fc367bc) | Nov 27, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [ade9f77281](https://bsd-hardware.info/?probe=ade9f77281) | Nov 25, 2021 |
| Acer          | Aspire E5-521G              | [5306253276](https://bsd-hardware.info/?probe=5306253276) | Nov 23, 2021 |
| Lenovo        | ThinkPad T430 2347G7G       | [66c64c1af9](https://bsd-hardware.info/?probe=66c64c1af9) | Nov 23, 2021 |
| Acer          | Aspire 5560                 | [e117631726](https://bsd-hardware.info/?probe=e117631726) | Nov 22, 2021 |
| Acer          | Aspire A315-21              | [44c1f82bee](https://bsd-hardware.info/?probe=44c1f82bee) | Nov 20, 2021 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [7330a6f958](https://bsd-hardware.info/?probe=7330a6f958) | Nov 20, 2021 |
| Lenovo        | ThinkPad X220 42915CG       | [d8628f80c0](https://bsd-hardware.info/?probe=d8628f80c0) | Nov 19, 2021 |
| HP            | Laptop 15s-du1xxx           | [8ebeac18ca](https://bsd-hardware.info/?probe=8ebeac18ca) | Nov 19, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [ddfd14ef31](https://bsd-hardware.info/?probe=ddfd14ef31) | Nov 17, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [ad4f0d967d](https://bsd-hardware.info/?probe=ad4f0d967d) | Nov 17, 2021 |
| HP            | EliteBook 8570p             | [822a2481bb](https://bsd-hardware.info/?probe=822a2481bb) | Nov 17, 2021 |
| Lenovo        | ThinkPad R60e 0658W2M       | [73774ed18e](https://bsd-hardware.info/?probe=73774ed18e) | Nov 16, 2021 |
| Dell          | Vostro 14-5480              | [0ba4cab539](https://bsd-hardware.info/?probe=0ba4cab539) | Nov 14, 2021 |
| Dell          | G15 5510                    | [e9d432bc06](https://bsd-hardware.info/?probe=e9d432bc06) | Nov 12, 2021 |
| Dell          | G15 5510                    | [91750755e4](https://bsd-hardware.info/?probe=91750755e4) | Nov 12, 2021 |
| Dell          | Vostro 1400                 | [1c594c9ded](https://bsd-hardware.info/?probe=1c594c9ded) | Nov 12, 2021 |
| Apple         | MacBook3,1                  | [61f1f0aef0](https://bsd-hardware.info/?probe=61f1f0aef0) | Nov 10, 2021 |
| HP            | Compaq 6720s                | [6b0d316afc](https://bsd-hardware.info/?probe=6b0d316afc) | Nov 10, 2021 |
| ASUSTek       | 1001P                       | [648081d75b](https://bsd-hardware.info/?probe=648081d75b) | Nov 09, 2021 |
| HP            | Compaq 6720s                | [06e31b2e77](https://bsd-hardware.info/?probe=06e31b2e77) | Nov 09, 2021 |
| HP            | Mini 110-1000               | [ef66d7a110](https://bsd-hardware.info/?probe=ef66d7a110) | Nov 09, 2021 |
| Dell          | Latitude E6430              | [46f2ef2432](https://bsd-hardware.info/?probe=46f2ef2432) | Nov 08, 2021 |
| IBM           | ThinkPad R52 185869G        | [6fd6fd89c5](https://bsd-hardware.info/?probe=6fd6fd89c5) | Nov 08, 2021 |
| Dell          | Inspiron N5050              | [2fbf2a9b2b](https://bsd-hardware.info/?probe=2fbf2a9b2b) | Nov 06, 2021 |
| Dell          | XPS 13 9350                 | [4cc0fd57a5](https://bsd-hardware.info/?probe=4cc0fd57a5) | Nov 04, 2021 |
| Lenovo        | IdeaPad S510p 20298         | [d3cfb73823](https://bsd-hardware.info/?probe=d3cfb73823) | Nov 04, 2021 |
| Lenovo        | ThinkPad X270 20HMCTO1WW    | [c469695daf](https://bsd-hardware.info/?probe=c469695daf) | Nov 04, 2021 |
| Dell          | XPS 13 9343                 | [227c2380d0](https://bsd-hardware.info/?probe=227c2380d0) | Nov 04, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [6f779d5170](https://bsd-hardware.info/?probe=6f779d5170) | Nov 03, 2021 |
| Toshiba       | Satellite Pro L510          | [52ce915b05](https://bsd-hardware.info/?probe=52ce915b05) | Nov 03, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [72f0937505](https://bsd-hardware.info/?probe=72f0937505) | Nov 02, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [e54d79065e](https://bsd-hardware.info/?probe=e54d79065e) | Nov 02, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [a71d3392eb](https://bsd-hardware.info/?probe=a71d3392eb) | Nov 02, 2021 |
| Acer          | Aspire E5-575               | [6ea93bc344](https://bsd-hardware.info/?probe=6ea93bc344) | Oct 31, 2021 |
| MSI           | GS65 Stealth Thin 8RF       | [eb5c495379](https://bsd-hardware.info/?probe=eb5c495379) | Oct 30, 2021 |
| Lenovo        | ThinkPad T430s 23532QG      | [db2a9e5e6f](https://bsd-hardware.info/?probe=db2a9e5e6f) | Oct 29, 2021 |
| Toshiba       | Dakar10FW8                  | [06598a2ed3](https://bsd-hardware.info/?probe=06598a2ed3) | Oct 29, 2021 |
| Acer          | Aspire E5-573G              | [e390271460](https://bsd-hardware.info/?probe=e390271460) | Oct 29, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [0fa0f325e9](https://bsd-hardware.info/?probe=0fa0f325e9) | Oct 28, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0PM0... | [7a61d90a55](https://bsd-hardware.info/?probe=7a61d90a55) | Oct 28, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [8ad7b068f4](https://bsd-hardware.info/?probe=8ad7b068f4) | Oct 26, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [c520513abd](https://bsd-hardware.info/?probe=c520513abd) | Oct 26, 2021 |
| GPD           | MicroPC                     | [8d0ac5e551](https://bsd-hardware.info/?probe=8d0ac5e551) | Oct 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [d910c79d75](https://bsd-hardware.info/?probe=d910c79d75) | Oct 24, 2021 |
| Dell          | XPS 13 9350                 | [a1ab44830c](https://bsd-hardware.info/?probe=a1ab44830c) | Oct 24, 2021 |
| Lenovo        | ThinkPad Mini10 3507A31     | [ced0819a8e](https://bsd-hardware.info/?probe=ced0819a8e) | Oct 24, 2021 |
| Dell          | XPS 13 9343                 | [4b8421b910](https://bsd-hardware.info/?probe=4b8421b910) | Oct 21, 2021 |
| Lenovo        | G580 26897SJ                | [da14095fb7](https://bsd-hardware.info/?probe=da14095fb7) | Oct 20, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [087d40ba7c](https://bsd-hardware.info/?probe=087d40ba7c) | Oct 19, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [d8a6d0daf3](https://bsd-hardware.info/?probe=d8a6d0daf3) | Oct 18, 2021 |
| HP            | EliteBook 8570p             | [86613b04d3](https://bsd-hardware.info/?probe=86613b04d3) | Oct 17, 2021 |
| Dell          | Inspiron 3493               | [ed41c18cfc](https://bsd-hardware.info/?probe=ed41c18cfc) | Oct 16, 2021 |
| Dell          | Latitude E6430              | [d31f35bb29](https://bsd-hardware.info/?probe=d31f35bb29) | Oct 15, 2021 |
| Dell          | XPS 13 9343                 | [7dd8f42ab1](https://bsd-hardware.info/?probe=7dd8f42ab1) | Oct 15, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [d6c59472e5](https://bsd-hardware.info/?probe=d6c59472e5) | Oct 15, 2021 |
| Dell          | Inspiron 7460               | [3dbc09a4df](https://bsd-hardware.info/?probe=3dbc09a4df) | Oct 13, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [be42957ecd](https://bsd-hardware.info/?probe=be42957ecd) | Oct 10, 2021 |
| Acer          | Acadia V1.45                | [29fe65832b](https://bsd-hardware.info/?probe=29fe65832b) | Oct 10, 2021 |
| Google        | Terra                       | [9ba239a4a3](https://bsd-hardware.info/?probe=9ba239a4a3) | Oct 10, 2021 |
| ASUSTek       | K53E                        | [4572d8b5e7](https://bsd-hardware.info/?probe=4572d8b5e7) | Oct 08, 2021 |
| Framework     | Laptop                      | [1e67a5d922](https://bsd-hardware.info/?probe=1e67a5d922) | Oct 08, 2021 |
| ASUSTek       | F83VD                       | [5f2df13f5b](https://bsd-hardware.info/?probe=5f2df13f5b) | Oct 06, 2021 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | [5b08c1de3d](https://bsd-hardware.info/?probe=5b08c1de3d) | Oct 06, 2021 |
| ASUSTek       | A9T                         | [83106a58ef](https://bsd-hardware.info/?probe=83106a58ef) | Oct 03, 2021 |
| Valve         | Jupiter                     | [e5aca4b7d0](https://bsd-hardware.info/?probe=e5aca4b7d0) | Oct 02, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [1c4cf7c21c](https://bsd-hardware.info/?probe=1c4cf7c21c) | Sep 30, 2021 |
| HP            | Stream Notebook PC 11       | [c8ea8a4c4f](https://bsd-hardware.info/?probe=c8ea8a4c4f) | Sep 30, 2021 |
| Apple         | MacBookPro13,2              | [0bf74dea55](https://bsd-hardware.info/?probe=0bf74dea55) | Sep 30, 2021 |
| Dell          | Latitude 5490               | [f0f4370a9c](https://bsd-hardware.info/?probe=f0f4370a9c) | Sep 27, 2021 |
| System76      | Darter Pro                  | [f99c9f56b7](https://bsd-hardware.info/?probe=f99c9f56b7) | Sep 25, 2021 |
| Toshiba       | Dakar10FW8                  | [6a4298baaa](https://bsd-hardware.info/?probe=6a4298baaa) | Sep 24, 2021 |
| Dell          | Precision 7710              | [f0bebc2b21](https://bsd-hardware.info/?probe=f0bebc2b21) | Sep 23, 2021 |
| System76      | Galago Pro                  | [ebe0575f31](https://bsd-hardware.info/?probe=ebe0575f31) | Sep 23, 2021 |
| Dell          | Precision 7710              | [46e9438bf9](https://bsd-hardware.info/?probe=46e9438bf9) | Sep 22, 2021 |
| Dell          | Latitude 5491               | [006dc5a9f4](https://bsd-hardware.info/?probe=006dc5a9f4) | Sep 22, 2021 |
| Dell          | Latitude E7450              | [4f1e40ad63](https://bsd-hardware.info/?probe=4f1e40ad63) | Sep 21, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [22c1aefeab](https://bsd-hardware.info/?probe=22c1aefeab) | Sep 19, 2021 |
| Lenovo        | G40-70 20369                | [ef8eafa662](https://bsd-hardware.info/?probe=ef8eafa662) | Sep 18, 2021 |
| MSI           | P65 Creator 8RE             | [2684b5021c](https://bsd-hardware.info/?probe=2684b5021c) | Sep 18, 2021 |
| ASUSTek       | G551JW                      | [5624c69d4b](https://bsd-hardware.info/?probe=5624c69d4b) | Sep 16, 2021 |
| System76      | Galago Pro                  | [41cd62c0fe](https://bsd-hardware.info/?probe=41cd62c0fe) | Sep 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [0b73df29bf](https://bsd-hardware.info/?probe=0b73df29bf) | Sep 15, 2021 |
| IBM           | ThinkPad X41 2525FAG        | [63a34dc807](https://bsd-hardware.info/?probe=63a34dc807) | Sep 14, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [8611fbfd97](https://bsd-hardware.info/?probe=8611fbfd97) | Sep 14, 2021 |
| Lenovo        | ThinkPad X395 20NL000GPG    | [d7812a2905](https://bsd-hardware.info/?probe=d7812a2905) | Sep 10, 2021 |
| Lenovo        | ThinkPad X395 20NL000GPG    | [cdde22fb04](https://bsd-hardware.info/?probe=cdde22fb04) | Sep 10, 2021 |
| ASUSTek       | TP300LD                     | [e9d8f7de51](https://bsd-hardware.info/?probe=e9d8f7de51) | Sep 09, 2021 |
| ASUSTek       | VX7SX                       | [6ca36a455d](https://bsd-hardware.info/?probe=6ca36a455d) | Sep 09, 2021 |
| Dell          | XPS 13 9343                 | [1f9857aa23](https://bsd-hardware.info/?probe=1f9857aa23) | Sep 08, 2021 |
| Lenovo        | ThinkPad T440s 20AR003SM... | [ff88b24116](https://bsd-hardware.info/?probe=ff88b24116) | Sep 08, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [bf9b083102](https://bsd-hardware.info/?probe=bf9b083102) | Sep 08, 2021 |
| Dell          | XPS 15 9500                 | [30424125f5](https://bsd-hardware.info/?probe=30424125f5) | Sep 08, 2021 |
| Dell          | XPS 15 9500                 | [76da651584](https://bsd-hardware.info/?probe=76da651584) | Sep 08, 2021 |
| Dell          | XPS 15 9570                 | [ee8980fec1](https://bsd-hardware.info/?probe=ee8980fec1) | Sep 07, 2021 |
| ASUSTek       | G551JW                      | [309b5d559f](https://bsd-hardware.info/?probe=309b5d559f) | Sep 07, 2021 |
| System76      | Galago Pro                  | [203560e1f5](https://bsd-hardware.info/?probe=203560e1f5) | Sep 07, 2021 |
| System76      | Galago Pro                  | [d3b33c7681](https://bsd-hardware.info/?probe=d3b33c7681) | Sep 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [b8408cb369](https://bsd-hardware.info/?probe=b8408cb369) | Sep 06, 2021 |
| Panasonic     | CF-F9KWHZZQ2                | [d160186cfb](https://bsd-hardware.info/?probe=d160186cfb) | Sep 05, 2021 |
| Panasonic     | CF-F9KWHZZQ2                | [05e94c09f6](https://bsd-hardware.info/?probe=05e94c09f6) | Sep 05, 2021 |
| Lenovo        | ThinkPad T61 6459CTO        | [713b72cfff](https://bsd-hardware.info/?probe=713b72cfff) | Sep 05, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [5147f5734d](https://bsd-hardware.info/?probe=5147f5734d) | Sep 04, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [2e8b641cc4](https://bsd-hardware.info/?probe=2e8b641cc4) | Sep 04, 2021 |
| Apple         | MacBookPro5,1               | [2cba98f24b](https://bsd-hardware.info/?probe=2cba98f24b) | Sep 04, 2021 |
| Dell          | Latitude E6530              | [8dbff835d2](https://bsd-hardware.info/?probe=8dbff835d2) | Sep 02, 2021 |
| HP            | 2000                        | [4e83c9da3f](https://bsd-hardware.info/?probe=4e83c9da3f) | Sep 02, 2021 |
| HP            | 2000                        | [7a48e639e6](https://bsd-hardware.info/?probe=7a48e639e6) | Sep 02, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [d028fc63d4](https://bsd-hardware.info/?probe=d028fc63d4) | Aug 29, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [67fd361be0](https://bsd-hardware.info/?probe=67fd361be0) | Aug 28, 2021 |
| HP            | EliteBook 8570p             | [fae9e84f60](https://bsd-hardware.info/?probe=fae9e84f60) | Aug 27, 2021 |
| Notebook      | N7x0WU                      | [7681a46a5b](https://bsd-hardware.info/?probe=7681a46a5b) | Aug 27, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [76f004bd26](https://bsd-hardware.info/?probe=76f004bd26) | Aug 26, 2021 |
| Apple         | MacBookPro8,3               | [455af20b0d](https://bsd-hardware.info/?probe=455af20b0d) | Aug 26, 2021 |
| BANGHO        | MAX G5                      | [d2560f69f7](https://bsd-hardware.info/?probe=d2560f69f7) | Aug 24, 2021 |
| Avell High... | A60 MUV                     | [85f5c972a5](https://bsd-hardware.info/?probe=85f5c972a5) | Aug 21, 2021 |
| Lenovo        | ZhaoYang K4e-IML 81VQ       | [cd3ac84240](https://bsd-hardware.info/?probe=cd3ac84240) | Aug 21, 2021 |
| Dell          | Inspiron N7010              | [0db8536c63](https://bsd-hardware.info/?probe=0db8536c63) | Aug 21, 2021 |
| Toshiba       | Satellite L50-C             | [250db17f57](https://bsd-hardware.info/?probe=250db17f57) | Aug 20, 2021 |
| Toshiba       | Satellite L50-C             | [a2e1cbd3d8](https://bsd-hardware.info/?probe=a2e1cbd3d8) | Aug 20, 2021 |
| Dell          | Latitude E6540              | [7d7cc24971](https://bsd-hardware.info/?probe=7d7cc24971) | Aug 19, 2021 |
| HP            | EliteBook 8570p             | [71092e78e2](https://bsd-hardware.info/?probe=71092e78e2) | Aug 17, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [1498417edf](https://bsd-hardware.info/?probe=1498417edf) | Aug 15, 2021 |
| Lenovo        | ThinkPad T61 6459CTO        | [b5018b8651](https://bsd-hardware.info/?probe=b5018b8651) | Aug 14, 2021 |
| HP            | EliteBook 8570p             | [6e97c9a59e](https://bsd-hardware.info/?probe=6e97c9a59e) | Aug 14, 2021 |
| Dell          | Latitude E7240              | [762d8366d0](https://bsd-hardware.info/?probe=762d8366d0) | Aug 12, 2021 |
| Lenovo        | Unknown                     | [e16ce5e864](https://bsd-hardware.info/?probe=e16ce5e864) | Aug 08, 2021 |
| HP            | ZBook 17 G2                 | [f2d911563a](https://bsd-hardware.info/?probe=f2d911563a) | Aug 07, 2021 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [6d5e1a13d0](https://bsd-hardware.info/?probe=6d5e1a13d0) | Aug 07, 2021 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | [bf56b2a81a](https://bsd-hardware.info/?probe=bf56b2a81a) | Aug 05, 2021 |
| Samsung       | 300E5M/300E5L               | [ae874102c3](https://bsd-hardware.info/?probe=ae874102c3) | Aug 04, 2021 |
| Lenovo        | G505 20240                  | [16e6ec4054](https://bsd-hardware.info/?probe=16e6ec4054) | Aug 02, 2021 |
| Dell          | Inspiron 3442               | [6283cb4190](https://bsd-hardware.info/?probe=6283cb4190) | Aug 01, 2021 |
| Apple         | MacBookPro8,1               | [1d941ee61d](https://bsd-hardware.info/?probe=1d941ee61d) | Jul 31, 2021 |
| HP            | ZBook 17 G2                 | [2faf8af7be](https://bsd-hardware.info/?probe=2faf8af7be) | Jul 30, 2021 |
| HP            | ZBook 17 G2                 | [c7fb9e9dee](https://bsd-hardware.info/?probe=c7fb9e9dee) | Jul 27, 2021 |
| HP            | ZBook 17 G2                 | [50c349b7b5](https://bsd-hardware.info/?probe=50c349b7b5) | Jul 27, 2021 |
| Lenovo        | ThinkPad T410 2516DCU       | [c3aa245b5d](https://bsd-hardware.info/?probe=c3aa245b5d) | Jul 27, 2021 |
| Lenovo        | ThinkPad E590 20NB0012RT    | [98072b8db6](https://bsd-hardware.info/?probe=98072b8db6) | Jul 26, 2021 |
| Intel         | Skylake Platform            | [a9144c7e47](https://bsd-hardware.info/?probe=a9144c7e47) | Jul 25, 2021 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [38910aa754](https://bsd-hardware.info/?probe=38910aa754) | Jul 25, 2021 |
| HP            | ZBook 17 G2                 | [6149ab50a8](https://bsd-hardware.info/?probe=6149ab50a8) | Jul 24, 2021 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [3fb09d0402](https://bsd-hardware.info/?probe=3fb09d0402) | Jul 24, 2021 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [bef816fe74](https://bsd-hardware.info/?probe=bef816fe74) | Jul 24, 2021 |
| Dell          | G5 5505                     | [9933a09c4f](https://bsd-hardware.info/?probe=9933a09c4f) | Jul 24, 2021 |
| HP            | ZBook 17 G2                 | [1ef99f31dd](https://bsd-hardware.info/?probe=1ef99f31dd) | Jul 23, 2021 |
| Dell          | Inspiron N4030              | [d6feef8717](https://bsd-hardware.info/?probe=d6feef8717) | Jul 23, 2021 |
| Acer          | Aspire A715-75G             | [f613cb0452](https://bsd-hardware.info/?probe=f613cb0452) | Jul 23, 2021 |
| Dell          | Inspiron N4030              | [9a3c3705d0](https://bsd-hardware.info/?probe=9a3c3705d0) | Jul 23, 2021 |
| Lenovo        | ThinkPad W520 42763KU       | [e16321d2fb](https://bsd-hardware.info/?probe=e16321d2fb) | Jul 21, 2021 |
| IBM           | ThinkPad T43 26686CU        | [122a5774ab](https://bsd-hardware.info/?probe=122a5774ab) | Jul 21, 2021 |
| IBM           | ThinkPad T43 26686CU        | [fdb4ebcf10](https://bsd-hardware.info/?probe=fdb4ebcf10) | Jul 21, 2021 |
| Avell High... | A62 LIV                     | [5983302b1d](https://bsd-hardware.info/?probe=5983302b1d) | Jul 21, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [daa7e68a1f](https://bsd-hardware.info/?probe=daa7e68a1f) | Jul 21, 2021 |
| Apple         | MacBookPro8,1               | [89a9db74f9](https://bsd-hardware.info/?probe=89a9db74f9) | Jul 21, 2021 |
| Lenovo        | ThinkPad T410 2516DCU       | [04b19bd02a](https://bsd-hardware.info/?probe=04b19bd02a) | Jul 21, 2021 |
| Dell          | Inspiron 5758               | [7542ae751d](https://bsd-hardware.info/?probe=7542ae751d) | Jul 20, 2021 |
| Dell          | Inspiron 3521               | [1fed4e841b](https://bsd-hardware.info/?probe=1fed4e841b) | Jul 19, 2021 |
| Dell          | Inspiron 5559               | [e38b3f1f93](https://bsd-hardware.info/?probe=e38b3f1f93) | Jul 19, 2021 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | [b0da42c20d](https://bsd-hardware.info/?probe=b0da42c20d) | Jul 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [9c9d4cc782](https://bsd-hardware.info/?probe=9c9d4cc782) | Jul 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [3d5e512e18](https://bsd-hardware.info/?probe=3d5e512e18) | Jul 18, 2021 |
| HP            | ProBook 440 G7              | [63dc88528c](https://bsd-hardware.info/?probe=63dc88528c) | Jul 17, 2021 |
| HP            | ProBook 440 G7              | [7138e2a9e7](https://bsd-hardware.info/?probe=7138e2a9e7) | Jul 17, 2021 |
| Dell          | Inspiron 3442               | [8f8cc52f23](https://bsd-hardware.info/?probe=8f8cc52f23) | Jul 17, 2021 |
| HP            | ProBook 440 G7              | [b73eb50747](https://bsd-hardware.info/?probe=b73eb50747) | Jul 16, 2021 |
| HP            | EliteBook 8570p             | [462fc329a9](https://bsd-hardware.info/?probe=462fc329a9) | Jul 16, 2021 |
| HP            | ProBook 440 G7              | [d2866f01b5](https://bsd-hardware.info/?probe=d2866f01b5) | Jul 16, 2021 |
| Framework     | Laptop                      | [8a7b477512](https://bsd-hardware.info/?probe=8a7b477512) | Jul 15, 2021 |
| Framework     | Laptop                      | [647138144b](https://bsd-hardware.info/?probe=647138144b) | Jul 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [85e94a1288](https://bsd-hardware.info/?probe=85e94a1288) | Jul 13, 2021 |
| Lenovo        | ThinkPad T420 42368A3       | [0a3b5c9c27](https://bsd-hardware.info/?probe=0a3b5c9c27) | Jul 12, 2021 |
| ASUSTek       | G74Sx                       | [96bee8d702](https://bsd-hardware.info/?probe=96bee8d702) | Jul 12, 2021 |
| Lenovo        | ThinkPad X230 2325A95       | [94d66a0677](https://bsd-hardware.info/?probe=94d66a0677) | Jul 10, 2021 |
| Lenovo        | ThinkPad T470p 20J6A012C... | [ba0270c8f8](https://bsd-hardware.info/?probe=ba0270c8f8) | Jul 09, 2021 |
| Dell          | Inspiron N5110              | [08641f83e8](https://bsd-hardware.info/?probe=08641f83e8) | Jul 07, 2021 |
| Acer          | Aspire A515-54G             | [08cafd05b1](https://bsd-hardware.info/?probe=08cafd05b1) | Jul 06, 2021 |
| HP            | 250 G4 Notebook PC          | [7c3643f8b1](https://bsd-hardware.info/?probe=7c3643f8b1) | Jul 06, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [128c08e60f](https://bsd-hardware.info/?probe=128c08e60f) | Jul 04, 2021 |
| Lenovo        | Rescuer-15ISK 80RQ          | [46d0d10dd8](https://bsd-hardware.info/?probe=46d0d10dd8) | Jul 03, 2021 |
| Gigabyte      | MMLP3AP-00                  | [168e674b55](https://bsd-hardware.info/?probe=168e674b55) | Jul 03, 2021 |
| Dell          | XPS 13 9343                 | [323044ccaf](https://bsd-hardware.info/?probe=323044ccaf) | Jul 03, 2021 |
| Notebook      | W510LU                      | [3d6de69bda](https://bsd-hardware.info/?probe=3d6de69bda) | Jul 02, 2021 |
| Acer          | Aspire E5-521               | [f8300de583](https://bsd-hardware.info/?probe=f8300de583) | Jul 01, 2021 |
| Samsung       | NC10                        | [d33644912a](https://bsd-hardware.info/?probe=d33644912a) | Jun 28, 2021 |
| Toshiba       | Satellite C655D             | [10bdf263b3](https://bsd-hardware.info/?probe=10bdf263b3) | Jun 27, 2021 |
| Dell          | Vostro 5481                 | [bb318fbc50](https://bsd-hardware.info/?probe=bb318fbc50) | Jun 26, 2021 |
| ASUSTek       | X556UAK                     | [795f6e5a42](https://bsd-hardware.info/?probe=795f6e5a42) | Jun 26, 2021 |
| Lenovo        | ThinkPad W520 42763KU       | [591cbc0879](https://bsd-hardware.info/?probe=591cbc0879) | Jun 24, 2021 |
| Dell          | Inspiron 5567               | [0b90603ace](https://bsd-hardware.info/?probe=0b90603ace) | Jun 23, 2021 |
| Lenovo        | Yoga 500-14IBD 80N4         | [9fda78d739](https://bsd-hardware.info/?probe=9fda78d739) | Jun 23, 2021 |
| ASUSTek       | G74Sx                       | [8b444409f4](https://bsd-hardware.info/?probe=8b444409f4) | Jun 22, 2021 |
| Lenovo        | ThinkPad X270 20HMS0MA18    | [117b790a84](https://bsd-hardware.info/?probe=117b790a84) | Jun 22, 2021 |
| Lenovo        | ThinkPad T450s 20BWS0L60... | [6ea6f6ffe7](https://bsd-hardware.info/?probe=6ea6f6ffe7) | Jun 20, 2021 |
| Dell          | Studio 1558                 | [c2ba752ab5](https://bsd-hardware.info/?probe=c2ba752ab5) | Jun 20, 2021 |
| Lenovo        | ThinkPad T420 4236NHG       | [ea00bc1f1f](https://bsd-hardware.info/?probe=ea00bc1f1f) | Jun 20, 2021 |
| HP            | ENVY x2 Detachable PC 13    | [8c78180ff9](https://bsd-hardware.info/?probe=8c78180ff9) | Jun 20, 2021 |
| HP            | ENVY x2 Detachable PC 13    | [2e7a8b5be3](https://bsd-hardware.info/?probe=2e7a8b5be3) | Jun 20, 2021 |
| HP            | EliteBook 8570p             | [cc24e867fc](https://bsd-hardware.info/?probe=cc24e867fc) | Jun 19, 2021 |
| IBM           | ThinkPad T42 2374K46        | [acf931a3e0](https://bsd-hardware.info/?probe=acf931a3e0) | Jun 19, 2021 |
| Lenovo        | ThinkPad T60 20076PU        | [7138c789e3](https://bsd-hardware.info/?probe=7138c789e3) | Jun 19, 2021 |
| Dell          | Inspiron 15-7579            | [4b8b5f7918](https://bsd-hardware.info/?probe=4b8b5f7918) | Jun 19, 2021 |
| Lenovo        | ThinkPad T60 20076PU        | [7d36d27958](https://bsd-hardware.info/?probe=7d36d27958) | Jun 19, 2021 |
| Lenovo        | ThinkPad T430 2349GCU       | [2b05811c5f](https://bsd-hardware.info/?probe=2b05811c5f) | Jun 18, 2021 |
| LG Electro... | E500-GP01A9                 | [7db1345e97](https://bsd-hardware.info/?probe=7db1345e97) | Jun 17, 2021 |
| LG Electro... | E500-GP01A9                 | [cbade775b6](https://bsd-hardware.info/?probe=cbade775b6) | Jun 17, 2021 |
| Acer          | Aspire V3-571G              | [a9fe2f5aad](https://bsd-hardware.info/?probe=a9fe2f5aad) | Jun 16, 2021 |
| LG Electro... | E500-GP01A9                 | [80052d6cdc](https://bsd-hardware.info/?probe=80052d6cdc) | Jun 15, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [901005edd3](https://bsd-hardware.info/?probe=901005edd3) | Jun 15, 2021 |
| Dell          | Latitude E6440              | [8fa2c1f5c4](https://bsd-hardware.info/?probe=8fa2c1f5c4) | Jun 13, 2021 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | [3d50ba4d85](https://bsd-hardware.info/?probe=3d50ba4d85) | Jun 13, 2021 |
| Dell          | G5 5505                     | [97319295ee](https://bsd-hardware.info/?probe=97319295ee) | Jun 13, 2021 |
| Dell          | Latitude E6440              | [77f259babe](https://bsd-hardware.info/?probe=77f259babe) | Jun 12, 2021 |
| Dell          | Vostro 5490                 | [cf3508718c](https://bsd-hardware.info/?probe=cf3508718c) | Jun 11, 2021 |
| SLIMBOOK      | Unknown                     | [80a9ba918e](https://bsd-hardware.info/?probe=80a9ba918e) | Jun 11, 2021 |
| Dell          | Latitude E4300              | [1150e00893](https://bsd-hardware.info/?probe=1150e00893) | Jun 10, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [1138d47591](https://bsd-hardware.info/?probe=1138d47591) | Jun 10, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [4ac6c9b3eb](https://bsd-hardware.info/?probe=4ac6c9b3eb) | Jun 08, 2021 |
| Acer          | Aspire ES1-132              | [62c87cf194](https://bsd-hardware.info/?probe=62c87cf194) | Jun 07, 2021 |
| Lenovo        | ThinkPad T410 2518A37       | [c887ff2917](https://bsd-hardware.info/?probe=c887ff2917) | Jun 07, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [8fc867cfae](https://bsd-hardware.info/?probe=8fc867cfae) | Jun 06, 2021 |
| Acer          | Aspire ES1-132              | [bf605b741b](https://bsd-hardware.info/?probe=bf605b741b) | Jun 04, 2021 |
| Lenovo        | ThinkPad X220 4291ON5       | [66743a51cc](https://bsd-hardware.info/?probe=66743a51cc) | Jun 04, 2021 |
| Acer          | Aspire A515-51G             | [53a69aa8c1](https://bsd-hardware.info/?probe=53a69aa8c1) | Jun 04, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [84e93d02e1](https://bsd-hardware.info/?probe=84e93d02e1) | Jun 03, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [1bb850edca](https://bsd-hardware.info/?probe=1bb850edca) | Jun 03, 2021 |
| HP            | EliteBook 8570p             | [52ba4e835f](https://bsd-hardware.info/?probe=52ba4e835f) | Jun 03, 2021 |
| Lenovo        | ThinkPad T420 4237A12       | [dc29d714d9](https://bsd-hardware.info/?probe=dc29d714d9) | Jun 02, 2021 |
| Acer          | Aspire E5-573G              | [52de90ff3d](https://bsd-hardware.info/?probe=52de90ff3d) | Jun 02, 2021 |
| Apple         | MacBookPro9,1               | [afc70d9c77](https://bsd-hardware.info/?probe=afc70d9c77) | Jun 01, 2021 |
| Notebook      | N7x0WU                      | [ba4260c181](https://bsd-hardware.info/?probe=ba4260c181) | Jun 01, 2021 |
| Sony          | SVF1421DSGW                 | [64f3f02018](https://bsd-hardware.info/?probe=64f3f02018) | Jun 01, 2021 |
| Lenovo        | ThinkPad T490 20N3X50500    | [6311d603ff](https://bsd-hardware.info/?probe=6311d603ff) | May 31, 2021 |
| ASUSTek       | UX31A                       | [67a6df2b68](https://bsd-hardware.info/?probe=67a6df2b68) | May 30, 2021 |
| System76      | Gazelle                     | [f9c37f2c8d](https://bsd-hardware.info/?probe=f9c37f2c8d) | May 30, 2021 |
| HP            | Pavilion Laptop 15-cc0xx    | [9dd5a9eeef](https://bsd-hardware.info/?probe=9dd5a9eeef) | May 30, 2021 |
| Dell          | Vostro 5568                 | [84a1925fc9](https://bsd-hardware.info/?probe=84a1925fc9) | May 29, 2021 |
| Dell          | Inspiron N5050              | [9b06ff01bb](https://bsd-hardware.info/?probe=9b06ff01bb) | May 29, 2021 |
| Lenovo        | ThinkPad T450s 20BWS0L60... | [ac567bd12d](https://bsd-hardware.info/?probe=ac567bd12d) | May 28, 2021 |
| Lenovo        | ThinkPad A485 20MVS0FD00    | [2f1ba02130](https://bsd-hardware.info/?probe=2f1ba02130) | May 28, 2021 |
| Acer          | Nitro AN515-54              | [337a8b5a3d](https://bsd-hardware.info/?probe=337a8b5a3d) | May 28, 2021 |
| Lenovo        | ThinkPad X220 4291PU5       | [c6d626c350](https://bsd-hardware.info/?probe=c6d626c350) | May 24, 2021 |
| Acer          | Aspire E5-571P              | [7c8c842fa7](https://bsd-hardware.info/?probe=7c8c842fa7) | May 24, 2021 |
| ASUSTek       | 1015PX                      | [c6e717c1e9](https://bsd-hardware.info/?probe=c6e717c1e9) | May 24, 2021 |
| Lenovo        | ThinkPad X270 20HM004JBR    | [88c27e65d7](https://bsd-hardware.info/?probe=88c27e65d7) | May 23, 2021 |
| Dell          | Latitude D620               | [1bd280a155](https://bsd-hardware.info/?probe=1bd280a155) | May 23, 2021 |
| Notebook      | N7x0WU                      | [70760365d0](https://bsd-hardware.info/?probe=70760365d0) | May 20, 2021 |
| Dell          | Latitude E6410              | [c0115917d2](https://bsd-hardware.info/?probe=c0115917d2) | May 19, 2021 |
| Lenovo        | Z51-70 80K6                 | [89ca4554ca](https://bsd-hardware.info/?probe=89ca4554ca) | May 18, 2021 |
| Packard Be... | AOA110                      | [4d9eb84daa](https://bsd-hardware.info/?probe=4d9eb84daa) | May 16, 2021 |
| MSI           | GL65 Leopard 10SFSK         | [a40e426983](https://bsd-hardware.info/?probe=a40e426983) | May 15, 2021 |
| Dell          | Latitude E5550              | [dca8ba9d37](https://bsd-hardware.info/?probe=dca8ba9d37) | May 13, 2021 |
| ASUSTek       | G750JM                      | [37be4ea27a](https://bsd-hardware.info/?probe=37be4ea27a) | May 13, 2021 |
| Apple         | MacBookPro6,2               | [0ab44e95df](https://bsd-hardware.info/?probe=0ab44e95df) | May 12, 2021 |
| Notebook      | NL5xRU                      | [792fb07dd9](https://bsd-hardware.info/?probe=792fb07dd9) | May 10, 2021 |
| Dell          | G5 5505                     | [ba74d8eee0](https://bsd-hardware.info/?probe=ba74d8eee0) | May 08, 2021 |
| Acer          | Predator PH517-61           | [9e03a76684](https://bsd-hardware.info/?probe=9e03a76684) | May 08, 2021 |
| Dell          | Latitude 5500               | [2538b038ed](https://bsd-hardware.info/?probe=2538b038ed) | May 08, 2021 |
| Toshiba       | TECRA M11                   | [6357d0d51f](https://bsd-hardware.info/?probe=6357d0d51f) | May 08, 2021 |
| Dell          | G5 5505                     | [23ae99e489](https://bsd-hardware.info/?probe=23ae99e489) | May 08, 2021 |
| HP            | Laptop 17-by0xxx            | [10af242f8b](https://bsd-hardware.info/?probe=10af242f8b) | May 07, 2021 |
| Lenovo        | ThinkPad X220 4290NE3       | [9d15dab449](https://bsd-hardware.info/?probe=9d15dab449) | May 07, 2021 |
| HP            | Laptop 17-by0xxx            | [b0b4ca9f27](https://bsd-hardware.info/?probe=b0b4ca9f27) | May 07, 2021 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | [d5adf152a7](https://bsd-hardware.info/?probe=d5adf152a7) | May 05, 2021 |
| Pegatron      | T12Ah                       | [ce8d45af17](https://bsd-hardware.info/?probe=ce8d45af17) | May 03, 2021 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | [2be8cf963c](https://bsd-hardware.info/?probe=2be8cf963c) | May 02, 2021 |
| Lenovo        | ThinkPad T440p 20AW0049L... | [7660f9b6db](https://bsd-hardware.info/?probe=7660f9b6db) | May 02, 2021 |
| Acer          | Aspire V5-531               | [edbf1ff1c6](https://bsd-hardware.info/?probe=edbf1ff1c6) | May 01, 2021 |
| Acer          | Aspire V5-531               | [8282b3e5fb](https://bsd-hardware.info/?probe=8282b3e5fb) | May 01, 2021 |
| HP            | Laptop 17-by0xxx            | [47221a4d1d](https://bsd-hardware.info/?probe=47221a4d1d) | Apr 30, 2021 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | [7c642e5e7d](https://bsd-hardware.info/?probe=7c642e5e7d) | Apr 30, 2021 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | [2e2e69cb9e](https://bsd-hardware.info/?probe=2e2e69cb9e) | Apr 29, 2021 |
| Toshiba       | Satellite C655D             | [6398601e16](https://bsd-hardware.info/?probe=6398601e16) | Apr 29, 2021 |
| Dell          | Inspiron 3793               | [c2d56fc369](https://bsd-hardware.info/?probe=c2d56fc369) | Apr 29, 2021 |
| Dell          | Latitude E5420              | [32f03aa888](https://bsd-hardware.info/?probe=32f03aa888) | Apr 27, 2021 |
| Dell          | Latitude E5420              | [4b4cd45ac7](https://bsd-hardware.info/?probe=4b4cd45ac7) | Apr 26, 2021 |
| Dell          | Latitude E5420              | [6457b99e73](https://bsd-hardware.info/?probe=6457b99e73) | Apr 26, 2021 |
| Dell          | Precision 5510              | [063d746a48](https://bsd-hardware.info/?probe=063d746a48) | Apr 25, 2021 |
| Dell          | Precision 5510              | [6bb3b7aa11](https://bsd-hardware.info/?probe=6bb3b7aa11) | Apr 25, 2021 |
| HP            | Compaq Presario CQ71        | [258ef16ace](https://bsd-hardware.info/?probe=258ef16ace) | Apr 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [4993ad0feb](https://bsd-hardware.info/?probe=4993ad0feb) | Apr 25, 2021 |
| Dell          | Inspiron 3793               | [c784e7b290](https://bsd-hardware.info/?probe=c784e7b290) | Apr 25, 2021 |
| Dell          | Inspiron N5050              | [2939c4cb17](https://bsd-hardware.info/?probe=2939c4cb17) | Apr 24, 2021 |
| HP            | ProBook 4530s               | [4fb8582dc1](https://bsd-hardware.info/?probe=4fb8582dc1) | Apr 24, 2021 |
| Lenovo        | ThinkPad E14 20RAS0F600     | [94d082c57c](https://bsd-hardware.info/?probe=94d082c57c) | Apr 24, 2021 |
| HP            | Laptop 17-by0xxx            | [4f4a6b1ab0](https://bsd-hardware.info/?probe=4f4a6b1ab0) | Apr 24, 2021 |
| Toshiba       | Satellite L50-C             | [9cf9861053](https://bsd-hardware.info/?probe=9cf9861053) | Apr 23, 2021 |
| Pegatron      | T12Ah                       | [5de4060089](https://bsd-hardware.info/?probe=5de4060089) | Apr 23, 2021 |
| Dell          | Precision 5520              | [7d5f7b5033](https://bsd-hardware.info/?probe=7d5f7b5033) | Apr 23, 2021 |
| Toshiba       | Satellite L50-C             | [94b2e5d5ff](https://bsd-hardware.info/?probe=94b2e5d5ff) | Apr 23, 2021 |
| Alienware     | M15x                        | [0b60c1cb25](https://bsd-hardware.info/?probe=0b60c1cb25) | Apr 22, 2021 |
| Lenovo        | ThinkPad E490 20N9001SBR    | [852a900303](https://bsd-hardware.info/?probe=852a900303) | Apr 22, 2021 |
| Lenovo        | ThinkPad Edge E320 1298R... | [6a96e2c5b1](https://bsd-hardware.info/?probe=6a96e2c5b1) | Apr 22, 2021 |
| Lenovo        | ThinkPad X270 20HMCTO1WW    | [7c7573eb45](https://bsd-hardware.info/?probe=7c7573eb45) | Apr 22, 2021 |
| Lenovo        | ThinkPad X270 20HMS0NS00    | [72fb01f474](https://bsd-hardware.info/?probe=72fb01f474) | Apr 22, 2021 |
| HP            | EliteBook 840 G3            | [2b97986de1](https://bsd-hardware.info/?probe=2b97986de1) | Apr 21, 2021 |
| Dell          | Latitude 5580               | [f967516613](https://bsd-hardware.info/?probe=f967516613) | Apr 20, 2021 |
| Dell          | Latitude E6440              | [3a656ded12](https://bsd-hardware.info/?probe=3a656ded12) | Apr 19, 2021 |
| Dell          | Latitude E6440              | [68f57531cb](https://bsd-hardware.info/?probe=68f57531cb) | Apr 19, 2021 |
| System76      | Lemur Pro                   | [0bd96ef663](https://bsd-hardware.info/?probe=0bd96ef663) | Apr 19, 2021 |
| ASUSTek       | Q500A                       | [c52b593262](https://bsd-hardware.info/?probe=c52b593262) | Apr 17, 2021 |
| Samsung       | NC10                        | [3307e80418](https://bsd-hardware.info/?probe=3307e80418) | Apr 17, 2021 |
| Clevo         | W55xEU                      | [229587fbd5](https://bsd-hardware.info/?probe=229587fbd5) | Apr 16, 2021 |
| HP            | EliteBook Folio 9470m       | [e1837571df](https://bsd-hardware.info/?probe=e1837571df) | Apr 15, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [270bd22b8d](https://bsd-hardware.info/?probe=270bd22b8d) | Apr 14, 2021 |
| Dell          | XPS 13 9360                 | [f8bfc70f13](https://bsd-hardware.info/?probe=f8bfc70f13) | Apr 13, 2021 |
| Samsung       | NC10                        | [dd4310d56f](https://bsd-hardware.info/?probe=dd4310d56f) | Apr 13, 2021 |
| Dell          | Latitude E5470              | [af72876fd2](https://bsd-hardware.info/?probe=af72876fd2) | Apr 12, 2021 |
| Dell          | Latitude D610               | [d2cbb1f229](https://bsd-hardware.info/?probe=d2cbb1f229) | Apr 12, 2021 |
| Dell          | Inspiron 3521               | [9050866fb2](https://bsd-hardware.info/?probe=9050866fb2) | Apr 12, 2021 |
| Dell          | Latitude E5570              | [da926f1065](https://bsd-hardware.info/?probe=da926f1065) | Apr 11, 2021 |
| Acer          | Extensa 2540                | [e7d6ece4ba](https://bsd-hardware.info/?probe=e7d6ece4ba) | Apr 11, 2021 |
| HUAWEI        | HN-WX9X                     | [d776625073](https://bsd-hardware.info/?probe=d776625073) | Apr 11, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [bd88655975](https://bsd-hardware.info/?probe=bd88655975) | Apr 10, 2021 |
| Lenovo        | ThinkPad T430 23495P8       | [2c985c22ef](https://bsd-hardware.info/?probe=2c985c22ef) | Apr 10, 2021 |
| Lenovo        | ThinkPad T420 4236NUG       | [4ff3fa22ff](https://bsd-hardware.info/?probe=4ff3fa22ff) | Apr 07, 2021 |
| Lenovo        | ThinkPad A485 20MUS07E00    | [812939c17f](https://bsd-hardware.info/?probe=812939c17f) | Apr 05, 2021 |
| Lenovo        | ThinkPad A485 20MUS07E00    | [22b35a127a](https://bsd-hardware.info/?probe=22b35a127a) | Apr 05, 2021 |
| Dell          | G5 5590                     | [18863bc535](https://bsd-hardware.info/?probe=18863bc535) | Apr 05, 2021 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | [676f16ac86](https://bsd-hardware.info/?probe=676f16ac86) | Apr 05, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U3C... | [2de4bc8337](https://bsd-hardware.info/?probe=2de4bc8337) | Apr 04, 2021 |
| Dell          | Latitude E7440              | [6ec8fd788a](https://bsd-hardware.info/?probe=6ec8fd788a) | Apr 04, 2021 |
| Dell          | Latitude E5420              | [be14a1d28e](https://bsd-hardware.info/?probe=be14a1d28e) | Apr 04, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [2376cf30b2](https://bsd-hardware.info/?probe=2376cf30b2) | Apr 03, 2021 |
| Toshiba       | Satellite L50-C             | [ff59142f85](https://bsd-hardware.info/?probe=ff59142f85) | Apr 03, 2021 |
| Lenovo        | ThinkPad X220 4290NE3       | [f466982179](https://bsd-hardware.info/?probe=f466982179) | Apr 01, 2021 |
| Sony          | VGN-FW290J                  | [4a6ca78bc0](https://bsd-hardware.info/?probe=4a6ca78bc0) | Apr 01, 2021 |
| ASUSTek       | 1225B                       | [3eff93bfb5](https://bsd-hardware.info/?probe=3eff93bfb5) | Mar 31, 2021 |
| Toshiba       | Satellite L50-C             | [32f33a7a8b](https://bsd-hardware.info/?probe=32f33a7a8b) | Mar 31, 2021 |
| Samsung       | N145P/N250P/N260P           | [a38a620353](https://bsd-hardware.info/?probe=a38a620353) | Mar 29, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [4376accb5e](https://bsd-hardware.info/?probe=4376accb5e) | Mar 29, 2021 |
| Lenovo        | ThinkPad X220 4290EE8       | [f46976d85d](https://bsd-hardware.info/?probe=f46976d85d) | Mar 29, 2021 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [342e914968](https://bsd-hardware.info/?probe=342e914968) | Mar 29, 2021 |
| Lenovo        | ThinkPad T490 20N20009FR    | [e1f691ac78](https://bsd-hardware.info/?probe=e1f691ac78) | Mar 29, 2021 |
| HP            | EliteBook Folio 9470m       | [57de8a523c](https://bsd-hardware.info/?probe=57de8a523c) | Mar 29, 2021 |
| Packard Be... | AOA110                      | [fbdf068328](https://bsd-hardware.info/?probe=fbdf068328) | Mar 28, 2021 |
| Packard Be... | AOA110                      | [8da75861b4](https://bsd-hardware.info/?probe=8da75861b4) | Mar 28, 2021 |
| HP            | EliteBook 8570p             | [ed80dc9019](https://bsd-hardware.info/?probe=ed80dc9019) | Mar 27, 2021 |
| HP            | ProBook 455 G7              | [dd877e6c6c](https://bsd-hardware.info/?probe=dd877e6c6c) | Mar 27, 2021 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | [dec8aa97f5](https://bsd-hardware.info/?probe=dec8aa97f5) | Mar 26, 2021 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | [83ed58b4d0](https://bsd-hardware.info/?probe=83ed58b4d0) | Mar 26, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [3cb0e979f8](https://bsd-hardware.info/?probe=3cb0e979f8) | Mar 26, 2021 |
| Dell          | Precision M4600             | [04fb75b4ea](https://bsd-hardware.info/?probe=04fb75b4ea) | Mar 26, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [beacf76b6a](https://bsd-hardware.info/?probe=beacf76b6a) | Mar 26, 2021 |
| HUAWEI        | MACH-WX9                    | [f7e09652d9](https://bsd-hardware.info/?probe=f7e09652d9) | Mar 25, 2021 |
| HUAWEI        | MACH-WX9                    | [f9fdc75b45](https://bsd-hardware.info/?probe=f9fdc75b45) | Mar 25, 2021 |
| Lenovo        | ThinkPad L530 24812TG       | [520982317e](https://bsd-hardware.info/?probe=520982317e) | Mar 25, 2021 |
| Dell          | Latitude 7390               | [2ad87768af](https://bsd-hardware.info/?probe=2ad87768af) | Mar 25, 2021 |
| Lenovo        | ThinkPad X220 4291IR6       | [3e9aab9818](https://bsd-hardware.info/?probe=3e9aab9818) | Mar 25, 2021 |
| Lenovo        | ThinkPad L590 20Q7000YSP    | [038fbabfe8](https://bsd-hardware.info/?probe=038fbabfe8) | Mar 24, 2021 |
| MSI           | GE75 Raider 10SGS           | [fea3cdb5d1](https://bsd-hardware.info/?probe=fea3cdb5d1) | Mar 24, 2021 |
| Lenovo        | ThinkPad R61 77331CU        | [d223a9b1fb](https://bsd-hardware.info/?probe=d223a9b1fb) | Mar 23, 2021 |
| ASUSTek       | 900A                        | [e920222f0e](https://bsd-hardware.info/?probe=e920222f0e) | Mar 23, 2021 |
| Toshiba       | Satellite L50-C             | [70cf274538](https://bsd-hardware.info/?probe=70cf274538) | Mar 23, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [dc40b42864](https://bsd-hardware.info/?probe=dc40b42864) | Mar 22, 2021 |
| Avell High... | A62                         | [df77dd6562](https://bsd-hardware.info/?probe=df77dd6562) | Mar 22, 2021 |
| Notebook      | N85_N87HCHNHZ               | [e84b5b6e5f](https://bsd-hardware.info/?probe=e84b5b6e5f) | Mar 22, 2021 |
| ASUSTek       | 900A                        | [a76303a060](https://bsd-hardware.info/?probe=a76303a060) | Mar 21, 2021 |
| Apple         | MacBookPro6,2               | [d0b3b5da10](https://bsd-hardware.info/?probe=d0b3b5da10) | Mar 21, 2021 |
| Dell          | Latitude 5580               | [175191ccff](https://bsd-hardware.info/?probe=175191ccff) | Mar 18, 2021 |
| Dell          | Latitude 5580               | [f6225cf8d8](https://bsd-hardware.info/?probe=f6225cf8d8) | Mar 18, 2021 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [bec05a34de](https://bsd-hardware.info/?probe=bec05a34de) | Mar 18, 2021 |
| Dell          | Inspiron 7566               | [183ac9b791](https://bsd-hardware.info/?probe=183ac9b791) | Mar 17, 2021 |
| Dell          | Inspiron 7566               | [b4a35aa7b0](https://bsd-hardware.info/?probe=b4a35aa7b0) | Mar 17, 2021 |
| Lenovo        | ThinkPad X395 20NL001SMX    | [cd016e96ee](https://bsd-hardware.info/?probe=cd016e96ee) | Mar 17, 2021 |
| Lenovo        | ThinkPad T470 20HES5PK00    | [6b2abd4df5](https://bsd-hardware.info/?probe=6b2abd4df5) | Mar 17, 2021 |
| Lenovo        | ThinkPad T480s 20L7001HR... | [ebd44c21d9](https://bsd-hardware.info/?probe=ebd44c21d9) | Mar 17, 2021 |
| Gateway       | Solo 450                    | [41e40c653e](https://bsd-hardware.info/?probe=41e40c653e) | Mar 16, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [b9eeb28ada](https://bsd-hardware.info/?probe=b9eeb28ada) | Mar 16, 2021 |
| Dell          | Latitude E6440              | [a332efd9d9](https://bsd-hardware.info/?probe=a332efd9d9) | Mar 15, 2021 |
| Apple         | MacBook3,1                  | [ed3684513f](https://bsd-hardware.info/?probe=ed3684513f) | Mar 15, 2021 |
| Samsung       | N150P                       | [68483fab9d](https://bsd-hardware.info/?probe=68483fab9d) | Mar 14, 2021 |
| HP            | EliteBook 820 G1            | [565343b334](https://bsd-hardware.info/?probe=565343b334) | Mar 13, 2021 |
| Lenovo        | ThinkPad E460 20ETA00DCD    | [0a6985f078](https://bsd-hardware.info/?probe=0a6985f078) | Mar 13, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [acbc65fd42](https://bsd-hardware.info/?probe=acbc65fd42) | Mar 10, 2021 |
| Dell          | Latitude 3410               | [80d7bf959a](https://bsd-hardware.info/?probe=80d7bf959a) | Mar 10, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [9fed35d792](https://bsd-hardware.info/?probe=9fed35d792) | Mar 10, 2021 |
| Lenovo        | ThinkPad X200s 7470W1V      | [926fe13d8f](https://bsd-hardware.info/?probe=926fe13d8f) | Mar 09, 2021 |
| HP            | 255 G3                      | [861bdc647d](https://bsd-hardware.info/?probe=861bdc647d) | Mar 09, 2021 |
| HP            | ProBook 455 G7              | [1fcde7c0e1](https://bsd-hardware.info/?probe=1fcde7c0e1) | Mar 09, 2021 |
| Gateway       | Solo 450                    | [5dcb6e0ef6](https://bsd-hardware.info/?probe=5dcb6e0ef6) | Mar 09, 2021 |
| Clevo         | W55xEU                      | [e51ee3b14c](https://bsd-hardware.info/?probe=e51ee3b14c) | Mar 08, 2021 |
| HP            | 255 G3                      | [bd82ed65e9](https://bsd-hardware.info/?probe=bd82ed65e9) | Mar 07, 2021 |
| Clevo         | W55xEU                      | [d874753fe2](https://bsd-hardware.info/?probe=d874753fe2) | Mar 07, 2021 |
| ASUSTek       | 1015BX                      | [5834a52924](https://bsd-hardware.info/?probe=5834a52924) | Mar 06, 2021 |
| Alienware     | 14                          | [0e0cdf952a](https://bsd-hardware.info/?probe=0e0cdf952a) | Mar 06, 2021 |
| Lenovo        | ThinkPad T60 20076PU        | [5375f351a5](https://bsd-hardware.info/?probe=5375f351a5) | Mar 05, 2021 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | [17ed006376](https://bsd-hardware.info/?probe=17ed006376) | Mar 05, 2021 |
| Dell          | Precision 3541              | [d07a4dc2c7](https://bsd-hardware.info/?probe=d07a4dc2c7) | Mar 04, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [b60382da32](https://bsd-hardware.info/?probe=b60382da32) | Mar 03, 2021 |
| Acer          | Extensa 5630                | [6a1b523efb](https://bsd-hardware.info/?probe=6a1b523efb) | Mar 03, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [6a4b5b90b7](https://bsd-hardware.info/?probe=6a4b5b90b7) | Mar 02, 2021 |
| Lenovo        | ThinkPad T490 20N3X50500    | [5f4ec887b6](https://bsd-hardware.info/?probe=5f4ec887b6) | Mar 02, 2021 |
| Lenovo        | ThinkPad T530 2429J74       | [8573903191](https://bsd-hardware.info/?probe=8573903191) | Feb 28, 2021 |
| Dell          | Latitude 5580               | [ab4ea78367](https://bsd-hardware.info/?probe=ab4ea78367) | Feb 28, 2021 |
| HP            | Compaq 6820s                | [f63d65b78c](https://bsd-hardware.info/?probe=f63d65b78c) | Feb 26, 2021 |
| Toshiba       | Satellite L50-C             | [3af26c7a29](https://bsd-hardware.info/?probe=3af26c7a29) | Feb 25, 2021 |
| Lenovo        | ThinkPad X280 20KFCTO1WW    | [9bdf9ecec8](https://bsd-hardware.info/?probe=9bdf9ecec8) | Feb 25, 2021 |
| Acer          | Aspire V5-531               | [fc868b6179](https://bsd-hardware.info/?probe=fc868b6179) | Feb 25, 2021 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | [aacafb6ace](https://bsd-hardware.info/?probe=aacafb6ace) | Feb 24, 2021 |
| Unknown       | Unknown                     | [d11ec93413](https://bsd-hardware.info/?probe=d11ec93413) | Feb 23, 2021 |
| Dell          | Studio 1537                 | [a4c1d361eb](https://bsd-hardware.info/?probe=a4c1d361eb) | Feb 23, 2021 |
| Lenovo        | ThinkPad T450 20BUS08800    | [d783b3b4dd](https://bsd-hardware.info/?probe=d783b3b4dd) | Feb 22, 2021 |
| Lenovo        | ThinkPad X61s 766734A       | [3eb96dce87](https://bsd-hardware.info/?probe=3eb96dce87) | Feb 22, 2021 |
| Dell          | Inspiron 910                | [047950e61b](https://bsd-hardware.info/?probe=047950e61b) | Feb 22, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [7f8c483af1](https://bsd-hardware.info/?probe=7f8c483af1) | Feb 21, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 4... | [f8f9140d92](https://bsd-hardware.info/?probe=f8f9140d92) | Feb 21, 2021 |
| Gigabyte      | P15FR7                      | [c65b4d297a](https://bsd-hardware.info/?probe=c65b4d297a) | Feb 21, 2021 |
| Dell          | Latitude E6430              | [a7fd669be4](https://bsd-hardware.info/?probe=a7fd669be4) | Feb 20, 2021 |
| Fujitsu       | FMVNF70YJ                   | [ac880c0076](https://bsd-hardware.info/?probe=ac880c0076) | Feb 20, 2021 |
| Dell          | Latitude E7450              | [0a8e2a2e29](https://bsd-hardware.info/?probe=0a8e2a2e29) | Feb 19, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [a9604cfdb8](https://bsd-hardware.info/?probe=a9604cfdb8) | Feb 19, 2021 |
| Lenovo        | V130-15IKB 81HN             | [893c17f73a](https://bsd-hardware.info/?probe=893c17f73a) | Feb 19, 2021 |
| Lenovo        | V130-15IKB 81HN             | [d0f504fad2](https://bsd-hardware.info/?probe=d0f504fad2) | Feb 19, 2021 |
| ASUSTek       | G73Jh                       | [ba7fb8e83c](https://bsd-hardware.info/?probe=ba7fb8e83c) | Feb 19, 2021 |
| Lenovo        | ThinkPad X220 4290NE3       | [a6a1824172](https://bsd-hardware.info/?probe=a6a1824172) | Feb 19, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [ed75b3d15b](https://bsd-hardware.info/?probe=ed75b3d15b) | Feb 18, 2021 |
| ASUSTek       | G73Jh                       | [35164ad41b](https://bsd-hardware.info/?probe=35164ad41b) | Feb 17, 2021 |
| Acer          | Aspire V5-531               | [ad4634140e](https://bsd-hardware.info/?probe=ad4634140e) | Feb 16, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [3df4abb2e9](https://bsd-hardware.info/?probe=3df4abb2e9) | Feb 16, 2021 |
| Acer          | Spin SP111-32N              | [dd7644026b](https://bsd-hardware.info/?probe=dd7644026b) | Feb 16, 2021 |
| Lenovo        | ThinkPad Edge 03282UA       | [0735d22638](https://bsd-hardware.info/?probe=0735d22638) | Feb 16, 2021 |
| Lenovo        | G505s 20255                 | [8bfcff9039](https://bsd-hardware.info/?probe=8bfcff9039) | Feb 16, 2021 |
| MOTILE        | M142                        | [5ec101bb3e](https://bsd-hardware.info/?probe=5ec101bb3e) | Feb 15, 2021 |
| A-DATA Tec... | XENIA159GENI72060           | [be88e8f865](https://bsd-hardware.info/?probe=be88e8f865) | Feb 15, 2021 |
| HP            | EliteBook 8460p             | [ada1119026](https://bsd-hardware.info/?probe=ada1119026) | Feb 14, 2021 |
| HP            | ENVY dv7                    | [4637a9eeff](https://bsd-hardware.info/?probe=4637a9eeff) | Feb 14, 2021 |
| ASUSTek       | X553MA                      | [cfc7d86b5a](https://bsd-hardware.info/?probe=cfc7d86b5a) | Feb 14, 2021 |
| Dell          | G7 7500                     | [a1c2eaee5f](https://bsd-hardware.info/?probe=a1c2eaee5f) | Feb 14, 2021 |
| Lenovo        | ThinkPad T495s 20QKS1812... | [0e5e228d18](https://bsd-hardware.info/?probe=0e5e228d18) | Feb 13, 2021 |
| Lenovo        | ThinkPad T495s 20QKS1812... | [2d93a6bebc](https://bsd-hardware.info/?probe=2d93a6bebc) | Feb 13, 2021 |
| ASUSTek       | E200HA                      | [5781a8b561](https://bsd-hardware.info/?probe=5781a8b561) | Feb 12, 2021 |
| Lenovo        | ThinkPad T61 6459CTO        | [c2c9931f74](https://bsd-hardware.info/?probe=c2c9931f74) | Feb 12, 2021 |
| Lenovo        | ThinkPad T61 6459CTO        | [c9e6341e78](https://bsd-hardware.info/?probe=c9e6341e78) | Feb 12, 2021 |
| Lenovo        | ThinkPad Edge 03282UA       | [f215fd8377](https://bsd-hardware.info/?probe=f215fd8377) | Feb 11, 2021 |
| Matsushita... | CF-T2BW1AXR                 | [f6ec2858a5](https://bsd-hardware.info/?probe=f6ec2858a5) | Feb 10, 2021 |
| Dell          | Latitude E6230              | [696e95fc08](https://bsd-hardware.info/?probe=696e95fc08) | Feb 10, 2021 |
| Lenovo        | ThinkPad Edge 03282UA       | [d48a95ffc2](https://bsd-hardware.info/?probe=d48a95ffc2) | Feb 09, 2021 |
| HP            | EliteBook 8570p             | [72137c63f8](https://bsd-hardware.info/?probe=72137c63f8) | Feb 09, 2021 |
| Lenovo        | 20QD0000US                  | [8d1c80c2cb](https://bsd-hardware.info/?probe=8d1c80c2cb) | Feb 09, 2021 |
| Dell          | Latitude 7370               | [8ec8d28024](https://bsd-hardware.info/?probe=8ec8d28024) | Feb 08, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [a2833c6695](https://bsd-hardware.info/?probe=a2833c6695) | Feb 08, 2021 |
| Lenovo        | ThinkPad X230 Tablet 343... | [55debb2f24](https://bsd-hardware.info/?probe=55debb2f24) | Feb 08, 2021 |
| Lenovo        | ThinkPad E420 1141CTO       | [a201c5f713](https://bsd-hardware.info/?probe=a201c5f713) | Feb 08, 2021 |
| Lenovo        | 20QD0000US                  | [77e80759a0](https://bsd-hardware.info/?probe=77e80759a0) | Feb 08, 2021 |
| System76      | Lemur Pro                   | [3071c04a4b](https://bsd-hardware.info/?probe=3071c04a4b) | Feb 08, 2021 |
| System76      | Galago Pro                  | [8f39c38e2e](https://bsd-hardware.info/?probe=8f39c38e2e) | Feb 08, 2021 |
| Lenovo        | ThinkPad E420 1141CTO       | [d0a5d1cb86](https://bsd-hardware.info/?probe=d0a5d1cb86) | Feb 08, 2021 |
| Lenovo        | ThinkPad T420 42368A3       | [5d7840d28e](https://bsd-hardware.info/?probe=5d7840d28e) | Feb 07, 2021 |
| Toshiba       | Satellite L50-C             | [7a5a694be1](https://bsd-hardware.info/?probe=7a5a694be1) | Feb 06, 2021 |
| Lenovo        | ThinkPad X220 42915CG       | [0bc3ba767e](https://bsd-hardware.info/?probe=0bc3ba767e) | Feb 06, 2021 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [045a80d8bc](https://bsd-hardware.info/?probe=045a80d8bc) | Feb 06, 2021 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [3754dfb89c](https://bsd-hardware.info/?probe=3754dfb89c) | Feb 06, 2021 |
| Dell          | Latitude E5430 vPro         | [bee421a110](https://bsd-hardware.info/?probe=bee421a110) | Feb 06, 2021 |
| Dell          | Latitude E5430 vPro         | [e8157ac6a3](https://bsd-hardware.info/?probe=e8157ac6a3) | Feb 06, 2021 |
| Lenovo        | ThinkPad E420 1141CTO       | [a51cf81e58](https://bsd-hardware.info/?probe=a51cf81e58) | Feb 06, 2021 |
| Acer          | Extensa 5220                | [5d6a8a51d0](https://bsd-hardware.info/?probe=5d6a8a51d0) | Feb 06, 2021 |
| Acer          | Extensa 5220                | [c443decee1](https://bsd-hardware.info/?probe=c443decee1) | Feb 06, 2021 |
| Dell          | Vostro 3750                 | [87b8a38ef9](https://bsd-hardware.info/?probe=87b8a38ef9) | Feb 05, 2021 |
| Lenovo        | ThinkPad T430 2349H2G       | [229db16a93](https://bsd-hardware.info/?probe=229db16a93) | Feb 05, 2021 |
| Acer          | Aspire E5-576               | [95e841a292](https://bsd-hardware.info/?probe=95e841a292) | Feb 04, 2021 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [92879d0781](https://bsd-hardware.info/?probe=92879d0781) | Feb 03, 2021 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [3ebe1fd064](https://bsd-hardware.info/?probe=3ebe1fd064) | Feb 03, 2021 |
| System76      | Lemur Pro                   | [e1cc11993d](https://bsd-hardware.info/?probe=e1cc11993d) | Feb 02, 2021 |
| HP            | EliteBook 8570p             | [46c938b853](https://bsd-hardware.info/?probe=46c938b853) | Feb 01, 2021 |
| Apple         | MacBookPro6,2               | [6174748602](https://bsd-hardware.info/?probe=6174748602) | Feb 01, 2021 |
| Lenovo        | ThinkPad SL510 2847Q9G      | [12e9632d4b](https://bsd-hardware.info/?probe=12e9632d4b) | Jan 31, 2021 |
| Dell          | Vostro V131                 | [897616d9c8](https://bsd-hardware.info/?probe=897616d9c8) | Jan 31, 2021 |
| Lenovo        | ThinkPad X230 Tablet 343... | [dbc05e2913](https://bsd-hardware.info/?probe=dbc05e2913) | Jan 30, 2021 |
| Acer          | Aspire V5-531               | [b917d2b6ad](https://bsd-hardware.info/?probe=b917d2b6ad) | Jan 30, 2021 |
| Toshiba       | Satellite L50-C             | [98af88dfe6](https://bsd-hardware.info/?probe=98af88dfe6) | Jan 30, 2021 |
| Clevo         | W55xEU                      | [ecacada83f](https://bsd-hardware.info/?probe=ecacada83f) | Jan 29, 2021 |
| Toshiba       | Satellite L50-C             | [f76ea8946b](https://bsd-hardware.info/?probe=f76ea8946b) | Jan 28, 2021 |
| Lenovo        | ThinkPad T570 20HAS0DP00    | [f73844a707](https://bsd-hardware.info/?probe=f73844a707) | Jan 26, 2021 |
| Dell          | Vostro V131                 | [630822a6a1](https://bsd-hardware.info/?probe=630822a6a1) | Jan 25, 2021 |
| Matsushita... | CF-T2BW1AXR                 | [c16cd20c42](https://bsd-hardware.info/?probe=c16cd20c42) | Jan 25, 2021 |
| Acer          | Aspire 5515                 | [d9ef473a7a](https://bsd-hardware.info/?probe=d9ef473a7a) | Jan 25, 2021 |
| Fujitsu       | LIFEBOOK E753               | [9a615ebaf8](https://bsd-hardware.info/?probe=9a615ebaf8) | Jan 24, 2021 |
| HP            | Laptop 17-ca1xxx            | [ecf07ad5fe](https://bsd-hardware.info/?probe=ecf07ad5fe) | Jan 24, 2021 |
| Acer          | Aspire V5-531               | [41caa6acaa](https://bsd-hardware.info/?probe=41caa6acaa) | Jan 24, 2021 |
| HP            | EliteBook 8570p             | [c2e361eeff](https://bsd-hardware.info/?probe=c2e361eeff) | Jan 23, 2021 |
| HP            | EliteBook 8570p             | [86e5ba4c5b](https://bsd-hardware.info/?probe=86e5ba4c5b) | Jan 22, 2021 |
| Apple         | MacBookPro11,4              | [dad5d994a0](https://bsd-hardware.info/?probe=dad5d994a0) | Jan 20, 2021 |
| System76      | Bonobo Extreme              | [8e91df5bb8](https://bsd-hardware.info/?probe=8e91df5bb8) | Jan 20, 2021 |
| Apple         | MacBook4,1                  | [539b95f535](https://bsd-hardware.info/?probe=539b95f535) | Jan 20, 2021 |
| Lenovo        | ThinkPad P50 20EQS0U60C     | [d8cf9e878e](https://bsd-hardware.info/?probe=d8cf9e878e) | Jan 19, 2021 |
| Dell          | Latitude E7240              | [b79278a4ad](https://bsd-hardware.info/?probe=b79278a4ad) | Jan 19, 2021 |
| Matsushita... | CF-T2BW1AXR                 | [7f12336d2f](https://bsd-hardware.info/?probe=7f12336d2f) | Jan 19, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [9458fbeb87](https://bsd-hardware.info/?probe=9458fbeb87) | Jan 19, 2021 |
| HP            | EliteBook 8570p             | [fcedf7a28d](https://bsd-hardware.info/?probe=fcedf7a28d) | Jan 19, 2021 |
| Matsushita... | CF-T2BW1AXR                 | [393d233391](https://bsd-hardware.info/?probe=393d233391) | Jan 19, 2021 |
| TUXEDO        | Pulse 14 Gen1               | [5359b4dee9](https://bsd-hardware.info/?probe=5359b4dee9) | Jan 18, 2021 |
| Toshiba       | KIRA                        | [1ee77fde0b](https://bsd-hardware.info/?probe=1ee77fde0b) | Jan 18, 2021 |
| Dell          | Vostro 1510                 | [ef1c0e0f2e](https://bsd-hardware.info/?probe=ef1c0e0f2e) | Jan 17, 2021 |
| Matsushita... | CF-T2BW1AXR                 | [4426ed4494](https://bsd-hardware.info/?probe=4426ed4494) | Jan 15, 2021 |
| Dell          | Inspiron 5521               | [b663df318c](https://bsd-hardware.info/?probe=b663df318c) | Jan 14, 2021 |
| Lenovo        | ThinkPad E590 20NB005MUS    | [f32bbdaff3](https://bsd-hardware.info/?probe=f32bbdaff3) | Jan 13, 2021 |
| Acer          | Aspire E5-521               | [079f83a360](https://bsd-hardware.info/?probe=079f83a360) | Jan 13, 2021 |
| Lenovo        | ThinkPad X201 3626HMG       | [a0b1fd0ca5](https://bsd-hardware.info/?probe=a0b1fd0ca5) | Jan 12, 2021 |
| Lenovo        | ThinkPad X201 3626HMG       | [f384858fd6](https://bsd-hardware.info/?probe=f384858fd6) | Jan 12, 2021 |
| HP            | EliteBook 2530p             | [1fd927e2cd](https://bsd-hardware.info/?probe=1fd927e2cd) | Jan 11, 2021 |
| Lenovo        | ThinkPad X270 20HMCTO1WW    | [6598d39f06](https://bsd-hardware.info/?probe=6598d39f06) | Jan 11, 2021 |
| Sony          | VGN-FW290J                  | [6683d77c92](https://bsd-hardware.info/?probe=6683d77c92) | Jan 11, 2021 |
| HP            | EliteBook 8570p             | [bb4f8afc82](https://bsd-hardware.info/?probe=bb4f8afc82) | Jan 09, 2021 |
| BANGHO        | MAX G5 i1                   | [c184b13749](https://bsd-hardware.info/?probe=c184b13749) | Jan 09, 2021 |
| Alienware     | 14                          | [dd2cc000a7](https://bsd-hardware.info/?probe=dd2cc000a7) | Jan 07, 2021 |
| Alienware     | 14                          | [48f61623f2](https://bsd-hardware.info/?probe=48f61623f2) | Jan 07, 2021 |
| Lenovo        | 41875PG                     | [0de11a4114](https://bsd-hardware.info/?probe=0de11a4114) | Jan 07, 2021 |
| Dell          | Latitude 7480               | [9c8bd9c479](https://bsd-hardware.info/?probe=9c8bd9c479) | Jan 04, 2021 |
| Dell          | Latitude 7480               | [78d3823932](https://bsd-hardware.info/?probe=78d3823932) | Jan 04, 2021 |
| Lenovo        | ThinkPad T520 4239CTO       | [b2669e195e](https://bsd-hardware.info/?probe=b2669e195e) | Jan 03, 2021 |
| Lenovo        | ThinkPad T520 4239CTO       | [a502198932](https://bsd-hardware.info/?probe=a502198932) | Jan 03, 2021 |
| Lenovo        | ThinkPad X220 4286CTO       | [c5e7d3037f](https://bsd-hardware.info/?probe=c5e7d3037f) | Jan 03, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [1ffaf5420c](https://bsd-hardware.info/?probe=1ffaf5420c) | Jan 03, 2021 |
| HP            | EliteBook 840 G3            | [11011ecee1](https://bsd-hardware.info/?probe=11011ecee1) | Jan 02, 2021 |
| HP            | ZBook 17 G4                 | [40ad0612de](https://bsd-hardware.info/?probe=40ad0612de) | Jan 02, 2021 |
| Lenovo        | ThinkPad E590 20NB005MUS    | [bb0846a279](https://bsd-hardware.info/?probe=bb0846a279) | Dec 30, 2020 |
| Lenovo        | ThinkPad E590 20NB005MUS    | [6491c362f0](https://bsd-hardware.info/?probe=6491c362f0) | Dec 29, 2020 |
| Notebook      | N7x0WU                      | [a478d3904a](https://bsd-hardware.info/?probe=a478d3904a) | Dec 28, 2020 |
| Pegatron      | T12Ah                       | [427bb18c90](https://bsd-hardware.info/?probe=427bb18c90) | Dec 27, 2020 |
| HP            | 655                         | [ae2de01d19](https://bsd-hardware.info/?probe=ae2de01d19) | Dec 26, 2020 |
| Lenovo        | ThinkPad P53 20QQS3R100     | [50ba4dea40](https://bsd-hardware.info/?probe=50ba4dea40) | Dec 25, 2020 |
| MSI           | MS-16GH                     | [35ad1fb80b](https://bsd-hardware.info/?probe=35ad1fb80b) | Dec 24, 2020 |
| Dell          | Inspiron 5758               | [c61b54598c](https://bsd-hardware.info/?probe=c61b54598c) | Dec 23, 2020 |
| Toshiba       | Satellite L50-C             | [8195760dd6](https://bsd-hardware.info/?probe=8195760dd6) | Dec 23, 2020 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [b6ae43880d](https://bsd-hardware.info/?probe=b6ae43880d) | Dec 22, 2020 |
| Lenovo        | ThinkPad T460 20FMS2J000    | [a069a19a1b](https://bsd-hardware.info/?probe=a069a19a1b) | Dec 22, 2020 |
| Samsung       | N140                        | [cab912c576](https://bsd-hardware.info/?probe=cab912c576) | Dec 21, 2020 |
| Lenovo        | ThinkPad X200s 7470A98      | [41f36aa8b6](https://bsd-hardware.info/?probe=41f36aa8b6) | Dec 19, 2020 |
| Lenovo        | ThinkPad W500 4063HK6       | [7330a399ba](https://bsd-hardware.info/?probe=7330a399ba) | Dec 19, 2020 |
| Lenovo        | Y50-70 20378                | [b65cd3d698](https://bsd-hardware.info/?probe=b65cd3d698) | Dec 18, 2020 |
| Dell          | Latitude E7440              | [af765f08b5](https://bsd-hardware.info/?probe=af765f08b5) | Dec 18, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [de7d8622aa](https://bsd-hardware.info/?probe=de7d8622aa) | Dec 18, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [7f6ebffad8](https://bsd-hardware.info/?probe=7f6ebffad8) | Dec 18, 2020 |
| HP            | 2000                        | [f83c769501](https://bsd-hardware.info/?probe=f83c769501) | Dec 18, 2020 |
| Lenovo        | ThinkPad T460p 20FXCTO1W... | [ddc907ccf4](https://bsd-hardware.info/?probe=ddc907ccf4) | Dec 17, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [1414d7ae80](https://bsd-hardware.info/?probe=1414d7ae80) | Dec 16, 2020 |
| Lenovo        | ThinkPad T490 20N3X50500    | [c4d6dd6438](https://bsd-hardware.info/?probe=c4d6dd6438) | Dec 16, 2020 |
| HP            | OMEN Laptop 15-en0xxx       | [7b7c8bf457](https://bsd-hardware.info/?probe=7b7c8bf457) | Dec 16, 2020 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [0309e4ac24](https://bsd-hardware.info/?probe=0309e4ac24) | Dec 16, 2020 |
| Lenovo        | ThinkPad X230 23244A9       | [d2e3890c19](https://bsd-hardware.info/?probe=d2e3890c19) | Dec 16, 2020 |
| Lenovo        | ThinkPad X230 23244A9       | [7aaf6835e2](https://bsd-hardware.info/?probe=7aaf6835e2) | Dec 16, 2020 |
| Toshiba       | Satellite C655D             | [23ca402ed6](https://bsd-hardware.info/?probe=23ca402ed6) | Dec 16, 2020 |
| Lenovo        | IdeaPad Slim 7 14IIL05 8... | [3278083ba9](https://bsd-hardware.info/?probe=3278083ba9) | Dec 16, 2020 |
| Dell          | XPS 15 9570                 | [91c4a075a1](https://bsd-hardware.info/?probe=91c4a075a1) | Dec 16, 2020 |
| Lenovo        | G50-80 80E5                 | [61c248a1e6](https://bsd-hardware.info/?probe=61c248a1e6) | Dec 16, 2020 |
| Lenovo        | ThinkPad T420s 417153U      | [7af178dcda](https://bsd-hardware.info/?probe=7af178dcda) | Dec 15, 2020 |
| Acer          | Aspire E5-471               | [a2a6e419ed](https://bsd-hardware.info/?probe=a2a6e419ed) | Dec 15, 2020 |
| Acer          | Aspire E5-471               | [6bfc5ec3b9](https://bsd-hardware.info/?probe=6bfc5ec3b9) | Dec 15, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [1952513db8](https://bsd-hardware.info/?probe=1952513db8) | Dec 15, 2020 |
| Lenovo        | ThinkPad X250 20CLS8S900    | [b67a427b6c](https://bsd-hardware.info/?probe=b67a427b6c) | Dec 12, 2020 |
| Lenovo        | ThinkPad T420 4180AJ3       | [683eca8c23](https://bsd-hardware.info/?probe=683eca8c23) | Dec 11, 2020 |
| Eluktronic... | THINN-15                    | [b898297110](https://bsd-hardware.info/?probe=b898297110) | Dec 10, 2020 |
| Eluktronic... | THINN-15                    | [78bab7cda9](https://bsd-hardware.info/?probe=78bab7cda9) | Dec 10, 2020 |
| Lenovo        | ThinkPad X250 20CLS02000    | [cbd9f8a13c](https://bsd-hardware.info/?probe=cbd9f8a13c) | Dec 09, 2020 |
| Dell          | Latitude 2100               | [899ce6ffe4](https://bsd-hardware.info/?probe=899ce6ffe4) | Dec 08, 2020 |
| ASUSTek       | K72F                        | [321cd9d139](https://bsd-hardware.info/?probe=321cd9d139) | Dec 08, 2020 |
| ASUSTek       | K72F                        | [b36ff0b052](https://bsd-hardware.info/?probe=b36ff0b052) | Dec 08, 2020 |
| Toshiba       | Satellite L50-C             | [2b478c0d01](https://bsd-hardware.info/?probe=2b478c0d01) | Dec 08, 2020 |
| Acer          | Peppy                       | [d15caaca04](https://bsd-hardware.info/?probe=d15caaca04) | Dec 08, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [16206c4970](https://bsd-hardware.info/?probe=16206c4970) | Dec 07, 2020 |
| Lenovo        | ThinkPad T400 6475K43       | [e5b985be88](https://bsd-hardware.info/?probe=e5b985be88) | Dec 07, 2020 |
| Dell          | XPS 13 9300                 | [7c1efa11b9](https://bsd-hardware.info/?probe=7c1efa11b9) | Dec 07, 2020 |
| Lenovo        | ThinkPad T450s 20BWS05G0... | [bc2855974c](https://bsd-hardware.info/?probe=bc2855974c) | Dec 06, 2020 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [e0f096eb0d](https://bsd-hardware.info/?probe=e0f096eb0d) | Dec 06, 2020 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [3d7c8e695c](https://bsd-hardware.info/?probe=3d7c8e695c) | Dec 06, 2020 |
| PC Special... | Recoil II                   | [343eec31b5](https://bsd-hardware.info/?probe=343eec31b5) | Dec 06, 2020 |
| Panasonic     | CFMX4-1                     | [761d21f21a](https://bsd-hardware.info/?probe=761d21f21a) | Dec 06, 2020 |
| Samsung       | N145P/N250P/N260P           | [b4cb55c681](https://bsd-hardware.info/?probe=b4cb55c681) | Dec 05, 2020 |
| Lenovo        | ThinkPad R400 7439X13       | [0d85bf3f3a](https://bsd-hardware.info/?probe=0d85bf3f3a) | Dec 03, 2020 |
| Acer          | Aspire V5-531               | [f62cab95dd](https://bsd-hardware.info/?probe=f62cab95dd) | Dec 03, 2020 |
| Sony          | SVP1321V9RB                 | [9cddee6a0a](https://bsd-hardware.info/?probe=9cddee6a0a) | Dec 01, 2020 |
| MSI           | X460/X460DX                 | [099fbcbec8](https://bsd-hardware.info/?probe=099fbcbec8) | Dec 01, 2020 |
| Lenovo        | ThinkPad T460 20FMS78014    | [c811e29e6c](https://bsd-hardware.info/?probe=c811e29e6c) | Nov 30, 2020 |
| HP            | ProBook 640 G1              | [8f36943974](https://bsd-hardware.info/?probe=8f36943974) | Nov 29, 2020 |
| Dell          | XPS 13 9300                 | [bf5b8bac58](https://bsd-hardware.info/?probe=bf5b8bac58) | Nov 27, 2020 |
| Dell          | Latitude E6440              | [f9278127a1](https://bsd-hardware.info/?probe=f9278127a1) | Nov 27, 2020 |
| Dell          | Inspiron 3542               | [063a26aec7](https://bsd-hardware.info/?probe=063a26aec7) | Nov 26, 2020 |
| ASUSTek       | X55A                        | [4591e37fa0](https://bsd-hardware.info/?probe=4591e37fa0) | Nov 25, 2020 |
| Lenovo        | ThinkPad T420 4236N2G       | [1565d5d570](https://bsd-hardware.info/?probe=1565d5d570) | Nov 24, 2020 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [0738824c51](https://bsd-hardware.info/?probe=0738824c51) | Nov 22, 2020 |
| HP            | EliteBook 8570p             | [1f3fa432dc](https://bsd-hardware.info/?probe=1f3fa432dc) | Nov 21, 2020 |
| Dell          | Latitude 5280               | [d1be72cc7e](https://bsd-hardware.info/?probe=d1be72cc7e) | Nov 21, 2020 |
| Dell          | Latitude 5280               | [fd4e8756b4](https://bsd-hardware.info/?probe=fd4e8756b4) | Nov 21, 2020 |
| HP            | ProBook 430 G2              | [da49561a8f](https://bsd-hardware.info/?probe=da49561a8f) | Nov 20, 2020 |
| Samsung       | NC210/NC110                 | [3ce5c260a2](https://bsd-hardware.info/?probe=3ce5c260a2) | Nov 20, 2020 |
| Lenovo        | Y50-70 20378                | [4b3200a110](https://bsd-hardware.info/?probe=4b3200a110) | Nov 19, 2020 |
| Lenovo        | ThinkPad T440 20B7S0A800    | [d3474f1ca3](https://bsd-hardware.info/?probe=d3474f1ca3) | Nov 18, 2020 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [dce3ba8c99](https://bsd-hardware.info/?probe=dce3ba8c99) | Nov 18, 2020 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [e7db61fd34](https://bsd-hardware.info/?probe=e7db61fd34) | Nov 17, 2020 |
| Matsushita... | CF-T2BW1AXR                 | [1cb38b186d](https://bsd-hardware.info/?probe=1cb38b186d) | Nov 13, 2020 |
| HP            | EliteBook 840 G3            | [e44b010bc9](https://bsd-hardware.info/?probe=e44b010bc9) | Nov 11, 2020 |
| HP            | EliteBook 840 G3            | [2fb1bc911f](https://bsd-hardware.info/?probe=2fb1bc911f) | Nov 11, 2020 |
| Sony          | VGN-S150(UC)                | [f2f3923ea6](https://bsd-hardware.info/?probe=f2f3923ea6) | Nov 10, 2020 |
| Lenovo        | ThinkPad T580 20L9000ECD    | [771d8ead80](https://bsd-hardware.info/?probe=771d8ead80) | Nov 10, 2020 |
| HP            | ProBook 650 G2              | [b6c63ea3f8](https://bsd-hardware.info/?probe=b6c63ea3f8) | Nov 09, 2020 |
| HP            | ProBook 650 G2              | [0d5f2584b7](https://bsd-hardware.info/?probe=0d5f2584b7) | Nov 09, 2020 |
| System76      | Serval WS                   | [0ac6aed43b](https://bsd-hardware.info/?probe=0ac6aed43b) | Nov 09, 2020 |
| System76      | Bonobo Extreme              | [de33b2c793](https://bsd-hardware.info/?probe=de33b2c793) | Nov 09, 2020 |
| System76      | Serval WS                   | [b23f15f795](https://bsd-hardware.info/?probe=b23f15f795) | Nov 09, 2020 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [698d36e0c7](https://bsd-hardware.info/?probe=698d36e0c7) | Nov 05, 2020 |
| System76      | Lemur Pro                   | [0b36cb0679](https://bsd-hardware.info/?probe=0b36cb0679) | Nov 05, 2020 |
| Lenovo        | V130-15IKB 81HN             | [d20a8be7d4](https://bsd-hardware.info/?probe=d20a8be7d4) | Nov 03, 2020 |
| Apple         | MacBookPro6,2               | [81e299fd14](https://bsd-hardware.info/?probe=81e299fd14) | Nov 03, 2020 |
| Fujitsu       | LIFEBOOK AH531              | [4ab524eadb](https://bsd-hardware.info/?probe=4ab524eadb) | Nov 02, 2020 |
| Lenovo        | ThinkPad T520 4243FS9       | [242cd8a6e7](https://bsd-hardware.info/?probe=242cd8a6e7) | Nov 02, 2020 |
| HP            | Compaq nx7400 (RU430ET#A... | [c9c7bae008](https://bsd-hardware.info/?probe=c9c7bae008) | Nov 01, 2020 |
| Lenovo        | ThinkPad X13 Gen 1 20UFC... | [ed34c1310f](https://bsd-hardware.info/?probe=ed34c1310f) | Nov 01, 2020 |
| Lenovo        | ThinkPad T430s 23564Q4      | [661877d8c9](https://bsd-hardware.info/?probe=661877d8c9) | Nov 01, 2020 |
| Toshiba       | Satellite M100              | [e6e0a1294c](https://bsd-hardware.info/?probe=e6e0a1294c) | Nov 01, 2020 |
| Lenovo        | ThinkPad T495 20NJS0KP00    | [7a706e46de](https://bsd-hardware.info/?probe=7a706e46de) | Oct 31, 2020 |
| Lenovo        | ThinkPad T430 23501B3       | [53233cc736](https://bsd-hardware.info/?probe=53233cc736) | Oct 31, 2020 |
| Toshiba       | Satellite L50-C             | [e5c99b958d](https://bsd-hardware.info/?probe=e5c99b958d) | Oct 31, 2020 |
| Acer          | Aspire V5-531               | [f9a374a310](https://bsd-hardware.info/?probe=f9a374a310) | Oct 30, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [7c8972f650](https://bsd-hardware.info/?probe=7c8972f650) | Oct 29, 2020 |
| Lenovo        | ThinkPad X61 7675A29        | [c7a5a867ab](https://bsd-hardware.info/?probe=c7a5a867ab) | Oct 29, 2020 |
| Lenovo        | ThinkPad T410 2537AT1       | [4e693bfcb2](https://bsd-hardware.info/?probe=4e693bfcb2) | Oct 29, 2020 |
| Dell          | Precision M4800             | [8afb8e7443](https://bsd-hardware.info/?probe=8afb8e7443) | Oct 29, 2020 |
| Dell          | Vostro 3550                 | [ecddd9d212](https://bsd-hardware.info/?probe=ecddd9d212) | Oct 29, 2020 |
| Schenker      | N13xWU                      | [c23a22a72d](https://bsd-hardware.info/?probe=c23a22a72d) | Oct 29, 2020 |
| Fujitsu       | LIFEBOOK AH531              | [0c8f5b5cb4](https://bsd-hardware.info/?probe=0c8f5b5cb4) | Oct 29, 2020 |
| Lenovo        | ThinkPad W520 4284W5L       | [2664153a6e](https://bsd-hardware.info/?probe=2664153a6e) | Oct 29, 2020 |
| Lenovo        | ThinkPad X230 2320JXM       | [cdbf62a168](https://bsd-hardware.info/?probe=cdbf62a168) | Oct 29, 2020 |
| HUAWEI        | MACH-WX9                    | [2a1b806f39](https://bsd-hardware.info/?probe=2a1b806f39) | Oct 29, 2020 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [cd2ad2800e](https://bsd-hardware.info/?probe=cd2ad2800e) | Oct 29, 2020 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [8387b08f3f](https://bsd-hardware.info/?probe=8387b08f3f) | Oct 29, 2020 |
| Dell          | Inspiron 3542               | [aa90ef6e4b](https://bsd-hardware.info/?probe=aa90ef6e4b) | Oct 29, 2020 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [26c750117f](https://bsd-hardware.info/?probe=26c750117f) | Oct 28, 2020 |
| Lenovo        | ThinkPad T490 20N3X50500    | [0a6ee35d3a](https://bsd-hardware.info/?probe=0a6ee35d3a) | Oct 28, 2020 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [f8fa32353f](https://bsd-hardware.info/?probe=f8fa32353f) | Oct 28, 2020 |
| System76      | Lemur Pro                   | [d775f6dac4](https://bsd-hardware.info/?probe=d775f6dac4) | Oct 26, 2020 |
| Toshiba       | Satellite C655D             | [4492d307fc](https://bsd-hardware.info/?probe=4492d307fc) | Oct 25, 2020 |
| Lenovo        | ThinkPad X230 23254S6       | [f4ac5ddaa4](https://bsd-hardware.info/?probe=f4ac5ddaa4) | Oct 25, 2020 |
| Sony          | SVP1321V9RB                 | [3f414895be](https://bsd-hardware.info/?probe=3f414895be) | Oct 24, 2020 |
| HP            | 635                         | [3b21406e87](https://bsd-hardware.info/?probe=3b21406e87) | Oct 23, 2020 |
| Dell          | Latitude E7240              | [0e736e5e31](https://bsd-hardware.info/?probe=0e736e5e31) | Oct 20, 2020 |
| Lenovo        | ThinkPad T495s 20QKS1812... | [a3bc7a0c88](https://bsd-hardware.info/?probe=a3bc7a0c88) | Oct 19, 2020 |
| Lenovo        | ThinkPad X230 23257Y1       | [7d49ddfd8c](https://bsd-hardware.info/?probe=7d49ddfd8c) | Oct 19, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [de9499f9fb](https://bsd-hardware.info/?probe=de9499f9fb) | Oct 15, 2020 |
| Acer          | Aspire one                  | [8514ff3ee8](https://bsd-hardware.info/?probe=8514ff3ee8) | Oct 14, 2020 |
| Lenovo        | ThinkPad T480 20L5S1S000    | [ec1fa2e60c](https://bsd-hardware.info/?probe=ec1fa2e60c) | Oct 13, 2020 |
| Lenovo        | ThinkPad E495 20NE0001US    | [a1fc75a9b7](https://bsd-hardware.info/?probe=a1fc75a9b7) | Oct 09, 2020 |
| HP            | ProBook 6550b               | [c1f086e90c](https://bsd-hardware.info/?probe=c1f086e90c) | Oct 08, 2020 |
| System76      | Lemur Pro                   | [30b32ece8f](https://bsd-hardware.info/?probe=30b32ece8f) | Oct 07, 2020 |
| Lenovo        | ThinkPad X220 4291OQ6       | [ed0340e006](https://bsd-hardware.info/?probe=ed0340e006) | Oct 04, 2020 |
| Lenovo        | ThinkPad T480 20L5S1S000    | [655613c78b](https://bsd-hardware.info/?probe=655613c78b) | Oct 04, 2020 |
| Lenovo        | Y50-70 20378                | [51cffbc74d](https://bsd-hardware.info/?probe=51cffbc74d) | Oct 03, 2020 |
| Lenovo        | ThinkPad W520 4284W5L       | [01d2c090de](https://bsd-hardware.info/?probe=01d2c090de) | Oct 03, 2020 |
| Dell          | Inspiron MM061              | [7f814a7e8d](https://bsd-hardware.info/?probe=7f814a7e8d) | Oct 02, 2020 |
| Acer          | Peppy                       | [d68bd5cbb5](https://bsd-hardware.info/?probe=d68bd5cbb5) | Oct 02, 2020 |
| Acer          | Peppy                       | [26058cddbf](https://bsd-hardware.info/?probe=26058cddbf) | Oct 02, 2020 |
| Dell          | Precision 5510              | [a167382d6e](https://bsd-hardware.info/?probe=a167382d6e) | Sep 26, 2020 |
| Dell          | Precision 5510              | [621d3ea7a0](https://bsd-hardware.info/?probe=621d3ea7a0) | Sep 26, 2020 |
| Dell          | Precision 5510              | [837ffdd649](https://bsd-hardware.info/?probe=837ffdd649) | Sep 26, 2020 |
| ASUSTek       | UX305FA                     | [4ecb1e9cd3](https://bsd-hardware.info/?probe=4ecb1e9cd3) | Sep 25, 2020 |
| Apple         | MacBookAir5,1               | [6cced6fcf0](https://bsd-hardware.info/?probe=6cced6fcf0) | Sep 23, 2020 |
| ASUSTek       | N56VJ                       | [9fb23e0394](https://bsd-hardware.info/?probe=9fb23e0394) | Sep 22, 2020 |
| Dell          | Latitude 3490               | [b28cc12aeb](https://bsd-hardware.info/?probe=b28cc12aeb) | Sep 20, 2020 |
| Lenovo        | ThinkPad X250 20CL001DGE    | [9057cb0832](https://bsd-hardware.info/?probe=9057cb0832) | Sep 18, 2020 |
| Notebook      | N7x0WU                      | [e444068605](https://bsd-hardware.info/?probe=e444068605) | Sep 17, 2020 |
| Lenovo        | ThinkPad T460 20FMS78014    | [53e545fcb9](https://bsd-hardware.info/?probe=53e545fcb9) | Sep 17, 2020 |
| Acer          | TravelMate 270              | [56a5581907](https://bsd-hardware.info/?probe=56a5581907) | Sep 17, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/FreeBSD/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| FreeBSD 13.0         | 111       | 12.17%  |
| FreeBSD 13.1         | 82        | 8.99%   |
| FreeBSD 12.2         | 59        | 6.47%   |
| FreeBSD 14.0-CURRENT | 56        | 6.14%   |
| FreeBSD 13.0-p4      | 35        | 3.84%   |
| FreeBSD 12.2-p2      | 34        | 3.73%   |
| FreeBSD 13.0-CURRENT | 31        | 3.4%    |
| FreeBSD 13.0-STABLE  | 28        | 3.07%   |
| FreeBSD 12.1         | 28        | 3.07%   |
| FreeBSD 12.1-p8      | 26        | 2.85%   |
| FreeBSD 13.0-p5      | 25        | 2.74%   |
| FreeBSD 13.0-p3      | 23        | 2.52%   |
| FreeBSD 12.2-p4      | 23        | 2.52%   |
| FreeBSD 12.1-p10     | 23        | 2.52%   |
| FreeBSD 13.1-p2      | 20        | 2.19%   |
| FreeBSD 12.1-p5      | 20        | 2.19%   |
| FreeBSD 13.0-p7      | 19        | 2.08%   |
| FreeBSD 12.2-p3      | 18        | 1.97%   |
| FreeBSD 13.0-p2      | 17        | 1.86%   |
| FreeBSD 12.1-STABLE  | 15        | 1.64%   |
| FreeBSD 12.1-p7      | 15        | 1.64%   |
| FreeBSD 13.0-p6      | 13        | 1.43%   |
| FreeBSD 12.2-p6      | 12        | 1.32%   |
| FreeBSD 12.2-STABLE  | 10        | 1.1%    |
| FreeBSD 13.0-p11     | 9         | 0.99%   |
| FreeBSD 13.1-p1      | 8         | 0.88%   |
| FreeBSD 13.1-STABLE  | 7         | 0.77%   |
| FreeBSD 12.1-p9      | 7         | 0.77%   |
| FreeBSD 12.1-p6      | 7         | 0.77%   |
| FreeBSD 12.1-p4      | 7         | 0.77%   |
| FreeBSD 13.0-p1      | 6         | 0.66%   |
| FreeBSD 13.0-RC5     | 5         | 0.55%   |
| FreeBSD 13.0-RC1     | 5         | 0.55%   |
| FreeBSD 13.0-p10     | 5         | 0.55%   |
| FreeBSD 13.0-BETA1   | 5         | 0.55%   |
| FreeBSD 12.2-p5      | 5         | 0.55%   |
| FreeBSD 13.0-RC3     | 4         | 0.44%   |
| FreeBSD 13.0-RC2     | 4         | 0.44%   |
| FreeBSD 13.0-BETA3   | 4         | 0.44%   |
| FreeBSD 12.3         | 4         | 0.44%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| FreeBSD | 763       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 722       | 94.5%   |
| i386  | 41        | 5.37%   |
| arm64 | 1         | 0.13%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| XFCE          | 180       | 22.5%   |
| KDE5          | 152       | 19%     |
| Console       | 94        | 11.75%  |
| TWM           | 80        | 10%     |
| GNOME         | 73        | 9.13%   |
| i3            | 61        | 7.63%   |
| MATE          | 48        | 6%      |
| Openbox       | 24        | 3%      |
| Cinnamon      | 15        | 1.88%   |
| AwesomeWM     | 14        | 1.75%   |
| LXQt          | 12        | 1.5%    |
| LXDE          | 8         | 1%      |
| Fluxbox       | 7         | 0.88%   |
| Enlightenment | 7         | 0.88%   |
| Lumina        | 4         | 0.5%    |
| dwm           | 4         | 0.5%    |
| GNUstep       | 3         | 0.38%   |
| spectrwm      | 2         | 0.25%   |
| Picom         | 2         | 0.25%   |
| IceWM         | 2         | 0.25%   |
| Xfwm4         | 1         | 0.13%   |
| X-Cinnamon    | 1         | 0.13%   |
| StumpWM       | 1         | 0.13%   |
| helloDesktop  | 1         | 0.13%   |
| ctwm          | 1         | 0.13%   |
| Compton       | 1         | 0.13%   |
| CDE           | 1         | 0.13%   |
| awesome       | 1         | 0.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 653       | 83.83%  |
| Console | 107       | 13.74%  |
| Wayland | 19        | 2.44%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 321       | 40.33%  |
| SDDM    | 157       | 19.72%  |
| SLiM    | 138       | 17.34%  |
| XDM     | 68        | 8.54%   |
| LightDM | 56        | 7.04%   |
| GDM     | 46        | 5.78%   |
| Ly      | 7         | 0.88%   |
| PCDM    | 2         | 0.25%   |
| WDM     | 1         | 0.13%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Notebooks | Percent |
|------------------|-----------|---------|
| C                | 327       | 40.62%  |
| Unknown          | 210       | 26.09%  |
| en_US            | 110       | 13.66%  |
| ru_RU            | 30        | 3.73%   |
| fr_FR            | 19        | 2.36%   |
| en_GB            | 16        | 1.99%   |
| de_DE            | 15        | 1.86%   |
| zh_CN            | 10        | 1.24%   |
| pl_PL            | 5         | 0.62%   |
| en_CA            | 5         | 0.62%   |
| nb_NO            | 4         | 0.5%    |
| en_NZ            | 4         | 0.5%    |
| uk_UA            | 3         | 0.37%   |
| pt_BR            | 3         | 0.37%   |
| en_US.US-ASCII   | 3         | 0.37%   |
| en_US.ISO8859-1  | 3         | 0.37%   |
| ja_JP            | 2         | 0.25%   |
| es_ES            | 2         | 0.25%   |
| en_SG            | 2         | 0.25%   |
| en_IE            | 2         | 0.25%   |
| en_AU            | 2         | 0.25%   |
| de_DE.ISO8859-1  | 2         | 0.25%   |
| de_CH            | 2         | 0.25%   |
| cs_CZ            | 2         | 0.25%   |
| zh_TW            | 1         | 0.12%   |
| zh_CN.GB2312     | 1         | 0.12%   |
| sl_SI            | 1         | 0.12%   |
| pt_PT            | 1         | 0.12%   |
| POSIX            | 1         | 0.12%   |
| nl_NL            | 1         | 0.12%   |
| it_IT.ISO8859-15 | 1         | 0.12%   |
| it_IT.ISO8859-1  | 1         | 0.12%   |
| it_IT            | 1         | 0.12%   |
| it_CH            | 1         | 0.12%   |
| hu_HU.US-ASCII   | 1         | 0.12%   |
| fi_FI            | 1         | 0.12%   |
| es_AR            | 1         | 0.12%   |
| en_PH            | 1         | 0.12%   |
| en_NZ.US-ASCII   | 1         | 0.12%   |
| en_NL            | 1         | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 535       | 69.75%  |
| BIOS | 232       | 30.25%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Zfs  | 480       | 62.34%  |
| Ufs  | 289       | 37.53%  |
| Xfs  | 1         | 0.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 673       | 87.63%  |
| MBR     | 90        | 11.72%  |
| BSD     | 4         | 0.52%   |
| Unknown | 1         | 0.13%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 269       | 35.26%  |
| Dell                   | 155       | 20.31%  |
| Hewlett-Packard        | 65        | 8.52%   |
| ASUSTek Computer       | 53        | 6.95%   |
| Acer                   | 44        | 5.77%   |
| Apple                  | 21        | 2.75%   |
| Toshiba                | 19        | 2.49%   |
| System76               | 13        | 1.7%    |
| Samsung Electronics    | 13        | 1.7%    |
| MSI                    | 11        | 1.44%   |
| Sony                   | 9         | 1.18%   |
| HUAWEI                 | 8         | 1.05%   |
| TUXEDO                 | 6         | 0.79%   |
| IBM                    | 6         | 0.79%   |
| Fujitsu                | 6         | 0.79%   |
| Notebook               | 5         | 0.66%   |
| Framework              | 5         | 0.66%   |
| Google                 | 4         | 0.52%   |
| Gigabyte Technology    | 4         | 0.52%   |
| Unknown                | 4         | 0.52%   |
| Gateway                | 3         | 0.39%   |
| Deciso                 | 3         | 0.39%   |
| Avell High Performance | 3         | 0.39%   |
| Timi                   | 2         | 0.26%   |
| Schenker               | 2         | 0.26%   |
| Panasonic              | 2         | 0.26%   |
| LG Electronics         | 2         | 0.26%   |
| Intel                  | 2         | 0.26%   |
| GPD                    | 2         | 0.26%   |
| Fujitsu Siemens        | 2         | 0.26%   |
| Clevo                  | 2         | 0.26%   |
| BANGHO                 | 2         | 0.26%   |
| Alienware              | 2         | 0.26%   |
| WOOKING                | 1         | 0.13%   |
| VIT                    | 1         | 0.13%   |
| Valve                  | 1         | 0.13%   |
| TOXIC by BTO           | 1         | 0.13%   |
| SLIMBOOK               | 1         | 0.13%   |
| Razer                  | 1         | 0.13%   |
| Pegatron               | 1         | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown                              | 6         | 0.79%   |
| Framework Laptop                     | 5         | 0.66%   |
| System76 Lemur Pro                   | 4         | 0.52%   |
| Dell Latitude E7240                  | 4         | 0.52%   |
| Lenovo ThinkPad T490 20N2CTO1WW      | 3         | 0.39%   |
| HUAWEI MACH-WX9                      | 3         | 0.39%   |
| HP EliteBook 8570p                   | 3         | 0.39%   |
| HP EliteBook 840 G3                  | 3         | 0.39%   |
| Dell XPS 13 9360                     | 3         | 0.39%   |
| Dell XPS 13 9343                     | 3         | 0.39%   |
| Dell Precision M4800                 | 3         | 0.39%   |
| Dell Latitude E7450                  | 3         | 0.39%   |
| Dell Latitude E7440                  | 3         | 0.39%   |
| Dell Latitude E6430                  | 3         | 0.39%   |
| Dell Latitude E5470                  | 3         | 0.39%   |
| Dell Latitude E5420                  | 3         | 0.39%   |
| Dell Latitude 7390                   | 3         | 0.39%   |
| Dell Latitude 2100                   | 3         | 0.39%   |
| Dell Inspiron 3521                   | 3         | 0.39%   |
| Dell Inspiron 15 7000 Gaming         | 3         | 0.39%   |
| Toshiba Satellite A300               | 2         | 0.26%   |
| System76 Gazelle                     | 2         | 0.26%   |
| System76 Galago Pro                  | 2         | 0.26%   |
| System76 Bonobo Extreme              | 2         | 0.26%   |
| Samsung NC10                         | 2         | 0.26%   |
| Samsung 340XAA/350XAA/550XAA         | 2         | 0.26%   |
| Lenovo ThinkPad X220 42915CG         | 2         | 0.26%   |
| Lenovo ThinkPad X220 42872WU         | 2         | 0.26%   |
| Lenovo ThinkPad X220 4286CTO         | 2         | 0.26%   |
| Lenovo ThinkPad T60 20076PU          | 2         | 0.26%   |
| Lenovo ThinkPad T410s 291245G        | 2         | 0.26%   |
| Lenovo ThinkPad E490 20N8CTO1WW      | 2         | 0.26%   |
| Lenovo ThinkPad E14 Gen 3 20Y7CTO1WW | 2         | 0.26%   |
| Lenovo Legion Y540-15IRH-PG0 81SY    | 2         | 0.26%   |
| Lenovo IdeaPad 330-15ARR 81D2        | 2         | 0.26%   |
| HP ZBook 17 G2                       | 2         | 0.26%   |
| HP ProBook 440 G6                    | 2         | 0.26%   |
| HP ProBook 430 G2                    | 2         | 0.26%   |
| HP EliteBook 850 G7 Notebook PC      | 2         | 0.26%   |
| HP Compaq 6720s                      | 2         | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 218       | 28.57%  |
| Dell Latitude     | 66        | 8.65%   |
| Dell Inspiron     | 41        | 5.37%   |
| Acer Aspire       | 27        | 3.54%   |
| Lenovo IdeaPad    | 23        | 3.01%   |
| Dell Precision    | 16        | 2.1%    |
| Toshiba Satellite | 13        | 1.7%    |
| HP EliteBook      | 13        | 1.7%    |
| Dell XPS          | 13        | 1.7%    |
| HP ProBook        | 12        | 1.57%   |
| Dell Vostro       | 11        | 1.44%   |
| HP Compaq         | 8         | 1.05%   |
| HP Laptop         | 7         | 0.92%   |
| IBM ThinkPad      | 6         | 0.79%   |
| HP Pavilion       | 6         | 0.79%   |
| Unknown           | 6         | 0.79%   |
| Fujitsu LIFEBOOK  | 5         | 0.66%   |
| Framework Laptop  | 5         | 0.66%   |
| ASUS ZenBook      | 5         | 0.66%   |
| ASUS VivoBook     | 5         | 0.66%   |
| System76 Lemur    | 4         | 0.52%   |
| Lenovo Legion     | 4         | 0.52%   |
| HP ZBook          | 4         | 0.52%   |
| HP ENVY           | 4         | 0.52%   |
| Apple MacBookPro8 | 4         | 0.52%   |
| Lenovo Yoga       | 3         | 0.39%   |
| HUAWEI MACH-WX9   | 3         | 0.39%   |
| Dell Studio       | 3         | 0.39%   |
| Acer TravelMate   | 3         | 0.39%   |
| Acer Swift        | 3         | 0.39%   |
| Acer Extensa      | 3         | 0.39%   |
| TUXEDO Pulse      | 2         | 0.26%   |
| Toshiba TECRA     | 2         | 0.26%   |
| System76 Gazelle  | 2         | 0.26%   |
| System76 Galago   | 2         | 0.26%   |
| System76 Bonobo   | 2         | 0.26%   |
| Samsung NC10      | 2         | 0.26%   |
| Samsung 340XAA    | 2         | 0.26%   |
| HP 255            | 2         | 0.26%   |
| HP 2000           | 2         | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 104       | 13.63%  |
| 2019 | 90        | 11.8%   |
| 2011 | 72        | 9.44%   |
| 2018 | 64        | 8.39%   |
| 2021 | 60        | 7.86%   |
| 2015 | 52        | 6.82%   |
| 2016 | 47        | 6.16%   |
| 2012 | 43        | 5.64%   |
| 2017 | 39        | 5.11%   |
| 2010 | 38        | 4.98%   |
| 2013 | 36        | 4.72%   |
| 2014 | 26        | 3.41%   |
| 2008 | 23        | 3.01%   |
| 2022 | 19        | 2.49%   |
| 2009 | 18        | 2.36%   |
| 2007 | 13        | 1.7%    |
| 2006 | 10        | 1.31%   |
| 2003 | 3         | 0.39%   |
| 2005 | 2         | 0.26%   |
| 2004 | 2         | 0.26%   |
| 2002 | 2         | 0.26%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 763       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 748       | 98.03%  |
| Yes  | 15        | 1.97%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 251       | 32.39%  |
| 16.01-24.0  | 225       | 29.03%  |
| 4.01-8.0    | 129       | 16.65%  |
| 32.01-64.0  | 62        | 8%      |
| 2.01-3.0    | 45        | 5.81%   |
| 3.01-4.0    | 15        | 1.94%   |
| 24.01-32.0  | 14        | 1.81%   |
| 64.01-256.0 | 12        | 1.55%   |
| 0.51-1.0    | 10        | 1.29%   |
| 1.01-2.0    | 8         | 1.03%   |
| 0.01-0.5    | 4         | 0.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 331       | 42.44%  |
| 0.51-1.0   | 261       | 33.46%  |
| 1.01-2.0   | 112       | 14.36%  |
| 2.01-3.0   | 31        | 3.97%   |
| 4.01-8.0   | 17        | 2.18%   |
| 8.01-16.0  | 13        | 1.67%   |
| 3.01-4.0   | 4         | 0.51%   |
| 16.01-24.0 | 4         | 0.51%   |
| 24.01-32.0 | 3         | 0.38%   |
| 32.01-64.0 | 2         | 0.26%   |
| 0          | 2         | 0.26%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 570       | 73.08%  |
| 2      | 163       | 20.9%   |
| 3      | 23        | 2.95%   |
| 0      | 22        | 2.82%   |
| 4      | 2         | 0.26%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 544       | 70.74%  |
| Yes       | 225       | 29.26%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 646       | 84.67%  |
| No        | 117       | 15.33%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 744       | 97.13%  |
| No        | 22        | 2.87%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 520       | 67.27%  |
| No        | 253       | 32.73%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 176       | 22.8%   |
| Germany     | 72        | 9.33%   |
| Russia      | 62        | 8.03%   |
| France      | 44        | 5.7%    |
| UK          | 29        | 3.76%   |
| China       | 26        | 3.37%   |
| Brazil      | 24        | 3.11%   |
| Ukraine     | 22        | 2.85%   |
| Canada      | 21        | 2.72%   |
| Poland      | 20        | 2.59%   |
| Switzerland | 17        | 2.2%    |
| Austria     | 16        | 2.07%   |
| Netherlands | 15        | 1.94%   |
| India       | 15        | 1.94%   |
| Australia   | 15        | 1.94%   |
| Spain       | 11        | 1.42%   |
| Indonesia   | 11        | 1.42%   |
| Czechia     | 11        | 1.42%   |
| Japan       | 10        | 1.3%    |
| Italy       | 9         | 1.17%   |
| Thailand    | 7         | 0.91%   |
| Portugal    | 7         | 0.91%   |
| Argentina   | 7         | 0.91%   |
| Sweden      | 6         | 0.78%   |
| Norway      | 6         | 0.78%   |
| New Zealand | 6         | 0.78%   |
| Finland     | 6         | 0.78%   |
| Denmark     | 6         | 0.78%   |
| Ireland     | 5         | 0.65%   |
| Greece      | 5         | 0.65%   |
| Romania     | 4         | 0.52%   |
| Philippines | 4         | 0.52%   |
| Belgium     | 4         | 0.52%   |
| Vietnam     | 3         | 0.39%   |
| Turkey      | 3         | 0.39%   |
| Slovenia    | 3         | 0.39%   |
| Singapore   | 3         | 0.39%   |
| Mexico      | 3         | 0.39%   |
| Israel      | 3         | 0.39%   |
| Iran        | 3         | 0.39%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Moscow        | 21        | 2.54%   |
| Brooklyn      | 20        | 2.42%   |
| Vienna        | 14        | 1.69%   |
| Kyiv          | 10        | 1.21%   |
| Berlin        | 9         | 1.09%   |
| St Petersburg | 8         | 0.97%   |
| Paris         | 8         | 0.97%   |
| Zurich        | 7         | 0.85%   |
| Warsaw        | 7         | 0.85%   |
| Brighton      | 7         | 0.85%   |
| Jakarta       | 6         | 0.73%   |
| Sydney        | 5         | 0.61%   |
| Seattle       | 5         | 0.61%   |
| London        | 5         | 0.61%   |
| Dublin        | 5         | 0.61%   |
| Chicago       | 5         | 0.61%   |
| Amsterdam     | 5         | 0.61%   |
| Shanghai      | 4         | 0.48%   |
| Christchurch  | 4         | 0.48%   |
| Bucharest     | 4         | 0.48%   |
| Brno          | 4         | 0.48%   |
| Barcelona     | 4         | 0.48%   |
| Wernigerode   | 3         | 0.36%   |
| Vancouver     | 3         | 0.36%   |
| Ulyanovsk     | 3         | 0.36%   |
| Tuklaty       | 3         | 0.36%   |
| Tehran        | 3         | 0.36%   |
| Singapore     | 3         | 0.36%   |
| Shenzhen      | 3         | 0.36%   |
| Portland      | 3         | 0.36%   |
| Perth         | 3         | 0.36%   |
| New York      | 3         | 0.36%   |
| Midvale       | 3         | 0.36%   |
| Manaus        | 3         | 0.36%   |
| Madrid        | 3         | 0.36%   |
| Glasgow       | 3         | 0.36%   |
| Eugene        | 3         | 0.36%   |
| Dallas        | 3         | 0.36%   |
| Chiang Mai    | 3         | 0.36%   |
| Beijing       | 3         | 0.36%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 194       | 268    | 20.97%  |
| WDC                 | 139       | 180    | 15.03%  |
| Seagate             | 74        | 92     | 8%      |
| Toshiba             | 68        | 98     | 7.35%   |
| Crucial             | 56        | 74     | 6.05%   |
| Kingston            | 49        | 69     | 5.3%    |
| SanDisk             | 42        | 53     | 4.54%   |
| Hitachi             | 36        | 43     | 3.89%   |
| Intel               | 32        | 39     | 3.46%   |
| SK hynix            | 29        | 33     | 3.14%   |
| HGST                | 23        | 41     | 2.49%   |
| Transcend           | 21        | 25     | 2.27%   |
| Micron Technology   | 18        | 22     | 1.95%   |
| A-DATA Technology   | 16        | 20     | 1.73%   |
| KIOXIA              | 10        | 10     | 1.08%   |
| Fujitsu             | 10        | 15     | 1.08%   |
| OWC                 | 7         | 8      | 0.76%   |
| Apple               | 7         | 7      | 0.76%   |
| SPCC                | 6         | 8      | 0.65%   |
| Phison              | 6         | 11     | 0.65%   |
| LITEON              | 6         | 10     | 0.65%   |
| KingSpec            | 6         | 6      | 0.65%   |
| PNY                 | 5         | 5      | 0.54%   |
| Hewlett-Packard     | 5         | 5      | 0.54%   |
| Gigabyte Technology | 5         | 7      | 0.54%   |
| Silicon Motion      | 4         | 4      | 0.43%   |
| China               | 4         | 5      | 0.43%   |
| Union Memory        | 3         | 3      | 0.32%   |
| Mushkin             | 3         | 3      | 0.32%   |
| Hikvision           | 3         | 3      | 0.32%   |
| Corsair             | 3         | 3      | 0.32%   |
| BIWIN               | 3         | 4      | 0.32%   |
| Zheino              | 2         | 3      | 0.22%   |
| Team                | 2         | 3      | 0.22%   |
| OCZ                 | 2         | 3      | 0.22%   |
| Lexar               | 2         | 7      | 0.22%   |
| Lenovo              | 2         | 2      | 0.22%   |
| Apacer              | 2         | 2      | 0.22%   |
| ZTC                 | 1         | 1      | 0.11%   |
| Verbatim            | 1         | 1      | 0.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB        | 14        | 1.46%   |
| Seagate ST1000LM035-1RK172 1TB     | 12        | 1.25%   |
| Toshiba MQ01ABD100 1TB             | 11        | 1.14%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 11        | 1.14%   |
| Samsung SSD 860 EVO 500GB          | 11        | 1.14%   |
| HGST HTS721010A9E630 1TB           | 10        | 1.04%   |
| Crucial CT500MX500SSD1 500GB       | 10        | 1.04%   |
| Toshiba MQ01ABF050 500GB           | 9         | 0.94%   |
| Samsung SSD 850 EVO 500GB          | 8         | 0.83%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB | 7         | 0.73%   |
| Samsung SSD 970 EVO Plus 1TB       | 7         | 0.73%   |
| Samsung SSD 970 EVO 500GB          | 7         | 0.73%   |
| Seagate ST500LT012-1DG142 500GB    | 6         | 0.62%   |
| SanDisk SSD PLUS 240GB             | 6         | 0.62%   |
| Samsung SSD 850 EVO 250GB          | 6         | 0.62%   |
| HGST HTS725050A7E630 500GB         | 6         | 0.62%   |
| WDC WDS500G3X0C-00SJG0 500GB       | 5         | 0.52%   |
| Toshiba MQ04ABF100 1TB             | 5         | 0.52%   |
| Seagate ST1000LM048-2E7172 1TB     | 5         | 0.52%   |
| Samsung MZVLB512HBJQ-000L7 512GB   | 5         | 0.52%   |
| Samsung MZVLB512HAJQ-000L7 512GB   | 5         | 0.52%   |
| Intel SSDPEKKF512G8L 512GB         | 5         | 0.52%   |
| Crucial CT2000MX500SSD1 2TB        | 5         | 0.52%   |
| Crucial CT1000P1SSD8 1TB           | 5         | 0.52%   |
| WDC WD1600BEVT-22ZCT0 160GB        | 4         | 0.42%   |
| WDC WD10JPVX-22JC3T0 1TB           | 4         | 0.42%   |
| Seagate ST9500420AS 500GB          | 4         | 0.42%   |
| Seagate ST9500325AS 500GB          | 4         | 0.42%   |
| Samsung SSD 970 EVO Plus 2TB       | 4         | 0.42%   |
| Samsung SSD 850 EVO 1TB            | 4         | 0.42%   |
| Samsung MZVLW256HEHP-000L7 256GB   | 4         | 0.42%   |
| Samsung MZALQ512HBLU-00BL1 512GB   | 4         | 0.42%   |
| Samsung MZ7TY256HDHP-000L7 256GB   | 4         | 0.42%   |
| Phison PCIe SSD 1TB                | 4         | 0.42%   |
| KIOXIA KBG40ZNS512G NVMe 512GB     | 4         | 0.42%   |
| Crucial CT250MX500SSD1 250GB       | 4         | 0.42%   |
| Crucial CT1000MX500SSD1 1TB        | 4         | 0.42%   |
| WDC WDS500G2B0C-00PXH0 500GB       | 3         | 0.31%   |
| WDC WDS240G2G0A-00JH30 240GB       | 3         | 0.31%   |
| WDC WD10SPZX-24Z10 1TB             | 3         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 79        | 94     | 28.62%  |
| Seagate             | 74        | 92     | 26.81%  |
| Toshiba             | 46        | 64     | 16.67%  |
| Hitachi             | 36        | 43     | 13.04%  |
| HGST                | 23        | 41     | 8.33%   |
| Fujitsu             | 10        | 15     | 3.62%   |
| Samsung Electronics | 7         | 7      | 2.54%   |
| IBM/Hitachi         | 1         | 1      | 0.36%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 99        | 141    | 25.06%  |
| Crucial             | 46        | 61     | 11.65%  |
| SanDisk             | 42        | 53     | 10.63%  |
| Kingston            | 39        | 58     | 9.87%   |
| WDC                 | 21        | 34     | 5.32%   |
| Transcend           | 18        | 21     | 4.56%   |
| Intel               | 17        | 21     | 4.3%    |
| Toshiba             | 9         | 9      | 2.28%   |
| SK hynix            | 9         | 10     | 2.28%   |
| Micron Technology   | 9         | 10     | 2.28%   |
| A-DATA Technology   | 8         | 11     | 2.03%   |
| OWC                 | 7         | 8      | 1.77%   |
| Apple               | 7         | 7      | 1.77%   |
| KingSpec            | 6         | 6      | 1.52%   |
| LITEON              | 5         | 9      | 1.27%   |
| Hewlett-Packard     | 5         | 5      | 1.27%   |
| SPCC                | 4         | 5      | 1.01%   |
| Gigabyte Technology | 4         | 5      | 1.01%   |
| China               | 4         | 5      | 1.01%   |
| PNY                 | 3         | 3      | 0.76%   |
| Corsair             | 3         | 3      | 0.76%   |
| Zheino              | 2         | 3      | 0.51%   |
| Team                | 2         | 3      | 0.51%   |
| OCZ                 | 2         | 3      | 0.51%   |
| Mushkin             | 2         | 2      | 0.51%   |
| Lexar               | 2         | 7      | 0.51%   |
| BIWIN               | 2         | 3      | 0.51%   |
| Apacer              | 2         | 2      | 0.51%   |
| ZTC                 | 1         | 1      | 0.25%   |
| Verbatim            | 1         | 1      | 0.25%   |
| TCSUNBOW            | 1         | 1      | 0.25%   |
| SSSTC               | 1         | 1      | 0.25%   |
| SMI                 | 1         | 1      | 0.25%   |
| Phison              | 1         | 1      | 0.25%   |
| Patriot             | 1         | 1      | 0.25%   |
| MicroDream          | 1         | 1      | 0.25%   |
| LITEONIT            | 1         | 1      | 0.25%   |
| Lenovo              | 1         | 1      | 0.25%   |
| KLLISRE             | 1         | 1      | 0.25%   |
| Intenso             | 1         | 1      | 0.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 356       | 524    | 41.64%  |
| HDD  | 258       | 357    | 30.18%  |
| NVMe | 241       | 333    | 28.19%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 564       | 881    | 70.06%  |
| NVMe | 241       | 333    | 29.94%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 434       | 633    | 70.45%  |
| 0.51-1.0   | 147       | 202    | 23.86%  |
| 1.01-2.0   | 32        | 41     | 5.19%   |
| 3.01-4.0   | 1         | 2      | 0.16%   |
| 2.01-3.0   | 1         | 2      | 0.16%   |
| 4.01-10.0  | 1         | 1      | 0.16%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 287       | 36.1%   |
| 251-500        | 220       | 27.67%  |
| 501-1000       | 113       | 14.21%  |
| 51-100         | 78        | 9.81%   |
| 21-50          | 49        | 6.16%   |
| 1001-2000      | 21        | 2.64%   |
| 1-20           | 21        | 2.64%   |
| Unknown        | 3         | 0.38%   |
| 2001-3000      | 2         | 0.25%   |
| More than 3000 | 1         | 0.13%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 571       | 71.38%  |
| 21-50          | 126       | 15.75%  |
| 51-100         | 43        | 5.38%   |
| 101-250        | 39        | 4.88%   |
| 251-500        | 10        | 1.25%   |
| 501-1000       | 7         | 0.88%   |
| Unknown        | 3         | 0.38%   |
| More than 3000 | 1         | 0.13%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB    | 6         | 6      | 4.51%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 4         | 5      | 3.01%   |
| HGST HTS725050A7E630 500GB         | 4         | 8      | 3.01%   |
| Toshiba MQ01ABF050 500GB           | 3         | 3      | 2.26%   |
| Toshiba MQ01ABD100 1TB             | 3         | 3      | 2.26%   |
| Seagate ST9500420AS 500GB          | 3         | 4      | 2.26%   |
| Seagate ST500LT012-9WS142 500GB    | 3         | 6      | 2.26%   |
| WDC WD3200BPVT-80JJ5T0 320GB       | 2         | 2      | 1.5%    |
| Toshiba MK2546GSX 250GB            | 2         | 2      | 1.5%    |
| Seagate ST320LT007-9ZV142 320GB    | 2         | 2      | 1.5%    |
| Seagate ST1000LM035-1RK172 1TB     | 2         | 2      | 1.5%    |
| Micron Technology 1100 SATA 256GB  | 2         | 2      | 1.5%    |
| Intel SSDSCKKF256G8H 256GB         | 2         | 5      | 1.5%    |
| Hitachi HTS547550A9E384 500GB      | 2         | 2      | 1.5%    |
| Hitachi HTS545032B9A300 320GB      | 2         | 3      | 1.5%    |
| Hitachi HTS541612J9SA00 120GB      | 2         | 2      | 1.5%    |
| HGST HTS721010A9E630 1TB           | 2         | 10     | 1.5%    |
| WDC WD7500BPVT-80HXZT3 752GB       | 1         | 1      | 0.75%   |
| WDC WD7500BPKT-75PK4T0 752GB       | 1         | 1      | 0.75%   |
| WDC WD6400BEVT-22A0RT0 640GB       | 1         | 1      | 0.75%   |
| WDC WD5000BEVT-75A0RT0 500GB       | 1         | 1      | 0.75%   |
| WDC WD5000B 500GB                  | 1         | 1      | 0.75%   |
| WDC WD3200BPVT-75ZEST0 320GB       | 1         | 1      | 0.75%   |
| WDC WD3200BPVT-75JJ5T0 320GB       | 1         | 1      | 0.75%   |
| WDC WD3200BEKT-60PVMT0 320GB       | 1         | 1      | 0.75%   |
| WDC WD2500BEVT-24A23T0 250GB       | 1         | 1      | 0.75%   |
| WDC WD2000JB-00GVC0 200GB          | 1         | 1      | 0.75%   |
| WDC WD15EARS-00Z5B1 1.5TB          | 1         | 1      | 0.75%   |
| WDC WD10SPZX-60Z10T0 1TB           | 1         | 1      | 0.75%   |
| WDC WD10JPVX-60JC3T1 1TB           | 1         | 1      | 0.75%   |
| WDC WD10JPVX-60JC3T0 1TB           | 1         | 1      | 0.75%   |
| Transcend TS256GSSD320 256GB       | 1         | 1      | 0.75%   |
| Toshiba MQ04ABF100 1TB             | 1         | 1      | 0.75%   |
| Toshiba MQ01ABF032 320GB           | 1         | 1      | 0.75%   |
| Toshiba MQ01ABD075 752GB           | 1         | 1      | 0.75%   |
| Toshiba MQ01ABD032 320GB           | 1         | 2      | 0.75%   |
| Toshiba MK6475GSX 640GB            | 1         | 1      | 0.75%   |
| Toshiba MK3265GSXN 320GB           | 1         | 5      | 0.75%   |
| Toshiba MK3261GSYN 320GB           | 1         | 1      | 0.75%   |
| Toshiba MK2018GAP 20GB             | 1         | 1      | 0.75%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 30        | 40     | 23.44%  |
| Hitachi             | 18        | 21     | 14.06%  |
| Toshiba             | 17        | 23     | 13.28%  |
| WDC                 | 15        | 16     | 11.72%  |
| Samsung Electronics | 10        | 11     | 7.81%   |
| Kingston            | 7         | 8      | 5.47%   |
| HGST                | 6         | 19     | 4.69%   |
| Intel               | 5         | 8      | 3.91%   |
| SanDisk             | 3         | 3      | 2.34%   |
| Micron Technology   | 3         | 3      | 2.34%   |
| Crucial             | 3         | 3      | 2.34%   |
| SK hynix            | 2         | 2      | 1.56%   |
| Fujitsu             | 2         | 5      | 1.56%   |
| Transcend           | 1         | 1      | 0.78%   |
| SSSTC               | 1         | 1      | 0.78%   |
| SMI                 | 1         | 1      | 0.78%   |
| IBM/Hitachi         | 1         | 1      | 0.78%   |
| Hewlett-Packard     | 1         | 1      | 0.78%   |
| Apple               | 1         | 1      | 0.78%   |
| A-DATA Technology   | 1         | 2      | 0.78%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 30        | 40     | 32.61%  |
| Hitachi             | 18        | 21     | 19.57%  |
| Toshiba             | 17        | 23     | 18.48%  |
| WDC                 | 15        | 16     | 16.3%   |
| HGST                | 6         | 19     | 6.52%   |
| Samsung Electronics | 3         | 3      | 3.26%   |
| Fujitsu             | 2         | 5      | 2.17%   |
| IBM/Hitachi         | 1         | 1      | 1.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 88        | 128    | 70.97%  |
| SSD  | 33        | 39     | 26.61%  |
| NVMe | 3         | 3      | 2.42%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| SanDisk pSSD 256GB                | 1         | 1      | 50%     |
| Samsung Electronics HM250JI 250GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 1         | 1      | 50%     |
| Samsung Electronics | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 653       | 1033   | 82.97%  |
| Malfunc  | 124       | 170    | 15.76%  |
| Detected | 8         | 9      | 1.02%   |
| Failed   | 2         | 2      | 0.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 558       | 62.91%  |
| Samsung Electronics              | 99        | 11.16%  |
| AMD                              | 70        | 7.89%   |
| SanDisk                          | 39        | 4.4%    |
| SK hynix                         | 20        | 2.25%   |
| Toshiba                          | 15        | 1.69%   |
| Silicon Motion                   | 10        | 1.13%   |
| Micron Technology                | 10        | 1.13%   |
| Phison Electronics               | 9         | 1.01%   |
| KIOXIA                           | 9         | 1.01%   |
| Kingston Technology Company      | 9         | 1.01%   |
| Micron/Crucial Technology        | 8         | 0.9%    |
| ADATA Technology                 | 6         | 0.68%   |
| Union Memory (Shenzhen)          | 4         | 0.45%   |
| Nvidia                           | 4         | 0.45%   |
| Silicon Integrated Systems [SiS] | 3         | 0.34%   |
| Realtek Semiconductor            | 2         | 0.23%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.23%   |
| JMicron Technology               | 2         | 0.23%   |
| Unknown                          | 2         | 0.23%   |
| ULi Electronics                  | 1         | 0.11%   |
| Solid State Storage Technology   | 1         | 0.11%   |
| Shenzhen Longsys Electronics     | 1         | 0.11%   |
| Lite-On Technology               | 1         | 0.11%   |
| Lenovo                           | 1         | 0.11%   |
| Apple                            | 1         | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 72        | 7.6%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 68        | 7.18%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 60        | 6.34%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 59        | 6.23%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 56        | 5.91%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 40        | 4.22%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 29        | 3.06%   |
| Unknown                                                                          | 28        | 2.96%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 25        | 2.64%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 24        | 2.53%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 23        | 2.43%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 23        | 2.43%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 21        | 2.22%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 20        | 2.11%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 19        | 2.01%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 16        | 1.69%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 15        | 1.58%   |
| Intel Comet Lake SATA AHCI Controller                                            | 15        | 1.58%   |
| Samsung NVMe SSD Controller 980                                                  | 14        | 1.48%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 14        | 1.48%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 13        | 1.37%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 13        | 1.37%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 12        | 1.27%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 10        | 1.06%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 10        | 1.06%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 10        | 1.06%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 10        | 1.06%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 9         | 0.95%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 9         | 0.95%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 9         | 0.95%   |
| Phison E12 NVMe Controller                                                       | 8         | 0.84%   |
| SK hynix BC511                                                                   | 7         | 0.74%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 7         | 0.74%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 6         | 0.63%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 6         | 0.63%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 6         | 0.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 6         | 0.63%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 6         | 0.63%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 6         | 0.63%   |
| SK hynix Gold P31 SSD                                                            | 5         | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 555       | 61.19%  |
| NVMe | 241       | 26.57%  |
| IDE  | 81        | 8.93%   |
| RAID | 30        | 3.31%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 665       | 86.93%  |
| AMD    | 99        | 12.94%  |
| ARM    | 1         | 0.13%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz       | 20        | 2.6%    |
| Intel Core i7-8550U CPU @ 1.80GHz       | 17        | 2.21%   |
| Intel CPU Version                       | 16        | 2.08%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 15        | 1.95%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 13        | 1.69%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 13        | 1.69%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 13        | 1.69%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 12        | 1.56%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 11        | 1.43%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 10        | 1.3%    |
| Intel Core i5-8250U CPU @ 1.60GHz       | 10        | 1.3%    |
| Intel Core i5-5200U CPU @ 2.20GHz       | 10        | 1.3%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 10        | 1.3%    |
| Intel Core i7-7500U CPU @ 2.70GHz       | 9         | 1.17%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 9         | 1.17%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 8         | 1.04%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 8         | 1.04%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 8         | 1.04%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 7         | 0.91%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 7         | 0.91%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 7         | 0.91%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 7         | 0.91%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 7         | 0.91%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 7         | 0.91%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 7         | 0.91%   |
| Intel Pentium M processor               | 6         | 0.78%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 6         | 0.78%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 6         | 0.78%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 6         | 0.78%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 6         | 0.78%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 6         | 0.78%   |
| Intel Core i5-2540M CPU @ 2.60GHz       | 6         | 0.78%   |
| Intel Core 2 Duo                        | 6         | 0.78%   |
| Intel Atom CPU N270 @ 1.60GHz           | 6         | 0.78%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 6         | 0.78%   |
| Intel Core i7-8665U CPU @ 1.90GHz       | 5         | 0.65%   |
| Intel Core i7-7600U CPU @ 2.80GHz       | 5         | 0.65%   |
| Intel Core i7-2760QM CPU @ 2.40GHz      | 5         | 0.65%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz      | 5         | 0.65%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 5         | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 235       | 30.64%  |
| Intel Core i7           | 214       | 27.9%   |
| Other                   | 54        | 7.04%   |
| Intel Core i3           | 38        | 4.95%   |
| Intel Core 2 Duo        | 36        | 4.69%   |
| AMD Ryzen 7             | 25        | 3.26%   |
| Intel Celeron           | 22        | 2.87%   |
| AMD Ryzen 5             | 19        | 2.48%   |
| Intel Atom              | 15        | 1.96%   |
| Intel Pentium M         | 11        | 1.43%   |
| Intel Pentium           | 10        | 1.3%    |
| AMD Ryzen 7 PRO         | 10        | 1.3%    |
| Intel Core 2            | 6         | 0.78%   |
| AMD Ryzen 3             | 6         | 0.78%   |
| AMD E                   | 6         | 0.78%   |
| Intel Pentium Dual      | 5         | 0.65%   |
| AMD Ryzen 5 PRO         | 5         | 0.65%   |
| Intel Pentium Silver    | 4         | 0.52%   |
| Intel Genuine           | 4         | 0.52%   |
| Intel Pentium 4         | 3         | 0.39%   |
| AMD E2                  | 3         | 0.39%   |
| AMD A8                  | 3         | 0.39%   |
| AMD A6                  | 3         | 0.39%   |
| Intel Xeon              | 2         | 0.26%   |
| Intel Core m3           | 2         | 0.26%   |
| Intel Core i9           | 2         | 0.26%   |
| Intel Celeron M         | 2         | 0.26%   |
| AMD Ryzen 9             | 2         | 0.26%   |
| AMD EPYC                | 2         | 0.26%   |
| AMD C-50                | 2         | 0.26%   |
| AMD A4                  | 2         | 0.26%   |
| Intel Mobile Pentium 4  | 1         | 0.13%   |
| Intel Core Solo         | 1         | 0.13%   |
| Intel Core m7           | 1         | 0.13%   |
| Intel Core M            | 1         | 0.13%   |
| Intel Core Duo          | 1         | 0.13%   |
| Intel Core 2 Extreme    | 1         | 0.13%   |
| Intel Celeron Dual-Core | 1         | 0.13%   |
| ARM Cortex              | 1         | 0.13%   |
| AMD Sempron             | 1         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 346       | 45.11%  |
| 4       | 231       | 30.12%  |
| Unknown | 53        | 6.91%   |
| 8       | 38        | 4.95%   |
| 1       | 33        | 4.3%    |
| 6       | 32        | 4.17%   |
| 16      | 24        | 3.13%   |
| 12      | 8         | 1.04%   |
| 24      | 1         | 0.13%   |
| 20      | 1         | 0.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 757       | 99.08%  |
| 2       | 6         | 0.79%   |
| Unknown | 1         | 0.13%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 534       | 69.71%  |
| 1       | 163       | 21.28%  |
| Unknown | 69        | 9.01%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 170       | 22.22%  |
| SandyBridge     | 77        | 10.07%  |
| IvyBridge       | 62        | 8.1%    |
| Haswell         | 54        | 7.06%   |
| Skylake         | 53        | 6.93%   |
| Broadwell       | 43        | 5.62%   |
| Core            | 31        | 4.05%   |
| Penryn          | 28        | 3.66%   |
| Westmere        | 27        | 3.53%   |
| Bonnell         | 27        | 3.53%   |
| Zen 2           | 23        | 3.01%   |
| TigerLake       | 21        | 2.75%   |
| Zen+            | 20        | 2.61%   |
| Unknown         | 20        | 2.61%   |
| CometLake       | 15        | 1.96%   |
| Silvermont      | 14        | 1.83%   |
| P6              | 14        | 1.83%   |
| Zen             | 10        | 1.31%   |
| Bobcat          | 8         | 1.05%   |
| IceLake         | 7         | 0.92%   |
| Zen 3           | 6         | 0.78%   |
| Puma            | 6         | 0.78%   |
| Goldmont plus   | 6         | 0.78%   |
| Excavator       | 6         | 0.78%   |
| NetBurst        | 4         | 0.52%   |
| Goldmont        | 3         | 0.39%   |
| Nehalem         | 2         | 0.26%   |
| K8 Hammer       | 2         | 0.26%   |
| K8 & K10 hybrid | 2         | 0.26%   |
| Piledriver      | 1         | 0.13%   |
| K10 Llano       | 1         | 0.13%   |
| K10             | 1         | 0.13%   |
| Jaguar          | 1         | 0.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 601       | 65.9%   |
| Nvidia                           | 170       | 18.64%  |
| AMD                              | 139       | 15.24%  |
| Silicon Integrated Systems [SiS] | 2         | 0.22%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 68        | 7.08%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 57        | 5.94%   |
| Intel HD Graphics 5500                                                                   | 39        | 4.06%   |
| Intel UHD Graphics 620                                                                   | 37        | 3.85%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 37        | 3.85%   |
| Intel HD Graphics 620                                                                    | 34        | 3.54%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 29        | 3.02%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 28        | 2.92%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 26        | 2.71%   |
| Intel Core Processor Integrated Graphics Controller                                      | 22        | 2.29%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 22        | 2.29%   |
| AMD Renoir                                                                               | 22        | 2.29%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 21        | 2.19%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 21        | 2.19%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 20        | 2.08%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 18        | 1.88%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 17        | 1.77%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 17        | 1.77%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 17        | 1.77%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 14        | 1.46%   |
| Intel HD Graphics 630                                                                    | 12        | 1.25%   |
| Intel HD Graphics 530                                                                    | 12        | 1.25%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 12        | 1.25%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 12        | 1.25%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 10        | 1.04%   |
| AMD Lucienne                                                                             | 10        | 1.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9         | 0.94%   |
| Nvidia TU117M                                                                            | 8         | 0.83%   |
| Nvidia GP108M [GeForce MX150]                                                            | 7         | 0.73%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 7         | 0.73%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 7         | 0.73%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 7         | 0.73%   |
| Intel Iris Plus Graphics G7                                                              | 6         | 0.63%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 5         | 0.52%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 5         | 0.52%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 5         | 0.52%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 5         | 0.52%   |
| Nvidia GM108M [GeForce MX130]                                                            | 5         | 0.52%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 5         | 0.52%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 390       | 50.72%  |
| Intel + Nvidia | 119       | 15.47%  |
| 1 x AMD        | 104       | 13.52%  |
| 2 x Intel      | 73        | 9.49%   |
| 1 x Nvidia     | 41        | 5.33%   |
| Intel + AMD    | 18        | 2.34%   |
| AMD + Nvidia   | 10        | 1.3%    |
| 2 x AMD        | 7         | 0.91%   |
| Other          | 3         | 0.39%   |
| 2 x Nvidia     | 2         | 0.26%   |
| 1 x SiS        | 2         | 0.26%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 684       | 88.83%  |
| Proprietary | 78        | 10.13%  |
| Unknown     | 8         | 1.04%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 646       | 83.46%  |
| 0.01-0.5   | 47        | 6.07%   |
| 1.01-2.0   | 37        | 4.78%   |
| 0.51-1.0   | 19        | 2.45%   |
| 3.01-4.0   | 15        | 1.94%   |
| 7.01-8.0   | 5         | 0.65%   |
| 2.01-3.0   | 3         | 0.39%   |
| 5.01-6.0   | 2         | 0.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 136       | 20.45%  |
| LG Display              | 122       | 18.35%  |
| Chimei Innolux          | 66        | 9.92%   |
| BOE                     | 66        | 9.92%   |
| Samsung Electronics     | 52        | 7.82%   |
| Lenovo                  | 35        | 5.26%   |
| Sharp                   | 22        | 3.31%   |
| Dell                    | 16        | 2.41%   |
| Apple                   | 12        | 1.8%    |
| Hewlett-Packard         | 10        | 1.5%    |
| Chi Mei Optoelectronics | 10        | 1.5%    |
| AOC                     | 9         | 1.35%   |
| InfoVision              | 8         | 1.2%    |
| Goldstar                | 8         | 1.2%    |
| Philips                 | 7         | 1.05%   |
| PANDA                   | 6         | 0.9%    |
| LGD                     | 6         | 0.9%    |
| LG Philips              | 5         | 0.75%   |
| JDI                     | 5         | 0.75%   |
| Acer                    | 5         | 0.75%   |
| Sceptre Tech            | 4         | 0.6%    |
| Iiyama                  | 4         | 0.6%    |
| CSO                     | 4         | 0.6%    |
| CPT                     | 4         | 0.6%    |
| BenQ                    | 4         | 0.6%    |
| Ancor Communications    | 4         | 0.6%    |
| ViewSonic               | 3         | 0.45%   |
| Toshiba                 | 3         | 0.45%   |
| HannStar                | 3         | 0.45%   |
| Vizio                   | 2         | 0.3%    |
| Unknown                 | 2         | 0.3%    |
| Panasonic               | 2         | 0.3%    |
| Eizo                    | 2         | 0.3%    |
| ASUSTek Computer        | 2         | 0.3%    |
| YTH                     | 1         | 0.15%   |
| USR                     | 1         | 0.15%   |
| Unknown (XXX)           | 1         | 0.15%   |
| SDC                     | 1         | 0.15%   |
| Nvidia                  | 1         | 0.15%   |
| NEC Computers           | 1         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch        | 10        | 1.49%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch          | 6         | 0.9%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch     | 5         | 0.75%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch     | 5         | 0.75%   |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                | 5         | 0.75%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch        | 5         | 0.75%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch | 4         | 0.6%    |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch         | 4         | 0.6%    |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch         | 4         | 0.6%    |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch             | 4         | 0.6%    |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch              | 4         | 0.6%    |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch              | 4         | 0.6%    |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 310x170mm 13.9-inch     | 4         | 0.6%    |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 280x160mm 12.7-inch     | 4         | 0.6%    |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch        | 4         | 0.6%    |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch       | 4         | 0.6%    |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch       | 4         | 0.6%    |
| Sharp LCD Monitor SHP1449 1920x1080 290x170mm 13.2-inch              | 3         | 0.45%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch       | 3         | 0.45%   |
| Philips LCD Monitor PHL08C3 1920x1080 600x340mm 27.2-inch            | 3         | 0.45%   |
| LGD LCD Monitor 1920x1080                                            | 3         | 0.45%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch         | 3         | 0.45%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch          | 3         | 0.45%   |
| LG Display LCD Monitor LGD03AB 1366x768 340x190mm 15.3-inch          | 3         | 0.45%   |
| LG Display LCD Monitor LGD0362 1600x900 310x170mm 13.9-inch          | 3         | 0.45%   |
| LG Display LCD Monitor LGD0353 1366x768 350x190mm 15.7-inch          | 3         | 0.45%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch          | 3         | 0.45%   |
| LG Display LCD Monitor LGD02D3 1366x768 280x160mm 12.7-inch          | 3         | 0.45%   |
| LG Display LCD Monitor LGD0258 1600x900 350x190mm 15.7-inch          | 3         | 0.45%   |
| Lenovo LCD Monitor LEN40B1 1600x900 350x190mm 15.7-inch              | 3         | 0.45%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x170mm 12.2-inch              | 3         | 0.45%   |
| JDI LCD Monitor JDI422A 3000x2000 290x200mm 13.9-inch                | 3         | 0.45%   |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch         | 3         | 0.45%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch           | 3         | 0.45%   |
| Dell U2414H DELA0A2 1920x1080 530x300mm 24.0-inch                    | 3         | 0.45%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 310x170mm 13.9-inch     | 3         | 0.45%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch      | 3         | 0.45%   |
| BOE LCD Monitor BOE0742 1920x1080 310x170mm 13.9-inch                | 3         | 0.45%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 340x190mm 15.3-inch       | 3         | 0.45%   |
| AU Optronics LCD Monitor AUO462D 1920x1080 290x170mm 13.2-inch       | 3         | 0.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 270       | 42.06%  |
| 1366x768 (WXGA)    | 157       | 24.45%  |
| 1600x900 (HD+)     | 41        | 6.39%   |
| 1280x800 (WXGA)    | 33        | 5.14%   |
| 3840x2160 (4K)     | 29        | 4.52%   |
| 2560x1440 (QHD)    | 21        | 3.27%   |
| 1024x600           | 14        | 2.18%   |
| 1920x1200 (WUXGA)  | 12        | 1.87%   |
| 1440x900 (WXGA+)   | 10        | 1.56%   |
| 2560x1080          | 7         | 1.09%   |
| 2256x1504          | 6         | 0.93%   |
| 3440x1440          | 4         | 0.62%   |
| 3200x1800 (QHD+)   | 4         | 0.62%   |
| 2560x1600          | 4         | 0.62%   |
| 1280x1024 (SXGA)   | 4         | 0.62%   |
| 3000x2000          | 3         | 0.47%   |
| 1680x1050 (WSXGA+) | 3         | 0.47%   |
| 2880x1800          | 2         | 0.31%   |
| 2880x1620          | 2         | 0.31%   |
| 2160x1440          | 2         | 0.31%   |
| 1920x540           | 2         | 0.31%   |
| 1400x1050          | 2         | 0.31%   |
| 1024x768 (XGA)     | 2         | 0.31%   |
| Unknown            | 2         | 0.31%   |
| 4480x1080          | 1         | 0.16%   |
| 3840x1200          | 1         | 0.16%   |
| 3520x1080          | 1         | 0.16%   |
| 2240x1400          | 1         | 0.16%   |
| 1360x768           | 1         | 0.16%   |
| 1280x720 (HD)      | 1         | 0.16%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 13      | 213       | 32.22%  |
| 15      | 195       | 29.5%   |
| 12      | 58        | 8.77%   |
| 17      | 26        | 3.93%   |
| 24      | 25        | 3.78%   |
| 14      | 21        | 3.18%   |
| 27      | 20        | 3.03%   |
| Unknown | 19        | 2.87%   |
| 23      | 15        | 2.27%   |
| 11      | 11        | 1.66%   |
| 10      | 11        | 1.66%   |
| 34      | 7         | 1.06%   |
| 21      | 6         | 0.91%   |
| 19      | 6         | 0.91%   |
| 31      | 4         | 0.61%   |
| 29      | 3         | 0.45%   |
| 18      | 3         | 0.45%   |
| 9       | 3         | 0.45%   |
| 64      | 2         | 0.3%    |
| 22      | 2         | 0.3%    |
| 49      | 1         | 0.15%   |
| 48      | 1         | 0.15%   |
| 43      | 1         | 0.15%   |
| 42      | 1         | 0.15%   |
| 39      | 1         | 0.15%   |
| 35      | 1         | 0.15%   |
| 33      | 1         | 0.15%   |
| 32      | 1         | 0.15%   |
| 26      | 1         | 0.15%   |
| 20      | 1         | 0.15%   |
| 8       | 1         | 0.15%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 352       | 53.5%   |
| 201-300     | 160       | 24.32%  |
| 501-600     | 54        | 8.21%   |
| 351-400     | 28        | 4.26%   |
| Unknown     | 19        | 2.89%   |
| 401-500     | 15        | 2.28%   |
| 601-700     | 11        | 1.67%   |
| 701-800     | 9         | 1.37%   |
| 1001-1500   | 5         | 0.76%   |
| 801-900     | 2         | 0.3%    |
| 101-200     | 2         | 0.3%    |
| 901-1000    | 1         | 0.15%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 481       | 80.17%  |
| 16/10   | 65        | 10.83%  |
| Unknown | 17        | 2.83%   |
| 21/9    | 11        | 1.83%   |
| 3/2     | 10        | 1.67%   |
| 4/3     | 8         | 1.33%   |
| 5/4     | 4         | 0.67%   |
| 6/5     | 1         | 0.17%   |
| 3.18    | 1         | 0.17%   |
| 11/10   | 1         | 0.17%   |
| 1.96    | 1         | 0.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 193       | 29.11%  |
| 91-100         | 152       | 22.93%  |
| 61-70          | 58        | 8.75%   |
| 101-110        | 48        | 7.24%   |
| 201-250        | 42        | 6.33%   |
| 71-80          | 35        | 5.28%   |
| 301-350        | 23        | 3.47%   |
| 121-130        | 23        | 3.47%   |
| Unknown        | 19        | 2.87%   |
| 351-500        | 14        | 2.11%   |
| 41-50          | 13        | 1.96%   |
| 51-60          | 11        | 1.66%   |
| 251-300        | 8         | 1.21%   |
| 151-200        | 7         | 1.06%   |
| 141-150        | 4         | 0.6%    |
| 501-1000       | 4         | 0.6%    |
| More than 1000 | 3         | 0.45%   |
| 131-140        | 3         | 0.45%   |
| 1-40           | 2         | 0.3%    |
| 111-120        | 1         | 0.15%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 283       | 43.47%  |
| 101-120       | 155       | 23.81%  |
| 51-100        | 97        | 14.9%   |
| 161-240       | 73        | 11.21%  |
| More than 240 | 22        | 3.38%   |
| Unknown       | 19        | 2.92%   |
| 1-50          | 2         | 0.31%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 509       | 64.76%  |
| 0     | 189       | 24.05%  |
| 2     | 82        | 10.43%  |
| 3     | 5         | 0.64%   |
| 4     | 1         | 0.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 535       | 44.32%  |
| Realtek Semiconductor             | 301       | 24.94%  |
| Qualcomm Atheros                  | 150       | 12.43%  |
| Broadcom                          | 81        | 6.71%   |
| Marvell Technology Group          | 16        | 1.33%   |
| Ralink Technology                 | 15        | 1.24%   |
| TP-Link                           | 13        | 1.08%   |
| Edimax Technology                 | 11        | 0.91%   |
| Samsung Electronics               | 6         | 0.5%    |
| MediaTek                          | 6         | 0.5%    |
| Hewlett-Packard                   | 6         | 0.5%    |
| Ericsson Business Mobile Networks | 6         | 0.5%    |
| Xiaomi                            | 5         | 0.41%   |
| Sierra Wireless                   | 5         | 0.41%   |
| Ralink                            | 4         | 0.33%   |
| Nvidia                            | 4         | 0.33%   |
| Google                            | 4         | 0.33%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.25%   |
| Dell                              | 3         | 0.25%   |
| D-Link System                     | 3         | 0.25%   |
| D-Link                            | 3         | 0.25%   |
| AMD                               | 3         | 0.25%   |
| Qualcomm                          | 2         | 0.17%   |
| NetGear                           | 2         | 0.17%   |
| Lenovo                            | 2         | 0.17%   |
| JMicron Technology                | 2         | 0.17%   |
| Huawei Technologies               | 2         | 0.17%   |
| Van Ooijen Technische Informatica | 1         | 0.08%   |
| ULi Electronics                   | 1         | 0.08%   |
| Sagem                             | 1         | 0.08%   |
| Realtek                           | 1         | 0.08%   |
| OPPO Electronics                  | 1         | 0.08%   |
| OpenMoko                          | 1         | 0.08%   |
| National Semiconductor            | 1         | 0.08%   |
| HMD Global                        | 1         | 0.08%   |
| Fibocom                           | 1         | 0.08%   |
| dog hunter                        | 1         | 0.08%   |
| BUFFALO                           | 1         | 0.08%   |
| Atheros                           | 1         | 0.08%   |
| Arduino SA                        | 1         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 189       | 12.26%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 73        | 4.74%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 67        | 4.35%   |
| Intel Wireless 8265 / 8275                                              | 64        | 4.15%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 53        | 3.44%   |
| Intel Wireless 8260                                                     | 37        | 2.4%    |
| Intel Wireless 7265                                                     | 31        | 2.01%   |
| Intel Wireless 7260                                                     | 31        | 2.01%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 30        | 1.95%   |
| Intel Wi-Fi 6 AX200                                                     | 30        | 1.95%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 24        | 1.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 23        | 1.49%   |
| Intel Wireless-AC 9260                                                  | 22        | 1.43%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 19        | 1.23%   |
| Intel Ethernet Connection I219-LM                                       | 19        | 1.23%   |
| Intel Ethernet Connection (4) I219-LM                                   | 19        | 1.23%   |
| Intel Ethernet Connection (3) I218-LM                                   | 19        | 1.23%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 18        | 1.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 17        | 1.1%    |
| Intel Ethernet Connection (4) I219-V                                    | 16        | 1.04%   |
| Intel Centrino Ultimate-N 6300                                          | 16        | 1.04%   |
| Intel Wireless 3165                                                     | 15        | 0.97%   |
| Intel Ethernet Connection I217-LM                                       | 15        | 0.97%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 14        | 0.91%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 14        | 0.91%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 13        | 0.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 12        | 0.78%   |
| Intel Wi-Fi 6 AX201                                                     | 12        | 0.78%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 12        | 0.78%   |
| Intel Ethernet Connection I218-LM                                       | 12        | 0.78%   |
| Intel 82577LM Gigabit Network Connection                                | 12        | 0.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 11        | 0.71%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 10        | 0.65%   |
| Intel Wireless 3160                                                     | 10        | 0.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 10        | 0.65%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 10        | 0.65%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 9         | 0.58%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 9         | 0.58%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 9         | 0.58%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 9         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 499       | 60.12%  |
| Qualcomm Atheros      | 131       | 15.78%  |
| Realtek Semiconductor | 74        | 8.92%   |
| Broadcom              | 60        | 7.23%   |
| Ralink Technology     | 15        | 1.81%   |
| TP-Link               | 13        | 1.57%   |
| Edimax Technology     | 11        | 1.33%   |
| MediaTek              | 5         | 0.6%    |
| Sierra Wireless       | 4         | 0.48%   |
| Ralink                | 4         | 0.48%   |
| Dell                  | 3         | 0.36%   |
| D-Link System         | 3         | 0.36%   |
| D-Link                | 3         | 0.36%   |
| NetGear               | 2         | 0.24%   |
| Sagem                 | 1         | 0.12%   |
| BUFFALO               | 1         | 0.12%   |
| Atheros               | 1         | 0.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 64        | 7.66%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 53        | 6.35%   |
| Intel Wireless 8260                                                     | 37        | 4.43%   |
| Intel Wireless 7265                                                     | 31        | 3.71%   |
| Intel Wireless 7260                                                     | 31        | 3.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 30        | 3.59%   |
| Intel Wi-Fi 6 AX200                                                     | 30        | 3.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 24        | 2.87%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 23        | 2.75%   |
| Intel Wireless-AC 9260                                                  | 22        | 2.63%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 19        | 2.28%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 18        | 2.16%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 17        | 2.04%   |
| Intel Wireless 3165                                                     | 15        | 1.8%    |
| Intel Centrino Ultimate-N 6300                                          | 15        | 1.8%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 14        | 1.68%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 14        | 1.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 13        | 1.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 12        | 1.44%   |
| Intel Wi-Fi 6 AX201                                                     | 12        | 1.44%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 12        | 1.44%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 11        | 1.32%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 10        | 1.2%    |
| Intel Wireless 3160                                                     | 10        | 1.2%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 10        | 1.2%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 10        | 1.2%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 9         | 1.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 9         | 1.08%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 9         | 1.08%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 9         | 1.08%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 9         | 1.08%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 9         | 1.08%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 8         | 0.96%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 8         | 0.96%   |
| Intel Centrino Advanced-N 6235                                          | 8         | 0.96%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 8         | 0.96%   |
| Ralink RT5370 Wireless Adapter                                          | 7         | 0.84%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 7         | 0.84%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 7         | 0.84%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 273       | 40.81%  |
| Realtek Semiconductor            | 264       | 39.46%  |
| Qualcomm Atheros                 | 41        | 6.13%   |
| Broadcom                         | 40        | 5.98%   |
| Marvell Technology Group         | 16        | 2.39%   |
| Samsung Electronics              | 6         | 0.9%    |
| Xiaomi                           | 5         | 0.75%   |
| Nvidia                           | 4         | 0.6%    |
| Google                           | 4         | 0.6%    |
| AMD                              | 3         | 0.45%   |
| Silicon Integrated Systems [SiS] | 2         | 0.3%    |
| Qualcomm                         | 2         | 0.3%    |
| Lenovo                           | 2         | 0.3%    |
| JMicron Technology               | 2         | 0.3%    |
| Realtek                          | 1         | 0.15%   |
| OPPO Electronics                 | 1         | 0.15%   |
| National Semiconductor           | 1         | 0.15%   |
| HMD Global                       | 1         | 0.15%   |
| Aquantia                         | 1         | 0.15%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 189       | 28.25%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 73        | 10.91%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 67        | 10.01%  |
| Intel Ethernet Connection I219-LM                                 | 19        | 2.84%   |
| Intel Ethernet Connection (4) I219-LM                             | 19        | 2.84%   |
| Intel Ethernet Connection (3) I218-LM                             | 19        | 2.84%   |
| Intel Ethernet Connection (4) I219-V                              | 16        | 2.39%   |
| Intel Ethernet Connection I217-LM                                 | 15        | 2.24%   |
| Intel Ethernet Connection I218-LM                                 | 12        | 1.79%   |
| Intel 82577LM Gigabit Network Connection                          | 12        | 1.79%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 8         | 1.2%    |
| Intel Ethernet Connection (2) I219-LM                             | 8         | 1.2%    |
| Intel Ethernet Connection I219-V                                  | 7         | 1.05%   |
| Intel 82567LM Gigabit Network Connection                          | 7         | 1.05%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 6         | 0.9%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6         | 0.9%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 6         | 0.9%    |
| Intel Ethernet Connection (7) I219-V                              | 6         | 0.9%    |
| Intel Ethernet Connection (6) I219-V                              | 6         | 0.9%    |
| Intel Ethernet Connection (6) I219-LM                             | 6         | 0.9%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 6         | 0.9%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 5         | 0.75%   |
| Intel Ethernet Connection (10) I219-V                             | 5         | 0.75%   |
| Intel 82566MM Gigabit Network Connection                          | 5         | 0.75%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 5         | 0.75%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 5         | 0.75%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4         | 0.6%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 4         | 0.6%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 4         | 0.6%    |
| Nvidia MCP79 Ethernet                                             | 4         | 0.6%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 4         | 0.6%    |
| Intel I210 Gigabit Network Connection                             | 4         | 0.6%    |
| Intel Ethernet Connection (7) I219-LM                             | 4         | 0.6%    |
| Intel 82573L Gigabit Ethernet Controller                          | 4         | 0.6%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 3         | 0.45%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 3         | 0.45%   |
| Intel Ethernet Connection (5) I219-V                              | 3         | 0.45%   |
| Intel Ethernet Connection (3) I218-V                              | 3         | 0.45%   |
| Intel 82577LC Gigabit Network Connection                          | 3         | 0.45%   |
| Intel 82562GT 10/100 Network Connection                           | 3         | 0.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 746       | 52.13%  |
| Ethernet | 648       | 45.28%  |
| Modem    | 28        | 1.96%   |
| Unknown  | 9         | 0.63%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 574       | 51.16%  |
| Ethernet | 540       | 48.13%  |
| Modem    | 5         | 0.45%   |
| Unknown  | 3         | 0.27%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 613       | 80.13%  |
| 1     | 135       | 17.65%  |
| 3     | 9         | 1.18%   |
| 0     | 5         | 0.65%   |
| 6     | 2         | 0.26%   |
| 5     | 1         | 0.13%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 708       | 91%     |
| Yes  | 70        | 9%      |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 311       | 59.46%  |
| Broadcom                        | 48        | 9.18%   |
| Qualcomm Atheros Communications | 39        | 7.46%   |
| Realtek Semiconductor           | 22        | 4.21%   |
| Apple                           | 21        | 4.02%   |
| Foxconn / Hon Hai               | 17        | 3.25%   |
| IMC Networks                    | 14        | 2.68%   |
| Dell                            | 14        | 2.68%   |
| Lite-On Technology              | 11        | 2.1%    |
| Hewlett-Packard                 | 10        | 1.91%   |
| ASUSTek Computer                | 5         | 0.96%   |
| Realtek                         | 4         | 0.76%   |
| Cambridge Silicon Radio         | 3         | 0.57%   |
| Alps Electric                   | 3         | 0.57%   |
| Toshiba                         | 1         | 0.19%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 141       | 26.96%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 45        | 8.6%    |
| Intel AX201 Bluetooth                                       | 42        | 8.03%   |
| Intel AX200 Bluetooth                                       | 29        | 5.54%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 19        | 3.63%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 17        | 3.25%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 17        | 3.25%   |
| Apple Bluetooth Host Controller                             | 13        | 2.49%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 11        | 2.1%    |
| Intel Wireless-AC 3168 Bluetooth                            | 10        | 1.91%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 10        | 1.91%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 8         | 1.53%   |
| Intel AX210 Bluetooth                                       | 8         | 1.53%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 7         | 1.34%   |
| Dell DW375 Bluetooth Module                                 | 7         | 1.34%   |
| Realtek  Bluetooth 4.2 Adapter                              | 6         | 1.15%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 6         | 1.15%   |
| Realtek  Bluetooth Adapter                                  | 5         | 0.96%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 5         | 0.96%   |
| Realtek  Bluetooth 4.0 Adapter                              | 4         | 0.76%   |
| Realtek Bluetooth Radio                                     | 4         | 0.76%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 4         | 0.76%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 4         | 0.76%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 4         | 0.76%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 4         | 0.76%   |
| Realtek Bluetooth Radio                                     | 3         | 0.57%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 3         | 0.57%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 3         | 0.57%   |
| Lite-On Atheros AR3012 Bluetooth                            | 3         | 0.57%   |
| IMC Networks Realtek Bluetooth Adapter                      | 3         | 0.57%   |
| IMC Networks Bluetooth module                               | 3         | 0.57%   |
| HP Broadcom 2070 Bluetooth Combo                            | 3         | 0.57%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter                  | 3         | 0.57%   |
| Foxconn / Hon Hai Wireless_Device                           | 3         | 0.57%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 3         | 0.57%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 3         | 0.57%   |
| ASUS BT-253 Bluetooth Adapter                               | 3         | 0.57%   |
| Apple Built-in iSight (no firmware loaded)                  | 3         | 0.57%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 3         | 0.57%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 2         | 0.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 654       | 73.81%  |
| AMD                                  | 116       | 13.09%  |
| Nvidia                               | 71        | 8.01%   |
| Lenovo                               | 11        | 1.24%   |
| Realtek Semiconductor                | 5         | 0.56%   |
| Silicon Integrated Systems [SiS]     | 3         | 0.34%   |
| Plantronics                          | 3         | 0.34%   |
| Logitech                             | 3         | 0.34%   |
| C-Media Electronics                  | 3         | 0.34%   |
| Texas Instruments                    | 2         | 0.23%   |
| SteelSeries ApS                      | 2         | 0.23%   |
| JMTek                                | 2         | 0.23%   |
| GN Netcom                            | 2         | 0.23%   |
| ULi Electronics                      | 1         | 0.11%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.11%   |
| Sony                                 | 1         | 0.11%   |
| Microsoft                            | 1         | 0.11%   |
| M-Audio                              | 1         | 0.11%   |
| Generalplus Technology               | 1         | 0.11%   |
| ESS Technology                       | 1         | 0.11%   |
| Creative Technology                  | 1         | 0.11%   |
| CMX Systems                          | 1         | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 115       | 10.86%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 73        | 6.89%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 67        | 6.33%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 64        | 6.04%   |
| Intel Broadwell-U Audio Controller                                                                | 43        | 4.06%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 40        | 3.78%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 38        | 3.59%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 33        | 3.12%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 31        | 2.93%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 29        | 2.74%   |
| Intel 8 Series HD Audio Controller                                                                | 29        | 2.74%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 28        | 2.64%   |
| Intel Cannon Lake PCH cAVS                                                                        | 27        | 2.55%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 25        | 2.36%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 25        | 2.36%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 23        | 2.17%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 23        | 2.17%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 23        | 2.17%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 22        | 2.08%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 21        | 1.98%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 18        | 1.7%    |
| Intel Comet Lake PCH cAVS                                                                         | 15        | 1.42%   |
| Intel CM238 HD Audio Controller                                                                   | 15        | 1.42%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 12        | 1.13%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 12        | 1.13%   |
| AMD FCH Azalia Controller                                                                         | 10        | 0.94%   |
| AMD Kabini HDMI/DP Audio                                                                          | 9         | 0.85%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 7         | 0.66%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 0.66%   |
| Lenovo Realtek USB Audio                                                                          | 6         | 0.57%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 0.57%   |
| AMD Wrestler HDMI Audio                                                                           | 6         | 0.57%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 6         | 0.57%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 5         | 0.47%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 5         | 0.47%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 5         | 0.47%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 0.47%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 5         | 0.47%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 5         | 0.47%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 5         | 0.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Samsung Electronics   | 257       | 28.03%  |
| SK hynix              | 199       | 21.7%   |
| Micron Technology     | 89        | 9.71%   |
| Kingston              | 88        | 9.6%    |
| Unknown               | 77        | 8.4%    |
| Crucial               | 46        | 5.02%   |
| Ramaxel Technology    | 22        | 2.4%    |
| Elpida                | 17        | 1.85%   |
| Corsair               | 17        | 1.85%   |
| Unknown               | 15        | 1.64%   |
| A-DATA Technology     | 12        | 1.31%   |
| Nanya Technology      | 9         | 0.98%   |
| Transcend             | 7         | 0.76%   |
| Team                  | 7         | 0.76%   |
| G.Skill               | 7         | 0.76%   |
| Smart                 | 5         | 0.55%   |
| Neo Forza             | 5         | 0.55%   |
| PNY                   | 4         | 0.44%   |
| 48spaces              | 4         | 0.44%   |
| GOODRAM               | 3         | 0.33%   |
| Goldkey               | 3         | 0.33%   |
| Avant                 | 3         | 0.33%   |
| Unknown (ABCD)        | 2         | 0.22%   |
| Patriot               | 2         | 0.22%   |
| KomputerBay           | 2         | 0.22%   |
| V-GeN                 | 1         | 0.11%   |
| V-Color               | 1         | 0.11%   |
| Teikon                | 1         | 0.11%   |
| Super Talent          | 1         | 0.11%   |
| Qimonda               | 1         | 0.11%   |
| PUSKILL               | 1         | 0.11%   |
| Magnum Tech           | 1         | 0.11%   |
| KingTiger             | 1         | 0.11%   |
| Kingmax Semiconductor | 1         | 0.11%   |
| Golden Empire         | 1         | 0.11%   |
| Gold Key              | 1         | 0.11%   |
| CSX                   | 1         | 0.11%   |
| Apacer                | 1         | 0.11%   |
| AMD                   | 1         | 0.11%   |
| A Force               | 1         | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 18        | 1.82%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 16        | 1.61%   |
| Unknown                                                      | 15        | 1.51%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s       | 14        | 1.41%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s        | 14        | 1.41%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 13        | 1.31%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 11        | 1.11%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 11        | 1.11%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s        | 11        | 1.11%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s        | 11        | 1.11%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 9         | 0.91%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 9         | 0.91%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 8         | 0.81%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 7         | 0.71%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s      | 7         | 0.71%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s        | 7         | 0.71%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 7         | 0.71%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s        | 7         | 0.71%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s        | 7         | 0.71%   |
| Unknown RAM Module 2GB SODIMM DDR2                           | 6         | 0.61%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 6         | 0.61%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s        | 6         | 0.61%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 6         | 0.61%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s       | 6         | 0.61%   |
| Unknown RAM Module 512MB SODIMM DDR                          | 5         | 0.5%    |
| Unknown RAM Module 1GB SODIMM DDR                            | 5         | 0.5%    |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s        | 5         | 0.5%    |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s       | 5         | 0.5%    |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 5         | 0.5%    |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s       | 5         | 0.5%    |
| Samsung RAM M471B5674-M0-YK0 4GB Chip DDR3 1600MT/s          | 5         | 0.5%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s        | 5         | 0.5%    |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s       | 5         | 0.5%    |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s       | 5         | 0.5%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 5         | 0.5%    |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s | 5         | 0.5%    |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s    | 5         | 0.5%    |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s        | 5         | 0.5%    |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s        | 5         | 0.5%    |
| Unknown RAM Module 1GB SODIMM DDR2                           | 4         | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 324       | 42.3%   |
| DDR4    | 294       | 38.38%  |
| DDR2    | 63        | 8.22%   |
| LPDDR3  | 32        | 4.18%   |
| DDR     | 17        | 2.22%   |
| LPDDR4  | 15        | 1.96%   |
| Unknown | 8         | 1.04%   |
| SDRAM   | 7         | 0.91%   |
| LPDDR5  | 2         | 0.26%   |
| DRAM    | 2         | 0.26%   |
| SRAM    | 1         | 0.13%   |
| RAM     | 1         | 0.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 702       | 90.82%  |
| Row Of Chips | 44        | 5.69%   |
| Chip         | 21        | 2.72%   |
| Unknown      | 4         | 0.52%   |
| DIMM         | 2         | 0.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 296       | 34.95%  |
| 4096  | 250       | 29.52%  |
| 2048  | 119       | 14.05%  |
| 16384 | 106       | 12.51%  |
| 1024  | 44        | 5.19%   |
| 32768 | 17        | 2.01%   |
| 512   | 10        | 1.18%   |
| 256   | 4         | 0.47%   |
| 2560  | 1         | 0.12%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 197       | 23.76%  |
| 2667    | 110       | 13.27%  |
| 2400    | 87        | 10.49%  |
| 3200    | 80        | 9.65%   |
| 1333    | 69        | 8.32%   |
| 2133    | 63        | 7.6%    |
| 1334    | 44        | 5.31%   |
| 667     | 36        | 4.34%   |
| Unknown | 32        | 3.86%   |
| 1867    | 26        | 3.14%   |
| 800     | 16        | 1.93%   |
| 533     | 15        | 1.81%   |
| 1067    | 12        | 1.45%   |
| 4267    | 9         | 1.09%   |
| 1066    | 9         | 1.09%   |
| 975     | 6         | 0.72%   |
| 4266    | 3         | 0.36%   |
| 1866    | 3         | 0.36%   |
| 2933    | 2         | 0.24%   |
| 6400    | 1         | 0.12%   |
| 4800    | 1         | 0.12%   |
| 2666    | 1         | 0.12%   |
| 1200    | 1         | 0.12%   |
| 666     | 1         | 0.12%   |
| 333     | 1         | 0.12%   |
| 266     | 1         | 0.12%   |
| 200     | 1         | 0.12%   |
| 166     | 1         | 0.12%   |
| 100     | 1         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| ELGIN               | 2         | 66.67%  |
| Samsung Electronics | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| ELGIN L42PRO                       | 2         | 66.67%  |
| Samsung ML-1610 Mono Laser Printer | 1         | 33.33%  |

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
| Chicony Electronics                    | 188       | 32.36%  |
| IMC Networks                           | 68        | 11.7%   |
| Realtek Semiconductor                  | 52        | 8.95%   |
| Microdia                               | 51        | 8.78%   |
| Acer                                   | 51        | 8.78%   |
| Sunplus Innovation Technology          | 39        | 6.71%   |
| Suyin                                  | 21        | 3.61%   |
| Lite-On Technology                     | 20        | 3.44%   |
| Cheng Uei Precision Industry (Foxlink) | 13        | 2.24%   |
| Quanta                                 | 9         | 1.55%   |
| Apple                                  | 9         | 1.55%   |
| Lenovo                                 | 7         | 1.2%    |
| Syntek                                 | 6         | 1.03%   |
| Silicon Motion                         | 6         | 1.03%   |
| Logitech                               | 5         | 0.86%   |
| Z-Star Microelectronics                | 4         | 0.69%   |
| Importek                               | 4         | 0.69%   |
| ALi                                    | 4         | 0.69%   |
| Alcor Micro                            | 4         | 0.69%   |
| Ricoh                                  | 3         | 0.52%   |
| Luxvisions Innotech Limited            | 3         | 0.52%   |
| Unknown                                | 2         | 0.34%   |
| Primax Electronics                     | 2         | 0.34%   |
| Pixart Imaging                         | 2         | 0.34%   |
| Intel                                  | 2         | 0.34%   |
| Sonix Technology                       | 1         | 0.17%   |
| ShineTech                              | 1         | 0.17%   |
| OmniVision Technologies                | 1         | 0.17%   |
| Genesys Logic                          | 1         | 0.17%   |
| DigiTech                               | 1         | 0.17%   |
| Cubeternet                             | 1         | 0.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Chicony Integrated Camera                 | 59        | 10.05%  |
| Acer Integrated Camera                    | 26        | 4.43%   |
| IMC Networks Integrated Camera            | 24        | 4.09%   |
| Realtek Integrated_Webcam_HD              | 20        | 3.41%   |
| Chicony HD WebCam                         | 17        | 2.9%    |
| Sunplus Integrated_Webcam_HD              | 14        | 2.39%   |
| Microdia Integrated_Webcam_HD             | 14        | 2.39%   |
| Microdia Integrated Webcam                | 14        | 2.39%   |
| Chicony Lenovo Integrated Camera (0.3MP)  | 14        | 2.39%   |
| Lite-On Integrated Camera                 | 12        | 2.04%   |
| Chicony Chicony USB2.0 Camera             | 11        | 1.87%   |
| Realtek Realtek USB2.0 PC Camera          | 10        | 1.7%    |
| IMC Networks USB2.0 HD UVC WebCam         | 10        | 1.7%    |
| Chicony Integrated Camera (1280x720@30)   | 10        | 1.7%    |
| IMC Networks EasyCamera                   | 8         | 1.36%   |
| Chicony ThinkPad T490 Webcam              | 7         | 1.19%   |
| Sunplus Laptop_Integrated_Webcam_FHD      | 6         | 1.02%   |
| IMC Networks Integrated Webcam            | 6         | 1.02%   |
| Acer SunplusIT Integrated Camera          | 6         | 1.02%   |
| Sunplus Laptop Integrated WebCam HD       | 5         | 0.85%   |
| Sunplus HD WebCam                         | 5         | 0.85%   |
| Microdia Integrated Webcam HD             | 5         | 0.85%   |
| Lenovo Integrated Webcam [R5U877]         | 5         | 0.85%   |
| IMC Networks UVC VGA Webcam               | 5         | 0.85%   |
| Apple FaceTime HD Camera                  | 5         | 0.85%   |
| Realtek Integrated Webcam                 | 4         | 0.68%   |
| Quanta HD WebCam                          | 4         | 0.68%   |
| Microdia Dell Laptop Integrated Webcam HD | 4         | 0.68%   |
| Lite-On HP HD Camera                      | 4         | 0.68%   |
| Chicony USB2.0 VGA UVC WebCam             | 4         | 0.68%   |
| Chicony Integrated IR Camera              | 4         | 0.68%   |
| Chicony Integrated HP HD Webcam           | 4         | 0.68%   |
| Chicony Integrated Camera [ThinkPad]      | 4         | 0.68%   |
| Chicony HP HD Webcam [Fixed]              | 4         | 0.68%   |
| ALi Gateway Webcam                        | 4         | 0.68%   |
| Acer ThinkPad P50 Integrated Camera       | 4         | 0.68%   |
| Acer Lenovo EasyCamera                    | 4         | 0.68%   |
| Syntek Lenovo EasyCamera                  | 3         | 0.51%   |
| Suyin Integrated_Webcam_HD                | 3         | 0.51%   |
| Suyin 1.3M HD WebCam                      | 3         | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 61        | 34.66%  |
| Synaptics                  | 45        | 25.57%  |
| Shenzhen Goodix Technology | 22        | 12.5%   |
| Upek                       | 16        | 9.09%   |
| STMicroelectronics         | 10        | 5.68%   |
| AuthenTec                  | 9         | 5.11%   |
| Broadcom                   | 8         | 4.55%   |
| LighTuning Technology      | 3         | 1.7%    |
| Samsung Electronics        | 1         | 0.57%   |
| Elan Microelectronics      | 1         | 0.57%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 22        | 12.5%   |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 20        | 11.36%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 16        | 9.09%   |
| Validity Sensors Synaptics WBDI                                              | 14        | 7.95%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 14        | 7.95%   |
| Shenzhen Goodix Fingerprint Reader                                           | 14        | 7.95%   |
| STMicroelectronics Fingerprint Reader                                        | 10        | 5.68%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 4.55%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 7         | 3.98%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 6         | 3.41%   |
| Shenzhen Goodix  Fingerprint Device                                          | 6         | 3.41%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 5         | 2.84%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                    | 4         | 2.27%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 3         | 1.7%    |
| AuthenTec AuthenTec Inc. AES1660                                             | 3         | 1.7%    |
| AuthenTec AES2501 Fingerprint Sensor                                         | 3         | 1.7%    |
| Validity Sensors VFS471 Fingerprint Reader                                   | 2         | 1.14%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint   | 2         | 1.14%   |
| Shenzhen Goodix FingerPrint                                                  | 2         | 1.14%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 2         | 1.14%   |
| AuthenTec AES2810                                                            | 2         | 1.14%   |
| Unknown                                                                      | 2         | 1.14%   |
| Validity Sensors VFS491                                                      | 1         | 0.57%   |
| Validity Sensors VFS451 Fingerprint Reader                                   | 1         | 0.57%   |
| Validity Sensors VFS Fingerprint sensor                                      | 1         | 0.57%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                  | 1         | 0.57%   |
| Validity Sensors Fingerprint scanner                                         | 1         | 0.57%   |
| Samsung Fingerprint Sensor Device - 730B                                     | 1         | 0.57%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 1         | 0.57%   |
| Elan ELAN WBF Fingerprint Sensor                                             | 1         | 0.57%   |
| AuthenTec AuthenTec Inc. AES2660                                             | 1         | 0.57%   |

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
| 2     | 241       | 30.01%  |
| 1     | 239       | 29.76%  |
| 3     | 153       | 19.05%  |
| 0     | 76        | 9.46%   |
| 4     | 68        | 8.47%   |
| 5     | 16        | 1.99%   |
| 6     | 8         | 1%      |
| 9     | 1         | 0.12%   |
| 7     | 1         | 0.12%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 547       | 38.71%  |
| Bluetooth                | 211       | 14.93%  |
| Card reader              | 183       | 12.95%  |
| Fingerprint reader       | 170       | 12.03%  |
| Net/wireless             | 166       | 11.75%  |
| Firewire controller      | 73        | 5.17%   |
| Storage                  | 19        | 1.34%   |
| Modem                    | 14        | 0.99%   |
| Sound                    | 11        | 0.78%   |
| Network                  | 10        | 0.71%   |
| Net/ethernet             | 7         | 0.5%    |
| Storage/nvme             | 1         | 0.07%   |
| Graphics card            | 1         | 0.07%   |

