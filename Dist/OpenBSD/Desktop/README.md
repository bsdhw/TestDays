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

Total: 423

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| ASUSTek       | PRIME B650-PLUS             | [3e01e5ffbf](https://bsd-hardware.info/?probe=3e01e5ffbf) | May 03, 2024 |
| ASRock        | Z87M Pro4                   | [91a487bad5](https://bsd-hardware.info/?probe=91a487bad5) | Apr 29, 2024 |
| ASRock        | A320M Pro4-F                | [b02849b872](https://bsd-hardware.info/?probe=b02849b872) | Apr 23, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [44758d3d74](https://bsd-hardware.info/?probe=44758d3d74) | Apr 16, 2024 |
| Unknown       | QDNV01                      | [0cb0009f73](https://bsd-hardware.info/?probe=0cb0009f73) | Apr 15, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS (W... | [1257111a5f](https://bsd-hardware.info/?probe=1257111a5f) | Apr 10, 2024 |
| Gigabyte      | G431-MM0-OT                 | [16c58f7ccb](https://bsd-hardware.info/?probe=16c58f7ccb) | Apr 07, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [d0ce6ee00b](https://bsd-hardware.info/?probe=d0ce6ee00b) | Apr 05, 2024 |
| Dell          | Vostro 3268                 | [3492b3ebb5](https://bsd-hardware.info/?probe=3492b3ebb5) | Mar 31, 2024 |
| ASUSTek       | PRIME B550M-A (WI-FI)       | [feb3803dbc](https://bsd-hardware.info/?probe=feb3803dbc) | Mar 24, 2024 |
| Dell          | Inspiron 5521               | [15446ac441](https://bsd-hardware.info/?probe=15446ac441) | Mar 24, 2024 |
| Sun           | SUNW,Ultra-1                | [33ed69952b](https://bsd-hardware.info/?probe=33ed69952b) | Mar 17, 2024 |
| HP            | ProLiant ML370 G4           | [e3d8ea32d4](https://bsd-hardware.info/?probe=e3d8ea32d4) | Mar 13, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS (W... | [9015dcf1b5](https://bsd-hardware.info/?probe=9015dcf1b5) | Mar 12, 2024 |
| Lenovo        | ThinkCentre M75n 11BXS00... | [6ed6f9c86f](https://bsd-hardware.info/?probe=6ed6f9c86f) | Mar 09, 2024 |
| Biostar       | B450NH                      | [9f4dedfcd6](https://bsd-hardware.info/?probe=9f4dedfcd6) | Feb 17, 2024 |
| Lenovo        | ThinkCentre M91p 7052C1G    | [3aeb926332](https://bsd-hardware.info/?probe=3aeb926332) | Feb 08, 2024 |
| MSI           | MS-7D15                     | [a22ee27a4a](https://bsd-hardware.info/?probe=a22ee27a4a) | Feb 03, 2024 |
| MSI           | MS-7D15                     | [476be56dc7](https://bsd-hardware.info/?probe=476be56dc7) | Feb 03, 2024 |
| Gigabyte      | Z690 UD DDR4                | [f6f19ac329](https://bsd-hardware.info/?probe=f6f19ac329) | Feb 02, 2024 |
| AZW           | MINI S                      | [99c79c2cc8](https://bsd-hardware.info/?probe=99c79c2cc8) | Jan 30, 2024 |
| IBM           | 830381U                     | [a3f2d51f21](https://bsd-hardware.info/?probe=a3f2d51f21) | Jan 21, 2024 |
| IBM           | 830381U                     | [e44647b8cd](https://bsd-hardware.info/?probe=e44647b8cd) | Jan 20, 2024 |
| Microsoft     | Windows Dev Kit 2023        | [2cd25bfacf](https://bsd-hardware.info/?probe=2cd25bfacf) | Jan 19, 2024 |
| HP            | s5-1210br                   | [9ce94bc2b7](https://bsd-hardware.info/?probe=9ce94bc2b7) | Jan 19, 2024 |
| Unknown       | Unknown                     | [2a34bc9613](https://bsd-hardware.info/?probe=2a34bc9613) | Nov 28, 2023 |
| AZW           | SER                         | [48a259ae28](https://bsd-hardware.info/?probe=48a259ae28) | Nov 28, 2023 |
| Lenovo        | ThinkCentre M90n-1 11AHS... | [eca5b59407](https://bsd-hardware.info/?probe=eca5b59407) | Nov 23, 2023 |
| Lenovo        | ThinkCentre M720s 10SUSB... | [a44a9f3526](https://bsd-hardware.info/?probe=a44a9f3526) | Nov 23, 2023 |
| HP            | Compaq CQ45                 | [4f3c176253](https://bsd-hardware.info/?probe=4f3c176253) | Nov 14, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [700d52c2dd](https://bsd-hardware.info/?probe=700d52c2dd) | Nov 07, 2023 |
| Apple         | MacPro4,1                   | [5960492992](https://bsd-hardware.info/?probe=5960492992) | Nov 07, 2023 |
| Intel         | DCP847SKE                   | [3b5b83d95f](https://bsd-hardware.info/?probe=3b5b83d95f) | Oct 30, 2023 |
| ASUSTek       | MINIPC PN53-G               | [57d8823b4b](https://bsd-hardware.info/?probe=57d8823b4b) | Oct 28, 2023 |
| Dell          | PowerEdge T110 II           | [f93395bc11](https://bsd-hardware.info/?probe=f93395bc11) | Oct 28, 2023 |
| Sun           | SUNW,SPARC-Enterprise-T5... | [50457ff825](https://bsd-hardware.info/?probe=50457ff825) | Oct 27, 2023 |
| Gigabyte      | H81M-S2PV                   | [310fcb9763](https://bsd-hardware.info/?probe=310fcb9763) | Oct 26, 2023 |
| MECHREVO      | Unknown                     | [2dac22205c](https://bsd-hardware.info/?probe=2dac22205c) | Oct 23, 2023 |
| Wistron       | ProLiant ML110 G6           | [d5676f7895](https://bsd-hardware.info/?probe=d5676f7895) | Oct 10, 2023 |
| PC Engines    | APU                         | [ca9bc2faa7](https://bsd-hardware.info/?probe=ca9bc2faa7) | Sep 29, 2023 |
| PC Engines    | APU                         | [067872c1f5](https://bsd-hardware.info/?probe=067872c1f5) | Sep 29, 2023 |
| ASUSTek       | PRIME A520M-A II            | [29bcb3ca3e](https://bsd-hardware.info/?probe=29bcb3ca3e) | Sep 29, 2023 |
| Apple         | MacPro4,1                   | [c368087050](https://bsd-hardware.info/?probe=c368087050) | Sep 20, 2023 |
| Huanan        | X99-F8D PLUS V1.3           | [53d31a28bf](https://bsd-hardware.info/?probe=53d31a28bf) | Sep 14, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS (W... | [89a601d720](https://bsd-hardware.info/?probe=89a601d720) | Sep 12, 2023 |
| Supermicro    | X8DTH-i/6/iF/6F             | [df114e1b94](https://bsd-hardware.info/?probe=df114e1b94) | Sep 09, 2023 |
| Apple         | PowerMac3,6                 | [36daf7ce75](https://bsd-hardware.info/?probe=36daf7ce75) | Sep 09, 2023 |
| VIA Techno... | VT8623-8235                 | [3274cd095e](https://bsd-hardware.info/?probe=3274cd095e) | Aug 31, 2023 |
| MSI           | MS-7125                     | [3dfb767d80](https://bsd-hardware.info/?probe=3dfb767d80) | Aug 30, 2023 |
| ASUSTek       | P5M2-R                      | [73135bf26d](https://bsd-hardware.info/?probe=73135bf26d) | Aug 25, 2023 |
| MSI           | MS-7721                     | [a577019634](https://bsd-hardware.info/?probe=a577019634) | Aug 18, 2023 |
| MSI           | MS-7623                     | [189fb4d7cc](https://bsd-hardware.info/?probe=189fb4d7cc) | Aug 08, 2023 |
| ASUSTek       | PRIME B650-PLUS             | [e74d459c5a](https://bsd-hardware.info/?probe=e74d459c5a) | Jul 28, 2023 |
| MSI           | G41M-P33 Combo              | [d4a26f9214](https://bsd-hardware.info/?probe=d4a26f9214) | Jul 24, 2023 |
| ASUSTek       | P5KPL-AM SE                 | [57f449130a](https://bsd-hardware.info/?probe=57f449130a) | Jul 16, 2023 |
| Sony          | VGC-RB41M                   | [95804a1f40](https://bsd-hardware.info/?probe=95804a1f40) | Jun 28, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS (W... | [4d99bc4b63](https://bsd-hardware.info/?probe=4d99bc4b63) | Jun 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS (W... | [8866724f46](https://bsd-hardware.info/?probe=8866724f46) | Jun 27, 2023 |
| Gigabyte      | G41MT-S2                    | [355202536f](https://bsd-hardware.info/?probe=355202536f) | Jun 07, 2023 |
| ASUSTek       | PRIME B460M-A               | [4c8047dca3](https://bsd-hardware.info/?probe=4c8047dca3) | May 19, 2023 |
| VIA Techno... | VT82C597                    | [d73db58e48](https://bsd-hardware.info/?probe=d73db58e48) | May 19, 2023 |
| HP            | 0A60h                       | [98e9deff3d](https://bsd-hardware.info/?probe=98e9deff3d) | May 16, 2023 |
| PC Engines    | APU2                        | [62fef2616b](https://bsd-hardware.info/?probe=62fef2616b) | May 15, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | [2ce057e389](https://bsd-hardware.info/?probe=2ce057e389) | May 14, 2023 |
| ASUSTek       | M3A78-EMH HDMI              | [b4bf04ac2f](https://bsd-hardware.info/?probe=b4bf04ac2f) | May 13, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | [cace71018f](https://bsd-hardware.info/?probe=cace71018f) | May 11, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | [4353bb0195](https://bsd-hardware.info/?probe=4353bb0195) | May 09, 2023 |
| ASUSTek       | PRIME B650-PLUS             | [be83fbb0f2](https://bsd-hardware.info/?probe=be83fbb0f2) | May 09, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [c26c1111c6](https://bsd-hardware.info/?probe=c26c1111c6) | Apr 21, 2023 |
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
| Gigabyte      | J3455N-D3H                  | [576771182b](https://bsd-hardware.info/?probe=576771182b) | May 25, 2020 |
| Gigabyte      | J3455N-D3H                  | [05e8154b2c](https://bsd-hardware.info/?probe=05e8154b2c) | May 25, 2020 |
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
| OpenBSD 6.8 | 108      | 30.68%  |
| OpenBSD 7.1 | 50       | 14.2%   |
| OpenBSD 7.2 | 36       | 10.23%  |
| OpenBSD 7.0 | 36       | 10.23%  |
| OpenBSD 6.9 | 32       | 9.09%   |
| OpenBSD 7.3 | 29       | 8.24%   |
| OpenBSD 7.4 | 27       | 7.67%   |
| OpenBSD 6.7 | 26       | 7.39%   |
| OpenBSD 7.5 | 7        | 1.99%   |
| OpenBSD 6.6 | 1        | 0.28%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| OpenBSD | 303      | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| amd64   | 250      | 82.24%  |
| i386    | 21       | 6.91%   |
| arm64   | 20       | 6.58%   |
| sparc64 | 5        | 1.64%   |
| macppc  | 4        | 1.32%   |
| octeon  | 2        | 0.66%   |
| armv7   | 2        | 0.66%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| helloDesktop  | 111      | 34.8%   |
| Console       | 97       | 30.41%  |
| fvwm          | 85       | 26.65%  |
| XFCE          | 21       | 6.58%   |
| GNOME         | 3        | 0.94%   |
| i3            | 1        | 0.31%   |
| Enlightenment | 1        | 0.31%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 163      | 52.92%  |
| Console | 145      | 47.08%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 294      | 96.08%  |
| SLiM    | 7        | 2.29%   |
| GDM     | 5        | 1.63%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 263      | 85.67%  |
| ru_RU      | 14       | 4.56%   |
| en_US      | 14       | 4.56%   |
| C          | 4        | 1.3%    |
| fr_FR      | 3        | 0.98%   |
| de_DE      | 3        | 0.98%   |
| pl_PL      | 2        | 0.65%   |
| ISO8859-15 | 1        | 0.33%   |
| es_CO      | 1        | 0.33%   |
| en_AU      | 1        | 0.33%   |
| de.DE      | 1        | 0.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 177      | 57.65%  |
| EFI  | 130      | 42.35%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ffs  | 303      | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| MBR  | 197      | 64.8%   |
| GPT  | 107      | 35.2%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUSTek Computer        | 43       | 14.19%  |
| PC Engines              | 34       | 11.22%  |
| Gigabyte Technology     | 26       | 8.58%   |
| Unknown                 | 26       | 8.58%   |
| Dell                    | 23       | 7.59%   |
| MSI                     | 20       | 6.6%    |
| Lenovo                  | 18       | 5.94%   |
| ASRock                  | 18       | 5.94%   |
| Hewlett-Packard         | 17       | 5.61%   |
| Intel                   | 9        | 2.97%   |
| Apple                   | 7        | 2.31%   |
| Supermicro              | 6        | 1.98%   |
| Raspberry Pi Foundation | 6        | 1.98%   |
| Sun                     | 5        | 1.65%   |
| Soekris Engineering     | 3        | 0.99%   |
| IBM                     | 3        | 0.99%   |
| Biostar                 | 3        | 0.99%   |
| AZW                     | 3        | 0.99%   |
| VIA Technologies        | 2        | 0.66%   |
| Sony                    | 2        | 0.66%   |
| Shuttle                 | 2        | 0.66%   |
| Pegatron                | 2        | 0.66%   |
| Acer                    | 2        | 0.66%   |
| ZOTAC                   | 1        | 0.33%   |
| Yanling                 | 1        | 0.33%   |
| WYSE                    | 1        | 0.33%   |
| Wistron                 | 1        | 0.33%   |
| Unknown                 | 1        | 0.33%   |
| Sony UK                 | 1        | 0.33%   |
| Protectli               | 1        | 0.33%   |
| NF541                   | 1        | 0.33%   |
| Microsoft               | 1        | 0.33%   |
| MECHREVO                | 1        | 0.33%   |
| KOHJINSHA               | 1        | 0.33%   |
| Huanan                  | 1        | 0.33%   |
| HARDKERNEL              | 1        | 0.33%   |
| Fujitsu                 | 1        | 0.33%   |
| Foxconn                 | 1        | 0.33%   |
| eMachines               | 1        | 0.33%   |
| Elpitech                | 1        | 0.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 30       | 9.9%    |
| PC Engines APU2                    | 15       | 4.95%   |
| PC Engines apu4                    | 9        | 2.97%   |
| PC Engines apu1                    | 5        | 1.65%   |
| Dell PowerEdge R620                | 5        | 1.65%   |
| ASUS All Series                    | 4        | 1.32%   |
| RPi Raspberry Pi 400               | 3        | 0.99%   |
| RPi Raspberry Pi 4 Model B         | 3        | 0.99%   |
| PC Engines APU3                    | 3        | 0.99%   |
| ASUS PRIME H410M-A                 | 3        | 0.99%   |
| ASUS PRIME B650-PLUS               | 3        | 0.99%   |
| Soekris Engineering net6501        | 2        | 0.66%   |
| PC Engines APU                     | 2        | 0.66%   |
| MSI MS-7A34                        | 2        | 0.66%   |
| Gigabyte M68MT-S2P                 | 2        | 0.66%   |
| ASUS TUF Gaming B550M-PLUS (WI-FI) | 2        | 0.66%   |
| ASUS PRIME X370-PRO                | 2        | 0.66%   |
| Apple PowerMac3,6                  | 2        | 0.66%   |
| Apple MacPro4,1                    | 2        | 0.66%   |
| ZOTAC XXXXXX                       | 1        | 0.33%   |
| Yanling YL-KBR6L                   | 1        | 0.33%   |
| WYSE D CLASS                       | 1        | 0.33%   |
| Wistron ProLiant ML110 G6          | 1        | 0.33%   |
| VIA VT8623-8235                    | 1        | 0.33%   |
| VIA VT82C597                       | 1        | 0.33%   |
| Supermicro X8STi                   | 1        | 0.33%   |
| Supermicro X8DTH-i/6/iF/6F         | 1        | 0.33%   |
| Supermicro X7SBL                   | 1        | 0.33%   |
| Supermicro X11SSW-F                | 1        | 0.33%   |
| Supermicro X11DDW-L                | 1        | 0.33%   |
| Supermicro X10SLH-N6-ST031         | 1        | 0.33%   |
| Sun SUNW,Ultra-1                   | 1        | 0.33%   |
| Sun SUNW,T5140                     | 1        | 0.33%   |
| Sun SUNW,Sun-Blade-1500            | 1        | 0.33%   |
| Sun SUNW,Sun-Blade-100             | 1        | 0.33%   |
| Sun SUNW,SPARC-Enterprise-T5120    | 1        | 0.33%   |
| Sony VPCL22Z1R                     | 1        | 0.33%   |
| Sony VGC-RB41M                     | 1        | 0.33%   |
| Sony UK Raspberry Pi 4 Model B     | 1        | 0.33%   |
| Soekris Engineering net5501        | 1        | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| Unknown                     | 30       | 9.9%    |
| ASUS PRIME                  | 18       | 5.94%   |
| PC Engines APU2             | 15       | 4.95%   |
| Lenovo ThinkCentre          | 11       | 3.63%   |
| Dell PowerEdge              | 11       | 3.63%   |
| PC Engines apu4             | 9        | 2.97%   |
| Dell OptiPlex               | 8        | 2.64%   |
| RPi Raspberry               | 6        | 1.98%   |
| Sun SUNW                    | 5        | 1.65%   |
| PC Engines apu1             | 5        | 1.65%   |
| HP ProLiant                 | 5        | 1.65%   |
| Lenovo ThinkPad             | 4        | 1.32%   |
| HP Compaq                   | 4        | 1.32%   |
| ASUS All                    | 4        | 1.32%   |
| PC Engines APU3             | 3        | 0.99%   |
| ASUS TUF                    | 3        | 0.99%   |
| ASUS ROG                    | 3        | 0.99%   |
| Soekris Engineering net6501 | 2        | 0.66%   |
| PC Engines APU              | 2        | 0.66%   |
| MSI MS-7A34                 | 2        | 0.66%   |
| Gigabyte M68MT-S2P          | 2        | 0.66%   |
| Gigabyte B450M              | 2        | 0.66%   |
| ASRock X570                 | 2        | 0.66%   |
| Apple PowerMac3             | 2        | 0.66%   |
| Apple MacPro4               | 2        | 0.66%   |
| ZOTAC XXXXXX                | 1        | 0.33%   |
| Yanling YL-KBR6L            | 1        | 0.33%   |
| WYSE D                      | 1        | 0.33%   |
| Wistron ProLiant            | 1        | 0.33%   |
| VIA VT8623-8235             | 1        | 0.33%   |
| VIA VT82C597                | 1        | 0.33%   |
| Supermicro X8STi            | 1        | 0.33%   |
| Supermicro X8DTH-i          | 1        | 0.33%   |
| Supermicro X7SBL            | 1        | 0.33%   |
| Supermicro X11SSW-F         | 1        | 0.33%   |
| Supermicro X11DDW-L         | 1        | 0.33%   |
| Supermicro X10SLH-N6-ST031  | 1        | 0.33%   |
| Sony VPCL22Z1R              | 1        | 0.33%   |
| Sony VGC-RB41M              | 1        | 0.33%   |
| Sony UK Raspberry           | 1        | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 33       | 10.89%  |
| Unknown | 33       | 10.89%  |
| 2019    | 25       | 8.25%   |
| 2020    | 22       | 7.26%   |
| 2016    | 22       | 7.26%   |
| 2014    | 19       | 6.27%   |
| 2023    | 18       | 5.94%   |
| 2021    | 17       | 5.61%   |
| 2022    | 13       | 4.29%   |
| 2013    | 13       | 4.29%   |
| 2012    | 13       | 4.29%   |
| 2010    | 13       | 4.29%   |
| 2017    | 11       | 3.63%   |
| 2011    | 10       | 3.3%    |
| 2008    | 8        | 2.64%   |
| 2007    | 8        | 2.64%   |
| 2015    | 7        | 2.31%   |
| 2009    | 7        | 2.31%   |
| 2006    | 4        | 1.32%   |
| 2005    | 3        | 0.99%   |
| 2004    | 2        | 0.66%   |
| 2003    | 1        | 0.33%   |
| 2001    | 1        | 0.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 303      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 267      | 88.12%  |
| Yes  | 36       | 11.88%  |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 4.01-8.0        | 68       | 22.01%  |
| 8.01-16.0       | 55       | 17.8%   |
| 16.01-24.0      | 48       | 15.53%  |
| 32.01-64.0      | 27       | 8.74%   |
| 3.01-4.0        | 26       | 8.41%   |
| 2.01-3.0        | 19       | 6.15%   |
| 64.01-256.0     | 18       | 5.83%   |
| 1.01-2.0        | 15       | 4.85%   |
| 0.01-0.5        | 11       | 3.56%   |
| 24.01-32.0      | 10       | 3.24%   |
| 0.51-1.0        | 9        | 2.91%   |
| More than 256.0 | 3        | 0.97%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 222      | 72.31%  |
| 0.51-1.0   | 35       | 11.4%   |
| 0          | 22       | 7.17%   |
| 1.01-2.0   | 12       | 3.91%   |
| 4.01-8.0   | 7        | 2.28%   |
| Unknown    | 3        | 0.98%   |
| 3.01-4.0   | 2        | 0.65%   |
| 8.01-16.0  | 2        | 0.65%   |
| 2.01-3.0   | 1        | 0.33%   |
| 16.01-24.0 | 1        | 0.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 162      | 50.47%  |
| 2      | 73       | 22.74%  |
| 3      | 40       | 12.46%  |
| 4      | 23       | 7.17%   |
| 0      | 7        | 2.18%   |
| 5      | 5        | 1.56%   |
| 6      | 4        | 1.25%   |
| 10     | 2        | 0.62%   |
| 7      | 2        | 0.62%   |
| 14     | 1        | 0.31%   |
| 12     | 1        | 0.31%   |
| 8      | 1        | 0.31%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 300      | 99.01%  |
| Yes       | 3        | 0.99%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 271      | 89.44%  |
| No        | 32       | 10.56%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 226      | 74.34%  |
| Yes       | 78       | 25.66%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 259      | 85.2%   |
| Yes       | 45       | 14.8%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Russia       | 51       | 16.78%  |
| USA          | 44       | 14.47%  |
| Germany      | 37       | 12.17%  |
| Italy        | 20       | 6.58%   |
| France       | 19       | 6.25%   |
| UK           | 12       | 3.95%   |
| Netherlands  | 12       | 3.95%   |
| Poland       | 11       | 3.62%   |
| Switzerland  | 10       | 3.29%   |
| Spain        | 10       | 3.29%   |
| Austria      | 8        | 2.63%   |
| Canada       | 7        | 2.3%    |
| Ukraine      | 6        | 1.97%   |
| Taiwan       | 5        | 1.64%   |
| Sweden       | 5        | 1.64%   |
| Romania      | 5        | 1.64%   |
| Australia    | 5        | 1.64%   |
| Norway       | 4        | 1.32%   |
| Brazil       | 4        | 1.32%   |
| Mexico       | 3        | 0.99%   |
| Denmark      | 2        | 0.66%   |
| Cyprus       | 2        | 0.66%   |
| Colombia     | 2        | 0.66%   |
| Bulgaria     | 2        | 0.66%   |
| UAE          | 1        | 0.33%   |
| Turkey       | 1        | 0.33%   |
| Saudi Arabia | 1        | 0.33%   |
| New Zealand  | 1        | 0.33%   |
| Moldova      | 1        | 0.33%   |
| Lithuania    | 1        | 0.33%   |
| Latvia       | 1        | 0.33%   |
| Japan        | 1        | 0.33%   |
| Jamaica      | 1        | 0.33%   |
| India        | 1        | 0.33%   |
| Hungary      | 1        | 0.33%   |
| Finland      | 1        | 0.33%   |
| Estonia      | 1        | 0.33%   |
| Egypt        | 1        | 0.33%   |
| Czechia      | 1        | 0.33%   |
| Croatia      | 1        | 0.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Moscow                  | 15       | 4.67%   |
| St Petersburg           | 11       | 3.43%   |
| Milan                   | 10       | 3.12%   |
| Berlin                  | 9        | 2.8%    |
| Amsterdam               | 7        | 2.18%   |
| Paris                   | 6        | 1.87%   |
| Vladivostok             | 5        | 1.56%   |
| Vienna                  | 5        | 1.56%   |
| New Taipei              | 5        | 1.56%   |
| Poortugaal              | 4        | 1.25%   |
| Zurich                  | 3        | 0.93%   |
| Wittersham              | 3        | 0.93%   |
| Syeverodonets'k         | 3        | 0.93%   |
| Sydney                  | 3        | 0.93%   |
| Puebla City             | 3        | 0.93%   |
| Nuremberg               | 3        | 0.93%   |
| New York                | 3        | 0.93%   |
| Miedziana Gora          | 3        | 0.93%   |
| Malmo                   | 3        | 0.93%   |
| Lausanne                | 3        | 0.93%   |
| Ibiza Town              | 3        | 0.93%   |
| Cherepovets             | 3        | 0.93%   |
| Wroclaw                 | 2        | 0.62%   |
| Wolfsburg               | 2        | 0.62%   |
| Svenstrup               | 2        | 0.62%   |
| Sofia                   | 2        | 0.62%   |
| Skien                   | 2        | 0.62%   |
| Saint-Martin-d'HГЁres | 2        | 0.62%   |
| Reutov                  | 2        | 0.62%   |
| Orsk                    | 2        | 0.62%   |
| Onalaska                | 2        | 0.62%   |
| Oensingen               | 2        | 0.62%   |
| London                  | 2        | 0.62%   |
| Lebanon                 | 2        | 0.62%   |
| Larnaca                 | 2        | 0.62%   |
| Krasnodar               | 2        | 0.62%   |
| Gummersbach             | 2        | 0.62%   |
| Gdansk                  | 2        | 0.62%   |
| Canberra                | 2        | 0.62%   |
| Cambridge               | 2        | 0.62%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 56       | 102    | 12.81%  |
| NVMe                | 53       | 79     | 12.13%  |
| WDC                 | 50       | 77     | 11.44%  |
| Samsung Electronics | 43       | 102    | 9.84%   |
| Kingston            | 28       | 38     | 6.41%   |
| Crucial             | 18       | 28     | 4.12%   |
| OPENBSD             | 15       | 27     | 3.43%   |
| Intel               | 15       | 20     | 3.43%   |
| Hitachi             | 14       | 26     | 3.2%    |
| Toshiba             | 13       | 23     | 2.97%   |
| SanDisk             | 13       | 17     | 2.97%   |
| Phison              | 13       | 15     | 2.97%   |
| HGST                | 10       | 19     | 2.29%   |
| Dell                | 7        | 12     | 1.6%    |
| A-DATA Technology   | 6        | 7      | 1.37%   |
| Transcend           | 5        | 12     | 1.14%   |
| Hewlett-Packard     | 5        | 10     | 1.14%   |
| USB                 | 3        | 3      | 0.69%   |
| PNY                 | 3        | 3      | 0.69%   |
| OCZ                 | 3        | 3      | 0.69%   |
| LSI                 | 3        | 7      | 0.69%   |
| Generic             | 3        | 3      | 0.69%   |
| Corsair             | 3        | 3      | 0.69%   |
| China               | 3        | 3      | 0.69%   |
| StoreJet            | 2        | 2      | 0.46%   |
| SPCC                | 2        | 2      | 0.46%   |
| SK hynix            | 2        | 2      | 0.46%   |
| Patriot             | 2        | 2      | 0.46%   |
| Multiple            | 2        | 2      | 0.46%   |
| Maxtor              | 2        | 3      | 0.46%   |
| KingSpec            | 2        | 2      | 0.46%   |
| Hoodisk             | 2        | 3      | 0.46%   |
| Fujitsu             | 2        | 2      | 0.46%   |
| ASMT                | 2        | 2      | 0.46%   |
| Apacer              | 2        | 2      | 0.46%   |
| AMD                 | 2        | 2      | 0.46%   |
| XPG                 | 1        | 1      | 0.23%   |
| SSDPR-CX            | 1        | 1      | 0.23%   |
| SABRENT             | 1        | 1      | 0.23%   |
| Qumo                | 1        | 1      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| OPENBSD SR RAID 1 2TB              | 12       | 2.46%   |
| Phison SATA SSD 16GB               | 11       | 2.26%   |
| NVMe Samsung SSD 980 1TB           | 8        | 1.64%   |
| NVMe Samsung SSD 970 500GB         | 5        | 1.03%   |
| Samsung SSD 860 EVO mSATA 500GB    | 4        | 0.82%   |
| Samsung SSD 860 EVO 250GB          | 4        | 0.82%   |
| Kingston SA400S37240G 240GB        | 4        | 0.82%   |
| Intel SSDSC2BW480H6 480GB          | 4        | 0.82%   |
| Dell PERC H710 282GB               | 4        | 0.82%   |
| WDC WD6400AARS-00Y5B1 640GB        | 3        | 0.62%   |
| USB SanDisk 3.2Gen1 64GB           | 3        | 0.62%   |
| Toshiba MQ04ABF100 1TB             | 3        | 0.62%   |
| Seagate ST3250318AS 250GB          | 3        | 0.62%   |
| Seagate ST250DM000-1BD141 250GB    | 3        | 0.62%   |
| Seagate ST1000DM010-2EP102 1TB     | 3        | 0.62%   |
| Seagate ST1000DM003-1CH162 1TB     | 3        | 0.62%   |
| SanDisk Ultra Fit 128GB            | 3        | 0.62%   |
| Samsung SSD 860 EVO 500GB          | 3        | 0.62%   |
| Samsung SSD 850 EVO 1TB            | 3        | 0.62%   |
| Samsung SSD 840 EVO 250GB          | 3        | 0.62%   |
| Kingston SUV500MS240G 240GB        | 3        | 0.62%   |
| Kingston SEDC500M480G 480GB        | 3        | 0.62%   |
| HGST HUS724020ALA640 2TB           | 3        | 0.62%   |
| Crucial CT120BX500SSD1 120GB       | 3        | 0.62%   |
| Crucial CT1000MX500SSD1 1TB        | 3        | 0.62%   |
| WDC WD5000AZLX-00K2TA0 500GB       | 2        | 0.41%   |
| WDC WD10JPVT-75A1YT0 1TB           | 2        | 0.41%   |
| WDC WD10EADS-00M2B0 1TB            | 2        | 0.41%   |
| WDC WD Elements 25A1 4TB           | 2        | 0.41%   |
| Toshiba HDWG440 4TB                | 2        | 0.41%   |
| Toshiba DT01ACA100 1TB             | 2        | 0.41%   |
| StoreJet Transcend 120GB           | 2        | 0.41%   |
| Seagate ST500DM002-1BD142 500GB    | 2        | 0.41%   |
| Seagate ST3320418AS 320GB          | 2        | 0.41%   |
| Seagate ST2000LX001-1RG174 2TB     | 2        | 0.41%   |
| Seagate ST1000LM035-1RK172 1TB     | 2        | 0.41%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2        | 0.41%   |
| Seagate Expansion 4TB              | 2        | 0.41%   |
| Seagate BUP Slim BK 2TB            | 2        | 0.41%   |
| SanDisk Ultra 32GB                 | 2        | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                             | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| Seagate                            | 56       | 102    | 23.43%  |
| WDC                                | 47       | 74     | 19.67%  |
| NVMe                               | 26       | 42     | 10.88%  |
| OPENBSD                            | 15       | 27     | 6.28%   |
| Hitachi                            | 14       | 26     | 5.86%   |
| Toshiba                            | 13       | 23     | 5.44%   |
| Samsung Electronics                | 12       | 20     | 5.02%   |
| HGST                               | 10       | 19     | 4.18%   |
| Dell                               | 7        | 12     | 2.93%   |
| Hewlett-Packard                    | 4        | 8      | 1.67%   |
| USB                                | 3        | 3      | 1.26%   |
| LSI                                | 3        | 7      | 1.26%   |
| Generic                            | 3        | 3      | 1.26%   |
| StoreJet                           | 2        | 2      | 0.84%   |
| Multiple                           | 2        | 2      | 0.84%   |
| Maxtor                             | 2        | 3      | 0.84%   |
| Fujitsu                            | 2        | 2      | 0.84%   |
| ASMT                               | 2        | 2      | 0.84%   |
| SSDPR-CX                           | 1        | 1      | 0.42%   |
| SABRENT                            | 1        | 1      | 0.42%   |
| Product:              USB DISK 3.0 | 1        | 1      | 0.42%   |
| Product:              USB DISK 2.0 | 1        | 1      | 0.42%   |
| Product:                           | 1        | 1      | 0.42%   |
| Memorex                            | 1        | 1      | 0.42%   |
| MaxDigital                         | 1        | 1      | 0.42%   |
| LSILOGIC                           | 1        | 1      | 0.42%   |
| Lexar                              | 1        | 1      | 0.42%   |
| JetFlash                           | 1        | 1      | 0.42%   |
| IBM-ESXS                           | 1        | 1      | 0.42%   |
| IBM                                | 1        | 1      | 0.42%   |
| General                            | 1        | 1      | 0.42%   |
| External                           | 1        | 1      | 0.42%   |
| China                              | 1        | 1      | 0.42%   |
| Apple                              | 1        | 1      | 0.42%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 31       | 82     | 15.66%  |
| Kingston            | 28       | 38     | 14.14%  |
| NVMe                | 27       | 34     | 13.64%  |
| Crucial             | 18       | 28     | 9.09%   |
| Intel               | 15       | 20     | 7.58%   |
| SanDisk             | 13       | 17     | 6.57%   |
| Phison              | 13       | 15     | 6.57%   |
| A-DATA Technology   | 6        | 7      | 3.03%   |
| Transcend           | 5        | 12     | 2.53%   |
| WDC                 | 3        | 3      | 1.52%   |
| PNY                 | 3        | 3      | 1.52%   |
| OCZ                 | 3        | 3      | 1.52%   |
| Corsair             | 3        | 3      | 1.52%   |
| SPCC                | 2        | 2      | 1.01%   |
| SK hynix            | 2        | 2      | 1.01%   |
| Patriot             | 2        | 2      | 1.01%   |
| KingSpec            | 2        | 2      | 1.01%   |
| Hoodisk             | 2        | 3      | 1.01%   |
| China               | 2        | 2      | 1.01%   |
| Apacer              | 2        | 2      | 1.01%   |
| AMD                 | 2        | 2      | 1.01%   |
| XPG                 | 1        | 1      | 0.51%   |
| Qumo                | 1        | 1      | 0.51%   |
| Netac               | 1        | 1      | 0.51%   |
| Micron Technology   | 1        | 1      | 0.51%   |
| MEMXPRO             | 1        | 1      | 0.51%   |
| LITEONIT            | 1        | 1      | 0.51%   |
| KIOXIA-EXCERIA      | 1        | 1      | 0.51%   |
| KingDian            | 1        | 1      | 0.51%   |
| HPE                 | 1        | 2      | 0.51%   |
| Hewlett-Packard     | 1        | 2      | 0.51%   |
| GOODRAM             | 1        | 1      | 0.51%   |
| GLOWAY              | 1        | 1      | 0.51%   |
| ASMedia             | 1        | 1      | 0.51%   |
| Argon               | 1        | 1      | 0.51%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 176      | 393    | 51.01%  |
| SSD  | 166      | 298    | 48.12%  |
| NVMe | 3        | 3      | 0.87%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 284      | 691    | 98.95%  |
| NVMe | 3        | 3      | 1.05%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| 0.01-0.5        | 235      | 389    | 62.33%  |
| 0.51-1.0        | 74       | 117    | 19.63%  |
| 1.01-2.0        | 40       | 131    | 10.61%  |
| 3.01-4.0        | 15       | 23     | 3.98%   |
| 4.01-10.0       | 9        | 25     | 2.39%   |
| 2.01-3.0        | 3        | 5      | 0.8%    |
| More than 100.0 | 1        | 1      | 0.27%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 93       | 29.62%  |
| 251-500        | 91       | 28.98%  |
| 1-20           | 31       | 9.87%   |
| 51-100         | 30       | 9.55%   |
| 21-50          | 22       | 7.01%   |
| 501-1000       | 18       | 5.73%   |
| More than 3000 | 15       | 4.78%   |
| 1001-2000      | 11       | 3.5%    |
| 2001-3000      | 3        | 0.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 224      | 69.57%  |
| 21-50          | 35       | 10.87%  |
| 101-250        | 20       | 6.21%   |
| 51-100         | 18       | 5.59%   |
| 251-500        | 7        | 2.17%   |
| 501-1000       | 7        | 2.17%   |
| 1001-2000      | 6        | 1.86%   |
| More than 3000 | 4        | 1.24%   |
| 2001-3000      | 1        | 0.31%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Intel SSDSC2BW480H6 480GB             | 4        | 4      | 6.9%    |
| Toshiba MQ04ABF100 1TB                | 2        | 2      | 3.45%   |
| Samsung Electronics SSD 840 EVO 250GB | 2        | 4      | 3.45%   |
| OCZ VERTEX3 120GB                     | 2        | 2      | 3.45%   |
| Kingston SMS200S330G 32GB             | 2        | 4      | 3.45%   |
| HGST HTS541010A7E630 1TB              | 2        | 4      | 3.45%   |
| XPG SX950U 240GB                      | 1        | 1      | 1.72%   |
| WDC WD7500AACS-00ZJB0 752GB           | 1        | 1      | 1.72%   |
| WDC WD6400AAKS-22A7B0 640GB           | 1        | 1      | 1.72%   |
| WDC WD5000AAKX-60U6AA0 500GB          | 1        | 2      | 1.72%   |
| WDC WD1600BEVE-00UYT0 160GB           | 1        | 1      | 1.72%   |
| WDC WD15EARS-00Z5B1 1.5TB             | 1        | 1      | 1.72%   |
| WDC WD10SPZX-24Z10 1TB                | 1        | 1      | 1.72%   |
| WDC WD10JPVT-75A1YT0 1TB              | 1        | 1      | 1.72%   |
| WDC WD10EADS-00M2B0 1TB               | 1        | 1      | 1.72%   |
| Transcend 3E128-TS2-550B01 100GB      | 1        | 4      | 1.72%   |
| Toshiba MK5065GSX 500GB               | 1        | 1      | 1.72%   |
| Toshiba DT01ACA100 1TB                | 1        | 1      | 1.72%   |
| Seagate ST9500325AS 500GB             | 1        | 1      | 1.72%   |
| Seagate ST9160310AS 160GB             | 1        | 2      | 1.72%   |
| Seagate ST500DM002-1BD142 500GB       | 1        | 1      | 1.72%   |
| Seagate ST380815AS 80GB               | 1        | 1      | 1.72%   |
| Seagate ST3750640NS 752GB             | 1        | 6      | 1.72%   |
| Seagate ST3320418AS 320GB             | 1        | 1      | 1.72%   |
| Seagate ST3160212SCE 160GB            | 1        | 1      | 1.72%   |
| Seagate ST3120211AS 120GB             | 1        | 1      | 1.72%   |
| Seagate ST250DM000-1BD141 250GB       | 1        | 3      | 1.72%   |
| Seagate ST2000DM006-2DM164 2TB        | 1        | 1      | 1.72%   |
| Seagate ST1000DM003-1CH162 1TB        | 1        | 1      | 1.72%   |
| SanDisk SSD PLUS 240GB                | 1        | 1      | 1.72%   |
| Samsung Electronics SSD 870 EVO 500GB | 1        | 1      | 1.72%   |
| Samsung Electronics HM160HI 160GB     | 1        | 2      | 1.72%   |
| Samsung Electronics HD753LJ 752GB     | 1        | 1      | 1.72%   |
| Samsung Electronics HD161HJ 160GB     | 1        | 2      | 1.72%   |
| Samsung Electronics HD154UI 1.5TB     | 1        | 1      | 1.72%   |
| Kingston SV300S37A120G 120GB          | 1        | 1      | 1.72%   |
| Kingston SMS200S3120G 120GB           | 1        | 1      | 1.72%   |
| KingSpec P3-512 512GB                 | 1        | 1      | 1.72%   |
| Intel SSDSC2CT180A4 180GB             | 1        | 1      | 1.72%   |
| Intel SSDSC2BB080G4 80GB              | 1        | 1      | 1.72%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 10       | 19     | 17.86%  |
| WDC                 | 7        | 9      | 12.5%   |
| Samsung Electronics | 7        | 11     | 12.5%   |
| Intel               | 6        | 6      | 10.71%  |
| Toshiba             | 4        | 4      | 7.14%   |
| Kingston            | 4        | 6      | 7.14%   |
| HGST                | 4        | 6      | 7.14%   |
| Hitachi             | 3        | 4      | 5.36%   |
| OCZ                 | 2        | 2      | 3.57%   |
| A-DATA Technology   | 2        | 3      | 3.57%   |
| XPG                 | 1        | 1      | 1.79%   |
| Transcend           | 1        | 4      | 1.79%   |
| SanDisk             | 1        | 1      | 1.79%   |
| KingSpec            | 1        | 1      | 1.79%   |
| Hewlett-Packard     | 1        | 1      | 1.79%   |
| GLOWAY              | 1        | 1      | 1.79%   |
| Corsair             | 1        | 1      | 1.79%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 10       | 19     | 30.3%   |
| WDC                 | 7        | 9      | 21.21%  |
| Toshiba             | 4        | 4      | 12.12%  |
| Samsung Electronics | 4        | 6      | 12.12%  |
| HGST                | 4        | 6      | 12.12%  |
| Hitachi             | 3        | 4      | 9.09%   |
| Hewlett-Packard     | 1        | 1      | 3.03%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 33       | 49     | 58.93%  |
| SSD  | 23       | 31     | 41.07%  |

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
| Works    | 204      | 435    | 56.98%  |
| Detected | 97       | 175    | 27.09%  |
| Malfunc  | 55       | 80     | 15.36%  |
| Failed   | 2        | 4      | 0.56%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 154      | 43.75%  |
| AMD                          | 96       | 27.27%  |
| Samsung Electronics          | 24       | 6.82%   |
| Broadcom / LSI               | 16       | 4.55%   |
| SanDisk                      | 9        | 2.56%   |
| Nvidia                       | 6        | 1.7%    |
| VIA Technologies             | 5        | 1.42%   |
| Phison Electronics           | 5        | 1.42%   |
| ASMedia Technology           | 5        | 1.42%   |
| Silicon Motion               | 3        | 0.85%   |
| Shenzhen Longsys Electronics | 3        | 0.85%   |
| Micron/Crucial Technology    | 3        | 0.85%   |
| Marvell Technology Group     | 3        | 0.85%   |
| KIOXIA                       | 3        | 0.85%   |
| ULi Electronics              | 2        | 0.57%   |
| Hewlett-Packard              | 2        | 0.57%   |
| ADATA Technology             | 2        | 0.57%   |
| Toshiba                      | 1        | 0.28%   |
| Silicon Image                | 1        | 0.28%   |
| Seagate Technology           | 1        | 0.28%   |
| MAXIO Technology (Hangzhou)  | 1        | 0.28%   |
| Kingston Technology Company  | 1        | 0.28%   |
| HighPoint Technologies       | 1        | 0.28%   |
| Dell                         | 1        | 0.28%   |
| Compaq Computer              | 1        | 0.28%   |
| Biwin Storage Technology     | 1        | 0.28%   |
| Artop Electronic             | 1        | 0.28%   |
| Unknown                      | 1        | 0.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 42       | 10.1%   |
| AMD FCH SATA Controller [IDE mode]                                             | 17       | 4.09%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 16       | 3.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 16       | 3.85%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 13       | 3.13%   |
| AMD 500 Series Chipset SATA Controller                                         | 11       | 2.64%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 9        | 2.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 9        | 2.16%   |
| AMD 400 Series Chipset SATA Controller                                         | 9        | 2.16%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 8        | 1.92%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 8        | 1.92%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 8        | 1.92%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 7        | 1.68%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 7        | 1.68%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7        | 1.68%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6        | 1.44%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 6        | 1.44%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 6        | 1.44%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 5        | 1.2%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 5        | 1.2%    |
| Nvidia MCP61 SATA Controller                                                   | 5        | 1.2%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 5        | 1.2%    |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                 | 5        | 1.2%    |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 5        | 1.2%    |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 4        | 0.96%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 4        | 0.96%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 4        | 0.96%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]           | 4        | 0.96%   |
| AMD 600 Series Chipset SATA Controller                                         | 4        | 0.96%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 3        | 0.72%   |
| Nvidia MCP61 IDE                                                               | 3        | 0.72%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 3        | 0.72%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 3        | 0.72%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 3        | 0.72%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 3        | 0.72%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 3        | 0.72%   |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                   | 3        | 0.72%   |
| Intel 82801EB (ICH5) SATA Controller                                           | 3        | 0.72%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 3        | 0.72%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3        | 0.72%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 208      | 57.78%  |
| IDE  | 73       | 20.28%  |
| NVMe | 53       | 14.72%  |
| RAID | 15       | 4.17%   |
| SCSI | 6        | 1.67%   |
| SAS  | 5        | 1.39%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 160      | 52.81%  |
| AMD     | 109      | 35.97%  |
| ARM     | 22       | 7.26%   |
| Unknown | 9        | 2.97%   |
| PowerPC | 2        | 0.66%   |
| VIA     | 1        | 0.33%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| AMD GX-412TC SOC                                                 | 27       | 8.85%   |
| ARM Cortex-A72 r0p3                                              | 12       | 3.93%   |
|                                                                  | 9        | 2.95%   |
| AMD G-T40E Processor                                             | 7        | 2.3%    |
| ARM Cortex-A53 r0p4                                              | 6        | 1.97%   |
| Intel Core i5-4570 CPU @ 3.20GHz                                 | 4        | 1.31%   |
| AMD Ryzen 7 5800X 8-Core Processor                               | 4        | 1.31%   |
| AMD Ryzen 7 3700X 8-Core Processor                               | 4        | 1.31%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz                              | 3        | 0.98%   |
| AMD Ryzen 9 7950X 16-Core Processor                              | 3        | 0.98%   |
| AMD Ryzen 5 3600 6-Core Processor                                | 3        | 0.98%   |
| Intel Xeon CPU E5520 @ 2.27GHz                                   | 2        | 0.66%   |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz                               | 2        | 0.66%   |
| Intel Xeon CPU E5-2630 0 @ 2.30GHz                               | 2        | 0.66%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz                              | 2        | 0.66%   |
| Intel Core i7-4770K CPU @ 3.50GHz                                | 2        | 0.66%   |
| Intel Core i7-4770 CPU @ 3.40GHz                                 | 2        | 0.66%   |
| Intel Core i7-3770 CPU @ 3.40GHz                                 | 2        | 0.66%   |
| Intel Core i5-4570T CPU @ 2.90GHz                                | 2        | 0.66%   |
| Intel Core i5-10400F CPU @ 2.90GHz                               | 2        | 0.66%   |
| Intel Core i3-10100F CPU @ 3.60GHz                               | 2        | 0.66%   |
| Intel Core i3-10100 CPU @ 3.60GHz                                | 2        | 0.66%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz                            | 2        | 0.66%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz                             | 2        | 0.66%   |
| Intel Celeron N5105 @ 2.00GHz                                    | 2        | 0.66%   |
| Intel Celeron CPU J1900 @ 1.99GHz                                | 2        | 0.66%   |
| Intel Celeron CPU 3865U @ 1.80GHz                                | 2        | 0.66%   |
| Intel Atom CPU N270 @ 1.60GHz ("GenuineIntel" 686-class)         | 2        | 0.66%   |
| AMD Ryzen 7 5700G with Radeon Graphics                           | 2        | 0.66%   |
| AMD Ryzen 7 2700 Eight-Core Processor                            | 2        | 0.66%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics                      | 2        | 0.66%   |
| AMD Geode Integrated Processor by PCS ("AuthenticAMD" 586-class) | 2        | 0.66%   |
| AMD E2-1800 APU with Radeon HD Graphics                          | 2        | 0.66%   |
| AMD Athlon II X3 455 Processor                                   | 2        | 0.66%   |
| VIA C3                                                           | 1        | 0.33%   |
| PowerPC 7447A (Revision 0x102)                                   | 1        | 0.33%   |
| PowerPC 7447A (Revision 0x101)                                   | 1        | 0.33%   |
| Intel Xeon Gold 5220 CPU @ 2.20GHz                               | 1        | 0.33%   |
| Intel Xeon E-2278G CPU @ 3.40GHz                                 | 1        | 0.33%   |
| Intel Xeon E-2236 CPU @ 3.40GHz                                  | 1        | 0.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Xeon              | 33       | 10.89%  |
| AMD GX                  | 28       | 9.24%   |
| Intel Core i5           | 23       | 7.59%   |
| Intel Core i7           | 22       | 7.26%   |
| ARM Cortex              | 22       | 7.26%   |
| Intel Celeron           | 20       | 6.6%    |
| Other                   | 19       | 6.27%   |
| AMD Ryzen 7             | 19       | 6.27%   |
| Intel Core i3           | 15       | 4.95%   |
| AMD Ryzen 5             | 10       | 3.3%    |
| AMD G                   | 8        | 2.64%   |
| Intel Atom              | 7        | 2.31%   |
| AMD Ryzen 9             | 7        | 2.31%   |
| Intel Pentium 4         | 6        | 1.98%   |
| Intel Pentium           | 5        | 1.65%   |
| Intel Pentium Dual-Core | 4        | 1.32%   |
| Intel Core 2 Duo        | 4        | 1.32%   |
| Intel Core 2            | 4        | 1.32%   |
| Intel Genuine           | 3        | 0.99%   |
| Intel Core 2 Quad       | 3        | 0.99%   |
| AMD Ryzen 3             | 3        | 0.99%   |
| AMD Athlon              | 3        | 0.99%   |
| AMD Phenom II X4        | 2        | 0.66%   |
| AMD Geode Integrated    | 2        | 0.66%   |
| AMD E2                  | 2        | 0.66%   |
| AMD Athlon II X3        | 2        | 0.66%   |
| AMD Athlon II X2        | 2        | 0.66%   |
| AMD Athlon 64 X2        | 2        | 0.66%   |
| AMD A4                  | 2        | 0.66%   |
| AMD A10                 | 2        | 0.66%   |
| Intel Xeon Gold         | 1        | 0.33%   |
| Intel Pentium III       | 1        | 0.33%   |
| Intel Pentium Dual      | 1        | 0.33%   |
| Intel Pentium D         | 1        | 0.33%   |
| Intel Core i9           | 1        | 0.33%   |
| Intel Celeron D         | 1        | 0.33%   |
| AMD Turion II Neo       | 1        | 0.33%   |
| AMD Ryzen 7 PRO         | 1        | 0.33%   |
| AMD Phenom II X6        | 1        | 0.33%   |
| AMD Phenom              | 1        | 0.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 102      | 33.55%  |
| Unknown | 67       | 22.04%  |
| 2       | 46       | 15.13%  |
| 1       | 22       | 7.24%   |
| 16      | 16       | 5.26%   |
| 6       | 15       | 4.93%   |
| 12      | 14       | 4.61%   |
| 8       | 12       | 3.95%   |
| 32      | 4        | 1.32%   |
| 24      | 2        | 0.66%   |
| 3       | 2        | 0.66%   |
| 36      | 1        | 0.33%   |
| 14      | 1        | 0.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 215      | 70.49%  |
| Unknown | 79       | 25.9%   |
| 2       | 11       | 3.61%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 151      | 49.83%  |
| Unknown | 84       | 27.72%  |
| 2       | 68       | 22.44%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Unknown       | 57       | 18.81%  |
| Puma          | 28       | 9.24%   |
| Haswell       | 22       | 7.26%   |
| KabyLake      | 20       | 6.6%    |
| SandyBridge   | 15       | 4.95%   |
| Zen 2         | 13       | 4.29%   |
| IvyBridge     | 12       | 3.96%   |
| K10           | 11       | 3.63%   |
| Bobcat        | 11       | 3.63%   |
| Zen 3         | 10       | 3.3%    |
| Core          | 10       | 3.3%    |
| Penryn        | 9        | 2.97%   |
| NetBurst      | 9        | 2.97%   |
| Zen           | 7        | 2.31%   |
| Westmere      | 7        | 2.31%   |
| Silvermont    | 7        | 2.31%   |
| Bonnell       | 7        | 2.31%   |
| Skylake       | 6        | 1.98%   |
| Nehalem       | 5        | 1.65%   |
| CometLake     | 5        | 1.65%   |
| Zen+          | 4        | 1.32%   |
| Piledriver    | 4        | 1.32%   |
| Goldmont      | 4        | 1.32%   |
| Broadwell     | 4        | 1.32%   |
| K8 Hammer     | 3        | 0.99%   |
| Geode         | 3        | 0.99%   |
| P6            | 2        | 0.66%   |
| Jaguar        | 2        | 0.66%   |
| Goldmont plus | 2        | 0.66%   |
| TigerLake     | 1        | 0.33%   |
| Steamroller   | 1        | 0.33%   |
| K6            | 1        | 0.33%   |
| K10 Llano     | 1        | 0.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| AMD                                          | 105      | 42%     |
| Intel                                        | 91       | 36.4%   |
| Nvidia                                       | 28       | 11.2%   |
| Matrox Electronics Systems                   | 16       | 6.4%    |
| ASPEED Technology                            | 7        | 2.8%    |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.4%    |
| VIA Technologies                             | 1        | 0.4%    |
| 3DLabs                                       | 1        | 0.4%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 12       | 4.67%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 11       | 4.28%   |
| Matrox Electronics Systems G200eR2                                                       | 7        | 2.72%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 7        | 2.72%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6        | 2.33%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 6        | 2.33%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 6        | 2.33%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 6        | 2.33%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 5        | 1.95%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 5        | 1.95%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4        | 1.56%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4        | 1.56%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4        | 1.56%   |
| AMD Raphael                                                                              | 4        | 1.56%   |
| AMD ES1000                                                                               | 4        | 1.56%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3        | 1.17%   |
| Intel JasperLake [UHD Graphics]                                                          | 3        | 1.17%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 3        | 1.17%   |
| Intel HD Graphics 630                                                                    | 3        | 1.17%   |
| Intel HD Graphics 610                                                                    | 3        | 1.17%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3        | 1.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3        | 1.17%   |
| AMD RV711/M93 [Mobility Radeon HD 4350/4550/530v/540v/545v / FirePro RG220]              | 3        | 1.17%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 3        | 1.17%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3        | 1.17%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2        | 0.78%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2        | 0.78%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 2        | 0.78%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2        | 0.78%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 2        | 0.78%   |
| Matrox Electronics Systems MGA G200EH                                                    | 2        | 0.78%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 2        | 0.78%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2        | 0.78%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2        | 0.78%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2        | 0.78%   |
| Intel HD Graphics 530                                                                    | 2        | 0.78%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2        | 0.78%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 2        | 0.78%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 2        | 0.78%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                                         | 2        | 0.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 95       | 31.05%  |
| 1 x Intel      | 78       | 25.49%  |
| Other          | 65       | 21.24%  |
| 1 x Nvidia     | 22       | 7.19%   |
| 1 x Matrox     | 15       | 4.9%    |
| 2 x Intel      | 7        | 2.29%   |
| 1 x ASPEED     | 7        | 2.29%   |
| Intel + AMD    | 4        | 1.31%   |
| 2 x AMD        | 3        | 0.98%   |
| Intel + Nvidia | 3        | 0.98%   |
| AMD + Nvidia   | 3        | 0.98%   |
| 1 x XGI        | 1        | 0.33%   |
| 1 x VIA        | 1        | 0.33%   |
| AMD + Matrox   | 1        | 0.33%   |
| 1 x 3DLabs     | 1        | 0.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Desktops | Percent |
|---------|----------|---------|
| Free    | 219      | 71.8%   |
| Unknown | 86       | 28.2%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 303      | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Philips              | 22       | 15.94%  |
| Samsung Electronics  | 17       | 12.32%  |
| Dell                 | 15       | 10.87%  |
| Goldstar             | 12       | 8.7%    |
| Ancor Communications | 9        | 6.52%   |
| ASUSTek Computer     | 7        | 5.07%   |
| AOC                  | 7        | 5.07%   |
| NEC Computers        | 5        | 3.62%   |
| Iiyama               | 5        | 3.62%   |
| BenQ                 | 5        | 3.62%   |
| Acer                 | 5        | 3.62%   |
| ViewSonic            | 4        | 2.9%    |
| Lenovo               | 4        | 2.9%    |
| Hewlett-Packard      | 4        | 2.9%    |
| MSI                  | 3        | 2.17%   |
| LG Display           | 2        | 1.45%   |
| Eizo                 | 2        | 1.45%   |
| AU Optronics         | 2        | 1.45%   |
| Vizio                | 1        | 0.72%   |
| SHI                  | 1        | 0.72%   |
| Sceptre Tech         | 1        | 0.72%   |
| Medion               | 1        | 0.72%   |
| InfoVision           | 1        | 0.72%   |
| DSC                  | 1        | 0.72%   |
| CMT                  | 1        | 0.72%   |
| Apple                | 1        | 0.72%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                  | 13       | 9.22%   |
| Samsung Electronics SyncMaster SAM03CF 1280x1024 340x270mm 17.1-inch   | 3        | 2.13%   |
| Ancor Communications ASUS VW199 ACI19ED 1440x900 410x260mm 19.1-inch   | 3        | 2.13%   |
| Philips 170S PHL0839 1280x1024 340x270mm 17.1-inch                     | 2        | 1.42%   |
| NEC Computers EX341R NEC2C7A 3440x1440 800x330mm 34.1-inch             | 2        | 1.42%   |
| MSI MP242 MSI30A1 1920x1080 530x300mm 24.0-inch                        | 2        | 1.42%   |
| Iiyama PL2779QQ IVM6641 3840x2160 600x330mm 27.0-inch                  | 2        | 1.42%   |
| Hewlett-Packard LA2405 HWP284B 1920x1200 520x320mm 24.0-inch           | 2        | 1.42%   |
| Eizo EV2450 ENC2530 1920x1080 530x300mm 24.0-inch                      | 2        | 1.42%   |
| Dell UP2715K DEL40B6 848x480 600x340mm 27.2-inch                       | 2        | 1.42%   |
| ASUSTek Computer PA279 AUS2768 3840x2160 600x340mm 27.2-inch           | 2        | 1.42%   |
| AOC Q27P2W AOC2702 2560x1440 600x340mm 27.2-inch                       | 2        | 1.42%   |
| Acer V223HQ ACR0070 1920x1080 470x270mm 21.3-inch                      | 2        | 1.42%   |
| Vizio E320i-A0 VIZ0091 1366x768 700x390mm 31.5-inch                    | 1        | 0.71%   |
| ViewSonic VA703-4SERIES VSC6A1E 1280x1024 340x270mm 17.1-inch          | 1        | 0.71%   |
| ViewSonic VA2418-FHD VSCD739 1920x1080 530x300mm 24.0-inch             | 1        | 0.71%   |
| ViewSonic LCD Monitor VSCE032 2560x1440 530x300mm 24.0-inch            | 1        | 0.71%   |
| ViewSonic LCD Monitor VSCC42B 1920x1080 480x270mm 21.7-inch            | 1        | 0.71%   |
| SHI LCD-TV**** SHI6102 1360x768 700x390mm 31.5-inch                    | 1        | 0.71%   |
| Sceptre Tech Sceptre C35 SPT0DB7 3440x1440 820x350mm 35.1-inch         | 1        | 0.71%   |
| Samsung Electronics T24D390 SAM0B6E 1920x1080 520x290mm 23.4-inch      | 1        | 0.71%   |
| Samsung Electronics SyncMaster SAM03EF 1680x1050 470x300mm 22.0-inch   | 1        | 0.71%   |
| Samsung Electronics SyncMaster SAM026F 1280x1024 380x300mm 19.1-inch   | 1        | 0.71%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x260mm 19.1-inch    | 1        | 0.71%   |
| Samsung Electronics SyncMaster SAM00A1 1280x1024 340x270mm 17.1-inch   | 1        | 0.71%   |
| Samsung Electronics SMB2340 SAM0691 1920x1080 510x290mm 23.1-inch      | 1        | 0.71%   |
| Samsung Electronics SE790C SAM0BFE 3440x1440 800x330mm 34.1-inch       | 1        | 0.71%   |
| Samsung Electronics S24E650 SAM0CC3 1920x1200 520x320mm 24.0-inch      | 1        | 0.71%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 520x290mm 23.4-inch      | 1        | 0.71%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 530x300mm 24.0-inch      | 1        | 0.71%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch  | 1        | 0.71%   |
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1210x680mm 54.6-inch | 1        | 0.71%   |
| Samsung Electronics LCD Monitor SAM0669 1920x1080                      | 1        | 0.71%   |
| Samsung Electronics C32JG5x SAM0F54 2560x1440 700x390mm 31.5-inch      | 1        | 0.71%   |
| Philips PHL 328E9Q PHLC180 1920x1080 700x390mm 31.5-inch               | 1        | 0.71%   |
| Philips PHL 276E8V PHLC18F 3840x2160 600x340mm 27.2-inch               | 1        | 0.71%   |
| Philips PHL 247E6 PHLC0E7 1920x1080 520x290mm 23.4-inch                | 1        | 0.71%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                | 1        | 0.71%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch                | 1        | 0.71%   |
| Philips LCD Monitor PHLC00B 1280x1024 340x270mm 17.1-inch              | 1        | 0.71%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 56       | 42.42%  |
| 1280x1024 (SXGA)   | 17       | 12.88%  |
| 3840x2160 (4K)     | 11       | 8.33%   |
| 2560x1440 (QHD)    | 9        | 6.82%   |
| 1440x900 (WXGA+)   | 8        | 6.06%   |
| 3440x1440          | 6        | 4.55%   |
| 1920x1200 (WUXGA)  | 5        | 3.79%   |
| 1366x768 (WXGA)    | 5        | 3.79%   |
| 3840x1080          | 3        | 2.27%   |
| 1680x1050 (WSXGA+) | 2        | 1.52%   |
| 1600x900 (HD+)     | 2        | 1.52%   |
| 1600x1200          | 2        | 1.52%   |
| 2560x1080          | 1        | 0.76%   |
| 2200x1650          | 1        | 0.76%   |
| 1400x1050          | 1        | 0.76%   |
| 1360x768           | 1        | 0.76%   |
| 1280x800 (WXGA)    | 1        | 0.76%   |
| 1024x768 (XGA)     | 1        | 0.76%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 23       | 17.29%  |
| 21      | 23       | 17.29%  |
| 27      | 14       | 10.53%  |
| 19      | 14       | 10.53%  |
| 23      | 13       | 9.77%   |
| 17      | 11       | 8.27%   |
| 34      | 6        | 4.51%   |
| 31      | 6        | 4.51%   |
| 18      | 3        | 2.26%   |
| 15      | 3        | 2.26%   |
| 14      | 3        | 2.26%   |
| 49      | 2        | 1.5%    |
| 22      | 2        | 1.5%    |
| 13      | 2        | 1.5%    |
| 54      | 1        | 0.75%   |
| 48      | 1        | 0.75%   |
| 35      | 1        | 0.75%   |
| 20      | 1        | 0.75%   |
| 16      | 1        | 0.75%   |
| 12      | 1        | 0.75%   |
| 9       | 1        | 0.75%   |
| Unknown | 1        | 0.75%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 49       | 36.84%  |
| 401-500     | 36       | 27.07%  |
| 301-350     | 16       | 12.03%  |
| 601-700     | 7        | 5.26%   |
| 351-400     | 7        | 5.26%   |
| 701-800     | 6        | 4.51%   |
| 201-300     | 5        | 3.76%   |
| 1001-1500   | 4        | 3.01%   |
| 801-900     | 1        | 0.75%   |
| 101-200     | 1        | 0.75%   |
| Unknown     | 1        | 0.75%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 82       | 63.08%  |
| 5/4   | 17       | 13.08%  |
| 16/10 | 16       | 12.31%  |
| 21/9  | 7        | 5.38%   |
| 4/3   | 5        | 3.85%   |
| 32/9  | 3        | 2.31%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 49       | 37.4%   |
| 151-200        | 18       | 13.74%  |
| 301-350        | 14       | 10.69%  |
| 351-500        | 13       | 9.92%   |
| 141-150        | 13       | 9.92%   |
| 251-300        | 8        | 6.11%   |
| 91-100         | 4        | 3.05%   |
| 81-90          | 3        | 2.29%   |
| 501-1000       | 3        | 2.29%   |
| More than 1000 | 1        | 0.76%   |
| 61-70          | 1        | 0.76%   |
| 41-50          | 1        | 0.76%   |
| 121-130        | 1        | 0.76%   |
| 101-110        | 1        | 0.76%   |
| Unknown        | 1        | 0.76%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 73       | 55.3%   |
| 101-120       | 34       | 25.76%  |
| 121-160       | 11       | 8.33%   |
| 161-240       | 8        | 6.06%   |
| 1-50          | 4        | 3.03%   |
| More than 240 | 1        | 0.76%   |
| Unknown       | 1        | 0.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 163      | 52.92%  |
| 1     | 135      | 43.83%  |
| 2     | 8        | 2.6%    |
| 3     | 2        | 0.65%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Intel                             | 140      | 39%     |
| Realtek Semiconductor             | 128      | 35.65%  |
| Broadcom                          | 22       | 6.13%   |
| Qualcomm Atheros                  | 17       | 4.74%   |
| Qualcomm Atheros Communications   | 7        | 1.95%   |
| TP-Link                           | 5        | 1.39%   |
| VIA Technologies                  | 4        | 1.11%   |
| U-Blox                            | 4        | 1.11%   |
| Apple                             | 4        | 1.11%   |
| Ralink                            | 3        | 0.84%   |
| MediaTek                          | 3        | 0.84%   |
| Oracle/SUN                        | 2        | 0.56%   |
| D-Link System                     | 2        | 0.56%   |
| ASUSTek Computer                  | 2        | 0.56%   |
| 3Com                              | 2        | 0.56%   |
| Qualcomm Technologies             | 1        | 0.28%   |
| Qcom                              | 1        | 0.28%   |
| National Semiconductor            | 1        | 0.28%   |
| Motorola PCS                      | 1        | 0.28%   |
| LG Electronics                    | 1        | 0.28%   |
| Huawei Technologies               | 1        | 0.28%   |
| Ericsson Business Mobile Networks | 1        | 0.28%   |
| Emulex                            | 1        | 0.28%   |
| Edimax Technology                 | 1        | 0.28%   |
| Davicom Semiconductor             | 1        | 0.28%   |
| AVM                               | 1        | 0.28%   |
| Aquantia                          | 1        | 0.28%   |
| American Megatrends               | 1        | 0.28%   |
| Accton Technology                 | 1        | 0.28%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 93       | 22.74%  |
| Intel I211 Gigabit Network Connection                                         | 27       | 6.6%    |
| Intel I210 Gigabit Network Connection                                         | 23       | 5.62%   |
| Realtek RTL8125 2.5GbE Controller                                             | 14       | 3.42%   |
| Intel 82574L Gigabit Network Connection                                       | 13       | 3.18%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 10       | 2.44%   |
| Intel Wi-Fi 6 AX200                                                           | 9        | 2.2%    |
| Intel I350 Gigabit Network Connection                                         | 9        | 2.2%    |
| Intel Ethernet Connection I217-LM                                             | 7        | 1.71%   |
| Qualcomm Atheros AR9271 802.11n                                               | 5        | 1.22%   |
| Intel Ethernet Controller I225-V                                              | 5        | 1.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 5        | 1.22%   |
| U-Blox [u-blox 8]                                                             | 4        | 0.98%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 4        | 0.98%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 4        | 0.98%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                               | 4        | 0.98%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                     | 3        | 0.73%   |
| Intel Ethernet Connection I217-V                                              | 3        | 0.73%   |
| Intel Ethernet Connection (7) I219-LM                                         | 3        | 0.73%   |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 0.73%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 3        | 0.73%   |
| Intel 82579V Gigabit Network Connection                                       | 3        | 0.73%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 3        | 0.73%   |
| VIA VT6105M [Rhine-III]                                                       | 2        | 0.49%   |
| VIA VT6102/VT6103 [Rhine-II]                                                  | 2        | 0.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2        | 0.49%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 2        | 0.49%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 2        | 0.49%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                     | 2        | 0.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 2        | 0.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2        | 0.49%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 2        | 0.49%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                    | 2        | 0.49%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                 | 2        | 0.49%   |
| Intel Wireless 7260                                                           | 2        | 0.49%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 2        | 0.49%   |
| Intel Platform Controller Hub EG20T Gigabit Ethernet Controller               | 2        | 0.49%   |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 0.49%   |
| Intel Centrino Wireless-N 2230                                                | 2        | 0.49%   |
| Intel 82576 Gigabit Network Connection                                        | 2        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 29       | 34.94%  |
| Realtek Semiconductor           | 14       | 16.87%  |
| Qualcomm Atheros                | 14       | 16.87%  |
| Qualcomm Atheros Communications | 7        | 8.43%   |
| TP-Link                         | 5        | 6.02%   |
| Ralink                          | 3        | 3.61%   |
| MediaTek                        | 3        | 3.61%   |
| Broadcom                        | 2        | 2.41%   |
| ASUSTek Computer                | 2        | 2.41%   |
| Qualcomm Technologies           | 1        | 1.2%    |
| Qcom                            | 1        | 1.2%    |
| Edimax Technology               | 1        | 1.2%    |
| D-Link System                   | 1        | 1.2%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                  | 9        | 10.71%  |
| Qualcomm Atheros AR9271 802.11n                                                      | 5        | 5.95%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                       | 4        | 4.76%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                            | 3        | 3.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                             | 2        | 2.38%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                      | 2        | 2.38%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                            | 2        | 2.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                           | 2        | 2.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 2        | 2.38%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                       | 2        | 2.38%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                           | 2        | 2.38%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                        | 2        | 2.38%   |
| Intel Wireless 7260                                                                  | 2        | 2.38%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                | 2        | 2.38%   |
| Intel Centrino Wireless-N 2230                                                       | 2        | 2.38%   |
| TP-Link Wireless USB Adapter                                                         | 1        | 1.19%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                  | 1        | 1.19%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                         | 1        | 1.19%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                               | 1        | 1.19%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                  | 1        | 1.19%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                           | 1        | 1.19%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                             | 1        | 1.19%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                             | 1        | 1.19%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                      | 1        | 1.19%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                      | 1        | 1.19%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                               | 1        | 1.19%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                          | 1        | 1.19%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 1        | 1.19%   |
| Realtek RTL8188EE Wireless Network Adapter                                           | 1        | 1.19%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                           | 1        | 1.19%   |
| Realtek 802.11n WLAN Adapter                                                         | 1        | 1.19%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                            | 1        | 1.19%   |
| Qualcomm QCNFA765 Wireless Network Adapter                                           | 1        | 1.19%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                           | 1        | 1.19%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1        | 1.19%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170]        | 1        | 1.19%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                       | 1        | 1.19%   |
| Qcom RT73 USB Wireless LAN Card                                                      | 1        | 1.19%   |
| MediaTek 802.11ac Wireless LAN Card                                                  | 1        | 1.19%   |
| Intel Wireless 8265 / 8275                                                           | 1        | 1.19%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Realtek Semiconductor  | 124      | 42.76%  |
| Intel                  | 123      | 42.41%  |
| Broadcom               | 20       | 6.9%    |
| VIA Technologies       | 4        | 1.38%   |
| Apple                  | 4        | 1.38%   |
| Qualcomm Atheros       | 3        | 1.03%   |
| Oracle/SUN             | 2        | 0.69%   |
| 3Com                   | 2        | 0.69%   |
| National Semiconductor | 1        | 0.34%   |
| Motorola PCS           | 1        | 0.34%   |
| Emulex                 | 1        | 0.34%   |
| Davicom Semiconductor  | 1        | 0.34%   |
| D-Link System          | 1        | 0.34%   |
| Aquantia               | 1        | 0.34%   |
| American Megatrends    | 1        | 0.34%   |
| Accton Technology      | 1        | 0.34%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 93       | 29.43%  |
| Intel I211 Gigabit Network Connection                                         | 27       | 8.54%   |
| Intel I210 Gigabit Network Connection                                         | 23       | 7.28%   |
| Realtek RTL8125 2.5GbE Controller                                             | 14       | 4.43%   |
| Intel 82574L Gigabit Network Connection                                       | 13       | 4.11%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 10       | 3.16%   |
| Intel I350 Gigabit Network Connection                                         | 9        | 2.85%   |
| Intel Ethernet Connection I217-LM                                             | 7        | 2.22%   |
| Intel Ethernet Controller I225-V                                              | 5        | 1.58%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 5        | 1.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 4        | 1.27%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                               | 4        | 1.27%   |
| Intel Ethernet Connection I217-V                                              | 3        | 0.95%   |
| Intel Ethernet Connection (7) I219-LM                                         | 3        | 0.95%   |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 0.95%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 3        | 0.95%   |
| Intel 82579V Gigabit Network Connection                                       | 3        | 0.95%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 3        | 0.95%   |
| VIA VT6105M [Rhine-III]                                                       | 2        | 0.63%   |
| VIA VT6102/VT6103 [Rhine-II]                                                  | 2        | 0.63%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 2        | 0.63%   |
| Intel Platform Controller Hub EG20T Gigabit Ethernet Controller               | 2        | 0.63%   |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 0.63%   |
| Intel 82576 Gigabit Network Connection                                        | 2        | 0.63%   |
| Intel 82573L Gigabit Ethernet Controller                                      | 2        | 0.63%   |
| Intel 82573E Gigabit Ethernet Controller (Copper)                             | 2        | 0.63%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 2        | 0.63%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 2        | 0.63%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                       | 2        | 0.63%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                       | 2        | 0.63%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 2        | 0.63%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2        | 0.63%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 2        | 0.63%   |
| Broadcom NetXtreme BCM5703 Gigabit Ethernet                                   | 2        | 0.63%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 1        | 0.32%   |
| Realtek Killer E2600 GbE Controller                                           | 1        | 0.32%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 1        | 0.32%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1        | 0.32%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                 | 1        | 0.32%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 1        | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 271      | 75.49%  |
| WiFi     | 79       | 22.01%  |
| Modem    | 6        | 1.67%   |
| Unknown  | 3        | 0.84%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 196      | 85.59%  |
| WiFi     | 33       | 14.41%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 120      | 39.47%  |
| 2     | 77       | 25.33%  |
| 3     | 38       | 12.5%   |
| 4     | 28       | 9.21%   |
| 0     | 28       | 9.21%   |
| 5     | 4        | 1.32%   |
| 8     | 3        | 0.99%   |
| 7     | 2        | 0.66%   |
| 6     | 2        | 0.66%   |
| 12    | 1        | 0.33%   |
| 9     | 1        | 0.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 302      | 99.34%  |
| Yes  | 2        | 0.66%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 24       | 52.17%  |
| Realtek Semiconductor           | 4        | 8.7%    |
| Qualcomm Atheros Communications | 3        | 6.52%   |
| Foxconn / Hon Hai               | 3        | 6.52%   |
| Cambridge Silicon Radio         | 3        | 6.52%   |
| Apple                           | 3        | 6.52%   |
| IMC Networks                    | 2        | 4.35%   |
| Broadcom                        | 2        | 4.35%   |
| Hewlett-Packard                 | 1        | 2.17%   |
| ASUSTek Computer                | 1        | 2.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                       | 9        | 19.57%  |
| Intel Bluetooth wireless interface                          | 6        | 13.04%  |
| Realtek Bluetooth Adapter                                   | 4        | 8.7%    |
| Intel Centrino Bluetooth Wireless Transceiver               | 3        | 6.52%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 3        | 6.52%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2        | 4.35%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 2        | 4.35%   |
| Intel AX210 Bluetooth                                       | 2        | 4.35%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip        | 2        | 4.35%   |
| Foxconn / Hon Hai RZ616 Bluetooth Adapter                   | 2        | 4.35%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 2        | 4.35%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1        | 2.17%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1        | 2.17%   |
| Intel AX201 Bluetooth                                       | 1        | 2.17%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1        | 2.17%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1        | 2.17%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 1        | 2.17%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 1        | 2.17%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 1        | 2.17%   |
| Apple Bluetooth Host Controller                             | 1        | 2.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 111      | 42.21%  |
| AMD                                          | 93       | 35.36%  |
| Nvidia                                       | 22       | 8.37%   |
| C-Media Electronics                          | 10       | 3.8%    |
| VIA Technologies                             | 4        | 1.52%   |
| Logitech                                     | 3        | 1.14%   |
| Creative Labs                                | 3        | 1.14%   |
| ULi Electronics                              | 2        | 0.76%   |
| Texas Instruments                            | 2        | 0.76%   |
| JMTek                                        | 2        | 0.76%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.38%   |
| Thesycon Systemsoftware & Consulting         | 1        | 0.38%   |
| Lenovo                                       | 1        | 0.38%   |
| KTMicro                                      | 1        | 0.38%   |
| Generalplus Technology                       | 1        | 0.38%   |
| Focusrite-Novation                           | 1        | 0.38%   |
| ESS Technology                               | 1        | 0.38%   |
| Elgato Systems                               | 1        | 0.38%   |
| Dell                                         | 1        | 0.38%   |
| Creative Technology                          | 1        | 0.38%   |
| Blue Microphones                             | 1        | 0.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                          | 19       | 5.74%   |
| AMD Family 17h/19h HD Audio Controller                                            | 16       | 4.83%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 13       | 3.93%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 12       | 3.63%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 12       | 3.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 11       | 3.32%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 11       | 3.32%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 11       | 3.32%   |
| Intel Cannon Lake PCH cAVS                                                        | 9        | 2.72%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 9        | 2.72%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 9        | 2.72%   |
| AMD FCH Azalia Controller                                                         | 8        | 2.42%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 7        | 2.11%   |
| AMD Navi 10 HDMI Audio                                                            | 7        | 2.11%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 7        | 2.11%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 7        | 2.11%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 6        | 1.81%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 6        | 1.81%   |
| AMD Rembrandt Radeon High Definition Audio Controller                             | 6        | 1.81%   |
| Intel Comet Lake PCH-V cAVS                                                       | 5        | 1.51%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 5        | 1.51%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 5        | 1.51%   |
| Nvidia MCP61 High Definition Audio                                                | 4        | 1.21%   |
| Nvidia GP106 High Definition Audio Controller                                     | 4        | 1.21%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 4        | 1.21%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 3        | 0.91%   |
| Intel Sunrise Point-LP HD Audio                                                   | 3        | 0.91%   |
| Intel Jasper Lake HD Audio                                                        | 3        | 0.91%   |
| Intel 200 Series PCH HD Audio                                                     | 3        | 0.91%   |
| AMD Trinity HDMI Audio Controller                                                 | 3        | 0.91%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 3        | 0.91%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                      | 3        | 0.91%   |
| AMD Kabini HDMI/DP Audio                                                          | 3        | 0.91%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 3        | 0.91%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 3        | 0.91%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                         | 2        | 0.6%    |
| ULi Electronics M5451 PCI AC-Link Controller Audio Device                         | 2        | 0.6%    |
| Texas Instruments PCM2902 Audio Codec                                             | 2        | 0.6%    |
| Nvidia GP108 High Definition Audio Controller                                     | 2        | 0.6%    |
| Nvidia GF108 High Definition Audio Controller                                     | 2        | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 11       | 36.67%  |
| Kingston            | 5        | 16.67%  |
| Samsung Electronics | 3        | 10%     |
| Unknown             | 3        | 10%     |
| Transcend           | 2        | 6.67%   |
| Corsair             | 2        | 6.67%   |
| SK hynix            | 1        | 3.33%   |
| Ramaxel Technology  | 1        | 3.33%   |
| Nanya Technology    | 1        | 3.33%   |
| Elpida              | 1        | 3.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s       | 3        | 8.57%   |
| Unknown                                                 | 3        | 8.57%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s          | 2        | 5.71%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 2400MT/s     | 2        | 5.71%   |
| Unknown RAM Module 512MB DIMM SDRAM                     | 1        | 2.86%   |
| Unknown RAM Module 512MB DIMM DDR 400MT/s               | 1        | 2.86%   |
| Unknown RAM Module 512MB DIMM 400MT/s                   | 1        | 2.86%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s             | 1        | 2.86%   |
| Unknown RAM Module 2GB DIMM DDR3 1332MT/s               | 1        | 2.86%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                | 1        | 2.86%   |
| Unknown RAM Module 256MB DIMM 333MT/s                   | 1        | 2.86%   |
| Unknown RAM Module 2048MB DIMM DDR2 266MT/s             | 1        | 2.86%   |
| Unknown RAM Module 1GB DIMM 400MT/s                     | 1        | 2.86%   |
| Unknown RAM Module 1024MB DIMM DDR                      | 1        | 2.86%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                  | 1        | 2.86%   |
| Transcend RAM TS1GSK64W6H 8GB DIMM DDR3 1600MT/s        | 1        | 2.86%   |
| Transcend RAM TS128MLQ64V6J 1GB DIMM DDR2 667MT/s       | 1        | 2.86%   |
| SK hynix RAM HYMP112U64CP8-Y5 1GB DIMM DDR2 667MT/s     | 1        | 2.86%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s   | 1        | 2.86%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s   | 1        | 2.86%   |
| Samsung RAM M393A4K40CB1-CRC 32GB DIMM DDR4 2400MT/s    | 1        | 2.86%   |
| Samsung RAM M3 78T2953CZ3-CE6 1GB DIMM DDR2 667MT/s     | 1        | 2.86%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s | 1        | 2.86%   |
| Nanya RAM NT1GT64U88D0BY-AD 1024MB DIMM DDR2 800MT/s    | 1        | 2.86%   |
| Kingston RAM KF3600C18D4/32GX 32GB DIMM DDR4 3000MT/s   | 1        | 2.86%   |
| Kingston RAM 9905316-005.A04LF 1GB DIMM DDR2 667MT/s    | 1        | 2.86%   |
| Elpida RAM EBE11UD8AJWA-8G-E 1024MB DIMM DDR2 800MT/s   | 1        | 2.86%   |
| Corsair RAM CML16GX3M2A1600C9 8GB DIMM DDR3 1600MT/s    | 1        | 2.86%   |
| Corsair RAM CMK64GX5M2B5200C40 32GB DIMM DDR5 4800MT/s  | 1        | 2.86%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 8        | 30.77%  |
| DDR4    | 5        | 19.23%  |
| DDR2    | 4        | 15.38%  |
| Unknown | 4        | 15.38%  |
| SDRAM   | 2        | 7.69%   |
| DDR     | 2        | 7.69%   |
| DDR5    | 1        | 3.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 21       | 80.77%  |
| SODIMM | 5        | 19.23%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 7        | 23.33%  |
| 1024  | 6        | 20%     |
| 8192  | 5        | 16.67%  |
| 2048  | 4        | 13.33%  |
| 512   | 4        | 13.33%  |
| 32768 | 3        | 10%     |
| 256   | 1        | 3.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 2400    | 4        | 14.81%  |
| 1600    | 4        | 14.81%  |
| Unknown | 4        | 14.81%  |
| 1333    | 3        | 11.11%  |
| 800     | 3        | 11.11%  |
| 667     | 2        | 7.41%   |
| 400     | 2        | 7.41%   |
| 4800    | 1        | 3.7%    |
| 3000    | 1        | 3.7%    |
| 1332    | 1        | 3.7%    |
| 333     | 1        | 3.7%    |
| 266     | 1        | 3.7%    |

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

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Seiko Epson | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO] | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Logitech                | 5        | 38.46%  |
| Microdia                | 2        | 15.38%  |
| Chicony Electronics     | 2        | 15.38%  |
| Z-Star Microelectronics | 1        | 7.69%   |
| Ricoh                   | 1        | 7.69%   |
| Realtek Semiconductor   | 1        | 7.69%   |
| Generalplus Technology  | 1        | 7.69%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Z-Star Integrated Camera             | 1        | 7.69%   |
| Ricoh USB2.0 Camera                  | 1        | 7.69%   |
| Realtek Integrated Webcam HD         | 1        | 7.69%   |
| Microdia USB 2.0 Camera              | 1        | 7.69%   |
| Microdia Ltd., USB  Live camera      | 1        | 7.69%   |
| Logitech Webcam C310                 | 1        | 7.69%   |
| Logitech Webcam C270                 | 1        | 7.69%   |
| Logitech HD Pro Webcam C920          | 1        | 7.69%   |
| Logitech C920 PRO HD Webcam          | 1        | 7.69%   |
| Logitech C920 HD Pro Webcam          | 1        | 7.69%   |
| Generalplus HD Webcam                | 1        | 7.69%   |
| Chicony Ltd., HP 0.3MP Webcam        | 1        | 7.69%   |
| Chicony Integrated Camera [ThinkPad] | 1        | 7.69%   |

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
| 0     | 151      | 49.19%  |
| 1     | 98       | 31.92%  |
| 2     | 47       | 15.31%  |
| 3     | 7        | 2.28%   |
| 7     | 2        | 0.65%   |
| 5     | 1        | 0.33%   |
| 4     | 1        | 0.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 101      | 47.87%  |
| Graphics card            | 35       | 16.59%  |
| Firewire controller      | 22       | 10.43%  |
| Net/wireless             | 19       | 9%      |
| Net/ethernet             | 11       | 5.21%   |
| Storage/ata              | 9        | 4.27%   |
| Sound                    | 9        | 4.27%   |
| Storage                  | 2        | 0.95%   |
| Storage/raid             | 1        | 0.47%   |
| Storage/ide              | 1        | 0.47%   |
| Network                  | 1        | 0.47%   |

