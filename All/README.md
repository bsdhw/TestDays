BSD - Tested Hardware & Statistics
----------------------------------

A project to collect tested hardware configurations for BSD.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Desktop/README.md) and [notebooks](/Notebook/README.md).

OS-specific reports: [FreeBSD](/Dist/FreeBSD), [GhostBSD](/Dist/GhostBSD), [helloSystem](/Dist/helloSystem), [NetBSD](/Dist/NetBSD), [NomadBSD](/Dist/NomadBSD), [OpenBSD](/Dist/OpenBSD), [OPNsense](/Dist/OPNsense), [pfSense](/Dist/pfSense), [TrueNAS](/Dist/TrueNAS).

This report is for real hardware. Report for virtual hardware: [TestCoverage_VE](https://github.com/bsdhw/TestCoverage_VE)

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

Total: 13351

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Dell          | 04415J A00                  | Mini pc     | [3737d80840](https://bsd-hardware.info/?probe=3737d80840) | Dec 31, 2022 |
| HP            | 1825                        | Desktop     | [f7e94decd0](https://bsd-hardware.info/?probe=f7e94decd0) | Dec 31, 2022 |
| HP            | 1825                        | Desktop     | [afc1259508](https://bsd-hardware.info/?probe=afc1259508) | Dec 31, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [b6ec2e7e28](https://bsd-hardware.info/?probe=b6ec2e7e28) | Dec 31, 2022 |
| Lenovo        | IdeaPad L340-17IWL 81M0     | Notebook    | [22c4a06468](https://bsd-hardware.info/?probe=22c4a06468) | Dec 31, 2022 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [ab7e64f657](https://bsd-hardware.info/?probe=ab7e64f657) | Dec 31, 2022 |
| Sophos        | UTM                         | Firewall    | [81bbacbfee](https://bsd-hardware.info/?probe=81bbacbfee) | Dec 31, 2022 |
| Deciso        | OPNsense Appliance          | Notebook    | [21e1293019](https://bsd-hardware.info/?probe=21e1293019) | Dec 31, 2022 |
| Sophos        | SG                          | Firewall    | [8679b4c8f4](https://bsd-hardware.info/?probe=8679b4c8f4) | Dec 31, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [0bf1c2abef](https://bsd-hardware.info/?probe=0bf1c2abef) | Dec 31, 2022 |
| Lenovo        | 30D9 SDK0J40700 WIN 3258... | Desktop     | [ac867149f2](https://bsd-hardware.info/?probe=ac867149f2) | Dec 31, 2022 |
| Supermicro    | X11SSH-LN4F                 | Server      | [5e84d1a402](https://bsd-hardware.info/?probe=5e84d1a402) | Dec 31, 2022 |
| Dell          | 04415J A00                  | Mini pc     | [c6c6858ef0](https://bsd-hardware.info/?probe=c6c6858ef0) | Dec 31, 2022 |
| Supermicro    | X10SDV-TP8F                 | Server      | [16daca3076](https://bsd-hardware.info/?probe=16daca3076) | Dec 31, 2022 |
| Unknown       | Unknown                     | Desktop     | [68a847f5c2](https://bsd-hardware.info/?probe=68a847f5c2) | Dec 31, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [cac58d91b6](https://bsd-hardware.info/?probe=cac58d91b6) | Dec 31, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [910c2bba4a](https://bsd-hardware.info/?probe=910c2bba4a) | Dec 31, 2022 |
| ASUSTek       | PRIME A320I-K               | Desktop     | [334575b738](https://bsd-hardware.info/?probe=334575b738) | Dec 31, 2022 |
| GoWin Solu... | R86S                        | Desktop     | [4243d313a1](https://bsd-hardware.info/?probe=4243d313a1) | Dec 31, 2022 |
| Supermicro    | X10SDV-TP8F                 | Server      | [5967766127](https://bsd-hardware.info/?probe=5967766127) | Dec 30, 2022 |
| Lenovo        | ThinkPad T410 2518C3U       | Notebook    | [c791e3e3fd](https://bsd-hardware.info/?probe=c791e3e3fd) | Dec 30, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B9450FA_... | Notebook    | [d5fa6c651c](https://bsd-hardware.info/?probe=d5fa6c651c) | Dec 30, 2022 |
| Fujitsu       | D3313-S3 S26361-D3313-S3    | Desktop     | [b89a55c4aa](https://bsd-hardware.info/?probe=b89a55c4aa) | Dec 30, 2022 |
| OEM           | 1.0                         | Desktop     | [f2aeb0ea02](https://bsd-hardware.info/?probe=f2aeb0ea02) | Dec 30, 2022 |
| CompuLab      | SBC-fit-PC4                 | Mini pc     | [c781bd46dc](https://bsd-hardware.info/?probe=c781bd46dc) | Dec 30, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [cd3e4f7122](https://bsd-hardware.info/?probe=cd3e4f7122) | Dec 30, 2022 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | Desktop     | [a8ece272af](https://bsd-hardware.info/?probe=a8ece272af) | Dec 30, 2022 |
| Protectli     | FW4B                        | Desktop     | [406fe72c22](https://bsd-hardware.info/?probe=406fe72c22) | Dec 30, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [126bde2444](https://bsd-hardware.info/?probe=126bde2444) | Dec 30, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [956499202e](https://bsd-hardware.info/?probe=956499202e) | Dec 30, 2022 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [4d9a4bfc40](https://bsd-hardware.info/?probe=4d9a4bfc40) | Dec 30, 2022 |
| Supermicro    | X10SDV-8C-TLN4F+            | Server      | [d4460f8031](https://bsd-hardware.info/?probe=d4460f8031) | Dec 30, 2022 |
| Protectli     | FW6                         | Desktop     | [0d62222b7a](https://bsd-hardware.info/?probe=0d62222b7a) | Dec 30, 2022 |
| Supermicro    | X10SDV-8C-TLN4F+            | Server      | [46c3e7ffdd](https://bsd-hardware.info/?probe=46c3e7ffdd) | Dec 30, 2022 |
| Deciso        | OPNsense Appliance          | Notebook    | [8b4c84d972](https://bsd-hardware.info/?probe=8b4c84d972) | Dec 30, 2022 |
| Unknown       | Unknown                     | Firewall    | [72eaa7a90f](https://bsd-hardware.info/?probe=72eaa7a90f) | Dec 30, 2022 |
| Shuttle       | FH110                       | Desktop     | [3759d77a05](https://bsd-hardware.info/?probe=3759d77a05) | Dec 29, 2022 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [e23f822438](https://bsd-hardware.info/?probe=e23f822438) | Dec 29, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [d22c37fa81](https://bsd-hardware.info/?probe=d22c37fa81) | Dec 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [0f727c761b](https://bsd-hardware.info/?probe=0f727c761b) | Dec 29, 2022 |
| Gigabyte      | MBHM87P-00                  | Desktop     | [5d287163c9](https://bsd-hardware.info/?probe=5d287163c9) | Dec 29, 2022 |
| Dell          | 0GN4PW A00                  | Desktop     | [77e235d9f8](https://bsd-hardware.info/?probe=77e235d9f8) | Dec 29, 2022 |
| Advantech     | UNO-2483G-474AE             | Desktop     | [d453f64b4f](https://bsd-hardware.info/?probe=d453f64b4f) | Dec 29, 2022 |
| HP            | 8000 X4                     | Desktop     | [e66d228381](https://bsd-hardware.info/?probe=e66d228381) | Dec 29, 2022 |
| PC Engines    | APU2                        | Desktop     | [7aaf2d91ba](https://bsd-hardware.info/?probe=7aaf2d91ba) | Dec 29, 2022 |
| Lanner        | FW-7543 B-GA                | Desktop     | [6c145361a3](https://bsd-hardware.info/?probe=6c145361a3) | Dec 29, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [d3b1e89901](https://bsd-hardware.info/?probe=d3b1e89901) | Dec 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [1dab2c420a](https://bsd-hardware.info/?probe=1dab2c420a) | Dec 28, 2022 |
| Intel         | DENLOW_REFRESH_WS           | Desktop     | [4f86e686d2](https://bsd-hardware.info/?probe=4f86e686d2) | Dec 28, 2022 |
| MSI           | H270 GAMING M3              | Desktop     | [5d14519e73](https://bsd-hardware.info/?probe=5d14519e73) | Dec 28, 2022 |
| MSI           | H270 GAMING M3              | Desktop     | [5dcdab1ee3](https://bsd-hardware.info/?probe=5dcdab1ee3) | Dec 28, 2022 |
| Hardkernel    | ODROID-H2                   | Desktop     | [b685ddc2ad](https://bsd-hardware.info/?probe=b685ddc2ad) | Dec 28, 2022 |
| Supermicro    | X10SDV-TP8F                 | Server      | [fa3c5f6504](https://bsd-hardware.info/?probe=fa3c5f6504) | Dec 28, 2022 |
| PC Engines    | APU2                        | Desktop     | [85da0654e1](https://bsd-hardware.info/?probe=85da0654e1) | Dec 28, 2022 |
| Intel         | CARLOW                      | Desktop     | [fa30f060f3](https://bsd-hardware.info/?probe=fa30f060f3) | Dec 28, 2022 |
| Timi          | Redmi Book Pro 14 2022      | Notebook    | [ce5e882952](https://bsd-hardware.info/?probe=ce5e882952) | Dec 28, 2022 |
| ASUSTek       | P11C-M Series               | Desktop     | [21f838983b](https://bsd-hardware.info/?probe=21f838983b) | Dec 28, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [9954c0abee](https://bsd-hardware.info/?probe=9954c0abee) | Dec 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [5b8ad02694](https://bsd-hardware.info/?probe=5b8ad02694) | Dec 28, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [5dafbbced0](https://bsd-hardware.info/?probe=5dafbbced0) | Dec 28, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B      | Desktop     | [888de76acd](https://bsd-hardware.info/?probe=888de76acd) | Dec 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [e70af54c3f](https://bsd-hardware.info/?probe=e70af54c3f) | Dec 28, 2022 |
| HP            | 1998                        | Desktop     | [afc7de60e3](https://bsd-hardware.info/?probe=afc7de60e3) | Dec 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [c3b95220d7](https://bsd-hardware.info/?probe=c3b95220d7) | Dec 28, 2022 |
| ZOTAC         | ZBOX-CI341                  | Mini pc     | [79d8b1477f](https://bsd-hardware.info/?probe=79d8b1477f) | Dec 28, 2022 |
| Shuttle       | FH110                       | Desktop     | [be457c2796](https://bsd-hardware.info/?probe=be457c2796) | Dec 27, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [8d3ab2cab5](https://bsd-hardware.info/?probe=8d3ab2cab5) | Dec 27, 2022 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [4bcc34fdca](https://bsd-hardware.info/?probe=4bcc34fdca) | Dec 27, 2022 |
| Intel         | D2500HN AAG81480-500        | Desktop     | [dae5627541](https://bsd-hardware.info/?probe=dae5627541) | Dec 27, 2022 |
| Google        | Peppy                       | Notebook    | [e063619f03](https://bsd-hardware.info/?probe=e063619f03) | Dec 27, 2022 |
| Apple         | MacBookAir5,1               | Notebook    | [0d398d5c59](https://bsd-hardware.info/?probe=0d398d5c59) | Dec 27, 2022 |
| Lenovo        | 314D NOK                    | Mini pc     | [8cb1f1a8ea](https://bsd-hardware.info/?probe=8cb1f1a8ea) | Dec 27, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [3bdb5aa361](https://bsd-hardware.info/?probe=3bdb5aa361) | Dec 27, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [41094c24b2](https://bsd-hardware.info/?probe=41094c24b2) | Dec 27, 2022 |
| Dell          | 0X744K A02                  | Server      | [c63d853abc](https://bsd-hardware.info/?probe=c63d853abc) | Dec 27, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [07dc4a3178](https://bsd-hardware.info/?probe=07dc4a3178) | Dec 27, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [b553cea3bd](https://bsd-hardware.info/?probe=b553cea3bd) | Dec 26, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [50c8cb79f7](https://bsd-hardware.info/?probe=50c8cb79f7) | Dec 26, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [d4296fd9d8](https://bsd-hardware.info/?probe=d4296fd9d8) | Dec 26, 2022 |
| Sophos        | SG                          | Firewall    | [e331fe5e06](https://bsd-hardware.info/?probe=e331fe5e06) | Dec 26, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [2265227a5c](https://bsd-hardware.info/?probe=2265227a5c) | Dec 26, 2022 |
| Dell          | 0X744K A02                  | Server      | [a9dac66670](https://bsd-hardware.info/?probe=a9dac66670) | Dec 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [39bce6117f](https://bsd-hardware.info/?probe=39bce6117f) | Dec 26, 2022 |
| Dell          | 051FJ8 A01                  | Desktop     | [7f66a21d24](https://bsd-hardware.info/?probe=7f66a21d24) | Dec 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [e52abbf1b8](https://bsd-hardware.info/?probe=e52abbf1b8) | Dec 26, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [d62deb9883](https://bsd-hardware.info/?probe=d62deb9883) | Dec 26, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [7b36d32911](https://bsd-hardware.info/?probe=7b36d32911) | Dec 26, 2022 |
| Lenovo        | 314D NOK                    | Mini pc     | [5f713b6061](https://bsd-hardware.info/?probe=5f713b6061) | Dec 26, 2022 |
| Protectli     | FW6                         | Desktop     | [90758fca97](https://bsd-hardware.info/?probe=90758fca97) | Dec 26, 2022 |
| Dell          | 0M877N A01                  | Server      | [340dc7255c](https://bsd-hardware.info/?probe=340dc7255c) | Dec 26, 2022 |
| Deciso        | OPNsense Appliance          | Notebook    | [3fc9a4fd5c](https://bsd-hardware.info/?probe=3fc9a4fd5c) | Dec 26, 2022 |
| Deciso        | NetBoard-A10                | Notebook    | [b09ff8826c](https://bsd-hardware.info/?probe=b09ff8826c) | Dec 26, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [f2a248dcfe](https://bsd-hardware.info/?probe=f2a248dcfe) | Dec 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [b4d44b0018](https://bsd-hardware.info/?probe=b4d44b0018) | Dec 26, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [bc829dbb1a](https://bsd-hardware.info/?probe=bc829dbb1a) | Dec 25, 2022 |
| MSI           | H81M-P33                    | Desktop     | [f73a37ab81](https://bsd-hardware.info/?probe=f73a37ab81) | Dec 25, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [2e842ddb27](https://bsd-hardware.info/?probe=2e842ddb27) | Dec 25, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [883dbf15e4](https://bsd-hardware.info/?probe=883dbf15e4) | Dec 25, 2022 |
| Cisco         | ASA5515 A0                  | Desktop     | [9e587b9499](https://bsd-hardware.info/?probe=9e587b9499) | Dec 25, 2022 |
| Shuttle       | FH110                       | Desktop     | [a194756b95](https://bsd-hardware.info/?probe=a194756b95) | Dec 25, 2022 |
| Gigabyte      | X399 AORUS Gaming 7         | Desktop     | [1769da5143](https://bsd-hardware.info/?probe=1769da5143) | Dec 25, 2022 |
| HP            | 8062                        | Desktop     | [f4d3eb024d](https://bsd-hardware.info/?probe=f4d3eb024d) | Dec 25, 2022 |
| Star Labs     | Lite                        | Notebook    | [9ad15636dd](https://bsd-hardware.info/?probe=9ad15636dd) | Dec 25, 2022 |
| HP            | 213D A01                    | Desktop     | [bd620f0fc0](https://bsd-hardware.info/?probe=bd620f0fc0) | Dec 25, 2022 |
| MSI           | B560M-A PRO                 | Desktop     | [f1cb9703a7](https://bsd-hardware.info/?probe=f1cb9703a7) | Dec 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [bd212706ad](https://bsd-hardware.info/?probe=bd212706ad) | Dec 24, 2022 |
| Lenovo        | 314D NOK                    | Mini pc     | [af60c7ce81](https://bsd-hardware.info/?probe=af60c7ce81) | Dec 24, 2022 |
| Supermicro    | X10SRH-CLN4FA               | Desktop     | [84c360ad02](https://bsd-hardware.info/?probe=84c360ad02) | Dec 24, 2022 |
| Sophos        | UTM                         | Firewall    | [224580445a](https://bsd-hardware.info/?probe=224580445a) | Dec 24, 2022 |
| Alienware     | m15 R4                      | Notebook    | [deaef8f0ef](https://bsd-hardware.info/?probe=deaef8f0ef) | Dec 24, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [33c59c687d](https://bsd-hardware.info/?probe=33c59c687d) | Dec 24, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [153f99a846](https://bsd-hardware.info/?probe=153f99a846) | Dec 24, 2022 |
| HP            | 8299                        | Desktop     | [6715ee2886](https://bsd-hardware.info/?probe=6715ee2886) | Dec 24, 2022 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [b29f2e4573](https://bsd-hardware.info/?probe=b29f2e4573) | Dec 24, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [701c6e95d6](https://bsd-hardware.info/?probe=701c6e95d6) | Dec 24, 2022 |
| ASRock        | N3710-NUC IPC               | Desktop     | [80c809e992](https://bsd-hardware.info/?probe=80c809e992) | Dec 24, 2022 |
| Gigabyte      | Z390 AORUS ELITE            | Desktop     | [91b7417b84](https://bsd-hardware.info/?probe=91b7417b84) | Dec 24, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [4c3b92bb42](https://bsd-hardware.info/?probe=4c3b92bb42) | Dec 24, 2022 |
| Dell          | 0H28RR A04                  | Server      | [8e22402d9e](https://bsd-hardware.info/?probe=8e22402d9e) | Dec 24, 2022 |
| Biostar       | A32M2                       | Desktop     | [49c31b364c](https://bsd-hardware.info/?probe=49c31b364c) | Dec 23, 2022 |
| Tactus        | GeoFlex 110                 | Notebook    | [955c355b47](https://bsd-hardware.info/?probe=955c355b47) | Dec 23, 2022 |
| Toshiba       | Satellite BE96-F299         | Notebook    | [ca475dd1d0](https://bsd-hardware.info/?probe=ca475dd1d0) | Dec 23, 2022 |
| Biostar       | A10N-8800E                  | Desktop     | [d3d1107f77](https://bsd-hardware.info/?probe=d3d1107f77) | Dec 23, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [58b47341c9](https://bsd-hardware.info/?probe=58b47341c9) | Dec 23, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [b38d32b139](https://bsd-hardware.info/?probe=b38d32b139) | Dec 23, 2022 |
| MSI           | A78M-E35                    | Desktop     | [03176e6683](https://bsd-hardware.info/?probe=03176e6683) | Dec 23, 2022 |
| Sony          | VPCSB11FX                   | Notebook    | [966183e570](https://bsd-hardware.info/?probe=966183e570) | Dec 23, 2022 |
| Dell          | 0NW6H5 A00                  | Desktop     | [b19a4d1696](https://bsd-hardware.info/?probe=b19a4d1696) | Dec 23, 2022 |
| Dell          | 03X6X0 A00                  | Server      | [52327286e4](https://bsd-hardware.info/?probe=52327286e4) | Dec 23, 2022 |
| Dell          | 03X6X0 A00                  | Server      | [0d70cc442b](https://bsd-hardware.info/?probe=0d70cc442b) | Dec 23, 2022 |
| ASRock        | B75M R2.0                   | Desktop     | [3a8d5c61b6](https://bsd-hardware.info/?probe=3a8d5c61b6) | Dec 23, 2022 |
| Lenovo        | ThinkPad T480 20L6S13100    | Notebook    | [67daa912fa](https://bsd-hardware.info/?probe=67daa912fa) | Dec 23, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [7cccecfde1](https://bsd-hardware.info/?probe=7cccecfde1) | Dec 23, 2022 |
| Intel BOX4... | Geminilake                  | Desktop     | [a2b2b7c25f](https://bsd-hardware.info/?probe=a2b2b7c25f) | Dec 23, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [a2bc442acd](https://bsd-hardware.info/?probe=a2bc442acd) | Dec 23, 2022 |
| Intel BOX4... | Geminilake                  | Desktop     | [06933f3d87](https://bsd-hardware.info/?probe=06933f3d87) | Dec 23, 2022 |
| Unknown       | QD-WHLU01                   | Desktop     | [a0fb185069](https://bsd-hardware.info/?probe=a0fb185069) | Dec 23, 2022 |
| Dell          | 03X6X0 A02                  | Server      | [e0b4e13386](https://bsd-hardware.info/?probe=e0b4e13386) | Dec 23, 2022 |
| MSI           | B560M-A PRO                 | Desktop     | [8325caa4d6](https://bsd-hardware.info/?probe=8325caa4d6) | Dec 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [d702dfcde2](https://bsd-hardware.info/?probe=d702dfcde2) | Dec 23, 2022 |
| Dell          | Vostro 1400                 | Notebook    | [087a3d269f](https://bsd-hardware.info/?probe=087a3d269f) | Dec 23, 2022 |
| Acer          | Aspire ES1-533              | Notebook    | [570b96d0f7](https://bsd-hardware.info/?probe=570b96d0f7) | Dec 23, 2022 |
| HP            | 8299                        | Desktop     | [d9eec3c9f5](https://bsd-hardware.info/?probe=d9eec3c9f5) | Dec 23, 2022 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [91a89db2ab](https://bsd-hardware.info/?probe=91a89db2ab) | Dec 23, 2022 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [bc2c536004](https://bsd-hardware.info/?probe=bc2c536004) | Dec 23, 2022 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [58ca7ca7d4](https://bsd-hardware.info/?probe=58ca7ca7d4) | Dec 23, 2022 |
| Deciso        | OPNsense Appliance          | Notebook    | [062fb4cccd](https://bsd-hardware.info/?probe=062fb4cccd) | Dec 23, 2022 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [dfd3e7acb1](https://bsd-hardware.info/?probe=dfd3e7acb1) | Dec 23, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [daaad6a386](https://bsd-hardware.info/?probe=daaad6a386) | Dec 23, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [67bc182d1d](https://bsd-hardware.info/?probe=67bc182d1d) | Dec 23, 2022 |
| MSI           | B560M-A PRO                 | Desktop     | [6f8bdb560b](https://bsd-hardware.info/?probe=6f8bdb560b) | Dec 23, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [3e5e7e3e61](https://bsd-hardware.info/?probe=3e5e7e3e61) | Dec 22, 2022 |
| Lenovo        | Yoga 710-11IKB 80V6         | Notebook    | [1d3ccd1fe6](https://bsd-hardware.info/?probe=1d3ccd1fe6) | Dec 22, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [cde7bad6c3](https://bsd-hardware.info/?probe=cde7bad6c3) | Dec 22, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [78bcccda01](https://bsd-hardware.info/?probe=78bcccda01) | Dec 22, 2022 |
| Dell          | 060J9C A00                  | Mini pc     | [29b3e0b639](https://bsd-hardware.info/?probe=29b3e0b639) | Dec 22, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [eea4262af2](https://bsd-hardware.info/?probe=eea4262af2) | Dec 22, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [cae00eb4d6](https://bsd-hardware.info/?probe=cae00eb4d6) | Dec 22, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [01d8e43ee1](https://bsd-hardware.info/?probe=01d8e43ee1) | Dec 22, 2022 |
| Unknown       | Unknown                     | Desktop     | [0f03a7f2ce](https://bsd-hardware.info/?probe=0f03a7f2ce) | Dec 22, 2022 |
| AAEON         | FWS-2251 V1.0               | Desktop     | [a4ff0a7ec5](https://bsd-hardware.info/?probe=a4ff0a7ec5) | Dec 22, 2022 |
| ZOTAC         | ZBOX-MI640/MI660/MI620NA... | Mini pc     | [9e817a9114](https://bsd-hardware.info/?probe=9e817a9114) | Dec 22, 2022 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [90dfe8ee6b](https://bsd-hardware.info/?probe=90dfe8ee6b) | Dec 22, 2022 |
| Acer          | WG43M                       | Desktop     | [d316352c20](https://bsd-hardware.info/?probe=d316352c20) | Dec 22, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [527bf6bbe4](https://bsd-hardware.info/?probe=527bf6bbe4) | Dec 22, 2022 |
| Supermicro    | X9DR3-F                     | Desktop     | [b8c89bdca8](https://bsd-hardware.info/?probe=b8c89bdca8) | Dec 22, 2022 |
| Supermicro    | X10SDV-8C-TLN4F+            | Server      | [633b9a5425](https://bsd-hardware.info/?probe=633b9a5425) | Dec 22, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [2ac107df0f](https://bsd-hardware.info/?probe=2ac107df0f) | Dec 22, 2022 |
| AMI           | Cherry Trail CR             | Mini pc     | [cc9eb40ce1](https://bsd-hardware.info/?probe=cc9eb40ce1) | Dec 22, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [f241237f76](https://bsd-hardware.info/?probe=f241237f76) | Dec 22, 2022 |
| Dell          | 0WR7PY A02                  | Desktop     | [0c3fea5eb0](https://bsd-hardware.info/?probe=0c3fea5eb0) | Dec 22, 2022 |
| Unknown       | Unknown                     | Desktop     | [0a40b02aeb](https://bsd-hardware.info/?probe=0a40b02aeb) | Dec 22, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [df221cefbc](https://bsd-hardware.info/?probe=df221cefbc) | Dec 22, 2022 |
| Supermicro    | X9DR3-F                     | Desktop     | [b0d1792185](https://bsd-hardware.info/?probe=b0d1792185) | Dec 21, 2022 |
| ZOTAC         | ZBOX-MI640/MI660/MI620NA... | Mini pc     | [16589e2878](https://bsd-hardware.info/?probe=16589e2878) | Dec 21, 2022 |
| HP            | ProLiant DL360 Gen9         | Server      | [17ddf8c2e1](https://bsd-hardware.info/?probe=17ddf8c2e1) | Dec 21, 2022 |
| PC Engines    | APU2                        | Desktop     | [9781d92062](https://bsd-hardware.info/?probe=9781d92062) | Dec 21, 2022 |
| Dell          | 0KYJ8C A02                  | Desktop     | [490f20c93d](https://bsd-hardware.info/?probe=490f20c93d) | Dec 21, 2022 |
| PC Engines    | APU2                        | Desktop     | [e94b983d48](https://bsd-hardware.info/?probe=e94b983d48) | Dec 21, 2022 |
| ACMA          | X8SIE                       | Desktop     | [01898b2ffb](https://bsd-hardware.info/?probe=01898b2ffb) | Dec 21, 2022 |
| Dell          | 0UW457 A03                  | Desktop     | [47b66a0d86](https://bsd-hardware.info/?probe=47b66a0d86) | Dec 21, 2022 |
| Raspberry ... | Raspberry Pi 400            | Desktop     | [ee9cac334f](https://bsd-hardware.info/?probe=ee9cac334f) | Dec 21, 2022 |
| Lenovo        | ThinkPad T60 1951A47        | Notebook    | [e254601f07](https://bsd-hardware.info/?probe=e254601f07) | Dec 21, 2022 |
| HP            | 18E7                        | Desktop     | [0b962b9400](https://bsd-hardware.info/?probe=0b962b9400) | Dec 20, 2022 |
| Intel         | S3420GP E51976-407          | Server      | [c614a1e46f](https://bsd-hardware.info/?probe=c614a1e46f) | Dec 20, 2022 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [16f59f69dc](https://bsd-hardware.info/?probe=16f59f69dc) | Dec 20, 2022 |
| Unknown       | Unknown                     | Desktop     | [0bffe61dae](https://bsd-hardware.info/?probe=0bffe61dae) | Dec 20, 2022 |
| ASRock        | 4X4-4000 Series             | Desktop     | [009ef73bd1](https://bsd-hardware.info/?probe=009ef73bd1) | Dec 20, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [3502cb3d47](https://bsd-hardware.info/?probe=3502cb3d47) | Dec 20, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [a8ec4c3ae4](https://bsd-hardware.info/?probe=a8ec4c3ae4) | Dec 20, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [4667028e67](https://bsd-hardware.info/?probe=4667028e67) | Dec 20, 2022 |
| Protectli     | FW2B Ver                    | Desktop     | [9596576df7](https://bsd-hardware.info/?probe=9596576df7) | Dec 20, 2022 |
| Lenovo        | 3098 SDK0E50510 PRO or W... | Desktop     | [e1e1a80328](https://bsd-hardware.info/?probe=e1e1a80328) | Dec 20, 2022 |
| Dell          | 0X744K A02                  | Server      | [e45fc09011](https://bsd-hardware.info/?probe=e45fc09011) | Dec 20, 2022 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | Desktop     | [2ea413db31](https://bsd-hardware.info/?probe=2ea413db31) | Dec 20, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [8de4ff8626](https://bsd-hardware.info/?probe=8de4ff8626) | Dec 20, 2022 |
| ASRock        | 4X4-4000 Series             | Desktop     | [31f17adc5b](https://bsd-hardware.info/?probe=31f17adc5b) | Dec 20, 2022 |
| Dell          | 0WR7PY A00                  | Desktop     | [360336dcc1](https://bsd-hardware.info/?probe=360336dcc1) | Dec 20, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [af2a9d1a42](https://bsd-hardware.info/?probe=af2a9d1a42) | Dec 20, 2022 |
| Unknown       | Unknown                     | Notebook    | [364b3758b6](https://bsd-hardware.info/?probe=364b3758b6) | Dec 20, 2022 |
| Sophos        | SG                          | Firewall    | [5536740301](https://bsd-hardware.info/?probe=5536740301) | Dec 20, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [3c36f8db41](https://bsd-hardware.info/?probe=3c36f8db41) | Dec 20, 2022 |
| MSI           | MS-7922                     | Desktop     | [95dbf4f7a8](https://bsd-hardware.info/?probe=95dbf4f7a8) | Dec 19, 2022 |
| Supermicro    | X10SDV-4C-TLN4F             | Server      | [c0c8d1f85e](https://bsd-hardware.info/?probe=c0c8d1f85e) | Dec 19, 2022 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [32207ea5d9](https://bsd-hardware.info/?probe=32207ea5d9) | Dec 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [4c5ccd04d0](https://bsd-hardware.info/?probe=4c5ccd04d0) | Dec 19, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [b84941cdd5](https://bsd-hardware.info/?probe=b84941cdd5) | Dec 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [5d37a0669c](https://bsd-hardware.info/?probe=5d37a0669c) | Dec 19, 2022 |
| Lenovo        | ThinkPad T530 2392AQU       | Notebook    | [9a3cbe1893](https://bsd-hardware.info/?probe=9a3cbe1893) | Dec 19, 2022 |
| Dell          | 0WR7PY A02                  | Desktop     | [67baacfc7d](https://bsd-hardware.info/?probe=67baacfc7d) | Dec 19, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [0eea35e069](https://bsd-hardware.info/?probe=0eea35e069) | Dec 19, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [c9de65beeb](https://bsd-hardware.info/?probe=c9de65beeb) | Dec 19, 2022 |
| PC Engines    | APU2                        | Desktop     | [5de84cb508](https://bsd-hardware.info/?probe=5de84cb508) | Dec 19, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [ced12f0b41](https://bsd-hardware.info/?probe=ced12f0b41) | Dec 19, 2022 |
| Pegatron      | 2ACF                        | Desktop     | [511f2a6d16](https://bsd-hardware.info/?probe=511f2a6d16) | Dec 19, 2022 |
| Unknown       | Pine64 RockPro64 v2.1       | Desktop     | [59525051d3](https://bsd-hardware.info/?probe=59525051d3) | Dec 19, 2022 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | Notebook    | [683591700f](https://bsd-hardware.info/?probe=683591700f) | Dec 19, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [fad0a431e5](https://bsd-hardware.info/?probe=fad0a431e5) | Dec 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [f876d5d5b1](https://bsd-hardware.info/?probe=f876d5d5b1) | Dec 19, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [b730e64d4a](https://bsd-hardware.info/?probe=b730e64d4a) | Dec 19, 2022 |
| Lenovo        | ThinkPad X200 Tablet 744... | Notebook    | [ea686f63f5](https://bsd-hardware.info/?probe=ea686f63f5) | Dec 19, 2022 |
| Framework     | Laptop                      | Notebook    | [9dcd3592db](https://bsd-hardware.info/?probe=9dcd3592db) | Dec 19, 2022 |
| Gigabyte      | H81M-DS2                    | Desktop     | [29ad5ee336](https://bsd-hardware.info/?probe=29ad5ee336) | Dec 19, 2022 |
| Acer          | Veriton M680G               | Desktop     | [cb44a9e848](https://bsd-hardware.info/?probe=cb44a9e848) | Dec 19, 2022 |
| Acer          | Veriton M680G               | Desktop     | [f7184d9158](https://bsd-hardware.info/?probe=f7184d9158) | Dec 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [3d77f833b0](https://bsd-hardware.info/?probe=3d77f833b0) | Dec 19, 2022 |
| Dell          | 0VD50G A01                  | Server      | [07852bf200](https://bsd-hardware.info/?probe=07852bf200) | Dec 19, 2022 |
| HP            | ProLiant DL360p Gen8        | Server      | [b9df714117](https://bsd-hardware.info/?probe=b9df714117) | Dec 19, 2022 |
| Supermicro    | X11SSL-F                    | Server      | [7bd99b62ab](https://bsd-hardware.info/?probe=7bd99b62ab) | Dec 19, 2022 |
| Dell          | Edge Gateway 5000           | Mini pc     | [0af7422e2f](https://bsd-hardware.info/?probe=0af7422e2f) | Dec 18, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [f321130f0e](https://bsd-hardware.info/?probe=f321130f0e) | Dec 18, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [14d483ac06](https://bsd-hardware.info/?probe=14d483ac06) | Dec 18, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [c233fa7d25](https://bsd-hardware.info/?probe=c233fa7d25) | Dec 18, 2022 |
| Dell          | Precision M4800             | Notebook    | [b7a834c4d0](https://bsd-hardware.info/?probe=b7a834c4d0) | Dec 18, 2022 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [53a90a6c63](https://bsd-hardware.info/?probe=53a90a6c63) | Dec 18, 2022 |
| ASRock        | B660M-ITX/ac                | Desktop     | [f6c8eb4e18](https://bsd-hardware.info/?probe=f6c8eb4e18) | Dec 18, 2022 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [abe21b9c9e](https://bsd-hardware.info/?probe=abe21b9c9e) | Dec 18, 2022 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [fc7928dfe9](https://bsd-hardware.info/?probe=fc7928dfe9) | Dec 18, 2022 |
| ASRock        | E3C224D2I                   | Desktop     | [106e525671](https://bsd-hardware.info/?probe=106e525671) | Dec 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [c1b0b83306](https://bsd-hardware.info/?probe=c1b0b83306) | Dec 18, 2022 |
| MSI           | H81M-P33                    | Desktop     | [78e4743abd](https://bsd-hardware.info/?probe=78e4743abd) | Dec 18, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [f232e5746e](https://bsd-hardware.info/?probe=f232e5746e) | Dec 18, 2022 |
| Supermicro    | X11SCL-F                    | Server      | [638b27bc34](https://bsd-hardware.info/?probe=638b27bc34) | Dec 18, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [108c9de5cc](https://bsd-hardware.info/?probe=108c9de5cc) | Dec 18, 2022 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | Desktop     | [1f1de1d49c](https://bsd-hardware.info/?probe=1f1de1d49c) | Dec 18, 2022 |
| ASRock        | H370M-ITX/ac                | Desktop     | [a40ada7f7f](https://bsd-hardware.info/?probe=a40ada7f7f) | Dec 18, 2022 |
| Unknown       | Unknown                     | Desktop     | [f6fababc22](https://bsd-hardware.info/?probe=f6fababc22) | Dec 18, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [e06fa5d522](https://bsd-hardware.info/?probe=e06fa5d522) | Dec 18, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [a1b29c356e](https://bsd-hardware.info/?probe=a1b29c356e) | Dec 17, 2022 |
| MSI           | X299 PRO                    | Desktop     | [beec8001a1](https://bsd-hardware.info/?probe=beec8001a1) | Dec 17, 2022 |
| Protectli     | FW6                         | Desktop     | [56f62226e7](https://bsd-hardware.info/?probe=56f62226e7) | Dec 17, 2022 |
| PC Engines    | APU3                        | Desktop     | [5597cca988](https://bsd-hardware.info/?probe=5597cca988) | Dec 17, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [92593f4e79](https://bsd-hardware.info/?probe=92593f4e79) | Dec 17, 2022 |
| MSI           | MS-98C8                     | Desktop     | [a6e45c8e5f](https://bsd-hardware.info/?probe=a6e45c8e5f) | Dec 17, 2022 |
| Dell          | Latitude E6430              | Notebook    | [b8f950de05](https://bsd-hardware.info/?probe=b8f950de05) | Dec 17, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [7cf06451fd](https://bsd-hardware.info/?probe=7cf06451fd) | Dec 17, 2022 |
| Lenovo        | ThinkCentre M93p 10A8S0C... | Desktop     | [11d5b82cdd](https://bsd-hardware.info/?probe=11d5b82cdd) | Dec 17, 2022 |
| PC Engines    | APU3                        | Desktop     | [0e1197c771](https://bsd-hardware.info/?probe=0e1197c771) | Dec 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [0e98358cf3](https://bsd-hardware.info/?probe=0e98358cf3) | Dec 17, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [e8095445e8](https://bsd-hardware.info/?probe=e8095445e8) | Dec 17, 2022 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [088766f04d](https://bsd-hardware.info/?probe=088766f04d) | Dec 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [f7700c781d](https://bsd-hardware.info/?probe=f7700c781d) | Dec 17, 2022 |
| Dell          | 03X6X0 A02                  | Server      | [f6085ba691](https://bsd-hardware.info/?probe=f6085ba691) | Dec 17, 2022 |
| Intel         | CRESCENTBAY                 | Desktop     | [7981529337](https://bsd-hardware.info/?probe=7981529337) | Dec 17, 2022 |
| PC Engines    | APU                         | Desktop     | [19786edc61](https://bsd-hardware.info/?probe=19786edc61) | Dec 17, 2022 |
| Dell          | 0FDY5C A00                  | Desktop     | [afef2952f9](https://bsd-hardware.info/?probe=afef2952f9) | Dec 17, 2022 |
| BESSTAR Te... | UM350                       | Desktop     | [b7e599f99d](https://bsd-hardware.info/?probe=b7e599f99d) | Dec 17, 2022 |
| Dell          | Latitude E6430              | Notebook    | [8d92a4e37e](https://bsd-hardware.info/?probe=8d92a4e37e) | Dec 17, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [0da9ef9752](https://bsd-hardware.info/?probe=0da9ef9752) | Dec 17, 2022 |
| AMI           | PEISIA E3845 VER1.0         | Desktop     | [c3ffb2c87d](https://bsd-hardware.info/?probe=c3ffb2c87d) | Dec 17, 2022 |
| Intel         | DN2820FYK H24582-203        | Desktop     | [160d942d28](https://bsd-hardware.info/?probe=160d942d28) | Dec 17, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [2fe9b1b8c9](https://bsd-hardware.info/?probe=2fe9b1b8c9) | Dec 16, 2022 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [4d3d23fbd1](https://bsd-hardware.info/?probe=4d3d23fbd1) | Dec 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [a94bfdaa5c](https://bsd-hardware.info/?probe=a94bfdaa5c) | Dec 16, 2022 |
| Dell          | 02YRK5 A03                  | Desktop     | [547b1abce0](https://bsd-hardware.info/?probe=547b1abce0) | Dec 16, 2022 |
| MSI           | H81M-E33                    | Desktop     | [411bb9d111](https://bsd-hardware.info/?probe=411bb9d111) | Dec 16, 2022 |
| MSI           | MS-B1831                    | Desktop     | [638e327c4e](https://bsd-hardware.info/?probe=638e327c4e) | Dec 16, 2022 |
| ASUSTek       | STRIX Z270I GAMING          | Desktop     | [d44c580408](https://bsd-hardware.info/?probe=d44c580408) | Dec 16, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [6bf18dfe5a](https://bsd-hardware.info/?probe=6bf18dfe5a) | Dec 16, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | Notebook    | [3a9623cfb4](https://bsd-hardware.info/?probe=3a9623cfb4) | Dec 16, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | Notebook    | [0314add226](https://bsd-hardware.info/?probe=0314add226) | Dec 16, 2022 |
| Intel         | DQ77KB AAG81483-501         | Desktop     | [cc51093e02](https://bsd-hardware.info/?probe=cc51093e02) | Dec 16, 2022 |
| ASRock        | Q2900M                      | Desktop     | [42a53e5201](https://bsd-hardware.info/?probe=42a53e5201) | Dec 16, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [fa8c102cfd](https://bsd-hardware.info/?probe=fa8c102cfd) | Dec 16, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [3faaaa8209](https://bsd-hardware.info/?probe=3faaaa8209) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [d19db2828c](https://bsd-hardware.info/?probe=d19db2828c) | Dec 16, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [d9376f2f63](https://bsd-hardware.info/?probe=d9376f2f63) | Dec 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [01e26ec145](https://bsd-hardware.info/?probe=01e26ec145) | Dec 15, 2022 |
| Lenovo        | B50-80 80EW                 | Notebook    | [e6778fa5fd](https://bsd-hardware.info/?probe=e6778fa5fd) | Dec 15, 2022 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [40911b66e2](https://bsd-hardware.info/?probe=40911b66e2) | Dec 15, 2022 |
| Supermicro    | X11SBA-LN4F                 | Server      | [649d525fdb](https://bsd-hardware.info/?probe=649d525fdb) | Dec 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [9ac68a1c6d](https://bsd-hardware.info/?probe=9ac68a1c6d) | Dec 15, 2022 |
| Gigabyte      | N3160ND3V                   | Desktop     | [c84bedc821](https://bsd-hardware.info/?probe=c84bedc821) | Dec 15, 2022 |
| Unknown       | SKYBAY                      | Desktop     | [deb30193e2](https://bsd-hardware.info/?probe=deb30193e2) | Dec 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [e3508ce360](https://bsd-hardware.info/?probe=e3508ce360) | Dec 15, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [435807287e](https://bsd-hardware.info/?probe=435807287e) | Dec 15, 2022 |
| Dell          | 0WR7PY A00                  | Desktop     | [f923c6c0d6](https://bsd-hardware.info/?probe=f923c6c0d6) | Dec 15, 2022 |
| ASUSTek       | K50IN                       | Notebook    | [b8bfdec836](https://bsd-hardware.info/?probe=b8bfdec836) | Dec 15, 2022 |
| Lenovo        | 3098 SDK0E50510 PRO or W... | Desktop     | [7cb1b0cc2d](https://bsd-hardware.info/?probe=7cb1b0cc2d) | Dec 15, 2022 |
| Intel         | H81U                        | Notebook    | [fab3eecc66](https://bsd-hardware.info/?probe=fab3eecc66) | Dec 15, 2022 |
| Dell          | Latitude 5400               | Notebook    | [639993a130](https://bsd-hardware.info/?probe=639993a130) | Dec 15, 2022 |
| Dell          | Latitude 5400               | Notebook    | [5b9eb16e5e](https://bsd-hardware.info/?probe=5b9eb16e5e) | Dec 15, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [55f876d83f](https://bsd-hardware.info/?probe=55f876d83f) | Dec 15, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [e199c0ec3d](https://bsd-hardware.info/?probe=e199c0ec3d) | Dec 15, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [e5c4d51eab](https://bsd-hardware.info/?probe=e5c4d51eab) | Dec 15, 2022 |
| Sophos        | SG                          | Firewall    | [16753b9090](https://bsd-hardware.info/?probe=16753b9090) | Dec 15, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [35ecaf0406](https://bsd-hardware.info/?probe=35ecaf0406) | Dec 15, 2022 |
| ZOTAC         | ZBOX-MI640/MI660/MI620NA... | Mini pc     | [9d71e35375](https://bsd-hardware.info/?probe=9d71e35375) | Dec 15, 2022 |
| ZOTAC         | ZBOX-MI640/MI660/MI620NA... | Mini pc     | [98621b669c](https://bsd-hardware.info/?probe=98621b669c) | Dec 15, 2022 |
| ZOTAC         | ZBOX-MI640/MI660/MI620NA... | Mini pc     | [b0639c3d01](https://bsd-hardware.info/?probe=b0639c3d01) | Dec 15, 2022 |
| ZOTAC         | ZBOX-MI640/MI660/MI620NA... | Mini pc     | [52fbc8ccf7](https://bsd-hardware.info/?probe=52fbc8ccf7) | Dec 15, 2022 |
| Dell          | 0CU409                      | Desktop     | [718c9c5c8b](https://bsd-hardware.info/?probe=718c9c5c8b) | Dec 15, 2022 |
| Dell          | 0CU409                      | Desktop     | [161da6b850](https://bsd-hardware.info/?probe=161da6b850) | Dec 15, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [d7d0ebf605](https://bsd-hardware.info/?probe=d7d0ebf605) | Dec 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [7c644cc639](https://bsd-hardware.info/?probe=7c644cc639) | Dec 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [9b5307f44d](https://bsd-hardware.info/?probe=9b5307f44d) | Dec 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [210418cc84](https://bsd-hardware.info/?probe=210418cc84) | Dec 15, 2022 |
| HP            | 1495                        | Desktop     | [04bd0455f2](https://bsd-hardware.info/?probe=04bd0455f2) | Dec 14, 2022 |
| Supermicro    | A1SRM-2758F                 | Server      | [fb96378782](https://bsd-hardware.info/?probe=fb96378782) | Dec 14, 2022 |
| Intel         | H81U                        | Notebook    | [fe1c3cb754](https://bsd-hardware.info/?probe=fe1c3cb754) | Dec 14, 2022 |
| Lenovo        | B50-80 80EW                 | Notebook    | [9551c57fc3](https://bsd-hardware.info/?probe=9551c57fc3) | Dec 14, 2022 |
| Dell          | 0X4N41 A01                  | Desktop     | [4091e15cac](https://bsd-hardware.info/?probe=4091e15cac) | Dec 14, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [64c549f3ae](https://bsd-hardware.info/?probe=64c549f3ae) | Dec 14, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [e44f465325](https://bsd-hardware.info/?probe=e44f465325) | Dec 14, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [cb16bb9431](https://bsd-hardware.info/?probe=cb16bb9431) | Dec 14, 2022 |
| NF541         | 1.0                         | Desktop     | [b0644bada6](https://bsd-hardware.info/?probe=b0644bada6) | Dec 14, 2022 |
| HP            | 1495                        | Desktop     | [23f8aeada7](https://bsd-hardware.info/?probe=23f8aeada7) | Dec 14, 2022 |
| Dell          | Vostro 15-3568              | Notebook    | [6fc0671dc6](https://bsd-hardware.info/?probe=6fc0671dc6) | Dec 14, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [617f431099](https://bsd-hardware.info/?probe=617f431099) | Dec 14, 2022 |
| HP            | 2215                        | Desktop     | [76f607b100](https://bsd-hardware.info/?probe=76f607b100) | Dec 14, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [a77d60297f](https://bsd-hardware.info/?probe=a77d60297f) | Dec 14, 2022 |
| Unknown       | Unknown                     | Desktop     | [85520bf6bf](https://bsd-hardware.info/?probe=85520bf6bf) | Dec 14, 2022 |
| HP            | ProBook 430 G7              | Notebook    | [0e2278affa](https://bsd-hardware.info/?probe=0e2278affa) | Dec 14, 2022 |
| Dell          | 03X6X0 A02                  | Server      | [6ebcd7c974](https://bsd-hardware.info/?probe=6ebcd7c974) | Dec 14, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [bc15367e9f](https://bsd-hardware.info/?probe=bc15367e9f) | Dec 14, 2022 |
| Unknown       | Unknown                     | Desktop     | [ad7f977515](https://bsd-hardware.info/?probe=ad7f977515) | Dec 13, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [babe4bb620](https://bsd-hardware.info/?probe=babe4bb620) | Dec 13, 2022 |
| AZW           | U59                         | Desktop     | [9b22c68e98](https://bsd-hardware.info/?probe=9b22c68e98) | Dec 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [ec6827e543](https://bsd-hardware.info/?probe=ec6827e543) | Dec 13, 2022 |
| Unknown       | SKYBAY                      | Desktop     | [2d6c881723](https://bsd-hardware.info/?probe=2d6c881723) | Dec 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [f52a3d3fa6](https://bsd-hardware.info/?probe=f52a3d3fa6) | Dec 13, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [f51b401c31](https://bsd-hardware.info/?probe=f51b401c31) | Dec 13, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0Y40... | Notebook    | [ce2b20b3a9](https://bsd-hardware.info/?probe=ce2b20b3a9) | Dec 13, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [abed96a938](https://bsd-hardware.info/?probe=abed96a938) | Dec 13, 2022 |
| Huanan        | X99-F8D V2.4                | Desktop     | [3d06b605c5](https://bsd-hardware.info/?probe=3d06b605c5) | Dec 13, 2022 |
| Gigabyte      | Z590 AORUS PRO AX           | Desktop     | [66e0c118d2](https://bsd-hardware.info/?probe=66e0c118d2) | Dec 13, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [af9df0d2c9](https://bsd-hardware.info/?probe=af9df0d2c9) | Dec 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [9ee8d1082b](https://bsd-hardware.info/?probe=9ee8d1082b) | Dec 12, 2022 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [353c3d5cee](https://bsd-hardware.info/?probe=353c3d5cee) | Dec 12, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0Y40... | Notebook    | [7463e05c88](https://bsd-hardware.info/?probe=7463e05c88) | Dec 12, 2022 |
| HP            | Pavilion dv4                | Notebook    | [ee94a86a43](https://bsd-hardware.info/?probe=ee94a86a43) | Dec 12, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [64c92d49d9](https://bsd-hardware.info/?probe=64c92d49d9) | Dec 12, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [73cb5d86bc](https://bsd-hardware.info/?probe=73cb5d86bc) | Dec 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [128ce54404](https://bsd-hardware.info/?probe=128ce54404) | Dec 12, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [735f01a028](https://bsd-hardware.info/?probe=735f01a028) | Dec 12, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [ca959befa0](https://bsd-hardware.info/?probe=ca959befa0) | Dec 12, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [e1297f9eef](https://bsd-hardware.info/?probe=e1297f9eef) | Dec 12, 2022 |
| Supermicro    | M11SDV-4CT-LN4F             | Server      | [76519f54e9](https://bsd-hardware.info/?probe=76519f54e9) | Dec 12, 2022 |
| Gigabyte      | X99-Designare EX-CF         | Desktop     | [de5bf4b420](https://bsd-hardware.info/?probe=de5bf4b420) | Dec 12, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [2bf8839d12](https://bsd-hardware.info/?probe=2bf8839d12) | Dec 12, 2022 |
| Shuttle       | DH370                       | Desktop     | [1b938aa1a4](https://bsd-hardware.info/?probe=1b938aa1a4) | Dec 12, 2022 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [ba191bd994](https://bsd-hardware.info/?probe=ba191bd994) | Dec 12, 2022 |
| Dell          | 0TY019 A02                  | Server      | [a12907d76a](https://bsd-hardware.info/?probe=a12907d76a) | Dec 12, 2022 |
| ASRock        | J5040-ITX                   | Desktop     | [7f343df5d5](https://bsd-hardware.info/?probe=7f343df5d5) | Dec 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [809da57d90](https://bsd-hardware.info/?probe=809da57d90) | Dec 11, 2022 |
| Sophos        | XG                          | Firewall    | [e35b3151a3](https://bsd-hardware.info/?probe=e35b3151a3) | Dec 11, 2022 |
| Biostar       | A68N-5600E                  | Desktop     | [5274876096](https://bsd-hardware.info/?probe=5274876096) | Dec 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [fa8afd004f](https://bsd-hardware.info/?probe=fa8afd004f) | Dec 11, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [0be43b76d1](https://bsd-hardware.info/?probe=0be43b76d1) | Dec 11, 2022 |
| MSI           | H81M-P33                    | Desktop     | [1f110891d0](https://bsd-hardware.info/?probe=1f110891d0) | Dec 11, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [028383847e](https://bsd-hardware.info/?probe=028383847e) | Dec 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [99502ebe9a](https://bsd-hardware.info/?probe=99502ebe9a) | Dec 11, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [ad71b00b0d](https://bsd-hardware.info/?probe=ad71b00b0d) | Dec 11, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [d79604d043](https://bsd-hardware.info/?probe=d79604d043) | Dec 11, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [6d10b2a0b4](https://bsd-hardware.info/?probe=6d10b2a0b4) | Dec 11, 2022 |
| HP            | 82B4                        | Desktop     | [c47cb195e0](https://bsd-hardware.info/?probe=c47cb195e0) | Dec 11, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [3124aaaf95](https://bsd-hardware.info/?probe=3124aaaf95) | Dec 11, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [b1bd01549a](https://bsd-hardware.info/?probe=b1bd01549a) | Dec 11, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [4b14039072](https://bsd-hardware.info/?probe=4b14039072) | Dec 11, 2022 |
| Dell          | 03X6X0 A02                  | Server      | [0939871923](https://bsd-hardware.info/?probe=0939871923) | Dec 11, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [808108016d](https://bsd-hardware.info/?probe=808108016d) | Dec 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [def65f518e](https://bsd-hardware.info/?probe=def65f518e) | Dec 10, 2022 |
| Fujitsu       | D3313-S1 S26361-D3313-S1    | Desktop     | [7570f3ae64](https://bsd-hardware.info/?probe=7570f3ae64) | Dec 10, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [d8d6af9e56](https://bsd-hardware.info/?probe=d8d6af9e56) | Dec 10, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [1d8397a653](https://bsd-hardware.info/?probe=1d8397a653) | Dec 10, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [6b64c3dbaf](https://bsd-hardware.info/?probe=6b64c3dbaf) | Dec 10, 2022 |
| HP            | 213D A01                    | Desktop     | [6c83f31e71](https://bsd-hardware.info/?probe=6c83f31e71) | Dec 10, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [0b08951f1c](https://bsd-hardware.info/?probe=0b08951f1c) | Dec 10, 2022 |
| Apple         | MacBook3,1                  | Notebook    | [7aef0a996b](https://bsd-hardware.info/?probe=7aef0a996b) | Dec 10, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [5234a39100](https://bsd-hardware.info/?probe=5234a39100) | Dec 10, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [342c99d07d](https://bsd-hardware.info/?probe=342c99d07d) | Dec 10, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [33395e819a](https://bsd-hardware.info/?probe=33395e819a) | Dec 10, 2022 |
| Supermicro    | X10SLL-F                    | Server      | [7d80c62813](https://bsd-hardware.info/?probe=7d80c62813) | Dec 09, 2022 |
| Dell          | 06X1TJ A00                  | Desktop     | [1115d508c1](https://bsd-hardware.info/?probe=1115d508c1) | Dec 09, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [2048ff5f71](https://bsd-hardware.info/?probe=2048ff5f71) | Dec 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [0405fd0f0d](https://bsd-hardware.info/?probe=0405fd0f0d) | Dec 09, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [c30f53fc6d](https://bsd-hardware.info/?probe=c30f53fc6d) | Dec 09, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [073c2c8de0](https://bsd-hardware.info/?probe=073c2c8de0) | Dec 09, 2022 |
| HP            | 2000                        | Notebook    | [5414b7c943](https://bsd-hardware.info/?probe=5414b7c943) | Dec 09, 2022 |
| Hardkernel    | ODROID-H3                   | Desktop     | [cd6aa62212](https://bsd-hardware.info/?probe=cd6aa62212) | Dec 09, 2022 |
| HP            | 1495                        | Desktop     | [3eab39d89f](https://bsd-hardware.info/?probe=3eab39d89f) | Dec 09, 2022 |
| Sophos        | SG                          | Firewall    | [07fbfad254](https://bsd-hardware.info/?probe=07fbfad254) | Dec 09, 2022 |
| Dell          | 0DRG19 A00                  | Mini pc     | [bbca9fc84f](https://bsd-hardware.info/?probe=bbca9fc84f) | Dec 09, 2022 |
| Sophos        | SG                          | Firewall    | [a3b0edbd3c](https://bsd-hardware.info/?probe=a3b0edbd3c) | Dec 09, 2022 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [10b6c81bce](https://bsd-hardware.info/?probe=10b6c81bce) | Dec 09, 2022 |
| Gigabyte      | H81M-S                      | Desktop     | [094ac0c253](https://bsd-hardware.info/?probe=094ac0c253) | Dec 09, 2022 |
| HP            | 3397                        | Desktop     | [bc9e5c3ab7](https://bsd-hardware.info/?probe=bc9e5c3ab7) | Dec 09, 2022 |
| Protectli     | VP2410 10                   | Desktop     | [3f55143fd9](https://bsd-hardware.info/?probe=3f55143fd9) | Dec 09, 2022 |
| Pegatron      | 2A72h                       | Desktop     | [87e76fd095](https://bsd-hardware.info/?probe=87e76fd095) | Dec 09, 2022 |
| MSI           | B450M BAZOOKA MAX WIFI      | Desktop     | [6b03cb139e](https://bsd-hardware.info/?probe=6b03cb139e) | Dec 09, 2022 |
| Dell          | 05GD68 A00                  | Desktop     | [b2f0da8246](https://bsd-hardware.info/?probe=b2f0da8246) | Dec 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [493df1f529](https://bsd-hardware.info/?probe=493df1f529) | Dec 09, 2022 |
| PC Engines    | apu4                        | Desktop     | [3e3ab7f196](https://bsd-hardware.info/?probe=3e3ab7f196) | Dec 09, 2022 |
| AMI           | PEISIA E3845 VER1.0         | Desktop     | [0ac47aa8a0](https://bsd-hardware.info/?probe=0ac47aa8a0) | Dec 09, 2022 |
| Supermicro    | X10SLL-F                    | Server      | [b2720b8b88](https://bsd-hardware.info/?probe=b2720b8b88) | Dec 08, 2022 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [48d5feacf2](https://bsd-hardware.info/?probe=48d5feacf2) | Dec 08, 2022 |
| Deciso        | NetBoard-A10                | Notebook    | [79b2a5d3a5](https://bsd-hardware.info/?probe=79b2a5d3a5) | Dec 08, 2022 |
| Dell          | 0TY019 A02                  | Server      | [84b683ec0b](https://bsd-hardware.info/?probe=84b683ec0b) | Dec 08, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [84f8198c18](https://bsd-hardware.info/?probe=84f8198c18) | Dec 08, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [dbbdd023e9](https://bsd-hardware.info/?probe=dbbdd023e9) | Dec 08, 2022 |
| Protectli     | FW4C Ver                    | Desktop     | [71368e5cde](https://bsd-hardware.info/?probe=71368e5cde) | Dec 08, 2022 |
| Deciso        | NetBoard-A10                | Notebook    | [575d201794](https://bsd-hardware.info/?probe=575d201794) | Dec 07, 2022 |
| HP            | 245 G6                      | Notebook    | [49ce6aa725](https://bsd-hardware.info/?probe=49ce6aa725) | Dec 07, 2022 |
| ASUSTek       | G11CD                       | Desktop     | [7bc1746333](https://bsd-hardware.info/?probe=7bc1746333) | Dec 07, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [294f283d65](https://bsd-hardware.info/?probe=294f283d65) | Dec 07, 2022 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [9862c1b507](https://bsd-hardware.info/?probe=9862c1b507) | Dec 07, 2022 |
| Lenovo        | 319E SEK0T35577 IOT 4247... | Mini pc     | [33545a5181](https://bsd-hardware.info/?probe=33545a5181) | Dec 07, 2022 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [6db81b5ffe](https://bsd-hardware.info/?probe=6db81b5ffe) | Dec 07, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [c953c78309](https://bsd-hardware.info/?probe=c953c78309) | Dec 07, 2022 |
| Intel         | NUC6CAYB J23203-405         | Mini pc     | [7f6194b56e](https://bsd-hardware.info/?probe=7f6194b56e) | Dec 07, 2022 |
| ASRock        | 4X4-4000 Series             | Desktop     | [8ac499a511](https://bsd-hardware.info/?probe=8ac499a511) | Dec 07, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [a28b2cf6da](https://bsd-hardware.info/?probe=a28b2cf6da) | Dec 07, 2022 |
| HP            | 1495                        | Desktop     | [3f033cb7f5](https://bsd-hardware.info/?probe=3f033cb7f5) | Dec 07, 2022 |
| Sophos        | XG                          | Firewall    | [b29a7eaa33](https://bsd-hardware.info/?probe=b29a7eaa33) | Dec 07, 2022 |
| ASRock        | H110 Pro BTC+               | Desktop     | [7cc4b63834](https://bsd-hardware.info/?probe=7cc4b63834) | Dec 07, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [27dea9bcb5](https://bsd-hardware.info/?probe=27dea9bcb5) | Dec 07, 2022 |
| ASRock        | H110 Pro BTC+               | Desktop     | [f733e29fc8](https://bsd-hardware.info/?probe=f733e29fc8) | Dec 06, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [c33d11ed7b](https://bsd-hardware.info/?probe=c33d11ed7b) | Dec 06, 2022 |
| JGINYUE       | H97I GAMING V1.0            | Desktop     | [f222af4098](https://bsd-hardware.info/?probe=f222af4098) | Dec 06, 2022 |
| Dell          | 0G261D A00                  | Desktop     | [24b9490c77](https://bsd-hardware.info/?probe=24b9490c77) | Dec 06, 2022 |
| Shuttle       | DS10U                       | Desktop     | [0f1e027b35](https://bsd-hardware.info/?probe=0f1e027b35) | Dec 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [78893acbd5](https://bsd-hardware.info/?probe=78893acbd5) | Dec 06, 2022 |
| ASUSTek       | CM1530                      | Desktop     | [902c77b5dc](https://bsd-hardware.info/?probe=902c77b5dc) | Dec 06, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [61347ab3e9](https://bsd-hardware.info/?probe=61347ab3e9) | Dec 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [e3dad11b11](https://bsd-hardware.info/?probe=e3dad11b11) | Dec 06, 2022 |
| HP            | 82A2                        | Desktop     | [c612b7e283](https://bsd-hardware.info/?probe=c612b7e283) | Dec 06, 2022 |
| Supermicro    | X10SLM+-LN4F                | Server      | [319819f81d](https://bsd-hardware.info/?probe=319819f81d) | Dec 06, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [657972a55d](https://bsd-hardware.info/?probe=657972a55d) | Dec 06, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [33f23b1291](https://bsd-hardware.info/?probe=33f23b1291) | Dec 06, 2022 |
| YANYU         | R250                        | Desktop     | [bb364271b2](https://bsd-hardware.info/?probe=bb364271b2) | Dec 05, 2022 |
| DFI           | BE17X(170/171/173)          | Notebook    | [9822160345](https://bsd-hardware.info/?probe=9822160345) | Dec 05, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [eaa3b9783e](https://bsd-hardware.info/?probe=eaa3b9783e) | Dec 05, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [5441995e7b](https://bsd-hardware.info/?probe=5441995e7b) | Dec 05, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [f130844e1e](https://bsd-hardware.info/?probe=f130844e1e) | Dec 05, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [15b2363325](https://bsd-hardware.info/?probe=15b2363325) | Dec 05, 2022 |
| PC Engines    | apu4                        | Desktop     | [72061eb254](https://bsd-hardware.info/?probe=72061eb254) | Dec 05, 2022 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [2fe00838c3](https://bsd-hardware.info/?probe=2fe00838c3) | Dec 05, 2022 |
| ACMA          | X8SIE                       | Desktop     | [361e4ccc04](https://bsd-hardware.info/?probe=361e4ccc04) | Dec 05, 2022 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [71f95dafb4](https://bsd-hardware.info/?probe=71f95dafb4) | Dec 05, 2022 |
| Huanan        | X99-F8D V2.4                | Desktop     | [f6685811a3](https://bsd-hardware.info/?probe=f6685811a3) | Dec 05, 2022 |
| Intel         | NUC6CAYB J23203-405         | Mini pc     | [218e00e7ea](https://bsd-hardware.info/?probe=218e00e7ea) | Dec 05, 2022 |
| Dell          | 0CNWVK A00                  | Desktop     | [5a022db6bf](https://bsd-hardware.info/?probe=5a022db6bf) | Dec 05, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [2c560bad00](https://bsd-hardware.info/?probe=2c560bad00) | Dec 05, 2022 |
| Acer          | Aspire XC-105               | Desktop     | [250b12c3f2](https://bsd-hardware.info/?probe=250b12c3f2) | Dec 05, 2022 |
| Intel         | CARLOW                      | Desktop     | [1b45524779](https://bsd-hardware.info/?probe=1b45524779) | Dec 05, 2022 |
| Supermicro    | X11SDV-4C-TP8F              | Desktop     | [05566134f9](https://bsd-hardware.info/?probe=05566134f9) | Dec 05, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [aa9482884f](https://bsd-hardware.info/?probe=aa9482884f) | Dec 05, 2022 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [90279b62b7](https://bsd-hardware.info/?probe=90279b62b7) | Dec 05, 2022 |
| Google        | Lick                        | Notebook    | [8099b2df21](https://bsd-hardware.info/?probe=8099b2df21) | Dec 04, 2022 |
| Shuttle       | FS77U                       | Desktop     | [4172b79cfc](https://bsd-hardware.info/?probe=4172b79cfc) | Dec 04, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [54d1511b82](https://bsd-hardware.info/?probe=54d1511b82) | Dec 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [54e89ef90b](https://bsd-hardware.info/?probe=54e89ef90b) | Dec 04, 2022 |
| MSI           | B560M-A PRO                 | Desktop     | [be5f6ad306](https://bsd-hardware.info/?probe=be5f6ad306) | Dec 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [af4f0984ae](https://bsd-hardware.info/?probe=af4f0984ae) | Dec 04, 2022 |
| ASUSTek       | E35M1-I DELUXE              | Desktop     | [1a183385c7](https://bsd-hardware.info/?probe=1a183385c7) | Dec 04, 2022 |
| MSI           | H81M-P33                    | Desktop     | [d72a45fb8f](https://bsd-hardware.info/?probe=d72a45fb8f) | Dec 04, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [595d174631](https://bsd-hardware.info/?probe=595d174631) | Dec 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [8ee41750dc](https://bsd-hardware.info/?probe=8ee41750dc) | Dec 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [d9113585f0](https://bsd-hardware.info/?probe=d9113585f0) | Dec 04, 2022 |
| Sophos        | XG                          | Firewall    | [a51c56cb12](https://bsd-hardware.info/?probe=a51c56cb12) | Dec 04, 2022 |
| ShenZhen M... | MW-GMLK-2.5G6L              | Desktop     | [0bdf47ea4c](https://bsd-hardware.info/?probe=0bdf47ea4c) | Dec 04, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [f34b488e42](https://bsd-hardware.info/?probe=f34b488e42) | Dec 04, 2022 |
| Dell          | 0GXM1W A00                  | Desktop     | [9497657cb2](https://bsd-hardware.info/?probe=9497657cb2) | Dec 04, 2022 |
| Google        | Lick                        | Notebook    | [9eb2abcdcc](https://bsd-hardware.info/?probe=9eb2abcdcc) | Dec 03, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [94f78cb509](https://bsd-hardware.info/?probe=94f78cb509) | Dec 03, 2022 |
| Google        | Lars                        | Notebook    | [4130b19cfa](https://bsd-hardware.info/?probe=4130b19cfa) | Dec 03, 2022 |
| Lenovo        | ThinkPad X250 20CLS5BU00    | Notebook    | [10619ac217](https://bsd-hardware.info/?probe=10619ac217) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [aeb690b9f3](https://bsd-hardware.info/?probe=aeb690b9f3) | Dec 03, 2022 |
| Dell          | 0PTTT9 A01                  | Desktop     | [1916a4064b](https://bsd-hardware.info/?probe=1916a4064b) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [d4e60c5984](https://bsd-hardware.info/?probe=d4e60c5984) | Dec 03, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [ddeb9befdf](https://bsd-hardware.info/?probe=ddeb9befdf) | Dec 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [90de1777bc](https://bsd-hardware.info/?probe=90de1777bc) | Dec 02, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [f6c721906b](https://bsd-hardware.info/?probe=f6c721906b) | Dec 02, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [5e75bcdb11](https://bsd-hardware.info/?probe=5e75bcdb11) | Dec 02, 2022 |
| Deciso        | Netboard A10 V2.1           | Desktop     | [40a0d948b4](https://bsd-hardware.info/?probe=40a0d948b4) | Dec 02, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [f8719b2320](https://bsd-hardware.info/?probe=f8719b2320) | Dec 02, 2022 |
| Dell          | 0KYJ8C A02                  | Desktop     | [c0c4fa9349](https://bsd-hardware.info/?probe=c0c4fa9349) | Dec 02, 2022 |
| HASEE Comp... | N95XKP6                     | Notebook    | [0bc2996a6d](https://bsd-hardware.info/?probe=0bc2996a6d) | Dec 02, 2022 |
| ASUSTek       | PRIME H310T2 R2.0           | All in one  | [d1cc7c07e0](https://bsd-hardware.info/?probe=d1cc7c07e0) | Dec 02, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [5c3941eb3f](https://bsd-hardware.info/?probe=5c3941eb3f) | Dec 02, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [d3b72fdce8](https://bsd-hardware.info/?probe=d3b72fdce8) | Dec 02, 2022 |
| Dell          | Latitude 5590               | Notebook    | [0a17f04eba](https://bsd-hardware.info/?probe=0a17f04eba) | Dec 02, 2022 |
| Intel         | D33217CK G76541-300         | Desktop     | [545a39b1e4](https://bsd-hardware.info/?probe=545a39b1e4) | Dec 02, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [4bf1aae972](https://bsd-hardware.info/?probe=4bf1aae972) | Dec 02, 2022 |
| Intel         | X99                         | Desktop     | [c21a466fc1](https://bsd-hardware.info/?probe=c21a466fc1) | Dec 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [243e309a04](https://bsd-hardware.info/?probe=243e309a04) | Dec 01, 2022 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [03708406e8](https://bsd-hardware.info/?probe=03708406e8) | Dec 01, 2022 |
| HP            | 8054                        | Desktop     | [c25adeb2ff](https://bsd-hardware.info/?probe=c25adeb2ff) | Dec 01, 2022 |
| Thomas-Kre... | P9A-I/2550/4L               | Firewall    | [6bec1ec37d](https://bsd-hardware.info/?probe=6bec1ec37d) | Dec 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [32a4df9cae](https://bsd-hardware.info/?probe=32a4df9cae) | Dec 01, 2022 |
| Intel         | NUC11ATBC4 M53051-400       | Mini pc     | [6fe2ba74b7](https://bsd-hardware.info/?probe=6fe2ba74b7) | Dec 01, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [a7c2e16f5c](https://bsd-hardware.info/?probe=a7c2e16f5c) | Dec 01, 2022 |
| Panasonic     | CF-54-1                     | Notebook    | [0c5820ea0d](https://bsd-hardware.info/?probe=0c5820ea0d) | Dec 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [504a659236](https://bsd-hardware.info/?probe=504a659236) | Dec 01, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [529cbab9aa](https://bsd-hardware.info/?probe=529cbab9aa) | Dec 01, 2022 |
| Acidanther... | MacBookPro15,1              | Notebook    | [57c3a4005a](https://bsd-hardware.info/?probe=57c3a4005a) | Dec 01, 2022 |
| MSI           | Z87I                        | Desktop     | [570046969c](https://bsd-hardware.info/?probe=570046969c) | Dec 01, 2022 |
| HP            | 8103 A01                    | Mini pc     | [5cd982c2ee](https://bsd-hardware.info/?probe=5cd982c2ee) | Nov 30, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [84d1656c05](https://bsd-hardware.info/?probe=84d1656c05) | Nov 30, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [6a1a5865cb](https://bsd-hardware.info/?probe=6a1a5865cb) | Nov 30, 2022 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [087264570d](https://bsd-hardware.info/?probe=087264570d) | Nov 30, 2022 |
| PC Engines    | apu4                        | Desktop     | [7c8b9014b1](https://bsd-hardware.info/?probe=7c8b9014b1) | Nov 30, 2022 |
| PC Engines    | apu4                        | Desktop     | [dd39e91713](https://bsd-hardware.info/?probe=dd39e91713) | Nov 30, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [794e041b13](https://bsd-hardware.info/?probe=794e041b13) | Nov 30, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [920a2fe2e9](https://bsd-hardware.info/?probe=920a2fe2e9) | Nov 30, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [ac4f4b181a](https://bsd-hardware.info/?probe=ac4f4b181a) | Nov 30, 2022 |
| Panasonic     | CF-31-5                     | Notebook    | [7047afaaf4](https://bsd-hardware.info/?probe=7047afaaf4) | Nov 30, 2022 |
| Protectli     | FW6                         | Desktop     | [95f3201109](https://bsd-hardware.info/?probe=95f3201109) | Nov 30, 2022 |
| GPD           | P3 MAX                      | Notebook    | [4a467c9616](https://bsd-hardware.info/?probe=4a467c9616) | Nov 30, 2022 |
| Protectli     | FW4A Ver                    | Desktop     | [9e6e0f5548](https://bsd-hardware.info/?probe=9e6e0f5548) | Nov 30, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [3dd9e3557c](https://bsd-hardware.info/?probe=3dd9e3557c) | Nov 30, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [f3b09cfb70](https://bsd-hardware.info/?probe=f3b09cfb70) | Nov 30, 2022 |
| Intel         | D33217CK G76541-300         | Desktop     | [bbdd9a1b98](https://bsd-hardware.info/?probe=bbdd9a1b98) | Nov 30, 2022 |
| Sophos        | SG                          | Firewall    | [357c380b7c](https://bsd-hardware.info/?probe=357c380b7c) | Nov 29, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [1d61d0cf62](https://bsd-hardware.info/?probe=1d61d0cf62) | Nov 29, 2022 |
| ASRockRack    | X470D4U                     | Desktop     | [38d7f55ef7](https://bsd-hardware.info/?probe=38d7f55ef7) | Nov 29, 2022 |
| Lenovo        | ThinkPad T430 2347G7G       | Notebook    | [640540cd67](https://bsd-hardware.info/?probe=640540cd67) | Nov 29, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [cfaeaeb2f2](https://bsd-hardware.info/?probe=cfaeaeb2f2) | Nov 29, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [929e4bda1e](https://bsd-hardware.info/?probe=929e4bda1e) | Nov 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [a5b10d3f79](https://bsd-hardware.info/?probe=a5b10d3f79) | Nov 29, 2022 |
| ACMA          | X8SIE                       | Desktop     | [532b81e55f](https://bsd-hardware.info/?probe=532b81e55f) | Nov 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [7308d658dc](https://bsd-hardware.info/?probe=7308d658dc) | Nov 29, 2022 |
| ZOTAC         | ZBOX-CI341                  | Mini pc     | [2299087d09](https://bsd-hardware.info/?probe=2299087d09) | Nov 29, 2022 |
| Unknown       | A04                         | Server      | [07f21afacc](https://bsd-hardware.info/?probe=07f21afacc) | Nov 29, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [9618eb0cbe](https://bsd-hardware.info/?probe=9618eb0cbe) | Nov 29, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [7c9ee800c5](https://bsd-hardware.info/?probe=7c9ee800c5) | Nov 29, 2022 |
| Lenovo        | 316A SDK0J40697 WIN 3305... | Mini pc     | [26c9557a0a](https://bsd-hardware.info/?probe=26c9557a0a) | Nov 29, 2022 |
| HP            | 8299                        | Desktop     | [d697a2e953](https://bsd-hardware.info/?probe=d697a2e953) | Nov 29, 2022 |
| Acer          | TravelMate B115-M           | Notebook    | [13e318fec2](https://bsd-hardware.info/?probe=13e318fec2) | Nov 29, 2022 |
| ACMA          | X8SIE                       | Desktop     | [d0112d027b](https://bsd-hardware.info/?probe=d0112d027b) | Nov 28, 2022 |
| QIYIDA        | X99-H9 V2.0                 | Desktop     | [43163b0170](https://bsd-hardware.info/?probe=43163b0170) | Nov 28, 2022 |
| QIYIDA        | X99-H9 V2.0                 | Desktop     | [d00aa0021e](https://bsd-hardware.info/?probe=d00aa0021e) | Nov 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [4e40278b06](https://bsd-hardware.info/?probe=4e40278b06) | Nov 28, 2022 |
| Lenovo        | ThinkPad T460 20FMS0XL23    | Notebook    | [bc7585ec56](https://bsd-hardware.info/?probe=bc7585ec56) | Nov 28, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [28dd3a0b1b](https://bsd-hardware.info/?probe=28dd3a0b1b) | Nov 28, 2022 |
| Deciso        | Netboard A10 GEN2 Model ... | Desktop     | [d48dbd053d](https://bsd-hardware.info/?probe=d48dbd053d) | Nov 28, 2022 |
| PC Engines    | apu4                        | Desktop     | [588e065800](https://bsd-hardware.info/?probe=588e065800) | Nov 28, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [e850e0ae9c](https://bsd-hardware.info/?probe=e850e0ae9c) | Nov 28, 2022 |
| Toshiba       | TECRA Z40-C-12Z             | Notebook    | [149e5c3de3](https://bsd-hardware.info/?probe=149e5c3de3) | Nov 28, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [35950045c6](https://bsd-hardware.info/?probe=35950045c6) | Nov 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [2fe35064cb](https://bsd-hardware.info/?probe=2fe35064cb) | Nov 28, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [b1f32ca8a1](https://bsd-hardware.info/?probe=b1f32ca8a1) | Nov 28, 2022 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [378270eba0](https://bsd-hardware.info/?probe=378270eba0) | Nov 28, 2022 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | Desktop     | [b4cc780c40](https://bsd-hardware.info/?probe=b4cc780c40) | Nov 28, 2022 |
| Shuttle       | FS81                        | Desktop     | [f714ba647f](https://bsd-hardware.info/?probe=f714ba647f) | Nov 28, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [fd111870fa](https://bsd-hardware.info/?probe=fd111870fa) | Nov 28, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [ae55a799e8](https://bsd-hardware.info/?probe=ae55a799e8) | Nov 28, 2022 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [7329e04c22](https://bsd-hardware.info/?probe=7329e04c22) | Nov 27, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [3541df7dd2](https://bsd-hardware.info/?probe=3541df7dd2) | Nov 27, 2022 |
| PC Engines    | apu6                        | Desktop     | [13dcbe5748](https://bsd-hardware.info/?probe=13dcbe5748) | Nov 27, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [39ece5deaf](https://bsd-hardware.info/?probe=39ece5deaf) | Nov 27, 2022 |
| YANYU         | R250                        | Desktop     | [0be0925e5b](https://bsd-hardware.info/?probe=0be0925e5b) | Nov 27, 2022 |
| ASRock        | X570 Pro4                   | Desktop     | [b23f59a068](https://bsd-hardware.info/?probe=b23f59a068) | Nov 27, 2022 |
| Dell          | 09M8Y8 A02                  | Desktop     | [2299b7c270](https://bsd-hardware.info/?probe=2299b7c270) | Nov 27, 2022 |
| MSI           | H81M-P33                    | Desktop     | [597d48d1c9](https://bsd-hardware.info/?probe=597d48d1c9) | Nov 27, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [10d76fd431](https://bsd-hardware.info/?probe=10d76fd431) | Nov 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [383341b2f1](https://bsd-hardware.info/?probe=383341b2f1) | Nov 27, 2022 |
| Acer          | Revo RN86                   | Desktop     | [a4dcb7f7a2](https://bsd-hardware.info/?probe=a4dcb7f7a2) | Nov 27, 2022 |
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
| ASRock        | N68-S                       | Desktop     | [3813c8856e](https://bsd-hardware.info/?probe=3813c8856e) | Nov 27, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [e8e158f783](https://bsd-hardware.info/?probe=e8e158f783) | Nov 27, 2022 |
| Supermicro    | X10SRG-F                    | Desktop     | [66b7819b2a](https://bsd-hardware.info/?probe=66b7819b2a) | Nov 27, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [10bece0518](https://bsd-hardware.info/?probe=10bece0518) | Nov 27, 2022 |
| Unknown       | Unknown                     | Desktop     | [512a05eefb](https://bsd-hardware.info/?probe=512a05eefb) | Nov 27, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [ed6b1f75ae](https://bsd-hardware.info/?probe=ed6b1f75ae) | Nov 27, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [5f0b8df8d0](https://bsd-hardware.info/?probe=5f0b8df8d0) | Nov 27, 2022 |
| ASRock        | J4125B-ITX                  | Desktop     | [ad497a63ac](https://bsd-hardware.info/?probe=ad497a63ac) | Nov 27, 2022 |
| HP            | 18E7                        | Desktop     | [c7635c715f](https://bsd-hardware.info/?probe=c7635c715f) | Nov 26, 2022 |
| Intel         | DH87MC AAG74242-401         | Desktop     | [33c1878560](https://bsd-hardware.info/?probe=33c1878560) | Nov 26, 2022 |
| ASUSTek       | P11C-X Series               | Desktop     | [6860cd72f8](https://bsd-hardware.info/?probe=6860cd72f8) | Nov 26, 2022 |
| ASUSTek       | P11C-X Series               | Desktop     | [cfdb06e761](https://bsd-hardware.info/?probe=cfdb06e761) | Nov 26, 2022 |
| CompuLab      | fit-PC3                     | Mini pc     | [34dd85f78d](https://bsd-hardware.info/?probe=34dd85f78d) | Nov 26, 2022 |
| ASUSTek       | P5K-E                       | Desktop     | [2b00248458](https://bsd-hardware.info/?probe=2b00248458) | Nov 26, 2022 |
| Intel         | CRESCENTBAY                 | Desktop     | [bd1f1fa769](https://bsd-hardware.info/?probe=bd1f1fa769) | Nov 26, 2022 |
| CompuLab      | fit-PC3                     | Mini pc     | [54a64a269c](https://bsd-hardware.info/?probe=54a64a269c) | Nov 26, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [3ad7cec298](https://bsd-hardware.info/?probe=3ad7cec298) | Nov 26, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [7c9df6da87](https://bsd-hardware.info/?probe=7c9df6da87) | Nov 26, 2022 |
| Acer          | Aspire 5738                 | Notebook    | [067e8e4d58](https://bsd-hardware.info/?probe=067e8e4d58) | Nov 26, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [b87ed70877](https://bsd-hardware.info/?probe=b87ed70877) | Nov 26, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [7f9869324b](https://bsd-hardware.info/?probe=7f9869324b) | Nov 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [222e69ff59](https://bsd-hardware.info/?probe=222e69ff59) | Nov 26, 2022 |
| Dell          | 0M017G A00                  | Desktop     | [3acaad9a7d](https://bsd-hardware.info/?probe=3acaad9a7d) | Nov 26, 2022 |
| HP            | ProLiant DL360p Gen8        | Server      | [a5514d3f4b](https://bsd-hardware.info/?probe=a5514d3f4b) | Nov 26, 2022 |
| Sophos        | SG                          | Firewall    | [d0fc510660](https://bsd-hardware.info/?probe=d0fc510660) | Nov 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [6de307244e](https://bsd-hardware.info/?probe=6de307244e) | Nov 26, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [787a2db2cd](https://bsd-hardware.info/?probe=787a2db2cd) | Nov 26, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [88929a3594](https://bsd-hardware.info/?probe=88929a3594) | Nov 25, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [ef6190861c](https://bsd-hardware.info/?probe=ef6190861c) | Nov 25, 2022 |
| Protectli     | FW6                         | Desktop     | [74510f3177](https://bsd-hardware.info/?probe=74510f3177) | Nov 25, 2022 |
| Lenovo        | ThinkPad T430 23446FP       | Notebook    | [6c2ef140be](https://bsd-hardware.info/?probe=6c2ef140be) | Nov 25, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [76ecd68ff6](https://bsd-hardware.info/?probe=76ecd68ff6) | Nov 25, 2022 |
| Protectli     | FW2B Ver                    | Desktop     | [e03929e52f](https://bsd-hardware.info/?probe=e03929e52f) | Nov 25, 2022 |
| Dell          | 0F0XJ6 A13                  | Server      | [1d71d3c9e7](https://bsd-hardware.info/?probe=1d71d3c9e7) | Nov 25, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [317231bad8](https://bsd-hardware.info/?probe=317231bad8) | Nov 25, 2022 |
| Supermicro    | M11SDV-8C+-LN4F             | Server      | [bcf17b19ec](https://bsd-hardware.info/?probe=bcf17b19ec) | Nov 25, 2022 |
| HP            | 3048h                       | Desktop     | [3f43816a5d](https://bsd-hardware.info/?probe=3f43816a5d) | Nov 25, 2022 |
| Lenovo        | ThinkStation S30 0569A93    | Desktop     | [dd545fb588](https://bsd-hardware.info/?probe=dd545fb588) | Nov 25, 2022 |
| Dell          | 0PTTT9 A01                  | Desktop     | [74575d6dfe](https://bsd-hardware.info/?probe=74575d6dfe) | Nov 25, 2022 |
| Pegatron      | IPM41-D3                    | Desktop     | [898f645e32](https://bsd-hardware.info/?probe=898f645e32) | Nov 25, 2022 |
| Supermicro    | M11SDV-4CT-LN4F             | Server      | [dc8015adc3](https://bsd-hardware.info/?probe=dc8015adc3) | Nov 25, 2022 |
| Dell          | Vostro 3501                 | Notebook    | [61f8a35700](https://bsd-hardware.info/?probe=61f8a35700) | Nov 25, 2022 |
| ASRock        | H510M-HDV                   | Desktop     | [d2029ae805](https://bsd-hardware.info/?probe=d2029ae805) | Nov 25, 2022 |
| Dell          | 0F0XJ6 A13                  | Server      | [1fb28aaef2](https://bsd-hardware.info/?probe=1fb28aaef2) | Nov 25, 2022 |
| Unknown       | Unknown                     | Desktop     | [1d3bd58d18](https://bsd-hardware.info/?probe=1d3bd58d18) | Nov 25, 2022 |
| Lenovo        | 1106A14 ThinkServer TS13... | Desktop     | [28aca8c985](https://bsd-hardware.info/?probe=28aca8c985) | Nov 25, 2022 |
| Gigabyte      | G31M-ES2C                   | Desktop     | [2959091a59](https://bsd-hardware.info/?probe=2959091a59) | Nov 25, 2022 |
| Dell          | 0HFG24 A01                  | Server      | [ca48ff12d3](https://bsd-hardware.info/?probe=ca48ff12d3) | Nov 25, 2022 |
| MSI           | Z170A GAMING M5             | Desktop     | [5740972ddc](https://bsd-hardware.info/?probe=5740972ddc) | Nov 25, 2022 |
| HP            | 8055                        | Desktop     | [ace4570d15](https://bsd-hardware.info/?probe=ace4570d15) | Nov 25, 2022 |
| HP            | ProLiant DL360p Gen8        | Server      | [7bb8186465](https://bsd-hardware.info/?probe=7bb8186465) | Nov 25, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [de7f2ee053](https://bsd-hardware.info/?probe=de7f2ee053) | Nov 25, 2022 |
| Sony          | SVP1321V9RB                 | Notebook    | [932facd689](https://bsd-hardware.info/?probe=932facd689) | Nov 25, 2022 |
| Dell          | 009Y81 A01                  | All in one  | [75132e6886](https://bsd-hardware.info/?probe=75132e6886) | Nov 25, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [7258992b77](https://bsd-hardware.info/?probe=7258992b77) | Nov 24, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [4a8efeb7a6](https://bsd-hardware.info/?probe=4a8efeb7a6) | Nov 24, 2022 |
| Dell          | Latitude D610               | Notebook    | [6ef8d8137b](https://bsd-hardware.info/?probe=6ef8d8137b) | Nov 24, 2022 |
| HP            | ProLiant DL360 G5           | Server      | [4a44193c5f](https://bsd-hardware.info/?probe=4a44193c5f) | Nov 24, 2022 |
| Deciso        | OPNsense Appliance          | Notebook    | [0bbf4f46e7](https://bsd-hardware.info/?probe=0bbf4f46e7) | Nov 24, 2022 |
| Dell          | 0W13NR A07                  | Server      | [c5b09b219b](https://bsd-hardware.info/?probe=c5b09b219b) | Nov 24, 2022 |
| ASRock        | B450M-HDV                   | Desktop     | [d0009172b1](https://bsd-hardware.info/?probe=d0009172b1) | Nov 24, 2022 |
| ASRock        | B450M-HDV                   | Desktop     | [25cc0129d9](https://bsd-hardware.info/?probe=25cc0129d9) | Nov 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [d4246caa0f](https://bsd-hardware.info/?probe=d4246caa0f) | Nov 24, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [6fa29c4e4d](https://bsd-hardware.info/?probe=6fa29c4e4d) | Nov 24, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [45d96a0b5a](https://bsd-hardware.info/?probe=45d96a0b5a) | Nov 24, 2022 |
| Deciso        | OPNsense Appliance          | Notebook    | [75a7bf9b27](https://bsd-hardware.info/?probe=75a7bf9b27) | Nov 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [5aa1f0193a](https://bsd-hardware.info/?probe=5aa1f0193a) | Nov 24, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3c11fc31b2](https://bsd-hardware.info/?probe=3c11fc31b2) | Nov 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [c5562e1851](https://bsd-hardware.info/?probe=c5562e1851) | Nov 24, 2022 |
| MSI           | A320M-A PRO                 | Desktop     | [fc71b97d90](https://bsd-hardware.info/?probe=fc71b97d90) | Nov 24, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [b6bbaa13e8](https://bsd-hardware.info/?probe=b6bbaa13e8) | Nov 24, 2022 |
| Dell          | 07F37C A01                  | Desktop     | [08d048da80](https://bsd-hardware.info/?probe=08d048da80) | Nov 24, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [e32a104392](https://bsd-hardware.info/?probe=e32a104392) | Nov 24, 2022 |
| ASRock Ind... | NUC-1240P                   | Desktop     | [75547bc09a](https://bsd-hardware.info/?probe=75547bc09a) | Nov 24, 2022 |
| Gigabyte      | E2500N                      | Desktop     | [64b937b551](https://bsd-hardware.info/?probe=64b937b551) | Nov 23, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [aa3c44499f](https://bsd-hardware.info/?probe=aa3c44499f) | Nov 23, 2022 |
| Gigabyte      | G31M-S2L                    | Desktop     | [d376385d80](https://bsd-hardware.info/?probe=d376385d80) | Nov 23, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [a4d92a3b73](https://bsd-hardware.info/?probe=a4d92a3b73) | Nov 23, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [1b6870d481](https://bsd-hardware.info/?probe=1b6870d481) | Nov 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [77e932dd9e](https://bsd-hardware.info/?probe=77e932dd9e) | Nov 23, 2022 |
| IceWhale T... | ZimaBoard 216 ZMB           | Desktop     | [b75d6c6581](https://bsd-hardware.info/?probe=b75d6c6581) | Nov 23, 2022 |
| Dell          | 06D7TR A00                  | Desktop     | [7fabc0cb8a](https://bsd-hardware.info/?probe=7fabc0cb8a) | Nov 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [337d5f0f4b](https://bsd-hardware.info/?probe=337d5f0f4b) | Nov 23, 2022 |
| ZOTAC         | ZBOX-CI622/CI642/CI662NA... | Mini pc     | [4c3be7ec24](https://bsd-hardware.info/?probe=4c3be7ec24) | Nov 23, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [1860d18e39](https://bsd-hardware.info/?probe=1860d18e39) | Nov 23, 2022 |
| Protectli     | FW4B                        | Desktop     | [d3090c9e8e](https://bsd-hardware.info/?probe=d3090c9e8e) | Nov 23, 2022 |
| Apple         | Mac-F2208EC8                | Mini pc     | [0ed70ba3c3](https://bsd-hardware.info/?probe=0ed70ba3c3) | Nov 23, 2022 |
| Infoblox      | IB-1410                     | Desktop     | [7521108ef5](https://bsd-hardware.info/?probe=7521108ef5) | Nov 23, 2022 |
| ASUSTek       | A55BM-K                     | Desktop     | [dc487b5779](https://bsd-hardware.info/?probe=dc487b5779) | Nov 23, 2022 |
| HP            | 3396                        | Desktop     | [dc94cbde1a](https://bsd-hardware.info/?probe=dc94cbde1a) | Nov 23, 2022 |
| PC Engines    | apu6                        | Desktop     | [bc334caa03](https://bsd-hardware.info/?probe=bc334caa03) | Nov 23, 2022 |
| PC Engines    | APU2                        | Desktop     | [4d33b6da51](https://bsd-hardware.info/?probe=4d33b6da51) | Nov 23, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [9701222998](https://bsd-hardware.info/?probe=9701222998) | Nov 23, 2022 |
| Sophos        | UTM                         | Firewall    | [1c0805f9ae](https://bsd-hardware.info/?probe=1c0805f9ae) | Nov 23, 2022 |
| Dell          | XPS 13 9343                 | Notebook    | [8ec61db3f0](https://bsd-hardware.info/?probe=8ec61db3f0) | Nov 22, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [d4791d1dfc](https://bsd-hardware.info/?probe=d4791d1dfc) | Nov 22, 2022 |
| Dell          | 0TW855 A07                  | Server      | [d2d859c434](https://bsd-hardware.info/?probe=d2d859c434) | Nov 22, 2022 |
| Intel         | H61                         | Desktop     | [689ebf0e57](https://bsd-hardware.info/?probe=689ebf0e57) | Nov 22, 2022 |
| Dell          | 0MD99X A05                  | Server      | [8adc53c921](https://bsd-hardware.info/?probe=8adc53c921) | Nov 22, 2022 |
| HP            | ProLiant DL360 G7           | Server      | [b666129e73](https://bsd-hardware.info/?probe=b666129e73) | Nov 22, 2022 |
| Datto         | SSD                         | Desktop     | [08d401fa34](https://bsd-hardware.info/?probe=08d401fa34) | Nov 22, 2022 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [2f812bd8c3](https://bsd-hardware.info/?probe=2f812bd8c3) | Nov 22, 2022 |
| Gigabyte      | H81M-HD3                    | Desktop     | [564cf3d66a](https://bsd-hardware.info/?probe=564cf3d66a) | Nov 22, 2022 |
| Dell          | Edge Gateway 5000           | Mini pc     | [18f8f8f8b5](https://bsd-hardware.info/?probe=18f8f8f8b5) | Nov 22, 2022 |
| Unknown       | Unknown                     | Desktop     | [fdffbdb940](https://bsd-hardware.info/?probe=fdffbdb940) | Nov 22, 2022 |
| Apple         | PowerMac10,1                | Desktop     | [0760ed34c3](https://bsd-hardware.info/?probe=0760ed34c3) | Nov 21, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [7742fc7455](https://bsd-hardware.info/?probe=7742fc7455) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d893e02d90](https://bsd-hardware.info/?probe=d893e02d90) | Nov 21, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [77fa42b66c](https://bsd-hardware.info/?probe=77fa42b66c) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [7518e4f06a](https://bsd-hardware.info/?probe=7518e4f06a) | Nov 21, 2022 |
| Gigabyte      | P61-USB3-B3                 | Desktop     | [1ec1683acd](https://bsd-hardware.info/?probe=1ec1683acd) | Nov 21, 2022 |
| Gigabyte      | P61-USB3-B3                 | Desktop     | [5f442f0c65](https://bsd-hardware.info/?probe=5f442f0c65) | Nov 21, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [2b851dbbc1](https://bsd-hardware.info/?probe=2b851dbbc1) | Nov 21, 2022 |
| Gigabyte      | Z590I AORUS ULTRA           | Desktop     | [e55eb53894](https://bsd-hardware.info/?probe=e55eb53894) | Nov 21, 2022 |
| ASUSTek       | ZenBook UX434FL_UX434FL     | Notebook    | [56bc3b04fd](https://bsd-hardware.info/?probe=56bc3b04fd) | Nov 21, 2022 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Mini pc     | [e0f08b66c2](https://bsd-hardware.info/?probe=e0f08b66c2) | Nov 21, 2022 |
| Lenovo        | ThinkPad X230 2325T4T       | Notebook    | [f0cc17c7eb](https://bsd-hardware.info/?probe=f0cc17c7eb) | Nov 21, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [f7129f1c87](https://bsd-hardware.info/?probe=f7129f1c87) | Nov 21, 2022 |
| Gigabyte      | 970A-D3P                    | Desktop     | [cced487ec5](https://bsd-hardware.info/?probe=cced487ec5) | Nov 21, 2022 |
| Gigabyte      | 970A-D3P                    | Desktop     | [c28a22ecb5](https://bsd-hardware.info/?probe=c28a22ecb5) | Nov 21, 2022 |
| ASUSTek       | P5KPL-VM-TWPC               | Desktop     | [6a5ff282a7](https://bsd-hardware.info/?probe=6a5ff282a7) | Nov 21, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [17aa370584](https://bsd-hardware.info/?probe=17aa370584) | Nov 21, 2022 |
| Supermicro    | M11SDV-4CT-LN4F             | Server      | [2d8d0056c4](https://bsd-hardware.info/?probe=2d8d0056c4) | Nov 21, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [298fde4e33](https://bsd-hardware.info/?probe=298fde4e33) | Nov 21, 2022 |
| Unknown       | SKYBAY                      | Desktop     | [5030575f0a](https://bsd-hardware.info/?probe=5030575f0a) | Nov 20, 2022 |
| HP            | ProLiant DL380 G6           | Server      | [3e3b056cdf](https://bsd-hardware.info/?probe=3e3b056cdf) | Nov 20, 2022 |
| HP            | ProBook 4540s               | Notebook    | [6dce896f40](https://bsd-hardware.info/?probe=6dce896f40) | Nov 20, 2022 |
| Sophos        | XG                          | Firewall    | [3868856b34](https://bsd-hardware.info/?probe=3868856b34) | Nov 20, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [8257d11669](https://bsd-hardware.info/?probe=8257d11669) | Nov 20, 2022 |
| Dell          | 07F37C A01                  | Desktop     | [efb5c9d03d](https://bsd-hardware.info/?probe=efb5c9d03d) | Nov 20, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [98684b1d19](https://bsd-hardware.info/?probe=98684b1d19) | Nov 20, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [f6491f1950](https://bsd-hardware.info/?probe=f6491f1950) | Nov 20, 2022 |
| OEM           | 1.0                         | Desktop     | [a821818533](https://bsd-hardware.info/?probe=a821818533) | Nov 20, 2022 |
| MSI           | H81M-P33                    | Desktop     | [d3303d1962](https://bsd-hardware.info/?probe=d3303d1962) | Nov 20, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [b1512a254c](https://bsd-hardware.info/?probe=b1512a254c) | Nov 20, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [521e5ffa8e](https://bsd-hardware.info/?probe=521e5ffa8e) | Nov 20, 2022 |
| HP            | 8054                        | Desktop     | [2c1e20c9e7](https://bsd-hardware.info/?probe=2c1e20c9e7) | Nov 20, 2022 |
| Dell          | 0TW855 A07                  | Server      | [dbeaf80924](https://bsd-hardware.info/?probe=dbeaf80924) | Nov 20, 2022 |
| Hardkernel    | ODROID-H3                   | Desktop     | [ec7611edd1](https://bsd-hardware.info/?probe=ec7611edd1) | Nov 20, 2022 |
| Dell          | 0YNVJG A01                  | Desktop     | [15d32e1e36](https://bsd-hardware.info/?probe=15d32e1e36) | Nov 20, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [29210f2239](https://bsd-hardware.info/?probe=29210f2239) | Nov 20, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [c226ac3d9b](https://bsd-hardware.info/?probe=c226ac3d9b) | Nov 20, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [5d3ccb6891](https://bsd-hardware.info/?probe=5d3ccb6891) | Nov 20, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [449dcd1463](https://bsd-hardware.info/?probe=449dcd1463) | Nov 19, 2022 |
| Dell          | 09D2HH A00                  | Desktop     | [794fe8eb65](https://bsd-hardware.info/?probe=794fe8eb65) | Nov 19, 2022 |
| Deciso        | NetBoard-A10                | Notebook    | [20058331ef](https://bsd-hardware.info/?probe=20058331ef) | Nov 19, 2022 |
| Supermicro    | A2SDi-4C-HLN4F              | Server      | [bf83fc6cdb](https://bsd-hardware.info/?probe=bf83fc6cdb) | Nov 19, 2022 |
| TOPFEEL       | H110D4-P1                   | Desktop     | [90b1dfc430](https://bsd-hardware.info/?probe=90b1dfc430) | Nov 19, 2022 |
| Supermicro    | X11SDV-4C-TP8F              | Desktop     | [402a623ed0](https://bsd-hardware.info/?probe=402a623ed0) | Nov 19, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [92eab8d065](https://bsd-hardware.info/?probe=92eab8d065) | Nov 19, 2022 |
| Foxconn       | H67S/H61SP                  | Desktop     | [80ad331089](https://bsd-hardware.info/?probe=80ad331089) | Nov 19, 2022 |
| ZOTAC         | ZBOX-CI327NANO-GS-01        | Mini pc     | [7bfffa2718](https://bsd-hardware.info/?probe=7bfffa2718) | Nov 19, 2022 |
| Dell          | 060J9C A00                  | Mini pc     | [efcae22b58](https://bsd-hardware.info/?probe=efcae22b58) | Nov 19, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [18062e5bd5](https://bsd-hardware.info/?probe=18062e5bd5) | Nov 19, 2022 |
| Dell          | 0KYJ8C A02                  | Desktop     | [7282ce8fe2](https://bsd-hardware.info/?probe=7282ce8fe2) | Nov 19, 2022 |
| Dell          | 0GN4PW A00                  | Desktop     | [9127ec4dac](https://bsd-hardware.info/?probe=9127ec4dac) | Nov 19, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [d3cbc9d6ca](https://bsd-hardware.info/?probe=d3cbc9d6ca) | Nov 19, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [2eba32390f](https://bsd-hardware.info/?probe=2eba32390f) | Nov 19, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [eaf4ec693e](https://bsd-hardware.info/?probe=eaf4ec693e) | Nov 19, 2022 |
| PC Engines    | apu6                        | Desktop     | [1e9acc3ae6](https://bsd-hardware.info/?probe=1e9acc3ae6) | Nov 18, 2022 |
| Huanan        | X99-F8D V2.4                | Desktop     | [9faf79b3f3](https://bsd-hardware.info/?probe=9faf79b3f3) | Nov 18, 2022 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [f25480c54a](https://bsd-hardware.info/?probe=f25480c54a) | Nov 18, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [5537746c27](https://bsd-hardware.info/?probe=5537746c27) | Nov 18, 2022 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [7c7a121711](https://bsd-hardware.info/?probe=7c7a121711) | Nov 18, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [7691355396](https://bsd-hardware.info/?probe=7691355396) | Nov 18, 2022 |
| Dell          | Latitude D630               | Notebook    | [1c600cc283](https://bsd-hardware.info/?probe=1c600cc283) | Nov 18, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [5875ecec9f](https://bsd-hardware.info/?probe=5875ecec9f) | Nov 18, 2022 |
| HP            | 82FE 11                     | Desktop     | [547e5e3ce1](https://bsd-hardware.info/?probe=547e5e3ce1) | Nov 18, 2022 |
| Foxconn       | 2AB1                        | Desktop     | [f732942dd9](https://bsd-hardware.info/?probe=f732942dd9) | Nov 18, 2022 |
| Fujitsu       | D3289-A1 S26361-D3289-A1... | Desktop     | [dae7027898](https://bsd-hardware.info/?probe=dae7027898) | Nov 18, 2022 |
| Dell          | 051FJ8 A02                  | Desktop     | [296b446a8f](https://bsd-hardware.info/?probe=296b446a8f) | Nov 18, 2022 |
| ASRock        | N3150M                      | Desktop     | [d3b3be7936](https://bsd-hardware.info/?probe=d3b3be7936) | Nov 17, 2022 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [f1f56fe86c](https://bsd-hardware.info/?probe=f1f56fe86c) | Nov 17, 2022 |
| Gigabyte      | H110TN                      | Desktop     | [c121bad3fb](https://bsd-hardware.info/?probe=c121bad3fb) | Nov 17, 2022 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [ddf3f8603a](https://bsd-hardware.info/?probe=ddf3f8603a) | Nov 17, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [64d8291a91](https://bsd-hardware.info/?probe=64d8291a91) | Nov 17, 2022 |
| PC Engines    | apu4                        | Desktop     | [212f27d85a](https://bsd-hardware.info/?probe=212f27d85a) | Nov 17, 2022 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [0d37f1878b](https://bsd-hardware.info/?probe=0d37f1878b) | Nov 17, 2022 |
| AAEON         | MF-001 V1.0                 | Desktop     | [d98d84f1a4](https://bsd-hardware.info/?probe=d98d84f1a4) | Nov 17, 2022 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [f362b4c2ea](https://bsd-hardware.info/?probe=f362b4c2ea) | Nov 17, 2022 |
| AZW           | U59                         | Desktop     | [25e1349c5f](https://bsd-hardware.info/?probe=25e1349c5f) | Nov 17, 2022 |
| HP            | ProLiant DL380 G7           | Server      | [79c7aad234](https://bsd-hardware.info/?probe=79c7aad234) | Nov 17, 2022 |
| Supermicro    | A2SDi-4C-HLN4F              | Desktop     | [9cd1c1fc21](https://bsd-hardware.info/?probe=9cd1c1fc21) | Nov 17, 2022 |
| Dell          | 05XGC8 A00                  | Desktop     | [15458aff84](https://bsd-hardware.info/?probe=15458aff84) | Nov 16, 2022 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [47f82850da](https://bsd-hardware.info/?probe=47f82850da) | Nov 16, 2022 |
| HP            | ProLiant DL120 Gen9         | Server      | [94513a53f8](https://bsd-hardware.info/?probe=94513a53f8) | Nov 16, 2022 |
| MSI           | X299 PRO                    | Desktop     | [d615157be7](https://bsd-hardware.info/?probe=d615157be7) | Nov 16, 2022 |
| ASRock        | J5040-ITX                   | Desktop     | [753c68cfb9](https://bsd-hardware.info/?probe=753c68cfb9) | Nov 16, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [abbd5ab7ff](https://bsd-hardware.info/?probe=abbd5ab7ff) | Nov 16, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [b7ed699f3c](https://bsd-hardware.info/?probe=b7ed699f3c) | Nov 16, 2022 |
| Dell          | 05XGC8 A00                  | Desktop     | [94afb24fbc](https://bsd-hardware.info/?probe=94afb24fbc) | Nov 16, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [2714f36aca](https://bsd-hardware.info/?probe=2714f36aca) | Nov 16, 2022 |
| Acer          | Aspire 5251                 | Notebook    | [046bc722cb](https://bsd-hardware.info/?probe=046bc722cb) | Nov 16, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [436a2d30f6](https://bsd-hardware.info/?probe=436a2d30f6) | Nov 16, 2022 |
| Acer          | Aspire 5251                 | Notebook    | [c9eb0051ed](https://bsd-hardware.info/?probe=c9eb0051ed) | Nov 16, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [5096994f99](https://bsd-hardware.info/?probe=5096994f99) | Nov 16, 2022 |
| HP            | 82B4                        | Desktop     | [d4badfa185](https://bsd-hardware.info/?probe=d4badfa185) | Nov 15, 2022 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [314916c885](https://bsd-hardware.info/?probe=314916c885) | Nov 15, 2022 |
| HP            | 1998                        | Desktop     | [9239fe7437](https://bsd-hardware.info/?probe=9239fe7437) | Nov 15, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [15657b37e2](https://bsd-hardware.info/?probe=15657b37e2) | Nov 15, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [f4a8c42773](https://bsd-hardware.info/?probe=f4a8c42773) | Nov 15, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [dd637e0562](https://bsd-hardware.info/?probe=dd637e0562) | Nov 15, 2022 |
| PC Engines    | apu4                        | Desktop     | [589dec199e](https://bsd-hardware.info/?probe=589dec199e) | Nov 15, 2022 |
| Acer          | TDPS05 R3700                | Desktop     | [4ebc5df17c](https://bsd-hardware.info/?probe=4ebc5df17c) | Nov 15, 2022 |
| Acer          | TDPS05 R3700                | Desktop     | [6e1273fdd6](https://bsd-hardware.info/?probe=6e1273fdd6) | Nov 15, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [3425326f3f](https://bsd-hardware.info/?probe=3425326f3f) | Nov 14, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [cecda8d045](https://bsd-hardware.info/?probe=cecda8d045) | Nov 14, 2022 |
| Shuttle       | FH61V                       | Desktop     | [012a5c0fcc](https://bsd-hardware.info/?probe=012a5c0fcc) | Nov 14, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [2aeadb4dfc](https://bsd-hardware.info/?probe=2aeadb4dfc) | Nov 14, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | Notebook    | [4c83122cc0](https://bsd-hardware.info/?probe=4c83122cc0) | Nov 14, 2022 |
| Dell          | 06D7TR A00                  | Desktop     | [9e568eb5ee](https://bsd-hardware.info/?probe=9e568eb5ee) | Nov 14, 2022 |
| Unknown       | Unknown                     | Desktop     | [b9994aa302](https://bsd-hardware.info/?probe=b9994aa302) | Nov 14, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [a678226171](https://bsd-hardware.info/?probe=a678226171) | Nov 14, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [7650f7619d](https://bsd-hardware.info/?probe=7650f7619d) | Nov 14, 2022 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [443891740b](https://bsd-hardware.info/?probe=443891740b) | Nov 13, 2022 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [0079838512](https://bsd-hardware.info/?probe=0079838512) | Nov 13, 2022 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [86dcacdb40](https://bsd-hardware.info/?probe=86dcacdb40) | Nov 13, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [74a717c2e6](https://bsd-hardware.info/?probe=74a717c2e6) | Nov 13, 2022 |
| Medion        | E15415                      | Notebook    | [e467080570](https://bsd-hardware.info/?probe=e467080570) | Nov 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [6f1e732a53](https://bsd-hardware.info/?probe=6f1e732a53) | Nov 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3448A... | Notebook    | [1d2be7d46a](https://bsd-hardware.info/?probe=1d2be7d46a) | Nov 13, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [15e38a5ca8](https://bsd-hardware.info/?probe=15e38a5ca8) | Nov 13, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [2b1175a4df](https://bsd-hardware.info/?probe=2b1175a4df) | Nov 13, 2022 |
| MSI           | H81M-P33                    | Desktop     | [98b0980231](https://bsd-hardware.info/?probe=98b0980231) | Nov 13, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [80c0d775a7](https://bsd-hardware.info/?probe=80c0d775a7) | Nov 13, 2022 |
| HP            | 83E1                        | Desktop     | [689b01c121](https://bsd-hardware.info/?probe=689b01c121) | Nov 13, 2022 |
| Sophos        | SG                          | Firewall    | [3d17d672bd](https://bsd-hardware.info/?probe=3d17d672bd) | Nov 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [072f2a6c27](https://bsd-hardware.info/?probe=072f2a6c27) | Nov 13, 2022 |
| Shuttle       | FS35V5                      | Mini pc     | [8b634987b4](https://bsd-hardware.info/?probe=8b634987b4) | Nov 13, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [269f915ce2](https://bsd-hardware.info/?probe=269f915ce2) | Nov 13, 2022 |
| Dell          | 04415J A00                  | Mini pc     | [5125bff15a](https://bsd-hardware.info/?probe=5125bff15a) | Nov 13, 2022 |
| HP            | 3397                        | Desktop     | [d087515b69](https://bsd-hardware.info/?probe=d087515b69) | Nov 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [838256315e](https://bsd-hardware.info/?probe=838256315e) | Nov 13, 2022 |
| Dell          | Latitude E7240              | Notebook    | [ea99621380](https://bsd-hardware.info/?probe=ea99621380) | Nov 12, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [ee16ad1ffb](https://bsd-hardware.info/?probe=ee16ad1ffb) | Nov 12, 2022 |
| Huanan        | X99-F8D V2.4                | Desktop     | [22ec05d988](https://bsd-hardware.info/?probe=22ec05d988) | Nov 12, 2022 |
| Fujitsu       | D3373-A1 S26361-D3373-A1... | Server      | [9e972fd1a1](https://bsd-hardware.info/?probe=9e972fd1a1) | Nov 12, 2022 |
| HP            | 8169                        | Desktop     | [e80c8a40a5](https://bsd-hardware.info/?probe=e80c8a40a5) | Nov 12, 2022 |
| Sophos        | SG                          | Firewall    | [4727b6a74e](https://bsd-hardware.info/?probe=4727b6a74e) | Nov 12, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [75b586fdfc](https://bsd-hardware.info/?probe=75b586fdfc) | Nov 12, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [e5b3cb0bcd](https://bsd-hardware.info/?probe=e5b3cb0bcd) | Nov 12, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [f1cd4bdbf3](https://bsd-hardware.info/?probe=f1cd4bdbf3) | Nov 12, 2022 |
| Sophos        | SG                          | Firewall    | [b07c5da938](https://bsd-hardware.info/?probe=b07c5da938) | Nov 12, 2022 |
| PC Engines    | APU2                        | Desktop     | [b92faf9ebb](https://bsd-hardware.info/?probe=b92faf9ebb) | Nov 12, 2022 |
| PC Engines    | APU2                        | Desktop     | [34960ed27c](https://bsd-hardware.info/?probe=34960ed27c) | Nov 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [817c69a4b0](https://bsd-hardware.info/?probe=817c69a4b0) | Nov 12, 2022 |
| Google        | Akemi                       | Notebook    | [2d8e99f0c2](https://bsd-hardware.info/?probe=2d8e99f0c2) | Nov 12, 2022 |
| Lenovo        | ThinkServer RS140           | Desktop     | [0dd05e08aa](https://bsd-hardware.info/?probe=0dd05e08aa) | Nov 12, 2022 |
| Supermicro    | X10SDV-TP8F                 | Server      | [cb88c3311a](https://bsd-hardware.info/?probe=cb88c3311a) | Nov 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [4044f32351](https://bsd-hardware.info/?probe=4044f32351) | Nov 12, 2022 |
| MSI           | MS-9897                     | Desktop     | [2527ac44f4](https://bsd-hardware.info/?probe=2527ac44f4) | Nov 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [790e616e22](https://bsd-hardware.info/?probe=790e616e22) | Nov 12, 2022 |
| Dell          | 06D7TR A00                  | Desktop     | [b8ee0562af](https://bsd-hardware.info/?probe=b8ee0562af) | Nov 12, 2022 |
| HP            | 8000 X4                     | Desktop     | [824d5f1ace](https://bsd-hardware.info/?probe=824d5f1ace) | Nov 12, 2022 |
| HP            | 83E1                        | Desktop     | [1760935c91](https://bsd-hardware.info/?probe=1760935c91) | Nov 12, 2022 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | Desktop     | [54dd33114e](https://bsd-hardware.info/?probe=54dd33114e) | Nov 12, 2022 |
| Unknown       | Unknown                     | Firewall    | [2d2b5ee614](https://bsd-hardware.info/?probe=2d2b5ee614) | Nov 12, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [23a0c08442](https://bsd-hardware.info/?probe=23a0c08442) | Nov 12, 2022 |
| HP            | ProLiant DL360p Gen8        | Server      | [863c472910](https://bsd-hardware.info/?probe=863c472910) | Nov 12, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [0989913192](https://bsd-hardware.info/?probe=0989913192) | Nov 12, 2022 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [e3161d12c5](https://bsd-hardware.info/?probe=e3161d12c5) | Nov 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [a2b2bb3a77](https://bsd-hardware.info/?probe=a2b2bb3a77) | Nov 11, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [0fcbc68304](https://bsd-hardware.info/?probe=0fcbc68304) | Nov 11, 2022 |
| HP            | 1998                        | Desktop     | [e397526bac](https://bsd-hardware.info/?probe=e397526bac) | Nov 11, 2022 |
| HP            | 806A                        | Desktop     | [9567b6949c](https://bsd-hardware.info/?probe=9567b6949c) | Nov 11, 2022 |
| MSI           | MS-B1831                    | Desktop     | [0db8392019](https://bsd-hardware.info/?probe=0db8392019) | Nov 11, 2022 |
| Lenovo        | ThinkServer RS140           | Desktop     | [b2b1509adf](https://bsd-hardware.info/?probe=b2b1509adf) | Nov 11, 2022 |
| HP            | 1998                        | Desktop     | [6a38c36a3e](https://bsd-hardware.info/?probe=6a38c36a3e) | Nov 11, 2022 |
| Lenovo        | 30D9 No DPK                 | Desktop     | [bb9cf416c4](https://bsd-hardware.info/?probe=bb9cf416c4) | Nov 11, 2022 |
| Supermicro    | X10SDV-8C-TLN4F+            | Server      | [515a9245ac](https://bsd-hardware.info/?probe=515a9245ac) | Nov 11, 2022 |
| Supermicro    | X10SDV-8C-TLN4F+            | Server      | [f12f8c8fb2](https://bsd-hardware.info/?probe=f12f8c8fb2) | Nov 11, 2022 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [5a5e24fdf7](https://bsd-hardware.info/?probe=5a5e24fdf7) | Nov 11, 2022 |
| HP            | 18E9                        | Desktop     | [b9df70f7eb](https://bsd-hardware.info/?probe=b9df70f7eb) | Nov 11, 2022 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [391c6bed59](https://bsd-hardware.info/?probe=391c6bed59) | Nov 11, 2022 |
| Supermicro    | X10SDV-TLN4F                | Server      | [2c96fe37f6](https://bsd-hardware.info/?probe=2c96fe37f6) | Nov 10, 2022 |
| ASRock        | J4005B-ITX                  | Desktop     | [554b92cae5](https://bsd-hardware.info/?probe=554b92cae5) | Nov 10, 2022 |
| Deciso        | Netboard A20                | Notebook    | [0320675a86](https://bsd-hardware.info/?probe=0320675a86) | Nov 10, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [569d5b0cca](https://bsd-hardware.info/?probe=569d5b0cca) | Nov 10, 2022 |
| CheckPoint    | PH-30-00                    | Desktop     | [e42768cd01](https://bsd-hardware.info/?probe=e42768cd01) | Nov 10, 2022 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [87d7d4435b](https://bsd-hardware.info/?probe=87d7d4435b) | Nov 10, 2022 |
| ASUSTek       | P5E-VM SE                   | Desktop     | [910dc6412e](https://bsd-hardware.info/?probe=910dc6412e) | Nov 10, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [c741b2fbfa](https://bsd-hardware.info/?probe=c741b2fbfa) | Nov 10, 2022 |
| Dell          | Inspiron 3421               | Notebook    | [5c37012f33](https://bsd-hardware.info/?probe=5c37012f33) | Nov 10, 2022 |
| Deciso        | NetBoard-A20                | Notebook    | [61157ac2b6](https://bsd-hardware.info/?probe=61157ac2b6) | Nov 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [521008f8da](https://bsd-hardware.info/?probe=521008f8da) | Nov 10, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [d8030d23b0](https://bsd-hardware.info/?probe=d8030d23b0) | Nov 10, 2022 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [686447d655](https://bsd-hardware.info/?probe=686447d655) | Nov 10, 2022 |
| BESSTAR Te... | TH50                        | Desktop     | [1300135627](https://bsd-hardware.info/?probe=1300135627) | Nov 10, 2022 |
| Cisco         | C170 A0                     | Desktop     | [3ba579a78c](https://bsd-hardware.info/?probe=3ba579a78c) | Nov 10, 2022 |
| AZW           | GK55                        | Desktop     | [d73ef4f4fc](https://bsd-hardware.info/?probe=d73ef4f4fc) | Nov 10, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [4bb9a9324b](https://bsd-hardware.info/?probe=4bb9a9324b) | Nov 10, 2022 |
| HP            | 843F                        | Desktop     | [23d8a9bda7](https://bsd-hardware.info/?probe=23d8a9bda7) | Nov 10, 2022 |
| ASUSTek       | PRIME Z490M-PLUS            | Desktop     | [9e3a09a0b3](https://bsd-hardware.info/?probe=9e3a09a0b3) | Nov 10, 2022 |
| Protectli     | FW2B                        | Desktop     | [d15326180f](https://bsd-hardware.info/?probe=d15326180f) | Nov 10, 2022 |
| Lenovo        | ThinkPad X260 20F5S2GM00    | Notebook    | [b8874a6df3](https://bsd-hardware.info/?probe=b8874a6df3) | Nov 10, 2022 |
| HP            | 21B4 A01                    | Desktop     | [c064c50fea](https://bsd-hardware.info/?probe=c064c50fea) | Nov 09, 2022 |
| HP            | 21B4 A01                    | Desktop     | [e5c599dfab](https://bsd-hardware.info/?probe=e5c599dfab) | Nov 09, 2022 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [f8e610e161](https://bsd-hardware.info/?probe=f8e610e161) | Nov 09, 2022 |
| ZOTAC         | ZBOX-QCM7T3000/EN072080S... | Mini pc     | [62ab446b5d](https://bsd-hardware.info/?probe=62ab446b5d) | Nov 09, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [d75162607b](https://bsd-hardware.info/?probe=d75162607b) | Nov 09, 2022 |
| HP            | 21B4 A01                    | Desktop     | [0a3ba5478b](https://bsd-hardware.info/?probe=0a3ba5478b) | Nov 09, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [c32a7b407d](https://bsd-hardware.info/?probe=c32a7b407d) | Nov 09, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [9945b6b3e7](https://bsd-hardware.info/?probe=9945b6b3e7) | Nov 09, 2022 |
| ASRock        | H570M-ITX/ac                | Desktop     | [8addd09aa7](https://bsd-hardware.info/?probe=8addd09aa7) | Nov 09, 2022 |
| Sophos        | SG                          | Firewall    | [04b1bf9b24](https://bsd-hardware.info/?probe=04b1bf9b24) | Nov 09, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [667abc6f38](https://bsd-hardware.info/?probe=667abc6f38) | Nov 09, 2022 |
| HP            | 1632                        | Desktop     | [96d60382b7](https://bsd-hardware.info/?probe=96d60382b7) | Nov 09, 2022 |
| ASUSTek       | P8H77-I                     | Desktop     | [04ea3cc97d](https://bsd-hardware.info/?probe=04ea3cc97d) | Nov 09, 2022 |
| Gigabyte      | A520M H                     | Desktop     | [a751c4e782](https://bsd-hardware.info/?probe=a751c4e782) | Nov 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [4adc5f7629](https://bsd-hardware.info/?probe=4adc5f7629) | Nov 09, 2022 |
| MSI           | Z370I GAMING PRO CARBON ... | Desktop     | [dd9f7679b5](https://bsd-hardware.info/?probe=dd9f7679b5) | Nov 09, 2022 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [5dcd51844e](https://bsd-hardware.info/?probe=5dcd51844e) | Nov 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [47e6a4fa8b](https://bsd-hardware.info/?probe=47e6a4fa8b) | Nov 09, 2022 |
| Deciso        | NetBoard-A10                | Notebook    | [1fc6403341](https://bsd-hardware.info/?probe=1fc6403341) | Nov 08, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [32331d772c](https://bsd-hardware.info/?probe=32331d772c) | Nov 08, 2022 |
| Thomas-Kre... | P9A-I/2550/4L               | Firewall    | [d63fd6f7bd](https://bsd-hardware.info/?probe=d63fd6f7bd) | Nov 08, 2022 |
| Dell          | 0G261D A00                  | Desktop     | [c3eb1a6caf](https://bsd-hardware.info/?probe=c3eb1a6caf) | Nov 08, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [127e0126d1](https://bsd-hardware.info/?probe=127e0126d1) | Nov 08, 2022 |
| Intel         | JSL MRD                     | Desktop     | [5800246e28](https://bsd-hardware.info/?probe=5800246e28) | Nov 08, 2022 |
| Lenovo        | ThinkPad X270 20HMCTO1WW    | Notebook    | [9f15cb8acc](https://bsd-hardware.info/?probe=9f15cb8acc) | Nov 08, 2022 |
| ASUSTek       | EX-H110M-V                  | Desktop     | [f9832b4966](https://bsd-hardware.info/?probe=f9832b4966) | Nov 08, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [5807159f51](https://bsd-hardware.info/?probe=5807159f51) | Nov 08, 2022 |
| Google        | Zako                        | Desktop     | [5d4b53e2d4](https://bsd-hardware.info/?probe=5d4b53e2d4) | Nov 08, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [a84d0a0380](https://bsd-hardware.info/?probe=a84d0a0380) | Nov 08, 2022 |
| Dell          | 0W3F1J A00                  | Mini pc     | [5c70ba3a0d](https://bsd-hardware.info/?probe=5c70ba3a0d) | Nov 08, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [2294352c5a](https://bsd-hardware.info/?probe=2294352c5a) | Nov 08, 2022 |
| Dell          | 0F428D A00                  | Desktop     | [0a9ca655d3](https://bsd-hardware.info/?probe=0a9ca655d3) | Nov 08, 2022 |
| Dell          | 0VD5HY A00                  | Desktop     | [1a0df311e3](https://bsd-hardware.info/?probe=1a0df311e3) | Nov 07, 2022 |
| Supermicro    | X8DT6                       | Server      | [e7536e4a4c](https://bsd-hardware.info/?probe=e7536e4a4c) | Nov 07, 2022 |
| HP            | ProBook 4540s               | Notebook    | [9c4be9deab](https://bsd-hardware.info/?probe=9c4be9deab) | Nov 07, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [970443066b](https://bsd-hardware.info/?probe=970443066b) | Nov 07, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [da16bac6f5](https://bsd-hardware.info/?probe=da16bac6f5) | Nov 07, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [45316a9769](https://bsd-hardware.info/?probe=45316a9769) | Nov 07, 2022 |
| HP            | ProLiant ML310e Gen8        | Desktop     | [cb5bb2c3b5](https://bsd-hardware.info/?probe=cb5bb2c3b5) | Nov 07, 2022 |
| ASUSTek       | A88XM-E                     | Desktop     | [fde1fa45b8](https://bsd-hardware.info/?probe=fde1fa45b8) | Nov 07, 2022 |
| ONDA          | N78G5D3 Ver:5.00            | Desktop     | [009bc44d12](https://bsd-hardware.info/?probe=009bc44d12) | Nov 07, 2022 |
| Acer          | RS880M05                    | Desktop     | [455f9b5026](https://bsd-hardware.info/?probe=455f9b5026) | Nov 07, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [798219138a](https://bsd-hardware.info/?probe=798219138a) | Nov 07, 2022 |
| Dell          | 081N4V A08                  | Server      | [6454631448](https://bsd-hardware.info/?probe=6454631448) | Nov 07, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [394e873da0](https://bsd-hardware.info/?probe=394e873da0) | Nov 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [31ff384824](https://bsd-hardware.info/?probe=31ff384824) | Nov 07, 2022 |
| HP            | 8768 A                      | Desktop     | [c8a44e84c6](https://bsd-hardware.info/?probe=c8a44e84c6) | Nov 07, 2022 |
| Sophos        | SG                          | Firewall    | [4547062398](https://bsd-hardware.info/?probe=4547062398) | Nov 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [659ec0b365](https://bsd-hardware.info/?probe=659ec0b365) | Nov 07, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [e8aea441aa](https://bsd-hardware.info/?probe=e8aea441aa) | Nov 06, 2022 |
| PC Engines    | APU2                        | Desktop     | [2a913e7a43](https://bsd-hardware.info/?probe=2a913e7a43) | Nov 06, 2022 |
| PC Engines    | APU2                        | Desktop     | [4fda77e4ca](https://bsd-hardware.info/?probe=4fda77e4ca) | Nov 06, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [70e257e360](https://bsd-hardware.info/?probe=70e257e360) | Nov 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [fed7f55a01](https://bsd-hardware.info/?probe=fed7f55a01) | Nov 06, 2022 |
| HP            | 18E7                        | Desktop     | [6a80fc5241](https://bsd-hardware.info/?probe=6a80fc5241) | Nov 06, 2022 |
| Protectli     | VP2410                      | Desktop     | [de5de1ca21](https://bsd-hardware.info/?probe=de5de1ca21) | Nov 06, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [59b8857bba](https://bsd-hardware.info/?probe=59b8857bba) | Nov 06, 2022 |
| Cisco Syst... | UCSC-C240-M5SX 74-105773... | Server      | [2633eaf68b](https://bsd-hardware.info/?probe=2633eaf68b) | Nov 06, 2022 |
| MSI           | H81M-P33                    | Desktop     | [750d2f53c7](https://bsd-hardware.info/?probe=750d2f53c7) | Nov 06, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [e427ea787e](https://bsd-hardware.info/?probe=e427ea787e) | Nov 06, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [c6abe84145](https://bsd-hardware.info/?probe=c6abe84145) | Nov 06, 2022 |
| Protectli     | FW6                         | Desktop     | [654e223853](https://bsd-hardware.info/?probe=654e223853) | Nov 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [a33d1a4123](https://bsd-hardware.info/?probe=a33d1a4123) | Nov 06, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [c4fd2595e6](https://bsd-hardware.info/?probe=c4fd2595e6) | Nov 06, 2022 |
| Supermicro    | X7SPA-HF                    | Desktop     | [66819692d5](https://bsd-hardware.info/?probe=66819692d5) | Nov 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [6fb650e2e8](https://bsd-hardware.info/?probe=6fb650e2e8) | Nov 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [47efa8b4bc](https://bsd-hardware.info/?probe=47efa8b4bc) | Nov 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [3771535d50](https://bsd-hardware.info/?probe=3771535d50) | Nov 06, 2022 |
| Dell          | OptiPlex 5050               | Desktop     | [cfd442a25d](https://bsd-hardware.info/?probe=cfd442a25d) | Nov 06, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [95d5580fd7](https://bsd-hardware.info/?probe=95d5580fd7) | Nov 05, 2022 |
| Datto         | SSD                         | Desktop     | [235483110d](https://bsd-hardware.info/?probe=235483110d) | Nov 05, 2022 |
| Lenovo        | ThinkPad T430 23446FP       | Notebook    | [1373bd7f3e](https://bsd-hardware.info/?probe=1373bd7f3e) | Nov 05, 2022 |
| HP            | ProBook 4540s               | Notebook    | [7596b602c6](https://bsd-hardware.info/?probe=7596b602c6) | Nov 05, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [33eea3a422](https://bsd-hardware.info/?probe=33eea3a422) | Nov 05, 2022 |
| ASUSTek       | Z170-K                      | Desktop     | [907b8c2402](https://bsd-hardware.info/?probe=907b8c2402) | Nov 05, 2022 |
| Sophos        | SG                          | Firewall    | [d80c273f85](https://bsd-hardware.info/?probe=d80c273f85) | Nov 05, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [80a31985d9](https://bsd-hardware.info/?probe=80a31985d9) | Nov 05, 2022 |
| ASUSTek       | Z97-A                       | Desktop     | [6a2b1c8105](https://bsd-hardware.info/?probe=6a2b1c8105) | Nov 05, 2022 |
| Intel         | CRESCENTBAY                 | Desktop     | [0312c464c4](https://bsd-hardware.info/?probe=0312c464c4) | Nov 05, 2022 |
| Protectli     | FW4C Ver                    | Desktop     | [71c0c846f1](https://bsd-hardware.info/?probe=71c0c846f1) | Nov 05, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [3fa9f3aa5c](https://bsd-hardware.info/?probe=3fa9f3aa5c) | Nov 05, 2022 |
| Dell          | 05GD68 A00                  | Desktop     | [946c93ec7b](https://bsd-hardware.info/?probe=946c93ec7b) | Nov 05, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d27fd3b1a7](https://bsd-hardware.info/?probe=d27fd3b1a7) | Nov 04, 2022 |
| Dell          | 0CN7CM A06                  | Server      | [6efd22e598](https://bsd-hardware.info/?probe=6efd22e598) | Nov 04, 2022 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [5784d8bed6](https://bsd-hardware.info/?probe=5784d8bed6) | Nov 04, 2022 |
| HP            | 213D A01                    | Desktop     | [f579ee6387](https://bsd-hardware.info/?probe=f579ee6387) | Nov 04, 2022 |
| Dell          | 0G7WYD A01                  | Server      | [655a9e7af2](https://bsd-hardware.info/?probe=655a9e7af2) | Nov 04, 2022 |
| ASRock        | H670M-ITX/ax                | Desktop     | [378889e1cd](https://bsd-hardware.info/?probe=378889e1cd) | Nov 04, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [73230496b2](https://bsd-hardware.info/?probe=73230496b2) | Nov 04, 2022 |
| Lenovo        | YangTianM6880N              | Desktop     | [2e9c3b7368](https://bsd-hardware.info/?probe=2e9c3b7368) | Nov 04, 2022 |
| BESSTAR Te... | HM80                        | Desktop     | [d5c5f30a2d](https://bsd-hardware.info/?probe=d5c5f30a2d) | Nov 04, 2022 |
| Dell          | 0KM5PX A01                  | Server      | [a1a15662d0](https://bsd-hardware.info/?probe=a1a15662d0) | Nov 04, 2022 |
| Dell          | 0KM5PX A01                  | Server      | [0ee82f0b87](https://bsd-hardware.info/?probe=0ee82f0b87) | Nov 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [4f58f89a6e](https://bsd-hardware.info/?probe=4f58f89a6e) | Nov 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [58c2f4b4f7](https://bsd-hardware.info/?probe=58c2f4b4f7) | Nov 04, 2022 |
| Fujitsu       | D3049-A1 S26361-D3049-A1... | Server      | [1b27159e27](https://bsd-hardware.info/?probe=1b27159e27) | Nov 04, 2022 |
| HP            | 82A2                        | Desktop     | [d83974a5ed](https://bsd-hardware.info/?probe=d83974a5ed) | Nov 03, 2022 |
| HP            | 339A                        | Desktop     | [a1e829d9d9](https://bsd-hardware.info/?probe=a1e829d9d9) | Nov 03, 2022 |
| Unknown       | 1.0                         | Desktop     | [9fe6ac4e68](https://bsd-hardware.info/?probe=9fe6ac4e68) | Nov 03, 2022 |
| Dell          | Precision M4500             | Notebook    | [ab63467f38](https://bsd-hardware.info/?probe=ab63467f38) | Nov 03, 2022 |
| Deciso        | NetBoard-A20                | Notebook    | [9c133326c9](https://bsd-hardware.info/?probe=9c133326c9) | Nov 03, 2022 |
| PC Engines    | apu4                        | Desktop     | [7ed7638be3](https://bsd-hardware.info/?probe=7ed7638be3) | Nov 03, 2022 |
| AMD           | Inagua CRB                  | Desktop     | [5d27c08853](https://bsd-hardware.info/?probe=5d27c08853) | Nov 03, 2022 |
| Sophos        | XG                          | Firewall    | [f2f91c4258](https://bsd-hardware.info/?probe=f2f91c4258) | Nov 03, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [3021b8ee09](https://bsd-hardware.info/?probe=3021b8ee09) | Nov 03, 2022 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [7729ec0863](https://bsd-hardware.info/?probe=7729ec0863) | Nov 03, 2022 |
| ASUSTek       | H110M-CS/BR                 | Desktop     | [0841d714d0](https://bsd-hardware.info/?probe=0841d714d0) | Nov 03, 2022 |
| Dell          | 05GD68 A00                  | Desktop     | [8e0c8344af](https://bsd-hardware.info/?probe=8e0c8344af) | Nov 03, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [72d95a4938](https://bsd-hardware.info/?probe=72d95a4938) | Nov 03, 2022 |
| Samsung       | 750TDA                      | Notebook    | [a880b1f616](https://bsd-hardware.info/?probe=a880b1f616) | Nov 02, 2022 |
| HP            | 843F                        | Desktop     | [f921634ea0](https://bsd-hardware.info/?probe=f921634ea0) | Nov 02, 2022 |
| HP            | 339A                        | Desktop     | [370d93ecde](https://bsd-hardware.info/?probe=370d93ecde) | Nov 02, 2022 |
| Dell          | 0VWT90 A10                  | Server      | [b74220aee1](https://bsd-hardware.info/?probe=b74220aee1) | Nov 02, 2022 |
| HP            | ProLiant DL180 G6           | Server      | [289d2f383b](https://bsd-hardware.info/?probe=289d2f383b) | Nov 02, 2022 |
| Lenovo        | 00FN849 E63448-400          | Server      | [0794efc014](https://bsd-hardware.info/?probe=0794efc014) | Nov 02, 2022 |
| Hardkernel    | ODROID-H2                   | Desktop     | [f0e3f3177a](https://bsd-hardware.info/?probe=f0e3f3177a) | Nov 02, 2022 |
| Gigabyte      | Z97X-UD5H                   | Desktop     | [d7141b866c](https://bsd-hardware.info/?probe=d7141b866c) | Nov 02, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [b6044fb84c](https://bsd-hardware.info/?probe=b6044fb84c) | Nov 02, 2022 |

...


System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| helloSystem 0.7.0    | 415       | 3.85%   |
| OPNsense 21.7.7      | 281       | 2.61%   |
| helloSystem 0.5.0    | 245       | 2.27%   |
| OPNsense 21.1        | 240       | 2.23%   |
| OPNsense 21.7.1      | 229       | 2.13%   |
| OPNsense 22.1        | 227       | 2.11%   |
| OPNsense 21.7.3      | 225       | 2.09%   |
| OPNsense 21.1.5      | 225       | 2.09%   |
| FreeBSD 13.0         | 222       | 2.06%   |
| OPNsense 22.7.4      | 214       | 1.99%   |
| OPNsense 20.7.8      | 214       | 1.99%   |
| OpenBSD 6.8          | 208       | 1.93%   |
| OPNsense 21.1.3      | 205       | 1.9%    |
| OPNsense 22.1.6      | 192       | 1.78%   |
| helloSystem 0.4.0    | 190       | 1.76%   |
| FreeBSD 13.1         | 189       | 1.75%   |
| OPNsense 22.1.8      | 187       | 1.74%   |
| OPNsense 22.7.6      | 182       | 1.69%   |
| OPNsense 21.1.4      | 175       | 1.62%   |
| OPNsense 22.7.9      | 169       | 1.57%   |
| OPNsense 22.1.10     | 168       | 1.56%   |
| OPNsense 21.1.1      | 157       | 1.46%   |
| OPNsense 21.1.2      | 147       | 1.36%   |
| FreeBSD 12.2         | 141       | 1.31%   |
| helloSystem 0.6.0    | 137       | 1.27%   |
| OPNsense 22.1.4      | 134       | 1.24%   |
| OPNsense 21.7.6      | 131       | 1.22%   |
| OPNsense 21.1.6      | 129       | 1.2%    |
| OPNsense 22.7        | 128       | 1.19%   |
| OPNsense 21.1.7      | 127       | 1.18%   |
| OPNsense 22.7.8      | 123       | 1.14%   |
| OPNsense 22.7.2      | 123       | 1.14%   |
| OPNsense 21.1.8      | 122       | 1.13%   |
| OPNsense 22.1.2      | 120       | 1.11%   |
| OPNsense 22.7.7      | 116       | 1.08%   |
| OPNsense 22.1.1      | 116       | 1.08%   |
| OPNsense 21.7.5      | 113       | 1.05%   |
| FreeBSD 14.0-CURRENT | 112       | 1.04%   |
| GhostBSD 20.04.02    | 109       | 1.01%   |
| OPNsense 22.1.7      | 106       | 0.98%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 4359      | 51.4%   |
| FreeBSD     | 1971      | 23.24%  |
| helloSystem | 1044      | 12.31%  |
| OpenBSD     | 497       | 5.86%   |
| GhostBSD    | 211       | 2.49%   |
| NomadBSD    | 149       | 1.76%   |
| NetBSD      | 55        | 0.65%   |
| TrueNAS     | 43        | 0.51%   |
| FreeNAS     | 30        | 0.35%   |
| pfSense     | 28        | 0.33%   |
| HardenedBSD | 19        | 0.22%   |
| DragonFly   | 16        | 0.19%   |
| MidnightBSD | 14        | 0.17%   |
| MyBee       | 11        | 0.13%   |
| FuryBSD     | 11        | 0.13%   |
| XigmaNAS    | 8         | 0.09%   |
| OS108       | 4         | 0.05%   |
| PC-BSD      | 3         | 0.04%   |
| ClonOS      | 3         | 0.04%   |
| Ting        | 2         | 0.02%   |
| FuguIta     | 2         | 0.02%   |
| LibertyBSD  | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| amd64   | 8115      | 97.01%  |
| i386    | 122       | 1.46%   |
| arm64   | 95        | 1.14%   |
| arm     | 12        | 0.14%   |
| evbarm  | 6         | 0.07%   |
| macppc  | 5         | 0.06%   |
| sparc64 | 3         | 0.04%   |
| powerpc | 2         | 0.02%   |
| octeon  | 2         | 0.02%   |
| armv7   | 2         | 0.02%   |
| riscv   | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Console          | 5312      | 61.95%  |
| helloDesktop     | 1159      | 13.52%  |
| XFCE             | 396       | 4.62%   |
| KDE5             | 341       | 3.98%   |
| MATE             | 281       | 3.28%   |
| fvwm             | 274       | 3.2%    |
| Openbox          | 190       | 2.22%   |
| GNOME            | 161       | 1.88%   |
| TWM              | 156       | 1.82%   |
| i3               | 102       | 1.19%   |
| Cinnamon         | 32        | 0.37%   |
| AwesomeWM        | 24        | 0.28%   |
| Fluxbox          | 22        | 0.26%   |
| LXQt             | 21        | 0.24%   |
| Enlightenment    | 16        | 0.19%   |
| LXDE             | 15        | 0.17%   |
| Lumina           | 11        | 0.13%   |
| DWM              | 8         | 0.09%   |
| GNUstep          | 6         | 0.07%   |
| xfwm             | 4         | 0.05%   |
| Window Maker     | 4         | 0.05%   |
| CTWM             | 4         | 0.05%   |
| CDE              | 4         | 0.05%   |
| spectrwm         | 3         | 0.03%   |
| Picom            | 3         | 0.03%   |
| Xfwm4            | 2         | 0.02%   |
| X-Cinnamon       | 2         | 0.02%   |
| Mutter           | 2         | 0.02%   |
| Metacity (Marco) | 2         | 0.02%   |
| IceWM            | 2         | 0.02%   |
| Compton          | 2         | 0.02%   |
| Awesome          | 2         | 0.02%   |
| xinitrc          | 1         | 0.01%   |
| StumpWM          | 1         | 0.01%   |
| Ratpoison        | 1         | 0.01%   |
| plasma           | 1         | 0.01%   |
| PekWM            | 1         | 0.01%   |
| KWin             | 1         | 0.01%   |
| KDE              | 1         | 0.01%   |
| iwm              | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 5402      | 64.21%  |
| X11     | 2976      | 35.37%  |
| Wayland | 35        | 0.42%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 6153      | 72.41%  |
| SLiM    | 1429      | 16.82%  |
| SDDM    | 326       | 3.84%   |
| LightDM | 321       | 3.78%   |
| XDM     | 139       | 1.64%   |
| GDM     | 117       | 1.38%   |
| Ly      | 10        | 0.12%   |
| PCDM    | 2         | 0.02%   |
| WDM     | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 5491      | 64.01%  |
| en_US            | 1574      | 18.35%  |
| C                | 924       | 10.77%  |
| ru_RU            | 150       | 1.75%   |
| de_DE            | 85        | 0.99%   |
| fr_FR            | 51        | 0.59%   |
| en_GB            | 46        | 0.54%   |
| es_ES            | 25        | 0.29%   |
| zh_CN            | 20        | 0.23%   |
| pt_BR            | 17        | 0.2%    |
| it_IT            | 15        | 0.17%   |
| en_CA            | 14        | 0.16%   |
| pl_PL            | 13        | 0.15%   |
| en_AU            | 12        | 0.14%   |
| ja_JP            | 11        | 0.13%   |
| uk_UA            | 10        | 0.12%   |
| nb_NO            | 7         | 0.08%   |
| hu_HU            | 6         | 0.07%   |
| fi_FI            | 6         | 0.07%   |
| en_IE            | 6         | 0.07%   |
| es_AR            | 5         | 0.06%   |
| en_NZ            | 5         | 0.06%   |
| el_GR            | 5         | 0.06%   |
| sv_SE            | 4         | 0.05%   |
| en_US.ISO8859-1  | 4         | 0.05%   |
| cs_CZ            | 4         | 0.05%   |
| zh_TW            | 3         | 0.03%   |
| tr_TR            | 3         | 0.03%   |
| ru_RU.KOI8-R     | 3         | 0.03%   |
| en_US.US-ASCII   | 3         | 0.03%   |
| de_DE.ISO8859-1  | 3         | 0.03%   |
| de_CH            | 3         | 0.03%   |
| sl_SI            | 2         | 0.02%   |
| sk_SK            | 2         | 0.02%   |
| pt_PT            | 2         | 0.02%   |
| nl_NL            | 2         | 0.02%   |
| it_IT.ISO8859-15 | 2         | 0.02%   |
| es_CO            | 2         | 0.02%   |
| en_SG            | 2         | 0.02%   |
| en_GB.US-ASCII   | 2         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 6752      | 79.73%  |
| BIOS | 1717      | 20.27%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ufs     | 4327      | 50.47%  |
| Zfs     | 3422      | 39.91%  |
| Ffs     | 500       | 5.83%   |
| Cd9660  | 299       | 3.49%   |
| Hammer2 | 15        | 0.17%   |
| Unknown | 6         | 0.07%   |
| XXX     | 3         | 0.03%   |
| Xfs     | 1         | 0.01%   |
| Nfs     | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 7483      | 88.79%  |
| MBR     | 827       | 9.81%   |
| Unknown | 104       | 1.23%   |
| BSD     | 14        | 0.17%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Dell                       | 1001      | 11.97%  |
| Lenovo                     | 859       | 10.27%  |
| ASUSTek Computer           | 740       | 8.85%   |
| Hewlett-Packard            | 724       | 8.66%   |
| Unknown                    | 623       | 7.45%   |
| Supermicro                 | 413       | 4.94%   |
| Intel                      | 403       | 4.82%   |
| Gigabyte Technology        | 369       | 4.41%   |
| ASRock                     | 351       | 4.2%    |
| PC Engines                 | 280       | 3.35%   |
| MSI                        | 246       | 2.94%   |
| Protectli                  | 245       | 2.93%   |
| AMI                        | 166       | 1.98%   |
| Fujitsu                    | 153       | 1.83%   |
| Acer                       | 153       | 1.83%   |
| Apple                      | 141       | 1.69%   |
| Sophos                     | 108       | 1.29%   |
| ZOTAC                      | 81        | 0.97%   |
| Deciso                     | 67        | 0.8%    |
| Shuttle                    | 61        | 0.73%   |
| BESSTAR Tech               | 60        | 0.72%   |
| Toshiba                    | 47        | 0.56%   |
| Biostar                    | 37        | 0.44%   |
| Samsung Electronics        | 35        | 0.42%   |
| IBM                        | 34        | 0.41%   |
| AWOW                       | 30        | 0.36%   |
| Sony                       | 29        | 0.35%   |
| MW                         | 29        | 0.35%   |
| HARDKERNEL                 | 29        | 0.35%   |
| ASRockRack                 | 28        | 0.33%   |
| CompuLab                   | 26        | 0.31%   |
| Techvision                 | 25        | 0.3%    |
| Raspberry Pi Foundation    | 22        | 0.26%   |
| Foxconn                    | 22        | 0.26%   |
| AZW                        | 22        | 0.26%   |
| Pegatron                   | 21        | 0.25%   |
| Google                     | 18        | 0.22%   |
| HPE                        | 17        | 0.2%    |
| ShenZhen MinWin Technology | 16        | 0.19%   |
| TUXEDO                     | 15        | 0.18%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 651       | 7.78%   |
| PC Engines APU2                     | 136       | 1.63%   |
| AMI Aptio CRB                       | 130       | 1.55%   |
| Supermicro Super Server             | 114       | 1.36%   |
| Protectli FW4B                      | 101       | 1.21%   |
| Intel Q3XXG4-P V1.0                 | 101       | 1.21%   |
| PC Engines apu4                     | 91        | 1.09%   |
| Protectli FW6                       | 75        | 0.9%    |
| ASUS All Series                     | 72        | 0.86%   |
| Sophos SG                           | 54        | 0.65%   |
| HP t620 PLUS Quad Core TC           | 47        | 0.56%   |
| Fujitsu FUTRO S920                  | 46        | 0.55%   |
| Dell PowerEdge R210 II              | 42        | 0.5%    |
| HP t730 Thin Client                 | 38        | 0.45%   |
| Dell OptiPlex 9020                  | 38        | 0.45%   |
| Dell OptiPlex 3020                  | 33        | 0.39%   |
| Sophos XG                           | 31        | 0.37%   |
| Dell OptiPlex 7010                  | 30        | 0.36%   |
| MW GMLK-2_5G4L                      | 29        | 0.35%   |
| HARDKERNEL ODROID-H2                | 27        | 0.32%   |
| Techvision TVI7309X                 | 25        | 0.3%    |
| Supermicro X9SCL/X9SCM              | 23        | 0.28%   |
| Sophos UTM                          | 23        | 0.28%   |
| HP ProLiant MicroServer Gen8        | 22        | 0.26%   |
| Supermicro A1SAi                    | 21        | 0.25%   |
| AWOW PC BOX                         | 21        | 0.25%   |
| Supermicro X10SLH-N6-ST031          | 20        | 0.24%   |
| PC Engines APU3                     | 20        | 0.24%   |
| PC Engines APU                      | 20        | 0.24%   |
| HP EliteDesk 800 G1 SFF             | 20        | 0.24%   |
| Deciso Netboard A20                 | 19        | 0.23%   |
| CompuLab fitlet2                    | 19        | 0.23%   |
| ZOTAC ZBOX-CI329NANO                | 18        | 0.22%   |
| Dell Wyse 5070 Extended Thin Client | 18        | 0.22%   |
| Dell PowerEdge R710                 | 18        | 0.22%   |
| Dell PowerEdge R610                 | 18        | 0.22%   |
| Protectli VP2410                    | 17        | 0.2%    |
| Protectli FW2B                      | 16        | 0.19%   |
| HP ProDesk 600 G1 SFF               | 16        | 0.19%   |
| HP Compaq Elite 8300 SFF            | 16        | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Unknown              | 651       | 7.78%   |
| Lenovo ThinkPad      | 519       | 6.21%   |
| Dell OptiPlex        | 299       | 3.58%   |
| Dell PowerEdge       | 257       | 3.07%   |
| Lenovo ThinkCentre   | 145       | 1.73%   |
| Dell Latitude        | 139       | 1.66%   |
| PC Engines APU2      | 136       | 1.63%   |
| AMI Aptio            | 132       | 1.58%   |
| HP ProLiant          | 131       | 1.57%   |
| Supermicro Super     | 114       | 1.36%   |
| ASUS PRIME           | 107       | 1.28%   |
| Dell Inspiron        | 105       | 1.26%   |
| Intel Q3XXG4-P       | 102       | 1.22%   |
| Protectli FW4B       | 101       | 1.21%   |
| Acer Aspire          | 98        | 1.17%   |
| PC Engines apu4      | 91        | 1.09%   |
| HP Compaq            | 90        | 1.08%   |
| Dell Precision       | 76        | 0.91%   |
| Protectli FW6        | 75        | 0.9%    |
| ASUS All             | 72        | 0.86%   |
| HP ProDesk           | 63        | 0.75%   |
| HP EliteDesk         | 63        | 0.75%   |
| Fujitsu FUTRO        | 63        | 0.75%   |
| Sophos SG            | 54        | 0.65%   |
| HP t620              | 53        | 0.63%   |
| Lenovo IdeaPad       | 52        | 0.62%   |
| ASUS ROG             | 52        | 0.62%   |
| ASUS TUF             | 49        | 0.59%   |
| HP Pavilion          | 42        | 0.5%    |
| Deciso Netboard      | 39        | 0.47%   |
| HP t730              | 38        | 0.45%   |
| HP EliteBook         | 38        | 0.45%   |
| Toshiba Satellite    | 32        | 0.38%   |
| Sophos XG            | 31        | 0.37%   |
| HP ProBook           | 30        | 0.36%   |
| MW GMLK-2            | 29        | 0.35%   |
| HARDKERNEL ODROID-H2 | 27        | 0.32%   |
| Fujitsu ESPRIMO      | 27        | 0.32%   |
| Dell XPS             | 27        | 0.32%   |
| Techvision TVI7309X  | 25        | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 985       | 11.78%  |
| 2019    | 893       | 10.68%  |
| 2020    | 865       | 10.34%  |
| 2021    | 664       | 7.94%   |
| 2016    | 644       | 7.7%    |
| 2014    | 607       | 7.26%   |
| 2013    | 541       | 6.47%   |
| 2017    | 480       | 5.74%   |
| 2015    | 470       | 5.62%   |
| 2011    | 447       | 5.34%   |
| 2012    | 433       | 5.18%   |
| 2010    | 317       | 3.79%   |
| 2022    | 304       | 3.64%   |
| 2009    | 235       | 2.81%   |
| 2008    | 160       | 1.91%   |
| Unknown | 152       | 1.82%   |
| 2007    | 85        | 1.02%   |
| 2006    | 43        | 0.51%   |
| 2005    | 12        | 0.14%   |
| 2004    | 11        | 0.13%   |
| 2003    | 8         | 0.1%    |
| 2002    | 5         | 0.06%   |
| 2001    | 2         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 4912      | 58.73%  |
| Notebook       | 1927      | 23.04%  |
| Server         | 676       | 8.08%   |
| Mini pc        | 573       | 6.85%   |
| Firewall       | 130       | 1.55%   |
| All in one     | 51        | 0.61%   |
| System on chip | 50        | 0.6%    |
| Convertible    | 39        | 0.47%   |
| Tablet         | 5         | 0.06%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 7950      | 95.06%  |
| Yes  | 413       | 4.94%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 2979      | 35%     |
| 4.01-8.0        | 1899      | 22.31%  |
| 16.01-24.0      | 1758      | 20.66%  |
| 32.01-64.0      | 755       | 8.87%   |
| 64.01-256.0     | 338       | 3.97%   |
| 2.01-3.0        | 328       | 3.85%   |
| 3.01-4.0        | 146       | 1.72%   |
| 24.01-32.0      | 118       | 1.39%   |
| 0.51-1.0        | 79        | 0.93%   |
| 1.01-2.0        | 60        | 0.7%    |
| 0.01-0.5        | 27        | 0.32%   |
| More than 256.0 | 21        | 0.25%   |
| Unknown         | 2         | 0.02%   |
| 0               | 1         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 0.01-0.5        | 4499      | 51.81%  |
| 0.51-1.0        | 2361      | 27.19%  |
| 1.01-2.0        | 909       | 10.47%  |
| 2.01-3.0        | 231       | 2.66%   |
| 4.01-8.0        | 180       | 2.07%   |
| 3.01-4.0        | 128       | 1.47%   |
| 8.01-16.0       | 95        | 1.09%   |
| Unknown         | 68        | 0.78%   |
| 0               | 61        | 0.7%    |
| 16.01-24.0      | 46        | 0.53%   |
| 24.01-32.0      | 45        | 0.52%   |
| 32.01-64.0      | 36        | 0.41%   |
| 64.01-256.0     | 24        | 0.28%   |
| More than 256.0 | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 5704      | 66.37%  |
| 2      | 1259      | 14.65%  |
| 0      | 701       | 8.16%   |
| 3      | 365       | 4.25%   |
| 4      | 222       | 2.58%   |
| 5      | 107       | 1.25%   |
| 6      | 75        | 0.87%   |
| 7      | 39        | 0.45%   |
| 8      | 24        | 0.28%   |
| 14     | 16        | 0.19%   |
| 10     | 14        | 0.16%   |
| 12     | 12        | 0.14%   |
| 9      | 12        | 0.14%   |
| 11     | 9         | 0.1%    |
| 17     | 5         | 0.06%   |
| 25     | 4         | 0.05%   |
| 18     | 3         | 0.03%   |
| 15     | 3         | 0.03%   |
| 13     | 3         | 0.03%   |
| 40     | 2         | 0.02%   |
| 23     | 2         | 0.02%   |
| 21     | 2         | 0.02%   |
| 19     | 2         | 0.02%   |
| 16     | 2         | 0.02%   |
| 63     | 1         | 0.01%   |
| 58     | 1         | 0.01%   |
| 28     | 1         | 0.01%   |
| 27     | 1         | 0.01%   |
| 26     | 1         | 0.01%   |
| 24     | 1         | 0.01%   |
| 22     | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 6697      | 79.47%  |
| Yes       | 1730      | 20.53%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 7953      | 95.09%  |
| No        | 411       | 4.91%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 5206      | 61.78%  |
| Yes       | 3221      | 38.22%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 6310      | 74.85%  |
| Yes       | 2120      | 25.15%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 2105      | 25.06%  |
| Germany      | 1426      | 16.97%  |
| Russia       | 437       | 5.2%    |
| France       | 347       | 4.13%   |
| UK           | 338       | 4.02%   |
| Canada       | 314       | 3.74%   |
| Netherlands  | 219       | 2.61%   |
| Poland       | 208       | 2.48%   |
| Brazil       | 199       | 2.37%   |
| Australia    | 193       | 2.3%    |
| Italy        | 164       | 1.95%   |
| Switzerland  | 163       | 1.94%   |
| Austria      | 151       | 1.8%    |
| China        | 141       | 1.68%   |
| Spain        | 138       | 1.64%   |
| Sweden       | 133       | 1.58%   |
| Ukraine      | 94        | 1.12%   |
| Czechia      | 83        | 0.99%   |
| Norway       | 77        | 0.92%   |
| Finland      | 73        | 0.87%   |
| India        | 71        | 0.85%   |
| Japan        | 69        | 0.82%   |
| Romania      | 64        | 0.76%   |
| Indonesia    | 62        | 0.74%   |
| Hungary      | 61        | 0.73%   |
| Portugal     | 59        | 0.7%    |
| Belgium      | 58        | 0.69%   |
| Denmark      | 54        | 0.64%   |
| Taiwan       | 51        | 0.61%   |
| Mexico       | 49        | 0.58%   |
| New Zealand  | 42        | 0.5%    |
| South Korea  | 40        | 0.48%   |
| South Africa | 36        | 0.43%   |
| Greece       | 36        | 0.43%   |
| Argentina    | 36        | 0.43%   |
| Bulgaria     | 33        | 0.39%   |
| Thailand     | 29        | 0.35%   |
| Turkey       | 27        | 0.32%   |
| Slovenia     | 24        | 0.29%   |
| Singapore    | 24        | 0.29%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 141       | 1.53%   |
| Berlin            | 131       | 1.42%   |
| Vienna            | 85        | 0.92%   |
| Paris             | 76        | 0.83%   |
| Munich            | 63        | 0.68%   |
| Hamburg           | 55        | 0.6%    |
| Sydney            | 48        | 0.52%   |
| Amsterdam         | 48        | 0.52%   |
| Zurich            | 46        | 0.5%    |
| St Petersburg     | 46        | 0.5%    |
| London            | 45        | 0.49%   |
| Frankfurt am Main | 39        | 0.42%   |
| Brooklyn          | 39        | 0.42%   |
| Chicago           | 37        | 0.4%    |
| Kyiv              | 36        | 0.39%   |
| Warsaw            | 35        | 0.38%   |
| Montreal          | 35        | 0.38%   |
| Melbourne         | 35        | 0.38%   |
| Jakarta           | 33        | 0.36%   |
| Cologne           | 33        | 0.36%   |
| Bucharest         | 33        | 0.36%   |
| Toronto           | 30        | 0.33%   |
| Seattle           | 30        | 0.33%   |
| New York          | 29        | 0.32%   |
| Helsinki          | 29        | 0.32%   |
| Denver            | 29        | 0.32%   |
| Stuttgart         | 28        | 0.3%    |
| Perth             | 28        | 0.3%    |
| Prague            | 27        | 0.29%   |
| Madrid            | 27        | 0.29%   |
| Oslo              | 26        | 0.28%   |
| Dallas            | 25        | 0.27%   |
| Portland          | 24        | 0.26%   |
| Brisbane          | 24        | 0.26%   |
| Singapore         | 23        | 0.25%   |
| Milan             | 23        | 0.25%   |
| Athens            | 23        | 0.25%   |
| Sofia             | 21        | 0.23%   |
| Karlsruhe         | 21        | 0.23%   |
| Rome              | 20        | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1528      | 2428   | 15.36%  |
| WDC                 | 1349      | 2890   | 13.56%  |
| Seagate             | 1040      | 2174   | 10.45%  |
| Kingston            | 733       | 1019   | 7.37%   |
| Crucial             | 490       | 713    | 4.93%   |
| Toshiba             | 462       | 829    | 4.64%   |
| SanDisk             | 429       | 566    | 4.31%   |
| Intel               | 409       | 660    | 4.11%   |
| Transcend           | 399       | 568    | 4.01%   |
| Hitachi             | 250       | 492    | 2.51%   |
| A-DATA Technology   | 193       | 268    | 1.94%   |
| Hoodisk             | 178       | 254    | 1.79%   |
| Phison              | 160       | 225    | 1.61%   |
| HGST                | 158       | 416    | 1.59%   |
| China               | 133       | 188    | 1.34%   |
| Hewlett-Packard     | 109       | 326    | 1.1%    |
| SK hynix            | 104       | 134    | 1.05%   |
| Micron Technology   | 104       | 163    | 1.05%   |
| NVMe                | 100       | 133    | 1.01%   |
| SPCC                | 85        | 127    | 0.85%   |
| OCZ                 | 79        | 106    | 0.79%   |
| FORESEE             | 78        | 112    | 0.78%   |
| PNY                 | 77        | 125    | 0.77%   |
| Apacer              | 65        | 74     | 0.65%   |
| Corsair             | 58        | 89     | 0.58%   |
| Intenso             | 51        | 81     | 0.51%   |
| Protectli           | 50        | 81     | 0.5%    |
| Apple               | 50        | 55     | 0.5%    |
| Dogfish             | 49        | 78     | 0.49%   |
| Patriot             | 39        | 54     | 0.39%   |
| KingSpec            | 39        | 48     | 0.39%   |
| Innodisk            | 39        | 47     | 0.39%   |
| BIWIN               | 39        | 55     | 0.39%   |
| LITEON              | 37        | 52     | 0.37%   |
| Gigabyte Technology | 34        | 45     | 0.34%   |
| LITEONIT            | 33        | 37     | 0.33%   |
| Fujitsu             | 31        | 42     | 0.31%   |
| Silicon Motion      | 29        | 34     | 0.29%   |
| Plextor             | 27        | 40     | 0.27%   |
| KIOXIA              | 26        | 33     | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB        | 118       | 1.08%   |
| Samsung SSD 850 EVO 250GB          | 99        | 0.91%   |
| Kingston SA400S37120G 120GB        | 95        | 0.87%   |
| Phison SATA SSD 16GB               | 74        | 0.68%   |
| Samsung SSD 860 EVO 500GB          | 72        | 0.66%   |
| Kingston SUV500MS120G 120GB        | 64        | 0.59%   |
| Samsung SSD 860 EVO 250GB          | 61        | 0.56%   |
| Crucial CT240BX500SSD1 240GB       | 60        | 0.55%   |
| Seagate ST500DM002-1BD142 500GB    | 56        | 0.51%   |
| Samsung SSD 850 EVO 500GB          | 52        | 0.48%   |
| Hoodisk SSD 32GB                   | 51        | 0.47%   |
| Crucial CT500MX500SSD1 500GB       | 50        | 0.46%   |
| Crucial CT250MX500SSD1 250GB       | 49        | 0.45%   |
| Hoodisk SSD 64GB                   | 47        | 0.43%   |
| Hoodisk SSD 128GB                  | 47        | 0.43%   |
| Kingston SV300S37A120G 120GB       | 46        | 0.42%   |
| Crucial CT120BX500SSD1 120GB       | 44        | 0.4%    |
| Transcend TS128GMSA230S 128GB      | 43        | 0.39%   |
| FORESEE 128GB SSD                  | 43        | 0.39%   |
| Seagate ST1000DM010-2EP102 1TB     | 41        | 0.38%   |
| Seagate ST1000LM035-1RK172 1TB     | 40        | 0.37%   |
| HP RAID 1(1+0) 800GB               | 40        | 0.37%   |
| Toshiba DT01ACA100 1TB             | 38        | 0.35%   |
| Toshiba MQ01ABD100 1TB             | 36        | 0.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 36        | 0.33%   |
| Samsung SSD 860 EVO 1TB            | 36        | 0.33%   |
| Samsung SSD 840 EVO 250GB          | 36        | 0.33%   |
| WDC WDS240G2G0A-00JH30 240GB       | 35        | 0.32%   |
| Kingston SUV500MS240G 240GB        | 35        | 0.32%   |
| WDC WD40EFRX-68N32N0 4TB           | 34        | 0.31%   |
| Samsung SSD 970 EVO Plus 500GB     | 34        | 0.31%   |
| WDC WDS120G2G0A-00JH30 120GB       | 32        | 0.29%   |
| A-DATA SU650 120GB                 | 32        | 0.29%   |
| Samsung SSD 840 EVO 120GB          | 31        | 0.28%   |
| Crucial CT1000MX500SSD1 1TB        | 31        | 0.28%   |
| Samsung SSD 850 EVO 120GB          | 30        | 0.27%   |
| Kingston SA400S37480G 480GB        | 30        | 0.27%   |
| PNY CS900 120GB SSD                | 29        | 0.27%   |
| SanDisk SDSSDA120G 120GB           | 28        | 0.26%   |
| WDC WD30EFRX-68EUZN0 3TB           | 27        | 0.25%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                             | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC                                | 1041      | 2349   | 31.91%  |
| Seagate                            | 1012      | 2119   | 31.02%  |
| Toshiba                            | 357       | 670    | 10.94%  |
| Hitachi                            | 249       | 488    | 7.63%   |
| HGST                               | 158       | 416    | 4.84%   |
| Samsung Electronics                | 148       | 208    | 4.54%   |
| NVMe                               | 65        | 87     | 1.99%   |
| Hewlett-Packard                    | 50        | 211    | 1.53%   |
| Fujitsu                            | 30        | 40     | 0.92%   |
| Maxtor                             | 25        | 31     | 0.77%   |
| Apple                              | 18        | 21     | 0.55%   |
| OPENBSD                            | 16        | 23     | 0.49%   |
| Dell                               | 12        | 66     | 0.37%   |
| LSI                                | 8         | 14     | 0.25%   |
| HPE                                | 7         | 29     | 0.21%   |
| Generic                            | 5         | 5      | 0.15%   |
| USB                                | 4         | 4      | 0.12%   |
| Adaptec                            | 4         | 14     | 0.12%   |
| NETAPP                             | 3         | 6      | 0.09%   |
| Lexar                              | 3         | 3      | 0.09%   |
| JetFlash                           | 3         | 3      | 0.09%   |
| HPT                                | 3         | 35     | 0.09%   |
| WD MediaMax                        | 2         | 5      | 0.06%   |
| StoreJet                           | 2         | 2      | 0.06%   |
| Multiple                           | 2         | 2      | 0.06%   |
| MaxDigital                         | 2         | 2      | 0.06%   |
| LSILOGIC                           | 2         | 5      | 0.06%   |
| Lenovo                             | 2         | 4      | 0.06%   |
| IBM/Hitachi                        | 2         | 2      | 0.06%   |
| IBM                                | 2         | 2      | 0.06%   |
| Cisco                              | 2         | 4      | 0.06%   |
| China                              | 2         | 2      | 0.06%   |
| ASMT                               | 2         | 2      | 0.06%   |
| Areca                              | 2         | 3      | 0.06%   |
| UFD 2.0                            | 1         | 1      | 0.03%   |
| SYNOLOGY                           | 1         | 1      | 0.03%   |
| SSDPR-CX                           | 1         | 1      | 0.03%   |
| SABRENT                            | 1         | 1      | 0.03%   |
| QUANTUM                            | 1         | 2      | 0.03%   |
| Product:              USB DISK 3.0 | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1015      | 1566   | 18.24%  |
| Kingston            | 655       | 911    | 11.77%  |
| SanDisk             | 427       | 561    | 7.67%   |
| Crucial             | 425       | 627    | 7.64%   |
| Transcend           | 368       | 532    | 6.61%   |
| Intel               | 331       | 555    | 5.95%   |
| WDC                 | 196       | 302    | 3.52%   |
| Hoodisk             | 177       | 253    | 3.18%   |
| A-DATA Technology   | 159       | 214    | 2.86%   |
| China               | 131       | 186    | 2.35%   |
| Phison              | 119       | 158    | 2.14%   |
| Micron Technology   | 82        | 130    | 1.47%   |
| OCZ                 | 79        | 106    | 1.42%   |
| FORESEE             | 76        | 109    | 1.37%   |
| SPCC                | 73        | 109    | 1.31%   |
| Toshiba             | 71        | 97     | 1.28%   |
| PNY                 | 71        | 116    | 1.28%   |
| Apacer              | 65        | 74     | 1.17%   |
| Hewlett-Packard     | 55        | 86     | 0.99%   |
| SK hynix            | 50        | 63     | 0.9%    |
| Protectli           | 50        | 81     | 0.9%    |
| Intenso             | 50        | 80     | 0.9%    |
| Dogfish             | 49        | 78     | 0.88%   |
| Corsair             | 45        | 61     | 0.81%   |
| KingSpec            | 39        | 48     | 0.7%    |
| Innodisk            | 39        | 47     | 0.7%    |
| Patriot             | 36        | 51     | 0.65%   |
| BIWIN               | 36        | 52     | 0.65%   |
| LITEON              | 35        | 50     | 0.63%   |
| LITEONIT            | 33        | 37     | 0.59%   |
| Apple               | 31        | 33     | 0.56%   |
| NVMe                | 29        | 34     | 0.52%   |
| Plextor             | 24        | 33     | 0.43%   |
| Seagate             | 20        | 38     | 0.36%   |
| Kston               | 20        | 25     | 0.36%   |
| Goodram             | 20        | 32     | 0.36%   |
| Gigabyte Technology | 19        | 28     | 0.34%   |
| ATP                 | 16        | 16     | 0.29%   |
| Mushkin             | 15        | 20     | 0.27%   |
| KingDian            | 15        | 22     | 0.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 5069      | 8078   | 56.69%  |
| HDD  | 2677      | 6898   | 29.94%  |
| NVMe | 1195      | 1821   | 13.37%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 6934      | 14976  | 85.3%   |
| NVMe | 1195      | 1821   | 14.7%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 5927      | 9715   | 73.13%  |
| 0.51-1.0        | 1235      | 2099   | 15.24%  |
| 1.01-2.0        | 406       | 966    | 5.01%   |
| 3.01-4.0        | 200       | 733    | 2.47%   |
| 4.01-10.0       | 170       | 840    | 2.1%    |
| 2.01-3.0        | 122       | 426    | 1.51%   |
| 10.01-20.0      | 39        | 188    | 0.48%   |
| 20.01-50.0      | 3         | 6      | 0.04%   |
| More than 100.0 | 2         | 2      | 0.02%   |
| 0               | 1         | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 3210      | 36.91%  |
| 251-500        | 1384      | 15.91%  |
| 1-20           | 1372      | 15.78%  |
| 51-100         | 943       | 10.84%  |
| 21-50          | 823       | 9.46%   |
| 501-1000       | 611       | 7.03%   |
| 1001-2000      | 164       | 1.89%   |
| More than 3000 | 88        | 1.01%   |
| Unknown        | 62        | 0.71%   |
| 2001-3000      | 40        | 0.46%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 7535      | 87.35%  |
| 21-50          | 523       | 6.06%   |
| 51-100         | 208       | 2.41%   |
| 101-250        | 139       | 1.61%   |
| Unknown        | 62        | 0.72%   |
| 251-500        | 57        | 0.66%   |
| 501-1000       | 41        | 0.48%   |
| More than 3000 | 25        | 0.29%   |
| 1001-2000      | 22        | 0.26%   |
| 2001-3000      | 13        | 0.15%   |
| 0              | 1         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 24        | 38     | 1.76%   |
| Kingston SV300S37A120G 120GB        | 15        | 17     | 1.1%    |
| HGST HTS725050A7E630 500GB          | 14        | 29     | 1.03%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 13        | 16     | 0.95%   |
| Seagate ST500LT012-9WS142 500GB     | 12        | 17     | 0.88%   |
| Seagate ST500LM021-1KJ152 500GB     | 11        | 11     | 0.81%   |
| Seagate ST500LT012-1DG142 500GB     | 10        | 11     | 0.73%   |
| Toshiba MQ01ABD100 1TB              | 9         | 9      | 0.66%   |
| Seagate ST3500413AS 500GB           | 9         | 23     | 0.66%   |
| Seagate ST9500420AS 500GB           | 8         | 11     | 0.59%   |
| Seagate ST3500418AS 500GB           | 8         | 17     | 0.59%   |
| Kingston SV300S37A60G 64GB          | 8         | 10     | 0.59%   |
| Kingston SMS200S3120G 120GB         | 8         | 9      | 0.59%   |
| Apacer 16GB SATA Flash Drive        | 8         | 10     | 0.59%   |
| WDC WDS240G2G0A-00JH30 240GB        | 7         | 8      | 0.51%   |
| WDC WD30EFRX-68EUZN0 3TB            | 7         | 19     | 0.51%   |
| Toshiba MQ01ABF050 500GB            | 7         | 9      | 0.51%   |
| Seagate ST9500325AS 500GB           | 7         | 8      | 0.51%   |
| Seagate ST320LT007-9ZV142 320GB     | 7         | 7      | 0.51%   |
| Samsung Electronics HD501LJ 500GB   | 7         | 9      | 0.51%   |
| Intel SSDSA2M080G2GC 80GB           | 7         | 8      | 0.51%   |
| WDC WD20EFRX-68EUZN0 2TB            | 6         | 14     | 0.44%   |
| Seagate ST9320423AS 320GB           | 6         | 6      | 0.44%   |
| Seagate ST9320325AS 320GB           | 6         | 6      | 0.44%   |
| Seagate ST3160815AS 160GB           | 6         | 7      | 0.44%   |
| Samsung Electronics SSD 870 EVO 1TB | 6         | 10     | 0.44%   |
| Kingston SMS200S360G 64GB           | 6         | 6      | 0.44%   |
| Intel SSDSA2M160G2GC 160GB          | 6         | 8      | 0.44%   |
| Hitachi HTS541612J9SA00 120GB       | 6         | 7      | 0.44%   |
| Crucial CT525MX300SSD1 528GB        | 6         | 10     | 0.44%   |
| Crucial CT275MX300SSD1 275GB        | 6         | 9      | 0.44%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 5         | 5      | 0.37%   |
| WDC WD40EFRX-68WT0N0 4TB            | 5         | 13     | 0.37%   |
| Toshiba MQ01ABD075 752GB            | 5         | 5      | 0.37%   |
| Seagate ST380815AS 80GB             | 5         | 5      | 0.37%   |
| Seagate ST3250310AS 250GB           | 5         | 5      | 0.37%   |
| Seagate ST31000528AS 1TB            | 5         | 6      | 0.37%   |
| Seagate ST2000DL003-9VT166 2TB      | 5         | 16     | 0.37%   |
| Seagate ST1000LM035-1RK172 1TB      | 5         | 6      | 0.37%   |
| Samsung Electronics HM160HI 160GB   | 5         | 5      | 0.37%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 305       | 450    | 23.19%  |
| WDC                 | 250       | 380    | 19.01%  |
| Hitachi             | 106       | 145    | 8.06%   |
| Samsung Electronics | 105       | 142    | 7.98%   |
| Toshiba             | 93        | 140    | 7.07%   |
| Intel               | 77        | 104    | 5.86%   |
| Kingston            | 72        | 88     | 5.48%   |
| HGST                | 40        | 72     | 3.04%   |
| Crucial             | 40        | 60     | 3.04%   |
| SanDisk             | 29        | 45     | 2.21%   |
| A-DATA Technology   | 18        | 27     | 1.37%   |
| OCZ                 | 17        | 21     | 1.29%   |
| Micron Technology   | 17        | 23     | 1.29%   |
| Apacer              | 13        | 15     | 0.99%   |
| SK hynix            | 11        | 15     | 0.84%   |
| Maxtor              | 11        | 15     | 0.84%   |
| Corsair             | 10        | 15     | 0.76%   |
| China               | 8         | 9      | 0.61%   |
| LITEON              | 7         | 8      | 0.53%   |
| Hewlett-Packard     | 6         | 12     | 0.46%   |
| Fujitsu             | 6         | 9      | 0.46%   |
| Apple               | 6         | 6      | 0.46%   |
| Dogfish             | 5         | 11     | 0.38%   |
| Transcend           | 4         | 8      | 0.3%    |
| VisionTek           | 3         | 7      | 0.23%   |
| SPCC                | 3         | 5      | 0.23%   |
| Phison              | 3         | 3      | 0.23%   |
| KingDian            | 3         | 3      | 0.23%   |
| Intenso             | 3         | 3      | 0.23%   |
| BIWIN               | 3         | 5      | 0.23%   |
| SSSTC               | 2         | 2      | 0.15%   |
| SMI                 | 2         | 2      | 0.15%   |
| Plextor             | 2         | 2      | 0.15%   |
| MyDigitalSSD        | 2         | 4      | 0.15%   |
| KingSpec            | 2         | 2      | 0.15%   |
| HP Phison           | 2         | 2      | 0.15%   |
| ZTC                 | 1         | 3      | 0.08%   |
| XrayDisk            | 1         | 1      | 0.08%   |
| XPG                 | 1         | 1      | 0.08%   |
| Wintec              | 1         | 1      | 0.08%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor               | Computers | Drives | Percent |
|----------------------|-----------|--------|---------|
| Seagate              | 304       | 449    | 35.31%  |
| WDC                  | 236       | 363    | 27.41%  |
| Hitachi              | 106       | 145    | 12.31%  |
| Toshiba              | 85        | 128    | 9.87%   |
| Samsung Electronics  | 57        | 72     | 6.62%   |
| HGST                 | 40        | 72     | 4.65%   |
| Maxtor               | 11        | 15     | 1.28%   |
| Fujitsu              | 6         | 9      | 0.7%    |
| Hewlett-Packard      | 5         | 10     | 0.58%   |
| Apple                | 4         | 4      | 0.46%   |
| WD MediaMax          | 1         | 3      | 0.12%   |
| InnoLite             | 1         | 1      | 0.12%   |
| IBM/Hitachi          | 1         | 1      | 0.12%   |
| HPE                  | 1         | 3      | 0.12%   |
| ExcelStor Technology | 1         | 2      | 0.12%   |
| China                | 1         | 1      | 0.12%   |
| Cactus               | 1         | 1      | 0.12%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 810       | 1279   | 64.18%  |
| SSD  | 439       | 600    | 34.79%  |
| NVMe | 13        | 18     | 1.03%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Samsung Electronics MZYLN256HCHP-000L2 256GB | 2         | 2      | 7.69%   |
| WDC WD6400AARS-00Y5B1 640GB                  | 1         | 2      | 3.85%   |
| WDC WD3200BPVT-16JJ5T0 320GB                 | 1         | 1      | 3.85%   |
| WDC WD3200AAJS-00YZCA0 320GB                 | 1         | 1      | 3.85%   |
| WDC WD20EARS-00MVWB0 2TB                     | 1         | 1      | 3.85%   |
| WDC WD10SPZX-00Z10T0 1TB                     | 1         | 1      | 3.85%   |
| Transcend TS32GSSD370S 32GB                  | 1         | 1      | 3.85%   |
| Toshiba MG05ACA800E 8TB                      | 1         | 1      | 3.85%   |
| SK hynix SC308 SATA 256GB                    | 1         | 1      | 3.85%   |
| Seagate ST4000NM0025 4TB                     | 1         | 2      | 3.85%   |
| Seagate ST3500418AS 500GB                    | 1         | 2      | 3.85%   |
| SanDisk pSSD 16GB                            | 1         | 1      | 3.85%   |
| Samsung Electronics SSD 960 EVO 250GB        | 1         | 1      | 3.85%   |
| Samsung Electronics HM250JI 250GB            | 1         | 1      | 3.85%   |
| Samsung Electronics HD204UI 2TB              | 1         | 2      | 3.85%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB   | 1         | 1      | 3.85%   |
| Maxtor 6E040L0 41GB                          | 1         | 1      | 3.85%   |
| Kingston SV300S37A60G 64GB                   | 1         | 1      | 3.85%   |
| Intel SSDSC2BW120H6 120GB                    | 1         | 1      | 3.85%   |
| HPE MK000480GWUGF 480GB                      | 1         | 1      | 3.85%   |
| Hitachi HUS724040ALE641 4TB                  | 1         | 14     | 3.85%   |
| Hitachi HTS545025B9A300 250GB                | 1         | 1      | 3.85%   |
| HGST HTS725050A7E630 500GB                   | 1         | 1      | 3.85%   |
| Crucial M4-CT256M4SSD1 256GB                 | 1         | 1      | 3.85%   |
| Crucial CT250P2SSD8 250GB                    | 1         | 1      | 3.85%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 6      | 19.23%  |
| Samsung Electronics | 5         | 6      | 19.23%  |
| Seagate             | 2         | 4      | 7.69%   |
| Hitachi             | 2         | 15     | 7.69%   |
| Crucial             | 2         | 2      | 7.69%   |
| Transcend           | 1         | 1      | 3.85%   |
| Toshiba             | 1         | 1      | 3.85%   |
| SK hynix            | 1         | 1      | 3.85%   |
| SanDisk             | 1         | 1      | 3.85%   |
| Micron Technology   | 1         | 1      | 3.85%   |
| Maxtor              | 1         | 1      | 3.85%   |
| Kingston            | 1         | 1      | 3.85%   |
| Intel               | 1         | 1      | 3.85%   |
| HPE                 | 1         | 1      | 3.85%   |
| HGST                | 1         | 1      | 3.85%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 6740      | 14162  | 80.87%  |
| Malfunc  | 1233      | 1897   | 14.79%  |
| Detected | 335       | 695    | 4.02%   |
| Failed   | 26        | 43     | 0.31%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 6315      | 62.93%  |
| AMD                              | 1412      | 14.07%  |
| Samsung Electronics              | 497       | 4.95%   |
| Broadcom / LSI                   | 326       | 3.25%   |
| SanDisk                          | 200       | 1.99%   |
| ASMedia Technology               | 162       | 1.61%   |
| Marvell Technology Group         | 107       | 1.07%   |
| Phison Electronics               | 100       | 1%      |
| Nvidia                           | 88        | 0.88%   |
| Kingston Technology Company      | 86        | 0.86%   |
| Silicon Motion                   | 84        | 0.84%   |
| Hewlett-Packard                  | 72        | 0.72%   |
| SK hynix                         | 62        | 0.62%   |
| Micron/Crucial Technology        | 62        | 0.62%   |
| JMicron Technology               | 53        | 0.53%   |
| Toshiba                          | 38        | 0.38%   |
| ADATA Technology                 | 36        | 0.36%   |
| KIOXIA                           | 35        | 0.35%   |
| Chelsio Communications           | 29        | 0.29%   |
| Adaptec                          | 28        | 0.28%   |
| Micron Technology                | 27        | 0.27%   |
| Transcend                        | 25        | 0.25%   |
| Silicon Image                    | 23        | 0.23%   |
| VIA Technologies                 | 21        | 0.21%   |
| Seagate Technology               | 15        | 0.15%   |
| Realtek Semiconductor            | 13        | 0.13%   |
| Shenzhen Longsys Electronics     | 12        | 0.12%   |
| Silicon Integrated Systems [SiS] | 10        | 0.1%    |
| Solid State Storage Technology   | 8         | 0.08%   |
| Areca Technology                 | 8         | 0.08%   |
| Union Memory (Shenzhen)          | 7         | 0.07%   |
| MAXIO Technology (Hangzhou)      | 7         | 0.07%   |
| Lite-On Technology               | 7         | 0.07%   |
| Lenovo                           | 7         | 0.07%   |
| Integrated Technology Express    | 6         | 0.06%   |
| Biwin Storage Technology         | 6         | 0.06%   |
| 3ware                            | 6         | 0.06%   |
| Dell                             | 5         | 0.05%   |
| ATP ELECTRONICS                  | 5         | 0.05%   |
| ULi Electronics                  | 4         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 942       | 8.2%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 578       | 5.03%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 472       | 4.11%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 328       | 2.86%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 319       | 2.78%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 300       | 2.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 297       | 2.59%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 286       | 2.49%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 255       | 2.22%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 235       | 2.05%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 196       | 1.71%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 195       | 1.7%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 188       | 1.64%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 185       | 1.61%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 175       | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 165       | 1.44%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 164       | 1.43%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 160       | 1.39%   |
| Unknown                                                                          | 154       | 1.34%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 153       | 1.33%   |
| AMD 400 Series Chipset SATA Controller                                           | 144       | 1.25%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 139       | 1.21%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 137       | 1.19%   |
| AMD FCH SATA Controller [IDE mode]                                               | 126       | 1.1%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 121       | 1.05%   |
| Intel SATA Controller [RAID mode]                                                | 118       | 1.03%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 104       | 0.91%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 103       | 0.9%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 93        | 0.81%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 93        | 0.81%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 91        | 0.79%   |
| Intel Comet Lake SATA AHCI Controller                                            | 89        | 0.77%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 84        | 0.73%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                     | 83        | 0.72%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 82        | 0.71%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 81        | 0.71%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 79        | 0.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 79        | 0.69%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                                 | 76        | 0.66%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 72        | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 6779      | 66.71%  |
| NVMe | 1340      | 13.19%  |
| IDE  | 1217      | 11.98%  |
| RAID | 584       | 5.75%   |
| SAS  | 160       | 1.57%   |
| SCSI | 82        | 0.81%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Intel              | 6693      | 79.85%  |
| AMD                | 1550      | 18.49%  |
| ARM                | 97        | 1.16%   |
| Unknown            | 24        | 0.29%   |
| PowerPC            | 4         | 0.05%   |
| VIA                | 3         | 0.04%   |
| Rockchip           | 2         | 0.02%   |
| Sun                | 1         | 0.01%   |
| Research           | 1         | 0.01%   |
| Motorola           | 1         | 0.01%   |
| IBM                | 1         | 0.01%   |
| i                  | 1         | 0.01%   |
| Broadcom           | 1         | 0.01%   |
| Baikal Electronics | 1         | 0.01%   |
| 123456789ABC       | 1         | 0.01%   |
| 11th               | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| AMD GX-412TC SOC                         | 248       | 2.93%   |
| Intel Celeron J4125 CPU @ 2.00GHz        | 164       | 1.94%   |
| Intel Celeron CPU J1900 @ 1.99GHz        | 152       | 1.8%    |
| Intel Celeron CPU J3160 @ 1.60GHz        | 151       | 1.78%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 82        | 0.97%   |
| Intel Celeron N5105 @ 2.00GHz            | 70        | 0.83%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 64        | 0.76%   |
| Intel Celeron CPU J3455 @ 1.50GHz        | 63        | 0.74%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 61        | 0.72%   |
| Intel Core i5-6500 CPU @ 3.20GHz         | 61        | 0.72%   |
| Intel Core i5-4570 CPU @ 3.20GHz         | 54        | 0.64%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 54        | 0.64%   |
| AMD GX-420CA SOC with Radeon HD Graphics | 51        | 0.6%    |
| Intel Core i7-8550U CPU @ 1.80GHz        | 47        | 0.56%   |
| Intel Atom CPU D525 @ 1.80GHz            | 47        | 0.56%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 45        | 0.53%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 44        | 0.52%   |
| Intel Core i3-7100U CPU @ 2.40GHz        | 44        | 0.52%   |
| Intel Celeron J4105 CPU @ 1.50GHz        | 43        | 0.51%   |
| Intel Core 2 Duo                         | 42        | 0.5%    |
| Intel Core i5-5200U CPU @ 2.20GHz        | 41        | 0.48%   |
| Intel Core i5-3320M CPU @ 2.60GHz        | 41        | 0.48%   |
| Intel Core i7-3770 CPU @ 3.40GHz         | 40        | 0.47%   |
| AMD RX-427BB with AMD Radeon R7 Graphics | 40        | 0.47%   |
| Intel Core i5-5300U CPU @ 2.30GHz        | 39        | 0.46%   |
| Intel Celeron CPU N3450 @ 1.10GHz        | 39        | 0.46%   |
| Intel Celeron CPU N3150 @ 1.60GHz        | 39        | 0.46%   |
| Intel Core i5-6300U CPU @ 2.40GHz        | 38        | 0.45%   |
| Intel Celeron CPU 3865U @ 1.80GHz        | 38        | 0.45%   |
| Intel Pentium CPU N3700 @ 1.60GHz        | 36        | 0.43%   |
| Intel CPU Version                        | 36        | 0.43%   |
| AMD GX-415GA SOC with Radeon HD Graphics | 36        | 0.43%   |
| ARM Cortex-A72 r0p3                      | 35        | 0.41%   |
| Intel Xeon                               | 34        | 0.4%    |
| Intel Atom CPU C3558 @ 2.20GHz           | 34        | 0.4%    |
| Intel Core i5-6200U CPU @ 2.30GHz        | 33        | 0.39%   |
| AMD Ryzen 5 3600 6-Core Processor        | 33        | 0.39%   |
| Intel Core i5-2400 CPU @ 3.10GHz         | 32        | 0.38%   |
| Intel Core i5-10210U CPU @ 1.60GHz       | 32        | 0.38%   |
| Intel Atom CPU E3845 @ 1.91GHz           | 32        | 0.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1607      | 19.07%  |
| Intel Celeron           | 1204      | 14.29%  |
| Intel Xeon              | 931       | 11.05%  |
| Intel Core i7           | 902       | 10.7%   |
| Intel Core i3           | 648       | 7.69%   |
| Intel Atom              | 394       | 4.68%   |
| AMD GX                  | 394       | 4.68%   |
| Other                   | 267       | 3.17%   |
| Intel Core 2 Duo        | 240       | 2.85%   |
| Intel Pentium           | 224       | 2.66%   |
| AMD Ryzen 5             | 195       | 2.31%   |
| AMD Ryzen 7             | 180       | 2.14%   |
| ARM Cortex              | 89        | 1.06%   |
| AMD FX                  | 80        | 0.95%   |
| AMD Ryzen 3             | 61        | 0.72%   |
| Intel Core 2 Quad       | 59        | 0.7%    |
| AMD G                   | 57        | 0.68%   |
| Intel Pentium Silver    | 56        | 0.66%   |
| Intel Pentium Dual-Core | 52        | 0.62%   |
| AMD Ryzen 9             | 48        | 0.57%   |
| AMD EPYC                | 43        | 0.51%   |
| Intel Core 2            | 34        | 0.4%    |
| AMD Ryzen Embedded      | 30        | 0.36%   |
| AMD Athlon              | 30        | 0.36%   |
| Intel Pentium 4         | 27        | 0.32%   |
| AMD Ryzen 5 PRO         | 27        | 0.32%   |
| Intel Pentium Gold      | 25        | 0.3%    |
| Intel Genuine           | 25        | 0.3%    |
| AMD A4                  | 25        | 0.3%    |
| Intel Xeon Silver       | 24        | 0.28%   |
| AMD A6                  | 24        | 0.28%   |
| AMD A8                  | 23        | 0.27%   |
| AMD A10                 | 23        | 0.27%   |
| Intel Core i9           | 22        | 0.26%   |
| AMD Phenom II X4        | 22        | 0.26%   |
| AMD Opteron             | 21        | 0.25%   |
| AMD Athlon 64 X2        | 21        | 0.25%   |
| AMD E                   | 20        | 0.24%   |
| Intel Pentium M         | 19        | 0.23%   |
| Intel Pentium Dual      | 19        | 0.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 3773      | 44.76%  |
| 2       | 2604      | 30.89%  |
| Unknown | 493       | 5.85%   |
| 8       | 485       | 5.75%   |
| 6       | 361       | 4.28%   |
| 16      | 225       | 2.67%   |
| 12      | 218       | 2.59%   |
| 1       | 131       | 1.55%   |
| 24      | 44        | 0.52%   |
| 10      | 23        | 0.27%   |
| 32      | 22        | 0.26%   |
| 20      | 16        | 0.19%   |
| 64      | 8         | 0.09%   |
| 3       | 7         | 0.08%   |
| 48      | 5         | 0.06%   |
| 28      | 4         | 0.05%   |
| 14      | 4         | 0.05%   |
| 36      | 3         | 0.04%   |
| 128     | 2         | 0.02%   |
| 40      | 1         | 0.01%   |
| 11      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 7830      | 93.36%  |
| 2       | 327       | 3.9%    |
| Unknown | 224       | 2.67%   |
| 4       | 5         | 0.06%   |
| 8       | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 4442      | 52.86%  |
| 2       | 3411      | 40.59%  |
| Unknown | 550       | 6.54%   |
| 4       | 1         | 0.01%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 1057      | 12.55%  |
| Haswell         | 894       | 10.61%  |
| Silvermont      | 687       | 8.16%   |
| IvyBridge       | 648       | 7.69%   |
| SandyBridge     | 544       | 6.46%   |
| Skylake         | 503       | 5.97%   |
| Unknown         | 346       | 4.11%   |
| Penryn          | 341       | 4.05%   |
| Goldmont plus   | 325       | 3.86%   |
| Puma            | 310       | 3.68%   |
| Broadwell       | 292       | 3.47%   |
| Goldmont        | 242       | 2.87%   |
| Westmere        | 234       | 2.78%   |
| Zen 2           | 197       | 2.34%   |
| Core            | 190       | 2.26%   |
| Bonnell         | 173       | 2.05%   |
| Zen             | 168       | 1.99%   |
| Zen+            | 160       | 1.9%    |
| Jaguar          | 145       | 1.72%   |
| CometLake       | 133       | 1.58%   |
| Nehalem         | 127       | 1.51%   |
| Piledriver      | 106       | 1.26%   |
| Bobcat          | 94        | 1.12%   |
| Zen 3           | 91        | 1.08%   |
| K10             | 91        | 1.08%   |
| TigerLake       | 52        | 0.62%   |
| Steamroller     | 52        | 0.62%   |
| NetBurst        | 46        | 0.55%   |
| Excavator       | 41        | 0.49%   |
| K8 Hammer       | 38        | 0.45%   |
| P6              | 37        | 0.44%   |
| IceLake         | 27        | 0.32%   |
| Bulldozer       | 14        | 0.17%   |
| K10 Llano       | 11        | 0.13%   |
| Geode           | 4         | 0.05%   |
| K8 & K10 hybrid | 3         | 0.04%   |
| K6              | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 4954      | 59.9%   |
| AMD                                          | 1286      | 15.55%  |
| Nvidia                                       | 1092      | 13.2%   |
| Matrox Electronics Systems                   | 494       | 5.97%   |
| ASPEED Technology                            | 411       | 4.97%   |
| XGI Technology (eXtreme Graphics Innovation) | 8         | 0.1%    |
| VIA Technologies                             | 6         | 0.07%   |
| Silicon Integrated Systems [SiS]             | 6         | 0.07%   |
| S3 Graphics                                  | 4         | 0.05%   |
| Silicon Motion                               | 2         | 0.02%   |
| Cirrus Logic                                 | 2         | 0.02%   |
| Tseng Labs                                   | 1         | 0.01%   |
| Trident Microsystems                         | 1         | 0.01%   |
| NVidia / SGS Thomson (Joint Venture)         | 1         | 0.01%   |
| Huawei Technologies                          | 1         | 0.01%   |
| ATI                                          | 1         | 0.01%   |
| 3DLabs                                       | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                                 | 411       | 4.87%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 339       | 4.02%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 319       | 3.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 311       | 3.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 292       | 3.46%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 283       | 3.36%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 221       | 2.62%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 211       | 2.5%    |
| Intel HD Graphics 620                                                                    | 202       | 2.4%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 194       | 2.3%    |
| Intel HD Graphics 530                                                                    | 190       | 2.25%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 159       | 1.89%   |
| Intel HD Graphics 500                                                                    | 158       | 1.87%   |
| Intel HD Graphics 5500                                                                   | 142       | 1.68%   |
| Intel UHD Graphics 620                                                                   | 140       | 1.66%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 130       | 1.54%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 129       | 1.53%   |
| Matrox Electronics Systems G200eR2                                                       | 106       | 1.26%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 102       | 1.21%   |
| Intel HD Graphics 630                                                                    | 98        | 1.16%   |
| Intel JasperLake [UHD Graphics]                                                          | 91        | 1.08%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 89        | 1.06%   |
| Intel Core Processor Integrated Graphics Controller                                      | 86        | 1.02%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 85        | 1.01%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 83        | 0.98%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 82        | 0.97%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 81        | 0.96%   |
| AMD ES1000                                                                               | 76        | 0.9%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 76        | 0.9%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 73        | 0.87%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 69        | 0.82%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 67        | 0.79%   |
| AMD Renoir                                                                               | 67        | 0.79%   |
| Matrox Electronics Systems MGA G200EH                                                    | 66        | 0.78%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 66        | 0.78%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 62        | 0.74%   |
| Intel HD Graphics 610                                                                    | 60        | 0.71%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 55        | 0.65%   |
| AMD Kabini [Radeon HD 8400E]                                                             | 51        | 0.6%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 50        | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| 1 x Intel                                | 4263      | 50.63%  |
| 1 x AMD                                  | 1148      | 13.63%  |
| 1 x Nvidia                               | 758       | 9%      |
| Other                                    | 578       | 6.86%   |
| 1 x Matrox                               | 489       | 5.81%   |
| 1 x ASPEED                               | 383       | 4.55%   |
| 2 x Intel                                | 300       | 3.56%   |
| Intel + Nvidia                           | 289       | 3.43%   |
| Intel + AMD                              | 82        | 0.97%   |
| 2 x AMD                                  | 28        | 0.33%   |
| AMD + Nvidia                             | 26        | 0.31%   |
| Intel + ASPEED                           | 18        | 0.21%   |
| 2 x Nvidia                               | 9         | 0.11%   |
| 1 x XGI                                  | 8         | 0.1%    |
| Nvidia + ASPEED                          | 8         | 0.1%    |
| 1 x VIA                                  | 6         | 0.07%   |
| 1 x SiS                                  | 6         | 0.07%   |
| 1 x S3 Graphics                          | 4         | 0.05%   |
| AMD + ASPEED                             | 3         | 0.04%   |
| 1 x Silicon Motion                       | 2         | 0.02%   |
| Intel + Matrox                           | 2         | 0.02%   |
| 1 x Cirrus Logic                         | 2         | 0.02%   |
| 2 x Intel + 1 x Nvidia                   | 1         | 0.01%   |
| 1 x Tseng Labs                           | 1         | 0.01%   |
| 1 x Trident Microsystems                 | 1         | 0.01%   |
| 1 x NVidia / SGS Thomson (Joint Venture) | 1         | 0.01%   |
| Nvidia + Matrox                          | 1         | 0.01%   |
| Nvidia + Huawei Technologies             | 1         | 0.01%   |
| AMD + Matrox                             | 1         | 0.01%   |
| 1 x 3DLabs                               | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 7154      | 84.98%  |
| Unknown     | 707       | 8.4%    |
| Proprietary | 557       | 6.62%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 7495      | 88.77%  |
| 1.01-2.0   | 259       | 3.07%   |
| 0.01-0.5   | 200       | 2.37%   |
| 0.51-1.0   | 161       | 1.91%   |
| 3.01-4.0   | 140       | 1.66%   |
| 7.01-8.0   | 94        | 1.11%   |
| 5.01-6.0   | 57        | 0.68%   |
| 2.01-3.0   | 22        | 0.26%   |
| 8.01-16.0  | 14        | 0.17%   |
| 4.01-5.0   | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 311       | 11.26%  |
| Samsung Electronics     | 309       | 11.18%  |
| AU Optronics            | 299       | 10.82%  |
| Dell                    | 193       | 6.99%   |
| Chimei Innolux          | 191       | 6.91%   |
| BOE                     | 175       | 6.33%   |
| Goldstar                | 152       | 5.5%    |
| Lenovo                  | 124       | 4.49%   |
| Hewlett-Packard         | 89        | 3.22%   |
| Acer                    | 88        | 3.18%   |
| BenQ                    | 74        | 2.68%   |
| Apple                   | 71        | 2.57%   |
| AOC                     | 69        | 2.5%    |
| Philips                 | 68        | 2.46%   |
| Ancor Communications    | 59        | 2.14%   |
| Iiyama                  | 34        | 1.23%   |
| Sharp                   | 33        | 1.19%   |
| Chi Mei Optoelectronics | 33        | 1.19%   |
| ViewSonic               | 32        | 1.16%   |
| InfoVision              | 23        | 0.83%   |
| ASUSTek Computer        | 22        | 0.8%    |
| LG Electronics          | 21        | 0.76%   |
| Sony                    | 20        | 0.72%   |
| PANDA                   | 17        | 0.62%   |
| NEC Computers           | 17        | 0.62%   |
| Eizo                    | 16        | 0.58%   |
| Fujitsu Siemens         | 14        | 0.51%   |
| LG Philips              | 13        | 0.47%   |
| Toshiba                 | 12        | 0.43%   |
| HannStar                | 12        | 0.43%   |
| Vizio                   | 9         | 0.33%   |
| Unknown                 | 9         | 0.33%   |
| Panasonic               | 9         | 0.33%   |
| Sceptre Tech            | 8         | 0.29%   |
| MSI                     | 7         | 0.25%   |
| LGD                     | 7         | 0.25%   |
| CSO                     | 7         | 0.25%   |
| Idek Iiyama             | 6         | 0.22%   |
| CPT                     | 6         | 0.22%   |
| JDI                     | 5         | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch        | 21        | 0.74%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch          | 15        | 0.53%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch          | 11        | 0.39%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch     | 11        | 0.39%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch              | 10        | 0.35%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch            | 10        | 0.35%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch              | 9         | 0.32%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch              | 9         | 0.32%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch           | 9         | 0.32%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch        | 9         | 0.32%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch | 8         | 0.28%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch | 8         | 0.28%   |
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                | 8         | 0.28%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch         | 8         | 0.28%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch          | 8         | 0.28%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch             | 8         | 0.28%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch              | 8         | 0.28%   |
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch              | 8         | 0.28%   |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                    | 8         | 0.28%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch     | 8         | 0.28%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch      | 8         | 0.28%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch        | 8         | 0.28%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch       | 8         | 0.28%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch        | 8         | 0.28%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch         | 7         | 0.25%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch              | 7         | 0.25%   |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch              | 7         | 0.25%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch           | 7         | 0.25%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 310x170mm 13.9-inch     | 7         | 0.25%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 310x170mm 13.9-inch      | 7         | 0.25%   |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                | 7         | 0.25%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch        | 7         | 0.25%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch       | 7         | 0.25%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch | 6         | 0.21%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch         | 6         | 0.21%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch          | 6         | 0.21%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch              | 6         | 0.21%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch           | 6         | 0.21%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 340x190mm 15.3-inch      | 6         | 0.21%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 280x160mm 12.7-inch     | 6         | 0.21%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1055      | 38.89%  |
| 1366x768 (WXGA)    | 558       | 20.57%  |
| 3840x2160 (4K)     | 141       | 5.2%    |
| 2560x1440 (QHD)    | 139       | 5.12%   |
| 1600x900 (HD+)     | 132       | 4.87%   |
| 1280x1024 (SXGA)   | 110       | 4.05%   |
| 1280x800 (WXGA)    | 104       | 3.83%   |
| 1920x1200 (WUXGA)  | 76        | 2.8%    |
| 1680x1050 (WSXGA+) | 71        | 2.62%   |
| 1440x900 (WXGA+)   | 70        | 2.58%   |
| 2560x1080          | 29        | 1.07%   |
| 3440x1440          | 28        | 1.03%   |
| 1024x600           | 25        | 0.92%   |
| Unknown            | 24        | 0.88%   |
| 1024x768 (XGA)     | 16        | 0.59%   |
| 1360x768           | 13        | 0.48%   |
| 1920x540           | 11        | 0.41%   |
| 1600x1200          | 11        | 0.41%   |
| 3200x1800 (QHD+)   | 10        | 0.37%   |
| 2560x1600          | 9         | 0.33%   |
| 2256x1504          | 8         | 0.29%   |
| 2880x1620          | 7         | 0.26%   |
| 3840x1080          | 6         | 0.22%   |
| 2880x1800          | 6         | 0.22%   |
| 3840x1600          | 3         | 0.11%   |
| 3840x1200          | 3         | 0.11%   |
| 3000x2000          | 3         | 0.11%   |
| 2160x1440          | 3         | 0.11%   |
| 2048x1152          | 3         | 0.11%   |
| 1400x1050          | 3         | 0.11%   |
| 5760x2160          | 2         | 0.07%   |
| 3840x2400          | 2         | 0.07%   |
| 2736x1824          | 2         | 0.07%   |
| 1280x720 (HD)      | 2         | 0.07%   |
| 7680x2160          | 1         | 0.04%   |
| 720x1280           | 1         | 0.04%   |
| 5760x1256          | 1         | 0.04%   |
| 5760x1200          | 1         | 0.04%   |
| 5760x1080          | 1         | 0.04%   |
| 5120x1440          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 532       | 19.25%  |
| 13      | 494       | 17.88%  |
| 24      | 224       | 8.11%   |
| 27      | 195       | 7.06%   |
| 21      | 172       | 6.23%   |
| 12      | 156       | 5.65%   |
| 23      | 148       | 5.36%   |
| Unknown | 141       | 5.1%    |
| 19      | 129       | 4.67%   |
| 17      | 107       | 3.87%   |
| 14      | 64        | 2.32%   |
| 31      | 59        | 2.14%   |
| 11      | 53        | 1.92%   |
| 18      | 46        | 1.66%   |
| 22      | 38        | 1.38%   |
| 34      | 36        | 1.3%    |
| 20      | 28        | 1.01%   |
| 10      | 25        | 0.9%    |
| 29      | 10        | 0.36%   |
| 40      | 9         | 0.33%   |
| 16      | 9         | 0.33%   |
| 54      | 7         | 0.25%   |
| 42      | 7         | 0.25%   |
| 9       | 7         | 0.25%   |
| 64      | 6         | 0.22%   |
| 39      | 5         | 0.18%   |
| 32      | 5         | 0.18%   |
| 28      | 5         | 0.18%   |
| 25      | 5         | 0.18%   |
| 52      | 4         | 0.14%   |
| 26      | 4         | 0.14%   |
| 50      | 3         | 0.11%   |
| 49      | 3         | 0.11%   |
| 46      | 3         | 0.11%   |
| 41      | 3         | 0.11%   |
| 37      | 3         | 0.11%   |
| 33      | 3         | 0.11%   |
| 48      | 2         | 0.07%   |
| 43      | 2         | 0.07%   |
| 35      | 2         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 934       | 34.22%  |
| 501-600     | 528       | 19.35%  |
| 201-300     | 443       | 16.23%  |
| 401-500     | 350       | 12.83%  |
| Unknown     | 141       | 5.17%   |
| 351-400     | 121       | 4.43%   |
| 601-700     | 97        | 3.55%   |
| 701-800     | 45        | 1.65%   |
| 1001-1500   | 33        | 1.21%   |
| 801-900     | 18        | 0.66%   |
| 901-1000    | 12        | 0.44%   |
| 101-200     | 6         | 0.22%   |
| 1-100       | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1915      | 73.97%  |
| 16/10   | 316       | 12.21%  |
| Unknown | 115       | 4.44%   |
| 5/4     | 98        | 3.79%   |
| 21/9    | 53        | 2.05%   |
| 3/2     | 44        | 1.7%    |
| 4/3     | 35        | 1.35%   |
| 6/5     | 4         | 0.15%   |
| 32/9    | 4         | 0.15%   |
| 3.18    | 1         | 0.04%   |
| 11/10   | 1         | 0.04%   |
| 1.96    | 1         | 0.04%   |
| 1.00    | 1         | 0.04%   |
| 0.46    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 491       | 17.89%  |
| 81-90          | 456       | 16.62%  |
| 91-100         | 412       | 15.01%  |
| 301-350        | 203       | 7.4%    |
| 151-200        | 170       | 6.2%    |
| 61-70          | 157       | 5.72%   |
| Unknown        | 141       | 5.14%   |
| 101-110        | 130       | 4.74%   |
| 351-500        | 111       | 4.05%   |
| 71-80          | 86        | 3.13%   |
| 141-150        | 85        | 3.1%    |
| 251-300        | 77        | 2.81%   |
| 121-130        | 60        | 2.19%   |
| 51-60          | 52        | 1.9%    |
| 501-1000       | 37        | 1.35%   |
| 41-50          | 28        | 1.02%   |
| More than 1000 | 25        | 0.91%   |
| 111-120        | 9         | 0.33%   |
| 131-140        | 8         | 0.29%   |
| 1-40           | 6         | 0.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 870       | 32.19%  |
| 101-120       | 727       | 26.9%   |
| 121-160       | 703       | 26.01%  |
| 161-240       | 195       | 7.21%   |
| Unknown       | 141       | 5.22%   |
| More than 240 | 46        | 1.7%    |
| 1-50          | 21        | 0.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 5799      | 68.51%  |
| 1     | 2371      | 28.01%  |
| 2     | 275       | 3.25%   |
| 3     | 19        | 0.22%   |
| 4     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 5944      | 50.76%  |
| Realtek Semiconductor             | 3006      | 25.67%  |
| Broadcom                          | 890       | 7.6%    |
| Qualcomm Atheros                  | 743       | 6.35%   |
| Marvell Technology Group          | 90        | 0.77%   |
| Ralink Technology                 | 83        | 0.71%   |
| TP-Link                           | 57        | 0.49%   |
| Mellanox Technologies             | 55        | 0.47%   |
| IMC Networks                      | 55        | 0.47%   |
| Ralink                            | 51        | 0.44%   |
| AMD                               | 47        | 0.4%    |
| Nvidia                            | 40        | 0.34%   |
| Chelsio Communications            | 40        | 0.34%   |
| D-Link System                     | 36        | 0.31%   |
| Edimax Technology                 | 33        | 0.28%   |
| Ericsson Business Mobile Networks | 28        | 0.24%   |
| MediaTek                          | 24        | 0.2%    |
| Sierra Wireless                   | 21        | 0.18%   |
| VIA Technologies                  | 19        | 0.16%   |
| U-Blox                            | 19        | 0.16%   |
| Xiaomi                            | 18        | 0.15%   |
| Samsung Electronics               | 18        | 0.15%   |
| Qualcomm Atheros Communications   | 18        | 0.15%   |
| Huawei Technologies               | 18        | 0.15%   |
| Aquantia                          | 18        | 0.15%   |
| Apple                             | 16        | 0.14%   |
| Solarflare Communications         | 15        | 0.13%   |
| ASUSTek Computer                  | 15        | 0.13%   |
| American Megatrends               | 15        | 0.13%   |
| QLogic                            | 14        | 0.12%   |
| Emulex                            | 14        | 0.12%   |
| 3Com                              | 13        | 0.11%   |
| IBM                               | 12        | 0.1%    |
| Google                            | 12        | 0.1%    |
| Hewlett-Packard                   | 11        | 0.09%   |
| Dell                              | 11        | 0.09%   |
| JMicron Technology                | 10        | 0.09%   |
| D-Link                            | 9         | 0.08%   |
| ZTE WCDMA Technologies MSM        | 8         | 0.07%   |
| Qualcomm                          | 8         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 2457      | 16.96%  |
| Intel I211 Gigabit Network Connection                                         | 1023      | 7.06%   |
| Intel I210 Gigabit Network Connection                                         | 692       | 4.78%   |
| Intel I350 Gigabit Network Connection                                         | 451       | 3.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 429       | 2.96%   |
| Intel 82574L Gigabit Network Connection                                       | 385       | 2.66%   |
| Intel Ethernet Connection I217-LM                                             | 225       | 1.55%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 202       | 1.39%   |
| Intel Ethernet Controller I225-V                                              | 183       | 1.26%   |
| Intel 82583V Gigabit Network Connection                                       | 181       | 1.25%   |
| Intel 82576 Gigabit Network Connection                                        | 177       | 1.22%   |
| Intel Wi-Fi 6 AX200                                                           | 169       | 1.17%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 161       | 1.11%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 160       | 1.1%    |
| Intel 82580 Gigabit Network Connection                                        | 158       | 1.09%   |
| Intel Wireless 8265 / 8275                                                    | 156       | 1.08%   |
| Intel Wireless 7265                                                           | 151       | 1.04%   |
| Realtek RTL8125 2.5GbE Controller                                             | 136       | 0.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 133       | 0.92%   |
| Intel Wireless 7260                                                           | 131       | 0.9%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 127       | 0.88%   |
| Intel Wireless 8260                                                           | 118       | 0.81%   |
| Intel Wireless 3165                                                           | 116       | 0.8%    |
| Intel Ethernet Connection (2) I219-LM                                         | 114       | 0.79%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 108       | 0.75%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 99        | 0.68%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 93        | 0.64%   |
| Intel Ethernet Connection (2) I219-V                                          | 90        | 0.62%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 88        | 0.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 86        | 0.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 79        | 0.55%   |
| Intel Ethernet Connection I354                                                | 75        | 0.52%   |
| Intel Ethernet Connection I219-LM                                             | 74        | 0.51%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 73        | 0.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 73        | 0.5%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 70        | 0.48%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 69        | 0.48%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 69        | 0.48%   |
| Intel 82579V Gigabit Network Connection                                       | 63        | 0.43%   |
| Intel Ethernet Connection (7) I219-V                                          | 62        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1786      | 51.34%  |
| Qualcomm Atheros                      | 607       | 17.45%  |
| Realtek Semiconductor                 | 416       | 11.96%  |
| Broadcom                              | 268       | 7.7%    |
| Ralink Technology                     | 83        | 2.39%   |
| TP-Link                               | 57        | 1.64%   |
| IMC Networks                          | 55        | 1.58%   |
| Ralink                                | 51        | 1.47%   |
| Edimax Technology                     | 33        | 0.95%   |
| MediaTek                              | 20        | 0.57%   |
| Qualcomm Atheros Communications       | 18        | 0.52%   |
| Sierra Wireless                       | 17        | 0.49%   |
| ASUSTek Computer                      | 15        | 0.43%   |
| D-Link                                | 9         | 0.26%   |
| NetGear                               | 8         | 0.23%   |
| D-Link System                         | 8         | 0.23%   |
| Dell                                  | 6         | 0.17%   |
| Mercucys                              | 3         | 0.09%   |
| Atheros                               | 3         | 0.09%   |
| AboCom Systems                        | 3         | 0.09%   |
| Belkin Components                     | 2         | 0.06%   |
| ZyXEL Communications                  | 1         | 0.03%   |
| Sitecom Europe                        | 1         | 0.03%   |
| Sagem                                 | 1         | 0.03%   |
| Qcom                                  | 1         | 0.03%   |
| Micro Star International              | 1         | 0.03%   |
| Marvell Technology Group              | 1         | 0.03%   |
| Linksys                               | 1         | 0.03%   |
| Gemtek                                | 1         | 0.03%   |
| BUFFALO                               | 1         | 0.03%   |
| Accton Technology                     | 1         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 169       | 4.81%   |
| Intel Wireless 8265 / 8275                                              | 156       | 4.44%   |
| Intel Wireless 7265                                                     | 151       | 4.3%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 133       | 3.79%   |
| Intel Wireless 7260                                                     | 131       | 3.73%   |
| Intel Wireless 8260                                                     | 118       | 3.36%   |
| Intel Wireless 3165                                                     | 116       | 3.3%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 88        | 2.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 86        | 2.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 79        | 2.25%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 73        | 2.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 73        | 2.08%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 70        | 1.99%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 69        | 1.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 60        | 1.71%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 56        | 1.59%   |
| Intel Wireless-AC 9260                                                  | 55        | 1.57%   |
| Intel Wireless 3160                                                     | 53        | 1.51%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 53        | 1.51%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 53        | 1.51%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                    | 51        | 1.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 40        | 1.14%   |
| Ralink RT5370 Wireless Adapter                                          | 39        | 1.11%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 38        | 1.08%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 38        | 1.08%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 35        | 1%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 34        | 0.97%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 33        | 0.94%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 32        | 0.91%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 31        | 0.88%   |
| Intel Centrino Advanced-N 6235                                          | 31        | 0.88%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 31        | 0.88%   |
| Intel Centrino Advanced-N 6200                                          | 30        | 0.85%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 30        | 0.85%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 30        | 0.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 29        | 0.83%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 29        | 0.83%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 29        | 0.83%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 28        | 0.8%    |
| Intel Wi-Fi 6 AX201                                                     | 28        | 0.8%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5061      | 54.6%   |
| Realtek Semiconductor            | 2822      | 30.45%  |
| Broadcom                         | 690       | 7.44%   |
| Qualcomm Atheros                 | 196       | 2.11%   |
| Marvell Technology Group         | 89        | 0.96%   |
| AMD                              | 47        | 0.51%   |
| Nvidia                           | 40        | 0.43%   |
| Chelsio Communications           | 29        | 0.31%   |
| D-Link System                    | 25        | 0.27%   |
| VIA Technologies                 | 19        | 0.2%    |
| Xiaomi                           | 18        | 0.19%   |
| Samsung Electronics              | 18        | 0.19%   |
| Aquantia                         | 18        | 0.19%   |
| Solarflare Communications        | 15        | 0.16%   |
| American Megatrends              | 15        | 0.16%   |
| QLogic                           | 14        | 0.15%   |
| Apple                            | 14        | 0.15%   |
| Emulex                           | 13        | 0.14%   |
| IBM                              | 12        | 0.13%   |
| 3Com                             | 12        | 0.13%   |
| JMicron Technology               | 10        | 0.11%   |
| Google                           | 10        | 0.11%   |
| Qualcomm                         | 8         | 0.09%   |
| Silicon Integrated Systems [SiS] | 6         | 0.06%   |
| ICS Advent                       | 6         | 0.06%   |
| Huawei Technologies              | 6         | 0.06%   |
| Novatel Wireless                 | 5         | 0.05%   |
| Insyde Software                  | 4         | 0.04%   |
| National Semiconductor           | 3         | 0.03%   |
| Microsoft                        | 3         | 0.03%   |
| Davicom Semiconductor            | 3         | 0.03%   |
| Cisco Systems                    | 3         | 0.03%   |
| ADMtek                           | 3         | 0.03%   |
| Tehuti Networks                  | 2         | 0.02%   |
| SysKonnect                       | 2         | 0.02%   |
| Silicom                          | 2         | 0.02%   |
| Realtek                          | 2         | 0.02%   |
| OPPO Electronics                 | 2         | 0.02%   |
| OnePlus Technology (Shenzhen)    | 2         | 0.02%   |
| MYRICOM                          | 2         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 2457      | 23%     |
| Intel I211 Gigabit Network Connection                                         | 1023      | 9.58%   |
| Intel I210 Gigabit Network Connection                                         | 692       | 6.48%   |
| Intel I350 Gigabit Network Connection                                         | 451       | 4.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 429       | 4.02%   |
| Intel 82574L Gigabit Network Connection                                       | 385       | 3.6%    |
| Intel Ethernet Connection I217-LM                                             | 225       | 2.11%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 202       | 1.89%   |
| Intel Ethernet Controller I225-V                                              | 183       | 1.71%   |
| Intel 82583V Gigabit Network Connection                                       | 181       | 1.69%   |
| Intel 82576 Gigabit Network Connection                                        | 177       | 1.66%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 161       | 1.51%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 160       | 1.5%    |
| Intel 82580 Gigabit Network Connection                                        | 158       | 1.48%   |
| Realtek RTL8125 2.5GbE Controller                                             | 127       | 1.19%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 127       | 1.19%   |
| Intel Ethernet Connection (2) I219-LM                                         | 114       | 1.07%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 108       | 1.01%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 99        | 0.93%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 93        | 0.87%   |
| Intel Ethernet Connection (2) I219-V                                          | 90        | 0.84%   |
| Intel Ethernet Connection I354                                                | 75        | 0.7%    |
| Intel Ethernet Connection I219-LM                                             | 74        | 0.69%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 69        | 0.65%   |
| Intel 82579V Gigabit Network Connection                                       | 63        | 0.59%   |
| Intel Ethernet Connection (7) I219-V                                          | 62        | 0.58%   |
| Intel Ethernet Connection X553 1GbE                                           | 56        | 0.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 55        | 0.51%   |
| Intel Ethernet Connection (7) I219-LM                                         | 54        | 0.51%   |
| Intel Ethernet Connection I217-V                                              | 53        | 0.5%    |
| Intel Ethernet Controller X550                                                | 46        | 0.43%   |
| Intel Ethernet Connection (3) I218-LM                                         | 46        | 0.43%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0                     | 46        | 0.43%   |
| Intel 82577LM Gigabit Network Connection                                      | 45        | 0.42%   |
| Intel Ethernet Connection (4) I219-LM                                         | 44        | 0.41%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 44        | 0.41%   |
| Intel Ethernet Connection I218-LM                                             | 42        | 0.39%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 40        | 0.37%   |
| Intel Ethernet Controller I226-V                                              | 40        | 0.37%   |
| Intel Ethernet Connection (4) I219-V                                          | 39        | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 7953      | 69.39%  |
| WiFi     | 3221      | 28.1%   |
| Unknown  | 176       | 1.54%   |
| Modem    | 112       | 0.98%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 7425      | 81.45%  |
| WiFi     | 1654      | 18.14%  |
| Unknown  | 24        | 0.26%   |
| Modem    | 13        | 0.14%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2965      | 35.01%  |
| 1     | 1457      | 17.2%   |
| 4     | 1268      | 14.97%  |
| 3     | 1048      | 12.37%  |
| 6     | 662       | 7.82%   |
| 5     | 485       | 5.73%   |
| 8     | 188       | 2.22%   |
| 0     | 142       | 1.68%   |
| 7     | 106       | 1.25%   |
| 10    | 53        | 0.63%   |
| 9     | 47        | 0.55%   |
| 12    | 18        | 0.21%   |
| 14    | 10        | 0.12%   |
| 11    | 7         | 0.08%   |
| 13    | 6         | 0.07%   |
| 16    | 3         | 0.04%   |
| 15    | 3         | 0.04%   |
| 20    | 2         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 7420      | 86.17%  |
| Yes  | 1191      | 13.83%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1206      | 56.17%  |
| Broadcom                        | 159       | 7.41%   |
| Apple                           | 132       | 6.15%   |
| Qualcomm Atheros Communications | 124       | 5.78%   |
| Realtek Semiconductor           | 111       | 5.17%   |
| IMC Networks                    | 105       | 4.89%   |
| Cambridge Silicon Radio         | 80        | 3.73%   |
| Lite-On Technology              | 44        | 2.05%   |
| Foxconn / Hon Hai               | 41        | 1.91%   |
| ASUSTek Computer                | 38        | 1.77%   |
| Dell                            | 31        | 1.44%   |
| Hewlett-Packard                 | 22        | 1.02%   |
| Alps Electric                   | 15        | 0.7%    |
| Ralink                          | 8         | 0.37%   |
| MediaTek                        | 8         | 0.37%   |
| Realtek                         | 7         | 0.33%   |
| Integrated System Solution      | 3         | 0.14%   |
| Toshiba                         | 2         | 0.09%   |
| HTC (High Tech Computer)        | 2         | 0.09%   |
| Creative Technology             | 2         | 0.09%   |
| TP-Link                         | 1         | 0.05%   |
| Qcom                            | 1         | 0.05%   |
| Opticis                         | 1         | 0.05%   |
| Micro Star International        | 1         | 0.05%   |
| Edimax Technology               | 1         | 0.05%   |
| Dynex                           | 1         | 0.05%   |
| Bluetooth Device                | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 555       | 25.8%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 169       | 7.86%   |
| Intel AX200 Bluetooth                                       | 163       | 7.58%   |
| Intel AX201 Bluetooth                                       | 112       | 5.21%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 80        | 3.72%   |
| Intel Wireless-AC 3168 Bluetooth                            | 69        | 3.21%   |
| Apple Bluetooth Host Controller                             | 58        | 2.7%    |
| Intel Centrino Bluetooth Wireless Transceiver               | 53        | 2.46%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 48        | 2.23%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 46        | 2.14%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 45        | 2.09%   |
| Realtek  Bluetooth 4.2 Adapter                              | 40        | 1.86%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 28        | 1.3%    |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 27        | 1.26%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 27        | 1.26%   |
| Realtek  Bluetooth Adapter                                  | 23        | 1.07%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 23        | 1.07%   |
| Intel AX210 Bluetooth                                       | 23        | 1.07%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 22        | 1.02%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 18        | 0.84%   |
| IMC Networks Realtek Bluetooth Adapter                      | 18        | 0.84%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 17        | 0.79%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip        | 16        | 0.74%   |
| Lite-On Atheros AR3012 Bluetooth                            | 15        | 0.7%    |
| Realtek  Bluetooth 4.0 Adapter                              | 13        | 0.6%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 12        | 0.56%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 12        | 0.56%   |
| Dell DW375 Bluetooth Module                                 | 12        | 0.56%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 12        | 0.56%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 12        | 0.56%   |
| Apple Built-in iSight (no firmware loaded)                  | 12        | 0.56%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 11        | 0.51%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 10        | 0.46%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 10        | 0.46%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 10        | 0.46%   |
| Realtek RTL8723B Bluetooth                                  | 9         | 0.42%   |
| Realtek Bluetooth Radio                                     | 9         | 0.42%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 9         | 0.42%   |
| Alps Electric UGTZ4 Bluetooth                               | 9         | 0.42%   |
| Ralink RT3290 Bluetooth                                     | 8         | 0.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 4908      | 66.28%  |
| AMD                                          | 1341      | 18.11%  |
| Nvidia                                       | 779       | 10.52%  |
| C-Media Electronics                          | 68        | 0.92%   |
| Logitech                                     | 29        | 0.39%   |
| Creative Labs                                | 25        | 0.34%   |
| Texas Instruments                            | 21        | 0.28%   |
| GN Netcom                                    | 14        | 0.19%   |
| Realtek Semiconductor                        | 13        | 0.18%   |
| Lenovo                                       | 13        | 0.18%   |
| VIA Technologies                             | 12        | 0.16%   |
| SteelSeries ApS                              | 12        | 0.16%   |
| JMTek                                        | 12        | 0.16%   |
| Silicon Integrated Systems [SiS]             | 10        | 0.14%   |
| Creative Technology                          | 8         | 0.11%   |
| Kingston Technology                          | 7         | 0.09%   |
| Sony                                         | 6         | 0.08%   |
| Generalplus Technology                       | 6         | 0.08%   |
| Focusrite-Novation                           | 6         | 0.08%   |
| Blue Microphones                             | 6         | 0.08%   |
| Zoran Co. Personal Media Division (Nogatech) | 5         | 0.07%   |
| Yamaha                                       | 5         | 0.07%   |
| ESS Technology                               | 5         | 0.07%   |
| Corsair                                      | 5         | 0.07%   |
| BEHRINGER International                      | 5         | 0.07%   |
| XMOS                                         | 4         | 0.05%   |
| Thesycon Systemsoftware & Consulting         | 4         | 0.05%   |
| Plantronics                                  | 4         | 0.05%   |
| Cambridge Silicon Radio                      | 4         | 0.05%   |
| ULi Electronics                              | 3         | 0.04%   |
| M-Audio                                      | 3         | 0.04%   |
| KTMicro                                      | 3         | 0.04%   |
| FiiO Electronics Technology                  | 3         | 0.04%   |
| ASUSTek Computer                             | 3         | 0.04%   |
| Trust                                        | 2         | 0.03%   |
| Tenx Technology                              | 2         | 0.03%   |
| RODE Microphones                             | 2         | 0.03%   |
| Microsoft                                    | 2         | 0.03%   |
| Hewlett-Packard                              | 2         | 0.03%   |
| Google                                       | 2         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 459       | 5.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 429       | 4.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 419       | 4.72%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 390       | 4.39%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 387       | 4.36%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 290       | 3.27%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 279       | 3.14%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 269       | 3.03%   |
| AMD FCH Azalia Controller                                                                         | 252       | 2.84%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 238       | 2.68%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 214       | 2.41%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 202       | 2.28%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 200       | 2.25%   |
| Intel 8 Series HD Audio Controller                                                                | 199       | 2.24%   |
| Intel Broadwell-U Audio Controller                                                                | 191       | 2.15%   |
| AMD Kabini HDMI/DP Audio                                                                          | 190       | 2.14%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 184       | 2.07%   |
| Intel Cannon Lake PCH cAVS                                                                        | 182       | 2.05%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 177       | 1.99%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 155       | 1.75%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 136       | 1.53%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 135       | 1.52%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 131       | 1.48%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 127       | 1.43%   |
| Intel 200 Series PCH HD Audio                                                                     | 127       | 1.43%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 125       | 1.41%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 122       | 1.37%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 107       | 1.21%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 102       | 1.15%   |
| Intel Jasper Lake HD Audio                                                                        | 91        | 1.03%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 91        | 1.03%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 78        | 0.88%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 75        | 0.85%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 70        | 0.79%   |
| Intel Comet Lake PCH cAVS                                                                         | 64        | 0.72%   |
| Nvidia High Definition Audio Controller                                                           | 54        | 0.61%   |
| AMD Wrestler HDMI Audio                                                                           | 53        | 0.6%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 52        | 0.59%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 52        | 0.59%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 49        | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 1595      | 18.49%  |
| SK hynix                     | 1205      | 13.97%  |
| Kingston                     | 1101      | 12.76%  |
| Unknown                      | 1066      | 12.36%  |
| Micron Technology            | 707       | 8.2%    |
| Crucial                      | 697       | 8.08%   |
| Corsair                      | 374       | 4.34%   |
| G.Skill                      | 274       | 3.18%   |
| Unknown                      | 206       | 2.39%   |
| Transcend                    | 138       | 1.6%    |
| A-DATA Technology            | 121       | 1.4%    |
| Unknown (ABCD)               | 120       | 1.39%   |
| Ramaxel Technology           | 107       | 1.24%   |
| Nanya Technology             | 104       | 1.21%   |
| Elpida                       | 88        | 1.02%   |
| Team                         | 60        | 0.7%    |
| Patriot                      | 58        | 0.67%   |
| Apacer                       | 40        | 0.46%   |
| Hewlett-Packard              | 39        | 0.45%   |
| Kimtigo                      | 34        | 0.39%   |
| Toshiba                      | 32        | 0.37%   |
| Smart                        | 30        | 0.35%   |
| PNY                          | 25        | 0.29%   |
| GOODRAM                      | 25        | 0.29%   |
| Avant                        | 21        | 0.24%   |
| Teikon                       | 19        | 0.22%   |
| ATP                          | 19        | 0.22%   |
| TIMETEC                      | 16        | 0.19%   |
| Super Talent                 | 13        | 0.15%   |
| Innodisk                     | 11        | 0.13%   |
| Tigo                         | 10        | 0.12%   |
| AMD                          | 10        | 0.12%   |
| Silicon Power                | 9         | 0.1%    |
| HPE                          | 9         | 0.1%    |
| GeIL                         | 9         | 0.1%    |
| 48spaces                     | 8         | 0.09%   |
| Qimonda                      | 7         | 0.08%   |
| Neo Forza                    | 7         | 0.08%   |
| Goldkey                      | 7         | 0.08%   |
| Patriot Memory (PDP Systems) | 6         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown                                                      | 206       | 2.23%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                  | 119       | 1.29%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 113       | 1.22%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 69        | 0.75%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 67        | 0.72%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 51        | 0.55%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 50        | 0.54%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 49        | 0.53%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 46        | 0.5%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 42        | 0.45%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 39        | 0.42%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                    | 36        | 0.39%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 36        | 0.39%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s       | 36        | 0.39%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 36        | 0.39%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 34        | 0.37%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s        | 34        | 0.37%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s        | 30        | 0.32%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s         | 29        | 0.31%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 29        | 0.31%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 28        | 0.3%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s        | 28        | 0.3%    |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s          | 27        | 0.29%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s      | 27        | 0.29%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s         | 26        | 0.28%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s         | 26        | 0.28%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s      | 26        | 0.28%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 25        | 0.27%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s        | 25        | 0.27%   |
| Unknown RAM Module 8GB 1600MT/s                              | 24        | 0.26%   |
| Unknown RAM Module 2GB DIMM SDRAM                            | 24        | 0.26%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s        | 24        | 0.26%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s        | 24        | 0.26%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 23        | 0.25%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s          | 23        | 0.25%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                    | 22        | 0.24%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s          | 22        | 0.24%   |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s          | 22        | 0.24%   |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s                   | 21        | 0.23%   |
| Unknown RAM Module 1GB DIMM SDRAM                            | 21        | 0.23%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind            | Computers | Percent |
|-----------------|-----------|---------|
| DDR3            | 3835      | 50.61%  |
| DDR4            | 2667      | 35.19%  |
| DDR2            | 419       | 5.53%   |
| Unknown         | 238       | 3.14%   |
| LPDDR4          | 168       | 2.22%   |
| SDRAM           | 96        | 1.27%   |
| LPDDR3          | 68        | 0.9%    |
| DDR             | 61        | 0.8%    |
| DRAM            | 15        | 0.2%    |
| RAM             | 4         | 0.05%   |
| LPDDR5          | 4         | 0.05%   |
| SRAM            | 1         | 0.01%   |
| Logical non-vol | 1         | 0.01%   |
| DDR5            | 1         | 0.01%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 3981      | 52.67%  |
| SODIMM       | 3324      | 43.98%  |
| Row Of Chips | 107       | 1.42%   |
| Unknown      | 64        | 0.85%   |
| Chip         | 48        | 0.64%   |
| FB-DIMM      | 25        | 0.33%   |
| RIMM         | 9         | 0.12%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 2807      | 34.4%   |
| 4096   | 2757      | 33.78%  |
| 2048   | 1140      | 13.97%  |
| 16384  | 994       | 12.18%  |
| 1024   | 242       | 2.97%   |
| 32768  | 153       | 1.87%   |
| 512    | 41        | 0.5%    |
| 256    | 8         | 0.1%    |
| 65536  | 5         | 0.06%   |
| 128    | 4         | 0.05%   |
| 32767  | 2         | 0.02%   |
| 131072 | 1         | 0.01%   |
| 129728 | 1         | 0.01%   |
| 6144   | 1         | 0.01%   |
| 4092   | 1         | 0.01%   |
| 2560   | 1         | 0.01%   |
| 1556   | 1         | 0.01%   |
| 64     | 1         | 0.01%   |
| 32     | 1         | 0.01%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 2397      | 29.76%  |
| 1333    | 1200      | 14.9%   |
| 2400    | 956       | 11.87%  |
| 2667    | 695       | 8.63%   |
| 2133    | 551       | 6.84%   |
| 3200    | 509       | 6.32%   |
| 667     | 275       | 3.41%   |
| 800     | 266       | 3.3%    |
| Unknown | 167       | 2.07%   |
| 1334    | 141       | 1.75%   |
| 2666    | 140       | 1.74%   |
| 1067    | 128       | 1.59%   |
| 1867    | 127       | 1.58%   |
| 1066    | 123       | 1.53%   |
| 1866    | 54        | 0.67%   |
| 3000    | 50        | 0.62%   |
| 2933    | 47        | 0.58%   |
| 533     | 43        | 0.53%   |
| 3600    | 39        | 0.48%   |
| 400     | 26        | 0.32%   |
| 4267    | 15        | 0.19%   |
| 975     | 11        | 0.14%   |
| 333     | 9         | 0.11%   |
| 266     | 7         | 0.09%   |
| 1400    | 6         | 0.07%   |
| 1332    | 6         | 0.07%   |
| 65535   | 5         | 0.06%   |
| 3400    | 5         | 0.06%   |
| 2134    | 5         | 0.06%   |
| 1033    | 5         | 0.06%   |
| 6400    | 4         | 0.05%   |
| 4266    | 4         | 0.05%   |
| 1200    | 4         | 0.05%   |
| 3534    | 3         | 0.04%   |
| 2048    | 3         | 0.04%   |
| 5200    | 2         | 0.02%   |
| 4800    | 2         | 0.02%   |
| 2600    | 2         | 0.02%   |
| 1639    | 2         | 0.02%   |
| 933     | 2         | 0.02%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Brother Industries    | 11        | 30.56%  |
| Hewlett-Packard       | 10        | 27.78%  |
| Seiko Epson           | 2         | 5.56%   |
| Prolific Technology   | 2         | 5.56%   |
| Lexmark International | 2         | 5.56%   |
| ELGIN                 | 2         | 5.56%   |
| Samsung Electronics   | 1         | 2.78%   |
| Ricoh                 | 1         | 2.78%   |
| QinHeng Electronics   | 1         | 2.78%   |
| Kyocera               | 1         | 2.78%   |
| Dymo-CoStar           | 1         | 2.78%   |
| Canon                 | 1         | 2.78%   |
| Apple                 | 1         | 2.78%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                                                                                             | Computers | Percent |
|-------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port                                                                                     | 2         | 5.26%   |
| ELGIN L42PRO                                                                                                      | 2         | 5.26%   |
| Brother MFC-7360N                                                                                                 | 2         | 5.26%   |
| Brother HL-1430 Laser Printer                                                                                     | 2         | 5.26%   |
| Seiko Epson USB2.0 Printer (Hi-speed)                                                                             | 1         | 2.63%   |
| Seiko Epson Printer                                                                                               | 1         | 2.63%   |
| Samsung ML-1610 Mono Laser Printer                                                                                | 1         | 2.63%   |
| Ricoh SP 112                                                                                                      | 1         | 2.63%   |
| QinHeng CH340S                                                                                                    | 1         | 2.63%   |
| Lexmark International SINDOH A603_A608 Print                                                                      | 1         | 2.63%   |
| Lexmark International Lexmark MS710 Print                                                                         | 1         | 2.63%   |
| Kyocera FS-1025MFP                                                                                                | 1         | 2.63%   |
| HP PNP Fax Null                                                                                                   | 1         | 2.63%   |
| HP LaserJet P3005                                                                                                 | 1         | 2.63%   |
| HP LaserJet 2200                                                                                                  | 1         | 2.63%   |
| HP LaserJet 1200                                                                                                  | 1         | 2.63%   |
| HP LaserJet 1012                                                                                                  | 1         | 2.63%   |
| HP HP LaserJet P2035 HP Print                                                                                     | 1         | 2.63%   |
| HP HP LaserJet MFP E52645 LaserJet 0 LaserJet 0 LaserJet 1 LaserJet 1 LaserJet 2 LaserJet 2 LaserJet 3 LaserJet 3 | 1         | 2.63%   |
| HP HP LaserJet M14-M17 Printer HP LEDM IPP Printer HP LEDM IPP Printer HP LEDM IPP Printer                        | 1         | 2.63%   |
| HP HP LaserJet M101-M106 Printer HP LEDM HP LEDM IPP Printer IPP Printer                                          | 1         | 2.63%   |
| HP HP Laser 107w                                                                                                  | 1         | 2.63%   |
| HP DeskJet 5850c                                                                                                  | 1         | 2.63%   |
| HP Color LaserJet CP1215                                                                                          | 1         | 2.63%   |
| Dymo-CoStar DYMO LabelWriter 450 DUO                                                                              | 1         | 2.63%   |
| Canon LBP2900                                                                                                     | 1         | 2.63%   |
| Brother MFC-L2685DW                                                                                               | 1         | 2.63%   |
| Brother MFC-J485DW                                                                                                | 1         | 2.63%   |
| Brother MFC-J200                                                                                                  | 1         | 2.63%   |
| Brother HL-L5200DW series                                                                                         | 1         | 2.63%   |
| Brother HL-L2310D series                                                                                          | 1         | 2.63%   |
| Brother HL-2030 Laser Printer                                                                                     | 1         | 2.63%   |
| Brother DCP-J100                                                                                                  | 1         | 2.63%   |
| Apple Gamesir-G3s 2.10                                                                                            | 1         | 2.63%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 7         | 77.78%  |
| Seiko Epson     | 1         | 11.11%  |
| Hewlett-Packard | 1         | 11.11%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                             | 4         | 44.44%  |
| Seiko Epson WF-2860 Series EPSON Scanner USB2.0 Printer EPSON Utility USB2.0 Faxout | 1         | 11.11%  |
| HP ScanJet 5300c/5370c                                                              | 1         | 11.11%  |
| Canon CanoScan LIDE 25                                                              | 1         | 11.11%  |
| Canon CanoScan LiDE 220                                                             | 1         | 11.11%  |
| Canon CanoScan LiDE 210                                                             | 1         | 11.11%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 422       | 27.3%   |
| Acer                                   | 149       | 9.64%   |
| IMC Networks                           | 141       | 9.12%   |
| Realtek Semiconductor                  | 130       | 8.41%   |
| Microdia                               | 128       | 8.28%   |
| Sunplus Innovation Technology          | 82        | 5.3%    |
| Logitech                               | 77        | 4.98%   |
| Suyin                                  | 55        | 3.56%   |
| Lite-On Technology                     | 51        | 3.3%    |
| Apple                                  | 32        | 2.07%   |
| Quanta                                 | 31        | 2.01%   |
| Syntek                                 | 30        | 1.94%   |
| Cheng Uei Precision Industry (Foxlink) | 30        | 1.94%   |
| Silicon Motion                         | 22        | 1.42%   |
| Lenovo                                 | 21        | 1.36%   |
| Alcor Micro                            | 19        | 1.23%   |
| Z-Star Microelectronics                | 16        | 1.03%   |
| Ricoh                                  | 12        | 0.78%   |
| Luxvisions Innotech Limited            | 12        | 0.78%   |
| ALi                                    | 11        | 0.71%   |
| Importek                               | 8         | 0.52%   |
| ARC International                      | 7         | 0.45%   |
| Intel                                  | 4         | 0.26%   |
| Arkmicro Technologies                  | 4         | 0.26%   |
| Sonix Technology                       | 3         | 0.19%   |
| Primax Electronics                     | 3         | 0.19%   |
| OmniVision Technologies                | 3         | 0.19%   |
| WCM_USB                                | 2         | 0.13%   |
| Unknown                                | 2         | 0.13%   |
| Tripath Technology                     | 2         | 0.13%   |
| ShineTech                              | 2         | 0.13%   |
| SHENZHEN EMEET TECHNOLOGY              | 2         | 0.13%   |
| Pixart Imaging                         | 2         | 0.13%   |
| Hewlett-Packard                        | 2         | 0.13%   |
| Genesys Logic                          | 2         | 0.13%   |
| Generalplus Technology                 | 2         | 0.13%   |
| GEMBIRD                                | 2         | 0.13%   |
| DigiTech                               | 2         | 0.13%   |
| Cubeternet                             | 2         | 0.13%   |
| Creative Technology                    | 2         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Chicony Integrated Camera                 | 128       | 8.21%   |
| Acer Integrated Camera                    | 69        | 4.42%   |
| Realtek Integrated_Webcam_HD              | 43        | 2.76%   |
| IMC Networks Integrated Camera            | 43        | 2.76%   |
| Chicony HD WebCam                         | 37        | 2.37%   |
| Lite-On Integrated Camera                 | 33        | 2.12%   |
| Microdia Integrated_Webcam_HD             | 30        | 1.92%   |
| Microdia Integrated Webcam                | 30        | 1.92%   |
| Chicony Lenovo Integrated Camera (0.3MP)  | 27        | 1.73%   |
| Sunplus Integrated_Webcam_HD              | 25        | 1.6%    |
| Realtek Realtek USB2.0 PC Camera          | 23        | 1.47%   |
| IMC Networks USB2.0 HD UVC WebCam         | 22        | 1.41%   |
| Logitech HD Pro Webcam C920               | 20        | 1.28%   |
| Logitech Webcam C270                      | 19        | 1.22%   |
| Acer Lenovo EasyCamera                    | 19        | 1.22%   |
| Chicony Integrated Camera (1280x720@30)   | 18        | 1.15%   |
| Apple FaceTime HD Camera                  | 18        | 1.15%   |
| Chicony Chicony USB2.0 Camera             | 17        | 1.09%   |
| IMC Networks EasyCamera                   | 15        | 0.96%   |
| Chicony Integrated Camera [ThinkPad]      | 15        | 0.96%   |
| Syntek Lenovo EasyCamera                  | 14        | 0.9%    |
| Lenovo Integrated Webcam [R5U877]         | 13        | 0.83%   |
| Chicony HP HD Webcam [Fixed]              | 13        | 0.83%   |
| Sunplus Laptop_Integrated_Webcam_FHD      | 12        | 0.77%   |
| Apple FaceTime HD Camera (Built-in)       | 12        | 0.77%   |
| IMC Networks USB2.0 VGA UVC WebCam        | 11        | 0.71%   |
| Syntek EasyCamera                         | 10        | 0.64%   |
| Realtek USB Camera                        | 10        | 0.64%   |
| Acer ThinkPad Integrated Camera           | 10        | 0.64%   |
| Acer SunplusIT Integrated Camera          | 10        | 0.64%   |
| Microdia Laptop_Integrated_Webcam_HD      | 9         | 0.58%   |
| Microdia Dell Laptop Integrated Webcam HD | 9         | 0.58%   |
| Chicony USB2.0 VGA UVC WebCam             | 9         | 0.58%   |
| Chicony ThinkPad T490 Webcam              | 9         | 0.58%   |
| Chicony Lenovo EasyCamera                 | 9         | 0.58%   |
| Acer Lenovo Integrated Webcam             | 9         | 0.58%   |
| IMC Networks USB2.0 UVC HD Webcam         | 8         | 0.51%   |
| Chicony USB2.0 HD UVC WebCam              | 8         | 0.51%   |
| Chicony EasyCamera                        | 8         | 0.51%   |
| ALi Gateway Webcam                        | 8         | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 159       | 39.26%  |
| Synaptics                  | 72        | 17.78%  |
| Upek                       | 49        | 12.1%   |
| AuthenTec                  | 36        | 8.89%   |
| Shenzhen Goodix Technology | 31        | 7.65%   |
| STMicroelectronics         | 26        | 6.42%   |
| Broadcom                   | 14        | 3.46%   |
| LighTuning Technology      | 9         | 2.22%   |
| Elan Microelectronics      | 4         | 0.99%   |
| Samsung Electronics        | 2         | 0.49%   |
| Next Biometrics            | 1         | 0.25%   |
| Focal-systems.Corp         | 1         | 0.25%   |
| DigitalPersona             | 1         | 0.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 53        | 13.09%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 46        | 11.36%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 30        | 7.41%   |
| Validity Sensors Synaptics WBDI                                              | 29        | 7.16%   |
| STMicroelectronics Fingerprint Reader                                        | 26        | 6.42%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 20        | 4.94%   |
| Shenzhen Goodix Fingerprint Reader                                           | 20        | 4.94%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 18        | 4.44%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 15        | 3.7%    |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 14        | 3.46%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 14        | 3.46%   |
| AuthenTec AES2810                                                            | 10        | 2.47%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 10        | 2.47%   |
| Shenzhen Goodix  Fingerprint Device                                          | 9         | 2.22%   |
| AuthenTec AuthenTec Inc. AES1660                                             | 6         | 1.48%   |
| Unknown                                                                      | 6         | 1.48%   |
| Validity Sensors VFS491                                                      | 5         | 1.23%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 5         | 1.23%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                    | 5         | 1.23%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 5         | 1.23%   |
| AuthenTec AES1600                                                            | 5         | 1.23%   |
| Validity Sensors VFS451 Fingerprint Reader                                   | 4         | 0.99%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint   | 4         | 0.99%   |
| Elan ELAN WBF Fingerprint Sensor                                             | 4         | 0.99%   |
| Validity Sensors VFS Fingerprint sensor                                      | 3         | 0.74%   |
| Validity Sensors Swipe Fingerprint Sensor                                    | 3         | 0.74%   |
| Validity Sensors Fingerprint scanner                                         | 3         | 0.74%   |
| Upek TCS5B Fingerprint sensor                                                | 3         | 0.74%   |
| Synaptics  WBDI                                                              | 3         | 0.74%   |
| Synaptics product 0x00be                                                     | 3         | 0.74%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 3         | 0.74%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 3         | 0.74%   |
| LighTuning EgisTec EH575                                                     | 3         | 0.74%   |
| Shenzhen Goodix FingerPrint                                                  | 2         | 0.49%   |
| AuthenTec AuthenTec Inc. AES2660                                             | 2         | 0.49%   |
| AuthenTec AES2550 Fingerprint Sensor                                         | 2         | 0.49%   |
| Validity Sensors VFS301 Fingerprint Reader                                   | 1         | 0.25%   |
| Validity Sensors VFS101 Fingerprint Reader                                   | 1         | 0.25%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                  | 1         | 0.25%   |
| Samsung Fingerprint Sensor Device - 730B                                     | 1         | 0.25%   |

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
| 1     | 3246      | 37.58%  |
| 0     | 2918      | 33.78%  |
| 2     | 1515      | 17.54%  |
| 3     | 631       | 7.31%   |
| 4     | 243       | 2.81%   |
| 5     | 57        | 0.66%   |
| 6     | 18        | 0.21%   |
| 7     | 7         | 0.08%   |
| 9     | 1         | 0.01%   |
| 8     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 4712      | 57.35%  |
| Net/wireless             | 865       | 10.53%  |
| Bluetooth                | 823       | 10.02%  |
| Card reader              | 593       | 7.22%   |
| Fingerprint reader       | 339       | 4.13%   |
| Firewire controller      | 307       | 3.74%   |
| Sound                    | 147       | 1.79%   |
| Net/ethernet             | 112       | 1.36%   |
| Network                  | 110       | 1.34%   |
| Graphics card            | 100       | 1.22%   |
| Storage                  | 40        | 0.49%   |
| Modem                    | 22        | 0.27%   |
| Storage/ata              | 15        | 0.18%   |
| Storage/raid             | 13        | 0.16%   |
| Dvb card                 | 8         | 0.1%    |
| Storage/ide              | 6         | 0.07%   |
| Storage/nvme             | 3         | 0.04%   |
| Wireless                 | 1         | 0.01%   |

