BSD in Russia - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for BSD in Russia.

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

Total: 355

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| ASRock        | A320M-DVS R4.0              | [77f61a8711](https://bsd-hardware.info/?probe=77f61a8711) | Aug 01, 2022 |
| Gigabyte      | 970A-DS3P FX                | [3c33e546bb](https://bsd-hardware.info/?probe=3c33e546bb) | Jul 31, 2022 |
| HP            | 339A                        | [241e56a349](https://bsd-hardware.info/?probe=241e56a349) | Jul 27, 2022 |
| ASUSTek       | P5Q-E                       | [3ba3cedec4](https://bsd-hardware.info/?probe=3ba3cedec4) | Jul 21, 2022 |
| Acer          | RS880M05                    | [7bcc14ceba](https://bsd-hardware.info/?probe=7bcc14ceba) | Jul 16, 2022 |
| Gigabyte      | H310M S2 x.x                | [b11ca9c369](https://bsd-hardware.info/?probe=b11ca9c369) | Jul 16, 2022 |
| Acer          | Revo 70                     | [aad484a882](https://bsd-hardware.info/?probe=aad484a882) | Jul 13, 2022 |
| Acer          | Revo 70                     | [c8b51a94bd](https://bsd-hardware.info/?probe=c8b51a94bd) | Jul 13, 2022 |
| Kraftway      | KWH77                       | [c34f44a495](https://bsd-hardware.info/?probe=c34f44a495) | Jul 12, 2022 |
| Gigabyte      | C1037UN-EU                  | [3644f56368](https://bsd-hardware.info/?probe=3644f56368) | Jul 10, 2022 |
| Intel         | DN2820FYK H24582-203        | [8a9a8cdbd0](https://bsd-hardware.info/?probe=8a9a8cdbd0) | Jul 08, 2022 |
| Lenovo        | NO DPK                      | [2c79a92fc4](https://bsd-hardware.info/?probe=2c79a92fc4) | Jul 06, 2022 |
| Techvision    | TVI7309X B0                 | [12279c8a4b](https://bsd-hardware.info/?probe=12279c8a4b) | Jul 06, 2022 |
| Techvision    | TVI7309X B0                 | [19a4b27ae7](https://bsd-hardware.info/?probe=19a4b27ae7) | Jul 05, 2022 |
| Acer          | Aspire XC-895 V:1.0         | [d67aa61a6b](https://bsd-hardware.info/?probe=d67aa61a6b) | Jul 05, 2022 |
| Acer          | Revo RN86                   | [2dc98202aa](https://bsd-hardware.info/?probe=2dc98202aa) | Jul 05, 2022 |
| Gigabyte      | G41MT-S2                    | [0563158740](https://bsd-hardware.info/?probe=0563158740) | Jun 28, 2022 |
| ASRock        | P67 Professional            | [3372d35113](https://bsd-hardware.info/?probe=3372d35113) | Jun 28, 2022 |
| Dell          | 07KY25 A00                  | [9981217b1b](https://bsd-hardware.info/?probe=9981217b1b) | Jun 16, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [067dbf3357](https://bsd-hardware.info/?probe=067dbf3357) | Jun 15, 2022 |
| Pegatron      | 2A94h                       | [17078490f7](https://bsd-hardware.info/?probe=17078490f7) | Jun 11, 2022 |
| Pegatron      | 2A94h                       | [438d4f9b2f](https://bsd-hardware.info/?probe=438d4f9b2f) | Jun 09, 2022 |
| Gigabyte      | F2A75M-D3H                  | [ae3436167b](https://bsd-hardware.info/?probe=ae3436167b) | Jun 05, 2022 |
| Unknown       | Unknown                     | [a56bc64f26](https://bsd-hardware.info/?probe=a56bc64f26) | May 27, 2022 |
| ASUSTek       | P5LD2                       | [64208afa2c](https://bsd-hardware.info/?probe=64208afa2c) | May 25, 2022 |
| khadas        | edge-v                      | [60fb48e34c](https://bsd-hardware.info/?probe=60fb48e34c) | May 23, 2022 |
| khadas        | edge-v                      | [6facaa8032](https://bsd-hardware.info/?probe=6facaa8032) | May 22, 2022 |
| Gigabyte      | H81M-S2PV                   | [1937e77b97](https://bsd-hardware.info/?probe=1937e77b97) | May 22, 2022 |
| ASUSTek       | P8Z77-V LX                  | [e7055d83e2](https://bsd-hardware.info/?probe=e7055d83e2) | May 20, 2022 |
| Supermicro    | X10DRi-T                    | [d6fa145c7c](https://bsd-hardware.info/?probe=d6fa145c7c) | May 16, 2022 |
| HP            | ProLiant MicroServer        | [e569bffe8f](https://bsd-hardware.info/?probe=e569bffe8f) | May 12, 2022 |
| ASUSTek       | PRIME H470M-PLUS            | [224614e9ab](https://bsd-hardware.info/?probe=224614e9ab) | May 10, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [76eef59920](https://bsd-hardware.info/?probe=76eef59920) | May 10, 2022 |
| ASUSTek       | P8Z77-V LX                  | [bf3d4941a2](https://bsd-hardware.info/?probe=bf3d4941a2) | May 06, 2022 |
| ASUSTek       | P8Z77-V LX                  | [dd3afff7f0](https://bsd-hardware.info/?probe=dd3afff7f0) | May 06, 2022 |
| Gigabyte      | A320M-H-CF                  | [24d308754b](https://bsd-hardware.info/?probe=24d308754b) | May 02, 2022 |
| Unknown       | Unknown                     | [d036c00d6c](https://bsd-hardware.info/?probe=d036c00d6c) | Apr 28, 2022 |
| ASRock        | J3355B-ITX                  | [c0739686fb](https://bsd-hardware.info/?probe=c0739686fb) | Apr 28, 2022 |
| Supermicro    | X10DRi-T                    | [dcd02e012d](https://bsd-hardware.info/?probe=dcd02e012d) | Apr 28, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [1a475f0939](https://bsd-hardware.info/?probe=1a475f0939) | Apr 27, 2022 |
| ASRock        | X570S PG Riptide            | [928d2abb5e](https://bsd-hardware.info/?probe=928d2abb5e) | Apr 26, 2022 |
| Gigabyte      | H310M S2 x.x                | [549053284c](https://bsd-hardware.info/?probe=549053284c) | Apr 25, 2022 |
| PC Engines    | APU2                        | [04a6549c99](https://bsd-hardware.info/?probe=04a6549c99) | Apr 23, 2022 |
| Dell          | 0HD5W2 A00                  | [955922ebe2](https://bsd-hardware.info/?probe=955922ebe2) | Apr 23, 2022 |
| Dell          | 0HD5W2 A00                  | [4d66b2b328](https://bsd-hardware.info/?probe=4d66b2b328) | Apr 23, 2022 |
| Intel         | DH67BL                      | [3c3c9e12da](https://bsd-hardware.info/?probe=3c3c9e12da) | Apr 22, 2022 |
| KOHJINSHA     | SH series                   | [3136a0ca03](https://bsd-hardware.info/?probe=3136a0ca03) | Apr 22, 2022 |
| Lenovo        | ThinkPad X240 20ALA0AHRT    | [062a08c811](https://bsd-hardware.info/?probe=062a08c811) | Apr 22, 2022 |
| Gigabyte      | B450 AORUS M                | [427cf12b45](https://bsd-hardware.info/?probe=427cf12b45) | Apr 22, 2022 |
| Sony          | VPCL22Z1R                   | [f199d57905](https://bsd-hardware.info/?probe=f199d57905) | Apr 22, 2022 |
| ASUSTek       | Z170-K                      | [b16705bbbd](https://bsd-hardware.info/?probe=b16705bbbd) | Apr 22, 2022 |
| ASUSTek       | P10S-I Series               | [aca13dba36](https://bsd-hardware.info/?probe=aca13dba36) | Apr 22, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | [8e64404e52](https://bsd-hardware.info/?probe=8e64404e52) | Apr 19, 2022 |
| Shuttle       | DS20U                       | [f01372719f](https://bsd-hardware.info/?probe=f01372719f) | Apr 16, 2022 |
| ASUSTek       | P8Z77-V LX                  | [562a4d0421](https://bsd-hardware.info/?probe=562a4d0421) | Apr 14, 2022 |
| ASUSTek       | P8Z77-V LX                  | [9f70756cb2](https://bsd-hardware.info/?probe=9f70756cb2) | Apr 14, 2022 |
| HP            | ProLiant MicroServer        | [fa76da045a](https://bsd-hardware.info/?probe=fa76da045a) | Apr 13, 2022 |
| Gigabyte      | E3000N                      | [7169c296cc](https://bsd-hardware.info/?probe=7169c296cc) | Apr 08, 2022 |
| Supermicro    | X10DRi-T                    | [e17bbe2186](https://bsd-hardware.info/?probe=e17bbe2186) | Apr 05, 2022 |
| Gigabyte      | H310M S2 x.x                | [29a9462f72](https://bsd-hardware.info/?probe=29a9462f72) | Apr 04, 2022 |
| Intel         | DCP847SKE                   | [a79e298be3](https://bsd-hardware.info/?probe=a79e298be3) | Apr 03, 2022 |
| ASUSTek       | P8Z77-V LX                  | [42419abab8](https://bsd-hardware.info/?probe=42419abab8) | Apr 01, 2022 |
| Supermicro    | X10DRi-T                    | [eae4612261](https://bsd-hardware.info/?probe=eae4612261) | Mar 31, 2022 |
| ASUSTek       | P8Z77-V LX                  | [49627775f3](https://bsd-hardware.info/?probe=49627775f3) | Mar 31, 2022 |
| ASUSTek       | P8Z77-V LX                  | [70d10ce47c](https://bsd-hardware.info/?probe=70d10ce47c) | Mar 25, 2022 |
| MSI           | B85-G43                     | [f0a919c35f](https://bsd-hardware.info/?probe=f0a919c35f) | Mar 25, 2022 |
| ASUSTek       | P8Z77-V LX                  | [99d079bd5a](https://bsd-hardware.info/?probe=99d079bd5a) | Mar 25, 2022 |
| MSI           | B85-G43                     | [7bd545fda8](https://bsd-hardware.info/?probe=7bd545fda8) | Mar 25, 2022 |
| ASUSTek       | P8Z77-V LX                  | [c76aa38baf](https://bsd-hardware.info/?probe=c76aa38baf) | Mar 24, 2022 |
| ASUSTek       | P8Z77-V LX                  | [8696405d09](https://bsd-hardware.info/?probe=8696405d09) | Mar 24, 2022 |
| Huanan        | X99-F8D V2.4                | [4ef193841e](https://bsd-hardware.info/?probe=4ef193841e) | Mar 13, 2022 |
| Gigabyte      | G31M-S2C                    | [5a22bb6991](https://bsd-hardware.info/?probe=5a22bb6991) | Mar 12, 2022 |
| MSI           | B350M BAZOOKA               | [bac8d0bdb7](https://bsd-hardware.info/?probe=bac8d0bdb7) | Mar 11, 2022 |
| ASRock        | G41C-VS                     | [a9a1b1a493](https://bsd-hardware.info/?probe=a9a1b1a493) | Mar 03, 2022 |
| Intel         | DN2800MT AAG23738-600       | [8ecf2d023f](https://bsd-hardware.info/?probe=8ecf2d023f) | Mar 02, 2022 |
| Gigabyte      | X58A-UD5                    | [58d57520c1](https://bsd-hardware.info/?probe=58d57520c1) | Feb 20, 2022 |
| Gigabyte      | C1037UN-EU                  | [5b6dd82da8](https://bsd-hardware.info/?probe=5b6dd82da8) | Feb 18, 2022 |
| ASRock        | B460M Pro4                  | [7a2781344f](https://bsd-hardware.info/?probe=7a2781344f) | Feb 17, 2022 |
| MW            | GMLK-2_5G4L                 | [2dd03795ba](https://bsd-hardware.info/?probe=2dd03795ba) | Feb 11, 2022 |
| ASRock        | X370 Gaming X               | [22f8d133d4](https://bsd-hardware.info/?probe=22f8d133d4) | Feb 09, 2022 |
| ASRock        | D1800M                      | [0902154c8e](https://bsd-hardware.info/?probe=0902154c8e) | Feb 08, 2022 |
| Dell          | 0654JC A01                  | [bbcf2bad96](https://bsd-hardware.info/?probe=bbcf2bad96) | Feb 08, 2022 |
| ASUSTek       | P5G41T-M                    | [a7d5b65ba1](https://bsd-hardware.info/?probe=a7d5b65ba1) | Feb 07, 2022 |
| MSI           | MS-7C96                     | [c08331ad58](https://bsd-hardware.info/?probe=c08331ad58) | Feb 06, 2022 |
| Kontron       | KT965/ATXP 61420000         | [b5389bbf43](https://bsd-hardware.info/?probe=b5389bbf43) | Feb 06, 2022 |
| ASRock        | H81M-VG4 R2.0               | [8af8b5270e](https://bsd-hardware.info/?probe=8af8b5270e) | Feb 04, 2022 |
| ASUSTek       | P4P800-VM                   | [2343c503a7](https://bsd-hardware.info/?probe=2343c503a7) | Feb 04, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [58ea01e4e6](https://bsd-hardware.info/?probe=58ea01e4e6) | Jan 29, 2022 |
| Lenovo        | 30C9 NOK                    | [7169d2989c](https://bsd-hardware.info/?probe=7169d2989c) | Jan 29, 2022 |
| Pegatron      | IPPPV-D3G                   | [d5e44ccf6b](https://bsd-hardware.info/?probe=d5e44ccf6b) | Jan 28, 2022 |
| ASUSTek       | P5GC-MX                     | [372749f9d7](https://bsd-hardware.info/?probe=372749f9d7) | Jan 27, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [eb44c8d7e1](https://bsd-hardware.info/?probe=eb44c8d7e1) | Jan 27, 2022 |
| ASUSTek       | P5B SE                      | [f97fba19c1](https://bsd-hardware.info/?probe=f97fba19c1) | Jan 26, 2022 |
| Kontron       | KT965/ATXP 61420000         | [36109b09ca](https://bsd-hardware.info/?probe=36109b09ca) | Jan 26, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [9f0a000ceb](https://bsd-hardware.info/?probe=9f0a000ceb) | Jan 25, 2022 |
| ASUSTek       | P5B SE                      | [e3332e7b94](https://bsd-hardware.info/?probe=e3332e7b94) | Jan 25, 2022 |
| ASRock        | B460M Pro4                  | [107a1e59f5](https://bsd-hardware.info/?probe=107a1e59f5) | Jan 25, 2022 |
| MSI           | G31TM-P21                   | [10ca6492c1](https://bsd-hardware.info/?probe=10ca6492c1) | Jan 25, 2022 |
| MSI           | G31TM-P21                   | [7563c4cf09](https://bsd-hardware.info/?probe=7563c4cf09) | Jan 25, 2022 |
| Kontron       | KT965/ATXP 61420000         | [db757ea2ef](https://bsd-hardware.info/?probe=db757ea2ef) | Jan 25, 2022 |
| Gigabyte      | H310M S2 x.x                | [b0aeac1ef8](https://bsd-hardware.info/?probe=b0aeac1ef8) | Jan 25, 2022 |
| ASUSTek       | P5M2                        | [f2d4eccf4d](https://bsd-hardware.info/?probe=f2d4eccf4d) | Jan 24, 2022 |
| ASUSTek       | P7H55-M                     | [fb73c2f7dc](https://bsd-hardware.info/?probe=fb73c2f7dc) | Jan 23, 2022 |
| ASRock        | J3455-ITX                   | [55d70a3070](https://bsd-hardware.info/?probe=55d70a3070) | Jan 22, 2022 |
| ASRock        | J3455-ITX                   | [bf033b6b9f](https://bsd-hardware.info/?probe=bf033b6b9f) | Jan 22, 2022 |
| Intel         | DCP847SKE                   | [2828ef2a6d](https://bsd-hardware.info/?probe=2828ef2a6d) | Jan 20, 2022 |
| ASUSTek       | PRIME Z590-P                | [0473b57d99](https://bsd-hardware.info/?probe=0473b57d99) | Jan 19, 2022 |
| Intel CNCT... | Unknown                     | [0debf023f1](https://bsd-hardware.info/?probe=0debf023f1) | Jan 18, 2022 |
| Gigabyte      | B365 HD3                    | [62fc48bd99](https://bsd-hardware.info/?probe=62fc48bd99) | Jan 15, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [d377e06101](https://bsd-hardware.info/?probe=d377e06101) | Jan 15, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [384cbe9714](https://bsd-hardware.info/?probe=384cbe9714) | Jan 13, 2022 |
| ASUSTek       | A68HM-PLUS                  | [650628a974](https://bsd-hardware.info/?probe=650628a974) | Jan 10, 2022 |
| friendlyel... | nanopi-m4                   | [bb29e50061](https://bsd-hardware.info/?probe=bb29e50061) | Dec 27, 2021 |
| Unknown       | TI AM335x BeagleBone Bla... | [14d6cfb7a4](https://bsd-hardware.info/?probe=14d6cfb7a4) | Dec 27, 2021 |
| Unknown       | TI AM335x BeagleBone Bla... | [ce75fa56bd](https://bsd-hardware.info/?probe=ce75fa56bd) | Dec 27, 2021 |
| Unknown       | TI AM335x BeagleBone Bla... | [612825abe3](https://bsd-hardware.info/?probe=612825abe3) | Dec 27, 2021 |
| khadas        | edge-v                      | [42c428aac0](https://bsd-hardware.info/?probe=42c428aac0) | Dec 26, 2021 |
| Gigabyte      | 970A-DS3P                   | [0918f0a5b9](https://bsd-hardware.info/?probe=0918f0a5b9) | Dec 25, 2021 |
| ASUSTek       | PRIME B350M-A               | [b0aa3885bb](https://bsd-hardware.info/?probe=b0aa3885bb) | Dec 25, 2021 |
| Acer          | Revo RN86                   | [6d184a1e62](https://bsd-hardware.info/?probe=6d184a1e62) | Dec 23, 2021 |
| Gigabyte      | E3000N                      | [eb0ba1b296](https://bsd-hardware.info/?probe=eb0ba1b296) | Dec 22, 2021 |
| HP            | 1850                        | [aa737033c4](https://bsd-hardware.info/?probe=aa737033c4) | Dec 21, 2021 |
| HP            | 1850                        | [17f42cda78](https://bsd-hardware.info/?probe=17f42cda78) | Dec 21, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [5cc62c68f9](https://bsd-hardware.info/?probe=5cc62c68f9) | Dec 21, 2021 |
| ASRock        | H110M-DGS                   | [40c4553adb](https://bsd-hardware.info/?probe=40c4553adb) | Dec 21, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [bc55ac50d1](https://bsd-hardware.info/?probe=bc55ac50d1) | Dec 20, 2021 |
| Acer          | Revo RN86                   | [68541bb331](https://bsd-hardware.info/?probe=68541bb331) | Dec 20, 2021 |
| Acer          | Aspire XC-895 V:1.0         | [58440d7663](https://bsd-hardware.info/?probe=58440d7663) | Dec 20, 2021 |
| MSI           | MS-9852 10                  | [4b851eef0a](https://bsd-hardware.info/?probe=4b851eef0a) | Dec 19, 2021 |
| ASUSTek       | P5G41T-M                    | [44bba395e8](https://bsd-hardware.info/?probe=44bba395e8) | Dec 13, 2021 |
| ASUSTek       | P5G41T-M                    | [1fb865c4ae](https://bsd-hardware.info/?probe=1fb865c4ae) | Dec 09, 2021 |
| Gigabyte      | Z68XP-UD3                   | [9fca53da56](https://bsd-hardware.info/?probe=9fca53da56) | Dec 08, 2021 |
| ASUSTek       | P5B                         | [93b542ab79](https://bsd-hardware.info/?probe=93b542ab79) | Dec 06, 2021 |
| Gigabyte      | GA-8S661FXM-775             | [3a64909558](https://bsd-hardware.info/?probe=3a64909558) | Dec 06, 2021 |
| Gigabyte      | MZGLKBP-00                  | [e713e3adee](https://bsd-hardware.info/?probe=e713e3adee) | Dec 05, 2021 |
| Unknown       | Q2XX V1.1                   | [66d6a26e35](https://bsd-hardware.info/?probe=66d6a26e35) | Dec 04, 2021 |
| Unknown       | Unknown                     | [a91c9ec877](https://bsd-hardware.info/?probe=a91c9ec877) | Dec 04, 2021 |
| Gigabyte      | H81M-S2PV                   | [0d4c532744](https://bsd-hardware.info/?probe=0d4c532744) | Nov 29, 2021 |
| Firefly       | roc-rk3399-pc-plus          | [dab56eef53](https://bsd-hardware.info/?probe=dab56eef53) | Nov 07, 2021 |
| Firefly       | roc-rk3399-pc-plus          | [f26b302e43](https://bsd-hardware.info/?probe=f26b302e43) | Nov 07, 2021 |
| Unknown       | Intel X79                   | [044908e7c3](https://bsd-hardware.info/?probe=044908e7c3) | Oct 30, 2021 |
| Gigabyte      | Z77X-UD3H                   | [4c9b877754](https://bsd-hardware.info/?probe=4c9b877754) | Oct 29, 2021 |
| HP            | 0A60h                       | [5c227c5b61](https://bsd-hardware.info/?probe=5c227c5b61) | Oct 27, 2021 |
| Radxa         | rock-pi-4                   | [767ef0f0a6](https://bsd-hardware.info/?probe=767ef0f0a6) | Oct 27, 2021 |
| Radxa         | rock-pi-4                   | [fcd3e65f7e](https://bsd-hardware.info/?probe=fcd3e65f7e) | Oct 26, 2021 |
| Acer          | RS880M05                    | [4718f0cb0c](https://bsd-hardware.info/?probe=4718f0cb0c) | Oct 21, 2021 |
| Radxa         | rock-pi-4                   | [876564310f](https://bsd-hardware.info/?probe=876564310f) | Oct 19, 2021 |
| Unknown       | Unknown                     | [9716564d5e](https://bsd-hardware.info/?probe=9716564d5e) | Oct 19, 2021 |
| Firefly       | roc-rk3399-pc-plus          | [39c78ac754](https://bsd-hardware.info/?probe=39c78ac754) | Oct 19, 2021 |
| ASUSTek       | P5P43TD PRO                 | [2870e26de1](https://bsd-hardware.info/?probe=2870e26de1) | Oct 17, 2021 |
| Firefly       | roc-rk3399-pc-plus          | [5173ffc13b](https://bsd-hardware.info/?probe=5173ffc13b) | Oct 17, 2021 |
| Dell          | 0Y7WYT A00                  | [1de7ed2a67](https://bsd-hardware.info/?probe=1de7ed2a67) | Oct 16, 2021 |
| Lenovo        | SHARKBAY No DPK             | [e762f9146e](https://bsd-hardware.info/?probe=e762f9146e) | Oct 16, 2021 |
| ASUSTek       | P10S-I Series               | [d086bf947a](https://bsd-hardware.info/?probe=d086bf947a) | Oct 15, 2021 |
| ASUSTek       | F2A85-M                     | [b4e3f33e5c](https://bsd-hardware.info/?probe=b4e3f33e5c) | Oct 14, 2021 |
| Lenovo        | SHARKBAY No DPK             | [14dcd924b5](https://bsd-hardware.info/?probe=14dcd924b5) | Oct 13, 2021 |
| Gigabyte      | B450 AORUS M                | [d09f63f257](https://bsd-hardware.info/?probe=d09f63f257) | Oct 07, 2021 |
| Intel         | J1900                       | [9d6c7612d3](https://bsd-hardware.info/?probe=9d6c7612d3) | Oct 05, 2021 |
| MSI           | MPG X570 GAMING PRO CARB... | [bd312d1c88](https://bsd-hardware.info/?probe=bd312d1c88) | Oct 03, 2021 |
| Unknown       | Unknown                     | [b45dad63f6](https://bsd-hardware.info/?probe=b45dad63f6) | Sep 20, 2021 |
| Unknown       | Unknown                     | [ed7c1c1f3b](https://bsd-hardware.info/?probe=ed7c1c1f3b) | Sep 20, 2021 |
| Firefly       | roc-rk3399-pc-plus          | [198c4264f9](https://bsd-hardware.info/?probe=198c4264f9) | Sep 16, 2021 |
| Firefly       | roc-rk3399-pc-plus          | [d05c3ba858](https://bsd-hardware.info/?probe=d05c3ba858) | Sep 15, 2021 |
| Firefly       | roc-rk3399-pc-plus          | [062602e8db](https://bsd-hardware.info/?probe=062602e8db) | Sep 15, 2021 |
| ASRock        | B450M Pro4-F                | [ae1765efd5](https://bsd-hardware.info/?probe=ae1765efd5) | Sep 10, 2021 |
| Gigabyte      | Z68P-DS3                    | [9a2545337b](https://bsd-hardware.info/?probe=9a2545337b) | Sep 09, 2021 |
| ASUSTek       | P5KPL-CM                    | [01ac3a91d0](https://bsd-hardware.info/?probe=01ac3a91d0) | Sep 01, 2021 |
| ASUSTek       | PRIME Z590-P                | [aeb23122b6](https://bsd-hardware.info/?probe=aeb23122b6) | Aug 31, 2021 |
| Intel         | DG33BU AAD79951-408         | [e8f4f644e3](https://bsd-hardware.info/?probe=e8f4f644e3) | Aug 30, 2021 |
| ASUSTek       | P4P800-VM                   | [f23a539453](https://bsd-hardware.info/?probe=f23a539453) | Aug 30, 2021 |
| Unknown       | Q2XX V1.1                   | [5ca9aa0bf2](https://bsd-hardware.info/?probe=5ca9aa0bf2) | Aug 19, 2021 |
| Gigabyte      | HA65M-D2H-B3                | [fc9b50bb85](https://bsd-hardware.info/?probe=fc9b50bb85) | Aug 16, 2021 |
| Supermicro    | X10DRH-CT                   | [6ccb3c09d6](https://bsd-hardware.info/?probe=6ccb3c09d6) | Aug 12, 2021 |
| Pegatron      | IPPCR-SS                    | [8a7fc2689b](https://bsd-hardware.info/?probe=8a7fc2689b) | Aug 09, 2021 |
| MSI           | H81M-P33                    | [6dcb3aa559](https://bsd-hardware.info/?probe=6dcb3aa559) | Aug 05, 2021 |
| ASRock        | X570 Pro4                   | [011fb96fe0](https://bsd-hardware.info/?probe=011fb96fe0) | Aug 04, 2021 |
| Gigabyte      | PH67A-D3-B3                 | [73dff53f04](https://bsd-hardware.info/?probe=73dff53f04) | Jul 23, 2021 |
| HP            | ProLiant DL360e Gen8        | [30eeb098b0](https://bsd-hardware.info/?probe=30eeb098b0) | Jul 10, 2021 |
| HP            | ProLiant DL320 G5           | [3b4ee33976](https://bsd-hardware.info/?probe=3b4ee33976) | Jul 10, 2021 |
| Foxconn       | AT-7000 Series              | [3802fb98b5](https://bsd-hardware.info/?probe=3802fb98b5) | Jul 10, 2021 |
| MSI           | H81M-E33                    | [c9fda90944](https://bsd-hardware.info/?probe=c9fda90944) | Jul 08, 2021 |
| Pegatron      | IPPCR-SS                    | [86b2e85d24](https://bsd-hardware.info/?probe=86b2e85d24) | Jul 05, 2021 |
| ASUSTek       | M5A97 R2.0                  | [e7a0dfcecf](https://bsd-hardware.info/?probe=e7a0dfcecf) | Jun 28, 2021 |
| Supermicro    | X10DRH-CT                   | [583e9e5a66](https://bsd-hardware.info/?probe=583e9e5a66) | Jun 26, 2021 |
| ECS           | A740GM-M                    | [a9d9106f11](https://bsd-hardware.info/?probe=a9d9106f11) | Jun 24, 2021 |
| Gigabyte      | GA-IMB370TN                 | [449fc82ff8](https://bsd-hardware.info/?probe=449fc82ff8) | Jun 21, 2021 |
| MSI           | H110M PRO-VH PLUS           | [45b842180e](https://bsd-hardware.info/?probe=45b842180e) | Jun 20, 2021 |
| ASUSTek       | H110I-PLUS                  | [0cb30b464d](https://bsd-hardware.info/?probe=0cb30b464d) | Jun 17, 2021 |
| ASUSTek       | M4A78LT-M                   | [0c8d6cd661](https://bsd-hardware.info/?probe=0c8d6cd661) | Jun 14, 2021 |
| Intel         | X79 V2.72A                  | [88173bcf06](https://bsd-hardware.info/?probe=88173bcf06) | Jun 14, 2021 |
| ASUSTek       | P5K SE/EPU                  | [60d9b24b69](https://bsd-hardware.info/?probe=60d9b24b69) | Jun 13, 2021 |
| Gigabyte      | GA-IMB370TN                 | [b486e670fe](https://bsd-hardware.info/?probe=b486e670fe) | Jun 02, 2021 |
| Biostar       | TH67B                       | [1f2321ec41](https://bsd-hardware.info/?probe=1f2321ec41) | Jun 01, 2021 |
| ASUSTek       | P5Q-E                       | [d9657e7246](https://bsd-hardware.info/?probe=d9657e7246) | Jun 01, 2021 |
| ASUSTek       | PRIME Z590-P                | [8c06f6b716](https://bsd-hardware.info/?probe=8c06f6b716) | Jun 01, 2021 |
| Apple         | PowerMac10,1                | [d098ba539d](https://bsd-hardware.info/?probe=d098ba539d) | May 27, 2021 |
| ASUSTek       | P7H55-M/USB3                | [87068a97be](https://bsd-hardware.info/?probe=87068a97be) | May 26, 2021 |
| Unknown       | Unknown                     | [f9fa9ae41a](https://bsd-hardware.info/?probe=f9fa9ae41a) | May 24, 2021 |
| Acer          | Revo RN86                   | [ec302a221a](https://bsd-hardware.info/?probe=ec302a221a) | May 15, 2021 |
| Unknown       | Unknown                     | [364a778de1](https://bsd-hardware.info/?probe=364a778de1) | May 14, 2021 |
| ASUSTek       | Z87-PLUS                    | [629d15378d](https://bsd-hardware.info/?probe=629d15378d) | May 10, 2021 |
| ASUSTek       | H81M-K                      | [ae105fb8bc](https://bsd-hardware.info/?probe=ae105fb8bc) | May 09, 2021 |
| ASUSTek       | Maximus II Formula          | [493bb4da66](https://bsd-hardware.info/?probe=493bb4da66) | May 07, 2021 |
| Gigabyte      | X58A-UD5                    | [24502c7f7b](https://bsd-hardware.info/?probe=24502c7f7b) | May 04, 2021 |
| ASUSTek       | P10S-I Series               | [6548ae7d88](https://bsd-hardware.info/?probe=6548ae7d88) | May 01, 2021 |
| ASUSTek       | SABERTOOTH Z97 MARK 2       | [8055ed41df](https://bsd-hardware.info/?probe=8055ed41df) | Apr 25, 2021 |
| Gigabyte      | F2A75M-HD2                  | [18a74377ac](https://bsd-hardware.info/?probe=18a74377ac) | Apr 25, 2021 |
| Unknown       | Q2XX V1.1                   | [5c7ea7fb7d](https://bsd-hardware.info/?probe=5c7ea7fb7d) | Apr 24, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [ab8235808d](https://bsd-hardware.info/?probe=ab8235808d) | Apr 23, 2021 |
| Gigabyte      | C1037UN-EU                  | [a379c24586](https://bsd-hardware.info/?probe=a379c24586) | Apr 19, 2021 |
| Gigabyte      | GA-IMB370TN                 | [7c77a33f75](https://bsd-hardware.info/?probe=7c77a33f75) | Apr 18, 2021 |
| Gigabyte      | GA-IMB370TN                 | [60053693cb](https://bsd-hardware.info/?probe=60053693cb) | Apr 17, 2021 |
| Unknown       | Unknown                     | [48090193c1](https://bsd-hardware.info/?probe=48090193c1) | Apr 17, 2021 |
| Unknown       | Unknown                     | [1c4a81b9a5](https://bsd-hardware.info/?probe=1c4a81b9a5) | Apr 17, 2021 |
| Unknown       | Unknown                     | [7b295345e6](https://bsd-hardware.info/?probe=7b295345e6) | Apr 17, 2021 |
| Unknown       | Unknown                     | [0c708350cd](https://bsd-hardware.info/?probe=0c708350cd) | Apr 17, 2021 |
| Gigabyte      | GA-IMB370TN                 | [513027c242](https://bsd-hardware.info/?probe=513027c242) | Apr 13, 2021 |
| Gigabyte      | GA-IMB370TN                 | [8023a25ccb](https://bsd-hardware.info/?probe=8023a25ccb) | Mar 29, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [ec9e43382e](https://bsd-hardware.info/?probe=ec9e43382e) | Mar 25, 2021 |
| ASRock        | H71M-DGS                    | [d05d6281d3](https://bsd-hardware.info/?probe=d05d6281d3) | Mar 21, 2021 |
| ASUSTek       | P8H77-I                     | [46d36c6b23](https://bsd-hardware.info/?probe=46d36c6b23) | Mar 21, 2021 |
| Intel         | PB_1900A V2.1               | [a2378c3bee](https://bsd-hardware.info/?probe=a2378c3bee) | Mar 17, 2021 |
| ASUSTek       | AT5NM10T-I                  | [7c26a8b81e](https://bsd-hardware.info/?probe=7c26a8b81e) | Mar 12, 2021 |
| ASRock        | Q1900M                      | [f366c06928](https://bsd-hardware.info/?probe=f366c06928) | Mar 09, 2021 |
| Gigabyte      | EG43M-S2H                   | [f6eaa55ada](https://bsd-hardware.info/?probe=f6eaa55ada) | Mar 06, 2021 |
| ASUSTek       | STRIX B250F GAMING          | [cf965a3a5b](https://bsd-hardware.info/?probe=cf965a3a5b) | Mar 06, 2021 |
| Gigabyte      | 8IG1000MK                   | [49ee1efce0](https://bsd-hardware.info/?probe=49ee1efce0) | Mar 01, 2021 |
| Kontron       | KT965/ATXP 61420000         | [8755a0003d](https://bsd-hardware.info/?probe=8755a0003d) | Mar 01, 2021 |
| Lenovo        | Board                       | [395ef09e6d](https://bsd-hardware.info/?probe=395ef09e6d) | Feb 25, 2021 |
| Lenovo        | Board                       | [e7d30d4253](https://bsd-hardware.info/?probe=e7d30d4253) | Feb 25, 2021 |
| Lenovo        | Board                       | [96fbaf0644](https://bsd-hardware.info/?probe=96fbaf0644) | Feb 25, 2021 |
| ASRock        | G31M-VS2                    | [6c7150dc1b](https://bsd-hardware.info/?probe=6c7150dc1b) | Feb 24, 2021 |
| Acer          | TPDS05 R3700                | [651f8a2bb4](https://bsd-hardware.info/?probe=651f8a2bb4) | Feb 23, 2021 |
| PC Engines    | APU2                        | [02a107a767](https://bsd-hardware.info/?probe=02a107a767) | Feb 23, 2021 |
| ASRock        | J4205-ITX                   | [c8e0b22858](https://bsd-hardware.info/?probe=c8e0b22858) | Feb 23, 2021 |
| ASUSTek       | P8Z77-V LX                  | [8390039d0b](https://bsd-hardware.info/?probe=8390039d0b) | Feb 22, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [8e52de9bec](https://bsd-hardware.info/?probe=8e52de9bec) | Feb 19, 2021 |
| ASRock        | Z170 Pro4/D3                | [7df0653726](https://bsd-hardware.info/?probe=7df0653726) | Feb 19, 2021 |
| ASUSTek       | H87I-PLUS                   | [8f8f08f763](https://bsd-hardware.info/?probe=8f8f08f763) | Feb 17, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [ae42a14150](https://bsd-hardware.info/?probe=ae42a14150) | Feb 16, 2021 |
| Supermicro    | A2SDi-8C-HLN4F              | [24551b886c](https://bsd-hardware.info/?probe=24551b886c) | Feb 16, 2021 |
| ASRock        | B550M Pro4                  | [61a5641019](https://bsd-hardware.info/?probe=61a5641019) | Feb 14, 2021 |
| ASUSTek       | PRIME B450M-A               | [ac6b550ff4](https://bsd-hardware.info/?probe=ac6b550ff4) | Feb 12, 2021 |
| ASUSTek       | P8H77-V                     | [aaaffba650](https://bsd-hardware.info/?probe=aaaffba650) | Feb 11, 2021 |
| ASUSTek       | P5GDC Pro                   | [ca50169bf4](https://bsd-hardware.info/?probe=ca50169bf4) | Feb 11, 2021 |
| Gigabyte      | J3455N-D3H                  | [65e5edcfd7](https://bsd-hardware.info/?probe=65e5edcfd7) | Feb 11, 2021 |
| ASRock        | J3455M                      | [0493901aff](https://bsd-hardware.info/?probe=0493901aff) | Feb 10, 2021 |
| ASRock        | H61M-S                      | [f7b01b5274](https://bsd-hardware.info/?probe=f7b01b5274) | Feb 08, 2021 |
| Gigabyte      | Z68A-D3H-B3                 | [e1c3b89d0d](https://bsd-hardware.info/?probe=e1c3b89d0d) | Feb 06, 2021 |
| Gigabyte      | J3455N-D3H                  | [e2fd3451b6](https://bsd-hardware.info/?probe=e2fd3451b6) | Jan 26, 2021 |
| ASUSTek       | PRIME X370-PRO              | [2a81a1bd1f](https://bsd-hardware.info/?probe=2a81a1bd1f) | Jan 24, 2021 |
| MSI           | MS-7235                     | [6a0d60ad2c](https://bsd-hardware.info/?probe=6a0d60ad2c) | Jan 21, 2021 |
| Dell          | 0Y7WYT A00                  | [4af9b92154](https://bsd-hardware.info/?probe=4af9b92154) | Jan 19, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [ad33eaab8a](https://bsd-hardware.info/?probe=ad33eaab8a) | Jan 19, 2021 |
| Centerm       | C30                         | [862ffd88e6](https://bsd-hardware.info/?probe=862ffd88e6) | Dec 16, 2020 |
| Gigabyte      | Z68P-DS3                    | [a1fe36fd99](https://bsd-hardware.info/?probe=a1fe36fd99) | Dec 16, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [fb6286f788](https://bsd-hardware.info/?probe=fb6286f788) | Dec 13, 2020 |
| ASUSTek       | P4P800-VM                   | [4fe4c14195](https://bsd-hardware.info/?probe=4fe4c14195) | Dec 05, 2020 |
| Acer          | Aspire XC-895 V:1.0         | [c5017eff06](https://bsd-hardware.info/?probe=c5017eff06) | Dec 04, 2020 |
| PC Engines    | APU2                        | [90d68eee14](https://bsd-hardware.info/?probe=90d68eee14) | Dec 04, 2020 |
| PC Engines    | APU2                        | [fab3041b1e](https://bsd-hardware.info/?probe=fab3041b1e) | Dec 04, 2020 |
| Gigabyte      | Unknown                     | [8a9ae48d42](https://bsd-hardware.info/?probe=8a9ae48d42) | Dec 01, 2020 |
| ASRock        | N68-GE                      | [ce9159c2fa](https://bsd-hardware.info/?probe=ce9159c2fa) | Nov 30, 2020 |
| ASRock        | N68-GE                      | [59cef03993](https://bsd-hardware.info/?probe=59cef03993) | Nov 30, 2020 |
| Unknown       | Unknown                     | [153be3caa3](https://bsd-hardware.info/?probe=153be3caa3) | Nov 28, 2020 |
| ASRock        | N68-GE                      | [028eabaec2](https://bsd-hardware.info/?probe=028eabaec2) | Nov 28, 2020 |
| ASUSTek       | H97M-E                      | [c3230a9065](https://bsd-hardware.info/?probe=c3230a9065) | Nov 23, 2020 |
| ASUSTek       | P5GDC Pro                   | [8776b186c1](https://bsd-hardware.info/?probe=8776b186c1) | Nov 14, 2020 |
| ASRock        | X570 Steel Legend           | [8a79e3f5e4](https://bsd-hardware.info/?probe=8a79e3f5e4) | Nov 11, 2020 |
| Pegatron      | 1.03                        | [e660e12e3c](https://bsd-hardware.info/?probe=e660e12e3c) | Nov 10, 2020 |
| Gigabyte      | M61SME-S2L                  | [d8809eb5e7](https://bsd-hardware.info/?probe=d8809eb5e7) | Nov 09, 2020 |
| Gigabyte      | M61SME-S2L                  | [e5f658c70a](https://bsd-hardware.info/?probe=e5f658c70a) | Nov 09, 2020 |
| MSI           | Z97S SLI Krait Edition      | [c766aab801](https://bsd-hardware.info/?probe=c766aab801) | Nov 09, 2020 |
| Pegatron      | SKLD4-P1                    | [ea548b4c71](https://bsd-hardware.info/?probe=ea548b4c71) | Nov 08, 2020 |
| ASUSTek       | B75M-A                      | [43ece33e8c](https://bsd-hardware.info/?probe=43ece33e8c) | Oct 31, 2020 |
| ASRock        | J3455-ITX                   | [52fe99a6d6](https://bsd-hardware.info/?probe=52fe99a6d6) | Oct 29, 2020 |
| Gigabyte      | X58A-UD5                    | [6e642641e5](https://bsd-hardware.info/?probe=6e642641e5) | Oct 25, 2020 |
| ASUSTek       | B150M-K                     | [135db0e455](https://bsd-hardware.info/?probe=135db0e455) | Oct 22, 2020 |
| Unknown       | Unknown                     | [223aa9e0a3](https://bsd-hardware.info/?probe=223aa9e0a3) | Oct 22, 2020 |
| ASUSTek       | Z170-A                      | [a1c6966373](https://bsd-hardware.info/?probe=a1c6966373) | Oct 21, 2020 |
| ASUSTek       | Z170-K                      | [19cb3ccc34](https://bsd-hardware.info/?probe=19cb3ccc34) | Oct 20, 2020 |
| Intel         | S3000AH                     | [f5b858601a](https://bsd-hardware.info/?probe=f5b858601a) | Oct 20, 2020 |
| Unknown       | Unknown                     | [bedb4a4b37](https://bsd-hardware.info/?probe=bedb4a4b37) | Oct 20, 2020 |
| ASUSTek       | P10S-I Series               | [1a0e9f0100](https://bsd-hardware.info/?probe=1a0e9f0100) | Oct 19, 2020 |
| IBM           | Board                       | [af2f64a7a8](https://bsd-hardware.info/?probe=af2f64a7a8) | Oct 19, 2020 |
| Foxconn       | AT-7000 Series              | [dc7b96e637](https://bsd-hardware.info/?probe=dc7b96e637) | Oct 19, 2020 |
| Foxconn       | AT-7000 Series              | [0184fcedcf](https://bsd-hardware.info/?probe=0184fcedcf) | Oct 19, 2020 |
| Unknown       | Unknown                     | [e36fc2b2b2](https://bsd-hardware.info/?probe=e36fc2b2b2) | Oct 19, 2020 |
| ASRock        | N68C-S UCC                  | [027fbd78f5](https://bsd-hardware.info/?probe=027fbd78f5) | Oct 19, 2020 |
| MSI           | B450M MORTAR MAX            | [1123cb92ba](https://bsd-hardware.info/?probe=1123cb92ba) | Oct 04, 2020 |
| ASUSTek       | H81M-D PLUS                 | [95b75130f4](https://bsd-hardware.info/?probe=95b75130f4) | Sep 26, 2020 |
| Gigabyte      | C246-WU4-CF                 | [4117a39b03](https://bsd-hardware.info/?probe=4117a39b03) | Sep 23, 2020 |
| Acer          | Revo RN86                   | [d1b1775be3](https://bsd-hardware.info/?probe=d1b1775be3) | Sep 23, 2020 |
| ASUSTek       | H81M-D PLUS                 | [e8ab84404c](https://bsd-hardware.info/?probe=e8ab84404c) | Sep 22, 2020 |
| Acer          | Revo RN86                   | [c6b2c64d14](https://bsd-hardware.info/?probe=c6b2c64d14) | Sep 20, 2020 |
| ASUSTek       | H81M-D PLUS                 | [036d9cfecb](https://bsd-hardware.info/?probe=036d9cfecb) | Sep 19, 2020 |
| ASUSTek       | H81M-D PLUS                 | [7be45f1bec](https://bsd-hardware.info/?probe=7be45f1bec) | Sep 19, 2020 |
| ASUSTek       | H81M-D PLUS                 | [582b037126](https://bsd-hardware.info/?probe=582b037126) | Sep 13, 2020 |
| ASUSTek       | H81M-D PLUS                 | [0567f88943](https://bsd-hardware.info/?probe=0567f88943) | Sep 13, 2020 |
| ASUSTek       | H81M-D PLUS                 | [e9dd488fe0](https://bsd-hardware.info/?probe=e9dd488fe0) | Sep 13, 2020 |
| ASUSTek       | P5QD TURBO                  | [598e77539b](https://bsd-hardware.info/?probe=598e77539b) | Aug 21, 2020 |
| ASUSTek       | P5QD TURBO                  | [eb8d562618](https://bsd-hardware.info/?probe=eb8d562618) | Aug 21, 2020 |
| ASUSTek       | P5QD TURBO                  | [e210609359](https://bsd-hardware.info/?probe=e210609359) | Aug 21, 2020 |
| Gigabyte      | X58A-UD5                    | [63a429ad0e](https://bsd-hardware.info/?probe=63a429ad0e) | Aug 16, 2020 |
| ASUSTek       | P8P67                       | [c61cac017e](https://bsd-hardware.info/?probe=c61cac017e) | Aug 06, 2020 |
| ASUSTek       | K8N-VM                      | [0ddf168986](https://bsd-hardware.info/?probe=0ddf168986) | Aug 06, 2020 |
| ASUSTek       | ROG Maximus XI HERO         | [4f4cb01708](https://bsd-hardware.info/?probe=4f4cb01708) | Aug 05, 2020 |
| MSI           | H61M-P20                    | [fefac5637b](https://bsd-hardware.info/?probe=fefac5637b) | Aug 03, 2020 |
| ASRock        | E350M1                      | [08eec78cdf](https://bsd-hardware.info/?probe=08eec78cdf) | Jul 25, 2020 |
| ASUSTek       | P5Q DELUXE                  | [eb3f0a19ae](https://bsd-hardware.info/?probe=eb3f0a19ae) | Jul 25, 2020 |
| Pegatron      | 2A73                        | [05dea28605](https://bsd-hardware.info/?probe=05dea28605) | Jul 21, 2020 |
| Supermicro    | NSM5200A                    | [49a39eb60f](https://bsd-hardware.info/?probe=49a39eb60f) | Jul 15, 2020 |
| Gigabyte      | GA-790FXTA-UD5              | [667d98ccb2](https://bsd-hardware.info/?probe=667d98ccb2) | Jul 15, 2020 |
| ASRock        | B450 Pro4                   | [836bf04a97](https://bsd-hardware.info/?probe=836bf04a97) | Jul 15, 2020 |
| ASUSTek       | P5KPL-AM                    | [daaa05bbf4](https://bsd-hardware.info/?probe=daaa05bbf4) | Jul 15, 2020 |
| Gigabyte      | Z77-D3H                     | [97c6656398](https://bsd-hardware.info/?probe=97c6656398) | Jul 12, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [08dd1b91a8](https://bsd-hardware.info/?probe=08dd1b91a8) | Jun 30, 2020 |
| Foxconn       | nT-330i                     | [79ab8efb37](https://bsd-hardware.info/?probe=79ab8efb37) | Jun 29, 2020 |
| ASRock        | J3455-ITX                   | [1c8e18b787](https://bsd-hardware.info/?probe=1c8e18b787) | Jun 15, 2020 |
| Unknown       | Unknown                     | [ee9f9df2c1](https://bsd-hardware.info/?probe=ee9f9df2c1) | May 31, 2020 |
| Unknown       | Unknown                     | [6034ab8e6e](https://bsd-hardware.info/?probe=6034ab8e6e) | May 31, 2020 |
| ASRock        | Q1900M                      | [8787d15bc5](https://bsd-hardware.info/?probe=8787d15bc5) | May 31, 2020 |
| ASRock        | Q1900M                      | [79fe3017ef](https://bsd-hardware.info/?probe=79fe3017ef) | May 31, 2020 |
| Gigabyte      | M68MT-S2P                   | [08534174df](https://bsd-hardware.info/?probe=08534174df) | May 27, 2020 |
| Unknown       | TI AM335x BeagleBone Bla... | [8e0f831fd8](https://bsd-hardware.info/?probe=8e0f831fd8) | May 27, 2020 |
| Gigabyte      | M68MT-S2P                   | [03ea0992c4](https://bsd-hardware.info/?probe=03ea0992c4) | May 27, 2020 |
| IBM           | Board                       | [1bcc2b8e0b](https://bsd-hardware.info/?probe=1bcc2b8e0b) | May 27, 2020 |
| Unknown       | TI AM335x BeagleBone Bla... | [74b9526162](https://bsd-hardware.info/?probe=74b9526162) | May 27, 2020 |
| Gigabyte      | B450M GAMING                | [b4c4c676c4](https://bsd-hardware.info/?probe=b4c4c676c4) | May 26, 2020 |
| Unknown       | YL-J3060L2                  | [55be2fab24](https://bsd-hardware.info/?probe=55be2fab24) | May 26, 2020 |
| Gigabyte      | GA-MA78GM-UD2H              | [66bce86f33](https://bsd-hardware.info/?probe=66bce86f33) | May 26, 2020 |
| Acer          | WMCP78M                     | [db1e7a52b9](https://bsd-hardware.info/?probe=db1e7a52b9) | May 25, 2020 |
| Acer          | WMCP78M                     | [d9b08cfc0c](https://bsd-hardware.info/?probe=d9b08cfc0c) | May 25, 2020 |
| ASUSTek       | P5Q SE PLUS                 | [84e9e67aa2](https://bsd-hardware.info/?probe=84e9e67aa2) | May 25, 2020 |
| ASUSTek       | P4P800-VM                   | [8b9481baf2](https://bsd-hardware.info/?probe=8b9481baf2) | May 25, 2020 |
| ASUSTek       | P4P800-VM                   | [33c4579f99](https://bsd-hardware.info/?probe=33c4579f99) | May 25, 2020 |
| MSI           | MS-7255                     | [3984f45545](https://bsd-hardware.info/?probe=3984f45545) | May 25, 2020 |
| Gigabyte      | 945GM-S2                    | [59e3624de7](https://bsd-hardware.info/?probe=59e3624de7) | May 25, 2020 |
| Gigabyte      | F2A75M-HD2                  | [09bfdeafbd](https://bsd-hardware.info/?probe=09bfdeafbd) | May 25, 2020 |
| ASRock        | J4205-ITX                   | [bb67f0e80b](https://bsd-hardware.info/?probe=bb67f0e80b) | May 25, 2020 |
| ASUSTek       | Z87-EXPERT                  | [9f0ad7bbcf](https://bsd-hardware.info/?probe=9f0ad7bbcf) | May 25, 2020 |
| Supermicro    | X11DPH-T                    | [1db4784753](https://bsd-hardware.info/?probe=1db4784753) | May 25, 2020 |
| Supermicro    | X11DPH-T                    | [79aea35f1f](https://bsd-hardware.info/?probe=79aea35f1f) | May 25, 2020 |
| ASUSTek       | P5M2                        | [c1f04b3a84](https://bsd-hardware.info/?probe=c1f04b3a84) | May 25, 2020 |
| ASUSTek       | P6T SE                      | [66bbed8d59](https://bsd-hardware.info/?probe=66bbed8d59) | May 25, 2020 |
| ASUSTek       | P6T SE                      | [6eb355eabd](https://bsd-hardware.info/?probe=6eb355eabd) | May 25, 2020 |
| Gigabyte      | EX58-UD4                    | [e7f015c6da](https://bsd-hardware.info/?probe=e7f015c6da) | May 25, 2020 |
| ASUSTek       | P5Q                         | [97732c8106](https://bsd-hardware.info/?probe=97732c8106) | May 25, 2020 |
| ASUSTek       | P5GD2-Deluxe                | [5b1dc84da5](https://bsd-hardware.info/?probe=5b1dc84da5) | May 25, 2020 |
| Acer          | WMCP78M                     | [55755e9ab9](https://bsd-hardware.info/?probe=55755e9ab9) | May 25, 2020 |
| ASUSTek       | P5K-E                       | [a1b81962ac](https://bsd-hardware.info/?probe=a1b81962ac) | May 25, 2020 |
| ASUSTek       | P5K-E                       | [8f72d18bff](https://bsd-hardware.info/?probe=8f72d18bff) | May 25, 2020 |
| Gigabyte      | Z68P-DS3                    | [c06e03cda0](https://bsd-hardware.info/?probe=c06e03cda0) | May 25, 2020 |
| Intel         | DN2820FYK H24582-203        | [6cb240a9f6](https://bsd-hardware.info/?probe=6cb240a9f6) | May 25, 2020 |
| ASUSTek       | B75M-PLUS                   | [4620a00ccc](https://bsd-hardware.info/?probe=4620a00ccc) | May 25, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| helloSystem 0.7.0    | 20       | 7.09%   |
| OpenBSD 6.8          | 19       | 6.74%   |
| FreeBSD 12.1-p5      | 15       | 5.32%   |
| FreeBSD 13.0         | 14       | 4.96%   |
| OpenBSD 7.1          | 10       | 3.55%   |
| helloSystem 0.5.0    | 9        | 3.19%   |
| FreeBSD 13.0-STABLE  | 9        | 3.19%   |
| OpenBSD 7.0          | 8        | 2.84%   |
| OpenBSD 6.7          | 8        | 2.84%   |
| FreeBSD 12.1-STABLE  | 7        | 2.48%   |
| helloSystem 0.6.0    | 6        | 2.13%   |
| helloSystem 0.4.0    | 6        | 2.13%   |
| FreeBSD 13.1         | 6        | 2.13%   |
| FreeBSD 12.2         | 6        | 2.13%   |
| GhostBSD 20.04.02    | 5        | 1.77%   |
| FreeBSD 12.1-p7      | 5        | 1.77%   |
| OPNsense 22.1.6      | 4        | 1.42%   |
| OPNsense 21.1.5      | 4        | 1.42%   |
| OpenBSD 6.9          | 4        | 1.42%   |
| helloSystem 0.8.0    | 4        | 1.42%   |
| FreeBSD 14.0-CURRENT | 4        | 1.42%   |
| FreeBSD 12.2-p3      | 4        | 1.42%   |
| FreeBSD 12.2-p2      | 4        | 1.42%   |
| OPNsense 22.1.10     | 3        | 1.06%   |
| OPNsense 22.1        | 3        | 1.06%   |
| OPNsense 21.7.6      | 3        | 1.06%   |
| OPNsense 21.1.7      | 3        | 1.06%   |
| OPNsense 21.1.1      | 3        | 1.06%   |
| OPNsense 21.1        | 3        | 1.06%   |
| FreeBSD 13.0-p5      | 3        | 1.06%   |
| FreeBSD 13.0-CURRENT | 3        | 1.06%   |
| FreeBSD 12.2-p4      | 3        | 1.06%   |
| FreeBSD 12.1-p8      | 3        | 1.06%   |
| FreeBSD 12.1-p6      | 3        | 1.06%   |
| OPNsense 21.7.1      | 2        | 0.71%   |
| OPNsense 21.1.3      | 2        | 0.71%   |
| NomadBSD 5806f915    | 2        | 0.71%   |
| NetBSD 9.2           | 2        | 0.71%   |
| NetBSD 9.1           | 2        | 0.71%   |
| NetBSD 9.0           | 2        | 0.71%   |
| FreeBSD 13.1-STABLE  | 2        | 0.71%   |
| FreeBSD 13.0-p6      | 2        | 0.71%   |
| FreeBSD 13.0-p4      | 2        | 0.71%   |
| FreeBSD 13.0-p2      | 2        | 0.71%   |
| FreeBSD 13.0-p11     | 2        | 0.71%   |
| FreeBSD 12.3-p1      | 2        | 0.71%   |
| FreeBSD 12.2-STABLE  | 2        | 0.71%   |
| FreeBSD 12.1-p10     | 2        | 0.71%   |
| pfSense 2.4.4        | 1        | 0.35%   |
| PC-BSD 10.3          | 1        | 0.35%   |
| OPNsense 22.1.9      | 1        | 0.35%   |
| OPNsense 22.1.8      | 1        | 0.35%   |
| OPNsense 22.1.7      | 1        | 0.35%   |
| OPNsense 22.1.4      | 1        | 0.35%   |
| OPNsense 22.1.1      | 1        | 0.35%   |
| OPNsense 21.7.8      | 1        | 0.35%   |
| OPNsense 21.7.7      | 1        | 0.35%   |
| OPNsense 21.7.3      | 1        | 0.35%   |
| OPNsense 21.7.2      | 1        | 0.35%   |
| OPNsense 21.7        | 1        | 0.35%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| FreeBSD     | 103      | 42.39%  |
| helloSystem | 45       | 18.52%  |
| OpenBSD     | 38       | 15.64%  |
| OPNsense    | 35       | 14.4%   |
| NetBSD      | 7        | 2.88%   |
| GhostBSD    | 5        | 2.06%   |
| NomadBSD    | 3        | 1.23%   |
| MyBee       | 2        | 0.82%   |
| pfSense     | 1        | 0.41%   |
| PC-BSD      | 1        | 0.41%   |
| FuryBSD     | 1        | 0.41%   |
| DragonFly   | 1        | 0.41%   |
| ClonOS      | 1        | 0.41%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| amd64  | 212      | 89.83%  |
| i386   | 11       | 4.66%   |
| arm64  | 9        | 3.81%   |
| macppc | 1        | 0.42%   |
| evbarm | 1        | 0.42%   |
| armv7  | 1        | 0.42%   |
| arm    | 1        | 0.42%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 104      | 42.28%  |
| helloDesktop | 54       | 21.95%  |
| fvwm         | 19       | 7.72%   |
| KDE5         | 15       | 6.1%    |
| XFCE         | 14       | 5.69%   |
| MATE         | 11       | 4.47%   |
| Openbox      | 10       | 4.07%   |
| TWM          | 7        | 2.85%   |
| GNOME        | 5        | 2.03%   |
| Fluxbox      | 5        | 2.03%   |
| KWin         | 1        | 0.41%   |
| akonadi_newm | 1        | 0.41%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 128      | 53.56%  |
| Console | 111      | 46.44%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 153      | 64.02%  |
| SLiM    | 61       | 25.52%  |
| SDDM    | 12       | 5.02%   |
| LightDM | 7        | 2.93%   |
| XDM     | 3        | 1.26%   |
| GDM     | 3        | 1.26%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang           | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 82       | 33.47%  |
| ru_RU          | 74       | 30.2%   |
| en_US          | 57       | 23.27%  |
| C              | 29       | 11.84%  |
| ru_RU.KOI8-R   | 2        | 0.82%   |
| cv_RU.US-ASCII | 1        | 0.41%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 137      | 56.85%  |
| BIOS | 104      | 43.15%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Zfs     | 100      | 41.67%  |
| Ufs     | 82       | 34.17%  |
| Ffs     | 38       | 15.83%  |
| Cd9660  | 19       | 7.92%   |
| Hammer2 | 1        | 0.42%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 185      | 78.06%  |
| MBR     | 50       | 21.1%   |
| Unknown | 2        | 0.84%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 64       | 27.12%  |
| Gigabyte Technology | 42       | 17.8%   |
| ASRock              | 28       | 11.86%  |
| Unknown             | 18       | 7.63%   |
| MSI                 | 14       | 5.93%   |
| Intel               | 9        | 3.81%   |
| Pegatron            | 7        | 2.97%   |
| Hewlett-Packard     | 7        | 2.97%   |
| Supermicro          | 6        | 2.54%   |
| Acer                | 6        | 2.54%   |
| Lenovo              | 5        | 2.12%   |
| Dell                | 4        | 1.69%   |
| PC Engines          | 3        | 1.27%   |
| Huanan              | 3        | 1.27%   |
| Foxconn             | 2        | 0.85%   |
| Techvision          | 1        | 0.42%   |
| Sony                | 1        | 0.42%   |
| Shuttle             | 1        | 0.42%   |
| Radxa               | 1        | 0.42%   |
| MW                  | 1        | 0.42%   |
| Kraftway            | 1        | 0.42%   |
| Kontron             | 1        | 0.42%   |
| KOHJINSHA           | 1        | 0.42%   |
| khadas              | 1        | 0.42%   |
| Intel CNCTION-IAF   | 1        | 0.42%   |
| IBM                 | 1        | 0.42%   |
| Fujitsu             | 1        | 0.42%   |
| friendlyelec        | 1        | 0.42%   |
| Firefly             | 1        | 0.42%   |
| ECS                 | 1        | 0.42%   |
| Centerm             | 1        | 0.42%   |
| Biostar             | 1        | 0.42%   |
| Apple               | 1        | 0.42%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                                                  | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Unknown                                                               | 19       | 8.05%   |
| ASUS All Series                                                       | 7        | 2.97%   |
| PC Engines APU2                                                       | 3        | 1.27%   |
| Supermicro SSG-6029P-E1CR12L                                          | 2        | 0.85%   |
| Pegatron SAISHIAT2                                                    | 2        | 0.85%   |
| MSI MS-7817                                                           | 2        | 0.85%   |
| Huanan X79 INTEL (INTEL Xeon E5/Corei7 DMI2 - C600/C200 Cipset V2.49P | 2        | 0.85%   |
| HP ProLiant MicroServer                                               | 2        | 0.85%   |
| Gigabyte M68MT-S2P                                                    | 2        | 0.85%   |
| Gigabyte H310M S2 2.0                                                 | 2        | 0.85%   |
| Gigabyte GA-IMB370TN                                                  | 2        | 0.85%   |
| Gigabyte C1037UN-EU                                                   | 2        | 0.85%   |
| Gigabyte B450 AORUS M                                                 | 2        | 0.85%   |
| Dell OptiPlex 7040                                                    | 2        | 0.85%   |
| ASUS PRIME Z590-P                                                     | 2        | 0.85%   |
| ASUS P8Z77-V LX                                                       | 2        | 0.85%   |
| ASUS P6T SE                                                           | 2        | 0.85%   |
| ASUS P4P800-VM                                                        | 2        | 0.85%   |
| ASRock J4205-ITX                                                      | 2        | 0.85%   |
| Techvision TVI7309X                                                   | 1        | 0.42%   |
| Supermicro SYS-6028R-TRT                                              | 1        | 0.42%   |
| Supermicro SYS-5019A-FTN4                                             | 1        | 0.42%   |
| Supermicro SSG-6028R-E1CR12T                                          | 1        | 0.42%   |
| Supermicro NSM5200-06-EU                                              | 1        | 0.42%   |
| Sony VPCL22Z1R                                                        | 1        | 0.42%   |
| Shuttle DS20U                                                         | 1        | 0.42%   |
| Radxa rock-pi-4                                                       | 1        | 0.42%   |
| Pegatron SKLD4-P1                                                     | 1        | 0.42%   |
| Pegatron SAISHIAT                                                     | 1        | 0.42%   |
| Pegatron Pro 3010 Microtower PC                                       | 1        | 0.42%   |
| Pegatron IPPPV-D3G                                                    | 1        | 0.42%   |
| Pegatron Compaq dx2400 Microtower                                     | 1        | 0.42%   |
| MW GMLK-2_5G4L                                                        | 1        | 0.42%   |
| MSI MS-9A25                                                           | 1        | 0.42%   |
| MSI MS-7C96                                                           | 1        | 0.42%   |
| MSI MS-7B93                                                           | 1        | 0.42%   |
| MSI MS-7B89                                                           | 1        | 0.42%   |
| MSI MS-7A38                                                           | 1        | 0.42%   |
| MSI MS-7A15                                                           | 1        | 0.42%   |
| MSI MS-7922                                                           | 1        | 0.42%   |
| MSI MS-7816                                                           | 1        | 0.42%   |
| MSI MS-7788                                                           | 1        | 0.42%   |
| MSI MS-7529                                                           | 1        | 0.42%   |
| MSI MS-7255                                                           | 1        | 0.42%   |
| MSI MS-7235                                                           | 1        | 0.42%   |
| Lenovo ThinkPad X240 20ALA0AHRT                                       | 1        | 0.42%   |
| Lenovo ThinkCentre M73z 10BB001DRU                                    | 1        | 0.42%   |
| Lenovo ThinkCentre M72e m72e                                          | 1        | 0.42%   |
| Lenovo ThinkCentre M600 10GB000TRU                                    | 1        | 0.42%   |
| Lenovo ThinkCentre A55 898562G                                        | 1        | 0.42%   |
| Kraftway GEG                                                          | 1        | 0.42%   |
| Kontron KT965/ATXP                                                    | 1        | 0.42%   |
| KOHJINSHA SH series                                                   | 1        | 0.42%   |
| khadas edge-v                                                         | 1        | 0.42%   |
| Intel X79 V2.72A                                                      | 1        | 0.42%   |
| Intel X64                                                             | 1        | 0.42%   |
| Intel S3000AH                                                         | 1        | 0.42%   |
| Intel J1900                                                           | 1        | 0.42%   |
| Intel DN2820FYK H24582-203                                            | 1        | 0.42%   |
| Intel DN2800MT AAG23738-600                                           | 1        | 0.42%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown                      | 19       | 8.05%   |
| ASUS PRIME                   | 7        | 2.97%   |
| ASUS All                     | 7        | 2.97%   |
| Lenovo ThinkCentre           | 4        | 1.69%   |
| HP ProLiant                  | 4        | 1.69%   |
| PC Engines APU2              | 3        | 1.27%   |
| HP Compaq                    | 3        | 1.27%   |
| Dell OptiPlex                | 3        | 1.27%   |
| ASUS ROG                     | 3        | 1.27%   |
| ASUS P5Q                     | 3        | 1.27%   |
| ASRock X570                  | 3        | 1.27%   |
| Acer Aspire                  | 3        | 1.27%   |
| Supermicro SSG-6029P-E1CR12L | 2        | 0.85%   |
| Pegatron SAISHIAT2           | 2        | 0.85%   |
| MSI MS-7817                  | 2        | 0.85%   |
| Huanan X79                   | 2        | 0.85%   |
| Gigabyte M68MT-S2P           | 2        | 0.85%   |
| Gigabyte H310M               | 2        | 0.85%   |
| Gigabyte GA-IMB370TN         | 2        | 0.85%   |
| Gigabyte C1037UN-EU          | 2        | 0.85%   |
| Gigabyte B450                | 2        | 0.85%   |
| Gigabyte 970A-DS3P           | 2        | 0.85%   |
| ASUS TUF                     | 2        | 0.85%   |
| ASUS P8Z77-V                 | 2        | 0.85%   |
| ASUS P7H55-M                 | 2        | 0.85%   |
| ASUS P6T                     | 2        | 0.85%   |
| ASUS P5B                     | 2        | 0.85%   |
| ASUS P4P800-VM               | 2        | 0.85%   |
| ASRock J4205-ITX             | 2        | 0.85%   |
| Acer Revo                    | 2        | 0.85%   |
| Techvision TVI7309X          | 1        | 0.42%   |
| Supermicro SYS-6028R-TRT     | 1        | 0.42%   |
| Supermicro SYS-5019A-FTN4    | 1        | 0.42%   |
| Supermicro SSG-6028R-E1CR12T | 1        | 0.42%   |
| Supermicro NSM5200-06-EU     | 1        | 0.42%   |
| Sony VPCL22Z1R               | 1        | 0.42%   |
| Shuttle DS20U                | 1        | 0.42%   |
| Radxa rock-pi-4              | 1        | 0.42%   |
| Pegatron SKLD4-P1            | 1        | 0.42%   |
| Pegatron SAISHIAT            | 1        | 0.42%   |
| Pegatron Pro                 | 1        | 0.42%   |
| Pegatron IPPPV-D3G           | 1        | 0.42%   |
| Pegatron Compaq              | 1        | 0.42%   |
| MW GMLK-2                    | 1        | 0.42%   |
| MSI MS-9A25                  | 1        | 0.42%   |
| MSI MS-7C96                  | 1        | 0.42%   |
| MSI MS-7B93                  | 1        | 0.42%   |
| MSI MS-7B89                  | 1        | 0.42%   |
| MSI MS-7A38                  | 1        | 0.42%   |
| MSI MS-7A15                  | 1        | 0.42%   |
| MSI MS-7922                  | 1        | 0.42%   |
| MSI MS-7816                  | 1        | 0.42%   |
| MSI MS-7788                  | 1        | 0.42%   |
| MSI MS-7529                  | 1        | 0.42%   |
| MSI MS-7255                  | 1        | 0.42%   |
| MSI MS-7235                  | 1        | 0.42%   |
| Lenovo ThinkPad              | 1        | 0.42%   |
| Kraftway GEG                 | 1        | 0.42%   |
| Kontron KT965                | 1        | 0.42%   |
| KOHJINSHA SH                 | 1        | 0.42%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2019    | 25       | 10.59%  |
| 2018    | 24       | 10.17%  |
| 2013    | 17       | 7.2%    |
| 2011    | 16       | 6.78%   |
| 2021    | 15       | 6.36%   |
| 2020    | 15       | 6.36%   |
| 2014    | 15       | 6.36%   |
| 2009    | 15       | 6.36%   |
| 2012    | 14       | 5.93%   |
| 2010    | 13       | 5.51%   |
| Unknown | 12       | 5.08%   |
| 2017    | 9        | 3.81%   |
| 2016    | 9        | 3.81%   |
| 2008    | 9        | 3.81%   |
| 2007    | 9        | 3.81%   |
| 2015    | 6        | 2.54%   |
| 2005    | 5        | 2.12%   |
| 2006    | 4        | 1.69%   |
| 2022    | 2        | 0.85%   |
| 2004    | 2        | 0.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 236      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 233      | 98.73%  |
| Yes  | 3        | 1.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 57       | 23.95%  |
| 8.01-16.0   | 52       | 21.85%  |
| 16.01-24.0  | 46       | 19.33%  |
| 2.01-3.0    | 24       | 10.08%  |
| 32.01-64.0  | 23       | 9.66%   |
| 3.01-4.0    | 11       | 4.62%   |
| 64.01-256.0 | 8        | 3.36%   |
| 0.51-1.0    | 8        | 3.36%   |
| 24.01-32.0  | 3        | 1.26%   |
| 1.01-2.0    | 3        | 1.26%   |
| 0.01-0.5    | 3        | 1.26%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 126      | 51.43%  |
| 0.51-1.0   | 55       | 22.45%  |
| 1.01-2.0   | 24       | 9.8%    |
| 3.01-4.0   | 9        | 3.67%   |
| 8.01-16.0  | 7        | 2.86%   |
| Unknown    | 7        | 2.86%   |
| 4.01-8.0   | 5        | 2.04%   |
| 0          | 4        | 1.63%   |
| 2.01-3.0   | 3        | 1.22%   |
| 16.01-24.0 | 3        | 1.22%   |
| 24.01-32.0 | 2        | 0.82%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 102      | 41.3%   |
| 2      | 60       | 24.29%  |
| 3      | 27       | 10.93%  |
| 4      | 23       | 9.31%   |
| 0      | 15       | 6.07%   |
| 5      | 9        | 3.64%   |
| 6      | 5        | 2.02%   |
| 7      | 4        | 1.62%   |
| 9      | 1        | 0.4%    |
| 8      | 1        | 0.4%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 197      | 81.74%  |
| Yes       | 44       | 18.26%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 219      | 92.8%   |
| No        | 17       | 7.2%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 188      | 79.32%  |
| Yes       | 49       | 20.68%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 211      | 89.41%  |
| Yes       | 25       | 10.59%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Russia  | 236      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                       | Desktops | Percent |
|----------------------------|----------|---------|
| Moscow                     | 78       | 31.71%  |
| St Petersburg              | 19       | 7.72%   |
| Yekaterinburg              | 10       | 4.07%   |
| Krasnodar                  | 9        | 3.66%   |
| Novosibirsk                | 8        | 3.25%   |
| Barnaul                    | 7        | 2.85%   |
| Vladivostok                | 6        | 2.44%   |
| Ozersk                     | 6        | 2.44%   |
| Chelyabinsk                | 6        | 2.44%   |
| Surgut                     | 5        | 2.03%   |
| Omsk                       | 4        | 1.63%   |
| Kamensk-Ural'skiy          | 4        | 1.63%   |
| Voronezh                   | 3        | 1.22%   |
| Ufa                        | 3        | 1.22%   |
| Podolsk                    | 3        | 1.22%   |
| Lipetsk                    | 3        | 1.22%   |
| Krasnoyarsk                | 3        | 1.22%   |
| Khimki                     | 3        | 1.22%   |
| Irkutsk                    | 3        | 1.22%   |
| Volzhskiy                  | 2        | 0.81%   |
| Volgograd                  | 2        | 0.81%   |
| Ulyanovsk                  | 2        | 0.81%   |
| Tambov                     | 2        | 0.81%   |
| Saratov                    | 2        | 0.81%   |
| Perm                       | 2        | 0.81%   |
| Orsk                       | 2        | 0.81%   |
| Obninsk                    | 2        | 0.81%   |
| Nizhniy Novgorod           | 2        | 0.81%   |
| Izhevsk                    | 2        | 0.81%   |
| Armavir                    | 2        | 0.81%   |
| Zhukovskiy                 | 1        | 0.41%   |
| Yegor'yevsk                | 1        | 0.41%   |
| Vostochnoe Degunino        | 1        | 0.41%   |
| Voskresensk                | 1        | 0.41%   |
| Vladimir                   | 1        | 0.41%   |
| Vidnoye                    | 1        | 0.41%   |
| Ust'-Charyshskaya Pristan' | 1        | 0.41%   |
| Ulan-Ude                   | 1        | 0.41%   |
| Tomsk                      | 1        | 0.41%   |
| Taganrog                   | 1        | 0.41%   |
| Stavropol                  | 1        | 0.41%   |
| Smolenshchina              | 1        | 0.41%   |
| Sevastopol                 | 1        | 0.41%   |
| Sertolovo                  | 1        | 0.41%   |
| Ryazan                     | 1        | 0.41%   |
| Rubtsovsk                  | 1        | 0.41%   |
| Rostov-on-Don              | 1        | 0.41%   |
| Reutov                     | 1        | 0.41%   |
| Petergof                   | 1        | 0.41%   |
| Penza                      | 1        | 0.41%   |
| Orenburg                   | 1        | 0.41%   |
| Myski                      | 1        | 0.41%   |
| Murmansk                   | 1        | 0.41%   |
| Murino                     | 1        | 0.41%   |
| Moscow Oblast              | 1        | 0.41%   |
| Lyubertsy                  | 1        | 0.41%   |
| Lesosibirsk                | 1        | 0.41%   |
| Kostroma                   | 1        | 0.41%   |
| Kommunar                   | 1        | 0.41%   |
| Kolomna                    | 1        | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor                             | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC                                | 75       | 137    | 21.25%  |
| Seagate                            | 72       | 153    | 20.4%   |
| Samsung Electronics                | 36       | 52     | 10.2%   |
| Toshiba                            | 23       | 44     | 6.52%   |
| Kingston                           | 21       | 23     | 5.95%   |
| Hitachi                            | 17       | 46     | 4.82%   |
| Intel                              | 12       | 17     | 3.4%    |
| Crucial                            | 12       | 14     | 3.4%    |
| A-DATA Technology                  | 7        | 11     | 1.98%   |
| Smartbuy                           | 5        | 5      | 1.42%   |
| Plextor                            | 5        | 8      | 1.42%   |
| OCZ                                | 5        | 5      | 1.42%   |
| HGST                               | 5        | 13     | 1.42%   |
| SPCC                               | 4        | 4      | 1.13%   |
| SanDisk                            | 4        | 5      | 1.13%   |
| OPENBSD                            | 4        | 8      | 1.13%   |
| AMD                                | 4        | 5      | 1.13%   |
| Silicon Motion                     | 3        | 3      | 0.85%   |
| Maxtor                             | 3        | 3      | 0.85%   |
| KingSpec                           | 3        | 5      | 0.85%   |
| Apacer                             | 3        | 3      | 0.85%   |
| XPG                                | 2        | 2      | 0.57%   |
| Verbatim                           | 2        | 2      | 0.57%   |
| Patriot                            | 2        | 2      | 0.57%   |
| Micron Technology                  | 2        | 4      | 0.57%   |
| Kston                              | 2        | 2      | 0.57%   |
| Hoodisk                            | 2        | 4      | 0.57%   |
| Fujitsu                            | 2        | 3      | 0.57%   |
| XUNZHE                             | 1        | 1      | 0.28%   |
| Transcend                          | 1        | 1      | 0.28%   |
| Qumo                               | 1        | 1      | 0.28%   |
| Product:              USB DISK 2.0 | 1        | 1      | 0.28%   |
| NVMe                               | 1        | 4      | 0.28%   |
| Netac                              | 1        | 1      | 0.28%   |
| MaxDigital                         | 1        | 1      | 0.28%   |
| LITEON                             | 1        | 1      | 0.28%   |
| KingDian                           | 1        | 3      | 0.28%   |
| IBM                                | 1        | 1      | 0.28%   |
| Hewlett-Packard                    | 1        | 4      | 0.28%   |
| Goodram                            | 1        | 1      | 0.28%   |
| GK                                 | 1        | 1      | 0.28%   |
| Gigabyte Technology                | 1        | 1      | 0.28%   |
| China                              | 1        | 1      | 0.28%   |
| AEGO                               | 1        | 1      | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB             | 6        | 1.45%   |
| WDC WDS240G2G0A-00JH30 240GB       | 5        | 1.21%   |
| Kingston SA400S37240G 240GB        | 5        | 1.21%   |
| Seagate ST3300657SS 304GB          | 4        | 0.97%   |
| Seagate ST250DM000-1BD141 250GB    | 4        | 0.97%   |
| Seagate ST1000DM010-2EP102 1TB     | 4        | 0.97%   |
| Samsung SSD 970 EVO Plus 250GB     | 4        | 0.97%   |
| OPENBSD SR RAID 1 752GB            | 4        | 0.97%   |
| WDC WD6400AARS-00Y5B1 640GB        | 3        | 0.72%   |
| WDC WD20EARX-00PASB0 2TB           | 3        | 0.72%   |
| WDC WD1002FAEX-00Y9A0 1TB          | 3        | 0.72%   |
| Toshiba DT01ACA050 500GB           | 3        | 0.72%   |
| Seagate ST500DM002-1BD142 500GB    | 3        | 0.72%   |
| Seagate ST380815AS 80GB            | 3        | 0.72%   |
| Seagate ST3500413AS 500GB          | 3        | 0.72%   |
| Seagate ST3250318AS 250GB          | 3        | 0.72%   |
| Seagate ST2000DM001-1CH164 2TB     | 3        | 0.72%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3        | 0.72%   |
| Samsung SSD 860 EVO 500GB          | 3        | 0.72%   |
| Samsung HD161HJ 160GB              | 3        | 0.72%   |
| A-DATA SU650 120GB                 | 3        | 0.72%   |
| WDC WDS500G1B0A-00H9H0 500GB       | 2        | 0.48%   |
| WDC WD5003AZEX-00K1GA0 500GB       | 2        | 0.48%   |
| WDC WD5000LPLX-00ZNTT0 500GB       | 2        | 0.48%   |
| WDC WD5000AZLX-00K2TA0 500GB       | 2        | 0.48%   |
| WDC WD40EFRX-68N32N0 4TB           | 2        | 0.48%   |
| WDC WD20EZRZ-00Z5HB0 2TB           | 2        | 0.48%   |
| WDC WD2000JS-55MHB0 192GB          | 2        | 0.48%   |
| WDC WD15EADS-00P8B0 1.5TB          | 2        | 0.48%   |
| WDC WD10EZRX-00A8LB0 1TB           | 2        | 0.48%   |
| WDC WD10EZEX-21M2NA0 1TB           | 2        | 0.48%   |
| WDC WD10EZEX-08WN4A0 1TB           | 2        | 0.48%   |
| WDC WD10EALX-009BA0 1TB            | 2        | 0.48%   |
| WDC WD1002FAEX-00Z3A0 1TB          | 2        | 0.48%   |
| Verbatim Vi550 S3 SSD 512GB        | 2        | 0.48%   |
| Toshiba MG04ACA600E 6TB            | 2        | 0.48%   |
| Toshiba HDWD130 3TB                | 2        | 0.48%   |
| Smartbuy SSD 60GB                  | 2        | 0.48%   |
| Silicon Motion NE-256 256GB        | 2        | 0.48%   |
| Seagate ST4000VN008-2DR166 4TB     | 2        | 0.48%   |
| Seagate ST380011A 80GB             | 2        | 0.48%   |
| Seagate ST3320418AS 320GB          | 2        | 0.48%   |
| Seagate ST3250410AS 250GB          | 2        | 0.48%   |
| Seagate ST3160813AS 160GB          | 2        | 0.48%   |
| Seagate ST31000524AS 1TB           | 2        | 0.48%   |
| Seagate ST2000DM008-2FR102 2TB     | 2        | 0.48%   |
| Seagate ST1000VX000-1CU162 1TB     | 2        | 0.48%   |
| Samsung SSD 970 EVO 1TB            | 2        | 0.48%   |
| Samsung SSD 870 EVO 1TB            | 2        | 0.48%   |
| Samsung SSD 840 PRO Series 256GB   | 2        | 0.48%   |
| OCZ VERTEX3 64GB                   | 2        | 0.48%   |
| Micron 5100_MTFDDAK240TCB 240GB    | 2        | 0.48%   |
| Maxtor STM3320613AS 320GB          | 2        | 0.48%   |
| Kston SSD 128GB                    | 2        | 0.48%   |
| Kingston SA400S37120G 120GB        | 2        | 0.48%   |
| Kingston SA2000M8500G 500GB        | 2        | 0.48%   |
| Kingston DataTraveler 3.0 32GB     | 2        | 0.48%   |
| KingSpec NT-512 512GB              | 2        | 0.48%   |
| Intel SSDSC2BB080G4 80GB           | 2        | 0.48%   |
| Intel SSDPEKNW020T8 2TB            | 2        | 0.48%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                             | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| Seagate                            | 72       | 153    | 35.29%  |
| WDC                                | 65       | 122    | 31.86%  |
| Toshiba                            | 22       | 43     | 10.78%  |
| Hitachi                            | 17       | 46     | 8.33%   |
| Samsung Electronics                | 9        | 12     | 4.41%   |
| HGST                               | 5        | 13     | 2.45%   |
| OPENBSD                            | 4        | 8      | 1.96%   |
| Maxtor                             | 3        | 3      | 1.47%   |
| Fujitsu                            | 2        | 3      | 0.98%   |
| Product:              USB DISK 2.0 | 1        | 1      | 0.49%   |
| NVMe                               | 1        | 4      | 0.49%   |
| MaxDigital                         | 1        | 1      | 0.49%   |
| IBM                                | 1        | 1      | 0.49%   |
| Hewlett-Packard                    | 1        | 4      | 0.49%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 18       | 23     | 14.06%  |
| Kingston            | 18       | 20     | 14.06%  |
| Crucial             | 11       | 13     | 8.59%   |
| WDC                 | 10       | 10     | 7.81%   |
| Intel               | 9        | 12     | 7.03%   |
| A-DATA Technology   | 7        | 10     | 5.47%   |
| Smartbuy            | 5        | 5      | 3.91%   |
| Plextor             | 5        | 8      | 3.91%   |
| OCZ                 | 5        | 5      | 3.91%   |
| SanDisk             | 4        | 5      | 3.13%   |
| AMD                 | 4        | 5      | 3.13%   |
| SPCC                | 3        | 3      | 2.34%   |
| KingSpec            | 3        | 5      | 2.34%   |
| Apacer              | 3        | 3      | 2.34%   |
| Verbatim            | 2        | 2      | 1.56%   |
| Patriot             | 2        | 2      | 1.56%   |
| Micron Technology   | 2        | 4      | 1.56%   |
| Kston               | 2        | 2      | 1.56%   |
| Hoodisk             | 2        | 4      | 1.56%   |
| XUNZHE              | 1        | 1      | 0.78%   |
| XPG                 | 1        | 1      | 0.78%   |
| Transcend           | 1        | 1      | 0.78%   |
| Toshiba             | 1        | 1      | 0.78%   |
| Qumo                | 1        | 1      | 0.78%   |
| Netac               | 1        | 1      | 0.78%   |
| LITEON              | 1        | 1      | 0.78%   |
| KingDian            | 1        | 3      | 0.78%   |
| Goodram             | 1        | 1      | 0.78%   |
| GK                  | 1        | 1      | 0.78%   |
| Gigabyte Technology | 1        | 1      | 0.78%   |
| China               | 1        | 1      | 0.78%   |
| AEGO                | 1        | 1      | 0.78%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 153      | 414    | 52.76%  |
| SSD  | 112      | 156    | 38.62%  |
| NVMe | 25       | 37     | 8.62%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 216      | 570    | 89.63%  |
| NVMe | 25       | 37     | 10.37%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 184      | 299    | 61.33%  |
| 0.51-1.0   | 66       | 118    | 22%     |
| 1.01-2.0   | 23       | 88     | 7.67%   |
| 3.01-4.0   | 12       | 25     | 4%      |
| 4.01-10.0  | 9        | 22     | 3%      |
| 2.01-3.0   | 6        | 18     | 2%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 68       | 27.53%  |
| 1-20           | 52       | 21.05%  |
| 251-500        | 39       | 15.79%  |
| 51-100         | 33       | 13.36%  |
| 21-50          | 18       | 7.29%   |
| 501-1000       | 16       | 6.48%   |
| More than 3000 | 8        | 3.24%   |
| 1001-2000      | 8        | 3.24%   |
| Unknown        | 3        | 1.21%   |
| 2001-3000      | 2        | 0.81%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 188      | 77.37%  |
| 21-50          | 23       | 9.47%   |
| 101-250        | 8        | 3.29%   |
| 51-100         | 7        | 2.88%   |
| 501-1000       | 5        | 2.06%   |
| More than 3000 | 3        | 1.23%   |
| 2001-3000      | 3        | 1.23%   |
| 1001-2000      | 3        | 1.23%   |
| Unknown        | 3        | 1.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Desktops | Drives | Percent |
|----------------------------------------------|----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB                 | 2        | 2      | 2.94%   |
| WDC WD1002FAEX-00Y9A0 1TB                    | 2        | 2      | 2.94%   |
| Seagate ST3500413AS 500GB                    | 2        | 4      | 2.94%   |
| Seagate ST3320418AS 320GB                    | 2        | 2      | 2.94%   |
| Samsung Electronics SSD 870 EVO 1TB          | 2        | 6      | 2.94%   |
| Samsung Electronics HD161HJ 160GB            | 2        | 2      | 2.94%   |
| Maxtor STM3320613AS 320GB                    | 2        | 2      | 2.94%   |
| Hitachi HDS721010CLA332 1TB                  | 2        | 4      | 2.94%   |
| XPG SX950U 240GB                             | 1        | 1      | 1.47%   |
| WDC WD7501AALS-00E8B0 752GB                  | 1        | 1      | 1.47%   |
| WDC WD60EFRX-68MYMN1 6TB                     | 1        | 1      | 1.47%   |
| WDC WD5003AZEX-00MK2A0 500GB                 | 1        | 1      | 1.47%   |
| WDC WD5000LPLX-00ZNTT0 500GB                 | 1        | 1      | 1.47%   |
| WDC WD5000AZRZ-00HTKB0 500GB                 | 1        | 1      | 1.47%   |
| WDC WD5000AZLX-00CL5A0 500GB                 | 1        | 1      | 1.47%   |
| WDC WD5000AAKX-00ERMA0 500GB                 | 1        | 1      | 1.47%   |
| WDC WD5000AAKS-00V1A0 500GB                  | 1        | 1      | 1.47%   |
| WDC WD40EFRX-68N32N0 4TB                     | 1        | 3      | 1.47%   |
| WDC WD3200BPVT-22JJ5T0 320GB                 | 1        | 1      | 1.47%   |
| WDC WD3200BEVT-00A0RT0 233GB                 | 1        | 1      | 1.47%   |
| WDC WD20EURX-63T0FY0 2TB                     | 1        | 1      | 1.47%   |
| WDC WD20EFRX-68EUZN0 2TB                     | 1        | 2      | 1.47%   |
| WDC WD1600BEVT-22ZCT0 160GB                  | 1        | 1      | 1.47%   |
| WDC WD15EADS-00P8B0 1.5TB                    | 1        | 1      | 1.47%   |
| WDC WD1002FAEX-00Z3A0 1TB                    | 1        | 1      | 1.47%   |
| Toshiba MK2002TSKB 2TB                       | 1        | 1      | 1.47%   |
| Toshiba HDWD105 500GB                        | 1        | 2      | 1.47%   |
| Toshiba DT01ACA050 500GB                     | 1        | 2      | 1.47%   |
| Seagate ST9120822AS 120GB                    | 1        | 1      | 1.47%   |
| Seagate ST500DM002-1BD142 500GB              | 1        | 1      | 1.47%   |
| Seagate ST3750640NS 752GB                    | 1        | 4      | 1.47%   |
| Seagate ST3500514NS 500GB                    | 1        | 1      | 1.47%   |
| Seagate ST3250410AS 250GB                    | 1        | 1      | 1.47%   |
| Seagate ST3250310AS 250GB                    | 1        | 1      | 1.47%   |
| Seagate ST320410A 20GB                       | 1        | 1      | 1.47%   |
| Seagate ST3160812A 160GB                     | 1        | 2      | 1.47%   |
| Seagate ST3120814A 120GB                     | 1        | 1      | 1.47%   |
| Seagate ST3120211AS 120GB                    | 1        | 1      | 1.47%   |
| Seagate ST250DM000-1BD141 250GB              | 1        | 2      | 1.47%   |
| Seagate ST2000DM006-2DM164 2TB               | 1        | 1      | 1.47%   |
| Seagate ST2000DM001-1CH164 2TB               | 1        | 1      | 1.47%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1        | 1      | 1.47%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1        | 1      | 1.47%   |
| Samsung Electronics SP2004C 200GB            | 1        | 1      | 1.47%   |
| Samsung Electronics HD501LJ 500GB            | 1        | 2      | 1.47%   |
| Samsung Electronics HD082GJ 80GB             | 1        | 1      | 1.47%   |
| Plextor PX-128M5S 128GB                      | 1        | 1      | 1.47%   |
| Maxtor STM3160815AS 160GB                    | 1        | 1      | 1.47%   |
| Kingston SNV425S2128GB                       | 1        | 1      | 1.47%   |
| Kingston SMS200S3120G 120GB                  | 1        | 1      | 1.47%   |
| Kingston SA400S37120G 120GB                  | 1        | 1      | 1.47%   |
| Intel SSDSC2BW480A4 480GB                    | 1        | 1      | 1.47%   |
| Intel SSDSC2BB080G4 80GB                     | 1        | 1      | 1.47%   |
| Intel SSDSA2M080G2GC 80GB                    | 1        | 1      | 1.47%   |
| Hitachi HTS547550A9E384 500GB                | 1        | 1      | 1.47%   |
| Hitachi HTS543232A7A384 320GB                | 1        | 1      | 1.47%   |
| Hitachi HDS721010CLA630 1TB                  | 1        | 1      | 1.47%   |
| GK SM2244LTAB ,TC58TEG6DDKTA00 8GB           | 1        | 1      | 1.47%   |
| AMD R5SL240G 240GB                           | 1        | 2      | 1.47%   |
| A-DATA Technology XM13 32GB                  | 1        | 1      | 1.47%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 18       | 23     | 27.27%  |
| Seagate             | 18       | 25     | 27.27%  |
| Samsung Electronics | 8        | 13     | 12.12%  |
| Hitachi             | 5        | 7      | 7.58%   |
| Toshiba             | 3        | 5      | 4.55%   |
| Maxtor              | 3        | 3      | 4.55%   |
| Kingston            | 3        | 3      | 4.55%   |
| Intel               | 3        | 3      | 4.55%   |
| XPG                 | 1        | 1      | 1.52%   |
| Plextor             | 1        | 1      | 1.52%   |
| GK                  | 1        | 1      | 1.52%   |
| AMD                 | 1        | 2      | 1.52%   |
| A-DATA Technology   | 1        | 1      | 1.52%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 18       | 25     | 36%     |
| WDC                 | 16       | 21     | 32%     |
| Samsung Electronics | 5        | 6      | 10%     |
| Hitachi             | 5        | 7      | 10%     |
| Toshiba             | 3        | 5      | 6%      |
| Maxtor              | 3        | 3      | 6%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 49       | 67     | 76.56%  |
| SSD  | 15       | 21     | 23.44%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                        | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| WDC WD6400AARS-00Y5B1 640GB  | 1        | 2      | 50%     |
| Crucial M4-CT256M4SSD1 256GB | 1        | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 2      | 50%     |
| Crucial | 1        | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 189      | 479    | 70%     |
| Malfunc  | 62       | 88     | 22.96%  |
| Detected | 17       | 37     | 6.3%    |
| Failed   | 2        | 3      | 0.74%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 164      | 54.49%  |
| AMD                              | 47       | 15.61%  |
| Samsung Electronics              | 14       | 4.65%   |
| Marvell Technology Group         | 12       | 3.99%   |
| ASMedia Technology               | 10       | 3.32%   |
| Nvidia                           | 9        | 2.99%   |
| JMicron Technology               | 9        | 2.99%   |
| Silicon Motion                   | 6        | 1.99%   |
| Broadcom / LSI                   | 5        | 1.66%   |
| Areca Technology                 | 4        | 1.33%   |
| SanDisk                          | 3        | 1%      |
| Kingston Technology Company      | 3        | 1%      |
| Toshiba                          | 2        | 0.66%   |
| Silicon Image                    | 2        | 0.66%   |
| ADATA Technology                 | 2        | 0.66%   |
| VIA Technologies                 | 1        | 0.33%   |
| Silicon Integrated Systems [SiS] | 1        | 0.33%   |
| Realtek Semiconductor            | 1        | 0.33%   |
| Phison Electronics               | 1        | 0.33%   |
| Micron/Crucial Technology        | 1        | 0.33%   |
| Lite-On Technology               | 1        | 0.33%   |
| Lite-On IT Corp. / Plextor       | 1        | 0.33%   |
| Integrated Technology Express    | 1        | 0.33%   |
| 3ware                            | 1        | 0.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 28       | 7.61%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 14       | 3.8%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 13       | 3.53%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 13       | 3.53%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 12       | 3.26%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 11       | 2.99%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 11       | 2.99%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 11       | 2.99%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 10       | 2.72%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 9        | 2.45%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 9        | 2.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 8        | 2.17%   |
| AMD 400 Series Chipset SATA Controller                                                  | 8        | 2.17%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 7        | 1.9%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 7        | 1.9%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 6        | 1.63%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 6        | 1.63%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 6        | 1.63%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 6        | 1.63%   |
| Nvidia MCP61 SATA Controller                                                            | 5        | 1.36%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 5        | 1.36%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4        | 1.09%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 4        | 1.09%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 4        | 1.09%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 4        | 1.09%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 4        | 1.09%   |
| Intel 82801EB (ICH5) SATA Controller                                                    | 4        | 1.09%   |
| Areca ARC-1300ix-16 16-Port PCI-Express to SAS Non-RAID Host Adapter                    | 4        | 1.09%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 3        | 0.82%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3        | 0.82%   |
| Nvidia MCP61 IDE                                                                        | 3        | 0.82%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 3        | 0.82%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 3        | 0.82%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 3        | 0.82%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3        | 0.82%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 3        | 0.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 3        | 0.82%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 0.82%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 3        | 0.82%   |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                            | 3        | 0.82%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 0.82%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 0.82%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3        | 0.82%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                        | 2        | 0.54%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 0.54%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 2        | 0.54%   |
| Marvell Group 88SE9120 SATA 6Gb/s Controller                                            | 2        | 0.54%   |
| Kingston Company A2000 NVMe SSD                                                         | 2        | 0.54%   |
| JMicron JMB361 AHCI/IDE                                                                 | 2        | 0.54%   |
| Intel SSD 660P Series                                                                   | 2        | 0.54%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2        | 0.54%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                           | 2        | 0.54%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                            | 2        | 0.54%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2        | 0.54%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 2        | 0.54%   |
| Intel 82801FR/FRW (ICH6R/ICH6RW) SATA Controller                                        | 2        | 0.54%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                                | 2        | 0.54%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 0.54%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 0.54%   |
| Broadcom / LSI SAS3008 PCI-Express Fusion-MPT SAS-3                                     | 2        | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 174      | 60%     |
| IDE  | 66       | 22.76%  |
| NVMe | 37       | 12.76%  |
| RAID | 6        | 2.07%   |
| SCSI | 4        | 1.38%   |
| SAS  | 3        | 1.03%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 168      | 70.59%  |
| AMD     | 55       | 23.11%  |
| ARM     | 10       | 4.2%    |
| Unknown | 4        | 1.68%   |
| PowerPC | 1        | 0.42%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 5        | 2.07%   |
| ARM Cortex-A57 r1p3                         | 4        | 1.66%   |
|                                             | 4        | 1.66%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 3        | 1.24%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3        | 1.24%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 1.24%   |
| Intel Celeron CPU J3455 @ 1.50GHz           | 3        | 1.24%   |
| Intel Celeron CPU 1037U @ 1.80GHz           | 3        | 1.24%   |
| ARM Cortex-A72 r0p2                         | 3        | 1.24%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 3        | 1.24%   |
| AMD GX-412TC SOC                            | 3        | 1.24%   |
| Intel Xeon CPU E3-1265L V2 @ 2.50GHz        | 2        | 0.83%   |
| Intel Xeon Bronze 3104 CPU @ 1.70GHz        | 2        | 0.83%   |
| Intel Pentium Gold G5400T CPU @ 3.10GHz     | 2        | 0.83%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 2        | 0.83%   |
| Intel Pentium CPU J4205 @ 1.50GHz           | 2        | 0.83%   |
| Intel Pentium 4 CPU                         | 2        | 0.83%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2        | 0.83%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 0.83%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 2        | 0.83%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 2        | 0.83%   |
| Intel Core i7 CPU                           | 2        | 0.83%   |
| Intel Core i5-8350U CPU @ 1.70GHz           | 2        | 0.83%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 2        | 0.83%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 2        | 0.83%   |
| Intel Core i3-4170 CPU @ 3.70GHz            | 2        | 0.83%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2        | 0.83%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 2        | 0.83%   |
| Intel Core 2 Quad CPU                       | 2        | 0.83%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 2        | 0.83%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz        | 2        | 0.83%   |
| Intel Core 2 Duo CPU E7200 @ 2.53GHz        | 2        | 0.83%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 2        | 0.83%   |
| Intel Celeron CPU J3060 @ 1.60GHz           | 2        | 0.83%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 2        | 0.83%   |
| Intel Celeron CPU J1800 @ 2.41GHz           | 2        | 0.83%   |
| Intel Atom CPU D525 @ 1.80GHz               | 2        | 0.83%   |
| Intel 686-class                             | 2        | 0.83%   |
| Intel 11th Gen Core i5-11600K @ 3.90GHz     | 2        | 0.83%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 2        | 0.83%   |
| AMD Ryzen 7 3800XT 8-Core Processor         | 2        | 0.83%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 2        | 0.83%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2        | 0.83%   |
| AMD FX-6300 Six-Core Processor              | 2        | 0.83%   |
| AMD Athlon II X3 455 Processor              | 2        | 0.83%   |
| PowerPC 7447A (Revision 0x101)              | 1        | 0.41%   |
| Intel Xeon CPU X5460 @ 3.16GHz              | 1        | 0.41%   |
| Intel Xeon CPU X3470 @ 2.93GHz              | 1        | 0.41%   |
| Intel Xeon CPU X3440 @ 2.53GHz              | 1        | 0.41%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 1        | 0.41%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz         | 1        | 0.41%   |
| Intel Xeon CPU E5-2660 v4 @ 2.00GHz         | 1        | 0.41%   |
| Intel Xeon CPU E5-2650 v4 @ 2.20GHz         | 1        | 0.41%   |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz          | 1        | 0.41%   |
| Intel Xeon CPU E5-2630L 0 @ 2.00GHz         | 1        | 0.41%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz         | 1        | 0.41%   |
| Intel Xeon CPU E5-2407 0 @ 2.20GHz          | 1        | 0.41%   |
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz         | 1        | 0.41%   |
| Intel Xeon CPU E3-1270 v3 @ 3.50GHz         | 1        | 0.41%   |
| Intel Xeon CPU E3-1240 V2 @ 3.40GHz         | 1        | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Celeron           | 27       | 11.3%   |
| Intel Core i5           | 25       | 10.46%  |
| Intel Core i7           | 19       | 7.95%   |
| Intel Xeon              | 17       | 7.11%   |
| Intel Core i3           | 14       | 5.86%   |
| AMD Ryzen 5             | 12       | 5.02%   |
| Intel Core 2 Quad       | 10       | 4.18%   |
| ARM Cortex              | 10       | 4.18%   |
| Intel Core 2 Duo        | 9        | 3.77%   |
| Intel Atom              | 8        | 3.35%   |
| Other                   | 7        | 2.93%   |
| Intel Pentium 4         | 7        | 2.93%   |
| Intel Pentium           | 6        | 2.51%   |
| AMD Ryzen 7             | 6        | 2.51%   |
| Intel Pentium Gold      | 4        | 1.67%   |
| AMD FX                  | 4        | 1.67%   |
| Intel Pentium Dual-Core | 3        | 1.26%   |
| Intel Pentium Dual      | 3        | 1.26%   |
| Intel Pentium D         | 3        | 1.26%   |
| Intel Core 2            | 3        | 1.26%   |
| AMD GX                  | 3        | 1.26%   |
| AMD Athlon 64 X2        | 3        | 1.26%   |
| Intel Xeon Bronze       | 2        | 0.84%   |
| Intel Core i9           | 2        | 0.84%   |
| Intel 686-class         | 2        | 0.84%   |
| AMD Turion II Neo       | 2        | 0.84%   |
| AMD Ryzen 9             | 2        | 0.84%   |
| AMD Phenom II X6        | 2        | 0.84%   |
| AMD Phenom              | 2        | 0.84%   |
| AMD E                   | 2        | 0.84%   |
| AMD Athlon X4           | 2        | 0.84%   |
| AMD Athlon II X3        | 2        | 0.84%   |
| AMD A10                 | 2        | 0.84%   |
| Intel Pentium Silver    | 1        | 0.42%   |
| Intel Genuine           | 1        | 0.42%   |
| Intel Celeron D         | 1        | 0.42%   |
| AMD Sempron             | 1        | 0.42%   |
| AMD Ryzen 3 PRO         | 1        | 0.42%   |
| AMD Ryzen 3             | 1        | 0.42%   |
| AMD Phenom II X4        | 1        | 0.42%   |
| AMD Phenom II X2        | 1        | 0.42%   |
| AMD E2                  | 1        | 0.42%   |
| AMD C-70                | 1        | 0.42%   |
| AMD Athlon II X4        | 1        | 0.42%   |
| AMD Athlon              | 1        | 0.42%   |
| AMD A4                  | 1        | 0.42%   |
| AMD 686-class           | 1        | 0.42%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 75       | 31.51%  |
| 2       | 59       | 24.79%  |
| Unknown | 40       | 16.81%  |
| 6       | 23       | 9.66%   |
| 1       | 11       | 4.62%   |
| 8       | 9        | 3.78%   |
| 12      | 8        | 3.36%   |
| 16      | 5        | 2.1%    |
| 24      | 3        | 1.26%   |
| 28      | 2        | 0.84%   |
| 3       | 2        | 0.84%   |
| 14      | 1        | 0.42%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 211      | 87.92%  |
| Unknown | 23       | 9.58%   |
| 2       | 6        | 2.5%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 125      | 52.52%  |
| 2       | 64       | 26.89%  |
| Unknown | 49       | 20.59%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| IvyBridge     | 21       | 8.86%   |
| Unknown       | 20       | 8.44%   |
| Penryn        | 19       | 8.02%   |
| KabyLake      | 18       | 7.59%   |
| SandyBridge   | 16       | 6.75%   |
| Haswell       | 16       | 6.75%   |
| Skylake       | 12       | 5.06%   |
| Zen 2         | 11       | 4.64%   |
| NetBurst      | 11       | 4.64%   |
| K10           | 11       | 4.64%   |
| Core          | 11       | 4.64%   |
| Silvermont    | 8        | 3.38%   |
| Goldmont      | 8        | 3.38%   |
| Piledriver    | 7        | 2.95%   |
| Bonnell       | 7        | 2.95%   |
| Zen           | 6        | 2.53%   |
| Zen+          | 5        | 2.11%   |
| Nehalem       | 5        | 2.11%   |
| K8 Hammer     | 4        | 1.69%   |
| Puma          | 3        | 1.27%   |
| Goldmont plus | 3        | 1.27%   |
| CometLake     | 3        | 1.27%   |
| Broadwell     | 3        | 1.27%   |
| Bobcat        | 3        | 1.27%   |
| Zen 3         | 1        | 0.42%   |
| Westmere      | 1        | 0.42%   |
| Steamroller   | 1        | 0.42%   |
| P6            | 1        | 0.42%   |
| Jaguar        | 1        | 0.42%   |
| Bulldozer     | 1        | 0.42%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 97       | 42.73%  |
| Nvidia                     | 71       | 31.28%  |
| AMD                        | 50       | 22.03%  |
| ASPEED Technology          | 6        | 2.64%   |
| Matrox Electronics Systems | 2        | 0.88%   |
| VIA Technologies           | 1        | 0.44%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 9        | 3.83%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 7        | 2.98%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 7        | 2.98%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6        | 2.55%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 6        | 2.55%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 6        | 2.55%   |
| Intel HD Graphics 530                                                                    | 5        | 2.13%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5        | 2.13%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5        | 2.13%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5        | 2.13%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 4        | 1.7%    |
| Intel HD Graphics 500                                                                    | 4        | 1.7%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 4        | 1.7%    |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 4        | 1.7%    |
| Intel 82865G Integrated Graphics Controller                                              | 4        | 1.7%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4        | 1.7%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 3        | 1.28%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 3        | 1.28%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                                      | 3        | 1.28%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 3        | 1.28%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3        | 1.28%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3        | 1.28%   |
| AMD RV710/M92 [Mobility Radeon HD 4350/4550]                                             | 3        | 1.28%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                                           | 3        | 1.28%   |
| AMD ES1000                                                                               | 3        | 1.28%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 2        | 0.85%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 2        | 0.85%   |
| Nvidia NV43 [GeForce 6600]                                                               | 2        | 0.85%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2        | 0.85%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 2        | 0.85%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 2        | 0.85%   |
| Nvidia GA102 [GeForce RTX 3080]                                                          | 2        | 0.85%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 2        | 0.85%   |
| Nvidia G86 [GeForce 8500 GT]                                                             | 2        | 0.85%   |
| Nvidia G73 [GeForce 7600 GS]                                                             | 2        | 0.85%   |
| Intel UHD Graphics 620                                                                   | 2        | 0.85%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2        | 0.85%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2        | 0.85%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2        | 0.85%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 2        | 0.85%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                                         | 2        | 0.85%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 2        | 0.85%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2        | 0.85%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 2        | 0.85%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 2        | 0.85%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1        | 0.43%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1        | 0.43%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 1        | 0.43%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1        | 0.43%   |
| Nvidia NV18 [GeForce4 MX 4000]                                                           | 1        | 0.43%   |
| Nvidia GT218 [ION]                                                                       | 1        | 0.43%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1        | 0.43%   |
| Nvidia GT218 [GeForce 210]                                                               | 1        | 0.43%   |
| Nvidia GT215 [GeForce GT 220]                                                            | 1        | 0.43%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1        | 0.43%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1        | 0.43%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1        | 0.43%   |
| Nvidia GP104 [GeForce GTX 1060 3GB]                                                      | 1        | 0.43%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 1        | 0.43%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1        | 0.43%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 85       | 35.71%  |
| 1 x Nvidia     | 68       | 28.57%  |
| 1 x AMD        | 40       | 16.81%  |
| Other          | 17       | 7.14%   |
| 2 x Intel      | 6        | 2.52%   |
| 2 x AMD        | 6        | 2.52%   |
| 1 x ASPEED     | 6        | 2.52%   |
| Intel + AMD    | 4        | 1.68%   |
| 1 x Matrox     | 2        | 0.84%   |
| Intel + Nvidia | 2        | 0.84%   |
| 1 x VIA        | 1        | 0.42%   |
| AMD + Nvidia   | 1        | 0.42%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 174      | 72.8%   |
| Proprietary | 43       | 17.99%  |
| Unknown     | 22       | 9.21%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 176      | 73.33%  |
| 1.01-2.0   | 17       | 7.08%   |
| 0.51-1.0   | 13       | 5.42%   |
| 3.01-4.0   | 11       | 4.58%   |
| 0.01-0.5   | 8        | 3.33%   |
| 7.01-8.0   | 6        | 2.5%    |
| 5.01-6.0   | 5        | 2.08%   |
| 8.01-16.0  | 3        | 1.25%   |
| 2.01-3.0   | 1        | 0.42%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 25       | 22.73%  |
| Goldstar             | 17       | 15.45%  |
| Dell                 | 12       | 10.91%  |
| Ancor Communications | 9        | 8.18%   |
| ViewSonic            | 8        | 7.27%   |
| Philips              | 7        | 6.36%   |
| Acer                 | 6        | 5.45%   |
| BenQ                 | 5        | 4.55%   |
| AOC                  | 5        | 4.55%   |
| NEC Computers        | 4        | 3.64%   |
| Sony                 | 3        | 2.73%   |
| RTK                  | 2        | 1.82%   |
| Fujitsu Siemens      | 2        | 1.82%   |
| Unknown (CDD)        | 1        | 0.91%   |
| Lenovo               | 1        | 0.91%   |
| InfoVision           | 1        | 0.91%   |
| Iiyama               | 1        | 0.91%   |
| Hewlett-Packard      | 1        | 0.91%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Ancor Communications ASUS VW199 ACI19ED 1440x900 410x260mm 19.1-inch   | 4        | 3.45%   |
| ViewSonic LCD Monitor VSCC42B 1920x1080 480x270mm 21.7-inch            | 2        | 1.72%   |
| Samsung Electronics SyncMaster SAM027D 1680x1050 430x270mm 20.0-inch   | 2        | 1.72%   |
| Samsung Electronics SMBX2250 SAM071B 1920x1080 480x270mm 21.7-inch     | 2        | 1.72%   |
| Samsung Electronics LCD Monitor SAM0AC6 1920x1080 1110x620mm 50.1-inch | 2        | 1.72%   |
| RTK WCS Display RTK1A1B 1920x1080 344x195mm 15.6-inch                  | 2        | 1.72%   |
| NEC Computers FE791SB NEC61D7 1600x1200 330x240mm 16.1-inch            | 2        | 1.72%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch             | 2        | 1.72%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch              | 2        | 1.72%   |
| ViewSonic VX2458-mhd VSC0437 1920x1080 520x290mm 23.4-inch             | 1        | 0.86%   |
| ViewSonic VP171s-2 VSC4B1B 1280x1024 340x270mm 17.1-inch               | 1        | 0.86%   |
| ViewSonic LCD Monitor VX2451 SERIES 1920x1080                          | 1        | 0.86%   |
| ViewSonic LCD Monitor VSCD22B 1920x1080 520x290mm 23.4-inch            | 1        | 0.86%   |
| ViewSonic LCD Monitor VSC8724 1440x900 410x260mm 19.1-inch             | 1        | 0.86%   |
| ViewSonic LCD Monitor VSC5826 1366x768 410x230mm 18.5-inch             | 1        | 0.86%   |
| ViewSonic LCD Monitor VSC2528 1920x1080 520x290mm 23.4-inch            | 1        | 0.86%   |
| Unknown (CDD) VGA CDD0030 1920x1080 1150x650mm 52.0-inch               | 1        | 0.86%   |
| Sony TV  *00 SNY8204 3840x2160 1220x680mm 55.0-inch                    | 1        | 0.86%   |
| Sony TV  *00 SNY7C04 3840x2160 1080x610mm 48.8-inch                    | 1        | 0.86%   |
| Sony SDM-S75D/F/N SNY3800 1280x1024 340x270mm 17.1-inch                | 1        | 0.86%   |
| Samsung Electronics U32H85x SAM0E3C 3840x2160 700x390mm 31.5-inch      | 1        | 0.86%   |
| Samsung Electronics SyncMaster SAM03CF 1280x1024 340x270mm 17.1-inch   | 1        | 0.86%   |
| Samsung Electronics SyncMaster SAM027E 1680x1050 470x300mm 22.0-inch   | 1        | 0.86%   |
| Samsung Electronics SyncMaster SAM026F 1280x1024 380x300mm 19.1-inch   | 1        | 0.86%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 430x270mm 20.0-inch   | 1        | 0.86%   |
| Samsung Electronics SyncMaster SAM01BB 1280x1024 380x300mm 19.1-inch   | 1        | 0.86%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 340x270mm 17.1-inch   | 1        | 0.86%   |
| Samsung Electronics SMS23A550H SAM07C9 1920x1080 510x290mm 23.1-inch   | 1        | 0.86%   |
| Samsung Electronics SME1920NR SAM06A4 1280x1024 380x300mm 19.1-inch    | 1        | 0.86%   |
| Samsung Electronics SMB2340 SAM0691 1920x1080 510x290mm 23.1-inch      | 1        | 0.86%   |
| Samsung Electronics SMB2240W SAM0699 1680x1050 470x300mm 22.0-inch     | 1        | 0.86%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 520x290mm 23.4-inch      | 1        | 0.86%   |
| Samsung Electronics S24D332 SAM0F5E 1920x1080 530x300mm 24.0-inch      | 1        | 0.86%   |
| Samsung Electronics S23C570 SAM0A56 1920x1080 510x290mm 23.1-inch      | 1        | 0.86%   |
| Samsung Electronics S22B300 SAM08AC 1920x1080 480x270mm 21.7-inch      | 1        | 0.86%   |
| Samsung Electronics S20C200 SAM09B4 1600x900 440x250mm 19.9-inch       | 1        | 0.86%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch       | 1        | 0.86%   |
| Samsung Electronics LCD Monitor SAM03BC 1920x1080                      | 1        | 0.86%   |
| Samsung Electronics LC24RG50 SAM0F91 1920x1080 530x300mm 24.0-inch     | 1        | 0.86%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch      | 1        | 0.86%   |
| Philips PHL 278E9Q PHLC17F 1920x1080 600x340mm 27.2-inch               | 1        | 0.86%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch                | 1        | 0.86%   |
| Philips PHL 240V5 PHLC10A 1920x1080 530x300mm 24.0-inch                | 1        | 0.86%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                 | 1        | 0.86%   |
| Philips LCD Monitor PHLC0B1 1920x1080 480x270mm 21.7-inch              | 1        | 0.86%   |
| Philips LCD Monitor PHL 240V5 1920x1080                                | 1        | 0.86%   |
| Philips 248CLH PHLC088 1920x1080 520x290mm 23.4-inch                   | 1        | 0.86%   |
| NEC Computers LCD190V NEC66D3 1280x1024 380x300mm 19.1-inch            | 1        | 0.86%   |
| NEC Computers LCD Monitor EA241WM 1920x1200                            | 1        | 0.86%   |
| Lenovo LEN-M73Z-D LEN00A0 1600x900 440x240mm 19.7-inch                 | 1        | 0.86%   |
| InfoVision LCD Monitor IVO04E3 1366x768 280x160mm 12.7-inch            | 1        | 0.86%   |
| Iiyama PL2783Q IVM661D 2560x1440 600x340mm 27.2-inch                   | 1        | 0.86%   |
| Hewlett-Packard 23xi HWP3031 1920x1080 510x290mm 23.1-inch             | 1        | 0.86%   |
| Goldstar W1934 GSM4B7A 1440x900 410x260mm 19.1-inch                    | 1        | 0.86%   |
| Goldstar LG ULTRAWIDE GSM59F2 2560x1080 580x240mm 24.7-inch            | 1        | 0.86%   |
| Goldstar LCD Monitor GSM5AB8 1920x1080 480x270mm 21.7-inch             | 1        | 0.86%   |
| Goldstar LCD Monitor GSM5AB6 1920x1080 480x270mm 21.7-inch             | 1        | 0.86%   |
| Goldstar LCD Monitor GSM5806 1920x1080 480x270mm 21.7-inch             | 1        | 0.86%   |
| Goldstar L1953TR GSM4B44 1280x1024 340x270mm 17.1-inch                 | 1        | 0.86%   |
| Goldstar L1753S GSM446F 1280x1024 340x270mm 17.1-inch                  | 1        | 0.86%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 48       | 44.04%  |
| 1280x1024 (SXGA)   | 15       | 13.76%  |
| 3840x2160 (4K)     | 9        | 8.26%   |
| 1680x1050 (WSXGA+) | 8        | 7.34%   |
| 1920x1200 (WUXGA)  | 7        | 6.42%   |
| 1440x900 (WXGA+)   | 6        | 5.5%    |
| 1366x768 (WXGA)    | 5        | 4.59%   |
| 1600x900 (HD+)     | 4        | 3.67%   |
| 2560x1440 (QHD)    | 2        | 1.83%   |
| 1600x1200          | 2        | 1.83%   |
| 2560x1080          | 1        | 0.92%   |
| 1024x768 (XGA)     | 1        | 0.92%   |
| Unknown            | 1        | 0.92%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 17       | 15.32%  |
| 24      | 14       | 12.61%  |
| 19      | 14       | 12.61%  |
| 23      | 12       | 10.81%  |
| 17      | 11       | 9.91%   |
| 27      | 9        | 8.11%   |
| Unknown | 7        | 6.31%   |
| 18      | 5        | 4.5%    |
| 22      | 4        | 3.6%    |
| 31      | 3        | 2.7%    |
| 20      | 3        | 2.7%    |
| 50      | 2        | 1.8%    |
| 16      | 2        | 1.8%    |
| 15      | 2        | 1.8%    |
| 55      | 1        | 0.9%    |
| 52      | 1        | 0.9%    |
| 48      | 1        | 0.9%    |
| 26      | 1        | 0.9%    |
| 14      | 1        | 0.9%    |
| 12      | 1        | 0.9%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 37       | 33.94%  |
| 501-600     | 35       | 32.11%  |
| 301-350     | 15       | 13.76%  |
| Unknown     | 7        | 6.42%   |
| 351-400     | 5        | 4.59%   |
| 1001-1500   | 5        | 4.59%   |
| 601-700     | 3        | 2.75%   |
| 201-300     | 2        | 1.83%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 65       | 59.09%  |
| 16/10   | 20       | 18.18%  |
| 5/4     | 15       | 13.64%  |
| Unknown | 6        | 5.45%   |
| 4/3     | 3        | 2.73%   |
| 21/9    | 1        | 0.91%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 42       | 37.5%   |
| 151-200        | 18       | 16.07%  |
| 141-150        | 15       | 13.39%  |
| 301-350        | 10       | 8.93%   |
| Unknown        | 7        | 6.25%   |
| 251-300        | 6        | 5.36%   |
| More than 1000 | 5        | 4.46%   |
| 351-500        | 3        | 2.68%   |
| 101-110        | 3        | 2.68%   |
| 121-130        | 2        | 1.79%   |
| 61-70          | 1        | 0.89%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 68       | 62.39%  |
| 101-120 | 19       | 17.43%  |
| 121-160 | 8        | 7.34%   |
| Unknown | 7        | 6.42%   |
| 161-240 | 4        | 3.67%   |
| 1-50    | 3        | 2.75%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 130      | 53.72%  |
| 1     | 103      | 42.56%  |
| 2     | 8        | 3.31%   |
| 3     | 1        | 0.41%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 138      | 45.85%  |
| Intel                             | 81       | 26.91%  |
| Qualcomm Atheros                  | 28       | 9.3%    |
| Broadcom                          | 9        | 2.99%   |
| Marvell Technology Group          | 7        | 2.33%   |
| D-Link System                     | 6        | 1.99%   |
| VIA Technologies                  | 4        | 1.33%   |
| IMC Networks                      | 3        | 1%      |
| Huawei Technologies               | 3        | 1%      |
| Qualcomm                          | 2        | 0.66%   |
| D-Link                            | 2        | 0.66%   |
| 3Com                              | 2        | 0.66%   |
| ZTE WCDMA Technologies MSM        | 1        | 0.33%   |
| TP-Link                           | 1        | 0.33%   |
| Sundance Technology Inc / IC Plus | 1        | 0.33%   |
| Silicon Integrated Systems [SiS]  | 1        | 0.33%   |
| Ralink Technology                 | 1        | 0.33%   |
| Ralink                            | 1        | 0.33%   |
| Qualcomm Atheros Communications   | 1        | 0.33%   |
| Qcom                              | 1        | 0.33%   |
| Nvidia                            | 1        | 0.33%   |
| MYRICOM                           | 1        | 0.33%   |
| Mercucys                          | 1        | 0.33%   |
| Edimax Technology                 | 1        | 0.33%   |
| Atmel                             | 1        | 0.33%   |
| Aquantia                          | 1        | 0.33%   |
| Apple                             | 1        | 0.33%   |
| Accton Technology                 | 1        | 0.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 120      | 35.19%  |
| Intel I211 Gigabit Network Connection                                         | 14       | 4.11%   |
| Intel 82574L Gigabit Network Connection                                       | 11       | 3.23%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 7        | 2.05%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 6        | 1.76%   |
| Intel I210 Gigabit Network Connection                                         | 5        | 1.47%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 4        | 1.17%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 4        | 1.17%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 4        | 1.17%   |
| Intel I350 Gigabit Network Connection                                         | 4        | 1.17%   |
| Intel Ethernet Connection I217-V                                              | 4        | 1.17%   |
| Intel 82579V Gigabit Network Connection                                       | 4        | 1.17%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 4        | 1.17%   |
| VIA VT6105/VT6106S [Rhine-III]                                                | 3        | 0.88%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 3        | 0.88%   |
| Realtek RTL8125 2.5GbE Controller                                             | 3        | 0.88%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 3        | 0.88%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 3        | 0.88%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 3        | 0.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 3        | 0.88%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 3        | 0.88%   |
| Intel Wi-Fi 6 AX200                                                           | 3        | 0.88%   |
| Intel Ethernet Connection (7) I219-V                                          | 3        | 0.88%   |
| Intel Ethernet Connection (7) I219-LM                                         | 3        | 0.88%   |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 0.88%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 3        | 0.88%   |
| Intel 82562EZ 10/100 Ethernet Controller                                      | 3        | 0.88%   |
| Intel 82540EM Gigabit Ethernet Controller                                     | 3        | 0.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 2        | 0.59%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 2        | 0.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 2        | 0.59%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 2        | 0.59%   |
| Qualcomm ALCATEL Composite RNDIS Interface                                    | 2        | 0.59%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                             | 2        | 0.59%   |
| Intel Wireless 7265                                                           | 2        | 0.59%   |
| Intel Ethernet Controller I225-V                                              | 2        | 0.59%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 2        | 0.59%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 2        | 0.59%   |
| Intel Ethernet Connection (2) I219-LM                                         | 2        | 0.59%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2        | 0.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2        | 0.59%   |
| Intel 82576 Gigabit Network Connection                                        | 2        | 0.59%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 2        | 0.59%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2        | 0.59%   |
| IMC Networks Realtek RTL8191SU Wireless LAN 802.11n USB 2.0 Network Adapter   | 2        | 0.59%   |
| Huawei E353/E3131                                                             | 2        | 0.59%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 2        | 0.59%   |
| ZTE WCDMA MSM AT Interface                                                    | 1        | 0.29%   |
| VIA VT6102/VT6103 [Rhine-II]                                                  | 1        | 0.29%   |
| TP-Link TP-LINK Wireless USB Adapter                                          | 1        | 0.29%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY    | 1        | 0.29%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                     | 1        | 0.29%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.29%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 1        | 0.29%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                        | 1        | 0.29%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 1        | 0.29%   |
| Realtek Realtek Bluetooth Adapter                                             | 1        | 0.29%   |
| Realtek Killer E3000 2.5GbE Controller                                        | 1        | 0.29%   |
| Realtek 802.11n WLAN Adapter                                                  | 1        | 0.29%   |
| Ralink RT5370 Wireless Adapter                                                | 1        | 0.29%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Qualcomm Atheros                | 14       | 26.92%  |
| Intel                           | 13       | 25%     |
| Realtek Semiconductor           | 12       | 23.08%  |
| IMC Networks                    | 3        | 5.77%   |
| D-Link                          | 2        | 3.85%   |
| TP-Link                         | 1        | 1.92%   |
| Ralink Technology               | 1        | 1.92%   |
| Ralink                          | 1        | 1.92%   |
| Qualcomm Atheros Communications | 1        | 1.92%   |
| Qcom                            | 1        | 1.92%   |
| Mercucys                        | 1        | 1.92%   |
| Edimax Technology               | 1        | 1.92%   |
| Broadcom                        | 1        | 1.92%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 3        | 5.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                     | 3        | 5.77%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                     | 3        | 5.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                       | 3        | 5.77%   |
| Intel Wi-Fi 6 AX200                                                                  | 3        | 5.77%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                      | 2        | 3.85%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                           | 2        | 3.85%   |
| Intel Wireless 7265                                                                  | 2        | 3.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                                      | 2        | 3.85%   |
| IMC Networks Realtek RTL8191SU Wireless LAN 802.11n USB 2.0 Network Adapter          | 2        | 3.85%   |
| TP-Link TP-LINK Wireless USB Adapter                                                 | 1        | 1.92%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                             | 1        | 1.92%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                      | 1        | 1.92%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                               | 1        | 1.92%   |
| Realtek Realtek Bluetooth Adapter                                                    | 1        | 1.92%   |
| Realtek 802.11n WLAN Adapter                                                         | 1        | 1.92%   |
| Ralink RT5370 Wireless Adapter                                                       | 1        | 1.92%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                                 | 1        | 1.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                           | 1        | 1.92%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1        | 1.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 1        | 1.92%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                       | 1        | 1.92%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                     | 1        | 1.92%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                           | 1        | 1.92%   |
| Qcom RT73 USB Wireless LAN Card                                                      | 1        | 1.92%   |
| Mercucys MERCUSYS Wireless USB Adapter                                               | 1        | 1.92%   |
| Intel Wireless 8260                                                                  | 1        | 1.92%   |
| Intel Wireless 7260                                                                  | 1        | 1.92%   |
| Intel Wireless 3160                                                                  | 1        | 1.92%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 1        | 1.92%   |
| Intel Centrino Wireless-N 2230                                                       | 1        | 1.92%   |
| Intel Centrino Wireless-N 2200                                                       | 1        | 1.92%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                                 | 1        | 1.92%   |
| Edimax EW-7612UAn V2 802.11n Wireless Adapter [Realtek RTL8192CU]                    | 1        | 1.92%   |
| D-Link DWA-140 RangeBooster N Adapter(rev.B3) [Ralink RT5372]                        | 1        | 1.92%   |
| D-Link DWA-125 Wireless N 150 Adapter(rev.B1) [Ralink RT5370]                        | 1        | 1.92%   |
| Broadcom BCM43228 802.11a/b/g/n                                                      | 1        | 1.92%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 135      | 51.72%  |
| Intel                             | 74       | 28.35%  |
| Qualcomm Atheros                  | 15       | 5.75%   |
| Broadcom                          | 8        | 3.07%   |
| Marvell Technology Group          | 7        | 2.68%   |
| D-Link System                     | 6        | 2.3%    |
| VIA Technologies                  | 4        | 1.53%   |
| Qualcomm                          | 2        | 0.77%   |
| 3Com                              | 2        | 0.77%   |
| ZTE WCDMA Technologies MSM        | 1        | 0.38%   |
| Sundance Technology Inc / IC Plus | 1        | 0.38%   |
| Silicon Integrated Systems [SiS]  | 1        | 0.38%   |
| Nvidia                            | 1        | 0.38%   |
| Huawei Technologies               | 1        | 0.38%   |
| Aquantia                          | 1        | 0.38%   |
| Apple                             | 1        | 0.38%   |
| Accton Technology                 | 1        | 0.38%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 120      | 42.25%  |
| Intel I211 Gigabit Network Connection                                         | 14       | 4.93%   |
| Intel 82574L Gigabit Network Connection                                       | 11       | 3.87%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 7        | 2.46%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 6        | 2.11%   |
| Intel I210 Gigabit Network Connection                                         | 5        | 1.76%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 4        | 1.41%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 4        | 1.41%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 4        | 1.41%   |
| Intel I350 Gigabit Network Connection                                         | 4        | 1.41%   |
| Intel Ethernet Connection I217-V                                              | 4        | 1.41%   |
| Intel 82579V Gigabit Network Connection                                       | 4        | 1.41%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 4        | 1.41%   |
| VIA VT6105/VT6106S [Rhine-III]                                                | 3        | 1.06%   |
| Realtek RTL8125 2.5GbE Controller                                             | 3        | 1.06%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 3        | 1.06%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 3        | 1.06%   |
| Intel Ethernet Connection (7) I219-V                                          | 3        | 1.06%   |
| Intel Ethernet Connection (7) I219-LM                                         | 3        | 1.06%   |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 1.06%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 3        | 1.06%   |
| Intel 82562EZ 10/100 Ethernet Controller                                      | 3        | 1.06%   |
| Intel 82540EM Gigabit Ethernet Controller                                     | 3        | 1.06%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 2        | 0.7%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 2        | 0.7%    |
| Qualcomm ALCATEL Composite RNDIS Interface                                    | 2        | 0.7%    |
| Marvell Group 88E8001 Gigabit Ethernet Controller                             | 2        | 0.7%    |
| Intel Ethernet Controller I225-V                                              | 2        | 0.7%    |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 2        | 0.7%    |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 2        | 0.7%    |
| Intel Ethernet Connection (2) I219-LM                                         | 2        | 0.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2        | 0.7%    |
| Intel 82576 Gigabit Network Connection                                        | 2        | 0.7%    |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 2        | 0.7%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2        | 0.7%    |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 2        | 0.7%    |
| ZTE WCDMA MSM AT Interface                                                    | 1        | 0.35%   |
| VIA VT6102/VT6103 [Rhine-II]                                                  | 1        | 0.35%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY    | 1        | 0.35%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                     | 1        | 0.35%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 1        | 0.35%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 1        | 0.35%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1        | 0.35%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                 | 1        | 0.35%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 1        | 0.35%   |
| Nvidia MCP77 Ethernet                                                         | 1        | 0.35%   |
| Intel Ethernet Controller X550                                                | 1        | 0.35%   |
| Intel Ethernet Connection X553 1GbE                                           | 1        | 0.35%   |
| Intel Ethernet Connection I218-LM                                             | 1        | 0.35%   |
| Intel Ethernet Connection (2) I218-V                                          | 1        | 0.35%   |
| Intel Ethernet Connection (12) I219-V                                         | 1        | 0.35%   |
| Intel Ethernet Connection (11) I219-V                                         | 1        | 0.35%   |
| Intel Ethernet Connection (10) I219-LM                                        | 1        | 0.35%   |
| Intel 82573E Gigabit Ethernet Controller (Copper)                             | 1        | 0.35%   |
| Intel 82566DC-2 Gigabit Network Connection                                    | 1        | 0.35%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 1        | 0.35%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 1        | 0.35%   |
| Intel 82541GI Gigabit Ethernet Controller                                     | 1        | 0.35%   |
| Intel 82541EI Gigabit Ethernet Controller                                     | 1        | 0.35%   |
| Huawei USB Composite Device                                                   | 1        | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 219      | 80.22%  |
| WiFi     | 49       | 17.95%  |
| Unknown  | 4        | 1.47%   |
| Modem    | 1        | 0.37%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 200      | 86.96%  |
| WiFi     | 29       | 12.61%  |
| Unknown  | 1        | 0.43%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 115      | 47.92%  |
| 2     | 67       | 27.92%  |
| 3     | 25       | 10.42%  |
| 0     | 18       | 7.5%    |
| 4     | 13       | 5.42%   |
| 8     | 1        | 0.42%   |
| 7     | 1        | 0.42%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 230      | 95.83%  |
| Yes  | 10       | 4.17%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 13       | 52%     |
| Qualcomm Atheros Communications | 2        | 8%      |
| IMC Networks                    | 2        | 8%      |
| Cambridge Silicon Radio         | 2        | 8%      |
| ASUSTek Computer                | 2        | 8%      |
| Realtek Semiconductor           | 1        | 4%      |
| Foxconn / Hon Hai               | 1        | 4%      |
| Edimax Technology               | 1        | 4%      |
| Broadcom                        | 1        | 4%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                          | 5        | 20%     |
| Intel AX200 Bluetooth                                       | 4        | 16%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 2        | 8%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2        | 8%      |
| Realtek  Bluetooth 4.0 Adapter                              | 1        | 4%      |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1        | 4%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1        | 4%      |
| Intel Wireless-AC 3168 Bluetooth                            | 1        | 4%      |
| Intel Centrino Bluetooth Wireless Transceiver               | 1        | 4%      |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip        | 1        | 4%      |
| IMC Networks Qualcomm Atheros AR9462 Bluetooth 4.0          | 1        | 4%      |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1        | 4%      |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter     | 1        | 4%      |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter            | 1        | 4%      |
| ASUS Qualcomm Atheros AR9462 Bluetooth 4.0 + HS Adapter     | 1        | 4%      |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 1        | 4%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 136      | 50.94%  |
| Nvidia                           | 56       | 20.97%  |
| AMD                              | 52       | 19.48%  |
| C-Media Electronics              | 4        | 1.5%    |
| Realtek Semiconductor            | 3        | 1.12%   |
| Logitech                         | 3        | 1.12%   |
| Creative Labs                    | 2        | 0.75%   |
| VIA Technologies                 | 1        | 0.37%   |
| Texas Instruments                | 1        | 0.37%   |
| SteelSeries ApS                  | 1        | 0.37%   |
| Silicon Integrated Systems [SiS] | 1        | 0.37%   |
| Samsung Electronics              | 1        | 0.37%   |
| Microsoft                        | 1        | 0.37%   |
| JMTek                            | 1        | 0.37%   |
| GN Netcom                        | 1        | 0.37%   |
| FiiO Electronics Technology      | 1        | 0.37%   |
| ESS Technology                   | 1        | 0.37%   |
| Creative Technology              | 1        | 0.37%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 18       | 6.06%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 16       | 5.39%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 12       | 4.04%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 11       | 3.7%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 11       | 3.7%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 11       | 3.7%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 10       | 3.37%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 10       | 3.37%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 9        | 3.03%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 9        | 3.03%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 6        | 2.02%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 6        | 2.02%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6        | 2.02%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6        | 2.02%   |
| Intel 200 Series PCH HD Audio                                                                     | 6        | 2.02%   |
| AMD FCH Azalia Controller                                                                         | 6        | 2.02%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 6        | 2.02%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5        | 1.68%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5        | 1.68%   |
| Nvidia High Definition Audio Controller                                                           | 4        | 1.35%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4        | 1.35%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4        | 1.35%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 4        | 1.35%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 4        | 1.35%   |
| Nvidia MCP61 High Definition Audio                                                                | 3        | 1.01%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 3        | 1.01%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3        | 1.01%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 3        | 1.01%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 3        | 1.01%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3        | 1.01%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                                              | 3        | 1.01%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 3        | 1.01%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 3        | 1.01%   |
| Realtek Semiconductor Realtek USB Audio                                                           | 2        | 0.67%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 2        | 0.67%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 2        | 0.67%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2        | 0.67%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 2        | 0.67%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 2        | 0.67%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2        | 0.67%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 2        | 0.67%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2        | 0.67%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 2        | 0.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2        | 0.67%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 2        | 0.67%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2        | 0.67%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                                     | 2        | 0.67%   |
| AMD Wrestler HDMI Audio                                                                           | 2        | 0.67%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2        | 0.67%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1        | 0.34%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                 | 1        | 0.34%   |
| SteelSeries ApS SteelSeries Arctis 5 Arctis 5 Chat Arctis 5 Game                                  | 1        | 0.34%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 1        | 0.34%   |
| Samsung Electronics Samsung Type-C to 3.5pi gender adapter                                        | 1        | 0.34%   |
| Realtek Semiconductor TX-384Khz Hifi Type-C Audio                                                 | 1        | 0.34%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1        | 0.34%   |
| Nvidia MCP79 High Definition Audio                                                                | 1        | 0.34%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 1        | 0.34%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1        | 0.34%   |
| Nvidia GP102 HDMI Audio Controller                                                                | 1        | 0.34%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown                      | 62       | 29.38%  |
| Kingston                     | 44       | 20.85%  |
| Samsung Electronics          | 23       | 10.9%   |
| Crucial                      | 12       | 5.69%   |
| SK hynix                     | 10       | 4.74%   |
| Corsair                      | 7        | 3.32%   |
| Patriot                      | 6        | 2.84%   |
| Micron Technology            | 6        | 2.84%   |
| Unknown                      | 5        | 2.37%   |
| Nanya Technology             | 4        | 1.9%    |
| G.Skill                      | 4        | 1.9%    |
| AMD                          | 4        | 1.9%    |
| A-DATA Technology            | 4        | 1.9%    |
| Unifosa                      | 2        | 0.95%   |
| Transcend                    | 2        | 0.95%   |
| Patriot Memory (PDP Systems) | 2        | 0.95%   |
| Elpida                       | 2        | 0.95%   |
| Apacer                       | 2        | 0.95%   |
| Unknown (ABCD)               | 1        | 0.47%   |
| Tigo                         | 1        | 0.47%   |
| S                            | 1        | 0.47%   |
| Ramos Technology             | 1        | 0.47%   |
| Qumo                         | 1        | 0.47%   |
| Kllisre                      | 1        | 0.47%   |
| Kingmax                      | 1        | 0.47%   |
| H                            | 1        | 0.47%   |
| Goldkey                      | 1        | 0.47%   |
| Atermiter                    | 1        | 0.47%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                    | Desktops | Percent |
|--------------------------------------------------------------------------|----------|---------|
| Unknown                                                                  | 5        | 2.07%   |
| Unknown RAM Module 512MB DIMM SDRAM                                      | 4        | 1.66%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                     | 4        | 1.66%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                              | 4        | 1.66%   |
| Unknown RAM Module 1GB DIMM SDRAM                                        | 4        | 1.66%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                     | 3        | 1.24%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 1333MT/s                      | 3        | 1.24%   |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3400MT/s                              | 3        | 1.24%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                                     | 2        | 0.83%   |
| Unknown RAM Module 8192MB DIMM 1066MT/s                                  | 2        | 0.83%   |
| Unknown RAM Module 2GB DIMM SDRAM                                        | 2        | 0.83%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                                 | 2        | 0.83%   |
| Unknown RAM Module 2GB DIMM 800MT/s                                      | 2        | 0.83%   |
| Unknown RAM Module 1GB DIMM 1333MT/s                                     | 2        | 0.83%   |
| Unknown RAM Module 1024MB DIMM SDRAM                                     | 2        | 0.83%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s                     | 2        | 0.83%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                    | 2        | 0.83%   |
| Samsung RAM M393A2K40BB2-CTD 16GB DIMM DDR4 2667MT/s                     | 2        | 0.83%   |
| Patriot Memory (PDP Systems) RAM 3200 C16 Series 16GB DIMM DDR4 2400MT/s | 2        | 0.83%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3200MT/s                     | 2        | 0.83%   |
| Kingston RAM KHX2400C11D3/8GX 8GB DIMM DDR3 2400MT/s                     | 2        | 0.83%   |
| Kingston RAM 99U5595-003.A00LF 2GB DIMM DDR3 1600MT/s                    | 2        | 0.83%   |
| Kingston RAM 99U5471-020.A00LF 4GB DIMM DDR3 1333MT/s                    | 2        | 0.83%   |
| Kingston RAM 9905584-029.A00LF 4GB DIMM DDR3 1600MT/s                    | 2        | 0.83%   |
| G.Skill RAM F4-4000C18-32GVK 32GB DIMM DDR4 3200MT/s                     | 2        | 0.83%   |
| Crucial RAM CT8G4SFS824A.C8BD1 8GB SODIMM DDR4 2400MT/s                  | 2        | 0.83%   |
| Crucial RAM CT51264BA160B.C16F 4GB DIMM DDR3 1600MT/s                    | 2        | 0.83%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s                    | 2        | 0.83%   |
| Apacer RAM 78.A2GF7.4000B 2GB SODIMM DDR4 2400MT/s                       | 2        | 0.83%   |
| Unknown RAM Module 8192MB DIMM 400MT/s                                   | 1        | 0.41%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                                  | 1        | 0.41%   |
| Unknown RAM Module 512MB DIMM DDR2 667MT/s                               | 1        | 0.41%   |
| Unknown RAM Module 512MB DIMM DDR2                                       | 1        | 0.41%   |
| Unknown RAM Module 512MB DIMM DDR 400MT/s                                | 1        | 0.41%   |
| Unknown RAM Module 512MB DIMM DDR 133MT/s                                | 1        | 0.41%   |
| Unknown RAM Module 512MB DIMM 667MT/s                                    | 1        | 0.41%   |
| Unknown RAM Module 512MB DIMM 400MT/s                                    | 1        | 0.41%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                              | 1        | 0.41%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                                | 1        | 0.41%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                                | 1        | 0.41%   |
| Unknown RAM Module 4GB DIMM 400MT/s                                      | 1        | 0.41%   |
| Unknown RAM Module 4096MB DIMM DDR3                                      | 1        | 0.41%   |
| Unknown RAM Module 4096MB DIMM DDR2 667MT/s                              | 1        | 0.41%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                                  | 1        | 0.41%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                                  | 1        | 0.41%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s                               | 1        | 0.41%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                              | 1        | 0.41%   |
| Unknown RAM Module 2GB DIMM SDRAM 533MT/s                                | 1        | 0.41%   |
| Unknown RAM Module 2GB DIMM DDR3 1600MT/s                                | 1        | 0.41%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                                | 1        | 0.41%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                                | 1        | 0.41%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                                 | 1        | 0.41%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                                 | 1        | 0.41%   |
| Unknown RAM Module 2GB DIMM DDR 667MT/s                                  | 1        | 0.41%   |
| Unknown RAM Module 2GB DIMM                                              | 1        | 0.41%   |
| Unknown RAM Module 256MB DIMM DDR 400MT/s                                | 1        | 0.41%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                              | 1        | 0.41%   |
| Unknown RAM Module 2048MB DIMM DDR2 533MT/s                              | 1        | 0.41%   |
| Unknown RAM Module 2048MB DIMM DDR2 266MT/s                              | 1        | 0.41%   |
| Unknown RAM Module 2048MB DIMM DDR2                                      | 1        | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 75       | 39.47%  |
| DDR4    | 57       | 30%     |
| Unknown | 20       | 10.53%  |
| DDR2    | 17       | 8.95%   |
| SDRAM   | 13       | 6.84%   |
| DDR     | 7        | 3.68%   |
| LPDDR4  | 1        | 0.53%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 167      | 87.89%  |
| SODIMM | 23       | 12.11%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 53       | 25.73%  |
| 2048  | 49       | 23.79%  |
| 8192  | 44       | 21.36%  |
| 16384 | 24       | 11.65%  |
| 1024  | 21       | 10.19%  |
| 512   | 10       | 4.85%   |
| 32768 | 4        | 1.94%   |
| 256   | 1        | 0.49%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 36       | 18.09%  |
| 1333    | 35       | 17.59%  |
| 2400    | 24       | 12.06%  |
| 800     | 17       | 8.54%   |
| 3200    | 14       | 7.04%   |
| Unknown | 14       | 7.04%   |
| 667     | 10       | 5.03%   |
| 2667    | 9        | 4.52%   |
| 2133    | 7        | 3.52%   |
| 400     | 7        | 3.52%   |
| 1066    | 5        | 2.51%   |
| 2666    | 4        | 2.01%   |
| 3400    | 3        | 1.51%   |
| 1866    | 2        | 1.01%   |
| 1067    | 2        | 1.01%   |
| 533     | 2        | 1.01%   |
| 3733    | 1        | 0.5%    |
| 2048    | 1        | 0.5%    |
| 1867    | 1        | 0.5%    |
| 1334    | 1        | 0.5%    |
| 933     | 1        | 0.5%    |
| 333     | 1        | 0.5%    |
| 266     | 1        | 0.5%    |
| 133     | 1        | 0.5%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Seiko Epson        | 1        | 25%     |
| Kyocera            | 1        | 25%     |
| Hewlett-Packard    | 1        | 25%     |
| Brother Industries | 1        | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Seiko Epson USB2.0 Printer (Hi-speed) | 1        | 25%     |
| Kyocera FS-1025MFP                    | 1        | 25%     |
| HP HP Laser 107w                      | 1        | 25%     |
| Brother HL-2030 Laser Printer         | 1        | 25%     |

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


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Z-Star Microelectronics | 1        | 11.11%  |
| Ricoh                   | 1        | 11.11%  |
| Realtek Semiconductor   | 1        | 11.11%  |
| Microdia                | 1        | 11.11%  |
| Huawei Technologies     | 1        | 11.11%  |
| Chicony Electronics     | 1        | 11.11%  |
| Aveo Technology         | 1        | 11.11%  |
| Arkmicro Technologies   | 1        | 11.11%  |
| A4Tech                  | 1        | 11.11%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Z-Star Integrated Camera          | 1        | 11.11%  |
| Ricoh USB2.0 Camera               | 1        | 11.11%  |
| Realtek USB Video Device          | 1        | 11.11%  |
| Microdia ASUS USB2.0 Webcam       | 1        | 11.11%  |
| Huawei HiCamera                   | 1        | 11.11%  |
| Chicony USB2.0 VGA UVC WebCam     | 1        | 11.11%  |
| Aveo Camera                       | 1        | 11.11%  |
| Arkmicro USB2.0 PC CAMERA         | 1        | 11.11%  |
| A4Tech A4tech FHD 1080P PC Camera | 1        | 11.11%  |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Validity Sensors | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor | 1        | 100%    |

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
| 0     | 115      | 47.72%  |
| 1     | 96       | 39.83%  |
| 2     | 21       | 8.71%   |
| 3     | 7        | 2.9%    |
| 4     | 2        | 0.83%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 98       | 65.33%  |
| Net/wireless             | 16       | 10.67%  |
| Sound                    | 14       | 9.33%   |
| Firewire controller      | 6        | 4%      |
| Bluetooth                | 5        | 3.33%   |
| Graphics card            | 3        | 2%      |
| Network                  | 2        | 1.33%   |
| Net/ethernet             | 2        | 1.33%   |
| Card reader              | 2        | 1.33%   |
| Storage/ata              | 1        | 0.67%   |
| Storage                  | 1        | 0.67%   |

