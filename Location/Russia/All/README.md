BSD in Russia - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for BSD in Russia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Russia/Desktop/README.md) and [notebooks](/Location/Russia/Notebook/README.md).

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

Total: 723

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Techvision    | TVI7309X B0                 | Desktop     | [a58d9501ad](https://bsd-hardware.info/?probe=a58d9501ad) | Jan 31, 2023 |
| F-Plus Mob... | FLAPTOP r                   | Notebook    | [c2f84d2103](https://bsd-hardware.info/?probe=c2f84d2103) | Jan 31, 2023 |
| F-Plus Mob... | FLAPTOP r                   | Notebook    | [165d435f30](https://bsd-hardware.info/?probe=165d435f30) | Jan 31, 2023 |
| MACHINIST     | X99-K9 V2.0                 | Desktop     | [eb8a6cb004](https://bsd-hardware.info/?probe=eb8a6cb004) | Jan 30, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [d5f06d91db](https://bsd-hardware.info/?probe=d5f06d91db) | Jan 28, 2023 |
| ASUSTek       | WS-C621E-SAGE Series        | Server      | [d32c9457b9](https://bsd-hardware.info/?probe=d32c9457b9) | Jan 28, 2023 |
| ChangWang     | CW56-58                     | Desktop     | [2d48772c23](https://bsd-hardware.info/?probe=2d48772c23) | Jan 27, 2023 |
| F-Plus Mob... | FLAPTOP r                   | Notebook    | [448f9265f2](https://bsd-hardware.info/?probe=448f9265f2) | Jan 27, 2023 |
| F-Plus Mob... | FLAPTOP r                   | Notebook    | [512bf8f61d](https://bsd-hardware.info/?probe=512bf8f61d) | Jan 27, 2023 |
| Citrix        | CB-1100                     | Desktop     | [36199a59e2](https://bsd-hardware.info/?probe=36199a59e2) | Jan 26, 2023 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [6b63a16799](https://bsd-hardware.info/?probe=6b63a16799) | Jan 26, 2023 |
| ChangWang     | CW56-58                     | Desktop     | [89ec5e42ef](https://bsd-hardware.info/?probe=89ec5e42ef) | Jan 26, 2023 |
| Gigabyte      | B360M D2V                   | Desktop     | [6685066b6e](https://bsd-hardware.info/?probe=6685066b6e) | Jan 26, 2023 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [a712c2d054](https://bsd-hardware.info/?probe=a712c2d054) | Jan 26, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [9a307961ed](https://bsd-hardware.info/?probe=9a307961ed) | Jan 26, 2023 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [7b2fee315d](https://bsd-hardware.info/?probe=7b2fee315d) | Jan 26, 2023 |
| Shuttle       | DS20U                       | Desktop     | [71033e4a64](https://bsd-hardware.info/?probe=71033e4a64) | Jan 26, 2023 |
| Dell          | 0HY9JP A02                  | Desktop     | [ca71c8ab2b](https://bsd-hardware.info/?probe=ca71c8ab2b) | Jan 25, 2023 |
| Dell          | 0CNWVK A00                  | Desktop     | [e59d4ab226](https://bsd-hardware.info/?probe=e59d4ab226) | Jan 25, 2023 |
| ASUSTek       | P7P55D LE                   | Desktop     | [5da1e71837](https://bsd-hardware.info/?probe=5da1e71837) | Jan 25, 2023 |
| Timi          | TM1607                      | Notebook    | [57113d2886](https://bsd-hardware.info/?probe=57113d2886) | Jan 25, 2023 |
| ASUSTek       | WS-C621E-SAGE Series        | Server      | [ab59ccf04c](https://bsd-hardware.info/?probe=ab59ccf04c) | Jan 24, 2023 |
| MSI           | PS63 Modern 8M              | Notebook    | [f740e313e5](https://bsd-hardware.info/?probe=f740e313e5) | Jan 24, 2023 |
| Timi          | TM1607                      | Notebook    | [27db14fdbd](https://bsd-hardware.info/?probe=27db14fdbd) | Jan 24, 2023 |
| ASUSTek       | K50IN                       | Notebook    | [6f7a8f3338](https://bsd-hardware.info/?probe=6f7a8f3338) | Jan 23, 2023 |
| ASRock        | Z390 Pro4                   | Desktop     | [b9d64a7496](https://bsd-hardware.info/?probe=b9d64a7496) | Jan 23, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [6cf4f6761e](https://bsd-hardware.info/?probe=6cf4f6761e) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [27ea626000](https://bsd-hardware.info/?probe=27ea626000) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [abc17c6fc6](https://bsd-hardware.info/?probe=abc17c6fc6) | Jan 23, 2023 |
| AZW           | U59                         | Desktop     | [1f97b27470](https://bsd-hardware.info/?probe=1f97b27470) | Jan 23, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [840145eb80](https://bsd-hardware.info/?probe=840145eb80) | Jan 23, 2023 |
| Timi          | TM1607                      | Notebook    | [7636a0ef8f](https://bsd-hardware.info/?probe=7636a0ef8f) | Jan 23, 2023 |
| Timi          | TM1607                      | Notebook    | [1ca46404a1](https://bsd-hardware.info/?probe=1ca46404a1) | Jan 23, 2023 |
| Acer          | Aspire ES1-533              | Notebook    | [d2652b76cf](https://bsd-hardware.info/?probe=d2652b76cf) | Jan 22, 2023 |
| Lenovo        | ThinkPad P50 20EN0041MX     | Notebook    | [c27f1f53f2](https://bsd-hardware.info/?probe=c27f1f53f2) | Jan 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [8956f4503e](https://bsd-hardware.info/?probe=8956f4503e) | Jan 21, 2023 |
| Unknown       | AMD-GX3                     | Desktop     | [a38ff8331a](https://bsd-hardware.info/?probe=a38ff8331a) | Jan 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [3afbfc6cea](https://bsd-hardware.info/?probe=3afbfc6cea) | Jan 20, 2023 |
| Unknown       | YL-SKUL6                    | Desktop     | [ef4abfe322](https://bsd-hardware.info/?probe=ef4abfe322) | Jan 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [e13627df1a](https://bsd-hardware.info/?probe=e13627df1a) | Jan 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [8c44d6309f](https://bsd-hardware.info/?probe=8c44d6309f) | Jan 15, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [3126dc27f1](https://bsd-hardware.info/?probe=3126dc27f1) | Jan 12, 2023 |
| Lenovo        | ThinkPad X220 4291LF6       | Notebook    | [25cddb26c3](https://bsd-hardware.info/?probe=25cddb26c3) | Jan 11, 2023 |
| ASUSTek       | H81M-E                      | Desktop     | [1008903f65](https://bsd-hardware.info/?probe=1008903f65) | Jan 11, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [2293d4960d](https://bsd-hardware.info/?probe=2293d4960d) | Jan 11, 2023 |
| Citrix        | CB-1100                     | Desktop     | [860f27ce64](https://bsd-hardware.info/?probe=860f27ce64) | Jan 11, 2023 |
| HP            | ProLiant DL160 Gen9         | Server      | [3a9ec9299c](https://bsd-hardware.info/?probe=3a9ec9299c) | Jan 09, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [19f4631b5a](https://bsd-hardware.info/?probe=19f4631b5a) | Jan 05, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [1deece00b3](https://bsd-hardware.info/?probe=1deece00b3) | Jan 05, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [cc9d84d5ed](https://bsd-hardware.info/?probe=cc9d84d5ed) | Jan 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [ea01217f17](https://bsd-hardware.info/?probe=ea01217f17) | Jan 02, 2023 |
| Gigabyte      | C1037UN-EU                  | Desktop     | [9c526b27dd](https://bsd-hardware.info/?probe=9c526b27dd) | Jan 02, 2023 |
| Shuttle       | DS20U                       | Desktop     | [a5aa09e49f](https://bsd-hardware.info/?probe=a5aa09e49f) | Jan 01, 2023 |
| Timi          | Redmi Book Pro 14 2022      | Notebook    | [ce5e882952](https://bsd-hardware.info/?probe=ce5e882952) | Dec 28, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [4c3b92bb42](https://bsd-hardware.info/?probe=4c3b92bb42) | Dec 24, 2022 |
| Dell          | 0H28RR A04                  | Server      | [8e22402d9e](https://bsd-hardware.info/?probe=8e22402d9e) | Dec 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [d702dfcde2](https://bsd-hardware.info/?probe=d702dfcde2) | Dec 23, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [3e5e7e3e61](https://bsd-hardware.info/?probe=3e5e7e3e61) | Dec 22, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [ced12f0b41](https://bsd-hardware.info/?probe=ced12f0b41) | Dec 19, 2022 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [53a90a6c63](https://bsd-hardware.info/?probe=53a90a6c63) | Dec 18, 2022 |
| ASUSTek       | K50IN                       | Notebook    | [b8bfdec836](https://bsd-hardware.info/?probe=b8bfdec836) | Dec 15, 2022 |
| Dell          | Latitude 5400               | Notebook    | [639993a130](https://bsd-hardware.info/?probe=639993a130) | Dec 15, 2022 |
| Dell          | Latitude 5400               | Notebook    | [5b9eb16e5e](https://bsd-hardware.info/?probe=5b9eb16e5e) | Dec 15, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [55f876d83f](https://bsd-hardware.info/?probe=55f876d83f) | Dec 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [7c644cc639](https://bsd-hardware.info/?probe=7c644cc639) | Dec 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [9b5307f44d](https://bsd-hardware.info/?probe=9b5307f44d) | Dec 15, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [babe4bb620](https://bsd-hardware.info/?probe=babe4bb620) | Dec 13, 2022 |
| Huanan        | X99-F8D V2.4                | Desktop     | [3d06b605c5](https://bsd-hardware.info/?probe=3d06b605c5) | Dec 13, 2022 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [10b6c81bce](https://bsd-hardware.info/?probe=10b6c81bce) | Dec 09, 2022 |
| Huanan        | X99-F8D V2.4                | Desktop     | [f6685811a3](https://bsd-hardware.info/?probe=f6685811a3) | Dec 05, 2022 |
| Dell          | 0CNWVK A00                  | Desktop     | [5a022db6bf](https://bsd-hardware.info/?probe=5a022db6bf) | Dec 05, 2022 |
| Intel         | X99                         | Desktop     | [c21a466fc1](https://bsd-hardware.info/?probe=c21a466fc1) | Dec 01, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [929e4bda1e](https://bsd-hardware.info/?probe=929e4bda1e) | Nov 29, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [7c9ee800c5](https://bsd-hardware.info/?probe=7c9ee800c5) | Nov 29, 2022 |
| QIYIDA        | X99-H9 V2.0                 | Desktop     | [43163b0170](https://bsd-hardware.info/?probe=43163b0170) | Nov 28, 2022 |
| QIYIDA        | X99-H9 V2.0                 | Desktop     | [d00aa0021e](https://bsd-hardware.info/?probe=d00aa0021e) | Nov 28, 2022 |
| Acer          | Revo RN86                   | Desktop     | [a4dcb7f7a2](https://bsd-hardware.info/?probe=a4dcb7f7a2) | Nov 27, 2022 |
| Unknown       | Unknown                     | Desktop     | [1d3bd58d18](https://bsd-hardware.info/?probe=1d3bd58d18) | Nov 25, 2022 |
| Sony          | SVP1321V9RB                 | Notebook    | [932facd689](https://bsd-hardware.info/?probe=932facd689) | Nov 25, 2022 |
| Gigabyte      | H81M-HD3                    | Desktop     | [564cf3d66a](https://bsd-hardware.info/?probe=564cf3d66a) | Nov 22, 2022 |
| Apple         | PowerMac10,1                | Desktop     | [0760ed34c3](https://bsd-hardware.info/?probe=0760ed34c3) | Nov 21, 2022 |
| Huanan        | X99-F8D V2.4                | Desktop     | [9faf79b3f3](https://bsd-hardware.info/?probe=9faf79b3f3) | Nov 18, 2022 |
| Huanan        | X99-F8D V2.4                | Desktop     | [22ec05d988](https://bsd-hardware.info/?probe=22ec05d988) | Nov 12, 2022 |
| ZOTAC         | ZBOX-QCM7T3000/EN072080S... | Mini pc     | [62ab446b5d](https://bsd-hardware.info/?probe=62ab446b5d) | Nov 09, 2022 |
| Acer          | RS880M05                    | Desktop     | [455f9b5026](https://bsd-hardware.info/?probe=455f9b5026) | Nov 07, 2022 |
| ASUSTek       | Z170-K                      | Desktop     | [907b8c2402](https://bsd-hardware.info/?probe=907b8c2402) | Nov 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [58c2f4b4f7](https://bsd-hardware.info/?probe=58c2f4b4f7) | Nov 04, 2022 |
| HP            | 339A                        | Desktop     | [370d93ecde](https://bsd-hardware.info/?probe=370d93ecde) | Nov 02, 2022 |
| HP            | ProLiant DL180 G6           | Server      | [289d2f383b](https://bsd-hardware.info/?probe=289d2f383b) | Nov 02, 2022 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [0f22defdb3](https://bsd-hardware.info/?probe=0f22defdb3) | Oct 30, 2022 |
| Unknown       | Unknown                     | Desktop     | [acf41f7000](https://bsd-hardware.info/?probe=acf41f7000) | Oct 29, 2022 |
| Samsung       | Q430/Q530                   | Notebook    | [fb98c8c797](https://bsd-hardware.info/?probe=fb98c8c797) | Oct 29, 2022 |
| PC Engines    | APU2                        | Desktop     | [d52e3d0ce3](https://bsd-hardware.info/?probe=d52e3d0ce3) | Oct 25, 2022 |
| Samsung       | Q430/Q530                   | Notebook    | [4965215a13](https://bsd-hardware.info/?probe=4965215a13) | Oct 25, 2022 |
| ASUSTek       | P8Z68-V GEN3                | Desktop     | [d7b32200a5](https://bsd-hardware.info/?probe=d7b32200a5) | Oct 22, 2022 |
| Acer          | Revo RN86                   | Desktop     | [692ea69bab](https://bsd-hardware.info/?probe=692ea69bab) | Oct 21, 2022 |
| PC Engines    | APU2                        | Desktop     | [cf1abf5e46](https://bsd-hardware.info/?probe=cf1abf5e46) | Oct 21, 2022 |
| Unknown       | Unknown                     | Desktop     | [d5586487b4](https://bsd-hardware.info/?probe=d5586487b4) | Oct 21, 2022 |
| ASUSTek       | P10S-I Series               | Desktop     | [ceb58e75b8](https://bsd-hardware.info/?probe=ceb58e75b8) | Oct 20, 2022 |
| MSI           | PS63 Modern 8M              | Notebook    | [949e472db5](https://bsd-hardware.info/?probe=949e472db5) | Oct 19, 2022 |
| Supermicro    | X11SSL-F                    | Desktop     | [24faa4663c](https://bsd-hardware.info/?probe=24faa4663c) | Oct 19, 2022 |
| ASUSTek       | N3050I-C                    | Desktop     | [4a83b0953e](https://bsd-hardware.info/?probe=4a83b0953e) | Oct 18, 2022 |
| HP            | ProLiant DL360e Gen8        | Server      | [0da59dff8f](https://bsd-hardware.info/?probe=0da59dff8f) | Oct 12, 2022 |
| Acer          | Aspire 5336                 | Notebook    | [127ddc93fb](https://bsd-hardware.info/?probe=127ddc93fb) | Oct 10, 2022 |
| Acer          | Aspire E5-722G              | Notebook    | [7a4eb565fe](https://bsd-hardware.info/?probe=7a4eb565fe) | Oct 10, 2022 |
| Gigabyte      | C1037UN-EU                  | Desktop     | [734ff7f48c](https://bsd-hardware.info/?probe=734ff7f48c) | Oct 02, 2022 |
| Kraftway      | KW10T                       | Notebook    | [db27da2e88](https://bsd-hardware.info/?probe=db27da2e88) | Sep 29, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [433857f5f7](https://bsd-hardware.info/?probe=433857f5f7) | Sep 27, 2022 |
| Dell          | System Vostro 3750          | Notebook    | [166fbacd73](https://bsd-hardware.info/?probe=166fbacd73) | Sep 24, 2022 |
| YANYU         | H67SL                       | Desktop     | [5f5819ef11](https://bsd-hardware.info/?probe=5f5819ef11) | Sep 24, 2022 |
| NITRINOnet    | M360RUS56                   | Desktop     | [490b9593e0](https://bsd-hardware.info/?probe=490b9593e0) | Sep 23, 2022 |
| YANYU         | H67SL                       | Desktop     | [37ba00c2f3](https://bsd-hardware.info/?probe=37ba00c2f3) | Sep 15, 2022 |
| Dell          | Inspiron 15 3511            | Notebook    | [5abbba28de](https://bsd-hardware.info/?probe=5abbba28de) | Sep 11, 2022 |
| Maxtang       | BYT30                       | Desktop     | [90053990c3](https://bsd-hardware.info/?probe=90053990c3) | Sep 10, 2022 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [98dff45d54](https://bsd-hardware.info/?probe=98dff45d54) | Sep 09, 2022 |
| Dell          | Vostro 5415                 | Notebook    | [ef6d4ee660](https://bsd-hardware.info/?probe=ef6d4ee660) | Sep 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [cffed92600](https://bsd-hardware.info/?probe=cffed92600) | Sep 06, 2022 |
| Dell          | 0Y7WYT A00                  | Desktop     | [2870b9e4c7](https://bsd-hardware.info/?probe=2870b9e4c7) | Sep 05, 2022 |
| HP            | 8719                        | Desktop     | [f3132fc160](https://bsd-hardware.info/?probe=f3132fc160) | Sep 05, 2022 |
| Maxtang       | BYT30                       | Desktop     | [f5c34c7662](https://bsd-hardware.info/?probe=f5c34c7662) | Sep 03, 2022 |
| ASRock        | ConRoeXFire-eSATA2          | Desktop     | [caf005ed95](https://bsd-hardware.info/?probe=caf005ed95) | Sep 01, 2022 |
| Lenovo        | ThinkPad T420 4178A72       | Notebook    | [18a105546b](https://bsd-hardware.info/?probe=18a105546b) | Aug 29, 2022 |
| Lenovo        | ThinkPad T420 4178A72       | Notebook    | [1433351032](https://bsd-hardware.info/?probe=1433351032) | Aug 29, 2022 |
| Intel         | X79 V2.72A                  | Desktop     | [435901d8c9](https://bsd-hardware.info/?probe=435901d8c9) | Aug 29, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [2549c7cadf](https://bsd-hardware.info/?probe=2549c7cadf) | Aug 27, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [2c7586b0ed](https://bsd-hardware.info/?probe=2c7586b0ed) | Aug 25, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [fcfa6205d8](https://bsd-hardware.info/?probe=fcfa6205d8) | Aug 23, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [7d4eaaf087](https://bsd-hardware.info/?probe=7d4eaaf087) | Aug 22, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [063addc66e](https://bsd-hardware.info/?probe=063addc66e) | Aug 22, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [6184507a45](https://bsd-hardware.info/?probe=6184507a45) | Aug 21, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [5ea9441653](https://bsd-hardware.info/?probe=5ea9441653) | Aug 19, 2022 |
| ASUSTek       | ZenBook 14 UX410UFR         | Notebook    | [2bf0f0ef08](https://bsd-hardware.info/?probe=2bf0f0ef08) | Aug 19, 2022 |
| Gigabyte      | C1037UN-EU                  | Desktop     | [0a867d7017](https://bsd-hardware.info/?probe=0a867d7017) | Aug 18, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [a2fc8d9c67](https://bsd-hardware.info/?probe=a2fc8d9c67) | Aug 18, 2022 |
| Intel         | S2600WTTR G92187-372        | Server      | [ce1988c8ff](https://bsd-hardware.info/?probe=ce1988c8ff) | Aug 18, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [9a7d45e51c](https://bsd-hardware.info/?probe=9a7d45e51c) | Aug 16, 2022 |
| Sony          | VGN-UX1XRN                  | Notebook    | [312df080a7](https://bsd-hardware.info/?probe=312df080a7) | Aug 14, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [4055810ef2](https://bsd-hardware.info/?probe=4055810ef2) | Aug 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [2da32e59b0](https://bsd-hardware.info/?probe=2da32e59b0) | Aug 14, 2022 |
| ASRock        | H110M-DGS R3.0              | Desktop     | [0c654b6c34](https://bsd-hardware.info/?probe=0c654b6c34) | Aug 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [467bcd3c04](https://bsd-hardware.info/?probe=467bcd3c04) | Aug 07, 2022 |
| Intel         | NUC5PPYB                    | Mini pc     | [9124f0eb45](https://bsd-hardware.info/?probe=9124f0eb45) | Aug 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [b3c0b4a4f4](https://bsd-hardware.info/?probe=b3c0b4a4f4) | Aug 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [612282319b](https://bsd-hardware.info/?probe=612282319b) | Aug 04, 2022 |
| Acer          | Revo 70                     | Desktop     | [0c23ffdc5a](https://bsd-hardware.info/?probe=0c23ffdc5a) | Aug 03, 2022 |
| Acer          | Aspire 5930                 | Notebook    | [4bd9ec4253](https://bsd-hardware.info/?probe=4bd9ec4253) | Aug 02, 2022 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [77f61a8711](https://bsd-hardware.info/?probe=77f61a8711) | Aug 01, 2022 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [3c33e546bb](https://bsd-hardware.info/?probe=3c33e546bb) | Jul 31, 2022 |
| Intel         | NUC5PPYB                    | Mini pc     | [d9a4a9745d](https://bsd-hardware.info/?probe=d9a4a9745d) | Jul 28, 2022 |
| HP            | 339A                        | Desktop     | [241e56a349](https://bsd-hardware.info/?probe=241e56a349) | Jul 27, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [511d057c70](https://bsd-hardware.info/?probe=511d057c70) | Jul 27, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [7b130fb168](https://bsd-hardware.info/?probe=7b130fb168) | Jul 27, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [3ba3cedec4](https://bsd-hardware.info/?probe=3ba3cedec4) | Jul 21, 2022 |
| Acer          | RS880M05                    | Desktop     | [7bcc14ceba](https://bsd-hardware.info/?probe=7bcc14ceba) | Jul 16, 2022 |
| Gigabyte      | H310M S2 x.x                | Desktop     | [b11ca9c369](https://bsd-hardware.info/?probe=b11ca9c369) | Jul 16, 2022 |
| Supermicro    | H8DGU                       | Server      | [172bfe70b5](https://bsd-hardware.info/?probe=172bfe70b5) | Jul 14, 2022 |
| Acer          | Revo 70                     | Desktop     | [aad484a882](https://bsd-hardware.info/?probe=aad484a882) | Jul 13, 2022 |
| Acer          | Revo 70                     | Desktop     | [c8b51a94bd](https://bsd-hardware.info/?probe=c8b51a94bd) | Jul 13, 2022 |
| Kraftway      | KWH77                       | Desktop     | [c34f44a495](https://bsd-hardware.info/?probe=c34f44a495) | Jul 12, 2022 |
| Gigabyte      | C1037UN-EU                  | Desktop     | [3644f56368](https://bsd-hardware.info/?probe=3644f56368) | Jul 10, 2022 |
| Intel         | DN2820FYK H24582-203        | Desktop     | [8a9a8cdbd0](https://bsd-hardware.info/?probe=8a9a8cdbd0) | Jul 08, 2022 |
| Intel         | NUC5PPYB                    | Mini pc     | [2d521e085b](https://bsd-hardware.info/?probe=2d521e085b) | Jul 08, 2022 |
| Lenovo        | NO DPK                      | Desktop     | [2c79a92fc4](https://bsd-hardware.info/?probe=2c79a92fc4) | Jul 06, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [12279c8a4b](https://bsd-hardware.info/?probe=12279c8a4b) | Jul 06, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [19a4b27ae7](https://bsd-hardware.info/?probe=19a4b27ae7) | Jul 05, 2022 |
| Acer          | Aspire XC-895 V:1.0         | Desktop     | [d67aa61a6b](https://bsd-hardware.info/?probe=d67aa61a6b) | Jul 05, 2022 |
| Acer          | Revo RN86                   | Desktop     | [2dc98202aa](https://bsd-hardware.info/?probe=2dc98202aa) | Jul 05, 2022 |
| Lenovo        | V580 20147                  | Notebook    | [0615e8260d](https://bsd-hardware.info/?probe=0615e8260d) | Jul 02, 2022 |
| Lenovo        | V580 20147                  | Notebook    | [6f1fd71366](https://bsd-hardware.info/?probe=6f1fd71366) | Jul 02, 2022 |
| HP            | ProLiant DL160 G6           | Server      | [a4c075339a](https://bsd-hardware.info/?probe=a4c075339a) | Jun 29, 2022 |
| Gigabyte      | G41MT-S2                    | Desktop     | [0563158740](https://bsd-hardware.info/?probe=0563158740) | Jun 28, 2022 |
| ASRock        | P67 Professional            | Desktop     | [3372d35113](https://bsd-hardware.info/?probe=3372d35113) | Jun 28, 2022 |
| Acer          | Aspire A114-33              | Notebook    | [d3659c85e9](https://bsd-hardware.info/?probe=d3659c85e9) | Jun 28, 2022 |
| Samsung       | R530/R730/R540              | Notebook    | [a4cd230718](https://bsd-hardware.info/?probe=a4cd230718) | Jun 27, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [e057898546](https://bsd-hardware.info/?probe=e057898546) | Jun 18, 2022 |
| Dell          | 07KY25 A00                  | Desktop     | [9981217b1b](https://bsd-hardware.info/?probe=9981217b1b) | Jun 16, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [067dbf3357](https://bsd-hardware.info/?probe=067dbf3357) | Jun 15, 2022 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [380218b2c1](https://bsd-hardware.info/?probe=380218b2c1) | Jun 12, 2022 |
| Pegatron      | 2A94h                       | Desktop     | [17078490f7](https://bsd-hardware.info/?probe=17078490f7) | Jun 11, 2022 |
| Pegatron      | 2A94h                       | Desktop     | [438d4f9b2f](https://bsd-hardware.info/?probe=438d4f9b2f) | Jun 09, 2022 |
| Gigabyte      | F2A75M-D3H                  | Desktop     | [ae3436167b](https://bsd-hardware.info/?probe=ae3436167b) | Jun 05, 2022 |
| Lenovo        | ThinkPad Yoga 260 20FES1... | Notebook    | [73ab89b8f0](https://bsd-hardware.info/?probe=73ab89b8f0) | Jun 05, 2022 |
| Lenovo        | ThinkPad Yoga 260 20FES1... | Notebook    | [637f87f44e](https://bsd-hardware.info/?probe=637f87f44e) | Jun 05, 2022 |
| Lenovo        | Aptio CRB SDK0E50515 STD    | Mini pc     | [260ae5b2fe](https://bsd-hardware.info/?probe=260ae5b2fe) | Jun 04, 2022 |
| Supermicro    | X9DRW                       | Server      | [bdfce3deff](https://bsd-hardware.info/?probe=bdfce3deff) | May 30, 2022 |
| Unknown       | Unknown                     | Desktop     | [a56bc64f26](https://bsd-hardware.info/?probe=a56bc64f26) | May 27, 2022 |
| ASUSTek       | P5LD2                       | Desktop     | [64208afa2c](https://bsd-hardware.info/?probe=64208afa2c) | May 25, 2022 |
| khadas        | edge-v                      | Desktop     | [60fb48e34c](https://bsd-hardware.info/?probe=60fb48e34c) | May 23, 2022 |
| khadas        | edge-v                      | Desktop     | [6facaa8032](https://bsd-hardware.info/?probe=6facaa8032) | May 22, 2022 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [1937e77b97](https://bsd-hardware.info/?probe=1937e77b97) | May 22, 2022 |
| HP            | ProLiant DL160 G5           | Server      | [e07440e3e0](https://bsd-hardware.info/?probe=e07440e3e0) | May 22, 2022 |
| Supermicro    | X9SRW-F                     | Server      | [89da730497](https://bsd-hardware.info/?probe=89da730497) | May 21, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | Notebook    | [cf5f498572](https://bsd-hardware.info/?probe=cf5f498572) | May 21, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [e7055d83e2](https://bsd-hardware.info/?probe=e7055d83e2) | May 20, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [c6944afe69](https://bsd-hardware.info/?probe=c6944afe69) | May 19, 2022 |
| Supermicro    | X10DRi-T                    | Desktop     | [d6fa145c7c](https://bsd-hardware.info/?probe=d6fa145c7c) | May 16, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [e569bffe8f](https://bsd-hardware.info/?probe=e569bffe8f) | May 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [64600e1c24](https://bsd-hardware.info/?probe=64600e1c24) | May 11, 2022 |
| Lenovo        | ThinkPad T495s 20QKS1812... | Notebook    | [89db84f7ec](https://bsd-hardware.info/?probe=89db84f7ec) | May 10, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [224614e9ab](https://bsd-hardware.info/?probe=224614e9ab) | May 10, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [76eef59920](https://bsd-hardware.info/?probe=76eef59920) | May 10, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [3ff916acf7](https://bsd-hardware.info/?probe=3ff916acf7) | May 09, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [33367fe342](https://bsd-hardware.info/?probe=33367fe342) | May 09, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [bf3d4941a2](https://bsd-hardware.info/?probe=bf3d4941a2) | May 06, 2022 |
| Acer          | Aspire ES1-132              | Notebook    | [18426698ad](https://bsd-hardware.info/?probe=18426698ad) | May 02, 2022 |
| HP            | Pavilion g6                 | Notebook    | [4b8ee6729a](https://bsd-hardware.info/?probe=4b8ee6729a) | May 02, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [24d308754b](https://bsd-hardware.info/?probe=24d308754b) | May 02, 2022 |
| Lenovo        | B50-30 20382                | Notebook    | [5701dac149](https://bsd-hardware.info/?probe=5701dac149) | Apr 30, 2022 |
| Unknown       | Unknown                     | Desktop     | [d036c00d6c](https://bsd-hardware.info/?probe=d036c00d6c) | Apr 28, 2022 |
| ASRock        | J3355B-ITX                  | Desktop     | [c0739686fb](https://bsd-hardware.info/?probe=c0739686fb) | Apr 28, 2022 |
| Supermicro    | X10DRi-T                    | Desktop     | [dcd02e012d](https://bsd-hardware.info/?probe=dcd02e012d) | Apr 28, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [1a475f0939](https://bsd-hardware.info/?probe=1a475f0939) | Apr 27, 2022 |
| ASRock        | X570S PG Riptide            | Desktop     | [928d2abb5e](https://bsd-hardware.info/?probe=928d2abb5e) | Apr 26, 2022 |
| Intel         | S3420GP E77063-304          | Server      | [09a475e0bc](https://bsd-hardware.info/?probe=09a475e0bc) | Apr 25, 2022 |
| HP            | ProLiant DL180 G6           | Server      | [3834dccb1f](https://bsd-hardware.info/?probe=3834dccb1f) | Apr 25, 2022 |
| Gigabyte      | H310M S2 x.x                | Desktop     | [549053284c](https://bsd-hardware.info/?probe=549053284c) | Apr 25, 2022 |
| PC Engines    | APU2                        | Desktop     | [04a6549c99](https://bsd-hardware.info/?probe=04a6549c99) | Apr 23, 2022 |
| Dell          | 0HD5W2 A00                  | Desktop     | [955922ebe2](https://bsd-hardware.info/?probe=955922ebe2) | Apr 23, 2022 |
| Dell          | 0HD5W2 A00                  | Desktop     | [4d66b2b328](https://bsd-hardware.info/?probe=4d66b2b328) | Apr 23, 2022 |
| Intel         | DH67BL                      | Desktop     | [3c3c9e12da](https://bsd-hardware.info/?probe=3c3c9e12da) | Apr 22, 2022 |
| KOHJINSHA     | SH series                   | Desktop     | [3136a0ca03](https://bsd-hardware.info/?probe=3136a0ca03) | Apr 22, 2022 |
| Lenovo        | ThinkPad X240 20ALA0AHRT    | Desktop     | [062a08c811](https://bsd-hardware.info/?probe=062a08c811) | Apr 22, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [427cf12b45](https://bsd-hardware.info/?probe=427cf12b45) | Apr 22, 2022 |
| DEXP          | NAVIS P100                  | Notebook    | [a9c8814bf8](https://bsd-hardware.info/?probe=a9c8814bf8) | Apr 22, 2022 |
| Sony          | VPCL22Z1R                   | Desktop     | [f199d57905](https://bsd-hardware.info/?probe=f199d57905) | Apr 22, 2022 |
| Lenovo        | ThinkPad X121e 3053A52      | Notebook    | [68d0bf2a99](https://bsd-hardware.info/?probe=68d0bf2a99) | Apr 22, 2022 |
| Samsung       | DP700A3D-X01RU SEC_SW_RE... | All in one  | [22febd212f](https://bsd-hardware.info/?probe=22febd212f) | Apr 22, 2022 |
| ASUSTek       | Z170-K                      | Desktop     | [b16705bbbd](https://bsd-hardware.info/?probe=b16705bbbd) | Apr 22, 2022 |
| ASUSTek       | P10S-I Series               | Desktop     | [aca13dba36](https://bsd-hardware.info/?probe=aca13dba36) | Apr 22, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [8e64404e52](https://bsd-hardware.info/?probe=8e64404e52) | Apr 19, 2022 |
| Shuttle       | DS20U                       | Desktop     | [f01372719f](https://bsd-hardware.info/?probe=f01372719f) | Apr 16, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [fa76da045a](https://bsd-hardware.info/?probe=fa76da045a) | Apr 13, 2022 |
| Gigabyte      | E3000N                      | Desktop     | [7169c296cc](https://bsd-hardware.info/?probe=7169c296cc) | Apr 08, 2022 |
| DNS           | W9x0LU                      | Notebook    | [8ac57e3b59](https://bsd-hardware.info/?probe=8ac57e3b59) | Apr 06, 2022 |
| Supermicro    | X10DRi-T                    | Desktop     | [e17bbe2186](https://bsd-hardware.info/?probe=e17bbe2186) | Apr 05, 2022 |
| Timi          | TM1612                      | Notebook    | [0389c8d487](https://bsd-hardware.info/?probe=0389c8d487) | Apr 05, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [1dd1823662](https://bsd-hardware.info/?probe=1dd1823662) | Apr 04, 2022 |
| Gigabyte      | H310M S2 x.x                | Desktop     | [29a9462f72](https://bsd-hardware.info/?probe=29a9462f72) | Apr 04, 2022 |
| Intel         | DCP847SKE                   | Desktop     | [a79e298be3](https://bsd-hardware.info/?probe=a79e298be3) | Apr 03, 2022 |
| Lenovo        | ThinkPad T490s 20NX000DR... | Notebook    | [c052d7cab0](https://bsd-hardware.info/?probe=c052d7cab0) | Apr 01, 2022 |
| Supermicro    | X10DRi-T                    | Desktop     | [eae4612261](https://bsd-hardware.info/?probe=eae4612261) | Mar 31, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [e750905413](https://bsd-hardware.info/?probe=e750905413) | Mar 29, 2022 |
| Lenovo        | 312D NOK                    | Mini pc     | [47ef9ef91a](https://bsd-hardware.info/?probe=47ef9ef91a) | Mar 27, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [00213ecee9](https://bsd-hardware.info/?probe=00213ecee9) | Mar 25, 2022 |
| MSI           | B85-G43                     | Desktop     | [f0a919c35f](https://bsd-hardware.info/?probe=f0a919c35f) | Mar 25, 2022 |
| MSI           | B85-G43                     | Desktop     | [7bd545fda8](https://bsd-hardware.info/?probe=7bd545fda8) | Mar 25, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [8696405d09](https://bsd-hardware.info/?probe=8696405d09) | Mar 24, 2022 |
| Lenovo        | 312D NOK                    | Mini pc     | [9b3dac520a](https://bsd-hardware.info/?probe=9b3dac520a) | Mar 24, 2022 |
| Acer          | Aspire A114-33              | Notebook    | [57765224eb](https://bsd-hardware.info/?probe=57765224eb) | Mar 18, 2022 |
| Packard Be... | EasyNote TE69HW             | Notebook    | [851eea349f](https://bsd-hardware.info/?probe=851eea349f) | Mar 17, 2022 |
| Supermicro    | A1SAi 123456789             | Mini pc     | [0f1362e9a9](https://bsd-hardware.info/?probe=0f1362e9a9) | Mar 16, 2022 |
| Acer          | Aspire 4820T                | Notebook    | [1617262a28](https://bsd-hardware.info/?probe=1617262a28) | Mar 16, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [7fb743c654](https://bsd-hardware.info/?probe=7fb743c654) | Mar 15, 2022 |
| Acer          | Aspire A114-33              | Notebook    | [6e7384f4cc](https://bsd-hardware.info/?probe=6e7384f4cc) | Mar 15, 2022 |
| Huanan        | X99-F8D V2.4                | Desktop     | [4ef193841e](https://bsd-hardware.info/?probe=4ef193841e) | Mar 13, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [5a22bb6991](https://bsd-hardware.info/?probe=5a22bb6991) | Mar 12, 2022 |
| MSI           | B350M BAZOOKA               | Desktop     | [bac8d0bdb7](https://bsd-hardware.info/?probe=bac8d0bdb7) | Mar 11, 2022 |
| ASUSTek       | M51Sr                       | Notebook    | [936a577d1a](https://bsd-hardware.info/?probe=936a577d1a) | Mar 10, 2022 |
| ASRock        | G41C-VS                     | Desktop     | [a9a1b1a493](https://bsd-hardware.info/?probe=a9a1b1a493) | Mar 03, 2022 |
| Intel         | DN2800MT AAG23738-600       | Desktop     | [8ecf2d023f](https://bsd-hardware.info/?probe=8ecf2d023f) | Mar 02, 2022 |
| Acer          | Aspire A114-33              | Notebook    | [62f4e0a060](https://bsd-hardware.info/?probe=62f4e0a060) | Feb 21, 2022 |
| Gigabyte      | X58A-UD5                    | Desktop     | [58d57520c1](https://bsd-hardware.info/?probe=58d57520c1) | Feb 20, 2022 |
| Acer          | Aspire A114-33              | Notebook    | [da786acd84](https://bsd-hardware.info/?probe=da786acd84) | Feb 20, 2022 |
| Gigabyte      | C1037UN-EU                  | Desktop     | [5b6dd82da8](https://bsd-hardware.info/?probe=5b6dd82da8) | Feb 18, 2022 |
| ASRock        | B460M Pro4                  | Desktop     | [7a2781344f](https://bsd-hardware.info/?probe=7a2781344f) | Feb 17, 2022 |
| Lenovo        | E31-80 80MX                 | Notebook    | [098afac660](https://bsd-hardware.info/?probe=098afac660) | Feb 16, 2022 |
| Acer          | Aspire A114-33              | Notebook    | [06887b10fd](https://bsd-hardware.info/?probe=06887b10fd) | Feb 15, 2022 |
| Firefly       | ROC-RK3566-PC               | Soc         | [b5c6aa26de](https://bsd-hardware.info/?probe=b5c6aa26de) | Feb 13, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [2dd03795ba](https://bsd-hardware.info/?probe=2dd03795ba) | Feb 11, 2022 |
| ASRock        | X370 Gaming X               | Desktop     | [22f8d133d4](https://bsd-hardware.info/?probe=22f8d133d4) | Feb 09, 2022 |
| ASRock        | D1800M                      | Desktop     | [0902154c8e](https://bsd-hardware.info/?probe=0902154c8e) | Feb 08, 2022 |
| Dell          | 0654JC A01                  | Desktop     | [bbcf2bad96](https://bsd-hardware.info/?probe=bbcf2bad96) | Feb 08, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [494195b923](https://bsd-hardware.info/?probe=494195b923) | Feb 08, 2022 |
| ASUSTek       | P5G41T-M                    | Desktop     | [a7d5b65ba1](https://bsd-hardware.info/?probe=a7d5b65ba1) | Feb 07, 2022 |
| MSI           | MS-7C96                     | Desktop     | [c08331ad58](https://bsd-hardware.info/?probe=c08331ad58) | Feb 06, 2022 |
| Kontron       | KT965/ATXP 61420000         | Desktop     | [b5389bbf43](https://bsd-hardware.info/?probe=b5389bbf43) | Feb 06, 2022 |
| Dell          | Venue 11 Pro 7140           | Notebook    | [328f9e8d94](https://bsd-hardware.info/?probe=328f9e8d94) | Feb 04, 2022 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [8af8b5270e](https://bsd-hardware.info/?probe=8af8b5270e) | Feb 04, 2022 |
| ASUSTek       | P4P800-VM                   | Desktop     | [2343c503a7](https://bsd-hardware.info/?probe=2343c503a7) | Feb 04, 2022 |
| HP            | Laptop 15-rb0xx             | Notebook    | [8e9a6cff62](https://bsd-hardware.info/?probe=8e9a6cff62) | Jan 31, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [58ea01e4e6](https://bsd-hardware.info/?probe=58ea01e4e6) | Jan 29, 2022 |
| Lenovo        | 30C9 NOK                    | Desktop     | [7169d2989c](https://bsd-hardware.info/?probe=7169d2989c) | Jan 29, 2022 |
| Pegatron      | IPPPV-D3G                   | Desktop     | [d5e44ccf6b](https://bsd-hardware.info/?probe=d5e44ccf6b) | Jan 28, 2022 |
| ASUSTek       | P5GC-MX                     | Desktop     | [372749f9d7](https://bsd-hardware.info/?probe=372749f9d7) | Jan 27, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [eb44c8d7e1](https://bsd-hardware.info/?probe=eb44c8d7e1) | Jan 27, 2022 |
| Firefly       | ROC-RK3566-PC               | Soc         | [aac0cd5332](https://bsd-hardware.info/?probe=aac0cd5332) | Jan 27, 2022 |
| ASUSTek       | P5B SE                      | Desktop     | [f97fba19c1](https://bsd-hardware.info/?probe=f97fba19c1) | Jan 26, 2022 |
| Kontron       | KT965/ATXP 61420000         | Desktop     | [36109b09ca](https://bsd-hardware.info/?probe=36109b09ca) | Jan 26, 2022 |
| MSI           | GE75 Raider 10SFS           | Notebook    | [48b172bfe8](https://bsd-hardware.info/?probe=48b172bfe8) | Jan 25, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [9f0a000ceb](https://bsd-hardware.info/?probe=9f0a000ceb) | Jan 25, 2022 |
| MSI           | GE75 Raider 10SFS           | Notebook    | [306f312c47](https://bsd-hardware.info/?probe=306f312c47) | Jan 25, 2022 |
| ASUSTek       | P5B SE                      | Desktop     | [e3332e7b94](https://bsd-hardware.info/?probe=e3332e7b94) | Jan 25, 2022 |
| ASRock        | B460M Pro4                  | Desktop     | [107a1e59f5](https://bsd-hardware.info/?probe=107a1e59f5) | Jan 25, 2022 |
| MSI           | G31TM-P21                   | Desktop     | [10ca6492c1](https://bsd-hardware.info/?probe=10ca6492c1) | Jan 25, 2022 |
| MSI           | G31TM-P21                   | Desktop     | [7563c4cf09](https://bsd-hardware.info/?probe=7563c4cf09) | Jan 25, 2022 |
| HP            | ProLiant DL180 G6           | Server      | [28f84e935f](https://bsd-hardware.info/?probe=28f84e935f) | Jan 25, 2022 |
| Kontron       | KT965/ATXP 61420000         | Desktop     | [db757ea2ef](https://bsd-hardware.info/?probe=db757ea2ef) | Jan 25, 2022 |
| Gigabyte      | H310M S2 x.x                | Desktop     | [b0aeac1ef8](https://bsd-hardware.info/?probe=b0aeac1ef8) | Jan 25, 2022 |
| Intel         | S3420GP E77063-304          | Server      | [acaa85b561](https://bsd-hardware.info/?probe=acaa85b561) | Jan 25, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [1c8f50f7eb](https://bsd-hardware.info/?probe=1c8f50f7eb) | Jan 24, 2022 |
| Wistron       | ProLiant DL120 G6           | Server      | [379fcf9804](https://bsd-hardware.info/?probe=379fcf9804) | Jan 24, 2022 |
| ASUSTek       | P5M2                        | Desktop     | [f2d4eccf4d](https://bsd-hardware.info/?probe=f2d4eccf4d) | Jan 24, 2022 |
| ASUSTek       | P7H55-M                     | Desktop     | [fb73c2f7dc](https://bsd-hardware.info/?probe=fb73c2f7dc) | Jan 23, 2022 |
| ASRock        | J3455-ITX                   | Desktop     | [55d70a3070](https://bsd-hardware.info/?probe=55d70a3070) | Jan 22, 2022 |
| ASRock        | J3455-ITX                   | Desktop     | [bf033b6b9f](https://bsd-hardware.info/?probe=bf033b6b9f) | Jan 22, 2022 |
| Intel         | DCP847SKE                   | Desktop     | [2828ef2a6d](https://bsd-hardware.info/?probe=2828ef2a6d) | Jan 20, 2022 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [0473b57d99](https://bsd-hardware.info/?probe=0473b57d99) | Jan 19, 2022 |
| Intel CNCT... | Unknown                     | Desktop     | [0debf023f1](https://bsd-hardware.info/?probe=0debf023f1) | Jan 18, 2022 |
| Gigabyte      | B365 HD3                    | Desktop     | [62fc48bd99](https://bsd-hardware.info/?probe=62fc48bd99) | Jan 15, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [d377e06101](https://bsd-hardware.info/?probe=d377e06101) | Jan 15, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | Desktop     | [384cbe9714](https://bsd-hardware.info/?probe=384cbe9714) | Jan 13, 2022 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [650628a974](https://bsd-hardware.info/?probe=650628a974) | Jan 10, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20T20... | Notebook    | [6836fc60f6](https://bsd-hardware.info/?probe=6836fc60f6) | Jan 09, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [7aea2ccaa7](https://bsd-hardware.info/?probe=7aea2ccaa7) | Jan 08, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [87c8ee9b4c](https://bsd-hardware.info/?probe=87c8ee9b4c) | Dec 31, 2021 |
| HP            | ProBook 655 G1              | Notebook    | [da312d7c14](https://bsd-hardware.info/?probe=da312d7c14) | Dec 30, 2021 |
| friendlyel... | nanopi-m4                   | Desktop     | [bb29e50061](https://bsd-hardware.info/?probe=bb29e50061) | Dec 27, 2021 |
| Unknown       | TI AM335x BeagleBone Bla... | Desktop     | [14d6cfb7a4](https://bsd-hardware.info/?probe=14d6cfb7a4) | Dec 27, 2021 |
| Unknown       | TI AM335x BeagleBone Bla... | Desktop     | [ce75fa56bd](https://bsd-hardware.info/?probe=ce75fa56bd) | Dec 27, 2021 |
| Unknown       | TI AM335x BeagleBone Bla... | Desktop     | [612825abe3](https://bsd-hardware.info/?probe=612825abe3) | Dec 27, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [4bb84a33fa](https://bsd-hardware.info/?probe=4bb84a33fa) | Dec 26, 2021 |
| khadas        | edge-v                      | Desktop     | [42c428aac0](https://bsd-hardware.info/?probe=42c428aac0) | Dec 26, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [0918f0a5b9](https://bsd-hardware.info/?probe=0918f0a5b9) | Dec 25, 2021 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [b0aa3885bb](https://bsd-hardware.info/?probe=b0aa3885bb) | Dec 25, 2021 |
| Acer          | Revo RN86                   | Desktop     | [6d184a1e62](https://bsd-hardware.info/?probe=6d184a1e62) | Dec 23, 2021 |
| Gigabyte      | E3000N                      | Desktop     | [eb0ba1b296](https://bsd-hardware.info/?probe=eb0ba1b296) | Dec 22, 2021 |
| HP            | 1850                        | Desktop     | [aa737033c4](https://bsd-hardware.info/?probe=aa737033c4) | Dec 21, 2021 |
| HP            | 1850                        | Desktop     | [17f42cda78](https://bsd-hardware.info/?probe=17f42cda78) | Dec 21, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [5cc62c68f9](https://bsd-hardware.info/?probe=5cc62c68f9) | Dec 21, 2021 |
| ASRock        | H110M-DGS                   | Desktop     | [40c4553adb](https://bsd-hardware.info/?probe=40c4553adb) | Dec 21, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [bc55ac50d1](https://bsd-hardware.info/?probe=bc55ac50d1) | Dec 20, 2021 |
| Acer          | Revo RN86                   | Desktop     | [68541bb331](https://bsd-hardware.info/?probe=68541bb331) | Dec 20, 2021 |
| Acer          | Aspire XC-895 V:1.0         | Desktop     | [58440d7663](https://bsd-hardware.info/?probe=58440d7663) | Dec 20, 2021 |
| MSI           | MS-9852 10                  | Desktop     | [4b851eef0a](https://bsd-hardware.info/?probe=4b851eef0a) | Dec 19, 2021 |
| ASUSTek       | P5G41T-M                    | Desktop     | [44bba395e8](https://bsd-hardware.info/?probe=44bba395e8) | Dec 13, 2021 |
| ASUSTek       | P5G41T-M                    | Desktop     | [1fb865c4ae](https://bsd-hardware.info/?probe=1fb865c4ae) | Dec 09, 2021 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [9fca53da56](https://bsd-hardware.info/?probe=9fca53da56) | Dec 08, 2021 |
| ASUSTek       | P5B                         | Desktop     | [93b542ab79](https://bsd-hardware.info/?probe=93b542ab79) | Dec 06, 2021 |
| Gigabyte      | GA-8S661FXM-775             | Desktop     | [3a64909558](https://bsd-hardware.info/?probe=3a64909558) | Dec 06, 2021 |
| Gigabyte      | MZGLKBP-00                  | Desktop     | [e713e3adee](https://bsd-hardware.info/?probe=e713e3adee) | Dec 05, 2021 |
| Unknown       | Q2XX V1.1                   | Desktop     | [66d6a26e35](https://bsd-hardware.info/?probe=66d6a26e35) | Dec 04, 2021 |
| Unknown       | Unknown                     | Desktop     | [a91c9ec877](https://bsd-hardware.info/?probe=a91c9ec877) | Dec 04, 2021 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [0d4c532744](https://bsd-hardware.info/?probe=0d4c532744) | Nov 29, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [ade9f77281](https://bsd-hardware.info/?probe=ade9f77281) | Nov 25, 2021 |
| Acer          | Aspire 3810T                | Notebook    | [86782a69be](https://bsd-hardware.info/?probe=86782a69be) | Nov 13, 2021 |
| Acer          | Aspire 3810T                | Notebook    | [608e43163d](https://bsd-hardware.info/?probe=608e43163d) | Nov 12, 2021 |
| Firefly       | roc-rk3399-pc-plus          | Desktop     | [dab56eef53](https://bsd-hardware.info/?probe=dab56eef53) | Nov 07, 2021 |
| Firefly       | roc-rk3399-pc-plus          | Desktop     | [f26b302e43](https://bsd-hardware.info/?probe=f26b302e43) | Nov 07, 2021 |
| Unknown       | Intel X79                   | Desktop     | [044908e7c3](https://bsd-hardware.info/?probe=044908e7c3) | Oct 30, 2021 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [4c9b877754](https://bsd-hardware.info/?probe=4c9b877754) | Oct 29, 2021 |
| Edelweiss     | TF307-MB-S-D                | Soc         | [2478821f6e](https://bsd-hardware.info/?probe=2478821f6e) | Oct 28, 2021 |
| HP            | 0A60h                       | Desktop     | [5c227c5b61](https://bsd-hardware.info/?probe=5c227c5b61) | Oct 27, 2021 |
| Radxa         | rock-pi-4                   | Desktop     | [767ef0f0a6](https://bsd-hardware.info/?probe=767ef0f0a6) | Oct 27, 2021 |
| Edelweiss     | TF307-MB-S-D                | Soc         | [b0ef9f0259](https://bsd-hardware.info/?probe=b0ef9f0259) | Oct 27, 2021 |
| Radxa         | rock-pi-4                   | Desktop     | [fcd3e65f7e](https://bsd-hardware.info/?probe=fcd3e65f7e) | Oct 26, 2021 |
| Acer          | RS880M05                    | Desktop     | [4718f0cb0c](https://bsd-hardware.info/?probe=4718f0cb0c) | Oct 21, 2021 |
| Radxa         | rock-pi-4                   | Desktop     | [876564310f](https://bsd-hardware.info/?probe=876564310f) | Oct 19, 2021 |
| Unknown       | Unknown                     | Desktop     | [9716564d5e](https://bsd-hardware.info/?probe=9716564d5e) | Oct 19, 2021 |
| Firefly       | roc-rk3399-pc-plus          | Desktop     | [39c78ac754](https://bsd-hardware.info/?probe=39c78ac754) | Oct 19, 2021 |
| ASUSTek       | P5P43TD PRO                 | Desktop     | [2870e26de1](https://bsd-hardware.info/?probe=2870e26de1) | Oct 17, 2021 |
| Firefly       | roc-rk3399-pc-plus          | Desktop     | [5173ffc13b](https://bsd-hardware.info/?probe=5173ffc13b) | Oct 17, 2021 |
| Dell          | 0Y7WYT A00                  | Desktop     | [1de7ed2a67](https://bsd-hardware.info/?probe=1de7ed2a67) | Oct 16, 2021 |
| Lenovo        | SHARKBAY No DPK             | Desktop     | [e762f9146e](https://bsd-hardware.info/?probe=e762f9146e) | Oct 16, 2021 |
| ASUSTek       | P10S-I Series               | Desktop     | [d086bf947a](https://bsd-hardware.info/?probe=d086bf947a) | Oct 15, 2021 |
| ASUSTek       | F2A85-M                     | Desktop     | [b4e3f33e5c](https://bsd-hardware.info/?probe=b4e3f33e5c) | Oct 14, 2021 |
| Lenovo        | SHARKBAY No DPK             | Desktop     | [14dcd924b5](https://bsd-hardware.info/?probe=14dcd924b5) | Oct 13, 2021 |
| Lenovo        | S20-30 Touch 20434          | Notebook    | [141a393d54](https://bsd-hardware.info/?probe=141a393d54) | Oct 08, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [d09f63f257](https://bsd-hardware.info/?probe=d09f63f257) | Oct 07, 2021 |
| Intel         | J1900                       | Desktop     | [9d6c7612d3](https://bsd-hardware.info/?probe=9d6c7612d3) | Oct 05, 2021 |
| ASUSTek       | UX21A                       | Notebook    | [fe08d28d4c](https://bsd-hardware.info/?probe=fe08d28d4c) | Oct 05, 2021 |
| HP            | 81BA                        | All in one  | [c2204a3dd2](https://bsd-hardware.info/?probe=c2204a3dd2) | Oct 04, 2021 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [bd312d1c88](https://bsd-hardware.info/?probe=bd312d1c88) | Oct 03, 2021 |
| IBM           | ThinkPad H 1846AQG          | Notebook    | [5e5c7247ca](https://bsd-hardware.info/?probe=5e5c7247ca) | Oct 01, 2021 |
| Unknown       | Unknown                     | Desktop     | [b45dad63f6](https://bsd-hardware.info/?probe=b45dad63f6) | Sep 20, 2021 |
| Unknown       | Unknown                     | Desktop     | [ed7c1c1f3b](https://bsd-hardware.info/?probe=ed7c1c1f3b) | Sep 20, 2021 |
| Firefly       | roc-rk3399-pc-plus          | Desktop     | [198c4264f9](https://bsd-hardware.info/?probe=198c4264f9) | Sep 16, 2021 |
| Firefly       | roc-rk3399-pc-plus          | Desktop     | [062602e8db](https://bsd-hardware.info/?probe=062602e8db) | Sep 15, 2021 |
| ASRock        | B450M Pro4-F                | Desktop     | [ae1765efd5](https://bsd-hardware.info/?probe=ae1765efd5) | Sep 10, 2021 |
| Gigabyte      | Z68P-DS3                    | Desktop     | [9a2545337b](https://bsd-hardware.info/?probe=9a2545337b) | Sep 09, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [8b51d2aabb](https://bsd-hardware.info/?probe=8b51d2aabb) | Sep 09, 2021 |
| ASUSTek       | VX7SX                       | Notebook    | [6ca36a455d](https://bsd-hardware.info/?probe=6ca36a455d) | Sep 09, 2021 |
| Kraftway      | KW10T                       | Notebook    | [4810842d82](https://bsd-hardware.info/?probe=4810842d82) | Sep 06, 2021 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [01ac3a91d0](https://bsd-hardware.info/?probe=01ac3a91d0) | Sep 01, 2021 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [aeb23122b6](https://bsd-hardware.info/?probe=aeb23122b6) | Aug 31, 2021 |
| Apple         | Mac-F2268CC8                | All in one  | [28bf815655](https://bsd-hardware.info/?probe=28bf815655) | Aug 30, 2021 |
| Intel         | DG33BU AAD79951-408         | Desktop     | [e8f4f644e3](https://bsd-hardware.info/?probe=e8f4f644e3) | Aug 30, 2021 |
| ASUSTek       | P4P800-VM                   | Desktop     | [f23a539453](https://bsd-hardware.info/?probe=f23a539453) | Aug 30, 2021 |
| Unknown       | Q2XX V1.1                   | Desktop     | [5ca9aa0bf2](https://bsd-hardware.info/?probe=5ca9aa0bf2) | Aug 19, 2021 |
| Gigabyte      | HA65M-D2H-B3                | Desktop     | [fc9b50bb85](https://bsd-hardware.info/?probe=fc9b50bb85) | Aug 16, 2021 |
| Supermicro    | X10DRH-CT                   | Desktop     | [6ccb3c09d6](https://bsd-hardware.info/?probe=6ccb3c09d6) | Aug 12, 2021 |
| Pegatron      | IPPCR-SS                    | Desktop     | [8a7fc2689b](https://bsd-hardware.info/?probe=8a7fc2689b) | Aug 09, 2021 |
| MSI           | H81M-P33                    | Desktop     | [6dcb3aa559](https://bsd-hardware.info/?probe=6dcb3aa559) | Aug 05, 2021 |
| ASRock        | X570 Pro4                   | Desktop     | [011fb96fe0](https://bsd-hardware.info/?probe=011fb96fe0) | Aug 04, 2021 |
| Supermicro    | X8DTU                       | Server      | [2862bf1465](https://bsd-hardware.info/?probe=2862bf1465) | Jul 29, 2021 |
| Lenovo        | ThinkPad E590 20NB0012RT    | Notebook    | [98072b8db6](https://bsd-hardware.info/?probe=98072b8db6) | Jul 26, 2021 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [3fb09d0402](https://bsd-hardware.info/?probe=3fb09d0402) | Jul 24, 2021 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [bef816fe74](https://bsd-hardware.info/?probe=bef816fe74) | Jul 24, 2021 |
| Gigabyte      | PH67A-D3-B3                 | Desktop     | [73dff53f04](https://bsd-hardware.info/?probe=73dff53f04) | Jul 23, 2021 |
| Acer          | Aspire A715-75G             | Notebook    | [f613cb0452](https://bsd-hardware.info/?probe=f613cb0452) | Jul 23, 2021 |
| Dell          | Inspiron 5758               | Notebook    | [7542ae751d](https://bsd-hardware.info/?probe=7542ae751d) | Jul 20, 2021 |
| HP            | ProLiant DL360e Gen8        | Desktop     | [30eeb098b0](https://bsd-hardware.info/?probe=30eeb098b0) | Jul 10, 2021 |
| HP            | ProLiant DL320 G5           | Desktop     | [3b4ee33976](https://bsd-hardware.info/?probe=3b4ee33976) | Jul 10, 2021 |
| Foxconn       | AT-7000 Series              | Desktop     | [3802fb98b5](https://bsd-hardware.info/?probe=3802fb98b5) | Jul 10, 2021 |
| MSI           | H81M-E33                    | Desktop     | [c9fda90944](https://bsd-hardware.info/?probe=c9fda90944) | Jul 08, 2021 |
| Pegatron      | IPPCR-SS                    | Desktop     | [86b2e85d24](https://bsd-hardware.info/?probe=86b2e85d24) | Jul 05, 2021 |
| eMachines     | eM350                       | Notebook    | [94579b896e](https://bsd-hardware.info/?probe=94579b896e) | Jul 04, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [e7a0dfcecf](https://bsd-hardware.info/?probe=e7a0dfcecf) | Jun 28, 2021 |
| Supermicro    | X10DRH-CT                   | Desktop     | [583e9e5a66](https://bsd-hardware.info/?probe=583e9e5a66) | Jun 26, 2021 |
| ECS           | A740GM-M                    | Desktop     | [a9d9106f11](https://bsd-hardware.info/?probe=a9d9106f11) | Jun 24, 2021 |
| eMachines     | eM350                       | Notebook    | [52198cfd80](https://bsd-hardware.info/?probe=52198cfd80) | Jun 22, 2021 |
| eMachines     | eM350                       | Notebook    | [60b4338ace](https://bsd-hardware.info/?probe=60b4338ace) | Jun 22, 2021 |
| Gigabyte      | GA-IMB370TN                 | Desktop     | [449fc82ff8](https://bsd-hardware.info/?probe=449fc82ff8) | Jun 21, 2021 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [45b842180e](https://bsd-hardware.info/?probe=45b842180e) | Jun 20, 2021 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [0cb30b464d](https://bsd-hardware.info/?probe=0cb30b464d) | Jun 17, 2021 |
| ASUSTek       | M4A78LT-M                   | Desktop     | [0c8d6cd661](https://bsd-hardware.info/?probe=0c8d6cd661) | Jun 14, 2021 |
| Intel         | X79 V2.72A                  | Desktop     | [88173bcf06](https://bsd-hardware.info/?probe=88173bcf06) | Jun 14, 2021 |
| ASUSTek       | P5K SE/EPU                  | Desktop     | [60d9b24b69](https://bsd-hardware.info/?probe=60d9b24b69) | Jun 13, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [4ac6c9b3eb](https://bsd-hardware.info/?probe=4ac6c9b3eb) | Jun 08, 2021 |
| Acer          | Aspire ES1-132              | Notebook    | [62c87cf194](https://bsd-hardware.info/?probe=62c87cf194) | Jun 07, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [8fc867cfae](https://bsd-hardware.info/?probe=8fc867cfae) | Jun 06, 2021 |
| Lenovo        | ThinkPad T430 23511A6       | Notebook    | [89fb2aa493](https://bsd-hardware.info/?probe=89fb2aa493) | Jun 05, 2021 |
| Acer          | Aspire ES1-132              | Notebook    | [bf605b741b](https://bsd-hardware.info/?probe=bf605b741b) | Jun 04, 2021 |
| Intel         | S2600WTTR G92187-372        | Server      | [289d61b1b2](https://bsd-hardware.info/?probe=289d61b1b2) | Jun 04, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [84e93d02e1](https://bsd-hardware.info/?probe=84e93d02e1) | Jun 03, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [1bb850edca](https://bsd-hardware.info/?probe=1bb850edca) | Jun 03, 2021 |
| Gigabyte      | GA-IMB370TN                 | Desktop     | [b486e670fe](https://bsd-hardware.info/?probe=b486e670fe) | Jun 02, 2021 |
| Biostar       | TH67B                       | Desktop     | [1f2321ec41](https://bsd-hardware.info/?probe=1f2321ec41) | Jun 01, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [d9657e7246](https://bsd-hardware.info/?probe=d9657e7246) | Jun 01, 2021 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [8c06f6b716](https://bsd-hardware.info/?probe=8c06f6b716) | Jun 01, 2021 |
| Apple         | PowerMac10,1                | Desktop     | [d098ba539d](https://bsd-hardware.info/?probe=d098ba539d) | May 27, 2021 |
| ASUSTek       | P7H55-M/USB3                | Desktop     | [87068a97be](https://bsd-hardware.info/?probe=87068a97be) | May 26, 2021 |
| Unknown       | Unknown                     | Desktop     | [f9fa9ae41a](https://bsd-hardware.info/?probe=f9fa9ae41a) | May 24, 2021 |
| Acer          | Revo RN86                   | Desktop     | [ec302a221a](https://bsd-hardware.info/?probe=ec302a221a) | May 15, 2021 |
| Unknown       | Unknown                     | Desktop     | [364a778de1](https://bsd-hardware.info/?probe=364a778de1) | May 14, 2021 |
| ASUSTek       | Z87-PLUS                    | Desktop     | [629d15378d](https://bsd-hardware.info/?probe=629d15378d) | May 10, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [ae105fb8bc](https://bsd-hardware.info/?probe=ae105fb8bc) | May 09, 2021 |
| ASUSTek       | Maximus II Formula          | Desktop     | [493bb4da66](https://bsd-hardware.info/?probe=493bb4da66) | May 07, 2021 |
| Gigabyte      | X58A-UD5                    | Desktop     | [24502c7f7b](https://bsd-hardware.info/?probe=24502c7f7b) | May 04, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [87c4175f48](https://bsd-hardware.info/?probe=87c4175f48) | May 03, 2021 |
| ASUSTek       | P10S-I Series               | Desktop     | [6548ae7d88](https://bsd-hardware.info/?probe=6548ae7d88) | May 01, 2021 |
| ASUSTek       | SABERTOOTH Z97 MARK 2       | Desktop     | [8055ed41df](https://bsd-hardware.info/?probe=8055ed41df) | Apr 25, 2021 |
| Gigabyte      | F2A75M-HD2                  | Desktop     | [18a74377ac](https://bsd-hardware.info/?probe=18a74377ac) | Apr 25, 2021 |
| Unknown       | Q2XX V1.1                   | Desktop     | [5c7ea7fb7d](https://bsd-hardware.info/?probe=5c7ea7fb7d) | Apr 24, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [ab8235808d](https://bsd-hardware.info/?probe=ab8235808d) | Apr 23, 2021 |
| HP            | 8430 1000                   | All in one  | [0d21e083f4](https://bsd-hardware.info/?probe=0d21e083f4) | Apr 20, 2021 |
| Gigabyte      | C1037UN-EU                  | Desktop     | [a379c24586](https://bsd-hardware.info/?probe=a379c24586) | Apr 19, 2021 |
| Gigabyte      | GA-IMB370TN                 | Desktop     | [7c77a33f75](https://bsd-hardware.info/?probe=7c77a33f75) | Apr 18, 2021 |
| Unknown       | Unknown                     | Desktop     | [48090193c1](https://bsd-hardware.info/?probe=48090193c1) | Apr 17, 2021 |
| Unknown       | Unknown                     | Desktop     | [1c4a81b9a5](https://bsd-hardware.info/?probe=1c4a81b9a5) | Apr 17, 2021 |
| Unknown       | Unknown                     | Desktop     | [7b295345e6](https://bsd-hardware.info/?probe=7b295345e6) | Apr 17, 2021 |
| Unknown       | Unknown                     | Desktop     | [0c708350cd](https://bsd-hardware.info/?probe=0c708350cd) | Apr 17, 2021 |
| Gigabyte      | GA-IMB370TN                 | Desktop     | [513027c242](https://bsd-hardware.info/?probe=513027c242) | Apr 13, 2021 |
| Acer          | Extensa 2540                | Notebook    | [e7d6ece4ba](https://bsd-hardware.info/?probe=e7d6ece4ba) | Apr 11, 2021 |
| ASUSTek       | 1225B                       | Notebook    | [3eff93bfb5](https://bsd-hardware.info/?probe=3eff93bfb5) | Mar 31, 2021 |
| Gigabyte      | GA-IMB370TN                 | Desktop     | [8023a25ccb](https://bsd-hardware.info/?probe=8023a25ccb) | Mar 29, 2021 |
| Samsung       | N145P/N250P/N260P           | Notebook    | [a38a620353](https://bsd-hardware.info/?probe=a38a620353) | Mar 29, 2021 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [342e914968](https://bsd-hardware.info/?probe=342e914968) | Mar 29, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [dd877e6c6c](https://bsd-hardware.info/?probe=dd877e6c6c) | Mar 27, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | Desktop     | [ec9e43382e](https://bsd-hardware.info/?probe=ec9e43382e) | Mar 25, 2021 |
| ASRock        | H71M-DGS                    | Desktop     | [d05d6281d3](https://bsd-hardware.info/?probe=d05d6281d3) | Mar 21, 2021 |
| ASUSTek       | P8H77-I                     | Desktop     | [46d36c6b23](https://bsd-hardware.info/?probe=46d36c6b23) | Mar 21, 2021 |
| Samsung       | N145P/N250P/N260P           | Notebook    | [eff02dafe1](https://bsd-hardware.info/?probe=eff02dafe1) | Mar 18, 2021 |
| Intel         | PB_1900A V2.1               | Desktop     | [a2378c3bee](https://bsd-hardware.info/?probe=a2378c3bee) | Mar 17, 2021 |
| Lenovo        | ThinkPad T480s 20L7001HR... | Notebook    | [ebd44c21d9](https://bsd-hardware.info/?probe=ebd44c21d9) | Mar 17, 2021 |
| Samsung       | N150P                       | Notebook    | [68483fab9d](https://bsd-hardware.info/?probe=68483fab9d) | Mar 14, 2021 |
| Apple         | MacBookAir6,2               | Notebook    | [52584aaa97](https://bsd-hardware.info/?probe=52584aaa97) | Mar 14, 2021 |
| Apple         | MacBookAir6,2               | Notebook    | [fb136a79e7](https://bsd-hardware.info/?probe=fb136a79e7) | Mar 13, 2021 |
| ASUSTek       | AT5NM10T-I                  | Desktop     | [7c26a8b81e](https://bsd-hardware.info/?probe=7c26a8b81e) | Mar 12, 2021 |
| Dell          | Latitude 3410               | Notebook    | [80d7bf959a](https://bsd-hardware.info/?probe=80d7bf959a) | Mar 10, 2021 |
| HP            | 255 G3                      | Notebook    | [861bdc647d](https://bsd-hardware.info/?probe=861bdc647d) | Mar 09, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [1fcde7c0e1](https://bsd-hardware.info/?probe=1fcde7c0e1) | Mar 09, 2021 |
| ASRock        | Q1900M                      | Desktop     | [f366c06928](https://bsd-hardware.info/?probe=f366c06928) | Mar 09, 2021 |
| HP            | 255 G3                      | Notebook    | [bd82ed65e9](https://bsd-hardware.info/?probe=bd82ed65e9) | Mar 07, 2021 |
| Gigabyte      | EG43M-S2H                   | Desktop     | [f6eaa55ada](https://bsd-hardware.info/?probe=f6eaa55ada) | Mar 06, 2021 |
| ASUSTek       | STRIX B250F GAMING          | Desktop     | [cf965a3a5b](https://bsd-hardware.info/?probe=cf965a3a5b) | Mar 06, 2021 |
| HP            | ProLiant DL180 G6           | Server      | [4907dd5d8f](https://bsd-hardware.info/?probe=4907dd5d8f) | Mar 03, 2021 |
| Supermicro    | X8DTU                       | Server      | [6dd2d44aa1](https://bsd-hardware.info/?probe=6dd2d44aa1) | Mar 03, 2021 |
| Gigabyte      | 8IG1000MK                   | Desktop     | [49ee1efce0](https://bsd-hardware.info/?probe=49ee1efce0) | Mar 01, 2021 |
| Intel         | S3420GP E77063-304          | Server      | [044617a994](https://bsd-hardware.info/?probe=044617a994) | Mar 01, 2021 |
| Kontron       | KT965/ATXP 61420000         | Desktop     | [8755a0003d](https://bsd-hardware.info/?probe=8755a0003d) | Mar 01, 2021 |
| HP            | Compaq 6820s                | Notebook    | [f63d65b78c](https://bsd-hardware.info/?probe=f63d65b78c) | Feb 26, 2021 |
| Lenovo        | Board                       | Desktop     | [395ef09e6d](https://bsd-hardware.info/?probe=395ef09e6d) | Feb 25, 2021 |
| Lenovo        | Board                       | Desktop     | [96fbaf0644](https://bsd-hardware.info/?probe=96fbaf0644) | Feb 25, 2021 |
| ASRock        | G31M-VS2                    | Desktop     | [6c7150dc1b](https://bsd-hardware.info/?probe=6c7150dc1b) | Feb 24, 2021 |
| Acer          | TPDS05 R3700                | Desktop     | [651f8a2bb4](https://bsd-hardware.info/?probe=651f8a2bb4) | Feb 23, 2021 |
| PC Engines    | APU2                        | Desktop     | [02a107a767](https://bsd-hardware.info/?probe=02a107a767) | Feb 23, 2021 |
| ASRock        | J4205-ITX                   | Desktop     | [c8e0b22858](https://bsd-hardware.info/?probe=c8e0b22858) | Feb 23, 2021 |
| Dell          | Studio 1537                 | Notebook    | [a4c1d361eb](https://bsd-hardware.info/?probe=a4c1d361eb) | Feb 23, 2021 |
| Intel         | NUC5PPYB H76558-107         | Mini pc     | [2c106472cb](https://bsd-hardware.info/?probe=2c106472cb) | Feb 22, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [8390039d0b](https://bsd-hardware.info/?probe=8390039d0b) | Feb 22, 2021 |
| Apple         | MacBook5,1                  | Notebook    | [41ea02c8bc](https://bsd-hardware.info/?probe=41ea02c8bc) | Feb 21, 2021 |
| Sophos        | SG                          | Firewall    | [b1c99da59c](https://bsd-hardware.info/?probe=b1c99da59c) | Feb 20, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [8e52de9bec](https://bsd-hardware.info/?probe=8e52de9bec) | Feb 19, 2021 |
| Apple         | MacBook5,1                  | Notebook    | [1a374f79df](https://bsd-hardware.info/?probe=1a374f79df) | Feb 19, 2021 |
| ASRock        | Z170 Pro4/D3                | Desktop     | [7df0653726](https://bsd-hardware.info/?probe=7df0653726) | Feb 19, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | Notebook    | [ed75b3d15b](https://bsd-hardware.info/?probe=ed75b3d15b) | Feb 18, 2021 |
| ASUSTek       | H87I-PLUS                   | Desktop     | [8f8f08f763](https://bsd-hardware.info/?probe=8f8f08f763) | Feb 17, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | Notebook    | [3df4abb2e9](https://bsd-hardware.info/?probe=3df4abb2e9) | Feb 16, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | Desktop     | [ae42a14150](https://bsd-hardware.info/?probe=ae42a14150) | Feb 16, 2021 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [24551b886c](https://bsd-hardware.info/?probe=24551b886c) | Feb 16, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [ada1119026](https://bsd-hardware.info/?probe=ada1119026) | Feb 14, 2021 |
| ASRock        | B550M Pro4                  | Desktop     | [61a5641019](https://bsd-hardware.info/?probe=61a5641019) | Feb 14, 2021 |
| Lenovo        | ThinkPad T495s 20QKS1812... | Notebook    | [0e5e228d18](https://bsd-hardware.info/?probe=0e5e228d18) | Feb 13, 2021 |
| Lenovo        | ThinkPad T495s 20QKS1812... | Notebook    | [2d93a6bebc](https://bsd-hardware.info/?probe=2d93a6bebc) | Feb 13, 2021 |
| Sony          | VPCX115KX                   | Notebook    | [fef3d94e6c](https://bsd-hardware.info/?probe=fef3d94e6c) | Feb 12, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [ac6b550ff4](https://bsd-hardware.info/?probe=ac6b550ff4) | Feb 12, 2021 |
| ASUSTek       | P8H77-V                     | Desktop     | [aaaffba650](https://bsd-hardware.info/?probe=aaaffba650) | Feb 11, 2021 |
| ASUSTek       | P5GDC Pro                   | Desktop     | [ca50169bf4](https://bsd-hardware.info/?probe=ca50169bf4) | Feb 11, 2021 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [65e5edcfd7](https://bsd-hardware.info/?probe=65e5edcfd7) | Feb 11, 2021 |
| ASRock        | J3455M                      | Desktop     | [0493901aff](https://bsd-hardware.info/?probe=0493901aff) | Feb 10, 2021 |
| Acer          | Extensa 5635Z               | Notebook    | [3b4a7e7fc2](https://bsd-hardware.info/?probe=3b4a7e7fc2) | Feb 10, 2021 |
| ASRock        | H61M-S                      | Desktop     | [f7b01b5274](https://bsd-hardware.info/?probe=f7b01b5274) | Feb 08, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [4a36ea2ecd](https://bsd-hardware.info/?probe=4a36ea2ecd) | Feb 07, 2021 |
| Gigabyte      | Z68A-D3H-B3                 | Desktop     | [e1c3b89d0d](https://bsd-hardware.info/?probe=e1c3b89d0d) | Feb 06, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [b35f7a5610](https://bsd-hardware.info/?probe=b35f7a5610) | Feb 05, 2021 |
| Lenovo        | ThinkPad E480 20KN005CRT    | Notebook    | [503378cac9](https://bsd-hardware.info/?probe=503378cac9) | Jan 31, 2021 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [e2fd3451b6](https://bsd-hardware.info/?probe=e2fd3451b6) | Jan 26, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [2a81a1bd1f](https://bsd-hardware.info/?probe=2a81a1bd1f) | Jan 24, 2021 |
| MSI           | MS-7235                     | Desktop     | [6a0d60ad2c](https://bsd-hardware.info/?probe=6a0d60ad2c) | Jan 21, 2021 |
| Dell          | 0Y7WYT A00                  | Desktop     | [4af9b92154](https://bsd-hardware.info/?probe=4af9b92154) | Jan 19, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [ad33eaab8a](https://bsd-hardware.info/?probe=ad33eaab8a) | Jan 19, 2021 |
| Sony          | VPCM13M1R                   | Notebook    | [30bb4fc23c](https://bsd-hardware.info/?probe=30bb4fc23c) | Jan 06, 2021 |
| ASUSTek       | X101CH                      | Notebook    | [112792b300](https://bsd-hardware.info/?probe=112792b300) | Jan 02, 2021 |
| ASUSTek       | X101CH                      | Notebook    | [8b571cc947](https://bsd-hardware.info/?probe=8b571cc947) | Jan 02, 2021 |
| Centerm       | C30                         | Desktop     | [862ffd88e6](https://bsd-hardware.info/?probe=862ffd88e6) | Dec 16, 2020 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [0309e4ac24](https://bsd-hardware.info/?probe=0309e4ac24) | Dec 16, 2020 |
| Gigabyte      | Z68P-DS3                    | Desktop     | [a1fe36fd99](https://bsd-hardware.info/?probe=a1fe36fd99) | Dec 16, 2020 |
| HP            | ProLiant DL360e Gen8        | Server      | [e22af8ee52](https://bsd-hardware.info/?probe=e22af8ee52) | Dec 16, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [c8c11a071d](https://bsd-hardware.info/?probe=c8c11a071d) | Dec 14, 2020 |
| Acer          | Aspire V5-122               | Notebook    | [ce0c079fd5](https://bsd-hardware.info/?probe=ce0c079fd5) | Dec 14, 2020 |
| Intel         | S5000PSL                    | Server      | [0546131058](https://bsd-hardware.info/?probe=0546131058) | Dec 14, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [fb6286f788](https://bsd-hardware.info/?probe=fb6286f788) | Dec 13, 2020 |
| Panasonic     | CF-19AHNC8FN                | Notebook    | [04a42812bb](https://bsd-hardware.info/?probe=04a42812bb) | Dec 11, 2020 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [3a78e7dc1a](https://bsd-hardware.info/?probe=3a78e7dc1a) | Dec 11, 2020 |
| Samsung       | N145P/N250P/N260P           | Notebook    | [b4cb55c681](https://bsd-hardware.info/?probe=b4cb55c681) | Dec 05, 2020 |
| ASUSTek       | P4P800-VM                   | Desktop     | [4fe4c14195](https://bsd-hardware.info/?probe=4fe4c14195) | Dec 05, 2020 |
| Acer          | Aspire XC-895 V:1.0         | Desktop     | [c5017eff06](https://bsd-hardware.info/?probe=c5017eff06) | Dec 04, 2020 |
| PC Engines    | APU2                        | Desktop     | [90d68eee14](https://bsd-hardware.info/?probe=90d68eee14) | Dec 04, 2020 |
| PC Engines    | APU2                        | Desktop     | [fab3041b1e](https://bsd-hardware.info/?probe=fab3041b1e) | Dec 04, 2020 |
| Gigabyte      | Unknown                     | Desktop     | [8a9ae48d42](https://bsd-hardware.info/?probe=8a9ae48d42) | Dec 01, 2020 |
| Sony          | SVP1321V9RB                 | Notebook    | [9cddee6a0a](https://bsd-hardware.info/?probe=9cddee6a0a) | Dec 01, 2020 |
| ASRock        | N68-GE                      | Desktop     | [ce9159c2fa](https://bsd-hardware.info/?probe=ce9159c2fa) | Nov 30, 2020 |
| Unknown       | Unknown                     | Desktop     | [153be3caa3](https://bsd-hardware.info/?probe=153be3caa3) | Nov 28, 2020 |
| ASRock        | N68-GE                      | Desktop     | [028eabaec2](https://bsd-hardware.info/?probe=028eabaec2) | Nov 28, 2020 |
| ASUSTek       | H97M-E                      | Desktop     | [c3230a9065](https://bsd-hardware.info/?probe=c3230a9065) | Nov 23, 2020 |
| ASUSTek       | P5GDC Pro                   | Desktop     | [8776b186c1](https://bsd-hardware.info/?probe=8776b186c1) | Nov 14, 2020 |
| ASRock        | X570 Steel Legend           | Desktop     | [8a79e3f5e4](https://bsd-hardware.info/?probe=8a79e3f5e4) | Nov 11, 2020 |
| Sony          | VGN-S150(UC)                | Notebook    | [f2f3923ea6](https://bsd-hardware.info/?probe=f2f3923ea6) | Nov 10, 2020 |
| Pegatron      | 1.03                        | Desktop     | [e660e12e3c](https://bsd-hardware.info/?probe=e660e12e3c) | Nov 10, 2020 |
| Gigabyte      | M61SME-S2L                  | Desktop     | [d8809eb5e7](https://bsd-hardware.info/?probe=d8809eb5e7) | Nov 09, 2020 |
| Gigabyte      | M61SME-S2L                  | Desktop     | [e5f658c70a](https://bsd-hardware.info/?probe=e5f658c70a) | Nov 09, 2020 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [c766aab801](https://bsd-hardware.info/?probe=c766aab801) | Nov 09, 2020 |
| Pegatron      | SKLD4-P1                    | Desktop     | [ea548b4c71](https://bsd-hardware.info/?probe=ea548b4c71) | Nov 08, 2020 |
| Toshiba       | Satellite M100              | Notebook    | [e6e0a1294c](https://bsd-hardware.info/?probe=e6e0a1294c) | Nov 01, 2020 |
| ASUSTek       | B75M-A                      | Desktop     | [43ece33e8c](https://bsd-hardware.info/?probe=43ece33e8c) | Oct 31, 2020 |
| ASRock        | J3455-ITX                   | Desktop     | [52fe99a6d6](https://bsd-hardware.info/?probe=52fe99a6d6) | Oct 29, 2020 |
| Gigabyte      | X58A-UD5                    | Desktop     | [6e642641e5](https://bsd-hardware.info/?probe=6e642641e5) | Oct 25, 2020 |
| Supermicro    | H8DGU                       | Server      | [58a580dd6b](https://bsd-hardware.info/?probe=58a580dd6b) | Oct 24, 2020 |
| Supermicro    | X10DRW-i                    | Server      | [3c7d64a2cb](https://bsd-hardware.info/?probe=3c7d64a2cb) | Oct 24, 2020 |
| Sony          | SVP1321V9RB                 | Notebook    | [3f414895be](https://bsd-hardware.info/?probe=3f414895be) | Oct 24, 2020 |
| Acer          | Aspire ES1-132              | Notebook    | [a4e45f3551](https://bsd-hardware.info/?probe=a4e45f3551) | Oct 22, 2020 |
| ASUSTek       | B150M-K                     | Desktop     | [135db0e455](https://bsd-hardware.info/?probe=135db0e455) | Oct 22, 2020 |
| Unknown       | Unknown                     | Desktop     | [223aa9e0a3](https://bsd-hardware.info/?probe=223aa9e0a3) | Oct 22, 2020 |
| Dell          | Latitude C400               | Notebook    | [1dcc5e7972](https://bsd-hardware.info/?probe=1dcc5e7972) | Oct 21, 2020 |
| Dell          | Latitude C400               | Notebook    | [8330d23bd7](https://bsd-hardware.info/?probe=8330d23bd7) | Oct 21, 2020 |
| ASUSTek       | Z170-A                      | Desktop     | [a1c6966373](https://bsd-hardware.info/?probe=a1c6966373) | Oct 21, 2020 |
| Google        | Chell                       | Notebook    | [4ffe68c199](https://bsd-hardware.info/?probe=4ffe68c199) | Oct 21, 2020 |
| ASUSTek       | Z170-K                      | Desktop     | [19cb3ccc34](https://bsd-hardware.info/?probe=19cb3ccc34) | Oct 20, 2020 |
| Lenovo        | ThinkPad X230 2325Y36       | Notebook    | [b2e65dd4c5](https://bsd-hardware.info/?probe=b2e65dd4c5) | Oct 20, 2020 |
| Intel         | S3000AH                     | Desktop     | [f5b858601a](https://bsd-hardware.info/?probe=f5b858601a) | Oct 20, 2020 |
| Unknown       | Unknown                     | Desktop     | [bedb4a4b37](https://bsd-hardware.info/?probe=bedb4a4b37) | Oct 20, 2020 |
| Lenovo        | ThinkPad X240 20AL00DKRT    | Notebook    | [623801416c](https://bsd-hardware.info/?probe=623801416c) | Oct 20, 2020 |
| ASUSTek       | P10S-I Series               | Desktop     | [1a0e9f0100](https://bsd-hardware.info/?probe=1a0e9f0100) | Oct 19, 2020 |
| Lenovo        | ThinkPad T495s 20QKS1812... | Notebook    | [a3bc7a0c88](https://bsd-hardware.info/?probe=a3bc7a0c88) | Oct 19, 2020 |
| IBM           | Board                       | Desktop     | [af2f64a7a8](https://bsd-hardware.info/?probe=af2f64a7a8) | Oct 19, 2020 |
| Foxconn       | AT-7000 Series              | Desktop     | [dc7b96e637](https://bsd-hardware.info/?probe=dc7b96e637) | Oct 19, 2020 |
| Foxconn       | AT-7000 Series              | Desktop     | [0184fcedcf](https://bsd-hardware.info/?probe=0184fcedcf) | Oct 19, 2020 |
| Unknown       | Unknown                     | Desktop     | [e36fc2b2b2](https://bsd-hardware.info/?probe=e36fc2b2b2) | Oct 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [4f54c8f399](https://bsd-hardware.info/?probe=4f54c8f399) | Oct 19, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [027fbd78f5](https://bsd-hardware.info/?probe=027fbd78f5) | Oct 19, 2020 |
| HP            | OmniBook PC                 | Notebook    | [0e0656d228](https://bsd-hardware.info/?probe=0e0656d228) | Oct 19, 2020 |
| HP            | OmniBook PC                 | Notebook    | [60e72f1c10](https://bsd-hardware.info/?probe=60e72f1c10) | Oct 19, 2020 |
| Acer          | Aspire A315-42              | Notebook    | [1ac21e1660](https://bsd-hardware.info/?probe=1ac21e1660) | Oct 08, 2020 |
| MSI           | B450M MORTAR MAX            | Desktop     | [1123cb92ba](https://bsd-hardware.info/?probe=1123cb92ba) | Oct 04, 2020 |
| ASUSTek       | H81M-D PLUS                 | Desktop     | [95b75130f4](https://bsd-hardware.info/?probe=95b75130f4) | Sep 26, 2020 |
| Gigabyte      | C246-WU4-CF                 | Desktop     | [4117a39b03](https://bsd-hardware.info/?probe=4117a39b03) | Sep 23, 2020 |
| Acer          | Revo RN86                   | Desktop     | [d1b1775be3](https://bsd-hardware.info/?probe=d1b1775be3) | Sep 23, 2020 |
| ASUSTek       | H81M-D PLUS                 | Desktop     | [e8ab84404c](https://bsd-hardware.info/?probe=e8ab84404c) | Sep 22, 2020 |
| Acer          | Revo RN86                   | Desktop     | [c6b2c64d14](https://bsd-hardware.info/?probe=c6b2c64d14) | Sep 20, 2020 |
| ASUSTek       | H81M-D PLUS                 | Desktop     | [7be45f1bec](https://bsd-hardware.info/?probe=7be45f1bec) | Sep 19, 2020 |
| ASUSTek       | H81M-D PLUS                 | Desktop     | [e9dd488fe0](https://bsd-hardware.info/?probe=e9dd488fe0) | Sep 13, 2020 |
| Lenovo        | ThinkPad X230 2325Y36       | Notebook    | [1f28f1c311](https://bsd-hardware.info/?probe=1f28f1c311) | Aug 30, 2020 |
| Lenovo        | ThinkPad X230 2325Y36       | Notebook    | [11a0bbb73f](https://bsd-hardware.info/?probe=11a0bbb73f) | Aug 30, 2020 |
| Dell          | Inspiron 15-3567            | Notebook    | [4d1897ed1f](https://bsd-hardware.info/?probe=4d1897ed1f) | Aug 29, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [0e99e72ec9](https://bsd-hardware.info/?probe=0e99e72ec9) | Aug 26, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [b9477154b9](https://bsd-hardware.info/?probe=b9477154b9) | Aug 26, 2020 |
| ASUSTek       | P5QD TURBO                  | Desktop     | [598e77539b](https://bsd-hardware.info/?probe=598e77539b) | Aug 21, 2020 |
| ASUSTek       | P5QD TURBO                  | Desktop     | [e210609359](https://bsd-hardware.info/?probe=e210609359) | Aug 21, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [19d1c3d086](https://bsd-hardware.info/?probe=19d1c3d086) | Aug 20, 2020 |
| Gigabyte      | X58A-UD5                    | Desktop     | [63a429ad0e](https://bsd-hardware.info/?probe=63a429ad0e) | Aug 16, 2020 |
| ASUSTek       | X71SL                       | Notebook    | [a2ee0c9edb](https://bsd-hardware.info/?probe=a2ee0c9edb) | Aug 15, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [bc97c1c0fa](https://bsd-hardware.info/?probe=bc97c1c0fa) | Aug 13, 2020 |
| Dell          | Inspiron 1501               | Notebook    | [9ee3e7cbc2](https://bsd-hardware.info/?probe=9ee3e7cbc2) | Aug 11, 2020 |
| Dell          | Inspiron 1501               | Notebook    | [807aae7095](https://bsd-hardware.info/?probe=807aae7095) | Aug 11, 2020 |
| ASUSTek       | P8P67                       | Desktop     | [c61cac017e](https://bsd-hardware.info/?probe=c61cac017e) | Aug 06, 2020 |
| ASUSTek       | K8N-VM                      | Desktop     | [0ddf168986](https://bsd-hardware.info/?probe=0ddf168986) | Aug 06, 2020 |
| Dell          | Inspiron 1525               | Notebook    | [d08ea3542e](https://bsd-hardware.info/?probe=d08ea3542e) | Aug 05, 2020 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [4f4cb01708](https://bsd-hardware.info/?probe=4f4cb01708) | Aug 05, 2020 |
| Dell          | Latitude 7490               | Notebook    | [b1d5e8c619](https://bsd-hardware.info/?probe=b1d5e8c619) | Aug 05, 2020 |
| HP            | ProBook 440 G6              | Notebook    | [0227811abb](https://bsd-hardware.info/?probe=0227811abb) | Aug 05, 2020 |
| MSI           | H61M-P20                    | Desktop     | [fefac5637b](https://bsd-hardware.info/?probe=fefac5637b) | Aug 03, 2020 |
| Lenovo        | ThinkPad T490s 20NX000DR... | Notebook    | [0919d8936f](https://bsd-hardware.info/?probe=0919d8936f) | Jul 27, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [15e87049a7](https://bsd-hardware.info/?probe=15e87049a7) | Jul 27, 2020 |
| ASRock        | E350M1                      | Desktop     | [08eec78cdf](https://bsd-hardware.info/?probe=08eec78cdf) | Jul 25, 2020 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [eb3f0a19ae](https://bsd-hardware.info/?probe=eb3f0a19ae) | Jul 25, 2020 |
| Pegatron      | 2A73                        | Desktop     | [05dea28605](https://bsd-hardware.info/?probe=05dea28605) | Jul 21, 2020 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [d06bcfe514](https://bsd-hardware.info/?probe=d06bcfe514) | Jul 19, 2020 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [35c4a3608e](https://bsd-hardware.info/?probe=35c4a3608e) | Jul 19, 2020 |
| Supermicro    | X10SRi-FB                   | Server      | [81db3f5be2](https://bsd-hardware.info/?probe=81db3f5be2) | Jul 15, 2020 |
| Supermicro    | NSM5200A                    | Desktop     | [49a39eb60f](https://bsd-hardware.info/?probe=49a39eb60f) | Jul 15, 2020 |
| Gigabyte      | GA-790FXTA-UD5              | Desktop     | [667d98ccb2](https://bsd-hardware.info/?probe=667d98ccb2) | Jul 15, 2020 |
| ASRock        | B450 Pro4                   | Desktop     | [836bf04a97](https://bsd-hardware.info/?probe=836bf04a97) | Jul 15, 2020 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [daaa05bbf4](https://bsd-hardware.info/?probe=daaa05bbf4) | Jul 15, 2020 |
| Gigabyte      | Z77-D3H                     | Desktop     | [97c6656398](https://bsd-hardware.info/?probe=97c6656398) | Jul 12, 2020 |
| HP            | ProBook 430 G2              | Notebook    | [3a33aa0d8c](https://bsd-hardware.info/?probe=3a33aa0d8c) | Jun 30, 2020 |
| HP            | ProBook 430 G2              | Notebook    | [365ebdaf9c](https://bsd-hardware.info/?probe=365ebdaf9c) | Jun 30, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [08dd1b91a8](https://bsd-hardware.info/?probe=08dd1b91a8) | Jun 30, 2020 |
| Foxconn       | nT-330i                     | Desktop     | [79ab8efb37](https://bsd-hardware.info/?probe=79ab8efb37) | Jun 29, 2020 |
| Intel         | NUC5PPYB                    | Mini pc     | [9fbca0a216](https://bsd-hardware.info/?probe=9fbca0a216) | Jun 17, 2020 |
| Intel         | NUC5PPYB                    | Mini pc     | [a24cfb5df9](https://bsd-hardware.info/?probe=a24cfb5df9) | Jun 16, 2020 |
| ASRock        | J3455-ITX                   | Desktop     | [1c8e18b787](https://bsd-hardware.info/?probe=1c8e18b787) | Jun 15, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [220313b249](https://bsd-hardware.info/?probe=220313b249) | Jun 03, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [7042848932](https://bsd-hardware.info/?probe=7042848932) | Jun 03, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [c7f3bf660a](https://bsd-hardware.info/?probe=c7f3bf660a) | Jun 02, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [b84d1b49d8](https://bsd-hardware.info/?probe=b84d1b49d8) | Jun 02, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [0cc3c53651](https://bsd-hardware.info/?probe=0cc3c53651) | Jun 02, 2020 |
| Supermicro    | X11SAE-M                    | Server      | [f6cf8f7870](https://bsd-hardware.info/?probe=f6cf8f7870) | Jun 02, 2020 |
| Dell          | Latitude E5400              | Notebook    | [54854343e4](https://bsd-hardware.info/?probe=54854343e4) | Jun 01, 2020 |
| Unknown       | Unknown                     | Desktop     | [ee9f9df2c1](https://bsd-hardware.info/?probe=ee9f9df2c1) | May 31, 2020 |
| Unknown       | Unknown                     | Desktop     | [6034ab8e6e](https://bsd-hardware.info/?probe=6034ab8e6e) | May 31, 2020 |
| ASRock        | Q1900M                      | Desktop     | [8787d15bc5](https://bsd-hardware.info/?probe=8787d15bc5) | May 31, 2020 |
| ASRock        | Q1900M                      | Desktop     | [79fe3017ef](https://bsd-hardware.info/?probe=79fe3017ef) | May 31, 2020 |
| Dell          | Latitude E6420              | Notebook    | [324265fe3f](https://bsd-hardware.info/?probe=324265fe3f) | May 31, 2020 |
| Supermicro    | X9DBL-3F/X9DBL-iF           | Server      | [1f4d1e4607](https://bsd-hardware.info/?probe=1f4d1e4607) | May 29, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [68840c222b](https://bsd-hardware.info/?probe=68840c222b) | May 28, 2020 |
| Lenovo        | ThinkPad X240 20AMA52RUK    | Notebook    | [c65cdb97de](https://bsd-hardware.info/?probe=c65cdb97de) | May 28, 2020 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [08534174df](https://bsd-hardware.info/?probe=08534174df) | May 27, 2020 |
| Unknown       | TI AM335x BeagleBone Bla... | Desktop     | [8e0f831fd8](https://bsd-hardware.info/?probe=8e0f831fd8) | May 27, 2020 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [03ea0992c4](https://bsd-hardware.info/?probe=03ea0992c4) | May 27, 2020 |
| IBM           | Board                       | Desktop     | [1bcc2b8e0b](https://bsd-hardware.info/?probe=1bcc2b8e0b) | May 27, 2020 |
| Unknown       | TI AM335x BeagleBone Bla... | Desktop     | [74b9526162](https://bsd-hardware.info/?probe=74b9526162) | May 27, 2020 |
| Acer          | Aspire 4820T                | Notebook    | [239eea83c6](https://bsd-hardware.info/?probe=239eea83c6) | May 26, 2020 |
| Gigabyte      | B450M GAMING                | Desktop     | [b4c4c676c4](https://bsd-hardware.info/?probe=b4c4c676c4) | May 26, 2020 |
| Unknown       | YL-J3060L2                  | Desktop     | [55be2fab24](https://bsd-hardware.info/?probe=55be2fab24) | May 26, 2020 |
| Gigabyte      | GA-MA78GM-UD2H              | Desktop     | [66bce86f33](https://bsd-hardware.info/?probe=66bce86f33) | May 26, 2020 |
| ASUSTek       | GL553VE                     | Notebook    | [dc7bb56859](https://bsd-hardware.info/?probe=dc7bb56859) | May 26, 2020 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [9728d93191](https://bsd-hardware.info/?probe=9728d93191) | May 25, 2020 |
| Acer          | WMCP78M                     | Desktop     | [db1e7a52b9](https://bsd-hardware.info/?probe=db1e7a52b9) | May 25, 2020 |
| Acer          | WMCP78M                     | Desktop     | [d9b08cfc0c](https://bsd-hardware.info/?probe=d9b08cfc0c) | May 25, 2020 |
| ASUSTek       | P5Q SE PLUS                 | Desktop     | [84e9e67aa2](https://bsd-hardware.info/?probe=84e9e67aa2) | May 25, 2020 |
| IBM           | ThinkPad X41 2525FAG        | Notebook    | [1e849f86cf](https://bsd-hardware.info/?probe=1e849f86cf) | May 25, 2020 |
| ASUSTek       | P4P800-VM                   | Desktop     | [8b9481baf2](https://bsd-hardware.info/?probe=8b9481baf2) | May 25, 2020 |
| ASUSTek       | P4P800-VM                   | Desktop     | [33c4579f99](https://bsd-hardware.info/?probe=33c4579f99) | May 25, 2020 |
| MSI           | MS-7255                     | Desktop     | [3984f45545](https://bsd-hardware.info/?probe=3984f45545) | May 25, 2020 |
| HP            | ProLiant DL365 G5           | Server      | [4ebc960e9c](https://bsd-hardware.info/?probe=4ebc960e9c) | May 25, 2020 |
| Gigabyte      | 945GM-S2                    | Desktop     | [59e3624de7](https://bsd-hardware.info/?probe=59e3624de7) | May 25, 2020 |
| Gigabyte      | F2A75M-HD2                  | Desktop     | [09bfdeafbd](https://bsd-hardware.info/?probe=09bfdeafbd) | May 25, 2020 |
| ASRock        | J4205-ITX                   | Desktop     | [bb67f0e80b](https://bsd-hardware.info/?probe=bb67f0e80b) | May 25, 2020 |
| ASUSTek       | Z87-EXPERT                  | Desktop     | [9f0ad7bbcf](https://bsd-hardware.info/?probe=9f0ad7bbcf) | May 25, 2020 |
| Intel         | S3420GP E51976-406          | Server      | [6b7fba08dd](https://bsd-hardware.info/?probe=6b7fba08dd) | May 25, 2020 |
| Supermicro    | X11DPH-T                    | Desktop     | [1db4784753](https://bsd-hardware.info/?probe=1db4784753) | May 25, 2020 |
| Supermicro    | X11DPH-T                    | Desktop     | [79aea35f1f](https://bsd-hardware.info/?probe=79aea35f1f) | May 25, 2020 |
| ASUSTek       | P5M2                        | Desktop     | [c1f04b3a84](https://bsd-hardware.info/?probe=c1f04b3a84) | May 25, 2020 |
| ASUSTek       | P6T SE                      | Desktop     | [66bbed8d59](https://bsd-hardware.info/?probe=66bbed8d59) | May 25, 2020 |
| ASUSTek       | P6T SE                      | Desktop     | [6eb355eabd](https://bsd-hardware.info/?probe=6eb355eabd) | May 25, 2020 |
| Intel         | S5000PSL                    | Server      | [9a893e2cc9](https://bsd-hardware.info/?probe=9a893e2cc9) | May 25, 2020 |
| Gigabyte      | EX58-UD4                    | Desktop     | [e7f015c6da](https://bsd-hardware.info/?probe=e7f015c6da) | May 25, 2020 |
| ASUSTek       | P5Q                         | Desktop     | [97732c8106](https://bsd-hardware.info/?probe=97732c8106) | May 25, 2020 |
| ASUSTek       | P5GD2-Deluxe                | Desktop     | [5b1dc84da5](https://bsd-hardware.info/?probe=5b1dc84da5) | May 25, 2020 |
| Acer          | WMCP78M                     | Desktop     | [55755e9ab9](https://bsd-hardware.info/?probe=55755e9ab9) | May 25, 2020 |
| ASUSTek       | P5K-E                       | Desktop     | [a1b81962ac](https://bsd-hardware.info/?probe=a1b81962ac) | May 25, 2020 |
| ASUSTek       | P5K-E                       | Desktop     | [8f72d18bff](https://bsd-hardware.info/?probe=8f72d18bff) | May 25, 2020 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [709a3db7de](https://bsd-hardware.info/?probe=709a3db7de) | May 25, 2020 |
| Gigabyte      | Z68P-DS3                    | Desktop     | [c06e03cda0](https://bsd-hardware.info/?probe=c06e03cda0) | May 25, 2020 |
| Intel         | DN2820FYK H24582-203        | Desktop     | [6cb240a9f6](https://bsd-hardware.info/?probe=6cb240a9f6) | May 25, 2020 |
| Intel         | NUC5PPYB                    | Mini pc     | [8ba62bd121](https://bsd-hardware.info/?probe=8ba62bd121) | May 25, 2020 |
| ASUSTek       | B75M-PLUS                   | Desktop     | [4620a00ccc](https://bsd-hardware.info/?probe=4620a00ccc) | May 25, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [0b7b4083bd](https://bsd-hardware.info/?probe=0b7b4083bd) | May 22, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [f7cb1aa38d](https://bsd-hardware.info/?probe=f7cb1aa38d) | May 21, 2020 |
| Dell          | Latitude E6530              | Notebook    | [04cd35a77b](https://bsd-hardware.info/?probe=04cd35a77b) | May 21, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [dc3c3cff26](https://bsd-hardware.info/?probe=dc3c3cff26) | May 21, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [807f3398e3](https://bsd-hardware.info/?probe=807f3398e3) | May 20, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [8212868b9f](https://bsd-hardware.info/?probe=8212868b9f) | May 19, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [ab53dfc003](https://bsd-hardware.info/?probe=ab53dfc003) | May 19, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [d3f180e9ef](https://bsd-hardware.info/?probe=d3f180e9ef) | May 17, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [bdd93164cf](https://bsd-hardware.info/?probe=bdd93164cf) | May 17, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [6a1b7867f0](https://bsd-hardware.info/?probe=6a1b7867f0) | May 16, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [112b83a485](https://bsd-hardware.info/?probe=112b83a485) | May 16, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [3258f01592](https://bsd-hardware.info/?probe=3258f01592) | May 16, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [4a419328b8](https://bsd-hardware.info/?probe=4a419328b8) | May 16, 2020 |
| ASUSTek       | A3L                         | Notebook    | [6b65fcf9c1](https://bsd-hardware.info/?probe=6b65fcf9c1) | May 15, 2020 |
| ASUSTek       | A3L                         | Notebook    | [0d292bca2f](https://bsd-hardware.info/?probe=0d292bca2f) | May 15, 2020 |
| ASUSTek       | X71SL                       | Notebook    | [2fd46cb7c7](https://bsd-hardware.info/?probe=2fd46cb7c7) | May 15, 2020 |
| ASUSTek       | X71SL                       | Notebook    | [8a027d0a73](https://bsd-hardware.info/?probe=8a027d0a73) | May 14, 2020 |
| Dell          | Latitude E6530              | Notebook    | [2c5eec6613](https://bsd-hardware.info/?probe=2c5eec6613) | May 09, 2020 |
| Dell          | Latitude E6530              | Notebook    | [1542f8e5a8](https://bsd-hardware.info/?probe=1542f8e5a8) | May 09, 2020 |
| ASUSTek       | X71SL                       | Notebook    | [adf290251e](https://bsd-hardware.info/?probe=adf290251e) | May 09, 2020 |
| ASUSTek       | X71SL                       | Notebook    | [7b4d0958ec](https://bsd-hardware.info/?probe=7b4d0958ec) | May 09, 2020 |
| Sony          | SVE1713S1RW                 | Notebook    | [9a751ddfd8](https://bsd-hardware.info/?probe=9a751ddfd8) | May 08, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [25fd1154c0](https://bsd-hardware.info/?probe=25fd1154c0) | May 08, 2020 |
| ASUSTek       | X71SL                       | Notebook    | [ab5297a63d](https://bsd-hardware.info/?probe=ab5297a63d) | May 07, 2020 |
| ASUSTek       | X71SL                       | Notebook    | [b8e364a2c0](https://bsd-hardware.info/?probe=b8e364a2c0) | May 07, 2020 |
| ASUSTek       | X71SL                       | Notebook    | [2aac4c3564](https://bsd-hardware.info/?probe=2aac4c3564) | May 07, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [4909d93faf](https://bsd-hardware.info/?probe=4909d93faf) | May 06, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [fb9c475d48](https://bsd-hardware.info/?probe=fb9c475d48) | May 06, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [2efd2c4c7a](https://bsd-hardware.info/?probe=2efd2c4c7a) | May 06, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [f1c2bcae9d](https://bsd-hardware.info/?probe=f1c2bcae9d) | May 06, 2020 |
| ASUSTek       | A3L                         | Notebook    | [0c73038abc](https://bsd-hardware.info/?probe=0c73038abc) | May 06, 2020 |
| ASUSTek       | A3L                         | Notebook    | [ff5b6e3024](https://bsd-hardware.info/?probe=ff5b6e3024) | May 06, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [eff0d8a3db](https://bsd-hardware.info/?probe=eff0d8a3db) | May 06, 2020 |
| ASUSTek       | X71SL                       | Notebook    | [b48cb0f2ce](https://bsd-hardware.info/?probe=b48cb0f2ce) | May 05, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [cd45078232](https://bsd-hardware.info/?probe=cd45078232) | May 05, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [0370bc0522](https://bsd-hardware.info/?probe=0370bc0522) | May 02, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Russia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| helloSystem 0.7.0    | 42        | 7.49%   |
| OpenBSD 6.8          | 30        | 5.35%   |
| FreeBSD 13.1         | 23        | 4.1%    |
| FreeBSD 13.0         | 23        | 4.1%    |
| helloSystem 0.8.0    | 22        | 3.92%   |
| FreeBSD 12.1-p5      | 20        | 3.57%   |
| OpenBSD 7.1          | 17        | 3.03%   |
| FreeBSD 14.0-CURRENT | 17        | 3.03%   |
| FreeBSD 13.0-STABLE  | 12        | 2.14%   |
| FreeBSD 12.1-STABLE  | 12        | 2.14%   |
| helloSystem 0.6.0    | 11        | 1.96%   |
| OpenBSD 6.7          | 10        | 1.78%   |
| OpenBSD 7.0          | 9         | 1.6%    |
| NomadBSD 1.3.2       | 9         | 1.6%    |
| helloSystem 0.5.0    | 9         | 1.6%    |
| FreeBSD 13.0-CURRENT | 9         | 1.6%    |
| GhostBSD 20.04.02    | 8         | 1.43%   |
| FreeBSD 13.1-p5      | 8         | 1.43%   |
| FreeBSD 12.2-p4      | 8         | 1.43%   |
| FreeBSD 12.1-p7      | 8         | 1.43%   |
| OpenBSD 7.2          | 7         | 1.25%   |
| OpenBSD 6.9          | 7         | 1.25%   |
| FreeBSD 12.2         | 7         | 1.25%   |
| NomadBSD 5806f915    | 6         | 1.07%   |
| helloSystem 0.4.0    | 6         | 1.07%   |
| FreeBSD 12.2-p3      | 6         | 1.07%   |
| FreeBSD 12.2-p2      | 6         | 1.07%   |
| OPNsense 22.7.11     | 5         | 0.89%   |
| OPNsense 21.1.1      | 5         | 0.89%   |
| FreeBSD 13.1-p2      | 5         | 0.89%   |
| FreeBSD 12.3-STABLE  | 5         | 0.89%   |
| FreeBSD 12.1-p8      | 5         | 0.89%   |
| OPNsense 22.7.6      | 4         | 0.71%   |
| OPNsense 22.1.6      | 4         | 0.71%   |
| OPNsense 22.1.10     | 4         | 0.71%   |
| OPNsense 21.1.5      | 4         | 0.71%   |
| OPNsense 21.1        | 4         | 0.71%   |
| FreeBSD 13.1-p1      | 4         | 0.71%   |
| FreeBSD 13.0-p4      | 4         | 0.71%   |
| FreeBSD 12.3-p5      | 4         | 0.71%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| FreeBSD     | 220       | 44.81%  |
| helloSystem | 92        | 18.74%  |
| OpenBSD     | 64        | 13.03%  |
| OPNsense    | 62        | 12.63%  |
| NomadBSD    | 16        | 3.26%   |
| NetBSD      | 11        | 2.24%   |
| GhostBSD    | 9         | 1.83%   |
| MyBee       | 7         | 1.43%   |
| XigmaNAS    | 1         | 0.2%    |
| TrueNAS     | 1         | 0.2%    |
| Ting        | 1         | 0.2%    |
| pfSense     | 1         | 0.2%    |
| PC-BSD      | 1         | 0.2%    |
| OS108       | 1         | 0.2%    |
| LibertyBSD  | 1         | 0.2%    |
| FuryBSD     | 1         | 0.2%    |
| DragonFly   | 1         | 0.2%    |
| ClonOS      | 1         | 0.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| amd64  | 423       | 90%     |
| i386   | 26        | 5.53%   |
| arm64  | 15        | 3.19%   |
| arm    | 3         | 0.64%   |
| macppc | 1         | 0.21%   |
| evbarm | 1         | 0.21%   |
| armv7  | 1         | 0.21%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 181       | 36.94%  |
| helloDesktop  | 109       | 22.24%  |
| KDE5          | 36        | 7.35%   |
| XFCE          | 35        | 7.14%   |
| fvwm          | 33        | 6.73%   |
| Openbox       | 26        | 5.31%   |
| MATE          | 18        | 3.67%   |
| TWM           | 15        | 3.06%   |
| GNOME         | 12        | 2.45%   |
| Fluxbox       | 5         | 1.02%   |
| IceWM         | 3         | 0.61%   |
| i3            | 3         | 0.61%   |
| LXQt          | 2         | 0.41%   |
| LXDE          | 2         | 0.41%   |
| Lumina        | 2         | 0.41%   |
| AwesomeWM     | 2         | 0.41%   |
| StumpWM       | 1         | 0.2%    |
| plasma        | 1         | 0.2%    |
| KWin          | 1         | 0.2%    |
| Enlightenment | 1         | 0.2%    |
| DWM           | 1         | 0.2%    |
| akonadi_newm  | 1         | 0.2%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 281       | 58.79%  |
| Console | 195       | 40.79%  |
| Wayland | 2         | 0.42%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 282       | 58.75%  |
| SLiM    | 132       | 27.5%   |
| SDDM    | 33        | 6.88%   |
| LightDM | 15        | 3.13%   |
| XDM     | 10        | 2.08%   |
| GDM     | 6         | 1.25%   |
| PCDM    | 1         | 0.21%   |
| Ly      | 1         | 0.21%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang           | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 153       | 31.1%   |
| ru_RU          | 130       | 26.42%  |
| en_US          | 121       | 24.59%  |
| C              | 69        | 14.02%  |
| ru             | 8         | 1.63%   |
| ru_RU.KOI8-R   | 4         | 0.81%   |
| en_GB          | 2         | 0.41%   |
| fr             | 1         | 0.2%    |
| en_EN          | 1         | 0.2%    |
| en             | 1         | 0.2%    |
| cv_RU.US-ASCII | 1         | 0.2%    |
| ba_RU          | 1         | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 306       | 63.35%  |
| BIOS | 177       | 36.65%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Zfs     | 205       | 42.36%  |
| Ufs     | 171       | 35.33%  |
| Ffs     | 65        | 13.43%  |
| Cd9660  | 41        | 8.47%   |
| Xfs     | 1         | 0.21%   |
| Hammer2 | 1         | 0.21%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 380       | 80.17%  |
| MBR     | 89        | 18.78%  |
| Unknown | 4         | 0.84%   |
| BSD     | 1         | 0.21%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 87        | 18.51%  |
| Gigabyte Technology | 51        | 10.85%  |
| Lenovo              | 45        | 9.57%   |
| Hewlett-Packard     | 34        | 7.23%   |
| ASRock              | 32        | 6.81%   |
| Unknown             | 32        | 6.81%   |
| Dell                | 25        | 5.32%   |
| Acer                | 21        | 4.47%   |
| MSI                 | 20        | 4.26%   |
| Intel               | 19        | 4.04%   |
| Supermicro          | 18        | 3.83%   |
| Sony                | 7         | 1.49%   |
| Pegatron            | 7         | 1.49%   |
| Samsung Electronics | 6         | 1.28%   |
| Apple               | 5         | 1.06%   |
| Timi                | 3         | 0.64%   |
| Techvision          | 3         | 0.64%   |
| PC Engines          | 3         | 0.64%   |
| IBM                 | 3         | 0.64%   |
| HUAWEI              | 3         | 0.64%   |
| Huanan              | 3         | 0.64%   |
| Firefly             | 3         | 0.64%   |
| Toshiba             | 2         | 0.43%   |
| Kraftway            | 2         | 0.43%   |
| Fujitsu             | 2         | 0.43%   |
| Foxconn             | 2         | 0.43%   |
| F-Plus Mobile       | 2         | 0.43%   |
| ZOTAC               | 1         | 0.21%   |
| YANYU               | 1         | 0.21%   |
| Wistron             | 1         | 0.21%   |
| Sophos              | 1         | 0.21%   |
| Shuttle             | 1         | 0.21%   |
| Radxa               | 1         | 0.21%   |
| QIYIDA              | 1         | 0.21%   |
| Panasonic           | 1         | 0.21%   |
| Packard Bell        | 1         | 0.21%   |
| NITRINOnet          | 1         | 0.21%   |
| MW                  | 1         | 0.21%   |
| Maxtang             | 1         | 0.21%   |
| MACHINIST           | 1         | 0.21%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                                                  | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Unknown                                                               | 33        | 7.02%   |
| ASUS All Series                                                       | 10        | 2.13%   |
| Techvision TVI7309X                                                   | 3         | 0.64%   |
| PC Engines APU2                                                       | 3         | 0.64%   |
| HP ProLiant DL360e Gen8                                               | 3         | 0.64%   |
| Supermicro Super Server                                               | 2         | 0.43%   |
| Supermicro SSG-6029P-E1CR12L                                          | 2         | 0.43%   |
| Supermicro H8DGU                                                      | 2         | 0.43%   |
| Samsung N145P/N250P/N260P                                             | 2         | 0.43%   |
| Pegatron SAISHIAT2                                                    | 2         | 0.43%   |
| MSI PS63 Modern 8M                                                    | 2         | 0.43%   |
| MSI MS-7B89                                                           | 2         | 0.43%   |
| MSI MS-7817                                                           | 2         | 0.43%   |
| Lenovo IdeaPad 330-15ARR 81D2                                         | 2         | 0.43%   |
| Intel X79 V2.72A                                                      | 2         | 0.43%   |
| Intel S3420GP                                                         | 2         | 0.43%   |
| HUAWEI CREM-WXX9                                                      | 2         | 0.43%   |
| Huanan X79 INTEL (INTEL Xeon E5/Corei7 DMI2 - C600/C200 Cipset V2.49P | 2         | 0.43%   |
| HP ProLiant MicroServer                                               | 2         | 0.43%   |
| HP Compaq Pro 6300 SFF                                                | 2         | 0.43%   |
| Gigabyte Z68XP-UD3                                                    | 2         | 0.43%   |
| Gigabyte M68MT-S2P                                                    | 2         | 0.43%   |
| Gigabyte H61M-DS2                                                     | 2         | 0.43%   |
| Gigabyte H310M S2 2.0                                                 | 2         | 0.43%   |
| Gigabyte GA-IMB370TN                                                  | 2         | 0.43%   |
| Gigabyte C1037UN-EU                                                   | 2         | 0.43%   |
| Gigabyte B450 AORUS M                                                 | 2         | 0.43%   |
| Gigabyte A320M-H                                                      | 2         | 0.43%   |
| Firefly ROC-RK3566-PC                                                 | 2         | 0.43%   |
| F-Plus Mobile FLAPTOP r                                               | 2         | 0.43%   |
| Dell OptiPlex 7040                                                    | 2         | 0.43%   |
| Dell Inspiron 15 7000 Gaming                                          | 2         | 0.43%   |
| ASUS PRIME Z590-P                                                     | 2         | 0.43%   |
| ASUS PRIME X370-PRO                                                   | 2         | 0.43%   |
| ASUS PRIME B550-PLUS                                                  | 2         | 0.43%   |
| ASUS P8Z77-V LX                                                       | 2         | 0.43%   |
| ASUS P6T SE                                                           | 2         | 0.43%   |
| ASUS P4P800-VM                                                        | 2         | 0.43%   |
| ASRock J4205-ITX                                                      | 2         | 0.43%   |
| Acer Aspire 4820T                                                     | 2         | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Unknown                      | 33        | 7.02%   |
| Lenovo ThinkPad              | 23        | 4.89%   |
| Acer Aspire                  | 16        | 3.4%    |
| HP ProLiant                  | 11        | 2.34%   |
| ASUS PRIME                   | 10        | 2.13%   |
| ASUS All                     | 10        | 2.13%   |
| Lenovo IdeaPad               | 9         | 1.91%   |
| Dell Inspiron                | 8         | 1.7%    |
| Dell Latitude                | 7         | 1.49%   |
| Lenovo ThinkCentre           | 6         | 1.28%   |
| HP ProBook                   | 6         | 1.28%   |
| HP Compaq                    | 5         | 1.06%   |
| Dell OptiPlex                | 5         | 1.06%   |
| Techvision TVI7309X          | 3         | 0.64%   |
| PC Engines APU2              | 3         | 0.64%   |
| HP Laptop                    | 3         | 0.64%   |
| ASUS VivoBook                | 3         | 0.64%   |
| ASUS ROG                     | 3         | 0.64%   |
| ASUS P5Q                     | 3         | 0.64%   |
| ASRock X570                  | 3         | 0.64%   |
| Toshiba Satellite            | 2         | 0.43%   |
| Supermicro Super             | 2         | 0.43%   |
| Supermicro SSG-6029P-E1CR12L | 2         | 0.43%   |
| Supermicro H8DGU             | 2         | 0.43%   |
| Samsung N145P                | 2         | 0.43%   |
| Pegatron SAISHIAT2           | 2         | 0.43%   |
| MSI PS63                     | 2         | 0.43%   |
| MSI MS-7B89                  | 2         | 0.43%   |
| MSI MS-7817                  | 2         | 0.43%   |
| Intel X79                    | 2         | 0.43%   |
| Intel S3420GP                | 2         | 0.43%   |
| Intel NUC5PPYB               | 2         | 0.43%   |
| IBM ThinkPad                 | 2         | 0.43%   |
| HUAWEI CREM-WXX9             | 2         | 0.43%   |
| Huanan X79                   | 2         | 0.43%   |
| Gigabyte Z68XP-UD3           | 2         | 0.43%   |
| Gigabyte M68MT-S2P           | 2         | 0.43%   |
| Gigabyte H61M-DS2            | 2         | 0.43%   |
| Gigabyte H310M               | 2         | 0.43%   |
| Gigabyte GA-IMB370TN         | 2         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 51        | 10.85%  |
| 2018    | 46        | 9.79%   |
| 2021    | 37        | 7.87%   |
| 2020    | 37        | 7.87%   |
| 2011    | 34        | 7.23%   |
| 2012    | 27        | 5.74%   |
| 2013    | 26        | 5.53%   |
| 2010    | 25        | 5.32%   |
| 2014    | 23        | 4.89%   |
| 2022    | 22        | 4.68%   |
| 2009    | 22        | 4.68%   |
| 2017    | 21        | 4.47%   |
| 2008    | 20        | 4.26%   |
| Unknown | 18        | 3.83%   |
| 2015    | 17        | 3.62%   |
| 2016    | 14        | 2.98%   |
| 2007    | 12        | 2.55%   |
| 2005    | 7         | 1.49%   |
| 2006    | 6         | 1.28%   |
| 2004    | 4         | 0.85%   |
| 2003    | 1         | 0.21%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 291       | 61.91%  |
| Notebook       | 134       | 28.51%  |
| Server         | 25        | 5.32%   |
| Mini pc        | 8         | 1.7%    |
| System on chip | 5         | 1.06%   |
| All in one     | 5         | 1.06%   |
| Firewall       | 1         | 0.21%   |
| Convertible    | 1         | 0.21%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 466       | 99.15%  |
| Yes  | 4         | 0.85%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 112       | 23.58%  |
| 4.01-8.0        | 110       | 23.16%  |
| 16.01-24.0      | 100       | 21.05%  |
| 32.01-64.0      | 41        | 8.63%   |
| 2.01-3.0        | 35        | 7.37%   |
| 3.01-4.0        | 18        | 3.79%   |
| 64.01-256.0     | 17        | 3.58%   |
| 0.51-1.0        | 17        | 3.58%   |
| 24.01-32.0      | 8         | 1.68%   |
| 1.01-2.0        | 8         | 1.68%   |
| 0.01-0.5        | 6         | 1.26%   |
| More than 256.0 | 3         | 0.63%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 237       | 48.37%  |
| 0.51-1.0   | 118       | 24.08%  |
| 1.01-2.0   | 53        | 10.82%  |
| 2.01-3.0   | 14        | 2.86%   |
| Unknown    | 13        | 2.65%   |
| 4.01-8.0   | 12        | 2.45%   |
| 3.01-4.0   | 11        | 2.24%   |
| 0          | 11        | 2.24%   |
| 8.01-16.0  | 10        | 2.04%   |
| 24.01-32.0 | 5         | 1.02%   |
| 16.01-24.0 | 5         | 1.02%   |
| 32.01-64.0 | 1         | 0.2%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 243       | 49.29%  |
| 2      | 108       | 21.91%  |
| 3      | 41        | 8.32%   |
| 0      | 37        | 7.51%   |
| 4      | 32        | 6.49%   |
| 5      | 13        | 2.64%   |
| 6      | 7         | 1.42%   |
| 7      | 5         | 1.01%   |
| 10     | 2         | 0.41%   |
| 19     | 1         | 0.2%    |
| 14     | 1         | 0.2%    |
| 11     | 1         | 0.2%    |
| 9      | 1         | 0.2%    |
| 8      | 1         | 0.2%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 392       | 82.53%  |
| Yes       | 83        | 17.47%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 420       | 89.36%  |
| No        | 50        | 10.64%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 267       | 56.69%  |
| Yes       | 204       | 43.31%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 334       | 70.91%  |
| Yes       | 137       | 29.09%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Russia  | 470       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 156       | 32.1%   |
| St Petersburg     | 48        | 9.88%   |
| Yekaterinburg     | 18        | 3.7%    |
| Krasnodar         | 17        | 3.5%    |
| Vladivostok       | 13        | 2.67%   |
| Novosibirsk       | 13        | 2.67%   |
| Chelyabinsk       | 12        | 2.47%   |
| Ozersk            | 10        | 2.06%   |
| Krasnoyarsk       | 10        | 2.06%   |
| Barnaul           | 7         | 1.44%   |
| Ufa               | 6         | 1.23%   |
| Surgut            | 6         | 1.23%   |
| Perm              | 6         | 1.23%   |
| Voronezh          | 5         | 1.03%   |
| Ulyanovsk         | 5         | 1.03%   |
| Kamensk-Ural'skiy | 5         | 1.03%   |
| Saratov           | 4         | 0.82%   |
| Rostov-on-Don     | 4         | 0.82%   |
| Omsk              | 4         | 0.82%   |
| Nizhniy Novgorod  | 4         | 0.82%   |
| Armavir           | 4         | 0.82%   |
| Volgograd         | 3         | 0.62%   |
| Vidnoye           | 3         | 0.62%   |
| Tyumen            | 3         | 0.62%   |
| Podolsk           | 3         | 0.62%   |
| Orenburg          | 3         | 0.62%   |
| Obninsk           | 3         | 0.62%   |
| Lipetsk           | 3         | 0.62%   |
| Kirov             | 3         | 0.62%   |
| Khimki            | 3         | 0.62%   |
| Izhevsk           | 3         | 0.62%   |
| Irkutsk           | 3         | 0.62%   |
| Zhukovskiy        | 2         | 0.41%   |
| Volzhskiy         | 2         | 0.41%   |
| Vladimir          | 2         | 0.41%   |
| Tsarskoye Selo    | 2         | 0.41%   |
| Tolyatti          | 2         | 0.41%   |
| Tambov            | 2         | 0.41%   |
| Stavropol         | 2         | 0.41%   |
| Reutov            | 2         | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 128       | 220    | 19.75%  |
| Seagate             | 109       | 235    | 16.82%  |
| Samsung Electronics | 67        | 99     | 10.34%  |
| Toshiba             | 42        | 74     | 6.48%   |
| Kingston            | 36        | 44     | 5.56%   |
| Hitachi             | 30        | 66     | 4.63%   |
| Intel               | 27        | 44     | 4.17%   |
| SanDisk             | 16        | 19     | 2.47%   |
| HGST                | 13        | 28     | 2.01%   |
| Crucial             | 13        | 19     | 2.01%   |
| A-DATA Technology   | 12        | 17     | 1.85%   |
| SPCC                | 10        | 12     | 1.54%   |
| SK hynix            | 9         | 10     | 1.39%   |
| Hewlett-Packard     | 8         | 17     | 1.23%   |
| Smartbuy            | 7         | 7      | 1.08%   |
| OCZ                 | 7         | 8      | 1.08%   |
| Micron Technology   | 7         | 10     | 1.08%   |
| Transcend           | 6         | 6      | 0.93%   |
| Silicon Motion      | 6         | 8      | 0.93%   |
| Plextor             | 6         | 9      | 0.93%   |
| AMD                 | 6         | 7      | 0.93%   |
| Patriot             | 5         | 5      | 0.77%   |
| OPENBSD             | 5         | 11     | 0.77%   |
| NVMe                | 5         | 9      | 0.77%   |
| Maxtor              | 5         | 5      | 0.77%   |
| KingSpec            | 4         | 6      | 0.62%   |
| Gigabyte Technology | 4         | 7      | 0.62%   |
| FORESEE             | 4         | 5      | 0.62%   |
| Apacer              | 4         | 4      | 0.62%   |
| Kston               | 3         | 3      | 0.46%   |
| KIOXIA              | 3         | 3      | 0.46%   |
| Innostor            | 3         | 3      | 0.46%   |
| China               | 3         | 3      | 0.46%   |
| XrayDisk            | 2         | 2      | 0.31%   |
| XPG                 | 2         | 2      | 0.31%   |
| Verbatim            | 2         | 2      | 0.31%   |
| Netac               | 2         | 2      | 0.31%   |
| Hoodisk             | 2         | 4      | 0.31%   |
| Goodram             | 2         | 2      | 0.31%   |
| Fujitsu             | 2         | 3      | 0.31%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| WDC WDS240G2G0A-00JH30 240GB        | 7         | 0.94%   |
| Toshiba DT01ACA100 1TB              | 7         | 0.94%   |
| Kingston SA400S37240G 240GB         | 7         | 0.94%   |
| WDC WD20EARX-00PASB0 2TB            | 6         | 0.8%    |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 6         | 0.8%    |
| Seagate ST1000DM010-2EP102 1TB      | 5         | 0.67%   |
| Samsung SSD 970 EVO Plus 250GB      | 5         | 0.67%   |
| OPENBSD SR RAID 1 1TB               | 5         | 0.67%   |
| Kingston SA400S37120G 120GB         | 5         | 0.67%   |
| HP RAID 1(1+0) 128GB                | 5         | 0.67%   |
| WDC WDS120G2G0A-00JH30 120GB        | 4         | 0.54%   |
| WDC WD1002FAEX-00Y9A0 1TB           | 4         | 0.54%   |
| Seagate ST3300657SS 304GB           | 4         | 0.54%   |
| Seagate ST250DM000-1BD141 250GB     | 4         | 0.54%   |
| Seagate ST1000LM049-2GH172 1TB      | 4         | 0.54%   |
| Seagate ST1000LM035-1RK172 1TB      | 4         | 0.54%   |
| Samsung SSD 860 EVO 500GB           | 4         | 0.54%   |
| Kingston SV300S37A120G 120GB        | 4         | 0.54%   |
| A-DATA SU650 120GB                  | 4         | 0.54%   |
| WDC WD6400AARS-00Y5B1 640GB         | 3         | 0.4%    |
| WDC WD5000LPLX-00ZNTT0 500GB        | 3         | 0.4%    |
| WDC WD10JFCX-68N6GN0 1TB            | 3         | 0.4%    |
| Toshiba MQ01ABF050 500GB            | 3         | 0.4%    |
| Toshiba MQ01ABD100 1TB              | 3         | 0.4%    |
| Toshiba DT01ACA050 500GB            | 3         | 0.4%    |
| SPCC Solid State Disk 128GB         | 3         | 0.4%    |
| Silicon Motion NE-256 256GB         | 3         | 0.4%    |
| Seagate ST9500325AS 500GB           | 3         | 0.4%    |
| Seagate ST500LM021-1KJ152 500GB     | 3         | 0.4%    |
| Seagate ST500LM012 HN-M500MBB 500GB | 3         | 0.4%    |
| Seagate ST500DM002-1BD142 500GB     | 3         | 0.4%    |
| Seagate ST4000VN008-2DR166 4TB      | 3         | 0.4%    |
| Seagate ST380815AS 80GB             | 3         | 0.4%    |
| Seagate ST3500413AS 500GB           | 3         | 0.4%    |
| Seagate ST3250318AS 250GB           | 3         | 0.4%    |
| Seagate ST2000DM008-2FR102 2TB      | 3         | 0.4%    |
| Seagate ST2000DM001-1CH164 2TB      | 3         | 0.4%    |
| Samsung SSD 970 EVO Plus 500GB      | 3         | 0.4%    |
| Samsung SSD 860 EVO 250GB           | 3         | 0.4%    |
| Samsung HD161HJ 160GB               | 3         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                             | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate                            | 109       | 235    | 32.25%  |
| WDC                                | 102       | 184    | 30.18%  |
| Toshiba                            | 39        | 71     | 11.54%  |
| Hitachi                            | 30        | 66     | 8.88%   |
| Samsung Electronics                | 13        | 21     | 3.85%   |
| HGST                               | 13        | 28     | 3.85%   |
| Hewlett-Packard                    | 7         | 16     | 2.07%   |
| OPENBSD                            | 5         | 11     | 1.48%   |
| NVMe                               | 5         | 9      | 1.48%   |
| Maxtor                             | 5         | 5      | 1.48%   |
| Fujitsu                            | 2         | 3      | 0.59%   |
| Adaptec                            | 2         | 12     | 0.59%   |
| USB                                | 1         | 1      | 0.3%    |
| UFD 2.0                            | 1         | 1      | 0.3%    |
| Product:              USB DISK 2.0 | 1         | 1      | 0.3%    |
| MaxDigital                         | 1         | 1      | 0.3%    |
| IBM                                | 1         | 1      | 0.3%    |
| Areca                              | 1         | 2      | 0.3%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 36        | 44     | 15.19%  |
| Kingston            | 30        | 37     | 12.66%  |
| Intel               | 21        | 36     | 8.86%   |
| WDC                 | 18        | 19     | 7.59%   |
| SanDisk             | 16        | 19     | 6.75%   |
| Crucial             | 12        | 18     | 5.06%   |
| A-DATA Technology   | 10        | 14     | 4.22%   |
| SPCC                | 9         | 11     | 3.8%    |
| Smartbuy            | 7         | 7      | 2.95%   |
| OCZ                 | 7         | 8      | 2.95%   |
| Micron Technology   | 7         | 10     | 2.95%   |
| Plextor             | 6         | 9      | 2.53%   |
| Transcend           | 5         | 5      | 2.11%   |
| Patriot             | 5         | 5      | 2.11%   |
| AMD                 | 5         | 6      | 2.11%   |
| KingSpec            | 4         | 6      | 1.69%   |
| Apacer              | 4         | 4      | 1.69%   |
| Kston               | 3         | 3      | 1.27%   |
| Innostor            | 3         | 3      | 1.27%   |
| China               | 3         | 3      | 1.27%   |
| Verbatim            | 2         | 2      | 0.84%   |
| Toshiba             | 2         | 2      | 0.84%   |
| Netac               | 2         | 2      | 0.84%   |
| Hoodisk             | 2         | 4      | 0.84%   |
| Gigabyte Technology | 2         | 4      | 0.84%   |
| XUNZHE              | 1         | 1      | 0.42%   |
| XrayDisk            | 1         | 1      | 0.42%   |
| XPG                 | 1         | 1      | 0.42%   |
| SK hynix            | 1         | 1      | 0.42%   |
| SATADOM             | 1         | 1      | 0.42%   |
| Qumo                | 1         | 1      | 0.42%   |
| LITEON              | 1         | 1      | 0.42%   |
| KLLISRE             | 1         | 1      | 0.42%   |
| KingDian            | 1         | 3      | 0.42%   |
| Kingchuxing         | 1         | 1      | 0.42%   |
| Hewlett-Packard     | 1         | 1      | 0.42%   |
| Goodram             | 1         | 1      | 0.42%   |
| GK                  | 1         | 1      | 0.42%   |
| FORESEE             | 1         | 2      | 0.42%   |
| Apple               | 1         | 1      | 0.42%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 263       | 668    | 47.73%  |
| SSD  | 209       | 300    | 37.93%  |
| NVMe | 79        | 106    | 14.34%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 393       | 968    | 83.26%  |
| NVMe | 79        | 106    | 16.74%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 328       | 534    | 63.08%  |
| 0.51-1.0        | 114       | 198    | 21.92%  |
| 1.01-2.0        | 37        | 135    | 7.12%   |
| 3.01-4.0        | 16        | 37     | 3.08%   |
| 4.01-10.0       | 13        | 30     | 2.5%    |
| 2.01-3.0        | 8         | 21     | 1.54%   |
| 10.01-20.0      | 3         | 12     | 0.58%   |
| More than 100.0 | 1         | 1      | 0.19%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 145       | 28.94%  |
| 1-20           | 105       | 20.96%  |
| 251-500        | 90        | 17.96%  |
| 51-100         | 53        | 10.58%  |
| 21-50          | 37        | 7.39%   |
| 501-1000       | 36        | 7.19%   |
| 1001-2000      | 16        | 3.19%   |
| More than 3000 | 11        | 2.2%    |
| Unknown        | 6         | 1.2%    |
| 2001-3000      | 2         | 0.4%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 380       | 77.87%  |
| 21-50          | 44        | 9.02%   |
| 101-250        | 20        | 4.1%    |
| 51-100         | 18        | 3.69%   |
| 501-1000       | 7         | 1.43%   |
| Unknown        | 6         | 1.23%   |
| More than 3000 | 5         | 1.02%   |
| 2001-3000      | 3         | 0.61%   |
| 1001-2000      | 3         | 0.61%   |
| 251-500        | 2         | 0.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB        | 2         | 2      | 1.67%   |
| WDC WD5000LPLX-00ZNTT0 500GB        | 2         | 2      | 1.67%   |
| WDC WD1002FAEX-00Y9A0 1TB           | 2         | 2      | 1.67%   |
| Toshiba MQ01ABF050 500GB            | 2         | 2      | 1.67%   |
| Seagate ST9500325AS 500GB           | 2         | 2      | 1.67%   |
| Seagate ST500LT012-1DG142 500GB     | 2         | 2      | 1.67%   |
| Seagate ST3500413AS 500GB           | 2         | 4      | 1.67%   |
| Seagate ST3320418AS 320GB           | 2         | 2      | 1.67%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 2         | 2      | 1.67%   |
| Samsung Electronics SSD 870 EVO 1TB | 2         | 6      | 1.67%   |
| Samsung Electronics HD501LJ 500GB   | 2         | 4      | 1.67%   |
| Samsung Electronics HD161HJ 160GB   | 2         | 2      | 1.67%   |
| Micron Technology 1100 SATA 256GB   | 2         | 2      | 1.67%   |
| Maxtor STM3320613AS 320GB           | 2         | 2      | 1.67%   |
| Kingston SA400S37120G 120GB         | 2         | 2      | 1.67%   |
| Hitachi HDS721010CLA332 1TB         | 2         | 4      | 1.67%   |
| XPG SX950U 240GB                    | 1         | 1      | 0.83%   |
| WDC WDS120G2G0A-00JH30 120GB        | 1         | 1      | 0.83%   |
| WDC WD7501AALS-00E8B0 752GB         | 1         | 1      | 0.83%   |
| WDC WD7500AACS-00ZJB0 752GB         | 1         | 1      | 0.83%   |
| WDC WD60EFRX-68MYMN1 6TB            | 1         | 1      | 0.83%   |
| WDC WD5003AZEX-00MK2A0 500GB        | 1         | 1      | 0.83%   |
| WDC WD5000LPLX-60ZNTT1 500GB        | 1         | 1      | 0.83%   |
| WDC WD5000LPCX-60VHAT0 500GB        | 1         | 1      | 0.83%   |
| WDC WD5000AZRZ-00HTKB0 500GB        | 1         | 1      | 0.83%   |
| WDC WD5000AZLX-00CL5A0 500GB        | 1         | 1      | 0.83%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 1         | 1      | 0.83%   |
| WDC WD5000AAKS-00V1A0 500GB         | 1         | 1      | 0.83%   |
| WDC WD40EFRX-68N32N0 4TB            | 1         | 3      | 0.83%   |
| WDC WD4000FYYZ-01UL1B0 4TB          | 1         | 1      | 0.83%   |
| WDC WD3200BPVT-80ZEST0 320GB        | 1         | 1      | 0.83%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 1         | 1      | 0.83%   |
| WDC WD3200BEVT-00A0RT0 233GB        | 1         | 1      | 0.83%   |
| WDC WD3200AAKX-001CA0 320GB         | 1         | 1      | 0.83%   |
| WDC WD20EURX-63T0FY0 2TB            | 1         | 1      | 0.83%   |
| WDC WD20EFRX-68EUZN0 2TB            | 1         | 2      | 0.83%   |
| WDC WD2000JB-00GVC0 200GB           | 1         | 1      | 0.83%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 1         | 1      | 0.83%   |
| WDC WD15EARS-00Z5B1 1.5TB           | 1         | 1      | 0.83%   |
| WDC WD15EADS-00P8B0 1.5TB           | 1         | 1      | 0.83%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 29        | 40     | 25%     |
| WDC                 | 28        | 34     | 24.14%  |
| Hitachi             | 13        | 17     | 11.21%  |
| Samsung Electronics | 10        | 16     | 8.62%   |
| Toshiba             | 9         | 11     | 7.76%   |
| Kingston            | 6         | 6      | 5.17%   |
| Intel               | 6         | 6      | 5.17%   |
| Maxtor              | 4         | 4      | 3.45%   |
| Micron Technology   | 2         | 2      | 1.72%   |
| HGST                | 2         | 2      | 1.72%   |
| XPG                 | 1         | 1      | 0.86%   |
| SPCC                | 1         | 1      | 0.86%   |
| Plextor             | 1         | 1      | 0.86%   |
| GK                  | 1         | 1      | 0.86%   |
| Apple               | 1         | 1      | 0.86%   |
| AMD                 | 1         | 2      | 0.86%   |
| A-DATA Technology   | 1         | 1      | 0.86%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 29        | 40     | 32.58%  |
| WDC                 | 25        | 31     | 28.09%  |
| Hitachi             | 13        | 17     | 14.61%  |
| Toshiba             | 9         | 11     | 10.11%  |
| Samsung Electronics | 7         | 9      | 7.87%   |
| Maxtor              | 4         | 4      | 4.49%   |
| HGST                | 2         | 2      | 2.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 87        | 114    | 76.99%  |
| SSD  | 26        | 32     | 23.01%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| WDC WD6400AARS-00Y5B1 640GB          | 1         | 2      | 20%     |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB | 1         | 1      | 20%     |
| Toshiba MG05ACA800E 8TB              | 1         | 1      | 20%     |
| Hitachi HTS545025B9A300 250GB        | 1         | 1      | 20%     |
| Crucial M4-CT256M4SSD1 256GB         | 1         | 1      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 3      | 40%     |
| Toshiba | 1         | 1      | 20%     |
| Hitachi | 1         | 1      | 20%     |
| Crucial | 1         | 1      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 367       | 842    | 71.26%  |
| Malfunc  | 110       | 146    | 21.36%  |
| Detected | 33        | 80     | 6.41%   |
| Failed   | 5         | 6      | 0.97%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 325       | 55.94%  |
| AMD                              | 82        | 14.11%  |
| Samsung Electronics              | 26        | 4.48%   |
| Silicon Motion                   | 16        | 2.75%   |
| Marvell Technology Group         | 14        | 2.41%   |
| SanDisk                          | 12        | 2.07%   |
| Nvidia                           | 12        | 2.07%   |
| ASMedia Technology               | 12        | 2.07%   |
| JMicron Technology               | 11        | 1.89%   |
| Broadcom / LSI                   | 10        | 1.72%   |
| SK hynix                         | 9         | 1.55%   |
| Kingston Technology Company      | 6         | 1.03%   |
| Hewlett-Packard                  | 6         | 1.03%   |
| Areca Technology                 | 5         | 0.86%   |
| Phison Electronics               | 4         | 0.69%   |
| Toshiba                          | 3         | 0.52%   |
| Realtek Semiconductor            | 3         | 0.52%   |
| KIOXIA                           | 3         | 0.52%   |
| ADATA Technology                 | 3         | 0.52%   |
| Silicon Integrated Systems [SiS] | 2         | 0.34%   |
| Silicon Image                    | 2         | 0.34%   |
| Shenzhen Longsys Electronics     | 2         | 0.34%   |
| Lite-On IT Corp. / Plextor       | 2         | 0.34%   |
| Adaptec                          | 2         | 0.34%   |
| VIA Technologies                 | 1         | 0.17%   |
| Transcend                        | 1         | 0.17%   |
| Solid State Storage Technology   | 1         | 0.17%   |
| Micron/Crucial Technology        | 1         | 0.17%   |
| Lite-On Technology               | 1         | 0.17%   |
| Lenovo                           | 1         | 0.17%   |
| Integrated Technology Express    | 1         | 0.17%   |
| Broadcom                         | 1         | 0.17%   |
| 3ware                            | 1         | 0.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 53        | 7.84%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 19        | 2.81%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 18        | 2.66%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 17        | 2.51%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 16        | 2.37%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 16        | 2.37%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 16        | 2.37%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 16        | 2.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 16        | 2.37%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 15        | 2.22%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 15        | 2.22%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 13        | 1.92%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 13        | 1.92%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 13        | 1.92%   |
| Unknown                                                                          | 12        | 1.78%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 11        | 1.63%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 11        | 1.63%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 10        | 1.48%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 10        | 1.48%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 10        | 1.48%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 9         | 1.33%   |
| AMD 400 Series Chipset SATA Controller                                           | 9         | 1.33%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 7         | 1.04%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 7         | 1.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 7         | 1.04%   |
| JMicron JMB363 SATA/IDE Controller                                               | 6         | 0.89%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 6         | 0.89%   |
| Intel Comet Lake SATA AHCI Controller                                            | 6         | 0.89%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 6         | 0.89%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 6         | 0.89%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 6         | 0.89%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 6         | 0.89%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 5         | 0.74%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 5         | 0.74%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 5         | 0.74%   |
| Nvidia MCP61 SATA Controller                                                     | 5         | 0.74%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 5         | 0.74%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 5         | 0.74%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 5         | 0.74%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 5         | 0.74%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 349       | 60.59%  |
| NVMe | 96        | 16.67%  |
| IDE  | 95        | 16.49%  |
| RAID | 23        | 3.99%   |
| SAS  | 9         | 1.56%   |
| SCSI | 4         | 0.69%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Intel              | 349       | 73.94%  |
| AMD                | 101       | 21.4%   |
| ARM                | 14        | 2.97%   |
| Unknown            | 4         | 0.85%   |
| Rockchip           | 2         | 0.42%   |
| PowerPC            | 1         | 0.21%   |
| Baikal Electronics | 1         | 0.21%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel Core i3-6006U CPU @ 2.00GHz        | 5         | 1.04%   |
| Intel Celeron CPU J1800 @ 2.41GHz        | 5         | 1.04%   |
| Intel 686-class                          | 5         | 1.04%   |
| AMD Ryzen 5 3600 6-Core Processor        | 5         | 1.04%   |
| Intel Core i7-8565U CPU @ 1.80GHz        | 4         | 0.84%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 4         | 0.84%   |
| Intel Celeron N5105 @ 2.00GHz            | 4         | 0.84%   |
| Intel Celeron CPU J1900 @ 1.99GHz        | 4         | 0.84%   |
| ARM Cortex-A57 r1p3                      | 4         | 0.84%   |
|                                          | 4         | 0.84%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz   | 3         | 0.63%   |
| Intel Pentium CPU N4200 @ 1.10GHz        | 3         | 0.63%   |
| Intel Pentium CPU N3700 @ 1.60GHz        | 3         | 0.63%   |
| Intel CPU Version                        | 3         | 0.63%   |
| Intel Core i7-6700 CPU @ 3.40GHz         | 3         | 0.63%   |
| Intel Core i7-3770 CPU @ 3.40GHz         | 3         | 0.63%   |
| Intel Core i5-8350U CPU @ 1.70GHz        | 3         | 0.63%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 3         | 0.63%   |
| Intel Core i3-3220 CPU @ 3.30GHz         | 3         | 0.63%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz    | 3         | 0.63%   |
| Intel Celeron J4125 CPU @ 2.00GHz        | 3         | 0.63%   |
| Intel Celeron CPU J3455 @ 1.50GHz        | 3         | 0.63%   |
| Intel Celeron CPU 1037U @ 1.80GHz        | 3         | 0.63%   |
| Intel C1                                 | 3         | 0.63%   |
| ARM Cortex-A7 r0p5 (ECO: 0x00000000)     | 3         | 0.63%   |
| ARM Cortex-A55 r2p0                      | 3         | 0.63%   |
| AMD Ryzen 9 3900X 12-Core Processor      | 3         | 0.63%   |
| AMD Ryzen 7 5825U with Radeon Graphics   | 3         | 0.63%   |
| AMD Ryzen 7 5800H with Radeon Graphics   | 3         | 0.63%   |
| AMD Ryzen 5 2600 Six-Core Processor      | 3         | 0.63%   |
| AMD GX-412TC SOC                         | 3         | 0.63%   |
| Rockchip RK3566 (Cortex-A55)             | 2         | 0.42%   |
| Intel Xeon CPU X3450 @ 2.67GHz           | 2         | 0.42%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz      | 2         | 0.42%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz      | 2         | 0.42%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz      | 2         | 0.42%   |
| Intel Xeon CPU E31270 @ 3.40GHz          | 2         | 0.42%   |
| Intel Xeon CPU E3-1265L V2 @ 2.50GHz     | 2         | 0.42%   |
| Intel Xeon Bronze 3104 CPU @ 1.70GHz     | 2         | 0.42%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz | 2         | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 58        | 12.18%  |
| Intel Xeon              | 46        | 9.66%   |
| Intel Celeron           | 46        | 9.66%   |
| Intel Core i7           | 40        | 8.4%    |
| Intel Core i3           | 30        | 6.3%    |
| Other                   | 22        | 4.62%   |
| Intel Core 2 Duo        | 19        | 3.99%   |
| AMD Ryzen 7             | 18        | 3.78%   |
| AMD Ryzen 5             | 18        | 3.78%   |
| Intel Pentium           | 16        | 3.36%   |
| Intel Atom              | 15        | 3.15%   |
| ARM Cortex              | 14        | 2.94%   |
| Intel Core 2 Quad       | 10        | 2.1%    |
| AMD Ryzen 3             | 9         | 1.89%   |
| Intel Pentium 4         | 7         | 1.47%   |
| Intel Pentium Dual-Core | 6         | 1.26%   |
| Intel Pentium Gold      | 5         | 1.05%   |
| Intel Genuine           | 5         | 1.05%   |
| Intel 686-class         | 5         | 1.05%   |
| AMD E                   | 5         | 1.05%   |
| Intel Pentium Silver    | 4         | 0.84%   |
| Intel Pentium M         | 4         | 0.84%   |
| AMD FX                  | 4         | 0.84%   |
| AMD A6                  | 4         | 0.84%   |
| Intel Pentium Dual      | 3         | 0.63%   |
| Intel Pentium D         | 3         | 0.63%   |
| Intel Core i9           | 3         | 0.63%   |
| Intel Core 2            | 3         | 0.63%   |
| AMD Ryzen 9             | 3         | 0.63%   |
| AMD Ryzen 7 PRO         | 3         | 0.63%   |
| AMD Opteron             | 3         | 0.63%   |
| AMD GX                  | 3         | 0.63%   |
| AMD Athlon 64 X2        | 3         | 0.63%   |
| AMD A10                 | 3         | 0.63%   |
| Intel Xeon Gold         | 2         | 0.42%   |
| Intel Xeon Bronze       | 2         | 0.42%   |
| Intel Core m3           | 2         | 0.42%   |
| AMD Turion II Neo       | 2         | 0.42%   |
| AMD Ryzen 5 PRO         | 2         | 0.42%   |
| AMD Phenom II X6        | 2         | 0.42%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 145       | 30.4%   |
| 2       | 135       | 28.3%   |
| Unknown | 65        | 13.63%  |
| 6       | 34        | 7.13%   |
| 8       | 30        | 6.29%   |
| 1       | 22        | 4.61%   |
| 16      | 18        | 3.77%   |
| 12      | 15        | 3.14%   |
| 24      | 6         | 1.26%   |
| 28      | 3         | 0.63%   |
| 3       | 2         | 0.42%   |
| 48      | 1         | 0.21%   |
| 14      | 1         | 0.21%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 418       | 87.63%  |
| Unknown | 37        | 7.76%   |
| 2       | 22        | 4.61%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 234       | 48.95%  |
| 2       | 164       | 34.31%  |
| Unknown | 80        | 16.74%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 50        | 10.53%  |
| Unknown       | 40        | 8.42%   |
| IvyBridge     | 38        | 8%      |
| Penryn        | 34        | 7.16%   |
| SandyBridge   | 32        | 6.74%   |
| Haswell       | 31        | 6.53%   |
| Skylake       | 25        | 5.26%   |
| Silvermont    | 22        | 4.63%   |
| Zen 2         | 20        | 4.21%   |
| Core          | 16        | 3.37%   |
| K10           | 15        | 3.16%   |
| Bonnell       | 14        | 2.95%   |
| NetBurst      | 12        | 2.53%   |
| Goldmont      | 12        | 2.53%   |
| Zen+          | 11        | 2.32%   |
| Zen           | 11        | 2.32%   |
| Zen 3         | 10        | 2.11%   |
| Nehalem       | 10        | 2.11%   |
| P6            | 9         | 1.89%   |
| Piledriver    | 8         | 1.68%   |
| CometLake     | 8         | 1.68%   |
| Broadwell     | 8         | 1.68%   |
| Westmere      | 7         | 1.47%   |
| Goldmont plus | 6         | 1.26%   |
| Puma          | 5         | 1.05%   |
| K8 Hammer     | 5         | 1.05%   |
| Bobcat        | 5         | 1.05%   |
| Excavator     | 3         | 0.63%   |
| TigerLake     | 2         | 0.42%   |
| Jaguar        | 2         | 0.42%   |
| Steamroller   | 1         | 0.21%   |
| IceLake       | 1         | 0.21%   |
| Geode         | 1         | 0.21%   |
| Bulldozer     | 1         | 0.21%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 222       | 46.35%  |
| AMD                        | 115       | 24.01%  |
| Nvidia                     | 109       | 22.76%  |
| Matrox Electronics Systems | 19        | 3.97%   |
| ASPEED Technology          | 12        | 2.51%   |
| VIA Technologies           | 1         | 0.21%   |
| ATI                        | 1         | 0.21%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15        | 3.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 13        | 2.63%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 12        | 2.43%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 2.02%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 10        | 2.02%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 9         | 1.82%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 9         | 1.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 1.62%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 7         | 1.42%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 7         | 1.42%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 1.42%   |
| Intel JasperLake [UHD Graphics]                                                          | 7         | 1.42%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 1.42%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 7         | 1.42%   |
| AMD Renoir                                                                               | 7         | 1.42%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 1.42%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 6         | 1.21%   |
| Intel UHD Graphics 620                                                                   | 6         | 1.21%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 1.21%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 6         | 1.21%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 6         | 1.21%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 6         | 1.21%   |
| AMD ES1000                                                                               | 6         | 1.21%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 6         | 1.21%   |
| Intel HD Graphics 630                                                                    | 5         | 1.01%   |
| Intel HD Graphics 530                                                                    | 5         | 1.01%   |
| Intel HD Graphics 500                                                                    | 5         | 1.01%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 5         | 1.01%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5         | 1.01%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 5         | 1.01%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 5         | 1.01%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 4         | 0.81%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4         | 0.81%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 4         | 0.81%   |
| Matrox Electronics Systems MGA G200EH                                                    | 4         | 0.81%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 0.81%   |
| Intel HD Graphics 620                                                                    | 4         | 0.81%   |
| Intel 82865G Integrated Graphics Controller                                              | 4         | 0.81%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4         | 0.81%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 0.81%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 178       | 37.55%  |
| 1 x AMD         | 96        | 20.25%  |
| 1 x Nvidia      | 86        | 18.14%  |
| Other           | 26        | 5.49%   |
| 1 x Matrox      | 19        | 4.01%   |
| 2 x Intel       | 18        | 3.8%    |
| Intel + Nvidia  | 18        | 3.8%    |
| 1 x ASPEED      | 11        | 2.32%   |
| 2 x AMD         | 9         | 1.9%    |
| Intel + AMD     | 8         | 1.69%   |
| AMD + Nvidia    | 3         | 0.63%   |
| 1 x VIA         | 1         | 0.21%   |
| Nvidia + ASPEED | 1         | 0.21%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 374       | 78.57%  |
| Proprietary | 64        | 13.45%  |
| Unknown     | 38        | 7.98%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 365       | 76.04%  |
| 0.01-0.5   | 30        | 6.25%   |
| 1.01-2.0   | 28        | 5.83%   |
| 0.51-1.0   | 21        | 4.38%   |
| 3.01-4.0   | 16        | 3.33%   |
| 7.01-8.0   | 8         | 1.67%   |
| 5.01-6.0   | 7         | 1.46%   |
| 8.01-16.0  | 3         | 0.63%   |
| 2.01-3.0   | 2         | 0.42%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 41        | 16.27%  |
| AU Optronics            | 27        | 10.71%  |
| Goldstar                | 22        | 8.73%   |
| LG Display              | 16        | 6.35%   |
| BOE                     | 15        | 5.95%   |
| Dell                    | 14        | 5.56%   |
| ViewSonic               | 13        | 5.16%   |
| Chimei Innolux          | 13        | 5.16%   |
| Acer                    | 11        | 4.37%   |
| Philips                 | 10        | 3.97%   |
| Ancor Communications    | 10        | 3.97%   |
| NEC Computers           | 6         | 2.38%   |
| BenQ                    | 6         | 2.38%   |
| AOC                     | 6         | 2.38%   |
| InfoVision              | 5         | 1.98%   |
| Hewlett-Packard         | 5         | 1.98%   |
| Sony                    | 4         | 1.59%   |
| LG Philips              | 3         | 1.19%   |
| Lenovo                  | 3         | 1.19%   |
| Chi Mei Optoelectronics | 3         | 1.19%   |
| RTK                     | 2         | 0.79%   |
| PANDA                   | 2         | 0.79%   |
| Panasonic               | 2         | 0.79%   |
| Iiyama                  | 2         | 0.79%   |
| HKC                     | 2         | 0.79%   |
| Fujitsu Siemens         | 2         | 0.79%   |
| Apple                   | 2         | 0.79%   |
| Unknown (CDD)           | 1         | 0.4%    |
| Toshiba                 | 1         | 0.4%    |
| HannStar                | 1         | 0.4%    |
| CSO                     | 1         | 0.4%    |
| CPT                     | 1         | 0.4%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| ViewSonic LCD Monitor VSCD22B 1920x1080 520x290mm 23.4-inch              | 4         | 1.54%   |
| Ancor Communications ASUS VW199 ACI19ED 1440x900 410x260mm 19.1-inch     | 4         | 1.54%   |
| ViewSonic LCD Monitor VSCC42B 1920x1080 480x270mm 21.7-inch              | 2         | 0.77%   |
| Samsung Electronics SyncMaster SAM027D 1680x1050 430x270mm 20.0-inch     | 2         | 0.77%   |
| Samsung Electronics SME1920NR SAM06A4 1280x1024 380x300mm 19.1-inch      | 2         | 0.77%   |
| Samsung Electronics SMBX2250 SAM071B 1920x1080 480x270mm 21.7-inch       | 2         | 0.77%   |
| Samsung Electronics S22B300 SAM08AC 1920x1080 480x270mm 21.7-inch        | 2         | 0.77%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 340x190mm 15.3-inch     | 2         | 0.77%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 220x130mm 10.1-inch     | 2         | 0.77%   |
| Samsung Electronics LCD Monitor SAM0AC6 1920x1080 1110x620mm 50.1-inch   | 2         | 0.77%   |
| RTK WCS Display RTK1A1B 1920x1080 344x195mm 15.6-inch                    | 2         | 0.77%   |
| Philips PHL 240V5 PHLC10A 1920x1080 530x300mm 24.0-inch                  | 2         | 0.77%   |
| NEC Computers FE791SB NEC61D7 1600x1200 330x240mm 16.1-inch              | 2         | 0.77%   |
| HKC LCD Monitor HKC3D05 1920x1080 340x190mm 15.3-inch                    | 2         | 0.77%   |
| Goldstar W1934 GSM4B7A 1440x900 410x260mm 19.1-inch                      | 2         | 0.77%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 2         | 0.77%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2         | 0.77%   |
| Goldstar LCD Monitor GSM5AB6 1920x1080 480x270mm 21.7-inch               | 2         | 0.77%   |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                        | 2         | 0.77%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 340x190mm 15.3-inch         | 2         | 0.77%   |
| Chi Mei Optoelectronics LCD Monitor CMO1457 1366x768 310x170mm 13.9-inch | 2         | 0.77%   |
| BOE LCD Monitor BOE0691 1920x1080 280x160mm 12.7-inch                    | 2         | 0.77%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch            | 2         | 0.77%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch            | 2         | 0.77%   |
| Acer K272HUL ACR0524 2560x1440 600x340mm 27.2-inch                       | 2         | 0.77%   |
| Acer AL1716 ACRAD46 1280x1024 340x270mm 17.1-inch                        | 2         | 0.77%   |
| ViewSonic VX2458-mhd VSC0437 1920x1080 520x290mm 23.4-inch               | 1         | 0.39%   |
| ViewSonic VP171s-2 VSC4B1B 1280x1024 340x270mm 17.1-inch                 | 1         | 0.39%   |
| ViewSonic VA2710-FHD VSCA736 1920x1080 600x340mm 27.2-inch               | 1         | 0.39%   |
| ViewSonic LCD Monitor VX2451 SERIES 1920x1080                            | 1         | 0.39%   |
| ViewSonic LCD Monitor VSC8724 1440x900 410x260mm 19.1-inch               | 1         | 0.39%   |
| ViewSonic LCD Monitor VSC6F2E 1920x1080 480x270mm 21.7-inch              | 1         | 0.39%   |
| ViewSonic LCD Monitor VSC5826 1366x768 410x230mm 18.5-inch               | 1         | 0.39%   |
| ViewSonic LCD Monitor VSC2528 1920x1080 520x290mm 23.4-inch              | 1         | 0.39%   |
| Unknown (CDD) VGA CDD0030 1920x1080 1150x650mm 52.0-inch                 | 1         | 0.39%   |
| Toshiba TV TSB0108 1360x768 700x390mm 31.5-inch                          | 1         | 0.39%   |
| Sony TV  *00 SNY8204 3840x2160 1220x680mm 55.0-inch                      | 1         | 0.39%   |
| Sony TV  *00 SNY7C04 3840x2160 1080x610mm 48.8-inch                      | 1         | 0.39%   |
| Sony SDM-S75D/F/N SNY3800 1280x1024 340x270mm 17.1-inch                  | 1         | 0.39%   |
| Sony SDM-E76D SNYB200 1280x1024 340x270mm 17.1-inch                      | 1         | 0.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 112       | 44.98%  |
| 1366x768 (WXGA)    | 35        | 14.06%  |
| 1280x1024 (SXGA)   | 22        | 8.84%   |
| 3840x2160 (4K)     | 13        | 5.22%   |
| 1440x900 (WXGA+)   | 11        | 4.42%   |
| 1920x1200 (WUXGA)  | 9         | 3.61%   |
| 1600x900 (HD+)     | 9         | 3.61%   |
| 1680x1050 (WSXGA+) | 8         | 3.21%   |
| 2560x1440 (QHD)    | 7         | 2.81%   |
| 1280x800 (WXGA)    | 6         | 2.41%   |
| 1024x600           | 4         | 1.61%   |
| 2560x1080          | 2         | 0.8%    |
| 1600x1200          | 2         | 0.8%    |
| 3440x1440          | 1         | 0.4%    |
| 3200x1800 (QHD+)   | 1         | 0.4%    |
| 2880x1620          | 1         | 0.4%    |
| 2520x1680          | 1         | 0.4%    |
| 2240x1400          | 1         | 0.4%    |
| 2160x1440          | 1         | 0.4%    |
| 1920x540           | 1         | 0.4%    |
| 1024x768 (XGA)     | 1         | 0.4%    |
| Unknown            | 1         | 0.4%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 50        | 19.76%  |
| 13      | 28        | 11.07%  |
| 21      | 24        | 9.49%   |
| 24      | 21        | 8.3%    |
| 19      | 20        | 7.91%   |
| 17      | 20        | 7.91%   |
| 23      | 16        | 6.32%   |
| 27      | 15        | 5.93%   |
| Unknown | 9         | 3.56%   |
| 14      | 6         | 2.37%   |
| 18      | 5         | 1.98%   |
| 12      | 5         | 1.98%   |
| 11      | 5         | 1.98%   |
| 10      | 5         | 1.98%   |
| 31      | 4         | 1.58%   |
| 22      | 4         | 1.58%   |
| 20      | 3         | 1.19%   |
| 16      | 3         | 1.19%   |
| 50      | 2         | 0.79%   |
| 34      | 2         | 0.79%   |
| 57      | 1         | 0.4%    |
| 55      | 1         | 0.4%    |
| 54      | 1         | 0.4%    |
| 52      | 1         | 0.4%    |
| 48      | 1         | 0.4%    |
| 26      | 1         | 0.4%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 87        | 34.66%  |
| 501-600     | 52        | 20.72%  |
| 401-500     | 46        | 18.33%  |
| 201-300     | 29        | 11.55%  |
| 351-400     | 15        | 5.98%   |
| Unknown     | 9         | 3.59%   |
| 1001-1500   | 7         | 2.79%   |
| 601-700     | 4         | 1.59%   |
| 701-800     | 2         | 0.8%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 170       | 69.96%  |
| 16/10   | 36        | 14.81%  |
| 5/4     | 22        | 9.05%   |
| Unknown | 8         | 3.29%   |
| 4/3     | 3         | 1.23%   |
| 3/2     | 2         | 0.82%   |
| 21/9    | 2         | 0.82%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 57        | 22.53%  |
| 91-100         | 42        | 16.6%   |
| 81-90          | 25        | 9.88%   |
| 151-200        | 24        | 9.49%   |
| 141-150        | 18        | 7.11%   |
| 301-350        | 16        | 6.32%   |
| 101-110        | 10        | 3.95%   |
| Unknown        | 9         | 3.56%   |
| 251-300        | 8         | 3.16%   |
| More than 1000 | 7         | 2.77%   |
| 71-80          | 7         | 2.77%   |
| 351-500        | 6         | 2.37%   |
| 121-130        | 6         | 2.37%   |
| 61-70          | 5         | 1.98%   |
| 51-60          | 5         | 1.98%   |
| 41-50          | 5         | 1.98%   |
| 131-140        | 3         | 1.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 103       | 41.04%  |
| 101-120       | 57        | 22.71%  |
| 121-160       | 54        | 21.51%  |
| 161-240       | 22        | 8.76%   |
| Unknown       | 9         | 3.59%   |
| 1-50          | 4         | 1.59%   |
| More than 240 | 2         | 0.8%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 236       | 48.66%  |
| 0     | 229       | 47.22%  |
| 2     | 19        | 3.92%   |
| 3     | 1         | 0.21%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 244       | 37.37%  |
| Intel                             | 209       | 32.01%  |
| Qualcomm Atheros                  | 74        | 11.33%  |
| Broadcom                          | 30        | 4.59%   |
| Marvell Technology Group          | 18        | 2.76%   |
| VIA Technologies                  | 6         | 0.92%   |
| TP-Link                           | 6         | 0.92%   |
| D-Link System                     | 6         | 0.92%   |
| Ralink Technology                 | 5         | 0.77%   |
| Huawei Technologies               | 4         | 0.61%   |
| Ralink                            | 3         | 0.46%   |
| Nvidia                            | 3         | 0.46%   |
| IMC Networks                      | 3         | 0.46%   |
| D-Link                            | 3         | 0.46%   |
| 3Com                              | 3         | 0.46%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.31%   |
| Samsung Electronics               | 2         | 0.31%   |
| Qualcomm                          | 2         | 0.31%   |
| QLogic                            | 2         | 0.31%   |
| Mercucys                          | 2         | 0.31%   |
| Fibocom                           | 2         | 0.31%   |
| Ericsson Business Mobile Networks | 2         | 0.31%   |
| ASUSTek Computer                  | 2         | 0.31%   |
| Arduino SA                        | 2         | 0.31%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.15%   |
| Sundance Technology Inc / IC Plus | 1         | 0.15%   |
| Realtek                           | 1         | 0.15%   |
| Qualcomm Atheros Communications   | 1         | 0.15%   |
| Qcom                              | 1         | 0.15%   |
| OPPO Electronics                  | 1         | 0.15%   |
| MYRICOM                           | 1         | 0.15%   |
| MediaTek                          | 1         | 0.15%   |
| JMicron Technology                | 1         | 0.15%   |
| Edimax Technology                 | 1         | 0.15%   |
| Dell                              | 1         | 0.15%   |
| BUFFALO                           | 1         | 0.15%   |
| Attansic                          | 1         | 0.15%   |
| Atmel                             | 1         | 0.15%   |
| Atheros                           | 1         | 0.15%   |
| Aquantia                          | 1         | 0.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 202       | 26.44%  |
| Intel I211 Gigabit Network Connection                             | 18        | 2.36%   |
| Intel 82574L Gigabit Network Connection                           | 18        | 2.36%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 17        | 2.23%   |
| Intel I350 Gigabit Network Connection                             | 16        | 2.09%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15        | 1.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13        | 1.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 1.18%   |
| Intel Wireless 7265                                               | 9         | 1.18%   |
| Intel I210 Gigabit Network Connection                             | 9         | 1.18%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 8         | 1.05%   |
| Intel Wireless 8265 / 8275                                        | 8         | 1.05%   |
| Intel Wi-Fi 6 AX200                                               | 8         | 1.05%   |
| Intel 82576 Gigabit Network Connection                            | 8         | 1.05%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 7         | 0.92%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 7         | 0.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6         | 0.79%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 6         | 0.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 6         | 0.79%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 6         | 0.79%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 6         | 0.79%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 5         | 0.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 0.65%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 0.65%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 5         | 0.65%   |
| Intel Wireless 8260                                               | 5         | 0.65%   |
| Intel Ethernet Controller I225-V                                  | 5         | 0.65%   |
| Intel Ethernet Connection (7) I219-V                              | 5         | 0.65%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 5         | 0.65%   |
| Intel 82579V Gigabit Network Connection                           | 5         | 0.65%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 4         | 0.52%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 4         | 0.52%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 4         | 0.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 0.52%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 4         | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.52%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4         | 0.52%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 4         | 0.52%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 4         | 0.52%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 4         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 92        | 40.89%  |
| Qualcomm Atheros                | 54        | 24%     |
| Realtek Semiconductor           | 38        | 16.89%  |
| Broadcom                        | 11        | 4.89%   |
| TP-Link                         | 6         | 2.67%   |
| Ralink Technology               | 5         | 2.22%   |
| Ralink                          | 3         | 1.33%   |
| IMC Networks                    | 3         | 1.33%   |
| D-Link                          | 3         | 1.33%   |
| Mercucys                        | 2         | 0.89%   |
| ASUSTek Computer                | 2         | 0.89%   |
| Qualcomm Atheros Communications | 1         | 0.44%   |
| Qcom                            | 1         | 0.44%   |
| MediaTek                        | 1         | 0.44%   |
| Edimax Technology               | 1         | 0.44%   |
| BUFFALO                         | 1         | 0.44%   |
| Atheros                         | 1         | 0.44%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 17        | 7.42%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 9         | 3.93%   |
| Intel Wireless 7265                                                         | 9         | 3.93%   |
| Intel Wireless 8265 / 8275                                                  | 8         | 3.49%   |
| Intel Wi-Fi 6 AX200                                                         | 8         | 3.49%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 7         | 3.06%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                            | 7         | 3.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 6         | 2.62%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 6         | 2.62%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 6         | 2.62%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                    | 6         | 2.62%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                    | 5         | 2.18%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                            | 5         | 2.18%   |
| Intel Wireless 8260                                                         | 5         | 2.18%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 4         | 1.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 4         | 1.75%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                            | 4         | 1.75%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 4         | 1.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 4         | 1.75%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 3         | 1.31%   |
| Intel Wireless 7260                                                         | 3         | 1.31%   |
| Intel Wireless 3165                                                         | 3         | 1.31%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                             | 3         | 1.31%   |
| Intel Comet Lake PCH CNVi WiFi                                              | 3         | 1.31%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                  | 2         | 0.87%   |
| Realtek RTL8723DE Wireless Network Adapter                                  | 2         | 0.87%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                             | 2         | 0.87%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                       | 2         | 0.87%   |
| Mercucys MERCUSYS Wireless USB Adapter                                      | 2         | 0.87%   |
| Intel Wireless-AC 9260                                                      | 2         | 0.87%   |
| Intel WiFi Link 5100                                                        | 2         | 0.87%   |
| Intel Ultimate N WiFi Link 5300                                             | 2         | 0.87%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                   | 2         | 0.87%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                           | 2         | 0.87%   |
| Intel Centrino Wireless-N 2200                                              | 2         | 0.87%   |
| Intel Centrino Advanced-N 6235                                              | 2         | 0.87%   |
| Intel Cannon Lake PCH CNVi WiFi                                             | 2         | 0.87%   |
| IMC Networks Realtek RTL8191SU Wireless LAN 802.11n USB 2.0 Network Adapter | 2         | 0.87%   |
| D-Link DWA-125 Wireless N 150 Adapter(rev.B1) [Ralink RT5370]               | 2         | 0.87%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                          | 2         | 0.87%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 228       | 47.8%   |
| Intel                             | 148       | 31.03%  |
| Qualcomm Atheros                  | 26        | 5.45%   |
| Broadcom                          | 20        | 4.19%   |
| Marvell Technology Group          | 18        | 3.77%   |
| VIA Technologies                  | 6         | 1.26%   |
| D-Link System                     | 6         | 1.26%   |
| Nvidia                            | 3         | 0.63%   |
| 3Com                              | 3         | 0.63%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.42%   |
| Samsung Electronics               | 2         | 0.42%   |
| Qualcomm                          | 2         | 0.42%   |
| QLogic                            | 2         | 0.42%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.21%   |
| Sundance Technology Inc / IC Plus | 1         | 0.21%   |
| Realtek                           | 1         | 0.21%   |
| OPPO Electronics                  | 1         | 0.21%   |
| MYRICOM                           | 1         | 0.21%   |
| JMicron Technology                | 1         | 0.21%   |
| Huawei Technologies               | 1         | 0.21%   |
| Attansic                          | 1         | 0.21%   |
| Aquantia                          | 1         | 0.21%   |
| Apple                             | 1         | 0.21%   |
| Accton Technology                 | 1         | 0.21%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 202       | 39%     |
| Intel I211 Gigabit Network Connection                             | 18        | 3.47%   |
| Intel 82574L Gigabit Network Connection                           | 18        | 3.47%   |
| Intel I350 Gigabit Network Connection                             | 16        | 3.09%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15        | 2.9%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13        | 2.51%   |
| Intel I210 Gigabit Network Connection                             | 9         | 1.74%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 8         | 1.54%   |
| Intel 82576 Gigabit Network Connection                            | 8         | 1.54%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 6         | 1.16%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 5         | 0.97%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 0.97%   |
| Intel Ethernet Controller I225-V                                  | 5         | 0.97%   |
| Intel Ethernet Connection (7) I219-V                              | 5         | 0.97%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 5         | 0.97%   |
| Intel 82579V Gigabit Network Connection                           | 5         | 0.97%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 4         | 0.77%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 4         | 0.77%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.77%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4         | 0.77%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 4         | 0.77%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 4         | 0.77%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 4         | 0.77%   |
| Intel Ethernet Connection I217-V                                  | 4         | 0.77%   |
| Intel Ethernet Connection (2) I219-LM                             | 4         | 0.77%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                | 4         | 0.77%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 4         | 0.77%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 0.58%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 3         | 0.58%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 3         | 0.58%   |
| Intel Ethernet Controller I226-V                                  | 3         | 0.58%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.58%   |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 0.58%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.58%   |
| Intel 82562EZ 10/100 Ethernet Controller                          | 3         | 0.58%   |
| Intel 82540EM Gigabit Ethernet Controller                         | 3         | 0.58%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                  | 3         | 0.58%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.39%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 2         | 0.39%   |
| QLogic FastLinQ QL41000 Series 10/25/40/50GbE Controller          | 2         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 420       | 65.52%  |
| WiFi     | 204       | 31.83%  |
| Unknown  | 10        | 1.56%   |
| Modem    | 7         | 1.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 360       | 73.62%  |
| WiFi     | 126       | 25.77%  |
| Unknown  | 3         | 0.61%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 198       | 41.6%   |
| 1     | 173       | 36.34%  |
| 3     | 38        | 7.98%   |
| 0     | 29        | 6.09%   |
| 4     | 21        | 4.41%   |
| 6     | 6         | 1.26%   |
| 5     | 4         | 0.84%   |
| 7     | 3         | 0.63%   |
| 9     | 2         | 0.42%   |
| 8     | 2         | 0.42%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 457       | 96.01%  |
| Yes  | 19        | 3.99%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 67        | 48.55%  |
| Realtek Semiconductor           | 13        | 9.42%   |
| Qualcomm Atheros Communications | 13        | 9.42%   |
| Broadcom                        | 7         | 5.07%   |
| IMC Networks                    | 6         | 4.35%   |
| ASUSTek Computer                | 5         | 3.62%   |
| Foxconn / Hon Hai               | 4         | 2.9%    |
| Cambridge Silicon Radio         | 4         | 2.9%    |
| Realtek                         | 3         | 2.17%   |
| Lite-On Technology              | 3         | 2.17%   |
| Apple                           | 3         | 2.17%   |
| Alps Electric                   | 3         | 2.17%   |
| Hewlett-Packard                 | 2         | 1.45%   |
| Ralink                          | 1         | 0.72%   |
| Opticis                         | 1         | 0.72%   |
| Edimax Technology               | 1         | 0.72%   |
| Dell                            | 1         | 0.72%   |
| Bluetooth Device                | 1         | 0.72%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 28        | 20.29%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 10        | 7.25%   |
| Intel AX200 Bluetooth                                       | 9         | 6.52%   |
| Intel Wireless-AC 3168 Bluetooth                            | 7         | 5.07%   |
| Intel AX201 Bluetooth                                       | 7         | 5.07%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 5         | 3.62%   |
| Realtek  Bluetooth Adapter                                  | 4         | 2.9%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 4         | 2.9%    |
| Realtek RTL8723B Bluetooth                                  | 3         | 2.17%   |
| Realtek Bluetooth Radio                                     | 3         | 2.17%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 3         | 2.17%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 3         | 2.17%   |
| Realtek  Bluetooth 4.0 Adapter                              | 2         | 1.45%   |
| Realtek  Bluetooth 4.0 + High Speed Chip                    | 2         | 1.45%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 1.45%   |
| Lite-On Atheros AR3012 Bluetooth                            | 2         | 1.45%   |
| IMC Networks Realtek Bluetooth Adapter                      | 2         | 1.45%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 2         | 1.45%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 1.45%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 1.45%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 0.72%   |
| Realtek Bluetooth Radio                                     | 1         | 0.72%   |
| Ralink RT3290 Bluetooth                                     | 1         | 0.72%   |
| Qualcomm Atheros  QCA9565 Bluetooth 4.0 + HS Adapter        | 1         | 0.72%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 0.72%   |
| Qualcomm Atheros Atheros AR9462 Bluetooth 3.0 + HS Adapter  | 1         | 0.72%   |
| Opticis Bluetooth Radio                                     | 1         | 0.72%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 0.72%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 0.72%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 1         | 0.72%   |
| Intel AX210 Bluetooth                                       | 1         | 0.72%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip        | 1         | 0.72%   |
| IMC Networks Qualcomm Atheros AR9462 Bluetooth 4.0          | 1         | 0.72%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 0.72%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter                  | 1         | 0.72%   |
| Foxconn / Hon Hai Wireless_Device                           | 1         | 0.72%   |
| Foxconn / Hon Hai Qualcomm Atheros Bluetooth 4.0            | 1         | 0.72%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3012 Bluetooth Adapter | 1         | 0.72%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 0.72%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter     | 1         | 0.72%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 285       | 57%     |
| AMD                                          | 102       | 20.4%   |
| Nvidia                                       | 77        | 15.4%   |
| C-Media Electronics                          | 5         | 1%      |
| Realtek Semiconductor                        | 3         | 0.6%    |
| Logitech                                     | 3         | 0.6%    |
| Lenovo                                       | 3         | 0.6%    |
| VIA Technologies                             | 2         | 0.4%    |
| Texas Instruments                            | 2         | 0.4%    |
| Silicon Integrated Systems [SiS]             | 2         | 0.4%    |
| JMTek                                        | 2         | 0.4%    |
| ESS Technology                               | 2         | 0.4%    |
| Creative Technology                          | 2         | 0.4%    |
| Creative Labs                                | 2         | 0.4%    |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.2%    |
| SteelSeries ApS                              | 1         | 0.2%    |
| Samsung Electronics                          | 1         | 0.2%    |
| Microsoft                                    | 1         | 0.2%    |
| KTMicro                                      | 1         | 0.2%    |
| GN Netcom                                    | 1         | 0.2%    |
| Generalplus Technology                       | 1         | 0.2%    |
| FiiO Electronics Technology                  | 1         | 0.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 32        | 5.53%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 30        | 5.18%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 27        | 4.66%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 25        | 4.32%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 21        | 3.63%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 19        | 3.28%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 14        | 2.42%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 14        | 2.42%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 13        | 2.25%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 13        | 2.25%   |
| Intel Cannon Lake PCH cAVS                                                                        | 12        | 2.07%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 12        | 2.07%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 11        | 1.9%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 11        | 1.9%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 10        | 1.73%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 10        | 1.73%   |
| AMD FCH Azalia Controller                                                                         | 10        | 1.73%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 10        | 1.73%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 9         | 1.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 8         | 1.38%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 7         | 1.21%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 7         | 1.21%   |
| Intel Jasper Lake HD Audio                                                                        | 7         | 1.21%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 1.21%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 7         | 1.21%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 1.21%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 1.21%   |
| Intel 8 Series HD Audio Controller                                                                | 7         | 1.21%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 1.21%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 7         | 1.21%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 6         | 1.04%   |
| Intel Comet Lake PCH cAVS                                                                         | 6         | 1.04%   |
| Intel 200 Series PCH HD Audio                                                                     | 6         | 1.04%   |
| Nvidia High Definition Audio Controller                                                           | 5         | 0.86%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 0.86%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 5         | 0.86%   |
| Nvidia MCP79 High Definition Audio                                                                | 4         | 0.69%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 4         | 0.69%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 0.69%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Unknown                                 | 89        | 19.56%  |
| Kingston                                | 87        | 19.12%  |
| Samsung Electronics                     | 67        | 14.73%  |
| SK hynix                                | 52        | 11.43%  |
| Micron Technology                       | 27        | 5.93%   |
| Crucial                                 | 21        | 4.62%   |
| Unknown                                 | 17        | 3.74%   |
| AMD                                     | 10        | 2.2%    |
| Corsair                                 | 9         | 1.98%   |
| A-DATA Technology                       | 8         | 1.76%   |
| Patriot                                 | 7         | 1.54%   |
| G.Skill                                 | 5         | 1.1%    |
| Elpida                                  | 5         | 1.1%    |
| Transcend                               | 4         | 0.88%   |
| Ramaxel Technology                      | 4         | 0.88%   |
| Nanya Technology                        | 4         | 0.88%   |
| Patriot Memory (PDP Systems)            | 3         | 0.66%   |
| Goldkey                                 | 3         | 0.66%   |
| Apacer                                  | 3         | 0.66%   |
| 48spaces                                | 3         | 0.66%   |
| Unifosa                                 | 2         | 0.44%   |
| Kllisre                                 | 2         | 0.44%   |
| Hewlett-Packard                         | 2         | 0.44%   |
| Goodram                                 | 2         | 0.44%   |
| Atermiter                               | 2         | 0.44%   |
| Unknown (ABCD)                          | 1         | 0.22%   |
| Unknown (0x0DD5)                        | 1         | 0.22%   |
| Unknown (0x0809)                        | 1         | 0.22%   |
| Unknown (0x0191)                        | 1         | 0.22%   |
| Tigo                                    | 1         | 0.22%   |
| Silicon Power Computer & Communications | 1         | 0.22%   |
| Silicon Power                           | 1         | 0.22%   |
| S                                       | 1         | 0.22%   |
| Ramos Technology                        | 1         | 0.22%   |
| Qumo                                    | 1         | 0.22%   |
| PUSKILL                                 | 1         | 0.22%   |
| Netac                                   | 1         | 0.22%   |
| Kingmax                                 | 1         | 0.22%   |
| Innodisk                                | 1         | 0.22%   |
| H                                       | 1         | 0.22%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                   | 17        | 3.33%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                      | 6         | 1.17%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 6         | 1.17%   |
| Unknown RAM Module 1GB DIMM SDRAM                                         | 5         | 0.98%   |
| Unknown RAM Module 512MB DIMM SDRAM                                       | 4         | 0.78%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                      | 4         | 0.78%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                               | 4         | 0.78%   |
| Unknown RAM Module 512MB SODIMM DDR                                       | 3         | 0.59%   |
| Unknown RAM Module 2GB DIMM SDRAM                                         | 3         | 0.59%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s                    | 3         | 0.59%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s                    | 3         | 0.59%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 3         | 0.59%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s                    | 3         | 0.59%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s                     | 3         | 0.59%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s                     | 3         | 0.59%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 1333MT/s                       | 3         | 0.59%   |
| Kingston RAM 9905711-015.A00G 4GB SODIMM DDR4 2400MT/s                    | 3         | 0.59%   |
| Crucial RAM CT51264BA160B.C16F 4GB DIMM DDR3 1600MT/s                     | 3         | 0.59%   |
| AMD RAM R748G2400U2S 8GB DIMM DDR4 2400MT/s                               | 3         | 0.59%   |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3400MT/s                               | 3         | 0.59%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 3         | 0.59%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                                      | 2         | 0.39%   |
| Unknown RAM Module 8192MB DIMM 1066MT/s                                   | 2         | 0.39%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                                 | 2         | 0.39%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 2         | 0.39%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                                  | 2         | 0.39%   |
| Unknown RAM Module 2GB DIMM 800MT/s                                       | 2         | 0.39%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                               | 2         | 0.39%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                                | 2         | 0.39%   |
| Unknown RAM Module 1GB DIMM 1333MT/s                                      | 2         | 0.39%   |
| Unknown RAM Module 1024MB DIMM SDRAM                                      | 2         | 0.39%   |
| SK hynix RAM Module 4GB Chip LPDDR4                                       | 2         | 0.39%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s                      | 2         | 0.39%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM 1333MT/s                         | 2         | 0.39%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s                    | 2         | 0.39%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s                     | 2         | 0.39%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s                     | 2         | 0.39%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 2         | 0.39%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s                     | 2         | 0.39%   |
| Samsung RAM M393A2K40BB2-CTD 16GB DIMM DDR4 2667MT/s                      | 2         | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 148       | 37%     |
| DDR3    | 144       | 36%     |
| DDR2    | 34        | 8.5%    |
| Unknown | 29        | 7.25%   |
| SDRAM   | 17        | 4.25%   |
| DDR     | 13        | 3.25%   |
| LPDDR3  | 7         | 1.75%   |
| LPDDR4  | 3         | 0.75%   |
| DRAM    | 3         | 0.75%   |
| RAM     | 1         | 0.25%   |
| LPDDR5  | 1         | 0.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 233       | 58.25%  |
| SODIMM       | 155       | 38.75%  |
| Row Of Chips | 8         | 2%      |
| Chip         | 3         | 0.75%   |
| FB-DIMM      | 1         | 0.25%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 123       | 27.7%   |
| 4096  | 116       | 26.13%  |
| 2048  | 87        | 19.59%  |
| 16384 | 54        | 12.16%  |
| 1024  | 34        | 7.66%   |
| 512   | 15        | 3.38%   |
| 32768 | 8         | 1.8%    |
| 256   | 3         | 0.68%   |
| 65536 | 1         | 0.23%   |
| 2560  | 1         | 0.23%   |
| 128   | 1         | 0.23%   |
| 8     | 1         | 0.23%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 70        | 16.75%  |
| 1333    | 65        | 15.55%  |
| 2400    | 53        | 12.68%  |
| 3200    | 46        | 11%     |
| 2667    | 32        | 7.66%   |
| Unknown | 28        | 6.7%    |
| 800     | 23        | 5.5%    |
| 667     | 23        | 5.5%    |
| 2133    | 16        | 3.83%   |
| 1066    | 8         | 1.91%   |
| 1867    | 7         | 1.67%   |
| 1067    | 7         | 1.67%   |
| 400     | 7         | 1.67%   |
| 2666    | 4         | 0.96%   |
| 3400    | 3         | 0.72%   |
| 2933    | 3         | 0.72%   |
| 533     | 3         | 0.72%   |
| 3000    | 2         | 0.48%   |
| 2048    | 2         | 0.48%   |
| 1866    | 2         | 0.48%   |
| 1334    | 2         | 0.48%   |
| 266     | 2         | 0.48%   |
| 6400    | 1         | 0.24%   |
| 3733    | 1         | 0.24%   |
| 3600    | 1         | 0.24%   |
| 1400    | 1         | 0.24%   |
| 1332    | 1         | 0.24%   |
| 975     | 1         | 0.24%   |
| 933     | 1         | 0.24%   |
| 333     | 1         | 0.24%   |
| 133     | 1         | 0.24%   |
| 100     | 1         | 0.24%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Seiko Epson        | 1         | 25%     |
| Kyocera            | 1         | 25%     |
| Hewlett-Packard    | 1         | 25%     |
| Brother Industries | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Seiko Epson USB2.0 Printer (Hi-speed) | 1         | 25%     |
| Kyocera FS-1025MFP                    | 1         | 25%     |
| HP HP Laser 107w                      | 1         | 25%     |
| Brother HL-2030 Laser Printer         | 1         | 25%     |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 29        | 23.39%  |
| IMC Networks                           | 14        | 11.29%  |
| Realtek Semiconductor                  | 12        | 9.68%   |
| Microdia                               | 12        | 9.68%   |
| Acer                                   | 7         | 5.65%   |
| Suyin                                  | 5         | 4.03%   |
| Lite-On Technology                     | 5         | 4.03%   |
| Quanta                                 | 4         | 3.23%   |
| ALi                                    | 4         | 3.23%   |
| Z-Star Microelectronics                | 3         | 2.42%   |
| Syntek                                 | 3         | 2.42%   |
| Silicon Motion                         | 3         | 2.42%   |
| Sunplus Innovation Technology          | 2         | 1.61%   |
| ShineTech                              | 2         | 1.61%   |
| Ricoh                                  | 2         | 1.61%   |
| Luxvisions Innotech Limited            | 2         | 1.61%   |
| Logitech                               | 2         | 1.61%   |
| DigiTech                               | 2         | 1.61%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.61%   |
| Arkmicro Technologies                  | 2         | 1.61%   |
| SunplusIT                              | 1         | 0.81%   |
| Sonix Technology                       | 1         | 0.81%   |
| Intel                                  | 1         | 0.81%   |
| Huawei Technologies                    | 1         | 0.81%   |
| Denron                                 | 1         | 0.81%   |
| Aveo Technology                        | 1         | 0.81%   |
| A4Tech                                 | 1         | 0.81%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 10        | 7.94%   |
| Microdia Integrated_Webcam_HD                       | 5         | 3.97%   |
| IMC Networks Integrated Camera                      | 5         | 3.97%   |
| Realtek Realtek USB2.0 PC Camera                    | 3         | 2.38%   |
| Realtek Acer 640 x 480 laptop camera                | 3         | 2.38%   |
| Quanta VGA WebCam                                   | 3         | 2.38%   |
| ALi Gateway Webcam                                  | 3         | 2.38%   |
| Acer Lenovo EasyCamera                              | 3         | 2.38%   |
| Syntek EasyCamera                                   | 2         | 1.59%   |
| Silicon Motion WebCam SCX Series                    | 2         | 1.59%   |
| ShineTech HD Camera                                 | 2         | 1.59%   |
| Realtek Integrated Webcam                           | 2         | 1.59%   |
| Microdia USB Camera                                 | 2         | 1.59%   |
| Microdia Integrated Webcam                          | 2         | 1.59%   |
| Lite-On Integrated Camera                           | 2         | 1.59%   |
| Lite-On HP HD Camera                                | 2         | 1.59%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 2         | 1.59%   |
| IMC Networks EasyCamera                             | 2         | 1.59%   |
| DigiTech WebCam SCB-0350M                           | 2         | 1.59%   |
| Chicony XiaoMi USB 2.0 Webcam                       | 2         | 1.59%   |
| Z-Star Webcam                                       | 1         | 0.79%   |
| Z-Star Venus USB2.0 Camera                          | 1         | 0.79%   |
| Z-Star Integrated Camera                            | 1         | 0.79%   |
| Syntek Lenovo EasyCamera                            | 1         | 0.79%   |
| Suyin USB 2.0 UVC 1.3M WebCam                       | 1         | 0.79%   |
| Suyin HP Webcam                                     | 1         | 0.79%   |
| Suyin HD WebCam                                     | 1         | 0.79%   |
| Suyin HD Video WebCam                               | 1         | 0.79%   |
| Suyin Acer Crystal Eye webcam                       | 1         | 0.79%   |
| SunplusIT XiaoMi USB 2.0 Webcam                     | 1         | 0.79%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 0.79%   |
| Sunplus HD WebCam                                   | 1         | 0.79%   |
| Sonix USB2.0 HD UVC WebCam                          | 1         | 0.79%   |
| Silicon Motion WebCam SC-10IRQ12340N                | 1         | 0.79%   |
| Ricoh Visual Communication Camera VGP-VCC3 [R5U870] | 1         | 0.79%   |
| Ricoh USB2.0 Camera                                 | 1         | 0.79%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 0.79%   |
| Realtek USB Webcam                                  | 1         | 0.79%   |
| Realtek USB Video Device                            | 1         | 0.79%   |
| Realtek Integrated_Webcam_FHD                       | 1         | 0.79%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 11        | 30.56%  |
| Synaptics                  | 11        | 30.56%  |
| STMicroelectronics         | 3         | 8.33%   |
| Shenzhen Goodix Technology | 3         | 8.33%   |
| Focal-systems.Corp         | 3         | 8.33%   |
| Upek                       | 2         | 5.56%   |
| AuthenTec                  | 2         | 5.56%   |
| Broadcom                   | 1         | 2.78%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 6         | 16.67%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 3         | 8.33%   |
| STMicroelectronics Fingerprint Reader                                        | 3         | 8.33%   |
| Shenzhen Goodix  Fingerprint Device                                          | 3         | 8.33%   |
| Focal-systems.Corp FocalTech Fingerprint reader                              | 3         | 8.33%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 2         | 5.56%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 2         | 5.56%   |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 2         | 5.56%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 2         | 5.56%   |
| AuthenTec AES1600                                                            | 2         | 5.56%   |
| Unknown                                                                      | 2         | 5.56%   |
| Validity Sensors Synaptics WBDI                                              | 1         | 2.78%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint   | 1         | 2.78%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                    | 1         | 2.78%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 1         | 2.78%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 1         | 2.78%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 2.78%   |

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


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 182       | 37.07%  |
| 1     | 179       | 36.46%  |
| 2     | 75        | 15.27%  |
| 3     | 28        | 5.7%    |
| 4     | 21        | 4.28%   |
| 7     | 2         | 0.41%   |
| 9     | 1         | 0.2%    |
| 8     | 1         | 0.2%    |
| 6     | 1         | 0.2%    |
| 5     | 1         | 0.2%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 211       | 46.48%  |
| Net/wireless             | 62        | 13.66%  |
| Bluetooth                | 40        | 8.81%   |
| Card reader              | 34        | 7.49%   |
| Fingerprint reader       | 31        | 6.83%   |
| Sound                    | 23        | 5.07%   |
| Firewire controller      | 21        | 4.63%   |
| Graphics card            | 9         | 1.98%   |
| Network                  | 7         | 1.54%   |
| Storage                  | 6         | 1.32%   |
| Net/ethernet             | 4         | 0.88%   |
| Storage/ata              | 3         | 0.66%   |
| Modem                    | 3         | 0.66%   |

