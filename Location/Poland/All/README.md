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

Total: 452

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
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
| ASRockRack    | X570D4I-2T                  | Desktop     | [9f06290060](https://bsd-hardware.info/?probe=9f06290060) | Jan 17, 2022 |
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

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| helloSystem 0.8.1    | 20        | 5.26%   |
| helloSystem 0.7.0    | 15        | 3.95%   |
| OpenBSD 7.0          | 12        | 3.16%   |
| FreeBSD 12.1-p10     | 12        | 3.16%   |
| OPNsense 22.7.10     | 9         | 2.37%   |
| FreeBSD 14.0-CURRENT | 9         | 2.37%   |
| FreeBSD 13.1-p8      | 9         | 2.37%   |
| OPNsense 23.1.7      | 7         | 1.84%   |
| OPNsense 23.1.11     | 7         | 1.84%   |
| OPNsense 23.1.1      | 7         | 1.84%   |
| FreeBSD 13.2         | 7         | 1.84%   |
| OPNsense 23.1        | 6         | 1.58%   |
| OpenBSD 7.1          | 6         | 1.58%   |
| helloSystem 0.6.0    | 6         | 1.58%   |
| FreeBSD 12.2         | 6         | 1.58%   |
| OPNsense 23.1.5      | 5         | 1.32%   |
| OPNsense 22.1        | 5         | 1.32%   |
| OPNsense 21.7.3      | 5         | 1.32%   |
| OPNsense 21.1.6      | 5         | 1.32%   |
| helloSystem 0.8.0    | 5         | 1.32%   |
| helloSystem 0.5.0    | 5         | 1.32%   |
| FreeBSD 13.0-p5      | 5         | 1.32%   |
| OPNsense 23.7.5      | 4         | 1.05%   |
| OPNsense 23.7.4      | 4         | 1.05%   |
| OPNsense 23.1.9      | 4         | 1.05%   |
| OPNsense 23.1.8      | 4         | 1.05%   |
| OPNsense 22.7.4      | 4         | 1.05%   |
| OPNsense 22.7.2      | 4         | 1.05%   |
| OPNsense 22.7.11     | 4         | 1.05%   |
| OPNsense 22.7        | 4         | 1.05%   |
| OPNsense 22.1.8      | 4         | 1.05%   |
| OPNsense 22.1.10     | 4         | 1.05%   |
| OPNsense 21.7.7      | 4         | 1.05%   |
| OPNsense 21.1.2      | 4         | 1.05%   |
| OPNsense 21.1.1      | 4         | 1.05%   |
| OPNsense 21.1        | 4         | 1.05%   |
| GhostBSD 20.04.02    | 4         | 1.05%   |
| FreeBSD 13.1-p2      | 4         | 1.05%   |
| FreeBSD 13.0-p4      | 4         | 1.05%   |
| FreeBSD 12.3-p2      | 4         | 1.05%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 134       | 43.51%  |
| FreeBSD     | 88        | 28.57%  |
| helloSystem | 51        | 16.56%  |
| OpenBSD     | 23        | 7.47%   |
| GhostBSD    | 7         | 2.27%   |
| XigmaNAS    | 2         | 0.65%   |
| NomadBSD    | 2         | 0.65%   |
| NetBSD      | 1         | 0.32%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| amd64  | 299       | 97.08%  |
| arm64  | 4         | 1.3%    |
| i386   | 3         | 0.97%   |
| macppc | 1         | 0.32%   |
| armv7  | 1         | 0.32%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 179       | 57.37%  |
| helloDesktop  | 57        | 18.27%  |
| fvwm          | 16        | 5.13%   |
| GNOME         | 15        | 4.81%   |
| XFCE          | 13        | 4.17%   |
| KDE5          | 9         | 2.88%   |
| MATE          | 8         | 2.56%   |
| Openbox       | 5         | 1.6%    |
| TWM           | 4         | 1.28%   |
| i3            | 4         | 1.28%   |
| xfwm          | 1         | 0.32%   |
| Enlightenment | 1         | 0.32%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 190       | 61.49%  |
| X11     | 119       | 38.51%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 213       | 68.93%  |
| SLiM    | 61        | 19.74%  |
| SDDM    | 10        | 3.24%   |
| LightDM | 9         | 2.91%   |
| GDM     | 9         | 2.91%   |
| XDM     | 7         | 2.27%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang           | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 184       | 58.79%  |
| en_US          | 48        | 15.34%  |
| C              | 43        | 13.74%  |
| pl_PL          | 25        | 7.99%   |
| fr_FR          | 8         | 2.56%   |
| pl             | 2         | 0.64%   |
| en_IE.US-ASCII | 1         | 0.32%   |
| en_GB          | 1         | 0.32%   |
| en             | 1         | 0.32%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 257       | 83.17%  |
| BIOS | 52        | 16.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Zfs    | 146       | 46.79%  |
| Ufs    | 122       | 39.1%   |
| Ffs    | 23        | 7.37%   |
| Cd9660 | 21        | 6.73%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 278       | 90.26%  |
| MBR     | 27        | 8.77%   |
| Unknown | 3         | 0.97%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Dell                       | 64        | 20.78%  |
| Lenovo                     | 38        | 12.34%  |
| Hewlett-Packard            | 28        | 9.09%   |
| Gigabyte Technology        | 22        | 7.14%   |
| ASUSTek Computer           | 22        | 7.14%   |
| Unknown                    | 20        | 6.49%   |
| Intel                      | 16        | 5.19%   |
| ASRock                     | 13        | 4.22%   |
| MSI                        | 12        | 3.9%    |
| Fujitsu                    | 10        | 3.25%   |
| Supermicro                 | 8         | 2.6%    |
| ZOTAC                      | 5         | 1.62%   |
| Acer                       | 5         | 1.62%   |
| Techvision                 | 4         | 1.3%    |
| PC Engines                 | 4         | 1.3%    |
| Shuttle                    | 3         | 0.97%   |
| Apple                      | 3         | 0.97%   |
| Inventec                   | 2         | 0.65%   |
| Google                     | 2         | 0.65%   |
| Deciso                     | 2         | 0.65%   |
| ASRockRack                 | 2         | 0.65%   |
| AMI                        | 2         | 0.65%   |
| Wistron                    | 1         | 0.32%   |
| Toshiba                    | 1         | 0.32%   |
| Sony                       | 1         | 0.32%   |
| ShenZhen MinWin Technology | 1         | 0.32%   |
| Seeed Studio               | 1         | 0.32%   |
| Samsung Electronics        | 1         | 0.32%   |
| Raspberry Pi Foundation    | 1         | 0.32%   |
| PC Specialist              | 1         | 0.32%   |
| Panasonic                  | 1         | 0.32%   |
| Packard Bell               | 1         | 0.32%   |
| NU591R                     | 1         | 0.32%   |
| Notebook                   | 1         | 0.32%   |
| Medion                     | 1         | 0.32%   |
| IGEL Technology            | 1         | 0.32%   |
| iEi                        | 1         | 0.32%   |
| IBM                        | 1         | 0.32%   |
| Fujitsu Siemens            | 1         | 0.32%   |
| Essentiel B                | 1         | 0.32%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 21        | 6.82%   |
| Dell OEM-R 720xd                    | 13        | 4.22%   |
| HP t620 PLUS Quad Core TC           | 9         | 2.92%   |
| Lenovo ThinkPad X200 745969G        | 5         | 1.62%   |
| Gigabyte B360N WIFI                 | 5         | 1.62%   |
| Fujitsu FUTRO S920                  | 5         | 1.62%   |
| Techvision TVI7309X                 | 4         | 1.3%    |
| Dell Wyse 5070 Thin Client          | 4         | 1.3%    |
| Dell Wyse 5070 Extended Thin Client | 4         | 1.3%    |
| ZOTAC ZBOX-CI329NANO                | 3         | 0.97%   |
| ASUS All Series                     | 3         | 0.97%   |
| ASRock Q1900B-ITX                   | 3         | 0.97%   |
| Intel SHARKBAY                      | 2         | 0.65%   |
| Intel Q3XXG4-P V1.0                 | 2         | 0.65%   |
| Intel D2500CC AAG81477-401          | 2         | 0.65%   |
| Intel Appliance B4                  | 2         | 0.65%   |
| HP ProLiant DL360 G7                | 2         | 0.65%   |
| Gigabyte H270N-WIFI                 | 2         | 0.65%   |
| Gigabyte H110TN                     | 2         | 0.65%   |
| Dell OptiPlex 7050                  | 2         | 0.65%   |
| Dell OptiPlex 3020                  | 2         | 0.65%   |
| Dell Latitude E6430                 | 2         | 0.65%   |
| ASRock J3455B-ITX                   | 2         | 0.65%   |
| ZOTAC ZBOX-CI341                    | 1         | 0.32%   |
| ZOTAC ZBOX-CI323NANO                | 1         | 0.32%   |
| Wistron ProLiant ML110 G5           | 1         | 0.32%   |
| Toshiba PORTEGE X20W-D              | 1         | 0.32%   |
| Supermicro X9SCL/X9SCM              | 1         | 0.32%   |
| Supermicro X8STi                    | 1         | 0.32%   |
| Supermicro X8SIL                    | 1         | 0.32%   |
| Supermicro X7SLA                    | 1         | 0.32%   |
| Supermicro X7DCL                    | 1         | 0.32%   |
| Supermicro X11SSN-L                 | 1         | 0.32%   |
| Supermicro SYS-E300-9A-4CN10P       | 1         | 0.32%   |
| Supermicro SYS-5018D-FN8T           | 1         | 0.32%   |
| Sony SVF1521K1EB                    | 1         | 0.32%   |
| Shuttle XH270                       | 1         | 0.32%   |
| Shuttle SZ270R9                     | 1         | 0.32%   |
| Shuttle SZ270                       | 1         | 0.32%   |
| ShenZhen MinWin MW-NANO-APL-4L      | 1         | 0.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 25        | 8.12%   |
| Unknown              | 21        | 6.82%   |
| Dell OEM-R           | 13        | 4.22%   |
| Dell Latitude        | 13        | 4.22%   |
| Dell PowerEdge       | 10        | 3.25%   |
| Dell OptiPlex        | 10        | 3.25%   |
| HP t620              | 9         | 2.92%   |
| Dell Wyse            | 8         | 2.6%    |
| Fujitsu FUTRO        | 7         | 2.27%   |
| Lenovo ThinkCentre   | 5         | 1.62%   |
| Gigabyte B360N       | 5         | 1.62%   |
| Techvision TVI7309X  | 4         | 1.3%    |
| HP ProLiant          | 4         | 1.3%    |
| Dell Vostro          | 4         | 1.3%    |
| Acer Aspire          | 4         | 1.3%    |
| ZOTAC ZBOX-CI329NANO | 3         | 0.97%   |
| HP EliteBook         | 3         | 0.97%   |
| HP Compaq            | 3         | 0.97%   |
| ASUS PRIME           | 3         | 0.97%   |
| ASUS All             | 3         | 0.97%   |
| ASRock Q1900B-ITX    | 3         | 0.97%   |
| Lenovo IdeaPad       | 2         | 0.65%   |
| Intel SHARKBAY       | 2         | 0.65%   |
| Intel Q3XXG4-P       | 2         | 0.65%   |
| Intel D2500CC        | 2         | 0.65%   |
| Intel Appliance      | 2         | 0.65%   |
| HP ENVY              | 2         | 0.65%   |
| HP EliteDesk         | 2         | 0.65%   |
| Gigabyte H270N-WIFI  | 2         | 0.65%   |
| Gigabyte H110TN      | 2         | 0.65%   |
| Gigabyte B450M       | 2         | 0.65%   |
| Dell Inspiron        | 2         | 0.65%   |
| ASUS P5G41T-M        | 2         | 0.65%   |
| ASRock J3455B-ITX    | 2         | 0.65%   |
| ZOTAC ZBOX-CI341     | 1         | 0.32%   |
| ZOTAC ZBOX-CI323NANO | 1         | 0.32%   |
| Wistron ProLiant     | 1         | 0.32%   |
| Toshiba PORTEGE      | 1         | 0.32%   |
| Supermicro X9SCL     | 1         | 0.32%   |
| Supermicro X8STi     | 1         | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2014    | 52        | 16.88%  |
| 2018    | 35        | 11.36%  |
| 2019    | 28        | 9.09%   |
| 2012    | 23        | 7.47%   |
| 2020    | 22        | 7.14%   |
| 2016    | 21        | 6.82%   |
| 2021    | 20        | 6.49%   |
| 2022    | 19        | 6.17%   |
| 2013    | 17        | 5.52%   |
| 2009    | 16        | 5.19%   |
| 2017    | 11        | 3.57%   |
| 2011    | 11        | 3.57%   |
| 2010    | 10        | 3.25%   |
| 2015    | 7         | 2.27%   |
| 2023    | 4         | 1.3%    |
| Unknown | 4         | 1.3%    |
| 2008    | 3         | 0.97%   |
| 2006    | 3         | 0.97%   |
| 2007    | 2         | 0.65%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 166       | 53.9%   |
| Notebook    | 84        | 27.27%  |
| Server      | 33        | 10.71%  |
| Mini pc     | 18        | 5.84%   |
| All in one  | 5         | 1.62%   |
| Convertible | 2         | 0.65%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 301       | 97.73%  |
| Yes  | 7         | 2.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 95        | 30.35%  |
| 4.01-8.0    | 83        | 26.52%  |
| 16.01-24.0  | 73        | 23.32%  |
| 32.01-64.0  | 20        | 6.39%   |
| 64.01-256.0 | 20        | 6.39%   |
| 3.01-4.0    | 7         | 2.24%   |
| 2.01-3.0    | 7         | 2.24%   |
| 0.51-1.0    | 4         | 1.28%   |
| 24.01-32.0  | 3         | 0.96%   |
| 1.01-2.0    | 1         | 0.32%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 168       | 52.34%  |
| 0.51-1.0    | 88        | 27.41%  |
| 1.01-2.0    | 43        | 13.4%   |
| 2.01-3.0    | 7         | 2.18%   |
| 4.01-8.0    | 4         | 1.25%   |
| 8.01-16.0   | 4         | 1.25%   |
| 3.01-4.0    | 2         | 0.62%   |
| 0           | 2         | 0.62%   |
| 64.01-256.0 | 1         | 0.31%   |
| 16.01-24.0  | 1         | 0.31%   |
| Unknown     | 1         | 0.31%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 178       | 55.63%  |
| 2      | 64        | 20%     |
| 0      | 43        | 13.44%  |
| 3      | 15        | 4.69%   |
| 4      | 7         | 2.19%   |
| 6      | 6         | 1.88%   |
| 5      | 3         | 0.94%   |
| 9      | 2         | 0.63%   |
| 10     | 1         | 0.31%   |
| 8      | 1         | 0.31%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 248       | 79.49%  |
| Yes       | 64        | 20.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 292       | 94.81%  |
| No        | 16        | 5.19%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 170       | 54.49%  |
| Yes       | 142       | 45.51%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 222       | 71.38%  |
| Yes       | 89        | 28.62%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Poland  | 308       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                      | Computers | Percent |
|---------------------------|-----------|---------|
| Warsaw                    | 50        | 14.79%  |
| Krakow                    | 27        | 7.99%   |
| Wroclaw                   | 25        | 7.4%    |
| Gdynia                    | 22        | 6.51%   |
| Gdansk                    | 21        | 6.21%   |
| Poznan                    | 10        | 2.96%   |
| Lublin                    | 8         | 2.37%   |
| Lodz                      | 7         | 2.07%   |
| Zgierz                    | 4         | 1.18%   |
| Miedziana Gora            | 4         | 1.18%   |
| Piaseczno                 | 3         | 0.89%   |
| Lezno                     | 3         | 0.89%   |
| Legionowo                 | 3         | 0.89%   |
| Kielce                    | 3         | 0.89%   |
| Katowice                  | 3         | 0.89%   |
| Gmina Świebodzin         | 3         | 0.89%   |
| Chrusty                   | 3         | 0.89%   |
| Bydgoszcz                 | 3         | 0.89%   |
| Е»ukowo                 | 2         | 0.59%   |
| Witkow                    | 2         | 0.59%   |
| Walendow                  | 2         | 0.59%   |
| Szczecin                  | 2         | 0.59%   |
| Siedlce                   | 2         | 0.59%   |
| Radzionkow                | 2         | 0.59%   |
| Radom                     | 2         | 0.59%   |
| Police                    | 2         | 0.59%   |
| Lubin                     | 2         | 0.59%   |
| Kamieniec Zabkowicki      | 2         | 0.59%   |
| Jelenia Góra             | 2         | 0.59%   |
| Grudziądz                | 2         | 0.59%   |
| Gliwice                   | 2         | 0.59%   |
| Glincz                    | 2         | 0.59%   |
| CzД™stochowa           | 2         | 0.59%   |
| Chorzów                  | 2         | 0.59%   |
| Choroszcz                 | 2         | 0.59%   |
| Bialystok                 | 2         | 0.59%   |
| ЕљwiД™tochЕ‚owice | 1         | 0.3%    |
| Zajaczki Pierwsze         | 1         | 0.3%    |
| Zagnansk                  | 1         | 0.3%    |
| WЕ‚ocЕ‚awek         | 1         | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 51        | 108    | 14.33%  |
| Samsung Electronics | 49        | 86     | 13.76%  |
| Seagate             | 41        | 75     | 11.52%  |
| GOODRAM             | 23        | 36     | 6.46%   |
| SanDisk             | 22        | 28     | 6.18%   |
| A-DATA Technology   | 18        | 21     | 5.06%   |
| Toshiba             | 15        | 32     | 4.21%   |
| Kingston            | 14        | 15     | 3.93%   |
| Crucial             | 9         | 16     | 2.53%   |
| Intel               | 8         | 11     | 2.25%   |
| Transcend           | 7         | 12     | 1.97%   |
| SPCC                | 7         | 11     | 1.97%   |
| SK hynix            | 6         | 6      | 1.69%   |
| Hitachi             | 6         | 6      | 1.69%   |
| China               | 6         | 7      | 1.69%   |
| Plextor             | 5         | 5      | 1.4%    |
| Innodisk            | 5         | 7      | 1.4%    |
| Hoodisk             | 5         | 10     | 1.4%    |
| Hewlett-Packard     | 5         | 5      | 1.4%    |
| Apacer              | 5         | 7      | 1.4%    |
| PNY                 | 4         | 8      | 1.12%   |
| Patriot             | 4         | 4      | 1.12%   |
| OCZ                 | 4         | 4      | 1.12%   |
| NVMe                | 4         | 7      | 1.12%   |
| LITEON              | 4         | 4      | 1.12%   |
| HGST                | 3         | 5      | 0.84%   |
| Gigabyte Technology | 3         | 3      | 0.84%   |
| Corsair             | 3         | 5      | 0.84%   |
| Micron Technology   | 2         | 8      | 0.56%   |
| Kston               | 2         | 2      | 0.56%   |
| Intenso             | 2         | 3      | 0.56%   |
| Fanxiang            | 2         | 3      | 0.56%   |
| Team                | 1         | 1      | 0.28%   |
| SSSTC               | 1         | 2      | 0.28%   |
| SSDPR-CX            | 1         | 1      | 0.28%   |
| Silicon Motion      | 1         | 1      | 0.28%   |
| Phison              | 1         | 1      | 0.28%   |
| LITEONIT            | 1         | 1      | 0.28%   |
| Lexar               | 1         | 1      | 0.28%   |
| KIOXIA              | 1         | 1      | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| WDC WDS500G1R0A-68A4W0 500GB       | 6         | 1.51%   |
| Samsung HM321HI 320GB              | 6         | 1.51%   |
| WDC WD5000LPLX-22ZNTT0 500GB       | 5         | 1.26%   |
| Seagate ST1000LM035-1RK172 1TB     | 4         | 1.01%   |
| Seagate ST1000DM003-1CH162 1TB     | 4         | 1.01%   |
| WDC WD20EFRX-68EUZN0 2TB           | 3         | 0.76%   |
| SPCC Solid State Disk 256GB        | 3         | 0.76%   |
| Seagate ST500DM002-1BD142 500GB    | 3         | 0.76%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 0.76%   |
| SanDisk SDSA6MM-016G-1006 16GB     | 3         | 0.76%   |
| Samsung SSD 850 EVO 250GB          | 3         | 0.76%   |
| Kingston SUV500MS120G 120GB        | 3         | 0.76%   |
| Kingston SA400S37240G 240GB        | 3         | 0.76%   |
| Innodisk DEMSR- 16GB mSATA 3ME3    | 3         | 0.76%   |
| Hoodisk SSD 128GB                  | 3         | 0.76%   |
| GOODRAM SSDPR-CX400-512-G2 512GB   | 3         | 0.76%   |
| GOODRAM SSDPR-CX400-256-G2 256GB   | 3         | 0.76%   |
| GOODRAM SSDPR-CX400-256 256GB      | 3         | 0.76%   |
| GOODRAM SSDPR-CX400-128 128GB      | 3         | 0.76%   |
| GOODRAM SSDPR-CL100-120-G3 120GB   | 3         | 0.76%   |
| Crucial CT500MX500SSD1 500GB       | 3         | 0.76%   |
| Apacer AS340 240GB                 | 3         | 0.76%   |
| A-DATA SU800 256GB                 | 3         | 0.76%   |
| WDC WDS240G2G0A-00JH30 240GB       | 2         | 0.5%    |
| WDC WD20SDZW-11JJ8S0 2TB           | 2         | 0.5%    |
| WDC WD20NMVW-59EDZS7 2TB           | 2         | 0.5%    |
| WDC WD20EARS-00MVWB0 2TB           | 2         | 0.5%    |
| WDC WD10JPLX-00MBPT0 1TB           | 2         | 0.5%    |
| Transcend TS120GMTS420S 120GB      | 2         | 0.5%    |
| Toshiba MQ04ABF100 1TB             | 2         | 0.5%    |
| Seagate ST96812AS 64GB             | 2         | 0.5%    |
| Seagate ST500LT012-1DG142 500GB    | 2         | 0.5%    |
| Seagate ST4000LM024-2U817V 4TB     | 2         | 0.5%    |
| Seagate ST4000LM024-2AN17V 4TB     | 2         | 0.5%    |
| Seagate ST3250312AS 250GB          | 2         | 0.5%    |
| Seagate ST3250310AS 250GB          | 2         | 0.5%    |
| Seagate ST2000DL003-9VT166 2TB     | 2         | 0.5%    |
| Seagate ST1000NM0033-9ZM173 1TB    | 2         | 0.5%    |
| Seagate ST1000DM010-2EP102 1TB     | 2         | 0.5%    |
| SanDisk X600 M.2 2280 SATA 128GB   | 2         | 0.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 44        | 84     | 34.92%  |
| Seagate             | 41        | 75     | 32.54%  |
| Toshiba             | 12        | 29     | 9.52%   |
| Samsung Electronics | 12        | 19     | 9.52%   |
| Hitachi             | 6         | 6      | 4.76%   |
| Hewlett-Packard     | 4         | 4      | 3.17%   |
| HGST                | 3         | 5      | 2.38%   |
| NVMe                | 2         | 3      | 1.59%   |
| SSDPR-CX            | 1         | 1      | 0.79%   |
| Apple               | 1         | 1      | 0.79%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 25        | 51     | 13.23%  |
| SanDisk             | 22        | 28     | 11.64%  |
| GOODRAM             | 21        | 32     | 11.11%  |
| Kingston            | 13        | 13     | 6.88%   |
| A-DATA Technology   | 12        | 14     | 6.35%   |
| WDC                 | 10        | 21     | 5.29%   |
| Crucial             | 8         | 15     | 4.23%   |
| SPCC                | 7         | 11     | 3.7%    |
| Transcend           | 6         | 11     | 3.17%   |
| China               | 6         | 7      | 3.17%   |
| Plextor             | 5         | 5      | 2.65%   |
| Innodisk            | 5         | 7      | 2.65%   |
| Hoodisk             | 5         | 10     | 2.65%   |
| Apacer              | 5         | 7      | 2.65%   |
| OCZ                 | 4         | 4      | 2.12%   |
| Intel               | 4         | 7      | 2.12%   |
| SK hynix            | 3         | 3      | 1.59%   |
| Patriot             | 3         | 3      | 1.59%   |
| LITEON              | 3         | 3      | 1.59%   |
| Gigabyte Technology | 3         | 3      | 1.59%   |
| Corsair             | 3         | 5      | 1.59%   |
| PNY                 | 2         | 5      | 1.06%   |
| Micron Technology   | 2         | 8      | 1.06%   |
| Kston               | 2         | 2      | 1.06%   |
| Intenso             | 2         | 3      | 1.06%   |
| Toshiba             | 1         | 1      | 0.53%   |
| Team                | 1         | 1      | 0.53%   |
| Phison              | 1         | 1      | 0.53%   |
| NVMe                | 1         | 1      | 0.53%   |
| LITEONIT            | 1         | 1      | 0.53%   |
| Hewlett-Packard     | 1         | 1      | 0.53%   |
| FORESEE             | 1         | 1      | 0.53%   |
| Advantech           | 1         | 1      | 0.53%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 165       | 286    | 52.72%  |
| HDD  | 101       | 227    | 32.27%  |
| NVMe | 47        | 60     | 15.02%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 230       | 513    | 83.03%  |
| NVMe | 47        | 60     | 16.97%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 190       | 335    | 70.11%  |
| 0.51-1.0   | 48        | 92     | 17.71%  |
| 1.01-2.0   | 20        | 51     | 7.38%   |
| 3.01-4.0   | 6         | 11     | 2.21%   |
| 4.01-10.0  | 4         | 11     | 1.48%   |
| 2.01-3.0   | 3         | 13     | 1.11%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 115       | 35.6%   |
| 1-20           | 53        | 16.41%  |
| 251-500        | 46        | 14.24%  |
| 51-100         | 45        | 13.93%  |
| 21-50          | 29        | 8.98%   |
| 501-1000       | 26        | 8.05%   |
| 1001-2000      | 4         | 1.24%   |
| More than 3000 | 3         | 0.93%   |
| 2001-3000      | 2         | 0.62%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 281       | 87.81%  |
| 21-50          | 16        | 5%      |
| 101-250        | 9         | 2.81%   |
| 51-100         | 7         | 2.19%   |
| 251-500        | 4         | 1.25%   |
| 1001-2000      | 2         | 0.63%   |
| More than 3000 | 1         | 0.31%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                     | Computers | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| WDC WD5000LPLX-22ZNTT0 500GB              | 2         | 2      | 4.17%   |
| Toshiba MQ04ABF100 1TB                    | 2         | 2      | 4.17%   |
| Seagate ST96812AS 64GB                    | 2         | 5      | 4.17%   |
| Seagate ST1000DM003-1CH162 1TB            | 2         | 2      | 4.17%   |
| WDC WD7500BPKT-00PK4T0 752GB              | 1         | 1      | 2.08%   |
| WDC WD360ADFD-00NLR1 37GB                 | 1         | 1      | 2.08%   |
| WDC WD3200BEKT-22PVMT0 320GB              | 1         | 1      | 2.08%   |
| WDC WD3200AAVS-00ZTB0 320GB               | 1         | 1      | 2.08%   |
| WDC WD2500AAKX-753CA0 250GB               | 1         | 1      | 2.08%   |
| WDC WD2500AAKX-083CA1 250GB               | 1         | 2      | 2.08%   |
| WDC WD20NPVX-00EA4T0 2TB                  | 1         | 2      | 2.08%   |
| WDC WD20EZRX-00D8PB0 2TB                  | 1         | 1      | 2.08%   |
| WDC WD20EURS-63S48Y0 2TB                  | 1         | 1      | 2.08%   |
| WDC WD20EARS-00MVWB0 2TB                  | 1         | 1      | 2.08%   |
| WDC WD1600BEVE-00UYT0 160GB               | 1         | 1      | 2.08%   |
| WDC WD1600AAJS-40H3A0 160GB               | 1         | 1      | 2.08%   |
| WDC WD1200BEVS-07LAT0 120GB               | 1         | 1      | 2.08%   |
| WDC WD10EARS-003BB1 1TB                   | 1         | 1      | 2.08%   |
| Toshiba THNSNK512GVN8 512GB               | 1         | 1      | 2.08%   |
| Toshiba MK3261GSYN 320GB                  | 1         | 1      | 2.08%   |
| Toshiba MK1252GSX 120GB                   | 1         | 1      | 2.08%   |
| SPCC Solid State Disk 256GB               | 1         | 1      | 2.08%   |
| SK hynix SC308 SATA 256GB                 | 1         | 1      | 2.08%   |
| SK hynix SC210 mSATA 256GB                | 1         | 1      | 2.08%   |
| Seagate ST9500420AS 500GB                 | 1         | 2      | 2.08%   |
| Seagate ST9160412AS 160GB                 | 1         | 1      | 2.08%   |
| Seagate ST500LM000-1EJ162 500GB           | 1         | 1      | 2.08%   |
| Seagate ST500DM002-1BD142 500GB           | 1         | 1      | 2.08%   |
| Seagate ST3250310AS 250GB                 | 1         | 1      | 2.08%   |
| Seagate ST32000542AS 2TB                  | 1         | 1      | 2.08%   |
| Seagate ST2000LM015-2E8174 2TB            | 1         | 2      | 2.08%   |
| Seagate ST2000DL003-9VT166 2TB            | 1         | 1      | 2.08%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 1         | 1      | 2.08%   |
| SanDisk SSD U100 64GB                     | 1         | 3      | 2.08%   |
| Samsung Electronics SSD 870 EVO 1TB       | 1         | 1      | 2.08%   |
| Samsung Electronics HD154UI 1.5TB         | 1         | 1      | 2.08%   |
| Plextor PX-128G7Ne 128GB                  | 1         | 1      | 2.08%   |
| Micron Technology MTFDDAT128MAM-1J2 128GB | 1         | 1      | 2.08%   |
| Kingston SV300S37A240G 240GB              | 1         | 1      | 2.08%   |
| Hitachi HTS721060G9SA00 64GB              | 1         | 1      | 2.08%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 15        | 18     | 31.91%  |
| Seagate             | 13        | 18     | 27.66%  |
| Toshiba             | 5         | 5      | 10.64%  |
| SK hynix            | 2         | 2      | 4.26%   |
| Samsung Electronics | 2         | 2      | 4.26%   |
| Hitachi             | 2         | 2      | 4.26%   |
| Crucial             | 2         | 3      | 4.26%   |
| SPCC                | 1         | 1      | 2.13%   |
| SanDisk             | 1         | 3      | 2.13%   |
| Plextor             | 1         | 1      | 2.13%   |
| Micron Technology   | 1         | 1      | 2.13%   |
| Kingston            | 1         | 1      | 2.13%   |
| A-DATA Technology   | 1         | 1      | 2.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 15        | 18     | 42.86%  |
| Seagate             | 13        | 18     | 37.14%  |
| Toshiba             | 4         | 4      | 11.43%  |
| Hitachi             | 2         | 2      | 5.71%   |
| Samsung Electronics | 1         | 1      | 2.86%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 32        | 43     | 72.73%  |
| SSD  | 12        | 15     | 27.27%  |

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
| Works    | 239       | 499    | 81.02%  |
| Malfunc  | 43        | 58     | 14.58%  |
| Detected | 11        | 14     | 3.73%   |
| Failed   | 2         | 2      | 0.68%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 220       | 60.77%  |
| AMD                            | 47        | 12.98%  |
| Broadcom / LSI                 | 26        | 7.18%   |
| Samsung Electronics            | 16        | 4.42%   |
| Silicon Motion                 | 6         | 1.66%   |
| SanDisk                        | 6         | 1.66%   |
| Hewlett-Packard                | 4         | 1.1%    |
| ADATA Technology               | 4         | 1.1%    |
| SK hynix                       | 3         | 0.83%   |
| Phison Electronics             | 3         | 0.83%   |
| Marvell Technology Group       | 3         | 0.83%   |
| JMicron Technology             | 3         | 0.83%   |
| ASMedia Technology             | 3         | 0.83%   |
| VIA Technologies               | 2         | 0.55%   |
| Nvidia                         | 2         | 0.55%   |
| KIOXIA                         | 2         | 0.55%   |
| Kingston Technology Company    | 2         | 0.55%   |
| Transcend                      | 1         | 0.28%   |
| Toshiba                        | 1         | 0.28%   |
| Solid State Storage Technology | 1         | 0.28%   |
| Shenzhen Longsys Electronics   | 1         | 0.28%   |
| Realtek Semiconductor          | 1         | 0.28%   |
| Micron/Crucial Technology      | 1         | 0.28%   |
| Lite-On Technology             | 1         | 0.28%   |
| Integrated Technology Express  | 1         | 0.28%   |
| Biwin Storage Technology       | 1         | 0.28%   |
| Apple                          | 1         | 0.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 34        | 8.61%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 20        | 5.06%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 16        | 4.05%   |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                   | 15        | 3.8%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 13        | 3.29%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 12        | 3.04%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 12        | 3.04%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 11        | 2.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 9         | 2.28%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 9         | 2.28%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 8         | 2.03%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 8         | 2.03%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 8         | 2.03%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 7         | 1.77%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 7         | 1.77%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6         | 1.52%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 6         | 1.52%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 6         | 1.52%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 5         | 1.27%   |
| Samsung NVMe SSD Controller 980                                                  | 5         | 1.27%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 5         | 1.27%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 5         | 1.27%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 5         | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 5         | 1.27%   |
| Intel SATA Controller [RAID mode]                                                | 4         | 1.01%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 1.01%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 4         | 1.01%   |
| AMD 400 Series Chipset SATA Controller                                           | 4         | 1.01%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 3         | 0.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 0.76%   |
| JMicron JMB363 SATA/IDE Controller                                               | 3         | 0.76%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 0.76%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 0.76%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 3         | 0.76%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 3         | 0.76%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 3         | 0.76%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 3         | 0.76%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]              | 3         | 0.76%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 3         | 0.76%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 236       | 65.56%  |
| NVMe | 51        | 14.17%  |
| RAID | 34        | 9.44%   |
| IDE  | 33        | 9.17%   |
| SAS  | 4         | 1.11%   |
| SCSI | 2         | 0.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 249       | 80.58%  |
| AMD     | 53        | 17.15%  |
| ARM     | 5         | 1.62%   |
| VIA     | 1         | 0.32%   |
| PowerPC | 1         | 0.32%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz      | 13        | 4.18%   |
| AMD GX-420CA SOC with Radeon HD Graphics | 9         | 2.89%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz     | 7         | 2.25%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz | 6         | 1.93%   |
| Intel Celeron CPU J1900 @ 1.99GHz        | 6         | 1.93%   |
| Intel Celeron N5105 @ 2.00GHz            | 5         | 1.61%   |
| Intel Celeron N4100 CPU @ 1.10GHz        | 5         | 1.61%   |
| AMD GX-415GA SOC with Radeon HD Graphics | 5         | 1.61%   |
| Intel Core i3-8300T CPU @ 3.20GHz        | 4         | 1.29%   |
| Intel Core i3-6100 CPU @ 3.70GHz         | 4         | 1.29%   |
| Intel Celeron J4125 CPU @ 2.00GHz        | 4         | 1.29%   |
| Intel Celeron CPU J3455 @ 1.50GHz        | 4         | 1.29%   |
| Intel Core i5-6500 CPU @ 3.20GHz         | 3         | 0.96%   |
| Intel Core i5-6300U CPU @ 2.40GHz        | 3         | 0.96%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 3         | 0.96%   |
| Intel Core i5-4570 CPU @ 3.20GHz         | 3         | 0.96%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 3         | 0.96%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 3         | 0.96%   |
| Intel Core i5-10210U CPU @ 1.60GHz       | 3         | 0.96%   |
| Intel Core 2 Duo                         | 3         | 0.96%   |
| Intel Celeron J4105 CPU @ 1.50GHz        | 3         | 0.96%   |
| Intel Celeron CPU N3150 @ 1.60GHz        | 3         | 0.96%   |
| Intel Atom CPU D2500 @ 1.86GHz           | 3         | 0.96%   |
| AMD Phenom II X4 965 Processor           | 3         | 0.96%   |
| AMD GX-412TC SOC                         | 3         | 0.96%   |
| Intel Xeon CPU X5660 @ 2.80GHz           | 2         | 0.64%   |
| Intel Xeon CPU X3430 @ 2.40GHz           | 2         | 0.64%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz      | 2         | 0.64%   |
| Intel Pentium CPU G860 @ 3.00GHz         | 2         | 0.64%   |
| Intel Pentium CPU G4600T @ 3.00GHz       | 2         | 0.64%   |
| Intel Pentium CPU G3220 @ 3.00GHz        | 2         | 0.64%   |
| Intel Core i7-8700 CPU @ 3.20GHz         | 2         | 0.64%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 2         | 0.64%   |
| Intel Core i7-3720QM CPU @ 2.60GHz       | 2         | 0.64%   |
| Intel Core i5-8365U CPU @ 1.60GHz        | 2         | 0.64%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 2         | 0.64%   |
| Intel Core i5-6400T CPU @ 2.20GHz        | 2         | 0.64%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 2         | 0.64%   |
| Intel Core i5-3320M CPU @ 2.60GHz        | 2         | 0.64%   |
| Intel Core i5-2400 CPU @ 3.10GHz         | 2         | 0.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 64        | 20.58%  |
| Intel Celeron           | 43        | 13.83%  |
| Intel Xeon              | 38        | 12.22%  |
| Intel Core i7           | 25        | 8.04%   |
| Intel Core i3           | 25        | 8.04%   |
| AMD GX                  | 19        | 6.11%   |
| Intel Core 2 Duo        | 14        | 4.5%    |
| Intel Pentium           | 12        | 3.86%   |
| Other                   | 10        | 3.22%   |
| Intel Pentium Silver    | 8         | 2.57%   |
| Intel Atom              | 8         | 2.57%   |
| ARM Cortex              | 5         | 1.61%   |
| AMD Ryzen 3             | 5         | 1.61%   |
| AMD Ryzen 5             | 4         | 1.29%   |
| Intel Pentium Dual-Core | 3         | 0.96%   |
| AMD Ryzen 7             | 3         | 0.96%   |
| AMD Phenom II X4        | 3         | 0.96%   |
| AMD G                   | 3         | 0.96%   |
| AMD Ryzen 9             | 2         | 0.64%   |
| AMD Ryzen 5 PRO         | 2         | 0.64%   |
| AMD E                   | 2         | 0.64%   |
| AMD Athlon              | 2         | 0.64%   |
| Intel Pentium M         | 1         | 0.32%   |
| Intel Genuine           | 1         | 0.32%   |
| Intel Core 2 Quad       | 1         | 0.32%   |
| Intel Core 2            | 1         | 0.32%   |
| Intel Celeron M         | 1         | 0.32%   |
| AMD Ryzen Embedded      | 1         | 0.32%   |
| AMD Ryzen 7 PRO         | 1         | 0.32%   |
| AMD Phenom II X6        | 1         | 0.32%   |
| AMD EPYC                | 1         | 0.32%   |
| AMD Athlon 64 X2        | 1         | 0.32%   |
| AMD A4                  | 1         | 0.32%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 137       | 44.19%  |
| 2       | 90        | 29.03%  |
| Unknown | 21        | 6.77%   |
| 16      | 16        | 5.16%   |
| 8       | 15        | 4.84%   |
| 6       | 11        | 3.55%   |
| 12      | 10        | 3.23%   |
| 1       | 6         | 1.94%   |
| 20      | 2         | 0.65%   |
| 32      | 1         | 0.32%   |
| 24      | 1         | 0.32%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 267       | 86.69%  |
| 2       | 27        | 8.77%   |
| Unknown | 14        | 4.55%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 164       | 52.9%   |
| 2       | 121       | 39.03%  |
| Unknown | 25        | 8.06%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| IvyBridge     | 36        | 11.58%  |
| KabyLake      | 35        | 11.25%  |
| Haswell       | 31        | 9.97%   |
| Penryn        | 21        | 6.75%   |
| Skylake       | 20        | 6.43%   |
| Goldmont plus | 20        | 6.43%   |
| Unknown       | 20        | 6.43%   |
| SandyBridge   | 19        | 6.11%   |
| Jaguar        | 17        | 5.47%   |
| Silvermont    | 13        | 4.18%   |
| Broadwell     | 9         | 2.89%   |
| Goldmont      | 8         | 2.57%   |
| Zen           | 7         | 2.25%   |
| Westmere      | 7         | 2.25%   |
| Zen 2         | 6         | 1.93%   |
| Bonnell       | 5         | 1.61%   |
| Bobcat        | 5         | 1.61%   |
| Puma          | 4         | 1.29%   |
| Nehalem       | 4         | 1.29%   |
| K10           | 4         | 1.29%   |
| Zen+          | 3         | 0.96%   |
| Zen 3         | 3         | 0.96%   |
| Core          | 3         | 0.96%   |
| CometLake     | 3         | 0.96%   |
| TigerLake     | 2         | 0.64%   |
| P6            | 2         | 0.64%   |
| Steamroller   | 1         | 0.32%   |
| NetBurst      | 1         | 0.32%   |
| K8 Hammer     | 1         | 0.32%   |
| Excavator     | 1         | 0.32%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 190       | 58.64%  |
| AMD                                          | 57        | 17.59%  |
| Nvidia                                       | 39        | 12.04%  |
| Matrox Electronics Systems                   | 30        | 9.26%   |
| ASPEED Technology                            | 5         | 1.54%   |
| VIA Technologies                             | 2         | 0.62%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.31%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Matrox Electronics Systems G200eR2                                                       | 18        | 5.5%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 13        | 3.98%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 12        | 3.67%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 12        | 3.67%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 12        | 3.67%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 10        | 3.06%   |
| Intel HD Graphics 530                                                                    | 10        | 3.06%   |
| AMD Kabini [Radeon HD 8400E]                                                             | 9         | 2.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 2.45%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 7         | 2.14%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 7         | 2.14%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 6         | 1.83%   |
| Intel JasperLake [UHD Graphics]                                                          | 6         | 1.83%   |
| Intel HD Graphics 620                                                                    | 6         | 1.83%   |
| Intel HD Graphics 5500                                                                   | 6         | 1.83%   |
| Intel HD Graphics 500                                                                    | 6         | 1.83%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 1.83%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6         | 1.83%   |
| Intel HD Graphics 630                                                                    | 5         | 1.53%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 1.53%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 5         | 1.53%   |
| AMD Kabini [Radeon HD 8330E]                                                             | 5         | 1.53%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 4         | 1.22%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 1.22%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 1.22%   |
| Intel HD Graphics 510                                                                    | 4         | 1.22%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 1.22%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4         | 1.22%   |
| AMD ES1000                                                                               | 4         | 1.22%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 0.92%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 0.92%   |
| Intel UHD Graphics 620                                                                   | 3         | 0.92%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 0.92%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 3         | 0.92%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3         | 0.92%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 0.92%   |
| AMD Renoir                                                                               | 3         | 0.92%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 0.92%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.61%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 2         | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 153       | 49.2%   |
| 1 x AMD         | 50        | 16.08%  |
| 1 x Matrox      | 30        | 9.65%   |
| 1 x Nvidia      | 21        | 6.75%   |
| Intel + Nvidia  | 17        | 5.47%   |
| 2 x Intel       | 15        | 4.82%   |
| Other           | 11        | 3.54%   |
| Intel + AMD     | 5         | 1.61%   |
| 1 x ASPEED      | 3         | 0.96%   |
| 1 x VIA         | 2         | 0.64%   |
| 1 x XGI         | 1         | 0.32%   |
| Nvidia + ASPEED | 1         | 0.32%   |
| AMD + Nvidia    | 1         | 0.32%   |
| AMD + ASPEED    | 1         | 0.32%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 274       | 88.67%  |
| Proprietary | 19        | 6.15%   |
| Unknown     | 16        | 5.18%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 277       | 89.64%  |
| 1.01-2.0   | 8         | 2.59%   |
| 3.01-4.0   | 7         | 2.27%   |
| 7.01-8.0   | 6         | 1.94%   |
| 0.01-0.5   | 5         | 1.62%   |
| 0.51-1.0   | 4         | 1.29%   |
| 5.01-6.0   | 1         | 0.32%   |
| 8.01-16.0  | 1         | 0.32%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 16        | 14.55%  |
| Samsung Electronics     | 10        | 9.09%   |
| Lenovo                  | 9         | 8.18%   |
| Iiyama                  | 9         | 8.18%   |
| BOE                     | 8         | 7.27%   |
| Dell                    | 6         | 5.45%   |
| Chimei Innolux          | 6         | 5.45%   |
| AU Optronics            | 6         | 5.45%   |
| NEC Computers           | 5         | 4.55%   |
| Acer                    | 5         | 4.55%   |
| Philips                 | 4         | 3.64%   |
| InfoVision              | 2         | 1.82%   |
| Idek Iiyama             | 2         | 1.82%   |
| Hewlett-Packard         | 2         | 1.82%   |
| Goldstar                | 2         | 1.82%   |
| Chi Mei Optoelectronics | 2         | 1.82%   |
| BenQ                    | 2         | 1.82%   |
| Apple                   | 2         | 1.82%   |
| AOC                     | 2         | 1.82%   |
| Vestel Elektronik       | 1         | 0.91%   |
| Toshiba                 | 1         | 0.91%   |
| Sharp                   | 1         | 0.91%   |
| PANDA                   | 1         | 0.91%   |
| KTC                     | 1         | 0.91%   |
| JDI                     | 1         | 0.91%   |
| HPN                     | 1         | 0.91%   |
| Eizo                    | 1         | 0.91%   |
| BOE Technology Group    | 1         | 0.91%   |
| Unknown                 | 1         | 0.91%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch                  | 6         | 5.45%   |
| Iiyama PL2775HD IVM6604 1920x1080 600x340mm 27.2-inch                    | 6         | 5.45%   |
| LG Display LCD Monitor LGD039F 1366x768 350x190mm 15.7-inch              | 2         | 1.82%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 2         | 1.82%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch       | 1         | 0.91%   |
| Toshiba TV TSB0110 1920x1080 1110x620mm 50.1-inch                        | 1         | 0.91%   |
| Sharp LCD Monitor SHP1451 1920x1080 280x160mm 12.7-inch                  | 1         | 0.91%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 700x390mm 31.5-inch        | 1         | 0.91%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 490x320mm 23.0-inch     | 1         | 0.91%   |
| Samsung Electronics LF27T370F SAM711E 1920x1080 600x340mm 27.2-inch      | 1         | 0.91%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x170mm 13.9-inch     | 1         | 0.91%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 300x190mm 14.0-inch     | 1         | 0.91%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 340x190mm 15.3-inch     | 1         | 0.91%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch     | 1         | 0.91%   |
| Samsung Electronics LCD Monitor SDC4163 3456x2160 290x180mm 13.4-inch    | 1         | 0.91%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch    | 1         | 0.91%   |
| Samsung Electronics LCD Monitor S24F350 1920x1080                        | 1         | 0.91%   |
| Philips PHL 275S1 PHL094B 2560x1440 600x340mm 27.2-inch                  | 1         | 0.91%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                  | 1         | 0.91%   |
| Philips LCD Monitor PHLC01A 1680x1050 470x300mm 22.0-inch                | 1         | 0.91%   |
| Philips 150S PHL0820 1024x768 300x230mm 14.9-inch                        | 1         | 0.91%   |
| PANDA LCD Monitor NCP006E 1920x1080 340x190mm 15.3-inch                  | 1         | 0.91%   |
| NEC Computers LCD4020 NEC66EA 1920x540 890x500mm 40.2-inch               | 1         | 0.91%   |
| NEC Computers LCD24WMCX NEC6720 1920x1200 520x320mm 24.0-inch            | 1         | 0.91%   |
| NEC Computers EA294WMi NEC68CF 2560x1080 670x280mm 28.6-inch             | 1         | 0.91%   |
| NEC Computers EA223WM NEC6891 1680x1050 470x300mm 22.0-inch              | 1         | 0.91%   |
| NEC Computers E438 NEC335C 3840x2160 940x530mm 42.5-inch                 | 1         | 0.91%   |
| LG Display LCD Monitor LGD0533 1920x1080 340x190mm 15.3-inch             | 1         | 0.91%   |
| LG Display LCD Monitor LGD04E2 1366x768 340x190mm 15.3-inch              | 1         | 0.91%   |
| LG Display LCD Monitor LGD0408 1920x1080 280x160mm 12.7-inch             | 1         | 0.91%   |
| LG Display LCD Monitor LGD03D3 1600x900 310x170mm 13.9-inch              | 1         | 0.91%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch              | 1         | 0.91%   |
| LG Display LCD Monitor LGD0368 1366x768 310x170mm 13.9-inch              | 1         | 0.91%   |
| LG Display LCD Monitor LGD033E 1366x768 310x170mm 13.9-inch              | 1         | 0.91%   |
| LG Display LCD Monitor LGD02F1 1366x768 340x190mm 15.3-inch              | 1         | 0.91%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 1         | 0.91%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 1         | 0.91%   |
| LG Display LCD Monitor LGD02AD 1366x768 340x190mm 15.3-inch              | 1         | 0.91%   |
| LG Display LCD Monitor LGD0283 1920x1080 380x220mm 17.3-inch             | 1         | 0.91%   |
| LG Display LCD Monitor LGD0250 1366x768 350x190mm 15.7-inch              | 1         | 0.91%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 47        | 44.76%  |
| 1366x768 (WXGA)    | 23        | 21.9%   |
| 1280x800 (WXGA)    | 8         | 7.62%   |
| 3840x2160 (4K)     | 6         | 5.71%   |
| 1680x1050 (WSXGA+) | 4         | 3.81%   |
| 1600x900 (HD+)     | 3         | 2.86%   |
| 2560x1440 (QHD)    | 2         | 1.9%    |
| 1920x540           | 2         | 1.9%    |
| 1920x1200 (WUXGA)  | 2         | 1.9%    |
| Unknown            | 2         | 1.9%    |
| 5760x2160          | 1         | 0.95%   |
| 3456x2160          | 1         | 0.95%   |
| 2560x1080          | 1         | 0.95%   |
| 1440x900 (WXGA+)   | 1         | 0.95%   |
| 1280x1024 (SXGA)   | 1         | 0.95%   |
| 1024x768 (XGA)     | 1         | 0.95%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 22        | 20.75%  |
| 13      | 19        | 17.92%  |
| 12      | 13        | 12.26%  |
| 27      | 11        | 10.38%  |
| 24      | 7         | 6.6%    |
| 23      | 6         | 5.66%   |
| Unknown | 6         | 5.66%   |
| 21      | 5         | 4.72%   |
| 18      | 3         | 2.83%   |
| 42      | 2         | 1.89%   |
| 31      | 2         | 1.89%   |
| 22      | 2         | 1.89%   |
| 17      | 2         | 1.89%   |
| 14      | 2         | 1.89%   |
| 50      | 1         | 0.94%   |
| 40      | 1         | 0.94%   |
| 28      | 1         | 0.94%   |
| 20      | 1         | 0.94%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 38        | 36.19%  |
| 501-600     | 23        | 21.9%   |
| 201-300     | 18        | 17.14%  |
| 401-500     | 11        | 10.48%  |
| Unknown     | 6         | 5.71%   |
| 601-700     | 3         | 2.86%   |
| 351-400     | 2         | 1.9%    |
| 901-1000    | 2         | 1.9%    |
| 801-900     | 1         | 0.95%   |
| 1001-1500   | 1         | 0.95%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 74        | 74%     |
| 16/10   | 15        | 15%     |
| Unknown | 6         | 6%      |
| 3/2     | 2         | 2%      |
| 5/4     | 1         | 1%      |
| 4/3     | 1         | 1%      |
| 21/9    | 1         | 1%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 18        | 17.14%  |
| 201-250        | 16        | 15.24%  |
| 91-100         | 16        | 15.24%  |
| 61-70          | 13        | 12.38%  |
| 301-350        | 11        | 10.48%  |
| 101-110        | 7         | 6.67%   |
| Unknown        | 6         | 5.71%   |
| 251-300        | 4         | 3.81%   |
| 141-150        | 3         | 2.86%   |
| 501-1000       | 3         | 2.86%   |
| 71-80          | 2         | 1.9%    |
| 351-500        | 2         | 1.9%    |
| 151-200        | 2         | 1.9%    |
| More than 1000 | 1         | 0.95%   |
| 121-130        | 1         | 0.95%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 35        | 33.98%  |
| 51-100        | 33        | 32.04%  |
| 101-120       | 21        | 20.39%  |
| Unknown       | 6         | 5.83%   |
| 161-240       | 5         | 4.85%   |
| 1-50          | 2         | 1.94%   |
| More than 240 | 1         | 0.97%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 196       | 63.23%  |
| 1     | 102       | 32.9%   |
| 2     | 11        | 3.55%   |
| 3     | 1         | 0.32%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 208       | 44.83%  |
| Realtek Semiconductor             | 133       | 28.66%  |
| Broadcom                          | 51        | 10.99%  |
| Qualcomm Atheros                  | 29        | 6.25%   |
| Qualcomm Atheros Communications   | 6         | 1.29%   |
| TP-Link                           | 3         | 0.65%   |
| Emulex                            | 3         | 0.65%   |
| Dell                              | 3         | 0.65%   |
| Marvell Technology Group          | 2         | 0.43%   |
| Huawei Technologies               | 2         | 0.43%   |
| AMD                               | 2         | 0.43%   |
| Xiaomi                            | 1         | 0.22%   |
| VIA Technologies                  | 1         | 0.22%   |
| Van Ooijen Technische Informatica | 1         | 0.22%   |
| U-Blox                            | 1         | 0.22%   |
| Sierra Wireless                   | 1         | 0.22%   |
| Seeed Technology                  | 1         | 0.22%   |
| Ralink Technology                 | 1         | 0.22%   |
| Ralink                            | 1         | 0.22%   |
| QLogic                            | 1         | 0.22%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.22%   |
| Nvidia                            | 1         | 0.22%   |
| Nuvoton                           | 1         | 0.22%   |
| NetGear                           | 1         | 0.22%   |
| Mellanox Technologies             | 1         | 0.22%   |
| IMC Networks                      | 1         | 0.22%   |
| Ericsson Business Mobile Networks | 1         | 0.22%   |
| D-Link System                     | 1         | 0.22%   |
| Chelsio Communications            | 1         | 0.22%   |
| Atheros                           | 1         | 0.22%   |
| Apple                             | 1         | 0.22%   |
| American Megatrends               | 1         | 0.22%   |
| 3Com                              | 1         | 0.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 118       | 20.81%  |
| Intel I211 Gigabit Network Connection                                         | 29        | 5.11%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 19        | 3.35%   |
| Intel I350 Gigabit Network Connection                                         | 18        | 3.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 17        | 3%      |
| Intel I210 Gigabit Network Connection                                         | 16        | 2.82%   |
| Intel 82574L Gigabit Network Connection                                       | 11        | 1.94%   |
| Intel Ethernet Connection I217-LM                                             | 10        | 1.76%   |
| Intel 82567LM Gigabit Network Connection                                      | 10        | 1.76%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 9         | 1.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 7         | 1.23%   |
| Intel Wireless 8265 / 8275                                                    | 7         | 1.23%   |
| Intel Wireless 8260                                                           | 7         | 1.23%   |
| Intel Ethernet Controller I226-V                                              | 7         | 1.23%   |
| Intel Ethernet Connection (7) I219-V                                          | 7         | 1.23%   |
| Intel Ethernet Connection (2) I219-V                                          | 7         | 1.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 7         | 1.23%   |
| Intel Ultimate N WiFi Link 5300                                               | 6         | 1.06%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 6         | 1.06%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 6         | 1.06%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 6         | 1.06%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 5         | 0.88%   |
| Intel Wireless 7265                                                           | 5         | 0.88%   |
| Broadcom BCM43228 802.11a/b/g/n                                               | 5         | 0.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 4         | 0.71%   |
| Qualcomm Atheros AR9271 802.11n                                               | 4         | 0.71%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 4         | 0.71%   |
| Intel Wireless 3165                                                           | 4         | 0.71%   |
| Intel Wi-Fi 6 AX200                                                           | 4         | 0.71%   |
| Intel Ethernet Controller I225-V                                              | 4         | 0.71%   |
| Intel Ethernet Connection I219-LM                                             | 4         | 0.71%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 4         | 0.71%   |
| Intel 82580 Gigabit Network Connection                                        | 4         | 0.71%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 4         | 0.71%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 4         | 0.71%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 3         | 0.53%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 3         | 0.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 3         | 0.53%   |
| Intel Wireless 7260                                                           | 3         | 0.53%   |
| Intel Ethernet Connection I218-LM                                             | 3         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 86        | 55.84%  |
| Qualcomm Atheros                | 25        | 16.23%  |
| Realtek Semiconductor           | 13        | 8.44%   |
| Broadcom                        | 13        | 8.44%   |
| Qualcomm Atheros Communications | 6         | 3.9%    |
| TP-Link                         | 3         | 1.95%   |
| Dell                            | 2         | 1.3%    |
| Ralink Technology               | 1         | 0.65%   |
| Ralink                          | 1         | 0.65%   |
| NetGear                         | 1         | 0.65%   |
| IMC Networks                    | 1         | 0.65%   |
| D-Link System                   | 1         | 0.65%   |
| Atheros                         | 1         | 0.65%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 7         | 4.55%   |
| Intel Wireless 8265 / 8275                                                    | 7         | 4.55%   |
| Intel Wireless 8260                                                           | 7         | 4.55%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 7         | 4.55%   |
| Intel Ultimate N WiFi Link 5300                                               | 6         | 3.9%    |
| Intel Gemini Lake PCH CNVi WiFi                                               | 6         | 3.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 6         | 3.9%    |
| Intel Wireless 7265                                                           | 5         | 3.25%   |
| Broadcom BCM43228 802.11a/b/g/n                                               | 5         | 3.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 4         | 2.6%    |
| Qualcomm Atheros AR9271 802.11n                                               | 4         | 2.6%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 4         | 2.6%    |
| Intel Wireless 3165                                                           | 4         | 2.6%    |
| Intel Wi-Fi 6 AX200                                                           | 4         | 2.6%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 3         | 1.95%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 3         | 1.95%   |
| Intel Wireless 7260                                                           | 3         | 1.95%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 3         | 1.95%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 2         | 1.3%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 2         | 1.3%    |
| Realtek RTL8188EE Wireless Network Adapter                                    | 2         | 1.3%    |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 2         | 1.3%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2         | 1.3%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 2         | 1.3%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 1.3%    |
| Intel Wi-Fi 6 AX201                                                           | 2         | 1.3%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                       | 2         | 1.3%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 2         | 1.3%    |
| Intel Centrino Advanced-N 6235                                                | 2         | 1.3%    |
| Intel Centrino Advanced-N 6200                                                | 2         | 1.3%    |
| Broadcom BCM43142 802.11b/g/n                                                 | 2         | 1.3%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1         | 0.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.65%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 0.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1         | 0.65%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 0.65%   |
| Ralink RT2561/RT61 rev B 802.11g                                              | 1         | 0.65%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter               | 1         | 0.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1         | 0.65%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1         | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 174       | 48.74%  |
| Realtek Semiconductor         | 124       | 34.73%  |
| Broadcom                      | 39        | 10.92%  |
| Qualcomm Atheros              | 5         | 1.4%    |
| Marvell Technology Group      | 2         | 0.56%   |
| Emulex                        | 2         | 0.56%   |
| AMD                           | 2         | 0.56%   |
| Xiaomi                        | 1         | 0.28%   |
| VIA Technologies              | 1         | 0.28%   |
| QLogic                        | 1         | 0.28%   |
| OnePlus Technology (Shenzhen) | 1         | 0.28%   |
| Nvidia                        | 1         | 0.28%   |
| Huawei Technologies           | 1         | 0.28%   |
| Apple                         | 1         | 0.28%   |
| American Megatrends           | 1         | 0.28%   |
| 3Com                          | 1         | 0.28%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 118       | 29.43%  |
| Intel I211 Gigabit Network Connection                                         | 29        | 7.23%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 19        | 4.74%   |
| Intel I350 Gigabit Network Connection                                         | 18        | 4.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 17        | 4.24%   |
| Intel I210 Gigabit Network Connection                                         | 16        | 3.99%   |
| Intel 82574L Gigabit Network Connection                                       | 11        | 2.74%   |
| Intel Ethernet Connection I217-LM                                             | 10        | 2.49%   |
| Intel 82567LM Gigabit Network Connection                                      | 10        | 2.49%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 9         | 2.24%   |
| Intel Ethernet Controller I226-V                                              | 7         | 1.75%   |
| Intel Ethernet Connection (7) I219-V                                          | 7         | 1.75%   |
| Intel Ethernet Connection (2) I219-V                                          | 7         | 1.75%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 6         | 1.5%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 5         | 1.25%   |
| Intel Ethernet Controller I225-V                                              | 4         | 1%      |
| Intel Ethernet Connection I219-LM                                             | 4         | 1%      |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 4         | 1%      |
| Intel 82580 Gigabit Network Connection                                        | 4         | 1%      |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 4         | 1%      |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 4         | 1%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 3         | 0.75%   |
| Intel Ethernet Connection I218-LM                                             | 3         | 0.75%   |
| Intel Ethernet Connection (3) I218-LM                                         | 3         | 0.75%   |
| Intel 82576 Gigabit Network Connection                                        | 3         | 0.75%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 3         | 0.75%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 2         | 0.5%    |
| Intel Ethernet Controller X550                                                | 2         | 0.5%    |
| Intel Ethernet Connection (5) I219-LM                                         | 2         | 0.5%    |
| Intel Ethernet Connection (4) I219-LM                                         | 2         | 0.5%    |
| Intel Ethernet Connection (10) I219-V                                         | 2         | 0.5%    |
| Intel 82583V Gigabit Network Connection                                       | 2         | 0.5%    |
| Intel 82577LM Gigabit Network Connection                                      | 2         | 0.5%    |
| Intel 82576NS Gigabit Network Connection                                      | 2         | 0.5%    |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 2         | 0.5%    |
| Emulex OneConnect 10Gb NIC (be3)                                              | 2         | 0.5%    |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 2         | 0.5%    |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0                     | 2         | 0.5%    |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 1         | 0.25%   |
| VIA VT6102/VT6103 [Rhine-II]                                                  | 1         | 0.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 292       | 65.47%  |
| WiFi     | 142       | 31.84%  |
| Modem    | 6         | 1.35%   |
| Unknown  | 6         | 1.35%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 256       | 77.34%  |
| WiFi     | 75        | 22.66%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 114       | 36.31%  |
| 1     | 58        | 18.47%  |
| 3     | 51        | 16.24%  |
| 4     | 42        | 13.38%  |
| 6     | 21        | 6.69%   |
| 5     | 18        | 5.73%   |
| 0     | 6         | 1.91%   |
| 14    | 1         | 0.32%   |
| 10    | 1         | 0.32%   |
| 8     | 1         | 0.32%   |
| 7     | 1         | 0.32%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 306       | 98.39%  |
| Yes  | 5         | 1.61%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 55        | 61.8%   |
| Broadcom                        | 8         | 8.99%   |
| IMC Networks                    | 4         | 4.49%   |
| Qualcomm Atheros Communications | 3         | 3.37%   |
| Foxconn / Hon Hai               | 3         | 3.37%   |
| Cambridge Silicon Radio         | 3         | 3.37%   |
| ASUSTek Computer                | 3         | 3.37%   |
| Realtek Semiconductor           | 2         | 2.25%   |
| Dell                            | 2         | 2.25%   |
| Apple                           | 2         | 2.25%   |
| TP-Link                         | 1         | 1.12%   |
| Qcom                            | 1         | 1.12%   |
| Lite-On Technology              | 1         | 1.12%   |
| Hewlett-Packard                 | 1         | 1.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                       | 21        | 23.6%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 14        | 15.73%  |
| Intel AX201 Bluetooth                                    | 8         | 8.99%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]       | 5         | 5.62%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 3         | 3.37%   |
| Intel AX200 Bluetooth                                    | 3         | 3.37%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 3         | 3.37%   |
| Intel Wireless-AC 3168 Bluetooth                         | 2         | 2.25%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter         | 2         | 2.25%   |
| TP-Link Bluetooth 5.0 USB Adapter                        | 1         | 1.12%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                  | 1         | 1.12%   |
| Realtek Bluetooth 4.2 Adapter                            | 1         | 1.12%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                   | 1         | 1.12%   |
| Qualcomm Atheros Dell Wireless 1601 Bluetooth Device     | 1         | 1.12%   |
| Qualcomm Atheros AR9462 Bluetooth                        | 1         | 1.12%   |
| Qcom Broadcom BCM2070 Bluetooth 2.1+EDR USB Device       | 1         | 1.12%   |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS              | 1         | 1.12%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 1         | 1.12%   |
| Intel AX210 Bluetooth                                    | 1         | 1.12%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip     | 1         | 1.12%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS         | 1         | 1.12%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter        | 1         | 1.12%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011]   | 1         | 1.12%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter               | 1         | 1.12%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device | 1         | 1.12%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth            | 1         | 1.12%   |
| Foxconn / Hon Hai Bluetooth USB Module                   | 1         | 1.12%   |
| Dell DW375 Bluetooth Module                              | 1         | 1.12%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module              | 1         | 1.12%   |
| Broadcom BCM43142A0 Bluetooth Module                     | 1         | 1.12%   |
| Broadcom BCM43142A0 Bluetooth 4.0                        | 1         | 1.12%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]               | 1         | 1.12%   |
| ASUS USB-BT500                                           | 1         | 1.12%   |
| ASUS BT-253 Bluetooth Adapter                            | 1         | 1.12%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 1         | 1.12%   |
| Apple Broadcom Built-in Bluetooth                        | 1         | 1.12%   |
| Apple Bluetooth Host Controller                          | 1         | 1.12%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 192       | 69.31%  |
| AMD                   | 51        | 18.41%  |
| Nvidia                | 23        | 8.3%    |
| VIA Technologies      | 2         | 0.72%   |
| Creative Labs         | 2         | 0.72%   |
| C-Media Electronics   | 2         | 0.72%   |
| ROCCAT                | 1         | 0.36%   |
| Realtek Semiconductor | 1         | 0.36%   |
| Logitech              | 1         | 0.36%   |
| Kingston Technology   | 1         | 0.36%   |
| Creative Technology   | 1         | 0.36%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 20        | 5.9%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 18        | 5.31%   |
| AMD Kabini HDMI/DP Audio                                                                          | 18        | 5.31%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 17        | 5.01%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 16        | 4.72%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 14        | 4.13%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 12        | 3.54%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 12        | 3.54%   |
| Intel Cannon Lake PCH cAVS                                                                        | 11        | 3.24%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 11        | 3.24%   |
| AMD FCH Azalia Controller                                                                         | 11        | 3.24%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 11        | 3.24%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 8         | 2.36%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 2.36%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 2.06%   |
| Intel Jasper Lake HD Audio                                                                        | 6         | 1.77%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 1.77%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 1.77%   |
| Intel 200 Series PCH HD Audio                                                                     | 6         | 1.77%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6         | 1.77%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 6         | 1.77%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 5         | 1.47%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 1.47%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 1.47%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 1.47%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 5         | 1.47%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 1.18%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 1.18%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1.18%   |
| AMD Wrestler HDMI Audio                                                                           | 4         | 1.18%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 4         | 1.18%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 1.18%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 0.88%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 3         | 0.88%   |
| AMD Navi 10 HDMI Audio                                                                            | 3         | 0.88%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 2         | 0.59%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 0.59%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.59%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 0.59%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 2         | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 74        | 23.2%   |
| SK hynix            | 54        | 16.93%  |
| Kingston            | 47        | 14.73%  |
| Unknown             | 29        | 9.09%   |
| Micron Technology   | 25        | 7.84%   |
| GOODRAM             | 19        | 5.96%   |
| Crucial             | 13        | 4.08%   |
| G.Skill             | 9         | 2.82%   |
| Corsair             | 7         | 2.19%   |
| Ramaxel Technology  | 6         | 1.88%   |
| Unknown             | 5         | 1.57%   |
| Patriot             | 4         | 1.25%   |
| Nanya Technology    | 4         | 1.25%   |
| Wilk                | 3         | 0.94%   |
| Toshiba             | 3         | 0.94%   |
| Transcend           | 2         | 0.63%   |
| Hewlett-Packard     | 2         | 0.63%   |
| Unknown (ABCD)      | 1         | 0.31%   |
| Unknown (07FB)      | 1         | 0.31%   |
| Team                | 1         | 0.31%   |
| Qimonda             | 1         | 0.31%   |
| PUSKILL             | 1         | 0.31%   |
| Lexar Co Limited    | 1         | 0.31%   |
| Kimtigo             | 1         | 0.31%   |
| Innodisk            | 1         | 0.31%   |
| GeIL                | 1         | 0.31%   |
| Elpida              | 1         | 0.31%   |
| ATP                 | 1         | 0.31%   |
| A-DATA Technology   | 1         | 0.31%   |
| A-DA                | 1         | 0.31%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Samsung RAM M393B1G70QH0-YK0 8192MB DIMM DDR3 1600MT/s    | 15        | 4.41%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s     | 6         | 1.76%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s         | 5         | 1.47%   |
| Unknown                                                   | 5         | 1.47%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                      | 4         | 1.18%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s    | 4         | 1.18%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 4         | 1.18%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s     | 4         | 1.18%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                 | 3         | 0.88%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s      | 3         | 0.88%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 3         | 0.88%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s      | 3         | 0.88%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s    | 3         | 0.88%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 3         | 0.88%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s     | 3         | 0.88%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s     | 3         | 0.88%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                 | 2         | 0.59%   |
| Toshiba RAM KKN2NM-MIE 4GB SODIMM DDR4 2666MT/s           | 2         | 0.59%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 2         | 0.59%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 2         | 0.59%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 2         | 0.59%   |
| SK hynix RAM HMT351R7BFR8A-H9 4GB DIMM DDR3 1333MT/s      | 2         | 0.59%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s    | 2         | 0.59%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s    | 2         | 0.59%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s     | 2         | 0.59%   |
| Samsung RAM M471B5674EB0-YK0 2GB SODIMM DDR3 1600MT/s     | 2         | 0.59%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM 1067MT/s          | 2         | 0.59%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s     | 2         | 0.59%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s     | 2         | 0.59%   |
| Samsung RAM M471B1G73BH0-CK0 8GB SODIMM DDR3 1600MT/s     | 2         | 0.59%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s     | 2         | 0.59%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s | 2         | 0.59%   |
| Patriot RAM 1600 CL9 Series 8GB DIMM DDR3 1600MT/s        | 2         | 0.59%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                | 2         | 0.59%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s     | 2         | 0.59%   |
| Micron RAM 16ATF2G64HZ-2G3H1 16GB SODIMM DDR4 2400MT/s    | 2         | 0.59%   |
| Kingston RAM Module 2GB DIMM DDR3 1333MT/s                | 2         | 0.59%   |
| Kingston RAM KHX1866C11S3L/4G 4GB SODIMM DDR3 1866MT/s    | 2         | 0.59%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s       | 2         | 0.59%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s   | 2         | 0.59%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 152       | 53.9%   |
| DDR4    | 102       | 36.17%  |
| DDR2    | 8         | 2.84%   |
| Unknown | 7         | 2.48%   |
| SDRAM   | 3         | 1.06%   |
| LPDDR4  | 3         | 1.06%   |
| LPDDR3  | 3         | 1.06%   |
| DDR     | 2         | 0.71%   |
| DRAM    | 1         | 0.35%   |
| DDR5    | 1         | 0.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 142       | 50.71%  |
| DIMM         | 131       | 46.79%  |
| Row Of Chips | 3         | 1.07%   |
| Unknown      | 2         | 0.71%   |
| RIMM         | 1         | 0.36%   |
| FB-DIMM      | 1         | 0.36%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 111       | 36.88%  |
| 4096  | 103       | 34.22%  |
| 2048  | 47        | 15.61%  |
| 16384 | 27        | 8.97%   |
| 1024  | 9         | 2.99%   |
| 32768 | 2         | 0.66%   |
| 512   | 2         | 0.66%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 97        | 32.33%  |
| 2400    | 43        | 14.33%  |
| 1333    | 37        | 12.33%  |
| 2667    | 22        | 7.33%   |
| 3200    | 21        | 7%      |
| 2133    | 16        | 5.33%   |
| 800     | 9         | 3%      |
| 1867    | 7         | 2.33%   |
| 1334    | 7         | 2.33%   |
| 667     | 7         | 2.33%   |
| 1067    | 6         | 2%      |
| 2666    | 5         | 1.67%   |
| 1066    | 5         | 1.67%   |
| Unknown | 5         | 1.67%   |
| 1866    | 4         | 1.33%   |
| 5200    | 1         | 0.33%   |
| 4267    | 1         | 0.33%   |
| 3600    | 1         | 0.33%   |
| 3333    | 1         | 0.33%   |
| 3000    | 1         | 0.33%   |
| 2933    | 1         | 0.33%   |
| 2048    | 1         | 0.33%   |
| 533     | 1         | 0.33%   |
| 400     | 1         | 0.33%   |

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
| Chicony Electronics                    | 26        | 42.62%  |
| Microdia                               | 9         | 14.75%  |
| Realtek Semiconductor                  | 5         | 8.2%    |
| Bison Electronics                      | 4         | 6.56%   |
| IMC Networks                           | 3         | 4.92%   |
| Sunplus Innovation Technology          | 2         | 3.28%   |
| Ricoh                                  | 2         | 3.28%   |
| Logitech                               | 2         | 3.28%   |
| Lite-On Technology                     | 2         | 3.28%   |
| Syntek                                 | 1         | 1.64%   |
| Suyin                                  | 1         | 1.64%   |
| Hewlett-Packard                        | 1         | 1.64%   |
| DigiTech                               | 1         | 1.64%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.64%   |
| Apple                                  | 1         | 1.64%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 6         | 9.84%   |
| Chicony Realtek DMFT RGB                                       | 4         | 6.56%   |
| Realtek Lenovo EasyCamera                                      | 3         | 4.92%   |
| Microdia Integrated Webcam                                     | 3         | 4.92%   |
| Microdia Integrated_Webcam_HD                                  | 2         | 3.28%   |
| Logitech HD Pro Webcam C920                                    | 2         | 3.28%   |
| Lite-On Integrated Camera                                      | 2         | 3.28%   |
| IMC Networks Integrated Camera                                 | 2         | 3.28%   |
| Chicony Integrated Camera [ThinkPad]                           | 2         | 3.28%   |
| Chicony Integrated Camera (1280x720@30)                        | 2         | 3.28%   |
| Syntek Lenovo EasyCamera                                       | 1         | 1.64%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 1         | 1.64%   |
| Sunplus Integrated_Webcam_HD                                   | 1         | 1.64%   |
| Sunplus Integrated_Webcam_FHD                                  | 1         | 1.64%   |
| Ricoh Integrated Webcam                                        | 1         | 1.64%   |
| Ricoh HD Webcam                                                | 1         | 1.64%   |
| Realtek Integrated_Webcam_HD                                   | 1         | 1.64%   |
| Realtek HD WebCam                                              | 1         | 1.64%   |
| Microdia USB 2.0 Camera                                        | 1         | 1.64%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 1         | 1.64%   |
| Microdia Integrated HD Webcam                                  | 1         | 1.64%   |
| Microdia Dell Integrated HD Webcam                             | 1         | 1.64%   |
| IMC Networks EasyCamera                                        | 1         | 1.64%   |
| HP Premium Starter Webcam                                      | 1         | 1.64%   |
| DigiTech WebCam SCB-0350M                                      | 1         | 1.64%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 1         | 1.64%   |
| Chicony ThinkPad T490 Webcam                                   | 1         | 1.64%   |
| Chicony HP Wide Vision HD Camera                               | 1         | 1.64%   |
| Chicony HP Integrated Webcam                                   | 1         | 1.64%   |
| Chicony HP HD Webcam [Fixed]                                   | 1         | 1.64%   |
| Chicony HP HD Webcam                                           | 1         | 1.64%   |
| Chicony HP HD Camera                                           | 1         | 1.64%   |
| Chicony HD WebCam                                              | 1         | 1.64%   |
| Chicony Front Camera                                           | 1         | 1.64%   |
| Chicony FJ Camera                                              | 1         | 1.64%   |
| Chicony 1.3M Webcam                                            | 1         | 1.64%   |
| Chicony 1.3 MPixel UVC Webcam                                  | 1         | 1.64%   |
| Cheng Uei Precision Industry (Foxlink) USB 2.0 UVC 1.3M WebCam | 1         | 1.64%   |
| Bison USB HD Webcam                                            | 1         | 1.64%   |
| Bison Lenovo EasyCamera                                        | 1         | 1.64%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 6         | 33.33%  |
| AuthenTec                  | 4         | 22.22%  |
| Validity Sensors           | 3         | 16.67%  |
| Broadcom                   | 3         | 16.67%  |
| STMicroelectronics         | 1         | 5.56%   |
| Shenzhen Goodix Technology | 1         | 5.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 4         | 22.22%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 16.67%  |
| AuthenTec AES2810                                                            | 3         | 16.67%  |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 2         | 11.11%  |
| Validity Sensors Fingerprint scanner                                         | 1         | 5.56%   |
| Synaptics WBDI                                                               | 1         | 5.56%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 1         | 5.56%   |
| STMicroelectronics Fingerprint Reader                                        | 1         | 5.56%   |
| Shenzhen Goodix Fingerprint Reader                                           | 1         | 5.56%   |
| AuthenTec AES2660                                                            | 1         | 5.56%   |

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
| 1     | 132       | 42.17%  |
| 0     | 88        | 28.12%  |
| 2     | 65        | 20.77%  |
| 3     | 18        | 5.75%   |
| 4     | 6         | 1.92%   |
| 5     | 3         | 0.96%   |
| 6     | 1         | 0.32%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 196       | 61.83%  |
| Bluetooth                | 32        | 10.09%  |
| Net/wireless             | 26        | 8.2%    |
| Fingerprint reader       | 17        | 5.36%   |
| Card reader              | 17        | 5.36%   |
| Graphics card            | 10        | 3.15%   |
| Firewire controller      | 7         | 2.21%   |
| Network                  | 4         | 1.26%   |
| Net/ethernet             | 3         | 0.95%   |
| Sound                    | 2         | 0.63%   |
| Storage/nvme             | 1         | 0.32%   |
| Storage                  | 1         | 0.32%   |
| Modem                    | 1         | 0.32%   |

