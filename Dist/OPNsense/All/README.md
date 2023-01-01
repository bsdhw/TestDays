OPNsense - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for OPNsense.

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

Total: 7465

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Dell          | 04415J A00                  | Mini pc     | [3737d80840](https://bsd-hardware.info/?probe=3737d80840) | Dec 31, 2022 |
| HP            | 1825                        | Desktop     | [f7e94decd0](https://bsd-hardware.info/?probe=f7e94decd0) | Dec 31, 2022 |
| HP            | 1825                        | Desktop     | [afc1259508](https://bsd-hardware.info/?probe=afc1259508) | Dec 31, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [b6ec2e7e28](https://bsd-hardware.info/?probe=b6ec2e7e28) | Dec 31, 2022 |
| Sophos        | UTM                         | Firewall    | [81bbacbfee](https://bsd-hardware.info/?probe=81bbacbfee) | Dec 31, 2022 |
| Deciso        | OPNsense Appliance          | Notebook    | [21e1293019](https://bsd-hardware.info/?probe=21e1293019) | Dec 31, 2022 |
| Sophos        | SG                          | Firewall    | [8679b4c8f4](https://bsd-hardware.info/?probe=8679b4c8f4) | Dec 31, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [0bf1c2abef](https://bsd-hardware.info/?probe=0bf1c2abef) | Dec 31, 2022 |
| Supermicro    | X11SSH-LN4F                 | Server      | [5e84d1a402](https://bsd-hardware.info/?probe=5e84d1a402) | Dec 31, 2022 |
| Dell          | 04415J A00                  | Mini pc     | [c6c6858ef0](https://bsd-hardware.info/?probe=c6c6858ef0) | Dec 31, 2022 |
| Supermicro    | X10SDV-TP8F                 | Server      | [16daca3076](https://bsd-hardware.info/?probe=16daca3076) | Dec 31, 2022 |
| Unknown       | Unknown                     | Desktop     | [68a847f5c2](https://bsd-hardware.info/?probe=68a847f5c2) | Dec 31, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [cac58d91b6](https://bsd-hardware.info/?probe=cac58d91b6) | Dec 31, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [910c2bba4a](https://bsd-hardware.info/?probe=910c2bba4a) | Dec 31, 2022 |
| ASUSTek       | PRIME A320I-K               | Desktop     | [334575b738](https://bsd-hardware.info/?probe=334575b738) | Dec 31, 2022 |
| GoWin Solu... | R86S                        | Desktop     | [4243d313a1](https://bsd-hardware.info/?probe=4243d313a1) | Dec 31, 2022 |
| Supermicro    | X10SDV-TP8F                 | Server      | [5967766127](https://bsd-hardware.info/?probe=5967766127) | Dec 30, 2022 |
| Fujitsu       | D3313-S3 S26361-D3313-S3    | Desktop     | [b89a55c4aa](https://bsd-hardware.info/?probe=b89a55c4aa) | Dec 30, 2022 |
| OEM           | 1.0                         | Desktop     | [f2aeb0ea02](https://bsd-hardware.info/?probe=f2aeb0ea02) | Dec 30, 2022 |
| CompuLab      | SBC-fit-PC4                 | Mini pc     | [c781bd46dc](https://bsd-hardware.info/?probe=c781bd46dc) | Dec 30, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [cd3e4f7122](https://bsd-hardware.info/?probe=cd3e4f7122) | Dec 30, 2022 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | Desktop     | [a8ece272af](https://bsd-hardware.info/?probe=a8ece272af) | Dec 30, 2022 |
| Protectli     | FW4B                        | Desktop     | [406fe72c22](https://bsd-hardware.info/?probe=406fe72c22) | Dec 30, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [126bde2444](https://bsd-hardware.info/?probe=126bde2444) | Dec 30, 2022 |
| Supermicro    | X10SDV-8C-TLN4F+            | Server      | [d4460f8031](https://bsd-hardware.info/?probe=d4460f8031) | Dec 30, 2022 |
| Protectli     | FW6                         | Desktop     | [0d62222b7a](https://bsd-hardware.info/?probe=0d62222b7a) | Dec 30, 2022 |
| Supermicro    | X10SDV-8C-TLN4F+            | Server      | [46c3e7ffdd](https://bsd-hardware.info/?probe=46c3e7ffdd) | Dec 30, 2022 |
| Deciso        | OPNsense Appliance          | Notebook    | [8b4c84d972](https://bsd-hardware.info/?probe=8b4c84d972) | Dec 30, 2022 |
| Unknown       | Unknown                     | Firewall    | [72eaa7a90f](https://bsd-hardware.info/?probe=72eaa7a90f) | Dec 30, 2022 |
| Shuttle       | FH110                       | Desktop     | [3759d77a05](https://bsd-hardware.info/?probe=3759d77a05) | Dec 29, 2022 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [e23f822438](https://bsd-hardware.info/?probe=e23f822438) | Dec 29, 2022 |
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
| Hardkernel    | ODROID-H2                   | Desktop     | [b685ddc2ad](https://bsd-hardware.info/?probe=b685ddc2ad) | Dec 28, 2022 |
| Supermicro    | X10SDV-TP8F                 | Server      | [fa3c5f6504](https://bsd-hardware.info/?probe=fa3c5f6504) | Dec 28, 2022 |
| PC Engines    | APU2                        | Desktop     | [85da0654e1](https://bsd-hardware.info/?probe=85da0654e1) | Dec 28, 2022 |
| Intel         | CARLOW                      | Desktop     | [fa30f060f3](https://bsd-hardware.info/?probe=fa30f060f3) | Dec 28, 2022 |
| ASUSTek       | P11C-M Series               | Desktop     | [21f838983b](https://bsd-hardware.info/?probe=21f838983b) | Dec 28, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [9954c0abee](https://bsd-hardware.info/?probe=9954c0abee) | Dec 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [5b8ad02694](https://bsd-hardware.info/?probe=5b8ad02694) | Dec 28, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [5dafbbced0](https://bsd-hardware.info/?probe=5dafbbced0) | Dec 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [e70af54c3f](https://bsd-hardware.info/?probe=e70af54c3f) | Dec 28, 2022 |
| HP            | 1998                        | Desktop     | [afc7de60e3](https://bsd-hardware.info/?probe=afc7de60e3) | Dec 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [c3b95220d7](https://bsd-hardware.info/?probe=c3b95220d7) | Dec 28, 2022 |
| ZOTAC         | ZBOX-CI341                  | Mini pc     | [79d8b1477f](https://bsd-hardware.info/?probe=79d8b1477f) | Dec 28, 2022 |
| Shuttle       | FH110                       | Desktop     | [be457c2796](https://bsd-hardware.info/?probe=be457c2796) | Dec 27, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [8d3ab2cab5](https://bsd-hardware.info/?probe=8d3ab2cab5) | Dec 27, 2022 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [4bcc34fdca](https://bsd-hardware.info/?probe=4bcc34fdca) | Dec 27, 2022 |
| Intel         | D2500HN AAG81480-500        | Desktop     | [dae5627541](https://bsd-hardware.info/?probe=dae5627541) | Dec 27, 2022 |
| Lenovo        | 314D NOK                    | Mini pc     | [8cb1f1a8ea](https://bsd-hardware.info/?probe=8cb1f1a8ea) | Dec 27, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [3bdb5aa361](https://bsd-hardware.info/?probe=3bdb5aa361) | Dec 27, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [41094c24b2](https://bsd-hardware.info/?probe=41094c24b2) | Dec 27, 2022 |
| Dell          | 0X744K A02                  | Server      | [c63d853abc](https://bsd-hardware.info/?probe=c63d853abc) | Dec 27, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [b553cea3bd](https://bsd-hardware.info/?probe=b553cea3bd) | Dec 26, 2022 |
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
| Cisco         | ASA5515 A0                  | Desktop     | [9e587b9499](https://bsd-hardware.info/?probe=9e587b9499) | Dec 25, 2022 |
| Shuttle       | FH110                       | Desktop     | [a194756b95](https://bsd-hardware.info/?probe=a194756b95) | Dec 25, 2022 |
| HP            | 8062                        | Desktop     | [f4d3eb024d](https://bsd-hardware.info/?probe=f4d3eb024d) | Dec 25, 2022 |
| HP            | 213D A01                    | Desktop     | [bd620f0fc0](https://bsd-hardware.info/?probe=bd620f0fc0) | Dec 25, 2022 |
| MSI           | B560M-A PRO                 | Desktop     | [f1cb9703a7](https://bsd-hardware.info/?probe=f1cb9703a7) | Dec 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [bd212706ad](https://bsd-hardware.info/?probe=bd212706ad) | Dec 24, 2022 |
| Lenovo        | 314D NOK                    | Mini pc     | [af60c7ce81](https://bsd-hardware.info/?probe=af60c7ce81) | Dec 24, 2022 |
| Sophos        | UTM                         | Firewall    | [224580445a](https://bsd-hardware.info/?probe=224580445a) | Dec 24, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [33c59c687d](https://bsd-hardware.info/?probe=33c59c687d) | Dec 24, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [153f99a846](https://bsd-hardware.info/?probe=153f99a846) | Dec 24, 2022 |
| HP            | 8299                        | Desktop     | [6715ee2886](https://bsd-hardware.info/?probe=6715ee2886) | Dec 24, 2022 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [b29f2e4573](https://bsd-hardware.info/?probe=b29f2e4573) | Dec 24, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [701c6e95d6](https://bsd-hardware.info/?probe=701c6e95d6) | Dec 24, 2022 |
| ASRock        | N3710-NUC IPC               | Desktop     | [80c809e992](https://bsd-hardware.info/?probe=80c809e992) | Dec 24, 2022 |
| Biostar       | A32M2                       | Desktop     | [49c31b364c](https://bsd-hardware.info/?probe=49c31b364c) | Dec 23, 2022 |
| Biostar       | A10N-8800E                  | Desktop     | [d3d1107f77](https://bsd-hardware.info/?probe=d3d1107f77) | Dec 23, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [58b47341c9](https://bsd-hardware.info/?probe=58b47341c9) | Dec 23, 2022 |
| MSI           | A78M-E35                    | Desktop     | [03176e6683](https://bsd-hardware.info/?probe=03176e6683) | Dec 23, 2022 |
| Dell          | 0NW6H5 A00                  | Desktop     | [b19a4d1696](https://bsd-hardware.info/?probe=b19a4d1696) | Dec 23, 2022 |
| Dell          | 03X6X0 A00                  | Server      | [52327286e4](https://bsd-hardware.info/?probe=52327286e4) | Dec 23, 2022 |
| Dell          | 03X6X0 A00                  | Server      | [0d70cc442b](https://bsd-hardware.info/?probe=0d70cc442b) | Dec 23, 2022 |
| ASRock        | B75M R2.0                   | Desktop     | [3a8d5c61b6](https://bsd-hardware.info/?probe=3a8d5c61b6) | Dec 23, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [7cccecfde1](https://bsd-hardware.info/?probe=7cccecfde1) | Dec 23, 2022 |
| Intel BOX4... | Geminilake                  | Desktop     | [a2b2b7c25f](https://bsd-hardware.info/?probe=a2b2b7c25f) | Dec 23, 2022 |
| Intel BOX4... | Geminilake                  | Desktop     | [06933f3d87](https://bsd-hardware.info/?probe=06933f3d87) | Dec 23, 2022 |
| Unknown       | QD-WHLU01                   | Desktop     | [a0fb185069](https://bsd-hardware.info/?probe=a0fb185069) | Dec 23, 2022 |
| Dell          | 03X6X0 A02                  | Server      | [e0b4e13386](https://bsd-hardware.info/?probe=e0b4e13386) | Dec 23, 2022 |
| MSI           | B560M-A PRO                 | Desktop     | [8325caa4d6](https://bsd-hardware.info/?probe=8325caa4d6) | Dec 23, 2022 |
| HP            | 8299                        | Desktop     | [d9eec3c9f5](https://bsd-hardware.info/?probe=d9eec3c9f5) | Dec 23, 2022 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [91a89db2ab](https://bsd-hardware.info/?probe=91a89db2ab) | Dec 23, 2022 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [bc2c536004](https://bsd-hardware.info/?probe=bc2c536004) | Dec 23, 2022 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [58ca7ca7d4](https://bsd-hardware.info/?probe=58ca7ca7d4) | Dec 23, 2022 |
| Deciso        | OPNsense Appliance          | Notebook    | [062fb4cccd](https://bsd-hardware.info/?probe=062fb4cccd) | Dec 23, 2022 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [dfd3e7acb1](https://bsd-hardware.info/?probe=dfd3e7acb1) | Dec 23, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [daaad6a386](https://bsd-hardware.info/?probe=daaad6a386) | Dec 23, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [67bc182d1d](https://bsd-hardware.info/?probe=67bc182d1d) | Dec 23, 2022 |
| MSI           | B560M-A PRO                 | Desktop     | [6f8bdb560b](https://bsd-hardware.info/?probe=6f8bdb560b) | Dec 23, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [cde7bad6c3](https://bsd-hardware.info/?probe=cde7bad6c3) | Dec 22, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [78bcccda01](https://bsd-hardware.info/?probe=78bcccda01) | Dec 22, 2022 |
| Dell          | 060J9C A00                  | Mini pc     | [29b3e0b639](https://bsd-hardware.info/?probe=29b3e0b639) | Dec 22, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [01d8e43ee1](https://bsd-hardware.info/?probe=01d8e43ee1) | Dec 22, 2022 |
| Unknown       | Unknown                     | Desktop     | [0f03a7f2ce](https://bsd-hardware.info/?probe=0f03a7f2ce) | Dec 22, 2022 |
| AAEON         | FWS-2251 V1.0               | Desktop     | [a4ff0a7ec5](https://bsd-hardware.info/?probe=a4ff0a7ec5) | Dec 22, 2022 |
| ZOTAC         | ZBOX-MI640/MI660/MI620NA... | Mini pc     | [9e817a9114](https://bsd-hardware.info/?probe=9e817a9114) | Dec 22, 2022 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [90dfe8ee6b](https://bsd-hardware.info/?probe=90dfe8ee6b) | Dec 22, 2022 |
| Acer          | WG43M                       | Desktop     | [d316352c20](https://bsd-hardware.info/?probe=d316352c20) | Dec 22, 2022 |
| Supermicro    | X10SDV-8C-TLN4F+            | Server      | [633b9a5425](https://bsd-hardware.info/?probe=633b9a5425) | Dec 22, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [2ac107df0f](https://bsd-hardware.info/?probe=2ac107df0f) | Dec 22, 2022 |
| AMI           | Cherry Trail CR             | Mini pc     | [cc9eb40ce1](https://bsd-hardware.info/?probe=cc9eb40ce1) | Dec 22, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [f241237f76](https://bsd-hardware.info/?probe=f241237f76) | Dec 22, 2022 |
| Dell          | 0WR7PY A02                  | Desktop     | [0c3fea5eb0](https://bsd-hardware.info/?probe=0c3fea5eb0) | Dec 22, 2022 |
| Unknown       | Unknown                     | Desktop     | [0a40b02aeb](https://bsd-hardware.info/?probe=0a40b02aeb) | Dec 22, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [df221cefbc](https://bsd-hardware.info/?probe=df221cefbc) | Dec 22, 2022 |
| ZOTAC         | ZBOX-MI640/MI660/MI620NA... | Mini pc     | [16589e2878](https://bsd-hardware.info/?probe=16589e2878) | Dec 21, 2022 |
| HP            | ProLiant DL360 Gen9         | Server      | [17ddf8c2e1](https://bsd-hardware.info/?probe=17ddf8c2e1) | Dec 21, 2022 |
| PC Engines    | APU2                        | Desktop     | [9781d92062](https://bsd-hardware.info/?probe=9781d92062) | Dec 21, 2022 |
| Dell          | 0KYJ8C A02                  | Desktop     | [490f20c93d](https://bsd-hardware.info/?probe=490f20c93d) | Dec 21, 2022 |
| PC Engines    | APU2                        | Desktop     | [e94b983d48](https://bsd-hardware.info/?probe=e94b983d48) | Dec 21, 2022 |
| ACMA          | X8SIE                       | Desktop     | [01898b2ffb](https://bsd-hardware.info/?probe=01898b2ffb) | Dec 21, 2022 |
| Intel         | S3420GP E51976-407          | Server      | [c614a1e46f](https://bsd-hardware.info/?probe=c614a1e46f) | Dec 20, 2022 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [16f59f69dc](https://bsd-hardware.info/?probe=16f59f69dc) | Dec 20, 2022 |
| Unknown       | Unknown                     | Desktop     | [0bffe61dae](https://bsd-hardware.info/?probe=0bffe61dae) | Dec 20, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [3502cb3d47](https://bsd-hardware.info/?probe=3502cb3d47) | Dec 20, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [a8ec4c3ae4](https://bsd-hardware.info/?probe=a8ec4c3ae4) | Dec 20, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [4667028e67](https://bsd-hardware.info/?probe=4667028e67) | Dec 20, 2022 |
| Protectli     | FW2B Ver                    | Desktop     | [9596576df7](https://bsd-hardware.info/?probe=9596576df7) | Dec 20, 2022 |
| Lenovo        | 3098 SDK0E50510 PRO or W... | Desktop     | [e1e1a80328](https://bsd-hardware.info/?probe=e1e1a80328) | Dec 20, 2022 |
| Dell          | 0X744K A02                  | Server      | [e45fc09011](https://bsd-hardware.info/?probe=e45fc09011) | Dec 20, 2022 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | Desktop     | [2ea413db31](https://bsd-hardware.info/?probe=2ea413db31) | Dec 20, 2022 |
| ASRock        | 4X4-4000 Series             | Desktop     | [31f17adc5b](https://bsd-hardware.info/?probe=31f17adc5b) | Dec 20, 2022 |
| Dell          | 0WR7PY A00                  | Desktop     | [360336dcc1](https://bsd-hardware.info/?probe=360336dcc1) | Dec 20, 2022 |
| Unknown       | Unknown                     | Notebook    | [364b3758b6](https://bsd-hardware.info/?probe=364b3758b6) | Dec 20, 2022 |
| Sophos        | SG                          | Firewall    | [5536740301](https://bsd-hardware.info/?probe=5536740301) | Dec 20, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [3c36f8db41](https://bsd-hardware.info/?probe=3c36f8db41) | Dec 20, 2022 |
| Supermicro    | X10SDV-4C-TLN4F             | Server      | [c0c8d1f85e](https://bsd-hardware.info/?probe=c0c8d1f85e) | Dec 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [4c5ccd04d0](https://bsd-hardware.info/?probe=4c5ccd04d0) | Dec 19, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [b84941cdd5](https://bsd-hardware.info/?probe=b84941cdd5) | Dec 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [5d37a0669c](https://bsd-hardware.info/?probe=5d37a0669c) | Dec 19, 2022 |
| Dell          | 0WR7PY A02                  | Desktop     | [67baacfc7d](https://bsd-hardware.info/?probe=67baacfc7d) | Dec 19, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [c9de65beeb](https://bsd-hardware.info/?probe=c9de65beeb) | Dec 19, 2022 |
| PC Engines    | APU2                        | Desktop     | [5de84cb508](https://bsd-hardware.info/?probe=5de84cb508) | Dec 19, 2022 |
| Pegatron      | 2ACF                        | Desktop     | [511f2a6d16](https://bsd-hardware.info/?probe=511f2a6d16) | Dec 19, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [fad0a431e5](https://bsd-hardware.info/?probe=fad0a431e5) | Dec 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [f876d5d5b1](https://bsd-hardware.info/?probe=f876d5d5b1) | Dec 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [3d77f833b0](https://bsd-hardware.info/?probe=3d77f833b0) | Dec 19, 2022 |
| Dell          | 0VD50G A01                  | Server      | [07852bf200](https://bsd-hardware.info/?probe=07852bf200) | Dec 19, 2022 |
| HP            | ProLiant DL360p Gen8        | Server      | [b9df714117](https://bsd-hardware.info/?probe=b9df714117) | Dec 19, 2022 |
| Supermicro    | X11SSL-F                    | Server      | [7bd99b62ab](https://bsd-hardware.info/?probe=7bd99b62ab) | Dec 19, 2022 |
| Dell          | Edge Gateway 5000           | Mini pc     | [0af7422e2f](https://bsd-hardware.info/?probe=0af7422e2f) | Dec 18, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [f321130f0e](https://bsd-hardware.info/?probe=f321130f0e) | Dec 18, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [14d483ac06](https://bsd-hardware.info/?probe=14d483ac06) | Dec 18, 2022 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [53a90a6c63](https://bsd-hardware.info/?probe=53a90a6c63) | Dec 18, 2022 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [abe21b9c9e](https://bsd-hardware.info/?probe=abe21b9c9e) | Dec 18, 2022 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [fc7928dfe9](https://bsd-hardware.info/?probe=fc7928dfe9) | Dec 18, 2022 |
| ASRock        | E3C224D2I                   | Desktop     | [106e525671](https://bsd-hardware.info/?probe=106e525671) | Dec 18, 2022 |
| Supermicro    | X11SCL-F                    | Server      | [638b27bc34](https://bsd-hardware.info/?probe=638b27bc34) | Dec 18, 2022 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | Desktop     | [1f1de1d49c](https://bsd-hardware.info/?probe=1f1de1d49c) | Dec 18, 2022 |
| ASRock        | H370M-ITX/ac                | Desktop     | [a40ada7f7f](https://bsd-hardware.info/?probe=a40ada7f7f) | Dec 18, 2022 |
| Unknown       | Unknown                     | Desktop     | [f6fababc22](https://bsd-hardware.info/?probe=f6fababc22) | Dec 18, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [e06fa5d522](https://bsd-hardware.info/?probe=e06fa5d522) | Dec 18, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [a1b29c356e](https://bsd-hardware.info/?probe=a1b29c356e) | Dec 17, 2022 |
| Protectli     | FW6                         | Desktop     | [56f62226e7](https://bsd-hardware.info/?probe=56f62226e7) | Dec 17, 2022 |
| PC Engines    | APU3                        | Desktop     | [5597cca988](https://bsd-hardware.info/?probe=5597cca988) | Dec 17, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [92593f4e79](https://bsd-hardware.info/?probe=92593f4e79) | Dec 17, 2022 |
| MSI           | MS-98C8                     | Desktop     | [a6e45c8e5f](https://bsd-hardware.info/?probe=a6e45c8e5f) | Dec 17, 2022 |
| PC Engines    | APU3                        | Desktop     | [0e1197c771](https://bsd-hardware.info/?probe=0e1197c771) | Dec 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [0e98358cf3](https://bsd-hardware.info/?probe=0e98358cf3) | Dec 17, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [e8095445e8](https://bsd-hardware.info/?probe=e8095445e8) | Dec 17, 2022 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [088766f04d](https://bsd-hardware.info/?probe=088766f04d) | Dec 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [f7700c781d](https://bsd-hardware.info/?probe=f7700c781d) | Dec 17, 2022 |
| Dell          | 03X6X0 A02                  | Server      | [f6085ba691](https://bsd-hardware.info/?probe=f6085ba691) | Dec 17, 2022 |
| Intel         | CRESCENTBAY                 | Desktop     | [7981529337](https://bsd-hardware.info/?probe=7981529337) | Dec 17, 2022 |
| PC Engines    | APU                         | Desktop     | [19786edc61](https://bsd-hardware.info/?probe=19786edc61) | Dec 17, 2022 |
| Dell          | 0FDY5C A00                  | Desktop     | [afef2952f9](https://bsd-hardware.info/?probe=afef2952f9) | Dec 17, 2022 |
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
| Intel         | DQ77KB AAG81483-501         | Desktop     | [cc51093e02](https://bsd-hardware.info/?probe=cc51093e02) | Dec 16, 2022 |
| ASRock        | Q2900M                      | Desktop     | [42a53e5201](https://bsd-hardware.info/?probe=42a53e5201) | Dec 16, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [fa8c102cfd](https://bsd-hardware.info/?probe=fa8c102cfd) | Dec 16, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [3faaaa8209](https://bsd-hardware.info/?probe=3faaaa8209) | Dec 16, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [d9376f2f63](https://bsd-hardware.info/?probe=d9376f2f63) | Dec 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [01e26ec145](https://bsd-hardware.info/?probe=01e26ec145) | Dec 15, 2022 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [40911b66e2](https://bsd-hardware.info/?probe=40911b66e2) | Dec 15, 2022 |
| Supermicro    | X11SBA-LN4F                 | Server      | [649d525fdb](https://bsd-hardware.info/?probe=649d525fdb) | Dec 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [9ac68a1c6d](https://bsd-hardware.info/?probe=9ac68a1c6d) | Dec 15, 2022 |
| Gigabyte      | N3160ND3V                   | Desktop     | [c84bedc821](https://bsd-hardware.info/?probe=c84bedc821) | Dec 15, 2022 |
| Unknown       | SKYBAY                      | Desktop     | [deb30193e2](https://bsd-hardware.info/?probe=deb30193e2) | Dec 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [e3508ce360](https://bsd-hardware.info/?probe=e3508ce360) | Dec 15, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [435807287e](https://bsd-hardware.info/?probe=435807287e) | Dec 15, 2022 |
| Dell          | 0WR7PY A00                  | Desktop     | [f923c6c0d6](https://bsd-hardware.info/?probe=f923c6c0d6) | Dec 15, 2022 |
| Lenovo        | 3098 SDK0E50510 PRO or W... | Desktop     | [7cb1b0cc2d](https://bsd-hardware.info/?probe=7cb1b0cc2d) | Dec 15, 2022 |
| Intel         | H81U                        | Notebook    | [fab3eecc66](https://bsd-hardware.info/?probe=fab3eecc66) | Dec 15, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [e199c0ec3d](https://bsd-hardware.info/?probe=e199c0ec3d) | Dec 15, 2022 |
| Sophos        | SG                          | Firewall    | [16753b9090](https://bsd-hardware.info/?probe=16753b9090) | Dec 15, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [35ecaf0406](https://bsd-hardware.info/?probe=35ecaf0406) | Dec 15, 2022 |
| ZOTAC         | ZBOX-MI640/MI660/MI620NA... | Mini pc     | [9d71e35375](https://bsd-hardware.info/?probe=9d71e35375) | Dec 15, 2022 |
| ZOTAC         | ZBOX-MI640/MI660/MI620NA... | Mini pc     | [98621b669c](https://bsd-hardware.info/?probe=98621b669c) | Dec 15, 2022 |
| ZOTAC         | ZBOX-MI640/MI660/MI620NA... | Mini pc     | [b0639c3d01](https://bsd-hardware.info/?probe=b0639c3d01) | Dec 15, 2022 |
| ZOTAC         | ZBOX-MI640/MI660/MI620NA... | Mini pc     | [52fbc8ccf7](https://bsd-hardware.info/?probe=52fbc8ccf7) | Dec 15, 2022 |
| Dell          | 0CU409                      | Desktop     | [718c9c5c8b](https://bsd-hardware.info/?probe=718c9c5c8b) | Dec 15, 2022 |
| Dell          | 0CU409                      | Desktop     | [161da6b850](https://bsd-hardware.info/?probe=161da6b850) | Dec 15, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [d7d0ebf605](https://bsd-hardware.info/?probe=d7d0ebf605) | Dec 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [210418cc84](https://bsd-hardware.info/?probe=210418cc84) | Dec 15, 2022 |
| HP            | 1495                        | Desktop     | [04bd0455f2](https://bsd-hardware.info/?probe=04bd0455f2) | Dec 14, 2022 |
| Supermicro    | A1SRM-2758F                 | Server      | [fb96378782](https://bsd-hardware.info/?probe=fb96378782) | Dec 14, 2022 |
| Intel         | H81U                        | Notebook    | [fe1c3cb754](https://bsd-hardware.info/?probe=fe1c3cb754) | Dec 14, 2022 |
| Dell          | 0X4N41 A01                  | Desktop     | [4091e15cac](https://bsd-hardware.info/?probe=4091e15cac) | Dec 14, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [64c549f3ae](https://bsd-hardware.info/?probe=64c549f3ae) | Dec 14, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [e44f465325](https://bsd-hardware.info/?probe=e44f465325) | Dec 14, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [cb16bb9431](https://bsd-hardware.info/?probe=cb16bb9431) | Dec 14, 2022 |
| NF541         | 1.0                         | Desktop     | [b0644bada6](https://bsd-hardware.info/?probe=b0644bada6) | Dec 14, 2022 |
| HP            | 1495                        | Desktop     | [23f8aeada7](https://bsd-hardware.info/?probe=23f8aeada7) | Dec 14, 2022 |
| HP            | 2215                        | Desktop     | [76f607b100](https://bsd-hardware.info/?probe=76f607b100) | Dec 14, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [a77d60297f](https://bsd-hardware.info/?probe=a77d60297f) | Dec 14, 2022 |
| Unknown       | Unknown                     | Desktop     | [85520bf6bf](https://bsd-hardware.info/?probe=85520bf6bf) | Dec 14, 2022 |
| Dell          | 03X6X0 A02                  | Server      | [6ebcd7c974](https://bsd-hardware.info/?probe=6ebcd7c974) | Dec 14, 2022 |
| Unknown       | Unknown                     | Desktop     | [ad7f977515](https://bsd-hardware.info/?probe=ad7f977515) | Dec 13, 2022 |
| AZW           | U59                         | Desktop     | [9b22c68e98](https://bsd-hardware.info/?probe=9b22c68e98) | Dec 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [ec6827e543](https://bsd-hardware.info/?probe=ec6827e543) | Dec 13, 2022 |
| Unknown       | SKYBAY                      | Desktop     | [2d6c881723](https://bsd-hardware.info/?probe=2d6c881723) | Dec 13, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [abed96a938](https://bsd-hardware.info/?probe=abed96a938) | Dec 13, 2022 |
| Gigabyte      | Z590 AORUS PRO AX           | Desktop     | [66e0c118d2](https://bsd-hardware.info/?probe=66e0c118d2) | Dec 13, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [af9df0d2c9](https://bsd-hardware.info/?probe=af9df0d2c9) | Dec 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [9ee8d1082b](https://bsd-hardware.info/?probe=9ee8d1082b) | Dec 12, 2022 |
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
| Sophos        | XG                          | Firewall    | [e35b3151a3](https://bsd-hardware.info/?probe=e35b3151a3) | Dec 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [fa8afd004f](https://bsd-hardware.info/?probe=fa8afd004f) | Dec 11, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [ad71b00b0d](https://bsd-hardware.info/?probe=ad71b00b0d) | Dec 11, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [d79604d043](https://bsd-hardware.info/?probe=d79604d043) | Dec 11, 2022 |
| HP            | 82B4                        | Desktop     | [c47cb195e0](https://bsd-hardware.info/?probe=c47cb195e0) | Dec 11, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [3124aaaf95](https://bsd-hardware.info/?probe=3124aaaf95) | Dec 11, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [b1bd01549a](https://bsd-hardware.info/?probe=b1bd01549a) | Dec 11, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [4b14039072](https://bsd-hardware.info/?probe=4b14039072) | Dec 11, 2022 |
| Dell          | 03X6X0 A02                  | Server      | [0939871923](https://bsd-hardware.info/?probe=0939871923) | Dec 11, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [808108016d](https://bsd-hardware.info/?probe=808108016d) | Dec 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [def65f518e](https://bsd-hardware.info/?probe=def65f518e) | Dec 10, 2022 |
| Fujitsu       | D3313-S1 S26361-D3313-S1    | Desktop     | [7570f3ae64](https://bsd-hardware.info/?probe=7570f3ae64) | Dec 10, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [6b64c3dbaf](https://bsd-hardware.info/?probe=6b64c3dbaf) | Dec 10, 2022 |
| HP            | 213D A01                    | Desktop     | [6c83f31e71](https://bsd-hardware.info/?probe=6c83f31e71) | Dec 10, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [0b08951f1c](https://bsd-hardware.info/?probe=0b08951f1c) | Dec 10, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [342c99d07d](https://bsd-hardware.info/?probe=342c99d07d) | Dec 10, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [33395e819a](https://bsd-hardware.info/?probe=33395e819a) | Dec 10, 2022 |
| Supermicro    | X10SLL-F                    | Server      | [7d80c62813](https://bsd-hardware.info/?probe=7d80c62813) | Dec 09, 2022 |
| Dell          | 06X1TJ A00                  | Desktop     | [1115d508c1](https://bsd-hardware.info/?probe=1115d508c1) | Dec 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [0405fd0f0d](https://bsd-hardware.info/?probe=0405fd0f0d) | Dec 09, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [073c2c8de0](https://bsd-hardware.info/?probe=073c2c8de0) | Dec 09, 2022 |
| Hardkernel    | ODROID-H3                   | Desktop     | [cd6aa62212](https://bsd-hardware.info/?probe=cd6aa62212) | Dec 09, 2022 |
| HP            | 1495                        | Desktop     | [3eab39d89f](https://bsd-hardware.info/?probe=3eab39d89f) | Dec 09, 2022 |
| Sophos        | SG                          | Firewall    | [07fbfad254](https://bsd-hardware.info/?probe=07fbfad254) | Dec 09, 2022 |
| Dell          | 0DRG19 A00                  | Mini pc     | [bbca9fc84f](https://bsd-hardware.info/?probe=bbca9fc84f) | Dec 09, 2022 |
| Sophos        | SG                          | Firewall    | [a3b0edbd3c](https://bsd-hardware.info/?probe=a3b0edbd3c) | Dec 09, 2022 |
| Gigabyte      | H81M-S                      | Desktop     | [094ac0c253](https://bsd-hardware.info/?probe=094ac0c253) | Dec 09, 2022 |
| Protectli     | VP2410 10                   | Desktop     | [3f55143fd9](https://bsd-hardware.info/?probe=3f55143fd9) | Dec 09, 2022 |
| MSI           | B450M BAZOOKA MAX WIFI      | Desktop     | [6b03cb139e](https://bsd-hardware.info/?probe=6b03cb139e) | Dec 09, 2022 |
| Dell          | 05GD68 A00                  | Desktop     | [b2f0da8246](https://bsd-hardware.info/?probe=b2f0da8246) | Dec 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [493df1f529](https://bsd-hardware.info/?probe=493df1f529) | Dec 09, 2022 |
| PC Engines    | apu4                        | Desktop     | [3e3ab7f196](https://bsd-hardware.info/?probe=3e3ab7f196) | Dec 09, 2022 |
| AMI           | PEISIA E3845 VER1.0         | Desktop     | [0ac47aa8a0](https://bsd-hardware.info/?probe=0ac47aa8a0) | Dec 09, 2022 |
| Supermicro    | X10SLL-F                    | Server      | [b2720b8b88](https://bsd-hardware.info/?probe=b2720b8b88) | Dec 08, 2022 |
| Deciso        | NetBoard-A10                | Notebook    | [79b2a5d3a5](https://bsd-hardware.info/?probe=79b2a5d3a5) | Dec 08, 2022 |
| Dell          | 0TY019 A02                  | Server      | [84b683ec0b](https://bsd-hardware.info/?probe=84b683ec0b) | Dec 08, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [84f8198c18](https://bsd-hardware.info/?probe=84f8198c18) | Dec 08, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [dbbdd023e9](https://bsd-hardware.info/?probe=dbbdd023e9) | Dec 08, 2022 |
| Protectli     | FW4C Ver                    | Desktop     | [71368e5cde](https://bsd-hardware.info/?probe=71368e5cde) | Dec 08, 2022 |
| Deciso        | NetBoard-A10                | Notebook    | [575d201794](https://bsd-hardware.info/?probe=575d201794) | Dec 07, 2022 |
| ASUSTek       | G11CD                       | Desktop     | [7bc1746333](https://bsd-hardware.info/?probe=7bc1746333) | Dec 07, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [294f283d65](https://bsd-hardware.info/?probe=294f283d65) | Dec 07, 2022 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [9862c1b507](https://bsd-hardware.info/?probe=9862c1b507) | Dec 07, 2022 |
| Lenovo        | 319E SEK0T35577 IOT 4247... | Mini pc     | [33545a5181](https://bsd-hardware.info/?probe=33545a5181) | Dec 07, 2022 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [6db81b5ffe](https://bsd-hardware.info/?probe=6db81b5ffe) | Dec 07, 2022 |
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
| Dell          | 0WMJ54 A01                  | Desktop     | [61347ab3e9](https://bsd-hardware.info/?probe=61347ab3e9) | Dec 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [e3dad11b11](https://bsd-hardware.info/?probe=e3dad11b11) | Dec 06, 2022 |
| Supermicro    | X10SLM+-LN4F                | Server      | [319819f81d](https://bsd-hardware.info/?probe=319819f81d) | Dec 06, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [657972a55d](https://bsd-hardware.info/?probe=657972a55d) | Dec 06, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [33f23b1291](https://bsd-hardware.info/?probe=33f23b1291) | Dec 06, 2022 |
| YANYU         | R250                        | Desktop     | [bb364271b2](https://bsd-hardware.info/?probe=bb364271b2) | Dec 05, 2022 |
| DFI           | BE17X(170/171/173)          | Notebook    | [9822160345](https://bsd-hardware.info/?probe=9822160345) | Dec 05, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [eaa3b9783e](https://bsd-hardware.info/?probe=eaa3b9783e) | Dec 05, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [f130844e1e](https://bsd-hardware.info/?probe=f130844e1e) | Dec 05, 2022 |
| PC Engines    | apu4                        | Desktop     | [72061eb254](https://bsd-hardware.info/?probe=72061eb254) | Dec 05, 2022 |
| ACMA          | X8SIE                       | Desktop     | [361e4ccc04](https://bsd-hardware.info/?probe=361e4ccc04) | Dec 05, 2022 |
| Intel         | NUC6CAYB J23203-405         | Mini pc     | [218e00e7ea](https://bsd-hardware.info/?probe=218e00e7ea) | Dec 05, 2022 |
| Dell          | 0CNWVK A00                  | Desktop     | [5a022db6bf](https://bsd-hardware.info/?probe=5a022db6bf) | Dec 05, 2022 |
| Intel         | CARLOW                      | Desktop     | [1b45524779](https://bsd-hardware.info/?probe=1b45524779) | Dec 05, 2022 |
| Supermicro    | X11SDV-4C-TP8F              | Desktop     | [05566134f9](https://bsd-hardware.info/?probe=05566134f9) | Dec 05, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [aa9482884f](https://bsd-hardware.info/?probe=aa9482884f) | Dec 05, 2022 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [90279b62b7](https://bsd-hardware.info/?probe=90279b62b7) | Dec 05, 2022 |
| Shuttle       | FS77U                       | Desktop     | [4172b79cfc](https://bsd-hardware.info/?probe=4172b79cfc) | Dec 04, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [54d1511b82](https://bsd-hardware.info/?probe=54d1511b82) | Dec 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [54e89ef90b](https://bsd-hardware.info/?probe=54e89ef90b) | Dec 04, 2022 |
| MSI           | B560M-A PRO                 | Desktop     | [be5f6ad306](https://bsd-hardware.info/?probe=be5f6ad306) | Dec 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [af4f0984ae](https://bsd-hardware.info/?probe=af4f0984ae) | Dec 04, 2022 |
| ASUSTek       | E35M1-I DELUXE              | Desktop     | [1a183385c7](https://bsd-hardware.info/?probe=1a183385c7) | Dec 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [d9113585f0](https://bsd-hardware.info/?probe=d9113585f0) | Dec 04, 2022 |
| Sophos        | XG                          | Firewall    | [a51c56cb12](https://bsd-hardware.info/?probe=a51c56cb12) | Dec 04, 2022 |
| ShenZhen M... | MW-GMLK-2.5G6L              | Desktop     | [0bdf47ea4c](https://bsd-hardware.info/?probe=0bdf47ea4c) | Dec 04, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [f34b488e42](https://bsd-hardware.info/?probe=f34b488e42) | Dec 04, 2022 |
| Dell          | 0GXM1W A00                  | Desktop     | [9497657cb2](https://bsd-hardware.info/?probe=9497657cb2) | Dec 04, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [94f78cb509](https://bsd-hardware.info/?probe=94f78cb509) | Dec 03, 2022 |
| Dell          | 0PTTT9 A01                  | Desktop     | [1916a4064b](https://bsd-hardware.info/?probe=1916a4064b) | Dec 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [90de1777bc](https://bsd-hardware.info/?probe=90de1777bc) | Dec 02, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [f6c721906b](https://bsd-hardware.info/?probe=f6c721906b) | Dec 02, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [5e75bcdb11](https://bsd-hardware.info/?probe=5e75bcdb11) | Dec 02, 2022 |
| Deciso        | Netboard A10 V2.1           | Desktop     | [40a0d948b4](https://bsd-hardware.info/?probe=40a0d948b4) | Dec 02, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [f8719b2320](https://bsd-hardware.info/?probe=f8719b2320) | Dec 02, 2022 |
| Dell          | 0KYJ8C A02                  | Desktop     | [c0c4fa9349](https://bsd-hardware.info/?probe=c0c4fa9349) | Dec 02, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [5c3941eb3f](https://bsd-hardware.info/?probe=5c3941eb3f) | Dec 02, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [d3b72fdce8](https://bsd-hardware.info/?probe=d3b72fdce8) | Dec 02, 2022 |
| Intel         | D33217CK G76541-300         | Desktop     | [545a39b1e4](https://bsd-hardware.info/?probe=545a39b1e4) | Dec 02, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [4bf1aae972](https://bsd-hardware.info/?probe=4bf1aae972) | Dec 02, 2022 |
| Unknown       | Unknown                     | Desktop     | [243e309a04](https://bsd-hardware.info/?probe=243e309a04) | Dec 01, 2022 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [03708406e8](https://bsd-hardware.info/?probe=03708406e8) | Dec 01, 2022 |
| HP            | 8054                        | Desktop     | [c25adeb2ff](https://bsd-hardware.info/?probe=c25adeb2ff) | Dec 01, 2022 |
| Thomas-Kre... | P9A-I/2550/4L               | Firewall    | [6bec1ec37d](https://bsd-hardware.info/?probe=6bec1ec37d) | Dec 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [32a4df9cae](https://bsd-hardware.info/?probe=32a4df9cae) | Dec 01, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [a7c2e16f5c](https://bsd-hardware.info/?probe=a7c2e16f5c) | Dec 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [504a659236](https://bsd-hardware.info/?probe=504a659236) | Dec 01, 2022 |
| MSI           | Z87I                        | Desktop     | [570046969c](https://bsd-hardware.info/?probe=570046969c) | Dec 01, 2022 |
| HP            | 8103 A01                    | Mini pc     | [5cd982c2ee](https://bsd-hardware.info/?probe=5cd982c2ee) | Nov 30, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [84d1656c05](https://bsd-hardware.info/?probe=84d1656c05) | Nov 30, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [6a1a5865cb](https://bsd-hardware.info/?probe=6a1a5865cb) | Nov 30, 2022 |
| PC Engines    | apu4                        | Desktop     | [7c8b9014b1](https://bsd-hardware.info/?probe=7c8b9014b1) | Nov 30, 2022 |
| PC Engines    | apu4                        | Desktop     | [dd39e91713](https://bsd-hardware.info/?probe=dd39e91713) | Nov 30, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [794e041b13](https://bsd-hardware.info/?probe=794e041b13) | Nov 30, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [ac4f4b181a](https://bsd-hardware.info/?probe=ac4f4b181a) | Nov 30, 2022 |
| Protectli     | FW6                         | Desktop     | [95f3201109](https://bsd-hardware.info/?probe=95f3201109) | Nov 30, 2022 |
| Protectli     | FW4A Ver                    | Desktop     | [9e6e0f5548](https://bsd-hardware.info/?probe=9e6e0f5548) | Nov 30, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [f3b09cfb70](https://bsd-hardware.info/?probe=f3b09cfb70) | Nov 30, 2022 |
| Intel         | D33217CK G76541-300         | Desktop     | [bbdd9a1b98](https://bsd-hardware.info/?probe=bbdd9a1b98) | Nov 30, 2022 |
| Sophos        | SG                          | Firewall    | [357c380b7c](https://bsd-hardware.info/?probe=357c380b7c) | Nov 29, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [cfaeaeb2f2](https://bsd-hardware.info/?probe=cfaeaeb2f2) | Nov 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [a5b10d3f79](https://bsd-hardware.info/?probe=a5b10d3f79) | Nov 29, 2022 |
| ACMA          | X8SIE                       | Desktop     | [532b81e55f](https://bsd-hardware.info/?probe=532b81e55f) | Nov 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [7308d658dc](https://bsd-hardware.info/?probe=7308d658dc) | Nov 29, 2022 |
| ZOTAC         | ZBOX-CI341                  | Mini pc     | [2299087d09](https://bsd-hardware.info/?probe=2299087d09) | Nov 29, 2022 |
| Unknown       | A04                         | Server      | [07f21afacc](https://bsd-hardware.info/?probe=07f21afacc) | Nov 29, 2022 |
| Lenovo        | 316A SDK0J40697 WIN 3305... | Mini pc     | [26c9557a0a](https://bsd-hardware.info/?probe=26c9557a0a) | Nov 29, 2022 |
| HP            | 8299                        | Desktop     | [d697a2e953](https://bsd-hardware.info/?probe=d697a2e953) | Nov 29, 2022 |
| ACMA          | X8SIE                       | Desktop     | [d0112d027b](https://bsd-hardware.info/?probe=d0112d027b) | Nov 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [4e40278b06](https://bsd-hardware.info/?probe=4e40278b06) | Nov 28, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [28dd3a0b1b](https://bsd-hardware.info/?probe=28dd3a0b1b) | Nov 28, 2022 |
| Deciso        | Netboard A10 GEN2 Model ... | Desktop     | [d48dbd053d](https://bsd-hardware.info/?probe=d48dbd053d) | Nov 28, 2022 |
| PC Engines    | apu4                        | Desktop     | [588e065800](https://bsd-hardware.info/?probe=588e065800) | Nov 28, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [e850e0ae9c](https://bsd-hardware.info/?probe=e850e0ae9c) | Nov 28, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [35950045c6](https://bsd-hardware.info/?probe=35950045c6) | Nov 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [2fe35064cb](https://bsd-hardware.info/?probe=2fe35064cb) | Nov 28, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [b1f32ca8a1](https://bsd-hardware.info/?probe=b1f32ca8a1) | Nov 28, 2022 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | Desktop     | [b4cc780c40](https://bsd-hardware.info/?probe=b4cc780c40) | Nov 28, 2022 |
| Shuttle       | FS81                        | Desktop     | [f714ba647f](https://bsd-hardware.info/?probe=f714ba647f) | Nov 28, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [fd111870fa](https://bsd-hardware.info/?probe=fd111870fa) | Nov 28, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [ae55a799e8](https://bsd-hardware.info/?probe=ae55a799e8) | Nov 28, 2022 |
| PC Engines    | apu6                        | Desktop     | [13dcbe5748](https://bsd-hardware.info/?probe=13dcbe5748) | Nov 27, 2022 |
| YANYU         | R250                        | Desktop     | [0be0925e5b](https://bsd-hardware.info/?probe=0be0925e5b) | Nov 27, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [e8e158f783](https://bsd-hardware.info/?probe=e8e158f783) | Nov 27, 2022 |
| Supermicro    | X10SRG-F                    | Desktop     | [66b7819b2a](https://bsd-hardware.info/?probe=66b7819b2a) | Nov 27, 2022 |
| Unknown       | Unknown                     | Desktop     | [512a05eefb](https://bsd-hardware.info/?probe=512a05eefb) | Nov 27, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [ed6b1f75ae](https://bsd-hardware.info/?probe=ed6b1f75ae) | Nov 27, 2022 |
| ASRock        | J4125B-ITX                  | Desktop     | [ad497a63ac](https://bsd-hardware.info/?probe=ad497a63ac) | Nov 27, 2022 |
| HP            | 18E7                        | Desktop     | [c7635c715f](https://bsd-hardware.info/?probe=c7635c715f) | Nov 26, 2022 |
| Intel         | DH87MC AAG74242-401         | Desktop     | [33c1878560](https://bsd-hardware.info/?probe=33c1878560) | Nov 26, 2022 |
| CompuLab      | fit-PC3                     | Mini pc     | [34dd85f78d](https://bsd-hardware.info/?probe=34dd85f78d) | Nov 26, 2022 |
| ASUSTek       | P5K-E                       | Desktop     | [2b00248458](https://bsd-hardware.info/?probe=2b00248458) | Nov 26, 2022 |
| Intel         | CRESCENTBAY                 | Desktop     | [bd1f1fa769](https://bsd-hardware.info/?probe=bd1f1fa769) | Nov 26, 2022 |
| CompuLab      | fit-PC3                     | Mini pc     | [54a64a269c](https://bsd-hardware.info/?probe=54a64a269c) | Nov 26, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [7c9df6da87](https://bsd-hardware.info/?probe=7c9df6da87) | Nov 26, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [b87ed70877](https://bsd-hardware.info/?probe=b87ed70877) | Nov 26, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [7f9869324b](https://bsd-hardware.info/?probe=7f9869324b) | Nov 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [222e69ff59](https://bsd-hardware.info/?probe=222e69ff59) | Nov 26, 2022 |
| HP            | ProLiant DL360p Gen8        | Server      | [a5514d3f4b](https://bsd-hardware.info/?probe=a5514d3f4b) | Nov 26, 2022 |
| Sophos        | SG                          | Firewall    | [d0fc510660](https://bsd-hardware.info/?probe=d0fc510660) | Nov 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [6de307244e](https://bsd-hardware.info/?probe=6de307244e) | Nov 26, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [787a2db2cd](https://bsd-hardware.info/?probe=787a2db2cd) | Nov 26, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [88929a3594](https://bsd-hardware.info/?probe=88929a3594) | Nov 25, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [ef6190861c](https://bsd-hardware.info/?probe=ef6190861c) | Nov 25, 2022 |
| Protectli     | FW6                         | Desktop     | [74510f3177](https://bsd-hardware.info/?probe=74510f3177) | Nov 25, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [76ecd68ff6](https://bsd-hardware.info/?probe=76ecd68ff6) | Nov 25, 2022 |
| Protectli     | FW2B Ver                    | Desktop     | [e03929e52f](https://bsd-hardware.info/?probe=e03929e52f) | Nov 25, 2022 |
| Dell          | 0F0XJ6 A13                  | Server      | [1d71d3c9e7](https://bsd-hardware.info/?probe=1d71d3c9e7) | Nov 25, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [317231bad8](https://bsd-hardware.info/?probe=317231bad8) | Nov 25, 2022 |
| Supermicro    | M11SDV-4CT-LN4F             | Server      | [dc8015adc3](https://bsd-hardware.info/?probe=dc8015adc3) | Nov 25, 2022 |
| ASRock        | H510M-HDV                   | Desktop     | [d2029ae805](https://bsd-hardware.info/?probe=d2029ae805) | Nov 25, 2022 |
| Dell          | 0F0XJ6 A13                  | Server      | [1fb28aaef2](https://bsd-hardware.info/?probe=1fb28aaef2) | Nov 25, 2022 |
| Lenovo        | 1106A14 ThinkServer TS13... | Desktop     | [28aca8c985](https://bsd-hardware.info/?probe=28aca8c985) | Nov 25, 2022 |
| Gigabyte      | G31M-ES2C                   | Desktop     | [2959091a59](https://bsd-hardware.info/?probe=2959091a59) | Nov 25, 2022 |
| Dell          | 0HFG24 A01                  | Server      | [ca48ff12d3](https://bsd-hardware.info/?probe=ca48ff12d3) | Nov 25, 2022 |
| HP            | 8055                        | Desktop     | [ace4570d15](https://bsd-hardware.info/?probe=ace4570d15) | Nov 25, 2022 |
| HP            | ProLiant DL360p Gen8        | Server      | [7bb8186465](https://bsd-hardware.info/?probe=7bb8186465) | Nov 25, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [de7f2ee053](https://bsd-hardware.info/?probe=de7f2ee053) | Nov 25, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [7258992b77](https://bsd-hardware.info/?probe=7258992b77) | Nov 24, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [4a8efeb7a6](https://bsd-hardware.info/?probe=4a8efeb7a6) | Nov 24, 2022 |
| HP            | ProLiant DL360 G5           | Server      | [4a44193c5f](https://bsd-hardware.info/?probe=4a44193c5f) | Nov 24, 2022 |
| Deciso        | OPNsense Appliance          | Notebook    | [0bbf4f46e7](https://bsd-hardware.info/?probe=0bbf4f46e7) | Nov 24, 2022 |
| Dell          | 0W13NR A07                  | Server      | [c5b09b219b](https://bsd-hardware.info/?probe=c5b09b219b) | Nov 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [d4246caa0f](https://bsd-hardware.info/?probe=d4246caa0f) | Nov 24, 2022 |
| Deciso        | OPNsense Appliance          | Notebook    | [75a7bf9b27](https://bsd-hardware.info/?probe=75a7bf9b27) | Nov 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [5aa1f0193a](https://bsd-hardware.info/?probe=5aa1f0193a) | Nov 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [c5562e1851](https://bsd-hardware.info/?probe=c5562e1851) | Nov 24, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [b6bbaa13e8](https://bsd-hardware.info/?probe=b6bbaa13e8) | Nov 24, 2022 |
| Dell          | 07F37C A01                  | Desktop     | [08d048da80](https://bsd-hardware.info/?probe=08d048da80) | Nov 24, 2022 |
| ASRock Ind... | NUC-1240P                   | Desktop     | [75547bc09a](https://bsd-hardware.info/?probe=75547bc09a) | Nov 24, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [aa3c44499f](https://bsd-hardware.info/?probe=aa3c44499f) | Nov 23, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [1b6870d481](https://bsd-hardware.info/?probe=1b6870d481) | Nov 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [77e932dd9e](https://bsd-hardware.info/?probe=77e932dd9e) | Nov 23, 2022 |
| IceWhale T... | ZimaBoard 216 ZMB           | Desktop     | [b75d6c6581](https://bsd-hardware.info/?probe=b75d6c6581) | Nov 23, 2022 |
| Dell          | 06D7TR A00                  | Desktop     | [7fabc0cb8a](https://bsd-hardware.info/?probe=7fabc0cb8a) | Nov 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [337d5f0f4b](https://bsd-hardware.info/?probe=337d5f0f4b) | Nov 23, 2022 |
| ZOTAC         | ZBOX-CI622/CI642/CI662NA... | Mini pc     | [4c3be7ec24](https://bsd-hardware.info/?probe=4c3be7ec24) | Nov 23, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [1860d18e39](https://bsd-hardware.info/?probe=1860d18e39) | Nov 23, 2022 |
| Protectli     | FW4B                        | Desktop     | [d3090c9e8e](https://bsd-hardware.info/?probe=d3090c9e8e) | Nov 23, 2022 |
| Infoblox      | IB-1410                     | Desktop     | [7521108ef5](https://bsd-hardware.info/?probe=7521108ef5) | Nov 23, 2022 |
| HP            | 3396                        | Desktop     | [dc94cbde1a](https://bsd-hardware.info/?probe=dc94cbde1a) | Nov 23, 2022 |
| PC Engines    | apu6                        | Desktop     | [bc334caa03](https://bsd-hardware.info/?probe=bc334caa03) | Nov 23, 2022 |
| PC Engines    | APU2                        | Desktop     | [4d33b6da51](https://bsd-hardware.info/?probe=4d33b6da51) | Nov 23, 2022 |
| Sophos        | UTM                         | Firewall    | [1c0805f9ae](https://bsd-hardware.info/?probe=1c0805f9ae) | Nov 23, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [d4791d1dfc](https://bsd-hardware.info/?probe=d4791d1dfc) | Nov 22, 2022 |
| Dell          | 0TW855 A07                  | Server      | [d2d859c434](https://bsd-hardware.info/?probe=d2d859c434) | Nov 22, 2022 |
| Dell          | 0MD99X A05                  | Server      | [8adc53c921](https://bsd-hardware.info/?probe=8adc53c921) | Nov 22, 2022 |
| HP            | ProLiant DL360 G7           | Server      | [b666129e73](https://bsd-hardware.info/?probe=b666129e73) | Nov 22, 2022 |
| Datto         | SSD                         | Desktop     | [08d401fa34](https://bsd-hardware.info/?probe=08d401fa34) | Nov 22, 2022 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [2f812bd8c3](https://bsd-hardware.info/?probe=2f812bd8c3) | Nov 22, 2022 |
| Dell          | Edge Gateway 5000           | Mini pc     | [18f8f8f8b5](https://bsd-hardware.info/?probe=18f8f8f8b5) | Nov 22, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [7742fc7455](https://bsd-hardware.info/?probe=7742fc7455) | Nov 21, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [77fa42b66c](https://bsd-hardware.info/?probe=77fa42b66c) | Nov 21, 2022 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Mini pc     | [e0f08b66c2](https://bsd-hardware.info/?probe=e0f08b66c2) | Nov 21, 2022 |
| Supermicro    | M11SDV-4CT-LN4F             | Server      | [2d8d0056c4](https://bsd-hardware.info/?probe=2d8d0056c4) | Nov 21, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [298fde4e33](https://bsd-hardware.info/?probe=298fde4e33) | Nov 21, 2022 |
| Unknown       | SKYBAY                      | Desktop     | [5030575f0a](https://bsd-hardware.info/?probe=5030575f0a) | Nov 20, 2022 |
| HP            | ProLiant DL380 G6           | Server      | [3e3b056cdf](https://bsd-hardware.info/?probe=3e3b056cdf) | Nov 20, 2022 |
| Sophos        | XG                          | Firewall    | [3868856b34](https://bsd-hardware.info/?probe=3868856b34) | Nov 20, 2022 |
| Dell          | 07F37C A01                  | Desktop     | [efb5c9d03d](https://bsd-hardware.info/?probe=efb5c9d03d) | Nov 20, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [98684b1d19](https://bsd-hardware.info/?probe=98684b1d19) | Nov 20, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [f6491f1950](https://bsd-hardware.info/?probe=f6491f1950) | Nov 20, 2022 |
| OEM           | 1.0                         | Desktop     | [a821818533](https://bsd-hardware.info/?probe=a821818533) | Nov 20, 2022 |
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
| Supermicro    | X11SDV-4C-TP8F              | Desktop     | [402a623ed0](https://bsd-hardware.info/?probe=402a623ed0) | Nov 19, 2022 |
| Foxconn       | H67S/H61SP                  | Desktop     | [80ad331089](https://bsd-hardware.info/?probe=80ad331089) | Nov 19, 2022 |
| ZOTAC         | ZBOX-CI327NANO-GS-01        | Mini pc     | [7bfffa2718](https://bsd-hardware.info/?probe=7bfffa2718) | Nov 19, 2022 |
| Dell          | 060J9C A00                  | Mini pc     | [efcae22b58](https://bsd-hardware.info/?probe=efcae22b58) | Nov 19, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [18062e5bd5](https://bsd-hardware.info/?probe=18062e5bd5) | Nov 19, 2022 |
| Dell          | 0KYJ8C A02                  | Desktop     | [7282ce8fe2](https://bsd-hardware.info/?probe=7282ce8fe2) | Nov 19, 2022 |
| Dell          | 0GN4PW A00                  | Desktop     | [9127ec4dac](https://bsd-hardware.info/?probe=9127ec4dac) | Nov 19, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [d3cbc9d6ca](https://bsd-hardware.info/?probe=d3cbc9d6ca) | Nov 19, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [2eba32390f](https://bsd-hardware.info/?probe=2eba32390f) | Nov 19, 2022 |
| PC Engines    | apu6                        | Desktop     | [1e9acc3ae6](https://bsd-hardware.info/?probe=1e9acc3ae6) | Nov 18, 2022 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [f25480c54a](https://bsd-hardware.info/?probe=f25480c54a) | Nov 18, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [5537746c27](https://bsd-hardware.info/?probe=5537746c27) | Nov 18, 2022 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [7c7a121711](https://bsd-hardware.info/?probe=7c7a121711) | Nov 18, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [5875ecec9f](https://bsd-hardware.info/?probe=5875ecec9f) | Nov 18, 2022 |
| HP            | 82FE 11                     | Desktop     | [547e5e3ce1](https://bsd-hardware.info/?probe=547e5e3ce1) | Nov 18, 2022 |
| Fujitsu       | D3289-A1 S26361-D3289-A1... | Desktop     | [dae7027898](https://bsd-hardware.info/?probe=dae7027898) | Nov 18, 2022 |
| Dell          | 051FJ8 A02                  | Desktop     | [296b446a8f](https://bsd-hardware.info/?probe=296b446a8f) | Nov 18, 2022 |
| ASRock        | N3150M                      | Desktop     | [d3b3be7936](https://bsd-hardware.info/?probe=d3b3be7936) | Nov 17, 2022 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [f1f56fe86c](https://bsd-hardware.info/?probe=f1f56fe86c) | Nov 17, 2022 |
| Gigabyte      | H110TN                      | Desktop     | [c121bad3fb](https://bsd-hardware.info/?probe=c121bad3fb) | Nov 17, 2022 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [ddf3f8603a](https://bsd-hardware.info/?probe=ddf3f8603a) | Nov 17, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [64d8291a91](https://bsd-hardware.info/?probe=64d8291a91) | Nov 17, 2022 |
| PC Engines    | apu4                        | Desktop     | [212f27d85a](https://bsd-hardware.info/?probe=212f27d85a) | Nov 17, 2022 |
| AAEON         | MF-001 V1.0                 | Desktop     | [d98d84f1a4](https://bsd-hardware.info/?probe=d98d84f1a4) | Nov 17, 2022 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [f362b4c2ea](https://bsd-hardware.info/?probe=f362b4c2ea) | Nov 17, 2022 |
| AZW           | U59                         | Desktop     | [25e1349c5f](https://bsd-hardware.info/?probe=25e1349c5f) | Nov 17, 2022 |
| HP            | ProLiant DL380 G7           | Server      | [79c7aad234](https://bsd-hardware.info/?probe=79c7aad234) | Nov 17, 2022 |
| Supermicro    | A2SDi-4C-HLN4F              | Desktop     | [9cd1c1fc21](https://bsd-hardware.info/?probe=9cd1c1fc21) | Nov 17, 2022 |
| Dell          | 05XGC8 A00                  | Desktop     | [15458aff84](https://bsd-hardware.info/?probe=15458aff84) | Nov 16, 2022 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [47f82850da](https://bsd-hardware.info/?probe=47f82850da) | Nov 16, 2022 |
| HP            | ProLiant DL120 Gen9         | Server      | [94513a53f8](https://bsd-hardware.info/?probe=94513a53f8) | Nov 16, 2022 |
| ASRock        | J5040-ITX                   | Desktop     | [753c68cfb9](https://bsd-hardware.info/?probe=753c68cfb9) | Nov 16, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [abbd5ab7ff](https://bsd-hardware.info/?probe=abbd5ab7ff) | Nov 16, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [b7ed699f3c](https://bsd-hardware.info/?probe=b7ed699f3c) | Nov 16, 2022 |
| Dell          | 05XGC8 A00                  | Desktop     | [94afb24fbc](https://bsd-hardware.info/?probe=94afb24fbc) | Nov 16, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [2714f36aca](https://bsd-hardware.info/?probe=2714f36aca) | Nov 16, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [5096994f99](https://bsd-hardware.info/?probe=5096994f99) | Nov 16, 2022 |
| HP            | 82B4                        | Desktop     | [d4badfa185](https://bsd-hardware.info/?probe=d4badfa185) | Nov 15, 2022 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [314916c885](https://bsd-hardware.info/?probe=314916c885) | Nov 15, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [dd637e0562](https://bsd-hardware.info/?probe=dd637e0562) | Nov 15, 2022 |
| PC Engines    | apu4                        | Desktop     | [589dec199e](https://bsd-hardware.info/?probe=589dec199e) | Nov 15, 2022 |
| Acer          | TDPS05 R3700                | Desktop     | [4ebc5df17c](https://bsd-hardware.info/?probe=4ebc5df17c) | Nov 15, 2022 |
| Acer          | TDPS05 R3700                | Desktop     | [6e1273fdd6](https://bsd-hardware.info/?probe=6e1273fdd6) | Nov 15, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [3425326f3f](https://bsd-hardware.info/?probe=3425326f3f) | Nov 14, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [cecda8d045](https://bsd-hardware.info/?probe=cecda8d045) | Nov 14, 2022 |
| Shuttle       | FH61V                       | Desktop     | [012a5c0fcc](https://bsd-hardware.info/?probe=012a5c0fcc) | Nov 14, 2022 |
| Dell          | 06D7TR A00                  | Desktop     | [9e568eb5ee](https://bsd-hardware.info/?probe=9e568eb5ee) | Nov 14, 2022 |
| Unknown       | Unknown                     | Desktop     | [b9994aa302](https://bsd-hardware.info/?probe=b9994aa302) | Nov 14, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [a678226171](https://bsd-hardware.info/?probe=a678226171) | Nov 14, 2022 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [0079838512](https://bsd-hardware.info/?probe=0079838512) | Nov 13, 2022 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [86dcacdb40](https://bsd-hardware.info/?probe=86dcacdb40) | Nov 13, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [74a717c2e6](https://bsd-hardware.info/?probe=74a717c2e6) | Nov 13, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [80c0d775a7](https://bsd-hardware.info/?probe=80c0d775a7) | Nov 13, 2022 |
| HP            | 83E1                        | Desktop     | [689b01c121](https://bsd-hardware.info/?probe=689b01c121) | Nov 13, 2022 |
| Sophos        | SG                          | Firewall    | [3d17d672bd](https://bsd-hardware.info/?probe=3d17d672bd) | Nov 13, 2022 |
| Shuttle       | FS35V5                      | Mini pc     | [8b634987b4](https://bsd-hardware.info/?probe=8b634987b4) | Nov 13, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [269f915ce2](https://bsd-hardware.info/?probe=269f915ce2) | Nov 13, 2022 |
| Dell          | 04415J A00                  | Mini pc     | [5125bff15a](https://bsd-hardware.info/?probe=5125bff15a) | Nov 13, 2022 |
| HP            | 3397                        | Desktop     | [d087515b69](https://bsd-hardware.info/?probe=d087515b69) | Nov 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [838256315e](https://bsd-hardware.info/?probe=838256315e) | Nov 13, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [ee16ad1ffb](https://bsd-hardware.info/?probe=ee16ad1ffb) | Nov 12, 2022 |
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
| Lenovo        | ThinkServer RS140           | Desktop     | [0dd05e08aa](https://bsd-hardware.info/?probe=0dd05e08aa) | Nov 12, 2022 |
| Supermicro    | X10SDV-TP8F                 | Server      | [cb88c3311a](https://bsd-hardware.info/?probe=cb88c3311a) | Nov 12, 2022 |
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
| CheckPoint    | PH-30-00                    | Desktop     | [e42768cd01](https://bsd-hardware.info/?probe=e42768cd01) | Nov 10, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [c741b2fbfa](https://bsd-hardware.info/?probe=c741b2fbfa) | Nov 10, 2022 |
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
| Gigabyte      | J3455N-D3H                  | Desktop     | [f8e610e161](https://bsd-hardware.info/?probe=f8e610e161) | Nov 09, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [d75162607b](https://bsd-hardware.info/?probe=d75162607b) | Nov 09, 2022 |
| ASRock        | H570M-ITX/ac                | Desktop     | [8addd09aa7](https://bsd-hardware.info/?probe=8addd09aa7) | Nov 09, 2022 |
| Sophos        | SG                          | Firewall    | [04b1bf9b24](https://bsd-hardware.info/?probe=04b1bf9b24) | Nov 09, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [667abc6f38](https://bsd-hardware.info/?probe=667abc6f38) | Nov 09, 2022 |
| HP            | 1632                        | Desktop     | [96d60382b7](https://bsd-hardware.info/?probe=96d60382b7) | Nov 09, 2022 |
| ASUSTek       | P8H77-I                     | Desktop     | [04ea3cc97d](https://bsd-hardware.info/?probe=04ea3cc97d) | Nov 09, 2022 |
| Gigabyte      | A520M H                     | Desktop     | [a751c4e782](https://bsd-hardware.info/?probe=a751c4e782) | Nov 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [47e6a4fa8b](https://bsd-hardware.info/?probe=47e6a4fa8b) | Nov 09, 2022 |
| Deciso        | NetBoard-A10                | Notebook    | [1fc6403341](https://bsd-hardware.info/?probe=1fc6403341) | Nov 08, 2022 |
| Thomas-Kre... | P9A-I/2550/4L               | Firewall    | [d63fd6f7bd](https://bsd-hardware.info/?probe=d63fd6f7bd) | Nov 08, 2022 |
| Dell          | 0G261D A00                  | Desktop     | [c3eb1a6caf](https://bsd-hardware.info/?probe=c3eb1a6caf) | Nov 08, 2022 |
| Intel         | JSL MRD                     | Desktop     | [5800246e28](https://bsd-hardware.info/?probe=5800246e28) | Nov 08, 2022 |
| ASUSTek       | EX-H110M-V                  | Desktop     | [f9832b4966](https://bsd-hardware.info/?probe=f9832b4966) | Nov 08, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [a84d0a0380](https://bsd-hardware.info/?probe=a84d0a0380) | Nov 08, 2022 |
| Dell          | 0W3F1J A00                  | Mini pc     | [5c70ba3a0d](https://bsd-hardware.info/?probe=5c70ba3a0d) | Nov 08, 2022 |
| Supermicro    | X8DT6                       | Server      | [e7536e4a4c](https://bsd-hardware.info/?probe=e7536e4a4c) | Nov 07, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [970443066b](https://bsd-hardware.info/?probe=970443066b) | Nov 07, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [da16bac6f5](https://bsd-hardware.info/?probe=da16bac6f5) | Nov 07, 2022 |
| HP            | ProLiant ML310e Gen8        | Desktop     | [cb5bb2c3b5](https://bsd-hardware.info/?probe=cb5bb2c3b5) | Nov 07, 2022 |
| Dell          | 081N4V A08                  | Server      | [6454631448](https://bsd-hardware.info/?probe=6454631448) | Nov 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [31ff384824](https://bsd-hardware.info/?probe=31ff384824) | Nov 07, 2022 |
| HP            | 8768 A                      | Desktop     | [c8a44e84c6](https://bsd-hardware.info/?probe=c8a44e84c6) | Nov 07, 2022 |
| Sophos        | SG                          | Firewall    | [4547062398](https://bsd-hardware.info/?probe=4547062398) | Nov 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [659ec0b365](https://bsd-hardware.info/?probe=659ec0b365) | Nov 07, 2022 |
| PC Engines    | APU2                        | Desktop     | [2a913e7a43](https://bsd-hardware.info/?probe=2a913e7a43) | Nov 06, 2022 |
| PC Engines    | APU2                        | Desktop     | [4fda77e4ca](https://bsd-hardware.info/?probe=4fda77e4ca) | Nov 06, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [70e257e360](https://bsd-hardware.info/?probe=70e257e360) | Nov 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [fed7f55a01](https://bsd-hardware.info/?probe=fed7f55a01) | Nov 06, 2022 |
| HP            | 18E7                        | Desktop     | [6a80fc5241](https://bsd-hardware.info/?probe=6a80fc5241) | Nov 06, 2022 |
| Protectli     | VP2410                      | Desktop     | [de5de1ca21](https://bsd-hardware.info/?probe=de5de1ca21) | Nov 06, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [59b8857bba](https://bsd-hardware.info/?probe=59b8857bba) | Nov 06, 2022 |
| Cisco Syst... | UCSC-C240-M5SX 74-105773... | Server      | [2633eaf68b](https://bsd-hardware.info/?probe=2633eaf68b) | Nov 06, 2022 |
| Protectli     | FW6                         | Desktop     | [654e223853](https://bsd-hardware.info/?probe=654e223853) | Nov 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [a33d1a4123](https://bsd-hardware.info/?probe=a33d1a4123) | Nov 06, 2022 |
| Supermicro    | X7SPA-HF                    | Desktop     | [66819692d5](https://bsd-hardware.info/?probe=66819692d5) | Nov 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [6fb650e2e8](https://bsd-hardware.info/?probe=6fb650e2e8) | Nov 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [47efa8b4bc](https://bsd-hardware.info/?probe=47efa8b4bc) | Nov 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [3771535d50](https://bsd-hardware.info/?probe=3771535d50) | Nov 06, 2022 |
| Dell          | OptiPlex 5050               | Desktop     | [cfd442a25d](https://bsd-hardware.info/?probe=cfd442a25d) | Nov 06, 2022 |
| Datto         | SSD                         | Desktop     | [235483110d](https://bsd-hardware.info/?probe=235483110d) | Nov 05, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [33eea3a422](https://bsd-hardware.info/?probe=33eea3a422) | Nov 05, 2022 |
| Sophos        | SG                          | Firewall    | [d80c273f85](https://bsd-hardware.info/?probe=d80c273f85) | Nov 05, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [80a31985d9](https://bsd-hardware.info/?probe=80a31985d9) | Nov 05, 2022 |
| Intel         | CRESCENTBAY                 | Desktop     | [0312c464c4](https://bsd-hardware.info/?probe=0312c464c4) | Nov 05, 2022 |
| Protectli     | FW4C Ver                    | Desktop     | [71c0c846f1](https://bsd-hardware.info/?probe=71c0c846f1) | Nov 05, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [3fa9f3aa5c](https://bsd-hardware.info/?probe=3fa9f3aa5c) | Nov 05, 2022 |
| Dell          | 05GD68 A00                  | Desktop     | [946c93ec7b](https://bsd-hardware.info/?probe=946c93ec7b) | Nov 05, 2022 |
| Dell          | 0CN7CM A06                  | Server      | [6efd22e598](https://bsd-hardware.info/?probe=6efd22e598) | Nov 04, 2022 |
| HP            | 213D A01                    | Desktop     | [f579ee6387](https://bsd-hardware.info/?probe=f579ee6387) | Nov 04, 2022 |
| Dell          | 0G7WYD A01                  | Server      | [655a9e7af2](https://bsd-hardware.info/?probe=655a9e7af2) | Nov 04, 2022 |
| ASRock        | H670M-ITX/ax                | Desktop     | [378889e1cd](https://bsd-hardware.info/?probe=378889e1cd) | Nov 04, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [73230496b2](https://bsd-hardware.info/?probe=73230496b2) | Nov 04, 2022 |
| Dell          | 0KM5PX A01                  | Server      | [a1a15662d0](https://bsd-hardware.info/?probe=a1a15662d0) | Nov 04, 2022 |
| Dell          | 0KM5PX A01                  | Server      | [0ee82f0b87](https://bsd-hardware.info/?probe=0ee82f0b87) | Nov 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [4f58f89a6e](https://bsd-hardware.info/?probe=4f58f89a6e) | Nov 04, 2022 |
| Fujitsu       | D3049-A1 S26361-D3049-A1... | Server      | [1b27159e27](https://bsd-hardware.info/?probe=1b27159e27) | Nov 04, 2022 |
| HP            | 82A2                        | Desktop     | [d83974a5ed](https://bsd-hardware.info/?probe=d83974a5ed) | Nov 03, 2022 |
| HP            | 339A                        | Desktop     | [a1e829d9d9](https://bsd-hardware.info/?probe=a1e829d9d9) | Nov 03, 2022 |
| Unknown       | 1.0                         | Desktop     | [9fe6ac4e68](https://bsd-hardware.info/?probe=9fe6ac4e68) | Nov 03, 2022 |
| Deciso        | NetBoard-A20                | Notebook    | [9c133326c9](https://bsd-hardware.info/?probe=9c133326c9) | Nov 03, 2022 |
| PC Engines    | apu4                        | Desktop     | [7ed7638be3](https://bsd-hardware.info/?probe=7ed7638be3) | Nov 03, 2022 |
| AMD           | Inagua CRB                  | Desktop     | [5d27c08853](https://bsd-hardware.info/?probe=5d27c08853) | Nov 03, 2022 |
| Sophos        | XG                          | Firewall    | [f2f91c4258](https://bsd-hardware.info/?probe=f2f91c4258) | Nov 03, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [3021b8ee09](https://bsd-hardware.info/?probe=3021b8ee09) | Nov 03, 2022 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [7729ec0863](https://bsd-hardware.info/?probe=7729ec0863) | Nov 03, 2022 |
| ASUSTek       | H110M-CS/BR                 | Desktop     | [0841d714d0](https://bsd-hardware.info/?probe=0841d714d0) | Nov 03, 2022 |
| Dell          | 05GD68 A00                  | Desktop     | [8e0c8344af](https://bsd-hardware.info/?probe=8e0c8344af) | Nov 03, 2022 |
| HP            | 843F                        | Desktop     | [f921634ea0](https://bsd-hardware.info/?probe=f921634ea0) | Nov 02, 2022 |
| HP            | 339A                        | Desktop     | [370d93ecde](https://bsd-hardware.info/?probe=370d93ecde) | Nov 02, 2022 |
| Dell          | 0VWT90 A10                  | Server      | [b74220aee1](https://bsd-hardware.info/?probe=b74220aee1) | Nov 02, 2022 |
| Lenovo        | 00FN849 E63448-400          | Server      | [0794efc014](https://bsd-hardware.info/?probe=0794efc014) | Nov 02, 2022 |
| Hardkernel    | ODROID-H2                   | Desktop     | [f0e3f3177a](https://bsd-hardware.info/?probe=f0e3f3177a) | Nov 02, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [b6044fb84c](https://bsd-hardware.info/?probe=b6044fb84c) | Nov 02, 2022 |
| Dell          | 0W3F1J A00                  | Mini pc     | [7c95a69cc9](https://bsd-hardware.info/?probe=7c95a69cc9) | Nov 02, 2022 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | Notebook    | [7708c4bb19](https://bsd-hardware.info/?probe=7708c4bb19) | Nov 02, 2022 |
| HP            | 843F                        | Desktop     | [bba76c5ce6](https://bsd-hardware.info/?probe=bba76c5ce6) | Nov 02, 2022 |
| Unknown       | Unknown                     | Desktop     | [bc7a300434](https://bsd-hardware.info/?probe=bc7a300434) | Nov 02, 2022 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | Notebook    | [22d3fc953a](https://bsd-hardware.info/?probe=22d3fc953a) | Nov 01, 2022 |
| MSI           | B560M-A PRO                 | Desktop     | [ac1e500e91](https://bsd-hardware.info/?probe=ac1e500e91) | Nov 01, 2022 |
| ASRock        | H670M-ITX/ax                | Desktop     | [bb78d5d8ea](https://bsd-hardware.info/?probe=bb78d5d8ea) | Nov 01, 2022 |
| Cisco         | ASA5512 A0                  | Desktop     | [871a5c449f](https://bsd-hardware.info/?probe=871a5c449f) | Nov 01, 2022 |
| Dell          | 09T7VV A02                  | Server      | [6e89de5b97](https://bsd-hardware.info/?probe=6e89de5b97) | Nov 01, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [8b2537708c](https://bsd-hardware.info/?probe=8b2537708c) | Nov 01, 2022 |
| Sophos        | SG                          | Firewall    | [ef9269be7e](https://bsd-hardware.info/?probe=ef9269be7e) | Nov 01, 2022 |
| ASRock        | H110 Pro BTC+               | Desktop     | [fb24f0fa6e](https://bsd-hardware.info/?probe=fb24f0fa6e) | Nov 01, 2022 |
| Sophos        | XG                          | Firewall    | [a245d23614](https://bsd-hardware.info/?probe=a245d23614) | Nov 01, 2022 |
| ASUSTek       | K30AM-J_A_F_K31AM-J         | Desktop     | [f587ec97a4](https://bsd-hardware.info/?probe=f587ec97a4) | Nov 01, 2022 |
| Dell          | 05GD68 A00                  | Desktop     | [23483285a8](https://bsd-hardware.info/?probe=23483285a8) | Nov 01, 2022 |
| Cisco         | ASA5512 A0                  | Desktop     | [5758027775](https://bsd-hardware.info/?probe=5758027775) | Oct 31, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [6afa103d09](https://bsd-hardware.info/?probe=6afa103d09) | Oct 31, 2022 |
| Supermicro    | X10SDV-TP8F                 | Server      | [09cb46f6bf](https://bsd-hardware.info/?probe=09cb46f6bf) | Oct 31, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [6f21c02bba](https://bsd-hardware.info/?probe=6f21c02bba) | Oct 31, 2022 |
| Supermicro    | X10DRU-i+                   | Desktop     | [1ffd63a929](https://bsd-hardware.info/?probe=1ffd63a929) | Oct 31, 2022 |
| maiyunda      | www.maiyunda.com            | Desktop     | [4dfd35f622](https://bsd-hardware.info/?probe=4dfd35f622) | Oct 31, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [d2d5364c96](https://bsd-hardware.info/?probe=d2d5364c96) | Oct 31, 2022 |
| Unknown       | Unknown                     | Desktop     | [9737a80a1c](https://bsd-hardware.info/?probe=9737a80a1c) | Oct 31, 2022 |
| Unknown       | Unknown                     | Desktop     | [c14a3eb06b](https://bsd-hardware.info/?probe=c14a3eb06b) | Oct 31, 2022 |
| Supermicro    | X7SPA-HF                    | Desktop     | [18b3b416ce](https://bsd-hardware.info/?probe=18b3b416ce) | Oct 31, 2022 |
| ASRock        | H110 Pro BTC+               | Desktop     | [20f2ab4251](https://bsd-hardware.info/?probe=20f2ab4251) | Oct 30, 2022 |
| Sophos        | SG                          | Firewall    | [cab7a59023](https://bsd-hardware.info/?probe=cab7a59023) | Oct 30, 2022 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [0f22defdb3](https://bsd-hardware.info/?probe=0f22defdb3) | Oct 30, 2022 |
| Cisco Syst... | UCSC-C240-M5SX 74-105773... | Server      | [5a7e972a9e](https://bsd-hardware.info/?probe=5a7e972a9e) | Oct 30, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [a52d7dda08](https://bsd-hardware.info/?probe=a52d7dda08) | Oct 30, 2022 |
| Cisco Syst... | UCSC-C240-M5SX 74-105773... | Server      | [da2336a58a](https://bsd-hardware.info/?probe=da2336a58a) | Oct 30, 2022 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [af6807035f](https://bsd-hardware.info/?probe=af6807035f) | Oct 30, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [4aecc55dcc](https://bsd-hardware.info/?probe=4aecc55dcc) | Oct 30, 2022 |
| Thomas-Kre... | LES network 6L              | Desktop     | [0816f2da97](https://bsd-hardware.info/?probe=0816f2da97) | Oct 30, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [1eaa616342](https://bsd-hardware.info/?probe=1eaa616342) | Oct 30, 2022 |
| Unknown       | J3160-4L                    | Desktop     | [e05d9b2d17](https://bsd-hardware.info/?probe=e05d9b2d17) | Oct 30, 2022 |
| maiyunda      | www.maiyunda.com            | Desktop     | [ed59c93b79](https://bsd-hardware.info/?probe=ed59c93b79) | Oct 29, 2022 |
| Sophos        | SG                          | Firewall    | [03633cdc2e](https://bsd-hardware.info/?probe=03633cdc2e) | Oct 29, 2022 |
| ASRock        | N68-GS4 FX R2.0             | Desktop     | [85be4177d6](https://bsd-hardware.info/?probe=85be4177d6) | Oct 29, 2022 |
| Sophos        | SG                          | Firewall    | [01f57abe1b](https://bsd-hardware.info/?probe=01f57abe1b) | Oct 29, 2022 |
| Dell          | 03X6X0 A00                  | Server      | [f8652952a4](https://bsd-hardware.info/?probe=f8652952a4) | Oct 29, 2022 |
| ASRock        | H570M-ITX/ac                | Desktop     | [06a8abdbf4](https://bsd-hardware.info/?probe=06a8abdbf4) | Oct 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [acf41f7000](https://bsd-hardware.info/?probe=acf41f7000) | Oct 29, 2022 |
| AWOW          | AK34Pro                     | Mini pc     | [70cc64ba78](https://bsd-hardware.info/?probe=70cc64ba78) | Oct 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [b8323aa325](https://bsd-hardware.info/?probe=b8323aa325) | Oct 29, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [02d617a604](https://bsd-hardware.info/?probe=02d617a604) | Oct 29, 2022 |
| Dell          | 0XCR8D A01                  | Desktop     | [a019244c85](https://bsd-hardware.info/?probe=a019244c85) | Oct 29, 2022 |
| Acer          | JM11-MS                     | Notebook    | [3ff8b20107](https://bsd-hardware.info/?probe=3ff8b20107) | Oct 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [3744629487](https://bsd-hardware.info/?probe=3744629487) | Oct 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [9a12cd02f0](https://bsd-hardware.info/?probe=9a12cd02f0) | Oct 28, 2022 |
| Unknown       | Unknown                     | Notebook    | [2df5c5b434](https://bsd-hardware.info/?probe=2df5c5b434) | Oct 28, 2022 |
| YANYU         | R250                        | Desktop     | [f39d55e42d](https://bsd-hardware.info/?probe=f39d55e42d) | Oct 28, 2022 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Mini pc     | [484e5520b7](https://bsd-hardware.info/?probe=484e5520b7) | Oct 28, 2022 |
| Centerm       | GA690-2 2                   | Desktop     | [9d6c3d67cd](https://bsd-hardware.info/?probe=9d6c3d67cd) | Oct 28, 2022 |
| MSI           | B360I GMAING PRO AC         | Desktop     | [7287c670f0](https://bsd-hardware.info/?probe=7287c670f0) | Oct 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [c483de83a9](https://bsd-hardware.info/?probe=c483de83a9) | Oct 28, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [6dda683e10](https://bsd-hardware.info/?probe=6dda683e10) | Oct 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [c03e63a0a8](https://bsd-hardware.info/?probe=c03e63a0a8) | Oct 28, 2022 |
| ASUSTek       | P5BV-M                      | Desktop     | [c5277ae3cd](https://bsd-hardware.info/?probe=c5277ae3cd) | Oct 27, 2022 |
| Unknown       | YL-J3160L4                  | Desktop     | [fa8d5e324b](https://bsd-hardware.info/?probe=fa8d5e324b) | Oct 27, 2022 |
| PC Engines    | APU2                        | Desktop     | [0c573848ce](https://bsd-hardware.info/?probe=0c573848ce) | Oct 27, 2022 |
| ASRock        | B550M Phantom Gaming 4      | Desktop     | [16c226553c](https://bsd-hardware.info/?probe=16c226553c) | Oct 27, 2022 |
| Unknown       | Unknown                     | Desktop     | [4e01e68bb2](https://bsd-hardware.info/?probe=4e01e68bb2) | Oct 27, 2022 |
| Unknown       | Unknown                     | Desktop     | [9de7465e6e](https://bsd-hardware.info/?probe=9de7465e6e) | Oct 27, 2022 |
| Dell          | 0CNCJW A08                  | Server      | [38a54bc15c](https://bsd-hardware.info/?probe=38a54bc15c) | Oct 27, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [f89024b7be](https://bsd-hardware.info/?probe=f89024b7be) | Oct 27, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [766ee6f4eb](https://bsd-hardware.info/?probe=766ee6f4eb) | Oct 27, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [14f174bd7c](https://bsd-hardware.info/?probe=14f174bd7c) | Oct 26, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [d2adcc8230](https://bsd-hardware.info/?probe=d2adcc8230) | Oct 26, 2022 |
| HP            | 8103 A01                    | Mini pc     | [9017d1ac90](https://bsd-hardware.info/?probe=9017d1ac90) | Oct 26, 2022 |
| HP            | 82B4                        | Desktop     | [f3b7970068](https://bsd-hardware.info/?probe=f3b7970068) | Oct 26, 2022 |
| Deciso        | NetBoard-A10                | Notebook    | [5d4c95dcac](https://bsd-hardware.info/?probe=5d4c95dcac) | Oct 26, 2022 |
| Dell          | 0HD5W2 A00                  | Desktop     | [7b330abf44](https://bsd-hardware.info/?probe=7b330abf44) | Oct 26, 2022 |
| Dell          | 0CNCJW A08                  | Server      | [a514dcc456](https://bsd-hardware.info/?probe=a514dcc456) | Oct 26, 2022 |
| Dell          | 081N4V A05                  | Server      | [913791b3cc](https://bsd-hardware.info/?probe=913791b3cc) | Oct 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [a6d41c71fd](https://bsd-hardware.info/?probe=a6d41c71fd) | Oct 26, 2022 |
| Supermicro    | A2SDi-4C-HLN4F              | Desktop     | [f6df7bf1e8](https://bsd-hardware.info/?probe=f6df7bf1e8) | Oct 26, 2022 |
| Dell          | 0HD5W2 A00                  | Desktop     | [84502a19a0](https://bsd-hardware.info/?probe=84502a19a0) | Oct 26, 2022 |
| PC Engines    | APU2                        | Desktop     | [0677b5c196](https://bsd-hardware.info/?probe=0677b5c196) | Oct 25, 2022 |
| Supermicro    | X11SSH-F                    | Server      | [66c10b64cb](https://bsd-hardware.info/?probe=66c10b64cb) | Oct 25, 2022 |
| Dell          | 05XGC8 A01                  | Desktop     | [97947568ee](https://bsd-hardware.info/?probe=97947568ee) | Oct 25, 2022 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [69a9ae7bde](https://bsd-hardware.info/?probe=69a9ae7bde) | Oct 25, 2022 |
| PC Engines    | apu1                        | Desktop     | [b8643f364d](https://bsd-hardware.info/?probe=b8643f364d) | Oct 25, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [0e2cd201d0](https://bsd-hardware.info/?probe=0e2cd201d0) | Oct 24, 2022 |
| Acer          | Veriton X2610G              | Desktop     | [e4289c3f15](https://bsd-hardware.info/?probe=e4289c3f15) | Oct 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [1f2cd1f9ea](https://bsd-hardware.info/?probe=1f2cd1f9ea) | Oct 24, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [079830f938](https://bsd-hardware.info/?probe=079830f938) | Oct 24, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [2fa4641b0e](https://bsd-hardware.info/?probe=2fa4641b0e) | Oct 24, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [09e5063724](https://bsd-hardware.info/?probe=09e5063724) | Oct 24, 2022 |
| ZOTAC         | ZBOX-MI522NANO/MI542NANO    | Mini pc     | [0d6e868d9c](https://bsd-hardware.info/?probe=0d6e868d9c) | Oct 24, 2022 |
| Intel         | H81U                        | Notebook    | [b0e1f80338](https://bsd-hardware.info/?probe=b0e1f80338) | Oct 24, 2022 |
| Cisco         | ASA5515 A0                  | Desktop     | [3f20d7f9bb](https://bsd-hardware.info/?probe=3f20d7f9bb) | Oct 24, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [eea9a0bef3](https://bsd-hardware.info/?probe=eea9a0bef3) | Oct 24, 2022 |
| Intel         | DQ77MK AAG39642-500         | Desktop     | [0708c0f089](https://bsd-hardware.info/?probe=0708c0f089) | Oct 24, 2022 |
| Intel         | D34010WYK H14771-305        | Desktop     | [5414062624](https://bsd-hardware.info/?probe=5414062624) | Oct 24, 2022 |
| Unknown       | YL-J3160L4                  | Desktop     | [746694bb1d](https://bsd-hardware.info/?probe=746694bb1d) | Oct 24, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [607fcd2571](https://bsd-hardware.info/?probe=607fcd2571) | Oct 24, 2022 |
| Sophos        | SG                          | Firewall    | [bb50acf083](https://bsd-hardware.info/?probe=bb50acf083) | Oct 24, 2022 |
| HP            | ProLiant DL360 G5           | Server      | [8a90c37da4](https://bsd-hardware.info/?probe=8a90c37da4) | Oct 23, 2022 |
| ASUSTek       | P5BV-M                      | Desktop     | [f7bfa3deed](https://bsd-hardware.info/?probe=f7bfa3deed) | Oct 23, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [6f0d5a7497](https://bsd-hardware.info/?probe=6f0d5a7497) | Oct 23, 2022 |
| Dell          | Latitude 5591               | Notebook    | [58b577382a](https://bsd-hardware.info/?probe=58b577382a) | Oct 23, 2022 |
| Gigabyte      | H61M-DS2 x.x                | Desktop     | [10ea57e48f](https://bsd-hardware.info/?probe=10ea57e48f) | Oct 23, 2022 |
| Unknown       | 1.21                        | Desktop     | [f8a845fcda](https://bsd-hardware.info/?probe=f8a845fcda) | Oct 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [89d0639a68](https://bsd-hardware.info/?probe=89d0639a68) | Oct 23, 2022 |
| Lenovo        | ThinkServer RS140           | Server      | [d6111b8ff1](https://bsd-hardware.info/?probe=d6111b8ff1) | Oct 23, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [d7829c8f35](https://bsd-hardware.info/?probe=d7829c8f35) | Oct 22, 2022 |
| Cisco         | ASA5515 A0                  | Desktop     | [7f848d7c57](https://bsd-hardware.info/?probe=7f848d7c57) | Oct 22, 2022 |
| Dell          | 01W23F A02                  | Server      | [8e2465430e](https://bsd-hardware.info/?probe=8e2465430e) | Oct 22, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [af3a73431f](https://bsd-hardware.info/?probe=af3a73431f) | Oct 22, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [a1b0ef3b39](https://bsd-hardware.info/?probe=a1b0ef3b39) | Oct 22, 2022 |
| HP            | 8719                        | Desktop     | [6bca1a0466](https://bsd-hardware.info/?probe=6bca1a0466) | Oct 22, 2022 |
| HP            | 8103 A01                    | Mini pc     | [d7df2919b1](https://bsd-hardware.info/?probe=d7df2919b1) | Oct 22, 2022 |
| HP            | 8103 A01                    | Mini pc     | [ff724ee8a1](https://bsd-hardware.info/?probe=ff724ee8a1) | Oct 22, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [172b2c53fe](https://bsd-hardware.info/?probe=172b2c53fe) | Oct 22, 2022 |
| Gigabyte      | H61M-DS2 x.x                | Desktop     | [947d061849](https://bsd-hardware.info/?probe=947d061849) | Oct 22, 2022 |
| Sophos        | UTM                         | Firewall    | [bae9180e3f](https://bsd-hardware.info/?probe=bae9180e3f) | Oct 22, 2022 |
| ASRock        | B250M-HDV                   | Desktop     | [803b44339b](https://bsd-hardware.info/?probe=803b44339b) | Oct 22, 2022 |
| Supermicro    | X9DRD-iF                    | Server      | [d21c2d1a10](https://bsd-hardware.info/?probe=d21c2d1a10) | Oct 22, 2022 |
| Intel         | D2500CC AAG81477-401        | Desktop     | [f27ff1a7c3](https://bsd-hardware.info/?probe=f27ff1a7c3) | Oct 22, 2022 |
| Supermicro    | X9DRD-iF                    | Server      | [c708a7828f](https://bsd-hardware.info/?probe=c708a7828f) | Oct 22, 2022 |
| Dell          | 0M877N A00                  | Server      | [dd965c2bfc](https://bsd-hardware.info/?probe=dd965c2bfc) | Oct 22, 2022 |
| Dell          | 0KM5PX A04                  | Server      | [9c2ca983ac](https://bsd-hardware.info/?probe=9c2ca983ac) | Oct 22, 2022 |
| MSI           | 890GXM-G65                  | Desktop     | [03c116d78f](https://bsd-hardware.info/?probe=03c116d78f) | Oct 22, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [623594855a](https://bsd-hardware.info/?probe=623594855a) | Oct 22, 2022 |
| Alienware     | 0PGRP5 A01                  | Desktop     | [e34219da0f](https://bsd-hardware.info/?probe=e34219da0f) | Oct 22, 2022 |
| Gigabyte      | 945PLM-S2                   | Desktop     | [ca0d187a0b](https://bsd-hardware.info/?probe=ca0d187a0b) | Oct 22, 2022 |
| Gigabyte      | 945PLM-S2                   | Desktop     | [5b8c853c20](https://bsd-hardware.info/?probe=5b8c853c20) | Oct 22, 2022 |
| PC Engines    | APU2                        | Desktop     | [f9ca8e5fdd](https://bsd-hardware.info/?probe=f9ca8e5fdd) | Oct 21, 2022 |
| Intel         | H67SL_VER1.2A               | Desktop     | [a469ad62a4](https://bsd-hardware.info/?probe=a469ad62a4) | Oct 21, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [0cd674332b](https://bsd-hardware.info/?probe=0cd674332b) | Oct 21, 2022 |
| Dell          | 0CN7CM A06                  | Server      | [764a816130](https://bsd-hardware.info/?probe=764a816130) | Oct 21, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [3b11114e36](https://bsd-hardware.info/?probe=3b11114e36) | Oct 21, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [d04ef8c45b](https://bsd-hardware.info/?probe=d04ef8c45b) | Oct 21, 2022 |
| Sophos        | UTM                         | Firewall    | [6a4c00a973](https://bsd-hardware.info/?probe=6a4c00a973) | Oct 21, 2022 |
| Dell          | 0FDY5C A00                  | Desktop     | [a47e59ad6b](https://bsd-hardware.info/?probe=a47e59ad6b) | Oct 21, 2022 |
| Dell          | 0FDY5C A00                  | Desktop     | [eb9ffe08e7](https://bsd-hardware.info/?probe=eb9ffe08e7) | Oct 21, 2022 |
| Protectli     | FW6                         | Desktop     | [528ef94fb5](https://bsd-hardware.info/?probe=528ef94fb5) | Oct 21, 2022 |
| Hardkernel    | ODROID-H3                   | Desktop     | [304db9bbbf](https://bsd-hardware.info/?probe=304db9bbbf) | Oct 20, 2022 |
| Dell          | 0CN7CM A06                  | Server      | [09bca1b1ff](https://bsd-hardware.info/?probe=09bca1b1ff) | Oct 20, 2022 |
| ASRock        | B460M-ITX/ac                | Desktop     | [c1a691f99c](https://bsd-hardware.info/?probe=c1a691f99c) | Oct 20, 2022 |
| Sophos        | SG                          | Firewall    | [a8593e1424](https://bsd-hardware.info/?probe=a8593e1424) | Oct 20, 2022 |
| Dell          | 04415J A00                  | Mini pc     | [bef50b27cb](https://bsd-hardware.info/?probe=bef50b27cb) | Oct 20, 2022 |
| PC Engines    | APU2                        | Desktop     | [c2e7b76bdf](https://bsd-hardware.info/?probe=c2e7b76bdf) | Oct 20, 2022 |
| PC Engines    | APU2                        | Desktop     | [ade8432e80](https://bsd-hardware.info/?probe=ade8432e80) | Oct 20, 2022 |
| Unknown       | Unknown                     | Desktop     | [1778396ba9](https://bsd-hardware.info/?probe=1778396ba9) | Oct 20, 2022 |
| Dell          | 012KND A00                  | Mini pc     | [c59e578a6f](https://bsd-hardware.info/?probe=c59e578a6f) | Oct 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [1188b56e14](https://bsd-hardware.info/?probe=1188b56e14) | Oct 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [915c66f8bd](https://bsd-hardware.info/?probe=915c66f8bd) | Oct 19, 2022 |
| Protectli     | FW6                         | Desktop     | [a7dabc97b0](https://bsd-hardware.info/?probe=a7dabc97b0) | Oct 19, 2022 |
| Quanmax       | spo-book TECH QUAD B1       | Desktop     | [f3db09e0f0](https://bsd-hardware.info/?probe=f3db09e0f0) | Oct 19, 2022 |
| Supermicro    | X10SLL-F                    | Server      | [ef14460db8](https://bsd-hardware.info/?probe=ef14460db8) | Oct 19, 2022 |
| Supermicro    | X11SSL-F                    | Desktop     | [24faa4663c](https://bsd-hardware.info/?probe=24faa4663c) | Oct 19, 2022 |
| Protectli     | FW4B                        | Desktop     | [0acd6e1143](https://bsd-hardware.info/?probe=0acd6e1143) | Oct 19, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [fa1f806269](https://bsd-hardware.info/?probe=fa1f806269) | Oct 19, 2022 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [a6c8096599](https://bsd-hardware.info/?probe=a6c8096599) | Oct 19, 2022 |
| Supermicro    | X10SDV-TP8F                 | Server      | [8c6555d6be](https://bsd-hardware.info/?probe=8c6555d6be) | Oct 18, 2022 |
| ASUSTek       | E35M1-I DELUXE              | Desktop     | [2fdf1c6db6](https://bsd-hardware.info/?probe=2fdf1c6db6) | Oct 18, 2022 |
| Lenovo        | 3188 SDK0J40697 WIN 3305... | Desktop     | [f84b205626](https://bsd-hardware.info/?probe=f84b205626) | Oct 18, 2022 |
| Iomega        | StorCenter Pro px2 SA       | Desktop     | [d4e8f25586](https://bsd-hardware.info/?probe=d4e8f25586) | Oct 18, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [c75bcb519e](https://bsd-hardware.info/?probe=c75bcb519e) | Oct 18, 2022 |
| Intel         | NUC9i7QNB K49245-500        | Mini pc     | [154dad5874](https://bsd-hardware.info/?probe=154dad5874) | Oct 18, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [c7971db0b8](https://bsd-hardware.info/?probe=c7971db0b8) | Oct 18, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [45d6590312](https://bsd-hardware.info/?probe=45d6590312) | Oct 18, 2022 |
| Dell          | 02K9CR A02                  | Desktop     | [a5cda6c49e](https://bsd-hardware.info/?probe=a5cda6c49e) | Oct 18, 2022 |
| Supermicro    | X10SLH-N6-ST031             | Desktop     | [2e4cd910d7](https://bsd-hardware.info/?probe=2e4cd910d7) | Oct 17, 2022 |
| Dell          | 0CNCJW A10                  | Server      | [1bc8c02062](https://bsd-hardware.info/?probe=1bc8c02062) | Oct 17, 2022 |
| Dell          | 0CNCJW A10                  | Server      | [25666c6950](https://bsd-hardware.info/?probe=25666c6950) | Oct 17, 2022 |
| Dell          | 03X6X0 A00                  | Server      | [7024873a21](https://bsd-hardware.info/?probe=7024873a21) | Oct 17, 2022 |
| PC Engines    | apu4                        | Desktop     | [20cfd8a3c8](https://bsd-hardware.info/?probe=20cfd8a3c8) | Oct 17, 2022 |
| NF541         | 1.0                         | Desktop     | [6f4f72398d](https://bsd-hardware.info/?probe=6f4f72398d) | Oct 17, 2022 |
| Pegatron      | 2ACF                        | Desktop     | [c57cc3a923](https://bsd-hardware.info/?probe=c57cc3a923) | Oct 17, 2022 |
| BESSTAR Te... | GB7B                        | Mini pc     | [75ee70a8cd](https://bsd-hardware.info/?probe=75ee70a8cd) | Oct 17, 2022 |
| Intel         | DH57DD AAE82022-202         | Desktop     | [01622a2528](https://bsd-hardware.info/?probe=01622a2528) | Oct 17, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [242e320350](https://bsd-hardware.info/?probe=242e320350) | Oct 17, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [2885a5ce85](https://bsd-hardware.info/?probe=2885a5ce85) | Oct 17, 2022 |
| Yanling       | YL-KBR6L Ver:1.00           | Desktop     | [c3f0ae254e](https://bsd-hardware.info/?probe=c3f0ae254e) | Oct 17, 2022 |
| HP            | 1588h                       | Desktop     | [e78a0308c7](https://bsd-hardware.info/?probe=e78a0308c7) | Oct 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [4fd307fbb4](https://bsd-hardware.info/?probe=4fd307fbb4) | Oct 16, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [f7d0616889](https://bsd-hardware.info/?probe=f7d0616889) | Oct 16, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [0c91327549](https://bsd-hardware.info/?probe=0c91327549) | Oct 16, 2022 |
| HP            | 8719                        | Desktop     | [87efb126fc](https://bsd-hardware.info/?probe=87efb126fc) | Oct 16, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [e7fe2f3a54](https://bsd-hardware.info/?probe=e7fe2f3a54) | Oct 16, 2022 |
| Dell          | 0200DY A02                  | Desktop     | [d32449b8c4](https://bsd-hardware.info/?probe=d32449b8c4) | Oct 16, 2022 |
| Dell          | 0HD5W2 A00                  | Desktop     | [f80953ee2f](https://bsd-hardware.info/?probe=f80953ee2f) | Oct 16, 2022 |
| Dell          | 0HD5W2 A00                  | Desktop     | [f27ffa7217](https://bsd-hardware.info/?probe=f27ffa7217) | Oct 16, 2022 |
| Yanling       | YL-KBR6L Ver:1.00           | Desktop     | [b4e02e3f51](https://bsd-hardware.info/?probe=b4e02e3f51) | Oct 16, 2022 |
| Hardkernel    | ODROID-H2                   | Desktop     | [77d3019212](https://bsd-hardware.info/?probe=77d3019212) | Oct 16, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [baf0edf73a](https://bsd-hardware.info/?probe=baf0edf73a) | Oct 16, 2022 |
| Protectli     | FW4B                        | Desktop     | [57ae1d8cda](https://bsd-hardware.info/?probe=57ae1d8cda) | Oct 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [83ceb2fb33](https://bsd-hardware.info/?probe=83ceb2fb33) | Oct 15, 2022 |
| PC Engines    | apu4                        | Desktop     | [cefbafec73](https://bsd-hardware.info/?probe=cefbafec73) | Oct 15, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [76a1007c46](https://bsd-hardware.info/?probe=76a1007c46) | Oct 15, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [55967e02f6](https://bsd-hardware.info/?probe=55967e02f6) | Oct 15, 2022 |
| Sophos        | SG                          | Firewall    | [885bf4ef1e](https://bsd-hardware.info/?probe=885bf4ef1e) | Oct 15, 2022 |
| TYAN Compu... | Tiger K8W Dual AMD Opter... | Desktop     | [bbd42243ae](https://bsd-hardware.info/?probe=bbd42243ae) | Oct 15, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [b02dcbb7b5](https://bsd-hardware.info/?probe=b02dcbb7b5) | Oct 15, 2022 |
| TYAN Compu... | Tiger K8W Dual AMD Opter... | Desktop     | [0e9ac1e935](https://bsd-hardware.info/?probe=0e9ac1e935) | Oct 15, 2022 |
| Dell          | 081N4V A09                  | Server      | [3cbacacfa4](https://bsd-hardware.info/?probe=3cbacacfa4) | Oct 15, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [a8bdbe4d1b](https://bsd-hardware.info/?probe=a8bdbe4d1b) | Oct 15, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [799410c58f](https://bsd-hardware.info/?probe=799410c58f) | Oct 15, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [73960ade29](https://bsd-hardware.info/?probe=73960ade29) | Oct 15, 2022 |
| Sophos        | SG                          | Firewall    | [4fbe0156a8](https://bsd-hardware.info/?probe=4fbe0156a8) | Oct 15, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [5a56504b92](https://bsd-hardware.info/?probe=5a56504b92) | Oct 15, 2022 |
| AZW           | Green G1                    | Desktop     | [f6f16c5141](https://bsd-hardware.info/?probe=f6f16c5141) | Oct 15, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [ae4868c65b](https://bsd-hardware.info/?probe=ae4868c65b) | Oct 15, 2022 |
| Sophos        | XG                          | Firewall    | [e80ccac6ff](https://bsd-hardware.info/?probe=e80ccac6ff) | Oct 15, 2022 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [e08c408ced](https://bsd-hardware.info/?probe=e08c408ced) | Oct 14, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [27d7eb468e](https://bsd-hardware.info/?probe=27d7eb468e) | Oct 14, 2022 |
| Unknown       | Unknown                     | Notebook    | [3b7146c456](https://bsd-hardware.info/?probe=3b7146c456) | Oct 14, 2022 |
| Supermicro    | X10SLL-F                    | Desktop     | [3b13ea475b](https://bsd-hardware.info/?probe=3b13ea475b) | Oct 14, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [5acdcd628d](https://bsd-hardware.info/?probe=5acdcd628d) | Oct 14, 2022 |
| PC Engines    | apu1                        | Desktop     | [06debf0076](https://bsd-hardware.info/?probe=06debf0076) | Oct 14, 2022 |
| Unknown       | Unknown                     | Notebook    | [1ad8d9e64c](https://bsd-hardware.info/?probe=1ad8d9e64c) | Oct 14, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [91cc2cadd4](https://bsd-hardware.info/?probe=91cc2cadd4) | Oct 14, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [17a6b61af7](https://bsd-hardware.info/?probe=17a6b61af7) | Oct 14, 2022 |
| Unknown       | Unknown                     | Desktop     | [6c330d9bab](https://bsd-hardware.info/?probe=6c330d9bab) | Oct 14, 2022 |
| PC Engines    | APU2                        | Desktop     | [856e29140e](https://bsd-hardware.info/?probe=856e29140e) | Oct 14, 2022 |
| PC Engines    | APU2                        | Desktop     | [0e09ac984a](https://bsd-hardware.info/?probe=0e09ac984a) | Oct 14, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [3a84a32c84](https://bsd-hardware.info/?probe=3a84a32c84) | Oct 14, 2022 |
| Unknown       | J3160-4L                    | Desktop     | [42c01a3aaf](https://bsd-hardware.info/?probe=42c01a3aaf) | Oct 13, 2022 |
| ASUSTek       | P5L-VM 1394                 | Desktop     | [d7c3749eba](https://bsd-hardware.info/?probe=d7c3749eba) | Oct 13, 2022 |
| Sophos        | UTM                         | Firewall    | [364e007b1c](https://bsd-hardware.info/?probe=364e007b1c) | Oct 13, 2022 |
| Intel         | H81U                        | Notebook    | [9b212d2264](https://bsd-hardware.info/?probe=9b212d2264) | Oct 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [00b5fa7a4e](https://bsd-hardware.info/?probe=00b5fa7a4e) | Oct 13, 2022 |
| ASRock        | B550M Phantom Gaming 4      | Desktop     | [0da821d451](https://bsd-hardware.info/?probe=0da821d451) | Oct 13, 2022 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [9757e40c42](https://bsd-hardware.info/?probe=9757e40c42) | Oct 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [763365591a](https://bsd-hardware.info/?probe=763365591a) | Oct 12, 2022 |
| PC Engines    | APU2                        | Desktop     | [a06a344954](https://bsd-hardware.info/?probe=a06a344954) | Oct 12, 2022 |
| Unknown       | YL-1900L4-V2                | Desktop     | [1f55db62cc](https://bsd-hardware.info/?probe=1f55db62cc) | Oct 12, 2022 |
| HP            | ProLiant DL360e Gen8        | Server      | [0da59dff8f](https://bsd-hardware.info/?probe=0da59dff8f) | Oct 12, 2022 |
| ASRock        | H570M-ITX/ac                | Desktop     | [ea8b1fd760](https://bsd-hardware.info/?probe=ea8b1fd760) | Oct 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [7000ef7aeb](https://bsd-hardware.info/?probe=7000ef7aeb) | Oct 12, 2022 |
| Protectli     | FW4B                        | Desktop     | [2fd9fcda8e](https://bsd-hardware.info/?probe=2fd9fcda8e) | Oct 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [94915735cc](https://bsd-hardware.info/?probe=94915735cc) | Oct 11, 2022 |
| CompuLab      | fitlet2                     | Mini pc     | [abceadc2e3](https://bsd-hardware.info/?probe=abceadc2e3) | Oct 11, 2022 |
| AMD           | Inagua CRB                  | Desktop     | [59c41dcd31](https://bsd-hardware.info/?probe=59c41dcd31) | Oct 11, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [ff2b9a916f](https://bsd-hardware.info/?probe=ff2b9a916f) | Oct 11, 2022 |
| maiyunda      | www.maiyunda.com            | Desktop     | [869687f6f0](https://bsd-hardware.info/?probe=869687f6f0) | Oct 11, 2022 |
| AMD           | Inagua CRB                  | Desktop     | [ff4eccae8a](https://bsd-hardware.info/?probe=ff4eccae8a) | Oct 11, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [9d3b9cb318](https://bsd-hardware.info/?probe=9d3b9cb318) | Oct 11, 2022 |
| ASUSTek       | H110M-CS/BR                 | Desktop     | [097a263bfc](https://bsd-hardware.info/?probe=097a263bfc) | Oct 11, 2022 |
| maiyunda      | www.maiyunda.com            | Desktop     | [f4b5bf9026](https://bsd-hardware.info/?probe=f4b5bf9026) | Oct 11, 2022 |
| Supermicro    | X11SDV-4C-TP8F              | Desktop     | [2cba6fbbb7](https://bsd-hardware.info/?probe=2cba6fbbb7) | Oct 11, 2022 |
| ASRock        | B450M Pro4-F                | Desktop     | [edead8a3ae](https://bsd-hardware.info/?probe=edead8a3ae) | Oct 11, 2022 |
| AZW           | U59                         | Desktop     | [8839497803](https://bsd-hardware.info/?probe=8839497803) | Oct 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [a5cbd6786d](https://bsd-hardware.info/?probe=a5cbd6786d) | Oct 11, 2022 |
| Dell          | 0HD5W2 A00                  | Desktop     | [4fb69eef28](https://bsd-hardware.info/?probe=4fb69eef28) | Oct 11, 2022 |
| Shuttle       | FH170                       | Desktop     | [8fd08beffa](https://bsd-hardware.info/?probe=8fd08beffa) | Oct 10, 2022 |
| PCWare        | IPMH81G1                    | Desktop     | [58b53464d1](https://bsd-hardware.info/?probe=58b53464d1) | Oct 10, 2022 |
| Dell          | 06X1TJ A00                  | Desktop     | [c70e4d6b3c](https://bsd-hardware.info/?probe=c70e4d6b3c) | Oct 10, 2022 |
| NU941         | 1.0                         | Desktop     | [2690c2a8df](https://bsd-hardware.info/?probe=2690c2a8df) | Oct 10, 2022 |
| ASRock        | J4005B-ITX                  | Desktop     | [6cf37e95da](https://bsd-hardware.info/?probe=6cf37e95da) | Oct 10, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [4c9069df20](https://bsd-hardware.info/?probe=4c9069df20) | Oct 10, 2022 |
| HP            | 1495                        | Desktop     | [cfa8ab5df3](https://bsd-hardware.info/?probe=cfa8ab5df3) | Oct 10, 2022 |
| ASRock        | J3355B-ITX                  | Desktop     | [d802705c1d](https://bsd-hardware.info/?probe=d802705c1d) | Oct 10, 2022 |
| MSI           | GL65 Leopard 10SFSK         | Notebook    | [2ea7c7f9a2](https://bsd-hardware.info/?probe=2ea7c7f9a2) | Oct 10, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [8b8f621562](https://bsd-hardware.info/?probe=8b8f621562) | Oct 10, 2022 |
| Dell          | 06X1TJ A00                  | Desktop     | [21117c0374](https://bsd-hardware.info/?probe=21117c0374) | Oct 10, 2022 |
| CncTion       | Jasper-4L B0                | Desktop     | [53c643dc95](https://bsd-hardware.info/?probe=53c643dc95) | Oct 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [2fc5bd737a](https://bsd-hardware.info/?probe=2fc5bd737a) | Oct 09, 2022 |
| Protectli     | FW1 Ver                     | Desktop     | [1015ef5e66](https://bsd-hardware.info/?probe=1015ef5e66) | Oct 09, 2022 |
| HP            | 8103 A01                    | Mini pc     | [f187229469](https://bsd-hardware.info/?probe=f187229469) | Oct 09, 2022 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [e08e2ca6e0](https://bsd-hardware.info/?probe=e08e2ca6e0) | Oct 09, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [5d929362ca](https://bsd-hardware.info/?probe=5d929362ca) | Oct 09, 2022 |
| Hardkernel    | ODROID-H2                   | Desktop     | [73c9bfe38b](https://bsd-hardware.info/?probe=73c9bfe38b) | Oct 09, 2022 |
| HP            | 84F5                        | Mini pc     | [99c0387102](https://bsd-hardware.info/?probe=99c0387102) | Oct 09, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [e595ade938](https://bsd-hardware.info/?probe=e595ade938) | Oct 09, 2022 |
| ASRock        | J4005B-ITX                  | Desktop     | [0e0ff27c25](https://bsd-hardware.info/?probe=0e0ff27c25) | Oct 09, 2022 |
| MiTAC         | PH11CMI                     | Desktop     | [71802cdcad](https://bsd-hardware.info/?probe=71802cdcad) | Oct 09, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [464739212c](https://bsd-hardware.info/?probe=464739212c) | Oct 08, 2022 |
| HP            | 339A                        | Desktop     | [7ad68046ce](https://bsd-hardware.info/?probe=7ad68046ce) | Oct 08, 2022 |
| HP            | 84F5                        | Mini pc     | [ecdab22807](https://bsd-hardware.info/?probe=ecdab22807) | Oct 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [f31f4c00cd](https://bsd-hardware.info/?probe=f31f4c00cd) | Oct 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [e76890ff26](https://bsd-hardware.info/?probe=e76890ff26) | Oct 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [d6396a74dd](https://bsd-hardware.info/?probe=d6396a74dd) | Oct 08, 2022 |
| HP            | 18E7                        | Desktop     | [35e68316d8](https://bsd-hardware.info/?probe=35e68316d8) | Oct 08, 2022 |
| Lenovo        | ThinkCentre M72e 3664AD9    | Desktop     | [f6fded284d](https://bsd-hardware.info/?probe=f6fded284d) | Oct 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [e4e47282a9](https://bsd-hardware.info/?probe=e4e47282a9) | Oct 08, 2022 |
| ZOTAC         | ZBOX-CI527/CI547            | Mini pc     | [231a0f9ce0](https://bsd-hardware.info/?probe=231a0f9ce0) | Oct 08, 2022 |
| CompuLab      | fitlet2                     | Mini pc     | [82335a8874](https://bsd-hardware.info/?probe=82335a8874) | Oct 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [d25832111e](https://bsd-hardware.info/?probe=d25832111e) | Oct 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [a34c1b8ccd](https://bsd-hardware.info/?probe=a34c1b8ccd) | Oct 07, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [9d3eed2bec](https://bsd-hardware.info/?probe=9d3eed2bec) | Oct 07, 2022 |
| Lenovo        | ThinkPad X270 20HMS04P00    | Notebook    | [7647b7a0b2](https://bsd-hardware.info/?probe=7647b7a0b2) | Oct 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [ad8b88d10b](https://bsd-hardware.info/?probe=ad8b88d10b) | Oct 07, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [31ce3d5e46](https://bsd-hardware.info/?probe=31ce3d5e46) | Oct 07, 2022 |
| Dell          | 04YP6J A01                  | Desktop     | [ce728798a1](https://bsd-hardware.info/?probe=ce728798a1) | Oct 07, 2022 |
| Intel         | CRESCENTBAY                 | Desktop     | [36fb81bec0](https://bsd-hardware.info/?probe=36fb81bec0) | Oct 07, 2022 |
| YANYU         | H67SL                       | Desktop     | [373902d38b](https://bsd-hardware.info/?probe=373902d38b) | Oct 07, 2022 |
| Acer          | Aspire ES1-523              | Notebook    | [92a125995f](https://bsd-hardware.info/?probe=92a125995f) | Oct 07, 2022 |
| ASRock        | B75M R2.0                   | Desktop     | [a28ea59f1f](https://bsd-hardware.info/?probe=a28ea59f1f) | Oct 07, 2022 |
| Dell          | 0KYJ8C A02                  | Desktop     | [130a05a115](https://bsd-hardware.info/?probe=130a05a115) | Oct 07, 2022 |
| ASRock        | B450M-HDV                   | Desktop     | [84300e7dcc](https://bsd-hardware.info/?probe=84300e7dcc) | Oct 07, 2022 |
| ADI Engine... | RCC-VE                      | Desktop     | [f6a9012bb2](https://bsd-hardware.info/?probe=f6a9012bb2) | Oct 07, 2022 |
| Jingsha       | x79-P3 by xUz               | Desktop     | [7e24ab5841](https://bsd-hardware.info/?probe=7e24ab5841) | Oct 07, 2022 |
| Jingsha       | x79-P3 by xUz               | Desktop     | [11e04b0c73](https://bsd-hardware.info/?probe=11e04b0c73) | Oct 07, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [34d05fe49c](https://bsd-hardware.info/?probe=34d05fe49c) | Oct 07, 2022 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [f521533d51](https://bsd-hardware.info/?probe=f521533d51) | Oct 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [7658e5e20d](https://bsd-hardware.info/?probe=7658e5e20d) | Oct 06, 2022 |
| PC Engines    | apu1                        | Desktop     | [1a8ff34d31](https://bsd-hardware.info/?probe=1a8ff34d31) | Oct 06, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [cc0380b2c6](https://bsd-hardware.info/?probe=cc0380b2c6) | Oct 06, 2022 |
| PC Engines    | APU2                        | Desktop     | [02416f3157](https://bsd-hardware.info/?probe=02416f3157) | Oct 06, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [6dff6ec466](https://bsd-hardware.info/?probe=6dff6ec466) | Oct 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [b889791d9f](https://bsd-hardware.info/?probe=b889791d9f) | Oct 06, 2022 |
| Protectli     | FW4B                        | Desktop     | [89a0375ecb](https://bsd-hardware.info/?probe=89a0375ecb) | Oct 06, 2022 |
| Protectli     | VP4650                      | Desktop     | [c9f3c90f23](https://bsd-hardware.info/?probe=c9f3c90f23) | Oct 06, 2022 |
| YANYU         | ITX-M9F VER:1.1             | Desktop     | [dcb1d22084](https://bsd-hardware.info/?probe=dcb1d22084) | Oct 06, 2022 |
| Dell          | 081N4V A04                  | Server      | [a2d73ebe76](https://bsd-hardware.info/?probe=a2d73ebe76) | Oct 05, 2022 |
| HP            | 8299                        | Desktop     | [e0f84d2500](https://bsd-hardware.info/?probe=e0f84d2500) | Oct 05, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [7eba59d7ca](https://bsd-hardware.info/?probe=7eba59d7ca) | Oct 05, 2022 |
| CncTion       | J4125-4L-I225               | Desktop     | [eb746dc4a1](https://bsd-hardware.info/?probe=eb746dc4a1) | Oct 05, 2022 |
| Cisco         | ASA5515 A0                  | Desktop     | [bdda6913d3](https://bsd-hardware.info/?probe=bdda6913d3) | Oct 05, 2022 |
| Sophos        | SG                          | Firewall    | [44ca915943](https://bsd-hardware.info/?probe=44ca915943) | Oct 05, 2022 |
| Sophos        | XG                          | Firewall    | [cf528e776d](https://bsd-hardware.info/?probe=cf528e776d) | Oct 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [7718c8e9ca](https://bsd-hardware.info/?probe=7718c8e9ca) | Oct 05, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [63b36c077a](https://bsd-hardware.info/?probe=63b36c077a) | Oct 05, 2022 |
| Dell          | 05GD68 A00                  | Desktop     | [ec799eed0c](https://bsd-hardware.info/?probe=ec799eed0c) | Oct 05, 2022 |
| Sophos        | XG                          | Firewall    | [7db10dce96](https://bsd-hardware.info/?probe=7db10dce96) | Oct 05, 2022 |
| PC Engines    | APU2                        | Desktop     | [47e38f3abe](https://bsd-hardware.info/?probe=47e38f3abe) | Oct 05, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OPNsense/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| OPNsense 21.7.7  | 281       | 4.64%   |
| OPNsense 21.1    | 240       | 3.97%   |
| OPNsense 21.7.1  | 229       | 3.79%   |
| OPNsense 22.1    | 227       | 3.75%   |
| OPNsense 21.7.3  | 225       | 3.72%   |
| OPNsense 21.1.5  | 225       | 3.72%   |
| OPNsense 22.7.4  | 214       | 3.54%   |
| OPNsense 20.7.8  | 214       | 3.54%   |
| OPNsense 21.1.3  | 205       | 3.39%   |
| OPNsense 22.1.6  | 192       | 3.17%   |
| OPNsense 22.1.8  | 187       | 3.09%   |
| OPNsense 22.7.6  | 182       | 3.01%   |
| OPNsense 21.1.4  | 175       | 2.89%   |
| OPNsense 22.7.9  | 169       | 2.79%   |
| OPNsense 22.1.10 | 168       | 2.78%   |
| OPNsense 21.1.1  | 157       | 2.6%    |
| OPNsense 21.1.2  | 147       | 2.43%   |
| OPNsense 22.1.4  | 134       | 2.21%   |
| OPNsense 21.7.6  | 131       | 2.17%   |
| OPNsense 21.1.6  | 129       | 2.13%   |
| OPNsense 22.7    | 128       | 2.12%   |
| OPNsense 21.1.7  | 127       | 2.1%    |
| OPNsense 22.7.8  | 123       | 2.03%   |
| OPNsense 22.7.2  | 123       | 2.03%   |
| OPNsense 21.1.8  | 122       | 2.02%   |
| OPNsense 22.1.2  | 120       | 1.98%   |
| OPNsense 22.7.7  | 116       | 1.92%   |
| OPNsense 22.1.1  | 116       | 1.92%   |
| OPNsense 21.7.5  | 113       | 1.87%   |
| OPNsense 22.1.7  | 106       | 1.75%   |
| OPNsense 22.7.10 | 95        | 1.57%   |
| OPNsense 21.7.2  | 95        | 1.57%   |
| OPNsense 21.7.4  | 93        | 1.54%   |
| OPNsense 21.7    | 92        | 1.52%   |
| OPNsense 22.1.9  | 89        | 1.47%   |
| OPNsense 21.7.8  | 82        | 1.36%   |
| OPNsense 22.1.3  | 76        | 1.26%   |
| OPNsense 22.7.5  | 68        | 1.12%   |
| OPNsense 22.7.1  | 63        | 1.04%   |
| OPNsense 22.1.5  | 63        | 1.04%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| OPNsense | 4359      | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 4346      | 99.7%   |
| arm64 | 12        | 0.28%   |
| i386  | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 4358      | 99.98%  |
| helloDesktop | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 4359      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 4359      | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 4316      | 98.56%  |
| C       | 62        | 1.42%   |
| en_US   | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 4026      | 91.48%  |
| BIOS | 375       | 8.52%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Ufs    | 3360      | 75.32%  |
| Zfs    | 1100      | 24.66%  |
| Cd9660 | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 4079      | 92.92%  |
| MBR     | 253       | 5.76%   |
| Unknown | 54        | 1.23%   |
| BSD     | 4         | 0.09%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Dell                       | 476       | 10.92%  |
| Unknown                    | 472       | 10.83%  |
| Hewlett-Packard            | 359       | 8.24%   |
| Supermicro                 | 305       | 7%      |
| Intel                      | 279       | 6.4%    |
| Protectli                  | 241       | 5.53%   |
| PC Engines                 | 232       | 5.32%   |
| ASUSTek Computer           | 198       | 4.54%   |
| ASRock                     | 176       | 4.04%   |
| AMI                        | 159       | 3.65%   |
| Lenovo                     | 156       | 3.58%   |
| Gigabyte Technology        | 130       | 2.98%   |
| Sophos                     | 108       | 2.48%   |
| Fujitsu                    | 102       | 2.34%   |
| MSI                        | 98        | 2.25%   |
| ZOTAC                      | 78        | 1.79%   |
| Deciso                     | 63        | 1.45%   |
| BESSTAR Tech               | 55        | 1.26%   |
| Shuttle                    | 50        | 1.15%   |
| MW                         | 29        | 0.67%   |
| AWOW                       | 28        | 0.64%   |
| HARDKERNEL                 | 26        | 0.6%    |
| CompuLab                   | 26        | 0.6%    |
| Biostar                    | 25        | 0.57%   |
| Acer                       | 25        | 0.57%   |
| Techvision                 | 24        | 0.55%   |
| AZW                        | 20        | 0.46%   |
| ShenZhen MinWin Technology | 15        | 0.34%   |
| ASRockRack                 | 15        | 0.34%   |
| YANYU                      | 14        | 0.32%   |
| CheckPoint                 | 14        | 0.32%   |
| Apple                      | 14        | 0.32%   |
| AAEON                      | 14        | 0.32%   |
| Thomas-Krenn.AG            | 12        | 0.28%   |
| Foxconn                    | 12        | 0.28%   |
| Seeed Studio               | 11        | 0.25%   |
| Inventec                   | 11        | 0.25%   |
| Cisco                      | 11        | 0.25%   |
| HPE                        | 10        | 0.23%   |
| SeeedStudio                | 9         | 0.21%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 486       | 11.15%  |
| AMI Aptio CRB                       | 125       | 2.87%   |
| PC Engines APU2                     | 114       | 2.62%   |
| Protectli FW4B                      | 101       | 2.32%   |
| Intel Q3XXG4-P V1.0                 | 98        | 2.25%   |
| Supermicro Super Server             | 88        | 2.02%   |
| PC Engines apu4                     | 79        | 1.81%   |
| Protectli FW6                       | 73        | 1.67%   |
| Sophos SG                           | 54        | 1.24%   |
| Fujitsu FUTRO S920                  | 44        | 1.01%   |
| HP t620 PLUS Quad Core TC           | 43        | 0.99%   |
| HP t730 Thin Client                 | 38        | 0.87%   |
| Dell PowerEdge R210 II              | 38        | 0.87%   |
| Sophos XG                           | 31        | 0.71%   |
| ASUS All Series                     | 30        | 0.69%   |
| MW GMLK-2_5G4L                      | 29        | 0.67%   |
| Dell OptiPlex 9020                  | 29        | 0.67%   |
| Dell OptiPlex 3020                  | 29        | 0.67%   |
| Dell OptiPlex 7010                  | 26        | 0.6%    |
| Techvision TVI7309X                 | 24        | 0.55%   |
| HARDKERNEL ODROID-H2                | 24        | 0.55%   |
| Sophos UTM                          | 23        | 0.53%   |
| Supermicro X10SLH-N6-ST031          | 19        | 0.44%   |
| Supermicro A1SAi                    | 19        | 0.44%   |
| CompuLab fitlet2                    | 19        | 0.44%   |
| AWOW PC BOX                         | 19        | 0.44%   |
| ZOTAC ZBOX-CI329NANO                | 18        | 0.41%   |
| HP EliteDesk 800 G1 SFF             | 18        | 0.41%   |
| Dell Wyse 5070 Extended Thin Client | 18        | 0.41%   |
| Deciso Netboard A20                 | 18        | 0.41%   |
| Supermicro X9SCL/X9SCM              | 17        | 0.39%   |
| Protectli VP2410                    | 17        | 0.39%   |
| PC Engines APU3                     | 16        | 0.37%   |
| PC Engines APU                      | 15        | 0.34%   |
| BESSTAR Tech GK41                   | 15        | 0.34%   |
| Protectli FW2B                      | 14        | 0.32%   |
| ZOTAC ZBOX-CI327NANO-GS-01          | 13        | 0.3%    |
| Intel CRESCENTBAY                   | 13        | 0.3%    |
| Dell PowerEdge R610                 | 13        | 0.3%    |
| ZOTAC ZBOX-CI323NANO                | 12        | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Unknown                    | 486       | 11.15%  |
| Dell OptiPlex              | 215       | 4.93%   |
| Dell PowerEdge             | 181       | 4.15%   |
| AMI Aptio                  | 127       | 2.91%   |
| PC Engines APU2            | 114       | 2.62%   |
| Lenovo ThinkCentre         | 103       | 2.36%   |
| Protectli FW4B             | 101       | 2.32%   |
| Intel Q3XXG4-P             | 98        | 2.25%   |
| Supermicro Super           | 88        | 2.02%   |
| HP ProLiant                | 86        | 1.97%   |
| PC Engines apu4            | 79        | 1.81%   |
| Protectli FW6              | 73        | 1.67%   |
| Fujitsu FUTRO              | 60        | 1.38%   |
| Sophos SG                  | 54        | 1.24%   |
| HP ProDesk                 | 50        | 1.15%   |
| HP t620                    | 45        | 1.03%   |
| HP EliteDesk               | 45        | 1.03%   |
| HP Compaq                  | 44        | 1.01%   |
| HP t730                    | 38        | 0.87%   |
| Deciso Netboard            | 36        | 0.83%   |
| Sophos XG                  | 31        | 0.71%   |
| ASUS All                   | 30        | 0.69%   |
| MW GMLK-2                  | 29        | 0.67%   |
| ASUS PRIME                 | 27        | 0.62%   |
| Techvision TVI7309X        | 24        | 0.55%   |
| Hardkernel ODROID-H2       | 24        | 0.55%   |
| Sophos UTM                 | 23        | 0.53%   |
| Dell Wyse                  | 22        | 0.5%    |
| Fujitsu ESPRIMO            | 21        | 0.48%   |
| Dell Precision             | 20        | 0.46%   |
| Supermicro X10SLH-N6-ST031 | 19        | 0.44%   |
| Supermicro A1SAi           | 19        | 0.44%   |
| CompuLab fitlet2           | 19        | 0.44%   |
| AWOW PC                    | 19        | 0.44%   |
| ZOTAC ZBOX-CI329NANO       | 18        | 0.41%   |
| Supermicro X9SCL           | 17        | 0.39%   |
| Supermicro 1HE             | 17        | 0.39%   |
| Protectli VP2410           | 17        | 0.39%   |
| Lenovo ThinkPad            | 17        | 0.39%   |
| PC Engines APU3            | 16        | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 625       | 14.34%  |
| 2019    | 472       | 10.83%  |
| 2016    | 440       | 10.09%  |
| 2020    | 431       | 9.89%   |
| 2021    | 383       | 8.79%   |
| 2014    | 372       | 8.53%   |
| 2017    | 273       | 6.26%   |
| 2013    | 264       | 6.06%   |
| 2015    | 238       | 5.46%   |
| 2022    | 217       | 4.98%   |
| 2011    | 198       | 4.54%   |
| 2012    | 182       | 4.18%   |
| 2010    | 116       | 2.66%   |
| 2009    | 68        | 1.56%   |
| 2008    | 45        | 1.03%   |
| 2007    | 18        | 0.41%   |
| 2006    | 9         | 0.21%   |
| Unknown | 6         | 0.14%   |
| 2005    | 1         | 0.02%   |
| 2004    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 3104      | 71.21%  |
| Mini pc        | 479       | 10.99%  |
| Server         | 473       | 10.85%  |
| Notebook       | 164       | 3.76%   |
| Firewall       | 130       | 2.98%   |
| All in one     | 5         | 0.11%   |
| Convertible    | 3         | 0.07%   |
| System on chip | 1         | 0.02%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4037      | 92.61%  |
| Yes  | 322       | 7.39%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 1805      | 40.45%  |
| 4.01-8.0        | 1120      | 25.1%   |
| 16.01-24.0      | 858       | 19.23%  |
| 32.01-64.0      | 296       | 6.63%   |
| 2.01-3.0        | 183       | 4.1%    |
| 64.01-256.0     | 98        | 2.2%    |
| 24.01-32.0      | 41        | 0.92%   |
| 3.01-4.0        | 33        | 0.74%   |
| 1.01-2.0        | 15        | 0.34%   |
| 0.51-1.0        | 9         | 0.2%    |
| More than 256.0 | 4         | 0.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 2645      | 58.21%  |
| 0.51-1.0    | 1241      | 27.31%  |
| 1.01-2.0    | 382       | 8.41%   |
| 2.01-3.0    | 89        | 1.96%   |
| 4.01-8.0    | 80        | 1.76%   |
| 3.01-4.0    | 51        | 1.12%   |
| 8.01-16.0   | 33        | 0.73%   |
| 16.01-24.0  | 10        | 0.22%   |
| 24.01-32.0  | 6         | 0.13%   |
| 32.01-64.0  | 3         | 0.07%   |
| 64.01-256.0 | 3         | 0.07%   |
| 0           | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 3583      | 80.95%  |
| 0      | 438       | 9.9%    |
| 2      | 346       | 7.82%   |
| 3      | 34        | 0.77%   |
| 4      | 15        | 0.34%   |
| 5      | 5         | 0.11%   |
| 25     | 2         | 0.05%   |
| 6      | 2         | 0.05%   |
| 8      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 3813      | 86.92%  |
| Yes       | 574       | 13.08%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4347      | 99.72%  |
| No        | 12        | 0.28%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 3540      | 80.38%  |
| Yes       | 864       | 19.62%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 3920      | 89.31%  |
| Yes       | 469       | 10.69%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 1264      | 28.88%  |
| Germany      | 1004      | 22.94%  |
| UK           | 181       | 4.14%   |
| Canada       | 175       | 4%      |
| France       | 160       | 3.66%   |
| Netherlands  | 125       | 2.86%   |
| Australia    | 112       | 2.56%   |
| Austria      | 106       | 2.42%   |
| Switzerland  | 103       | 2.35%   |
| Poland       | 85        | 1.94%   |
| Sweden       | 76        | 1.74%   |
| Brazil       | 73        | 1.67%   |
| Italy        | 60        | 1.37%   |
| Russia       | 54        | 1.23%   |
| China        | 53        | 1.21%   |
| Spain        | 46        | 1.05%   |
| Belgium      | 39        | 0.89%   |
| Portugal     | 34        | 0.78%   |
| Finland      | 34        | 0.78%   |
| Denmark      | 34        | 0.78%   |
| Romania      | 33        | 0.75%   |
| Norway       | 29        | 0.66%   |
| Indonesia    | 29        | 0.66%   |
| South Korea  | 28        | 0.64%   |
| South Africa | 28        | 0.64%   |
| Czechia      | 28        | 0.64%   |
| Taiwan       | 23        | 0.53%   |
| Hungary      | 20        | 0.46%   |
| New Zealand  | 19        | 0.43%   |
| India        | 19        | 0.43%   |
| Japan        | 17        | 0.39%   |
| Singapore    | 15        | 0.34%   |
| Mexico       | 15        | 0.34%   |
| Israel       | 14        | 0.32%   |
| Hong Kong    | 14        | 0.32%   |
| Slovenia     | 12        | 0.27%   |
| Bulgaria     | 12        | 0.27%   |
| Lithuania    | 11        | 0.25%   |
| Turkey       | 9         | 0.21%   |
| Latvia       | 9         | 0.21%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Berlin            | 84        | 1.71%   |
| Munich            | 48        | 0.98%   |
| Vienna            | 45        | 0.91%   |
| Hamburg           | 45        | 0.91%   |
| Paris             | 36        | 0.73%   |
| Frankfurt am Main | 29        | 0.59%   |
| Cologne           | 27        | 0.55%   |
| Sydney            | 25        | 0.51%   |
| Zurich            | 23        | 0.47%   |
| Melbourne         | 23        | 0.47%   |
| Toronto           | 21        | 0.43%   |
| London            | 21        | 0.43%   |
| Bucharest         | 21        | 0.43%   |
| Stuttgart         | 20        | 0.41%   |
| Moscow            | 20        | 0.41%   |
| Denver            | 19        | 0.39%   |
| Chicago           | 19        | 0.39%   |
| Seattle           | 17        | 0.35%   |
| Karlsruhe         | 17        | 0.35%   |
| Dallas            | 17        | 0.35%   |
| Perth             | 16        | 0.33%   |
| New York          | 16        | 0.33%   |
| Jakarta           | 16        | 0.33%   |
| Amsterdam         | 16        | 0.33%   |
| Warsaw            | 15        | 0.3%    |
| Austin            | 15        | 0.3%    |
| Singapore         | 14        | 0.28%   |
| Mountain View     | 14        | 0.28%   |
| Brisbane          | 14        | 0.28%   |
| Columbus          | 13        | 0.26%   |
| Ottawa            | 12        | 0.24%   |
| Madrid            | 12        | 0.24%   |
| Johannesburg      | 12        | 0.24%   |
| Hanover           | 12        | 0.24%   |
| Stockholm         | 11        | 0.22%   |
| Montreal          | 11        | 0.22%   |
| Helsinki          | 11        | 0.22%   |
| Dresden           | 11        | 0.22%   |
| Beijing           | 11        | 0.22%   |
| SГЈo Paulo      | 10        | 0.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 623       | 901    | 14.52%  |
| Kingston            | 410       | 601    | 9.55%   |
| Transcend           | 339       | 487    | 7.9%    |
| WDC                 | 323       | 495    | 7.53%   |
| Seagate             | 237       | 379    | 5.52%   |
| SanDisk             | 230       | 311    | 5.36%   |
| Intel               | 212       | 315    | 4.94%   |
| Crucial             | 197       | 301    | 4.59%   |
| Hoodisk             | 170       | 243    | 3.96%   |
| China               | 115       | 166    | 2.68%   |
| Phison              | 110       | 158    | 2.56%   |
| Toshiba             | 98        | 168    | 2.28%   |
| A-DATA Technology   | 95        | 139    | 2.21%   |
| FORESEE             | 73        | 106    | 1.7%    |
| Hewlett-Packard     | 64        | 114    | 1.49%   |
| Protectli           | 49        | 80     | 1.14%   |
| Dogfish             | 48        | 77     | 1.12%   |
| OCZ                 | 46        | 66     | 1.07%   |
| Micron Technology   | 46        | 73     | 1.07%   |
| Hitachi             | 46        | 66     | 1.07%   |
| Apacer              | 43        | 52     | 1%      |
| SPCC                | 42        | 63     | 0.98%   |
| PNY                 | 38        | 61     | 0.89%   |
| Innodisk            | 36        | 44     | 0.84%   |
| Intenso             | 34        | 61     | 0.79%   |
| HGST                | 34        | 75     | 0.79%   |
| BIWIN               | 34        | 49     | 0.79%   |
| SK hynix            | 32        | 44     | 0.75%   |
| Corsair             | 30        | 46     | 0.7%    |
| LITEONIT            | 21        | 25     | 0.49%   |
| LITEON              | 20        | 30     | 0.47%   |
| ATP                 | 19        | 22     | 0.44%   |
| Kston               | 18        | 23     | 0.42%   |
| Silicon Motion      | 16        | 18     | 0.37%   |
| Patriot             | 16        | 25     | 0.37%   |
| KingSpec            | 16        | 19     | 0.37%   |
| ShiJi               | 15        | 24     | 0.35%   |
| Gigabyte Technology | 15        | 20     | 0.35%   |
| Plextor             | 13        | 20     | 0.3%    |
| Team                | 10        | 11     | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| Phison SATA SSD 16GB            | 62        | 1.42%   |
| Kingston SUV500MS120G 120GB     | 54        | 1.24%   |
| Kingston SA400S37240G 240GB     | 54        | 1.24%   |
| Kingston SA400S37120G 120GB     | 50        | 1.15%   |
| Samsung SSD 850 EVO 250GB       | 47        | 1.08%   |
| Hoodisk SSD 32GB                | 47        | 1.08%   |
| Hoodisk SSD 128GB               | 46        | 1.06%   |
| Hoodisk SSD 64GB                | 45        | 1.03%   |
| Transcend TS128GMSA230S 128GB   | 43        | 0.99%   |
| FORESEE 128GB SSD               | 41        | 0.94%   |
| Crucial CT240BX500SSD1 240GB    | 33        | 0.76%   |
| HP RAID 1(1+0) 800GB            | 32        | 0.74%   |
| Kingston SUV500MS240G 240GB     | 29        | 0.67%   |
| Crucial CT120BX500SSD1 120GB    | 28        | 0.64%   |
| Transcend TS64GMSA230S 64GB     | 27        | 0.62%   |
| Seagate ST500DM002-1BD142 500GB | 26        | 0.6%    |
| BIWIN SSD 128GB                 | 26        | 0.6%    |
| Crucial CT250MX500SSD1 250GB    | 25        | 0.57%   |
| Transcend TS256GMSA230S 256GB   | 23        | 0.53%   |
| Samsung SSD 860 EVO 250GB       | 23        | 0.53%   |
| Kingston SV300S37A120G 120GB    | 23        | 0.53%   |
| Kingston SKC600MS256G 256GB     | 22        | 0.51%   |
| China SATA SSD 16GB             | 22        | 0.51%   |
| Transcend TS256GMTS952T2 256GB  | 21        | 0.48%   |
| Samsung SSD 840 EVO 120GB       | 21        | 0.48%   |
| PNY CS900 120GB SSD             | 21        | 0.48%   |
| Samsung SSD 850 EVO 120GB       | 20        | 0.46%   |
| Protectli 120GB mSATA           | 20        | 0.46%   |
| FORESEE 64GB SSD                | 20        | 0.46%   |
| A-DATA SU650 120GB              | 20        | 0.46%   |
| SanDisk SDSSDA120G 120GB        | 19        | 0.44%   |
| Samsung SSD 870 EVO 250GB       | 19        | 0.44%   |
| Samsung SSD 860 EVO 500GB       | 19        | 0.44%   |
| Samsung SSD 840 EVO 250GB       | 19        | 0.44%   |
| WDC WDS120G2G0A-00JH30 120GB    | 18        | 0.41%   |
| Samsung SSD 850 EVO 500GB       | 18        | 0.41%   |
| Hoodisk SSD 16GB                | 18        | 0.41%   |
| Transcend TS64GSSD370 64GB      | 17        | 0.39%   |
| Transcend TS64GMSA370 64GB      | 17        | 0.39%   |
| Transcend TS128GMSA370 128GB    | 17        | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 220       | 347    | 32.69%  |
| WDC                 | 212       | 328    | 31.5%   |
| Toshiba             | 65        | 116    | 9.66%   |
| Hitachi             | 46        | 66     | 6.84%   |
| HGST                | 34        | 75     | 5.05%   |
| Samsung Electronics | 27        | 35     | 4.01%   |
| Hewlett-Packard     | 27        | 53     | 4.01%   |
| Maxtor              | 9         | 10     | 1.34%   |
| Fujitsu             | 6         | 7      | 0.89%   |
| HPE                 | 5         | 17     | 0.74%   |
| Apple               | 5         | 7      | 0.74%   |
| Dell                | 3         | 49     | 0.45%   |
| NETAPP              | 2         | 4      | 0.3%    |
| LSILOGIC            | 2         | 5      | 0.3%    |
| Cisco               | 2         | 4      | 0.3%    |
| Adaptec             | 2         | 2      | 0.3%    |
| MARVELL             | 1         | 1      | 0.15%   |
| LSI                 | 1         | 1      | 0.15%   |
| InnoLite            | 1         | 1      | 0.15%   |
| IBM-207x            | 1         | 1      | 0.15%   |
| China               | 1         | 1      | 0.15%   |
| Cactus              | 1         | 1      | 0.15%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 464       | 652    | 14.43%  |
| Kingston            | 374       | 546    | 11.63%  |
| Transcend           | 313       | 458    | 9.74%   |
| SanDisk             | 229       | 310    | 7.12%   |
| Intel               | 190       | 287    | 5.91%   |
| Crucial             | 178       | 275    | 5.54%   |
| Hoodisk             | 169       | 242    | 5.26%   |
| China               | 114       | 165    | 3.55%   |
| Phison              | 96        | 131    | 2.99%   |
| A-DATA Technology   | 83        | 119    | 2.58%   |
| FORESEE             | 71        | 103    | 2.21%   |
| WDC                 | 66        | 93     | 2.05%   |
| Protectli           | 49        | 80     | 1.52%   |
| Dogfish             | 48        | 77     | 1.49%   |
| OCZ                 | 46        | 66     | 1.43%   |
| Micron Technology   | 43        | 68     | 1.34%   |
| Apacer              | 43        | 52     | 1.34%   |
| Hewlett-Packard     | 39        | 61     | 1.21%   |
| SPCC                | 37        | 54     | 1.15%   |
| PNY                 | 37        | 60     | 1.15%   |
| Innodisk            | 36        | 44     | 1.12%   |
| Intenso             | 34        | 61     | 1.06%   |
| BIWIN               | 34        | 49     | 1.06%   |
| Toshiba             | 26        | 41     | 0.81%   |
| Corsair             | 26        | 39     | 0.81%   |
| LITEONIT            | 21        | 25     | 0.65%   |
| SK hynix            | 19        | 26     | 0.59%   |
| LITEON              | 19        | 29     | 0.59%   |
| Kston               | 18        | 23     | 0.56%   |
| KingSpec            | 16        | 19     | 0.5%    |
| ATP                 | 16        | 16     | 0.5%    |
| ShiJi               | 14        | 23     | 0.44%   |
| Patriot             | 14        | 23     | 0.44%   |
| Plextor             | 12        | 18     | 0.37%   |
| Seagate             | 11        | 25     | 0.34%   |
| Netac               | 9         | 13     | 0.28%   |
| Mushkin             | 9         | 14     | 0.28%   |
| Supermicro          | 8         | 8      | 0.25%   |
| KingDian            | 8         | 9      | 0.25%   |
| Gigabyte Technology | 8         | 13     | 0.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 3065      | 4668   | 74.72%  |
| HDD  | 630       | 1131   | 15.36%  |
| NVMe | 407       | 606    | 9.92%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3586      | 5799   | 89.81%  |
| NVMe | 407       | 606    | 10.19%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 3332      | 5252   | 91.01%  |
| 0.51-1.0   | 274       | 424    | 7.48%   |
| 1.01-2.0   | 41        | 79     | 1.12%   |
| 2.01-3.0   | 7         | 10     | 0.19%   |
| 3.01-4.0   | 4         | 5      | 0.11%   |
| 4.01-10.0  | 3         | 29     | 0.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 2099      | 46.79%  |
| 251-500        | 601       | 13.4%   |
| 51-100         | 592       | 13.2%   |
| 21-50          | 589       | 13.13%  |
| 1-20           | 348       | 7.76%   |
| 501-1000       | 202       | 4.5%    |
| 1001-2000      | 38        | 0.85%   |
| More than 3000 | 8         | 0.18%   |
| 2001-3000      | 5         | 0.11%   |
| Unknown        | 4         | 0.09%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 4262      | 95.18%  |
| 21-50   | 151       | 3.37%   |
| 51-100  | 47        | 1.05%   |
| 101-250 | 14        | 0.31%   |
| Unknown | 4         | 0.09%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB    | 13        | 24     | 2.88%   |
| Kingston SV300S37A120G 120GB       | 11        | 13     | 2.43%   |
| Apacer 16GB SATA Flash Drive       | 8         | 10     | 1.77%   |
| Kingston SV300S37A60G 64GB         | 7         | 9      | 1.55%   |
| Seagate ST500LM021-1KJ152 500GB    | 6         | 6      | 1.33%   |
| HGST HTS725050A7E630 500GB         | 6         | 11     | 1.33%   |
| Seagate ST3160815AS 160GB          | 5         | 6      | 1.11%   |
| Crucial CT275MX300SSD1 275GB       | 5         | 6      | 1.11%   |
| Kingston SMS200S360G 64GB          | 4         | 4      | 0.88%   |
| Kingston SMS200S3120G 120GB        | 4         | 5      | 0.88%   |
| Intel SSDSA2M160G2GC 160GB         | 4         | 6      | 0.88%   |
| WDC WDS240G2G0A-00JH30 240GB       | 3         | 4      | 0.66%   |
| WDC WDS120G2G0A-00JH30 120GB       | 3         | 4      | 0.66%   |
| WDC WD1600AAJS-75M0A0 160GB        | 3         | 3      | 0.66%   |
| VisionTek mSATA 120GB              | 3         | 7      | 0.66%   |
| Seagate ST500LT012-1DG142 500GB    | 3         | 4      | 0.66%   |
| Seagate ST3500418AS 500GB          | 3         | 9      | 0.66%   |
| Seagate ST3250310AS 250GB          | 3         | 3      | 0.66%   |
| Seagate ST320LT007-9ZV142 320GB    | 3         | 3      | 0.66%   |
| Seagate ST3160318AS 160GB          | 3         | 6      | 0.66%   |
| LITEON CV8-8E128-HP 128GB          | 3         | 4      | 0.66%   |
| Kingston SUV400S37120G 120GB       | 3         | 5      | 0.66%   |
| Intel SSDSC2CT120A3 120GB          | 3         | 3      | 0.66%   |
| Hitachi HDS721050CLA660 500GB      | 3         | 4      | 0.66%   |
| WDC WD800JD-60LSA5 80GB            | 2         | 2      | 0.44%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 2         | 3      | 0.44%   |
| WDC WD5000AAKS-22V1A0 500GB        | 2         | 2      | 0.44%   |
| Toshiba MQ01ABD075 752GB           | 2         | 2      | 0.44%   |
| Toshiba DT01ACA100 1TB             | 2         | 2      | 0.44%   |
| Toshiba DT01ACA050 500GB           | 2         | 2      | 0.44%   |
| SK hynix SC308 SATA 128GB          | 2         | 3      | 0.44%   |
| SK hynix SC210 mSATA 256GB         | 2         | 2      | 0.44%   |
| Seagate ST9320423AS 320GB          | 2         | 2      | 0.44%   |
| Seagate ST500LT012-9WS142 500GB    | 2         | 3      | 0.44%   |
| Seagate ST380815AS 80GB            | 2         | 2      | 0.44%   |
| Seagate ST3160310CS 160GB          | 2         | 2      | 0.44%   |
| Seagate ST1000NM0011 1TB           | 2         | 3      | 0.44%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 3      | 0.44%   |
| SanDisk SSD P4 16GB                | 2         | 2      | 0.44%   |
| SanDisk SDSSDA240G 240GB           | 2         | 3      | 0.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 85        | 134    | 18.81%  |
| WDC                 | 57        | 83     | 12.61%  |
| Kingston            | 44        | 56     | 9.73%   |
| Intel               | 38        | 57     | 8.41%   |
| Samsung Electronics | 32        | 47     | 7.08%   |
| Crucial             | 23        | 34     | 5.09%   |
| Hitachi             | 20        | 26     | 4.42%   |
| Toshiba             | 19        | 24     | 4.2%    |
| SanDisk             | 15        | 28     | 3.32%   |
| Apacer              | 11        | 13     | 2.43%   |
| OCZ                 | 10        | 13     | 2.21%   |
| HGST                | 10        | 16     | 2.21%   |
| China               | 7         | 8      | 1.55%   |
| A-DATA Technology   | 7         | 10     | 1.55%   |
| SK hynix            | 6         | 8      | 1.33%   |
| Micron Technology   | 6         | 6      | 1.33%   |
| Dogfish             | 5         | 11     | 1.11%   |
| Corsair             | 5         | 8      | 1.11%   |
| Maxtor              | 4         | 4      | 0.88%   |
| LITEON              | 4         | 5      | 0.88%   |
| VisionTek           | 3         | 7      | 0.66%   |
| KingDian            | 3         | 3      | 0.66%   |
| Hewlett-Packard     | 3         | 4      | 0.66%   |
| BIWIN               | 3         | 5      | 0.66%   |
| Transcend           | 2         | 3      | 0.44%   |
| SPCC                | 2         | 4      | 0.44%   |
| Phison              | 2         | 2      | 0.44%   |
| MyDigitalSSD        | 2         | 4      | 0.44%   |
| Intenso             | 2         | 2      | 0.44%   |
| HP Phison           | 2         | 2      | 0.44%   |
| ZTC                 | 1         | 3      | 0.22%   |
| Wintec              | 1         | 1      | 0.22%   |
| V-GeN               | 1         | 1      | 0.22%   |
| Terabit             | 1         | 1      | 0.22%   |
| SMI                 | 1         | 1      | 0.22%   |
| ShiJi               | 1         | 1      | 0.22%   |
| PNY                 | 1         | 1      | 0.22%   |
| Plextor             | 1         | 1      | 0.22%   |
| Netac               | 1         | 1      | 0.22%   |
| Mushkin             | 1         | 1      | 0.22%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 85        | 134    | 41.87%  |
| WDC                 | 50        | 74     | 24.63%  |
| Hitachi             | 20        | 26     | 9.85%   |
| Toshiba             | 14        | 15     | 6.9%    |
| Samsung Electronics | 13        | 15     | 6.4%    |
| HGST                | 10        | 16     | 4.93%   |
| Maxtor              | 4         | 4      | 1.97%   |
| Hewlett-Packard     | 3         | 4      | 1.48%   |
| InnoLite            | 1         | 1      | 0.49%   |
| HPE                 | 1         | 3      | 0.49%   |
| China               | 1         | 1      | 0.49%   |
| Cactus              | 1         | 1      | 0.49%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 244       | 348    | 54.46%  |
| HDD  | 200       | 294    | 44.64%  |
| NVMe | 4         | 9      | 0.89%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Samsung Electronics MZYLN256HCHP-000L2 256GB | 2         | 2      | 16.67%  |
| WDC WD3200BPVT-16JJ5T0 320GB                 | 1         | 1      | 8.33%   |
| WDC WD10SPZX-00Z10T0 1TB                     | 1         | 1      | 8.33%   |
| Transcend TS32GSSD370S 32GB                  | 1         | 1      | 8.33%   |
| SK hynix SC308 SATA 256GB                    | 1         | 1      | 8.33%   |
| Seagate ST4000NM0025 4TB                     | 1         | 2      | 8.33%   |
| Seagate ST3500418AS 500GB                    | 1         | 2      | 8.33%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB   | 1         | 1      | 8.33%   |
| Kingston SV300S37A60G 64GB                   | 1         | 1      | 8.33%   |
| Intel SSDSC2BW120H6 120GB                    | 1         | 1      | 8.33%   |
| Crucial CT250P2SSD8 250GB                    | 1         | 1      | 8.33%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 16.67%  |
| Seagate             | 2         | 4      | 16.67%  |
| Samsung Electronics | 2         | 2      | 16.67%  |
| Transcend           | 1         | 1      | 8.33%   |
| SK hynix            | 1         | 1      | 8.33%   |
| Micron Technology   | 1         | 1      | 8.33%   |
| Kingston            | 1         | 1      | 8.33%   |
| Intel               | 1         | 1      | 8.33%   |
| Crucial             | 1         | 1      | 8.33%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 3520      | 5587   | 86.42%  |
| Malfunc  | 444       | 651    | 10.9%   |
| Detected | 97        | 153    | 2.38%   |
| Failed   | 12        | 14     | 0.29%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3550      | 71.36%  |
| AMD                              | 679       | 13.65%  |
| Samsung Electronics              | 137       | 2.75%   |
| Broadcom / LSI                   | 130       | 2.61%   |
| ASMedia Technology               | 59        | 1.19%   |
| SanDisk                          | 55        | 1.11%   |
| Hewlett-Packard                  | 49        | 0.98%   |
| Kingston Technology Company      | 36        | 0.72%   |
| Phison Electronics               | 34        | 0.68%   |
| Silicon Motion                   | 32        | 0.64%   |
| Marvell Technology Group         | 28        | 0.56%   |
| Chelsio Communications           | 26        | 0.52%   |
| Transcend                        | 22        | 0.44%   |
| Micron/Crucial Technology        | 18        | 0.36%   |
| SK hynix                         | 13        | 0.26%   |
| Nvidia                           | 12        | 0.24%   |
| JMicron Technology               | 12        | 0.24%   |
| ADATA Technology                 | 10        | 0.2%    |
| Toshiba                          | 8         | 0.16%   |
| Silicon Image                    | 6         | 0.12%   |
| Shenzhen Longsys Electronics     | 6         | 0.12%   |
| Seagate Technology               | 6         | 0.12%   |
| Micron Technology                | 5         | 0.1%    |
| MAXIO Technology (Hangzhou)      | 5         | 0.1%    |
| KIOXIA                           | 5         | 0.1%    |
| ATP ELECTRONICS                  | 5         | 0.1%    |
| Adaptec                          | 5         | 0.1%    |
| VIA Technologies                 | 3         | 0.06%   |
| Realtek Semiconductor            | 3         | 0.06%   |
| Dell                             | 3         | 0.06%   |
| XenSource                        | 2         | 0.04%   |
| Solid State Storage Technology   | 2         | 0.04%   |
| Lite-On Technology               | 2         | 0.04%   |
| Yangtze Memory Technologies      | 1         | 0.02%   |
| Unknown                          | 1         | 0.02%   |
| Union Memory (Shenzhen)          | 1         | 0.02%   |
| Silicon Integrated Systems [SiS] | 1         | 0.02%   |
| Integrated Technology Express    | 1         | 0.02%   |
| Biwin Storage Technology         | 1         | 0.02%   |
| 3ware                            | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 472       | 8.4%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 397       | 7.06%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 285       | 5.07%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 265       | 4.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 260       | 4.63%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 244       | 4.34%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 207       | 3.68%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 166       | 2.95%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 146       | 2.6%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 109       | 1.94%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 100       | 1.78%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 96        | 1.71%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 90        | 1.6%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 86        | 1.53%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 83        | 1.48%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 80        | 1.42%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 78        | 1.39%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 75        | 1.33%   |
| Unknown                                                                                 | 75        | 1.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 72        | 1.28%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                                        | 67        | 1.19%   |
| Intel SATA Controller [RAID mode]                                                       | 64        | 1.14%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 61        | 1.09%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 59        | 1.05%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 52        | 0.93%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 51        | 0.91%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 50        | 0.89%   |
| Intel Atom Processor C3000 Series SATA Controller 0                                     | 48        | 0.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 48        | 0.85%   |
| Intel Atom Processor C3000 Series SATA Controller 1                                     | 44        | 0.78%   |
| AMD FCH IDE Controller                                                                  | 44        | 0.78%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 41        | 0.73%   |
| Intel Atom processor C2000 AHCI SATA2 Controller                                        | 41        | 0.73%   |
| AMD 400 Series Chipset SATA Controller                                                  | 41        | 0.73%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 38        | 0.68%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 38        | 0.68%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                           | 36        | 0.64%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 35        | 0.62%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 35        | 0.62%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 34        | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3744      | 73.67%  |
| IDE  | 562       | 11.06%  |
| NVMe | 424       | 8.34%   |
| RAID | 277       | 5.45%   |
| SCSI | 44        | 0.87%   |
| SAS  | 31        | 0.61%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 3638      | 83.27%  |
| AMD     | 717       | 16.41%  |
| ARM     | 9         | 0.21%   |
| Unknown | 3         | 0.07%   |
| VIA     | 2         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| AMD GX-412TC SOC                         | 210       | 4.75%   |
| Intel Celeron J4125 CPU @ 2.00GHz        | 164       | 3.71%   |
| Intel Celeron CPU J3160 @ 1.60GHz        | 150       | 3.39%   |
| Intel Celeron CPU J1900 @ 1.99GHz        | 137       | 3.1%    |
| Intel Celeron N5105 @ 2.00GHz            | 65        | 1.47%   |
| Intel Celeron CPU J3455 @ 1.50GHz        | 56        | 1.27%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 55        | 1.24%   |
| Intel Core i5-6500 CPU @ 3.20GHz         | 47        | 1.06%   |
| AMD GX-420CA SOC with Radeon HD Graphics | 47        | 1.06%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 46        | 1.04%   |
| Intel Core i5-4570 CPU @ 3.20GHz         | 41        | 0.93%   |
| Intel Atom CPU D525 @ 1.80GHz            | 41        | 0.93%   |
| AMD RX-427BB with AMD Radeon R7 Graphics | 40        | 0.9%    |
| Intel Celeron J4105 CPU @ 1.50GHz        | 38        | 0.86%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 35        | 0.79%   |
| Intel Core i3-7100U CPU @ 2.40GHz        | 34        | 0.77%   |
| Intel Celeron CPU 3865U @ 1.80GHz        | 34        | 0.77%   |
| Intel Atom CPU C3558 @ 2.20GHz           | 32        | 0.72%   |
| AMD GX-415GA SOC with Radeon HD Graphics | 32        | 0.72%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 31        | 0.7%    |
| Intel Celeron CPU N3450 @ 1.10GHz        | 31        | 0.7%    |
| Intel Pentium CPU N3700 @ 1.60GHz        | 29        | 0.66%   |
| Intel Atom CPU E3845 @ 1.91GHz           | 29        | 0.66%   |
| Intel Celeron CPU N3150 @ 1.60GHz        | 28        | 0.63%   |
| Intel Xeon CPU D-1518 @ 2.20GHz          | 27        | 0.61%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 25        | 0.57%   |
| Intel Celeron N4100 CPU @ 1.10GHz        | 25        | 0.57%   |
| Intel Celeron CPU J1800 @ 2.41GHz        | 25        | 0.57%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz | 24        | 0.54%   |
| Intel Atom CPU C2558 @ 2.40GHz           | 23        | 0.52%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz      | 22        | 0.5%    |
| Intel Core i5-2400 CPU @ 3.10GHz         | 21        | 0.48%   |
| Intel Core i3-4160 CPU @ 3.60GHz         | 21        | 0.48%   |
| Intel Celeron CPU N3160 @ 1.60GHz        | 21        | 0.48%   |
| AMD G-T40E Processor                     | 21        | 0.48%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 20        | 0.45%   |
| Intel Core i7-3770 CPU @ 3.40GHz         | 20        | 0.45%   |
| Intel Celeron J4115 CPU @ 1.80GHz        | 20        | 0.45%   |
| AMD Ryzen Embedded V1500B                | 20        | 0.45%   |
| Intel Xeon CPU E31220 @ 3.10GHz          | 19        | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Celeron           | 1018      | 23.14%  |
| Intel Core i5           | 728       | 16.55%  |
| Intel Xeon              | 558       | 12.68%  |
| Intel Core i3           | 402       | 9.14%   |
| AMD GX                  | 342       | 7.77%   |
| Intel Atom              | 313       | 7.12%   |
| Intel Core i7           | 261       | 5.93%   |
| Intel Pentium           | 140       | 3.18%   |
| Other                   | 92        | 2.09%   |
| AMD Ryzen 5             | 44        | 1%      |
| AMD G                   | 44        | 1%      |
| Intel Core 2 Duo        | 43        | 0.98%   |
| Intel Pentium Silver    | 40        | 0.91%   |
| AMD EPYC                | 34        | 0.77%   |
| Intel Core 2 Quad       | 31        | 0.7%    |
| AMD Ryzen Embedded      | 28        | 0.64%   |
| Intel Pentium Dual-Core | 27        | 0.61%   |
| AMD Ryzen 7             | 25        | 0.57%   |
| AMD FX                  | 24        | 0.55%   |
| Intel Pentium Gold      | 20        | 0.45%   |
| AMD Athlon              | 20        | 0.45%   |
| AMD Ryzen 3             | 13        | 0.3%    |
| AMD A4                  | 11        | 0.25%   |
| Intel Pentium Dual      | 10        | 0.23%   |
| AMD Ryzen 5 PRO         | 10        | 0.23%   |
| Intel Xeon Silver       | 9         | 0.2%    |
| ARM Cortex              | 9         | 0.2%    |
| Intel Core 2            | 7         | 0.16%   |
| AMD Opteron             | 7         | 0.16%   |
| AMD E                   | 7         | 0.16%   |
| AMD A10                 | 7         | 0.16%   |
| Intel Genuine           | 6         | 0.14%   |
| AMD A8                  | 6         | 0.14%   |
| Intel Xeon Gold         | 5         | 0.11%   |
| Intel Pentium 4         | 5         | 0.11%   |
| AMD Athlon 64 X2        | 5         | 0.11%   |
| Intel Core i9           | 4         | 0.09%   |
| AMD Turion II Neo       | 4         | 0.09%   |
| AMD A6                  | 4         | 0.09%   |
| AMD Ryzen 9             | 3         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 2510      | 57.06%  |
| 2       | 1276      | 29.01%  |
| 8       | 211       | 4.8%    |
| 6       | 140       | 3.18%   |
| 12      | 79        | 1.8%    |
| Unknown | 66        | 1.5%    |
| 16      | 48        | 1.09%   |
| 1       | 34        | 0.77%   |
| 10      | 10        | 0.23%   |
| 24      | 5         | 0.11%   |
| 20      | 5         | 0.11%   |
| 64      | 4         | 0.09%   |
| 32      | 3         | 0.07%   |
| 36      | 2         | 0.05%   |
| 28      | 2         | 0.05%   |
| 3       | 2         | 0.05%   |
| 128     | 1         | 0.02%   |
| 40      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 4219      | 96.72%  |
| 2       | 129       | 2.96%   |
| Unknown | 10        | 0.23%   |
| 4       | 4         | 0.09%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2865      | 65.41%  |
| 2       | 1447      | 33.04%  |
| Unknown | 67        | 1.53%   |
| 4       | 1         | 0.02%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Silvermont    | 588       | 13.36%  |
| Haswell       | 522       | 11.86%  |
| KabyLake      | 520       | 11.82%  |
| Goldmont plus | 288       | 6.55%   |
| IvyBridge     | 283       | 6.43%   |
| Puma          | 250       | 5.68%   |
| Skylake       | 242       | 5.5%    |
| SandyBridge   | 235       | 5.34%   |
| Goldmont      | 208       | 4.73%   |
| Broadwell     | 144       | 3.27%   |
| Unknown       | 133       | 3.02%   |
| Jaguar        | 118       | 2.68%   |
| Penryn        | 108       | 2.45%   |
| Bonnell       | 98        | 2.23%   |
| Westmere      | 88        | 2%      |
| Zen           | 78        | 1.77%   |
| Core          | 68        | 1.55%   |
| Nehalem       | 65        | 1.48%   |
| CometLake     | 57        | 1.3%    |
| Bobcat        | 55        | 1.25%   |
| Steamroller   | 47        | 1.07%   |
| Zen+          | 38        | 0.86%   |
| Piledriver    | 31        | 0.7%    |
| Zen 2         | 30        | 0.68%   |
| Zen 3         | 24        | 0.55%   |
| K10           | 15        | 0.34%   |
| TigerLake     | 14        | 0.32%   |
| Excavator     | 13        | 0.3%    |
| IceLake       | 12        | 0.27%   |
| NetBurst      | 10        | 0.23%   |
| K8 Hammer     | 10        | 0.23%   |
| Bulldozer     | 5         | 0.11%   |
| K10 Llano     | 3         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2822      | 70.22%  |
| AMD                                          | 428       | 10.65%  |
| ASPEED Technology                            | 319       | 7.94%   |
| Matrox Electronics Systems                   | 316       | 7.86%   |
| Nvidia                                       | 120       | 2.99%   |
| XGI Technology (eXtreme Graphics Innovation) | 5         | 0.12%   |
| VIA Technologies                             | 2         | 0.05%   |
| Silicon Motion                               | 2         | 0.05%   |
| Cirrus Logic                                 | 2         | 0.05%   |
| Tseng Labs                                   | 1         | 0.02%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.02%   |
| S3 Graphics                                  | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                                 | 319       | 7.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 266       | 6.56%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 259       | 6.38%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 247       | 6.09%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 229       | 5.64%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 147       | 3.62%   |
| Intel HD Graphics 500                                                                    | 136       | 3.35%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 132       | 3.25%   |
| Intel HD Graphics 620                                                                    | 121       | 2.98%   |
| Intel HD Graphics 530                                                                    | 116       | 2.86%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 112       | 2.76%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 88        | 2.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 86        | 2.12%   |
| Intel JasperLake [UHD Graphics]                                                          | 81        | 2%      |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 78        | 1.92%   |
| Matrox Electronics Systems G200eR2                                                       | 67        | 1.65%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 67        | 1.65%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 60        | 1.48%   |
| Intel UHD Graphics 620                                                                   | 58        | 1.43%   |
| Intel HD Graphics 630                                                                    | 55        | 1.36%   |
| Intel HD Graphics 610                                                                    | 51        | 1.26%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 47        | 1.16%   |
| AMD Kabini [Radeon HD 8400E]                                                             | 47        | 1.16%   |
| AMD ES1000                                                                               | 47        | 1.16%   |
| Intel HD Graphics 5500                                                                   | 46        | 1.13%   |
| Matrox Electronics Systems MGA G200EH                                                    | 44        | 1.08%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 40        | 0.99%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 38        | 0.94%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 37        | 0.91%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 35        | 0.86%   |
| AMD Kabini [Radeon HD 8330E]                                                             | 32        | 0.79%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 31        | 0.76%   |
| Intel HD Graphics 510                                                                    | 29        | 0.71%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 29        | 0.71%   |
| Intel HD Graphics 6000                                                                   | 28        | 0.69%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 28        | 0.69%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 26        | 0.64%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 25        | 0.62%   |
| Intel Core Processor Integrated Graphics Controller                                      | 21        | 0.52%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 21        | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| 1 x Intel              | 2681      | 61.17%  |
| 1 x AMD                | 417       | 9.51%   |
| Other                  | 405       | 9.24%   |
| 1 x Matrox             | 313       | 7.14%   |
| 1 x ASPEED             | 301       | 6.87%   |
| 2 x Intel              | 106       | 2.42%   |
| 1 x Nvidia             | 106       | 2.42%   |
| Intel + ASPEED         | 16        | 0.37%   |
| Intel + Nvidia         | 9         | 0.21%   |
| Intel + AMD            | 7         | 0.16%   |
| 1 x XGI                | 5         | 0.11%   |
| 2 x AMD                | 3         | 0.07%   |
| 1 x VIA                | 2         | 0.05%   |
| 1 x Silicon Motion     | 2         | 0.05%   |
| 1 x Cirrus Logic       | 2         | 0.05%   |
| 2 x Intel + 1 x Nvidia | 1         | 0.02%   |
| 1 x Tseng Labs         | 1         | 0.02%   |
| 1 x SiS                | 1         | 0.02%   |
| 1 x S3 Graphics        | 1         | 0.02%   |
| Nvidia + Matrox        | 1         | 0.02%   |
| Nvidia + ASPEED        | 1         | 0.02%   |
| Intel + Matrox         | 1         | 0.02%   |
| AMD + ASPEED           | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 3963      | 90.77%  |
| Unknown | 403       | 9.23%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 4359      | 99.98%  |
| 1.01-2.0   | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

Zero info for selected period =(

Monitor Model
-------------

Monitor models

Zero info for selected period =(

Monitor Resolution
------------------

Monitor screen resolution

Zero info for selected period =(

Monitor Diagonal
----------------

Diagonal size in inches

Zero info for selected period =(

Monitor Width
-------------

Physical width

Zero info for selected period =(

Aspect Ratio
------------

Proportional relationship between the width and the height

Zero info for selected period =(

Monitor Area
------------

Area in inch²

Zero info for selected period =(

Pixel Density
-------------

Pixels per inch

Zero info for selected period =(

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 4359      | 99.98%  |
| 1     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 3656      | 59.13%  |
| Realtek Semiconductor           | 1407      | 22.76%  |
| Broadcom                        | 431       | 6.97%   |
| Qualcomm Atheros                | 221       | 3.57%   |
| IMC Networks                    | 50        | 0.81%   |
| AMD                             | 45        | 0.73%   |
| Mellanox Technologies           | 38        | 0.61%   |
| Chelsio Communications          | 37        | 0.6%    |
| Ralink Technology               | 29        | 0.47%   |
| D-Link System                   | 19        | 0.31%   |
| Marvell Technology Group        | 17        | 0.27%   |
| U-Blox                          | 15        | 0.24%   |
| TP-Link                         | 14        | 0.23%   |
| Solarflare Communications       | 12        | 0.19%   |
| Ralink                          | 11        | 0.18%   |
| QLogic                          | 11        | 0.18%   |
| American Megatrends             | 11        | 0.18%   |
| Emulex                          | 9         | 0.15%   |
| Aquantia                        | 9         | 0.15%   |
| ZTE WCDMA Technologies MSM      | 8         | 0.13%   |
| Seeed Technology                | 7         | 0.11%   |
| MediaTek                        | 7         | 0.11%   |
| IBM                             | 7         | 0.11%   |
| Huawei Technologies             | 7         | 0.11%   |
| ICS Advent                      | 6         | 0.1%    |
| Edimax Technology               | 6         | 0.1%    |
| ASUSTek Computer                | 6         | 0.1%    |
| Apple                           | 6         | 0.1%    |
| VIA Technologies                | 5         | 0.08%   |
| Novatel Wireless                | 5         | 0.08%   |
| 3Com                            | 5         | 0.08%   |
| Qualcomm Atheros Communications | 4         | 0.06%   |
| NetXen Incorporated             | 4         | 0.06%   |
| Dell                            | 4         | 0.06%   |
| Samsung Electronics             | 3         | 0.05%   |
| Insyde Software                 | 3         | 0.05%   |
| Xiaomi                          | 2         | 0.03%   |
| SysKonnect                      | 2         | 0.03%   |
| Silicom                         | 2         | 0.03%   |
| Nvidia                          | 2         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 1247      | 16.2%   |
| Intel I211 Gigabit Network Connection                                         | 867       | 11.26%  |
| Intel I210 Gigabit Network Connection                                         | 582       | 7.56%   |
| Intel I350 Gigabit Network Connection                                         | 386       | 5.01%   |
| Intel 82574L Gigabit Network Connection                                       | 285       | 3.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 188       | 2.44%   |
| Intel 82583V Gigabit Network Connection                                       | 176       | 2.29%   |
| Intel Ethernet Controller I225-V                                              | 157       | 2.04%   |
| Intel 82576 Gigabit Network Connection                                        | 154       | 2%      |
| Intel 82580 Gigabit Network Connection                                        | 149       | 1.94%   |
| Intel Ethernet Connection I217-LM                                             | 135       | 1.75%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 132       | 1.71%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 107       | 1.39%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 104       | 1.35%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 101       | 1.31%   |
| Realtek RTL8125 2.5GbE Controller                                             | 91        | 1.18%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 81        | 1.05%   |
| Intel Wireless 3165                                                           | 75        | 0.97%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 73        | 0.95%   |
| Intel Ethernet Connection I354                                                | 69        | 0.9%    |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 57        | 0.74%   |
| Intel Ethernet Connection (2) I219-LM                                         | 55        | 0.71%   |
| Intel Ethernet Connection X553 1GbE                                           | 52        | 0.68%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                          | 50        | 0.65%   |
| Intel Wi-Fi 6 AX200                                                           | 46        | 0.6%    |
| Intel Gemini Lake PCH CNVi WiFi                                               | 44        | 0.57%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0                     | 44        | 0.57%   |
| Intel Ethernet Connection (2) I219-V                                          | 43        | 0.56%   |
| Intel Wireless 7265                                                           | 40        | 0.52%   |
| Intel Ethernet Controller I226-V                                              | 39        | 0.51%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 38        | 0.49%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 37        | 0.48%   |
| Intel Ethernet Controller X550                                                | 36        | 0.47%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 35        | 0.45%   |
| Intel Wireless 3160                                                           | 33        | 0.43%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 33        | 0.43%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 32        | 0.42%   |
| Intel Ethernet Connection X552 10 GbE SFP+                                    | 31        | 0.4%    |
| Intel Ethernet Connection I217-V                                              | 31        | 0.4%    |
| Intel Wireless 7260                                                           | 30        | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 424       | 47.16%  |
| Qualcomm Atheros                | 182       | 20.24%  |
| Realtek Semiconductor           | 99        | 11.01%  |
| Broadcom                        | 55        | 6.12%   |
| IMC Networks                    | 50        | 5.56%   |
| Ralink Technology               | 29        | 3.23%   |
| TP-Link                         | 14        | 1.56%   |
| Ralink                          | 11        | 1.22%   |
| MediaTek                        | 7         | 0.78%   |
| Edimax Technology               | 6         | 0.67%   |
| ASUSTek Computer                | 6         | 0.67%   |
| Qualcomm Atheros Communications | 4         | 0.44%   |
| NetGear                         | 2         | 0.22%   |
| ZyXEL Communications            | 1         | 0.11%   |
| Sitecom Europe                  | 1         | 0.11%   |
| Sierra Wireless                 | 1         | 0.11%   |
| Mercucys                        | 1         | 0.11%   |
| Marvell Technology Group        | 1         | 0.11%   |
| Gemtek                          | 1         | 0.11%   |
| Dell                            | 1         | 0.11%   |
| D-Link                          | 1         | 0.11%   |
| Belkin Components               | 1         | 0.11%   |
| Accton Technology               | 1         | 0.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Intel Wireless 3165                                             | 75        | 8.27%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card            | 50        | 5.51%   |
| Intel Wi-Fi 6 AX200                                             | 46        | 5.07%   |
| Intel Gemini Lake PCH CNVi WiFi                                 | 44        | 4.85%   |
| Intel Wireless 7265                                             | 40        | 4.41%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)  | 38        | 4.19%   |
| Intel Wireless 3160                                             | 33        | 3.64%   |
| Intel Wireless 7260                                             | 30        | 3.31%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter      | 27        | 2.98%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 22        | 2.43%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                | 20        | 2.21%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter | 18        | 1.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                | 18        | 1.98%   |
| Intel Wireless 8260                                             | 17        | 1.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 16        | 1.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)  | 16        | 1.76%   |
| Intel Wireless 8265 / 8275                                      | 16        | 1.76%   |
| Broadcom BCM43228 802.11a/b/g/n                                 | 15        | 1.65%   |
| Ralink RT5370 Wireless Adapter                                  | 14        | 1.54%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter             | 11        | 1.21%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                          | 11        | 1.21%   |
| Intel Centrino Advanced-N 6235                                  | 11        | 1.21%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                        | 11        | 1.21%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter        | 10        | 1.1%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter      | 10        | 1.1%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                | 10        | 1.1%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)  | 9         | 0.99%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                    | 9         | 0.99%   |
| Intel Wireless-AC 9260                                          | 8         | 0.88%   |
| Broadcom BCM4331 802.11a/b/g/n                                  | 8         | 0.88%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter             | 8         | 0.88%   |
| Realtek RTL8188EE Wireless Network Adapter                      | 7         | 0.77%   |
| Intel Comet Lake PCH-LP CNVi WiFi                               | 7         | 0.77%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter              | 7         | 0.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter        | 6         | 0.66%   |
| Ralink RT5572 Wireless Adapter                                  | 6         | 0.66%   |
| Intel WiFi Link 5100                                            | 6         | 0.66%   |
| Broadcom BCM43224 802.11a/b/g/n                                 | 6         | 0.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                 | 5         | 0.55%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                          | 5         | 0.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 3423      | 63.05%  |
| Realtek Semiconductor       | 1355      | 24.96%  |
| Broadcom                    | 390       | 7.18%   |
| AMD                         | 45        | 0.83%   |
| Qualcomm Atheros            | 42        | 0.77%   |
| Chelsio Communications      | 26        | 0.48%   |
| D-Link System               | 17        | 0.31%   |
| Marvell Technology Group    | 16        | 0.29%   |
| Solarflare Communications   | 12        | 0.22%   |
| QLogic                      | 11        | 0.2%    |
| American Megatrends         | 11        | 0.2%    |
| Aquantia                    | 9         | 0.17%   |
| Emulex                      | 8         | 0.15%   |
| IBM                         | 7         | 0.13%   |
| ICS Advent                  | 6         | 0.11%   |
| Apple                       | 6         | 0.11%   |
| VIA Technologies            | 5         | 0.09%   |
| Novatel Wireless            | 5         | 0.09%   |
| 3Com                        | 5         | 0.09%   |
| Samsung Electronics         | 3         | 0.06%   |
| Insyde Software             | 3         | 0.06%   |
| Xiaomi                      | 2         | 0.04%   |
| SysKonnect                  | 2         | 0.04%   |
| Silicom                     | 2         | 0.04%   |
| Nvidia                      | 2         | 0.04%   |
| Microsoft                   | 2         | 0.04%   |
| Digital Equipment           | 2         | 0.04%   |
| ZTE WCDMA Technologies MSM  | 1         | 0.02%   |
| Tehuti Networks             | 1         | 0.02%   |
| T & A Mobile Phones         | 1         | 0.02%   |
| Standard Microsystems [SMC] | 1         | 0.02%   |
| Realtek                     | 1         | 0.02%   |
| QNAP System                 | 1         | 0.02%   |
| Netchip Technology          | 1         | 0.02%   |
| National Semiconductor      | 1         | 0.02%   |
| MYRICOM                     | 1         | 0.02%   |
| Google                      | 1         | 0.02%   |
| Davicom Semiconductor       | 1         | 0.02%   |
| ADMtek                      | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 1247      | 18.75%  |
| Intel I211 Gigabit Network Connection                                         | 867       | 13.04%  |
| Intel I210 Gigabit Network Connection                                         | 582       | 8.75%   |
| Intel I350 Gigabit Network Connection                                         | 386       | 5.81%   |
| Intel 82574L Gigabit Network Connection                                       | 285       | 4.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 188       | 2.83%   |
| Intel 82583V Gigabit Network Connection                                       | 176       | 2.65%   |
| Intel Ethernet Controller I225-V                                              | 157       | 2.36%   |
| Intel 82576 Gigabit Network Connection                                        | 154       | 2.32%   |
| Intel 82580 Gigabit Network Connection                                        | 149       | 2.24%   |
| Intel Ethernet Connection I217-LM                                             | 135       | 2.03%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 132       | 1.99%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 107       | 1.61%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 104       | 1.56%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 101       | 1.52%   |
| Realtek RTL8125 2.5GbE Controller                                             | 90        | 1.35%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 81        | 1.22%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 73        | 1.1%    |
| Intel Ethernet Connection I354                                                | 69        | 1.04%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 57        | 0.86%   |
| Intel Ethernet Connection (2) I219-LM                                         | 55        | 0.83%   |
| Intel Ethernet Connection X553 1GbE                                           | 52        | 0.78%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0                     | 44        | 0.66%   |
| Intel Ethernet Connection (2) I219-V                                          | 43        | 0.65%   |
| Intel Ethernet Controller I226-V                                              | 39        | 0.59%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 37        | 0.56%   |
| Intel Ethernet Controller X550                                                | 36        | 0.54%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 35        | 0.53%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 33        | 0.5%    |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 32        | 0.48%   |
| Intel Ethernet Connection X552 10 GbE SFP+                                    | 31        | 0.47%   |
| Intel Ethernet Connection I217-V                                              | 31        | 0.47%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 28        | 0.42%   |
| Intel Ethernet Connection (7) I219-LM                                         | 28        | 0.42%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 26        | 0.39%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 25        | 0.38%   |
| Intel Ethernet Connection (7) I219-V                                          | 25        | 0.38%   |
| Intel 82579V Gigabit Network Connection                                       | 24        | 0.36%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 24        | 0.36%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 23        | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 4347      | 81.27%  |
| WiFi     | 865       | 16.17%  |
| Unknown  | 101       | 1.89%   |
| Modem    | 36        | 0.67%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 4316      | 99.52%  |
| WiFi     | 20        | 0.46%   |
| Unknown  | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 4     | 1117      | 25.17%  |
| 3     | 867       | 19.54%  |
| 2     | 800       | 18.03%  |
| 6     | 627       | 14.13%  |
| 5     | 454       | 10.23%  |
| 8     | 179       | 4.03%   |
| 1     | 142       | 3.2%    |
| 7     | 99        | 2.23%   |
| 10    | 52        | 1.17%   |
| 9     | 47        | 1.06%   |
| 12    | 17        | 0.38%   |
| 14    | 10        | 0.23%   |
| 11    | 7         | 0.16%   |
| 13    | 6         | 0.14%   |
| 0     | 6         | 0.14%   |
| 16    | 3         | 0.07%   |
| 15    | 3         | 0.07%   |
| 20    | 2         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3641      | 80.11%  |
| Yes  | 904       | 19.89%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 319       | 67.44%  |
| IMC Networks                    | 50        | 10.57%  |
| Qualcomm Atheros Communications | 25        | 5.29%   |
| Broadcom                        | 17        | 3.59%   |
| Apple                           | 14        | 2.96%   |
| Realtek Semiconductor           | 12        | 2.54%   |
| Cambridge Silicon Radio         | 8         | 1.69%   |
| Foxconn / Hon Hai               | 6         | 1.27%   |
| MediaTek                        | 5         | 1.06%   |
| Lite-On Technology              | 5         | 1.06%   |
| ASUSTek Computer                | 5         | 1.06%   |
| Dell                            | 4         | 0.85%   |
| Qcom                            | 1         | 0.21%   |
| Hewlett-Packard                 | 1         | 0.21%   |
| Dynex                           | 1         | 0.21%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                         | 140       | 29.6%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)             | 61        | 12.9%   |
| Intel AX200 Bluetooth                                      | 46        | 9.73%   |
| Intel Wireless-AC 3168 Bluetooth                           | 22        | 4.65%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                | 20        | 4.23%   |
| Intel Centrino Bluetooth Wireless Transceiver              | 19        | 4.02%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip       | 12        | 2.54%   |
| Apple Bluetooth Host Controller                            | 12        | 2.54%   |
| Intel AX201 Bluetooth                                      | 11        | 2.33%   |
| Intel AX210 Bluetooth                                      | 10        | 2.11%   |
| IMC Networks Realtek Bluetooth Adapter                     | 9         | 1.9%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                      | 8         | 1.69%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)        | 8         | 1.69%   |
| Realtek  Bluetooth 4.2 Adapter                             | 7         | 1.48%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                   | 7         | 1.48%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                     | 5         | 1.06%   |
| MediaTek Wireless_Device                                   | 5         | 1.06%   |
| IMC Networks Bluetooth Radio                               | 5         | 1.06%   |
| Qualcomm Atheros AR9462 Bluetooth                          | 3         | 0.63%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)            | 3         | 0.63%   |
| Intel Intel Wireless Bluetooth                             | 3         | 0.63%   |
| Foxconn / Hon Hai Bluetooth USB Module                     | 3         | 0.63%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                 | 3         | 0.63%   |
| Broadcom BCM2045B (BDC-2.1)                                | 3         | 0.63%   |
| Realtek RTL8821A Bluetooth                                 | 2         | 0.42%   |
| Realtek RTL8723A Bluetooth                                 | 2         | 0.42%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                    | 2         | 0.42%   |
| Qualcomm Atheros Atheros AR9462 Bluetooth 3.0 + HS Adapter | 2         | 0.42%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                 | 2         | 0.42%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                | 2         | 0.42%   |
| Broadcom HP Bluethunder                                    | 2         | 0.42%   |
| Broadcom Broadcom 20702 Bluetooth 4.0 Adapter              | 2         | 0.42%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE      | 2         | 0.42%   |
| ASUS Bluetooth Controller                                  | 2         | 0.42%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                    | 1         | 0.21%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE        | 1         | 0.21%   |
| Qualcomm Atheros AR3012 Bluetooth                          | 1         | 0.21%   |
| Qcom Broadcom BCM2070 Bluetooth 2.1+EDR USB Device         | 1         | 0.21%   |
| Lite-On Qualcomm Atheros QCA61x4A Bluetooth 4.1            | 1         | 0.21%   |
| Lite-On Bluetooth USB Module                               | 1         | 0.21%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2343      | 80.57%  |
| AMD                                          | 453       | 15.58%  |
| Nvidia                                       | 88        | 3.03%   |
| C-Media Electronics                          | 8         | 0.28%   |
| Zoran Co. Personal Media Division (Nogatech) | 5         | 0.17%   |
| KTMicro                                      | 3         | 0.1%    |
| VIA Technologies                             | 2         | 0.07%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.03%   |
| Logitech                                     | 1         | 0.03%   |
| GN Netcom                                    | 1         | 0.03%   |
| Giga-Byte Technology                         | 1         | 0.03%   |
| Genesys Logic                                | 1         | 0.03%   |
| ESS Technology                               | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 283       | 8.01%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 255       | 7.22%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 234       | 6.62%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 221       | 6.26%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 179       | 5.07%   |
| AMD FCH Azalia Controller                                                                         | 166       | 4.7%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 163       | 4.61%   |
| AMD Kabini HDMI/DP Audio                                                                          | 139       | 3.93%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 135       | 3.82%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 131       | 3.71%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 122       | 3.45%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 109       | 3.09%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 91        | 2.58%   |
| Intel 8 Series HD Audio Controller                                                                | 89        | 2.52%   |
| Intel Jasper Lake HD Audio                                                                        | 81        | 2.29%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 75        | 2.12%   |
| Intel Broadwell-U Audio Controller                                                                | 75        | 2.12%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 75        | 2.12%   |
| Intel Cannon Lake PCH cAVS                                                                        | 70        | 1.98%   |
| Intel 200 Series PCH HD Audio                                                                     | 70        | 1.98%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 63        | 1.78%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 47        | 1.33%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 47        | 1.33%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 45        | 1.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 45        | 1.27%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 38        | 1.08%   |
| AMD Wrestler HDMI Audio                                                                           | 30        | 0.85%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 30        | 0.85%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 23        | 0.65%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 21        | 0.59%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 21        | 0.59%   |
| Intel Comet Lake PCH cAVS                                                                         | 19        | 0.54%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 19        | 0.54%   |
| Unknown                                                                                           | 18        | 0.51%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 17        | 0.48%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 17        | 0.48%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 16        | 0.45%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 15        | 0.42%   |
| Nvidia High Definition Audio Controller                                                           | 14        | 0.4%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 14        | 0.4%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Samsung Electronics        | 780       | 16.95%  |
| Unknown                    | 599       | 13.02%  |
| Kingston                   | 583       | 12.67%  |
| SK hynix                   | 569       | 12.37%  |
| Crucial                    | 446       | 9.69%   |
| Micron Technology          | 361       | 7.85%   |
| Corsair                    | 170       | 3.69%   |
| G.Skill                    | 146       | 3.17%   |
| Unknown                    | 138       | 3%      |
| Unknown (ABCD)             | 105       | 2.28%   |
| Transcend                  | 103       | 2.24%   |
| A-DATA Technology          | 60        | 1.3%    |
| Nanya Technology           | 50        | 1.09%   |
| Ramaxel Technology         | 44        | 0.96%   |
| Patriot                    | 36        | 0.78%   |
| Kimtigo                    | 32        | 0.7%    |
| Team                       | 31        | 0.67%   |
| Apacer                     | 30        | 0.65%   |
| Toshiba                    | 28        | 0.61%   |
| Hewlett-Packard            | 24        | 0.52%   |
| Elpida                     | 20        | 0.43%   |
| ATP                        | 19        | 0.41%   |
| Timetec                    | 14        | 0.3%    |
| PNY                        | 13        | 0.28%   |
| Teikon                     | 12        | 0.26%   |
| Innodisk                   | 10        | 0.22%   |
| Smart                      | 9         | 0.2%    |
| Goodram                    | 9         | 0.2%    |
| Tigo                       | 8         | 0.17%   |
| Super Talent               | 7         | 0.15%   |
| GeIL                       | 7         | 0.15%   |
| HPE                        | 6         | 0.13%   |
| Avant                      | 6         | 0.13%   |
| Smart Modular              | 5         | 0.11%   |
| Goldenmars                 | 5         | 0.11%   |
| Unknown (0x0C26)           | 4         | 0.09%   |
| Silicon Power              | 4         | 0.09%   |
| Shenzhen Jinge Information | 4         | 0.09%   |
| OCZ                        | 4         | 0.09%   |
| CSX                        | 4         | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown                                                      | 138       | 2.83%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                  | 106       | 2.18%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 104       | 2.14%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 45        | 0.92%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 36        | 0.74%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 33        | 0.68%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                    | 28        | 0.57%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s         | 25        | 0.51%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 25        | 0.51%   |
| Unknown RAM Module 8GB 1600MT/s                              | 24        | 0.49%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 23        | 0.47%   |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s          | 22        | 0.45%   |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s                   | 21        | 0.43%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 21        | 0.43%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s          | 21        | 0.43%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 21        | 0.43%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s         | 20        | 0.41%   |
| Samsung RAM M471B1G73QH0-YK0 8GB DIMM DDR3 1600MT/s          | 20        | 0.41%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s      | 20        | 0.41%   |
| Crucial RAM CT102464BF160B.C16 8GB DIMM DDR3 1600MT/s        | 20        | 0.41%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                    | 19        | 0.39%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s         | 19        | 0.39%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s          | 19        | 0.39%   |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s               | 19        | 0.39%   |
| Micron RAM 8KTF51264HZ-1G9P1 4GB SODIMM DDR3 1867MT/s        | 17        | 0.35%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s          | 17        | 0.35%   |
| Crucial RAM CT102464BF160B.M16 8GB DIMM DDR3 1600MT/s        | 17        | 0.35%   |
| Unknown RAM Module 2GB DIMM SDRAM                            | 16        | 0.33%   |
| Samsung RAM M471B5173QH0-YK0 4GB DIMM DDR3 1600MT/s          | 16        | 0.33%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s                   | 15        | 0.31%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 15        | 0.31%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                    | 15        | 0.31%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s          | 15        | 0.31%   |
| Kingston RAM 99U5469-045.A00LF 4GB DIMM DDR3 1600MT/s        | 15        | 0.31%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s      | 15        | 0.31%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                    | 14        | 0.29%   |
| Unknown RAM Module 1GB DIMM SDRAM                            | 13        | 0.27%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 13        | 0.27%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                  | 12        | 0.25%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                     | 12        | 0.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind            | Computers | Percent |
|-----------------|-----------|---------|
| DDR3            | 2291      | 55.32%  |
| DDR4            | 1395      | 33.69%  |
| DDR2            | 160       | 3.86%   |
| LPDDR4          | 127       | 3.07%   |
| Unknown         | 107       | 2.58%   |
| SDRAM           | 41        | 0.99%   |
| DDR             | 13        | 0.31%   |
| RAM             | 2         | 0.05%   |
| LPDDR3          | 2         | 0.05%   |
| DRAM            | 2         | 0.05%   |
| Logical non-vol | 1         | 0.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 2423      | 58.8%   |
| SODIMM       | 1602      | 38.87%  |
| Unknown      | 53        | 1.29%   |
| Row Of Chips | 18        | 0.44%   |
| FB-DIMM      | 14        | 0.34%   |
| Chip         | 7         | 0.17%   |
| RIMM         | 4         | 0.1%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 4096   | 1577      | 36.22%  |
| 8192   | 1573      | 36.13%  |
| 2048   | 542       | 12.45%  |
| 16384  | 501       | 11.51%  |
| 1024   | 93        | 2.14%   |
| 32768  | 52        | 1.19%   |
| 512    | 8         | 0.18%   |
| 65536  | 2         | 0.05%   |
| 32767  | 2         | 0.05%   |
| 129728 | 1         | 0.02%   |
| 6144   | 1         | 0.02%   |
| 4092   | 1         | 0.02%   |
| 1556   | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 1488      | 34.13%  |
| 1333    | 711       | 16.31%  |
| 2400    | 600       | 13.76%  |
| 2667    | 382       | 8.76%   |
| 2133    | 265       | 6.08%   |
| 3200    | 194       | 4.45%   |
| 800     | 125       | 2.87%   |
| 667     | 124       | 2.84%   |
| 2666    | 73        | 1.67%   |
| 1066    | 67        | 1.54%   |
| Unknown | 60        | 1.38%   |
| 1867    | 57        | 1.31%   |
| 1067    | 40        | 0.92%   |
| 1866    | 34        | 0.78%   |
| 1334    | 34        | 0.78%   |
| 3000    | 22        | 0.5%    |
| 2933    | 21        | 0.48%   |
| 3600    | 15        | 0.34%   |
| 400     | 10        | 0.23%   |
| 1033    | 5         | 0.11%   |
| 533     | 5         | 0.11%   |
| 65535   | 4         | 0.09%   |
| 1332    | 4         | 0.09%   |
| 1400    | 3         | 0.07%   |
| 2600    | 2         | 0.05%   |
| 1200    | 2         | 0.05%   |
| 133     | 2         | 0.05%   |
| 59392   | 1         | 0.02%   |
| 6400    | 1         | 0.02%   |
| 5354    | 1         | 0.02%   |
| 5200    | 1         | 0.02%   |
| 4000    | 1         | 0.02%   |
| 3534    | 1         | 0.02%   |
| 2134    | 1         | 0.02%   |
| 1419    | 1         | 0.02%   |
| 933     | 1         | 0.02%   |
| 333     | 1         | 0.02%   |
| 200     | 1         | 0.02%   |

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


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 12        | 27.91%  |
| Acer                          | 6         | 13.95%  |
| Suyin                         | 4         | 9.3%    |
| Realtek Semiconductor         | 3         | 6.98%   |
| Microdia                      | 3         | 6.98%   |
| Apple                         | 3         | 6.98%   |
| Sunplus Innovation Technology | 2         | 4.65%   |
| Lite-On Technology            | 2         | 4.65%   |
| Z-Star Microelectronics       | 1         | 2.33%   |
| Syntek                        | 1         | 2.33%   |
| Sonix Technology              | 1         | 2.33%   |
| Silicon Motion                | 1         | 2.33%   |
| Logitech                      | 1         | 2.33%   |
| Lenovo                        | 1         | 2.33%   |
| IMC Networks                  | 1         | 2.33%   |
| ALi                           | 1         | 2.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 4         | 9.3%    |
| Apple FaceTime HD Camera                 | 3         | 6.98%   |
| Acer Integrated Camera                   | 3         | 6.98%   |
| Realtek Integrated_Webcam_HD             | 2         | 4.65%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 2         | 4.65%   |
| Chicony HP HD Webcam [Fixed]             | 2         | 4.65%   |
| Acer Lenovo EasyCamera                   | 2         | 4.65%   |
| Z-Star WebCam SC-03FFL11739P             | 1         | 2.33%   |
| Syntek EasyCamera                        | 1         | 2.33%   |
| Suyin UVC 1.3MPixel WebCam               | 1         | 2.33%   |
| Suyin HP Webcam                          | 1         | 2.33%   |
| Suyin HD WebCam                          | 1         | 2.33%   |
| Suyin Acer/Lenovo Webcam [CN0316]        | 1         | 2.33%   |
| Sunplus Laptop_Integrated_Webcam_HD      | 1         | 2.33%   |
| Sunplus Laptop_Integrated_Webcam_1.3M    | 1         | 2.33%   |
| Sonix USB 2.0 Camera                     | 1         | 2.33%   |
| Silicon Motion WebCam SCB-0385N          | 1         | 2.33%   |
| Realtek Integrated Webcam HD             | 1         | 2.33%   |
| Microdia Laptop_Integrated_Webcam_HD     | 1         | 2.33%   |
| Microdia Laptop_Integrated_Webcam_0.3M   | 1         | 2.33%   |
| Microdia 1.3 MPixel Integrated Webcam    | 1         | 2.33%   |
| Logitech HD Pro Webcam C920              | 1         | 2.33%   |
| Lite-On Integrated Camera                | 1         | 2.33%   |
| Lite-On HP HD Webcam [Fixed]             | 1         | 2.33%   |
| Lenovo Integrated Camera                 | 1         | 2.33%   |
| IMC Networks USB2.0 UVC 1.3M WebCam      | 1         | 2.33%   |
| Chicony Integrated Camera [ThinkPad]     | 1         | 2.33%   |
| Chicony HD WebCam (Acer)                 | 1         | 2.33%   |
| Chicony HD Webcam                        | 1         | 2.33%   |
| Chicony Camera                           | 1         | 2.33%   |
| ALi Gateway Webcam                       | 1         | 2.33%   |
| Acer Lenovo Integrated Webcam            | 1         | 2.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 9         | 64.29%  |
| Upek             | 2         | 14.29%  |
| AuthenTec        | 2         | 14.29%  |
| Broadcom         | 1         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 3         | 21.43%  |
| Validity Sensors VFS495 Fingerprint Reader                                   | 2         | 14.29%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 2         | 14.29%  |
| AuthenTec AES2550 Fingerprint Sensor                                         | 2         | 14.29%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 1         | 7.14%   |
| Validity Sensors VFS491                                                      | 1         | 7.14%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 1         | 7.14%   |
| Validity Sensors Synaptics WBDI                                              | 1         | 7.14%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 7.14%   |

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
| 1     | 1831      | 40.93%  |
| 0     | 1769      | 39.55%  |
| 2     | 561       | 12.54%  |
| 3     | 224       | 5.01%   |
| 4     | 72        | 1.61%   |
| 5     | 16        | 0.36%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 2424      | 72.84%  |
| Net/wireless             | 270       | 8.11%   |
| Bluetooth                | 270       | 8.11%   |
| Card reader              | 148       | 4.45%   |
| Net/ethernet             | 60        | 1.8%    |
| Firewire controller      | 53        | 1.59%   |
| Network                  | 51        | 1.53%   |
| Sound                    | 29        | 0.87%   |
| Fingerprint reader       | 14        | 0.42%   |
| Storage/raid             | 6         | 0.18%   |
| Storage                  | 3         | 0.09%   |

