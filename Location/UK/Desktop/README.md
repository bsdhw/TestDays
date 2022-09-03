BSD in UK - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for BSD in UK.

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

Total: 282

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| MSI           | A320M-A PRO M2              | [d455ed153a](https://bsd-hardware.info/?probe=d455ed153a) | Aug 30, 2022 |
| MSI           | A320M-A PRO M2              | [9d367a6989](https://bsd-hardware.info/?probe=9d367a6989) | Aug 30, 2022 |
| Gigabyte      | H61M-DS2                    | [edb9608bc9](https://bsd-hardware.info/?probe=edb9608bc9) | Aug 24, 2022 |
| Gigabyte      | H61M-DS2 x.x                | [5648905ca2](https://bsd-hardware.info/?probe=5648905ca2) | Aug 19, 2022 |
| HP            | 8592                        | [212adc2c89](https://bsd-hardware.info/?probe=212adc2c89) | Aug 19, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [2b5456b337](https://bsd-hardware.info/?probe=2b5456b337) | Aug 19, 2022 |
| Unknown       | Unknown                     | [3208aefb72](https://bsd-hardware.info/?probe=3208aefb72) | Aug 17, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | [78340c12ef](https://bsd-hardware.info/?probe=78340c12ef) | Aug 16, 2022 |
| Protectli     | FW6 Ver                     | [970bec57b8](https://bsd-hardware.info/?probe=970bec57b8) | Aug 15, 2022 |
| Protectli     | FW6 Ver                     | [4cf33d57a1](https://bsd-hardware.info/?probe=4cf33d57a1) | Aug 15, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | [9783858164](https://bsd-hardware.info/?probe=9783858164) | Aug 14, 2022 |
| HP            | 8592                        | [7c6794942c](https://bsd-hardware.info/?probe=7c6794942c) | Aug 10, 2022 |
| Protectli     | FW6 Ver                     | [8176a8261d](https://bsd-hardware.info/?probe=8176a8261d) | Aug 04, 2022 |
| Unknown       | Unknown                     | [cbda56eddb](https://bsd-hardware.info/?probe=cbda56eddb) | Aug 03, 2022 |
| Protectli     | FW4B Ver                    | [b33527f3ee](https://bsd-hardware.info/?probe=b33527f3ee) | Jul 25, 2022 |
| Dell          | 0T7D40 A00                  | [3d5e83cf1a](https://bsd-hardware.info/?probe=3d5e83cf1a) | Jul 20, 2022 |
| Gigabyte      | J1900N-D3V                  | [17aa06f41f](https://bsd-hardware.info/?probe=17aa06f41f) | Jul 18, 2022 |
| Dell          | 0T7D40 A00                  | [2aef6b2ab4](https://bsd-hardware.info/?probe=2aef6b2ab4) | Jul 18, 2022 |
| Shuttle       | FH170                       | [a156048964](https://bsd-hardware.info/?probe=a156048964) | Jul 16, 2022 |
| Shuttle       | FH170                       | [81b62c2839](https://bsd-hardware.info/?probe=81b62c2839) | Jul 16, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [0f36e9b5a4](https://bsd-hardware.info/?probe=0f36e9b5a4) | Jul 03, 2022 |
| Inventec      | D CLASS A02                 | [6b5f81700c](https://bsd-hardware.info/?probe=6b5f81700c) | Jul 01, 2022 |
| Intel         | CARLOW                      | [615107464b](https://bsd-hardware.info/?probe=615107464b) | Jul 01, 2022 |
| Intel         | Q3XXG4-P V1.0               | [f8d0f1f7e0](https://bsd-hardware.info/?probe=f8d0f1f7e0) | Jun 29, 2022 |
| AMD           | Kabini CRB                  | [2ee9e57522](https://bsd-hardware.info/?probe=2ee9e57522) | Jun 26, 2022 |
| Dell          | 0J3C2F A02                  | [58ff991ef8](https://bsd-hardware.info/?probe=58ff991ef8) | Jun 23, 2022 |
| Dell          | 0WMJ54 A01                  | [aa5b395a20](https://bsd-hardware.info/?probe=aa5b395a20) | Jun 19, 2022 |
| Lenovo        | ThinkPad T530 24292VG       | [6f744019ce](https://bsd-hardware.info/?probe=6f744019ce) | Jun 19, 2022 |
| Gigabyte      | N3150ND3V                   | [56999b6746](https://bsd-hardware.info/?probe=56999b6746) | Jun 13, 2022 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | [31c49e462c](https://bsd-hardware.info/?probe=31c49e462c) | Jun 01, 2022 |
| Unknown       | Unknown                     | [607561a9a4](https://bsd-hardware.info/?probe=607561a9a4) | May 28, 2022 |
| Unknown       | Unknown                     | [c67bf4af0a](https://bsd-hardware.info/?probe=c67bf4af0a) | May 27, 2022 |
| ASUSTek       | A55BM-E                     | [d5773cd8b3](https://bsd-hardware.info/?probe=d5773cd8b3) | May 16, 2022 |
| ASUSTek       | A55BM-E                     | [34eddd04fc](https://bsd-hardware.info/?probe=34eddd04fc) | May 16, 2022 |
| Dell          | 0WMJ54 A01                  | [c6faa8080e](https://bsd-hardware.info/?probe=c6faa8080e) | May 10, 2022 |
| HP            | 8592                        | [d922327cdd](https://bsd-hardware.info/?probe=d922327cdd) | May 06, 2022 |
| Intel         | CARLOW                      | [6f185d9b30](https://bsd-hardware.info/?probe=6f185d9b30) | May 06, 2022 |
| Intel         | CARLOW                      | [2240df9d2d](https://bsd-hardware.info/?probe=2240df9d2d) | May 04, 2022 |
| MSI           | B450 GAMING PRO CARBON M... | [544b83da9f](https://bsd-hardware.info/?probe=544b83da9f) | Apr 24, 2022 |
| ASUSTek       | A55BM-E                     | [9758c067ec](https://bsd-hardware.info/?probe=9758c067ec) | Apr 23, 2022 |
| Unknown       | Unknown                     | [3b256304a0](https://bsd-hardware.info/?probe=3b256304a0) | Apr 23, 2022 |
| Shuttle       | FH61V                       | [6f4c78b7db](https://bsd-hardware.info/?probe=6f4c78b7db) | Apr 23, 2022 |
| Gigabyte      | 990FXA-UD3                  | [3813b46bc1](https://bsd-hardware.info/?probe=3813b46bc1) | Apr 22, 2022 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [3322ad9dac](https://bsd-hardware.info/?probe=3322ad9dac) | Apr 20, 2022 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [aa48329066](https://bsd-hardware.info/?probe=aa48329066) | Apr 20, 2022 |
| ASUSTek       | AM1M-A                      | [754d45f24f](https://bsd-hardware.info/?probe=754d45f24f) | Apr 11, 2022 |
| Jetway        | 1.0                         | [0048067292](https://bsd-hardware.info/?probe=0048067292) | Apr 11, 2022 |
| ASRock        | X370 Taichi                 | [7f156a0671](https://bsd-hardware.info/?probe=7f156a0671) | Apr 10, 2022 |
| ASRock        | X370 Taichi                 | [a006c9e999](https://bsd-hardware.info/?probe=a006c9e999) | Apr 10, 2022 |
| ASUSTek       | A55BM-E                     | [907da6ea08](https://bsd-hardware.info/?probe=907da6ea08) | Apr 10, 2022 |
| ASUSTek       | A55BM-E                     | [f71ea0931e](https://bsd-hardware.info/?probe=f71ea0931e) | Apr 10, 2022 |
| Gigabyte      | B560M DS3H                  | [a7470aa647](https://bsd-hardware.info/?probe=a7470aa647) | Apr 09, 2022 |
| MSI           | MAG B550M MORTAR            | [d9ef1569d2](https://bsd-hardware.info/?probe=d9ef1569d2) | Apr 07, 2022 |
| Gigabyte      | H61M-DS2 x.x                | [2a7de69b4b](https://bsd-hardware.info/?probe=2a7de69b4b) | Apr 04, 2022 |
| Quanmax       | spo-book TECH QUAD B1       | [1b382db711](https://bsd-hardware.info/?probe=1b382db711) | Apr 04, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [6274858d8d](https://bsd-hardware.info/?probe=6274858d8d) | Apr 02, 2022 |
| Foxconn       | 2ADA                        | [9fae64765f](https://bsd-hardware.info/?probe=9fae64765f) | Mar 31, 2022 |
| ASUSTek       | A55BM-E                     | [eaa8d1a7d7](https://bsd-hardware.info/?probe=eaa8d1a7d7) | Mar 30, 2022 |
| Intel         | Q3XXG4-P V1.0               | [730dd09705](https://bsd-hardware.info/?probe=730dd09705) | Mar 28, 2022 |
| Unknown       | Unknown                     | [9b49ac0cf2](https://bsd-hardware.info/?probe=9b49ac0cf2) | Mar 23, 2022 |
| Intel         | DH61CR AAG14064-209         | [3812666505](https://bsd-hardware.info/?probe=3812666505) | Mar 23, 2022 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | [87289f0c36](https://bsd-hardware.info/?probe=87289f0c36) | Mar 20, 2022 |
| Unknown       | Unknown                     | [8870903766](https://bsd-hardware.info/?probe=8870903766) | Mar 20, 2022 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | [c9fb46b179](https://bsd-hardware.info/?probe=c9fb46b179) | Mar 19, 2022 |
| HP            | 8592                        | [afffe00b26](https://bsd-hardware.info/?probe=afffe00b26) | Mar 19, 2022 |
| Dell          | 0GXM1W A02                  | [d28bef2c37](https://bsd-hardware.info/?probe=d28bef2c37) | Mar 17, 2022 |
| PC Engines    | APU2                        | [e56b256787](https://bsd-hardware.info/?probe=e56b256787) | Mar 15, 2022 |
| Intel         | DH67BL AAG10189-211         | [10a235fe8f](https://bsd-hardware.info/?probe=10a235fe8f) | Mar 13, 2022 |
| Unknown       | Unknown                     | [a556350922](https://bsd-hardware.info/?probe=a556350922) | Mar 11, 2022 |
| Unknown       | Unknown                     | [5a22c1d4ab](https://bsd-hardware.info/?probe=5a22c1d4ab) | Mar 10, 2022 |
| Dell          | 0WMJ54 A01                  | [77c308e93e](https://bsd-hardware.info/?probe=77c308e93e) | Mar 05, 2022 |
| Dell          | 0WMJ54 A01                  | [1ffc0a0805](https://bsd-hardware.info/?probe=1ffc0a0805) | Mar 03, 2022 |
| ASUSTek       | H81M-PLUS                   | [26565f3d84](https://bsd-hardware.info/?probe=26565f3d84) | Mar 01, 2022 |
| Biostar       | J3160NH                     | [536f856d94](https://bsd-hardware.info/?probe=536f856d94) | Feb 23, 2022 |
| Dell          | 0VD5HY A07                  | [bb86fb3e67](https://bsd-hardware.info/?probe=bb86fb3e67) | Feb 22, 2022 |
| HP            | 8592                        | [fc273bb51a](https://bsd-hardware.info/?probe=fc273bb51a) | Feb 14, 2022 |
| HP            | 8592                        | [5accd7ce0d](https://bsd-hardware.info/?probe=5accd7ce0d) | Feb 13, 2022 |
| PAIQ          | EC3-BT19D4L A1              | [a3843d55ca](https://bsd-hardware.info/?probe=a3843d55ca) | Feb 05, 2022 |
| Intel         | J1900                       | [3b4b841677](https://bsd-hardware.info/?probe=3b4b841677) | Feb 04, 2022 |
| PAIQ          | EC3-BT19D4L A1              | [86cb857d00](https://bsd-hardware.info/?probe=86cb857d00) | Feb 02, 2022 |
| PC Engines    | APU2                        | [0409aa82c2](https://bsd-hardware.info/?probe=0409aa82c2) | Feb 01, 2022 |
| Dell          | 0J3C2F A02                  | [4b4b77d8f3](https://bsd-hardware.info/?probe=4b4b77d8f3) | Feb 01, 2022 |
| Yanling       | YL-KBR6L Ver:1.01           | [a65a16decd](https://bsd-hardware.info/?probe=a65a16decd) | Jan 31, 2022 |
| ASUSTek       | PRIME Z490M-PLUS            | [d08074d468](https://bsd-hardware.info/?probe=d08074d468) | Jan 28, 2022 |
| Gigabyte      | J3455N-D3H                  | [461b538b72](https://bsd-hardware.info/?probe=461b538b72) | Jan 28, 2022 |
| Unknown       | PICO PC                     | [538ca6b389](https://bsd-hardware.info/?probe=538ca6b389) | Jan 27, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [277f5bacdd](https://bsd-hardware.info/?probe=277f5bacdd) | Jan 22, 2022 |
| ASRock        | QC5000M-ITX/PH              | [6ea5e898fa](https://bsd-hardware.info/?probe=6ea5e898fa) | Jan 21, 2022 |
| Intel         | SHARKBAY                    | [6bde480ecd](https://bsd-hardware.info/?probe=6bde480ecd) | Jan 14, 2022 |
| ASUSTek       | Z87-PRO                     | [280ea0618b](https://bsd-hardware.info/?probe=280ea0618b) | Jan 14, 2022 |
| Gigabyte      | B450M DS3H-CF               | [825d20fcf7](https://bsd-hardware.info/?probe=825d20fcf7) | Jan 14, 2022 |
| Winston Ma... | PICO PC                     | [ac1014aab2](https://bsd-hardware.info/?probe=ac1014aab2) | Jan 13, 2022 |
| Gigabyte      | B450M DS3H-CF               | [b953d9d2e6](https://bsd-hardware.info/?probe=b953d9d2e6) | Jan 13, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | [1527560bbd](https://bsd-hardware.info/?probe=1527560bbd) | Jan 11, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | [d914e4c500](https://bsd-hardware.info/?probe=d914e4c500) | Jan 10, 2022 |
| HP            | 8169                        | [85e0cf058c](https://bsd-hardware.info/?probe=85e0cf058c) | Jan 10, 2022 |
| HP            | ProLiant MicroServer Gen... | [9a24935dab](https://bsd-hardware.info/?probe=9a24935dab) | Jan 09, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [ce54324df7](https://bsd-hardware.info/?probe=ce54324df7) | Jan 09, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [de6d713222](https://bsd-hardware.info/?probe=de6d713222) | Jan 05, 2022 |
| PC Engines    | APU                         | [efe2fbd850](https://bsd-hardware.info/?probe=efe2fbd850) | Jan 04, 2022 |
| ASRock        | B450 Steel Legend           | [e67007df20](https://bsd-hardware.info/?probe=e67007df20) | Jan 01, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [dd62d57a45](https://bsd-hardware.info/?probe=dd62d57a45) | Dec 29, 2021 |
| Protectli     | FW6 Ver                     | [c3c1529f86](https://bsd-hardware.info/?probe=c3c1529f86) | Dec 22, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [c83118d6d0](https://bsd-hardware.info/?probe=c83118d6d0) | Dec 09, 2021 |
| Inventec      | Z CLASS A02                 | [67556468e3](https://bsd-hardware.info/?probe=67556468e3) | Nov 30, 2021 |
| Protectli     | FW6 Ver                     | [53e6ac863a](https://bsd-hardware.info/?probe=53e6ac863a) | Nov 18, 2021 |
| Dell          | 0J3C2F A02                  | [56cd34ffef](https://bsd-hardware.info/?probe=56cd34ffef) | Nov 17, 2021 |
| Dell          | 0F6X5P A00                  | [8451595212](https://bsd-hardware.info/?probe=8451595212) | Nov 16, 2021 |
| Dell          | 0GXM1W A01                  | [e0c3737f7c](https://bsd-hardware.info/?probe=e0c3737f7c) | Nov 15, 2021 |
| Dell          | 0J3C2F A02                  | [a2bbadf4a5](https://bsd-hardware.info/?probe=a2bbadf4a5) | Nov 12, 2021 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [f0c5f5ef97](https://bsd-hardware.info/?probe=f0c5f5ef97) | Nov 09, 2021 |
| Yanling       | YL-KBR6L                    | [35f1c905eb](https://bsd-hardware.info/?probe=35f1c905eb) | Nov 04, 2021 |
| AZW           | GK55                        | [91db367d18](https://bsd-hardware.info/?probe=91db367d18) | Oct 28, 2021 |
| Unknown       | Unknown                     | [8caf15c2a5](https://bsd-hardware.info/?probe=8caf15c2a5) | Oct 22, 2021 |
| Gigabyte      | H61M-DS2 x.x                | [8e11143a1d](https://bsd-hardware.info/?probe=8e11143a1d) | Oct 14, 2021 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | [c8b057c4e4](https://bsd-hardware.info/?probe=c8b057c4e4) | Oct 12, 2021 |
| Gigabyte      | J3455N-D3H                  | [40aba3842c](https://bsd-hardware.info/?probe=40aba3842c) | Oct 03, 2021 |
| ASUSTek       | PRIME A320M-K               | [c574dcc409](https://bsd-hardware.info/?probe=c574dcc409) | Oct 01, 2021 |
| ASRockRack    | X470D4U2-2T                 | [357b9d3ad2](https://bsd-hardware.info/?probe=357b9d3ad2) | Sep 30, 2021 |
| HP            | 0AE8h C                     | [159e371cc7](https://bsd-hardware.info/?probe=159e371cc7) | Sep 30, 2021 |
| Intel         | DH67BL AAG10189-211         | [cc7d3fa6a3](https://bsd-hardware.info/?probe=cc7d3fa6a3) | Sep 26, 2021 |
| Intel         | DH67BL AAG10189-211         | [dc09f7f7cb](https://bsd-hardware.info/?probe=dc09f7f7cb) | Sep 25, 2021 |
| ASRock        | J3455M                      | [411b04cbba](https://bsd-hardware.info/?probe=411b04cbba) | Sep 25, 2021 |
| Unknown       | Unknown                     | [462d25d041](https://bsd-hardware.info/?probe=462d25d041) | Sep 19, 2021 |
| Intel         | Q3XXG4-P V1.0               | [63a24ea67f](https://bsd-hardware.info/?probe=63a24ea67f) | Sep 12, 2021 |
| ASUSTek       | H110M-PLUS                  | [08b4825275](https://bsd-hardware.info/?probe=08b4825275) | Sep 09, 2021 |
| ASRockRack    | X470D4U2-2T                 | [8ce323def8](https://bsd-hardware.info/?probe=8ce323def8) | Sep 09, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [f860e13b6b](https://bsd-hardware.info/?probe=f860e13b6b) | Sep 08, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [a3fe3577b0](https://bsd-hardware.info/?probe=a3fe3577b0) | Aug 26, 2021 |
| ASRock        | B450M-HDV                   | [fdeba8e75d](https://bsd-hardware.info/?probe=fdeba8e75d) | Aug 26, 2021 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [2499806edc](https://bsd-hardware.info/?probe=2499806edc) | Aug 26, 2021 |
| ASRock        | B450M-HDV                   | [996f8b5618](https://bsd-hardware.info/?probe=996f8b5618) | Aug 22, 2021 |
| Unknown       | Unknown                     | [beda690c72](https://bsd-hardware.info/?probe=beda690c72) | Aug 19, 2021 |
| Intel         | Q3XXG4-P V1.0               | [f4fe59224e](https://bsd-hardware.info/?probe=f4fe59224e) | Aug 18, 2021 |
| Unknown       | Unknown                     | [621207a309](https://bsd-hardware.info/?probe=621207a309) | Aug 11, 2021 |
| Shuttle       | FH81                        | [58ddd2da40](https://bsd-hardware.info/?probe=58ddd2da40) | Aug 08, 2021 |
| Intel         | DH67BL AAG10189-211         | [6106746a7f](https://bsd-hardware.info/?probe=6106746a7f) | Aug 07, 2021 |
| NU941         | 1.0                         | [e76f1a177c](https://bsd-hardware.info/?probe=e76f1a177c) | Aug 07, 2021 |
| ASUSTek       | PRIME Z490M-PLUS            | [aad64262b5](https://bsd-hardware.info/?probe=aad64262b5) | Jul 29, 2021 |
| Unknown       | PICO PC                     | [47f932c3d3](https://bsd-hardware.info/?probe=47f932c3d3) | Jul 29, 2021 |
| Biostar       | A88M                        | [f9d3b78d58](https://bsd-hardware.info/?probe=f9d3b78d58) | Jul 26, 2021 |
| Unknown       | Unknown                     | [41e0c49bcb](https://bsd-hardware.info/?probe=41e0c49bcb) | Jul 24, 2021 |
| Intel         | Q3XXG4-P V1.0               | [05180e292a](https://bsd-hardware.info/?probe=05180e292a) | Jul 24, 2021 |
| ASUSTek       | H110M-PLUS                  | [d0f2da9c41](https://bsd-hardware.info/?probe=d0f2da9c41) | Jul 21, 2021 |
| HP            | 213D A01                    | [3b518acc68](https://bsd-hardware.info/?probe=3b518acc68) | Jul 15, 2021 |
| Unknown       | Unknown                     | [17938ca56f](https://bsd-hardware.info/?probe=17938ca56f) | Jul 14, 2021 |
| Dell          | 0F6X5P A00                  | [46aaff0a7c](https://bsd-hardware.info/?probe=46aaff0a7c) | Jul 14, 2021 |
| HP            | 0AE8h C                     | [23df6b2e94](https://bsd-hardware.info/?probe=23df6b2e94) | Jul 12, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [0c9fc39896](https://bsd-hardware.info/?probe=0c9fc39896) | Jul 11, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [3d69b35f7d](https://bsd-hardware.info/?probe=3d69b35f7d) | Jul 11, 2021 |
| Unknown       | Unknown                     | [4a3836de00](https://bsd-hardware.info/?probe=4a3836de00) | Jul 08, 2021 |
| Protectli     | FW4B Ver                    | [18d373b2d3](https://bsd-hardware.info/?probe=18d373b2d3) | Jul 06, 2021 |
| ASRock        | J3355B-ITX                  | [d8bd1a3025](https://bsd-hardware.info/?probe=d8bd1a3025) | Jul 05, 2021 |
| ASRock        | B450M-HDV                   | [dca41aa10a](https://bsd-hardware.info/?probe=dca41aa10a) | Jul 05, 2021 |
| PC Engines    | apu4                        | [18a1374b95](https://bsd-hardware.info/?probe=18a1374b95) | Jul 04, 2021 |
| Biostar       | B450MH                      | [167f09a25c](https://bsd-hardware.info/?probe=167f09a25c) | Jun 29, 2021 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [1b35a7ea0a](https://bsd-hardware.info/?probe=1b35a7ea0a) | Jun 28, 2021 |
| Intel CNCT... | Unknown                     | [d2298356a0](https://bsd-hardware.info/?probe=d2298356a0) | Jun 22, 2021 |
| Intel         | DH67CL AAG10212-206         | [f2367a4249](https://bsd-hardware.info/?probe=f2367a4249) | Jun 21, 2021 |
| Unknown       | Unknown                     | [287ec8a2ee](https://bsd-hardware.info/?probe=287ec8a2ee) | Jun 19, 2021 |
| Unknown       | Unknown                     | [e6a66eac0b](https://bsd-hardware.info/?probe=e6a66eac0b) | Jun 19, 2021 |
| ASUSTek       | PRIME Z270-A                | [c7b4a17b7d](https://bsd-hardware.info/?probe=c7b4a17b7d) | Jun 19, 2021 |
| Unknown       | Unknown                     | [c3f7e818ae](https://bsd-hardware.info/?probe=c3f7e818ae) | Jun 18, 2021 |
| ASRock        | B550 Phantom Gaming 4       | [5ccdc16de4](https://bsd-hardware.info/?probe=5ccdc16de4) | Jun 12, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [9062f35935](https://bsd-hardware.info/?probe=9062f35935) | Jun 10, 2021 |
| Dell          | 02YYK5 A01                  | [2bb2632198](https://bsd-hardware.info/?probe=2bb2632198) | Jun 04, 2021 |
| Gigabyte      | J3455N-D3H                  | [23751b05a9](https://bsd-hardware.info/?probe=23751b05a9) | Jun 01, 2021 |
| PC Engines    | APU2                        | [c5f1ffd6c0](https://bsd-hardware.info/?probe=c5f1ffd6c0) | May 31, 2021 |
| Intel         | Q3XXG4-P V1.0               | [cd60e38216](https://bsd-hardware.info/?probe=cd60e38216) | May 30, 2021 |
| HP            | 213D A01                    | [de3d6dcdf5](https://bsd-hardware.info/?probe=de3d6dcdf5) | May 22, 2021 |
| HP            | 18E7                        | [56a672af0a](https://bsd-hardware.info/?probe=56a672af0a) | May 20, 2021 |
| Apple         | Mac-F221BEC8                | [869f003493](https://bsd-hardware.info/?probe=869f003493) | May 17, 2021 |
| Lenovo        | SDK0J40705 WIN 342503995... | [b7ea8547ce](https://bsd-hardware.info/?probe=b7ea8547ce) | May 15, 2021 |
| EVGA          | X299 FTW K                  | [c4862c598a](https://bsd-hardware.info/?probe=c4862c598a) | May 11, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | [cc49321b12](https://bsd-hardware.info/?probe=cc49321b12) | May 11, 2021 |
| Biostar       | A88M                        | [74c3afbf45](https://bsd-hardware.info/?probe=74c3afbf45) | May 10, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [8d78068ca7](https://bsd-hardware.info/?probe=8d78068ca7) | May 09, 2021 |
| Unknown       | Unknown                     | [a707beae6f](https://bsd-hardware.info/?probe=a707beae6f) | May 02, 2021 |
| Yanling       | YL-KBR6L Ver:1.01           | [0cddbdee33](https://bsd-hardware.info/?probe=0cddbdee33) | May 01, 2021 |
| Dell          | 0WR7PY A02                  | [1a780b9a95](https://bsd-hardware.info/?probe=1a780b9a95) | Apr 27, 2021 |
| ASUSTek       | Z87-PRO                     | [d218181abb](https://bsd-hardware.info/?probe=d218181abb) | Apr 26, 2021 |
| Intel         | Q3XXG4-P V1.0               | [f888bd5312](https://bsd-hardware.info/?probe=f888bd5312) | Apr 20, 2021 |
| Intel         | Q3XXG4-P V1.0               | [7dacccd5f5](https://bsd-hardware.info/?probe=7dacccd5f5) | Apr 18, 2021 |
| Lenovo        | 3129 SDK0J40700 WIN 3258... | [1cef60d042](https://bsd-hardware.info/?probe=1cef60d042) | Apr 13, 2021 |
| Dell          | 0VRWRC A00                  | [903d74f8e7](https://bsd-hardware.info/?probe=903d74f8e7) | Apr 12, 2021 |
| Unknown       | PICO PC                     | [8ab959af5c](https://bsd-hardware.info/?probe=8ab959af5c) | Apr 11, 2021 |
| Biostar       | A88M                        | [6fc307ade8](https://bsd-hardware.info/?probe=6fc307ade8) | Apr 09, 2021 |
| Unknown       | Unknown                     | [9eafdd3e07](https://bsd-hardware.info/?probe=9eafdd3e07) | Apr 07, 2021 |
| Unknown       | Unknown                     | [5393389555](https://bsd-hardware.info/?probe=5393389555) | Apr 05, 2021 |
| Dell          | 0TP412                      | [1bc05b5951](https://bsd-hardware.info/?probe=1bc05b5951) | Apr 04, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [7fc044cdb6](https://bsd-hardware.info/?probe=7fc044cdb6) | Apr 03, 2021 |
| AMI           | PEISIA E3845 VER1.0         | [12909e67d4](https://bsd-hardware.info/?probe=12909e67d4) | Mar 23, 2021 |
| AMI           | PEISIA E3845 VER1.0         | [159f39df79](https://bsd-hardware.info/?probe=159f39df79) | Mar 23, 2021 |
| Unknown       | Unknown                     | [a81f03223e](https://bsd-hardware.info/?probe=a81f03223e) | Mar 22, 2021 |
| Unknown       | Unknown                     | [04d2c36bec](https://bsd-hardware.info/?probe=04d2c36bec) | Mar 22, 2021 |
| HP            | 1825                        | [15e822a4dc](https://bsd-hardware.info/?probe=15e822a4dc) | Mar 20, 2021 |
| Unknown       | Unknown                     | [192451364a](https://bsd-hardware.info/?probe=192451364a) | Mar 20, 2021 |
| Quanmax       | spo-book TECH QUAD B1       | [3e479a0551](https://bsd-hardware.info/?probe=3e479a0551) | Mar 16, 2021 |
| ASUSTek       | H110M-PLUS                  | [80e7c230d7](https://bsd-hardware.info/?probe=80e7c230d7) | Mar 12, 2021 |
| ASUSTek       | H110M-PLUS                  | [cf00023cef](https://bsd-hardware.info/?probe=cf00023cef) | Mar 11, 2021 |
| PC Engines    | APU2                        | [14142a990a](https://bsd-hardware.info/?probe=14142a990a) | Mar 09, 2021 |
| Unknown       | Unknown                     | [1ad8d8132f](https://bsd-hardware.info/?probe=1ad8d8132f) | Mar 09, 2021 |
| ASUSTek       | All Series                  | [b4aec46644](https://bsd-hardware.info/?probe=b4aec46644) | Mar 07, 2021 |
| ASUSTek       | All Series                  | [f7b1921594](https://bsd-hardware.info/?probe=f7b1921594) | Mar 07, 2021 |
| ASUSTek       | P8Z77-V                     | [88ee81b089](https://bsd-hardware.info/?probe=88ee81b089) | Mar 06, 2021 |
| Unknown       | Unknown                     | [99448b6fad](https://bsd-hardware.info/?probe=99448b6fad) | Mar 02, 2021 |
| ASUSTek       | PRIME Z490M-PLUS            | [d106f46dde](https://bsd-hardware.info/?probe=d106f46dde) | Mar 01, 2021 |
| Shuttle       | FS61                        | [3016999a76](https://bsd-hardware.info/?probe=3016999a76) | Feb 25, 2021 |
| Unknown       | YL-SKUL6                    | [96d7fbef45](https://bsd-hardware.info/?probe=96d7fbef45) | Feb 25, 2021 |
| Acer          | RS780HVF                    | [3367ae4413](https://bsd-hardware.info/?probe=3367ae4413) | Feb 24, 2021 |
| ASUSTek       | P8Z77-V LX2                 | [0aeea0fec9](https://bsd-hardware.info/?probe=0aeea0fec9) | Feb 23, 2021 |
| Biostar       | A88M                        | [2d4a32fbc3](https://bsd-hardware.info/?probe=2d4a32fbc3) | Feb 22, 2021 |
| Biostar       | A88M                        | [7ff97a241a](https://bsd-hardware.info/?probe=7ff97a241a) | Feb 22, 2021 |
| MSI           | A78M-E35                    | [0a1462e4a7](https://bsd-hardware.info/?probe=0a1462e4a7) | Feb 22, 2021 |
| Dell          | 0M863N A01                  | [8dd5cd14a9](https://bsd-hardware.info/?probe=8dd5cd14a9) | Feb 22, 2021 |
| Dell          | 0M863N A01                  | [94f2627d79](https://bsd-hardware.info/?probe=94f2627d79) | Feb 20, 2021 |
| Lenovo        | SDK0J40705 WIN 342503995... | [3f0003e9a2](https://bsd-hardware.info/?probe=3f0003e9a2) | Feb 19, 2021 |
| Gigabyte      | M68MT-S2                    | [5d94572e10](https://bsd-hardware.info/?probe=5d94572e10) | Feb 16, 2021 |
| Gigabyte      | B450M DS3H-CF               | [9181a2479b](https://bsd-hardware.info/?probe=9181a2479b) | Feb 15, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | [3c043807ba](https://bsd-hardware.info/?probe=3c043807ba) | Feb 15, 2021 |
| Lenovo        | SDK0J40705 WIN 342503995... | [62e8f472f6](https://bsd-hardware.info/?probe=62e8f472f6) | Feb 15, 2021 |
| Shuttle       | DS10U                       | [ad9283aae7](https://bsd-hardware.info/?probe=ad9283aae7) | Feb 14, 2021 |
| Intel         | Q3XXG4-P V1.0               | [7313a6d6e2](https://bsd-hardware.info/?probe=7313a6d6e2) | Feb 14, 2021 |
| Gigabyte      | Z97M-D3H                    | [a335917871](https://bsd-hardware.info/?probe=a335917871) | Feb 14, 2021 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [565ceb36f0](https://bsd-hardware.info/?probe=565ceb36f0) | Feb 14, 2021 |
| Shuttle       | DS10U                       | [aef3ca0794](https://bsd-hardware.info/?probe=aef3ca0794) | Feb 12, 2021 |
| ASUSTek       | Z87-PRO                     | [ad0f0dde9d](https://bsd-hardware.info/?probe=ad0f0dde9d) | Feb 10, 2021 |
| ASRock        | B550 Phantom Gaming 4       | [435f081b3b](https://bsd-hardware.info/?probe=435f081b3b) | Feb 09, 2021 |
| ASRock        | B550 Phantom Gaming 4       | [7a8ab8feaf](https://bsd-hardware.info/?probe=7a8ab8feaf) | Feb 08, 2021 |
| ASRock        | B550 Phantom Gaming 4       | [2d0beb2534](https://bsd-hardware.info/?probe=2d0beb2534) | Feb 08, 2021 |
| QOTOM         | Q355G4-P V1.0               | [5c09abed71](https://bsd-hardware.info/?probe=5c09abed71) | Feb 05, 2021 |
| QOTOM         | Q355G4-P V1.0               | [c79ea5055f](https://bsd-hardware.info/?probe=c79ea5055f) | Feb 05, 2021 |
| QOTOM         | Q355G4-P V1.0               | [222778ae2b](https://bsd-hardware.info/?probe=222778ae2b) | Feb 05, 2021 |
| Lenovo        | SDK0J40705 WIN 342503995... | [f827129438](https://bsd-hardware.info/?probe=f827129438) | Feb 04, 2021 |
| Unknown       | PICO PC                     | [de1cd4e050](https://bsd-hardware.info/?probe=de1cd4e050) | Feb 04, 2021 |
| Lenovo        | SDK0J40705 WIN 342503995... | [b192745cde](https://bsd-hardware.info/?probe=b192745cde) | Feb 03, 2021 |
| Lenovo        | SDK0J40705 WIN 342503995... | [c11da3972d](https://bsd-hardware.info/?probe=c11da3972d) | Feb 03, 2021 |
| Protectli     | FW4B                        | [5334bf8761](https://bsd-hardware.info/?probe=5334bf8761) | Feb 03, 2021 |
| Deciso        | Netboard A10                | [a3f5b21dff](https://bsd-hardware.info/?probe=a3f5b21dff) | Feb 03, 2021 |
| Supermicro    | X8SIU                       | [57fbc2cb9a](https://bsd-hardware.info/?probe=57fbc2cb9a) | Feb 02, 2021 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [6b9511bf39](https://bsd-hardware.info/?probe=6b9511bf39) | Jan 31, 2021 |
| Unknown       | YL-SKUL6                    | [9f0538d38b](https://bsd-hardware.info/?probe=9f0538d38b) | Jan 31, 2021 |
| ASRock        | X399 Taichi                 | [875e6714ca](https://bsd-hardware.info/?probe=875e6714ca) | Jan 27, 2021 |
| ASRock        | J3455M                      | [c90667d62c](https://bsd-hardware.info/?probe=c90667d62c) | Jan 27, 2021 |
| Lenovo        | Board                       | [da81aa7cb9](https://bsd-hardware.info/?probe=da81aa7cb9) | Jan 26, 2021 |
| AZW           | GK55                        | [077fedae7d](https://bsd-hardware.info/?probe=077fedae7d) | Jan 26, 2021 |
| AZW           | GK55                        | [db3fc2c7b2](https://bsd-hardware.info/?probe=db3fc2c7b2) | Jan 25, 2021 |
| Intel         | Q3XXG4-P V1.0               | [aa5782d83e](https://bsd-hardware.info/?probe=aa5782d83e) | Jan 24, 2021 |
| Dell          | 0WMJ54 A01                  | [6d11e7b348](https://bsd-hardware.info/?probe=6d11e7b348) | Jan 23, 2021 |
| Unknown       | Unknown                     | [aeb42f8919](https://bsd-hardware.info/?probe=aeb42f8919) | Jan 23, 2021 |
| Unknown       | Unknown                     | [5b3be23f50](https://bsd-hardware.info/?probe=5b3be23f50) | Jan 23, 2021 |
| Jetway        | 1.0                         | [8f47246cdf](https://bsd-hardware.info/?probe=8f47246cdf) | Jan 23, 2021 |
| Unknown       | Unknown                     | [f952cac718](https://bsd-hardware.info/?probe=f952cac718) | Jan 22, 2021 |
| Intel         | Q3XXG4-P V1.0               | [29c88c0b95](https://bsd-hardware.info/?probe=29c88c0b95) | Jan 22, 2021 |
| Protectli     | FW4B                        | [ea6fcc20bc](https://bsd-hardware.info/?probe=ea6fcc20bc) | Jan 22, 2021 |
| Intel         | Q3XXG4-P V1.0               | [1722f1824f](https://bsd-hardware.info/?probe=1722f1824f) | Jan 22, 2021 |
| PC Engines    | APU2                        | [0fac28f2bf](https://bsd-hardware.info/?probe=0fac28f2bf) | Jan 21, 2021 |
| Shuttle       | FS67U                       | [8ed524df62](https://bsd-hardware.info/?probe=8ed524df62) | Jan 20, 2021 |
| Protectli     | FW4A Ver                    | [5725505d31](https://bsd-hardware.info/?probe=5725505d31) | Jan 20, 2021 |
| PC Engines    | APU2                        | [49463c91f7](https://bsd-hardware.info/?probe=49463c91f7) | Jan 19, 2021 |
| Dell          | 0M863N A01                  | [4feae8b20d](https://bsd-hardware.info/?probe=4feae8b20d) | Jan 15, 2021 |
| ASRock        | 990FX Extreme4              | [20c77fd91b](https://bsd-hardware.info/?probe=20c77fd91b) | Dec 16, 2020 |
| Gigabyte      | Z97P-D3                     | [588af8f5b3](https://bsd-hardware.info/?probe=588af8f5b3) | Dec 16, 2020 |
| Acer          | Aspire X1440                | [6100b30349](https://bsd-hardware.info/?probe=6100b30349) | Dec 15, 2020 |
| Apple         | Xserve3,1                   | [7329a7650d](https://bsd-hardware.info/?probe=7329a7650d) | Dec 05, 2020 |
| ASUSTek       | PRIME X570-P                | [1076ee5826](https://bsd-hardware.info/?probe=1076ee5826) | Dec 04, 2020 |
| ASUSTek       | PRIME X570-P                | [ec1363a9ea](https://bsd-hardware.info/?probe=ec1363a9ea) | Dec 04, 2020 |
| MSI           | B450 GAMING PLUS            | [4cf3dd682b](https://bsd-hardware.info/?probe=4cf3dd682b) | Nov 24, 2020 |
| ASRock        | IMB-191                     | [76991234cd](https://bsd-hardware.info/?probe=76991234cd) | Nov 18, 2020 |
| Unknown       | Unknown                     | [d08d610bd0](https://bsd-hardware.info/?probe=d08d610bd0) | Oct 29, 2020 |
| Intel         | CRESCENTBAY                 | [42d114559b](https://bsd-hardware.info/?probe=42d114559b) | Oct 21, 2020 |
| ASRock        | IMB-191                     | [4ac9e9cf2a](https://bsd-hardware.info/?probe=4ac9e9cf2a) | Oct 19, 2020 |
| Fujitsu       | D2950-A1 S26361-D2950-A1    | [86e9866c03](https://bsd-hardware.info/?probe=86e9866c03) | Oct 02, 2020 |
| Fujitsu       | D2950-A1 S26361-D2950-A1    | [3b8f8a2033](https://bsd-hardware.info/?probe=3b8f8a2033) | Oct 02, 2020 |
| Lenovo        | 3098 SDK0E50510 WIN         | [b9b460d9e2](https://bsd-hardware.info/?probe=b9b460d9e2) | Sep 28, 2020 |
| PC Engines    | apu4                        | [f0f8a22656](https://bsd-hardware.info/?probe=f0f8a22656) | Aug 05, 2020 |
| Biostar       | B450MH                      | [4ad280f947](https://bsd-hardware.info/?probe=4ad280f947) | Aug 02, 2020 |
| HPE           | ProLiant MicroServer Gen... | [6b015a340b](https://bsd-hardware.info/?probe=6b015a340b) | Jul 31, 2020 |
| Lenovo        | Win8 Pro DPK TPG            | [db7146b868](https://bsd-hardware.info/?probe=db7146b868) | Jul 14, 2020 |
| Sony UK       | Raspberry Pi 4 Model B      | [483af3998c](https://bsd-hardware.info/?probe=483af3998c) | May 28, 2020 |
| Gigabyte      | H61M-S2PV                   | [14e00aa09f](https://bsd-hardware.info/?probe=14e00aa09f) | May 25, 2020 |
| HP            | 213D A01                    | [23f8adb299](https://bsd-hardware.info/?probe=23f8adb299) | May 25, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| OPNsense 20.7.8      | 12       | 5.41%   |
| OPNsense 21.7.7      | 8        | 3.6%    |
| OPNsense 21.1.5      | 8        | 3.6%    |
| helloSystem 0.5.0    | 8        | 3.6%    |
| OPNsense 22.1        | 7        | 3.15%   |
| OPNsense 21.7.1      | 7        | 3.15%   |
| OPNsense 21.1        | 7        | 3.15%   |
| OPNsense 22.1.6      | 6        | 2.7%    |
| OPNsense 21.1.7      | 6        | 2.7%    |
| OPNsense 21.1.4      | 6        | 2.7%    |
| helloSystem 0.4.0    | 6        | 2.7%    |
| OPNsense 22.7.2      | 5        | 2.25%   |
| OPNsense 22.1.9      | 5        | 2.25%   |
| OPNsense 22.1.8      | 5        | 2.25%   |
| OPNsense 22.1.3      | 5        | 2.25%   |
| OPNsense 21.7.8      | 5        | 2.25%   |
| OPNsense 21.7.3      | 5        | 2.25%   |
| OPNsense 21.1.1      | 5        | 2.25%   |
| OPNsense 22.1.4      | 4        | 1.8%    |
| OPNsense 22.1.2      | 4        | 1.8%    |
| OPNsense 21.1.8      | 4        | 1.8%    |
| OPNsense 21.1.6      | 4        | 1.8%    |
| OPNsense 21.1.3      | 4        | 1.8%    |
| OPNsense 21.1.2      | 4        | 1.8%    |
| OpenBSD 6.8          | 4        | 1.8%    |
| GhostBSD 20.04.02    | 4        | 1.8%    |
| FreeBSD 14.0-CURRENT | 4        | 1.8%    |
| OPNsense 22.1.10     | 3        | 1.35%   |
| OPNsense 21.7.5      | 3        | 1.35%   |
| OPNsense 21.7.2      | 3        | 1.35%   |
| helloSystem 0.7.0    | 3        | 1.35%   |
| FreeBSD 13.0-STABLE  | 3        | 1.35%   |
| FreeBSD 13.0-p3      | 3        | 1.35%   |
| FreeBSD 13.0-p2      | 3        | 1.35%   |
| FreeBSD 13.0         | 3        | 1.35%   |
| FreeBSD 12.2-p3      | 3        | 1.35%   |
| FreeBSD 12.2         | 3        | 1.35%   |
| OPNsense 22.7.1      | 2        | 0.9%    |
| OPNsense 22.7        | 2        | 0.9%    |
| OPNsense 22.1.5      | 2        | 0.9%    |
| OPNsense 21.7.4      | 2        | 0.9%    |
| OPNsense 21.7        | 2        | 0.9%    |
| OPNsense 20.7.7      | 2        | 0.9%    |
| OPNsense 20.7        | 2        | 0.9%    |
| OpenBSD 6.7          | 2        | 0.9%    |
| helloSystem 0.3.0    | 2        | 0.9%    |
| FreeBSD 13.0-p11     | 2        | 0.9%    |
| FreeBSD 12.1-p7      | 2        | 0.9%    |
| FreeBSD 12.1         | 2        | 0.9%    |
| XigmaNAS 12.2        | 1        | 0.45%   |
| pfSense 12.3-STABLE  | 1        | 0.45%   |
| OPNsense 22.1.1      | 1        | 0.45%   |
| OPNsense 21.7.6      | 1        | 0.45%   |
| OpenBSD 7.1          | 1        | 0.45%   |
| OpenBSD 7.0          | 1        | 0.45%   |
| OpenBSD 6.9          | 1        | 0.45%   |
| NetBSD 9.99.74       | 1        | 0.45%   |
| NetBSD 9.99.23       | 1        | 0.45%   |
| NetBSD 9.2           | 1        | 0.45%   |
| helloSystem 0.6.0    | 1        | 0.45%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 106      | 61.27%  |
| FreeBSD     | 30       | 17.34%  |
| helloSystem | 19       | 10.98%  |
| OpenBSD     | 9        | 5.2%    |
| GhostBSD    | 4        | 2.31%   |
| NetBSD      | 3        | 1.73%   |
| XigmaNAS    | 1        | 0.58%   |
| pfSense     | 1        | 0.58%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 168      | 98.25%  |
| arm64 | 2        | 1.17%   |
| riscv | 1        | 0.58%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Console          | 125      | 72.25%  |
| helloDesktop     | 20       | 11.56%  |
| KDE5             | 8        | 4.62%   |
| XFCE             | 6        | 3.47%   |
| MATE             | 3        | 1.73%   |
| GNOME            | 3        | 1.73%   |
| fvwm             | 2        | 1.16%   |
| TWM              | 1        | 0.58%   |
| PekWM            | 1        | 0.58%   |
| Openbox          | 1        | 0.58%   |
| Metacity (Marco) | 1        | 0.58%   |
| DWM              | 1        | 0.58%   |
| CDE              | 1        | 0.58%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 125      | 72.67%  |
| X11     | 46       | 26.74%  |
| Wayland | 1        | 0.58%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 140      | 80%     |
| SLiM    | 19       | 10.86%  |
| SDDM    | 7        | 4%      |
| LightDM | 6        | 3.43%   |
| XDM     | 2        | 1.14%   |
| Ly      | 1        | 0.57%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang           | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 126      | 72.83%  |
| en_US          | 23       | 13.29%  |
| C              | 15       | 8.67%   |
| en_GB          | 8        | 4.62%   |
| en_GB.US-ASCII | 1        | 0.58%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 143      | 82.18%  |
| BIOS | 31       | 17.82%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ufs     | 104      | 59.77%  |
| Zfs     | 58       | 33.33%  |
| Ffs     | 9        | 5.17%   |
| Cd9660  | 2        | 1.15%   |
| Unknown | 1        | 0.57%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 157      | 91.28%  |
| MBR     | 10       | 5.81%   |
| Unknown | 5        | 2.91%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 17       | 9.94%   |
| Dell                | 17       | 9.94%   |
| ASUSTek Computer    | 17       | 9.94%   |
| Unknown             | 17       | 9.94%   |
| Intel               | 15       | 8.77%   |
| ASRock              | 11       | 6.43%   |
| Lenovo              | 9        | 5.26%   |
| Hewlett-Packard     | 9        | 5.26%   |
| PC Engines          | 8        | 4.68%   |
| Shuttle             | 6        | 3.51%   |
| Protectli           | 6        | 3.51%   |
| MSI                 | 5        | 2.92%   |
| Fujitsu             | 4        | 2.34%   |
| Biostar             | 3        | 1.75%   |
| Yanling             | 2        | 1.17%   |
| Inventec            | 2        | 1.17%   |
| Apple               | 2        | 1.17%   |
| Acer                | 2        | 1.17%   |
| Winston Marriot     | 1        | 0.58%   |
| Supermicro          | 1        | 0.58%   |
| Sony UK             | 1        | 0.58%   |
| Seeed Studio        | 1        | 0.58%   |
| Quanmax             | 1        | 0.58%   |
| QOTOM               | 1        | 0.58%   |
| PAIQ                | 1        | 0.58%   |
| NU941               | 1        | 0.58%   |
| Jetway              | 1        | 0.58%   |
| Intel CNCTION-IAF   | 1        | 0.58%   |
| IceWhale Technology | 1        | 0.58%   |
| HPE                 | 1        | 0.58%   |
| Foxconn             | 1        | 0.58%   |
| EVGA                | 1        | 0.58%   |
| Deciso              | 1        | 0.58%   |
| AZW                 | 1        | 0.58%   |
| ASRockRack          | 1        | 0.58%   |
| AMI                 | 1        | 0.58%   |
| AMD                 | 1        | 0.58%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                    | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Unknown                                 | 17       | 9.94%   |
| Intel Q3XXG4-P V1.0                     | 8        | 4.68%   |
| PC Engines APU2                         | 5        | 2.92%   |
| ASUS All Series                         | 4        | 2.34%   |
| Protectli FW4B                          | 3        | 1.75%   |
| Dell OptiPlex 7010                      | 3        | 1.75%   |
| Dell OptiPlex 3020                      | 3        | 1.75%   |
| Yanling YL-KBR6L                        | 2        | 1.17%   |
| Protectli FW6                           | 2        | 1.17%   |
| PC Engines apu4                         | 2        | 1.17%   |
| Lenovo ThinkCentre M920s 10SJ0041UK     | 2        | 1.17%   |
| HP Z600 Workstation                     | 2        | 1.17%   |
| HP t620 PLUS Quad Core TC               | 2        | 1.17%   |
| Gigabyte B450M DS3H                     | 2        | 1.17%   |
| Dell OptiPlex 790                       | 2        | 1.17%   |
| Dell OptiPlex 760                       | 2        | 1.17%   |
| Dell OptiPlex 390                       | 2        | 1.17%   |
| ASUS ROG STRIX X570-E GAMING            | 2        | 1.17%   |
| ASRock B550 Phantom Gaming 4            | 2        | 1.17%   |
| Winston Marriot PICO PC(R)              | 1        | 0.58%   |
| Supermicro X8SIU                        | 1        | 0.58%   |
| Sony UK Raspberry Pi 4 Model B          | 1        | 0.58%   |
| Shuttle XH61V                           | 1        | 0.58%   |
| Shuttle XH170                           | 1        | 0.58%   |
| Shuttle SH81R                           | 1        | 0.58%   |
| Shuttle DS67U                           | 1        | 0.58%   |
| Shuttle DS61                            | 1        | 0.58%   |
| Shuttle DS10U                           | 1        | 0.58%   |
| Seeed Studio ODYSSEY-X86J4105           | 1        | 0.58%   |
| Quanmax spo-book TECH QUAD              | 1        | 0.58%   |
| QOTOM Q355G4-P V1.0                     | 1        | 0.58%   |
| Protectli FW4A                          | 1        | 0.58%   |
| PC Engines APU                          | 1        | 0.58%   |
| PAIQ EC3-BT19D4L                        | 1        | 0.58%   |
| NU941 1.0                               | 1        | 0.58%   |
| MSI MS-7C94                             | 1        | 0.58%   |
| MSI MS-7C52                             | 1        | 0.58%   |
| MSI MS-7B86                             | 1        | 0.58%   |
| MSI MS-7B85                             | 1        | 0.58%   |
| MSI MS-7721                             | 1        | 0.58%   |
| Lenovo ThinkPad T530 24292VG            | 1        | 0.58%   |
| Lenovo ThinkCentre M93p 10AAS0F201      | 1        | 0.58%   |
| Lenovo ThinkCentre Edge72 3493DEG       | 1        | 0.58%   |
| Lenovo ThinkCentre E73 10DU0003UK       | 1        | 0.58%   |
| Lenovo ThinkCentre E73 10DS0015UK       | 1        | 0.58%   |
| Lenovo ThinkCentre A55 870577G          | 1        | 0.58%   |
| Lenovo IdeaCentre 310S-08IGM 90HX000PUK | 1        | 0.58%   |
| Jetway 1.0                              | 1        | 0.58%   |
| Inventec Z CLASS                        | 1        | 0.58%   |
| Inventec D CLASS                        | 1        | 0.58%   |
| Intel SHARKBAY                          | 1        | 0.58%   |
| Intel J1900                             | 1        | 0.58%   |
| Intel DH67CL AAG10212-206               | 1        | 0.58%   |
| Intel DH67BL AAG10189-211               | 1        | 0.58%   |
| Intel DH61CR                            | 1        | 0.58%   |
| Intel CRESCENTBAY                       | 1        | 0.58%   |
| Intel CNCTION-IAF CNCTION-IAF           | 1        | 0.58%   |
| Intel CARLOW                            | 1        | 0.58%   |
| IceWhale ZimaBoard 832 ZMB              | 1        | 0.58%   |
| HPE ProLiant MicroServer Gen10          | 1        | 0.58%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                          | Desktops | Percent |
|-------------------------------|----------|---------|
| Unknown                       | 17       | 9.94%   |
| Dell OptiPlex                 | 15       | 8.77%   |
| Intel Q3XXG4-P                | 8        | 4.68%   |
| Lenovo ThinkCentre            | 7        | 4.09%   |
| PC Engines APU2               | 5        | 2.92%   |
| ASUS ROG                      | 4        | 2.34%   |
| ASUS PRIME                    | 4        | 2.34%   |
| ASUS All                      | 4        | 2.34%   |
| Protectli FW4B                | 3        | 1.75%   |
| Yanling YL-KBR6L              | 2        | 1.17%   |
| Protectli FW6                 | 2        | 1.17%   |
| PC Engines apu4               | 2        | 1.17%   |
| HP Z600                       | 2        | 1.17%   |
| HP t620                       | 2        | 1.17%   |
| HP ProDesk                    | 2        | 1.17%   |
| HP EliteDesk                  | 2        | 1.17%   |
| Gigabyte H61M-DS2             | 2        | 1.17%   |
| Gigabyte B450M                | 2        | 1.17%   |
| Fujitsu FUTRO                 | 2        | 1.17%   |
| Fujitsu ESPRIMO               | 2        | 1.17%   |
| ASUS P8Z77-V                  | 2        | 1.17%   |
| ASRock B550                   | 2        | 1.17%   |
| Acer Aspire                   | 2        | 1.17%   |
| Winston Marriot PICO          | 1        | 0.58%   |
| Supermicro X8SIU              | 1        | 0.58%   |
| Sony UK Raspberry             | 1        | 0.58%   |
| Shuttle XH61V                 | 1        | 0.58%   |
| Shuttle XH170                 | 1        | 0.58%   |
| Shuttle SH81R                 | 1        | 0.58%   |
| Shuttle DS67U                 | 1        | 0.58%   |
| Shuttle DS61                  | 1        | 0.58%   |
| Shuttle DS10U                 | 1        | 0.58%   |
| Seeed Studio ODYSSEY-X86J4105 | 1        | 0.58%   |
| Quanmax spo-book              | 1        | 0.58%   |
| QOTOM Q355G4-P                | 1        | 0.58%   |
| Protectli FW4A                | 1        | 0.58%   |
| PC Engines APU                | 1        | 0.58%   |
| PAIQ EC3-BT19D4L              | 1        | 0.58%   |
| NU941 1.0                     | 1        | 0.58%   |
| MSI MS-7C94                   | 1        | 0.58%   |
| MSI MS-7C52                   | 1        | 0.58%   |
| MSI MS-7B86                   | 1        | 0.58%   |
| MSI MS-7B85                   | 1        | 0.58%   |
| MSI MS-7721                   | 1        | 0.58%   |
| Lenovo ThinkPad               | 1        | 0.58%   |
| Lenovo IdeaCentre             | 1        | 0.58%   |
| Jetway 1.0                    | 1        | 0.58%   |
| Inventec Z                    | 1        | 0.58%   |
| Inventec D                    | 1        | 0.58%   |
| Intel SHARKBAY                | 1        | 0.58%   |
| Intel J1900                   | 1        | 0.58%   |
| Intel DH67CL                  | 1        | 0.58%   |
| Intel DH67BL                  | 1        | 0.58%   |
| Intel DH61CR                  | 1        | 0.58%   |
| Intel CRESCENTBAY             | 1        | 0.58%   |
| Intel CNCTION-IAF CNCTION-IAF | 1        | 0.58%   |
| Intel CARLOW                  | 1        | 0.58%   |
| IceWhale ZimaBoard            | 1        | 0.58%   |
| HPE ProLiant                  | 1        | 0.58%   |
| HP ProLiant                   | 1        | 0.58%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2014    | 22       | 12.87%  |
| 2018    | 20       | 11.7%   |
| 2016    | 20       | 11.7%   |
| 2020    | 17       | 9.94%   |
| 2019    | 15       | 8.77%   |
| 2015    | 14       | 8.19%   |
| 2021    | 13       | 7.6%    |
| 2013    | 13       | 7.6%    |
| 2012    | 8        | 4.68%   |
| 2017    | 7        | 4.09%   |
| 2011    | 6        | 3.51%   |
| 2010    | 5        | 2.92%   |
| 2009    | 4        | 2.34%   |
| Unknown | 4        | 2.34%   |
| 2022    | 1        | 0.58%   |
| 2008    | 1        | 0.58%   |
| 2007    | 1        | 0.58%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 171      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 161      | 94.15%  |
| Yes  | 10       | 5.85%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 67       | 38.95%  |
| 4.01-8.0    | 40       | 23.26%  |
| 16.01-24.0  | 35       | 20.35%  |
| 32.01-64.0  | 12       | 6.98%   |
| 2.01-3.0    | 7        | 4.07%   |
| 64.01-256.0 | 6        | 3.49%   |
| 24.01-32.0  | 3        | 1.74%   |
| 3.01-4.0    | 2        | 1.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 0.01-0.5    | 98       | 54.75%  |
| 0.51-1.0    | 46       | 25.7%   |
| 1.01-2.0    | 17       | 9.5%    |
| 2.01-3.0    | 5        | 2.79%   |
| 3.01-4.0    | 4        | 2.23%   |
| Unknown     | 3        | 1.68%   |
| 4.01-8.0    | 2        | 1.12%   |
| 24.01-32.0  | 2        | 1.12%   |
| 32.01-64.0  | 1        | 0.56%   |
| 64.01-256.0 | 1        | 0.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 114      | 65.14%  |
| 2      | 20       | 11.43%  |
| 0      | 15       | 8.57%   |
| 3      | 8        | 4.57%   |
| 4      | 7        | 4%      |
| 5      | 6        | 3.43%   |
| 8      | 3        | 1.71%   |
| 7      | 1        | 0.57%   |
| 6      | 1        | 0.57%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 140      | 81.4%   |
| Yes       | 32       | 18.6%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 168      | 98.25%  |
| No        | 3        | 1.75%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 139      | 80.81%  |
| Yes       | 33       | 19.19%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 148      | 86.05%  |
| Yes       | 24       | 13.95%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| UK      | 171      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| London                | 18       | 9.42%   |
| Newcastle upon Tyne   | 5        | 2.62%   |
| Watford               | 4        | 2.09%   |
| Sheffield             | 4        | 2.09%   |
| Hull                  | 4        | 2.09%   |
| York                  | 3        | 1.57%   |
| Wolverhampton         | 3        | 1.57%   |
| Wittersham            | 3        | 1.57%   |
| Stourbridge           | 3        | 1.57%   |
| Poplar                | 3        | 1.57%   |
| Milton Keynes         | 3        | 1.57%   |
| Mansfield             | 3        | 1.57%   |
| Liverpool             | 3        | 1.57%   |
| Kensington            | 3        | 1.57%   |
| Cambridge             | 3        | 1.57%   |
| Andover               | 3        | 1.57%   |
| Telford               | 2        | 1.05%   |
| Slough                | 2        | 1.05%   |
| Scunthorpe            | 2        | 1.05%   |
| Ruthin                | 2        | 1.05%   |
| Oldham                | 2        | 1.05%   |
| Malton                | 2        | 1.05%   |
| Leeds                 | 2        | 1.05%   |
| Glasgow               | 2        | 1.05%   |
| Egham                 | 2        | 1.05%   |
| Dundee                | 2        | 1.05%   |
| Dulwich               | 2        | 1.05%   |
| Castleford            | 2        | 1.05%   |
| Bristol               | 2        | 1.05%   |
| Birmingham            | 2        | 1.05%   |
| Banbury               | 2        | 1.05%   |
| Yeovil                | 1        | 0.52%   |
| Windsor               | 1        | 0.52%   |
| West Hanningfield     | 1        | 0.52%   |
| Weedon Bec            | 1        | 0.52%   |
| Ware                  | 1        | 0.52%   |
| Walthamstow           | 1        | 0.52%   |
| Upper Norwood         | 1        | 0.52%   |
| Truro                 | 1        | 0.52%   |
| Trowbridge            | 1        | 0.52%   |
| Swindon               | 1        | 0.52%   |
| Swansea               | 1        | 0.52%   |
| Sutton Coldfield      | 1        | 0.52%   |
| Streatham             | 1        | 0.52%   |
| Stratford             | 1        | 0.52%   |
| Stonehouse            | 1        | 0.52%   |
| Stoke Newington       | 1        | 0.52%   |
| St Asaph              | 1        | 0.52%   |
| Southampton           | 1        | 0.52%   |
| South Shields         | 1        | 0.52%   |
| Royal Tunbridge Wells | 1        | 0.52%   |
| Royal Leamington Spa  | 1        | 0.52%   |
| Rotherham             | 1        | 0.52%   |
| Romford               | 1        | 0.52%   |
| Rochdale              | 1        | 0.52%   |
| Rickmansworth         | 1        | 0.52%   |
| Reigate               | 1        | 0.52%   |
| Reading               | 1        | 0.52%   |
| Preston               | 1        | 0.52%   |
| Portsmouth            | 1        | 0.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 28       | 53     | 13.73%  |
| WDC                 | 25       | 40     | 12.25%  |
| Seagate             | 22       | 48     | 10.78%  |
| Kingston            | 21       | 33     | 10.29%  |
| Crucial             | 21       | 29     | 10.29%  |
| SanDisk             | 14       | 16     | 6.86%   |
| Toshiba             | 8        | 30     | 3.92%   |
| Phison              | 7        | 11     | 3.43%   |
| Hoodisk             | 7        | 11     | 3.43%   |
| Transcend           | 5        | 8      | 2.45%   |
| LITEONIT            | 5        | 6      | 2.45%   |
| Intel               | 5        | 6      | 2.45%   |
| SK hynix            | 3        | 3      | 1.47%   |
| OCZ                 | 3        | 4      | 1.47%   |
| Micron Technology   | 3        | 3      | 1.47%   |
| Hitachi             | 3        | 6      | 1.47%   |
| PNY                 | 2        | 10     | 0.98%   |
| OPENBSD             | 2        | 2      | 0.98%   |
| Integral            | 2        | 4      | 0.98%   |
| Corsair             | 2        | 2      | 0.98%   |
| Apacer              | 2        | 3      | 0.98%   |
| A-DATA Technology   | 2        | 3      | 0.98%   |
| Zheino              | 1        | 1      | 0.49%   |
| TCSUNBOW            | 1        | 2      | 0.49%   |
| SPCC                | 1        | 1      | 0.49%   |
| Patriot             | 1        | 4      | 0.49%   |
| Netac               | 1        | 3      | 0.49%   |
| Lexar               | 1        | 1      | 0.49%   |
| KIOXIA              | 1        | 1      | 0.49%   |
| HGST                | 1        | 1      | 0.49%   |
| Gigabyte Technology | 1        | 2      | 0.49%   |
| FORESEE             | 1        | 1      | 0.49%   |
| BIWIN               | 1        | 1      | 0.49%   |
| Apple               | 1        | 1      | 0.49%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB          | 4        | 1.76%   |
| Hoodisk SSD 64GB                     | 4        | 1.76%   |
| Samsung SSD 850 EVO 250GB            | 3        | 1.32%   |
| Phison Sabrent 256GB                 | 3        | 1.32%   |
| Kingston SUV500MS120G 120GB          | 3        | 1.32%   |
| Crucial CT500MX500SSD1 500GB         | 3        | 1.32%   |
| Crucial CT120BX500SSD1 120GB         | 3        | 1.32%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 2        | 0.88%   |
| Toshiba HDWE140 4TB                  | 2        | 0.88%   |
| Seagate ST8000VN0022-2EL112 8TB      | 2        | 0.88%   |
| Seagate ST4000NE001-2MA101 4TB       | 2        | 0.88%   |
| Seagate ST3500418AS 500GB            | 2        | 0.88%   |
| Seagate ST3500312CS 500GB            | 2        | 0.88%   |
| Seagate ST3160318AS 160GB            | 2        | 0.88%   |
| Seagate ST3160310CS 160GB            | 2        | 0.88%   |
| SanDisk SSD PLUS 480GB               | 2        | 0.88%   |
| SanDisk SDSSDA120G 120GB             | 2        | 0.88%   |
| SanDisk SDCFHS-016G                  | 2        | 0.88%   |
| Samsung SSD 860 EVO 500GB            | 2        | 0.88%   |
| Samsung SSD 840 EVO 250GB            | 2        | 0.88%   |
| Samsung SSD 750 EVO 250GB            | 2        | 0.88%   |
| Phison SATA SSD 16GB                 | 2        | 0.88%   |
| OPENBSD SR RAID 1 752GB              | 2        | 0.88%   |
| LITEONIT LCS-128L9S-11 2.5 7mm 128GB | 2        | 0.88%   |
| Kingston SV300S37A240G 240GB         | 2        | 0.88%   |
| Kingston SUV500MS480G 480GB          | 2        | 0.88%   |
| Kingston SUV500MS240G 240GB          | 2        | 0.88%   |
| Kingston SMS200S330G 32GB            | 2        | 0.88%   |
| Intel SSDSA2CT040G3 40GB             | 2        | 0.88%   |
| Hoodisk SSD 32GB                     | 2        | 0.88%   |
| Crucial CT525MX300SSD1 528GB         | 2        | 0.88%   |
| Crucial CT240BX500SSD1 240GB         | 2        | 0.88%   |
| Crucial CT1000MX500SSD1 1TB          | 2        | 0.88%   |
| Crucial CT1000BX500SSD1 1TB          | 2        | 0.88%   |
| Zheino CHN HFmSATA01M 128 128GB      | 1        | 0.44%   |
| WDC WDS500G2B0A-00SM50 500GB         | 1        | 0.44%   |
| WDC WDS250G2B0A-00SM50 250GB         | 1        | 0.44%   |
| WDC WDS240G2G0A-00JH30 240GB         | 1        | 0.44%   |
| WDC WDS100T3X0C-00SJG0 1TB           | 1        | 0.44%   |
| WDC WD800JD-75MSA3 80GB              | 1        | 0.44%   |
| WDC WD5003AZEX-00K3CA0 500GB         | 1        | 0.44%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1        | 0.44%   |
| WDC WD5000AZLX-75K2TA0 500GB         | 1        | 0.44%   |
| WDC WD5000AVDS-63U7B1 500GB          | 1        | 0.44%   |
| WDC WD5000AAKX-221CA1 500GB          | 1        | 0.44%   |
| WDC WD5000AAKS-60WWPA0 500GB         | 1        | 0.44%   |
| WDC WD5000AAKS-00A7B2 500GB          | 1        | 0.44%   |
| WDC WD4001FAEX-00MJRA0 4TB           | 1        | 0.44%   |
| WDC WD3200BEVT-22A23T0 320GB         | 1        | 0.44%   |
| WDC WD3200AAJS-22B4A0 320GB          | 1        | 0.44%   |
| WDC WD3000JS-63PDB1 304GB            | 1        | 0.44%   |
| WDC WD2503ABYX-01WERA1 256GB         | 1        | 0.44%   |
| WDC WD2500AAJS-75M0A0 250GB          | 1        | 0.44%   |
| WDC WD1602ABJS-43P5A0 160GB          | 1        | 0.44%   |
| WDC WD10SPZX-22Z10T1 1TB             | 1        | 0.44%   |
| WDC WD10SPCX-24HWST1 1TB             | 1        | 0.44%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1        | 0.44%   |
| WDC WD10JMVW-11AJGS0 1TB             | 1        | 0.44%   |
| WDC WD10EZRX-00A8LB0 1TB             | 1        | 0.44%   |
| WDC WD10EZEX-00WN4A0 1TB             | 1        | 0.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 22       | 48     | 38.6%   |
| WDC                 | 20       | 32     | 35.09%  |
| Toshiba             | 6        | 23     | 10.53%  |
| Samsung Electronics | 3        | 3      | 5.26%   |
| Hitachi             | 3        | 6      | 5.26%   |
| OPENBSD             | 2        | 2      | 3.51%   |
| HGST                | 1        | 1      | 1.75%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 21       | 37     | 15.79%  |
| Kingston            | 21       | 33     | 15.79%  |
| Crucial             | 19       | 27     | 14.29%  |
| SanDisk             | 14       | 16     | 10.53%  |
| Hoodisk             | 7        | 11     | 5.26%   |
| Transcend           | 5        | 8      | 3.76%   |
| LITEONIT            | 5        | 6      | 3.76%   |
| Phison              | 4        | 5      | 3.01%   |
| Intel               | 4        | 4      | 3.01%   |
| WDC                 | 3        | 4      | 2.26%   |
| OCZ                 | 3        | 4      | 2.26%   |
| Micron Technology   | 3        | 3      | 2.26%   |
| Toshiba             | 2        | 7      | 1.5%    |
| SK hynix            | 2        | 2      | 1.5%    |
| PNY                 | 2        | 8      | 1.5%    |
| Integral            | 2        | 4      | 1.5%    |
| Corsair             | 2        | 2      | 1.5%    |
| Apacer              | 2        | 3      | 1.5%    |
| A-DATA Technology   | 2        | 3      | 1.5%    |
| Zheino              | 1        | 1      | 0.75%   |
| TCSUNBOW            | 1        | 2      | 0.75%   |
| SPCC                | 1        | 1      | 0.75%   |
| Patriot             | 1        | 4      | 0.75%   |
| Netac               | 1        | 3      | 0.75%   |
| Lexar               | 1        | 1      | 0.75%   |
| Gigabyte Technology | 1        | 2      | 0.75%   |
| FORESEE             | 1        | 1      | 0.75%   |
| BIWIN               | 1        | 1      | 0.75%   |
| Apple               | 1        | 1      | 0.75%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 119      | 204    | 65.38%  |
| HDD  | 46       | 115    | 25.27%  |
| NVMe | 17       | 31     | 9.34%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 148      | 319    | 89.7%   |
| NVMe | 17       | 31     | 10.3%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 137      | 233    | 77.84%  |
| 0.51-1.0   | 19       | 30     | 10.8%   |
| 1.01-2.0   | 7        | 10     | 3.98%   |
| 3.01-4.0   | 6        | 31     | 3.41%   |
| 4.01-10.0  | 6        | 14     | 3.41%   |
| 2.01-3.0   | 1        | 1      | 0.57%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 72       | 40.45%  |
| 1-20       | 28       | 15.73%  |
| 251-500    | 26       | 14.61%  |
| 21-50      | 23       | 12.92%  |
| 51-100     | 20       | 11.24%  |
| 501-1000   | 6        | 3.37%   |
| 1001-2000  | 3        | 1.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 157      | 89.71%  |
| 21-50   | 9        | 5.14%   |
| 51-100  | 4        | 2.29%   |
| 101-250 | 3        | 1.71%   |
| 251-500 | 2        | 1.14%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                            | Desktops | Drives | Percent |
|--------------------------------------------------|----------|--------|---------|
| Seagate ST3160310CS 160GB                        | 2        | 2      | 7.69%   |
| SanDisk SSD PLUS 480GB                           | 2        | 2      | 7.69%   |
| Crucial CT525MX300SSD1 528GB                     | 2        | 3      | 7.69%   |
| WDC WD5000AAKX-221CA1 500GB                      | 1        | 1      | 3.85%   |
| WDC WD5000AAKS-60WWPA0 500GB                     | 1        | 1      | 3.85%   |
| WDC WD4001FAEX-00MJRA0 4TB                       | 1        | 4      | 3.85%   |
| WDC WD3200BEVT-22A23T0 320GB                     | 1        | 3      | 3.85%   |
| WDC WD3200AAJS-22B4A0 320GB                      | 1        | 1      | 3.85%   |
| WDC WD10JMVW-11AJGS0 1TB                         | 1        | 1      | 3.85%   |
| Transcend TS256GSSD320 256GB                     | 1        | 1      | 3.85%   |
| Toshiba MD04ACA400 4TB                           | 1        | 1      | 3.85%   |
| Toshiba HDWE140 4TB                              | 1        | 8      | 3.85%   |
| Toshiba DT01ACA200 2TB                           | 1        | 1      | 3.85%   |
| Toshiba DT01ABA300 3TB                           | 1        | 1      | 3.85%   |
| Seagate ST3500418AS 500GB                        | 1        | 2      | 3.85%   |
| Seagate ST2000LM015-2E8174 2TB                   | 1        | 1      | 3.85%   |
| SanDisk SSD P4 16GB                              | 1        | 1      | 3.85%   |
| SanDisk SDCFHS-016G                              | 1        | 1      | 3.85%   |
| Samsung Electronics SSD PM810 2.5-inch 7mm 256GB | 1        | 2      | 3.85%   |
| Samsung Electronics MZHPV512HDGL-00000 512GB     | 1        | 1      | 3.85%   |
| Samsung Electronics HM160HI 160GB                | 1        | 1      | 3.85%   |
| Kingston SV200S3128G 128GB                       | 1        | 1      | 3.85%   |
| A-DATA Technology SU630 240GB                    | 1        | 2      | 3.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 6        | 11     | 24%     |
| Seagate             | 4        | 5      | 16%     |
| SanDisk             | 4        | 4      | 16%     |
| Toshiba             | 3        | 11     | 12%     |
| Samsung Electronics | 3        | 4      | 12%     |
| Crucial             | 2        | 3      | 8%      |
| Transcend           | 1        | 1      | 4%      |
| Kingston            | 1        | 1      | 4%      |
| A-DATA Technology   | 1        | 2      | 4%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 6        | 11     | 42.86%  |
| Seagate             | 4        | 5      | 28.57%  |
| Toshiba             | 3        | 11     | 21.43%  |
| Samsung Electronics | 1        | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 14       | 28     | 56%     |
| SSD  | 11       | 14     | 44%     |

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
| Works    | 142      | 297    | 83.53%  |
| Malfunc  | 22       | 42     | 12.94%  |
| Detected | 6        | 11     | 3.53%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 118      | 55.66%  |
| AMD                       | 49       | 23.11%  |
| Samsung Electronics       | 9        | 4.25%   |
| ASMedia Technology        | 8        | 3.77%   |
| Marvell Technology Group  | 6        | 2.83%   |
| SanDisk                   | 5        | 2.36%   |
| Phison Electronics        | 4        | 1.89%   |
| Nvidia                    | 2        | 0.94%   |
| Micron/Crucial Technology | 2        | 0.94%   |
| Broadcom / LSI            | 2        | 0.94%   |
| Adaptec                   | 2        | 0.94%   |
| VIA Technologies          | 1        | 0.47%   |
| Toshiba                   | 1        | 0.47%   |
| SK hynix                  | 1        | 0.47%   |
| Silicon Motion            | 1        | 0.47%   |
| Silicon Image             | 1        | 0.47%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 32       | 13.39%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 15       | 6.28%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 12       | 5.02%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 11       | 4.6%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 9        | 3.77%   |
| AMD 400 Series Chipset SATA Controller                                                  | 8        | 3.35%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 7        | 2.93%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7        | 2.93%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 6        | 2.51%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 6        | 2.51%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6        | 2.51%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 6        | 2.51%   |
| AMD 500 Series Chipset SATA Controller                                                  | 6        | 2.51%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5        | 2.09%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 5        | 2.09%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5        | 2.09%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 2.09%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5        | 2.09%   |
| Phison E12 NVMe Controller                                                              | 4        | 1.67%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 4        | 1.67%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 1.67%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 4        | 1.67%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 1.26%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 1.26%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 1.26%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 1.26%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2        | 0.84%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 2        | 0.84%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 2        | 0.84%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2        | 0.84%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 0.84%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 2        | 0.84%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 2        | 0.84%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 0.84%   |
| AMD FCH SATA Controller D                                                               | 2        | 0.84%   |
| Adaptec AIC-7850T/7856T [AVA-2902/4/6 / AHA-2910]                                       | 2        | 0.84%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 0.42%   |
| Toshiba XG6 NVMe SSD Controller                                                         | 1        | 0.42%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 1        | 0.42%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 0.42%   |
| Silicon Image SiI 3512 [SATALink/SATARaid] Serial ATA Controller                        | 1        | 0.42%   |
| SanDisk WD Blue SN570 NVMe SSD                                                          | 1        | 0.42%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 1        | 0.42%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.42%   |
| Samsung SM951 AHCI                                                                      | 1        | 0.42%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.42%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.42%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 0.42%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 0.42%   |
| Nvidia GeForce 7100/nForce 630i SATA                                                    | 1        | 0.42%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller                   | 1        | 0.42%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 1        | 0.42%   |
| Marvell Group 88SE9170 PCIe 2.0 x1 2-port SATA 6 Gb/s Controller                        | 1        | 0.42%   |
| Marvell Group 88SE912x SATA 6Gb/s Controller [IDE mode]                                 | 1        | 0.42%   |
| Intel SSD 660P Series                                                                   | 1        | 0.42%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 0.42%   |
| Intel Comet Lake PCH-H RAID                                                             | 1        | 0.42%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 1        | 0.42%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 1        | 0.42%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1        | 0.42%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 151      | 75.88%  |
| NVMe | 20       | 10.05%  |
| IDE  | 20       | 10.05%  |
| RAID | 5        | 2.51%   |
| SCSI | 3        | 1.51%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Intel    | 118      | 69.01%  |
| AMD      | 50       | 29.24%  |
| Research | 1        | 0.58%   |
| ARM      | 1        | 0.58%   |
| Unknown  | 1        | 0.58%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD GX-412TC SOC                            | 7        | 4.02%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 6        | 3.45%   |
| Intel Core i5-5250U CPU @ 1.60GHz           | 4        | 2.3%    |
| Intel Celeron CPU J3160 @ 1.60GHz           | 4        | 2.3%    |
| Intel Atom CPU E3845 @ 1.91GHz              | 4        | 2.3%    |
| AMD Ryzen 5 3600 6-Core Processor           | 4        | 2.3%    |
| Intel Core i5-9500 CPU @ 3.00GHz            | 3        | 1.72%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 3        | 1.72%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 3        | 1.72%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 3        | 1.72%   |
| Intel Celeron CPU 3865U @ 1.80GHz           | 3        | 1.72%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 3        | 1.72%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 3        | 1.72%   |
| Intel Core i7-4500U CPU @ 1.80GHz           | 2        | 1.15%   |
| Intel Core i7-2600 CPU @ 3.40GH             | 2        | 1.15%   |
| Intel Core i5-4590S CPU @ 3.00GHz           | 2        | 1.15%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2        | 1.15%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2        | 1.15%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 2        | 1.15%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 1.15%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 2        | 1.15%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 2        | 1.15%   |
| Intel Core i3-2100 CPU @ 3.10GH             | 2        | 1.15%   |
| Intel Core 2 Duo                            | 2        | 1.15%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 2        | 1.15%   |
| Intel Celeron CPU N3450 @ 1.10GHz           | 2        | 1.15%   |
| Intel Celeron CPU J3455 @ 1.50GHz           | 2        | 1.15%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 2        | 1.15%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 2        | 1.15%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 2        | 1.15%   |
| AMD GX-420CA SOC with Radeon HD Graphics    | 2        | 1.15%   |
| AMD GX-416RA SOC                            | 2        | 1.15%   |
| Research Morello SoC r0p0                   | 1        | 0.57%   |
| Intel Xeon CPU X5690 @ 3.47GHz              | 1        | 0.57%   |
| Intel Xeon CPU X5570 @ 2.93GHz              | 1        | 0.57%   |
| Intel Xeon CPU X3450 @ 2.67GHz              | 1        | 0.57%   |
| Intel Xeon CPU E5530 @ 2.40GHz              | 1        | 0.57%   |
| Intel Xeon CPU E5520 @ 2.27GHz              | 1        | 0.57%   |
| Intel Xeon CPU E31265L @ 2.40GHz            | 1        | 0.57%   |
| Intel Xeon CPU E3-1265L v3 @ 2.50GHz        | 1        | 0.57%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz         | 1        | 0.57%   |
| Intel Xeon CPU E3-1225 V2 @ 3.20GHz         | 1        | 0.57%   |
| Intel Xeon                                  | 1        | 0.57%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz    | 1        | 0.57%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1        | 0.57%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 1        | 0.57%   |
| Intel Core i9-9900X CPU @ 3.50GHz           | 1        | 0.57%   |
| Intel Core i9-10850K CPU @ 3.60GHz          | 1        | 0.57%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 0.57%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1        | 0.57%   |
| Intel Core i7-6700T CPU @ 2.80GHz           | 1        | 0.57%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 0.57%   |
| Intel Core i7-4770S CPU @ 3.10GHz           | 1        | 0.57%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1        | 0.57%   |
| Intel Core i7-3770S CPU @ 3.10GHz           | 1        | 0.57%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1        | 0.57%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 0.57%   |
| Intel Core i7-3610QM CPU @ 2.30GHz          | 1        | 0.57%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1        | 0.57%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 1        | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 29       | 16.76%  |
| Intel Celeron           | 27       | 15.61%  |
| Intel Core i3           | 22       | 12.72%  |
| Intel Core i7           | 15       | 8.67%   |
| AMD GX                  | 13       | 7.51%   |
| Intel Xeon              | 10       | 5.78%   |
| AMD Ryzen 5             | 10       | 5.78%   |
| Intel Atom              | 5        | 2.89%   |
| Intel Core 2 Duo        | 4        | 2.31%   |
| AMD Ryzen 7             | 4        | 2.31%   |
| AMD Ryzen 3             | 3        | 1.73%   |
| AMD G                   | 3        | 1.73%   |
| AMD FX                  | 3        | 1.73%   |
| Other                   | 2        | 1.16%   |
| Intel Core i9           | 2        | 1.16%   |
| Intel Core 2 Quad       | 2        | 1.16%   |
| AMD Ryzen 9             | 2        | 1.16%   |
| AMD Athlon              | 2        | 1.16%   |
| AMD A4                  | 2        | 1.16%   |
| Intel Pentium Silver    | 1        | 0.58%   |
| Intel Pentium Dual-Core | 1        | 0.58%   |
| Intel Pentium           | 1        | 0.58%   |
| Intel 686-class         | 1        | 0.58%   |
| ARM Cortex              | 1        | 0.58%   |
| AMD Ryzen Threadripper  | 1        | 0.58%   |
| AMD Ryzen 7 PRO         | 1        | 0.58%   |
| AMD Phenom II X6        | 1        | 0.58%   |
| AMD Phenom              | 1        | 0.58%   |
| AMD Opteron             | 1        | 0.58%   |
| AMD E2                  | 1        | 0.58%   |
| AMD A8                  | 1        | 0.58%   |
| AMD A6                  | 1        | 0.58%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 80       | 45.71%  |
| 2       | 56       | 32%     |
| 12      | 10       | 5.71%   |
| 6       | 8        | 4.57%   |
| Unknown | 6        | 3.43%   |
| 16      | 5        | 2.86%   |
| 8       | 5        | 2.86%   |
| 24      | 3        | 1.71%   |
| 10      | 2        | 1.14%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 165      | 96.49%  |
| Unknown | 4        | 2.34%   |
| 2       | 2        | 1.17%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 109      | 63.01%  |
| 2       | 58       | 33.53%  |
| Unknown | 6        | 3.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 24       | 13.95%  |
| Silvermont    | 18       | 10.47%  |
| KabyLake      | 16       | 9.3%    |
| SandyBridge   | 11       | 6.4%    |
| IvyBridge     | 11       | 6.4%    |
| Zen 2         | 10       | 5.81%   |
| Penryn        | 8        | 4.65%   |
| Jaguar        | 8        | 4.65%   |
| Zen 3         | 7        | 4.07%   |
| Puma          | 7        | 4.07%   |
| Skylake       | 6        | 3.49%   |
| Broadwell     | 6        | 3.49%   |
| Piledriver    | 5        | 2.91%   |
| Goldmont      | 5        | 2.91%   |
| Nehalem       | 4        | 2.33%   |
| Goldmont plus | 4        | 2.33%   |
| Bobcat        | 4        | 2.33%   |
| Unknown       | 4        | 2.33%   |
| Zen           | 3        | 1.74%   |
| Zen+          | 2        | 1.16%   |
| K10           | 2        | 1.16%   |
| CometLake     | 2        | 1.16%   |
| Westmere      | 1        | 0.58%   |
| Excavator     | 1        | 0.58%   |
| Core          | 1        | 0.58%   |
| Bulldozer     | 1        | 0.58%   |
| Bonnell       | 1        | 0.58%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 100      | 61.35%  |
| AMD                        | 34       | 20.86%  |
| Nvidia                     | 26       | 15.95%  |
| Matrox Electronics Systems | 2        | 1.23%   |
| ASPEED Technology          | 1        | 0.61%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 12       | 7.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 11       | 6.63%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9        | 5.42%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 7        | 4.22%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6        | 3.61%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5        | 3.01%   |
| Intel HD Graphics 500                                                                    | 5        | 3.01%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 5        | 3.01%   |
| Intel HD Graphics 620                                                                    | 4        | 2.41%   |
| Intel HD Graphics 6000                                                                   | 4        | 2.41%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4        | 2.41%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3        | 1.81%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 3        | 1.81%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 3        | 1.81%   |
| Intel HD Graphics 530                                                                    | 3        | 1.81%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3        | 1.81%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3        | 1.81%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 3        | 1.81%   |
| AMD Cezanne                                                                              | 3        | 1.81%   |
| Nvidia GT218 [GeForce 210]                                                               | 2        | 1.2%    |
| Nvidia GF119 [GeForce GT 520]                                                            | 2        | 1.2%    |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 2        | 1.2%    |
| Intel HD Graphics 5500                                                                   | 2        | 1.2%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 1.2%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2        | 1.2%    |
| AMD Kabini [Radeon HD 8400E]                                                             | 2        | 1.2%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2        | 1.2%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1        | 0.6%    |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                                   | 1        | 0.6%    |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1        | 0.6%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1        | 0.6%    |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 1        | 0.6%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 1        | 0.6%    |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1        | 0.6%    |
| Nvidia GM107 [GeForce GTX 750]                                                           | 1        | 0.6%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1        | 0.6%    |
| Nvidia GK107GL [Quadro K2000]                                                            | 1        | 0.6%    |
| Nvidia GK107 [GeForce GT 640]                                                            | 1        | 0.6%    |
| Nvidia GF114 [GeForce GTX 560 Ti]                                                        | 1        | 0.6%    |
| Nvidia GF108M [NVS 5400M]                                                                | 1        | 0.6%    |
| Nvidia GF108GL [Quadro 600]                                                              | 1        | 0.6%    |
| Nvidia GF106GL [Quadro 2000]                                                             | 1        | 0.6%    |
| Nvidia GA104 [GeForce RTX 3070]                                                          | 1        | 0.6%    |
| Nvidia G96 [GeForce GT 120 Mac Edition]                                                  | 1        | 0.6%    |
| Nvidia G92 [GeForce GTS 250]                                                             | 1        | 0.6%    |
| Nvidia G84 [GeForce 8600 GT]                                                             | 1        | 0.6%    |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1        | 0.6%    |
| Matrox Electronics Systems MGA G200EH                                                    | 1        | 0.6%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1        | 0.6%    |
| Intel UHD Graphics 620                                                                   | 1        | 0.6%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1        | 0.6%    |
| Intel HD Graphics 610                                                                    | 1        | 0.6%    |
| Intel HD Graphics 510                                                                    | 1        | 0.6%    |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1        | 0.6%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1        | 0.6%    |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1        | 0.6%    |
| Intel 82946GZ/GL Integrated Graphics Controller                                          | 1        | 0.6%    |
| ASPEED Technology ASPEED Graphics Family                                                 | 1        | 0.6%    |
| AMD Wrestler [Radeon HD 7340]                                                            | 1        | 0.6%    |
| AMD Wrestler [Radeon HD 6320]                                                            | 1        | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| 1 x Intel   | 97       | 56.4%   |
| 1 x AMD     | 31       | 18.02%  |
| 1 x Nvidia  | 25       | 14.53%  |
| Other       | 13       | 7.56%   |
| 1 x Matrox  | 2        | 1.16%   |
| Intel + AMD | 2        | 1.16%   |
| 2 x Intel   | 1        | 0.58%   |
| 1 x ASPEED  | 1        | 0.58%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 142      | 82.56%  |
| Unknown     | 18       | 10.47%  |
| Proprietary | 12       | 6.98%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 153      | 88.44%  |
| 3.01-4.0   | 5        | 2.89%   |
| 1.01-2.0   | 5        | 2.89%   |
| 0.51-1.0   | 5        | 2.89%   |
| 7.01-8.0   | 3        | 1.73%   |
| 5.01-6.0   | 1        | 0.58%   |
| 8.01-16.0  | 1        | 0.58%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 8        | 22.22%  |
| Samsung Electronics | 5        | 13.89%  |
| Hewlett-Packard     | 4        | 11.11%  |
| BenQ                | 4        | 11.11%  |
| AOC                 | 4        | 11.11%  |
| Iiyama              | 3        | 8.33%   |
| Acer                | 2        | 5.56%   |
| RS                  | 1        | 2.78%   |
| Pixio               | 1        | 2.78%   |
| OEM                 | 1        | 2.78%   |
| Lenovo              | 1        | 2.78%   |
| Goldstar            | 1        | 2.78%   |
| AVX                 | 1        | 2.78%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Hewlett-Packard ZR24w HWP286A 1920x1200 540x350mm 25.3-inch          | 2        | 5.13%   |
| BenQ GL2450 BNQ78A4 1920x1080 530x300mm 24.0-inch                    | 2        | 5.13%   |
| Samsung Electronics U28D590 SAM0B80 3840x2160 610x350mm 27.7-inch    | 1        | 2.56%   |
| Samsung Electronics T24D390 SAM0B6E 1920x1080 520x290mm 23.4-inch    | 1        | 2.56%   |
| Samsung Electronics SyncMaster SAM030D 1680x1050 470x300mm 22.0-inch | 1        | 2.56%   |
| Samsung Electronics SyncMaster SAM011F 1280x1024 380x300mm 19.1-inch | 1        | 2.56%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch    | 1        | 2.56%   |
| RS LE2262 BTC2262 1680x1050 470x290mm 21.7-inch                      | 1        | 2.56%   |
| Pixio PX247 PNS0247 1920x1080 520x310mm 23.8-inch                    | 1        | 2.56%   |
| OEM 32W_LCD_TV OEM3700 1920x540                                      | 1        | 2.56%   |
| Lenovo LCD Monitor LEN0990 1440x900 410x260mm 19.1-inch              | 1        | 2.56%   |
| Iiyama PL4071UH IVM000A 3840x2160 880x490mm 39.7-inch                | 1        | 2.56%   |
| Iiyama PL2390 IVM562D 1920x1080 510x290mm 23.1-inch                  | 1        | 2.56%   |
| Iiyama PL2283H IVM562E 1920x1080 500x290mm 22.8-inch                 | 1        | 2.56%   |
| Iiyama PL2273HD IVM561A 1920x1080 480x270mm 21.7-inch                | 1        | 2.56%   |
| Hewlett-Packard w1907 HWP26A2 1440x900 410x260mm 19.1-inch           | 1        | 2.56%   |
| Hewlett-Packard 2310e HWP2909 1920x1080 510x290mm 23.1-inch          | 1        | 2.56%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch           | 1        | 2.56%   |
| Dell U4919DW DELA107 3840x1080 1200x340mm 49.1-inch                  | 1        | 2.56%   |
| Dell U3415W DELA0A6 3440x1440 800x330mm 34.1-inch                    | 1        | 2.56%   |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                    | 1        | 2.56%   |
| Dell LCD Monitor S2740L 1920x1080                                    | 1        | 2.56%   |
| Dell LCD Monitor P2214H 1920x1080                                    | 1        | 2.56%   |
| Dell LCD Monitor DELD110 2560x1440 700x400mm 31.7-inch               | 1        | 2.56%   |
| Dell LCD Monitor 1908FP 3200x1080                                    | 1        | 2.56%   |
| Dell E196FP DELA015 1280x1024 380x300mm 19.1-inch                    | 1        | 2.56%   |
| BenQ LCD Monitor DL2215                                              | 1        | 2.56%   |
| BenQ GW2475H BNQ78EE 1920x1080 530x300mm 24.0-inch                   | 1        | 2.56%   |
| AVX AVERMEDIA_HD AVX0003 1920x1080 380x300mm 19.1-inch               | 1        | 2.56%   |
| AOC N22W AOC220A 1680x1050 470x300mm 22.0-inch                       | 1        | 2.56%   |
| AOC LCD Monitor 2460X 5760x1200                                      | 1        | 2.56%   |
| AOC LCD Monitor 2460X                                                | 1        | 2.56%   |
| AOC G2460 AOC2460 1920x1080 530x300mm 24.0-inch                      | 1        | 2.56%   |
| AOC 2280W AOC2280 1920x1080 480x270mm 21.7-inch                      | 1        | 2.56%   |
| AOC 2070W AOC2070 1600x900 430x240mm 19.4-inch                       | 1        | 2.56%   |
| Acer S271HL ACR02CA 1920x1080 600x340mm 27.2-inch                    | 1        | 2.56%   |
| Acer ET241Y ACR056C 1920x1080 480x270mm 21.7-inch                    | 1        | 2.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 16       | 42.11%  |
| 3840x2160 (4K)     | 3        | 7.89%   |
| 1920x1200 (WUXGA)  | 3        | 7.89%   |
| 1680x1050 (WSXGA+) | 3        | 7.89%   |
| 1440x900 (WXGA+)   | 2        | 5.26%   |
| 1280x1024 (SXGA)   | 2        | 5.26%   |
| Unknown            | 2        | 5.26%   |
| 5760x1200          | 1        | 2.63%   |
| 3840x1080          | 1        | 2.63%   |
| 3440x1440          | 1        | 2.63%   |
| 3200x1080          | 1        | 2.63%   |
| 2560x1440 (QHD)    | 1        | 2.63%   |
| 1920x540           | 1        | 2.63%   |
| 1600x900 (HD+)     | 1        | 2.63%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 19      | 6        | 16.22%  |
| 24      | 5        | 13.51%  |
| 23      | 5        | 13.51%  |
| Unknown | 5        | 13.51%  |
| 21      | 4        | 10.81%  |
| 27      | 3        | 8.11%   |
| 22      | 3        | 8.11%   |
| 25      | 2        | 5.41%   |
| 49      | 1        | 2.7%    |
| 39      | 1        | 2.7%    |
| 34      | 1        | 2.7%    |
| 31      | 1        | 2.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 14       | 40%     |
| 401-500     | 8        | 22.86%  |
| Unknown     | 5        | 14.29%  |
| 351-400     | 3        | 8.57%   |
| 601-700     | 2        | 5.71%   |
| 801-900     | 1        | 2.86%   |
| 701-800     | 1        | 2.86%   |
| 1001-1500   | 1        | 2.86%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 18       | 50%     |
| 16/10   | 6        | 16.67%  |
| Unknown | 4        | 11.11%  |
| 5/4     | 3        | 8.33%   |
| 32/9    | 2        | 5.56%   |
| 3/2     | 2        | 5.56%   |
| 21/9    | 1        | 2.78%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 13       | 38.24%  |
| 151-200        | 6        | 17.65%  |
| Unknown        | 5        | 14.71%  |
| 301-350        | 3        | 8.82%   |
| 251-300        | 3        | 8.82%   |
| 351-500        | 2        | 5.88%   |
| 501-1000       | 2        | 5.88%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 23       | 63.89%  |
| 101-120 | 6        | 16.67%  |
| Unknown | 5        | 13.89%  |
| 161-240 | 1        | 2.78%   |
| 121-160 | 1        | 2.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 134      | 77.91%  |
| 1     | 33       | 19.19%  |
| 2     | 4        | 2.33%   |
| 3     | 1        | 0.58%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Intel                             | 118      | 53.88%  |
| Realtek Semiconductor             | 72       | 32.88%  |
| Qualcomm Atheros                  | 9        | 4.11%   |
| Broadcom                          | 9        | 4.11%   |
| Ralink Technology                 | 2        | 0.91%   |
| Ralink                            | 2        | 0.91%   |
| U-Blox                            | 1        | 0.46%   |
| Nvidia                            | 1        | 0.46%   |
| Marvell Technology Group          | 1        | 0.46%   |
| Ericsson Business Mobile Networks | 1        | 0.46%   |
| Bluegiga Technologies             | 1        | 0.46%   |
| ASUSTek Computer                  | 1        | 0.46%   |
| American Megatrends               | 1        | 0.46%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 65       | 24.16%  |
| Intel I211 Gigabit Network Connection                                         | 36       | 13.38%  |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 12       | 4.46%   |
| Intel 82574L Gigabit Network Connection                                       | 11       | 4.09%   |
| Intel I210 Gigabit Network Connection                                         | 10       | 3.72%   |
| Realtek RTL8125 2.5GbE Controller                                             | 9        | 3.35%   |
| Intel I350 Gigabit Network Connection                                         | 7        | 2.6%    |
| Intel 82580 Gigabit Network Connection                                        | 7        | 2.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 7        | 2.6%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 7        | 2.6%    |
| Intel Wi-Fi 6 AX200                                                           | 5        | 1.86%   |
| Intel Ethernet Connection I217-LM                                             | 5        | 1.86%   |
| Intel Ethernet Connection (2) I219-V                                          | 5        | 1.86%   |
| Intel 82583V Gigabit Network Connection                                       | 5        | 1.86%   |
| Intel 82576 Gigabit Network Connection                                        | 5        | 1.86%   |
| Intel 82579V Gigabit Network Connection                                       | 4        | 1.49%   |
| Intel Wireless 7260                                                           | 3        | 1.12%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 3        | 1.12%   |
| Intel Ethernet Connection (7) I219-LM                                         | 3        | 1.12%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 2        | 0.74%   |
| Intel Wireless-AC 9260                                                        | 2        | 0.74%   |
| Intel Wireless 3160                                                           | 2        | 0.74%   |
| Intel Ethernet Controller X550                                                | 2        | 0.74%   |
| Intel Ethernet Connection I217-V                                              | 2        | 0.74%   |
| Intel Ethernet Connection (2) I219-LM                                         | 2        | 0.74%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 2        | 0.74%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 2        | 0.74%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 2        | 0.74%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2        | 0.74%   |
| U-Blox [u-blox 8]                                                             | 1        | 0.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.37%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.37%   |
| Ralink RT3072 Wireless Adapter                                                | 1        | 0.37%   |
| Ralink MT7601U Wireless Adapter                                               | 1        | 0.37%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 1        | 0.37%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1        | 0.37%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1        | 0.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1        | 0.37%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1        | 0.37%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1        | 0.37%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 1        | 0.37%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1        | 0.37%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn]        | 1        | 0.37%   |
| Nvidia MCP73 Ethernet                                                         | 1        | 0.37%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                       | 1        | 0.37%   |
| Intel Wireless 7265                                                           | 1        | 0.37%   |
| Intel Wireless 3165                                                           | 1        | 0.37%   |
| Intel I350 Gigabit Fiber Network Connection                                   | 1        | 0.37%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 1        | 0.37%   |
| Intel Ethernet Controller I225-V                                              | 1        | 0.37%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 1        | 0.37%   |
| Intel Ethernet Connection I219-LM                                             | 1        | 0.37%   |
| Intel Ethernet Connection (6) I219-LM                                         | 1        | 0.37%   |
| Intel Ethernet Connection (11) I219-V                                         | 1        | 0.37%   |
| Intel DH8900CC Null Device                                                    | 1        | 0.37%   |
| Intel Centrino Wireless-N 2230                                                | 1        | 0.37%   |
| Intel Centrino Ultimate-N 6300                                                | 1        | 0.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 1        | 0.37%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 1        | 0.37%   |
| Intel 82571EB Gigabit Ethernet Controller                                     | 1        | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 18       | 54.55%  |
| Qualcomm Atheros      | 7        | 21.21%  |
| Realtek Semiconductor | 2        | 6.06%   |
| Ralink Technology     | 2        | 6.06%   |
| Ralink                | 2        | 6.06%   |
| Broadcom              | 1        | 3.03%   |
| ASUSTek Computer      | 1        | 3.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                    | 5        | 15.15%  |
| Intel Wireless 7260                                                    | 3        | 9.09%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                       | 2        | 6.06%   |
| Intel Wireless-AC 9260                                                 | 2        | 6.06%   |
| Intel Wireless 3160                                                    | 2        | 6.06%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 2        | 6.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 1        | 3.03%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 1        | 3.03%   |
| Ralink RT3072 Wireless Adapter                                         | 1        | 3.03%   |
| Ralink MT7601U Wireless Adapter                                        | 1        | 3.03%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                              | 1        | 3.03%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                              | 1        | 3.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 1        | 3.03%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 1        | 3.03%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 1        | 3.03%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 1        | 3.03%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn] | 1        | 3.03%   |
| Intel Wireless 7265                                                    | 1        | 3.03%   |
| Intel Wireless 3165                                                    | 1        | 3.03%   |
| Intel Centrino Wireless-N 2230                                         | 1        | 3.03%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 1        | 3.03%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                 | 1        | 3.03%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]              | 1        | 3.03%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 117      | 59.09%  |
| Realtek Semiconductor    | 68       | 34.34%  |
| Broadcom                 | 8        | 4.04%   |
| Qualcomm Atheros         | 2        | 1.01%   |
| Nvidia                   | 1        | 0.51%   |
| Marvell Technology Group | 1        | 0.51%   |
| American Megatrends      | 1        | 0.51%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 65       | 28.38%  |
| Intel I211 Gigabit Network Connection                                         | 36       | 15.72%  |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 12       | 5.24%   |
| Intel 82574L Gigabit Network Connection                                       | 11       | 4.8%    |
| Intel I210 Gigabit Network Connection                                         | 10       | 4.37%   |
| Realtek RTL8125 2.5GbE Controller                                             | 7        | 3.06%   |
| Intel I350 Gigabit Network Connection                                         | 7        | 3.06%   |
| Intel 82580 Gigabit Network Connection                                        | 7        | 3.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 7        | 3.06%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 7        | 3.06%   |
| Intel Ethernet Connection I217-LM                                             | 5        | 2.18%   |
| Intel Ethernet Connection (2) I219-V                                          | 5        | 2.18%   |
| Intel 82583V Gigabit Network Connection                                       | 5        | 2.18%   |
| Intel 82576 Gigabit Network Connection                                        | 5        | 2.18%   |
| Intel 82579V Gigabit Network Connection                                       | 4        | 1.75%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 3        | 1.31%   |
| Intel Ethernet Connection (7) I219-LM                                         | 3        | 1.31%   |
| Intel Ethernet Controller X550                                                | 2        | 0.87%   |
| Intel Ethernet Connection I217-V                                              | 2        | 0.87%   |
| Intel Ethernet Connection (2) I219-LM                                         | 2        | 0.87%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 2        | 0.87%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 2        | 0.87%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2        | 0.87%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1        | 0.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1        | 0.44%   |
| Nvidia MCP73 Ethernet                                                         | 1        | 0.44%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                       | 1        | 0.44%   |
| Intel I350 Gigabit Fiber Network Connection                                   | 1        | 0.44%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 1        | 0.44%   |
| Intel Ethernet Controller I225-V                                              | 1        | 0.44%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 1        | 0.44%   |
| Intel Ethernet Connection I219-LM                                             | 1        | 0.44%   |
| Intel Ethernet Connection (6) I219-LM                                         | 1        | 0.44%   |
| Intel Ethernet Connection (11) I219-V                                         | 1        | 0.44%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 1        | 0.44%   |
| Intel 82571EB Gigabit Ethernet Controller                                     | 1        | 0.44%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                       | 1        | 0.44%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express                       | 1        | 0.44%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                         | 1        | 0.44%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                               | 1        | 0.44%   |
| American Megatrends Virtual Ethernet                                          | 1        | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 168      | 80.77%  |
| WiFi     | 33       | 15.87%  |
| Unknown  | 4        | 1.92%   |
| Modem    | 3        | 1.44%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 165      | 93.22%  |
| WiFi     | 12       | 6.78%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 36       | 20.81%  |
| 2     | 35       | 20.23%  |
| 3     | 30       | 17.34%  |
| 4     | 24       | 13.87%  |
| 5     | 19       | 10.98%  |
| 6     | 15       | 8.67%   |
| 7     | 5        | 2.89%   |
| 0     | 3        | 1.73%   |
| 8     | 2        | 1.16%   |
| 15    | 1        | 0.58%   |
| 14    | 1        | 0.58%   |
| 12    | 1        | 0.58%   |
| 10    | 1        | 0.58%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 157      | 88.7%   |
| Yes  | 20       | 11.3%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 14       | 58.33%  |
| Cambridge Silicon Radio | 5        | 20.83%  |
| IMC Networks            | 2        | 8.33%   |
| ASUSTek Computer        | 2        | 8.33%   |
| Realtek Semiconductor   | 1        | 4.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                   | 5        | 20.83%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)     | 5        | 20.83%  |
| Intel Bluetooth wireless interface                      | 4        | 16.67%  |
| Intel Wireless-AC 9260 Bluetooth Adapter                | 2        | 8.33%   |
| Intel Wireless-AC 3168 Bluetooth                        | 2        | 8.33%   |
| Realtek Bluetooth Radio                                 | 1        | 4.17%   |
| Intel Centrino Bluetooth Wireless Transceiver           | 1        | 4.17%   |
| IMC Networks Realtek Bluetooth Adapter                  | 1        | 4.17%   |
| IMC Networks Realtek Bluetooth 4.0 Adapter              | 1        | 4.17%   |
| ASUS Qualcomm Atheros AR9462 Bluetooth 4.0 + HS Adapter | 1        | 4.17%   |
| ASUS Broadcom BCM20702A0 Bluetooth                      | 1        | 4.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 96       | 54.86%  |
| AMD                                  | 45       | 25.71%  |
| Nvidia                               | 23       | 13.14%  |
| Texas Instruments                    | 2        | 1.14%   |
| C-Media Electronics                  | 2        | 1.14%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.57%   |
| Nam Tai E&E Products                 | 1        | 0.57%   |
| Logitech                             | 1        | 0.57%   |
| Griffin Technology                   | 1        | 0.57%   |
| Elgato Systems                       | 1        | 0.57%   |
| Creative Labs                        | 1        | 0.57%   |
| BEHRINGER International              | 1        | 0.57%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 17       | 7.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 13       | 5.78%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 13       | 5.78%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 12       | 5.33%   |
| AMD FCH Azalia Controller                                                                         | 8        | 3.56%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 7        | 3.11%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 7        | 3.11%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6        | 2.67%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 6        | 2.67%   |
| Intel Broadwell-U Audio Controller                                                                | 6        | 2.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6        | 2.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6        | 2.67%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6        | 2.67%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 5        | 2.22%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5        | 2.22%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4        | 1.78%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 4        | 1.78%   |
| Intel 8 Series HD Audio Controller                                                                | 4        | 1.78%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4        | 1.78%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4        | 1.78%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 4        | 1.78%   |
| Nvidia High Definition Audio Controller                                                           | 3        | 1.33%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3        | 1.33%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3        | 1.33%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3        | 1.33%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3        | 1.33%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3        | 1.33%   |
| Intel 200 Series PCH HD Audio                                                                     | 3        | 1.33%   |
| AMD Wrestler HDMI Audio                                                                           | 3        | 1.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3        | 1.33%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 3        | 1.33%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 2        | 0.89%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2        | 0.89%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2        | 0.89%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2        | 0.89%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2        | 0.89%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2        | 0.89%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2        | 0.89%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2        | 0.89%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2        | 0.89%   |
| Thesycon Systemsoftware & Consulting Topping DX3 Pro Audio Control                                | 1        | 0.44%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1        | 0.44%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1        | 0.44%   |
| Nvidia MCP73 High Definition Audio                                                                | 1        | 0.44%   |
| Nvidia MCP61 High Definition Audio                                                                | 1        | 0.44%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1        | 0.44%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1        | 0.44%   |
| Nvidia GP102 HDMI Audio Controller                                                                | 1        | 0.44%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1        | 0.44%   |
| Nvidia GF114 HDMI Audio Controller                                                                | 1        | 0.44%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1        | 0.44%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1        | 0.44%   |
| Nam Tai E&E Products Sony SingStar USBMIC                                                         | 1        | 0.44%   |
| Logitech HD Webcam C910                                                                           | 1        | 0.44%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1        | 0.44%   |
| Intel Comet Lake PCH cAVS                                                                         | 1        | 0.44%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1        | 0.44%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1        | 0.44%   |
| Griffin Technology iMic                                                                           | 1        | 0.44%   |
| Elgato Systems Elgato Wave:3 Elgato Wave:3 Controls Elgato Wave:3 DFU                             | 1        | 0.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 27       | 15.88%  |
| Crucial             | 25       | 14.71%  |
| Corsair             | 24       | 14.12%  |
| SK hynix            | 23       | 13.53%  |
| Unknown             | 21       | 12.35%  |
| Samsung Electronics | 13       | 7.65%   |
| Unknown (ABCD)      | 5        | 2.94%   |
| Micron Technology   | 5        | 2.94%   |
| Ramaxel Technology  | 4        | 2.35%   |
| A-DATA Technology   | 4        | 2.35%   |
| Unknown             | 4        | 2.35%   |
| Team                | 3        | 1.76%   |
| Nanya Technology    | 3        | 1.76%   |
| Transcend           | 2        | 1.18%   |
| G.Skill             | 2        | 1.18%   |
| Unknown (AB)        | 1        | 0.59%   |
| TIMETEC             | 1        | 0.59%   |
| Teikon              | 1        | 0.59%   |
| CSX                 | 1        | 0.59%   |
| Avant               | 1        | 0.59%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR3 2400MT/s | 5        | 2.75%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                       | 4        | 2.2%    |
| Unknown                                                           | 4        | 2.2%    |
| Unknown RAM Module 1GB DIMM SDRAM                                 | 3        | 1.65%   |
| Kingston RAM 99U5469-045.A00LF 4GB DIMM DDR3 1600MT/s             | 3        | 1.65%   |
| Corsair RAM CMX8GX3M2A1333C9 4GB DIMM 1333MT/s                    | 3        | 1.65%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                         | 2        | 1.1%    |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                         | 2        | 1.1%    |
| SK hynix RAM HMT451U7BFR8A-PB 4GB DIMM DDR3 1600MT/s              | 2        | 1.1%    |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s              | 2        | 1.1%    |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s              | 2        | 1.1%    |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s              | 2        | 1.1%    |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s              | 2        | 1.1%    |
| Kingston RAM Module 2048MB DIMM DDR2 800MT/s                      | 2        | 1.1%    |
| Kingston RAM LV26D4U9S8HJ-8 8GB DIMM DDR4 2667MT/s                | 2        | 1.1%    |
| Kingston RAM 9905584-016.A00LF 4GB DIMM DDR3 1600MT/s             | 2        | 1.1%    |
| Crucial RAM CT4G4DFS8213.C8FBR2 4GB DIMM DDR4 2133MT/s            | 2        | 1.1%    |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s           | 2        | 1.1%    |
| Crucial RAM CT102464BF160B.C16 8GB DIMM DDR3 1600MT/s             | 2        | 1.1%    |
| Crucial RAM BL32G36C16U4B.M16FB1 32GB DIMM DDR4 3600MT/s          | 2        | 1.1%    |
| Corsair RAM CMK32GX4M2D3200C16 16GB DIMM DDR4 3200MT/s            | 2        | 1.1%    |
| Unknown RAM Module 8GB SODIMM DDR4 2133MT/s                       | 1        | 0.55%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                         | 1        | 0.55%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                         | 1        | 0.55%   |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s                        | 1        | 0.55%   |
| Unknown RAM Module 4GB DIMM DDR3 65535MT/s                        | 1        | 0.55%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                              | 1        | 0.55%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                          | 1        | 0.55%   |
| Unknown RAM Module 2GB DIMM DDR 133MT/s                           | 1        | 0.55%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                       | 1        | 0.55%   |
| Unknown RAM Module 16GB DIMM DDR4 2133MT/s                        | 1        | 0.55%   |
| Unknown RAM HooDisk NB 4G 1600 4GB DIMM DDR3 1600MT/s             | 1        | 0.55%   |
| Unknown (AB) RAM Module 1GB DIMM LPDDR3 1600MT/s                  | 1        | 0.55%   |
| Transcend RAM TS512MSK64W6H 4GB SODIMM DDR3 1600MT/s              | 1        | 0.55%   |
| Transcend RAM TS1GLK72V6H 8GB DIMM DDR3 1600MT/s                  | 1        | 0.55%   |
| TIMETEC RAM SD3-1600 8GB SODIMM DDR3 1600MT/s                     | 1        | 0.55%   |
| Teikon RAM TMTS8G58DFRBFIR-16 8GB SODIMM DDR3 1600MT/s            | 1        | 0.55%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s               | 1        | 0.55%   |
| Team RAM TEAMGROUP-UD4-3000 4GB DIMM DDR4 2400MT/s                | 1        | 0.55%   |
| Team RAM Elite-1600 4GB DIMM DDR3 1600MT/s                        | 1        | 0.55%   |
| SK hynix RAM Module 16GB DIMM DDR4 2667MT/s                       | 1        | 0.55%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s              | 1        | 0.55%   |
| SK hynix RAM HMT451U6AFR8A-PB 4GB DIMM DDR3 1600MT/s              | 1        | 0.55%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 1        | 0.55%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 1        | 0.55%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB DIMM DDR3 1600MT/s              | 1        | 0.55%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 1        | 0.55%   |
| SK hynix RAM HMT351U6CFR8C-PBA 8GB DIMM DDR3 1600MT/s             | 1        | 0.55%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s              | 1        | 0.55%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s              | 1        | 0.55%   |
| SK hynix RAM HMT325U6BFR8C-H9 2GB DIMM DDR3 1333MT/s              | 1        | 0.55%   |
| SK hynix RAM HMT125U6BFR8C-H9 2048MB DIMM DDR3 1333MT/s           | 1        | 0.55%   |
| SK hynix RAM HMAA4GS6AJR8N-WM 32GB SODIMM DDR4 2933MT/s           | 1        | 0.55%   |
| SK hynix RAM HMA81GU7AFR8N-UH 8192MB DIMM DDR4 2400MT/s           | 1        | 0.55%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s            | 1        | 0.55%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2133MT/s            | 1        | 0.55%   |
| SK hynix RAM 484D543435315336 4GB SODIMM DDR3 1600MT/s            | 1        | 0.55%   |
| Samsung RAM Module 4GB SODIMM DDR4 2133MT/s                       | 1        | 0.55%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s             | 1        | 0.55%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s             | 1        | 0.55%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 95       | 61.69%  |
| DDR4    | 42       | 27.27%  |
| LPDDR4  | 5        | 3.25%   |
| DDR2    | 5        | 3.25%   |
| SDRAM   | 3        | 1.95%   |
| Unknown | 2        | 1.3%    |
| LPDDR3  | 1        | 0.65%   |
| DDR     | 1        | 0.65%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 110      | 72.37%  |
| SODIMM  | 41       | 26.97%  |
| Unknown | 1        | 0.66%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 64       | 39.51%  |
| 8192  | 57       | 35.19%  |
| 2048  | 18       | 11.11%  |
| 16384 | 15       | 9.26%   |
| 32768 | 4        | 2.47%   |
| 1024  | 4        | 2.47%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 65       | 39.63%  |
| 1333    | 26       | 15.85%  |
| 2400    | 16       | 9.76%   |
| 2667    | 9        | 5.49%   |
| 2133    | 9        | 5.49%   |
| 800     | 8        | 4.88%   |
| 3200    | 5        | 3.05%   |
| 3600    | 4        | 2.44%   |
| 1867    | 4        | 2.44%   |
| 2666    | 3        | 1.83%   |
| 667     | 3        | 1.83%   |
| Unknown | 3        | 1.83%   |
| 65535   | 1        | 0.61%   |
| 3534    | 1        | 0.61%   |
| 2933    | 1        | 0.61%   |
| 1866    | 1        | 0.61%   |
| 1800    | 1        | 0.61%   |
| 1067    | 1        | 0.61%   |
| 1066    | 1        | 0.61%   |
| 933     | 1        | 0.61%   |
| 133     | 1        | 0.61%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model            | Desktops | Percent |
|------------------|----------|---------|
| HP LaserJet 1200 | 1        | 50%     |
| HP DeskJet 5850c | 1        | 50%     |

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
| Canon CanoScan LiDE 210 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Logitech            | 6        | 75%     |
| Chicony Electronics | 1        | 12.5%   |
| ARC International   | 1        | 12.5%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Logitech Labtec Webcam Pro           | 2        | 25%     |
| Logitech HD Pro Webcam C920          | 2        | 25%     |
| Logitech Webcam C930e                | 1        | 12.5%   |
| Logitech Webcam C310                 | 1        | 12.5%   |
| Chicony Integrated Camera [ThinkPad] | 1        | 12.5%   |
| ARC International Camera             | 1        | 12.5%   |

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
| 1     | 81       | 46.02%  |
| 0     | 74       | 42.05%  |
| 2     | 13       | 7.39%   |
| 3     | 8        | 4.55%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 84       | 70%     |
| Net/wireless             | 9        | 7.5%    |
| Bluetooth                | 7        | 5.83%   |
| Card reader              | 6        | 5%      |
| Sound                    | 4        | 3.33%   |
| Firewire controller      | 4        | 3.33%   |
| Network                  | 2        | 1.67%   |
| Graphics card            | 2        | 1.67%   |
| Storage/raid             | 1        | 0.83%   |
| Net/ethernet             | 1        | 0.83%   |

