BSD in Poland - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for BSD in Poland.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Poland/Desktop/README.md) and [notebooks](/Location/Poland/Notebook/README.md).

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

Total: 510

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| HP            | 8103 A01                    | Mini pc     | [92bebda2d7](https://bsd-hardware.info/?probe=92bebda2d7) | Feb 12, 2024 |
| HP            | 17E2                        | Desktop     | [946d33d274](https://bsd-hardware.info/?probe=946d33d274) | Feb 09, 2024 |
| Dell          | 03NXH8 A00                  | Mini pc     | [7d16a53b54](https://bsd-hardware.info/?probe=7d16a53b54) | Feb 04, 2024 |
| Unknown       | Unknown                     | Desktop     | [0bf7e7f085](https://bsd-hardware.info/?probe=0bf7e7f085) | Feb 03, 2024 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [f6f19ac329](https://bsd-hardware.info/?probe=f6f19ac329) | Feb 02, 2024 |
| Dell          | 0NW6H5 A00                  | Desktop     | [043918562c](https://bsd-hardware.info/?probe=043918562c) | Jan 30, 2024 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [8b93ca6177](https://bsd-hardware.info/?probe=8b93ca6177) | Jan 29, 2024 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [5d0e727014](https://bsd-hardware.info/?probe=5d0e727014) | Jan 29, 2024 |
| HP            | 17E2                        | Desktop     | [f5d50d721e](https://bsd-hardware.info/?probe=f5d50d721e) | Jan 28, 2024 |
| ASRock        | H310M-ITX/ac                | Desktop     | [55ac417044](https://bsd-hardware.info/?probe=55ac417044) | Jan 28, 2024 |
| HP            | 17E2                        | Desktop     | [970b437e61](https://bsd-hardware.info/?probe=970b437e61) | Jan 21, 2024 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [01499997cb](https://bsd-hardware.info/?probe=01499997cb) | Jan 21, 2024 |
| HP            | 213D A01                    | Desktop     | [23ae22cd46](https://bsd-hardware.info/?probe=23ae22cd46) | Jan 19, 2024 |
| Unknown       | Unknown                     | Desktop     | [6afcd4a25f](https://bsd-hardware.info/?probe=6afcd4a25f) | Jan 19, 2024 |
| Unknown       | Unknown                     | Desktop     | [36e0f351c2](https://bsd-hardware.info/?probe=36e0f351c2) | Jan 18, 2024 |
| Dell          | 03NXH8 A00                  | Mini pc     | [8634625b34](https://bsd-hardware.info/?probe=8634625b34) | Jan 16, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [53acaf27b3](https://bsd-hardware.info/?probe=53acaf27b3) | Jan 16, 2024 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [d318950ac5](https://bsd-hardware.info/?probe=d318950ac5) | Jan 15, 2024 |
| Dell          | 0MGK50 A02                  | Desktop     | [311083cbe9](https://bsd-hardware.info/?probe=311083cbe9) | Jan 11, 2024 |
| Dell          | 0MGK50 A02                  | Desktop     | [7c2faad499](https://bsd-hardware.info/?probe=7c2faad499) | Jan 11, 2024 |
| HP            | 18E5                        | Desktop     | [cdea726a3a](https://bsd-hardware.info/?probe=cdea726a3a) | Jan 03, 2024 |
| Intel         | H61M-DS2                    | Desktop     | [bd541b60c8](https://bsd-hardware.info/?probe=bd541b60c8) | Dec 30, 2023 |
| Lenovo        | ThinkPad X220 4291H77       | Notebook    | [2fe3ff7e06](https://bsd-hardware.info/?probe=2fe3ff7e06) | Dec 18, 2023 |
| Unknown       | Unknown                     | Desktop     | [c99ee25103](https://bsd-hardware.info/?probe=c99ee25103) | Dec 17, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [b600237a69](https://bsd-hardware.info/?probe=b600237a69) | Dec 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [92ae7371ee](https://bsd-hardware.info/?probe=92ae7371ee) | Dec 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [6097033e25](https://bsd-hardware.info/?probe=6097033e25) | Dec 05, 2023 |
| Yanling       | YL-EL4L-0A Ver              | Desktop     | [d0c780fa8b](https://bsd-hardware.info/?probe=d0c780fa8b) | Nov 27, 2023 |
| NU591R        | 1.0                         | Desktop     | [2552269778](https://bsd-hardware.info/?probe=2552269778) | Nov 27, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [f2aa7b3ebf](https://bsd-hardware.info/?probe=f2aa7b3ebf) | Nov 25, 2023 |
| Lenovo        | 0x30F617AA SDK0J40705 WI... | Desktop     | [3385be6d7c](https://bsd-hardware.info/?probe=3385be6d7c) | Nov 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [74aaffb0d7](https://bsd-hardware.info/?probe=74aaffb0d7) | Nov 21, 2023 |
| ASUSTek       | P7P55D                      | Desktop     | [9eab94b4f7](https://bsd-hardware.info/?probe=9eab94b4f7) | Nov 18, 2023 |
| Dell          | 03NXH8 A00                  | Mini pc     | [00de0389fb](https://bsd-hardware.info/?probe=00de0389fb) | Nov 18, 2023 |
| HP            | 17E2                        | Mini pc     | [2e93df6830](https://bsd-hardware.info/?probe=2e93df6830) | Nov 17, 2023 |
| Unknown       | Raspberry Pi                | Soc         | [de988c2e66](https://bsd-hardware.info/?probe=de988c2e66) | Nov 14, 2023 |
| ASUSTek       | P7P55D                      | Desktop     | [2487233a5d](https://bsd-hardware.info/?probe=2487233a5d) | Nov 13, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [05bf5fb9f4](https://bsd-hardware.info/?probe=05bf5fb9f4) | Nov 07, 2023 |
| Dell          | 03NXH8 A00                  | Mini pc     | [1d80294e3e](https://bsd-hardware.info/?probe=1d80294e3e) | Nov 06, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [a217880b63](https://bsd-hardware.info/?probe=a217880b63) | Nov 05, 2023 |
| HP            | 213D A01                    | Desktop     | [e7de264f61](https://bsd-hardware.info/?probe=e7de264f61) | Nov 05, 2023 |
| Dell          | 03NXH8 A00                  | Mini pc     | [f6a8d5dbad](https://bsd-hardware.info/?probe=f6a8d5dbad) | Nov 03, 2023 |
| Dell          | 03NXH8 A00                  | Mini pc     | [8473035148](https://bsd-hardware.info/?probe=8473035148) | Nov 03, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [e977a38199](https://bsd-hardware.info/?probe=e977a38199) | Nov 02, 2023 |
| Intel         | JSL MRD                     | Desktop     | [328c764941](https://bsd-hardware.info/?probe=328c764941) | Oct 27, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [1157df98bf](https://bsd-hardware.info/?probe=1157df98bf) | Oct 27, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [1b42e4a912](https://bsd-hardware.info/?probe=1b42e4a912) | Oct 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [8e245ccb85](https://bsd-hardware.info/?probe=8e245ccb85) | Oct 25, 2023 |
| Shuttle       | FZ270                       | Desktop     | [1aa4ad0971](https://bsd-hardware.info/?probe=1aa4ad0971) | Oct 23, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [ab44e043d2](https://bsd-hardware.info/?probe=ab44e043d2) | Oct 23, 2023 |
| HP            | 8103 A01                    | Mini pc     | [d621f08c5a](https://bsd-hardware.info/?probe=d621f08c5a) | Oct 23, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [5a7e4222f1](https://bsd-hardware.info/?probe=5a7e4222f1) | Oct 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [cc1a558efe](https://bsd-hardware.info/?probe=cc1a558efe) | Oct 21, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [a8727c3ee3](https://bsd-hardware.info/?probe=a8727c3ee3) | Oct 19, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [b2a20ba176](https://bsd-hardware.info/?probe=b2a20ba176) | Oct 10, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [b192196423](https://bsd-hardware.info/?probe=b192196423) | Oct 08, 2023 |
| Gigabyte      | P35-DS3R                    | Desktop     | [6f742cd646](https://bsd-hardware.info/?probe=6f742cd646) | Oct 05, 2023 |
| MSI           | MS-98G4                     | Desktop     | [fa88c3c925](https://bsd-hardware.info/?probe=fa88c3c925) | Oct 04, 2023 |
| IGEL Techn... | VX900                       | Desktop     | [eb65624dc3](https://bsd-hardware.info/?probe=eb65624dc3) | Sep 29, 2023 |
| Dell          | 03NXH8 A00                  | Mini pc     | [c560c88351](https://bsd-hardware.info/?probe=c560c88351) | Sep 29, 2023 |
| Dell          | 03NXH8 A00                  | Mini pc     | [cc346350f3](https://bsd-hardware.info/?probe=cc346350f3) | Sep 29, 2023 |
| MSI           | MS-98G4                     | Desktop     | [a8ea23c0df](https://bsd-hardware.info/?probe=a8ea23c0df) | Sep 28, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [b698f41785](https://bsd-hardware.info/?probe=b698f41785) | Sep 28, 2023 |
| Dell          | 05XGC8 A00                  | Desktop     | [a0d9fae143](https://bsd-hardware.info/?probe=a0d9fae143) | Sep 27, 2023 |
| HP            | 3396                        | Desktop     | [a60feb9960](https://bsd-hardware.info/?probe=a60feb9960) | Sep 25, 2023 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [621470728b](https://bsd-hardware.info/?probe=621470728b) | Sep 19, 2023 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [49593de0a0](https://bsd-hardware.info/?probe=49593de0a0) | Sep 16, 2023 |
| Dell          | XPS 9320                    | Notebook    | [d80b3d5a54](https://bsd-hardware.info/?probe=d80b3d5a54) | Sep 14, 2023 |
| Dell          | 0D24M8 A03                  | Desktop     | [48441955a6](https://bsd-hardware.info/?probe=48441955a6) | Sep 14, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [cda96eed7a](https://bsd-hardware.info/?probe=cda96eed7a) | Aug 28, 2023 |
| Gigabyte      | GA-890FXA-UD5               | Desktop     | [85b0bba1ea](https://bsd-hardware.info/?probe=85b0bba1ea) | Aug 27, 2023 |
| Gigabyte      | H510M K                     | Desktop     | [17f15f19f4](https://bsd-hardware.info/?probe=17f15f19f4) | Aug 26, 2023 |
| Lenovo        | ThinkPad X200 7458WNZ       | Notebook    | [3ac1d60240](https://bsd-hardware.info/?probe=3ac1d60240) | Aug 12, 2023 |
| HP            | 18E5                        | Desktop     | [61bde93177](https://bsd-hardware.info/?probe=61bde93177) | Aug 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [7751768206](https://bsd-hardware.info/?probe=7751768206) | Aug 10, 2023 |
| AMI           | PB_1900A                    | Desktop     | [791f6e0cb4](https://bsd-hardware.info/?probe=791f6e0cb4) | Aug 07, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [6496fe0cfe](https://bsd-hardware.info/?probe=6496fe0cfe) | Aug 03, 2023 |
| ASUSTek       | PRIME A320I-K               | Desktop     | [09f173d4b6](https://bsd-hardware.info/?probe=09f173d4b6) | Jul 30, 2023 |
| ASUSTek       | X555LD                      | Notebook    | [9c0c41b663](https://bsd-hardware.info/?probe=9c0c41b663) | Jul 30, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [e11855c762](https://bsd-hardware.info/?probe=e11855c762) | Jul 24, 2023 |
| Dell          | 05XGC8 A00                  | Desktop     | [3a774e653a](https://bsd-hardware.info/?probe=3a774e653a) | Jul 19, 2023 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | Notebook    | [386a80104d](https://bsd-hardware.info/?probe=386a80104d) | Jul 19, 2023 |
| Dell          | 05XGC8 A00                  | Desktop     | [604ac1ea85](https://bsd-hardware.info/?probe=604ac1ea85) | Jul 19, 2023 |
| Supermicro    | A2SDV-4C-LN10PF             | Desktop     | [8be657ad15](https://bsd-hardware.info/?probe=8be657ad15) | Jul 17, 2023 |
| HP            | 213D A01                    | Desktop     | [ae7b01c282](https://bsd-hardware.info/?probe=ae7b01c282) | Jul 16, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [1de68296ba](https://bsd-hardware.info/?probe=1de68296ba) | Jul 15, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [5f5c78ed40](https://bsd-hardware.info/?probe=5f5c78ed40) | Jul 15, 2023 |
| HP            | ProLiant DL360 G7           | Server      | [c55c8784e1](https://bsd-hardware.info/?probe=c55c8784e1) | Jul 13, 2023 |
| HP            | ProLiant DL360 G7           | Server      | [df74f4520e](https://bsd-hardware.info/?probe=df74f4520e) | Jul 08, 2023 |
| Dell          | 05XGC8 A00                  | Desktop     | [16fc35ccac](https://bsd-hardware.info/?probe=16fc35ccac) | Jul 06, 2023 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [e569621be2](https://bsd-hardware.info/?probe=e569621be2) | Jul 03, 2023 |
| Gigabyte      | H270N-WIFI-CF               | Desktop     | [553cd9ecae](https://bsd-hardware.info/?probe=553cd9ecae) | Jul 03, 2023 |
| ASRock        | J3455B-ITX                  | Desktop     | [3c80c960d3](https://bsd-hardware.info/?probe=3c80c960d3) | Jul 03, 2023 |
| ASRock        | J3455B-ITX                  | Desktop     | [051ddf6f8d](https://bsd-hardware.info/?probe=051ddf6f8d) | Jul 03, 2023 |
| Gigabyte      | H270N-WIFI-CF               | Desktop     | [dfdb0bd650](https://bsd-hardware.info/?probe=dfdb0bd650) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [e68bb73773](https://bsd-hardware.info/?probe=e68bb73773) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [3b4a248520](https://bsd-hardware.info/?probe=3b4a248520) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [0a2a221aae](https://bsd-hardware.info/?probe=0a2a221aae) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [7e5ee8de12](https://bsd-hardware.info/?probe=7e5ee8de12) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [3b50a90ebc](https://bsd-hardware.info/?probe=3b50a90ebc) | Jul 03, 2023 |
| Unknown       | Unknown                     | Notebook    | [13c087ef5e](https://bsd-hardware.info/?probe=13c087ef5e) | Jul 03, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [1aff07438c](https://bsd-hardware.info/?probe=1aff07438c) | Jun 28, 2023 |
| Dell          | Latitude E4310              | Notebook    | [9cdd4909fe](https://bsd-hardware.info/?probe=9cdd4909fe) | Jun 24, 2023 |
| HP            | 213D A01                    | Desktop     | [eccc48bb80](https://bsd-hardware.info/?probe=eccc48bb80) | Jun 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [6b4f214b72](https://bsd-hardware.info/?probe=6b4f214b72) | Jun 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [615e7cbf52](https://bsd-hardware.info/?probe=615e7cbf52) | Jun 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [8357f0f72e](https://bsd-hardware.info/?probe=8357f0f72e) | Jun 15, 2023 |
| Intel         | D2500CC AAG81477-401        | Desktop     | [15329a007b](https://bsd-hardware.info/?probe=15329a007b) | Jun 14, 2023 |
| Samsung       | R530/R730/R540              | Notebook    | [b007264caa](https://bsd-hardware.info/?probe=b007264caa) | Jun 11, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [3679eb8cd4](https://bsd-hardware.info/?probe=3679eb8cd4) | Jun 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [9afa1aea18](https://bsd-hardware.info/?probe=9afa1aea18) | Jun 10, 2023 |
| Dell          | 05XGC8 A00                  | Desktop     | [f79924e37b](https://bsd-hardware.info/?probe=f79924e37b) | Jun 08, 2023 |
| Lenovo        | ThinkPad T480 20L6S5VP4C    | Notebook    | [b891388109](https://bsd-hardware.info/?probe=b891388109) | Jun 07, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [95ceb1335c](https://bsd-hardware.info/?probe=95ceb1335c) | Jun 04, 2023 |
| Dell          | 0TKM9Y A00                  | Mini pc     | [fdd78a8f45](https://bsd-hardware.info/?probe=fdd78a8f45) | Jun 03, 2023 |
| Dell          | 05XGC8 A00                  | Desktop     | [98ebd3efdb](https://bsd-hardware.info/?probe=98ebd3efdb) | Jun 02, 2023 |
| Deciso        | NetBoard-A20                | Notebook    | [48a63a2328](https://bsd-hardware.info/?probe=48a63a2328) | Jun 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [e057606b14](https://bsd-hardware.info/?probe=e057606b14) | May 29, 2023 |
| NU591R        | 1.0                         | Desktop     | [e4bdd753d1](https://bsd-hardware.info/?probe=e4bdd753d1) | May 28, 2023 |
| Dell          | 05XGC8 A00                  | Desktop     | [b121b2cba9](https://bsd-hardware.info/?probe=b121b2cba9) | May 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [1070ff80a8](https://bsd-hardware.info/?probe=1070ff80a8) | May 26, 2023 |
| Intel         | S1200RP                     | Server      | [f3143ec0e1](https://bsd-hardware.info/?probe=f3143ec0e1) | May 25, 2023 |
| Unknown       | Unknown                     | Notebook    | [3b4be5b07a](https://bsd-hardware.info/?probe=3b4be5b07a) | May 24, 2023 |
| Intel         | S1200RP                     | Server      | [59ee73a435](https://bsd-hardware.info/?probe=59ee73a435) | May 23, 2023 |
| Google        | Sentry                      | Notebook    | [107124dd66](https://bsd-hardware.info/?probe=107124dd66) | May 22, 2023 |
| PC Engines    | apu6                        | Desktop     | [cfebc05e50](https://bsd-hardware.info/?probe=cfebc05e50) | May 21, 2023 |
| PC Engines    | apu6                        | Desktop     | [320d6a85a3](https://bsd-hardware.info/?probe=320d6a85a3) | May 21, 2023 |
| Unknown       | Unknown                     | Notebook    | [2a2b4272f9](https://bsd-hardware.info/?probe=2a2b4272f9) | May 20, 2023 |
| HP            | 213D A01                    | Desktop     | [8e1d1d5670](https://bsd-hardware.info/?probe=8e1d1d5670) | May 20, 2023 |
| Packard Be... | EasyNote LJ65               | Notebook    | [36d3e7aaf7](https://bsd-hardware.info/?probe=36d3e7aaf7) | May 19, 2023 |
| PC Engines    | apu4                        | Desktop     | [1d4c0fad6a](https://bsd-hardware.info/?probe=1d4c0fad6a) | May 16, 2023 |
| PC Engines    | apu4                        | Desktop     | [94bdc05090](https://bsd-hardware.info/?probe=94bdc05090) | May 16, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [526906c806](https://bsd-hardware.info/?probe=526906c806) | May 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [8aede62ca8](https://bsd-hardware.info/?probe=8aede62ca8) | May 14, 2023 |
| Supermicro    | X8SIL                       | Desktop     | [bb30062fc1](https://bsd-hardware.info/?probe=bb30062fc1) | May 14, 2023 |
| Dell          | 05XGC8 A00                  | Desktop     | [dd2b0657d0](https://bsd-hardware.info/?probe=dd2b0657d0) | May 13, 2023 |
| Dell          | 05XGC8 A00                  | Desktop     | [131214e3a7](https://bsd-hardware.info/?probe=131214e3a7) | May 12, 2023 |
| HP            | 213D A01                    | Desktop     | [92c8d4c54e](https://bsd-hardware.info/?probe=92c8d4c54e) | May 12, 2023 |
| Lenovo        | ThinkPad T500 205663G       | Notebook    | [d706da9400](https://bsd-hardware.info/?probe=d706da9400) | May 06, 2023 |
| ASRock        | J4125-ITX                   | Desktop     | [6e34c8b22a](https://bsd-hardware.info/?probe=6e34c8b22a) | May 05, 2023 |
| Gigabyte      | H510M K                     | Desktop     | [e4a5065086](https://bsd-hardware.info/?probe=e4a5065086) | May 03, 2023 |
| HP            | 213D A01                    | Desktop     | [6810604547](https://bsd-hardware.info/?probe=6810604547) | May 03, 2023 |
| HP            | ProLiant DL320e Gen8        | Server      | [03255b960a](https://bsd-hardware.info/?probe=03255b960a) | Apr 30, 2023 |
| HP            | ProLiant DL320e Gen8        | Server      | [b1c41e5e29](https://bsd-hardware.info/?probe=b1c41e5e29) | Apr 29, 2023 |
| Gigabyte      | H510M K                     | Desktop     | [a952664d92](https://bsd-hardware.info/?probe=a952664d92) | Apr 29, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [ce8453fcce](https://bsd-hardware.info/?probe=ce8453fcce) | Apr 27, 2023 |
| HP            | 18E5                        | Desktop     | [9f82560327](https://bsd-hardware.info/?probe=9f82560327) | Apr 26, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [838979f891](https://bsd-hardware.info/?probe=838979f891) | Apr 20, 2023 |
| Medion        | E15302                      | Notebook    | [f47f32e1cc](https://bsd-hardware.info/?probe=f47f32e1cc) | Apr 17, 2023 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [a7830f5244](https://bsd-hardware.info/?probe=a7830f5244) | Apr 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [fb756bb34e](https://bsd-hardware.info/?probe=fb756bb34e) | Apr 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [add8280600](https://bsd-hardware.info/?probe=add8280600) | Apr 11, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [e1e041b34a](https://bsd-hardware.info/?probe=e1e041b34a) | Apr 07, 2023 |
| Fujitsu       | CELSIUS H920                | Notebook    | [0551eecbcc](https://bsd-hardware.info/?probe=0551eecbcc) | Apr 06, 2023 |
| Dell          | 012KND A00                  | Mini pc     | [55d92330be](https://bsd-hardware.info/?probe=55d92330be) | Apr 04, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [ac38e117ac](https://bsd-hardware.info/?probe=ac38e117ac) | Apr 04, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [032a4be314](https://bsd-hardware.info/?probe=032a4be314) | Apr 03, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [f4d583f326](https://bsd-hardware.info/?probe=f4d583f326) | Apr 01, 2023 |
| Fujitsu       | CELSIUS H920                | Notebook    | [e6300dc691](https://bsd-hardware.info/?probe=e6300dc691) | Mar 31, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [837fdf1a2c](https://bsd-hardware.info/?probe=837fdf1a2c) | Mar 31, 2023 |
| Lenovo        | ThinkPad T540p 20BFS10W0... | Notebook    | [30c5fc2625](https://bsd-hardware.info/?probe=30c5fc2625) | Mar 29, 2023 |
| Dell          | 0T1D10 A01                  | Desktop     | [2f5592023f](https://bsd-hardware.info/?probe=2f5592023f) | Mar 29, 2023 |
| Dell          | 0T1D10 A01                  | Desktop     | [6316b108be](https://bsd-hardware.info/?probe=6316b108be) | Mar 29, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [a8f794f3fb](https://bsd-hardware.info/?probe=a8f794f3fb) | Mar 24, 2023 |
| HP            | 18E5                        | Desktop     | [1f402a50e7](https://bsd-hardware.info/?probe=1f402a50e7) | Mar 22, 2023 |
| ASUSTek       | X71Vn                       | Notebook    | [6e96ea55ee](https://bsd-hardware.info/?probe=6e96ea55ee) | Mar 22, 2023 |
| Intel         | X99                         | Desktop     | [a74c2b96ff](https://bsd-hardware.info/?probe=a74c2b96ff) | Mar 21, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [8d0e6be5da](https://bsd-hardware.info/?probe=8d0e6be5da) | Mar 20, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [acc1970543](https://bsd-hardware.info/?probe=acc1970543) | Mar 18, 2023 |
| Lenovo        | ThinkPad A275 20KCS07010    | Notebook    | [4d6daf66c1](https://bsd-hardware.info/?probe=4d6daf66c1) | Mar 18, 2023 |
| HP            | EliteBook 850 G2            | Notebook    | [653dbe54a4](https://bsd-hardware.info/?probe=653dbe54a4) | Mar 18, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [b8404f57ba](https://bsd-hardware.info/?probe=b8404f57ba) | Mar 15, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [2d5e8056c0](https://bsd-hardware.info/?probe=2d5e8056c0) | Mar 15, 2023 |
| Dell          | Latitude D630               | Notebook    | [da1fa73418](https://bsd-hardware.info/?probe=da1fa73418) | Mar 14, 2023 |
| Lenovo        | ThinkPad X200 74591P0       | Notebook    | [882cc7fc62](https://bsd-hardware.info/?probe=882cc7fc62) | Mar 13, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [593f6ff02d](https://bsd-hardware.info/?probe=593f6ff02d) | Mar 12, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [e8204efca6](https://bsd-hardware.info/?probe=e8204efca6) | Mar 12, 2023 |
| Dell          | Latitude E5450              | Notebook    | [4bb2040221](https://bsd-hardware.info/?probe=4bb2040221) | Mar 11, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [29ad0e1044](https://bsd-hardware.info/?probe=29ad0e1044) | Mar 11, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [12990e3b0f](https://bsd-hardware.info/?probe=12990e3b0f) | Mar 09, 2023 |
| HP            | 8103 A01                    | Mini pc     | [acb993fd8a](https://bsd-hardware.info/?probe=acb993fd8a) | Mar 06, 2023 |
| AMI           | PB_1900A                    | Desktop     | [79504fcf66](https://bsd-hardware.info/?probe=79504fcf66) | Mar 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [78d56cd69d](https://bsd-hardware.info/?probe=78d56cd69d) | Mar 01, 2023 |
| Intel         | S1200RP                     | Server      | [176c42716f](https://bsd-hardware.info/?probe=176c42716f) | Mar 01, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [1758c6207c](https://bsd-hardware.info/?probe=1758c6207c) | Feb 27, 2023 |
| Lenovo        | ThinkPad T530 24297XG       | Notebook    | [97d9b10c8a](https://bsd-hardware.info/?probe=97d9b10c8a) | Feb 24, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [e55635df08](https://bsd-hardware.info/?probe=e55635df08) | Feb 23, 2023 |
| PC Engines    | apu1                        | Desktop     | [41fe7362c4](https://bsd-hardware.info/?probe=41fe7362c4) | Feb 22, 2023 |
| Unknown       | V0.9x                       | Desktop     | [21243cad5f](https://bsd-hardware.info/?probe=21243cad5f) | Feb 21, 2023 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [9aec93f312](https://bsd-hardware.info/?probe=9aec93f312) | Feb 19, 2023 |
| MSI           | Z97 GUARD-PRO               | Desktop     | [43d56964b9](https://bsd-hardware.info/?probe=43d56964b9) | Feb 12, 2023 |
| Supermicro    | X8STi                       | Desktop     | [4faeca02d3](https://bsd-hardware.info/?probe=4faeca02d3) | Feb 11, 2023 |
| MSI           | Z97 GUARD-PRO               | Desktop     | [9f066752d5](https://bsd-hardware.info/?probe=9f066752d5) | Feb 11, 2023 |
| HP            | 3396                        | Desktop     | [6a20d52898](https://bsd-hardware.info/?probe=6a20d52898) | Feb 08, 2023 |
| MSI           | Z97 GAMING 3                | Desktop     | [bbe7b327fd](https://bsd-hardware.info/?probe=bbe7b327fd) | Feb 06, 2023 |
| HP            | Notebook                    | Notebook    | [8d8e5c294a](https://bsd-hardware.info/?probe=8d8e5c294a) | Feb 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [cb25ee692c](https://bsd-hardware.info/?probe=cb25ee692c) | Feb 05, 2023 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [ea5b1c178b](https://bsd-hardware.info/?probe=ea5b1c178b) | Feb 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [e76cc93e5d](https://bsd-hardware.info/?probe=e76cc93e5d) | Jan 31, 2023 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | Notebook    | [bccdd2f331](https://bsd-hardware.info/?probe=bccdd2f331) | Jan 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [540696f4e5](https://bsd-hardware.info/?probe=540696f4e5) | Jan 29, 2023 |
| Acidanther... | Mac-AA95B1DDAB278B95 iMa... | All in one  | [3492d9a849](https://bsd-hardware.info/?probe=3492d9a849) | Jan 27, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [92c676e033](https://bsd-hardware.info/?probe=92c676e033) | Jan 26, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [7bd5f0c2e9](https://bsd-hardware.info/?probe=7bd5f0c2e9) | Jan 22, 2023 |
| Dell          | 0K6VXP A00                  | Mini pc     | [6b331ff558](https://bsd-hardware.info/?probe=6b331ff558) | Jan 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [6aa648ba82](https://bsd-hardware.info/?probe=6aa648ba82) | Jan 19, 2023 |
| Intel         | H81U                        | Notebook    | [08d2539153](https://bsd-hardware.info/?probe=08d2539153) | Jan 18, 2023 |
| Intel         | H81U                        | Notebook    | [fe47328dd0](https://bsd-hardware.info/?probe=fe47328dd0) | Jan 17, 2023 |
| HP            | 1495                        | Desktop     | [4e16deda5a](https://bsd-hardware.info/?probe=4e16deda5a) | Jan 11, 2023 |
| Gigabyte      | H510M K                     | Desktop     | [c30a71f5ae](https://bsd-hardware.info/?probe=c30a71f5ae) | Jan 10, 2023 |
| Dell          | Latitude E6430              | Notebook    | [45f592a66f](https://bsd-hardware.info/?probe=45f592a66f) | Jan 06, 2023 |
| Dell          | Latitude E6430              | Notebook    | [1c4bec17bb](https://bsd-hardware.info/?probe=1c4bec17bb) | Jan 06, 2023 |
| Biostar       | J4125NHU                    | Desktop     | [41114c45b7](https://bsd-hardware.info/?probe=41114c45b7) | Jan 05, 2023 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [4bcc34fdca](https://bsd-hardware.info/?probe=4bcc34fdca) | Dec 27, 2022 |
| Intel         | D2500HN AAG81480-500        | Desktop     | [dae5627541](https://bsd-hardware.info/?probe=dae5627541) | Dec 27, 2022 |
| Dell          | 060J9C A00                  | Mini pc     | [29b3e0b639](https://bsd-hardware.info/?probe=29b3e0b639) | Dec 22, 2022 |
| Acer          | WG43M                       | Desktop     | [d316352c20](https://bsd-hardware.info/?probe=d316352c20) | Dec 22, 2022 |
| Unknown       | Unknown                     | Desktop     | [0e98358cf3](https://bsd-hardware.info/?probe=0e98358cf3) | Dec 17, 2022 |
| Google        | Lars                        | Notebook    | [4130b19cfa](https://bsd-hardware.info/?probe=4130b19cfa) | Dec 03, 2022 |
| ASRock        | X570 Pro4                   | Desktop     | [b23f59a068](https://bsd-hardware.info/?probe=b23f59a068) | Nov 27, 2022 |
| ASRock        | Q1900B-ITX                  | Desktop     | [c93690c7ca](https://bsd-hardware.info/?probe=c93690c7ca) | Nov 27, 2022 |
| Shuttle       | FZ270                       | Desktop     | [04a7f49322](https://bsd-hardware.info/?probe=04a7f49322) | Nov 27, 2022 |
| Shuttle       | FZ270                       | Desktop     | [10016f39b9](https://bsd-hardware.info/?probe=10016f39b9) | Nov 27, 2022 |
| ASRock        | Q1900B-ITX                  | Desktop     | [675c9fdf94](https://bsd-hardware.info/?probe=675c9fdf94) | Nov 27, 2022 |
| ASRock        | Q1900B-ITX                  | Desktop     | [a337eb9e5f](https://bsd-hardware.info/?probe=a337eb9e5f) | Nov 27, 2022 |
| Shuttle       | FH270                       | Desktop     | [192351ac6f](https://bsd-hardware.info/?probe=192351ac6f) | Nov 27, 2022 |
| Shuttle       | FH270                       | Desktop     | [3b68d89092](https://bsd-hardware.info/?probe=3b68d89092) | Nov 27, 2022 |
| Dell          | 0VRCY5 A14                  | Server      | [5048d00fd8](https://bsd-hardware.info/?probe=5048d00fd8) | Nov 27, 2022 |
| Dell          | 0VRCY5 A14                  | Server      | [60bdb57227](https://bsd-hardware.info/?probe=60bdb57227) | Nov 27, 2022 |
| Dell          | 0VRCY5 A14                  | Server      | [ebdca950cc](https://bsd-hardware.info/?probe=ebdca950cc) | Nov 27, 2022 |
| HP            | 3396                        | Desktop     | [dc94cbde1a](https://bsd-hardware.info/?probe=dc94cbde1a) | Nov 23, 2022 |
| Gigabyte      | H110TN                      | Desktop     | [c121bad3fb](https://bsd-hardware.info/?probe=c121bad3fb) | Nov 17, 2022 |
| Intel         | D2500CC AAG81477-401        | Desktop     | [f27ff1a7c3](https://bsd-hardware.info/?probe=f27ff1a7c3) | Oct 22, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [348bef7dba](https://bsd-hardware.info/?probe=348bef7dba) | Oct 20, 2022 |
| Lenovo        | 3188 SDK0J40697 WIN 3305... | Desktop     | [f84b205626](https://bsd-hardware.info/?probe=f84b205626) | Oct 18, 2022 |
| HP            | SpectreXT Pro 13-b000 PC    | Notebook    | [f45ea42873](https://bsd-hardware.info/?probe=f45ea42873) | Oct 16, 2022 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [e08c408ced](https://bsd-hardware.info/?probe=e08c408ced) | Oct 14, 2022 |
| ASRockRack    | EP2C612D16FM                | Desktop     | [30a582fccb](https://bsd-hardware.info/?probe=30a582fccb) | Oct 07, 2022 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [f521533d51](https://bsd-hardware.info/?probe=f521533d51) | Oct 06, 2022 |
| Gigabyte      | H510M K                     | Desktop     | [27f932ee37](https://bsd-hardware.info/?probe=27f932ee37) | Oct 02, 2022 |
| Gigabyte      | H510M K                     | Desktop     | [4beab225f6](https://bsd-hardware.info/?probe=4beab225f6) | Sep 28, 2022 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [fe44242c3b](https://bsd-hardware.info/?probe=fe44242c3b) | Sep 25, 2022 |
| Gigabyte      | H81M-S1                     | Desktop     | [fe9eecb935](https://bsd-hardware.info/?probe=fe9eecb935) | Sep 18, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [da4bd87fee](https://bsd-hardware.info/?probe=da4bd87fee) | Sep 17, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [7aa564bfb2](https://bsd-hardware.info/?probe=7aa564bfb2) | Sep 14, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [0ee299e989](https://bsd-hardware.info/?probe=0ee299e989) | Sep 14, 2022 |
| Dell          | 0HJK12 A03                  | Server      | [96ad323ca0](https://bsd-hardware.info/?probe=96ad323ca0) | Sep 13, 2022 |
| Dell          | 0H5J4J A01                  | Server      | [acb91f797f](https://bsd-hardware.info/?probe=acb91f797f) | Sep 13, 2022 |
| HP            | 213D A01                    | Desktop     | [6354ddb4a8](https://bsd-hardware.info/?probe=6354ddb4a8) | Sep 12, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [b2dc861f47](https://bsd-hardware.info/?probe=b2dc861f47) | Sep 10, 2022 |
| Deciso        | NetBoard-A10                | Notebook    | [3547d9da9c](https://bsd-hardware.info/?probe=3547d9da9c) | Sep 01, 2022 |
| HP            | 213D A01                    | Desktop     | [c495fb5448](https://bsd-hardware.info/?probe=c495fb5448) | Aug 30, 2022 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [d721e505cb](https://bsd-hardware.info/?probe=d721e505cb) | Aug 27, 2022 |
| HP            | 213D A01                    | Desktop     | [1b90f312ea](https://bsd-hardware.info/?probe=1b90f312ea) | Aug 26, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [eec9546431](https://bsd-hardware.info/?probe=eec9546431) | Aug 23, 2022 |
| Inventec      | Z CLASS A02                 | Desktop     | [cb3708c9bf](https://bsd-hardware.info/?probe=cb3708c9bf) | Aug 21, 2022 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | Notebook    | [2e7d570822](https://bsd-hardware.info/?probe=2e7d570822) | Aug 20, 2022 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | Notebook    | [7afa139f4f](https://bsd-hardware.info/?probe=7afa139f4f) | Aug 20, 2022 |
| Gigabyte      | IMB4100TN                   | Desktop     | [aa4bae0d12](https://bsd-hardware.info/?probe=aa4bae0d12) | Aug 15, 2022 |
| ASRock        | Z370 Pro4                   | Desktop     | [038c5f8763](https://bsd-hardware.info/?probe=038c5f8763) | Aug 10, 2022 |
| Dell          | 084J0R A00                  | Desktop     | [932058e97a](https://bsd-hardware.info/?probe=932058e97a) | Aug 09, 2022 |
| iEi           | B449 V1.00                  | Desktop     | [7776910eea](https://bsd-hardware.info/?probe=7776910eea) | Aug 05, 2022 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [c38ad87323](https://bsd-hardware.info/?probe=c38ad87323) | Aug 04, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [6093566ed2](https://bsd-hardware.info/?probe=6093566ed2) | Aug 04, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [706d8fc244](https://bsd-hardware.info/?probe=706d8fc244) | Aug 04, 2022 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [2967d5275e](https://bsd-hardware.info/?probe=2967d5275e) | Jul 29, 2022 |
| HP            | 3397                        | Desktop     | [68eb683936](https://bsd-hardware.info/?probe=68eb683936) | Jul 27, 2022 |
| ASUSTek       | P8B WS                      | Desktop     | [dd7f8123d2](https://bsd-hardware.info/?probe=dd7f8123d2) | Jul 19, 2022 |
| Lenovo        | ThinkPad T495 20NJ0010PB    | Notebook    | [078888676a](https://bsd-hardware.info/?probe=078888676a) | Jul 13, 2022 |
| HP            | 213D A01                    | Desktop     | [0f58ab215e](https://bsd-hardware.info/?probe=0f58ab215e) | Jul 03, 2022 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [a094c1c53b](https://bsd-hardware.info/?probe=a094c1c53b) | Jun 20, 2022 |
| Unknown       | Unknown                     | Desktop     | [fe9f636040](https://bsd-hardware.info/?probe=fe9f636040) | Jun 13, 2022 |
| Dell          | 0TY019 A01                  | Server      | [1aeb1bf3bf](https://bsd-hardware.info/?probe=1aeb1bf3bf) | Jun 09, 2022 |
| Dell          | Latitude 5410               | Notebook    | [3334ff3727](https://bsd-hardware.info/?probe=3334ff3727) | Jun 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [6acbc93101](https://bsd-hardware.info/?probe=6acbc93101) | May 30, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [3f39f21672](https://bsd-hardware.info/?probe=3f39f21672) | May 29, 2022 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [6a6fda6d6d](https://bsd-hardware.info/?probe=6a6fda6d6d) | May 26, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [ce4d7c01e5](https://bsd-hardware.info/?probe=ce4d7c01e5) | May 24, 2022 |
| HP            | 213D A01                    | Desktop     | [562722ac56](https://bsd-hardware.info/?probe=562722ac56) | Apr 30, 2022 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | Desktop     | [0d46ae5678](https://bsd-hardware.info/?probe=0d46ae5678) | Apr 25, 2022 |
| Apple         | PowerMac10,1                | Desktop     | [e054e605fa](https://bsd-hardware.info/?probe=e054e605fa) | Apr 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [3c5fcc2377](https://bsd-hardware.info/?probe=3c5fcc2377) | Apr 22, 2022 |
| HP            | 213D A01                    | Desktop     | [4dea775e1b](https://bsd-hardware.info/?probe=4dea775e1b) | Apr 12, 2022 |
| Intel         | NUC6CAYB J26842-405         | Mini pc     | [534af14a9f](https://bsd-hardware.info/?probe=534af14a9f) | Apr 11, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [da64cbb0d1](https://bsd-hardware.info/?probe=da64cbb0d1) | Apr 07, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [9a260e4d21](https://bsd-hardware.info/?probe=9a260e4d21) | Apr 05, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | Desktop     | [964ceb3616](https://bsd-hardware.info/?probe=964ceb3616) | Apr 03, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | Desktop     | [5038186437](https://bsd-hardware.info/?probe=5038186437) | Apr 02, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [e0c61311da](https://bsd-hardware.info/?probe=e0c61311da) | Apr 01, 2022 |
| ASUSTek       | P6-P8H61E                   | Desktop     | [11664cd9d7](https://bsd-hardware.info/?probe=11664cd9d7) | Mar 30, 2022 |
| ASUSTek       | P6-P8H61E                   | Desktop     | [540f66f678](https://bsd-hardware.info/?probe=540f66f678) | Mar 29, 2022 |
| Dell          | 0GXM1W A00                  | Desktop     | [717721a634](https://bsd-hardware.info/?probe=717721a634) | Mar 29, 2022 |
| Dell          | 0DNFFW A00                  | All in one  | [30432daccb](https://bsd-hardware.info/?probe=30432daccb) | Mar 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [38c71bac61](https://bsd-hardware.info/?probe=38c71bac61) | Mar 22, 2022 |
| Acer          | Aptio CRB                   | Mini pc     | [f38b7df811](https://bsd-hardware.info/?probe=f38b7df811) | Mar 20, 2022 |
| Lenovo        | ThinkPad X200 745969G       | Notebook    | [e973d1e806](https://bsd-hardware.info/?probe=e973d1e806) | Mar 18, 2022 |
| Unknown       | Unknown                     | Desktop     | [a54ee6f019](https://bsd-hardware.info/?probe=a54ee6f019) | Mar 18, 2022 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | Desktop     | [55515325c4](https://bsd-hardware.info/?probe=55515325c4) | Mar 15, 2022 |
| Dell          | 0GXM1W A00                  | Desktop     | [a488c9af25](https://bsd-hardware.info/?probe=a488c9af25) | Mar 14, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [9e440b5500](https://bsd-hardware.info/?probe=9e440b5500) | Mar 13, 2022 |
| ASRock        | Q1900B-ITX                  | Desktop     | [b4142103cb](https://bsd-hardware.info/?probe=b4142103cb) | Mar 10, 2022 |
| Dell          | 075CGM A00                  | Mini pc     | [ac38d3156d](https://bsd-hardware.info/?probe=ac38d3156d) | Mar 10, 2022 |
| Inventec      | 0VKXH3 A01                  | Mini pc     | [d018e86ea8](https://bsd-hardware.info/?probe=d018e86ea8) | Mar 10, 2022 |
| Unknown       | LeMaker Banana Pi           | Desktop     | [37e7d1912b](https://bsd-hardware.info/?probe=37e7d1912b) | Mar 05, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [4bc5573cf5](https://bsd-hardware.info/?probe=4bc5573cf5) | Mar 02, 2022 |
| Dell          | 0DNFFW A00                  | All in one  | [2db3ec9574](https://bsd-hardware.info/?probe=2db3ec9574) | Feb 27, 2022 |
| Intel         | D945GSEJT                   | Desktop     | [bf6a38dfcb](https://bsd-hardware.info/?probe=bf6a38dfcb) | Feb 26, 2022 |
| HP            | 213D A01                    | Desktop     | [b9560ec339](https://bsd-hardware.info/?probe=b9560ec339) | Feb 24, 2022 |
| Dell          | Latitude E6430              | Notebook    | [fdde41404d](https://bsd-hardware.info/?probe=fdde41404d) | Feb 24, 2022 |
| Lenovo        | ThinkPad X200 745969G       | Notebook    | [a4341268d0](https://bsd-hardware.info/?probe=a4341268d0) | Feb 23, 2022 |
| ASRock        | ConRoe1333-D667             | Desktop     | [624b4f4de7](https://bsd-hardware.info/?probe=624b4f4de7) | Feb 23, 2022 |
| Shuttle       | FZ270                       | Desktop     | [7e0eb61342](https://bsd-hardware.info/?probe=7e0eb61342) | Feb 22, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [feb7882341](https://bsd-hardware.info/?probe=feb7882341) | Feb 22, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [11bed21472](https://bsd-hardware.info/?probe=11bed21472) | Feb 21, 2022 |
| MSI           | MS-AEC11                    | All in one  | [7863616b75](https://bsd-hardware.info/?probe=7863616b75) | Feb 20, 2022 |
| Unknown       | Raspberry Pi 4 Model B R... | Desktop     | [04e528ca9f](https://bsd-hardware.info/?probe=04e528ca9f) | Feb 19, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [64999a24c1](https://bsd-hardware.info/?probe=64999a24c1) | Feb 16, 2022 |
| Raspberry ... | Raspberry Pi 400            | Desktop     | [dd56609ceb](https://bsd-hardware.info/?probe=dd56609ceb) | Feb 14, 2022 |
| Lenovo        | ThinkPad X200 745969G       | Notebook    | [c024d383e7](https://bsd-hardware.info/?probe=c024d383e7) | Feb 13, 2022 |
| HP            | 213D A01                    | Desktop     | [0171663489](https://bsd-hardware.info/?probe=0171663489) | Feb 12, 2022 |
| Unknown       | LeMaker Banana Pi           | Desktop     | [77413a3d9d](https://bsd-hardware.info/?probe=77413a3d9d) | Feb 12, 2022 |
| MSI           | B75A-G43                    | Desktop     | [8e445eb2d4](https://bsd-hardware.info/?probe=8e445eb2d4) | Feb 08, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [478714c7c9](https://bsd-hardware.info/?probe=478714c7c9) | Feb 07, 2022 |
| MSI           | H61M-P20                    | Desktop     | [98ec852f90](https://bsd-hardware.info/?probe=98ec852f90) | Feb 06, 2022 |
| Lenovo        | ThinkPad X200 745969G       | Notebook    | [f107f7c1b1](https://bsd-hardware.info/?probe=f107f7c1b1) | Feb 06, 2022 |
| ASUSTek       | P6-P8H61E                   | Desktop     | [e838981914](https://bsd-hardware.info/?probe=e838981914) | Feb 06, 2022 |
| Dell          | 075CGM A00                  | Mini pc     | [5a9e6ea87f](https://bsd-hardware.info/?probe=5a9e6ea87f) | Feb 05, 2022 |
| Lenovo        | G500s 20245                 | Notebook    | [41f9f804ac](https://bsd-hardware.info/?probe=41f9f804ac) | Feb 04, 2022 |
| Dell          | 04YP6J A02                  | Desktop     | [550e7feb7f](https://bsd-hardware.info/?probe=550e7feb7f) | Feb 03, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [0b290f2ac3](https://bsd-hardware.info/?probe=0b290f2ac3) | Feb 02, 2022 |
| Lenovo        | ThinkPad X200 745969G       | Notebook    | [f8476c0ea7](https://bsd-hardware.info/?probe=f8476c0ea7) | Feb 01, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [97ef0862c2](https://bsd-hardware.info/?probe=97ef0862c2) | Feb 01, 2022 |
| Dell          | 0K6VXP A00                  | Mini pc     | [cbb110122a](https://bsd-hardware.info/?probe=cbb110122a) | Jan 29, 2022 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [2acf9ac926](https://bsd-hardware.info/?probe=2acf9ac926) | Jan 29, 2022 |
| Intel         | D2500HN AAG81480-500        | Desktop     | [3a39fe5ec2](https://bsd-hardware.info/?probe=3a39fe5ec2) | Jan 29, 2022 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [268906bcbe](https://bsd-hardware.info/?probe=268906bcbe) | Jan 29, 2022 |
| Dell          | 014GRG A03                  | Desktop     | [8e0a22c065](https://bsd-hardware.info/?probe=8e0a22c065) | Jan 28, 2022 |
| Dell          | 014GRG A03                  | Desktop     | [5996ba19b1](https://bsd-hardware.info/?probe=5996ba19b1) | Jan 27, 2022 |
| Dell          | 014GRG A03                  | Desktop     | [223d955a90](https://bsd-hardware.info/?probe=223d955a90) | Jan 26, 2022 |
| Apple         | Mac-DB15BD556843C820 iMa... | All in one  | [2506316700](https://bsd-hardware.info/?probe=2506316700) | Jan 26, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [8edf072b67](https://bsd-hardware.info/?probe=8edf072b67) | Jan 25, 2022 |
| ASRock        | X570 Pro4                   | Desktop     | [d77aae8064](https://bsd-hardware.info/?probe=d77aae8064) | Jan 23, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [04abd226f3](https://bsd-hardware.info/?probe=04abd226f3) | Jan 21, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [9f06290060](https://bsd-hardware.info/?probe=9f06290060) | Jan 17, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [9f442754d0](https://bsd-hardware.info/?probe=9f442754d0) | Jan 17, 2022 |
| Dell          | Latitude E6430              | Notebook    | [e18a4bc564](https://bsd-hardware.info/?probe=e18a4bc564) | Jan 10, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [19be37f181](https://bsd-hardware.info/?probe=19be37f181) | Jan 09, 2022 |
| Intel         | SKYBAY                      | Desktop     | [64db889658](https://bsd-hardware.info/?probe=64db889658) | Jan 01, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [a671e3eb04](https://bsd-hardware.info/?probe=a671e3eb04) | Dec 31, 2021 |
| Acer          | Aspire 5742G                | Notebook    | [b77a4ee97c](https://bsd-hardware.info/?probe=b77a4ee97c) | Dec 30, 2021 |
| Dell          | 0VV3F2 A02                  | Server      | [2897e61a2f](https://bsd-hardware.info/?probe=2897e61a2f) | Dec 28, 2021 |
| Acer          | Aspire 5742G                | Notebook    | [b650885b00](https://bsd-hardware.info/?probe=b650885b00) | Dec 24, 2021 |
| MSI           | H81M-P32                    | Desktop     | [bb4e756ca9](https://bsd-hardware.info/?probe=bb4e756ca9) | Dec 20, 2021 |
| Supermicro    | X11SSN-L-VDCA               | Server      | [2efe92bba7](https://bsd-hardware.info/?probe=2efe92bba7) | Dec 20, 2021 |
| Dell          | Latitude E5470              | Notebook    | [18470afd9d](https://bsd-hardware.info/?probe=18470afd9d) | Dec 19, 2021 |
| Gigabyte      | H110TN                      | Desktop     | [8b6f0f839d](https://bsd-hardware.info/?probe=8b6f0f839d) | Dec 18, 2021 |
| Supermicro    | X11SSN-L-VDCA               | Server      | [5f9458870a](https://bsd-hardware.info/?probe=5f9458870a) | Dec 18, 2021 |
| Dell          | 0YY821 A00                  | Desktop     | [5de293a0be](https://bsd-hardware.info/?probe=5de293a0be) | Dec 17, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [32d20b9b8e](https://bsd-hardware.info/?probe=32d20b9b8e) | Dec 14, 2021 |
| ASUSTek       | H110M-K                     | Desktop     | [2921401f70](https://bsd-hardware.info/?probe=2921401f70) | Dec 12, 2021 |
| Dell          | G15 5510                    | Notebook    | [2da7a07664](https://bsd-hardware.info/?probe=2da7a07664) | Dec 07, 2021 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [66ed413cab](https://bsd-hardware.info/?probe=66ed413cab) | Dec 05, 2021 |
| ASUSTek       | P7P55D                      | Desktop     | [73373c3c65](https://bsd-hardware.info/?probe=73373c3c65) | Dec 04, 2021 |
| ASUSTek       | P7P55D                      | Desktop     | [540d2ef68c](https://bsd-hardware.info/?probe=540d2ef68c) | Nov 29, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [bc3b65334e](https://bsd-hardware.info/?probe=bc3b65334e) | Nov 29, 2021 |
| Dell          | G15 5510                    | Notebook    | [8846b3fd69](https://bsd-hardware.info/?probe=8846b3fd69) | Nov 27, 2021 |
| Shuttle       | FH270                       | Desktop     | [81643d52fd](https://bsd-hardware.info/?probe=81643d52fd) | Nov 26, 2021 |
| Dell          | 0VRCY5 A14                  | Server      | [5add1e88aa](https://bsd-hardware.info/?probe=5add1e88aa) | Nov 26, 2021 |
| Dell          | 0VRCY5 A14                  | Server      | [23281cbd58](https://bsd-hardware.info/?probe=23281cbd58) | Nov 26, 2021 |
| Dell          | 0VRCY5 A14                  | Server      | [f092d1f57b](https://bsd-hardware.info/?probe=f092d1f57b) | Nov 26, 2021 |
| ASRock        | Q1900B-ITX                  | Desktop     | [7f32937b2c](https://bsd-hardware.info/?probe=7f32937b2c) | Nov 26, 2021 |
| Shuttle       | FZ270                       | Desktop     | [309687b5be](https://bsd-hardware.info/?probe=309687b5be) | Nov 26, 2021 |
| ASRock        | Q1900B-ITX                  | Desktop     | [4df18caa5f](https://bsd-hardware.info/?probe=4df18caa5f) | Nov 26, 2021 |
| HP            | ProLiant DL360p Gen8        | Server      | [74a4364a7f](https://bsd-hardware.info/?probe=74a4364a7f) | Nov 25, 2021 |
| HP            | 213D A01                    | Desktop     | [0059e5b645](https://bsd-hardware.info/?probe=0059e5b645) | Nov 23, 2021 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | Notebook    | [7330a6f958](https://bsd-hardware.info/?probe=7330a6f958) | Nov 20, 2021 |
| Gigabyte      | MX33-BS1-V1                 | Server      | [bccac8e3bb](https://bsd-hardware.info/?probe=bccac8e3bb) | Nov 19, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [12a360ddd1](https://bsd-hardware.info/?probe=12a360ddd1) | Nov 14, 2021 |
| Dell          | G15 5510                    | Notebook    | [e9d432bc06](https://bsd-hardware.info/?probe=e9d432bc06) | Nov 12, 2021 |
| Dell          | G15 5510                    | Notebook    | [91750755e4](https://bsd-hardware.info/?probe=91750755e4) | Nov 12, 2021 |
| Acer          | Aspire 5742G                | Notebook    | [0513869be8](https://bsd-hardware.info/?probe=0513869be8) | Nov 09, 2021 |
| Dell          | Latitude E6430              | Notebook    | [46f2ef2432](https://bsd-hardware.info/?probe=46f2ef2432) | Nov 08, 2021 |
| Unknown       | Unknown                     | Desktop     | [d31ea9f041](https://bsd-hardware.info/?probe=d31ea9f041) | Nov 02, 2021 |
| Dell          | 0JD6X3 A05                  | Server      | [76dc6d941d](https://bsd-hardware.info/?probe=76dc6d941d) | Oct 30, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [9f8010bdbe](https://bsd-hardware.info/?probe=9f8010bdbe) | Oct 25, 2021 |
| HP            | ProLiant DL360 G7           | Server      | [5c6ee51d15](https://bsd-hardware.info/?probe=5c6ee51d15) | Oct 23, 2021 |
| Gigabyte      | B450M S2H                   | Desktop     | [f3bf8edc1e](https://bsd-hardware.info/?probe=f3bf8edc1e) | Oct 22, 2021 |
| HP            | 213D A01                    | Desktop     | [4b4903dfb2](https://bsd-hardware.info/?probe=4b4903dfb2) | Oct 17, 2021 |
| Dell          | Latitude E6430              | Notebook    | [d31f35bb29](https://bsd-hardware.info/?probe=d31f35bb29) | Oct 15, 2021 |
| Gigabyte      | B450M DS3H                  | Desktop     | [445b53ddba](https://bsd-hardware.info/?probe=445b53ddba) | Oct 15, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [3d0a63b493](https://bsd-hardware.info/?probe=3d0a63b493) | Oct 12, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [fc1eda0998](https://bsd-hardware.info/?probe=fc1eda0998) | Oct 08, 2021 |
| Gigabyte      | B450M DS3H                  | Desktop     | [50e4e13ee0](https://bsd-hardware.info/?probe=50e4e13ee0) | Oct 07, 2021 |
| MSI           | MS-7B53                     | Desktop     | [c7104d301e](https://bsd-hardware.info/?probe=c7104d301e) | Oct 05, 2021 |
| Unknown       | Raspberry Pi 4 Model B R... | Desktop     | [49173900e7](https://bsd-hardware.info/?probe=49173900e7) | Oct 04, 2021 |
| Unknown       | Raspberry Pi 4 Model B R... | Desktop     | [d05a877535](https://bsd-hardware.info/?probe=d05a877535) | Oct 03, 2021 |
| ASUSTek       | X555LB                      | Notebook    | [e3443d9f27](https://bsd-hardware.info/?probe=e3443d9f27) | Oct 02, 2021 |
| Intel         | SHARKBAY                    | Desktop     | [96448603f5](https://bsd-hardware.info/?probe=96448603f5) | Oct 02, 2021 |
| ZOTAC         | ZBOX-CI341                  | Mini pc     | [e186d750d0](https://bsd-hardware.info/?probe=e186d750d0) | Sep 30, 2021 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [a302e181a5](https://bsd-hardware.info/?probe=a302e181a5) | Sep 27, 2021 |
| Dell          | 04YP6J A02                  | Desktop     | [9ff547c00b](https://bsd-hardware.info/?probe=9ff547c00b) | Sep 16, 2021 |
| IBM           | ThinkPad X41 2525FAG        | Notebook    | [63a34dc807](https://bsd-hardware.info/?probe=63a34dc807) | Sep 14, 2021 |
| ASUSTek       | Q87T                        | Desktop     | [91e631c240](https://bsd-hardware.info/?probe=91e631c240) | Sep 11, 2021 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [c7b549e91e](https://bsd-hardware.info/?probe=c7b549e91e) | Sep 02, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [9e13729a12](https://bsd-hardware.info/?probe=9e13729a12) | Sep 02, 2021 |
| Essentiel ... | MS-7848                     | Desktop     | [fa20a0307e](https://bsd-hardware.info/?probe=fa20a0307e) | Sep 01, 2021 |
| Dell          | 086HF8 A07                  | Server      | [810f826ac4](https://bsd-hardware.info/?probe=810f826ac4) | Aug 26, 2021 |
| Intel         | SHARKBAY                    | Desktop     | [38332c6f8d](https://bsd-hardware.info/?probe=38332c6f8d) | Aug 16, 2021 |
| Lenovo        | Unknown                     | Notebook    | [e16ce5e864](https://bsd-hardware.info/?probe=e16ce5e864) | Aug 08, 2021 |
| AOpen         | D1009 A1A4                  | Desktop     | [dc60a8dece](https://bsd-hardware.info/?probe=dc60a8dece) | Aug 03, 2021 |
| Fujitsu Si... | AMILO PRO V3515             | Notebook    | [77676fbcfc](https://bsd-hardware.info/?probe=77676fbcfc) | Jul 18, 2021 |
| Dell          | 012KND A00                  | Mini pc     | [fd9fbe6981](https://bsd-hardware.info/?probe=fd9fbe6981) | Jul 16, 2021 |
| Dell          | 012KND A00                  | Mini pc     | [ccbdcabf0a](https://bsd-hardware.info/?probe=ccbdcabf0a) | Jul 12, 2021 |
| HP            | 1998                        | Desktop     | [fdf0088303](https://bsd-hardware.info/?probe=fdf0088303) | Jul 08, 2021 |
| Supermicro    | X10SDV-TP8F                 | Server      | [51d7177ca5](https://bsd-hardware.info/?probe=51d7177ca5) | Jul 01, 2021 |
| Toshiba       | PORTEGE X20W-D              | Convertible | [1e5dc453f6](https://bsd-hardware.info/?probe=1e5dc453f6) | Jun 25, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [668bf95221](https://bsd-hardware.info/?probe=668bf95221) | Jun 25, 2021 |
| Unknown       | Unknown                     | Desktop     | [1fffc03fbf](https://bsd-hardware.info/?probe=1fffc03fbf) | Jun 24, 2021 |
| Lenovo        | ThinkPad T440 20B7S1860W    | Notebook    | [8552205176](https://bsd-hardware.info/?probe=8552205176) | Jun 22, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [9f82e215c3](https://bsd-hardware.info/?probe=9f82e215c3) | Jun 22, 2021 |
| Dell          | 0MJ137 A00                  | Server      | [8a115f25d1](https://bsd-hardware.info/?probe=8a115f25d1) | Jun 18, 2021 |
| Dell          | Vostro 3560                 | Notebook    | [ce9d5f9a46](https://bsd-hardware.info/?probe=ce9d5f9a46) | Jun 18, 2021 |
| Dell          | 012KND A00                  | Mini pc     | [4097d7aea8](https://bsd-hardware.info/?probe=4097d7aea8) | Jun 16, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [a9fe2f5aad](https://bsd-hardware.info/?probe=a9fe2f5aad) | Jun 16, 2021 |
| Lenovo        | Board                       | Desktop     | [c981ffdff7](https://bsd-hardware.info/?probe=c981ffdff7) | Jun 15, 2021 |
| Dell          | Latitude 5400               | Notebook    | [1bb6c1f63f](https://bsd-hardware.info/?probe=1bb6c1f63f) | Jun 15, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [eeb4489d2f](https://bsd-hardware.info/?probe=eeb4489d2f) | Jun 13, 2021 |
| Dell          | Latitude E6440              | Notebook    | [8fa2c1f5c4](https://bsd-hardware.info/?probe=8fa2c1f5c4) | Jun 13, 2021 |
| Dell          | Latitude E6440              | Notebook    | [77f259babe](https://bsd-hardware.info/?probe=77f259babe) | Jun 12, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [338240a790](https://bsd-hardware.info/?probe=338240a790) | Jun 05, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [bf23a1ca58](https://bsd-hardware.info/?probe=bf23a1ca58) | Jun 02, 2021 |
| Dell          | 012KND A00                  | Mini pc     | [9f4ebe949f](https://bsd-hardware.info/?probe=9f4ebe949f) | May 31, 2021 |
| MSI           | H81M-P32                    | Desktop     | [1ffaa46853](https://bsd-hardware.info/?probe=1ffaa46853) | May 31, 2021 |
| Dell          | 012KND A00                  | Mini pc     | [b19abd94b7](https://bsd-hardware.info/?probe=b19abd94b7) | May 31, 2021 |
| Dell          | 012KND A00                  | Mini pc     | [732a50af16](https://bsd-hardware.info/?probe=732a50af16) | May 29, 2021 |
| MSI           | H81M-P32                    | Desktop     | [253deda07f](https://bsd-hardware.info/?probe=253deda07f) | May 28, 2021 |
| Lenovo        | Board                       | Desktop     | [1d6f23a5de](https://bsd-hardware.info/?probe=1d6f23a5de) | May 24, 2021 |
| Dell          | Latitude E6410              | Notebook    | [211fe874fd](https://bsd-hardware.info/?probe=211fe874fd) | May 22, 2021 |
| Dell          | 0R230R A00                  | Desktop     | [bd8bf06e7f](https://bsd-hardware.info/?probe=bd8bf06e7f) | May 21, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [6317bd7dbd](https://bsd-hardware.info/?probe=6317bd7dbd) | May 05, 2021 |
| Unknown       | Unknown                     | Desktop     | [1dcb55d9fe](https://bsd-hardware.info/?probe=1dcb55d9fe) | May 05, 2021 |
| Supermicro    | X7DCL                       | Desktop     | [27fc294bca](https://bsd-hardware.info/?probe=27fc294bca) | May 03, 2021 |
| Dell          | Latitude E6440              | Notebook    | [3a656ded12](https://bsd-hardware.info/?probe=3a656ded12) | Apr 19, 2021 |
| Dell          | Latitude E6440              | Notebook    | [68f57531cb](https://bsd-hardware.info/?probe=68f57531cb) | Apr 19, 2021 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [b848b8e046](https://bsd-hardware.info/?probe=b848b8e046) | Apr 03, 2021 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [7ce3b2f01e](https://bsd-hardware.info/?probe=7ce3b2f01e) | Mar 27, 2021 |
| Dell          | 086HF8 A07                  | Server      | [0a3a820345](https://bsd-hardware.info/?probe=0a3a820345) | Mar 26, 2021 |
| Supermicro    | X7SLA                       | Desktop     | [043c20b93d](https://bsd-hardware.info/?probe=043c20b93d) | Mar 19, 2021 |
| Dell          | Latitude E6440              | Notebook    | [a332efd9d9](https://bsd-hardware.info/?probe=a332efd9d9) | Mar 15, 2021 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [b570778ef7](https://bsd-hardware.info/?probe=b570778ef7) | Mar 14, 2021 |
| Dell          | 0TY019 A01                  | Server      | [6a1cb01323](https://bsd-hardware.info/?probe=6a1cb01323) | Mar 09, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [dee034110e](https://bsd-hardware.info/?probe=dee034110e) | Mar 05, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [73eec13c5e](https://bsd-hardware.info/?probe=73eec13c5e) | Mar 02, 2021 |
| Unknown       | Unknown                     | Desktop     | [6d7bac1be1](https://bsd-hardware.info/?probe=6d7bac1be1) | Feb 23, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [60d084275e](https://bsd-hardware.info/?probe=60d084275e) | Feb 19, 2021 |
| Dell          | 05KX61 A02                  | Server      | [31b6e52cf4](https://bsd-hardware.info/?probe=31b6e52cf4) | Feb 15, 2021 |
| HP            | ENVY dv7                    | Notebook    | [4637a9eeff](https://bsd-hardware.info/?probe=4637a9eeff) | Feb 14, 2021 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [8d8683565a](https://bsd-hardware.info/?probe=8d8683565a) | Feb 13, 2021 |
| ASRock        | D1800B-ITX                  | Desktop     | [38f8b13f43](https://bsd-hardware.info/?probe=38f8b13f43) | Feb 10, 2021 |
| Unknown       | Unknown                     | Desktop     | [f4b7bb4518](https://bsd-hardware.info/?probe=f4b7bb4518) | Feb 08, 2021 |
| Dell          | 096JG8 A00                  | Desktop     | [b6630c8516](https://bsd-hardware.info/?probe=b6630c8516) | Feb 07, 2021 |
| Dell          | Latitude E5430 vPro         | Notebook    | [bee421a110](https://bsd-hardware.info/?probe=bee421a110) | Feb 06, 2021 |
| Dell          | Latitude E5430 vPro         | Notebook    | [e8157ac6a3](https://bsd-hardware.info/?probe=e8157ac6a3) | Feb 06, 2021 |
| Dell          | 012KND A00                  | Mini pc     | [5f293a8796](https://bsd-hardware.info/?probe=5f293a8796) | Feb 05, 2021 |
| Dell          | 096JG8 A00                  | Desktop     | [e73a728a76](https://bsd-hardware.info/?probe=e73a728a76) | Feb 03, 2021 |
| Dell          | 096JG8 A00                  | Desktop     | [612272e598](https://bsd-hardware.info/?probe=612272e598) | Feb 03, 2021 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | Notebook    | [3d18f3f8a9](https://bsd-hardware.info/?probe=3d18f3f8a9) | Jan 23, 2021 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [b26cfcd81d](https://bsd-hardware.info/?probe=b26cfcd81d) | Dec 28, 2020 |
| Lenovo        | ThinkPad X200s 7470A98      | Notebook    | [41f36aa8b6](https://bsd-hardware.info/?probe=41f36aa8b6) | Dec 19, 2020 |
| ASUSTek       | E45M1-I DELUXE              | Desktop     | [8e767b517d](https://bsd-hardware.info/?probe=8e767b517d) | Dec 16, 2020 |
| Unknown       | Spring Peak                 | Notebook    | [b61f5c268a](https://bsd-hardware.info/?probe=b61f5c268a) | Dec 15, 2020 |
| PC Special... | Recoil II                   | Notebook    | [343eec31b5](https://bsd-hardware.info/?probe=343eec31b5) | Dec 06, 2020 |
| Panasonic     | CFMX4-1                     | Notebook    | [761d21f21a](https://bsd-hardware.info/?probe=761d21f21a) | Dec 06, 2020 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [dce3ba8c99](https://bsd-hardware.info/?probe=dce3ba8c99) | Nov 18, 2020 |
| HP            | 213D A01                    | Desktop     | [ca6ab5347e](https://bsd-hardware.info/?probe=ca6ab5347e) | Nov 13, 2020 |
| Shuttle       | FH270                       | Desktop     | [532cda62a8](https://bsd-hardware.info/?probe=532cda62a8) | Oct 29, 2020 |
| Intel         | D53427RKE G87971-406        | Desktop     | [bb6eeb8ef8](https://bsd-hardware.info/?probe=bb6eeb8ef8) | Oct 29, 2020 |
| Dell          | 0VRCY5 A14                  | Server      | [8f4b51dabd](https://bsd-hardware.info/?probe=8f4b51dabd) | Oct 29, 2020 |
| Dell          | 0VRCY5 A14                  | Server      | [bb3d02abc3](https://bsd-hardware.info/?probe=bb3d02abc3) | Oct 29, 2020 |
| Dell          | 0VRCY5 A14                  | Server      | [26d1d76748](https://bsd-hardware.info/?probe=26d1d76748) | Oct 29, 2020 |
| Dell          | 0VRCY5 A14                  | Server      | [fb3b9ecee9](https://bsd-hardware.info/?probe=fb3b9ecee9) | Oct 29, 2020 |
| Dell          | 0VRCY5 A14                  | Server      | [785c53f34c](https://bsd-hardware.info/?probe=785c53f34c) | Oct 29, 2020 |
| Dell          | 0VRCY5 A14                  | Server      | [f5efac2cc7](https://bsd-hardware.info/?probe=f5efac2cc7) | Oct 29, 2020 |
| Dell          | 0VRCY5 A14                  | Server      | [cc8f51b953](https://bsd-hardware.info/?probe=cc8f51b953) | Oct 29, 2020 |
| Dell          | 0VRCY5 A14                  | Server      | [397aee2b27](https://bsd-hardware.info/?probe=397aee2b27) | Oct 29, 2020 |
| Intel         | S2600GZ G11481-352          | Server      | [474b0e44ea](https://bsd-hardware.info/?probe=474b0e44ea) | Oct 29, 2020 |
| Dell          | 0M332H A00                  | Server      | [9c70f76349](https://bsd-hardware.info/?probe=9c70f76349) | Oct 29, 2020 |
| Dell          | 072T6D A01                  | Server      | [4389b1ce81](https://bsd-hardware.info/?probe=4389b1ce81) | Oct 29, 2020 |
| Shuttle       | FH270                       | Desktop     | [e93928c59b](https://bsd-hardware.info/?probe=e93928c59b) | Oct 29, 2020 |
| ASRock        | QC5000M-ITX/PH              | Desktop     | [8d27c35122](https://bsd-hardware.info/?probe=8d27c35122) | Oct 29, 2020 |
| Lenovo        | ThinkPad W520 4284W5L       | Notebook    | [2664153a6e](https://bsd-hardware.info/?probe=2664153a6e) | Oct 29, 2020 |
| Dell          | 06NWYK A01                  | Desktop     | [9d4ea8797b](https://bsd-hardware.info/?probe=9d4ea8797b) | Oct 29, 2020 |
| Dell          | 06NWYK A01                  | Desktop     | [5ae47d058d](https://bsd-hardware.info/?probe=5ae47d058d) | Oct 29, 2020 |
| Lenovo        | ThinkPad X230 23254S6       | Notebook    | [f4ac5ddaa4](https://bsd-hardware.info/?probe=f4ac5ddaa4) | Oct 25, 2020 |
| HP            | 635                         | Notebook    | [3b21406e87](https://bsd-hardware.info/?probe=3b21406e87) | Oct 23, 2020 |
| PC Engines    | apu1                        | Desktop     | [c77b06b3eb](https://bsd-hardware.info/?probe=c77b06b3eb) | Oct 20, 2020 |
| Lenovo        | ThinkPad T480 20L6S4GR02    | Notebook    | [6c2d8a57ea](https://bsd-hardware.info/?probe=6c2d8a57ea) | Oct 19, 2020 |
| Lenovo        | ThinkPad W520 4284W5L       | Notebook    | [01d2c090de](https://bsd-hardware.info/?probe=01d2c090de) | Oct 03, 2020 |
| Wistron       | ProLiant ML110 G5           | Desktop     | [4906f28cfc](https://bsd-hardware.info/?probe=4906f28cfc) | Aug 14, 2020 |
| ASUSTek       | AM1M-A                      | Desktop     | [4dca0d2aa4](https://bsd-hardware.info/?probe=4dca0d2aa4) | Aug 14, 2020 |
| PC Engines    | APU2                        | Desktop     | [82f64585b8](https://bsd-hardware.info/?probe=82f64585b8) | Aug 14, 2020 |
| Fujitsu       | D3003-B1 S26361-D3003-B1    | Desktop     | [8c92fcf25f](https://bsd-hardware.info/?probe=8c92fcf25f) | Aug 14, 2020 |
| Fujitsu       | D3003-B1 S26361-D3003-B1    | Desktop     | [b6a4e39a1b](https://bsd-hardware.info/?probe=b6a4e39a1b) | Aug 14, 2020 |
| Dell          | Latitude XT2                | Notebook    | [19456100cf](https://bsd-hardware.info/?probe=19456100cf) | Jul 16, 2020 |
| Dell          | Latitude XT2                | Notebook    | [160725773f](https://bsd-hardware.info/?probe=160725773f) | Jul 16, 2020 |
| Sony          | SVF1521K1EB                 | Notebook    | [fe29d4e002](https://bsd-hardware.info/?probe=fe29d4e002) | Jun 29, 2020 |
| ASRock        | N3150B-ITX                  | Desktop     | [2b9248155e](https://bsd-hardware.info/?probe=2b9248155e) | Jun 09, 2020 |
| ASUSTek       | N3150I-C                    | Desktop     | [3da71be3c9](https://bsd-hardware.info/?probe=3da71be3c9) | Jun 09, 2020 |
| Lenovo        | ThinkPad W520 4284W5L       | Notebook    | [9ba8051e48](https://bsd-hardware.info/?probe=9ba8051e48) | Jun 09, 2020 |
| Dell          | Latitude E7240              | Notebook    | [1de87c0000](https://bsd-hardware.info/?probe=1de87c0000) | May 30, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Poland/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| helloSystem 0.8.1    | 21        | 4.91%   |
| helloSystem 0.7.0    | 15        | 3.5%    |
| OpenBSD 7.0          | 12        | 2.8%    |
| FreeBSD 12.1-p10     | 12        | 2.8%    |
| OPNsense 22.7.10     | 9         | 2.1%    |
| FreeBSD 14.0-CURRENT | 9         | 2.1%    |
| FreeBSD 13.1-p8      | 9         | 2.1%    |
| OPNsense 23.1.7      | 7         | 1.64%   |
| OPNsense 23.1.11     | 7         | 1.64%   |
| OPNsense 23.1.1      | 7         | 1.64%   |
| FreeBSD 13.2         | 7         | 1.64%   |
| OPNsense 23.7.9      | 6         | 1.4%    |
| OPNsense 23.7.7      | 6         | 1.4%    |
| OPNsense 23.7.12     | 6         | 1.4%    |
| OPNsense 23.1        | 6         | 1.4%    |
| OpenBSD 7.1          | 6         | 1.4%    |
| helloSystem 0.6.0    | 6         | 1.4%    |
| FreeBSD 12.2         | 6         | 1.4%    |
| OPNsense 23.7.5      | 5         | 1.17%   |
| OPNsense 23.7.4      | 5         | 1.17%   |
| OPNsense 23.1.5      | 5         | 1.17%   |
| OPNsense 22.1        | 5         | 1.17%   |
| OPNsense 21.7.3      | 5         | 1.17%   |
| OPNsense 21.1.6      | 5         | 1.17%   |
| helloSystem 0.8.0    | 5         | 1.17%   |
| helloSystem 0.5.0    | 5         | 1.17%   |
| FreeBSD 13.0-p5      | 5         | 1.17%   |
| OPNsense 23.1.9      | 4         | 0.93%   |
| OPNsense 23.1.8      | 4         | 0.93%   |
| OPNsense 22.7.4      | 4         | 0.93%   |
| OPNsense 22.7.2      | 4         | 0.93%   |
| OPNsense 22.7.11     | 4         | 0.93%   |
| OPNsense 22.7        | 4         | 0.93%   |
| OPNsense 22.1.8      | 4         | 0.93%   |
| OPNsense 22.1.10     | 4         | 0.93%   |
| OPNsense 21.7.7      | 4         | 0.93%   |
| OPNsense 21.1.2      | 4         | 0.93%   |
| OPNsense 21.1.1      | 4         | 0.93%   |
| OPNsense 21.1        | 4         | 0.93%   |
| OpenBSD 7.3          | 4         | 0.93%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 154       | 45.16%  |
| FreeBSD     | 93        | 27.27%  |
| helloSystem | 53        | 15.54%  |
| OpenBSD     | 26        | 7.62%   |
| GhostBSD    | 8         | 2.35%   |
| NomadBSD    | 3         | 0.88%   |
| XigmaNAS    | 2         | 0.59%   |
| NetBSD      | 2         | 0.59%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| amd64  | 328       | 96.47%  |
| arm64  | 6         | 1.76%   |
| i386   | 4         | 1.18%   |
| macppc | 1         | 0.29%   |
| armv7  | 1         | 0.29%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 201       | 58.26%  |
| helloDesktop  | 61        | 17.68%  |
| GNOME         | 16        | 4.64%   |
| fvwm          | 16        | 4.64%   |
| XFCE          | 15        | 4.35%   |
| KDE5          | 11        | 3.19%   |
| MATE          | 9         | 2.61%   |
| Openbox       | 5         | 1.45%   |
| TWM           | 4         | 1.16%   |
| i3            | 4         | 1.16%   |
| xinitrc       | 1         | 0.29%   |
| xfwm          | 1         | 0.29%   |
| Enlightenment | 1         | 0.29%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 213       | 62.46%  |
| X11     | 128       | 37.54%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 238       | 69.59%  |
| SLiM    | 63        | 18.42%  |
| SDDM    | 13        | 3.8%    |
| LightDM | 11        | 3.22%   |
| GDM     | 9         | 2.63%   |
| XDM     | 8         | 2.34%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang           | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 207       | 60%     |
| en_US          | 49        | 14.2%   |
| C              | 46        | 13.33%  |
| pl_PL          | 29        | 8.41%   |
| fr_FR          | 8         | 2.32%   |
| pl             | 2         | 0.58%   |
| en_GB          | 2         | 0.58%   |
| en_IE.US-ASCII | 1         | 0.29%   |
| en             | 1         | 0.29%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 284       | 83.04%  |
| BIOS | 58        | 16.96%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Zfs    | 160       | 46.38%  |
| Ufs    | 138       | 40%     |
| Ffs    | 26        | 7.54%   |
| Cd9660 | 21        | 6.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 306       | 90%     |
| MBR     | 30        | 8.82%   |
| Unknown | 3         | 0.88%   |
| BSD     | 1         | 0.29%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Dell                       | 68        | 20%     |
| Lenovo                     | 44        | 12.94%  |
| Hewlett-Packard            | 36        | 10.59%  |
| Unknown                    | 25        | 7.35%   |
| Gigabyte Technology        | 24        | 7.06%   |
| ASUSTek Computer           | 24        | 7.06%   |
| Intel                      | 18        | 5.29%   |
| ASRock                     | 14        | 4.12%   |
| MSI                        | 12        | 3.53%   |
| Fujitsu                    | 12        | 3.53%   |
| Supermicro                 | 8         | 2.35%   |
| ZOTAC                      | 5         | 1.47%   |
| Acer                       | 5         | 1.47%   |
| Techvision                 | 4         | 1.18%   |
| PC Engines                 | 4         | 1.18%   |
| Shuttle                    | 3         | 0.88%   |
| Apple                      | 3         | 0.88%   |
| Inventec                   | 2         | 0.59%   |
| Google                     | 2         | 0.59%   |
| Deciso                     | 2         | 0.59%   |
| AMI                        | 2         | 0.59%   |
| Yanling                    | 1         | 0.29%   |
| Wistron                    | 1         | 0.29%   |
| Toshiba                    | 1         | 0.29%   |
| Sony                       | 1         | 0.29%   |
| ShenZhen MinWin Technology | 1         | 0.29%   |
| Seeed Studio               | 1         | 0.29%   |
| Samsung Electronics        | 1         | 0.29%   |
| Raspberry Pi Foundation    | 1         | 0.29%   |
| PC Specialist              | 1         | 0.29%   |
| Panasonic                  | 1         | 0.29%   |
| Packard Bell               | 1         | 0.29%   |
| NU591R                     | 1         | 0.29%   |
| Notebook                   | 1         | 0.29%   |
| Medion                     | 1         | 0.29%   |
| IGEL Technology            | 1         | 0.29%   |
| iEi                        | 1         | 0.29%   |
| IBM                        | 1         | 0.29%   |
| Fujitsu Siemens            | 1         | 0.29%   |
| Essentiel B                | 1         | 0.29%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 26        | 7.65%   |
| Dell OEM-R 720xd                    | 13        | 3.82%   |
| HP t620 PLUS Quad Core TC           | 11        | 3.24%   |
| Fujitsu FUTRO S920                  | 7         | 2.06%   |
| Dell Wyse 5070 Extended Thin Client | 6         | 1.76%   |
| Lenovo ThinkPad X200 745969G        | 5         | 1.47%   |
| Gigabyte B360N WIFI                 | 5         | 1.47%   |
| Techvision TVI7309X                 | 4         | 1.18%   |
| Dell Wyse 5070 Thin Client          | 4         | 1.18%   |
| ZOTAC ZBOX-CI329NANO                | 3         | 0.88%   |
| ASUS All Series                     | 3         | 0.88%   |
| ASRock Q1900B-ITX                   | 3         | 0.88%   |
| Lenovo ThinkCentre M700 10J0S1CK00  | 2         | 0.59%   |
| Intel SHARKBAY                      | 2         | 0.59%   |
| Intel Q3XXG4-P V1.0                 | 2         | 0.59%   |
| Intel D2500CC AAG81477-401          | 2         | 0.59%   |
| Intel Appliance B4                  | 2         | 0.59%   |
| HP t730 Thin Client                 | 2         | 0.59%   |
| HP ProLiant DL360 G7                | 2         | 0.59%   |
| HP 17E2                             | 2         | 0.59%   |
| Gigabyte H270N-WIFI                 | 2         | 0.59%   |
| Gigabyte H110TN                     | 2         | 0.59%   |
| Dell OptiPlex 7050                  | 2         | 0.59%   |
| Dell OptiPlex 3040                  | 2         | 0.59%   |
| Dell OptiPlex 3020                  | 2         | 0.59%   |
| Dell Latitude E6430                 | 2         | 0.59%   |
| ASRock J3455B-ITX                   | 2         | 0.59%   |
| ZOTAC ZBOX-CI341                    | 1         | 0.29%   |
| ZOTAC ZBOX-CI323NANO                | 1         | 0.29%   |
| Yanling YL-EL4L-0A                  | 1         | 0.29%   |
| Wistron ProLiant ML110 G5           | 1         | 0.29%   |
| Toshiba PORTEGE X20W-D              | 1         | 0.29%   |
| Supermicro X9SCL/X9SCM              | 1         | 0.29%   |
| Supermicro X8STi                    | 1         | 0.29%   |
| Supermicro X8SIL                    | 1         | 0.29%   |
| Supermicro X7SLA                    | 1         | 0.29%   |
| Supermicro X7DCL                    | 1         | 0.29%   |
| Supermicro X11SSN-L                 | 1         | 0.29%   |
| Supermicro SYS-E300-9A-4CN10P       | 1         | 0.29%   |
| Supermicro SYS-5018D-FN8T           | 1         | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 27        | 7.94%   |
| Unknown              | 26        | 7.65%   |
| Dell OEM-R           | 13        | 3.82%   |
| Dell Latitude        | 13        | 3.82%   |
| Dell OptiPlex        | 12        | 3.53%   |
| HP t620              | 11        | 3.24%   |
| Dell Wyse            | 10        | 2.94%   |
| Dell PowerEdge       | 10        | 2.94%   |
| Fujitsu FUTRO        | 9         | 2.65%   |
| Lenovo ThinkCentre   | 6         | 1.76%   |
| Gigabyte B360N       | 5         | 1.47%   |
| Techvision TVI7309X  | 4         | 1.18%   |
| HP ProLiant          | 4         | 1.18%   |
| Dell Vostro          | 4         | 1.18%   |
| Acer Aspire          | 4         | 1.18%   |
| ZOTAC ZBOX-CI329NANO | 3         | 0.88%   |
| HP t730              | 3         | 0.88%   |
| HP EliteBook         | 3         | 0.88%   |
| HP Compaq            | 3         | 0.88%   |
| ASUS PRIME           | 3         | 0.88%   |
| ASUS All             | 3         | 0.88%   |
| ASRock Q1900B-ITX    | 3         | 0.88%   |
| Lenovo IdeaPad       | 2         | 0.59%   |
| Intel SHARKBAY       | 2         | 0.59%   |
| Intel Q3XXG4-P       | 2         | 0.59%   |
| Intel D2500CC        | 2         | 0.59%   |
| Intel Appliance      | 2         | 0.59%   |
| HP Laptop            | 2         | 0.59%   |
| HP ENVY              | 2         | 0.59%   |
| HP EliteDesk         | 2         | 0.59%   |
| HP 17E2              | 2         | 0.59%   |
| Gigabyte H270N-WIFI  | 2         | 0.59%   |
| Gigabyte H110TN      | 2         | 0.59%   |
| Gigabyte B450M       | 2         | 0.59%   |
| Dell Inspiron        | 2         | 0.59%   |
| ASUS TUF             | 2         | 0.59%   |
| ASUS ROG             | 2         | 0.59%   |
| ASUS P5G41T-M        | 2         | 0.59%   |
| ASRock J3455B-ITX    | 2         | 0.59%   |
| ZOTAC ZBOX-CI341     | 1         | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2014    | 57        | 16.76%  |
| 2018    | 36        | 10.59%  |
| 2020    | 26        | 7.65%   |
| 2019    | 26        | 7.65%   |
| 2022    | 25        | 7.35%   |
| 2012    | 24        | 7.06%   |
| 2016    | 22        | 6.47%   |
| 2021    | 21        | 6.18%   |
| 2013    | 18        | 5.29%   |
| 2009    | 16        | 4.71%   |
| 2011    | 14        | 4.12%   |
| 2015    | 12        | 3.53%   |
| 2017    | 11        | 3.24%   |
| 2010    | 10        | 2.94%   |
| 2023    | 8         | 2.35%   |
| Unknown | 5         | 1.47%   |
| 2008    | 3         | 0.88%   |
| 2007    | 3         | 0.88%   |
| 2006    | 3         | 0.88%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 188       | 55.29%  |
| Notebook       | 88        | 25.88%  |
| Server         | 33        | 9.71%   |
| Mini pc        | 23        | 6.76%   |
| All in one     | 5         | 1.47%   |
| Convertible    | 2         | 0.59%   |
| System on chip | 1         | 0.29%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 333       | 97.94%  |
| Yes  | 7         | 2.06%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 111       | 31.99%  |
| 4.01-8.0    | 88        | 25.36%  |
| 16.01-24.0  | 81        | 23.34%  |
| 32.01-64.0  | 23        | 6.63%   |
| 64.01-256.0 | 20        | 5.76%   |
| 2.01-3.0    | 8         | 2.31%   |
| 3.01-4.0    | 7         | 2.02%   |
| 0.51-1.0    | 5         | 1.44%   |
| 24.01-32.0  | 3         | 0.86%   |
| 1.01-2.0    | 1         | 0.29%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 182       | 51.27%  |
| 0.51-1.0    | 101       | 28.45%  |
| 1.01-2.0    | 48        | 13.52%  |
| 2.01-3.0    | 8         | 2.25%   |
| 4.01-8.0    | 4         | 1.13%   |
| 8.01-16.0   | 4         | 1.13%   |
| 3.01-4.0    | 2         | 0.56%   |
| 0           | 2         | 0.56%   |
| Unknown     | 2         | 0.56%   |
| 64.01-256.0 | 1         | 0.28%   |
| 16.01-24.0  | 1         | 0.28%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 203       | 57.34%  |
| 2      | 68        | 19.21%  |
| 0      | 48        | 13.56%  |
| 3      | 15        | 4.24%   |
| 4      | 7         | 1.98%   |
| 6      | 6         | 1.69%   |
| 5      | 3         | 0.85%   |
| 9      | 2         | 0.56%   |
| 10     | 1         | 0.28%   |
| 8      | 1         | 0.28%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 277       | 80.29%  |
| Yes       | 68        | 19.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 321       | 94.41%  |
| No        | 19        | 5.59%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 188       | 54.65%  |
| Yes       | 156       | 45.35%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 248       | 72.3%   |
| Yes       | 95        | 27.7%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Poland  | 340       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                      | Computers | Percent |
|---------------------------|-----------|---------|
| Warsaw                    | 54        | 14.36%  |
| Krakow                    | 29        | 7.71%   |
| Wroclaw                   | 27        | 7.18%   |
| Gdansk                    | 23        | 6.12%   |
| Gdynia                    | 22        | 5.85%   |
| Poznan                    | 12        | 3.19%   |
| Lodz                      | 10        | 2.66%   |
| Lublin                    | 8         | 2.13%   |
| Bydgoszcz                 | 5         | 1.33%   |
| Zgierz                    | 4         | 1.06%   |
| Piaseczno                 | 4         | 1.06%   |
| Miedziana Gora            | 4         | 1.06%   |
| Szczecin                  | 3         | 0.8%    |
| Radom                     | 3         | 0.8%    |
| Lezno                     | 3         | 0.8%    |
| Legionowo                 | 3         | 0.8%    |
| Kielce                    | 3         | 0.8%    |
| Katowice                  | 3         | 0.8%    |
| Gmina Świebodzin         | 3         | 0.8%    |
| Chrusty                   | 3         | 0.8%    |
| Е»ukowo                 | 2         | 0.53%   |
| Witkow                    | 2         | 0.53%   |
| Walendow                  | 2         | 0.53%   |
| Siedlce                   | 2         | 0.53%   |
| Radzionkow                | 2         | 0.53%   |
| Pstragowa                 | 2         | 0.53%   |
| Police                    | 2         | 0.53%   |
| Lubin                     | 2         | 0.53%   |
| Kamieniec Zabkowicki      | 2         | 0.53%   |
| Jelenia Góra             | 2         | 0.53%   |
| Jarosław                 | 2         | 0.53%   |
| Grudziądz                | 2         | 0.53%   |
| Gliwice                   | 2         | 0.53%   |
| Glincz                    | 2         | 0.53%   |
| CzД™stochowa           | 2         | 0.53%   |
| Chorzów                  | 2         | 0.53%   |
| Choroszcz                 | 2         | 0.53%   |
| Bialystok                 | 2         | 0.53%   |
| ЕљwiД™tochЕ‚owice | 1         | 0.27%   |
| Zajaczki Pierwsze         | 1         | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 55        | 94     | 14.25%  |
| WDC                 | 53        | 115    | 13.73%  |
| Seagate             | 43        | 77     | 11.14%  |
| GOODRAM             | 26        | 41     | 6.74%   |
| SanDisk             | 24        | 33     | 6.22%   |
| A-DATA Technology   | 19        | 23     | 4.92%   |
| Toshiba             | 15        | 32     | 3.89%   |
| Kingston            | 14        | 15     | 3.63%   |
| Crucial             | 9         | 17     | 2.33%   |
| Transcend           | 8         | 13     | 2.07%   |
| Intel               | 8         | 11     | 2.07%   |
| SPCC                | 7         | 11     | 1.81%   |
| China               | 7         | 9      | 1.81%   |
| Apacer              | 7         | 10     | 1.81%   |
| SK hynix            | 6         | 6      | 1.55%   |
| Hoodisk             | 6         | 12     | 1.55%   |
| Hitachi             | 6         | 6      | 1.55%   |
| Plextor             | 5         | 5      | 1.3%    |
| Patriot             | 5         | 5      | 1.3%    |
| NVMe                | 5         | 8      | 1.3%    |
| Innodisk            | 5         | 7      | 1.3%    |
| Hewlett-Packard     | 5         | 5      | 1.3%    |
| PNY                 | 4         | 8      | 1.04%   |
| OCZ                 | 4         | 4      | 1.04%   |
| LITEONIT            | 4         | 4      | 1.04%   |
| LITEON              | 4         | 4      | 1.04%   |
| Gigabyte Technology | 4         | 5      | 1.04%   |
| Micron Technology   | 3         | 9      | 0.78%   |
| HGST                | 3         | 5      | 0.78%   |
| Corsair             | 3         | 5      | 0.78%   |
| Lexar               | 2         | 2      | 0.52%   |
| Kston               | 2         | 2      | 0.52%   |
| Intenso             | 2         | 3      | 0.52%   |
| Fanxiang            | 2         | 3      | 0.52%   |
| Team                | 1         | 1      | 0.26%   |
| SSSTC               | 1         | 2      | 0.26%   |
| SSDPR-CX            | 1         | 1      | 0.26%   |
| Silicon Power       | 1         | 1      | 0.26%   |
| Silicon Motion      | 1         | 1      | 0.26%   |
| Phison              | 1         | 1      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| WDC WDS500G1R0A-68A4W0 500GB       | 6         | 1.4%    |
| Samsung HM321HI 320GB              | 6         | 1.4%    |
| WDC WD5000LPLX-22ZNTT0 500GB       | 5         | 1.17%   |
| Seagate ST1000LM035-1RK172 1TB     | 4         | 0.93%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 4         | 0.93%   |
| Seagate ST1000DM003-1CH162 1TB     | 4         | 0.93%   |
| SanDisk SDSA6MM-016G-1006 16GB     | 4         | 0.93%   |
| Hoodisk SSD 128GB                  | 4         | 0.93%   |
| GOODRAM SSDPR-CX400-512-G2 512GB   | 4         | 0.93%   |
| WDC WD20EFRX-68EUZN0 2TB           | 3         | 0.7%    |
| SPCC Solid State Disk 256GB        | 3         | 0.7%    |
| Seagate ST500DM002-1BD142 500GB    | 3         | 0.7%    |
| Samsung SSD 850 EVO 250GB          | 3         | 0.7%    |
| Kingston SUV500MS120G 120GB        | 3         | 0.7%    |
| Kingston SA400S37240G 240GB        | 3         | 0.7%    |
| Innodisk DEMSR- 16GB mSATA 3ME3    | 3         | 0.7%    |
| GOODRAM SSDPR-CX400-256-G2 256GB   | 3         | 0.7%    |
| GOODRAM SSDPR-CX400-256 256GB      | 3         | 0.7%    |
| GOODRAM SSDPR-CX400-128 128GB      | 3         | 0.7%    |
| GOODRAM SSDPR-CL100-120-G3 120GB   | 3         | 0.7%    |
| Crucial CT500MX500SSD1 500GB       | 3         | 0.7%    |
| Apacer AS340 240GB                 | 3         | 0.7%    |
| A-DATA SU800 256GB                 | 3         | 0.7%    |
| WDC WDS500G2B0B-00YS70 500GB       | 2         | 0.47%   |
| WDC WDS240G2G0A-00JH30 240GB       | 2         | 0.47%   |
| WDC WD20SDZW-11JJ8S0 2TB           | 2         | 0.47%   |
| WDC WD20NMVW-59EDZS7 2TB           | 2         | 0.47%   |
| WDC WD20EARS-00MVWB0 2TB           | 2         | 0.47%   |
| WDC WD10JPLX-00MBPT0 1TB           | 2         | 0.47%   |
| Transcend TS120GMTS420S 120GB      | 2         | 0.47%   |
| Toshiba MQ04ABF100 1TB             | 2         | 0.47%   |
| Seagate ST96812AS 64GB             | 2         | 0.47%   |
| Seagate ST500LT012-1DG142 500GB    | 2         | 0.47%   |
| Seagate ST4000LM024-2U817V 4TB     | 2         | 0.47%   |
| Seagate ST4000LM024-2AN17V 4TB     | 2         | 0.47%   |
| Seagate ST3250312AS 250GB          | 2         | 0.47%   |
| Seagate ST3250310AS 250GB          | 2         | 0.47%   |
| Seagate ST2000DL003-9VT166 2TB     | 2         | 0.47%   |
| Seagate ST1000NM0033-9ZM173 1TB    | 2         | 0.47%   |
| Seagate ST1000DM010-2EP102 1TB     | 2         | 0.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 44        | 89     | 34.11%  |
| Seagate             | 43        | 77     | 33.33%  |
| Samsung Electronics | 13        | 20     | 10.08%  |
| Toshiba             | 12        | 29     | 9.3%    |
| Hitachi             | 6         | 6      | 4.65%   |
| Hewlett-Packard     | 4         | 4      | 3.1%    |
| HGST                | 3         | 5      | 2.33%   |
| NVMe                | 2         | 3      | 1.55%   |
| SSDPR-CX            | 1         | 1      | 0.78%   |
| Apple               | 1         | 1      | 0.78%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 26        | 53     | 12.44%  |
| SanDisk             | 24        | 33     | 11.48%  |
| GOODRAM             | 24        | 37     | 11.48%  |
| Kingston            | 13        | 13     | 6.22%   |
| A-DATA Technology   | 13        | 16     | 6.22%   |
| WDC                 | 11        | 22     | 5.26%   |
| Crucial             | 8         | 16     | 3.83%   |
| Transcend           | 7         | 12     | 3.35%   |
| SPCC                | 7         | 11     | 3.35%   |
| China               | 7         | 9      | 3.35%   |
| Apacer              | 7         | 10     | 3.35%   |
| Hoodisk             | 6         | 12     | 2.87%   |
| Plextor             | 5         | 5      | 2.39%   |
| Innodisk            | 5         | 7      | 2.39%   |
| OCZ                 | 4         | 4      | 1.91%   |
| LITEONIT            | 4         | 4      | 1.91%   |
| Intel               | 4         | 7      | 1.91%   |
| Gigabyte Technology | 4         | 5      | 1.91%   |
| SK hynix            | 3         | 3      | 1.44%   |
| Patriot             | 3         | 3      | 1.44%   |
| Micron Technology   | 3         | 9      | 1.44%   |
| LITEON              | 3         | 3      | 1.44%   |
| Corsair             | 3         | 5      | 1.44%   |
| PNY                 | 2         | 5      | 0.96%   |
| NVMe                | 2         | 2      | 0.96%   |
| Kston               | 2         | 2      | 0.96%   |
| Intenso             | 2         | 3      | 0.96%   |
| Toshiba             | 1         | 1      | 0.48%   |
| Team                | 1         | 1      | 0.48%   |
| Silicon Power       | 1         | 1      | 0.48%   |
| Phison              | 1         | 1      | 0.48%   |
| Hewlett-Packard     | 1         | 1      | 0.48%   |
| FORESEE             | 1         | 1      | 0.48%   |
| Advantech           | 1         | 1      | 0.48%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 185       | 318    | 54.41%  |
| HDD  | 104       | 235    | 30.59%  |
| NVMe | 51        | 68     | 15%     |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 253       | 553    | 83.22%  |
| NVMe | 51        | 68     | 16.78%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 213       | 370    | 72.2%   |
| 0.51-1.0   | 50        | 95     | 16.95%  |
| 1.01-2.0   | 18        | 49     | 6.1%    |
| 3.01-4.0   | 7         | 15     | 2.37%   |
| 4.01-10.0  | 4         | 11     | 1.36%   |
| 2.01-3.0   | 3         | 13     | 1.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 133       | 37.25%  |
| 1-20           | 57        | 15.97%  |
| 251-500        | 52        | 14.57%  |
| 51-100         | 49        | 13.73%  |
| 21-50          | 30        | 8.4%    |
| 501-1000       | 27        | 7.56%   |
| 1001-2000      | 4         | 1.12%   |
| More than 3000 | 3         | 0.84%   |
| 2001-3000      | 2         | 0.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 311       | 88.35%  |
| 21-50          | 18        | 5.11%   |
| 101-250        | 9         | 2.56%   |
| 51-100         | 7         | 1.99%   |
| 251-500        | 4         | 1.14%   |
| 1001-2000      | 2         | 0.57%   |
| More than 3000 | 1         | 0.28%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                           | Computers | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| WDC WD5000LPLX-22ZNTT0 500GB                    | 2         | 2      | 3.92%   |
| Toshiba MQ04ABF100 1TB                          | 2         | 2      | 3.92%   |
| Seagate ST96812AS 64GB                          | 2         | 5      | 3.92%   |
| Seagate ST1000DM003-1CH162 1TB                  | 2         | 2      | 3.92%   |
| WDC WD7500BPKT-00PK4T0 752GB                    | 1         | 1      | 1.96%   |
| WDC WD360ADFD-00NLR1 37GB                       | 1         | 1      | 1.96%   |
| WDC WD3200BEKT-22PVMT0 320GB                    | 1         | 1      | 1.96%   |
| WDC WD3200AAVS-00ZTB0 320GB                     | 1         | 1      | 1.96%   |
| WDC WD2500AAKX-753CA0 250GB                     | 1         | 1      | 1.96%   |
| WDC WD2500AAKX-083CA1 250GB                     | 1         | 2      | 1.96%   |
| WDC WD20NPVX-00EA4T0 2TB                        | 1         | 2      | 1.96%   |
| WDC WD20EZRX-00D8PB0 2TB                        | 1         | 1      | 1.96%   |
| WDC WD20EURS-63S48Y0 2TB                        | 1         | 1      | 1.96%   |
| WDC WD20EARS-00MVWB0 2TB                        | 1         | 1      | 1.96%   |
| WDC WD1600BEVE-00UYT0 160GB                     | 1         | 1      | 1.96%   |
| WDC WD1600AAJS-40H3A0 160GB                     | 1         | 1      | 1.96%   |
| WDC WD1200BEVS-07LAT0 120GB                     | 1         | 1      | 1.96%   |
| WDC WD10EARS-003BB1 1TB                         | 1         | 1      | 1.96%   |
| Toshiba THNSNK512GVN8 512GB                     | 1         | 1      | 1.96%   |
| Toshiba MK3261GSYN 320GB                        | 1         | 1      | 1.96%   |
| Toshiba MK1252GSX 120GB                         | 1         | 1      | 1.96%   |
| SPCC Solid State Disk 256GB                     | 1         | 1      | 1.96%   |
| SK hynix SC308 SATA 256GB                       | 1         | 1      | 1.96%   |
| SK hynix SC210 mSATA 256GB                      | 1         | 1      | 1.96%   |
| Seagate ST9500420AS 500GB                       | 1         | 2      | 1.96%   |
| Seagate ST9160412AS 160GB                       | 1         | 1      | 1.96%   |
| Seagate ST500LM000-1EJ162 500GB                 | 1         | 1      | 1.96%   |
| Seagate ST500DM002-1BD142 500GB                 | 1         | 1      | 1.96%   |
| Seagate ST3250310AS 250GB                       | 1         | 1      | 1.96%   |
| Seagate ST32000542AS 2TB                        | 1         | 1      | 1.96%   |
| Seagate ST2000LM015-2E8174 2TB                  | 1         | 2      | 1.96%   |
| Seagate ST2000DL003-9VT166 2TB                  | 1         | 1      | 1.96%   |
| Seagate ST1000LM024 HN-M101MBB 1TB              | 1         | 1      | 1.96%   |
| SanDisk SSD U100 64GB                           | 1         | 4      | 1.96%   |
| Samsung Electronics SSD 870 EVO 1TB             | 1         | 1      | 1.96%   |
| Samsung Electronics SP2504C 250GB               | 1         | 1      | 1.96%   |
| Samsung Electronics HD154UI 1.5TB               | 1         | 1      | 1.96%   |
| Plextor PX-128G7Ne 128GB                        | 1         | 1      | 1.96%   |
| Micron Technology MTFDDAT128MAM-1J2 128GB       | 1         | 1      | 1.96%   |
| Micron Technology MTFDDAK256TBN-1AR1ZABHA 256GB | 1         | 1      | 1.96%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 15        | 18     | 30%     |
| Seagate             | 13        | 18     | 26%     |
| Toshiba             | 5         | 5      | 10%     |
| Samsung Electronics | 3         | 3      | 6%      |
| SK hynix            | 2         | 2      | 4%      |
| Micron Technology   | 2         | 2      | 4%      |
| Hitachi             | 2         | 2      | 4%      |
| Crucial             | 2         | 3      | 4%      |
| SPCC                | 1         | 1      | 2%      |
| SanDisk             | 1         | 4      | 2%      |
| Plextor             | 1         | 1      | 2%      |
| Kingston            | 1         | 1      | 2%      |
| Apacer              | 1         | 1      | 2%      |
| A-DATA Technology   | 1         | 1      | 2%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 15        | 18     | 41.67%  |
| Seagate             | 13        | 18     | 36.11%  |
| Toshiba             | 4         | 4      | 11.11%  |
| Samsung Electronics | 2         | 2      | 5.56%   |
| Hitachi             | 2         | 2      | 5.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 33        | 44     | 70.21%  |
| SSD  | 14        | 18     | 29.79%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD20EARS-00MVWB0 2TB        | 1         | 1      | 50%     |
| SanDisk SD9SN8W-256G-1006 256GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| SanDisk | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 262       | 542    | 81.37%  |
| Malfunc  | 46        | 62     | 14.29%  |
| Detected | 12        | 15     | 3.73%   |
| Failed   | 2         | 2      | 0.62%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 237       | 58.81%  |
| AMD                            | 58        | 14.39%  |
| Broadcom / LSI                 | 27        | 6.7%    |
| Samsung Electronics            | 20        | 4.96%   |
| SanDisk                        | 8         | 1.99%   |
| Silicon Motion                 | 6         | 1.49%   |
| SK hynix                       | 4         | 0.99%   |
| Hewlett-Packard                | 4         | 0.99%   |
| ASMedia Technology             | 4         | 0.99%   |
| ADATA Technology               | 4         | 0.99%   |
| Phison Electronics             | 3         | 0.74%   |
| Marvell Technology Group       | 3         | 0.74%   |
| JMicron Technology             | 3         | 0.74%   |
| VIA Technologies               | 2         | 0.5%    |
| Nvidia                         | 2         | 0.5%    |
| MAXIO Technology (Hangzhou)    | 2         | 0.5%    |
| KIOXIA                         | 2         | 0.5%    |
| Kingston Technology Company    | 2         | 0.5%    |
| Transcend                      | 1         | 0.25%   |
| Toshiba                        | 1         | 0.25%   |
| Solid State Storage Technology | 1         | 0.25%   |
| Shenzhen Longsys Electronics   | 1         | 0.25%   |
| Realtek Semiconductor          | 1         | 0.25%   |
| O2 Micro                       | 1         | 0.25%   |
| Micron/Crucial Technology      | 1         | 0.25%   |
| Lite-On Technology             | 1         | 0.25%   |
| Integrated Technology Express  | 1         | 0.25%   |
| Hosin Global Electronics       | 1         | 0.25%   |
| Biwin Storage Technology       | 1         | 0.25%   |
| Apple                          | 1         | 0.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 40        | 9.09%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 23        | 5.23%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 17        | 3.86%   |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                          | 16        | 3.64%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 14        | 3.18%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 13        | 2.95%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 12        | 2.73%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 12        | 2.73%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 12        | 2.73%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 9         | 2.05%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 9         | 2.05%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 9         | 2.05%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 9         | 2.05%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 8         | 1.82%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 7         | 1.59%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 7         | 1.59%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 7         | 1.59%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 6         | 1.36%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 6         | 1.36%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 6         | 1.36%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 5         | 1.14%   |
| Intel SATA Controller [RAID mode]                                                       | 5         | 1.14%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5         | 1.14%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5         | 1.14%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5         | 1.14%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5         | 1.14%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 4         | 0.91%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 4         | 0.91%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 3         | 0.68%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3         | 0.68%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 3         | 0.68%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 3         | 0.68%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3         | 0.68%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 3         | 0.68%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3         | 0.68%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 3         | 0.68%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3         | 0.68%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 3         | 0.68%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3         | 0.68%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3         | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 263       | 65.91%  |
| NVMe | 59        | 14.79%  |
| IDE  | 36        | 9.02%   |
| RAID | 35        | 8.77%   |
| SAS  | 4         | 1%      |
| SCSI | 2         | 0.5%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 267       | 78.3%   |
| AMD     | 65        | 19.06%  |
| ARM     | 7         | 2.05%   |
| VIA     | 1         | 0.29%   |
| PowerPC | 1         | 0.29%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz      | 13        | 3.78%   |
| AMD GX-420CA SOC with Radeon HD Graphics | 11        | 3.2%    |
| Intel Pentium Silver J5005 CPU @ 1.50GHz | 8         | 2.33%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz     | 7         | 2.03%   |
| AMD GX-415GA SOC with Radeon HD Graphics | 7         | 2.03%   |
| Intel Celeron CPU J1900 @ 1.99GHz        | 6         | 1.74%   |
| Intel Celeron N5105 @ 2.00GHz            | 5         | 1.45%   |
| Intel Celeron N4100 CPU @ 1.10GHz        | 5         | 1.45%   |
| Intel Celeron J4125 CPU @ 2.00GHz        | 5         | 1.45%   |
| Intel Core i5-6500 CPU @ 3.20GHz         | 4         | 1.16%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 4         | 1.16%   |
| Intel Core i3-8300T CPU @ 3.20GHz        | 4         | 1.16%   |
| Intel Core i3-6100 CPU @ 3.70GHz         | 4         | 1.16%   |
| Intel Celeron CPU J3455 @ 1.50GHz        | 4         | 1.16%   |
| AMD G-T56N Processor                     | 4         | 1.16%   |
| Intel Core i5-6300U CPU @ 2.40GHz        | 3         | 0.87%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 3         | 0.87%   |
| Intel Core i5-4570 CPU @ 3.20GHz         | 3         | 0.87%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 3         | 0.87%   |
| Intel Core i5-10210U CPU @ 1.60GHz       | 3         | 0.87%   |
| Intel Core 2 Duo                         | 3         | 0.87%   |
| Intel Celeron J4105 CPU @ 1.50GHz        | 3         | 0.87%   |
| Intel Celeron CPU N3150 @ 1.60GHz        | 3         | 0.87%   |
| Intel Atom CPU D2500 @ 1.86GHz           | 3         | 0.87%   |
| ARM Cortex-A72 r0p3                      | 3         | 0.87%   |
| ARM Cortex-A55 r2p0                      | 3         | 0.87%   |
| AMD RX-427BB with AMD Radeon R7 Graphics | 3         | 0.87%   |
| AMD Phenom II X4 965 Processor           | 3         | 0.87%   |
| AMD GX-412TC SOC                         | 3         | 0.87%   |
| Intel Xeon CPU X5660 @ 2.80GHz           | 2         | 0.58%   |
| Intel Xeon CPU X3430 @ 2.40GHz           | 2         | 0.58%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz      | 2         | 0.58%   |
| Intel Pentium CPU G860 @ 3.00GHz         | 2         | 0.58%   |
| Intel Pentium CPU G4600T @ 3.00GHz       | 2         | 0.58%   |
| Intel Pentium CPU G3220 @ 3.00GHz        | 2         | 0.58%   |
| Intel N100                               | 2         | 0.58%   |
| Intel Core i7-8700 CPU @ 3.20GHz         | 2         | 0.58%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 2         | 0.58%   |
| Intel Core i7-3720QM CPU @ 2.60GHz       | 2         | 0.58%   |
| Intel Core i5-8365U CPU @ 1.60GHz        | 2         | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 67        | 19.48%  |
| Intel Celeron           | 47        | 13.66%  |
| Intel Xeon              | 38        | 11.05%  |
| Intel Core i7           | 29        | 8.43%   |
| Intel Core i3           | 27        | 7.85%   |
| AMD GX                  | 23        | 6.69%   |
| Other                   | 15        | 4.36%   |
| Intel Core 2 Duo        | 14        | 4.07%   |
| Intel Pentium           | 12        | 3.49%   |
| Intel Pentium Silver    | 10        | 2.91%   |
| Intel Atom              | 8         | 2.33%   |
| ARM Cortex              | 7         | 2.03%   |
| AMD Ryzen 3             | 6         | 1.74%   |
| AMD G                   | 6         | 1.74%   |
| AMD Ryzen 7             | 4         | 1.16%   |
| AMD Ryzen 5             | 4         | 1.16%   |
| Intel Pentium Dual-Core | 3         | 0.87%   |
| AMD Ryzen 9             | 3         | 0.87%   |
| AMD Phenom II X4        | 3         | 0.87%   |
| Intel Core 2            | 2         | 0.58%   |
| AMD Ryzen 5 PRO         | 2         | 0.58%   |
| AMD E                   | 2         | 0.58%   |
| AMD Athlon              | 2         | 0.58%   |
| Intel Pentium M         | 1         | 0.29%   |
| Intel Genuine           | 1         | 0.29%   |
| Intel Core 2 Quad       | 1         | 0.29%   |
| Intel Celeron M         | 1         | 0.29%   |
| AMD Ryzen Embedded      | 1         | 0.29%   |
| AMD Ryzen 7 PRO         | 1         | 0.29%   |
| AMD Phenom II X6        | 1         | 0.29%   |
| AMD EPYC                | 1         | 0.29%   |
| AMD Athlon 64 X2        | 1         | 0.29%   |
| AMD A4                  | 1         | 0.29%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 156       | 45.35%  |
| 2       | 97        | 28.2%   |
| Unknown | 24        | 6.98%   |
| 16      | 17        | 4.94%   |
| 8       | 16        | 4.65%   |
| 12      | 12        | 3.49%   |
| 6       | 11        | 3.2%    |
| 1       | 6         | 1.74%   |
| 24      | 2         | 0.58%   |
| 20      | 2         | 0.58%   |
| 32      | 1         | 0.29%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 297       | 87.35%  |
| 2       | 27        | 7.94%   |
| Unknown | 16        | 4.71%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 187       | 54.52%  |
| 2       | 128       | 37.32%  |
| Unknown | 28        | 8.16%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 37        | 10.76%  |
| IvyBridge     | 36        | 10.47%  |
| Haswell       | 32        | 9.3%    |
| Unknown       | 28        | 8.14%   |
| Skylake       | 23        | 6.69%   |
| Goldmont plus | 23        | 6.69%   |
| SandyBridge   | 22        | 6.4%    |
| Penryn        | 22        | 6.4%    |
| Jaguar        | 21        | 6.1%    |
| Silvermont    | 13        | 3.78%   |
| Broadwell     | 9         | 2.62%   |
| Goldmont      | 8         | 2.33%   |
| Bobcat        | 8         | 2.33%   |
| Zen 2         | 7         | 2.03%   |
| Zen           | 7         | 2.03%   |
| Westmere      | 7         | 2.03%   |
| Nehalem       | 5         | 1.45%   |
| Bonnell       | 5         | 1.45%   |
| Zen 3         | 4         | 1.16%   |
| Puma          | 4         | 1.16%   |
| K10           | 4         | 1.16%   |
| Zen+          | 3         | 0.87%   |
| Steamroller   | 3         | 0.87%   |
| Core          | 3         | 0.87%   |
| CometLake     | 3         | 0.87%   |
| TigerLake     | 2         | 0.58%   |
| P6            | 2         | 0.58%   |
| NetBurst      | 1         | 0.29%   |
| K8 Hammer     | 1         | 0.29%   |
| Excavator     | 1         | 0.29%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 205       | 57.91%  |
| AMD                                          | 70        | 19.77%  |
| Nvidia                                       | 41        | 11.58%  |
| Matrox Electronics Systems                   | 30        | 8.47%   |
| ASPEED Technology                            | 5         | 1.41%   |
| VIA Technologies                             | 2         | 0.56%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.28%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Matrox Electronics Systems G200eR2                                                       | 18        | 5.04%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 14        | 3.92%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 14        | 3.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 13        | 3.64%   |
| Intel HD Graphics 530                                                                    | 13        | 3.64%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 12        | 3.36%   |
| AMD Kabini [Radeon HD 8400E]                                                             | 11        | 3.08%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 10        | 2.8%    |
| Intel GeminiLake [UHD Graphics 605]                                                      | 9         | 2.52%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 8         | 2.24%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 2.24%   |
| Intel JasperLake [UHD Graphics]                                                          | 7         | 1.96%   |
| AMD Kabini [Radeon HD 8330E]                                                             | 7         | 1.96%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 6         | 1.68%   |
| Intel HD Graphics 630                                                                    | 6         | 1.68%   |
| Intel HD Graphics 620                                                                    | 6         | 1.68%   |
| Intel HD Graphics 5500                                                                   | 6         | 1.68%   |
| Intel HD Graphics 500                                                                    | 6         | 1.68%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 1.68%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6         | 1.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 1.4%    |
| ASPEED Technology ASPEED Graphics Family                                                 | 5         | 1.4%    |
| AMD Wrestler [Radeon HD 6320]                                                            | 5         | 1.4%    |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 4         | 1.12%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 1.12%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 1.12%   |
| Intel HD Graphics 510                                                                    | 4         | 1.12%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 1.12%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4         | 1.12%   |
| AMD ES1000                                                                               | 4         | 1.12%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 0.84%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 0.84%   |
| Intel UHD Graphics 620                                                                   | 3         | 0.84%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 0.84%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 3         | 0.84%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3         | 0.84%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 0.84%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 3         | 0.84%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 0.84%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 3         | 0.84%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 168       | 48.84%  |
| 1 x AMD         | 64        | 18.6%   |
| 1 x Matrox      | 30        | 8.72%   |
| 1 x Nvidia      | 23        | 6.69%   |
| Intel + Nvidia  | 17        | 4.94%   |
| 2 x Intel       | 15        | 4.36%   |
| Other           | 13        | 3.78%   |
| Intel + AMD     | 5         | 1.45%   |
| 1 x ASPEED      | 3         | 0.87%   |
| 1 x VIA         | 2         | 0.58%   |
| 1 x XGI         | 1         | 0.29%   |
| Nvidia + ASPEED | 1         | 0.29%   |
| AMD + Nvidia    | 1         | 0.29%   |
| AMD + ASPEED    | 1         | 0.29%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 304       | 89.15%  |
| Proprietary | 19        | 5.57%   |
| Unknown     | 18        | 5.28%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 307       | 89.77%  |
| 1.01-2.0   | 9         | 2.63%   |
| 7.01-8.0   | 7         | 2.05%   |
| 3.01-4.0   | 7         | 2.05%   |
| 0.01-0.5   | 6         | 1.75%   |
| 0.51-1.0   | 4         | 1.17%   |
| 5.01-6.0   | 1         | 0.29%   |
| 8.01-16.0  | 1         | 0.29%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 16        | 13.45%  |
| Samsung Electronics     | 10        | 8.4%    |
| Lenovo                  | 10        | 8.4%    |
| BOE                     | 10        | 8.4%    |
| Iiyama                  | 9         | 7.56%   |
| AU Optronics            | 8         | 6.72%   |
| Dell                    | 6         | 5.04%   |
| Chimei Innolux          | 6         | 5.04%   |
| NEC Computers           | 5         | 4.2%    |
| Acer                    | 5         | 4.2%    |
| Philips                 | 4         | 3.36%   |
| Goldstar                | 3         | 2.52%   |
| BenQ                    | 3         | 2.52%   |
| AOC                     | 3         | 2.52%   |
| InfoVision              | 2         | 1.68%   |
| Idek Iiyama             | 2         | 1.68%   |
| Hewlett-Packard         | 2         | 1.68%   |
| Chi Mei Optoelectronics | 2         | 1.68%   |
| Apple                   | 2         | 1.68%   |
| Vestel Elektronik       | 1         | 0.84%   |
| Toshiba                 | 1         | 0.84%   |
| Sharp                   | 1         | 0.84%   |
| RTK                     | 1         | 0.84%   |
| PANDA                   | 1         | 0.84%   |
| KTC                     | 1         | 0.84%   |
| JDI                     | 1         | 0.84%   |
| HPN                     | 1         | 0.84%   |
| Eizo                    | 1         | 0.84%   |
| BOE Technology Group    | 1         | 0.84%   |
| Unknown                 | 1         | 0.84%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch                  | 6         | 5.04%   |
| Iiyama PL2775HD IVM6604 1920x1080 600x340mm 27.2-inch                    | 6         | 5.04%   |
| LG Display LCD Monitor LGD039F 1366x768 350x190mm 15.7-inch              | 2         | 1.68%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 2         | 1.68%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 2         | 1.68%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch       | 1         | 0.84%   |
| Toshiba TV TSB0110 1920x1080 1110x620mm 50.1-inch                        | 1         | 0.84%   |
| Sharp LCD Monitor SHP1451 1920x1080 280x160mm 12.7-inch                  | 1         | 0.84%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 700x390mm 31.5-inch        | 1         | 0.84%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 490x320mm 23.0-inch     | 1         | 0.84%   |
| Samsung Electronics LF27T370F SAM711E 1920x1080 600x340mm 27.2-inch      | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x170mm 13.9-inch     | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 300x190mm 14.0-inch     | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SEC3245 1280x800 330x210mm 15.4-inch     | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch     | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SDC4163 3456x2160 290x180mm 13.4-inch    | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch    | 1         | 0.84%   |
| Samsung Electronics LCD Monitor S24F350 1920x1080                        | 1         | 0.84%   |
| RTK FHD RTK0039 1920x1080 300x190mm 14.0-inch                            | 1         | 0.84%   |
| Philips PHL 275S1 PHL094B 2560x1440 600x340mm 27.2-inch                  | 1         | 0.84%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                  | 1         | 0.84%   |
| Philips LCD Monitor PHLC01A 1680x1050 470x300mm 22.0-inch                | 1         | 0.84%   |
| Philips 150S PHL0820 1024x768 300x230mm 14.9-inch                        | 1         | 0.84%   |
| PANDA LCD Monitor NCP006E 1920x1080 340x190mm 15.3-inch                  | 1         | 0.84%   |
| NEC Computers LCD4020 NEC66EA 1920x540 890x500mm 40.2-inch               | 1         | 0.84%   |
| NEC Computers LCD24WMCX NEC6720 1920x1200 520x320mm 24.0-inch            | 1         | 0.84%   |
| NEC Computers EA294WMi NEC68CF 2560x1080 670x280mm 28.6-inch             | 1         | 0.84%   |
| NEC Computers EA223WM NEC6891 1680x1050 470x300mm 22.0-inch              | 1         | 0.84%   |
| NEC Computers E438 NEC335C 3840x2160 940x530mm 42.5-inch                 | 1         | 0.84%   |
| LG Display LCD Monitor LGD0533 1920x1080 340x190mm 15.3-inch             | 1         | 0.84%   |
| LG Display LCD Monitor LGD04E2 1366x768 340x190mm 15.3-inch              | 1         | 0.84%   |
| LG Display LCD Monitor LGD0408 1920x1080 280x160mm 12.7-inch             | 1         | 0.84%   |
| LG Display LCD Monitor LGD03D3 1600x900 310x170mm 13.9-inch              | 1         | 0.84%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch              | 1         | 0.84%   |
| LG Display LCD Monitor LGD0368 1366x768 310x170mm 13.9-inch              | 1         | 0.84%   |
| LG Display LCD Monitor LGD033E 1366x768 310x170mm 13.9-inch              | 1         | 0.84%   |
| LG Display LCD Monitor LGD02F1 1366x768 340x190mm 15.3-inch              | 1         | 0.84%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 1         | 0.84%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 1         | 0.84%   |
| LG Display LCD Monitor LGD02AD 1366x768 340x190mm 15.3-inch              | 1         | 0.84%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 52        | 45.61%  |
| 1366x768 (WXGA)    | 25        | 21.93%  |
| 1280x800 (WXGA)    | 8         | 7.02%   |
| 3840x2160 (4K)     | 6         | 5.26%   |
| 1680x1050 (WSXGA+) | 4         | 3.51%   |
| 2560x1440 (QHD)    | 3         | 2.63%   |
| 1600x900 (HD+)     | 3         | 2.63%   |
| 1920x540           | 2         | 1.75%   |
| 1920x1200 (WUXGA)  | 2         | 1.75%   |
| 1440x900 (WXGA+)   | 2         | 1.75%   |
| Unknown            | 2         | 1.75%   |
| 5760x2160          | 1         | 0.88%   |
| 3456x2160          | 1         | 0.88%   |
| 2560x1080          | 1         | 0.88%   |
| 1280x1024 (SXGA)   | 1         | 0.88%   |
| 1024x768 (XGA)     | 1         | 0.88%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 24        | 20.87%  |
| 13      | 19        | 16.52%  |
| 12      | 15        | 13.04%  |
| 27      | 13        | 11.3%   |
| 24      | 7         | 6.09%   |
| 23      | 7         | 6.09%   |
| Unknown | 6         | 5.22%   |
| 21      | 5         | 4.35%   |
| 18      | 3         | 2.61%   |
| 14      | 3         | 2.61%   |
| 42      | 2         | 1.74%   |
| 31      | 2         | 1.74%   |
| 22      | 2         | 1.74%   |
| 17      | 2         | 1.74%   |
| 50      | 1         | 0.87%   |
| 40      | 1         | 0.87%   |
| 28      | 1         | 0.87%   |
| 20      | 1         | 0.87%   |
| 19      | 1         | 0.87%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 40        | 35.09%  |
| 501-600     | 26        | 22.81%  |
| 201-300     | 21        | 18.42%  |
| 401-500     | 12        | 10.53%  |
| Unknown     | 6         | 5.26%   |
| 601-700     | 3         | 2.63%   |
| 351-400     | 2         | 1.75%   |
| 901-1000    | 2         | 1.75%   |
| 801-900     | 1         | 0.88%   |
| 1001-1500   | 1         | 0.88%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 80        | 73.39%  |
| 16/10   | 18        | 16.51%  |
| Unknown | 6         | 5.5%    |
| 3/2     | 2         | 1.83%   |
| 5/4     | 1         | 0.92%   |
| 4/3     | 1         | 0.92%   |
| 21/9    | 1         | 0.92%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 19        | 16.67%  |
| 201-250        | 17        | 14.91%  |
| 91-100         | 17        | 14.91%  |
| 61-70          | 15        | 13.16%  |
| 301-350        | 13        | 11.4%   |
| 101-110        | 8         | 7.02%   |
| Unknown        | 6         | 5.26%   |
| 251-300        | 4         | 3.51%   |
| 151-200        | 3         | 2.63%   |
| 141-150        | 3         | 2.63%   |
| 501-1000       | 3         | 2.63%   |
| 71-80          | 2         | 1.75%   |
| 351-500        | 2         | 1.75%   |
| More than 1000 | 1         | 0.88%   |
| 121-130        | 1         | 0.88%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 40        | 35.71%  |
| 51-100        | 37        | 33.04%  |
| 101-120       | 21        | 18.75%  |
| Unknown       | 6         | 5.36%   |
| 161-240       | 5         | 4.46%   |
| 1-50          | 2         | 1.79%   |
| More than 240 | 1         | 0.89%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 219       | 64.04%  |
| 1     | 111       | 32.46%  |
| 2     | 11        | 3.22%   |
| 3     | 1         | 0.29%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 226       | 43.97%  |
| Realtek Semiconductor             | 153       | 29.77%  |
| Broadcom                          | 56        | 10.89%  |
| Qualcomm Atheros                  | 30        | 5.84%   |
| Qualcomm Atheros Communications   | 6         | 1.17%   |
| TP-Link                           | 4         | 0.78%   |
| Huawei Technologies               | 3         | 0.58%   |
| Emulex                            | 3         | 0.58%   |
| Dell                              | 3         | 0.58%   |
| Xiaomi                            | 2         | 0.39%   |
| Mellanox Technologies             | 2         | 0.39%   |
| Marvell Technology Group          | 2         | 0.39%   |
| AMD                               | 2         | 0.39%   |
| VIA Technologies                  | 1         | 0.19%   |
| Van Ooijen Technische Informatica | 1         | 0.19%   |
| U-Blox                            | 1         | 0.19%   |
| Sierra Wireless                   | 1         | 0.19%   |
| Seeed Technology                  | 1         | 0.19%   |
| Samsung Electronics               | 1         | 0.19%   |
| Ralink Technology                 | 1         | 0.19%   |
| Ralink                            | 1         | 0.19%   |
| QLogic                            | 1         | 0.19%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.19%   |
| Nvidia                            | 1         | 0.19%   |
| Nuvoton                           | 1         | 0.19%   |
| NetGear                           | 1         | 0.19%   |
| IMC Networks                      | 1         | 0.19%   |
| Ericsson Business Mobile Networks | 1         | 0.19%   |
| D-Link System                     | 1         | 0.19%   |
| Chelsio Communications            | 1         | 0.19%   |
| Atheros                           | 1         | 0.19%   |
| ASUSTek Computer                  | 1         | 0.19%   |
| Apple                             | 1         | 0.19%   |
| American Megatrends               | 1         | 0.19%   |
| 3Com                              | 1         | 0.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 135       | 21.5%   |
| Intel I211 Gigabit Network Connection                                         | 29        | 4.62%   |
| Intel I350 Gigabit Network Connection                                         | 21        | 3.34%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 20        | 3.18%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 19        | 3.03%   |
| Intel I210 Gigabit Network Connection                                         | 16        | 2.55%   |
| Intel Ethernet Connection I217-LM                                             | 11        | 1.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 11        | 1.75%   |
| Intel 82574L Gigabit Network Connection                                       | 11        | 1.75%   |
| Intel 82567LM Gigabit Network Connection                                      | 10        | 1.59%   |
| Intel Ethernet Controller I226-V                                              | 9         | 1.43%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 9         | 1.43%   |
| Intel Wireless 8265 / 8275                                                    | 8         | 1.27%   |
| Intel Ethernet Connection (7) I219-V                                          | 8         | 1.27%   |
| Intel Ethernet Connection (2) I219-V                                          | 8         | 1.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 7         | 1.11%   |
| Intel Wireless 8260                                                           | 7         | 1.11%   |
| Intel Ethernet Controller I225-V                                              | 7         | 1.11%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 7         | 1.11%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 7         | 1.11%   |
| Intel Ultimate N WiFi Link 5300                                               | 6         | 0.96%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 6         | 0.96%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 5         | 0.8%    |
| Intel Wireless 7265                                                           | 5         | 0.8%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 5         | 0.8%    |
| Broadcom BCM43228 802.11a/b/g/n                                               | 5         | 0.8%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 4         | 0.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 4         | 0.64%   |
| Qualcomm Atheros AR9271 802.11n                                               | 4         | 0.64%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 4         | 0.64%   |
| Intel Wireless 3165                                                           | 4         | 0.64%   |
| Intel Wi-Fi 6 AX200                                                           | 4         | 0.64%   |
| Intel Ethernet Connection I219-LM                                             | 4         | 0.64%   |
| Intel 82580 Gigabit Network Connection                                        | 4         | 0.64%   |
| Intel 82576 Gigabit Network Connection                                        | 4         | 0.64%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 4         | 0.64%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 4         | 0.64%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 3         | 0.48%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 3         | 0.48%   |
| Intel Wireless 7260                                                           | 3         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 93        | 55.36%  |
| Qualcomm Atheros                | 26        | 15.48%  |
| Realtek Semiconductor           | 17        | 10.12%  |
| Broadcom                        | 13        | 7.74%   |
| Qualcomm Atheros Communications | 6         | 3.57%   |
| TP-Link                         | 4         | 2.38%   |
| Dell                            | 2         | 1.19%   |
| Ralink Technology               | 1         | 0.6%    |
| Ralink                          | 1         | 0.6%    |
| NetGear                         | 1         | 0.6%    |
| IMC Networks                    | 1         | 0.6%    |
| D-Link System                   | 1         | 0.6%    |
| Atheros                         | 1         | 0.6%    |
| ASUSTek Computer                | 1         | 0.6%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 11        | 6.55%   |
| Intel Wireless 8265 / 8275                                                    | 8         | 4.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 7         | 4.17%   |
| Intel Wireless 8260                                                           | 7         | 4.17%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 7         | 4.17%   |
| Intel Ultimate N WiFi Link 5300                                               | 6         | 3.57%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 6         | 3.57%   |
| Intel Wireless 7265                                                           | 5         | 2.98%   |
| Broadcom BCM43228 802.11a/b/g/n                                               | 5         | 2.98%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 4         | 2.38%   |
| Qualcomm Atheros AR9271 802.11n                                               | 4         | 2.38%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 4         | 2.38%   |
| Intel Wireless 3165                                                           | 4         | 2.38%   |
| Intel Wi-Fi 6 AX200                                                           | 4         | 2.38%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 3         | 1.79%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 3         | 1.79%   |
| Intel Wireless 7260                                                           | 3         | 1.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 3         | 1.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 3         | 1.79%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 2         | 1.19%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 2         | 1.19%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 1.19%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 2         | 1.19%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 1.19%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 2         | 1.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2         | 1.19%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 2         | 1.19%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 1.19%   |
| Intel Wi-Fi 6 AX201                                                           | 2         | 1.19%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                       | 2         | 1.19%   |
| Intel Centrino Advanced-N 6235                                                | 2         | 1.19%   |
| Intel Centrino Advanced-N 6200                                                | 2         | 1.19%   |
| Broadcom BCM43142 802.11b/g/n                                                 | 2         | 1.19%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                           | 1         | 0.6%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1         | 0.6%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                   | 1         | 0.6%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 0.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.6%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1         | 0.6%    |
| Realtek RTL8187SE Wireless LAN Controller                                     | 1         | 0.6%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 188       | 47.36%  |
| Realtek Semiconductor         | 143       | 36.02%  |
| Broadcom                      | 44        | 11.08%  |
| Qualcomm Atheros              | 5         | 1.26%   |
| Xiaomi                        | 2         | 0.5%    |
| Marvell Technology Group      | 2         | 0.5%    |
| Emulex                        | 2         | 0.5%    |
| AMD                           | 2         | 0.5%    |
| VIA Technologies              | 1         | 0.25%   |
| Samsung Electronics           | 1         | 0.25%   |
| QLogic                        | 1         | 0.25%   |
| OnePlus Technology (Shenzhen) | 1         | 0.25%   |
| Nvidia                        | 1         | 0.25%   |
| Huawei Technologies           | 1         | 0.25%   |
| Apple                         | 1         | 0.25%   |
| American Megatrends           | 1         | 0.25%   |
| 3Com                          | 1         | 0.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 135       | 30.34%  |
| Intel I211 Gigabit Network Connection                                         | 29        | 6.52%   |
| Intel I350 Gigabit Network Connection                                         | 21        | 4.72%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 20        | 4.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 19        | 4.27%   |
| Intel I210 Gigabit Network Connection                                         | 16        | 3.6%    |
| Intel Ethernet Connection I217-LM                                             | 11        | 2.47%   |
| Intel 82574L Gigabit Network Connection                                       | 11        | 2.47%   |
| Intel 82567LM Gigabit Network Connection                                      | 10        | 2.25%   |
| Intel Ethernet Controller I226-V                                              | 9         | 2.02%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 9         | 2.02%   |
| Intel Ethernet Connection (7) I219-V                                          | 8         | 1.8%    |
| Intel Ethernet Connection (2) I219-V                                          | 8         | 1.8%    |
| Intel Ethernet Controller I225-V                                              | 7         | 1.57%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 7         | 1.57%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 5         | 1.12%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 5         | 1.12%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 4         | 0.9%    |
| Intel Ethernet Connection I219-LM                                             | 4         | 0.9%    |
| Intel 82580 Gigabit Network Connection                                        | 4         | 0.9%    |
| Intel 82576 Gigabit Network Connection                                        | 4         | 0.9%    |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 4         | 0.9%    |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 4         | 0.9%    |
| Intel Ethernet Connection I218-LM                                             | 3         | 0.67%   |
| Intel Ethernet Connection (3) I218-LM                                         | 3         | 0.67%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 3         | 0.67%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                               | 3         | 0.67%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 2         | 0.45%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 2         | 0.45%   |
| Intel Ethernet Controller X550                                                | 2         | 0.45%   |
| Intel Ethernet Connection (5) I219-LM                                         | 2         | 0.45%   |
| Intel Ethernet Connection (4) I219-LM                                         | 2         | 0.45%   |
| Intel Ethernet Connection (10) I219-V                                         | 2         | 0.45%   |
| Intel 82583V Gigabit Network Connection                                       | 2         | 0.45%   |
| Intel 82577LM Gigabit Network Connection                                      | 2         | 0.45%   |
| Intel 82576NS Gigabit Network Connection                                      | 2         | 0.45%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 2         | 0.45%   |
| Emulex OneConnect 10Gb NIC (be3)                                              | 2         | 0.45%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 2         | 0.45%   |
| AMD XGMAC 10GbE Controller                                                    | 2         | 0.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 321       | 65.24%  |
| WiFi     | 156       | 31.71%  |
| Unknown  | 9         | 1.83%   |
| Modem    | 6         | 1.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 281       | 78.27%  |
| WiFi     | 78        | 21.73%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 120       | 34.58%  |
| 1     | 65        | 18.73%  |
| 3     | 58        | 16.71%  |
| 4     | 48        | 13.83%  |
| 6     | 22        | 6.34%   |
| 5     | 22        | 6.34%   |
| 0     | 8         | 2.31%   |
| 14    | 1         | 0.29%   |
| 10    | 1         | 0.29%   |
| 8     | 1         | 0.29%   |
| 7     | 1         | 0.29%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 337       | 98.25%  |
| Yes  | 6         | 1.75%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 57        | 60%     |
| Broadcom                        | 9         | 9.47%   |
| Realtek Semiconductor           | 5         | 5.26%   |
| IMC Networks                    | 4         | 4.21%   |
| Qualcomm Atheros Communications | 3         | 3.16%   |
| Foxconn / Hon Hai               | 3         | 3.16%   |
| Cambridge Silicon Radio         | 3         | 3.16%   |
| ASUSTek Computer                | 3         | 3.16%   |
| Dell                            | 2         | 2.11%   |
| Apple                           | 2         | 2.11%   |
| TP-Link                         | 1         | 1.05%   |
| Qcom                            | 1         | 1.05%   |
| Lite-On Technology              | 1         | 1.05%   |
| Hewlett-Packard                 | 1         | 1.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                       | 22        | 23.16%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 14        | 14.74%  |
| Intel AX201 Bluetooth                                    | 8         | 8.42%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]       | 5         | 5.26%   |
| Intel Wireless-AC 3168 Bluetooth                         | 3         | 3.16%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 3         | 3.16%   |
| Intel AX200 Bluetooth                                    | 3         | 3.16%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 3         | 3.16%   |
| Realtek Bluetooth Adapter                                | 2         | 2.11%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter         | 2         | 2.11%   |
| TP-Link Bluetooth 5.0 USB Adapter                        | 1         | 1.05%   |
| Realtek Wireless Bluetooth Adapter                       | 1         | 1.05%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                  | 1         | 1.05%   |
| Realtek Bluetooth 4.2 Adapter                            | 1         | 1.05%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                   | 1         | 1.05%   |
| Qualcomm Atheros Dell Wireless 1601 Bluetooth Device     | 1         | 1.05%   |
| Qualcomm Atheros AR9462 Bluetooth                        | 1         | 1.05%   |
| Qcom Broadcom BCM2070 Bluetooth 2.1+EDR USB Device       | 1         | 1.05%   |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS              | 1         | 1.05%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 1         | 1.05%   |
| Intel AX210 Bluetooth                                    | 1         | 1.05%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip     | 1         | 1.05%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS         | 1         | 1.05%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter        | 1         | 1.05%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011]   | 1         | 1.05%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter               | 1         | 1.05%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device | 1         | 1.05%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth            | 1         | 1.05%   |
| Foxconn / Hon Hai Bluetooth USB Module                   | 1         | 1.05%   |
| Dell DW375 Bluetooth Module                              | 1         | 1.05%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module              | 1         | 1.05%   |
| Broadcom BCM43142A0 Bluetooth Module                     | 1         | 1.05%   |
| Broadcom BCM43142A0 Bluetooth 4.0                        | 1         | 1.05%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]               | 1         | 1.05%   |
| Broadcom BCM2045B (BDC-2.1)                              | 1         | 1.05%   |
| ASUS USB-BT500                                           | 1         | 1.05%   |
| ASUS BT-253 Bluetooth Adapter                            | 1         | 1.05%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 1         | 1.05%   |
| Apple Broadcom Built-in Bluetooth                        | 1         | 1.05%   |
| Apple Bluetooth Host Controller                          | 1         | 1.05%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 207       | 66.99%  |
| AMD                   | 64        | 20.71%  |
| Nvidia                | 24        | 7.77%   |
| C-Media Electronics   | 4         | 1.29%   |
| VIA Technologies      | 2         | 0.65%   |
| Logitech              | 2         | 0.65%   |
| Creative Labs         | 2         | 0.65%   |
| ROCCAT                | 1         | 0.32%   |
| Realtek Semiconductor | 1         | 0.32%   |
| Kingston Technology   | 1         | 0.32%   |
| Creative Technology   | 1         | 0.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Kabini HDMI/DP Audio                                                                          | 22        | 5.74%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 20        | 5.22%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 20        | 5.22%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 17        | 4.44%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 17        | 4.44%   |
| AMD FCH Azalia Controller                                                                         | 16        | 4.18%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 15        | 3.92%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 15        | 3.92%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 14        | 3.66%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 13        | 3.39%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 13        | 3.39%   |
| Intel Cannon Lake PCH cAVS                                                                        | 11        | 2.87%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 9         | 2.35%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 8         | 2.09%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 2.09%   |
| Intel Jasper Lake HD Audio                                                                        | 7         | 1.83%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 1.83%   |
| Intel 200 Series PCH HD Audio                                                                     | 7         | 1.83%   |
| AMD Wrestler HDMI Audio                                                                           | 7         | 1.83%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 7         | 1.83%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 1.57%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 1.57%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 6         | 1.57%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 5         | 1.31%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 1.31%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 1.31%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 5         | 1.31%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 5         | 1.31%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 1.04%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 1.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1.04%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 1.04%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 4         | 1.04%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 0.78%   |
| AMD Navi 10 HDMI Audio                                                                            | 3         | 0.78%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 3         | 0.78%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 2         | 0.52%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 0.52%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.52%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 82        | 23.36%  |
| SK hynix            | 57        | 16.24%  |
| Kingston            | 50        | 14.25%  |
| Unknown             | 33        | 9.4%    |
| Micron Technology   | 26        | 7.41%   |
| GOODRAM             | 21        | 5.98%   |
| Crucial             | 14        | 3.99%   |
| G.Skill             | 10        | 2.85%   |
| Corsair             | 8         | 2.28%   |
| Unknown             | 8         | 2.28%   |
| Ramaxel Technology  | 6         | 1.71%   |
| Toshiba             | 5         | 1.42%   |
| Patriot             | 4         | 1.14%   |
| Nanya Technology    | 4         | 1.14%   |
| Wilk                | 3         | 0.85%   |
| Transcend           | 2         | 0.57%   |
| Lexar Co Limited    | 2         | 0.57%   |
| Hewlett-Packard     | 2         | 0.57%   |
| A-DATA Technology   | 2         | 0.57%   |
| Unknown (ABCD)      | 1         | 0.28%   |
| Unknown (07FB)      | 1         | 0.28%   |
| Team                | 1         | 0.28%   |
| Qimonda             | 1         | 0.28%   |
| PUSKILL             | 1         | 0.28%   |
| Kimtigo             | 1         | 0.28%   |
| Innodisk            | 1         | 0.28%   |
| GeIL                | 1         | 0.28%   |
| Elpida              | 1         | 0.28%   |
| ATP                 | 1         | 0.28%   |
| Apacer              | 1         | 0.28%   |
| A-DA                | 1         | 0.28%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Samsung RAM M393B1G70QH0-YK0 8192MB DIMM DDR3 1600MT/s    | 15        | 4.01%   |
| Unknown                                                   | 8         | 2.14%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s     | 6         | 1.6%    |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s         | 5         | 1.34%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                      | 4         | 1.07%   |
| Toshiba RAM KKN2NM-MIE 4GB SODIMM DDR4 2666MT/s           | 4         | 1.07%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 4         | 1.07%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s    | 4         | 1.07%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 4         | 1.07%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s     | 4         | 1.07%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                 | 3         | 0.8%    |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s      | 3         | 0.8%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 3         | 0.8%    |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s      | 3         | 0.8%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s    | 3         | 0.8%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 3         | 0.8%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s     | 3         | 0.8%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s     | 3         | 0.8%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s     | 3         | 0.8%    |
| GOODRAM RAM GR1600S364L11/8G 8GB SODIMM DDR3 1600MT/s     | 3         | 0.8%    |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                 | 2         | 0.53%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                 | 2         | 0.53%   |
| Unknown RAM Module 2GB DIMM 800MT/s                       | 2         | 0.53%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 2         | 0.53%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 2         | 0.53%   |
| SK hynix RAM HMT351R7BFR8A-H9 4GB DIMM DDR3 1333MT/s      | 2         | 0.53%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s    | 2         | 0.53%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s    | 2         | 0.53%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s     | 2         | 0.53%   |
| Samsung RAM M471B5674EB0-YK0 2GB SODIMM DDR3 1600MT/s     | 2         | 0.53%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s     | 2         | 0.53%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s     | 2         | 0.53%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s     | 2         | 0.53%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 2         | 0.53%   |
| Samsung RAM M471B1G73BH0-CK0 8GB SODIMM DDR3 1600MT/s     | 2         | 0.53%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s | 2         | 0.53%   |
| Patriot RAM 1600 CL9 Series 8GB DIMM DDR3 1600MT/s        | 2         | 0.53%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                | 2         | 0.53%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s     | 2         | 0.53%   |
| Micron RAM 16ATF2G64HZ-2G3H1 16GB SODIMM DDR4 2400MT/s    | 2         | 0.53%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 165       | 53.05%  |
| DDR4    | 114       | 36.66%  |
| DDR2    | 8         | 2.57%   |
| Unknown | 8         | 2.57%   |
| LPDDR4  | 4         | 1.29%   |
| SDRAM   | 3         | 0.96%   |
| LPDDR3  | 3         | 0.96%   |
| DDR5    | 3         | 0.96%   |
| DDR     | 2         | 0.64%   |
| DRAM    | 1         | 0.32%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 158       | 50.97%  |
| DIMM         | 143       | 46.13%  |
| Row Of Chips | 5         | 1.61%   |
| Unknown      | 2         | 0.65%   |
| RIMM         | 1         | 0.32%   |
| FB-DIMM      | 1         | 0.32%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 130       | 38.92%  |
| 4096  | 112       | 33.53%  |
| 2048  | 51        | 15.27%  |
| 16384 | 28        | 8.38%   |
| 1024  | 9         | 2.69%   |
| 32768 | 2         | 0.6%    |
| 512   | 2         | 0.6%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 107       | 32.52%  |
| 2400    | 44        | 13.37%  |
| 1333    | 37        | 11.25%  |
| 2667    | 26        | 7.9%    |
| 3200    | 25        | 7.6%    |
| 2133    | 17        | 5.17%   |
| 800     | 13        | 3.95%   |
| 2666    | 7         | 2.13%   |
| 1867    | 7         | 2.13%   |
| 1334    | 7         | 2.13%   |
| 1067    | 7         | 2.13%   |
| 667     | 7         | 2.13%   |
| 1066    | 5         | 1.52%   |
| Unknown | 5         | 1.52%   |
| 1866    | 4         | 1.22%   |
| 4800    | 2         | 0.61%   |
| 5200    | 1         | 0.3%    |
| 4267    | 1         | 0.3%    |
| 3600    | 1         | 0.3%    |
| 3333    | 1         | 0.3%    |
| 3000    | 1         | 0.3%    |
| 2933    | 1         | 0.3%    |
| 2048    | 1         | 0.3%    |
| 533     | 1         | 0.3%    |
| 400     | 1         | 0.3%    |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 27        | 41.54%  |
| Microdia                               | 9         | 13.85%  |
| Realtek Semiconductor                  | 5         | 7.69%   |
| Bison Electronics                      | 5         | 7.69%   |
| IMC Networks                           | 3         | 4.62%   |
| Sunplus Innovation Technology          | 2         | 3.08%   |
| Ricoh                                  | 2         | 3.08%   |
| Logitech                               | 2         | 3.08%   |
| Lite-On Technology                     | 2         | 3.08%   |
| Syntek                                 | 1         | 1.54%   |
| Suyin                                  | 1         | 1.54%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 1.54%   |
| Luxvisions Innotech Limited            | 1         | 1.54%   |
| Hewlett-Packard                        | 1         | 1.54%   |
| DigiTech                               | 1         | 1.54%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.54%   |
| Apple                                  | 1         | 1.54%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                     | 6         | 9.23%   |
| Chicony Realtek DMFT RGB                                      | 4         | 6.15%   |
| Realtek Lenovo EasyCamera                                     | 3         | 4.62%   |
| Microdia Integrated Webcam                                    | 3         | 4.62%   |
| Microdia Integrated_Webcam_HD                                 | 2         | 3.08%   |
| Logitech HD Pro Webcam C920                                   | 2         | 3.08%   |
| Lite-On Integrated Camera                                     | 2         | 3.08%   |
| IMC Networks Integrated Camera                                | 2         | 3.08%   |
| Chicony Integrated Camera [ThinkPad]                          | 2         | 3.08%   |
| Chicony Integrated Camera (1280x720@30)                       | 2         | 3.08%   |
| Bison Integrated Camera                                       | 2         | 3.08%   |
| Syntek Lenovo EasyCamera                                      | 1         | 1.54%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                      | 1         | 1.54%   |
| Sunplus Integrated_Webcam_HD                                  | 1         | 1.54%   |
| Sunplus Integrated_Webcam_FHD                                 | 1         | 1.54%   |
| Shenzhen Kingcome Optoelectronic NexiGo HelloCam N930W Camera | 1         | 1.54%   |
| Ricoh Integrated Webcam                                       | 1         | 1.54%   |
| Ricoh HD Webcam                                               | 1         | 1.54%   |
| Realtek Integrated_Webcam_HD                                  | 1         | 1.54%   |
| Realtek HD WebCam                                             | 1         | 1.54%   |
| Microdia USB 2.0 Camera                                       | 1         | 1.54%   |
| Microdia Laptop_Integrated_Webcam_HD                          | 1         | 1.54%   |
| Microdia Integrated HD Webcam                                 | 1         | 1.54%   |
| Microdia Dell Integrated HD Webcam                            | 1         | 1.54%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera           | 1         | 1.54%   |
| IMC Networks EasyCamera                                       | 1         | 1.54%   |
| HP Premium Starter Webcam                                     | 1         | 1.54%   |
| DigiTech WebCam SCB-0350M                                     | 1         | 1.54%   |
| Chicony USB2.0 VGA UVC WebCam                                 | 1         | 1.54%   |
| Chicony ThinkPad T490 Webcam                                  | 1         | 1.54%   |
| Chicony Lenovo Integrated Camera (0.3MP)                      | 1         | 1.54%   |
| Chicony HP Wide Vision HD Camera                              | 1         | 1.54%   |
| Chicony HP Integrated Webcam                                  | 1         | 1.54%   |
| Chicony HP HD Webcam [Fixed]                                  | 1         | 1.54%   |
| Chicony HP HD Webcam                                          | 1         | 1.54%   |
| Chicony HP HD Camera                                          | 1         | 1.54%   |
| Chicony HD WebCam                                             | 1         | 1.54%   |
| Chicony Front Camera                                          | 1         | 1.54%   |
| Chicony FJ Camera                                             | 1         | 1.54%   |
| Chicony 1.3M Webcam                                           | 1         | 1.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 6         | 31.58%  |
| AuthenTec                  | 4         | 21.05%  |
| Validity Sensors           | 3         | 15.79%  |
| Broadcom                   | 3         | 15.79%  |
| STMicroelectronics         | 1         | 5.26%   |
| Shenzhen Goodix Technology | 1         | 5.26%   |
| Elan Microelectronics      | 1         | 5.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 4         | 21.05%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 15.79%  |
| AuthenTec AES2810                                                            | 3         | 15.79%  |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 2         | 10.53%  |
| Validity Sensors Fingerprint scanner                                         | 1         | 5.26%   |
| Synaptics WBDI                                                               | 1         | 5.26%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 1         | 5.26%   |
| STMicroelectronics Fingerprint Reader                                        | 1         | 5.26%   |
| Shenzhen Goodix Fingerprint Reader                                           | 1         | 5.26%   |
| Elan Fingerprint Sensor                                                      | 1         | 5.26%   |
| AuthenTec AES2660                                                            | 1         | 5.26%   |

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
| 1     | 149       | 43.19%  |
| 0     | 99        | 28.7%   |
| 2     | 69        | 20%     |
| 3     | 18        | 5.22%   |
| 4     | 6         | 1.74%   |
| 5     | 3         | 0.87%   |
| 6     | 1         | 0.29%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 213       | 62.46%  |
| Bluetooth                | 33        | 9.68%   |
| Net/wireless             | 29        | 8.5%    |
| Fingerprint reader       | 18        | 5.28%   |
| Card reader              | 18        | 5.28%   |
| Graphics card            | 10        | 2.93%   |
| Firewire controller      | 7         | 2.05%   |
| Network                  | 5         | 1.47%   |
| Net/ethernet             | 3         | 0.88%   |
| Sound                    | 2         | 0.59%   |
| Storage/nvme             | 1         | 0.29%   |
| Storage                  | 1         | 0.29%   |
| Modem                    | 1         | 0.29%   |

