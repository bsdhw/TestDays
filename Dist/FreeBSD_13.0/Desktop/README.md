FreeBSD 13.0 - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for FreeBSD 13.0.

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
| MSI           | B365M PRO-VDH               | [d45ca02f84](https://bsd-hardware.info/?probe=d45ca02f84) | Feb 24, 2022 |
| Biostar       | X470GTA                     | [b7fc5ef684](https://bsd-hardware.info/?probe=b7fc5ef684) | Feb 12, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [d57de875a6](https://bsd-hardware.info/?probe=d57de875a6) | Feb 07, 2022 |
| HP            | ProLiant MicroServer        | [0da2a93271](https://bsd-hardware.info/?probe=0da2a93271) | Jan 11, 2022 |
| HP            | ProLiant MicroServer        | [e95a3dd5ec](https://bsd-hardware.info/?probe=e95a3dd5ec) | Jan 10, 2022 |
| ASRock        | FM2A85X Extreme6            | [c87969f2d8](https://bsd-hardware.info/?probe=c87969f2d8) | Jan 09, 2022 |
| ASRock        | Z170M Extreme4              | [c518ded272](https://bsd-hardware.info/?probe=c518ded272) | Jan 09, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [dd62d57a45](https://bsd-hardware.info/?probe=dd62d57a45) | Dec 29, 2021 |
| Gigabyte      | P67A-D3-B3                  | [62f424cac5](https://bsd-hardware.info/?probe=62f424cac5) | Dec 26, 2021 |
| ASUSTek       | ROG Maximus X FORMULA       | [8a9387c5da](https://bsd-hardware.info/?probe=8a9387c5da) | Dec 11, 2021 |
| ASUSTek       | ROG Maximus X FORMULA       | [9762ebd7c7](https://bsd-hardware.info/?probe=9762ebd7c7) | Dec 10, 2021 |
| MSI           | H81M-P33                    | [237b84b5fc](https://bsd-hardware.info/?probe=237b84b5fc) | Dec 09, 2021 |
| Cisco Syst... | UCSC-C240-M3L 74-10443-0... | [3956ad0525](https://bsd-hardware.info/?probe=3956ad0525) | Dec 09, 2021 |
| ASUSTek       | P5B                         | [93b542ab79](https://bsd-hardware.info/?probe=93b542ab79) | Dec 06, 2021 |
| Gigabyte      | GA-8S661FXM-775             | [3a64909558](https://bsd-hardware.info/?probe=3a64909558) | Dec 06, 2021 |
| ASUSTek       | P7P55D                      | [540d2ef68c](https://bsd-hardware.info/?probe=540d2ef68c) | Nov 29, 2021 |
| ASUSTek       | P5Q-E                       | [0ed5f516f4](https://bsd-hardware.info/?probe=0ed5f516f4) | Nov 21, 2021 |
| ASUSTek       | P5Q-E                       | [48c39762c6](https://bsd-hardware.info/?probe=48c39762c6) | Nov 14, 2021 |
| ASUSTek       | P5Q-E                       | [6c875941b3](https://bsd-hardware.info/?probe=6c875941b3) | Nov 07, 2021 |
| ASUSTek       | P5Q-E                       | [19a0911df6](https://bsd-hardware.info/?probe=19a0911df6) | Oct 31, 2021 |
| ASUSTek       | P5Q-E                       | [a33aece313](https://bsd-hardware.info/?probe=a33aece313) | Oct 24, 2021 |
| firefly       | roc-rk3399-pc-plus          | [39c78ac754](https://bsd-hardware.info/?probe=39c78ac754) | Oct 19, 2021 |
| firefly       | roc-rk3399-pc-plus          | [5173ffc13b](https://bsd-hardware.info/?probe=5173ffc13b) | Oct 17, 2021 |
| ASUSTek       | P5Q-E                       | [9e9b5166bc](https://bsd-hardware.info/?probe=9e9b5166bc) | Oct 17, 2021 |
| ASUSTek       | P5Q-E                       | [da31eaf836](https://bsd-hardware.info/?probe=da31eaf836) | Oct 17, 2021 |
| MSI           | H81M-P33                    | [2e84516857](https://bsd-hardware.info/?probe=2e84516857) | Oct 17, 2021 |
| Dell          | 0Y7WYT A00                  | [1de7ed2a67](https://bsd-hardware.info/?probe=1de7ed2a67) | Oct 16, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [6ceda5d7b4](https://bsd-hardware.info/?probe=6ceda5d7b4) | Oct 15, 2021 |
| ASUSTek       | P5Q-E                       | [65954adbf3](https://bsd-hardware.info/?probe=65954adbf3) | Oct 10, 2021 |
| MSI           | H81M-P33                    | [592dbd7c17](https://bsd-hardware.info/?probe=592dbd7c17) | Oct 10, 2021 |
| ASUSTek       | P5Q-E                       | [00efddc7e4](https://bsd-hardware.info/?probe=00efddc7e4) | Oct 10, 2021 |
| ASUSTek       | P5Q-E                       | [d65e453ea7](https://bsd-hardware.info/?probe=d65e453ea7) | Oct 03, 2021 |
| MSI           | H81M-P33                    | [fd498893fb](https://bsd-hardware.info/?probe=fd498893fb) | Oct 03, 2021 |
| ASUSTek       | P5Q-E                       | [0bfcd11255](https://bsd-hardware.info/?probe=0bfcd11255) | Oct 03, 2021 |
| ASUSTek       | H81M-E                      | [0cc0d2dcb1](https://bsd-hardware.info/?probe=0cc0d2dcb1) | Oct 01, 2021 |
| ASUSTek       | H81M-E                      | [76866f2db7](https://bsd-hardware.info/?probe=76866f2db7) | Oct 01, 2021 |
| ASUSTek       | H81M-E                      | [319470ebbd](https://bsd-hardware.info/?probe=319470ebbd) | Oct 01, 2021 |
| ASUSTek       | P5Q-E                       | [18cd64ae96](https://bsd-hardware.info/?probe=18cd64ae96) | Sep 26, 2021 |
| MSI           | H81M-P33                    | [8a8d67b8b1](https://bsd-hardware.info/?probe=8a8d67b8b1) | Sep 26, 2021 |
| ASUSTek       | P5Q-E                       | [fb056a1840](https://bsd-hardware.info/?probe=fb056a1840) | Sep 26, 2021 |
| ASUSTek       | H81M-E                      | [137654a2f8](https://bsd-hardware.info/?probe=137654a2f8) | Sep 24, 2021 |
| ASUSTek       | H81M-E                      | [dec23f7ff8](https://bsd-hardware.info/?probe=dec23f7ff8) | Sep 23, 2021 |
| ASUSTek       | P5Q-E                       | [6b68e14399](https://bsd-hardware.info/?probe=6b68e14399) | Sep 19, 2021 |
| MSI           | H81M-P33                    | [60ec488627](https://bsd-hardware.info/?probe=60ec488627) | Sep 19, 2021 |
| ASUSTek       | P5Q-E                       | [c2d07d370e](https://bsd-hardware.info/?probe=c2d07d370e) | Sep 19, 2021 |
| Unknown       | Unknown                     | [392cf6ec24](https://bsd-hardware.info/?probe=392cf6ec24) | Sep 17, 2021 |
| firefly       | roc-rk3399-pc-plus          | [198c4264f9](https://bsd-hardware.info/?probe=198c4264f9) | Sep 16, 2021 |
| firefly       | roc-rk3399-pc-plus          | [d05c3ba858](https://bsd-hardware.info/?probe=d05c3ba858) | Sep 15, 2021 |
| firefly       | roc-rk3399-pc-plus          | [062602e8db](https://bsd-hardware.info/?probe=062602e8db) | Sep 15, 2021 |
| ASUSTek       | P5Q-E                       | [4d1aa99478](https://bsd-hardware.info/?probe=4d1aa99478) | Sep 12, 2021 |
| ASUSTek       | P5Q-E                       | [8055702eac](https://bsd-hardware.info/?probe=8055702eac) | Sep 12, 2021 |
| MSI           | H81M-P33                    | [a8feb1807d](https://bsd-hardware.info/?probe=a8feb1807d) | Sep 12, 2021 |
| Unknown       | Unknown                     | [5933c93a5b](https://bsd-hardware.info/?probe=5933c93a5b) | Sep 09, 2021 |
| ASUSTek       | P5Q-E                       | [b1677cb485](https://bsd-hardware.info/?probe=b1677cb485) | Sep 05, 2021 |
| ASUSTek       | P5Q-E                       | [33392e3299](https://bsd-hardware.info/?probe=33392e3299) | Sep 05, 2021 |
| MSI           | H81M-P33                    | [ad52aa4ea5](https://bsd-hardware.info/?probe=ad52aa4ea5) | Sep 05, 2021 |
| ASUSTek       | P5Q-E                       | [1d408ec8df](https://bsd-hardware.info/?probe=1d408ec8df) | Aug 29, 2021 |
| ASUSTek       | P5Q-E                       | [37fe7a021f](https://bsd-hardware.info/?probe=37fe7a021f) | Aug 29, 2021 |
| MSI           | H81M-P33                    | [90f439a559](https://bsd-hardware.info/?probe=90f439a559) | Aug 29, 2021 |
| Medion        | MS-7616                     | [98f0e21e6c](https://bsd-hardware.info/?probe=98f0e21e6c) | Aug 26, 2021 |
| Medion        | MS-7616                     | [663b50102d](https://bsd-hardware.info/?probe=663b50102d) | Aug 26, 2021 |
| ASRock        | B450M Pro4                  | [70dc185964](https://bsd-hardware.info/?probe=70dc185964) | Aug 25, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [3e088c942b](https://bsd-hardware.info/?probe=3e088c942b) | Aug 22, 2021 |
| ASUSTek       | P5Q-E                       | [0db2178b94](https://bsd-hardware.info/?probe=0db2178b94) | Aug 22, 2021 |
| ASUSTek       | P5Q-E                       | [eee5ea8171](https://bsd-hardware.info/?probe=eee5ea8171) | Aug 22, 2021 |
| MSI           | H81M-P33                    | [ceb4fcb174](https://bsd-hardware.info/?probe=ceb4fcb174) | Aug 22, 2021 |
| ASUSTek       | P5Q-E                       | [9fa08ee32f](https://bsd-hardware.info/?probe=9fa08ee32f) | Aug 15, 2021 |
| ASUSTek       | P5Q-E                       | [3f15cbe8cc](https://bsd-hardware.info/?probe=3f15cbe8cc) | Aug 15, 2021 |
| MSI           | H81M-P33                    | [8a9a281ee1](https://bsd-hardware.info/?probe=8a9a281ee1) | Aug 15, 2021 |
| Cisco Syst... | UCSC-C240-M3L 74-10443-0... | [adf41eedab](https://bsd-hardware.info/?probe=adf41eedab) | Aug 13, 2021 |
| Cisco Syst... | UCSC-C240-M3L 74-10443-0... | [4dd5f1c0c6](https://bsd-hardware.info/?probe=4dd5f1c0c6) | Aug 12, 2021 |
| Cisco Syst... | UCSC-C240-M3L 74-10443-0... | [1c835c20cb](https://bsd-hardware.info/?probe=1c835c20cb) | Aug 09, 2021 |
| ASUSTek       | P5Q-E                       | [b972923c8d](https://bsd-hardware.info/?probe=b972923c8d) | Aug 08, 2021 |
| MSI           | H81M-P33                    | [5ae84c8d07](https://bsd-hardware.info/?probe=5ae84c8d07) | Aug 08, 2021 |
| ASUSTek       | P5Q-E                       | [e51135c93a](https://bsd-hardware.info/?probe=e51135c93a) | Aug 08, 2021 |
| ASUSTek       | P5Q-E                       | [048bfd8f45](https://bsd-hardware.info/?probe=048bfd8f45) | Aug 01, 2021 |
| ASUSTek       | P5Q-E                       | [faeca32de9](https://bsd-hardware.info/?probe=faeca32de9) | Aug 01, 2021 |
| MSI           | H81M-P33                    | [062450ca66](https://bsd-hardware.info/?probe=062450ca66) | Aug 01, 2021 |
| ASUSTek       | P5Q-E                       | [692320f986](https://bsd-hardware.info/?probe=692320f986) | Jul 25, 2021 |
| ASUSTek       | P5Q-E                       | [ca4e2c4a94](https://bsd-hardware.info/?probe=ca4e2c4a94) | Jul 25, 2021 |
| ASRock        | X570 Phantom Gaming 4       | [586c14dd63](https://bsd-hardware.info/?probe=586c14dd63) | Jul 23, 2021 |
| ASUSTek       | PRIME X370-PRO              | [389bf7ae4b](https://bsd-hardware.info/?probe=389bf7ae4b) | Jul 23, 2021 |
| ASUSTek       | P5Q-E                       | [d041bb0182](https://bsd-hardware.info/?probe=d041bb0182) | Jul 18, 2021 |
| ASUSTek       | P5Q-E                       | [9cdc6262f6](https://bsd-hardware.info/?probe=9cdc6262f6) | Jul 18, 2021 |
| Dell          | 0HD5W2 A00                  | [8315a3b948](https://bsd-hardware.info/?probe=8315a3b948) | Jul 17, 2021 |
| Dell          | 0HD5W2 A00                  | [8780a9eb26](https://bsd-hardware.info/?probe=8780a9eb26) | Jul 17, 2021 |
| Cisco Syst... | UCSC-C240-M3L 74-10443-0... | [fb1c3af983](https://bsd-hardware.info/?probe=fb1c3af983) | Jul 16, 2021 |
| Cisco Syst... | UCSC-C240-M3L 74-10443-0... | [9d729e0508](https://bsd-hardware.info/?probe=9d729e0508) | Jul 13, 2021 |
| ASUSTek       | PRIME X370-PRO              | [5038f75992](https://bsd-hardware.info/?probe=5038f75992) | Jul 13, 2021 |
| ASUSTek       | P5Q-E                       | [d859525592](https://bsd-hardware.info/?probe=d859525592) | Jul 11, 2021 |
| ASUSTek       | P5Q-E                       | [708d1e2608](https://bsd-hardware.info/?probe=708d1e2608) | Jul 11, 2021 |
| Pegatron      | IPPCR-SS                    | [86b2e85d24](https://bsd-hardware.info/?probe=86b2e85d24) | Jul 05, 2021 |
| Dell          | 0HD5W2 A00                  | [9fe5dd4b75](https://bsd-hardware.info/?probe=9fe5dd4b75) | Jul 04, 2021 |
| Dell          | 0HD5W2 A00                  | [e85afd7989](https://bsd-hardware.info/?probe=e85afd7989) | Jul 04, 2021 |
| ASUSTek       | P5Q-E                       | [e24689b692](https://bsd-hardware.info/?probe=e24689b692) | Jul 04, 2021 |
| ASUSTek       | P5Q-E                       | [c62837354b](https://bsd-hardware.info/?probe=c62837354b) | Jul 04, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [7360fb3199](https://bsd-hardware.info/?probe=7360fb3199) | Jul 03, 2021 |
| Gigabyte      | A320M-S2H-CF                | [c1a27ca913](https://bsd-hardware.info/?probe=c1a27ca913) | Jun 27, 2021 |
| ASUSTek       | P5Q-E                       | [1e5ccb0c3c](https://bsd-hardware.info/?probe=1e5ccb0c3c) | Jun 27, 2021 |
| ASUSTek       | P5Q-E                       | [96d46d6f38](https://bsd-hardware.info/?probe=96d46d6f38) | Jun 27, 2021 |
| ASUSTek       | P5Q-E                       | [ac70749f81](https://bsd-hardware.info/?probe=ac70749f81) | Jun 20, 2021 |
| ASUSTek       | P5Q-E                       | [d6c3fe4058](https://bsd-hardware.info/?probe=d6c3fe4058) | Jun 20, 2021 |
| MSI           | H81M-P33                    | [2a26234f71](https://bsd-hardware.info/?probe=2a26234f71) | Jun 20, 2021 |
| Wistron       | ProLiant ML110 G6           | [8f336c0fa3](https://bsd-hardware.info/?probe=8f336c0fa3) | Jun 19, 2021 |
| Wistron       | ProLiant ML110 G6           | [dc619f203f](https://bsd-hardware.info/?probe=dc619f203f) | Jun 19, 2021 |
| Raspberry ... | rpi                         | [692d412c0c](https://bsd-hardware.info/?probe=692d412c0c) | Jun 14, 2021 |
| ASUSTek       | PRIME X370-PRO              | [c066194e27](https://bsd-hardware.info/?probe=c066194e27) | Jun 13, 2021 |
| ASUSTek       | P5K SE/EPU                  | [60d9b24b69](https://bsd-hardware.info/?probe=60d9b24b69) | Jun 13, 2021 |
| ASUSTek       | P5Q-E                       | [197b4515ad](https://bsd-hardware.info/?probe=197b4515ad) | Jun 13, 2021 |
| ASUSTek       | P5Q-E                       | [4af3098758](https://bsd-hardware.info/?probe=4af3098758) | Jun 13, 2021 |
| MSI           | H81M-P33                    | [48d5da63d6](https://bsd-hardware.info/?probe=48d5da63d6) | Jun 13, 2021 |
| ASRock        | B450M Pro4                  | [9a7adb8860](https://bsd-hardware.info/?probe=9a7adb8860) | Jun 06, 2021 |
| ASUSTek       | P5Q-E                       | [84abffd607](https://bsd-hardware.info/?probe=84abffd607) | Jun 06, 2021 |
| ASUSTek       | P5Q-E                       | [65893eaa25](https://bsd-hardware.info/?probe=65893eaa25) | Jun 06, 2021 |
| MSI           | H81M-P33                    | [54636fa78f](https://bsd-hardware.info/?probe=54636fa78f) | Jun 06, 2021 |
| MSI           | MAG Z490 TOMAHAWK           | [0b3c9a332d](https://bsd-hardware.info/?probe=0b3c9a332d) | May 31, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | [a87473149b](https://bsd-hardware.info/?probe=a87473149b) | May 31, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | [82d464f2a8](https://bsd-hardware.info/?probe=82d464f2a8) | May 31, 2021 |
| ASUSTek       | P5Q-E                       | [f8036fdef4](https://bsd-hardware.info/?probe=f8036fdef4) | May 30, 2021 |
| MSI           | H81M-P33                    | [9ff6febdba](https://bsd-hardware.info/?probe=9ff6febdba) | May 30, 2021 |
| ASUSTek       | P5Q-E                       | [aabcf92dd5](https://bsd-hardware.info/?probe=aabcf92dd5) | May 30, 2021 |
| Gigabyte      | B85-HD3                     | [331da3091c](https://bsd-hardware.info/?probe=331da3091c) | May 28, 2021 |
| MSI           | X399 GAMING PRO CARBON A... | [20052b0d55](https://bsd-hardware.info/?probe=20052b0d55) | May 27, 2021 |
| ASUSTek       | P7H55-M/USB3                | [87068a97be](https://bsd-hardware.info/?probe=87068a97be) | May 26, 2021 |
| ASRock        | X570 Phantom Gaming-ITX/... | [2247c7130f](https://bsd-hardware.info/?probe=2247c7130f) | May 26, 2021 |
| HP            | 1790                        | [59e472fb01](https://bsd-hardware.info/?probe=59e472fb01) | May 24, 2021 |
| HP            | 1790                        | [3a4e33eb4d](https://bsd-hardware.info/?probe=3a4e33eb4d) | May 24, 2021 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | [f035aab141](https://bsd-hardware.info/?probe=f035aab141) | May 24, 2021 |
| ASRock        | X570 Phantom Gaming-ITX/... | [4d15a3ffe3](https://bsd-hardware.info/?probe=4d15a3ffe3) | May 23, 2021 |
| ASUSTek       | P5Q-E                       | [d76f0d88b2](https://bsd-hardware.info/?probe=d76f0d88b2) | May 23, 2021 |
| ASUSTek       | P5Q-E                       | [9589f37f30](https://bsd-hardware.info/?probe=9589f37f30) | May 23, 2021 |
| MSI           | H81M-P33                    | [67ce92aee6](https://bsd-hardware.info/?probe=67ce92aee6) | May 23, 2021 |
| MSI           | H61I-E35/W8                 | [d07ad10827](https://bsd-hardware.info/?probe=d07ad10827) | May 22, 2021 |
| HP            | ProLiant MicroServer Gen... | [80cf566074](https://bsd-hardware.info/?probe=80cf566074) | May 21, 2021 |
| ASRock        | J3455-ITX                   | [c9218ee21d](https://bsd-hardware.info/?probe=c9218ee21d) | May 17, 2021 |
| ASUSTek       | P5Q-E                       | [3d35e6b890](https://bsd-hardware.info/?probe=3d35e6b890) | May 16, 2021 |
| ASUSTek       | P5Q-E                       | [9e4c7bf061](https://bsd-hardware.info/?probe=9e4c7bf061) | May 16, 2021 |
| MSI           | H81M-P33                    | [3f3f826118](https://bsd-hardware.info/?probe=3f3f826118) | May 16, 2021 |
| EVGA          | X299 FTW K                  | [c4862c598a](https://bsd-hardware.info/?probe=c4862c598a) | May 11, 2021 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | [a9a897258e](https://bsd-hardware.info/?probe=a9a897258e) | May 11, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [8d78068ca7](https://bsd-hardware.info/?probe=8d78068ca7) | May 09, 2021 |
| ASUSTek       | P5Q-E                       | [dfb015cf64](https://bsd-hardware.info/?probe=dfb015cf64) | May 09, 2021 |
| ASUSTek       | P5Q-E                       | [cbfba11dfe](https://bsd-hardware.info/?probe=cbfba11dfe) | May 09, 2021 |
| MSI           | H81M-P33                    | [6a9b635e7c](https://bsd-hardware.info/?probe=6a9b635e7c) | May 09, 2021 |
| Shuttle       | FH87                        | [bf5457ff02](https://bsd-hardware.info/?probe=bf5457ff02) | May 09, 2021 |
| ASUSTek       | P8H77-M PRO                 | [87e5651fd1](https://bsd-hardware.info/?probe=87e5651fd1) | May 06, 2021 |
| Gigabyte      | X58A-UD5                    | [24502c7f7b](https://bsd-hardware.info/?probe=24502c7f7b) | May 04, 2021 |
| ASRock        | Z170M Extreme4              | [e2d2bb7f28](https://bsd-hardware.info/?probe=e2d2bb7f28) | May 04, 2021 |
| ASUSTek       | TUF GAMING X570-PRO         | [4d7013aeab](https://bsd-hardware.info/?probe=4d7013aeab) | May 04, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [cbbf4f86cd](https://bsd-hardware.info/?probe=cbbf4f86cd) | May 03, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [7fc73d2db3](https://bsd-hardware.info/?probe=7fc73d2db3) | May 03, 2021 |
| ASUSTek       | P5Q-E                       | [7b8ebcef12](https://bsd-hardware.info/?probe=7b8ebcef12) | May 02, 2021 |
| ASUSTek       | P5Q-E                       | [7033f42e70](https://bsd-hardware.info/?probe=7033f42e70) | May 02, 2021 |
| MSI           | H81M-P33                    | [96111749b8](https://bsd-hardware.info/?probe=96111749b8) | May 02, 2021 |
| ASUSTek       | Z97-K                       | [d8ecc7077a](https://bsd-hardware.info/?probe=d8ecc7077a) | May 02, 2021 |
| GVC           | DR 738                      | [9ff0fb7df4](https://bsd-hardware.info/?probe=9ff0fb7df4) | May 01, 2021 |
| Gigabyte      | H81M-S2PV                   | [2713d38658](https://bsd-hardware.info/?probe=2713d38658) | May 01, 2021 |
| Beckhoff A... | CB3056 G4                   | [120665d4d3](https://bsd-hardware.info/?probe=120665d4d3) | Apr 30, 2021 |
| Dell          | 0FJ030                      | [91418a4965](https://bsd-hardware.info/?probe=91418a4965) | Apr 30, 2021 |
| Dell          | 0FJ030                      | [7bee24ee8a](https://bsd-hardware.info/?probe=7bee24ee8a) | Apr 30, 2021 |
| ASUSTek       | P5Q-E                       | [39d9a85a18](https://bsd-hardware.info/?probe=39d9a85a18) | Apr 25, 2021 |
| MSI           | H81M-P33                    | [e0660a37f5](https://bsd-hardware.info/?probe=e0660a37f5) | Apr 25, 2021 |
| ASUSTek       | P5Q-E                       | [1ee72db86e](https://bsd-hardware.info/?probe=1ee72db86e) | Apr 25, 2021 |
| ASUSTek       | SABERTOOTH Z97 MARK 2       | [8055ed41df](https://bsd-hardware.info/?probe=8055ed41df) | Apr 25, 2021 |
| Gigabyte      | F2A75M-HD2                  | [18a74377ac](https://bsd-hardware.info/?probe=18a74377ac) | Apr 25, 2021 |
| Fujitsu       | D3417-B2 S26361-D3417-B2    | [9a0602d408](https://bsd-hardware.info/?probe=9a0602d408) | Apr 25, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [ab8235808d](https://bsd-hardware.info/?probe=ab8235808d) | Apr 23, 2021 |
| ASUSTek       | PRIME X370-PRO              | [6251043541](https://bsd-hardware.info/?probe=6251043541) | Apr 22, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [a932c6d687](https://bsd-hardware.info/?probe=a932c6d687) | Apr 21, 2021 |
| Dell          | 0MWYPT A02                  | [92d895d2d4](https://bsd-hardware.info/?probe=92d895d2d4) | Apr 21, 2021 |
| ASRock        | J4105-ITX                   | [66eee76b50](https://bsd-hardware.info/?probe=66eee76b50) | Apr 21, 2021 |
| ASRock        | H110M-STX                   | [c98cb0e438](https://bsd-hardware.info/?probe=c98cb0e438) | Apr 19, 2021 |
| ASUSTek       | P5Q-E                       | [418cc1382c](https://bsd-hardware.info/?probe=418cc1382c) | Apr 18, 2021 |
| ASUSTek       | P5Q-E                       | [be1821da8a](https://bsd-hardware.info/?probe=be1821da8a) | Apr 18, 2021 |
| MSI           | H81M-P33                    | [3a81fe2ee4](https://bsd-hardware.info/?probe=3a81fe2ee4) | Apr 18, 2021 |
| Unknown       | Unknown                     | [1c4a81b9a5](https://bsd-hardware.info/?probe=1c4a81b9a5) | Apr 17, 2021 |
| Unknown       | Unknown                     | [48090193c1](https://bsd-hardware.info/?probe=48090193c1) | Apr 17, 2021 |
| Unknown       | Unknown                     | [0c708350cd](https://bsd-hardware.info/?probe=0c708350cd) | Apr 17, 2021 |
| Unknown       | Unknown                     | [7b295345e6](https://bsd-hardware.info/?probe=7b295345e6) | Apr 17, 2021 |
| ASRock        | AM1H-ITX                    | [917ee44fe9](https://bsd-hardware.info/?probe=917ee44fe9) | Apr 15, 2021 |
| Beckhoff A... | CB3163 G5                   | [25df932cdf](https://bsd-hardware.info/?probe=25df932cdf) | Apr 14, 2021 |
| Beckhoff A... | CX51x0 G2                   | [ab8247d8b5](https://bsd-hardware.info/?probe=ab8247d8b5) | Apr 14, 2021 |
| Gigabyte      | B450M DS3H-CF               | [431eaac648](https://bsd-hardware.info/?probe=431eaac648) | Apr 14, 2021 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 66       | 91.67%  |
| arm64 | 4        | 5.56%   |
| i386  | 2        | 2.78%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| Console   | 32       | 43.84%  |
| KDE5      | 12       | 16.44%  |
| XFCE      | 10       | 13.7%   |
| GNOME     | 6        | 8.22%   |
| TWM       | 3        | 4.11%   |
| Openbox   | 3        | 4.11%   |
| MATE      | 3        | 4.11%   |
| LXQt      | 1        | 1.37%   |
| Fluxbox   | 1        | 1.37%   |
| Cinnamon  | 1        | 1.37%   |
| AwesomeWM | 1        | 1.37%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 40       | 54.79%  |
| Console | 32       | 43.84%  |
| Wayland | 1        | 1.37%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 47       | 64.38%  |
| SDDM    | 9        | 12.33%  |
| SLiM    | 5        | 6.85%   |
| LightDM | 5        | 6.85%   |
| GDM     | 5        | 6.85%   |
| XDM     | 2        | 2.74%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| C       | 50       | 69.44%  |
| en_US   | 6        | 8.33%   |
| ru_RU   | 4        | 5.56%   |
| de_DE   | 4        | 5.56%   |
| Unknown | 3        | 4.17%   |
| fr_FR   | 2        | 2.78%   |
| nb_NO   | 1        | 1.39%   |
| es_ES   | 1        | 1.39%   |
| en_GB   | 1        | 1.39%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 46       | 62.16%  |
| BIOS | 28       | 37.84%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Zfs  | 53       | 73.61%  |
| Ufs  | 19       | 26.39%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 69       | 95.83%  |
| MBR  | 3        | 4.17%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUSTek Computer        | 19       | 26.39%  |
| Gigabyte Technology     | 12       | 16.67%  |
| ASRock                  | 10       | 13.89%  |
| MSI                     | 6        | 8.33%   |
| Dell                    | 4        | 5.56%   |
| Unknown                 | 4        | 5.56%   |
| Hewlett-Packard         | 3        | 4.17%   |
| Beckhoff Automation     | 3        | 4.17%   |
| Wistron                 | 1        | 1.39%   |
| Shuttle                 | 1        | 1.39%   |
| Raspberry Pi Foundation | 1        | 1.39%   |
| Pegatron                | 1        | 1.39%   |
| Medion                  | 1        | 1.39%   |
| GVC                     | 1        | 1.39%   |
| Fujitsu                 | 1        | 1.39%   |
| firefly                 | 1        | 1.39%   |
| EVGA                    | 1        | 1.39%   |
| Cisco Systems           | 1        | 1.39%   |
| Biostar                 | 1        | 1.39%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 4        | 5.56%   |
| ASUS All Series                    | 3        | 4.17%   |
| Dell OptiPlex 7040                 | 2        | 2.78%   |
| Beckhoff Automation Industrial PC  | 2        | 2.78%   |
| ASUS TUF GAMING X570-PLUS          | 2        | 2.78%   |
| ASUS P5Q-E                         | 2        | 2.78%   |
| ASRock B450M Pro4                  | 2        | 2.78%   |
| Wistron ProLiant ML110 G6          | 1        | 1.39%   |
| Shuttle SH87R                      | 1        | 1.39%   |
| RPi rpi                            | 1        | 1.39%   |
| Pegatron SAISHIAT2                 | 1        | 1.39%   |
| MSI MS-7C80                        | 1        | 1.39%   |
| MSI MS-7C39                        | 1        | 1.39%   |
| MSI MS-7C02                        | 1        | 1.39%   |
| MSI MS-7B09                        | 1        | 1.39%   |
| MSI MS-7817                        | 1        | 1.39%   |
| MSI MS-7677                        | 1        | 1.39%   |
| Medion MS-7616                     | 1        | 1.39%   |
| HP Z220 CMT Workstation            | 1        | 1.39%   |
| HP ProLiant MicroServer Gen8       | 1        | 1.39%   |
| HP ProLiant MicroServer            | 1        | 1.39%   |
| GVC EQUIUM 3200M                   | 1        | 1.39%   |
| Gigabyte X58A-UD5                  | 1        | 1.39%   |
| Gigabyte X570 I AORUS PRO WIFI     | 1        | 1.39%   |
| Gigabyte X570 AORUS ULTRA          | 1        | 1.39%   |
| Gigabyte X470 AORUS GAMING 5 WIFI  | 1        | 1.39%   |
| Gigabyte OFFICEPRO 7000            | 1        | 1.39%   |
| Gigabyte H81M-S2PV                 | 1        | 1.39%   |
| Gigabyte GA-8S661FXM-775           | 1        | 1.39%   |
| Gigabyte F2A75M-HD2                | 1        | 1.39%   |
| Gigabyte B85-HD3                   | 1        | 1.39%   |
| Gigabyte B550M AORUS PRO-P         | 1        | 1.39%   |
| Gigabyte B450M DS3H                | 1        | 1.39%   |
| Gigabyte A320M-S2H                 | 1        | 1.39%   |
| Fujitsu D3417-B2 S26361-D3417-B2   | 1        | 1.39%   |
| firefly roc-rk3399-pc-plus         | 1        | 1.39%   |
| EVGA X299 FTW K                    | 1        | 1.39%   |
| Dell Precision Tower 3620          | 1        | 1.39%   |
| Dell DXP051                        | 1        | 1.39%   |
| Cisco Systems UCSC-C240-M3L        | 1        | 1.39%   |
| Biostar X470GTA                    | 1        | 1.39%   |
| Beckhoff Automation CX5130-0120    | 1        | 1.39%   |
| ASUS TUF GAMING X570-PRO           | 1        | 1.39%   |
| ASUS SABERTOOTH 990FX R2.0         | 1        | 1.39%   |
| ASUS ROG STRIX X570-E GAMING       | 1        | 1.39%   |
| ASUS ROG STRIX X470-F GAMING       | 1        | 1.39%   |
| ASUS ROG Maximus X FORMULA         | 1        | 1.39%   |
| ASUS PRIME X370-PRO                | 1        | 1.39%   |
| ASUS PRIME B450M-GAMING/BR         | 1        | 1.39%   |
| ASUS P8H77-M PRO                   | 1        | 1.39%   |
| ASUS P7P55D                        | 1        | 1.39%   |
| ASUS P7H55-M/USB3                  | 1        | 1.39%   |
| ASUS P5K SE/EPU                    | 1        | 1.39%   |
| ASUS P5B                           | 1        | 1.39%   |
| ASRock Z170M Extreme4              | 1        | 1.39%   |
| ASRock X570 Phantom Gaming-ITX/TB3 | 1        | 1.39%   |
| ASRock X570 Phantom Gaming 4       | 1        | 1.39%   |
| ASRock J4105-ITX                   | 1        | 1.39%   |
| ASRock J3455-ITX                   | 1        | 1.39%   |
| ASRock H110M-STX                   | 1        | 1.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| Unknown                         | 4        | 5.56%   |
| ASUS TUF                        | 3        | 4.17%   |
| ASUS ROG                        | 3        | 4.17%   |
| ASUS All                        | 3        | 4.17%   |
| HP ProLiant                     | 2        | 2.78%   |
| Gigabyte X570                   | 2        | 2.78%   |
| Dell OptiPlex                   | 2        | 2.78%   |
| Beckhoff Automation Industrial  | 2        | 2.78%   |
| ASUS PRIME                      | 2        | 2.78%   |
| ASUS P5Q-E                      | 2        | 2.78%   |
| ASRock X570                     | 2        | 2.78%   |
| ASRock B450M                    | 2        | 2.78%   |
| Wistron ProLiant                | 1        | 1.39%   |
| Shuttle SH87R                   | 1        | 1.39%   |
| RPi rpi                         | 1        | 1.39%   |
| Pegatron SAISHIAT2              | 1        | 1.39%   |
| MSI MS-7C80                     | 1        | 1.39%   |
| MSI MS-7C39                     | 1        | 1.39%   |
| MSI MS-7C02                     | 1        | 1.39%   |
| MSI MS-7B09                     | 1        | 1.39%   |
| MSI MS-7817                     | 1        | 1.39%   |
| MSI MS-7677                     | 1        | 1.39%   |
| Medion MS-7616                  | 1        | 1.39%   |
| HP Z220                         | 1        | 1.39%   |
| GVC EQUIUM                      | 1        | 1.39%   |
| Gigabyte X58A-UD5               | 1        | 1.39%   |
| Gigabyte X470                   | 1        | 1.39%   |
| Gigabyte OFFICEPRO              | 1        | 1.39%   |
| Gigabyte H81M-S2PV              | 1        | 1.39%   |
| Gigabyte GA-8S661FXM-775        | 1        | 1.39%   |
| Gigabyte F2A75M-HD2             | 1        | 1.39%   |
| Gigabyte B85-HD3                | 1        | 1.39%   |
| Gigabyte B550M                  | 1        | 1.39%   |
| Gigabyte B450M                  | 1        | 1.39%   |
| Gigabyte A320M-S2H              | 1        | 1.39%   |
| Fujitsu D3417-B2                | 1        | 1.39%   |
| firefly roc-rk3399-pc-plus      | 1        | 1.39%   |
| EVGA X299                       | 1        | 1.39%   |
| Dell Precision                  | 1        | 1.39%   |
| Dell DXP051                     | 1        | 1.39%   |
| Cisco Systems UCSC-C240-M3L     | 1        | 1.39%   |
| Biostar X470GTA                 | 1        | 1.39%   |
| Beckhoff Automation CX5130-0120 | 1        | 1.39%   |
| ASUS SABERTOOTH                 | 1        | 1.39%   |
| ASUS P8H77-M                    | 1        | 1.39%   |
| ASUS P7P55D                     | 1        | 1.39%   |
| ASUS P7H55-M                    | 1        | 1.39%   |
| ASUS P5K                        | 1        | 1.39%   |
| ASUS P5B                        | 1        | 1.39%   |
| ASRock Z170M                    | 1        | 1.39%   |
| ASRock J4105-ITX                | 1        | 1.39%   |
| ASRock J3455-ITX                | 1        | 1.39%   |
| ASRock H110M-STX                | 1        | 1.39%   |
| ASRock FM2A85X                  | 1        | 1.39%   |
| ASRock AM1H-ITX                 | 1        | 1.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2019    | 11       | 15.28%  |
| 2018    | 9        | 12.5%   |
| 2020    | 8        | 11.11%  |
| 2021    | 5        | 6.94%   |
| 2012    | 5        | 6.94%   |
| 2011    | 5        | 6.94%   |
| 2017    | 4        | 5.56%   |
| 2016    | 4        | 5.56%   |
| 2013    | 4        | 5.56%   |
| 2015    | 3        | 4.17%   |
| 2014    | 3        | 4.17%   |
| 2008    | 3        | 4.17%   |
| Unknown | 3        | 4.17%   |
| 2006    | 2        | 2.78%   |
| 2010    | 1        | 1.39%   |
| 2009    | 1        | 1.39%   |
| 2005    | 1        | 1.39%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 72       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 72       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 16       | 22.22%  |
| 16.01-24.0  | 14       | 19.44%  |
| 64.01-256.0 | 12       | 16.67%  |
| 8.01-16.0   | 12       | 16.67%  |
| 4.01-8.0    | 10       | 13.89%  |
| 2.01-3.0    | 5        | 6.94%   |
| 24.01-32.0  | 2        | 2.78%   |
| 0.01-0.5    | 1        | 1.39%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 23       | 31.51%  |
| 0.51-1.0   | 21       | 28.77%  |
| 1.01-2.0   | 18       | 24.66%  |
| 3.01-4.0   | 4        | 5.48%   |
| 2.01-3.0   | 3        | 4.11%   |
| 4.01-8.0   | 1        | 1.37%   |
| 24.01-32.0 | 1        | 1.37%   |
| 16.01-24.0 | 1        | 1.37%   |
| 0          | 1        | 1.37%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 18       | 24%     |
| 1      | 17       | 22.67%  |
| 3      | 10       | 13.33%  |
| 4      | 8        | 10.67%  |
| 5      | 6        | 8%      |
| 0      | 5        | 6.67%   |
| 7      | 4        | 5.33%   |
| 6      | 4        | 5.33%   |
| 13     | 1        | 1.33%   |
| 12     | 1        | 1.33%   |
| 9      | 1        | 1.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 50       | 68.49%  |
| Yes       | 23       | 31.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 69       | 95.83%  |
| No        | 3        | 4.17%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 47       | 65.28%  |
| Yes       | 25       | 34.72%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 55       | 76.39%  |
| Yes       | 17       | 23.61%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 23       | 31.94%  |
| Russia      | 13       | 18.06%  |
| Germany     | 10       | 13.89%  |
| Netherlands | 5        | 6.94%   |
| UK          | 3        | 4.17%   |
| France      | 3        | 4.17%   |
| Canada      | 2        | 2.78%   |
| Ukraine     | 1        | 1.39%   |
| Thailand    | 1        | 1.39%   |
| Spain       | 1        | 1.39%   |
| Poland      | 1        | 1.39%   |
| Norway      | 1        | 1.39%   |
| New Zealand | 1        | 1.39%   |
| Ireland     | 1        | 1.39%   |
| Guatemala   | 1        | 1.39%   |
| Guadeloupe  | 1        | 1.39%   |
| Finland     | 1        | 1.39%   |
| Czechia     | 1        | 1.39%   |
| Colombia    | 1        | 1.39%   |
| Brazil      | 1        | 1.39%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Seattle             | 3        | 4%      |
| Moscow              | 3        | 4%      |
| Menlo Park          | 3        | 4%      |
| Salem               | 2        | 2.67%   |
| Redmond             | 2        | 2.67%   |
| LГјbeck           | 2        | 2.67%   |
| Kirkland            | 2        | 2.67%   |
| Irkutsk             | 2        | 2.67%   |
| Berlin              | 2        | 2.67%   |
| Yekaterinburg       | 1        | 1.33%   |
| Wenatchee           | 1        | 1.33%   |
| Vostochnoe Degunino | 1        | 1.33%   |
| Vancouver           | 1        | 1.33%   |
| Valladolid          | 1        | 1.33%   |
| Ufa                 | 1        | 1.33%   |
| Tuddal              | 1        | 1.33%   |
| Trang               | 1        | 1.33%   |
| Teteghem            | 1        | 1.33%   |
| Stuttgart           | 1        | 1.33%   |
| St. Catharines      | 1        | 1.33%   |
| Scottsdale          | 1        | 1.33%   |
| Sao Vicente         | 1        | 1.33%   |
| Palo Alto           | 1        | 1.33%   |
| Ozersk              | 1        | 1.33%   |
| Otley               | 1        | 1.33%   |
| Ostrzeszow          | 1        | 1.33%   |
| Ostrava             | 1        | 1.33%   |
| OrlГ©ans          | 1        | 1.33%   |
| Omsk                | 1        | 1.33%   |
| Omaha               | 1        | 1.33%   |
| Oklahoma City       | 1        | 1.33%   |
| Novosibirsk         | 1        | 1.33%   |
| New York            | 1        | 1.33%   |
| Munich              | 1        | 1.33%   |
| MonterГ­a         | 1        | 1.33%   |
| Minneapolis         | 1        | 1.33%   |
| Mead                | 1        | 1.33%   |
| Lexington           | 1        | 1.33%   |
| Le Gosier           | 1        | 1.33%   |
| Kyiv                | 1        | 1.33%   |
| Krommenie           | 1        | 1.33%   |
| Krasnodar           | 1        | 1.33%   |
| Hoofddorp           | 1        | 1.33%   |
| Henderson           | 1        | 1.33%   |
| Helsinki            | 1        | 1.33%   |
| Hebden Bridge       | 1        | 1.33%   |
| Hamburg             | 1        | 1.33%   |
| GГјtersloh        | 1        | 1.33%   |
| Guelph              | 1        | 1.33%   |
| Guatemala City      | 1        | 1.33%   |
| Gilbert             | 1        | 1.33%   |
| Gennevilliers       | 1        | 1.33%   |
| Cologne             | 1        | 1.33%   |
| Cobh                | 1        | 1.33%   |
| Chelyabinsk         | 1        | 1.33%   |
| Brockton            | 1        | 1.33%   |
| Bielefeld           | 1        | 1.33%   |
| Bellevue            | 1        | 1.33%   |
| Auckland            | 1        | 1.33%   |
| Andover             | 1        | 1.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 30       | 96     | 22.9%   |
| Samsung Electronics | 23       | 53     | 17.56%  |
| WDC                 | 17       | 80     | 12.98%  |
| Toshiba             | 10       | 16     | 7.63%   |
| Kingston            | 7        | 7      | 5.34%   |
| Crucial             | 6        | 6      | 4.58%   |
| A-DATA Technology   | 6        | 6      | 4.58%   |
| Intel               | 5        | 6      | 3.82%   |
| HGST                | 5        | 7      | 3.82%   |
| Hitachi             | 3        | 12     | 2.29%   |
| PLEXTOR             | 2        | 3      | 1.53%   |
| Phison              | 2        | 2      | 1.53%   |
| Corsair             | 2        | 2      | 1.53%   |
| VMware              | 1        | 1      | 0.76%   |
| Verbatim            | 1        | 1      | 0.76%   |
| Smartbuy            | 1        | 1      | 0.76%   |
| SK Hynix            | 1        | 1      | 0.76%   |
| Silicon Motion      | 1        | 1      | 0.76%   |
| SanDisk             | 1        | 1      | 0.76%   |
| PNY                 | 1        | 1      | 0.76%   |
| Patriot             | 1        | 1      | 0.76%   |
| Micron Technology   | 1        | 1      | 0.76%   |
| MAXTOR              | 1        | 1      | 0.76%   |
| LITEONIT            | 1        | 1      | 0.76%   |
| KingDian            | 1        | 1      | 0.76%   |
| Intenso             | 1        | 1      | 0.76%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Seagate ST4000DM000-1F2168 4TB       | 4        | 2.48%   |
| Kingston SA400S37120G 120GB          | 3        | 1.86%   |
| WDC WD80EFAX-68LHPN0 8TB             | 2        | 1.24%   |
| WDC WD20EFRX-68EUZN0 2TB             | 2        | 1.24%   |
| Toshiba DT01ACA100 1TB               | 2        | 1.24%   |
| Seagate ST8000VN004-2M2101 8TB       | 2        | 1.24%   |
| Seagate ST4000VN000-1H4168 4TB       | 2        | 1.24%   |
| Seagate ST4000DM004-2CV104 4TB       | 2        | 1.24%   |
| Seagate ST16000NM001G-2KK103 16TB    | 2        | 1.24%   |
| Seagate ST1000LM048-2E7172 1TB       | 2        | 1.24%   |
| Seagate ST1000DM010-2EP102 1TB       | 2        | 1.24%   |
| Samsung SSD 970 EVO Plus 250GB       | 2        | 1.24%   |
| Samsung SSD 970 EVO Plus 1TB         | 2        | 1.24%   |
| Samsung SSD 870 EVO 1TB              | 2        | 1.24%   |
| Samsung SSD 860 EVO 500GB            | 2        | 1.24%   |
| Samsung SSD 860 EVO 1TB              | 2        | 1.24%   |
| Crucial CT120BX500SSD1 120GB         | 2        | 1.24%   |
| WDC WDS500G2B0C-00PXH0 500GB         | 1        | 0.62%   |
| WDC WDS500G2B0B-00YS70 500GB         | 1        | 0.62%   |
| WDC WDS250G2B0A 250GB                | 1        | 0.62%   |
| WDC WD80EMAZ-00WJTA0 8TB             | 1        | 0.62%   |
| WDC WD80EFZX-68UW8N0 8TB             | 1        | 0.62%   |
| WDC WD6003FZBX-00K5WB0 6TB           | 1        | 0.62%   |
| WDC WD5000AAKX-083CA0 500GB          | 1        | 0.62%   |
| WDC WD40EZRZ-22GXCB0 4TB             | 1        | 0.62%   |
| WDC WD40EZAZ-00SF3B0 4TB             | 1        | 0.62%   |
| WDC WD40EFRX-68N32N0 4TB             | 1        | 0.62%   |
| WDC WD30EZRX-00AZ6B0 3TB             | 1        | 0.62%   |
| WDC WD30EFRX-68EUZN0 3TB             | 1        | 0.62%   |
| WDC WD20EARX-00PASB0 2TB             | 1        | 0.62%   |
| WDC WD120EMFZ-11A6JA0 12TB           | 1        | 0.62%   |
| WDC WD120EMAZ-11BLFA0 12TB           | 1        | 0.62%   |
| WDC WD10EZEX-08WN4A0 1TB             | 1        | 0.62%   |
| WDC WD10EADS-00P8B0 1TB              | 1        | 0.62%   |
| WDC WD102KRYZ-01A5AB0 10TB           | 1        | 0.62%   |
| WDC WD100EZAZ-11TDBA0 10TB           | 1        | 0.62%   |
| WDC WD1001FALS-00J7B0 1TB            | 1        | 0.62%   |
| VMware Virtual disk 112GB            | 1        | 0.62%   |
| Verbatim Vi550 S3 SSD 128GB          | 1        | 0.62%   |
| Toshiba MQ02ABD100H 1TB              | 1        | 0.62%   |
| Toshiba MQ01ACF032 320GB             | 1        | 0.62%   |
| Toshiba MK3261GSYN 320GB             | 1        | 0.62%   |
| Toshiba MK1234GSX 120GB              | 1        | 0.62%   |
| Toshiba MG04SCA20EN 2TB              | 1        | 0.62%   |
| Toshiba MG03ACA100 1TB               | 1        | 0.62%   |
| Toshiba HDWE160 6TB                  | 1        | 0.62%   |
| Toshiba HDWD120 2TB                  | 1        | 0.62%   |
| Toshiba HDWD110 1TB                  | 1        | 0.62%   |
| Smartbuy SSD 64GB                    | 1        | 0.62%   |
| SK Hynix SHGS31-500GS-2 500GB        | 1        | 0.62%   |
| Silicon Motion NE-256 256GB          | 1        | 0.62%   |
| Seagate ST980313AS 80GB              | 1        | 0.62%   |
| Seagate ST96812AS 64GB               | 1        | 0.62%   |
| Seagate ST9500423AS 500GB            | 1        | 0.62%   |
| Seagate ST9250827AS 250GB            | 1        | 0.62%   |
| Seagate ST500LM000-1EJ162-SSHD 500GB | 1        | 0.62%   |
| Seagate ST500DM002-1BC142 500GB      | 1        | 0.62%   |
| Seagate ST4000VN008-2DR166 4TB       | 1        | 0.62%   |
| Seagate ST380013AS 80GB              | 1        | 0.62%   |
| Seagate ST380011A 80GB               | 1        | 0.62%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 29       | 95     | 45.31%  |
| WDC                 | 15       | 76     | 23.44%  |
| Toshiba             | 10       | 16     | 15.63%  |
| HGST                | 5        | 7      | 7.81%   |
| Hitachi             | 3        | 12     | 4.69%   |
| Samsung Electronics | 1        | 2      | 1.56%   |
| MAXTOR              | 1        | 1      | 1.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 17       | 36     | 32.08%  |
| Kingston            | 7        | 7      | 13.21%  |
| Crucial             | 6        | 6      | 11.32%  |
| Intel               | 4        | 5      | 7.55%   |
| A-DATA Technology   | 4        | 4      | 7.55%   |
| WDC                 | 2        | 3      | 3.77%   |
| VMware              | 1        | 1      | 1.89%   |
| Verbatim            | 1        | 1      | 1.89%   |
| Smartbuy            | 1        | 1      | 1.89%   |
| SK Hynix            | 1        | 1      | 1.89%   |
| SanDisk             | 1        | 1      | 1.89%   |
| PNY                 | 1        | 1      | 1.89%   |
| PLEXTOR             | 1        | 1      | 1.89%   |
| Patriot             | 1        | 1      | 1.89%   |
| Micron Technology   | 1        | 1      | 1.89%   |
| LITEONIT            | 1        | 1      | 1.89%   |
| KingDian            | 1        | 1      | 1.89%   |
| Intenso             | 1        | 1      | 1.89%   |
| Corsair             | 1        | 1      | 1.89%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 50       | 209    | 45.87%  |
| SSD  | 40       | 74     | 36.7%   |
| NVMe | 19       | 26     | 17.43%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 64       | 283    | 77.11%  |
| NVMe | 19       | 26     | 22.89%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 44       | 79     | 41.51%  |
| 0.51-1.0   | 24       | 64     | 22.64%  |
| 3.01-4.0   | 10       | 34     | 9.43%   |
| 4.01-10.0  | 10       | 49     | 9.43%   |
| 1.01-2.0   | 9        | 20     | 8.49%   |
| 2.01-3.0   | 5        | 18     | 4.72%   |
| 10.01-20.0 | 4        | 19     | 3.77%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 14       | 19.44%  |
| 51-100         | 13       | 18.06%  |
| 251-500        | 10       | 13.89%  |
| 1-20           | 8        | 11.11%  |
| 501-1000       | 8        | 11.11%  |
| 21-50          | 7        | 9.72%   |
| 1001-2000      | 6        | 8.33%   |
| More than 3000 | 3        | 4.17%   |
| 2001-3000      | 2        | 2.78%   |
| Unknown        | 1        | 1.39%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 60       | 83.33%  |
| 21-50          | 4        | 5.56%   |
| More than 3000 | 2        | 2.78%   |
| 251-500        | 2        | 2.78%   |
| 51-100         | 2        | 2.78%   |
| 1001-2000      | 1        | 1.39%   |
| Unknown        | 1        | 1.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD5000AAKX-083CA0 500GB           | 1        | 1      | 5.56%   |
| WDC WD20EARX-00PASB0 2TB              | 1        | 1      | 5.56%   |
| WDC WD10EADS-00P8B0 1TB               | 1        | 1      | 5.56%   |
| Toshiba MQ02ABD100H 1TB               | 1        | 1      | 5.56%   |
| Toshiba MK3261GSYN 320GB              | 1        | 1      | 5.56%   |
| Seagate ST96812AS 64GB                | 1        | 4      | 5.56%   |
| Seagate ST9250827AS 250GB             | 1        | 1      | 5.56%   |
| Seagate ST500DM002-1BC142 500GB       | 1        | 1      | 5.56%   |
| Seagate ST380013AS 80GB               | 1        | 2      | 5.56%   |
| Seagate ST3250620AS 250GB             | 1        | 1      | 5.56%   |
| Seagate ST31000524AS 1TB              | 1        | 1      | 5.56%   |
| Samsung Electronics SSD 840 EVO 120GB | 1        | 1      | 5.56%   |
| PLEXTOR PX-128M5S 128GB               | 1        | 1      | 5.56%   |
| MAXTOR STM3160815AS 160GB             | 1        | 1      | 5.56%   |
| Hitachi HDS721010CLA332 1TB           | 1        | 1      | 5.56%   |
| HGST HDN726060ALE614 6TB              | 1        | 2      | 5.56%   |
| Crucial CT250MX200SSD1 250GB          | 1        | 1      | 5.56%   |
| Corsair Force 3 SSD 180GB             | 1        | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 10     | 31.25%  |
| WDC                 | 2        | 3      | 12.5%   |
| Toshiba             | 2        | 2      | 12.5%   |
| Samsung Electronics | 1        | 1      | 6.25%   |
| PLEXTOR             | 1        | 1      | 6.25%   |
| MAXTOR              | 1        | 1      | 6.25%   |
| Hitachi             | 1        | 1      | 6.25%   |
| HGST                | 1        | 2      | 6.25%   |
| Crucial             | 1        | 1      | 6.25%   |
| Corsair             | 1        | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 5        | 10     | 41.67%  |
| WDC     | 2        | 3      | 16.67%  |
| Toshiba | 2        | 2      | 16.67%  |
| MAXTOR  | 1        | 1      | 8.33%   |
| Hitachi | 1        | 1      | 8.33%   |
| HGST    | 1        | 2      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 10       | 19     | 71.43%  |
| SSD  | 4        | 4      | 28.57%  |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 63       | 280    | 78.75%  |
| Malfunc  | 14       | 23     | 17.5%   |
| Detected | 3        | 6      | 3.75%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 42       | 40%     |
| AMD                              | 25       | 23.81%  |
| Samsung Electronics              | 10       | 9.52%   |
| ASMedia Technology               | 7        | 6.67%   |
| Marvell Technology Group         | 4        | 3.81%   |
| Phison Electronics               | 3        | 2.86%   |
| VMware                           | 2        | 1.9%    |
| JMicron Technology               | 2        | 1.9%    |
| Broadcom / LSI                   | 2        | 1.9%    |
| ADATA Technology                 | 2        | 1.9%    |
| Silicon Motion                   | 1        | 0.95%   |
| Silicon Integrated Systems [SiS] | 1        | 0.95%   |
| Seagate Technology               | 1        | 0.95%   |
| Sandisk                          | 1        | 0.95%   |
| Lite-On Technology               | 1        | 0.95%   |
| Adaptec                          | 1        | 0.95%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 20       | 15.75%  |
| AMD 400 Series Chipset SATA Controller                                         | 8        | 6.3%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6        | 4.72%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5        | 3.94%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5        | 3.94%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 5        | 3.94%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4        | 3.15%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3        | 2.36%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3        | 2.36%   |
| Unknown                                                                        | 3        | 2.36%   |
| VMware SATA AHCI controller                                                    | 2        | 1.57%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2        | 1.57%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2        | 1.57%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                          | 2        | 1.57%   |
| JMicron JMB363 SATA/IDE Controller                                             | 2        | 1.57%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2        | 1.57%   |
| Intel SATA Controller [RAID mode]                                              | 2        | 1.57%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2        | 1.57%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 2        | 1.57%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2        | 1.57%   |
| AMD FCH IDE Controller                                                         | 2        | 1.57%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 2        | 1.57%   |
| VMware PVSCSI SCSI Controller                                                  | 1        | 0.79%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1        | 0.79%   |
| Silicon Integrated Systems [SiS] RAID bus controller 180 SATA/PATA  [SiS]      | 1        | 0.79%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 1        | 0.79%   |
| Seagate FireCuda 530 SSD                                                       | 1        | 0.79%   |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 1        | 0.79%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1        | 0.79%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1        | 0.79%   |
| Samsung NVMe SSD Controller 980                                                | 1        | 0.79%   |
| Phison E18 PCIe4 NVMe Controller                                               | 1        | 0.79%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 1        | 0.79%   |
| Marvell Group 88SE9123 PCIe SATA 6.0 Gb/s controller                           | 1        | 0.79%   |
| Lite-On M8Pe Series NVMe SSD                                                   | 1        | 0.79%   |
| Intel SSD 660P Series                                                          | 1        | 0.79%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1        | 0.79%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1        | 0.79%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1        | 0.79%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 1        | 0.79%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 1        | 0.79%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 1        | 0.79%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]           | 1        | 0.79%   |
| Intel 82801IB (ICH9) 4 port SATA Controller [AHCI mode]                        | 1        | 0.79%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]            | 1        | 0.79%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                   | 1        | 0.79%   |
| Intel 82801GR/GDH (ICH7R/ICH7DH) SATA Controller [RAID mode]                   | 1        | 0.79%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1        | 0.79%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                  | 1        | 0.79%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]    | 1        | 0.79%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]    | 1        | 0.79%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1        | 0.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1        | 0.79%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                            | 1        | 0.79%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                   | 1        | 0.79%   |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                 | 1        | 0.79%   |
| Broadcom / LSI MegaRAID SAS 2008 [Falcon]                                      | 1        | 0.79%   |
| AMD X399 Series Chipset SATA Controller                                        | 1        | 0.79%   |
| AMD X370 Series Chipset SATA Controller                                        | 1        | 0.79%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                       | 1        | 0.79%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 63       | 61.17%  |
| NVMe | 20       | 19.42%  |
| IDE  | 12       | 11.65%  |
| RAID | 4        | 3.88%   |
| SAS  | 3        | 2.91%   |
| SCSI | 1        | 0.97%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 43       | 59.72%  |
| AMD     | 25       | 34.72%  |
| Unknown | 2        | 2.78%   |
| Unknown | 1        | 1.39%   |
| ARM     | 1        | 1.39%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Intel Core i7-6700 CPU @ 3.40GHz              | 3        | 4.17%   |
| AMD Ryzen 7 2700 Eight-Core Processor         | 3        | 4.17%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2        | 2.78%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 2        | 2.78%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 2        | 2.78%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 2        | 2.78%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 2        | 2.78%   |
|                                               | 2        | 2.78%   |
| Unknown Implementer Processor r0p0            | 1        | 1.39%   |
| Intel Xeon CPU X3440 @ 2.53GHz                | 1        | 1.39%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz           | 1        | 1.39%   |
| Intel Xeon CPU E3-1275 v5 @ 3.60GHz           | 1        | 1.39%   |
| Intel Pentium II                              | 1        | 1.39%   |
| Intel Pentium CPU G630T @ 2.30GHz             | 1        | 1.39%   |
| Intel Pentium CPU G3420 @ 3.20GHz             | 1        | 1.39%   |
| Intel Pentium CPU G3220 @ 3.00GHz             | 1        | 1.39%   |
| Intel Pentium CPU G2020 @ 2.90GHz             | 1        | 1.39%   |
| Intel Pentium 4 CPU                           | 1        | 1.39%   |
| Intel Pentium 4                               | 1        | 1.39%   |
| Intel Core i9-9900X CPU @ 3.50GHz             | 1        | 1.39%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 1        | 1.39%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 1        | 1.39%   |
| Intel Core i7-4790S CPU @ 3.20GHz             | 1        | 1.39%   |
| Intel Core i7-4770T CPU @ 2.50GHz             | 1        | 1.39%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 1        | 1.39%   |
| Intel Core i7-3610QE CPU @ 2.30GHz            | 1        | 1.39%   |
| Intel Core i7-2600 CPU                        | 1        | 1.39%   |
| Intel Core i7-10700K CPU @ 3.80GHz            | 1        | 1.39%   |
| Intel Core i7 CPU                             | 1        | 1.39%   |
| Intel Core i5-9600K CPU @ 3.70GHz             | 1        | 1.39%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 1        | 1.39%   |
| Intel Core i5-4690 CPU @ 3.50GHz              | 1        | 1.39%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 1        | 1.39%   |
| Intel Core i5-4440 CPU @ 3.10GHz              | 1        | 1.39%   |
| Intel Core i5 CPU 650 @ 3.20GHz               | 1        | 1.39%   |
| Intel Core i3 CPU 530 @ 2.93GHz               | 1        | 1.39%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 1        | 1.39%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz          | 1        | 1.39%   |
| Intel Core 2 CPU 6300 @ 1.86GHz               | 1        | 1.39%   |
| Intel Celeron J4105 CPU @ 1.50GHz             | 1        | 1.39%   |
| Intel Celeron CPU J3455 @ 1.50GHz             | 1        | 1.39%   |
| Intel Celeron CPU G1610T @ 2.30GHz            | 1        | 1.39%   |
| Intel Celeron CPU G1101 @ 2.27GHz             | 1        | 1.39%   |
| Intel Celeron CPU 847 @ 1.10GHz               | 1        | 1.39%   |
| Intel Atom CPU E3845 @ 1.91GHz                | 1        | 1.39%   |
| Intel Atom CPU E3827 @ 1.74GHz                | 1        | 1.39%   |
| Intel Atom CPU D510 @ 1.66GHz                 | 1        | 1.39%   |
| ARM Cortex-A72 r0p3                           | 1        | 1.39%   |
| AMD Turion II Neo N40L Dual-Core Processor    | 1        | 1.39%   |
| AMD Ryzen Threadripper 1900X 8-Core Processor | 1        | 1.39%   |
| AMD Ryzen 9 3950X 16-Core Processor           | 1        | 1.39%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 1        | 1.39%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 1        | 1.39%   |
| AMD Ryzen 7 1700X Eight-Core Processor        | 1        | 1.39%   |
| AMD Ryzen 7 1700 Eight-Core Processor         | 1        | 1.39%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 1        | 1.39%   |
| AMD Ryzen 5 2600X Six-Core Processor          | 1        | 1.39%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics   | 1        | 1.39%   |
| AMD FX-8350 Eight-Core Processor              | 1        | 1.39%   |
| AMD Athlon X4 750K Quad Core Processor        | 1        | 1.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i7          | 12       | 16.67%  |
| Intel Core i5          | 8        | 11.11%  |
| AMD Ryzen 9            | 7        | 9.72%   |
| AMD Ryzen 7            | 7        | 9.72%   |
| Intel Pentium          | 5        | 6.94%   |
| Intel Celeron          | 5        | 6.94%   |
| Other                  | 3        | 4.17%   |
| Intel Xeon             | 3        | 4.17%   |
| Intel Atom             | 3        | 4.17%   |
| AMD Ryzen 5            | 3        | 4.17%   |
| Intel Pentium 4        | 2        | 2.78%   |
| AMD Ryzen 3            | 2        | 2.78%   |
| Intel Core i9          | 1        | 1.39%   |
| Intel Core i3          | 1        | 1.39%   |
| Intel Core 2 Quad      | 1        | 1.39%   |
| Intel Core 2 Duo       | 1        | 1.39%   |
| Intel Core 2           | 1        | 1.39%   |
| ARM Cortex             | 1        | 1.39%   |
| AMD Turion II Neo      | 1        | 1.39%   |
| AMD Ryzen Threadripper | 1        | 1.39%   |
| AMD FX                 | 1        | 1.39%   |
| AMD Athlon X4          | 1        | 1.39%   |
| AMD Athlon             | 1        | 1.39%   |
| AMD A10                | 1        | 1.39%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 26       | 36.11%  |
| 2       | 12       | 16.67%  |
| 16      | 8        | 11.11%  |
| Unknown | 7        | 9.72%   |
| 24      | 4        | 5.56%   |
| 32      | 3        | 4.17%   |
| 12      | 3        | 4.17%   |
| 8       | 3        | 4.17%   |
| 6       | 3        | 4.17%   |
| 1       | 2        | 2.78%   |
| 10      | 1        | 1.39%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 68       | 94.44%  |
| 2       | 2        | 2.78%   |
| Unknown | 2        | 2.78%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 42       | 58.33%  |
| 2       | 21       | 29.17%  |
| Unknown | 9        | 12.5%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Zen+          | 7        | 9.72%   |
| Skylake       | 7        | 9.72%   |
| Haswell       | 7        | 9.72%   |
| Zen 3         | 5        | 6.94%   |
| IvyBridge     | 5        | 6.94%   |
| Zen 2         | 4        | 5.56%   |
| Zen           | 4        | 5.56%   |
| Westmere      | 4        | 5.56%   |
| KabyLake      | 4        | 5.56%   |
| Unknown       | 4        | 5.56%   |
| SandyBridge   | 3        | 4.17%   |
| Piledriver    | 3        | 4.17%   |
| Silvermont    | 2        | 2.78%   |
| NetBurst      | 2        | 2.78%   |
| Core          | 2        | 2.78%   |
| Penryn        | 1        | 1.39%   |
| P6            | 1        | 1.39%   |
| Nehalem       | 1        | 1.39%   |
| K10           | 1        | 1.39%   |
| Jaguar        | 1        | 1.39%   |
| Goldmont plus | 1        | 1.39%   |
| Goldmont      | 1        | 1.39%   |
| CometLake     | 1        | 1.39%   |
| Bonnell       | 1        | 1.39%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Nvidia                               | 26       | 34.67%  |
| Intel                                | 24       | 32%     |
| AMD                                  | 19       | 25.33%  |
| Matrox Electronics Systems           | 3        | 4%      |
| VMware                               | 2        | 2.67%   |
| NVidia / SGS Thomson (Joint Venture) | 1        | 1.33%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 7        | 9.21%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 6.58%   |
| Intel HD Graphics 530                                                       | 5        | 6.58%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 3.95%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 2.63%   |
| Nvidia GF119 [GeForce GT 610]                                               | 2        | 2.63%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)           | 2        | 2.63%   |
| Intel UHD Graphics 620                                                      | 2        | 2.63%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 2.63%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 2        | 2.63%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 2        | 2.63%   |
| Unknown                                                                     | 2        | 2.63%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.32%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 1.32%   |
| Nvidia GT218 [NVS 300]                                                      | 1        | 1.32%   |
| Nvidia GP107GL [Quadro P600]                                                | 1        | 1.32%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 1.32%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 1.32%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 1.32%   |
| Nvidia GF119 [GeForce GT 520]                                               | 1        | 1.32%   |
| Nvidia GF110 [GeForce GTX 580]                                              | 1        | 1.32%   |
| Nvidia GF100GL [Quadro 4000]                                                | 1        | 1.32%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 1.32%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 1        | 1.32%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 1        | 1.32%   |
| Nvidia G96C [GeForce 9400 GT]                                               | 1        | 1.32%   |
| Nvidia G92 [GeForce GT 330]                                                 | 1        | 1.32%   |
| Nvidia G86 [GeForce 8500 GT]                                                | 1        | 1.32%   |
| Nvidia G84GL [Quadro FX 1700]                                               | 1        | 1.32%   |
| Nvidia G72 [GeForce 7300 LE]                                                | 1        | 1.32%   |
| Nvidia G72 [GeForce 7200 GS / 7300 SE]                                      | 1        | 1.32%   |
| NVidia / SGS Thomson (Joint Venture) Riva128                                | 1        | 1.32%   |
| Matrox Electronics Systems MGA G200EH                                       | 1        | 1.32%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 1.32%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 1.32%   |
| Intel HD Graphics P530                                                      | 1        | 1.32%   |
| Intel HD Graphics 500                                                       | 1        | 1.32%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 1.32%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller     | 1        | 1.32%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 1        | 1.32%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.32%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 1        | 1.32%   |
| AMD Trinity [Radeon HD 7660D]                                               | 1        | 1.32%   |
| AMD RV280 [Radeon 9200 PRO] (Secondary)                                     | 1        | 1.32%   |
| AMD RV280 [Radeon 9200 PRO / 9250]                                          | 1        | 1.32%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                   | 1        | 1.32%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 1.32%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]           | 1        | 1.32%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT / 6800M]                                | 1        | 1.32%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 1        | 1.32%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 1.32%   |
| AMD Cezanne                                                                 | 1        | 1.32%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| 1 x Nvidia                               | 23       | 31.94%  |
| 1 x Intel                                | 19       | 26.39%  |
| 1 x AMD                                  | 16       | 22.22%  |
| 1 x Matrox                               | 3        | 4.17%   |
| Other                                    | 2        | 2.78%   |
| 1 x VMware                               | 2        | 2.78%   |
| Intel + Nvidia                           | 2        | 2.78%   |
| Intel + AMD                              | 2        | 2.78%   |
| 2 x Intel                                | 1        | 1.39%   |
| 2 x AMD                                  | 1        | 1.39%   |
| 1 x NVidia / SGS Thomson (Joint Venture) | 1        | 1.39%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 55       | 76.39%  |
| Proprietary | 15       | 20.83%  |
| Unknown     | 2        | 2.78%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 48       | 66.67%  |
| 7.01-8.0   | 6        | 8.33%   |
| 3.01-4.0   | 6        | 8.33%   |
| 1.01-2.0   | 6        | 8.33%   |
| 5.01-6.0   | 2        | 2.78%   |
| 0.51-1.0   | 2        | 2.78%   |
| 8.01-16.0  | 1        | 1.39%   |
| 0.01-0.5   | 1        | 1.39%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 10       | 23.26%  |
| Goldstar             | 8        | 18.6%   |
| Samsung Electronics  | 5        | 11.63%  |
| Ancor Communications | 4        | 9.3%    |
| Iiyama               | 2        | 4.65%   |
| BenQ                 | 2        | 4.65%   |
| AOC                  | 2        | 4.65%   |
| Acer                 | 2        | 4.65%   |
| Sceptre Tech         | 1        | 2.33%   |
| Philips              | 1        | 2.33%   |
| Panasonic            | 1        | 2.33%   |
| LG Electronics       | 1        | 2.33%   |
| Hewlett-Packard      | 1        | 2.33%   |
| Eizo                 | 1        | 2.33%   |
| CKL                  | 1        | 2.33%   |
| ASUSTek Computer     | 1        | 2.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Dell U2412M DELA07B 1920x1200 520x320mm 24.0-inch                      | 2        | 4.44%   |
| Sceptre Tech Sceptre E20 SPT080D 1600x900 410x280mm 19.5-inch          | 1        | 2.22%   |
| Samsung Electronics SyncMaster SAM027D 1680x1050 430x270mm 20.0-inch   | 1        | 2.22%   |
| Samsung Electronics SyncMaster SAM0236 2560x1600 640x400mm 29.7-inch   | 1        | 2.22%   |
| Samsung Electronics SyncMaster SAM01BB 1280x1024 380x300mm 19.1-inch   | 1        | 2.22%   |
| Samsung Electronics S24E510C SAM0C61 1920x1080 520x300mm 23.6-inch     | 1        | 2.22%   |
| Samsung Electronics LCD Monitor SAM0D4F 1920x1080 1020x570mm 46.0-inch | 1        | 2.22%   |
| Philips PHL 233V5 PHLC0D0 1920x1080 510x290mm 23.1-inch                | 1        | 2.22%   |
| Philips LCD Monitor PHLC050 1366x768 410x230mm 18.5-inch               | 1        | 2.22%   |
| Panasonic TV MEIC136 1280x720 698x392mm 31.5-inch                      | 1        | 2.22%   |
| LG Electronics LCD Monitor LG Ultra HD 3840x2160                       | 1        | 2.22%   |
| Iiyama PLX2483H IVM6114 1920x1080 530x300mm 24.0-inch                  | 1        | 2.22%   |
| Iiyama PL2209HD IVM560B 1920x1080 480x270mm 21.7-inch                  | 1        | 2.22%   |
| Hewlett-Packard Z24nf HWP3209 1920x1080 530x300mm 24.0-inch            | 1        | 2.22%   |
| Goldstar W2246 GSM5784 1920x1080 480x270mm 21.7-inch                   | 1        | 2.22%   |
| Goldstar W2052 GSM4E88 1680x1050 470x300mm 22.0-inch                   | 1        | 2.22%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch             | 1        | 2.22%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch             | 1        | 2.22%   |
| Goldstar LG TV GSMC0A0 3840x2160                                       | 1        | 2.22%   |
| Goldstar LG FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch              | 1        | 2.22%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 600x340mm 27.2-inch                 | 1        | 2.22%   |
| Goldstar 22EA53 GSM59A4 1920x1080 480x270mm 21.7-inch                  | 1        | 2.22%   |
| Eizo CS2420 ENC2741 1920x1200 520x330mm 24.2-inch                      | 1        | 2.22%   |
| Dell U3011 DEL4064 1920x1200 640x400mm 29.7-inch                       | 1        | 2.22%   |
| Dell SE2717H/HX DELD0A1 1920x1080 600x340mm 27.2-inch                  | 1        | 2.22%   |
| Dell S2340M DELD05A 1920x1080 510x290mm 23.1-inch                      | 1        | 2.22%   |
| Dell P2715Q DEL40BD 3840x2160 600x340mm 27.2-inch                      | 1        | 2.22%   |
| Dell P2415Q DELA0BE 3840x2160 530x300mm 24.0-inch                      | 1        | 2.22%   |
| Dell LCD Monitor U3011 2560x1600                                       | 1        | 2.22%   |
| Dell LCD Monitor DELD110 2560x1440 700x400mm 31.7-inch                 | 1        | 2.22%   |
| Dell E2417H DELA0E1 1920x1080 530x300mm 24.0-inch                      | 1        | 2.22%   |
| Dell E1916H DELF065 1366x768 410x230mm 18.5-inch                       | 1        | 2.22%   |
| CKL LCD Monitor CKL0001 1920x1200 1150x650mm 52.0-inch                 | 1        | 2.22%   |
| BenQ GW2270 BNQ78DB 1920x1080 480x270mm 21.7-inch                      | 1        | 2.22%   |
| BenQ BL2411 BNQ8011 1920x1200 520x320mm 24.0-inch                      | 1        | 2.22%   |
| ASUSTek Computer VP247 AUS24CA 1920x1080 520x290mm 23.4-inch           | 1        | 2.22%   |
| AOC Q3277 AOC3277 2560x1440 710x400mm 32.1-inch                        | 1        | 2.22%   |
| AOC 24G2W1G4 AOC2402 1920x1080 530x300mm 24.0-inch                     | 1        | 2.22%   |
| Ancor Communications VG248 ACI24A5 1920x1080 530x300mm 24.0-inch       | 1        | 2.22%   |
| Ancor Communications LCD Monitor PA249 1920x1200                       | 1        | 2.22%   |
| Ancor Communications ASUS VN247 ACI24C3 1920x1080 520x290mm 23.4-inch  | 1        | 2.22%   |
| Ancor Communications ASUS MX239 ACI23C2 1920x1080 530x310mm 24.2-inch  | 1        | 2.22%   |
| Acer K202HQL ACR03E0 1600x900 430x240mm 19.4-inch                      | 1        | 2.22%   |
| Acer EB321HQU ACR0507 2560x1440 700x390mm 31.5-inch                    | 1        | 2.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 16       | 38.1%   |
| 3840x2160 (4K)     | 7        | 16.67%  |
| 1920x1200 (WUXGA)  | 7        | 16.67%  |
| 2560x1440 (QHD)    | 3        | 7.14%   |
| 2560x1600          | 2        | 4.76%   |
| 1680x1050 (WSXGA+) | 2        | 4.76%   |
| 1366x768 (WXGA)    | 2        | 4.76%   |
| 1600x900 (HD+)     | 1        | 2.38%   |
| 1280x720 (HD)      | 1        | 2.38%   |
| 1280x1024 (SXGA)   | 1        | 2.38%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 9        | 21.43%  |
| 27      | 5        | 11.9%   |
| 23      | 5        | 11.9%   |
| 21      | 5        | 11.9%   |
| Unknown | 4        | 9.52%   |
| 31      | 3        | 7.14%   |
| 29      | 2        | 4.76%   |
| 19      | 2        | 4.76%   |
| 18      | 2        | 4.76%   |
| 52      | 1        | 2.38%   |
| 46      | 1        | 2.38%   |
| 32      | 1        | 2.38%   |
| 22      | 1        | 2.38%   |
| 20      | 1        | 2.38%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 17       | 42.5%   |
| 401-500     | 10       | 25%     |
| 601-700     | 5        | 12.5%   |
| Unknown     | 4        | 10%     |
| 1001-1500   | 2        | 5%      |
| 701-800     | 1        | 2.5%    |
| 351-400     | 1        | 2.5%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 27       | 69.23%  |
| 16/10   | 7        | 17.95%  |
| Unknown | 3        | 7.69%   |
| 5/4     | 1        | 2.56%   |
| 3/2     | 1        | 2.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 15       | 35.71%  |
| 351-500        | 6        | 14.29%  |
| 301-350        | 5        | 11.9%   |
| 251-300        | 5        | 11.9%   |
| Unknown        | 4        | 9.52%   |
| 151-200        | 3        | 7.14%   |
| 141-150        | 2        | 4.76%   |
| More than 1000 | 1        | 2.38%   |
| 501-1000       | 1        | 2.38%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 22       | 55%     |
| 101-120 | 7        | 17.5%   |
| 161-240 | 4        | 10%     |
| Unknown | 4        | 10%     |
| 1-50    | 3        | 7.5%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 37       | 50.68%  |
| 1     | 27       | 36.99%  |
| 2     | 8        | 10.96%  |
| 3     | 1        | 1.37%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 36       | 37.89%  |
| Intel                             | 36       | 37.89%  |
| Qualcomm Atheros                  | 7        | 7.37%   |
| Broadcom                          | 4        | 4.21%   |
| Mellanox Technologies             | 2        | 2.11%   |
| Sundance Technology Inc / IC Plus | 1        | 1.05%   |
| Silicon Integrated Systems [SiS]  | 1        | 1.05%   |
| Samsung Electronics               | 1        | 1.05%   |
| Ralink Technology                 | 1        | 1.05%   |
| Ralink                            | 1        | 1.05%   |
| Qualcomm                          | 1        | 1.05%   |
| Marvell Technology Group          | 1        | 1.05%   |
| IMC Networks                      | 1        | 1.05%   |
| Edimax Technology                 | 1        | 1.05%   |
| ADMtek                            | 1        | 1.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 32       | 29.09%  |
| Intel I211 Gigabit Network Connection                                         | 9        | 8.18%   |
| Intel Wi-Fi 6 AX200                                                           | 6        | 5.45%   |
| Intel 82574L Gigabit Network Connection                                       | 6        | 5.45%   |
| Intel Ethernet Connection (2) I219-V                                          | 4        | 3.64%   |
| Intel Ethernet Connection (2) I219-LM                                         | 4        | 3.64%   |
| Realtek RTL8125 2.5GbE Controller                                             | 3        | 2.73%   |
| Intel Wireless-AC 9260                                                        | 3        | 2.73%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 2        | 1.82%   |
| Mellanox MT27500 Family [ConnectX-3]                                          | 2        | 1.82%   |
| Intel I210 Gigabit Network Connection                                         | 2        | 1.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2        | 1.82%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2        | 1.82%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 2        | 1.82%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY    | 1        | 0.91%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                     | 1        | 0.91%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                   | 1        | 0.91%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 1        | 0.91%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 1        | 0.91%   |
| Realtek Realtek Bluetooth Adapter                                             | 1        | 0.91%   |
| Realtek Realtek 8811CU Wireless LAN 802.11ac USB NIC                          | 1        | 0.91%   |
| Ralink RT5370 Wireless Adapter                                                | 1        | 0.91%   |
| Ralink RT2500 Wireless 802.11bg                                               | 1        | 0.91%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1        | 0.91%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 1        | 0.91%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1        | 0.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 1        | 0.91%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 1        | 0.91%   |
| Qualcomm ALCATEL Composite RNDIS Interface                                    | 1        | 0.91%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1        | 0.91%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                             | 1        | 0.91%   |
| Intel Wireless 7265                                                           | 1        | 0.91%   |
| Intel Wireless 3160                                                           | 1        | 0.91%   |
| Intel I350 Gigabit Network Connection                                         | 1        | 0.91%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 1        | 0.91%   |
| Intel Ethernet Controller I225-V                                              | 1        | 0.91%   |
| Intel Ethernet Connection (7) I219-V                                          | 1        | 0.91%   |
| Intel Ethernet Connection (2) I218-V                                          | 1        | 0.91%   |
| Intel 82573L Gigabit Ethernet Controller                                      | 1        | 0.91%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 1        | 0.91%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]                          | 1        | 0.91%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                | 1        | 0.91%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 1        | 0.91%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                   | 1        | 0.91%   |
| ADMtek NC100 Network Everywhere Fast Ethernet 10/100                          | 1        | 0.91%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 12       | 46.15%  |
| Qualcomm Atheros      | 5        | 19.23%  |
| Realtek Semiconductor | 4        | 15.38%  |
| Ralink Technology     | 1        | 3.85%   |
| Ralink                | 1        | 3.85%   |
| IMC Networks          | 1        | 3.85%   |
| Edimax Technology     | 1        | 3.85%   |
| Broadcom              | 1        | 3.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 6        | 23.08%  |
| Intel Wireless-AC 9260                                         | 3        | 11.54%  |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 2        | 7.69%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1        | 3.85%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1        | 3.85%   |
| Realtek Realtek Bluetooth Adapter                              | 1        | 3.85%   |
| Realtek Realtek 8811CU Wireless LAN 802.11ac USB NIC           | 1        | 3.85%   |
| Ralink RT5370 Wireless Adapter                                 | 1        | 3.85%   |
| Ralink RT2500 Wireless 802.11bg                                | 1        | 3.85%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1        | 3.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1        | 3.85%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 1        | 3.85%   |
| Intel Wireless 7265                                            | 1        | 3.85%   |
| Intel Wireless 3160                                            | 1        | 3.85%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 1        | 3.85%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]           | 1        | 3.85%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 1        | 3.85%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 1        | 3.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 33       | 43.42%  |
| Intel                             | 32       | 42.11%  |
| Broadcom                          | 3        | 3.95%   |
| Qualcomm Atheros                  | 2        | 2.63%   |
| Sundance Technology Inc / IC Plus | 1        | 1.32%   |
| Silicon Integrated Systems [SiS]  | 1        | 1.32%   |
| Samsung Electronics               | 1        | 1.32%   |
| Qualcomm                          | 1        | 1.32%   |
| Marvell Technology Group          | 1        | 1.32%   |
| ADMtek                            | 1        | 1.32%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 32       | 40%     |
| Intel I211 Gigabit Network Connection                                         | 9        | 11.25%  |
| Intel 82574L Gigabit Network Connection                                       | 6        | 7.5%    |
| Intel Ethernet Connection (2) I219-V                                          | 4        | 5%      |
| Intel Ethernet Connection (2) I219-LM                                         | 4        | 5%      |
| Intel I210 Gigabit Network Connection                                         | 2        | 2.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2        | 2.5%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2        | 2.5%    |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 2        | 2.5%    |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY    | 1        | 1.25%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                     | 1        | 1.25%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                   | 1        | 1.25%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 1.25%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1        | 1.25%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 1        | 1.25%   |
| Qualcomm ALCATEL Composite RNDIS Interface                                    | 1        | 1.25%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1        | 1.25%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                             | 1        | 1.25%   |
| Intel I350 Gigabit Network Connection                                         | 1        | 1.25%   |
| Intel Ethernet Controller I225-V                                              | 1        | 1.25%   |
| Intel Ethernet Connection (7) I219-V                                          | 1        | 1.25%   |
| Intel Ethernet Connection (2) I218-V                                          | 1        | 1.25%   |
| Intel 82573L Gigabit Ethernet Controller                                      | 1        | 1.25%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 1        | 1.25%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 1        | 1.25%   |
| ADMtek NC100 Network Everywhere Fast Ethernet 10/100                          | 1        | 1.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 69       | 70.41%  |
| WiFi     | 25       | 25.51%  |
| Unknown  | 4        | 4.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 65       | 83.33%  |
| WiFi     | 13       | 16.67%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 35       | 48.61%  |
| 2     | 26       | 36.11%  |
| 3     | 5        | 6.94%   |
| 4     | 4        | 5.56%   |
| 0     | 2        | 2.78%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 57       | 78.08%  |
| Yes  | 16       | 21.92%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 13       | 72.22%  |
| Cambridge Silicon Radio | 2        | 11.11%  |
| VMware                  | 1        | 5.56%   |
| Broadcom                | 1        | 5.56%   |
| Apple                   | 1        | 5.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 6        | 33.33%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4        | 22.22%  |
| Intel Bluetooth wireless interface                  | 2        | 11.11%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 11.11%  |
| VMware Virtual Bluetooth Adapter                    | 1        | 5.56%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 5.56%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 5.56%   |
| Apple Bluetooth Host Controller                     | 1        | 5.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 34       | 37.36%  |
| AMD                                  | 26       | 28.57%  |
| Nvidia                               | 19       | 20.88%  |
| Creative Labs                        | 2        | 2.2%    |
| C-Media Electronics                  | 2        | 2.2%    |
| VMware                               | 1        | 1.1%    |
| Thesycon Systemsoftware & Consulting | 1        | 1.1%    |
| Texas Instruments                    | 1        | 1.1%    |
| SteelSeries ApS                      | 1        | 1.1%    |
| Silicon Integrated Systems [SiS]     | 1        | 1.1%    |
| Ensoniq                              | 1        | 1.1%    |
| Corsair                              | 1        | 1.1%    |
| BEHRINGER International              | 1        | 1.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                                     | Desktops | Percent |
|-----------------------------------------------------------------------------------------------------------|----------|---------|
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                                       | 8        | 7.48%   |
| AMD Starship/Matisse HD Audio Controller                                                                  | 7        | 6.54%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                                | 7        | 6.54%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                                       | 5        | 4.67%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                           | 5        | 4.67%   |
| AMD Family 17h/19h HD Audio Controller                                                                    | 4        | 3.74%   |
| Nvidia High Definition Audio Controller                                                                   | 3        | 2.8%    |
| Nvidia GP108 High Definition Audio Controller                                                             | 3        | 2.8%    |
| Nvidia GF119 HDMI Audio Controller                                                                        | 3        | 2.8%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                          | 3        | 2.8%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                                       | 3        | 2.8%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                                  | 3        | 2.8%    |
| AMD FCH Azalia Controller                                                                                 | 3        | 2.8%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                              | 3        | 2.8%    |
| Nvidia GP106 High Definition Audio Controller                                                             | 2        | 1.87%   |
| Intel Sunrise Point-LP HD Audio                                                                           | 2        | 1.87%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                                | 2        | 1.87%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                         | 2        | 1.87%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                          | 2        | 1.87%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                                | 2        | 1.87%   |
| Intel 200 Series PCH HD Audio                                                                             | 2        | 1.87%   |
| AMD Navi 21 HDMI Audio [Radeon RX 6800/6800 XT / 6900 XT]                                                 | 2        | 1.87%   |
| VMware HD Audio Controller                                                                                | 1        | 0.93%   |
| Thesycon Systemsoftware & Consulting Topping DX3 Pro Audio Control                                        | 1        | 0.93%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                         | 1        | 0.93%   |
| SteelSeries ApS Arctis Pro Wireless Arctis Pro Wireless Chat Arctis Pro Wireless Game Arctis Pro Wireless | 1        | 0.93%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                           | 1        | 0.93%   |
| Nvidia TU116 High Definition Audio Controller                                                             | 1        | 0.93%   |
| Nvidia TU104 HD Audio Controller                                                                          | 1        | 0.93%   |
| Nvidia GP107GL High Definition Audio Controller                                                           | 1        | 0.93%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                                     | 1        | 0.93%   |
| Nvidia GF110 High Definition Audio Controller                                                             | 1        | 0.93%   |
| Nvidia GF100 High Definition Audio Controller                                                             | 1        | 0.93%   |
| Nvidia GA104 High Definition Audio Controller                                                             | 1        | 0.93%   |
| Nvidia GA102 High Definition Audio Controller                                                             | 1        | 0.93%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                                   | 1        | 0.93%   |
| Intel Comet Lake PCH cAVS                                                                                 | 1        | 0.93%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                              | 1        | 0.93%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                         | 1        | 0.93%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                            | 1        | 0.93%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                            | 1        | 0.93%   |
| Ensoniq 5880B / Creative Labs CT5880                                                                      | 1        | 0.93%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                                             | 1        | 0.93%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]                                 | 1        | 0.93%   |
| Corsair Corsair VOID PRO Wireless Gaming Headset                                                          | 1        | 0.93%   |
| C-Media Electronics CM108 Audio Controller                                                                | 1        | 0.93%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                         | 1        | 0.93%   |
| BEHRINGER International UMC202HD 192k                                                                     | 1        | 0.93%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                                                | 1        | 0.93%   |
| AMD Trinity HDMI Audio Controller                                                                         | 1        | 0.93%   |
| AMD Renoir Radeon High Definition Audio Controller                                                        | 1        | 0.93%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                                       | 1        | 0.93%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                                   | 1        | 0.93%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 15       | 22.73%  |
| Kingston            | 10       | 15.15%  |
| Corsair             | 10       | 15.15%  |
| Crucial             | 9        | 13.64%  |
| Samsung Electronics | 4        | 6.06%   |
| Micron Technology   | 4        | 6.06%   |
| G.Skill             | 4        | 6.06%   |
| Team                | 2        | 3.03%   |
| SK Hynix            | 2        | 3.03%   |
| A-DATA Technology   | 2        | 3.03%   |
| Silicon Power       | 1        | 1.52%   |
| GeIL                | 1        | 1.52%   |
| AMD                 | 1        | 1.52%   |
| Unknown             | 1        | 1.52%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM 1333MT/s                     | 2        | 2.82%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s      | 2        | 2.82%   |
| Crucial RAM CT8G4SFS824A.C8BD1 8GB SODIMM DDR4 2400MT/s  | 2        | 2.82%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s    | 2        | 2.82%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                | 1        | 1.41%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                | 1        | 1.41%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                 | 1        | 1.41%   |
| Unknown RAM Module 4GB DIMM 400MT/s                      | 1        | 1.41%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 1        | 1.41%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s               | 1        | 1.41%   |
| Unknown RAM Module 2GB DIMM SDRAM                        | 1        | 1.41%   |
| Unknown RAM Module 2GB DIMM DDR3 1332MT/s                | 1        | 1.41%   |
| Unknown RAM Module 2GB DIMM DDR 800MT/s                  | 1        | 1.41%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                 | 1        | 1.41%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                 | 1        | 1.41%   |
| Unknown RAM Module 1GB DIMM 400MT/s                      | 1        | 1.41%   |
| Unknown RAM Module 16GB DIMM DDR4 2133MT/s               | 1        | 1.41%   |
| Unknown RAM 2G-08-10-12-1333 2GB DIMM DDR3 1333MT/s      | 1        | 1.41%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s   | 1        | 1.41%   |
| SK Hynix RAM HMA82GU6AFR8N-UH 16GB DIMM DDR4 2400MT/s    | 1        | 1.41%   |
| Silicon Power RAM DCLT4GN128O 4GB DIMM DDR3 1333MT/s     | 1        | 1.41%   |
| Samsung RAM Module 16GB DIMM DDR3 1600MT/s               | 1        | 1.41%   |
| Samsung RAM M391A4G43MB1-CTD 32GB DIMM DDR4 3200MT/s     | 1        | 1.41%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 1333MT/s      | 1        | 1.41%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1333MT/s      | 1        | 1.41%   |
| Samsung RAM M378A1K43BB1-CPB 8GB DIMM DDR4 3000MT/s      | 1        | 1.41%   |
| Micron RAM 8ATF51264AZ-2G1A2 4GB DIMM DDR4 2133MT/s      | 1        | 1.41%   |
| Micron RAM 18ASF2G72AZ-2G3B1 16GB DIMM DDR4 2400MT/s     | 1        | 1.41%   |
| Micron RAM 16JTF1G64AZ-1G6D1 8GB DIMM DDR3 1600MT/s      | 1        | 1.41%   |
| Micron RAM 16HTF12864AY-53ED4 1GB DIMM DDR 533MT/s       | 1        | 1.41%   |
| Kingston RAM KHX3600C17D4/16GX 16GB DIMM DDR4 2400MT/s   | 1        | 1.41%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 2667MT/s        | 1        | 1.41%   |
| Kingston RAM KHX2400C15/16G 16GB DIMM DDR4 2400MT/s      | 1        | 1.41%   |
| Kingston RAM KHX16LC9/8GX 8GB DIMM DDR3 1600MT/s         | 1        | 1.41%   |
| Kingston RAM KHX1600C9D3/8GX 8GB DIMM DDR3 1333MT/s      | 1        | 1.41%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s      | 1        | 1.41%   |
| Kingston RAM 99U5471-039.A 8GB DIMM DDR3 1600MT/s        | 1        | 1.41%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s  | 1        | 1.41%   |
| Kingston RAM 99P5471-041.A00LF 8GB DIMM DDR3 1600MT/s    | 1        | 1.41%   |
| Kingston RAM 9965745-002.A00G 16GB DIMM DDR4 3000MT/s    | 1        | 1.41%   |
| Kingston RAM 9905471-074.A 8GB DIMM DDR3 1600MT/s        | 1        | 1.41%   |
| GeIL RAM CL9-9-9 D3-1600 8GB DIMM DDR3 800MT/s           | 1        | 1.41%   |
| G.Skill RAM F4-3200C16-32GVK 32GB DIMM DDR4 2666MT/s     | 1        | 1.41%   |
| G.Skill RAM F4-3200C16-16GTZSW 16GB DIMM DDR4 2133MT/s   | 1        | 1.41%   |
| G.Skill RAM F4-3000C16-16GISB 16GB DIMM DDR4 2133MT/s    | 1        | 1.41%   |
| G.Skill RAM F4-2666C19-16GIS 16GB DIMM DDR4 2133MT/s     | 1        | 1.41%   |
| G.Skill RAM F4-2400C15-8GVR 8GB DIMM DDR4 2133MT/s       | 1        | 1.41%   |
| G.Skill RAM F3-12800CL7-2GBRM 2GB DIMM DDR3 1600MT/s     | 1        | 1.41%   |
| Crucial RAM CT8G4DFS824A.M8FE 8GB DIMM DDR4 2933MT/s     | 1        | 1.41%   |
| Crucial RAM CT25664BF160B.M8FM 2GB SODIMM DDR3 1333MT/s  | 1        | 1.41%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s    | 1        | 1.41%   |
| Crucial RAM BLT16G4D30AETA.K16FB 16GB DIMM DDR4 3000MT/s | 1        | 1.41%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1600MT/s    | 1        | 1.41%   |
| Crucial RAM BLS16G4D26BFSC.16FBD 16GB DIMM DDR4 2667MT/s | 1        | 1.41%   |
| Crucial RAM BL32G36C16U4B.M16FB1 32GB DIMM DDR4 3600MT/s | 1        | 1.41%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s   | 1        | 1.41%   |
| Corsair RAM CMSO8GX4M1A2133C15 8GB SODIMM DDR4 2133MT/s  | 1        | 1.41%   |
| Corsair RAM CML16GX3M2A1600C9 8GB DIMM DDR3 1600MT/s     | 1        | 1.41%   |
| Corsair RAM CML16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s    | 1        | 1.41%   |
| Corsair RAM CMK64GX4M2D3600C18 32GB DIMM DDR4 2133MT/s   | 1        | 1.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 31       | 47.69%  |
| DDR3    | 22       | 33.85%  |
| DDR     | 4        | 6.15%   |
| Unknown | 4        | 6.15%   |
| SDRAM   | 2        | 3.08%   |
| DDR2    | 2        | 3.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 58       | 89.23%  |
| SODIMM | 7        | 10.77%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 27       | 39.71%  |
| 16384 | 15       | 22.06%  |
| 4096  | 9        | 13.24%  |
| 2048  | 8        | 11.76%  |
| 32768 | 5        | 7.35%   |
| 1024  | 4        | 5.88%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 15       | 23.08%  |
| 1333    | 9        | 13.85%  |
| 3200    | 8        | 12.31%  |
| 2400    | 6        | 9.23%   |
| 2133    | 6        | 9.23%   |
| 800     | 4        | 6.15%   |
| 3000    | 3        | 4.62%   |
| 2667    | 3        | 4.62%   |
| 2933    | 2        | 3.08%   |
| 2666    | 2        | 3.08%   |
| 400     | 2        | 3.08%   |
| 3600    | 1        | 1.54%   |
| 1332    | 1        | 1.54%   |
| 667     | 1        | 1.54%   |
| 533     | 1        | 1.54%   |
| Unknown | 1        | 1.54%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Seiko Epson     | 1        | 33.33%  |
| Hewlett-Packard | 1        | 33.33%  |
| Canon           | 1        | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                                                                      | Desktops | Percent |
|--------------------------------------------------------------------------------------------|----------|---------|
| Seiko Epson Printer                                                                        | 1        | 33.33%  |
| HP HP LaserJet M14-M17 Printer HP LEDM IPP Printer HP LEDM IPP Printer HP LEDM IPP Printer | 1        | 33.33%  |
| Canon LBP2900                                                                              | 1        | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 110 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| Logitech       | 3        | 75%     |
| Valve Software | 1        | 25%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| Valve Software 3D Camera    | 1        | 25%     |
| Logitech Webcam C270        | 1        | 25%     |
| Logitech HD Webcam C615     | 1        | 25%     |
| Logitech HD Pro Webcam C920 | 1        | 25%     |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

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


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 30       | 41.67%  |
| 1     | 29       | 40.28%  |
| 2     | 12       | 16.67%  |
| 3     | 1        | 1.39%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 27       | 50.94%  |
| Net/wireless             | 9        | 16.98%  |
| Firewire controller      | 5        | 9.43%   |
| Bluetooth                | 5        | 9.43%   |
| Sound                    | 3        | 5.66%   |
| Network                  | 2        | 3.77%   |
| Net/ethernet             | 1        | 1.89%   |
| Card reader              | 1        | 1.89%   |

