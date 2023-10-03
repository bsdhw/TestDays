BSD in Poland - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for BSD in Poland.

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

Total: 264

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| IGEL Techn... | VX900                       | [eb65624dc3](https://bsd-hardware.info/?probe=eb65624dc3) | Sep 29, 2023 |
| MSI           | MS-98G4                     | [a8ea23c0df](https://bsd-hardware.info/?probe=a8ea23c0df) | Sep 28, 2023 |
| Dell          | 0NW6H5 A00                  | [b698f41785](https://bsd-hardware.info/?probe=b698f41785) | Sep 28, 2023 |
| Dell          | 05XGC8 A00                  | [a0d9fae143](https://bsd-hardware.info/?probe=a0d9fae143) | Sep 27, 2023 |
| HP            | 3396                        | [a60feb9960](https://bsd-hardware.info/?probe=a60feb9960) | Sep 25, 2023 |
| ASUSTek       | P5G41T-M LX3                | [621470728b](https://bsd-hardware.info/?probe=621470728b) | Sep 19, 2023 |
| Dell          | 0D24M8 A03                  | [48441955a6](https://bsd-hardware.info/?probe=48441955a6) | Sep 14, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [cda96eed7a](https://bsd-hardware.info/?probe=cda96eed7a) | Aug 28, 2023 |
| Gigabyte      | GA-890FXA-UD5               | [85b0bba1ea](https://bsd-hardware.info/?probe=85b0bba1ea) | Aug 27, 2023 |
| Gigabyte      | H510M K                     | [17f15f19f4](https://bsd-hardware.info/?probe=17f15f19f4) | Aug 26, 2023 |
| HP            | 18E5                        | [61bde93177](https://bsd-hardware.info/?probe=61bde93177) | Aug 11, 2023 |
| Unknown       | Unknown                     | [7751768206](https://bsd-hardware.info/?probe=7751768206) | Aug 10, 2023 |
| AMI           | PB_1900A                    | [791f6e0cb4](https://bsd-hardware.info/?probe=791f6e0cb4) | Aug 07, 2023 |
| ASUSTek       | PRIME A320I-K               | [09f173d4b6](https://bsd-hardware.info/?probe=09f173d4b6) | Jul 30, 2023 |
| Dell          | 0WMJ54 A01                  | [e11855c762](https://bsd-hardware.info/?probe=e11855c762) | Jul 24, 2023 |
| Dell          | 05XGC8 A00                  | [3a774e653a](https://bsd-hardware.info/?probe=3a774e653a) | Jul 19, 2023 |
| Dell          | 05XGC8 A00                  | [604ac1ea85](https://bsd-hardware.info/?probe=604ac1ea85) | Jul 19, 2023 |
| Supermicro    | A2SDV-4C-LN10PF             | [8be657ad15](https://bsd-hardware.info/?probe=8be657ad15) | Jul 17, 2023 |
| HP            | 213D A01                    | [ae7b01c282](https://bsd-hardware.info/?probe=ae7b01c282) | Jul 16, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [1de68296ba](https://bsd-hardware.info/?probe=1de68296ba) | Jul 15, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [5f5c78ed40](https://bsd-hardware.info/?probe=5f5c78ed40) | Jul 15, 2023 |
| Dell          | 05XGC8 A00                  | [16fc35ccac](https://bsd-hardware.info/?probe=16fc35ccac) | Jul 06, 2023 |
| Gigabyte      | B360N WIFI-CF               | [e569621be2](https://bsd-hardware.info/?probe=e569621be2) | Jul 03, 2023 |
| Gigabyte      | H270N-WIFI-CF               | [553cd9ecae](https://bsd-hardware.info/?probe=553cd9ecae) | Jul 03, 2023 |
| ASRock        | J3455B-ITX                  | [3c80c960d3](https://bsd-hardware.info/?probe=3c80c960d3) | Jul 03, 2023 |
| ASRock        | J3455B-ITX                  | [051ddf6f8d](https://bsd-hardware.info/?probe=051ddf6f8d) | Jul 03, 2023 |
| Gigabyte      | H270N-WIFI-CF               | [dfdb0bd650](https://bsd-hardware.info/?probe=dfdb0bd650) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | [e68bb73773](https://bsd-hardware.info/?probe=e68bb73773) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | [3b4a248520](https://bsd-hardware.info/?probe=3b4a248520) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | [0a2a221aae](https://bsd-hardware.info/?probe=0a2a221aae) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | [7e5ee8de12](https://bsd-hardware.info/?probe=7e5ee8de12) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | [3b50a90ebc](https://bsd-hardware.info/?probe=3b50a90ebc) | Jul 03, 2023 |
| HP            | 213D A01                    | [eccc48bb80](https://bsd-hardware.info/?probe=eccc48bb80) | Jun 23, 2023 |
| Unknown       | Unknown                     | [6b4f214b72](https://bsd-hardware.info/?probe=6b4f214b72) | Jun 15, 2023 |
| Unknown       | Unknown                     | [615e7cbf52](https://bsd-hardware.info/?probe=615e7cbf52) | Jun 15, 2023 |
| Unknown       | Unknown                     | [8357f0f72e](https://bsd-hardware.info/?probe=8357f0f72e) | Jun 15, 2023 |
| Intel         | D2500CC AAG81477-401        | [15329a007b](https://bsd-hardware.info/?probe=15329a007b) | Jun 14, 2023 |
| Techvision    | TVI7309X B0                 | [3679eb8cd4](https://bsd-hardware.info/?probe=3679eb8cd4) | Jun 11, 2023 |
| Dell          | 05XGC8 A00                  | [f79924e37b](https://bsd-hardware.info/?probe=f79924e37b) | Jun 08, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [95ceb1335c](https://bsd-hardware.info/?probe=95ceb1335c) | Jun 04, 2023 |
| Dell          | 05XGC8 A00                  | [98ebd3efdb](https://bsd-hardware.info/?probe=98ebd3efdb) | Jun 02, 2023 |
| Unknown       | Unknown                     | [e057606b14](https://bsd-hardware.info/?probe=e057606b14) | May 29, 2023 |
| NU591R        | 1.0                         | [e4bdd753d1](https://bsd-hardware.info/?probe=e4bdd753d1) | May 28, 2023 |
| Dell          | 05XGC8 A00                  | [b121b2cba9](https://bsd-hardware.info/?probe=b121b2cba9) | May 26, 2023 |
| Unknown       | Unknown                     | [1070ff80a8](https://bsd-hardware.info/?probe=1070ff80a8) | May 26, 2023 |
| PC Engines    | apu6                        | [cfebc05e50](https://bsd-hardware.info/?probe=cfebc05e50) | May 21, 2023 |
| PC Engines    | apu6                        | [320d6a85a3](https://bsd-hardware.info/?probe=320d6a85a3) | May 21, 2023 |
| HP            | 213D A01                    | [8e1d1d5670](https://bsd-hardware.info/?probe=8e1d1d5670) | May 20, 2023 |
| PC Engines    | apu4                        | [1d4c0fad6a](https://bsd-hardware.info/?probe=1d4c0fad6a) | May 16, 2023 |
| PC Engines    | apu4                        | [94bdc05090](https://bsd-hardware.info/?probe=94bdc05090) | May 16, 2023 |
| Supermicro    | X8SIL                       | [bb30062fc1](https://bsd-hardware.info/?probe=bb30062fc1) | May 14, 2023 |
| Dell          | 05XGC8 A00                  | [dd2b0657d0](https://bsd-hardware.info/?probe=dd2b0657d0) | May 13, 2023 |
| Dell          | 05XGC8 A00                  | [131214e3a7](https://bsd-hardware.info/?probe=131214e3a7) | May 12, 2023 |
| HP            | 213D A01                    | [92c8d4c54e](https://bsd-hardware.info/?probe=92c8d4c54e) | May 12, 2023 |
| ASRock        | J4125-ITX                   | [6e34c8b22a](https://bsd-hardware.info/?probe=6e34c8b22a) | May 05, 2023 |
| Gigabyte      | H510M K                     | [e4a5065086](https://bsd-hardware.info/?probe=e4a5065086) | May 03, 2023 |
| HP            | 213D A01                    | [6810604547](https://bsd-hardware.info/?probe=6810604547) | May 03, 2023 |
| Gigabyte      | H510M K                     | [a952664d92](https://bsd-hardware.info/?probe=a952664d92) | Apr 29, 2023 |
| MSI           | H110M PRO-VD                | [ce8453fcce](https://bsd-hardware.info/?probe=ce8453fcce) | Apr 27, 2023 |
| HP            | 18E5                        | [9f82560327](https://bsd-hardware.info/?probe=9f82560327) | Apr 26, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [838979f891](https://bsd-hardware.info/?probe=838979f891) | Apr 20, 2023 |
| ASUSTek       | Crosshair IV Formula        | [a7830f5244](https://bsd-hardware.info/?probe=a7830f5244) | Apr 17, 2023 |
| Unknown       | Unknown                     | [fb756bb34e](https://bsd-hardware.info/?probe=fb756bb34e) | Apr 16, 2023 |
| Techvision    | TVI7309X B0                 | [e1e041b34a](https://bsd-hardware.info/?probe=e1e041b34a) | Apr 07, 2023 |
| Techvision    | TVI7309X B0                 | [ac38e117ac](https://bsd-hardware.info/?probe=ac38e117ac) | Apr 04, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [032a4be314](https://bsd-hardware.info/?probe=032a4be314) | Apr 03, 2023 |
| Techvision    | TVI7309X B0                 | [f4d583f326](https://bsd-hardware.info/?probe=f4d583f326) | Apr 01, 2023 |
| Techvision    | TVI7309X B0                 | [837fdf1a2c](https://bsd-hardware.info/?probe=837fdf1a2c) | Mar 31, 2023 |
| Dell          | 0T1D10 A01                  | [2f5592023f](https://bsd-hardware.info/?probe=2f5592023f) | Mar 29, 2023 |
| Dell          | 0T1D10 A01                  | [6316b108be](https://bsd-hardware.info/?probe=6316b108be) | Mar 29, 2023 |
| HP            | 18E5                        | [1f402a50e7](https://bsd-hardware.info/?probe=1f402a50e7) | Mar 22, 2023 |
| Intel         | X99                         | [a74c2b96ff](https://bsd-hardware.info/?probe=a74c2b96ff) | Mar 21, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [8d0e6be5da](https://bsd-hardware.info/?probe=8d0e6be5da) | Mar 20, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [acc1970543](https://bsd-hardware.info/?probe=acc1970543) | Mar 18, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [b8404f57ba](https://bsd-hardware.info/?probe=b8404f57ba) | Mar 15, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [2d5e8056c0](https://bsd-hardware.info/?probe=2d5e8056c0) | Mar 15, 2023 |
| MSI           | A320M-A PRO                 | [593f6ff02d](https://bsd-hardware.info/?probe=593f6ff02d) | Mar 12, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [e8204efca6](https://bsd-hardware.info/?probe=e8204efca6) | Mar 12, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | [29ad0e1044](https://bsd-hardware.info/?probe=29ad0e1044) | Mar 11, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [12990e3b0f](https://bsd-hardware.info/?probe=12990e3b0f) | Mar 09, 2023 |
| AMI           | PB_1900A                    | [79504fcf66](https://bsd-hardware.info/?probe=79504fcf66) | Mar 02, 2023 |
| Unknown       | Unknown                     | [78d56cd69d](https://bsd-hardware.info/?probe=78d56cd69d) | Mar 01, 2023 |
| Techvision    | TVI7309X B0                 | [1758c6207c](https://bsd-hardware.info/?probe=1758c6207c) | Feb 27, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [e55635df08](https://bsd-hardware.info/?probe=e55635df08) | Feb 23, 2023 |
| PC Engines    | apu1                        | [41fe7362c4](https://bsd-hardware.info/?probe=41fe7362c4) | Feb 22, 2023 |
| Unknown       | V0.9x                       | [21243cad5f](https://bsd-hardware.info/?probe=21243cad5f) | Feb 21, 2023 |
| MSI           | Z97 GUARD-PRO               | [43d56964b9](https://bsd-hardware.info/?probe=43d56964b9) | Feb 12, 2023 |
| Supermicro    | X8STi                       | [4faeca02d3](https://bsd-hardware.info/?probe=4faeca02d3) | Feb 11, 2023 |
| MSI           | Z97 GUARD-PRO               | [9f066752d5](https://bsd-hardware.info/?probe=9f066752d5) | Feb 11, 2023 |
| HP            | 3396                        | [6a20d52898](https://bsd-hardware.info/?probe=6a20d52898) | Feb 08, 2023 |
| MSI           | Z97 GAMING 3                | [bbe7b327fd](https://bsd-hardware.info/?probe=bbe7b327fd) | Feb 06, 2023 |
| Unknown       | Unknown                     | [cb25ee692c](https://bsd-hardware.info/?probe=cb25ee692c) | Feb 05, 2023 |
| ASUSTek       | P5G41T-M LX3                | [ea5b1c178b](https://bsd-hardware.info/?probe=ea5b1c178b) | Feb 01, 2023 |
| Unknown       | Unknown                     | [e76cc93e5d](https://bsd-hardware.info/?probe=e76cc93e5d) | Jan 31, 2023 |
| Unknown       | Unknown                     | [540696f4e5](https://bsd-hardware.info/?probe=540696f4e5) | Jan 29, 2023 |
| Unknown       | Unknown                     | [6aa648ba82](https://bsd-hardware.info/?probe=6aa648ba82) | Jan 19, 2023 |
| HP            | 1495                        | [4e16deda5a](https://bsd-hardware.info/?probe=4e16deda5a) | Jan 11, 2023 |
| Gigabyte      | H510M K                     | [c30a71f5ae](https://bsd-hardware.info/?probe=c30a71f5ae) | Jan 10, 2023 |
| Biostar       | J4125NHU                    | [41114c45b7](https://bsd-hardware.info/?probe=41114c45b7) | Jan 05, 2023 |
| Gigabyte      | J4005ND2P-CF                | [4bcc34fdca](https://bsd-hardware.info/?probe=4bcc34fdca) | Dec 27, 2022 |
| Intel         | D2500HN AAG81480-500        | [dae5627541](https://bsd-hardware.info/?probe=dae5627541) | Dec 27, 2022 |
| Acer          | WG43M                       | [d316352c20](https://bsd-hardware.info/?probe=d316352c20) | Dec 22, 2022 |
| Unknown       | Unknown                     | [0e98358cf3](https://bsd-hardware.info/?probe=0e98358cf3) | Dec 17, 2022 |
| ASRock        | X570 Pro4                   | [b23f59a068](https://bsd-hardware.info/?probe=b23f59a068) | Nov 27, 2022 |
| ASRock        | Q1900B-ITX                  | [c93690c7ca](https://bsd-hardware.info/?probe=c93690c7ca) | Nov 27, 2022 |
| Shuttle       | FZ270                       | [04a7f49322](https://bsd-hardware.info/?probe=04a7f49322) | Nov 27, 2022 |
| Shuttle       | FZ270                       | [10016f39b9](https://bsd-hardware.info/?probe=10016f39b9) | Nov 27, 2022 |
| ASRock        | Q1900B-ITX                  | [675c9fdf94](https://bsd-hardware.info/?probe=675c9fdf94) | Nov 27, 2022 |
| ASRock        | Q1900B-ITX                  | [a337eb9e5f](https://bsd-hardware.info/?probe=a337eb9e5f) | Nov 27, 2022 |
| Shuttle       | FH270                       | [192351ac6f](https://bsd-hardware.info/?probe=192351ac6f) | Nov 27, 2022 |
| Shuttle       | FH270                       | [3b68d89092](https://bsd-hardware.info/?probe=3b68d89092) | Nov 27, 2022 |
| HP            | 3396                        | [dc94cbde1a](https://bsd-hardware.info/?probe=dc94cbde1a) | Nov 23, 2022 |
| Gigabyte      | H110TN                      | [c121bad3fb](https://bsd-hardware.info/?probe=c121bad3fb) | Nov 17, 2022 |
| Intel         | D2500CC AAG81477-401        | [f27ff1a7c3](https://bsd-hardware.info/?probe=f27ff1a7c3) | Oct 22, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [348bef7dba](https://bsd-hardware.info/?probe=348bef7dba) | Oct 20, 2022 |
| Lenovo        | 3188 SDK0J40697 WIN 3305... | [f84b205626](https://bsd-hardware.info/?probe=f84b205626) | Oct 18, 2022 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [e08c408ced](https://bsd-hardware.info/?probe=e08c408ced) | Oct 14, 2022 |
| ASRockRack    | EP2C612D16FM                | [30a582fccb](https://bsd-hardware.info/?probe=30a582fccb) | Oct 07, 2022 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | [f521533d51](https://bsd-hardware.info/?probe=f521533d51) | Oct 06, 2022 |
| Gigabyte      | H510M K                     | [27f932ee37](https://bsd-hardware.info/?probe=27f932ee37) | Oct 02, 2022 |
| Gigabyte      | H510M K                     | [4beab225f6](https://bsd-hardware.info/?probe=4beab225f6) | Sep 28, 2022 |
| Supermicro    | X9SCL/X9SCMA                | [fe44242c3b](https://bsd-hardware.info/?probe=fe44242c3b) | Sep 25, 2022 |
| Gigabyte      | H81M-S1                     | [fe9eecb935](https://bsd-hardware.info/?probe=fe9eecb935) | Sep 18, 2022 |
| Intel         | Q3XXG4-P V1.0               | [7aa564bfb2](https://bsd-hardware.info/?probe=7aa564bfb2) | Sep 14, 2022 |
| ASUSTek       | H61M-K                      | [0ee299e989](https://bsd-hardware.info/?probe=0ee299e989) | Sep 14, 2022 |
| HP            | 213D A01                    | [6354ddb4a8](https://bsd-hardware.info/?probe=6354ddb4a8) | Sep 12, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [b2dc861f47](https://bsd-hardware.info/?probe=b2dc861f47) | Sep 10, 2022 |
| HP            | 213D A01                    | [c495fb5448](https://bsd-hardware.info/?probe=c495fb5448) | Aug 30, 2022 |
| HP            | 213D A01                    | [1b90f312ea](https://bsd-hardware.info/?probe=1b90f312ea) | Aug 26, 2022 |
| Inventec      | Z CLASS A02                 | [cb3708c9bf](https://bsd-hardware.info/?probe=cb3708c9bf) | Aug 21, 2022 |
| Gigabyte      | IMB4100TN                   | [aa4bae0d12](https://bsd-hardware.info/?probe=aa4bae0d12) | Aug 15, 2022 |
| ASRock        | Z370 Pro4                   | [038c5f8763](https://bsd-hardware.info/?probe=038c5f8763) | Aug 10, 2022 |
| Dell          | 084J0R A00                  | [932058e97a](https://bsd-hardware.info/?probe=932058e97a) | Aug 09, 2022 |
| iEi           | B449 V1.00                  | [7776910eea](https://bsd-hardware.info/?probe=7776910eea) | Aug 05, 2022 |
| Gigabyte      | J4005ND2P-CF                | [2967d5275e](https://bsd-hardware.info/?probe=2967d5275e) | Jul 29, 2022 |
| HP            | 3397                        | [68eb683936](https://bsd-hardware.info/?probe=68eb683936) | Jul 27, 2022 |
| ASUSTek       | P8B WS                      | [dd7f8123d2](https://bsd-hardware.info/?probe=dd7f8123d2) | Jul 19, 2022 |
| HP            | 213D A01                    | [0f58ab215e](https://bsd-hardware.info/?probe=0f58ab215e) | Jul 03, 2022 |
| Gigabyte      | GA-970A-UD3                 | [a094c1c53b](https://bsd-hardware.info/?probe=a094c1c53b) | Jun 20, 2022 |
| Unknown       | Unknown                     | [fe9f636040](https://bsd-hardware.info/?probe=fe9f636040) | Jun 13, 2022 |
| Unknown       | Unknown                     | [6acbc93101](https://bsd-hardware.info/?probe=6acbc93101) | May 30, 2022 |
| ASUSTek       | P5G41T-M LX3                | [3f39f21672](https://bsd-hardware.info/?probe=3f39f21672) | May 29, 2022 |
| Intel         | Q3XXG4-P V1.0               | [ce4d7c01e5](https://bsd-hardware.info/?probe=ce4d7c01e5) | May 24, 2022 |
| HP            | 213D A01                    | [562722ac56](https://bsd-hardware.info/?probe=562722ac56) | Apr 30, 2022 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | [0d46ae5678](https://bsd-hardware.info/?probe=0d46ae5678) | Apr 25, 2022 |
| Apple         | PowerMac10,1                | [e054e605fa](https://bsd-hardware.info/?probe=e054e605fa) | Apr 23, 2022 |
| Unknown       | Unknown                     | [3c5fcc2377](https://bsd-hardware.info/?probe=3c5fcc2377) | Apr 22, 2022 |
| HP            | 213D A01                    | [4dea775e1b](https://bsd-hardware.info/?probe=4dea775e1b) | Apr 12, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | [da64cbb0d1](https://bsd-hardware.info/?probe=da64cbb0d1) | Apr 07, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [9a260e4d21](https://bsd-hardware.info/?probe=9a260e4d21) | Apr 05, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | [964ceb3616](https://bsd-hardware.info/?probe=964ceb3616) | Apr 03, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | [5038186437](https://bsd-hardware.info/?probe=5038186437) | Apr 02, 2022 |
| ASUSTek       | P6-P8H61E                   | [11664cd9d7](https://bsd-hardware.info/?probe=11664cd9d7) | Mar 30, 2022 |
| ASUSTek       | P6-P8H61E                   | [540f66f678](https://bsd-hardware.info/?probe=540f66f678) | Mar 29, 2022 |
| Dell          | 0GXM1W A00                  | [717721a634](https://bsd-hardware.info/?probe=717721a634) | Mar 29, 2022 |
| Unknown       | Unknown                     | [38c71bac61](https://bsd-hardware.info/?probe=38c71bac61) | Mar 22, 2022 |
| Unknown       | Unknown                     | [a54ee6f019](https://bsd-hardware.info/?probe=a54ee6f019) | Mar 18, 2022 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | [55515325c4](https://bsd-hardware.info/?probe=55515325c4) | Mar 15, 2022 |
| Dell          | 0GXM1W A00                  | [a488c9af25](https://bsd-hardware.info/?probe=a488c9af25) | Mar 14, 2022 |
| ASRock        | Q1900B-ITX                  | [b4142103cb](https://bsd-hardware.info/?probe=b4142103cb) | Mar 10, 2022 |
| Unknown       | LeMaker Banana Pi           | [37e7d1912b](https://bsd-hardware.info/?probe=37e7d1912b) | Mar 05, 2022 |
| Intel         | D945GSEJT                   | [bf6a38dfcb](https://bsd-hardware.info/?probe=bf6a38dfcb) | Feb 26, 2022 |
| HP            | 213D A01                    | [b9560ec339](https://bsd-hardware.info/?probe=b9560ec339) | Feb 24, 2022 |
| ASRock        | ConRoe1333-D667             | [624b4f4de7](https://bsd-hardware.info/?probe=624b4f4de7) | Feb 23, 2022 |
| Shuttle       | FZ270                       | [7e0eb61342](https://bsd-hardware.info/?probe=7e0eb61342) | Feb 22, 2022 |
| Unknown       | Raspberry Pi 4 Model B R... | [04e528ca9f](https://bsd-hardware.info/?probe=04e528ca9f) | Feb 19, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | [64999a24c1](https://bsd-hardware.info/?probe=64999a24c1) | Feb 16, 2022 |
| Raspberry ... | Raspberry Pi 400            | [dd56609ceb](https://bsd-hardware.info/?probe=dd56609ceb) | Feb 14, 2022 |
| HP            | 213D A01                    | [0171663489](https://bsd-hardware.info/?probe=0171663489) | Feb 12, 2022 |
| Unknown       | LeMaker Banana Pi           | [77413a3d9d](https://bsd-hardware.info/?probe=77413a3d9d) | Feb 12, 2022 |
| MSI           | B75A-G43                    | [8e445eb2d4](https://bsd-hardware.info/?probe=8e445eb2d4) | Feb 08, 2022 |
| MSI           | H61M-P20                    | [98ec852f90](https://bsd-hardware.info/?probe=98ec852f90) | Feb 06, 2022 |
| ASUSTek       | P6-P8H61E                   | [e838981914](https://bsd-hardware.info/?probe=e838981914) | Feb 06, 2022 |
| Dell          | 04YP6J A02                  | [550e7feb7f](https://bsd-hardware.info/?probe=550e7feb7f) | Feb 03, 2022 |
| Gigabyte      | J4005ND2P-CF                | [2acf9ac926](https://bsd-hardware.info/?probe=2acf9ac926) | Jan 29, 2022 |
| Intel         | D2500HN AAG81480-500        | [3a39fe5ec2](https://bsd-hardware.info/?probe=3a39fe5ec2) | Jan 29, 2022 |
| Gigabyte      | J4005ND2P-CF                | [268906bcbe](https://bsd-hardware.info/?probe=268906bcbe) | Jan 29, 2022 |
| Dell          | 014GRG A03                  | [8e0a22c065](https://bsd-hardware.info/?probe=8e0a22c065) | Jan 28, 2022 |
| Dell          | 014GRG A03                  | [5996ba19b1](https://bsd-hardware.info/?probe=5996ba19b1) | Jan 27, 2022 |
| Dell          | 014GRG A03                  | [223d955a90](https://bsd-hardware.info/?probe=223d955a90) | Jan 26, 2022 |
| ASRock        | A300M-STX                   | [8edf072b67](https://bsd-hardware.info/?probe=8edf072b67) | Jan 25, 2022 |
| ASRock        | X570 Pro4                   | [d77aae8064](https://bsd-hardware.info/?probe=d77aae8064) | Jan 23, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | [04abd226f3](https://bsd-hardware.info/?probe=04abd226f3) | Jan 21, 2022 |
| ASRockRack    | X570D4I-2T                  | [9f06290060](https://bsd-hardware.info/?probe=9f06290060) | Jan 17, 2022 |
| ASUSTek       | M5A97 R2.0                  | [9f442754d0](https://bsd-hardware.info/?probe=9f442754d0) | Jan 17, 2022 |
| Intel         | SKYBAY                      | [64db889658](https://bsd-hardware.info/?probe=64db889658) | Jan 01, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | [a671e3eb04](https://bsd-hardware.info/?probe=a671e3eb04) | Dec 31, 2021 |
| MSI           | H81M-P32                    | [bb4e756ca9](https://bsd-hardware.info/?probe=bb4e756ca9) | Dec 20, 2021 |
| Gigabyte      | H110TN                      | [8b6f0f839d](https://bsd-hardware.info/?probe=8b6f0f839d) | Dec 18, 2021 |
| Dell          | 0YY821 A00                  | [5de293a0be](https://bsd-hardware.info/?probe=5de293a0be) | Dec 17, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [32d20b9b8e](https://bsd-hardware.info/?probe=32d20b9b8e) | Dec 14, 2021 |
| ASUSTek       | H110M-K                     | [2921401f70](https://bsd-hardware.info/?probe=2921401f70) | Dec 12, 2021 |
| Gigabyte      | B550M AORUS ELITE           | [66ed413cab](https://bsd-hardware.info/?probe=66ed413cab) | Dec 05, 2021 |
| ASUSTek       | P7P55D                      | [73373c3c65](https://bsd-hardware.info/?probe=73373c3c65) | Dec 04, 2021 |
| ASUSTek       | P7P55D                      | [540d2ef68c](https://bsd-hardware.info/?probe=540d2ef68c) | Nov 29, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [bc3b65334e](https://bsd-hardware.info/?probe=bc3b65334e) | Nov 29, 2021 |
| Shuttle       | FH270                       | [81643d52fd](https://bsd-hardware.info/?probe=81643d52fd) | Nov 26, 2021 |
| ASRock        | Q1900B-ITX                  | [7f32937b2c](https://bsd-hardware.info/?probe=7f32937b2c) | Nov 26, 2021 |
| Shuttle       | FZ270                       | [309687b5be](https://bsd-hardware.info/?probe=309687b5be) | Nov 26, 2021 |
| ASRock        | Q1900B-ITX                  | [4df18caa5f](https://bsd-hardware.info/?probe=4df18caa5f) | Nov 26, 2021 |
| HP            | 213D A01                    | [0059e5b645](https://bsd-hardware.info/?probe=0059e5b645) | Nov 23, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [12a360ddd1](https://bsd-hardware.info/?probe=12a360ddd1) | Nov 14, 2021 |
| Unknown       | Unknown                     | [d31ea9f041](https://bsd-hardware.info/?probe=d31ea9f041) | Nov 02, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [9f8010bdbe](https://bsd-hardware.info/?probe=9f8010bdbe) | Oct 25, 2021 |
| Gigabyte      | B450M S2H                   | [f3bf8edc1e](https://bsd-hardware.info/?probe=f3bf8edc1e) | Oct 22, 2021 |
| HP            | 213D A01                    | [4b4903dfb2](https://bsd-hardware.info/?probe=4b4903dfb2) | Oct 17, 2021 |
| Gigabyte      | B450M DS3H                  | [445b53ddba](https://bsd-hardware.info/?probe=445b53ddba) | Oct 15, 2021 |
| Unknown       | YL-J3160L4                  | [3d0a63b493](https://bsd-hardware.info/?probe=3d0a63b493) | Oct 12, 2021 |
| Gigabyte      | B450M DS3H                  | [50e4e13ee0](https://bsd-hardware.info/?probe=50e4e13ee0) | Oct 07, 2021 |
| MSI           | MS-7B53                     | [c7104d301e](https://bsd-hardware.info/?probe=c7104d301e) | Oct 05, 2021 |
| Unknown       | Raspberry Pi 4 Model B R... | [49173900e7](https://bsd-hardware.info/?probe=49173900e7) | Oct 04, 2021 |
| Unknown       | Raspberry Pi 4 Model B R... | [d05a877535](https://bsd-hardware.info/?probe=d05a877535) | Oct 03, 2021 |
| Intel         | SHARKBAY                    | [96448603f5](https://bsd-hardware.info/?probe=96448603f5) | Oct 02, 2021 |
| ASUSTek       | PRIME H310M-D R2.0          | [a302e181a5](https://bsd-hardware.info/?probe=a302e181a5) | Sep 27, 2021 |
| Dell          | 04YP6J A02                  | [9ff547c00b](https://bsd-hardware.info/?probe=9ff547c00b) | Sep 16, 2021 |
| ASUSTek       | Q87T                        | [91e631c240](https://bsd-hardware.info/?probe=91e631c240) | Sep 11, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [9e13729a12](https://bsd-hardware.info/?probe=9e13729a12) | Sep 02, 2021 |
| Essentiel ... | MS-7848                     | [fa20a0307e](https://bsd-hardware.info/?probe=fa20a0307e) | Sep 01, 2021 |
| Intel         | SHARKBAY                    | [38332c6f8d](https://bsd-hardware.info/?probe=38332c6f8d) | Aug 16, 2021 |
| AOpen         | D1009 A1A4                  | [dc60a8dece](https://bsd-hardware.info/?probe=dc60a8dece) | Aug 03, 2021 |
| HP            | 1998                        | [fdf0088303](https://bsd-hardware.info/?probe=fdf0088303) | Jul 08, 2021 |
| Unknown       | Unknown                     | [1fffc03fbf](https://bsd-hardware.info/?probe=1fffc03fbf) | Jun 24, 2021 |
| Lenovo        | Board                       | [c981ffdff7](https://bsd-hardware.info/?probe=c981ffdff7) | Jun 15, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [eeb4489d2f](https://bsd-hardware.info/?probe=eeb4489d2f) | Jun 13, 2021 |
| Gigabyte      | G31M-ES2L                   | [338240a790](https://bsd-hardware.info/?probe=338240a790) | Jun 05, 2021 |
| Gigabyte      | G31M-ES2L                   | [bf23a1ca58](https://bsd-hardware.info/?probe=bf23a1ca58) | Jun 02, 2021 |
| MSI           | H81M-P32                    | [1ffaa46853](https://bsd-hardware.info/?probe=1ffaa46853) | May 31, 2021 |
| MSI           | H81M-P32                    | [253deda07f](https://bsd-hardware.info/?probe=253deda07f) | May 28, 2021 |
| Lenovo        | Board                       | [1d6f23a5de](https://bsd-hardware.info/?probe=1d6f23a5de) | May 24, 2021 |
| Dell          | 0R230R A00                  | [bd8bf06e7f](https://bsd-hardware.info/?probe=bd8bf06e7f) | May 21, 2021 |
| MSI           | B450M-A PRO MAX             | [6317bd7dbd](https://bsd-hardware.info/?probe=6317bd7dbd) | May 05, 2021 |
| Unknown       | Unknown                     | [1dcb55d9fe](https://bsd-hardware.info/?probe=1dcb55d9fe) | May 05, 2021 |
| Supermicro    | X7DCL                       | [27fc294bca](https://bsd-hardware.info/?probe=27fc294bca) | May 03, 2021 |
| ShenZhen M... | MW-NANO-APL-4L              | [b848b8e046](https://bsd-hardware.info/?probe=b848b8e046) | Apr 03, 2021 |
| Gigabyte      | J4005ND2P-CF                | [7ce3b2f01e](https://bsd-hardware.info/?probe=7ce3b2f01e) | Mar 27, 2021 |
| Supermicro    | X7SLA                       | [043c20b93d](https://bsd-hardware.info/?probe=043c20b93d) | Mar 19, 2021 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [b570778ef7](https://bsd-hardware.info/?probe=b570778ef7) | Mar 14, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [dee034110e](https://bsd-hardware.info/?probe=dee034110e) | Mar 05, 2021 |
| Intel         | Q3XXG4-P V1.0               | [73eec13c5e](https://bsd-hardware.info/?probe=73eec13c5e) | Mar 02, 2021 |
| Unknown       | Unknown                     | [6d7bac1be1](https://bsd-hardware.info/?probe=6d7bac1be1) | Feb 23, 2021 |
| Intel         | Q3XXG4-P V1.0               | [60d084275e](https://bsd-hardware.info/?probe=60d084275e) | Feb 19, 2021 |
| Gigabyte      | J4005ND2P-CF                | [8d8683565a](https://bsd-hardware.info/?probe=8d8683565a) | Feb 13, 2021 |
| ASRock        | D1800B-ITX                  | [38f8b13f43](https://bsd-hardware.info/?probe=38f8b13f43) | Feb 10, 2021 |
| Unknown       | Unknown                     | [f4b7bb4518](https://bsd-hardware.info/?probe=f4b7bb4518) | Feb 08, 2021 |
| Dell          | 096JG8 A00                  | [b6630c8516](https://bsd-hardware.info/?probe=b6630c8516) | Feb 07, 2021 |
| Dell          | 096JG8 A00                  | [e73a728a76](https://bsd-hardware.info/?probe=e73a728a76) | Feb 03, 2021 |
| Dell          | 096JG8 A00                  | [612272e598](https://bsd-hardware.info/?probe=612272e598) | Feb 03, 2021 |
| ASUSTek       | PRIME H310M-D R2.0          | [b26cfcd81d](https://bsd-hardware.info/?probe=b26cfcd81d) | Dec 28, 2020 |
| ASUSTek       | E45M1-I DELUXE              | [8e767b517d](https://bsd-hardware.info/?probe=8e767b517d) | Dec 16, 2020 |
| HP            | 213D A01                    | [ca6ab5347e](https://bsd-hardware.info/?probe=ca6ab5347e) | Nov 13, 2020 |
| Shuttle       | FH270                       | [532cda62a8](https://bsd-hardware.info/?probe=532cda62a8) | Oct 29, 2020 |
| Intel         | D53427RKE G87971-406        | [bb6eeb8ef8](https://bsd-hardware.info/?probe=bb6eeb8ef8) | Oct 29, 2020 |
| Shuttle       | FH270                       | [e93928c59b](https://bsd-hardware.info/?probe=e93928c59b) | Oct 29, 2020 |
| ASRock        | QC5000M-ITX/PH              | [8d27c35122](https://bsd-hardware.info/?probe=8d27c35122) | Oct 29, 2020 |
| Dell          | 06NWYK A01                  | [9d4ea8797b](https://bsd-hardware.info/?probe=9d4ea8797b) | Oct 29, 2020 |
| Dell          | 06NWYK A01                  | [5ae47d058d](https://bsd-hardware.info/?probe=5ae47d058d) | Oct 29, 2020 |
| PC Engines    | apu1                        | [c77b06b3eb](https://bsd-hardware.info/?probe=c77b06b3eb) | Oct 20, 2020 |
| Wistron       | ProLiant ML110 G5           | [4906f28cfc](https://bsd-hardware.info/?probe=4906f28cfc) | Aug 14, 2020 |
| ASUSTek       | AM1M-A                      | [4dca0d2aa4](https://bsd-hardware.info/?probe=4dca0d2aa4) | Aug 14, 2020 |
| PC Engines    | APU2                        | [82f64585b8](https://bsd-hardware.info/?probe=82f64585b8) | Aug 14, 2020 |
| Fujitsu       | D3003-B1 S26361-D3003-B1    | [8c92fcf25f](https://bsd-hardware.info/?probe=8c92fcf25f) | Aug 14, 2020 |
| Fujitsu       | D3003-B1 S26361-D3003-B1    | [b6a4e39a1b](https://bsd-hardware.info/?probe=b6a4e39a1b) | Aug 14, 2020 |
| ASRock        | N3150B-ITX                  | [2b9248155e](https://bsd-hardware.info/?probe=2b9248155e) | Jun 09, 2020 |
| ASUSTek       | N3150I-C                    | [3da71be3c9](https://bsd-hardware.info/?probe=3da71be3c9) | Jun 09, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| FreeBSD 13.1-p8      | 9        | 4.15%   |
| helloSystem 0.7.0    | 8        | 3.69%   |
| OpenBSD 7.0          | 7        | 3.23%   |
| OPNsense 23.1        | 6        | 2.76%   |
| OPNsense 22.7.10     | 6        | 2.76%   |
| OPNsense 23.1.7      | 5        | 2.3%    |
| OPNsense 23.1.11     | 5        | 2.3%    |
| helloSystem 0.8.1    | 5        | 2.3%    |
| OPNsense 23.1.8      | 4        | 1.84%   |
| OPNsense 23.1.5      | 4        | 1.84%   |
| OPNsense 23.1.1      | 4        | 1.84%   |
| OPNsense 22.7.4      | 4        | 1.84%   |
| OPNsense 22.1.10     | 4        | 1.84%   |
| helloSystem 0.6.0    | 4        | 1.84%   |
| FreeBSD 12.3-p2      | 4        | 1.84%   |
| OPNsense 23.7.5      | 3        | 1.38%   |
| OPNsense 23.7.4      | 3        | 1.38%   |
| OPNsense 23.7.2      | 3        | 1.38%   |
| OPNsense 23.1.9      | 3        | 1.38%   |
| OPNsense 23.1.3      | 3        | 1.38%   |
| OPNsense 22.7.6      | 3        | 1.38%   |
| OPNsense 22.7.2      | 3        | 1.38%   |
| OPNsense 22.7.11     | 3        | 1.38%   |
| OPNsense 22.1        | 3        | 1.38%   |
| OPNsense 21.7.7      | 3        | 1.38%   |
| OPNsense 21.7.3      | 3        | 1.38%   |
| OPNsense 21.1.2      | 3        | 1.38%   |
| OPNsense 21.1.1      | 3        | 1.38%   |
| OPNsense 21.1        | 3        | 1.38%   |
| helloSystem 0.8.0    | 3        | 1.38%   |
| FreeBSD 14.0-CURRENT | 3        | 1.38%   |
| FreeBSD 13.2         | 3        | 1.38%   |
| FreeBSD 13.0-p5      | 3        | 1.38%   |
| FreeBSD 12.2-p2      | 3        | 1.38%   |
| FreeBSD 12.1-p8      | 3        | 1.38%   |
| FreeBSD 12.1-p13     | 3        | 1.38%   |
| OPNsense 23.7        | 2        | 0.92%   |
| OPNsense 23.1.6      | 2        | 0.92%   |
| OPNsense 22.7.8      | 2        | 0.92%   |
| OPNsense 22.7        | 2        | 0.92%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 94       | 56.63%  |
| FreeBSD     | 39       | 23.49%  |
| helloSystem | 20       | 12.05%  |
| OpenBSD     | 10       | 6.02%   |
| XigmaNAS    | 2        | 1.2%    |
| NetBSD      | 1        | 0.6%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| amd64  | 159      | 95.78%  |
| arm64  | 4        | 2.41%   |
| macppc | 1        | 0.6%    |
| i386   | 1        | 0.6%    |
| armv7  | 1        | 0.6%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Console       | 117      | 69.23%  |
| helloDesktop  | 23       | 13.61%  |
| GNOME         | 12       | 7.1%    |
| fvwm          | 6        | 3.55%   |
| KDE5          | 4        | 2.37%   |
| XFCE          | 3        | 1.78%   |
| TWM           | 1        | 0.59%   |
| Openbox       | 1        | 0.59%   |
| i3            | 1        | 0.59%   |
| Enlightenment | 1        | 0.59%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 127      | 76.51%  |
| X11     | 39       | 23.49%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 130      | 78.31%  |
| SLiM    | 20       | 12.05%  |
| GDM     | 7        | 4.22%   |
| XDM     | 5        | 3.01%   |
| SDDM    | 2        | 1.2%    |
| LightDM | 2        | 1.2%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 115      | 68.86%  |
| en_US   | 24       | 14.37%  |
| C       | 19       | 11.38%  |
| pl_PL   | 6        | 3.59%   |
| pl      | 1        | 0.6%    |
| fr_FR   | 1        | 0.6%    |
| en_GB   | 1        | 0.6%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 145      | 87.35%  |
| BIOS | 21       | 12.65%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Ufs    | 83       | 49.11%  |
| Zfs    | 69       | 40.83%  |
| Ffs    | 10       | 5.92%   |
| Cd9660 | 7        | 4.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 151      | 90.96%  |
| MBR     | 12       | 7.23%   |
| Unknown | 3        | 1.81%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| Gigabyte Technology        | 21       | 12.65%  |
| ASUSTek Computer           | 19       | 11.45%  |
| Unknown                    | 16       | 9.64%   |
| Hewlett-Packard            | 14       | 8.43%   |
| Dell                       | 13       | 7.83%   |
| ASRock                     | 13       | 7.83%   |
| MSI                        | 11       | 6.63%   |
| Intel                      | 11       | 6.63%   |
| Fujitsu                    | 9        | 5.42%   |
| Supermicro                 | 6        | 3.61%   |
| Lenovo                     | 6        | 3.61%   |
| Techvision                 | 4        | 2.41%   |
| PC Engines                 | 4        | 2.41%   |
| Shuttle                    | 3        | 1.81%   |
| ASRockRack                 | 2        | 1.2%    |
| Wistron                    | 1        | 0.6%    |
| ShenZhen MinWin Technology | 1        | 0.6%    |
| Seeed Studio               | 1        | 0.6%    |
| Raspberry Pi Foundation    | 1        | 0.6%    |
| NU591R                     | 1        | 0.6%    |
| Inventec                   | 1        | 0.6%    |
| IGEL Technology            | 1        | 0.6%    |
| iEi                        | 1        | 0.6%    |
| Essentiel B                | 1        | 0.6%    |
| Biostar                    | 1        | 0.6%    |
| Apple                      | 1        | 0.6%    |
| AOpen                      | 1        | 0.6%    |
| AMI                        | 1        | 0.6%    |
| Acer                       | 1        | 0.6%    |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Unknown                        | 16       | 9.64%   |
| HP t620 PLUS Quad Core TC      | 9        | 5.42%   |
| Gigabyte B360N WIFI            | 5        | 3.01%   |
| Fujitsu FUTRO S920             | 5        | 3.01%   |
| Techvision TVI7309X            | 4        | 2.41%   |
| ASUS All Series                | 3        | 1.81%   |
| ASRock Q1900B-ITX              | 3        | 1.81%   |
| Intel SHARKBAY                 | 2        | 1.2%    |
| Intel Q3XXG4-P V1.0            | 2        | 1.2%    |
| Intel D2500CC AAG81477-401     | 2        | 1.2%    |
| Gigabyte H270N-WIFI            | 2        | 1.2%    |
| Gigabyte H110TN                | 2        | 1.2%    |
| Dell OptiPlex 7050             | 2        | 1.2%    |
| Dell OptiPlex 3020             | 2        | 1.2%    |
| ASRock J3455B-ITX              | 2        | 1.2%    |
| Wistron ProLiant ML110 G5      | 1        | 0.6%    |
| Supermicro X9SCL/X9SCM         | 1        | 0.6%    |
| Supermicro X8STi               | 1        | 0.6%    |
| Supermicro X8SIL               | 1        | 0.6%    |
| Supermicro X7SLA               | 1        | 0.6%    |
| Supermicro X7DCL               | 1        | 0.6%    |
| Supermicro SYS-E300-9A-4CN10P  | 1        | 0.6%    |
| Shuttle XH270                  | 1        | 0.6%    |
| Shuttle SZ270R9                | 1        | 0.6%    |
| Shuttle SZ270                  | 1        | 0.6%    |
| ShenZhen MinWin MW-NANO-APL-4L | 1        | 0.6%    |
| Seeed Studio ODYSSEY-X86J4125  | 1        | 0.6%    |
| RPi Raspberry Pi 400           | 1        | 0.6%    |
| PC Engines apu6                | 1        | 0.6%    |
| PC Engines apu4                | 1        | 0.6%    |
| PC Engines APU2                | 1        | 0.6%    |
| PC Engines apu1                | 1        | 0.6%    |
| NU591R NU591R                  | 1        | 0.6%    |
| MSI MS-9A65                    | 1        | 0.6%    |
| MSI MS-7D25                    | 1        | 0.6%    |
| MSI MS-7C52                    | 1        | 0.6%    |
| MSI MS-7C51                    | 1        | 0.6%    |
| MSI MS-7B53                    | 1        | 0.6%    |
| MSI MS-7996                    | 1        | 0.6%    |
| MSI MS-7923                    | 1        | 0.6%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Unknown                        | 16       | 9.64%   |
| HP t620                        | 9        | 5.42%   |
| Dell OptiPlex                  | 9        | 5.42%   |
| Fujitsu FUTRO                  | 7        | 4.22%   |
| Lenovo ThinkCentre             | 5        | 3.01%   |
| Gigabyte B360N                 | 5        | 3.01%   |
| Techvision TVI7309X            | 4        | 2.41%   |
| HP Compaq                      | 3        | 1.81%   |
| ASUS PRIME                     | 3        | 1.81%   |
| ASUS All                       | 3        | 1.81%   |
| ASRock Q1900B-ITX              | 3        | 1.81%   |
| Intel SHARKBAY                 | 2        | 1.2%    |
| Intel Q3XXG4-P                 | 2        | 1.2%    |
| Intel D2500CC                  | 2        | 1.2%    |
| HP EliteDesk                   | 2        | 1.2%    |
| Gigabyte H270N-WIFI            | 2        | 1.2%    |
| Gigabyte H110TN                | 2        | 1.2%    |
| Gigabyte B450M                 | 2        | 1.2%    |
| Dell Vostro                    | 2        | 1.2%    |
| ASUS P5G41T-M                  | 2        | 1.2%    |
| ASRock J3455B-ITX              | 2        | 1.2%    |
| Wistron ProLiant               | 1        | 0.6%    |
| Supermicro X9SCL               | 1        | 0.6%    |
| Supermicro X8STi               | 1        | 0.6%    |
| Supermicro X8SIL               | 1        | 0.6%    |
| Supermicro X7SLA               | 1        | 0.6%    |
| Supermicro X7DCL               | 1        | 0.6%    |
| Supermicro SYS-E300-9A-4CN10P  | 1        | 0.6%    |
| Shuttle XH270                  | 1        | 0.6%    |
| Shuttle SZ270R9                | 1        | 0.6%    |
| Shuttle SZ270                  | 1        | 0.6%    |
| ShenZhen MinWin MW-NANO-APL-4L | 1        | 0.6%    |
| Seeed Studio ODYSSEY-X86J4125  | 1        | 0.6%    |
| RPi Raspberry                  | 1        | 0.6%    |
| PC Engines apu6                | 1        | 0.6%    |
| PC Engines apu4                | 1        | 0.6%    |
| PC Engines APU2                | 1        | 0.6%    |
| PC Engines apu1                | 1        | 0.6%    |
| NU591R NU591R                  | 1        | 0.6%    |
| MSI MS-9A65                    | 1        | 0.6%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2014    | 33       | 19.88%  |
| 2018    | 19       | 11.45%  |
| 2012    | 15       | 9.04%   |
| 2022    | 14       | 8.43%   |
| 2020    | 13       | 7.83%   |
| 2016    | 13       | 7.83%   |
| 2019    | 10       | 6.02%   |
| 2021    | 9        | 5.42%   |
| 2009    | 7        | 4.22%   |
| 2017    | 6        | 3.61%   |
| 2013    | 6        | 3.61%   |
| 2015    | 5        | 3.01%   |
| 2011    | 5        | 3.01%   |
| 2010    | 4        | 2.41%   |
| Unknown | 4        | 2.41%   |
| 2007    | 2        | 1.2%    |
| 2023    | 1        | 0.6%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 166      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 162      | 97.59%  |
| Yes  | 4        | 2.41%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 58       | 34.12%  |
| 4.01-8.0    | 44       | 25.88%  |
| 16.01-24.0  | 43       | 25.29%  |
| 32.01-64.0  | 8        | 4.71%   |
| 2.01-3.0    | 5        | 2.94%   |
| 3.01-4.0    | 4        | 2.35%   |
| 0.51-1.0    | 4        | 2.35%   |
| 24.01-32.0  | 2        | 1.18%   |
| 64.01-256.0 | 1        | 0.59%   |
| 1.01-2.0    | 1        | 0.59%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 0.01-0.5  | 96       | 54.86%  |
| 0.51-1.0  | 51       | 29.14%  |
| 1.01-2.0  | 14       | 8%      |
| 4.01-8.0  | 4        | 2.29%   |
| 2.01-3.0  | 4        | 2.29%   |
| 8.01-16.0 | 2        | 1.14%   |
| 0         | 2        | 1.14%   |
| 3.01-4.0  | 1        | 0.57%   |
| Unknown   | 1        | 0.57%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 96       | 54.55%  |
| 2      | 36       | 20.45%  |
| 0      | 15       | 8.52%   |
| 3      | 12       | 6.82%   |
| 6      | 6        | 3.41%   |
| 4      | 5        | 2.84%   |
| 5      | 3        | 1.7%    |
| 9      | 2        | 1.14%   |
| 10     | 1        | 0.57%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 138      | 82.14%  |
| Yes       | 30       | 17.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 161      | 96.99%  |
| No        | 5        | 3.01%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 120      | 71.43%  |
| Yes       | 48       | 28.57%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 143      | 86.14%  |
| Yes       | 23       | 13.86%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Poland  | 166      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Warsaw            | 24       | 12.83%  |
| Wroclaw           | 15       | 8.02%   |
| Krakow            | 12       | 6.42%   |
| Gdansk            | 12       | 6.42%   |
| Lublin            | 6        | 3.21%   |
| Poznan            | 5        | 2.67%   |
| Lodz              | 5        | 2.67%   |
| Miedziana Gora    | 3        | 1.6%    |
| Lezno             | 3        | 1.6%    |
| Gmina Świebodzin | 3        | 1.6%    |
| Bydgoszcz         | 3        | 1.6%    |
| Е»ukowo         | 2        | 1.07%   |
| Zgierz            | 2        | 1.07%   |
| Walendow          | 2        | 1.07%   |
| Siedlce           | 2        | 1.07%   |
| Radzionkow        | 2        | 1.07%   |
| Police            | 2        | 1.07%   |
| Legionowo         | 2        | 1.07%   |
| Kielce            | 2        | 1.07%   |
| Jelenia Góra     | 2        | 1.07%   |
| Glincz            | 2        | 1.07%   |
| Gdynia            | 2        | 1.07%   |
| Chorzów          | 2        | 1.07%   |
| Choroszcz         | 2        | 1.07%   |
| Zajaczki Pierwsze | 1        | 0.53%   |
| Zagnansk          | 1        | 0.53%   |
| WЕ‚ocЕ‚awek | 1        | 0.53%   |
| Włocławek       | 1        | 0.53%   |
| Wolsztyn          | 1        | 0.53%   |
| Witkow            | 1        | 0.53%   |
| Wejherowo         | 1        | 0.53%   |
| Walcz             | 1        | 0.53%   |
| Tychy             | 1        | 0.53%   |
| Torun             | 1        | 0.53%   |
| Szczytno          | 1        | 0.53%   |
| Swadzim           | 1        | 0.53%   |
| Sulejowek         | 1        | 0.53%   |
| Sulechow          | 1        | 0.53%   |
| Suchedniow        | 1        | 0.53%   |
| Stopnica          | 1        | 0.53%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 41       | 96     | 18.47%  |
| Seagate             | 29       | 55     | 13.06%  |
| Samsung Electronics | 24       | 52     | 10.81%  |
| GOODRAM             | 17       | 30     | 7.66%   |
| SanDisk             | 15       | 20     | 6.76%   |
| A-DATA Technology   | 13       | 16     | 5.86%   |
| Kingston            | 10       | 11     | 4.5%    |
| Toshiba             | 9        | 18     | 4.05%   |
| SPCC                | 5        | 9      | 2.25%   |
| Hoodisk             | 5        | 10     | 2.25%   |
| OCZ                 | 4        | 4      | 1.8%    |
| Innodisk            | 4        | 6      | 1.8%    |
| Apacer              | 4        | 4      | 1.8%    |
| PNY                 | 3        | 7      | 1.35%   |
| Patriot             | 3        | 3      | 1.35%   |
| LITEON              | 3        | 3      | 1.35%   |
| Crucial             | 3        | 4      | 1.35%   |
| Corsair             | 3        | 5      | 1.35%   |
| China               | 3        | 3      | 1.35%   |
| Transcend           | 2        | 7      | 0.9%    |
| Plextor             | 2        | 2      | 0.9%    |
| Kston               | 2        | 2      | 0.9%    |
| Intel               | 2        | 2      | 0.9%    |
| Hitachi             | 2        | 2      | 0.9%    |
| Gigabyte Technology | 2        | 2      | 0.9%    |
| Fanxiang            | 2        | 3      | 0.9%    |
| Team                | 1        | 1      | 0.45%   |
| SSDPR-CX            | 1        | 1      | 0.45%   |
| SK hynix            | 1        | 1      | 0.45%   |
| Silicon Motion      | 1        | 1      | 0.45%   |
| Phison              | 1        | 1      | 0.45%   |
| NVMe                | 1        | 2      | 0.45%   |
| Micron Technology   | 1        | 6      | 0.45%   |
| Lexar               | 1        | 1      | 0.45%   |
| Intenso             | 1        | 2      | 0.45%   |
| HGST                | 1        | 2      | 0.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| WDC WDS500G1R0A-68A4W0 500GB       | 6        | 2.32%   |
| WDC WD5000LPLX-22ZNTT0 500GB       | 5        | 1.93%   |
| Seagate ST1000DM003-1CH162 1TB     | 4        | 1.54%   |
| WDC WD20EFRX-68EUZN0 2TB           | 3        | 1.16%   |
| Seagate ST500DM002-1BD142 500GB    | 3        | 1.16%   |
| Kingston SUV500MS120G 120GB        | 3        | 1.16%   |
| Innodisk DEMSR- 16GB mSATA 3ME3    | 3        | 1.16%   |
| Hoodisk SSD 128GB                  | 3        | 1.16%   |
| GOODRAM SSDPR-CX400-128 128GB      | 3        | 1.16%   |
| GOODRAM SSDPR-CL100-120-G3 120GB   | 3        | 1.16%   |
| WDC WD20SDZW-11JJ8S0 2TB           | 2        | 0.77%   |
| WDC WD20NMVW-59EDZS7 2TB           | 2        | 0.77%   |
| WDC WD20EARS-00MVWB0 2TB           | 2        | 0.77%   |
| WDC WD10JPLX-00MBPT0 1TB           | 2        | 0.77%   |
| Toshiba MQ04ABF100 1TB             | 2        | 0.77%   |
| SPCC Solid State Disk 256GB        | 2        | 0.77%   |
| Seagate ST96812AS 64GB             | 2        | 0.77%   |
| Seagate ST500LT012-1DG142 500GB    | 2        | 0.77%   |
| Seagate ST4000LM024-2U817V 4TB     | 2        | 0.77%   |
| Seagate ST4000LM024-2AN17V 4TB     | 2        | 0.77%   |
| Seagate ST2000DL003-9VT166 2TB     | 2        | 0.77%   |
| Seagate ST1000LM035-1RK172 1TB     | 2        | 0.77%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2        | 0.77%   |
| Seagate ST1000DM010-2EP102 1TB     | 2        | 0.77%   |
| SanDisk X600 M.2 2280 SATA 128GB   | 2        | 0.77%   |
| SanDisk SDSA6MM-016G-1006 16GB     | 2        | 0.77%   |
| Samsung SSD 870 QVO 1TB            | 2        | 0.77%   |
| Samsung SSD 860 EVO 250GB          | 2        | 0.77%   |
| Samsung SSD 850 EVO 250GB          | 2        | 0.77%   |
| PNY CS900 120GB SSD                | 2        | 0.77%   |
| Patriot Burst 120GB                | 2        | 0.77%   |
| Kingston SA400S37240G 240GB        | 2        | 0.77%   |
| GOODRAM SSDPR-CX400-256-G2 256GB   | 2        | 0.77%   |
| GOODRAM SSDPR-CX400-256 256GB      | 2        | 0.77%   |
| Fanxiang S501 128GB                | 2        | 0.77%   |
| Corsair CMFSSD-256D1 256GB         | 2        | 0.77%   |
| China SATA SSD 32GB                | 2        | 0.77%   |
| Apacer AS340 240GB                 | 2        | 0.77%   |
| A-DATA SU800 256GB                 | 2        | 0.77%   |
| A-DATA LEGEND 710 256GB            | 2        | 0.77%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 37       | 75     | 43.02%  |
| Seagate             | 29       | 55     | 33.72%  |
| Toshiba             | 9        | 18     | 10.47%  |
| Samsung Electronics | 6        | 13     | 6.98%   |
| Hitachi             | 2        | 2      | 2.33%   |
| SSDPR-CX            | 1        | 1      | 1.16%   |
| NVMe                | 1        | 2      | 1.16%   |
| HGST                | 1        | 2      | 1.16%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| SanDisk             | 15       | 20     | 12.4%   |
| Samsung Electronics | 15       | 33     | 12.4%   |
| GOODRAM             | 15       | 26     | 12.4%   |
| WDC                 | 9        | 20     | 7.44%   |
| Kingston            | 9        | 9      | 7.44%   |
| A-DATA Technology   | 8        | 10     | 6.61%   |
| SPCC                | 5        | 9      | 4.13%   |
| Hoodisk             | 5        | 10     | 4.13%   |
| OCZ                 | 4        | 4      | 3.31%   |
| Innodisk            | 4        | 6      | 3.31%   |
| Apacer              | 4        | 4      | 3.31%   |
| Crucial             | 3        | 4      | 2.48%   |
| Corsair             | 3        | 5      | 2.48%   |
| China               | 3        | 3      | 2.48%   |
| Transcend           | 2        | 7      | 1.65%   |
| PNY                 | 2        | 5      | 1.65%   |
| Plextor             | 2        | 2      | 1.65%   |
| Patriot             | 2        | 2      | 1.65%   |
| LITEON              | 2        | 2      | 1.65%   |
| Kston               | 2        | 2      | 1.65%   |
| Gigabyte Technology | 2        | 2      | 1.65%   |
| Team                | 1        | 1      | 0.83%   |
| Phison              | 1        | 1      | 0.83%   |
| Micron Technology   | 1        | 6      | 0.83%   |
| Intenso             | 1        | 2      | 0.83%   |
| Intel               | 1        | 1      | 0.83%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 104      | 196    | 54.45%  |
| HDD  | 63       | 168    | 32.98%  |
| NVMe | 24       | 30     | 12.57%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 139      | 364    | 85.28%  |
| NVMe | 24       | 30     | 14.72%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 117      | 230    | 67.63%  |
| 0.51-1.0   | 31       | 64     | 17.92%  |
| 1.01-2.0   | 14       | 38     | 8.09%   |
| 3.01-4.0   | 5        | 9      | 2.89%   |
| 4.01-10.0  | 4        | 11     | 2.31%   |
| 2.01-3.0   | 2        | 12     | 1.16%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 71       | 40.34%  |
| 1-20           | 25       | 14.2%   |
| 51-100         | 24       | 13.64%  |
| 251-500        | 22       | 12.5%   |
| 501-1000       | 17       | 9.66%   |
| 21-50          | 13       | 7.39%   |
| 1001-2000      | 2        | 1.14%   |
| More than 3000 | 1        | 0.57%   |
| 2001-3000      | 1        | 0.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 149      | 86.13%  |
| 21-50          | 8        | 4.62%   |
| 101-250        | 6        | 3.47%   |
| 251-500        | 4        | 2.31%   |
| 51-100         | 3        | 1.73%   |
| 1001-2000      | 2        | 1.16%   |
| More than 3000 | 1        | 0.58%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| WDC WD5000LPLX-22ZNTT0 500GB        | 2        | 2      | 6.67%   |
| Toshiba MQ04ABF100 1TB              | 2        | 2      | 6.67%   |
| Seagate ST96812AS 64GB              | 2        | 5      | 6.67%   |
| Seagate ST1000DM003-1CH162 1TB      | 2        | 2      | 6.67%   |
| WDC WD7500BPKT-00PK4T0 752GB        | 1        | 1      | 3.33%   |
| WDC WD360ADFD-00NLR1 37GB           | 1        | 1      | 3.33%   |
| WDC WD3200AAVS-00ZTB0 320GB         | 1        | 1      | 3.33%   |
| WDC WD2500AAKX-753CA0 250GB         | 1        | 1      | 3.33%   |
| WDC WD2500AAKX-083CA1 250GB         | 1        | 2      | 3.33%   |
| WDC WD20NPVX-00EA4T0 2TB            | 1        | 2      | 3.33%   |
| WDC WD20EZRX-00D8PB0 2TB            | 1        | 1      | 3.33%   |
| WDC WD20EURS-63S48Y0 2TB            | 1        | 1      | 3.33%   |
| WDC WD20EARS-00MVWB0 2TB            | 1        | 1      | 3.33%   |
| WDC WD1600BEVE-00UYT0 160GB         | 1        | 1      | 3.33%   |
| WDC WD10EARS-003BB1 1TB             | 1        | 1      | 3.33%   |
| Toshiba MK3261GSYN 320GB            | 1        | 1      | 3.33%   |
| Seagate ST500DM002-1BD142 500GB     | 1        | 1      | 3.33%   |
| Seagate ST32000542AS 2TB            | 1        | 1      | 3.33%   |
| Seagate ST2000LM015-2E8174 2TB      | 1        | 2      | 3.33%   |
| Seagate ST2000DL003-9VT166 2TB      | 1        | 1      | 3.33%   |
| SanDisk SSD U100 64GB               | 1        | 3      | 3.33%   |
| Samsung Electronics SSD 870 EVO 1TB | 1        | 1      | 3.33%   |
| Samsung Electronics HD154UI 1.5TB   | 1        | 1      | 3.33%   |
| Hitachi HTS721060G9SA00 64GB        | 1        | 1      | 3.33%   |
| Crucial CT525MX300SSD1 528GB        | 1        | 1      | 3.33%   |
| A-DATA Technology SU800 256GB       | 1        | 1      | 3.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 15     | 41.38%  |
| Seagate             | 8        | 12     | 27.59%  |
| Toshiba             | 3        | 3      | 10.34%  |
| Samsung Electronics | 2        | 2      | 6.9%    |
| SanDisk             | 1        | 3      | 3.45%   |
| Hitachi             | 1        | 1      | 3.45%   |
| Crucial             | 1        | 1      | 3.45%   |
| A-DATA Technology   | 1        | 1      | 3.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 15     | 48%     |
| Seagate             | 8        | 12     | 32%     |
| Toshiba             | 3        | 3      | 12%     |
| Samsung Electronics | 1        | 1      | 4%      |
| Hitachi             | 1        | 1      | 4%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 23       | 32     | 85.19%  |
| SSD  | 4        | 6      | 14.81%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| WDC WD20EARS-00MVWB0 2TB        | 1        | 1      | 50%     |
| SanDisk SD9SN8W-256G-1006 256GB | 1        | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 50%     |
| SanDisk | 1        | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 142      | 349    | 81.61%  |
| Malfunc  | 26       | 38     | 14.94%  |
| Detected | 4        | 5      | 2.3%    |
| Failed   | 2        | 2      | 1.15%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 115      | 58.67%  |
| AMD                           | 41       | 20.92%  |
| Samsung Electronics           | 6        | 3.06%   |
| Silicon Motion                | 5        | 2.55%   |
| ADATA Technology              | 4        | 2.04%   |
| SanDisk                       | 3        | 1.53%   |
| Marvell Technology Group      | 3        | 1.53%   |
| JMicron Technology            | 3        | 1.53%   |
| ASMedia Technology            | 3        | 1.53%   |
| Phison Electronics            | 2        | 1.02%   |
| Kingston Technology Company   | 2        | 1.02%   |
| Broadcom / LSI                | 2        | 1.02%   |
| VIA Technologies              | 1        | 0.51%   |
| SK hynix                      | 1        | 0.51%   |
| Shenzhen Longsys Electronics  | 1        | 0.51%   |
| Realtek Semiconductor         | 1        | 0.51%   |
| Nvidia                        | 1        | 0.51%   |
| Lite-On Technology            | 1        | 0.51%   |
| Integrated Technology Express | 1        | 0.51%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 29       | 13.36%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 11       | 5.07%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 10       | 4.61%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 8        | 3.69%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 8        | 3.69%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 8        | 3.69%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 7        | 3.23%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 7        | 3.23%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 6        | 2.76%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 6        | 2.76%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 5        | 2.3%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 5        | 2.3%    |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 5        | 2.3%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 5        | 2.3%    |
| Samsung NVMe SSD Controller 980                                                  | 4        | 1.84%   |
| Intel SATA Controller [RAID mode]                                                | 4        | 1.84%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 4        | 1.84%   |
| AMD 400 Series Chipset SATA Controller                                           | 4        | 1.84%   |
| JMicron JMB363 SATA/IDE Controller                                               | 3        | 1.38%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3        | 1.38%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3        | 1.38%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 3        | 1.38%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 2        | 0.92%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller            | 2        | 0.92%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2        | 0.92%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2        | 0.92%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 2        | 0.92%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 2        | 0.92%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 2        | 0.92%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]              | 2        | 0.92%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                     | 2        | 0.92%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]    | 2        | 0.92%   |
| AMD FCH SATA Controller D                                                        | 2        | 0.92%   |
| AMD 500 Series Chipset SATA Controller                                           | 2        | 0.92%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 2        | 0.92%   |
| ADATA ADATA XPG GAMMIXS1 1L Media (256 GB SSD)                                   | 2        | 0.92%   |
| VIA VX900 Series Serial-ATA Controller                                           | 1        | 0.46%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 1        | 0.46%   |
| Shenzhen Longsys Lexar NM620 NVME SSD (DRAM-less)                                | 1        | 0.46%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1        | 0.46%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 139      | 72.02%  |
| NVMe | 26       | 13.47%  |
| IDE  | 22       | 11.4%   |
| RAID | 4        | 2.07%   |
| SAS  | 1        | 0.52%   |
| SCSI | 1        | 0.52%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 117      | 70.06%  |
| AMD     | 43       | 25.75%  |
| ARM     | 5        | 2.99%   |
| VIA     | 1        | 0.6%    |
| PowerPC | 1        | 0.6%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD GX-420CA SOC with Radeon HD Graphics    | 9        | 5.39%   |
| Intel Celeron N5105 @ 2.00GHz               | 5        | 2.99%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 5        | 2.99%   |
| AMD GX-415GA SOC with Radeon HD Graphics    | 5        | 2.99%   |
| Intel Core i3-8300T CPU @ 3.20GHz           | 4        | 2.4%    |
| Intel Core i3-6100 CPU @ 3.70GHz            | 4        | 2.4%    |
| Intel Celeron J4125 CPU @ 2.00GHz           | 4        | 2.4%    |
| Intel Core i5-4590 CPU @ 3.30GHz            | 3        | 1.8%    |
| Intel Core i5-4570 CPU @ 3.20GHz            | 3        | 1.8%    |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3        | 1.8%    |
| Intel Celeron CPU J3455 @ 1.50GHz           | 3        | 1.8%    |
| Intel Atom CPU D2500 @ 1.86GHz              | 3        | 1.8%    |
| AMD Phenom II X4 965 Processor              | 3        | 1.8%    |
| AMD GX-412TC SOC                            | 3        | 1.8%    |
| Intel Pentium CPU G860 @ 3.00GHz            | 2        | 1.2%    |
| Intel Pentium CPU G4600T @ 3.00GHz          | 2        | 1.2%    |
| Intel Pentium CPU G3220 @ 3.00GHz           | 2        | 1.2%    |
| Intel Core i7-8700 CPU @ 3.20GHz            | 2        | 1.2%    |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 1.2%    |
| Intel Core i5-6400T CPU @ 2.20GHz           | 2        | 1.2%    |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 1.2%    |
| Intel Celeron CPU N3150 @ 1.60GHz           | 2        | 1.2%    |
| ARM Cortex-A72 r0p3                         | 2        | 1.2%    |
| ARM Cortex-A55 r2p0                         | 2        | 1.2%    |
| AMD Ryzen 5 1600X Six-Core Processor        | 2        | 1.2%    |
| AMD Ryzen 3 3100 4-Core Processor           | 2        | 1.2%    |
| VIA Nano U3100 (1.6GHz Capable)             | 1        | 0.6%    |
| PowerPC 7447A (Revision 0x102)              | 1        | 0.6%    |
| Intel Xeon CPU X3430 @ 2.40GHz              | 1        | 0.6%    |
| Intel Xeon CPU W3565 @ 3.20GHz              | 1        | 0.6%    |
| Intel Xeon CPU E5410 @ 2.33GHz              | 1        | 0.6%    |
| Intel Xeon CPU E5-2650 v3 @ 2.30GHz         | 1        | 0.6%    |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz         | 1        | 0.6%    |
| Intel Xeon CPU E31225 @ 3.10GH              | 1        | 0.6%    |
| Intel Xeon CPU E31220 @ 3.10GHz             | 1        | 0.6%    |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 1        | 0.6%    |
| Intel Pentium Silver N6005 @ 2.00GHz        | 1        | 0.6%    |
| Intel Pentium Dual-Core CPU E6              | 1        | 0.6%    |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 0.6%    |
| Intel Pentium CPU G620 @ 2.60GHz            | 1        | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 30       | 17.96%  |
| Intel Celeron           | 29       | 17.37%  |
| AMD GX                  | 18       | 10.78%  |
| Intel Core i3           | 14       | 8.38%   |
| Intel Pentium           | 10       | 5.99%   |
| Intel Core i7           | 10       | 5.99%   |
| Intel Xeon              | 8        | 4.79%   |
| Intel Atom              | 7        | 4.19%   |
| Other                   | 5        | 2.99%   |
| ARM Cortex              | 5        | 2.99%   |
| AMD Ryzen 3             | 5        | 2.99%   |
| AMD Ryzen 5             | 4        | 2.4%    |
| AMD Phenom II X4        | 3        | 1.8%    |
| AMD G                   | 3        | 1.8%    |
| Intel Pentium Dual-Core | 2        | 1.2%    |
| AMD Ryzen 9             | 2        | 1.2%    |
| AMD Ryzen 7             | 2        | 1.2%    |
| Intel Pentium Silver    | 1        | 0.6%    |
| Intel Core 2 Quad       | 1        | 0.6%    |
| Intel Core 2 Duo        | 1        | 0.6%    |
| Intel Core 2            | 1        | 0.6%    |
| AMD Ryzen 5 PRO         | 1        | 0.6%    |
| AMD Phenom II X6        | 1        | 0.6%    |
| AMD E                   | 1        | 0.6%    |
| AMD Athlon 64 X2        | 1        | 0.6%    |
| AMD Athlon              | 1        | 0.6%    |
| AMD A4                  | 1        | 0.6%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 92       | 55.09%  |
| 2       | 40       | 23.95%  |
| Unknown | 10       | 5.99%   |
| 8       | 6        | 3.59%   |
| 6       | 6        | 3.59%   |
| 12      | 4        | 2.4%    |
| 1       | 4        | 2.4%    |
| 16      | 2        | 1.2%    |
| 32      | 1        | 0.6%    |
| 24      | 1        | 0.6%    |
| 20      | 1        | 0.6%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 156      | 93.98%  |
| Unknown | 8        | 4.82%   |
| 2       | 2        | 1.2%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 121      | 72.46%  |
| 2       | 34       | 20.36%  |
| Unknown | 12       | 7.19%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 20       | 11.98%  |
| Unknown       | 18       | 10.78%  |
| KabyLake      | 17       | 10.18%  |
| Jaguar        | 17       | 10.18%  |
| Skylake       | 13       | 7.78%   |
| Silvermont    | 10       | 5.99%   |
| SandyBridge   | 10       | 5.99%   |
| Penryn        | 7        | 4.19%   |
| IvyBridge     | 7        | 4.19%   |
| Goldmont plus | 7        | 4.19%   |
| Zen           | 5        | 2.99%   |
| Goldmont      | 5        | 2.99%   |
| Bonnell       | 5        | 2.99%   |
| Zen 2         | 4        | 2.4%    |
| K10           | 4        | 2.4%    |
| Bobcat        | 4        | 2.4%    |
| Zen 3         | 3        | 1.8%    |
| Puma          | 3        | 1.8%    |
| Nehalem       | 2        | 1.2%    |
| Zen+          | 1        | 0.6%    |
| Westmere      | 1        | 0.6%    |
| K8 Hammer     | 1        | 0.6%    |
| Core          | 1        | 0.6%    |
| CometLake     | 1        | 0.6%    |
| Broadwell     | 1        | 0.6%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 99       | 60.37%  |
| AMD                                          | 39       | 23.78%  |
| Nvidia                                       | 17       | 10.37%  |
| Matrox Electronics Systems                   | 4        | 2.44%   |
| ASPEED Technology                            | 3        | 1.83%   |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.61%   |
| VIA Technologies                             | 1        | 0.61%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 12       | 7.27%   |
| Intel HD Graphics 530                                                                    | 10       | 6.06%   |
| AMD Kabini [Radeon HD 8400E]                                                             | 9        | 5.45%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7        | 4.24%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7        | 4.24%   |
| Intel JasperLake [UHD Graphics]                                                          | 6        | 3.64%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 6        | 3.64%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6        | 3.64%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6        | 3.64%   |
| AMD Kabini [Radeon HD 8330E]                                                             | 5        | 3.03%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4        | 2.42%   |
| Intel HD Graphics 630                                                                    | 4        | 2.42%   |
| Intel HD Graphics 500                                                                    | 4        | 2.42%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4        | 2.42%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4        | 2.42%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 3        | 1.82%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 3        | 1.82%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3        | 1.82%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 3        | 1.82%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 2        | 1.21%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2        | 1.21%   |
| Intel HD Graphics 510                                                                    | 2        | 1.21%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 2        | 1.21%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 2        | 1.21%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 2        | 1.21%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2        | 1.21%   |
| XGI Technology (eXtreme Graphics Innovation) Z9s/Z9m (XG21 core)                         | 1        | 0.61%   |
| VIA Technologies VX900 Graphics [Chrome9 HD]                                             | 1        | 0.61%   |
| Nvidia GP104GL [Quadro P4000]                                                            | 1        | 0.61%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 1        | 0.61%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 1        | 0.61%   |
| Nvidia GM206GL [Quadro M2000]                                                            | 1        | 0.61%   |
| Nvidia GM206 [GeForce GTX 950]                                                           | 1        | 0.61%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1        | 0.61%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1        | 0.61%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1        | 0.61%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 1        | 0.61%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 1        | 0.61%   |
| Nvidia GF100 [GeForce GTX 470]                                                           | 1        | 0.61%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                                        | 1        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Intel       | 93       | 55.36%  |
| 1 x AMD         | 36       | 21.43%  |
| 1 x Nvidia      | 14       | 8.33%   |
| Other           | 9        | 5.36%   |
| 1 x Matrox      | 4        | 2.38%   |
| 2 x Intel       | 3        | 1.79%   |
| Intel + Nvidia  | 2        | 1.19%   |
| 1 x XGI         | 1        | 0.6%    |
| 1 x VIA         | 1        | 0.6%    |
| Nvidia + ASPEED | 1        | 0.6%    |
| Intel + AMD     | 1        | 0.6%    |
| 1 x ASPEED      | 1        | 0.6%    |
| AMD + Nvidia    | 1        | 0.6%    |
| AMD + ASPEED    | 1        | 0.6%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 145      | 87.35%  |
| Unknown     | 11       | 6.63%   |
| Proprietary | 10       | 6.02%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 145      | 87.35%  |
| 7.01-8.0   | 6        | 3.61%   |
| 1.01-2.0   | 6        | 3.61%   |
| 3.01-4.0   | 5        | 3.01%   |
| 0.01-0.5   | 2        | 1.2%    |
| 8.01-16.0  | 1        | 0.6%    |
| 0.51-1.0   | 1        | 0.6%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Iiyama              | 8        | 20%     |
| NEC Computers       | 5        | 12.5%   |
| Samsung Electronics | 4        | 10%     |
| Acer                | 4        | 10%     |
| Philips             | 3        | 7.5%    |
| Dell                | 3        | 7.5%    |
| Idek Iiyama         | 2        | 5%      |
| Hewlett-Packard     | 2        | 5%      |
| Goldstar            | 2        | 5%      |
| Vestel Elektronik   | 1        | 2.5%    |
| Toshiba             | 1        | 2.5%    |
| HPN                 | 1        | 2.5%    |
| Eizo                | 1        | 2.5%    |
| BenQ                | 1        | 2.5%    |
| AOC                 | 1        | 2.5%    |
| Unknown             | 1        | 2.5%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Iiyama PL2775HD IVM6604 1920x1080 600x340mm 27.2-inch                 | 6        | 15%     |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch    | 1        | 2.5%    |
| Toshiba TV TSB0110 1920x1080 1110x620mm 50.1-inch                     | 1        | 2.5%    |
| Samsung Electronics U32J59x SAM0F35 3840x2160 700x390mm 31.5-inch     | 1        | 2.5%    |
| Samsung Electronics SyncMaster SAM0304 1680x1050 490x320mm 23.0-inch  | 1        | 2.5%    |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch | 1        | 2.5%    |
| Samsung Electronics LCD Monitor S24F350 1920x1080                     | 1        | 2.5%    |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch               | 1        | 2.5%    |
| Philips LCD Monitor PHLC01A 1680x1050 470x300mm 22.0-inch             | 1        | 2.5%    |
| Philips 150S PHL0820 1024x768 300x230mm 14.9-inch                     | 1        | 2.5%    |
| NEC Computers LCD4020 NEC66EA 1920x540 890x500mm 40.2-inch            | 1        | 2.5%    |
| NEC Computers LCD24WMCX NEC6720 1920x1200 520x320mm 24.0-inch         | 1        | 2.5%    |
| NEC Computers EA294WMi NEC68CF 2560x1080 670x280mm 28.6-inch          | 1        | 2.5%    |
| NEC Computers EA223WM NEC6891 1680x1050 470x300mm 22.0-inch           | 1        | 2.5%    |
| NEC Computers E438 NEC335C 3840x2160 940x530mm 42.5-inch              | 1        | 2.5%    |
| Iiyama PLE2407HDS IVM560D 1920x1080 520x300mm 23.6-inch               | 1        | 2.5%    |
| Iiyama PL2773HD IVM6606 1920x1080 600x340mm 27.2-inch                 | 1        | 2.5%    |
| Idek Iiyama LCD Monitor PL2792UH 3840x2160                            | 1        | 2.5%    |
| Idek Iiyama LCD Monitor PL2209HD 5760x2160                            | 1        | 2.5%    |
| HPN LCD Monitor HP E233 1920x1080                                     | 1        | 2.5%    |
| Hewlett-Packard E221c HWP3092 1920x1080 500x290mm 22.8-inch           | 1        | 2.5%    |
| Hewlett-Packard 19ka HWP3328 1366x768 410x230mm 18.5-inch             | 1        | 2.5%    |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                  | 1        | 2.5%    |
| Goldstar E1942 GSM4C09 1366x768 410x230mm 18.5-inch                   | 1        | 2.5%    |
| Eizo EV2455 ENC2533 1920x1200 520x330mm 24.2-inch                     | 1        | 2.5%    |
| Dell U2515H DELD070 2560x1440 550x310mm 24.9-inch                     | 1        | 2.5%    |
| Dell U2212HM DELD047 1920x1080 480x270mm 21.7-inch                    | 1        | 2.5%    |
| Dell P2312H DEL4076 1920x1080 510x290mm 23.1-inch                     | 1        | 2.5%    |
| BenQ G2255 BNQ78B7 1920x1080 480x270mm 21.7-inch                      | 1        | 2.5%    |
| AOC 2269WM AOC2269 1920x1080 480x270mm 21.7-inch                      | 1        | 2.5%    |
| Acer X193HQ ACR0064 1366x768 400x250mm 18.6-inch                      | 1        | 2.5%    |
| Acer VG220Q ACR06D8 1920x1080 480x270mm 21.7-inch                     | 1        | 2.5%    |
| Acer S240HL ACR0289 1920x1080 530x300mm 24.0-inch                     | 1        | 2.5%    |
| Acer EG220Q ACR06A1 1920x1080 480x270mm 21.7-inch                     | 1        | 2.5%    |
| Unknown                                                               | 1        | 2.5%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 19       | 51.35%  |
| 3840x2160 (4K)     | 4        | 10.81%  |
| 1366x768 (WXGA)    | 3        | 8.11%   |
| 1920x540           | 2        | 5.41%   |
| 1920x1200 (WUXGA)  | 2        | 5.41%   |
| 1680x1050 (WSXGA+) | 2        | 5.41%   |
| 5760x2160          | 1        | 2.7%    |
| 2560x1440 (QHD)    | 1        | 2.7%    |
| 2560x1080          | 1        | 2.7%    |
| 1024x768 (XGA)     | 1        | 2.7%    |
| Unknown            | 1        | 2.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 7        | 18.92%  |
| 24      | 5        | 13.51%  |
| 21      | 5        | 13.51%  |
| Unknown | 4        | 10.81%  |
| 23      | 3        | 8.11%   |
| 18      | 3        | 8.11%   |
| 42      | 2        | 5.41%   |
| 31      | 2        | 5.41%   |
| 22      | 2        | 5.41%   |
| 50      | 1        | 2.7%    |
| 40      | 1        | 2.7%    |
| 28      | 1        | 2.7%    |
| 14      | 1        | 2.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 14       | 37.84%  |
| 401-500     | 10       | 27.03%  |
| Unknown     | 4        | 10.81%  |
| 601-700     | 3        | 8.11%   |
| 901-1000    | 2        | 5.41%   |
| 801-900     | 1        | 2.7%    |
| 351-400     | 1        | 2.7%    |
| 201-300     | 1        | 2.7%    |
| 1001-1500   | 1        | 2.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 24       | 68.57%  |
| 16/10   | 4        | 11.43%  |
| Unknown | 4        | 11.43%  |
| 4/3     | 1        | 2.86%   |
| 3/2     | 1        | 2.86%   |
| 21/9    | 1        | 2.86%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 11       | 30.56%  |
| 301-350        | 7        | 19.44%  |
| 251-300        | 4        | 11.11%  |
| Unknown        | 4        | 11.11%  |
| 501-1000       | 3        | 8.33%   |
| 351-500        | 2        | 5.56%   |
| 141-150        | 2        | 5.56%   |
| More than 1000 | 1        | 2.78%   |
| 151-200        | 1        | 2.78%   |
| 101-110        | 1        | 2.78%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 21       | 60%     |
| 101-120 | 6        | 17.14%  |
| Unknown | 4        | 11.43%  |
| 1-50    | 2        | 5.71%   |
| 121-160 | 2        | 5.71%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 128      | 77.11%  |
| 1     | 33       | 19.88%  |
| 2     | 4        | 2.41%   |
| 3     | 1        | 0.6%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 114      | 46.15%  |
| Realtek Semiconductor           | 87       | 35.22%  |
| Broadcom                        | 14       | 5.67%   |
| Qualcomm Atheros                | 12       | 4.86%   |
| Qualcomm Atheros Communications | 4        | 1.62%   |
| Huawei Technologies             | 2        | 0.81%   |
| Xiaomi                          | 1        | 0.4%    |
| U-Blox                          | 1        | 0.4%    |
| TP-Link                         | 1        | 0.4%    |
| Seeed Technology                | 1        | 0.4%    |
| Ralink                          | 1        | 0.4%    |
| Nuvoton                         | 1        | 0.4%    |
| NetGear                         | 1        | 0.4%    |
| Mellanox Technologies           | 1        | 0.4%    |
| Marvell Technology Group        | 1        | 0.4%    |
| IMC Networks                    | 1        | 0.4%    |
| D-Link System                   | 1        | 0.4%    |
| Apple                           | 1        | 0.4%    |
| American Megatrends             | 1        | 0.4%    |
| 3Com                            | 1        | 0.4%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 79       | 26.16%  |
| Intel I211 Gigabit Network Connection                                         | 25       | 8.28%   |
| Intel I350 Gigabit Network Connection                                         | 11       | 3.64%   |
| Intel I210 Gigabit Network Connection                                         | 10       | 3.31%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 10       | 3.31%   |
| Intel 82574L Gigabit Network Connection                                       | 10       | 3.31%   |
| Intel Ethernet Connection I217-LM                                             | 8        | 2.65%   |
| Intel Ethernet Controller I226-V                                              | 7        | 2.32%   |
| Intel Ethernet Connection (2) I219-V                                          | 7        | 2.32%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 7        | 2.32%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 6        | 1.99%   |
| Intel Ethernet Connection (7) I219-V                                          | 5        | 1.66%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 5        | 1.66%   |
| Intel Ethernet Controller I225-V                                              | 4        | 1.32%   |
| Intel 82580 Gigabit Network Connection                                        | 4        | 1.32%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 4        | 1.32%   |
| Broadcom BCM43228 802.11a/b/g/n                                               | 4        | 1.32%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 3        | 0.99%   |
| Qualcomm Atheros AR9271 802.11n                                               | 3        | 0.99%   |
| Intel Wireless 8260                                                           | 3        | 0.99%   |
| Intel 82576 Gigabit Network Connection                                        | 3        | 0.99%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 3        | 0.99%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 2        | 0.66%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 2        | 0.66%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 2        | 0.66%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2        | 0.66%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 2        | 0.66%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 2        | 0.66%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 2        | 0.66%   |
| Intel Wireless 8265 / 8275                                                    | 2        | 0.66%   |
| Intel Wi-Fi 6 AX200                                                           | 2        | 0.66%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 2        | 0.66%   |
| Intel Ethernet Connection (5) I219-LM                                         | 2        | 0.66%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 2        | 0.66%   |
| Intel 82583V Gigabit Network Connection                                       | 2        | 0.66%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 2        | 0.66%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 1        | 0.33%   |
| U-Blox [u-blox 7]                                                             | 1        | 0.33%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 1        | 0.33%   |
| Seeed Seeeduino_Cortex_M0+                                                    | 1        | 0.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 18       | 35.29%  |
| Qualcomm Atheros                | 10       | 19.61%  |
| Realtek Semiconductor           | 8        | 15.69%  |
| Broadcom                        | 6        | 11.76%  |
| Qualcomm Atheros Communications | 4        | 7.84%   |
| TP-Link                         | 1        | 1.96%   |
| Ralink                          | 1        | 1.96%   |
| NetGear                         | 1        | 1.96%   |
| IMC Networks                    | 1        | 1.96%   |
| D-Link System                   | 1        | 1.96%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel Cannon Lake PCH CNVi WiFi                                               | 5        | 9.8%    |
| Broadcom BCM43228 802.11a/b/g/n                                               | 4        | 7.84%   |
| Qualcomm Atheros AR9271 802.11n                                               | 3        | 5.88%   |
| Intel Wireless 8260                                                           | 3        | 5.88%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 2        | 3.92%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 2        | 3.92%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 2        | 3.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 2        | 3.92%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 2        | 3.92%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 2        | 3.92%   |
| Intel Wireless 8265 / 8275                                                    | 2        | 3.92%   |
| Intel Wi-Fi 6 AX200                                                           | 2        | 3.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 2        | 3.92%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 1        | 1.96%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1        | 1.96%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1        | 1.96%   |
| Ralink RT2561/RT61 rev B 802.11g                                              | 1        | 1.96%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter               | 1        | 1.96%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1        | 1.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1        | 1.96%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1        | 1.96%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 1        | 1.96%   |
| NetGear WN111(v2) RangeMax Next Wireless [Atheros AR9170+AR9101]              | 1        | 1.96%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 1        | 1.96%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                 | 1        | 1.96%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 1        | 1.96%   |
| Intel Alder Lake-S PCH CNVi WiFi                                              | 1        | 1.96%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                          | 1        | 1.96%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]    | 1        | 1.96%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 1        | 1.96%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 1        | 1.96%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 111      | 52.86%  |
| Realtek Semiconductor    | 82       | 39.05%  |
| Broadcom                 | 8        | 3.81%   |
| Qualcomm Atheros         | 3        | 1.43%   |
| Xiaomi                   | 1        | 0.48%   |
| Marvell Technology Group | 1        | 0.48%   |
| Huawei Technologies      | 1        | 0.48%   |
| Apple                    | 1        | 0.48%   |
| American Megatrends      | 1        | 0.48%   |
| 3Com                     | 1        | 0.48%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 79       | 32.11%  |
| Intel I211 Gigabit Network Connection                                          | 25       | 10.16%  |
| Intel I350 Gigabit Network Connection                                          | 11       | 4.47%   |
| Intel I210 Gigabit Network Connection                                          | 10       | 4.07%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 10       | 4.07%   |
| Intel 82574L Gigabit Network Connection                                        | 10       | 4.07%   |
| Intel Ethernet Connection I217-LM                                              | 8        | 3.25%   |
| Intel Ethernet Controller I226-V                                               | 7        | 2.85%   |
| Intel Ethernet Connection (2) I219-V                                           | 7        | 2.85%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications)  | 7        | 2.85%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                     | 6        | 2.44%   |
| Intel Ethernet Connection (7) I219-V                                           | 5        | 2.03%   |
| Intel Ethernet Controller I225-V                                               | 4        | 1.63%   |
| Intel 82580 Gigabit Network Connection                                         | 4        | 1.63%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                               | 4        | 1.63%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 3        | 1.22%   |
| Intel 82576 Gigabit Network Connection                                         | 3        | 1.22%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                             | 3        | 1.22%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2        | 0.81%   |
| Intel I210 Gigabit Fiber Network Connection                                    | 2        | 0.81%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2        | 0.81%   |
| Intel 82583V Gigabit Network Connection                                        | 2        | 0.81%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                           | 2        | 0.81%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1        | 0.41%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1        | 0.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1        | 0.41%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1        | 0.41%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1        | 0.41%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                  | 1        | 0.41%   |
| Intel Ethernet Controller X550                                                 | 1        | 0.41%   |
| Intel Ethernet Connection X553 1GbE                                            | 1        | 0.41%   |
| Intel Ethernet Connection I217-V                                               | 1        | 0.41%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1        | 0.41%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1        | 0.41%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                           | 1        | 0.41%   |
| Intel 82579V Gigabit Network Connection                                        | 1        | 0.41%   |
| Intel 82576NS Gigabit Network Connection                                       | 1        | 0.41%   |
| Intel 82575GB Gigabit Network Connection                                       | 1        | 0.41%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 1        | 0.41%   |
| Intel 82573E Gigabit Ethernet Controller (Copper)                              | 1        | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 161      | 75.23%  |
| WiFi     | 48       | 22.43%  |
| Modem    | 3        | 1.4%    |
| Unknown  | 2        | 0.93%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 153      | 92.73%  |
| WiFi     | 12       | 7.27%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 42       | 24.56%  |
| 3     | 41       | 23.98%  |
| 2     | 34       | 19.88%  |
| 4     | 17       | 9.94%   |
| 6     | 16       | 9.36%   |
| 5     | 14       | 8.19%   |
| 0     | 5        | 2.92%   |
| 10    | 1        | 0.58%   |
| 7     | 1        | 0.58%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 164      | 97.62%  |
| Yes  | 4        | 2.38%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 13       | 56.52%  |
| Cambridge Silicon Radio         | 3        | 13.04%  |
| ASUSTek Computer                | 2        | 8.7%    |
| TP-Link                         | 1        | 4.35%   |
| Qualcomm Atheros Communications | 1        | 4.35%   |
| Qcom                            | 1        | 4.35%   |
| IMC Networks                    | 1        | 4.35%   |
| Apple                           | 1        | 4.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)       | 6        | 26.09%  |
| Intel Bluetooth wireless interface                   | 4        | 17.39%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)  | 3        | 13.04%  |
| TP-Link Bluetooth 5.0 USB Adapter                    | 1        | 4.35%   |
| Qualcomm Atheros AR9462 Bluetooth                    | 1        | 4.35%   |
| Qcom Broadcom BCM2070 Bluetooth 2.1+EDR USB Device   | 1        | 4.35%   |
| Intel AX210 Bluetooth                                | 1        | 4.35%   |
| Intel AX201 Bluetooth                                | 1        | 4.35%   |
| Intel AX200 Bluetooth                                | 1        | 4.35%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip | 1        | 4.35%   |
| ASUS USB-BT500                                       | 1        | 4.35%   |
| ASUS Broadcom BCM20702A0 Bluetooth                   | 1        | 4.35%   |
| Apple Bluetooth Host Controller                      | 1        | 4.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 98       | 60.87%  |
| AMD                 | 40       | 24.84%  |
| Nvidia              | 15       | 9.32%   |
| Creative Labs       | 2        | 1.24%   |
| C-Media Electronics | 2        | 1.24%   |
| VIA Technologies    | 1        | 0.62%   |
| ROCCAT              | 1        | 0.62%   |
| Logitech            | 1        | 0.62%   |
| Creative Technology | 1        | 0.62%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| AMD Kabini HDMI/DP Audio                                                                          | 16       | 8%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 13       | 6.5%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 11       | 5.5%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 10       | 5%      |
| AMD FCH Azalia Controller                                                                         | 10       | 5%      |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8        | 4%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8        | 4%      |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7        | 3.5%    |
| Intel Cannon Lake PCH cAVS                                                                        | 7        | 3.5%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 7        | 3.5%    |
| Intel Jasper Lake HD Audio                                                                        | 6        | 3%      |
| Intel 200 Series PCH HD Audio                                                                     | 6        | 3%      |
| AMD Family 17h/19h HD Audio Controller                                                            | 6        | 3%      |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 6        | 3%      |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5        | 2.5%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4        | 2%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4        | 2%      |
| AMD Starship/Matisse HD Audio Controller                                                          | 4        | 2%      |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 4        | 2%      |
| AMD Wrestler HDMI Audio                                                                           | 3        | 1.5%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3        | 1.5%    |
| AMD Navi 10 HDMI Audio                                                                            | 3        | 1.5%    |
| Nvidia GP106 High Definition Audio Controller                                                     | 2        | 1%      |
| Nvidia GP104 High Definition Audio Controller                                                     | 2        | 1%      |
| Nvidia GM206 High Definition Audio Controller                                                     | 2        | 1%      |
| Intel Sunrise Point-LP HD Audio                                                                   | 2        | 1%      |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2        | 1%      |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2        | 1%      |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 2        | 1%      |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]                         | 2        | 1%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2        | 1%      |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2        | 1%      |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1        | 0.5%    |
| VIA Technologies High Definition Audio Controller                                                 | 1        | 0.5%    |
| ROCCAT USB PnP Sound Device                                                                       | 1        | 0.5%    |
| Nvidia MCP51 High Definition Audio                                                                | 1        | 0.5%    |
| Nvidia GP102 HDMI Audio Controller                                                                | 1        | 0.5%    |
| Nvidia GM204 High Definition Audio Controller                                                     | 1        | 0.5%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1        | 0.5%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1        | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 31       | 18.13%  |
| SK hynix            | 27       | 15.79%  |
| Samsung Electronics | 23       | 13.45%  |
| Unknown             | 20       | 11.7%   |
| GOODRAM             | 13       | 7.6%    |
| Micron Technology   | 12       | 7.02%   |
| Crucial             | 9        | 5.26%   |
| G.Skill             | 8        | 4.68%   |
| Corsair             | 5        | 2.92%   |
| Patriot             | 4        | 2.34%   |
| Wilk                | 3        | 1.75%   |
| Unknown             | 3        | 1.75%   |
| Ramaxel Technology  | 2        | 1.17%   |
| Nanya Technology    | 2        | 1.17%   |
| Unknown (ABCD)      | 1        | 0.58%   |
| Unknown (07FB)      | 1        | 0.58%   |
| Toshiba             | 1        | 0.58%   |
| Qimonda             | 1        | 0.58%   |
| PUSKILL             | 1        | 0.58%   |
| Lexar Co Limited    | 1        | 0.58%   |
| Kimtigo             | 1        | 0.58%   |
| GeIL                | 1        | 0.58%   |
| ATP                 | 1        | 0.58%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s            | 5        | 2.73%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 4        | 2.19%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                    | 3        | 1.64%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s         | 3        | 1.64%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s         | 3        | 1.64%   |
| Unknown                                                      | 3        | 1.64%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2        | 1.09%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s       | 2        | 1.09%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s        | 2        | 1.09%   |
| Samsung RAM M471B5674EB0-YK0 2GB SODIMM DDR3 1600MT/s        | 2        | 1.09%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s        | 2        | 1.09%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s        | 2        | 1.09%   |
| Patriot RAM 1600 CL9 Series 8GB DIMM DDR3 1600MT/s           | 2        | 1.09%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                   | 2        | 1.09%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s        | 2        | 1.09%   |
| Micron RAM 16ATF2G64HZ-2G3H1 16GB SODIMM DDR4 2400MT/s       | 2        | 1.09%   |
| Kingston RAM Module 2GB DIMM DDR3 1333MT/s                   | 2        | 1.09%   |
| Kingston RAM KHX1866C11S3L/4G 4GB SODIMM DDR3 1866MT/s       | 2        | 1.09%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s          | 2        | 1.09%   |
| GOODRAM RAM GR2400D464L17S/8G 8GB DIMM DDR4 2400MT/s         | 2        | 1.09%   |
| G.Skill RAM F4-2400C15-16GIS 16GB DIMM DDR4 2400MT/s         | 2        | 1.09%   |
| Wilk RAM IR2400D464L15S/8G 8GB DIMM DDR4 2400MT/s            | 1        | 0.55%   |
| Wilk RAM GR3200S464L22S/8G 8GB SODIMM DDR4 3200MT/s          | 1        | 0.55%   |
| Wilk RAM GR2666S464L19S/8G 8GB SODIMM DDR4 2667MT/s          | 1        | 0.55%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                    | 1        | 0.55%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                    | 1        | 0.55%   |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s                   | 1        | 0.55%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                  | 1        | 0.55%   |
| Unknown RAM Module 4GB DIMM DDR3                             | 1        | 0.55%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                     | 1        | 0.55%   |
| Unknown RAM Module 2GB DIMM 800MT/s                          | 1        | 0.55%   |
| Unknown RAM Module 2GB DIMM                                  | 1        | 0.55%   |
| Unknown RAM Module 2048MB DIMM DDR3 667MT/s                  | 1        | 0.55%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                  | 1        | 0.55%   |
| Unknown RAM Module 1GB DIMM SDRAM                            | 1        | 0.55%   |
| Unknown RAM Module 16384MB DIMM DDR3 800MT/s                 | 1        | 0.55%   |
| Unknown RAM 8G2400MHz 8GB SODIMM DDR4 2400MT/s               | 1        | 0.55%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 1        | 0.55%   |
| Unknown (07FB) RAM GSA8G4SCL176P-24 8GB SODIMM DDR4 2400MT/s | 1        | 0.55%   |
| Toshiba RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s             | 1        | 0.55%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 79       | 52.32%  |
| DDR4    | 57       | 37.75%  |
| Unknown | 6        | 3.97%   |
| DDR2    | 4        | 2.65%   |
| SDRAM   | 2        | 1.32%   |
| LPDDR4  | 1        | 0.66%   |
| DDR5    | 1        | 0.66%   |
| DDR     | 1        | 0.66%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 95       | 63.33%  |
| SODIMM | 54       | 36%     |
| RIMM   | 1        | 0.67%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 62       | 38.27%  |
| 4096  | 57       | 35.19%  |
| 2048  | 24       | 14.81%  |
| 16384 | 12       | 7.41%   |
| 1024  | 4        | 2.47%   |
| 32768 | 2        | 1.23%   |
| 512   | 1        | 0.62%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 50       | 31.65%  |
| 2400    | 25       | 15.82%  |
| 1333    | 22       | 13.92%  |
| 3200    | 12       | 7.59%   |
| 2667    | 10       | 6.33%   |
| 2133    | 8        | 5.06%   |
| 667     | 5        | 3.16%   |
| 800     | 4        | 2.53%   |
| 2666    | 3        | 1.9%    |
| 1867    | 3        | 1.9%    |
| 1866    | 3        | 1.9%    |
| 1066    | 3        | 1.9%    |
| Unknown | 3        | 1.9%    |
| 5200    | 1        | 0.63%   |
| 3600    | 1        | 0.63%   |
| 3333    | 1        | 0.63%   |
| 3000    | 1        | 0.63%   |
| 2933    | 1        | 0.63%   |
| 1334    | 1        | 0.63%   |
| 1067    | 1        | 0.63%   |

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


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Microdia        | 1        | 33.33%  |
| Logitech        | 1        | 33.33%  |
| Hewlett-Packard | 1        | 33.33%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| Microdia USB 2.0 Camera     | 1        | 33.33%  |
| Logitech HD Pro Webcam C920 | 1        | 33.33%  |
| HP Premium Starter Webcam   | 1        | 33.33%  |

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
| 1     | 91       | 54.49%  |
| 0     | 64       | 38.32%  |
| 2     | 10       | 5.99%   |
| 4     | 1        | 0.6%    |
| 3     | 1        | 0.6%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 87       | 76.32%  |
| Net/wireless             | 11       | 9.65%   |
| Bluetooth                | 5        | 4.39%   |
| Firewire controller      | 4        | 3.51%   |
| Net/ethernet             | 2        | 1.75%   |
| Graphics card            | 2        | 1.75%   |
| Sound                    | 1        | 0.88%   |
| Network                  | 1        | 0.88%   |
| Card reader              | 1        | 0.88%   |

