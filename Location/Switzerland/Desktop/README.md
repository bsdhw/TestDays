BSD in Switzerland - Tested Hardware & Statistics (Desktops)
------------------------------------------------------------

A project to collect tested hardware configurations for BSD in Switzerland.

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
| Protectli     | VP2420                      | [a3a282fc47](https://bsd-hardware.info/?probe=a3a282fc47) | Jan 04, 2025 |
| IGEL Techn... | IGEL-D220                   | [9d3ca29f8a](https://bsd-hardware.info/?probe=9d3ca29f8a) | Dec 30, 2024 |
| PC Engines    | apu4                        | [1245a959bc](https://bsd-hardware.info/?probe=1245a959bc) | Dec 19, 2024 |
| Unknown       | Unknown                     | [4d58aebb29](https://bsd-hardware.info/?probe=4d58aebb29) | Dec 18, 2024 |
| Supermicro    | X11SDV-4C-TP8F              | [f031d48a53](https://bsd-hardware.info/?probe=f031d48a53) | Dec 16, 2024 |
| Supermicro    | X11SDV-4C-TP8F              | [1eb9f463b0](https://bsd-hardware.info/?probe=1eb9f463b0) | Dec 16, 2024 |
| Unknown       | Unknown                     | [696aedf790](https://bsd-hardware.info/?probe=696aedf790) | Dec 13, 2024 |
| Silicom       | 80300-0134-g01              | [9c18dc951c](https://bsd-hardware.info/?probe=9c18dc951c) | Dec 11, 2024 |
| Unknown       | Unknown                     | [3a099cfc0b](https://bsd-hardware.info/?probe=3a099cfc0b) | Dec 07, 2024 |
| PC Engines    | APU2                        | [897b7914d9](https://bsd-hardware.info/?probe=897b7914d9) | Dec 04, 2024 |
| Intel         | D34010WYK H14771-303        | [cc9f37f097](https://bsd-hardware.info/?probe=cc9f37f097) | Dec 04, 2024 |
| Intel         | HURONRIVER                  | [d74d9a6d06](https://bsd-hardware.info/?probe=d74d9a6d06) | Nov 27, 2024 |
| Gowin Solu... | GW-MB-U01                   | [2626f42aad](https://bsd-hardware.info/?probe=2626f42aad) | Nov 25, 2024 |
| ASRock        | B550 Taichi                 | [8ef9cf51fb](https://bsd-hardware.info/?probe=8ef9cf51fb) | Nov 21, 2024 |
| Shuttle       | FH61V                       | [1770dc6006](https://bsd-hardware.info/?probe=1770dc6006) | Nov 19, 2024 |
| Shenzhen M... | AHWSA                       | [8e58ca6121](https://bsd-hardware.info/?probe=8e58ca6121) | Nov 14, 2024 |
| PC Engines    | APU                         | [933dc34c47](https://bsd-hardware.info/?probe=933dc34c47) | Nov 14, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [8583a7eb2e](https://bsd-hardware.info/?probe=8583a7eb2e) | Nov 09, 2024 |
| Shenzhen M... | AHWSA                       | [123789a341](https://bsd-hardware.info/?probe=123789a341) | Nov 07, 2024 |
| HP            | 1494                        | [ac956f4a8a](https://bsd-hardware.info/?probe=ac956f4a8a) | Nov 04, 2024 |
| Supermicro    | X11SDV-4C-TP8F              | [ae14bea998](https://bsd-hardware.info/?probe=ae14bea998) | Nov 02, 2024 |
| Unknown       | Unknown                     | [aeaca5f3a0](https://bsd-hardware.info/?probe=aeaca5f3a0) | Oct 24, 2024 |
| Unknown       | Unknown                     | [f191f5d343](https://bsd-hardware.info/?probe=f191f5d343) | Oct 23, 2024 |
| HP            | 1494                        | [154852b17b](https://bsd-hardware.info/?probe=154852b17b) | Oct 22, 2024 |
| Unknown       | Unknown                     | [574cd1a009](https://bsd-hardware.info/?probe=574cd1a009) | Oct 18, 2024 |
| PC Engines    | APU                         | [05d1822d02](https://bsd-hardware.info/?probe=05d1822d02) | Oct 17, 2024 |
| PC Engines    | APU                         | [1ccdfd7edd](https://bsd-hardware.info/?probe=1ccdfd7edd) | Oct 17, 2024 |
| PC Engines    | apu4                        | [d185e2c850](https://bsd-hardware.info/?probe=d185e2c850) | Oct 16, 2024 |
| Shenzhen M... | AHWSA                       | [d8cf190bc2](https://bsd-hardware.info/?probe=d8cf190bc2) | Sep 28, 2024 |
| Unknown       | Unknown                     | [d9e63995fb](https://bsd-hardware.info/?probe=d9e63995fb) | Sep 28, 2024 |
| Unknown       | Unknown                     | [9ddfeb7780](https://bsd-hardware.info/?probe=9ddfeb7780) | Sep 21, 2024 |
| Protectli     | V1410                       | [452edd44ed](https://bsd-hardware.info/?probe=452edd44ed) | Sep 20, 2024 |
| Shuttle       | DL30N                       | [895fb08a2f](https://bsd-hardware.info/?probe=895fb08a2f) | Sep 18, 2024 |
| Intel BOX4... | Geminilake                  | [7bc6403170](https://bsd-hardware.info/?probe=7bc6403170) | Sep 14, 2024 |
| Protectli     | VP6670                      | [6bf32f779c](https://bsd-hardware.info/?probe=6bf32f779c) | Sep 14, 2024 |
| Techvision    | TVI7309X B0                 | [52e2d4ad6a](https://bsd-hardware.info/?probe=52e2d4ad6a) | Aug 29, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [db7a0dda31](https://bsd-hardware.info/?probe=db7a0dda31) | Aug 26, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [c56df5fe7c](https://bsd-hardware.info/?probe=c56df5fe7c) | Aug 25, 2024 |
| Shuttle       | FH310V                      | [ca649bfffa](https://bsd-hardware.info/?probe=ca649bfffa) | Aug 23, 2024 |
| LinuxConta... | Incus pc-q35-9.0            | [550411a5aa](https://bsd-hardware.info/?probe=550411a5aa) | Aug 04, 2024 |
| Supermicro    | X11SDV-4C-TLN2F             | [b2bd066528](https://bsd-hardware.info/?probe=b2bd066528) | Aug 02, 2024 |
| Supermicro    | X11SDV-4C-TLN2F             | [be116a0073](https://bsd-hardware.info/?probe=be116a0073) | Aug 02, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [e96f250351](https://bsd-hardware.info/?probe=e96f250351) | Aug 01, 2024 |
| Unknown       | Unknown                     | [2f1762c0ca](https://bsd-hardware.info/?probe=2f1762c0ca) | Jul 26, 2024 |
| Unknown       | QDNV01                      | [6c29d0b29c](https://bsd-hardware.info/?probe=6c29d0b29c) | Jul 19, 2024 |
| Shuttle       | DL30N                       | [8004067dfc](https://bsd-hardware.info/?probe=8004067dfc) | Jul 02, 2024 |
| Protectli     | VP6670                      | [9c24cea9d2](https://bsd-hardware.info/?probe=9c24cea9d2) | Jun 16, 2024 |
| HP            | ProLiant ML350p Gen8        | [820bfd0c77](https://bsd-hardware.info/?probe=820bfd0c77) | Jun 14, 2024 |
| Unknown       | Unknown                     | [71e118978a](https://bsd-hardware.info/?probe=71e118978a) | May 19, 2024 |
| Trigkey       | Green G5                    | [85a239bc2f](https://bsd-hardware.info/?probe=85a239bc2f) | May 18, 2024 |
| Unknown       | QDNV01                      | [f23cb7b083](https://bsd-hardware.info/?probe=f23cb7b083) | May 18, 2024 |
| Unknown       | QDNV01                      | [9b0fbcd081](https://bsd-hardware.info/?probe=9b0fbcd081) | May 18, 2024 |
| ASUSTek       | H170M-E D3                  | [a07851f5f5](https://bsd-hardware.info/?probe=a07851f5f5) | May 13, 2024 |
| Trigkey       | Green G5                    | [0cc228bf09](https://bsd-hardware.info/?probe=0cc228bf09) | May 09, 2024 |
| ASUSTek       | TUF Gaming A620-PRO WIFI    | [a186355a65](https://bsd-hardware.info/?probe=a186355a65) | May 02, 2024 |
| Trigkey       | Green G5                    | [6bad716921](https://bsd-hardware.info/?probe=6bad716921) | Apr 26, 2024 |
| Intel         | SHARKBAY                    | [cbe3a65615](https://bsd-hardware.info/?probe=cbe3a65615) | Apr 16, 2024 |
| Unknown       | QDNV01                      | [e90c02d0da](https://bsd-hardware.info/?probe=e90c02d0da) | Apr 13, 2024 |
| ASUSTek       | Z97-A                       | [2f83e16bd9](https://bsd-hardware.info/?probe=2f83e16bd9) | Apr 11, 2024 |
| PC Engines    | APU2                        | [22fc545294](https://bsd-hardware.info/?probe=22fc545294) | Apr 11, 2024 |
| Unknown       | Unknown                     | [258e758f9b](https://bsd-hardware.info/?probe=258e758f9b) | Mar 30, 2024 |
| MW            | GMLK-2_5G4L                 | [690a945c99](https://bsd-hardware.info/?probe=690a945c99) | Mar 30, 2024 |
| PC Engines    | APU2                        | [e5ac53d0d4](https://bsd-hardware.info/?probe=e5ac53d0d4) | Mar 26, 2024 |
| Unknown       | Unknown                     | [352fb163da](https://bsd-hardware.info/?probe=352fb163da) | Mar 24, 2024 |
| Unknown       | Unknown                     | [462b269f0f](https://bsd-hardware.info/?probe=462b269f0f) | Mar 18, 2024 |
| Supermicro    | X11SDW-8C-TP13F             | [8092b98305](https://bsd-hardware.info/?probe=8092b98305) | Mar 11, 2024 |
| Dell          | 0X4N41 A01                  | [25688a2cac](https://bsd-hardware.info/?probe=25688a2cac) | Mar 11, 2024 |
| Unknown       | Unknown                     | [cc261708c0](https://bsd-hardware.info/?probe=cc261708c0) | Mar 02, 2024 |
| Unknown       | Unknown                     | [0960d6e3b5](https://bsd-hardware.info/?probe=0960d6e3b5) | Feb 29, 2024 |
| PC Engines    | APU2                        | [513a0febb8](https://bsd-hardware.info/?probe=513a0febb8) | Feb 20, 2024 |
| PC Engines    | APU2                        | [4f83cef1be](https://bsd-hardware.info/?probe=4f83cef1be) | Feb 20, 2024 |
| ASUSTek       | Q87T                        | [cc75f2f0fa](https://bsd-hardware.info/?probe=cc75f2f0fa) | Feb 18, 2024 |
| PC Engines    | apu6                        | [9f618d2d95](https://bsd-hardware.info/?probe=9f618d2d95) | Feb 17, 2024 |
| Unknown       | Unknown                     | [0a1749e911](https://bsd-hardware.info/?probe=0a1749e911) | Feb 17, 2024 |
| ASUSTek       | Q87T                        | [ca381bbbcc](https://bsd-hardware.info/?probe=ca381bbbcc) | Feb 17, 2024 |
| ASRock        | B550 Taichi                 | [814a0aba66](https://bsd-hardware.info/?probe=814a0aba66) | Feb 14, 2024 |
| ASRock        | B450M Pro4 R2.0             | [55d74d88f2](https://bsd-hardware.info/?probe=55d74d88f2) | Feb 06, 2024 |
| Unknown       | Unknown                     | [f206c1a24c](https://bsd-hardware.info/?probe=f206c1a24c) | Feb 05, 2024 |
| Unknown       | Unknown                     | [829691c455](https://bsd-hardware.info/?probe=829691c455) | Jan 26, 2024 |
| Shuttle       | FS110                       | [48cc3837da](https://bsd-hardware.info/?probe=48cc3837da) | Jan 14, 2024 |
| HP            | 1905                        | [9e67ddf10b](https://bsd-hardware.info/?probe=9e67ddf10b) | Jan 05, 2024 |
| PC Engines    | APU2                        | [79f4518fa1](https://bsd-hardware.info/?probe=79f4518fa1) | Dec 23, 2023 |
| ASUSTek       | PRIME H610I-PLUS D4         | [3a435d185e](https://bsd-hardware.info/?probe=3a435d185e) | Dec 22, 2023 |
| PC Engines    | APU2                        | [f3061d599c](https://bsd-hardware.info/?probe=f3061d599c) | Dec 19, 2023 |
| Intel         | HURONRIVER                  | [d0ebaa4479](https://bsd-hardware.info/?probe=d0ebaa4479) | Dec 17, 2023 |
| Unknown       | QDNV01                      | [63cbf7642b](https://bsd-hardware.info/?probe=63cbf7642b) | Nov 28, 2023 |
| ASRock        | B550 Taichi                 | [60d2873b5d](https://bsd-hardware.info/?probe=60d2873b5d) | Nov 26, 2023 |
| Unknown       | YL-SKUL6                    | [ac654676da](https://bsd-hardware.info/?probe=ac654676da) | Nov 16, 2023 |
| ASUSTek       | Z97-A                       | [3ce8e78453](https://bsd-hardware.info/?probe=3ce8e78453) | Nov 11, 2023 |
| Dell          | 0WR7PY A02                  | [3ce02454f8](https://bsd-hardware.info/?probe=3ce02454f8) | Nov 09, 2023 |
| Unknown       | Unknown                     | [876b0db38a](https://bsd-hardware.info/?probe=876b0db38a) | Nov 07, 2023 |
| ASUSTek       | Z97-A                       | [a8aad4a386](https://bsd-hardware.info/?probe=a8aad4a386) | Nov 04, 2023 |
| Yanling       | YL-KBR6L Ver:1.01           | [bdc7be2258](https://bsd-hardware.info/?probe=bdc7be2258) | Oct 29, 2023 |
| GoWin Solu... | R86S                        | [8668f0e8e9](https://bsd-hardware.info/?probe=8668f0e8e9) | Oct 24, 2023 |
| Unknown       | Unknown                     | [135c0112a4](https://bsd-hardware.info/?probe=135c0112a4) | Oct 21, 2023 |
| Unknown       | QDNV01                      | [df90627ba3](https://bsd-hardware.info/?probe=df90627ba3) | Oct 17, 2023 |
| Unknown       | Unknown                     | [50418139b2](https://bsd-hardware.info/?probe=50418139b2) | Sep 30, 2023 |
| PC Engines    | APU                         | [ca9bc2faa7](https://bsd-hardware.info/?probe=ca9bc2faa7) | Sep 29, 2023 |
| PC Engines    | APU                         | [067872c1f5](https://bsd-hardware.info/?probe=067872c1f5) | Sep 29, 2023 |
| PC Engines    | APU2                        | [252385ae71](https://bsd-hardware.info/?probe=252385ae71) | Sep 27, 2023 |
| GoWin Solu... | R86S                        | [6d38812084](https://bsd-hardware.info/?probe=6d38812084) | Sep 22, 2023 |
| HP            | 1790                        | [17ace3bb2c](https://bsd-hardware.info/?probe=17ace3bb2c) | Sep 18, 2023 |
| ASUSTek       | H170M-E D3                  | [f9bde14ab2](https://bsd-hardware.info/?probe=f9bde14ab2) | Sep 10, 2023 |
| Techvision    | TVI7309X B0                 | [e59ce0fb84](https://bsd-hardware.info/?probe=e59ce0fb84) | Aug 21, 2023 |
| Supermicro    | X11SDW-8C-TP13F             | [da4385727b](https://bsd-hardware.info/?probe=da4385727b) | Aug 19, 2023 |
| PC Engines    | apu6                        | [65fda0fe1f](https://bsd-hardware.info/?probe=65fda0fe1f) | Aug 11, 2023 |
| Lenovo        | 3743 SDK0T76461 WIN 3422... | [d5675b5940](https://bsd-hardware.info/?probe=d5675b5940) | Aug 06, 2023 |
| Intel BOX4... | Geminilake                  | [b833ada775](https://bsd-hardware.info/?probe=b833ada775) | Aug 01, 2023 |
| GoWin Solu... | R86S                        | [51bb255924](https://bsd-hardware.info/?probe=51bb255924) | Jul 29, 2023 |
| Unknown       | Unknown                     | [dc7318d29f](https://bsd-hardware.info/?probe=dc7318d29f) | Jul 15, 2023 |
| Unknown       | Unknown                     | [9ce40969da](https://bsd-hardware.info/?probe=9ce40969da) | Jul 11, 2023 |
| Protectli     | VP2410                      | [8ad8c5daa9](https://bsd-hardware.info/?probe=8ad8c5daa9) | Jul 03, 2023 |
| Gigabyte      | J4005ND2P-CF                | [ee61a4b160](https://bsd-hardware.info/?probe=ee61a4b160) | Jun 17, 2023 |
| PC Engines    | apu4                        | [f130ecbaa3](https://bsd-hardware.info/?probe=f130ecbaa3) | Jun 01, 2023 |
| Unknown       | Unknown                     | [c1854cc5f2](https://bsd-hardware.info/?probe=c1854cc5f2) | May 27, 2023 |
| ASRock        | Z68 Pro3 Gen3               | [0a03cd86a0](https://bsd-hardware.info/?probe=0a03cd86a0) | May 21, 2023 |
| HP            | 8299                        | [f5ecf1eaeb](https://bsd-hardware.info/?probe=f5ecf1eaeb) | May 17, 2023 |
| CWWK          | MINIPC-G12                  | [b26aab0f0d](https://bsd-hardware.info/?probe=b26aab0f0d) | May 17, 2023 |
| PC Engines    | apu6                        | [3733cf215f](https://bsd-hardware.info/?probe=3733cf215f) | May 13, 2023 |
| Supermicro    | X11SDW-16C-TP13F+           | [1cc0308686](https://bsd-hardware.info/?probe=1cc0308686) | May 13, 2023 |
| MW            | GMLK-2_5G4L                 | [9fea438eba](https://bsd-hardware.info/?probe=9fea438eba) | May 07, 2023 |
| ASUSTek       | PRIME H610I-PLUS D4         | [472c5fb78e](https://bsd-hardware.info/?probe=472c5fb78e) | Apr 29, 2023 |
| PC Engines    | APU2                        | [4337168a3a](https://bsd-hardware.info/?probe=4337168a3a) | Apr 20, 2023 |
| Supermicro    | M11SDV-8C-LN4F              | [49a95f197c](https://bsd-hardware.info/?probe=49a95f197c) | Apr 20, 2023 |
| Intel BOX4... | Geminilake                  | [79d72cc60f](https://bsd-hardware.info/?probe=79d72cc60f) | Apr 13, 2023 |
| PC Engines    | APU2                        | [766755078c](https://bsd-hardware.info/?probe=766755078c) | Apr 10, 2023 |
| GoWin Solu... | R86S                        | [35e1503946](https://bsd-hardware.info/?probe=35e1503946) | Mar 08, 2023 |
| Protectli     | FW4C Ver                    | [d93437d96b](https://bsd-hardware.info/?probe=d93437d96b) | Mar 04, 2023 |
| Shuttle       | FS81                        | [5787eda5ac](https://bsd-hardware.info/?probe=5787eda5ac) | Feb 26, 2023 |
| Unknown       | Unknown                     | [913946ccc9](https://bsd-hardware.info/?probe=913946ccc9) | Feb 25, 2023 |
| Techvision    | TVI7309X B0                 | [0e62dfc436](https://bsd-hardware.info/?probe=0e62dfc436) | Feb 25, 2023 |
| Dell          | 05XGC8 A01                  | [c51a264e20](https://bsd-hardware.info/?probe=c51a264e20) | Feb 23, 2023 |
| Supermicro    | M11SDV-8C-LN4F              | [4874e3417f](https://bsd-hardware.info/?probe=4874e3417f) | Feb 09, 2023 |
| Intel BOX4... | Geminilake                  | [286c29b1bb](https://bsd-hardware.info/?probe=286c29b1bb) | Feb 08, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [3a47e70001](https://bsd-hardware.info/?probe=3a47e70001) | Feb 03, 2023 |
| PC Engines    | apu4                        | [c3ff966a17](https://bsd-hardware.info/?probe=c3ff966a17) | Feb 03, 2023 |
| PC Engines    | APU2                        | [315ef90664](https://bsd-hardware.info/?probe=315ef90664) | Feb 01, 2023 |
| Techvision    | TVI7309X B0                 | [739cc6e5ac](https://bsd-hardware.info/?probe=739cc6e5ac) | Jan 18, 2023 |
| Intel         | HURONRIVER                  | [9994ae920b](https://bsd-hardware.info/?probe=9994ae920b) | Jan 15, 2023 |
| Intel         | HURONRIVER                  | [320272bdf1](https://bsd-hardware.info/?probe=320272bdf1) | Jan 11, 2023 |
| PC Engines    | apu4                        | [3d69b3aec1](https://bsd-hardware.info/?probe=3d69b3aec1) | Jan 03, 2023 |
| PC Engines    | apu4                        | [62e6e7e679](https://bsd-hardware.info/?probe=62e6e7e679) | Jan 03, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [d22c37fa81](https://bsd-hardware.info/?probe=d22c37fa81) | Dec 29, 2022 |
| Intel BOX4... | Geminilake                  | [a2b2b7c25f](https://bsd-hardware.info/?probe=a2b2b7c25f) | Dec 23, 2022 |
| HP            | ProLiant MicroServer Gen... | [a2bc442acd](https://bsd-hardware.info/?probe=a2bc442acd) | Dec 23, 2022 |
| Intel BOX4... | Geminilake                  | [06933f3d87](https://bsd-hardware.info/?probe=06933f3d87) | Dec 23, 2022 |
| Dell          | 0X4N41 A01                  | [4091e15cac](https://bsd-hardware.info/?probe=4091e15cac) | Dec 14, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [1d8397a653](https://bsd-hardware.info/?probe=1d8397a653) | Dec 10, 2022 |
| Unknown       | Unknown                     | [0405fd0f0d](https://bsd-hardware.info/?probe=0405fd0f0d) | Dec 09, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [c30f53fc6d](https://bsd-hardware.info/?probe=c30f53fc6d) | Dec 09, 2022 |
| Unknown       | Unknown                     | [78893acbd5](https://bsd-hardware.info/?probe=78893acbd5) | Dec 06, 2022 |
| Unknown       | Unknown                     | [a5b10d3f79](https://bsd-hardware.info/?probe=a5b10d3f79) | Nov 29, 2022 |
| Unknown       | Unknown                     | [2fe35064cb](https://bsd-hardware.info/?probe=2fe35064cb) | Nov 28, 2022 |
| MW            | GMLK-2_5G4L                 | [7f9869324b](https://bsd-hardware.info/?probe=7f9869324b) | Nov 26, 2022 |
| Unknown       | Unknown                     | [77e932dd9e](https://bsd-hardware.info/?probe=77e932dd9e) | Nov 23, 2022 |
| Infoblox      | IB-1410                     | [7521108ef5](https://bsd-hardware.info/?probe=7521108ef5) | Nov 23, 2022 |
| Unknown       | Unknown                     | [521008f8da](https://bsd-hardware.info/?probe=521008f8da) | Nov 10, 2022 |
| Unknown       | Unknown                     | [bc7a300434](https://bsd-hardware.info/?probe=bc7a300434) | Nov 02, 2022 |
| Unknown       | Unknown                     | [2fc5bd737a](https://bsd-hardware.info/?probe=2fc5bd737a) | Oct 09, 2022 |
| PC Engines    | APU2                        | [47e38f3abe](https://bsd-hardware.info/?probe=47e38f3abe) | Oct 05, 2022 |
| Unknown       | Unknown                     | [02a9700c12](https://bsd-hardware.info/?probe=02a9700c12) | Oct 03, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [353008eb5e](https://bsd-hardware.info/?probe=353008eb5e) | Sep 29, 2022 |
| PC Engines    | APU2                        | [3fcc5e5ae2](https://bsd-hardware.info/?probe=3fcc5e5ae2) | Sep 25, 2022 |
| HP            | ProLiant ML350p Gen8        | [1a9c6a10bd](https://bsd-hardware.info/?probe=1a9c6a10bd) | Sep 19, 2022 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [a24f08281d](https://bsd-hardware.info/?probe=a24f08281d) | Sep 19, 2022 |
| Apple         | Mac-7BA5B2D9E42DDD94        | [d2e169b8ad](https://bsd-hardware.info/?probe=d2e169b8ad) | Sep 13, 2022 |
| Unknown       | Unknown                     | [9422de47ab](https://bsd-hardware.info/?probe=9422de47ab) | Aug 30, 2022 |
| Shuttle       | FS81                        | [b2db8ceabe](https://bsd-hardware.info/?probe=b2db8ceabe) | Aug 24, 2022 |
| Dell          | 02YYK5 A00                  | [5428710004](https://bsd-hardware.info/?probe=5428710004) | Aug 16, 2022 |
| Acer          | Aspire X3995                | [9240256ae5](https://bsd-hardware.info/?probe=9240256ae5) | Aug 06, 2022 |
| Unknown       | Unknown                     | [9f98df6faf](https://bsd-hardware.info/?probe=9f98df6faf) | Aug 05, 2022 |
| Unknown       | Unknown                     | [25ca16baef](https://bsd-hardware.info/?probe=25ca16baef) | Aug 05, 2022 |
| Unknown       | Unknown                     | [f9bf5b2e00](https://bsd-hardware.info/?probe=f9bf5b2e00) | Aug 04, 2022 |
| PC Engines    | APU2                        | [35d0a79b04](https://bsd-hardware.info/?probe=35d0a79b04) | Aug 04, 2022 |
| Protectli     | FW6                         | [b686fdf1c1](https://bsd-hardware.info/?probe=b686fdf1c1) | Jul 31, 2022 |
| Unknown       | Unknown                     | [0b84314fbf](https://bsd-hardware.info/?probe=0b84314fbf) | Jul 28, 2022 |
| Unknown       | Unknown                     | [4e721b00d5](https://bsd-hardware.info/?probe=4e721b00d5) | Jul 28, 2022 |
| PC Engines    | APU2                        | [7d3a1f2825](https://bsd-hardware.info/?probe=7d3a1f2825) | Jul 14, 2022 |
| PC Engines    | APU2                        | [0dd60aeb9a](https://bsd-hardware.info/?probe=0dd60aeb9a) | Jul 14, 2022 |
| Biostar       | H61MHV2                     | [58a61e6171](https://bsd-hardware.info/?probe=58a61e6171) | Jul 11, 2022 |
| Biostar       | H61MHV2                     | [2aa5e2a62d](https://bsd-hardware.info/?probe=2aa5e2a62d) | Jul 08, 2022 |
| Dell          | 02YYK5 A00                  | [fb2e5bec61](https://bsd-hardware.info/?probe=fb2e5bec61) | Jul 05, 2022 |
| Dell          | 02YYK5 A00                  | [629de6cdb6](https://bsd-hardware.info/?probe=629de6cdb6) | Jul 05, 2022 |
| HP            | 1494                        | [3a61eb7bae](https://bsd-hardware.info/?probe=3a61eb7bae) | Jul 01, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [34bb6613ee](https://bsd-hardware.info/?probe=34bb6613ee) | Jun 23, 2022 |
| Unknown       | Unknown                     | [d7d6b654a4](https://bsd-hardware.info/?probe=d7d6b654a4) | Jun 22, 2022 |
| Dell          | 02YYK5 A00                  | [180af6a2da](https://bsd-hardware.info/?probe=180af6a2da) | Jun 19, 2022 |
| Dell          | 02YYK5 A00                  | [c58d529930](https://bsd-hardware.info/?probe=c58d529930) | Jun 19, 2022 |
| MW            | GMLK-2_5G4L                 | [97e567c06b](https://bsd-hardware.info/?probe=97e567c06b) | Jun 18, 2022 |
| ASUSTek       | Pro B660M-C D4              | [302ea8252d](https://bsd-hardware.info/?probe=302ea8252d) | Jun 08, 2022 |
| PC Engines    | apu4                        | [1067180759](https://bsd-hardware.info/?probe=1067180759) | May 31, 2022 |
| PC Engines    | apu4                        | [214bc37259](https://bsd-hardware.info/?probe=214bc37259) | May 26, 2022 |
| Protectli     | FW6                         | [0dc7509652](https://bsd-hardware.info/?probe=0dc7509652) | May 24, 2022 |
| Unknown       | Unknown                     | [7c260c2423](https://bsd-hardware.info/?probe=7c260c2423) | May 20, 2022 |
| Intel         | D54250WYK H13922-303        | [8f9e0896d7](https://bsd-hardware.info/?probe=8f9e0896d7) | May 12, 2022 |
| Dell          | 0X4N41 A01                  | [d1596f34bf](https://bsd-hardware.info/?probe=d1596f34bf) | May 12, 2022 |
| Intel         | D54250WYK H13922-303        | [6dfeb3d80d](https://bsd-hardware.info/?probe=6dfeb3d80d) | May 10, 2022 |
| Intel         | HURONRIVER                  | [515172b464](https://bsd-hardware.info/?probe=515172b464) | May 09, 2022 |
| PC Engines    | APU2                        | [a2b68686f0](https://bsd-hardware.info/?probe=a2b68686f0) | Apr 27, 2022 |
| Dell          | 0TP406                      | [775061bc83](https://bsd-hardware.info/?probe=775061bc83) | Apr 25, 2022 |
| Biostar       | H61MHV2                     | [7d9806d719](https://bsd-hardware.info/?probe=7d9806d719) | Apr 21, 2022 |
| Gigabyte      | 990FXA-UD3                  | [378021707a](https://bsd-hardware.info/?probe=378021707a) | Apr 17, 2022 |
| PC Engines    | apu4                        | [62df504364](https://bsd-hardware.info/?probe=62df504364) | Apr 09, 2022 |
| Dell          | 0TP406                      | [9a29305ef1](https://bsd-hardware.info/?probe=9a29305ef1) | Apr 06, 2022 |
| Unknown       | Unknown                     | [b6b1ec9dc1](https://bsd-hardware.info/?probe=b6b1ec9dc1) | Mar 30, 2022 |
| ASRockRack    | X570D4U-2L2T                | [7e042aa70d](https://bsd-hardware.info/?probe=7e042aa70d) | Mar 25, 2022 |
| Unknown       | Unknown                     | [abb17bcb42](https://bsd-hardware.info/?probe=abb17bcb42) | Mar 21, 2022 |
| Unknown       | Unknown                     | [1d97ecbc95](https://bsd-hardware.info/?probe=1d97ecbc95) | Mar 20, 2022 |
| Unknown       | Unknown                     | [e169892276](https://bsd-hardware.info/?probe=e169892276) | Mar 18, 2022 |
| Dell          | 0X4N41 A01                  | [456b55de38](https://bsd-hardware.info/?probe=456b55de38) | Mar 17, 2022 |
| Unknown       | Unknown                     | [1ed23967fd](https://bsd-hardware.info/?probe=1ed23967fd) | Mar 17, 2022 |
| Dell          | 0X4N41 A01                  | [4d7d8fd92b](https://bsd-hardware.info/?probe=4d7d8fd92b) | Mar 17, 2022 |
| Unknown       | Unknown                     | [95154c4898](https://bsd-hardware.info/?probe=95154c4898) | Mar 16, 2022 |
| PC Engines    | APU2                        | [6e5badb880](https://bsd-hardware.info/?probe=6e5badb880) | Mar 04, 2022 |
| Intel         | Q3XXG4-P V1.0               | [7da5182091](https://bsd-hardware.info/?probe=7da5182091) | Feb 27, 2022 |
| PC Engines    | APU2                        | [40ba1b35da](https://bsd-hardware.info/?probe=40ba1b35da) | Feb 24, 2022 |
| Dell          | 0X4N41 A01                  | [fea17bcf92](https://bsd-hardware.info/?probe=fea17bcf92) | Feb 19, 2022 |
| PC Engines    | APU2                        | [547be2fb61](https://bsd-hardware.info/?probe=547be2fb61) | Feb 19, 2022 |
| Dell          | 0X4N41 A01                  | [a62eea5e4e](https://bsd-hardware.info/?probe=a62eea5e4e) | Feb 11, 2022 |
| Dell          | 0X4N41 A01                  | [55b7348a0c](https://bsd-hardware.info/?probe=55b7348a0c) | Feb 11, 2022 |
| PC Engines    | APU2                        | [566948b2c1](https://bsd-hardware.info/?probe=566948b2c1) | Feb 09, 2022 |
| Acer          | Aspire XC-885 V:1.1         | [76fadb9527](https://bsd-hardware.info/?probe=76fadb9527) | Feb 09, 2022 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [c2b43efb8f](https://bsd-hardware.info/?probe=c2b43efb8f) | Feb 07, 2022 |
| HP            | ProLiant ML350p Gen8        | [7987f643d7](https://bsd-hardware.info/?probe=7987f643d7) | Feb 06, 2022 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [1878f5822c](https://bsd-hardware.info/?probe=1878f5822c) | Feb 06, 2022 |
| HP            | ProLiant ML350p Gen8        | [b9e0021bfb](https://bsd-hardware.info/?probe=b9e0021bfb) | Feb 06, 2022 |
| Unknown       | Unknown                     | [000331f38e](https://bsd-hardware.info/?probe=000331f38e) | Jan 31, 2022 |
| Unknown       | Unknown                     | [74b8fc0269](https://bsd-hardware.info/?probe=74b8fc0269) | Jan 30, 2022 |
| PC Engines    | apu4                        | [4f6a1c9c9a](https://bsd-hardware.info/?probe=4f6a1c9c9a) | Jan 25, 2022 |
| Unknown       | Unknown                     | [b572e30460](https://bsd-hardware.info/?probe=b572e30460) | Jan 19, 2022 |
| HP            | 3396                        | [236ed20a86](https://bsd-hardware.info/?probe=236ed20a86) | Jan 11, 2022 |
| Unknown       | Unknown                     | [e38915ac8c](https://bsd-hardware.info/?probe=e38915ac8c) | Jan 08, 2022 |
| Unknown       | Unknown                     | [0a82e095ee](https://bsd-hardware.info/?probe=0a82e095ee) | Jan 08, 2022 |
| Unknown       | Unknown                     | [9c67eb6ecd](https://bsd-hardware.info/?probe=9c67eb6ecd) | Dec 30, 2021 |
| Gigabyte      | H97N-WIFI                   | [3ccd5eace4](https://bsd-hardware.info/?probe=3ccd5eace4) | Dec 15, 2021 |
| ASRock        | B550 Taichi                 | [ed2fd72332](https://bsd-hardware.info/?probe=ed2fd72332) | Dec 14, 2021 |
| PC Engines    | apu4                        | [a06765ebb1](https://bsd-hardware.info/?probe=a06765ebb1) | Dec 09, 2021 |
| Dell          | 0X4N41 A01                  | [015319ce8c](https://bsd-hardware.info/?probe=015319ce8c) | Dec 08, 2021 |
| Supermicro    | X11SDW-4C-TP13F             | [f424260bfa](https://bsd-hardware.info/?probe=f424260bfa) | Dec 03, 2021 |
| ASRockRack    | X570D4U-2L2T                | [b35a4b529c](https://bsd-hardware.info/?probe=b35a4b529c) | Nov 22, 2021 |
| Intel         | HURONRIVER                  | [741fd0e126](https://bsd-hardware.info/?probe=741fd0e126) | Nov 13, 2021 |
| Dell          | 0X4N41 A01                  | [d08d7fde4a](https://bsd-hardware.info/?probe=d08d7fde4a) | Nov 13, 2021 |
| PC Engines    | apu4                        | [64cad2ccf6](https://bsd-hardware.info/?probe=64cad2ccf6) | Nov 08, 2021 |
| HP            | 3397                        | [3434fa8427](https://bsd-hardware.info/?probe=3434fa8427) | Nov 07, 2021 |
| HP            | 3397                        | [155eceb394](https://bsd-hardware.info/?probe=155eceb394) | Nov 07, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | [15d56aee58](https://bsd-hardware.info/?probe=15d56aee58) | Oct 21, 2021 |
| Apple         | Mac-F221BEC8                | [cb2cc35e6c](https://bsd-hardware.info/?probe=cb2cc35e6c) | Oct 19, 2021 |
| Apple         | Mac-F221BEC8                | [4e91fa71b2](https://bsd-hardware.info/?probe=4e91fa71b2) | Oct 19, 2021 |
| Unknown       | Unknown                     | [734ec7d9fc](https://bsd-hardware.info/?probe=734ec7d9fc) | Oct 18, 2021 |
| Unknown       | Unknown                     | [4ecab88e78](https://bsd-hardware.info/?probe=4ecab88e78) | Oct 17, 2021 |
| ASRock        | A320M-ITX                   | [06a8c0d2ac](https://bsd-hardware.info/?probe=06a8c0d2ac) | Oct 08, 2021 |
| ASRock        | B550 Taichi                 | [7599775c70](https://bsd-hardware.info/?probe=7599775c70) | Oct 08, 2021 |
| PC Engines    | APU2                        | [7a21594bf7](https://bsd-hardware.info/?probe=7a21594bf7) | Oct 08, 2021 |
| PC Engines    | apu6                        | [a184c5f1b2](https://bsd-hardware.info/?probe=a184c5f1b2) | Oct 06, 2021 |
| PC Engines    | APU2                        | [d36e631149](https://bsd-hardware.info/?probe=d36e631149) | Oct 03, 2021 |
| Gigabyte      | B450M DS3H-CF               | [1038e3314d](https://bsd-hardware.info/?probe=1038e3314d) | Sep 21, 2021 |
| PC Engines    | apu4                        | [9557835b54](https://bsd-hardware.info/?probe=9557835b54) | Sep 09, 2021 |
| Gigabyte      | BRi3(H)-10110               | [9aa3540749](https://bsd-hardware.info/?probe=9aa3540749) | Sep 09, 2021 |
| Gigabyte      | X399 DESIGNARE EX-CF        | [a78cc6a11b](https://bsd-hardware.info/?probe=a78cc6a11b) | Sep 04, 2021 |
| ASRock        | A320M-ITX                   | [051ca0708f](https://bsd-hardware.info/?probe=051ca0708f) | Sep 03, 2021 |
| ASRock        | A320M-ITX                   | [23bccfa11c](https://bsd-hardware.info/?probe=23bccfa11c) | Sep 01, 2021 |
| ASUSTek       | P8Z77-V                     | [eb4948e855](https://bsd-hardware.info/?probe=eb4948e855) | Aug 31, 2021 |
| Unknown       | Unknown                     | [114a632ab4](https://bsd-hardware.info/?probe=114a632ab4) | Aug 30, 2021 |
| ASRock        | A320M-ITX                   | [b0339f73bc](https://bsd-hardware.info/?probe=b0339f73bc) | Aug 28, 2021 |
| Unknown       | Unknown                     | [5bb434cb3f](https://bsd-hardware.info/?probe=5bb434cb3f) | Aug 27, 2021 |
| ASRock        | A320M-ITX                   | [c28bfd784d](https://bsd-hardware.info/?probe=c28bfd784d) | Aug 27, 2021 |
| Supermicro    | X9SCL/X9SCMA                | [47284b4819](https://bsd-hardware.info/?probe=47284b4819) | Aug 27, 2021 |
| PC Engines    | apu4                        | [9f5ec6c23f](https://bsd-hardware.info/?probe=9f5ec6c23f) | Aug 23, 2021 |
| PC Engines    | apu4                        | [514a974f68](https://bsd-hardware.info/?probe=514a974f68) | Aug 10, 2021 |
| PC Engines    | APU2                        | [823fdc32f0](https://bsd-hardware.info/?probe=823fdc32f0) | Aug 09, 2021 |
| ASRock        | J4105-ITX                   | [1ac35fcecf](https://bsd-hardware.info/?probe=1ac35fcecf) | Aug 08, 2021 |
| Shuttle       | DS10U                       | [fa151322fc](https://bsd-hardware.info/?probe=fa151322fc) | Aug 03, 2021 |
| Supermicro    | X9SCL/X9SCMA                | [772a9416ab](https://bsd-hardware.info/?probe=772a9416ab) | Aug 01, 2021 |
| PC Engines    | APU2                        | [4c2b89d2e6](https://bsd-hardware.info/?probe=4c2b89d2e6) | Jul 31, 2021 |
| Dell          | 0X4N41 A01                  | [a528966ab8](https://bsd-hardware.info/?probe=a528966ab8) | Jul 30, 2021 |
| Dell          | 0X4N41 A01                  | [51136572fc](https://bsd-hardware.info/?probe=51136572fc) | Jul 29, 2021 |
| ASRockRack    | X470D4U2-2T                 | [8a2efd6b5b](https://bsd-hardware.info/?probe=8a2efd6b5b) | Jul 25, 2021 |
| Supermicro    | X9SCL/X9SCMA                | [fea747e9eb](https://bsd-hardware.info/?probe=fea747e9eb) | Jul 25, 2021 |
| Dell          | 0X4N41 A01                  | [f29fab4508](https://bsd-hardware.info/?probe=f29fab4508) | Jul 23, 2021 |
| Dell          | 0X4N41 A01                  | [b7c3a2b2e4](https://bsd-hardware.info/?probe=b7c3a2b2e4) | Jul 23, 2021 |
| Supermicro    | X9SCL/X9SCMA                | [89938d9a3a](https://bsd-hardware.info/?probe=89938d9a3a) | Jul 20, 2021 |
| Supermicro    | X9SCL/X9SCMA                | [c2721a852b](https://bsd-hardware.info/?probe=c2721a852b) | Jul 18, 2021 |
| Supermicro    | PDSML+                      | [f8a9ca42d6](https://bsd-hardware.info/?probe=f8a9ca42d6) | Jul 11, 2021 |
| PC Engines    | APU2                        | [fe77a10950](https://bsd-hardware.info/?probe=fe77a10950) | Jul 08, 2021 |
| Protectli     | FW6                         | [c28479f624](https://bsd-hardware.info/?probe=c28479f624) | Jun 20, 2021 |
| ASRockRack    | X470D4U2-2T                 | [6efb43e299](https://bsd-hardware.info/?probe=6efb43e299) | Jun 18, 2021 |
| Protectli     | FW6                         | [36d53d9465](https://bsd-hardware.info/?probe=36d53d9465) | Jun 17, 2021 |
| Protectli     | FW6                         | [9579e972f2](https://bsd-hardware.info/?probe=9579e972f2) | Jun 13, 2021 |
| ASUSTek       | ROG STRIX Z370-I GAMING     | [15ba8e73e1](https://bsd-hardware.info/?probe=15ba8e73e1) | Jun 09, 2021 |
| PC Engines    | apu4                        | [7ffaed1505](https://bsd-hardware.info/?probe=7ffaed1505) | Jun 06, 2021 |
| HPE           | ProLiant MicroServer Gen... | [74f5dbcf1b](https://bsd-hardware.info/?probe=74f5dbcf1b) | Jun 01, 2021 |
| PC Engines    | apu4                        | [aad3e6a309](https://bsd-hardware.info/?probe=aad3e6a309) | May 28, 2021 |
| Shuttle       | DS10U                       | [bd8bea4a6a](https://bsd-hardware.info/?probe=bd8bea4a6a) | May 27, 2021 |
| ASRock        | X99M Extreme4               | [ef131c774d](https://bsd-hardware.info/?probe=ef131c774d) | May 02, 2021 |
| Lenovo        | 318E NOK                    | [115f2c7b35](https://bsd-hardware.info/?probe=115f2c7b35) | Apr 27, 2021 |
| Unknown       | Unknown                     | [44e10ac014](https://bsd-hardware.info/?probe=44e10ac014) | Apr 19, 2021 |
| PC Engines    | APU2                        | [8b425e6086](https://bsd-hardware.info/?probe=8b425e6086) | Apr 08, 2021 |
| PC Engines    | APU2                        | [f261049b51](https://bsd-hardware.info/?probe=f261049b51) | Apr 07, 2021 |
| Unknown       | Unknown                     | [09e3c55edf](https://bsd-hardware.info/?probe=09e3c55edf) | Mar 26, 2021 |
| PC Engines    | APU2                        | [6204024271](https://bsd-hardware.info/?probe=6204024271) | Mar 24, 2021 |
| PC Engines    | APU2                        | [b39d8ba487](https://bsd-hardware.info/?probe=b39d8ba487) | Mar 24, 2021 |
| HPE           | ProLiant MicroServer Gen... | [40ec36ad78](https://bsd-hardware.info/?probe=40ec36ad78) | Mar 18, 2021 |
| PC Engines    | apu4                        | [e10b5c92e9](https://bsd-hardware.info/?probe=e10b5c92e9) | Mar 16, 2021 |
| Unknown       | Unknown                     | [36f81afd88](https://bsd-hardware.info/?probe=36f81afd88) | Mar 13, 2021 |
| PC Engines    | apu4                        | [9268ee6857](https://bsd-hardware.info/?probe=9268ee6857) | Mar 13, 2021 |
| HPE           | ProLiant MicroServer Gen... | [2c0b0d8eb0](https://bsd-hardware.info/?probe=2c0b0d8eb0) | Mar 09, 2021 |
| BESSTAR Te... | IB9                         | [6d455b5e28](https://bsd-hardware.info/?probe=6d455b5e28) | Mar 08, 2021 |
| PC Engines    | APU3                        | [cf397191d2](https://bsd-hardware.info/?probe=cf397191d2) | Mar 04, 2021 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [eb8428d5f3](https://bsd-hardware.info/?probe=eb8428d5f3) | Mar 01, 2021 |
| PC Engines    | APU2                        | [2ac1695054](https://bsd-hardware.info/?probe=2ac1695054) | Feb 28, 2021 |
| Unknown       | Unknown                     | [b6c6031b46](https://bsd-hardware.info/?probe=b6c6031b46) | Feb 27, 2021 |
| ASUSTek       | Z170-K                      | [aa525de283](https://bsd-hardware.info/?probe=aa525de283) | Feb 13, 2021 |
| Unknown       | Unknown                     | [ad3998234a](https://bsd-hardware.info/?probe=ad3998234a) | Feb 11, 2021 |
| PC Engines    | APU2                        | [836a3035f1](https://bsd-hardware.info/?probe=836a3035f1) | Feb 06, 2021 |
| PC Engines    | APU2                        | [4985fa31bf](https://bsd-hardware.info/?probe=4985fa31bf) | Feb 03, 2021 |
| PC Engines    | apu4                        | [c740c17c50](https://bsd-hardware.info/?probe=c740c17c50) | Feb 01, 2021 |
| YANYU         | D19SL_B                     | [d16128eed9](https://bsd-hardware.info/?probe=d16128eed9) | Jan 28, 2021 |
| Unknown       | Unknown                     | [d2895512c0](https://bsd-hardware.info/?probe=d2895512c0) | Jan 27, 2021 |
| Unknown       | Unknown                     | [b936d5a273](https://bsd-hardware.info/?probe=b936d5a273) | Jan 27, 2021 |
| PC Engines    | APU2                        | [3448eacd29](https://bsd-hardware.info/?probe=3448eacd29) | Jan 24, 2021 |
| PC Engines    | APU2                        | [72e0243d73](https://bsd-hardware.info/?probe=72e0243d73) | Jan 23, 2021 |
| Sun           | SUNW,Sun-Blade-1500         | [647618a0ca](https://bsd-hardware.info/?probe=647618a0ca) | Jan 22, 2021 |
| PC Engines    | APU2                        | [c6c764813a](https://bsd-hardware.info/?probe=c6c764813a) | Jan 21, 2021 |
| PC Engines    | APU2                        | [bf1b93e96d](https://bsd-hardware.info/?probe=bf1b93e96d) | Jan 21, 2021 |
| ADI Engine... | RCC                         | [199da8eab6](https://bsd-hardware.info/?probe=199da8eab6) | Jan 20, 2021 |
| ASUSTek       | SABERTOOTH Z77              | [c107103d53](https://bsd-hardware.info/?probe=c107103d53) | Jan 19, 2021 |
| Sun           | SUNW,Sun-Blade-100          | [299c76eb85](https://bsd-hardware.info/?probe=299c76eb85) | Jan 18, 2021 |
| HP            | 1495                        | [2606547041](https://bsd-hardware.info/?probe=2606547041) | Dec 22, 2020 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [de35ebc178](https://bsd-hardware.info/?probe=de35ebc178) | Dec 04, 2020 |
| PC Engines    | APU2                        | [e6ee8a14d5](https://bsd-hardware.info/?probe=e6ee8a14d5) | Oct 20, 2020 |
| PC Engines    | apu4                        | [e4cd6d0b48](https://bsd-hardware.info/?probe=e4cd6d0b48) | Oct 19, 2020 |
| HP            | ProLiant MicroServer Gen... | [94a279c84d](https://bsd-hardware.info/?probe=94a279c84d) | Sep 03, 2020 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [840b12f1f9](https://bsd-hardware.info/?probe=840b12f1f9) | Aug 09, 2020 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [c4454eaa39](https://bsd-hardware.info/?probe=c4454eaa39) | Aug 09, 2020 |
| Gigabyte      | H67A-UD3H-B3                | [aa29eb9c75](https://bsd-hardware.info/?probe=aa29eb9c75) | Aug 01, 2020 |
| PC Engines    | apu4                        | [52c611855b](https://bsd-hardware.info/?probe=52c611855b) | Jul 12, 2020 |
| HP            | 158A                        | [dfff5dd2f9](https://bsd-hardware.info/?probe=dfff5dd2f9) | Jun 09, 2020 |
| Unknown       | Unknown                     | [80a1eda96f](https://bsd-hardware.info/?probe=80a1eda96f) | May 28, 2020 |
| ASUSTek       | H81M-C                      | [d65f5372ec](https://bsd-hardware.info/?probe=d65f5372ec) | May 26, 2020 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [b43db1d84e](https://bsd-hardware.info/?probe=b43db1d84e) | May 25, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| OPNsense 22.7    | 7        | 2.54%   |
| OPNsense 21.7.3  | 7        | 2.54%   |
| OPNsense 21.7.1  | 7        | 2.54%   |
| OPNsense 21.1.6  | 7        | 2.54%   |
| OPNsense 20.7.8  | 7        | 2.54%   |
| OPNsense 22.1.8  | 6        | 2.17%   |
| OPNsense 24.7.4  | 5        | 1.81%   |
| OPNsense 24.7.10 | 5        | 1.81%   |
| OPNsense 21.7.6  | 5        | 1.81%   |
| OPNsense 24.7.6  | 4        | 1.45%   |
| OPNsense 24.1.1  | 4        | 1.45%   |
| OPNsense 23.7.10 | 4        | 1.45%   |
| OPNsense 23.1.7  | 4        | 1.45%   |
| OPNsense 23.1.11 | 4        | 1.45%   |
| OPNsense 23.1.1  | 4        | 1.45%   |
| OPNsense 23.1    | 4        | 1.45%   |
| OPNsense 22.7.4  | 4        | 1.45%   |
| OPNsense 22.7.10 | 4        | 1.45%   |
| OPNsense 22.1.6  | 4        | 1.45%   |
| OPNsense 22.1.3  | 4        | 1.45%   |
| OPNsense 21.7.7  | 4        | 1.45%   |
| OPNsense 21.1.3  | 4        | 1.45%   |
| OPNsense 21.1    | 4        | 1.45%   |
| OpenBSD 6.8      | 4        | 1.45%   |
| OPNsense 24.7.9  | 3        | 1.09%   |
| OPNsense 24.7.8  | 3        | 1.09%   |
| OPNsense 24.7.7  | 3        | 1.09%   |
| OPNsense 24.1.7  | 3        | 1.09%   |
| OPNsense 24.1.4  | 3        | 1.09%   |
| OPNsense 24.1.3  | 3        | 1.09%   |
| OPNsense 24.1.2  | 3        | 1.09%   |
| OPNsense 23.7.7  | 3        | 1.09%   |
| OPNsense 23.7.6  | 3        | 1.09%   |
| OPNsense 23.7.1  | 3        | 1.09%   |
| OPNsense 23.1.5  | 3        | 1.09%   |
| OPNsense 22.7.8  | 3        | 1.09%   |
| OPNsense 22.1.7  | 3        | 1.09%   |
| OPNsense 22.1.10 | 3        | 1.09%   |
| OPNsense 22.1.1  | 3        | 1.09%   |
| OPNsense 21.7    | 3        | 1.09%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 155      | 82.01%  |
| FreeBSD     | 14       | 7.41%   |
| OpenBSD     | 12       | 6.35%   |
| helloSystem | 5        | 2.65%   |
| TrueNAS     | 2        | 1.06%   |
| GhostBSD    | 1        | 0.53%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| amd64   | 186      | 98.41%  |
| sparc64 | 2        | 1.06%   |
| i386    | 1        | 0.53%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Console       | 168      | 87.5%   |
| helloDesktop  | 9        | 4.69%   |
| KDE5          | 3        | 1.56%   |
| fvwm          | 3        | 1.56%   |
| LXQt          | 2        | 1.04%   |
| GNOME         | 2        | 1.04%   |
| XFCE          | 1        | 0.52%   |
| MATE          | 1        | 0.52%   |
| i3            | 1        | 0.52%   |
| Enlightenment | 1        | 0.52%   |
| CDE           | 1        | 0.52%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 173      | 91.05%  |
| X11     | 15       | 7.89%   |
| Wayland | 2        | 1.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 177      | 93.16%  |
| SLiM    | 5        | 2.63%   |
| SDDM    | 2        | 1.05%   |
| Ly      | 2        | 1.05%   |
| LightDM | 2        | 1.05%   |
| XDM     | 1        | 0.53%   |
| GDM     | 1        | 0.53%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 166      | 85.57%  |
| C       | 14       | 7.22%   |
| en_US   | 11       | 5.67%   |
| de_DE   | 2        | 1.03%   |
| de_CH   | 1        | 0.52%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 173      | 91.05%  |
| BIOS | 17       | 8.95%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Ufs    | 100      | 52.36%  |
| Zfs    | 78       | 40.84%  |
| Ffs    | 12       | 6.28%   |
| Cd9660 | 1        | 0.52%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 178      | 93.68%  |
| MBR     | 11       | 5.79%   |
| Unknown | 1        | 0.53%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| PC Engines                           | 42       | 22.22%  |
| Unknown                              | 32       | 16.93%  |
| ASUSTek Computer                     | 14       | 7.41%   |
| Hewlett-Packard                      | 11       | 5.82%   |
| Supermicro                           | 9        | 4.76%   |
| Gigabyte Technology                  | 9        | 4.76%   |
| ASRock                               | 9        | 4.76%   |
| Shuttle                              | 8        | 4.23%   |
| Protectli                            | 8        | 4.23%   |
| Dell                                 | 6        | 3.17%   |
| Intel                                | 5        | 2.65%   |
| Techvision                           | 4        | 2.12%   |
| GoWin Solution                       | 4        | 2.12%   |
| Apple                                | 3        | 1.59%   |
| Sun                                  | 2        | 1.06%   |
| Shenzhen Meigao Electronic Equipment | 2        | 1.06%   |
| Lenovo                               | 2        | 1.06%   |
| ASRockRack                           | 2        | 1.06%   |
| Acer                                 | 2        | 1.06%   |
| YANYU                                | 1        | 0.53%   |
| Yanling                              | 1        | 0.53%   |
| Trigkey                              | 1        | 0.53%   |
| Silicom                              | 1        | 0.53%   |
| MW                                   | 1        | 0.53%   |
| LinuxContainers                      | 1        | 0.53%   |
| Intel BOX4A200                       | 1        | 0.53%   |
| Infoblox                             | 1        | 0.53%   |
| IGEL Technology                      | 1        | 0.53%   |
| HPE                                  | 1        | 0.53%   |
| Fujitsu                              | 1        | 0.53%   |
| CWWK                                 | 1        | 0.53%   |
| Biostar                              | 1        | 0.53%   |
| BESSTAR Tech                         | 1        | 0.53%   |
| ADI Engineering                      | 1        | 0.53%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                              | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Unknown                                           | 32       | 16.93%  |
| PC Engines APU2                                   | 22       | 11.64%  |
| PC Engines apu4                                   | 14       | 7.41%   |
| Techvision TVI7309X                               | 4        | 2.12%   |
| Protectli FW6                                     | 3        | 1.59%   |
| PC Engines APU                                    | 3        | 1.59%   |
| GoWin Solution R86S                               | 3        | 1.59%   |
| ASUS All Series                                   | 3        | 1.59%   |
| ASRock A320M-ITX                                  | 3        | 1.59%   |
| Shuttle DS10U                                     | 2        | 1.06%   |
| Shuttle DL30N                                     | 2        | 1.06%   |
| Shenzhen Meigao Electronic Equipment Venus Series | 2        | 1.06%   |
| PC Engines apu6                                   | 2        | 1.06%   |
| HP Compaq 8200 Elite CMT PC                       | 2        | 1.06%   |
| Dell Precision 3440                               | 2        | 1.06%   |
| ASRock B550 Taichi                                | 2        | 1.06%   |
| Apple MacPro5,1                                   | 2        | 1.06%   |
| YANYU D19SL_B                                     | 1        | 0.53%   |
| Yanling YL-KBR6L                                  | 1        | 0.53%   |
| Trigkey Green G5                                  | 1        | 0.53%   |
| Supermicro X9SCL/X9SCM                            | 1        | 0.53%   |
| Supermicro SYS-E300-9D-4CN8TP                     | 1        | 0.53%   |
| Supermicro SYS-E300-9D                            | 1        | 0.53%   |
| Supermicro SYS-5019D-4C-FN8TP                     | 1        | 0.53%   |
| Supermicro SYS-1019D-FHN13TP                      | 1        | 0.53%   |
| Supermicro SYS-1019D-4C-FHN13TP                   | 1        | 0.53%   |
| Supermicro SYS-1019D-16C-RAN13TP+                 | 1        | 0.53%   |
| Supermicro PDSML                                  | 1        | 0.53%   |
| Supermicro AS -5019D-FTN4                         | 1        | 0.53%   |
| Sun SUNW,Sun-Blade-1500                           | 1        | 0.53%   |
| Sun SUNW,Sun-Blade-100                            | 1        | 0.53%   |
| Silicom 80300-0134-g01                            | 1        | 0.53%   |
| Shuttle XH61V                                     | 1        | 0.53%   |
| Shuttle XH310                                     | 1        | 0.53%   |
| Shuttle TERRA_PC                                  | 1        | 0.53%   |
| Shuttle DH110                                     | 1        | 0.53%   |
| Protectli VP6670                                  | 1        | 0.53%   |
| Protectli VP2420                                  | 1        | 0.53%   |
| Protectli VP2410                                  | 1        | 0.53%   |
| Protectli V1410                                   | 1        | 0.53%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Unknown                                    | 32       | 16.93%  |
| PC Engines APU2                            | 22       | 11.64%  |
| PC Engines apu4                            | 14       | 7.41%   |
| HP Compaq                                  | 5        | 2.65%   |
| Techvision TVI7309X                        | 4        | 2.12%   |
| Protectli FW6                              | 3        | 1.59%   |
| PC Engines APU                             | 3        | 1.59%   |
| GoWin Solution R86S                        | 3        | 1.59%   |
| Dell OptiPlex                              | 3        | 1.59%   |
| ASUS TUF                                   | 3        | 1.59%   |
| ASUS All                                   | 3        | 1.59%   |
| ASRock A320M-ITX                           | 3        | 1.59%   |
| Sun SUNW                                   | 2        | 1.06%   |
| Shuttle DS10U                              | 2        | 1.06%   |
| Shuttle DL30N                              | 2        | 1.06%   |
| Shenzhen Meigao Electronic Equipment Venus | 2        | 1.06%   |
| PC Engines apu6                            | 2        | 1.06%   |
| HP ProLiant                                | 2        | 1.06%   |
| Dell Precision                             | 2        | 1.06%   |
| ASUS PRIME                                 | 2        | 1.06%   |
| ASRock B550                                | 2        | 1.06%   |
| Apple MacPro5                              | 2        | 1.06%   |
| Acer Aspire                                | 2        | 1.06%   |
| YANYU D19SL                                | 1        | 0.53%   |
| Yanling YL-KBR6L                           | 1        | 0.53%   |
| Trigkey Green                              | 1        | 0.53%   |
| Supermicro X9SCL                           | 1        | 0.53%   |
| Supermicro SYS-E300-9D-4CN8TP              | 1        | 0.53%   |
| Supermicro SYS-E300-9D                     | 1        | 0.53%   |
| Supermicro SYS-5019D-4C-FN8TP              | 1        | 0.53%   |
| Supermicro SYS-1019D-FHN13TP               | 1        | 0.53%   |
| Supermicro SYS-1019D-4C-FHN13TP            | 1        | 0.53%   |
| Supermicro SYS-1019D-16C-RAN13TP+          | 1        | 0.53%   |
| Supermicro PDSML                           | 1        | 0.53%   |
| Supermicro AS                              | 1        | 0.53%   |
| Silicom 80300-0134-g01                     | 1        | 0.53%   |
| Shuttle XH61V                              | 1        | 0.53%   |
| Shuttle XH310                              | 1        | 0.53%   |
| Shuttle TERRA                              | 1        | 0.53%   |
| Shuttle DH110                              | 1        | 0.53%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 27       | 14.29%  |
| 2016    | 26       | 13.76%  |
| 2022    | 22       | 11.64%  |
| 2020    | 19       | 10.05%  |
| 2023    | 17       | 8.99%   |
| 2012    | 12       | 6.35%   |
| 2021    | 11       | 5.82%   |
| 2019    | 10       | 5.29%   |
| 2017    | 9        | 4.76%   |
| 2024    | 7        | 3.7%    |
| 2014    | 7        | 3.7%    |
| 2015    | 6        | 3.17%   |
| 2013    | 5        | 2.65%   |
| 2011    | 4        | 2.12%   |
| Unknown | 3        | 1.59%   |
| 2008    | 2        | 1.06%   |
| 2010    | 1        | 0.53%   |
| 2007    | 1        | 0.53%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 189      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 142      | 75.13%  |
| Yes  | 47       | 24.87%  |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 53       | 27.32%  |
| 4.01-8.0    | 47       | 24.23%  |
| 8.01-16.0   | 45       | 23.2%   |
| 32.01-64.0  | 30       | 15.46%  |
| 64.01-256.0 | 11       | 5.67%   |
| 2.01-3.0    | 4        | 2.06%   |
| 1.01-2.0    | 2        | 1.03%   |
| 0.01-0.5    | 1        | 0.52%   |
| Unknown     | 1        | 0.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 78       | 38.81%  |
| 0.51-1.0   | 66       | 32.84%  |
| 1.01-2.0   | 30       | 14.93%  |
| 2.01-3.0   | 14       | 6.97%   |
| 4.01-8.0   | 4        | 1.99%   |
| 3.01-4.0   | 3        | 1.49%   |
| 8.01-16.0  | 2        | 1%      |
| 0          | 2        | 1%      |
| 16.01-24.0 | 1        | 0.5%    |
| Unknown    | 1        | 0.5%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 127      | 65.46%  |
| 0      | 35       | 18.04%  |
| 2      | 11       | 5.67%   |
| 4      | 6        | 3.09%   |
| 3      | 5        | 2.58%   |
| 6      | 3        | 1.55%   |
| 5      | 3        | 1.55%   |
| 17     | 1        | 0.52%   |
| 16     | 1        | 0.52%   |
| 8      | 1        | 0.52%   |
| 7      | 1        | 0.52%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 168      | 88.42%  |
| Yes       | 22       | 11.58%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 188      | 99.47%  |
| No        | 1        | 0.53%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 159      | 83.25%  |
| Yes       | 32       | 16.75%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 167      | 87.89%  |
| Yes       | 23       | 12.11%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Switzerland | 189      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Zurich                             | 40       | 18.02%  |
| Winterthur                         | 8        | 3.6%    |
| Lausanne                           | 7        | 3.15%   |
| Geneva                             | 7        | 3.15%   |
| Gachnang                           | 6        | 2.7%    |
| Bern                               | 6        | 2.7%    |
| Gordola                            | 5        | 2.25%   |
| Basel                              | 4        | 1.8%    |
| St. Moritz                         | 3        | 1.35%   |
| St. Gallen                         | 3        | 1.35%   |
| Lucerne                            | 3        | 1.35%   |
| Lenzburg                           | 3        | 1.35%   |
| Horgen                             | 3        | 1.35%   |
| Dietikon                           | 3        | 1.35%   |
| Zug                                | 2        | 0.9%    |
| Tagelswangen                       | 2        | 0.9%    |
| Siggenthal Station                 | 2        | 0.9%    |
| Riehen                             | 2        | 0.9%    |
| Palezieux                          | 2        | 0.9%    |
| Ottenbach                          | 2        | 0.9%    |
| Oensingen                          | 2        | 0.9%    |
| Niederbipp                         | 2        | 0.9%    |
| Mohlin                             | 2        | 0.9%    |
| Mettmenstetten                     | 2        | 0.9%    |
| Maennedorf                         | 2        | 0.9%    |
| Kolliken                           | 2        | 0.9%    |
| Gerlafingen                        | 2        | 0.9%    |
| Dielsdorf                          | 2        | 0.9%    |
| Burgdorf                           | 2        | 0.9%    |
| Biel/Bienne                        | 2        | 0.9%    |
| Belp                               | 2        | 0.9%    |
| Zuzwil                             | 1        | 0.45%   |
| Zuben                              | 1        | 0.45%   |
| Yverdon-les-Bains                  | 1        | 0.45%   |
| Yens                               | 1        | 0.45%   |
| Worblaufen                         | 1        | 0.45%   |
| Wohlen                             | 1        | 0.45%   |
| Willisau                           | 1        | 0.45%   |
| Wiesendangen / Wiesendangen (Dorf) | 1        | 0.45%   |
| Wetzikon                           | 1        | 0.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 45       | 77     | 24.73%  |
| WDC                 | 18       | 51     | 9.89%   |
| Kingston            | 16       | 21     | 8.79%   |
| Phison              | 15       | 19     | 8.24%   |
| China               | 12       | 15     | 6.59%   |
| Seagate             | 9        | 15     | 4.95%   |
| Crucial             | 8        | 16     | 4.4%    |
| Intel               | 6        | 22     | 3.3%    |
| Hoodisk             | 5        | 8      | 2.75%   |
| Corsair             | 5        | 8      | 2.75%   |
| Transcend           | 3        | 3      | 1.65%   |
| Toshiba             | 3        | 4      | 1.65%   |
| SK hynix            | 3        | 3      | 1.65%   |
| ShiJi               | 3        | 10     | 1.65%   |
| SanDisk             | 3        | 9      | 1.65%   |
| HPT                 | 3        | 35     | 1.65%   |
| Hitachi             | 3        | 3      | 1.65%   |
| Fanxiang            | 3        | 3      | 1.65%   |
| Silicon Motion      | 2        | 2      | 1.1%    |
| Protectli           | 2        | 2      | 1.1%    |
| FORESEE             | 2        | 3      | 1.1%    |
| A-DATA Technology   | 2        | 2      | 1.1%    |
| SPCC                | 1        | 2      | 0.55%   |
| QEMU                | 1        | 1      | 0.55%   |
| PNY                 | 1        | 1      | 0.55%   |
| OPENBSD             | 1        | 1      | 0.55%   |
| Micron Technology   | 1        | 2      | 0.55%   |
| KingSpec            | 1        | 1      | 0.55%   |
| Intenso             | 1        | 5      | 0.55%   |
| Hewlett-Packard     | 1        | 15     | 0.55%   |
| CWdisk              | 1        | 2      | 0.55%   |
| BIWIN               | 1        | 1      | 0.55%   |
| Apple               | 1        | 1      | 0.55%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Phison SATA SSD 16GB              | 10       | 4.31%   |
| Samsung SSD 860 EVO 250GB         | 6        | 2.59%   |
| Hoodisk SSD 32GB                  | 5        | 2.16%   |
| China SATA SSD 16GB               | 5        | 2.16%   |
| ShiJi SSD 128GB                   | 3        | 1.29%   |
| Samsung SSD 860 PRO 256GB         | 3        | 1.29%   |
| Samsung SSD 850 PRO 256GB         | 3        | 1.29%   |
| Phison SATA SSD 32GB              | 3        | 1.29%   |
| Kingston RBUSNS8180DS3128GH 128GB | 3        | 1.29%   |
| HPT DISK 0_3 1TB                  | 3        | 1.29%   |
| HPT DISK 0_2 1TB                  | 3        | 1.29%   |
| HPT DISK 0_1 1TB                  | 3        | 1.29%   |
| HPT DISK 0_0 4TB                  | 3        | 1.29%   |
| Fanxiang S501 128GB               | 3        | 1.29%   |
| China SATA SSD 32GB               | 3        | 1.29%   |
| WDC WD6002FRYZ-01WD5B1 6TB        | 2        | 0.86%   |
| WDC WD40EFPX-68C6CN0 4TB          | 2        | 0.86%   |
| WDC WD30EFRX-68EUZN0 3TB          | 2        | 0.86%   |
| WDC WD1000DHTZ-04N21V0 1TB        | 2        | 0.86%   |
| SK hynix SC311 SATA 256GB         | 2        | 0.86%   |
| Seagate ST3500413AS 500GB         | 2        | 0.86%   |
| Samsung SSD 980 PRO 250GB         | 2        | 0.86%   |
| Samsung SSD 970 EVO Plus 1TB      | 2        | 0.86%   |
| Samsung SSD 960 EVO 250GB         | 2        | 0.86%   |
| Samsung SSD 850 PRO 1TB           | 2        | 0.86%   |
| Samsung SSD 840 Series 120GB      | 2        | 0.86%   |
| Phison YSO256GTLCW-E3C-2 256GB    | 2        | 0.86%   |
| Kingston SKC600MS512G 512GB       | 2        | 0.86%   |
| Kingston SA400M8120G 120GB        | 2        | 0.86%   |
| HPT DISK 0_9 3TB                  | 2        | 0.86%   |
| HPT DISK 0_8 3TB                  | 2        | 0.86%   |
| HPT DISK 0_7 1TB                  | 2        | 0.86%   |
| HPT DISK 0_6 1TB                  | 2        | 0.86%   |
| HPT DISK 0_5 1TB                  | 2        | 0.86%   |
| HPT DISK 0_4 1TB                  | 2        | 0.86%   |
| HPT DISK 0_14 3TB                 | 2        | 0.86%   |
| HPT DISK 0_13 2TB                 | 2        | 0.86%   |
| HPT DISK 0_12 1TB                 | 2        | 0.86%   |
| HPT DISK 0_11 1TB                 | 2        | 0.86%   |
| HPT DISK 0_10 1TB                 | 2        | 0.86%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 10       | 38     | 30.3%   |
| Seagate             | 9        | 15     | 27.27%  |
| HPT                 | 3        | 35     | 9.09%   |
| Hitachi             | 3        | 3      | 9.09%   |
| Toshiba             | 2        | 3      | 6.06%   |
| Samsung Electronics | 1        | 1      | 3.03%   |
| QEMU                | 1        | 1      | 3.03%   |
| OPENBSD             | 1        | 1      | 3.03%   |
| Hewlett-Packard     | 1        | 12     | 3.03%   |
| China               | 1        | 1      | 3.03%   |
| Apple               | 1        | 1      | 3.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 32       | 57     | 26.23%  |
| Kingston            | 14       | 16     | 11.48%  |
| Phison              | 13       | 16     | 10.66%  |
| China               | 11       | 14     | 9.02%   |
| Crucial             | 7        | 15     | 5.74%   |
| Intel               | 6        | 22     | 4.92%   |
| WDC                 | 5        | 8      | 4.1%    |
| Hoodisk             | 5        | 8      | 4.1%    |
| Corsair             | 4        | 7      | 3.28%   |
| Transcend           | 3        | 3      | 2.46%   |
| SK hynix            | 3        | 3      | 2.46%   |
| ShiJi               | 3        | 10     | 2.46%   |
| SanDisk             | 3        | 9      | 2.46%   |
| Protectli           | 2        | 2      | 1.64%   |
| A-DATA Technology   | 2        | 2      | 1.64%   |
| Toshiba             | 1        | 1      | 0.82%   |
| SPCC                | 1        | 2      | 0.82%   |
| PNY                 | 1        | 1      | 0.82%   |
| Micron Technology   | 1        | 2      | 0.82%   |
| KingSpec            | 1        | 1      | 0.82%   |
| Intenso             | 1        | 5      | 0.82%   |
| Hewlett-Packard     | 1        | 3      | 0.82%   |
| FORESEE             | 1        | 1      | 0.82%   |
| BIWIN               | 1        | 1      | 0.82%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 116      | 209    | 67.84%  |
| NVMe | 31       | 43     | 18.13%  |
| HDD  | 24       | 111    | 14.04%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 126      | 320    | 80.25%  |
| NVMe | 31       | 43     | 19.75%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 117      | 210    | 74.52%  |
| 0.51-1.0   | 15       | 58     | 9.55%   |
| 1.01-2.0   | 9        | 18     | 5.73%   |
| 3.01-4.0   | 7        | 9      | 4.46%   |
| 2.01-3.0   | 5        | 13     | 3.18%   |
| 4.01-10.0  | 4        | 12     | 2.55%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 92       | 46.94%  |
| 1-20       | 27       | 13.78%  |
| 251-500    | 23       | 11.73%  |
| 51-100     | 20       | 10.2%   |
| 21-50      | 17       | 8.67%   |
| 501-1000   | 12       | 6.12%   |
| 1001-2000  | 4        | 2.04%   |
| 2001-3000  | 1        | 0.51%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 179      | 89.95%  |
| 21-50   | 11       | 5.53%   |
| 51-100  | 6        | 3.02%   |
| 251-500 | 2        | 1.01%   |
| 101-250 | 1        | 0.5%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                     | Desktops | Drives | Percent |
|-------------------------------------------|----------|--------|---------|
| Seagate ST3500413AS 500GB                 | 2        | 3      | 9.52%   |
| WDC WDS120G2G0A-00JH30 120GB              | 1        | 2      | 4.76%   |
| WDC WD6002FRYZ-01WD5B1 6TB                | 1        | 6      | 4.76%   |
| WDC WD40EFRX-68WT0N0 4TB                  | 1        | 1      | 4.76%   |
| WDC WD30EFRX-68EUZN0 3TB                  | 1        | 1      | 4.76%   |
| WDC WD2002FYPS-01U1B0 2TB                 | 1        | 3      | 4.76%   |
| Toshiba MK1059GSM 1TB                     | 1        | 1      | 4.76%   |
| Seagate ST3500418AS 500GB                 | 1        | 2      | 4.76%   |
| Seagate ST2000VN004-2E4164 2TB            | 1        | 2      | 4.76%   |
| Samsung Electronics SSD 850 EVO mSATA 1TB | 1        | 1      | 4.76%   |
| Samsung Electronics HD204UI 2TB           | 1        | 1      | 4.76%   |
| Kingston SV300S37A120G 120GB              | 1        | 1      | 4.76%   |
| Intel SSDSC2CT240A4 240GB                 | 1        | 1      | 4.76%   |
| Intel SSDSC2BW240A4 240GB                 | 1        | 2      | 4.76%   |
| Intel SSDSA2M160G2GC 160GB                | 1        | 2      | 4.76%   |
| Intel SSDSA2BW160G3H 160GB                | 1        | 5      | 4.76%   |
| Hitachi HDS721050CLA660 500GB             | 1        | 1      | 4.76%   |
| Crucial CT256MX100SSD1 256GB              | 1        | 2      | 4.76%   |
| Corsair Force 3 SSD 120GB                 | 1        | 2      | 4.76%   |
| Corsair CSSD-F120GB2                      | 1        | 2      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 4        | 13     | 21.05%  |
| Intel               | 4        | 10     | 21.05%  |
| Seagate             | 3        | 7      | 15.79%  |
| Samsung Electronics | 2        | 2      | 10.53%  |
| Corsair             | 2        | 4      | 10.53%  |
| Toshiba             | 1        | 1      | 5.26%   |
| Kingston            | 1        | 1      | 5.26%   |
| Hitachi             | 1        | 1      | 5.26%   |
| Crucial             | 1        | 2      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 3        | 11     | 33.33%  |
| Seagate             | 3        | 7      | 33.33%  |
| Toshiba             | 1        | 1      | 11.11%  |
| Samsung Electronics | 1        | 1      | 11.11%  |
| Hitachi             | 1        | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 10       | 20     | 58.82%  |
| HDD  | 7        | 21     | 41.18%  |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 141      | 276    | 85.98%  |
| Malfunc  | 16       | 41     | 9.76%   |
| Detected | 7        | 46     | 4.27%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 111      | 46.25%  |
| AMD                          | 65       | 27.08%  |
| Samsung Electronics          | 17       | 7.08%   |
| Silicon Motion               | 9        | 3.75%   |
| SanDisk                      | 6        | 2.5%    |
| Kingston Technology Company  | 6        | 2.5%    |
| ASMedia Technology           | 4        | 1.67%   |
| Phison Electronics           | 3        | 1.25%   |
| HighPoint Technologies       | 3        | 1.25%   |
| ULi Electronics              | 2        | 0.83%   |
| MAXIO Technology (Hangzhou)  | 2        | 0.83%   |
| Marvell Technology Group     | 2        | 0.83%   |
| JMicron Technology           | 2        | 0.83%   |
| Toshiba                      | 1        | 0.42%   |
| Shenzhen Longsys Electronics | 1        | 0.42%   |
| Red Hat                      | 1        | 0.42%   |
| Micron/Crucial Technology    | 1        | 0.42%   |
| Micron Technology            | 1        | 0.42%   |
| Hewlett-Packard              | 1        | 0.42%   |
| Chelsio Communications       | 1        | 0.42%   |
| Broadcom / LSI               | 1        | 0.42%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 40       | 15.04%  |
| AMD FCH SATA Controller [IDE mode]                                             | 11       | 4.14%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 9        | 3.38%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 9        | 3.38%   |
| Intel Alder Lake-N SATA AHCI Controller                                        | 8        | 3.01%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 8        | 3.01%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7        | 2.63%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 7        | 2.63%   |
| AMD 500 Series Chipset SATA Controller                                         | 7        | 2.63%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 6        | 2.26%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6        | 2.26%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 6        | 2.26%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                  | 6        | 2.26%   |
| Intel Atom Processor C3000 Series SATA Controller 1                            | 6        | 2.26%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6        | 2.26%   |
| Intel Comet Lake SATA AHCI Controller                                          | 5        | 1.88%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4        | 1.5%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4        | 1.5%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 4        | 1.5%    |
| Intel Atom Processor C3000 Series SATA Controller 0                            | 4        | 1.5%    |
| Intel Alder Lake-P SATA AHCI Controller                                        | 4        | 1.5%    |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 4        | 1.5%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4        | 1.5%    |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                   | 3        | 1.13%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                   | 3        | 1.13%   |
| AMD 400 Series Chipset SATA Controller                                         | 3        | 1.13%   |
| ULi M5229 IDE                                                                  | 2        | 0.75%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 2        | 0.75%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 2        | 0.75%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 2        | 0.75%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 2        | 0.75%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                           | 2        | 0.75%   |
| JMicron JMB58x AHCI SATA controller                                            | 2        | 0.75%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2        | 0.75%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2        | 0.75%   |
| Intel SATA Controller [RAID mode]                                              | 2        | 0.75%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2        | 0.75%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2        | 0.75%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 2        | 0.75%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 2        | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 160      | 67.23%  |
| NVMe | 46       | 19.33%  |
| IDE  | 19       | 7.98%   |
| RAID | 8        | 3.36%   |
| SCSI | 3        | 1.26%   |
| SAS  | 2        | 0.84%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 122      | 64.21%  |
| AMD     | 65       | 34.21%  |
| Unknown | 2        | 1.05%   |
| QEMU    | 1        | 0.53%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD GX-412TC SOC                            | 39       | 20.42%  |
| Intel N100                                  | 7        | 3.66%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 7        | 3.66%   |
| Intel Celeron N5105 @ 2.00GHz               | 5        | 2.62%   |
| Intel Xeon D-2123IT CPU @ 2.20GHz           | 4        | 2.09%   |
| Intel Pentium Silver N6005 @ 2.00GHz        | 4        | 2.09%   |
| Intel Celeron CPU 3865U @ 1.80GHz           | 4        | 2.09%   |
| Intel Atom CPU C3758 @ 2.20GHz              | 4        | 2.09%   |
| Intel Core i3-N305                          | 3        | 1.57%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 3        | 1.57%   |
| AMD G-T40E Processor                        | 3        | 1.57%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 2        | 1.05%   |
| Intel Core i5-8365U CPU @ 1.60GHz           | 2        | 1.05%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 1.05%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 1.05%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 2        | 1.05%   |
| Intel Core i5-10500 CPU @ 3.10GHz           | 2        | 1.05%   |
| Intel Celeron N5100 @ 1.10GHz               | 2        | 1.05%   |
| Intel 12th Gen Core i5-12600H               | 2        | 1.05%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 2        | 1.05%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 2        | 1.05%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 2        | 1.05%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 2        | 1.05%   |
|                                             | 2        | 1.05%   |
| QEMU pc-q35-9.0                             | 1        | 0.52%   |
| Intel Xeon D-2183IT CPU @ 2.20GHz           | 1        | 0.52%   |
| Intel Xeon D-2146NT CPU @ 2.30GHz           | 1        | 0.52%   |
| Intel Xeon CPU X5550 @ 2.67GHz              | 1        | 0.52%   |
| Intel Xeon CPU X3450 @ 2.67GHz              | 1        | 0.52%   |
| Intel Xeon CPU W3680 @ 3.33GHz              | 1        | 0.52%   |
| Intel Xeon CPU E5630 @ 2.53GHz              | 1        | 0.52%   |
| Intel Xeon CPU E5-2650 v3 @ 2.30GHz         | 1        | 0.52%   |
| Intel Xeon CPU E5-2620 @ 2.00GHz            | 1        | 0.52%   |
| Intel Xeon CPU E5-2609 0 @ 2.40GHz          | 1        | 0.52%   |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz         | 1        | 0.52%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 1        | 0.52%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz         | 1        | 0.52%   |
| Intel Xeon CPU E3-1225 V2 @ 3.20GHz         | 1        | 0.52%   |
| Intel Xeon CPU E3-1220L V2 @ 2.30GHz        | 1        | 0.52%   |
| Intel Xeon CPU E                            | 1        | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| AMD GX                 | 40       | 20.94%  |
| Intel Core i5          | 24       | 12.57%  |
| Intel Celeron          | 24       | 12.57%  |
| Other                  | 19       | 9.95%   |
| Intel Xeon             | 19       | 9.95%   |
| Intel Core i3          | 11       | 5.76%   |
| Intel Core i7          | 10       | 5.24%   |
| Intel Atom             | 9        | 4.71%   |
| AMD Ryzen 7            | 6        | 3.14%   |
| AMD Ryzen 5            | 6        | 3.14%   |
| Intel Pentium Silver   | 4        | 2.09%   |
| Intel Pentium          | 3        | 1.57%   |
| AMD G                  | 3        | 1.57%   |
| Intel Core 2 Duo       | 2        | 1.05%   |
| AMD Ryzen 9            | 2        | 1.05%   |
| AMD Ryzen 7 PRO        | 2        | 1.05%   |
| Intel Pentium Gold     | 1        | 0.52%   |
| AMD Ryzen Threadripper | 1        | 0.52%   |
| AMD Ryzen 3            | 1        | 0.52%   |
| AMD Opteron            | 1        | 0.52%   |
| AMD Geode Integrated   | 1        | 0.52%   |
| AMD FX                 | 1        | 0.52%   |
| AMD EPYC               | 1        | 0.52%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 113      | 58.85%  |
| 2       | 25       | 13.02%  |
| 8       | 22       | 11.46%  |
| 16      | 11       | 5.73%   |
| 12      | 6        | 3.13%   |
| 6       | 6        | 3.13%   |
| 1       | 4        | 2.08%   |
| Unknown | 2        | 1.04%   |
| 32      | 1        | 0.52%   |
| 24      | 1        | 0.52%   |
| 10      | 1        | 0.52%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 184      | 96.84%  |
| 2       | 3        | 1.58%   |
| Unknown | 2        | 1.05%   |
| 4       | 1        | 0.53%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 137      | 72.11%  |
| 2       | 49       | 25.79%  |
| Unknown | 4        | 2.11%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Puma          | 39       | 20.42%  |
| Unknown       | 34       | 17.8%   |
| KabyLake      | 18       | 9.42%   |
| Skylake       | 12       | 6.28%   |
| IvyBridge     | 11       | 5.76%   |
| Haswell       | 11       | 5.76%   |
| Goldmont plus | 9        | 4.71%   |
| Zen 3         | 8        | 4.19%   |
| SandyBridge   | 8        | 4.19%   |
| Goldmont      | 8        | 4.19%   |
| Zen           | 4        | 2.09%   |
| Silvermont    | 4        | 2.09%   |
| Zen+          | 3        | 1.57%   |
| Bobcat        | 3        | 1.57%   |
| Zen 2         | 2        | 1.05%   |
| Westmere      | 2        | 1.05%   |
| TigerLake     | 2        | 1.05%   |
| Nehalem       | 2        | 1.05%   |
| Core          | 2        | 1.05%   |
| CometLake     | 2        | 1.05%   |
| Piledriver    | 1        | 0.52%   |
| Penryn        | 1        | 0.52%   |
| Jaguar        | 1        | 0.52%   |
| IceLake       | 1        | 0.52%   |
| Geode         | 1        | 0.52%   |
| Excavator     | 1        | 0.52%   |
| Broadwell     | 1        | 0.52%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 90       | 62.5%   |
| AMD                                          | 20       | 13.89%  |
| ASPEED Technology                            | 14       | 9.72%   |
| Nvidia                                       | 13       | 9.03%   |
| Matrox Electronics Systems                   | 4        | 2.78%   |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.69%   |
| Red Hat                                      | 1        | 0.69%   |
| 3DLabs                                       | 1        | 0.69%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| ASPEED Technology ASPEED Graphics Family                                    | 14       | 9.52%   |
| Intel JasperLake [UHD Graphics]                                             | 11       | 7.48%   |
| Intel Alder Lake-N [UHD Graphics]                                           | 10       | 6.8%    |
| Intel GeminiLake [UHD Graphics 600]                                         | 9        | 6.12%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 5        | 3.4%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5        | 3.4%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 5        | 3.4%    |
| Intel HD Graphics 610                                                       | 4        | 2.72%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4        | 2.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3        | 2.04%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 3        | 2.04%   |
| Intel HD Graphics 530                                                       | 3        | 2.04%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 3        | 2.04%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 2.04%   |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 2        | 1.36%   |
| Matrox Electronics Systems MGA G200EH                                       | 2        | 1.36%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 2        | 1.36%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 1.36%   |
| Intel HD Graphics 510                                                       | 2        | 1.36%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2        | 1.36%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 1.36%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 2        | 1.36%   |
| Intel Alder Lake-UP3 GT2 [UHD Graphics]                                     | 2        | 1.36%   |
| Intel Alder Lake-P Integrated Graphics Controller                           | 2        | 1.36%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.36%   |
| AMD Raphael                                                                 | 2        | 1.36%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 2        | 1.36%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                        | 2        | 1.36%   |
| XGI Technology (eXtreme Graphics Innovation) Z7/Z9 (XG20 core)              | 1        | 0.68%   |
| Red Hat Virtio 1.0 GPU                                                      | 1        | 0.68%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.68%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 0.68%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 0.68%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 0.68%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 0.68%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 0.68%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 0.68%   |
| Nvidia GK107 [GeForce GT 640 OEM]                                           | 1        | 0.68%   |
| Nvidia GK104 [GeForce GTX 680]                                              | 1        | 0.68%   |
| Nvidia GF119 [GeForce GT 520]                                               | 1        | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 89       | 46.6%   |
| Other          | 47       | 24.61%  |
| 1 x AMD        | 19       | 9.95%   |
| 1 x ASPEED     | 14       | 7.33%   |
| 1 x Nvidia     | 12       | 6.28%   |
| 1 x Matrox     | 4        | 2.09%   |
| 2 x AMD        | 2        | 1.05%   |
| 1 x XGI        | 1        | 0.52%   |
| 1 x Red Hat    | 1        | 0.52%   |
| Intel + Nvidia | 1        | 0.52%   |
| 1 x 3DLabs     | 1        | 0.52%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 129      | 68.25%  |
| Unknown     | 52       | 27.51%  |
| Proprietary | 8        | 4.23%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 177      | 93.16%  |
| 1.01-2.0   | 4        | 2.11%   |
| 3.01-4.0   | 3        | 1.58%   |
| 7.01-8.0   | 2        | 1.05%   |
| 5.01-6.0   | 1        | 0.53%   |
| 2.01-3.0   | 1        | 0.53%   |
| 0.51-1.0   | 1        | 0.53%   |
| 0.01-0.5   | 1        | 0.53%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 2        | 13.33%  |
| Acer                 | 2        | 13.33%  |
| Philips              | 1        | 6.67%   |
| NEC Computers        | 1        | 6.67%   |
| LG Electronics       | 1        | 6.67%   |
| Lenovo               | 1        | 6.67%   |
| Iiyama               | 1        | 6.67%   |
| Hewlett-Packard      | 1        | 6.67%   |
| Fujitsu Siemens      | 1        | 6.67%   |
| Eizo                 | 1        | 6.67%   |
| BenQ                 | 1        | 6.67%   |
| ASUSTek Computer     | 1        | 6.67%   |
| Ancor Communications | 1        | 6.67%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Samsung Electronics U32E850 SAM0CE3 3840x2160 700x390mm 31.5-inch | 1        | 6.25%   |
| Samsung Electronics S27E390 SAM0C1B 1920x1080 600x340mm 27.2-inch | 1        | 6.25%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                | 1        | 6.25%   |
| NEC Computers LCD Monitor EA224WMi 1920x1080                      | 1        | 6.25%   |
| LG Electronics LCD Monitor LG Ultra HD 11520x2160                 | 1        | 6.25%   |
| LG Electronics LCD Monitor LG Ultra HD                            | 1        | 6.25%   |
| Lenovo LEN P27q-10 LEN61A8 2560x1440 600x340mm 27.2-inch          | 1        | 6.25%   |
| Iiyama PL3288UH IVM7610 3840x2160 700x390mm 31.5-inch             | 1        | 6.25%   |
| Hewlett-Packard ZR24w HWP286A 1920x1200 540x350mm 25.3-inch       | 1        | 6.25%   |
| Fujitsu Siemens S19-1 FUS0517 1280x1024 380x300mm 19.1-inch       | 1        | 6.25%   |
| Eizo EV2316W ENC2394 1920x1080 510x290mm 23.1-inch                | 1        | 6.25%   |
| BenQ GW2250H BNQ78BD 1920x1080 480x270mm 21.7-inch                | 1        | 6.25%   |
| ASUSTek Computer XG35V AUS3551 3440x1440 820x350mm 35.1-inch      | 1        | 6.25%   |
| Ancor Communications VS278 ACI27A1 1920x1080 600x340mm 27.2-inch  | 1        | 6.25%   |
| Acer XB271HU ACR0490 2560x1440 600x340mm 27.2-inch                | 1        | 6.25%   |
| Acer XB271HU A ACR052F 2560x1440 600x340mm 27.2-inch              | 1        | 6.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 6        | 37.5%   |
| 2560x1440 (QHD)   | 3        | 18.75%  |
| 3840x2160 (4K)    | 2        | 12.5%   |
| 3440x1440         | 1        | 6.25%   |
| 1920x1200 (WUXGA) | 1        | 6.25%   |
| 1280x1024 (SXGA)  | 1        | 6.25%   |
| 11520x2160        | 1        | 6.25%   |
| Unknown           | 1        | 6.25%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 5        | 33.33%  |
| 31      | 2        | 13.33%  |
| Unknown | 2        | 13.33%  |
| 65      | 1        | 6.67%   |
| 35      | 1        | 6.67%   |
| 25      | 1        | 6.67%   |
| 23      | 1        | 6.67%   |
| 21      | 1        | 6.67%   |
| 19      | 1        | 6.67%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 7        | 46.67%  |
| 601-700     | 2        | 13.33%  |
| Unknown     | 2        | 13.33%  |
| 801-900     | 1        | 6.67%   |
| 401-500     | 1        | 6.67%   |
| 351-400     | 1        | 6.67%   |
| 1001-1500   | 1        | 6.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 10       | 66.67%  |
| Unknown | 2        | 13.33%  |
| 5/4     | 1        | 6.67%   |
| 3/2     | 1        | 6.67%   |
| 21/9    | 1        | 6.67%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 301-350        | 5        | 33.33%  |
| 351-500        | 3        | 20%     |
| 201-250        | 2        | 13.33%  |
| Unknown        | 2        | 13.33%  |
| More than 1000 | 1        | 6.67%   |
| 251-300        | 1        | 6.67%   |
| 151-200        | 1        | 6.67%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 101-120 | 5        | 33.33%  |
| 51-100  | 5        | 33.33%  |
| 121-160 | 2        | 13.33%  |
| Unknown | 2        | 13.33%  |
| 1-50    | 1        | 6.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 175      | 92.11%  |
| 1     | 14       | 7.37%   |
| 2     | 1        | 0.53%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Intel                             | 165      | 66.27%  |
| Realtek Semiconductor             | 39       | 15.66%  |
| Qualcomm Atheros                  | 9        | 3.61%   |
| Broadcom                          | 9        | 3.61%   |
| Mellanox Technologies             | 6        | 2.41%   |
| MediaTek                          | 3        | 1.2%    |
| U-Blox                            | 2        | 0.8%    |
| Huawei Technologies               | 2        | 0.8%    |
| American Megatrends               | 2        | 0.8%    |
| VIA Technologies                  | 1        | 0.4%    |
| Samsung Electronics               | 1        | 0.4%    |
| Red Hat                           | 1        | 0.4%    |
| Qualcomm Atheros Communications   | 1        | 0.4%    |
| QLogic                            | 1        | 0.4%    |
| Oracle/SUN                        | 1        | 0.4%    |
| Microchip Technology              | 1        | 0.4%    |
| Free Software Initiative of Japan | 1        | 0.4%    |
| Edimax Technology                 | 1        | 0.4%    |
| Chelsio Communications            | 1        | 0.4%    |
| Aquantia                          | 1        | 0.4%    |
| 3Com                              | 1        | 0.4%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel I211 Gigabit Network Connection                                         | 40       | 12.08%  |
| Intel I210 Gigabit Network Connection                                         | 32       | 9.67%   |
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 27       | 8.16%   |
| Intel Ethernet Controller I226-V                                              | 22       | 6.65%   |
| Intel Ethernet Controller I225-V                                              | 18       | 5.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 10       | 3.02%   |
| Intel I350 Gigabit Network Connection                                         | 9        | 2.72%   |
| Intel Ethernet Connection X553 10 GbE SFP+                                    | 8        | 2.42%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 7        | 2.11%   |
| Intel 82574L Gigabit Network Connection                                       | 7        | 2.11%   |
| Realtek RTL8125 2.5GbE Controller                                             | 5        | 1.51%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 5        | 1.51%   |
| Intel Ethernet Controller X550                                                | 5        | 1.51%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 5        | 1.51%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 5        | 1.51%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 4        | 1.21%   |
| Mellanox MT27500 Family [ConnectX-3]                                          | 4        | 1.21%   |
| Intel Ethernet Controller I226-LM                                             | 4        | 1.21%   |
| Intel Ethernet Connection I217-LM                                             | 4        | 1.21%   |
| Intel 82583V Gigabit Network Connection                                       | 4        | 1.21%   |
| Intel 82576 Gigabit Network Connection                                        | 4        | 1.21%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4        | 1.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 3        | 0.91%   |
| Intel Wi-Fi 6 AX200                                                           | 3        | 0.91%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 3        | 0.91%   |
| Intel Ethernet Controller E810-XXV for SFP                                    | 3        | 0.91%   |
| Intel 82579V Gigabit Network Connection                                       | 3        | 0.91%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 3        | 0.91%   |
| U-Blox [u-blox 7]                                                             | 2        | 0.6%    |
| Realtek RTL8188EE Wireless Network Adapter                                    | 2        | 0.6%    |
| Intel Wi-Fi 6 AX201 160MHz                                                    | 2        | 0.6%    |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                              | 2        | 0.6%    |
| Intel Ethernet Connection I218-V                                              | 2        | 0.6%    |
| Intel Ethernet Connection (6) I219-LM                                         | 2        | 0.6%    |
| Intel Ethernet Connection (2) I218-V                                          | 2        | 0.6%    |
| Intel Ethernet Connection (11) I219-LM                                        | 2        | 0.6%    |
| Intel 82599 10 Gigabit TN Network Connection                                  | 2        | 0.6%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2        | 0.6%    |
| American Megatrends Virtual Ethernet                                          | 2        | 0.6%    |
| VIA VT6105M [Rhine-III]                                                       | 1        | 0.3%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 11       | 33.33%  |
| Realtek Semiconductor           | 8        | 24.24%  |
| Qualcomm Atheros                | 8        | 24.24%  |
| MediaTek                        | 3        | 9.09%   |
| Qualcomm Atheros Communications | 1        | 3.03%   |
| Edimax Technology               | 1        | 3.03%   |
| Broadcom                        | 1        | 3.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 4        | 12.12%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 3        | 9.09%   |
| Intel Wi-Fi 6 AX200                                            | 3        | 9.09%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2        | 6.06%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 2        | 6.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1        | 3.03%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1        | 3.03%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 1        | 3.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1        | 3.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1        | 3.03%   |
| Qualcomm Atheros AR9271 802.11n                                | 1        | 3.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1        | 3.03%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 1        | 3.03%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter              | 1        | 3.03%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 1        | 3.03%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 1        | 3.03%   |
| Intel Wireless 8265 / 8275                                     | 1        | 3.03%   |
| Intel Wireless 7260                                            | 1        | 3.03%   |
| Intel Wireless 3160                                            | 1        | 3.03%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 1        | 3.03%   |
| Intel CNVi: Wi-Fi                                              | 1        | 3.03%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1        | 3.03%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]       | 1        | 3.03%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 1        | 3.03%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 162      | 76.06%  |
| Realtek Semiconductor  | 33       | 15.49%  |
| Broadcom               | 8        | 3.76%   |
| American Megatrends    | 2        | 0.94%   |
| VIA Technologies       | 1        | 0.47%   |
| Samsung Electronics    | 1        | 0.47%   |
| Qualcomm Atheros       | 1        | 0.47%   |
| QLogic                 | 1        | 0.47%   |
| Oracle/SUN             | 1        | 0.47%   |
| Huawei Technologies    | 1        | 0.47%   |
| Chelsio Communications | 1        | 0.47%   |
| Aquantia               | 1        | 0.47%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel I211 Gigabit Network Connection                                         | 40       | 14.04%  |
| Intel I210 Gigabit Network Connection                                         | 32       | 11.23%  |
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 27       | 9.47%   |
| Intel Ethernet Controller I226-V                                              | 22       | 7.72%   |
| Intel Ethernet Controller I225-V                                              | 18       | 6.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 10       | 3.51%   |
| Intel I350 Gigabit Network Connection                                         | 9        | 3.16%   |
| Intel Ethernet Connection X553 10 GbE SFP+                                    | 8        | 2.81%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 7        | 2.46%   |
| Intel 82574L Gigabit Network Connection                                       | 7        | 2.46%   |
| Realtek RTL8125 2.5GbE Controller                                             | 5        | 1.75%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 5        | 1.75%   |
| Intel Ethernet Controller X550                                                | 5        | 1.75%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 5        | 1.75%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 5        | 1.75%   |
| Intel Ethernet Controller I226-LM                                             | 4        | 1.4%    |
| Intel Ethernet Connection I217-LM                                             | 4        | 1.4%    |
| Intel 82583V Gigabit Network Connection                                       | 4        | 1.4%    |
| Intel 82576 Gigabit Network Connection                                        | 4        | 1.4%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4        | 1.4%    |
| Intel I210 Gigabit Fiber Network Connection                                   | 3        | 1.05%   |
| Intel Ethernet Controller E810-XXV for SFP                                    | 3        | 1.05%   |
| Intel 82579V Gigabit Network Connection                                       | 3        | 1.05%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 3        | 1.05%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                              | 2        | 0.7%    |
| Intel Ethernet Connection I218-V                                              | 2        | 0.7%    |
| Intel Ethernet Connection (6) I219-LM                                         | 2        | 0.7%    |
| Intel Ethernet Connection (2) I218-V                                          | 2        | 0.7%    |
| Intel Ethernet Connection (11) I219-LM                                        | 2        | 0.7%    |
| Intel 82599 10 Gigabit TN Network Connection                                  | 2        | 0.7%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2        | 0.7%    |
| American Megatrends Virtual Ethernet                                          | 2        | 0.7%    |
| VIA VT6105M [Rhine-III]                                                       | 1        | 0.35%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1        | 0.35%   |
| Realtek USB 2.5GbE Controller                                                 | 1        | 0.35%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 1        | 0.35%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1        | 0.35%   |
| QLogic cLOM8214 1/10GbE Controller                                            | 1        | 0.35%   |
| Oracle/SUN RIO 10/100 Ethernet [eri]                                          | 1        | 0.35%   |
| Intel Ethernet Controller X710/X557-AT 10GBASE-T                              | 1        | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 188      | 81.03%  |
| WiFi     | 31       | 13.36%  |
| Unknown  | 9        | 3.88%   |
| Modem    | 4        | 1.72%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 181      | 98.91%  |
| WiFi     | 2        | 1.09%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 4     | 47       | 24.48%  |
| 3     | 43       | 22.4%   |
| 6     | 26       | 13.54%  |
| 5     | 23       | 11.98%  |
| 2     | 18       | 9.38%   |
| 1     | 17       | 8.85%   |
| 8     | 6        | 3.13%   |
| 9     | 4        | 2.08%   |
| 13    | 3        | 1.56%   |
| 7     | 3        | 1.56%   |
| 15    | 1        | 0.52%   |
| 14    | 1        | 0.52%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 150      | 74.63%  |
| Yes  | 51       | 25.37%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 10       | 41.67%  |
| MediaTek                        | 3        | 12.5%   |
| IMC Networks                    | 3        | 12.5%   |
| Realtek Semiconductor           | 2        | 8.33%   |
| Qualcomm Atheros Communications | 2        | 8.33%   |
| ASUSTek Computer                | 2        | 8.33%   |
| Apple                           | 2        | 8.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel AX201 Bluetooth                          | 3        | 12.5%   |
| Intel AX200 Bluetooth                          | 3        | 12.5%   |
| Realtek Bluetooth Adapter                      | 2        | 8.33%   |
| MediaTek Wireless_Device                       | 2        | 8.33%   |
| Intel Bluetooth wireless interface             | 2        | 8.33%   |
| IMC Networks Realtek Bluetooth Adapter         | 2        | 8.33%   |
| Apple Built-in Bluetooth 2.0+EDR HCI           | 2        | 8.33%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0         | 1        | 4.17%   |
| Qualcomm Atheros AR9462 Bluetooth              | 1        | 4.17%   |
| MediaTek RZ608 Bluetooth Adapter               | 1        | 4.17%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 1        | 4.17%   |
| Intel AX210 Bluetooth                          | 1        | 4.17%   |
| IMC Networks Wireless_Device                   | 1        | 4.17%   |
| ASUS Broadcom BCM20702A0 Bluetooth             | 1        | 4.17%   |
| ASUS Bluetooth Controller                      | 1        | 4.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 92       | 70.77%  |
| AMD                   | 23       | 17.69%  |
| Nvidia                | 11       | 8.46%   |
| ULi Electronics       | 2        | 1.54%   |
| Realtek Semiconductor | 1        | 0.77%   |
| Logitech              | 1        | 0.77%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel Jasper Lake HD Audio                                                        | 10       | 6.62%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                        | 10       | 6.62%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 9        | 5.96%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                           | 9        | 5.96%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 8        | 5.3%    |
| AMD Renoir Radeon High Definition Audio Controller                                | 7        | 4.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 6        | 3.97%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 6        | 3.97%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                           | 5        | 3.31%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 5        | 3.31%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 4        | 2.65%   |
| Intel Sunrise Point-LP HD Audio                                                   | 3        | 1.99%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 3        | 1.99%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 3        | 1.99%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 3        | 1.99%   |
| AMD Starship/Matisse HD Audio Controller                                          | 3        | 1.99%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 3        | 1.99%   |
| ULi Electronics M5451 PCI AC-Link Controller Audio Device                         | 2        | 1.32%   |
| Nvidia GK107 HDMI Audio Controller                                                | 2        | 1.32%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 2        | 1.32%   |
| Intel Haswell-ULT HD Audio Controller                                             | 2        | 1.32%   |
| Intel Comet Lake PCH cAVS                                                         | 2        | 1.32%   |
| Intel Cannon Lake PCH cAVS                                                        | 2        | 1.32%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 2        | 1.32%   |
| Intel Alder Lake-S HD Audio Controller                                            | 2        | 1.32%   |
| Intel 8 Series HD Audio Controller                                                | 2        | 1.32%   |
| Intel 200 Series PCH HD Audio                                                     | 2        | 1.32%   |
| AMD Rembrandt Radeon High Definition Audio Controller                             | 2        | 1.32%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 2        | 1.32%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 2        | 1.32%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2        | 1.32%   |
| Realtek Semiconductor USB Audio Maono Elf retrieving string failed                | 1        | 0.66%   |
| Nvidia TU116 High Definition Audio Controller                                     | 1        | 0.66%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 1        | 0.66%   |
| Nvidia GP106 High Definition Audio Controller                                     | 1        | 0.66%   |
| Nvidia GM206 High Definition Audio Controller                                     | 1        | 0.66%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 1        | 0.66%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 1        | 0.66%   |
| Nvidia GK104 HDMI Audio Controller                                                | 1        | 0.66%   |
| Nvidia GF119 HDMI Audio Controller                                                | 1        | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 43       | 23.5%   |
| Unknown             | 29       | 15.85%  |
| Crucial             | 23       | 12.57%  |
| SK hynix            | 20       | 10.93%  |
| Samsung Electronics | 19       | 10.38%  |
| Micron Technology   | 18       | 9.84%   |
| Corsair             | 15       | 8.2%    |
| Nanya Technology    | 3        | 1.64%   |
| Unknown (07FB)      | 2        | 1.09%   |
| Hewlett-Packard     | 2        | 1.09%   |
| G.Skill             | 2        | 1.09%   |
| Unknown (ABCD)      | 1        | 0.55%   |
| Unknown (0x05F7)    | 1        | 0.55%   |
| Transcend           | 1        | 0.55%   |
| tigo                | 1        | 0.55%   |
| Super Talent        | 1        | 0.55%   |
| QEMU                | 1        | 0.55%   |
| Goldenmars          | 1        | 0.55%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                    | 19       | 10.05%  |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s                     | 3        | 1.59%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                    | 3        | 1.59%   |
| SK hynix RAM HMA81GU6CJR8N-XN 8GB DIMM DDR4 3200MT/s           | 3        | 1.59%   |
| Kingston RAM KHX2933C15D4/8GX 8GB DIMM DDR4 2400MT/s           | 3        | 1.59%   |
| Kingston RAM KF2666C15S4/8G 8GB SODIMM DDR4 2667MT/s           | 3        | 1.59%   |
| Kingston RAM CBD24D4S7S8K1A-8 8GB SODIMM DDR4 2400MT/s         | 3        | 1.59%   |
| Crucial RAM CT16G56C46S5.M8G1 16GB SODIMM DDR5 5600MT/s        | 3        | 1.59%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 2        | 1.06%   |
| Micron RAM Module 8GB Row Of Chips LPDDR4 3200MT/s             | 2        | 1.06%   |
| Micron RAM Module 2GB DIMM DDR3 1333MT/s                       | 2        | 1.06%   |
| Micron RAM Module 16GB Row Of Chips LPDDR4 4267MT/s            | 2        | 1.06%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s            | 2        | 1.06%   |
| Kingston RAM 99U5471-052.A00LF 8GB DIMM DDR3 1333MT/s          | 2        | 1.06%   |
| Kingston RAM 9965745-020.A00G 32GB DIMM DDR4 3200MT/s          | 2        | 1.06%   |
| Kingston RAM 9905403-559.A00LF 8GB DIMM DDR3 1333MT/s          | 2        | 1.06%   |
| Crucial RAM CT8G4SFS824A.M8FD 8GB SODIMM DDR4 2400MT/s         | 2        | 1.06%   |
| Crucial RAM CT8G4SFRA32A.M8FR 8GB SODIMM DDR4 3200MT/s         | 2        | 1.06%   |
| Crucial RAM CT8G4DFS8266.M8FJ 8GB DIMM DDR4 2666MT/s           | 2        | 1.06%   |
| Crucial RAM CT8G4DFRA266.C8FB 8GB DIMM DDR4 2666MT/s           | 2        | 1.06%   |
| Crucial RAM CT8G48C40S5.M4A1 8GB SODIMM DDR5 4800MT/s          | 2        | 1.06%   |
| Crucial RAM CT32G48C40S5.M16A1 32GB SODIMM DDR5 4800MT/s       | 2        | 1.06%   |
| Crucial RAM CT16G56C46S5.C8D 16GB SODIMM DDR5 5600MT/s         | 2        | 1.06%   |
| Unknown RAM Module 512MB DIMM DDR2 667MT/s                     | 1        | 0.53%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                        | 1        | 0.53%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2133MT/s | 1        | 0.53%   |
| Unknown (0x05F7) RAM Module 1GB FB-DIMM DDR2 800MT/s           | 1        | 0.53%   |
| Unknown (07FB) RAM GSA8G4SCL196P-26 8GB SODIMM DDR4 2667MT/s   | 1        | 0.53%   |
| Unknown (07FB) RAM GSA8G4SCL176P-24 8GB SODIMM DDR4 2400MT/s   | 1        | 0.53%   |
| Transcend RAM TS512MLK64V6H 4GB DIMM DDR3 1600MT/s             | 1        | 0.53%   |
| tigo RAM 1600Mhz-8G 8GB SODIMM DDR3 1600MT/s                   | 1        | 0.53%   |
| Super Talent RAM SUPERTALENT02 4GB DIMM DDR3 1600MT/s          | 1        | 0.53%   |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                   | 1        | 0.53%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2667MT/s                   | 1        | 0.53%   |
| SK hynix RAM Module 8GB DIMM DDR4 2133MT/s                     | 1        | 0.53%   |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s                     | 1        | 0.53%   |
| SK hynix RAM Module 1GB FB-DIMM DDR2 800MT/s                   | 1        | 0.53%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                  | 1        | 0.53%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s           | 1        | 0.53%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1        | 0.53%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 70       | 42.17%  |
| DDR3    | 67       | 40.36%  |
| DDR5    | 16       | 9.64%   |
| LPDDR4  | 7        | 4.22%   |
| DDR2    | 3        | 1.81%   |
| RAM     | 1        | 0.6%    |
| LPDDR5  | 1        | 0.6%    |
| Unknown | 1        | 0.6%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 79       | 47.88%  |
| SODIMM       | 77       | 46.67%  |
| Row Of Chips | 7        | 4.24%   |
| RIMM         | 1        | 0.61%   |
| FB-DIMM      | 1        | 0.61%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 62       | 36.05%  |
| 4096  | 44       | 25.58%  |
| 16384 | 39       | 22.67%  |
| 32768 | 14       | 8.14%   |
| 2048  | 8        | 4.65%   |
| 1024  | 2        | 1.16%   |
| 65536 | 1        | 0.58%   |
| 6144  | 1        | 0.58%   |
| 512   | 1        | 0.58%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 41       | 23.03%  |
| 3200    | 26       | 14.61%  |
| 1600    | 23       | 12.92%  |
| 2667    | 20       | 11.24%  |
| 2400    | 15       | 8.43%   |
| 4800    | 12       | 6.74%   |
| 2666    | 8        | 4.49%   |
| 2133    | 8        | 4.49%   |
| 5600    | 5        | 2.81%   |
| 667     | 5        | 2.81%   |
| 4267    | 2        | 1.12%   |
| 3600    | 2        | 1.12%   |
| 2933    | 2        | 1.12%   |
| 800     | 2        | 1.12%   |
| 6400    | 1        | 0.56%   |
| 3000    | 1        | 0.56%   |
| 1800    | 1        | 0.56%   |
| 1334    | 1        | 0.56%   |
| 1067    | 1        | 0.56%   |
| 1066    | 1        | 0.56%   |
| Unknown | 1        | 0.56%   |

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


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Microdia | 2        | 100%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                      | Desktops | Percent |
|----------------------------|----------|---------|
| Microdia Lenovo EasyCamera | 2        | 100%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

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
| 1     | 88       | 44.67%  |
| 0     | 72       | 36.55%  |
| 2     | 21       | 10.66%  |
| 3     | 13       | 6.6%    |
| 4     | 3        | 1.52%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 105      | 71.43%  |
| Net/wireless             | 11       | 7.48%   |
| Bluetooth                | 10       | 6.8%    |
| Firewire controller      | 8        | 5.44%   |
| Net/ethernet             | 5        | 3.4%    |
| Card reader              | 3        | 2.04%   |
| Sound                    | 2        | 1.36%   |
| Graphics card            | 2        | 1.36%   |
| Network                  | 1        | 0.68%   |

