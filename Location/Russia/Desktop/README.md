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

Total: 340

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| Unknown       | Unknown                     | [57765224eb](https://bsd-hardware.info/?probe=57765224eb) | Mar 18, 2022 |
| Unknown       | Unknown                     | [6e7384f4cc](https://bsd-hardware.info/?probe=6e7384f4cc) | Mar 15, 2022 |
| Huanan        | X99-F8D V2.4                | [4ef193841e](https://bsd-hardware.info/?probe=4ef193841e) | Mar 13, 2022 |
| Gigabyte      | G31M-S2C                    | [5a22bb6991](https://bsd-hardware.info/?probe=5a22bb6991) | Mar 12, 2022 |
| MSI           | B350M BAZOOKA               | [bac8d0bdb7](https://bsd-hardware.info/?probe=bac8d0bdb7) | Mar 11, 2022 |
| ASRock        | G41C-VS                     | [a9a1b1a493](https://bsd-hardware.info/?probe=a9a1b1a493) | Mar 03, 2022 |
| Intel         | DN2800MT AAG23738-600       | [8ecf2d023f](https://bsd-hardware.info/?probe=8ecf2d023f) | Mar 02, 2022 |
| Unknown       | Unknown                     | [62f4e0a060](https://bsd-hardware.info/?probe=62f4e0a060) | Feb 21, 2022 |
| Gigabyte      | X58A-UD5                    | [58d57520c1](https://bsd-hardware.info/?probe=58d57520c1) | Feb 20, 2022 |
| Unknown       | Unknown                     | [da786acd84](https://bsd-hardware.info/?probe=da786acd84) | Feb 20, 2022 |
| Gigabyte      | C1037UN-EU                  | [5b6dd82da8](https://bsd-hardware.info/?probe=5b6dd82da8) | Feb 18, 2022 |
| ASRock        | B460M Pro4                  | [7a2781344f](https://bsd-hardware.info/?probe=7a2781344f) | Feb 17, 2022 |
| Unknown       | Unknown                     | [06887b10fd](https://bsd-hardware.info/?probe=06887b10fd) | Feb 15, 2022 |
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
| Unknown       | Unknown                     | [6d184a1e62](https://bsd-hardware.info/?probe=6d184a1e62) | Dec 23, 2021 |
| Gigabyte      | E3000N                      | [eb0ba1b296](https://bsd-hardware.info/?probe=eb0ba1b296) | Dec 22, 2021 |
| HP            | 1850                        | [aa737033c4](https://bsd-hardware.info/?probe=aa737033c4) | Dec 21, 2021 |
| HP            | 1850                        | [17f42cda78](https://bsd-hardware.info/?probe=17f42cda78) | Dec 21, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [5cc62c68f9](https://bsd-hardware.info/?probe=5cc62c68f9) | Dec 21, 2021 |
| ASRock        | H110M-DGS                   | [40c4553adb](https://bsd-hardware.info/?probe=40c4553adb) | Dec 21, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [bc55ac50d1](https://bsd-hardware.info/?probe=bc55ac50d1) | Dec 20, 2021 |
| Unknown       | Unknown                     | [68541bb331](https://bsd-hardware.info/?probe=68541bb331) | Dec 20, 2021 |
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
| firefly       | roc-rk3399-pc-plus          | [dab56eef53](https://bsd-hardware.info/?probe=dab56eef53) | Nov 07, 2021 |
| firefly       | roc-rk3399-pc-plus          | [f26b302e43](https://bsd-hardware.info/?probe=f26b302e43) | Nov 07, 2021 |
| Unknown       | Intel X79                   | [044908e7c3](https://bsd-hardware.info/?probe=044908e7c3) | Oct 30, 2021 |
| Gigabyte      | Z77X-UD3H                   | [4c9b877754](https://bsd-hardware.info/?probe=4c9b877754) | Oct 29, 2021 |
| HP            | 0A60h                       | [5c227c5b61](https://bsd-hardware.info/?probe=5c227c5b61) | Oct 27, 2021 |
| radxa         | rock-pi-4                   | [767ef0f0a6](https://bsd-hardware.info/?probe=767ef0f0a6) | Oct 27, 2021 |
| radxa         | rock-pi-4                   | [fcd3e65f7e](https://bsd-hardware.info/?probe=fcd3e65f7e) | Oct 26, 2021 |
| Acer          | RS880M05                    | [4718f0cb0c](https://bsd-hardware.info/?probe=4718f0cb0c) | Oct 21, 2021 |
| radxa         | rock-pi-4                   | [876564310f](https://bsd-hardware.info/?probe=876564310f) | Oct 19, 2021 |
| Unknown       | Unknown                     | [9716564d5e](https://bsd-hardware.info/?probe=9716564d5e) | Oct 19, 2021 |
| firefly       | roc-rk3399-pc-plus          | [39c78ac754](https://bsd-hardware.info/?probe=39c78ac754) | Oct 19, 2021 |
| ASUSTek       | P5P43TD PRO                 | [2870e26de1](https://bsd-hardware.info/?probe=2870e26de1) | Oct 17, 2021 |
| firefly       | roc-rk3399-pc-plus          | [5173ffc13b](https://bsd-hardware.info/?probe=5173ffc13b) | Oct 17, 2021 |
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
| firefly       | roc-rk3399-pc-plus          | [198c4264f9](https://bsd-hardware.info/?probe=198c4264f9) | Sep 16, 2021 |
| firefly       | roc-rk3399-pc-plus          | [d05c3ba858](https://bsd-hardware.info/?probe=d05c3ba858) | Sep 15, 2021 |
| firefly       | roc-rk3399-pc-plus          | [062602e8db](https://bsd-hardware.info/?probe=062602e8db) | Sep 15, 2021 |
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
| Unknown       | Unknown                     | [ec302a221a](https://bsd-hardware.info/?probe=ec302a221a) | May 15, 2021 |
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
| Unknown       | Unknown                     | [1c4a81b9a5](https://bsd-hardware.info/?probe=1c4a81b9a5) | Apr 17, 2021 |
| Unknown       | Unknown                     | [48090193c1](https://bsd-hardware.info/?probe=48090193c1) | Apr 17, 2021 |
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
| PC Engines    | apu2                        | [02a107a767](https://bsd-hardware.info/?probe=02a107a767) | Feb 23, 2021 |
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
| Unknown       | Unknown                     | [d1b1775be3](https://bsd-hardware.info/?probe=d1b1775be3) | Sep 23, 2020 |
| ASUSTek       | H81M-D PLUS                 | [e8ab84404c](https://bsd-hardware.info/?probe=e8ab84404c) | Sep 22, 2020 |
| Unknown       | Unknown                     | [c6b2c64d14](https://bsd-hardware.info/?probe=c6b2c64d14) | Sep 20, 2020 |
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
| Unknown       | Unknown                     | [9fbca0a216](https://bsd-hardware.info/?probe=9fbca0a216) | Jun 17, 2020 |
| Unknown       | Unknown                     | [a24cfb5df9](https://bsd-hardware.info/?probe=a24cfb5df9) | Jun 16, 2020 |
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
| Unknown       | Unknown                     | [8ba62bd121](https://bsd-hardware.info/?probe=8ba62bd121) | May 25, 2020 |
| ASUSTek       | B75M-PLUS                   | [4620a00ccc](https://bsd-hardware.info/?probe=4620a00ccc) | May 25, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| OpenBSD 6.8          | 19       | 7.12%   |
| helloSystem 0.7.0    | 19       | 7.12%   |
| FreeBSD 12.1-p5      | 15       | 5.62%   |
| FreeBSD 13.0         | 14       | 5.24%   |
| OpenBSD 7.1          | 9        | 3.37%   |
| helloSystem 0.5.0    | 9        | 3.37%   |
| FreeBSD 13.0-STABLE  | 9        | 3.37%   |
| OpenBSD 7.0          | 8        | 3%      |
| OpenBSD 6.7          | 8        | 3%      |
| FreeBSD 12.1-STABLE  | 7        | 2.62%   |
| helloSystem 0.6.0    | 6        | 2.25%   |
| helloSystem 0.4.0    | 6        | 2.25%   |
| FreeBSD 12.2         | 6        | 2.25%   |
| GhostBSD 20.04.02    | 5        | 1.87%   |
| FreeBSD 12.1-p7      | 5        | 1.87%   |
| OPNsense 22.1.6      | 4        | 1.5%    |
| OPNsense 21.1.5      | 4        | 1.5%    |
| OpenBSD 6.9          | 4        | 1.5%    |
| helloSystem 0.8.0    | 4        | 1.5%    |
| FreeBSD 14.0-CURRENT | 4        | 1.5%    |
| FreeBSD 12.2-p3      | 4        | 1.5%    |
| FreeBSD 12.2-p2      | 4        | 1.5%    |
| OPNsense 22.1        | 3        | 1.12%   |
| OPNsense 21.7.6      | 3        | 1.12%   |
| OPNsense 21.1.7      | 3        | 1.12%   |
| OPNsense 21.1.1      | 3        | 1.12%   |
| NetBSD 9.0           | 3        | 1.12%   |
| FreeBSD 13.0-p5      | 3        | 1.12%   |
| FreeBSD 13.0-CURRENT | 3        | 1.12%   |
| FreeBSD 12.2-p4      | 3        | 1.12%   |
| FreeBSD 12.1-p8      | 3        | 1.12%   |
| FreeBSD 12.1-p6      | 3        | 1.12%   |
| OPNsense 21.7.1      | 2        | 0.75%   |
| OPNsense 21.1.3      | 2        | 0.75%   |
| OPNsense 21.1        | 2        | 0.75%   |
| NomadBSD 5806f915    | 2        | 0.75%   |
| NetBSD 9.2           | 2        | 0.75%   |
| NetBSD 9.1           | 2        | 0.75%   |
| FreeBSD 13.0-p6      | 2        | 0.75%   |
| FreeBSD 13.0-p4      | 2        | 0.75%   |
| FreeBSD 13.0-p2      | 2        | 0.75%   |
| FreeBSD 13.0-p11     | 2        | 0.75%   |
| FreeBSD 12.3-p1      | 2        | 0.75%   |
| FreeBSD 12.2-STABLE  | 2        | 0.75%   |
| FreeBSD 12.1-p10     | 2        | 0.75%   |
| pfSense 2.4.4        | 1        | 0.37%   |
| PC-BSD 10.3          | 1        | 0.37%   |
| OPNsense 22.1.7      | 1        | 0.37%   |
| OPNsense 22.1.4      | 1        | 0.37%   |
| OPNsense 22.1.1      | 1        | 0.37%   |
| OPNsense 21.7.8      | 1        | 0.37%   |
| OPNsense 21.7.7      | 1        | 0.37%   |
| OPNsense 21.7.3      | 1        | 0.37%   |
| OPNsense 21.7.2      | 1        | 0.37%   |
| OPNsense 21.7        | 1        | 0.37%   |
| OPNsense 21.1.4      | 1        | 0.37%   |
| OPNsense 21.1.2      | 1        | 0.37%   |
| OPNsense 20.7.8      | 1        | 0.37%   |
| NomadBSD 1.3.2       | 1        | 0.37%   |
| NetBSD 9.99.94       | 1        | 0.37%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| FreeBSD     | 97       | 42.17%  |
| helloSystem | 44       | 19.13%  |
| OpenBSD     | 37       | 16.09%  |
| OPNsense    | 30       | 13.04%  |
| NetBSD      | 9        | 3.91%   |
| GhostBSD    | 5        | 2.17%   |
| NomadBSD    | 3        | 1.3%    |
| pfSense     | 1        | 0.43%   |
| PC-BSD      | 1        | 0.43%   |
| FuryBSD     | 1        | 0.43%   |
| DragonFly   | 1        | 0.43%   |
| ClonOS      | 1        | 0.43%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| amd64  | 201      | 89.33%  |
| i386   | 11       | 4.89%   |
| arm64  | 9        | 4%      |
| macppc | 1        | 0.44%   |
| evbarm | 1        | 0.44%   |
| armv7  | 1        | 0.44%   |
| arm    | 1        | 0.44%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 96       | 40.85%  |
| helloDesktop | 51       | 21.7%   |
| fvwm         | 20       | 8.51%   |
| XFCE         | 15       | 6.38%   |
| KDE5         | 14       | 5.96%   |
| MATE         | 11       | 4.68%   |
| Openbox      | 9        | 3.83%   |
| TWM          | 7        | 2.98%   |
| GNOME        | 5        | 2.13%   |
| Fluxbox      | 5        | 2.13%   |
| KWin         | 1        | 0.43%   |
| akonadi_newm | 1        | 0.43%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 124      | 54.63%  |
| Console | 103      | 45.37%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 142      | 62.56%  |
| SLiM    | 60       | 26.43%  |
| SDDM    | 12       | 5.29%   |
| LightDM | 7        | 3.08%   |
| XDM     | 3        | 1.32%   |
| GDM     | 3        | 1.32%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang           | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 75       | 32.19%  |
| ru_RU          | 73       | 31.33%  |
| en_US          | 56       | 24.03%  |
| C              | 26       | 11.16%  |
| ru_RU.KOI8-R   | 2        | 0.86%   |
| cv_RU.US-ASCII | 1        | 0.43%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 128      | 56.14%  |
| BIOS | 100      | 43.86%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Zfs     | 96       | 41.92%  |
| Ufs     | 77       | 33.62%  |
| Ffs     | 37       | 16.16%  |
| Cd9660  | 18       | 7.86%   |
| Hammer2 | 1        | 0.44%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 178      | 78.76%  |
| MBR     | 46       | 20.35%  |
| Unknown | 2        | 0.88%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 64       | 28.44%  |
| Gigabyte Technology | 38       | 16.89%  |
| ASRock              | 26       | 11.56%  |
| Unknown             | 21       | 9.33%   |
| MSI                 | 14       | 6.22%   |
| Intel               | 9        | 4%      |
| Supermicro          | 6        | 2.67%   |
| Pegatron            | 6        | 2.67%   |
| Hewlett-Packard     | 6        | 2.67%   |
| Lenovo              | 4        | 1.78%   |
| Acer                | 4        | 1.78%   |
| PC Engines          | 3        | 1.33%   |
| Huanan              | 3        | 1.33%   |
| Dell                | 3        | 1.33%   |
| Foxconn             | 2        | 0.89%   |
| Sony                | 1        | 0.44%   |
| Shuttle             | 1        | 0.44%   |
| radxa               | 1        | 0.44%   |
| MW                  | 1        | 0.44%   |
| Kontron             | 1        | 0.44%   |
| KOHJINSHA           | 1        | 0.44%   |
| khadas              | 1        | 0.44%   |
| Intel CNCTION-IAF   | 1        | 0.44%   |
| IBM                 | 1        | 0.44%   |
| Fujitsu             | 1        | 0.44%   |
| friendlyelec        | 1        | 0.44%   |
| firefly             | 1        | 0.44%   |
| ECS                 | 1        | 0.44%   |
| Centerm             | 1        | 0.44%   |
| Biostar             | 1        | 0.44%   |
| Apple               | 1        | 0.44%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                                                  | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Unknown                                                               | 22       | 9.78%   |
| ASUS All Series                                                       | 7        | 3.11%   |
| PC Engines APU2                                                       | 3        | 1.33%   |
| Supermicro SSG-6029P-E1CR12L                                          | 2        | 0.89%   |
| Pegatron SAISHIAT2                                                    | 2        | 0.89%   |
| MSI MS-7817                                                           | 2        | 0.89%   |
| Huanan X79 INTEL (INTEL Xeon E5/Corei7 DMI2 - C600/C200 Cipset V2.49P | 2        | 0.89%   |
| HP ProLiant MicroServer                                               | 2        | 0.89%   |
| Gigabyte M68MT-S2P                                                    | 2        | 0.89%   |
| Gigabyte GA-IMB370TN                                                  | 2        | 0.89%   |
| Gigabyte C1037UN-EU                                                   | 2        | 0.89%   |
| Gigabyte B450 AORUS M                                                 | 2        | 0.89%   |
| Dell OptiPlex 7040                                                    | 2        | 0.89%   |
| ASUS PRIME Z590-P                                                     | 2        | 0.89%   |
| ASUS P8Z77-V LX                                                       | 2        | 0.89%   |
| ASUS P6T SE                                                           | 2        | 0.89%   |
| ASUS P4P800-VM                                                        | 2        | 0.89%   |
| ASRock J4205-ITX                                                      | 2        | 0.89%   |
| Supermicro SYS-6028R-TRT                                              | 1        | 0.44%   |
| Supermicro SYS-5019A-FTN4                                             | 1        | 0.44%   |
| Supermicro SSG-6028R-E1CR12T                                          | 1        | 0.44%   |
| Supermicro NSM5200-06-EU                                              | 1        | 0.44%   |
| Sony VPCL22Z1R                                                        | 1        | 0.44%   |
| Shuttle DS20U                                                         | 1        | 0.44%   |
| radxa rock-pi-4                                                       | 1        | 0.44%   |
| Pegatron SKLD4-P1                                                     | 1        | 0.44%   |
| Pegatron SAISHIAT                                                     | 1        | 0.44%   |
| Pegatron IPPPV-D3G                                                    | 1        | 0.44%   |
| Pegatron Compaq dx2400 Microtower                                     | 1        | 0.44%   |
| MW GMLK-2_5G4L                                                        | 1        | 0.44%   |
| MSI MS-9A25                                                           | 1        | 0.44%   |
| MSI MS-7C96                                                           | 1        | 0.44%   |
| MSI MS-7B93                                                           | 1        | 0.44%   |
| MSI MS-7B89                                                           | 1        | 0.44%   |
| MSI MS-7A38                                                           | 1        | 0.44%   |
| MSI MS-7A15                                                           | 1        | 0.44%   |
| MSI MS-7922                                                           | 1        | 0.44%   |
| MSI MS-7816                                                           | 1        | 0.44%   |
| MSI MS-7788                                                           | 1        | 0.44%   |
| MSI MS-7529                                                           | 1        | 0.44%   |
| MSI MS-7255                                                           | 1        | 0.44%   |
| MSI MS-7235                                                           | 1        | 0.44%   |
| Lenovo ThinkPad X240 20ALA0AHRT                                       | 1        | 0.44%   |
| Lenovo ThinkCentre M73z 10BB001DRU                                    | 1        | 0.44%   |
| Lenovo ThinkCentre M600 10GB000TRU                                    | 1        | 0.44%   |
| Lenovo ThinkCentre A55 898562G                                        | 1        | 0.44%   |
| Kontron KT965/ATXP                                                    | 1        | 0.44%   |
| KOHJINSHA SH series                                                   | 1        | 0.44%   |
| khadas edge-v                                                         | 1        | 0.44%   |
| Intel X79 V2.72A                                                      | 1        | 0.44%   |
| Intel X64                                                             | 1        | 0.44%   |
| Intel S3000AH                                                         | 1        | 0.44%   |
| Intel J1900                                                           | 1        | 0.44%   |
| Intel DN2820FYK H24582-203                                            | 1        | 0.44%   |
| Intel DN2800MT AAG23738-600                                           | 1        | 0.44%   |
| Intel DH67BL                                                          | 1        | 0.44%   |
| Intel DG33BU AAD79951-408                                             | 1        | 0.44%   |
| Intel DCP847SKE                                                       | 1        | 0.44%   |
| Intel CNCTION-IAF CNCTION-IAF                                         | 1        | 0.44%   |
| IBM 81832BG                                                           | 1        | 0.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown                      | 22       | 9.78%   |
| ASUS PRIME                   | 7        | 3.11%   |
| ASUS All                     | 7        | 3.11%   |
| HP ProLiant                  | 4        | 1.78%   |
| PC Engines APU2              | 3        | 1.33%   |
| Lenovo ThinkCentre           | 3        | 1.33%   |
| Dell OptiPlex                | 3        | 1.33%   |
| ASUS ROG                     | 3        | 1.33%   |
| ASUS P5Q                     | 3        | 1.33%   |
| ASRock X570                  | 3        | 1.33%   |
| Acer Aspire                  | 3        | 1.33%   |
| Supermicro SSG-6029P-E1CR12L | 2        | 0.89%   |
| Pegatron SAISHIAT2           | 2        | 0.89%   |
| MSI MS-7817                  | 2        | 0.89%   |
| Huanan X79                   | 2        | 0.89%   |
| HP Compaq                    | 2        | 0.89%   |
| Gigabyte M68MT-S2P           | 2        | 0.89%   |
| Gigabyte GA-IMB370TN         | 2        | 0.89%   |
| Gigabyte C1037UN-EU          | 2        | 0.89%   |
| Gigabyte B450                | 2        | 0.89%   |
| ASUS TUF                     | 2        | 0.89%   |
| ASUS P8Z77-V                 | 2        | 0.89%   |
| ASUS P7H55-M                 | 2        | 0.89%   |
| ASUS P6T                     | 2        | 0.89%   |
| ASUS P5B                     | 2        | 0.89%   |
| ASUS P4P800-VM               | 2        | 0.89%   |
| ASRock J4205-ITX             | 2        | 0.89%   |
| Supermicro SYS-6028R-TRT     | 1        | 0.44%   |
| Supermicro SYS-5019A-FTN4    | 1        | 0.44%   |
| Supermicro SSG-6028R-E1CR12T | 1        | 0.44%   |
| Supermicro NSM5200-06-EU     | 1        | 0.44%   |
| Sony VPCL22Z1R               | 1        | 0.44%   |
| Shuttle DS20U                | 1        | 0.44%   |
| radxa rock-pi-4              | 1        | 0.44%   |
| Pegatron SKLD4-P1            | 1        | 0.44%   |
| Pegatron SAISHIAT            | 1        | 0.44%   |
| Pegatron IPPPV-D3G           | 1        | 0.44%   |
| Pegatron Compaq              | 1        | 0.44%   |
| MW GMLK-2                    | 1        | 0.44%   |
| MSI MS-9A25                  | 1        | 0.44%   |
| MSI MS-7C96                  | 1        | 0.44%   |
| MSI MS-7B93                  | 1        | 0.44%   |
| MSI MS-7B89                  | 1        | 0.44%   |
| MSI MS-7A38                  | 1        | 0.44%   |
| MSI MS-7A15                  | 1        | 0.44%   |
| MSI MS-7922                  | 1        | 0.44%   |
| MSI MS-7816                  | 1        | 0.44%   |
| MSI MS-7788                  | 1        | 0.44%   |
| MSI MS-7529                  | 1        | 0.44%   |
| MSI MS-7255                  | 1        | 0.44%   |
| MSI MS-7235                  | 1        | 0.44%   |
| Lenovo ThinkPad              | 1        | 0.44%   |
| Kontron KT965                | 1        | 0.44%   |
| KOHJINSHA SH                 | 1        | 0.44%   |
| khadas edge-v                | 1        | 0.44%   |
| Intel X79                    | 1        | 0.44%   |
| Intel X64                    | 1        | 0.44%   |
| Intel S3000AH                | 1        | 0.44%   |
| Intel J1900                  | 1        | 0.44%   |
| Intel DN2820FYK              | 1        | 0.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2019    | 25       | 11.11%  |
| 2018    | 22       | 9.78%   |
| 2021    | 16       | 7.11%   |
| 2020    | 15       | 6.67%   |
| 2014    | 15       | 6.67%   |
| 2013    | 15       | 6.67%   |
| 2011    | 15       | 6.67%   |
| 2009    | 13       | 5.78%   |
| 2012    | 12       | 5.33%   |
| 2010    | 12       | 5.33%   |
| Unknown | 12       | 5.33%   |
| 2016    | 9        | 4%      |
| 2008    | 9        | 4%      |
| 2007    | 9        | 4%      |
| 2017    | 8        | 3.56%   |
| 2015    | 6        | 2.67%   |
| 2005    | 5        | 2.22%   |
| 2006    | 4        | 1.78%   |
| 2004    | 2        | 0.89%   |
| 2022    | 1        | 0.44%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 225      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 222      | 98.67%  |
| Yes  | 3        | 1.33%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 53       | 23.35%  |
| 8.01-16.0   | 48       | 21.15%  |
| 16.01-24.0  | 43       | 18.94%  |
| 32.01-64.0  | 23       | 10.13%  |
| 2.01-3.0    | 23       | 10.13%  |
| 3.01-4.0    | 12       | 5.29%   |
| 64.01-256.0 | 8        | 3.52%   |
| 0.51-1.0    | 8        | 3.52%   |
| 24.01-32.0  | 3        | 1.32%   |
| 1.01-2.0    | 3        | 1.32%   |
| 0.01-0.5    | 3        | 1.32%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 116      | 50%     |
| 0.51-1.0   | 52       | 22.41%  |
| 1.01-2.0   | 24       | 10.34%  |
| 3.01-4.0   | 9        | 3.88%   |
| Unknown    | 9        | 3.88%   |
| 8.01-16.0  | 7        | 3.02%   |
| 4.01-8.0   | 4        | 1.72%   |
| 0          | 4        | 1.72%   |
| 2.01-3.0   | 3        | 1.29%   |
| 24.01-32.0 | 2        | 0.86%   |
| 16.01-24.0 | 2        | 0.86%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 97       | 41.45%  |
| 2      | 54       | 23.08%  |
| 3      | 27       | 11.54%  |
| 4      | 21       | 8.97%   |
| 0      | 16       | 6.84%   |
| 5      | 9        | 3.85%   |
| 7      | 4        | 1.71%   |
| 6      | 4        | 1.71%   |
| 9      | 1        | 0.43%   |
| 8      | 1        | 0.43%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 189      | 82.53%  |
| Yes       | 40       | 17.47%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 208      | 92.44%  |
| No        | 17       | 7.56%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 178      | 79.11%  |
| Yes       | 47       | 20.89%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 200      | 88.89%  |
| Yes       | 25       | 11.11%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Russia  | 225      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                       | Desktops | Percent |
|----------------------------|----------|---------|
| Moscow                     | 74       | 31.49%  |
| St Petersburg              | 18       | 7.66%   |
| Yekaterinburg              | 10       | 4.26%   |
| Ozersk                     | 8        | 3.4%    |
| Novosibirsk                | 8        | 3.4%    |
| Krasnodar                  | 7        | 2.98%   |
| Barnaul                    | 7        | 2.98%   |
| Vladivostok                | 6        | 2.55%   |
| Chelyabinsk                | 5        | 2.13%   |
| Surgut                     | 4        | 1.7%    |
| Omsk                       | 4        | 1.7%    |
| Kamensk-Ural'skiy          | 4        | 1.7%    |
| Voronezh                   | 3        | 1.28%   |
| Ufa                        | 3        | 1.28%   |
| Podolsk                    | 3        | 1.28%   |
| Krasnoyarsk                | 3        | 1.28%   |
| Khimki                     | 3        | 1.28%   |
| Irkutsk                    | 3        | 1.28%   |
| Volzhskiy                  | 2        | 0.85%   |
| Volgograd                  | 2        | 0.85%   |
| Ulyanovsk                  | 2        | 0.85%   |
| Tambov                     | 2        | 0.85%   |
| Saratov                    | 2        | 0.85%   |
| Perm                       | 2        | 0.85%   |
| Orsk                       | 2        | 0.85%   |
| Obninsk                    | 2        | 0.85%   |
| Nizhniy Novgorod           | 2        | 0.85%   |
| Lipetsk                    | 2        | 0.85%   |
| Izhevsk                    | 2        | 0.85%   |
| Armavir                    | 2        | 0.85%   |
| Zhukovskiy                 | 1        | 0.43%   |
| Yegor'yevsk                | 1        | 0.43%   |
| Vostochnoe Degunino        | 1        | 0.43%   |
| Voskresensk                | 1        | 0.43%   |
| Vladimir                   | 1        | 0.43%   |
| Vidnoye                    | 1        | 0.43%   |
| Ust'-Charyshskaya Pristan' | 1        | 0.43%   |
| Ulan-Ude                   | 1        | 0.43%   |
| Tomsk                      | 1        | 0.43%   |
| Taganrog                   | 1        | 0.43%   |
| Stavropol                  | 1        | 0.43%   |
| Smolenshchina              | 1        | 0.43%   |
| Sevastopol                 | 1        | 0.43%   |
| Sertolovo                  | 1        | 0.43%   |
| Ryazan                     | 1        | 0.43%   |
| Rubtsovsk                  | 1        | 0.43%   |
| Rostov-on-Don              | 1        | 0.43%   |
| Reutov                     | 1        | 0.43%   |
| Petergof                   | 1        | 0.43%   |
| Penza                      | 1        | 0.43%   |
| Orenburg                   | 1        | 0.43%   |
| Myski                      | 1        | 0.43%   |
| Murino                     | 1        | 0.43%   |
| Moscow Oblast              | 1        | 0.43%   |
| Lyubertsy                  | 1        | 0.43%   |
| Lesosibirsk                | 1        | 0.43%   |
| Kostroma                   | 1        | 0.43%   |
| Kommunar                   | 1        | 0.43%   |
| Kolomna                    | 1        | 0.43%   |
| Kiselëvsk                 | 1        | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor                             | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC                                | 70       | 129    | 21.02%  |
| Seagate                            | 66       | 140    | 19.82%  |
| Samsung Electronics                | 34       | 47     | 10.21%  |
| Toshiba                            | 22       | 38     | 6.61%   |
| Kingston                           | 20       | 22     | 6.01%   |
| Hitachi                            | 17       | 46     | 5.11%   |
| Crucial                            | 11       | 13     | 3.3%    |
| Intel                              | 10       | 15     | 3%      |
| A-DATA Technology                  | 7        | 11     | 2.1%    |
| Smartbuy                           | 5        | 5      | 1.5%    |
| PLEXTOR                            | 5        | 8      | 1.5%    |
| OCZ                                | 5        | 5      | 1.5%    |
| HGST                               | 5        | 13     | 1.5%    |
| SanDisk                            | 4        | 5      | 1.2%    |
| OPENBSD                            | 4        | 8      | 1.2%    |
| SPCC                               | 3        | 3      | 0.9%    |
| Silicon Motion                     | 3        | 3      | 0.9%    |
| MAXTOR                             | 3        | 3      | 0.9%    |
| KingSpec                           | 3        | 5      | 0.9%    |
| Apacer                             | 3        | 3      | 0.9%    |
| AMD                                | 3        | 4      | 0.9%    |
| XPG                                | 2        | 2      | 0.6%    |
| Verbatim                           | 2        | 2      | 0.6%    |
| Patriot                            | 2        | 2      | 0.6%    |
| Micron Technology                  | 2        | 4      | 0.6%    |
| Kston                              | 2        | 2      | 0.6%    |
| Hoodisk                            | 2        | 4      | 0.6%    |
| Fujitsu                            | 2        | 3      | 0.6%    |
| XUNZHE                             | 1        | 1      | 0.3%    |
| Transcend                          | 1        | 1      | 0.3%    |
| QUMO                               | 1        | 1      | 0.3%    |
| Product:              USB DISK 2.0 | 1        | 1      | 0.3%    |
| NVMe                               | 1        | 4      | 0.3%    |
| Netac                              | 1        | 1      | 0.3%    |
| MaxDigital                         | 1        | 1      | 0.3%    |
| LITEON                             | 1        | 1      | 0.3%    |
| KingDian                           | 1        | 3      | 0.3%    |
| IBM                                | 1        | 1      | 0.3%    |
| Hewlett-Packard                    | 1        | 4      | 0.3%    |
| GOODRAM                            | 1        | 1      | 0.3%    |
| GK                                 | 1        | 1      | 0.3%    |
| Gigabyte Technology                | 1        | 1      | 0.3%    |
| China                              | 1        | 1      | 0.3%    |
| AEGO                               | 1        | 1      | 0.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB             | 6        | 1.53%   |
| WDC WDS240G2G0A-00JH30 240GB       | 5        | 1.27%   |
| Seagate ST3300657SS 304GB          | 4        | 1.02%   |
| Seagate ST250DM000-1BD141 250GB    | 4        | 1.02%   |
| Samsung SSD 970 EVO Plus 250GB     | 4        | 1.02%   |
| OPENBSD SR RAID 1 752GB            | 4        | 1.02%   |
| Kingston SA400S37240G 240GB        | 4        | 1.02%   |
| WDC WD6400AARS-00Y5B1 640GB        | 3        | 0.76%   |
| WDC WD20EARX-00PASB0 2TB           | 3        | 0.76%   |
| WDC WD1002FAEX-00Y9A0 1TB          | 3        | 0.76%   |
| Toshiba DT01ACA050 500GB           | 3        | 0.76%   |
| Seagate ST380815AS 80GB            | 3        | 0.76%   |
| Seagate ST3500413AS 500GB          | 3        | 0.76%   |
| Seagate ST3250318AS 250GB          | 3        | 0.76%   |
| Seagate ST2000DM001-1CH164 2TB     | 3        | 0.76%   |
| Seagate ST1000DM010-2EP102 1TB     | 3        | 0.76%   |
| Samsung SSD 860 EVO 500GB          | 3        | 0.76%   |
| A-DATA SU650 120GB                 | 3        | 0.76%   |
| WDC WDS500G1B0A-00H9H0 500GB       | 2        | 0.51%   |
| WDC WD5003AZEX-00K1GA0 500GB       | 2        | 0.51%   |
| WDC WD5000LPLX-00ZNTT0 500GB       | 2        | 0.51%   |
| WDC WD40EFRX-68N32N0 4TB           | 2        | 0.51%   |
| WDC WD20EZRZ-00Z5HB0 2TB           | 2        | 0.51%   |
| WDC WD2000JS-55MHB0 192GB          | 2        | 0.51%   |
| WDC WD15EADS-00P8B0 1.5TB          | 2        | 0.51%   |
| WDC WD10EZRX-00A8LB0 1TB           | 2        | 0.51%   |
| WDC WD10EZEX-21M2NA0 1TB           | 2        | 0.51%   |
| WDC WD10EALX-009BA0 1TB            | 2        | 0.51%   |
| Verbatim Vi550 S3 SSD 512GB        | 2        | 0.51%   |
| Toshiba MG04ACA600E 6TB            | 2        | 0.51%   |
| Toshiba HDWD130 3TB                | 2        | 0.51%   |
| Smartbuy SSD 60GB                  | 2        | 0.51%   |
| Silicon Motion NE-256 256GB        | 2        | 0.51%   |
| Seagate ST500DM002-1BD142 500GB    | 2        | 0.51%   |
| Seagate ST380011A 80GB             | 2        | 0.51%   |
| Seagate ST3320418AS 320GB          | 2        | 0.51%   |
| Seagate ST3250410AS 250GB          | 2        | 0.51%   |
| Seagate ST3160813AS 160GB          | 2        | 0.51%   |
| Seagate ST2000DM008-2FR102 2TB     | 2        | 0.51%   |
| Seagate ST1000VX000-1CU162 1TB     | 2        | 0.51%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2        | 0.51%   |
| Samsung SSD 970 EVO 1TB            | 2        | 0.51%   |
| Samsung SSD 870 EVO 1TB            | 2        | 0.51%   |
| Samsung SSD 840 PRO Series 256GB   | 2        | 0.51%   |
| Samsung HD161HJ 160GB              | 2        | 0.51%   |
| OCZ VERTEX3 64GB                   | 2        | 0.51%   |
| Micron 5100_MTFDDAK240TCB 240GB    | 2        | 0.51%   |
| MAXTOR STM3320613AS 320GB          | 2        | 0.51%   |
| Kston SSD 128GB                    | 2        | 0.51%   |
| Kingston SA400S37120G 120GB        | 2        | 0.51%   |
| Kingston SA2000M8500G 500GB        | 2        | 0.51%   |
| Kingston DataTraveler 3.0 32GB     | 2        | 0.51%   |
| KingSpec NT-512 512GB              | 2        | 0.51%   |
| Intel SSDSC2BB080G4 80GB           | 2        | 0.51%   |
| Intel SSDPEKNW020T8 2TB            | 2        | 0.51%   |
| Hitachi HUA722020ALA330 2TB        | 2        | 0.51%   |
| Hitachi HDT725025VLA380 250GB      | 2        | 0.51%   |
| Hitachi HDS721010CLA332 1TB        | 2        | 0.51%   |
| Fujitsu MHT2080BH 80GB             | 2        | 0.51%   |
| Crucial M4-CT064M4SSD2 64GB        | 2        | 0.51%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                             | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| Seagate                            | 66       | 140    | 34.74%  |
| WDC                                | 60       | 115    | 31.58%  |
| Toshiba                            | 21       | 37     | 11.05%  |
| Hitachi                            | 17       | 46     | 8.95%   |
| Samsung Electronics                | 7        | 10     | 3.68%   |
| HGST                               | 5        | 13     | 2.63%   |
| OPENBSD                            | 4        | 8      | 2.11%   |
| MAXTOR                             | 3        | 3      | 1.58%   |
| Fujitsu                            | 2        | 3      | 1.05%   |
| Product:              USB DISK 2.0 | 1        | 1      | 0.53%   |
| NVMe                               | 1        | 4      | 0.53%   |
| MaxDigital                         | 1        | 1      | 0.53%   |
| IBM                                | 1        | 1      | 0.53%   |
| Hewlett-Packard                    | 1        | 4      | 0.53%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 18       | 21     | 14.63%  |
| Kingston            | 17       | 19     | 13.82%  |
| Crucial             | 11       | 13     | 8.94%   |
| WDC                 | 10       | 10     | 8.13%   |
| Intel               | 7        | 10     | 5.69%   |
| A-DATA Technology   | 7        | 10     | 5.69%   |
| Smartbuy            | 5        | 5      | 4.07%   |
| PLEXTOR             | 5        | 8      | 4.07%   |
| OCZ                 | 5        | 5      | 4.07%   |
| SanDisk             | 4        | 5      | 3.25%   |
| KingSpec            | 3        | 5      | 2.44%   |
| Apacer              | 3        | 3      | 2.44%   |
| AMD                 | 3        | 4      | 2.44%   |
| Verbatim            | 2        | 2      | 1.63%   |
| SPCC                | 2        | 2      | 1.63%   |
| Patriot             | 2        | 2      | 1.63%   |
| Micron Technology   | 2        | 4      | 1.63%   |
| Kston               | 2        | 2      | 1.63%   |
| Hoodisk             | 2        | 4      | 1.63%   |
| XUNZHE              | 1        | 1      | 0.81%   |
| XPG                 | 1        | 1      | 0.81%   |
| Transcend           | 1        | 1      | 0.81%   |
| Toshiba             | 1        | 1      | 0.81%   |
| QUMO                | 1        | 1      | 0.81%   |
| Netac               | 1        | 1      | 0.81%   |
| LITEON              | 1        | 1      | 0.81%   |
| KingDian            | 1        | 3      | 0.81%   |
| GOODRAM             | 1        | 1      | 0.81%   |
| GK                  | 1        | 1      | 0.81%   |
| Gigabyte Technology | 1        | 1      | 0.81%   |
| China               | 1        | 1      | 0.81%   |
| AEGO                | 1        | 1      | 0.81%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 142      | 386    | 52.01%  |
| SSD  | 107      | 149    | 39.19%  |
| NVMe | 24       | 34     | 8.79%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 204      | 535    | 89.47%  |
| NVMe | 24       | 34     | 10.53%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 174      | 284    | 61.27%  |
| 0.51-1.0   | 62       | 107    | 21.83%  |
| 1.01-2.0   | 22       | 85     | 7.75%   |
| 3.01-4.0   | 11       | 23     | 3.87%   |
| 4.01-10.0  | 9        | 18     | 3.17%   |
| 2.01-3.0   | 6        | 18     | 2.11%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 65       | 27.9%   |
| 1-20           | 50       | 21.46%  |
| 251-500        | 34       | 14.59%  |
| 51-100         | 33       | 14.16%  |
| 21-50          | 16       | 6.87%   |
| 501-1000       | 14       | 6.01%   |
| More than 3000 | 8        | 3.43%   |
| 1001-2000      | 8        | 3.43%   |
| Unknown        | 3        | 1.29%   |
| 2001-3000      | 2        | 0.86%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 179      | 76.82%  |
| 21-50          | 24       | 10.3%   |
| 101-250        | 7        | 3%      |
| 51-100         | 6        | 2.58%   |
| 501-1000       | 5        | 2.15%   |
| More than 3000 | 3        | 1.29%   |
| 2001-3000      | 3        | 1.29%   |
| 1001-2000      | 3        | 1.29%   |
| Unknown        | 3        | 1.29%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Desktops | Drives | Percent |
|----------------------------------------------|----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB                 | 2        | 2      | 3.13%   |
| WDC WD1002FAEX-00Y9A0 1TB                    | 2        | 2      | 3.13%   |
| Seagate ST3500413AS 500GB                    | 2        | 4      | 3.13%   |
| Seagate ST3320418AS 320GB                    | 2        | 2      | 3.13%   |
| Samsung Electronics SSD 870 EVO 1TB          | 2        | 4      | 3.13%   |
| MAXTOR STM3320613AS 320GB                    | 2        | 2      | 3.13%   |
| Hitachi HDS721010CLA332 1TB                  | 2        | 4      | 3.13%   |
| XPG SX950U 240GB                             | 1        | 1      | 1.56%   |
| WDC WD7501AALS-00E8B0 752GB                  | 1        | 1      | 1.56%   |
| WDC WD60EFRX-68MYMN1 6TB                     | 1        | 1      | 1.56%   |
| WDC WD5003AZEX-00MK2A0 500GB                 | 1        | 1      | 1.56%   |
| WDC WD5000LPLX-00ZNTT0 500GB                 | 1        | 1      | 1.56%   |
| WDC WD5000AZRZ-00HTKB0 500GB                 | 1        | 1      | 1.56%   |
| WDC WD5000AZLX-00CL5A0 500GB                 | 1        | 1      | 1.56%   |
| WDC WD5000AAKS-00V1A0 500GB                  | 1        | 1      | 1.56%   |
| WDC WD40EFRX-68N32N0 4TB                     | 1        | 3      | 1.56%   |
| WDC WD3200BPVT-22JJ5T0 320GB                 | 1        | 1      | 1.56%   |
| WDC WD3200BEVT-00A0RT0 233GB                 | 1        | 1      | 1.56%   |
| WDC WD20EURX-63T0FY0 2TB                     | 1        | 1      | 1.56%   |
| WDC WD20EFRX-68EUZN0 2TB                     | 1        | 2      | 1.56%   |
| WDC WD1600BEVT-22ZCT0 160GB                  | 1        | 1      | 1.56%   |
| WDC WD15EADS-00P8B0 1.5TB                    | 1        | 1      | 1.56%   |
| WDC WD1002FAEX-00Z3A0 1TB                    | 1        | 1      | 1.56%   |
| Toshiba HDWD105 500GB                        | 1        | 2      | 1.56%   |
| Toshiba DT01ACA050 500GB                     | 1        | 2      | 1.56%   |
| Seagate ST9120822AS 120GB                    | 1        | 1      | 1.56%   |
| Seagate ST3750640NS 752GB                    | 1        | 4      | 1.56%   |
| Seagate ST3500514NS 500GB                    | 1        | 1      | 1.56%   |
| Seagate ST3250410AS 250GB                    | 1        | 1      | 1.56%   |
| Seagate ST3250310AS 250GB                    | 1        | 1      | 1.56%   |
| Seagate ST320410A 20GB                       | 1        | 1      | 1.56%   |
| Seagate ST3160812A 160GB                     | 1        | 2      | 1.56%   |
| Seagate ST3120814A 120GB                     | 1        | 1      | 1.56%   |
| Seagate ST3120211AS 120GB                    | 1        | 1      | 1.56%   |
| Seagate ST250DM000-1BD141 250GB              | 1        | 2      | 1.56%   |
| Seagate ST2000DM006-2DM164 2TB               | 1        | 1      | 1.56%   |
| Seagate ST2000DM001-1CH164 2TB               | 1        | 1      | 1.56%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1        | 1      | 1.56%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1        | 1      | 1.56%   |
| Samsung Electronics SP2004C 200GB            | 1        | 1      | 1.56%   |
| Samsung Electronics HD501LJ 500GB            | 1        | 2      | 1.56%   |
| Samsung Electronics HD161HJ 160GB            | 1        | 1      | 1.56%   |
| Samsung Electronics HD082GJ 80GB             | 1        | 1      | 1.56%   |
| PLEXTOR PX-128M5S 128GB                      | 1        | 1      | 1.56%   |
| MAXTOR STM3160815AS 160GB                    | 1        | 1      | 1.56%   |
| Kingston SNV425S2128GB                       | 1        | 1      | 1.56%   |
| Kingston SMS200S3120G 120GB                  | 1        | 1      | 1.56%   |
| Kingston SA400S37120G 120GB                  | 1        | 1      | 1.56%   |
| Intel SSDSC2BW480A4 480GB                    | 1        | 1      | 1.56%   |
| Intel SSDSC2BB080G4 80GB                     | 1        | 1      | 1.56%   |
| Intel SSDSA2M080G2GC 80GB                    | 1        | 1      | 1.56%   |
| Hitachi HTS547550A9E384 500GB                | 1        | 1      | 1.56%   |
| Hitachi HTS543232A7A384 320GB                | 1        | 1      | 1.56%   |
| Hitachi HDS721010CLA630 1TB                  | 1        | 1      | 1.56%   |
| GK SM2244LTAB ,TC58TEG6DDKTA00 8GB           | 1        | 1      | 1.56%   |
| AMD R5SL240G 240GB                           | 1        | 2      | 1.56%   |
| A-DATA Technology XM13 32GB                  | 1        | 1      | 1.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 17       | 22     | 27.42%  |
| Seagate             | 17       | 24     | 27.42%  |
| Samsung Electronics | 7        | 10     | 11.29%  |
| Hitachi             | 5        | 7      | 8.06%   |
| MAXTOR              | 3        | 3      | 4.84%   |
| Kingston            | 3        | 3      | 4.84%   |
| Intel               | 3        | 3      | 4.84%   |
| Toshiba             | 2        | 4      | 3.23%   |
| XPG                 | 1        | 1      | 1.61%   |
| PLEXTOR             | 1        | 1      | 1.61%   |
| GK                  | 1        | 1      | 1.61%   |
| AMD                 | 1        | 2      | 1.61%   |
| A-DATA Technology   | 1        | 1      | 1.61%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 17       | 24     | 36.96%  |
| WDC                 | 15       | 20     | 32.61%  |
| Hitachi             | 5        | 7      | 10.87%  |
| Samsung Electronics | 4        | 5      | 8.7%    |
| MAXTOR              | 3        | 3      | 6.52%   |
| Toshiba             | 2        | 4      | 4.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 45       | 63     | 75%     |
| SSD  | 15       | 19     | 25%     |

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
| Works    | 178      | 450    | 70.08%  |
| Malfunc  | 58       | 82     | 22.83%  |
| Detected | 16       | 34     | 6.3%    |
| Failed   | 2        | 3      | 0.79%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 157      | 54.51%  |
| AMD                              | 43       | 14.93%  |
| Samsung Electronics              | 14       | 4.86%   |
| Marvell Technology Group         | 11       | 3.82%   |
| ASMedia Technology               | 10       | 3.47%   |
| Nvidia                           | 9        | 3.13%   |
| JMicron Technology               | 9        | 3.13%   |
| Silicon Motion                   | 6        | 2.08%   |
| Broadcom / LSI                   | 5        | 1.74%   |
| Areca Technology                 | 4        | 1.39%   |
| Sandisk                          | 3        | 1.04%   |
| Kingston Technology Company      | 3        | 1.04%   |
| Toshiba                          | 2        | 0.69%   |
| Silicon Image                    | 2        | 0.69%   |
| ADATA Technology                 | 2        | 0.69%   |
| VIA Technologies                 | 1        | 0.35%   |
| Silicon Integrated Systems [SiS] | 1        | 0.35%   |
| Realtek Semiconductor            | 1        | 0.35%   |
| Phison Electronics               | 1        | 0.35%   |
| Lite-On Technology               | 1        | 0.35%   |
| Lite-On IT Corp. / Plextor       | 1        | 0.35%   |
| Integrated Technology Express    | 1        | 0.35%   |
| 3ware                            | 1        | 0.35%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 26       | 7.37%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 13       | 3.68%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 12       | 3.4%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 12       | 3.4%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 11       | 3.12%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 10       | 2.83%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 10       | 2.83%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 10       | 2.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 9        | 2.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 8        | 2.27%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 8        | 2.27%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 8        | 2.27%   |
| AMD 400 Series Chipset SATA Controller                                                  | 8        | 2.27%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 7        | 1.98%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 7        | 1.98%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 6        | 1.7%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 6        | 1.7%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 6        | 1.7%    |
| Nvidia MCP61 SATA Controller                                                            | 5        | 1.42%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 5        | 1.42%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5        | 1.42%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4        | 1.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 4        | 1.13%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 4        | 1.13%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 4        | 1.13%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 4        | 1.13%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 4        | 1.13%   |
| Intel 82801EB (ICH5) SATA Controller                                                    | 4        | 1.13%   |
| Areca ARC-1300ix-16 16-Port PCI-Express to SAS Non-RAID Host Adapter                    | 4        | 1.13%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 3        | 0.85%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3        | 0.85%   |
| Nvidia MCP61 IDE                                                                        | 3        | 0.85%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 3        | 0.85%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 3        | 0.85%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 3        | 0.85%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3        | 0.85%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 3        | 0.85%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 0.85%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 3        | 0.85%   |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                            | 3        | 0.85%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 0.85%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 0.85%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3        | 0.85%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                        | 2        | 0.57%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 0.57%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 2        | 0.57%   |
| Kingston Company A2000 NVMe SSD                                                         | 2        | 0.57%   |
| JMicron JMB361 AHCI/IDE                                                                 | 2        | 0.57%   |
| Intel SSD 660P Series                                                                   | 2        | 0.57%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2        | 0.57%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                           | 2        | 0.57%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                            | 2        | 0.57%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2        | 0.57%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 2        | 0.57%   |
| Intel 82801FR/FRW (ICH6R/ICH6RW) SATA Controller                                        | 2        | 0.57%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                                | 2        | 0.57%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 0.57%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 0.57%   |
| Broadcom / LSI SAS3008 PCI-Express Fusion-MPT SAS-3                                     | 2        | 0.57%   |
| AMD X370 Series Chipset SATA Controller                                                 | 2        | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 164      | 59.21%  |
| IDE  | 64       | 23.1%   |
| NVMe | 36       | 13%     |
| RAID | 6        | 2.17%   |
| SCSI | 4        | 1.44%   |
| SAS  | 3        | 1.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 161      | 70.93%  |
| AMD     | 51       | 22.47%  |
| ARM     | 10       | 4.41%   |
| Unknown | 4        | 1.76%   |
| PowerPC | 1        | 0.44%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 5        | 2.16%   |
| Intel 686-class                             | 4        | 1.73%   |
| ARM Cortex-A57 r1p3                         | 4        | 1.73%   |
|                                             | 4        | 1.73%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 3        | 1.3%    |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 1.3%    |
| Intel Celeron CPU J3455 @ 1.50GHz           | 3        | 1.3%    |
| Intel Celeron CPU 1037U @ 1.80GHz           | 3        | 1.3%    |
| ARM Cortex-A72 r0p2                         | 3        | 1.3%    |
| AMD Ryzen 5 2600 Six-Core Processor         | 3        | 1.3%    |
| AMD GX-412TC SOC                            | 3        | 1.3%    |
| Intel Xeon CPU E3-1265L V2 @ 2.50GHz        | 2        | 0.87%   |
| Intel Xeon Bronze 3104 CPU @ 1.70GHz        | 2        | 0.87%   |
| Intel Pentium Gold G5400T CPU @ 3.10GHz     | 2        | 0.87%   |
| Intel Pentium CPU J4205 @ 1.50GHz           | 2        | 0.87%   |
| Intel Pentium 4 CPU                         | 2        | 0.87%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2        | 0.87%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 0.87%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 2        | 0.87%   |
| Intel Core i7 CPU                           | 2        | 0.87%   |
| Intel Core i5-8350U CPU @ 1.70GHz           | 2        | 0.87%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 0.87%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 2        | 0.87%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 2        | 0.87%   |
| Intel Core i3-4170 CPU @ 3.70GHz            | 2        | 0.87%   |
| Intel Core 2 Quad CPU                       | 2        | 0.87%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 2        | 0.87%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz        | 2        | 0.87%   |
| Intel Core 2 Duo CPU E7200 @ 2.53GHz        | 2        | 0.87%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 2        | 0.87%   |
| Intel Celeron CPU J3060 @ 1.60GHz           | 2        | 0.87%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 2        | 0.87%   |
| Intel Celeron CPU J1800 @ 2.41GHz           | 2        | 0.87%   |
| Intel Atom CPU D525 @ 1.80GHz               | 2        | 0.87%   |
| Intel 11th Gen Core i5-11600K @ 3.90GHz     | 2        | 0.87%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 2        | 0.87%   |
| AMD Ryzen 7 3800XT 8-Core Processor         | 2        | 0.87%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 2        | 0.87%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2        | 0.87%   |
| AMD Athlon II X3 455 Processor              | 2        | 0.87%   |
| PowerPC 7447A (Revision 0x101)              | 1        | 0.43%   |
| Intel Xeon CPU X5460 @ 3.16GHz              | 1        | 0.43%   |
| Intel Xeon CPU X3470 @ 2.93GHz              | 1        | 0.43%   |
| Intel Xeon CPU X3440 @ 2.53GHz              | 1        | 0.43%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 1        | 0.43%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz         | 1        | 0.43%   |
| Intel Xeon CPU E5-2660 v4 @ 2.00GHz         | 1        | 0.43%   |
| Intel Xeon CPU E5-2650 v4 @ 2.20GHz         | 1        | 0.43%   |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz          | 1        | 0.43%   |
| Intel Xeon CPU E5-2630L 0 @ 2.00GHz         | 1        | 0.43%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz         | 1        | 0.43%   |
| Intel Xeon CPU E5-2407 0 @ 2.20GHz          | 1        | 0.43%   |
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz         | 1        | 0.43%   |
| Intel Xeon CPU E3-1270 v3 @ 3.50GHz         | 1        | 0.43%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz         | 1        | 0.43%   |
| Intel Pentium Silver N6000 @ 1.10GHz        | 1        | 0.43%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz    | 1        | 0.43%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 1        | 0.43%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 1        | 0.43%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Celeron           | 26       | 11.35%  |
| Intel Core i5           | 24       | 10.48%  |
| Intel Core i7           | 17       | 7.42%   |
| Intel Xeon              | 16       | 6.99%   |
| Intel Core i3           | 13       | 5.68%   |
| AMD Ryzen 5             | 12       | 5.24%   |
| ARM Cortex              | 10       | 4.37%   |
| Intel Core 2 Quad       | 9        | 3.93%   |
| Intel Core 2 Duo        | 9        | 3.93%   |
| Intel Atom              | 8        | 3.49%   |
| Other                   | 7        | 3.06%   |
| Intel Pentium 4         | 7        | 3.06%   |
| Intel Pentium           | 6        | 2.62%   |
| AMD Ryzen 7             | 6        | 2.62%   |
| Intel 686-class         | 4        | 1.75%   |
| Intel Pentium Gold      | 3        | 1.31%   |
| Intel Pentium Dual      | 3        | 1.31%   |
| Intel Pentium D         | 3        | 1.31%   |
| Intel Core 2            | 3        | 1.31%   |
| AMD GX                  | 3        | 1.31%   |
| AMD FX                  | 3        | 1.31%   |
| AMD Athlon 64 X2        | 3        | 1.31%   |
| Intel Xeon Bronze       | 2        | 0.87%   |
| Intel Pentium Silver    | 2        | 0.87%   |
| Intel Pentium Dual-Core | 2        | 0.87%   |
| Intel Core i9           | 2        | 0.87%   |
| AMD Turion II Neo       | 2        | 0.87%   |
| AMD Ryzen 9             | 2        | 0.87%   |
| AMD Phenom II X6        | 2        | 0.87%   |
| AMD Phenom              | 2        | 0.87%   |
| AMD Athlon X4           | 2        | 0.87%   |
| AMD Athlon II X3        | 2        | 0.87%   |
| Intel Genuine           | 1        | 0.44%   |
| Intel Celeron D         | 1        | 0.44%   |
| AMD Sempron             | 1        | 0.44%   |
| AMD Ryzen 3 PRO         | 1        | 0.44%   |
| AMD Ryzen 3             | 1        | 0.44%   |
| AMD Phenom II X4        | 1        | 0.44%   |
| AMD Phenom II X2        | 1        | 0.44%   |
| AMD E2                  | 1        | 0.44%   |
| AMD E                   | 1        | 0.44%   |
| AMD C-70                | 1        | 0.44%   |
| AMD Athlon II X4        | 1        | 0.44%   |
| AMD A4                  | 1        | 0.44%   |
| AMD A10                 | 1        | 0.44%   |
| AMD 686-class           | 1        | 0.44%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 69       | 30.26%  |
| 2       | 55       | 24.12%  |
| Unknown | 41       | 17.98%  |
| 6       | 22       | 9.65%   |
| 1       | 11       | 4.82%   |
| 8       | 9        | 3.95%   |
| 12      | 8        | 3.51%   |
| 16      | 5        | 2.19%   |
| 24      | 3        | 1.32%   |
| 28      | 2        | 0.88%   |
| 3       | 2        | 0.88%   |
| 14      | 1        | 0.44%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 200      | 86.96%  |
| Unknown | 24       | 10.43%  |
| 2       | 6        | 2.61%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 119      | 52.19%  |
| 2       | 59       | 25.88%  |
| Unknown | 50       | 21.93%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Unknown       | 21       | 9.29%   |
| IvyBridge     | 18       | 7.96%   |
| Penryn        | 17       | 7.52%   |
| KabyLake      | 16       | 7.08%   |
| Haswell       | 16       | 7.08%   |
| SandyBridge   | 15       | 6.64%   |
| Skylake       | 12       | 5.31%   |
| Zen 2         | 11       | 4.87%   |
| NetBurst      | 11       | 4.87%   |
| K10           | 11       | 4.87%   |
| Core          | 11       | 4.87%   |
| Silvermont    | 8        | 3.54%   |
| Goldmont      | 8        | 3.54%   |
| Bonnell       | 7        | 3.1%    |
| Zen           | 6        | 2.65%   |
| Piledriver    | 5        | 2.21%   |
| Nehalem       | 5        | 2.21%   |
| Zen+          | 4        | 1.77%   |
| K8 Hammer     | 4        | 1.77%   |
| Puma          | 3        | 1.33%   |
| Goldmont plus | 3        | 1.33%   |
| CometLake     | 3        | 1.33%   |
| Broadwell     | 3        | 1.33%   |
| Bobcat        | 2        | 0.88%   |
| Zen 3         | 1        | 0.44%   |
| Westmere      | 1        | 0.44%   |
| Steamroller   | 1        | 0.44%   |
| P6            | 1        | 0.44%   |
| Jaguar        | 1        | 0.44%   |
| Bulldozer     | 1        | 0.44%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 94       | 43.52%  |
| Nvidia                     | 70       | 32.41%  |
| AMD                        | 43       | 19.91%  |
| ASPEED Technology          | 6        | 2.78%   |
| Matrox Electronics Systems | 2        | 0.93%   |
| VIA Technologies           | 1        | 0.46%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 8        | 3.59%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 7        | 3.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6        | 2.69%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 6        | 2.69%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 6        | 2.69%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5        | 2.24%   |
| Intel HD Graphics 530                                                                    | 5        | 2.24%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5        | 2.24%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5        | 2.24%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5        | 2.24%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 4        | 1.79%   |
| Intel HD Graphics 500                                                                    | 4        | 1.79%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 4        | 1.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4        | 1.79%   |
| Intel 82865G Integrated Graphics Controller                                              | 4        | 1.79%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4        | 1.79%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 3        | 1.35%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 3        | 1.35%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                                      | 3        | 1.35%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 3        | 1.35%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 3        | 1.35%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3        | 1.35%   |
| AMD RV710/M92 [Mobility Radeon HD 4350/4550]                                             | 3        | 1.35%   |
| AMD ES1000                                                                               | 3        | 1.35%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 2        | 0.9%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 2        | 0.9%    |
| Nvidia NV43 [GeForce 6600]                                                               | 2        | 0.9%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2        | 0.9%    |
| Nvidia GK107 [GeForce GT 640]                                                            | 2        | 0.9%    |
| Nvidia GF119 [GeForce GT 520]                                                            | 2        | 0.9%    |
| Nvidia GA102 [GeForce RTX 3080]                                                          | 2        | 0.9%    |
| Nvidia G96C [GeForce 9500 GT]                                                            | 2        | 0.9%    |
| Nvidia G86 [GeForce 8500 GT]                                                             | 2        | 0.9%    |
| Nvidia G73 [GeForce 7600 GS]                                                             | 2        | 0.9%    |
| Intel UHD Graphics 620                                                                   | 2        | 0.9%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2        | 0.9%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2        | 0.9%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2        | 0.9%    |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 2        | 0.9%    |
| Intel 82Q963/Q965 Integrated Graphics Controller                                         | 2        | 0.9%    |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 2        | 0.9%    |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 2        | 0.9%    |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                                           | 2        | 0.9%    |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 2        | 0.9%    |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1        | 0.45%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1        | 0.45%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 1        | 0.45%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1        | 0.45%   |
| Nvidia NV18 [GeForce4 MX 4000]                                                           | 1        | 0.45%   |
| Nvidia GT218 [ION]                                                                       | 1        | 0.45%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1        | 0.45%   |
| Nvidia GT218 [GeForce 210]                                                               | 1        | 0.45%   |
| Nvidia GT215 [GeForce GT 220]                                                            | 1        | 0.45%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1        | 0.45%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1        | 0.45%   |
| Nvidia GP104 [GeForce GTX 1060 3GB]                                                      | 1        | 0.45%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 1        | 0.45%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1        | 0.45%   |
| Nvidia GM206 [GeForce GTX 950]                                                           | 1        | 0.45%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1        | 0.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 83       | 36.56%  |
| 1 x Nvidia     | 67       | 29.52%  |
| 1 x AMD        | 34       | 14.98%  |
| Other          | 17       | 7.49%   |
| 1 x ASPEED     | 6        | 2.64%   |
| 2 x Intel      | 5        | 2.2%    |
| 2 x AMD        | 5        | 2.2%    |
| Intel + AMD    | 4        | 1.76%   |
| 1 x Matrox     | 2        | 0.88%   |
| Intel + Nvidia | 2        | 0.88%   |
| 1 x VIA        | 1        | 0.44%   |
| AMD + Nvidia   | 1        | 0.44%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 163      | 71.81%  |
| Proprietary | 42       | 18.5%   |
| Unknown     | 22       | 9.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 165      | 72.69%  |
| 1.01-2.0   | 17       | 7.49%   |
| 0.51-1.0   | 13       | 5.73%   |
| 3.01-4.0   | 10       | 4.41%   |
| 0.01-0.5   | 7        | 3.08%   |
| 7.01-8.0   | 6        | 2.64%   |
| 5.01-6.0   | 5        | 2.2%    |
| 8.01-16.0  | 3        | 1.32%   |
| 2.01-3.0   | 1        | 0.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 23       | 21.5%   |
| Goldstar             | 17       | 15.89%  |
| Dell                 | 12       | 11.21%  |
| ViewSonic            | 9        | 8.41%   |
| Ancor Communications | 9        | 8.41%   |
| Philips              | 7        | 6.54%   |
| AOC                  | 5        | 4.67%   |
| Acer                 | 5        | 4.67%   |
| NEC Computers        | 4        | 3.74%   |
| BenQ                 | 4        | 3.74%   |
| Sony                 | 3        | 2.8%    |
| RTK                  | 2        | 1.87%   |
| Unknown (CDD)        | 1        | 0.93%   |
| Lenovo               | 1        | 0.93%   |
| InfoVision           | 1        | 0.93%   |
| Iiyama               | 1        | 0.93%   |
| Hewlett-Packard      | 1        | 0.93%   |
| Fujitsu Siemens      | 1        | 0.93%   |
| BOE                  | 1        | 0.93%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Ancor Communications ASUS VW199 ACI19ED 1440x900 410x260mm 19.1-inch   | 4        | 3.54%   |
| ViewSonic LCD Monitor VSCD22B 1920x1080 520x290mm 23.4-inch            | 2        | 1.77%   |
| ViewSonic LCD Monitor VSCC42B 1920x1080 480x270mm 21.7-inch            | 2        | 1.77%   |
| Samsung Electronics SyncMaster SAM027D 1680x1050 430x270mm 20.0-inch   | 2        | 1.77%   |
| Samsung Electronics SMBX2250 SAM071B 1920x1080 480x270mm 21.7-inch     | 2        | 1.77%   |
| Samsung Electronics LCD Monitor SAM0AC6 1920x1080 1110x620mm 50.1-inch | 2        | 1.77%   |
| RTK WCS Display RTK1A1B 1920x1080 344x195mm 15.6-inch                  | 2        | 1.77%   |
| NEC Computers FE791SB NEC61D7 1600x1200 330x240mm 16.1-inch            | 2        | 1.77%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch             | 2        | 1.77%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch              | 2        | 1.77%   |
| Goldstar LCD Monitor GSM5AB6 1920x1080 480x270mm 21.7-inch             | 2        | 1.77%   |
| ViewSonic VX2458-mhd VSC0437 1920x1080 520x290mm 23.4-inch             | 1        | 0.88%   |
| ViewSonic VP171s-2 VSC4B1B 1280x1024 340x270mm 17.1-inch               | 1        | 0.88%   |
| ViewSonic LCD Monitor VX2451 SERIES 1920x1080                          | 1        | 0.88%   |
| ViewSonic LCD Monitor VSC8724 1440x900 410x260mm 19.1-inch             | 1        | 0.88%   |
| ViewSonic LCD Monitor VSC5826 1366x768 410x230mm 18.5-inch             | 1        | 0.88%   |
| ViewSonic LCD Monitor VSC2528 1920x1080 520x290mm 23.4-inch            | 1        | 0.88%   |
| Unknown (CDD) VGA CDD0030 1920x1080 1150x650mm 52.0-inch               | 1        | 0.88%   |
| Sony TV  *00 SNY8204 3840x2160 1220x680mm 55.0-inch                    | 1        | 0.88%   |
| Sony TV  *00 SNY7C04 3840x2160 1080x610mm 48.8-inch                    | 1        | 0.88%   |
| Sony SDM-S75D/F/N SNY3800 1280x1024 340x270mm 17.1-inch                | 1        | 0.88%   |
| Samsung Electronics U32H85x SAM0E3C 3840x2160 700x390mm 31.5-inch      | 1        | 0.88%   |
| Samsung Electronics SyncMaster SAM027E 1680x1050 470x300mm 22.0-inch   | 1        | 0.88%   |
| Samsung Electronics SyncMaster SAM026F 1280x1024 380x300mm 19.1-inch   | 1        | 0.88%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 430x270mm 20.0-inch   | 1        | 0.88%   |
| Samsung Electronics SyncMaster SAM01BB 1280x1024 380x300mm 19.1-inch   | 1        | 0.88%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 340x270mm 17.1-inch   | 1        | 0.88%   |
| Samsung Electronics SMS23A550H SAM07C9 1920x1080 510x290mm 23.1-inch   | 1        | 0.88%   |
| Samsung Electronics SME1920NR SAM06A4 1280x1024 380x300mm 19.1-inch    | 1        | 0.88%   |
| Samsung Electronics SMB2340 SAM0691 1920x1080 510x290mm 23.1-inch      | 1        | 0.88%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 520x290mm 23.4-inch      | 1        | 0.88%   |
| Samsung Electronics S24D332 SAM0F5E 1920x1080 530x300mm 24.0-inch      | 1        | 0.88%   |
| Samsung Electronics S23C570 SAM0A56 1920x1080 510x290mm 23.1-inch      | 1        | 0.88%   |
| Samsung Electronics S22B300 SAM08AC 1920x1080 480x270mm 21.7-inch      | 1        | 0.88%   |
| Samsung Electronics S20C200 SAM09B4 1600x900 440x250mm 19.9-inch       | 1        | 0.88%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch       | 1        | 0.88%   |
| Samsung Electronics LCD Monitor SAM03BC 1920x1080                      | 1        | 0.88%   |
| Samsung Electronics LC24RG50 SAM0F91 1920x1080 530x300mm 24.0-inch     | 1        | 0.88%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch      | 1        | 0.88%   |
| Philips PHL 278E9Q PHLC17F 1920x1080 600x340mm 27.2-inch               | 1        | 0.88%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch                | 1        | 0.88%   |
| Philips PHL 240V5 PHLC10A 1920x1080 530x300mm 24.0-inch                | 1        | 0.88%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                 | 1        | 0.88%   |
| Philips LCD Monitor PHLC0B1 1920x1080 480x270mm 21.7-inch              | 1        | 0.88%   |
| Philips LCD Monitor PHL 240V5 1920x1080                                | 1        | 0.88%   |
| Philips 248CLH PHLC088 1920x1080 520x290mm 23.4-inch                   | 1        | 0.88%   |
| NEC Computers LCD190V NEC66D3 1280x1024 380x300mm 19.1-inch            | 1        | 0.88%   |
| NEC Computers LCD Monitor EA241WM 1920x1200                            | 1        | 0.88%   |
| Lenovo LEN-M73Z-D LEN00A0 1600x900 440x240mm 19.7-inch                 | 1        | 0.88%   |
| InfoVision LCD Monitor IVO04E3 1366x768 280x160mm 12.7-inch            | 1        | 0.88%   |
| Iiyama PL2783Q IVM661D 2560x1440 600x340mm 27.2-inch                   | 1        | 0.88%   |
| Hewlett-Packard 23xi HWP3031 1920x1080 510x290mm 23.1-inch             | 1        | 0.88%   |
| Goldstar W1934 GSM4B7A 1440x900 410x260mm 19.1-inch                    | 1        | 0.88%   |
| Goldstar LG ULTRAWIDE GSM59F2 2560x1080 580x240mm 24.7-inch            | 1        | 0.88%   |
| Goldstar LCD Monitor GSM5806 1920x1080 480x270mm 21.7-inch             | 1        | 0.88%   |
| Goldstar L1953TR GSM4B44 1280x1024 340x270mm 17.1-inch                 | 1        | 0.88%   |
| Goldstar L1753S GSM446F 1280x1024 340x270mm 17.1-inch                  | 1        | 0.88%   |
| Goldstar L1751SQ GSM43F1 1280x1024 340x270mm 17.1-inch                 | 1        | 0.88%   |
| Goldstar L1530P GSM3B99 1024x768 300x230mm 14.9-inch                   | 1        | 0.88%   |
| Goldstar E2211 GSM5839 1920x1080 480x270mm 21.7-inch                   | 1        | 0.88%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 49       | 45.79%  |
| 1280x1024 (SXGA)   | 13       | 12.15%  |
| 3840x2160 (4K)     | 9        | 8.41%   |
| 1920x1200 (WUXGA)  | 7        | 6.54%   |
| 1680x1050 (WSXGA+) | 6        | 5.61%   |
| 1440x900 (WXGA+)   | 6        | 5.61%   |
| 1366x768 (WXGA)    | 6        | 5.61%   |
| 1600x900 (HD+)     | 4        | 3.74%   |
| 2560x1440 (QHD)    | 2        | 1.87%   |
| 1600x1200          | 2        | 1.87%   |
| 2560x1080          | 1        | 0.93%   |
| 1024x768 (XGA)     | 1        | 0.93%   |
| Unknown            | 1        | 0.93%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 17       | 15.74%  |
| 24      | 14       | 12.96%  |
| 19      | 14       | 12.96%  |
| 23      | 13       | 12.04%  |
| 17      | 9        | 8.33%   |
| 27      | 8        | 7.41%   |
| Unknown | 7        | 6.48%   |
| 18      | 5        | 4.63%   |
| 31      | 3        | 2.78%   |
| 20      | 3        | 2.78%   |
| 50      | 2        | 1.85%   |
| 22      | 2        | 1.85%   |
| 16      | 2        | 1.85%   |
| 15      | 2        | 1.85%   |
| 55      | 1        | 0.93%   |
| 52      | 1        | 0.93%   |
| 48      | 1        | 0.93%   |
| 26      | 1        | 0.93%   |
| 14      | 1        | 0.93%   |
| 13      | 1        | 0.93%   |
| 12      | 1        | 0.93%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 35       | 33.02%  |
| 401-500     | 35       | 33.02%  |
| 301-350     | 14       | 13.21%  |
| Unknown     | 7        | 6.6%    |
| 351-400     | 5        | 4.72%   |
| 1001-1500   | 5        | 4.72%   |
| 601-700     | 3        | 2.83%   |
| 201-300     | 2        | 1.89%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 66       | 61.68%  |
| 16/10   | 18       | 16.82%  |
| 5/4     | 13       | 12.15%  |
| Unknown | 6        | 5.61%   |
| 4/3     | 3        | 2.8%    |
| 21/9    | 1        | 0.93%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 41       | 37.61%  |
| 151-200        | 18       | 16.51%  |
| 141-150        | 13       | 11.93%  |
| 301-350        | 9        | 8.26%   |
| Unknown        | 7        | 6.42%   |
| 251-300        | 6        | 5.5%    |
| More than 1000 | 5        | 4.59%   |
| 351-500        | 3        | 2.75%   |
| 101-110        | 3        | 2.75%   |
| 121-130        | 2        | 1.83%   |
| 81-90          | 1        | 0.92%   |
| 61-70          | 1        | 0.92%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 64       | 60.38%  |
| 101-120 | 20       | 18.87%  |
| 121-160 | 8        | 7.55%   |
| Unknown | 7        | 6.6%    |
| 161-240 | 4        | 3.77%   |
| 1-50    | 3        | 2.83%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 123      | 53.25%  |
| 1     | 99       | 42.86%  |
| 2     | 8        | 3.46%   |
| 3     | 1        | 0.43%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 129      | 45.58%  |
| Intel                             | 78       | 27.56%  |
| Qualcomm Atheros                  | 25       | 8.83%   |
| Broadcom                          | 9        | 3.18%   |
| Marvell Technology Group          | 7        | 2.47%   |
| D-Link System                     | 5        | 1.77%   |
| VIA Technologies                  | 4        | 1.41%   |
| IMC Networks                      | 3        | 1.06%   |
| Qualcomm                          | 2        | 0.71%   |
| Huawei Technologies               | 2        | 0.71%   |
| D-Link                            | 2        | 0.71%   |
| 3Com                              | 2        | 0.71%   |
| TP-Link                           | 1        | 0.35%   |
| Sundance Technology Inc / IC Plus | 1        | 0.35%   |
| Silicon Integrated Systems [SiS]  | 1        | 0.35%   |
| Ralink Technology                 | 1        | 0.35%   |
| Ralink                            | 1        | 0.35%   |
| Qualcomm Atheros Communications   | 1        | 0.35%   |
| Qcom                              | 1        | 0.35%   |
| Nvidia                            | 1        | 0.35%   |
| MYRICOM                           | 1        | 0.35%   |
| Mercucys                          | 1        | 0.35%   |
| Edimax Technology                 | 1        | 0.35%   |
| Atmel                             | 1        | 0.35%   |
| Aquantia                          | 1        | 0.35%   |
| Apple                             | 1        | 0.35%   |
| Accton Technology                 | 1        | 0.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                    | 111      | 34.58%  |
| Intel I211 Gigabit Network Connection                                                | 14       | 4.36%   |
| Intel 82574L Gigabit Network Connection                                              | 11       | 3.43%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                | 7        | 2.18%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                | 6        | 1.87%   |
| Intel I210 Gigabit Network Connection                                                | 5        | 1.56%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                      | 4        | 1.25%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                       | 4        | 1.25%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                              | 4        | 1.25%   |
| Intel I350 Gigabit Network Connection                                                | 4        | 1.25%   |
| Intel Ethernet Connection I217-V                                                     | 4        | 1.25%   |
| VIA VT6105/VT6106S [Rhine-III]                                                       | 3        | 0.93%   |
| Realtek RTL8125 2.5GbE Controller                                                    | 3        | 0.93%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                        | 3        | 0.93%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                     | 3        | 0.93%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                       | 3        | 0.93%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                              | 3        | 0.93%   |
| Intel Wi-Fi 6 AX200                                                                  | 3        | 0.93%   |
| Intel Ethernet Connection (7) I219-V                                                 | 3        | 0.93%   |
| Intel Ethernet Connection (7) I219-LM                                                | 3        | 0.93%   |
| Intel Ethernet Connection (2) I219-V                                                 | 3        | 0.93%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                                 | 3        | 0.93%   |
| Intel 82579V Gigabit Network Connection                                              | 3        | 0.93%   |
| Intel 82562EZ 10/100 Ethernet Controller                                             | 3        | 0.93%   |
| Intel 82540EM Gigabit Ethernet Controller                                            | 3        | 0.93%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                                      | 3        | 0.93%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                      | 2        | 0.62%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                           | 2        | 0.62%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                     | 2        | 0.62%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                        | 2        | 0.62%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                             | 2        | 0.62%   |
| Qualcomm ALCATEL Composite RNDIS Interface                                           | 2        | 0.62%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                                    | 2        | 0.62%   |
| Intel Wireless 7265                                                                  | 2        | 0.62%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                        | 2        | 0.62%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                         | 2        | 0.62%   |
| Intel Ethernet Connection (2) I219-LM                                                | 2        | 0.62%   |
| Intel Cannon Lake PCH CNVi WiFi                                                      | 2        | 0.62%   |
| Intel 82576 Gigabit Network Connection                                               | 2        | 0.62%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                                   | 2        | 0.62%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications)        | 2        | 0.62%   |
| IMC Networks Realtek RTL8191SU Wireless LAN 802.11n USB 2.0 Network Adapter          | 2        | 0.62%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                                     | 2        | 0.62%   |
| VIA VT6102/VT6103 [Rhine-II]                                                         | 1        | 0.31%   |
| TP-Link TP-LINK Wireless USB Adapter                                                 | 1        | 0.31%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY           | 1        | 0.31%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                            | 1        | 0.31%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                             | 1        | 0.31%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                      | 1        | 0.31%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                               | 1        | 0.31%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 1        | 0.31%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                           | 1        | 0.31%   |
| Realtek Realtek Bluetooth Adapter                                                    | 1        | 0.31%   |
| Realtek Killer E3000 2.5GbE Controller                                               | 1        | 0.31%   |
| Realtek 802.11n WLAN Adapter                                                         | 1        | 0.31%   |
| Ralink RT5370 Wireless Adapter                                                       | 1        | 0.31%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                                 | 1        | 0.31%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1        | 0.31%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 1        | 0.31%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                       | 1        | 0.31%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 14       | 28.57%  |
| Qualcomm Atheros                | 12       | 24.49%  |
| Realtek Semiconductor           | 10       | 20.41%  |
| IMC Networks                    | 3        | 6.12%   |
| D-Link                          | 2        | 4.08%   |
| TP-Link                         | 1        | 2.04%   |
| Ralink Technology               | 1        | 2.04%   |
| Ralink                          | 1        | 2.04%   |
| Qualcomm Atheros Communications | 1        | 2.04%   |
| Qcom                            | 1        | 2.04%   |
| Mercucys                        | 1        | 2.04%   |
| Edimax Technology               | 1        | 2.04%   |
| Broadcom                        | 1        | 2.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR93xx Wireless Network Adapter                                     | 3        | 6.12%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                       | 3        | 6.12%   |
| Intel Wi-Fi 6 AX200                                                                  | 3        | 6.12%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                      | 2        | 4.08%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                           | 2        | 4.08%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                     | 2        | 4.08%   |
| Intel Wireless 7265                                                                  | 2        | 4.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                                      | 2        | 4.08%   |
| IMC Networks Realtek RTL8191SU Wireless LAN 802.11n USB 2.0 Network Adapter          | 2        | 4.08%   |
| TP-Link TP-LINK Wireless USB Adapter                                                 | 1        | 2.04%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                             | 1        | 2.04%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                      | 1        | 2.04%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                               | 1        | 2.04%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 1        | 2.04%   |
| Realtek Realtek Bluetooth Adapter                                                    | 1        | 2.04%   |
| Realtek 802.11n WLAN Adapter                                                         | 1        | 2.04%   |
| Ralink RT5370 Wireless Adapter                                                       | 1        | 2.04%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                                 | 1        | 2.04%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1        | 2.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 1        | 2.04%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                       | 1        | 2.04%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                     | 1        | 2.04%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                           | 1        | 2.04%   |
| Qcom RT73 USB Wireless LAN Card                                                      | 1        | 2.04%   |
| Mercucys MERCUSYS Wireless USB Adapter                                               | 1        | 2.04%   |
| Intel Wireless 8260                                                                  | 1        | 2.04%   |
| Intel Wireless 7260                                                                  | 1        | 2.04%   |
| Intel Wireless 3160                                                                  | 1        | 2.04%   |
| Intel Wi-Fi 6 AX201 160MHz                                                           | 1        | 2.04%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 1        | 2.04%   |
| Intel Centrino Wireless-N 2230                                                       | 1        | 2.04%   |
| Intel Centrino Wireless-N 2200                                                       | 1        | 2.04%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                                 | 1        | 2.04%   |
| Edimax EW-7612UAn V2 802.11n Wireless Adapter [Realtek RTL8192CU]                    | 1        | 2.04%   |
| D-Link DWA-140 RangeBooster N Adapter(rev.B3) [Ralink RT5372]                        | 1        | 2.04%   |
| D-Link DWA-125 Wireless N 150 Adapter(rev.B1) [Ralink RT5370]                        | 1        | 2.04%   |
| Broadcom BCM43228 802.11a/b/g/n                                                      | 1        | 2.04%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 126      | 51.43%  |
| Intel                             | 70       | 28.57%  |
| Qualcomm Atheros                  | 14       | 5.71%   |
| Broadcom                          | 8        | 3.27%   |
| Marvell Technology Group          | 7        | 2.86%   |
| D-Link System                     | 5        | 2.04%   |
| VIA Technologies                  | 4        | 1.63%   |
| Qualcomm                          | 2        | 0.82%   |
| 3Com                              | 2        | 0.82%   |
| Sundance Technology Inc / IC Plus | 1        | 0.41%   |
| Silicon Integrated Systems [SiS]  | 1        | 0.41%   |
| Nvidia                            | 1        | 0.41%   |
| Huawei Technologies               | 1        | 0.41%   |
| Aquantia                          | 1        | 0.41%   |
| Apple                             | 1        | 0.41%   |
| Accton Technology                 | 1        | 0.41%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 111      | 41.42%  |
| Intel I211 Gigabit Network Connection                                         | 14       | 5.22%   |
| Intel 82574L Gigabit Network Connection                                       | 11       | 4.1%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 7        | 2.61%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 6        | 2.24%   |
| Intel I210 Gigabit Network Connection                                         | 5        | 1.87%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 4        | 1.49%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 4        | 1.49%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 4        | 1.49%   |
| Intel I350 Gigabit Network Connection                                         | 4        | 1.49%   |
| Intel Ethernet Connection I217-V                                              | 4        | 1.49%   |
| VIA VT6105/VT6106S [Rhine-III]                                                | 3        | 1.12%   |
| Realtek RTL8125 2.5GbE Controller                                             | 3        | 1.12%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 3        | 1.12%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 3        | 1.12%   |
| Intel Ethernet Connection (7) I219-V                                          | 3        | 1.12%   |
| Intel Ethernet Connection (7) I219-LM                                         | 3        | 1.12%   |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 1.12%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 3        | 1.12%   |
| Intel 82579V Gigabit Network Connection                                       | 3        | 1.12%   |
| Intel 82562EZ 10/100 Ethernet Controller                                      | 3        | 1.12%   |
| Intel 82540EM Gigabit Ethernet Controller                                     | 3        | 1.12%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 3        | 1.12%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 2        | 0.75%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 2        | 0.75%   |
| Qualcomm ALCATEL Composite RNDIS Interface                                    | 2        | 0.75%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                             | 2        | 0.75%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 2        | 0.75%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 2        | 0.75%   |
| Intel Ethernet Connection (2) I219-LM                                         | 2        | 0.75%   |
| Intel 82576 Gigabit Network Connection                                        | 2        | 0.75%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 2        | 0.75%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2        | 0.75%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 2        | 0.75%   |
| VIA VT6102/VT6103 [Rhine-II]                                                  | 1        | 0.37%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY    | 1        | 0.37%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                     | 1        | 0.37%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 1        | 0.37%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 1        | 0.37%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1        | 0.37%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 1        | 0.37%   |
| Nvidia MCP77 Ethernet                                                         | 1        | 0.37%   |
| Intel Ethernet Controller X550                                                | 1        | 0.37%   |
| Intel Ethernet Controller I225-V                                              | 1        | 0.37%   |
| Intel Ethernet Connection X553 1GbE                                           | 1        | 0.37%   |
| Intel Ethernet Connection I218-LM                                             | 1        | 0.37%   |
| Intel Ethernet Connection (2) I218-V                                          | 1        | 0.37%   |
| Intel Ethernet Connection (12) I219-V                                         | 1        | 0.37%   |
| Intel Ethernet Connection (11) I219-V                                         | 1        | 0.37%   |
| Intel Ethernet Connection (10) I219-LM                                        | 1        | 0.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 1        | 0.37%   |
| Intel 82573E Gigabit Ethernet Controller (Copper)                             | 1        | 0.37%   |
| Intel 82566DC-2 Gigabit Network Connection                                    | 1        | 0.37%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 1        | 0.37%   |
| Intel 82541GI Gigabit Ethernet Controller                                     | 1        | 0.37%   |
| Intel 82541EI Gigabit Ethernet Controller                                     | 1        | 0.37%   |
| Huawei USB Composite Device                                                   | 1        | 0.37%   |
| D-Link System RTL8139 Ethernet                                                | 1        | 0.37%   |
| D-Link System DL10050 Sundance Ethernet                                       | 1        | 0.37%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 1        | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 208      | 80.31%  |
| WiFi     | 47       | 18.15%  |
| Unknown  | 3        | 1.16%   |
| Modem    | 1        | 0.39%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 190      | 86.36%  |
| WiFi     | 29       | 13.18%  |
| Unknown  | 1        | 0.45%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 110      | 48.46%  |
| 2     | 64       | 28.19%  |
| 3     | 24       | 10.57%  |
| 0     | 16       | 7.05%   |
| 4     | 11       | 4.85%   |
| 8     | 1        | 0.44%   |
| 7     | 1        | 0.44%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 219      | 95.63%  |
| Yes  | 10       | 4.37%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 14       | 56%     |
| IMC Networks                    | 2        | 8%      |
| Cambridge Silicon Radio         | 2        | 8%      |
| ASUSTek Computer                | 2        | 8%      |
| Realtek Semiconductor           | 1        | 4%      |
| Qualcomm Atheros Communications | 1        | 4%      |
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
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 3        | 12%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2        | 8%      |
| Realtek  Bluetooth 4.0 Adapter                              | 1        | 4%      |
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
| Intel                            | 130      | 51.18%  |
| Nvidia                           | 55       | 21.65%  |
| AMD                              | 46       | 18.11%  |
| C-Media Electronics              | 4        | 1.57%   |
| Realtek Semiconductor            | 3        | 1.18%   |
| Logitech                         | 3        | 1.18%   |
| Creative Labs                    | 2        | 0.79%   |
| VIA Technologies                 | 1        | 0.39%   |
| Texas Instruments                | 1        | 0.39%   |
| SteelSeries ApS                  | 1        | 0.39%   |
| Silicon Integrated Systems [SiS] | 1        | 0.39%   |
| Samsung Electronics              | 1        | 0.39%   |
| Microsoft                        | 1        | 0.39%   |
| JMTek                            | 1        | 0.39%   |
| GN Netcom                        | 1        | 0.39%   |
| FiiO Electronics Technology      | 1        | 0.39%   |
| ESS Technology                   | 1        | 0.39%   |
| Creative Technology              | 1        | 0.39%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 16       | 5.71%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 15       | 5.36%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 11       | 3.93%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11       | 3.93%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 11       | 3.93%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 10       | 3.57%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 9        | 3.21%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 9        | 3.21%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 8        | 2.86%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 8        | 2.86%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 6        | 2.14%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 6        | 2.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6        | 2.14%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6        | 2.14%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 6        | 2.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5        | 1.79%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5        | 1.79%   |
| Intel 200 Series PCH HD Audio                                                                     | 5        | 1.79%   |
| AMD FCH Azalia Controller                                                                         | 5        | 1.79%   |
| Nvidia High Definition Audio Controller                                                           | 4        | 1.43%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4        | 1.43%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4        | 1.43%   |
| Nvidia MCP61 High Definition Audio                                                                | 3        | 1.07%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 3        | 1.07%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 3        | 1.07%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 3        | 1.07%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3        | 1.07%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3        | 1.07%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                                              | 3        | 1.07%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 3        | 1.07%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 3        | 1.07%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3        | 1.07%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 3        | 1.07%   |
| Realtek Semiconductor Realtek USB Audio                                                           | 2        | 0.71%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2        | 0.71%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 2        | 0.71%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 2        | 0.71%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2        | 0.71%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 2        | 0.71%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2        | 0.71%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 2        | 0.71%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2        | 0.71%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 2        | 0.71%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 2        | 0.71%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2        | 0.71%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                                     | 2        | 0.71%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2        | 0.71%   |
| Unknown                                                                                           | 2        | 0.71%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1        | 0.36%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                 | 1        | 0.36%   |
| SteelSeries ApS SteelSeries Arctis 5 Arctis 5 Chat Arctis 5 Game                                  | 1        | 0.36%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 1        | 0.36%   |
| Samsung Electronics Samsung Type-C to 3.5pi gender adapter                                        | 1        | 0.36%   |
| Realtek Semiconductor TX-384Khz Hifi Type-C Audio                                                 | 1        | 0.36%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1        | 0.36%   |
| Nvidia MCP79 High Definition Audio                                                                | 1        | 0.36%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 1        | 0.36%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1        | 0.36%   |
| Nvidia GP102 HDMI Audio Controller                                                                | 1        | 0.36%   |
| Nvidia GK110 High Definition Audio Controller                                                     | 1        | 0.36%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown                      | 60       | 30.46%  |
| Kingston                     | 42       | 21.32%  |
| Samsung Electronics          | 23       | 11.68%  |
| Crucial                      | 11       | 5.58%   |
| SK Hynix                     | 7        | 3.55%   |
| Corsair                      | 6        | 3.05%   |
| Patriot                      | 5        | 2.54%   |
| Micron Technology            | 5        | 2.54%   |
| Unknown                      | 5        | 2.54%   |
| Nanya Technology             | 4        | 2.03%   |
| G.Skill                      | 4        | 2.03%   |
| AMD                          | 4        | 2.03%   |
| A-DATA Technology            | 4        | 2.03%   |
| Transcend                    | 2        | 1.02%   |
| Patriot Memory (PDP Systems) | 2        | 1.02%   |
| Apacer                       | 2        | 1.02%   |
| Unknown (ABCD)               | 1        | 0.51%   |
| Unifosa                      | 1        | 0.51%   |
| Tigo                         | 1        | 0.51%   |
| S                            | 1        | 0.51%   |
| Ramos Technology             | 1        | 0.51%   |
| Qumo                         | 1        | 0.51%   |
| Kingmax                      | 1        | 0.51%   |
| H                            | 1        | 0.51%   |
| Goldkey                      | 1        | 0.51%   |
| Elpida                       | 1        | 0.51%   |
| Atermiter                    | 1        | 0.51%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                    | Desktops | Percent |
|--------------------------------------------------------------------------|----------|---------|
| Unknown                                                                  | 5        | 2.2%    |
| Unknown RAM Module 512MB DIMM SDRAM                                      | 4        | 1.76%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                     | 4        | 1.76%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                              | 4        | 1.76%   |
| Unknown RAM Module 1GB DIMM SDRAM                                        | 4        | 1.76%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                     | 3        | 1.32%   |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3400MT/s                              | 3        | 1.32%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                                     | 2        | 0.88%   |
| Unknown RAM Module 8192MB DIMM 1066MT/s                                  | 2        | 0.88%   |
| Unknown RAM Module 2GB DIMM SDRAM                                        | 2        | 0.88%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                                 | 2        | 0.88%   |
| Unknown RAM Module 2GB DIMM 800MT/s                                      | 2        | 0.88%   |
| Unknown RAM Module 1GB DIMM 1333MT/s                                     | 2        | 0.88%   |
| Unknown RAM Module 1024MB DIMM SDRAM                                     | 2        | 0.88%   |
| SK Hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s                     | 2        | 0.88%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                    | 2        | 0.88%   |
| Samsung RAM M393A2K40BB2-CTD 16GB DIMM DDR4 2667MT/s                     | 2        | 0.88%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 1333MT/s                      | 2        | 0.88%   |
| Patriot Memory (PDP Systems) RAM 3200 C16 Series 16GB DIMM DDR4 2400MT/s | 2        | 0.88%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3200MT/s                     | 2        | 0.88%   |
| Kingston RAM KHX2400C11D3/8GX 8GB DIMM DDR3 2400MT/s                     | 2        | 0.88%   |
| Kingston RAM 99U5595-003.A00LF 2GB DIMM DDR3 1600MT/s                    | 2        | 0.88%   |
| Kingston RAM 99U5471-020.A00LF 4GB DIMM DDR3 1333MT/s                    | 2        | 0.88%   |
| Kingston RAM 9905584-029.A00LF 4GB DIMM DDR3 1600MT/s                    | 2        | 0.88%   |
| G.Skill RAM F4-4000C18-32GVK 32GB DIMM DDR4 3200MT/s                     | 2        | 0.88%   |
| Crucial RAM CT8G4SFS824A.C8BD1 8GB SODIMM DDR4 2400MT/s                  | 2        | 0.88%   |
| Crucial RAM CT51264BA160B.C16F 4GB DIMM DDR3 1600MT/s                    | 2        | 0.88%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s                    | 2        | 0.88%   |
| Apacer RAM 78.A2GF7.4000B 2GB SODIMM DDR4 2400MT/s                       | 2        | 0.88%   |
| Unknown RAM Module 8192MB DIMM 400MT/s                                   | 1        | 0.44%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                                  | 1        | 0.44%   |
| Unknown RAM Module 512MB DIMM DDR2 667MT/s                               | 1        | 0.44%   |
| Unknown RAM Module 512MB DIMM DDR2                                       | 1        | 0.44%   |
| Unknown RAM Module 512MB DIMM DDR 400MT/s                                | 1        | 0.44%   |
| Unknown RAM Module 512MB DIMM DDR 133MT/s                                | 1        | 0.44%   |
| Unknown RAM Module 512MB DIMM 667MT/s                                    | 1        | 0.44%   |
| Unknown RAM Module 512MB DIMM 400MT/s                                    | 1        | 0.44%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                              | 1        | 0.44%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                                | 1        | 0.44%   |
| Unknown RAM Module 4GB DIMM 400MT/s                                      | 1        | 0.44%   |
| Unknown RAM Module 4096MB DIMM DDR3                                      | 1        | 0.44%   |
| Unknown RAM Module 4096MB DIMM DDR2 667MT/s                              | 1        | 0.44%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                                  | 1        | 0.44%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                                  | 1        | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s                               | 1        | 0.44%   |
| Unknown RAM Module 2GB DIMM SDRAM 533MT/s                                | 1        | 0.44%   |
| Unknown RAM Module 2GB DIMM DDR3 1600MT/s                                | 1        | 0.44%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                                | 1        | 0.44%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                                | 1        | 0.44%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                                 | 1        | 0.44%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                                 | 1        | 0.44%   |
| Unknown RAM Module 2GB DIMM DDR 667MT/s                                  | 1        | 0.44%   |
| Unknown RAM Module 2GB DIMM                                              | 1        | 0.44%   |
| Unknown RAM Module 256MB DIMM DDR 400MT/s                                | 1        | 0.44%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                              | 1        | 0.44%   |
| Unknown RAM Module 2048MB DIMM DDR2 533MT/s                              | 1        | 0.44%   |
| Unknown RAM Module 2048MB DIMM DDR2 266MT/s                              | 1        | 0.44%   |
| Unknown RAM Module 2048MB DIMM DDR2                                      | 1        | 0.44%   |
| Unknown RAM Module 2048MB DIMM DDR 667MT/s                               | 1        | 0.44%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                                   | 1        | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 68       | 37.57%  |
| DDR4    | 55       | 30.39%  |
| Unknown | 20       | 11.05%  |
| DDR2    | 17       | 9.39%   |
| SDRAM   | 13       | 7.18%   |
| DDR     | 7        | 3.87%   |
| LPDDR4  | 1        | 0.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 159      | 87.85%  |
| SODIMM | 22       | 12.15%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 49       | 25.26%  |
| 2048  | 44       | 22.68%  |
| 8192  | 41       | 21.13%  |
| 16384 | 24       | 12.37%  |
| 1024  | 21       | 10.82%  |
| 512   | 10       | 5.15%   |
| 32768 | 4        | 2.06%   |
| 256   | 1        | 0.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 35       | 18.52%  |
| 1333    | 32       | 16.93%  |
| 2400    | 22       | 11.64%  |
| 800     | 16       | 8.47%   |
| 3200    | 14       | 7.41%   |
| Unknown | 14       | 7.41%   |
| 2667    | 9        | 4.76%   |
| 667     | 9        | 4.76%   |
| 2133    | 7        | 3.7%    |
| 400     | 7        | 3.7%    |
| 2666    | 4        | 2.12%   |
| 1066    | 4        | 2.12%   |
| 3400    | 3        | 1.59%   |
| 1866    | 2        | 1.06%   |
| 1067    | 2        | 1.06%   |
| 533     | 2        | 1.06%   |
| 3733    | 1        | 0.53%   |
| 2048    | 1        | 0.53%   |
| 1867    | 1        | 0.53%   |
| 1334    | 1        | 0.53%   |
| 333     | 1        | 0.53%   |
| 266     | 1        | 0.53%   |
| 133     | 1        | 0.53%   |

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
| Quanta                  | 1        | 11.11%  |
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
| Quanta VGA WebCam                 | 1        | 11.11%  |
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
| 0     | 110      | 47.62%  |
| 1     | 91       | 39.39%  |
| 2     | 19       | 8.23%   |
| 3     | 8        | 3.46%   |
| 4     | 3        | 1.3%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 92       | 63.89%  |
| Net/wireless             | 17       | 11.81%  |
| Sound                    | 13       | 9.03%   |
| Firewire controller      | 6        | 4.17%   |
| Bluetooth                | 6        | 4.17%   |
| Graphics card            | 3        | 2.08%   |
| Network                  | 2        | 1.39%   |
| Net/ethernet             | 2        | 1.39%   |
| Storage/ata              | 1        | 0.69%   |
| Storage                  | 1        | 0.69%   |
| Card reader              | 1        | 0.69%   |

