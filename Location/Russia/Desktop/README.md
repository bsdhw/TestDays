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

Total: 398

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| ASUSTek       | PRIME B550-PLUS             | [4c3b92bb42](https://bsd-hardware.info/?probe=4c3b92bb42) | Dec 24, 2022 |
| Unknown       | Unknown                     | [d702dfcde2](https://bsd-hardware.info/?probe=d702dfcde2) | Dec 23, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [3e5e7e3e61](https://bsd-hardware.info/?probe=3e5e7e3e61) | Dec 22, 2022 |
| Unknown       | Unknown                     | [7c644cc639](https://bsd-hardware.info/?probe=7c644cc639) | Dec 15, 2022 |
| Unknown       | Unknown                     | [9b5307f44d](https://bsd-hardware.info/?probe=9b5307f44d) | Dec 15, 2022 |
| Huanan        | X99-F8D V2.4                | [3d06b605c5](https://bsd-hardware.info/?probe=3d06b605c5) | Dec 13, 2022 |
| ASUSTek       | P8H77-V LE                  | [10b6c81bce](https://bsd-hardware.info/?probe=10b6c81bce) | Dec 09, 2022 |
| Huanan        | X99-F8D V2.4                | [f6685811a3](https://bsd-hardware.info/?probe=f6685811a3) | Dec 05, 2022 |
| Dell          | 0CNWVK A00                  | [5a022db6bf](https://bsd-hardware.info/?probe=5a022db6bf) | Dec 05, 2022 |
| Intel         | X99                         | [c21a466fc1](https://bsd-hardware.info/?probe=c21a466fc1) | Dec 01, 2022 |
| MSI           | PRO H610M-B DDR4            | [929e4bda1e](https://bsd-hardware.info/?probe=929e4bda1e) | Nov 29, 2022 |
| MSI           | PRO H610M-B DDR4            | [7c9ee800c5](https://bsd-hardware.info/?probe=7c9ee800c5) | Nov 29, 2022 |
| QIYIDA        | X99-H9 V2.0                 | [43163b0170](https://bsd-hardware.info/?probe=43163b0170) | Nov 28, 2022 |
| QIYIDA        | X99-H9 V2.0                 | [d00aa0021e](https://bsd-hardware.info/?probe=d00aa0021e) | Nov 28, 2022 |
| Acer          | Revo RN86                   | [a4dcb7f7a2](https://bsd-hardware.info/?probe=a4dcb7f7a2) | Nov 27, 2022 |
| Unknown       | Unknown                     | [1d3bd58d18](https://bsd-hardware.info/?probe=1d3bd58d18) | Nov 25, 2022 |
| Gigabyte      | H81M-HD3                    | [564cf3d66a](https://bsd-hardware.info/?probe=564cf3d66a) | Nov 22, 2022 |
| Apple         | PowerMac10,1                | [0760ed34c3](https://bsd-hardware.info/?probe=0760ed34c3) | Nov 21, 2022 |
| Huanan        | X99-F8D V2.4                | [9faf79b3f3](https://bsd-hardware.info/?probe=9faf79b3f3) | Nov 18, 2022 |
| Huanan        | X99-F8D V2.4                | [22ec05d988](https://bsd-hardware.info/?probe=22ec05d988) | Nov 12, 2022 |
| Acer          | RS880M05                    | [455f9b5026](https://bsd-hardware.info/?probe=455f9b5026) | Nov 07, 2022 |
| ASUSTek       | Z170-K                      | [907b8c2402](https://bsd-hardware.info/?probe=907b8c2402) | Nov 05, 2022 |
| Unknown       | Unknown                     | [58c2f4b4f7](https://bsd-hardware.info/?probe=58c2f4b4f7) | Nov 04, 2022 |
| HP            | 339A                        | [370d93ecde](https://bsd-hardware.info/?probe=370d93ecde) | Nov 02, 2022 |
| Gigabyte      | Z68XP-UD3                   | [0f22defdb3](https://bsd-hardware.info/?probe=0f22defdb3) | Oct 30, 2022 |
| Unknown       | Unknown                     | [acf41f7000](https://bsd-hardware.info/?probe=acf41f7000) | Oct 29, 2022 |
| PC Engines    | APU2                        | [d52e3d0ce3](https://bsd-hardware.info/?probe=d52e3d0ce3) | Oct 25, 2022 |
| ASUSTek       | P8Z68-V GEN3                | [d7b32200a5](https://bsd-hardware.info/?probe=d7b32200a5) | Oct 22, 2022 |
| Acer          | Revo RN86                   | [692ea69bab](https://bsd-hardware.info/?probe=692ea69bab) | Oct 21, 2022 |
| PC Engines    | APU2                        | [cf1abf5e46](https://bsd-hardware.info/?probe=cf1abf5e46) | Oct 21, 2022 |
| Unknown       | Unknown                     | [d5586487b4](https://bsd-hardware.info/?probe=d5586487b4) | Oct 21, 2022 |
| ASUSTek       | P10S-I Series               | [ceb58e75b8](https://bsd-hardware.info/?probe=ceb58e75b8) | Oct 20, 2022 |
| Supermicro    | X11SSL-F                    | [24faa4663c](https://bsd-hardware.info/?probe=24faa4663c) | Oct 19, 2022 |
| ASUSTek       | N3050I-C                    | [4a83b0953e](https://bsd-hardware.info/?probe=4a83b0953e) | Oct 18, 2022 |
| Gigabyte      | C1037UN-EU                  | [734ff7f48c](https://bsd-hardware.info/?probe=734ff7f48c) | Oct 02, 2022 |
| ASRock        | X570M Pro4                  | [433857f5f7](https://bsd-hardware.info/?probe=433857f5f7) | Sep 27, 2022 |
| YANYU         | H67SL                       | [5f5819ef11](https://bsd-hardware.info/?probe=5f5819ef11) | Sep 24, 2022 |
| NITRINOnet    | M360RUS56                   | [490b9593e0](https://bsd-hardware.info/?probe=490b9593e0) | Sep 23, 2022 |
| YANYU         | H67SL                       | [37ba00c2f3](https://bsd-hardware.info/?probe=37ba00c2f3) | Sep 15, 2022 |
| Maxtang       | BYT30                       | [90053990c3](https://bsd-hardware.info/?probe=90053990c3) | Sep 10, 2022 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [98dff45d54](https://bsd-hardware.info/?probe=98dff45d54) | Sep 09, 2022 |
| Dell          | 0Y7WYT A00                  | [2870b9e4c7](https://bsd-hardware.info/?probe=2870b9e4c7) | Sep 05, 2022 |
| HP            | 8719                        | [f3132fc160](https://bsd-hardware.info/?probe=f3132fc160) | Sep 05, 2022 |
| Maxtang       | BYT30                       | [f5c34c7662](https://bsd-hardware.info/?probe=f5c34c7662) | Sep 03, 2022 |
| ASRock        | ConRoeXFire-eSATA2          | [caf005ed95](https://bsd-hardware.info/?probe=caf005ed95) | Sep 01, 2022 |
| Intel         | X79 V2.72A                  | [435901d8c9](https://bsd-hardware.info/?probe=435901d8c9) | Aug 29, 2022 |
| Gigabyte      | A320M-H-CF                  | [2549c7cadf](https://bsd-hardware.info/?probe=2549c7cadf) | Aug 27, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [7d4eaaf087](https://bsd-hardware.info/?probe=7d4eaaf087) | Aug 22, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [063addc66e](https://bsd-hardware.info/?probe=063addc66e) | Aug 22, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [5ea9441653](https://bsd-hardware.info/?probe=5ea9441653) | Aug 19, 2022 |
| Gigabyte      | C1037UN-EU                  | [0a867d7017](https://bsd-hardware.info/?probe=0a867d7017) | Aug 18, 2022 |
| Gigabyte      | H61M-DS2                    | [a2fc8d9c67](https://bsd-hardware.info/?probe=a2fc8d9c67) | Aug 18, 2022 |
| Gigabyte      | H61M-DS2                    | [9a7d45e51c](https://bsd-hardware.info/?probe=9a7d45e51c) | Aug 16, 2022 |
| ASUSTek       | PRIME X370-PRO              | [4055810ef2](https://bsd-hardware.info/?probe=4055810ef2) | Aug 14, 2022 |
| ASRock        | H110M-DGS R3.0              | [0c654b6c34](https://bsd-hardware.info/?probe=0c654b6c34) | Aug 11, 2022 |
| Unknown       | Unknown                     | [467bcd3c04](https://bsd-hardware.info/?probe=467bcd3c04) | Aug 07, 2022 |
| Unknown       | Unknown                     | [b3c0b4a4f4](https://bsd-hardware.info/?probe=b3c0b4a4f4) | Aug 04, 2022 |
| Unknown       | Unknown                     | [612282319b](https://bsd-hardware.info/?probe=612282319b) | Aug 04, 2022 |
| Acer          | Revo 70                     | [0c23ffdc5a](https://bsd-hardware.info/?probe=0c23ffdc5a) | Aug 03, 2022 |
| ASRock        | A320M-DVS R4.0              | [77f61a8711](https://bsd-hardware.info/?probe=77f61a8711) | Aug 01, 2022 |
| Gigabyte      | 970A-DS3P FX                | [3c33e546bb](https://bsd-hardware.info/?probe=3c33e546bb) | Jul 31, 2022 |
| HP            | 339A                        | [241e56a349](https://bsd-hardware.info/?probe=241e56a349) | Jul 27, 2022 |
| Gigabyte      | H61M-DS2                    | [3ba3cedec4](https://bsd-hardware.info/?probe=3ba3cedec4) | Jul 21, 2022 |
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
| ASUSTek       | PRIME B550-PLUS             | [224614e9ab](https://bsd-hardware.info/?probe=224614e9ab) | May 10, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [76eef59920](https://bsd-hardware.info/?probe=76eef59920) | May 10, 2022 |
| ASUSTek       | P8Z77-V LX                  | [bf3d4941a2](https://bsd-hardware.info/?probe=bf3d4941a2) | May 06, 2022 |
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
| HP            | ProLiant MicroServer        | [fa76da045a](https://bsd-hardware.info/?probe=fa76da045a) | Apr 13, 2022 |
| Gigabyte      | E3000N                      | [7169c296cc](https://bsd-hardware.info/?probe=7169c296cc) | Apr 08, 2022 |
| Supermicro    | X10DRi-T                    | [e17bbe2186](https://bsd-hardware.info/?probe=e17bbe2186) | Apr 05, 2022 |
| Gigabyte      | H310M S2 x.x                | [29a9462f72](https://bsd-hardware.info/?probe=29a9462f72) | Apr 04, 2022 |
| Intel         | DCP847SKE                   | [a79e298be3](https://bsd-hardware.info/?probe=a79e298be3) | Apr 03, 2022 |
| Supermicro    | X10DRi-T                    | [eae4612261](https://bsd-hardware.info/?probe=eae4612261) | Mar 31, 2022 |
| MSI           | B85-G43                     | [f0a919c35f](https://bsd-hardware.info/?probe=f0a919c35f) | Mar 25, 2022 |
| MSI           | B85-G43                     | [7bd545fda8](https://bsd-hardware.info/?probe=7bd545fda8) | Mar 25, 2022 |
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
| Gigabyte      | H61M-DS2                    | [d9657e7246](https://bsd-hardware.info/?probe=d9657e7246) | Jun 01, 2021 |
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
| ASUSTek       | H81M-D PLUS                 | [7be45f1bec](https://bsd-hardware.info/?probe=7be45f1bec) | Sep 19, 2020 |
| ASUSTek       | H81M-D PLUS                 | [e9dd488fe0](https://bsd-hardware.info/?probe=e9dd488fe0) | Sep 13, 2020 |
| ASUSTek       | P5QD TURBO                  | [598e77539b](https://bsd-hardware.info/?probe=598e77539b) | Aug 21, 2020 |
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
| helloSystem 0.7.0    | 24       | 7.32%   |
| OpenBSD 6.8          | 19       | 5.79%   |
| FreeBSD 12.1-p5      | 15       | 4.57%   |
| FreeBSD 13.0         | 14       | 4.27%   |
| FreeBSD 13.1         | 11       | 3.35%   |
| OpenBSD 7.1          | 10       | 3.05%   |
| helloSystem 0.5.0    | 9        | 2.74%   |
| FreeBSD 13.0-STABLE  | 9        | 2.74%   |
| OpenBSD 7.0          | 8        | 2.44%   |
| OpenBSD 6.7          | 8        | 2.44%   |
| FreeBSD 14.0-CURRENT | 7        | 2.13%   |
| FreeBSD 12.1-STABLE  | 7        | 2.13%   |
| OpenBSD 7.2          | 6        | 1.83%   |
| helloSystem 0.6.0    | 6        | 1.83%   |
| helloSystem 0.4.0    | 6        | 1.83%   |
| FreeBSD 12.2         | 6        | 1.83%   |
| helloSystem 0.8.0    | 5        | 1.52%   |
| GhostBSD 20.04.02    | 5        | 1.52%   |
| FreeBSD 12.1-p7      | 5        | 1.52%   |
| OPNsense 22.7.6      | 4        | 1.22%   |
| OPNsense 22.1.6      | 4        | 1.22%   |
| OPNsense 21.1.5      | 4        | 1.22%   |
| OpenBSD 6.9          | 4        | 1.22%   |
| FreeBSD 12.2-p3      | 4        | 1.22%   |
| FreeBSD 12.2-p2      | 4        | 1.22%   |
| OPNsense 22.1.10     | 3        | 0.91%   |
| OPNsense 22.1        | 3        | 0.91%   |
| OPNsense 21.7.6      | 3        | 0.91%   |
| OPNsense 21.1.7      | 3        | 0.91%   |
| OPNsense 21.1.1      | 3        | 0.91%   |
| OPNsense 21.1        | 3        | 0.91%   |
| FreeBSD 13.1-p2      | 3        | 0.91%   |
| FreeBSD 13.0-p5      | 3        | 0.91%   |
| FreeBSD 13.0-CURRENT | 3        | 0.91%   |
| FreeBSD 12.2-p4      | 3        | 0.91%   |
| FreeBSD 12.1-p8      | 3        | 0.91%   |
| FreeBSD 12.1-p6      | 3        | 0.91%   |
| OPNsense 22.7.4      | 2        | 0.61%   |
| OPNsense 22.7        | 2        | 0.61%   |
| OPNsense 21.7.1      | 2        | 0.61%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| FreeBSD     | 117      | 42.09%  |
| helloSystem | 51       | 18.35%  |
| OPNsense    | 43       | 15.47%  |
| OpenBSD     | 41       | 14.75%  |
| NetBSD      | 7        | 2.52%   |
| MyBee       | 5        | 1.8%    |
| GhostBSD    | 5        | 1.8%    |
| NomadBSD    | 3        | 1.08%   |
| Ting        | 1        | 0.36%   |
| pfSense     | 1        | 0.36%   |
| PC-BSD      | 1        | 0.36%   |
| FuryBSD     | 1        | 0.36%   |
| DragonFly   | 1        | 0.36%   |
| ClonOS      | 1        | 0.36%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| amd64  | 241      | 89.93%  |
| i386   | 11       | 4.1%    |
| arm64  | 11       | 4.1%    |
| arm    | 2        | 0.75%   |
| macppc | 1        | 0.37%   |
| evbarm | 1        | 0.37%   |
| armv7  | 1        | 0.37%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 121      | 43.53%  |
| helloDesktop | 63       | 22.66%  |
| fvwm         | 19       | 6.83%   |
| KDE5         | 18       | 6.47%   |
| XFCE         | 16       | 5.76%   |
| MATE         | 11       | 3.96%   |
| Openbox      | 10       | 3.6%    |
| TWM          | 7        | 2.52%   |
| GNOME        | 5        | 1.8%    |
| Fluxbox      | 5        | 1.8%    |
| plasma       | 1        | 0.36%   |
| KWin         | 1        | 0.36%   |
| akonadi_newm | 1        | 0.36%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 141      | 52.03%  |
| Console | 130      | 47.97%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 175      | 64.34%  |
| SLiM    | 66       | 24.26%  |
| SDDM    | 17       | 6.25%   |
| LightDM | 7        | 2.57%   |
| XDM     | 4        | 1.47%   |
| GDM     | 3        | 1.1%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang           | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 98       | 34.63%  |
| ru_RU          | 79       | 27.92%  |
| en_US          | 70       | 24.73%  |
| C              | 33       | 11.66%  |
| ru_RU.KOI8-R   | 2        | 0.71%   |
| cv_RU.US-ASCII | 1        | 0.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 164      | 59.85%  |
| BIOS | 110      | 40.15%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Zfs     | 116      | 42.65%  |
| Ufs     | 92       | 33.82%  |
| Ffs     | 41       | 15.07%  |
| Cd9660  | 22       | 8.09%   |
| Hammer2 | 1        | 0.37%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 214      | 79.55%  |
| MBR     | 53       | 19.7%   |
| Unknown | 2        | 0.74%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 68       | 25.37%  |
| Gigabyte Technology | 47       | 17.54%  |
| ASRock              | 31       | 11.57%  |
| Unknown             | 25       | 9.33%   |
| MSI                 | 16       | 5.97%   |
| Intel               | 11       | 4.1%    |
| Hewlett-Packard     | 9        | 3.36%   |
| Supermicro          | 7        | 2.61%   |
| Pegatron            | 7        | 2.61%   |
| Acer                | 6        | 2.24%   |
| Lenovo              | 5        | 1.87%   |
| Dell                | 5        | 1.87%   |
| PC Engines          | 3        | 1.12%   |
| Huanan              | 3        | 1.12%   |
| Fujitsu             | 2        | 0.75%   |
| Foxconn             | 2        | 0.75%   |
| YANYU               | 1        | 0.37%   |
| Techvision          | 1        | 0.37%   |
| Sony                | 1        | 0.37%   |
| Shuttle             | 1        | 0.37%   |
| Radxa               | 1        | 0.37%   |
| QIYIDA              | 1        | 0.37%   |
| NITRINOnet          | 1        | 0.37%   |
| MW                  | 1        | 0.37%   |
| Maxtang             | 1        | 0.37%   |
| Kraftway            | 1        | 0.37%   |
| Kontron             | 1        | 0.37%   |
| KOHJINSHA           | 1        | 0.37%   |
| khadas              | 1        | 0.37%   |
| Intel CNCTION-IAF   | 1        | 0.37%   |
| IBM                 | 1        | 0.37%   |
| friendlyelec        | 1        | 0.37%   |
| Firefly             | 1        | 0.37%   |
| ECS                 | 1        | 0.37%   |
| Centerm             | 1        | 0.37%   |
| Biostar             | 1        | 0.37%   |
| Apple               | 1        | 0.37%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                                                  | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Unknown                                                               | 26       | 9.7%    |
| ASUS All Series                                                       | 8        | 2.99%   |
| PC Engines APU2                                                       | 3        | 1.12%   |
| Supermicro SSG-6029P-E1CR12L                                          | 2        | 0.75%   |
| Pegatron SAISHIAT2                                                    | 2        | 0.75%   |
| MSI MS-7817                                                           | 2        | 0.75%   |
| Intel X79 V2.72A                                                      | 2        | 0.75%   |
| Huanan X79 INTEL (INTEL Xeon E5/Corei7 DMI2 - C600/C200 Cipset V2.49P | 2        | 0.75%   |
| HP ProLiant MicroServer                                               | 2        | 0.75%   |
| HP Compaq Pro 6300 SFF                                                | 2        | 0.75%   |
| Gigabyte Z68XP-UD3                                                    | 2        | 0.75%   |
| Gigabyte M68MT-S2P                                                    | 2        | 0.75%   |
| Gigabyte H61M-DS2                                                     | 2        | 0.75%   |
| Gigabyte H310M S2 2.0                                                 | 2        | 0.75%   |
| Gigabyte GA-IMB370TN                                                  | 2        | 0.75%   |
| Gigabyte C1037UN-EU                                                   | 2        | 0.75%   |
| Gigabyte B450 AORUS M                                                 | 2        | 0.75%   |
| Gigabyte A320M-H                                                      | 2        | 0.75%   |
| Dell OptiPlex 7040                                                    | 2        | 0.75%   |
| ASUS PRIME Z590-P                                                     | 2        | 0.75%   |
| ASUS PRIME X370-PRO                                                   | 2        | 0.75%   |
| ASUS PRIME B550-PLUS                                                  | 2        | 0.75%   |
| ASUS P8Z77-V LX                                                       | 2        | 0.75%   |
| ASUS P6T SE                                                           | 2        | 0.75%   |
| ASUS P4P800-VM                                                        | 2        | 0.75%   |
| ASRock J4205-ITX                                                      | 2        | 0.75%   |
| YANYU H67SL                                                           | 1        | 0.37%   |
| Techvision TVI7309X                                                   | 1        | 0.37%   |
| Supermicro SYS-6028R-TRT                                              | 1        | 0.37%   |
| Supermicro SYS-5019S-L                                                | 1        | 0.37%   |
| Supermicro SYS-5019A-FTN4                                             | 1        | 0.37%   |
| Supermicro SSG-6028R-E1CR12T                                          | 1        | 0.37%   |
| Supermicro NSM5200-06-EU                                              | 1        | 0.37%   |
| Sony VPCL22Z1R                                                        | 1        | 0.37%   |
| Shuttle DS20U                                                         | 1        | 0.37%   |
| Radxa rock-pi-4                                                       | 1        | 0.37%   |
| QIYIDA X99-H9 V2.0                                                    | 1        | 0.37%   |
| Pegatron SKLD4-P1                                                     | 1        | 0.37%   |
| Pegatron SAISHIAT                                                     | 1        | 0.37%   |
| Pegatron Pro 3010 Microtower PC                                       | 1        | 0.37%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown                      | 26       | 9.7%    |
| ASUS PRIME                   | 9        | 3.36%   |
| ASUS All                     | 8        | 2.99%   |
| Lenovo ThinkCentre           | 4        | 1.49%   |
| HP ProLiant                  | 4        | 1.49%   |
| HP Compaq                    | 4        | 1.49%   |
| Dell OptiPlex                | 4        | 1.49%   |
| PC Engines APU2              | 3        | 1.12%   |
| ASUS ROG                     | 3        | 1.12%   |
| ASUS P5Q                     | 3        | 1.12%   |
| ASRock X570                  | 3        | 1.12%   |
| Acer Aspire                  | 3        | 1.12%   |
| Supermicro SSG-6029P-E1CR12L | 2        | 0.75%   |
| Pegatron SAISHIAT2           | 2        | 0.75%   |
| MSI MS-7817                  | 2        | 0.75%   |
| Intel X79                    | 2        | 0.75%   |
| Huanan X79                   | 2        | 0.75%   |
| Gigabyte Z68XP-UD3           | 2        | 0.75%   |
| Gigabyte M68MT-S2P           | 2        | 0.75%   |
| Gigabyte H61M-DS2            | 2        | 0.75%   |
| Gigabyte H310M               | 2        | 0.75%   |
| Gigabyte GA-IMB370TN         | 2        | 0.75%   |
| Gigabyte C1037UN-EU          | 2        | 0.75%   |
| Gigabyte B450                | 2        | 0.75%   |
| Gigabyte A320M-H             | 2        | 0.75%   |
| Gigabyte 970A-DS3P           | 2        | 0.75%   |
| Fujitsu ESPRIMO              | 2        | 0.75%   |
| ASUS TUF                     | 2        | 0.75%   |
| ASUS P8Z77-V                 | 2        | 0.75%   |
| ASUS P8H77-V                 | 2        | 0.75%   |
| ASUS P7H55-M                 | 2        | 0.75%   |
| ASUS P6T                     | 2        | 0.75%   |
| ASUS P5B                     | 2        | 0.75%   |
| ASUS P4P800-VM               | 2        | 0.75%   |
| ASRock J4205-ITX             | 2        | 0.75%   |
| ASRock H110M-DGS             | 2        | 0.75%   |
| Acer Revo                    | 2        | 0.75%   |
| YANYU H67SL                  | 1        | 0.37%   |
| Techvision TVI7309X          | 1        | 0.37%   |
| Supermicro SYS-6028R-TRT     | 1        | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 28       | 10.45%  |
| 2019    | 27       | 10.07%  |
| 2021    | 21       | 7.84%   |
| 2020    | 18       | 6.72%   |
| 2013    | 18       | 6.72%   |
| 2014    | 16       | 5.97%   |
| 2011    | 16       | 5.97%   |
| 2009    | 16       | 5.97%   |
| 2012    | 15       | 5.6%    |
| 2010    | 15       | 5.6%    |
| Unknown | 15       | 5.6%    |
| 2008    | 11       | 4.1%    |
| 2017    | 10       | 3.73%   |
| 2007    | 9        | 3.36%   |
| 2016    | 8        | 2.99%   |
| 2015    | 8        | 2.99%   |
| 2022    | 6        | 2.24%   |
| 2005    | 5        | 1.87%   |
| 2006    | 4        | 1.49%   |
| 2004    | 2        | 0.75%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 268      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 265      | 98.88%  |
| Yes  | 3        | 1.12%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 64       | 23.7%   |
| 8.01-16.0   | 59       | 21.85%  |
| 16.01-24.0  | 53       | 19.63%  |
| 32.01-64.0  | 26       | 9.63%   |
| 2.01-3.0    | 25       | 9.26%   |
| 3.01-4.0    | 13       | 4.81%   |
| 64.01-256.0 | 10       | 3.7%    |
| 0.51-1.0    | 9        | 3.33%   |
| 24.01-32.0  | 5        | 1.85%   |
| 1.01-2.0    | 3        | 1.11%   |
| 0.01-0.5    | 3        | 1.11%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 142      | 50.9%   |
| 0.51-1.0   | 66       | 23.66%  |
| 1.01-2.0   | 29       | 10.39%  |
| 3.01-4.0   | 9        | 3.23%   |
| 8.01-16.0  | 7        | 2.51%   |
| Unknown    | 7        | 2.51%   |
| 4.01-8.0   | 5        | 1.79%   |
| 2.01-3.0   | 4        | 1.43%   |
| 16.01-24.0 | 4        | 1.43%   |
| 0          | 4        | 1.43%   |
| 24.01-32.0 | 2        | 0.72%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 116      | 40.99%  |
| 2      | 64       | 22.61%  |
| 3      | 30       | 10.6%   |
| 4      | 26       | 9.19%   |
| 0      | 23       | 8.13%   |
| 5      | 11       | 3.89%   |
| 6      | 5        | 1.77%   |
| 7      | 4        | 1.41%   |
| 19     | 1        | 0.35%   |
| 14     | 1        | 0.35%   |
| 9      | 1        | 0.35%   |
| 8      | 1        | 0.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 225      | 82.42%  |
| Yes       | 48       | 17.58%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 250      | 93.28%  |
| No        | 18       | 6.72%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 214      | 79.55%  |
| Yes       | 55       | 20.45%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 238      | 88.81%  |
| Yes       | 30       | 11.19%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Russia  | 268      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Moscow              | 85       | 30.36%  |
| St Petersburg       | 25       | 8.93%   |
| Krasnodar           | 13       | 4.64%   |
| Yekaterinburg       | 10       | 3.57%   |
| Novosibirsk         | 8        | 2.86%   |
| Chelyabinsk         | 7        | 2.5%    |
| Barnaul             | 7        | 2.5%    |
| Vladivostok         | 6        | 2.14%   |
| Ozersk              | 6        | 2.14%   |
| Surgut              | 5        | 1.79%   |
| Kamensk-Ural'skiy   | 5        | 1.79%   |
| Omsk                | 4        | 1.43%   |
| Krasnoyarsk         | 4        | 1.43%   |
| Voronezh            | 3        | 1.07%   |
| Volgograd           | 3        | 1.07%   |
| Ufa                 | 3        | 1.07%   |
| Podolsk             | 3        | 1.07%   |
| Orenburg            | 3        | 1.07%   |
| Nizhniy Novgorod    | 3        | 1.07%   |
| Lipetsk             | 3        | 1.07%   |
| Khimki              | 3        | 1.07%   |
| Irkutsk             | 3        | 1.07%   |
| Volzhskiy           | 2        | 0.71%   |
| Vidnoye             | 2        | 0.71%   |
| Ulyanovsk           | 2        | 0.71%   |
| Tambov              | 2        | 0.71%   |
| Stavropol           | 2        | 0.71%   |
| Saratov             | 2        | 0.71%   |
| Reutov              | 2        | 0.71%   |
| Perm                | 2        | 0.71%   |
| Orsk                | 2        | 0.71%   |
| Obninsk             | 2        | 0.71%   |
| Murmansk            | 2        | 0.71%   |
| Izhevsk             | 2        | 0.71%   |
| Armavir             | 2        | 0.71%   |
| Zhukovskiy          | 1        | 0.36%   |
| Yegor'yevsk         | 1        | 0.36%   |
| Vostochnoe Degunino | 1        | 0.36%   |
| Voskresensk         | 1        | 0.36%   |
| Vladimir            | 1        | 0.36%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor                             | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC                                | 80       | 147    | 20.3%   |
| Seagate                            | 80       | 192    | 20.3%   |
| Samsung Electronics                | 41       | 63     | 10.41%  |
| Toshiba                            | 26       | 57     | 6.6%    |
| Kingston                           | 24       | 26     | 6.09%   |
| Hitachi                            | 19       | 52     | 4.82%   |
| Intel                              | 14       | 19     | 3.55%   |
| Crucial                            | 12       | 18     | 3.05%   |
| A-DATA Technology                  | 7        | 11     | 1.78%   |
| SPCC                               | 6        | 7      | 1.52%   |
| Smartbuy                           | 5        | 5      | 1.27%   |
| SanDisk                            | 5        | 6      | 1.27%   |
| Plextor                            | 5        | 8      | 1.27%   |
| OPENBSD                            | 5        | 11     | 1.27%   |
| OCZ                                | 5        | 5      | 1.27%   |
| Maxtor                             | 5        | 5      | 1.27%   |
| HGST                               | 5        | 14     | 1.27%   |
| Silicon Motion                     | 4        | 5      | 1.02%   |
| AMD                                | 4        | 5      | 1.02%   |
| Patriot                            | 3        | 3      | 0.76%   |
| Kston                              | 3        | 3      | 0.76%   |
| KingSpec                           | 3        | 5      | 0.76%   |
| Apacer                             | 3        | 3      | 0.76%   |
| XPG                                | 2        | 2      | 0.51%   |
| Verbatim                           | 2        | 2      | 0.51%   |
| NVMe                               | 2        | 6      | 0.51%   |
| Micron Technology                  | 2        | 4      | 0.51%   |
| Hoodisk                            | 2        | 4      | 0.51%   |
| GOODRAM                            | 2        | 2      | 0.51%   |
| Fujitsu                            | 2        | 3      | 0.51%   |
| XUNZHE                             | 1        | 1      | 0.25%   |
| Transcend                          | 1        | 1      | 0.25%   |
| Qumo                               | 1        | 1      | 0.25%   |
| Product:              USB DISK 2.0 | 1        | 1      | 0.25%   |
| Netac                              | 1        | 1      | 0.25%   |
| MaxDigital                         | 1        | 1      | 0.25%   |
| LITEON                             | 1        | 1      | 0.25%   |
| KIOXIA                             | 1        | 1      | 0.25%   |
| KingDian                           | 1        | 3      | 0.25%   |
| Kingchuxing                        | 1        | 1      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB             | 6        | 1.27%   |
| WDC WDS240G2G0A-00JH30 240GB       | 5        | 1.06%   |
| Seagate ST1000DM010-2EP102 1TB     | 5        | 1.06%   |
| OPENBSD SR RAID 1 1TB              | 5        | 1.06%   |
| Kingston SA400S37240G 240GB        | 5        | 1.06%   |
| WDC WD20EARX-00PASB0 2TB           | 4        | 0.85%   |
| Seagate ST3300657SS 304GB          | 4        | 0.85%   |
| Seagate ST250DM000-1BD141 250GB    | 4        | 0.85%   |
| Samsung SSD 970 EVO Plus 250GB     | 4        | 0.85%   |
| WDC WD6400AARS-00Y5B1 640GB        | 3        | 0.64%   |
| WDC WD1002FAEX-00Y9A0 1TB          | 3        | 0.64%   |
| Toshiba DT01ACA050 500GB           | 3        | 0.64%   |
| Seagate ST500DM002-1BD142 500GB    | 3        | 0.64%   |
| Seagate ST380815AS 80GB            | 3        | 0.64%   |
| Seagate ST3500413AS 500GB          | 3        | 0.64%   |
| Seagate ST3250318AS 250GB          | 3        | 0.64%   |
| Seagate ST2000DM008-2FR102 2TB     | 3        | 0.64%   |
| Seagate ST2000DM001-1CH164 2TB     | 3        | 0.64%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3        | 0.64%   |
| Samsung SSD 860 EVO 500GB          | 3        | 0.64%   |
| Samsung HD161HJ 160GB              | 3        | 0.64%   |
| Kston SSD 128GB                    | 3        | 0.64%   |
| Kingston SA400S37120G 120GB        | 3        | 0.64%   |
| Kingston SA2000M8500G 500GB        | 3        | 0.64%   |
| A-DATA SU650 120GB                 | 3        | 0.64%   |
| WDC WDS500G1B0A-00H9H0 500GB       | 2        | 0.42%   |
| WDC WDS120G2G0A-00JH30 120GB       | 2        | 0.42%   |
| WDC WD5003AZEX-00K1GA0 500GB       | 2        | 0.42%   |
| WDC WD5000LPLX-00ZNTT0 500GB       | 2        | 0.42%   |
| WDC WD5000AZLX-00K2TA0 500GB       | 2        | 0.42%   |
| WDC WD40EFRX-68N32N0 4TB           | 2        | 0.42%   |
| WDC WD20EZRZ-00Z5HB0 2TB           | 2        | 0.42%   |
| WDC WD2000JS-55MHB0 192GB          | 2        | 0.42%   |
| WDC WD15EADS-00P8B0 1.5TB          | 2        | 0.42%   |
| WDC WD10EZRX-00A8LB0 1TB           | 2        | 0.42%   |
| WDC WD10EZEX-21M2NA0 1TB           | 2        | 0.42%   |
| WDC WD10EZEX-08WN4A0 1TB           | 2        | 0.42%   |
| WDC WD10EALX-009BA0 1TB            | 2        | 0.42%   |
| WDC WD1002FAEX-00Z3A0 1TB          | 2        | 0.42%   |
| Verbatim Vi550 S3 SSD 512GB        | 2        | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                             | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| Seagate                            | 80       | 192    | 35.4%   |
| WDC                                | 69       | 131    | 30.53%  |
| Toshiba                            | 25       | 56     | 11.06%  |
| Hitachi                            | 19       | 52     | 8.41%   |
| Samsung Electronics                | 10       | 14     | 4.42%   |
| OPENBSD                            | 5        | 11     | 2.21%   |
| Maxtor                             | 5        | 5      | 2.21%   |
| HGST                               | 5        | 14     | 2.21%   |
| NVMe                               | 2        | 6      | 0.88%   |
| Fujitsu                            | 2        | 3      | 0.88%   |
| Product:              USB DISK 2.0 | 1        | 1      | 0.44%   |
| MaxDigital                         | 1        | 1      | 0.44%   |
| IBM                                | 1        | 1      | 0.44%   |
| Hewlett-Packard                    | 1        | 4      | 0.44%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 22       | 27     | 15.38%  |
| Kingston            | 20       | 22     | 13.99%  |
| WDC                 | 11       | 11     | 7.69%   |
| Intel               | 11       | 14     | 7.69%   |
| Crucial             | 11       | 17     | 7.69%   |
| A-DATA Technology   | 7        | 10     | 4.9%    |
| SPCC                | 5        | 6      | 3.5%    |
| Smartbuy            | 5        | 5      | 3.5%    |
| SanDisk             | 5        | 6      | 3.5%    |
| Plextor             | 5        | 8      | 3.5%    |
| OCZ                 | 5        | 5      | 3.5%    |
| AMD                 | 4        | 5      | 2.8%    |
| Patriot             | 3        | 3      | 2.1%    |
| Kston               | 3        | 3      | 2.1%    |
| KingSpec            | 3        | 5      | 2.1%    |
| Apacer              | 3        | 3      | 2.1%    |
| Verbatim            | 2        | 2      | 1.4%    |
| Micron Technology   | 2        | 4      | 1.4%    |
| Hoodisk             | 2        | 4      | 1.4%    |
| XUNZHE              | 1        | 1      | 0.7%    |
| XPG                 | 1        | 1      | 0.7%    |
| Transcend           | 1        | 1      | 0.7%    |
| Toshiba             | 1        | 1      | 0.7%    |
| Qumo                | 1        | 1      | 0.7%    |
| Netac               | 1        | 1      | 0.7%    |
| LITEON              | 1        | 1      | 0.7%    |
| KingDian            | 1        | 3      | 0.7%    |
| Kingchuxing         | 1        | 1      | 0.7%    |
| Goodram             | 1        | 1      | 0.7%    |
| GK                  | 1        | 1      | 0.7%    |
| Gigabyte Technology | 1        | 1      | 0.7%    |
| China               | 1        | 1      | 0.7%    |
| AEGO                | 1        | 1      | 0.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 168      | 491    | 51.69%  |
| SSD  | 126      | 176    | 38.77%  |
| NVMe | 31       | 47     | 9.54%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 239      | 667    | 88.52%  |
| NVMe | 31       | 47     | 11.48%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 202      | 332    | 60.3%   |
| 0.51-1.0   | 73       | 134    | 21.79%  |
| 1.01-2.0   | 27       | 118    | 8.06%   |
| 3.01-4.0   | 13       | 28     | 3.88%   |
| 4.01-10.0  | 12       | 27     | 3.58%   |
| 2.01-3.0   | 6        | 18     | 1.79%   |
| 10.01-20.0 | 2        | 10     | 0.6%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 82       | 28.98%  |
| 1-20           | 58       | 20.49%  |
| 251-500        | 46       | 16.25%  |
| 51-100         | 36       | 12.72%  |
| 21-50          | 21       | 7.42%   |
| 501-1000       | 16       | 5.65%   |
| More than 3000 | 11       | 3.89%   |
| 1001-2000      | 8        | 2.83%   |
| Unknown        | 3        | 1.06%   |
| 2001-3000      | 2        | 0.71%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 218      | 78.14%  |
| 21-50          | 27       | 9.68%   |
| 101-250        | 8        | 2.87%   |
| 51-100         | 7        | 2.51%   |
| More than 3000 | 5        | 1.79%   |
| 501-1000       | 5        | 1.79%   |
| 2001-3000      | 3        | 1.08%   |
| 1001-2000      | 3        | 1.08%   |
| Unknown        | 3        | 1.08%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB        | 2        | 2      | 2.6%    |
| WDC WD1002FAEX-00Y9A0 1TB           | 2        | 2      | 2.6%    |
| Seagate ST3500413AS 500GB           | 2        | 4      | 2.6%    |
| Seagate ST3320418AS 320GB           | 2        | 2      | 2.6%    |
| Samsung Electronics SSD 870 EVO 1TB | 2        | 6      | 2.6%    |
| Samsung Electronics HD161HJ 160GB   | 2        | 2      | 2.6%    |
| Maxtor STM3320613AS 320GB           | 2        | 2      | 2.6%    |
| Kingston SA400S37120G 120GB         | 2        | 2      | 2.6%    |
| Hitachi HDS721010CLA332 1TB         | 2        | 4      | 2.6%    |
| XPG SX950U 240GB                    | 1        | 1      | 1.3%    |
| WDC WD7501AALS-00E8B0 752GB         | 1        | 1      | 1.3%    |
| WDC WD7500AACS-00ZJB0 752GB         | 1        | 1      | 1.3%    |
| WDC WD60EFRX-68MYMN1 6TB            | 1        | 1      | 1.3%    |
| WDC WD5003AZEX-00MK2A0 500GB        | 1        | 1      | 1.3%    |
| WDC WD5000LPLX-00ZNTT0 500GB        | 1        | 1      | 1.3%    |
| WDC WD5000AZRZ-00HTKB0 500GB        | 1        | 1      | 1.3%    |
| WDC WD5000AZLX-00CL5A0 500GB        | 1        | 1      | 1.3%    |
| WDC WD5000AAKX-00ERMA0 500GB        | 1        | 1      | 1.3%    |
| WDC WD5000AAKS-00V1A0 500GB         | 1        | 1      | 1.3%    |
| WDC WD40EFRX-68N32N0 4TB            | 1        | 3      | 1.3%    |
| WDC WD3200BPVT-22JJ5T0 320GB        | 1        | 1      | 1.3%    |
| WDC WD3200BEVT-00A0RT0 233GB        | 1        | 1      | 1.3%    |
| WDC WD20EURX-63T0FY0 2TB            | 1        | 1      | 1.3%    |
| WDC WD20EFRX-68EUZN0 2TB            | 1        | 2      | 1.3%    |
| WDC WD1600BEVT-22ZCT0 160GB         | 1        | 1      | 1.3%    |
| WDC WD15EARS-00Z5B1 1.5TB           | 1        | 1      | 1.3%    |
| WDC WD15EADS-00P8B0 1.5TB           | 1        | 1      | 1.3%    |
| WDC WD1002FAEX-00Z3A0 1TB           | 1        | 1      | 1.3%    |
| Toshiba MK2002TSKB 2TB              | 1        | 1      | 1.3%    |
| Toshiba HDWD105 500GB               | 1        | 2      | 1.3%    |
| Toshiba DT01ACA050 500GB            | 1        | 2      | 1.3%    |
| SPCC M.2 SSD 256GB                  | 1        | 1      | 1.3%    |
| Seagate ST9500325AS 500GB           | 1        | 1      | 1.3%    |
| Seagate ST9120822AS 120GB           | 1        | 1      | 1.3%    |
| Seagate ST500DM002-1BD142 500GB     | 1        | 1      | 1.3%    |
| Seagate ST3750640NS 752GB           | 1        | 6      | 1.3%    |
| Seagate ST3500514NS 500GB           | 1        | 1      | 1.3%    |
| Seagate ST3250410AS 250GB           | 1        | 1      | 1.3%    |
| Seagate ST3250310AS 250GB           | 1        | 1      | 1.3%    |
| Seagate ST320410A 20GB              | 1        | 1      | 1.3%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 20       | 29     | 27.03%  |
| WDC                 | 19       | 25     | 25.68%  |
| Samsung Electronics | 8        | 13     | 10.81%  |
| Hitachi             | 6        | 10     | 8.11%   |
| Kingston            | 5        | 5      | 6.76%   |
| Maxtor              | 4        | 4      | 5.41%   |
| Toshiba             | 3        | 5      | 4.05%   |
| Intel               | 3        | 3      | 4.05%   |
| XPG                 | 1        | 1      | 1.35%   |
| SPCC                | 1        | 1      | 1.35%   |
| Plextor             | 1        | 1      | 1.35%   |
| GK                  | 1        | 1      | 1.35%   |
| AMD                 | 1        | 2      | 1.35%   |
| A-DATA Technology   | 1        | 1      | 1.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 20       | 29     | 36.36%  |
| WDC                 | 17       | 23     | 30.91%  |
| Hitachi             | 6        | 10     | 10.91%  |
| Samsung Electronics | 5        | 6      | 9.09%   |
| Maxtor              | 4        | 4      | 7.27%   |
| Toshiba             | 3        | 5      | 5.45%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 53       | 77     | 74.65%  |
| SSD  | 18       | 24     | 25.35%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                        | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| WDC WD6400AARS-00Y5B1 640GB  | 1        | 2      | 33.33%  |
| Toshiba MG05ACA800E 8TB      | 1        | 1      | 33.33%  |
| Crucial M4-CT256M4SSD1 256GB | 1        | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 2      | 33.33%  |
| Toshiba | 1        | 1      | 33.33%  |
| Crucial | 1        | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 212      | 557    | 69.97%  |
| Malfunc  | 68       | 101    | 22.44%  |
| Detected | 20       | 52     | 6.6%    |
| Failed   | 3        | 4      | 0.99%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 188      | 55.29%  |
| AMD                              | 52       | 15.29%  |
| Samsung Electronics              | 16       | 4.71%   |
| Marvell Technology Group         | 13       | 3.82%   |
| ASMedia Technology               | 11       | 3.24%   |
| Silicon Motion                   | 9        | 2.65%   |
| Nvidia                           | 9        | 2.65%   |
| JMicron Technology               | 9        | 2.65%   |
| Broadcom / LSI                   | 5        | 1.47%   |
| Kingston Technology Company      | 4        | 1.18%   |
| Areca Technology                 | 4        | 1.18%   |
| SanDisk                          | 3        | 0.88%   |
| ADATA Technology                 | 3        | 0.88%   |
| Toshiba                          | 2        | 0.59%   |
| Silicon Image                    | 2        | 0.59%   |
| VIA Technologies                 | 1        | 0.29%   |
| Silicon Integrated Systems [SiS] | 1        | 0.29%   |
| Realtek Semiconductor            | 1        | 0.29%   |
| Phison Electronics               | 1        | 0.29%   |
| Micron/Crucial Technology        | 1        | 0.29%   |
| Lite-On Technology               | 1        | 0.29%   |
| Lite-On IT Corp. / Plextor       | 1        | 0.29%   |
| KIOXIA                           | 1        | 0.29%   |
| Integrated Technology Express    | 1        | 0.29%   |
| 3ware                            | 1        | 0.29%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 31       | 7.54%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 18       | 4.38%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 15       | 3.65%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 14       | 3.41%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 14       | 3.41%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 14       | 3.41%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 13       | 3.16%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 12       | 2.92%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 11       | 2.68%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 10       | 2.43%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 9        | 2.19%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 9        | 2.19%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 9        | 2.19%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 8        | 1.95%   |
| AMD 400 Series Chipset SATA Controller                                         | 8        | 1.95%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 7        | 1.7%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 7        | 1.7%    |
| JMicron JMB363 SATA/IDE Controller                                             | 6        | 1.46%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6        | 1.46%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 6        | 1.46%   |
| Nvidia MCP61 SATA Controller                                                   | 5        | 1.22%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 5        | 1.22%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4        | 0.97%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4        | 0.97%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 4        | 0.97%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 4        | 0.97%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 4        | 0.97%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]            | 4        | 0.97%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                   | 4        | 0.97%   |
| Intel 82801EB (ICH5) SATA Controller                                           | 4        | 0.97%   |
| Areca ARC-1300ix-16 16-Port PCI-Express to SAS Non-RAID Host Adapter           | 4        | 0.97%   |
| AMD 500 Series Chipset SATA Controller                                         | 4        | 0.97%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 3        | 0.73%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3        | 0.73%   |
| Nvidia MCP61 IDE                                                               | 3        | 0.73%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 3        | 0.73%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                          | 3        | 0.73%   |
| Kingston Company A2000 NVMe SSD                                                | 3        | 0.73%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3        | 0.73%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 3        | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 201      | 61.47%  |
| IDE  | 68       | 20.8%   |
| NVMe | 45       | 13.76%  |
| RAID | 6        | 1.83%   |
| SCSI | 4        | 1.22%   |
| SAS  | 3        | 0.92%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 193      | 71.48%  |
| AMD     | 60       | 22.22%  |
| ARM     | 12       | 4.44%   |
| Unknown | 4        | 1.48%   |
| PowerPC | 1        | 0.37%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor       | 5        | 1.82%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 4        | 1.46%   |
| Intel Celeron CPU J1900 @ 1.99GHz       | 4        | 1.46%   |
| ARM Cortex-A57 r1p3                     | 4        | 1.46%   |
|                                         | 4        | 1.46%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz  | 3        | 1.09%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 3        | 1.09%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 3        | 1.09%   |
| Intel Core i3-3220 CPU @ 3.30GHz        | 3        | 1.09%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz   | 3        | 1.09%   |
| Intel Celeron J4125 CPU @ 2.00GHz       | 3        | 1.09%   |
| Intel Celeron CPU J3455 @ 1.50GHz       | 3        | 1.09%   |
| Intel Celeron CPU 1037U @ 1.80GHz       | 3        | 1.09%   |
| ARM Cortex-A55 r2p0                     | 3        | 1.09%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 3        | 1.09%   |
| AMD Ryzen 5 2600 Six-Core Processor     | 3        | 1.09%   |
| AMD GX-412TC SOC                        | 3        | 1.09%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz     | 2        | 0.73%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz     | 2        | 0.73%   |
| Intel Xeon CPU E31270 @ 3.40GHz         | 2        | 0.73%   |
| Intel Xeon CPU E3-1265L V2 @ 2.50GHz    | 2        | 0.73%   |
| Intel Xeon Bronze 3104 CPU @ 1.70GHz    | 2        | 0.73%   |
| Intel Pentium Gold G5400T CPU @ 3.10GHz | 2        | 0.73%   |
| Intel Pentium CPU J4205 @ 1.50GHz       | 2        | 0.73%   |
| Intel Pentium 4 CPU                     | 2        | 0.73%   |
| Intel Core i7-4770 CPU @ 3.40GHz        | 2        | 0.73%   |
| Intel Core i7-2600K CPU @ 3.40GHz       | 2        | 0.73%   |
| Intel Core i7 CPU 920 @ 2.67GHz         | 2        | 0.73%   |
| Intel Core i7 CPU                       | 2        | 0.73%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 2        | 0.73%   |
| Intel Core i5-7400 CPU @ 3.00GHz        | 2        | 0.73%   |
| Intel Core i5-3570K CPU @ 3.40GHz       | 2        | 0.73%   |
| Intel Core i5-10500 CPU @ 3.10GHz       | 2        | 0.73%   |
| Intel Core i5-10400 CPU @ 2.90GHz       | 2        | 0.73%   |
| Intel Core i3-6100 CPU @ 3.70GHz        | 2        | 0.73%   |
| Intel Core i3-4170 CPU @ 3.70GHz        | 2        | 0.73%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz   | 2        | 0.73%   |
| Intel Core 2 Quad CPU                   | 2        | 0.73%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz    | 2        | 0.73%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz    | 2        | 0.73%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Celeron           | 33       | 12.18%  |
| Intel Core i5           | 29       | 10.7%   |
| Intel Xeon              | 23       | 8.49%   |
| Intel Core i7           | 21       | 7.75%   |
| Intel Core i3           | 16       | 5.9%    |
| AMD Ryzen 5             | 13       | 4.8%    |
| ARM Cortex              | 12       | 4.43%   |
| Intel Core 2 Quad       | 10       | 3.69%   |
| Intel Core 2 Duo        | 10       | 3.69%   |
| Other                   | 8        | 2.95%   |
| Intel Atom              | 8        | 2.95%   |
| Intel Pentium 4         | 7        | 2.58%   |
| Intel Pentium           | 7        | 2.58%   |
| AMD Ryzen 7             | 7        | 2.58%   |
| Intel Pentium Gold      | 5        | 1.85%   |
| Intel Pentium Dual-Core | 4        | 1.48%   |
| AMD FX                  | 4        | 1.48%   |
| Intel Pentium Dual      | 3        | 1.11%   |
| Intel Pentium D         | 3        | 1.11%   |
| Intel Core 2            | 3        | 1.11%   |
| AMD Ryzen 9             | 3        | 1.11%   |
| AMD GX                  | 3        | 1.11%   |
| AMD Athlon 64 X2        | 3        | 1.11%   |
| Intel Xeon Bronze       | 2        | 0.74%   |
| Intel Core i9           | 2        | 0.74%   |
| Intel 686-class         | 2        | 0.74%   |
| AMD Turion II Neo       | 2        | 0.74%   |
| AMD Ryzen 5 PRO         | 2        | 0.74%   |
| AMD Phenom II X6        | 2        | 0.74%   |
| AMD Phenom              | 2        | 0.74%   |
| AMD E                   | 2        | 0.74%   |
| AMD Athlon X4           | 2        | 0.74%   |
| AMD Athlon II X3        | 2        | 0.74%   |
| AMD A10                 | 2        | 0.74%   |
| Intel Pentium Silver    | 1        | 0.37%   |
| Intel Genuine           | 1        | 0.37%   |
| Intel Celeron D         | 1        | 0.37%   |
| AMD Sempron             | 1        | 0.37%   |
| AMD Ryzen 3 PRO         | 1        | 0.37%   |
| AMD Ryzen 3             | 1        | 0.37%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 85       | 31.37%  |
| 2       | 66       | 24.35%  |
| Unknown | 44       | 16.24%  |
| 6       | 27       | 9.96%   |
| 8       | 13       | 4.8%    |
| 1       | 11       | 4.06%   |
| 12      | 10       | 3.69%   |
| 16      | 6        | 2.21%   |
| 24      | 4        | 1.48%   |
| 28      | 2        | 0.74%   |
| 3       | 2        | 0.74%   |
| 14      | 1        | 0.37%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 240      | 88.56%  |
| Unknown | 25       | 9.23%   |
| 2       | 6        | 2.21%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 141      | 51.84%  |
| 2       | 78       | 28.68%  |
| Unknown | 53       | 19.49%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| IvyBridge     | 26       | 9.59%   |
| Unknown       | 25       | 9.23%   |
| Penryn        | 21       | 7.75%   |
| KabyLake      | 21       | 7.75%   |
| SandyBridge   | 20       | 7.38%   |
| Haswell       | 20       | 7.38%   |
| Zen 2         | 14       | 5.17%   |
| Skylake       | 12       | 4.43%   |
| Silvermont    | 11       | 4.06%   |
| NetBurst      | 11       | 4.06%   |
| K10           | 11       | 4.06%   |
| Core          | 11       | 4.06%   |
| Goldmont      | 8        | 2.95%   |
| Zen           | 7        | 2.58%   |
| Piledriver    | 7        | 2.58%   |
| Bonnell       | 7        | 2.58%   |
| Zen+          | 6        | 2.21%   |
| Nehalem       | 5        | 1.85%   |
| CometLake     | 5        | 1.85%   |
| K8 Hammer     | 4        | 1.48%   |
| Goldmont plus | 4        | 1.48%   |
| Puma          | 3        | 1.11%   |
| Broadwell     | 3        | 1.11%   |
| Bobcat        | 3        | 1.11%   |
| Zen 3         | 1        | 0.37%   |
| Westmere      | 1        | 0.37%   |
| Steamroller   | 1        | 0.37%   |
| P6            | 1        | 0.37%   |
| Jaguar        | 1        | 0.37%   |
| Bulldozer     | 1        | 0.37%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 113      | 43.63%  |
| Nvidia                     | 78       | 30.12%  |
| AMD                        | 58       | 22.39%  |
| ASPEED Technology          | 7        | 2.7%    |
| Matrox Electronics Systems | 2        | 0.77%   |
| VIA Technologies           | 1        | 0.39%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 9        | 3.35%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 9        | 3.35%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 7        | 2.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 7        | 2.6%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7        | 2.6%    |
| ASPEED Technology ASPEED Graphics Family                                                 | 7        | 2.6%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 6        | 2.23%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 6        | 2.23%   |
| Intel HD Graphics 530                                                                    | 5        | 1.86%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 5        | 1.86%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5        | 1.86%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 5        | 1.86%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5        | 1.86%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 4        | 1.49%   |
| Intel HD Graphics 500                                                                    | 4        | 1.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4        | 1.49%   |
| Intel 82865G Integrated Graphics Controller                                              | 4        | 1.49%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4        | 1.49%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 3        | 1.12%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 3        | 1.12%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 3        | 1.12%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                                      | 3        | 1.12%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3        | 1.12%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 3        | 1.12%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3        | 1.12%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3        | 1.12%   |
| AMD RV710/M92 [Mobility Radeon HD 4350/4550]                                             | 3        | 1.12%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                                           | 3        | 1.12%   |
| AMD ES1000                                                                               | 3        | 1.12%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 2        | 0.74%   |
| Nvidia NV43 [GeForce 6600]                                                               | 2        | 0.74%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 2        | 0.74%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 2        | 0.74%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 2        | 0.74%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                           | 2        | 0.74%   |
| Nvidia GA102 [GeForce RTX 3080]                                                          | 2        | 0.74%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 2        | 0.74%   |
| Nvidia G86 [GeForce 8500 GT]                                                             | 2        | 0.74%   |
| Nvidia G84 [GeForce 8600 GTS]                                                            | 2        | 0.74%   |
| Nvidia G73 [GeForce 7600 GS]                                                             | 2        | 0.74%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 100      | 36.9%   |
| 1 x Nvidia     | 73       | 26.94%  |
| 1 x AMD        | 47       | 17.34%  |
| Other          | 20       | 7.38%   |
| 2 x AMD        | 7        | 2.58%   |
| 1 x ASPEED     | 7        | 2.58%   |
| 2 x Intel      | 6        | 2.21%   |
| Intel + AMD    | 4        | 1.48%   |
| Intel + Nvidia | 3        | 1.11%   |
| 1 x Matrox     | 2        | 0.74%   |
| 1 x VIA        | 1        | 0.37%   |
| AMD + Nvidia   | 1        | 0.37%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 198      | 72.79%  |
| Proprietary | 49       | 18.01%  |
| Unknown     | 25       | 9.19%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 200      | 73.53%  |
| 1.01-2.0   | 19       | 6.99%   |
| 0.51-1.0   | 14       | 5.15%   |
| 3.01-4.0   | 13       | 4.78%   |
| 0.01-0.5   | 9        | 3.31%   |
| 5.01-6.0   | 7        | 2.57%   |
| 7.01-8.0   | 6        | 2.21%   |
| 8.01-16.0  | 3        | 1.1%    |
| 2.01-3.0   | 1        | 0.37%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 29       | 23.39%  |
| Goldstar             | 19       | 15.32%  |
| Dell                 | 13       | 10.48%  |
| Philips              | 9        | 7.26%   |
| Ancor Communications | 9        | 7.26%   |
| ViewSonic            | 8        | 6.45%   |
| Acer                 | 7        | 5.65%   |
| BenQ                 | 5        | 4.03%   |
| AOC                  | 5        | 4.03%   |
| Sony                 | 4        | 3.23%   |
| NEC Computers        | 4        | 3.23%   |
| RTK                  | 2        | 1.61%   |
| Iiyama               | 2        | 1.61%   |
| Hewlett-Packard      | 2        | 1.61%   |
| Fujitsu Siemens      | 2        | 1.61%   |
| Unknown (CDD)        | 1        | 0.81%   |
| Panasonic            | 1        | 0.81%   |
| Lenovo               | 1        | 0.81%   |
| InfoVision           | 1        | 0.81%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Ancor Communications ASUS VW199 ACI19ED 1440x900 410x260mm 19.1-inch   | 4        | 3.05%   |
| ViewSonic LCD Monitor VSCC42B 1920x1080 480x270mm 21.7-inch            | 2        | 1.53%   |
| Samsung Electronics SyncMaster SAM027D 1680x1050 430x270mm 20.0-inch   | 2        | 1.53%   |
| Samsung Electronics SME1920NR SAM06A4 1280x1024 380x300mm 19.1-inch    | 2        | 1.53%   |
| Samsung Electronics SMBX2250 SAM071B 1920x1080 480x270mm 21.7-inch     | 2        | 1.53%   |
| Samsung Electronics S22B300 SAM08AC 1920x1080 480x270mm 21.7-inch      | 2        | 1.53%   |
| Samsung Electronics LCD Monitor SAM0AC6 1920x1080 1110x620mm 50.1-inch | 2        | 1.53%   |
| RTK WCS Display RTK1A1B 1920x1080 344x195mm 15.6-inch                  | 2        | 1.53%   |
| Philips PHL 240V5 PHLC10A 1920x1080 530x300mm 24.0-inch                | 2        | 1.53%   |
| NEC Computers FE791SB NEC61D7 1600x1200 330x240mm 16.1-inch            | 2        | 1.53%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch             | 2        | 1.53%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch              | 2        | 1.53%   |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                      | 2        | 1.53%   |
| ViewSonic VX2458-mhd VSC0437 1920x1080 520x290mm 23.4-inch             | 1        | 0.76%   |
| ViewSonic VP171s-2 VSC4B1B 1280x1024 340x270mm 17.1-inch               | 1        | 0.76%   |
| ViewSonic LCD Monitor VX2451 SERIES 1920x1080                          | 1        | 0.76%   |
| ViewSonic LCD Monitor VSCD22B 1920x1080 520x290mm 23.4-inch            | 1        | 0.76%   |
| ViewSonic LCD Monitor VSC8724 1440x900 410x260mm 19.1-inch             | 1        | 0.76%   |
| ViewSonic LCD Monitor VSC5826 1366x768 410x230mm 18.5-inch             | 1        | 0.76%   |
| ViewSonic LCD Monitor VSC2528 1920x1080 520x290mm 23.4-inch            | 1        | 0.76%   |
| Unknown (CDD) VGA CDD0030 1920x1080 1150x650mm 52.0-inch               | 1        | 0.76%   |
| Sony TV  *00 SNY8204 3840x2160 1220x680mm 55.0-inch                    | 1        | 0.76%   |
| Sony TV  *00 SNY7C04 3840x2160 1080x610mm 48.8-inch                    | 1        | 0.76%   |
| Sony SDM-S75D/F/N SNY3800 1280x1024 340x270mm 17.1-inch                | 1        | 0.76%   |
| Sony SDM-E76D SNYB200 1280x1024 340x270mm 17.1-inch                    | 1        | 0.76%   |
| Samsung Electronics U32H85x SAM0E3C 3840x2160 700x390mm 31.5-inch      | 1        | 0.76%   |
| Samsung Electronics SyncMaster SAM03CF 1280x1024 340x270mm 17.1-inch   | 1        | 0.76%   |
| Samsung Electronics SyncMaster SAM027E 1680x1050 470x300mm 22.0-inch   | 1        | 0.76%   |
| Samsung Electronics SyncMaster SAM026F 1280x1024 380x300mm 19.1-inch   | 1        | 0.76%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x260mm 19.1-inch    | 1        | 0.76%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 430x270mm 20.0-inch   | 1        | 0.76%   |
| Samsung Electronics SyncMaster SAM01BB 1280x1024 380x300mm 19.1-inch   | 1        | 0.76%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 340x270mm 17.1-inch   | 1        | 0.76%   |
| Samsung Electronics SMS23A550H SAM07C9 1920x1080 510x290mm 23.1-inch   | 1        | 0.76%   |
| Samsung Electronics SMB2340 SAM0691 1920x1080 510x290mm 23.1-inch      | 1        | 0.76%   |
| Samsung Electronics SMB2240W SAM0699 1680x1050 470x300mm 22.0-inch     | 1        | 0.76%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 520x290mm 23.4-inch      | 1        | 0.76%   |
| Samsung Electronics S24E650 SAM0CC3 1920x1200 520x320mm 24.0-inch      | 1        | 0.76%   |
| Samsung Electronics S24D332 SAM0F5E 1920x1080 530x300mm 24.0-inch      | 1        | 0.76%   |
| Samsung Electronics S23C570 SAM0A56 1920x1080 510x290mm 23.1-inch      | 1        | 0.76%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 53       | 43.44%  |
| 1280x1024 (SXGA)   | 19       | 15.57%  |
| 3840x2160 (4K)     | 10       | 8.2%    |
| 1920x1200 (WUXGA)  | 8        | 6.56%   |
| 1680x1050 (WSXGA+) | 8        | 6.56%   |
| 1440x900 (WXGA+)   | 7        | 5.74%   |
| 1366x768 (WXGA)    | 5        | 4.1%    |
| 1600x900 (HD+)     | 4        | 3.28%   |
| 2560x1440 (QHD)    | 2        | 1.64%   |
| 1600x1200          | 2        | 1.64%   |
| 3440x1440          | 1        | 0.82%   |
| 2560x1080          | 1        | 0.82%   |
| 1024x768 (XGA)     | 1        | 0.82%   |
| Unknown            | 1        | 0.82%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 19       | 15.2%   |
| 19      | 18       | 14.4%   |
| 24      | 17       | 13.6%   |
| 23      | 12       | 9.6%    |
| 17      | 12       | 9.6%    |
| 27      | 10       | 8%      |
| Unknown | 8        | 6.4%    |
| 18      | 5        | 4%      |
| 22      | 4        | 3.2%    |
| 31      | 3        | 2.4%    |
| 20      | 3        | 2.4%    |
| 50      | 2        | 1.6%    |
| 16      | 2        | 1.6%    |
| 15      | 2        | 1.6%    |
| 57      | 1        | 0.8%    |
| 55      | 1        | 0.8%    |
| 52      | 1        | 0.8%    |
| 48      | 1        | 0.8%    |
| 34      | 1        | 0.8%    |
| 26      | 1        | 0.8%    |
| 14      | 1        | 0.8%    |
| 12      | 1        | 0.8%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 40       | 32.52%  |
| 501-600     | 39       | 31.71%  |
| 301-350     | 16       | 13.01%  |
| 351-400     | 8        | 6.5%    |
| Unknown     | 8        | 6.5%    |
| 1001-1500   | 6        | 4.88%   |
| 601-700     | 3        | 2.44%   |
| 201-300     | 2        | 1.63%   |
| 701-800     | 1        | 0.81%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 71       | 57.72%  |
| 16/10   | 22       | 17.89%  |
| 5/4     | 19       | 15.45%  |
| Unknown | 7        | 5.69%   |
| 4/3     | 3        | 2.44%   |
| 21/9    | 1        | 0.81%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 46       | 36.51%  |
| 151-200        | 22       | 17.46%  |
| 141-150        | 16       | 12.7%   |
| 301-350        | 11       | 8.73%   |
| Unknown        | 8        | 6.35%   |
| 251-300        | 7        | 5.56%   |
| More than 1000 | 6        | 4.76%   |
| 351-500        | 4        | 3.17%   |
| 101-110        | 3        | 2.38%   |
| 121-130        | 2        | 1.59%   |
| 61-70          | 1        | 0.79%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 78       | 63.41%  |
| 101-120 | 20       | 16.26%  |
| 121-160 | 8        | 6.5%    |
| Unknown | 8        | 6.5%    |
| 161-240 | 5        | 4.07%   |
| 1-50    | 4        | 3.25%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 148      | 54.01%  |
| 1     | 116      | 42.34%  |
| 2     | 9        | 3.28%   |
| 3     | 1        | 0.36%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 159      | 46.63%  |
| Intel                             | 96       | 28.15%  |
| Qualcomm Atheros                  | 30       | 8.8%    |
| Broadcom                          | 10       | 2.93%   |
| Marvell Technology Group          | 7        | 2.05%   |
| D-Link System                     | 6        | 1.76%   |
| VIA Technologies                  | 4        | 1.17%   |
| IMC Networks                      | 3        | 0.88%   |
| Huawei Technologies               | 3        | 0.88%   |
| Qualcomm                          | 2        | 0.59%   |
| D-Link                            | 2        | 0.59%   |
| 3Com                              | 2        | 0.59%   |
| ZTE WCDMA Technologies MSM        | 1        | 0.29%   |
| TP-Link                           | 1        | 0.29%   |
| Sundance Technology Inc / IC Plus | 1        | 0.29%   |
| Silicon Integrated Systems [SiS]  | 1        | 0.29%   |
| Ralink Technology                 | 1        | 0.29%   |
| Ralink                            | 1        | 0.29%   |
| Qualcomm Atheros Communications   | 1        | 0.29%   |
| Qcom                              | 1        | 0.29%   |
| Nvidia                            | 1        | 0.29%   |
| MYRICOM                           | 1        | 0.29%   |
| Mercucys                          | 1        | 0.29%   |
| Edimax Technology                 | 1        | 0.29%   |
| Atmel                             | 1        | 0.29%   |
| ASUSTek Computer                  | 1        | 0.29%   |
| Aquantia                          | 1        | 0.29%   |
| Apple                             | 1        | 0.29%   |
| Accton Technology                 | 1        | 0.29%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 139      | 36.01%  |
| Intel I211 Gigabit Network Connection                             | 16       | 4.15%   |
| Intel 82574L Gigabit Network Connection                           | 13       | 3.37%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7        | 1.81%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 6        | 1.55%   |
| Intel I350 Gigabit Network Connection                             | 6        | 1.55%   |
| Intel I210 Gigabit Network Connection                             | 6        | 1.55%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 1.3%    |
| Intel 82579V Gigabit Network Connection                           | 5        | 1.3%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 4        | 1.04%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 4        | 1.04%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 4        | 1.04%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 4        | 1.04%   |
| Intel Ethernet Connection I217-V                                  | 4        | 1.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 1.04%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 4        | 1.04%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 3        | 0.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3        | 0.78%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 3        | 0.78%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 3        | 0.78%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3        | 0.78%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 3        | 0.78%   |
| Intel Wi-Fi 6 AX200                                               | 3        | 0.78%   |
| Intel Ethernet Controller I225-V                                  | 3        | 0.78%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 0.78%   |
| Intel Ethernet Connection (7) I219-LM                             | 3        | 0.78%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 0.78%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 3        | 0.78%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                | 3        | 0.78%   |
| Intel 82562EZ 10/100 Ethernet Controller                          | 3        | 0.78%   |
| Intel 82540EM Gigabit Ethernet Controller                         | 3        | 0.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2        | 0.52%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2        | 0.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2        | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 0.52%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2        | 0.52%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 2        | 0.52%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 2        | 0.52%   |
| Intel Wireless 7265                                               | 2        | 0.52%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 2        | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Qualcomm Atheros                | 16       | 27.59%  |
| Intel                           | 15       | 25.86%  |
| Realtek Semiconductor           | 12       | 20.69%  |
| IMC Networks                    | 3        | 5.17%   |
| D-Link                          | 2        | 3.45%   |
| Broadcom                        | 2        | 3.45%   |
| TP-Link                         | 1        | 1.72%   |
| Ralink Technology               | 1        | 1.72%   |
| Ralink                          | 1        | 1.72%   |
| Qualcomm Atheros Communications | 1        | 1.72%   |
| Qcom                            | 1        | 1.72%   |
| Mercucys                        | 1        | 1.72%   |
| Edimax Technology               | 1        | 1.72%   |
| ASUSTek Computer                | 1        | 1.72%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR9462 Wireless Network Adapter                                     | 4        | 6.9%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 3        | 5.17%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                     | 3        | 5.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                       | 3        | 5.17%   |
| Intel Wi-Fi 6 AX200                                                                  | 3        | 5.17%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                      | 2        | 3.45%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                           | 2        | 3.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 2        | 3.45%   |
| Intel Wireless 7265                                                                  | 2        | 3.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                                      | 2        | 3.45%   |
| IMC Networks Realtek RTL8191SU Wireless LAN 802.11n USB 2.0 Network Adapter          | 2        | 3.45%   |
| TP-Link TP-LINK Wireless USB Adapter                                                 | 1        | 1.72%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                             | 1        | 1.72%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                      | 1        | 1.72%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                               | 1        | 1.72%   |
| Realtek Realtek Bluetooth Adapter                                                    | 1        | 1.72%   |
| Realtek 802.11n WLAN Adapter                                                         | 1        | 1.72%   |
| Ralink RT5370 Wireless Adapter                                                       | 1        | 1.72%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                                 | 1        | 1.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                           | 1        | 1.72%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1        | 1.72%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                       | 1        | 1.72%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                     | 1        | 1.72%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                           | 1        | 1.72%   |
| Qcom RT73 USB Wireless LAN Card                                                      | 1        | 1.72%   |
| Mercucys MERCUSYS Wireless USB Adapter                                               | 1        | 1.72%   |
| Intel Wireless 8260                                                                  | 1        | 1.72%   |
| Intel Wireless 7260                                                                  | 1        | 1.72%   |
| Intel Wireless 3160                                                                  | 1        | 1.72%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 1        | 1.72%   |
| Intel Comet Lake PCH CNVi WiFi                                                       | 1        | 1.72%   |
| Intel Centrino Wireless-N 2230                                                       | 1        | 1.72%   |
| Intel Centrino Wireless-N 2200                                                       | 1        | 1.72%   |
| Intel Centrino Advanced-N 6235                                                       | 1        | 1.72%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                                 | 1        | 1.72%   |
| Edimax EW-7612UAn V2 802.11n Wireless Adapter [Realtek RTL8192CU]                    | 1        | 1.72%   |
| D-Link DWA-140 RangeBooster N Adapter(rev.B3) [Ralink RT5372]                        | 1        | 1.72%   |
| D-Link DWA-125 Wireless N 150 Adapter(rev.B1) [Ralink RT5370]                        | 1        | 1.72%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                   | 1        | 1.72%   |
| Broadcom BCM43228 802.11a/b/g/n                                                      | 1        | 1.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 156      | 52.53%  |
| Intel                             | 88       | 29.63%  |
| Qualcomm Atheros                  | 15       | 5.05%   |
| Broadcom                          | 8        | 2.69%   |
| Marvell Technology Group          | 7        | 2.36%   |
| D-Link System                     | 6        | 2.02%   |
| VIA Technologies                  | 4        | 1.35%   |
| Qualcomm                          | 2        | 0.67%   |
| 3Com                              | 2        | 0.67%   |
| ZTE WCDMA Technologies MSM        | 1        | 0.34%   |
| Sundance Technology Inc / IC Plus | 1        | 0.34%   |
| Silicon Integrated Systems [SiS]  | 1        | 0.34%   |
| Nvidia                            | 1        | 0.34%   |
| MYRICOM                           | 1        | 0.34%   |
| Huawei Technologies               | 1        | 0.34%   |
| Aquantia                          | 1        | 0.34%   |
| Apple                             | 1        | 0.34%   |
| Accton Technology                 | 1        | 0.34%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 139      | 42.9%   |
| Intel I211 Gigabit Network Connection                                         | 16       | 4.94%   |
| Intel 82574L Gigabit Network Connection                                       | 13       | 4.01%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 7        | 2.16%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 6        | 1.85%   |
| Intel I350 Gigabit Network Connection                                         | 6        | 1.85%   |
| Intel I210 Gigabit Network Connection                                         | 6        | 1.85%   |
| Realtek RTL8125 2.5GbE Controller                                             | 5        | 1.54%   |
| Intel 82579V Gigabit Network Connection                                       | 5        | 1.54%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 4        | 1.23%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 4        | 1.23%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 4        | 1.23%   |
| Intel Ethernet Connection I217-V                                              | 4        | 1.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 4        | 1.23%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 4        | 1.23%   |
| VIA VT6105/VT6106S [Rhine-III]                                                | 3        | 0.93%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 3        | 0.93%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 3        | 0.93%   |
| Intel Ethernet Controller I225-V                                              | 3        | 0.93%   |
| Intel Ethernet Connection (7) I219-V                                          | 3        | 0.93%   |
| Intel Ethernet Connection (7) I219-LM                                         | 3        | 0.93%   |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 0.93%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 3        | 0.93%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 3        | 0.93%   |
| Intel 82562EZ 10/100 Ethernet Controller                                      | 3        | 0.93%   |
| Intel 82540EM Gigabit Ethernet Controller                                     | 3        | 0.93%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 2        | 0.62%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 2        | 0.62%   |
| Qualcomm ALCATEL Composite RNDIS Interface                                    | 2        | 0.62%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                             | 2        | 0.62%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 2        | 0.62%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 2        | 0.62%   |
| Intel Ethernet Connection (2) I219-LM                                         | 2        | 0.62%   |
| Intel 82576 Gigabit Network Connection                                        | 2        | 0.62%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2        | 0.62%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 2        | 0.62%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 2        | 0.62%   |
| ZTE WCDMA MSM AT Interface                                                    | 1        | 0.31%   |
| VIA VT6102/VT6103 [Rhine-II]                                                  | 1        | 0.31%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY    | 1        | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 250      | 80.91%  |
| WiFi     | 55       | 17.8%   |
| Unknown  | 3        | 0.97%   |
| Modem    | 1        | 0.32%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 227      | 88.33%  |
| WiFi     | 29       | 11.28%  |
| Unknown  | 1        | 0.39%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 130      | 47.62%  |
| 2     | 73       | 26.74%  |
| 3     | 27       | 9.89%   |
| 0     | 22       | 8.06%   |
| 4     | 14       | 5.13%   |
| 7     | 3        | 1.1%    |
| 9     | 1        | 0.37%   |
| 8     | 1        | 0.37%   |
| 6     | 1        | 0.37%   |
| 5     | 1        | 0.37%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 262      | 96.32%  |
| Yes  | 10       | 3.68%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 15       | 50%     |
| Qualcomm Atheros Communications | 3        | 10%     |
| Realtek Semiconductor           | 2        | 6.67%   |
| IMC Networks                    | 2        | 6.67%   |
| Cambridge Silicon Radio         | 2        | 6.67%   |
| ASUSTek Computer                | 2        | 6.67%   |
| Foxconn / Hon Hai               | 1        | 3.33%   |
| Edimax Technology               | 1        | 3.33%   |
| Broadcom                        | 1        | 3.33%   |
| Bluetooth Device                | 1        | 3.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                          | 5        | 16.67%  |
| Intel AX200 Bluetooth                                       | 4        | 13.33%  |
| Intel Centrino Bluetooth Wireless Transceiver               | 2        | 6.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 2        | 6.67%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2        | 6.67%   |
| Realtek  Bluetooth Adapter                                  | 1        | 3.33%   |
| Realtek  Bluetooth 4.0 Adapter                              | 1        | 3.33%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1        | 3.33%   |
| Qualcomm Atheros Atheros AR9462 Bluetooth 3.0 + HS Adapter  | 1        | 3.33%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1        | 3.33%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1        | 3.33%   |
| Intel AX201 Bluetooth                                       | 1        | 3.33%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip        | 1        | 3.33%   |
| IMC Networks Qualcomm Atheros AR9462 Bluetooth 4.0          | 1        | 3.33%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1        | 3.33%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter     | 1        | 3.33%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter            | 1        | 3.33%   |
| Bluetooth Device Silicon Wave Bluetooth Wireless Adapter    | 1        | 3.33%   |
| ASUS Qualcomm Atheros AR9462 Bluetooth 4.0 + HS Adapter     | 1        | 3.33%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 1        | 3.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 160      | 51.78%  |
| Nvidia                           | 62       | 20.06%  |
| AMD                              | 60       | 19.42%  |
| C-Media Electronics              | 5        | 1.62%   |
| Realtek Semiconductor            | 3        | 0.97%   |
| Logitech                         | 3        | 0.97%   |
| VIA Technologies                 | 2        | 0.65%   |
| JMTek                            | 2        | 0.65%   |
| Creative Labs                    | 2        | 0.65%   |
| Texas Instruments                | 1        | 0.32%   |
| SteelSeries ApS                  | 1        | 0.32%   |
| Silicon Integrated Systems [SiS] | 1        | 0.32%   |
| Samsung Electronics              | 1        | 0.32%   |
| Microsoft                        | 1        | 0.32%   |
| GN Netcom                        | 1        | 0.32%   |
| Generalplus Technology           | 1        | 0.32%   |
| FiiO Electronics Technology      | 1        | 0.32%   |
| ESS Technology                   | 1        | 0.32%   |
| Creative Technology              | 1        | 0.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 22       | 6.38%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 18       | 5.22%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 15       | 4.35%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 13       | 3.77%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 12       | 3.48%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 11       | 3.19%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 11       | 3.19%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 10       | 2.9%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 9        | 2.61%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 9        | 2.61%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 7        | 2.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7        | 2.03%   |
| Intel Cannon Lake PCH cAVS                                                                        | 7        | 2.03%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 7        | 2.03%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 7        | 2.03%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 7        | 2.03%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 6        | 1.74%   |
| Intel 200 Series PCH HD Audio                                                                     | 6        | 1.74%   |
| AMD FCH Azalia Controller                                                                         | 6        | 1.74%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5        | 1.45%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5        | 1.45%   |
| Nvidia High Definition Audio Controller                                                           | 4        | 1.16%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 4        | 1.16%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4        | 1.16%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4        | 1.16%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 4        | 1.16%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 4        | 1.16%   |
| Nvidia MCP61 High Definition Audio                                                                | 3        | 0.87%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 3        | 0.87%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3        | 0.87%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 3        | 0.87%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 3        | 0.87%   |
| Intel Comet Lake PCH cAVS                                                                         | 3        | 0.87%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3        | 0.87%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 3        | 0.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3        | 0.87%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3        | 0.87%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                                              | 3        | 0.87%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 3        | 0.87%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3        | 0.87%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                                  | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Unknown                                 | 64       | 26.02%  |
| Kingston                                | 52       | 21.14%  |
| Samsung Electronics                     | 27       | 10.98%  |
| SK hynix                                | 15       | 6.1%    |
| Crucial                                 | 15       | 6.1%    |
| Micron Technology                       | 9        | 3.66%   |
| Unknown                                 | 8        | 3.25%   |
| Corsair                                 | 7        | 2.85%   |
| Patriot                                 | 6        | 2.44%   |
| AMD                                     | 6        | 2.44%   |
| G.Skill                                 | 5        | 2.03%   |
| Nanya Technology                        | 4        | 1.63%   |
| A-DATA Technology                       | 4        | 1.63%   |
| Goldkey                                 | 3        | 1.22%   |
| Unifosa                                 | 2        | 0.81%   |
| Transcend                               | 2        | 0.81%   |
| Patriot Memory (PDP Systems)            | 2        | 0.81%   |
| Elpida                                  | 2        | 0.81%   |
| Atermiter                               | 2        | 0.81%   |
| Apacer                                  | 2        | 0.81%   |
| Unknown (ABCD)                          | 1        | 0.41%   |
| Tigo                                    | 1        | 0.41%   |
| Silicon Power Computer & Communications | 1        | 0.41%   |
| S                                       | 1        | 0.41%   |
| Ramos Technology                        | 1        | 0.41%   |
| Qumo                                    | 1        | 0.41%   |
| Kllisre                                 | 1        | 0.41%   |
| Kingmax                                 | 1        | 0.41%   |
| H                                       | 1        | 0.41%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                    | Desktops | Percent |
|--------------------------------------------------------------------------|----------|---------|
| Unknown                                                                  | 8        | 2.83%   |
| Unknown RAM Module 1GB DIMM SDRAM                                        | 5        | 1.77%   |
| Unknown RAM Module 512MB DIMM SDRAM                                      | 4        | 1.41%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                     | 4        | 1.41%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                              | 4        | 1.41%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                     | 3        | 1.06%   |
| Unknown RAM Module 2GB DIMM SDRAM                                        | 3        | 1.06%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 1333MT/s                      | 3        | 1.06%   |
| Crucial RAM CT51264BA160B.C16F 4GB DIMM DDR3 1600MT/s                    | 3        | 1.06%   |
| AMD RAM R748G2400U2S 8GB DIMM DDR4 2400MT/s                              | 3        | 1.06%   |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3400MT/s                              | 3        | 1.06%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                                     | 2        | 0.71%   |
| Unknown RAM Module 8192MB DIMM 1066MT/s                                  | 2        | 0.71%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                                 | 2        | 0.71%   |
| Unknown RAM Module 2GB DIMM 800MT/s                                      | 2        | 0.71%   |
| Unknown RAM Module 1GB DIMM 1333MT/s                                     | 2        | 0.71%   |
| Unknown RAM Module 1024MB DIMM SDRAM                                     | 2        | 0.71%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s                     | 2        | 0.71%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s                   | 2        | 0.71%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                    | 2        | 0.71%   |
| Samsung RAM M393A2K40BB2-CTD 16GB DIMM DDR4 2667MT/s                     | 2        | 0.71%   |
| Patriot Memory (PDP Systems) RAM 3200 C16 Series 16GB DIMM DDR4 2400MT/s | 2        | 0.71%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3200MT/s                     | 2        | 0.71%   |
| Kingston RAM KHX2400C11D3/8GX 8GB DIMM DDR3 2400MT/s                     | 2        | 0.71%   |
| Kingston RAM 99U5595-003.A00LF 2GB DIMM DDR3 1600MT/s                    | 2        | 0.71%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s                    | 2        | 0.71%   |
| Kingston RAM 99U5471-020.A00LF 4GB DIMM DDR3 1333MT/s                    | 2        | 0.71%   |
| Kingston RAM 9965745-026.A00G 16GB DIMM DDR4 3200MT/s                    | 2        | 0.71%   |
| Kingston RAM 9905584-029.A00LF 4GB DIMM DDR3 1600MT/s                    | 2        | 0.71%   |
| Kingston RAM 9905402-015.A05LF 1GB DIMM DDR3 1333MT/s                    | 2        | 0.71%   |
| Goldkey RAM BKH400SO51208-1333 4GB SODIMM DDR3 1333MT/s                  | 2        | 0.71%   |
| G.Skill RAM F4-4000C18-32GVK 32GB DIMM DDR4 3200MT/s                     | 2        | 0.71%   |
| Crucial RAM CT8G4SFS824A.C8BD1 8GB SODIMM DDR4 2400MT/s                  | 2        | 0.71%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s                    | 2        | 0.71%   |
| Apacer RAM 78.A2GF7.4000B 2GB SODIMM DDR4 2400MT/s                       | 2        | 0.71%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                                | 1        | 0.35%   |
| Unknown RAM Module 8192MB DIMM 400MT/s                                   | 1        | 0.35%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                                  | 1        | 0.35%   |
| Unknown RAM Module 512MB DIMM DDR2 667MT/s                               | 1        | 0.35%   |
| Unknown RAM Module 512MB DIMM DDR2                                       | 1        | 0.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 87       | 40.09%  |
| DDR4    | 70       | 32.26%  |
| Unknown | 20       | 9.22%   |
| DDR2    | 18       | 8.29%   |
| SDRAM   | 14       | 6.45%   |
| DDR     | 7        | 3.23%   |
| LPDDR4  | 1        | 0.46%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 190      | 87.56%  |
| SODIMM | 27       | 12.44%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 62       | 25.94%  |
| 8192  | 54       | 22.59%  |
| 2048  | 52       | 21.76%  |
| 16384 | 32       | 13.39%  |
| 1024  | 24       | 10.04%  |
| 512   | 10       | 4.18%   |
| 32768 | 4        | 1.67%   |
| 256   | 1        | 0.42%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 41       | 17.98%  |
| 1333    | 40       | 17.54%  |
| 2400    | 28       | 12.28%  |
| 3200    | 19       | 8.33%   |
| 800     | 17       | 7.46%   |
| Unknown | 15       | 6.58%   |
| 667     | 10       | 4.39%   |
| 2667    | 8        | 3.51%   |
| 2133    | 8        | 3.51%   |
| 400     | 7        | 3.07%   |
| 1066    | 6        | 2.63%   |
| 2666    | 4        | 1.75%   |
| 3400    | 3        | 1.32%   |
| 1067    | 3        | 1.32%   |
| 533     | 3        | 1.32%   |
| 3000    | 2        | 0.88%   |
| 2933    | 2        | 0.88%   |
| 1866    | 2        | 0.88%   |
| 3733    | 1        | 0.44%   |
| 3600    | 1        | 0.44%   |
| 2048    | 1        | 0.44%   |
| 1867    | 1        | 0.44%   |
| 1400    | 1        | 0.44%   |
| 1334    | 1        | 0.44%   |
| 933     | 1        | 0.44%   |
| 333     | 1        | 0.44%   |
| 266     | 1        | 0.44%   |
| 133     | 1        | 0.44%   |

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
| Z-Star Microelectronics | 2        | 16.67%  |
| Arkmicro Technologies   | 2        | 16.67%  |
| Ricoh                   | 1        | 8.33%   |
| Realtek Semiconductor   | 1        | 8.33%   |
| Microdia                | 1        | 8.33%   |
| Logitech                | 1        | 8.33%   |
| Huawei Technologies     | 1        | 8.33%   |
| Chicony Electronics     | 1        | 8.33%   |
| Aveo Technology         | 1        | 8.33%   |
| A4Tech                  | 1        | 8.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Z-Star Venus USB2.0 Camera        | 1        | 8.33%   |
| Z-Star Integrated Camera          | 1        | 8.33%   |
| Ricoh USB2.0 Camera               | 1        | 8.33%   |
| Realtek USB Video Device          | 1        | 8.33%   |
| Microdia ASUS USB2.0 Webcam       | 1        | 8.33%   |
| Logitech Webcam C270              | 1        | 8.33%   |
| Huawei HiCamera                   | 1        | 8.33%   |
| Chicony USB2.0 VGA UVC WebCam     | 1        | 8.33%   |
| Aveo Camera                       | 1        | 8.33%   |
| Arkmicro Webcam Carrefour         | 1        | 8.33%   |
| Arkmicro USB2.0 PC CAMERA         | 1        | 8.33%   |
| A4Tech A4tech FHD 1080P PC Camera | 1        | 8.33%   |

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
| 0     | 130      | 47.1%   |
| 1     | 112      | 40.58%  |
| 2     | 25       | 9.06%   |
| 3     | 7        | 2.54%   |
| 4     | 2        | 0.72%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 114      | 66.28%  |
| Net/wireless             | 17       | 9.88%   |
| Sound                    | 16       | 9.3%    |
| Firewire controller      | 6        | 3.49%   |
| Bluetooth                | 5        | 2.91%   |
| Net/ethernet             | 4        | 2.33%   |
| Graphics card            | 3        | 1.74%   |
| Storage/ata              | 2        | 1.16%   |
| Network                  | 2        | 1.16%   |
| Card reader              | 2        | 1.16%   |
| Storage                  | 1        | 0.58%   |

