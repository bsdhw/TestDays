BSD in USA - Tested Hardware & Statistics
-----------------------------------------

A project to collect tested hardware configurations for BSD in USA.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/USA/Desktop/README.md) and [notebooks](/Location/USA/Notebook/README.md).

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

Total: 5732

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| AZW           | U59                         | Desktop     | [c8ffb92584](https://bsd-hardware.info/?probe=c8ffb92584) | Jan 02, 2024 |
| Lenovo        | ThinkPad T490s 20NX000MU... | Notebook    | [1271688c43](https://bsd-hardware.info/?probe=1271688c43) | Jan 02, 2024 |
| AWOW          | AZ51                        | Mini pc     | [2dc5c759ac](https://bsd-hardware.info/?probe=2dc5c759ac) | Jan 02, 2024 |
| Protectli     | VP46xx                      | Desktop     | [f958569c30](https://bsd-hardware.info/?probe=f958569c30) | Jan 02, 2024 |
| Gowin Solu... | GW-MB-U01                   | Desktop     | [673266d486](https://bsd-hardware.info/?probe=673266d486) | Jan 01, 2024 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [270a946916](https://bsd-hardware.info/?probe=270a946916) | Jan 01, 2024 |
| Alienware     | 07HV66 A00                  | Desktop     | [ea6a3f3020](https://bsd-hardware.info/?probe=ea6a3f3020) | Jan 01, 2024 |
| Protectli     | FW4B Ver                    | Desktop     | [3191952740](https://bsd-hardware.info/?probe=3191952740) | Jan 01, 2024 |
| MSI           | Z170A PC MATE               | Desktop     | [e05af13af9](https://bsd-hardware.info/?probe=e05af13af9) | Jan 01, 2024 |
| MSI           | Z270-A PRO                  | Desktop     | [2f2f406aa3](https://bsd-hardware.info/?probe=2f2f406aa3) | Dec 31, 2023 |
| MSI           | H81M-P33                    | Desktop     | [82e08820f2](https://bsd-hardware.info/?probe=82e08820f2) | Dec 31, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [da3b88ef85](https://bsd-hardware.info/?probe=da3b88ef85) | Dec 31, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [391f4c0e0b](https://bsd-hardware.info/?probe=391f4c0e0b) | Dec 31, 2023 |
| GEEK+         | Mini PC                     | Mini pc     | [9e550a39c1](https://bsd-hardware.info/?probe=9e550a39c1) | Dec 31, 2023 |
| Intel         | SHARKBAY                    | Desktop     | [bcbbfa0368](https://bsd-hardware.info/?probe=bcbbfa0368) | Dec 31, 2023 |
| Unknown       | Unknown                     | Desktop     | [56ecba336a](https://bsd-hardware.info/?probe=56ecba336a) | Dec 31, 2023 |
| ASUSTek       | CM6870                      | Desktop     | [1889675f37](https://bsd-hardware.info/?probe=1889675f37) | Dec 30, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI D... | Desktop     | [715a274a2e](https://bsd-hardware.info/?probe=715a274a2e) | Dec 30, 2023 |
| Protectli     | FW4A Ver                    | Desktop     | [39c4ea3a24](https://bsd-hardware.info/?probe=39c4ea3a24) | Dec 30, 2023 |
| HP            | 3397                        | Desktop     | [46b6923bcd](https://bsd-hardware.info/?probe=46b6923bcd) | Dec 30, 2023 |
| Protectli     | FW2B Ver                    | Desktop     | [3dbf91e1d4](https://bsd-hardware.info/?probe=3dbf91e1d4) | Dec 30, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [e235575d34](https://bsd-hardware.info/?probe=e235575d34) | Dec 30, 2023 |
| Unknown       | QDNV01                      | Desktop     | [d2fed4bb5f](https://bsd-hardware.info/?probe=d2fed4bb5f) | Dec 30, 2023 |
| HP            | 82B4                        | Desktop     | [de6046d060](https://bsd-hardware.info/?probe=de6046d060) | Dec 29, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [49375afedd](https://bsd-hardware.info/?probe=49375afedd) | Dec 29, 2023 |
| PC Engines    | apu4                        | Desktop     | [3901782984](https://bsd-hardware.info/?probe=3901782984) | Dec 29, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [e54393775b](https://bsd-hardware.info/?probe=e54393775b) | Dec 29, 2023 |
| Deciso        | Netboard A20                | Notebook    | [c545672f6f](https://bsd-hardware.info/?probe=c545672f6f) | Dec 28, 2023 |
| Protectli     | VP2420                      | Desktop     | [39b80f6d35](https://bsd-hardware.info/?probe=39b80f6d35) | Dec 28, 2023 |
| HP            | 0B54h D                     | Desktop     | [0fc53a659f](https://bsd-hardware.info/?probe=0fc53a659f) | Dec 28, 2023 |
| Intel         | SHARKBAY                    | Desktop     | [55a9dc404b](https://bsd-hardware.info/?probe=55a9dc404b) | Dec 27, 2023 |
| Protectli     | VP2420                      | Desktop     | [a7e60ab925](https://bsd-hardware.info/?probe=a7e60ab925) | Dec 27, 2023 |
| HP            | 1998                        | Desktop     | [8bebbb8dab](https://bsd-hardware.info/?probe=8bebbb8dab) | Dec 27, 2023 |
| MSI           | Aspen                       | Desktop     | [ac6dd2b153](https://bsd-hardware.info/?probe=ac6dd2b153) | Dec 27, 2023 |
| Protectli     | FW4B                        | Desktop     | [cf4ead1922](https://bsd-hardware.info/?probe=cf4ead1922) | Dec 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [48677111e5](https://bsd-hardware.info/?probe=48677111e5) | Dec 26, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [d08712b71d](https://bsd-hardware.info/?probe=d08712b71d) | Dec 26, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [47fdb04811](https://bsd-hardware.info/?probe=47fdb04811) | Dec 25, 2023 |
| Supermicro    | X11SDW-16C-TP13F+           | Desktop     | [49ed0c6dca](https://bsd-hardware.info/?probe=49ed0c6dca) | Dec 25, 2023 |
| Lenovo        | ThinkPad X131e 33672T9      | Notebook    | [93f964da45](https://bsd-hardware.info/?probe=93f964da45) | Dec 25, 2023 |
| Gigabyte      | Z690I A ULTRA LITE D4       | Desktop     | [304af7e00e](https://bsd-hardware.info/?probe=304af7e00e) | Dec 25, 2023 |
| Dell          | 081N4V A10                  | Server      | [62d49dec3c](https://bsd-hardware.info/?probe=62d49dec3c) | Dec 25, 2023 |
| Unknown       | QGLK03                      | Desktop     | [4be2a41109](https://bsd-hardware.info/?probe=4be2a41109) | Dec 25, 2023 |
| Unknown       | QGLK03                      | Desktop     | [b187a024cb](https://bsd-hardware.info/?probe=b187a024cb) | Dec 25, 2023 |
| Unknown       | QSKL01                      | Desktop     | [f69898815d](https://bsd-hardware.info/?probe=f69898815d) | Dec 25, 2023 |
| Lenovo        | 30D9 SDK0J40700 WIN 3258... | Desktop     | [504fb1678f](https://bsd-hardware.info/?probe=504fb1678f) | Dec 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | Notebook    | [278ab700ae](https://bsd-hardware.info/?probe=278ab700ae) | Dec 24, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [04675127c2](https://bsd-hardware.info/?probe=04675127c2) | Dec 24, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [1ef7136151](https://bsd-hardware.info/?probe=1ef7136151) | Dec 24, 2023 |
| Dell          | 0KV62T A00                  | Desktop     | [5844adb190](https://bsd-hardware.info/?probe=5844adb190) | Dec 24, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [1656e8f6b0](https://bsd-hardware.info/?probe=1656e8f6b0) | Dec 24, 2023 |
| Unknown       | QGLK03                      | Desktop     | [a586279dd0](https://bsd-hardware.info/?probe=a586279dd0) | Dec 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [da2b7d434e](https://bsd-hardware.info/?probe=da2b7d434e) | Dec 24, 2023 |
| Dell          | 01Y1CJ A00                  | Mini pc     | [69e3982549](https://bsd-hardware.info/?probe=69e3982549) | Dec 23, 2023 |
| Dell          | 01G5C3 A02                  | Server      | [7940d24d8e](https://bsd-hardware.info/?probe=7940d24d8e) | Dec 23, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [06828fbfed](https://bsd-hardware.info/?probe=06828fbfed) | Dec 23, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [3c06ec4635](https://bsd-hardware.info/?probe=3c06ec4635) | Dec 23, 2023 |
| AZW           | EQ                          | Desktop     | [9818e5f996](https://bsd-hardware.info/?probe=9818e5f996) | Dec 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [97559370a8](https://bsd-hardware.info/?probe=97559370a8) | Dec 23, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [4b6a62bebe](https://bsd-hardware.info/?probe=4b6a62bebe) | Dec 22, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [c4e5366baa](https://bsd-hardware.info/?probe=c4e5366baa) | Dec 22, 2023 |
| Dell          | Latitude E7240              | Notebook    | [f2229124bf](https://bsd-hardware.info/?probe=f2229124bf) | Dec 22, 2023 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [2463b12f4e](https://bsd-hardware.info/?probe=2463b12f4e) | Dec 22, 2023 |
| Lenovo        | ThinkPad A485 20MU000VUS    | Notebook    | [98663cbfef](https://bsd-hardware.info/?probe=98663cbfef) | Dec 22, 2023 |
| Shuttle       | FS77U                       | Desktop     | [9c746c0d5c](https://bsd-hardware.info/?probe=9c746c0d5c) | Dec 21, 2023 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [70fe8567d6](https://bsd-hardware.info/?probe=70fe8567d6) | Dec 21, 2023 |
| Dell          | 0KV62T A00                  | Desktop     | [8a2c7af96c](https://bsd-hardware.info/?probe=8a2c7af96c) | Dec 21, 2023 |
| PC Engines    | apu4                        | Desktop     | [7fa270657e](https://bsd-hardware.info/?probe=7fa270657e) | Dec 21, 2023 |
| Intel         | DH61AG AAG23736-400         | Desktop     | [e6a38faa07](https://bsd-hardware.info/?probe=e6a38faa07) | Dec 21, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [f9fd749985](https://bsd-hardware.info/?probe=f9fd749985) | Dec 21, 2023 |
| Protectli     | VP2420                      | Desktop     | [9a4aba32a7](https://bsd-hardware.info/?probe=9a4aba32a7) | Dec 21, 2023 |
| Dell          | 0NV0M7 A01                  | Desktop     | [835ca2056c](https://bsd-hardware.info/?probe=835ca2056c) | Dec 21, 2023 |
| Protectli     | FW4B                        | Desktop     | [d67b8b063a](https://bsd-hardware.info/?probe=d67b8b063a) | Dec 21, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [760c7214cc](https://bsd-hardware.info/?probe=760c7214cc) | Dec 20, 2023 |
| Apple         | PowerBook3,5                | Notebook    | [53313e58d8](https://bsd-hardware.info/?probe=53313e58d8) | Dec 20, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [6e070fbb90](https://bsd-hardware.info/?probe=6e070fbb90) | Dec 20, 2023 |
| Acer          | Aspire XC-1660G V:1.1       | Desktop     | [54b2061c80](https://bsd-hardware.info/?probe=54b2061c80) | Dec 19, 2023 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [c00a69de7c](https://bsd-hardware.info/?probe=c00a69de7c) | Dec 19, 2023 |
| Advantech     | NAMB-3250 A102-1            | Desktop     | [bb91074237](https://bsd-hardware.info/?probe=bb91074237) | Dec 19, 2023 |
| Dell          | Latitude E7240              | Notebook    | [7d5e8bcb8a](https://bsd-hardware.info/?probe=7d5e8bcb8a) | Dec 19, 2023 |
| Dell          | 04YP6J A02                  | Desktop     | [abcaede8e1](https://bsd-hardware.info/?probe=abcaede8e1) | Dec 19, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YV... | Notebook    | [10fb96c00d](https://bsd-hardware.info/?probe=10fb96c00d) | Dec 18, 2023 |
| Dell          | 04JN2K A03                  | Server      | [d56fe5aeb2](https://bsd-hardware.info/?probe=d56fe5aeb2) | Dec 18, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [c4a54e3710](https://bsd-hardware.info/?probe=c4a54e3710) | Dec 18, 2023 |
| Protectli     | FW4A Ver                    | Desktop     | [9660edcc5c](https://bsd-hardware.info/?probe=9660edcc5c) | Dec 18, 2023 |
| Unknown       | Unknown                     | Desktop     | [107e747798](https://bsd-hardware.info/?probe=107e747798) | Dec 17, 2023 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [ea3bc70906](https://bsd-hardware.info/?probe=ea3bc70906) | Dec 17, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [5a4d01667e](https://bsd-hardware.info/?probe=5a4d01667e) | Dec 17, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [ea79e98108](https://bsd-hardware.info/?probe=ea79e98108) | Dec 17, 2023 |
| ECS           | H81H3-WM                    | Desktop     | [9df1f030f9](https://bsd-hardware.info/?probe=9df1f030f9) | Dec 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [88306fe484](https://bsd-hardware.info/?probe=88306fe484) | Dec 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [6a3ef5165f](https://bsd-hardware.info/?probe=6a3ef5165f) | Dec 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [cefdf7d9ca](https://bsd-hardware.info/?probe=cefdf7d9ca) | Dec 17, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [4b134e7787](https://bsd-hardware.info/?probe=4b134e7787) | Dec 16, 2023 |
| Protectli     | FW4B                        | Desktop     | [b862c8c507](https://bsd-hardware.info/?probe=b862c8c507) | Dec 16, 2023 |
| Lenovo        | ThinkPad P1 20MD002MUS      | Notebook    | [c0dcfec41d](https://bsd-hardware.info/?probe=c0dcfec41d) | Dec 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [df97b81bea](https://bsd-hardware.info/?probe=df97b81bea) | Dec 15, 2023 |
| AZW           | MINI S 10                   | Desktop     | [d8eee18baf](https://bsd-hardware.info/?probe=d8eee18baf) | Dec 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [5adc44e122](https://bsd-hardware.info/?probe=5adc44e122) | Dec 15, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [4b7be4588e](https://bsd-hardware.info/?probe=4b7be4588e) | Dec 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [93f650efc3](https://bsd-hardware.info/?probe=93f650efc3) | Dec 15, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [9773ffcc27](https://bsd-hardware.info/?probe=9773ffcc27) | Dec 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [a9f96c677c](https://bsd-hardware.info/?probe=a9f96c677c) | Dec 14, 2023 |
| CWWK          | MINIPC-G12                  | Desktop     | [e15a019715](https://bsd-hardware.info/?probe=e15a019715) | Dec 14, 2023 |
| Dell          | 0NK5PH A00                  | Desktop     | [60451d4e43](https://bsd-hardware.info/?probe=60451d4e43) | Dec 14, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [bc50d301fa](https://bsd-hardware.info/?probe=bc50d301fa) | Dec 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [dced442907](https://bsd-hardware.info/?probe=dced442907) | Dec 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [b2407b8a31](https://bsd-hardware.info/?probe=b2407b8a31) | Dec 13, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [12e42ebd6d](https://bsd-hardware.info/?probe=12e42ebd6d) | Dec 13, 2023 |
| Dell          | 02YYK5 A00                  | Desktop     | [8eb8c9eff3](https://bsd-hardware.info/?probe=8eb8c9eff3) | Dec 13, 2023 |
| Google        | Lindar rev3                 | Notebook    | [2e748fc42c](https://bsd-hardware.info/?probe=2e748fc42c) | Dec 13, 2023 |
| Intel         | QHSW02                      | Desktop     | [da6b7c7115](https://bsd-hardware.info/?probe=da6b7c7115) | Dec 13, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F6... | Notebook    | [a7fcca51be](https://bsd-hardware.info/?probe=a7fcca51be) | Dec 13, 2023 |
| ASRock        | H170M-ITX/DL                | Desktop     | [79039f6105](https://bsd-hardware.info/?probe=79039f6105) | Dec 13, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [09f5b25e72](https://bsd-hardware.info/?probe=09f5b25e72) | Dec 12, 2023 |
| MSI           | B150 GAMING M3              | Desktop     | [b5dc4da596](https://bsd-hardware.info/?probe=b5dc4da596) | Dec 12, 2023 |
| Dell          | 0DRG19 A00                  | Mini pc     | [c26ebe6c80](https://bsd-hardware.info/?probe=c26ebe6c80) | Dec 12, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI D... | Desktop     | [c05c574f37](https://bsd-hardware.info/?probe=c05c574f37) | Dec 12, 2023 |
| EVGA          | X570 DARK.0                 | Desktop     | [1c84a8169b](https://bsd-hardware.info/?probe=1c84a8169b) | Dec 11, 2023 |
| HP            | 8103 A01                    | Mini pc     | [e2f44ab91e](https://bsd-hardware.info/?probe=e2f44ab91e) | Dec 11, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [becfed036a](https://bsd-hardware.info/?probe=becfed036a) | Dec 11, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [68f73bf8ba](https://bsd-hardware.info/?probe=68f73bf8ba) | Dec 11, 2023 |
| ASRock        | H370M-ITX/ac                | Desktop     | [b806cc2a41](https://bsd-hardware.info/?probe=b806cc2a41) | Dec 10, 2023 |
| AZW           | EQ                          | Desktop     | [0280c1cdb9](https://bsd-hardware.info/?probe=0280c1cdb9) | Dec 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [ec8c50c128](https://bsd-hardware.info/?probe=ec8c50c128) | Dec 10, 2023 |
| AZW           | EQ                          | Desktop     | [48537a5985](https://bsd-hardware.info/?probe=48537a5985) | Dec 10, 2023 |
| ASUSTek       | CM6870                      | Desktop     | [881ad2eacf](https://bsd-hardware.info/?probe=881ad2eacf) | Dec 10, 2023 |
| Dell          | 0YNVJG A02                  | Desktop     | [2d8992cd50](https://bsd-hardware.info/?probe=2d8992cd50) | Dec 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [fc1097e9b0](https://bsd-hardware.info/?probe=fc1097e9b0) | Dec 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [3e478d7459](https://bsd-hardware.info/?probe=3e478d7459) | Dec 10, 2023 |
| Deciso        | NetBoard-A20                | Notebook    | [06e5f53429](https://bsd-hardware.info/?probe=06e5f53429) | Dec 10, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [8dd13bf91f](https://bsd-hardware.info/?probe=8dd13bf91f) | Dec 10, 2023 |
| MSI           | H81M-P33                    | Desktop     | [2b1599aacd](https://bsd-hardware.info/?probe=2b1599aacd) | Dec 10, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [89f0463ec6](https://bsd-hardware.info/?probe=89f0463ec6) | Dec 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [edfa10c0dd](https://bsd-hardware.info/?probe=edfa10c0dd) | Dec 10, 2023 |
| Google        | Parrot                      | Notebook    | [c10a95cbcc](https://bsd-hardware.info/?probe=c10a95cbcc) | Dec 10, 2023 |
| ASRock        | B660M Phantom Gaming 4      | Desktop     | [e71ffa9a86](https://bsd-hardware.info/?probe=e71ffa9a86) | Dec 10, 2023 |
| Google        | Parrot                      | Notebook    | [3a69ea2682](https://bsd-hardware.info/?probe=3a69ea2682) | Dec 10, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [a03446d994](https://bsd-hardware.info/?probe=a03446d994) | Dec 10, 2023 |
| ASRock        | Q1900B-ITX                  | Desktop     | [b7e23a4ed4](https://bsd-hardware.info/?probe=b7e23a4ed4) | Dec 10, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [3b6c1c2fbb](https://bsd-hardware.info/?probe=3b6c1c2fbb) | Dec 09, 2023 |
| ASUSTek       | CM6870                      | Desktop     | [78399ba39e](https://bsd-hardware.info/?probe=78399ba39e) | Dec 09, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [05acf05b44](https://bsd-hardware.info/?probe=05acf05b44) | Dec 09, 2023 |
| Gigabyte      | B650 AORUS ELITE AX V2      | Desktop     | [7a6cdb3f06](https://bsd-hardware.info/?probe=7a6cdb3f06) | Dec 09, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [55094840ea](https://bsd-hardware.info/?probe=55094840ea) | Dec 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [76f58e8986](https://bsd-hardware.info/?probe=76f58e8986) | Dec 09, 2023 |
| Dell          | 0DRG19 A00                  | Mini pc     | [0674ed24ed](https://bsd-hardware.info/?probe=0674ed24ed) | Dec 09, 2023 |
| Dell          | 0D28YY A00                  | Desktop     | [20dbd4481a](https://bsd-hardware.info/?probe=20dbd4481a) | Dec 09, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [8422bc152b](https://bsd-hardware.info/?probe=8422bc152b) | Dec 08, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [a0591ac105](https://bsd-hardware.info/?probe=a0591ac105) | Dec 08, 2023 |
| ASRock        | Z370 Gaming K6              | Desktop     | [2074ab8412](https://bsd-hardware.info/?probe=2074ab8412) | Dec 08, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [050e7d8c01](https://bsd-hardware.info/?probe=050e7d8c01) | Dec 08, 2023 |
| Dell          | 081N4V A08                  | Server      | [3aba7cf14e](https://bsd-hardware.info/?probe=3aba7cf14e) | Dec 08, 2023 |
| Supermicro    | X11SDV-4C-TP8F              | Desktop     | [cf3304bda2](https://bsd-hardware.info/?probe=cf3304bda2) | Dec 08, 2023 |
| Dell          | 03NVJ6 A03                  | Desktop     | [c119d3003e](https://bsd-hardware.info/?probe=c119d3003e) | Dec 07, 2023 |
| Protectli     | VP46xx                      | Desktop     | [5051678913](https://bsd-hardware.info/?probe=5051678913) | Dec 07, 2023 |
| PC Engines    | APU2                        | Desktop     | [92c3ba510a](https://bsd-hardware.info/?probe=92c3ba510a) | Dec 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [23b689f778](https://bsd-hardware.info/?probe=23b689f778) | Dec 07, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [c906f764b0](https://bsd-hardware.info/?probe=c906f764b0) | Dec 07, 2023 |
| HP            | 213D A01                    | Desktop     | [a7ded310e3](https://bsd-hardware.info/?probe=a7ded310e3) | Dec 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [a11b04691d](https://bsd-hardware.info/?probe=a11b04691d) | Dec 07, 2023 |
| Sony          | VJS122C11L                  | Notebook    | [7d100c8e2c](https://bsd-hardware.info/?probe=7d100c8e2c) | Dec 06, 2023 |
| Dell          | 0CN7X8 A01                  | Server      | [82ff66fb79](https://bsd-hardware.info/?probe=82ff66fb79) | Dec 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [ac7f59dc32](https://bsd-hardware.info/?probe=ac7f59dc32) | Dec 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [ef425e8732](https://bsd-hardware.info/?probe=ef425e8732) | Dec 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [2301bb487f](https://bsd-hardware.info/?probe=2301bb487f) | Dec 05, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [8c023b9c33](https://bsd-hardware.info/?probe=8c023b9c33) | Dec 05, 2023 |
| CWWK          | MINIPC-G12                  | Desktop     | [d6c18203b4](https://bsd-hardware.info/?probe=d6c18203b4) | Dec 04, 2023 |
| Lenovo        | XXXX FFFFFFFFFF             | Desktop     | [780619812e](https://bsd-hardware.info/?probe=780619812e) | Dec 04, 2023 |
| Lenovo        | XXXX FFFFFFFFFF             | Desktop     | [7ddfbf4af2](https://bsd-hardware.info/?probe=7ddfbf4af2) | Dec 04, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [267d300e4a](https://bsd-hardware.info/?probe=267d300e4a) | Dec 04, 2023 |
| Dell          | 01G5C3 A02                  | Server      | [c5e25db7f9](https://bsd-hardware.info/?probe=c5e25db7f9) | Dec 04, 2023 |
| GoWin Solu... | R86S                        | Desktop     | [494f638f4e](https://bsd-hardware.info/?probe=494f638f4e) | Dec 04, 2023 |
| Protectli     | FW6                         | Desktop     | [91d91ebf31](https://bsd-hardware.info/?probe=91d91ebf31) | Dec 04, 2023 |
| MiTAC         | UltraPoint                  | Desktop     | [346d03e78c](https://bsd-hardware.info/?probe=346d03e78c) | Dec 04, 2023 |
| HP            | 8715                        | Mini pc     | [262c6ee87c](https://bsd-hardware.info/?probe=262c6ee87c) | Dec 03, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [2fefe41bcd](https://bsd-hardware.info/?probe=2fefe41bcd) | Dec 03, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [d04fd54963](https://bsd-hardware.info/?probe=d04fd54963) | Dec 03, 2023 |
| AZW           | MINI S 10                   | Desktop     | [caf105bd1b](https://bsd-hardware.info/?probe=caf105bd1b) | Dec 02, 2023 |
| Intel         | D33217GKE G76540-207        | Desktop     | [761e1e0eae](https://bsd-hardware.info/?probe=761e1e0eae) | Dec 02, 2023 |
| Dell          | 0VRWRC A00                  | Desktop     | [8ffbff07d4](https://bsd-hardware.info/?probe=8ffbff07d4) | Dec 02, 2023 |
| HP            | 8265                        | Desktop     | [ec9e6fdd6e](https://bsd-hardware.info/?probe=ec9e6fdd6e) | Dec 02, 2023 |
| Protectli     | FW4C                        | Desktop     | [c3b8887f26](https://bsd-hardware.info/?probe=c3b8887f26) | Dec 02, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [baf3e413d0](https://bsd-hardware.info/?probe=baf3e413d0) | Dec 01, 2023 |
| AZW           | EQ                          | Desktop     | [1f66e98633](https://bsd-hardware.info/?probe=1f66e98633) | Dec 01, 2023 |
| ASRock        | H110M-HDS                   | Desktop     | [519a82f253](https://bsd-hardware.info/?probe=519a82f253) | Dec 01, 2023 |
| Dell          | 081N4V A10                  | Server      | [46338756b8](https://bsd-hardware.info/?probe=46338756b8) | Nov 30, 2023 |
| Dell          | 0XN8Y6 A12                  | Server      | [3c8b7cfb27](https://bsd-hardware.info/?probe=3c8b7cfb27) | Nov 30, 2023 |
| AZW           | EQ                          | Desktop     | [a2f18cb86e](https://bsd-hardware.info/?probe=a2f18cb86e) | Nov 30, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [78fef35503](https://bsd-hardware.info/?probe=78fef35503) | Nov 30, 2023 |
| Silver Pea... | Unknown                     | Firewall    | [405efa1824](https://bsd-hardware.info/?probe=405efa1824) | Nov 30, 2023 |
| MUCAI         | H61 V1.6A                   | Desktop     | [8dfd16da29](https://bsd-hardware.info/?probe=8dfd16da29) | Nov 29, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [f3a2321558](https://bsd-hardware.info/?probe=f3a2321558) | Nov 29, 2023 |
| Deciso        | Netboard A8                 | Desktop     | [53d89587d0](https://bsd-hardware.info/?probe=53d89587d0) | Nov 28, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [d45a39836c](https://bsd-hardware.info/?probe=d45a39836c) | Nov 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [97fc765ff5](https://bsd-hardware.info/?probe=97fc765ff5) | Nov 28, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [30e336f42f](https://bsd-hardware.info/?probe=30e336f42f) | Nov 28, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [be0344dcf2](https://bsd-hardware.info/?probe=be0344dcf2) | Nov 28, 2023 |
| Supermicro    | X10SDV-TP8F                 | Server      | [b132017cc8](https://bsd-hardware.info/?probe=b132017cc8) | Nov 27, 2023 |
| GoWin Solu... | R86S-N                      | Desktop     | [1d40615c24](https://bsd-hardware.info/?probe=1d40615c24) | Nov 27, 2023 |
| WTM           | BKHD-N5105-5LAN B0          | Desktop     | [4d58c53d68](https://bsd-hardware.info/?probe=4d58c53d68) | Nov 27, 2023 |
| Lenovo        | ThinkServer TS140           | Desktop     | [af326ddda5](https://bsd-hardware.info/?probe=af326ddda5) | Nov 27, 2023 |
| Lenovo        | 1036 NO DPK                 | Desktop     | [3b18ff26c0](https://bsd-hardware.info/?probe=3b18ff26c0) | Nov 27, 2023 |
| Dell          | Inspiron 7558               | Notebook    | [b34a8742d5](https://bsd-hardware.info/?probe=b34a8742d5) | Nov 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [14c7b94add](https://bsd-hardware.info/?probe=14c7b94add) | Nov 26, 2023 |
| Intel         | D33217GKE G76540-207        | Desktop     | [9b0af83da8](https://bsd-hardware.info/?probe=9b0af83da8) | Nov 26, 2023 |
| MSI           | H81M-P33                    | Desktop     | [b653e75063](https://bsd-hardware.info/?probe=b653e75063) | Nov 26, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [1454187842](https://bsd-hardware.info/?probe=1454187842) | Nov 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [28f6ec2a7b](https://bsd-hardware.info/?probe=28f6ec2a7b) | Nov 26, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [7241023750](https://bsd-hardware.info/?probe=7241023750) | Nov 26, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [268228d2b7](https://bsd-hardware.info/?probe=268228d2b7) | Nov 26, 2023 |
| Dell          | 03X6X0 A03                  | Server      | [238143f959](https://bsd-hardware.info/?probe=238143f959) | Nov 26, 2023 |
| Dell          | 0XCR8D A01                  | Desktop     | [de52fe9aef](https://bsd-hardware.info/?probe=de52fe9aef) | Nov 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [c3dc51f3fe](https://bsd-hardware.info/?probe=c3dc51f3fe) | Nov 25, 2023 |
| Dell          | Latitude E5540              | Notebook    | [d12acc0425](https://bsd-hardware.info/?probe=d12acc0425) | Nov 25, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [be568b54bf](https://bsd-hardware.info/?probe=be568b54bf) | Nov 25, 2023 |
| HP            | 8103 A01                    | Mini pc     | [de7a23f9ca](https://bsd-hardware.info/?probe=de7a23f9ca) | Nov 25, 2023 |
| HP            | 8103 A01                    | Mini pc     | [06217360c6](https://bsd-hardware.info/?probe=06217360c6) | Nov 25, 2023 |
| Dell          | 01Y1CJ A00                  | Mini pc     | [761475ca9e](https://bsd-hardware.info/?probe=761475ca9e) | Nov 24, 2023 |
| Dell          | Inspiron 7558               | Notebook    | [aad8d359f3](https://bsd-hardware.info/?probe=aad8d359f3) | Nov 24, 2023 |
| Dell          | 0MFXTY A01                  | Server      | [d60cd55e61](https://bsd-hardware.info/?probe=d60cd55e61) | Nov 24, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [ece72d8870](https://bsd-hardware.info/?probe=ece72d8870) | Nov 24, 2023 |
| Google        | Dragonair                   | Notebook    | [713cf1bc38](https://bsd-hardware.info/?probe=713cf1bc38) | Nov 24, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI D... | Desktop     | [b479df9cfc](https://bsd-hardware.info/?probe=b479df9cfc) | Nov 24, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [b7e6b2579a](https://bsd-hardware.info/?probe=b7e6b2579a) | Nov 24, 2023 |
| Lenovo        | ThinkPad A485 20MU000VUS    | Notebook    | [8f21b7d70f](https://bsd-hardware.info/?probe=8f21b7d70f) | Nov 24, 2023 |
| ASRock        | X399 Professional Gaming    | Desktop     | [9c9645e87a](https://bsd-hardware.info/?probe=9c9645e87a) | Nov 23, 2023 |
| Dell          | Latitude E5440              | Notebook    | [629fba28cc](https://bsd-hardware.info/?probe=629fba28cc) | Nov 23, 2023 |
| CWWK          | MINIPC-G12                  | Desktop     | [2756c10ff8](https://bsd-hardware.info/?probe=2756c10ff8) | Nov 23, 2023 |
| Dell          | 0MFXTY A01                  | Server      | [982b2609c5](https://bsd-hardware.info/?probe=982b2609c5) | Nov 23, 2023 |
| Lenovo        | 3098 SDK0E50510 WIN         | Desktop     | [d883d8bbd1](https://bsd-hardware.info/?probe=d883d8bbd1) | Nov 23, 2023 |
| Acer          | JM11-MS                     | Notebook    | [0490895189](https://bsd-hardware.info/?probe=0490895189) | Nov 23, 2023 |
| HP            | 8767 A                      | Desktop     | [12aa6c74c7](https://bsd-hardware.info/?probe=12aa6c74c7) | Nov 23, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [086dd66ae7](https://bsd-hardware.info/?probe=086dd66ae7) | Nov 22, 2023 |
| Dell          | 0GY6Y8 A00                  | Desktop     | [8181170ec9](https://bsd-hardware.info/?probe=8181170ec9) | Nov 22, 2023 |
| Cisco         | ASA5525 A0                  | Desktop     | [0e4aa1cec5](https://bsd-hardware.info/?probe=0e4aa1cec5) | Nov 22, 2023 |
| ASRock        | Z490M-ITX/ac                | Desktop     | [2c256503f5](https://bsd-hardware.info/?probe=2c256503f5) | Nov 22, 2023 |
| MUCAI         | H61 V1.6A                   | Desktop     | [f750403713](https://bsd-hardware.info/?probe=f750403713) | Nov 21, 2023 |
| CWWK          | MINIPC-G4                   | Desktop     | [d9b122a533](https://bsd-hardware.info/?probe=d9b122a533) | Nov 21, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [9f690594a0](https://bsd-hardware.info/?probe=9f690594a0) | Nov 21, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [9b3cb9cbd6](https://bsd-hardware.info/?probe=9b3cb9cbd6) | Nov 21, 2023 |
| Pegatron      | TRUCKEE                     | Desktop     | [9f4c9969f1](https://bsd-hardware.info/?probe=9f4c9969f1) | Nov 21, 2023 |
| Pegatron      | TRUCKEE                     | Desktop     | [8c8daeff55](https://bsd-hardware.info/?probe=8c8daeff55) | Nov 21, 2023 |
| Protectli     | FW4C                        | Desktop     | [7fa5301a63](https://bsd-hardware.info/?probe=7fa5301a63) | Nov 20, 2023 |
| AZW           | EQ                          | Desktop     | [cb2efd436d](https://bsd-hardware.info/?probe=cb2efd436d) | Nov 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [6e5266f2a1](https://bsd-hardware.info/?probe=6e5266f2a1) | Nov 20, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [4b6284d041](https://bsd-hardware.info/?probe=4b6284d041) | Nov 20, 2023 |
| AZW           | EQ                          | Desktop     | [adcc84f66a](https://bsd-hardware.info/?probe=adcc84f66a) | Nov 20, 2023 |
| Supermicro    | A2SAP-HA                    | Desktop     | [c912b74149](https://bsd-hardware.info/?probe=c912b74149) | Nov 20, 2023 |
| AZW           | EQ                          | Desktop     | [9f0dd7c0b4](https://bsd-hardware.info/?probe=9f0dd7c0b4) | Nov 20, 2023 |
| Dell          | 01V648 A07                  | Server      | [cb698d50c6](https://bsd-hardware.info/?probe=cb698d50c6) | Nov 20, 2023 |
| ASRock        | Z370 Gaming K6              | Desktop     | [0b219600a3](https://bsd-hardware.info/?probe=0b219600a3) | Nov 19, 2023 |
| Protectli     | VP2420                      | Desktop     | [42bac7a450](https://bsd-hardware.info/?probe=42bac7a450) | Nov 19, 2023 |
| Sophos        | SG                          | Firewall    | [516a13a5f0](https://bsd-hardware.info/?probe=516a13a5f0) | Nov 19, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [41bb4c277b](https://bsd-hardware.info/?probe=41bb4c277b) | Nov 19, 2023 |
| MSI           | H81M-P33                    | Desktop     | [6406980bbf](https://bsd-hardware.info/?probe=6406980bbf) | Nov 19, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [e7ccb4156e](https://bsd-hardware.info/?probe=e7ccb4156e) | Nov 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [a570c7994c](https://bsd-hardware.info/?probe=a570c7994c) | Nov 19, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [e6bfeee196](https://bsd-hardware.info/?probe=e6bfeee196) | Nov 19, 2023 |
| Dell          | 0Y7WYT A00                  | Desktop     | [72987e629d](https://bsd-hardware.info/?probe=72987e629d) | Nov 19, 2023 |
| Protectli     | VP2420                      | Desktop     | [05284d48bc](https://bsd-hardware.info/?probe=05284d48bc) | Nov 19, 2023 |
| Supermicro    | H8SML                       | Desktop     | [c4a58844c5](https://bsd-hardware.info/?probe=c4a58844c5) | Nov 18, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [cfbda53125](https://bsd-hardware.info/?probe=cfbda53125) | Nov 18, 2023 |
| HP            | Notebook                    | Notebook    | [c583c221c7](https://bsd-hardware.info/?probe=c583c221c7) | Nov 17, 2023 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [9ca9377fee](https://bsd-hardware.info/?probe=9ca9377fee) | Nov 17, 2023 |
| Protectli     | VP2420                      | Desktop     | [ee1cbf5fd0](https://bsd-hardware.info/?probe=ee1cbf5fd0) | Nov 17, 2023 |
| Fujitsu       | D3433-S2 S26361-D3433-S2    | Desktop     | [1b811bacb7](https://bsd-hardware.info/?probe=1b811bacb7) | Nov 17, 2023 |
| HP            | Notebook                    | Notebook    | [5d2df329aa](https://bsd-hardware.info/?probe=5d2df329aa) | Nov 17, 2023 |
| ASUSTek       | ROG Maximus XII APEX        | Desktop     | [204ee8891b](https://bsd-hardware.info/?probe=204ee8891b) | Nov 16, 2023 |
| Lenovo        | ThinkPad X230 2320A5U       | Notebook    | [48f8b6a93a](https://bsd-hardware.info/?probe=48f8b6a93a) | Nov 16, 2023 |
| ASUSTek       | ROG Maximus XII APEX        | Desktop     | [b34836b090](https://bsd-hardware.info/?probe=b34836b090) | Nov 16, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [7d9f6b4511](https://bsd-hardware.info/?probe=7d9f6b4511) | Nov 15, 2023 |
| Dell          | G5 5505                     | Notebook    | [088aea32c0](https://bsd-hardware.info/?probe=088aea32c0) | Nov 15, 2023 |
| HP            | 18E7                        | Desktop     | [3cbe1117fa](https://bsd-hardware.info/?probe=3cbe1117fa) | Nov 14, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [b858bd0986](https://bsd-hardware.info/?probe=b858bd0986) | Nov 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [db926657cc](https://bsd-hardware.info/?probe=db926657cc) | Nov 14, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [253d230fd3](https://bsd-hardware.info/?probe=253d230fd3) | Nov 14, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [d74a1ddc22](https://bsd-hardware.info/?probe=d74a1ddc22) | Nov 14, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [ea2d57ac16](https://bsd-hardware.info/?probe=ea2d57ac16) | Nov 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [771c13f8ea](https://bsd-hardware.info/?probe=771c13f8ea) | Nov 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [35ae423f7a](https://bsd-hardware.info/?probe=35ae423f7a) | Nov 13, 2023 |
| Dell          | 02YYK5 A00                  | Desktop     | [8b333abcaa](https://bsd-hardware.info/?probe=8b333abcaa) | Nov 13, 2023 |
| MUCAI         | H61 V1.6A                   | Desktop     | [bd3f1334ee](https://bsd-hardware.info/?probe=bd3f1334ee) | Nov 13, 2023 |
| Protectli     | VP4650                      | Desktop     | [0eeeb46242](https://bsd-hardware.info/?probe=0eeeb46242) | Nov 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [a058c72d2c](https://bsd-hardware.info/?probe=a058c72d2c) | Nov 12, 2023 |
| Advantech     | NAMB-3250 A102-1            | Desktop     | [aabeab0c4f](https://bsd-hardware.info/?probe=aabeab0c4f) | Nov 12, 2023 |
| MSI           | H81M-P33                    | Desktop     | [a062354358](https://bsd-hardware.info/?probe=a062354358) | Nov 12, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [0869172a54](https://bsd-hardware.info/?probe=0869172a54) | Nov 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [b1e348523f](https://bsd-hardware.info/?probe=b1e348523f) | Nov 12, 2023 |
| Gigabyte      | C1037UN                     | Desktop     | [57a9aedd4e](https://bsd-hardware.info/?probe=57a9aedd4e) | Nov 12, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [f32f8bdf95](https://bsd-hardware.info/?probe=f32f8bdf95) | Nov 12, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [f0f418db58](https://bsd-hardware.info/?probe=f0f418db58) | Nov 11, 2023 |
| MSI           | MS-7360                     | Desktop     | [07d8a855f3](https://bsd-hardware.info/?probe=07d8a855f3) | Nov 11, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [0f681ab133](https://bsd-hardware.info/?probe=0f681ab133) | Nov 11, 2023 |
| Dell          | 03X6X0 A03                  | Server      | [5993f3956e](https://bsd-hardware.info/?probe=5993f3956e) | Nov 11, 2023 |
| HP            | 805D                        | Desktop     | [f39c87a2a3](https://bsd-hardware.info/?probe=f39c87a2a3) | Nov 11, 2023 |
| Dell          | 042P49 A01                  | Desktop     | [14493eb926](https://bsd-hardware.info/?probe=14493eb926) | Nov 11, 2023 |
| Intel         | HM570                       | Desktop     | [6079db8b21](https://bsd-hardware.info/?probe=6079db8b21) | Nov 11, 2023 |
| Intel         | S1200BTL E98681-306         | Server      | [0304f2c0f6](https://bsd-hardware.info/?probe=0304f2c0f6) | Nov 11, 2023 |
| Sophos        | XG                          | Firewall    | [3f3a233ec8](https://bsd-hardware.info/?probe=3f3a233ec8) | Nov 11, 2023 |
| Protectli     | FW6                         | Desktop     | [823022b2b0](https://bsd-hardware.info/?probe=823022b2b0) | Nov 10, 2023 |
| HP            | 1495                        | Desktop     | [e92d919eff](https://bsd-hardware.info/?probe=e92d919eff) | Nov 10, 2023 |
| Dell          | 0M788G A07                  | Server      | [6a8999de0e](https://bsd-hardware.info/?probe=6a8999de0e) | Nov 10, 2023 |
| HP            | 872C                        | Mini pc     | [6f2c2334f4](https://bsd-hardware.info/?probe=6f2c2334f4) | Nov 10, 2023 |
| Protectli     | VP2420                      | Desktop     | [3921d18b28](https://bsd-hardware.info/?probe=3921d18b28) | Nov 09, 2023 |
| PC Engines    | apu4                        | Desktop     | [85202e5b6e](https://bsd-hardware.info/?probe=85202e5b6e) | Nov 09, 2023 |
| Lenovo        | ThinkPad T480 20L6S5VP00    | Notebook    | [5eb914094b](https://bsd-hardware.info/?probe=5eb914094b) | Nov 09, 2023 |
| HP            | 1495                        | Desktop     | [8be7b95a27](https://bsd-hardware.info/?probe=8be7b95a27) | Nov 09, 2023 |
| Gateway       | NV79                        | Notebook    | [2a7dd49956](https://bsd-hardware.info/?probe=2a7dd49956) | Nov 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [41e181dd6f](https://bsd-hardware.info/?probe=41e181dd6f) | Nov 09, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [b6cd3662e9](https://bsd-hardware.info/?probe=b6cd3662e9) | Nov 09, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [b7b9df03f3](https://bsd-hardware.info/?probe=b7b9df03f3) | Nov 09, 2023 |
| Intel         | QHSW02                      | Desktop     | [e06c922fda](https://bsd-hardware.info/?probe=e06c922fda) | Nov 08, 2023 |
| Dell          | 0DPRF9 A00                  | All in one  | [6ee8baf52b](https://bsd-hardware.info/?probe=6ee8baf52b) | Nov 08, 2023 |
| Dell          | 0DPRF9 A00                  | All in one  | [abaff39583](https://bsd-hardware.info/?probe=abaff39583) | Nov 08, 2023 |
| Samsung       | 740U5M                      | Convertible | [1a996f2f48](https://bsd-hardware.info/?probe=1a996f2f48) | Nov 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [1987a99b64](https://bsd-hardware.info/?probe=1987a99b64) | Nov 07, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [dfdd6ff4c4](https://bsd-hardware.info/?probe=dfdd6ff4c4) | Nov 07, 2023 |
| CncTion       | N6000-4L B0                 | Desktop     | [ed06cf2232](https://bsd-hardware.info/?probe=ed06cf2232) | Nov 07, 2023 |
| Unknown       | Raspberry Pi                | Soc         | [e2a506d1b7](https://bsd-hardware.info/?probe=e2a506d1b7) | Nov 07, 2023 |
| Apple         | MacPro4,1                   | Desktop     | [5960492992](https://bsd-hardware.info/?probe=5960492992) | Nov 07, 2023 |
| Unknown       | QSKL01                      | Desktop     | [46543dd22d](https://bsd-hardware.info/?probe=46543dd22d) | Nov 07, 2023 |
| Intel         | QHSW02                      | Desktop     | [3203d5ee34](https://bsd-hardware.info/?probe=3203d5ee34) | Nov 07, 2023 |
| Intel         | HM570                       | Desktop     | [004550243c](https://bsd-hardware.info/?probe=004550243c) | Nov 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [624a69488f](https://bsd-hardware.info/?probe=624a69488f) | Nov 06, 2023 |
| ASUSTek       | AM1I-A                      | Desktop     | [a0580939a5](https://bsd-hardware.info/?probe=a0580939a5) | Nov 06, 2023 |
| HP            | 213D A01                    | Desktop     | [d475dfa7a4](https://bsd-hardware.info/?probe=d475dfa7a4) | Nov 06, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [bc88549a37](https://bsd-hardware.info/?probe=bc88549a37) | Nov 06, 2023 |
| Advantech     | NAMB-3250 A102-1            | Desktop     | [02f5e40f3d](https://bsd-hardware.info/?probe=02f5e40f3d) | Nov 06, 2023 |
| Cisco         | ASA5525 A0                  | Desktop     | [f6eb14f059](https://bsd-hardware.info/?probe=f6eb14f059) | Nov 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [8b1079a297](https://bsd-hardware.info/?probe=8b1079a297) | Nov 06, 2023 |
| Dell          | 05XGC8 A01                  | Desktop     | [9e054bbcb2](https://bsd-hardware.info/?probe=9e054bbcb2) | Nov 06, 2023 |
| Dell          | 0M788G A07                  | Server      | [a404997d9d](https://bsd-hardware.info/?probe=a404997d9d) | Nov 06, 2023 |
| CncTion       | N6000-4L B0                 | Desktop     | [7ee545bad3](https://bsd-hardware.info/?probe=7ee545bad3) | Nov 06, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [e8c7d22b1f](https://bsd-hardware.info/?probe=e8c7d22b1f) | Nov 05, 2023 |
| MSI           | H81M-P33                    | Desktop     | [d44c30f985](https://bsd-hardware.info/?probe=d44c30f985) | Nov 05, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [dac3ca2eca](https://bsd-hardware.info/?probe=dac3ca2eca) | Nov 05, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [e744712416](https://bsd-hardware.info/?probe=e744712416) | Nov 05, 2023 |
| Supermicro    | H8SML                       | Desktop     | [ab650cfab8](https://bsd-hardware.info/?probe=ab650cfab8) | Nov 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [2a768a9f63](https://bsd-hardware.info/?probe=2a768a9f63) | Nov 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [5d0e537b3e](https://bsd-hardware.info/?probe=5d0e537b3e) | Nov 05, 2023 |
| HP            | ProLiant ML10               | Desktop     | [43badefe76](https://bsd-hardware.info/?probe=43badefe76) | Nov 05, 2023 |
| Dell          | 0XCR8D A03                  | Desktop     | [cc58b2f58f](https://bsd-hardware.info/?probe=cc58b2f58f) | Nov 05, 2023 |
| Supermicro    | X10SLM+-LN4F                | Server      | [ed0fb62285](https://bsd-hardware.info/?probe=ed0fb62285) | Nov 04, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [0b678c5e33](https://bsd-hardware.info/?probe=0b678c5e33) | Nov 04, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [90a26f497a](https://bsd-hardware.info/?probe=90a26f497a) | Nov 04, 2023 |
| HP            | 18E4                        | Desktop     | [479b255034](https://bsd-hardware.info/?probe=479b255034) | Nov 03, 2023 |
| Protectli     | FW6                         | Desktop     | [2dc16f3849](https://bsd-hardware.info/?probe=2dc16f3849) | Nov 03, 2023 |
| Shenzhen M... | RPBNB                       | Desktop     | [db0f05f919](https://bsd-hardware.info/?probe=db0f05f919) | Nov 03, 2023 |
| Shenzhen M... | RPBNB                       | Desktop     | [b729c4137a](https://bsd-hardware.info/?probe=b729c4137a) | Nov 03, 2023 |
| Lenovo        | 312D SDK0L22692 WIN 3306... | Mini pc     | [c958c2b087](https://bsd-hardware.info/?probe=c958c2b087) | Nov 02, 2023 |
| IBM           | FWA-3211 A102               | Server      | [8c4e5effec](https://bsd-hardware.info/?probe=8c4e5effec) | Nov 02, 2023 |
| CWWK          | MINIPC-G12                  | Desktop     | [4fd9e1d707](https://bsd-hardware.info/?probe=4fd9e1d707) | Nov 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [f1e1a3e8c8](https://bsd-hardware.info/?probe=f1e1a3e8c8) | Nov 02, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [ff78edaee6](https://bsd-hardware.info/?probe=ff78edaee6) | Nov 02, 2023 |
| Dell          | 0XCR8D A01                  | Desktop     | [224cc728f5](https://bsd-hardware.info/?probe=224cc728f5) | Nov 02, 2023 |
| Dell          | 0XCR8D A02                  | Desktop     | [f9df1890fa](https://bsd-hardware.info/?probe=f9df1890fa) | Nov 02, 2023 |
| Dell          | 0M788G A07                  | Server      | [3d5a1fc986](https://bsd-hardware.info/?probe=3d5a1fc986) | Nov 02, 2023 |
| Dell          | 0XCR8D A01                  | Desktop     | [83c8ab8d4b](https://bsd-hardware.info/?probe=83c8ab8d4b) | Nov 02, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [3e55355c4b](https://bsd-hardware.info/?probe=3e55355c4b) | Nov 02, 2023 |
| Protectli     | VP2420                      | Desktop     | [7621eb7370](https://bsd-hardware.info/?probe=7621eb7370) | Nov 01, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [7e40f68fc3](https://bsd-hardware.info/?probe=7e40f68fc3) | Nov 01, 2023 |
| Supermicro    | A2SDi-4C-HLN4F              | Server      | [5b6e9f8808](https://bsd-hardware.info/?probe=5b6e9f8808) | Oct 31, 2023 |
| Shuttle       | FS61                        | Desktop     | [24158fbe17](https://bsd-hardware.info/?probe=24158fbe17) | Oct 31, 2023 |
| Shuttle       | FS61                        | Desktop     | [2efb16a5f4](https://bsd-hardware.info/?probe=2efb16a5f4) | Oct 31, 2023 |
| Lenovo        | ThinkPad T480 20L5000WUS    | Notebook    | [4dcf84c76c](https://bsd-hardware.info/?probe=4dcf84c76c) | Oct 31, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [c163891517](https://bsd-hardware.info/?probe=c163891517) | Oct 31, 2023 |
| CheckPoint    | T-110-00                    | Desktop     | [970671ce27](https://bsd-hardware.info/?probe=970671ce27) | Oct 31, 2023 |
| Gigabyte      | H370M D3H-CF                | Desktop     | [6b2553e06c](https://bsd-hardware.info/?probe=6b2553e06c) | Oct 30, 2023 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [da2fa90c43](https://bsd-hardware.info/?probe=da2fa90c43) | Oct 30, 2023 |
| Dell          | 0KP561                      | Desktop     | [cd0ae50eb0](https://bsd-hardware.info/?probe=cd0ae50eb0) | Oct 30, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [10d46f39aa](https://bsd-hardware.info/?probe=10d46f39aa) | Oct 30, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [5995fa3115](https://bsd-hardware.info/?probe=5995fa3115) | Oct 30, 2023 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [c7e5f79b34](https://bsd-hardware.info/?probe=c7e5f79b34) | Oct 30, 2023 |
| ShenZhen M... | MW-GMLK-2.5G6L              | Desktop     | [9567268d28](https://bsd-hardware.info/?probe=9567268d28) | Oct 30, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [32b7f19d78](https://bsd-hardware.info/?probe=32b7f19d78) | Oct 30, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [522298f90a](https://bsd-hardware.info/?probe=522298f90a) | Oct 29, 2023 |
| ShenZhen M... | MW-GMLK-2.5G6L              | Desktop     | [709f8e1566](https://bsd-hardware.info/?probe=709f8e1566) | Oct 29, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [1f6542c47d](https://bsd-hardware.info/?probe=1f6542c47d) | Oct 29, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [74c3cbd1a3](https://bsd-hardware.info/?probe=74c3cbd1a3) | Oct 29, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [b60083ef1f](https://bsd-hardware.info/?probe=b60083ef1f) | Oct 28, 2023 |
| ASRock        | H370M-ITX/ac                | Desktop     | [ace25d235f](https://bsd-hardware.info/?probe=ace25d235f) | Oct 28, 2023 |
| HP            | 2AF7                        | Desktop     | [a45659c9d2](https://bsd-hardware.info/?probe=a45659c9d2) | Oct 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [3e99a14af3](https://bsd-hardware.info/?probe=3e99a14af3) | Oct 28, 2023 |
| IBM           | ThinkPad R51 2889W11        | Notebook    | [26d2e55032](https://bsd-hardware.info/?probe=26d2e55032) | Oct 28, 2023 |
| Dell          | 09WH54 A01                  | Desktop     | [a012c0e1c9](https://bsd-hardware.info/?probe=a012c0e1c9) | Oct 27, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [03ef00fab1](https://bsd-hardware.info/?probe=03ef00fab1) | Oct 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [7a9e2d88ed](https://bsd-hardware.info/?probe=7a9e2d88ed) | Oct 27, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [f8ae786555](https://bsd-hardware.info/?probe=f8ae786555) | Oct 27, 2023 |
| Shenzhen M... | AHBNB OEM                   | Desktop     | [8a1a0cdc32](https://bsd-hardware.info/?probe=8a1a0cdc32) | Oct 27, 2023 |
| Supermicro    | X10SLM+-LN4F                | Server      | [53651e09ac](https://bsd-hardware.info/?probe=53651e09ac) | Oct 27, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [233d4d3b64](https://bsd-hardware.info/?probe=233d4d3b64) | Oct 26, 2023 |
| HPE           | ProLiant DL20 Gen10         | Server      | [3541caeb52](https://bsd-hardware.info/?probe=3541caeb52) | Oct 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [f06cbf02dc](https://bsd-hardware.info/?probe=f06cbf02dc) | Oct 25, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [66f5010f59](https://bsd-hardware.info/?probe=66f5010f59) | Oct 24, 2023 |
| Protectli     | FW6                         | Desktop     | [9ba0e874f4](https://bsd-hardware.info/?probe=9ba0e874f4) | Oct 24, 2023 |
| Lenovo        | ThinkPad T490 20N3X50500    | Notebook    | [364c7828be](https://bsd-hardware.info/?probe=364c7828be) | Oct 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [b42465c967](https://bsd-hardware.info/?probe=b42465c967) | Oct 23, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [2424acbde7](https://bsd-hardware.info/?probe=2424acbde7) | Oct 23, 2023 |
| Supermicro    | X10SLM-F                    | Desktop     | [8e622421c6](https://bsd-hardware.info/?probe=8e622421c6) | Oct 23, 2023 |
| HP            | 3397                        | Desktop     | [2c004318d4](https://bsd-hardware.info/?probe=2c004318d4) | Oct 22, 2023 |
| Acer          | Aspire XC-830               | Desktop     | [6aea1130aa](https://bsd-hardware.info/?probe=6aea1130aa) | Oct 22, 2023 |
| Acer          | Aspire XC-830               | Desktop     | [3a4d822cfc](https://bsd-hardware.info/?probe=3a4d822cfc) | Oct 22, 2023 |
| MSI           | H81M-P33                    | Desktop     | [dd9ff802a9](https://bsd-hardware.info/?probe=dd9ff802a9) | Oct 22, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [1b94fd9385](https://bsd-hardware.info/?probe=1b94fd9385) | Oct 22, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [cc7fb797f5](https://bsd-hardware.info/?probe=cc7fb797f5) | Oct 22, 2023 |
| Sophos        | SG                          | Firewall    | [cb44d7e49b](https://bsd-hardware.info/?probe=cb44d7e49b) | Oct 22, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [e12093f6bd](https://bsd-hardware.info/?probe=e12093f6bd) | Oct 22, 2023 |
| Lenovo        | ThinkPad T410 2518C3U       | Notebook    | [e4b35a3ff6](https://bsd-hardware.info/?probe=e4b35a3ff6) | Oct 21, 2023 |
| Dell          | 0M788G A07                  | Server      | [702549b133](https://bsd-hardware.info/?probe=702549b133) | Oct 21, 2023 |
| HP            | 8054                        | Desktop     | [71b61dc284](https://bsd-hardware.info/?probe=71b61dc284) | Oct 21, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [3a35f074d9](https://bsd-hardware.info/?probe=3a35f074d9) | Oct 20, 2023 |
| Dell          | Latitude 5490               | Notebook    | [eeab525ffd](https://bsd-hardware.info/?probe=eeab525ffd) | Oct 20, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [48bb0077c3](https://bsd-hardware.info/?probe=48bb0077c3) | Oct 20, 2023 |
| Protectli     | FW4A Ver                    | Desktop     | [d40c67f9ca](https://bsd-hardware.info/?probe=d40c67f9ca) | Oct 20, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [3f7a4e2865](https://bsd-hardware.info/?probe=3f7a4e2865) | Oct 20, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [d3ad63aa13](https://bsd-hardware.info/?probe=d3ad63aa13) | Oct 19, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [a8dd61b29b](https://bsd-hardware.info/?probe=a8dd61b29b) | Oct 19, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [e85b1bd1ee](https://bsd-hardware.info/?probe=e85b1bd1ee) | Oct 19, 2023 |
| Gigabyte      | B85M-DS3H                   | Desktop     | [bd9d649fb6](https://bsd-hardware.info/?probe=bd9d649fb6) | Oct 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [94f0b39689](https://bsd-hardware.info/?probe=94f0b39689) | Oct 19, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [606ed441ae](https://bsd-hardware.info/?probe=606ed441ae) | Oct 19, 2023 |
| Fujitsu       | D3433-S2 S26361-D3433-S2    | Desktop     | [26a1b95e16](https://bsd-hardware.info/?probe=26a1b95e16) | Oct 19, 2023 |
| ASRock        | 970 Extreme3 R2.0           | Desktop     | [6f6f1bf009](https://bsd-hardware.info/?probe=6f6f1bf009) | Oct 18, 2023 |
| CncTion       | J4125-4L-I225               | Desktop     | [d8114642f5](https://bsd-hardware.info/?probe=d8114642f5) | Oct 18, 2023 |
| Dell          | 0YXT71 A00                  | Desktop     | [1bf1c3b807](https://bsd-hardware.info/?probe=1bf1c3b807) | Oct 18, 2023 |
| AZW           | EQ                          | Desktop     | [0d647b68a6](https://bsd-hardware.info/?probe=0d647b68a6) | Oct 18, 2023 |
| AZW           | EQ                          | Desktop     | [71f6a16f5a](https://bsd-hardware.info/?probe=71f6a16f5a) | Oct 18, 2023 |
| HP            | 8299                        | Desktop     | [b4ba6a7e52](https://bsd-hardware.info/?probe=b4ba6a7e52) | Oct 18, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [0f18316a17](https://bsd-hardware.info/?probe=0f18316a17) | Oct 18, 2023 |
| ASRock        | 970 Extreme3 R2.0           | Desktop     | [3dffc4d445](https://bsd-hardware.info/?probe=3dffc4d445) | Oct 18, 2023 |
| HP            | 8299                        | Desktop     | [8da92e01e0](https://bsd-hardware.info/?probe=8da92e01e0) | Oct 17, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [0ae4cee8b3](https://bsd-hardware.info/?probe=0ae4cee8b3) | Oct 17, 2023 |
| ASUSTek       | X99-A/USB                   | Desktop     | [0f914c6351](https://bsd-hardware.info/?probe=0f914c6351) | Oct 17, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [5f364ec930](https://bsd-hardware.info/?probe=5f364ec930) | Oct 17, 2023 |
| Dell          | 0W3F1J A00                  | Mini pc     | [0139098ee3](https://bsd-hardware.info/?probe=0139098ee3) | Oct 16, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [8ff0ba4fcb](https://bsd-hardware.info/?probe=8ff0ba4fcb) | Oct 16, 2023 |
| Supermicro    | X10SRi-FB                   | Server      | [3129e4f848](https://bsd-hardware.info/?probe=3129e4f848) | Oct 16, 2023 |
| Sophos        | SG                          | Firewall    | [d825f1a130](https://bsd-hardware.info/?probe=d825f1a130) | Oct 15, 2023 |
| Intel         | DH55TC AAE70932-206         | Desktop     | [745b988354](https://bsd-hardware.info/?probe=745b988354) | Oct 15, 2023 |
| Dell          | 0WR7PY A03                  | Desktop     | [128323ada4](https://bsd-hardware.info/?probe=128323ada4) | Oct 15, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [bf66ef021e](https://bsd-hardware.info/?probe=bf66ef021e) | Oct 15, 2023 |
| MSI           | H81M-P33                    | Desktop     | [6902d492db](https://bsd-hardware.info/?probe=6902d492db) | Oct 15, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [094b766a05](https://bsd-hardware.info/?probe=094b766a05) | Oct 15, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [b502116394](https://bsd-hardware.info/?probe=b502116394) | Oct 15, 2023 |
| Protectli     | VP4650                      | Desktop     | [9c073eb854](https://bsd-hardware.info/?probe=9c073eb854) | Oct 15, 2023 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [ca5e8cfb2b](https://bsd-hardware.info/?probe=ca5e8cfb2b) | Oct 15, 2023 |
| Protectli     | VP2410                      | Desktop     | [aaffd45671](https://bsd-hardware.info/?probe=aaffd45671) | Oct 15, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [9d81c598a9](https://bsd-hardware.info/?probe=9d81c598a9) | Oct 15, 2023 |
| Sophos        | XG                          | Firewall    | [ab8b265b82](https://bsd-hardware.info/?probe=ab8b265b82) | Oct 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [697f24cf01](https://bsd-hardware.info/?probe=697f24cf01) | Oct 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [d14ff47394](https://bsd-hardware.info/?probe=d14ff47394) | Oct 13, 2023 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [95653dd42d](https://bsd-hardware.info/?probe=95653dd42d) | Oct 13, 2023 |
| Protectli     | FW4C                        | Desktop     | [16326174bb](https://bsd-hardware.info/?probe=16326174bb) | Oct 13, 2023 |
| Dell          | 02YYK5 A00                  | Desktop     | [b57183cbb0](https://bsd-hardware.info/?probe=b57183cbb0) | Oct 13, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [30f97615e6](https://bsd-hardware.info/?probe=30f97615e6) | Oct 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [9145630ed9](https://bsd-hardware.info/?probe=9145630ed9) | Oct 12, 2023 |
| IBM           | ThinkPad R51 2889W11        | Notebook    | [45836fafc3](https://bsd-hardware.info/?probe=45836fafc3) | Oct 12, 2023 |
| Toshiba       | Satellite C55-A             | Notebook    | [f27ea283cf](https://bsd-hardware.info/?probe=f27ea283cf) | Oct 12, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [cdc40fe6a3](https://bsd-hardware.info/?probe=cdc40fe6a3) | Oct 11, 2023 |
| Dell          | Precision 7550              | Notebook    | [a21e06c16c](https://bsd-hardware.info/?probe=a21e06c16c) | Oct 11, 2023 |
| Dell          | 08WKV3 A00                  | Desktop     | [67379c4768](https://bsd-hardware.info/?probe=67379c4768) | Oct 11, 2023 |
| Deciso        | NetBoard-A20                | Notebook    | [ddffd0a126](https://bsd-hardware.info/?probe=ddffd0a126) | Oct 10, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [3aa38e5b1f](https://bsd-hardware.info/?probe=3aa38e5b1f) | Oct 10, 2023 |
| AZW           | EQ                          | Desktop     | [ea7e5029de](https://bsd-hardware.info/?probe=ea7e5029de) | Oct 10, 2023 |
| Dell          | 03X6X0 A00                  | Server      | [26e755b8be](https://bsd-hardware.info/?probe=26e755b8be) | Oct 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [89d680cba1](https://bsd-hardware.info/?probe=89d680cba1) | Oct 09, 2023 |
| Dell          | 065TRV A04                  | Server      | [2d07fc66b5](https://bsd-hardware.info/?probe=2d07fc66b5) | Oct 09, 2023 |
| HP            | 1497                        | Desktop     | [9ffee4ae55](https://bsd-hardware.info/?probe=9ffee4ae55) | Oct 09, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [f55c557bcf](https://bsd-hardware.info/?probe=f55c557bcf) | Oct 09, 2023 |
| EVGA          | X299 MICRO                  | Desktop     | [2907f2166d](https://bsd-hardware.info/?probe=2907f2166d) | Oct 09, 2023 |
| Gigabyte      | H470M DS3H                  | Desktop     | [80e01e48bf](https://bsd-hardware.info/?probe=80e01e48bf) | Oct 09, 2023 |
| ASRock        | Z690M Phantom Gaming 4      | Desktop     | [20ff855aec](https://bsd-hardware.info/?probe=20ff855aec) | Oct 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [a64ed6b5d1](https://bsd-hardware.info/?probe=a64ed6b5d1) | Oct 08, 2023 |
| MSI           | H81M-P33                    | Desktop     | [a9729ebc38](https://bsd-hardware.info/?probe=a9729ebc38) | Oct 08, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [06a76899d6](https://bsd-hardware.info/?probe=06a76899d6) | Oct 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [cacbb83f98](https://bsd-hardware.info/?probe=cacbb83f98) | Oct 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [bb66634f7c](https://bsd-hardware.info/?probe=bb66634f7c) | Oct 08, 2023 |
| Lenovo        | ThinkPad T410 2518C3U       | Notebook    | [36daf066ca](https://bsd-hardware.info/?probe=36daf066ca) | Oct 08, 2023 |
| MSI           | Aspen                       | Desktop     | [7bb665508f](https://bsd-hardware.info/?probe=7bb665508f) | Oct 07, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2AD0... | Notebook    | [ac6742bd0f](https://bsd-hardware.info/?probe=ac6742bd0f) | Oct 07, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2AD0... | Notebook    | [3e15173331](https://bsd-hardware.info/?probe=3e15173331) | Oct 07, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [b3580a1e53](https://bsd-hardware.info/?probe=b3580a1e53) | Oct 07, 2023 |
| Dell          | 0PXXHP A03                  | Server      | [f3f37dd0e7](https://bsd-hardware.info/?probe=f3f37dd0e7) | Oct 06, 2023 |
| Intel         | CRESCENTBAY                 | Desktop     | [fb6d008bfc](https://bsd-hardware.info/?probe=fb6d008bfc) | Oct 06, 2023 |
| Intel         | QHSW02                      | Desktop     | [e0d4a273f5](https://bsd-hardware.info/?probe=e0d4a273f5) | Oct 06, 2023 |
| HP            | 8056                        | Desktop     | [7516a37588](https://bsd-hardware.info/?probe=7516a37588) | Oct 06, 2023 |
| Dell          | 0XN8Y6 A09                  | Server      | [0aa4133255](https://bsd-hardware.info/?probe=0aa4133255) | Oct 05, 2023 |
| Win elemen... | M600                        | Desktop     | [da4e03cd91](https://bsd-hardware.info/?probe=da4e03cd91) | Oct 05, 2023 |
| Win elemen... | M600                        | Desktop     | [27492e0298](https://bsd-hardware.info/?probe=27492e0298) | Oct 04, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | Notebook    | [88e8c64b6f](https://bsd-hardware.info/?probe=88e8c64b6f) | Oct 04, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [17406f5021](https://bsd-hardware.info/?probe=17406f5021) | Oct 04, 2023 |
| Protectli     | FW4C                        | Desktop     | [671429444f](https://bsd-hardware.info/?probe=671429444f) | Oct 04, 2023 |
| Supermicro    | A2SDi-TP8F                  | Desktop     | [1792df4520](https://bsd-hardware.info/?probe=1792df4520) | Oct 04, 2023 |
| Chuwi         | LarkBox X                   | Mini pc     | [4fa9bbbecf](https://bsd-hardware.info/?probe=4fa9bbbecf) | Oct 03, 2023 |
| HP            | 83E2                        | Desktop     | [dbb1010907](https://bsd-hardware.info/?probe=dbb1010907) | Oct 03, 2023 |
| ASUSTek       | PRIME B560-PLUS AC-HES      | Desktop     | [471133280c](https://bsd-hardware.info/?probe=471133280c) | Oct 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [cab6cdb306](https://bsd-hardware.info/?probe=cab6cdb306) | Oct 02, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [d5d794abdb](https://bsd-hardware.info/?probe=d5d794abdb) | Oct 02, 2023 |
| Google        | Auron_Paine                 | Notebook    | [d202b4dd6f](https://bsd-hardware.info/?probe=d202b4dd6f) | Oct 02, 2023 |
| Google        | Auron_Paine                 | Notebook    | [1c44cf70e8](https://bsd-hardware.info/?probe=1c44cf70e8) | Oct 02, 2023 |
| Protectli     | VP2420                      | Desktop     | [c77ef1792c](https://bsd-hardware.info/?probe=c77ef1792c) | Oct 02, 2023 |
| Protectli     | VP46xx                      | Desktop     | [4985863bd8](https://bsd-hardware.info/?probe=4985863bd8) | Oct 01, 2023 |
| Google        | Auron_Paine                 | Notebook    | [021624028a](https://bsd-hardware.info/?probe=021624028a) | Oct 01, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [7a6b97e997](https://bsd-hardware.info/?probe=7a6b97e997) | Oct 01, 2023 |
| MSI           | H81M-P33                    | Desktop     | [da12fe3c05](https://bsd-hardware.info/?probe=da12fe3c05) | Oct 01, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [6975204e47](https://bsd-hardware.info/?probe=6975204e47) | Oct 01, 2023 |
| Supermicro    | A2SDi-4C-HLN4F              | Desktop     | [f97e242e6b](https://bsd-hardware.info/?probe=f97e242e6b) | Oct 01, 2023 |
| Win elemen... | M600                        | Desktop     | [b5caabfd31](https://bsd-hardware.info/?probe=b5caabfd31) | Oct 01, 2023 |
| Win elemen... | M600                        | Desktop     | [7a1378a001](https://bsd-hardware.info/?probe=7a1378a001) | Oct 01, 2023 |
| Win elemen... | M600                        | Desktop     | [93cc6a1173](https://bsd-hardware.info/?probe=93cc6a1173) | Oct 01, 2023 |
| Gigabyte      | H470M DS3H                  | Desktop     | [604bce28c1](https://bsd-hardware.info/?probe=604bce28c1) | Sep 30, 2023 |
| Supermicro    | X9DRD-iF                    | Server      | [fc2ba7c8d8](https://bsd-hardware.info/?probe=fc2ba7c8d8) | Sep 30, 2023 |
| Win elemen... | M600                        | Desktop     | [abc175c93b](https://bsd-hardware.info/?probe=abc175c93b) | Sep 30, 2023 |
| Win elemen... | M600                        | Desktop     | [5b7606e786](https://bsd-hardware.info/?probe=5b7606e786) | Sep 30, 2023 |
| MUCAI         | H61 V1.6A                   | Desktop     | [2008598c7e](https://bsd-hardware.info/?probe=2008598c7e) | Sep 29, 2023 |
| Deciso        | Netboard A20                | Notebook    | [3877143e37](https://bsd-hardware.info/?probe=3877143e37) | Sep 29, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [cda7be3da8](https://bsd-hardware.info/?probe=cda7be3da8) | Sep 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [6ed3c7314d](https://bsd-hardware.info/?probe=6ed3c7314d) | Sep 29, 2023 |
| HP            | 0B54h D                     | Desktop     | [55122a1908](https://bsd-hardware.info/?probe=55122a1908) | Sep 29, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [0f1805a40e](https://bsd-hardware.info/?probe=0f1805a40e) | Sep 27, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [d86474bd03](https://bsd-hardware.info/?probe=d86474bd03) | Sep 27, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [57577a5f14](https://bsd-hardware.info/?probe=57577a5f14) | Sep 27, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [8a4596eefa](https://bsd-hardware.info/?probe=8a4596eefa) | Sep 27, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [86abd76c4e](https://bsd-hardware.info/?probe=86abd76c4e) | Sep 27, 2023 |
| Lenovo        | ThinkPad T16 Gen 2 21HHC... | Notebook    | [74d0396f87](https://bsd-hardware.info/?probe=74d0396f87) | Sep 27, 2023 |
| Intel         | DENLOW_REFRESH_WS           | Desktop     | [9ca318e043](https://bsd-hardware.info/?probe=9ca318e043) | Sep 27, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [0c56aeb6b5](https://bsd-hardware.info/?probe=0c56aeb6b5) | Sep 27, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [d7cdc9b73e](https://bsd-hardware.info/?probe=d7cdc9b73e) | Sep 26, 2023 |
| HP            | 8055                        | Desktop     | [b86f4f02a5](https://bsd-hardware.info/?probe=b86f4f02a5) | Sep 26, 2023 |
| HPE           | ProLiant DL20 Gen10         | Server      | [3c10d0b8ed](https://bsd-hardware.info/?probe=3c10d0b8ed) | Sep 26, 2023 |
| HPE           | ProLiant DL20 Gen10         | Server      | [bc62c36654](https://bsd-hardware.info/?probe=bc62c36654) | Sep 25, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D60... | Notebook    | [231aedbf9e](https://bsd-hardware.info/?probe=231aedbf9e) | Sep 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [a77db6c46a](https://bsd-hardware.info/?probe=a77db6c46a) | Sep 25, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [6153909c9e](https://bsd-hardware.info/?probe=6153909c9e) | Sep 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [5232e5837b](https://bsd-hardware.info/?probe=5232e5837b) | Sep 25, 2023 |
| CncTion       | N4505-4L B0                 | Desktop     | [5880a22b30](https://bsd-hardware.info/?probe=5880a22b30) | Sep 25, 2023 |
| Protectli     | VP4630                      | Desktop     | [d5c0fe73ef](https://bsd-hardware.info/?probe=d5c0fe73ef) | Sep 24, 2023 |
| MSI           | H81M-P33                    | Desktop     | [971f3fdba1](https://bsd-hardware.info/?probe=971f3fdba1) | Sep 24, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [6538212bd6](https://bsd-hardware.info/?probe=6538212bd6) | Sep 24, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [f7aee1db53](https://bsd-hardware.info/?probe=f7aee1db53) | Sep 24, 2023 |
| Intel         | DQ77KB AAG40294-401         | Desktop     | [be147f7ff1](https://bsd-hardware.info/?probe=be147f7ff1) | Sep 24, 2023 |
| Protectli     | VP2420                      | Desktop     | [8644c80a4a](https://bsd-hardware.info/?probe=8644c80a4a) | Sep 24, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [d8ccddab5a](https://bsd-hardware.info/?probe=d8ccddab5a) | Sep 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [3e1ef4a73c](https://bsd-hardware.info/?probe=3e1ef4a73c) | Sep 23, 2023 |
| IceWhale T... | ZimaBoard 216 ZMB           | Desktop     | [8386219e8f](https://bsd-hardware.info/?probe=8386219e8f) | Sep 22, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [5478cff8a7](https://bsd-hardware.info/?probe=5478cff8a7) | Sep 21, 2023 |
| Lenovo        | ThinkPad P50 20EN0012US     | Notebook    | [a1945198c6](https://bsd-hardware.info/?probe=a1945198c6) | Sep 21, 2023 |
| Premio        | BlueCat XMB3 00C            | Desktop     | [423687627b](https://bsd-hardware.info/?probe=423687627b) | Sep 21, 2023 |
| Protectli     | FW4C Ver                    | Desktop     | [eae9f87345](https://bsd-hardware.info/?probe=eae9f87345) | Sep 20, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [398d7a6f26](https://bsd-hardware.info/?probe=398d7a6f26) | Sep 20, 2023 |
| Supermicro    | A1SRi-2758F                 | Desktop     | [6ee2f45613](https://bsd-hardware.info/?probe=6ee2f45613) | Sep 20, 2023 |
| Supermicro    | A1SRi-2758F                 | Desktop     | [34bffe0ed1](https://bsd-hardware.info/?probe=34bffe0ed1) | Sep 20, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [60a616adf4](https://bsd-hardware.info/?probe=60a616adf4) | Sep 20, 2023 |
| HP            | 8522 A01                    | Mini pc     | [dd5d9863aa](https://bsd-hardware.info/?probe=dd5d9863aa) | Sep 19, 2023 |
| Shenzhen M... | RPBNB                       | Desktop     | [07698e61c2](https://bsd-hardware.info/?probe=07698e61c2) | Sep 19, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [ed7bef076e](https://bsd-hardware.info/?probe=ed7bef076e) | Sep 19, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [7c6f946c9b](https://bsd-hardware.info/?probe=7c6f946c9b) | Sep 19, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [0fe1aab1d8](https://bsd-hardware.info/?probe=0fe1aab1d8) | Sep 19, 2023 |
| Protectli     | VP2420                      | Desktop     | [c4599cac13](https://bsd-hardware.info/?probe=c4599cac13) | Sep 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [0a9c074970](https://bsd-hardware.info/?probe=0a9c074970) | Sep 18, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [5e7775568c](https://bsd-hardware.info/?probe=5e7775568c) | Sep 18, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [815d9f2867](https://bsd-hardware.info/?probe=815d9f2867) | Sep 18, 2023 |
| Inventec      | DQ Class A02                | Desktop     | [e6e705b7cf](https://bsd-hardware.info/?probe=e6e705b7cf) | Sep 18, 2023 |
| Advantech     | NAMB-3250 A102-1            | Desktop     | [143c5f73fc](https://bsd-hardware.info/?probe=143c5f73fc) | Sep 17, 2023 |
| Dell          | 04415J A00                  | Mini pc     | [35fbb60b50](https://bsd-hardware.info/?probe=35fbb60b50) | Sep 17, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [31455b0d33](https://bsd-hardware.info/?probe=31455b0d33) | Sep 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [31cf5dc87d](https://bsd-hardware.info/?probe=31cf5dc87d) | Sep 16, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [a054400ef6](https://bsd-hardware.info/?probe=a054400ef6) | Sep 16, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [1f54d2bb5b](https://bsd-hardware.info/?probe=1f54d2bb5b) | Sep 16, 2023 |
| Dell          | 02YYK5 A00                  | Desktop     | [a2d011d2d7](https://bsd-hardware.info/?probe=a2d011d2d7) | Sep 16, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [d36ff6181c](https://bsd-hardware.info/?probe=d36ff6181c) | Sep 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [3fcc5727d3](https://bsd-hardware.info/?probe=3fcc5727d3) | Sep 15, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [6fc18e3db7](https://bsd-hardware.info/?probe=6fc18e3db7) | Sep 15, 2023 |
| Lenovo        | ThinkPad Edge E531 68852... | Notebook    | [cc3bef6a45](https://bsd-hardware.info/?probe=cc3bef6a45) | Sep 15, 2023 |
| Deciso        | NetBoard-A20                | Notebook    | [0c65fb5e8c](https://bsd-hardware.info/?probe=0c65fb5e8c) | Sep 15, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [9790cd72bc](https://bsd-hardware.info/?probe=9790cd72bc) | Sep 15, 2023 |
| Dell          | OptiPlex 3020               | Desktop     | [dfb6cce27d](https://bsd-hardware.info/?probe=dfb6cce27d) | Sep 14, 2023 |
| ASRock        | J1900D2Y                    | Desktop     | [2084583d47](https://bsd-hardware.info/?probe=2084583d47) | Sep 14, 2023 |
| ASRock        | J3455M                      | Desktop     | [f9809dfb0f](https://bsd-hardware.info/?probe=f9809dfb0f) | Sep 13, 2023 |
| Dell          | 04YP6J A02                  | Desktop     | [0933e1164a](https://bsd-hardware.info/?probe=0933e1164a) | Sep 13, 2023 |
| GPU Compan... | GWTC116-2                   | Notebook    | [03a8809fe4](https://bsd-hardware.info/?probe=03a8809fe4) | Sep 13, 2023 |
| GPU Compan... | GWTC116-2                   | Notebook    | [7ba189ff8a](https://bsd-hardware.info/?probe=7ba189ff8a) | Sep 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [5dee3a945f](https://bsd-hardware.info/?probe=5dee3a945f) | Sep 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [9fee6e83fc](https://bsd-hardware.info/?probe=9fee6e83fc) | Sep 13, 2023 |
| Dell          | 02YYK5 A00                  | Desktop     | [ae320bd7de](https://bsd-hardware.info/?probe=ae320bd7de) | Sep 13, 2023 |
| Intel         | S1200BTL E98681-306         | Server      | [f3594b1f7c](https://bsd-hardware.info/?probe=f3594b1f7c) | Sep 13, 2023 |
| HP            | 212B                        | Desktop     | [3370718b29](https://bsd-hardware.info/?probe=3370718b29) | Sep 13, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [984a64677e](https://bsd-hardware.info/?probe=984a64677e) | Sep 13, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [b0cd1ce0f4](https://bsd-hardware.info/?probe=b0cd1ce0f4) | Sep 13, 2023 |
| Lenovo        | ThinkPad X140e 20BMS03E0... | Notebook    | [54b04ea958](https://bsd-hardware.info/?probe=54b04ea958) | Sep 12, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS (W... | Desktop     | [89a601d720](https://bsd-hardware.info/?probe=89a601d720) | Sep 12, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [7923196f55](https://bsd-hardware.info/?probe=7923196f55) | Sep 11, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [8b541c71a9](https://bsd-hardware.info/?probe=8b541c71a9) | Sep 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [6610a56ab4](https://bsd-hardware.info/?probe=6610a56ab4) | Sep 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [ccc62ac366](https://bsd-hardware.info/?probe=ccc62ac366) | Sep 10, 2023 |
| Intel         | NUC5i5MYBE H47797-205       | Mini pc     | [5ef436c661](https://bsd-hardware.info/?probe=5ef436c661) | Sep 10, 2023 |
| ASRock        | 4X4-4000 Series             | Desktop     | [525ed7878c](https://bsd-hardware.info/?probe=525ed7878c) | Sep 10, 2023 |
| ASRock        | 4X4-4000 Series             | Desktop     | [0131f46755](https://bsd-hardware.info/?probe=0131f46755) | Sep 10, 2023 |
| AZW           | EQ                          | Desktop     | [c6f83de1e4](https://bsd-hardware.info/?probe=c6f83de1e4) | Sep 10, 2023 |
| MSI           | H81M-P33                    | Desktop     | [57a847859f](https://bsd-hardware.info/?probe=57a847859f) | Sep 10, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [b7e0d87f47](https://bsd-hardware.info/?probe=b7e0d87f47) | Sep 10, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [c2378b3e83](https://bsd-hardware.info/?probe=c2378b3e83) | Sep 10, 2023 |
| Unknown       | QGLK03                      | Desktop     | [42ea8dfb44](https://bsd-hardware.info/?probe=42ea8dfb44) | Sep 10, 2023 |
| CWWK          | CW-AD4L-N V1                | Desktop     | [52764da7d8](https://bsd-hardware.info/?probe=52764da7d8) | Sep 10, 2023 |
| Supermicro    | X10SLM-F                    | Desktop     | [332a3f8516](https://bsd-hardware.info/?probe=332a3f8516) | Sep 09, 2023 |
| Supermicro    | X8DTH-i/6/iF/6F             | Desktop     | [df114e1b94](https://bsd-hardware.info/?probe=df114e1b94) | Sep 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [8579d5fa0d](https://bsd-hardware.info/?probe=8579d5fa0d) | Sep 09, 2023 |
| Protectli     | FW4C Ver                    | Desktop     | [7ea278ed7a](https://bsd-hardware.info/?probe=7ea278ed7a) | Sep 09, 2023 |
| Protectli     | FW4C Ver                    | Desktop     | [331f3de91a](https://bsd-hardware.info/?probe=331f3de91a) | Sep 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [ee507594a0](https://bsd-hardware.info/?probe=ee507594a0) | Sep 09, 2023 |
| Lenovo        | ThinkPad X61 Tablet 7762... | Notebook    | [252fc12d3b](https://bsd-hardware.info/?probe=252fc12d3b) | Sep 09, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [07d197cf04](https://bsd-hardware.info/?probe=07d197cf04) | Sep 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [2e51c11ed2](https://bsd-hardware.info/?probe=2e51c11ed2) | Sep 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [480823e372](https://bsd-hardware.info/?probe=480823e372) | Sep 08, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [122601f717](https://bsd-hardware.info/?probe=122601f717) | Sep 08, 2023 |
| AZW           | MINI S 10                   | Desktop     | [4580cb5481](https://bsd-hardware.info/?probe=4580cb5481) | Sep 08, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [aaeb12b1c6](https://bsd-hardware.info/?probe=aaeb12b1c6) | Sep 08, 2023 |
| Protectli     | VP2420                      | Desktop     | [2a8eb1b056](https://bsd-hardware.info/?probe=2a8eb1b056) | Sep 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [fa747c859f](https://bsd-hardware.info/?probe=fa747c859f) | Sep 08, 2023 |
| Intel         | MAHOBAY                     | Desktop     | [a3e54e7628](https://bsd-hardware.info/?probe=a3e54e7628) | Sep 08, 2023 |
| HP            | 8158 A01                    | Mini pc     | [ae22c1bea5](https://bsd-hardware.info/?probe=ae22c1bea5) | Sep 08, 2023 |
| HP            | Pavilion g7                 | Notebook    | [4870da3b0e](https://bsd-hardware.info/?probe=4870da3b0e) | Sep 07, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [eff74e8df0](https://bsd-hardware.info/?probe=eff74e8df0) | Sep 07, 2023 |
| Dell          | 05XGC8 A01                  | Desktop     | [7c0acfa5b9](https://bsd-hardware.info/?probe=7c0acfa5b9) | Sep 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [94d9b19ade](https://bsd-hardware.info/?probe=94d9b19ade) | Sep 07, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [b5aa3f010f](https://bsd-hardware.info/?probe=b5aa3f010f) | Sep 07, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [12145f939b](https://bsd-hardware.info/?probe=12145f939b) | Sep 07, 2023 |
| Dell          | 0KM5PX A01                  | Server      | [67f910daa9](https://bsd-hardware.info/?probe=67f910daa9) | Sep 06, 2023 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [4397f70291](https://bsd-hardware.info/?probe=4397f70291) | Sep 06, 2023 |
| AZW           | MINI S 10                   | Desktop     | [2daf516a05](https://bsd-hardware.info/?probe=2daf516a05) | Sep 06, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [0b7d85b124](https://bsd-hardware.info/?probe=0b7d85b124) | Sep 06, 2023 |
| LG Electro... | 16U70Q-K.AAS7U1             | Notebook    | [82e3b2e5f8](https://bsd-hardware.info/?probe=82e3b2e5f8) | Sep 06, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [3af68f2594](https://bsd-hardware.info/?probe=3af68f2594) | Sep 06, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [ec3e0338eb](https://bsd-hardware.info/?probe=ec3e0338eb) | Sep 06, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [84d768ee15](https://bsd-hardware.info/?probe=84d768ee15) | Sep 05, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [3fb536ecce](https://bsd-hardware.info/?probe=3fb536ecce) | Sep 05, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [67e9eafa7e](https://bsd-hardware.info/?probe=67e9eafa7e) | Sep 05, 2023 |
| Dell          | 0X3D66 A02                  | Server      | [8dcfb77863](https://bsd-hardware.info/?probe=8dcfb77863) | Sep 05, 2023 |
| ASUSTek       | H97I-PLUS                   | Desktop     | [e92272bb87](https://bsd-hardware.info/?probe=e92272bb87) | Sep 05, 2023 |
| Supermicro    | X11SSH-F                    | Desktop     | [bff90e93d0](https://bsd-hardware.info/?probe=bff90e93d0) | Sep 05, 2023 |
| Lenovo        | ThinkPad X61 Tablet 7762... | Notebook    | [00dd1bd84e](https://bsd-hardware.info/?probe=00dd1bd84e) | Sep 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [a4796e8170](https://bsd-hardware.info/?probe=a4796e8170) | Sep 04, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [8cc0358a69](https://bsd-hardware.info/?probe=8cc0358a69) | Sep 04, 2023 |
| CWWK          | CW-AD4L-N V1                | Desktop     | [dd32d9d4e1](https://bsd-hardware.info/?probe=dd32d9d4e1) | Sep 04, 2023 |
| Toshiba       | QOSMIO X775                 | Notebook    | [d92a05ab1d](https://bsd-hardware.info/?probe=d92a05ab1d) | Sep 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [7d95befe6e](https://bsd-hardware.info/?probe=7d95befe6e) | Sep 04, 2023 |
| Intel         | S1200KP AAG34877-201        | Desktop     | [1b07865ce7](https://bsd-hardware.info/?probe=1b07865ce7) | Sep 04, 2023 |
| ASRock        | X570 Steel Legend WiFi a... | Desktop     | [a98f0b3d67](https://bsd-hardware.info/?probe=a98f0b3d67) | Sep 03, 2023 |
| Gigabyte      | A520I AC                    | Desktop     | [58e061f420](https://bsd-hardware.info/?probe=58e061f420) | Sep 03, 2023 |
| ASRock        | X570 Steel Legend WiFi a... | Desktop     | [d352ea60cf](https://bsd-hardware.info/?probe=d352ea60cf) | Sep 03, 2023 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [fe53c55492](https://bsd-hardware.info/?probe=fe53c55492) | Sep 03, 2023 |
| MSI           | H81M-P33                    | Desktop     | [b47290007a](https://bsd-hardware.info/?probe=b47290007a) | Sep 03, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [ef4604a40f](https://bsd-hardware.info/?probe=ef4604a40f) | Sep 03, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [8d37c44440](https://bsd-hardware.info/?probe=8d37c44440) | Sep 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [9c1891cda7](https://bsd-hardware.info/?probe=9c1891cda7) | Sep 03, 2023 |
| AAEON         | FWS-2363 V1.0               | Desktop     | [098bc5466b](https://bsd-hardware.info/?probe=098bc5466b) | Sep 03, 2023 |
| Lenovo        | ThinkPad P50 20EN0012US     | Notebook    | [9d1b9e7af6](https://bsd-hardware.info/?probe=9d1b9e7af6) | Sep 03, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [1ae33cfe72](https://bsd-hardware.info/?probe=1ae33cfe72) | Sep 02, 2023 |
| ASRock        | J3455M                      | Desktop     | [762d4d9370](https://bsd-hardware.info/?probe=762d4d9370) | Sep 02, 2023 |
| Dell          | 0XCR8D A00                  | Desktop     | [b89126c9d9](https://bsd-hardware.info/?probe=b89126c9d9) | Sep 02, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [b63ded7b81](https://bsd-hardware.info/?probe=b63ded7b81) | Sep 02, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [57925dc8bb](https://bsd-hardware.info/?probe=57925dc8bb) | Sep 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [94487109c2](https://bsd-hardware.info/?probe=94487109c2) | Sep 01, 2023 |
| Supermicro    | X9DRD-iF                    | Server      | [708af02c7b](https://bsd-hardware.info/?probe=708af02c7b) | Sep 01, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [5e44dfed67](https://bsd-hardware.info/?probe=5e44dfed67) | Sep 01, 2023 |
| Dell          | 0DRG19 A00                  | Mini pc     | [9e6cb6fe25](https://bsd-hardware.info/?probe=9e6cb6fe25) | Sep 01, 2023 |
| CompuLab      | fitlet2                     | Mini pc     | [525a1718ff](https://bsd-hardware.info/?probe=525a1718ff) | Sep 01, 2023 |
| Shuttle       | FS77U                       | Desktop     | [149a8a1437](https://bsd-hardware.info/?probe=149a8a1437) | Sep 01, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [8f54654916](https://bsd-hardware.info/?probe=8f54654916) | Sep 01, 2023 |
| Dell          | 0YXT71 A02                  | Desktop     | [b887caabe7](https://bsd-hardware.info/?probe=b887caabe7) | Aug 31, 2023 |
| Foxconn       | nT-A3000 series FAB         | Desktop     | [d9f360b4fe](https://bsd-hardware.info/?probe=d9f360b4fe) | Aug 31, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [2557e04cf5](https://bsd-hardware.info/?probe=2557e04cf5) | Aug 31, 2023 |
| Intel         | NUC8i7HNB J68197-602        | Mini pc     | [f2806a3c65](https://bsd-hardware.info/?probe=f2806a3c65) | Aug 31, 2023 |
| Biostar       | A68N-5545                   | Desktop     | [b2a1070e2d](https://bsd-hardware.info/?probe=b2a1070e2d) | Aug 31, 2023 |
| CWWK          | CW-AD4L-N V1                | Desktop     | [363a27fb74](https://bsd-hardware.info/?probe=363a27fb74) | Aug 31, 2023 |
| Acer          | Aspire A515-55              | Notebook    | [fcbd8a3f31](https://bsd-hardware.info/?probe=fcbd8a3f31) | Aug 31, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [97975e788b](https://bsd-hardware.info/?probe=97975e788b) | Aug 30, 2023 |
| Deciso        | NetBoard-A20                | Notebook    | [0119402f80](https://bsd-hardware.info/?probe=0119402f80) | Aug 30, 2023 |
| Infoblox      | IB-810                      | Desktop     | [34c0fa6bec](https://bsd-hardware.info/?probe=34c0fa6bec) | Aug 30, 2023 |
| Supermicro    | X12SDV-8C-SPT8FA            | Server      | [c46557f737](https://bsd-hardware.info/?probe=c46557f737) | Aug 30, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [259a7ec99d](https://bsd-hardware.info/?probe=259a7ec99d) | Aug 30, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [20946147de](https://bsd-hardware.info/?probe=20946147de) | Aug 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [8cfa60050b](https://bsd-hardware.info/?probe=8cfa60050b) | Aug 30, 2023 |
| Dell          | Latitude E4310              | Notebook    | [7645de3654](https://bsd-hardware.info/?probe=7645de3654) | Aug 30, 2023 |
| Supermicro    | A1SRi-2758F                 | Desktop     | [c8b4f33fb1](https://bsd-hardware.info/?probe=c8b4f33fb1) | Aug 30, 2023 |
| Biostar       | A68N-5545                   | Desktop     | [c90edbc46a](https://bsd-hardware.info/?probe=c90edbc46a) | Aug 29, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | Notebook    | [e74ef1d37c](https://bsd-hardware.info/?probe=e74ef1d37c) | Aug 29, 2023 |
| Supermicro    | X9DRD-iF                    | Desktop     | [be36f2fe2b](https://bsd-hardware.info/?probe=be36f2fe2b) | Aug 28, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [e0d13077ea](https://bsd-hardware.info/?probe=e0d13077ea) | Aug 28, 2023 |
| Lenovo        | ThinkPad T490 20RYS06R00    | Notebook    | [978cd1d6bc](https://bsd-hardware.info/?probe=978cd1d6bc) | Aug 28, 2023 |
| Dell          | 04Y8V0 A02                  | Desktop     | [a84c23941d](https://bsd-hardware.info/?probe=a84c23941d) | Aug 27, 2023 |
| Protectli     | FW6                         | Desktop     | [37b744ff79](https://bsd-hardware.info/?probe=37b744ff79) | Aug 27, 2023 |
| Dell          | Latitude 7280               | Notebook    | [c858f191cf](https://bsd-hardware.info/?probe=c858f191cf) | Aug 27, 2023 |
| MSI           | H81M-P33                    | Desktop     | [2e9a066a01](https://bsd-hardware.info/?probe=2e9a066a01) | Aug 27, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [9898ae1ead](https://bsd-hardware.info/?probe=9898ae1ead) | Aug 27, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [0bb56ff672](https://bsd-hardware.info/?probe=0bb56ff672) | Aug 27, 2023 |
| HP            | 8103 A01                    | Mini pc     | [484d82cac6](https://bsd-hardware.info/?probe=484d82cac6) | Aug 27, 2023 |
| Supermicro    | X11SDV-4C-TP8F-01           | Desktop     | [21e958a05d](https://bsd-hardware.info/?probe=21e958a05d) | Aug 26, 2023 |
| ASRock        | 970 Extreme3 R2.0           | Desktop     | [bf289c5941](https://bsd-hardware.info/?probe=bf289c5941) | Aug 26, 2023 |
| HP            | 8299                        | Desktop     | [77a077cb11](https://bsd-hardware.info/?probe=77a077cb11) | Aug 26, 2023 |
| Pegatron      | 2ACD                        | Desktop     | [c20fcb2b2f](https://bsd-hardware.info/?probe=c20fcb2b2f) | Aug 26, 2023 |
| HP            | ENVY Notebook 13-ab0XX      | Notebook    | [3d96f4d5b4](https://bsd-hardware.info/?probe=3d96f4d5b4) | Aug 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [c8e95f3772](https://bsd-hardware.info/?probe=c8e95f3772) | Aug 26, 2023 |
| Supermicro    | X10DRi-LN4+                 | Server      | [4978b62b97](https://bsd-hardware.info/?probe=4978b62b97) | Aug 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [f1a43ebe23](https://bsd-hardware.info/?probe=f1a43ebe23) | Aug 24, 2023 |
| Inventec      | Z CLASS A02                 | Desktop     | [8d7f83c319](https://bsd-hardware.info/?probe=8d7f83c319) | Aug 24, 2023 |
| Dell          | Inspiron 15-7568            | Notebook    | [9e555f0b24](https://bsd-hardware.info/?probe=9e555f0b24) | Aug 24, 2023 |
| Dell          | Latitude 7490               | Notebook    | [0b05de2297](https://bsd-hardware.info/?probe=0b05de2297) | Aug 24, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [d07ade15d2](https://bsd-hardware.info/?probe=d07ade15d2) | Aug 23, 2023 |
| MSI           | PRO B550-VC                 | Desktop     | [005e9c7b4c](https://bsd-hardware.info/?probe=005e9c7b4c) | Aug 23, 2023 |
| AZW           | EQ                          | Desktop     | [a43bd92291](https://bsd-hardware.info/?probe=a43bd92291) | Aug 23, 2023 |
| Lenovo        | 3102 SDK0J40705 WIN 3425... | Desktop     | [1fcc80636d](https://bsd-hardware.info/?probe=1fcc80636d) | Aug 22, 2023 |
| Supermicro    | X9DRD-iF                    | Server      | [962bf51507](https://bsd-hardware.info/?probe=962bf51507) | Aug 22, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [ff55eb5161](https://bsd-hardware.info/?probe=ff55eb5161) | Aug 22, 2023 |
| Protectli     | FW4B                        | Desktop     | [6041b7e153](https://bsd-hardware.info/?probe=6041b7e153) | Aug 21, 2023 |
| Intel         | JSL MRD                     | Desktop     | [0f3ef76fb8](https://bsd-hardware.info/?probe=0f3ef76fb8) | Aug 21, 2023 |
| Cisco         | ASA5525 A0                  | Desktop     | [7c88ca29f7](https://bsd-hardware.info/?probe=7c88ca29f7) | Aug 21, 2023 |
| Dell          | 0PXXHP A03                  | Server      | [e8eef1fb22](https://bsd-hardware.info/?probe=e8eef1fb22) | Aug 21, 2023 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [3941ce5fae](https://bsd-hardware.info/?probe=3941ce5fae) | Aug 21, 2023 |
| ASRock        | X570M Pro4                  | Desktop     | [c03bc6fa91](https://bsd-hardware.info/?probe=c03bc6fa91) | Aug 21, 2023 |
| MSI           | MEG X570 ACE                | Desktop     | [0d69491bdd](https://bsd-hardware.info/?probe=0d69491bdd) | Aug 21, 2023 |
| MSI           | MEG X570 ACE                | Desktop     | [913cc77381](https://bsd-hardware.info/?probe=913cc77381) | Aug 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [e57d2d76d2](https://bsd-hardware.info/?probe=e57d2d76d2) | Aug 21, 2023 |
| Unknown       | J3160-4L                    | Desktop     | [cf30fa594f](https://bsd-hardware.info/?probe=cf30fa594f) | Aug 21, 2023 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [e6bfadb400](https://bsd-hardware.info/?probe=e6bfadb400) | Aug 21, 2023 |
| Inventec      | Z CLASS A02                 | Desktop     | [3194978ea5](https://bsd-hardware.info/?probe=3194978ea5) | Aug 20, 2023 |
| Dell          | 0D7449 A01                  | Server      | [33c9f97cb9](https://bsd-hardware.info/?probe=33c9f97cb9) | Aug 20, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [2beb3e34d8](https://bsd-hardware.info/?probe=2beb3e34d8) | Aug 20, 2023 |
| Gigabyte      | GA-880GA-UD3H               | Desktop     | [35eb7df9a7](https://bsd-hardware.info/?probe=35eb7df9a7) | Aug 20, 2023 |
| MSI           | 990FXA-GD80                 | Desktop     | [70c65a5a34](https://bsd-hardware.info/?probe=70c65a5a34) | Aug 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [3296816fc1](https://bsd-hardware.info/?probe=3296816fc1) | Aug 20, 2023 |
| ASRock        | H110M-STX                   | Desktop     | [5c819b9ff1](https://bsd-hardware.info/?probe=5c819b9ff1) | Aug 20, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [1b53079f34](https://bsd-hardware.info/?probe=1b53079f34) | Aug 19, 2023 |
| Protectli     | FW1 Ver                     | Desktop     | [8b49278bbd](https://bsd-hardware.info/?probe=8b49278bbd) | Aug 19, 2023 |
| Supermicro    | A1SRi-2758F                 | Desktop     | [c9c0312302](https://bsd-hardware.info/?probe=c9c0312302) | Aug 19, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [1bc7f67754](https://bsd-hardware.info/?probe=1bc7f67754) | Aug 18, 2023 |
| Protectli     | FW2B Ver                    | Desktop     | [b200aabc73](https://bsd-hardware.info/?probe=b200aabc73) | Aug 18, 2023 |
| Unknown       | Unknown                     | Desktop     | [f7c887c84f](https://bsd-hardware.info/?probe=f7c887c84f) | Aug 18, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [df095be4ba](https://bsd-hardware.info/?probe=df095be4ba) | Aug 18, 2023 |
| Dell          | 0GY6Y8 A00                  | Desktop     | [e982da98d2](https://bsd-hardware.info/?probe=e982da98d2) | Aug 18, 2023 |
| MSI           | MS-7721                     | Desktop     | [a577019634](https://bsd-hardware.info/?probe=a577019634) | Aug 18, 2023 |
| MSI           | MS-7721                     | Desktop     | [678c81c8c1](https://bsd-hardware.info/?probe=678c81c8c1) | Aug 18, 2023 |
| Unknown       | Unknown                     | Desktop     | [3521bed0e8](https://bsd-hardware.info/?probe=3521bed0e8) | Aug 18, 2023 |
| Unknown       | QSKL01                      | Desktop     | [b768029249](https://bsd-hardware.info/?probe=b768029249) | Aug 18, 2023 |
| ASRock        | B660M Steel Legend          | Desktop     | [c50e637bc2](https://bsd-hardware.info/?probe=c50e637bc2) | Aug 18, 2023 |
| Supermicro    | A1SRi-2758F                 | Desktop     | [71fff01c39](https://bsd-hardware.info/?probe=71fff01c39) | Aug 18, 2023 |
| Protectli     | FW4B                        | Desktop     | [880c0c7069](https://bsd-hardware.info/?probe=880c0c7069) | Aug 18, 2023 |
| HP            | 1495                        | Desktop     | [556a339a7e](https://bsd-hardware.info/?probe=556a339a7e) | Aug 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [a574d1cce5](https://bsd-hardware.info/?probe=a574d1cce5) | Aug 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [20348d2f47](https://bsd-hardware.info/?probe=20348d2f47) | Aug 17, 2023 |
| Unknown       | YL-E3854L4-V2               | Desktop     | [6b85b4a31c](https://bsd-hardware.info/?probe=6b85b4a31c) | Aug 16, 2023 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [fcb3075158](https://bsd-hardware.info/?probe=fcb3075158) | Aug 16, 2023 |
| Dell          | 0F9NPY A00                  | Server      | [bc1b3da23f](https://bsd-hardware.info/?probe=bc1b3da23f) | Aug 16, 2023 |
| Dell          | 05KX61 A02                  | Server      | [2fe3211471](https://bsd-hardware.info/?probe=2fe3211471) | Aug 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [e457a41b4a](https://bsd-hardware.info/?probe=e457a41b4a) | Aug 16, 2023 |
| Supermicro    | X11SDV-8C-TP8F              | Desktop     | [3b5ddbcb06](https://bsd-hardware.info/?probe=3b5ddbcb06) | Aug 16, 2023 |
| CncTion       | J4125-4L-I225               | Desktop     | [269cfa2253](https://bsd-hardware.info/?probe=269cfa2253) | Aug 16, 2023 |
| CWWK          | CW-AD4L-N V1                | Desktop     | [f710821a92](https://bsd-hardware.info/?probe=f710821a92) | Aug 16, 2023 |
| HP            | 18E7                        | Desktop     | [3c24defdf8](https://bsd-hardware.info/?probe=3c24defdf8) | Aug 16, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [9a8ad54cd3](https://bsd-hardware.info/?probe=9a8ad54cd3) | Aug 16, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [fc152ce8d4](https://bsd-hardware.info/?probe=fc152ce8d4) | Aug 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [86c4d1f8cf](https://bsd-hardware.info/?probe=86c4d1f8cf) | Aug 15, 2023 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [30c58f7403](https://bsd-hardware.info/?probe=30c58f7403) | Aug 15, 2023 |
| Lenovo        | IdeaPad Slim 9 14ITL5 82... | Notebook    | [be7bd4b126](https://bsd-hardware.info/?probe=be7bd4b126) | Aug 15, 2023 |
| PC Engines    | APU2                        | Desktop     | [c11fdc1cf9](https://bsd-hardware.info/?probe=c11fdc1cf9) | Aug 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [99fd3696dd](https://bsd-hardware.info/?probe=99fd3696dd) | Aug 15, 2023 |
| AZW           | EQ                          | Desktop     | [5393736ae4](https://bsd-hardware.info/?probe=5393736ae4) | Aug 15, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [dbbd82bd80](https://bsd-hardware.info/?probe=dbbd82bd80) | Aug 15, 2023 |
| MSI           | B360M BAZOOKA               | Desktop     | [472c17f992](https://bsd-hardware.info/?probe=472c17f992) | Aug 15, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [aba7b573c1](https://bsd-hardware.info/?probe=aba7b573c1) | Aug 14, 2023 |
| MSI           | 990FXA-GD80                 | Desktop     | [169da97c61](https://bsd-hardware.info/?probe=169da97c61) | Aug 14, 2023 |
| Protectli     | FW4B                        | Desktop     | [417b740320](https://bsd-hardware.info/?probe=417b740320) | Aug 14, 2023 |
| Dell          | 0HY9JP A00                  | Desktop     | [c09110c605](https://bsd-hardware.info/?probe=c09110c605) | Aug 13, 2023 |
| Protectli     | VP2420                      | Desktop     | [b4bed593e9](https://bsd-hardware.info/?probe=b4bed593e9) | Aug 13, 2023 |
| Protectli     | VP2420                      | Desktop     | [b81c163920](https://bsd-hardware.info/?probe=b81c163920) | Aug 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [2529ce32a7](https://bsd-hardware.info/?probe=2529ce32a7) | Aug 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [80fbf43a6c](https://bsd-hardware.info/?probe=80fbf43a6c) | Aug 13, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [fbb75a1ace](https://bsd-hardware.info/?probe=fbb75a1ace) | Aug 13, 2023 |
| MSI           | H81M-P33                    | Desktop     | [c7b0e4ca6c](https://bsd-hardware.info/?probe=c7b0e4ca6c) | Aug 13, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [245d908d1a](https://bsd-hardware.info/?probe=245d908d1a) | Aug 13, 2023 |
| Dell          | 02YYK5 A00                  | Desktop     | [fecdfd45c7](https://bsd-hardware.info/?probe=fecdfd45c7) | Aug 13, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [9d53e56e92](https://bsd-hardware.info/?probe=9d53e56e92) | Aug 13, 2023 |
| Supermicro    | X11SSH-F                    | Desktop     | [deb4e10cd2](https://bsd-hardware.info/?probe=deb4e10cd2) | Aug 13, 2023 |
| Supermicro    | X11SSH-F                    | Desktop     | [947caf3be1](https://bsd-hardware.info/?probe=947caf3be1) | Aug 13, 2023 |
| Unknown       | YL-E3854L4-V2               | Desktop     | [e21c4e8012](https://bsd-hardware.info/?probe=e21c4e8012) | Aug 13, 2023 |
| Unknown       | YL-E3854L4-V2               | Desktop     | [2b24029c25](https://bsd-hardware.info/?probe=2b24029c25) | Aug 12, 2023 |
| HP            | 8265                        | Desktop     | [cefac793c7](https://bsd-hardware.info/?probe=cefac793c7) | Aug 12, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [41f42269dc](https://bsd-hardware.info/?probe=41f42269dc) | Aug 12, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [edc2f0f879](https://bsd-hardware.info/?probe=edc2f0f879) | Aug 12, 2023 |
| Protectli     | FW4C Ver                    | Desktop     | [519987ec57](https://bsd-hardware.info/?probe=519987ec57) | Aug 12, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [2ee5b48d5c](https://bsd-hardware.info/?probe=2ee5b48d5c) | Aug 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [e310e0d309](https://bsd-hardware.info/?probe=e310e0d309) | Aug 11, 2023 |
| HP            | 8054                        | Desktop     | [05cae0efcc](https://bsd-hardware.info/?probe=05cae0efcc) | Aug 11, 2023 |
| HP            | 8055                        | Desktop     | [d686196496](https://bsd-hardware.info/?probe=d686196496) | Aug 11, 2023 |
| HP            | 1495                        | Desktop     | [7591160534](https://bsd-hardware.info/?probe=7591160534) | Aug 11, 2023 |
| Shuttle       | FH270                       | Desktop     | [8b697be8be](https://bsd-hardware.info/?probe=8b697be8be) | Aug 11, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [2db86b4dff](https://bsd-hardware.info/?probe=2db86b4dff) | Aug 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [fdd28fbae2](https://bsd-hardware.info/?probe=fdd28fbae2) | Aug 10, 2023 |
| MSI           | B360M BAZOOKA               | Desktop     | [4b0b4b88a7](https://bsd-hardware.info/?probe=4b0b4b88a7) | Aug 10, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [d4b7006d24](https://bsd-hardware.info/?probe=d4b7006d24) | Aug 10, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [4f4c550075](https://bsd-hardware.info/?probe=4f4c550075) | Aug 10, 2023 |
| Supermicro    | X12SDV-4C-SP6F              | Desktop     | [6a275811b8](https://bsd-hardware.info/?probe=6a275811b8) | Aug 10, 2023 |
| Supermicro    | A1SRi 123456789             | Mini pc     | [a66d0c2283](https://bsd-hardware.info/?probe=a66d0c2283) | Aug 10, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [877307aa80](https://bsd-hardware.info/?probe=877307aa80) | Aug 09, 2023 |
| Premio        | BlueCat XMB3 00C            | Desktop     | [76abf23a1f](https://bsd-hardware.info/?probe=76abf23a1f) | Aug 08, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [c0884d7f16](https://bsd-hardware.info/?probe=c0884d7f16) | Aug 08, 2023 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [211a64ef6e](https://bsd-hardware.info/?probe=211a64ef6e) | Aug 08, 2023 |
| Dell          | 00NH4P A07                  | Server      | [be1b164954](https://bsd-hardware.info/?probe=be1b164954) | Aug 08, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [c54bdb8e4b](https://bsd-hardware.info/?probe=c54bdb8e4b) | Aug 08, 2023 |
| ASUSTek       | PRIME Z590M-PLUS            | Desktop     | [87810aceef](https://bsd-hardware.info/?probe=87810aceef) | Aug 08, 2023 |
| PC Engines    | apu4                        | Desktop     | [bb7ad49154](https://bsd-hardware.info/?probe=bb7ad49154) | Aug 07, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [d880905ae7](https://bsd-hardware.info/?probe=d880905ae7) | Aug 07, 2023 |
| Intel         | SHARKBAY                    | Desktop     | [2a8896bb78](https://bsd-hardware.info/?probe=2a8896bb78) | Aug 07, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [5b58edb60b](https://bsd-hardware.info/?probe=5b58edb60b) | Aug 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [16e7763338](https://bsd-hardware.info/?probe=16e7763338) | Aug 07, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [19e34e504c](https://bsd-hardware.info/?probe=19e34e504c) | Aug 07, 2023 |
| PC Engines    | apu4                        | Desktop     | [57e0cc469e](https://bsd-hardware.info/?probe=57e0cc469e) | Aug 07, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [c05ddd6998](https://bsd-hardware.info/?probe=c05ddd6998) | Aug 07, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [4836027efd](https://bsd-hardware.info/?probe=4836027efd) | Aug 07, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [ec37cc1ba1](https://bsd-hardware.info/?probe=ec37cc1ba1) | Aug 07, 2023 |
| Dell          | 01G5C3 A02                  | Server      | [da26fc11fd](https://bsd-hardware.info/?probe=da26fc11fd) | Aug 07, 2023 |
| Lenovo        | 30FD SDK0J40705 WIN 3425... | Mini pc     | [6a45c89f9c](https://bsd-hardware.info/?probe=6a45c89f9c) | Aug 06, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [21c932d1ca](https://bsd-hardware.info/?probe=21c932d1ca) | Aug 06, 2023 |
| ZOTAC         | Unknown                     | Desktop     | [415f49b491](https://bsd-hardware.info/?probe=415f49b491) | Aug 06, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [d2ba7bbf34](https://bsd-hardware.info/?probe=d2ba7bbf34) | Aug 06, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [d203b32a8f](https://bsd-hardware.info/?probe=d203b32a8f) | Aug 06, 2023 |
| Supermicro    | X12SDV-4C-SP6F              | Desktop     | [5a87146725](https://bsd-hardware.info/?probe=5a87146725) | Aug 06, 2023 |
| Supermicro    | X10DRI-TB                   | Server      | [d4e7a4dde7](https://bsd-hardware.info/?probe=d4e7a4dde7) | Aug 06, 2023 |
| MSI           | H81M-P33                    | Desktop     | [1f7493ada9](https://bsd-hardware.info/?probe=1f7493ada9) | Aug 06, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [46b9ec2e56](https://bsd-hardware.info/?probe=46b9ec2e56) | Aug 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [5bd8b552e6](https://bsd-hardware.info/?probe=5bd8b552e6) | Aug 06, 2023 |
| Acer          | Aspire TC-330               | Desktop     | [4d3de96309](https://bsd-hardware.info/?probe=4d3de96309) | Aug 05, 2023 |
| HP            | 843F                        | Desktop     | [d192efba82](https://bsd-hardware.info/?probe=d192efba82) | Aug 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [0f6e0d9566](https://bsd-hardware.info/?probe=0f6e0d9566) | Aug 05, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [8446d61b81](https://bsd-hardware.info/?probe=8446d61b81) | Aug 04, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [36d63888b2](https://bsd-hardware.info/?probe=36d63888b2) | Aug 04, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [bee8eb05f2](https://bsd-hardware.info/?probe=bee8eb05f2) | Aug 04, 2023 |
| Intel         | S2600GZ G29051-355          | Server      | [33697196aa](https://bsd-hardware.info/?probe=33697196aa) | Aug 04, 2023 |
| CompuLab      | fitlet2                     | Mini pc     | [1c593bf547](https://bsd-hardware.info/?probe=1c593bf547) | Aug 04, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [4a2c98005b](https://bsd-hardware.info/?probe=4a2c98005b) | Aug 04, 2023 |
| Protectli     | VP4650                      | Desktop     | [94d2d08a9d](https://bsd-hardware.info/?probe=94d2d08a9d) | Aug 04, 2023 |
| ASRock        | 4X4-4000 Series             | Desktop     | [da7d5e31aa](https://bsd-hardware.info/?probe=da7d5e31aa) | Aug 03, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [2bef587ef1](https://bsd-hardware.info/?probe=2bef587ef1) | Aug 03, 2023 |
| Dell          | 0G7MDY A12                  | Server      | [3caa904aa3](https://bsd-hardware.info/?probe=3caa904aa3) | Aug 03, 2023 |
| Dell          | 0G7MDY A12                  | Server      | [4dfb2ccae6](https://bsd-hardware.info/?probe=4dfb2ccae6) | Aug 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [803f6b50b3](https://bsd-hardware.info/?probe=803f6b50b3) | Aug 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [91dd6813a1](https://bsd-hardware.info/?probe=91dd6813a1) | Aug 03, 2023 |
| ASRock        | 4X4-4000 Series             | Desktop     | [d896138d30](https://bsd-hardware.info/?probe=d896138d30) | Aug 03, 2023 |
| HP            | 1495                        | Desktop     | [551688d163](https://bsd-hardware.info/?probe=551688d163) | Aug 03, 2023 |
| Shuttle       | FH270                       | Desktop     | [92c45a20de](https://bsd-hardware.info/?probe=92c45a20de) | Aug 02, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [e0a72a6c82](https://bsd-hardware.info/?probe=e0a72a6c82) | Aug 02, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [249d4620d2](https://bsd-hardware.info/?probe=249d4620d2) | Aug 02, 2023 |
| ASRock        | B660-ITX                    | Desktop     | [c218c3c4d4](https://bsd-hardware.info/?probe=c218c3c4d4) | Aug 02, 2023 |
| Protectli     | VP2410 10                   | Desktop     | [3d653ab54c](https://bsd-hardware.info/?probe=3d653ab54c) | Aug 02, 2023 |
| Dell          | 0DRG19 A00                  | Mini pc     | [3962253bda](https://bsd-hardware.info/?probe=3962253bda) | Aug 02, 2023 |
| Dell          | 0WR7PY A01                  | Desktop     | [54388809cd](https://bsd-hardware.info/?probe=54388809cd) | Aug 02, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [ffc50e224c](https://bsd-hardware.info/?probe=ffc50e224c) | Aug 01, 2023 |
| Supermicro    | X7SPA-H                     | Desktop     | [de44613a90](https://bsd-hardware.info/?probe=de44613a90) | Aug 01, 2023 |
| Fujitsu       | D3433-S2 S26361-D3433-S2    | Desktop     | [bdb1c85615](https://bsd-hardware.info/?probe=bdb1c85615) | Aug 01, 2023 |
| CWWK          | CW-AD4L-N V1                | Desktop     | [9cf0b7fe7c](https://bsd-hardware.info/?probe=9cf0b7fe7c) | Aug 01, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [1421e45cea](https://bsd-hardware.info/?probe=1421e45cea) | Aug 01, 2023 |
| AZW           | EQ                          | Desktop     | [24d56ab18f](https://bsd-hardware.info/?probe=24d56ab18f) | Aug 01, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [f26504cb5b](https://bsd-hardware.info/?probe=f26504cb5b) | Jul 31, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [c045012233](https://bsd-hardware.info/?probe=c045012233) | Jul 31, 2023 |
| Sophos        | XG                          | Firewall    | [629bf7a092](https://bsd-hardware.info/?probe=629bf7a092) | Jul 31, 2023 |
| Protectli     | FW6                         | Desktop     | [aa7b970016](https://bsd-hardware.info/?probe=aa7b970016) | Jul 31, 2023 |
| Protectli     | FW1 Ver                     | Desktop     | [1d6213fd35](https://bsd-hardware.info/?probe=1d6213fd35) | Jul 30, 2023 |
| MSI           | H81M-P33                    | Desktop     | [9c27c27611](https://bsd-hardware.info/?probe=9c27c27611) | Jul 30, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [a2dbe84ed3](https://bsd-hardware.info/?probe=a2dbe84ed3) | Jul 30, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [591f8397a9](https://bsd-hardware.info/?probe=591f8397a9) | Jul 30, 2023 |
| Sophos        | XG                          | Firewall    | [a6fc41a58b](https://bsd-hardware.info/?probe=a6fc41a58b) | Jul 30, 2023 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [72abf8e420](https://bsd-hardware.info/?probe=72abf8e420) | Jul 30, 2023 |
| Premio        | BlueCat XMB3 00C            | Desktop     | [c453573c71](https://bsd-hardware.info/?probe=c453573c71) | Jul 30, 2023 |
| Dell          | 05XGC8 A01                  | Desktop     | [38310a9c5e](https://bsd-hardware.info/?probe=38310a9c5e) | Jul 30, 2023 |
| HP            | 213D A01                    | Desktop     | [802a71b9f6](https://bsd-hardware.info/?probe=802a71b9f6) | Jul 29, 2023 |
| Sophos        | SG                          | Firewall    | [07e908538b](https://bsd-hardware.info/?probe=07e908538b) | Jul 29, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [fc2a96cc75](https://bsd-hardware.info/?probe=fc2a96cc75) | Jul 29, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [71b3719bfe](https://bsd-hardware.info/?probe=71b3719bfe) | Jul 29, 2023 |
| Cisco Syst... | ENCS5412/K9 M3              | Server      | [4a34cf5294](https://bsd-hardware.info/?probe=4a34cf5294) | Jul 29, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [a1380ccfe1](https://bsd-hardware.info/?probe=a1380ccfe1) | Jul 29, 2023 |
| Dell          | 0HD5W2 A00                  | Desktop     | [ce83168854](https://bsd-hardware.info/?probe=ce83168854) | Jul 29, 2023 |
| Cisco Syst... | ENCS5412/K9 M3              | Server      | [2be0baa769](https://bsd-hardware.info/?probe=2be0baa769) | Jul 29, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [53e133857b](https://bsd-hardware.info/?probe=53e133857b) | Jul 29, 2023 |
| Dell          | 05XGC8 A01                  | Desktop     | [06e6afb4f1](https://bsd-hardware.info/?probe=06e6afb4f1) | Jul 28, 2023 |
| HP            | 18E4                        | Desktop     | [6a0ce7d626](https://bsd-hardware.info/?probe=6a0ce7d626) | Jul 28, 2023 |
| Dell          | 03X6X0 A03                  | Server      | [74ef7a9db3](https://bsd-hardware.info/?probe=74ef7a9db3) | Jul 28, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [088f599199](https://bsd-hardware.info/?probe=088f599199) | Jul 28, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [1595ce505c](https://bsd-hardware.info/?probe=1595ce505c) | Jul 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [836d435712](https://bsd-hardware.info/?probe=836d435712) | Jul 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [6d6a8cb863](https://bsd-hardware.info/?probe=6d6a8cb863) | Jul 28, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [fccf22f7a7](https://bsd-hardware.info/?probe=fccf22f7a7) | Jul 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [9d078811ba](https://bsd-hardware.info/?probe=9d078811ba) | Jul 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [dbb7d95d59](https://bsd-hardware.info/?probe=dbb7d95d59) | Jul 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [7841057467](https://bsd-hardware.info/?probe=7841057467) | Jul 27, 2023 |
| Protectli     | VP2420                      | Desktop     | [87d17e77a8](https://bsd-hardware.info/?probe=87d17e77a8) | Jul 26, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [e266a42fa5](https://bsd-hardware.info/?probe=e266a42fa5) | Jul 26, 2023 |
| CONTEC        | G1/EMB-CV1/iD2550           | Desktop     | [34f5c817fb](https://bsd-hardware.info/?probe=34f5c817fb) | Jul 26, 2023 |
| HP            | 17E2                        | Mini pc     | [61d1f4cd45](https://bsd-hardware.info/?probe=61d1f4cd45) | Jul 25, 2023 |
| Dell          | Inspiron 3180               | Notebook    | [e97b5d9219](https://bsd-hardware.info/?probe=e97b5d9219) | Jul 25, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [103e75cb64](https://bsd-hardware.info/?probe=103e75cb64) | Jul 25, 2023 |
| Deciso        | Netboard A20                | Notebook    | [9030d92418](https://bsd-hardware.info/?probe=9030d92418) | Jul 25, 2023 |
| HP            | 339A                        | Desktop     | [b770568bae](https://bsd-hardware.info/?probe=b770568bae) | Jul 25, 2023 |
| Seeed Stud... | ODYSSEY-TGL-A               | Desktop     | [11ee31d0b3](https://bsd-hardware.info/?probe=11ee31d0b3) | Jul 24, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [461ad23cc9](https://bsd-hardware.info/?probe=461ad23cc9) | Jul 24, 2023 |
| HP            | 1495                        | Desktop     | [3ddc49b877](https://bsd-hardware.info/?probe=3ddc49b877) | Jul 24, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [1ac1ddd084](https://bsd-hardware.info/?probe=1ac1ddd084) | Jul 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [bbae253aa2](https://bsd-hardware.info/?probe=bbae253aa2) | Jul 23, 2023 |
| HP            | 1495                        | Desktop     | [9de7021e50](https://bsd-hardware.info/?probe=9de7021e50) | Jul 23, 2023 |
| Protectli     | VP2420                      | Desktop     | [7f388b0128](https://bsd-hardware.info/?probe=7f388b0128) | Jul 23, 2023 |
| MSI           | H81M-P33                    | Desktop     | [14b1509851](https://bsd-hardware.info/?probe=14b1509851) | Jul 23, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [7b725a65c4](https://bsd-hardware.info/?probe=7b725a65c4) | Jul 23, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [877ddd1995](https://bsd-hardware.info/?probe=877ddd1995) | Jul 23, 2023 |
| Premio        | BlueCat XMB3 00C            | Desktop     | [974c8673b7](https://bsd-hardware.info/?probe=974c8673b7) | Jul 23, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [a2f320b278](https://bsd-hardware.info/?probe=a2f320b278) | Jul 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [4d91799b3c](https://bsd-hardware.info/?probe=4d91799b3c) | Jul 23, 2023 |
| PC Engines    | APU2                        | Desktop     | [e02df69b63](https://bsd-hardware.info/?probe=e02df69b63) | Jul 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [fb0affa930](https://bsd-hardware.info/?probe=fb0affa930) | Jul 23, 2023 |
| Intel         | S1200KP AAG34877-201        | Desktop     | [26d7c98e18](https://bsd-hardware.info/?probe=26d7c98e18) | Jul 22, 2023 |
| Acer          | Spin SP314-21               | Convertible | [375c9f30cd](https://bsd-hardware.info/?probe=375c9f30cd) | Jul 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [36ccde4a75](https://bsd-hardware.info/?probe=36ccde4a75) | Jul 22, 2023 |
| ASRock        | 970 Extreme3 R2.0           | Desktop     | [89f4d8e6a0](https://bsd-hardware.info/?probe=89f4d8e6a0) | Jul 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [267063ed35](https://bsd-hardware.info/?probe=267063ed35) | Jul 22, 2023 |
| HP            | ProBook x360 11 G7 Educa... | Convertible | [22e1b9f0d5](https://bsd-hardware.info/?probe=22e1b9f0d5) | Jul 22, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [db56801c55](https://bsd-hardware.info/?probe=db56801c55) | Jul 21, 2023 |
| Unknown       | QGLK03                      | Desktop     | [d7396cc0e8](https://bsd-hardware.info/?probe=d7396cc0e8) | Jul 21, 2023 |
| Shuttle       | FX48 V10                    | Desktop     | [c0ac40d196](https://bsd-hardware.info/?probe=c0ac40d196) | Jul 21, 2023 |
| Toshiba       | Satellite L655              | Notebook    | [67080aeb1d](https://bsd-hardware.info/?probe=67080aeb1d) | Jul 20, 2023 |
| HPE           | ProLiant DL360 Gen10        | Server      | [115edf7c58](https://bsd-hardware.info/?probe=115edf7c58) | Jul 20, 2023 |
| HP            | 3397                        | Desktop     | [c6d7ddd8e8](https://bsd-hardware.info/?probe=c6d7ddd8e8) | Jul 19, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [5b3f040896](https://bsd-hardware.info/?probe=5b3f040896) | Jul 19, 2023 |
| HP            | 81C5 MVB                    | Desktop     | [1a4fbc384d](https://bsd-hardware.info/?probe=1a4fbc384d) | Jul 19, 2023 |
| Intel         | HURONRIVER                  | Desktop     | [b7f28022b2](https://bsd-hardware.info/?probe=b7f28022b2) | Jul 19, 2023 |
| HP            | 1495                        | Desktop     | [174216c4d3](https://bsd-hardware.info/?probe=174216c4d3) | Jul 18, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [fe07363baa](https://bsd-hardware.info/?probe=fe07363baa) | Jul 18, 2023 |
| ASUSTek       | PRIME B560M-A AC            | Desktop     | [13985f2c0c](https://bsd-hardware.info/?probe=13985f2c0c) | Jul 18, 2023 |
| Lenovo        | ThinkServer TS140           | Desktop     | [b5f034579d](https://bsd-hardware.info/?probe=b5f034579d) | Jul 17, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [aeb5bc8b52](https://bsd-hardware.info/?probe=aeb5bc8b52) | Jul 17, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [3a5b0b3193](https://bsd-hardware.info/?probe=3a5b0b3193) | Jul 17, 2023 |
| Lenovo        | ThinkPad X395 20NLCTO1WW    | Notebook    | [826ba238d8](https://bsd-hardware.info/?probe=826ba238d8) | Jul 16, 2023 |
| Lenovo        | ThinkPad X395 20NLCTO1WW    | Notebook    | [0273f2f271](https://bsd-hardware.info/?probe=0273f2f271) | Jul 16, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [93dd663d57](https://bsd-hardware.info/?probe=93dd663d57) | Jul 16, 2023 |
| ASUSTek       | H97M-E                      | Desktop     | [82bc9b32bd](https://bsd-hardware.info/?probe=82bc9b32bd) | Jul 16, 2023 |
| HP            | 8103 A01                    | Mini pc     | [17401bacdc](https://bsd-hardware.info/?probe=17401bacdc) | Jul 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [a0b045dfd2](https://bsd-hardware.info/?probe=a0b045dfd2) | Jul 15, 2023 |
| HP            | 1495                        | Desktop     | [7756cc81eb](https://bsd-hardware.info/?probe=7756cc81eb) | Jul 15, 2023 |
| Supermicro    | X9DRD-iF                    | Server      | [62035a5d06](https://bsd-hardware.info/?probe=62035a5d06) | Jul 15, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [5f7014bcb6](https://bsd-hardware.info/?probe=5f7014bcb6) | Jul 15, 2023 |
| PC Engines    | APU2                        | Desktop     | [167d51d317](https://bsd-hardware.info/?probe=167d51d317) | Jul 14, 2023 |
| 10ZiG Tech... | 5900q                       | Notebook    | [3c3668fcd2](https://bsd-hardware.info/?probe=3c3668fcd2) | Jul 14, 2023 |
| HP            | 8055                        | Desktop     | [1274fc1b5e](https://bsd-hardware.info/?probe=1274fc1b5e) | Jul 14, 2023 |
| Protectli     | VP2420                      | Desktop     | [26957c4a08](https://bsd-hardware.info/?probe=26957c4a08) | Jul 14, 2023 |
| Sophos        | SG                          | Firewall    | [61bd0223ab](https://bsd-hardware.info/?probe=61bd0223ab) | Jul 14, 2023 |
| HP            | 8299                        | Desktop     | [5874bc1020](https://bsd-hardware.info/?probe=5874bc1020) | Jul 14, 2023 |
| Protectli     | FW6                         | Desktop     | [f337c2d283](https://bsd-hardware.info/?probe=f337c2d283) | Jul 13, 2023 |
| PC Engines    | APU2                        | Desktop     | [a1af1a8c1d](https://bsd-hardware.info/?probe=a1af1a8c1d) | Jul 13, 2023 |
| ASUSTek       | STRIX H270I GAMING          | Desktop     | [f1899c02c1](https://bsd-hardware.info/?probe=f1899c02c1) | Jul 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [88fae8d98c](https://bsd-hardware.info/?probe=88fae8d98c) | Jul 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [1516e2960a](https://bsd-hardware.info/?probe=1516e2960a) | Jul 13, 2023 |
| Dell          | 02YYK5 A00                  | Desktop     | [32b118286e](https://bsd-hardware.info/?probe=32b118286e) | Jul 13, 2023 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [91965a9c00](https://bsd-hardware.info/?probe=91965a9c00) | Jul 13, 2023 |
| Dell          | 0RC130 A03                  | Server      | [01cb31f643](https://bsd-hardware.info/?probe=01cb31f643) | Jul 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [c580a701d0](https://bsd-hardware.info/?probe=c580a701d0) | Jul 12, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [4ec99c1909](https://bsd-hardware.info/?probe=4ec99c1909) | Jul 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [7e735a2b8f](https://bsd-hardware.info/?probe=7e735a2b8f) | Jul 12, 2023 |
| ASUSTek       | PRIME B760M-A D4            | Desktop     | [d13984b682](https://bsd-hardware.info/?probe=d13984b682) | Jul 12, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [3658cb969a](https://bsd-hardware.info/?probe=3658cb969a) | Jul 11, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [63f0cba062](https://bsd-hardware.info/?probe=63f0cba062) | Jul 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [fe3184dd5b](https://bsd-hardware.info/?probe=fe3184dd5b) | Jul 10, 2023 |
| ASUSTek       | PRIME B760M-A D4            | Desktop     | [a24f2cca34](https://bsd-hardware.info/?probe=a24f2cca34) | Jul 10, 2023 |
| Dell          | 0HFG24 A02                  | Server      | [153d52d1c3](https://bsd-hardware.info/?probe=153d52d1c3) | Jul 10, 2023 |
| PC Engines    | apu4                        | Desktop     | [8f0a65309f](https://bsd-hardware.info/?probe=8f0a65309f) | Jul 10, 2023 |
| HP            | 8299                        | Desktop     | [9cfe218328](https://bsd-hardware.info/?probe=9cfe218328) | Jul 10, 2023 |
| PC Engines    | apu4                        | Desktop     | [b82b8da585](https://bsd-hardware.info/?probe=b82b8da585) | Jul 10, 2023 |
| AZW           | EQ                          | Desktop     | [46754d358b](https://bsd-hardware.info/?probe=46754d358b) | Jul 10, 2023 |
| AZW           | EQ                          | Desktop     | [3f38b7c248](https://bsd-hardware.info/?probe=3f38b7c248) | Jul 10, 2023 |
| Protectli     | VP2420                      | Desktop     | [83135eaeca](https://bsd-hardware.info/?probe=83135eaeca) | Jul 10, 2023 |
| HP            | 802E                        | Desktop     | [298896b37a](https://bsd-hardware.info/?probe=298896b37a) | Jul 09, 2023 |
| Unknown       | QCML03                      | Desktop     | [63a27fdd5b](https://bsd-hardware.info/?probe=63a27fdd5b) | Jul 09, 2023 |
| Intel         | DH55TC AAE70932-206         | Desktop     | [bbfc2c35b1](https://bsd-hardware.info/?probe=bbfc2c35b1) | Jul 09, 2023 |
| MSI           | H81M-P33                    | Desktop     | [f0de15f4e2](https://bsd-hardware.info/?probe=f0de15f4e2) | Jul 09, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [3bb3ebc39d](https://bsd-hardware.info/?probe=3bb3ebc39d) | Jul 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [87bb7727a2](https://bsd-hardware.info/?probe=87bb7727a2) | Jul 09, 2023 |
| Getac         | F110G2                      | Notebook    | [b7b9efc38d](https://bsd-hardware.info/?probe=b7b9efc38d) | Jul 09, 2023 |
| Seeed Stud... | ODYSSEY-TGL-A               | Desktop     | [264f689c35](https://bsd-hardware.info/?probe=264f689c35) | Jul 09, 2023 |
| Supermicro    | X10SDV-TLN4F                | Server      | [46021c73ca](https://bsd-hardware.info/?probe=46021c73ca) | Jul 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [7395b234bc](https://bsd-hardware.info/?probe=7395b234bc) | Jul 09, 2023 |
| Sophos        | XG                          | Firewall    | [4c98fc4092](https://bsd-hardware.info/?probe=4c98fc4092) | Jul 09, 2023 |
| Acer          | Aspire XC-830               | Desktop     | [b121db09fb](https://bsd-hardware.info/?probe=b121db09fb) | Jul 09, 2023 |
| Protectli     | FW1 Ver                     | Desktop     | [f5844f1fbd](https://bsd-hardware.info/?probe=f5844f1fbd) | Jul 09, 2023 |
| Protectli     | VP2410 10                   | Desktop     | [75f3eb7e81](https://bsd-hardware.info/?probe=75f3eb7e81) | Jul 08, 2023 |
| Lenovo        | ThinkPad T480s 20L8S45W0... | Notebook    | [80ac9dddda](https://bsd-hardware.info/?probe=80ac9dddda) | Jul 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [80eb767d39](https://bsd-hardware.info/?probe=80eb767d39) | Jul 08, 2023 |
| HP            | 3397                        | Desktop     | [3d32ba4cd9](https://bsd-hardware.info/?probe=3d32ba4cd9) | Jul 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [a780f8f8ad](https://bsd-hardware.info/?probe=a780f8f8ad) | Jul 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [273d642ff6](https://bsd-hardware.info/?probe=273d642ff6) | Jul 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [b07e2a5b47](https://bsd-hardware.info/?probe=b07e2a5b47) | Jul 08, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [2100c4c1d0](https://bsd-hardware.info/?probe=2100c4c1d0) | Jul 07, 2023 |
| HP            | 1495                        | Desktop     | [3e7cdee510](https://bsd-hardware.info/?probe=3e7cdee510) | Jul 07, 2023 |
| Lenovo        | ThinkCentre M81 7518E1U     | Desktop     | [2c818e6169](https://bsd-hardware.info/?probe=2c818e6169) | Jul 06, 2023 |
| AZW           | EQ                          | Desktop     | [158f9680b5](https://bsd-hardware.info/?probe=158f9680b5) | Jul 06, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/USA/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| OPNsense 23.1.11  | 117       | 2.62%   |
| OPNsense 21.7.7   | 90        | 2.01%   |
| OPNsense 22.7.10  | 82        | 1.83%   |
| OPNsense 23.1     | 80        | 1.79%   |
| OPNsense 21.7.3   | 77        | 1.72%   |
| OPNsense 23.1.7   | 69        | 1.54%   |
| OPNsense 21.7.1   | 69        | 1.54%   |
| OPNsense 23.1.1   | 68        | 1.52%   |
| OPNsense 22.1     | 68        | 1.52%   |
| OPNsense 23.7.9   | 67        | 1.5%    |
| OPNsense 23.7.10  | 67        | 1.5%    |
| OPNsense 21.1.5   | 67        | 1.5%    |
| OPNsense 22.1.10  | 66        | 1.48%   |
| helloSystem 0.7.0 | 66        | 1.48%   |
| OPNsense 23.1.5   | 65        | 1.45%   |
| OPNsense 22.7.4   | 65        | 1.45%   |
| OPNsense 20.7.8   | 61        | 1.36%   |
| OPNsense 21.1.4   | 60        | 1.34%   |
| helloSystem 0.8.1 | 60        | 1.34%   |
| FreeBSD 13.0      | 60        | 1.34%   |
| OPNsense 23.7.1   | 58        | 1.3%    |
| OPNsense 22.1.8   | 58        | 1.3%    |
| OPNsense 21.1.3   | 58        | 1.3%    |
| FreeBSD 13.1      | 57        | 1.27%   |
| OPNsense 23.1.9   | 54        | 1.21%   |
| OPNsense 23.1.6   | 54        | 1.21%   |
| OPNsense 23.7.7   | 53        | 1.18%   |
| OPNsense 23.7.3   | 53        | 1.18%   |
| OPNsense 21.1     | 51        | 1.14%   |
| OPNsense 22.7.9   | 50        | 1.12%   |
| OPNsense 22.7.6   | 50        | 1.12%   |
| OPNsense 21.1.8   | 50        | 1.12%   |
| OPNsense 23.7     | 48        | 1.07%   |
| helloSystem 0.8.0 | 48        | 1.07%   |
| OPNsense 22.7.8   | 45        | 1.01%   |
| OPNsense 22.7.2   | 45        | 1.01%   |
| OPNsense 23.7.8   | 43        | 0.96%   |
| OPNsense 22.7.11  | 43        | 0.96%   |
| OPNsense 22.7     | 43        | 0.96%   |
| OPNsense 22.1.6   | 42        | 0.94%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 2069      | 64.19%  |
| FreeBSD     | 568       | 17.62%  |
| helloSystem | 279       | 8.66%   |
| OpenBSD     | 106       | 3.29%   |
| GhostBSD    | 66        | 2.05%   |
| NomadBSD    | 38        | 1.18%   |
| pfSense     | 18        | 0.56%   |
| FreeNAS     | 17        | 0.53%   |
| MidnightBSD | 16        | 0.5%    |
| TrueNAS     | 11        | 0.34%   |
| NetBSD      | 10        | 0.31%   |
| HardenedBSD | 9         | 0.28%   |
| DragonFly   | 6         | 0.19%   |
| XigmaNAS    | 3         | 0.09%   |
| FuryBSD     | 3         | 0.09%   |
| OS108       | 2         | 0.06%   |
| MyBee       | 1         | 0.03%   |
| ClonOS      | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| amd64   | 3133      | 98.06%  |
| i386    | 30        | 0.94%   |
| arm64   | 25        | 0.78%   |
| powerpc | 3         | 0.09%   |
| evbarm  | 2         | 0.06%   |
| sparc64 | 1         | 0.03%   |
| macppc  | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 2335      | 71.67%  |
| helloDesktop  | 302       | 9.27%   |
| XFCE          | 120       | 3.68%   |
| MATE          | 95        | 2.92%   |
| KDE5          | 94        | 2.89%   |
| TWM           | 58        | 1.78%   |
| fvwm          | 58        | 1.78%   |
| GNOME         | 54        | 1.66%   |
| Openbox       | 53        | 1.63%   |
| i3            | 33        | 1.01%   |
| Cinnamon      | 12        | 0.37%   |
| Enlightenment | 8         | 0.25%   |
| LXQt          | 6         | 0.18%   |
| Fluxbox       | 6         | 0.18%   |
| Lumina        | 5         | 0.15%   |
| AwesomeWM     | 3         | 0.09%   |
| Xfwm4         | 2         | 0.06%   |
| Picom         | 2         | 0.06%   |
| GNUstep       | 2         | 0.06%   |
| DWM           | 2         | 0.06%   |
| Window Maker  | 1         | 0.03%   |
| spectrwm      | 1         | 0.03%   |
| sdorfehs      | 1         | 0.03%   |
| LXDE          | 1         | 0.03%   |
| KDE           | 1         | 0.03%   |
| fvwm2         | 1         | 0.03%   |
| Compton       | 1         | 0.03%   |
| CDE           | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 2361      | 73.51%  |
| X11     | 842       | 26.21%  |
| Wayland | 9         | 0.28%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 2568      | 79.36%  |
| SLiM    | 377       | 11.65%  |
| LightDM | 110       | 3.4%    |
| SDDM    | 93        | 2.87%   |
| XDM     | 49        | 1.51%   |
| GDM     | 36        | 1.11%   |
| Ly      | 3         | 0.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| Unknown         | 2403      | 73.46%  |
| en_US           | 443       | 13.54%  |
| C               | 369       | 11.28%  |
| en              | 34        | 1.04%   |
| fr_FR           | 6         | 0.18%   |
| fr              | 4         | 0.12%   |
| ru_RU           | 2         | 0.06%   |
| en_US.US-ASCII  | 2         | 0.06%   |
| en_US.ISO8859-1 | 2         | 0.06%   |
| en_GB           | 2         | 0.06%   |
| ru              | 1         | 0.03%   |
| es_CO           | 1         | 0.03%   |
| en_US.utf-8     | 1         | 0.03%   |
| de_DE           | 1         | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 2793      | 86.12%  |
| BIOS | 450       | 13.88%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ufs     | 1620      | 49.17%  |
| Zfs     | 1465      | 44.46%  |
| Ffs     | 106       | 3.22%   |
| Cd9660  | 97        | 2.94%   |
| Hammer2 | 6         | 0.18%   |
| Unknown | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 2987      | 92.59%  |
| MBR     | 208       | 6.45%   |
| Unknown | 24        | 0.74%   |
| BSD     | 7         | 0.22%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 524       | 16.41%  |
| Hewlett-Packard         | 316       | 9.9%    |
| Lenovo                  | 291       | 9.11%   |
| Unknown                 | 266       | 8.33%   |
| Supermicro              | 252       | 7.89%   |
| Protectli               | 235       | 7.36%   |
| ASUSTek Computer        | 198       | 6.2%    |
| Intel                   | 135       | 4.23%   |
| ASRock                  | 115       | 3.6%    |
| Gigabyte Technology     | 89        | 2.79%   |
| MSI                     | 82        | 2.57%   |
| AMI                     | 58        | 1.82%   |
| Apple                   | 53        | 1.66%   |
| PC Engines              | 42        | 1.32%   |
| Acer                    | 35        | 1.1%    |
| Techvision              | 27        | 0.85%   |
| AZW                     | 27        | 0.85%   |
| Sophos                  | 24        | 0.75%   |
| Deciso                  | 22        | 0.69%   |
| Google                  | 16        | 0.5%    |
| MW                      | 15        | 0.47%   |
| CWWK                    | 14        | 0.44%   |
| Toshiba                 | 13        | 0.41%   |
| Biostar                 | 13        | 0.41%   |
| CompuLab                | 12        | 0.38%   |
| ASRockRack              | 12        | 0.38%   |
| BESSTAR Tech            | 11        | 0.34%   |
| AWOW                    | 11        | 0.34%   |
| System76                | 10        | 0.31%   |
| Shuttle                 | 10        | 0.31%   |
| Seeed Studio            | 9         | 0.28%   |
| Fujitsu                 | 9         | 0.28%   |
| Raspberry Pi Foundation | 8         | 0.25%   |
| Foxconn                 | 8         | 0.25%   |
| Hardkernel              | 7         | 0.22%   |
| GoWin Solution          | 7         | 0.22%   |
| Framework               | 7         | 0.22%   |
| CheckPoint              | 7         | 0.22%   |
| ZOTAC                   | 6         | 0.19%   |
| IceWhale Technology     | 6         | 0.19%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 274       | 8.58%   |
| Protectli FW4B                      | 75        | 2.35%   |
| Supermicro Super Server             | 66        | 2.07%   |
| Protectli FW6                       | 62        | 1.94%   |
| AMI Aptio CRB                       | 52        | 1.63%   |
| Intel Q3XXG4-P V1.0                 | 42        | 1.32%   |
| HP t730 Thin Client                 | 29        | 0.91%   |
| Dell OptiPlex 9020                  | 28        | 0.88%   |
| Techvision TVI7309X                 | 27        | 0.85%   |
| Dell PowerEdge R210 II              | 26        | 0.81%   |
| Dell OptiPlex 3020                  | 26        | 0.81%   |
| HP t620 PLUS Quad Core TC           | 25        | 0.78%   |
| ASUS All Series                     | 25        | 0.78%   |
| Supermicro X9SCL/X9SCM              | 21        | 0.66%   |
| Supermicro X10SLH-N6-ST031          | 21        | 0.66%   |
| PC Engines APU2                     | 20        | 0.63%   |
| Dell OptiPlex 7010                  | 20        | 0.63%   |
| PC Engines apu4                     | 17        | 0.53%   |
| Protectli VP2420                    | 15        | 0.47%   |
| Protectli VP2410                    | 15        | 0.47%   |
| MW GMLK-2_5G4L                      | 15        | 0.47%   |
| Protectli FW4C                      | 14        | 0.44%   |
| Protectli FW2B                      | 14        | 0.44%   |
| Dell Wyse 5070 Extended Thin Client | 14        | 0.44%   |
| Dell OptiPlex 7040                  | 14        | 0.44%   |
| Dell OptiPlex 990                   | 13        | 0.41%   |
| Sophos XG                           | 12        | 0.38%   |
| HP EliteDesk 800 G1 SFF             | 12        | 0.38%   |
| CompuLab fitlet2                    | 12        | 0.38%   |
| Supermicro A1SAi                    | 11        | 0.34%   |
| Protectli FW1                       | 11        | 0.34%   |
| HP EliteDesk 800 G3 SFF             | 11        | 0.34%   |
| AZW EQ                              | 11        | 0.34%   |
| Sophos SG                           | 10        | 0.31%   |
| Dell OptiPlex 9010                  | 10        | 0.31%   |
| Dell OptiPlex 790                   | 10        | 0.31%   |
| Dell OptiPlex 3040                  | 10        | 0.31%   |
| Deciso Netboard A20                 | 10        | 0.31%   |
| Intel Nobilis                       | 9         | 0.28%   |
| HP ProDesk 600 G1 SFF               | 9         | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Unknown                    | 274       | 8.58%   |
| Dell OptiPlex              | 214       | 6.7%    |
| Lenovo ThinkPad            | 158       | 4.95%   |
| Dell PowerEdge             | 133       | 4.17%   |
| Lenovo ThinkCentre         | 77        | 2.41%   |
| Protectli FW4B             | 75        | 2.35%   |
| Supermicro Super           | 66        | 2.07%   |
| Protectli FW6              | 62        | 1.94%   |
| HP EliteDesk               | 52        | 1.63%   |
| AMI Aptio                  | 52        | 1.63%   |
| Dell Inspiron              | 49        | 1.53%   |
| Dell Latitude              | 45        | 1.41%   |
| Intel Q3XXG4-P             | 43        | 1.35%   |
| HP ProDesk                 | 34        | 1.06%   |
| Dell Precision             | 33        | 1.03%   |
| ASUS ROG                   | 32        | 1%      |
| HP t730                    | 29        | 0.91%   |
| ASUS TUF                   | 28        | 0.88%   |
| Techvision TVI7309X        | 27        | 0.85%   |
| HP t620                    | 27        | 0.85%   |
| HP Compaq                  | 27        | 0.85%   |
| ASUS PRIME                 | 27        | 0.85%   |
| ASUS All                   | 25        | 0.78%   |
| HP Pavilion                | 24        | 0.75%   |
| HP ProLiant                | 22        | 0.69%   |
| Supermicro X9SCL           | 21        | 0.66%   |
| Supermicro X10SLH-N6-ST031 | 21        | 0.66%   |
| PC Engines APU2            | 20        | 0.63%   |
| Acer Aspire                | 18        | 0.56%   |
| PC Engines apu4            | 17        | 0.53%   |
| Dell Wyse                  | 17        | 0.53%   |
| Protectli VP2420           | 15        | 0.47%   |
| Protectli VP2410           | 15        | 0.47%   |
| MW GMLK-2                  | 15        | 0.47%   |
| Lenovo IdeaPad             | 15        | 0.47%   |
| ASRock X570                | 15        | 0.47%   |
| Protectli FW4C             | 14        | 0.44%   |
| Protectli FW2B             | 14        | 0.44%   |
| Dell XPS                   | 13        | 0.41%   |
| Sophos XG                  | 12        | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 396       | 12.4%   |
| 2022    | 303       | 9.49%   |
| 2019    | 298       | 9.33%   |
| 2020    | 269       | 8.42%   |
| 2021    | 262       | 8.21%   |
| 2016    | 237       | 7.42%   |
| 2014    | 211       | 6.61%   |
| 2013    | 180       | 5.64%   |
| 2011    | 176       | 5.51%   |
| 2015    | 170       | 5.32%   |
| 2017    | 160       | 5.01%   |
| 2012    | 156       | 4.89%   |
| 2023    | 114       | 3.57%   |
| 2010    | 76        | 2.38%   |
| 2009    | 50        | 1.57%   |
| 2008    | 47        | 1.47%   |
| Unknown | 42        | 1.32%   |
| 2007    | 22        | 0.69%   |
| 2006    | 15        | 0.47%   |
| 2004    | 4         | 0.13%   |
| 2005    | 2         | 0.06%   |
| 2003    | 1         | 0.03%   |
| 2002    | 1         | 0.03%   |
| 2001    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 2037      | 63.8%   |
| Notebook       | 533       | 16.69%  |
| Server         | 312       | 9.77%   |
| Mini pc        | 233       | 7.3%    |
| Firewall       | 33        | 1.03%   |
| Convertible    | 20        | 0.63%   |
| System on chip | 17        | 0.53%   |
| All in one     | 8         | 0.25%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3071      | 96.18%  |
| Yes  | 122       | 3.82%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 1162      | 35.41%  |
| 16.01-24.0      | 844       | 25.72%  |
| 4.01-8.0        | 486       | 14.81%  |
| 32.01-64.0      | 407       | 12.4%   |
| 64.01-256.0     | 184       | 5.61%   |
| 24.01-32.0      | 66        | 2.01%   |
| 2.01-3.0        | 65        | 1.98%   |
| 3.01-4.0        | 32        | 0.98%   |
| 0.51-1.0        | 15        | 0.46%   |
| 1.01-2.0        | 9         | 0.27%   |
| 0.01-0.5        | 7         | 0.21%   |
| More than 256.0 | 5         | 0.15%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 1421      | 42.58%  |
| 0.51-1.0    | 1074      | 32.18%  |
| 1.01-2.0    | 500       | 14.98%  |
| 2.01-3.0    | 96        | 2.88%   |
| 4.01-8.0    | 70        | 2.1%    |
| 3.01-4.0    | 50        | 1.5%    |
| 8.01-16.0   | 41        | 1.23%   |
| 16.01-24.0  | 19        | 0.57%   |
| 24.01-32.0  | 18        | 0.54%   |
| Unknown     | 15        | 0.45%   |
| 32.01-64.0  | 14        | 0.42%   |
| 0           | 13        | 0.39%   |
| 64.01-256.0 | 6         | 0.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 2257      | 68.25%  |
| 2      | 433       | 13.09%  |
| 0      | 319       | 9.65%   |
| 3      | 118       | 3.57%   |
| 4      | 51        | 1.54%   |
| 5      | 34        | 1.03%   |
| 6      | 25        | 0.76%   |
| 7      | 14        | 0.42%   |
| 8      | 9         | 0.27%   |
| 14     | 8         | 0.24%   |
| 10     | 7         | 0.21%   |
| 12     | 6         | 0.18%   |
| 9      | 6         | 0.18%   |
| 11     | 4         | 0.12%   |
| 21     | 2         | 0.06%   |
| 18     | 2         | 0.06%   |
| 17     | 2         | 0.06%   |
| 58     | 1         | 0.03%   |
| 40     | 1         | 0.03%   |
| 30     | 1         | 0.03%   |
| 28     | 1         | 0.03%   |
| 26     | 1         | 0.03%   |
| 22     | 1         | 0.03%   |
| 19     | 1         | 0.03%   |
| 16     | 1         | 0.03%   |
| 15     | 1         | 0.03%   |
| 13     | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2551      | 79.03%  |
| Yes       | 677       | 20.97%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3062      | 95.9%   |
| No        | 131       | 4.1%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2146      | 66.58%  |
| Yes       | 1077      | 33.42%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2462      | 76.51%  |
| Yes       | 756       | 23.49%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| USA     | 3193      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Seattle        | 55        | 1.55%   |
| New York       | 49        | 1.38%   |
| Brooklyn       | 49        | 1.38%   |
| Denver         | 47        | 1.33%   |
| Chicago        | 47        | 1.33%   |
| Los Angeles    | 39        | 1.1%    |
| Portland       | 36        | 1.02%   |
| Dallas         | 34        | 0.96%   |
| Austin         | 31        | 0.87%   |
| Atlanta        | 26        | 0.73%   |
| San Francisco  | 25        | 0.71%   |
| Phoenix        | 24        | 0.68%   |
| Rochester      | 23        | 0.65%   |
| Columbus       | 22        | 0.62%   |
| Mountain View  | 20        | 0.56%   |
| Houston        | 19        | 0.54%   |
| Grand Rapids   | 19        | 0.54%   |
| Springfield    | 18        | 0.51%   |
| Oakland        | 18        | 0.51%   |
| San Jose       | 16        | 0.45%   |
| San Antonio    | 16        | 0.45%   |
| Las Vegas      | 16        | 0.45%   |
| Philadelphia   | 15        | 0.42%   |
| Orlando        | 15        | 0.42%   |
| Charlotte      | 15        | 0.42%   |
| Ypsilanti      | 14        | 0.4%    |
| Omaha          | 14        | 0.4%    |
| Oklahoma City  | 14        | 0.4%    |
| Minneapolis    | 14        | 0.4%    |
| Jacksonville   | 14        | 0.4%    |
| Raleigh        | 13        | 0.37%   |
| Kansas City    | 13        | 0.37%   |
| Salt Lake City | 12        | 0.34%   |
| Salem          | 12        | 0.34%   |
| Pittsburgh     | 12        | 0.34%   |
| Milwaukee      | 12        | 0.34%   |
| Indianapolis   | 12        | 0.34%   |
| Washington     | 11        | 0.31%   |
| Saint Paul     | 11        | 0.31%   |
| Harrisburg     | 11        | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 602       | 1171   | 16.28%  |
| WDC                 | 440       | 1324   | 11.9%   |
| Seagate             | 317       | 849    | 8.57%   |
| Kingston            | 247       | 337    | 6.68%   |
| Crucial             | 184       | 286    | 4.98%   |
| Intel               | 166       | 314    | 4.49%   |
| SanDisk             | 159       | 212    | 4.3%    |
| Toshiba             | 135       | 231    | 3.65%   |
| Transcend           | 124       | 229    | 3.35%   |
| SK hynix            | 82        | 117    | 2.22%   |
| Hoodisk             | 77        | 109    | 2.08%   |
| China               | 76        | 116    | 2.06%   |
| A-DATA Technology   | 73        | 114    | 1.97%   |
| Hitachi             | 70        | 167    | 1.89%   |
| Protectli           | 66        | 108    | 1.79%   |
| PNY                 | 66        | 99     | 1.79%   |
| Phison              | 66        | 106    | 1.79%   |
| SPCC                | 60        | 106    | 1.62%   |
| HGST                | 43        | 129    | 1.16%   |
| Hewlett-Packard     | 42        | 121    | 1.14%   |
| Micron Technology   | 39        | 55     | 1.05%   |
| Dogfish             | 34        | 58     | 0.92%   |
| Team                | 30        | 53     | 0.81%   |
| BIWIN               | 28        | 46     | 0.76%   |
| FORESEE             | 27        | 42     | 0.73%   |
| NVMe                | 26        | 36     | 0.7%    |
| OCZ                 | 24        | 35     | 0.65%   |
| Apple               | 23        | 27     | 0.62%   |
| Silicon Motion      | 18        | 27     | 0.49%   |
| Apacer              | 17        | 23     | 0.46%   |
| Corsair             | 16        | 45     | 0.43%   |
| Mushkin             | 15        | 22     | 0.41%   |
| KIOXIA              | 15        | 21     | 0.41%   |
| KingSpec            | 15        | 19     | 0.41%   |
| Lexar               | 14        | 21     | 0.38%   |
| Fanxiang            | 13        | 19     | 0.35%   |
| Patriot             | 12        | 15     | 0.32%   |
| LITEON              | 11        | 17     | 0.3%    |
| Zheino              | 10        | 18     | 0.27%   |
| Supermicro          | 10        | 10     | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB       | 34        | 0.84%   |
| Kingston SA400S37240G 240GB     | 34        | 0.84%   |
| Hoodisk SSD 32GB                | 32        | 0.79%   |
| Samsung SSD 970 EVO Plus 500GB  | 27        | 0.67%   |
| Samsung SSD 860 EVO 500GB       | 26        | 0.64%   |
| Kingston SUV500MS240G 240GB     | 25        | 0.62%   |
| Kingston SA400S37120G 120GB     | 24        | 0.59%   |
| Seagate ST500DM002-1BD142 500GB | 23        | 0.57%   |
| Samsung SSD 860 EVO 250GB       | 22        | 0.54%   |
| Samsung SSD 860 EVO 1TB         | 22        | 0.54%   |
| Kingston SUV500MS120G 120GB     | 22        | 0.54%   |
| Hoodisk SSD 128GB               | 22        | 0.54%   |
| PNY CS900 120GB SSD             | 21        | 0.52%   |
| Crucial CT500MX500SSD1 500GB    | 21        | 0.52%   |
| Samsung SSD 850 EVO 500GB       | 20        | 0.49%   |
| Samsung SSD 970 EVO Plus 1TB    | 19        | 0.47%   |
| Protectli 120GB mSATA           | 19        | 0.47%   |
| BIWIN SSD 128GB                 | 19        | 0.47%   |
| Kingston SV300S37A120G 120GB    | 17        | 0.42%   |
| Samsung SSD 870 EVO 500GB       | 16        | 0.4%    |
| Hoodisk SSD 64GB                | 16        | 0.4%    |
| Crucial CT250MX500SSD1 250GB    | 16        | 0.4%    |
| WDC WD800JD-75MSA3 80GB         | 15        | 0.37%   |
| SanDisk SSD PLUS 240GB          | 15        | 0.37%   |
| FORESEE 128GB SSD               | 15        | 0.37%   |
| Crucial CT1000MX500SSD1 1TB     | 15        | 0.37%   |
| Samsung SSD 860 EVO M.2 250GB   | 14        | 0.35%   |
| Phison Sabrent 1TB              | 14        | 0.35%   |
| WDC WD10EZEX-08WN4A0 1TB        | 13        | 0.32%   |
| Transcend TS256GMTS952T2 256GB  | 13        | 0.32%   |
| SPCC Solid State Disk 128GB     | 13        | 0.32%   |
| Dogfish SSD 128GB               | 13        | 0.32%   |
| China SATA SSD 120GB            | 13        | 0.32%   |
| SanDisk SDSSDA120G 120GB        | 12        | 0.3%    |
| SanDisk SDSA6MM-016G-1006 16GB  | 12        | 0.3%    |
| Protectli 64GB mSATA            | 12        | 0.3%    |
| WDC WDS500G3X0C-00SJG0 500GB    | 11        | 0.27%   |
| WDC WD30EFRX-68EUZN0 3TB        | 11        | 0.27%   |
| Transcend TS128GMSA230S 128GB   | 11        | 0.27%   |
| Toshiba DT01ACA100 1TB          | 11        | 0.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                             | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC                                | 324       | 1119   | 34.18%  |
| Seagate                            | 303       | 814    | 31.96%  |
| Toshiba                            | 104       | 190    | 10.97%  |
| Hitachi                            | 69        | 166    | 7.28%   |
| HGST                               | 43        | 125    | 4.54%   |
| Hewlett-Packard                    | 24        | 75     | 2.53%   |
| NVMe                               | 17        | 23     | 1.79%   |
| Samsung Electronics                | 13        | 19     | 1.37%   |
| Apple                              | 11        | 12     | 1.16%   |
| Fujitsu                            | 7         | 8      | 0.74%   |
| Maxtor                             | 5         | 9      | 0.53%   |
| Lexar                              | 3         | 3      | 0.32%   |
| LSI                                | 2         | 8      | 0.21%   |
| HPE                                | 2         | 7      | 0.21%   |
| China                              | 2         | 2      | 0.21%   |
| Adaptec                            | 2         | 2      | 0.21%   |
| WD MediaMax                        | 1         | 3      | 0.11%   |
| QUANTUM                            | 1         | 2      | 0.11%   |
| Product:              USB DISK 3.0 | 1         | 1      | 0.11%   |
| OPENBSD                            | 1         | 1      | 0.11%   |
| NETAPP                             | 1         | 2      | 0.11%   |
| Memorex                            | 1         | 1      | 0.11%   |
| MaxDigital                         | 1         | 1      | 0.11%   |
| MARVELL                            | 1         | 1      | 0.11%   |
| IBM/Hitachi                        | 1         | 1      | 0.11%   |
| IBM-ESXS                           | 1         | 1      | 0.11%   |
| IBM-207x                           | 1         | 1      | 0.11%   |
| HPT                                | 1         | 8      | 0.11%   |
| Generic                            | 1         | 1      | 0.11%   |
| General                            | 1         | 1      | 0.11%   |
| ExcelStor Technology               | 1         | 4      | 0.11%   |
| Dell                               | 1         | 3      | 0.11%   |
| ASMT                               | 1         | 1      | 0.11%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 391       | 784    | 18.5%   |
| Kingston            | 218       | 305    | 10.31%  |
| SanDisk             | 157       | 206    | 7.43%   |
| Crucial             | 147       | 226    | 6.95%   |
| Intel               | 119       | 245    | 5.63%   |
| Transcend           | 117       | 221    | 5.53%   |
| Hoodisk             | 76        | 108    | 3.6%    |
| China               | 74        | 114    | 3.5%    |
| Protectli           | 66        | 108    | 3.12%   |
| A-DATA Technology   | 63        | 94     | 2.98%   |
| PNY                 | 61        | 93     | 2.89%   |
| WDC                 | 52        | 90     | 2.46%   |
| SPCC                | 43        | 83     | 2.03%   |
| SK hynix            | 43        | 61     | 2.03%   |
| Dogfish             | 34        | 58     | 1.61%   |
| Phison              | 28        | 38     | 1.32%   |
| BIWIN               | 27        | 45     | 1.28%   |
| Micron Technology   | 26        | 36     | 1.23%   |
| FORESEE             | 25        | 40     | 1.18%   |
| OCZ                 | 24        | 35     | 1.14%   |
| Apacer              | 17        | 23     | 0.8%    |
| KingSpec            | 15        | 19     | 0.71%   |
| Toshiba             | 13        | 18     | 0.61%   |
| Team                | 13        | 33     | 0.61%   |
| Seagate             | 13        | 28     | 0.61%   |
| Corsair             | 13        | 18     | 0.61%   |
| Mushkin             | 12        | 18     | 0.57%   |
| Apple               | 12        | 15     | 0.57%   |
| Zheino              | 10        | 18     | 0.47%   |
| Supermicro          | 10        | 10     | 0.47%   |
| Patriot             | 10        | 13     | 0.47%   |
| OWC                 | 10        | 16     | 0.47%   |
| Lexar               | 10        | 17     | 0.47%   |
| NVMe                | 9         | 11     | 0.43%   |
| LITEONIT            | 9         | 12     | 0.43%   |
| LITEON              | 9         | 15     | 0.43%   |
| Hewlett-Packard     | 9         | 14     | 0.43%   |
| Innodisk            | 8         | 10     | 0.38%   |
| Plextor             | 7         | 12     | 0.33%   |
| Intenso             | 6         | 12     | 0.28%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1903      | 3483   | 57.11%  |
| HDD  | 789       | 2615   | 23.68%  |
| NVMe | 640       | 1073   | 19.21%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2448      | 6098   | 79.27%  |
| NVMe | 640       | 1073   | 20.73%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2033      | 3621   | 71.89%  |
| 0.51-1.0   | 443       | 895    | 15.66%  |
| 1.01-2.0   | 155       | 423    | 5.48%   |
| 4.01-10.0  | 72        | 572    | 2.55%   |
| 3.01-4.0   | 54        | 234    | 1.91%   |
| 2.01-3.0   | 49        | 197    | 1.73%   |
| 10.01-20.0 | 21        | 152    | 0.74%   |
| 20.01-50.0 | 1         | 4      | 0.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1312      | 39.47%  |
| 251-500        | 632       | 19.01%  |
| 1-20           | 322       | 9.69%   |
| 501-1000       | 320       | 9.63%   |
| 51-100         | 318       | 9.57%   |
| 21-50          | 288       | 8.66%   |
| 1001-2000      | 79        | 2.38%   |
| More than 3000 | 31        | 0.93%   |
| Unknown        | 14        | 0.42%   |
| 2001-3000      | 8         | 0.24%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2979      | 89.86%  |
| 21-50          | 184       | 5.55%   |
| 51-100         | 66        | 1.99%   |
| 101-250        | 37        | 1.12%   |
| 251-500        | 15        | 0.45%   |
| Unknown        | 14        | 0.42%   |
| More than 3000 | 7         | 0.21%   |
| 501-1000       | 7         | 0.21%   |
| 1001-2000      | 3         | 0.09%   |
| 2001-3000      | 2         | 0.06%   |
| 0              | 1         | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 8         | 12     | 1.9%    |
| Seagate ST500LM021-1KJ152 500GB       | 5         | 5      | 1.19%   |
| Kingston SV300S37A120G 120GB          | 5         | 6      | 1.19%   |
| Crucial CT275MX300SSD1 275GB          | 5         | 8      | 1.19%   |
| Apacer 16GB SATA Flash Drive          | 5         | 9      | 1.19%   |
| Seagate ST3500418AS 500GB             | 4         | 11     | 0.95%   |
| SanDisk SSD PLUS 240GB                | 4         | 5      | 0.95%   |
| Kingston SV300S37A60G 64GB            | 4         | 4      | 0.95%   |
| Kingston SMS200S3120G 120GB           | 4         | 4      | 0.95%   |
| WDC WD5003ABYX-18WERA0 500GB          | 3         | 6      | 0.71%   |
| WDC WD5000AAKX-60U6AA0 500GB          | 3         | 4      | 0.71%   |
| WDC WD30EFRX-68EUZN0 3TB              | 3         | 15     | 0.71%   |
| SK hynix SC210 mSATA 256GB            | 3         | 4      | 0.71%   |
| Seagate ST2000DM008-2FR102 2TB        | 3         | 3      | 0.71%   |
| Seagate ST1000DM003-9YN162 1TB        | 3         | 7      | 0.71%   |
| Kingston SNS4151S316GD 16GB           | 3         | 5      | 0.71%   |
| Apacer 32GB SATA Flash Drive          | 3         | 3      | 0.71%   |
| WDC WD5000AAKX-001CA0 500GB           | 2         | 4      | 0.48%   |
| WDC WD20EARS-00MVWB0 2TB              | 2         | 2      | 0.48%   |
| WDC WD2001FASS-00W2B0 2TB             | 2         | 3      | 0.48%   |
| WDC WD1600BEKT-66F3T2 160GB           | 2         | 4      | 0.48%   |
| WDC WD1600AAJS-75M0A0 160GB           | 2         | 2      | 0.48%   |
| Toshiba MQ01ABF050 500GB              | 2         | 2      | 0.48%   |
| Toshiba MQ01ABD100 1TB                | 2         | 2      | 0.48%   |
| Toshiba DT01ACA050 500GB              | 2         | 2      | 0.48%   |
| SSSTC CVB-8D128-HP 128GB              | 2         | 2      | 0.48%   |
| SPCC Solid State Disk 512GB           | 2         | 3      | 0.48%   |
| SK hynix SC308 SATA 128GB             | 2         | 3      | 0.48%   |
| Seagate ST95005620AS 500GB            | 2         | 2      | 0.48%   |
| Seagate ST9500420AS 500GB             | 2         | 3      | 0.48%   |
| Seagate ST500LT012-1DG142 500GB       | 2         | 3      | 0.48%   |
| Seagate ST5000DM000-1FK178 5TB        | 2         | 3      | 0.48%   |
| Seagate ST3500413AS 500GB             | 2         | 10     | 0.48%   |
| Seagate ST31000528AS 1TB              | 2         | 2      | 0.48%   |
| Seagate ST2000DL001-9VT156 2TB        | 2         | 2      | 0.48%   |
| Samsung Electronics SSD 950 PRO 256GB | 2         | 2      | 0.48%   |
| Samsung Electronics SSD 850 EVO 500GB | 2         | 2      | 0.48%   |
| MyDigitalSSD SB2 256GB                | 2         | 4      | 0.48%   |
| Kingston SUV400S37120G 120GB          | 2         | 3      | 0.48%   |
| Kingston SNS4151S316G 16GB            | 2         | 3      | 0.48%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 85        | 148    | 20.88%  |
| WDC                 | 65        | 123    | 15.97%  |
| Kingston            | 32        | 39     | 7.86%   |
| Intel               | 31        | 38     | 7.62%   |
| Samsung Electronics | 28        | 42     | 6.88%   |
| Hitachi             | 23        | 31     | 5.65%   |
| Toshiba             | 22        | 31     | 5.41%   |
| Crucial             | 19        | 27     | 4.67%   |
| SanDisk             | 14        | 17     | 3.44%   |
| HGST                | 11        | 11     | 2.7%    |
| SK hynix            | 9         | 13     | 2.21%   |
| Apacer              | 8         | 12     | 1.97%   |
| OCZ                 | 4         | 4      | 0.98%   |
| Micron Technology   | 4         | 5      | 0.98%   |
| HP Phison           | 4         | 4      | 0.98%   |
| SPCC                | 3         | 6      | 0.74%   |
| Phison              | 3         | 3      | 0.74%   |
| Maxtor              | 3         | 6      | 0.74%   |
| LITEON              | 3         | 4      | 0.74%   |
| Apple               | 3         | 3      | 0.74%   |
| SSSTC               | 2         | 2      | 0.49%   |
| PNY                 | 2         | 2      | 0.49%   |
| Patriot             | 2         | 2      | 0.49%   |
| MyDigitalSSD        | 2         | 4      | 0.49%   |
| Corsair             | 2         | 2      | 0.49%   |
| China               | 2         | 2      | 0.49%   |
| A-DATA Technology   | 2         | 2      | 0.49%   |
| ZTC                 | 1         | 3      | 0.25%   |
| Wintec              | 1         | 1      | 0.25%   |
| WD MediaMax         | 1         | 3      | 0.25%   |
| VisionTek           | 1         | 1      | 0.25%   |
| Transcend           | 1         | 4      | 0.25%   |
| Plextor             | 1         | 1      | 0.25%   |
| LITEONIT            | 1         | 3      | 0.25%   |
| KingSpec            | 1         | 1      | 0.25%   |
| KingDian            | 1         | 1      | 0.25%   |
| KeepData            | 1         | 1      | 0.25%   |
| INDMEM              | 1         | 1      | 0.25%   |
| IBM/Hitachi         | 1         | 1      | 0.25%   |
| HPE                 | 1         | 3      | 0.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor               | Computers | Drives | Percent |
|----------------------|-----------|--------|---------|
| Seagate              | 85        | 148    | 38.46%  |
| WDC                  | 64        | 122    | 28.96%  |
| Hitachi              | 23        | 31     | 10.41%  |
| Toshiba              | 20        | 29     | 9.05%   |
| HGST                 | 11        | 11     | 4.98%   |
| Samsung Electronics  | 5         | 6      | 2.26%   |
| Maxtor               | 3         | 6      | 1.36%   |
| China                | 2         | 2      | 0.9%    |
| Apple                | 2         | 2      | 0.9%    |
| WD MediaMax          | 1         | 3      | 0.45%   |
| IBM/Hitachi          | 1         | 1      | 0.45%   |
| HPE                  | 1         | 3      | 0.45%   |
| Hewlett-Packard      | 1         | 4      | 0.45%   |
| Fujitsu              | 1         | 1      | 0.45%   |
| ExcelStor Technology | 1         | 2      | 0.45%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 212       | 371    | 53.4%   |
| SSD  | 179       | 244    | 45.09%  |
| NVMe | 6         | 6      | 1.51%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Samsung Electronics MZYLN256HCHP-000L2 256GB | 2         | 2      | 16.67%  |
| WDC WD3200L 320GB                            | 1         | 1      | 8.33%   |
| SK hynix SC308 SATA 256GB                    | 1         | 1      | 8.33%   |
| Seagate ST3500418AS 500GB                    | 1         | 2      | 8.33%   |
| SanDisk pSSD 16GB                            | 1         | 1      | 8.33%   |
| Samsung Electronics SSD 970 EVO Plus 500GB   | 1         | 1      | 8.33%   |
| Samsung Electronics PM981 NVMe 256GB         | 1         | 1      | 8.33%   |
| Samsung Electronics MZVLB256HBHQ-000H1 256GB | 1         | 1      | 8.33%   |
| Samsung Electronics HD204UI 2TB              | 1         | 2      | 8.33%   |
| Kingston SA2000M8500G 500GB                  | 1         | 2      | 8.33%   |
| Intel SSDSC2KB019T8 1.9TB                    | 1         | 2      | 8.33%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 7      | 50%     |
| WDC                 | 1         | 1      | 8.33%   |
| SK hynix            | 1         | 1      | 8.33%   |
| Seagate             | 1         | 2      | 8.33%   |
| SanDisk             | 1         | 1      | 8.33%   |
| Kingston            | 1         | 2      | 8.33%   |
| Intel               | 1         | 2      | 8.33%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 2613      | 6366   | 84.24%  |
| Malfunc  | 389       | 621    | 12.54%  |
| Detected | 88        | 168    | 2.84%   |
| Failed   | 12        | 16     | 0.39%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 2484      | 61.09%  |
| AMD                                     | 485       | 11.93%  |
| Samsung Electronics                     | 253       | 6.22%   |
| Broadcom / LSI                          | 139       | 3.42%   |
| SanDisk                                 | 123       | 3.03%   |
| Phison Electronics                      | 67        | 1.65%   |
| ASMedia Technology                      | 61        | 1.5%    |
| Silicon Motion                          | 55        | 1.35%   |
| SK hynix                                | 42        | 1.03%   |
| Marvell Technology Group                | 38        | 0.93%   |
| Micron/Crucial Technology               | 35        | 0.86%   |
| Kingston Technology Company             | 30        | 0.74%   |
| MAXIO Technology (Hangzhou)             | 26        | 0.64%   |
| Chelsio Communications                  | 26        | 0.64%   |
| Hewlett-Packard                         | 19        | 0.47%   |
| JMicron Technology                      | 18        | 0.44%   |
| Toshiba                                 | 17        | 0.42%   |
| Micron Technology                       | 17        | 0.42%   |
| KIOXIA                                  | 16        | 0.39%   |
| Nvidia                                  | 15        | 0.37%   |
| Realtek Semiconductor                   | 14        | 0.34%   |
| Adaptec                                 | 11        | 0.27%   |
| ADATA Technology                        | 8         | 0.2%    |
| Transcend                               | 7         | 0.17%   |
| Silicon Image                           | 6         | 0.15%   |
| Shenzhen Longsys Electronics            | 6         | 0.15%   |
| Seagate Technology                      | 6         | 0.15%   |
| Lite-On Technology                      | 4         | 0.1%    |
| VIA Technologies                        | 3         | 0.07%   |
| Union Memory (Shenzhen)                 | 3         | 0.07%   |
| Solid State Storage Technology          | 3         | 0.07%   |
| Silicon Integrated Systems [SiS]        | 3         | 0.07%   |
| Shenzhen Unionmemory Information System | 3         | 0.07%   |
| Hosin Global Electronics                | 3         | 0.07%   |
| Biwin Storage Technology                | 3         | 0.07%   |
| Netac Technology                        | 2         | 0.05%   |
| Lenovo                                  | 2         | 0.05%   |
| HighPoint Technologies                  | 2         | 0.05%   |
| Dell                                    | 2         | 0.05%   |
| Broadcom                                | 2         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 336       | 7.31%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 257       | 5.59%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 175       | 3.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 152       | 3.31%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 134       | 2.91%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 133       | 2.89%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 132       | 2.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 128       | 2.78%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 94        | 2.04%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 89        | 1.94%   |
| Intel SATA Controller [RAID mode]                                                | 87        | 1.89%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 86        | 1.87%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 68        | 1.48%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 66        | 1.44%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 64        | 1.39%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 62        | 1.35%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 53        | 1.15%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 52        | 1.13%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 52        | 1.13%   |
| AMD 400 Series Chipset SATA Controller                                           | 50        | 1.09%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 49        | 1.07%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 49        | 1.07%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 43        | 0.93%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 43        | 0.93%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 42        | 0.91%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 41        | 0.89%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 40        | 0.87%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                     | 40        | 0.87%   |
| AMD FCH IDE Controller                                                           | 40        | 0.87%   |
| AMD 500 Series Chipset SATA Controller                                           | 40        | 0.87%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 39        | 0.85%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 38        | 0.83%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                                 | 38        | 0.83%   |
| Phison E12 NVMe Controller                                                       | 34        | 0.74%   |
| Intel Atom processor C2000 AHCI SATA2 Controller                                 | 33        | 0.72%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 33        | 0.72%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 33        | 0.72%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 32        | 0.7%    |
| Intel unknown                                                                    | 31        | 0.67%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 30        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2632      | 64.43%  |
| NVMe | 736       | 18.02%  |
| IDE  | 351       | 8.59%   |
| RAID | 237       | 5.8%    |
| SAS  | 82        | 2.01%   |
| SCSI | 47        | 1.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 2636      | 82.38%  |
| AMD      | 530       | 16.56%  |
| ARM      | 21        | 0.66%   |
| Unknown  | 7         | 0.22%   |
| IBM      | 2         | 0.06%   |
| NXP      | 1         | 0.03%   |
| Motorola | 1         | 0.03%   |
| i        | 1         | 0.03%   |
| Broadcom | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel Celeron J4125 CPU @ 2.00GHz        | 88        | 2.71%   |
| Intel Celeron N5105 @ 2.00GHz            | 78        | 2.4%    |
| Intel Celeron CPU J3160 @ 1.60GHz        | 78        | 2.4%    |
| Intel Celeron CPU J1900 @ 1.99GHz        | 53        | 1.63%   |
| Intel Core i5-6500 CPU @ 3.20GHz         | 46        | 1.42%   |
| AMD GX-412TC SOC                         | 38        | 1.17%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 36        | 1.11%   |
| Intel Core i5-4570 CPU @ 3.20GHz         | 34        | 1.05%   |
| Intel N100                               | 32        | 0.98%   |
| AMD RX-427BB with AMD Radeon R7 Graphics | 31        | 0.95%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 29        | 0.89%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 28        | 0.86%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 27        | 0.83%   |
| AMD GX-420CA SOC with Radeon HD Graphics | 26        | 0.8%    |
| Intel Core i7-3770 CPU @ 3.40GHz         | 25        | 0.77%   |
| Intel Pentium CPU N3700 @ 1.60GHz        | 23        | 0.71%   |
| Intel Core i3-7100U CPU @ 2.40GHz        | 22        | 0.68%   |
| Intel Celeron CPU J3455 @ 1.50GHz        | 22        | 0.68%   |
| Intel Atom CPU D525 @ 1.80GHz            | 20        | 0.62%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 19        | 0.58%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 19        | 0.58%   |
| Intel Xeon D-2123IT CPU @ 2.20GHz        | 18        | 0.55%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 18        | 0.55%   |
| Intel Celeron CPU 3865U @ 1.80GHz        | 18        | 0.55%   |
| Intel Core i7-6700 CPU @ 3.40GHz         | 17        | 0.52%   |
| Intel Core i5-7500 CPU @ 3.40GHz         | 17        | 0.52%   |
| Intel Atom CPU C3558 @ 2.20GHz           | 17        | 0.52%   |
| Intel Pentium Silver N6005 @ 2.00GHz     | 16        | 0.49%   |
| Intel Core i7-4770 CPU @ 3.40GHz         | 16        | 0.49%   |
| Intel Core i5-3320M CPU @ 2.60GHz        | 16        | 0.49%   |
| Intel Core i5-2400 CPU @ 3.10GH          | 16        | 0.49%   |
| Intel Xeon CPU E3-1270 v3 @ 3.50GHz      | 15        | 0.46%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz | 15        | 0.46%   |
| Intel Pentium CPU J3710 @ 1.60GHz        | 15        | 0.46%   |
| Intel Core 2 Duo                         | 15        | 0.46%   |
| Intel Celeron J6412 @ 2.00GHz            | 15        | 0.46%   |
| Intel Celeron J4105 CPU @ 1.50GHz        | 15        | 0.46%   |
| Intel Celeron CPU J3060 @ 1.60GHz        | 15        | 0.46%   |
| Intel Core i7-4790 CPU @ 3.60GHz         | 14        | 0.43%   |
| Intel Core i5-2400 CPU @ 3.10GHz         | 14        | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 639       | 19.8%   |
| Intel Celeron           | 504       | 15.62%  |
| Intel Xeon              | 425       | 13.17%  |
| Intel Core i7           | 364       | 11.28%  |
| Intel Core i3           | 198       | 6.14%   |
| Other                   | 185       | 5.73%   |
| Intel Atom              | 152       | 4.71%   |
| AMD Ryzen 7             | 92        | 2.85%   |
| AMD GX                  | 79        | 2.45%   |
| Intel Pentium           | 77        | 2.39%   |
| AMD Ryzen 5             | 67        | 2.08%   |
| Intel Core 2 Duo        | 53        | 1.64%   |
| Intel Pentium Silver    | 34        | 1.05%   |
| AMD Ryzen 9             | 30        | 0.93%   |
| AMD EPYC                | 24        | 0.74%   |
| AMD FX                  | 23        | 0.71%   |
| AMD Ryzen 3             | 22        | 0.68%   |
| ARM Cortex              | 20        | 0.62%   |
| AMD A10                 | 19        | 0.59%   |
| Intel Core i9           | 14        | 0.43%   |
| Intel Core 2 Quad       | 13        | 0.4%    |
| AMD Ryzen 5 PRO         | 12        | 0.37%   |
| AMD Athlon              | 11        | 0.34%   |
| Intel Core 2            | 10        | 0.31%   |
| AMD Phenom II X4        | 10        | 0.31%   |
| AMD G                   | 10        | 0.31%   |
| AMD Ryzen Embedded      | 9         | 0.28%   |
| AMD A8                  | 9         | 0.28%   |
| Intel Genuine           | 8         | 0.25%   |
| AMD A6                  | 8         | 0.25%   |
| Intel Pentium Dual-Core | 7         | 0.22%   |
| AMD Opteron             | 7         | 0.22%   |
| Intel Pentium 4         | 6         | 0.19%   |
| AMD Ryzen Threadripper  | 6         | 0.19%   |
| AMD Phenom II X6        | 5         | 0.15%   |
| AMD A4                  | 5         | 0.15%   |
| Intel Xeon Gold         | 4         | 0.12%   |
| Intel Pentium M         | 4         | 0.12%   |
| AMD Ryzen 7 PRO         | 4         | 0.12%   |
| AMD E2                  | 4         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1681      | 52.04%  |
| 2       | 746       | 23.1%   |
| 8       | 214       | 6.63%   |
| 6       | 168       | 5.2%    |
| 16      | 113       | 3.5%    |
| Unknown | 108       | 3.34%   |
| 12      | 104       | 3.22%   |
| 1       | 25        | 0.77%   |
| 24      | 19        | 0.59%   |
| 32      | 18        | 0.56%   |
| 10      | 11        | 0.34%   |
| 20      | 7         | 0.22%   |
| 48      | 3         | 0.09%   |
| 36      | 3         | 0.09%   |
| 14      | 3         | 0.09%   |
| 64      | 2         | 0.06%   |
| 28      | 2         | 0.06%   |
| 3       | 2         | 0.06%   |
| 40      | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3027      | 94.59%  |
| 2       | 127       | 3.97%   |
| Unknown | 44        | 1.38%   |
| 8       | 1         | 0.03%   |
| 4       | 1         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1799      | 55.96%  |
| 2       | 1295      | 40.28%  |
| Unknown | 120       | 3.73%   |
| 4       | 1         | 0.03%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 417       | 12.91%  |
| Haswell         | 360       | 11.14%  |
| Silvermont      | 285       | 8.82%   |
| Unknown         | 273       | 8.45%   |
| IvyBridge       | 226       | 6.99%   |
| Skylake         | 215       | 6.65%   |
| SandyBridge     | 190       | 5.88%   |
| Goldmont plus   | 139       | 4.3%    |
| Broadwell       | 123       | 3.81%   |
| Goldmont        | 82        | 2.54%   |
| Westmere        | 76        | 2.35%   |
| Zen 2           | 69        | 2.14%   |
| Zen+            | 66        | 2.04%   |
| Zen 3           | 64        | 1.98%   |
| Penryn          | 63        | 1.95%   |
| Zen             | 61        | 1.89%   |
| CometLake       | 54        | 1.67%   |
| Nehalem         | 49        | 1.52%   |
| Bonnell         | 49        | 1.52%   |
| Puma            | 48        | 1.49%   |
| Core            | 48        | 1.49%   |
| Jaguar          | 47        | 1.45%   |
| Steamroller     | 41        | 1.27%   |
| Piledriver      | 39        | 1.21%   |
| TigerLake       | 33        | 1.02%   |
| K10             | 27        | 0.84%   |
| Bobcat          | 22        | 0.68%   |
| Excavator       | 20        | 0.62%   |
| NetBurst        | 16        | 0.5%    |
| K8 Hammer       | 10        | 0.31%   |
| P6              | 6         | 0.19%   |
| IceLake         | 5         | 0.15%   |
| K10 Llano       | 4         | 0.12%   |
| Bulldozer       | 2         | 0.06%   |
| K8 & K10 hybrid | 1         | 0.03%   |
| Geode           | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1971      | 61.52%  |
| AMD                                          | 492       | 15.36%  |
| Nvidia                                       | 313       | 9.77%   |
| ASPEED Technology                            | 214       | 6.68%   |
| Matrox Electronics Systems                   | 207       | 6.46%   |
| XGI Technology (eXtreme Graphics Innovation) | 4         | 0.12%   |
| Silicon Integrated Systems [SiS]             | 3         | 0.09%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                                 | 214       | 6.55%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 153       | 4.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 141       | 4.32%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 122       | 3.73%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 122       | 3.73%   |
| Intel HD Graphics 530                                                                    | 121       | 3.7%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 119       | 3.64%   |
| Intel JasperLake [UHD Graphics]                                                          | 101       | 3.09%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 90        | 2.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 89        | 2.72%   |
| Intel HD Graphics 620                                                                    | 83        | 2.54%   |
| Intel UHD Graphics 620                                                                   | 61        | 1.87%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 59        | 1.81%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 57        | 1.74%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 54        | 1.65%   |
| Matrox Electronics Systems G200eR2                                                       | 52        | 1.59%   |
| Intel HD Graphics 630                                                                    | 52        | 1.59%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 48        | 1.47%   |
| Intel HD Graphics 500                                                                    | 47        | 1.44%   |
| Intel HD Graphics 5500                                                                   | 43        | 1.32%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 39        | 1.19%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 34        | 1.04%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 33        | 1.01%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 30        | 0.92%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 29        | 0.89%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 29        | 0.89%   |
| Intel Core Processor Integrated Graphics Controller                                      | 28        | 0.86%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 28        | 0.86%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 27        | 0.83%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 26        | 0.8%    |
| AMD Kabini [Radeon HD 8400E]                                                             | 26        | 0.8%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 26        | 0.8%    |
| Intel HD Graphics 610                                                                    | 23        | 0.7%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 22        | 0.67%   |
| Intel Elkhart Lake [UHD Graphics Gen11 16EU]                                             | 22        | 0.67%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 22        | 0.67%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 22        | 0.67%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 19        | 0.58%   |
| AMD ES1000                                                                               | 19        | 0.58%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 17        | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 1799      | 55.75%  |
| 1 x AMD         | 440       | 13.63%  |
| 1 x Nvidia      | 222       | 6.88%   |
| 1 x Matrox      | 205       | 6.35%   |
| 1 x ASPEED      | 200       | 6.2%    |
| Other           | 143       | 4.43%   |
| Intel + Nvidia  | 73        | 2.26%   |
| 2 x Intel       | 70        | 2.17%   |
| Intel + AMD     | 23        | 0.71%   |
| 2 x AMD         | 13        | 0.4%    |
| AMD + Nvidia    | 12        | 0.37%   |
| Intel + ASPEED  | 8         | 0.25%   |
| Nvidia + ASPEED | 5         | 0.15%   |
| 1 x XGI         | 4         | 0.12%   |
| 2 x Nvidia      | 3         | 0.09%   |
| 1 x SiS         | 3         | 0.09%   |
| AMD + ASPEED    | 2         | 0.06%   |
| Intel + 2 x AMD | 1         | 0.03%   |
| AMD + Matrox    | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2874      | 89.45%  |
| Unknown     | 178       | 5.54%   |
| Proprietary | 161       | 5.01%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2949      | 91.41%  |
| 1.01-2.0   | 66        | 2.05%   |
| 0.01-0.5   | 58        | 1.8%    |
| 3.01-4.0   | 46        | 1.43%   |
| 7.01-8.0   | 35        | 1.08%   |
| 0.51-1.0   | 34        | 1.05%   |
| 5.01-6.0   | 21        | 0.65%   |
| 8.01-16.0  | 12        | 0.37%   |
| 2.01-3.0   | 4         | 0.12%   |
| 4.01-5.0   | 1         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 77        | 10.71%  |
| AU Optronics            | 75        | 10.43%  |
| LG Display              | 71        | 9.87%   |
| Dell                    | 69        | 9.6%    |
| BOE                     | 55        | 7.65%   |
| Chimei Innolux          | 45        | 6.26%   |
| Goldstar                | 37        | 5.15%   |
| Acer                    | 37        | 5.15%   |
| Lenovo                  | 33        | 4.59%   |
| Hewlett-Packard         | 27        | 3.76%   |
| Apple                   | 23        | 3.2%    |
| Ancor Communications    | 23        | 3.2%    |
| AOC                     | 12        | 1.67%   |
| ASUSTek Computer        | 11        | 1.53%   |
| Vizio                   | 10        | 1.39%   |
| Sharp                   | 10        | 1.39%   |
| ViewSonic               | 9         | 1.25%   |
| Sceptre Tech            | 8         | 1.11%   |
| Chi Mei Optoelectronics | 8         | 1.11%   |
| BenQ                    | 8         | 1.11%   |
| LG Electronics          | 7         | 0.97%   |
| InfoVision              | 5         | 0.7%    |
| Sony                    | 3         | 0.42%   |
| Philips                 | 3         | 0.42%   |
| MSI                     | 3         | 0.42%   |
| LGD                     | 3         | 0.42%   |
| Lenovo Group Limited    | 3         | 0.42%   |
| Insignia                | 3         | 0.42%   |
| HannStar                | 3         | 0.42%   |
| Westinghouse            | 2         | 0.28%   |
| NEC Computers           | 2         | 0.28%   |
| LG Philips              | 2         | 0.28%   |
| IBM                     | 2         | 0.28%   |
| Gigabyte Technology     | 2         | 0.28%   |
| Unknown                 | 2         | 0.28%   |
| Wacom                   | 1         | 0.14%   |
| unknown                 | 1         | 0.14%   |
| Toshiba                 | 1         | 0.14%   |
| Tech Concepts           | 1         | 0.14%   |
| SHI                     | 1         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch           | 7         | 0.94%   |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                 | 7         | 0.94%   |
| LG Display LCD Monitor LGD03AB 1366x768 340x190mm 15.3-inch           | 5         | 0.67%   |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                 | 5         | 0.67%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch        | 4         | 0.54%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch  | 4         | 0.54%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch               | 4         | 0.54%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch               | 4         | 0.54%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch       | 4         | 0.54%   |
| Samsung Electronics SyncMaster SAM00A4 1024x768 300x230mm 14.9-inch   | 3         | 0.4%    |
| MSI G32C4 MSI3DA6 1920x1080 700x390mm 31.5-inch                       | 3         | 0.4%    |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch           | 3         | 0.4%    |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch              | 3         | 0.4%    |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch               | 3         | 0.4%    |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch               | 3         | 0.4%    |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch             | 3         | 0.4%    |
| Dell U2518D DEL413C 2560x1440 550x310mm 24.9-inch                     | 3         | 0.4%    |
| Dell U2412M DELA07B 1920x1200 520x320mm 24.0-inch                     | 3         | 0.4%    |
| Dell S2418HN/NX DEL4123 1920x1080 530x300mm 24.0-inch                 | 3         | 0.4%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch      | 3         | 0.4%    |
| BOE LCD Monitor BOE05DA 1366x768 280x160mm 12.7-inch                  | 3         | 0.4%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 310x170mm 13.9-inch        | 3         | 0.4%    |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch         | 3         | 0.4%    |
| ASUSTek Computer VG245 AUS24A1 1920x1080 530x300mm 24.0-inch          | 3         | 0.4%    |
| Ancor Communications VS248 ACI2498 1920x1080 530x300mm 24.0-inch      | 3         | 0.4%    |
| Acer V246HL ACR032E 1920x1080 530x300mm 24.0-inch                     | 3         | 0.4%    |
| Sony TV SNY9C01 1360x768                                              | 2         | 0.27%   |
| Sceptre Tech Sceptre C35 SPT0DB7 3440x1440 820x350mm 35.1-inch        | 2         | 0.27%   |
| Samsung Electronics U28E510 SAM0D68 3840x2160 610x350mm 27.7-inch     | 2         | 0.27%   |
| Samsung Electronics S27C750 SAM0A60 1920x1080 600x340mm 27.2-inch     | 2         | 0.27%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch  | 2         | 0.27%   |
| Samsung Electronics LCD Monitor SEC3157 1440x900 330x210mm 15.4-inch  | 2         | 0.27%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch  | 2         | 0.27%   |
| Samsung Electronics LCD Monitor SDC4C46 3840x2160 340x190mm 15.3-inch | 2         | 0.27%   |
| Samsung Electronics LCD Monitor SDC424A 3200x1800 290x170mm 13.2-inch | 2         | 0.27%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch          | 2         | 0.27%   |
| LG Display LCD Monitor LGD058B 2560x1440 310x170mm 13.9-inch          | 2         | 0.27%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch          | 2         | 0.27%   |
| LG Display LCD Monitor LGD0459 1920x1080 380x210mm 17.1-inch          | 2         | 0.27%   |
| LG Display LCD Monitor LGD0418 2560x1440 310x170mm 13.9-inch          | 2         | 0.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 240       | 33.85%  |
| 1366x768 (WXGA)    | 142       | 20.03%  |
| 3840x2160 (4K)     | 47        | 6.63%   |
| 2560x1440 (QHD)    | 46        | 6.49%   |
| 1600x900 (HD+)     | 37        | 5.22%   |
| 1920x1200 (WUXGA)  | 27        | 3.81%   |
| 1280x800 (WXGA)    | 24        | 3.39%   |
| 1280x1024 (SXGA)   | 20        | 2.82%   |
| 1680x1050 (WSXGA+) | 18        | 2.54%   |
| 1440x900 (WXGA+)   | 15        | 2.12%   |
| 2560x1080          | 14        | 1.97%   |
| 3440x1440          | 12        | 1.69%   |
| Unknown            | 9         | 1.27%   |
| 1360x768           | 8         | 1.13%   |
| 2256x1504          | 7         | 0.99%   |
| 1024x768 (XGA)     | 7         | 0.99%   |
| 2560x1600          | 6         | 0.85%   |
| 1024x600           | 5         | 0.71%   |
| 3200x1800 (QHD+)   | 4         | 0.56%   |
| 3840x1080          | 3         | 0.42%   |
| 1600x1200          | 3         | 0.42%   |
| 3840x1600          | 2         | 0.28%   |
| 7860x2400          | 1         | 0.14%   |
| 7040x1440          | 1         | 0.14%   |
| 5760x2160          | 1         | 0.14%   |
| 5760x1080          | 1         | 0.14%   |
| 4640x1080          | 1         | 0.14%   |
| 4480x1080          | 1         | 0.14%   |
| 3520x1080          | 1         | 0.14%   |
| 2806x900           | 1         | 0.14%   |
| 1920x540           | 1         | 0.14%   |
| 1920x1920          | 1         | 0.14%   |
| 1400x1050          | 1         | 0.14%   |
| 1280x854           | 1         | 0.14%   |
| 1280x768           | 1         | 0.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 140       | 19.53%  |
| 13      | 122       | 17.02%  |
| 24      | 64        | 8.93%   |
| 27      | 57        | 7.95%   |
| Unknown | 45        | 6.28%   |
| 31      | 30        | 4.18%   |
| 17      | 29        | 4.04%   |
| 12      | 29        | 4.04%   |
| 19      | 27        | 3.77%   |
| 11      | 27        | 3.77%   |
| 23      | 26        | 3.63%   |
| 21      | 24        | 3.35%   |
| 14      | 20        | 2.79%   |
| 34      | 16        | 2.23%   |
| 22      | 9         | 1.26%   |
| 29      | 7         | 0.98%   |
| 20      | 7         | 0.98%   |
| 18      | 6         | 0.84%   |
| 64      | 4         | 0.56%   |
| 26      | 4         | 0.56%   |
| 43      | 2         | 0.28%   |
| 42      | 2         | 0.28%   |
| 37      | 2         | 0.28%   |
| 35      | 2         | 0.28%   |
| 28      | 2         | 0.28%   |
| 16      | 2         | 0.28%   |
| 10      | 2         | 0.28%   |
| 9       | 2         | 0.28%   |
| 54      | 1         | 0.14%   |
| 52      | 1         | 0.14%   |
| 49      | 1         | 0.14%   |
| 41      | 1         | 0.14%   |
| 39      | 1         | 0.14%   |
| 32      | 1         | 0.14%   |
| 25      | 1         | 0.14%   |
| 8       | 1         | 0.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 232       | 33%     |
| 501-600     | 136       | 19.35%  |
| 201-300     | 119       | 16.93%  |
| 401-500     | 64        | 9.1%    |
| Unknown     | 45        | 6.4%    |
| 601-700     | 44        | 6.26%   |
| 351-400     | 26        | 3.7%    |
| 701-800     | 17        | 2.42%   |
| 1001-1500   | 7         | 1%      |
| 801-900     | 5         | 0.71%   |
| 901-1000    | 5         | 0.71%   |
| 101-200     | 3         | 0.43%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 477       | 70.98%  |
| 16/10   | 79        | 11.76%  |
| Unknown | 41        | 6.1%    |
| 21/9    | 26        | 3.87%   |
| 5/4     | 17        | 2.53%   |
| 3/2     | 15        | 2.23%   |
| 4/3     | 12        | 1.79%   |
| 6/5     | 3         | 0.45%   |
| 32/9    | 1         | 0.15%   |
| 1.00    | 1         | 0.15%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 117       | 16.39%  |
| 91-100         | 105       | 14.71%  |
| 201-250        | 99        | 13.87%  |
| 301-350        | 63        | 8.82%   |
| 351-500        | 52        | 7.28%   |
| Unknown        | 45        | 6.3%    |
| 101-110        | 36        | 5.04%   |
| 151-200        | 34        | 4.76%   |
| 61-70          | 30        | 4.2%    |
| 51-60          | 26        | 3.64%   |
| 251-300        | 25        | 3.5%    |
| 71-80          | 18        | 2.52%   |
| 121-130        | 18        | 2.52%   |
| 141-150        | 17        | 2.38%   |
| 501-1000       | 9         | 1.26%   |
| More than 1000 | 6         | 0.84%   |
| 111-120        | 6         | 0.84%   |
| 1-40           | 3         | 0.42%   |
| 131-140        | 3         | 0.42%   |
| 41-50          | 2         | 0.28%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 220       | 31.61%  |
| 121-160       | 189       | 27.16%  |
| 101-120       | 174       | 25%     |
| 161-240       | 48        | 6.9%    |
| Unknown       | 45        | 6.47%   |
| More than 240 | 16        | 2.3%    |
| 1-50          | 4         | 0.57%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2479      | 76.99%  |
| 1     | 660       | 20.5%   |
| 2     | 72        | 2.24%   |
| 3     | 7         | 0.22%   |
| 4     | 2         | 0.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2594      | 58.33%  |
| Realtek Semiconductor           | 927       | 20.85%  |
| Broadcom                        | 319       | 7.17%   |
| Qualcomm Atheros                | 195       | 4.38%   |
| Mellanox Technologies           | 56        | 1.26%   |
| Ralink Technology               | 36        | 0.81%   |
| Chelsio Communications          | 29        | 0.65%   |
| IMC Networks                    | 25        | 0.56%   |
| AMD                             | 20        | 0.45%   |
| U-Blox                          | 18        | 0.4%    |
| Marvell Technology Group        | 17        | 0.38%   |
| TP-Link                         | 15        | 0.34%   |
| Ralink                          | 15        | 0.34%   |
| Edimax Technology               | 14        | 0.31%   |
| Solarflare Communications       | 12        | 0.27%   |
| Aquantia                        | 12        | 0.27%   |
| MediaTek                        | 11        | 0.25%   |
| Google                          | 9         | 0.2%    |
| D-Link System                   | 8         | 0.18%   |
| Nvidia                          | 7         | 0.16%   |
| Novatel Wireless                | 7         | 0.16%   |
| NetGear                         | 7         | 0.16%   |
| Seeed Technology                | 6         | 0.13%   |
| Emulex                          | 6         | 0.13%   |
| Dell                            | 6         | 0.13%   |
| Apple                           | 6         | 0.13%   |
| QLogic                          | 5         | 0.11%   |
| ASUSTek Computer                | 5         | 0.11%   |
| American Megatrends             | 5         | 0.11%   |
| Sierra Wireless                 | 3         | 0.07%   |
| Sequans Communications          | 3         | 0.07%   |
| Cisco Systems                   | 3         | 0.07%   |
| VIA Technologies                | 2         | 0.04%   |
| Qualcomm Atheros Communications | 2         | 0.04%   |
| Qualcomm                        | 2         | 0.04%   |
| OnePlus Technology (Shenzhen)   | 2         | 0.04%   |
| Linksys                         | 2         | 0.04%   |
| Insyde Software                 | 2         | 0.04%   |
| ICS Advent                      | 2         | 0.04%   |
| D-Link                          | 2         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 728       | 12.69%  |
| Intel I211 Gigabit Network Connection                                         | 352       | 6.13%   |
| Intel I210 Gigabit Network Connection                                         | 260       | 4.53%   |
| Intel I350 Gigabit Network Connection                                         | 232       | 4.04%   |
| Intel Ethernet Controller I225-V                                              | 196       | 3.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 186       | 3.24%   |
| Intel 82574L Gigabit Network Connection                                       | 150       | 2.61%   |
| Intel Ethernet Connection I217-LM                                             | 130       | 2.27%   |
| Intel Ethernet Controller I226-V                                              | 126       | 2.2%    |
| Intel 82580 Gigabit Network Connection                                        | 96        | 1.67%   |
| Intel 82583V Gigabit Network Connection                                       | 93        | 1.62%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 89        | 1.55%   |
| Realtek RTL8125 2.5GbE Controller                                             | 88        | 1.53%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 87        | 1.52%   |
| Intel 82576 Gigabit Network Connection                                        | 87        | 1.52%   |
| Intel Wi-Fi 6 AX200                                                           | 81        | 1.41%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 80        | 1.39%   |
| Intel Ethernet Connection (2) I219-LM                                         | 73        | 1.27%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 60        | 1.05%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 59        | 1.03%   |
| Intel Wireless 8265 / 8275                                                    | 56        | 0.98%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 53        | 0.92%   |
| Intel Wireless 7260                                                           | 46        | 0.8%    |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 46        | 0.8%    |
| Intel Wireless 8260                                                           | 44        | 0.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 44        | 0.77%   |
| Intel Wireless 7265                                                           | 42        | 0.73%   |
| Intel Ethernet Connection (2) I219-V                                          | 39        | 0.68%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 39        | 0.68%   |
| Intel Ethernet Connection I354                                                | 38        | 0.66%   |
| Intel Ethernet Connection (7) I219-LM                                         | 38        | 0.66%   |
| Intel Ethernet Controller X550                                                | 35        | 0.61%   |
| Intel Wireless 3165                                                           | 34        | 0.59%   |
| Intel Ethernet Connection (7) I219-V                                          | 34        | 0.59%   |
| Mellanox MT27500 Family [ConnectX-3]                                          | 32        | 0.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 31        | 0.54%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 27        | 0.47%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 25        | 0.44%   |
| Intel 82575EB Gigabit Network Connection                                      | 25        | 0.44%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                          | 25        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 631       | 54.63%  |
| Qualcomm Atheros                | 164       | 14.2%   |
| Realtek Semiconductor           | 133       | 11.52%  |
| Broadcom                        | 84        | 7.27%   |
| Ralink Technology               | 36        | 3.12%   |
| IMC Networks                    | 25        | 2.16%   |
| TP-Link                         | 15        | 1.3%    |
| Ralink                          | 15        | 1.3%    |
| Edimax Technology               | 14        | 1.21%   |
| MediaTek                        | 11        | 0.95%   |
| NetGear                         | 7         | 0.61%   |
| ASUSTek Computer                | 5         | 0.43%   |
| Sierra Wireless                 | 2         | 0.17%   |
| Qualcomm Atheros Communications | 2         | 0.17%   |
| D-Link System                   | 2         | 0.17%   |
| D-Link                          | 2         | 0.17%   |
| Belkin Components               | 2         | 0.17%   |
| ZyXEL Communications            | 1         | 0.09%   |
| Marvell Technology Group        | 1         | 0.09%   |
| Linksys                         | 1         | 0.09%   |
| Dell                            | 1         | 0.09%   |
| AboCom Systems                  | 1         | 0.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 81        | 6.93%   |
| Intel Wireless 8265 / 8275                                     | 56        | 4.79%   |
| Intel Wireless 7260                                            | 46        | 3.94%   |
| Intel Wireless 8260                                            | 44        | 3.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 44        | 3.77%   |
| Intel Wireless 7265                                            | 42        | 3.6%    |
| Intel Wireless 3165                                            | 34        | 2.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 31        | 2.65%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 27        | 2.31%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 25        | 2.14%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card           | 25        | 2.14%   |
| Intel Wireless-AC 9260                                         | 24        | 2.05%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 23        | 1.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 21        | 1.8%    |
| Intel Gemini Lake PCH CNVi WiFi                                | 21        | 1.8%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 19        | 1.63%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 19        | 1.63%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 18        | 1.54%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 17        | 1.46%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 17        | 1.46%   |
| Ralink RT5370 Wireless Adapter                                 | 16        | 1.37%   |
| Intel Wireless 3160                                            | 16        | 1.37%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 15        | 1.28%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 15        | 1.28%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 15        | 1.28%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 14        | 1.2%    |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 14        | 1.2%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 13        | 1.11%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 13        | 1.11%   |
| Intel Wi-Fi 6 AX201                                            | 13        | 1.11%   |
| Intel CNVi: Wi-Fi                                              | 11        | 0.94%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 11        | 0.94%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 11        | 0.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 10        | 0.86%   |
| Intel Centrino Wireless-N 2230                                 | 10        | 0.86%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 10        | 0.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 9         | 0.77%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 8         | 0.68%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 8         | 0.68%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 8         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2332      | 63.72%  |
| Realtek Semiconductor            | 864       | 23.61%  |
| Broadcom                         | 268       | 7.32%   |
| Qualcomm Atheros                 | 39        | 1.07%   |
| Chelsio Communications           | 26        | 0.71%   |
| AMD                              | 19        | 0.52%   |
| Marvell Technology Group         | 15        | 0.41%   |
| Solarflare Communications        | 12        | 0.33%   |
| Aquantia                         | 11        | 0.3%    |
| Nvidia                           | 7         | 0.19%   |
| Novatel Wireless                 | 7         | 0.19%   |
| Emulex                           | 6         | 0.16%   |
| D-Link System                    | 6         | 0.16%   |
| QLogic                           | 5         | 0.14%   |
| American Megatrends              | 5         | 0.14%   |
| Google                           | 4         | 0.11%   |
| Apple                            | 4         | 0.11%   |
| Cisco Systems                    | 3         | 0.08%   |
| VIA Technologies                 | 2         | 0.05%   |
| Qualcomm                         | 2         | 0.05%   |
| OnePlus Technology (Shenzhen)    | 2         | 0.05%   |
| Insyde Software                  | 2         | 0.05%   |
| ICS Advent                       | 2         | 0.05%   |
| 3Com                             | 2         | 0.05%   |
| Xiaomi                           | 1         | 0.03%   |
| TRENDnet                         | 1         | 0.03%   |
| Tehuti Networks                  | 1         | 0.03%   |
| Silicon Integrated Systems [SiS] | 1         | 0.03%   |
| Silicom                          | 1         | 0.03%   |
| Samsung Electronics              | 1         | 0.03%   |
| Oracle/SUN                       | 1         | 0.03%   |
| OPPO Electronics                 | 1         | 0.03%   |
| National Semiconductor           | 1         | 0.03%   |
| MYRICOM                          | 1         | 0.03%   |
| Linksys                          | 1         | 0.03%   |
| Lenovo                           | 1         | 0.03%   |
| Amazon.com                       | 1         | 0.03%   |
| ADMtek                           | 1         | 0.03%   |
| Accton Technology                | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 728       | 16.42%  |
| Intel I211 Gigabit Network Connection                                         | 352       | 7.94%   |
| Intel I210 Gigabit Network Connection                                         | 260       | 5.86%   |
| Intel I350 Gigabit Network Connection                                         | 232       | 5.23%   |
| Intel Ethernet Controller I225-V                                              | 196       | 4.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 186       | 4.19%   |
| Intel 82574L Gigabit Network Connection                                       | 150       | 3.38%   |
| Intel Ethernet Connection I217-LM                                             | 130       | 2.93%   |
| Intel Ethernet Controller I226-V                                              | 126       | 2.84%   |
| Intel 82580 Gigabit Network Connection                                        | 96        | 2.17%   |
| Intel 82583V Gigabit Network Connection                                       | 93        | 2.1%    |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 89        | 2.01%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 87        | 1.96%   |
| Intel 82576 Gigabit Network Connection                                        | 87        | 1.96%   |
| Realtek RTL8125 2.5GbE Controller                                             | 85        | 1.92%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 80        | 1.8%    |
| Intel Ethernet Connection (2) I219-LM                                         | 73        | 1.65%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 60        | 1.35%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 59        | 1.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 53        | 1.2%    |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 46        | 1.04%   |
| Intel Ethernet Connection (2) I219-V                                          | 39        | 0.88%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 39        | 0.88%   |
| Intel Ethernet Connection I354                                                | 38        | 0.86%   |
| Intel Ethernet Connection (7) I219-LM                                         | 38        | 0.86%   |
| Intel Ethernet Controller X550                                                | 35        | 0.79%   |
| Intel Ethernet Connection (7) I219-V                                          | 34        | 0.77%   |
| Intel 82575EB Gigabit Network Connection                                      | 25        | 0.56%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 23        | 0.52%   |
| Intel Ethernet Connection X553 1GbE                                           | 23        | 0.52%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 22        | 0.5%    |
| Intel Ethernet Connection (5) I219-LM                                         | 21        | 0.47%   |
| Intel 82579V Gigabit Network Connection                                       | 21        | 0.47%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 21        | 0.47%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 20        | 0.45%   |
| AMD XGMAC 10GbE Controller                                                    | 19        | 0.43%   |
| Intel Ethernet Controller I225-LM                                             | 18        | 0.41%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                              | 17        | 0.38%   |
| Intel Ethernet Connection (4) I219-LM                                         | 17        | 0.38%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 17        | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3061      | 71.65%  |
| WiFi     | 1078      | 25.23%  |
| Unknown  | 96        | 2.25%   |
| Modem    | 37        | 0.87%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2859      | 86.35%  |
| WiFi     | 443       | 13.38%  |
| Unknown  | 9         | 0.27%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 914       | 27.95%  |
| 4     | 672       | 20.55%  |
| 3     | 449       | 13.73%  |
| 1     | 392       | 11.99%  |
| 6     | 351       | 10.73%  |
| 5     | 242       | 7.4%    |
| 8     | 74        | 2.26%   |
| 7     | 64        | 1.96%   |
| 0     | 31        | 0.95%   |
| 10    | 29        | 0.89%   |
| 9     | 26        | 0.8%    |
| 11    | 7         | 0.21%   |
| 13    | 4         | 0.12%   |
| 12    | 4         | 0.12%   |
| 16    | 3         | 0.09%   |
| 15    | 3         | 0.09%   |
| 14    | 3         | 0.09%   |
| 20    | 1         | 0.03%   |
| 17    | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2640      | 79.3%   |
| Yes  | 689       | 20.7%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 478       | 62.24%  |
| Broadcom                        | 55        | 7.16%   |
| Apple                           | 51        | 6.64%   |
| Realtek Semiconductor           | 50        | 6.51%   |
| Qualcomm Atheros Communications | 31        | 4.04%   |
| IMC Networks                    | 29        | 3.78%   |
| Cambridge Silicon Radio         | 14        | 1.82%   |
| ASUSTek Computer                | 12        | 1.56%   |
| Lite-On Technology              | 10        | 1.3%    |
| Foxconn / Hon Hai               | 9         | 1.17%   |
| Dell                            | 9         | 1.17%   |
| MediaTek                        | 7         | 0.91%   |
| Alps Electric                   | 4         | 0.52%   |
| Ralink                          | 2         | 0.26%   |
| TP-Link                         | 1         | 0.13%   |
| Taiyo Yuden                     | 1         | 0.13%   |
| Primax Electronics              | 1         | 0.13%   |
| Hewlett-Packard                 | 1         | 0.13%   |
| Esel International              | 1         | 0.13%   |
| Dynex                           | 1         | 0.13%   |
| Corsair                         | 1         | 0.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 197       | 25.52%  |
| Intel AX200 Bluetooth                                       | 74        | 9.59%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 65        | 8.42%   |
| Intel AX201 Bluetooth                                       | 53        | 6.87%   |
| Intel Wireless-AC 3168 Bluetooth                            | 26        | 3.37%   |
| Intel AX210 Bluetooth                                       | 23        | 2.98%   |
| Apple Bluetooth Host Controller                             | 22        | 2.85%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 21        | 2.72%   |
| Realtek  Bluetooth 4.2 Adapter                              | 18        | 2.33%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 17        | 2.2%    |
| Realtek Bluetooth Adapter                                   | 16        | 2.07%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 14        | 1.81%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 14        | 1.81%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 12        | 1.55%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 12        | 1.55%   |
| Apple Broadcom Built-in Bluetooth                           | 12        | 1.55%   |
| IMC Networks Realtek Bluetooth Adapter                      | 11        | 1.42%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 9         | 1.17%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 8         | 1.04%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 7         | 0.91%   |
| Realtek Bluetooth 4.2 Adapter                               | 6         | 0.78%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 6         | 0.78%   |
| MediaTek RZ608 Bluetooth Adapter                            | 6         | 0.78%   |
| Lite-On Bluetooth USB Module                                | 6         | 0.78%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 6         | 0.78%   |
| Apple Built-in iSight (no firmware loaded)                  | 6         | 0.78%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 5         | 0.65%   |
| Intel AX211 Bluetooth                                       | 5         | 0.65%   |
| Dell DW375 Bluetooth Module                                 | 5         | 0.65%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 4         | 0.52%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 4         | 0.52%   |
| Realtek RTL8821A Bluetooth                                  | 3         | 0.39%   |
| Realtek Bluetooth 4.0 Adapter                               | 3         | 0.39%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 3         | 0.39%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 3         | 0.39%   |
| ASUS USB-BT500                                              | 3         | 0.39%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 2         | 0.26%   |
| Ralink RT3290 Bluetooth                                     | 2         | 0.26%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.1                      | 2         | 0.26%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 2         | 0.26%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1897      | 67.58%  |
| AMD                                          | 531       | 18.92%  |
| Nvidia                                       | 245       | 8.73%   |
| C-Media Electronics                          | 38        | 1.35%   |
| Creative Labs                                | 13        | 0.46%   |
| Logitech                                     | 7         | 0.25%   |
| Texas Instruments                            | 6         | 0.21%   |
| SteelSeries ApS                              | 6         | 0.21%   |
| Realtek Semiconductor                        | 5         | 0.18%   |
| Blue Microphones                             | 5         | 0.18%   |
| MosArt Semiconductor                         | 3         | 0.11%   |
| Generalplus Technology                       | 3         | 0.11%   |
| Creative Technology                          | 3         | 0.11%   |
| Corsair                                      | 3         | 0.11%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.07%   |
| Yamaha                                       | 2         | 0.07%   |
| Silicon Integrated Systems [SiS]             | 2         | 0.07%   |
| Razer USA                                    | 2         | 0.07%   |
| Lenovo                                       | 2         | 0.07%   |
| Google                                       | 2         | 0.07%   |
| CMX Systems                                  | 2         | 0.07%   |
| Cambridge Silicon Radio                      | 2         | 0.07%   |
| ASUSTek Computer                             | 2         | 0.07%   |
| Apple                                        | 2         | 0.07%   |
| XMOS                                         | 1         | 0.04%   |
| VIA Technologies                             | 1         | 0.04%   |
| Universal Audio                              | 1         | 0.04%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.04%   |
| Tenx Technology                              | 1         | 0.04%   |
| Quanta                                       | 1         | 0.04%   |
| Nektar                                       | 1         | 0.04%   |
| LG Electronics                               | 1         | 0.04%   |
| KTMicro                                      | 1         | 0.04%   |
| KORG                                         | 1         | 0.04%   |
| Kingston Technology                          | 1         | 0.04%   |
| JMTek                                        | 1         | 0.04%   |
| Hewlett-Packard                              | 1         | 0.04%   |
| Harman                                       | 1         | 0.04%   |
| Genesys Logic                                | 1         | 0.04%   |
| Focusrite-Novation                           | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 183       | 5.38%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 166       | 4.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 145       | 4.26%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 141       | 4.14%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 138       | 4.06%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 128       | 3.76%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 124       | 3.64%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 111       | 3.26%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 107       | 3.15%   |
| AMD FCH Azalia Controller                                                                         | 104       | 3.06%   |
| Intel Cannon Lake PCH cAVS                                                                        | 103       | 3.03%   |
| Intel Jasper Lake HD Audio                                                                        | 101       | 2.97%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 72        | 2.12%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 68        | 2%      |
| Intel 200 Series PCH HD Audio                                                                     | 67        | 1.97%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 63        | 1.85%   |
| Intel Broadwell-U Audio Controller                                                                | 63        | 1.85%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 59        | 1.73%   |
| AMD Kabini HDMI/DP Audio                                                                          | 57        | 1.68%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 56        | 1.65%   |
| Intel 8 Series HD Audio Controller                                                                | 55        | 1.62%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 54        | 1.59%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 52        | 1.53%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 49        | 1.44%   |
| Intel Alder Lake-N HD Graphics SGPC                                                               | 44        | 1.29%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 43        | 1.26%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 38        | 1.12%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 35        | 1.03%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 34        | 1%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 34        | 1%      |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 30        | 0.88%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 27        | 0.79%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 24        | 0.71%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 23        | 0.68%   |
| Intel Elkhart Lake High Density Audio bus interface                                               | 22        | 0.65%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 21        | 0.62%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 21        | 0.62%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 21        | 0.62%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 20        | 0.59%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 20        | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 638       | 18.45%  |
| SK hynix                                | 549       | 15.88%  |
| Crucial                                 | 374       | 10.82%  |
| Micron Technology                       | 369       | 10.67%  |
| Kingston                                | 285       | 8.24%   |
| Unknown                                 | 270       | 7.81%   |
| G.Skill                                 | 164       | 4.74%   |
| Corsair                                 | 131       | 3.79%   |
| Unknown                                 | 96        | 2.78%   |
| Team                                    | 70        | 2.02%   |
| Unknown (ABCD)                          | 45        | 1.3%    |
| Transcend                               | 45        | 1.3%    |
| A-DATA Technology                       | 42        | 1.21%   |
| Ramaxel Technology                      | 41        | 1.19%   |
| Nanya Technology                        | 36        | 1.04%   |
| Patriot                                 | 34        | 0.98%   |
| PNY                                     | 27        | 0.78%   |
| Kimtigo                                 | 24        | 0.69%   |
| Elpida                                  | 24        | 0.69%   |
| Timetec                                 | 17        | 0.49%   |
| Toshiba                                 | 13        | 0.38%   |
| Silicon Power                           | 12        | 0.35%   |
| Avant                                   | 12        | 0.35%   |
| Super Talent                            | 11        | 0.32%   |
| SK_Hynix                                | 7         | 0.2%    |
| Innodisk                                | 7         | 0.2%    |
| Silicon Power Computer & Communications | 6         | 0.17%   |
| Sesame                                  | 6         | 0.17%   |
| GeIL                                    | 5         | 0.14%   |
| Apacer                                  | 5         | 0.14%   |
| Patriot Memory (PDP Systems)            | 4         | 0.12%   |
| HPE                                     | 4         | 0.12%   |
| Wodposit                                | 3         | 0.09%   |
| tigo                                    | 3         | 0.09%   |
| Ramsta                                  | 3         | 0.09%   |
| Neo Forza                               | 3         | 0.09%   |
| Mushkin                                 | 3         | 0.09%   |
| Hewlett-Packard                         | 3         | 0.09%   |
| Goldkey                                 | 3         | 0.09%   |
| Vasekey                                 | 2         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Unknown                                                           | 96        | 2.6%    |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR3 2400MT/s | 41        | 1.11%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s             | 24        | 0.65%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 23        | 0.62%   |
| Unknown RAM Module 8GB 1600MT/s                                   | 21        | 0.57%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s               | 20        | 0.54%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s               | 20        | 0.54%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s            | 19        | 0.51%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                       | 18        | 0.49%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s             | 17        | 0.46%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s             | 17        | 0.46%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s              | 16        | 0.43%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s             | 16        | 0.43%   |
| Samsung RAM M471B1G73QH0-YK0 8GB DIMM DDR3 1600MT/s               | 16        | 0.43%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                         | 15        | 0.41%   |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s               | 14        | 0.38%   |
| Samsung RAM M393A2G40DB0-CPB 16GB DIMM 2133MT/s                   | 14        | 0.38%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                         | 13        | 0.35%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s              | 13        | 0.35%   |
| Micron RAM 8KTF51264HZ-1G9P1 4GB SODIMM DDR3 1867MT/s             | 13        | 0.35%   |
| Crucial RAM CT102464BF160B.C16 8GB DIMM DDR3 1600MT/s             | 13        | 0.35%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s              | 12        | 0.32%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s             | 12        | 0.32%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s             | 12        | 0.32%   |
| Crucial RAM CT102464BF160B.M16 8GB DIMM DDR3 1600MT/s             | 12        | 0.32%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                        | 11        | 0.3%    |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s              | 11        | 0.3%    |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s            | 11        | 0.3%    |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s                    | 11        | 0.3%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 10        | 0.27%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s              | 10        | 0.27%   |
| Samsung RAM M471B5173QH0-YK0 4GB DIMM DDR3 1600MT/s               | 10        | 0.27%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s             | 10        | 0.27%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s            | 10        | 0.27%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s               | 10        | 0.27%   |
| Micron RAM 18KSF1G72AZ-1G6E1 8GB DIMM DDR3 1600MT/s               | 10        | 0.27%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3200MT/s              | 10        | 0.27%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s           | 10        | 0.27%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                         | 9         | 0.24%   |
| Super Talent RAM SUPERTALENT02 4GB DIMM DDR3 1600MT/s             | 9         | 0.24%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind         | Computers | Percent |
|--------------|-----------|---------|
| DDR3         | 1389      | 45.95%  |
| DDR4         | 1267      | 41.91%  |
| DDR2         | 108       | 3.57%   |
| LPDDR4       | 72        | 2.38%   |
| Unknown      | 64        | 2.12%   |
| DDR5         | 52        | 1.72%   |
| SDRAM        | 24        | 0.79%   |
| LPDDR3       | 17        | 0.56%   |
| DDR          | 15        | 0.5%    |
| LPDDR5       | 10        | 0.33%   |
| DRAM         | 3         | 0.1%    |
| SRAM         | 1         | 0.03%   |
| DDR2 FB-DIMM | 1         | 0.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 1641      | 54.5%   |
| SODIMM       | 1246      | 41.38%  |
| Row Of Chips | 49        | 1.63%   |
| Unknown      | 46        | 1.53%   |
| Chip         | 13        | 0.43%   |
| FB-DIMM      | 10        | 0.33%   |
| RIMM         | 6         | 0.2%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 1302      | 40.04%  |
| 4096   | 946       | 29.09%  |
| 16384  | 488       | 15.01%  |
| 2048   | 306       | 9.41%   |
| 32768  | 134       | 4.12%   |
| 1024   | 63        | 1.94%   |
| 512    | 7         | 0.22%   |
| 65536  | 3         | 0.09%   |
| 131072 | 1         | 0.03%   |
| 3072   | 1         | 0.03%   |
| 256    | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 965       | 29.8%   |
| 2400    | 390       | 12.04%  |
| 1333    | 380       | 11.74%  |
| 2667    | 323       | 9.98%   |
| 3200    | 309       | 9.54%   |
| 2133    | 265       | 8.18%   |
| 800     | 71        | 2.19%   |
| 2666    | 65        | 2.01%   |
| 667     | 65        | 2.01%   |
| 1867    | 47        | 1.45%   |
| 1334    | 44        | 1.36%   |
| 4800    | 41        | 1.27%   |
| 1066    | 39        | 1.2%    |
| 1067    | 37        | 1.14%   |
| 3600    | 33        | 1.02%   |
| Unknown | 31        | 0.96%   |
| 3000    | 29        | 0.9%    |
| 2933    | 16        | 0.49%   |
| 1866    | 13        | 0.4%    |
| 533     | 11        | 0.34%   |
| 6400    | 10        | 0.31%   |
| 5600    | 10        | 0.31%   |
| 4267    | 10        | 0.31%   |
| 400     | 5         | 0.15%   |
| 975     | 4         | 0.12%   |
| 4266    | 3         | 0.09%   |
| 4000    | 3         | 0.09%   |
| 3733    | 3         | 0.09%   |
| 1200    | 3         | 0.09%   |
| 1400    | 2         | 0.06%   |
| 4133    | 1         | 0.03%   |
| 3534    | 1         | 0.03%   |
| 3333    | 1         | 0.03%   |
| 2866    | 1         | 0.03%   |
| 2048    | 1         | 0.03%   |
| 1639    | 1         | 0.03%   |
| 1596    | 1         | 0.03%   |
| 1033    | 1         | 0.03%   |
| 266     | 1         | 0.03%   |
| 200     | 1         | 0.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 2         | 28.57%  |
| Brother Industries    | 2         | 28.57%  |
| Prolific Technology   | 1         | 14.29%  |
| Lexmark International | 1         | 14.29%  |
| Apple                 | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port                                            | 1         | 12.5%   |
| Lexmark International Lexmark MS710 Print                                | 1         | 12.5%   |
| HP PNP Fax Null                                                          | 1         | 12.5%   |
| HP LaserJet 1012                                                         | 1         | 12.5%   |
| HP HP LaserJet M101-M106 Printer HP LEDM HP LEDM IPP Printer IPP Printer | 1         | 12.5%   |
| Brother MFC-L2685DW                                                      | 1         | 12.5%   |
| Brother MFC-J485DW                                                       | 1         | 12.5%   |
| Apple Gamesir-G3s 2.10                                                   | 1         | 12.5%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 2         | 66.67%  |
| Hewlett-Packard | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Seiko Epson WF-2850 Series EPSON Scanner USB2.0 Printer EPSON Utility USB2.0 Faxout | 2         | 66.67%  |
| HP ScanJet 5300c/5370c                                                              | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 105       | 24.88%  |
| Bison Electronics                      | 50        | 11.85%  |
| Microdia                               | 34        | 8.06%   |
| Realtek Semiconductor                  | 33        | 7.82%   |
| Sunplus Innovation Technology          | 30        | 7.11%   |
| IMC Networks                           | 28        | 6.64%   |
| Logitech                               | 27        | 6.4%    |
| Apple                                  | 15        | 3.55%   |
| Quanta                                 | 13        | 3.08%   |
| Cheng Uei Precision Industry (Foxlink) | 12        | 2.84%   |
| Suyin                                  | 11        | 2.61%   |
| Lite-On Technology                     | 10        | 2.37%   |
| Luxvisions Innotech Limited            | 8         | 1.9%    |
| Syntek                                 | 6         | 1.42%   |
| Lenovo                                 | 6         | 1.42%   |
| Importek                               | 4         | 0.95%   |
| Primax Electronics                     | 3         | 0.71%   |
| Intel                                  | 3         | 0.71%   |
| Alcor Micro                            | 3         | 0.71%   |
| WCM_USB                                | 2         | 0.47%   |
| Shenzhen Kingcome Optoelectronic       | 2         | 0.47%   |
| SHENZHEN EMEET TECHNOLOGY              | 2         | 0.47%   |
| Ricoh                                  | 2         | 0.47%   |
| OmniVision Technologies                | 2         | 0.47%   |
| Generalplus Technology                 | 2         | 0.47%   |
| Z-Star Microelectronics                | 1         | 0.24%   |
| Xiongmai                               | 1         | 0.24%   |
| Unknown                                | 1         | 0.24%   |
| Supreme Electronics                    | 1         | 0.24%   |
| Silicon Motion                         | 1         | 0.24%   |
| Goodong Industry                       | 1         | 0.24%   |
| Arkmicro Technologies                  | 1         | 0.24%   |
| ARC International                      | 1         | 0.24%   |
| ALi                                    | 1         | 0.24%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 33        | 7.73%   |
| Bison Integrated Camera                             | 26        | 6.09%   |
| Sunplus Integrated_Webcam_HD                        | 13        | 3.04%   |
| Chicony Lenovo Integrated Camera (0.3MP)            | 11        | 2.58%   |
| Realtek Integrated_Webcam_HD                        | 10        | 2.34%   |
| IMC Networks Integrated Camera                      | 10        | 2.34%   |
| Apple FaceTime HD Camera                            | 10        | 2.34%   |
| Microdia Integrated Webcam                          | 9         | 2.11%   |
| Chicony Integrated Camera (1280x720@30)             | 9         | 2.11%   |
| Realtek USB 2.0 PC Camera                           | 8         | 1.87%   |
| Logitech HD Pro Webcam C920                         | 7         | 1.64%   |
| Lite-On Integrated Camera                           | 7         | 1.64%   |
| Chicony Integrated Camera [ThinkPad]                | 7         | 1.64%   |
| Microdia Integrated_Webcam_HD                       | 6         | 1.41%   |
| Logitech Webcam C270                                | 6         | 1.41%   |
| Bison ThinkPad Integrated Camera                    | 6         | 1.41%   |
| Logitech BRIO Ultra HD Webcam                       | 5         | 1.17%   |
| Bison SunplusIT Integrated Camera                   | 5         | 1.17%   |
| Suyin Integrated_Webcam_HD                          | 4         | 0.94%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 4         | 0.94%   |
| Microdia Webcam Vitade AF                           | 4         | 0.94%   |
| Microdia Dell Laptop Integrated Webcam HD           | 4         | 0.94%   |
| Luxvisions Innotech Limited Integrated Camera       | 4         | 0.94%   |
| Lenovo Integrated Webcam [R5U877]                   | 4         | 0.94%   |
| IMC Networks Realtek PC Camera                      | 4         | 0.94%   |
| Chicony Integrated IR Camera                        | 4         | 0.94%   |
| Chicony HP TrueVision HD Camera                     | 4         | 0.94%   |
| Chicony HD WebCam                                   | 4         | 0.94%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 4         | 0.94%   |
| Bison Lenovo Integrated Webcam                      | 4         | 0.94%   |
| Apple FaceTime HD Camera (Built-in)                 | 4         | 0.94%   |
| Syntek EasyCamera                                   | 3         | 0.7%    |
| Sunplus HD WebCam                                   | 3         | 0.7%    |
| Realtek Laptop Camera                               | 3         | 0.7%    |
| Realtek Integrated Webcam HD                        | 3         | 0.7%    |
| Quanta HP Webcam                                    | 3         | 0.7%    |
| Quanta HP TrueVision HD Camera                      | 3         | 0.7%    |
| Logitech C922 Pro Stream Webcam                     | 3         | 0.7%    |
| IMC Networks UVC VGA Webcam                         | 3         | 0.7%    |
| IMC Networks EasyCamera                             | 3         | 0.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 35        | 33.02%  |
| Synaptics                  | 24        | 22.64%  |
| Upek                       | 14        | 13.21%  |
| STMicroelectronics         | 12        | 11.32%  |
| Shenzhen Goodix Technology | 7         | 6.6%    |
| AuthenTec                  | 7         | 6.6%    |
| Elan Microelectronics      | 2         | 1.89%   |
| Broadcom                   | 2         | 1.89%   |
| Samsung Electronics        | 1         | 0.94%   |
| LighTuning Technology      | 1         | 0.94%   |
| FocalTech Systems          | 1         | 0.94%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 16        | 15.09%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 14        | 13.21%  |
| STMicroelectronics Fingerprint Reader                                        | 12        | 11.32%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 11        | 10.38%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 10        | 9.43%   |
| Shenzhen Goodix Fingerprint Reader                                           | 6         | 5.66%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 5         | 4.72%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 4         | 3.77%   |
| Validity Sensors Synaptics WBDI                                              | 4         | 3.77%   |
| AuthenTec AES2810                                                            | 3         | 2.83%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 2         | 1.89%   |
| Elan Fingerprint Sensor                                                      | 2         | 1.89%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 1.89%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 2         | 1.89%   |
| AuthenTec AES1660                                                            | 2         | 1.89%   |
| Validity Sensors VFS491                                                      | 1         | 0.94%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 1         | 0.94%   |
| Validity Sensors VFS301 Fingerprint Reader                                   | 1         | 0.94%   |
| Validity Sensors Fingerprint scanner                                         | 1         | 0.94%   |
| Synaptics WBDI Fingerprint Reader USB 102                                    | 1         | 0.94%   |
| Synaptics WBDI                                                               | 1         | 0.94%   |
| Synaptics UWP WBDI                                                           | 1         | 0.94%   |
| Shenzhen Goodix Fingerprint Reader SGX                                       | 1         | 0.94%   |
| Samsung CanvasBio Fingerprint Reader                                         | 1         | 0.94%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 1         | 0.94%   |
| FocalTech Systems Fingerprint Reader                                         | 1         | 0.94%   |

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
| 1     | 1336      | 40.56%  |
| 0     | 975       | 29.6%   |
| 2     | 653       | 19.82%  |
| 3     | 241       | 7.32%   |
| 4     | 67        | 2.03%   |
| 5     | 15        | 0.46%   |
| 6     | 5         | 0.15%   |
| 7     | 2         | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 1963      | 62.9%   |
| Bluetooth                | 333       | 10.67%  |
| Net/wireless             | 283       | 9.07%   |
| Card reader              | 139       | 4.45%   |
| Firewire controller      | 104       | 3.33%   |
| Fingerprint reader       | 91        | 2.92%   |
| Net/ethernet             | 57        | 1.83%   |
| Sound                    | 52        | 1.67%   |
| Network                  | 43        | 1.38%   |
| Graphics card            | 22        | 0.7%    |
| Storage                  | 11        | 0.35%   |
| Modem                    | 8         | 0.26%   |
| Storage/raid             | 7         | 0.22%   |
| Storage/ata              | 3         | 0.1%    |
| Dvb card                 | 3         | 0.1%    |
| Storage/ide              | 2         | 0.06%   |

