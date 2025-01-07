BSD in Switzerland - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for BSD in Switzerland.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Switzerland/Desktop/README.md) and [notebooks](/Location/Switzerland/Notebook/README.md).

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

Total: 545

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Protectli     | VP2420                      | Desktop     | [a3a282fc47](https://bsd-hardware.info/?probe=a3a282fc47) | Jan 04, 2025 |
| IGEL Techn... | IGEL-D220                   | Desktop     | [9d3ca29f8a](https://bsd-hardware.info/?probe=9d3ca29f8a) | Dec 30, 2024 |
| TUXEDO        | InfinityBook Pro AMD Gen... | Notebook    | [b880be6d5f](https://bsd-hardware.info/?probe=b880be6d5f) | Dec 30, 2024 |
| PC Engines    | apu4                        | Desktop     | [1245a959bc](https://bsd-hardware.info/?probe=1245a959bc) | Dec 19, 2024 |
| Unknown       | Unknown                     | Desktop     | [4d58aebb29](https://bsd-hardware.info/?probe=4d58aebb29) | Dec 18, 2024 |
| Supermicro    | X11SDV-4C-TP8F              | Desktop     | [f031d48a53](https://bsd-hardware.info/?probe=f031d48a53) | Dec 16, 2024 |
| Supermicro    | X11SDV-4C-TP8F              | Desktop     | [1eb9f463b0](https://bsd-hardware.info/?probe=1eb9f463b0) | Dec 16, 2024 |
| Chuwi         | LarkBox X                   | Mini pc     | [49533a833d](https://bsd-hardware.info/?probe=49533a833d) | Dec 15, 2024 |
| Chuwi         | LarkBox X                   | Mini pc     | [992ad315d3](https://bsd-hardware.info/?probe=992ad315d3) | Dec 15, 2024 |
| Unknown       | Unknown                     | Desktop     | [696aedf790](https://bsd-hardware.info/?probe=696aedf790) | Dec 13, 2024 |
| Silicom       | 80300-0134-g01              | Desktop     | [9c18dc951c](https://bsd-hardware.info/?probe=9c18dc951c) | Dec 11, 2024 |
| Unknown       | Unknown                     | Desktop     | [3a099cfc0b](https://bsd-hardware.info/?probe=3a099cfc0b) | Dec 07, 2024 |
| PC Engines    | APU2                        | Desktop     | [897b7914d9](https://bsd-hardware.info/?probe=897b7914d9) | Dec 04, 2024 |
| Intel         | D34010WYK H14771-303        | Desktop     | [cc9f37f097](https://bsd-hardware.info/?probe=cc9f37f097) | Dec 04, 2024 |
| Intel         | HURONRIVER                  | Desktop     | [d74d9a6d06](https://bsd-hardware.info/?probe=d74d9a6d06) | Nov 27, 2024 |
| Gowin Solu... | GW-MB-U01                   | Desktop     | [2626f42aad](https://bsd-hardware.info/?probe=2626f42aad) | Nov 25, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [dc3d4a1f8d](https://bsd-hardware.info/?probe=dc3d4a1f8d) | Nov 24, 2024 |
| ASRock        | B550 Taichi                 | Desktop     | [8ef9cf51fb](https://bsd-hardware.info/?probe=8ef9cf51fb) | Nov 21, 2024 |
| Supermicro    | X10SLM+-LN4F                | Server      | [2feec23495](https://bsd-hardware.info/?probe=2feec23495) | Nov 21, 2024 |
| Shuttle       | FH61V                       | Desktop     | [1770dc6006](https://bsd-hardware.info/?probe=1770dc6006) | Nov 19, 2024 |
| Shenzhen M... | AHWSA                       | Desktop     | [8e58ca6121](https://bsd-hardware.info/?probe=8e58ca6121) | Nov 14, 2024 |
| PC Engines    | APU                         | Desktop     | [933dc34c47](https://bsd-hardware.info/?probe=933dc34c47) | Nov 14, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [8583a7eb2e](https://bsd-hardware.info/?probe=8583a7eb2e) | Nov 09, 2024 |
| Shenzhen M... | AHWSA                       | Desktop     | [123789a341](https://bsd-hardware.info/?probe=123789a341) | Nov 07, 2024 |
| ASUSTek       | G75VW                       | Notebook    | [2ede0a1468](https://bsd-hardware.info/?probe=2ede0a1468) | Nov 06, 2024 |
| HP            | 1494                        | Desktop     | [ac956f4a8a](https://bsd-hardware.info/?probe=ac956f4a8a) | Nov 04, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | Notebook    | [7aa93cd8ba](https://bsd-hardware.info/?probe=7aa93cd8ba) | Nov 03, 2024 |
| Supermicro    | X11SDV-4C-TP8F              | Desktop     | [ae14bea998](https://bsd-hardware.info/?probe=ae14bea998) | Nov 02, 2024 |
| Unknown       | Unknown                     | Desktop     | [aeaca5f3a0](https://bsd-hardware.info/?probe=aeaca5f3a0) | Oct 24, 2024 |
| Unknown       | Unknown                     | Desktop     | [f191f5d343](https://bsd-hardware.info/?probe=f191f5d343) | Oct 23, 2024 |
| Supermicro    | X11SCL-IF                   | Server      | [2cb6364513](https://bsd-hardware.info/?probe=2cb6364513) | Oct 23, 2024 |
| HP            | 1494                        | Desktop     | [154852b17b](https://bsd-hardware.info/?probe=154852b17b) | Oct 22, 2024 |
| Unknown       | Unknown                     | Desktop     | [574cd1a009](https://bsd-hardware.info/?probe=574cd1a009) | Oct 18, 2024 |
| PC Engines    | APU                         | Desktop     | [05d1822d02](https://bsd-hardware.info/?probe=05d1822d02) | Oct 17, 2024 |
| PC Engines    | APU                         | Desktop     | [1ccdfd7edd](https://bsd-hardware.info/?probe=1ccdfd7edd) | Oct 17, 2024 |
| PC Engines    | apu4                        | Desktop     | [d185e2c850](https://bsd-hardware.info/?probe=d185e2c850) | Oct 16, 2024 |
| Deciso        | DEC2700 - OPNsense Appli... | Notebook    | [1d5b951541](https://bsd-hardware.info/?probe=1d5b951541) | Oct 04, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [bbc44a72cc](https://bsd-hardware.info/?probe=bbc44a72cc) | Oct 03, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [80cdd4fffc](https://bsd-hardware.info/?probe=80cdd4fffc) | Oct 03, 2024 |
| Shenzhen M... | AHWSA                       | Desktop     | [d8cf190bc2](https://bsd-hardware.info/?probe=d8cf190bc2) | Sep 28, 2024 |
| Unknown       | Unknown                     | Desktop     | [d9e63995fb](https://bsd-hardware.info/?probe=d9e63995fb) | Sep 28, 2024 |
| Supermicro    | X10SDV-TP8F                 | Server      | [b0ce68cff4](https://bsd-hardware.info/?probe=b0ce68cff4) | Sep 28, 2024 |
| Apple         | MacBookPro11,4              | Notebook    | [df7c99c150](https://bsd-hardware.info/?probe=df7c99c150) | Sep 25, 2024 |
| Deciso        | DEC2700 - OPNsense Appli... | Notebook    | [999fa3b31b](https://bsd-hardware.info/?probe=999fa3b31b) | Sep 25, 2024 |
| Apple         | MacBookPro11,4              | Notebook    | [5138a61509](https://bsd-hardware.info/?probe=5138a61509) | Sep 24, 2024 |
| Lenovo        | Yoga 900S-12ISK 80ML        | Notebook    | [8836aa08ec](https://bsd-hardware.info/?probe=8836aa08ec) | Sep 23, 2024 |
| Unknown       | Unknown                     | Desktop     | [9ddfeb7780](https://bsd-hardware.info/?probe=9ddfeb7780) | Sep 21, 2024 |
| Protectli     | V1410                       | Desktop     | [452edd44ed](https://bsd-hardware.info/?probe=452edd44ed) | Sep 20, 2024 |
| Shuttle       | DL30N                       | Desktop     | [895fb08a2f](https://bsd-hardware.info/?probe=895fb08a2f) | Sep 18, 2024 |
| Lenovo        | Yoga 900S-12ISK 80ML        | Notebook    | [41254dde12](https://bsd-hardware.info/?probe=41254dde12) | Sep 15, 2024 |
| Intel BOX4... | Geminilake                  | Desktop     | [7bc6403170](https://bsd-hardware.info/?probe=7bc6403170) | Sep 14, 2024 |
| Protectli     | VP6670                      | Desktop     | [6bf32f779c](https://bsd-hardware.info/?probe=6bf32f779c) | Sep 14, 2024 |
| Deciso        | NetBoard-A20                | Notebook    | [2cad072780](https://bsd-hardware.info/?probe=2cad072780) | Sep 12, 2024 |
| Lenovo        | Yoga 900S-12ISK 80ML        | Notebook    | [ce0404f7c9](https://bsd-hardware.info/?probe=ce0404f7c9) | Aug 31, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [52e2d4ad6a](https://bsd-hardware.info/?probe=52e2d4ad6a) | Aug 29, 2024 |
| Sophos        | XG                          | Firewall    | [c5a7e9a655](https://bsd-hardware.info/?probe=c5a7e9a655) | Aug 28, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [db7a0dda31](https://bsd-hardware.info/?probe=db7a0dda31) | Aug 26, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [c56df5fe7c](https://bsd-hardware.info/?probe=c56df5fe7c) | Aug 25, 2024 |
| Lenovo        | ThinkPad X250 20CMCTO1WW    | Notebook    | [403fdba0ec](https://bsd-hardware.info/?probe=403fdba0ec) | Aug 25, 2024 |
| HP            | EliteBook 2570p             | Notebook    | [facf720e84](https://bsd-hardware.info/?probe=facf720e84) | Aug 24, 2024 |
| Shuttle       | FH310V                      | Desktop     | [ca649bfffa](https://bsd-hardware.info/?probe=ca649bfffa) | Aug 23, 2024 |
| Lenovo        | Yoga 900S-12ISK 80ML        | Notebook    | [a0abac7ab7](https://bsd-hardware.info/?probe=a0abac7ab7) | Aug 21, 2024 |
| Intel         | NUC9i7QNB K49245-500        | Mini pc     | [0ae392a6d4](https://bsd-hardware.info/?probe=0ae392a6d4) | Aug 12, 2024 |
| LinuxConta... | Incus pc-q35-9.0            | Desktop     | [550411a5aa](https://bsd-hardware.info/?probe=550411a5aa) | Aug 04, 2024 |
| ZOTAC         | ZBOX-CI337NANO              | Mini pc     | [a33f652b8c](https://bsd-hardware.info/?probe=a33f652b8c) | Aug 04, 2024 |
| Supermicro    | X11SDV-4C-TLN2F             | Desktop     | [b2bd066528](https://bsd-hardware.info/?probe=b2bd066528) | Aug 02, 2024 |
| Supermicro    | X11SDV-4C-TLN2F             | Desktop     | [be116a0073](https://bsd-hardware.info/?probe=be116a0073) | Aug 02, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [e96f250351](https://bsd-hardware.info/?probe=e96f250351) | Aug 01, 2024 |
| Unknown       | Unknown                     | Desktop     | [2f1762c0ca](https://bsd-hardware.info/?probe=2f1762c0ca) | Jul 26, 2024 |
| Supermicro    | X10SLH-F/X10SLM+-F          | Server      | [44fd1c41b8](https://bsd-hardware.info/?probe=44fd1c41b8) | Jul 24, 2024 |
| Deciso        | DEC2700 - OPNsense Appli... | Notebook    | [bcbdd06498](https://bsd-hardware.info/?probe=bcbdd06498) | Jul 21, 2024 |
| ZOTAC         | ZBOX-CI337NANO              | Mini pc     | [3039d78d20](https://bsd-hardware.info/?probe=3039d78d20) | Jul 19, 2024 |
| Unknown       | QDNV01                      | Desktop     | [6c29d0b29c](https://bsd-hardware.info/?probe=6c29d0b29c) | Jul 19, 2024 |
| Deciso        | NetBoard-A20                | Notebook    | [190d52ebe5](https://bsd-hardware.info/?probe=190d52ebe5) | Jul 13, 2024 |
| ZOTAC         | ZBOX-CI337NANO              | Mini pc     | [207da6c3ec](https://bsd-hardware.info/?probe=207da6c3ec) | Jul 06, 2024 |
| ZOTAC         | ZBOX-CI337NANO              | Mini pc     | [c1b95e991f](https://bsd-hardware.info/?probe=c1b95e991f) | Jul 04, 2024 |
| Shuttle       | DL30N                       | Desktop     | [8004067dfc](https://bsd-hardware.info/?probe=8004067dfc) | Jul 02, 2024 |
| Supermicro    | X11SCL-IF                   | Server      | [9bc9088d47](https://bsd-hardware.info/?probe=9bc9088d47) | Jun 22, 2024 |
| HP            | ProLiant DL380 G7           | Server      | [4aaa4938f3](https://bsd-hardware.info/?probe=4aaa4938f3) | Jun 17, 2024 |
| Protectli     | VP6670                      | Desktop     | [9c24cea9d2](https://bsd-hardware.info/?probe=9c24cea9d2) | Jun 16, 2024 |
| HP            | EliteBook 8540p             | Notebook    | [cad0e50ea5](https://bsd-hardware.info/?probe=cad0e50ea5) | Jun 14, 2024 |
| HP            | ProLiant ML350p Gen8        | Desktop     | [820bfd0c77](https://bsd-hardware.info/?probe=820bfd0c77) | Jun 14, 2024 |
| Lenovo        | ThinkPad X250 20CMCTO1WW    | Notebook    | [bbc7b223f1](https://bsd-hardware.info/?probe=bbc7b223f1) | Jun 14, 2024 |
| CheckPoint    | PB-10-00                    | Firewall    | [db2a3b2992](https://bsd-hardware.info/?probe=db2a3b2992) | Jun 13, 2024 |
| Sophos        | XG                          | Firewall    | [339760b2c7](https://bsd-hardware.info/?probe=339760b2c7) | Jun 09, 2024 |
| Sophos        | XG                          | Firewall    | [129a40e081](https://bsd-hardware.info/?probe=129a40e081) | Jun 04, 2024 |
| Deciso        | NetBoard-A20                | Notebook    | [e30ed0bb29](https://bsd-hardware.info/?probe=e30ed0bb29) | Jun 03, 2024 |
| Dell          | 0TWW5Y A02                  | Server      | [22fdb634c0](https://bsd-hardware.info/?probe=22fdb634c0) | May 26, 2024 |
| Deciso        | NetBoard-A20                | Notebook    | [ce91493709](https://bsd-hardware.info/?probe=ce91493709) | May 24, 2024 |
| CheckPoint    | PB-10-00                    | Firewall    | [43e01c8dc5](https://bsd-hardware.info/?probe=43e01c8dc5) | May 21, 2024 |
| Unknown       | Unknown                     | Desktop     | [71e118978a](https://bsd-hardware.info/?probe=71e118978a) | May 19, 2024 |
| Trigkey       | Green G5                    | Desktop     | [85a239bc2f](https://bsd-hardware.info/?probe=85a239bc2f) | May 18, 2024 |
| Unknown       | QDNV01                      | Desktop     | [f23cb7b083](https://bsd-hardware.info/?probe=f23cb7b083) | May 18, 2024 |
| Unknown       | QDNV01                      | Desktop     | [9b0fbcd081](https://bsd-hardware.info/?probe=9b0fbcd081) | May 18, 2024 |
| Sophos        | SG                          | Firewall    | [b9b4ba32e4](https://bsd-hardware.info/?probe=b9b4ba32e4) | May 18, 2024 |
| ASUSTek       | H170M-E D3                  | Desktop     | [a07851f5f5](https://bsd-hardware.info/?probe=a07851f5f5) | May 13, 2024 |
| Trigkey       | Green G5                    | Desktop     | [0cc228bf09](https://bsd-hardware.info/?probe=0cc228bf09) | May 09, 2024 |
| Dell          | 072T6D A01                  | Server      | [a7a95f387b](https://bsd-hardware.info/?probe=a7a95f387b) | May 07, 2024 |
| Lenovo        | ThinkPad T15p Gen 1 20TN... | Notebook    | [5f31e6dc7e](https://bsd-hardware.info/?probe=5f31e6dc7e) | May 04, 2024 |
| ASUSTek       | TUF Gaming A620-PRO WIFI    | Desktop     | [a186355a65](https://bsd-hardware.info/?probe=a186355a65) | May 02, 2024 |
| Intel         | NUC10i3FNB M38070-307       | Mini pc     | [671adbdfc4](https://bsd-hardware.info/?probe=671adbdfc4) | May 01, 2024 |
| HP            | EliteBook 2560p             | Notebook    | [bb6303ed5b](https://bsd-hardware.info/?probe=bb6303ed5b) | Apr 29, 2024 |
| Trigkey       | Green G5                    | Desktop     | [6bad716921](https://bsd-hardware.info/?probe=6bad716921) | Apr 26, 2024 |
| Intel         | SHARKBAY                    | Desktop     | [cbe3a65615](https://bsd-hardware.info/?probe=cbe3a65615) | Apr 16, 2024 |
| Unknown       | QDNV01                      | Desktop     | [e90c02d0da](https://bsd-hardware.info/?probe=e90c02d0da) | Apr 13, 2024 |
| ASUSTek       | Z97-A                       | Desktop     | [2f83e16bd9](https://bsd-hardware.info/?probe=2f83e16bd9) | Apr 11, 2024 |
| PC Engines    | APU2                        | Desktop     | [22fc545294](https://bsd-hardware.info/?probe=22fc545294) | Apr 11, 2024 |
| Dell          | 0TWW5Y A02                  | Server      | [7f7aa552e1](https://bsd-hardware.info/?probe=7f7aa552e1) | Apr 10, 2024 |
| Unknown       | Unknown                     | Desktop     | [258e758f9b](https://bsd-hardware.info/?probe=258e758f9b) | Mar 30, 2024 |
| MW            | GMLK-2_5G4L                 | Desktop     | [690a945c99](https://bsd-hardware.info/?probe=690a945c99) | Mar 30, 2024 |
| PC Engines    | APU2                        | Desktop     | [e5ac53d0d4](https://bsd-hardware.info/?probe=e5ac53d0d4) | Mar 26, 2024 |
| Unknown       | Unknown                     | Desktop     | [352fb163da](https://bsd-hardware.info/?probe=352fb163da) | Mar 24, 2024 |
| Unknown       | Unknown                     | Desktop     | [462b269f0f](https://bsd-hardware.info/?probe=462b269f0f) | Mar 18, 2024 |
| Supermicro    | X10SDV-TP8F                 | Server      | [b9029d81da](https://bsd-hardware.info/?probe=b9029d81da) | Mar 11, 2024 |
| Supermicro    | X11SDW-8C-TP13F             | Desktop     | [8092b98305](https://bsd-hardware.info/?probe=8092b98305) | Mar 11, 2024 |
| Dell          | 0X4N41 A01                  | Desktop     | [25688a2cac](https://bsd-hardware.info/?probe=25688a2cac) | Mar 11, 2024 |
| Unknown       | Unknown                     | Desktop     | [cc261708c0](https://bsd-hardware.info/?probe=cc261708c0) | Mar 02, 2024 |
| Unknown       | Unknown                     | Desktop     | [0960d6e3b5](https://bsd-hardware.info/?probe=0960d6e3b5) | Feb 29, 2024 |
| PC Engines    | APU2                        | Desktop     | [513a0febb8](https://bsd-hardware.info/?probe=513a0febb8) | Feb 20, 2024 |
| PC Engines    | APU2                        | Desktop     | [4f83cef1be](https://bsd-hardware.info/?probe=4f83cef1be) | Feb 20, 2024 |
| ASUSTek       | Q87T                        | Desktop     | [cc75f2f0fa](https://bsd-hardware.info/?probe=cc75f2f0fa) | Feb 18, 2024 |
| Sophos        | SG                          | Firewall    | [e38a7b380e](https://bsd-hardware.info/?probe=e38a7b380e) | Feb 18, 2024 |
| PC Engines    | apu6                        | Desktop     | [9f618d2d95](https://bsd-hardware.info/?probe=9f618d2d95) | Feb 17, 2024 |
| Unknown       | Unknown                     | Desktop     | [0a1749e911](https://bsd-hardware.info/?probe=0a1749e911) | Feb 17, 2024 |
| ASUSTek       | Q87T                        | Desktop     | [ca381bbbcc](https://bsd-hardware.info/?probe=ca381bbbcc) | Feb 17, 2024 |
| ASRock        | B550 Taichi                 | Desktop     | [814a0aba66](https://bsd-hardware.info/?probe=814a0aba66) | Feb 14, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [52d7bc4280](https://bsd-hardware.info/?probe=52d7bc4280) | Feb 13, 2024 |
| Lenovo        | Yoga 900S-12ISK 80ML        | Notebook    | [47f57b0893](https://bsd-hardware.info/?probe=47f57b0893) | Feb 11, 2024 |
| Lenovo        | Yoga 900S-12ISK 80ML        | Notebook    | [5315513827](https://bsd-hardware.info/?probe=5315513827) | Feb 11, 2024 |
| Intel         | NUC11DBBi7 M17027-404       | Mini pc     | [4b3438a1eb](https://bsd-hardware.info/?probe=4b3438a1eb) | Feb 09, 2024 |
| Supermicro    | A1SAi 123456789             | Mini pc     | [ebb7e0a814](https://bsd-hardware.info/?probe=ebb7e0a814) | Feb 06, 2024 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [55d74d88f2](https://bsd-hardware.info/?probe=55d74d88f2) | Feb 06, 2024 |
| Unknown       | Unknown                     | Desktop     | [f206c1a24c](https://bsd-hardware.info/?probe=f206c1a24c) | Feb 05, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [39e92446fc](https://bsd-hardware.info/?probe=39e92446fc) | Feb 03, 2024 |
| Intel         | NUC11DBBi7 M17027-404       | Mini pc     | [c29c522ede](https://bsd-hardware.info/?probe=c29c522ede) | Feb 03, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [98d2751465](https://bsd-hardware.info/?probe=98d2751465) | Feb 01, 2024 |
| BESSTAR Te... | GB7                         | Mini pc     | [21fc9a3c78](https://bsd-hardware.info/?probe=21fc9a3c78) | Jan 27, 2024 |
| BESSTAR Te... | GB7                         | Mini pc     | [d280f919ce](https://bsd-hardware.info/?probe=d280f919ce) | Jan 26, 2024 |
| Unknown       | Unknown                     | Desktop     | [829691c455](https://bsd-hardware.info/?probe=829691c455) | Jan 26, 2024 |
| Shuttle       | FS110                       | Desktop     | [48cc3837da](https://bsd-hardware.info/?probe=48cc3837da) | Jan 14, 2024 |
| Deciso        | NetBoard-A20                | Notebook    | [aaadb904c1](https://bsd-hardware.info/?probe=aaadb904c1) | Jan 10, 2024 |
| Deciso        | NetBoard-A20                | Notebook    | [cfcb03c18a](https://bsd-hardware.info/?probe=cfcb03c18a) | Jan 05, 2024 |
| HP            | 1905                        | Desktop     | [9e67ddf10b](https://bsd-hardware.info/?probe=9e67ddf10b) | Jan 05, 2024 |
| Dell          | XPS 15 7590                 | Notebook    | [67a65520e6](https://bsd-hardware.info/?probe=67a65520e6) | Jan 03, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | Notebook    | [2ab7b9d6b2](https://bsd-hardware.info/?probe=2ab7b9d6b2) | Jan 02, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | Notebook    | [0a2c02f944](https://bsd-hardware.info/?probe=0a2c02f944) | Dec 27, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | Notebook    | [4b1250f831](https://bsd-hardware.info/?probe=4b1250f831) | Dec 26, 2023 |
| PC Engines    | APU2                        | Desktop     | [79f4518fa1](https://bsd-hardware.info/?probe=79f4518fa1) | Dec 23, 2023 |
| ASUSTek       | PRIME H610I-PLUS D4         | Desktop     | [3a435d185e](https://bsd-hardware.info/?probe=3a435d185e) | Dec 22, 2023 |
| PC Engines    | APU2                        | Desktop     | [f3061d599c](https://bsd-hardware.info/?probe=f3061d599c) | Dec 19, 2023 |
| Intel         | HURONRIVER                  | Desktop     | [d0ebaa4479](https://bsd-hardware.info/?probe=d0ebaa4479) | Dec 17, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [e1867819f3](https://bsd-hardware.info/?probe=e1867819f3) | Dec 15, 2023 |
| Deciso        | NetBoard-A20                | Notebook    | [18364861b5](https://bsd-hardware.info/?probe=18364861b5) | Dec 03, 2023 |
| Unknown       | QDNV01                      | Desktop     | [63cbf7642b](https://bsd-hardware.info/?probe=63cbf7642b) | Nov 28, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [1096dc8160](https://bsd-hardware.info/?probe=1096dc8160) | Nov 27, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [1bfc57a019](https://bsd-hardware.info/?probe=1bfc57a019) | Nov 27, 2023 |
| ASRock        | B550 Taichi                 | Desktop     | [60d2873b5d](https://bsd-hardware.info/?probe=60d2873b5d) | Nov 26, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [797f393ce0](https://bsd-hardware.info/?probe=797f393ce0) | Nov 19, 2023 |
| Lenovo        | ThinkPad W530 24411M9       | Notebook    | [0272396725](https://bsd-hardware.info/?probe=0272396725) | Nov 19, 2023 |
| Unknown       | YL-SKUL6                    | Desktop     | [ac654676da](https://bsd-hardware.info/?probe=ac654676da) | Nov 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [918706e110](https://bsd-hardware.info/?probe=918706e110) | Nov 15, 2023 |
| ASUSTek       | K56CB                       | Notebook    | [8d4f2c439a](https://bsd-hardware.info/?probe=8d4f2c439a) | Nov 11, 2023 |
| ASUSTek       | Z97-A                       | Desktop     | [3ce8e78453](https://bsd-hardware.info/?probe=3ce8e78453) | Nov 11, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [3ce02454f8](https://bsd-hardware.info/?probe=3ce02454f8) | Nov 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [876b0db38a](https://bsd-hardware.info/?probe=876b0db38a) | Nov 07, 2023 |
| ZOTAC         | ZBOX-CI320NANO series Re... | Mini pc     | [9de790eac0](https://bsd-hardware.info/?probe=9de790eac0) | Nov 05, 2023 |
| ASUSTek       | K56CB                       | Notebook    | [7d6d03a42b](https://bsd-hardware.info/?probe=7d6d03a42b) | Nov 05, 2023 |
| Dell          | 0MD99X A12                  | Server      | [c137d2d6da](https://bsd-hardware.info/?probe=c137d2d6da) | Nov 05, 2023 |
| ASUSTek       | Z97-A                       | Desktop     | [a8aad4a386](https://bsd-hardware.info/?probe=a8aad4a386) | Nov 04, 2023 |
| Yanling       | YL-KBR6L Ver:1.01           | Desktop     | [bdc7be2258](https://bsd-hardware.info/?probe=bdc7be2258) | Oct 29, 2023 |
| GoWin Solu... | R86S                        | Desktop     | [8668f0e8e9](https://bsd-hardware.info/?probe=8668f0e8e9) | Oct 24, 2023 |
| Seco          | UDOO x86                    | Notebook    | [260f8194ed](https://bsd-hardware.info/?probe=260f8194ed) | Oct 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [135c0112a4](https://bsd-hardware.info/?probe=135c0112a4) | Oct 21, 2023 |
| Unknown       | QDNV01                      | Desktop     | [df90627ba3](https://bsd-hardware.info/?probe=df90627ba3) | Oct 17, 2023 |
| Deciso        | NetBoard-A20                | Notebook    | [7ed49c5f2f](https://bsd-hardware.info/?probe=7ed49c5f2f) | Oct 13, 2023 |
| Deciso        | NetBoard-A20                | Notebook    | [b9c11f29c9](https://bsd-hardware.info/?probe=b9c11f29c9) | Oct 10, 2023 |
| Deciso        | Netboard A20                | Notebook    | [c549fc9540](https://bsd-hardware.info/?probe=c549fc9540) | Oct 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [50418139b2](https://bsd-hardware.info/?probe=50418139b2) | Sep 30, 2023 |
| Sophos        | SG                          | Firewall    | [273b148522](https://bsd-hardware.info/?probe=273b148522) | Sep 30, 2023 |
| PC Engines    | APU                         | Desktop     | [ca9bc2faa7](https://bsd-hardware.info/?probe=ca9bc2faa7) | Sep 29, 2023 |
| PC Engines    | APU                         | Desktop     | [067872c1f5](https://bsd-hardware.info/?probe=067872c1f5) | Sep 29, 2023 |
| PC Engines    | APU2                        | Desktop     | [252385ae71](https://bsd-hardware.info/?probe=252385ae71) | Sep 27, 2023 |
| GoWin Solu... | R86S                        | Desktop     | [6d38812084](https://bsd-hardware.info/?probe=6d38812084) | Sep 22, 2023 |
| Supermicro    | X11SCL-IF                   | Server      | [da7e89f514](https://bsd-hardware.info/?probe=da7e89f514) | Sep 20, 2023 |
| Supermicro    | X11SCL-IF                   | Server      | [5a57c7066e](https://bsd-hardware.info/?probe=5a57c7066e) | Sep 19, 2023 |
| HP            | 1790                        | Desktop     | [17ace3bb2c](https://bsd-hardware.info/?probe=17ace3bb2c) | Sep 18, 2023 |
| Sophos        | SG                          | Firewall    | [960f408d24](https://bsd-hardware.info/?probe=960f408d24) | Sep 13, 2023 |
| ASUSTek       | H170M-E D3                  | Desktop     | [f9bde14ab2](https://bsd-hardware.info/?probe=f9bde14ab2) | Sep 10, 2023 |
| Supermicro    | X11SCL-IF                   | Server      | [b8c6daa2c4](https://bsd-hardware.info/?probe=b8c6daa2c4) | Aug 30, 2023 |
| Deciso        | NetBoard-A20                | Notebook    | [e9e295eae3](https://bsd-hardware.info/?probe=e9e295eae3) | Aug 24, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [e59ce0fb84](https://bsd-hardware.info/?probe=e59ce0fb84) | Aug 21, 2023 |
| Supermicro    | X11SDW-8C-TP13F             | Desktop     | [da4385727b](https://bsd-hardware.info/?probe=da4385727b) | Aug 19, 2023 |
| Deciso        | NetBoard-A20                | Notebook    | [c38eb6b9bd](https://bsd-hardware.info/?probe=c38eb6b9bd) | Aug 19, 2023 |
| Supermicro    | X10SLM+-LN4F                | Server      | [05e32e30fd](https://bsd-hardware.info/?probe=05e32e30fd) | Aug 17, 2023 |
| PC Engines    | apu6                        | Desktop     | [65fda0fe1f](https://bsd-hardware.info/?probe=65fda0fe1f) | Aug 11, 2023 |
| Lenovo        | 3743 SDK0T76461 WIN 3422... | Desktop     | [d5675b5940](https://bsd-hardware.info/?probe=d5675b5940) | Aug 06, 2023 |
| Intel BOX4... | Geminilake                  | Desktop     | [b833ada775](https://bsd-hardware.info/?probe=b833ada775) | Aug 01, 2023 |
| GoWin Solu... | R86S                        | Desktop     | [51bb255924](https://bsd-hardware.info/?probe=51bb255924) | Jul 29, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [020e17c2f8](https://bsd-hardware.info/?probe=020e17c2f8) | Jul 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [dc7318d29f](https://bsd-hardware.info/?probe=dc7318d29f) | Jul 15, 2023 |
| Deciso        | Netboard A20                | Notebook    | [e82dfa5520](https://bsd-hardware.info/?probe=e82dfa5520) | Jul 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [9ce40969da](https://bsd-hardware.info/?probe=9ce40969da) | Jul 11, 2023 |
| Protectli     | VP2410                      | Desktop     | [8ad8c5daa9](https://bsd-hardware.info/?probe=8ad8c5daa9) | Jul 03, 2023 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [3f2469c1b3](https://bsd-hardware.info/?probe=3f2469c1b3) | Jul 01, 2023 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [ee61a4b160](https://bsd-hardware.info/?probe=ee61a4b160) | Jun 17, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [dd937d0914](https://bsd-hardware.info/?probe=dd937d0914) | Jun 12, 2023 |
| PC Engines    | apu4                        | Desktop     | [f130ecbaa3](https://bsd-hardware.info/?probe=f130ecbaa3) | Jun 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [c1854cc5f2](https://bsd-hardware.info/?probe=c1854cc5f2) | May 27, 2023 |
| ASRock        | Z68 Pro3 Gen3               | Desktop     | [0a03cd86a0](https://bsd-hardware.info/?probe=0a03cd86a0) | May 21, 2023 |
| HP            | 8299                        | Desktop     | [f5ecf1eaeb](https://bsd-hardware.info/?probe=f5ecf1eaeb) | May 17, 2023 |
| CWWK          | MINIPC-G12                  | Desktop     | [b26aab0f0d](https://bsd-hardware.info/?probe=b26aab0f0d) | May 17, 2023 |
| Supermicro    | X11SCL-IF                   | Server      | [e44ad0928d](https://bsd-hardware.info/?probe=e44ad0928d) | May 15, 2023 |
| PC Engines    | apu6                        | Desktop     | [3733cf215f](https://bsd-hardware.info/?probe=3733cf215f) | May 13, 2023 |
| Supermicro    | X11SDW-16C-TP13F+           | Desktop     | [1cc0308686](https://bsd-hardware.info/?probe=1cc0308686) | May 13, 2023 |
| Supermicro    | X11SCL-IF                   | Server      | [4932220de5](https://bsd-hardware.info/?probe=4932220de5) | May 09, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [95695f78c5](https://bsd-hardware.info/?probe=95695f78c5) | May 08, 2023 |
| Supermicro    | X11SCL-IF                   | Server      | [d4916dbd5f](https://bsd-hardware.info/?probe=d4916dbd5f) | May 08, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [9fea438eba](https://bsd-hardware.info/?probe=9fea438eba) | May 07, 2023 |
| ASUSTek       | PRIME H610I-PLUS D4         | Desktop     | [472c5fb78e](https://bsd-hardware.info/?probe=472c5fb78e) | Apr 29, 2023 |
| Sophos        | SG                          | Firewall    | [b5452a27b6](https://bsd-hardware.info/?probe=b5452a27b6) | Apr 24, 2023 |
| PC Engines    | APU2                        | Desktop     | [4337168a3a](https://bsd-hardware.info/?probe=4337168a3a) | Apr 20, 2023 |
| Supermicro    | M11SDV-8C-LN4F              | Desktop     | [49a95f197c](https://bsd-hardware.info/?probe=49a95f197c) | Apr 20, 2023 |
| Intel BOX4... | Geminilake                  | Desktop     | [79d72cc60f](https://bsd-hardware.info/?probe=79d72cc60f) | Apr 13, 2023 |
| PC Engines    | APU2                        | Desktop     | [766755078c](https://bsd-hardware.info/?probe=766755078c) | Apr 10, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [692b42afcd](https://bsd-hardware.info/?probe=692b42afcd) | Apr 08, 2023 |
| Sophos        | SG                          | Firewall    | [b3328d5498](https://bsd-hardware.info/?probe=b3328d5498) | Apr 01, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [0af5cebe20](https://bsd-hardware.info/?probe=0af5cebe20) | Mar 29, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [f4e450fed1](https://bsd-hardware.info/?probe=f4e450fed1) | Mar 29, 2023 |
| Supermicro    | A1SAi 123456789             | Mini pc     | [72e4bf10a6](https://bsd-hardware.info/?probe=72e4bf10a6) | Mar 23, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [136a6641be](https://bsd-hardware.info/?probe=136a6641be) | Mar 21, 2023 |
| Apple         | iMac18,1                    | All in one  | [c6c12705af](https://bsd-hardware.info/?probe=c6c12705af) | Mar 20, 2023 |
| Apple         | MacBookPro5,1               | Notebook    | [9e300b5797](https://bsd-hardware.info/?probe=9e300b5797) | Mar 19, 2023 |
| GoWin Solu... | R86S                        | Desktop     | [35e1503946](https://bsd-hardware.info/?probe=35e1503946) | Mar 08, 2023 |
| Protectli     | FW4C Ver                    | Desktop     | [d93437d96b](https://bsd-hardware.info/?probe=d93437d96b) | Mar 04, 2023 |
| Shuttle       | FS81                        | Desktop     | [5787eda5ac](https://bsd-hardware.info/?probe=5787eda5ac) | Feb 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [913946ccc9](https://bsd-hardware.info/?probe=913946ccc9) | Feb 25, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [0e62dfc436](https://bsd-hardware.info/?probe=0e62dfc436) | Feb 25, 2023 |
| Dell          | 05XGC8 A01                  | Desktop     | [c51a264e20](https://bsd-hardware.info/?probe=c51a264e20) | Feb 23, 2023 |
| Intel         | NUC12WSBi3 M36953-303       | Mini pc     | [727ca24f1c](https://bsd-hardware.info/?probe=727ca24f1c) | Feb 22, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [5b8fdd6349](https://bsd-hardware.info/?probe=5b8fdd6349) | Feb 21, 2023 |
| Intel         | NUC12WSBi3 M36953-303       | Mini pc     | [9bdcc78235](https://bsd-hardware.info/?probe=9bdcc78235) | Feb 19, 2023 |
| Deciso        | Netboard A20                | Notebook    | [7c91a0f01b](https://bsd-hardware.info/?probe=7c91a0f01b) | Feb 14, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [0c9cf4e002](https://bsd-hardware.info/?probe=0c9cf4e002) | Feb 09, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [ca1e51a042](https://bsd-hardware.info/?probe=ca1e51a042) | Feb 09, 2023 |
| Supermicro    | M11SDV-8C-LN4F              | Desktop     | [4874e3417f](https://bsd-hardware.info/?probe=4874e3417f) | Feb 09, 2023 |
| Intel BOX4... | Geminilake                  | Desktop     | [286c29b1bb](https://bsd-hardware.info/?probe=286c29b1bb) | Feb 08, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [3a47e70001](https://bsd-hardware.info/?probe=3a47e70001) | Feb 03, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [193659d215](https://bsd-hardware.info/?probe=193659d215) | Feb 03, 2023 |
| PC Engines    | apu4                        | Desktop     | [c3ff966a17](https://bsd-hardware.info/?probe=c3ff966a17) | Feb 03, 2023 |
| PC Engines    | APU2                        | Desktop     | [315ef90664](https://bsd-hardware.info/?probe=315ef90664) | Feb 01, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [e43ebed0e6](https://bsd-hardware.info/?probe=e43ebed0e6) | Jan 29, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [92aedf2a46](https://bsd-hardware.info/?probe=92aedf2a46) | Jan 28, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [5b226a942e](https://bsd-hardware.info/?probe=5b226a942e) | Jan 27, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [06e3f3daea](https://bsd-hardware.info/?probe=06e3f3daea) | Jan 24, 2023 |
| Unknown       | Unknown                     | Notebook    | [8511097117](https://bsd-hardware.info/?probe=8511097117) | Jan 22, 2023 |
| Unknown       | Unknown                     | Notebook    | [d5d2ce1b39](https://bsd-hardware.info/?probe=d5d2ce1b39) | Jan 22, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [739cc6e5ac](https://bsd-hardware.info/?probe=739cc6e5ac) | Jan 18, 2023 |
| Intel         | HURONRIVER                  | Desktop     | [9994ae920b](https://bsd-hardware.info/?probe=9994ae920b) | Jan 15, 2023 |
| Intel         | HURONRIVER                  | Desktop     | [320272bdf1](https://bsd-hardware.info/?probe=320272bdf1) | Jan 11, 2023 |
| PC Engines    | apu4                        | Desktop     | [3d69b3aec1](https://bsd-hardware.info/?probe=3d69b3aec1) | Jan 03, 2023 |
| PC Engines    | apu4                        | Desktop     | [62e6e7e679](https://bsd-hardware.info/?probe=62e6e7e679) | Jan 03, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [2973cd399c](https://bsd-hardware.info/?probe=2973cd399c) | Jan 01, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [d22c37fa81](https://bsd-hardware.info/?probe=d22c37fa81) | Dec 29, 2022 |
| Sophos        | SG                          | Firewall    | [e331fe5e06](https://bsd-hardware.info/?probe=e331fe5e06) | Dec 26, 2022 |
| Intel BOX4... | Geminilake                  | Desktop     | [a2b2b7c25f](https://bsd-hardware.info/?probe=a2b2b7c25f) | Dec 23, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [a2bc442acd](https://bsd-hardware.info/?probe=a2bc442acd) | Dec 23, 2022 |
| Intel BOX4... | Geminilake                  | Desktop     | [06933f3d87](https://bsd-hardware.info/?probe=06933f3d87) | Dec 23, 2022 |
| Dell          | 0X4N41 A01                  | Desktop     | [4091e15cac](https://bsd-hardware.info/?probe=4091e15cac) | Dec 14, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [1d8397a653](https://bsd-hardware.info/?probe=1d8397a653) | Dec 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [0405fd0f0d](https://bsd-hardware.info/?probe=0405fd0f0d) | Dec 09, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [c30f53fc6d](https://bsd-hardware.info/?probe=c30f53fc6d) | Dec 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [78893acbd5](https://bsd-hardware.info/?probe=78893acbd5) | Dec 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [a5b10d3f79](https://bsd-hardware.info/?probe=a5b10d3f79) | Nov 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [2fe35064cb](https://bsd-hardware.info/?probe=2fe35064cb) | Nov 28, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [7f9869324b](https://bsd-hardware.info/?probe=7f9869324b) | Nov 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [77e932dd9e](https://bsd-hardware.info/?probe=77e932dd9e) | Nov 23, 2022 |
| Infoblox      | IB-1410                     | Desktop     | [7521108ef5](https://bsd-hardware.info/?probe=7521108ef5) | Nov 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [521008f8da](https://bsd-hardware.info/?probe=521008f8da) | Nov 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [bc7a300434](https://bsd-hardware.info/?probe=bc7a300434) | Nov 02, 2022 |
| Intel         | NUC9i7QNB K49245-500        | Mini pc     | [154dad5874](https://bsd-hardware.info/?probe=154dad5874) | Oct 18, 2022 |
| Unknown       | Unknown                     | Desktop     | [2fc5bd737a](https://bsd-hardware.info/?probe=2fc5bd737a) | Oct 09, 2022 |
| PC Engines    | APU2                        | Desktop     | [47e38f3abe](https://bsd-hardware.info/?probe=47e38f3abe) | Oct 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [02a9700c12](https://bsd-hardware.info/?probe=02a9700c12) | Oct 03, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [353008eb5e](https://bsd-hardware.info/?probe=353008eb5e) | Sep 29, 2022 |
| PC Engines    | APU2                        | Desktop     | [3fcc5e5ae2](https://bsd-hardware.info/?probe=3fcc5e5ae2) | Sep 25, 2022 |
| Lenovo        | ThinkPad T460p 20FW003PM... | Notebook    | [ac8e728222](https://bsd-hardware.info/?probe=ac8e728222) | Sep 24, 2022 |
| Sophos        | SG                          | Firewall    | [d485561c3b](https://bsd-hardware.info/?probe=d485561c3b) | Sep 21, 2022 |
| Unknown       | Unknown                     | Notebook    | [fbd1af0e98](https://bsd-hardware.info/?probe=fbd1af0e98) | Sep 21, 2022 |
| Acer          | Aspire E5-771               | Notebook    | [0a58077c49](https://bsd-hardware.info/?probe=0a58077c49) | Sep 20, 2022 |
| HP            | ProLiant ML350p Gen8        | Desktop     | [1a9c6a10bd](https://bsd-hardware.info/?probe=1a9c6a10bd) | Sep 19, 2022 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [a24f08281d](https://bsd-hardware.info/?probe=a24f08281d) | Sep 19, 2022 |
| Apple         | Mac-7BA5B2D9E42DDD94        | Desktop     | [d2e169b8ad](https://bsd-hardware.info/?probe=d2e169b8ad) | Sep 13, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [68ac9de055](https://bsd-hardware.info/?probe=68ac9de055) | Sep 05, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [f4d84edb3b](https://bsd-hardware.info/?probe=f4d84edb3b) | Sep 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [9422de47ab](https://bsd-hardware.info/?probe=9422de47ab) | Aug 30, 2022 |
| Shuttle       | FS81                        | Desktop     | [b2db8ceabe](https://bsd-hardware.info/?probe=b2db8ceabe) | Aug 24, 2022 |
| Dell          | 02YYK5 A00                  | Desktop     | [5428710004](https://bsd-hardware.info/?probe=5428710004) | Aug 16, 2022 |
| Supermicro    | X10SDV-TP8F                 | Server      | [3b99c8f471](https://bsd-hardware.info/?probe=3b99c8f471) | Aug 09, 2022 |
| Acer          | Aspire X3995                | Desktop     | [9240256ae5](https://bsd-hardware.info/?probe=9240256ae5) | Aug 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [9f98df6faf](https://bsd-hardware.info/?probe=9f98df6faf) | Aug 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [25ca16baef](https://bsd-hardware.info/?probe=25ca16baef) | Aug 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [f9bf5b2e00](https://bsd-hardware.info/?probe=f9bf5b2e00) | Aug 04, 2022 |
| PC Engines    | APU2                        | Desktop     | [35d0a79b04](https://bsd-hardware.info/?probe=35d0a79b04) | Aug 04, 2022 |
| Protectli     | FW6                         | Desktop     | [b686fdf1c1](https://bsd-hardware.info/?probe=b686fdf1c1) | Jul 31, 2022 |
| Unknown       | Unknown                     | Desktop     | [0b84314fbf](https://bsd-hardware.info/?probe=0b84314fbf) | Jul 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [4e721b00d5](https://bsd-hardware.info/?probe=4e721b00d5) | Jul 28, 2022 |
| PC Engines    | APU2                        | Desktop     | [7d3a1f2825](https://bsd-hardware.info/?probe=7d3a1f2825) | Jul 14, 2022 |
| PC Engines    | APU2                        | Desktop     | [0dd60aeb9a](https://bsd-hardware.info/?probe=0dd60aeb9a) | Jul 14, 2022 |
| Biostar       | H61MHV2                     | Desktop     | [58a61e6171](https://bsd-hardware.info/?probe=58a61e6171) | Jul 11, 2022 |
| Biostar       | H61MHV2                     | Desktop     | [2aa5e2a62d](https://bsd-hardware.info/?probe=2aa5e2a62d) | Jul 08, 2022 |
| Deciso        | Netboard A20                | Notebook    | [c70ba0979e](https://bsd-hardware.info/?probe=c70ba0979e) | Jul 07, 2022 |
| Dell          | 02YYK5 A00                  | Desktop     | [fb2e5bec61](https://bsd-hardware.info/?probe=fb2e5bec61) | Jul 05, 2022 |
| Dell          | 02YYK5 A00                  | Desktop     | [629de6cdb6](https://bsd-hardware.info/?probe=629de6cdb6) | Jul 05, 2022 |
| HP            | 1494                        | Desktop     | [3a61eb7bae](https://bsd-hardware.info/?probe=3a61eb7bae) | Jul 01, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [34bb6613ee](https://bsd-hardware.info/?probe=34bb6613ee) | Jun 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [d7d6b654a4](https://bsd-hardware.info/?probe=d7d6b654a4) | Jun 22, 2022 |
| Dell          | 02YYK5 A00                  | Desktop     | [180af6a2da](https://bsd-hardware.info/?probe=180af6a2da) | Jun 19, 2022 |
| Dell          | 02YYK5 A00                  | Desktop     | [c58d529930](https://bsd-hardware.info/?probe=c58d529930) | Jun 19, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [97e567c06b](https://bsd-hardware.info/?probe=97e567c06b) | Jun 18, 2022 |
| Supermicro    | A1SRM-2758F                 | Server      | [3c53a92a68](https://bsd-hardware.info/?probe=3c53a92a68) | Jun 17, 2022 |
| Supermicro    | X10SLH-F/X10SLM+-F          | Server      | [626b058309](https://bsd-hardware.info/?probe=626b058309) | Jun 16, 2022 |
| Supermicro    | X10SLH-F/X10SLM+-F          | Server      | [ef0e973cad](https://bsd-hardware.info/?probe=ef0e973cad) | Jun 15, 2022 |
| ASUSTek       | Pro B660M-C D4              | Desktop     | [302ea8252d](https://bsd-hardware.info/?probe=302ea8252d) | Jun 08, 2022 |
| PC Engines    | apu4                        | Desktop     | [1067180759](https://bsd-hardware.info/?probe=1067180759) | May 31, 2022 |
| PC Engines    | apu4                        | Desktop     | [214bc37259](https://bsd-hardware.info/?probe=214bc37259) | May 26, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [1cc5f44e4a](https://bsd-hardware.info/?probe=1cc5f44e4a) | May 25, 2022 |
| Protectli     | FW6                         | Desktop     | [0dc7509652](https://bsd-hardware.info/?probe=0dc7509652) | May 24, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [ddaca5356c](https://bsd-hardware.info/?probe=ddaca5356c) | May 21, 2022 |
| Unknown       | Unknown                     | Desktop     | [7c260c2423](https://bsd-hardware.info/?probe=7c260c2423) | May 20, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [8f9e0896d7](https://bsd-hardware.info/?probe=8f9e0896d7) | May 12, 2022 |
| Dell          | 0X4N41 A01                  | Desktop     | [d1596f34bf](https://bsd-hardware.info/?probe=d1596f34bf) | May 12, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [6dfeb3d80d](https://bsd-hardware.info/?probe=6dfeb3d80d) | May 10, 2022 |
| Intel         | HURONRIVER                  | Desktop     | [515172b464](https://bsd-hardware.info/?probe=515172b464) | May 09, 2022 |
| PC Engines    | APU2                        | Desktop     | [a2b68686f0](https://bsd-hardware.info/?probe=a2b68686f0) | Apr 27, 2022 |
| Dell          | 0TP406                      | Desktop     | [775061bc83](https://bsd-hardware.info/?probe=775061bc83) | Apr 25, 2022 |
| Biostar       | H61MHV2                     | Desktop     | [7d9806d719](https://bsd-hardware.info/?probe=7d9806d719) | Apr 21, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [378021707a](https://bsd-hardware.info/?probe=378021707a) | Apr 17, 2022 |
| Sophos        | SG                          | Firewall    | [2b5126d5a1](https://bsd-hardware.info/?probe=2b5126d5a1) | Apr 09, 2022 |
| PC Engines    | apu4                        | Desktop     | [62df504364](https://bsd-hardware.info/?probe=62df504364) | Apr 09, 2022 |
| Sophos        | UTM                         | Firewall    | [37af5c0425](https://bsd-hardware.info/?probe=37af5c0425) | Apr 08, 2022 |
| Sophos        | UTM                         | Firewall    | [8e79b3e5bf](https://bsd-hardware.info/?probe=8e79b3e5bf) | Apr 07, 2022 |
| Deciso        | DEC2700 - OPNsense Appli... | Notebook    | [926afc7ac8](https://bsd-hardware.info/?probe=926afc7ac8) | Apr 07, 2022 |
| Dell          | 0TP406                      | Desktop     | [9a29305ef1](https://bsd-hardware.info/?probe=9a29305ef1) | Apr 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [b6b1ec9dc1](https://bsd-hardware.info/?probe=b6b1ec9dc1) | Mar 30, 2022 |
| Deciso        | Netboard A20                | Notebook    | [835d6c060f](https://bsd-hardware.info/?probe=835d6c060f) | Mar 25, 2022 |
| ASRockRack    | X570D4U-2L2T                | Desktop     | [7e042aa70d](https://bsd-hardware.info/?probe=7e042aa70d) | Mar 25, 2022 |
| Deciso        | Netboard A20                | Notebook    | [5a6b66aa01](https://bsd-hardware.info/?probe=5a6b66aa01) | Mar 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [abb17bcb42](https://bsd-hardware.info/?probe=abb17bcb42) | Mar 21, 2022 |
| Unknown       | Unknown                     | Desktop     | [1d97ecbc95](https://bsd-hardware.info/?probe=1d97ecbc95) | Mar 20, 2022 |
| Unknown       | Unknown                     | Desktop     | [e169892276](https://bsd-hardware.info/?probe=e169892276) | Mar 18, 2022 |
| Dell          | 0X4N41 A01                  | Desktop     | [456b55de38](https://bsd-hardware.info/?probe=456b55de38) | Mar 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [1ed23967fd](https://bsd-hardware.info/?probe=1ed23967fd) | Mar 17, 2022 |
| Dell          | 0X4N41 A01                  | Desktop     | [4d7d8fd92b](https://bsd-hardware.info/?probe=4d7d8fd92b) | Mar 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [95154c4898](https://bsd-hardware.info/?probe=95154c4898) | Mar 16, 2022 |
| ASUSTek       | N50Vc                       | Notebook    | [883ded6cb1](https://bsd-hardware.info/?probe=883ded6cb1) | Mar 15, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [dd57366224](https://bsd-hardware.info/?probe=dd57366224) | Mar 15, 2022 |
| PC Engines    | APU2                        | Desktop     | [6e5badb880](https://bsd-hardware.info/?probe=6e5badb880) | Mar 04, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [7da5182091](https://bsd-hardware.info/?probe=7da5182091) | Feb 27, 2022 |
| PC Engines    | APU2                        | Desktop     | [40ba1b35da](https://bsd-hardware.info/?probe=40ba1b35da) | Feb 24, 2022 |
| Shuttle       | DS77U                       | Notebook    | [1ca3d58dfc](https://bsd-hardware.info/?probe=1ca3d58dfc) | Feb 23, 2022 |
| Dell          | 0X4N41 A01                  | Desktop     | [fea17bcf92](https://bsd-hardware.info/?probe=fea17bcf92) | Feb 19, 2022 |
| PC Engines    | APU2                        | Desktop     | [547be2fb61](https://bsd-hardware.info/?probe=547be2fb61) | Feb 19, 2022 |
| Dell          | 0X4N41 A01                  | Desktop     | [a62eea5e4e](https://bsd-hardware.info/?probe=a62eea5e4e) | Feb 11, 2022 |
| Dell          | 0X4N41 A01                  | Desktop     | [55b7348a0c](https://bsd-hardware.info/?probe=55b7348a0c) | Feb 11, 2022 |
| PC Engines    | APU2                        | Desktop     | [566948b2c1](https://bsd-hardware.info/?probe=566948b2c1) | Feb 09, 2022 |
| Acer          | Aspire XC-885 V:1.1         | Desktop     | [76fadb9527](https://bsd-hardware.info/?probe=76fadb9527) | Feb 09, 2022 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [c2b43efb8f](https://bsd-hardware.info/?probe=c2b43efb8f) | Feb 07, 2022 |
| Supermicro    | X10SLL-F                    | Server      | [0fa41ad797](https://bsd-hardware.info/?probe=0fa41ad797) | Feb 06, 2022 |
| Lenovo        | ThinkPad X250 20CMCTO1WW    | Notebook    | [4ba527dc9b](https://bsd-hardware.info/?probe=4ba527dc9b) | Feb 06, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [d04ab1a7bf](https://bsd-hardware.info/?probe=d04ab1a7bf) | Feb 06, 2022 |
| HP            | ProLiant ML350p Gen8        | Desktop     | [7987f643d7](https://bsd-hardware.info/?probe=7987f643d7) | Feb 06, 2022 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [1878f5822c](https://bsd-hardware.info/?probe=1878f5822c) | Feb 06, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [b9ed6f82cc](https://bsd-hardware.info/?probe=b9ed6f82cc) | Feb 06, 2022 |
| HP            | ProLiant ML350p Gen8        | Desktop     | [b9e0021bfb](https://bsd-hardware.info/?probe=b9e0021bfb) | Feb 06, 2022 |
| ZOTAC         | ZBOX-CI327NANO-GS-01        | Mini pc     | [c6a0bd2277](https://bsd-hardware.info/?probe=c6a0bd2277) | Feb 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [000331f38e](https://bsd-hardware.info/?probe=000331f38e) | Jan 31, 2022 |
| Unknown       | Unknown                     | Desktop     | [74b8fc0269](https://bsd-hardware.info/?probe=74b8fc0269) | Jan 30, 2022 |
| ZOTAC         | ZBOX-CI327NANO-GS-01        | Mini pc     | [3e78e7eb38](https://bsd-hardware.info/?probe=3e78e7eb38) | Jan 30, 2022 |
| PC Engines    | apu4                        | Desktop     | [4f6a1c9c9a](https://bsd-hardware.info/?probe=4f6a1c9c9a) | Jan 25, 2022 |
| Unknown       | Unknown                     | Desktop     | [b572e30460](https://bsd-hardware.info/?probe=b572e30460) | Jan 19, 2022 |
| ASUSTek       | N50Vc                       | Notebook    | [468a2d7ab8](https://bsd-hardware.info/?probe=468a2d7ab8) | Jan 17, 2022 |
| Supermicro    | X10SLL-F                    | Server      | [b11f87a501](https://bsd-hardware.info/?probe=b11f87a501) | Jan 16, 2022 |
| HP            | 3396                        | Desktop     | [236ed20a86](https://bsd-hardware.info/?probe=236ed20a86) | Jan 11, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [6c895cb96f](https://bsd-hardware.info/?probe=6c895cb96f) | Jan 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [e38915ac8c](https://bsd-hardware.info/?probe=e38915ac8c) | Jan 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [0a82e095ee](https://bsd-hardware.info/?probe=0a82e095ee) | Jan 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [9c67eb6ecd](https://bsd-hardware.info/?probe=9c67eb6ecd) | Dec 30, 2021 |
| Casper        | EXCALIBUR G900              | Notebook    | [539cf08655](https://bsd-hardware.info/?probe=539cf08655) | Dec 24, 2021 |
| Gigabyte      | H97N-WIFI                   | Desktop     | [3ccd5eace4](https://bsd-hardware.info/?probe=3ccd5eace4) | Dec 15, 2021 |
| ASRock        | B550 Taichi                 | Desktop     | [ed2fd72332](https://bsd-hardware.info/?probe=ed2fd72332) | Dec 14, 2021 |
| PC Engines    | apu4                        | Desktop     | [a06765ebb1](https://bsd-hardware.info/?probe=a06765ebb1) | Dec 09, 2021 |
| Dell          | 0X4N41 A01                  | Desktop     | [015319ce8c](https://bsd-hardware.info/?probe=015319ce8c) | Dec 08, 2021 |
| Supermicro    | X11SDW-4C-TP13F             | Desktop     | [f424260bfa](https://bsd-hardware.info/?probe=f424260bfa) | Dec 03, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [8f9e9ddde5](https://bsd-hardware.info/?probe=8f9e9ddde5) | Dec 02, 2021 |
| ASRockRack    | X570D4U-2L2T                | Desktop     | [b35a4b529c](https://bsd-hardware.info/?probe=b35a4b529c) | Nov 22, 2021 |
| Intel         | HURONRIVER                  | Desktop     | [741fd0e126](https://bsd-hardware.info/?probe=741fd0e126) | Nov 13, 2021 |
| Dell          | 0X4N41 A01                  | Desktop     | [d08d7fde4a](https://bsd-hardware.info/?probe=d08d7fde4a) | Nov 13, 2021 |
| PC Engines    | apu4                        | Desktop     | [64cad2ccf6](https://bsd-hardware.info/?probe=64cad2ccf6) | Nov 08, 2021 |
| HP            | 3397                        | Desktop     | [3434fa8427](https://bsd-hardware.info/?probe=3434fa8427) | Nov 07, 2021 |
| HP            | 3397                        | Desktop     | [155eceb394](https://bsd-hardware.info/?probe=155eceb394) | Nov 07, 2021 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [cc8c604fa6](https://bsd-hardware.info/?probe=cc8c604fa6) | Nov 03, 2021 |
| BESSTAR Te... | GB7                         | Mini pc     | [45a2da748c](https://bsd-hardware.info/?probe=45a2da748c) | Oct 30, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [0fa0f325e9](https://bsd-hardware.info/?probe=0fa0f325e9) | Oct 28, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [15d56aee58](https://bsd-hardware.info/?probe=15d56aee58) | Oct 21, 2021 |
| Apple         | Mac-F221BEC8                | Desktop     | [cb2cc35e6c](https://bsd-hardware.info/?probe=cb2cc35e6c) | Oct 19, 2021 |
| Apple         | Mac-F221BEC8                | Desktop     | [4e91fa71b2](https://bsd-hardware.info/?probe=4e91fa71b2) | Oct 19, 2021 |
| Unknown       | Unknown                     | Desktop     | [734ec7d9fc](https://bsd-hardware.info/?probe=734ec7d9fc) | Oct 18, 2021 |
| Unknown       | Unknown                     | Desktop     | [4ecab88e78](https://bsd-hardware.info/?probe=4ecab88e78) | Oct 17, 2021 |
| ASRock        | A320M-ITX                   | Desktop     | [06a8c0d2ac](https://bsd-hardware.info/?probe=06a8c0d2ac) | Oct 08, 2021 |
| ASRock        | B550 Taichi                 | Desktop     | [7599775c70](https://bsd-hardware.info/?probe=7599775c70) | Oct 08, 2021 |
| PC Engines    | APU2                        | Desktop     | [7a21594bf7](https://bsd-hardware.info/?probe=7a21594bf7) | Oct 08, 2021 |
| PC Engines    | apu6                        | Desktop     | [a184c5f1b2](https://bsd-hardware.info/?probe=a184c5f1b2) | Oct 06, 2021 |
| PC Engines    | APU2                        | Desktop     | [d36e631149](https://bsd-hardware.info/?probe=d36e631149) | Oct 03, 2021 |
| Lenovo        | ThinkPad T490s 20NYS3TU0... | Notebook    | [d377309110](https://bsd-hardware.info/?probe=d377309110) | Oct 02, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [1038e3314d](https://bsd-hardware.info/?probe=1038e3314d) | Sep 21, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [2a54a0c338](https://bsd-hardware.info/?probe=2a54a0c338) | Sep 14, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [7979c87340](https://bsd-hardware.info/?probe=7979c87340) | Sep 14, 2021 |
| PC Engines    | apu4                        | Desktop     | [9557835b54](https://bsd-hardware.info/?probe=9557835b54) | Sep 09, 2021 |
| Gigabyte      | BRi3(H)-10110               | Desktop     | [9aa3540749](https://bsd-hardware.info/?probe=9aa3540749) | Sep 09, 2021 |
| Gigabyte      | X399 DESIGNARE EX-CF        | Desktop     | [a78cc6a11b](https://bsd-hardware.info/?probe=a78cc6a11b) | Sep 04, 2021 |
| ASRock        | A320M-ITX                   | Desktop     | [051ca0708f](https://bsd-hardware.info/?probe=051ca0708f) | Sep 03, 2021 |
| ASRock        | A320M-ITX                   | Desktop     | [23bccfa11c](https://bsd-hardware.info/?probe=23bccfa11c) | Sep 01, 2021 |
| ASUSTek       | P8Z77-V                     | Desktop     | [eb4948e855](https://bsd-hardware.info/?probe=eb4948e855) | Aug 31, 2021 |
| Unknown       | Unknown                     | Desktop     | [114a632ab4](https://bsd-hardware.info/?probe=114a632ab4) | Aug 30, 2021 |
| ASRock        | A320M-ITX                   | Desktop     | [b0339f73bc](https://bsd-hardware.info/?probe=b0339f73bc) | Aug 28, 2021 |
| Unknown       | Unknown                     | Desktop     | [5bb434cb3f](https://bsd-hardware.info/?probe=5bb434cb3f) | Aug 27, 2021 |
| ASRock        | A320M-ITX                   | Desktop     | [c28bfd784d](https://bsd-hardware.info/?probe=c28bfd784d) | Aug 27, 2021 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [47284b4819](https://bsd-hardware.info/?probe=47284b4819) | Aug 27, 2021 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [31b995146e](https://bsd-hardware.info/?probe=31b995146e) | Aug 25, 2021 |
| PC Engines    | apu4                        | Desktop     | [9f5ec6c23f](https://bsd-hardware.info/?probe=9f5ec6c23f) | Aug 23, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [1498417edf](https://bsd-hardware.info/?probe=1498417edf) | Aug 15, 2021 |
| PC Engines    | apu4                        | Desktop     | [514a974f68](https://bsd-hardware.info/?probe=514a974f68) | Aug 10, 2021 |
| PC Engines    | APU2                        | Desktop     | [823fdc32f0](https://bsd-hardware.info/?probe=823fdc32f0) | Aug 09, 2021 |
| ASRock        | J4105-ITX                   | Desktop     | [1ac35fcecf](https://bsd-hardware.info/?probe=1ac35fcecf) | Aug 08, 2021 |
| Supermicro    | A2SDi-4C-HLN4F              | Server      | [fa4ba34119](https://bsd-hardware.info/?probe=fa4ba34119) | Aug 07, 2021 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [9fe86991b5](https://bsd-hardware.info/?probe=9fe86991b5) | Aug 04, 2021 |
| Shuttle       | DS10U                       | Desktop     | [fa151322fc](https://bsd-hardware.info/?probe=fa151322fc) | Aug 03, 2021 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [772a9416ab](https://bsd-hardware.info/?probe=772a9416ab) | Aug 01, 2021 |
| PC Engines    | APU2                        | Desktop     | [4c2b89d2e6](https://bsd-hardware.info/?probe=4c2b89d2e6) | Jul 31, 2021 |
| Dell          | 0X4N41 A01                  | Desktop     | [a528966ab8](https://bsd-hardware.info/?probe=a528966ab8) | Jul 30, 2021 |
| Dell          | 0X4N41 A01                  | Desktop     | [51136572fc](https://bsd-hardware.info/?probe=51136572fc) | Jul 29, 2021 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [8a2efd6b5b](https://bsd-hardware.info/?probe=8a2efd6b5b) | Jul 25, 2021 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [fea747e9eb](https://bsd-hardware.info/?probe=fea747e9eb) | Jul 25, 2021 |
| CompuLab      | fitlet2                     | Mini pc     | [18ce49973d](https://bsd-hardware.info/?probe=18ce49973d) | Jul 24, 2021 |
| Dell          | 0X4N41 A01                  | Desktop     | [f29fab4508](https://bsd-hardware.info/?probe=f29fab4508) | Jul 23, 2021 |
| Dell          | 0X4N41 A01                  | Desktop     | [b7c3a2b2e4](https://bsd-hardware.info/?probe=b7c3a2b2e4) | Jul 23, 2021 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [89938d9a3a](https://bsd-hardware.info/?probe=89938d9a3a) | Jul 20, 2021 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [c2721a852b](https://bsd-hardware.info/?probe=c2721a852b) | Jul 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [85e94a1288](https://bsd-hardware.info/?probe=85e94a1288) | Jul 13, 2021 |
| Supermicro    | PDSML+                      | Desktop     | [f8a9ca42d6](https://bsd-hardware.info/?probe=f8a9ca42d6) | Jul 11, 2021 |
| PC Engines    | APU2                        | Desktop     | [fe77a10950](https://bsd-hardware.info/?probe=fe77a10950) | Jul 08, 2021 |
| Intel         | NUC7i7BNB J31145-302        | Mini pc     | [a54eaf1e7b](https://bsd-hardware.info/?probe=a54eaf1e7b) | Jun 28, 2021 |
| Protectli     | FW6                         | Desktop     | [c28479f624](https://bsd-hardware.info/?probe=c28479f624) | Jun 20, 2021 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [6efb43e299](https://bsd-hardware.info/?probe=6efb43e299) | Jun 18, 2021 |
| Protectli     | FW6                         | Desktop     | [36d53d9465](https://bsd-hardware.info/?probe=36d53d9465) | Jun 17, 2021 |
| Sophos        | SG                          | Firewall    | [48b4a02fef](https://bsd-hardware.info/?probe=48b4a02fef) | Jun 17, 2021 |
| Protectli     | FW6                         | Desktop     | [9579e972f2](https://bsd-hardware.info/?probe=9579e972f2) | Jun 13, 2021 |
| ASUSTek       | ROG STRIX Z370-I GAMING     | Desktop     | [15ba8e73e1](https://bsd-hardware.info/?probe=15ba8e73e1) | Jun 09, 2021 |
| PC Engines    | apu4                        | Desktop     | [7ffaed1505](https://bsd-hardware.info/?probe=7ffaed1505) | Jun 06, 2021 |
| Lenovo        | ThinkPad T420 4237A12       | Notebook    | [dc29d714d9](https://bsd-hardware.info/?probe=dc29d714d9) | Jun 02, 2021 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [74f5dbcf1b](https://bsd-hardware.info/?probe=74f5dbcf1b) | Jun 01, 2021 |
| ASUSTek       | UX31A                       | Notebook    | [67a6df2b68](https://bsd-hardware.info/?probe=67a6df2b68) | May 30, 2021 |
| PC Engines    | apu4                        | Desktop     | [aad3e6a309](https://bsd-hardware.info/?probe=aad3e6a309) | May 28, 2021 |
| Shuttle       | DS10U                       | Desktop     | [bd8bea4a6a](https://bsd-hardware.info/?probe=bd8bea4a6a) | May 27, 2021 |
| Fujitsu       | D3383-B1 S26361-D3383-B1... | Server      | [6460f775b0](https://bsd-hardware.info/?probe=6460f775b0) | May 25, 2021 |
| Fujitsu       | D3383-B1 S26361-D3383-B1... | Server      | [10a74a9200](https://bsd-hardware.info/?probe=10a74a9200) | May 25, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [b8b40dbc2d](https://bsd-hardware.info/?probe=b8b40dbc2d) | May 20, 2021 |
| Dell          | Latitude E6430              | Notebook    | [8d24817728](https://bsd-hardware.info/?probe=8d24817728) | May 19, 2021 |
| ASUSTek       | P9D-I Series                | Server      | [fe8dc15588](https://bsd-hardware.info/?probe=fe8dc15588) | May 17, 2021 |
| Sophos        | SG                          | Firewall    | [8d2f78f042](https://bsd-hardware.info/?probe=8d2f78f042) | May 16, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [ae3bb311de](https://bsd-hardware.info/?probe=ae3bb311de) | May 07, 2021 |
| ASRock        | X99M Extreme4               | Desktop     | [ef131c774d](https://bsd-hardware.info/?probe=ef131c774d) | May 02, 2021 |
| Lenovo        | 318E NOK                    | Desktop     | [115f2c7b35](https://bsd-hardware.info/?probe=115f2c7b35) | Apr 27, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [2b97986de1](https://bsd-hardware.info/?probe=2b97986de1) | Apr 21, 2021 |
| Unknown       | Unknown                     | Desktop     | [44e10ac014](https://bsd-hardware.info/?probe=44e10ac014) | Apr 19, 2021 |
| Sophos        | XG                          | Firewall    | [428b16a419](https://bsd-hardware.info/?probe=428b16a419) | Apr 14, 2021 |
| PC Engines    | APU2                        | Desktop     | [8b425e6086](https://bsd-hardware.info/?probe=8b425e6086) | Apr 08, 2021 |
| PC Engines    | APU2                        | Desktop     | [f261049b51](https://bsd-hardware.info/?probe=f261049b51) | Apr 07, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [beacf76b6a](https://bsd-hardware.info/?probe=beacf76b6a) | Mar 26, 2021 |
| Unknown       | Unknown                     | Desktop     | [09e3c55edf](https://bsd-hardware.info/?probe=09e3c55edf) | Mar 26, 2021 |
| HUAWEI        | MACH-WX9                    | Notebook    | [f7e09652d9](https://bsd-hardware.info/?probe=f7e09652d9) | Mar 25, 2021 |
| HUAWEI        | MACH-WX9                    | Notebook    | [f9fdc75b45](https://bsd-hardware.info/?probe=f9fdc75b45) | Mar 25, 2021 |
| PC Engines    | APU2                        | Desktop     | [6204024271](https://bsd-hardware.info/?probe=6204024271) | Mar 24, 2021 |
| PC Engines    | APU2                        | Desktop     | [b39d8ba487](https://bsd-hardware.info/?probe=b39d8ba487) | Mar 24, 2021 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [40ec36ad78](https://bsd-hardware.info/?probe=40ec36ad78) | Mar 18, 2021 |
| PC Engines    | apu4                        | Desktop     | [e10b5c92e9](https://bsd-hardware.info/?probe=e10b5c92e9) | Mar 16, 2021 |
| Unknown       | Unknown                     | Desktop     | [36f81afd88](https://bsd-hardware.info/?probe=36f81afd88) | Mar 13, 2021 |
| PC Engines    | apu4                        | Desktop     | [9268ee6857](https://bsd-hardware.info/?probe=9268ee6857) | Mar 13, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [acbc65fd42](https://bsd-hardware.info/?probe=acbc65fd42) | Mar 10, 2021 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [2c0b0d8eb0](https://bsd-hardware.info/?probe=2c0b0d8eb0) | Mar 09, 2021 |
| BESSTAR Te... | IB9                         | Desktop     | [6d455b5e28](https://bsd-hardware.info/?probe=6d455b5e28) | Mar 08, 2021 |
| PC Engines    | APU3                        | Desktop     | [cf397191d2](https://bsd-hardware.info/?probe=cf397191d2) | Mar 04, 2021 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [eb8428d5f3](https://bsd-hardware.info/?probe=eb8428d5f3) | Mar 01, 2021 |
| PC Engines    | APU2                        | Desktop     | [2ac1695054](https://bsd-hardware.info/?probe=2ac1695054) | Feb 28, 2021 |
| Unknown       | Unknown                     | Desktop     | [b6c6031b46](https://bsd-hardware.info/?probe=b6c6031b46) | Feb 27, 2021 |
| Sophos        | SG                          | Firewall    | [c7392a1f0d](https://bsd-hardware.info/?probe=c7392a1f0d) | Feb 23, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [a7d9aeda81](https://bsd-hardware.info/?probe=a7d9aeda81) | Feb 22, 2021 |
| Supermicro    | X10SDV-8C-TLN4F             | Server      | [636a269a2a](https://bsd-hardware.info/?probe=636a269a2a) | Feb 15, 2021 |
| ASUSTek       | Z170-K                      | Desktop     | [aa525de283](https://bsd-hardware.info/?probe=aa525de283) | Feb 13, 2021 |
| Unknown       | Unknown                     | Desktop     | [ad3998234a](https://bsd-hardware.info/?probe=ad3998234a) | Feb 11, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [5a0b61ac41](https://bsd-hardware.info/?probe=5a0b61ac41) | Feb 07, 2021 |
| PC Engines    | APU2                        | Desktop     | [836a3035f1](https://bsd-hardware.info/?probe=836a3035f1) | Feb 06, 2021 |
| Lenovo        | ThinkPad T430 2349H2G       | Notebook    | [229db16a93](https://bsd-hardware.info/?probe=229db16a93) | Feb 05, 2021 |
| PC Engines    | APU2                        | Desktop     | [4985fa31bf](https://bsd-hardware.info/?probe=4985fa31bf) | Feb 03, 2021 |
| PC Engines    | apu4                        | Desktop     | [c740c17c50](https://bsd-hardware.info/?probe=c740c17c50) | Feb 01, 2021 |
| Supermicro    | A2SDi-4C-HLN4F              | Server      | [db0ed2b3c2](https://bsd-hardware.info/?probe=db0ed2b3c2) | Jan 31, 2021 |
| YANYU         | D19SL_B                     | Desktop     | [d16128eed9](https://bsd-hardware.info/?probe=d16128eed9) | Jan 28, 2021 |
| Unknown       | Unknown                     | Desktop     | [d2895512c0](https://bsd-hardware.info/?probe=d2895512c0) | Jan 27, 2021 |
| Unknown       | Unknown                     | Desktop     | [b936d5a273](https://bsd-hardware.info/?probe=b936d5a273) | Jan 27, 2021 |
| PC Engines    | APU2                        | Desktop     | [3448eacd29](https://bsd-hardware.info/?probe=3448eacd29) | Jan 24, 2021 |
| PC Engines    | APU2                        | Desktop     | [72e0243d73](https://bsd-hardware.info/?probe=72e0243d73) | Jan 23, 2021 |
| Sun           | SUNW,Sun-Blade-1500         | Desktop     | [647618a0ca](https://bsd-hardware.info/?probe=647618a0ca) | Jan 22, 2021 |
| PC Engines    | APU2                        | Desktop     | [c6c764813a](https://bsd-hardware.info/?probe=c6c764813a) | Jan 21, 2021 |
| PC Engines    | APU2                        | Desktop     | [bf1b93e96d](https://bsd-hardware.info/?probe=bf1b93e96d) | Jan 21, 2021 |
| Supermicro    | A1SRi 123456789             | Mini pc     | [cf9cb3dfcf](https://bsd-hardware.info/?probe=cf9cb3dfcf) | Jan 20, 2021 |
| ADI Engine... | RCC                         | Desktop     | [199da8eab6](https://bsd-hardware.info/?probe=199da8eab6) | Jan 20, 2021 |
| Supermicro    | A2SDi-4C-HLN4F              | Server      | [3d1e915a1b](https://bsd-hardware.info/?probe=3d1e915a1b) | Jan 19, 2021 |
| Supermicro    | A2SDi-4C-HLN4F              | Server      | [39f883b288](https://bsd-hardware.info/?probe=39f883b288) | Jan 19, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [9458fbeb87](https://bsd-hardware.info/?probe=9458fbeb87) | Jan 19, 2021 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [c107103d53](https://bsd-hardware.info/?probe=c107103d53) | Jan 19, 2021 |
| Sun           | SUNW,Sun-Blade-100          | Desktop     | [299c76eb85](https://bsd-hardware.info/?probe=299c76eb85) | Jan 18, 2021 |
| HP            | 1495                        | Desktop     | [2606547041](https://bsd-hardware.info/?probe=2606547041) | Dec 22, 2020 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [de35ebc178](https://bsd-hardware.info/?probe=de35ebc178) | Dec 04, 2020 |
| Lenovo        | Yoga 720-13IKB 81C3         | Notebook    | [467a6fc001](https://bsd-hardware.info/?probe=467a6fc001) | Nov 26, 2020 |
| HP            | EliteBook 840 G3            | Notebook    | [e44b010bc9](https://bsd-hardware.info/?probe=e44b010bc9) | Nov 11, 2020 |
| HP            | EliteBook 840 G3            | Notebook    | [2fb1bc911f](https://bsd-hardware.info/?probe=2fb1bc911f) | Nov 11, 2020 |
| Lenovo        | Yoga 720-13IKB 81C3         | Notebook    | [bdc2de68ce](https://bsd-hardware.info/?probe=bdc2de68ce) | Nov 05, 2020 |
| Lenovo        | Yoga 720-13IKB 81C3         | Notebook    | [8cfb32120b](https://bsd-hardware.info/?probe=8cfb32120b) | Nov 05, 2020 |
| PC Engines    | APU2                        | Desktop     | [e6ee8a14d5](https://bsd-hardware.info/?probe=e6ee8a14d5) | Oct 20, 2020 |
| PC Engines    | apu4                        | Desktop     | [e4cd6d0b48](https://bsd-hardware.info/?probe=e4cd6d0b48) | Oct 19, 2020 |
| Acer          | Aspire E1-532               | Notebook    | [10bff44534](https://bsd-hardware.info/?probe=10bff44534) | Oct 07, 2020 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [94a279c84d](https://bsd-hardware.info/?probe=94a279c84d) | Sep 03, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [2dd2bb5d60](https://bsd-hardware.info/?probe=2dd2bb5d60) | Aug 20, 2020 |
| Dell          | Precision M6600             | Notebook    | [b6c974b8bd](https://bsd-hardware.info/?probe=b6c974b8bd) | Aug 19, 2020 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [840b12f1f9](https://bsd-hardware.info/?probe=840b12f1f9) | Aug 09, 2020 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [c4454eaa39](https://bsd-hardware.info/?probe=c4454eaa39) | Aug 09, 2020 |
| Dell          | Precision M6600             | Notebook    | [da6f06315a](https://bsd-hardware.info/?probe=da6f06315a) | Aug 06, 2020 |
| Gigabyte      | H67A-UD3H-B3                | Desktop     | [aa29eb9c75](https://bsd-hardware.info/?probe=aa29eb9c75) | Aug 01, 2020 |
| HUAWEI        | MACH-WX9                    | Notebook    | [455ba9f0a8](https://bsd-hardware.info/?probe=455ba9f0a8) | Jul 20, 2020 |
| PC Engines    | apu4                        | Desktop     | [52c611855b](https://bsd-hardware.info/?probe=52c611855b) | Jul 12, 2020 |
| HP            | 158A                        | Desktop     | [dfff5dd2f9](https://bsd-hardware.info/?probe=dfff5dd2f9) | Jun 09, 2020 |
| Panasonic     | CF-19ADUAX1M                | Notebook    | [cefc742c62](https://bsd-hardware.info/?probe=cefc742c62) | May 29, 2020 |
| Unknown       | Unknown                     | Desktop     | [80a1eda96f](https://bsd-hardware.info/?probe=80a1eda96f) | May 28, 2020 |
| ASUSTek       | H81M-C                      | Desktop     | [d65f5372ec](https://bsd-hardware.info/?probe=d65f5372ec) | May 26, 2020 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [b43db1d84e](https://bsd-hardware.info/?probe=b43db1d84e) | May 25, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Switzerland/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart_bsd/os_name.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| OPNsense 24.1.1  | 8         | 1.84%   |
| OPNsense 22.1.8  | 8         | 1.84%   |
| OPNsense 21.7.1  | 8         | 1.84%   |
| OPNsense 20.7.8  | 8         | 1.84%   |
| OPNsense 23.1    | 7         | 1.61%   |
| OPNsense 22.7    | 7         | 1.61%   |
| OPNsense 21.7.3  | 7         | 1.61%   |
| OPNsense 21.1.6  | 7         | 1.61%   |
| OPNsense 24.7.4  | 6         | 1.38%   |
| OPNsense 24.7.10 | 6         | 1.38%   |
| OPNsense 23.7.1  | 6         | 1.38%   |
| OPNsense 23.1.1  | 6         | 1.38%   |
| OPNsense 22.7.4  | 6         | 1.38%   |
| OPNsense 22.7.10 | 6         | 1.38%   |
| OPNsense 21.1    | 6         | 1.38%   |
| FreeBSD 14.0-p6  | 6         | 1.38%   |
| OPNsense 24.1.7  | 5         | 1.15%   |
| OPNsense 23.1.7  | 5         | 1.15%   |
| OPNsense 23.1.11 | 5         | 1.15%   |
| OPNsense 21.7.7  | 5         | 1.15%   |
| OPNsense 21.7.6  | 5         | 1.15%   |
| OPNsense 21.1.5  | 5         | 1.15%   |
| OpenBSD 6.8      | 5         | 1.15%   |
| FreeBSD 13.0-p7  | 5         | 1.15%   |
| OPNsense 24.7.8  | 4         | 0.92%   |
| OPNsense 24.7.7  | 4         | 0.92%   |
| OPNsense 24.7.6  | 4         | 0.92%   |
| OPNsense 24.7.5  | 4         | 0.92%   |
| OPNsense 24.1.8  | 4         | 0.92%   |
| OPNsense 24.1.3  | 4         | 0.92%   |
| OPNsense 23.7.6  | 4         | 0.92%   |
| OPNsense 23.7.5  | 4         | 0.92%   |
| OPNsense 23.7.10 | 4         | 0.92%   |
| OPNsense 23.1.5  | 4         | 0.92%   |
| OPNsense 22.1.6  | 4         | 0.92%   |
| OPNsense 22.1.3  | 4         | 0.92%   |
| OPNsense 22.1.1  | 4         | 0.92%   |
| OPNsense 22.1    | 4         | 0.92%   |
| OPNsense 21.1.3  | 4         | 0.92%   |
| OPNsense 21.1.2  | 4         | 0.92%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 215       | 68.47%  |
| FreeBSD     | 54        | 17.2%   |
| OpenBSD     | 16        | 5.1%    |
| helloSystem | 14        | 4.46%   |
| GhostBSD    | 10        | 3.18%   |
| NomadBSD    | 3         | 0.96%   |
| TrueNAS     | 2         | 0.64%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| amd64   | 306       | 98.39%  |
| sparc64 | 2         | 0.64%   |
| arm64   | 2         | 0.64%   |
| i386    | 1         | 0.32%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 245       | 77.29%  |
| helloDesktop  | 18        | 5.68%   |
| XFCE          | 10        | 3.15%   |
| MATE          | 10        | 3.15%   |
| KDE5          | 8         | 2.52%   |
| i3            | 5         | 1.58%   |
| fvwm          | 5         | 1.58%   |
| TWM           | 4         | 1.26%   |
| GNOME         | 4         | 1.26%   |
| LXQt          | 2         | 0.63%   |
| wlroots       | 1         | 0.32%   |
| Openbox       | 1         | 0.32%   |
| LXDE          | 1         | 0.32%   |
| Enlightenment | 1         | 0.32%   |
| CDE           | 1         | 0.32%   |
| AwesomeWM     | 1         | 0.32%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 250       | 79.37%  |
| X11     | 58        | 18.41%  |
| Wayland | 7         | 2.22%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 265       | 83.86%  |
| SLiM    | 20        | 6.33%   |
| LightDM | 14        | 4.43%   |
| SDDM    | 7         | 2.22%   |
| Ly      | 5         | 1.58%   |
| GDM     | 3         | 0.95%   |
| XDM     | 2         | 0.63%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 237       | 74.29%  |
| C       | 43        | 13.48%  |
| en_US   | 25        | 7.84%   |
| de_CH   | 5         | 1.57%   |
| ru_RU   | 3         | 0.94%   |
| de_DE   | 3         | 0.94%   |
| fr_FR   | 2         | 0.63%   |
| fi_FI   | 1         | 0.31%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 282       | 90.38%  |
| BIOS | 30        | 9.62%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Zfs    | 154       | 48.13%  |
| Ufs    | 144       | 45%     |
| Ffs    | 16        | 5%      |
| Cd9660 | 6         | 1.88%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 292       | 93.59%  |
| MBR     | 18        | 5.77%   |
| Unknown | 2         | 0.64%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| PC Engines                           | 42        | 13.5%   |
| Unknown                              | 35        | 11.25%  |
| Lenovo                               | 26        | 8.36%   |
| Supermicro                           | 21        | 6.75%   |
| ASUSTek Computer                     | 21        | 6.75%   |
| Hewlett-Packard                      | 16        | 5.14%   |
| Dell                                 | 14        | 4.5%    |
| Deciso                               | 13        | 4.18%   |
| Sophos                               | 12        | 3.86%   |
| Intel                                | 12        | 3.86%   |
| Apple                                | 11        | 3.54%   |
| Shuttle                              | 9         | 2.89%   |
| Gigabyte Technology                  | 9         | 2.89%   |
| ASRock                               | 9         | 2.89%   |
| Protectli                            | 8         | 2.57%   |
| Techvision                           | 4         | 1.29%   |
| GoWin Solution                       | 4         | 1.29%   |
| Acer                                 | 4         | 1.29%   |
| ZOTAC                                | 3         | 0.96%   |
| Fujitsu                              | 3         | 0.96%   |
| BESSTAR Tech                         | 3         | 0.96%   |
| Sun                                  | 2         | 0.64%   |
| Shenzhen Meigao Electronic Equipment | 2         | 0.64%   |
| HUAWEI                               | 2         | 0.64%   |
| CheckPoint                           | 2         | 0.64%   |
| ASRockRack                           | 2         | 0.64%   |
| AMI                                  | 2         | 0.64%   |
| YANYU                                | 1         | 0.32%   |
| Yanling                              | 1         | 0.32%   |
| TUXEDO                               | 1         | 0.32%   |
| Trigkey                              | 1         | 0.32%   |
| Silicom                              | 1         | 0.32%   |
| Seco                                 | 1         | 0.32%   |
| Raspberry Pi Foundation              | 1         | 0.32%   |
| Panasonic                            | 1         | 0.32%   |
| MW                                   | 1         | 0.32%   |
| LinuxContainers                      | 1         | 0.32%   |
| Intel BOX4A200                       | 1         | 0.32%   |
| Infoblox                             | 1         | 0.32%   |
| IGEL Technology                      | 1         | 0.32%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                              | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown                                           | 35        | 11.25%  |
| PC Engines APU2                                   | 22        | 7.07%   |
| PC Engines apu4                                   | 14        | 4.5%    |
| Sophos SG                                         | 8         | 2.57%   |
| Deciso NetBoard-A20                               | 6         | 1.93%   |
| Supermicro Super Server                           | 5         | 1.61%   |
| Techvision TVI7309X                               | 4         | 1.29%   |
| Deciso DEC2700 - OPNsense Appliance               | 4         | 1.29%   |
| Sophos XG                                         | 3         | 0.96%   |
| Protectli FW6                                     | 3         | 0.96%   |
| PC Engines APU                                    | 3         | 0.96%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS                | 3         | 0.96%   |
| Lenovo Yoga 900S-12ISK 80ML                       | 3         | 0.96%   |
| GoWin Solution R86S                               | 3         | 0.96%   |
| ASUS All Series                                   | 3         | 0.96%   |
| ASRock A320M-ITX                                  | 3         | 0.96%   |
| Supermicro A1SAi                                  | 2         | 0.64%   |
| Shuttle DS10U                                     | 2         | 0.64%   |
| Shuttle DL30N                                     | 2         | 0.64%   |
| Shenzhen Meigao Electronic Equipment Venus Series | 2         | 0.64%   |
| PC Engines apu6                                   | 2         | 0.64%   |
| Intel NUC9i7QNX                                   | 2         | 0.64%   |
| HUAWEI MACH-WX9                                   | 2         | 0.64%   |
| HP Compaq 8200 Elite CMT PC                       | 2         | 0.64%   |
| Fujitsu PRIMERGY RX2530 M5                        | 2         | 0.64%   |
| Dell Precision 3440                               | 2         | 0.64%   |
| Dell PowerEdge T640                               | 2         | 0.64%   |
| Deciso Netboard A20                               | 2         | 0.64%   |
| CheckPoint PB-10-00                               | 2         | 0.64%   |
| BESSTAR Tech GK41                                 | 2         | 0.64%   |
| ASRock B550 Taichi                                | 2         | 0.64%   |
| Apple MacPro5,1                                   | 2         | 0.64%   |
| ZOTAC ZBOX-CI337NANO                              | 1         | 0.32%   |
| ZOTAC ZBOX-CI327NANO-GS-01                        | 1         | 0.32%   |
| ZOTAC ZBOX-CI320NANO series                       | 1         | 0.32%   |
| YANYU D19SL_B                                     | 1         | 0.32%   |
| Yanling YL-KBR6L                                  | 1         | 0.32%   |
| TUXEDO InfinityBook Pro AMD Gen9                  | 1         | 0.32%   |
| Trigkey Green G5                                  | 1         | 0.32%   |
| Supermicro X9SCL/X9SCM                            | 1         | 0.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 35        | 11.25%  |
| PC Engines APU2                            | 22        | 7.07%   |
| Lenovo ThinkPad                            | 15        | 4.82%   |
| PC Engines apu4                            | 14        | 4.5%    |
| Sophos SG                                  | 8         | 2.57%   |
| Lenovo Yoga                                | 8         | 2.57%   |
| Deciso NetBoard-A20                        | 6         | 1.93%   |
| Supermicro Super                           | 5         | 1.61%   |
| HP Compaq                                  | 5         | 1.61%   |
| Techvision TVI7309X                        | 4         | 1.29%   |
| HP EliteBook                               | 4         | 1.29%   |
| Dell PowerEdge                             | 4         | 1.29%   |
| Deciso DEC2700                             | 4         | 1.29%   |
| Acer Aspire                                | 4         | 1.29%   |
| Sophos XG                                  | 3         | 0.96%   |
| Protectli FW6                              | 3         | 0.96%   |
| PC Engines APU                             | 3         | 0.96%   |
| HP ProLiant                                | 3         | 0.96%   |
| GoWin Solution R86S                        | 3         | 0.96%   |
| Dell Precision                             | 3         | 0.96%   |
| Dell OptiPlex                              | 3         | 0.96%   |
| ASUS TUF                                   | 3         | 0.96%   |
| ASUS All                                   | 3         | 0.96%   |
| ASRock A320M-ITX                           | 3         | 0.96%   |
| Supermicro A1SAi                           | 2         | 0.64%   |
| Sun SUNW                                   | 2         | 0.64%   |
| Shuttle DS10U                              | 2         | 0.64%   |
| Shuttle DL30N                              | 2         | 0.64%   |
| Shenzhen Meigao Electronic Equipment Venus | 2         | 0.64%   |
| PC Engines apu6                            | 2         | 0.64%   |
| Intel NUC9i7QNX                            | 2         | 0.64%   |
| HUAWEI MACH-WX9                            | 2         | 0.64%   |
| Fujitsu PRIMERGY                           | 2         | 0.64%   |
| Dell XPS                                   | 2         | 0.64%   |
| Deciso Netboard                            | 2         | 0.64%   |
| CheckPoint PB-10-00                        | 2         | 0.64%   |
| BESSTAR Tech GK41                          | 2         | 0.64%   |
| ASUS PRIME                                 | 2         | 0.64%   |
| ASRock B550                                | 2         | 0.64%   |
| Apple MacPro5                              | 2         | 0.64%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2016    | 38        | 12.22%  |
| 2018    | 37        | 11.9%   |
| 2021    | 32        | 10.29%  |
| 2020    | 30        | 9.65%   |
| 2022    | 29        | 9.32%   |
| 2023    | 19        | 6.11%   |
| 2019    | 19        | 6.11%   |
| 2017    | 18        | 5.79%   |
| 2014    | 18        | 5.79%   |
| 2015    | 16        | 5.14%   |
| 2012    | 15        | 4.82%   |
| 2013    | 12        | 3.86%   |
| 2024    | 9         | 2.89%   |
| 2011    | 9         | 2.89%   |
| Unknown | 5         | 1.61%   |
| 2008    | 2         | 0.64%   |
| 2010    | 1         | 0.32%   |
| 2009    | 1         | 0.32%   |
| 2007    | 1         | 0.32%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 189       | 60.77%  |
| Notebook       | 65        | 20.9%   |
| Mini pc        | 20        | 6.43%   |
| Server         | 18        | 5.79%   |
| Firewall       | 14        | 4.5%    |
| System on chip | 2         | 0.64%   |
| All in one     | 2         | 0.64%   |
| Convertible    | 1         | 0.32%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 264       | 84.89%  |
| Yes  | 47        | 15.11%  |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 91        | 28.62%  |
| 16.01-24.0      | 87        | 27.36%  |
| 4.01-8.0        | 61        | 19.18%  |
| 32.01-64.0      | 47        | 14.78%  |
| 64.01-256.0     | 19        | 5.97%   |
| 2.01-3.0        | 4         | 1.26%   |
| More than 256.0 | 2         | 0.63%   |
| 1.01-2.0        | 2         | 0.63%   |
| 0.51-1.0        | 2         | 0.63%   |
| 3.01-4.0        | 1         | 0.31%   |
| 0.01-0.5        | 1         | 0.31%   |
| Unknown         | 1         | 0.31%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 135       | 41.67%  |
| 0.51-1.0    | 100       | 30.86%  |
| 1.01-2.0    | 51        | 15.74%  |
| 2.01-3.0    | 18        | 5.56%   |
| 4.01-8.0    | 6         | 1.85%   |
| 3.01-4.0    | 5         | 1.54%   |
| 0           | 3         | 0.93%   |
| 16.01-24.0  | 2         | 0.62%   |
| 8.01-16.0   | 2         | 0.62%   |
| 64.01-256.0 | 1         | 0.31%   |
| Unknown     | 1         | 0.31%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 211       | 65.94%  |
| 0      | 55        | 17.19%  |
| 2      | 32        | 10%     |
| 4      | 7         | 2.19%   |
| 3      | 5         | 1.56%   |
| 6      | 3         | 0.94%   |
| 5      | 3         | 0.94%   |
| 17     | 1         | 0.31%   |
| 16     | 1         | 0.31%   |
| 8      | 1         | 0.31%   |
| 7      | 1         | 0.31%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 274       | 87.82%  |
| Yes       | 38        | 12.18%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 296       | 94.87%  |
| No        | 16        | 5.13%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 213       | 68.05%  |
| Yes       | 100       | 31.95%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 230       | 73.48%  |
| Yes       | 83        | 26.52%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Switzerland | 311       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Zurich                   | 84        | 23.4%   |
| Geneva                   | 12        | 3.34%   |
| Winterthur               | 10        | 2.79%   |
| Lausanne                 | 10        | 2.79%   |
| Bern                     | 8         | 2.23%   |
| Basel                    | 8         | 2.23%   |
| Gachnang                 | 7         | 1.95%   |
| Horgen                   | 5         | 1.39%   |
| Gordola                  | 5         | 1.39%   |
| St. Moritz               | 4         | 1.11%   |
| Muttenz                  | 4         | 1.11%   |
| Lucerne                  | 4         | 1.11%   |
| Lenzburg                 | 4         | 1.11%   |
| Burgdorf                 | 4         | 1.11%   |
| St. Gallen               | 3         | 0.84%   |
| Riehen                   | 3         | 0.84%   |
| Niederbipp               | 3         | 0.84%   |
| Dietikon                 | 3         | 0.84%   |
| Zug                      | 2         | 0.56%   |
| Wallisellen              | 2         | 0.56%   |
| Therwil                  | 2         | 0.56%   |
| Tagelswangen             | 2         | 0.56%   |
| Steckborn                | 2         | 0.56%   |
| Siggenthal Station       | 2         | 0.56%   |
| Palezieux                | 2         | 0.56%   |
| Ottenbach                | 2         | 0.56%   |
| Onex                     | 2         | 0.56%   |
| Oensingen                | 2         | 0.56%   |
| Munchenstein             | 2         | 0.56%   |
| Moosseedorf              | 2         | 0.56%   |
| Mohlin                   | 2         | 0.56%   |
| Mettmenstetten           | 2         | 0.56%   |
| Maennedorf               | 2         | 0.56%   |
| Kolliken                 | 2         | 0.56%   |
| Hittnau / Hittnau (Dorf) | 2         | 0.56%   |
| Hildisrieden             | 2         | 0.56%   |
| Herisau                  | 2         | 0.56%   |
| Grenchen                 | 2         | 0.56%   |
| Glattbrugg               | 2         | 0.56%   |
| Gerlafingen              | 2         | 0.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 71        | 111    | 23.36%  |
| WDC                 | 31        | 68     | 10.2%   |
| Kingston            | 24        | 29     | 7.89%   |
| Intel               | 19        | 43     | 6.25%   |
| Transcend           | 17        | 26     | 5.59%   |
| Phison              | 15        | 19     | 4.93%   |
| Seagate             | 14        | 21     | 4.61%   |
| Crucial             | 12        | 20     | 3.95%   |
| China               | 12        | 15     | 3.95%   |
| Toshiba             | 7         | 8      | 2.3%    |
| SanDisk             | 7         | 13     | 2.3%    |
| SK hynix            | 6         | 8      | 1.97%   |
| Corsair             | 6         | 10     | 1.97%   |
| A-DATA Technology   | 6         | 9      | 1.97%   |
| Hoodisk             | 5         | 8      | 1.64%   |
| Apple               | 4         | 4      | 1.32%   |
| Silicon Motion      | 3         | 3      | 0.99%   |
| ShiJi               | 3         | 10     | 0.99%   |
| NVMe                | 3         | 3      | 0.99%   |
| HPT                 | 3         | 35     | 0.99%   |
| Hitachi             | 3         | 3      | 0.99%   |
| Fanxiang            | 3         | 3      | 0.99%   |
| Protectli           | 2         | 2      | 0.66%   |
| OCZ                 | 2         | 3      | 0.66%   |
| Micron Technology   | 2         | 3      | 0.66%   |
| KingSpec            | 2         | 2      | 0.66%   |
| Intenso             | 2         | 6      | 0.66%   |
| HGST                | 2         | 2      | 0.66%   |
| Hewlett-Packard     | 2         | 17     | 0.66%   |
| FTS                 | 2         | 2      | 0.66%   |
| FORESEE             | 2         | 3      | 0.66%   |
| VICK                | 1         | 1      | 0.33%   |
| Verbatim            | 1         | 2      | 0.33%   |
| USB                 | 1         | 1      | 0.33%   |
| SPCC                | 1         | 2      | 0.33%   |
| QEMU                | 1         | 1      | 0.33%   |
| PNY                 | 1         | 1      | 0.33%   |
| OPENBSD             | 1         | 1      | 0.33%   |
| LITEON              | 1         | 6      | 0.33%   |
| KIOXIA              | 1         | 1      | 0.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Phison SATA SSD 16GB                   | 10        | 2.79%   |
| Samsung SSD 860 EVO 250GB              | 7         | 1.96%   |
| Samsung SSD 850 PRO 256GB              | 5         | 1.4%    |
| Hoodisk SSD 32GB                       | 5         | 1.4%    |
| China SATA SSD 16GB                    | 5         | 1.4%    |
| Transcend TS256GMTS952T2 256GB         | 4         | 1.12%   |
| Transcend TS256GMTE710T 256GB          | 4         | 1.12%   |
| Samsung SSD 860 PRO 256GB              | 4         | 1.12%   |
| WDC WDS120G2G0B-00EPW0 120GB           | 3         | 0.84%   |
| SK hynix SKHynix_HFS512GDE9X081N 512GB | 3         | 0.84%   |
| ShiJi SSD 128GB                        | 3         | 0.84%   |
| Phison SATA SSD 32GB                   | 3         | 0.84%   |
| Kingston SKC600MS512G 512GB            | 3         | 0.84%   |
| Kingston RBUSNS8180DS3128GH 128GB      | 3         | 0.84%   |
| Intel SSDSA2BW160G3H 160GB             | 3         | 0.84%   |
| HPT DISK 0_3 1TB                       | 3         | 0.84%   |
| HPT DISK 0_2 1TB                       | 3         | 0.84%   |
| HPT DISK 0_1 1TB                       | 3         | 0.84%   |
| HPT DISK 0_0 4TB                       | 3         | 0.84%   |
| Fanxiang S501 128GB                    | 3         | 0.84%   |
| China SATA SSD 32GB                    | 3         | 0.84%   |
| WDC WDS240G2G0A-00JH30 240GB           | 2         | 0.56%   |
| WDC WD6002FRYZ-01WD5B1 6TB             | 2         | 0.56%   |
| WDC WD40EFPX-68C6CN0 4TB               | 2         | 0.56%   |
| WDC WD30EFRX-68EUZN0 3TB               | 2         | 0.56%   |
| WDC WD1000DHTZ-04N21V0 1TB             | 2         | 0.56%   |
| Transcend TS512GMTS952T2 512GB         | 2         | 0.56%   |
| Transcend TS128GMTE110S 128GB          | 2         | 0.56%   |
| SK hynix SC311 SATA 256GB              | 2         | 0.56%   |
| Seagate ST3500413AS 500GB              | 2         | 0.56%   |
| Seagate ST18000NE000-3G6101 18TB       | 2         | 0.56%   |
| SanDisk SSD U100 24GB                  | 2         | 0.56%   |
| Samsung SSD 980 PRO 500GB              | 2         | 0.56%   |
| Samsung SSD 980 PRO 250GB              | 2         | 0.56%   |
| Samsung SSD 970 EVO Plus 1TB           | 2         | 0.56%   |
| Samsung SSD 960 EVO 250GB              | 2         | 0.56%   |
| Samsung SSD 850 PRO 1TB                | 2         | 0.56%   |
| Samsung SSD 850 PRO 128GB              | 2         | 0.56%   |
| Samsung SSD 850 EVO 500GB              | 2         | 0.56%   |
| Samsung SSD 850 EVO 250GB              | 2         | 0.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 15        | 44     | 29.41%  |
| Seagate             | 13        | 20     | 25.49%  |
| Toshiba             | 4         | 5      | 7.84%   |
| HPT                 | 3         | 35     | 5.88%   |
| Hitachi             | 3         | 3      | 5.88%   |
| NVMe                | 2         | 2      | 3.92%   |
| HGST                | 2         | 2      | 3.92%   |
| Hewlett-Packard     | 2         | 13     | 3.92%   |
| Apple               | 2         | 2      | 3.92%   |
| USB                 | 1         | 1      | 1.96%   |
| Samsung Electronics | 1         | 1      | 1.96%   |
| QEMU                | 1         | 1      | 1.96%   |
| OPENBSD             | 1         | 1      | 1.96%   |
| China               | 1         | 1      | 1.96%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 50        | 78     | 25%     |
| Kingston            | 22        | 24     | 11%     |
| Intel               | 16        | 40     | 8%      |
| Phison              | 13        | 16     | 6.5%    |
| WDC                 | 11        | 17     | 5.5%    |
| China               | 11        | 14     | 5.5%    |
| Transcend           | 10        | 19     | 5%      |
| Crucial             | 10        | 18     | 5%      |
| SanDisk             | 7         | 13     | 3.5%    |
| A-DATA Technology   | 6         | 9      | 3%      |
| Hoodisk             | 5         | 8      | 2.5%    |
| Corsair             | 5         | 9      | 2.5%    |
| Toshiba             | 3         | 3      | 1.5%    |
| SK hynix            | 3         | 3      | 1.5%    |
| ShiJi               | 3         | 10     | 1.5%    |
| Protectli           | 2         | 2      | 1%      |
| OCZ                 | 2         | 3      | 1%      |
| Micron Technology   | 2         | 3      | 1%      |
| KingSpec            | 2         | 2      | 1%      |
| Intenso             | 2         | 6      | 1%      |
| Hewlett-Packard     | 2         | 4      | 1%      |
| FTS                 | 2         | 2      | 1%      |
| Apple               | 2         | 2      | 1%      |
| VICK                | 1         | 1      | 0.5%    |
| Verbatim            | 1         | 2      | 0.5%    |
| SPCC                | 1         | 2      | 0.5%    |
| Seagate             | 1         | 1      | 0.5%    |
| PNY                 | 1         | 1      | 0.5%    |
| NVMe                | 1         | 1      | 0.5%    |
| LITEON              | 1         | 6      | 0.5%    |
| FORESEE             | 1         | 1      | 0.5%    |
| BIWIN               | 1         | 1      | 0.5%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 188       | 321    | 65.05%  |
| NVMe | 59        | 77     | 20.42%  |
| HDD  | 42        | 131    | 14.53%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 208       | 452    | 77.9%   |
| NVMe | 59        | 77     | 22.1%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 182       | 311    | 74.29%  |
| 0.51-1.0   | 31        | 82     | 12.65%  |
| 1.01-2.0   | 12        | 21     | 4.9%    |
| 3.01-4.0   | 7         | 9      | 2.86%   |
| 2.01-3.0   | 7         | 15     | 2.86%   |
| 4.01-10.0  | 4         | 12     | 1.63%   |
| 10.01-20.0 | 2         | 2      | 0.82%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 150       | 46.01%  |
| 251-500        | 50        | 15.34%  |
| 1-20           | 41        | 12.58%  |
| 51-100         | 32        | 9.82%   |
| 501-1000       | 24        | 7.36%   |
| 21-50          | 22        | 6.75%   |
| 1001-2000      | 4         | 1.23%   |
| More than 3000 | 1         | 0.31%   |
| 2001-3000      | 1         | 0.31%   |
| Unknown        | 1         | 0.31%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 290       | 88.69%  |
| 21-50   | 20        | 6.12%   |
| 51-100  | 10        | 3.06%   |
| 101-250 | 4         | 1.22%   |
| 251-500 | 2         | 0.61%   |
| Unknown | 1         | 0.31%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                      | Computers | Drives | Percent |
|--------------------------------------------|-----------|--------|---------|
| Seagate ST3500413AS 500GB                  | 2         | 3      | 5.71%   |
| WDC WDS250G2B0B-00YS70 250GB               | 1         | 1      | 2.86%   |
| WDC WDS120G2G0A-00JH30 120GB               | 1         | 2      | 2.86%   |
| WDC WD6002FRYZ-01WD5B1 6TB                 | 1         | 6      | 2.86%   |
| WDC WD40EFRX-68WT0N0 4TB                   | 1         | 1      | 2.86%   |
| WDC WD30EFRX-68EUZN0 3TB                   | 1         | 1      | 2.86%   |
| WDC WD2002FYPS-01U1B0 2TB                  | 1         | 3      | 2.86%   |
| Toshiba MK1059GSM 1TB                      | 1         | 1      | 2.86%   |
| Seagate ST3500418AS 500GB                  | 1         | 2      | 2.86%   |
| Seagate ST2000VN004-2E4164 2TB             | 1         | 2      | 2.86%   |
| Samsung Electronics SSD 870 EVO 1TB        | 1         | 1      | 2.86%   |
| Samsung Electronics SSD 850 EVO mSATA 1TB  | 1         | 1      | 2.86%   |
| Samsung Electronics HD204UI 2TB            | 1         | 1      | 2.86%   |
| OCZ AGILITY3 240GB                         | 1         | 1      | 2.86%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB | 1         | 1      | 2.86%   |
| Kingston SV300S37A60G 64GB                 | 1         | 1      | 2.86%   |
| Kingston SV300S37A120G 120GB               | 1         | 1      | 2.86%   |
| Kingston SH103S3120G 120GB                 | 1         | 1      | 2.86%   |
| Intenso SSD Sata III 248GB                 | 1         | 1      | 2.86%   |
| Intel SSDSCKKF256G8H 256GB                 | 1         | 2      | 2.86%   |
| Intel SSDSC2CT240A4 240GB                  | 1         | 1      | 2.86%   |
| Intel SSDSC2BW480A4 480GB                  | 1         | 2      | 2.86%   |
| Intel SSDSC2BW240A4 240GB                  | 1         | 2      | 2.86%   |
| Intel SSDSC2BW120H6 120GB                  | 1         | 1      | 2.86%   |
| Intel SSDSA2M160G2GC 160GB                 | 1         | 2      | 2.86%   |
| Intel SSDSA2M120G2GC 120GB                 | 1         | 1      | 2.86%   |
| Intel SSDSA2BW160G3H 160GB                 | 1         | 5      | 2.86%   |
| Hitachi HDS721050CLA660 500GB              | 1         | 1      | 2.86%   |
| HGST HUS726020ALE614 2TB                   | 1         | 1      | 2.86%   |
| HGST HTE725032A7E630 320GB                 | 1         | 1      | 2.86%   |
| Crucial CT480M500SSD1 480GB                | 1         | 1      | 2.86%   |
| Crucial CT256MX100SSD1 256GB               | 1         | 2      | 2.86%   |
| Corsair Force 3 SSD 120GB                  | 1         | 2      | 2.86%   |
| Corsair CSSD-F120GB2                       | 1         | 2      | 2.86%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Intel               | 8         | 16     | 24.24%  |
| WDC                 | 5         | 14     | 15.15%  |
| Seagate             | 3         | 7      | 9.09%   |
| Samsung Electronics | 3         | 3      | 9.09%   |
| Kingston            | 3         | 3      | 9.09%   |
| HGST                | 2         | 2      | 6.06%   |
| Crucial             | 2         | 3      | 6.06%   |
| Corsair             | 2         | 4      | 6.06%   |
| Toshiba             | 1         | 1      | 3.03%   |
| OCZ                 | 1         | 1      | 3.03%   |
| Micron Technology   | 1         | 1      | 3.03%   |
| Intenso             | 1         | 1      | 3.03%   |
| Hitachi             | 1         | 1      | 3.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 11     | 27.27%  |
| Seagate             | 3         | 7      | 27.27%  |
| HGST                | 2         | 2      | 18.18%  |
| Toshiba             | 1         | 1      | 9.09%   |
| Samsung Electronics | 1         | 1      | 9.09%   |
| Hitachi             | 1         | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 22        | 34     | 70.97%  |
| HDD  | 9         | 23     | 29.03%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart_bsd/drive_failed.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Samsung Electronics MZVLW256HEHP-000L7 256GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 232       | 418    | 84.06%  |
| Malfunc  | 30        | 57     | 10.87%  |
| Detected | 13        | 53     | 4.71%   |
| Failed   | 1         | 1      | 0.36%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 195       | 50.78%  |
| AMD                          | 72        | 18.75%  |
| Samsung Electronics          | 34        | 8.85%   |
| Silicon Motion               | 11        | 2.86%   |
| SanDisk                      | 10        | 2.6%    |
| Transcend                    | 7         | 1.82%   |
| Broadcom / LSI               | 7         | 1.82%   |
| Kingston Technology Company  | 6         | 1.56%   |
| SK hynix                     | 4         | 1.04%   |
| Phison Electronics           | 4         | 1.04%   |
| Micron/Crucial Technology    | 4         | 1.04%   |
| Marvell Technology Group     | 4         | 1.04%   |
| ASMedia Technology           | 4         | 1.04%   |
| MAXIO Technology (Hangzhou)  | 3         | 0.78%   |
| HighPoint Technologies       | 3         | 0.78%   |
| ULi Electronics              | 2         | 0.52%   |
| Toshiba                      | 2         | 0.52%   |
| KIOXIA                       | 2         | 0.52%   |
| JMicron Technology           | 2         | 0.52%   |
| Hewlett-Packard              | 2         | 0.52%   |
| Chelsio Communications       | 2         | 0.52%   |
| Shenzhen Longsys Electronics | 1         | 0.26%   |
| Red Hat                      | 1         | 0.26%   |
| Nvidia                       | 1         | 0.26%   |
| Micron Technology            | 1         | 0.26%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 47        | 11.11%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 18        | 4.26%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 12        | 2.84%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 11        | 2.6%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 11        | 2.6%    |
| AMD FCH SATA Controller [IDE mode]                                             | 11        | 2.6%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 10        | 2.36%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 10        | 2.36%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                  | 10        | 2.36%   |
| Intel Alder Lake-N SATA AHCI Controller                                        | 10        | 2.36%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 8         | 1.89%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 8         | 1.89%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 8         | 1.89%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 8         | 1.89%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 7         | 1.65%   |
| Intel Comet Lake SATA AHCI Controller                                          | 7         | 1.65%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                   | 7         | 1.65%   |
| Intel Atom Processor C3000 Series SATA Controller 1                            | 7         | 1.65%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                               | 7         | 1.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 7         | 1.65%   |
| AMD 500 Series Chipset SATA Controller                                         | 7         | 1.65%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 6         | 1.42%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 5         | 1.18%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 5         | 1.18%   |
| Intel Atom Processor C3000 Series SATA Controller 0                            | 5         | 1.18%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 5         | 1.18%   |
| Transcend NVMe PCIe SSD 220S/240S/MTE710T                                      | 4         | 0.95%   |
| Intel Atom processor C2000 AHCI SATA2 Controller                               | 4         | 0.95%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 0.95%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 4         | 0.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4         | 0.95%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 3         | 0.71%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 3         | 0.71%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 3         | 0.71%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 3         | 0.71%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 3         | 0.71%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller          | 3         | 0.71%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 0.71%   |
| Intel SATA Controller [RAID mode]                                              | 3         | 0.71%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 3         | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 247       | 65%     |
| NVMe | 87        | 22.89%  |
| IDE  | 22        | 5.79%   |
| RAID | 18        | 4.74%   |
| SCSI | 4         | 1.05%   |
| SAS  | 2         | 0.53%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 222       | 71.15%  |
| AMD     | 85        | 27.24%  |
| ARM     | 2         | 0.64%   |
| Unknown | 2         | 0.64%   |
| QEMU    | 1         | 0.32%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| AMD GX-412TC SOC                            | 39        | 12.42%  |
| Intel N100                                  | 9         | 2.87%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 9         | 2.87%   |
| Intel Celeron N5105 @ 2.00GHz               | 5         | 1.59%   |
| AMD Ryzen Embedded V1500B                   | 5         | 1.59%   |
| AMD EPYC 3201 8-Core Processor              | 5         | 1.59%   |
| Intel Xeon D-2123IT CPU @ 2.20GHz           | 4         | 1.27%   |
| Intel Pentium Silver N6005 @ 2.00GHz        | 4         | 1.27%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 4         | 1.27%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 4         | 1.27%   |
| Intel Celeron CPU 3865U @ 1.80GHz           | 4         | 1.27%   |
| Intel Atom CPU C3758 @ 2.20GHz              | 4         | 1.27%   |
| Intel Atom CPU C2558 @ 2.40GHz              | 4         | 1.27%   |
| Intel Xeon Silver 4210 CPU @ 2.20GHz        | 3         | 0.96%   |
| Intel Core m7-6Y75 CPU @ 1.20GHz            | 3         | 0.96%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 3         | 0.96%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 3         | 0.96%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 3         | 0.96%   |
| Intel Core i3-N305                          | 3         | 0.96%   |
| AMD Ryzen 7 5800H with Radeon Graphics      | 3         | 0.96%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 3         | 0.96%   |
| AMD G-T40E Processor                        | 3         | 0.96%   |
| AMD EPYC 3101 4-Core Processor              | 3         | 0.96%   |
| Intel Xeon CPU X5650 @ 2.67GHz              | 2         | 0.64%   |
| Intel Xeon CPU D-1518 @ 2.20GHz             | 2         | 0.64%   |
| Intel Pentium CPU G3420 @ 3.20GHz           | 2         | 0.64%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 2         | 0.64%   |
| Intel Core i5-8365U CPU @ 1.60GHz           | 2         | 0.64%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 0.64%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 2         | 0.64%   |
| Intel Core i5-4570S CPU @ 2.90GHz           | 2         | 0.64%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2         | 0.64%   |
| Intel Core i5-3317U CPU @ 1.70GHz           | 2         | 0.64%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 2         | 0.64%   |
| Intel Core i5-10500 CPU @ 3.10GHz           | 2         | 0.64%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 2         | 0.64%   |
| Intel Core i3-10110U CPU @ 2.10GHz          | 2         | 0.64%   |
| Intel Celeron N5100 @ 1.10GHz               | 2         | 0.64%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 2         | 0.64%   |
| Intel Atom CPU C3558 @ 2.20GHz              | 2         | 0.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i5          | 47        | 15.02%  |
| AMD GX                 | 40        | 12.78%  |
| Intel Core i7          | 36        | 11.5%   |
| Intel Celeron          | 33        | 10.54%  |
| Intel Xeon             | 29        | 9.27%   |
| Other                  | 25        | 7.99%   |
| Intel Atom             | 19        | 6.07%   |
| Intel Core i3          | 16        | 5.11%   |
| AMD Ryzen 7            | 11        | 3.51%   |
| AMD EPYC               | 9         | 2.88%   |
| AMD Ryzen 5            | 6         | 1.92%   |
| Intel Pentium          | 5         | 1.6%    |
| AMD Ryzen Embedded     | 5         | 1.6%    |
| Intel Xeon Silver      | 4         | 1.28%   |
| Intel Pentium Silver   | 4         | 1.28%   |
| Intel Core 2 Duo       | 4         | 1.28%   |
| Intel Core m7          | 3         | 0.96%   |
| AMD Ryzen 7 PRO        | 3         | 0.96%   |
| AMD G                  | 3         | 0.96%   |
| ARM Cortex             | 2         | 0.64%   |
| AMD Ryzen 9            | 2         | 0.64%   |
| AMD Ryzen 3            | 2         | 0.64%   |
| Intel Pentium Gold     | 1         | 0.32%   |
| AMD Ryzen Threadripper | 1         | 0.32%   |
| AMD Opteron            | 1         | 0.32%   |
| AMD Geode Integrated   | 1         | 0.32%   |
| AMD FX                 | 1         | 0.32%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 164       | 52.06%  |
| 2       | 62        | 19.68%  |
| 8       | 37        | 11.75%  |
| 16      | 17        | 5.4%    |
| 6       | 11        | 3.49%   |
| 12      | 8         | 2.54%   |
| Unknown | 5         | 1.59%   |
| 1       | 4         | 1.27%   |
| 20      | 3         | 0.95%   |
| 24      | 2         | 0.63%   |
| 32      | 1         | 0.32%   |
| 10      | 1         | 0.32%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 297       | 95.19%  |
| 2       | 10        | 3.21%   |
| Unknown | 4         | 1.28%   |
| 4       | 1         | 0.32%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 189       | 60.38%  |
| 2       | 117       | 37.38%  |
| Unknown | 7         | 2.24%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Unknown       | 44        | 14.01%  |
| Puma          | 39        | 12.42%  |
| KabyLake      | 36        | 11.46%  |
| Skylake       | 28        | 8.92%   |
| Haswell       | 24        | 7.64%   |
| IvyBridge     | 22        | 7.01%   |
| Zen           | 17        | 5.41%   |
| Silvermont    | 14        | 4.46%   |
| SandyBridge   | 14        | 4.46%   |
| Goldmont      | 12        | 3.82%   |
| Zen 3         | 11        | 3.5%    |
| Goldmont plus | 11        | 3.5%    |
| Broadwell     | 8         | 2.55%   |
| Westmere      | 5         | 1.59%   |
| Zen+          | 3         | 0.96%   |
| Zen 2         | 3         | 0.96%   |
| TigerLake     | 3         | 0.96%   |
| Penryn        | 3         | 0.96%   |
| Core          | 3         | 0.96%   |
| CometLake     | 3         | 0.96%   |
| Bobcat        | 3         | 0.96%   |
| Nehalem       | 2         | 0.64%   |
| IceLake       | 2         | 0.64%   |
| Piledriver    | 1         | 0.32%   |
| Jaguar        | 1         | 0.32%   |
| Geode         | 1         | 0.32%   |
| Excavator     | 1         | 0.32%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 161       | 62.16%  |
| AMD                                          | 30        | 11.58%  |
| ASPEED Technology                            | 28        | 10.81%  |
| Nvidia                                       | 27        | 10.42%  |
| Matrox Electronics Systems                   | 10        | 3.86%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.39%   |
| Red Hat                                      | 1         | 0.39%   |
| 3DLabs                                       | 1         | 0.39%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                                 | 28        | 10.65%  |
| Intel Alder Lake-N [UHD Graphics]                                                        | 12        | 4.56%   |
| Intel JasperLake [UHD Graphics]                                                          | 11        | 4.18%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 11        | 4.18%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 3.8%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 9         | 3.42%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 9         | 3.42%   |
| Intel HD Graphics 530                                                                    | 8         | 3.04%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 8         | 3.04%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 2.28%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5         | 1.9%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 1.9%    |
| Intel UHD Graphics 620                                                                   | 5         | 1.9%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 1.9%    |
| Intel HD Graphics 610                                                                    | 4         | 1.52%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 1.52%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4         | 1.52%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 3         | 1.14%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.14%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 1.14%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.14%   |
| Intel HD Graphics 515                                                                    | 3         | 1.14%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.14%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 1.14%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.76%   |
| Matrox Electronics Systems MGA G200EH                                                    | 2         | 0.76%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 2         | 0.76%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller                 | 2         | 0.76%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 0.76%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2         | 0.76%   |
| Intel HD Graphics 620                                                                    | 2         | 0.76%   |
| Intel HD Graphics 510                                                                    | 2         | 0.76%   |
| Intel HD Graphics 500                                                                    | 2         | 0.76%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 0.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.76%   |
| Intel Alder Lake-UP3 GT2 [UHD Graphics]                                                  | 2         | 0.76%   |
| Intel Alder Lake-UP3 GT1 [UHD Graphics]                                                  | 2         | 0.76%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 2         | 0.76%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 0.76%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 2         | 0.76%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 151       | 48.24%  |
| Other           | 64        | 20.45%  |
| 1 x ASPEED      | 28        | 8.95%   |
| 1 x AMD         | 27        | 8.63%   |
| 1 x Nvidia      | 16        | 5.11%   |
| 1 x Matrox      | 9         | 2.88%   |
| Intel + Nvidia  | 8         | 2.56%   |
| 2 x AMD         | 2         | 0.64%   |
| 2 x Nvidia      | 1         | 0.32%   |
| 2 x Intel       | 1         | 0.32%   |
| 1 x XGI         | 1         | 0.32%   |
| 1 x Red Hat     | 1         | 0.32%   |
| Nvidia + Matrox | 1         | 0.32%   |
| Intel + AMD     | 1         | 0.32%   |
| AMD + Nvidia    | 1         | 0.32%   |
| 1 x 3DLabs      | 1         | 0.32%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 228       | 73.31%  |
| Unknown     | 71        | 22.83%  |
| Proprietary | 12        | 3.86%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 294       | 93.33%  |
| 1.01-2.0   | 8         | 2.54%   |
| 3.01-4.0   | 3         | 0.95%   |
| 0.51-1.0   | 3         | 0.95%   |
| 0.01-0.5   | 3         | 0.95%   |
| 7.01-8.0   | 2         | 0.63%   |
| 5.01-6.0   | 1         | 0.32%   |
| 2.01-3.0   | 1         | 0.32%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 9         | 16.36%  |
| Samsung Electronics     | 5         | 9.09%   |
| LG Display              | 5         | 9.09%   |
| Sharp                   | 4         | 7.27%   |
| Apple                   | 4         | 7.27%   |
| CSO                     | 3         | 5.45%   |
| Chimei Innolux          | 3         | 5.45%   |
| JDI                     | 2         | 3.64%   |
| Chi Mei Optoelectronics | 2         | 3.64%   |
| BOE                     | 2         | 3.64%   |
| Acer                    | 2         | 3.64%   |
| Philips                 | 1         | 1.82%   |
| NEC Computers           | 1         | 1.82%   |
| LG Electronics          | 1         | 1.82%   |
| Lenovo                  | 1         | 1.82%   |
| Iiyama                  | 1         | 1.82%   |
| Hewlett-Packard         | 1         | 1.82%   |
| Fujitsu Siemens         | 1         | 1.82%   |
| Eizo                    | 1         | 1.82%   |
| DENON                   | 1         | 1.82%   |
| Dell                    | 1         | 1.82%   |
| CSW                     | 1         | 1.82%   |
| BenQ                    | 1         | 1.82%   |
| ASUSTek Computer        | 1         | 1.82%   |
| Ancor Communications    | 1         | 1.82%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP1457 2560x1440 280x160mm 12.7-inch                  | 3         | 5.36%   |
| JDI LCD Monitor JDI422A 3000x2000 290x200mm 13.9-inch                    | 2         | 3.57%   |
| CSO LCD Monitor CSO1402 2880x1800 300x190mm 14.0-inch                    | 2         | 3.57%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 310x170mm 13.9-inch         | 2         | 3.57%   |
| Sharp LCD Monitor SHP143A 3840x2160 350x190mm 15.7-inch                  | 1         | 1.79%   |
| Samsung Electronics U32E850 SAM0CE3 3840x2160 700x390mm 31.5-inch        | 1         | 1.79%   |
| Samsung Electronics S27E390 SAM0C1B 1920x1080 600x340mm 27.2-inch        | 1         | 1.79%   |
| Samsung Electronics LCD Monitor SDC424A 3200x1800 290x170mm 13.2-inch    | 1         | 1.79%   |
| Samsung Electronics CF791 SAM0DC3 3440x1440 800x330mm 34.1-inch          | 1         | 1.79%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch        | 1         | 1.79%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                       | 1         | 1.79%   |
| NEC Computers LCD Monitor EA224WMi 1920x1080                             | 1         | 1.79%   |
| LG Electronics LCD Monitor LG Ultra HD 11520x2160                        | 1         | 1.79%   |
| LG Electronics LCD Monitor LG Ultra HD                                   | 1         | 1.79%   |
| LG Display LCD Monitor LGD06ED 1920x1200 300x190mm 14.0-inch             | 1         | 1.79%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch             | 1         | 1.79%   |
| LG Display LCD Monitor LGD0430 1366x768 350x190mm 15.7-inch              | 1         | 1.79%   |
| LG Display LCD Monitor LGD0419 2560x1440 310x170mm 13.9-inch             | 1         | 1.79%   |
| LG Display LCD Monitor LGD0258 1600x900 350x190mm 15.7-inch              | 1         | 1.79%   |
| Lenovo LEN P27q-10 LEN61A8 2560x1440 600x340mm 27.2-inch                 | 1         | 1.79%   |
| Iiyama PL3288UH IVM7610 3840x2160 700x390mm 31.5-inch                    | 1         | 1.79%   |
| Hewlett-Packard ZR24w HWP286A 1920x1200 540x350mm 25.3-inch              | 1         | 1.79%   |
| Fujitsu Siemens S19-1 FUS0517 1280x1024 380x300mm 19.1-inch              | 1         | 1.79%   |
| Eizo EV2316W ENC2394 1920x1080 510x290mm 23.1-inch                       | 1         | 1.79%   |
| DENON AVRHD DON003A 1920x1080 698x392mm 31.5-inch                        | 1         | 1.79%   |
| Dell P2715Q DEL40BD 3840x2160 600x340mm 27.2-inch                        | 1         | 1.79%   |
| CSW MNE007ZA3-2 CSW1431 2880x1800 300x190mm 14.0-inch                    | 1         | 1.79%   |
| CSO LCD Monitor CSO1500 3840x2160 340x190mm 15.3-inch                    | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN1348 1920x1080 280x160mm 12.7-inch         | 1         | 1.79%   |
| Chi Mei Optoelectronics LCD Monitor CMO1561 1280x800 330x210mm 15.4-inch | 1         | 1.79%   |
| Chi Mei Optoelectronics LCD Monitor 1920x1080                            | 1         | 1.79%   |
| BOE LCD Monitor BOE0910 1920x1080 340x190mm 15.3-inch                    | 1         | 1.79%   |
| BOE LCD Monitor BOE06DF 1920x1080 310x170mm 13.9-inch                    | 1         | 1.79%   |
| BenQ GW2250H BNQ78BD 1920x1080 480x270mm 21.7-inch                       | 1         | 1.79%   |
| AU Optronics LCD Monitor AUOD291 1920x1200 300x190mm 14.0-inch           | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 340x190mm 15.3-inch            | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch            | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch           | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch            | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO206C 1366x768 280x160mm 12.7-inch            | 1         | 1.79%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 19        | 33.93%  |
| 2560x1440 (QHD)   | 7         | 12.5%   |
| 3840x2160 (4K)    | 5         | 8.93%   |
| 2880x1800         | 4         | 7.14%   |
| 1366x768 (WXGA)   | 4         | 7.14%   |
| 1920x1200 (WUXGA) | 3         | 5.36%   |
| 3440x1440         | 2         | 3.57%   |
| 3000x2000         | 2         | 3.57%   |
| 1600x900 (HD+)    | 2         | 3.57%   |
| 1280x800 (WXGA)   | 2         | 3.57%   |
| 3200x1800 (QHD+)  | 1         | 1.79%   |
| 2560x1600         | 1         | 1.79%   |
| 1440x900 (WXGA+)  | 1         | 1.79%   |
| 1280x1024 (SXGA)  | 1         | 1.79%   |
| 11520x2160        | 1         | 1.79%   |
| Unknown           | 1         | 1.79%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 13        | 23.64%  |
| 15      | 10        | 18.18%  |
| 27      | 6         | 10.91%  |
| 12      | 6         | 10.91%  |
| 14      | 5         | 9.09%   |
| 31      | 3         | 5.45%   |
| Unknown | 3         | 5.45%   |
| 23      | 2         | 3.64%   |
| 65      | 1         | 1.82%   |
| 35      | 1         | 1.82%   |
| 34      | 1         | 1.82%   |
| 25      | 1         | 1.82%   |
| 21      | 1         | 1.82%   |
| 19      | 1         | 1.82%   |
| 17      | 1         | 1.82%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 18        | 32.73%  |
| 201-300     | 16        | 29.09%  |
| 501-600     | 9         | 16.36%  |
| 601-700     | 3         | 5.45%   |
| Unknown     | 3         | 5.45%   |
| 351-400     | 2         | 3.64%   |
| 801-900     | 1         | 1.82%   |
| 701-800     | 1         | 1.82%   |
| 401-500     | 1         | 1.82%   |
| 1001-1500   | 1         | 1.82%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 35        | 64.81%  |
| 16/10   | 10        | 18.52%  |
| Unknown | 3         | 5.56%   |
| 4/3     | 2         | 3.7%    |
| 21/9    | 2         | 3.7%    |
| 5/4     | 1         | 1.85%   |
| 3/2     | 1         | 1.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 17        | 30.91%  |
| 61-70          | 6         | 10.91%  |
| 301-350        | 6         | 10.91%  |
| 101-110        | 6         | 10.91%  |
| 351-500        | 5         | 9.09%   |
| 91-100         | 4         | 7.27%   |
| 201-250        | 3         | 5.45%   |
| Unknown        | 3         | 5.45%   |
| More than 1000 | 1         | 1.82%   |
| 71-80          | 1         | 1.82%   |
| 251-300        | 1         | 1.82%   |
| 151-200        | 1         | 1.82%   |
| 121-130        | 1         | 1.82%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 12        | 21.82%  |
| 161-240       | 11        | 20%     |
| 101-120       | 11        | 20%     |
| 51-100        | 9         | 16.36%  |
| More than 240 | 8         | 14.55%  |
| Unknown       | 3         | 5.45%   |
| 1-50          | 1         | 1.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 261       | 82.33%  |
| 1     | 52        | 16.4%   |
| 2     | 4         | 1.26%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 260       | 60.89%  |
| Realtek Semiconductor                  | 58        | 13.58%  |
| Broadcom                               | 27        | 6.32%   |
| Qualcomm Atheros                       | 14        | 3.28%   |
| AMD                                    | 13        | 3.04%   |
| Mellanox Technologies                  | 11        | 2.58%   |
| MediaTek                               | 5         | 1.17%   |
| TP-Link                                | 3         | 0.7%    |
| Qualcomm                               | 3         | 0.7%    |
| U-Blox                                 | 2         | 0.47%   |
| Sierra Wireless                        | 2         | 0.47%   |
| Samsung Electronics                    | 2         | 0.47%   |
| Huawei Technologies                    | 2         | 0.47%   |
| Hewlett-Packard                        | 2         | 0.47%   |
| Chelsio Communications                 | 2         | 0.47%   |
| American Megatrends                    | 2         | 0.47%   |
| VIA Technologies                       | 1         | 0.23%   |
| Suzhou Motorcomm Electronic Technology | 1         | 0.23%   |
| Red Hat                                | 1         | 0.23%   |
| Ralink Technology                      | 1         | 0.23%   |
| Qualcomm Technologies                  | 1         | 0.23%   |
| Qualcomm Atheros Communications        | 1         | 0.23%   |
| QLogic                                 | 1         | 0.23%   |
| Prolific Technology                    | 1         | 0.23%   |
| Oracle/SUN                             | 1         | 0.23%   |
| Nvidia                                 | 1         | 0.23%   |
| NetXen Incorporated                    | 1         | 0.23%   |
| Motorola PCS                           | 1         | 0.23%   |
| Microchip Technology                   | 1         | 0.23%   |
| Free Software Initiative of Japan      | 1         | 0.23%   |
| Ericsson Business Mobile Networks      | 1         | 0.23%   |
| Emulex                                 | 1         | 0.23%   |
| Edimax Technology                      | 1         | 0.23%   |
| Aquantia                               | 1         | 0.23%   |
| 3Com                                   | 1         | 0.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel I210 Gigabit Network Connection                                         | 55        | 9.55%   |
| Intel I211 Gigabit Network Connection                                         | 52        | 9.03%   |
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 42        | 7.29%   |
| Intel Ethernet Controller I225-V                                              | 24        | 4.17%   |
| Intel Ethernet Controller I226-V                                              | 22        | 3.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 19        | 3.3%    |
| Intel I350 Gigabit Network Connection                                         | 16        | 2.78%   |
| AMD XGMAC 10GbE Controller                                                    | 13        | 2.26%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 11        | 1.91%   |
| Intel 82574L Gigabit Network Connection                                       | 9         | 1.56%   |
| Intel Wi-Fi 6 AX200                                                           | 8         | 1.39%   |
| Intel Ethernet Connection X553 10 GbE SFP+                                    | 8         | 1.39%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 7         | 1.22%   |
| Intel Ethernet Connection I354                                                | 7         | 1.22%   |
| Realtek RTL8125 2.5GbE Controller                                             | 6         | 1.04%   |
| Intel Wireless 8265 / 8275                                                    | 6         | 1.04%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 6         | 1.04%   |
| Intel Ethernet Controller X550                                                | 6         | 1.04%   |
| Mellanox MT27500 Family [ConnectX-3]                                          | 5         | 0.87%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 5         | 0.87%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 5         | 0.87%   |
| Intel 82576 Gigabit Network Connection                                        | 5         | 0.87%   |
| Broadcom BCM4331 802.11a/b/g/n                                                | 5         | 0.87%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 4         | 0.69%   |
| Intel Ethernet Controller I226-LM                                             | 4         | 0.69%   |
| Intel Ethernet Connection I219-LM                                             | 4         | 0.69%   |
| Intel Ethernet Connection I217-LM                                             | 4         | 0.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 4         | 0.69%   |
| Intel 82583V Gigabit Network Connection                                       | 4         | 0.69%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4         | 0.69%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                      | 3         | 0.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 3         | 0.52%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 3         | 0.52%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                         | 3         | 0.52%   |
| Intel Wireless 8260                                                           | 3         | 0.52%   |
| Intel Wireless 7265                                                           | 3         | 0.52%   |
| Intel Wireless 7260                                                           | 3         | 0.52%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                     | 3         | 0.52%   |
| Intel Ethernet Controller E810-XXV for SFP                                    | 3         | 0.52%   |
| Intel Ethernet Connection (6) I219-V                                          | 3         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 55        | 50.46%  |
| Realtek Semiconductor           | 15        | 13.76%  |
| Broadcom                        | 13        | 11.93%  |
| Qualcomm Atheros                | 12        | 11.01%  |
| MediaTek                        | 5         | 4.59%   |
| TP-Link                         | 3         | 2.75%   |
| Sierra Wireless                 | 2         | 1.83%   |
| Ralink Technology               | 1         | 0.92%   |
| Qualcomm Technologies           | 1         | 0.92%   |
| Qualcomm Atheros Communications | 1         | 0.92%   |
| Edimax Technology               | 1         | 0.92%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 8         | 7.34%   |
| Intel Wireless 8265 / 8275                                     | 6         | 5.5%    |
| Broadcom BCM4331 802.11a/b/g/n                                 | 5         | 4.59%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 4         | 3.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 3.67%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 3         | 2.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 3         | 2.75%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 3         | 2.75%   |
| Intel Wireless 8260                                            | 3         | 2.75%   |
| Intel Wireless 7265                                            | 3         | 2.75%   |
| Intel Wireless 7260                                            | 3         | 2.75%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 3         | 2.75%   |
| Intel CNVi: Wi-Fi                                              | 3         | 2.75%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 2.75%   |
| Sierra Wireless EM7455                                         | 2         | 1.83%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 1.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2         | 1.83%   |
| Intel Wireless 3160                                            | 2         | 1.83%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 2         | 1.83%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 1.83%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 1.83%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 2         | 1.83%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter             | 2         | 1.83%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 2         | 1.83%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 1.83%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 0.92%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 0.92%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.92%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.92%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter            | 1         | 0.92%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 1         | 0.92%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.92%   |
| Ralink RT2501/RT2573 Wireless Adapter                          | 1         | 0.92%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 1         | 0.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 0.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 0.92%   |
| Qualcomm Atheros AR9271 802.11n                                | 1         | 0.92%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 1         | 0.92%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 0.92%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 236       | 70.03%  |
| Realtek Semiconductor                  | 48        | 14.24%  |
| Broadcom                               | 20        | 5.93%   |
| AMD                                    | 13        | 3.86%   |
| Qualcomm                               | 3         | 0.89%   |
| Samsung Electronics                    | 2         | 0.59%   |
| Qualcomm Atheros                       | 2         | 0.59%   |
| Chelsio Communications                 | 2         | 0.59%   |
| American Megatrends                    | 2         | 0.59%   |
| VIA Technologies                       | 1         | 0.3%    |
| Suzhou Motorcomm Electronic Technology | 1         | 0.3%    |
| QLogic                                 | 1         | 0.3%    |
| Oracle/SUN                             | 1         | 0.3%    |
| Nvidia                                 | 1         | 0.3%    |
| Motorola PCS                           | 1         | 0.3%    |
| Huawei Technologies                    | 1         | 0.3%    |
| Emulex                                 | 1         | 0.3%    |
| Aquantia                               | 1         | 0.3%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel I210 Gigabit Network Connection                                         | 55        | 12.42%  |
| Intel I211 Gigabit Network Connection                                         | 52        | 11.74%  |
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 42        | 9.48%   |
| Intel Ethernet Controller I225-V                                              | 24        | 5.42%   |
| Intel Ethernet Controller I226-V                                              | 22        | 4.97%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 19        | 4.29%   |
| Intel I350 Gigabit Network Connection                                         | 16        | 3.61%   |
| AMD XGMAC 10GbE Controller                                                    | 13        | 2.93%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 11        | 2.48%   |
| Intel 82574L Gigabit Network Connection                                       | 9         | 2.03%   |
| Intel Ethernet Connection X553 10 GbE SFP+                                    | 8         | 1.81%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 7         | 1.58%   |
| Intel Ethernet Connection I354                                                | 7         | 1.58%   |
| Realtek RTL8125 2.5GbE Controller                                             | 6         | 1.35%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 6         | 1.35%   |
| Intel Ethernet Controller X550                                                | 6         | 1.35%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 5         | 1.13%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 5         | 1.13%   |
| Intel 82576 Gigabit Network Connection                                        | 5         | 1.13%   |
| Intel Ethernet Controller I226-LM                                             | 4         | 0.9%    |
| Intel Ethernet Connection I219-LM                                             | 4         | 0.9%    |
| Intel Ethernet Connection I217-LM                                             | 4         | 0.9%    |
| Intel 82583V Gigabit Network Connection                                       | 4         | 0.9%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4         | 0.9%    |
| Intel Ethernet Controller E810-XXV for SFP                                    | 3         | 0.68%   |
| Intel Ethernet Connection (6) I219-V                                          | 3         | 0.68%   |
| Intel Ethernet Connection (6) I219-LM                                         | 3         | 0.68%   |
| Intel 82579V Gigabit Network Connection                                       | 3         | 0.68%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 3         | 0.68%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                             | 3         | 0.68%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 2         | 0.45%   |
| Qualcomm FP3                                                                  | 2         | 0.45%   |
| Intel I350 Gigabit Fiber Network Connection                                   | 2         | 0.45%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                              | 2         | 0.45%   |
| Intel Ethernet Connection X722 for 1GbE                                       | 2         | 0.45%   |
| Intel Ethernet Connection X552 10 GbE SFP+                                    | 2         | 0.45%   |
| Intel Ethernet Connection I218-V                                              | 2         | 0.45%   |
| Intel Ethernet Connection (7) I219-LM                                         | 2         | 0.45%   |
| Intel Ethernet Connection (4) I219-V                                          | 2         | 0.45%   |
| Intel Ethernet Connection (2) I219-LM                                         | 2         | 0.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 296       | 70.64%  |
| WiFi     | 99        | 23.63%  |
| Unknown  | 15        | 3.58%   |
| Modem    | 9         | 2.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 273       | 88.35%  |
| WiFi     | 36        | 11.65%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 4     | 61        | 19.37%  |
| 2     | 58        | 18.41%  |
| 3     | 54        | 17.14%  |
| 6     | 46        | 14.6%   |
| 1     | 34        | 10.79%  |
| 5     | 30        | 9.52%   |
| 8     | 9         | 2.86%   |
| 7     | 6         | 1.9%    |
| 9     | 5         | 1.59%   |
| 13    | 3         | 0.95%   |
| 12    | 2         | 0.63%   |
| 10    | 2         | 0.63%   |
| 0     | 2         | 0.63%   |
| 16    | 1         | 0.32%   |
| 15    | 1         | 0.32%   |
| 14    | 1         | 0.32%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 245       | 74.92%  |
| Yes  | 82        | 25.08%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 43        | 51.19%  |
| Apple                           | 10        | 11.9%   |
| IMC Networks                    | 7         | 8.33%   |
| Realtek Semiconductor           | 5         | 5.95%   |
| ASUSTek Computer                | 4         | 4.76%   |
| MediaTek                        | 3         | 3.57%   |
| Broadcom                        | 3         | 3.57%   |
| Qualcomm Atheros Communications | 2         | 2.38%   |
| USI                             | 1         | 1.19%   |
| Lite-On Technology              | 1         | 1.19%   |
| Hewlett-Packard                 | 1         | 1.19%   |
| Foxconn / Hon Hai               | 1         | 1.19%   |
| Dell                            | 1         | 1.19%   |
| Cambridge Silicon Radio         | 1         | 1.19%   |
| Alps Electric                   | 1         | 1.19%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 16        | 19.05%  |
| Intel AX201 Bluetooth                                       | 11        | 13.1%   |
| Intel AX200 Bluetooth                                       | 8         | 9.52%   |
| Realtek Bluetooth Adapter                                   | 5         | 5.95%   |
| Apple Bluetooth Host Controller                             | 5         | 5.95%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 3         | 3.57%   |
| Intel AX210 Bluetooth                                       | 3         | 3.57%   |
| IMC Networks Realtek Bluetooth Adapter                      | 3         | 3.57%   |
| Apple Broadcom Built-in Bluetooth                           | 3         | 3.57%   |
| MediaTek Wireless_Device                                    | 2         | 2.38%   |
| Broadcom Bluetooth 4.1 USB                                  | 2         | 2.38%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 2         | 2.38%   |
| USI Qualcomm WCN685x Bluetooth Adapter                      | 1         | 1.19%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 1.19%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 1.19%   |
| MediaTek RZ608 Bluetooth Adapter                            | 1         | 1.19%   |
| Lite-On Atheros AR3012 Bluetooth                            | 1         | 1.19%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 1.19%   |
| Intel AX211 Bluetooth                                       | 1         | 1.19%   |
| IMC Networks Wireless_Device                                | 1         | 1.19%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 1         | 1.19%   |
| IMC Networks MediaTek Bluetooth Adapter                     | 1         | 1.19%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 1         | 1.19%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 1.19%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 1.19%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 1         | 1.19%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 1         | 1.19%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 1         | 1.19%   |
| ASUS USB-BT500                                              | 1         | 1.19%   |
| ASUS BT-253 Bluetooth Adapter                               | 1         | 1.19%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 1         | 1.19%   |
| ASUS Bluetooth Controller                                   | 1         | 1.19%   |
| Alps Electric UGTZ4 Bluetooth                               | 1         | 1.19%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 163       | 69.36%  |
| AMD                   | 42        | 17.87%  |
| Nvidia                | 17        | 7.23%   |
| Lenovo                | 3         | 1.28%   |
| ULi Electronics       | 2         | 0.85%   |
| Realtek Semiconductor | 2         | 0.85%   |
| PS Audio              | 1         | 0.43%   |
| Logitech              | 1         | 0.43%   |
| GN Netcom             | 1         | 0.43%   |
| ESS Technology        | 1         | 0.43%   |
| C-Media Electronics   | 1         | 0.43%   |
| ASUSTek Computer      | 1         | 0.43%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 21        | 7.84%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 16        | 5.97%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 16        | 5.97%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 15        | 5.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 12        | 4.48%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 11        | 4.1%    |
| Intel Alder Lake-N PCH High Definition Audio Controller                                           | 11        | 4.1%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 11        | 4.1%    |
| Intel Jasper Lake HD Audio                                                                        | 10        | 3.73%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 8         | 2.99%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 8         | 2.99%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 2.61%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 2.24%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 6         | 2.24%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 2.24%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 1.87%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 4         | 1.49%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 1.49%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4         | 1.49%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 1.49%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1.49%   |
| Intel 8 Series HD Audio Controller                                                                | 4         | 1.49%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 4         | 1.49%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.12%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 1.12%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 1.12%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 1.12%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 1.12%   |
| ULi Electronics M5451 PCI AC-Link Controller Audio Device                                         | 2         | 0.75%   |
| Lenovo Lenovo USB-C Mini Dock                                                                     | 2         | 0.75%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 0.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.75%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 2         | 0.75%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 0.75%   |
| Intel 200 Series PCH HD Audio                                                                     | 2         | 0.75%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 2         | 0.75%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 2         | 0.75%   |
| Realtek Semiconductor USB Audio Maono Elf retrieving string failed                                | 1         | 0.37%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.37%   |
| PS Audio PS Audio USB Audio 2.0                                                                   | 1         | 0.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Kingston            | 64        | 21.48%  |
| SK hynix            | 43        | 14.43%  |
| Samsung Electronics | 36        | 12.08%  |
| Unknown             | 33        | 11.07%  |
| Micron Technology   | 30        | 10.07%  |
| Crucial             | 26        | 8.72%   |
| Corsair             | 21        | 7.05%   |
| Transcend           | 15        | 5.03%   |
| Unknown (ABCD)      | 3         | 1.01%   |
| Toshiba             | 3         | 1.01%   |
| Nanya Technology    | 3         | 1.01%   |
| Unknown             | 3         | 1.01%   |
| Unknown (07FB)      | 2         | 0.67%   |
| Hewlett-Packard     | 2         | 0.67%   |
| G.Skill             | 2         | 0.67%   |
| Elpida              | 2         | 0.67%   |
| A-DATA Technology   | 2         | 0.67%   |
| Unknown (F301)      | 1         | 0.34%   |
| Unknown (0x05F7)    | 1         | 0.34%   |
| tigo                | 1         | 0.34%   |
| Super Talent        | 1         | 0.34%   |
| Silicon Power       | 1         | 0.34%   |
| QEMU                | 1         | 0.34%   |
| Goldenmars          | 1         | 0.34%   |
| ASint Technology    | 1         | 0.34%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                    | 19        | 6.01%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s            | 8         | 2.53%   |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s                     | 3         | 0.95%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                    | 3         | 0.95%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2133MT/s | 3         | 0.95%   |
| SK hynix RAM Module 4GB SODIMM LPDDR3 1600MT/s                 | 3         | 0.95%   |
| SK hynix RAM HMA81GU6CJR8N-XN 8GB DIMM DDR4 3200MT/s           | 3         | 0.95%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s    | 3         | 0.95%   |
| Kingston RAM KHX2933C15D4/8GX 8GB DIMM DDR4 2400MT/s           | 3         | 0.95%   |
| Kingston RAM KF2666C15S4/8G 8GB SODIMM DDR4 2667MT/s           | 3         | 0.95%   |
| Kingston RAM CBD24D4S7S8K1A-8 8GB SODIMM DDR4 2400MT/s         | 3         | 0.95%   |
| Crucial RAM CT16G56C46S5.M8G1 16GB SODIMM DDR5 5600MT/s        | 3         | 0.95%   |
| Unknown                                                        | 3         | 0.95%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 2         | 0.63%   |
| Transcend RAM TS512MLH64V6HL 4GB SODIMM DDR4 2667MT/s          | 2         | 0.63%   |
| Transcend RAM TS1GLH64V6B3 8GB SODIMM DDR4 1333MT/s            | 2         | 0.63%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 0.63%   |
| SK hynix RAM HMA82GR7CJR4N-WM 16GB DIMM DDR4 2933MT/s          | 2         | 0.63%   |
| SK hynix RAM HMA82GR7AFR8N-VK 16GB DIMM DDR4 2666MT/s          | 2         | 0.63%   |
| SK hynix RAM HMA82GR7AFR4N-UH 16GB DIMM DDR4 2400MT/s          | 2         | 0.63%   |
| Micron RAM MT52L512M32D2PF-09 4GB Row Of Chips LPDDR3 2133MT/s | 2         | 0.63%   |
| Micron RAM Module 8GB Row Of Chips LPDDR4 3200MT/s             | 2         | 0.63%   |
| Micron RAM Module 2GB DIMM DDR3 1333MT/s                       | 2         | 0.63%   |
| Micron RAM Module 16GB Row Of Chips LPDDR4 4267MT/s            | 2         | 0.63%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s            | 2         | 0.63%   |
| Kingston RAM 99U5471-052.A00LF 8GB DIMM DDR3 1333MT/s          | 2         | 0.63%   |
| Kingston RAM 9965745-020.A00G 32GB DIMM DDR4 3200MT/s          | 2         | 0.63%   |
| Kingston RAM 9905403-559.A00LF 8GB DIMM DDR3 1333MT/s          | 2         | 0.63%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.63%   |
| Crucial RAM CT8G4SFS824A.M8FD 8GB SODIMM DDR4 2400MT/s         | 2         | 0.63%   |
| Crucial RAM CT8G4SFRA32A.M8FR 8GB SODIMM DDR4 3200MT/s         | 2         | 0.63%   |
| Crucial RAM CT8G4DFS8266.M8FJ 8GB DIMM DDR4 2666MT/s           | 2         | 0.63%   |
| Crucial RAM CT8G4DFRA266.C8FB 8GB DIMM DDR4 2666MT/s           | 2         | 0.63%   |
| Crucial RAM CT8G48C40S5.M4A1 8GB SODIMM DDR5 4800MT/s          | 2         | 0.63%   |
| Crucial RAM CT32G48C40S5.M16A1 32GB SODIMM DDR5 4800MT/s       | 2         | 0.63%   |
| Crucial RAM CT16G56C46S5.C8D 16GB SODIMM DDR5 5600MT/s         | 2         | 0.63%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3000MT/s         | 2         | 0.63%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 1         | 0.32%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                      | 1         | 0.32%   |
| Unknown RAM Module 512MB DIMM DDR2 667MT/s                     | 1         | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 116       | 42.34%  |
| DDR3    | 109       | 39.78%  |
| DDR5    | 19        | 6.93%   |
| LPDDR4  | 11        | 4.01%   |
| LPDDR3  | 8         | 2.92%   |
| DDR2    | 5         | 1.82%   |
| LPDDR5  | 3         | 1.09%   |
| Unknown | 2         | 0.73%   |
| RAM     | 1         | 0.36%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 145       | 53.11%  |
| DIMM         | 107       | 39.19%  |
| Row Of Chips | 17        | 6.23%   |
| Chip         | 2         | 0.73%   |
| RIMM         | 1         | 0.37%   |
| FB-DIMM      | 1         | 0.37%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 106       | 36.93%  |
| 4096  | 73        | 25.44%  |
| 16384 | 65        | 22.65%  |
| 2048  | 18        | 6.27%   |
| 32768 | 17        | 5.92%   |
| 1024  | 3         | 1.05%   |
| 65536 | 2         | 0.7%    |
| 6144  | 1         | 0.35%   |
| 3072  | 1         | 0.35%   |
| 512   | 1         | 0.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1333    | 56        | 19.18%  |
| 1600    | 52        | 17.81%  |
| 2667    | 39        | 13.36%  |
| 3200    | 33        | 11.3%   |
| 2400    | 25        | 8.56%   |
| 2133    | 17        | 5.82%   |
| 4800    | 14        | 4.79%   |
| 2666    | 10        | 3.42%   |
| 5600    | 6         | 2.05%   |
| 667     | 5         | 1.71%   |
| 4267    | 4         | 1.37%   |
| 2933    | 4         | 1.37%   |
| 1867    | 4         | 1.37%   |
| 800     | 4         | 1.37%   |
| 3000    | 3         | 1.03%   |
| 1334    | 3         | 1.03%   |
| 6400    | 2         | 0.68%   |
| 3600    | 2         | 0.68%   |
| 1067    | 2         | 0.68%   |
| Unknown | 2         | 0.68%   |
| 4000    | 1         | 0.34%   |
| 1866    | 1         | 0.34%   |
| 1800    | 1         | 0.34%   |
| 1066    | 1         | 0.34%   |
| 1033    | 1         | 0.34%   |

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

![Camera Vendor](./All/images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 13        | 28.89%  |
| IMC Networks                           | 9         | 20%     |
| Bison Electronics                      | 7         | 15.56%  |
| Apple                                  | 5         | 11.11%  |
| Sunplus Innovation Technology          | 3         | 6.67%   |
| Microdia                               | 3         | 6.67%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 4.44%   |
| Suyin                                  | 1         | 2.22%   |
| Supreme Electronics                    | 1         | 2.22%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 2.22%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Bison Integrated Camera                                     | 6         | 13.33%  |
| Chicony Integrated Camera                                   | 5         | 11.11%  |
| IMC Networks Integrated Camera                              | 4         | 8.89%   |
| IMC Networks Lenovo EasyCamera                              | 3         | 6.67%   |
| Apple FaceTime HD Camera (Built-in)                         | 3         | 6.67%   |
| Microdia Lenovo EasyCamera                                  | 2         | 4.44%   |
| Apple FaceTime HD Camera                                    | 2         | 4.44%   |
| Suyin HD WebCam                                             | 1         | 2.22%   |
| Supreme Realtek PC Camera                                   | 1         | 2.22%   |
| Sunplus Laptop Integrated WebCam HD                         | 1         | 2.22%   |
| Sunplus Laptop Integrated Webcam FHD                        | 1         | 2.22%   |
| Sunplus ASUS Webcam                                         | 1         | 2.22%   |
| Shenzhen Kingcome Optoelectronic FHD WebCam                 | 1         | 2.22%   |
| Microdia Integrated Webcam                                  | 1         | 2.22%   |
| IMC Networks EasyCamera                                     | 1         | 2.22%   |
| IMC Networks ASUS EasyCamera                                | 1         | 2.22%   |
| Chicony USB2.0 HD UVC WebCam                                | 1         | 2.22%   |
| Chicony USB 2.0 2.0M UVC WebCam                             | 1         | 2.22%   |
| Chicony ThinkPad T490 Webcam                                | 1         | 2.22%   |
| Chicony Lenovo EasyCamera                                   | 1         | 2.22%   |
| Chicony Integrated HP HD Webcam                             | 1         | 2.22%   |
| Chicony Integrated Camera [ThinkPad]                        | 1         | 2.22%   |
| Chicony HP Webcam [2 MP Macro]                              | 1         | 2.22%   |
| Chicony HP Universal Camera                                 | 1         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed] | 1         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera            | 1         | 2.22%   |
| Bison Lenovo EasyCamera integrated webcam                   | 1         | 2.22%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 53.85%  |
| Synaptics                  | 4         | 30.77%  |
| Upek                       | 1         | 7.69%   |
| Shenzhen Goodix Technology | 1         | 7.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 2         | 15.38%  |
| Validity Sensors VFS 5011 fingerprint sensor           | 2         | 15.38%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 15.38%  |
| Validity Sensors VFS491                                | 1         | 7.69%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 7.69%   |
| Validity Sensors Synaptics WBDI                        | 1         | 7.69%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 7.69%   |
| Synaptics WBDI                                         | 1         | 7.69%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 7.69%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 7.69%   |

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

![Unsupported Devices](./All/images/pie_chart_bsd/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 111       | 34.26%  |
| 0     | 108       | 33.33%  |
| 2     | 54        | 16.67%  |
| 3     | 37        | 11.42%  |
| 4     | 11        | 3.4%    |
| 5     | 3         | 0.93%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 183       | 58.65%  |
| Bluetooth                | 37        | 11.86%  |
| Net/wireless             | 31        | 9.94%   |
| Firewire controller      | 16        | 5.13%   |
| Card reader              | 14        | 4.49%   |
| Fingerprint reader       | 11        | 3.53%   |
| Net/ethernet             | 8         | 2.56%   |
| Sound                    | 5         | 1.6%    |
| Network                  | 3         | 0.96%   |
| Graphics card            | 3         | 0.96%   |
| Storage                  | 1         | 0.32%   |

