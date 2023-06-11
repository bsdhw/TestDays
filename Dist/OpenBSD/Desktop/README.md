OpenBSD - Tested Hardware & Statistics (Desktops)
-------------------------------------------------

A project to collect tested hardware configurations for OpenBSD.

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

Total: 370

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Gigabyte      | G41MT-S2                    | [355202536f](https://bsd-hardware.info/?probe=355202536f) | Jun 07, 2023 |
| ASUSTek       | PRIME B460M-A               | [4c8047dca3](https://bsd-hardware.info/?probe=4c8047dca3) | May 19, 2023 |
| VIA Techno... | VT82C597                    | [d73db58e48](https://bsd-hardware.info/?probe=d73db58e48) | May 19, 2023 |
| HP            | 0A60h                       | [98e9deff3d](https://bsd-hardware.info/?probe=98e9deff3d) | May 16, 2023 |
| PC Engines    | APU2                        | [62fef2616b](https://bsd-hardware.info/?probe=62fef2616b) | May 15, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | [2ce057e389](https://bsd-hardware.info/?probe=2ce057e389) | May 14, 2023 |
| ASUSTek       | M3A78-EMH HDMI              | [b4bf04ac2f](https://bsd-hardware.info/?probe=b4bf04ac2f) | May 13, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | [fa87f4741a](https://bsd-hardware.info/?probe=fa87f4741a) | May 13, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | [bd81294acc](https://bsd-hardware.info/?probe=bd81294acc) | May 13, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | [cace71018f](https://bsd-hardware.info/?probe=cace71018f) | May 11, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | [4353bb0195](https://bsd-hardware.info/?probe=4353bb0195) | May 09, 2023 |
| ASUSTek       | PRIME B650-PLUS             | [be83fbb0f2](https://bsd-hardware.info/?probe=be83fbb0f2) | May 09, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | [827308827b](https://bsd-hardware.info/?probe=827308827b) | Apr 24, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [c26c1111c6](https://bsd-hardware.info/?probe=c26c1111c6) | Apr 21, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | [a6141b809a](https://bsd-hardware.info/?probe=a6141b809a) | Apr 21, 2023 |
| ASUSTek       | P10S-I Series               | [5084c2b77f](https://bsd-hardware.info/?probe=5084c2b77f) | Apr 11, 2023 |
| Apple         | MacPro1,1                   | [6843822d8c](https://bsd-hardware.info/?probe=6843822d8c) | Apr 11, 2023 |
| PC Engines    | APU2                        | [cdcdfe6e0b](https://bsd-hardware.info/?probe=cdcdfe6e0b) | Apr 10, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | [a149d0b4b5](https://bsd-hardware.info/?probe=a149d0b4b5) | Apr 10, 2023 |
| HP            | Pavilion g6                 | [eeffda8d57](https://bsd-hardware.info/?probe=eeffda8d57) | Apr 09, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | [ffbe23b7d8](https://bsd-hardware.info/?probe=ffbe23b7d8) | Apr 09, 2023 |
| Sun           | SUNW,T5140                  | [a285e4f43a](https://bsd-hardware.info/?probe=a285e4f43a) | Apr 02, 2023 |
| Lenovo        | ThinkCentre M910q 10MVCT... | [5459ed9c31](https://bsd-hardware.info/?probe=5459ed9c31) | Mar 22, 2023 |
| ASUSTek       | PRIME H410M-A               | [cbbeb5c41c](https://bsd-hardware.info/?probe=cbbeb5c41c) | Mar 22, 2023 |
| Gigabyte      | B450M K                     | [0d0433284e](https://bsd-hardware.info/?probe=0d0433284e) | Mar 11, 2023 |
| Elpitech      | ET101-A1                    | [0172697883](https://bsd-hardware.info/?probe=0172697883) | Mar 10, 2023 |
| Unknown       | Unknown                     | [13ac9d6b7e](https://bsd-hardware.info/?probe=13ac9d6b7e) | Mar 01, 2023 |
| HP            | Pavilion g6                 | [39a7b609d6](https://bsd-hardware.info/?probe=39a7b609d6) | Feb 27, 2023 |
| PC Engines    | apu1                        | [41fe7362c4](https://bsd-hardware.info/?probe=41fe7362c4) | Feb 22, 2023 |
| Apple         | PowerMac3,6                 | [f31181f95c](https://bsd-hardware.info/?probe=f31181f95c) | Feb 20, 2023 |
| Dell          | OptiPlex 9020               | [0c8a5f8dfa](https://bsd-hardware.info/?probe=0c8a5f8dfa) | Feb 13, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [4c25e80924](https://bsd-hardware.info/?probe=4c25e80924) | Jan 29, 2023 |
| ASUSTek       | PRIME B460M-A               | [a6b109939f](https://bsd-hardware.info/?probe=a6b109939f) | Jan 28, 2023 |
| Lenovo        | ThinkCentre Edge72 34971... | [9c392dab85](https://bsd-hardware.info/?probe=9c392dab85) | Jan 24, 2023 |
| Dell          | OptiPlex 3040               | [9c925f4e7f](https://bsd-hardware.info/?probe=9c925f4e7f) | Jan 23, 2023 |
| ASUSTek       | PRO A520M-C                 | [bebcd1a008](https://bsd-hardware.info/?probe=bebcd1a008) | Jan 20, 2023 |
| Fujitsu       | PRIMERGY RX200 S6           | [4bcc8752f4](https://bsd-hardware.info/?probe=4bcc8752f4) | Jan 20, 2023 |
| Lenovo        | H30-05 90BJ0085SP           | [1424b3641c](https://bsd-hardware.info/?probe=1424b3641c) | Jan 18, 2023 |
| Dell          | PowerEdge R710              | [720e99b25e](https://bsd-hardware.info/?probe=720e99b25e) | Jan 17, 2023 |
| Dell          | OptiPlex 3040               | [07abf8e8b2](https://bsd-hardware.info/?probe=07abf8e8b2) | Jan 14, 2023 |
| Gigabyte      | Z390 AORUS ELITE            | [53a5719c6a](https://bsd-hardware.info/?probe=53a5719c6a) | Jan 12, 2023 |
| Lenovo        | ThinkStation D20 415575G    | [0a15d989e3](https://bsd-hardware.info/?probe=0a15d989e3) | Jan 08, 2023 |
| ASUSTek       | F2A85-M                     | [e25da8b10a](https://bsd-hardware.info/?probe=e25da8b10a) | Jan 06, 2023 |
| PC Engines    | apu4                        | [62e6e7e679](https://bsd-hardware.info/?probe=62e6e7e679) | Jan 03, 2023 |
| Gigabyte      | Z390 AORUS ELITE            | [dcf6e2df1a](https://bsd-hardware.info/?probe=dcf6e2df1a) | Jan 02, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B      | [888de76acd](https://bsd-hardware.info/?probe=888de76acd) | Dec 28, 2022 |
| Gigabyte      | Z390 AORUS ELITE            | [91b7417b84](https://bsd-hardware.info/?probe=91b7417b84) | Dec 24, 2022 |
| Raspberry ... | Raspberry Pi 400            | [ee9cac334f](https://bsd-hardware.info/?probe=ee9cac334f) | Dec 21, 2022 |
| MSI           | MS-7922                     | [95dbf4f7a8](https://bsd-hardware.info/?probe=95dbf4f7a8) | Dec 19, 2022 |
| Unknown       | Pine64 RockPro64 v2.1       | [59525051d3](https://bsd-hardware.info/?probe=59525051d3) | Dec 19, 2022 |
| Lenovo        | ThinkCentre M93p 10A8S0C... | [11d5b82cdd](https://bsd-hardware.info/?probe=11d5b82cdd) | Dec 17, 2022 |
| Unknown       | Unknown                     | [9b5307f44d](https://bsd-hardware.info/?probe=9b5307f44d) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [15b2363325](https://bsd-hardware.info/?probe=15b2363325) | Dec 05, 2022 |
| Acer          | Aspire XC-105               | [250b12c3f2](https://bsd-hardware.info/?probe=250b12c3f2) | Dec 05, 2022 |
| ASRock        | X570 Pro4                   | [b23f59a068](https://bsd-hardware.info/?probe=b23f59a068) | Nov 27, 2022 |
| ASUSTek       | P11C-X Series               | [6860cd72f8](https://bsd-hardware.info/?probe=6860cd72f8) | Nov 26, 2022 |
| ASUSTek       | P11C-X Series               | [cfdb06e761](https://bsd-hardware.info/?probe=cfdb06e761) | Nov 26, 2022 |
| Unknown       | Unknown                     | [0760ed34c3](https://bsd-hardware.info/?probe=0760ed34c3) | Nov 21, 2022 |
| ASUSTek       | Rampage V EDITION 10        | [5dcd51844e](https://bsd-hardware.info/?probe=5dcd51844e) | Nov 09, 2022 |
| ASUSTek       | PRIME B560M-A               | [95d5580fd7](https://bsd-hardware.info/?probe=95d5580fd7) | Nov 05, 2022 |
| ASUSTek       | Z170-K                      | [907b8c2402](https://bsd-hardware.info/?probe=907b8c2402) | Nov 05, 2022 |
| PC Engines    | APU2                        | [d52e3d0ce3](https://bsd-hardware.info/?probe=d52e3d0ce3) | Oct 25, 2022 |
| ASUSTek       | P8Z68-V GEN3                | [d7b32200a5](https://bsd-hardware.info/?probe=d7b32200a5) | Oct 22, 2022 |
| PC Engines    | APU2                        | [cf1abf5e46](https://bsd-hardware.info/?probe=cf1abf5e46) | Oct 21, 2022 |
| Supermicro    | X8DTH-i/6/iF/6F             | [12f7ac40ac](https://bsd-hardware.info/?probe=12f7ac40ac) | Oct 21, 2022 |
| Unknown       | Unknown                     | [d5586487b4](https://bsd-hardware.info/?probe=d5586487b4) | Oct 21, 2022 |
| ASUSTek       | P10S-I Series               | [ceb58e75b8](https://bsd-hardware.info/?probe=ceb58e75b8) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [7ecffc1ca3](https://bsd-hardware.info/?probe=7ecffc1ca3) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [eb6eda641d](https://bsd-hardware.info/?probe=eb6eda641d) | Oct 20, 2022 |
| ASRock        | Q1900M                      | [7d0380e2d0](https://bsd-hardware.info/?probe=7d0380e2d0) | Oct 15, 2022 |
| HP            | 260 G3 DM                   | [3ad5292d71](https://bsd-hardware.info/?probe=3ad5292d71) | Oct 13, 2022 |
| HP            | Compaq nw8440 (RND39ET)     | [55bef385e3](https://bsd-hardware.info/?probe=55bef385e3) | Oct 13, 2022 |
| Clevo         | R130T                       | [6f8a6bf77c](https://bsd-hardware.info/?probe=6f8a6bf77c) | Oct 10, 2022 |
| Soekris En... | net6501                     | [1cb23f6bda](https://bsd-hardware.info/?probe=1cb23f6bda) | Oct 08, 2022 |
| Soekris En... | net6501                     | [03ee772b1f](https://bsd-hardware.info/?probe=03ee772b1f) | Oct 08, 2022 |
| Lenovo        | ThinkPad T60 2613CTO        | [cb649b809c](https://bsd-hardware.info/?probe=cb649b809c) | Oct 04, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [e001150f93](https://bsd-hardware.info/?probe=e001150f93) | Oct 03, 2022 |
| ASUSTek       | All Series                  | [ab3b339cf0](https://bsd-hardware.info/?probe=ab3b339cf0) | Sep 24, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [1a89d78fa4](https://bsd-hardware.info/?probe=1a89d78fa4) | Sep 22, 2022 |
| Gigabyte      | H81M-S1                     | [fe9eecb935](https://bsd-hardware.info/?probe=fe9eecb935) | Sep 18, 2022 |
| CncTion       | N5105-4L                    | [2a34dc3fe0](https://bsd-hardware.info/?probe=2a34dc3fe0) | Sep 05, 2022 |
| Dell          | PowerEdge R620              | [66db9eb745](https://bsd-hardware.info/?probe=66db9eb745) | Aug 25, 2022 |
| ASUSTek       | PRIME B460M-A               | [21fed03fa2](https://bsd-hardware.info/?probe=21fed03fa2) | Aug 24, 2022 |
| ASUSTek       | PRIME B460M-A               | [48210e4d2a](https://bsd-hardware.info/?probe=48210e4d2a) | Aug 24, 2022 |
| Fujitsu       | PRIMERGY RX200 S6           | [9267873961](https://bsd-hardware.info/?probe=9267873961) | Aug 13, 2022 |
| Biostar       | TA880GU3+                   | [8b0c8541b3](https://bsd-hardware.info/?probe=8b0c8541b3) | Aug 06, 2022 |
| ASUSTek       | P5QL-ASUS-SE                | [f2836f4a6c](https://bsd-hardware.info/?probe=f2836f4a6c) | Aug 01, 2022 |
| ASRock        | A320M-DVS R4.0              | [77f61a8711](https://bsd-hardware.info/?probe=77f61a8711) | Aug 01, 2022 |
| Gigabyte      | H87-HD3                     | [e6a9b0dd8b](https://bsd-hardware.info/?probe=e6a9b0dd8b) | Jul 25, 2022 |
| ASUSTek       | M4A785TD-M EVO              | [def87ec245](https://bsd-hardware.info/?probe=def87ec245) | Jul 18, 2022 |
| ASUSTek       | PRIME H410M-A               | [7b6faf5301](https://bsd-hardware.info/?probe=7b6faf5301) | Jul 14, 2022 |
| ASUSTek       | PRIME H410M-A               | [ba243fa7c4](https://bsd-hardware.info/?probe=ba243fa7c4) | Jul 09, 2022 |
| Dell          | OptiPlex 580                | [620888d077](https://bsd-hardware.info/?probe=620888d077) | Jul 02, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [77acc9f5cf](https://bsd-hardware.info/?probe=77acc9f5cf) | Jul 01, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [ffa0086c70](https://bsd-hardware.info/?probe=ffa0086c70) | Jul 01, 2022 |
| Gigabyte      | G41MT-S2                    | [0563158740](https://bsd-hardware.info/?probe=0563158740) | Jun 28, 2022 |
| MSI           | MS-7C02                     | [65265eea62](https://bsd-hardware.info/?probe=65265eea62) | Jun 20, 2022 |
| Lenovo        | ThinkPad T530 24292VG       | [6f744019ce](https://bsd-hardware.info/?probe=6f744019ce) | Jun 19, 2022 |
| Apple         | MacPro4,1                   | [65380f3847](https://bsd-hardware.info/?probe=65380f3847) | Jun 06, 2022 |
| ASUSTek       | PRIME H410M-E               | [8099e7abaf](https://bsd-hardware.info/?probe=8099e7abaf) | Jun 03, 2022 |
| MSI           | MS-6788                     | [f750cb83e3](https://bsd-hardware.info/?probe=f750cb83e3) | May 31, 2022 |
| Unknown       | Raspberry Pi 4 Model B R... | [ade09344b8](https://bsd-hardware.info/?probe=ade09344b8) | May 26, 2022 |
| Unknown       | Raspberry Pi 4 Model B R... | [cc37ea1b7d](https://bsd-hardware.info/?probe=cc37ea1b7d) | May 26, 2022 |
| Unknown       | Raspberry Pi 4 Model B R... | [abacee12a9](https://bsd-hardware.info/?probe=abacee12a9) | May 26, 2022 |
| Unknown       | Raspberry Pi 3 Model B P... | [21fa41e4c1](https://bsd-hardware.info/?probe=21fa41e4c1) | May 26, 2022 |
| Gigabyte      | H81M-S2PV                   | [1937e77b97](https://bsd-hardware.info/?probe=1937e77b97) | May 22, 2022 |
| Biostar       | G31-M7 TE                   | [5c7af4b143](https://bsd-hardware.info/?probe=5c7af4b143) | May 21, 2022 |
| ASUSTek       | PRIME B550M-K               | [ce5ddde5ad](https://bsd-hardware.info/?probe=ce5ddde5ad) | May 18, 2022 |
| MSI           | MS-7C82                     | [2ad883afec](https://bsd-hardware.info/?probe=2ad883afec) | May 15, 2022 |
| ASUSTek       | PRIME X470-PRO              | [9f6b4f114d](https://bsd-hardware.info/?probe=9f6b4f114d) | May 11, 2022 |
| Unknown       | Raspberry Pi 4 Model B R... | [154799d7fa](https://bsd-hardware.info/?probe=154799d7fa) | May 08, 2022 |
| Intel         | Q3XXG4-P                    | [ed04988a23](https://bsd-hardware.info/?probe=ed04988a23) | May 03, 2022 |
| MSI           | MS-7C37                     | [aaab7cf22a](https://bsd-hardware.info/?probe=aaab7cf22a) | Apr 28, 2022 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [12cc40cc60](https://bsd-hardware.info/?probe=12cc40cc60) | Apr 23, 2022 |
| PC Engines    | APU2                        | [04a6549c99](https://bsd-hardware.info/?probe=04a6549c99) | Apr 23, 2022 |
| Apple         | PowerMac10,1                | [e054e605fa](https://bsd-hardware.info/?probe=e054e605fa) | Apr 23, 2022 |
| Intel         | DH67BL                      | [3c3c9e12da](https://bsd-hardware.info/?probe=3c3c9e12da) | Apr 22, 2022 |
| KOHJINSHA     | SH series                   | [3136a0ca03](https://bsd-hardware.info/?probe=3136a0ca03) | Apr 22, 2022 |
| Lenovo        | ThinkPad X240 20ALA0AHRT    | [062a08c811](https://bsd-hardware.info/?probe=062a08c811) | Apr 22, 2022 |
| Sony          | VPCL22Z1R                   | [f199d57905](https://bsd-hardware.info/?probe=f199d57905) | Apr 22, 2022 |
| ASUSTek       | Z170-K                      | [b16705bbbd](https://bsd-hardware.info/?probe=b16705bbbd) | Apr 22, 2022 |
| ASUSTek       | P10S-I Series               | [aca13dba36](https://bsd-hardware.info/?probe=aca13dba36) | Apr 22, 2022 |
| Dell          | G5 5090                     | [8b24170852](https://bsd-hardware.info/?probe=8b24170852) | Apr 17, 2022 |
| PC Engines    | apu4                        | [62df504364](https://bsd-hardware.info/?probe=62df504364) | Apr 09, 2022 |
| Unknown       | Raspberry Pi 3 Model B R... | [040f37113c](https://bsd-hardware.info/?probe=040f37113c) | Apr 06, 2022 |
| Intel         | DCP847SKE                   | [a79e298be3](https://bsd-hardware.info/?probe=a79e298be3) | Apr 03, 2022 |
| Lenovo        | ThinkCentre M93p 10AAS25... | [32d27b9404](https://bsd-hardware.info/?probe=32d27b9404) | Mar 19, 2022 |
| Lenovo        | ThinkCentre M93p 10AAS25... | [7361628ed9](https://bsd-hardware.info/?probe=7361628ed9) | Mar 19, 2022 |
| Unknown       | LeMaker Banana Pi           | [37e7d1912b](https://bsd-hardware.info/?probe=37e7d1912b) | Mar 05, 2022 |
| Intel         | D945GSEJT                   | [bf6a38dfcb](https://bsd-hardware.info/?probe=bf6a38dfcb) | Feb 26, 2022 |
| Dell          | OptiPlex 755                | [9ddfe010c4](https://bsd-hardware.info/?probe=9ddfe010c4) | Feb 24, 2022 |
| Gigabyte      | X58A-UD5                    | [58d57520c1](https://bsd-hardware.info/?probe=58d57520c1) | Feb 20, 2022 |
| Unknown       | Raspberry Pi 4 Model B R... | [04e528ca9f](https://bsd-hardware.info/?probe=04e528ca9f) | Feb 19, 2022 |
| ASRock        | FM2A88X Extreme6+           | [07546b5925](https://bsd-hardware.info/?probe=07546b5925) | Feb 18, 2022 |
| MSI           | MS-7253                     | [c4e971ea82](https://bsd-hardware.info/?probe=c4e971ea82) | Feb 16, 2022 |
| Raspberry ... | Raspberry Pi 400            | [dd56609ceb](https://bsd-hardware.info/?probe=dd56609ceb) | Feb 14, 2022 |
| Lenovo        | ThinkPad T400 2768W3A       | [4691fdb146](https://bsd-hardware.info/?probe=4691fdb146) | Feb 13, 2022 |
| Lenovo        | ThinkPad T400 2768W3A       | [97788dfb1a](https://bsd-hardware.info/?probe=97788dfb1a) | Feb 13, 2022 |
| Unknown       | LeMaker Banana Pi           | [77413a3d9d](https://bsd-hardware.info/?probe=77413a3d9d) | Feb 12, 2022 |
| HP            | t620 Quad Core TC           | [965ced51e6](https://bsd-hardware.info/?probe=965ced51e6) | Feb 12, 2022 |
| MSI           | MS-7C96                     | [c08331ad58](https://bsd-hardware.info/?probe=c08331ad58) | Feb 06, 2022 |
| Raspberry ... | Raspberry Pi 400            | [b35265f8f4](https://bsd-hardware.info/?probe=b35265f8f4) | Jan 29, 2022 |
| Gigabyte      | Z590 VISION G               | [9c73c01062](https://bsd-hardware.info/?probe=9c73c01062) | Jan 28, 2022 |
| WYSE          | D CLASS                     | [5f31ae866c](https://bsd-hardware.info/?probe=5f31ae866c) | Jan 24, 2022 |
| ASRock        | X570 Pro4                   | [d77aae8064](https://bsd-hardware.info/?probe=d77aae8064) | Jan 23, 2022 |
| MSI           | MS-7C56                     | [962ac1c7b0](https://bsd-hardware.info/?probe=962ac1c7b0) | Jan 20, 2022 |
| Unknown       | TI AM335x BeagleBone Bla... | [14d6cfb7a4](https://bsd-hardware.info/?probe=14d6cfb7a4) | Dec 27, 2021 |
| Unknown       | TI AM335x BeagleBone Bla... | [ce75fa56bd](https://bsd-hardware.info/?probe=ce75fa56bd) | Dec 27, 2021 |
| Unknown       | TI AM335x BeagleBone Bla... | [612825abe3](https://bsd-hardware.info/?probe=612825abe3) | Dec 27, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING     | [2ee4c7fefe](https://bsd-hardware.info/?probe=2ee4c7fefe) | Dec 27, 2021 |
| PC Engines    | APU2                        | [d271c4a29f](https://bsd-hardware.info/?probe=d271c4a29f) | Dec 15, 2021 |
| Gigabyte      | H81M-S2PV                   | [0d4c532744](https://bsd-hardware.info/?probe=0d4c532744) | Nov 29, 2021 |
| MSI           | MS-7C56                     | [d4e3f14ad4](https://bsd-hardware.info/?probe=d4e3f14ad4) | Nov 23, 2021 |
| PC Engines    | APU2                        | [15a26da041](https://bsd-hardware.info/?probe=15a26da041) | Nov 14, 2021 |
| Unknown       | Hardkernel ODROID-N2        | [42f6e357c9](https://bsd-hardware.info/?probe=42f6e357c9) | Nov 05, 2021 |
| Yanling       | YL-KBR6L                    | [35f1c905eb](https://bsd-hardware.info/?probe=35f1c905eb) | Nov 04, 2021 |
| HP            | 0A60h                       | [5c227c5b61](https://bsd-hardware.info/?probe=5c227c5b61) | Oct 27, 2021 |
| HP            | ProDesk 600 G1 SFF          | [7f19a8a566](https://bsd-hardware.info/?probe=7f19a8a566) | Oct 26, 2021 |
| Supermicro    | X7SBL                       | [f5b4e8e7ab](https://bsd-hardware.info/?probe=f5b4e8e7ab) | Oct 23, 2021 |
| Lenovo        | SHARKBAY No DPK             | [e762f9146e](https://bsd-hardware.info/?probe=e762f9146e) | Oct 16, 2021 |
| ASUSTek       | P10S-I Series               | [d086bf947a](https://bsd-hardware.info/?probe=d086bf947a) | Oct 15, 2021 |
| Gigabyte      | B450M DS3H                  | [445b53ddba](https://bsd-hardware.info/?probe=445b53ddba) | Oct 15, 2021 |
| Protectli     | FW6                         | [de39c4e316](https://bsd-hardware.info/?probe=de39c4e316) | Oct 15, 2021 |
| MSI           | MS-7D54                     | [ac1f6ee8a6](https://bsd-hardware.info/?probe=ac1f6ee8a6) | Oct 13, 2021 |
| Gigabyte      | B450M DS3H                  | [50e4e13ee0](https://bsd-hardware.info/?probe=50e4e13ee0) | Oct 07, 2021 |
| MSI           | MS-7B53                     | [c7104d301e](https://bsd-hardware.info/?probe=c7104d301e) | Oct 05, 2021 |
| Unknown       | Raspberry Pi 4 Model B R... | [49173900e7](https://bsd-hardware.info/?probe=49173900e7) | Oct 04, 2021 |
| Unknown       | Raspberry Pi 4 Model B R... | [d05a877535](https://bsd-hardware.info/?probe=d05a877535) | Oct 03, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [46672cf89f](https://bsd-hardware.info/?probe=46672cf89f) | Oct 01, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [838a177f57](https://bsd-hardware.info/?probe=838a177f57) | Sep 30, 2021 |
| HP            | Pro3500 Series              | [abf3223f32](https://bsd-hardware.info/?probe=abf3223f32) | Sep 19, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [7a800aec88](https://bsd-hardware.info/?probe=7a800aec88) | Sep 15, 2021 |
| NF541         | Unknown                     | [deb29af749](https://bsd-hardware.info/?probe=deb29af749) | Sep 11, 2021 |
| MSI           | MS-7A34                     | [decfe43121](https://bsd-hardware.info/?probe=decfe43121) | Sep 10, 2021 |
| PC Engines    | apu4                        | [9557835b54](https://bsd-hardware.info/?probe=9557835b54) | Sep 09, 2021 |
| Gigabyte      | BRi3(H)-10110               | [9aa3540749](https://bsd-hardware.info/?probe=9aa3540749) | Sep 09, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [f860e13b6b](https://bsd-hardware.info/?probe=f860e13b6b) | Sep 08, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [1b6bf4666c](https://bsd-hardware.info/?probe=1b6bf4666c) | Sep 05, 2021 |
| Gigabyte      | GA-7VT600                   | [83b86f3e8c](https://bsd-hardware.info/?probe=83b86f3e8c) | Aug 23, 2021 |
| Unknown       | FriendlyElec NanoPi R4S     | [ac10928ac3](https://bsd-hardware.info/?probe=ac10928ac3) | Aug 05, 2021 |
| Unknown       | Pine64 Rock64               | [0df3f7572c](https://bsd-hardware.info/?probe=0df3f7572c) | Jul 23, 2021 |
| ASUSTek       | B202                        | [9f5f0a4117](https://bsd-hardware.info/?probe=9f5f0a4117) | Jul 21, 2021 |
| Unknown       | Pine64 Rock64               | [83c18360fc](https://bsd-hardware.info/?probe=83c18360fc) | Jul 12, 2021 |
| HP            | ProLiant DL360e Gen8        | [30eeb098b0](https://bsd-hardware.info/?probe=30eeb098b0) | Jul 10, 2021 |
| HP            | ProLiant DL320 G5           | [3b4ee33976](https://bsd-hardware.info/?probe=3b4ee33976) | Jul 10, 2021 |
| Foxconn       | AT-7000 Series              | [3802fb98b5](https://bsd-hardware.info/?probe=3802fb98b5) | Jul 10, 2021 |
| Unknown       | Pine64 Rock64               | [9cffa29c69](https://bsd-hardware.info/?probe=9cffa29c69) | Jul 08, 2021 |
| ASUSTek       | PRIME B560M-A               | [55f46bc85d](https://bsd-hardware.info/?probe=55f46bc85d) | Jul 07, 2021 |
| Unknown       | Unknown                     | [cfb0e172cb](https://bsd-hardware.info/?probe=cfb0e172cb) | Jun 27, 2021 |
| Dell          | 0GTK4K A02                  | [bb610333d0](https://bsd-hardware.info/?probe=bb610333d0) | Jun 22, 2021 |
| ASRock        | X99 WS                      | [201a7417a5](https://bsd-hardware.info/?probe=201a7417a5) | Jun 11, 2021 |
| Supermicro    | X8DTH-i/6/iF/6F             | [1e8ac47693](https://bsd-hardware.info/?probe=1e8ac47693) | Jun 08, 2021 |
| Supermicro    | X8DTH-i/6/iF/6F             | [bd4a74c5e5](https://bsd-hardware.info/?probe=bd4a74c5e5) | Jun 08, 2021 |
| Supermicro    | X10SLH-N6-ST031             | [e54175f99f](https://bsd-hardware.info/?probe=e54175f99f) | Jun 06, 2021 |
| ASRock        | Z68 Extreme4 Gen3           | [58c8cdc060](https://bsd-hardware.info/?probe=58c8cdc060) | Jun 05, 2021 |
| Shuttle       | DS77U                       | [5d1c78145e](https://bsd-hardware.info/?probe=5d1c78145e) | May 30, 2021 |
| ASUSTek       | PRIME B560M-A               | [ca05acd52f](https://bsd-hardware.info/?probe=ca05acd52f) | May 30, 2021 |
| ASRock        | X570M Pro4                  | [1d1a5afcfb](https://bsd-hardware.info/?probe=1d1a5afcfb) | May 28, 2021 |
| Alienware     | Aurora Ryzen Edition        | [b9dc8b182c](https://bsd-hardware.info/?probe=b9dc8b182c) | May 28, 2021 |
| Unknown       | Unknown                     | [d098ba539d](https://bsd-hardware.info/?probe=d098ba539d) | May 27, 2021 |
| ASUSTek       | B202                        | [0b66a5fd20](https://bsd-hardware.info/?probe=0b66a5fd20) | May 21, 2021 |
| PC Engines    | APU2                        | [c99a0b0e4d](https://bsd-hardware.info/?probe=c99a0b0e4d) | May 05, 2021 |
| ASRock        | X99 WS                      | [eb20367455](https://bsd-hardware.info/?probe=eb20367455) | May 05, 2021 |
| Supermicro    | X8STi                       | [c615ef1edf](https://bsd-hardware.info/?probe=c615ef1edf) | May 04, 2021 |
| Lenovo        | ThinkCentre M93p 10AAS25... | [a9bbd07ad9](https://bsd-hardware.info/?probe=a9bbd07ad9) | May 03, 2021 |
| PC Engines    | apu1                        | [7b4678c7ef](https://bsd-hardware.info/?probe=7b4678c7ef) | May 03, 2021 |
| ASUSTek       | P10S-I Series               | [6548ae7d88](https://bsd-hardware.info/?probe=6548ae7d88) | May 01, 2021 |
| PC Engines    | apu1                        | [c5ae3337e7](https://bsd-hardware.info/?probe=c5ae3337e7) | May 01, 2021 |
| ASUSTek       | All Series                  | [ef6afe88d7](https://bsd-hardware.info/?probe=ef6afe88d7) | Apr 17, 2021 |
| ECT           | One Computer AMD A10-785... | [de7e23b3e3](https://bsd-hardware.info/?probe=de7e23b3e3) | Apr 07, 2021 |
| Gigabyte      | GB-BXBT-2807                | [25e9765fc0](https://bsd-hardware.info/?probe=25e9765fc0) | Apr 03, 2021 |
| ASUSTek       | All Series                  | [c5bc64e4e9](https://bsd-hardware.info/?probe=c5bc64e4e9) | Mar 22, 2021 |
| ASUSTek       | All Series                  | [700ff7d378](https://bsd-hardware.info/?probe=700ff7d378) | Mar 22, 2021 |
| HP            | ProLiant DL360 Gen9         | [b283b34881](https://bsd-hardware.info/?probe=b283b34881) | Mar 17, 2021 |
| HP            | ProLiant DL360 Gen9         | [bf440e72a1](https://bsd-hardware.info/?probe=bf440e72a1) | Mar 17, 2021 |
| HP            | EliteDesk 800 G5 SFF        | [aaf9bc1c12](https://bsd-hardware.info/?probe=aaf9bc1c12) | Mar 17, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1HL0... | [954c65dbcf](https://bsd-hardware.info/?probe=954c65dbcf) | Mar 11, 2021 |
| ASUSTek       | All Series                  | [b4aec46644](https://bsd-hardware.info/?probe=b4aec46644) | Mar 07, 2021 |
| ASUSTek       | All Series                  | [f7b1921594](https://bsd-hardware.info/?probe=f7b1921594) | Mar 07, 2021 |
| ASRock        | G31M-VS2                    | [6c7150dc1b](https://bsd-hardware.info/?probe=6c7150dc1b) | Feb 24, 2021 |
| ASRock        | J4205-ITX                   | [c8e0b22858](https://bsd-hardware.info/?probe=c8e0b22858) | Feb 23, 2021 |
| PC Engines    | apu4                        | [b30884fc0e](https://bsd-hardware.info/?probe=b30884fc0e) | Feb 18, 2021 |
| PC Engines    | APU3                        | [449967354c](https://bsd-hardware.info/?probe=449967354c) | Feb 18, 2021 |
| PC Engines    | APU2                        | [b911e3bec2](https://bsd-hardware.info/?probe=b911e3bec2) | Feb 18, 2021 |
| Shuttle       | DS77U                       | [2d0bd0e99a](https://bsd-hardware.info/?probe=2d0bd0e99a) | Feb 14, 2021 |
| Gigabyte      | Z68A-D3H-B3                 | [e1c3b89d0d](https://bsd-hardware.info/?probe=e1c3b89d0d) | Feb 06, 2021 |
| ASUSTek       | PRIME X470-PRO              | [828a9df369](https://bsd-hardware.info/?probe=828a9df369) | Feb 01, 2021 |
| Lenovo        | ThinkCentre M93p 10A8S0C... | [c8af335c01](https://bsd-hardware.info/?probe=c8af335c01) | Jan 29, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B      | [8c953bac3f](https://bsd-hardware.info/?probe=8c953bac3f) | Jan 25, 2021 |
| ASUSTek       | All Series                  | [7ebe6eee38](https://bsd-hardware.info/?probe=7ebe6eee38) | Jan 25, 2021 |
| ASUSTek       | PRIME X370-PRO              | [2a81a1bd1f](https://bsd-hardware.info/?probe=2a81a1bd1f) | Jan 24, 2021 |
| Sun           | SUNW,Sun-Blade-1500         | [647618a0ca](https://bsd-hardware.info/?probe=647618a0ca) | Jan 22, 2021 |
| PC Engines    | apu1                        | [a5d18dcbbc](https://bsd-hardware.info/?probe=a5d18dcbbc) | Jan 21, 2021 |
| PC Engines    | apu1                        | [70918da1e7](https://bsd-hardware.info/?probe=70918da1e7) | Jan 21, 2021 |
| Sun           | SUNW,Sun-Blade-100          | [299c76eb85](https://bsd-hardware.info/?probe=299c76eb85) | Jan 18, 2021 |
| Lenovo        | ThinkCentre M93p 10A8S0C... | [36ef631bfe](https://bsd-hardware.info/?probe=36ef631bfe) | Jan 05, 2021 |
| Gigabyte      | 970A-DS3P                   | [f0b9687ab8](https://bsd-hardware.info/?probe=f0b9687ab8) | Dec 22, 2020 |
| Unknown       | ODYSSEY-X86J4105            | [17749e13c8](https://bsd-hardware.info/?probe=17749e13c8) | Dec 16, 2020 |
| ASUSTek       | PRIME B450M-A               | [d13e0a1749](https://bsd-hardware.info/?probe=d13e0a1749) | Dec 15, 2020 |
| Supermicro    | X11DDW-L                    | [57a5022e27](https://bsd-hardware.info/?probe=57a5022e27) | Dec 14, 2020 |
| ASUSTek       | P4P800-VM                   | [4fe4c14195](https://bsd-hardware.info/?probe=4fe4c14195) | Dec 05, 2020 |
| Apple         | Xserve3,1                   | [7329a7650d](https://bsd-hardware.info/?probe=7329a7650d) | Dec 05, 2020 |
| Gigabyte      | Unknown                     | [8a9ae48d42](https://bsd-hardware.info/?probe=8a9ae48d42) | Dec 01, 2020 |
| HP            | Compaq dc7800 Small Form... | [2b49eb75dc](https://bsd-hardware.info/?probe=2b49eb75dc) | Nov 27, 2020 |
| HP            | Compaq dc7800 Small Form... | [3fe6528682](https://bsd-hardware.info/?probe=3fe6528682) | Nov 27, 2020 |
| Dell          | OptiPlex GX1 500M+          | [deb0d463ab](https://bsd-hardware.info/?probe=deb0d463ab) | Nov 27, 2020 |
| Dell          | OptiPlex GX1 500M+          | [5186eb9e52](https://bsd-hardware.info/?probe=5186eb9e52) | Nov 26, 2020 |
| ASUSTek       | PRIME X370-PRO              | [9cf79cf54b](https://bsd-hardware.info/?probe=9cf79cf54b) | Nov 22, 2020 |
| ASUSTek       | PRIME X370-PRO              | [cab036429d](https://bsd-hardware.info/?probe=cab036429d) | Nov 22, 2020 |
| Unknown       | cavium,ubnt_e300            | [b8524b5002](https://bsd-hardware.info/?probe=b8524b5002) | Nov 20, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B      | [c030400069](https://bsd-hardware.info/?probe=c030400069) | Nov 19, 2020 |
| ASRock        | IMB-191                     | [76991234cd](https://bsd-hardware.info/?probe=76991234cd) | Nov 18, 2020 |
| HARDKERNEL    | ODROID-H2                   | [c03bc18b3a](https://bsd-hardware.info/?probe=c03bc18b3a) | Nov 18, 2020 |
| MSI           | MS-B09012                   | [7ba791108f](https://bsd-hardware.info/?probe=7ba791108f) | Nov 18, 2020 |
| PC Engines    | APU2                        | [b4f5d7d344](https://bsd-hardware.info/?probe=b4f5d7d344) | Nov 16, 2020 |
| Supermicro    | X8DTH-i/6/iF/6F             | [778cb9f428](https://bsd-hardware.info/?probe=778cb9f428) | Nov 16, 2020 |
| Gigabyte      | GB-BXBT-2807                | [c11b475d28](https://bsd-hardware.info/?probe=c11b475d28) | Nov 13, 2020 |
| Lenovo        | ThinkCentre M92p 3212AD2    | [579528e284](https://bsd-hardware.info/?probe=579528e284) | Nov 10, 2020 |
| Gigabyte      | M61SME-S2L                  | [d8809eb5e7](https://bsd-hardware.info/?probe=d8809eb5e7) | Nov 09, 2020 |
| Gigabyte      | M61SME-S2L                  | [e5f658c70a](https://bsd-hardware.info/?probe=e5f658c70a) | Nov 09, 2020 |
| Pegatron      | SKLD4-P1                    | [ea548b4c71](https://bsd-hardware.info/?probe=ea548b4c71) | Nov 08, 2020 |
| Soekris En... | net5501                     | [bd9930a18a](https://bsd-hardware.info/?probe=bd9930a18a) | Nov 06, 2020 |
| Soekris En... | net6501                     | [fdf124653b](https://bsd-hardware.info/?probe=fdf124653b) | Nov 06, 2020 |
| MSI           | MS-7A34                     | [8c87d6b643](https://bsd-hardware.info/?probe=8c87d6b643) | Nov 03, 2020 |
| PC Engines    | APU2                        | [e0361ddbad](https://bsd-hardware.info/?probe=e0361ddbad) | Oct 31, 2020 |
| ASUSTek       | B75M-A                      | [43ece33e8c](https://bsd-hardware.info/?probe=43ece33e8c) | Oct 31, 2020 |
| Intel         | D945GCLF2                   | [58678b0643](https://bsd-hardware.info/?probe=58678b0643) | Oct 30, 2020 |
| Intel         | D945GCLF2                   | [3354fb903b](https://bsd-hardware.info/?probe=3354fb903b) | Oct 30, 2020 |
| Gigabyte      | X570 AORUS ELITE            | [973b62551f](https://bsd-hardware.info/?probe=973b62551f) | Oct 30, 2020 |
| eMachines     | EL1200                      | [ae59908738](https://bsd-hardware.info/?probe=ae59908738) | Oct 30, 2020 |
| Acer          | Veriton M6610G              | [7dd00aa8b1](https://bsd-hardware.info/?probe=7dd00aa8b1) | Oct 30, 2020 |
| eMachines     | EL1200                      | [5bc54351be](https://bsd-hardware.info/?probe=5bc54351be) | Oct 30, 2020 |
| ECS           | BSWI-D2                     | [c5b07f5c31](https://bsd-hardware.info/?probe=c5b07f5c31) | Oct 30, 2020 |
| ASRock        | N3160-NUC IPC               | [8d13af2f0b](https://bsd-hardware.info/?probe=8d13af2f0b) | Oct 28, 2020 |
| ASRock        | N3160-NUC IPC               | [8714fe0665](https://bsd-hardware.info/?probe=8714fe0665) | Oct 28, 2020 |
| ASUSTek       | PRIME B250M-C               | [4594c1084c](https://bsd-hardware.info/?probe=4594c1084c) | Oct 28, 2020 |
| Shuttle       | DS77U                       | [c70e526574](https://bsd-hardware.info/?probe=c70e526574) | Oct 27, 2020 |
| PC Engines    | APU2                        | [ce4c41d466](https://bsd-hardware.info/?probe=ce4c41d466) | Oct 26, 2020 |
| Dell          | PowerEdge R230              | [1422e9737b](https://bsd-hardware.info/?probe=1422e9737b) | Oct 26, 2020 |
| Supermicro    | X8STi                       | [1b64902781](https://bsd-hardware.info/?probe=1b64902781) | Oct 26, 2020 |
| HP            | 120-1136                    | [12f3eb0227](https://bsd-hardware.info/?probe=12f3eb0227) | Oct 25, 2020 |
| HP            | ProLiant MicroServer        | [04b6ad9952](https://bsd-hardware.info/?probe=04b6ad9952) | Oct 25, 2020 |
| Supermicro    | X11SSW-F                    | [ca07d7ef48](https://bsd-hardware.info/?probe=ca07d7ef48) | Oct 25, 2020 |
| Gigabyte      | X58A-UD5                    | [6e642641e5](https://bsd-hardware.info/?probe=6e642641e5) | Oct 25, 2020 |
| AZW           | Z83 II                      | [9416876f20](https://bsd-hardware.info/?probe=9416876f20) | Oct 24, 2020 |
| AZW           | Z83 II                      | [19b1b4d85d](https://bsd-hardware.info/?probe=19b1b4d85d) | Oct 24, 2020 |
| Dell          | Precision WorkStation T7... | [c01ce9ec81](https://bsd-hardware.info/?probe=c01ce9ec81) | Oct 24, 2020 |
| PC Engines    | APU2                        | [5cee7fa636](https://bsd-hardware.info/?probe=5cee7fa636) | Oct 22, 2020 |
| MSI           | MS-7345                     | [96cc99accc](https://bsd-hardware.info/?probe=96cc99accc) | Oct 22, 2020 |
| MSI           | MS-7816                     | [337e5b8e0c](https://bsd-hardware.info/?probe=337e5b8e0c) | Oct 22, 2020 |
| ASRock        | DN2800MT                    | [b475aa2ead](https://bsd-hardware.info/?probe=b475aa2ead) | Oct 21, 2020 |
| Intel         | D2500HN                     | [6dbc4dfa33](https://bsd-hardware.info/?probe=6dbc4dfa33) | Oct 21, 2020 |
| Intel         | CRESCENTBAY                 | [42d114559b](https://bsd-hardware.info/?probe=42d114559b) | Oct 21, 2020 |
| PC Engines    | APU2                        | [d1ca549fe7](https://bsd-hardware.info/?probe=d1ca549fe7) | Oct 21, 2020 |
| ZOTAC         | XXXXXX                      | [0f8960bdd3](https://bsd-hardware.info/?probe=0f8960bdd3) | Oct 21, 2020 |
| IBM           | Board                       | [11b0b7012f](https://bsd-hardware.info/?probe=11b0b7012f) | Oct 21, 2020 |
| IBM           | Board                       | [a92c08a920](https://bsd-hardware.info/?probe=a92c08a920) | Oct 21, 2020 |
| IBM           | Board                       | [80d5f15a63](https://bsd-hardware.info/?probe=80d5f15a63) | Oct 21, 2020 |
| Gigabyte      | GA-MA770T-UD3P              | [2cb76e5886](https://bsd-hardware.info/?probe=2cb76e5886) | Oct 21, 2020 |
| PC Engines    | APU2                        | [e6ee8a14d5](https://bsd-hardware.info/?probe=e6ee8a14d5) | Oct 20, 2020 |
| ASUSTek       | Z170-K                      | [19cb3ccc34](https://bsd-hardware.info/?probe=19cb3ccc34) | Oct 20, 2020 |
| Intel         | S3000AH                     | [f5b858601a](https://bsd-hardware.info/?probe=f5b858601a) | Oct 20, 2020 |
| Intel         | D2500HN                     | [4b432dcb3d](https://bsd-hardware.info/?probe=4b432dcb3d) | Oct 20, 2020 |
| PC Engines    | APU2                        | [b95ef9962d](https://bsd-hardware.info/?probe=b95ef9962d) | Oct 20, 2020 |
| PC Engines    | APU2                        | [aecf376503](https://bsd-hardware.info/?probe=aecf376503) | Oct 20, 2020 |
| Unknown       | Unknown                     | [bedb4a4b37](https://bsd-hardware.info/?probe=bedb4a4b37) | Oct 20, 2020 |
| Unknown       | Unknown                     | [a28ef1d2b8](https://bsd-hardware.info/?probe=a28ef1d2b8) | Oct 20, 2020 |
| PC Engines    | apu1                        | [c77b06b3eb](https://bsd-hardware.info/?probe=c77b06b3eb) | Oct 20, 2020 |
| Dell          | PowerEdge R620              | [7671a495d1](https://bsd-hardware.info/?probe=7671a495d1) | Oct 19, 2020 |
| Dell          | PowerEdge R620              | [c1a2bc7a51](https://bsd-hardware.info/?probe=c1a2bc7a51) | Oct 19, 2020 |
| Dell          | PowerEdge R620              | [c1c5ee566c](https://bsd-hardware.info/?probe=c1c5ee566c) | Oct 19, 2020 |
| Dell          | PowerEdge R620              | [af87ddbbaa](https://bsd-hardware.info/?probe=af87ddbbaa) | Oct 19, 2020 |
| ASUSTek       | P10S-I Series               | [1a0e9f0100](https://bsd-hardware.info/?probe=1a0e9f0100) | Oct 19, 2020 |
| Unknown       | Unknown                     | [a3db8641e6](https://bsd-hardware.info/?probe=a3db8641e6) | Oct 19, 2020 |
| PC Engines    | apu4                        | [e4cd6d0b48](https://bsd-hardware.info/?probe=e4cd6d0b48) | Oct 19, 2020 |
| PC Engines    | APU                         | [0cf4f6a5f9](https://bsd-hardware.info/?probe=0cf4f6a5f9) | Oct 19, 2020 |
| Lenovo        | SHARKBAY WIN                | [53feb1fec6](https://bsd-hardware.info/?probe=53feb1fec6) | Oct 19, 2020 |
| ASRock        | IMB-191                     | [4ac9e9cf2a](https://bsd-hardware.info/?probe=4ac9e9cf2a) | Oct 19, 2020 |
| PC Engines    | APU2                        | [064e7167a0](https://bsd-hardware.info/?probe=064e7167a0) | Oct 19, 2020 |
| Dell          | OptiPlex 3060               | [13992dbb10](https://bsd-hardware.info/?probe=13992dbb10) | Oct 19, 2020 |
| PC Engines    | APU2                        | [a5b1c3a559](https://bsd-hardware.info/?probe=a5b1c3a559) | Oct 19, 2020 |
| Dell          | PowerEdge T320              | [75c395f941](https://bsd-hardware.info/?probe=75c395f941) | Oct 19, 2020 |
| Dell          | PowerEdge 1950              | [3cfcdfce6d](https://bsd-hardware.info/?probe=3cfcdfce6d) | Oct 19, 2020 |
| Dell          | PowerEdge 1950              | [0865193e7e](https://bsd-hardware.info/?probe=0865193e7e) | Oct 19, 2020 |
| Dell          | PowerEdge R610              | [2ea539bbd3](https://bsd-hardware.info/?probe=2ea539bbd3) | Oct 19, 2020 |
| Dell          | OptiPlex 7020               | [293e6af35e](https://bsd-hardware.info/?probe=293e6af35e) | Oct 19, 2020 |
| PC Engines    | APU2                        | [2ab3051cb8](https://bsd-hardware.info/?probe=2ab3051cb8) | Oct 19, 2020 |
| PC Engines    | apu4                        | [f0116986e0](https://bsd-hardware.info/?probe=f0116986e0) | Oct 19, 2020 |
| IBM           | Board                       | [af2f64a7a8](https://bsd-hardware.info/?probe=af2f64a7a8) | Oct 19, 2020 |
| Foxconn       | AT-7000 Series              | [dc7b96e637](https://bsd-hardware.info/?probe=dc7b96e637) | Oct 19, 2020 |
| Foxconn       | AT-7000 Series              | [0184fcedcf](https://bsd-hardware.info/?probe=0184fcedcf) | Oct 19, 2020 |
| ASUSTek       | PRIME X570-P                | [b33e2a5177](https://bsd-hardware.info/?probe=b33e2a5177) | Oct 19, 2020 |
| PC Engines    | apu1                        | [576f4db9e1](https://bsd-hardware.info/?probe=576f4db9e1) | Oct 19, 2020 |
| PC Engines    | APU2                        | [e4030e5ee2](https://bsd-hardware.info/?probe=e4030e5ee2) | Oct 19, 2020 |
| PC Engines    | APU2                        | [ca0480a30d](https://bsd-hardware.info/?probe=ca0480a30d) | Oct 19, 2020 |
| Bluechip C... | bluechip BUSINESSline Wo... | [6dc86d6a5b](https://bsd-hardware.info/?probe=6dc86d6a5b) | Oct 19, 2020 |
| Unknown       | Unknown                     | [e36fc2b2b2](https://bsd-hardware.info/?probe=e36fc2b2b2) | Oct 19, 2020 |
| ASRock        | N68C-S UCC                  | [027fbd78f5](https://bsd-hardware.info/?probe=027fbd78f5) | Oct 19, 2020 |
| ASRock        | A75M-ITX                    | [dff827c2ae](https://bsd-hardware.info/?probe=dff827c2ae) | Oct 19, 2020 |
| PC Engines    | apu1                        | [8aade944d5](https://bsd-hardware.info/?probe=8aade944d5) | Oct 19, 2020 |
| PC Engines    | apu4                        | [ee8a1317f9](https://bsd-hardware.info/?probe=ee8a1317f9) | Oct 19, 2020 |
| Protectli     | FW6                         | [1454991c98](https://bsd-hardware.info/?probe=1454991c98) | Aug 27, 2020 |
| PC Engines    | apu4                        | [8f4ed98a45](https://bsd-hardware.info/?probe=8f4ed98a45) | Aug 21, 2020 |
| Gigabyte      | X58A-UD5                    | [63a429ad0e](https://bsd-hardware.info/?probe=63a429ad0e) | Aug 16, 2020 |
| Dell          | OptiPlex 745                | [6de04c2c9c](https://bsd-hardware.info/?probe=6de04c2c9c) | Aug 14, 2020 |
| PC Engines    | apu4                        | [f0f8a22656](https://bsd-hardware.info/?probe=f0f8a22656) | Aug 05, 2020 |
| Intel         | ChiefRiver                  | [022d2761b9](https://bsd-hardware.info/?probe=022d2761b9) | Aug 03, 2020 |
| PC Engines    | APU3                        | [1eaf8a1484](https://bsd-hardware.info/?probe=1eaf8a1484) | Aug 03, 2020 |
| PC Engines    | APU3                        | [4980462667](https://bsd-hardware.info/?probe=4980462667) | Aug 03, 2020 |
| PC Engines    | APU3                        | [975e23e09d](https://bsd-hardware.info/?probe=975e23e09d) | Aug 03, 2020 |
| Shuttle       | DS437                       | [aa350b6b92](https://bsd-hardware.info/?probe=aa350b6b92) | Aug 03, 2020 |
| PC Engines    | APU2                        | [fe5c2f4838](https://bsd-hardware.info/?probe=fe5c2f4838) | Aug 03, 2020 |
| Lenovo        | ThinkCentre M92p 3212AD2    | [ca76cc5467](https://bsd-hardware.info/?probe=ca76cc5467) | Jul 30, 2020 |
| ASRock        | E350M1                      | [08eec78cdf](https://bsd-hardware.info/?probe=08eec78cdf) | Jul 25, 2020 |
| Pegatron      | 2A73                        | [05dea28605](https://bsd-hardware.info/?probe=05dea28605) | Jul 21, 2020 |
| PC Engines    | apu4                        | [52c611855b](https://bsd-hardware.info/?probe=52c611855b) | Jul 12, 2020 |
| ASUSTek       | All Series                  | [e4f1a19012](https://bsd-hardware.info/?probe=e4f1a19012) | Jun 05, 2020 |
| Unknown       | Unknown                     | [4e3b87cc6c](https://bsd-hardware.info/?probe=4e3b87cc6c) | Jun 01, 2020 |
| Sony UK       | Raspberry Pi 4 Model B      | [483af3998c](https://bsd-hardware.info/?probe=483af3998c) | May 28, 2020 |
| Unknown       | Unknown                     | [80a1eda96f](https://bsd-hardware.info/?probe=80a1eda96f) | May 28, 2020 |
| Dell          | PowerEdge T320              | [eec750b5c5](https://bsd-hardware.info/?probe=eec750b5c5) | May 28, 2020 |
| Gigabyte      | M68MT-S2P                   | [08534174df](https://bsd-hardware.info/?probe=08534174df) | May 27, 2020 |
| Unknown       | TI AM335x BeagleBone Bla... | [8e0f831fd8](https://bsd-hardware.info/?probe=8e0f831fd8) | May 27, 2020 |
| Gigabyte      | M68MT-S2P                   | [03ea0992c4](https://bsd-hardware.info/?probe=03ea0992c4) | May 27, 2020 |
| IBM           | Board                       | [1bcc2b8e0b](https://bsd-hardware.info/?probe=1bcc2b8e0b) | May 27, 2020 |
| Unknown       | TI AM335x BeagleBone Bla... | [74b9526162](https://bsd-hardware.info/?probe=74b9526162) | May 27, 2020 |
| Gigabyte      | Unknown                     | [576771182b](https://bsd-hardware.info/?probe=576771182b) | May 25, 2020 |
| Gigabyte      | Unknown                     | [05e8154b2c](https://bsd-hardware.info/?probe=05e8154b2c) | May 25, 2020 |
| ASUSTek       | P4P800-VM                   | [8b9481baf2](https://bsd-hardware.info/?probe=8b9481baf2) | May 25, 2020 |
| ASUSTek       | P4P800-VM                   | [33c4579f99](https://bsd-hardware.info/?probe=33c4579f99) | May 25, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OpenBSD 6.8 | 109      | 36.09%  |
| OpenBSD 7.1 | 50       | 16.56%  |
| OpenBSD 7.2 | 36       | 11.92%  |
| OpenBSD 7.0 | 35       | 11.59%  |
| OpenBSD 6.9 | 31       | 10.26%  |
| OpenBSD 6.7 | 26       | 8.61%   |
| OpenBSD 7.3 | 14       | 4.64%   |
| OpenBSD 6.6 | 1        | 0.33%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| OpenBSD | 260      | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| amd64   | 214      | 81.99%  |
| arm64   | 19       | 7.28%   |
| i386    | 18       | 6.9%    |
| sparc64 | 3        | 1.15%   |
| macppc  | 3        | 1.15%   |
| octeon  | 2        | 0.77%   |
| armv7   | 2        | 0.77%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Console       | 97       | 35.27%  |
| fvwm          | 85       | 30.91%  |
| helloDesktop  | 77       | 28%     |
| XFCE          | 12       | 4.36%   |
| GNOME         | 2        | 0.73%   |
| i3            | 1        | 0.36%   |
| Enlightenment | 1        | 0.36%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 133      | 50.19%  |
| Console | 132      | 49.81%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 251      | 95.44%  |
| SLiM    | 7        | 2.66%   |
| GDM     | 5        | 1.9%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 226      | 85.61%  |
| ru_RU      | 14       | 5.3%    |
| en_US      | 12       | 4.55%   |
| C          | 4        | 1.52%   |
| de_DE      | 3        | 1.14%   |
| fr_FR      | 2        | 0.76%   |
| pl_PL      | 1        | 0.38%   |
| ISO8859-15 | 1        | 0.38%   |
| en_AU      | 1        | 0.38%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 162      | 61.36%  |
| EFI  | 102      | 38.64%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ffs  | 260      | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| MBR  | 179      | 68.58%  |
| GPT  | 82       | 31.42%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUSTek Computer        | 34       | 13.08%  |
| PC Engines              | 33       | 12.69%  |
| Gigabyte Technology     | 24       | 9.23%   |
| Unknown                 | 24       | 9.23%   |
| Dell                    | 20       | 7.69%   |
| Lenovo                  | 16       | 6.15%   |
| ASRock                  | 16       | 6.15%   |
| MSI                     | 15       | 5.77%   |
| Hewlett-Packard         | 14       | 5.38%   |
| Intel                   | 9        | 3.46%   |
| Supermicro              | 6        | 2.31%   |
| Raspberry Pi Foundation | 6        | 2.31%   |
| Apple                   | 5        | 1.92%   |
| Sun                     | 3        | 1.15%   |
| Soekris Engineering     | 3        | 1.15%   |
| Shuttle                 | 2        | 0.77%   |
| Pegatron                | 2        | 0.77%   |
| IBM                     | 2        | 0.77%   |
| Biostar                 | 2        | 0.77%   |
| Acer                    | 2        | 0.77%   |
| ZOTAC                   | 1        | 0.38%   |
| Yanling                 | 1        | 0.38%   |
| WYSE                    | 1        | 0.38%   |
| VIA Technologies        | 1        | 0.38%   |
| Unknown                 | 1        | 0.38%   |
| Sony UK                 | 1        | 0.38%   |
| Sony                    | 1        | 0.38%   |
| Protectli               | 1        | 0.38%   |
| NF541                   | 1        | 0.38%   |
| KOHJINSHA               | 1        | 0.38%   |
| HARDKERNEL              | 1        | 0.38%   |
| Fujitsu                 | 1        | 0.38%   |
| Foxconn                 | 1        | 0.38%   |
| eMachines               | 1        | 0.38%   |
| Elpitech                | 1        | 0.38%   |
| ECT                     | 1        | 0.38%   |
| ECS                     | 1        | 0.38%   |
| CncTion                 | 1        | 0.38%   |
| Clevo                   | 1        | 0.38%   |
| Bluechip Computer       | 1        | 0.38%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| Unknown                           | 28       | 10.77%  |
| PC Engines APU2                   | 15       | 5.77%   |
| PC Engines apu4                   | 9        | 3.46%   |
| PC Engines apu1                   | 5        | 1.92%   |
| Dell PowerEdge R620               | 5        | 1.92%   |
| ASUS All Series                   | 4        | 1.54%   |
| RPi Raspberry Pi 400              | 3        | 1.15%   |
| RPi Raspberry Pi 4 Model B        | 3        | 1.15%   |
| PC Engines APU3                   | 3        | 1.15%   |
| ASUS PRIME H410M-A                | 3        | 1.15%   |
| Soekris Engineering net6501       | 2        | 0.77%   |
| MSI MS-7A34                       | 2        | 0.77%   |
| Gigabyte M68MT-S2P                | 2        | 0.77%   |
| ASUS PRIME X370-PRO               | 2        | 0.77%   |
| ZOTAC XXXXXX                      | 1        | 0.38%   |
| Yanling YL-KBR6L                  | 1        | 0.38%   |
| WYSE D CLASS                      | 1        | 0.38%   |
| VIA VT82C597                      | 1        | 0.38%   |
| Supermicro X8STi                  | 1        | 0.38%   |
| Supermicro X8DTH-i/6/iF/6F        | 1        | 0.38%   |
| Supermicro X7SBL                  | 1        | 0.38%   |
| Supermicro X11SSW-F               | 1        | 0.38%   |
| Supermicro X11DDW-L               | 1        | 0.38%   |
| Supermicro X10SLH-N6-ST031        | 1        | 0.38%   |
| Sun SUNW,T5140                    | 1        | 0.38%   |
| Sun SUNW,Sun-Blade-1500           | 1        | 0.38%   |
| Sun SUNW,Sun-Blade-100            | 1        | 0.38%   |
| Sony VPCL22Z1R                    | 1        | 0.38%   |
| Sony UK Raspberry Pi 4 Model B    | 1        | 0.38%   |
| Soekris Engineering net5501       | 1        | 0.38%   |
| Shuttle DS77U                     | 1        | 0.38%   |
| Shuttle DS437                     | 1        | 0.38%   |
| Protectli FW6                     | 1        | 0.38%   |
| Pegatron SKLD4-P1                 | 1        | 0.38%   |
| Pegatron Compaq dx2400 Microtower | 1        | 0.38%   |
| PC Engines APU                    | 1        | 0.38%   |
| MSI MS-B09012                     | 1        | 0.38%   |
| MSI MS-7D54                       | 1        | 0.38%   |
| MSI MS-7C96                       | 1        | 0.38%   |
| MSI MS-7C82                       | 1        | 0.38%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| Unknown                     | 28       | 10.77%  |
| PC Engines APU2             | 15       | 5.77%   |
| ASUS PRIME                  | 14       | 5.38%   |
| Dell PowerEdge              | 10       | 3.85%   |
| PC Engines apu4             | 9        | 3.46%   |
| Dell OptiPlex               | 8        | 3.08%   |
| Lenovo ThinkCentre          | 7        | 2.69%   |
| RPi Raspberry               | 6        | 2.31%   |
| PC Engines apu1             | 5        | 1.92%   |
| Lenovo ThinkPad             | 5        | 1.92%   |
| HP ProLiant                 | 4        | 1.54%   |
| ASUS All                    | 4        | 1.54%   |
| Sun SUNW                    | 3        | 1.15%   |
| PC Engines APU3             | 3        | 1.15%   |
| HP Compaq                   | 3        | 1.15%   |
| ASUS ROG                    | 3        | 1.15%   |
| Soekris Engineering net6501 | 2        | 0.77%   |
| MSI MS-7A34                 | 2        | 0.77%   |
| Gigabyte M68MT-S2P          | 2        | 0.77%   |
| Gigabyte B450M              | 2        | 0.77%   |
| ASRock X570                 | 2        | 0.77%   |
| ZOTAC XXXXXX                | 1        | 0.38%   |
| Yanling YL-KBR6L            | 1        | 0.38%   |
| WYSE D                      | 1        | 0.38%   |
| VIA VT82C597                | 1        | 0.38%   |
| Supermicro X8STi            | 1        | 0.38%   |
| Supermicro X8DTH-i          | 1        | 0.38%   |
| Supermicro X7SBL            | 1        | 0.38%   |
| Supermicro X11SSW-F         | 1        | 0.38%   |
| Supermicro X11DDW-L         | 1        | 0.38%   |
| Supermicro X10SLH-N6-ST031  | 1        | 0.38%   |
| Sony VPCL22Z1R              | 1        | 0.38%   |
| Sony UK Raspberry           | 1        | 0.38%   |
| Soekris Engineering net5501 | 1        | 0.38%   |
| Shuttle DS77U               | 1        | 0.38%   |
| Shuttle DS437               | 1        | 0.38%   |
| Protectli FW6               | 1        | 0.38%   |
| Pegatron SKLD4-P1           | 1        | 0.38%   |
| Pegatron Compaq             | 1        | 0.38%   |
| PC Engines APU              | 1        | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 31       | 11.92%  |
| Unknown | 30       | 11.54%  |
| 2019    | 25       | 9.62%   |
| 2020    | 22       | 8.46%   |
| 2016    | 21       | 8.08%   |
| 2014    | 17       | 6.54%   |
| 2021    | 15       | 5.77%   |
| 2013    | 12       | 4.62%   |
| 2012    | 11       | 4.23%   |
| 2010    | 11       | 4.23%   |
| 2022    | 10       | 3.85%   |
| 2017    | 10       | 3.85%   |
| 2011    | 9        | 3.46%   |
| 2008    | 8        | 3.08%   |
| 2015    | 7        | 2.69%   |
| 2007    | 7        | 2.69%   |
| 2009    | 5        | 1.92%   |
| 2023    | 3        | 1.15%   |
| 2006    | 2        | 0.77%   |
| 2005    | 1        | 0.38%   |
| 2004    | 1        | 0.38%   |
| 2003    | 1        | 0.38%   |
| 2001    | 1        | 0.38%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 260      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 225      | 86.54%  |
| Yes  | 35       | 13.46%  |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 4.01-8.0        | 60       | 22.47%  |
| 8.01-16.0       | 48       | 17.98%  |
| 16.01-24.0      | 42       | 15.73%  |
| 3.01-4.0        | 24       | 8.99%   |
| 32.01-64.0      | 21       | 7.87%   |
| 2.01-3.0        | 15       | 5.62%   |
| 1.01-2.0        | 15       | 5.62%   |
| 64.01-256.0     | 13       | 4.87%   |
| 24.01-32.0      | 9        | 3.37%   |
| 0.51-1.0        | 9        | 3.37%   |
| 0.01-0.5        | 8        | 3%      |
| More than 256.0 | 3        | 1.12%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 194      | 73.76%  |
| 0.51-1.0   | 29       | 11.03%  |
| 0          | 19       | 7.22%   |
| 1.01-2.0   | 8        | 3.04%   |
| 4.01-8.0   | 5        | 1.9%    |
| Unknown    | 3        | 1.14%   |
| 3.01-4.0   | 2        | 0.76%   |
| 8.01-16.0  | 2        | 0.76%   |
| 16.01-24.0 | 1        | 0.38%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 137      | 49.82%  |
| 2      | 62       | 22.55%  |
| 3      | 36       | 13.09%  |
| 4      | 19       | 6.91%   |
| 5      | 5        | 1.82%   |
| 0      | 5        | 1.82%   |
| 6      | 4        | 1.45%   |
| 10     | 2        | 0.73%   |
| 7      | 2        | 0.73%   |
| 14     | 1        | 0.36%   |
| 12     | 1        | 0.36%   |
| 8      | 1        | 0.36%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 257      | 98.85%  |
| Yes       | 3        | 1.15%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 231      | 88.85%  |
| No        | 29       | 11.15%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 197      | 75.48%  |
| Yes       | 64       | 24.52%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 227      | 87.31%  |
| Yes       | 33       | 12.69%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Russia       | 42       | 16.09%  |
| USA          | 39       | 14.94%  |
| Germany      | 34       | 13.03%  |
| France       | 18       | 6.9%    |
| Italy        | 15       | 5.75%   |
| Netherlands  | 12       | 4.6%    |
| UK           | 11       | 4.21%   |
| Poland       | 10       | 3.83%   |
| Switzerland  | 9        | 3.45%   |
| Spain        | 8        | 3.07%   |
| Austria      | 7        | 2.68%   |
| Canada       | 6        | 2.3%    |
| Ukraine      | 5        | 1.92%   |
| Taiwan       | 5        | 1.92%   |
| Sweden       | 5        | 1.92%   |
| Romania      | 3        | 1.15%   |
| Norway       | 3        | 1.15%   |
| Brazil       | 3        | 1.15%   |
| Australia    | 3        | 1.15%   |
| Mexico       | 2        | 0.77%   |
| Denmark      | 2        | 0.77%   |
| Cyprus       | 2        | 0.77%   |
| Bulgaria     | 2        | 0.77%   |
| UAE          | 1        | 0.38%   |
| Saudi Arabia | 1        | 0.38%   |
| New Zealand  | 1        | 0.38%   |
| Moldova      | 1        | 0.38%   |
| Lithuania    | 1        | 0.38%   |
| Jamaica      | 1        | 0.38%   |
| Indonesia    | 1        | 0.38%   |
| India        | 1        | 0.38%   |
| Hungary      | 1        | 0.38%   |
| Finland      | 1        | 0.38%   |
| Estonia      | 1        | 0.38%   |
| Egypt        | 1        | 0.38%   |
| Czechia      | 1        | 0.38%   |
| Croatia      | 1        | 0.38%   |
| Argentina    | 1        | 0.38%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Moscow                  | 15       | 5.47%   |
| Berlin                  | 9        | 3.28%   |
| Amsterdam               | 7        | 2.55%   |
| Paris                   | 6        | 2.19%   |
| Vladivostok             | 5        | 1.82%   |
| Vienna                  | 5        | 1.82%   |
| New Taipei              | 5        | 1.82%   |
| Milan                   | 5        | 1.82%   |
| St Petersburg           | 4        | 1.46%   |
| Poortugaal              | 4        | 1.46%   |
| Zurich                  | 3        | 1.09%   |
| Wittersham              | 3        | 1.09%   |
| Syeverodonets'k         | 3        | 1.09%   |
| Sydney                  | 3        | 1.09%   |
| Nuremberg               | 3        | 1.09%   |
| Miedziana Gora          | 3        | 1.09%   |
| Malmo                   | 3        | 1.09%   |
| Lausanne                | 3        | 1.09%   |
| Ibiza Town              | 3        | 1.09%   |
| Wroclaw                 | 2        | 0.73%   |
| Svenstrup               | 2        | 0.73%   |
| Sofia                   | 2        | 0.73%   |
| Skien                   | 2        | 0.73%   |
| Saint-Martin-d'HГЁres | 2        | 0.73%   |
| Reutov                  | 2        | 0.73%   |
| Puebla City             | 2        | 0.73%   |
| Orsk                    | 2        | 0.73%   |
| Onalaska                | 2        | 0.73%   |
| Oensingen               | 2        | 0.73%   |
| London                  | 2        | 0.73%   |
| Lebanon                 | 2        | 0.73%   |
| Larnaca                 | 2        | 0.73%   |
| Krasnodar               | 2        | 0.73%   |
| Gummersbach             | 2        | 0.73%   |
| Gdansk                  | 2        | 0.73%   |
| Cambridge               | 2        | 0.73%   |
| Braunschweig            | 2        | 0.73%   |
| Blumenau                | 2        | 0.73%   |
| Barcelona               | 2        | 0.73%   |
| Atlanta                 | 2        | 0.73%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor                             | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| Seagate                            | 51       | 94     | 13.32%  |
| WDC                                | 46       | 70     | 12.01%  |
| NVMe                               | 38       | 56     | 9.92%   |
| Samsung Electronics                | 35       | 80     | 9.14%   |
| Kingston                           | 26       | 36     | 6.79%   |
| Crucial                            | 17       | 28     | 4.44%   |
| OPENBSD                            | 15       | 25     | 3.92%   |
| Toshiba                            | 13       | 22     | 3.39%   |
| Phison                             | 13       | 15     | 3.39%   |
| Hitachi                            | 13       | 23     | 3.39%   |
| SanDisk                            | 12       | 16     | 3.13%   |
| Intel                              | 10       | 15     | 2.61%   |
| HGST                               | 8        | 17     | 2.09%   |
| Dell                               | 7        | 12     | 1.83%   |
| A-DATA Technology                  | 6        | 7      | 1.57%   |
| Transcend                          | 5        | 12     | 1.31%   |
| USB                                | 3        | 3      | 0.78%   |
| OCZ                                | 3        | 3      | 0.78%   |
| LSI                                | 3        | 6      | 0.78%   |
| Hewlett-Packard                    | 3        | 8      | 0.78%   |
| Corsair                            | 3        | 3      | 0.78%   |
| StoreJet                           | 2        | 2      | 0.52%   |
| SPCC                               | 2        | 2      | 0.52%   |
| SK hynix                           | 2        | 2      | 0.52%   |
| PNY                                | 2        | 2      | 0.52%   |
| Patriot                            | 2        | 2      | 0.52%   |
| Multiple                           | 2        | 2      | 0.52%   |
| Maxtor                             | 2        | 3      | 0.52%   |
| KingSpec                           | 2        | 2      | 0.52%   |
| Hoodisk                            | 2        | 3      | 0.52%   |
| Generic                            | 2        | 2      | 0.52%   |
| China                              | 2        | 2      | 0.52%   |
| ASMT                               | 2        | 2      | 0.52%   |
| Apacer                             | 2        | 2      | 0.52%   |
| XPG                                | 1        | 1      | 0.26%   |
| SSDPR-CX                           | 1        | 1      | 0.26%   |
| SABRENT                            | 1        | 1      | 0.26%   |
| Qumo                               | 1        | 1      | 0.26%   |
| Product:              USB DISK 3.0 | 1        | 1      | 0.26%   |
| Product:              USB DISK 2.0 | 1        | 1      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| OPENBSD SR RAID 1 2TB              | 12       | 2.81%   |
| Phison SATA SSD 16GB               | 11       | 2.58%   |
| NVMe Samsung SSD 980 500GB         | 7        | 1.64%   |
| NVMe Samsung SSD 970 250GB         | 5        | 1.17%   |
| Samsung SSD 860 EVO mSATA 500GB    | 4        | 0.94%   |
| Dell PERC H710 282GB               | 4        | 0.94%   |
| WDC WD6400AARS-00Y5B1 640GB        | 3        | 0.7%    |
| USB SanDisk 3.2Gen1 16GB           | 3        | 0.7%    |
| Toshiba MQ04ABF100 1TB             | 3        | 0.7%    |
| Seagate ST3250318AS 250GB          | 3        | 0.7%    |
| Seagate ST250DM000-1BD141 250GB    | 3        | 0.7%    |
| Seagate ST1000DM010-2EP102 1TB     | 3        | 0.7%    |
| SanDisk Ultra Fit 128GB            | 3        | 0.7%    |
| Samsung SSD 860 EVO 500GB          | 3        | 0.7%    |
| Samsung SSD 860 EVO 250GB          | 3        | 0.7%    |
| Samsung SSD 850 EVO 1TB            | 3        | 0.7%    |
| Kingston SUV500MS240G 240GB        | 3        | 0.7%    |
| Kingston SEDC500M480G 480GB        | 3        | 0.7%    |
| HGST HUS724020ALA640 2TB           | 3        | 0.7%    |
| Crucial CT120BX500SSD1 120GB       | 3        | 0.7%    |
| Crucial CT1000MX500SSD1 1TB        | 3        | 0.7%    |
| WDC WD10EADS-00M2B0 1TB            | 2        | 0.47%   |
| WDC WD Elements 25A1 4TB           | 2        | 0.47%   |
| Toshiba HDWG440 4TB                | 2        | 0.47%   |
| Toshiba DT01ACA100 1TB             | 2        | 0.47%   |
| StoreJet Transcend 120GB           | 2        | 0.47%   |
| Seagate ST500DM002-1BD142 500GB    | 2        | 0.47%   |
| Seagate ST3320418AS 320GB          | 2        | 0.47%   |
| Seagate ST1000LM035-1RK172 1TB     | 2        | 0.47%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2        | 0.47%   |
| Seagate ST1000DM003-1CH162 1TB     | 2        | 0.47%   |
| Seagate Expansion 4TB              | 2        | 0.47%   |
| Seagate BUP Slim BK 2TB            | 2        | 0.47%   |
| SanDisk Ultra 32GB                 | 2        | 0.47%   |
| SanDisk Cruzer Blade 64GB          | 2        | 0.47%   |
| Samsung SSD 860 EVO M.2 1TB        | 2        | 0.47%   |
| Samsung SSD 850 EVO M.2 250GB      | 2        | 0.47%   |
| Samsung HD161HJ 160GB              | 2        | 0.47%   |
| Samsung Flash Drive FIT 32GB       | 2        | 0.47%   |
| OPENBSD SR RAID 5 9.9TB            | 2        | 0.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                             | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| Seagate                            | 51       | 94     | 24.06%  |
| WDC                                | 43       | 67     | 20.28%  |
| NVMe                               | 20       | 31     | 9.43%   |
| OPENBSD                            | 15       | 25     | 7.08%   |
| Toshiba                            | 13       | 22     | 6.13%   |
| Hitachi                            | 13       | 23     | 6.13%   |
| Samsung Electronics                | 10       | 18     | 4.72%   |
| HGST                               | 8        | 17     | 3.77%   |
| Dell                               | 7        | 12     | 3.3%    |
| USB                                | 3        | 3      | 1.42%   |
| StoreJet                           | 2        | 2      | 0.94%   |
| Multiple                           | 2        | 2      | 0.94%   |
| Maxtor                             | 2        | 3      | 0.94%   |
| LSI                                | 2        | 4      | 0.94%   |
| Hewlett-Packard                    | 2        | 6      | 0.94%   |
| Generic                            | 2        | 2      | 0.94%   |
| ASMT                               | 2        | 2      | 0.94%   |
| SSDPR-CX                           | 1        | 1      | 0.47%   |
| SABRENT                            | 1        | 1      | 0.47%   |
| Product:              USB DISK 3.0 | 1        | 1      | 0.47%   |
| Product:              USB DISK 2.0 | 1        | 1      | 0.47%   |
| Product:                           | 1        | 1      | 0.47%   |
| Memorex                            | 1        | 1      | 0.47%   |
| MaxDigital                         | 1        | 1      | 0.47%   |
| Lexar                              | 1        | 1      | 0.47%   |
| JetFlash                           | 1        | 1      | 0.47%   |
| IBM-ESXS                           | 1        | 1      | 0.47%   |
| IBM                                | 1        | 1      | 0.47%   |
| General                            | 1        | 1      | 0.47%   |
| Fujitsu                            | 1        | 1      | 0.47%   |
| China                              | 1        | 1      | 0.47%   |
| Apple                              | 1        | 1      | 0.47%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 26       | 36     | 15.2%   |
| Samsung Electronics | 25       | 62     | 14.62%  |
| NVMe                | 18       | 23     | 10.53%  |
| Crucial             | 17       | 28     | 9.94%   |
| Phison              | 13       | 15     | 7.6%    |
| SanDisk             | 12       | 16     | 7.02%   |
| Intel               | 10       | 15     | 5.85%   |
| A-DATA Technology   | 6        | 7      | 3.51%   |
| Transcend           | 5        | 12     | 2.92%   |
| WDC                 | 3        | 3      | 1.75%   |
| OCZ                 | 3        | 3      | 1.75%   |
| Corsair             | 3        | 3      | 1.75%   |
| SPCC                | 2        | 2      | 1.17%   |
| SK hynix            | 2        | 2      | 1.17%   |
| PNY                 | 2        | 2      | 1.17%   |
| Patriot             | 2        | 2      | 1.17%   |
| KingSpec            | 2        | 2      | 1.17%   |
| Hoodisk             | 2        | 3      | 1.17%   |
| Apacer              | 2        | 2      | 1.17%   |
| XPG                 | 1        | 1      | 0.58%   |
| Qumo                | 1        | 1      | 0.58%   |
| MidasForce          | 1        | 1      | 0.58%   |
| Micron Technology   | 1        | 1      | 0.58%   |
| MEMXPRO             | 1        | 1      | 0.58%   |
| LSI                 | 1        | 2      | 0.58%   |
| LITEONIT            | 1        | 1      | 0.58%   |
| KingDian            | 1        | 1      | 0.58%   |
| HPE                 | 1        | 2      | 0.58%   |
| Hewlett-Packard     | 1        | 2      | 0.58%   |
| GOODRAM             | 1        | 1      | 0.58%   |
| GLOWAY              | 1        | 1      | 0.58%   |
| China               | 1        | 1      | 0.58%   |
| ASMedia             | 1        | 1      | 0.58%   |
| Argon               | 1        | 1      | 0.58%   |
| AMD                 | 1        | 1      | 0.58%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 153      | 348    | 51.34%  |
| SSD  | 143      | 257    | 47.99%  |
| NVMe | 2        | 2      | 0.67%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 244      | 605    | 99.19%  |
| NVMe | 2        | 2      | 0.81%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| 0.01-0.5        | 209      | 349    | 63.72%  |
| 0.51-1.0        | 59       | 93     | 17.99%  |
| 1.01-2.0        | 33       | 112    | 10.06%  |
| 3.01-4.0        | 14       | 22     | 4.27%   |
| 4.01-10.0       | 9        | 23     | 2.74%   |
| 2.01-3.0        | 3        | 5      | 0.91%   |
| More than 100.0 | 1        | 1      | 0.3%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 81       | 30%     |
| 251-500        | 67       | 24.81%  |
| 51-100         | 31       | 11.48%  |
| 1-20           | 29       | 10.74%  |
| 21-50          | 21       | 7.78%   |
| 501-1000       | 15       | 5.56%   |
| More than 3000 | 14       | 5.19%   |
| 1001-2000      | 9        | 3.33%   |
| 2001-3000      | 3        | 1.11%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 190      | 69.09%  |
| 21-50          | 26       | 9.45%   |
| 101-250        | 20       | 7.27%   |
| 51-100         | 16       | 5.82%   |
| 251-500        | 7        | 2.55%   |
| 501-1000       | 6        | 2.18%   |
| 1001-2000      | 5        | 1.82%   |
| More than 3000 | 4        | 1.45%   |
| 2001-3000      | 1        | 0.36%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Toshiba MQ04ABF100 1TB                | 2        | 2      | 4.17%   |
| OCZ VERTEX3 120GB                     | 2        | 2      | 4.17%   |
| Kingston SMS200S330G 32GB             | 2        | 4      | 4.17%   |
| HGST HTS541010A7E630 1TB              | 2        | 4      | 4.17%   |
| XPG SX950U 240GB                      | 1        | 1      | 2.08%   |
| WDC WD7500AACS-00ZJB0 752GB           | 1        | 1      | 2.08%   |
| WDC WD6400AAKS-22A7B0 640GB           | 1        | 1      | 2.08%   |
| WDC WD5000AAKX-60U6AA0 500GB          | 1        | 1      | 2.08%   |
| WDC WD1600BEVE-00UYT0 160GB           | 1        | 1      | 2.08%   |
| WDC WD15EARS-00Z5B1 1.5TB             | 1        | 1      | 2.08%   |
| WDC WD10SPZX-24Z10 1TB                | 1        | 1      | 2.08%   |
| WDC WD10EADS-00M2B0 1TB               | 1        | 1      | 2.08%   |
| Transcend 3E128-TS2-550B01 100GB      | 1        | 4      | 2.08%   |
| Toshiba MK5065GSX 500GB               | 1        | 1      | 2.08%   |
| Toshiba DT01ACA100 1TB                | 1        | 1      | 2.08%   |
| Seagate ST9500325AS 500GB             | 1        | 1      | 2.08%   |
| Seagate ST9160310AS 160GB             | 1        | 2      | 2.08%   |
| Seagate ST500DM002-1BD142 500GB       | 1        | 1      | 2.08%   |
| Seagate ST380815AS 80GB               | 1        | 1      | 2.08%   |
| Seagate ST3750640NS 752GB             | 1        | 6      | 2.08%   |
| Seagate ST3320418AS 320GB             | 1        | 1      | 2.08%   |
| Seagate ST3160212SCE 160GB            | 1        | 1      | 2.08%   |
| Seagate ST3120211AS 120GB             | 1        | 1      | 2.08%   |
| Seagate ST250DM000-1BD141 250GB       | 1        | 2      | 2.08%   |
| Seagate ST2000DM006-2DM164 2TB        | 1        | 1      | 2.08%   |
| Seagate ST1000DM003-1CH162 1TB        | 1        | 1      | 2.08%   |
| Samsung Electronics SSD 870 EVO 500GB | 1        | 1      | 2.08%   |
| Samsung Electronics HM160HI 160GB     | 1        | 2      | 2.08%   |
| Samsung Electronics HD753LJ 752GB     | 1        | 1      | 2.08%   |
| Samsung Electronics HD161HJ 160GB     | 1        | 2      | 2.08%   |
| Samsung Electronics HD154UI 1.5TB     | 1        | 1      | 2.08%   |
| Kingston SV300S37A120G 120GB          | 1        | 1      | 2.08%   |
| Kingston SMS200S3120G 120GB           | 1        | 1      | 2.08%   |
| KingSpec P3-512 512GB                 | 1        | 1      | 2.08%   |
| Intel SSDSC2CT180A4 180GB             | 1        | 1      | 2.08%   |
| Intel SSDSC2BB080G4 80GB              | 1        | 1      | 2.08%   |
| Hitachi HDS722516VLAT80 164GB         | 1        | 1      | 2.08%   |
| Hitachi HDS721010CLA332 1TB           | 1        | 2      | 2.08%   |
| Hitachi HDP725016GLA380 160GB         | 1        | 1      | 2.08%   |
| HGST HTS721010A9E630 1TB              | 1        | 1      | 2.08%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 10       | 18     | 21.74%  |
| WDC                 | 6        | 7      | 13.04%  |
| Samsung Electronics | 5        | 7      | 10.87%  |
| Toshiba             | 4        | 4      | 8.7%    |
| Kingston            | 4        | 6      | 8.7%    |
| Hitachi             | 3        | 4      | 6.52%   |
| HGST                | 3        | 5      | 6.52%   |
| OCZ                 | 2        | 2      | 4.35%   |
| Intel               | 2        | 2      | 4.35%   |
| A-DATA Technology   | 2        | 3      | 4.35%   |
| XPG                 | 1        | 1      | 2.17%   |
| Transcend           | 1        | 4      | 2.17%   |
| KingSpec            | 1        | 1      | 2.17%   |
| GLOWAY              | 1        | 1      | 2.17%   |
| Corsair             | 1        | 1      | 2.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 10       | 18     | 33.33%  |
| WDC                 | 6        | 7      | 20%     |
| Toshiba             | 4        | 4      | 13.33%  |
| Samsung Electronics | 4        | 6      | 13.33%  |
| Hitachi             | 3        | 4      | 10%     |
| HGST                | 3        | 5      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 30       | 44     | 65.22%  |
| SSD  | 16       | 22     | 34.78%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| WDC WD6400AARS-00Y5B1 640GB     | 1        | 2      | 50%     |
| Samsung Electronics HD204UI 2TB | 1        | 2      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 1        | 2      | 50%     |
| Samsung Electronics | 1        | 2      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 184      | 391    | 59.35%  |
| Detected | 79       | 146    | 25.48%  |
| Malfunc  | 45       | 66     | 14.52%  |
| Failed   | 2        | 4      | 0.65%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 135      | 45.45%  |
| AMD                            | 84       | 28.28%  |
| Samsung Electronics            | 19       | 6.4%    |
| Broadcom / LSI                 | 14       | 4.71%   |
| SanDisk                        | 7        | 2.36%   |
| Nvidia                         | 5        | 1.68%   |
| VIA Technologies               | 4        | 1.35%   |
| ASMedia Technology             | 4        | 1.35%   |
| Marvell Technology Group       | 3        | 1.01%   |
| ULi Electronics                | 2        | 0.67%   |
| Silicon Motion                 | 2        | 0.67%   |
| Phison Electronics             | 2        | 0.67%   |
| Micron/Crucial Technology      | 2        | 0.67%   |
| Hewlett-Packard                | 2        | 0.67%   |
| ADATA Technology               | 2        | 0.67%   |
| Toshiba                        | 1        | 0.34%   |
| Solid State Storage Technology | 1        | 0.34%   |
| Silicon Image                  | 1        | 0.34%   |
| Shenzhen Longsys Electronics   | 1        | 0.34%   |
| Seagate Technology             | 1        | 0.34%   |
| KIOXIA                         | 1        | 0.34%   |
| Kingston Technology Company    | 1        | 0.34%   |
| HighPoint Technologies         | 1        | 0.34%   |
| Dell                           | 1        | 0.34%   |
| Artop Electronic               | 1        | 0.34%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 40       | 11.33%  |
| AMD FCH SATA Controller [IDE mode]                                             | 17       | 4.82%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 16       | 4.53%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 15       | 4.25%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 10       | 2.83%   |
| AMD 400 Series Chipset SATA Controller                                         | 8        | 2.27%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 7        | 1.98%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 7        | 1.98%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 7        | 1.98%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 7        | 1.98%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 7        | 1.98%   |
| AMD 500 Series Chipset SATA Controller                                         | 7        | 1.98%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6        | 1.7%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 6        | 1.7%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 6        | 1.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 6        | 1.7%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 6        | 1.7%    |
| Nvidia MCP61 SATA Controller                                                   | 5        | 1.42%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 5        | 1.42%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 5        | 1.42%   |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                 | 5        | 1.42%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 4        | 1.13%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]           | 4        | 1.13%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 4        | 1.13%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 3        | 0.85%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 3        | 0.85%   |
| SanDisk unknown                                                                | 3        | 0.85%   |
| Nvidia MCP61 IDE                                                               | 3        | 0.85%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 3        | 0.85%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 3        | 0.85%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 3        | 0.85%   |
| Intel 82801EB (ICH5) SATA Controller                                           | 3        | 0.85%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3        | 0.85%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                   | 3        | 0.85%   |
| ULi M5229 IDE                                                                  | 2        | 0.57%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 2        | 0.57%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2        | 0.57%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 2        | 0.57%   |
| Samsung NVMe SSD Controller 980                                                | 2        | 0.57%   |
| Phison E12 NVMe Controller                                                     | 2        | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 182      | 59.28%  |
| IDE  | 64       | 20.85%  |
| NVMe | 38       | 12.38%  |
| RAID | 14       | 4.56%   |
| SAS  | 5        | 1.63%   |
| SCSI | 4        | 1.3%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 139      | 53.46%  |
| AMD     | 92       | 35.38%  |
| ARM     | 21       | 8.08%   |
| Unknown | 6        | 2.31%   |
| PowerPC | 2        | 0.77%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| AMD GX-412TC SOC                                                 | 27       | 10.31%  |
| ARM Cortex-A72 r0p3                                              | 12       | 4.58%   |
| ARM Cortex-A53 r0p4                                              | 6        | 2.29%   |
| AMD G-T40E Processor                                             | 6        | 2.29%   |
|                                                                  | 6        | 2.29%   |
| Intel Core i5-4570 CPU @ 3.20GHz                                 | 4        | 1.53%   |
| AMD Ryzen 7 5800X 8-Core Processor                               | 4        | 1.53%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz                              | 3        | 1.15%   |
| AMD Ryzen 5 3600 6-Core Processor                                | 3        | 1.15%   |
| Intel Xeon CPU E5520 @ 2.27GHz                                   | 2        | 0.76%   |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz                               | 2        | 0.76%   |
| Intel Xeon CPU E5-2630 0 @ 2.30GHz                               | 2        | 0.76%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz                              | 2        | 0.76%   |
| Intel Core i7-4770K CPU @ 3.50GHz                                | 2        | 0.76%   |
| Intel Core i7-3770 CPU @ 3.40GHz                                 | 2        | 0.76%   |
| Intel Core i5-4570T CPU @ 2.90GHz                                | 2        | 0.76%   |
| Intel Core i3-10100F CPU @ 3.60GHz                               | 2        | 0.76%   |
| Intel Core i3-10100 CPU @ 3.60GHz                                | 2        | 0.76%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz                             | 2        | 0.76%   |
| Intel Celeron N5105 @ 2.00GHz                                    | 2        | 0.76%   |
| Intel Celeron CPU J1900 @ 1.99GHz                                | 2        | 0.76%   |
| Intel Celeron CPU 3865U @ 1.80GHz                                | 2        | 0.76%   |
| Intel Atom CPU N270 @ 1.60GHz ("GenuineIntel" 686-class)         | 2        | 0.76%   |
| AMD Ryzen 7 5700G with Radeon Graphics                           | 2        | 0.76%   |
| AMD Ryzen 7 2700 Eight-Core Processor                            | 2        | 0.76%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics                      | 2        | 0.76%   |
| AMD Geode Integrated Processor by PCS ("AuthenticAMD" 586-class) | 2        | 0.76%   |
| AMD E2-1800 APU with Radeon HD Graphics                          | 2        | 0.76%   |
| AMD Athlon II X3 455 Processor                                   | 2        | 0.76%   |
| PowerPC 7447A (Revision 0x102)                                   | 1        | 0.38%   |
| PowerPC 7447A (Revision 0x101)                                   | 1        | 0.38%   |
| Intel Xeon Gold 5220 CPU @ 2.20GHz                               | 1        | 0.38%   |
| Intel Xeon E-2278G CPU @ 3.40GHz                                 | 1        | 0.38%   |
| Intel Xeon E-2236 CPU @ 3.40GHz                                  | 1        | 0.38%   |
| Intel Xeon CPU X5690 @ 3.47GHz                                   | 1        | 0.38%   |
| Intel Xeon CPU X5680 @ 3.33GHz                                   | 1        | 0.38%   |
| Intel Xeon CPU X5675 @ 3.07GHz                                   | 1        | 0.38%   |
| Intel Xeon CPU X5650 @ 2.67GHz                                   | 1        | 0.38%   |
| Intel Xeon CPU W3530 @ 2.80GHz                                   | 1        | 0.38%   |
| Intel Xeon CPU E5620 @ 2.40GHz                                   | 1        | 0.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Xeon              | 29       | 11.15%  |
| AMD GX                  | 28       | 10.77%  |
| Intel Core i5           | 22       | 8.46%   |
| ARM Cortex              | 21       | 8.08%   |
| Intel Core i7           | 19       | 7.31%   |
| Intel Celeron           | 18       | 6.92%   |
| AMD Ryzen 7             | 15       | 5.77%   |
| Other                   | 14       | 5.38%   |
| Intel Core i3           | 13       | 5%      |
| AMD G                   | 7        | 2.69%   |
| Intel Atom              | 6        | 2.31%   |
| AMD Ryzen 5             | 6        | 2.31%   |
| Intel Pentium 4         | 4        | 1.54%   |
| Intel Core 2 Duo        | 4        | 1.54%   |
| Intel Core 2            | 4        | 1.54%   |
| AMD Ryzen 9             | 4        | 1.54%   |
| Intel Pentium Dual-Core | 3        | 1.15%   |
| Intel Pentium           | 3        | 1.15%   |
| Intel Genuine           | 3        | 1.15%   |
| AMD Ryzen 3             | 3        | 1.15%   |
| AMD Phenom II X4        | 2        | 0.77%   |
| AMD Geode Integrated    | 2        | 0.77%   |
| AMD E2                  | 2        | 0.77%   |
| AMD Athlon II X3        | 2        | 0.77%   |
| AMD Athlon 64 X2        | 2        | 0.77%   |
| AMD Athlon              | 2        | 0.77%   |
| AMD A4                  | 2        | 0.77%   |
| AMD A10                 | 2        | 0.77%   |
| Intel Xeon Gold         | 1        | 0.38%   |
| Intel Pentium III       | 1        | 0.38%   |
| Intel Pentium Dual      | 1        | 0.38%   |
| Intel Pentium D         | 1        | 0.38%   |
| Intel Core i9           | 1        | 0.38%   |
| Intel Core 2 Quad       | 1        | 0.38%   |
| Intel Celeron D         | 1        | 0.38%   |
| AMD Turion II Neo       | 1        | 0.38%   |
| AMD Ryzen 7 PRO         | 1        | 0.38%   |
| AMD Phenom II X6        | 1        | 0.38%   |
| AMD Phenom              | 1        | 0.38%   |
| AMD FX                  | 1        | 0.38%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 91       | 34.87%  |
| Unknown | 59       | 22.61%  |
| 2       | 40       | 15.33%  |
| 1       | 18       | 6.9%    |
| 6       | 15       | 5.75%   |
| 16      | 11       | 4.21%   |
| 8       | 11       | 4.21%   |
| 12      | 9        | 3.45%   |
| 32      | 2        | 0.77%   |
| 24      | 2        | 0.77%   |
| 3       | 2        | 0.77%   |
| 36      | 1        | 0.38%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 182      | 69.47%  |
| Unknown | 70       | 26.72%  |
| 2       | 10       | 3.82%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 125      | 48.08%  |
| Unknown | 72       | 27.69%  |
| 2       | 63       | 24.23%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Unknown       | 44       | 16.92%  |
| Puma          | 28       | 10.77%  |
| Haswell       | 22       | 8.46%   |
| KabyLake      | 17       | 6.54%   |
| SandyBridge   | 12       | 4.62%   |
| K10           | 10       | 3.85%   |
| IvyBridge     | 10       | 3.85%   |
| Bobcat        | 10       | 3.85%   |
| Zen 2         | 9        | 3.46%   |
| Penryn        | 8        | 3.08%   |
| Core          | 8        | 3.08%   |
| Zen 3         | 7        | 2.69%   |
| Silvermont    | 7        | 2.69%   |
| Bonnell       | 7        | 2.69%   |
| Westmere      | 6        | 2.31%   |
| Skylake       | 6        | 2.31%   |
| NetBurst      | 6        | 2.31%   |
| Zen           | 5        | 1.92%   |
| CometLake     | 5        | 1.92%   |
| Zen+          | 4        | 1.54%   |
| Piledriver    | 4        | 1.54%   |
| Nehalem       | 4        | 1.54%   |
| Goldmont      | 3        | 1.15%   |
| Geode         | 3        | 1.15%   |
| Broadwell     | 3        | 1.15%   |
| TigerLake     | 2        | 0.77%   |
| P6            | 2        | 0.77%   |
| K8 Hammer     | 2        | 0.77%   |
| Jaguar        | 2        | 0.77%   |
| Goldmont plus | 2        | 0.77%   |
| K6            | 1        | 0.38%   |
| K10 Llano     | 1        | 0.38%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| AMD                                          | 84       | 40.38%  |
| Intel                                        | 81       | 38.94%  |
| Nvidia                                       | 22       | 10.58%  |
| Matrox Electronics Systems                   | 14       | 6.73%   |
| ASPEED Technology                            | 5        | 2.4%    |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.48%   |
| 3DLabs                                       | 1        | 0.48%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 11       | 5.16%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 11       | 5.16%   |
| Matrox Electronics Systems G200eR2                                                       | 7        | 3.29%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 6        | 2.82%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 6        | 2.82%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 5        | 2.35%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 4        | 1.88%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4        | 1.88%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4        | 1.88%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3        | 1.41%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 3        | 1.41%   |
| Intel HD Graphics 610                                                                    | 3        | 1.41%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3        | 1.41%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3        | 1.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3        | 1.41%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3        | 1.41%   |
| AMD RV711/M93 [Mobility Radeon HD 4350/4550/530v/540v/545v / FirePro RG220]              | 3        | 1.41%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 3        | 1.41%   |
| AMD ES1000                                                                               | 3        | 1.41%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3        | 1.41%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2        | 0.94%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 2        | 0.94%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2        | 0.94%   |
| Matrox Electronics Systems MGA G200EH                                                    | 2        | 0.94%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2        | 0.94%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2        | 0.94%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2        | 0.94%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2        | 0.94%   |
| Intel JasperLake [UHD Graphics]                                                          | 2        | 0.94%   |
| Intel HD Graphics 630                                                                    | 2        | 0.94%   |
| Intel HD Graphics 530                                                                    | 2        | 0.94%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2        | 0.94%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 2        | 0.94%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 2        | 0.94%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                                         | 2        | 0.94%   |
| Intel 82865G Integrated Graphics Controller                                              | 2        | 0.94%   |
| AMD Wrestler [Radeon HD 7340]                                                            | 2        | 0.94%   |
| AMD RV280 [Radeon 9200]                                                                  | 2        | 0.94%   |
| AMD RS880 [Radeon HD 4200]                                                               | 2        | 0.94%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2        | 0.94%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 78       | 29.66%  |
| 1 x Intel      | 69       | 26.24%  |
| Other          | 61       | 23.19%  |
| 1 x Nvidia     | 17       | 6.46%   |
| 1 x Matrox     | 13       | 4.94%   |
| 2 x Intel      | 7        | 2.66%   |
| 1 x ASPEED     | 5        | 1.9%    |
| Intel + Nvidia | 3        | 1.14%   |
| Intel + AMD    | 3        | 1.14%   |
| 2 x AMD        | 2        | 0.76%   |
| AMD + Nvidia   | 2        | 0.76%   |
| 1 x XGI        | 1        | 0.38%   |
| AMD + Matrox   | 1        | 0.38%   |
| 1 x 3DLabs     | 1        | 0.38%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Desktops | Percent |
|---------|----------|---------|
| Free    | 182      | 69.73%  |
| Unknown | 79       | 30.27%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 260      | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Philips              | 16       | 14.16%  |
| Samsung Electronics  | 14       | 12.39%  |
| Dell                 | 13       | 11.5%   |
| Goldstar             | 11       | 9.73%   |
| Ancor Communications | 8        | 7.08%   |
| Iiyama               | 5        | 4.42%   |
| Acer                 | 5        | 4.42%   |
| NEC Computers        | 4        | 3.54%   |
| Lenovo               | 4        | 3.54%   |
| Hewlett-Packard      | 4        | 3.54%   |
| BenQ                 | 4        | 3.54%   |
| AOC                  | 4        | 3.54%   |
| ViewSonic            | 3        | 2.65%   |
| ASUSTek Computer     | 3        | 2.65%   |
| MSI                  | 2        | 1.77%   |
| LG Display           | 2        | 1.77%   |
| Eizo                 | 2        | 1.77%   |
| Vizio                | 1        | 0.88%   |
| SHI                  | 1        | 0.88%   |
| Sceptre Tech         | 1        | 0.88%   |
| Medion               | 1        | 0.88%   |
| InfoVision           | 1        | 0.88%   |
| DSC                  | 1        | 0.88%   |
| Chimei Innolux       | 1        | 0.88%   |
| AU Optronics         | 1        | 0.88%   |
| Apple                | 1        | 0.88%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                  | 10       | 8.62%   |
| Ancor Communications ASUS VW199 ACI19ED 1440x900 410x260mm 19.1-inch   | 3        | 2.59%   |
| Iiyama PL2779QQ IVM6641 3840x2160 600x330mm 27.0-inch                  | 2        | 1.72%   |
| Hewlett-Packard LA2405 HWP284B 1920x1200 520x320mm 24.0-inch           | 2        | 1.72%   |
| Eizo EV2450 ENC2530 1920x1080 530x300mm 24.0-inch                      | 2        | 1.72%   |
| Dell UP2715K DEL40B6 848x480 600x340mm 27.2-inch                       | 2        | 1.72%   |
| Acer V223HQ ACR0070 1920x1080 470x270mm 21.3-inch                      | 2        | 1.72%   |
| Vizio E320i-A0 VIZ0091 1366x768 700x390mm 31.5-inch                    | 1        | 0.86%   |
| ViewSonic VA703-4SERIES VSC6A1E 1280x1024 340x270mm 17.1-inch          | 1        | 0.86%   |
| ViewSonic LCD Monitor VSCE032 2560x1440 530x300mm 24.0-inch            | 1        | 0.86%   |
| ViewSonic LCD Monitor VSCC42B 1920x1080 480x270mm 21.7-inch            | 1        | 0.86%   |
| SHI LCD-TV**** SHI6102 1360x768 700x390mm 31.5-inch                    | 1        | 0.86%   |
| Sceptre Tech Sceptre C35 SPT0DB7 3440x1440 820x350mm 35.1-inch         | 1        | 0.86%   |
| Samsung Electronics T24D390 SAM0B6E 1920x1080 520x290mm 23.4-inch      | 1        | 0.86%   |
| Samsung Electronics SyncMaster SAM03EF 1680x1050 470x300mm 22.0-inch   | 1        | 0.86%   |
| Samsung Electronics SyncMaster SAM03CF 1280x1024 340x270mm 17.1-inch   | 1        | 0.86%   |
| Samsung Electronics SyncMaster SAM026F 1280x1024 380x300mm 19.1-inch   | 1        | 0.86%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x260mm 19.1-inch    | 1        | 0.86%   |
| Samsung Electronics SyncMaster SAM00A1 1280x1024 340x270mm 17.1-inch   | 1        | 0.86%   |
| Samsung Electronics SMB2340 SAM0691 1920x1080 510x290mm 23.1-inch      | 1        | 0.86%   |
| Samsung Electronics SE790C SAM0BFE 3440x1440 800x330mm 34.1-inch       | 1        | 0.86%   |
| Samsung Electronics S24E650 SAM0CC3 1920x1200 520x320mm 24.0-inch      | 1        | 0.86%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 520x290mm 23.4-inch      | 1        | 0.86%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 530x300mm 24.0-inch      | 1        | 0.86%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch  | 1        | 0.86%   |
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1210x680mm 54.6-inch | 1        | 0.86%   |
| Samsung Electronics LCD Monitor SAM0669 1920x1080                      | 1        | 0.86%   |
| Philips PHL 328E9Q PHLC180 1920x1080 700x390mm 31.5-inch               | 1        | 0.86%   |
| Philips PHL 276E8V PHLC18F 3840x2160 600x340mm 27.2-inch               | 1        | 0.86%   |
| Philips PHL 247E6 PHLC0E7 1920x1080 520x290mm 23.4-inch                | 1        | 0.86%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                | 1        | 0.86%   |
| Philips LCD Monitor PHLC00B 1280x1024 340x270mm 17.1-inch              | 1        | 0.86%   |
| Philips 190S PHL086B 1280x1024 380x300mm 19.1-inch                     | 1        | 0.86%   |
| NEC Computers LCD1970NX NEC6662 1280x1024 380x300mm 19.1-inch          | 1        | 0.86%   |
| NEC Computers LCD190V NEC66D3 1280x1024 380x300mm 19.1-inch            | 1        | 0.86%   |
| NEC Computers EX341R NEC2C7A 3440x1440 800x330mm 34.1-inch             | 1        | 0.86%   |
| NEC Computers EA243WM NEC6866 1920x1200 520x320mm 24.0-inch            | 1        | 0.86%   |
| MSI MP242 MSI30A1 1920x1080 530x300mm 24.0-inch                        | 1        | 0.86%   |
| MSI MAG241C MSI3EA2 1920x1080 520x290mm 23.4-inch                      | 1        | 0.86%   |
| Medion LCD Monitor MED09A3 1280x1024 380x300mm 19.1-inch               | 1        | 0.86%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 48       | 44.04%  |
| 1280x1024 (SXGA)   | 13       | 11.93%  |
| 3840x2160 (4K)     | 8        | 7.34%   |
| 1440x900 (WXGA+)   | 8        | 7.34%   |
| 2560x1440 (QHD)    | 6        | 5.5%    |
| 3440x1440          | 5        | 4.59%   |
| 1920x1200 (WUXGA)  | 5        | 4.59%   |
| 1366x768 (WXGA)    | 4        | 3.67%   |
| 1600x900 (HD+)     | 2        | 1.83%   |
| 1600x1200          | 2        | 1.83%   |
| 3840x1080          | 1        | 0.92%   |
| 2560x1080          | 1        | 0.92%   |
| 2200x1650          | 1        | 0.92%   |
| 1680x1050 (WSXGA+) | 1        | 0.92%   |
| 1400x1050          | 1        | 0.92%   |
| 1360x768           | 1        | 0.92%   |
| 1280x800 (WXGA)    | 1        | 0.92%   |
| 1024x768 (XGA)     | 1        | 0.92%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 19       | 17.43%  |
| 21      | 18       | 16.51%  |
| 19      | 14       | 12.84%  |
| 23      | 12       | 11.01%  |
| 27      | 9        | 8.26%   |
| 17      | 7        | 6.42%   |
| 34      | 5        | 4.59%   |
| 31      | 5        | 4.59%   |
| 18      | 3        | 2.75%   |
| 14      | 3        | 2.75%   |
| 13      | 3        | 2.75%   |
| 15      | 2        | 1.83%   |
| 54      | 1        | 0.92%   |
| 49      | 1        | 0.92%   |
| 35      | 1        | 0.92%   |
| 22      | 1        | 0.92%   |
| 20      | 1        | 0.92%   |
| 16      | 1        | 0.92%   |
| 12      | 1        | 0.92%   |
| 9       | 1        | 0.92%   |
| Unknown | 1        | 0.92%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 39       | 35.78%  |
| 401-500     | 30       | 27.52%  |
| 301-350     | 12       | 11.01%  |
| 351-400     | 7        | 6.42%   |
| 601-700     | 6        | 5.5%    |
| 701-800     | 5        | 4.59%   |
| 201-300     | 5        | 4.59%   |
| 1001-1500   | 2        | 1.83%   |
| 801-900     | 1        | 0.92%   |
| 101-200     | 1        | 0.92%   |
| Unknown     | 1        | 0.92%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 67       | 62.62%  |
| 16/10 | 15       | 14.02%  |
| 5/4   | 13       | 12.15%  |
| 21/9  | 6        | 5.61%   |
| 4/3   | 5        | 4.67%   |
| 32/9  | 1        | 0.93%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 38       | 35.85%  |
| 151-200        | 17       | 16.04%  |
| 351-500        | 11       | 10.38%  |
| 301-350        | 9        | 8.49%   |
| 141-150        | 9        | 8.49%   |
| 251-300        | 8        | 7.55%   |
| 81-90          | 4        | 3.77%   |
| 91-100         | 3        | 2.83%   |
| More than 1000 | 1        | 0.94%   |
| 61-70          | 1        | 0.94%   |
| 41-50          | 1        | 0.94%   |
| 121-130        | 1        | 0.94%   |
| 101-110        | 1        | 0.94%   |
| 501-1000       | 1        | 0.94%   |
| Unknown        | 1        | 0.94%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 58       | 53.7%   |
| 101-120       | 27       | 25%     |
| 121-160       | 12       | 11.11%  |
| 161-240       | 5        | 4.63%   |
| 1-50          | 4        | 3.7%    |
| More than 240 | 1        | 0.93%   |
| Unknown       | 1        | 0.93%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 144      | 54.55%  |
| 1     | 112      | 42.42%  |
| 2     | 6        | 2.27%   |
| 3     | 2        | 0.76%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Intel                             | 123      | 40.59%  |
| Realtek Semiconductor             | 104      | 34.32%  |
| Broadcom                          | 18       | 5.94%   |
| Qualcomm Atheros                  | 15       | 4.95%   |
| Qualcomm Atheros Communications   | 7        | 2.31%   |
| TP-Link                           | 5        | 1.65%   |
| U-Blox                            | 4        | 1.32%   |
| VIA Technologies                  | 3        | 0.99%   |
| Ralink                            | 3        | 0.99%   |
| Apple                             | 3        | 0.99%   |
| Oracle/SUN                        | 2        | 0.66%   |
| MediaTek                          | 2        | 0.66%   |
| 3Com                              | 2        | 0.66%   |
| Qcom                              | 1        | 0.33%   |
| National Semiconductor            | 1        | 0.33%   |
| LG Electronics                    | 1        | 0.33%   |
| Huawei Technologies               | 1        | 0.33%   |
| Ericsson Business Mobile Networks | 1        | 0.33%   |
| Emulex                            | 1        | 0.33%   |
| Edimax Technology                 | 1        | 0.33%   |
| Davicom Semiconductor             | 1        | 0.33%   |
| D-Link System                     | 1        | 0.33%   |
| AVM                               | 1        | 0.33%   |
| Aquantia                          | 1        | 0.33%   |
| Accton Technology                 | 1        | 0.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 81       | 23.21%  |
| Intel I211 Gigabit Network Connection                             | 27       | 7.74%   |
| Intel I210 Gigabit Network Connection                             | 22       | 6.3%    |
| Intel 82574L Gigabit Network Connection                           | 12       | 3.44%   |
| Intel I350 Gigabit Network Connection                             | 9        | 2.58%   |
| Intel Ethernet Connection I217-LM                                 | 8        | 2.29%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6        | 1.72%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6        | 1.72%   |
| Qualcomm Atheros AR9271 802.11n                                   | 5        | 1.43%   |
| Intel Wi-Fi 6 AX200                                               | 5        | 1.43%   |
| U-Blox [u-blox 8]                                                 | 4        | 1.15%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4        | 1.15%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 4        | 1.15%   |
| Intel Ethernet Controller I225-V                                  | 4        | 1.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 1.15%   |
| Intel Wireless 7260                                               | 3        | 0.86%   |
| Intel Ethernet Connection (7) I219-LM                             | 3        | 0.86%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 0.86%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 3        | 0.86%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 0.86%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                   | 3        | 0.86%   |
| VIA VT6105M [Rhine-III]                                           | 2        | 0.57%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2        | 0.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2        | 0.57%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 0.57%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 2        | 0.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2        | 0.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2        | 0.57%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 2        | 0.57%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2        | 0.57%   |
| Intel Wi-Fi 6 AX201                                               | 2        | 0.57%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 2        | 0.57%   |
| Intel Platform Controller Hub EG20T Gigabit Ethernet Controller   | 2        | 0.57%   |
| Intel Ethernet Connection I217-V                                  | 2        | 0.57%   |
| Intel 82576 Gigabit Network Connection                            | 2        | 0.57%   |
| Intel 82573L Gigabit Ethernet Controller                          | 2        | 0.57%   |
| Intel 82573E Gigabit Ethernet Controller (Copper)                 | 2        | 0.57%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.57%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 2        | 0.57%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 2        | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 23       | 32.86%  |
| Qualcomm Atheros                | 13       | 18.57%  |
| Realtek Semiconductor           | 12       | 17.14%  |
| Qualcomm Atheros Communications | 7        | 10%     |
| TP-Link                         | 5        | 7.14%   |
| Ralink                          | 3        | 4.29%   |
| MediaTek                        | 2        | 2.86%   |
| Broadcom                        | 2        | 2.86%   |
| Qcom                            | 1        | 1.43%   |
| Edimax Technology               | 1        | 1.43%   |
| D-Link System                   | 1        | 1.43%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR9271 802.11n                                                      | 5        | 7.04%   |
| Intel Wi-Fi 6 AX200                                                                  | 5        | 7.04%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                       | 4        | 5.63%   |
| Intel Wireless 7260                                                                  | 3        | 4.23%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                         | 2        | 2.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                      | 2        | 2.82%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                            | 2        | 2.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 2        | 2.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                       | 2        | 2.82%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                           | 2        | 2.82%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                               | 2        | 2.82%   |
| Intel Wi-Fi 6 AX201                                                                  | 2        | 2.82%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                | 2        | 2.82%   |
| TP-Link Wireless USB Adapter                                                         | 1        | 1.41%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                  | 1        | 1.41%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                  | 1        | 1.41%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                           | 1        | 1.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                             | 1        | 1.41%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                             | 1        | 1.41%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                      | 1        | 1.41%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                      | 1        | 1.41%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                               | 1        | 1.41%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                          | 1        | 1.41%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 1        | 1.41%   |
| Realtek RTL8188EE Wireless Network Adapter                                           | 1        | 1.41%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                           | 1        | 1.41%   |
| Realtek 802.11n WLAN Adapter                                                         | 1        | 1.41%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                            | 1        | 1.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                           | 1        | 1.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                           | 1        | 1.41%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1        | 1.41%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170]        | 1        | 1.41%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                       | 1        | 1.41%   |
| Qcom RT73 USB Wireless LAN Card                                                      | 1        | 1.41%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                        | 1        | 1.41%   |
| MediaTek 802.11ac Wireless LAN Card                                                  | 1        | 1.41%   |
| Intel Wireless 8265 / 8275                                                           | 1        | 1.41%   |
| Intel Wireless 8260                                                                  | 1        | 1.41%   |
| Intel Wireless 3160                                                                  | 1        | 1.41%   |
| Intel Ultimate N WiFi Link 5300                                                      | 1        | 1.41%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 113      | 45.93%  |
| Realtek Semiconductor  | 100      | 40.65%  |
| Broadcom               | 16       | 6.5%    |
| VIA Technologies       | 3        | 1.22%   |
| Apple                  | 3        | 1.22%   |
| Qualcomm Atheros       | 2        | 0.81%   |
| Oracle/SUN             | 2        | 0.81%   |
| 3Com                   | 2        | 0.81%   |
| National Semiconductor | 1        | 0.41%   |
| Emulex                 | 1        | 0.41%   |
| Davicom Semiconductor  | 1        | 0.41%   |
| Aquantia               | 1        | 0.41%   |
| Accton Technology      | 1        | 0.41%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 81       | 30.11%  |
| Intel I211 Gigabit Network Connection                             | 27       | 10.04%  |
| Intel I210 Gigabit Network Connection                             | 22       | 8.18%   |
| Intel 82574L Gigabit Network Connection                           | 12       | 4.46%   |
| Intel I350 Gigabit Network Connection                             | 9        | 3.35%   |
| Intel Ethernet Connection I217-LM                                 | 8        | 2.97%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6        | 2.23%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6        | 2.23%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4        | 1.49%   |
| Intel Ethernet Controller I225-V                                  | 4        | 1.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 1.49%   |
| Intel Ethernet Connection (7) I219-LM                             | 3        | 1.12%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 1.12%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 3        | 1.12%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 1.12%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                   | 3        | 1.12%   |
| VIA VT6105M [Rhine-III]                                           | 2        | 0.74%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 0.74%   |
| Intel Platform Controller Hub EG20T Gigabit Ethernet Controller   | 2        | 0.74%   |
| Intel Ethernet Connection I217-V                                  | 2        | 0.74%   |
| Intel 82576 Gigabit Network Connection                            | 2        | 0.74%   |
| Intel 82573L Gigabit Ethernet Controller                          | 2        | 0.74%   |
| Intel 82573E Gigabit Ethernet Controller (Copper)                 | 2        | 0.74%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.74%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 2        | 0.74%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 2        | 0.74%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2        | 0.74%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 2        | 0.74%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 2        | 0.74%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.37%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1        | 0.37%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1        | 0.37%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.37%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1        | 0.37%   |
| Oracle/SUN RIO 10/100 Ethernet [eri]                              | 1        | 0.37%   |
| Oracle/SUN Multithreaded 10-Gigabit Ethernet Network Controller   | 1        | 0.37%   |
| National DP83815 (MacPhyter) Ethernet Controller                  | 1        | 0.37%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 0.37%   |
| Intel I210 Gigabit Fiber Network Connection                       | 1        | 0.37%   |
| Intel Ethernet Controller I226-V                                  | 1        | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 231      | 75.74%  |
| WiFi     | 65       | 21.31%  |
| Modem    | 6        | 1.97%   |
| Unknown  | 3        | 0.98%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 164      | 83.25%  |
| WiFi     | 33       | 16.75%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 97       | 37.16%  |
| 2     | 64       | 24.52%  |
| 3     | 34       | 13.03%  |
| 4     | 27       | 10.34%  |
| 0     | 27       | 10.34%  |
| 5     | 4        | 1.53%   |
| 8     | 3        | 1.15%   |
| 7     | 2        | 0.77%   |
| 6     | 2        | 0.77%   |
| 12    | 1        | 0.38%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 260      | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 17       | 50%     |
| Cambridge Silicon Radio         | 3        | 8.82%   |
| Realtek Semiconductor           | 2        | 5.88%   |
| Qualcomm Atheros Communications | 2        | 5.88%   |
| IMC Networks                    | 2        | 5.88%   |
| Foxconn / Hon Hai               | 2        | 5.88%   |
| Broadcom                        | 2        | 5.88%   |
| Apple                           | 2        | 5.88%   |
| Hewlett-Packard                 | 1        | 2.94%   |
| ASUSTek Computer                | 1        | 2.94%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                          | 5        | 14.71%  |
| Intel AX200 Bluetooth                                       | 5        | 14.71%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 3        | 8.82%   |
| Realtek Bluetooth Adapter                                   | 2        | 5.88%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2        | 5.88%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2        | 5.88%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 2        | 5.88%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip        | 2        | 5.88%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1        | 2.94%   |
| Intel AX210 Bluetooth                                       | 1        | 2.94%   |
| Intel AX201 Bluetooth                                       | 1        | 2.94%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1        | 2.94%   |
| Foxconn / Hon Hai RZ616 Bluetooth Adapter                   | 1        | 2.94%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1        | 2.94%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 1        | 2.94%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 1        | 2.94%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 1        | 2.94%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1        | 2.94%   |
| Apple Bluetooth Host Controller                             | 1        | 2.94%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 96       | 44.65%  |
| AMD                                  | 76       | 35.35%  |
| Nvidia                               | 18       | 8.37%   |
| C-Media Electronics                  | 7        | 3.26%   |
| VIA Technologies                     | 3        | 1.4%    |
| ULi Electronics                      | 2        | 0.93%   |
| JMTek                                | 2        | 0.93%   |
| Creative Labs                        | 2        | 0.93%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.47%   |
| Texas Instruments                    | 1        | 0.47%   |
| Logitech                             | 1        | 0.47%   |
| Lenovo                               | 1        | 0.47%   |
| Generalplus Technology               | 1        | 0.47%   |
| ESS Technology                       | 1        | 0.47%   |
| Elgato Systems                       | 1        | 0.47%   |
| Dell                                 | 1        | 0.47%   |
| Blue Microphones                     | 1        | 0.47%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                          | 16       | 5.99%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 13       | 4.87%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 11       | 4.12%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 11       | 4.12%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 11       | 4.12%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 9        | 3.37%   |
| Intel Cannon Lake PCH cAVS                                                        | 8        | 3%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 7        | 2.62%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 7        | 2.62%   |
| AMD Navi 10 HDMI Audio                                                            | 7        | 2.62%   |
| AMD FCH Azalia Controller                                                         | 7        | 2.62%   |
| AMD Family 17h/19h HD Audio Controller                                            | 7        | 2.62%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 7        | 2.62%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 6        | 2.25%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 6        | 2.25%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 6        | 2.25%   |
| Intel Comet Lake PCH-V cAVS                                                       | 5        | 1.87%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 5        | 1.87%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 5        | 1.87%   |
| Nvidia MCP61 High Definition Audio                                                | 4        | 1.5%    |
| Nvidia GP106 High Definition Audio Controller                                     | 4        | 1.5%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 4        | 1.5%    |
| Intel Sunrise Point-LP HD Audio                                                   | 3        | 1.12%   |
| Intel 200 Series PCH HD Audio                                                     | 3        | 1.12%   |
| AMD Trinity HDMI Audio Controller                                                 | 3        | 1.12%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 3        | 1.12%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                      | 3        | 1.12%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 3        | 1.12%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 3        | 1.12%   |
| AMD Kabini HDMI/DP Audio                                                          | 3        | 1.12%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 3        | 1.12%   |
| ULi Electronics M5451 PCI AC-Link Controller Audio Device                         | 2        | 0.75%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 2        | 0.75%   |
| Nvidia GF108 High Definition Audio Controller                                     | 2        | 0.75%   |
| JMTek USB PnP Audio Device                                                        | 2        | 0.75%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 2        | 0.75%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 2        | 0.75%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 2        | 0.75%   |
| Intel Jasper Lake HD Audio                                                        | 2        | 0.75%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                 | 2        | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 9        | 37.5%   |
| Kingston            | 5        | 20.83%  |
| Transcend           | 2        | 8.33%   |
| Samsung Electronics | 2        | 8.33%   |
| Corsair             | 2        | 8.33%   |
| SK hynix            | 1        | 4.17%   |
| Ramaxel Technology  | 1        | 4.17%   |
| Nanya Technology    | 1        | 4.17%   |
| Elpida              | 1        | 4.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s       | 3        | 10.34%  |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s          | 2        | 6.9%    |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 2400MT/s     | 2        | 6.9%    |
| Unknown RAM Module 512MB DIMM SDRAM                     | 1        | 3.45%   |
| Unknown RAM Module 512MB DIMM DDR 400MT/s               | 1        | 3.45%   |
| Unknown RAM Module 512MB DIMM 400MT/s                   | 1        | 3.45%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s             | 1        | 3.45%   |
| Unknown RAM Module 256MB DIMM 333MT/s                   | 1        | 3.45%   |
| Unknown RAM Module 2048MB DIMM DDR2 266MT/s             | 1        | 3.45%   |
| Unknown RAM Module 1GB DIMM 400MT/s                     | 1        | 3.45%   |
| Unknown RAM Module 1024MB DIMM DDR                      | 1        | 3.45%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                  | 1        | 3.45%   |
| Transcend RAM TS1GSK64W6H 8GB DIMM DDR3 1600MT/s        | 1        | 3.45%   |
| Transcend RAM TS128MLQ64V6J 1GB DIMM DDR2 667MT/s       | 1        | 3.45%   |
| SK hynix RAM HYMP112U64CP8-Y5 1GB DIMM DDR2 667MT/s     | 1        | 3.45%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s   | 1        | 3.45%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s   | 1        | 3.45%   |
| Samsung RAM M3 78T2953CZ3-CE6 1GB DIMM DDR2 667MT/s     | 1        | 3.45%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s | 1        | 3.45%   |
| Nanya RAM NT1GT64U88D0BY-AD 1024MB DIMM DDR2 800MT/s    | 1        | 3.45%   |
| Kingston RAM KF3600C18D4/32GX 32GB DIMM DDR4 2400MT/s   | 1        | 3.45%   |
| Kingston RAM 9905316-005.A04LF 1GB DIMM DDR2 667MT/s    | 1        | 3.45%   |
| Elpida RAM EBE11UD8AJWA-8G-E 1024MB DIMM DDR2 800MT/s   | 1        | 3.45%   |
| Corsair RAM CML16GX3M2A1600C9 8GB DIMM DDR3 1600MT/s    | 1        | 3.45%   |
| Corsair RAM CMK64GX5M2B5200C40 32GB DIMM DDR5 4800MT/s  | 1        | 3.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 7        | 35%     |
| DDR4    | 4        | 20%     |
| DDR2    | 3        | 15%     |
| DDR     | 2        | 10%     |
| Unknown | 2        | 10%     |
| SDRAM   | 1        | 5%      |
| DDR5    | 1        | 5%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 15       | 75%     |
| SODIMM | 5        | 25%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 7        | 29.17%  |
| 8192  | 5        | 20.83%  |
| 1024  | 5        | 20.83%  |
| 512   | 3        | 12.5%   |
| 32768 | 2        | 8.33%   |
| 2048  | 1        | 4.17%   |
| 256   | 1        | 4.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 2400    | 4        | 19.05%  |
| 1600    | 4        | 19.05%  |
| 1333    | 3        | 14.29%  |
| 800     | 2        | 9.52%   |
| 400     | 2        | 9.52%   |
| Unknown | 2        | 9.52%   |
| 4800    | 1        | 4.76%   |
| 667     | 1        | 4.76%   |
| 333     | 1        | 4.76%   |
| 266     | 1        | 4.76%   |

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


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Logitech                | 4        | 33.33%  |
| Chicony Electronics     | 4        | 33.33%  |
| Microdia                | 2        | 16.67%  |
| Z-Star Microelectronics | 1        | 8.33%   |
| Ricoh                   | 1        | 8.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Chicony Integrated Camera            | 2        | 16.67%  |
| Z-Star Integrated Camera             | 1        | 8.33%   |
| Ricoh USB2.0 Camera                  | 1        | 8.33%   |
| Microdia REDRAGON Live Camera Audio  | 1        | 8.33%   |
| Microdia Ltd., USB  Live camera      | 1        | 8.33%   |
| Logitech Webcam C310                 | 1        | 8.33%   |
| Logitech Webcam C270                 | 1        | 8.33%   |
| Logitech HD Pro Webcam C920          | 1        | 8.33%   |
| Logitech C920 HD Pro Webcam          | 1        | 8.33%   |
| Chicony Ltd., HP 0.3MP Webcam        | 1        | 8.33%   |
| Chicony Integrated Camera [ThinkPad] | 1        | 8.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Validity Sensors           | 1        | 20%     |
| Upek                       | 1        | 20%     |
| STMicroelectronics         | 1        | 20%     |
| Shenzhen Goodix Technology | 1        | 20%     |
| AuthenTec                  | 1        | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 1        | 20%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1        | 20%     |
| STMicroelectronics Fingerprint Reader                  | 1        | 20%     |
| Shenzhen Goodix Fingerprint Reader                     | 1        | 20%     |
| AuthenTec AES2501 Fingerprint Sensor                   | 1        | 20%     |

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
| 0     | 129      | 48.86%  |
| 1     | 82       | 31.06%  |
| 2     | 43       | 16.29%  |
| 3     | 7        | 2.65%   |
| 7     | 2        | 0.76%   |
| 5     | 1        | 0.38%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 89       | 48.37%  |
| Graphics card            | 31       | 16.85%  |
| Firewire controller      | 18       | 9.78%   |
| Net/wireless             | 15       | 8.15%   |
| Net/ethernet             | 10       | 5.43%   |
| Storage/ata              | 8        | 4.35%   |
| Sound                    | 8        | 4.35%   |
| Storage                  | 2        | 1.09%   |
| Storage/raid             | 1        | 0.54%   |
| Storage/ide              | 1        | 0.54%   |
| Network                  | 1        | 0.54%   |

