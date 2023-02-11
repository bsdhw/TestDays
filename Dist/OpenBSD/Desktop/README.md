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

Total: 339

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| Apple         | PowerMac10,1                | [0760ed34c3](https://bsd-hardware.info/?probe=0760ed34c3) | Nov 21, 2022 |
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
| Apple         | PowerMac10,1                | [d098ba539d](https://bsd-hardware.info/?probe=d098ba539d) | May 27, 2021 |
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
| OpenBSD 6.8 | 109      | 38.93%  |
| OpenBSD 7.1 | 50       | 17.86%  |
| OpenBSD 7.0 | 35       | 12.5%   |
| OpenBSD 6.9 | 31       | 11.07%  |
| OpenBSD 7.2 | 28       | 10%     |
| OpenBSD 6.7 | 26       | 9.29%   |
| OpenBSD 6.6 | 1        | 0.36%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| OpenBSD | 245      | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| amd64   | 202      | 82.45%  |
| arm64   | 18       | 7.35%   |
| i386    | 17       | 6.94%   |
| sparc64 | 2        | 0.82%   |
| octeon  | 2        | 0.82%   |
| macppc  | 2        | 0.82%   |
| armv7   | 2        | 0.82%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Console       | 97       | 37.6%   |
| fvwm          | 85       | 32.95%  |
| helloDesktop  | 64       | 24.81%  |
| XFCE          | 9        | 3.49%   |
| i3            | 1        | 0.39%   |
| GNOME         | 1        | 0.39%   |
| Enlightenment | 1        | 0.39%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 127      | 51.21%  |
| X11     | 121      | 48.79%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 236      | 95.16%  |
| SLiM    | 7        | 2.82%   |
| GDM     | 5        | 2.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 212      | 85.14%  |
| ru_RU      | 14       | 5.62%   |
| en_US      | 11       | 4.42%   |
| C          | 4        | 1.61%   |
| de_DE      | 3        | 1.2%    |
| fr_FR      | 2        | 0.8%    |
| pl_PL      | 1        | 0.4%    |
| ISO8859-15 | 1        | 0.4%    |
| en_AU      | 1        | 0.4%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 153      | 61.45%  |
| EFI  | 96       | 38.55%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ffs  | 245      | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| MBR  | 170      | 69.11%  |
| GPT  | 76       | 30.89%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| PC Engines              | 32       | 13.06%  |
| ASUSTek Computer        | 31       | 12.65%  |
| Unknown                 | 23       | 9.39%   |
| Gigabyte Technology     | 22       | 8.98%   |
| Dell                    | 19       | 7.76%   |
| ASRock                  | 16       | 6.53%   |
| MSI                     | 15       | 6.12%   |
| Lenovo                  | 14       | 5.71%   |
| Hewlett-Packard         | 13       | 5.31%   |
| Intel                   | 9        | 3.67%   |
| Supermicro              | 6        | 2.45%   |
| Raspberry Pi Foundation | 6        | 2.45%   |
| Apple                   | 4        | 1.63%   |
| Soekris Engineering     | 3        | 1.22%   |
| Sun                     | 2        | 0.82%   |
| Shuttle                 | 2        | 0.82%   |
| Pegatron                | 2        | 0.82%   |
| IBM                     | 2        | 0.82%   |
| Biostar                 | 2        | 0.82%   |
| Acer                    | 2        | 0.82%   |
| ZOTAC                   | 1        | 0.41%   |
| Yanling                 | 1        | 0.41%   |
| WYSE                    | 1        | 0.41%   |
| Unknown                 | 1        | 0.41%   |
| Sony UK                 | 1        | 0.41%   |
| Sony                    | 1        | 0.41%   |
| Protectli               | 1        | 0.41%   |
| NF541                   | 1        | 0.41%   |
| KOHJINSHA               | 1        | 0.41%   |
| HARDKERNEL              | 1        | 0.41%   |
| Fujitsu                 | 1        | 0.41%   |
| Foxconn                 | 1        | 0.41%   |
| eMachines               | 1        | 0.41%   |
| ECT                     | 1        | 0.41%   |
| ECS                     | 1        | 0.41%   |
| CncTion                 | 1        | 0.41%   |
| Clevo                   | 1        | 0.41%   |
| Bluechip Computer       | 1        | 0.41%   |
| AZW                     | 1        | 0.41%   |
| Alienware               | 1        | 0.41%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| Unknown                           | 27       | 11.02%  |
| PC Engines APU2                   | 14       | 5.71%   |
| PC Engines apu4                   | 9        | 3.67%   |
| PC Engines apu1                   | 5        | 2.04%   |
| Dell PowerEdge R620               | 5        | 2.04%   |
| ASUS All Series                   | 4        | 1.63%   |
| RPi Raspberry Pi 400              | 3        | 1.22%   |
| RPi Raspberry Pi 4 Model B        | 3        | 1.22%   |
| PC Engines APU3                   | 3        | 1.22%   |
| Soekris Engineering net6501       | 2        | 0.82%   |
| MSI MS-7A34                       | 2        | 0.82%   |
| Gigabyte M68MT-S2P                | 2        | 0.82%   |
| ASUS PRIME X370-PRO               | 2        | 0.82%   |
| ASUS PRIME H410M-A                | 2        | 0.82%   |
| Apple PowerMac10,1                | 2        | 0.82%   |
| ZOTAC XXXXXX                      | 1        | 0.41%   |
| Yanling YL-KBR6L                  | 1        | 0.41%   |
| WYSE D CLASS                      | 1        | 0.41%   |
| Supermicro X8STi                  | 1        | 0.41%   |
| Supermicro X8DTH-i/6/iF/6F        | 1        | 0.41%   |
| Supermicro X7SBL                  | 1        | 0.41%   |
| Supermicro X11SSW-F               | 1        | 0.41%   |
| Supermicro X11DDW-L               | 1        | 0.41%   |
| Supermicro X10SLH-N6-ST031        | 1        | 0.41%   |
| Sun SUNW,Sun-Blade-1500           | 1        | 0.41%   |
| Sun SUNW,Sun-Blade-100            | 1        | 0.41%   |
| Sony VPCL22Z1R                    | 1        | 0.41%   |
| Sony UK Raspberry Pi 4 Model B    | 1        | 0.41%   |
| Soekris Engineering net5501       | 1        | 0.41%   |
| Shuttle DS77U                     | 1        | 0.41%   |
| Shuttle DS437                     | 1        | 0.41%   |
| Protectli FW6                     | 1        | 0.41%   |
| Pegatron SKLD4-P1                 | 1        | 0.41%   |
| Pegatron Compaq dx2400 Microtower | 1        | 0.41%   |
| PC Engines APU                    | 1        | 0.41%   |
| MSI MS-B09012                     | 1        | 0.41%   |
| MSI MS-7D54                       | 1        | 0.41%   |
| MSI MS-7C96                       | 1        | 0.41%   |
| MSI MS-7C82                       | 1        | 0.41%   |
| MSI MS-7C56                       | 1        | 0.41%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| Unknown                     | 27       | 11.02%  |
| PC Engines APU2             | 14       | 5.71%   |
| ASUS PRIME                  | 12       | 4.9%    |
| Dell PowerEdge              | 10       | 4.08%   |
| PC Engines apu4             | 9        | 3.67%   |
| Dell OptiPlex               | 7        | 2.86%   |
| RPi Raspberry               | 6        | 2.45%   |
| Lenovo ThinkCentre          | 6        | 2.45%   |
| PC Engines apu1             | 5        | 2.04%   |
| Lenovo ThinkPad             | 5        | 2.04%   |
| HP ProLiant                 | 4        | 1.63%   |
| ASUS All                    | 4        | 1.63%   |
| PC Engines APU3             | 3        | 1.22%   |
| HP Compaq                   | 3        | 1.22%   |
| ASUS ROG                    | 3        | 1.22%   |
| Sun SUNW                    | 2        | 0.82%   |
| Soekris Engineering net6501 | 2        | 0.82%   |
| MSI MS-7A34                 | 2        | 0.82%   |
| Gigabyte M68MT-S2P          | 2        | 0.82%   |
| ASRock X570                 | 2        | 0.82%   |
| Apple PowerMac10            | 2        | 0.82%   |
| ZOTAC XXXXXX                | 1        | 0.41%   |
| Yanling YL-KBR6L            | 1        | 0.41%   |
| WYSE D                      | 1        | 0.41%   |
| Supermicro X8STi            | 1        | 0.41%   |
| Supermicro X8DTH-i          | 1        | 0.41%   |
| Supermicro X7SBL            | 1        | 0.41%   |
| Supermicro X11SSW-F         | 1        | 0.41%   |
| Supermicro X11DDW-L         | 1        | 0.41%   |
| Supermicro X10SLH-N6-ST031  | 1        | 0.41%   |
| Sony VPCL22Z1R              | 1        | 0.41%   |
| Sony UK Raspberry           | 1        | 0.41%   |
| Soekris Engineering net5501 | 1        | 0.41%   |
| Shuttle DS77U               | 1        | 0.41%   |
| Shuttle DS437               | 1        | 0.41%   |
| Protectli FW6               | 1        | 0.41%   |
| Pegatron SKLD4-P1           | 1        | 0.41%   |
| Pegatron Compaq             | 1        | 0.41%   |
| PC Engines APU              | 1        | 0.41%   |
| MSI MS-B09012               | 1        | 0.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 30       | 12.24%  |
| Unknown | 27       | 11.02%  |
| 2019    | 23       | 9.39%   |
| 2020    | 22       | 8.98%   |
| 2016    | 20       | 8.16%   |
| 2014    | 17       | 6.94%   |
| 2021    | 14       | 5.71%   |
| 2013    | 11       | 4.49%   |
| 2012    | 11       | 4.49%   |
| 2022    | 10       | 4.08%   |
| 2010    | 10       | 4.08%   |
| 2017    | 9        | 3.67%   |
| 2011    | 9        | 3.67%   |
| 2008    | 8        | 3.27%   |
| 2015    | 7        | 2.86%   |
| 2007    | 6        | 2.45%   |
| 2009    | 5        | 2.04%   |
| 2006    | 2        | 0.82%   |
| 2005    | 1        | 0.41%   |
| 2004    | 1        | 0.41%   |
| 2003    | 1        | 0.41%   |
| 2001    | 1        | 0.41%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 245      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 211      | 86.12%  |
| Yes  | 34       | 13.88%  |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 4.01-8.0        | 58       | 23.29%  |
| 8.01-16.0       | 43       | 17.27%  |
| 16.01-24.0      | 38       | 15.26%  |
| 3.01-4.0        | 24       | 9.64%   |
| 32.01-64.0      | 18       | 7.23%   |
| 2.01-3.0        | 14       | 5.62%   |
| 1.01-2.0        | 14       | 5.62%   |
| 64.01-256.0     | 12       | 4.82%   |
| 24.01-32.0      | 9        | 3.61%   |
| 0.51-1.0        | 9        | 3.61%   |
| 0.01-0.5        | 7        | 2.81%   |
| More than 256.0 | 3        | 1.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 183      | 74.09%  |
| 0.51-1.0   | 26       | 10.53%  |
| 0          | 18       | 7.29%   |
| 1.01-2.0   | 7        | 2.83%   |
| 4.01-8.0   | 5        | 2.02%   |
| Unknown    | 3        | 1.21%   |
| 3.01-4.0   | 2        | 0.81%   |
| 8.01-16.0  | 2        | 0.81%   |
| 16.01-24.0 | 1        | 0.4%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 129      | 50%     |
| 2      | 58       | 22.48%  |
| 3      | 32       | 12.4%   |
| 4      | 19       | 7.36%   |
| 5      | 5        | 1.94%   |
| 0      | 5        | 1.94%   |
| 6      | 3        | 1.16%   |
| 10     | 2        | 0.78%   |
| 7      | 2        | 0.78%   |
| 14     | 1        | 0.39%   |
| 12     | 1        | 0.39%   |
| 8      | 1        | 0.39%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 242      | 98.78%  |
| Yes       | 3        | 1.22%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 217      | 88.57%  |
| No        | 28       | 11.43%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 186      | 75.61%  |
| Yes       | 60       | 24.39%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 216      | 88.16%  |
| Yes       | 29       | 11.84%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Russia       | 41       | 16.67%  |
| USA          | 37       | 15.04%  |
| Germany      | 32       | 13.01%  |
| France       | 17       | 6.91%   |
| Netherlands  | 12       | 4.88%   |
| Italy        | 12       | 4.88%   |
| UK           | 11       | 4.47%   |
| Poland       | 10       | 4.07%   |
| Switzerland  | 9        | 3.66%   |
| Spain        | 8        | 3.25%   |
| Austria      | 7        | 2.85%   |
| Ukraine      | 5        | 2.03%   |
| Taiwan       | 5        | 2.03%   |
| Sweden       | 5        | 2.03%   |
| Canada       | 5        | 2.03%   |
| Norway       | 3        | 1.22%   |
| Australia    | 3        | 1.22%   |
| Romania      | 2        | 0.81%   |
| Denmark      | 2        | 0.81%   |
| Cyprus       | 2        | 0.81%   |
| Bulgaria     | 2        | 0.81%   |
| UAE          | 1        | 0.41%   |
| Saudi Arabia | 1        | 0.41%   |
| New Zealand  | 1        | 0.41%   |
| Moldova      | 1        | 0.41%   |
| Lithuania    | 1        | 0.41%   |
| Jamaica      | 1        | 0.41%   |
| Indonesia    | 1        | 0.41%   |
| India        | 1        | 0.41%   |
| Hungary      | 1        | 0.41%   |
| Finland      | 1        | 0.41%   |
| Estonia      | 1        | 0.41%   |
| Egypt        | 1        | 0.41%   |
| Czechia      | 1        | 0.41%   |
| Croatia      | 1        | 0.41%   |
| Brazil       | 1        | 0.41%   |
| Argentina    | 1        | 0.41%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Moscow                  | 15       | 5.79%   |
| Berlin                  | 9        | 3.47%   |
| Amsterdam               | 7        | 2.7%    |
| Vladivostok             | 5        | 1.93%   |
| Vienna                  | 5        | 1.93%   |
| Paris                   | 5        | 1.93%   |
| New Taipei              | 5        | 1.93%   |
| St Petersburg           | 4        | 1.54%   |
| Poortugaal              | 4        | 1.54%   |
| Milan                   | 4        | 1.54%   |
| Zurich                  | 3        | 1.16%   |
| Wittersham              | 3        | 1.16%   |
| Syeverodonets'k         | 3        | 1.16%   |
| Sydney                  | 3        | 1.16%   |
| Miedziana Gora          | 3        | 1.16%   |
| Malmo                   | 3        | 1.16%   |
| Lausanne                | 3        | 1.16%   |
| Ibiza Town              | 3        | 1.16%   |
| Wroclaw                 | 2        | 0.77%   |
| Svenstrup               | 2        | 0.77%   |
| Sofia                   | 2        | 0.77%   |
| Skien                   | 2        | 0.77%   |
| Saint-Martin-d'HГЁres | 2        | 0.77%   |
| Reutov                  | 2        | 0.77%   |
| Orsk                    | 2        | 0.77%   |
| Onalaska                | 2        | 0.77%   |
| Oensingen               | 2        | 0.77%   |
| Nuremberg               | 2        | 0.77%   |
| London                  | 2        | 0.77%   |
| Lebanon                 | 2        | 0.77%   |
| Larnaca                 | 2        | 0.77%   |
| Krasnodar               | 2        | 0.77%   |
| Gummersbach             | 2        | 0.77%   |
| Gdansk                  | 2        | 0.77%   |
| Braunschweig            | 2        | 0.77%   |
| Barcelona               | 2        | 0.77%   |
| Atlanta                 | 2        | 0.77%   |
| Anglet                  | 2        | 0.77%   |
| Zhukovskiy              | 1        | 0.39%   |
| Zagreb                  | 1        | 0.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor                             | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| Seagate                            | 50       | 91     | 13.89%  |
| WDC                                | 45       | 68     | 12.5%   |
| NVMe                               | 33       | 47     | 9.17%   |
| Samsung Electronics                | 31       | 67     | 8.61%   |
| Kingston                           | 25       | 33     | 6.94%   |
| Crucial                            | 16       | 26     | 4.44%   |
| OPENBSD                            | 15       | 23     | 4.17%   |
| Phison                             | 13       | 15     | 3.61%   |
| Hitachi                            | 12       | 20     | 3.33%   |
| Toshiba                            | 11       | 16     | 3.06%   |
| SanDisk                            | 11       | 13     | 3.06%   |
| Intel                              | 10       | 15     | 2.78%   |
| HGST                               | 8        | 16     | 2.22%   |
| Dell                               | 7        | 12     | 1.94%   |
| Transcend                          | 5        | 12     | 1.39%   |
| A-DATA Technology                  | 5        | 6      | 1.39%   |
| USB                                | 3        | 3      | 0.83%   |
| OCZ                                | 3        | 3      | 0.83%   |
| LSI                                | 3        | 6      | 0.83%   |
| Hewlett-Packard                    | 3        | 8      | 0.83%   |
| Corsair                            | 3        | 3      | 0.83%   |
| StoreJet                           | 2        | 2      | 0.56%   |
| SPCC                               | 2        | 2      | 0.56%   |
| SK hynix                           | 2        | 2      | 0.56%   |
| PNY                                | 2        | 2      | 0.56%   |
| Multiple                           | 2        | 2      | 0.56%   |
| Maxtor                             | 2        | 3      | 0.56%   |
| KingSpec                           | 2        | 2      | 0.56%   |
| Hoodisk                            | 2        | 3      | 0.56%   |
| Generic                            | 2        | 2      | 0.56%   |
| ASMT                               | 2        | 2      | 0.56%   |
| XPG                                | 1        | 1      | 0.28%   |
| SSDPR-CX                           | 1        | 1      | 0.28%   |
| SABRENT                            | 1        | 1      | 0.28%   |
| Qumo                               | 1        | 1      | 0.28%   |
| Product:              USB DISK 3.0 | 1        | 1      | 0.28%   |
| Product:              USB DISK 2.0 | 1        | 1      | 0.28%   |
| Product:                           | 1        | 1      | 0.28%   |
| Patriot                            | 1        | 1      | 0.28%   |
| MidasForce                         | 1        | 1      | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| OPENBSD SR RAID 1 1TB              | 12       | 2.99%   |
| Phison SATA SSD 16GB               | 11       | 2.74%   |
| NVMe Samsung SSD 980 1TB           | 5        | 1.24%   |
| NVMe Samsung SSD 970 250GB         | 5        | 1.24%   |
| Samsung SSD 860 EVO mSATA 500GB    | 4        | 1%      |
| Dell PERC H710 282GB               | 4        | 1%      |
| WDC WD6400AARS-00Y5B1 640GB        | 3        | 0.75%   |
| USB SanDisk 3.2Gen1 64GB           | 3        | 0.75%   |
| Toshiba MQ04ABF100 1TB             | 3        | 0.75%   |
| Seagate ST3250318AS 250GB          | 3        | 0.75%   |
| Seagate ST250DM000-1BD141 250GB    | 3        | 0.75%   |
| Seagate ST1000DM010-2EP102 1TB     | 3        | 0.75%   |
| SanDisk Ultra Fit 128GB            | 3        | 0.75%   |
| Samsung SSD 860 EVO 500GB          | 3        | 0.75%   |
| Samsung SSD 860 EVO 250GB          | 3        | 0.75%   |
| Kingston SUV500MS240G 240GB        | 3        | 0.75%   |
| HGST HUS724020ALA640 2TB           | 3        | 0.75%   |
| Crucial CT120BX500SSD1 120GB       | 3        | 0.75%   |
| Crucial CT1000MX500SSD1 1TB        | 3        | 0.75%   |
| WDC WD10EADS-00M2B0 1TB            | 2        | 0.5%    |
| WDC WD Elements 25A1 4TB           | 2        | 0.5%    |
| Toshiba HDWG440 4TB                | 2        | 0.5%    |
| StoreJet Transcend 120GB           | 2        | 0.5%    |
| Seagate ST500DM002-1BD142 500GB    | 2        | 0.5%    |
| Seagate ST3320418AS 320GB          | 2        | 0.5%    |
| Seagate ST1000LM035-1RK172 1TB     | 2        | 0.5%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2        | 0.5%    |
| Seagate ST1000DM003-1CH162 1TB     | 2        | 0.5%    |
| Seagate Expansion 4TB              | 2        | 0.5%    |
| Seagate BUP Slim BK 2TB            | 2        | 0.5%    |
| SanDisk Ultra 32GB                 | 2        | 0.5%    |
| Samsung SSD 860 EVO M.2 1TB        | 2        | 0.5%    |
| Samsung SSD 850 EVO M.2 250GB      | 2        | 0.5%    |
| Samsung SSD 850 EVO 1TB            | 2        | 0.5%    |
| Samsung HD161HJ 160GB              | 2        | 0.5%    |
| Samsung Flash Drive FIT 32GB       | 2        | 0.5%    |
| OPENBSD SR RAID 5 9.9TB            | 2        | 0.5%    |
| OCZ VERTEX3 120GB                  | 2        | 0.5%    |
| NVMe Samsung SSD 960 500GB         | 2        | 0.5%    |
| NVMe CT500P2SSD8 500GB             | 2        | 0.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                             | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| Seagate                            | 50       | 91     | 24.75%  |
| WDC                                | 42       | 65     | 20.79%  |
| NVMe                               | 17       | 25     | 8.42%   |
| OPENBSD                            | 15       | 23     | 7.43%   |
| Hitachi                            | 12       | 20     | 5.94%   |
| Toshiba                            | 11       | 16     | 5.45%   |
| Samsung Electronics                | 9        | 14     | 4.46%   |
| HGST                               | 8        | 16     | 3.96%   |
| Dell                               | 7        | 12     | 3.47%   |
| USB                                | 3        | 3      | 1.49%   |
| LSI                                | 3        | 6      | 1.49%   |
| StoreJet                           | 2        | 2      | 0.99%   |
| Multiple                           | 2        | 2      | 0.99%   |
| Maxtor                             | 2        | 3      | 0.99%   |
| Hewlett-Packard                    | 2        | 6      | 0.99%   |
| Generic                            | 2        | 2      | 0.99%   |
| ASMT                               | 2        | 2      | 0.99%   |
| SSDPR-CX                           | 1        | 1      | 0.5%    |
| SABRENT                            | 1        | 1      | 0.5%    |
| Product:              USB DISK 3.0 | 1        | 1      | 0.5%    |
| Product:              USB DISK 2.0 | 1        | 1      | 0.5%    |
| Product:                           | 1        | 1      | 0.5%    |
| MaxDigital                         | 1        | 1      | 0.5%    |
| Lexar                              | 1        | 1      | 0.5%    |
| JetFlash                           | 1        | 1      | 0.5%    |
| IBM                                | 1        | 1      | 0.5%    |
| General                            | 1        | 1      | 0.5%    |
| Fujitsu                            | 1        | 1      | 0.5%    |
| China                              | 1        | 1      | 0.5%    |
| Apple                              | 1        | 1      | 0.5%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 25       | 33     | 15.82%  |
| Samsung Electronics | 22       | 53     | 13.92%  |
| NVMe                | 16       | 20     | 10.13%  |
| Crucial             | 16       | 26     | 10.13%  |
| Phison              | 13       | 15     | 8.23%   |
| SanDisk             | 11       | 13     | 6.96%   |
| Intel               | 10       | 15     | 6.33%   |
| Transcend           | 5        | 12     | 3.16%   |
| A-DATA Technology   | 5        | 6      | 3.16%   |
| WDC                 | 3        | 3      | 1.9%    |
| OCZ                 | 3        | 3      | 1.9%    |
| Corsair             | 3        | 3      | 1.9%    |
| SPCC                | 2        | 2      | 1.27%   |
| SK hynix            | 2        | 2      | 1.27%   |
| PNY                 | 2        | 2      | 1.27%   |
| KingSpec            | 2        | 2      | 1.27%   |
| Hoodisk             | 2        | 3      | 1.27%   |
| XPG                 | 1        | 1      | 0.63%   |
| Qumo                | 1        | 1      | 0.63%   |
| Patriot             | 1        | 1      | 0.63%   |
| MidasForce          | 1        | 1      | 0.63%   |
| Micron Technology   | 1        | 1      | 0.63%   |
| MEMXPRO             | 1        | 1      | 0.63%   |
| LITEONIT            | 1        | 1      | 0.63%   |
| KingDian            | 1        | 1      | 0.63%   |
| HPE                 | 1        | 2      | 0.63%   |
| Hewlett-Packard     | 1        | 2      | 0.63%   |
| GOODRAM             | 1        | 1      | 0.63%   |
| GLOWAY              | 1        | 1      | 0.63%   |
| ASMedia             | 1        | 1      | 0.63%   |
| Argon               | 1        | 1      | 0.63%   |
| Apacer              | 1        | 1      | 0.63%   |
| AMD                 | 1        | 1      | 0.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 144      | 321    | 51.99%  |
| SSD  | 131      | 231    | 47.29%  |
| NVMe | 2        | 2      | 0.72%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 230      | 552    | 99.14%  |
| NVMe | 2        | 2      | 0.86%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| 0.01-0.5        | 191      | 308    | 61.81%  |
| 0.51-1.0        | 69       | 118    | 22.33%  |
| 1.01-2.0        | 23       | 81     | 7.44%   |
| 3.01-4.0        | 14       | 22     | 4.53%   |
| 4.01-10.0       | 8        | 17     | 2.59%   |
| 2.01-3.0        | 3        | 5      | 0.97%   |
| More than 100.0 | 1        | 1      | 0.32%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 75       | 29.64%  |
| 251-500        | 65       | 25.69%  |
| 1-20           | 28       | 11.07%  |
| 51-100         | 27       | 10.67%  |
| 21-50          | 20       | 7.91%   |
| More than 3000 | 13       | 5.14%   |
| 501-1000       | 13       | 5.14%   |
| 1001-2000      | 9        | 3.56%   |
| 2001-3000      | 3        | 1.19%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 179      | 69.38%  |
| 21-50          | 26       | 10.08%  |
| 101-250        | 19       | 7.36%   |
| 51-100         | 13       | 5.04%   |
| 251-500        | 6        | 2.33%   |
| 501-1000       | 6        | 2.33%   |
| 1001-2000      | 5        | 1.94%   |
| More than 3000 | 3        | 1.16%   |
| 2001-3000      | 1        | 0.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Toshiba MQ04ABF100 1TB            | 2        | 2      | 4.65%   |
| OCZ VERTEX3 120GB                 | 2        | 2      | 4.65%   |
| Kingston SMS200S330G 32GB         | 2        | 4      | 4.65%   |
| HGST HTS541010A7E630 1TB          | 2        | 4      | 4.65%   |
| XPG SX950U 240GB                  | 1        | 1      | 2.33%   |
| WDC WD7500AACS-00ZJB0 752GB       | 1        | 1      | 2.33%   |
| WDC WD6400AAKS-22A7B0 640GB       | 1        | 1      | 2.33%   |
| WDC WD5000AAKX-60U6AA0 500GB      | 1        | 1      | 2.33%   |
| WDC WD1600BEVE-00UYT0 160GB       | 1        | 1      | 2.33%   |
| WDC WD15EARS-00Z5B1 1.5TB         | 1        | 1      | 2.33%   |
| WDC WD10SPZX-24Z10 1TB            | 1        | 1      | 2.33%   |
| WDC WD10EADS-00M2B0 1TB           | 1        | 1      | 2.33%   |
| Transcend 3E128-TS2-550B01 100GB  | 1        | 4      | 2.33%   |
| Toshiba MK5065GSX 500GB           | 1        | 1      | 2.33%   |
| Seagate ST9500325AS 500GB         | 1        | 1      | 2.33%   |
| Seagate ST9160310AS 160GB         | 1        | 2      | 2.33%   |
| Seagate ST500DM002-1BD142 500GB   | 1        | 1      | 2.33%   |
| Seagate ST380815AS 80GB           | 1        | 1      | 2.33%   |
| Seagate ST3750640NS 752GB         | 1        | 6      | 2.33%   |
| Seagate ST3320418AS 320GB         | 1        | 1      | 2.33%   |
| Seagate ST3160212SCE 160GB        | 1        | 1      | 2.33%   |
| Seagate ST3120211AS 120GB         | 1        | 1      | 2.33%   |
| Seagate ST250DM000-1BD141 250GB   | 1        | 2      | 2.33%   |
| Seagate ST2000DM006-2DM164 2TB    | 1        | 1      | 2.33%   |
| Seagate ST1000DM003-1CH162 1TB    | 1        | 1      | 2.33%   |
| Samsung Electronics HD753LJ 752GB | 1        | 1      | 2.33%   |
| Samsung Electronics HD161HJ 160GB | 1        | 1      | 2.33%   |
| Samsung Electronics HD154UI 1.5TB | 1        | 1      | 2.33%   |
| Kingston SV300S37A120G 120GB      | 1        | 1      | 2.33%   |
| Kingston SMS200S3120G 120GB       | 1        | 1      | 2.33%   |
| KingSpec P3-512 512GB             | 1        | 1      | 2.33%   |
| Intel SSDSC2CT180A4 180GB         | 1        | 1      | 2.33%   |
| Intel SSDSC2BB080G4 80GB          | 1        | 1      | 2.33%   |
| Hitachi HDS721010CLA332 1TB       | 1        | 2      | 2.33%   |
| Hitachi HDP725016GLA380 160GB     | 1        | 1      | 2.33%   |
| HGST HTS721010A9E630 1TB          | 1        | 1      | 2.33%   |
| GLOWAY FER60GS3-S7 64GB           | 1        | 1      | 2.33%   |
| Corsair Force LS SSD 120GB        | 1        | 1      | 2.33%   |
| A-DATA Technology SU630 240GB     | 1        | 2      | 2.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 10       | 18     | 24.39%  |
| WDC                 | 6        | 7      | 14.63%  |
| Kingston            | 4        | 6      | 9.76%   |
| Toshiba             | 3        | 3      | 7.32%   |
| Samsung Electronics | 3        | 3      | 7.32%   |
| HGST                | 3        | 5      | 7.32%   |
| OCZ                 | 2        | 2      | 4.88%   |
| Intel               | 2        | 2      | 4.88%   |
| Hitachi             | 2        | 3      | 4.88%   |
| XPG                 | 1        | 1      | 2.44%   |
| Transcend           | 1        | 4      | 2.44%   |
| KingSpec            | 1        | 1      | 2.44%   |
| GLOWAY              | 1        | 1      | 2.44%   |
| Corsair             | 1        | 1      | 2.44%   |
| A-DATA Technology   | 1        | 2      | 2.44%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 10       | 18     | 37.04%  |
| WDC                 | 6        | 7      | 22.22%  |
| Toshiba             | 3        | 3      | 11.11%  |
| Samsung Electronics | 3        | 3      | 11.11%  |
| HGST                | 3        | 5      | 11.11%  |
| Hitachi             | 2        | 3      | 7.41%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 27       | 39     | 65.85%  |
| SSD  | 14       | 20     | 34.15%  |

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
| Works    | 174      | 354    | 59.79%  |
| Detected | 75       | 137    | 25.77%  |
| Malfunc  | 40       | 59     | 13.75%  |
| Failed   | 2        | 4      | 0.69%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 129      | 46.57%  |
| AMD                          | 79       | 28.52%  |
| Samsung Electronics          | 16       | 5.78%   |
| Broadcom / LSI               | 13       | 4.69%   |
| SanDisk                      | 7        | 2.53%   |
| Nvidia                       | 5        | 1.81%   |
| ASMedia Technology           | 4        | 1.44%   |
| VIA Technologies             | 3        | 1.08%   |
| ULi Electronics              | 2        | 0.72%   |
| Phison Electronics           | 2        | 0.72%   |
| Micron/Crucial Technology    | 2        | 0.72%   |
| Marvell Technology Group     | 2        | 0.72%   |
| Hewlett-Packard              | 2        | 0.72%   |
| ADATA Technology             | 2        | 0.72%   |
| Toshiba                      | 1        | 0.36%   |
| Silicon Motion               | 1        | 0.36%   |
| Silicon Image                | 1        | 0.36%   |
| Shenzhen Longsys Electronics | 1        | 0.36%   |
| Seagate Technology           | 1        | 0.36%   |
| KIOXIA                       | 1        | 0.36%   |
| Kingston Technology Company  | 1        | 0.36%   |
| HighPoint Technologies       | 1        | 0.36%   |
| Dell                         | 1        | 0.36%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 37       | 11.18%  |
| AMD FCH SATA Controller [IDE mode]                                             | 16       | 4.83%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 15       | 4.53%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 14       | 4.23%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 10       | 3.02%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 7        | 2.11%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 7        | 2.11%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 7        | 2.11%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 7        | 2.11%   |
| AMD 500 Series Chipset SATA Controller                                         | 7        | 2.11%   |
| AMD 400 Series Chipset SATA Controller                                         | 7        | 2.11%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 6        | 1.81%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 6        | 1.81%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 6        | 1.81%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 6        | 1.81%   |
| Nvidia MCP61 SATA Controller                                                   | 5        | 1.51%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 5        | 1.51%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 5        | 1.51%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 5        | 1.51%   |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                 | 5        | 1.51%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4        | 1.21%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 4        | 1.21%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]           | 4        | 1.21%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 4        | 1.21%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 3        | 0.91%   |
| Sandisk unknown                                                                | 3        | 0.91%   |
| Nvidia MCP61 IDE                                                               | 3        | 0.91%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 3        | 0.91%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 3        | 0.91%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 3        | 0.91%   |
| Intel 82801EB (ICH5) SATA Controller                                           | 3        | 0.91%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                   | 3        | 0.91%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 2        | 0.6%    |
| ULi M5229 IDE                                                                  | 2        | 0.6%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2        | 0.6%    |
| Samsung NVMe SSD Controller 980                                                | 2        | 0.6%    |
| Phison E12 NVMe Controller                                                     | 2        | 0.6%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2        | 0.6%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2        | 0.6%    |
| Intel Platform Controller Hub EG20T SATA AHCI Controller                       | 2        | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 173      | 60.49%  |
| IDE  | 60       | 20.98%  |
| NVMe | 33       | 11.54%  |
| RAID | 14       | 4.9%    |
| SAS  | 5        | 1.75%   |
| SCSI | 1        | 0.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 133      | 54.29%  |
| AMD     | 86       | 35.1%   |
| ARM     | 20       | 8.16%   |
| Unknown | 4        | 1.63%   |
| PowerPC | 2        | 0.82%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| AMD GX-412TC SOC                                                 | 26       | 10.57%  |
| ARM Cortex-A72 r0p3                                              | 12       | 4.88%   |
| ARM Cortex-A53 r0p4                                              | 6        | 2.44%   |
| AMD G-T40E Processor                                             | 6        | 2.44%   |
| AMD Ryzen 7 5800X 8-Core Processor                               | 4        | 1.63%   |
|                                                                  | 4        | 1.63%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz                              | 3        | 1.22%   |
| Intel Core i5-4570 CPU @ 3.20GHz                                 | 3        | 1.22%   |
| AMD Ryzen 5 3600 6-Core Processor                                | 3        | 1.22%   |
| Intel Xeon CPU E5520 @ 2.27GHz                                   | 2        | 0.81%   |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz                               | 2        | 0.81%   |
| Intel Xeon CPU E5-2630 0 @ 2.30GHz                               | 2        | 0.81%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz                              | 2        | 0.81%   |
| Intel Core i7-4770K CPU @ 3.50GHz                                | 2        | 0.81%   |
| Intel Core i7-3770 CPU @ 3.40GHz                                 | 2        | 0.81%   |
| Intel Core i5-4570T CPU @ 2.90GHz                                | 2        | 0.81%   |
| Intel Core i3-10100F CPU @ 3.60GHz                               | 2        | 0.81%   |
| Intel Core i3-10100 CPU @ 3.60GHz                                | 2        | 0.81%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz                             | 2        | 0.81%   |
| Intel Celeron N5105 @ 2.00GHz                                    | 2        | 0.81%   |
| Intel Celeron CPU J1900 @ 1.99GHz                                | 2        | 0.81%   |
| Intel Celeron CPU 3865U @ 1.80GHz                                | 2        | 0.81%   |
| Intel Atom CPU N270 @ 1.60GHz ("GenuineIntel" 686-class)         | 2        | 0.81%   |
| AMD Ryzen 7 5700G with Radeon Graphics                           | 2        | 0.81%   |
| AMD Ryzen 7 2700 Eight-Core Processor                            | 2        | 0.81%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics                      | 2        | 0.81%   |
| AMD Geode Integrated Processor by PCS ("AuthenticAMD" 586-class) | 2        | 0.81%   |
| AMD E2-1800 APU with Radeon HD Graphics                          | 2        | 0.81%   |
| AMD Athlon II X3 455 Processor                                   | 2        | 0.81%   |
| PowerPC 7447A (Revision 0x102)                                   | 1        | 0.41%   |
| PowerPC 7447A (Revision 0x101)                                   | 1        | 0.41%   |
| Intel Xeon Gold 5220 CPU @ 2.20GHz                               | 1        | 0.41%   |
| Intel Xeon E-2278G CPU @ 3.40GHz                                 | 1        | 0.41%   |
| Intel Xeon E-2236 CPU @ 3.40GHz                                  | 1        | 0.41%   |
| Intel Xeon CPU X5690 @ 3.47GHz                                   | 1        | 0.41%   |
| Intel Xeon CPU X5680 @ 3.33GHz                                   | 1        | 0.41%   |
| Intel Xeon CPU X5675 @ 3.07GHz                                   | 1        | 0.41%   |
| Intel Xeon CPU X5650 @ 2.67GHz                                   | 1        | 0.41%   |
| Intel Xeon CPU W3530 @ 2.80GHz                                   | 1        | 0.41%   |
| Intel Xeon CPU E5620 @ 2.40GHz                                   | 1        | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Xeon              | 28       | 11.43%  |
| AMD GX                  | 27       | 11.02%  |
| Intel Core i5           | 20       | 8.16%   |
| ARM Cortex              | 20       | 8.16%   |
| Intel Celeron           | 18       | 7.35%   |
| Intel Core i7           | 17       | 6.94%   |
| Intel Core i3           | 13       | 5.31%   |
| AMD Ryzen 7             | 13       | 5.31%   |
| Other                   | 10       | 4.08%   |
| AMD G                   | 7        | 2.86%   |
| Intel Atom              | 6        | 2.45%   |
| AMD Ryzen 5             | 6        | 2.45%   |
| Intel Pentium 4         | 4        | 1.63%   |
| Intel Core 2 Duo        | 4        | 1.63%   |
| Intel Core 2            | 4        | 1.63%   |
| AMD Ryzen 9             | 4        | 1.63%   |
| Intel Pentium Dual-Core | 3        | 1.22%   |
| Intel Pentium           | 3        | 1.22%   |
| Intel Genuine           | 3        | 1.22%   |
| AMD Ryzen 3             | 3        | 1.22%   |
| AMD Phenom II X4        | 2        | 0.82%   |
| AMD Geode Integrated    | 2        | 0.82%   |
| AMD E2                  | 2        | 0.82%   |
| AMD Athlon II X3        | 2        | 0.82%   |
| AMD Athlon 64 X2        | 2        | 0.82%   |
| AMD Athlon              | 2        | 0.82%   |
| AMD A4                  | 2        | 0.82%   |
| AMD A10                 | 2        | 0.82%   |
| Intel Xeon Gold         | 1        | 0.41%   |
| Intel Pentium III       | 1        | 0.41%   |
| Intel Pentium Dual      | 1        | 0.41%   |
| Intel Pentium D         | 1        | 0.41%   |
| Intel Core i9           | 1        | 0.41%   |
| Intel Core 2 Quad       | 1        | 0.41%   |
| Intel Celeron D         | 1        | 0.41%   |
| AMD Turion II Neo       | 1        | 0.41%   |
| AMD Ryzen 7 PRO         | 1        | 0.41%   |
| AMD Phenom II X6        | 1        | 0.41%   |
| AMD FX                  | 1        | 0.41%   |
| AMD E1                  | 1        | 0.41%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 85       | 34.55%  |
| Unknown | 55       | 22.36%  |
| 2       | 39       | 15.85%  |
| 1       | 17       | 6.91%   |
| 6       | 15       | 6.1%    |
| 8       | 10       | 4.07%   |
| 16      | 9        | 3.66%   |
| 12      | 9        | 3.66%   |
| 32      | 2        | 0.81%   |
| 24      | 2        | 0.81%   |
| 3       | 2        | 0.81%   |
| 36      | 1        | 0.41%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 171      | 69.23%  |
| Unknown | 66       | 26.72%  |
| 2       | 10       | 4.05%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 117      | 47.76%  |
| Unknown | 68       | 27.76%  |
| 2       | 60       | 24.49%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Unknown       | 40       | 16.33%  |
| Puma          | 27       | 11.02%  |
| Haswell       | 21       | 8.57%   |
| KabyLake      | 15       | 6.12%   |
| SandyBridge   | 12       | 4.9%    |
| IvyBridge     | 10       | 4.08%   |
| Bobcat        | 10       | 4.08%   |
| Zen 2         | 9        | 3.67%   |
| K10           | 9        | 3.67%   |
| Penryn        | 8        | 3.27%   |
| Silvermont    | 7        | 2.86%   |
| Core          | 7        | 2.86%   |
| Bonnell       | 7        | 2.86%   |
| Zen 3         | 6        | 2.45%   |
| Westmere      | 6        | 2.45%   |
| Skylake       | 6        | 2.45%   |
| NetBurst      | 6        | 2.45%   |
| Zen           | 5        | 2.04%   |
| Zen+          | 4        | 1.63%   |
| Nehalem       | 4        | 1.63%   |
| CometLake     | 4        | 1.63%   |
| Piledriver    | 3        | 1.22%   |
| Goldmont      | 3        | 1.22%   |
| Broadwell     | 3        | 1.22%   |
| P6            | 2        | 0.82%   |
| K8 Hammer     | 2        | 0.82%   |
| Jaguar        | 2        | 0.82%   |
| Goldmont plus | 2        | 0.82%   |
| Geode         | 2        | 0.82%   |
| TigerLake     | 1        | 0.41%   |
| K6            | 1        | 0.41%   |
| K10 Llano     | 1        | 0.41%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| AMD                                          | 79       | 40.72%  |
| Intel                                        | 76       | 39.18%  |
| Nvidia                                       | 18       | 9.28%   |
| Matrox Electronics Systems                   | 14       | 7.22%   |
| ASPEED Technology                            | 5        | 2.58%   |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.52%   |
| 3DLabs                                       | 1        | 0.52%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 11       | 5.53%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 10       | 5.03%   |
| Matrox Electronics Systems G200eR2                                                       | 7        | 3.52%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 6        | 3.02%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 6        | 3.02%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 5        | 2.51%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 4        | 2.01%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4        | 2.01%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4        | 2.01%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3        | 1.51%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 3        | 1.51%   |
| Intel HD Graphics 610                                                                    | 3        | 1.51%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3        | 1.51%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3        | 1.51%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3        | 1.51%   |
| AMD RV710/M92 [Mobility Radeon HD 4350/4550]                                             | 3        | 1.51%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 3        | 1.51%   |
| AMD ES1000                                                                               | 3        | 1.51%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3        | 1.51%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 2        | 1.01%   |
| Matrox Electronics Systems MGA G200EH                                                    | 2        | 1.01%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2        | 1.01%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2        | 1.01%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2        | 1.01%   |
| Intel JasperLake [UHD Graphics]                                                          | 2        | 1.01%   |
| Intel HD Graphics 530                                                                    | 2        | 1.01%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2        | 1.01%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 1.01%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 2        | 1.01%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 2        | 1.01%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                                         | 2        | 1.01%   |
| Intel 82865G Integrated Graphics Controller                                              | 2        | 1.01%   |
| AMD Wrestler [Radeon HD 7340]                                                            | 2        | 1.01%   |
| AMD RV280 [Radeon 9200]                                                                  | 2        | 1.01%   |
| AMD RS880 [Radeon HD 4200]                                                               | 2        | 1.01%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2        | 1.01%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 2        | 1.01%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                                           | 2        | 1.01%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2        | 1.01%   |
| XGI Technology (eXtreme Graphics Innovation) Z9s/Z9m (XG21 core)                         | 1        | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 74       | 29.84%  |
| 1 x Intel      | 65       | 26.21%  |
| Other          | 58       | 23.39%  |
| 1 x Nvidia     | 15       | 6.05%   |
| 1 x Matrox     | 13       | 5.24%   |
| 2 x Intel      | 7        | 2.82%   |
| 1 x ASPEED     | 5        | 2.02%   |
| Intel + AMD    | 3        | 1.21%   |
| 2 x AMD        | 2        | 0.81%   |
| Intel + Nvidia | 2        | 0.81%   |
| 1 x XGI        | 1        | 0.4%    |
| AMD + Nvidia   | 1        | 0.4%    |
| AMD + Matrox   | 1        | 0.4%    |
| 1 x 3DLabs     | 1        | 0.4%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Desktops | Percent |
|---------|----------|---------|
| Free    | 170      | 69.11%  |
| Unknown | 76       | 30.89%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 245      | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Philips              | 14       | 13.21%  |
| Samsung Electronics  | 13       | 12.26%  |
| Dell                 | 13       | 12.26%  |
| Goldstar             | 10       | 9.43%   |
| Ancor Communications | 8        | 7.55%   |
| Acer                 | 5        | 4.72%   |
| NEC Computers        | 4        | 3.77%   |
| Lenovo               | 4        | 3.77%   |
| Iiyama               | 4        | 3.77%   |
| Hewlett-Packard      | 4        | 3.77%   |
| BenQ                 | 4        | 3.77%   |
| AOC                  | 4        | 3.77%   |
| ASUSTek Computer     | 3        | 2.83%   |
| ViewSonic            | 2        | 1.89%   |
| MSI                  | 2        | 1.89%   |
| LG Display           | 2        | 1.89%   |
| Eizo                 | 2        | 1.89%   |
| Vizio                | 1        | 0.94%   |
| SHI                  | 1        | 0.94%   |
| Sceptre Tech         | 1        | 0.94%   |
| Medion               | 1        | 0.94%   |
| InfoVision           | 1        | 0.94%   |
| DSC                  | 1        | 0.94%   |
| AU Optronics         | 1        | 0.94%   |
| Apple                | 1        | 0.94%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                  | 9        | 8.26%   |
| Ancor Communications ASUS VW199 ACI19ED 1440x900 410x260mm 19.1-inch   | 3        | 2.75%   |
| Iiyama PL2779QQ IVM6641 3840x2160 600x330mm 27.0-inch                  | 2        | 1.83%   |
| Hewlett-Packard LA2405 HWP284B 1920x1200 520x320mm 24.0-inch           | 2        | 1.83%   |
| Eizo EV2450 ENC2530 1920x1080 530x300mm 24.0-inch                      | 2        | 1.83%   |
| Dell UP2715K DEL40B6 848x480 600x340mm 27.2-inch                       | 2        | 1.83%   |
| Acer V223HQ ACR0070 1920x1080 470x270mm 21.3-inch                      | 2        | 1.83%   |
| Vizio E320i-A0 VIZ0091 1366x768 700x390mm 31.5-inch                    | 1        | 0.92%   |
| ViewSonic LCD Monitor VSCE032 2560x1440 530x300mm 24.0-inch            | 1        | 0.92%   |
| ViewSonic LCD Monitor VSCC42B 1920x1080 480x270mm 21.7-inch            | 1        | 0.92%   |
| SHI LCD-TV**** SHI6102 1360x768 700x390mm 31.5-inch                    | 1        | 0.92%   |
| Sceptre Tech Sceptre C35 SPT0DB7 3440x1440 820x350mm 35.1-inch         | 1        | 0.92%   |
| Samsung Electronics T24D390 SAM0B6E 1920x1080 520x290mm 23.4-inch      | 1        | 0.92%   |
| Samsung Electronics SyncMaster SAM03EF 1680x1050 470x300mm 22.0-inch   | 1        | 0.92%   |
| Samsung Electronics SyncMaster SAM03CF 1280x1024 340x270mm 17.1-inch   | 1        | 0.92%   |
| Samsung Electronics SyncMaster SAM026F 1280x1024 380x300mm 19.1-inch   | 1        | 0.92%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x260mm 19.1-inch    | 1        | 0.92%   |
| Samsung Electronics SyncMaster SAM00A1 1280x1024 340x270mm 17.1-inch   | 1        | 0.92%   |
| Samsung Electronics SMB2340 SAM0691 1920x1080 510x290mm 23.1-inch      | 1        | 0.92%   |
| Samsung Electronics SE790C SAM0BFE 3440x1440 800x330mm 34.1-inch       | 1        | 0.92%   |
| Samsung Electronics S24E650 SAM0CC3 1920x1200 520x320mm 24.0-inch      | 1        | 0.92%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 520x290mm 23.4-inch      | 1        | 0.92%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 530x300mm 24.0-inch      | 1        | 0.92%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch  | 1        | 0.92%   |
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1210x680mm 54.6-inch | 1        | 0.92%   |
| Philips PHL 328E9Q PHLC180 1920x1080 700x390mm 31.5-inch               | 1        | 0.92%   |
| Philips PHL 276E8V PHLC18F 3840x2160 600x340mm 27.2-inch               | 1        | 0.92%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                | 1        | 0.92%   |
| Philips LCD Monitor PHLC00B 1280x1024 340x270mm 17.1-inch              | 1        | 0.92%   |
| Philips 190S PHL086B 1280x1024 380x300mm 19.1-inch                     | 1        | 0.92%   |
| NEC Computers LCD1970NX NEC6662 1280x1024 380x300mm 19.1-inch          | 1        | 0.92%   |
| NEC Computers LCD190V NEC66D3 1280x1024 380x300mm 19.1-inch            | 1        | 0.92%   |
| NEC Computers EX341R NEC2C7A 3440x1440 800x330mm 34.1-inch             | 1        | 0.92%   |
| NEC Computers EA243WM NEC6866 1920x1200 520x320mm 24.0-inch            | 1        | 0.92%   |
| MSI MP242 MSI30A1 1920x1080 530x300mm 24.0-inch                        | 1        | 0.92%   |
| MSI MAG241C MSI3EA2 1920x1080 520x290mm 23.4-inch                      | 1        | 0.92%   |
| Medion LCD Monitor MED09A3 1280x1024 380x300mm 19.1-inch               | 1        | 0.92%   |
| LG Display LCD Monitor LGD05D8 1920x1080 340x190mm 15.3-inch           | 1        | 0.92%   |
| LG Display LCD Monitor LGD040A 1920x1080 310x170mm 13.9-inch           | 1        | 0.92%   |
| Lenovo LEN T24i-10 LEN61CE 1920x1080 530x300mm 24.0-inch               | 1        | 0.92%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 43       | 42.16%  |
| 1280x1024 (SXGA)   | 12       | 11.76%  |
| 3840x2160 (4K)     | 8        | 7.84%   |
| 1440x900 (WXGA+)   | 8        | 7.84%   |
| 2560x1440 (QHD)    | 6        | 5.88%   |
| 3440x1440          | 5        | 4.9%    |
| 1920x1200 (WUXGA)  | 5        | 4.9%    |
| 1366x768 (WXGA)    | 4        | 3.92%   |
| 1600x900 (HD+)     | 2        | 1.96%   |
| 1600x1200          | 2        | 1.96%   |
| 3840x1080          | 1        | 0.98%   |
| 2200x1650          | 1        | 0.98%   |
| 1680x1050 (WSXGA+) | 1        | 0.98%   |
| 1400x1050          | 1        | 0.98%   |
| 1360x768           | 1        | 0.98%   |
| 1280x800 (WXGA)    | 1        | 0.98%   |
| 1024x768 (XGA)     | 1        | 0.98%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 24     | 18       | 17.65%  |
| 21     | 17       | 16.67%  |
| 19     | 14       | 13.73%  |
| 23     | 11       | 10.78%  |
| 27     | 9        | 8.82%   |
| 17     | 6        | 5.88%   |
| 31     | 5        | 4.9%    |
| 34     | 4        | 3.92%   |
| 18     | 3        | 2.94%   |
| 14     | 3        | 2.94%   |
| 15     | 2        | 1.96%   |
| 13     | 2        | 1.96%   |
| 54     | 1        | 0.98%   |
| 49     | 1        | 0.98%   |
| 35     | 1        | 0.98%   |
| 22     | 1        | 0.98%   |
| 20     | 1        | 0.98%   |
| 16     | 1        | 0.98%   |
| 12     | 1        | 0.98%   |
| 9      | 1        | 0.98%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 37       | 36.27%  |
| 401-500     | 29       | 28.43%  |
| 301-350     | 10       | 9.8%    |
| 351-400     | 7        | 6.86%   |
| 601-700     | 6        | 5.88%   |
| 201-300     | 5        | 4.9%    |
| 701-800     | 4        | 3.92%   |
| 1001-1500   | 2        | 1.96%   |
| 801-900     | 1        | 0.98%   |
| 101-200     | 1        | 0.98%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 62       | 62%     |
| 16/10 | 15       | 15%     |
| 5/4   | 12       | 12%     |
| 4/3   | 5        | 5%      |
| 21/9  | 5        | 5%      |
| 32/9  | 1        | 1%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 36       | 36.36%  |
| 151-200        | 17       | 17.17%  |
| 351-500        | 10       | 10.1%   |
| 301-350        | 9        | 9.09%   |
| 141-150        | 8        | 8.08%   |
| 251-300        | 7        | 7.07%   |
| 81-90          | 3        | 3.03%   |
| 91-100         | 3        | 3.03%   |
| More than 1000 | 1        | 1.01%   |
| 61-70          | 1        | 1.01%   |
| 41-50          | 1        | 1.01%   |
| 121-130        | 1        | 1.01%   |
| 101-110        | 1        | 1.01%   |
| 501-1000       | 1        | 1.01%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 54       | 53.47%  |
| 101-120       | 26       | 25.74%  |
| 121-160       | 11       | 10.89%  |
| 161-240       | 5        | 4.95%   |
| 1-50          | 4        | 3.96%   |
| More than 240 | 1        | 0.99%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 139      | 56.05%  |
| 1     | 101      | 40.73%  |
| 2     | 6        | 2.42%   |
| 3     | 2        | 0.81%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Intel                             | 117      | 41.2%   |
| Realtek Semiconductor             | 97       | 34.15%  |
| Broadcom                          | 18       | 6.34%   |
| Qualcomm Atheros                  | 14       | 4.93%   |
| Qualcomm Atheros Communications   | 7        | 2.46%   |
| TP-Link                           | 5        | 1.76%   |
| U-Blox                            | 4        | 1.41%   |
| VIA Technologies                  | 3        | 1.06%   |
| Ralink                            | 3        | 1.06%   |
| MediaTek                          | 2        | 0.7%    |
| Apple                             | 2        | 0.7%    |
| 3Com                              | 2        | 0.7%    |
| Qcom                              | 1        | 0.35%   |
| Oracle/SUN                        | 1        | 0.35%   |
| National Semiconductor            | 1        | 0.35%   |
| LG Electronics                    | 1        | 0.35%   |
| Ericsson Business Mobile Networks | 1        | 0.35%   |
| Emulex                            | 1        | 0.35%   |
| Davicom Semiconductor             | 1        | 0.35%   |
| D-Link System                     | 1        | 0.35%   |
| AVM                               | 1        | 0.35%   |
| Accton Technology                 | 1        | 0.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 77       | 23.4%   |
| Intel I211 Gigabit Network Connection                             | 27       | 8.21%   |
| Intel I210 Gigabit Network Connection                             | 21       | 6.38%   |
| Intel 82574L Gigabit Network Connection                           | 12       | 3.65%   |
| Intel I350 Gigabit Network Connection                             | 9        | 2.74%   |
| Intel Ethernet Connection I217-LM                                 | 7        | 2.13%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 1.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5        | 1.52%   |
| Qualcomm Atheros AR9271 802.11n                                   | 5        | 1.52%   |
| Intel Wi-Fi 6 AX200                                               | 5        | 1.52%   |
| U-Blox [u-blox 8]                                                 | 4        | 1.22%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 4        | 1.22%   |
| Intel Ethernet Controller I225-V                                  | 4        | 1.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 1.22%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3        | 0.91%   |
| Intel Wireless 7260                                               | 3        | 0.91%   |
| Intel Ethernet Connection (7) I219-LM                             | 3        | 0.91%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 3        | 0.91%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 0.91%   |
| VIA VT6105M [Rhine-III]                                           | 2        | 0.61%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2        | 0.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2        | 0.61%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 0.61%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 2        | 0.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2        | 0.61%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 2        | 0.61%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2        | 0.61%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 2        | 0.61%   |
| Intel Platform Controller Hub EG20T Gigabit Ethernet Controller   | 2        | 0.61%   |
| Intel Ethernet Connection I217-V                                  | 2        | 0.61%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 0.61%   |
| Intel 82576 Gigabit Network Connection                            | 2        | 0.61%   |
| Intel 82573L Gigabit Ethernet Controller                          | 2        | 0.61%   |
| Intel 82573E Gigabit Ethernet Controller (Copper)                 | 2        | 0.61%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.61%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 2        | 0.61%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 2        | 0.61%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2        | 0.61%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 2        | 0.61%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 2        | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 21       | 31.82%  |
| Realtek Semiconductor           | 12       | 18.18%  |
| Qualcomm Atheros                | 12       | 18.18%  |
| Qualcomm Atheros Communications | 7        | 10.61%  |
| TP-Link                         | 5        | 7.58%   |
| Ralink                          | 3        | 4.55%   |
| MediaTek                        | 2        | 3.03%   |
| Broadcom                        | 2        | 3.03%   |
| Qcom                            | 1        | 1.52%   |
| D-Link System                   | 1        | 1.52%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR9271 802.11n                                                      | 5        | 7.46%   |
| Intel Wi-Fi 6 AX200                                                                  | 5        | 7.46%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                       | 4        | 5.97%   |
| Intel Wireless 7260                                                                  | 3        | 4.48%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                         | 2        | 2.99%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                      | 2        | 2.99%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                            | 2        | 2.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                       | 2        | 2.99%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                           | 2        | 2.99%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                               | 2        | 2.99%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                | 2        | 2.99%   |
| TP-Link TP-LINK Wireless USB Adapter                                                 | 1        | 1.49%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                  | 1        | 1.49%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                  | 1        | 1.49%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                           | 1        | 1.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                             | 1        | 1.49%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                             | 1        | 1.49%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                      | 1        | 1.49%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                      | 1        | 1.49%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                               | 1        | 1.49%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                          | 1        | 1.49%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 1        | 1.49%   |
| Realtek RTL8188EE Wireless Network Adapter                                           | 1        | 1.49%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                           | 1        | 1.49%   |
| Realtek 802.11n WLAN Adapter                                                         | 1        | 1.49%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                            | 1        | 1.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                           | 1        | 1.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                           | 1        | 1.49%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1        | 1.49%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170]        | 1        | 1.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 1        | 1.49%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                       | 1        | 1.49%   |
| Qcom RT73 USB Wireless LAN Card                                                      | 1        | 1.49%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                        | 1        | 1.49%   |
| MediaTek 802.11ac Wireless LAN Card                                                  | 1        | 1.49%   |
| Intel Wireless 8260                                                                  | 1        | 1.49%   |
| Intel Wireless 3160                                                                  | 1        | 1.49%   |
| Intel Wi-Fi 6 AX201                                                                  | 1        | 1.49%   |
| Intel Ultimate N WiFi Link 5300                                                      | 1        | 1.49%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 1        | 1.49%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 108      | 46.75%  |
| Realtek Semiconductor  | 93       | 40.26%  |
| Broadcom               | 16       | 6.93%   |
| VIA Technologies       | 3        | 1.3%    |
| Qualcomm Atheros       | 2        | 0.87%   |
| Apple                  | 2        | 0.87%   |
| 3Com                   | 2        | 0.87%   |
| Oracle/SUN             | 1        | 0.43%   |
| National Semiconductor | 1        | 0.43%   |
| Emulex                 | 1        | 0.43%   |
| Davicom Semiconductor  | 1        | 0.43%   |
| Accton Technology      | 1        | 0.43%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 77       | 30.31%  |
| Intel I211 Gigabit Network Connection                             | 27       | 10.63%  |
| Intel I210 Gigabit Network Connection                             | 21       | 8.27%   |
| Intel 82574L Gigabit Network Connection                           | 12       | 4.72%   |
| Intel I350 Gigabit Network Connection                             | 9        | 3.54%   |
| Intel Ethernet Connection I217-LM                                 | 7        | 2.76%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 1.97%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5        | 1.97%   |
| Intel Ethernet Controller I225-V                                  | 4        | 1.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 1.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3        | 1.18%   |
| Intel Ethernet Connection (7) I219-LM                             | 3        | 1.18%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 3        | 1.18%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 1.18%   |
| VIA VT6105M [Rhine-III]                                           | 2        | 0.79%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 0.79%   |
| Intel Platform Controller Hub EG20T Gigabit Ethernet Controller   | 2        | 0.79%   |
| Intel Ethernet Connection I217-V                                  | 2        | 0.79%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 0.79%   |
| Intel 82576 Gigabit Network Connection                            | 2        | 0.79%   |
| Intel 82573L Gigabit Ethernet Controller                          | 2        | 0.79%   |
| Intel 82573E Gigabit Ethernet Controller (Copper)                 | 2        | 0.79%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.79%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 2        | 0.79%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 2        | 0.79%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2        | 0.79%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 2        | 0.79%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 2        | 0.79%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                   | 2        | 0.79%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.39%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1        | 0.39%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1        | 0.39%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.39%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1        | 0.39%   |
| Oracle/SUN RIO 10/100 Ethernet [eri]                              | 1        | 0.39%   |
| National DP83815 (MacPhyter) Ethernet Controller                  | 1        | 0.39%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 0.39%   |
| Intel I210 Gigabit Fiber Network Connection                       | 1        | 0.39%   |
| Intel Ethernet Controller I226-V                                  | 1        | 0.39%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1        | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 217      | 75.87%  |
| WiFi     | 61       | 21.33%  |
| Modem    | 6        | 2.1%    |
| Unknown  | 2        | 0.7%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 154      | 82.8%   |
| WiFi     | 32       | 17.2%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 90       | 36.59%  |
| 2     | 59       | 23.98%  |
| 3     | 33       | 13.41%  |
| 4     | 26       | 10.57%  |
| 0     | 26       | 10.57%  |
| 5     | 4        | 1.63%   |
| 8     | 3        | 1.22%   |
| 7     | 2        | 0.81%   |
| 6     | 2        | 0.81%   |
| 12    | 1        | 0.41%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 245      | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 15       | 50%     |
| Realtek Semiconductor           | 2        | 6.67%   |
| Qualcomm Atheros Communications | 2        | 6.67%   |
| IMC Networks                    | 2        | 6.67%   |
| Cambridge Silicon Radio         | 2        | 6.67%   |
| Broadcom                        | 2        | 6.67%   |
| Apple                           | 2        | 6.67%   |
| Hewlett-Packard                 | 1        | 3.33%   |
| Foxconn / Hon Hai               | 1        | 3.33%   |
| ASUSTek Computer                | 1        | 3.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                       | 5        | 16.67%  |
| Intel Bluetooth wireless interface                          | 4        | 13.33%  |
| Realtek  Bluetooth Adapter                                  | 2        | 6.67%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2        | 6.67%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2        | 6.67%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip        | 2        | 6.67%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2        | 6.67%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1        | 3.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 1        | 3.33%   |
| Intel AX210 Bluetooth                                       | 1        | 3.33%   |
| Intel AX201 Bluetooth                                       | 1        | 3.33%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1        | 3.33%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1        | 3.33%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 1        | 3.33%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 1        | 3.33%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 1        | 3.33%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1        | 3.33%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 1        | 3.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 90       | 45.45%  |
| AMD                                  | 72       | 36.36%  |
| Nvidia                               | 15       | 7.58%   |
| C-Media Electronics                  | 5        | 2.53%   |
| VIA Technologies                     | 3        | 1.52%   |
| ULi Electronics                      | 2        | 1.01%   |
| JMTek                                | 2        | 1.01%   |
| Creative Labs                        | 2        | 1.01%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.51%   |
| Texas Instruments                    | 1        | 0.51%   |
| Lenovo                               | 1        | 0.51%   |
| Generalplus Technology               | 1        | 0.51%   |
| ESS Technology                       | 1        | 0.51%   |
| Elgato Systems                       | 1        | 0.51%   |
| Blue Microphones                     | 1        | 0.51%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                          | 15       | 6.1%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 12       | 4.88%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 11       | 4.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 10       | 4.07%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 10       | 4.07%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 9        | 3.66%   |
| Intel Cannon Lake PCH cAVS                                                        | 8        | 3.25%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 7        | 2.85%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 7        | 2.85%   |
| AMD Navi 10 HDMI Audio                                                            | 7        | 2.85%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 7        | 2.85%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 6        | 2.44%   |
| AMD FCH Azalia Controller                                                         | 6        | 2.44%   |
| AMD Family 17h/19h HD Audio Controller                                            | 6        | 2.44%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 6        | 2.44%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 5        | 2.03%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 5        | 2.03%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 5        | 2.03%   |
| Nvidia MCP61 High Definition Audio                                                | 4        | 1.63%   |
| Intel Comet Lake PCH-V cAVS                                                       | 4        | 1.63%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 4        | 1.63%   |
| Nvidia GP106 High Definition Audio Controller                                     | 3        | 1.22%   |
| Intel Sunrise Point-LP HD Audio                                                   | 3        | 1.22%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 3        | 1.22%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                      | 3        | 1.22%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 3        | 1.22%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 3        | 1.22%   |
| AMD Kabini HDMI/DP Audio                                                          | 3        | 1.22%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 3        | 1.22%   |
| ULi Electronics M5451 PCI AC-Link Controller Audio Device                         | 2        | 0.81%   |
| Nvidia GF108 High Definition Audio Controller                                     | 2        | 0.81%   |
| JMTek USB PnP Audio Device                                                        | 2        | 0.81%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 2        | 0.81%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 2        | 0.81%   |
| Intel Jasper Lake HD Audio                                                        | 2        | 0.81%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                 | 2        | 0.81%   |
| Intel Broadwell-U Audio Controller                                                | 2        | 0.81%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 2        | 0.81%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 2        | 0.81%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                              | 2        | 0.81%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 9        | 40.91%  |
| Kingston            | 3        | 13.64%  |
| Transcend           | 2        | 9.09%   |
| Samsung Electronics | 2        | 9.09%   |
| Corsair             | 2        | 9.09%   |
| SK hynix            | 1        | 4.55%   |
| Ramaxel Technology  | 1        | 4.55%   |
| Nanya Technology    | 1        | 4.55%   |
| Elpida              | 1        | 4.55%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s           | 2        | 7.41%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 2400MT/s      | 2        | 7.41%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s        | 2        | 7.41%   |
| Unknown RAM Module 512MB DIMM SDRAM                      | 1        | 3.7%    |
| Unknown RAM Module 512MB DIMM DDR 400MT/s                | 1        | 3.7%    |
| Unknown RAM Module 512MB DIMM 400MT/s                    | 1        | 3.7%    |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s              | 1        | 3.7%    |
| Unknown RAM Module 256MB DIMM 333MT/s                    | 1        | 3.7%    |
| Unknown RAM Module 2048MB DIMM DDR2 266MT/s              | 1        | 3.7%    |
| Unknown RAM Module 1GB DIMM 400MT/s                      | 1        | 3.7%    |
| Unknown RAM Module 1024MB DIMM DDR                       | 1        | 3.7%    |
| Unknown RAM Module 1024MB DIMM 800MT/s                   | 1        | 3.7%    |
| Transcend RAM TS1GSK64W6H 8GB DIMM DDR3 1600MT/s         | 1        | 3.7%    |
| Transcend RAM TS128MLQ64V6J 1GB DIMM DDR2 667MT/s        | 1        | 3.7%    |
| SK hynix RAM HYMP112U64CP8-Y5 1GB DIMM DDR2 667MT/s      | 1        | 3.7%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s    | 1        | 3.7%    |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s | 1        | 3.7%    |
| Samsung RAM M3 78T2953CZ3-CE6 1GB DIMM DDR2 667MT/s      | 1        | 3.7%    |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s  | 1        | 3.7%    |
| Nanya RAM NT1GT64U88D0BY-AD 1024MB DIMM DDR2 800MT/s     | 1        | 3.7%    |
| Kingston RAM KF3600C18D4/32GX 32GB DIMM DDR4 2400MT/s    | 1        | 3.7%    |
| Elpida RAM EBE11UD8AJWA-8G-E 1024MB DIMM DDR2 800MT/s    | 1        | 3.7%    |
| Corsair RAM CML16GX3M2A1600C9 8GB DIMM DDR3 1600MT/s     | 1        | 3.7%    |
| Corsair RAM CMK64GX5M2B5200C40 32GB DIMM DDR5 4800MT/s   | 1        | 3.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 7        | 36.84%  |
| DDR4    | 3        | 15.79%  |
| DDR2    | 3        | 15.79%  |
| DDR     | 2        | 10.53%  |
| Unknown | 2        | 10.53%  |
| SDRAM   | 1        | 5.26%   |
| DDR5    | 1        | 5.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 14       | 73.68%  |
| SODIMM | 5        | 26.32%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 7        | 30.43%  |
| 1024  | 5        | 21.74%  |
| 8192  | 4        | 17.39%  |
| 512   | 3        | 13.04%  |
| 32768 | 2        | 8.7%    |
| 2048  | 1        | 4.35%   |
| 256   | 1        | 4.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 4        | 20%     |
| 2400    | 3        | 15%     |
| 1333    | 3        | 15%     |
| 800     | 2        | 10%     |
| 400     | 2        | 10%     |
| Unknown | 2        | 10%     |
| 4800    | 1        | 5%      |
| 667     | 1        | 5%      |
| 333     | 1        | 5%      |
| 266     | 1        | 5%      |

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
| Logitech                | 4        | 36.36%  |
| Chicony Electronics     | 3        | 27.27%  |
| Microdia                | 2        | 18.18%  |
| Z-Star Microelectronics | 1        | 9.09%   |
| Ricoh                   | 1        | 9.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Z-Star Integrated Camera             | 1        | 9.09%   |
| Ricoh USB2.0 Camera                  | 1        | 9.09%   |
| Microdia USB 2.0 Camera              | 1        | 9.09%   |
| Microdia Ltd., USB  Live camera      | 1        | 9.09%   |
| Logitech Webcam C310                 | 1        | 9.09%   |
| Logitech Webcam C270                 | 1        | 9.09%   |
| Logitech HD Pro Webcam C920          | 1        | 9.09%   |
| Logitech C920 HD Pro Webcam          | 1        | 9.09%   |
| Chicony Ltd., HP 0.3MP Webcam        | 1        | 9.09%   |
| Chicony Integrated Camera [ThinkPad] | 1        | 9.09%   |
| Chicony Integrated Camera            | 1        | 9.09%   |

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
| Shenzhen Goodix  FingerPrint Device                    | 1        | 20%     |
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
| 0     | 123      | 49.4%   |
| 1     | 76       | 30.52%  |
| 2     | 40       | 16.06%  |
| 3     | 7        | 2.81%   |
| 7     | 2        | 0.8%    |
| 5     | 1        | 0.4%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 84       | 48.55%  |
| Graphics card            | 29       | 16.76%  |
| Firewire controller      | 16       | 9.25%   |
| Net/wireless             | 14       | 8.09%   |
| Net/ethernet             | 9        | 5.2%    |
| Storage/ata              | 8        | 4.62%   |
| Sound                    | 8        | 4.62%   |
| Storage                  | 2        | 1.16%   |
| Storage/raid             | 1        | 0.58%   |
| Storage/ide              | 1        | 0.58%   |
| Network                  | 1        | 0.58%   |

