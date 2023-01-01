BSD - Tested Hardware & Statistics (Desktops)
---------------------------------------------

A project to collect tested hardware configurations for BSD.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 8091

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| HP            | 1825                        | [f7e94decd0](https://bsd-hardware.info/?probe=f7e94decd0) | Dec 31, 2022 |
| HP            | 1825                        | [afc1259508](https://bsd-hardware.info/?probe=afc1259508) | Dec 31, 2022 |
| Dell          | 0WR7PY A03                  | [b6ec2e7e28](https://bsd-hardware.info/?probe=b6ec2e7e28) | Dec 31, 2022 |
| ASRockRack    | EPYC3101D4I-2T              | [ab7e64f657](https://bsd-hardware.info/?probe=ab7e64f657) | Dec 31, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [0bf1c2abef](https://bsd-hardware.info/?probe=0bf1c2abef) | Dec 31, 2022 |
| Lenovo        | 30D9 SDK0J40700 WIN 3258... | [ac867149f2](https://bsd-hardware.info/?probe=ac867149f2) | Dec 31, 2022 |
| Unknown       | Unknown                     | [68a847f5c2](https://bsd-hardware.info/?probe=68a847f5c2) | Dec 31, 2022 |
| Dell          | 02YYK5 A01                  | [910c2bba4a](https://bsd-hardware.info/?probe=910c2bba4a) | Dec 31, 2022 |
| ASUSTek       | PRIME A320I-K               | [334575b738](https://bsd-hardware.info/?probe=334575b738) | Dec 31, 2022 |
| GoWin Solu... | R86S                        | [4243d313a1](https://bsd-hardware.info/?probe=4243d313a1) | Dec 31, 2022 |
| Fujitsu       | D3313-S3 S26361-D3313-S3    | [b89a55c4aa](https://bsd-hardware.info/?probe=b89a55c4aa) | Dec 30, 2022 |
| OEM           | 1.0                         | [f2aeb0ea02](https://bsd-hardware.info/?probe=f2aeb0ea02) | Dec 30, 2022 |
| CncTion       | N5105-4L B0                 | [cd3e4f7122](https://bsd-hardware.info/?probe=cd3e4f7122) | Dec 30, 2022 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | [a8ece272af](https://bsd-hardware.info/?probe=a8ece272af) | Dec 30, 2022 |
| Protectli     | FW4B                        | [406fe72c22](https://bsd-hardware.info/?probe=406fe72c22) | Dec 30, 2022 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [4d9a4bfc40](https://bsd-hardware.info/?probe=4d9a4bfc40) | Dec 30, 2022 |
| Protectli     | FW6                         | [0d62222b7a](https://bsd-hardware.info/?probe=0d62222b7a) | Dec 30, 2022 |
| Shuttle       | FH110                       | [3759d77a05](https://bsd-hardware.info/?probe=3759d77a05) | Dec 29, 2022 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [e23f822438](https://bsd-hardware.info/?probe=e23f822438) | Dec 29, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [d22c37fa81](https://bsd-hardware.info/?probe=d22c37fa81) | Dec 29, 2022 |
| Unknown       | Unknown                     | [0f727c761b](https://bsd-hardware.info/?probe=0f727c761b) | Dec 29, 2022 |
| Gigabyte      | MBHM87P-00                  | [5d287163c9](https://bsd-hardware.info/?probe=5d287163c9) | Dec 29, 2022 |
| Dell          | 0GN4PW A00                  | [77e235d9f8](https://bsd-hardware.info/?probe=77e235d9f8) | Dec 29, 2022 |
| Advantech     | UNO-2483G-474AE             | [d453f64b4f](https://bsd-hardware.info/?probe=d453f64b4f) | Dec 29, 2022 |
| HP            | 8000 X4                     | [e66d228381](https://bsd-hardware.info/?probe=e66d228381) | Dec 29, 2022 |
| PC Engines    | APU2                        | [7aaf2d91ba](https://bsd-hardware.info/?probe=7aaf2d91ba) | Dec 29, 2022 |
| Lanner        | FW-7543 B-GA                | [6c145361a3](https://bsd-hardware.info/?probe=6c145361a3) | Dec 29, 2022 |
| Unknown       | Unknown                     | [1dab2c420a](https://bsd-hardware.info/?probe=1dab2c420a) | Dec 28, 2022 |
| Intel         | DENLOW_REFRESH_WS           | [4f86e686d2](https://bsd-hardware.info/?probe=4f86e686d2) | Dec 28, 2022 |
| MSI           | H270 GAMING M3              | [5d14519e73](https://bsd-hardware.info/?probe=5d14519e73) | Dec 28, 2022 |
| MSI           | H270 GAMING M3              | [5dcdab1ee3](https://bsd-hardware.info/?probe=5dcdab1ee3) | Dec 28, 2022 |
| Hardkernel    | ODROID-H2                   | [b685ddc2ad](https://bsd-hardware.info/?probe=b685ddc2ad) | Dec 28, 2022 |
| PC Engines    | APU2                        | [85da0654e1](https://bsd-hardware.info/?probe=85da0654e1) | Dec 28, 2022 |
| Intel         | CARLOW                      | [fa30f060f3](https://bsd-hardware.info/?probe=fa30f060f3) | Dec 28, 2022 |
| ASUSTek       | P11C-M Series               | [21f838983b](https://bsd-hardware.info/?probe=21f838983b) | Dec 28, 2022 |
| Unknown       | Unknown                     | [5b8ad02694](https://bsd-hardware.info/?probe=5b8ad02694) | Dec 28, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [5dafbbced0](https://bsd-hardware.info/?probe=5dafbbced0) | Dec 28, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B      | [888de76acd](https://bsd-hardware.info/?probe=888de76acd) | Dec 28, 2022 |
| Unknown       | Unknown                     | [e70af54c3f](https://bsd-hardware.info/?probe=e70af54c3f) | Dec 28, 2022 |
| HP            | 1998                        | [afc7de60e3](https://bsd-hardware.info/?probe=afc7de60e3) | Dec 28, 2022 |
| Unknown       | Unknown                     | [c3b95220d7](https://bsd-hardware.info/?probe=c3b95220d7) | Dec 28, 2022 |
| Shuttle       | FH110                       | [be457c2796](https://bsd-hardware.info/?probe=be457c2796) | Dec 27, 2022 |
| MW            | GMLK-2_5G4L                 | [8d3ab2cab5](https://bsd-hardware.info/?probe=8d3ab2cab5) | Dec 27, 2022 |
| Gigabyte      | J4005ND2P-CF                | [4bcc34fdca](https://bsd-hardware.info/?probe=4bcc34fdca) | Dec 27, 2022 |
| Intel         | D2500HN AAG81480-500        | [dae5627541](https://bsd-hardware.info/?probe=dae5627541) | Dec 27, 2022 |
| Techvision    | TVI7309X B0                 | [3bdb5aa361](https://bsd-hardware.info/?probe=3bdb5aa361) | Dec 27, 2022 |
| Protectli     | FW6 Ver                     | [41094c24b2](https://bsd-hardware.info/?probe=41094c24b2) | Dec 27, 2022 |
| HP            | ProLiant MicroServer        | [50c8cb79f7](https://bsd-hardware.info/?probe=50c8cb79f7) | Dec 26, 2022 |
| Dell          | 0WMJ54 A01                  | [d4296fd9d8](https://bsd-hardware.info/?probe=d4296fd9d8) | Dec 26, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [2265227a5c](https://bsd-hardware.info/?probe=2265227a5c) | Dec 26, 2022 |
| Unknown       | Unknown                     | [39bce6117f](https://bsd-hardware.info/?probe=39bce6117f) | Dec 26, 2022 |
| Dell          | 051FJ8 A01                  | [7f66a21d24](https://bsd-hardware.info/?probe=7f66a21d24) | Dec 26, 2022 |
| Unknown       | Unknown                     | [e52abbf1b8](https://bsd-hardware.info/?probe=e52abbf1b8) | Dec 26, 2022 |
| Protectli     | FW6 Ver                     | [d62deb9883](https://bsd-hardware.info/?probe=d62deb9883) | Dec 26, 2022 |
| Protectli     | FW6                         | [90758fca97](https://bsd-hardware.info/?probe=90758fca97) | Dec 26, 2022 |
| ASUSTek       | H97-PLUS                    | [f2a248dcfe](https://bsd-hardware.info/?probe=f2a248dcfe) | Dec 26, 2022 |
| Unknown       | Unknown                     | [b4d44b0018](https://bsd-hardware.info/?probe=b4d44b0018) | Dec 26, 2022 |
| ASUSTek       | P5Q-E                       | [bc829dbb1a](https://bsd-hardware.info/?probe=bc829dbb1a) | Dec 25, 2022 |
| MSI           | H81M-P33                    | [f73a37ab81](https://bsd-hardware.info/?probe=f73a37ab81) | Dec 25, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [2e842ddb27](https://bsd-hardware.info/?probe=2e842ddb27) | Dec 25, 2022 |
| Cisco         | ASA5515 A0                  | [9e587b9499](https://bsd-hardware.info/?probe=9e587b9499) | Dec 25, 2022 |
| Shuttle       | FH110                       | [a194756b95](https://bsd-hardware.info/?probe=a194756b95) | Dec 25, 2022 |
| Gigabyte      | X399 AORUS Gaming 7         | [1769da5143](https://bsd-hardware.info/?probe=1769da5143) | Dec 25, 2022 |
| HP            | 8062                        | [f4d3eb024d](https://bsd-hardware.info/?probe=f4d3eb024d) | Dec 25, 2022 |
| HP            | 213D A01                    | [bd620f0fc0](https://bsd-hardware.info/?probe=bd620f0fc0) | Dec 25, 2022 |
| MSI           | B560M-A PRO                 | [f1cb9703a7](https://bsd-hardware.info/?probe=f1cb9703a7) | Dec 24, 2022 |
| Unknown       | Unknown                     | [bd212706ad](https://bsd-hardware.info/?probe=bd212706ad) | Dec 24, 2022 |
| Supermicro    | X10SRH-CLN4FA               | [84c360ad02](https://bsd-hardware.info/?probe=84c360ad02) | Dec 24, 2022 |
| Intel         | Q3XXG4-P V1.0               | [33c59c687d](https://bsd-hardware.info/?probe=33c59c687d) | Dec 24, 2022 |
| HP            | 8299                        | [6715ee2886](https://bsd-hardware.info/?probe=6715ee2886) | Dec 24, 2022 |
| ASUSTek       | GRYPHON Z87                 | [b29f2e4573](https://bsd-hardware.info/?probe=b29f2e4573) | Dec 24, 2022 |
| Dell          | 02YYK5 A01                  | [701c6e95d6](https://bsd-hardware.info/?probe=701c6e95d6) | Dec 24, 2022 |
| ASRock        | N3710-NUC IPC               | [80c809e992](https://bsd-hardware.info/?probe=80c809e992) | Dec 24, 2022 |
| Gigabyte      | Z390 AORUS ELITE            | [91b7417b84](https://bsd-hardware.info/?probe=91b7417b84) | Dec 24, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [4c3b92bb42](https://bsd-hardware.info/?probe=4c3b92bb42) | Dec 24, 2022 |
| Biostar       | A32M2                       | [49c31b364c](https://bsd-hardware.info/?probe=49c31b364c) | Dec 23, 2022 |
| Biostar       | A10N-8800E                  | [d3d1107f77](https://bsd-hardware.info/?probe=d3d1107f77) | Dec 23, 2022 |
| Intel         | Q3XXG4-P V1.0               | [58b47341c9](https://bsd-hardware.info/?probe=58b47341c9) | Dec 23, 2022 |
| MSI           | A78M-E35                    | [03176e6683](https://bsd-hardware.info/?probe=03176e6683) | Dec 23, 2022 |
| Dell          | 0NW6H5 A00                  | [b19a4d1696](https://bsd-hardware.info/?probe=b19a4d1696) | Dec 23, 2022 |
| ASRock        | B75M R2.0                   | [3a8d5c61b6](https://bsd-hardware.info/?probe=3a8d5c61b6) | Dec 23, 2022 |
| Intel         | Q3XXG4-P V1.0               | [7cccecfde1](https://bsd-hardware.info/?probe=7cccecfde1) | Dec 23, 2022 |
| Intel BOX4... | Geminilake                  | [a2b2b7c25f](https://bsd-hardware.info/?probe=a2b2b7c25f) | Dec 23, 2022 |
| HP            | ProLiant MicroServer Gen... | [a2bc442acd](https://bsd-hardware.info/?probe=a2bc442acd) | Dec 23, 2022 |
| Intel BOX4... | Geminilake                  | [06933f3d87](https://bsd-hardware.info/?probe=06933f3d87) | Dec 23, 2022 |
| Unknown       | QD-WHLU01                   | [a0fb185069](https://bsd-hardware.info/?probe=a0fb185069) | Dec 23, 2022 |
| MSI           | B560M-A PRO                 | [8325caa4d6](https://bsd-hardware.info/?probe=8325caa4d6) | Dec 23, 2022 |
| Unknown       | Unknown                     | [d702dfcde2](https://bsd-hardware.info/?probe=d702dfcde2) | Dec 23, 2022 |
| HP            | 8299                        | [d9eec3c9f5](https://bsd-hardware.info/?probe=d9eec3c9f5) | Dec 23, 2022 |
| Unknown       | MANIFOLD 2-C                | [bc2c536004](https://bsd-hardware.info/?probe=bc2c536004) | Dec 23, 2022 |
| HP            | ProLiant MicroServer Gen... | [daaad6a386](https://bsd-hardware.info/?probe=daaad6a386) | Dec 23, 2022 |
| HP            | ProLiant MicroServer Gen... | [67bc182d1d](https://bsd-hardware.info/?probe=67bc182d1d) | Dec 23, 2022 |
| MSI           | B560M-A PRO                 | [6f8bdb560b](https://bsd-hardware.info/?probe=6f8bdb560b) | Dec 23, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [3e5e7e3e61](https://bsd-hardware.info/?probe=3e5e7e3e61) | Dec 22, 2022 |
| Protectli     | FW4B Ver                    | [cde7bad6c3](https://bsd-hardware.info/?probe=cde7bad6c3) | Dec 22, 2022 |
| CncTion       | N5105-4L B0                 | [78bcccda01](https://bsd-hardware.info/?probe=78bcccda01) | Dec 22, 2022 |
| ASRock        | A75M-HVS                    | [01d8e43ee1](https://bsd-hardware.info/?probe=01d8e43ee1) | Dec 22, 2022 |
| Unknown       | Unknown                     | [0f03a7f2ce](https://bsd-hardware.info/?probe=0f03a7f2ce) | Dec 22, 2022 |
| AAEON         | FWS-2251 V1.0               | [a4ff0a7ec5](https://bsd-hardware.info/?probe=a4ff0a7ec5) | Dec 22, 2022 |
| Acer          | WG43M                       | [d316352c20](https://bsd-hardware.info/?probe=d316352c20) | Dec 22, 2022 |
| Supermicro    | X9DR3-F                     | [b8c89bdca8](https://bsd-hardware.info/?probe=b8c89bdca8) | Dec 22, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [2ac107df0f](https://bsd-hardware.info/?probe=2ac107df0f) | Dec 22, 2022 |
| Acer          | Veriton X2640G V:1.0        | [f241237f76](https://bsd-hardware.info/?probe=f241237f76) | Dec 22, 2022 |
| Dell          | 0WR7PY A02                  | [0c3fea5eb0](https://bsd-hardware.info/?probe=0c3fea5eb0) | Dec 22, 2022 |
| Unknown       | Unknown                     | [0a40b02aeb](https://bsd-hardware.info/?probe=0a40b02aeb) | Dec 22, 2022 |
| Intel         | SHARKBAY                    | [df221cefbc](https://bsd-hardware.info/?probe=df221cefbc) | Dec 22, 2022 |
| Supermicro    | X9DR3-F                     | [b0d1792185](https://bsd-hardware.info/?probe=b0d1792185) | Dec 21, 2022 |
| PC Engines    | APU2                        | [9781d92062](https://bsd-hardware.info/?probe=9781d92062) | Dec 21, 2022 |
| Dell          | 0KYJ8C A02                  | [490f20c93d](https://bsd-hardware.info/?probe=490f20c93d) | Dec 21, 2022 |
| PC Engines    | APU2                        | [e94b983d48](https://bsd-hardware.info/?probe=e94b983d48) | Dec 21, 2022 |
| ACMA          | X8SIE                       | [01898b2ffb](https://bsd-hardware.info/?probe=01898b2ffb) | Dec 21, 2022 |
| Dell          | 0UW457 A03                  | [47b66a0d86](https://bsd-hardware.info/?probe=47b66a0d86) | Dec 21, 2022 |
| Raspberry ... | Raspberry Pi 400            | [ee9cac334f](https://bsd-hardware.info/?probe=ee9cac334f) | Dec 21, 2022 |
| HP            | 18E7                        | [0b962b9400](https://bsd-hardware.info/?probe=0b962b9400) | Dec 20, 2022 |
| Unknown       | Unknown                     | [0bffe61dae](https://bsd-hardware.info/?probe=0bffe61dae) | Dec 20, 2022 |
| ASRock        | 4X4-4000 Series             | [009ef73bd1](https://bsd-hardware.info/?probe=009ef73bd1) | Dec 20, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [a8ec4c3ae4](https://bsd-hardware.info/?probe=a8ec4c3ae4) | Dec 20, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [4667028e67](https://bsd-hardware.info/?probe=4667028e67) | Dec 20, 2022 |
| Protectli     | FW2B Ver                    | [9596576df7](https://bsd-hardware.info/?probe=9596576df7) | Dec 20, 2022 |
| Lenovo        | 3098 SDK0E50510 PRO or W... | [e1e1a80328](https://bsd-hardware.info/?probe=e1e1a80328) | Dec 20, 2022 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | [2ea413db31](https://bsd-hardware.info/?probe=2ea413db31) | Dec 20, 2022 |
| HP            | ProLiant MicroServer Gen... | [8de4ff8626](https://bsd-hardware.info/?probe=8de4ff8626) | Dec 20, 2022 |
| ASRock        | 4X4-4000 Series             | [31f17adc5b](https://bsd-hardware.info/?probe=31f17adc5b) | Dec 20, 2022 |
| Dell          | 0WR7PY A00                  | [360336dcc1](https://bsd-hardware.info/?probe=360336dcc1) | Dec 20, 2022 |
| MSI           | MS-7922                     | [95dbf4f7a8](https://bsd-hardware.info/?probe=95dbf4f7a8) | Dec 19, 2022 |
| Unknown       | Unknown                     | [4c5ccd04d0](https://bsd-hardware.info/?probe=4c5ccd04d0) | Dec 19, 2022 |
| Dell          | 0WMJ54 A01                  | [b84941cdd5](https://bsd-hardware.info/?probe=b84941cdd5) | Dec 19, 2022 |
| Unknown       | Unknown                     | [5d37a0669c](https://bsd-hardware.info/?probe=5d37a0669c) | Dec 19, 2022 |
| Dell          | 0WR7PY A02                  | [67baacfc7d](https://bsd-hardware.info/?probe=67baacfc7d) | Dec 19, 2022 |
| Dell          | 09KPNV A01                  | [0eea35e069](https://bsd-hardware.info/?probe=0eea35e069) | Dec 19, 2022 |
| ASUSTek       | H97-PLUS                    | [c9de65beeb](https://bsd-hardware.info/?probe=c9de65beeb) | Dec 19, 2022 |
| PC Engines    | APU2                        | [5de84cb508](https://bsd-hardware.info/?probe=5de84cb508) | Dec 19, 2022 |
| Pegatron      | 2ACF                        | [511f2a6d16](https://bsd-hardware.info/?probe=511f2a6d16) | Dec 19, 2022 |
| Unknown       | Pine64 RockPro64 v2.1       | [59525051d3](https://bsd-hardware.info/?probe=59525051d3) | Dec 19, 2022 |
| Unknown       | Unknown                     | [f876d5d5b1](https://bsd-hardware.info/?probe=f876d5d5b1) | Dec 19, 2022 |
| HP            | ProLiant MicroServer        | [b730e64d4a](https://bsd-hardware.info/?probe=b730e64d4a) | Dec 19, 2022 |
| Gigabyte      | H81M-DS2                    | [29ad5ee336](https://bsd-hardware.info/?probe=29ad5ee336) | Dec 19, 2022 |
| Acer          | Veriton M680G               | [cb44a9e848](https://bsd-hardware.info/?probe=cb44a9e848) | Dec 19, 2022 |
| Acer          | Veriton M680G               | [f7184d9158](https://bsd-hardware.info/?probe=f7184d9158) | Dec 19, 2022 |
| Unknown       | Unknown                     | [3d77f833b0](https://bsd-hardware.info/?probe=3d77f833b0) | Dec 19, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [f321130f0e](https://bsd-hardware.info/?probe=f321130f0e) | Dec 18, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [14d483ac06](https://bsd-hardware.info/?probe=14d483ac06) | Dec 18, 2022 |
| ASRock        | B660M-ITX/ac                | [f6c8eb4e18](https://bsd-hardware.info/?probe=f6c8eb4e18) | Dec 18, 2022 |
| ASUSTek       | X99-DELUXE                  | [abe21b9c9e](https://bsd-hardware.info/?probe=abe21b9c9e) | Dec 18, 2022 |
| Gigabyte      | J3455N-D3H                  | [fc7928dfe9](https://bsd-hardware.info/?probe=fc7928dfe9) | Dec 18, 2022 |
| ASRock        | E3C224D2I                   | [106e525671](https://bsd-hardware.info/?probe=106e525671) | Dec 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [c1b0b83306](https://bsd-hardware.info/?probe=c1b0b83306) | Dec 18, 2022 |
| MSI           | H81M-P33                    | [78e4743abd](https://bsd-hardware.info/?probe=78e4743abd) | Dec 18, 2022 |
| ASUSTek       | P5Q-E                       | [f232e5746e](https://bsd-hardware.info/?probe=f232e5746e) | Dec 18, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | [108c9de5cc](https://bsd-hardware.info/?probe=108c9de5cc) | Dec 18, 2022 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | [1f1de1d49c](https://bsd-hardware.info/?probe=1f1de1d49c) | Dec 18, 2022 |
| ASRock        | H370M-ITX/ac                | [a40ada7f7f](https://bsd-hardware.info/?probe=a40ada7f7f) | Dec 18, 2022 |
| Unknown       | Unknown                     | [f6fababc22](https://bsd-hardware.info/?probe=f6fababc22) | Dec 18, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [a1b29c356e](https://bsd-hardware.info/?probe=a1b29c356e) | Dec 17, 2022 |
| MSI           | X299 PRO                    | [beec8001a1](https://bsd-hardware.info/?probe=beec8001a1) | Dec 17, 2022 |
| Protectli     | FW6                         | [56f62226e7](https://bsd-hardware.info/?probe=56f62226e7) | Dec 17, 2022 |
| PC Engines    | APU3                        | [5597cca988](https://bsd-hardware.info/?probe=5597cca988) | Dec 17, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [92593f4e79](https://bsd-hardware.info/?probe=92593f4e79) | Dec 17, 2022 |
| MSI           | MS-98C8                     | [a6e45c8e5f](https://bsd-hardware.info/?probe=a6e45c8e5f) | Dec 17, 2022 |
| Lenovo        | ThinkCentre M93p 10A8S0C... | [11d5b82cdd](https://bsd-hardware.info/?probe=11d5b82cdd) | Dec 17, 2022 |
| PC Engines    | APU3                        | [0e1197c771](https://bsd-hardware.info/?probe=0e1197c771) | Dec 17, 2022 |
| Unknown       | Unknown                     | [0e98358cf3](https://bsd-hardware.info/?probe=0e98358cf3) | Dec 17, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [e8095445e8](https://bsd-hardware.info/?probe=e8095445e8) | Dec 17, 2022 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | [088766f04d](https://bsd-hardware.info/?probe=088766f04d) | Dec 17, 2022 |
| Unknown       | Unknown                     | [f7700c781d](https://bsd-hardware.info/?probe=f7700c781d) | Dec 17, 2022 |
| Intel         | CRESCENTBAY                 | [7981529337](https://bsd-hardware.info/?probe=7981529337) | Dec 17, 2022 |
| PC Engines    | APU                         | [19786edc61](https://bsd-hardware.info/?probe=19786edc61) | Dec 17, 2022 |
| Dell          | 0FDY5C A00                  | [afef2952f9](https://bsd-hardware.info/?probe=afef2952f9) | Dec 17, 2022 |
| BESSTAR Te... | UM350                       | [b7e599f99d](https://bsd-hardware.info/?probe=b7e599f99d) | Dec 17, 2022 |
| CncTion       | N5105-4L B0                 | [0da9ef9752](https://bsd-hardware.info/?probe=0da9ef9752) | Dec 17, 2022 |
| AMI           | PEISIA E3845 VER1.0         | [c3ffb2c87d](https://bsd-hardware.info/?probe=c3ffb2c87d) | Dec 17, 2022 |
| Intel         | DN2820FYK H24582-203        | [160d942d28](https://bsd-hardware.info/?probe=160d942d28) | Dec 17, 2022 |
| Unknown       | Unknown                     | [a94bfdaa5c](https://bsd-hardware.info/?probe=a94bfdaa5c) | Dec 16, 2022 |
| Dell          | 02YRK5 A03                  | [547b1abce0](https://bsd-hardware.info/?probe=547b1abce0) | Dec 16, 2022 |
| MSI           | H81M-E33                    | [411bb9d111](https://bsd-hardware.info/?probe=411bb9d111) | Dec 16, 2022 |
| MSI           | MS-B1831                    | [638e327c4e](https://bsd-hardware.info/?probe=638e327c4e) | Dec 16, 2022 |
| ASUSTek       | STRIX Z270I GAMING          | [d44c580408](https://bsd-hardware.info/?probe=d44c580408) | Dec 16, 2022 |
| Intel         | DQ77KB AAG81483-501         | [cc51093e02](https://bsd-hardware.info/?probe=cc51093e02) | Dec 16, 2022 |
| ASRock        | Q2900M                      | [42a53e5201](https://bsd-hardware.info/?probe=42a53e5201) | Dec 16, 2022 |
| ASRock        | A75M-HVS                    | [fa8c102cfd](https://bsd-hardware.info/?probe=fa8c102cfd) | Dec 16, 2022 |
| ASUSTek       | PRIME X470-PRO              | [3faaaa8209](https://bsd-hardware.info/?probe=3faaaa8209) | Dec 16, 2022 |
| ASUSTek       | PRIME B450M-A II            | [d9376f2f63](https://bsd-hardware.info/?probe=d9376f2f63) | Dec 16, 2022 |
| Unknown       | Unknown                     | [01e26ec145](https://bsd-hardware.info/?probe=01e26ec145) | Dec 15, 2022 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | [40911b66e2](https://bsd-hardware.info/?probe=40911b66e2) | Dec 15, 2022 |
| Unknown       | Unknown                     | [9ac68a1c6d](https://bsd-hardware.info/?probe=9ac68a1c6d) | Dec 15, 2022 |
| Gigabyte      | N3160ND3V                   | [c84bedc821](https://bsd-hardware.info/?probe=c84bedc821) | Dec 15, 2022 |
| Unknown       | SKYBAY                      | [deb30193e2](https://bsd-hardware.info/?probe=deb30193e2) | Dec 15, 2022 |
| Unknown       | Unknown                     | [e3508ce360](https://bsd-hardware.info/?probe=e3508ce360) | Dec 15, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [435807287e](https://bsd-hardware.info/?probe=435807287e) | Dec 15, 2022 |
| Dell          | 0WR7PY A00                  | [f923c6c0d6](https://bsd-hardware.info/?probe=f923c6c0d6) | Dec 15, 2022 |
| Lenovo        | 3098 SDK0E50510 PRO or W... | [7cb1b0cc2d](https://bsd-hardware.info/?probe=7cb1b0cc2d) | Dec 15, 2022 |
| Dell          | 08NPPY A00                  | [e199c0ec3d](https://bsd-hardware.info/?probe=e199c0ec3d) | Dec 15, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [35ecaf0406](https://bsd-hardware.info/?probe=35ecaf0406) | Dec 15, 2022 |
| Dell          | 0CU409                      | [718c9c5c8b](https://bsd-hardware.info/?probe=718c9c5c8b) | Dec 15, 2022 |
| Dell          | 0CU409                      | [161da6b850](https://bsd-hardware.info/?probe=161da6b850) | Dec 15, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [d7d0ebf605](https://bsd-hardware.info/?probe=d7d0ebf605) | Dec 15, 2022 |
| Unknown       | Unknown                     | [7c644cc639](https://bsd-hardware.info/?probe=7c644cc639) | Dec 15, 2022 |
| Unknown       | Unknown                     | [9b5307f44d](https://bsd-hardware.info/?probe=9b5307f44d) | Dec 15, 2022 |
| Unknown       | Unknown                     | [210418cc84](https://bsd-hardware.info/?probe=210418cc84) | Dec 15, 2022 |
| HP            | 1495                        | [04bd0455f2](https://bsd-hardware.info/?probe=04bd0455f2) | Dec 14, 2022 |
| Dell          | 0X4N41 A01                  | [4091e15cac](https://bsd-hardware.info/?probe=4091e15cac) | Dec 14, 2022 |
| MW            | GMLK-2_5G4L                 | [cb16bb9431](https://bsd-hardware.info/?probe=cb16bb9431) | Dec 14, 2022 |
| NF541         | 1.0                         | [b0644bada6](https://bsd-hardware.info/?probe=b0644bada6) | Dec 14, 2022 |
| HP            | 1495                        | [23f8aeada7](https://bsd-hardware.info/?probe=23f8aeada7) | Dec 14, 2022 |
| HP            | ProLiant MicroServer        | [617f431099](https://bsd-hardware.info/?probe=617f431099) | Dec 14, 2022 |
| HP            | 2215                        | [76f607b100](https://bsd-hardware.info/?probe=76f607b100) | Dec 14, 2022 |
| Techvision    | TVI7309X B0                 | [a77d60297f](https://bsd-hardware.info/?probe=a77d60297f) | Dec 14, 2022 |
| Unknown       | Unknown                     | [85520bf6bf](https://bsd-hardware.info/?probe=85520bf6bf) | Dec 14, 2022 |
| Apple         | Mac-F221BEC8                | [bc15367e9f](https://bsd-hardware.info/?probe=bc15367e9f) | Dec 14, 2022 |
| Unknown       | Unknown                     | [ad7f977515](https://bsd-hardware.info/?probe=ad7f977515) | Dec 13, 2022 |
| AZW           | U59                         | [9b22c68e98](https://bsd-hardware.info/?probe=9b22c68e98) | Dec 13, 2022 |
| Unknown       | Unknown                     | [ec6827e543](https://bsd-hardware.info/?probe=ec6827e543) | Dec 13, 2022 |
| Unknown       | SKYBAY                      | [2d6c881723](https://bsd-hardware.info/?probe=2d6c881723) | Dec 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | [f52a3d3fa6](https://bsd-hardware.info/?probe=f52a3d3fa6) | Dec 13, 2022 |
| ASUSTek       | PRIME H410M-A               | [f51b401c31](https://bsd-hardware.info/?probe=f51b401c31) | Dec 13, 2022 |
| Intel         | Q3XXG4-P V1.0               | [abed96a938](https://bsd-hardware.info/?probe=abed96a938) | Dec 13, 2022 |
| Huanan        | X99-F8D V2.4                | [3d06b605c5](https://bsd-hardware.info/?probe=3d06b605c5) | Dec 13, 2022 |
| Gigabyte      | Z590 AORUS PRO AX           | [66e0c118d2](https://bsd-hardware.info/?probe=66e0c118d2) | Dec 13, 2022 |
| Techvision    | TVI7309X B0                 | [af9df0d2c9](https://bsd-hardware.info/?probe=af9df0d2c9) | Dec 13, 2022 |
| Unknown       | Unknown                     | [9ee8d1082b](https://bsd-hardware.info/?probe=9ee8d1082b) | Dec 12, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [73cb5d86bc](https://bsd-hardware.info/?probe=73cb5d86bc) | Dec 12, 2022 |
| Unknown       | Unknown                     | [128ce54404](https://bsd-hardware.info/?probe=128ce54404) | Dec 12, 2022 |
| MSI           | Z77A-G43                    | [735f01a028](https://bsd-hardware.info/?probe=735f01a028) | Dec 12, 2022 |
| Lenovo        | SHARKBAY NOK                | [ca959befa0](https://bsd-hardware.info/?probe=ca959befa0) | Dec 12, 2022 |
| MSI           | Z77A-G43                    | [e1297f9eef](https://bsd-hardware.info/?probe=e1297f9eef) | Dec 12, 2022 |
| Gigabyte      | X99-Designare EX-CF         | [de5bf4b420](https://bsd-hardware.info/?probe=de5bf4b420) | Dec 12, 2022 |
| Shuttle       | DH370                       | [1b938aa1a4](https://bsd-hardware.info/?probe=1b938aa1a4) | Dec 12, 2022 |
| Unknown       | MANIFOLD 2-C                | [ba191bd994](https://bsd-hardware.info/?probe=ba191bd994) | Dec 12, 2022 |
| ASRock        | J5040-ITX                   | [7f343df5d5](https://bsd-hardware.info/?probe=7f343df5d5) | Dec 12, 2022 |
| Biostar       | A68N-5600E                  | [5274876096](https://bsd-hardware.info/?probe=5274876096) | Dec 11, 2022 |
| Unknown       | Unknown                     | [fa8afd004f](https://bsd-hardware.info/?probe=fa8afd004f) | Dec 11, 2022 |
| MSI           | H81M-P33                    | [1f110891d0](https://bsd-hardware.info/?probe=1f110891d0) | Dec 11, 2022 |
| ASUSTek       | P5Q-E                       | [028383847e](https://bsd-hardware.info/?probe=028383847e) | Dec 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [99502ebe9a](https://bsd-hardware.info/?probe=99502ebe9a) | Dec 11, 2022 |
| Lenovo        | MAHOBAY NOK                 | [ad71b00b0d](https://bsd-hardware.info/?probe=ad71b00b0d) | Dec 11, 2022 |
| Techvision    | TVI7309X B0                 | [d79604d043](https://bsd-hardware.info/?probe=d79604d043) | Dec 11, 2022 |
| HP            | 82B4                        | [c47cb195e0](https://bsd-hardware.info/?probe=c47cb195e0) | Dec 11, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [3124aaaf95](https://bsd-hardware.info/?probe=3124aaaf95) | Dec 11, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [b1bd01549a](https://bsd-hardware.info/?probe=b1bd01549a) | Dec 11, 2022 |
| Dell          | 0WMJ54 A01                  | [4b14039072](https://bsd-hardware.info/?probe=4b14039072) | Dec 11, 2022 |
| Protectli     | FW4B Ver                    | [808108016d](https://bsd-hardware.info/?probe=808108016d) | Dec 10, 2022 |
| Unknown       | Unknown                     | [def65f518e](https://bsd-hardware.info/?probe=def65f518e) | Dec 10, 2022 |
| Fujitsu       | D3313-S1 S26361-D3313-S1    | [7570f3ae64](https://bsd-hardware.info/?probe=7570f3ae64) | Dec 10, 2022 |
| MSI           | B450M MORTAR MAX            | [d8d6af9e56](https://bsd-hardware.info/?probe=d8d6af9e56) | Dec 10, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [1d8397a653](https://bsd-hardware.info/?probe=1d8397a653) | Dec 10, 2022 |
| Lenovo        | SHARKBAY NOK                | [6b64c3dbaf](https://bsd-hardware.info/?probe=6b64c3dbaf) | Dec 10, 2022 |
| HP            | 213D A01                    | [6c83f31e71](https://bsd-hardware.info/?probe=6c83f31e71) | Dec 10, 2022 |
| Intel         | Q3XXG4-P V1.0               | [0b08951f1c](https://bsd-hardware.info/?probe=0b08951f1c) | Dec 10, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [342c99d07d](https://bsd-hardware.info/?probe=342c99d07d) | Dec 10, 2022 |
| Protectli     | FW4B Ver                    | [33395e819a](https://bsd-hardware.info/?probe=33395e819a) | Dec 10, 2022 |
| Dell          | 06X1TJ A00                  | [1115d508c1](https://bsd-hardware.info/?probe=1115d508c1) | Dec 09, 2022 |
| Unknown       | Unknown                     | [0405fd0f0d](https://bsd-hardware.info/?probe=0405fd0f0d) | Dec 09, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [c30f53fc6d](https://bsd-hardware.info/?probe=c30f53fc6d) | Dec 09, 2022 |
| Intel         | SHARKBAY                    | [073c2c8de0](https://bsd-hardware.info/?probe=073c2c8de0) | Dec 09, 2022 |
| Hardkernel    | ODROID-H3                   | [cd6aa62212](https://bsd-hardware.info/?probe=cd6aa62212) | Dec 09, 2022 |
| HP            | 1495                        | [3eab39d89f](https://bsd-hardware.info/?probe=3eab39d89f) | Dec 09, 2022 |
| ASUSTek       | P8H77-V LE                  | [10b6c81bce](https://bsd-hardware.info/?probe=10b6c81bce) | Dec 09, 2022 |
| Gigabyte      | H81M-S                      | [094ac0c253](https://bsd-hardware.info/?probe=094ac0c253) | Dec 09, 2022 |
| HP            | 3397                        | [bc9e5c3ab7](https://bsd-hardware.info/?probe=bc9e5c3ab7) | Dec 09, 2022 |
| Protectli     | VP2410 10                   | [3f55143fd9](https://bsd-hardware.info/?probe=3f55143fd9) | Dec 09, 2022 |
| Pegatron      | 2A72h                       | [87e76fd095](https://bsd-hardware.info/?probe=87e76fd095) | Dec 09, 2022 |
| MSI           | B450M BAZOOKA MAX WIFI      | [6b03cb139e](https://bsd-hardware.info/?probe=6b03cb139e) | Dec 09, 2022 |
| Dell          | 05GD68 A00                  | [b2f0da8246](https://bsd-hardware.info/?probe=b2f0da8246) | Dec 09, 2022 |
| Unknown       | Unknown                     | [493df1f529](https://bsd-hardware.info/?probe=493df1f529) | Dec 09, 2022 |
| PC Engines    | apu4                        | [3e3ab7f196](https://bsd-hardware.info/?probe=3e3ab7f196) | Dec 09, 2022 |
| AMI           | PEISIA E3845 VER1.0         | [0ac47aa8a0](https://bsd-hardware.info/?probe=0ac47aa8a0) | Dec 09, 2022 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [48d5feacf2](https://bsd-hardware.info/?probe=48d5feacf2) | Dec 08, 2022 |
| MW            | GMLK-2_5G4L                 | [84f8198c18](https://bsd-hardware.info/?probe=84f8198c18) | Dec 08, 2022 |
| Protectli     | FW4B Ver                    | [dbbdd023e9](https://bsd-hardware.info/?probe=dbbdd023e9) | Dec 08, 2022 |
| Protectli     | FW4C Ver                    | [71368e5cde](https://bsd-hardware.info/?probe=71368e5cde) | Dec 08, 2022 |
| ASUSTek       | G11CD                       | [7bc1746333](https://bsd-hardware.info/?probe=7bc1746333) | Dec 07, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [c953c78309](https://bsd-hardware.info/?probe=c953c78309) | Dec 07, 2022 |
| ASRock        | 4X4-4000 Series             | [8ac499a511](https://bsd-hardware.info/?probe=8ac499a511) | Dec 07, 2022 |
| Techvision    | TVI7309X B0                 | [a28b2cf6da](https://bsd-hardware.info/?probe=a28b2cf6da) | Dec 07, 2022 |
| HP            | 1495                        | [3f033cb7f5](https://bsd-hardware.info/?probe=3f033cb7f5) | Dec 07, 2022 |
| ASRock        | H110 Pro BTC+               | [7cc4b63834](https://bsd-hardware.info/?probe=7cc4b63834) | Dec 07, 2022 |
| Protectli     | FW4B Ver                    | [27dea9bcb5](https://bsd-hardware.info/?probe=27dea9bcb5) | Dec 07, 2022 |
| ASRock        | H110 Pro BTC+               | [f733e29fc8](https://bsd-hardware.info/?probe=f733e29fc8) | Dec 06, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | [c33d11ed7b](https://bsd-hardware.info/?probe=c33d11ed7b) | Dec 06, 2022 |
| JGINYUE       | H97I GAMING V1.0            | [f222af4098](https://bsd-hardware.info/?probe=f222af4098) | Dec 06, 2022 |
| Dell          | 0G261D A00                  | [24b9490c77](https://bsd-hardware.info/?probe=24b9490c77) | Dec 06, 2022 |
| Shuttle       | DS10U                       | [0f1e027b35](https://bsd-hardware.info/?probe=0f1e027b35) | Dec 06, 2022 |
| Unknown       | Unknown                     | [78893acbd5](https://bsd-hardware.info/?probe=78893acbd5) | Dec 06, 2022 |
| ASUSTek       | CM1530                      | [902c77b5dc](https://bsd-hardware.info/?probe=902c77b5dc) | Dec 06, 2022 |
| Dell          | 0WMJ54 A01                  | [61347ab3e9](https://bsd-hardware.info/?probe=61347ab3e9) | Dec 06, 2022 |
| Unknown       | Unknown                     | [e3dad11b11](https://bsd-hardware.info/?probe=e3dad11b11) | Dec 06, 2022 |
| HP            | 82A2                        | [c612b7e283](https://bsd-hardware.info/?probe=c612b7e283) | Dec 06, 2022 |
| Techvision    | TVI7309X B0                 | [657972a55d](https://bsd-hardware.info/?probe=657972a55d) | Dec 06, 2022 |
| Techvision    | TVI7309X B0                 | [33f23b1291](https://bsd-hardware.info/?probe=33f23b1291) | Dec 06, 2022 |
| YANYU         | R250                        | [bb364271b2](https://bsd-hardware.info/?probe=bb364271b2) | Dec 05, 2022 |
| Protectli     | FW4B Ver                    | [eaa3b9783e](https://bsd-hardware.info/?probe=eaa3b9783e) | Dec 05, 2022 |
| Dell          | 0WMJ54 A01                  | [5441995e7b](https://bsd-hardware.info/?probe=5441995e7b) | Dec 05, 2022 |
| Intel         | Q3XXG4-P V1.0               | [f130844e1e](https://bsd-hardware.info/?probe=f130844e1e) | Dec 05, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [15b2363325](https://bsd-hardware.info/?probe=15b2363325) | Dec 05, 2022 |
| PC Engines    | apu4                        | [72061eb254](https://bsd-hardware.info/?probe=72061eb254) | Dec 05, 2022 |
| Gigabyte      | M68MT-S2P                   | [2fe00838c3](https://bsd-hardware.info/?probe=2fe00838c3) | Dec 05, 2022 |
| ACMA          | X8SIE                       | [361e4ccc04](https://bsd-hardware.info/?probe=361e4ccc04) | Dec 05, 2022 |
| Gigabyte      | M68MT-S2P                   | [71f95dafb4](https://bsd-hardware.info/?probe=71f95dafb4) | Dec 05, 2022 |
| Huanan        | X99-F8D V2.4                | [f6685811a3](https://bsd-hardware.info/?probe=f6685811a3) | Dec 05, 2022 |
| Dell          | 0CNWVK A00                  | [5a022db6bf](https://bsd-hardware.info/?probe=5a022db6bf) | Dec 05, 2022 |
| Acer          | Aspire XC-105               | [250b12c3f2](https://bsd-hardware.info/?probe=250b12c3f2) | Dec 05, 2022 |
| Intel         | CARLOW                      | [1b45524779](https://bsd-hardware.info/?probe=1b45524779) | Dec 05, 2022 |
| Supermicro    | X11SDV-4C-TP8F              | [05566134f9](https://bsd-hardware.info/?probe=05566134f9) | Dec 05, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [aa9482884f](https://bsd-hardware.info/?probe=aa9482884f) | Dec 05, 2022 |
| ASUSTek       | PRIME B360M-K               | [90279b62b7](https://bsd-hardware.info/?probe=90279b62b7) | Dec 05, 2022 |
| Shuttle       | FS77U                       | [4172b79cfc](https://bsd-hardware.info/?probe=4172b79cfc) | Dec 04, 2022 |
| Dell          | 02YYK5 A01                  | [54d1511b82](https://bsd-hardware.info/?probe=54d1511b82) | Dec 04, 2022 |
| Unknown       | Unknown                     | [54e89ef90b](https://bsd-hardware.info/?probe=54e89ef90b) | Dec 04, 2022 |
| MSI           | B560M-A PRO                 | [be5f6ad306](https://bsd-hardware.info/?probe=be5f6ad306) | Dec 04, 2022 |
| Unknown       | Unknown                     | [af4f0984ae](https://bsd-hardware.info/?probe=af4f0984ae) | Dec 04, 2022 |
| ASUSTek       | E35M1-I DELUXE              | [1a183385c7](https://bsd-hardware.info/?probe=1a183385c7) | Dec 04, 2022 |
| MSI           | H81M-P33                    | [d72a45fb8f](https://bsd-hardware.info/?probe=d72a45fb8f) | Dec 04, 2022 |
| ASUSTek       | P5Q-E                       | [595d174631](https://bsd-hardware.info/?probe=595d174631) | Dec 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [8ee41750dc](https://bsd-hardware.info/?probe=8ee41750dc) | Dec 04, 2022 |
| Unknown       | Unknown                     | [d9113585f0](https://bsd-hardware.info/?probe=d9113585f0) | Dec 04, 2022 |
| ShenZhen M... | MW-GMLK-2.5G6L              | [0bdf47ea4c](https://bsd-hardware.info/?probe=0bdf47ea4c) | Dec 04, 2022 |
| Intel         | MAHOBAY                     | [f34b488e42](https://bsd-hardware.info/?probe=f34b488e42) | Dec 04, 2022 |
| Dell          | 0GXM1W A00                  | [9497657cb2](https://bsd-hardware.info/?probe=9497657cb2) | Dec 04, 2022 |
| Intel         | SHARKBAY                    | [94f78cb509](https://bsd-hardware.info/?probe=94f78cb509) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [aeb690b9f3](https://bsd-hardware.info/?probe=aeb690b9f3) | Dec 03, 2022 |
| Dell          | 0PTTT9 A01                  | [1916a4064b](https://bsd-hardware.info/?probe=1916a4064b) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [d4e60c5984](https://bsd-hardware.info/?probe=d4e60c5984) | Dec 03, 2022 |
| Unknown       | Unknown                     | [90de1777bc](https://bsd-hardware.info/?probe=90de1777bc) | Dec 02, 2022 |
| ASRock        | A320M-HDV R4.0              | [f6c721906b](https://bsd-hardware.info/?probe=f6c721906b) | Dec 02, 2022 |
| MSI           | A320M-A PRO MAX             | [5e75bcdb11](https://bsd-hardware.info/?probe=5e75bcdb11) | Dec 02, 2022 |
| Deciso        | Netboard A10 V2.1           | [40a0d948b4](https://bsd-hardware.info/?probe=40a0d948b4) | Dec 02, 2022 |
| Techvision    | TVI7309X B0                 | [f8719b2320](https://bsd-hardware.info/?probe=f8719b2320) | Dec 02, 2022 |
| Dell          | 0KYJ8C A02                  | [c0c4fa9349](https://bsd-hardware.info/?probe=c0c4fa9349) | Dec 02, 2022 |
| Intel         | D33217CK G76541-300         | [545a39b1e4](https://bsd-hardware.info/?probe=545a39b1e4) | Dec 02, 2022 |
| Protectli     | FW4B Ver                    | [4bf1aae972](https://bsd-hardware.info/?probe=4bf1aae972) | Dec 02, 2022 |
| Intel         | X99                         | [c21a466fc1](https://bsd-hardware.info/?probe=c21a466fc1) | Dec 01, 2022 |
| Unknown       | Unknown                     | [243e309a04](https://bsd-hardware.info/?probe=243e309a04) | Dec 01, 2022 |
| Gigabyte      | Z170X-Gaming 3              | [03708406e8](https://bsd-hardware.info/?probe=03708406e8) | Dec 01, 2022 |
| HP            | 8054                        | [c25adeb2ff](https://bsd-hardware.info/?probe=c25adeb2ff) | Dec 01, 2022 |
| Unknown       | Unknown                     | [32a4df9cae](https://bsd-hardware.info/?probe=32a4df9cae) | Dec 01, 2022 |
| Unknown       | Unknown                     | [504a659236](https://bsd-hardware.info/?probe=504a659236) | Dec 01, 2022 |
| MSI           | Z87I                        | [570046969c](https://bsd-hardware.info/?probe=570046969c) | Dec 01, 2022 |
| Intel         | Q3XXG4-P V1.0               | [84d1656c05](https://bsd-hardware.info/?probe=84d1656c05) | Nov 30, 2022 |
| Dell          | 08NPPY A00                  | [6a1a5865cb](https://bsd-hardware.info/?probe=6a1a5865cb) | Nov 30, 2022 |
| ASRockRack    | EPYC3101D4I-2T              | [087264570d](https://bsd-hardware.info/?probe=087264570d) | Nov 30, 2022 |
| PC Engines    | apu4                        | [7c8b9014b1](https://bsd-hardware.info/?probe=7c8b9014b1) | Nov 30, 2022 |
| PC Engines    | apu4                        | [dd39e91713](https://bsd-hardware.info/?probe=dd39e91713) | Nov 30, 2022 |
| Gigabyte      | B450M DS3H-CF               | [794e041b13](https://bsd-hardware.info/?probe=794e041b13) | Nov 30, 2022 |
| Protectli     | FW6                         | [95f3201109](https://bsd-hardware.info/?probe=95f3201109) | Nov 30, 2022 |
| Protectli     | FW4A Ver                    | [9e6e0f5548](https://bsd-hardware.info/?probe=9e6e0f5548) | Nov 30, 2022 |
| Intel         | D54250WYK H13922-303        | [f3b09cfb70](https://bsd-hardware.info/?probe=f3b09cfb70) | Nov 30, 2022 |
| Intel         | D33217CK G76541-300         | [bbdd9a1b98](https://bsd-hardware.info/?probe=bbdd9a1b98) | Nov 30, 2022 |
| Lenovo        | MAHOBAY                     | [1d61d0cf62](https://bsd-hardware.info/?probe=1d61d0cf62) | Nov 29, 2022 |
| ASRockRack    | X470D4U                     | [38d7f55ef7](https://bsd-hardware.info/?probe=38d7f55ef7) | Nov 29, 2022 |
| Protectli     | FW4B Ver                    | [cfaeaeb2f2](https://bsd-hardware.info/?probe=cfaeaeb2f2) | Nov 29, 2022 |
| MSI           | PRO H610M-B DDR4            | [929e4bda1e](https://bsd-hardware.info/?probe=929e4bda1e) | Nov 29, 2022 |
| Unknown       | Unknown                     | [a5b10d3f79](https://bsd-hardware.info/?probe=a5b10d3f79) | Nov 29, 2022 |
| ACMA          | X8SIE                       | [532b81e55f](https://bsd-hardware.info/?probe=532b81e55f) | Nov 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [7308d658dc](https://bsd-hardware.info/?probe=7308d658dc) | Nov 29, 2022 |
| MSI           | PRO H610M-B DDR4            | [7c9ee800c5](https://bsd-hardware.info/?probe=7c9ee800c5) | Nov 29, 2022 |
| HP            | 8299                        | [d697a2e953](https://bsd-hardware.info/?probe=d697a2e953) | Nov 29, 2022 |
| ACMA          | X8SIE                       | [d0112d027b](https://bsd-hardware.info/?probe=d0112d027b) | Nov 28, 2022 |
| QIYIDA        | X99-H9 V2.0                 | [43163b0170](https://bsd-hardware.info/?probe=43163b0170) | Nov 28, 2022 |
| QIYIDA        | X99-H9 V2.0                 | [d00aa0021e](https://bsd-hardware.info/?probe=d00aa0021e) | Nov 28, 2022 |
| Unknown       | Unknown                     | [4e40278b06](https://bsd-hardware.info/?probe=4e40278b06) | Nov 28, 2022 |
| MSI           | Z77A-G43                    | [28dd3a0b1b](https://bsd-hardware.info/?probe=28dd3a0b1b) | Nov 28, 2022 |
| Deciso        | Netboard A10 GEN2 Model ... | [d48dbd053d](https://bsd-hardware.info/?probe=d48dbd053d) | Nov 28, 2022 |
| PC Engines    | apu4                        | [588e065800](https://bsd-hardware.info/?probe=588e065800) | Nov 28, 2022 |
| Intel         | D54250WYK H13922-303        | [e850e0ae9c](https://bsd-hardware.info/?probe=e850e0ae9c) | Nov 28, 2022 |
| Gigabyte      | H110M-S2H-CF                | [35950045c6](https://bsd-hardware.info/?probe=35950045c6) | Nov 28, 2022 |
| Unknown       | Unknown                     | [2fe35064cb](https://bsd-hardware.info/?probe=2fe35064cb) | Nov 28, 2022 |
| Intel         | Q3XXG4-P V1.0               | [b1f32ca8a1](https://bsd-hardware.info/?probe=b1f32ca8a1) | Nov 28, 2022 |
| ASUSTek       | Pro WS 565-ACE              | [378270eba0](https://bsd-hardware.info/?probe=378270eba0) | Nov 28, 2022 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | [b4cc780c40](https://bsd-hardware.info/?probe=b4cc780c40) | Nov 28, 2022 |
| Shuttle       | FS81                        | [f714ba647f](https://bsd-hardware.info/?probe=f714ba647f) | Nov 28, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | [fd111870fa](https://bsd-hardware.info/?probe=fd111870fa) | Nov 28, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [ae55a799e8](https://bsd-hardware.info/?probe=ae55a799e8) | Nov 28, 2022 |
| ASUSTek       | PRIME Z390M-PLUS            | [7329e04c22](https://bsd-hardware.info/?probe=7329e04c22) | Nov 27, 2022 |
| PC Engines    | apu6                        | [13dcbe5748](https://bsd-hardware.info/?probe=13dcbe5748) | Nov 27, 2022 |
| ASUSTek       | H97-PLUS                    | [39ece5deaf](https://bsd-hardware.info/?probe=39ece5deaf) | Nov 27, 2022 |
| YANYU         | R250                        | [0be0925e5b](https://bsd-hardware.info/?probe=0be0925e5b) | Nov 27, 2022 |
| ASRock        | X570 Pro4                   | [b23f59a068](https://bsd-hardware.info/?probe=b23f59a068) | Nov 27, 2022 |
| Dell          | 09M8Y8 A02                  | [2299b7c270](https://bsd-hardware.info/?probe=2299b7c270) | Nov 27, 2022 |
| MSI           | H81M-P33                    | [597d48d1c9](https://bsd-hardware.info/?probe=597d48d1c9) | Nov 27, 2022 |
| ASUSTek       | P5Q-E                       | [10d76fd431](https://bsd-hardware.info/?probe=10d76fd431) | Nov 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [383341b2f1](https://bsd-hardware.info/?probe=383341b2f1) | Nov 27, 2022 |
| Acer          | Revo RN86                   | [a4dcb7f7a2](https://bsd-hardware.info/?probe=a4dcb7f7a2) | Nov 27, 2022 |
| ASRock        | Q1900B-ITX                  | [c93690c7ca](https://bsd-hardware.info/?probe=c93690c7ca) | Nov 27, 2022 |
| Shuttle       | FZ270                       | [04a7f49322](https://bsd-hardware.info/?probe=04a7f49322) | Nov 27, 2022 |
| Shuttle       | FZ270                       | [10016f39b9](https://bsd-hardware.info/?probe=10016f39b9) | Nov 27, 2022 |
| ASRock        | Q1900B-ITX                  | [675c9fdf94](https://bsd-hardware.info/?probe=675c9fdf94) | Nov 27, 2022 |
| ASRock        | Q1900B-ITX                  | [a337eb9e5f](https://bsd-hardware.info/?probe=a337eb9e5f) | Nov 27, 2022 |
| Shuttle       | FH270                       | [192351ac6f](https://bsd-hardware.info/?probe=192351ac6f) | Nov 27, 2022 |
| Shuttle       | FH270                       | [3b68d89092](https://bsd-hardware.info/?probe=3b68d89092) | Nov 27, 2022 |
| ASRock        | N68-S                       | [3813c8856e](https://bsd-hardware.info/?probe=3813c8856e) | Nov 27, 2022 |
| Protectli     | FW4B Ver                    | [e8e158f783](https://bsd-hardware.info/?probe=e8e158f783) | Nov 27, 2022 |
| Supermicro    | X10SRG-F                    | [66b7819b2a](https://bsd-hardware.info/?probe=66b7819b2a) | Nov 27, 2022 |
| Unknown       | Unknown                     | [512a05eefb](https://bsd-hardware.info/?probe=512a05eefb) | Nov 27, 2022 |
| Gigabyte      | H110M-S2H-CF                | [ed6b1f75ae](https://bsd-hardware.info/?probe=ed6b1f75ae) | Nov 27, 2022 |
| ASUSTek       | PRIME B450M-A               | [5f0b8df8d0](https://bsd-hardware.info/?probe=5f0b8df8d0) | Nov 27, 2022 |
| ASRock        | J4125B-ITX                  | [ad497a63ac](https://bsd-hardware.info/?probe=ad497a63ac) | Nov 27, 2022 |
| HP            | 18E7                        | [c7635c715f](https://bsd-hardware.info/?probe=c7635c715f) | Nov 26, 2022 |
| Intel         | DH87MC AAG74242-401         | [33c1878560](https://bsd-hardware.info/?probe=33c1878560) | Nov 26, 2022 |
| ASUSTek       | P11C-X Series               | [6860cd72f8](https://bsd-hardware.info/?probe=6860cd72f8) | Nov 26, 2022 |
| ASUSTek       | P11C-X Series               | [cfdb06e761](https://bsd-hardware.info/?probe=cfdb06e761) | Nov 26, 2022 |
| ASUSTek       | P5K-E                       | [2b00248458](https://bsd-hardware.info/?probe=2b00248458) | Nov 26, 2022 |
| Intel         | CRESCENTBAY                 | [bd1f1fa769](https://bsd-hardware.info/?probe=bd1f1fa769) | Nov 26, 2022 |
| Lenovo        | SHARKBAY NOK                | [7c9df6da87](https://bsd-hardware.info/?probe=7c9df6da87) | Nov 26, 2022 |
| Lenovo        | SHARKBAY NOK                | [b87ed70877](https://bsd-hardware.info/?probe=b87ed70877) | Nov 26, 2022 |
| MW            | GMLK-2_5G4L                 | [7f9869324b](https://bsd-hardware.info/?probe=7f9869324b) | Nov 26, 2022 |
| Unknown       | Unknown                     | [222e69ff59](https://bsd-hardware.info/?probe=222e69ff59) | Nov 26, 2022 |
| Dell          | 0M017G A00                  | [3acaad9a7d](https://bsd-hardware.info/?probe=3acaad9a7d) | Nov 26, 2022 |
| Unknown       | Unknown                     | [6de307244e](https://bsd-hardware.info/?probe=6de307244e) | Nov 26, 2022 |
| MW            | GMLK-2_5G4L                 | [787a2db2cd](https://bsd-hardware.info/?probe=787a2db2cd) | Nov 26, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [88929a3594](https://bsd-hardware.info/?probe=88929a3594) | Nov 25, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [ef6190861c](https://bsd-hardware.info/?probe=ef6190861c) | Nov 25, 2022 |
| Protectli     | FW6                         | [74510f3177](https://bsd-hardware.info/?probe=74510f3177) | Nov 25, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [76ecd68ff6](https://bsd-hardware.info/?probe=76ecd68ff6) | Nov 25, 2022 |
| Protectli     | FW2B Ver                    | [e03929e52f](https://bsd-hardware.info/?probe=e03929e52f) | Nov 25, 2022 |
| Techvision    | TVI7309X B0                 | [317231bad8](https://bsd-hardware.info/?probe=317231bad8) | Nov 25, 2022 |
| HP            | 3048h                       | [3f43816a5d](https://bsd-hardware.info/?probe=3f43816a5d) | Nov 25, 2022 |
| Lenovo        | ThinkStation S30 0569A93    | [dd545fb588](https://bsd-hardware.info/?probe=dd545fb588) | Nov 25, 2022 |
| Dell          | 0PTTT9 A01                  | [74575d6dfe](https://bsd-hardware.info/?probe=74575d6dfe) | Nov 25, 2022 |
| Pegatron      | IPM41-D3                    | [898f645e32](https://bsd-hardware.info/?probe=898f645e32) | Nov 25, 2022 |
| ASRock        | H510M-HDV                   | [d2029ae805](https://bsd-hardware.info/?probe=d2029ae805) | Nov 25, 2022 |
| Unknown       | Unknown                     | [1d3bd58d18](https://bsd-hardware.info/?probe=1d3bd58d18) | Nov 25, 2022 |
| Lenovo        | 1106A14 ThinkServer TS13... | [28aca8c985](https://bsd-hardware.info/?probe=28aca8c985) | Nov 25, 2022 |
| Gigabyte      | G31M-ES2C                   | [2959091a59](https://bsd-hardware.info/?probe=2959091a59) | Nov 25, 2022 |
| MSI           | Z170A GAMING M5             | [5740972ddc](https://bsd-hardware.info/?probe=5740972ddc) | Nov 25, 2022 |
| HP            | 8055                        | [ace4570d15](https://bsd-hardware.info/?probe=ace4570d15) | Nov 25, 2022 |
| MW            | GMLK-2_5G4L                 | [de7f2ee053](https://bsd-hardware.info/?probe=de7f2ee053) | Nov 25, 2022 |
| Techvision    | TVI7309X B0                 | [7258992b77](https://bsd-hardware.info/?probe=7258992b77) | Nov 24, 2022 |
| ASRock        | B450M-HDV                   | [d0009172b1](https://bsd-hardware.info/?probe=d0009172b1) | Nov 24, 2022 |
| ASRock        | B450M-HDV                   | [25cc0129d9](https://bsd-hardware.info/?probe=25cc0129d9) | Nov 24, 2022 |
| Unknown       | Unknown                     | [d4246caa0f](https://bsd-hardware.info/?probe=d4246caa0f) | Nov 24, 2022 |
| Dell          | 0T7D40 A01                  | [45d96a0b5a](https://bsd-hardware.info/?probe=45d96a0b5a) | Nov 24, 2022 |
| Unknown       | Unknown                     | [5aa1f0193a](https://bsd-hardware.info/?probe=5aa1f0193a) | Nov 24, 2022 |
| Unknown       | Unknown                     | [c5562e1851](https://bsd-hardware.info/?probe=c5562e1851) | Nov 24, 2022 |
| MSI           | A320M-A PRO                 | [fc71b97d90](https://bsd-hardware.info/?probe=fc71b97d90) | Nov 24, 2022 |
| MW            | GMLK-2_5G4L                 | [b6bbaa13e8](https://bsd-hardware.info/?probe=b6bbaa13e8) | Nov 24, 2022 |
| Dell          | 07F37C A01                  | [08d048da80](https://bsd-hardware.info/?probe=08d048da80) | Nov 24, 2022 |
| ASRock Ind... | NUC-1240P                   | [75547bc09a](https://bsd-hardware.info/?probe=75547bc09a) | Nov 24, 2022 |
| Gigabyte      | E2500N                      | [64b937b551](https://bsd-hardware.info/?probe=64b937b551) | Nov 23, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [aa3c44499f](https://bsd-hardware.info/?probe=aa3c44499f) | Nov 23, 2022 |
| Gigabyte      | G31M-S2L                    | [d376385d80](https://bsd-hardware.info/?probe=d376385d80) | Nov 23, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [1b6870d481](https://bsd-hardware.info/?probe=1b6870d481) | Nov 23, 2022 |
| Unknown       | Unknown                     | [77e932dd9e](https://bsd-hardware.info/?probe=77e932dd9e) | Nov 23, 2022 |
| IceWhale T... | ZimaBoard 216 ZMB           | [b75d6c6581](https://bsd-hardware.info/?probe=b75d6c6581) | Nov 23, 2022 |
| Dell          | 06D7TR A00                  | [7fabc0cb8a](https://bsd-hardware.info/?probe=7fabc0cb8a) | Nov 23, 2022 |
| Unknown       | Unknown                     | [337d5f0f4b](https://bsd-hardware.info/?probe=337d5f0f4b) | Nov 23, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | [1860d18e39](https://bsd-hardware.info/?probe=1860d18e39) | Nov 23, 2022 |
| Protectli     | FW4B                        | [d3090c9e8e](https://bsd-hardware.info/?probe=d3090c9e8e) | Nov 23, 2022 |
| Infoblox      | IB-1410                     | [7521108ef5](https://bsd-hardware.info/?probe=7521108ef5) | Nov 23, 2022 |
| ASUSTek       | A55BM-K                     | [dc487b5779](https://bsd-hardware.info/?probe=dc487b5779) | Nov 23, 2022 |
| HP            | 3396                        | [dc94cbde1a](https://bsd-hardware.info/?probe=dc94cbde1a) | Nov 23, 2022 |
| PC Engines    | apu6                        | [bc334caa03](https://bsd-hardware.info/?probe=bc334caa03) | Nov 23, 2022 |
| PC Engines    | APU2                        | [4d33b6da51](https://bsd-hardware.info/?probe=4d33b6da51) | Nov 23, 2022 |
| ASUSTek       | PRIME A320M-K               | [9701222998](https://bsd-hardware.info/?probe=9701222998) | Nov 23, 2022 |
| CncTion       | N5105-4L B0                 | [d4791d1dfc](https://bsd-hardware.info/?probe=d4791d1dfc) | Nov 22, 2022 |
| Intel         | H61                         | [689ebf0e57](https://bsd-hardware.info/?probe=689ebf0e57) | Nov 22, 2022 |
| Datto         | SSD                         | [08d401fa34](https://bsd-hardware.info/?probe=08d401fa34) | Nov 22, 2022 |
| Gigabyte      | J3455N-D3H                  | [2f812bd8c3](https://bsd-hardware.info/?probe=2f812bd8c3) | Nov 22, 2022 |
| Gigabyte      | H81M-HD3                    | [564cf3d66a](https://bsd-hardware.info/?probe=564cf3d66a) | Nov 22, 2022 |
| Unknown       | Unknown                     | [fdffbdb940](https://bsd-hardware.info/?probe=fdffbdb940) | Nov 22, 2022 |
| Apple         | PowerMac10,1                | [0760ed34c3](https://bsd-hardware.info/?probe=0760ed34c3) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d893e02d90](https://bsd-hardware.info/?probe=d893e02d90) | Nov 21, 2022 |
| Protectli     | FW4B Ver                    | [77fa42b66c](https://bsd-hardware.info/?probe=77fa42b66c) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [7518e4f06a](https://bsd-hardware.info/?probe=7518e4f06a) | Nov 21, 2022 |
| Gigabyte      | P61-USB3-B3                 | [1ec1683acd](https://bsd-hardware.info/?probe=1ec1683acd) | Nov 21, 2022 |
| Gigabyte      | P61-USB3-B3                 | [5f442f0c65](https://bsd-hardware.info/?probe=5f442f0c65) | Nov 21, 2022 |
| Gigabyte      | H61M-S1                     | [2b851dbbc1](https://bsd-hardware.info/?probe=2b851dbbc1) | Nov 21, 2022 |
| Gigabyte      | Z590I AORUS ULTRA           | [e55eb53894](https://bsd-hardware.info/?probe=e55eb53894) | Nov 21, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [f7129f1c87](https://bsd-hardware.info/?probe=f7129f1c87) | Nov 21, 2022 |
| Gigabyte      | 970A-D3P                    | [cced487ec5](https://bsd-hardware.info/?probe=cced487ec5) | Nov 21, 2022 |
| Gigabyte      | 970A-D3P                    | [c28a22ecb5](https://bsd-hardware.info/?probe=c28a22ecb5) | Nov 21, 2022 |
| ASUSTek       | P5KPL-VM-TWPC               | [6a5ff282a7](https://bsd-hardware.info/?probe=6a5ff282a7) | Nov 21, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [17aa370584](https://bsd-hardware.info/?probe=17aa370584) | Nov 21, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [298fde4e33](https://bsd-hardware.info/?probe=298fde4e33) | Nov 21, 2022 |
| Unknown       | SKYBAY                      | [5030575f0a](https://bsd-hardware.info/?probe=5030575f0a) | Nov 20, 2022 |
| Dell          | 07F37C A01                  | [efb5c9d03d](https://bsd-hardware.info/?probe=efb5c9d03d) | Nov 20, 2022 |
| Techvision    | TVI7309X B0                 | [98684b1d19](https://bsd-hardware.info/?probe=98684b1d19) | Nov 20, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | [f6491f1950](https://bsd-hardware.info/?probe=f6491f1950) | Nov 20, 2022 |
| OEM           | 1.0                         | [a821818533](https://bsd-hardware.info/?probe=a821818533) | Nov 20, 2022 |
| MSI           | H81M-P33                    | [d3303d1962](https://bsd-hardware.info/?probe=d3303d1962) | Nov 20, 2022 |
| ASUSTek       | P5Q-E                       | [b1512a254c](https://bsd-hardware.info/?probe=b1512a254c) | Nov 20, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [521e5ffa8e](https://bsd-hardware.info/?probe=521e5ffa8e) | Nov 20, 2022 |
| HP            | 8054                        | [2c1e20c9e7](https://bsd-hardware.info/?probe=2c1e20c9e7) | Nov 20, 2022 |
| Hardkernel    | ODROID-H3                   | [ec7611edd1](https://bsd-hardware.info/?probe=ec7611edd1) | Nov 20, 2022 |
| Dell          | 0YNVJG A01                  | [15d32e1e36](https://bsd-hardware.info/?probe=15d32e1e36) | Nov 20, 2022 |
| Techvision    | TVI7309X B0                 | [c226ac3d9b](https://bsd-hardware.info/?probe=c226ac3d9b) | Nov 20, 2022 |
| ASUSTek       | PRIME B450M-A II            | [5d3ccb6891](https://bsd-hardware.info/?probe=5d3ccb6891) | Nov 20, 2022 |
| CncTion       | N5105-4L B0                 | [449dcd1463](https://bsd-hardware.info/?probe=449dcd1463) | Nov 19, 2022 |
| Dell          | 09D2HH A00                  | [794fe8eb65](https://bsd-hardware.info/?probe=794fe8eb65) | Nov 19, 2022 |
| TOPFEEL       | H110D4-P1                   | [90b1dfc430](https://bsd-hardware.info/?probe=90b1dfc430) | Nov 19, 2022 |
| Supermicro    | X11SDV-4C-TP8F              | [402a623ed0](https://bsd-hardware.info/?probe=402a623ed0) | Nov 19, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [92eab8d065](https://bsd-hardware.info/?probe=92eab8d065) | Nov 19, 2022 |
| Foxconn       | H67S/H61SP                  | [80ad331089](https://bsd-hardware.info/?probe=80ad331089) | Nov 19, 2022 |
| Lenovo        | MAHOBAY NOK                 | [18062e5bd5](https://bsd-hardware.info/?probe=18062e5bd5) | Nov 19, 2022 |
| Dell          | 0KYJ8C A02                  | [7282ce8fe2](https://bsd-hardware.info/?probe=7282ce8fe2) | Nov 19, 2022 |
| Dell          | 0GN4PW A00                  | [9127ec4dac](https://bsd-hardware.info/?probe=9127ec4dac) | Nov 19, 2022 |
| Techvision    | TVI7309X B0                 | [d3cbc9d6ca](https://bsd-hardware.info/?probe=d3cbc9d6ca) | Nov 19, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [2eba32390f](https://bsd-hardware.info/?probe=2eba32390f) | Nov 19, 2022 |
| PC Engines    | apu6                        | [1e9acc3ae6](https://bsd-hardware.info/?probe=1e9acc3ae6) | Nov 18, 2022 |
| Huanan        | X99-F8D V2.4                | [9faf79b3f3](https://bsd-hardware.info/?probe=9faf79b3f3) | Nov 18, 2022 |
| MSI           | Z97S SLI Krait Edition      | [f25480c54a](https://bsd-hardware.info/?probe=f25480c54a) | Nov 18, 2022 |
| ASUSTek       | M5A97 PLUS                  | [7c7a121711](https://bsd-hardware.info/?probe=7c7a121711) | Nov 18, 2022 |
| Intel         | SHARKBAY                    | [5875ecec9f](https://bsd-hardware.info/?probe=5875ecec9f) | Nov 18, 2022 |
| HP            | 82FE 11                     | [547e5e3ce1](https://bsd-hardware.info/?probe=547e5e3ce1) | Nov 18, 2022 |
| Foxconn       | 2AB1                        | [f732942dd9](https://bsd-hardware.info/?probe=f732942dd9) | Nov 18, 2022 |
| Fujitsu       | D3289-A1 S26361-D3289-A1... | [dae7027898](https://bsd-hardware.info/?probe=dae7027898) | Nov 18, 2022 |
| Dell          | 051FJ8 A02                  | [296b446a8f](https://bsd-hardware.info/?probe=296b446a8f) | Nov 18, 2022 |
| ASRock        | N3150M                      | [d3b3be7936](https://bsd-hardware.info/?probe=d3b3be7936) | Nov 17, 2022 |
| ASUSTek       | H110I-PLUS                  | [f1f56fe86c](https://bsd-hardware.info/?probe=f1f56fe86c) | Nov 17, 2022 |
| Gigabyte      | H110TN                      | [c121bad3fb](https://bsd-hardware.info/?probe=c121bad3fb) | Nov 17, 2022 |
| MSI           | Z97S SLI Krait Edition      | [ddf3f8603a](https://bsd-hardware.info/?probe=ddf3f8603a) | Nov 17, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [64d8291a91](https://bsd-hardware.info/?probe=64d8291a91) | Nov 17, 2022 |
| PC Engines    | apu4                        | [212f27d85a](https://bsd-hardware.info/?probe=212f27d85a) | Nov 17, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [0d37f1878b](https://bsd-hardware.info/?probe=0d37f1878b) | Nov 17, 2022 |
| AAEON         | MF-001 V1.0                 | [d98d84f1a4](https://bsd-hardware.info/?probe=d98d84f1a4) | Nov 17, 2022 |
| AZW           | U59                         | [25e1349c5f](https://bsd-hardware.info/?probe=25e1349c5f) | Nov 17, 2022 |
| Supermicro    | A2SDi-4C-HLN4F              | [9cd1c1fc21](https://bsd-hardware.info/?probe=9cd1c1fc21) | Nov 17, 2022 |
| Dell          | 05XGC8 A00                  | [15458aff84](https://bsd-hardware.info/?probe=15458aff84) | Nov 16, 2022 |
| MSI           | Z97S SLI Krait Edition      | [47f82850da](https://bsd-hardware.info/?probe=47f82850da) | Nov 16, 2022 |
| MSI           | X299 PRO                    | [d615157be7](https://bsd-hardware.info/?probe=d615157be7) | Nov 16, 2022 |
| ASRock        | J5040-ITX                   | [753c68cfb9](https://bsd-hardware.info/?probe=753c68cfb9) | Nov 16, 2022 |
| Dell          | 05XGC8 A00                  | [94afb24fbc](https://bsd-hardware.info/?probe=94afb24fbc) | Nov 16, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [2714f36aca](https://bsd-hardware.info/?probe=2714f36aca) | Nov 16, 2022 |
| Intel         | Q3XXG4-P V1.0               | [5096994f99](https://bsd-hardware.info/?probe=5096994f99) | Nov 16, 2022 |
| HP            | 82B4                        | [d4badfa185](https://bsd-hardware.info/?probe=d4badfa185) | Nov 15, 2022 |
| ASUSTek       | P6T DELUXE V2               | [314916c885](https://bsd-hardware.info/?probe=314916c885) | Nov 15, 2022 |
| HP            | 1998                        | [9239fe7437](https://bsd-hardware.info/?probe=9239fe7437) | Nov 15, 2022 |
| MSI           | B450M MORTAR MAX            | [15657b37e2](https://bsd-hardware.info/?probe=15657b37e2) | Nov 15, 2022 |
| MSI           | B450M MORTAR MAX            | [f4a8c42773](https://bsd-hardware.info/?probe=f4a8c42773) | Nov 15, 2022 |
| Protectli     | FW4B Ver                    | [dd637e0562](https://bsd-hardware.info/?probe=dd637e0562) | Nov 15, 2022 |
| PC Engines    | apu4                        | [589dec199e](https://bsd-hardware.info/?probe=589dec199e) | Nov 15, 2022 |
| Acer          | TDPS05 R3700                | [4ebc5df17c](https://bsd-hardware.info/?probe=4ebc5df17c) | Nov 15, 2022 |
| Acer          | TDPS05 R3700                | [6e1273fdd6](https://bsd-hardware.info/?probe=6e1273fdd6) | Nov 15, 2022 |
| Dell          | 0WR7PY A03                  | [cecda8d045](https://bsd-hardware.info/?probe=cecda8d045) | Nov 14, 2022 |
| Shuttle       | FH61V                       | [012a5c0fcc](https://bsd-hardware.info/?probe=012a5c0fcc) | Nov 14, 2022 |
| Dell          | 06D7TR A00                  | [9e568eb5ee](https://bsd-hardware.info/?probe=9e568eb5ee) | Nov 14, 2022 |
| Unknown       | Unknown                     | [b9994aa302](https://bsd-hardware.info/?probe=b9994aa302) | Nov 14, 2022 |
| MW            | GMLK-2_5G4L                 | [a678226171](https://bsd-hardware.info/?probe=a678226171) | Nov 14, 2022 |
| ASUSTek       | Rampage V EDITION 10        | [443891740b](https://bsd-hardware.info/?probe=443891740b) | Nov 13, 2022 |
| ASUSTek       | H110I-PLUS                  | [0079838512](https://bsd-hardware.info/?probe=0079838512) | Nov 13, 2022 |
| Gigabyte      | J3455N-D3H                  | [86dcacdb40](https://bsd-hardware.info/?probe=86dcacdb40) | Nov 13, 2022 |
| Intel         | Q3XXG4-P V1.0               | [74a717c2e6](https://bsd-hardware.info/?probe=74a717c2e6) | Nov 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | [6f1e732a53](https://bsd-hardware.info/?probe=6f1e732a53) | Nov 13, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [15e38a5ca8](https://bsd-hardware.info/?probe=15e38a5ca8) | Nov 13, 2022 |
| ASUSTek       | P5Q-E                       | [2b1175a4df](https://bsd-hardware.info/?probe=2b1175a4df) | Nov 13, 2022 |
| MSI           | H81M-P33                    | [98b0980231](https://bsd-hardware.info/?probe=98b0980231) | Nov 13, 2022 |
| Protectli     | FW4B Ver                    | [80c0d775a7](https://bsd-hardware.info/?probe=80c0d775a7) | Nov 13, 2022 |
| HP            | 83E1                        | [689b01c121](https://bsd-hardware.info/?probe=689b01c121) | Nov 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [072f2a6c27](https://bsd-hardware.info/?probe=072f2a6c27) | Nov 13, 2022 |
| HP            | 3397                        | [d087515b69](https://bsd-hardware.info/?probe=d087515b69) | Nov 13, 2022 |
| Unknown       | Unknown                     | [838256315e](https://bsd-hardware.info/?probe=838256315e) | Nov 13, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [ee16ad1ffb](https://bsd-hardware.info/?probe=ee16ad1ffb) | Nov 12, 2022 |
| Huanan        | X99-F8D V2.4                | [22ec05d988](https://bsd-hardware.info/?probe=22ec05d988) | Nov 12, 2022 |
| HP            | 8169                        | [e80c8a40a5](https://bsd-hardware.info/?probe=e80c8a40a5) | Nov 12, 2022 |
| Protectli     | FW4B Ver                    | [75b586fdfc](https://bsd-hardware.info/?probe=75b586fdfc) | Nov 12, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [e5b3cb0bcd](https://bsd-hardware.info/?probe=e5b3cb0bcd) | Nov 12, 2022 |
| PC Engines    | APU2                        | [b92faf9ebb](https://bsd-hardware.info/?probe=b92faf9ebb) | Nov 12, 2022 |
| PC Engines    | APU2                        | [34960ed27c](https://bsd-hardware.info/?probe=34960ed27c) | Nov 12, 2022 |
| Unknown       | Unknown                     | [817c69a4b0](https://bsd-hardware.info/?probe=817c69a4b0) | Nov 12, 2022 |
| Lenovo        | ThinkServer RS140           | [0dd05e08aa](https://bsd-hardware.info/?probe=0dd05e08aa) | Nov 12, 2022 |
| MSI           | MS-9897                     | [2527ac44f4](https://bsd-hardware.info/?probe=2527ac44f4) | Nov 12, 2022 |
| Unknown       | Unknown                     | [790e616e22](https://bsd-hardware.info/?probe=790e616e22) | Nov 12, 2022 |
| Dell          | 06D7TR A00                  | [b8ee0562af](https://bsd-hardware.info/?probe=b8ee0562af) | Nov 12, 2022 |
| HP            | 8000 X4                     | [824d5f1ace](https://bsd-hardware.info/?probe=824d5f1ace) | Nov 12, 2022 |
| HP            | 83E1                        | [1760935c91](https://bsd-hardware.info/?probe=1760935c91) | Nov 12, 2022 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | [54dd33114e](https://bsd-hardware.info/?probe=54dd33114e) | Nov 12, 2022 |
| Protectli     | FW6 Ver                     | [23a0c08442](https://bsd-hardware.info/?probe=23a0c08442) | Nov 12, 2022 |
| ASUSTek       | H110I-PLUS                  | [e3161d12c5](https://bsd-hardware.info/?probe=e3161d12c5) | Nov 11, 2022 |
| Unknown       | Unknown                     | [a2b2bb3a77](https://bsd-hardware.info/?probe=a2b2bb3a77) | Nov 11, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | [0fcbc68304](https://bsd-hardware.info/?probe=0fcbc68304) | Nov 11, 2022 |
| HP            | 1998                        | [e397526bac](https://bsd-hardware.info/?probe=e397526bac) | Nov 11, 2022 |
| HP            | 806A                        | [9567b6949c](https://bsd-hardware.info/?probe=9567b6949c) | Nov 11, 2022 |
| MSI           | MS-B1831                    | [0db8392019](https://bsd-hardware.info/?probe=0db8392019) | Nov 11, 2022 |
| Lenovo        | ThinkServer RS140           | [b2b1509adf](https://bsd-hardware.info/?probe=b2b1509adf) | Nov 11, 2022 |
| HP            | 1998                        | [6a38c36a3e](https://bsd-hardware.info/?probe=6a38c36a3e) | Nov 11, 2022 |
| Lenovo        | 30D9 No DPK                 | [bb9cf416c4](https://bsd-hardware.info/?probe=bb9cf416c4) | Nov 11, 2022 |
| HP            | 18E9                        | [b9df70f7eb](https://bsd-hardware.info/?probe=b9df70f7eb) | Nov 11, 2022 |
| ASRock        | J4005B-ITX                  | [554b92cae5](https://bsd-hardware.info/?probe=554b92cae5) | Nov 10, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [569d5b0cca](https://bsd-hardware.info/?probe=569d5b0cca) | Nov 10, 2022 |
| CheckPoint    | PH-30-00                    | [e42768cd01](https://bsd-hardware.info/?probe=e42768cd01) | Nov 10, 2022 |
| ASUSTek       | P5B-Deluxe                  | [87d7d4435b](https://bsd-hardware.info/?probe=87d7d4435b) | Nov 10, 2022 |
| ASUSTek       | P5E-VM SE                   | [910dc6412e](https://bsd-hardware.info/?probe=910dc6412e) | Nov 10, 2022 |
| Unknown       | Unknown                     | [521008f8da](https://bsd-hardware.info/?probe=521008f8da) | Nov 10, 2022 |
| Techvision    | TVI7309X B0                 | [d8030d23b0](https://bsd-hardware.info/?probe=d8030d23b0) | Nov 10, 2022 |
| Gigabyte      | B450M DS3H V2               | [686447d655](https://bsd-hardware.info/?probe=686447d655) | Nov 10, 2022 |
| BESSTAR Te... | TH50                        | [1300135627](https://bsd-hardware.info/?probe=1300135627) | Nov 10, 2022 |
| Cisco         | C170 A0                     | [3ba579a78c](https://bsd-hardware.info/?probe=3ba579a78c) | Nov 10, 2022 |
| AZW           | GK55                        | [d73ef4f4fc](https://bsd-hardware.info/?probe=d73ef4f4fc) | Nov 10, 2022 |
| Dell          | 0M5DCD A00                  | [4bb9a9324b](https://bsd-hardware.info/?probe=4bb9a9324b) | Nov 10, 2022 |
| HP            | 843F                        | [23d8a9bda7](https://bsd-hardware.info/?probe=23d8a9bda7) | Nov 10, 2022 |
| ASUSTek       | PRIME Z490M-PLUS            | [9e3a09a0b3](https://bsd-hardware.info/?probe=9e3a09a0b3) | Nov 10, 2022 |
| Protectli     | FW2B                        | [d15326180f](https://bsd-hardware.info/?probe=d15326180f) | Nov 10, 2022 |
| HP            | 21B4 A01                    | [c064c50fea](https://bsd-hardware.info/?probe=c064c50fea) | Nov 09, 2022 |
| HP            | 21B4 A01                    | [e5c599dfab](https://bsd-hardware.info/?probe=e5c599dfab) | Nov 09, 2022 |
| Gigabyte      | J3455N-D3H                  | [f8e610e161](https://bsd-hardware.info/?probe=f8e610e161) | Nov 09, 2022 |
| Protectli     | FW6 Ver                     | [d75162607b](https://bsd-hardware.info/?probe=d75162607b) | Nov 09, 2022 |
| HP            | 21B4 A01                    | [0a3ba5478b](https://bsd-hardware.info/?probe=0a3ba5478b) | Nov 09, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [c32a7b407d](https://bsd-hardware.info/?probe=c32a7b407d) | Nov 09, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [9945b6b3e7](https://bsd-hardware.info/?probe=9945b6b3e7) | Nov 09, 2022 |
| ASRock        | H570M-ITX/ac                | [8addd09aa7](https://bsd-hardware.info/?probe=8addd09aa7) | Nov 09, 2022 |
| Intel         | SHARKBAY                    | [667abc6f38](https://bsd-hardware.info/?probe=667abc6f38) | Nov 09, 2022 |
| HP            | 1632                        | [96d60382b7](https://bsd-hardware.info/?probe=96d60382b7) | Nov 09, 2022 |
| ASUSTek       | P8H77-I                     | [04ea3cc97d](https://bsd-hardware.info/?probe=04ea3cc97d) | Nov 09, 2022 |
| Gigabyte      | A520M H                     | [a751c4e782](https://bsd-hardware.info/?probe=a751c4e782) | Nov 09, 2022 |
| Unknown       | Unknown                     | [4adc5f7629](https://bsd-hardware.info/?probe=4adc5f7629) | Nov 09, 2022 |
| MSI           | Z370I GAMING PRO CARBON ... | [dd9f7679b5](https://bsd-hardware.info/?probe=dd9f7679b5) | Nov 09, 2022 |
| ASUSTek       | Rampage V EDITION 10        | [5dcd51844e](https://bsd-hardware.info/?probe=5dcd51844e) | Nov 09, 2022 |
| Unknown       | Unknown                     | [47e6a4fa8b](https://bsd-hardware.info/?probe=47e6a4fa8b) | Nov 09, 2022 |
| Dell          | 09KPNV A01                  | [32331d772c](https://bsd-hardware.info/?probe=32331d772c) | Nov 08, 2022 |
| Dell          | 0G261D A00                  | [c3eb1a6caf](https://bsd-hardware.info/?probe=c3eb1a6caf) | Nov 08, 2022 |
| ASRock        | B450 Gaming K4              | [127e0126d1](https://bsd-hardware.info/?probe=127e0126d1) | Nov 08, 2022 |
| Intel         | JSL MRD                     | [5800246e28](https://bsd-hardware.info/?probe=5800246e28) | Nov 08, 2022 |
| ASUSTek       | EX-H110M-V                  | [f9832b4966](https://bsd-hardware.info/?probe=f9832b4966) | Nov 08, 2022 |
| Google        | Zako                        | [5d4b53e2d4](https://bsd-hardware.info/?probe=5d4b53e2d4) | Nov 08, 2022 |
| Dell          | 0F428D A00                  | [0a9ca655d3](https://bsd-hardware.info/?probe=0a9ca655d3) | Nov 08, 2022 |
| Dell          | 0VD5HY A00                  | [1a0df311e3](https://bsd-hardware.info/?probe=1a0df311e3) | Nov 07, 2022 |
| HP            | ProLiant ML310e Gen8        | [cb5bb2c3b5](https://bsd-hardware.info/?probe=cb5bb2c3b5) | Nov 07, 2022 |
| ASUSTek       | A88XM-E                     | [fde1fa45b8](https://bsd-hardware.info/?probe=fde1fa45b8) | Nov 07, 2022 |
| ONDA          | N78G5D3 Ver:5.00            | [009bc44d12](https://bsd-hardware.info/?probe=009bc44d12) | Nov 07, 2022 |
| Acer          | RS880M05                    | [455f9b5026](https://bsd-hardware.info/?probe=455f9b5026) | Nov 07, 2022 |
| HP            | ProLiant MicroServer        | [798219138a](https://bsd-hardware.info/?probe=798219138a) | Nov 07, 2022 |
| HP            | ProLiant MicroServer        | [394e873da0](https://bsd-hardware.info/?probe=394e873da0) | Nov 07, 2022 |
| Unknown       | Unknown                     | [31ff384824](https://bsd-hardware.info/?probe=31ff384824) | Nov 07, 2022 |
| HP            | 8768 A                      | [c8a44e84c6](https://bsd-hardware.info/?probe=c8a44e84c6) | Nov 07, 2022 |
| Unknown       | Unknown                     | [659ec0b365](https://bsd-hardware.info/?probe=659ec0b365) | Nov 07, 2022 |
| PC Engines    | APU2                        | [2a913e7a43](https://bsd-hardware.info/?probe=2a913e7a43) | Nov 06, 2022 |
| PC Engines    | APU2                        | [4fda77e4ca](https://bsd-hardware.info/?probe=4fda77e4ca) | Nov 06, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [70e257e360](https://bsd-hardware.info/?probe=70e257e360) | Nov 06, 2022 |
| Unknown       | Unknown                     | [fed7f55a01](https://bsd-hardware.info/?probe=fed7f55a01) | Nov 06, 2022 |
| HP            | 18E7                        | [6a80fc5241](https://bsd-hardware.info/?probe=6a80fc5241) | Nov 06, 2022 |
| Protectli     | VP2410                      | [de5de1ca21](https://bsd-hardware.info/?probe=de5de1ca21) | Nov 06, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [59b8857bba](https://bsd-hardware.info/?probe=59b8857bba) | Nov 06, 2022 |
| MSI           | H81M-P33                    | [750d2f53c7](https://bsd-hardware.info/?probe=750d2f53c7) | Nov 06, 2022 |
| ASUSTek       | P5Q-E                       | [e427ea787e](https://bsd-hardware.info/?probe=e427ea787e) | Nov 06, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [c6abe84145](https://bsd-hardware.info/?probe=c6abe84145) | Nov 06, 2022 |
| Protectli     | FW6                         | [654e223853](https://bsd-hardware.info/?probe=654e223853) | Nov 06, 2022 |
| Unknown       | Unknown                     | [a33d1a4123](https://bsd-hardware.info/?probe=a33d1a4123) | Nov 06, 2022 |
| Supermicro    | X7SPA-HF                    | [66819692d5](https://bsd-hardware.info/?probe=66819692d5) | Nov 06, 2022 |
| Unknown       | Unknown                     | [6fb650e2e8](https://bsd-hardware.info/?probe=6fb650e2e8) | Nov 06, 2022 |
| Unknown       | Unknown                     | [47efa8b4bc](https://bsd-hardware.info/?probe=47efa8b4bc) | Nov 06, 2022 |
| Unknown       | Unknown                     | [3771535d50](https://bsd-hardware.info/?probe=3771535d50) | Nov 06, 2022 |
| Dell          | OptiPlex 5050               | [cfd442a25d](https://bsd-hardware.info/?probe=cfd442a25d) | Nov 06, 2022 |
| ASUSTek       | PRIME B560M-A               | [95d5580fd7](https://bsd-hardware.info/?probe=95d5580fd7) | Nov 05, 2022 |
| Datto         | SSD                         | [235483110d](https://bsd-hardware.info/?probe=235483110d) | Nov 05, 2022 |
| Protectli     | FW4B Ver                    | [33eea3a422](https://bsd-hardware.info/?probe=33eea3a422) | Nov 05, 2022 |
| ASUSTek       | Z170-K                      | [907b8c2402](https://bsd-hardware.info/?probe=907b8c2402) | Nov 05, 2022 |
| Intel         | SHARKBAY                    | [80a31985d9](https://bsd-hardware.info/?probe=80a31985d9) | Nov 05, 2022 |
| ASUSTek       | Z97-A                       | [6a2b1c8105](https://bsd-hardware.info/?probe=6a2b1c8105) | Nov 05, 2022 |
| Intel         | CRESCENTBAY                 | [0312c464c4](https://bsd-hardware.info/?probe=0312c464c4) | Nov 05, 2022 |
| Protectli     | FW4C Ver                    | [71c0c846f1](https://bsd-hardware.info/?probe=71c0c846f1) | Nov 05, 2022 |
| Dell          | 05GD68 A00                  | [946c93ec7b](https://bsd-hardware.info/?probe=946c93ec7b) | Nov 05, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d27fd3b1a7](https://bsd-hardware.info/?probe=d27fd3b1a7) | Nov 04, 2022 |
| Gigabyte      | H270M-DS3H-CF               | [5784d8bed6](https://bsd-hardware.info/?probe=5784d8bed6) | Nov 04, 2022 |
| HP            | 213D A01                    | [f579ee6387](https://bsd-hardware.info/?probe=f579ee6387) | Nov 04, 2022 |
| ASRock        | H670M-ITX/ax                | [378889e1cd](https://bsd-hardware.info/?probe=378889e1cd) | Nov 04, 2022 |
| MW            | GMLK-2_5G4L                 | [73230496b2](https://bsd-hardware.info/?probe=73230496b2) | Nov 04, 2022 |
| Lenovo        | YangTianM6880N              | [2e9c3b7368](https://bsd-hardware.info/?probe=2e9c3b7368) | Nov 04, 2022 |
| BESSTAR Te... | HM80                        | [d5c5f30a2d](https://bsd-hardware.info/?probe=d5c5f30a2d) | Nov 04, 2022 |
| Unknown       | Unknown                     | [4f58f89a6e](https://bsd-hardware.info/?probe=4f58f89a6e) | Nov 04, 2022 |
| Unknown       | Unknown                     | [58c2f4b4f7](https://bsd-hardware.info/?probe=58c2f4b4f7) | Nov 04, 2022 |
| HP            | 82A2                        | [d83974a5ed](https://bsd-hardware.info/?probe=d83974a5ed) | Nov 03, 2022 |
| HP            | 339A                        | [a1e829d9d9](https://bsd-hardware.info/?probe=a1e829d9d9) | Nov 03, 2022 |
| Unknown       | 1.0                         | [9fe6ac4e68](https://bsd-hardware.info/?probe=9fe6ac4e68) | Nov 03, 2022 |
| PC Engines    | apu4                        | [7ed7638be3](https://bsd-hardware.info/?probe=7ed7638be3) | Nov 03, 2022 |
| AMD           | Inagua CRB                  | [5d27c08853](https://bsd-hardware.info/?probe=5d27c08853) | Nov 03, 2022 |
| ASRock        | G41M-VS3                    | [3021b8ee09](https://bsd-hardware.info/?probe=3021b8ee09) | Nov 03, 2022 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | [7729ec0863](https://bsd-hardware.info/?probe=7729ec0863) | Nov 03, 2022 |
| ASUSTek       | H110M-CS/BR                 | [0841d714d0](https://bsd-hardware.info/?probe=0841d714d0) | Nov 03, 2022 |
| Dell          | 05GD68 A00                  | [8e0c8344af](https://bsd-hardware.info/?probe=8e0c8344af) | Nov 03, 2022 |
| HP            | 843F                        | [f921634ea0](https://bsd-hardware.info/?probe=f921634ea0) | Nov 02, 2022 |
| HP            | 339A                        | [370d93ecde](https://bsd-hardware.info/?probe=370d93ecde) | Nov 02, 2022 |
| Hardkernel    | ODROID-H2                   | [f0e3f3177a](https://bsd-hardware.info/?probe=f0e3f3177a) | Nov 02, 2022 |
| Gigabyte      | Z97X-UD5H                   | [d7141b866c](https://bsd-hardware.info/?probe=d7141b866c) | Nov 02, 2022 |
| ASRock        | G41M-VS3                    | [b6044fb84c](https://bsd-hardware.info/?probe=b6044fb84c) | Nov 02, 2022 |
| HP            | 8053                        | [92583639f6](https://bsd-hardware.info/?probe=92583639f6) | Nov 02, 2022 |
| HP            | 843F                        | [bba76c5ce6](https://bsd-hardware.info/?probe=bba76c5ce6) | Nov 02, 2022 |
| Unknown       | Unknown                     | [bc7a300434](https://bsd-hardware.info/?probe=bc7a300434) | Nov 02, 2022 |
| MSI           | B560M-A PRO                 | [ac1e500e91](https://bsd-hardware.info/?probe=ac1e500e91) | Nov 01, 2022 |
| ASRock        | H670M-ITX/ax                | [bb78d5d8ea](https://bsd-hardware.info/?probe=bb78d5d8ea) | Nov 01, 2022 |
| Cisco         | ASA5512 A0                  | [871a5c449f](https://bsd-hardware.info/?probe=871a5c449f) | Nov 01, 2022 |
| ASRock        | H110 Pro BTC+               | [fb24f0fa6e](https://bsd-hardware.info/?probe=fb24f0fa6e) | Nov 01, 2022 |
| ASUSTek       | K30AM-J_A_F_K31AM-J         | [f587ec97a4](https://bsd-hardware.info/?probe=f587ec97a4) | Nov 01, 2022 |
| Dell          | 05GD68 A00                  | [23483285a8](https://bsd-hardware.info/?probe=23483285a8) | Nov 01, 2022 |
| Cisco         | ASA5512 A0                  | [5758027775](https://bsd-hardware.info/?probe=5758027775) | Oct 31, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [6afa103d09](https://bsd-hardware.info/?probe=6afa103d09) | Oct 31, 2022 |
| ASRockRack    | EPYC3101D4I-2T              | [bb0f8a5bfc](https://bsd-hardware.info/?probe=bb0f8a5bfc) | Oct 31, 2022 |
| Protectli     | FW6 Ver                     | [6f21c02bba](https://bsd-hardware.info/?probe=6f21c02bba) | Oct 31, 2022 |
| Supermicro    | X10DRU-i+                   | [1ffd63a929](https://bsd-hardware.info/?probe=1ffd63a929) | Oct 31, 2022 |
| maiyunda      | www.maiyunda.com            | [4dfd35f622](https://bsd-hardware.info/?probe=4dfd35f622) | Oct 31, 2022 |
| Unknown       | Unknown                     | [9737a80a1c](https://bsd-hardware.info/?probe=9737a80a1c) | Oct 31, 2022 |
| Unknown       | Unknown                     | [c14a3eb06b](https://bsd-hardware.info/?probe=c14a3eb06b) | Oct 31, 2022 |
| Supermicro    | X7SPA-HF                    | [18b3b416ce](https://bsd-hardware.info/?probe=18b3b416ce) | Oct 31, 2022 |
| ASRock        | H110 Pro BTC+               | [20f2ab4251](https://bsd-hardware.info/?probe=20f2ab4251) | Oct 30, 2022 |
| Gigabyte      | Z68XP-UD3                   | [0f22defdb3](https://bsd-hardware.info/?probe=0f22defdb3) | Oct 30, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | [cce93ff157](https://bsd-hardware.info/?probe=cce93ff157) | Oct 30, 2022 |
| Protectli     | FW6 Ver                     | [a52d7dda08](https://bsd-hardware.info/?probe=a52d7dda08) | Oct 30, 2022 |
| Protectli     | FW6 Ver                     | [4aecc55dcc](https://bsd-hardware.info/?probe=4aecc55dcc) | Oct 30, 2022 |
| Thomas-Kre... | LES network 6L              | [0816f2da97](https://bsd-hardware.info/?probe=0816f2da97) | Oct 30, 2022 |
| MSI           | H81M-P33                    | [b67d6a7bb2](https://bsd-hardware.info/?probe=b67d6a7bb2) | Oct 30, 2022 |
| ASUSTek       | P5Q-E                       | [8161bfd24d](https://bsd-hardware.info/?probe=8161bfd24d) | Oct 30, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [a0896f17e4](https://bsd-hardware.info/?probe=a0896f17e4) | Oct 30, 2022 |
| Lenovo        | 3106 SDK0J40705 WIN 3425... | [d20bfb6d64](https://bsd-hardware.info/?probe=d20bfb6d64) | Oct 30, 2022 |
| Unknown       | J3160-4L                    | [e05d9b2d17](https://bsd-hardware.info/?probe=e05d9b2d17) | Oct 30, 2022 |
| HP            | 843B                        | [d7d572f9ad](https://bsd-hardware.info/?probe=d7d572f9ad) | Oct 29, 2022 |
| maiyunda      | www.maiyunda.com            | [ed59c93b79](https://bsd-hardware.info/?probe=ed59c93b79) | Oct 29, 2022 |
| ASRock        | N68-GS4 FX R2.0             | [85be4177d6](https://bsd-hardware.info/?probe=85be4177d6) | Oct 29, 2022 |
| ASRock        | H570M-ITX/ac                | [06a8abdbf4](https://bsd-hardware.info/?probe=06a8abdbf4) | Oct 29, 2022 |
| Unknown       | Unknown                     | [acf41f7000](https://bsd-hardware.info/?probe=acf41f7000) | Oct 29, 2022 |
| Unknown       | Unknown                     | [b8323aa325](https://bsd-hardware.info/?probe=b8323aa325) | Oct 29, 2022 |
| Intel         | Q3XXG4-P V1.0               | [02d617a604](https://bsd-hardware.info/?probe=02d617a604) | Oct 29, 2022 |
| Dell          | 0XCR8D A01                  | [a019244c85](https://bsd-hardware.info/?probe=a019244c85) | Oct 29, 2022 |
| Unknown       | Unknown                     | [3744629487](https://bsd-hardware.info/?probe=3744629487) | Oct 29, 2022 |
| Unknown       | Unknown                     | [9a12cd02f0](https://bsd-hardware.info/?probe=9a12cd02f0) | Oct 28, 2022 |
| YANYU         | R250                        | [f39d55e42d](https://bsd-hardware.info/?probe=f39d55e42d) | Oct 28, 2022 |
| Centerm       | GA690-2 2                   | [9d6c3d67cd](https://bsd-hardware.info/?probe=9d6c3d67cd) | Oct 28, 2022 |
| MSI           | B360I GMAING PRO AC         | [7287c670f0](https://bsd-hardware.info/?probe=7287c670f0) | Oct 28, 2022 |
| Unknown       | Unknown                     | [c483de83a9](https://bsd-hardware.info/?probe=c483de83a9) | Oct 28, 2022 |
| Protectli     | FW4B Ver                    | [6dda683e10](https://bsd-hardware.info/?probe=6dda683e10) | Oct 28, 2022 |
| Unknown       | Unknown                     | [c03e63a0a8](https://bsd-hardware.info/?probe=c03e63a0a8) | Oct 28, 2022 |
| ASUSTek       | P5BV-M                      | [c5277ae3cd](https://bsd-hardware.info/?probe=c5277ae3cd) | Oct 27, 2022 |
| Unknown       | YL-J3160L4                  | [fa8d5e324b](https://bsd-hardware.info/?probe=fa8d5e324b) | Oct 27, 2022 |
| PC Engines    | APU2                        | [0c573848ce](https://bsd-hardware.info/?probe=0c573848ce) | Oct 27, 2022 |
| ASRock        | B550M Phantom Gaming 4      | [16c226553c](https://bsd-hardware.info/?probe=16c226553c) | Oct 27, 2022 |
| Unknown       | Unknown                     | [4e01e68bb2](https://bsd-hardware.info/?probe=4e01e68bb2) | Oct 27, 2022 |
| Unknown       | Unknown                     | [9de7465e6e](https://bsd-hardware.info/?probe=9de7465e6e) | Oct 27, 2022 |
| Dell          | 0WMJ54 A01                  | [f89024b7be](https://bsd-hardware.info/?probe=f89024b7be) | Oct 27, 2022 |
| Protectli     | FW4B Ver                    | [766ee6f4eb](https://bsd-hardware.info/?probe=766ee6f4eb) | Oct 27, 2022 |
| CncTion       | N5105-4L B0                 | [d2adcc8230](https://bsd-hardware.info/?probe=d2adcc8230) | Oct 26, 2022 |
| HP            | 82B4                        | [f3b7970068](https://bsd-hardware.info/?probe=f3b7970068) | Oct 26, 2022 |
| Dell          | 0HD5W2 A00                  | [7b330abf44](https://bsd-hardware.info/?probe=7b330abf44) | Oct 26, 2022 |
| Unknown       | Unknown                     | [a6d41c71fd](https://bsd-hardware.info/?probe=a6d41c71fd) | Oct 26, 2022 |
| Supermicro    | A2SDi-4C-HLN4F              | [f6df7bf1e8](https://bsd-hardware.info/?probe=f6df7bf1e8) | Oct 26, 2022 |
| Dell          | 0HD5W2 A00                  | [84502a19a0](https://bsd-hardware.info/?probe=84502a19a0) | Oct 26, 2022 |
| PC Engines    | APU2                        | [0677b5c196](https://bsd-hardware.info/?probe=0677b5c196) | Oct 25, 2022 |
| Dell          | 05XGC8 A01                  | [97947568ee](https://bsd-hardware.info/?probe=97947568ee) | Oct 25, 2022 |
| PC Engines    | apu1                        | [b8643f364d](https://bsd-hardware.info/?probe=b8643f364d) | Oct 25, 2022 |
| PC Engines    | APU2                        | [d52e3d0ce3](https://bsd-hardware.info/?probe=d52e3d0ce3) | Oct 25, 2022 |
| Gigabyte      | B450M DS3H-CF               | [51ec4ce710](https://bsd-hardware.info/?probe=51ec4ce710) | Oct 24, 2022 |
| Acer          | Veriton X2610G              | [e4289c3f15](https://bsd-hardware.info/?probe=e4289c3f15) | Oct 24, 2022 |
| Unknown       | Unknown                     | [1f2cd1f9ea](https://bsd-hardware.info/?probe=1f2cd1f9ea) | Oct 24, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [079830f938](https://bsd-hardware.info/?probe=079830f938) | Oct 24, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [2fa4641b0e](https://bsd-hardware.info/?probe=2fa4641b0e) | Oct 24, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [09e5063724](https://bsd-hardware.info/?probe=09e5063724) | Oct 24, 2022 |
| Cisco         | ASA5515 A0                  | [3f20d7f9bb](https://bsd-hardware.info/?probe=3f20d7f9bb) | Oct 24, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [eea9a0bef3](https://bsd-hardware.info/?probe=eea9a0bef3) | Oct 24, 2022 |
| Intel         | DQ77MK AAG39642-500         | [0708c0f089](https://bsd-hardware.info/?probe=0708c0f089) | Oct 24, 2022 |
| Intel         | D34010WYK H14771-305        | [5414062624](https://bsd-hardware.info/?probe=5414062624) | Oct 24, 2022 |
| Unknown       | YL-J3160L4                  | [746694bb1d](https://bsd-hardware.info/?probe=746694bb1d) | Oct 24, 2022 |
| MSI           | MAG B550M MORTAR            | [607fcd2571](https://bsd-hardware.info/?probe=607fcd2571) | Oct 24, 2022 |
| ASUSTek       | P5BV-M                      | [f7bfa3deed](https://bsd-hardware.info/?probe=f7bfa3deed) | Oct 23, 2022 |
| CncTion       | N5105-4L B0                 | [6f0d5a7497](https://bsd-hardware.info/?probe=6f0d5a7497) | Oct 23, 2022 |
| Gigabyte      | H61M-DS2 x.x                | [10ea57e48f](https://bsd-hardware.info/?probe=10ea57e48f) | Oct 23, 2022 |
| MSI           | H81M-P33                    | [626f503cad](https://bsd-hardware.info/?probe=626f503cad) | Oct 23, 2022 |
| ASUSTek       | P5Q-E                       | [2b98739799](https://bsd-hardware.info/?probe=2b98739799) | Oct 23, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [56dac6bc80](https://bsd-hardware.info/?probe=56dac6bc80) | Oct 23, 2022 |
| HP            | 843B                        | [9ea2590610](https://bsd-hardware.info/?probe=9ea2590610) | Oct 23, 2022 |
| Unknown       | 1.21                        | [f8a845fcda](https://bsd-hardware.info/?probe=f8a845fcda) | Oct 23, 2022 |
| Unknown       | Unknown                     | [89d0639a68](https://bsd-hardware.info/?probe=89d0639a68) | Oct 23, 2022 |
| CncTion       | N5105-4L B0                 | [d7829c8f35](https://bsd-hardware.info/?probe=d7829c8f35) | Oct 22, 2022 |
| Cisco         | ASA5515 A0                  | [7f848d7c57](https://bsd-hardware.info/?probe=7f848d7c57) | Oct 22, 2022 |
| Techvision    | TVI7309X B0                 | [af3a73431f](https://bsd-hardware.info/?probe=af3a73431f) | Oct 22, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [a1b0ef3b39](https://bsd-hardware.info/?probe=a1b0ef3b39) | Oct 22, 2022 |
| Unknown       | Unknown                     | [410283dd4f](https://bsd-hardware.info/?probe=410283dd4f) | Oct 22, 2022 |
| HP            | 8719                        | [6bca1a0466](https://bsd-hardware.info/?probe=6bca1a0466) | Oct 22, 2022 |
| MW            | GMLK-2_5G4L                 | [172b2c53fe](https://bsd-hardware.info/?probe=172b2c53fe) | Oct 22, 2022 |
| ASUSTek       | P8Z68-V GEN3                | [d7b32200a5](https://bsd-hardware.info/?probe=d7b32200a5) | Oct 22, 2022 |
| Gigabyte      | H61M-DS2 x.x                | [947d061849](https://bsd-hardware.info/?probe=947d061849) | Oct 22, 2022 |
| ASRock        | B250M-HDV                   | [803b44339b](https://bsd-hardware.info/?probe=803b44339b) | Oct 22, 2022 |
| Intel         | D2500CC AAG81477-401        | [f27ff1a7c3](https://bsd-hardware.info/?probe=f27ff1a7c3) | Oct 22, 2022 |
| MSI           | 890GXM-G65                  | [03c116d78f](https://bsd-hardware.info/?probe=03c116d78f) | Oct 22, 2022 |
| Alienware     | 0PGRP5 A01                  | [e34219da0f](https://bsd-hardware.info/?probe=e34219da0f) | Oct 22, 2022 |
| Gigabyte      | 945PLM-S2                   | [ca0d187a0b](https://bsd-hardware.info/?probe=ca0d187a0b) | Oct 22, 2022 |
| Gigabyte      | 945PLM-S2                   | [5b8c853c20](https://bsd-hardware.info/?probe=5b8c853c20) | Oct 22, 2022 |
| Acer          | Revo RN86                   | [692ea69bab](https://bsd-hardware.info/?probe=692ea69bab) | Oct 21, 2022 |
| PC Engines    | APU2                        | [f9ca8e5fdd](https://bsd-hardware.info/?probe=f9ca8e5fdd) | Oct 21, 2022 |
| Intel         | H67SL_VER1.2A               | [a469ad62a4](https://bsd-hardware.info/?probe=a469ad62a4) | Oct 21, 2022 |
| MSI           | B450M PRO-VDH PLUS          | [54e4202bc7](https://bsd-hardware.info/?probe=54e4202bc7) | Oct 21, 2022 |
| PC Engines    | APU2                        | [cf1abf5e46](https://bsd-hardware.info/?probe=cf1abf5e46) | Oct 21, 2022 |
| Protectli     | FW6 Ver                     | [d04ef8c45b](https://bsd-hardware.info/?probe=d04ef8c45b) | Oct 21, 2022 |
| Supermicro    | X8DTH-i/6/iF/6F             | [12f7ac40ac](https://bsd-hardware.info/?probe=12f7ac40ac) | Oct 21, 2022 |
| Dell          | 0FDY5C A00                  | [a47e59ad6b](https://bsd-hardware.info/?probe=a47e59ad6b) | Oct 21, 2022 |
| Dell          | 0FDY5C A00                  | [eb9ffe08e7](https://bsd-hardware.info/?probe=eb9ffe08e7) | Oct 21, 2022 |
| Unknown       | Unknown                     | [d5586487b4](https://bsd-hardware.info/?probe=d5586487b4) | Oct 21, 2022 |
| Protectli     | FW6                         | [528ef94fb5](https://bsd-hardware.info/?probe=528ef94fb5) | Oct 21, 2022 |
| HP            | 18E4                        | [d66ffbbf6d](https://bsd-hardware.info/?probe=d66ffbbf6d) | Oct 21, 2022 |
| ASUSTek       | P10S-I Series               | [ceb58e75b8](https://bsd-hardware.info/?probe=ceb58e75b8) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [7ecffc1ca3](https://bsd-hardware.info/?probe=7ecffc1ca3) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [eb6eda641d](https://bsd-hardware.info/?probe=eb6eda641d) | Oct 20, 2022 |
| Hardkernel    | ODROID-H3                   | [304db9bbbf](https://bsd-hardware.info/?probe=304db9bbbf) | Oct 20, 2022 |
| MSI           | B450M PRO-VDH PLUS          | [c6ee09790d](https://bsd-hardware.info/?probe=c6ee09790d) | Oct 20, 2022 |
| ASRock        | B460M-ITX/ac                | [c1a691f99c](https://bsd-hardware.info/?probe=c1a691f99c) | Oct 20, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [348bef7dba](https://bsd-hardware.info/?probe=348bef7dba) | Oct 20, 2022 |
| PC Engines    | APU2                        | [c2e7b76bdf](https://bsd-hardware.info/?probe=c2e7b76bdf) | Oct 20, 2022 |
| PC Engines    | APU2                        | [ade8432e80](https://bsd-hardware.info/?probe=ade8432e80) | Oct 20, 2022 |
| Unknown       | Unknown                     | [1778396ba9](https://bsd-hardware.info/?probe=1778396ba9) | Oct 20, 2022 |
| Unknown       | Unknown                     | [1188b56e14](https://bsd-hardware.info/?probe=1188b56e14) | Oct 19, 2022 |
| Unknown       | Unknown                     | [915c66f8bd](https://bsd-hardware.info/?probe=915c66f8bd) | Oct 19, 2022 |
| Protectli     | FW6                         | [a7dabc97b0](https://bsd-hardware.info/?probe=a7dabc97b0) | Oct 19, 2022 |
| Quanmax       | spo-book TECH QUAD B1       | [f3db09e0f0](https://bsd-hardware.info/?probe=f3db09e0f0) | Oct 19, 2022 |
| Supermicro    | X11SSL-F                    | [24faa4663c](https://bsd-hardware.info/?probe=24faa4663c) | Oct 19, 2022 |
| Protectli     | FW4B                        | [0acd6e1143](https://bsd-hardware.info/?probe=0acd6e1143) | Oct 19, 2022 |
| Unknown       | MANIFOLD 2-C                | [a6c8096599](https://bsd-hardware.info/?probe=a6c8096599) | Oct 19, 2022 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | [3e2f5956c1](https://bsd-hardware.info/?probe=3e2f5956c1) | Oct 19, 2022 |
| ASUSTek       | E35M1-I DELUXE              | [2fdf1c6db6](https://bsd-hardware.info/?probe=2fdf1c6db6) | Oct 18, 2022 |
| Unknown       | Unknown                     | [20ff21d751](https://bsd-hardware.info/?probe=20ff21d751) | Oct 18, 2022 |
| Lenovo        | 3188 SDK0J40697 WIN 3305... | [f84b205626](https://bsd-hardware.info/?probe=f84b205626) | Oct 18, 2022 |
| Lenovo        | 30D0 NOK                    | [d1fab8bd54](https://bsd-hardware.info/?probe=d1fab8bd54) | Oct 18, 2022 |
| Iomega        | StorCenter Pro px2 SA       | [d4e8f25586](https://bsd-hardware.info/?probe=d4e8f25586) | Oct 18, 2022 |
| Protectli     | FW4B Ver                    | [c75bcb519e](https://bsd-hardware.info/?probe=c75bcb519e) | Oct 18, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [c7971db0b8](https://bsd-hardware.info/?probe=c7971db0b8) | Oct 18, 2022 |
| ASUSTek       | N3050I-C                    | [4a83b0953e](https://bsd-hardware.info/?probe=4a83b0953e) | Oct 18, 2022 |
| CncTion       | N5105-4L B0                 | [45d6590312](https://bsd-hardware.info/?probe=45d6590312) | Oct 18, 2022 |
| Dell          | 02K9CR A02                  | [a5cda6c49e](https://bsd-hardware.info/?probe=a5cda6c49e) | Oct 18, 2022 |
| Supermicro    | X10SLH-N6-ST031             | [2e4cd910d7](https://bsd-hardware.info/?probe=2e4cd910d7) | Oct 17, 2022 |
| PC Engines    | apu4                        | [20cfd8a3c8](https://bsd-hardware.info/?probe=20cfd8a3c8) | Oct 17, 2022 |
| NF541         | 1.0                         | [6f4f72398d](https://bsd-hardware.info/?probe=6f4f72398d) | Oct 17, 2022 |
| Pegatron      | 2ACF                        | [c57cc3a923](https://bsd-hardware.info/?probe=c57cc3a923) | Oct 17, 2022 |
| Intel         | DH57DD AAE82022-202         | [01622a2528](https://bsd-hardware.info/?probe=01622a2528) | Oct 17, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [242e320350](https://bsd-hardware.info/?probe=242e320350) | Oct 17, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [2885a5ce85](https://bsd-hardware.info/?probe=2885a5ce85) | Oct 17, 2022 |
| Yanling       | YL-KBR6L Ver:1.00           | [c3f0ae254e](https://bsd-hardware.info/?probe=c3f0ae254e) | Oct 17, 2022 |
| HP            | 1588h                       | [e78a0308c7](https://bsd-hardware.info/?probe=e78a0308c7) | Oct 16, 2022 |
| Unknown       | Unknown                     | [4fd307fbb4](https://bsd-hardware.info/?probe=4fd307fbb4) | Oct 16, 2022 |
| Techvision    | TVI7309X B0                 | [f7d0616889](https://bsd-hardware.info/?probe=f7d0616889) | Oct 16, 2022 |
| HP            | 8719                        | [87efb126fc](https://bsd-hardware.info/?probe=87efb126fc) | Oct 16, 2022 |
| Dell          | 0200DY A02                  | [d32449b8c4](https://bsd-hardware.info/?probe=d32449b8c4) | Oct 16, 2022 |
| Dell          | 0HD5W2 A00                  | [f80953ee2f](https://bsd-hardware.info/?probe=f80953ee2f) | Oct 16, 2022 |
| Dell          | 0HD5W2 A00                  | [f27ffa7217](https://bsd-hardware.info/?probe=f27ffa7217) | Oct 16, 2022 |
| Yanling       | YL-KBR6L Ver:1.00           | [b4e02e3f51](https://bsd-hardware.info/?probe=b4e02e3f51) | Oct 16, 2022 |
| Hardkernel    | ODROID-H2                   | [77d3019212](https://bsd-hardware.info/?probe=77d3019212) | Oct 16, 2022 |
| Protectli     | FW4B                        | [57ae1d8cda](https://bsd-hardware.info/?probe=57ae1d8cda) | Oct 15, 2022 |
| Unknown       | Unknown                     | [83ceb2fb33](https://bsd-hardware.info/?probe=83ceb2fb33) | Oct 15, 2022 |
| PC Engines    | apu4                        | [cefbafec73](https://bsd-hardware.info/?probe=cefbafec73) | Oct 15, 2022 |
| HP            | 8169                        | [86b1fbf917](https://bsd-hardware.info/?probe=86b1fbf917) | Oct 15, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [76a1007c46](https://bsd-hardware.info/?probe=76a1007c46) | Oct 15, 2022 |
| Protectli     | FW6 Ver                     | [55967e02f6](https://bsd-hardware.info/?probe=55967e02f6) | Oct 15, 2022 |
| TYAN Compu... | Tiger K8W Dual AMD Opter... | [bbd42243ae](https://bsd-hardware.info/?probe=bbd42243ae) | Oct 15, 2022 |
| Techvision    | TVI7309X B0                 | [b02dcbb7b5](https://bsd-hardware.info/?probe=b02dcbb7b5) | Oct 15, 2022 |
| TYAN Compu... | Tiger K8W Dual AMD Opter... | [0e9ac1e935](https://bsd-hardware.info/?probe=0e9ac1e935) | Oct 15, 2022 |
| ASRock        | Q1900M                      | [7d0380e2d0](https://bsd-hardware.info/?probe=7d0380e2d0) | Oct 15, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [a8bdbe4d1b](https://bsd-hardware.info/?probe=a8bdbe4d1b) | Oct 15, 2022 |
| TYAN Compu... | Intel 440BX/GX Rev. 4       | [8d99f317e4](https://bsd-hardware.info/?probe=8d99f317e4) | Oct 15, 2022 |
| Dell          | 0G1548 A00                  | [226af33d5b](https://bsd-hardware.info/?probe=226af33d5b) | Oct 15, 2022 |
| MW            | GMLK-2_5G4L                 | [73960ade29](https://bsd-hardware.info/?probe=73960ade29) | Oct 15, 2022 |
| ASRock        | G41C-GS R2.0                | [06214241b3](https://bsd-hardware.info/?probe=06214241b3) | Oct 15, 2022 |
| Intel         | Q3XXG4-P V1.0               | [5a56504b92](https://bsd-hardware.info/?probe=5a56504b92) | Oct 15, 2022 |
| AZW           | Green G1                    | [f6f16c5141](https://bsd-hardware.info/?probe=f6f16c5141) | Oct 15, 2022 |
| MW            | GMLK-2_5G4L                 | [ae4868c65b](https://bsd-hardware.info/?probe=ae4868c65b) | Oct 15, 2022 |
| Lenovo        | ThinkCentre M57p 6078AJ6    | [a808a7360d](https://bsd-hardware.info/?probe=a808a7360d) | Oct 14, 2022 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [e08c408ced](https://bsd-hardware.info/?probe=e08c408ced) | Oct 14, 2022 |
| Supermicro    | X10SLL-F                    | [3b13ea475b](https://bsd-hardware.info/?probe=3b13ea475b) | Oct 14, 2022 |
| Dell          | 0WMJ54 A01                  | [5acdcd628d](https://bsd-hardware.info/?probe=5acdcd628d) | Oct 14, 2022 |
| PC Engines    | apu1                        | [06debf0076](https://bsd-hardware.info/?probe=06debf0076) | Oct 14, 2022 |
| Dell          | 00V62H A00                  | [17a6b61af7](https://bsd-hardware.info/?probe=17a6b61af7) | Oct 14, 2022 |
| Unknown       | Unknown                     | [6c330d9bab](https://bsd-hardware.info/?probe=6c330d9bab) | Oct 14, 2022 |
| PC Engines    | APU2                        | [856e29140e](https://bsd-hardware.info/?probe=856e29140e) | Oct 14, 2022 |
| PC Engines    | APU2                        | [0e09ac984a](https://bsd-hardware.info/?probe=0e09ac984a) | Oct 14, 2022 |
| Unknown       | J3160-4L                    | [42c01a3aaf](https://bsd-hardware.info/?probe=42c01a3aaf) | Oct 13, 2022 |
| ASUSTek       | P5L-VM 1394                 | [d7c3749eba](https://bsd-hardware.info/?probe=d7c3749eba) | Oct 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | [10358c7207](https://bsd-hardware.info/?probe=10358c7207) | Oct 13, 2022 |
| HP            | 260 G3 DM                   | [3ad5292d71](https://bsd-hardware.info/?probe=3ad5292d71) | Oct 13, 2022 |
| HP            | Compaq nw8440 (RND39ET)     | [55bef385e3](https://bsd-hardware.info/?probe=55bef385e3) | Oct 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [b20b6c7997](https://bsd-hardware.info/?probe=b20b6c7997) | Oct 13, 2022 |
| Unknown       | Unknown                     | [00b5fa7a4e](https://bsd-hardware.info/?probe=00b5fa7a4e) | Oct 13, 2022 |
| ASRock        | B550M Phantom Gaming 4      | [0da821d451](https://bsd-hardware.info/?probe=0da821d451) | Oct 13, 2022 |
| Gigabyte      | J3455N-D3H                  | [9757e40c42](https://bsd-hardware.info/?probe=9757e40c42) | Oct 13, 2022 |
| Unknown       | Unknown                     | [763365591a](https://bsd-hardware.info/?probe=763365591a) | Oct 12, 2022 |
| ASUSTek       | H110M-PLUS                  | [ba30f2772b](https://bsd-hardware.info/?probe=ba30f2772b) | Oct 12, 2022 |
| PC Engines    | APU2                        | [a06a344954](https://bsd-hardware.info/?probe=a06a344954) | Oct 12, 2022 |
| Unknown       | YL-1900L4-V2                | [1f55db62cc](https://bsd-hardware.info/?probe=1f55db62cc) | Oct 12, 2022 |
| HP            | 1589                        | [0696d30d3f](https://bsd-hardware.info/?probe=0696d30d3f) | Oct 12, 2022 |
| ASRock        | H570M-ITX/ac                | [ea8b1fd760](https://bsd-hardware.info/?probe=ea8b1fd760) | Oct 12, 2022 |
| Unknown       | Unknown                     | [7000ef7aeb](https://bsd-hardware.info/?probe=7000ef7aeb) | Oct 12, 2022 |
| Protectli     | FW4B                        | [2fd9fcda8e](https://bsd-hardware.info/?probe=2fd9fcda8e) | Oct 11, 2022 |
| ASUSTek       | P8Z68-V                     | [6674bbf7f3](https://bsd-hardware.info/?probe=6674bbf7f3) | Oct 11, 2022 |
| Unknown       | Unknown                     | [94915735cc](https://bsd-hardware.info/?probe=94915735cc) | Oct 11, 2022 |
| AMD           | Inagua CRB                  | [59c41dcd31](https://bsd-hardware.info/?probe=59c41dcd31) | Oct 11, 2022 |
| MW            | GMLK-2_5G4L                 | [ff2b9a916f](https://bsd-hardware.info/?probe=ff2b9a916f) | Oct 11, 2022 |
| maiyunda      | www.maiyunda.com            | [869687f6f0](https://bsd-hardware.info/?probe=869687f6f0) | Oct 11, 2022 |
| AMD           | Inagua CRB                  | [ff4eccae8a](https://bsd-hardware.info/?probe=ff4eccae8a) | Oct 11, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [9d3b9cb318](https://bsd-hardware.info/?probe=9d3b9cb318) | Oct 11, 2022 |
| ASUSTek       | H110M-CS/BR                 | [097a263bfc](https://bsd-hardware.info/?probe=097a263bfc) | Oct 11, 2022 |
| maiyunda      | www.maiyunda.com            | [f4b5bf9026](https://bsd-hardware.info/?probe=f4b5bf9026) | Oct 11, 2022 |
| Supermicro    | X11SDV-4C-TP8F              | [2cba6fbbb7](https://bsd-hardware.info/?probe=2cba6fbbb7) | Oct 11, 2022 |
| ASRock        | B450M Pro4-F                | [edead8a3ae](https://bsd-hardware.info/?probe=edead8a3ae) | Oct 11, 2022 |
| AZW           | U59                         | [8839497803](https://bsd-hardware.info/?probe=8839497803) | Oct 11, 2022 |
| Unknown       | Unknown                     | [a5cbd6786d](https://bsd-hardware.info/?probe=a5cbd6786d) | Oct 11, 2022 |
| Dell          | 0HD5W2 A00                  | [4fb69eef28](https://bsd-hardware.info/?probe=4fb69eef28) | Oct 11, 2022 |
| Shuttle       | FH170                       | [8fd08beffa](https://bsd-hardware.info/?probe=8fd08beffa) | Oct 10, 2022 |
| PCWare        | IPMH81G1                    | [58b53464d1](https://bsd-hardware.info/?probe=58b53464d1) | Oct 10, 2022 |
| Dell          | 06X1TJ A00                  | [c70e4d6b3c](https://bsd-hardware.info/?probe=c70e4d6b3c) | Oct 10, 2022 |
| NU941         | 1.0                         | [2690c2a8df](https://bsd-hardware.info/?probe=2690c2a8df) | Oct 10, 2022 |
| ASRock        | J4005B-ITX                  | [6cf37e95da](https://bsd-hardware.info/?probe=6cf37e95da) | Oct 10, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [4c9069df20](https://bsd-hardware.info/?probe=4c9069df20) | Oct 10, 2022 |
| HP            | 1495                        | [cfa8ab5df3](https://bsd-hardware.info/?probe=cfa8ab5df3) | Oct 10, 2022 |
| ASRock        | J3355B-ITX                  | [d802705c1d](https://bsd-hardware.info/?probe=d802705c1d) | Oct 10, 2022 |
| Clevo         | R130T                       | [6f8a6bf77c](https://bsd-hardware.info/?probe=6f8a6bf77c) | Oct 10, 2022 |
| Gigabyte      | G31M-S2C                    | [8b8f621562](https://bsd-hardware.info/?probe=8b8f621562) | Oct 10, 2022 |
| Dell          | 06X1TJ A00                  | [21117c0374](https://bsd-hardware.info/?probe=21117c0374) | Oct 10, 2022 |
| CncTion       | Jasper-4L B0                | [53c643dc95](https://bsd-hardware.info/?probe=53c643dc95) | Oct 10, 2022 |
| Unknown       | Unknown                     | [2fc5bd737a](https://bsd-hardware.info/?probe=2fc5bd737a) | Oct 09, 2022 |
| Protectli     | FW1 Ver                     | [1015ef5e66](https://bsd-hardware.info/?probe=1015ef5e66) | Oct 09, 2022 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | [e08e2ca6e0](https://bsd-hardware.info/?probe=e08e2ca6e0) | Oct 09, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | [5d929362ca](https://bsd-hardware.info/?probe=5d929362ca) | Oct 09, 2022 |
| ASRock        | X399 Taichi                 | [c79fa6f001](https://bsd-hardware.info/?probe=c79fa6f001) | Oct 09, 2022 |
| Hardkernel    | ODROID-H2                   | [73c9bfe38b](https://bsd-hardware.info/?probe=73c9bfe38b) | Oct 09, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [e595ade938](https://bsd-hardware.info/?probe=e595ade938) | Oct 09, 2022 |
| ASRock        | J4005B-ITX                  | [0e0ff27c25](https://bsd-hardware.info/?probe=0e0ff27c25) | Oct 09, 2022 |
| MiTAC         | PH11CMI                     | [71802cdcad](https://bsd-hardware.info/?probe=71802cdcad) | Oct 09, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [464739212c](https://bsd-hardware.info/?probe=464739212c) | Oct 08, 2022 |
| HP            | 339A                        | [7ad68046ce](https://bsd-hardware.info/?probe=7ad68046ce) | Oct 08, 2022 |
| HP            | 86FC MVB                    | [56453b00c8](https://bsd-hardware.info/?probe=56453b00c8) | Oct 08, 2022 |
| HP            | 86FC MVB                    | [c542b16d75](https://bsd-hardware.info/?probe=c542b16d75) | Oct 08, 2022 |
| Soekris En... | net6501                     | [1cb23f6bda](https://bsd-hardware.info/?probe=1cb23f6bda) | Oct 08, 2022 |
| Soekris En... | net6501                     | [03ee772b1f](https://bsd-hardware.info/?probe=03ee772b1f) | Oct 08, 2022 |
| Unknown       | Unknown                     | [f31f4c00cd](https://bsd-hardware.info/?probe=f31f4c00cd) | Oct 08, 2022 |
| Unknown       | Unknown                     | [e76890ff26](https://bsd-hardware.info/?probe=e76890ff26) | Oct 08, 2022 |
| Unknown       | Unknown                     | [d6396a74dd](https://bsd-hardware.info/?probe=d6396a74dd) | Oct 08, 2022 |
| HP            | 18E7                        | [35e68316d8](https://bsd-hardware.info/?probe=35e68316d8) | Oct 08, 2022 |
| Lenovo        | ThinkCentre M72e 3664AD9    | [f6fded284d](https://bsd-hardware.info/?probe=f6fded284d) | Oct 08, 2022 |
| Unknown       | Unknown                     | [e4e47282a9](https://bsd-hardware.info/?probe=e4e47282a9) | Oct 08, 2022 |
| Techvision    | TVI7309X B0                 | [384de92279](https://bsd-hardware.info/?probe=384de92279) | Oct 07, 2022 |
| Unknown       | Unknown                     | [d25832111e](https://bsd-hardware.info/?probe=d25832111e) | Oct 07, 2022 |
| Unknown       | Unknown                     | [a34c1b8ccd](https://bsd-hardware.info/?probe=a34c1b8ccd) | Oct 07, 2022 |
| Intel         | SHARKBAY                    | [9d3eed2bec](https://bsd-hardware.info/?probe=9d3eed2bec) | Oct 07, 2022 |
| ASRockRack    | EP2C612D16FM                | [30a582fccb](https://bsd-hardware.info/?probe=30a582fccb) | Oct 07, 2022 |
| Unknown       | Unknown                     | [ad8b88d10b](https://bsd-hardware.info/?probe=ad8b88d10b) | Oct 07, 2022 |
| HP            | ProLiant MicroServer Gen... | [31ce3d5e46](https://bsd-hardware.info/?probe=31ce3d5e46) | Oct 07, 2022 |
| Dell          | 04YP6J A01                  | [ce728798a1](https://bsd-hardware.info/?probe=ce728798a1) | Oct 07, 2022 |
| Intel         | CRESCENTBAY                 | [36fb81bec0](https://bsd-hardware.info/?probe=36fb81bec0) | Oct 07, 2022 |
| YANYU         | H67SL                       | [373902d38b](https://bsd-hardware.info/?probe=373902d38b) | Oct 07, 2022 |
| ASRock        | B75M R2.0                   | [a28ea59f1f](https://bsd-hardware.info/?probe=a28ea59f1f) | Oct 07, 2022 |
| Dell          | 0KYJ8C A02                  | [130a05a115](https://bsd-hardware.info/?probe=130a05a115) | Oct 07, 2022 |
| ASRock        | B450M-HDV                   | [84300e7dcc](https://bsd-hardware.info/?probe=84300e7dcc) | Oct 07, 2022 |
| ADI Engine... | RCC-VE                      | [f6a9012bb2](https://bsd-hardware.info/?probe=f6a9012bb2) | Oct 07, 2022 |
| Jingsha       | x79-P3 by xUz               | [7e24ab5841](https://bsd-hardware.info/?probe=7e24ab5841) | Oct 07, 2022 |
| Jingsha       | x79-P3 by xUz               | [11e04b0c73](https://bsd-hardware.info/?probe=11e04b0c73) | Oct 07, 2022 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | [f521533d51](https://bsd-hardware.info/?probe=f521533d51) | Oct 06, 2022 |
| Unknown       | Unknown                     | [7658e5e20d](https://bsd-hardware.info/?probe=7658e5e20d) | Oct 06, 2022 |
| PC Engines    | apu1                        | [1a8ff34d31](https://bsd-hardware.info/?probe=1a8ff34d31) | Oct 06, 2022 |
| PC Engines    | APU2                        | [02416f3157](https://bsd-hardware.info/?probe=02416f3157) | Oct 06, 2022 |
| Unknown       | Unknown                     | [b889791d9f](https://bsd-hardware.info/?probe=b889791d9f) | Oct 06, 2022 |
| Protectli     | FW4B                        | [89a0375ecb](https://bsd-hardware.info/?probe=89a0375ecb) | Oct 06, 2022 |
| Protectli     | VP4650                      | [c9f3c90f23](https://bsd-hardware.info/?probe=c9f3c90f23) | Oct 06, 2022 |
| YANYU         | ITX-M9F VER:1.1             | [dcb1d22084](https://bsd-hardware.info/?probe=dcb1d22084) | Oct 06, 2022 |
| HP            | 8299                        | [e0f84d2500](https://bsd-hardware.info/?probe=e0f84d2500) | Oct 05, 2022 |
| MW            | GMLK-2_5G4L                 | [7eba59d7ca](https://bsd-hardware.info/?probe=7eba59d7ca) | Oct 05, 2022 |
| CncTion       | J4125-4L-I225               | [eb746dc4a1](https://bsd-hardware.info/?probe=eb746dc4a1) | Oct 05, 2022 |
| Cisco         | ASA5515 A0                  | [bdda6913d3](https://bsd-hardware.info/?probe=bdda6913d3) | Oct 05, 2022 |
| Unknown       | Unknown                     | [7718c8e9ca](https://bsd-hardware.info/?probe=7718c8e9ca) | Oct 05, 2022 |
| Protectli     | FW4B Ver                    | [63b36c077a](https://bsd-hardware.info/?probe=63b36c077a) | Oct 05, 2022 |
| Dell          | 05GD68 A00                  | [ec799eed0c](https://bsd-hardware.info/?probe=ec799eed0c) | Oct 05, 2022 |
| PC Engines    | APU2                        | [47e38f3abe](https://bsd-hardware.info/?probe=47e38f3abe) | Oct 05, 2022 |
| Dell          | 0WMJ54 A00                  | [541e5011d9](https://bsd-hardware.info/?probe=541e5011d9) | Oct 04, 2022 |
| ASUSTek       | P8B75-M                     | [2620fd3511](https://bsd-hardware.info/?probe=2620fd3511) | Oct 04, 2022 |
| Lenovo        | ThinkPad T60 2613CTO        | [cb649b809c](https://bsd-hardware.info/?probe=cb649b809c) | Oct 04, 2022 |
| ASRock        | Z370M-ITX/ac                | [e73c308b5f](https://bsd-hardware.info/?probe=e73c308b5f) | Oct 04, 2022 |
| HP            | 18E7                        | [ad345682d8](https://bsd-hardware.info/?probe=ad345682d8) | Oct 04, 2022 |
| ASRock        | Z77 Extreme4                | [459c674b3b](https://bsd-hardware.info/?probe=459c674b3b) | Oct 04, 2022 |
| MSI           | MS-B1831                    | [7cf04bb1f4](https://bsd-hardware.info/?probe=7cf04bb1f4) | Oct 04, 2022 |
| Unknown       | Unknown                     | [c3608a94b1](https://bsd-hardware.info/?probe=c3608a94b1) | Oct 04, 2022 |
| ASRock        | J3355M                      | [0240dbc2bb](https://bsd-hardware.info/?probe=0240dbc2bb) | Oct 04, 2022 |
| Techvision    | TVI7309X B0                 | [1fd10e86d9](https://bsd-hardware.info/?probe=1fd10e86d9) | Oct 04, 2022 |
| Protectli     | FW4B                        | [36c62d7ffe](https://bsd-hardware.info/?probe=36c62d7ffe) | Oct 03, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [e001150f93](https://bsd-hardware.info/?probe=e001150f93) | Oct 03, 2022 |
| Intel         | Q3XXG4-P V1.0               | [58def8d407](https://bsd-hardware.info/?probe=58def8d407) | Oct 03, 2022 |
| ASRock        | AM1H-ITX                    | [8123ab15ec](https://bsd-hardware.info/?probe=8123ab15ec) | Oct 03, 2022 |
| Unknown       | Unknown                     | [dac9b93a46](https://bsd-hardware.info/?probe=dac9b93a46) | Oct 03, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [bb4a59dd43](https://bsd-hardware.info/?probe=bb4a59dd43) | Oct 03, 2022 |
| maiyunda      | www.maiyunda.com            | [d30234a34e](https://bsd-hardware.info/?probe=d30234a34e) | Oct 03, 2022 |
| IBM           | 9210MML                     | [a6e7d7483f](https://bsd-hardware.info/?probe=a6e7d7483f) | Oct 03, 2022 |
| Unknown       | Unknown                     | [02a9700c12](https://bsd-hardware.info/?probe=02a9700c12) | Oct 03, 2022 |
| Unknown       | Unknown                     | [79060c241b](https://bsd-hardware.info/?probe=79060c241b) | Oct 03, 2022 |
| Dell          | 04YP6J A02                  | [dacf88ac40](https://bsd-hardware.info/?probe=dacf88ac40) | Oct 02, 2022 |
| Unknown       | Unknown                     | [4e021d720f](https://bsd-hardware.info/?probe=4e021d720f) | Oct 02, 2022 |
| Unknown       | Unknown                     | [f2647037ec](https://bsd-hardware.info/?probe=f2647037ec) | Oct 02, 2022 |
| HPE           | ProLiant ML30 Gen10         | [f1b45790d4](https://bsd-hardware.info/?probe=f1b45790d4) | Oct 02, 2022 |
| Biostar       | B450NH                      | [27f932ee37](https://bsd-hardware.info/?probe=27f932ee37) | Oct 02, 2022 |
| ECS           | H61H2-MV                    | [6f40caa9f8](https://bsd-hardware.info/?probe=6f40caa9f8) | Oct 02, 2022 |
| HP            | 8767 A                      | [9d98b3baa4](https://bsd-hardware.info/?probe=9d98b3baa4) | Oct 02, 2022 |
| Gigabyte      | C1037UN-EU                  | [734ff7f48c](https://bsd-hardware.info/?probe=734ff7f48c) | Oct 02, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | [122f6f6837](https://bsd-hardware.info/?probe=122f6f6837) | Oct 02, 2022 |
| HP            | 212B                        | [7bc6506336](https://bsd-hardware.info/?probe=7bc6506336) | Oct 01, 2022 |
| AAEON         | FWS-2350 V1.0               | [00cc54cbad](https://bsd-hardware.info/?probe=00cc54cbad) | Oct 01, 2022 |
| Unknown       | Unknown                     | [01566cd078](https://bsd-hardware.info/?probe=01566cd078) | Oct 01, 2022 |
| Protectli     | FW6 Ver                     | [23450789e4](https://bsd-hardware.info/?probe=23450789e4) | Oct 01, 2022 |
| Unknown       | Unknown                     | [bdabafdcb1](https://bsd-hardware.info/?probe=bdabafdcb1) | Oct 01, 2022 |
| AMI           | PICO PC                     | [ab45092607](https://bsd-hardware.info/?probe=ab45092607) | Oct 01, 2022 |
| Shuttle       | FH61V                       | [305f06cd6a](https://bsd-hardware.info/?probe=305f06cd6a) | Oct 01, 2022 |
| Unknown       | Unknown                     | [c4e771c07c](https://bsd-hardware.info/?probe=c4e771c07c) | Oct 01, 2022 |
| Dell          | 0WMJ54 A01                  | [53dfc5844c](https://bsd-hardware.info/?probe=53dfc5844c) | Oct 01, 2022 |
| BESSTAR Te... | IB9                         | [0cb7bacc88](https://bsd-hardware.info/?probe=0cb7bacc88) | Oct 01, 2022 |
| Protectli     | FW4B Ver                    | [05651f8664](https://bsd-hardware.info/?probe=05651f8664) | Oct 01, 2022 |
| Dell          | 0PC5F7 A00                  | [376550557f](https://bsd-hardware.info/?probe=376550557f) | Sep 30, 2022 |
| Cisco         | ASA5512 A0                  | [5b31d03140](https://bsd-hardware.info/?probe=5b31d03140) | Sep 30, 2022 |
| Jingsha       | x79-P3 by xUz               | [6853ba1191](https://bsd-hardware.info/?probe=6853ba1191) | Sep 30, 2022 |
| ASRockRack    | EPYC3101D4I-2T              | [8e658fe40f](https://bsd-hardware.info/?probe=8e658fe40f) | Sep 30, 2022 |
| Lenovo        | SHARKBAY NOK                | [c1c59c9d14](https://bsd-hardware.info/?probe=c1c59c9d14) | Sep 30, 2022 |
| Dell          | 0T10XW A01                  | [c2ff0bc0b9](https://bsd-hardware.info/?probe=c2ff0bc0b9) | Sep 30, 2022 |
| Dell          | 0WMJ54 A01                  | [30cb759583](https://bsd-hardware.info/?probe=30cb759583) | Sep 30, 2022 |
| Gigabyte      | H510M H                     | [8ad31cc470](https://bsd-hardware.info/?probe=8ad31cc470) | Sep 29, 2022 |
| Intel         | CARLOW                      | [25b6d62332](https://bsd-hardware.info/?probe=25b6d62332) | Sep 29, 2022 |

...


System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| OPNsense 21.7.7   | 201      | 3.08%   |
| helloSystem 0.7.0 | 182      | 2.79%   |
| OPNsense 21.1     | 170      | 2.61%   |
| OPNsense 21.7.1   | 167      | 2.56%   |
| OPNsense 21.1.5   | 167      | 2.56%   |
| OPNsense 22.1     | 166      | 2.54%   |
| OPNsense 21.7.3   | 166      | 2.54%   |
| OPNsense 22.7.4   | 161      | 2.47%   |
| OPNsense 20.7.8   | 159      | 2.44%   |
| OPNsense 21.1.3   | 148      | 2.27%   |
| OPNsense 22.1.6   | 139      | 2.13%   |
| OPNsense 22.1.8   | 137      | 2.1%    |
| OPNsense 21.1.4   | 129      | 1.98%   |
| OPNsense 22.7.9   | 128      | 1.96%   |
| OPNsense 22.7.6   | 128      | 1.96%   |
| OPNsense 22.1.10  | 128      | 1.96%   |
| helloSystem 0.5.0 | 115      | 1.76%   |
| OPNsense 21.1.1   | 111      | 1.7%    |
| OpenBSD 6.8       | 109      | 1.67%   |
| OPNsense 21.7.6   | 99       | 1.52%   |
| OPNsense 21.1.2   | 99       | 1.52%   |
| OPNsense 22.7.8   | 93       | 1.43%   |
| OPNsense 22.1.4   | 93       | 1.43%   |
| OPNsense 22.7     | 91       | 1.39%   |
| helloSystem 0.4.0 | 90       | 1.38%   |
| OPNsense 22.1.2   | 89       | 1.36%   |
| OPNsense 21.7.5   | 88       | 1.35%   |
| OPNsense 21.1.8   | 87       | 1.33%   |
| OPNsense 21.1.7   | 87       | 1.33%   |
| OPNsense 22.7.2   | 86       | 1.32%   |
| OPNsense 22.7.7   | 85       | 1.3%    |
| OPNsense 21.1.6   | 82       | 1.26%   |
| OPNsense 22.1.1   | 78       | 1.2%    |
| FreeBSD 13.0      | 77       | 1.18%   |
| OPNsense 22.1.7   | 76       | 1.16%   |
| FreeBSD 13.1      | 76       | 1.16%   |
| OPNsense 21.7     | 71       | 1.09%   |
| OPNsense 21.7.4   | 70       | 1.07%   |
| OPNsense 21.7.2   | 69       | 1.06%   |
| OPNsense 22.7.10  | 66       | 1.01%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 3104     | 62.61%  |
| FreeBSD     | 860      | 17.35%  |
| helloSystem | 466      | 9.4%    |
| OpenBSD     | 238      | 4.8%    |
| GhostBSD    | 73       | 1.47%   |
| NomadBSD    | 44       | 0.89%   |
| TrueNAS     | 35       | 0.71%   |
| NetBSD      | 35       | 0.71%   |
| pfSense     | 25       | 0.5%    |
| FreeNAS     | 24       | 0.48%   |
| MidnightBSD | 10       | 0.2%    |
| XigmaNAS    | 8        | 0.16%   |
| MyBee       | 8        | 0.16%   |
| DragonFly   | 8        | 0.16%   |
| HardenedBSD | 5        | 0.1%    |
| FuryBSD     | 5        | 0.1%    |
| ClonOS      | 3        | 0.06%   |
| Ting        | 2        | 0.04%   |
| PC-BSD      | 2        | 0.04%   |
| OS108       | 2        | 0.04%   |
| FuguIta     | 1        | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| amd64   | 4794     | 97.6%   |
| arm64   | 49       | 1%      |
| i386    | 44       | 0.9%    |
| arm     | 8        | 0.16%   |
| evbarm  | 5        | 0.1%    |
| sparc64 | 3        | 0.06%   |
| powerpc | 2        | 0.04%   |
| octeon  | 2        | 0.04%   |
| macppc  | 2        | 0.04%   |
| armv7   | 2        | 0.04%   |
| riscv   | 1        | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Console          | 3695     | 73.99%  |
| helloDesktop     | 534      | 10.69%  |
| KDE5             | 152      | 3.04%   |
| XFCE             | 137      | 2.74%   |
| MATE             | 104      | 2.08%   |
| fvwm             | 86       | 1.72%   |
| Openbox          | 63       | 1.26%   |
| GNOME            | 58       | 1.16%   |
| TWM              | 56       | 1.12%   |
| i3               | 26       | 0.52%   |
| Cinnamon         | 11       | 0.22%   |
| Fluxbox          | 10       | 0.2%    |
| AwesomeWM        | 9        | 0.18%   |
| LXQt             | 7        | 0.14%   |
| LXDE             | 6        | 0.12%   |
| Enlightenment    | 6        | 0.12%   |
| Lumina           | 5        | 0.1%    |
| Window Maker     | 3        | 0.06%   |
| GNUstep          | 3        | 0.06%   |
| DWM              | 3        | 0.06%   |
| CDE              | 3        | 0.06%   |
| xfwm             | 2        | 0.04%   |
| xinitrc          | 1        | 0.02%   |
| Xfwm4            | 1        | 0.02%   |
| X-Cinnamon       | 1        | 0.02%   |
| spectrwm         | 1        | 0.02%   |
| Ratpoison        | 1        | 0.02%   |
| plasma           | 1        | 0.02%   |
| Picom            | 1        | 0.02%   |
| PekWM            | 1        | 0.02%   |
| Metacity (Marco) | 1        | 0.02%   |
| KWin             | 1        | 0.02%   |
| filer            | 1        | 0.02%   |
| CTWM             | 1        | 0.02%   |
| Compton          | 1        | 0.02%   |
| bspwm            | 1        | 0.02%   |
| akonadi_newm     | 1        | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 3753     | 76.02%  |
| X11     | 1175     | 23.8%   |
| Wayland | 9        | 0.18%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 4032     | 81.36%  |
| SLiM    | 578      | 11.66%  |
| SDDM    | 137      | 2.76%   |
| LightDM | 113      | 2.28%   |
| XDM     | 56       | 1.13%   |
| GDM     | 38       | 0.77%   |
| Ly      | 2        | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Desktops | Percent |
|------------------|----------|---------|
| Unknown          | 3648     | 72.86%  |
| en_US            | 722      | 14.42%  |
| C                | 373      | 7.45%   |
| ru_RU            | 93       | 1.86%   |
| de_DE            | 34       | 0.68%   |
| fr_FR            | 17       | 0.34%   |
| en_GB            | 14       | 0.28%   |
| es_ES            | 11       | 0.22%   |
| pt_BR            | 9        | 0.18%   |
| it_IT            | 7        | 0.14%   |
| en_AU            | 7        | 0.14%   |
| uk_UA            | 6        | 0.12%   |
| ja_JP            | 6        | 0.12%   |
| zh_CN            | 5        | 0.1%    |
| fi_FI            | 5        | 0.1%    |
| en_CA            | 5        | 0.1%    |
| el_GR            | 4        | 0.08%   |
| sv_SE            | 3        | 0.06%   |
| hu_HU            | 3        | 0.06%   |
| es_AR            | 3        | 0.06%   |
| zh_TW            | 2        | 0.04%   |
| tr_TR            | 2        | 0.04%   |
| ru_RU.KOI8-R     | 2        | 0.04%   |
| pl_PL            | 2        | 0.04%   |
| nb_NO            | 2        | 0.04%   |
| en_IE            | 2        | 0.04%   |
| sv_SE.US-ASCII   | 1        | 0.02%   |
| sl_SI            | 1        | 0.02%   |
| sk_SK            | 1        | 0.02%   |
| nl_NL            | 1        | 0.02%   |
| it_IT.ISO8859-15 | 1        | 0.02%   |
| fr_FR.US-ASCII   | 1        | 0.02%   |
| fr               | 1        | 0.02%   |
| fi_FI.ISO8859-15 | 1        | 0.02%   |
| et_EE.US-ASCII   | 1        | 0.02%   |
| es_MX            | 1        | 0.02%   |
| es_ES.ISO8859-15 | 1        | 0.02%   |
| en_US.utf-8      | 1        | 0.02%   |
| en_US.ISO8859-1  | 1        | 0.02%   |
| en_GB.US-ASCII   | 1        | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 3974     | 79.77%  |
| BIOS | 1008     | 20.23%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ufs     | 2821     | 56.03%  |
| Zfs     | 1817     | 36.09%  |
| Ffs     | 239      | 4.75%   |
| Cd9660  | 141      | 2.8%    |
| Hammer2 | 8        | 0.16%   |
| Unknown | 5        | 0.1%    |
| XXX     | 3        | 0.06%   |
| Nfs     | 1        | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 4387     | 88.59%  |
| MBR     | 484      | 9.77%   |
| Unknown | 74       | 1.49%   |
| BSD     | 7        | 0.14%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| ASUSTek Computer           | 586      | 11.93%  |
| Unknown                    | 542      | 11.03%  |
| Dell                       | 406      | 8.27%   |
| Hewlett-Packard            | 388      | 7.9%    |
| Gigabyte Technology        | 359      | 7.31%   |
| ASRock                     | 351      | 7.15%   |
| Intel                      | 285      | 5.8%    |
| PC Engines                 | 280      | 5.7%    |
| Protectli                  | 245      | 4.99%   |
| MSI                        | 220      | 4.48%   |
| Lenovo                     | 163      | 3.32%   |
| Supermicro                 | 152      | 3.09%   |
| Fujitsu                    | 116      | 2.36%   |
| Shuttle                    | 56       | 1.14%   |
| Acer                       | 42       | 0.86%   |
| Biostar                    | 37       | 0.75%   |
| MW                         | 29       | 0.59%   |
| HARDKERNEL                 | 29       | 0.59%   |
| BESSTAR Tech               | 27       | 0.55%   |
| ASRockRack                 | 27       | 0.55%   |
| Techvision                 | 25       | 0.51%   |
| Foxconn                    | 22       | 0.45%   |
| Deciso                     | 21       | 0.43%   |
| Pegatron                   | 20       | 0.41%   |
| AZW                        | 20       | 0.41%   |
| ShenZhen MinWin Technology | 16       | 0.33%   |
| Apple                      | 15       | 0.31%   |
| YANYU                      | 14       | 0.29%   |
| AAEON                      | 13       | 0.26%   |
| CheckPoint                 | 12       | 0.24%   |
| Seeed Studio               | 11       | 0.22%   |
| ECS                        | 11       | 0.22%   |
| Cisco                      | 11       | 0.22%   |
| AMI                        | 11       | 0.22%   |
| Thomas-Krenn.AG            | 10       | 0.2%    |
| CncTion                    | 10       | 0.2%    |
| Yanling                    | 9        | 0.18%   |
| SeeedStudio                | 9        | 0.18%   |
| NF541                      | 9        | 0.18%   |
| Inventec                   | 9        | 0.18%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Unknown                        | 560      | 11.4%   |
| PC Engines APU2                | 136      | 2.77%   |
| Protectli FW4B                 | 101      | 2.06%   |
| Intel Q3XXG4-P V1.0            | 101      | 2.06%   |
| PC Engines apu4                | 91       | 1.85%   |
| Protectli FW6                  | 75       | 1.53%   |
| ASUS All Series                | 72       | 1.47%   |
| HP t620 PLUS Quad Core TC      | 47       | 0.96%   |
| Fujitsu FUTRO S920             | 46       | 0.94%   |
| Dell OptiPlex 9020             | 38       | 0.77%   |
| Dell OptiPlex 3020             | 33       | 0.67%   |
| Dell OptiPlex 7010             | 30       | 0.61%   |
| MW GMLK-2_5G4L                 | 29       | 0.59%   |
| HARDKERNEL ODROID-H2           | 27       | 0.55%   |
| Techvision TVI7309X            | 25       | 0.51%   |
| Supermicro X9SCL/X9SCM         | 23       | 0.47%   |
| HP ProLiant MicroServer Gen8   | 22       | 0.45%   |
| PC Engines APU3                | 20       | 0.41%   |
| PC Engines APU                 | 20       | 0.41%   |
| HP EliteDesk 800 G1 SFF        | 20       | 0.41%   |
| Protectli VP2410               | 17       | 0.35%   |
| Protectli FW2B                 | 16       | 0.33%   |
| HP ProDesk 600 G1 SFF          | 16       | 0.33%   |
| HP Compaq Elite 8300 SFF       | 16       | 0.33%   |
| Dell OptiPlex 790              | 15       | 0.31%   |
| Intel CRESCENTBAY              | 14       | 0.29%   |
| Dell OptiPlex 990              | 14       | 0.29%   |
| Dell OptiPlex 390              | 13       | 0.26%   |
| Dell OptiPlex 3010             | 13       | 0.26%   |
| HP ProLiant MicroServer        | 12       | 0.24%   |
| Supermicro X7SPA-HF            | 11       | 0.22%   |
| ShenZhen MinWin MW-NANO-APL-4L | 11       | 0.22%   |
| PC Engines apu1                | 11       | 0.22%   |
| Intel MAHOBAY                  | 11       | 0.22%   |
| Dell OptiPlex 9010             | 11       | 0.22%   |
| Dell OptiPlex 3040             | 11       | 0.22%   |
| BESSTAR Tech X35G              | 11       | 0.22%   |
| AZW GK55                       | 11       | 0.22%   |
| HP EliteDesk 800 G2 SFF        | 10       | 0.2%    |
| HP Compaq Pro 6300 SFF         | 10       | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Unknown              | 560      | 11.4%   |
| Dell OptiPlex        | 294      | 5.99%   |
| PC Engines APU2      | 136      | 2.77%   |
| Lenovo ThinkCentre   | 115      | 2.34%   |
| ASUS PRIME           | 107      | 2.18%   |
| Intel Q3XXG4-P       | 102      | 2.08%   |
| Protectli FW4B       | 101      | 2.06%   |
| PC Engines apu4      | 91       | 1.85%   |
| HP Compaq            | 79       | 1.61%   |
| Protectli FW6        | 75       | 1.53%   |
| ASUS All             | 72       | 1.47%   |
| HP ProDesk           | 63       | 1.28%   |
| Fujitsu FUTRO        | 63       | 1.28%   |
| HP EliteDesk         | 58       | 1.18%   |
| HP ProLiant          | 56       | 1.14%   |
| HP t620              | 53       | 1.08%   |
| ASUS ROG             | 51       | 1.04%   |
| ASUS TUF             | 43       | 0.88%   |
| Dell Precision       | 42       | 0.86%   |
| MW GMLK-2            | 29       | 0.59%   |
| HARDKERNEL ODROID-H2 | 27       | 0.55%   |
| Fujitsu ESPRIMO      | 27       | 0.55%   |
| Techvision TVI7309X  | 25       | 0.51%   |
| Acer Aspire          | 25       | 0.51%   |
| Supermicro X9SCL     | 23       | 0.47%   |
| Gigabyte X570        | 21       | 0.43%   |
| Dell PowerEdge       | 21       | 0.43%   |
| ASRock X570          | 21       | 0.43%   |
| PC Engines APU3      | 20       | 0.41%   |
| PC Engines APU       | 20       | 0.41%   |
| Dell Inspiron        | 20       | 0.41%   |
| Deciso Netboard      | 20       | 0.41%   |
| ASUS M5A78L-M        | 19       | 0.39%   |
| Protectli VP2410     | 17       | 0.35%   |
| Protectli FW2B       | 16       | 0.33%   |
| Gigabyte B450M       | 15       | 0.31%   |
| Intel CRESCENTBAY    | 14       | 0.29%   |
| ASUS P8Z77-V         | 13       | 0.26%   |
| Acer Veriton         | 13       | 0.26%   |
| HP Slim              | 12       | 0.24%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 622      | 12.66%  |
| 2019    | 542      | 11.03%  |
| 2020    | 457      | 9.3%    |
| 2016    | 451      | 9.18%   |
| 2014    | 407      | 8.29%   |
| 2021    | 372      | 7.57%   |
| 2013    | 336      | 6.84%   |
| 2012    | 275      | 5.6%    |
| 2017    | 261      | 5.31%   |
| 2011    | 229      | 4.66%   |
| 2022    | 204      | 4.15%   |
| 2015    | 196      | 3.99%   |
| 2010    | 174      | 3.54%   |
| 2009    | 128      | 2.61%   |
| Unknown | 103      | 2.1%    |
| 2008    | 81       | 1.65%   |
| 2007    | 42       | 0.86%   |
| 2006    | 14       | 0.29%   |
| 2004    | 6        | 0.12%   |
| 2005    | 5        | 0.1%    |
| 2003    | 3        | 0.06%   |
| 2002    | 2        | 0.04%   |
| 2001    | 2        | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 4912     | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 4529     | 92.2%   |
| Yes  | 383      | 7.8%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 1732     | 34.58%  |
| 4.01-8.0        | 1164     | 23.24%  |
| 16.01-24.0      | 1053     | 21.02%  |
| 32.01-64.0      | 476      | 9.5%    |
| 2.01-3.0        | 187      | 3.73%   |
| 64.01-256.0     | 163      | 3.25%   |
| 3.01-4.0        | 67       | 1.34%   |
| 24.01-32.0      | 66       | 1.32%   |
| 0.51-1.0        | 40       | 0.8%    |
| 1.01-2.0        | 38       | 0.76%   |
| 0.01-0.5        | 17       | 0.34%   |
| More than 256.0 | 5        | 0.1%    |
| Unknown         | 1        | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 0.01-0.5    | 2626     | 51.3%   |
| 0.51-1.0    | 1446     | 28.25%  |
| 1.01-2.0    | 550      | 10.74%  |
| 2.01-3.0    | 116      | 2.27%   |
| 4.01-8.0    | 105      | 2.05%   |
| 3.01-4.0    | 83       | 1.62%   |
| 8.01-16.0   | 48       | 0.94%   |
| Unknown     | 42       | 0.82%   |
| 0           | 32       | 0.63%   |
| 16.01-24.0  | 26       | 0.51%   |
| 24.01-32.0  | 19       | 0.37%   |
| 32.01-64.0  | 17       | 0.33%   |
| 64.01-256.0 | 9        | 0.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 3314     | 65.42%  |
| 2      | 671      | 13.25%  |
| 0      | 361      | 7.13%   |
| 3      | 280      | 5.53%   |
| 4      | 185      | 3.65%   |
| 5      | 97       | 1.91%   |
| 6      | 59       | 1.16%   |
| 7      | 32       | 0.63%   |
| 8      | 15       | 0.3%    |
| 10     | 10       | 0.2%    |
| 9      | 10       | 0.2%    |
| 12     | 6        | 0.12%   |
| 14     | 4        | 0.08%   |
| 11     | 4        | 0.08%   |
| 17     | 3        | 0.06%   |
| 23     | 2        | 0.04%   |
| 21     | 2        | 0.04%   |
| 19     | 2        | 0.04%   |
| 13     | 2        | 0.04%   |
| 40     | 1        | 0.02%   |
| 27     | 1        | 0.02%   |
| 26     | 1        | 0.02%   |
| 22     | 1        | 0.02%   |
| 18     | 1        | 0.02%   |
| 16     | 1        | 0.02%   |
| 15     | 1        | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 4053     | 81.81%  |
| Yes       | 901      | 18.19%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 4825     | 98.23%  |
| No        | 87       | 1.77%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 3977     | 80.2%   |
| Yes       | 982      | 19.8%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 4373     | 88.54%  |
| Yes       | 566      | 11.46%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 1295     | 26.26%  |
| Germany      | 853      | 17.3%   |
| Russia       | 268      | 5.44%   |
| UK           | 198      | 4.02%   |
| Canada       | 197      | 4%      |
| France       | 193      | 3.91%   |
| Netherlands  | 127      | 2.58%   |
| Australia    | 126      | 2.56%   |
| Poland       | 109      | 2.21%   |
| Switzerland  | 104      | 2.11%   |
| Brazil       | 102      | 2.07%   |
| Austria      | 93       | 1.89%   |
| Italy        | 91       | 1.85%   |
| Sweden       | 78       | 1.58%   |
| Spain        | 78       | 1.58%   |
| China        | 65       | 1.32%   |
| Ukraine      | 51       | 1.03%   |
| Czechia      | 48       | 0.97%   |
| Finland      | 46       | 0.93%   |
| Norway       | 41       | 0.83%   |
| Hungary      | 41       | 0.83%   |
| Taiwan       | 40       | 0.81%   |
| Romania      | 37       | 0.75%   |
| Belgium      | 37       | 0.75%   |
| Denmark      | 33       | 0.67%   |
| India        | 32       | 0.65%   |
| Japan        | 31       | 0.63%   |
| Portugal     | 30       | 0.61%   |
| Indonesia    | 28       | 0.57%   |
| South Korea  | 27       | 0.55%   |
| Mexico       | 27       | 0.55%   |
| New Zealand  | 25       | 0.51%   |
| Greece       | 20       | 0.41%   |
| Thailand     | 19       | 0.39%   |
| Argentina    | 19       | 0.39%   |
| South Africa | 18       | 0.37%   |
| Bulgaria     | 16       | 0.32%   |
| Lithuania    | 15       | 0.3%    |
| Turkey       | 14       | 0.28%   |
| Israel       | 14       | 0.28%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Moscow            | 85       | 1.56%   |
| Berlin            | 82       | 1.5%    |
| Vienna            | 49       | 0.9%    |
| Paris             | 44       | 0.81%   |
| Munich            | 42       | 0.77%   |
| Sydney            | 35       | 0.64%   |
| Hamburg           | 31       | 0.57%   |
| London            | 29       | 0.53%   |
| St Petersburg     | 25       | 0.46%   |
| Frankfurt am Main | 25       | 0.46%   |
| Cologne           | 24       | 0.44%   |
| Amsterdam         | 24       | 0.44%   |
| Denver            | 23       | 0.42%   |
| Zurich            | 22       | 0.4%    |
| Helsinki          | 22       | 0.4%    |
| Melbourne         | 21       | 0.39%   |
| Kyiv              | 20       | 0.37%   |
| Bucharest         | 20       | 0.37%   |
| Toronto           | 19       | 0.35%   |
| Chicago           | 19       | 0.35%   |
| Perth             | 17       | 0.31%   |
| Milan             | 17       | 0.31%   |
| Jakarta           | 17       | 0.31%   |
| Seattle           | 16       | 0.29%   |
| Madrid            | 16       | 0.29%   |
| Warsaw            | 15       | 0.28%   |
| Stuttgart         | 15       | 0.28%   |
| Stockholm         | 15       | 0.28%   |
| New York          | 15       | 0.28%   |
| Ottawa            | 14       | 0.26%   |
| Karlsruhe         | 14       | 0.26%   |
| Brooklyn          | 14       | 0.26%   |
| Brisbane          | 14       | 0.26%   |
| Austin            | 14       | 0.26%   |
| Rochester         | 13       | 0.24%   |
| Portland          | 13       | 0.24%   |
| Montreal          | 13       | 0.24%   |
| Ludwigsburg       | 13       | 0.24%   |
| Krasnodar         | 13       | 0.24%   |
| Bangkok           | 13       | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 892      | 1523   | 14.45%  |
| WDC                 | 874      | 2047   | 14.16%  |
| Seagate             | 718      | 1497   | 11.63%  |
| Kingston            | 512      | 740    | 8.29%   |
| Crucial             | 309      | 460    | 5%      |
| Toshiba             | 255      | 464    | 4.13%   |
| SanDisk             | 249      | 335    | 4.03%   |
| Transcend           | 242      | 363    | 3.92%   |
| Intel               | 207      | 352    | 3.35%   |
| Hoodisk             | 156      | 226    | 2.53%   |
| Phison              | 133      | 187    | 2.15%   |
| Hitachi             | 133      | 245    | 2.15%   |
| A-DATA Technology   | 117      | 170    | 1.9%    |
| China               | 99       | 139    | 1.6%    |
| HGST                | 80       | 181    | 1.3%    |
| OCZ                 | 59       | 78     | 0.96%   |
| SPCC                | 57       | 95     | 0.92%   |
| PNY                 | 53       | 91     | 0.86%   |
| Protectli           | 50       | 81     | 0.81%   |
| Micron Technology   | 49       | 82     | 0.79%   |
| SK hynix            | 45       | 61     | 0.73%   |
| FORESEE             | 40       | 49     | 0.65%   |
| Dogfish             | 39       | 60     | 0.63%   |
| Corsair             | 39       | 65     | 0.63%   |
| Apacer              | 39       | 44     | 0.63%   |
| Intenso             | 35       | 60     | 0.57%   |
| BIWIN               | 35       | 50     | 0.57%   |
| Hewlett-Packard     | 34       | 76     | 0.55%   |
| Innodisk            | 33       | 39     | 0.53%   |
| NVMe                | 31       | 43     | 0.5%    |
| Patriot             | 25       | 37     | 0.4%    |
| LITEONIT            | 24       | 28     | 0.39%   |
| Maxtor              | 23       | 28     | 0.37%   |
| Gigabyte Technology | 22       | 26     | 0.36%   |
| GOODRAM             | 21       | 34     | 0.34%   |
| Silicon Motion      | 20       | 25     | 0.32%   |
| KingSpec            | 20       | 28     | 0.32%   |
| LITEON              | 18       | 26     | 0.29%   |
| Plextor             | 16       | 26     | 0.26%   |
| ShiJi               | 15       | 24     | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Kingston SA400S37240G 240GB     | 76       | 1.1%    |
| Phison SATA SSD 16GB            | 74       | 1.07%   |
| Samsung SSD 850 EVO 250GB       | 67       | 0.97%   |
| Kingston SA400S37120G 120GB     | 63       | 0.91%   |
| Seagate ST500DM002-1BD142 500GB | 56       | 0.81%   |
| Kingston SUV500MS120G 120GB     | 56       | 0.81%   |
| Crucial CT240BX500SSD1 240GB    | 46       | 0.66%   |
| Samsung SSD 860 EVO 500GB       | 45       | 0.65%   |
| Hoodisk SSD 32GB                | 43       | 0.62%   |
| Samsung SSD 860 EVO 250GB       | 42       | 0.61%   |
| Hoodisk SSD 64GB                | 42       | 0.61%   |
| Transcend TS128GMSA230S 128GB   | 41       | 0.59%   |
| Hoodisk SSD 128GB               | 40       | 0.58%   |
| Seagate ST1000DM010-2EP102 1TB  | 38       | 0.55%   |
| Toshiba DT01ACA100 1TB          | 36       | 0.52%   |
| Kingston SUV500MS240G 240GB     | 34       | 0.49%   |
| Samsung SSD 850 EVO 500GB       | 32       | 0.46%   |
| Crucial CT250MX500SSD1 250GB    | 32       | 0.46%   |
| Kingston SV300S37A120G 120GB    | 29       | 0.42%   |
| Crucial CT120BX500SSD1 120GB    | 29       | 0.42%   |
| WDC WD10EZEX-08WN4A0 1TB        | 26       | 0.38%   |
| BIWIN SSD 128GB                 | 26       | 0.38%   |
| Transcend TS64GMSA230S 64GB     | 25       | 0.36%   |
| WDC WD40EFRX-68N32N0 4TB        | 24       | 0.35%   |
| Samsung SSD 970 EVO Plus 500GB  | 24       | 0.35%   |
| Crucial CT500MX500SSD1 500GB    | 23       | 0.33%   |
| WDC WD30EFRX-68EUZN0 3TB        | 22       | 0.32%   |
| Samsung SSD 860 EVO 1TB         | 22       | 0.32%   |
| Samsung SSD 850 EVO 120GB       | 22       | 0.32%   |
| Samsung SSD 840 EVO 120GB       | 22       | 0.32%   |
| PNY CS900 120GB SSD             | 22       | 0.32%   |
| Seagate ST1000DM003-1CH162 1TB  | 21       | 0.3%    |
| Samsung SSD 870 EVO 250GB       | 21       | 0.3%    |
| Samsung SSD 840 EVO 250GB       | 21       | 0.3%    |
| Kingston SKC600MS256G 256GB     | 21       | 0.3%    |
| China SATA SSD 16GB             | 21       | 0.3%    |
| A-DATA SU650 120GB              | 21       | 0.3%    |
| WDC WDS120G2G0A-00JH30 120GB    | 20       | 0.29%   |
| Seagate ST3500418AS 500GB       | 20       | 0.29%   |
| Seagate ST2000DM008-2FR102 2TB  | 20       | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                             | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC                                | 725      | 1732   | 34.46%  |
| Seagate                            | 699      | 1460   | 33.22%  |
| Toshiba                            | 208      | 391    | 9.89%   |
| Hitachi                            | 133      | 245    | 6.32%   |
| Samsung Electronics                | 112      | 158    | 5.32%   |
| HGST                               | 80       | 181    | 3.8%    |
| Maxtor                             | 23       | 28     | 1.09%   |
| Hewlett-Packard                    | 19       | 45     | 0.9%    |
| NVMe                               | 16       | 24     | 0.76%   |
| OPENBSD                            | 15       | 22     | 0.71%   |
| Fujitsu                            | 9        | 11     | 0.43%   |
| Apple                              | 7        | 10     | 0.33%   |
| Dell                               | 6        | 10     | 0.29%   |
| LSI                                | 4        | 7      | 0.19%   |
| HPE                                | 4        | 11     | 0.19%   |
| USB                                | 3        | 3      | 0.14%   |
| HPT                                | 3        | 35     | 0.14%   |
| Generic                            | 3        | 3      | 0.14%   |
| WD MediaMax                        | 2        | 5      | 0.1%    |
| StoreJet                           | 2        | 2      | 0.1%    |
| Multiple                           | 2        | 2      | 0.1%    |
| MaxDigital                         | 2        | 2      | 0.1%    |
| Lexar                              | 2        | 2      | 0.1%    |
| JetFlash                           | 2        | 2      | 0.1%    |
| IBM                                | 2        | 2      | 0.1%    |
| ASMT                               | 2        | 2      | 0.1%    |
| Adaptec                            | 2        | 2      | 0.1%    |
| SSDPR-CX                           | 1        | 1      | 0.05%   |
| SABRENT                            | 1        | 1      | 0.05%   |
| QUANTUM                            | 1        | 2      | 0.05%   |
| Product:              USB DISK 3.0 | 1        | 1      | 0.05%   |
| Product:              USB DISK 2.0 | 1        | 1      | 0.05%   |
| Product:                           | 1        | 1      | 0.05%   |
| MARVELL                            | 1        | 1      | 0.05%   |
| Intenso                            | 1        | 1      | 0.05%   |
| InnoLite                           | 1        | 1      | 0.05%   |
| IBM/Hitachi                        | 1        | 1      | 0.05%   |
| IBM-207x                           | 1        | 1      | 0.05%   |
| General                            | 1        | 1      | 0.05%   |
| ExcelStor Technology               | 1        | 4      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 608      | 992    | 17.29%  |
| Kingston            | 461      | 662    | 13.11%  |
| Crucial             | 268      | 409    | 7.62%   |
| SanDisk             | 247      | 330    | 7.02%   |
| Transcend           | 237      | 356    | 6.74%   |
| Intel               | 171      | 300    | 4.86%   |
| Hoodisk             | 155      | 225    | 4.41%   |
| WDC                 | 110      | 190    | 3.13%   |
| Phison              | 103      | 137    | 2.93%   |
| China               | 98       | 138    | 2.79%   |
| A-DATA Technology   | 97       | 132    | 2.76%   |
| OCZ                 | 59       | 78     | 1.68%   |
| Protectli           | 50       | 81     | 1.42%   |
| PNY                 | 49       | 84     | 1.39%   |
| SPCC                | 47       | 80     | 1.34%   |
| Micron Technology   | 44       | 74     | 1.25%   |
| Toshiba             | 42       | 59     | 1.19%   |
| Dogfish             | 39       | 60     | 1.11%   |
| Apacer              | 39       | 44     | 1.11%   |
| FORESEE             | 38       | 46     | 1.08%   |
| Intenso             | 34       | 59     | 0.97%   |
| BIWIN               | 34       | 49     | 0.97%   |
| Innodisk            | 33       | 39     | 0.94%   |
| Corsair             | 28       | 41     | 0.8%    |
| SK hynix            | 24       | 33     | 0.68%   |
| LITEONIT            | 24       | 28     | 0.68%   |
| Patriot             | 23       | 35     | 0.65%   |
| KingSpec            | 20       | 28     | 0.57%   |
| LITEON              | 17       | 25     | 0.48%   |
| Goodram             | 17       | 29     | 0.48%   |
| ShiJi               | 14       | 23     | 0.4%    |
| Seagate             | 14       | 24     | 0.4%    |
| Plextor             | 14       | 20     | 0.4%    |
| NVMe                | 14       | 17     | 0.4%    |
| Gigabyte Technology | 11       | 14     | 0.31%   |
| Mushkin             | 10       | 12     | 0.28%   |
| KingDian            | 10       | 17     | 0.28%   |
| Kston               | 9        | 13     | 0.26%   |
| Vaseky              | 8        | 11     | 0.23%   |
| Team                | 8        | 9      | 0.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 3183     | 5277   | 58.59%  |
| HDD  | 1632     | 4418   | 30.04%  |
| NVMe | 618      | 1023   | 11.37%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 4239     | 9695   | 87.28%  |
| NVMe | 618      | 1023   | 12.72%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| 0.01-0.5        | 3730     | 6273   | 72.82%  |
| 0.51-1.0        | 704      | 1271   | 13.74%  |
| 1.01-2.0        | 277      | 682    | 5.41%   |
| 3.01-4.0        | 158      | 441    | 3.08%   |
| 4.01-10.0       | 128      | 589    | 2.5%    |
| 2.01-3.0        | 94       | 315    | 1.84%   |
| 10.01-20.0      | 29       | 122    | 0.57%   |
| More than 100.0 | 1        | 1      | 0.02%   |
| 20.01-50.0      | 1        | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 1950     | 38.29%  |
| 1-20           | 773      | 15.18%  |
| 251-500        | 744      | 14.61%  |
| 51-100         | 574      | 11.27%  |
| 21-50          | 527      | 10.35%  |
| 501-1000       | 313      | 6.15%   |
| 1001-2000      | 87       | 1.71%   |
| More than 3000 | 67       | 1.32%   |
| Unknown        | 31       | 0.61%   |
| 2001-3000      | 27       | 0.53%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 4482     | 88.52%  |
| 21-50          | 282      | 5.57%   |
| 51-100         | 103      | 2.03%   |
| 101-250        | 54       | 1.07%   |
| 251-500        | 32       | 0.63%   |
| Unknown        | 31       | 0.61%   |
| 501-1000       | 26       | 0.51%   |
| More than 3000 | 22       | 0.43%   |
| 1001-2000      | 20       | 0.4%    |
| 2001-3000      | 10       | 0.2%    |
| 0              | 1        | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 24       | 38     | 2.82%   |
| Kingston SV300S37A120G 120GB        | 10       | 11     | 1.18%   |
| Seagate ST3500413AS 500GB           | 9        | 23     | 1.06%   |
| WDC WD30EFRX-68EUZN0 3TB            | 7        | 19     | 0.82%   |
| Seagate ST3500418AS 500GB           | 7        | 16     | 0.82%   |
| Kingston SV300S37A60G 64GB          | 7        | 9      | 0.82%   |
| HGST HTS725050A7E630 500GB          | 7        | 16     | 0.82%   |
| WDC WDS240G2G0A-00JH30 240GB        | 6        | 7      | 0.71%   |
| Seagate ST3160815AS 160GB           | 6        | 7      | 0.71%   |
| Samsung Electronics SSD 870 EVO 1TB | 6        | 10     | 0.71%   |
| Samsung Electronics HD501LJ 500GB   | 6        | 7      | 0.71%   |
| Kingston SMS200S3120G 120GB         | 6        | 7      | 0.71%   |
| Crucial CT275MX300SSD1 275GB        | 6        | 9      | 0.71%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 5        | 5      | 0.59%   |
| WDC WD20EFRX-68EUZN0 2TB            | 5        | 12     | 0.59%   |
| Seagate ST380815AS 80GB             | 5        | 5      | 0.59%   |
| Samsung Electronics HD161HJ 160GB   | 5        | 5      | 0.59%   |
| Kingston SMS200S360G 64GB           | 5        | 5      | 0.59%   |
| WDC WD40EFRX-68WT0N0 4TB            | 4        | 8      | 0.47%   |
| Toshiba DT01ACA100 1TB              | 4        | 7      | 0.47%   |
| Seagate ST500LT012-1DG142 500GB     | 4        | 5      | 0.47%   |
| Seagate ST500LM021-1KJ152 500GB     | 4        | 4      | 0.47%   |
| Seagate ST500DM002-1BC142 500GB     | 4        | 4      | 0.47%   |
| Seagate ST3320418AS 320GB           | 4        | 5      | 0.47%   |
| Seagate ST3250310AS 250GB           | 4        | 4      | 0.47%   |
| Seagate ST320LT007-9ZV142 320GB     | 4        | 4      | 0.47%   |
| Seagate ST31000528AS 1TB            | 4        | 5      | 0.47%   |
| Seagate ST2000DL003-9VT166 2TB      | 4        | 12     | 0.47%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 4        | 5      | 0.47%   |
| Seagate ST1000DM003-1CH162 1TB      | 4        | 5      | 0.47%   |
| Samsung Electronics HD322HJ 320GB   | 4        | 4      | 0.47%   |
| Samsung Electronics HD103UJ 1TB     | 4        | 7      | 0.47%   |
| OCZ VERTEX3 120GB                   | 4        | 4      | 0.47%   |
| Kingston SA400S37120G 120GB         | 4        | 4      | 0.47%   |
| Intel SSDSA2M080G2GC 80GB           | 4        | 4      | 0.47%   |
| HGST HTS545032A7E380 320GB          | 4        | 4      | 0.47%   |
| Crucial CT525MX300SSD1 528GB        | 4        | 6      | 0.47%   |
| WDC WDS120G2G0A-00JH30 120GB        | 3        | 4      | 0.35%   |
| WDC WD6400AAKS-22A7B0 640GB         | 3        | 3      | 0.35%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 3        | 3      | 0.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 202      | 308    | 24.88%  |
| WDC                 | 185      | 287    | 22.78%  |
| Samsung Electronics | 75       | 103    | 9.24%   |
| Hitachi             | 50       | 65     | 6.16%   |
| Kingston            | 46       | 58     | 5.67%   |
| Intel               | 40       | 56     | 4.93%   |
| Toshiba             | 39       | 64     | 4.8%    |
| Crucial             | 29       | 43     | 3.57%   |
| HGST                | 21       | 33     | 2.59%   |
| SanDisk             | 14       | 26     | 1.72%   |
| OCZ                 | 12       | 13     | 1.48%   |
| Maxtor              | 11       | 15     | 1.35%   |
| A-DATA Technology   | 11       | 16     | 1.35%   |
| SK hynix            | 7        | 11     | 0.86%   |
| Micron Technology   | 6        | 11     | 0.74%   |
| LITEON              | 5        | 6      | 0.62%   |
| Corsair             | 5        | 9      | 0.62%   |
| Apacer              | 5        | 5      | 0.62%   |
| Hewlett-Packard     | 4        | 8      | 0.49%   |
| VisionTek           | 3        | 7      | 0.37%   |
| KingDian            | 3        | 3      | 0.37%   |
| Dogfish             | 3        | 8      | 0.37%   |
| BIWIN               | 3        | 5      | 0.37%   |
| Transcend           | 2        | 5      | 0.25%   |
| SPCC                | 2        | 4      | 0.25%   |
| MyDigitalSSD        | 2        | 4      | 0.25%   |
| Intenso             | 2        | 2      | 0.25%   |
| XrayDisk            | 1        | 1      | 0.12%   |
| XPG                 | 1        | 1      | 0.12%   |
| WD MediaMax         | 1        | 3      | 0.12%   |
| V-GeN               | 1        | 1      | 0.12%   |
| Terabit             | 1        | 1      | 0.12%   |
| SMI                 | 1        | 1      | 0.12%   |
| ShiJi               | 1        | 1      | 0.12%   |
| PNY                 | 1        | 1      | 0.12%   |
| Plextor             | 1        | 1      | 0.12%   |
| Phison              | 1        | 1      | 0.12%   |
| Netac               | 1        | 1      | 0.12%   |
| Mushkin             | 1        | 1      | 0.12%   |
| LITEONIT            | 1        | 1      | 0.12%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor               | Desktops | Drives | Percent |
|----------------------|----------|--------|---------|
| Seagate              | 201      | 307    | 36.68%  |
| WDC                  | 174      | 273    | 31.75%  |
| Hitachi              | 50       | 65     | 9.12%   |
| Samsung Electronics  | 47       | 59     | 8.58%   |
| Toshiba              | 34       | 59     | 6.2%    |
| HGST                 | 21       | 33     | 3.83%   |
| Maxtor               | 11       | 15     | 2.01%   |
| Hewlett-Packard      | 4        | 8      | 0.73%   |
| WD MediaMax          | 1        | 3      | 0.18%   |
| InnoLite             | 1        | 1      | 0.18%   |
| HPE                  | 1        | 3      | 0.18%   |
| Fujitsu              | 1        | 1      | 0.18%   |
| ExcelStor Technology | 1        | 2      | 0.18%   |
| Cactus               | 1        | 1      | 0.18%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 507      | 830    | 66.02%  |
| SSD  | 256      | 366    | 33.33%  |
| NVMe | 5        | 10     | 0.65%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| WDC WD6400AARS-00Y5B1 640GB     | 1        | 2      | 6.67%   |
| WDC WD3200BPVT-16JJ5T0 320GB    | 1        | 1      | 6.67%   |
| WDC WD3200AAJS-00YZCA0 320GB    | 1        | 1      | 6.67%   |
| WDC WD20EARS-00MVWB0 2TB        | 1        | 1      | 6.67%   |
| WDC WD10SPZX-00Z10T0 1TB        | 1        | 1      | 6.67%   |
| Transcend TS32GSSD370S 32GB     | 1        | 1      | 6.67%   |
| Toshiba MG05ACA800E 8TB         | 1        | 1      | 6.67%   |
| SK hynix SC308 SATA 256GB       | 1        | 1      | 6.67%   |
| Seagate ST3500418AS 500GB       | 1        | 2      | 6.67%   |
| Samsung Electronics HD204UI 2TB | 1        | 2      | 6.67%   |
| Maxtor 6E040L0 41GB             | 1        | 1      | 6.67%   |
| Kingston SV300S37A60G 64GB      | 1        | 1      | 6.67%   |
| HGST HTS725050A7E630 500GB      | 1        | 1      | 6.67%   |
| Crucial M4-CT256M4SSD1 256GB    | 1        | 1      | 6.67%   |
| Crucial CT250P2SSD8 250GB       | 1        | 1      | 6.67%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 6      | 33.33%  |
| Crucial             | 2        | 2      | 13.33%  |
| Transcend           | 1        | 1      | 6.67%   |
| Toshiba             | 1        | 1      | 6.67%   |
| SK hynix            | 1        | 1      | 6.67%   |
| Seagate             | 1        | 2      | 6.67%   |
| Samsung Electronics | 1        | 2      | 6.67%   |
| Maxtor              | 1        | 1      | 6.67%   |
| Kingston            | 1        | 1      | 6.67%   |
| HGST                | 1        | 1      | 6.67%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 4088     | 9143   | 81.35%  |
| Malfunc  | 745      | 1206   | 14.83%  |
| Detected | 177      | 351    | 3.52%   |
| Failed   | 15       | 18     | 0.3%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 3609     | 60.11%  |
| AMD                              | 1136     | 18.92%  |
| Samsung Electronics              | 251      | 4.18%   |
| ASMedia Technology               | 157      | 2.61%   |
| SanDisk                          | 99       | 1.65%   |
| Broadcom / LSI                   | 94       | 1.57%   |
| Marvell Technology Group         | 86       | 1.43%   |
| Phison Electronics               | 74       | 1.23%   |
| Silicon Motion                   | 60       | 1%      |
| Kingston Technology Company      | 57       | 0.95%   |
| Nvidia                           | 50       | 0.83%   |
| JMicron Technology               | 47       | 0.78%   |
| Micron/Crucial Technology        | 42       | 0.7%    |
| ADATA Technology                 | 23       | 0.38%   |
| SK hynix                         | 22       | 0.37%   |
| Silicon Image                    | 20       | 0.33%   |
| VIA Technologies                 | 19       | 0.32%   |
| Chelsio Communications           | 19       | 0.32%   |
| Adaptec                          | 13       | 0.22%   |
| Hewlett-Packard                  | 12       | 0.2%    |
| Seagate Technology               | 11       | 0.18%   |
| KIOXIA                           | 11       | 0.18%   |
| Toshiba                          | 10       | 0.17%   |
| Shenzhen Longsys Electronics     | 10       | 0.17%   |
| Realtek Semiconductor            | 8        | 0.13%   |
| Micron Technology                | 8        | 0.13%   |
| Areca Technology                 | 7        | 0.12%   |
| Integrated Technology Express    | 6        | 0.1%    |
| MAXIO Technology (Hangzhou)      | 5        | 0.08%   |
| Silicon Integrated Systems [SiS] | 4        | 0.07%   |
| Lite-On Technology               | 4        | 0.07%   |
| HighPoint Technologies           | 4        | 0.07%   |
| 3ware                            | 4        | 0.07%   |
| ULi Electronics                  | 3        | 0.05%   |
| Biwin Storage Technology         | 3        | 0.05%   |
| XenSource                        | 2        | 0.03%   |
| Transcend                        | 2        | 0.03%   |
| Solid State Storage Technology   | 2        | 0.03%   |
| Promise Technology               | 2        | 0.03%   |
| Yangtze Memory Technologies      | 1        | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 711      | 10.17%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 381      | 5.45%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 266      | 3.81%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 249      | 3.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 226      | 3.23%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 219      | 3.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 213      | 3.05%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 182      | 2.6%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 167      | 2.39%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 151      | 2.16%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 148      | 2.12%   |
| AMD 400 Series Chipset SATA Controller                                                  | 140      | 2%      |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 132      | 1.89%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 129      | 1.85%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 128      | 1.83%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 126      | 1.8%    |
| AMD FCH SATA Controller [IDE mode]                                                      | 122      | 1.75%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 120      | 1.72%   |
| Intel SATA Controller [RAID mode]                                                       | 111      | 1.59%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 98       | 1.4%    |
| Intel Jasper Lake SATA AHCI Controller                                                  | 76       | 1.09%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 74       | 1.06%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 70       | 1%      |
| Unknown                                                                                 | 70       | 1%      |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 69       | 0.99%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 66       | 0.94%   |
| AMD 500 Series Chipset SATA Controller                                                  | 62       | 0.89%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 60       | 0.86%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 55       | 0.79%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 54       | 0.77%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 53       | 0.76%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 52       | 0.74%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 48       | 0.69%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 46       | 0.66%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 44       | 0.63%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 42       | 0.6%    |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                            | 42       | 0.6%    |
| AMD FCH SATA Controller D                                                               | 41       | 0.59%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 39       | 0.56%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 39       | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 4102     | 68.7%   |
| IDE  | 803      | 13.45%  |
| NVMe | 694      | 11.62%  |
| RAID | 237      | 3.97%   |
| SAS  | 84       | 1.41%   |
| SCSI | 51       | 0.85%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Intel    | 3657     | 74.24%  |
| AMD      | 1188     | 24.12%  |
| ARM      | 55       | 1.12%   |
| Unknown  | 16       | 0.32%   |
| VIA      | 3        | 0.06%   |
| PowerPC  | 2        | 0.04%   |
| Sun      | 1        | 0.02%   |
| Research | 1        | 0.02%   |
| Motorola | 1        | 0.02%   |
| IBM      | 1        | 0.02%   |
| i        | 1        | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| AMD GX-412TC SOC                         | 248      | 4.98%   |
| Intel Celeron J4125 CPU @ 2.00GHz        | 147      | 2.95%   |
| Intel Celeron CPU J3160 @ 1.60GHz        | 140      | 2.81%   |
| Intel Celeron CPU J1900 @ 1.99GHz        | 80       | 1.61%   |
| Intel Celeron N5105 @ 2.00GHz            | 68       | 1.36%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 64       | 1.28%   |
| Intel Core i5-6500 CPU @ 3.20GHz         | 54       | 1.08%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 52       | 1.04%   |
| Intel Core i5-4570 CPU @ 3.20GHz         | 52       | 1.04%   |
| AMD GX-420CA SOC with Radeon HD Graphics | 49       | 0.98%   |
| Intel Atom CPU D525 @ 1.80GHz            | 46       | 0.92%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 42       | 0.84%   |
| Intel Core i7-3770 CPU @ 3.40GHz         | 40       | 0.8%    |
| Intel Celeron CPU 3865U @ 1.80GHz        | 37       | 0.74%   |
| Intel Celeron J4105 CPU @ 1.50GHz        | 36       | 0.72%   |
| Intel Celeron CPU J3455 @ 1.50GHz        | 36       | 0.72%   |
| AMD GX-415GA SOC with Radeon HD Graphics | 34       | 0.68%   |
| AMD Ryzen 5 3600 6-Core Processor        | 33       | 0.66%   |
| AMD G-T40E Processor                     | 31       | 0.62%   |
| Intel Core i3-7100U CPU @ 2.40GHz        | 30       | 0.6%    |
| Intel Atom CPU E3845 @ 1.91GHz           | 30       | 0.6%    |
| Intel Core i5-8250U CPU @ 1.60GHz        | 29       | 0.58%   |
| Intel Core i5-2400 CPU @ 3.10GHz         | 29       | 0.58%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 26       | 0.52%   |
| Intel Core i7-4770 CPU @ 3.40GHz         | 26       | 0.52%   |
| Intel Core i3-4160 CPU @ 3.60GHz         | 25       | 0.5%    |
| Intel Core 2 Duo                         | 25       | 0.5%    |
| AMD Ryzen 7 3700X 8-Core Processor       | 25       | 0.5%    |
| Intel Core i7-7700 CPU @ 3.60GHz         | 24       | 0.48%   |
| Intel Core i3-6100 CPU @ 3.70GHz         | 24       | 0.48%   |
| Intel Core i7-4790 CPU @ 3.60GHz         | 23       | 0.46%   |
| Intel Core i5-3570 CPU @ 3.40GHz         | 22       | 0.44%   |
| Intel Core i3-3220 CPU @ 3.30GHz         | 22       | 0.44%   |
| Intel Celeron J4115 CPU @ 1.80GHz        | 22       | 0.44%   |
| AMD FX-8350 Eight-Core Processor         | 22       | 0.44%   |
| Intel Core i3-4130 CPU @ 3.40GHz         | 21       | 0.42%   |
| Intel Core i3-10100 CPU @ 3.60GHz        | 21       | 0.42%   |
| Intel Celeron CPU J3060 @ 1.60GHz        | 21       | 0.42%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 20       | 0.4%    |
| Intel Celeron CPU N3150 @ 1.60GHz        | 20       | 0.4%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 884      | 17.83%  |
| Intel Celeron           | 821      | 16.56%  |
| Intel Core i3           | 429      | 8.65%   |
| Intel Core i7           | 420      | 8.47%   |
| Intel Xeon              | 389      | 7.85%   |
| AMD GX                  | 388      | 7.83%   |
| Intel Atom              | 203      | 4.09%   |
| AMD Ryzen 5             | 152      | 3.07%   |
| Intel Pentium           | 140      | 2.82%   |
| AMD Ryzen 7             | 129      | 2.6%    |
| Other                   | 99       | 2%      |
| Intel Core 2 Duo        | 95       | 1.92%   |
| AMD FX                  | 80       | 1.61%   |
| Intel Core 2 Quad       | 59       | 1.19%   |
| ARM Cortex              | 50       | 1.01%   |
| AMD G                   | 50       | 1.01%   |
| AMD Ryzen 3             | 47       | 0.95%   |
| AMD Ryzen 9             | 46       | 0.93%   |
| Intel Pentium Dual-Core | 44       | 0.89%   |
| AMD Athlon              | 29       | 0.58%   |
| Intel Pentium Gold      | 22       | 0.44%   |
| Intel Pentium 4         | 22       | 0.44%   |
| AMD Phenom II X4        | 22       | 0.44%   |
| Intel Pentium Silver    | 21       | 0.42%   |
| AMD Athlon 64 X2        | 20       | 0.4%    |
| AMD Ryzen 5 PRO         | 18       | 0.36%   |
| AMD A10                 | 18       | 0.36%   |
| Intel Core 2            | 17       | 0.34%   |
| AMD A4                  | 16       | 0.32%   |
| AMD Ryzen Threadripper  | 15       | 0.3%    |
| Intel Core i9           | 14       | 0.28%   |
| AMD A8                  | 14       | 0.28%   |
| AMD Turion II Neo       | 13       | 0.26%   |
| AMD Phenom II X6        | 12       | 0.24%   |
| Intel Pentium Dual      | 11       | 0.22%   |
| Intel Genuine           | 11       | 0.22%   |
| AMD E                   | 11       | 0.22%   |
| Intel 686-class         | 9        | 0.18%   |
| AMD Athlon II X2        | 9        | 0.18%   |
| AMD Opteron             | 8        | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 2486     | 50.11%  |
| 2       | 1328     | 26.77%  |
| 8       | 249      | 5.02%   |
| Unknown | 241      | 4.86%   |
| 6       | 230      | 4.64%   |
| 12      | 140      | 2.82%   |
| 16      | 138      | 2.78%   |
| 1       | 60       | 1.21%   |
| 24      | 33       | 0.67%   |
| 32      | 19       | 0.38%   |
| 10      | 14       | 0.28%   |
| 3       | 7        | 0.14%   |
| 64      | 3        | 0.06%   |
| 48      | 3        | 0.06%   |
| 28      | 3        | 0.06%   |
| 14      | 3        | 0.06%   |
| 20      | 2        | 0.04%   |
| 36      | 1        | 0.02%   |
| 11      | 1        | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 4730     | 96.14%  |
| Unknown | 123      | 2.5%    |
| 2       | 64       | 1.3%    |
| 4       | 2        | 0.04%   |
| 8       | 1        | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 3145     | 63.7%   |
| 2       | 1527     | 30.93%  |
| Unknown | 265      | 5.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| KabyLake      | 570      | 11.49%  |
| Haswell       | 564      | 11.37%  |
| Silvermont    | 391      | 7.88%   |
| IvyBridge     | 361      | 7.28%   |
| Puma          | 290      | 5.85%   |
| SandyBridge   | 278      | 5.61%   |
| Skylake       | 265      | 5.34%   |
| Unknown       | 238      | 4.8%    |
| Goldmont plus | 221      | 4.46%   |
| Penryn        | 185      | 3.73%   |
| Zen 2         | 144      | 2.9%    |
| Jaguar        | 129      | 2.6%    |
| Zen+          | 118      | 2.38%   |
| Bonnell       | 115      | 2.32%   |
| Goldmont      | 103      | 2.08%   |
| Zen           | 99       | 2%      |
| Piledriver    | 96       | 1.94%   |
| Broadwell     | 95       | 1.92%   |
| Core          | 91       | 1.84%   |
| CometLake     | 89       | 1.79%   |
| Zen 3         | 79       | 1.59%   |
| K10           | 79       | 1.59%   |
| Westmere      | 73       | 1.47%   |
| Nehalem       | 71       | 1.43%   |
| Bobcat        | 69       | 1.39%   |
| NetBurst      | 32       | 0.65%   |
| K8 Hammer     | 30       | 0.6%    |
| Excavator     | 17       | 0.34%   |
| TigerLake     | 16       | 0.32%   |
| Bulldozer     | 14       | 0.28%   |
| Steamroller   | 11       | 0.22%   |
| IceLake       | 11       | 0.22%   |
| K10 Llano     | 6        | 0.12%   |
| P6            | 5        | 0.1%    |
| Geode         | 3        | 0.06%   |
| K6            | 1        | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 2806     | 61.43%  |
| AMD                                          | 798      | 17.47%  |
| Nvidia                                       | 677      | 14.82%  |
| ASPEED Technology                            | 135      | 2.96%   |
| Matrox Electronics Systems                   | 130      | 2.85%   |
| XGI Technology (eXtreme Graphics Innovation) | 8        | 0.18%   |
| VIA Technologies                             | 4        | 0.09%   |
| S3 Graphics                                  | 3        | 0.07%   |
| Silicon Integrated Systems [SiS]             | 2        | 0.04%   |
| Cirrus Logic                                 | 2        | 0.04%   |
| Tseng Labs                                   | 1        | 0.02%   |
| NVidia / SGS Thomson (Joint Venture)         | 1        | 0.02%   |
| 3DLabs                                       | 1        | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 288      | 6.22%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 221      | 4.78%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 211      | 4.56%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 162      | 3.5%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 157      | 3.39%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 153      | 3.31%   |
| Intel HD Graphics 530                                                                    | 146      | 3.15%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 135      | 2.92%   |
| Intel HD Graphics 620                                                                    | 115      | 2.48%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 107      | 2.31%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 92       | 1.99%   |
| Intel JasperLake [UHD Graphics]                                                          | 83       | 1.79%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 80       | 1.73%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 78       | 1.69%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 73       | 1.58%   |
| Intel HD Graphics 630                                                                    | 70       | 1.51%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 69       | 1.49%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 67       | 1.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 65       | 1.4%    |
| Intel HD Graphics 500                                                                    | 62       | 1.34%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 62       | 1.34%   |
| Intel HD Graphics 610                                                                    | 57       | 1.23%   |
| Intel UHD Graphics 620                                                                   | 51       | 1.1%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 51       | 1.1%    |
| AMD Kabini [Radeon HD 8400E]                                                             | 49       | 1.06%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 43       | 0.93%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 42       | 0.91%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 40       | 0.86%   |
| Intel HD Graphics 5500                                                                   | 38       | 0.82%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 37       | 0.8%    |
| AMD Kabini [Radeon HD 8330E]                                                             | 34       | 0.73%   |
| Matrox Electronics Systems MGA G200EH                                                    | 33       | 0.71%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 31       | 0.67%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 30       | 0.65%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 29       | 0.63%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 29       | 0.63%   |
| Intel HD Graphics 6000                                                                   | 29       | 0.63%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 28       | 0.61%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 27       | 0.58%   |
| Nvidia GT218 [GeForce 210]                                                               | 25       | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| 1 x Intel                                | 2634     | 53.16%  |
| 1 x AMD                                  | 754      | 15.22%  |
| 1 x Nvidia                               | 625      | 12.61%  |
| Other                                    | 462      | 9.32%   |
| 1 x ASPEED                               | 128      | 2.58%   |
| 1 x Matrox                               | 127      | 2.56%   |
| 2 x Intel                                | 107      | 2.16%   |
| Intel + Nvidia                           | 39       | 0.79%   |
| Intel + AMD                              | 20       | 0.4%    |
| 2 x AMD                                  | 18       | 0.36%   |
| 1 x XGI                                  | 8        | 0.16%   |
| AMD + Nvidia                             | 5        | 0.1%    |
| 2 x Nvidia                               | 4        | 0.08%   |
| 1 x VIA                                  | 4        | 0.08%   |
| Intel + ASPEED                           | 4        | 0.08%   |
| 1 x S3 Graphics                          | 3        | 0.06%   |
| 1 x SiS                                  | 2        | 0.04%   |
| Nvidia + ASPEED                          | 2        | 0.04%   |
| 1 x Cirrus Logic                         | 2        | 0.04%   |
| AMD + ASPEED                             | 2        | 0.04%   |
| 1 x Tseng Labs                           | 1        | 0.02%   |
| 1 x NVidia / SGS Thomson (Joint Venture) | 1        | 0.02%   |
| Intel + Matrox                           | 1        | 0.02%   |
| AMD + Matrox                             | 1        | 0.02%   |
| 1 x 3DLabs                               | 1        | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 4019     | 81.34%  |
| Unknown     | 509      | 10.3%   |
| Proprietary | 413      | 8.36%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 4303     | 86.82%  |
| 1.01-2.0   | 191      | 3.85%   |
| 0.51-1.0   | 119      | 2.4%    |
| 3.01-4.0   | 112      | 2.26%   |
| 7.01-8.0   | 85       | 1.72%   |
| 0.01-0.5   | 64       | 1.29%   |
| 5.01-6.0   | 50       | 1.01%   |
| 2.01-3.0   | 17       | 0.34%   |
| 8.01-16.0  | 14       | 0.28%   |
| 4.01-5.0   | 1        | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 168      | 15.56%  |
| Dell                 | 148      | 13.7%   |
| Goldstar             | 128      | 11.85%  |
| Acer                 | 75       | 6.94%   |
| Hewlett-Packard      | 69       | 6.39%   |
| BenQ                 | 55       | 5.09%   |
| Philips              | 53       | 4.91%   |
| AOC                  | 53       | 4.91%   |
| Ancor Communications | 44       | 4.07%   |
| Iiyama               | 28       | 2.59%   |
| Lenovo               | 25       | 2.31%   |
| ViewSonic            | 23       | 2.13%   |
| LG Electronics       | 20       | 1.85%   |
| ASUSTek Computer     | 19       | 1.76%   |
| Sony                 | 18       | 1.67%   |
| NEC Computers        | 14       | 1.3%    |
| Eizo                 | 11       | 1.02%   |
| Fujitsu Siemens      | 10       | 0.93%   |
| Vizio                | 7        | 0.65%   |
| Toshiba              | 7        | 0.65%   |
| MSI                  | 7        | 0.65%   |
| Unknown              | 6        | 0.56%   |
| Idek Iiyama          | 6        | 0.56%   |
| Apple                | 5        | 0.46%   |
| Sceptre Tech         | 4        | 0.37%   |
| HannStar             | 4        | 0.37%   |
| Vestel Elektronik    | 3        | 0.28%   |
| Packard Bell         | 3        | 0.28%   |
| Mi                   | 3        | 0.28%   |
| Medion               | 3        | 0.28%   |
| LG Display           | 3        | 0.28%   |
| Insignia             | 3        | 0.28%   |
| Westinghouse         | 2        | 0.19%   |
| VIE                  | 2        | 0.19%   |
| SGT                  | 2        | 0.19%   |
| RTK                  | 2        | 0.19%   |
| Panasonic            | 2        | 0.19%   |
| IOD                  | 2        | 0.19%   |
| HPN                  | 2        | 0.19%   |
| Gateway              | 2        | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                 | 8        | 0.7%    |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch            | 8        | 0.7%    |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                     | 8        | 0.7%    |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch             | 6        | 0.52%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch            | 5        | 0.44%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch     | 4        | 0.35%   |
| Goldstar LCD Monitor GSM5AB8 1920x1080 480x270mm 21.7-inch            | 4        | 0.35%   |
| Dell U2412M DELA07B 1920x1200 520x320mm 24.0-inch                     | 4        | 0.35%   |
| AOC 24G2W1G4 AOC2402 1920x1080 530x300mm 24.0-inch                    | 4        | 0.35%   |
| AOC 24G1WG4 AOC2401 1920x1080 520x290mm 23.4-inch                     | 4        | 0.35%   |
| Ancor Communications ASUS VW199 ACI19ED 1440x900 410x260mm 19.1-inch  | 4        | 0.35%   |
| Acer G227HQL ACR03DE 1920x1080 480x270mm 21.7-inch                    | 4        | 0.35%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch    | 3        | 0.26%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 430x270mm 20.0-inch  | 3        | 0.26%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 520x290mm 23.4-inch     | 3        | 0.26%   |
| Samsung Electronics S22B300 SAM08AC 1920x1080 480x270mm 21.7-inch     | 3        | 0.26%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 890x500mm 40.2-inch | 3        | 0.26%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch     | 3        | 0.26%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch               | 3        | 0.26%   |
| MSI G32C4 MSI3DA6 1920x1080 700x390mm 31.5-inch                       | 3        | 0.26%   |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                 | 3        | 0.26%   |
| Lenovo LEN S24e-10 LEN61CA 1920x1080 530x300mm 24.0-inch              | 3        | 0.26%   |
| Hewlett-Packard LCD Monitor HWP4218 1600x900 440x250mm 19.9-inch      | 3        | 0.26%   |
| Hewlett-Packard 27er HWP3325 1920x1080 600x340mm 27.2-inch            | 3        | 0.26%   |
| Goldstar W2242 GSM4B6F 1680x1050 490x320mm 23.0-inch                  | 3        | 0.26%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch           | 3        | 0.26%   |
| Goldstar 22MP55 GSM5A26 1920x1080 480x270mm 21.7-inch                 | 3        | 0.26%   |
| Dell U2518D DEL413C 2560x1440 550x310mm 24.9-inch                     | 3        | 0.26%   |
| Dell U2415 DELA0BA 1920x1200 520x320mm 24.0-inch                      | 3        | 0.26%   |
| BenQ GW2270 BNQ78DB 1920x1080 480x270mm 21.7-inch                     | 3        | 0.26%   |
| BenQ GW2260 BNQ78C4 1920x1080 480x270mm 21.7-inch                     | 3        | 0.26%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 530x300mm 24.0-inch          | 3        | 0.26%   |
| AOC 22V2WG5 AOC2202 1920x1080 480x270mm 21.7-inch                     | 3        | 0.26%   |
| Ancor Communications ASUS VN247 ACI24C3 1920x1080 520x290mm 23.4-inch | 3        | 0.26%   |
| ViewSonic VX1940w VSC6A20 1680x1050 410x260mm 19.1-inch               | 2        | 0.17%   |
| ViewSonic LCD Monitor VSCFA2B 1920x1080 510x290mm 23.1-inch           | 2        | 0.17%   |
| ViewSonic LCD Monitor VSCC42B 1920x1080 480x270mm 21.7-inch           | 2        | 0.17%   |
| unknown LCD Monitor SAMSUNG 1920x1080                                 | 2        | 0.17%   |
| Sony TV SNY9C01 1360x768                                              | 2        | 0.17%   |
| Sony TV SNY4B03 1920x1080 930x520mm 41.9-inch                         | 2        | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 468      | 43.82%  |
| 1280x1024 (SXGA)   | 91       | 8.52%   |
| 3840x2160 (4K)     | 83       | 7.77%   |
| 2560x1440 (QHD)    | 80       | 7.49%   |
| 1920x1200 (WUXGA)  | 56       | 5.24%   |
| 1680x1050 (WSXGA+) | 49       | 4.59%   |
| 1440x900 (WXGA+)   | 41       | 3.84%   |
| 1366x768 (WXGA)    | 34       | 3.18%   |
| 1600x900 (HD+)     | 33       | 3.09%   |
| 3440x1440          | 20       | 1.87%   |
| Unknown            | 20       | 1.87%   |
| 2560x1080          | 19       | 1.78%   |
| 1360x768           | 11       | 1.03%   |
| 1600x1200          | 10       | 0.94%   |
| 1024x768 (XGA)     | 10       | 0.94%   |
| 1920x540           | 7        | 0.66%   |
| 3840x1080          | 6        | 0.56%   |
| 2560x1600          | 4        | 0.37%   |
| 2048x1152          | 3        | 0.28%   |
| 3840x1600          | 2        | 0.19%   |
| 3840x1200          | 2        | 0.19%   |
| 7680x2160          | 1        | 0.09%   |
| 5760x1256          | 1        | 0.09%   |
| 5760x1200          | 1        | 0.09%   |
| 5760x1080          | 1        | 0.09%   |
| 5120x1440          | 1        | 0.09%   |
| 3640x1920          | 1        | 0.09%   |
| 3600x1080          | 1        | 0.09%   |
| 3520x1200          | 1        | 0.09%   |
| 3360x1050          | 1        | 0.09%   |
| 3200x1080          | 1        | 0.09%   |
| 2806x900           | 1        | 0.09%   |
| 2648x1024          | 1        | 0.09%   |
| 2560x2520          | 1        | 0.09%   |
| 2200x1650          | 1        | 0.09%   |
| 1400x1050          | 1        | 0.09%   |
| 1280x800 (WXGA)    | 1        | 0.09%   |
| 1280x720 (HD)      | 1        | 0.09%   |
| 11520x2160         | 1        | 0.09%   |
| 1024x600           | 1        | 0.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 164      | 15.2%   |
| 21      | 146      | 13.53%  |
| 27      | 137      | 12.7%   |
| Unknown | 113      | 10.47%  |
| 23      | 111      | 10.29%  |
| 19      | 111      | 10.29%  |
| 31      | 47       | 4.36%   |
| 17      | 42       | 3.89%   |
| 18      | 35       | 3.24%   |
| 22      | 30       | 2.78%   |
| 34      | 23       | 2.13%   |
| 20      | 15       | 1.39%   |
| 15      | 10       | 0.93%   |
| 14      | 9        | 0.83%   |
| 40      | 7        | 0.65%   |
| 13      | 7        | 0.65%   |
| 29      | 6        | 0.56%   |
| 16      | 6        | 0.56%   |
| 54      | 5        | 0.46%   |
| 42      | 5        | 0.46%   |
| 25      | 5        | 0.46%   |
| 52      | 4        | 0.37%   |
| 32      | 4        | 0.37%   |
| 28      | 4        | 0.37%   |
| 50      | 3        | 0.28%   |
| 41      | 3        | 0.28%   |
| 39      | 3        | 0.28%   |
| 64      | 2        | 0.19%   |
| 49      | 2        | 0.19%   |
| 46      | 2        | 0.19%   |
| 37      | 2        | 0.19%   |
| 33      | 2        | 0.19%   |
| 26      | 2        | 0.19%   |
| 9       | 2        | 0.19%   |
| 65      | 1        | 0.09%   |
| 57      | 1        | 0.09%   |
| 55      | 1        | 0.09%   |
| 48      | 1        | 0.09%   |
| 47      | 1        | 0.09%   |
| 43      | 1        | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 385      | 36.56%  |
| 401-500     | 286      | 27.16%  |
| Unknown     | 113      | 10.73%  |
| 601-700     | 72       | 6.84%   |
| 301-350     | 58       | 5.51%   |
| 351-400     | 48       | 4.56%   |
| 701-800     | 30       | 2.85%   |
| 1001-1500   | 23       | 2.18%   |
| 201-300     | 14       | 1.33%   |
| 801-900     | 12       | 1.14%   |
| 901-1000    | 10       | 0.95%   |
| 101-200     | 2        | 0.19%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 656      | 63.81%  |
| 16/10   | 128      | 12.45%  |
| Unknown | 90       | 8.75%   |
| 5/4     | 80       | 7.78%   |
| 21/9    | 34       | 3.31%   |
| 4/3     | 22       | 2.14%   |
| 3/2     | 11       | 1.07%   |
| 32/9    | 4        | 0.39%   |
| 6/5     | 3        | 0.29%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 375      | 35.38%  |
| 301-350        | 141      | 13.3%   |
| 151-200        | 136      | 12.83%  |
| Unknown        | 113      | 10.66%  |
| 351-500        | 81       | 7.64%   |
| 141-150        | 69       | 6.51%   |
| 251-300        | 63       | 5.94%   |
| 501-1000       | 27       | 2.55%   |
| More than 1000 | 18       | 1.7%    |
| 101-110        | 9        | 0.85%   |
| 81-90          | 7        | 0.66%   |
| 121-130        | 6        | 0.57%   |
| 91-100         | 6        | 0.57%   |
| 111-120        | 4        | 0.38%   |
| 131-140        | 2        | 0.19%   |
| 61-70          | 1        | 0.09%   |
| 41-50          | 1        | 0.09%   |
| 1-40           | 1        | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 608      | 58.13%  |
| 101-120       | 224      | 21.41%  |
| Unknown       | 113      | 10.8%   |
| 121-160       | 48       | 4.59%   |
| 161-240       | 34       | 3.25%   |
| 1-50          | 18       | 1.72%   |
| More than 240 | 1        | 0.1%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 3910     | 78.94%  |
| 1     | 919      | 18.55%  |
| 2     | 111      | 2.24%   |
| 3     | 13       | 0.26%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 3537     | 53.63%  |
| Realtek Semiconductor           | 1949     | 29.55%  |
| Qualcomm Atheros                | 299      | 4.53%   |
| Broadcom                        | 277      | 4.2%    |
| Ralink Technology               | 38       | 0.58%   |
| IMC Networks                    | 38       | 0.58%   |
| Mellanox Technologies           | 34       | 0.52%   |
| Marvell Technology Group        | 34       | 0.52%   |
| Ralink                          | 33       | 0.5%    |
| D-Link System                   | 29       | 0.44%   |
| TP-Link                         | 24       | 0.36%   |
| Chelsio Communications          | 24       | 0.36%   |
| U-Blox                          | 18       | 0.27%   |
| VIA Technologies                | 16       | 0.24%   |
| American Megatrends             | 15       | 0.23%   |
| MediaTek                        | 14       | 0.21%   |
| Aquantia                        | 14       | 0.21%   |
| Solarflare Communications       | 13       | 0.2%    |
| Qualcomm Atheros Communications | 13       | 0.2%    |
| 3Com                            | 12       | 0.18%   |
| Huawei Technologies             | 11       | 0.17%   |
| Edimax Technology               | 9        | 0.14%   |
| ASUSTek Computer                | 8        | 0.12%   |
| Seeed Technology                | 7        | 0.11%   |
| Nvidia                          | 7        | 0.11%   |
| ZTE WCDMA Technologies MSM      | 6        | 0.09%   |
| Emulex                          | 6        | 0.09%   |
| Xiaomi                          | 5        | 0.08%   |
| Microchip Technology            | 5        | 0.08%   |
| ICS Advent                      | 5        | 0.08%   |
| Apple                           | 5        | 0.08%   |
| Samsung Electronics             | 4        | 0.06%   |
| Qualcomm                        | 4        | 0.06%   |
| QLogic                          | 4        | 0.06%   |
| Accton Technology               | 4        | 0.06%   |
| NetXen Incorporated             | 3        | 0.05%   |
| Davicom Semiconductor           | 3        | 0.05%   |
| Arduino SA                      | 3        | 0.05%   |
| ADMtek                          | 3        | 0.05%   |
| Tehuti Networks                 | 2        | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 1675     | 21.08%  |
| Intel I211 Gigabit Network Connection                                         | 829      | 10.43%  |
| Intel I210 Gigabit Network Connection                                         | 451      | 5.68%   |
| Intel 82574L Gigabit Network Connection                                       | 331      | 4.17%   |
| Intel I350 Gigabit Network Connection                                         | 254      | 3.2%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 252      | 3.17%   |
| Intel Ethernet Connection I217-LM                                             | 174      | 2.19%   |
| Intel Ethernet Controller I225-V                                              | 167      | 2.1%    |
| Intel 82583V Gigabit Network Connection                                       | 151      | 1.9%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 132      | 1.66%   |
| Realtek RTL8125 2.5GbE Controller                                             | 130      | 1.64%   |
| Intel 82580 Gigabit Network Connection                                        | 127      | 1.6%    |
| Intel 82576 Gigabit Network Connection                                        | 126      | 1.59%   |
| Intel Wi-Fi 6 AX200                                                           | 99       | 1.25%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 95       | 1.2%    |
| Intel Ethernet Connection (2) I219-V                                          | 88       | 1.11%   |
| Intel Ethernet Connection (2) I219-LM                                         | 84       | 1.06%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 73       | 0.92%   |
| Intel 82579V Gigabit Network Connection                                       | 61       | 0.77%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 57       | 0.72%   |
| Intel Ethernet Connection I217-V                                              | 51       | 0.64%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 45       | 0.57%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 44       | 0.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 44       | 0.55%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 44       | 0.55%   |
| Intel Ethernet Controller I226-V                                              | 40       | 0.5%    |
| Intel Ethernet Connection (7) I219-V                                          | 40       | 0.5%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 39       | 0.49%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 34       | 0.43%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                          | 34       | 0.43%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 33       | 0.42%   |
| Intel Wireless 7260                                                           | 33       | 0.42%   |
| Intel Wireless 3165                                                           | 33       | 0.42%   |
| Intel Ethernet Connection (7) I219-LM                                         | 32       | 0.4%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 29       | 0.36%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 28       | 0.35%   |
| Intel Ethernet Controller X550                                                | 27       | 0.34%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 27       | 0.34%   |
| Intel Ethernet Connection X553 1GbE                                           | 26       | 0.33%   |
| Intel Ethernet Connection (2) I218-V                                          | 26       | 0.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 383      | 37.15%  |
| Qualcomm Atheros                      | 212      | 20.56%  |
| Realtek Semiconductor                 | 185      | 17.94%  |
| Broadcom                              | 57       | 5.53%   |
| Ralink Technology                     | 38       | 3.69%   |
| IMC Networks                          | 38       | 3.69%   |
| Ralink                                | 33       | 3.2%    |
| TP-Link                               | 24       | 2.33%   |
| Qualcomm Atheros Communications       | 13       | 1.26%   |
| MediaTek                              | 12       | 1.16%   |
| Edimax Technology                     | 9        | 0.87%   |
| ASUSTek Computer                      | 8        | 0.78%   |
| NetGear                               | 2        | 0.19%   |
| D-Link System                         | 2        | 0.19%   |
| D-Link                                | 2        | 0.19%   |
| ZyXEL Communications                  | 1        | 0.1%    |
| Sitecom Europe                        | 1        | 0.1%    |
| Sierra Wireless                       | 1        | 0.1%    |
| Qcom                                  | 1        | 0.1%    |
| Mercucys                              | 1        | 0.1%    |
| Linksys                               | 1        | 0.1%    |
| Gemtek                                | 1        | 0.1%    |
| Dell                                  | 1        | 0.1%    |
| Belkin Components                     | 1        | 0.1%    |
| Atheros                               | 1        | 0.1%    |
| Accton Technology                     | 1        | 0.1%    |
| AboCom Systems                        | 1        | 0.1%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                             | 99       | 9.53%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)  | 45       | 4.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 39       | 3.75%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card            | 34       | 3.27%   |
| Intel Wireless 7260                                             | 33       | 3.18%   |
| Intel Wireless 3165                                             | 33       | 3.18%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                | 29       | 2.79%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter             | 28       | 2.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 25       | 2.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                | 25       | 2.41%   |
| Intel Wireless-AC 9260                                          | 22       | 2.12%   |
| Intel Wireless 7265                                             | 20       | 1.92%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                | 18       | 1.73%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)  | 18       | 1.73%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)  | 18       | 1.73%   |
| Intel Wireless 3160                                             | 18       | 1.73%   |
| Ralink RT5370 Wireless Adapter                                  | 17       | 1.64%   |
| Intel Gemini Lake PCH CNVi WiFi                                 | 17       | 1.64%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter        | 16       | 1.54%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                          | 16       | 1.54%   |
| Realtek RTL8188EE Wireless Network Adapter                      | 13       | 1.25%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter | 13       | 1.25%   |
| Intel Centrino Advanced-N 6235                                  | 13       | 1.25%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter              | 13       | 1.25%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter        | 12       | 1.15%   |
| Broadcom BCM43228 802.11a/b/g/n                                 | 11       | 1.06%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                 | 10       | 0.96%   |
| Qualcomm Atheros AR9271 802.11n                                 | 10       | 0.96%   |
| Intel Wireless 8265 / 8275                                      | 10       | 0.96%   |
| Intel Wireless 8260                                             | 9        | 0.87%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                 | 8        | 0.77%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                         | 8        | 0.77%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter      | 8        | 0.77%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter      | 8        | 0.77%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                         | 8        | 0.77%   |
| Intel Cannon Lake PCH CNVi WiFi                                 | 8        | 0.77%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter              | 8        | 0.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter        | 7        | 0.67%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                      | 7        | 0.67%   |
| Ralink RT5572 Wireless Adapter                                  | 7        | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Intel                             | 3390     | 58.66%  |
| Realtek Semiconductor             | 1860     | 32.19%  |
| Broadcom                          | 221      | 3.82%   |
| Qualcomm Atheros                  | 91       | 1.57%   |
| Marvell Technology Group          | 34       | 0.59%   |
| D-Link System                     | 25       | 0.43%   |
| Chelsio Communications            | 19       | 0.33%   |
| VIA Technologies                  | 16       | 0.28%   |
| American Megatrends               | 15       | 0.26%   |
| Aquantia                          | 14       | 0.24%   |
| Solarflare Communications         | 13       | 0.22%   |
| 3Com                              | 11       | 0.19%   |
| Nvidia                            | 7        | 0.12%   |
| Xiaomi                            | 5        | 0.09%   |
| ICS Advent                        | 5        | 0.09%   |
| Emulex                            | 5        | 0.09%   |
| Samsung Electronics               | 4        | 0.07%   |
| Qualcomm                          | 4        | 0.07%   |
| QLogic                            | 4        | 0.07%   |
| Apple                             | 4        | 0.07%   |
| Huawei Technologies               | 3        | 0.05%   |
| Davicom Semiconductor             | 3        | 0.05%   |
| ADMtek                            | 3        | 0.05%   |
| Tehuti Networks                   | 2        | 0.03%   |
| National Semiconductor            | 2        | 0.03%   |
| Digital Equipment                 | 2        | 0.03%   |
| Accton Technology                 | 2        | 0.03%   |
| ZTE WCDMA Technologies MSM        | 1        | 0.02%   |
| U.S. Robotics                     | 1        | 0.02%   |
| T & A Mobile Phones               | 1        | 0.02%   |
| SysKonnect                        | 1        | 0.02%   |
| Sundance Technology Inc / IC Plus | 1        | 0.02%   |
| Standard Microsystems [SMC]       | 1        | 0.02%   |
| Silicon Integrated Systems [SiS]  | 1        | 0.02%   |
| Silicom                           | 1        | 0.02%   |
| Oracle/SUN                        | 1        | 0.02%   |
| Novatel Wireless                  | 1        | 0.02%   |
| MYRICOM                           | 1        | 0.02%   |
| Microsoft                         | 1        | 0.02%   |
| MediaTek                          | 1        | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 1675     | 24.82%  |
| Intel I211 Gigabit Network Connection                                         | 829      | 12.29%  |
| Intel I210 Gigabit Network Connection                                         | 451      | 6.68%   |
| Intel 82574L Gigabit Network Connection                                       | 331      | 4.91%   |
| Intel I350 Gigabit Network Connection                                         | 254      | 3.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 252      | 3.73%   |
| Intel Ethernet Connection I217-LM                                             | 174      | 2.58%   |
| Intel Ethernet Controller I225-V                                              | 167      | 2.47%   |
| Intel 82583V Gigabit Network Connection                                       | 151      | 2.24%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 132      | 1.96%   |
| Intel 82580 Gigabit Network Connection                                        | 127      | 1.88%   |
| Intel 82576 Gigabit Network Connection                                        | 126      | 1.87%   |
| Realtek RTL8125 2.5GbE Controller                                             | 121      | 1.79%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 95       | 1.41%   |
| Intel Ethernet Connection (2) I219-V                                          | 88       | 1.3%    |
| Intel Ethernet Connection (2) I219-LM                                         | 84       | 1.24%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 73       | 1.08%   |
| Intel 82579V Gigabit Network Connection                                       | 61       | 0.9%    |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 57       | 0.84%   |
| Intel Ethernet Connection I217-V                                              | 51       | 0.76%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 44       | 0.65%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 44       | 0.65%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 44       | 0.65%   |
| Intel Ethernet Controller I226-V                                              | 40       | 0.59%   |
| Intel Ethernet Connection (7) I219-V                                          | 40       | 0.59%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 34       | 0.5%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 33       | 0.49%   |
| Intel Ethernet Connection (7) I219-LM                                         | 32       | 0.47%   |
| Intel Ethernet Controller X550                                                | 27       | 0.4%    |
| Intel 82567LM-3 Gigabit Network Connection                                    | 27       | 0.4%    |
| Intel Ethernet Connection X553 1GbE                                           | 26       | 0.39%   |
| Intel Ethernet Connection (2) I218-V                                          | 26       | 0.39%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 23       | 0.34%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 22       | 0.33%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 22       | 0.33%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 21       | 0.31%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 20       | 0.3%    |
| Intel 82575GB Gigabit Network Connection                                      | 19       | 0.28%   |
| Intel 82575EB Gigabit Network Connection                                      | 19       | 0.28%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 19       | 0.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 4825     | 80.9%   |
| WiFi     | 982      | 16.47%  |
| Unknown  | 102      | 1.71%   |
| Modem    | 55       | 0.92%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 4685     | 94.88%  |
| WiFi     | 243      | 4.92%   |
| Unknown  | 10       | 0.2%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1079     | 21.6%   |
| 2     | 1074     | 21.5%   |
| 4     | 848      | 16.98%  |
| 3     | 785      | 15.72%  |
| 6     | 471      | 9.43%   |
| 5     | 401      | 8.03%   |
| 7     | 91       | 1.82%   |
| 0     | 81       | 1.62%   |
| 8     | 77       | 1.54%   |
| 9     | 32       | 0.64%   |
| 10    | 25       | 0.5%    |
| 12    | 8        | 0.16%   |
| 13    | 6        | 0.12%   |
| 11    | 5        | 0.1%    |
| 14    | 4        | 0.08%   |
| 16    | 3        | 0.06%   |
| 15    | 3        | 0.06%   |
| 20    | 2        | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 4304     | 84.61%  |
| Yes  | 783      | 15.39%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 321      | 55.63%  |
| Cambridge Silicon Radio         | 58       | 10.05%  |
| Realtek Semiconductor           | 39       | 6.76%   |
| IMC Networks                    | 31       | 5.37%   |
| Qualcomm Atheros Communications | 28       | 4.85%   |
| ASUSTek Computer                | 27       | 4.68%   |
| Broadcom                        | 22       | 3.81%   |
| Apple                           | 19       | 3.29%   |
| MediaTek                        | 8        | 1.39%   |
| Foxconn / Hon Hai               | 6        | 1.04%   |
| Lite-On Technology              | 5        | 0.87%   |
| Integrated System Solution      | 3        | 0.52%   |
| HTC (High Tech Computer)        | 2        | 0.35%   |
| TP-Link                         | 1        | 0.17%   |
| Qcom                            | 1        | 0.17%   |
| Micro Star International        | 1        | 0.17%   |
| Hewlett-Packard                 | 1        | 0.17%   |
| Edimax Technology               | 1        | 0.17%   |
| Dynex                           | 1        | 0.17%   |
| Dell                            | 1        | 0.17%   |
| Bluetooth Device                | 1        | 0.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 93       | 16.09%  |
| Intel Bluetooth wireless interface                                   | 88       | 15.22%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 58       | 10.03%  |
| Intel Wireless-AC 3168 Bluetooth                                     | 39       | 6.75%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 28       | 4.84%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 23       | 3.98%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 21       | 3.63%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 21       | 3.63%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip                 | 16       | 2.77%   |
| Intel AX201 Bluetooth                                                | 14       | 2.42%   |
| Intel AX210 Bluetooth                                                | 13       | 2.25%   |
| Realtek  Bluetooth Adapter                                           | 11       | 1.9%    |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 9        | 1.56%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 9        | 1.56%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 8        | 1.38%   |
| MediaTek Wireless_Device                                             | 8        | 1.38%   |
| IMC Networks Realtek Bluetooth Adapter                               | 8        | 1.38%   |
| Apple Apple Broadcom Built-in Bluetooth                              | 8        | 1.38%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 7        | 1.21%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 4        | 0.69%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)                      | 4        | 0.69%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 4        | 0.69%   |
| ASUS Bluetooth Controller                                            | 4        | 0.69%   |
| ASUS ASUS USB-BT500                                                  | 4        | 0.69%   |
| Realtek  Bluetooth 4.0 Adapter                                       | 3        | 0.52%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 3        | 0.52%   |
| Qualcomm Atheros Atheros AR9462 Bluetooth 3.0 + HS Adapter           | 3        | 0.52%   |
| Intel Intel Wireless Bluetooth                                       | 3        | 0.52%   |
| Foxconn / Hon Hai Bluetooth USB Module                               | 3        | 0.52%   |
| ASUS Realtek Bluetooth 4.0 + High Speed Chip                         | 3        | 0.52%   |
| Realtek RTL8821A Bluetooth                                           | 2        | 0.35%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device          | 2        | 0.35%   |
| Lite-On Bluetooth USB Module                                         | 2        | 0.35%   |
| Integrated System Solution Bluetooth Device                          | 2        | 0.35%   |
| IMC Networks Realtek Bluetooth 4.0 Adapter                           | 2        | 0.35%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 2        | 0.35%   |
| Broadcom HP Bluethunder                                              | 2        | 0.35%   |
| Broadcom Broadcom 20702 Bluetooth 4.0 Adapter                        | 2        | 0.35%   |
| Broadcom BCM2045 Bluetooth                                           | 2        | 0.35%   |
| ASUS Qualcomm Atheros AR9462 Bluetooth 4.0 + HS Adapter              | 2        | 0.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 2744     | 59.97%  |
| AMD                                          | 953      | 20.83%  |
| Nvidia                                       | 598      | 13.07%  |
| C-Media Electronics                          | 58       | 1.27%   |
| Creative Labs                                | 25       | 0.55%   |
| Logitech                                     | 22       | 0.48%   |
| Texas Instruments                            | 15       | 0.33%   |
| VIA Technologies                             | 10       | 0.22%   |
| JMTek                                        | 10       | 0.22%   |
| SteelSeries ApS                              | 9        | 0.2%    |
| Realtek Semiconductor                        | 6        | 0.13%   |
| Kingston Technology                          | 6        | 0.13%   |
| Focusrite-Novation                           | 6        | 0.13%   |
| Yamaha                                       | 5        | 0.11%   |
| Sony                                         | 5        | 0.11%   |
| Creative Technology                          | 5        | 0.11%   |
| Blue Microphones                             | 5        | 0.11%   |
| BEHRINGER International                      | 5        | 0.11%   |
| Silicon Integrated Systems [SiS]             | 4        | 0.09%   |
| GN Netcom                                    | 4        | 0.09%   |
| Generalplus Technology                       | 4        | 0.09%   |
| Corsair                                      | 4        | 0.09%   |
| Zoran Co. Personal Media Division (Nogatech) | 3        | 0.07%   |
| XMOS                                         | 3        | 0.07%   |
| Thesycon Systemsoftware & Consulting         | 3        | 0.07%   |
| KTMicro                                      | 3        | 0.07%   |
| Cambridge Silicon Radio                      | 3        | 0.07%   |
| ASUSTek Computer                             | 3        | 0.07%   |
| ULi Electronics                              | 2        | 0.04%   |
| Trust                                        | 2        | 0.04%   |
| Tenx Technology                              | 2        | 0.04%   |
| M-Audio                                      | 2        | 0.04%   |
| Google                                       | 2        | 0.04%   |
| Giga-Byte Technology                         | 2        | 0.04%   |
| FiiO Electronics Technology                  | 2        | 0.04%   |
| ESS Technology                               | 2        | 0.04%   |
| Ensoniq                                      | 2        | 0.04%   |
| Elgato Systems                               | 2        | 0.04%   |
| Audio-Technica                               | 2        | 0.04%   |
| Astro Gaming                                 | 2        | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 336      | 6.12%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 325      | 5.92%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 215      | 3.91%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 205      | 3.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 194      | 3.53%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 193      | 3.51%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 183      | 3.33%   |
| AMD FCH Azalia Controller                                                                         | 169      | 3.08%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 156      | 2.84%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 153      | 2.79%   |
| AMD Kabini HDMI/DP Audio                                                                          | 150      | 2.73%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 142      | 2.59%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 130      | 2.37%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 127      | 2.31%   |
| Intel 200 Series PCH HD Audio                                                                     | 118      | 2.15%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 106      | 1.93%   |
| Intel Cannon Lake PCH cAVS                                                                        | 105      | 1.91%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 105      | 1.91%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 99       | 1.8%    |
| Intel Jasper Lake HD Audio                                                                        | 83       | 1.51%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 82       | 1.49%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 75       | 1.37%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 70       | 1.27%   |
| Intel 8 Series HD Audio Controller                                                                | 70       | 1.27%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 69       | 1.26%   |
| Intel Broadwell-U Audio Controller                                                                | 66       | 1.2%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 65       | 1.18%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 60       | 1.09%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 54       | 0.98%   |
| Nvidia High Definition Audio Controller                                                           | 44       | 0.8%    |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 41       | 0.75%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 40       | 0.73%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 40       | 0.73%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 39       | 0.71%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 36       | 0.66%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 36       | 0.66%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 36       | 0.66%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 35       | 0.64%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 34       | 0.62%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 34       | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown                      | 742      | 14.79%  |
| Kingston                     | 741      | 14.77%  |
| Samsung Electronics          | 712      | 14.19%  |
| SK hynix                     | 526      | 10.48%  |
| Crucial                      | 503      | 10.02%  |
| Micron Technology            | 343      | 6.84%   |
| Corsair                      | 325      | 6.48%   |
| G.Skill                      | 237      | 4.72%   |
| Unknown                      | 129      | 2.57%   |
| Nanya Technology             | 64       | 1.28%   |
| Transcend                    | 57       | 1.14%   |
| A-DATA Technology            | 55       | 1.1%    |
| Unknown (ABCD)               | 52       | 1.04%   |
| Ramaxel Technology           | 50       | 1%      |
| Team                         | 46       | 0.92%   |
| Patriot                      | 46       | 0.92%   |
| Kimtigo                      | 27       | 0.54%   |
| Elpida                       | 24       | 0.48%   |
| Apacer                       | 24       | 0.48%   |
| Hewlett-Packard              | 17       | 0.34%   |
| GOODRAM                      | 17       | 0.34%   |
| PNY                          | 16       | 0.32%   |
| Avant                        | 14       | 0.28%   |
| ATP                          | 14       | 0.28%   |
| Teikon                       | 11       | 0.22%   |
| TIMETEC                      | 10       | 0.2%    |
| Toshiba                      | 9        | 0.18%   |
| Smart                        | 9        | 0.18%   |
| AMD                          | 9        | 0.18%   |
| Super Talent                 | 8        | 0.16%   |
| GeIL                         | 8        | 0.16%   |
| Tigo                         | 7        | 0.14%   |
| Silicon Power                | 6        | 0.12%   |
| Patriot Memory (PDP Systems) | 6        | 0.12%   |
| Innodisk                     | 6        | 0.12%   |
| Smart Modular                | 5        | 0.1%    |
| Qimonda                      | 5        | 0.1%    |
| Kingmax                      | 5        | 0.1%    |
| Unknown (0x0C26)             | 4        | 0.08%   |
| Shenzhen Jinge Information   | 4        | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Unknown                                                      | 129      | 2.4%    |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                  | 111      | 2.06%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 52       | 0.97%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 35       | 0.65%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 31       | 0.58%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 28       | 0.52%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s         | 27       | 0.5%    |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 26       | 0.48%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s         | 26       | 0.48%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 26       | 0.48%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s          | 25       | 0.46%   |
| Unknown RAM Module 8GB 1600MT/s                              | 24       | 0.45%   |
| Unknown RAM Module 2GB DIMM SDRAM                            | 24       | 0.45%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s         | 24       | 0.45%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                    | 22       | 0.41%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s        | 22       | 0.41%   |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s                   | 21       | 0.39%   |
| Unknown RAM Module 1GB DIMM SDRAM                            | 21       | 0.39%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 21       | 0.39%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s          | 21       | 0.39%   |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s          | 20       | 0.37%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s          | 20       | 0.37%   |
| Samsung RAM M471B1G73QH0-YK0 8GB DIMM DDR3 1600MT/s          | 19       | 0.35%   |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s               | 19       | 0.35%   |
| Samsung RAM M471B5173QH0-YK0 4GB DIMM DDR3 1600MT/s          | 17       | 0.32%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s                   | 16       | 0.3%    |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s         | 16       | 0.3%    |
| Unknown RAM Module 2GB DIMM 1333MT/s                         | 15       | 0.28%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 15       | 0.28%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 15       | 0.28%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 2667MT/s            | 15       | 0.28%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s          | 15       | 0.28%   |
| Crucial RAM CT102464BF160B.M16 8GB DIMM DDR3 1600MT/s        | 15       | 0.28%   |
| Crucial RAM CT102464BF160B.C16 8GB DIMM DDR3 1600MT/s        | 15       | 0.28%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s        | 15       | 0.28%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                     | 14       | 0.26%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s         | 14       | 0.26%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 1600MT/s          | 14       | 0.26%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                         | 13       | 0.24%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                  | 13       | 0.24%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 2194     | 49.55%  |
| DDR4    | 1633     | 36.88%  |
| DDR2    | 209      | 4.72%   |
| Unknown | 198      | 4.47%   |
| SDRAM   | 83       | 1.87%   |
| LPDDR4  | 71       | 1.6%    |
| DDR     | 32       | 0.72%   |
| DRAM    | 3        | 0.07%   |
| RAM     | 2        | 0.05%   |
| LPDDR3  | 2        | 0.05%   |
| DDR5    | 1        | 0.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 3020     | 68.61%  |
| SODIMM       | 1293     | 29.37%  |
| Unknown      | 54       | 1.23%   |
| Row Of Chips | 17       | 0.39%   |
| RIMM         | 9        | 0.2%    |
| FB-DIMM      | 5        | 0.11%   |
| Chip         | 4        | 0.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 1676     | 35.25%  |
| 4096  | 1584     | 33.32%  |
| 2048  | 648      | 13.63%  |
| 16384 | 588      | 12.37%  |
| 1024  | 140      | 2.94%   |
| 32768 | 84       | 1.77%   |
| 512   | 25       | 0.53%   |
| 256   | 2        | 0.04%   |
| 128   | 2        | 0.04%   |
| 65536 | 1        | 0.02%   |
| 4092  | 1        | 0.02%   |
| 1556  | 1        | 0.02%   |
| 64    | 1        | 0.02%   |
| 32    | 1        | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 1367     | 29.11%  |
| 1333    | 768      | 16.35%  |
| 2400    | 571      | 12.16%  |
| 2667    | 360      | 7.67%   |
| 3200    | 324      | 6.9%    |
| 2133    | 319      | 6.79%   |
| 800     | 200      | 4.26%   |
| 667     | 134      | 2.85%   |
| 2666    | 101      | 2.15%   |
| Unknown | 99       | 2.11%   |
| 1066    | 78       | 1.66%   |
| 1867    | 55       | 1.17%   |
| 3000    | 48       | 1.02%   |
| 1067    | 42       | 0.89%   |
| 3600    | 39       | 0.83%   |
| 1866    | 30       | 0.64%   |
| 2933    | 29       | 0.62%   |
| 1334    | 28       | 0.6%    |
| 533     | 22       | 0.47%   |
| 400     | 21       | 0.45%   |
| 333     | 6        | 0.13%   |
| 65535   | 5        | 0.11%   |
| 3400    | 5        | 0.11%   |
| 2134    | 5        | 0.11%   |
| 1332    | 5        | 0.11%   |
| 1400    | 4        | 0.09%   |
| 1033    | 4        | 0.09%   |
| 3534    | 3        | 0.06%   |
| 5200    | 2        | 0.04%   |
| 2048    | 2        | 0.04%   |
| 933     | 2        | 0.04%   |
| 266     | 2        | 0.04%   |
| 133     | 2        | 0.04%   |
| 59392   | 1        | 0.02%   |
| 5354    | 1        | 0.02%   |
| 4800    | 1        | 0.02%   |
| 4133    | 1        | 0.02%   |
| 3733    | 1        | 0.02%   |
| 3500    | 1        | 0.02%   |
| 3333    | 1        | 0.02%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Brother Industries    | 11       | 35.48%  |
| Hewlett-Packard       | 10       | 32.26%  |
| Seiko Epson           | 2        | 6.45%   |
| Lexmark International | 2        | 6.45%   |
| Ricoh                 | 1        | 3.23%   |
| QinHeng Electronics   | 1        | 3.23%   |
| Prolific Technology   | 1        | 3.23%   |
| Kyocera               | 1        | 3.23%   |
| Canon                 | 1        | 3.23%   |
| Apple                 | 1        | 3.23%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                                                                                             | Desktops | Percent |
|-------------------------------------------------------------------------------------------------------------------|----------|---------|
| Brother MFC-7360N                                                                                                 | 2        | 6.06%   |
| Brother HL-1430 Laser Printer                                                                                     | 2        | 6.06%   |
| Seiko Epson USB2.0 Printer (Hi-speed)                                                                             | 1        | 3.03%   |
| Seiko Epson Printer                                                                                               | 1        | 3.03%   |
| Ricoh SP 112                                                                                                      | 1        | 3.03%   |
| QinHeng CH340S                                                                                                    | 1        | 3.03%   |
| Prolific PL2305 Parallel Port                                                                                     | 1        | 3.03%   |
| Lexmark International SINDOH A603_A608 Print                                                                      | 1        | 3.03%   |
| Lexmark International Lexmark MS710 Print                                                                         | 1        | 3.03%   |
| Kyocera FS-1025MFP                                                                                                | 1        | 3.03%   |
| HP PNP Fax Null                                                                                                   | 1        | 3.03%   |
| HP LaserJet P3005                                                                                                 | 1        | 3.03%   |
| HP LaserJet 2200                                                                                                  | 1        | 3.03%   |
| HP LaserJet 1200                                                                                                  | 1        | 3.03%   |
| HP LaserJet 1012                                                                                                  | 1        | 3.03%   |
| HP HP LaserJet P2035 HP Print                                                                                     | 1        | 3.03%   |
| HP HP LaserJet MFP E52645 LaserJet 0 LaserJet 0 LaserJet 1 LaserJet 1 LaserJet 2 LaserJet 2 LaserJet 3 LaserJet 3 | 1        | 3.03%   |
| HP HP LaserJet M14-M17 Printer HP LEDM IPP Printer HP LEDM IPP Printer HP LEDM IPP Printer                        | 1        | 3.03%   |
| HP HP LaserJet M101-M106 Printer HP LEDM HP LEDM IPP Printer IPP Printer                                          | 1        | 3.03%   |
| HP HP Laser 107w                                                                                                  | 1        | 3.03%   |
| HP DeskJet 5850c                                                                                                  | 1        | 3.03%   |
| HP Color LaserJet CP1215                                                                                          | 1        | 3.03%   |
| Canon LBP2900                                                                                                     | 1        | 3.03%   |
| Brother MFC-L2685DW                                                                                               | 1        | 3.03%   |
| Brother MFC-J485DW                                                                                                | 1        | 3.03%   |
| Brother MFC-J200                                                                                                  | 1        | 3.03%   |
| Brother HL-L5200DW series                                                                                         | 1        | 3.03%   |
| Brother HL-L2310D series                                                                                          | 1        | 3.03%   |
| Brother HL-2030 Laser Printer                                                                                     | 1        | 3.03%   |
| Brother DCP-J100                                                                                                  | 1        | 3.03%   |
| Apple Gamesir-G3s 2.10                                                                                            | 1        | 3.03%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 6        | 75%     |
| Seiko Epson     | 1        | 12.5%   |
| Hewlett-Packard | 1        | 12.5%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                                                                               | Desktops | Percent |
|-------------------------------------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 110                                                             | 3        | 37.5%   |
| Seiko Epson WF-2860 Series EPSON Scanner USB2.0 Printer EPSON Utility USB2.0 Faxout | 1        | 12.5%   |
| HP ScanJet 5300c/5370c                                                              | 1        | 12.5%   |
| Canon CanoScan LIDE 25                                                              | 1        | 12.5%   |
| Canon CanoScan LiDE 220                                                             | 1        | 12.5%   |
| Canon CanoScan LiDE 210                                                             | 1        | 12.5%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 61       | 44.53%  |
| Microdia                      | 15       | 10.95%  |
| Chicony Electronics           | 9        | 6.57%   |
| Z-Star Microelectronics       | 7        | 5.11%   |
| ARC International             | 5        | 3.65%   |
| Arkmicro Technologies         | 4        | 2.92%   |
| WCM_USB                       | 2        | 1.46%   |
| SHENZHEN EMEET TECHNOLOGY     | 2        | 1.46%   |
| IMC Networks                  | 2        | 1.46%   |
| Hewlett-Packard               | 2        | 1.46%   |
| Generalplus Technology        | 2        | 1.46%   |
| Aveo Technology               | 2        | 1.46%   |
| YGTek                         | 1        | 0.73%   |
| Xiongmai                      | 1        | 0.73%   |
| Valve Software                | 1        | 0.73%   |
| Trust                         | 1        | 0.73%   |
| Suyin                         | 1        | 0.73%   |
| Sunplus Innovation Technology | 1        | 0.73%   |
| Sonix Technology              | 1        | 0.73%   |
| Silicon Motion                | 1        | 0.73%   |
| Ricoh                         | 1        | 0.73%   |
| Realtek Semiconductor         | 1        | 0.73%   |
| Quanta                        | 1        | 0.73%   |
| OmniVision Technologies       | 1        | 0.73%   |
| Novatek Microelectronics      | 1        | 0.73%   |
| Linux Foundation              | 1        | 0.73%   |
| Lenovo                        | 1        | 0.73%   |
| KYE Systems (Mouse Systems)   | 1        | 0.73%   |
| Huawei Technologies           | 1        | 0.73%   |
| HD WEBCAM                     | 1        | 0.73%   |
| Genesys Logic                 | 1        | 0.73%   |
| GEMBIRD                       | 1        | 0.73%   |
| Cubeternet                    | 1        | 0.73%   |
| Creative Technology           | 1        | 0.73%   |
| Alcor Micro                   | 1        | 0.73%   |
| A4Tech                        | 1        | 0.73%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Logitech Webcam C270                           | 15       | 10.95%  |
| Logitech HD Pro Webcam C920                    | 14       | 10.22%  |
| Logitech Webcam C310                           | 7        | 5.11%   |
| Logitech C922 Pro Stream Webcam                | 6        | 4.38%   |
| ARC International Camera                       | 5        | 3.65%   |
| Microdia Webcam Vitade AF                      | 3        | 2.19%   |
| Logitech C920 PRO HD Webcam                    | 3        | 2.19%   |
| Arkmicro USB2.0 PC CAMERA                      | 3        | 2.19%   |
| Z-Star Venus USB2.0 Camera                     | 2        | 1.46%   |
| Z-Star Integrated Camera                       | 2        | 1.46%   |
| WCM_USB WEB CAM                                | 2        | 1.46%   |
| SHENZHEN EMEET TECHNOLOGY HD Webcam eMeet C960 | 2        | 1.46%   |
| Microdia HP Integrated Webcam                  | 2        | 1.46%   |
| Microdia FHD Webcam                            | 2        | 1.46%   |
| Microdia Camera                                | 2        | 1.46%   |
| Microdia ASUS USB2.0 Webcam                    | 2        | 1.46%   |
| Logitech Webcam C930e                          | 2        | 1.46%   |
| Logitech Webcam C170                           | 2        | 1.46%   |
| Logitech Labtec Webcam Pro                     | 2        | 1.46%   |
| Logitech HD Webcam C525                        | 2        | 1.46%   |
| Logitech C920 HD Pro Webcam                    | 2        | 1.46%   |
| Logitech C505 HD Webcam                        | 2        | 1.46%   |
| IMC Networks XHC Camera                        | 2        | 1.46%   |
| Generalplus GENERAL WEBCAM                     | 2        | 1.46%   |
| Z-Star Vega USB 2.0 Camera                     | 1        | 0.73%   |
| Z-Star Lenovo USB2.0 UVC Camera                | 1        | 0.73%   |
| Z-Star A4 TECH USB2.0 PC Camera J              | 1        | 0.73%   |
| YGTek Webcam                                   | 1        | 0.73%   |
| Xiongmai web camera                            | 1        | 0.73%   |
| Valve Software 3D Camera                       | 1        | 0.73%   |
| Trust Trust USB Camera                         | 1        | 0.73%   |
| Suyin Acer CrystalEye Webcam                   | 1        | 0.73%   |
| Sunplus Aukey-PC-LM1E Camera                   | 1        | 0.73%   |
| Sonix FHD Webcam                               | 1        | 0.73%   |
| Silicon Motion 300k Pixel Camera               | 1        | 0.73%   |
| Ricoh USB2.0 Camera                            | 1        | 0.73%   |
| Realtek USB Video Device                       | 1        | 0.73%   |
| Quanta Realtek DMFT - RGB                      | 1        | 0.73%   |
| OmniVision Monitor Webcam                      | 1        | 0.73%   |
| Novatek HP High Definition 2MP Webcam          | 1        | 0.73%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Validity Sensors           | 1        | 16.67%  |
| Upek                       | 1        | 16.67%  |
| STMicroelectronics         | 1        | 16.67%  |
| Shenzhen Goodix Technology | 1        | 16.67%  |
| DigitalPersona             | 1        | 16.67%  |
| AuthenTec                  | 1        | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 1        | 16.67%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1        | 16.67%  |
| STMicroelectronics Fingerprint Reader                  | 1        | 16.67%  |
| Shenzhen Goodix  FingerPrint Device                    | 1        | 16.67%  |
| DigitalPersona Fingerprint Reader                      | 1        | 16.67%  |
| AuthenTec AES2501 Fingerprint Sensor                   | 1        | 16.67%  |

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
| 1     | 2345     | 46.57%  |
| 0     | 1943     | 38.59%  |
| 2     | 532      | 10.57%  |
| 3     | 156      | 3.1%    |
| 4     | 41       | 0.81%   |
| 5     | 14       | 0.28%   |
| 7     | 2        | 0.04%   |
| 6     | 2        | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 2611     | 70.78%  |
| Net/wireless             | 344      | 9.33%   |
| Bluetooth                | 214      | 5.8%    |
| Firewire controller      | 137      | 3.71%   |
| Card reader              | 100      | 2.71%   |
| Sound                    | 90       | 2.44%   |
| Net/ethernet             | 72       | 1.95%   |
| Network                  | 67       | 1.82%   |
| Graphics card            | 30       | 0.81%   |
| Storage/raid             | 7        | 0.19%   |
| Storage/ata              | 7        | 0.19%   |
| Storage                  | 3        | 0.08%   |
| Dvb card                 | 3        | 0.08%   |
| Wireless                 | 1        | 0.03%   |
| Storage/ide              | 1        | 0.03%   |
| Modem                    | 1        | 0.03%   |
| Fingerprint reader       | 1        | 0.03%   |

