BSD in Russia - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for BSD in Russia.

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

Total: 283

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [68efc7ef8d](https://bsd-hardware.info/?probe=68efc7ef8d) | Sep 06, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [f42dfa2992](https://bsd-hardware.info/?probe=f42dfa2992) | Sep 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [044910f579](https://bsd-hardware.info/?probe=044910f579) | Sep 01, 2023 |
| MSI           | Sword 17 A11UD              | [4b101af84b](https://bsd-hardware.info/?probe=4b101af84b) | Aug 19, 2023 |
| Lenovo        | ThinkPad T495s 20QKS1812... | [0238ea2cab](https://bsd-hardware.info/?probe=0238ea2cab) | Aug 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [9beb5f6126](https://bsd-hardware.info/?probe=9beb5f6126) | Aug 17, 2023 |
| Fujitsu Si... | LIFEBOOK P1610              | [bb055a94f0](https://bsd-hardware.info/?probe=bb055a94f0) | Aug 12, 2023 |
| Lenovo        | ThinkPad T410 2522NP6       | [194b8efa98](https://bsd-hardware.info/?probe=194b8efa98) | Jul 25, 2023 |
| ASUSTek       | 900                         | [2e55f5d4cc](https://bsd-hardware.info/?probe=2e55f5d4cc) | Jul 20, 2023 |
| MSI           | Sword 17 A11UD              | [c9852c1ee3](https://bsd-hardware.info/?probe=c9852c1ee3) | Jul 19, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | [5fcffa5bd6](https://bsd-hardware.info/?probe=5fcffa5bd6) | Jul 19, 2023 |
| IBM           | ThinkPad T43 1871F1G        | [d6fbc6ebfb](https://bsd-hardware.info/?probe=d6fbc6ebfb) | Jul 18, 2023 |
| ASUSTek       | K42Jr                       | [256168572a](https://bsd-hardware.info/?probe=256168572a) | Jul 18, 2023 |
| HP            | EliteBook 6930p             | [12124d8753](https://bsd-hardware.info/?probe=12124d8753) | Jul 15, 2023 |
| Sony          | VPCX115KX                   | [9dab449a23](https://bsd-hardware.info/?probe=9dab449a23) | Jul 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [03e83e60ca](https://bsd-hardware.info/?probe=03e83e60ca) | Jul 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [3096d8532a](https://bsd-hardware.info/?probe=3096d8532a) | Jul 07, 2023 |
| HP            | 250 G6 Notebook PC          | [f7df283c94](https://bsd-hardware.info/?probe=f7df283c94) | Jun 24, 2023 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | [27ba75252a](https://bsd-hardware.info/?probe=27ba75252a) | Jun 09, 2023 |
| ASUSTek       | 1015BX                      | [ad05aaf9fe](https://bsd-hardware.info/?probe=ad05aaf9fe) | Jun 07, 2023 |
| HP            | Pavilion Notebook           | [1bb0436fe5](https://bsd-hardware.info/?probe=1bb0436fe5) | May 30, 2023 |
| HP            | Pavilion Notebook           | [41ce3c5d11](https://bsd-hardware.info/?probe=41ce3c5d11) | May 21, 2023 |
| Lenovo        | ThinkPad X201 3323BBG       | [7b529b0888](https://bsd-hardware.info/?probe=7b529b0888) | May 17, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [256915976d](https://bsd-hardware.info/?probe=256915976d) | May 12, 2023 |
| MSI           | GE62 6QC                    | [7c3fd3c9ca](https://bsd-hardware.info/?probe=7c3fd3c9ca) | May 08, 2023 |
| HP            | Laptop 14-bs0xx             | [98ea66d6e8](https://bsd-hardware.info/?probe=98ea66d6e8) | May 07, 2023 |
| Samsung       | NC110P/NC108P/NC111P        | [ea55a6fecf](https://bsd-hardware.info/?probe=ea55a6fecf) | May 02, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | [b8d2c0d81d](https://bsd-hardware.info/?probe=b8d2c0d81d) | Apr 16, 2023 |
| Dell          | Inspiron 3542               | [4dfa2f0148](https://bsd-hardware.info/?probe=4dfa2f0148) | Apr 15, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [b189b0988c](https://bsd-hardware.info/?probe=b189b0988c) | Apr 14, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [3d7bf4205b](https://bsd-hardware.info/?probe=3d7bf4205b) | Apr 13, 2023 |
| HMT           | W041-TF-A-45                | [298d106fd1](https://bsd-hardware.info/?probe=298d106fd1) | Apr 13, 2023 |
| ASUSTek       | X200MA                      | [c30e92db89](https://bsd-hardware.info/?probe=c30e92db89) | Apr 06, 2023 |
| Lenovo        | G570 20079                  | [76cc1653c3](https://bsd-hardware.info/?probe=76cc1653c3) | Apr 03, 2023 |
| Apple         | MacBookPro12,1              | [640aad419a](https://bsd-hardware.info/?probe=640aad419a) | Apr 02, 2023 |
| DNS           | W9x0LU                      | [6539659387](https://bsd-hardware.info/?probe=6539659387) | Mar 31, 2023 |
| HMT           | W041-TF-A-45                | [666df5a7e0](https://bsd-hardware.info/?probe=666df5a7e0) | Mar 31, 2023 |
| Intel         | Intel                       | [75e9733afd](https://bsd-hardware.info/?probe=75e9733afd) | Mar 30, 2023 |
| Irbis         | NB78                        | [471efbc788](https://bsd-hardware.info/?probe=471efbc788) | Mar 29, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [dddf27cde4](https://bsd-hardware.info/?probe=dddf27cde4) | Mar 28, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [c2ba6aca7d](https://bsd-hardware.info/?probe=c2ba6aca7d) | Mar 28, 2023 |
| Samsung       | R468/R418                   | [f620a5c6ec](https://bsd-hardware.info/?probe=f620a5c6ec) | Mar 25, 2023 |
| Dell          | G5 5587                     | [9b7714cbab](https://bsd-hardware.info/?probe=9b7714cbab) | Mar 24, 2023 |
| Dell          | G5 5587                     | [c118e0665f](https://bsd-hardware.info/?probe=c118e0665f) | Mar 24, 2023 |
| HUAWEI        | HVY-WXX9                    | [e1b5d66244](https://bsd-hardware.info/?probe=e1b5d66244) | Mar 20, 2023 |
| ASUSTek       | 1015PX                      | [d6c1199165](https://bsd-hardware.info/?probe=d6c1199165) | Mar 20, 2023 |
| ASUSTek       | K501UQ                      | [b7256fddbb](https://bsd-hardware.info/?probe=b7256fddbb) | Mar 19, 2023 |
| IP3 Techno... | ACN1S                       | [d0761f4192](https://bsd-hardware.info/?probe=d0761f4192) | Mar 18, 2023 |
| Toshiba       | Satellite L40               | [2297dcb7e7](https://bsd-hardware.info/?probe=2297dcb7e7) | Mar 17, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [564b1ccce1](https://bsd-hardware.info/?probe=564b1ccce1) | Mar 15, 2023 |
| Samsung       | R468/R418                   | [af44a29d38](https://bsd-hardware.info/?probe=af44a29d38) | Mar 13, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [9c1172aa29](https://bsd-hardware.info/?probe=9c1172aa29) | Mar 12, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [5bcd236c4a](https://bsd-hardware.info/?probe=5bcd236c4a) | Mar 12, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [ef722fc37b](https://bsd-hardware.info/?probe=ef722fc37b) | Feb 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [0232c45faa](https://bsd-hardware.info/?probe=0232c45faa) | Feb 04, 2023 |
| Lenovo        | ThinkPad E14 20RA0036RT     | [941da31f26](https://bsd-hardware.info/?probe=941da31f26) | Feb 02, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [c2f84d2103](https://bsd-hardware.info/?probe=c2f84d2103) | Jan 31, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [165d435f30](https://bsd-hardware.info/?probe=165d435f30) | Jan 31, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [d5f06d91db](https://bsd-hardware.info/?probe=d5f06d91db) | Jan 28, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [448f9265f2](https://bsd-hardware.info/?probe=448f9265f2) | Jan 27, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [512bf8f61d](https://bsd-hardware.info/?probe=512bf8f61d) | Jan 27, 2023 |
| Timi          | TM1607                      | [57113d2886](https://bsd-hardware.info/?probe=57113d2886) | Jan 25, 2023 |
| MSI           | PS63 Modern 8M              | [f740e313e5](https://bsd-hardware.info/?probe=f740e313e5) | Jan 24, 2023 |
| Timi          | TM1607                      | [27db14fdbd](https://bsd-hardware.info/?probe=27db14fdbd) | Jan 24, 2023 |
| ASUSTek       | K50IN                       | [6f7a8f3338](https://bsd-hardware.info/?probe=6f7a8f3338) | Jan 23, 2023 |
| Timi          | TM1607                      | [7636a0ef8f](https://bsd-hardware.info/?probe=7636a0ef8f) | Jan 23, 2023 |
| Timi          | TM1607                      | [1ca46404a1](https://bsd-hardware.info/?probe=1ca46404a1) | Jan 23, 2023 |
| Acer          | Aspire ES1-533              | [d2652b76cf](https://bsd-hardware.info/?probe=d2652b76cf) | Jan 22, 2023 |
| Lenovo        | ThinkPad P50 20EN0041MX     | [c27f1f53f2](https://bsd-hardware.info/?probe=c27f1f53f2) | Jan 22, 2023 |
| Lenovo        | ThinkPad X220 4291LF6       | [25cddb26c3](https://bsd-hardware.info/?probe=25cddb26c3) | Jan 11, 2023 |
| Timi          | Redmi Book Pro 14 2022      | [ce5e882952](https://bsd-hardware.info/?probe=ce5e882952) | Dec 28, 2022 |
| HUAWEI        | CREM-WXX9                   | [ced12f0b41](https://bsd-hardware.info/?probe=ced12f0b41) | Dec 19, 2022 |
| ASUSTek       | K50IN                       | [b8bfdec836](https://bsd-hardware.info/?probe=b8bfdec836) | Dec 15, 2022 |
| Dell          | Latitude 5400               | [639993a130](https://bsd-hardware.info/?probe=639993a130) | Dec 15, 2022 |
| Dell          | Latitude 5400               | [5b9eb16e5e](https://bsd-hardware.info/?probe=5b9eb16e5e) | Dec 15, 2022 |
| HUAWEI        | KLVL-WXXW                   | [55f876d83f](https://bsd-hardware.info/?probe=55f876d83f) | Dec 15, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [babe4bb620](https://bsd-hardware.info/?probe=babe4bb620) | Dec 13, 2022 |
| Sony          | SVP1321V9RB                 | [932facd689](https://bsd-hardware.info/?probe=932facd689) | Nov 25, 2022 |
| Samsung       | Q430/Q530                   | [fb98c8c797](https://bsd-hardware.info/?probe=fb98c8c797) | Oct 29, 2022 |
| Samsung       | Q430/Q530                   | [4965215a13](https://bsd-hardware.info/?probe=4965215a13) | Oct 25, 2022 |
| MSI           | PS63 Modern 8M              | [949e472db5](https://bsd-hardware.info/?probe=949e472db5) | Oct 19, 2022 |
| Acer          | Aspire 5336                 | [127ddc93fb](https://bsd-hardware.info/?probe=127ddc93fb) | Oct 10, 2022 |
| Acer          | Aspire E5-722G              | [7a4eb565fe](https://bsd-hardware.info/?probe=7a4eb565fe) | Oct 10, 2022 |
| Kraftway      | KW10T                       | [db27da2e88](https://bsd-hardware.info/?probe=db27da2e88) | Sep 29, 2022 |
| Dell          | System Vostro 3750          | [166fbacd73](https://bsd-hardware.info/?probe=166fbacd73) | Sep 24, 2022 |
| Dell          | Inspiron 15 3511            | [5abbba28de](https://bsd-hardware.info/?probe=5abbba28de) | Sep 11, 2022 |
| Dell          | Vostro 5415                 | [ef6d4ee660](https://bsd-hardware.info/?probe=ef6d4ee660) | Sep 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [cffed92600](https://bsd-hardware.info/?probe=cffed92600) | Sep 06, 2022 |
| Lenovo        | ThinkPad T420 4178A72       | [18a105546b](https://bsd-hardware.info/?probe=18a105546b) | Aug 29, 2022 |
| Lenovo        | ThinkPad T420 4178A72       | [1433351032](https://bsd-hardware.info/?probe=1433351032) | Aug 29, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [2c7586b0ed](https://bsd-hardware.info/?probe=2c7586b0ed) | Aug 25, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [fcfa6205d8](https://bsd-hardware.info/?probe=fcfa6205d8) | Aug 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [6184507a45](https://bsd-hardware.info/?probe=6184507a45) | Aug 21, 2022 |
| ASUSTek       | ZenBook 14 UX410UFR         | [2bf0f0ef08](https://bsd-hardware.info/?probe=2bf0f0ef08) | Aug 19, 2022 |
| Sony          | VGN-UX1XRN                  | [312df080a7](https://bsd-hardware.info/?probe=312df080a7) | Aug 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [2da32e59b0](https://bsd-hardware.info/?probe=2da32e59b0) | Aug 14, 2022 |
| Acer          | Aspire 5930                 | [4bd9ec4253](https://bsd-hardware.info/?probe=4bd9ec4253) | Aug 02, 2022 |
| HP            | 250 G6 Notebook PC          | [511d057c70](https://bsd-hardware.info/?probe=511d057c70) | Jul 27, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [7b130fb168](https://bsd-hardware.info/?probe=7b130fb168) | Jul 27, 2022 |
| Lenovo        | V580 20147                  | [0615e8260d](https://bsd-hardware.info/?probe=0615e8260d) | Jul 02, 2022 |
| Lenovo        | V580 20147                  | [6f1fd71366](https://bsd-hardware.info/?probe=6f1fd71366) | Jul 02, 2022 |
| Acer          | Aspire A114-33              | [d3659c85e9](https://bsd-hardware.info/?probe=d3659c85e9) | Jun 28, 2022 |
| Samsung       | R530/R730/R540              | [a4cd230718](https://bsd-hardware.info/?probe=a4cd230718) | Jun 27, 2022 |
| Toshiba       | Satellite A300              | [e057898546](https://bsd-hardware.info/?probe=e057898546) | Jun 18, 2022 |
| HP            | Laptop 15s-fq1xxx           | [380218b2c1](https://bsd-hardware.info/?probe=380218b2c1) | Jun 12, 2022 |
| Lenovo        | ThinkPad Yoga 260 20FES1... | [73ab89b8f0](https://bsd-hardware.info/?probe=73ab89b8f0) | Jun 05, 2022 |
| Lenovo        | ThinkPad Yoga 260 20FES1... | [637f87f44e](https://bsd-hardware.info/?probe=637f87f44e) | Jun 05, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [cf5f498572](https://bsd-hardware.info/?probe=cf5f498572) | May 21, 2022 |
| HP            | ProBook 455 G7              | [c6944afe69](https://bsd-hardware.info/?probe=c6944afe69) | May 19, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [64600e1c24](https://bsd-hardware.info/?probe=64600e1c24) | May 11, 2022 |
| Lenovo        | ThinkPad T495s 20QKS1812... | [89db84f7ec](https://bsd-hardware.info/?probe=89db84f7ec) | May 10, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [3ff916acf7](https://bsd-hardware.info/?probe=3ff916acf7) | May 09, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [33367fe342](https://bsd-hardware.info/?probe=33367fe342) | May 09, 2022 |
| Acer          | Aspire ES1-132              | [18426698ad](https://bsd-hardware.info/?probe=18426698ad) | May 02, 2022 |
| HP            | Pavilion g6                 | [4b8ee6729a](https://bsd-hardware.info/?probe=4b8ee6729a) | May 02, 2022 |
| Lenovo        | B50-30 20382                | [5701dac149](https://bsd-hardware.info/?probe=5701dac149) | Apr 30, 2022 |
| DEXP          | NAVIS P100                  | [a9c8814bf8](https://bsd-hardware.info/?probe=a9c8814bf8) | Apr 22, 2022 |
| Lenovo        | ThinkPad X121e 3053A52      | [68d0bf2a99](https://bsd-hardware.info/?probe=68d0bf2a99) | Apr 22, 2022 |
| DNS           | W9x0LU                      | [8ac57e3b59](https://bsd-hardware.info/?probe=8ac57e3b59) | Apr 06, 2022 |
| Timi          | TM1612                      | [0389c8d487](https://bsd-hardware.info/?probe=0389c8d487) | Apr 05, 2022 |
| Lenovo        | ThinkPad T490s 20NX000DR... | [c052d7cab0](https://bsd-hardware.info/?probe=c052d7cab0) | Apr 01, 2022 |
| HUAWEI        | CREM-WXX9                   | [e750905413](https://bsd-hardware.info/?probe=e750905413) | Mar 29, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [00213ecee9](https://bsd-hardware.info/?probe=00213ecee9) | Mar 25, 2022 |
| Acer          | Aspire A114-33              | [57765224eb](https://bsd-hardware.info/?probe=57765224eb) | Mar 18, 2022 |
| Packard Be... | EasyNote TE69HW             | [851eea349f](https://bsd-hardware.info/?probe=851eea349f) | Mar 17, 2022 |
| Acer          | Aspire 4820T                | [1617262a28](https://bsd-hardware.info/?probe=1617262a28) | Mar 16, 2022 |
| Acer          | Aspire A315-23              | [7fb743c654](https://bsd-hardware.info/?probe=7fb743c654) | Mar 15, 2022 |
| Acer          | Aspire A114-33              | [6e7384f4cc](https://bsd-hardware.info/?probe=6e7384f4cc) | Mar 15, 2022 |
| ASUSTek       | M51Sr                       | [936a577d1a](https://bsd-hardware.info/?probe=936a577d1a) | Mar 10, 2022 |
| Acer          | Aspire A114-33              | [62f4e0a060](https://bsd-hardware.info/?probe=62f4e0a060) | Feb 21, 2022 |
| Acer          | Aspire A114-33              | [da786acd84](https://bsd-hardware.info/?probe=da786acd84) | Feb 20, 2022 |
| Lenovo        | E31-80 80MX                 | [098afac660](https://bsd-hardware.info/?probe=098afac660) | Feb 16, 2022 |
| Acer          | Aspire A114-33              | [06887b10fd](https://bsd-hardware.info/?probe=06887b10fd) | Feb 15, 2022 |
| HP            | ProBook 445 G7              | [494195b923](https://bsd-hardware.info/?probe=494195b923) | Feb 08, 2022 |
| Dell          | Venue 11 Pro 7140           | [328f9e8d94](https://bsd-hardware.info/?probe=328f9e8d94) | Feb 04, 2022 |
| HP            | Laptop 15-rb0xx             | [8e9a6cff62](https://bsd-hardware.info/?probe=8e9a6cff62) | Jan 31, 2022 |
| MSI           | GE75 Raider 10SFS           | [48b172bfe8](https://bsd-hardware.info/?probe=48b172bfe8) | Jan 25, 2022 |
| MSI           | GE75 Raider 10SFS           | [306f312c47](https://bsd-hardware.info/?probe=306f312c47) | Jan 25, 2022 |
| HP            | Laptop 15-bw0xx             | [1c8f50f7eb](https://bsd-hardware.info/?probe=1c8f50f7eb) | Jan 24, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20T20... | [6836fc60f6](https://bsd-hardware.info/?probe=6836fc60f6) | Jan 09, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [7aea2ccaa7](https://bsd-hardware.info/?probe=7aea2ccaa7) | Jan 08, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [87c8ee9b4c](https://bsd-hardware.info/?probe=87c8ee9b4c) | Dec 31, 2021 |
| HP            | ProBook 655 G1              | [da312d7c14](https://bsd-hardware.info/?probe=da312d7c14) | Dec 30, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [4bb84a33fa](https://bsd-hardware.info/?probe=4bb84a33fa) | Dec 26, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [ade9f77281](https://bsd-hardware.info/?probe=ade9f77281) | Nov 25, 2021 |
| Acer          | Aspire 3810T                | [86782a69be](https://bsd-hardware.info/?probe=86782a69be) | Nov 13, 2021 |
| Acer          | Aspire 3810T                | [608e43163d](https://bsd-hardware.info/?probe=608e43163d) | Nov 12, 2021 |
| Lenovo        | S20-30 Touch 20434          | [141a393d54](https://bsd-hardware.info/?probe=141a393d54) | Oct 08, 2021 |
| ASUSTek       | UX21A                       | [fe08d28d4c](https://bsd-hardware.info/?probe=fe08d28d4c) | Oct 05, 2021 |
| IBM           | ThinkPad H 1846AQG          | [5e5c7247ca](https://bsd-hardware.info/?probe=5e5c7247ca) | Oct 01, 2021 |
| ASUSTek       | VX7SX                       | [6ca36a455d](https://bsd-hardware.info/?probe=6ca36a455d) | Sep 09, 2021 |
| Kraftway      | KW10T                       | [4810842d82](https://bsd-hardware.info/?probe=4810842d82) | Sep 06, 2021 |
| Lenovo        | ThinkPad E590 20NB0012RT    | [98072b8db6](https://bsd-hardware.info/?probe=98072b8db6) | Jul 26, 2021 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [3fb09d0402](https://bsd-hardware.info/?probe=3fb09d0402) | Jul 24, 2021 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [bef816fe74](https://bsd-hardware.info/?probe=bef816fe74) | Jul 24, 2021 |
| Acer          | Aspire A715-75G             | [f613cb0452](https://bsd-hardware.info/?probe=f613cb0452) | Jul 23, 2021 |
| Dell          | Inspiron 5758               | [7542ae751d](https://bsd-hardware.info/?probe=7542ae751d) | Jul 20, 2021 |
| eMachines     | eM350                       | [94579b896e](https://bsd-hardware.info/?probe=94579b896e) | Jul 04, 2021 |
| eMachines     | eM350                       | [52198cfd80](https://bsd-hardware.info/?probe=52198cfd80) | Jun 22, 2021 |
| eMachines     | eM350                       | [60b4338ace](https://bsd-hardware.info/?probe=60b4338ace) | Jun 22, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [4ac6c9b3eb](https://bsd-hardware.info/?probe=4ac6c9b3eb) | Jun 08, 2021 |
| Acer          | Aspire ES1-132              | [62c87cf194](https://bsd-hardware.info/?probe=62c87cf194) | Jun 07, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [8fc867cfae](https://bsd-hardware.info/?probe=8fc867cfae) | Jun 06, 2021 |
| Lenovo        | ThinkPad T430 23511A6       | [89fb2aa493](https://bsd-hardware.info/?probe=89fb2aa493) | Jun 05, 2021 |
| Acer          | Aspire ES1-132              | [bf605b741b](https://bsd-hardware.info/?probe=bf605b741b) | Jun 04, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [84e93d02e1](https://bsd-hardware.info/?probe=84e93d02e1) | Jun 03, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [1bb850edca](https://bsd-hardware.info/?probe=1bb850edca) | Jun 03, 2021 |
| Acer          | Extensa 2540                | [e7d6ece4ba](https://bsd-hardware.info/?probe=e7d6ece4ba) | Apr 11, 2021 |
| ASUSTek       | 1225B                       | [3eff93bfb5](https://bsd-hardware.info/?probe=3eff93bfb5) | Mar 31, 2021 |
| Samsung       | N145P/N250P/N260P           | [a38a620353](https://bsd-hardware.info/?probe=a38a620353) | Mar 29, 2021 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [342e914968](https://bsd-hardware.info/?probe=342e914968) | Mar 29, 2021 |
| HP            | ProBook 455 G7              | [dd877e6c6c](https://bsd-hardware.info/?probe=dd877e6c6c) | Mar 27, 2021 |
| Samsung       | N145P/N250P/N260P           | [eff02dafe1](https://bsd-hardware.info/?probe=eff02dafe1) | Mar 18, 2021 |
| Lenovo        | ThinkPad T480s 20L7001HR... | [ebd44c21d9](https://bsd-hardware.info/?probe=ebd44c21d9) | Mar 17, 2021 |
| Samsung       | N150P                       | [68483fab9d](https://bsd-hardware.info/?probe=68483fab9d) | Mar 14, 2021 |
| Apple         | MacBookAir6,2               | [52584aaa97](https://bsd-hardware.info/?probe=52584aaa97) | Mar 14, 2021 |
| Apple         | MacBookAir6,2               | [fb136a79e7](https://bsd-hardware.info/?probe=fb136a79e7) | Mar 13, 2021 |
| Dell          | Latitude 3410               | [80d7bf959a](https://bsd-hardware.info/?probe=80d7bf959a) | Mar 10, 2021 |
| HP            | 255 G3                      | [861bdc647d](https://bsd-hardware.info/?probe=861bdc647d) | Mar 09, 2021 |
| HP            | ProBook 455 G7              | [1fcde7c0e1](https://bsd-hardware.info/?probe=1fcde7c0e1) | Mar 09, 2021 |
| HP            | 255 G3                      | [bd82ed65e9](https://bsd-hardware.info/?probe=bd82ed65e9) | Mar 07, 2021 |
| HP            | Compaq 6820s                | [f63d65b78c](https://bsd-hardware.info/?probe=f63d65b78c) | Feb 26, 2021 |
| Dell          | Studio 1537                 | [a4c1d361eb](https://bsd-hardware.info/?probe=a4c1d361eb) | Feb 23, 2021 |
| Apple         | MacBook5,1                  | [41ea02c8bc](https://bsd-hardware.info/?probe=41ea02c8bc) | Feb 21, 2021 |
| Apple         | MacBook5,1                  | [1a374f79df](https://bsd-hardware.info/?probe=1a374f79df) | Feb 19, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [ed75b3d15b](https://bsd-hardware.info/?probe=ed75b3d15b) | Feb 18, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [3df4abb2e9](https://bsd-hardware.info/?probe=3df4abb2e9) | Feb 16, 2021 |
| HP            | EliteBook 8460p             | [ada1119026](https://bsd-hardware.info/?probe=ada1119026) | Feb 14, 2021 |
| Lenovo        | ThinkPad T495s 20QKS1812... | [0e5e228d18](https://bsd-hardware.info/?probe=0e5e228d18) | Feb 13, 2021 |
| Lenovo        | ThinkPad T495s 20QKS1812... | [2d93a6bebc](https://bsd-hardware.info/?probe=2d93a6bebc) | Feb 13, 2021 |
| Sony          | VPCX115KX                   | [fef3d94e6c](https://bsd-hardware.info/?probe=fef3d94e6c) | Feb 12, 2021 |
| Acer          | Extensa 5635Z               | [3b4a7e7fc2](https://bsd-hardware.info/?probe=3b4a7e7fc2) | Feb 10, 2021 |
| Lenovo        | ThinkPad E480 20KN005CRT    | [503378cac9](https://bsd-hardware.info/?probe=503378cac9) | Jan 31, 2021 |
| Sony          | VPCM13M1R                   | [30bb4fc23c](https://bsd-hardware.info/?probe=30bb4fc23c) | Jan 06, 2021 |
| ASUSTek       | X101CH                      | [112792b300](https://bsd-hardware.info/?probe=112792b300) | Jan 02, 2021 |
| ASUSTek       | X101CH                      | [8b571cc947](https://bsd-hardware.info/?probe=8b571cc947) | Jan 02, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [0309e4ac24](https://bsd-hardware.info/?probe=0309e4ac24) | Dec 16, 2020 |
| Acer          | Aspire V5-122               | [ce0c079fd5](https://bsd-hardware.info/?probe=ce0c079fd5) | Dec 14, 2020 |
| Panasonic     | CF-19AHNC8FN                | [04a42812bb](https://bsd-hardware.info/?probe=04a42812bb) | Dec 11, 2020 |
| Lenovo        | IdeaPad L340-15API 81LW     | [3a78e7dc1a](https://bsd-hardware.info/?probe=3a78e7dc1a) | Dec 11, 2020 |
| Samsung       | N145P/N250P/N260P           | [b4cb55c681](https://bsd-hardware.info/?probe=b4cb55c681) | Dec 05, 2020 |
| Sony          | SVP1321V9RB                 | [9cddee6a0a](https://bsd-hardware.info/?probe=9cddee6a0a) | Dec 01, 2020 |
| Sony          | VGN-S150(UC)                | [f2f3923ea6](https://bsd-hardware.info/?probe=f2f3923ea6) | Nov 10, 2020 |
| Toshiba       | Satellite M100              | [e6e0a1294c](https://bsd-hardware.info/?probe=e6e0a1294c) | Nov 01, 2020 |
| Sony          | SVP1321V9RB                 | [3f414895be](https://bsd-hardware.info/?probe=3f414895be) | Oct 24, 2020 |
| Acer          | Aspire ES1-132              | [a4e45f3551](https://bsd-hardware.info/?probe=a4e45f3551) | Oct 22, 2020 |
| Dell          | Latitude C400               | [1dcc5e7972](https://bsd-hardware.info/?probe=1dcc5e7972) | Oct 21, 2020 |
| Dell          | Latitude C400               | [8330d23bd7](https://bsd-hardware.info/?probe=8330d23bd7) | Oct 21, 2020 |
| Google        | Chell                       | [4ffe68c199](https://bsd-hardware.info/?probe=4ffe68c199) | Oct 21, 2020 |
| Lenovo        | ThinkPad X230 2325Y36       | [b2e65dd4c5](https://bsd-hardware.info/?probe=b2e65dd4c5) | Oct 20, 2020 |
| Lenovo        | ThinkPad X240 20AL00DKRT    | [623801416c](https://bsd-hardware.info/?probe=623801416c) | Oct 20, 2020 |
| Lenovo        | ThinkPad T495s 20QKS1812... | [a3bc7a0c88](https://bsd-hardware.info/?probe=a3bc7a0c88) | Oct 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [4f54c8f399](https://bsd-hardware.info/?probe=4f54c8f399) | Oct 19, 2020 |
| HP            | OmniBook PC                 | [0e0656d228](https://bsd-hardware.info/?probe=0e0656d228) | Oct 19, 2020 |
| HP            | OmniBook PC                 | [60e72f1c10](https://bsd-hardware.info/?probe=60e72f1c10) | Oct 19, 2020 |
| Acer          | Aspire A315-42              | [1ac21e1660](https://bsd-hardware.info/?probe=1ac21e1660) | Oct 08, 2020 |
| Lenovo        | ThinkPad X230 2325Y36       | [1f28f1c311](https://bsd-hardware.info/?probe=1f28f1c311) | Aug 30, 2020 |
| Lenovo        | ThinkPad X230 2325Y36       | [11a0bbb73f](https://bsd-hardware.info/?probe=11a0bbb73f) | Aug 30, 2020 |
| Dell          | Inspiron 15-3567            | [4d1897ed1f](https://bsd-hardware.info/?probe=4d1897ed1f) | Aug 29, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [0e99e72ec9](https://bsd-hardware.info/?probe=0e99e72ec9) | Aug 26, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [b9477154b9](https://bsd-hardware.info/?probe=b9477154b9) | Aug 26, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [19d1c3d086](https://bsd-hardware.info/?probe=19d1c3d086) | Aug 20, 2020 |
| ASUSTek       | X71SL                       | [a2ee0c9edb](https://bsd-hardware.info/?probe=a2ee0c9edb) | Aug 15, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [bc97c1c0fa](https://bsd-hardware.info/?probe=bc97c1c0fa) | Aug 13, 2020 |
| Dell          | Inspiron 1501               | [9ee3e7cbc2](https://bsd-hardware.info/?probe=9ee3e7cbc2) | Aug 11, 2020 |
| Dell          | Inspiron 1501               | [807aae7095](https://bsd-hardware.info/?probe=807aae7095) | Aug 11, 2020 |
| Dell          | Inspiron 1525               | [d08ea3542e](https://bsd-hardware.info/?probe=d08ea3542e) | Aug 05, 2020 |
| Dell          | Latitude 7490               | [b1d5e8c619](https://bsd-hardware.info/?probe=b1d5e8c619) | Aug 05, 2020 |
| HP            | ProBook 440 G6              | [0227811abb](https://bsd-hardware.info/?probe=0227811abb) | Aug 05, 2020 |
| Lenovo        | ThinkPad T490s 20NX000DR... | [0919d8936f](https://bsd-hardware.info/?probe=0919d8936f) | Jul 27, 2020 |
| Lenovo        | G570 20079                  | [15e87049a7](https://bsd-hardware.info/?probe=15e87049a7) | Jul 27, 2020 |
| HP            | ProBook 430 G2              | [3a33aa0d8c](https://bsd-hardware.info/?probe=3a33aa0d8c) | Jun 30, 2020 |
| HP            | ProBook 430 G2              | [365ebdaf9c](https://bsd-hardware.info/?probe=365ebdaf9c) | Jun 30, 2020 |
| Lenovo        | G570 20079                  | [220313b249](https://bsd-hardware.info/?probe=220313b249) | Jun 03, 2020 |
| Lenovo        | G570 20079                  | [7042848932](https://bsd-hardware.info/?probe=7042848932) | Jun 03, 2020 |
| Lenovo        | G570 20079                  | [c7f3bf660a](https://bsd-hardware.info/?probe=c7f3bf660a) | Jun 02, 2020 |
| Lenovo        | G570 20079                  | [b84d1b49d8](https://bsd-hardware.info/?probe=b84d1b49d8) | Jun 02, 2020 |
| Lenovo        | G570 20079                  | [0cc3c53651](https://bsd-hardware.info/?probe=0cc3c53651) | Jun 02, 2020 |
| Dell          | Latitude E5400              | [54854343e4](https://bsd-hardware.info/?probe=54854343e4) | Jun 01, 2020 |
| Dell          | Latitude E6420              | [324265fe3f](https://bsd-hardware.info/?probe=324265fe3f) | May 31, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [68840c222b](https://bsd-hardware.info/?probe=68840c222b) | May 28, 2020 |
| Lenovo        | ThinkPad X240 20AMA52RUK    | [c65cdb97de](https://bsd-hardware.info/?probe=c65cdb97de) | May 28, 2020 |
| Acer          | Aspire 4820T                | [239eea83c6](https://bsd-hardware.info/?probe=239eea83c6) | May 26, 2020 |
| ASUSTek       | GL553VE                     | [dc7bb56859](https://bsd-hardware.info/?probe=dc7bb56859) | May 26, 2020 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [9728d93191](https://bsd-hardware.info/?probe=9728d93191) | May 25, 2020 |
| IBM           | ThinkPad X41 2525FAG        | [1e849f86cf](https://bsd-hardware.info/?probe=1e849f86cf) | May 25, 2020 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [709a3db7de](https://bsd-hardware.info/?probe=709a3db7de) | May 25, 2020 |
| Lenovo        | G570 20079                  | [0b7b4083bd](https://bsd-hardware.info/?probe=0b7b4083bd) | May 22, 2020 |
| Lenovo        | G570 20079                  | [f7cb1aa38d](https://bsd-hardware.info/?probe=f7cb1aa38d) | May 21, 2020 |
| Dell          | Latitude E6530              | [04cd35a77b](https://bsd-hardware.info/?probe=04cd35a77b) | May 21, 2020 |
| Lenovo        | G570 20079                  | [dc3c3cff26](https://bsd-hardware.info/?probe=dc3c3cff26) | May 21, 2020 |
| Lenovo        | G570 20079                  | [807f3398e3](https://bsd-hardware.info/?probe=807f3398e3) | May 20, 2020 |
| Lenovo        | G570 20079                  | [8212868b9f](https://bsd-hardware.info/?probe=8212868b9f) | May 19, 2020 |
| Lenovo        | G570 20079                  | [ab53dfc003](https://bsd-hardware.info/?probe=ab53dfc003) | May 19, 2020 |
| Lenovo        | G570 20079                  | [d3f180e9ef](https://bsd-hardware.info/?probe=d3f180e9ef) | May 17, 2020 |
| Lenovo        | G570 20079                  | [bdd93164cf](https://bsd-hardware.info/?probe=bdd93164cf) | May 17, 2020 |
| Lenovo        | G570 20079                  | [6a1b7867f0](https://bsd-hardware.info/?probe=6a1b7867f0) | May 16, 2020 |
| Lenovo        | G570 20079                  | [112b83a485](https://bsd-hardware.info/?probe=112b83a485) | May 16, 2020 |
| Lenovo        | G570 20079                  | [3258f01592](https://bsd-hardware.info/?probe=3258f01592) | May 16, 2020 |
| Lenovo        | G570 20079                  | [4a419328b8](https://bsd-hardware.info/?probe=4a419328b8) | May 16, 2020 |
| ASUSTek       | A3L                         | [6b65fcf9c1](https://bsd-hardware.info/?probe=6b65fcf9c1) | May 15, 2020 |
| ASUSTek       | A3L                         | [0d292bca2f](https://bsd-hardware.info/?probe=0d292bca2f) | May 15, 2020 |
| ASUSTek       | X71SL                       | [2fd46cb7c7](https://bsd-hardware.info/?probe=2fd46cb7c7) | May 15, 2020 |
| ASUSTek       | X71SL                       | [8a027d0a73](https://bsd-hardware.info/?probe=8a027d0a73) | May 14, 2020 |
| Dell          | Latitude E6530              | [2c5eec6613](https://bsd-hardware.info/?probe=2c5eec6613) | May 09, 2020 |
| Dell          | Latitude E6530              | [1542f8e5a8](https://bsd-hardware.info/?probe=1542f8e5a8) | May 09, 2020 |
| ASUSTek       | X71SL                       | [adf290251e](https://bsd-hardware.info/?probe=adf290251e) | May 09, 2020 |
| ASUSTek       | X71SL                       | [7b4d0958ec](https://bsd-hardware.info/?probe=7b4d0958ec) | May 09, 2020 |
| Sony          | SVE1713S1RW                 | [9a751ddfd8](https://bsd-hardware.info/?probe=9a751ddfd8) | May 08, 2020 |
| Lenovo        | G570 20079                  | [25fd1154c0](https://bsd-hardware.info/?probe=25fd1154c0) | May 08, 2020 |
| ASUSTek       | X71SL                       | [ab5297a63d](https://bsd-hardware.info/?probe=ab5297a63d) | May 07, 2020 |
| ASUSTek       | X71SL                       | [b8e364a2c0](https://bsd-hardware.info/?probe=b8e364a2c0) | May 07, 2020 |
| ASUSTek       | X71SL                       | [2aac4c3564](https://bsd-hardware.info/?probe=2aac4c3564) | May 07, 2020 |
| Lenovo        | G570 20079                  | [4909d93faf](https://bsd-hardware.info/?probe=4909d93faf) | May 06, 2020 |
| Lenovo        | G570 20079                  | [fb9c475d48](https://bsd-hardware.info/?probe=fb9c475d48) | May 06, 2020 |
| Lenovo        | G570 20079                  | [2efd2c4c7a](https://bsd-hardware.info/?probe=2efd2c4c7a) | May 06, 2020 |
| Lenovo        | G570 20079                  | [f1c2bcae9d](https://bsd-hardware.info/?probe=f1c2bcae9d) | May 06, 2020 |
| ASUSTek       | A3L                         | [0c73038abc](https://bsd-hardware.info/?probe=0c73038abc) | May 06, 2020 |
| ASUSTek       | A3L                         | [ff5b6e3024](https://bsd-hardware.info/?probe=ff5b6e3024) | May 06, 2020 |
| Lenovo        | G570 20079                  | [eff0d8a3db](https://bsd-hardware.info/?probe=eff0d8a3db) | May 06, 2020 |
| ASUSTek       | X71SL                       | [b48cb0f2ce](https://bsd-hardware.info/?probe=b48cb0f2ce) | May 05, 2020 |
| Lenovo        | G570 20079                  | [cd45078232](https://bsd-hardware.info/?probe=cd45078232) | May 05, 2020 |
| Lenovo        | G570 20079                  | [0370bc0522](https://bsd-hardware.info/?probe=0370bc0522) | May 02, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| helloSystem 0.7.0    | 15        | 7.54%   |
| helloSystem 0.8.1    | 14        | 7.04%   |
| OpenBSD 6.8          | 10        | 5.03%   |
| helloSystem 0.8.0    | 10        | 5.03%   |
| FreeBSD 13.1         | 10        | 5.03%   |
| FreeBSD 14.0-CURRENT | 8         | 4.02%   |
| OpenBSD 7.3          | 7         | 3.52%   |
| NomadBSD 1.3.2       | 7         | 3.52%   |
| FreeBSD 13.1-p5      | 7         | 3.52%   |
| FreeBSD 13.0         | 6         | 3.02%   |
| OpenBSD 7.1          | 5         | 2.51%   |
| helloSystem 0.8.2    | 5         | 2.51%   |
| FreeBSD 13.2         | 5         | 2.51%   |
| FreeBSD 13.0-CURRENT | 5         | 2.51%   |
| NomadBSD 5806f915    | 4         | 2.01%   |
| helloSystem 0.6.0    | 4         | 2.01%   |
| FreeBSD 12.1-STABLE  | 4         | 2.01%   |
| OpenBSD 6.9          | 3         | 1.51%   |
| GhostBSD 20.04.02    | 3         | 1.51%   |
| FreeBSD 13.2-RC3     | 3         | 1.51%   |
| FreeBSD 13.1-p1      | 3         | 1.51%   |
| FreeBSD 12.2-p4      | 3         | 1.51%   |
| OpenBSD 7.2          | 2         | 1.01%   |
| OpenBSD 6.7          | 2         | 1.01%   |
| NomadBSD 20221130    | 2         | 1.01%   |
| FreeBSD 13.0-p3      | 2         | 1.01%   |
| FreeBSD 12.3-STABLE  | 2         | 1.01%   |
| FreeBSD 12.2-STABLE  | 2         | 1.01%   |
| FreeBSD 12.2-p3      | 2         | 1.01%   |
| FreeBSD 12.1-p8      | 2         | 1.01%   |
| FreeBSD 12.1-p7      | 2         | 1.01%   |
| FreeBSD 12.1-p5      | 2         | 1.01%   |
| OS108 9.0            | 1         | 0.5%    |
| OpenBSD 7.0          | 1         | 0.5%    |
| NomadBSD 1.4         | 1         | 0.5%    |
| NomadBSD 1.3.1       | 1         | 0.5%    |
| NetBSD 9.99.94       | 1         | 0.5%    |
| NetBSD 9.1           | 1         | 0.5%    |
| NetBSD 7.2           | 1         | 0.5%    |
| LibertyBSD 6.1       | 1         | 0.5%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 83        | 44.86%  |
| helloSystem | 47        | 25.41%  |
| OpenBSD     | 28        | 15.14%  |
| NomadBSD    | 14        | 7.57%   |
| GhostBSD    | 7         | 3.78%   |
| NetBSD      | 3         | 1.62%   |
| OS108       | 1         | 0.54%   |
| LibertyBSD  | 1         | 0.54%   |
| FuguIta     | 1         | 0.54%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 155       | 89.08%  |
| i386  | 19        | 10.92%  |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| helloDesktop  | 60        | 32.09%  |
| KDE5          | 23        | 12.3%   |
| Console       | 18        | 9.63%   |
| XFCE          | 16        | 8.56%   |
| Openbox       | 14        | 7.49%   |
| fvwm          | 13        | 6.95%   |
| MATE          | 10        | 5.35%   |
| GNOME         | 10        | 5.35%   |
| TWM           | 6         | 3.21%   |
| IceWM         | 3         | 1.6%    |
| i3            | 3         | 1.6%    |
| LXQt          | 2         | 1.07%   |
| LXDE          | 2         | 1.07%   |
| AwesomeWM     | 2         | 1.07%   |
| xinitrc       | 1         | 0.53%   |
| StumpWM       | 1         | 0.53%   |
| Lumina        | 1         | 0.53%   |
| Enlightenment | 1         | 0.53%   |
| DWM           | 1         | 0.53%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 155       | 86.11%  |
| Console | 23        | 12.78%  |
| Wayland | 2         | 1.11%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 72        | 39.56%  |
| Console | 66        | 36.26%  |
| SDDM    | 22        | 12.09%  |
| LightDM | 10        | 5.49%   |
| XDM     | 6         | 3.3%    |
| GDM     | 4         | 2.2%    |
| PCDM    | 1         | 0.55%   |
| Ly      | 1         | 0.55%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| ru_RU   | 61        | 32.97%  |
| en_US   | 45        | 24.32%  |
| Unknown | 37        | 20%     |
| C       | 34        | 18.38%  |
| ru      | 4         | 2.16%   |
| en_GB   | 1         | 0.54%   |
| en_EN   | 1         | 0.54%   |
| en      | 1         | 0.54%   |
| ba_RU   | 1         | 0.54%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 127       | 70.95%  |
| BIOS | 52        | 29.05%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 79        | 42.93%  |
| Ufs    | 55        | 29.89%  |
| Ffs    | 30        | 16.3%   |
| Cd9660 | 19        | 10.33%  |
| Xfs    | 1         | 0.54%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 140       | 79.1%   |
| MBR     | 34        | 19.21%  |
| Unknown | 2         | 1.13%   |
| BSD     | 1         | 0.56%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 49        | 28.16%  |
| ASUSTek Computer    | 21        | 12.07%  |
| Dell                | 20        | 11.49%  |
| Hewlett-Packard     | 18        | 10.34%  |
| Acer                | 15        | 8.62%   |
| Samsung Electronics | 8         | 4.6%    |
| Sony                | 6         | 3.45%   |
| MSI                 | 5         | 2.87%   |
| HUAWEI              | 4         | 2.3%    |
| Toshiba             | 3         | 1.72%   |
| Timi                | 3         | 1.72%   |
| IBM                 | 3         | 1.72%   |
| F-Plus Mobile       | 3         | 1.72%   |
| Apple               | 3         | 1.72%   |
| HMT                 | 2         | 1.15%   |
| Panasonic           | 1         | 0.57%   |
| Packard Bell        | 1         | 0.57%   |
| Kraftway            | 1         | 0.57%   |
| Irbis               | 1         | 0.57%   |
| IP3 Technology      | 1         | 0.57%   |
| Intel               | 1         | 0.57%   |
| Google              | 1         | 0.57%   |
| Fujitsu Siemens     | 1         | 0.57%   |
| eMachines           | 1         | 0.57%   |
| DNS                 | 1         | 0.57%   |
| DEXP                | 1         | 0.57%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| F-Plus Mobile FLAPTOP r             | 3         | 1.72%   |
| Samsung N145P/N250P/N260P           | 2         | 1.15%   |
| MSI PS63 Modern 8M                  | 2         | 1.15%   |
| Lenovo IdeaPad 330-15ARR 81D2       | 2         | 1.15%   |
| Lenovo IdeaPad 320-15ISK 80XH       | 2         | 1.15%   |
| Lenovo G570 20079                   | 2         | 1.15%   |
| HUAWEI CREM-WXX9                    | 2         | 1.15%   |
| HMT W041-TF-A-45                    | 2         | 1.15%   |
| Dell Inspiron 15 7000 Gaming        | 2         | 1.15%   |
| Acer Aspire 4820T                   | 2         | 1.15%   |
| Toshiba Satellite M100              | 1         | 0.57%   |
| Toshiba Satellite L40               | 1         | 0.57%   |
| Toshiba Satellite A300              | 1         | 0.57%   |
| Timi TM1612                         | 1         | 0.57%   |
| Timi TM1607                         | 1         | 0.57%   |
| Timi Redmi Book Pro 14 2022         | 1         | 0.57%   |
| Sony VPCX115KX                      | 1         | 0.57%   |
| Sony VPCM13M1R                      | 1         | 0.57%   |
| Sony VGN-UX1XRN                     | 1         | 0.57%   |
| Sony VGN-S150(UC)                   | 1         | 0.57%   |
| Sony SVP1321V9RB                    | 1         | 0.57%   |
| Sony SVE1713S1RW                    | 1         | 0.57%   |
| Samsung R530/R730/R540              | 1         | 0.57%   |
| Samsung R468/R418                   | 1         | 0.57%   |
| Samsung Q430/Q530                   | 1         | 0.57%   |
| Samsung NC110P/NC108P/NC111P        | 1         | 0.57%   |
| Samsung N150P                       | 1         | 0.57%   |
| Samsung 305E4A/305E5A/305E7A        | 1         | 0.57%   |
| Panasonic CF-19AHNC8FN              | 1         | 0.57%   |
| Packard Bell EasyNote TE69HW        | 1         | 0.57%   |
| MSI Sword 17 A11UD                  | 1         | 0.57%   |
| MSI GE75 Raider 10SFS               | 1         | 0.57%   |
| MSI GE62 6QC                        | 1         | 0.57%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS  | 1         | 0.57%   |
| Lenovo V580 20147                   | 1         | 0.57%   |
| Lenovo ThinkPad Yoga 260 20FES1K81V | 1         | 0.57%   |
| Lenovo ThinkPad X240 20AMA52RUK     | 1         | 0.57%   |
| Lenovo ThinkPad X240 20AL00DKRT     | 1         | 0.57%   |
| Lenovo ThinkPad X230 2325Y36        | 1         | 0.57%   |
| Lenovo ThinkPad X220 4291LF6        | 1         | 0.57%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 26        | 14.94%  |
| Acer Aspire            | 13        | 7.47%   |
| Lenovo IdeaPad         | 12        | 6.9%    |
| Dell Inspiron          | 8         | 4.6%    |
| Dell Latitude          | 7         | 4.02%   |
| HP ProBook             | 6         | 3.45%   |
| HP Laptop              | 4         | 2.3%    |
| ASUS VivoBook          | 4         | 2.3%    |
| Toshiba Satellite      | 3         | 1.72%   |
| IBM ThinkPad           | 3         | 1.72%   |
| F-Plus Mobile FLAPTOP  | 3         | 1.72%   |
| Samsung N145P          | 2         | 1.15%   |
| MSI PS63               | 2         | 1.15%   |
| Lenovo ThinkBook       | 2         | 1.15%   |
| Lenovo G570            | 2         | 1.15%   |
| HUAWEI CREM-WXX9       | 2         | 1.15%   |
| HMT W041-TF-A-45       | 2         | 1.15%   |
| HP Pavilion            | 2         | 1.15%   |
| HP EliteBook           | 2         | 1.15%   |
| Acer Extensa           | 2         | 1.15%   |
| Timi TM1612            | 1         | 0.57%   |
| Timi TM1607            | 1         | 0.57%   |
| Timi Redmi             | 1         | 0.57%   |
| Sony VPCX115KX         | 1         | 0.57%   |
| Sony VPCM13M1R         | 1         | 0.57%   |
| Sony VGN-UX1XRN        | 1         | 0.57%   |
| Sony VGN-S150(UC)      | 1         | 0.57%   |
| Sony SVP1321V9RB       | 1         | 0.57%   |
| Sony SVE1713S1RW       | 1         | 0.57%   |
| Samsung R530           | 1         | 0.57%   |
| Samsung R468           | 1         | 0.57%   |
| Samsung Q430           | 1         | 0.57%   |
| Samsung NC110P         | 1         | 0.57%   |
| Samsung N150P          | 1         | 0.57%   |
| Samsung 305E4A         | 1         | 0.57%   |
| Panasonic CF-19AHNC8FN | 1         | 0.57%   |
| Packard Bell EasyNote  | 1         | 0.57%   |
| MSI Sword              | 1         | 0.57%   |
| MSI GE75               | 1         | 0.57%   |
| MSI GE62               | 1         | 0.57%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 19        | 10.92%  |
| 2022 | 18        | 10.34%  |
| 2020 | 17        | 9.77%   |
| 2011 | 15        | 8.62%   |
| 2012 | 13        | 7.47%   |
| 2021 | 12        | 6.9%    |
| 2010 | 11        | 6.32%   |
| 2018 | 10        | 5.75%   |
| 2017 | 9         | 5.17%   |
| 2016 | 8         | 4.6%    |
| 2009 | 7         | 4.02%   |
| 2015 | 6         | 3.45%   |
| 2014 | 6         | 3.45%   |
| 2008 | 6         | 3.45%   |
| 2013 | 4         | 2.3%    |
| 2006 | 4         | 2.3%    |
| 2007 | 3         | 1.72%   |
| 2005 | 2         | 1.15%   |
| 2004 | 2         | 1.15%   |
| 2023 | 1         | 0.57%   |
| 2003 | 1         | 0.57%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 174       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 173       | 99.43%  |
| Yes  | 1         | 0.57%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 49        | 27.68%  |
| 4.01-8.0    | 46        | 25.99%  |
| 16.01-24.0  | 41        | 23.16%  |
| 2.01-3.0    | 17        | 9.6%    |
| 0.51-1.0    | 6         | 3.39%   |
| 1.01-2.0    | 5         | 2.82%   |
| 32.01-64.0  | 4         | 2.26%   |
| 24.01-32.0  | 3         | 1.69%   |
| 0.01-0.5    | 3         | 1.69%   |
| 3.01-4.0    | 2         | 1.13%   |
| 64.01-256.0 | 1         | 0.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 97        | 53.3%   |
| 0.51-1.0   | 47        | 25.82%  |
| 1.01-2.0   | 15        | 8.24%   |
| 2.01-3.0   | 8         | 4.4%    |
| 0          | 5         | 2.75%   |
| Unknown    | 5         | 2.75%   |
| 4.01-8.0   | 3         | 1.65%   |
| 24.01-32.0 | 1         | 0.55%   |
| 8.01-16.0  | 1         | 0.55%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 130       | 71.43%  |
| 2      | 40        | 21.98%  |
| 0      | 7         | 3.85%   |
| 4      | 3         | 1.65%   |
| 3      | 2         | 1.1%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 140       | 80.46%  |
| Yes       | 34        | 19.54%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 137       | 78.74%  |
| No        | 37        | 21.26%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 169       | 97.13%  |
| No        | 5         | 2.87%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 121       | 69.14%  |
| No        | 54        | 30.86%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Russia  | 174       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Moscow           | 64        | 35.75%  |
| St Petersburg    | 24        | 13.41%  |
| Novosibirsk      | 7         | 3.91%   |
| Vladivostok      | 6         | 3.35%   |
| Yekaterinburg    | 5         | 2.79%   |
| Ulyanovsk        | 4         | 2.23%   |
| Ufa              | 3         | 1.68%   |
| Tyumen           | 3         | 1.68%   |
| Tolyatti         | 3         | 1.68%   |
| Saratov          | 3         | 1.68%   |
| Perm             | 3         | 1.68%   |
| Krasnoyarsk      | 3         | 1.68%   |
| Chelyabinsk      | 3         | 1.68%   |
| Tsarskoye Selo   | 2         | 1.12%   |
| Krasnodar        | 2         | 1.12%   |
| Kirov            | 2         | 1.12%   |
| Kaliningrad      | 2         | 1.12%   |
| Irkutsk          | 2         | 1.12%   |
| Chita            | 2         | 1.12%   |
| Zhukovskiy       | 1         | 0.56%   |
| Yoshkar-Ola      | 1         | 0.56%   |
| Yegorlykskaya    | 1         | 0.56%   |
| Yaroslavl        | 1         | 0.56%   |
| Vorkuta          | 1         | 0.56%   |
| Vladimir         | 1         | 0.56%   |
| Vidnoye          | 1         | 0.56%   |
| Ust'-Luga        | 1         | 0.56%   |
| Surgut           | 1         | 0.56%   |
| Smolensk         | 1         | 0.56%   |
| Sevastopol'      | 1         | 0.56%   |
| Rostov-on-Don    | 1         | 0.56%   |
| Pushkino         | 1         | 0.56%   |
| Penza            | 1         | 0.56%   |
| Ozersk           | 1         | 0.56%   |
| Oryol            | 1         | 0.56%   |
| Omsk             | 1         | 0.56%   |
| Obninsk          | 1         | 0.56%   |
| Nizhniy Novgorod | 1         | 0.56%   |
| Mytishchi        | 1         | 0.56%   |
| Minusinsk        | 1         | 0.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 37        | 45     | 17.79%  |
| Seagate             | 21        | 25     | 10.1%   |
| Samsung Electronics | 21        | 26     | 10.1%   |
| Toshiba             | 16        | 17     | 7.69%   |
| SanDisk             | 11        | 13     | 5.29%   |
| Hitachi             | 11        | 13     | 5.29%   |
| SK hynix            | 9         | 10     | 4.33%   |
| Intel               | 9         | 12     | 4.33%   |
| Kingston            | 8         | 10     | 3.85%   |
| Micron Technology   | 5         | 5      | 2.4%    |
| HGST                | 5         | 7      | 2.4%    |
| FORESEE             | 5         | 6      | 2.4%    |
| Transcend           | 4         | 4      | 1.92%   |
| SPCC                | 4         | 5      | 1.92%   |
| NVMe                | 4         | 4      | 1.92%   |
| Gigabyte Technology | 3         | 6      | 1.44%   |
| A-DATA Technology   | 3         | 3      | 1.44%   |
| UMIS                | 2         | 2      | 0.96%   |
| KIOXIA              | 2         | 2      | 0.96%   |
| JetFlash            | 2         | 2      | 0.96%   |
| Innostor            | 2         | 2      | 0.96%   |
| Apple               | 2         | 2      | 0.96%   |
| Apacer              | 2         | 2      | 0.96%   |
| USB                 | 1         | 1      | 0.48%   |
| Union Memory        | 1         | 1      | 0.48%   |
| UFD 2.0             | 1         | 1      | 0.48%   |
| SSSTC               | 1         | 1      | 0.48%   |
| Smartbuy            | 1         | 1      | 0.48%   |
| Silicon Motion      | 1         | 1      | 0.48%   |
| SETHRISE            | 1         | 1      | 0.48%   |
| Phison              | 1         | 1      | 0.48%   |
| Patriot             | 1         | 1      | 0.48%   |
| OCZ                 | 1         | 2      | 0.48%   |
| Netac               | 1         | 1      | 0.48%   |
| Lenovo              | 1         | 1      | 0.48%   |
| KLLISRE             | 1         | 1      | 0.48%   |
| KINGBANK            | 1         | 1      | 0.48%   |
| Hoodisk             | 1         | 1      | 0.48%   |
| Hewlett-Packard     | 1         | 1      | 0.48%   |
| Goldenfir           | 1         | 1      | 0.48%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB             | 4         | 1.84%   |
| Seagate ST1000LM035-1RK172 1TB       | 4         | 1.84%   |
| FORESEE XP1000F001T 1TB              | 4         | 1.84%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 3         | 1.38%   |
| Kingston SV300S37A120G 120GB         | 3         | 1.38%   |
| HGST HTS721010A9E630 1TB             | 3         | 1.38%   |
| WDC WDS240G2G0A-00JH30 240GB         | 2         | 0.92%   |
| WDC WD5000LPVX-60V0TT0 500GB         | 2         | 0.92%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 2         | 0.92%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 2         | 0.92%   |
| WDC WD2500BEVT-22A23T0 250GB         | 2         | 0.92%   |
| WDC WD10SPZX-08Z10 1TB               | 2         | 0.92%   |
| WDC WD10JPVX-22JC3T0 1TB             | 2         | 0.92%   |
| WDC PC SN730 SDBPNTY-512G            | 2         | 0.92%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB | 2         | 0.92%   |
| Toshiba MQ04ABF100 1TB               | 2         | 0.92%   |
| Toshiba MQ01ABD100 1TB               | 2         | 0.92%   |
| Seagate ST9500325AS 500GB            | 2         | 0.92%   |
| Seagate ST500LT012-1DG142 500GB      | 2         | 0.92%   |
| Seagate ST500LM021-1KJ152 500GB      | 2         | 0.92%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 0.92%   |
| Samsung SSD 860 EVO 250GB            | 2         | 0.92%   |
| Samsung MZNTY128HDHP-00000 128GB     | 2         | 0.92%   |
| Micron 1100 SATA 256GB               | 2         | 0.92%   |
| Kingston SA400S37120G 120GB          | 2         | 0.92%   |
| Intel SSDPEKNU512GZ 512GB            | 2         | 0.92%   |
| Innostor SSD 15GB                    | 2         | 0.92%   |
| Hitachi HDS721616PLA380 160GB        | 2         | 0.92%   |
| Gigabyte GP-AG42TB                   | 2         | 0.92%   |
| A-DATA SX6000LNP 512GB               | 2         | 0.92%   |
| WDC WDS500G2B0A-00SM50 500GB         | 1         | 0.46%   |
| WDC WDS240G1G0B-00RC30 240GB         | 1         | 0.46%   |
| WDC WDS120G2G0A-00JH30 120GB         | 1         | 0.46%   |
| WDC WDS100T3X0C-00SJG0 1TB           | 1         | 0.46%   |
| WDC WD5000LPLX-60ZNTT1 500GB         | 1         | 0.46%   |
| WDC WD5000LPLX-00ZNTT0 500GB         | 1         | 0.46%   |
| WDC WD5000BPVT-24HXZT3 500GB         | 1         | 0.46%   |
| WDC WD3200BPVT-80ZEST0 320GB         | 1         | 0.46%   |
| WDC WD3200BPVT-24JJ5T0 320GB         | 1         | 0.46%   |
| WDC WD20SPZX-00UA7T0 2TB             | 1         | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 22        | 24     | 26.51%  |
| Seagate             | 21        | 25     | 25.3%   |
| Toshiba             | 14        | 15     | 16.87%  |
| Hitachi             | 11        | 13     | 13.25%  |
| HGST                | 5         | 7      | 6.02%   |
| NVMe                | 3         | 3      | 3.61%   |
| Samsung Electronics | 2         | 2      | 2.41%   |
| JetFlash            | 2         | 2      | 2.41%   |
| USB                 | 1         | 1      | 1.2%    |
| UFD 2.0             | 1         | 1      | 1.2%    |
| Fujitsu             | 1         | 1      | 1.2%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 16     | 17.57%  |
| SanDisk             | 11        | 13     | 14.86%  |
| Kingston            | 7         | 9      | 9.46%   |
| WDC                 | 5         | 6      | 6.76%   |
| Intel               | 5         | 7      | 6.76%   |
| SPCC                | 4         | 5      | 5.41%   |
| Transcend           | 3         | 3      | 4.05%   |
| Micron Technology   | 3         | 3      | 4.05%   |
| SK hynix            | 2         | 2      | 2.7%    |
| Innostor            | 2         | 2      | 2.7%    |
| Apple               | 2         | 2      | 2.7%    |
| Apacer              | 2         | 2      | 2.7%    |
| Union Memory        | 1         | 1      | 1.35%   |
| Smartbuy            | 1         | 1      | 1.35%   |
| SETHRISE            | 1         | 1      | 1.35%   |
| Patriot             | 1         | 1      | 1.35%   |
| OCZ                 | 1         | 2      | 1.35%   |
| NVMe                | 1         | 1      | 1.35%   |
| Netac               | 1         | 1      | 1.35%   |
| KLLISRE             | 1         | 1      | 1.35%   |
| Hewlett-Packard     | 1         | 1      | 1.35%   |
| Goldenfir           | 1         | 1      | 1.35%   |
| Gigabyte Technology | 1         | 3      | 1.35%   |
| FORESEE             | 1         | 2      | 1.35%   |
| ASUSTek Computer    | 1         | 2      | 1.35%   |
| AMD                 | 1         | 1      | 1.35%   |
| A-DATA Technology   | 1         | 1      | 1.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 74        | 94     | 38.34%  |
| SSD  | 67        | 90     | 34.72%  |
| NVMe | 52        | 61     | 26.94%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 127       | 184    | 70.95%  |
| NVMe | 52        | 61     | 29.05%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Notebooks | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 104       | 143    | 74.29%  |
| 0.51-1.0        | 32        | 37     | 22.86%  |
| 1.01-2.0        | 3         | 3      | 2.14%   |
| More than 100.0 | 1         | 1      | 0.71%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 49        | 26.2%   |
| 1-20       | 45        | 24.06%  |
| 251-500    | 42        | 22.46%  |
| 501-1000   | 17        | 9.09%   |
| 21-50      | 14        | 7.49%   |
| 51-100     | 13        | 6.95%   |
| 1001-2000  | 5         | 2.67%   |
| Unknown    | 2         | 1.07%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 140       | 77.78%  |
| 21-50    | 16        | 8.89%   |
| 101-250  | 12        | 6.67%   |
| 51-100   | 7         | 3.89%   |
| 251-500  | 2         | 1.11%   |
| Unknown  | 2         | 1.11%   |
| 501-1000 | 1         | 0.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABF050 500GB            | 2         | 2      | 5.56%   |
| Seagate ST500LT012-1DG142 500GB     | 2         | 2      | 5.56%   |
| Micron Technology 1100 SATA 256GB   | 2         | 2      | 5.56%   |
| WDC WD5000LPLX-60ZNTT1 500GB        | 1         | 1      | 2.78%   |
| WDC WD3200BPVT-80ZEST0 320GB        | 1         | 1      | 2.78%   |
| WDC WD2000JB-00GVC0 200GB           | 1         | 1      | 2.78%   |
| Toshiba MQ01ABD100 1TB              | 1         | 1      | 2.78%   |
| Toshiba MK7575GSX 752GB             | 1         | 1      | 2.78%   |
| Toshiba MK2546GSX 250GB             | 1         | 1      | 2.78%   |
| Toshiba MK1646GSX 160GB             | 1         | 1      | 2.78%   |
| Seagate ST9500325AS 500GB           | 1         | 1      | 2.78%   |
| Seagate ST9320325AS 320GB           | 1         | 1      | 2.78%   |
| Seagate ST9250320AS 250GB           | 1         | 1      | 2.78%   |
| Seagate ST500LM021-1KJ152 500GB     | 1         | 1      | 2.78%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1      | 2.78%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1         | 1      | 2.78%   |
| Samsung Electronics HM080HI 80GB    | 1         | 1      | 2.78%   |
| Kingston SV300S37A120G 120GB        | 1         | 1      | 2.78%   |
| Intel SSDSC2KW120H6 120GB           | 1         | 1      | 2.78%   |
| Intel SSDSC2CW060A3 64GB            | 1         | 1      | 2.78%   |
| Intel SSDSC2BW480H6 480GB           | 1         | 1      | 2.78%   |
| Intel SSDSC2BB480G7 480GB           | 1         | 1      | 2.78%   |
| Hitachi HTS725025A9A364 250GB       | 1         | 1      | 2.78%   |
| Hitachi HTS721060G9AT00 64GB        | 1         | 1      | 2.78%   |
| Hitachi HTS547564A9E384 640GB       | 1         | 1      | 2.78%   |
| Hitachi HTS547550A9E384 500GB       | 1         | 1      | 2.78%   |
| Hitachi HTS541616J9SA00 160GB       | 1         | 1      | 2.78%   |
| Hitachi HTS541612J9SA00 120GB       | 1         | 1      | 2.78%   |
| Hitachi HTC426060G9AT00 64GB        | 1         | 1      | 2.78%   |
| Hitachi DK23AA-12 12GB              | 1         | 1      | 2.78%   |
| HGST HTS541075A7E630 752GB          | 1         | 2      | 2.78%   |
| HGST HTE725032A7E630 320GB          | 1         | 1      | 2.78%   |
| Apple SSD SD0128F 121GB             | 1         | 1      | 2.78%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 22.22%  |
| Hitachi             | 8         | 8      | 22.22%  |
| Toshiba             | 6         | 6      | 16.67%  |
| Intel               | 4         | 4      | 11.11%  |
| WDC                 | 3         | 3      | 8.33%   |
| Micron Technology   | 2         | 2      | 5.56%   |
| HGST                | 2         | 3      | 5.56%   |
| Samsung Electronics | 1         | 1      | 2.78%   |
| Kingston            | 1         | 1      | 2.78%   |
| Apple               | 1         | 1      | 2.78%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 28.57%  |
| Hitachi             | 8         | 8      | 28.57%  |
| Toshiba             | 6         | 6      | 21.43%  |
| WDC                 | 3         | 3      | 10.71%  |
| HGST                | 2         | 3      | 7.14%   |
| Samsung Electronics | 1         | 1      | 3.57%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 28        | 29     | 77.78%  |
| SSD  | 8         | 8      | 22.22%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| SanDisk pSSD 256GB            | 1         | 1      | 50%     |
| Hitachi HTS545025B9A300 250GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SanDisk | 1         | 1      | 50%     |
| Hitachi | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 140       | 197    | 75.27%  |
| Malfunc  | 36        | 37     | 19.35%  |
| Detected | 8         | 9      | 4.3%    |
| Failed   | 2         | 2      | 1.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 119       | 59.8%   |
| AMD                                     | 24        | 12.06%  |
| SanDisk                                 | 11        | 5.53%   |
| SK hynix                                | 8         | 4.02%   |
| Samsung Electronics                     | 8         | 4.02%   |
| Shenzhen Longsys Electronics            | 4         | 2.01%   |
| Phison Electronics                      | 4         | 2.01%   |
| KIOXIA                                  | 3         | 1.51%   |
| Silicon Motion                          | 2         | 1.01%   |
| Realtek Semiconductor                   | 2         | 1.01%   |
| Nvidia                                  | 2         | 1.01%   |
| Micron Technology                       | 2         | 1.01%   |
| Union Memory (Shenzhen)                 | 1         | 0.5%    |
| Transcend                               | 1         | 0.5%    |
| Toshiba                                 | 1         | 0.5%    |
| Solid State Storage Technology          | 1         | 0.5%    |
| Silicon Integrated Systems [SiS]        | 1         | 0.5%    |
| Shenzhen Unionmemory Information System | 1         | 0.5%    |
| Marvell Technology Group                | 1         | 0.5%    |
| Lenovo                                  | 1         | 0.5%    |
| Kingston Technology Company             | 1         | 0.5%    |
| JMicron Technology                      | 1         | 0.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 20        | 9.62%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 13        | 6.25%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 11        | 5.29%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 8         | 3.85%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 7         | 3.37%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 7         | 3.37%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 7         | 3.37%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 6         | 2.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 5         | 2.4%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 5         | 2.4%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 5         | 2.4%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 5         | 2.4%    |
| SK hynix BC501 NVMe Solid State Drive                                            | 4         | 1.92%   |
| Shenzhen Longsys Lexar NM620 NVME SSD (DRAM-less)                                | 4         | 1.92%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 4         | 1.92%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 4         | 1.92%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 4         | 1.92%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 1.92%   |
| Intel 82801FBM (ICH6M) SATA Controller                                           | 4         | 1.92%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                            | 3         | 1.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 1.44%   |
| Intel Tiger Lake-LP SATA Controller                                              | 3         | 1.44%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 1.44%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 1.44%   |
| SK hynix BC511 NVMe SSD                                                          | 2         | 0.96%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 2         | 0.96%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                                | 2         | 0.96%   |
| Phison PS5013 E13 NVMe Controller                                                | 2         | 0.96%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 2         | 0.96%   |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 0.96%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 2         | 0.96%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 0.96%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 0.96%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 2         | 0.96%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 2         | 0.96%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 0.96%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 0.96%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 2         | 0.96%   |
| Intel 82801CAM IDE U100 Controller                                               | 2         | 0.96%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 0.96%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 124       | 60.78%  |
| NVMe | 52        | 25.49%  |
| IDE  | 21        | 10.29%  |
| RAID | 7         | 3.43%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 132       | 75.43%  |
| AMD    | 42        | 24%     |
| 11th   | 1         | 0.57%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Intel Core i3-6006U CPU @ 2.00GHz                                   | 6         | 3.37%   |
| Intel CPU Version                                                   | 4         | 2.25%   |
| Intel Core i7-8565U CPU @ 1.80GHz                                   | 4         | 2.25%   |
| Intel Core i3 CPU M 350 @ 2.27GHz                                   | 3         | 1.69%   |
| Intel C1                                                            | 3         | 1.69%   |
| AMD Ryzen 7 5825U with Radeon Graphics                              | 3         | 1.69%   |
| AMD Ryzen 7 5800H with Radeon Graphics                              | 3         | 1.69%   |
| Intel Pentium M processor 1.60GHz                                   | 2         | 1.12%   |
| Intel Pentium M processor                                           | 2         | 1.12%   |
| Intel Pentium CPU N4200 @ 1.10GHz                                   | 2         | 1.12%   |
| Intel Genuine CPU                                                   | 2         | 1.12%   |
| Intel Core i7-8665U CPU @ 1.90GHz                                   | 2         | 1.12%   |
| Intel Core i7-8550U CPU @ 1.80GHz                                   | 2         | 1.12%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz                                  | 2         | 1.12%   |
| Intel Core i5-3320M CPU @ 2.60GHz                                   | 2         | 1.12%   |
| Intel Core i5-2520M CPU @ 2.50GHz                                   | 2         | 1.12%   |
| Intel Core i5-2430M CPU @ 2.40GHz                                   | 2         | 1.12%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz                                | 2         | 1.12%   |
| Intel Core 2 Duo                                                    | 2         | 1.12%   |
| Intel Celeron CPU N3350 @ 1.10GHz                                   | 2         | 1.12%   |
| Intel Celeron CPU N3060 @ 1.60GHz                                   | 2         | 1.12%   |
| Intel Atom CPU N570 @ 1.66GHz                                       | 2         | 1.12%   |
| Intel 686-class                                                     | 2         | 1.12%   |
| AMD Ryzen 7 6800H with Radeon Graphics                              | 2         | 1.12%   |
| AMD Ryzen 7 5800U with Radeon Graphics                              | 2         | 1.12%   |
| AMD Ryzen 7 4700U with Radeon Graphics                              | 2         | 1.12%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx                       | 2         | 1.12%   |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx                       | 2         | 1.12%   |
| Intel Xeon W-10885M CPU @ 2.40GHz                                   | 1         | 0.56%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz                                | 1         | 0.56%   |
| Intel Pentium Silver N6000 @ 1.10GHz                                | 1         | 0.56%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz                            | 1         | 0.56%   |
| Intel Pentium M processor 1.86GHz ("GenuineIntel" 686-class)        | 1         | 0.56%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz                         | 1         | 0.56%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz                         | 1         | 0.56%   |
| Intel Pentium CPU N3700 @ 1.60GHz                                   | 1         | 0.56%   |
| Intel Pentium CPU N3530 @ 2.16GHz                                   | 1         | 0.56%   |
| Intel Pentium CPU 4417U @ 2.30GHz                                   | 1         | 0.56%   |
| Intel Mobile Pentium III CPU - M 1200MHz ("GenuineIntel" 686-class) | 1         | 0.56%   |
| Intel Mobile Pentium III CPU - M 1000MHz ("GenuineIntel" 686-class) | 1         | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 31        | 17.61%  |
| Intel Core i7           | 20        | 11.36%  |
| Other                   | 14        | 7.95%   |
| Intel Core i3           | 14        | 7.95%   |
| AMD Ryzen 7             | 14        | 7.95%   |
| Intel Celeron           | 9         | 5.11%   |
| Intel Atom              | 8         | 4.55%   |
| Intel Core 2 Duo        | 7         | 3.98%   |
| AMD Ryzen 3             | 7         | 3.98%   |
| AMD Ryzen 5             | 6         | 3.41%   |
| Intel Pentium M         | 5         | 2.84%   |
| Intel Pentium           | 5         | 2.84%   |
| Intel Genuine           | 5         | 2.84%   |
| AMD Ryzen 7 PRO         | 3         | 1.7%    |
| AMD E                   | 3         | 1.7%    |
| AMD A6                  | 3         | 1.7%    |
| Intel Xeon              | 2         | 1.14%   |
| Intel Pentium Silver    | 2         | 1.14%   |
| Intel Pentium Dual-Core | 2         | 1.14%   |
| Intel Core m3           | 2         | 1.14%   |
| Intel 686-class         | 2         | 1.14%   |
| Intel Core Solo         | 1         | 0.57%   |
| Intel Core m5           | 1         | 0.57%   |
| Intel Core M            | 1         | 0.57%   |
| Intel Core i9           | 1         | 0.57%   |
| Intel Celeron M         | 1         | 0.57%   |
| Intel Celeron Dual-Core | 1         | 0.57%   |
| AMD Ryzen 9             | 1         | 0.57%   |
| AMD E2                  | 1         | 0.57%   |
| AMD E1                  | 1         | 0.57%   |
| AMD C-60                | 1         | 0.57%   |
| AMD A8                  | 1         | 0.57%   |
| AMD A10                 | 1         | 0.57%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 72        | 40.45%  |
| 4       | 44        | 24.72%  |
| Unknown | 18        | 10.11%  |
| 16      | 14        | 7.87%   |
| 1       | 14        | 7.87%   |
| 8       | 9         | 5.06%   |
| 12      | 4         | 2.25%   |
| 6       | 3         | 1.69%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 168       | 93.85%  |
| Unknown | 11        | 6.15%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 83        | 46.63%  |
| 1       | 67        | 37.64%  |
| Unknown | 28        | 15.73%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 24        | 13.71%  |
| Skylake       | 13        | 7.43%   |
| Zen 3         | 11        | 6.29%   |
| SandyBridge   | 11        | 6.29%   |
| Penryn        | 11        | 6.29%   |
| P6            | 11        | 6.29%   |
| Bonnell       | 10        | 5.71%   |
| Unknown       | 8         | 4.57%   |
| Zen 2         | 7         | 4%      |
| Westmere      | 7         | 4%      |
| Silvermont    | 7         | 4%      |
| IvyBridge     | 7         | 4%      |
| Haswell       | 7         | 4%      |
| Zen+          | 5         | 2.86%   |
| TigerLake     | 5         | 2.86%   |
| Core          | 5         | 2.86%   |
| Goldmont      | 4         | 2.29%   |
| Zen           | 3         | 1.71%   |
| CometLake     | 3         | 1.71%   |
| Broadwell     | 3         | 1.71%   |
| Bobcat        | 3         | 1.71%   |
| Puma          | 2         | 1.14%   |
| Excavator     | 2         | 1.14%   |
| Piledriver    | 1         | 0.57%   |
| K8 Hammer     | 1         | 0.57%   |
| K10 Llano     | 1         | 0.57%   |
| Jaguar        | 1         | 0.57%   |
| IceLake       | 1         | 0.57%   |
| Goldmont plus | 1         | 0.57%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 117       | 56.52%  |
| AMD    | 57        | 27.54%  |
| Nvidia | 32        | 15.46%  |
| ATI    | 1         | 0.48%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 4.65%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 8         | 3.72%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 3.26%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 3.26%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 7         | 3.26%   |
| AMD Renoir                                                                               | 7         | 3.26%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 2.79%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 2.79%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 2.79%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 2.33%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 2.33%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 1.86%   |
| Intel UHD Graphics 620                                                                   | 4         | 1.86%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.86%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.4%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 1.4%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 1.4%    |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 3         | 1.4%    |
| Intel HD Graphics 630                                                                    | 3         | 1.4%    |
| Intel HD Graphics 520                                                                    | 3         | 1.4%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 1.4%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.4%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.4%    |
| AMD Rembrandt [Radeon 680M]                                                              | 3         | 1.4%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 1.4%    |
| AMD Barcelo                                                                              | 3         | 1.4%    |
| Nvidia GK208BM [GeForce 920M]                                                            | 2         | 0.93%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 2         | 0.93%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.93%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.93%   |
| Intel HD Graphics 620                                                                    | 2         | 0.93%   |
| Intel HD Graphics 515                                                                    | 2         | 0.93%   |
| Intel HD Graphics 500                                                                    | 2         | 0.93%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 0.93%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 2         | 0.93%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 2         | 0.93%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 0.93%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 0.93%   |
| AMD Robson CE [Radeon HD 6370M/7370M]                                                    | 2         | 0.93%   |
| AMD Lucienne                                                                             | 2         | 0.93%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 68        | 38.86%  |
| 1 x AMD        | 47        | 26.86%  |
| Intel + Nvidia | 24        | 13.71%  |
| 2 x Intel      | 20        | 11.43%  |
| 1 x Nvidia     | 6         | 3.43%   |
| Intel + AMD    | 5         | 2.86%   |
| 2 x AMD        | 3         | 1.71%   |
| AMD + Nvidia   | 2         | 1.14%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 157       | 88.2%   |
| Unknown     | 11        | 6.18%   |
| Proprietary | 10        | 5.62%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 138       | 76.67%  |
| 0.01-0.5   | 27        | 15%     |
| 1.01-2.0   | 6         | 3.33%   |
| 0.51-1.0   | 6         | 3.33%   |
| 3.01-4.0   | 2         | 1.11%   |
| 2.01-3.0   | 1         | 0.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 30        | 24.79%  |
| LG Display              | 17        | 14.05%  |
| BOE                     | 17        | 14.05%  |
| Chimei Innolux          | 15        | 12.4%   |
| Samsung Electronics     | 11        | 9.09%   |
| InfoVision              | 4         | 3.31%   |
| LG Philips              | 3         | 2.48%   |
| Chi Mei Optoelectronics | 3         | 2.48%   |
| Acer                    | 3         | 2.48%   |
| ViewSonic               | 2         | 1.65%   |
| PANDA                   | 2         | 1.65%   |
| Lenovo                  | 2         | 1.65%   |
| HKC                     | 2         | 1.65%   |
| HannStar                | 2         | 1.65%   |
| Toshiba                 | 1         | 0.83%   |
| Panasonic               | 1         | 0.83%   |
| NEC Computers           | 1         | 0.83%   |
| Goldstar                | 1         | 0.83%   |
| CSO                     | 1         | 0.83%   |
| CPT                     | 1         | 0.83%   |
| Apple                   | 1         | 0.83%   |
| Ancor Communications    | 1         | 0.83%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC3245 1366x768 340x190mm 15.3-inch     | 2         | 1.65%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 220x130mm 10.1-inch     | 2         | 1.65%   |
| HKC LCD Monitor HKC3D05 1920x1080 340x190mm 15.3-inch                    | 2         | 1.65%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch                | 2         | 1.65%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 340x190mm 15.3-inch         | 2         | 1.65%   |
| Chi Mei Optoelectronics LCD Monitor CMO1457 1366x768 310x170mm 13.9-inch | 2         | 1.65%   |
| BOE LCD Monitor BOE0691 1920x1080 280x160mm 12.7-inch                    | 2         | 1.65%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch            | 2         | 1.65%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch            | 2         | 1.65%   |
| Acer K272HUL ACR0524 2560x1440 600x340mm 27.2-inch                       | 2         | 1.65%   |
| ViewSonic VG2439 Series VSCD22B 1920x1080 520x290mm 23.4-inch            | 1         | 0.83%   |
| ViewSonic LCD Monitor VSC6F2E 1920x1080 480x270mm 21.7-inch              | 1         | 0.83%   |
| Toshiba TV TSB0108 1360x768 700x390mm 31.5-inch                          | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC5643 1280x800 300x190mm 14.0-inch     | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC4542 1280x800 300x190mm 14.0-inch     | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 370x230mm 17.2-inch     | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 340x190mm 15.3-inch    | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch    | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SDC415A 3200x1800 290x160mm 13.0-inch    | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 1020x570mm 46.0-inch   | 1         | 0.83%   |
| PANDA LM133LF1L01 NCP13FB 1920x1080 290x170mm 13.2-inch                  | 1         | 0.83%   |
| PANDA LCD Monitor NCP002B 1920x1080 310x170mm 13.9-inch                  | 1         | 0.83%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch             | 1         | 0.83%   |
| NEC Computers LCD1970NX NEC6662 1280x1024 380x300mm 19.1-inch            | 1         | 0.83%   |
| LG Philips LCD Monitor LPLA101 1440x900 370x230mm 17.2-inch              | 1         | 0.83%   |
| LG Philips LCD Monitor LPL3B01 1280x800 330x210mm 15.4-inch              | 1         | 0.83%   |
| LG Philips LCD Monitor LPL0301 1280x800 330x210mm 15.4-inch              | 1         | 0.83%   |
| LG Display LCD Monitor LGD06FF 1920x1080 340x190mm 15.3-inch             | 1         | 0.83%   |
| LG Display LCD Monitor LGD062E 1920x1080 340x190mm 15.3-inch             | 1         | 0.83%   |
| LG Display LCD Monitor LGD060A 1920x1080 290x170mm 13.2-inch             | 1         | 0.83%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch             | 1         | 0.83%   |
| LG Display LCD Monitor LGD05EE 2560x1440 310x170mm 13.9-inch             | 1         | 0.83%   |
| LG Display LCD Monitor LGD053F 1920x1080 340x190mm 15.3-inch             | 1         | 0.83%   |
| LG Display LCD Monitor LGD046F 1920x1080 350x190mm 15.7-inch             | 1         | 0.83%   |
| LG Display LCD Monitor LGD046B 1366x768 340x190mm 15.3-inch              | 1         | 0.83%   |
| LG Display LCD Monitor LGD0465 1366x768 340x190mm 15.3-inch              | 1         | 0.83%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch             | 1         | 0.83%   |
| LG Display LCD Monitor LGD0430 1366x768 350x190mm 15.7-inch              | 1         | 0.83%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch              | 1         | 0.83%   |
| LG Display LCD Monitor LGD034D 1366x768 340x190mm 15.3-inch              | 1         | 0.83%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 51        | 42.15%  |
| 1366x768 (WXGA)   | 32        | 26.45%  |
| 1280x800 (WXGA)   | 6         | 4.96%   |
| 2560x1440 (QHD)   | 5         | 4.13%   |
| 1600x900 (HD+)    | 5         | 4.13%   |
| 1024x600          | 5         | 4.13%   |
| 1440x900 (WXGA+)  | 3         | 2.48%   |
| 3840x2160 (4K)    | 2         | 1.65%   |
| 1280x1024 (SXGA)  | 2         | 1.65%   |
| 3200x1800 (QHD+)  | 1         | 0.83%   |
| 2880x1620         | 1         | 0.83%   |
| 2560x1600         | 1         | 0.83%   |
| 2560x1080         | 1         | 0.83%   |
| 2520x1680         | 1         | 0.83%   |
| 2240x1400         | 1         | 0.83%   |
| 2160x1440         | 1         | 0.83%   |
| 2160x1350         | 1         | 0.83%   |
| 1920x540          | 1         | 0.83%   |
| 1920x1200 (WUXGA) | 1         | 0.83%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 53        | 43.8%   |
| 13     | 28        | 23.14%  |
| 17     | 9         | 7.44%   |
| 10     | 6         | 4.96%   |
| 14     | 5         | 4.13%   |
| 12     | 5         | 4.13%   |
| 11     | 5         | 4.13%   |
| 27     | 2         | 1.65%   |
| 21     | 2         | 1.65%   |
| 54     | 1         | 0.83%   |
| 34     | 1         | 0.83%   |
| 31     | 1         | 0.83%   |
| 23     | 1         | 0.83%   |
| 19     | 1         | 0.83%   |
| 16     | 1         | 0.83%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 76        | 62.81%  |
| 201-300     | 28        | 23.14%  |
| 351-400     | 9         | 7.44%   |
| 501-600     | 3         | 2.48%   |
| 401-500     | 2         | 1.65%   |
| 701-800     | 1         | 0.83%   |
| 601-700     | 1         | 0.83%   |
| 1001-1500   | 1         | 0.83%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 95        | 83.33%  |
| 16/10 | 14        | 12.28%  |
| 5/4   | 2         | 1.75%   |
| 3/2   | 2         | 1.75%   |
| 21/9  | 1         | 0.88%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 46        | 38.02%  |
| 81-90          | 26        | 21.49%  |
| 71-80          | 7         | 5.79%   |
| 101-110        | 7         | 5.79%   |
| 41-50          | 6         | 4.96%   |
| 121-130        | 6         | 4.96%   |
| 51-60          | 5         | 4.13%   |
| 61-70          | 4         | 3.31%   |
| 201-250        | 3         | 2.48%   |
| 131-140        | 3         | 2.48%   |
| 351-500        | 2         | 1.65%   |
| 301-350        | 2         | 1.65%   |
| More than 1000 | 1         | 0.83%   |
| 151-200        | 1         | 0.83%   |
| 141-150        | 1         | 0.83%   |
| 111-120        | 1         | 0.83%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 51        | 42.15%  |
| 101-120       | 37        | 30.58%  |
| 161-240       | 17        | 14.05%  |
| 51-100        | 14        | 11.57%  |
| More than 240 | 2         | 1.65%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 136       | 74.32%  |
| 0     | 36        | 19.67%  |
| 2     | 11        | 6.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 95        | 31.77%  |
| Realtek Semiconductor             | 83        | 27.76%  |
| Qualcomm Atheros                  | 51        | 17.06%  |
| Broadcom                          | 17        | 5.69%   |
| Marvell Technology Group          | 11        | 3.68%   |
| TP-Link                           | 8         | 2.68%   |
| Ralink Technology                 | 4         | 1.34%   |
| MediaTek                          | 3         | 1%      |
| Xiaomi                            | 2         | 0.67%   |
| Samsung Electronics               | 2         | 0.67%   |
| Ralink                            | 2         | 0.67%   |
| JMicron Technology                | 2         | 0.67%   |
| Huawei Technologies               | 2         | 0.67%   |
| Fibocom                           | 2         | 0.67%   |
| Ericsson Business Mobile Networks | 2         | 0.67%   |
| Arduino SA                        | 2         | 0.67%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.33%   |
| Shenzhen Goodix Technology        | 1         | 0.33%   |
| Realtek                           | 1         | 0.33%   |
| Nvidia                            | 1         | 0.33%   |
| Mercucys                          | 1         | 0.33%   |
| Dell                              | 1         | 0.33%   |
| D-Link                            | 1         | 0.33%   |
| BUFFALO                           | 1         | 0.33%   |
| Attansic                          | 1         | 0.33%   |
| Atheros                           | 1         | 0.33%   |
| 3Com                              | 1         | 0.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 54        | 15.25%  |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 17        | 4.8%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 12        | 3.39%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 10        | 2.82%   |
| Intel Wireless 7265                                                     | 9         | 2.54%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 8         | 2.26%   |
| Intel Wireless 8265 / 8275                                              | 7         | 1.98%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 7         | 1.98%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 1.69%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 6         | 1.69%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 6         | 1.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.41%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 5         | 1.41%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 1.41%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 1.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 1.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 1.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 1.13%   |
| Intel Wireless 8260                                                     | 4         | 1.13%   |
| Intel Wireless 3165                                                     | 4         | 1.13%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 1.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 1.13%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 3         | 0.85%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 0.85%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                   | 3         | 0.85%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 0.85%   |
| Intel WiFi Link 5100                                                    | 3         | 0.85%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection               | 3         | 0.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 0.85%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 0.85%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express                | 3         | 0.85%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 0.85%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 2         | 0.56%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.56%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 2         | 0.56%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.56%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 2         | 0.56%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 2         | 0.56%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                           | 2         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 90        | 47.12%  |
| Qualcomm Atheros      | 43        | 22.51%  |
| Realtek Semiconductor | 28        | 14.66%  |
| Broadcom              | 10        | 5.24%   |
| TP-Link               | 8         | 4.19%   |
| Ralink Technology     | 4         | 2.09%   |
| Ralink                | 2         | 1.05%   |
| MediaTek              | 2         | 1.05%   |
| Mercucys              | 1         | 0.52%   |
| D-Link                | 1         | 0.52%   |
| BUFFALO               | 1         | 0.52%   |
| Atheros               | 1         | 0.52%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 17        | 8.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 10        | 5.1%    |
| Intel Wireless 7265                                                     | 9         | 4.59%   |
| Intel Wireless 8265 / 8275                                              | 7         | 3.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 7         | 3.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 3.06%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 6         | 3.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 2.55%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 2.55%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 2.55%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 2.04%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 2.04%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 2.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 2.04%   |
| Intel Wireless 8260                                                     | 4         | 2.04%   |
| Intel Wireless 3165                                                     | 4         | 2.04%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 2.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 2.04%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 3         | 1.53%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 1.53%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                   | 3         | 1.53%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 1.53%   |
| Intel WiFi Link 5100                                                    | 3         | 1.53%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection               | 3         | 1.53%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.53%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.53%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 1.53%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 1.02%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.02%   |
| Intel Wireless-AC 9260                                                  | 2         | 1.02%   |
| Intel Wireless 7260                                                     | 2         | 1.02%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 1.02%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 1.02%   |
| TP-Link Wireless USB Adapter                                            | 1         | 0.51%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 0.51%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]     | 1         | 0.51%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 1         | 0.51%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.51%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                         | 1         | 0.51%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1         | 0.51%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 68        | 47.55%  |
| Intel                            | 28        | 19.58%  |
| Qualcomm Atheros                 | 16        | 11.19%  |
| Marvell Technology Group         | 11        | 7.69%   |
| Broadcom                         | 8         | 5.59%   |
| Xiaomi                           | 2         | 1.4%    |
| Samsung Electronics              | 2         | 1.4%    |
| JMicron Technology               | 2         | 1.4%    |
| Silicon Integrated Systems [SiS] | 1         | 0.7%    |
| Realtek                          | 1         | 0.7%    |
| Nvidia                           | 1         | 0.7%    |
| MediaTek                         | 1         | 0.7%    |
| Attansic                         | 1         | 0.7%    |
| 3Com                             | 1         | 0.7%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 54        | 37.76%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 8.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 5.59%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 6         | 4.2%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 5         | 3.5%    |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 3         | 2.1%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 1.4%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 1.4%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 1.4%    |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 2         | 1.4%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 1.4%    |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.4%    |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.4%    |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 1.4%    |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.4%    |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.4%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.7%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.7%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.7%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.7%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.7%    |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 0.7%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 0.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.7%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.7%    |
| Nvidia MCP79 Ethernet                                             | 1         | 0.7%    |
| MediaTek USB Ethernet-RNDIS                                       | 1         | 0.7%    |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.7%    |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.7%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.7%    |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 0.7%    |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 0.7%    |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 1         | 0.7%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.7%    |
| Intel PRO/100 VM Network Connection                               | 1         | 0.7%    |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.7%    |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.7%    |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.7%    |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 0.7%    |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.7%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 169       | 52.65%  |
| Ethernet | 137       | 42.68%  |
| Unknown  | 8         | 2.49%   |
| Modem    | 7         | 2.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 114       | 55.88%  |
| Ethernet | 88        | 43.14%  |
| Unknown  | 2         | 0.98%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 130       | 74.71%  |
| 1     | 42        | 24.14%  |
| 3     | 1         | 0.57%   |
| 0     | 1         | 0.57%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 172       | 97.73%  |
| Yes  | 4         | 2.27%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 61        | 50%     |
| Qualcomm Atheros Communications | 12        | 9.84%   |
| Realtek Semiconductor           | 9         | 7.38%   |
| IMC Networks                    | 7         | 5.74%   |
| Broadcom                        | 6         | 4.92%   |
| Foxconn / Hon Hai               | 4         | 3.28%   |
| ASUSTek Computer                | 4         | 3.28%   |
| Skylight Digital                | 3         | 2.46%   |
| Lite-On Technology              | 3         | 2.46%   |
| Apple                           | 3         | 2.46%   |
| Alps Electric                   | 3         | 2.46%   |
| Hewlett-Packard                 | 2         | 1.64%   |
| TP-Link                         | 1         | 0.82%   |
| Taiyo Yuden                     | 1         | 0.82%   |
| Ralink                          | 1         | 0.82%   |
| Opticis                         | 1         | 0.82%   |
| Dell                            | 1         | 0.82%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 24        | 19.67%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 10        | 8.2%    |
| Intel AX201 Bluetooth                                       | 10        | 8.2%    |
| Intel Wireless-AC 3168 Bluetooth                            | 7         | 5.74%   |
| Intel AX200 Bluetooth                                       | 5         | 4.1%    |
| Realtek Bluetooth Adapter                                   | 4         | 3.28%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 4         | 3.28%   |
| Skylight Digital Realtek Bluetooth Adapter                  | 3         | 2.46%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 3         | 2.46%   |
| Realtek RTL8723B Bluetooth                                  | 2         | 1.64%   |
| Realtek Bluetooth 4.0 + High Speed Chip                     | 2         | 1.64%   |
| Lite-On Atheros AR3012 Bluetooth                            | 2         | 1.64%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 2         | 1.64%   |
| IMC Networks Realtek Bluetooth Adapter                      | 2         | 1.64%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 2         | 1.64%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 1.64%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 1.64%   |
| ASUS BT-270 Bluetooth Adapter                               | 2         | 1.64%   |
| Apple Bluetooth Host Controller                             | 2         | 1.64%   |
| TP-Link Bluetooth 5.0 USB Adapter                           | 1         | 0.82%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)                     | 1         | 0.82%   |
| Realtek RTL8821A Bluetooth                                  | 1         | 0.82%   |
| Ralink RT3290 Bluetooth                                     | 1         | 0.82%   |
| Qualcomm Atheros QCA9565 Bluetooth 4.0 + HS Adapter         | 1         | 0.82%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 0.82%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 0.82%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 0.82%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 1         | 0.82%   |
| Opticis Realtek Bluetooth Adapter                           | 1         | 0.82%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 0.82%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 0.82%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 0.82%   |
| Intel AX210 Bluetooth                                       | 1         | 0.82%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 0.82%   |
| IMC Networks MediaTek Bluetooth Adapter                     | 1         | 0.82%   |
| IMC Networks Bluetooth module                               | 1         | 0.82%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 0.82%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter                  | 1         | 0.82%   |
| Foxconn / Hon Hai Qualcomm Atheros Bluetooth 4.0            | 1         | 0.82%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3012 Bluetooth Adapter | 1         | 0.82%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 128       | 67.37%  |
| AMD                              | 46        | 24.21%  |
| Nvidia                           | 8         | 4.21%   |
| Lenovo                           | 3         | 1.58%   |
| Texas Instruments                | 1         | 0.53%   |
| Silicon Integrated Systems [SiS] | 1         | 0.53%   |
| Generalplus Technology           | 1         | 0.53%   |
| ESS Technology                   | 1         | 0.53%   |
| Creative Technology              | 1         | 0.53%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 30        | 12.5%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 20        | 8.33%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 19        | 7.92%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 12        | 5%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11        | 4.58%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 8         | 3.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 3.33%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 2.92%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 2.92%   |
| Intel 8 Series HD Audio Controller                                                                | 7         | 2.92%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 7         | 2.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 2.92%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 2.08%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5         | 2.08%   |
| AMD FCH Azalia Controller                                                                         | 5         | 2.08%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 1.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1.67%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 1.67%   |
| Lenovo Realtek USB Audio                                                                          | 3         | 1.25%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 1.25%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 1.25%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 1.25%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 1.25%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.25%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 3         | 1.25%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 1.25%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 3         | 1.25%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.25%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 0.83%   |
| Nvidia TU104 HD Audio Controller                                                                  | 2         | 0.83%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 0.83%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 0.83%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 2         | 0.83%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 0.83%   |
| AMD High Definition Audio Controller                                                              | 2         | 0.83%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 0.83%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                 | 1         | 0.42%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.42%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.42%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 47        | 25.68%  |
| SK hynix            | 31        | 16.94%  |
| Unknown             | 25        | 13.66%  |
| Micron Technology   | 20        | 10.93%  |
| Kingston            | 19        | 10.38%  |
| Unknown             | 13        | 7.1%    |
| Elpida              | 5         | 2.73%   |
| Ramaxel Technology  | 3         | 1.64%   |
| Crucial             | 3         | 1.64%   |
| A-DATA Technology   | 3         | 1.64%   |
| 48spaces            | 3         | 1.64%   |
| Transcend           | 2         | 1.09%   |
| Corsair             | 2         | 1.09%   |
| Unknown (ABCD)      | 1         | 0.55%   |
| Unknown (0x0809)    | 1         | 0.55%   |
| Silicon Power       | 1         | 0.55%   |
| PUSKILL             | 1         | 0.55%   |
| GeIL                | 1         | 0.55%   |
| Apacer              | 1         | 0.55%   |
| AMD                 | 1         | 0.55%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                   | 13        | 6.63%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 5         | 2.55%   |
| Unknown RAM Module 512MB SODIMM DDR                                       | 3         | 1.53%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 3         | 1.53%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s                    | 3         | 1.53%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 3         | 1.53%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s                    | 3         | 1.53%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s                     | 3         | 1.53%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s                     | 3         | 1.53%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s                     | 3         | 1.53%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                      | 3         | 1.53%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s                | 3         | 1.53%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 3         | 1.53%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                                | 2         | 1.02%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM 1333MT/s                         | 2         | 1.02%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s                    | 2         | 1.02%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 2         | 1.02%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s                     | 2         | 1.02%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 2         | 1.02%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s                     | 2         | 1.02%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s                     | 2         | 1.02%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 2         | 1.02%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s                     | 2         | 1.02%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                      | 2         | 1.02%   |
| Kingston RAM 9905700-011.A00G 8192MB SODIMM DDR4 2400MT/s                 | 2         | 1.02%   |
| Unknown RAM Module 512MB SODIMM DRAM                                      | 1         | 0.51%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                               | 1         | 0.51%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                               | 1         | 0.51%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                                 | 1         | 0.51%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                               | 1         | 0.51%   |
| Unknown RAM Module 2GB SODIMM DDR3                                        | 1         | 0.51%   |
| Unknown RAM Module 2GB SODIMM 667MT/s                                     | 1         | 0.51%   |
| Unknown RAM Module 2GB DIMM 667MT/s                                       | 1         | 0.51%   |
| Unknown RAM Module 256MB SODIMM DRAM                                      | 1         | 0.51%   |
| Unknown RAM Module 256MB SODIMM DDR 100MT/s                               | 1         | 0.51%   |
| Unknown RAM Module 2560MB SODIMM DDR                                      | 1         | 0.51%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                                    | 1         | 0.51%   |
| Unknown RAM Module 2048MB SODIMM DDR3                                     | 1         | 0.51%   |
| Unknown RAM Module 2048MB SODIMM DDR2                                     | 1         | 0.51%   |
| Unknown RAM Module 2048MB SODIMM DDR 800MT/s                              | 1         | 0.51%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 67        | 42.14%  |
| DDR3    | 45        | 28.3%   |
| DDR2    | 16        | 10.06%  |
| LPDDR3  | 7         | 4.4%    |
| DDR     | 6         | 3.77%   |
| SDRAM   | 5         | 3.14%   |
| Unknown | 4         | 2.52%   |
| DRAM    | 3         | 1.89%   |
| LPDDR5  | 2         | 1.26%   |
| LPDDR4  | 2         | 1.26%   |
| RAM     | 1         | 0.63%   |
| DDR5    | 1         | 0.63%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 142       | 89.31%  |
| Row Of Chips | 12        | 7.55%   |
| DIMM         | 3         | 1.89%   |
| Chip         | 1         | 0.63%   |
| Unknown      | 1         | 0.63%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 64        | 35.75%  |
| 4096  | 45        | 25.14%  |
| 2048  | 38        | 21.23%  |
| 16384 | 11        | 6.15%   |
| 1024  | 11        | 6.15%   |
| 512   | 4         | 2.23%   |
| 32768 | 2         | 1.12%   |
| 256   | 2         | 1.12%   |
| 2560  | 1         | 0.56%   |
| 128   | 1         | 0.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 28        | 16.67%  |
| 2667    | 25        | 14.88%  |
| 1600    | 24        | 14.29%  |
| 2400    | 15        | 8.93%   |
| 1333    | 13        | 7.74%   |
| 667     | 12        | 7.14%   |
| Unknown | 12        | 7.14%   |
| 1867    | 7         | 4.17%   |
| 2133    | 6         | 3.57%   |
| 800     | 6         | 3.57%   |
| 1067    | 4         | 2.38%   |
| 1334    | 3         | 1.79%   |
| 6400    | 2         | 1.19%   |
| 2048    | 2         | 1.19%   |
| 266     | 2         | 1.19%   |
| 4800    | 1         | 0.6%    |
| 4267    | 1         | 0.6%    |
| 2933    | 1         | 0.6%    |
| 1639    | 1         | 0.6%    |
| 975     | 1         | 0.6%    |
| 400     | 1         | 0.6%    |
| 100     | 1         | 0.6%    |

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
| Chicony Electronics                    | 32        | 23.53%  |
| IMC Networks                           | 18        | 13.24%  |
| Microdia                               | 14        | 10.29%  |
| Realtek Semiconductor                  | 12        | 8.82%   |
| Bison Electronics                      | 9         | 6.62%   |
| Suyin                                  | 5         | 3.68%   |
| Quanta                                 | 5         | 3.68%   |
| Syntek                                 | 4         | 2.94%   |
| Sunplus Innovation Technology          | 4         | 2.94%   |
| Silicon Motion                         | 4         | 2.94%   |
| Lite-On Technology                     | 4         | 2.94%   |
| ALi                                    | 4         | 2.94%   |
| Luxvisions Innotech Limited            | 3         | 2.21%   |
| Jiangxi Shinetech Optical              | 3         | 2.21%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.21%   |
| Lenovo                                 | 2         | 1.47%   |
| DigiTech                               | 2         | 1.47%   |
| Z-Star Microelectronics                | 1         | 0.74%   |
| Y Media                                | 1         | 0.74%   |
| Supreme Electronics                    | 1         | 0.74%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.74%   |
| Ricoh                                  | 1         | 0.74%   |
| Intel                                  | 1         | 0.74%   |
| Genesys Logic                          | 1         | 0.74%   |
| Denron                                 | 1         | 0.74%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                              | 11        | 7.97%   |
| Microdia Integrated_Webcam_HD                          | 7         | 5.07%   |
| IMC Networks Integrated Camera                         | 6         | 4.35%   |
| Silicon Motion WebCam SCX Series                       | 4         | 2.9%    |
| Realtek USB 2.0 PC Camera                              | 3         | 2.17%   |
| Realtek Acer 640 x 480 laptop camera                   | 3         | 2.17%   |
| Quanta VGA WebCam                                      | 3         | 2.17%   |
| Microdia USB Camera                                    | 3         | 2.17%   |
| IMC Networks EasyCamera                                | 3         | 2.17%   |
| Bison Lenovo EasyCamera                                | 3         | 2.17%   |
| ALi Gateway Webcam                                     | 3         | 2.17%   |
| Syntek EasyCamera                                      | 2         | 1.45%   |
| Sunplus Hy HD Camera                                   | 2         | 1.45%   |
| Realtek Integrated Webcam                              | 2         | 1.45%   |
| Microdia Integrated Webcam                             | 2         | 1.45%   |
| Luxvisions Innotech Limited Integrated Camera          | 2         | 1.45%   |
| Lite-On Integrated Camera                              | 2         | 1.45%   |
| Lite-On HP HD Camera                                   | 2         | 1.45%   |
| Jiangxi Shinetech Optical HD Camera                    | 2         | 1.45%   |
| IMC Networks UVC VGA Webcam                            | 2         | 1.45%   |
| IMC Networks Realtek DMFT RGB                          | 2         | 1.45%   |
| DigiTech WebCam SCB-0350M                              | 2         | 1.45%   |
| Chicony XiaoMi USB 2.0 Webcam                          | 2         | 1.45%   |
| Chicony Lenovo EasyCamera                              | 2         | 1.45%   |
| Chicony 2.0M UVC Webcam / CNF7129                      | 2         | 1.45%   |
| Bison Lenovo Integrated Webcam                         | 2         | 1.45%   |
| Bison Integrated Camera                                | 2         | 1.45%   |
| Z-Star Webcam                                          | 1         | 0.72%   |
| Y Media USB Camera                                     | 1         | 0.72%   |
| Syntek Lenovo EasyCamera                               | 1         | 0.72%   |
| Syntek Integrated Camera                               | 1         | 0.72%   |
| Suyin USB 2.0 UVC 1.3M WebCam                          | 1         | 0.72%   |
| Suyin HP Webcam                                        | 1         | 0.72%   |
| Suyin HD WebCam                                        | 1         | 0.72%   |
| Suyin HD Video WebCam                                  | 1         | 0.72%   |
| Suyin Acer Crystal Eye webcam                          | 1         | 0.72%   |
| Supreme Integrated Camera                              | 1         | 0.72%   |
| Sunplus Integrated_Webcam_HD                           | 1         | 0.72%   |
| Sunplus HD WebCam                                      | 1         | 0.72%   |
| Shenzhen Kingcome Optoelectronic XiaoMi USB 2.0 Webcam | 1         | 0.72%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 12        | 30%     |
| Validity Sensors           | 10        | 25%     |
| STMicroelectronics         | 4         | 10%     |
| AuthenTec                  | 4         | 10%     |
| Upek                       | 3         | 7.5%    |
| Shenzhen Goodix Technology | 3         | 7.5%    |
| FocalTech Systems          | 3         | 7.5%    |
| Broadcom                   | 1         | 2.5%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 7         | 17.5%   |
| STMicroelectronics Fingerprint Reader                                        | 4         | 10%     |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 3         | 7.5%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 3         | 7.5%    |
| Shenzhen Goodix  Fingerprint Device                                          | 3         | 7.5%    |
| FocalTech Systems Fingerprint Reader                                         | 3         | 7.5%    |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 2         | 5%      |
| Validity Sensors VFS495 Fingerprint Reader                                   | 2         | 5%      |
| Synaptics WBDI Fingerprint Reader USB 086                                    | 2         | 5%      |
| AuthenTec AES1600                                                            | 2         | 5%      |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 1         | 2.5%    |
| Validity Sensors Synaptics WBDI                                              | 1         | 2.5%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint   | 1         | 2.5%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 1         | 2.5%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 1         | 2.5%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                     | 1         | 2.5%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 2.5%    |
| AuthenTec AES2810                                                            | 1         | 2.5%    |
| AuthenTec AES2501 Fingerprint Sensor                                         | 1         | 2.5%    |

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
| 1     | 69        | 36.7%   |
| 2     | 46        | 24.47%  |
| 0     | 25        | 13.3%   |
| 3     | 23        | 12.23%  |
| 4     | 18        | 9.57%   |
| 5     | 3         | 1.6%    |
| 9     | 1         | 0.53%   |
| 8     | 1         | 0.53%   |
| 7     | 1         | 0.53%   |
| 6     | 1         | 0.53%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 88        | 29.73%  |
| Net/wireless             | 46        | 15.54%  |
| Bluetooth                | 40        | 13.51%  |
| Card reader              | 35        | 11.82%  |
| Fingerprint reader       | 33        | 11.15%  |
| Firewire controller      | 14        | 4.73%   |
| Graphics card            | 11        | 3.72%   |
| Sound                    | 10        | 3.38%   |
| Network                  | 7         | 2.36%   |
| Storage                  | 5         | 1.69%   |
| Modem                    | 4         | 1.35%   |
| Storage/ata              | 3         | 1.01%   |

