BSD in Germany - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for BSD in Germany.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Germany/Desktop/README.md) and [notebooks](/Location/Germany/Notebook/README.md).

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

Total: 3189

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Unknown       | Unknown                     | Desktop     | [9876dcc6aa](https://bsd-hardware.info/?probe=9876dcc6aa) | Dec 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [9a23873dc4](https://bsd-hardware.info/?probe=9a23873dc4) | Dec 24, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [7ca1ae0c93](https://bsd-hardware.info/?probe=7ca1ae0c93) | Dec 23, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [13699f3359](https://bsd-hardware.info/?probe=13699f3359) | Dec 23, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | Desktop     | [ee768bd5a0](https://bsd-hardware.info/?probe=ee768bd5a0) | Dec 23, 2023 |
| Lenovo        | ThinkPad T480 20L6S8LW00    | Notebook    | [32c06c5669](https://bsd-hardware.info/?probe=32c06c5669) | Dec 23, 2023 |
| Dell          | 03X6X0 A02                  | Server      | [1fc8559747](https://bsd-hardware.info/?probe=1fc8559747) | Dec 23, 2023 |
| CWWK          | CW-ADLN-6L                  | Desktop     | [d8245df746](https://bsd-hardware.info/?probe=d8245df746) | Dec 23, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [5ed362ce02](https://bsd-hardware.info/?probe=5ed362ce02) | Dec 22, 2023 |
| ZX            | H610ITXG                    | Desktop     | [11edcbeaff](https://bsd-hardware.info/?probe=11edcbeaff) | Dec 22, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [2e35364732](https://bsd-hardware.info/?probe=2e35364732) | Dec 22, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [9eaa02c47c](https://bsd-hardware.info/?probe=9eaa02c47c) | Dec 22, 2023 |
| Supermicro    | X11SSH-LN4F                 | Server      | [132a8d8b6f](https://bsd-hardware.info/?probe=132a8d8b6f) | Dec 21, 2023 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [b2597a7f2b](https://bsd-hardware.info/?probe=b2597a7f2b) | Dec 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [ec4c6d8fb5](https://bsd-hardware.info/?probe=ec4c6d8fb5) | Dec 21, 2023 |
| Yanling       | YL-CLU6L-V1                 | Desktop     | [9a0369cc72](https://bsd-hardware.info/?probe=9a0369cc72) | Dec 21, 2023 |
| Sophos        | UTM                         | Firewall    | [e1e002bdd4](https://bsd-hardware.info/?probe=e1e002bdd4) | Dec 21, 2023 |
| CWWK          | CW-ADLN-6L                  | Desktop     | [094d15625b](https://bsd-hardware.info/?probe=094d15625b) | Dec 21, 2023 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [5c6e9bd18a](https://bsd-hardware.info/?probe=5c6e9bd18a) | Dec 20, 2023 |
| Fujitsu       | D3544-A1 S26361-D3544-A1... | Desktop     | [ec18d4f3a1](https://bsd-hardware.info/?probe=ec18d4f3a1) | Dec 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [f11c353c61](https://bsd-hardware.info/?probe=f11c353c61) | Dec 19, 2023 |
| PC Engines    | apu4                        | Desktop     | [97c6f1ef2a](https://bsd-hardware.info/?probe=97c6f1ef2a) | Dec 19, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [11e5e87b70](https://bsd-hardware.info/?probe=11e5e87b70) | Dec 16, 2023 |
| Supermicro    | X10SLH-F/X10SLM+-F          | Server      | [17f70cfb67](https://bsd-hardware.info/?probe=17f70cfb67) | Dec 16, 2023 |
| CSL-Comput... | C15 v3                      | Notebook    | [dd93594896](https://bsd-hardware.info/?probe=dd93594896) | Dec 16, 2023 |
| SHANGZHAOY... | B85M-PRO V1.1               | Desktop     | [3b7ed136da](https://bsd-hardware.info/?probe=3b7ed136da) | Dec 16, 2023 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [aefb80936c](https://bsd-hardware.info/?probe=aefb80936c) | Dec 15, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [f05a97db34](https://bsd-hardware.info/?probe=f05a97db34) | Dec 15, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [343d176e9c](https://bsd-hardware.info/?probe=343d176e9c) | Dec 15, 2023 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [7a32a123f6](https://bsd-hardware.info/?probe=7a32a123f6) | Dec 15, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [b6845a3e54](https://bsd-hardware.info/?probe=b6845a3e54) | Dec 15, 2023 |
| AZW           | EQ                          | Desktop     | [f1e4bf2224](https://bsd-hardware.info/?probe=f1e4bf2224) | Dec 15, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [c197b26909](https://bsd-hardware.info/?probe=c197b26909) | Dec 14, 2023 |
| Dell          | Latitude E6540              | Notebook    | [77a9b10ab9](https://bsd-hardware.info/?probe=77a9b10ab9) | Dec 13, 2023 |
| Sophos        | SG                          | Firewall    | [13c711aabf](https://bsd-hardware.info/?probe=13c711aabf) | Dec 13, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [b5f9416c13](https://bsd-hardware.info/?probe=b5f9416c13) | Dec 12, 2023 |
| HP            | ProLiant DL380p Gen8        | Server      | [20dd6f1621](https://bsd-hardware.info/?probe=20dd6f1621) | Dec 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [8a0a469ad0](https://bsd-hardware.info/?probe=8a0a469ad0) | Dec 12, 2023 |
| SHANGZHAOY... | B85M-PRO V1.1               | Desktop     | [5cf5db5a05](https://bsd-hardware.info/?probe=5cf5db5a05) | Dec 11, 2023 |
| Dell          | 08CYF7 A05                  | Server      | [2768b91142](https://bsd-hardware.info/?probe=2768b91142) | Dec 11, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [9a3a20d295](https://bsd-hardware.info/?probe=9a3a20d295) | Dec 11, 2023 |
| Supermicro    | X10SBAA                     | Server      | [f68b2d784b](https://bsd-hardware.info/?probe=f68b2d784b) | Dec 10, 2023 |
| ASRock        | H110M-DVS R3.0              | Desktop     | [b6a4782cbf](https://bsd-hardware.info/?probe=b6a4782cbf) | Dec 10, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [47480f848d](https://bsd-hardware.info/?probe=47480f848d) | Dec 10, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [d62ad0d622](https://bsd-hardware.info/?probe=d62ad0d622) | Dec 09, 2023 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [0fe56565dc](https://bsd-hardware.info/?probe=0fe56565dc) | Dec 09, 2023 |
| Dell          | 02YYK5 A00                  | Desktop     | [39e0078d08](https://bsd-hardware.info/?probe=39e0078d08) | Dec 09, 2023 |
| ASRock        | Z370 Pro4                   | Desktop     | [6b4d8c076f](https://bsd-hardware.info/?probe=6b4d8c076f) | Dec 09, 2023 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [5b31c551ae](https://bsd-hardware.info/?probe=5b31c551ae) | Dec 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [31619d30b3](https://bsd-hardware.info/?probe=31619d30b3) | Dec 09, 2023 |
| PC Engines    | APU2                        | Desktop     | [8f318ea168](https://bsd-hardware.info/?probe=8f318ea168) | Dec 09, 2023 |
| PC Engines    | APU2                        | Desktop     | [ca43be99fc](https://bsd-hardware.info/?probe=ca43be99fc) | Dec 08, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | Desktop     | [eb2eef3d17](https://bsd-hardware.info/?probe=eb2eef3d17) | Dec 08, 2023 |
| PC Engines    | apu4                        | Desktop     | [cdbac53ff6](https://bsd-hardware.info/?probe=cdbac53ff6) | Dec 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [efab62c197](https://bsd-hardware.info/?probe=efab62c197) | Dec 07, 2023 |
| Fujitsu       | D3633-S1 S26361-D3633-S1    | Desktop     | [d3898c1e39](https://bsd-hardware.info/?probe=d3898c1e39) | Dec 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [fed92c23db](https://bsd-hardware.info/?probe=fed92c23db) | Dec 07, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [7476cc6440](https://bsd-hardware.info/?probe=7476cc6440) | Dec 06, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [3784a39a41](https://bsd-hardware.info/?probe=3784a39a41) | Dec 06, 2023 |
| Supermicro    | X10SDV-TP8F                 | Server      | [52605948b7](https://bsd-hardware.info/?probe=52605948b7) | Dec 06, 2023 |
| PC Engines    | APU3                        | Desktop     | [06a4e1c23b](https://bsd-hardware.info/?probe=06a4e1c23b) | Dec 06, 2023 |
| PC Engines    | apu4                        | Desktop     | [04dd506405](https://bsd-hardware.info/?probe=04dd506405) | Dec 06, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [9d54a02c53](https://bsd-hardware.info/?probe=9d54a02c53) | Dec 05, 2023 |
| Yanling       | YL-KBRL2 Series Ver:1.02    | Desktop     | [3bd3f01055](https://bsd-hardware.info/?probe=3bd3f01055) | Dec 05, 2023 |
| HP            | 8103 A01                    | Mini pc     | [f558be71a3](https://bsd-hardware.info/?probe=f558be71a3) | Dec 05, 2023 |
| HP            | 8103 A01                    | Mini pc     | [a71bdf2036](https://bsd-hardware.info/?probe=a71bdf2036) | Dec 05, 2023 |
| Wortmann      | TERRA_MOBILE_1541           | Notebook    | [63f1a71855](https://bsd-hardware.info/?probe=63f1a71855) | Dec 04, 2023 |
| HP            | 8103 A01                    | Mini pc     | [0da20332e6](https://bsd-hardware.info/?probe=0da20332e6) | Dec 04, 2023 |
| Protectli     | FW2B Ver                    | Desktop     | [9ae293de1b](https://bsd-hardware.info/?probe=9ae293de1b) | Dec 03, 2023 |
| Protectli     | VP2420                      | Desktop     | [31b70f1d0d](https://bsd-hardware.info/?probe=31b70f1d0d) | Dec 03, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [f23df632e4](https://bsd-hardware.info/?probe=f23df632e4) | Dec 03, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [8a6ce136cc](https://bsd-hardware.info/?probe=8a6ce136cc) | Dec 03, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [150fd26797](https://bsd-hardware.info/?probe=150fd26797) | Dec 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [5efe3ae6f9](https://bsd-hardware.info/?probe=5efe3ae6f9) | Dec 01, 2023 |
| Protectli     | VP2420                      | Desktop     | [4d59cef5e8](https://bsd-hardware.info/?probe=4d59cef5e8) | Nov 30, 2023 |
| Intel         | JSL MRD                     | Desktop     | [0ec285953e](https://bsd-hardware.info/?probe=0ec285953e) | Nov 30, 2023 |
| Unknown       | Unknown                     | Notebook    | [7d3416a30f](https://bsd-hardware.info/?probe=7d3416a30f) | Nov 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [e5be2bebf5](https://bsd-hardware.info/?probe=e5be2bebf5) | Nov 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [9579521c83](https://bsd-hardware.info/?probe=9579521c83) | Nov 30, 2023 |
| Intel         | JSL MRD                     | Desktop     | [f8beb1caa9](https://bsd-hardware.info/?probe=f8beb1caa9) | Nov 30, 2023 |
| CWWK          | CW-AD4L-N V1                | Desktop     | [e31a43fc53](https://bsd-hardware.info/?probe=e31a43fc53) | Nov 30, 2023 |
| Yanling       | YL-ALU6L                    | Desktop     | [21135d9aa5](https://bsd-hardware.info/?probe=21135d9aa5) | Nov 29, 2023 |
| Deciso        | DEC2700 - OPNsense Appli... | Notebook    | [e98e7bcab5](https://bsd-hardware.info/?probe=e98e7bcab5) | Nov 29, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [895be1e0cd](https://bsd-hardware.info/?probe=895be1e0cd) | Nov 28, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [61bf87efe4](https://bsd-hardware.info/?probe=61bf87efe4) | Nov 28, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [a2a08d6eec](https://bsd-hardware.info/?probe=a2a08d6eec) | Nov 28, 2023 |
| CNCTION-IA... | Unknown                     | Desktop     | [1b4871792b](https://bsd-hardware.info/?probe=1b4871792b) | Nov 28, 2023 |
| Lanner        | FW-7543 B-GA                | Desktop     | [fa32eea2ff](https://bsd-hardware.info/?probe=fa32eea2ff) | Nov 26, 2023 |
| Unknown       | Unknown                     | Notebook    | [55339dbfab](https://bsd-hardware.info/?probe=55339dbfab) | Nov 26, 2023 |
| PC Engines    | APU2                        | Desktop     | [c2ab63093b](https://bsd-hardware.info/?probe=c2ab63093b) | Nov 25, 2023 |
| ASRock        | H570M-ITX/ac                | Desktop     | [a8d3950959](https://bsd-hardware.info/?probe=a8d3950959) | Nov 25, 2023 |
| HP            | 1825                        | Desktop     | [373a147d04](https://bsd-hardware.info/?probe=373a147d04) | Nov 24, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [7bb170248d](https://bsd-hardware.info/?probe=7bb170248d) | Nov 24, 2023 |
| Dell          | 0F0XJ6 A13                  | Server      | [f4a31a2e53](https://bsd-hardware.info/?probe=f4a31a2e53) | Nov 24, 2023 |
| PICO PC       | MNHO-113                    | Desktop     | [261b0d936c](https://bsd-hardware.info/?probe=261b0d936c) | Nov 23, 2023 |
| Sophos        | XG                          | Firewall    | [a0539d33da](https://bsd-hardware.info/?probe=a0539d33da) | Nov 23, 2023 |
| Dell          | 00P8G1 A00                  | All in one  | [daca9b37fd](https://bsd-hardware.info/?probe=daca9b37fd) | Nov 23, 2023 |
| Lanner        | FW-7543 B-GA                | Desktop     | [eca8e8785c](https://bsd-hardware.info/?probe=eca8e8785c) | Nov 22, 2023 |
| AZW           | EQ                          | Desktop     | [3407ab2a5b](https://bsd-hardware.info/?probe=3407ab2a5b) | Nov 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [87ab49a51e](https://bsd-hardware.info/?probe=87ab49a51e) | Nov 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [b60795e523](https://bsd-hardware.info/?probe=b60795e523) | Nov 22, 2023 |
| Thomas-Kre... | LES network 6L              | Desktop     | [654e4f96f7](https://bsd-hardware.info/?probe=654e4f96f7) | Nov 21, 2023 |
| Unknown       | Unknown                     | Notebook    | [ff855b549e](https://bsd-hardware.info/?probe=ff855b549e) | Nov 20, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [d38d698b2e](https://bsd-hardware.info/?probe=d38d698b2e) | Nov 20, 2023 |
| Intel         | ND2X-NET-PC BIOS Revisio... | Desktop     | [7fd080cf42](https://bsd-hardware.info/?probe=7fd080cf42) | Nov 19, 2023 |
| Panasonic     | CF-31-5                     | Notebook    | [8771ab6139](https://bsd-hardware.info/?probe=8771ab6139) | Nov 18, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [bd12235645](https://bsd-hardware.info/?probe=bd12235645) | Nov 18, 2023 |
| Deciso        | Netboard A10                | Desktop     | [5efc270fa6](https://bsd-hardware.info/?probe=5efc270fa6) | Nov 18, 2023 |
| ShenZhen M... | MW-GMLK-2.5G6L              | Desktop     | [947076a4de](https://bsd-hardware.info/?probe=947076a4de) | Nov 18, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [07dbd58d8e](https://bsd-hardware.info/?probe=07dbd58d8e) | Nov 17, 2023 |
| TUXEDO        | Pulse 15 Gen2               | Notebook    | [9061ad4228](https://bsd-hardware.info/?probe=9061ad4228) | Nov 17, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [984f5f2f4b](https://bsd-hardware.info/?probe=984f5f2f4b) | Nov 16, 2023 |
| Fujitsu       | D3633-S1 S26361-D3633-S1    | Desktop     | [a406ee9805](https://bsd-hardware.info/?probe=a406ee9805) | Nov 16, 2023 |
| PC Engines    | APU2                        | Desktop     | [5ea4af0d94](https://bsd-hardware.info/?probe=5ea4af0d94) | Nov 16, 2023 |
| Intel         | QHSW02                      | Desktop     | [f05cdb2841](https://bsd-hardware.info/?probe=f05cdb2841) | Nov 15, 2023 |
| ASRock        | A300M-STX                   | Desktop     | [e5f0053202](https://bsd-hardware.info/?probe=e5f0053202) | Nov 15, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [7719e7606c](https://bsd-hardware.info/?probe=7719e7606c) | Nov 15, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [6257d05c99](https://bsd-hardware.info/?probe=6257d05c99) | Nov 15, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [e98965d0f9](https://bsd-hardware.info/?probe=e98965d0f9) | Nov 14, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [0f82d77235](https://bsd-hardware.info/?probe=0f82d77235) | Nov 14, 2023 |
| Supermicro    | X10SDV-TP8F                 | Server      | [fec17c799c](https://bsd-hardware.info/?probe=fec17c799c) | Nov 14, 2023 |
| HP            | ProLiant DL360 G5           | Server      | [8b2811bcf5](https://bsd-hardware.info/?probe=8b2811bcf5) | Nov 14, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [4984b1536a](https://bsd-hardware.info/?probe=4984b1536a) | Nov 14, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [5d9467ed74](https://bsd-hardware.info/?probe=5d9467ed74) | Nov 14, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [d6f10bf9d2](https://bsd-hardware.info/?probe=d6f10bf9d2) | Nov 13, 2023 |
| Dell          | 015HP0 A00                  | Mini pc     | [b282285d51](https://bsd-hardware.info/?probe=b282285d51) | Nov 13, 2023 |
| Dell          | 015HP0 A00                  | Mini pc     | [2c1f962756](https://bsd-hardware.info/?probe=2c1f962756) | Nov 13, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | Desktop     | [49089c64bf](https://bsd-hardware.info/?probe=49089c64bf) | Nov 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [d8cc007961](https://bsd-hardware.info/?probe=d8cc007961) | Nov 12, 2023 |
| PC Engines    | APU3                        | Desktop     | [0c58a923fe](https://bsd-hardware.info/?probe=0c58a923fe) | Nov 12, 2023 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [2f916d0780](https://bsd-hardware.info/?probe=2f916d0780) | Nov 12, 2023 |
| HP            | ProLiant DL320e Gen8 v2     | Server      | [faf46e5802](https://bsd-hardware.info/?probe=faf46e5802) | Nov 11, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [9bab52c825](https://bsd-hardware.info/?probe=9bab52c825) | Nov 11, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [da0816e168](https://bsd-hardware.info/?probe=da0816e168) | Nov 10, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [6afb2cc33f](https://bsd-hardware.info/?probe=6afb2cc33f) | Nov 10, 2023 |
| Dell          | 045M96 A02                  | Server      | [afd35f3afa](https://bsd-hardware.info/?probe=afd35f3afa) | Nov 09, 2023 |
| Sophos        | SG                          | Firewall    | [042fb4f2e1](https://bsd-hardware.info/?probe=042fb4f2e1) | Nov 09, 2023 |
| Sophos        | SG                          | Firewall    | [396d8e0dca](https://bsd-hardware.info/?probe=396d8e0dca) | Nov 09, 2023 |
| Sophos        | UTM                         | Firewall    | [8b26d81a35](https://bsd-hardware.info/?probe=8b26d81a35) | Nov 08, 2023 |
| Sophos        | UTM                         | Firewall    | [6d031ab91e](https://bsd-hardware.info/?probe=6d031ab91e) | Nov 08, 2023 |
| Supermicro    | X11SDV-4C-TP8F              | Server      | [7b3740b7c0](https://bsd-hardware.info/?probe=7b3740b7c0) | Nov 08, 2023 |
| ZOTAC         | ZBOX-MI643/MI623 Rev.00     | Mini pc     | [709dd91ea2](https://bsd-hardware.info/?probe=709dd91ea2) | Nov 08, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [700d52c2dd](https://bsd-hardware.info/?probe=700d52c2dd) | Nov 07, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [2c085953ca](https://bsd-hardware.info/?probe=2c085953ca) | Nov 07, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [df41e8f6b2](https://bsd-hardware.info/?probe=df41e8f6b2) | Nov 07, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [cf8fb90fe0](https://bsd-hardware.info/?probe=cf8fb90fe0) | Nov 07, 2023 |
| Supermicro    | X11SDV-4C-TP8F              | Server      | [5a26b6b1f5](https://bsd-hardware.info/?probe=5a26b6b1f5) | Nov 07, 2023 |
| Unknown       | Unknown                     | Notebook    | [61c7e94f23](https://bsd-hardware.info/?probe=61c7e94f23) | Nov 06, 2023 |
| Unknown       | Unknown                     | Notebook    | [316be7bb33](https://bsd-hardware.info/?probe=316be7bb33) | Nov 06, 2023 |
| Supermicro    | X10SDV-TP8F                 | Server      | [dc54c810d3](https://bsd-hardware.info/?probe=dc54c810d3) | Nov 06, 2023 |
| MSI           | Z270 PC MATE                | Desktop     | [9686c20980](https://bsd-hardware.info/?probe=9686c20980) | Nov 06, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [b4c8864cef](https://bsd-hardware.info/?probe=b4c8864cef) | Nov 06, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [456fe0a275](https://bsd-hardware.info/?probe=456fe0a275) | Nov 06, 2023 |
| Dell          | Latitude E6540              | Notebook    | [a26912fd0d](https://bsd-hardware.info/?probe=a26912fd0d) | Nov 06, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [4f9885c454](https://bsd-hardware.info/?probe=4f9885c454) | Nov 05, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [ea78913e4c](https://bsd-hardware.info/?probe=ea78913e4c) | Nov 05, 2023 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [38b5f3b9ad](https://bsd-hardware.info/?probe=38b5f3b9ad) | Nov 04, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [86aa07c0ae](https://bsd-hardware.info/?probe=86aa07c0ae) | Nov 04, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | Notebook    | [a9448cf3b5](https://bsd-hardware.info/?probe=a9448cf3b5) | Nov 04, 2023 |
| ASRock        | B365M-HDV                   | Desktop     | [368366454f](https://bsd-hardware.info/?probe=368366454f) | Nov 03, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [19514dd0bd](https://bsd-hardware.info/?probe=19514dd0bd) | Nov 03, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [e6927b5eb8](https://bsd-hardware.info/?probe=e6927b5eb8) | Nov 03, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [13eb07060d](https://bsd-hardware.info/?probe=13eb07060d) | Nov 03, 2023 |
| PC Engines    | apu4                        | Desktop     | [b85acbe43d](https://bsd-hardware.info/?probe=b85acbe43d) | Nov 03, 2023 |
| Fujitsu Si... | D2584-A1 S26361-D2584-A1    | Desktop     | [d4298a293f](https://bsd-hardware.info/?probe=d4298a293f) | Nov 02, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [b038d8a95d](https://bsd-hardware.info/?probe=b038d8a95d) | Nov 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [691338cb44](https://bsd-hardware.info/?probe=691338cb44) | Nov 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [c6610a58ac](https://bsd-hardware.info/?probe=c6610a58ac) | Nov 02, 2023 |
| PICO PC       | MNHO-113                    | Desktop     | [a4175476a0](https://bsd-hardware.info/?probe=a4175476a0) | Nov 02, 2023 |
| Sophos        | SG                          | Firewall    | [24994d8e2f](https://bsd-hardware.info/?probe=24994d8e2f) | Nov 02, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [8d3cf4e648](https://bsd-hardware.info/?probe=8d3cf4e648) | Nov 01, 2023 |
| Fujitsu       | D3544-A1 S26361-D3544-A1... | Desktop     | [2fcac7d927](https://bsd-hardware.info/?probe=2fcac7d927) | Nov 01, 2023 |
| Hardkernel    | ODROID-H2                   | Desktop     | [41c4097002](https://bsd-hardware.info/?probe=41c4097002) | Oct 30, 2023 |
| Sophos        | SG                          | Firewall    | [f9c46ab5cb](https://bsd-hardware.info/?probe=f9c46ab5cb) | Oct 30, 2023 |
| AZW           | EQ                          | Desktop     | [034b060507](https://bsd-hardware.info/?probe=034b060507) | Oct 30, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [ec852f7037](https://bsd-hardware.info/?probe=ec852f7037) | Oct 29, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [c774066857](https://bsd-hardware.info/?probe=c774066857) | Oct 28, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | Desktop     | [fc42f6db17](https://bsd-hardware.info/?probe=fc42f6db17) | Oct 28, 2023 |
| HP            | 1825                        | Desktop     | [8a0a258efc](https://bsd-hardware.info/?probe=8a0a258efc) | Oct 28, 2023 |
| Lenovo        | ThinkPad X230 23205UG       | Notebook    | [f204abc5fc](https://bsd-hardware.info/?probe=f204abc5fc) | Oct 28, 2023 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [6448ed1b12](https://bsd-hardware.info/?probe=6448ed1b12) | Oct 28, 2023 |
| IGEL Techn... | D220                        | Desktop     | [3478db91ef](https://bsd-hardware.info/?probe=3478db91ef) | Oct 28, 2023 |
| Supermicro    | X11SSH-F                    | Desktop     | [73160cea1d](https://bsd-hardware.info/?probe=73160cea1d) | Oct 28, 2023 |
| Intel         | NUC11TNBi3 M11908-500       | Mini pc     | [72634e7285](https://bsd-hardware.info/?probe=72634e7285) | Oct 28, 2023 |
| Protectli     | FW4B                        | Desktop     | [23c31e7f9f](https://bsd-hardware.info/?probe=23c31e7f9f) | Oct 27, 2023 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [5d64d42233](https://bsd-hardware.info/?probe=5d64d42233) | Oct 27, 2023 |
| Fujitsu       | D3314-E1 S26361-D3314-E1    | Desktop     | [2cde7906c1](https://bsd-hardware.info/?probe=2cde7906c1) | Oct 27, 2023 |
| Fujitsu       | D3314-A1 S26361-D3314-A1    | Desktop     | [d005339b5f](https://bsd-hardware.info/?probe=d005339b5f) | Oct 27, 2023 |
| Sophos        | UTM                         | Firewall    | [b6232a012b](https://bsd-hardware.info/?probe=b6232a012b) | Oct 27, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [fe3d35aef8](https://bsd-hardware.info/?probe=fe3d35aef8) | Oct 27, 2023 |
| PC Engines    | apu4                        | Desktop     | [7bbd252741](https://bsd-hardware.info/?probe=7bbd252741) | Oct 27, 2023 |
| Acer          | Veriton X4620G v1.0         | Desktop     | [bc374cdc01](https://bsd-hardware.info/?probe=bc374cdc01) | Oct 26, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [17cdba9414](https://bsd-hardware.info/?probe=17cdba9414) | Oct 26, 2023 |
| Dell          | 0PRWNC A05                  | Server      | [9b44f96ab2](https://bsd-hardware.info/?probe=9b44f96ab2) | Oct 26, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [09cf753c7a](https://bsd-hardware.info/?probe=09cf753c7a) | Oct 26, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [0d97ba1ab0](https://bsd-hardware.info/?probe=0d97ba1ab0) | Oct 24, 2023 |
| Gigabyte      | MZGLKBP-00                  | Desktop     | [dcd8b6e432](https://bsd-hardware.info/?probe=dcd8b6e432) | Oct 24, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [dea9eee8a4](https://bsd-hardware.info/?probe=dea9eee8a4) | Oct 24, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [38b1931562](https://bsd-hardware.info/?probe=38b1931562) | Oct 24, 2023 |
| ZOTAC         | ZBOX-CI341                  | Mini pc     | [cca1027ab8](https://bsd-hardware.info/?probe=cca1027ab8) | Oct 23, 2023 |
| AZW           | EQ                          | Desktop     | [8cb6ac80d2](https://bsd-hardware.info/?probe=8cb6ac80d2) | Oct 23, 2023 |
| HP            | 8103 A01                    | Mini pc     | [9740c7419d](https://bsd-hardware.info/?probe=9740c7419d) | Oct 23, 2023 |
| Unknown       | YL-J3160L4                  | Desktop     | [3192ead8b5](https://bsd-hardware.info/?probe=3192ead8b5) | Oct 22, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [7a57e0a112](https://bsd-hardware.info/?probe=7a57e0a112) | Oct 21, 2023 |
| Sophos        | SG                          | Firewall    | [411f124671](https://bsd-hardware.info/?probe=411f124671) | Oct 21, 2023 |
| Supermicro    | X11SBA-LN4FA                | Server      | [682d4aec9e](https://bsd-hardware.info/?probe=682d4aec9e) | Oct 20, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [8943e5449f](https://bsd-hardware.info/?probe=8943e5449f) | Oct 20, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [b91ffc9125](https://bsd-hardware.info/?probe=b91ffc9125) | Oct 20, 2023 |
| Unknown       | Unknown                     | Notebook    | [363b63c1a1](https://bsd-hardware.info/?probe=363b63c1a1) | Oct 18, 2023 |
| Sophos        | SG                          | Firewall    | [164161ab82](https://bsd-hardware.info/?probe=164161ab82) | Oct 18, 2023 |
| Supermicro    | X10SDV-TP8F                 | Server      | [4a39ad1a98](https://bsd-hardware.info/?probe=4a39ad1a98) | Oct 18, 2023 |
| Unknown       | J3160-4L                    | Desktop     | [d69749afe5](https://bsd-hardware.info/?probe=d69749afe5) | Oct 18, 2023 |
| Sophos        | SG                          | Firewall    | [2ee4ce0769](https://bsd-hardware.info/?probe=2ee4ce0769) | Oct 17, 2023 |
| Fujitsu       | D3049-A1 S26361-D3049-A1... | Server      | [eadbd154ab](https://bsd-hardware.info/?probe=eadbd154ab) | Oct 16, 2023 |
| ASUSTek       | N552VX                      | Notebook    | [f927cf5ba4](https://bsd-hardware.info/?probe=f927cf5ba4) | Oct 16, 2023 |
| PC Engines    | APU2                        | Desktop     | [7fb59a92f0](https://bsd-hardware.info/?probe=7fb59a92f0) | Oct 16, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [5a15dd2166](https://bsd-hardware.info/?probe=5a15dd2166) | Oct 15, 2023 |
| ASRock        | H110M-DVS R3.0              | Desktop     | [abe8593d6e](https://bsd-hardware.info/?probe=abe8593d6e) | Oct 15, 2023 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [4fc886d589](https://bsd-hardware.info/?probe=4fc886d589) | Oct 15, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [eb383d6f22](https://bsd-hardware.info/?probe=eb383d6f22) | Oct 15, 2023 |
| Fujitsu       | LIFEBOOK E744               | Notebook    | [72a9b731f6](https://bsd-hardware.info/?probe=72a9b731f6) | Oct 14, 2023 |
| Supermicro    | A1SRi-2758F                 | Mini pc     | [88725f5ed5](https://bsd-hardware.info/?probe=88725f5ed5) | Oct 14, 2023 |
| Sophos        | SG                          | Firewall    | [93d1eca671](https://bsd-hardware.info/?probe=93d1eca671) | Oct 14, 2023 |
| Deciso        | Netboard A20                | Notebook    | [879efbe255](https://bsd-hardware.info/?probe=879efbe255) | Oct 14, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [248c73db22](https://bsd-hardware.info/?probe=248c73db22) | Oct 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [77a827631b](https://bsd-hardware.info/?probe=77a827631b) | Oct 13, 2023 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [8b0d009cc4](https://bsd-hardware.info/?probe=8b0d009cc4) | Oct 13, 2023 |
| Sophos        | SG                          | Firewall    | [896045150c](https://bsd-hardware.info/?probe=896045150c) | Oct 13, 2023 |
| Unknown       | YL-J3160L4                  | Desktop     | [65acf27cad](https://bsd-hardware.info/?probe=65acf27cad) | Oct 13, 2023 |
| Dell          | 08CYF7 A05                  | Server      | [6b8bbc4ad9](https://bsd-hardware.info/?probe=6b8bbc4ad9) | Oct 13, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [516eda52f0](https://bsd-hardware.info/?probe=516eda52f0) | Oct 12, 2023 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [bb82c13e39](https://bsd-hardware.info/?probe=bb82c13e39) | Oct 12, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [418d78095d](https://bsd-hardware.info/?probe=418d78095d) | Oct 12, 2023 |
| Yanling       | YL-CLU6L-V1                 | Desktop     | [f3b384d87a](https://bsd-hardware.info/?probe=f3b384d87a) | Oct 12, 2023 |
| Lenovo        | ThinkPad X250 20CM004VFR    | Notebook    | [e4ab2acd8d](https://bsd-hardware.info/?probe=e4ab2acd8d) | Oct 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [30ec824cf5](https://bsd-hardware.info/?probe=30ec824cf5) | Oct 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [3d5abb3996](https://bsd-hardware.info/?probe=3d5abb3996) | Oct 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [e4faecc5e8](https://bsd-hardware.info/?probe=e4faecc5e8) | Oct 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [5031b0a5a7](https://bsd-hardware.info/?probe=5031b0a5a7) | Oct 10, 2023 |
| Yanling       | YL-CLU6L-V1                 | Desktop     | [cf15e11738](https://bsd-hardware.info/?probe=cf15e11738) | Oct 10, 2023 |
| Unknown       | QD-CMU01                    | Desktop     | [8637821e57](https://bsd-hardware.info/?probe=8637821e57) | Oct 09, 2023 |
| Sophos        | UTM                         | Firewall    | [002d6256fa](https://bsd-hardware.info/?probe=002d6256fa) | Oct 09, 2023 |
| ASRock        | A75M-HVS                    | Desktop     | [93709074ae](https://bsd-hardware.info/?probe=93709074ae) | Oct 09, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [862d0bbe4d](https://bsd-hardware.info/?probe=862d0bbe4d) | Oct 08, 2023 |
| Sophos        | SG                          | Firewall    | [2e19b2128b](https://bsd-hardware.info/?probe=2e19b2128b) | Oct 08, 2023 |
| Unknown       | Unknown                     | Notebook    | [57e5ab8786](https://bsd-hardware.info/?probe=57e5ab8786) | Oct 08, 2023 |
| Unknown       | Unknown                     | Notebook    | [1f7ab105e3](https://bsd-hardware.info/?probe=1f7ab105e3) | Oct 08, 2023 |
| Intel         | DENLOW_WS                   | Desktop     | [11b0d7b64f](https://bsd-hardware.info/?probe=11b0d7b64f) | Oct 07, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [d7a7e7338f](https://bsd-hardware.info/?probe=d7a7e7338f) | Oct 07, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [e3141878a9](https://bsd-hardware.info/?probe=e3141878a9) | Oct 07, 2023 |
| ASRock        | J5040-ITX                   | Desktop     | [dffb96790c](https://bsd-hardware.info/?probe=dffb96790c) | Oct 06, 2023 |
| GoWin Solu... | R86S                        | Desktop     | [91b63fa5c7](https://bsd-hardware.info/?probe=91b63fa5c7) | Oct 06, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [31c7e1d3f3](https://bsd-hardware.info/?probe=31c7e1d3f3) | Oct 06, 2023 |
| Deciso        | Netboard A8                 | Desktop     | [cf3b678212](https://bsd-hardware.info/?probe=cf3b678212) | Oct 06, 2023 |
| Fujitsu       | D3633-S1 S26361-D3633-S1    | Desktop     | [5b33d7b22e](https://bsd-hardware.info/?probe=5b33d7b22e) | Oct 04, 2023 |
| PC Engines    | APU2                        | Desktop     | [626d74b530](https://bsd-hardware.info/?probe=626d74b530) | Oct 04, 2023 |
| PC Engines    | apu4                        | Desktop     | [0e813a0050](https://bsd-hardware.info/?probe=0e813a0050) | Oct 04, 2023 |
| Sophos        | SG                          | Firewall    | [c91ad52ddf](https://bsd-hardware.info/?probe=c91ad52ddf) | Oct 04, 2023 |
| Dell          | Latitude 5591               | Notebook    | [8f6ca1e82a](https://bsd-hardware.info/?probe=8f6ca1e82a) | Oct 03, 2023 |
| Fujitsu       | D2863 S26361-D2863-A10 W... | Server      | [f2d65698fb](https://bsd-hardware.info/?probe=f2d65698fb) | Oct 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [f5e7677e76](https://bsd-hardware.info/?probe=f5e7677e76) | Oct 01, 2023 |
| PC Engines    | APU2                        | Desktop     | [064fd13617](https://bsd-hardware.info/?probe=064fd13617) | Oct 01, 2023 |
| Sophos        | SG                          | Firewall    | [40e14eca4b](https://bsd-hardware.info/?probe=40e14eca4b) | Oct 01, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [5524017014](https://bsd-hardware.info/?probe=5524017014) | Oct 01, 2023 |
| Sophos        | SG                          | Firewall    | [13acf2a462](https://bsd-hardware.info/?probe=13acf2a462) | Oct 01, 2023 |
| Unknown       | Unknown                     | Notebook    | [7cfd3d40eb](https://bsd-hardware.info/?probe=7cfd3d40eb) | Sep 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [716f9b28ab](https://bsd-hardware.info/?probe=716f9b28ab) | Sep 30, 2023 |
| Sophos        | SG                          | Firewall    | [c46ccbd5b9](https://bsd-hardware.info/?probe=c46ccbd5b9) | Sep 30, 2023 |
| Sophos        | SG                          | Firewall    | [1429a7de9a](https://bsd-hardware.info/?probe=1429a7de9a) | Sep 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [fb21a44f71](https://bsd-hardware.info/?probe=fb21a44f71) | Sep 29, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [f50d617197](https://bsd-hardware.info/?probe=f50d617197) | Sep 28, 2023 |
| Gigabyte      | B450M S2H V2                | Desktop     | [31da8655d1](https://bsd-hardware.info/?probe=31da8655d1) | Sep 28, 2023 |
| Dell          | Latitude 5591               | Notebook    | [c30943def8](https://bsd-hardware.info/?probe=c30943def8) | Sep 28, 2023 |
| Sophos        | SG                          | Firewall    | [e6a4159f0c](https://bsd-hardware.info/?probe=e6a4159f0c) | Sep 28, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [b3f0a784ab](https://bsd-hardware.info/?probe=b3f0a784ab) | Sep 28, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [0b2b7195c1](https://bsd-hardware.info/?probe=0b2b7195c1) | Sep 26, 2023 |
| Unknown       | YL-J1900L4-V2               | Desktop     | [c186f8b50c](https://bsd-hardware.info/?probe=c186f8b50c) | Sep 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [1ba135fef1](https://bsd-hardware.info/?probe=1ba135fef1) | Sep 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [9c8516c8a8](https://bsd-hardware.info/?probe=9c8516c8a8) | Sep 24, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [6a2ce1e29f](https://bsd-hardware.info/?probe=6a2ce1e29f) | Sep 24, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [b31f8c12f8](https://bsd-hardware.info/?probe=b31f8c12f8) | Sep 24, 2023 |
| NU591         | 1.0                         | Desktop     | [99f3260ee0](https://bsd-hardware.info/?probe=99f3260ee0) | Sep 24, 2023 |
| Supermicro    | X10SDV-TP8F                 | Server      | [d99ed8ecd0](https://bsd-hardware.info/?probe=d99ed8ecd0) | Sep 23, 2023 |
| Supermicro    | X10SDV-TP8F                 | Server      | [80f0800cee](https://bsd-hardware.info/?probe=80f0800cee) | Sep 23, 2023 |
| PC Engines    | APU2                        | Desktop     | [3c7bd005ef](https://bsd-hardware.info/?probe=3c7bd005ef) | Sep 23, 2023 |
| Yanling       | YL-CLU6L-V1                 | Desktop     | [06d8f02eb7](https://bsd-hardware.info/?probe=06d8f02eb7) | Sep 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [16640c7f04](https://bsd-hardware.info/?probe=16640c7f04) | Sep 22, 2023 |
| Sophos        | SG                          | Firewall    | [54ff756b5b](https://bsd-hardware.info/?probe=54ff756b5b) | Sep 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [fcde651e99](https://bsd-hardware.info/?probe=fcde651e99) | Sep 21, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [e046bd9405](https://bsd-hardware.info/?probe=e046bd9405) | Sep 21, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [90f89eea16](https://bsd-hardware.info/?probe=90f89eea16) | Sep 21, 2023 |
| ASRock        | J3455B-ITX                  | Desktop     | [c5a2093552](https://bsd-hardware.info/?probe=c5a2093552) | Sep 21, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [de1bdf0601](https://bsd-hardware.info/?probe=de1bdf0601) | Sep 21, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [e84cddfaaf](https://bsd-hardware.info/?probe=e84cddfaaf) | Sep 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [3c479d7824](https://bsd-hardware.info/?probe=3c479d7824) | Sep 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [13ba11c952](https://bsd-hardware.info/?probe=13ba11c952) | Sep 20, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [92da10b93b](https://bsd-hardware.info/?probe=92da10b93b) | Sep 20, 2023 |
| Unknown       | SKYBAY                      | Desktop     | [95286f41d9](https://bsd-hardware.info/?probe=95286f41d9) | Sep 19, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [3950a0580d](https://bsd-hardware.info/?probe=3950a0580d) | Sep 16, 2023 |
| Intel         | DENLOW_WS                   | Desktop     | [029b3cdd58](https://bsd-hardware.info/?probe=029b3cdd58) | Sep 16, 2023 |
| Dell          | 0R5KP9 A09                  | Server      | [54ff0b9d41](https://bsd-hardware.info/?probe=54ff0b9d41) | Sep 16, 2023 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [80707f8712](https://bsd-hardware.info/?probe=80707f8712) | Sep 16, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [9a30d2d88c](https://bsd-hardware.info/?probe=9a30d2d88c) | Sep 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [1808e7891c](https://bsd-hardware.info/?probe=1808e7891c) | Sep 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [d6acb378a1](https://bsd-hardware.info/?probe=d6acb378a1) | Sep 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [fe010506e6](https://bsd-hardware.info/?probe=fe010506e6) | Sep 15, 2023 |
| Alienware     | m15                         | Notebook    | [609d2ce1ce](https://bsd-hardware.info/?probe=609d2ce1ce) | Sep 14, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [227062e965](https://bsd-hardware.info/?probe=227062e965) | Sep 13, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [0068732d33](https://bsd-hardware.info/?probe=0068732d33) | Sep 13, 2023 |
| Dell          | 0KM5PX A02                  | Server      | [2028895de0](https://bsd-hardware.info/?probe=2028895de0) | Sep 13, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [5c89a7a1f1](https://bsd-hardware.info/?probe=5c89a7a1f1) | Sep 13, 2023 |
| HP            | ProBook 4530s               | Notebook    | [0b47c15c42](https://bsd-hardware.info/?probe=0b47c15c42) | Sep 12, 2023 |
| HP            | ProBook 4530s               | Notebook    | [4b6daa1f1c](https://bsd-hardware.info/?probe=4b6daa1f1c) | Sep 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [fd131bd648](https://bsd-hardware.info/?probe=fd131bd648) | Sep 11, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [0797783a1c](https://bsd-hardware.info/?probe=0797783a1c) | Sep 10, 2023 |
| Supermicro    | A1SRi-2558F                 | Mini pc     | [04e0638cca](https://bsd-hardware.info/?probe=04e0638cca) | Sep 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [3c85271913](https://bsd-hardware.info/?probe=3c85271913) | Sep 10, 2023 |
| HP            | 8103 A01                    | Mini pc     | [ff26b688eb](https://bsd-hardware.info/?probe=ff26b688eb) | Sep 09, 2023 |
| Apple         | PowerMac3,6                 | Desktop     | [36daf7ce75](https://bsd-hardware.info/?probe=36daf7ce75) | Sep 09, 2023 |
| Lenovo        | ThinkPad SL 2746N8G         | Notebook    | [07eda65608](https://bsd-hardware.info/?probe=07eda65608) | Sep 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [3bc1fc9c7b](https://bsd-hardware.info/?probe=3bc1fc9c7b) | Sep 09, 2023 |
| Sophos        | XG                          | Firewall    | [01ed655ea2](https://bsd-hardware.info/?probe=01ed655ea2) | Sep 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [68a0e23945](https://bsd-hardware.info/?probe=68a0e23945) | Sep 09, 2023 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [1d5aff2e2a](https://bsd-hardware.info/?probe=1d5aff2e2a) | Sep 08, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [fe6bcbc332](https://bsd-hardware.info/?probe=fe6bcbc332) | Sep 08, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [37e25cbcec](https://bsd-hardware.info/?probe=37e25cbcec) | Sep 08, 2023 |
| Lex           | Pineview-D                  | Desktop     | [351aabdb80](https://bsd-hardware.info/?probe=351aabdb80) | Sep 08, 2023 |
| PC Engines    | APU3                        | Desktop     | [ad38dcf54a](https://bsd-hardware.info/?probe=ad38dcf54a) | Sep 07, 2023 |
| IceWhale T... | ZimaBoard 432 ZMB           | Desktop     | [451cfdf64f](https://bsd-hardware.info/?probe=451cfdf64f) | Sep 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [6361addd62](https://bsd-hardware.info/?probe=6361addd62) | Sep 06, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [48ca84af37](https://bsd-hardware.info/?probe=48ca84af37) | Sep 06, 2023 |
| PC Engines    | APU2                        | Desktop     | [d582e62190](https://bsd-hardware.info/?probe=d582e62190) | Sep 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [f757c58686](https://bsd-hardware.info/?probe=f757c58686) | Sep 05, 2023 |
| Dell          | 0PRWNC A05                  | Server      | [ded67b8cd6](https://bsd-hardware.info/?probe=ded67b8cd6) | Sep 04, 2023 |
| Dell          | 03X6X0 A02                  | Server      | [8d9b81f936](https://bsd-hardware.info/?probe=8d9b81f936) | Sep 04, 2023 |
| Supermicro    | X10SDV-TP8F                 | Server      | [25cc035e73](https://bsd-hardware.info/?probe=25cc035e73) | Sep 03, 2023 |
| PC Engines    | APU2                        | Desktop     | [c9d2cfe6fa](https://bsd-hardware.info/?probe=c9d2cfe6fa) | Sep 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [53cee3b3c8](https://bsd-hardware.info/?probe=53cee3b3c8) | Sep 03, 2023 |
| Biostar       | J4105NHU                    | Desktop     | [2ac770aa55](https://bsd-hardware.info/?probe=2ac770aa55) | Sep 03, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [f95d1da00c](https://bsd-hardware.info/?probe=f95d1da00c) | Sep 01, 2023 |
| Inventec      | Z CLASS A02                 | Desktop     | [1f4bf47cab](https://bsd-hardware.info/?probe=1f4bf47cab) | Sep 01, 2023 |
| Sophos        | UTM                         | Firewall    | [01a7eea7b9](https://bsd-hardware.info/?probe=01a7eea7b9) | Aug 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [b59ce07b49](https://bsd-hardware.info/?probe=b59ce07b49) | Aug 30, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [56ac0149f8](https://bsd-hardware.info/?probe=56ac0149f8) | Aug 30, 2023 |
| CncTion       | N6000-4L B0                 | Desktop     | [81cbfbffca](https://bsd-hardware.info/?probe=81cbfbffca) | Aug 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [fc384f5de7](https://bsd-hardware.info/?probe=fc384f5de7) | Aug 28, 2023 |
| IceWhale T... | ZimaBoard 432 ZMB           | Desktop     | [a47cd8ee32](https://bsd-hardware.info/?probe=a47cd8ee32) | Aug 27, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [5025d5adb6](https://bsd-hardware.info/?probe=5025d5adb6) | Aug 27, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [a684024d8e](https://bsd-hardware.info/?probe=a684024d8e) | Aug 27, 2023 |
| PC Engines    | APU                         | Desktop     | [3b29671556](https://bsd-hardware.info/?probe=3b29671556) | Aug 26, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [ed6162710b](https://bsd-hardware.info/?probe=ed6162710b) | Aug 26, 2023 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [a487121854](https://bsd-hardware.info/?probe=a487121854) | Aug 26, 2023 |
| IGEL Techn... | D220                        | Desktop     | [a7686520e1](https://bsd-hardware.info/?probe=a7686520e1) | Aug 26, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [662ce63a50](https://bsd-hardware.info/?probe=662ce63a50) | Aug 25, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [8c6f7098f9](https://bsd-hardware.info/?probe=8c6f7098f9) | Aug 25, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [b8f1609842](https://bsd-hardware.info/?probe=b8f1609842) | Aug 25, 2023 |
| CncTion       | N6000-4L B0                 | Desktop     | [d8a9af2435](https://bsd-hardware.info/?probe=d8a9af2435) | Aug 24, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [a8fa821e5e](https://bsd-hardware.info/?probe=a8fa821e5e) | Aug 24, 2023 |
| Supermicro    | H12SSW-iN                   | Server      | [d0be592303](https://bsd-hardware.info/?probe=d0be592303) | Aug 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [74a7137090](https://bsd-hardware.info/?probe=74a7137090) | Aug 22, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [8622d78a7c](https://bsd-hardware.info/?probe=8622d78a7c) | Aug 22, 2023 |
| Gigabyte      | H610I DDR4                  | Desktop     | [f4310832c2](https://bsd-hardware.info/?probe=f4310832c2) | Aug 22, 2023 |
| Intel         | JSL MRD                     | Desktop     | [56165c654b](https://bsd-hardware.info/?probe=56165c654b) | Aug 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [03da20b37e](https://bsd-hardware.info/?probe=03da20b37e) | Aug 22, 2023 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [71e00307ae](https://bsd-hardware.info/?probe=71e00307ae) | Aug 22, 2023 |
| PC Engines    | APU2                        | Desktop     | [3e32acfdc4](https://bsd-hardware.info/?probe=3e32acfdc4) | Aug 22, 2023 |
| Gigabyte      | H110M-D2P-WG-CF             | Desktop     | [a91c61e3e3](https://bsd-hardware.info/?probe=a91c61e3e3) | Aug 21, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [ef28836f5c](https://bsd-hardware.info/?probe=ef28836f5c) | Aug 20, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [01d58784e6](https://bsd-hardware.info/?probe=01d58784e6) | Aug 20, 2023 |
| HP            | 8594                        | Desktop     | [b3e5652c1b](https://bsd-hardware.info/?probe=b3e5652c1b) | Aug 20, 2023 |
| HP            | 8594                        | Desktop     | [77d6ac3f77](https://bsd-hardware.info/?probe=77d6ac3f77) | Aug 20, 2023 |
| Sophos        | XG                          | Firewall    | [2f35580968](https://bsd-hardware.info/?probe=2f35580968) | Aug 19, 2023 |
| Sophos        | SG                          | Firewall    | [30708a275a](https://bsd-hardware.info/?probe=30708a275a) | Aug 18, 2023 |
| Dell          | Latitude 5591               | Notebook    | [972da999fb](https://bsd-hardware.info/?probe=972da999fb) | Aug 18, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [b3625ada4b](https://bsd-hardware.info/?probe=b3625ada4b) | Aug 18, 2023 |
| Unknown       | Unknown                     | Desktop     | [de9a146c44](https://bsd-hardware.info/?probe=de9a146c44) | Aug 16, 2023 |
| Unknown       | Q2XX V1.0                   | Desktop     | [be1252b2ff](https://bsd-hardware.info/?probe=be1252b2ff) | Aug 16, 2023 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [18559e2fde](https://bsd-hardware.info/?probe=18559e2fde) | Aug 15, 2023 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [73c35b0a8a](https://bsd-hardware.info/?probe=73c35b0a8a) | Aug 15, 2023 |
| Intel         | SKYBAY                      | Desktop     | [77fbc82e41](https://bsd-hardware.info/?probe=77fbc82e41) | Aug 15, 2023 |
| Protectli     | VP4620                      | Desktop     | [0f0695d190](https://bsd-hardware.info/?probe=0f0695d190) | Aug 15, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [680fdcd4f6](https://bsd-hardware.info/?probe=680fdcd4f6) | Aug 14, 2023 |
| PC Engines    | APU2                        | Desktop     | [bdd3050b5f](https://bsd-hardware.info/?probe=bdd3050b5f) | Aug 14, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [b8e7299136](https://bsd-hardware.info/?probe=b8e7299136) | Aug 13, 2023 |
| Dell          | Latitude 5591               | Notebook    | [a599361016](https://bsd-hardware.info/?probe=a599361016) | Aug 13, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [6c4364fe15](https://bsd-hardware.info/?probe=6c4364fe15) | Aug 13, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [b978121948](https://bsd-hardware.info/?probe=b978121948) | Aug 13, 2023 |
| PC Engines    | apu4                        | Desktop     | [24e025662c](https://bsd-hardware.info/?probe=24e025662c) | Aug 12, 2023 |
| CncTion       | J4125-4L-I225               | Desktop     | [983bbef1fb](https://bsd-hardware.info/?probe=983bbef1fb) | Aug 12, 2023 |
| WeiBu         | ADL-N Prod                  | Desktop     | [26bbe26e7c](https://bsd-hardware.info/?probe=26bbe26e7c) | Aug 12, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [27f84c75b5](https://bsd-hardware.info/?probe=27f84c75b5) | Aug 11, 2023 |
| PC Engines    | APU2                        | Desktop     | [2e9106fc92](https://bsd-hardware.info/?probe=2e9106fc92) | Aug 11, 2023 |
| Gigabyte      | AX370M-DS3H-CF              | Desktop     | [7b00ddd0a1](https://bsd-hardware.info/?probe=7b00ddd0a1) | Aug 11, 2023 |
| PC Engines    | apu1                        | Desktop     | [0b3594d9a3](https://bsd-hardware.info/?probe=0b3594d9a3) | Aug 11, 2023 |
| PC Engines    | apu4                        | Desktop     | [b81f51408d](https://bsd-hardware.info/?probe=b81f51408d) | Aug 10, 2023 |
| Sophos        | SG                          | Firewall    | [ee7cfb0c22](https://bsd-hardware.info/?probe=ee7cfb0c22) | Aug 10, 2023 |
| Sophos        | UTM                         | Firewall    | [e7e8344a31](https://bsd-hardware.info/?probe=e7e8344a31) | Aug 09, 2023 |
| PC Engines    | APU2                        | Desktop     | [be0e8bf959](https://bsd-hardware.info/?probe=be0e8bf959) | Aug 09, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [fac2fa5cbe](https://bsd-hardware.info/?probe=fac2fa5cbe) | Aug 08, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [8720a76ea8](https://bsd-hardware.info/?probe=8720a76ea8) | Aug 08, 2023 |
| Fujitsu       | D3049-A1 S26361-D3049-A1... | Server      | [322b24ffa1](https://bsd-hardware.info/?probe=322b24ffa1) | Aug 08, 2023 |
| Acer          | Veriton N2620G              | Desktop     | [2acf1e4557](https://bsd-hardware.info/?probe=2acf1e4557) | Aug 08, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [aeccb6e70c](https://bsd-hardware.info/?probe=aeccb6e70c) | Aug 07, 2023 |
| Lanner        | FW-7543 B-GA                | Desktop     | [dadf592128](https://bsd-hardware.info/?probe=dadf592128) | Aug 06, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [eceed9eb7a](https://bsd-hardware.info/?probe=eceed9eb7a) | Aug 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [9c4dbcfd67](https://bsd-hardware.info/?probe=9c4dbcfd67) | Aug 05, 2023 |
| Lanner        | FW-7543 B-GA                | Desktop     | [6236e692de](https://bsd-hardware.info/?probe=6236e692de) | Aug 05, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | Desktop     | [283fce4c68](https://bsd-hardware.info/?probe=283fce4c68) | Aug 05, 2023 |
| CWWK          | MINIPC-G12                  | Desktop     | [c449203453](https://bsd-hardware.info/?probe=c449203453) | Aug 04, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [ea7a6fba73](https://bsd-hardware.info/?probe=ea7a6fba73) | Aug 04, 2023 |
| Lenovo        | SHARKBAY NO DPK             | Desktop     | [62ed2f59f6](https://bsd-hardware.info/?probe=62ed2f59f6) | Aug 04, 2023 |
| Supermicro    | A2SDi-4C-HLN4F              | Server      | [b6aafbefd3](https://bsd-hardware.info/?probe=b6aafbefd3) | Aug 04, 2023 |
| PC Engines    | APU2                        | Desktop     | [78c8ed6a89](https://bsd-hardware.info/?probe=78c8ed6a89) | Aug 03, 2023 |
| Dell          | 045M96 A02                  | Server      | [17cf8cd2f0](https://bsd-hardware.info/?probe=17cf8cd2f0) | Aug 03, 2023 |
| Supermicro    | A2SDi-4C-HLN4F              | Server      | [b3fd8251db](https://bsd-hardware.info/?probe=b3fd8251db) | Aug 02, 2023 |
| Shuttle       | DH610                       | Desktop     | [bbdd78fe4b](https://bsd-hardware.info/?probe=bbdd78fe4b) | Aug 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [42c65b8b8b](https://bsd-hardware.info/?probe=42c65b8b8b) | Aug 01, 2023 |
| Unknown       | Unknown                     | Notebook    | [09d17597cf](https://bsd-hardware.info/?probe=09d17597cf) | Aug 01, 2023 |
| Unknown       | Unknown                     | Notebook    | [2a2e7a98e3](https://bsd-hardware.info/?probe=2a2e7a98e3) | Aug 01, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [65667b2f29](https://bsd-hardware.info/?probe=65667b2f29) | Aug 01, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [aa708122cf](https://bsd-hardware.info/?probe=aa708122cf) | Aug 01, 2023 |
| Shuttle       | DH610                       | Desktop     | [e7c63c97d3](https://bsd-hardware.info/?probe=e7c63c97d3) | Aug 01, 2023 |
| Shuttle       | DH370                       | Desktop     | [a3ab1c6344](https://bsd-hardware.info/?probe=a3ab1c6344) | Jul 31, 2023 |
| Deciso        | NetBoard-A20                | Notebook    | [9bd5d8fd54](https://bsd-hardware.info/?probe=9bd5d8fd54) | Jul 31, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [42fcdacbf7](https://bsd-hardware.info/?probe=42fcdacbf7) | Jul 31, 2023 |
| Lenovo        | ThinkPad X230 23202DG       | Notebook    | [f8ade878ce](https://bsd-hardware.info/?probe=f8ade878ce) | Jul 30, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [64137e0eec](https://bsd-hardware.info/?probe=64137e0eec) | Jul 29, 2023 |
| HP            | Notebook                    | Notebook    | [360790274a](https://bsd-hardware.info/?probe=360790274a) | Jul 29, 2023 |
| AWOW          | AK34Pro                     | Mini pc     | [7c8e0ac36d](https://bsd-hardware.info/?probe=7c8e0ac36d) | Jul 29, 2023 |
| PC Engines    | APU2                        | Desktop     | [5eddd5369a](https://bsd-hardware.info/?probe=5eddd5369a) | Jul 28, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [0bb6b16689](https://bsd-hardware.info/?probe=0bb6b16689) | Jul 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [1c6ab6b999](https://bsd-hardware.info/?probe=1c6ab6b999) | Jul 28, 2023 |
| Sophos        | UTM                         | Firewall    | [c33c212896](https://bsd-hardware.info/?probe=c33c212896) | Jul 28, 2023 |
| PC Engines    | apu1                        | Desktop     | [8bc97daada](https://bsd-hardware.info/?probe=8bc97daada) | Jul 27, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [64b577cd8e](https://bsd-hardware.info/?probe=64b577cd8e) | Jul 27, 2023 |
| NF541         | 1.0                         | Desktop     | [ba959613a5](https://bsd-hardware.info/?probe=ba959613a5) | Jul 26, 2023 |
| Cisco         | ASA5525 A0                  | Desktop     | [f4409bdc8f](https://bsd-hardware.info/?probe=f4409bdc8f) | Jul 26, 2023 |
| Supermicro    | X10SDV-TP8F                 | Server      | [d9c7f4173a](https://bsd-hardware.info/?probe=d9c7f4173a) | Jul 25, 2023 |
| Sophos        | XG                          | Firewall    | [bcf0e85fdc](https://bsd-hardware.info/?probe=bcf0e85fdc) | Jul 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [f7728cee03](https://bsd-hardware.info/?probe=f7728cee03) | Jul 25, 2023 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [8aa3f5491e](https://bsd-hardware.info/?probe=8aa3f5491e) | Jul 25, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | Desktop     | [af215ad226](https://bsd-hardware.info/?probe=af215ad226) | Jul 24, 2023 |
| PC Engines    | apu4                        | Desktop     | [0aa9951131](https://bsd-hardware.info/?probe=0aa9951131) | Jul 24, 2023 |
| PC Engines    | apu4                        | Desktop     | [514dc1e9f9](https://bsd-hardware.info/?probe=514dc1e9f9) | Jul 24, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [dec2c34899](https://bsd-hardware.info/?probe=dec2c34899) | Jul 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [aab49bd228](https://bsd-hardware.info/?probe=aab49bd228) | Jul 24, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS       | Desktop     | [438424a9d9](https://bsd-hardware.info/?probe=438424a9d9) | Jul 23, 2023 |
| PC Engines    | apu4                        | Desktop     | [ea9a81b423](https://bsd-hardware.info/?probe=ea9a81b423) | Jul 23, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [3b16dab962](https://bsd-hardware.info/?probe=3b16dab962) | Jul 22, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [7e1b416d09](https://bsd-hardware.info/?probe=7e1b416d09) | Jul 21, 2023 |
| Yanling       | YL-CLU6L-V1                 | Desktop     | [489c685ec4](https://bsd-hardware.info/?probe=489c685ec4) | Jul 21, 2023 |
| AZW           | EQ                          | Desktop     | [9883a89b8d](https://bsd-hardware.info/?probe=9883a89b8d) | Jul 21, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [efe49f9e5d](https://bsd-hardware.info/?probe=efe49f9e5d) | Jul 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [cce6d65dfb](https://bsd-hardware.info/?probe=cce6d65dfb) | Jul 20, 2023 |
| Lenovo        | ThinkPad T520 42435GG       | Notebook    | [f3aa06579e](https://bsd-hardware.info/?probe=f3aa06579e) | Jul 20, 2023 |
| Dell          | 08CYF7 A03                  | Server      | [67e68a4ad9](https://bsd-hardware.info/?probe=67e68a4ad9) | Jul 19, 2023 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [cbb13789d2](https://bsd-hardware.info/?probe=cbb13789d2) | Jul 19, 2023 |
| Dell          | 0MD99X A12                  | Server      | [eaabbf3ff3](https://bsd-hardware.info/?probe=eaabbf3ff3) | Jul 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [e487955dea](https://bsd-hardware.info/?probe=e487955dea) | Jul 18, 2023 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [35ab9e002d](https://bsd-hardware.info/?probe=35ab9e002d) | Jul 17, 2023 |
| Samsung       | RC530/RC730                 | Notebook    | [b76e5e8a87](https://bsd-hardware.info/?probe=b76e5e8a87) | Jul 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [8d82f25df2](https://bsd-hardware.info/?probe=8d82f25df2) | Jul 16, 2023 |
| Unknown       | Unknown                     | Firewall    | [af05859a76](https://bsd-hardware.info/?probe=af05859a76) | Jul 16, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [a2602b7fbf](https://bsd-hardware.info/?probe=a2602b7fbf) | Jul 16, 2023 |
| Gigabyte      | GB-BSi7-1165G7              | Desktop     | [c5f92a4c5e](https://bsd-hardware.info/?probe=c5f92a4c5e) | Jul 14, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [0b90f241cd](https://bsd-hardware.info/?probe=0b90f241cd) | Jul 13, 2023 |
| PICO PC       | JSL-4L                      | Desktop     | [d93e338744](https://bsd-hardware.info/?probe=d93e338744) | Jul 13, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [535720220a](https://bsd-hardware.info/?probe=535720220a) | Jul 13, 2023 |
| Supermicro    | X11SCH-F                    | Server      | [8f25848f38](https://bsd-hardware.info/?probe=8f25848f38) | Jul 13, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [c2cb1e21fa](https://bsd-hardware.info/?probe=c2cb1e21fa) | Jul 11, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [96bda9f774](https://bsd-hardware.info/?probe=96bda9f774) | Jul 11, 2023 |
| Tactus        | GeoBook 140                 | Notebook    | [4b7383c876](https://bsd-hardware.info/?probe=4b7383c876) | Jul 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [5625dd24f6](https://bsd-hardware.info/?probe=5625dd24f6) | Jul 11, 2023 |
| PICO PC       | JSL-4L                      | Desktop     | [d8c9a61dcf](https://bsd-hardware.info/?probe=d8c9a61dcf) | Jul 10, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [3a544928aa](https://bsd-hardware.info/?probe=3a544928aa) | Jul 09, 2023 |
| MiTAC         | PH13CMI                     | Desktop     | [6d0cd37fce](https://bsd-hardware.info/?probe=6d0cd37fce) | Jul 09, 2023 |
| Biostar       | A68N-2100K                  | Desktop     | [20cb208208](https://bsd-hardware.info/?probe=20cb208208) | Jul 09, 2023 |
| Lex           | Pineview-D                  | Desktop     | [290c53a822](https://bsd-hardware.info/?probe=290c53a822) | Jul 09, 2023 |
| Lenovo        | ThinkPad X250 20CLS13Q06    | Notebook    | [c318ab3cc7](https://bsd-hardware.info/?probe=c318ab3cc7) | Jul 09, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [9cd5d7878b](https://bsd-hardware.info/?probe=9cd5d7878b) | Jul 07, 2023 |
| Yanling       | YL-ELU3L                    | Desktop     | [0a3c74b25c](https://bsd-hardware.info/?probe=0a3c74b25c) | Jul 07, 2023 |
| ASRock        | A300M-STX                   | Desktop     | [5d896a607e](https://bsd-hardware.info/?probe=5d896a607e) | Jul 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [3644875d54](https://bsd-hardware.info/?probe=3644875d54) | Jul 03, 2023 |
| Supermicro    | X10SLH-F/X10SLM+-F          | Server      | [877c048c7d](https://bsd-hardware.info/?probe=877c048c7d) | Jul 03, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [2053dbb697](https://bsd-hardware.info/?probe=2053dbb697) | Jul 03, 2023 |
| Unknown       | Unknown                     | Notebook    | [3725d44c33](https://bsd-hardware.info/?probe=3725d44c33) | Jul 01, 2023 |
| Supermicro    | X11SCL-IF                   | Server      | [0f9a1dc60c](https://bsd-hardware.info/?probe=0f9a1dc60c) | Jul 01, 2023 |
| PC Engines    | apu4                        | Desktop     | [62f0b60653](https://bsd-hardware.info/?probe=62f0b60653) | Jun 30, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [d60c967edb](https://bsd-hardware.info/?probe=d60c967edb) | Jun 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [075deef24f](https://bsd-hardware.info/?probe=075deef24f) | Jun 28, 2023 |
| CncTion       | J4125-4L-I225               | Desktop     | [1785cb2fa3](https://bsd-hardware.info/?probe=1785cb2fa3) | Jun 28, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [2eff359d8f](https://bsd-hardware.info/?probe=2eff359d8f) | Jun 28, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [bcad942162](https://bsd-hardware.info/?probe=bcad942162) | Jun 26, 2023 |
| Unknown       | YL-SKUL6                    | Desktop     | [1512f63972](https://bsd-hardware.info/?probe=1512f63972) | Jun 26, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [fa177a2538](https://bsd-hardware.info/?probe=fa177a2538) | Jun 26, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [54ef7dc131](https://bsd-hardware.info/?probe=54ef7dc131) | Jun 26, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [b056cd0426](https://bsd-hardware.info/?probe=b056cd0426) | Jun 26, 2023 |
| Unknown       | J3160-4L                    | Desktop     | [5ad411cd6b](https://bsd-hardware.info/?probe=5ad411cd6b) | Jun 25, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [8a2ea60929](https://bsd-hardware.info/?probe=8a2ea60929) | Jun 25, 2023 |
| Sophos        | SG                          | Firewall    | [11e1176b5e](https://bsd-hardware.info/?probe=11e1176b5e) | Jun 24, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [18cf91f3a4](https://bsd-hardware.info/?probe=18cf91f3a4) | Jun 23, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [bb4dc2b1a2](https://bsd-hardware.info/?probe=bb4dc2b1a2) | Jun 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [16ceade742](https://bsd-hardware.info/?probe=16ceade742) | Jun 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [508aa0bdb4](https://bsd-hardware.info/?probe=508aa0bdb4) | Jun 23, 2023 |
| Sophos        | SG                          | Firewall    | [6763145000](https://bsd-hardware.info/?probe=6763145000) | Jun 22, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [4f80d81bbe](https://bsd-hardware.info/?probe=4f80d81bbe) | Jun 20, 2023 |
| Lenovo        | ThinkPad T430 2347A45       | Notebook    | [6969cd9e1a](https://bsd-hardware.info/?probe=6969cd9e1a) | Jun 20, 2023 |
| Lenovo        | ThinkPad T430 2347A45       | Notebook    | [461a92a1a2](https://bsd-hardware.info/?probe=461a92a1a2) | Jun 20, 2023 |
| Yanling       | YL-KBRL2 Series Ver:1.02    | Desktop     | [9e8d6110f4](https://bsd-hardware.info/?probe=9e8d6110f4) | Jun 19, 2023 |
| LANCOM Sys... | UF-60                       | Desktop     | [96904b8bdd](https://bsd-hardware.info/?probe=96904b8bdd) | Jun 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [5fc629699d](https://bsd-hardware.info/?probe=5fc629699d) | Jun 18, 2023 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [9f41fa4740](https://bsd-hardware.info/?probe=9f41fa4740) | Jun 18, 2023 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [8eb0be633d](https://bsd-hardware.info/?probe=8eb0be633d) | Jun 18, 2023 |
| Dell          | Latitude E6520              | Notebook    | [98868960d5](https://bsd-hardware.info/?probe=98868960d5) | Jun 18, 2023 |
| ASRock        | Z97 Professional            | Desktop     | [c978ddda86](https://bsd-hardware.info/?probe=c978ddda86) | Jun 18, 2023 |
| Sophos        | SG                          | Firewall    | [94a6b615cb](https://bsd-hardware.info/?probe=94a6b615cb) | Jun 17, 2023 |
| Samsung       | NC210/NC110                 | Notebook    | [06f5a9210b](https://bsd-hardware.info/?probe=06f5a9210b) | Jun 17, 2023 |
| Apple         | MacBook7,1                  | Notebook    | [6412e6fb23](https://bsd-hardware.info/?probe=6412e6fb23) | Jun 16, 2023 |
| AMD           | Kabini CRB                  | Desktop     | [b774a8b586](https://bsd-hardware.info/?probe=b774a8b586) | Jun 16, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [b9c5b6ec05](https://bsd-hardware.info/?probe=b9c5b6ec05) | Jun 15, 2023 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | Desktop     | [70b0e8172d](https://bsd-hardware.info/?probe=70b0e8172d) | Jun 14, 2023 |
| PC Engines    | apu4                        | Desktop     | [ea036662ca](https://bsd-hardware.info/?probe=ea036662ca) | Jun 14, 2023 |
| Unknown       | J3160-4L                    | Desktop     | [4a6667249e](https://bsd-hardware.info/?probe=4a6667249e) | Jun 13, 2023 |
| Lenovo        | ThinkPad T530 2429AP0       | Notebook    | [ddf37e7b17](https://bsd-hardware.info/?probe=ddf37e7b17) | Jun 13, 2023 |
| Samsung       | NC210/NC110                 | Notebook    | [dad27d6099](https://bsd-hardware.info/?probe=dad27d6099) | Jun 13, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [015a5d839a](https://bsd-hardware.info/?probe=015a5d839a) | Jun 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [27617e1ca6](https://bsd-hardware.info/?probe=27617e1ca6) | Jun 13, 2023 |
| HP            | 3397                        | Desktop     | [a918ce0c4b](https://bsd-hardware.info/?probe=a918ce0c4b) | Jun 12, 2023 |
| CWWK          | MINIPC-G12                  | Desktop     | [04ae7435e5](https://bsd-hardware.info/?probe=04ae7435e5) | Jun 12, 2023 |
| MSI           | A320M GRENADE               | Desktop     | [6e0b1f598f](https://bsd-hardware.info/?probe=6e0b1f598f) | Jun 12, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [02509df772](https://bsd-hardware.info/?probe=02509df772) | Jun 12, 2023 |
| Sophos        | UTM                         | Firewall    | [d4856d7798](https://bsd-hardware.info/?probe=d4856d7798) | Jun 11, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS       | Desktop     | [2d2052de27](https://bsd-hardware.info/?probe=2d2052de27) | Jun 11, 2023 |
| HP            | 15                          | Notebook    | [4664b4c93f](https://bsd-hardware.info/?probe=4664b4c93f) | Jun 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [8988baa83b](https://bsd-hardware.info/?probe=8988baa83b) | Jun 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [40bb474319](https://bsd-hardware.info/?probe=40bb474319) | Jun 10, 2023 |
| ASRock        | B85M-HDS                    | Desktop     | [09a4700a14](https://bsd-hardware.info/?probe=09a4700a14) | Jun 09, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [d21bdf0cdb](https://bsd-hardware.info/?probe=d21bdf0cdb) | Jun 09, 2023 |
| Wortmann      | terra Nettop 2700           | Desktop     | [e4a90ea530](https://bsd-hardware.info/?probe=e4a90ea530) | Jun 08, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [1ae49c4706](https://bsd-hardware.info/?probe=1ae49c4706) | Jun 08, 2023 |
| Sophos        | SG                          | Firewall    | [6cf087f800](https://bsd-hardware.info/?probe=6cf087f800) | Jun 08, 2023 |
| Intel         | SKYBAY                      | Desktop     | [f1b649ed11](https://bsd-hardware.info/?probe=f1b649ed11) | Jun 08, 2023 |
| Lanner        | FW-7543 B-GA                | Desktop     | [ee85efd1c0](https://bsd-hardware.info/?probe=ee85efd1c0) | Jun 08, 2023 |
| LANCOM Sys... | UF-60                       | Desktop     | [204f10b60f](https://bsd-hardware.info/?probe=204f10b60f) | Jun 07, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [4e57bbcdb5](https://bsd-hardware.info/?probe=4e57bbcdb5) | Jun 06, 2023 |
| Intel         | DENLOW_WS                   | Desktop     | [ce3bef7b5a](https://bsd-hardware.info/?probe=ce3bef7b5a) | Jun 06, 2023 |
| CncTion       | N6000-4L B0                 | Desktop     | [c9ec51aa84](https://bsd-hardware.info/?probe=c9ec51aa84) | Jun 05, 2023 |
| HP            | 3397                        | Desktop     | [6783902b93](https://bsd-hardware.info/?probe=6783902b93) | Jun 05, 2023 |
| Toshiba       | Satellite C70-B             | Notebook    | [cf9ed85e65](https://bsd-hardware.info/?probe=cf9ed85e65) | Jun 05, 2023 |
| Toshiba       | Satellite C70-B             | Notebook    | [fc66ebba25](https://bsd-hardware.info/?probe=fc66ebba25) | Jun 05, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [42e80f8003](https://bsd-hardware.info/?probe=42e80f8003) | Jun 05, 2023 |
| Sophos        | UTM                         | Firewall    | [05ee8903b5](https://bsd-hardware.info/?probe=05ee8903b5) | Jun 04, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [ab3919bc32](https://bsd-hardware.info/?probe=ab3919bc32) | Jun 04, 2023 |
| Dell          | 0PC5F7 A03                  | Desktop     | [23bd5ef252](https://bsd-hardware.info/?probe=23bd5ef252) | Jun 04, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [56a9981ff3](https://bsd-hardware.info/?probe=56a9981ff3) | Jun 03, 2023 |
| PC Engines    | APU2                        | Desktop     | [31c697459b](https://bsd-hardware.info/?probe=31c697459b) | Jun 02, 2023 |
| HP            | ProLiant DL360p Gen8        | Server      | [300b958d60](https://bsd-hardware.info/?probe=300b958d60) | May 30, 2023 |
| HP            | 3397                        | Desktop     | [1f8a9a4f27](https://bsd-hardware.info/?probe=1f8a9a4f27) | May 29, 2023 |
| ASRock        | H410M/ac                    | Desktop     | [d3e3d20cc4](https://bsd-hardware.info/?probe=d3e3d20cc4) | May 29, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [2827d90215](https://bsd-hardware.info/?probe=2827d90215) | May 28, 2023 |
| Tactus        | GeoFlex 110                 | Notebook    | [df93ad7e83](https://bsd-hardware.info/?probe=df93ad7e83) | May 27, 2023 |
| HP            | 3397                        | Desktop     | [036d4e087c](https://bsd-hardware.info/?probe=036d4e087c) | May 27, 2023 |
| HP            | 3397                        | Desktop     | [19abd8768e](https://bsd-hardware.info/?probe=19abd8768e) | May 27, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [81775d5ca1](https://bsd-hardware.info/?probe=81775d5ca1) | May 26, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [aad8268158](https://bsd-hardware.info/?probe=aad8268158) | May 24, 2023 |
| Nitrokey      | NitroWall                   | Desktop     | [1b3b451dee](https://bsd-hardware.info/?probe=1b3b451dee) | May 24, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [fff8a7a86f](https://bsd-hardware.info/?probe=fff8a7a86f) | May 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [4c7e1d476d](https://bsd-hardware.info/?probe=4c7e1d476d) | May 23, 2023 |
| Nitrokey      | NitroWall                   | Desktop     | [ef701f3991](https://bsd-hardware.info/?probe=ef701f3991) | May 23, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [14583f30e3](https://bsd-hardware.info/?probe=14583f30e3) | May 22, 2023 |
| Unknown       | QD-WHLU01                   | Desktop     | [700bcad7cc](https://bsd-hardware.info/?probe=700bcad7cc) | May 22, 2023 |
| HP            | 158B                        | Desktop     | [1ef3762103](https://bsd-hardware.info/?probe=1ef3762103) | May 20, 2023 |
| HP            | 158B                        | Desktop     | [a9c63041a6](https://bsd-hardware.info/?probe=a9c63041a6) | May 20, 2023 |
| ZOTAC         | Unknown                     | Desktop     | [8156e3fede](https://bsd-hardware.info/?probe=8156e3fede) | May 19, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS       | Desktop     | [612e3a21d4](https://bsd-hardware.info/?probe=612e3a21d4) | May 19, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [8f3c5de741](https://bsd-hardware.info/?probe=8f3c5de741) | May 19, 2023 |
| VIA Techno... | VT82C597                    | Desktop     | [d73db58e48](https://bsd-hardware.info/?probe=d73db58e48) | May 19, 2023 |
| Sophos        | SG                          | Firewall    | [a27da0f165](https://bsd-hardware.info/?probe=a27da0f165) | May 19, 2023 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [9350bb37db](https://bsd-hardware.info/?probe=9350bb37db) | May 18, 2023 |
| Medion        | MS-7633                     | Desktop     | [c01f7b9894](https://bsd-hardware.info/?probe=c01f7b9894) | May 18, 2023 |
| Lenovo        | ThinkPad T560 20FJS03Q00    | Notebook    | [a2110471aa](https://bsd-hardware.info/?probe=a2110471aa) | May 18, 2023 |
| Supermicro    | H8DM8-2                     | Desktop     | [68c51b6006](https://bsd-hardware.info/?probe=68c51b6006) | May 18, 2023 |
| CncTion       | N5105-4L-I226 B0            | Desktop     | [75f5674d44](https://bsd-hardware.info/?probe=75f5674d44) | May 18, 2023 |
| HP            | 3397                        | Desktop     | [d405f14bb9](https://bsd-hardware.info/?probe=d405f14bb9) | May 18, 2023 |
| Unknown       | Unknown                     | Desktop     | [fff8127c3f](https://bsd-hardware.info/?probe=fff8127c3f) | May 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [cc27c738be](https://bsd-hardware.info/?probe=cc27c738be) | May 17, 2023 |
| PC Engines    | apu4                        | Desktop     | [7fe2bf9ad6](https://bsd-hardware.info/?probe=7fe2bf9ad6) | May 16, 2023 |
| PC Engines    | apu4                        | Desktop     | [7723fe0a0a](https://bsd-hardware.info/?probe=7723fe0a0a) | May 16, 2023 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [37922a69a6](https://bsd-hardware.info/?probe=37922a69a6) | May 15, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [2b4ece70c9](https://bsd-hardware.info/?probe=2b4ece70c9) | May 15, 2023 |
| ASRock        | AM1B-ITX                    | Desktop     | [8ad16a1805](https://bsd-hardware.info/?probe=8ad16a1805) | May 15, 2023 |
| Supermicro    | X10SDV-6C-TLN4F             | Server      | [acf561c8dd](https://bsd-hardware.info/?probe=acf561c8dd) | May 15, 2023 |
| PC Engines    | APU2                        | Desktop     | [62fef2616b](https://bsd-hardware.info/?probe=62fef2616b) | May 15, 2023 |
| MSI           | B85M-G43                    | Desktop     | [6d2160dcee](https://bsd-hardware.info/?probe=6d2160dcee) | May 14, 2023 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [31beba4f9c](https://bsd-hardware.info/?probe=31beba4f9c) | May 14, 2023 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [41cf5e3d74](https://bsd-hardware.info/?probe=41cf5e3d74) | May 14, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [7332aba586](https://bsd-hardware.info/?probe=7332aba586) | May 14, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [2eb7679f0a](https://bsd-hardware.info/?probe=2eb7679f0a) | May 13, 2023 |
| Supermicro    | X10SDV-6C-TLN4F             | Server      | [bced2662cd](https://bsd-hardware.info/?probe=bced2662cd) | May 13, 2023 |
| Supermicro    | X10SDV-6C-TLN4F             | Server      | [819210fd5f](https://bsd-hardware.info/?probe=819210fd5f) | May 12, 2023 |
| Supermicro    | X11SBA-LN4FA                | Server      | [66569d2c7d](https://bsd-hardware.info/?probe=66569d2c7d) | May 12, 2023 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [4eea72e4a6](https://bsd-hardware.info/?probe=4eea72e4a6) | May 11, 2023 |
| Fujitsu       | D3823-A2 S26361-D3823-Ax... | Desktop     | [2528087de1](https://bsd-hardware.info/?probe=2528087de1) | May 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [eee23dec87](https://bsd-hardware.info/?probe=eee23dec87) | May 11, 2023 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [2543ed83b9](https://bsd-hardware.info/?probe=2543ed83b9) | May 10, 2023 |
| Sophos        | SG                          | Firewall    | [420ac95a25](https://bsd-hardware.info/?probe=420ac95a25) | May 10, 2023 |
| Fujitsu       | D3644-B1 S26361-D3644-B1    | Desktop     | [b2e52b5677](https://bsd-hardware.info/?probe=b2e52b5677) | May 10, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [fbf3fde510](https://bsd-hardware.info/?probe=fbf3fde510) | May 09, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [96abd89bab](https://bsd-hardware.info/?probe=96abd89bab) | May 09, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [37ee98e0b6](https://bsd-hardware.info/?probe=37ee98e0b6) | May 09, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [38243e0313](https://bsd-hardware.info/?probe=38243e0313) | May 09, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [da07885adb](https://bsd-hardware.info/?probe=da07885adb) | May 09, 2023 |
| PC Engines    | APU2                        | Desktop     | [6aff35010a](https://bsd-hardware.info/?probe=6aff35010a) | May 08, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [5b669f261f](https://bsd-hardware.info/?probe=5b669f261f) | May 08, 2023 |
| Unknown       | T100                        | Desktop     | [fb9c6bff7b](https://bsd-hardware.info/?probe=fb9c6bff7b) | May 07, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [45a1c497b6](https://bsd-hardware.info/?probe=45a1c497b6) | May 07, 2023 |
| Supermicro    | X12STN-C-WOHS               | Desktop     | [d8cf344aee](https://bsd-hardware.info/?probe=d8cf344aee) | May 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [349e1709cd](https://bsd-hardware.info/?probe=349e1709cd) | May 06, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [c29d140ee6](https://bsd-hardware.info/?probe=c29d140ee6) | May 06, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [deeed22abd](https://bsd-hardware.info/?probe=deeed22abd) | May 04, 2023 |
| Lanner        | FW-7543 B-GA                | Desktop     | [8346fdf608](https://bsd-hardware.info/?probe=8346fdf608) | May 03, 2023 |
| HP            | 1589                        | Desktop     | [4aee1909c8](https://bsd-hardware.info/?probe=4aee1909c8) | May 03, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [a5a1ca2ee6](https://bsd-hardware.info/?probe=a5a1ca2ee6) | May 02, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [70b09db335](https://bsd-hardware.info/?probe=70b09db335) | May 02, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [eb61af55d5](https://bsd-hardware.info/?probe=eb61af55d5) | May 01, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [8227d6d32c](https://bsd-hardware.info/?probe=8227d6d32c) | Apr 30, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [f86a94eb66](https://bsd-hardware.info/?probe=f86a94eb66) | Apr 30, 2023 |
| Protectli     | VP2420                      | Desktop     | [4ea8453453](https://bsd-hardware.info/?probe=4ea8453453) | Apr 30, 2023 |
| Protectli     | VP2420                      | Desktop     | [46a00b21d9](https://bsd-hardware.info/?probe=46a00b21d9) | Apr 30, 2023 |
| Supermicro    | A1SAi 123456789             | Mini pc     | [38dc0b126e](https://bsd-hardware.info/?probe=38dc0b126e) | Apr 29, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [ec520be044](https://bsd-hardware.info/?probe=ec520be044) | Apr 29, 2023 |
| Supermicro    | A2SDi-H-TF                  | Server      | [cae933d56e](https://bsd-hardware.info/?probe=cae933d56e) | Apr 29, 2023 |
| Protectli     | FW4B                        | Desktop     | [048da71e18](https://bsd-hardware.info/?probe=048da71e18) | Apr 29, 2023 |
| Sophos        | SG                          | Firewall    | [b0c4592563](https://bsd-hardware.info/?probe=b0c4592563) | Apr 29, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [79c36f752c](https://bsd-hardware.info/?probe=79c36f752c) | Apr 28, 2023 |
| Supermicro    | A2SDi-4C-HLN4F              | Server      | [9dc9ca0768](https://bsd-hardware.info/?probe=9dc9ca0768) | Apr 28, 2023 |
| PC Engines    | apu1                        | Desktop     | [1a37e9d978](https://bsd-hardware.info/?probe=1a37e9d978) | Apr 27, 2023 |
| Supermicro    | X11SCM-LN8F                 | Server      | [32afb6ef58](https://bsd-hardware.info/?probe=32afb6ef58) | Apr 27, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [52174cc0ba](https://bsd-hardware.info/?probe=52174cc0ba) | Apr 27, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [989f3b44bf](https://bsd-hardware.info/?probe=989f3b44bf) | Apr 26, 2023 |
| Supermicro    | X11SDW-8C-TP13F             | Desktop     | [94316d20c8](https://bsd-hardware.info/?probe=94316d20c8) | Apr 26, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [4c7f33d6a9](https://bsd-hardware.info/?probe=4c7f33d6a9) | Apr 25, 2023 |
| MiTAC         | PH13CMI                     | Desktop     | [5d3e954049](https://bsd-hardware.info/?probe=5d3e954049) | Apr 24, 2023 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [c452485a00](https://bsd-hardware.info/?probe=c452485a00) | Apr 24, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS       | Desktop     | [0c8a0100c5](https://bsd-hardware.info/?probe=0c8a0100c5) | Apr 23, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [ad73cda832](https://bsd-hardware.info/?probe=ad73cda832) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS       | Desktop     | [775424cbff](https://bsd-hardware.info/?probe=775424cbff) | Apr 22, 2023 |
| HP            | 8103 A01                    | Mini pc     | [e9c239c897](https://bsd-hardware.info/?probe=e9c239c897) | Apr 21, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [c26c1111c6](https://bsd-hardware.info/?probe=c26c1111c6) | Apr 21, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [215364d870](https://bsd-hardware.info/?probe=215364d870) | Apr 21, 2023 |
| Dell          | Latitude 7280               | Notebook    | [254acb5df8](https://bsd-hardware.info/?probe=254acb5df8) | Apr 20, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [fdbbde509c](https://bsd-hardware.info/?probe=fdbbde509c) | Apr 20, 2023 |
| Sophos        | SG                          | Firewall    | [c05ad03e84](https://bsd-hardware.info/?probe=c05ad03e84) | Apr 19, 2023 |
| Lenovo        | ThinkPad X201 3626WNP       | Notebook    | [d642970071](https://bsd-hardware.info/?probe=d642970071) | Apr 19, 2023 |
| PC Engines    | APU2                        | Desktop     | [59b3a3eebf](https://bsd-hardware.info/?probe=59b3a3eebf) | Apr 19, 2023 |
| Sophos        | UTM                         | Firewall    | [d45ac19cd1](https://bsd-hardware.info/?probe=d45ac19cd1) | Apr 19, 2023 |
| ASUSTek       | Pro B560M-C                 | Desktop     | [b341a9c9c9](https://bsd-hardware.info/?probe=b341a9c9c9) | Apr 19, 2023 |
| Dell          | 060J9C A00                  | Mini pc     | [1cec8655b7](https://bsd-hardware.info/?probe=1cec8655b7) | Apr 19, 2023 |
| Dell          | 060J9C A00                  | Mini pc     | [92b99c6f08](https://bsd-hardware.info/?probe=92b99c6f08) | Apr 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [311e89be7a](https://bsd-hardware.info/?probe=311e89be7a) | Apr 18, 2023 |
| CncTion       | J4125-4L-I225               | Desktop     | [b4fd4e35b2](https://bsd-hardware.info/?probe=b4fd4e35b2) | Apr 18, 2023 |
| Supermicro    | X11SDW-8C-TP13F             | Desktop     | [20fac0b7a5](https://bsd-hardware.info/?probe=20fac0b7a5) | Apr 18, 2023 |
| Sophos        | SG                          | Firewall    | [fa6f321ece](https://bsd-hardware.info/?probe=fa6f321ece) | Apr 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [f5153e1b18](https://bsd-hardware.info/?probe=f5153e1b18) | Apr 17, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [6de7890035](https://bsd-hardware.info/?probe=6de7890035) | Apr 17, 2023 |
| Sophos        | SG                          | Firewall    | [4280767cdb](https://bsd-hardware.info/?probe=4280767cdb) | Apr 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [56505e8956](https://bsd-hardware.info/?probe=56505e8956) | Apr 16, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [4fbc5291d9](https://bsd-hardware.info/?probe=4fbc5291d9) | Apr 16, 2023 |
| Lenovo        | Larne CRB 31900002 WIN      | All in one  | [1f18ec4466](https://bsd-hardware.info/?probe=1f18ec4466) | Apr 16, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [a29966f9ee](https://bsd-hardware.info/?probe=a29966f9ee) | Apr 16, 2023 |
| Unknown       | Unknown                     | Notebook    | [c221bccd5d](https://bsd-hardware.info/?probe=c221bccd5d) | Apr 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [94151c41f1](https://bsd-hardware.info/?probe=94151c41f1) | Apr 14, 2023 |
| Unknown       | YL-SKUL6-7 Series           | Desktop     | [627e7a86c6](https://bsd-hardware.info/?probe=627e7a86c6) | Apr 13, 2023 |
| CncTion       | N5105-4L-I226 B0            | Desktop     | [0c7855ee11](https://bsd-hardware.info/?probe=0c7855ee11) | Apr 13, 2023 |
| Intel         | S3420GP E51974-403          | Server      | [e65290edd3](https://bsd-hardware.info/?probe=e65290edd3) | Apr 12, 2023 |
| Intel         | S3420GP E51974-403          | Server      | [00c76c0db0](https://bsd-hardware.info/?probe=00c76c0db0) | Apr 12, 2023 |
| Advantech     | UNO-2271G_V2                | Desktop     | [23e4b8d9b1](https://bsd-hardware.info/?probe=23e4b8d9b1) | Apr 12, 2023 |
| ASUSTek       | P10S-M Series               | Desktop     | [0b060edc48](https://bsd-hardware.info/?probe=0b060edc48) | Apr 12, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [9b1dbe0b9a](https://bsd-hardware.info/?probe=9b1dbe0b9a) | Apr 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [cfa755bf6d](https://bsd-hardware.info/?probe=cfa755bf6d) | Apr 11, 2023 |
| Sophos        | SG                          | Firewall    | [3a2796626e](https://bsd-hardware.info/?probe=3a2796626e) | Apr 11, 2023 |
| CncTion       | N5105-4L-I226 B0            | Desktop     | [65d80d8aeb](https://bsd-hardware.info/?probe=65d80d8aeb) | Apr 09, 2023 |
| Gigabyte      | H610I DDR4                  | Desktop     | [59d65282c3](https://bsd-hardware.info/?probe=59d65282c3) | Apr 08, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [7a0ca560df](https://bsd-hardware.info/?probe=7a0ca560df) | Apr 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 34487... | Notebook    | [cec90ddd1b](https://bsd-hardware.info/?probe=cec90ddd1b) | Apr 08, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [f3ac765863](https://bsd-hardware.info/?probe=f3ac765863) | Apr 08, 2023 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [8fb3cbee23](https://bsd-hardware.info/?probe=8fb3cbee23) | Apr 07, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [f1cabdb067](https://bsd-hardware.info/?probe=f1cabdb067) | Apr 06, 2023 |
| Dell          | 04Y8V0 A02                  | Desktop     | [b4dab62ac2](https://bsd-hardware.info/?probe=b4dab62ac2) | Apr 05, 2023 |
| Dell          | 04Y8V0 A02                  | Desktop     | [24d7b97629](https://bsd-hardware.info/?probe=24d7b97629) | Apr 05, 2023 |
| Lanner        | FW-8771 C-GA                | Desktop     | [90d7028263](https://bsd-hardware.info/?probe=90d7028263) | Apr 05, 2023 |
| IGEL Techn... | M340C                       | Notebook    | [6c8b2b7af7](https://bsd-hardware.info/?probe=6c8b2b7af7) | Apr 05, 2023 |
| PC Engines    | apu4                        | Desktop     | [e91a75d782](https://bsd-hardware.info/?probe=e91a75d782) | Apr 05, 2023 |
| Intel         | SKYBAY                      | Desktop     | [81655c4fd5](https://bsd-hardware.info/?probe=81655c4fd5) | Apr 05, 2023 |
| Sophos        | SG                          | Firewall    | [c2a2d9d6c9](https://bsd-hardware.info/?probe=c2a2d9d6c9) | Apr 04, 2023 |
| maiyunda      | www.maiyunda.com            | Desktop     | [7cf52a3977](https://bsd-hardware.info/?probe=7cf52a3977) | Apr 03, 2023 |
| Supermicro    | X10SDV-TP8F                 | Server      | [70a4d74b1a](https://bsd-hardware.info/?probe=70a4d74b1a) | Apr 03, 2023 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [828e914b59](https://bsd-hardware.info/?probe=828e914b59) | Apr 03, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [ca1360b939](https://bsd-hardware.info/?probe=ca1360b939) | Apr 03, 2023 |
| Lenovo        | 30BE SDK0J40697 WIN 3305... | Desktop     | [bea5641594](https://bsd-hardware.info/?probe=bea5641594) | Apr 02, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [01bf5e8678](https://bsd-hardware.info/?probe=01bf5e8678) | Apr 02, 2023 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [6ef5047d5a](https://bsd-hardware.info/?probe=6ef5047d5a) | Apr 01, 2023 |
| Sophos        | SG                          | Firewall    | [de22e4dd72](https://bsd-hardware.info/?probe=de22e4dd72) | Apr 01, 2023 |
| ZOTAC         | ZBOX-ID91                   | Mini pc     | [d7bb801369](https://bsd-hardware.info/?probe=d7bb801369) | Mar 31, 2023 |
| Gigabyte      | H55M-S2H                    | Desktop     | [60c66c5066](https://bsd-hardware.info/?probe=60c66c5066) | Mar 30, 2023 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | Desktop     | [bde9fd671b](https://bsd-hardware.info/?probe=bde9fd671b) | Mar 30, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [a160027cc2](https://bsd-hardware.info/?probe=a160027cc2) | Mar 30, 2023 |
| Dell          | 0VG93V A00                  | Desktop     | [1f3e086401](https://bsd-hardware.info/?probe=1f3e086401) | Mar 30, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [3a5111c467](https://bsd-hardware.info/?probe=3a5111c467) | Mar 29, 2023 |
| Intel         | S2600GZ G29051-355          | Server      | [6bc00cde60](https://bsd-hardware.info/?probe=6bc00cde60) | Mar 28, 2023 |
| Intel         | JSL MRD                     | Desktop     | [07adf23a3d](https://bsd-hardware.info/?probe=07adf23a3d) | Mar 28, 2023 |
| Sophos        | SG                          | Firewall    | [b3346fe828](https://bsd-hardware.info/?probe=b3346fe828) | Mar 27, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [b6fd7cd6ae](https://bsd-hardware.info/?probe=b6fd7cd6ae) | Mar 27, 2023 |
| Shuttle       | FS81                        | Desktop     | [b80626e045](https://bsd-hardware.info/?probe=b80626e045) | Mar 26, 2023 |
| Lanner        | FW-7543 B-GA                | Desktop     | [3ed4cfc9c8](https://bsd-hardware.info/?probe=3ed4cfc9c8) | Mar 26, 2023 |
| Sophos        | UTM                         | Firewall    | [99af1f0a15](https://bsd-hardware.info/?probe=99af1f0a15) | Mar 26, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS       | Desktop     | [15e452d25d](https://bsd-hardware.info/?probe=15e452d25d) | Mar 26, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [2f16e29f78](https://bsd-hardware.info/?probe=2f16e29f78) | Mar 26, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [fc5ab682fc](https://bsd-hardware.info/?probe=fc5ab682fc) | Mar 26, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [5082d62025](https://bsd-hardware.info/?probe=5082d62025) | Mar 25, 2023 |
| Lenovo        | ThinkPad X220 4291AN9       | Notebook    | [1646bb53ab](https://bsd-hardware.info/?probe=1646bb53ab) | Mar 25, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [41fa3f51d3](https://bsd-hardware.info/?probe=41fa3f51d3) | Mar 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [387c27f1d7](https://bsd-hardware.info/?probe=387c27f1d7) | Mar 25, 2023 |
| PC Engines    | APU2                        | Desktop     | [4e4a81e456](https://bsd-hardware.info/?probe=4e4a81e456) | Mar 24, 2023 |
| Lex           | Pineview-D                  | Desktop     | [ca2fbb614d](https://bsd-hardware.info/?probe=ca2fbb614d) | Mar 24, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [9561c72b9c](https://bsd-hardware.info/?probe=9561c72b9c) | Mar 24, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [083d2e65da](https://bsd-hardware.info/?probe=083d2e65da) | Mar 24, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [18877701a6](https://bsd-hardware.info/?probe=18877701a6) | Mar 24, 2023 |
| HP            | 8103 A01                    | Mini pc     | [23f893285e](https://bsd-hardware.info/?probe=23f893285e) | Mar 24, 2023 |
| Protectli     | VP2420                      | Desktop     | [f07553b02c](https://bsd-hardware.info/?probe=f07553b02c) | Mar 23, 2023 |
| Protectli     | VP2420                      | Desktop     | [dfad78899e](https://bsd-hardware.info/?probe=dfad78899e) | Mar 23, 2023 |
| ShenZhen M... | MW-GMLK-2.5G6L              | Desktop     | [720f15a1ce](https://bsd-hardware.info/?probe=720f15a1ce) | Mar 23, 2023 |
| Sony          | VAIO                        | All in one  | [ef7c622d8d](https://bsd-hardware.info/?probe=ef7c622d8d) | Mar 23, 2023 |
| Sony          | VAIO                        | All in one  | [ededfcfd39](https://bsd-hardware.info/?probe=ededfcfd39) | Mar 23, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [491c0ca78a](https://bsd-hardware.info/?probe=491c0ca78a) | Mar 22, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [680002292e](https://bsd-hardware.info/?probe=680002292e) | Mar 22, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [b3f0879ebf](https://bsd-hardware.info/?probe=b3f0879ebf) | Mar 22, 2023 |
| Intel         | SKYBAY                      | Desktop     | [83ea0b27b1](https://bsd-hardware.info/?probe=83ea0b27b1) | Mar 21, 2023 |
| Sophos        | SG                          | Firewall    | [4f818307ff](https://bsd-hardware.info/?probe=4f818307ff) | Mar 21, 2023 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | Desktop     | [bcada44b09](https://bsd-hardware.info/?probe=bcada44b09) | Mar 21, 2023 |
| Lenovo        | ThinkPad X230 232578G       | Notebook    | [edf47cb2d4](https://bsd-hardware.info/?probe=edf47cb2d4) | Mar 21, 2023 |
| Supermicro    | X11SDV-8C-TP8F              | Desktop     | [7ae004c035](https://bsd-hardware.info/?probe=7ae004c035) | Mar 21, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [5193764df7](https://bsd-hardware.info/?probe=5193764df7) | Mar 20, 2023 |
| Lenovo        | ThinkPad T61 7659CA1        | Notebook    | [bba228ddc9](https://bsd-hardware.info/?probe=bba228ddc9) | Mar 20, 2023 |
| Sophos        | SG                          | Firewall    | [e0ac090471](https://bsd-hardware.info/?probe=e0ac090471) | Mar 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [e4365dfa60](https://bsd-hardware.info/?probe=e4365dfa60) | Mar 20, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [4dc54510d2](https://bsd-hardware.info/?probe=4dc54510d2) | Mar 19, 2023 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [cab50cddd5](https://bsd-hardware.info/?probe=cab50cddd5) | Mar 19, 2023 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [ff4dda40eb](https://bsd-hardware.info/?probe=ff4dda40eb) | Mar 19, 2023 |
| ASUSTek       | G750JS                      | Notebook    | [bb6117addd](https://bsd-hardware.info/?probe=bb6117addd) | Mar 19, 2023 |
| Intel         | SKYBAY                      | Desktop     | [7bd7f393b1](https://bsd-hardware.info/?probe=7bd7f393b1) | Mar 18, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [e726d886c8](https://bsd-hardware.info/?probe=e726d886c8) | Mar 18, 2023 |
| Intel         | SKYBAY                      | Desktop     | [a8f1d29e24](https://bsd-hardware.info/?probe=a8f1d29e24) | Mar 18, 2023 |
| MSI           | X299 PRO                    | Desktop     | [a26d096ecb](https://bsd-hardware.info/?probe=a26d096ecb) | Mar 18, 2023 |
| ZOTAC         | ZBOX-ID91                   | Mini pc     | [4bbec4b82a](https://bsd-hardware.info/?probe=4bbec4b82a) | Mar 18, 2023 |
| Fujitsu       | D3313-S3 S26361-D3313-S3    | Desktop     | [1bf34a929a](https://bsd-hardware.info/?probe=1bf34a929a) | Mar 18, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [2ceda5b586](https://bsd-hardware.info/?probe=2ceda5b586) | Mar 17, 2023 |
| Supermicro    | X10SLH-F/X10SLM+-F          | Server      | [17516fffcf](https://bsd-hardware.info/?probe=17516fffcf) | Mar 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [6d9c564a33](https://bsd-hardware.info/?probe=6d9c564a33) | Mar 17, 2023 |
| Lenovo        | ThinkPad X61s 7667WQS       | Notebook    | [f1351003d1](https://bsd-hardware.info/?probe=f1351003d1) | Mar 17, 2023 |
| ASRock        | J5040-ITX                   | Desktop     | [435dc7ee7b](https://bsd-hardware.info/?probe=435dc7ee7b) | Mar 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [68b45d5083](https://bsd-hardware.info/?probe=68b45d5083) | Mar 15, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [1ccc8081fd](https://bsd-hardware.info/?probe=1ccc8081fd) | Mar 15, 2023 |
| Acer          | Aspire V3-112P              | Notebook    | [104c10f9b0](https://bsd-hardware.info/?probe=104c10f9b0) | Mar 14, 2023 |
| Foxconn       | H61M/H61M-S                 | Desktop     | [865fbff42a](https://bsd-hardware.info/?probe=865fbff42a) | Mar 14, 2023 |
| ASRock        | Q1900M                      | Desktop     | [9570525d52](https://bsd-hardware.info/?probe=9570525d52) | Mar 14, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [5211185a2a](https://bsd-hardware.info/?probe=5211185a2a) | Mar 14, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | Notebook    | [d9d7368322](https://bsd-hardware.info/?probe=d9d7368322) | Mar 13, 2023 |
| Sophos        | SG                          | Firewall    | [77db75effb](https://bsd-hardware.info/?probe=77db75effb) | Mar 13, 2023 |
| HP            | 8056                        | Desktop     | [e1d2423153](https://bsd-hardware.info/?probe=e1d2423153) | Mar 13, 2023 |
| HP            | 8056                        | Desktop     | [d89b45ea6d](https://bsd-hardware.info/?probe=d89b45ea6d) | Mar 13, 2023 |
| Dell          | 0W0CHX A00                  | Desktop     | [85a9fddd44](https://bsd-hardware.info/?probe=85a9fddd44) | Mar 12, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [fee0ff7804](https://bsd-hardware.info/?probe=fee0ff7804) | Mar 12, 2023 |
| Lenovo        | ZIUS6                       | Notebook    | [d387825f01](https://bsd-hardware.info/?probe=d387825f01) | Mar 12, 2023 |
| Dell          | Latitude E6330              | Notebook    | [5c60cd3d04](https://bsd-hardware.info/?probe=5c60cd3d04) | Mar 12, 2023 |
| Acer          | Veriton N2620G              | Desktop     | [fa57448331](https://bsd-hardware.info/?probe=fa57448331) | Mar 12, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2BR0... | Notebook    | [56fa0d4656](https://bsd-hardware.info/?probe=56fa0d4656) | Mar 11, 2023 |
| ASUSTek       | P8Z68-V                     | Desktop     | [3d8ef63e18](https://bsd-hardware.info/?probe=3d8ef63e18) | Mar 11, 2023 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [8736b12c9a](https://bsd-hardware.info/?probe=8736b12c9a) | Mar 11, 2023 |
| MSI           | X299 PRO                    | Desktop     | [0cebc094ca](https://bsd-hardware.info/?probe=0cebc094ca) | Mar 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [2a55137e71](https://bsd-hardware.info/?probe=2a55137e71) | Mar 10, 2023 |
| CheckPoint    | PH-30-00                    | Desktop     | [ec7a5f05fd](https://bsd-hardware.info/?probe=ec7a5f05fd) | Mar 09, 2023 |
| CompuLab      | fitlet2                     | Mini pc     | [2e616f1ad4](https://bsd-hardware.info/?probe=2e616f1ad4) | Mar 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [d7b171d0bb](https://bsd-hardware.info/?probe=d7b171d0bb) | Mar 09, 2023 |
| Protectli     | VP2420                      | Desktop     | [21d2214da6](https://bsd-hardware.info/?probe=21d2214da6) | Mar 08, 2023 |
| Fujitsu       | D3544-Sx S26361-D3544-Sx... | Mini pc     | [3ad95b9444](https://bsd-hardware.info/?probe=3ad95b9444) | Mar 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [86c132c242](https://bsd-hardware.info/?probe=86c132c242) | Mar 07, 2023 |
| Fujitsu       | D3049-A1 S26361-D3049-A1... | Server      | [b077e8e71a](https://bsd-hardware.info/?probe=b077e8e71a) | Mar 06, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [1a2543f92f](https://bsd-hardware.info/?probe=1a2543f92f) | Mar 06, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [b91b7cf52d](https://bsd-hardware.info/?probe=b91b7cf52d) | Mar 06, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [789ae683f7](https://bsd-hardware.info/?probe=789ae683f7) | Mar 05, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [2ba0e18863](https://bsd-hardware.info/?probe=2ba0e18863) | Mar 05, 2023 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [a3f77b82cc](https://bsd-hardware.info/?probe=a3f77b82cc) | Mar 05, 2023 |
| Dell          | VEP-4600-V910 0PDG1JA02     | Desktop     | [5070c11c54](https://bsd-hardware.info/?probe=5070c11c54) | Mar 05, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [3d912f92aa](https://bsd-hardware.info/?probe=3d912f92aa) | Mar 05, 2023 |
| ASRock        | E350M1                      | Desktop     | [461f8cca23](https://bsd-hardware.info/?probe=461f8cca23) | Mar 04, 2023 |
| HP            | 8158 A01                    | Mini pc     | [021f9a6e74](https://bsd-hardware.info/?probe=021f9a6e74) | Mar 04, 2023 |
| Fujitsu       | D3049-A1 S26361-D3049-A1... | Server      | [5416a8e0b5](https://bsd-hardware.info/?probe=5416a8e0b5) | Mar 03, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [6067b3f58d](https://bsd-hardware.info/?probe=6067b3f58d) | Mar 03, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [bbbd05a4c3](https://bsd-hardware.info/?probe=bbbd05a4c3) | Mar 03, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [9ab07ae7f1](https://bsd-hardware.info/?probe=9ab07ae7f1) | Mar 03, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [228816d44e](https://bsd-hardware.info/?probe=228816d44e) | Mar 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [81bf3cf726](https://bsd-hardware.info/?probe=81bf3cf726) | Mar 03, 2023 |
| Intel         | DENLOW_WS                   | Desktop     | [2b70fdb96a](https://bsd-hardware.info/?probe=2b70fdb96a) | Mar 02, 2023 |
| Sophos        | SG                          | Firewall    | [19b95b3238](https://bsd-hardware.info/?probe=19b95b3238) | Mar 01, 2023 |
| Sophos        | SG                          | Firewall    | [26cd20e559](https://bsd-hardware.info/?probe=26cd20e559) | Mar 01, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [29290b1b9c](https://bsd-hardware.info/?probe=29290b1b9c) | Mar 01, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [5eb87a21db](https://bsd-hardware.info/?probe=5eb87a21db) | Mar 01, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [39d5f658ce](https://bsd-hardware.info/?probe=39d5f658ce) | Feb 28, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [ca59a5e6f4](https://bsd-hardware.info/?probe=ca59a5e6f4) | Feb 28, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [dcf3f03ddc](https://bsd-hardware.info/?probe=dcf3f03ddc) | Feb 28, 2023 |
| Intel         | NUC7i3BNB J22859-307        | Mini pc     | [aca9e2885d](https://bsd-hardware.info/?probe=aca9e2885d) | Feb 28, 2023 |
| Supermicro    | PDSBM                       | Desktop     | [1dea83dd64](https://bsd-hardware.info/?probe=1dea83dd64) | Feb 26, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [27e756f63d](https://bsd-hardware.info/?probe=27e756f63d) | Feb 26, 2023 |
| Foxconn       | 2A8Ch                       | Desktop     | [96a8673b26](https://bsd-hardware.info/?probe=96a8673b26) | Feb 26, 2023 |
| Sophos        | SG                          | Firewall    | [6f8d299ffb](https://bsd-hardware.info/?probe=6f8d299ffb) | Feb 26, 2023 |
| NF541         | 1.0                         | Desktop     | [863e6235d4](https://bsd-hardware.info/?probe=863e6235d4) | Feb 26, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | Notebook    | [59e609fbb2](https://bsd-hardware.info/?probe=59e609fbb2) | Feb 26, 2023 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [33330ade31](https://bsd-hardware.info/?probe=33330ade31) | Feb 25, 2023 |
| Unknown       | YL-J3160L4                  | Desktop     | [b774e80761](https://bsd-hardware.info/?probe=b774e80761) | Feb 25, 2023 |
| Sophos        | SG                          | Firewall    | [7e05fcaf2b](https://bsd-hardware.info/?probe=7e05fcaf2b) | Feb 25, 2023 |
| AWOW          | PC BOX                      | Mini pc     | [54d8b7446b](https://bsd-hardware.info/?probe=54d8b7446b) | Feb 25, 2023 |
| ASRock        | X470 Gaming K4              | Desktop     | [fbff29a62a](https://bsd-hardware.info/?probe=fbff29a62a) | Feb 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [87ad08a144](https://bsd-hardware.info/?probe=87ad08a144) | Feb 25, 2023 |
| Lenovo        | ThinkCentre M91p 7033A2G    | Desktop     | [25528a00f3](https://bsd-hardware.info/?probe=25528a00f3) | Feb 24, 2023 |
| MSI           | X299 PRO                    | Desktop     | [3ca12f88d9](https://bsd-hardware.info/?probe=3ca12f88d9) | Feb 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [efab6dedba](https://bsd-hardware.info/?probe=efab6dedba) | Feb 24, 2023 |
| Protectli     | VP2420                      | Desktop     | [ac2228fa2b](https://bsd-hardware.info/?probe=ac2228fa2b) | Feb 24, 2023 |
| Supermicro    | X10SBAA                     | Server      | [d22806833a](https://bsd-hardware.info/?probe=d22806833a) | Feb 23, 2023 |
| Dell          | 0C27VV A02                  | Desktop     | [5899533edd](https://bsd-hardware.info/?probe=5899533edd) | Feb 23, 2023 |
| Fujitsu       | D3543-A2 S26361-D3543-A2... | Desktop     | [68165a639f](https://bsd-hardware.info/?probe=68165a639f) | Feb 22, 2023 |
| PC Engines    | APU2                        | Desktop     | [05966fb4dc](https://bsd-hardware.info/?probe=05966fb4dc) | Feb 22, 2023 |
| Protectli     | VP2420                      | Desktop     | [541c13b778](https://bsd-hardware.info/?probe=541c13b778) | Feb 22, 2023 |
| Dell          | 0C27VV A02                  | Desktop     | [a10df954b7](https://bsd-hardware.info/?probe=a10df954b7) | Feb 22, 2023 |
| Intel         | QHSW02                      | Desktop     | [6bec4024a8](https://bsd-hardware.info/?probe=6bec4024a8) | Feb 22, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | Desktop     | [3f78b1a6c7](https://bsd-hardware.info/?probe=3f78b1a6c7) | Feb 20, 2023 |
| Protectli     | VP2420                      | Desktop     | [5d8285d184](https://bsd-hardware.info/?probe=5d8285d184) | Feb 19, 2023 |
| CncTion       | J4125-4L-I225               | Desktop     | [6d2c693305](https://bsd-hardware.info/?probe=6d2c693305) | Feb 19, 2023 |
| Yanling       | YL-CLU6L-V1                 | Desktop     | [8d1fa6606b](https://bsd-hardware.info/?probe=8d1fa6606b) | Feb 19, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | Notebook    | [d8ba5b3157](https://bsd-hardware.info/?probe=d8ba5b3157) | Feb 19, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | Notebook    | [820596f359](https://bsd-hardware.info/?probe=820596f359) | Feb 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [63b73012e6](https://bsd-hardware.info/?probe=63b73012e6) | Feb 18, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [cffec30b6b](https://bsd-hardware.info/?probe=cffec30b6b) | Feb 18, 2023 |
| Unknown       | Unknown                     | Desktop     | [1478bc453d](https://bsd-hardware.info/?probe=1478bc453d) | Feb 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [ac4b0186ff](https://bsd-hardware.info/?probe=ac4b0186ff) | Feb 17, 2023 |
| ZOTAC         | Unknown                     | Desktop     | [0adf0ca671](https://bsd-hardware.info/?probe=0adf0ca671) | Feb 17, 2023 |
| ASUSTek       | N3050M-E                    | Desktop     | [7d6e696fb4](https://bsd-hardware.info/?probe=7d6e696fb4) | Feb 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [71cc084a9c](https://bsd-hardware.info/?probe=71cc084a9c) | Feb 16, 2023 |
| PC Engines    | APU                         | Desktop     | [1162545537](https://bsd-hardware.info/?probe=1162545537) | Feb 15, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [35aa7d7f04](https://bsd-hardware.info/?probe=35aa7d7f04) | Feb 15, 2023 |
| Intel         | S3420GP E51974-403          | Server      | [c7b82f8e59](https://bsd-hardware.info/?probe=c7b82f8e59) | Feb 14, 2023 |
| Intel         | S3420GP E51974-403          | Server      | [9d0765df2e](https://bsd-hardware.info/?probe=9d0765df2e) | Feb 14, 2023 |
| Supermicro    | X7SPA-HF                    | Desktop     | [6a91635684](https://bsd-hardware.info/?probe=6a91635684) | Feb 14, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [a9d6421d3c](https://bsd-hardware.info/?probe=a9d6421d3c) | Feb 14, 2023 |
| Yanling       | YL-CLU6L-V1                 | Desktop     | [9c12ee263f](https://bsd-hardware.info/?probe=9c12ee263f) | Feb 14, 2023 |
| Fujitsu       | D3413-A1 S26361-D3413-A1    | Desktop     | [d69aba5432](https://bsd-hardware.info/?probe=d69aba5432) | Feb 14, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [c258b4972c](https://bsd-hardware.info/?probe=c258b4972c) | Feb 13, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [d7080f05ef](https://bsd-hardware.info/?probe=d7080f05ef) | Feb 13, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | Notebook    | [9137c7933c](https://bsd-hardware.info/?probe=9137c7933c) | Feb 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [98819b1db5](https://bsd-hardware.info/?probe=98819b1db5) | Feb 13, 2023 |
| ZOTAC         | ZBOX-ID88/ID89/ID90         | Mini pc     | [cb4c316a05](https://bsd-hardware.info/?probe=cb4c316a05) | Feb 13, 2023 |
| Shuttle       | DS437T                      | Notebook    | [9a16ad9fec](https://bsd-hardware.info/?probe=9a16ad9fec) | Feb 12, 2023 |
| Alienware     | m15                         | Notebook    | [3ab3e4b671](https://bsd-hardware.info/?probe=3ab3e4b671) | Feb 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [dbe1c51575](https://bsd-hardware.info/?probe=dbe1c51575) | Feb 12, 2023 |
| IBM           | 00AL980                     | Server      | [80fa278909](https://bsd-hardware.info/?probe=80fa278909) | Feb 11, 2023 |
| ASUSTek       | P8Z68-V                     | Desktop     | [74ebc950e2](https://bsd-hardware.info/?probe=74ebc950e2) | Feb 11, 2023 |
| Yanling       | YL-KBR6L Ver:1.00           | Desktop     | [516c778d65](https://bsd-hardware.info/?probe=516c778d65) | Feb 11, 2023 |
| Foxconn       | 2A8Ch                       | Desktop     | [2874f7a7fa](https://bsd-hardware.info/?probe=2874f7a7fa) | Feb 11, 2023 |
| Sophos        | UTM                         | Firewall    | [806a078730](https://bsd-hardware.info/?probe=806a078730) | Feb 11, 2023 |
| Gigabyte      | Z490 VISION G               | Desktop     | [6f8ad1a8b9](https://bsd-hardware.info/?probe=6f8ad1a8b9) | Feb 11, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [c4c07aec07](https://bsd-hardware.info/?probe=c4c07aec07) | Feb 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [18362d0f11](https://bsd-hardware.info/?probe=18362d0f11) | Feb 10, 2023 |
| Sophos        | SG                          | Firewall    | [643f5cb10f](https://bsd-hardware.info/?probe=643f5cb10f) | Feb 10, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [12e4e26e40](https://bsd-hardware.info/?probe=12e4e26e40) | Feb 10, 2023 |
| Foxconn       | 2A8Ch                       | Desktop     | [84c0208f8d](https://bsd-hardware.info/?probe=84c0208f8d) | Feb 10, 2023 |
| MSI           | GF76 12UE                   | Notebook    | [371f734e07](https://bsd-hardware.info/?probe=371f734e07) | Feb 10, 2023 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [ef0a4a4744](https://bsd-hardware.info/?probe=ef0a4a4744) | Feb 10, 2023 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [c1b4617895](https://bsd-hardware.info/?probe=c1b4617895) | Feb 10, 2023 |
| ASUSTek       | P7P55D DELUXE               | Desktop     | [dd9685a909](https://bsd-hardware.info/?probe=dd9685a909) | Feb 09, 2023 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [4347c8c716](https://bsd-hardware.info/?probe=4347c8c716) | Feb 09, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [e5b2e1bb9d](https://bsd-hardware.info/?probe=e5b2e1bb9d) | Feb 09, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [f66883c5c2](https://bsd-hardware.info/?probe=f66883c5c2) | Feb 09, 2023 |
| ASUSTek       | P10S-M Series               | Desktop     | [78975e45b7](https://bsd-hardware.info/?probe=78975e45b7) | Feb 09, 2023 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [1a23b05eca](https://bsd-hardware.info/?probe=1a23b05eca) | Feb 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [f4978c3575](https://bsd-hardware.info/?probe=f4978c3575) | Feb 07, 2023 |
| ASUSTek       | P10S-M Series               | Desktop     | [24b74b8ce3](https://bsd-hardware.info/?probe=24b74b8ce3) | Feb 07, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [39fa7db109](https://bsd-hardware.info/?probe=39fa7db109) | Feb 07, 2023 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [923b6d85fd](https://bsd-hardware.info/?probe=923b6d85fd) | Feb 06, 2023 |
| PC Engines    | APU2                        | Desktop     | [e4e00e259c](https://bsd-hardware.info/?probe=e4e00e259c) | Feb 06, 2023 |
| ASUSTek       | P8Z77-M                     | Desktop     | [627bdfafb7](https://bsd-hardware.info/?probe=627bdfafb7) | Feb 06, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [ec37957aed](https://bsd-hardware.info/?probe=ec37957aed) | Feb 05, 2023 |
| Sophos        | SG                          | Firewall    | [0b353acc9f](https://bsd-hardware.info/?probe=0b353acc9f) | Feb 05, 2023 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [8a2bba8635](https://bsd-hardware.info/?probe=8a2bba8635) | Feb 05, 2023 |
| Intel         | QHSW02                      | Desktop     | [16722b7429](https://bsd-hardware.info/?probe=16722b7429) | Feb 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [8fdace282e](https://bsd-hardware.info/?probe=8fdace282e) | Feb 04, 2023 |
| Lenovo        | ThinkPad P50 20EN0008GE     | Notebook    | [8cb09e34ec](https://bsd-hardware.info/?probe=8cb09e34ec) | Feb 04, 2023 |
| Lenovo        | G70-70 80HW006AGE           | Notebook    | [a52e13cf4e](https://bsd-hardware.info/?probe=a52e13cf4e) | Feb 04, 2023 |
| Supermicro    | X10SDV-2C-TP4F              | Server      | [e766835ab5](https://bsd-hardware.info/?probe=e766835ab5) | Feb 04, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | Notebook    | [c0a6490fc8](https://bsd-hardware.info/?probe=c0a6490fc8) | Feb 03, 2023 |
| ASUSTek       | P10S-M Series               | Desktop     | [c6fc0a639d](https://bsd-hardware.info/?probe=c6fc0a639d) | Feb 03, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [77c7c36f87](https://bsd-hardware.info/?probe=77c7c36f87) | Feb 03, 2023 |
| Lenovo        | ThinkPad T460 20FMS04200    | Notebook    | [3178015cd3](https://bsd-hardware.info/?probe=3178015cd3) | Feb 02, 2023 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [b2784f4025](https://bsd-hardware.info/?probe=b2784f4025) | Feb 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [433e29e7bd](https://bsd-hardware.info/?probe=433e29e7bd) | Feb 01, 2023 |
| Supermicro    | X7SPA-HF                    | Desktop     | [2d410c6882](https://bsd-hardware.info/?probe=2d410c6882) | Feb 01, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [9fa25e53f1](https://bsd-hardware.info/?probe=9fa25e53f1) | Feb 01, 2023 |
| PC Engines    | apu4                        | Desktop     | [0d1561fea9](https://bsd-hardware.info/?probe=0d1561fea9) | Jan 31, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [418694e14d](https://bsd-hardware.info/?probe=418694e14d) | Jan 31, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [6ed22671aa](https://bsd-hardware.info/?probe=6ed22671aa) | Jan 31, 2023 |
| Lanner        | FW-7543 B-GA                | Desktop     | [149345d14c](https://bsd-hardware.info/?probe=149345d14c) | Jan 30, 2023 |
| HP            | 1825                        | Desktop     | [717279c19f](https://bsd-hardware.info/?probe=717279c19f) | Jan 29, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [eeed92ab62](https://bsd-hardware.info/?probe=eeed92ab62) | Jan 29, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [4c25e80924](https://bsd-hardware.info/?probe=4c25e80924) | Jan 29, 2023 |
| Shenzhen M... | F4BHD                       | Desktop     | [b2540f3beb](https://bsd-hardware.info/?probe=b2540f3beb) | Jan 29, 2023 |
| HP            | 21B4 A01                    | Desktop     | [8df824afd4](https://bsd-hardware.info/?probe=8df824afd4) | Jan 28, 2023 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [8fd7f80256](https://bsd-hardware.info/?probe=8fd7f80256) | Jan 28, 2023 |
| HP            | ProLiant DL160 Gen9         | Server      | [3797cbf278](https://bsd-hardware.info/?probe=3797cbf278) | Jan 28, 2023 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [1603f38c4c](https://bsd-hardware.info/?probe=1603f38c4c) | Jan 28, 2023 |
| ZOTAC         | ZBOX-CI321NANO              | Mini pc     | [47bbed6ae7](https://bsd-hardware.info/?probe=47bbed6ae7) | Jan 28, 2023 |
| ASUSTek       | M4A89TD PRO USB3            | Desktop     | [1328d01296](https://bsd-hardware.info/?probe=1328d01296) | Jan 28, 2023 |
| Dell          | 03X6X0 A07                  | Server      | [e93b47ed87](https://bsd-hardware.info/?probe=e93b47ed87) | Jan 28, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [937a255571](https://bsd-hardware.info/?probe=937a255571) | Jan 28, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [a7fe868f42](https://bsd-hardware.info/?probe=a7fe868f42) | Jan 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [d3750005c2](https://bsd-hardware.info/?probe=d3750005c2) | Jan 27, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [232a81d2ed](https://bsd-hardware.info/?probe=232a81d2ed) | Jan 27, 2023 |
| ASRock        | H570M-ITX/ac                | Desktop     | [4ebeac2699](https://bsd-hardware.info/?probe=4ebeac2699) | Jan 26, 2023 |
| PC Engines    | APU2                        | Desktop     | [436e596f40](https://bsd-hardware.info/?probe=436e596f40) | Jan 26, 2023 |
| Sophos        | SG                          | Firewall    | [f21b92f971](https://bsd-hardware.info/?probe=f21b92f971) | Jan 25, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [8ba06cd5d3](https://bsd-hardware.info/?probe=8ba06cd5d3) | Jan 24, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [3698389ce4](https://bsd-hardware.info/?probe=3698389ce4) | Jan 24, 2023 |
| Fujitsu       | LIFEBOOK S935               | Notebook    | [5c07c1a47e](https://bsd-hardware.info/?probe=5c07c1a47e) | Jan 24, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [7319560506](https://bsd-hardware.info/?probe=7319560506) | Jan 24, 2023 |
| Medion        | S14409                      | Notebook    | [9a44efb64c](https://bsd-hardware.info/?probe=9a44efb64c) | Jan 23, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [cdad2f0001](https://bsd-hardware.info/?probe=cdad2f0001) | Jan 23, 2023 |
| AWOW          | AK50                        | Desktop     | [8c983f91e4](https://bsd-hardware.info/?probe=8c983f91e4) | Jan 22, 2023 |
| Lenovo        | ThinkPad T440p 20AN007FG... | Notebook    | [0883806434](https://bsd-hardware.info/?probe=0883806434) | Jan 22, 2023 |
| PC Engines    | APU2                        | Desktop     | [658569ae16](https://bsd-hardware.info/?probe=658569ae16) | Jan 22, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | Notebook    | [ab38c51298](https://bsd-hardware.info/?probe=ab38c51298) | Jan 22, 2023 |
| HP            | 1825                        | Desktop     | [2705218636](https://bsd-hardware.info/?probe=2705218636) | Jan 21, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [59c83cb9ee](https://bsd-hardware.info/?probe=59c83cb9ee) | Jan 21, 2023 |
| Fujitsu       | D3243-S1 S26361-D3243-S1    | Desktop     | [d69c3cae4c](https://bsd-hardware.info/?probe=d69c3cae4c) | Jan 21, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [e6873fe42f](https://bsd-hardware.info/?probe=e6873fe42f) | Jan 21, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [495563926c](https://bsd-hardware.info/?probe=495563926c) | Jan 21, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [f862df1689](https://bsd-hardware.info/?probe=f862df1689) | Jan 20, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [d4018ae0f3](https://bsd-hardware.info/?probe=d4018ae0f3) | Jan 20, 2023 |
| Fujitsu       | PRIMERGY RX200 S6           | Desktop     | [4bcc8752f4](https://bsd-hardware.info/?probe=4bcc8752f4) | Jan 20, 2023 |
| Sophos        | SG                          | Firewall    | [324882f1d6](https://bsd-hardware.info/?probe=324882f1d6) | Jan 20, 2023 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [48206a7d4a](https://bsd-hardware.info/?probe=48206a7d4a) | Jan 19, 2023 |
| Sophos        | SG                          | Firewall    | [f10f04a5b1](https://bsd-hardware.info/?probe=f10f04a5b1) | Jan 19, 2023 |
| Sophos        | SG                          | Firewall    | [9275bbae4e](https://bsd-hardware.info/?probe=9275bbae4e) | Jan 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [35e269ef1c](https://bsd-hardware.info/?probe=35e269ef1c) | Jan 19, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [b528c0bbe3](https://bsd-hardware.info/?probe=b528c0bbe3) | Jan 18, 2023 |
| BESSTAR Te... | TH50                        | Desktop     | [b9de543167](https://bsd-hardware.info/?probe=b9de543167) | Jan 18, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [11948a0ab1](https://bsd-hardware.info/?probe=11948a0ab1) | Jan 18, 2023 |
| Fujitsu       | D3031 S26361-D3031-A100-... | Server      | [ed566c9a5c](https://bsd-hardware.info/?probe=ed566c9a5c) | Jan 18, 2023 |
| Fujitsu       | PRIMERGY RX200 S6           | Desktop     | [f7de27b0ca](https://bsd-hardware.info/?probe=f7de27b0ca) | Jan 18, 2023 |
| Fujitsu       | D3031 S26361-D3031-A100-... | Server      | [cfb839082b](https://bsd-hardware.info/?probe=cfb839082b) | Jan 18, 2023 |
| Sophos        | UTM                         | Firewall    | [4b0eace553](https://bsd-hardware.info/?probe=4b0eace553) | Jan 18, 2023 |
| Fujitsu       | PRIMERGY RX200 S6           | Desktop     | [9eee9cc526](https://bsd-hardware.info/?probe=9eee9cc526) | Jan 18, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [46178567ff](https://bsd-hardware.info/?probe=46178567ff) | Jan 18, 2023 |
| Wortmann      | terra MiniPC                | Desktop     | [be22193265](https://bsd-hardware.info/?probe=be22193265) | Jan 17, 2023 |
| MSI           | MS-9897                     | Desktop     | [8aa91d17fa](https://bsd-hardware.info/?probe=8aa91d17fa) | Jan 17, 2023 |
| MSI           | MS-9897                     | Desktop     | [0ccc361bd9](https://bsd-hardware.info/?probe=0ccc361bd9) | Jan 17, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [1ef7026e21](https://bsd-hardware.info/?probe=1ef7026e21) | Jan 15, 2023 |
| Supermicro    | X11SCM-LN8F                 | Server      | [9e102da483](https://bsd-hardware.info/?probe=9e102da483) | Jan 15, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [624bfd62b5](https://bsd-hardware.info/?probe=624bfd62b5) | Jan 15, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [8aebf3b22a](https://bsd-hardware.info/?probe=8aebf3b22a) | Jan 15, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | Notebook    | [ced6c29193](https://bsd-hardware.info/?probe=ced6c29193) | Jan 14, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [17d73c4d40](https://bsd-hardware.info/?probe=17d73c4d40) | Jan 14, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [ad7329411a](https://bsd-hardware.info/?probe=ad7329411a) | Jan 14, 2023 |
| HP            | ProLiant DL160 Gen9         | Server      | [f8a84dbf0c](https://bsd-hardware.info/?probe=f8a84dbf0c) | Jan 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [fba3e00878](https://bsd-hardware.info/?probe=fba3e00878) | Jan 13, 2023 |
| HP            | 82A1                        | Desktop     | [567894a0bb](https://bsd-hardware.info/?probe=567894a0bb) | Jan 12, 2023 |
| PC Engines    | APU3                        | Desktop     | [b080710198](https://bsd-hardware.info/?probe=b080710198) | Jan 12, 2023 |
| ASRockRack    | X470D4U2/1N1                | Desktop     | [07f15d0014](https://bsd-hardware.info/?probe=07f15d0014) | Jan 11, 2023 |
| CncTion       | J4125-4L-I225               | Desktop     | [56a5c0de6e](https://bsd-hardware.info/?probe=56a5c0de6e) | Jan 11, 2023 |
| PC Engines    | APU2                        | Desktop     | [1e65573dfa](https://bsd-hardware.info/?probe=1e65573dfa) | Jan 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [e870cfc473](https://bsd-hardware.info/?probe=e870cfc473) | Jan 10, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [55bd6297fa](https://bsd-hardware.info/?probe=55bd6297fa) | Jan 10, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [76ce0f8e69](https://bsd-hardware.info/?probe=76ce0f8e69) | Jan 09, 2023 |
| MSI           | X299 PRO                    | Desktop     | [a1f37f69d9](https://bsd-hardware.info/?probe=a1f37f69d9) | Jan 08, 2023 |
| Dell          | 03X6X0 A07                  | Server      | [dea6b95d26](https://bsd-hardware.info/?probe=dea6b95d26) | Jan 08, 2023 |
| Dell          | 0YNVJG A01                  | Desktop     | [8bb9472e6b](https://bsd-hardware.info/?probe=8bb9472e6b) | Jan 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [7b5333020a](https://bsd-hardware.info/?probe=7b5333020a) | Jan 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [1e3ebde983](https://bsd-hardware.info/?probe=1e3ebde983) | Jan 07, 2023 |
| ASUSTek       | F2A85-M                     | Desktop     | [e25da8b10a](https://bsd-hardware.info/?probe=e25da8b10a) | Jan 06, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [fa12ea67eb](https://bsd-hardware.info/?probe=fa12ea67eb) | Jan 06, 2023 |
| ShenZhen M... | MW-GMLK-2.5G6L              | Desktop     | [92c2e73bd4](https://bsd-hardware.info/?probe=92c2e73bd4) | Jan 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [cc8588d977](https://bsd-hardware.info/?probe=cc8588d977) | Jan 05, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [39149acdbd](https://bsd-hardware.info/?probe=39149acdbd) | Jan 04, 2023 |
| Sophos        | SG                          | Firewall    | [4f105d12b8](https://bsd-hardware.info/?probe=4f105d12b8) | Jan 03, 2023 |
| Unknown       | J3160-4L                    | Desktop     | [849af12174](https://bsd-hardware.info/?probe=849af12174) | Jan 02, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [70b1ca485d](https://bsd-hardware.info/?probe=70b1ca485d) | Jan 02, 2023 |
| ASRock        | E350M1                      | Desktop     | [6a7e5c8d0c](https://bsd-hardware.info/?probe=6a7e5c8d0c) | Jan 01, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [b3ac391a7e](https://bsd-hardware.info/?probe=b3ac391a7e) | Jan 01, 2023 |
| Supermicro    | A1SAi 123456789             | Mini pc     | [d179977442](https://bsd-hardware.info/?probe=d179977442) | Jan 01, 2023 |
| HP            | 1825                        | Desktop     | [f7e94decd0](https://bsd-hardware.info/?probe=f7e94decd0) | Dec 31, 2022 |
| HP            | 1825                        | Desktop     | [afc1259508](https://bsd-hardware.info/?probe=afc1259508) | Dec 31, 2022 |
| Supermicro    | X10SDV-TP8F                 | Server      | [16daca3076](https://bsd-hardware.info/?probe=16daca3076) | Dec 31, 2022 |
| Supermicro    | X10SDV-TP8F                 | Server      | [5967766127](https://bsd-hardware.info/?probe=5967766127) | Dec 30, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [cd3e4f7122](https://bsd-hardware.info/?probe=cd3e4f7122) | Dec 30, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Germany/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart_bsd/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| OPNsense 21.7.7   | 65        | 2.46%   |
| OPNsense 21.1     | 64        | 2.43%   |
| OPNsense 22.7.10  | 59        | 2.24%   |
| OPNsense 21.1.5   | 56        | 2.12%   |
| OPNsense 22.1     | 54        | 2.05%   |
| OPNsense 20.7.8   | 54        | 2.05%   |
| OPNsense 21.7.3   | 52        | 1.97%   |
| OPNsense 21.7.1   | 51        | 1.93%   |
| OPNsense 23.1.11  | 50        | 1.89%   |
| OPNsense 21.1.3   | 45        | 1.71%   |
| OPNsense 21.7.6   | 43        | 1.63%   |
| OPNsense 21.1.2   | 43        | 1.63%   |
| OPNsense 23.1     | 42        | 1.59%   |
| OPNsense 22.7.6   | 42        | 1.59%   |
| OPNsense 22.7.4   | 42        | 1.59%   |
| OPNsense 22.1.8   | 42        | 1.59%   |
| OPNsense 21.1.1   | 42        | 1.59%   |
| OPNsense 23.1.5   | 41        | 1.55%   |
| OPNsense 22.1.6   | 40        | 1.52%   |
| OPNsense 21.1.4   | 39        | 1.48%   |
| OPNsense 22.7.9   | 38        | 1.44%   |
| OPNsense 23.7.9   | 36        | 1.36%   |
| OPNsense 23.1.1   | 35        | 1.33%   |
| OPNsense 23.7.7   | 34        | 1.29%   |
| helloSystem 0.4.0 | 34        | 1.29%   |
| OPNsense 23.7.6   | 33        | 1.25%   |
| OPNsense 23.1.7   | 33        | 1.25%   |
| OPNsense 23.7.1   | 31        | 1.17%   |
| OPNsense 23.1.9   | 31        | 1.17%   |
| OPNsense 23.7.8   | 30        | 1.14%   |
| helloSystem 0.8.1 | 30        | 1.14%   |
| OPNsense 22.1.10  | 29        | 1.1%    |
| OpenBSD 6.8       | 28        | 1.06%   |
| OPNsense 23.7.5   | 27        | 1.02%   |
| OPNsense 23.7.3   | 27        | 1.02%   |
| OPNsense 22.7.7   | 26        | 0.99%   |
| OPNsense 22.7.11  | 26        | 0.99%   |
| OPNsense 22.1.9   | 26        | 0.99%   |
| OPNsense 22.1.1   | 26        | 0.99%   |
| OPNsense 21.7.5   | 26        | 0.99%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 1465      | 72.17%  |
| FreeBSD     | 251       | 12.36%  |
| helloSystem | 146       | 7.19%   |
| OpenBSD     | 71        | 3.5%    |
| GhostBSD    | 42        | 2.07%   |
| NomadBSD    | 28        | 1.38%   |
| NetBSD      | 8         | 0.39%   |
| TrueNAS     | 6         | 0.3%    |
| MyBee       | 3         | 0.15%   |
| pfSense     | 2         | 0.1%    |
| HardenedBSD | 2         | 0.1%    |
| PC-BSD      | 1         | 0.05%   |
| MidnightBSD | 1         | 0.05%   |
| FuryBSD     | 1         | 0.05%   |
| FreeNAS     | 1         | 0.05%   |
| DragonFly   | 1         | 0.05%   |
| ClonOS      | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| amd64   | 1980      | 98.56%  |
| i386    | 12        | 0.6%    |
| arm64   | 9         | 0.45%   |
| arm     | 5         | 0.25%   |
| macppc  | 2         | 0.1%    |
| sparc64 | 1         | 0.05%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 1592      | 78%     |
| helloDesktop  | 162       | 7.94%   |
| MATE          | 57        | 2.79%   |
| KDE5          | 47        | 2.3%    |
| XFCE          | 43        | 2.11%   |
| fvwm          | 38        | 1.86%   |
| GNOME         | 23        | 1.13%   |
| Openbox       | 21        | 1.03%   |
| TWM           | 19        | 0.93%   |
| AwesomeWM     | 11        | 0.54%   |
| i3            | 7         | 0.34%   |
| LXQt          | 3         | 0.15%   |
| Enlightenment | 3         | 0.15%   |
| Cinnamon      | 3         | 0.15%   |
| LXDE          | 2         | 0.1%    |
| ICEWM         | 2         | 0.1%    |
| Fluxbox       | 2         | 0.1%    |
| Picom         | 1         | 0.05%   |
| JWM           | 1         | 0.05%   |
| iwm           | 1         | 0.05%   |
| GNUstep       | 1         | 0.05%   |
| filer         | 1         | 0.05%   |
| Compton       | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 1608      | 79.76%  |
| X11     | 405       | 20.09%  |
| Wayland | 2         | 0.1%    |
| Tty     | 1         | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 1688      | 82.83%  |
| SLiM    | 194       | 9.52%   |
| LightDM | 55        | 2.7%    |
| SDDM    | 52        | 2.55%   |
| XDM     | 25        | 1.23%   |
| GDM     | 19        | 0.93%   |
| Ly      | 5         | 0.25%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 1606      | 78.46%  |
| C                | 145       | 7.08%   |
| en_US            | 141       | 6.89%   |
| de_DE            | 116       | 5.67%   |
| en_GB            | 8         | 0.39%   |
| de               | 8         | 0.39%   |
| fr_FR            | 7         | 0.34%   |
| en               | 4         | 0.2%    |
| de_DE.ISO8859-1  | 3         | 0.15%   |
| ru_RU            | 1         | 0.05%   |
| pl_PL            | 1         | 0.05%   |
| ISO8859-15       | 1         | 0.05%   |
| fr               | 1         | 0.05%   |
| en_IE            | 1         | 0.05%   |
| en_GB.ISO8859-1  | 1         | 0.05%   |
| en_DE            | 1         | 0.05%   |
| en_CA            | 1         | 0.05%   |
| de_DE.ISO8859-15 | 1         | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1757      | 86.81%  |
| BIOS | 267       | 13.19%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ufs     | 1193      | 58%     |
| Zfs     | 741       | 36.02%  |
| Ffs     | 71        | 3.45%   |
| Cd9660  | 51        | 2.48%   |
| Hammer2 | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 1867      | 92.33%  |
| MBR     | 126       | 6.23%   |
| Unknown | 28        | 1.38%   |
| BSD     | 1         | 0.05%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Unknown                    | 235       | 11.7%   |
| Lenovo                     | 151       | 7.52%   |
| PC Engines                 | 133       | 6.62%   |
| Fujitsu                    | 127       | 6.32%   |
| Supermicro                 | 125       | 6.22%   |
| Dell                       | 110       | 5.48%   |
| Hewlett-Packard            | 109       | 5.43%   |
| Sophos                     | 100       | 4.98%   |
| ASUSTek Computer           | 89        | 4.43%   |
| Intel                      | 88        | 4.38%   |
| ASRock                     | 72        | 3.58%   |
| Gigabyte Technology        | 59        | 2.94%   |
| ZOTAC                      | 56        | 2.79%   |
| MSI                        | 46        | 2.29%   |
| AMI                        | 40        | 1.99%   |
| BESSTAR Tech               | 36        | 1.79%   |
| Protectli                  | 33        | 1.64%   |
| Deciso                     | 32        | 1.59%   |
| Apple                      | 29        | 1.44%   |
| Techvision                 | 23        | 1.14%   |
| Shuttle                    | 21        | 1.05%   |
| CncTion                    | 21        | 1.05%   |
| Acer                       | 19        | 0.95%   |
| Hardkernel                 | 14        | 0.7%    |
| MW                         | 13        | 0.65%   |
| AWOW                       | 13        | 0.65%   |
| Thomas-Krenn.AG            | 12        | 0.6%    |
| TUXEDO                     | 10        | 0.5%    |
| Yanling                    | 9         | 0.45%   |
| CheckPoint                 | 9         | 0.45%   |
| ASRockRack                 | 9         | 0.45%   |
| NF541                      | 8         | 0.4%    |
| IceWhale Technology        | 7         | 0.35%   |
| IBM                        | 7         | 0.35%   |
| Biostar                    | 7         | 0.35%   |
| Medion                     | 5         | 0.25%   |
| Lanner                     | 5         | 0.25%   |
| Beckhoff Automation        | 5         | 0.25%   |
| Sony                       | 4         | 0.2%    |
| ShenZhen MinWin Technology | 4         | 0.2%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                             | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Unknown                                          | 240       | 11.95%  |
| PC Engines APU2                                  | 66        | 3.29%   |
| Sophos SG                                        | 60        | 2.99%   |
| Fujitsu FUTRO S920                               | 49        | 2.44%   |
| Supermicro Super Server                          | 43        | 2.14%   |
| PC Engines apu4                                  | 41        | 2.04%   |
| Techvision TVI7309X                              | 23        | 1.14%   |
| Sophos UTM                                       | 22        | 1.1%    |
| AMI Aptio CRB                                    | 21        | 1.05%   |
| Sophos XG                                        | 18        | 0.9%    |
| Intel Q3XXG4-P V1.0                              | 18        | 0.9%    |
| ZOTAC ZBOX-CI329NANO                             | 14        | 0.7%    |
| MW GMLK-2_5G4L                                   | 13        | 0.65%   |
| HARDKERNEL ODROID-H2                             | 13        | 0.65%   |
| Deciso NetBoard-A10                              | 13        | 0.65%   |
| Protectli FW6                                    | 12        | 0.6%    |
| Protectli FW4B                                   | 11        | 0.55%   |
| PC Engines APU3                                  | 11        | 0.55%   |
| CncTion N5105-4L                                 | 11        | 0.55%   |
| ZOTAC ZBOX-CI327NANO-GS-01                       | 10        | 0.5%    |
| Supermicro A1SAi                                 | 10        | 0.5%    |
| PC Engines APU                                   | 10        | 0.5%    |
| BESSTAR Tech GK41                                | 10        | 0.5%    |
| HP ProLiant MicroServer Gen8                     | 9         | 0.45%   |
| Dell PowerEdge R210 II                           | 9         | 0.45%   |
| BESSTAR Tech X35G                                | 9         | 0.45%   |
| Supermicro 1HE Intel Single-CPU RI1102D-F Server | 8         | 0.4%    |
| Fujitsu FUTRO S930                               | 8         | 0.4%    |
| NF541 1.0                                        | 7         | 0.35%   |
| AWOW PC BOX                                      | 7         | 0.35%   |
| AMI SG                                           | 7         | 0.35%   |
| HP t730 Thin Client                              | 6         | 0.3%    |
| HP t620 PLUS Quad Core TC                        | 6         | 0.3%    |
| Deciso Netboard A20                              | 6         | 0.3%    |
| ZOTAC ZBOX-MI640/MI660/MI620NANO                 | 5         | 0.25%   |
| ZOTAC ZBOX-CI323NANO                             | 5         | 0.25%   |
| Thomas-Krenn.AG LES network+                     | 5         | 0.25%   |
| Protectli VP2420                                 | 5         | 0.25%   |
| Intel DENLOW_WS                                  | 5         | 0.25%   |
| IceWhale ZimaBoard 832 ZMB                       | 5         | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Unknown                    | 240       | 11.95%  |
| Lenovo ThinkPad            | 97        | 4.83%   |
| Fujitsu FUTRO              | 73        | 3.63%   |
| PC Engines APU2            | 66        | 3.29%   |
| Sophos SG                  | 60        | 2.99%   |
| Supermicro Super           | 43        | 2.14%   |
| PC Engines apu4            | 41        | 2.04%   |
| Dell OptiPlex              | 35        | 1.74%   |
| HP ProLiant                | 33        | 1.64%   |
| Dell PowerEdge             | 30        | 1.49%   |
| Lenovo ThinkCentre         | 25        | 1.24%   |
| Techvision TVI7309X        | 23        | 1.14%   |
| Sophos UTM                 | 22        | 1.1%    |
| Dell Latitude              | 22        | 1.1%    |
| AMI Aptio                  | 21        | 1.05%   |
| Supermicro 1HE             | 19        | 0.95%   |
| Sophos XG                  | 18        | 0.9%    |
| Intel Q3XXG4-P             | 18        | 0.9%    |
| Fujitsu ESPRIMO            | 16        | 0.8%    |
| ZOTAC ZBOX-CI329NANO       | 14        | 0.7%    |
| MW GMLK-2                  | 13        | 0.65%   |
| HP Compaq                  | 13        | 0.65%   |
| Hardkernel ODROID-H2       | 13        | 0.65%   |
| Deciso NetBoard-A10        | 13        | 0.65%   |
| Deciso Netboard            | 13        | 0.65%   |
| Protectli FW6              | 12        | 0.6%    |
| ASUS TUF                   | 12        | 0.6%    |
| Protectli FW4B             | 11        | 0.55%   |
| PC Engines APU3            | 11        | 0.55%   |
| HP t620                    | 11        | 0.55%   |
| HP ProDesk                 | 11        | 0.55%   |
| Fujitsu PRIMERGY           | 11        | 0.55%   |
| Fujitsu LIFEBOOK           | 11        | 0.55%   |
| CncTion N5105-4L           | 11        | 0.55%   |
| ASUS PRIME                 | 11        | 0.55%   |
| ZOTAC ZBOX-CI327NANO-GS-01 | 10        | 0.5%    |
| Supermicro A1SAi           | 10        | 0.5%    |
| PC Engines APU             | 10        | 0.5%    |
| BESSTAR Tech GK41          | 10        | 0.5%    |
| Thomas-Krenn.AG LES        | 9         | 0.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 237       | 11.8%   |
| 2016    | 213       | 10.6%   |
| 2021    | 205       | 10.2%   |
| 2020    | 201       | 10%     |
| 2019    | 186       | 9.26%   |
| 2022    | 163       | 8.11%   |
| 2014    | 161       | 8.01%   |
| 2017    | 118       | 5.87%   |
| 2013    | 99        | 4.93%   |
| 2011    | 82        | 4.08%   |
| 2012    | 78        | 3.88%   |
| 2015    | 72        | 3.58%   |
| 2023    | 48        | 2.39%   |
| 2010    | 48        | 2.39%   |
| 2009    | 35        | 1.74%   |
| 2008    | 23        | 1.14%   |
| Unknown | 20        | 1%      |
| 2007    | 11        | 0.55%   |
| 2006    | 5         | 0.25%   |
| 2003    | 2         | 0.1%    |
| 2005    | 1         | 0.05%   |
| 2002    | 1         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 1224      | 60.93%  |
| Notebook       | 311       | 15.48%  |
| Mini pc        | 183       | 9.11%   |
| Server         | 160       | 7.96%   |
| Firewall       | 105       | 5.23%   |
| All in one     | 12        | 0.6%    |
| Convertible    | 8         | 0.4%    |
| System on chip | 6         | 0.3%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1858      | 92.48%  |
| Yes  | 151       | 7.52%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 759       | 37.06%  |
| 4.01-8.0        | 470       | 22.95%  |
| 16.01-24.0      | 442       | 21.58%  |
| 32.01-64.0      | 173       | 8.45%   |
| 2.01-3.0        | 83        | 4.05%   |
| 64.01-256.0     | 66        | 3.22%   |
| 3.01-4.0        | 15        | 0.73%   |
| 24.01-32.0      | 12        | 0.59%   |
| 0.51-1.0        | 9         | 0.44%   |
| 1.01-2.0        | 8         | 0.39%   |
| 0.01-0.5        | 7         | 0.34%   |
| More than 256.0 | 3         | 0.15%   |
| 0               | 1         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 1118      | 53.88%  |
| 0.51-1.0    | 639       | 30.8%   |
| 1.01-2.0    | 184       | 8.87%   |
| 2.01-3.0    | 49        | 2.36%   |
| 4.01-8.0    | 24        | 1.16%   |
| 3.01-4.0    | 19        | 0.92%   |
| 0           | 12        | 0.58%   |
| Unknown     | 10        | 0.48%   |
| 8.01-16.0   | 8         | 0.39%   |
| 16.01-24.0  | 6         | 0.29%   |
| 24.01-32.0  | 3         | 0.14%   |
| 64.01-256.0 | 2         | 0.1%    |
| 32.01-64.0  | 1         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1531      | 74.21%  |
| 2      | 232       | 11.25%  |
| 0      | 170       | 8.24%   |
| 3      | 57        | 2.76%   |
| 4      | 35        | 1.7%    |
| 5      | 13        | 0.63%   |
| 6      | 9         | 0.44%   |
| 8      | 6         | 0.29%   |
| 7      | 5         | 0.24%   |
| 9      | 2         | 0.1%    |
| 14     | 1         | 0.05%   |
| 11     | 1         | 0.05%   |
| 10     | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1731      | 85.65%  |
| Yes       | 290       | 14.35%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1958      | 97.46%  |
| No        | 51        | 2.54%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1395      | 68.82%  |
| Yes       | 632       | 31.18%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1613      | 79.77%  |
| Yes       | 409       | 20.23%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Germany | 2009      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Berlin            | 176       | 7.81%   |
| Munich            | 79        | 3.5%    |
| Hamburg           | 77        | 3.42%   |
| Frankfurt am Main | 56        | 2.48%   |
| Cologne           | 51        | 2.26%   |
| Stuttgart         | 37        | 1.64%   |
| Ludwigsburg       | 26        | 1.15%   |
| Karlsruhe         | 26        | 1.15%   |
| Hanover           | 23        | 1.02%   |
| Nuremberg         | 22        | 0.98%   |
| Leipzig           | 19        | 0.84%   |
| Bonn              | 19        | 0.84%   |
| Dresden           | 18        | 0.8%    |
| Dortmund          | 16        | 0.71%   |
| Bochum            | 16        | 0.71%   |
| Wuppertal         | 15        | 0.67%   |
| Wiesbaden         | 13        | 0.58%   |
| Mannheim          | 13        | 0.58%   |
| Falkenstein       | 13        | 0.58%   |
| Bielefeld         | 13        | 0.58%   |
| Essen             | 12        | 0.53%   |
| Düsseldorf       | 12        | 0.53%   |
| Darmstadt         | 12        | 0.53%   |
| Mainz             | 10        | 0.44%   |
| Magdeburg         | 10        | 0.44%   |
| Heidelberg        | 10        | 0.44%   |
| Chemnitz          | 10        | 0.44%   |
| Bremen            | 10        | 0.44%   |
| Reutlingen        | 9         | 0.4%    |
| Münster          | 9         | 0.4%    |
| Kassel            | 9         | 0.4%    |
| Halle             | 9         | 0.4%    |
| Erlangen          | 9         | 0.4%    |
| Braunschweig      | 9         | 0.4%    |
| Augsburg          | 9         | 0.4%    |
| Aachen            | 9         | 0.4%    |
| Ulm               | 8         | 0.35%   |
| Tamm              | 8         | 0.35%   |
| Potsdam           | 8         | 0.35%   |
| Paderborn         | 8         | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 382       | 591    | 17.47%  |
| Transcend           | 202       | 275    | 9.24%   |
| WDC                 | 172       | 288    | 7.86%   |
| Kingston            | 153       | 247    | 7%      |
| Intel               | 123       | 204    | 5.62%   |
| SanDisk             | 122       | 167    | 5.58%   |
| Crucial             | 118       | 178    | 5.4%    |
| Seagate             | 109       | 182    | 4.98%   |
| Toshiba             | 70        | 128    | 3.2%    |
| China               | 60        | 72     | 2.74%   |
| Intenso             | 48        | 71     | 2.19%   |
| Phison              | 42        | 61     | 1.92%   |
| A-DATA Technology   | 41        | 50     | 1.87%   |
| Hitachi             | 40        | 72     | 1.83%   |
| Hoodisk             | 35        | 60     | 1.6%    |
| HGST                | 35        | 68     | 1.6%    |
| Micron Technology   | 33        | 50     | 1.51%   |
| Innodisk            | 26        | 30     | 1.19%   |
| FORESEE             | 25        | 34     | 1.14%   |
| NVMe                | 24        | 42     | 1.1%    |
| ATP                 | 21        | 24     | 0.96%   |
| Hewlett-Packard     | 17        | 23     | 0.78%   |
| SK hynix            | 15        | 16     | 0.69%   |
| OCZ                 | 15        | 24     | 0.69%   |
| SPCC                | 14        | 20     | 0.64%   |
| Protectli           | 12        | 15     | 0.55%   |
| Corsair             | 12        | 18     | 0.55%   |
| Apple               | 12        | 12     | 0.55%   |
| Apacer              | 12        | 20     | 0.55%   |
| Patriot             | 11        | 14     | 0.5%    |
| KIOXIA              | 10        | 11     | 0.46%   |
| Dogfish             | 8         | 10     | 0.37%   |
| Verbatim            | 7         | 13     | 0.32%   |
| TCSUNBOW            | 7         | 8      | 0.32%   |
| LITEON              | 7         | 8      | 0.32%   |
| PNY                 | 6         | 7      | 0.27%   |
| LITEONIT            | 6         | 8      | 0.27%   |
| Gigabyte Technology | 6         | 7      | 0.27%   |
| Fujitsu             | 6         | 6      | 0.27%   |
| ShiJi               | 5         | 6      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| Phison SATA SSD 16GB            | 31        | 1.36%   |
| Transcend TS128GMSA230S 128GB   | 30        | 1.31%   |
| China SATA SSD 16GB             | 25        | 1.09%   |
| Samsung SSD 850 EVO 250GB       | 21        | 0.92%   |
| Kingston SA400S37120G 120GB     | 19        | 0.83%   |
| Samsung SSD 860 EVO 500GB       | 18        | 0.79%   |
| Crucial CT240BX500SSD1 240GB    | 18        | 0.79%   |
| Samsung SSD 840 EVO 250GB       | 16        | 0.7%    |
| A-DATA IM2S3134N-064GM 64GB     | 16        | 0.7%    |
| Transcend TS64GMSA230S 64GB     | 15        | 0.66%   |
| Transcend TS256GMSA230S 256GB   | 15        | 0.66%   |
| Samsung SSD 870 EVO 250GB       | 15        | 0.66%   |
| Crucial CT120BX500SSD1 120GB    | 15        | 0.66%   |
| Transcend TS64GSSD370 64GB      | 14        | 0.61%   |
| Samsung SSD 840 EVO 120GB       | 14        | 0.61%   |
| Kingston SUV500MS120G 120GB     | 13        | 0.57%   |
| FORESEE 128GB SSD               | 13        | 0.57%   |
| SanDisk SSD PLUS 120GB          | 12        | 0.52%   |
| Innodisk DEMSR- 08GB mSATA 3ME3 | 12        | 0.52%   |
| SanDisk SSD PLUS 240GB          | 11        | 0.48%   |
| Samsung SSD 860 EVO 250GB       | 11        | 0.48%   |
| Kingston SA400S37240G 240GB     | 11        | 0.48%   |
| Intenso SSD 128GB               | 11        | 0.48%   |
| Hoodisk SSD 64GB                | 11        | 0.48%   |
| Hoodisk SSD 128GB               | 11        | 0.48%   |
| SanDisk SDSSDA120G 120GB        | 10        | 0.44%   |
| Intenso SSD 120GB               | 10        | 0.44%   |
| Crucial CT500MX500SSD1 500GB    | 10        | 0.44%   |
| WDC WD40EFRX-68N32N0 4TB        | 9         | 0.39%   |
| Transcend TS32GSSD370S 32GB     | 9         | 0.39%   |
| Transcend TS32GMSA370 32GB      | 9         | 0.39%   |
| Transcend TS128GMSA370 128GB    | 9         | 0.39%   |
| Samsung SSD 970 EVO Plus 500GB  | 9         | 0.39%   |
| Samsung SSD 850 EVO 500GB       | 9         | 0.39%   |
| Kingston SV300S37A120G 120GB    | 9         | 0.39%   |
| Kingston SKC600MS256G 256GB     | 9         | 0.39%   |
| Intel SSDSC2BB120G4 120GB       | 9         | 0.39%   |
| HP RAID 1(1+0) 304GB            | 9         | 0.39%   |
| Crucial CT250MX500SSD1 250GB    | 9         | 0.39%   |
| Samsung SSD 850 PRO 256GB       | 8         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 123       | 222    | 29.5%   |
| Seagate             | 103       | 171    | 24.7%   |
| Toshiba             | 43        | 74     | 10.31%  |
| Hitachi             | 38        | 65     | 9.11%   |
| HGST                | 35        | 68     | 8.39%   |
| Samsung Electronics | 19        | 25     | 4.56%   |
| NVMe                | 16        | 27     | 3.84%   |
| Hewlett-Packard     | 15        | 20     | 3.6%    |
| Fujitsu             | 6         | 6      | 1.44%   |
| OPENBSD             | 3         | 6      | 0.72%   |
| LSILOGIC            | 2         | 5      | 0.48%   |
| JetFlash            | 2         | 2      | 0.48%   |
| Apple               | 2         | 2      | 0.48%   |
| WD MediaMax         | 1         | 3      | 0.24%   |
| Product:            | 1         | 1      | 0.24%   |
| Maxtor              | 1         | 1      | 0.24%   |
| LSI                 | 1         | 1      | 0.24%   |
| Intenso             | 1         | 1      | 0.24%   |
| IBM/Hitachi         | 1         | 1      | 0.24%   |
| IBM                 | 1         | 1      | 0.24%   |
| Generic             | 1         | 1      | 0.24%   |
| General             | 1         | 1      | 0.24%   |
| ASMT                | 1         | 1      | 0.24%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 269       | 409    | 18.16%  |
| Transcend           | 180       | 250    | 12.15%  |
| Kingston            | 122       | 197    | 8.24%   |
| SanDisk             | 121       | 166    | 8.17%   |
| Intel               | 109       | 185    | 7.36%   |
| Crucial             | 105       | 158    | 7.09%   |
| China               | 60        | 72     | 4.05%   |
| Intenso             | 47        | 70     | 3.17%   |
| A-DATA Technology   | 40        | 48     | 2.7%    |
| Phison              | 36        | 52     | 2.43%   |
| Hoodisk             | 35        | 60     | 2.36%   |
| WDC                 | 30        | 33     | 2.03%   |
| Innodisk            | 26        | 30     | 1.76%   |
| Micron Technology   | 23        | 36     | 1.55%   |
| FORESEE             | 22        | 30     | 1.49%   |
| Toshiba             | 18        | 28     | 1.22%   |
| ATP                 | 18        | 18     | 1.22%   |
| OCZ                 | 15        | 24     | 1.01%   |
| Protectli           | 12        | 15     | 0.81%   |
| Apacer              | 12        | 20     | 0.81%   |
| SPCC                | 10        | 15     | 0.68%   |
| Apple               | 10        | 10     | 0.68%   |
| SK hynix            | 9         | 10     | 0.61%   |
| NVMe                | 9         | 13     | 0.61%   |
| Dogfish             | 8         | 10     | 0.54%   |
| Verbatim            | 7         | 13     | 0.47%   |
| TCSUNBOW            | 7         | 8      | 0.47%   |
| Patriot             | 7         | 9      | 0.47%   |
| LITEON              | 7         | 8      | 0.47%   |
| Corsair             | 7         | 11     | 0.47%   |
| LITEONIT            | 6         | 8      | 0.41%   |
| ShiJi               | 5         | 6      | 0.34%   |
| PNY                 | 5         | 6      | 0.34%   |
| KingSpec            | 5         | 6      | 0.34%   |
| VICKTER             | 4         | 4      | 0.27%   |
| Vaseky              | 4         | 4      | 0.27%   |
| Seagate             | 4         | 9      | 0.27%   |
| Leven               | 4         | 6      | 0.27%   |
| Kston               | 4         | 5      | 0.27%   |
| KingDian            | 4         | 10     | 0.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1380      | 2149   | 67.88%  |
| HDD  | 354       | 705    | 17.41%  |
| NVMe | 299       | 449    | 14.71%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1619      | 2854   | 84.41%  |
| NVMe | 299       | 449    | 15.59%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 1478      | 2275   | 83.64%  |
| 0.51-1.0        | 160       | 256    | 9.05%   |
| 1.01-2.0        | 66        | 154    | 3.74%   |
| 3.01-4.0        | 29        | 90     | 1.64%   |
| 4.01-10.0       | 15        | 28     | 0.85%   |
| 2.01-3.0        | 14        | 38     | 0.79%   |
| 10.01-20.0      | 4         | 12     | 0.23%   |
| More than 100.0 | 1         | 1      | 0.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 895       | 43.3%   |
| 251-500        | 286       | 13.84%  |
| 1-20           | 274       | 13.26%  |
| 51-100         | 229       | 11.08%  |
| 21-50          | 222       | 10.74%  |
| 501-1000       | 104       | 5.03%   |
| 1001-2000      | 22        | 1.06%   |
| More than 3000 | 16        | 0.77%   |
| Unknown        | 13        | 0.63%   |
| 2001-3000      | 6         | 0.29%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1886      | 90.67%  |
| 21-50          | 93        | 4.47%   |
| 51-100         | 37        | 1.78%   |
| 101-250        | 26        | 1.25%   |
| Unknown        | 13        | 0.63%   |
| 251-500        | 8         | 0.38%   |
| 501-1000       | 7         | 0.34%   |
| 1001-2000      | 5         | 0.24%   |
| More than 3000 | 3         | 0.14%   |
| 2001-3000      | 2         | 0.1%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Kingston SV300S37A60G 64GB                   | 4         | 6      | 2.26%   |
| WDC WD2000FYYZ-01UL1B2 2TB                   | 3         | 5      | 1.69%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 3         | 5      | 1.69%   |
| Kingston SMS200S360G 64GB                    | 3         | 3      | 1.69%   |
| WDC WDS240G2G0A-00JH30 240GB                 | 2         | 3      | 1.13%   |
| WDC WD30EFRX-68EUZN0 3TB                     | 2         | 7      | 1.13%   |
| WDC WD2000FYYZ-01UL1B1 2TB                   | 2         | 4      | 1.13%   |
| WDC WD1600AAJS-75M0A0 160GB                  | 2         | 2      | 1.13%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB         | 2         | 8      | 1.13%   |
| Toshiba THNSNK128GCS8 SATA 128GB             | 2         | 2      | 1.13%   |
| Seagate ST9320325AS 320GB                    | 2         | 2      | 1.13%   |
| Seagate ST3160318AS 160GB                    | 2         | 2      | 1.13%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 2         | 2      | 1.13%   |
| Seagate ST1000DX001-1CM162 1TB               | 2         | 2      | 1.13%   |
| SanDisk SSD PLUS 240GB                       | 2         | 2      | 1.13%   |
| Samsung Electronics HD501LJ 500GB            | 2         | 2      | 1.13%   |
| Micron Technology 1100_MTFDDAK512TBN 512GB   | 2         | 4      | 1.13%   |
| Micron Technology 1100 SATA 256GB            | 2         | 2      | 1.13%   |
| Kingston SMS200S3120G 120GB                  | 2         | 3      | 1.13%   |
| Kingston SHFS37A120G 120GB                   | 2         | 3      | 1.13%   |
| Intenso SSD SATAIII 256GB                    | 2         | 2      | 1.13%   |
| Intel SSDSC2CT180A3 180GB                    | 2         | 2      | 1.13%   |
| Intel SSDSC2CT120A3 120GB                    | 2         | 2      | 1.13%   |
| Intel SSDSC2BF180A4L 180GB                   | 2         | 2      | 1.13%   |
| Hitachi HTS545032B9A300 320GB                | 2         | 4      | 1.13%   |
| Hitachi HTS543232L9SA02 320GB                | 2         | 3      | 1.13%   |
| Hitachi HTS543225L9A300 250GB                | 2         | 2      | 1.13%   |
| HGST HTS541010A9E680 1TB                     | 2         | 3      | 1.13%   |
| HGST HTS541010A7E630 1TB                     | 2         | 4      | 1.13%   |
| Crucial CT275MX300SSD1 275GB                 | 2         | 2      | 1.13%   |
| Apacer 8GB SATA Flash Drive                  | 2         | 2      | 1.13%   |
| WDC WD60EFRX-68TGBN1 6TB                     | 1         | 3      | 0.56%   |
| WDC WD5000LPVX-22V0TT0 500GB                 | 1         | 1      | 0.56%   |
| WDC WD3200BEVT-22ZCT0 320GB                  | 1         | 1      | 0.56%   |
| WDC WD3000BLFS-60YBU2 304GB                  | 1         | 2      | 0.56%   |
| WDC WD2503ABYX-01WERA1 256GB                 | 1         | 4      | 0.56%   |
| WDC WD2503ABYX-01WERA0 256GB                 | 1         | 2      | 0.56%   |
| WDC WD20EFRX-68EUZN0 2TB                     | 1         | 2      | 0.56%   |
| WDC WD1600BEVS-07RST0 160GB                  | 1         | 1      | 0.56%   |
| WDC WD1600AAJS-08L7A0 160GB                  | 1         | 1      | 0.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 28        | 34     | 15.91%  |
| WDC                 | 25        | 44     | 14.2%   |
| Kingston            | 17        | 22     | 9.66%   |
| Samsung Electronics | 15        | 20     | 8.52%   |
| Intel               | 15        | 17     | 8.52%   |
| Hitachi             | 14        | 19     | 7.95%   |
| Crucial             | 9         | 22     | 5.11%   |
| SanDisk             | 8         | 11     | 4.55%   |
| HGST                | 8         | 12     | 4.55%   |
| Toshiba             | 7         | 16     | 3.98%   |
| Micron Technology   | 6         | 8      | 3.41%   |
| Apacer              | 4         | 4      | 2.27%   |
| Intenso             | 3         | 3      | 1.7%    |
| A-DATA Technology   | 3         | 4      | 1.7%    |
| OCZ                 | 2         | 2      | 1.14%   |
| Corsair             | 2         | 4      | 1.14%   |
| China               | 2         | 2      | 1.14%   |
| Transcend           | 1         | 2      | 0.57%   |
| SPCC                | 1         | 1      | 0.57%   |
| SMI                 | 1         | 1      | 0.57%   |
| SK hynix            | 1         | 1      | 0.57%   |
| Maxtor              | 1         | 1      | 0.57%   |
| KingSpec            | 1         | 1      | 0.57%   |
| KingDian            | 1         | 3      | 0.57%   |
| Fujitsu             | 1         | 1      | 0.57%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 28        | 34     | 33.73%  |
| WDC                 | 23        | 41     | 27.71%  |
| Hitachi             | 14        | 19     | 16.87%  |
| HGST                | 8         | 12     | 9.64%   |
| Samsung Electronics | 5         | 7      | 6.02%   |
| Toshiba             | 3         | 6      | 3.61%   |
| Maxtor              | 1         | 1      | 1.2%    |
| Fujitsu             | 1         | 1      | 1.2%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 90        | 131    | 51.72%  |
| HDD  | 81        | 121    | 46.55%  |
| NVMe | 3         | 3      | 1.72%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart_bsd/drive_failed.svg)


| Model                                     | Computers | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| WDC WD3200BPVT-16JJ5T0 320GB              | 1         | 1      | 16.67%  |
| Transcend TS32GSSD370S 32GB               | 1         | 2      | 16.67%  |
| Samsung Electronics SSD 980 250GB         | 1         | 2      | 16.67%  |
| Micron Technology 1100_MTFDDAV256TBN 64GB | 1         | 1      | 16.67%  |
| Kingston SV300S37A60G 64GB                | 1         | 1      | 16.67%  |
| Intel SSDSC2BW120H6 120GB                 | 1         | 1      | 16.67%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 16.67%  |
| Transcend           | 1         | 2      | 16.67%  |
| Samsung Electronics | 1         | 2      | 16.67%  |
| Micron Technology   | 1         | 1      | 16.67%  |
| Kingston            | 1         | 1      | 16.67%  |
| Intel               | 1         | 1      | 16.67%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1698      | 2938   | 87.66%  |
| Malfunc  | 172       | 255    | 8.88%   |
| Detected | 61        | 102    | 3.15%   |
| Failed   | 6         | 8      | 0.31%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1494      | 63.04%  |
| AMD                              | 374       | 15.78%  |
| Samsung Electronics              | 133       | 5.61%   |
| Broadcom / LSI                   | 49        | 2.07%   |
| SanDisk                          | 42        | 1.77%   |
| Kingston Technology Company      | 31        | 1.31%   |
| ASMedia Technology               | 27        | 1.14%   |
| Phison Electronics               | 25        | 1.05%   |
| Transcend                        | 19        | 0.8%    |
| Hewlett-Packard                  | 16        | 0.68%   |
| Micron/Crucial Technology        | 15        | 0.63%   |
| Silicon Motion                   | 14        | 0.59%   |
| Nvidia                           | 14        | 0.59%   |
| Toshiba                          | 13        | 0.55%   |
| MAXIO Technology (Hangzhou)      | 13        | 0.55%   |
| Marvell Technology Group         | 13        | 0.55%   |
| Micron Technology                | 11        | 0.46%   |
| KIOXIA                           | 10        | 0.42%   |
| SK hynix                         | 7         | 0.3%    |
| VIA Technologies                 | 5         | 0.21%   |
| ATP ELECTRONICS                  | 5         | 0.21%   |
| Adaptec                          | 5         | 0.21%   |
| Shenzhen Longsys Electronics     | 4         | 0.17%   |
| JMicron Technology               | 4         | 0.17%   |
| Silicon Image                    | 3         | 0.13%   |
| 3ware                            | 3         | 0.13%   |
| Yangtze Memory Technologies      | 2         | 0.08%   |
| ULi Electronics                  | 2         | 0.08%   |
| Seagate Technology               | 2         | 0.08%   |
| Realtek Semiconductor            | 2         | 0.08%   |
| Hosin Global Electronics         | 2         | 0.08%   |
| Chelsio Communications           | 2         | 0.08%   |
| ADATA Technology                 | 2         | 0.08%   |
| Solid State Storage Technology   | 1         | 0.04%   |
| Silicon Integrated Systems [SiS] | 1         | 0.04%   |
| Lenovo                           | 1         | 0.04%   |
| Integrated Technology Express    | 1         | 0.04%   |
| Enmotus                          | 1         | 0.04%   |
| Artop Electronic                 | 1         | 0.04%   |
| Unknown                          | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 256       | 9.64%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 137       | 5.16%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 135       | 5.08%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 123       | 4.63%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 78        | 2.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 77        | 2.9%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 66        | 2.48%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 64        | 2.41%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 64        | 2.41%   |
| AMD FCH SATA Controller [IDE mode]                                               | 62        | 2.33%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 53        | 2%      |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 51        | 1.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 46        | 1.73%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 43        | 1.62%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 42        | 1.58%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 42        | 1.58%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 40        | 1.51%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 36        | 1.36%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 30        | 1.13%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 29        | 1.09%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                                 | 29        | 1.09%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 28        | 1.05%   |
| Intel Atom Processor C3000 Series SATA Controller 0                              | 27        | 1.02%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 26        | 0.98%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 26        | 0.98%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 25        | 0.94%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 24        | 0.9%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 24        | 0.9%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 24        | 0.9%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 24        | 0.9%    |
| Intel Atom Processor C3000 Series SATA Controller 1                              | 23        | 0.87%   |
| AMD 400 Series Chipset SATA Controller                                           | 23        | 0.87%   |
| Intel Comet Lake SATA AHCI Controller                                            | 22        | 0.83%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 22        | 0.83%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 20        | 0.75%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 18        | 0.68%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 17        | 0.64%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 17        | 0.64%   |
| Intel SATA Controller [RAID mode]                                                | 16        | 0.6%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 15        | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1726      | 71.29%  |
| NVMe | 348       | 14.37%  |
| IDE  | 208       | 8.59%   |
| RAID | 104       | 4.3%    |
| SAS  | 18        | 0.74%   |
| SCSI | 17        | 0.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 1586      | 78.71%  |
| AMD     | 409       | 20.3%   |
| ARM     | 14        | 0.69%   |
| VIA     | 2         | 0.1%    |
| Unknown | 2         | 0.1%    |
| Sun     | 1         | 0.05%   |
| PowerPC | 1         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| AMD GX-412TC SOC                          | 119       | 5.86%   |
| Intel Celeron J4125 CPU @ 2.00GHz         | 67        | 3.3%    |
| Intel Celeron N5105 @ 2.00GHz             | 44        | 2.17%   |
| Intel Celeron CPU J1900 @ 1.99GHz         | 37        | 1.82%   |
| Intel Celeron CPU J3160 @ 1.60GHz         | 35        | 1.72%   |
| AMD GX-415GA SOC with Radeon HD Graphics  | 32        | 1.58%   |
| Intel Celeron CPU N3450 @ 1.10GHz         | 27        | 1.33%   |
| AMD GX-222GC SOC with Radeon R5E Graphics | 23        | 1.13%   |
| Intel Core i5-6500 CPU @ 3.20GHz          | 19        | 0.94%   |
| Intel Atom CPU C3558 @ 2.20GHz            | 19        | 0.94%   |
| Intel Core i5-7200U CPU @ 2.50GHz         | 18        | 0.89%   |
| Intel Xeon CPU D-1518 @ 2.20GHz           | 17        | 0.84%   |
| Intel Celeron N4100 CPU @ 1.10GHz         | 17        | 0.84%   |
| Intel Celeron J4105 CPU @ 1.50GHz         | 17        | 0.84%   |
| AMD Ryzen Embedded V1500B                 | 17        | 0.84%   |
| Intel Atom CPU D525 @ 1.80GHz             | 16        | 0.79%   |
| Intel Atom CPU C2558 @ 2.40GHz            | 16        | 0.79%   |
| Intel Core i7-8550U CPU @ 1.80GHz         | 15        | 0.74%   |
| Intel Core i5-8250U CPU @ 1.60GHz         | 15        | 0.74%   |
| Intel Celeron CPU N3150 @ 1.60GHz         | 15        | 0.74%   |
| Intel Celeron CPU J3455 @ 1.50GHz         | 15        | 0.74%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz  | 14        | 0.69%   |
| Intel Core i7-7500U CPU @ 2.70GHz         | 14        | 0.69%   |
| AMD G-T40E Processor                      | 14        | 0.69%   |
| Intel N100                                | 13        | 0.64%   |
| Intel Core i5-6300U CPU @ 2.40GHz         | 12        | 0.59%   |
| Intel Core i3-7100U CPU @ 2.40GHz         | 11        | 0.54%   |
| Intel Core i5-8365U CPU @ 1.60GHz         | 10        | 0.49%   |
| Intel Core i5-6200U CPU @ 2.30GHz         | 10        | 0.49%   |
| Intel Core i5-3470 CPU @ 3.20GHz          | 10        | 0.49%   |
| Intel Core i5-2520M CPU @ 2.50GHz         | 10        | 0.49%   |
| Intel Celeron CPU N3160 @ 1.60GHz         | 10        | 0.49%   |
| Intel Celeron                             | 10        | 0.49%   |
| Intel Atom CPU N450 @ 1.66GHz             | 10        | 0.49%   |
| AMD GX-424CC SOC with Radeon R5E Graphics | 10        | 0.49%   |
| Intel Core i5-5300U CPU @ 2.30GHz         | 9         | 0.44%   |
| Intel Core i5-10210U CPU @ 1.60GHz        | 9         | 0.44%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz        | 9         | 0.44%   |
| Intel Celeron J6412 @ 2.00GHz             | 9         | 0.44%   |
| Intel Celeron J4115 CPU @ 1.80GHz         | 9         | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Celeron           | 404       | 19.95%  |
| Intel Core i5           | 332       | 16.4%   |
| AMD GX                  | 205       | 10.12%  |
| Intel Xeon              | 186       | 9.19%   |
| Intel Core i3           | 149       | 7.36%   |
| Intel Atom              | 145       | 7.16%   |
| Intel Core i7           | 144       | 7.11%   |
| Other                   | 82        | 4.05%   |
| Intel Pentium           | 47        | 2.32%   |
| AMD Ryzen 7             | 37        | 1.83%   |
| Intel Core 2 Duo        | 32        | 1.58%   |
| Intel Pentium Silver    | 31        | 1.53%   |
| AMD Ryzen 5             | 29        | 1.43%   |
| AMD Ryzen Embedded      | 20        | 0.99%   |
| AMD G                   | 20        | 0.99%   |
| AMD FX                  | 15        | 0.74%   |
| AMD EPYC                | 14        | 0.69%   |
| Intel Pentium Dual-Core | 12        | 0.59%   |
| Intel Pentium Gold      | 10        | 0.49%   |
| Intel Core 2 Quad       | 10        | 0.49%   |
| ARM Cortex              | 10        | 0.49%   |
| AMD Ryzen 5 PRO         | 7         | 0.35%   |
| AMD Ryzen 3             | 7         | 0.35%   |
| AMD Ryzen 9             | 6         | 0.3%    |
| AMD Ryzen 7 PRO         | 5         | 0.25%   |
| Intel Xeon Silver       | 4         | 0.2%    |
| Intel Xeon Gold         | 4         | 0.2%    |
| AMD E                   | 4         | 0.2%    |
| Intel Pentium M         | 3         | 0.15%   |
| Intel Pentium Dual      | 3         | 0.15%   |
| Intel Genuine           | 3         | 0.15%   |
| Intel Core i9           | 3         | 0.15%   |
| Intel Core 2            | 3         | 0.15%   |
| AMD Turion II Neo       | 3         | 0.15%   |
| AMD Ryzen Threadripper  | 3         | 0.15%   |
| AMD Athlon 64 X2        | 3         | 0.15%   |
| AMD Athlon              | 3         | 0.15%   |
| AMD A4                  | 3         | 0.15%   |
| AMD A10                 | 3         | 0.15%   |
| Intel Pentium 4         | 2         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1085      | 53.55%  |
| 2       | 573       | 28.28%  |
| 8       | 101       | 4.99%   |
| 6       | 71        | 3.5%    |
| Unknown | 64        | 3.16%   |
| 16      | 48        | 2.37%   |
| 12      | 39        | 1.92%   |
| 1       | 28        | 1.38%   |
| 32      | 7         | 0.35%   |
| 10      | 4         | 0.2%    |
| 24      | 2         | 0.1%    |
| 128     | 1         | 0.05%   |
| 36      | 1         | 0.05%   |
| 22      | 1         | 0.05%   |
| 20      | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1933      | 96.03%  |
| 2       | 53        | 2.63%   |
| Unknown | 27        | 1.34%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1237      | 61.36%  |
| 2       | 706       | 35.02%  |
| Unknown | 73        | 3.62%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 264       | 13.07%  |
| Silvermont    | 178       | 8.81%   |
| Haswell       | 174       | 8.61%   |
| Puma          | 162       | 8.02%   |
| Unknown       | 150       | 7.43%   |
| Goldmont plus | 139       | 6.88%   |
| Skylake       | 120       | 5.94%   |
| IvyBridge     | 103       | 5.1%    |
| Goldmont      | 97        | 4.8%    |
| SandyBridge   | 76        | 3.76%   |
| Penryn        | 61        | 3.02%   |
| Broadwell     | 60        | 2.97%   |
| Bonnell       | 50        | 2.48%   |
| Zen           | 49        | 2.43%   |
| Jaguar        | 49        | 2.43%   |
| Westmere      | 34        | 1.68%   |
| Core          | 32        | 1.58%   |
| Zen 2         | 30        | 1.49%   |
| Zen+          | 27        | 1.34%   |
| Bobcat        | 25        | 1.24%   |
| TigerLake     | 23        | 1.14%   |
| CometLake     | 21        | 1.04%   |
| Nehalem       | 18        | 0.89%   |
| Piledriver    | 16        | 0.79%   |
| Zen 3         | 15        | 0.74%   |
| IceLake       | 10        | 0.5%    |
| Steamroller   | 7         | 0.35%   |
| K8 Hammer     | 7         | 0.35%   |
| K10           | 5         | 0.25%   |
| P6            | 4         | 0.2%    |
| NetBurst      | 4         | 0.2%    |
| Bulldozer     | 4         | 0.2%    |
| Excavator     | 3         | 0.15%   |
| Geode         | 2         | 0.1%    |
| K10 Llano     | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1244      | 66.52%  |
| AMD                                          | 237       | 12.67%  |
| ASPEED Technology                            | 157       | 8.4%    |
| Nvidia                                       | 139       | 7.43%   |
| Matrox Electronics Systems                   | 88        | 4.71%   |
| VIA Technologies                             | 2         | 0.11%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.05%   |
| Trident Microsystems                         | 1         | 0.05%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                                 | 157       | 8.27%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 117       | 6.16%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 79        | 4.16%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 68        | 3.58%   |
| Intel JasperLake [UHD Graphics]                                                          | 65        | 3.42%   |
| Intel HD Graphics 500                                                                    | 64        | 3.37%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 63        | 3.32%   |
| Intel HD Graphics 620                                                                    | 49        | 2.58%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 45        | 2.37%   |
| Intel HD Graphics 530                                                                    | 43        | 2.27%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 41        | 2.16%   |
| Intel UHD Graphics 620                                                                   | 40        | 2.11%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 35        | 1.84%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 35        | 1.84%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 35        | 1.84%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 32        | 1.69%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 32        | 1.69%   |
| AMD Kabini [Radeon HD 8330E]                                                             | 32        | 1.69%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 30        | 1.58%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 27        | 1.42%   |
| Intel HD Graphics 5500                                                                   | 25        | 1.32%   |
| Matrox Electronics Systems MGA G200EH                                                    | 23        | 1.21%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 22        | 1.16%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 22        | 1.16%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 21        | 1.11%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 20        | 1.05%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 19        | 1%      |
| Intel HD Graphics 630                                                                    | 19        | 1%      |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 17        | 0.9%    |
| Intel Core Processor Integrated Graphics Controller                                      | 17        | 0.9%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 17        | 0.9%    |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 16        | 0.84%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 16        | 0.84%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 15        | 0.79%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 13        | 0.68%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 13        | 0.68%   |
| Intel HD Graphics 510                                                                    | 12        | 0.63%   |
| Intel Elkhart Lake [UHD Graphics Gen11 16EU]                                             | 12        | 0.63%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 12        | 0.63%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 12        | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1109      | 54.96%  |
| 1 x AMD                  | 224       | 11.1%   |
| Other                    | 214       | 10.6%   |
| 1 x ASPEED               | 142       | 7.04%   |
| 1 x Nvidia               | 97        | 4.81%   |
| 1 x Matrox               | 86        | 4.26%   |
| 2 x Intel                | 73        | 3.62%   |
| Intel + Nvidia           | 39        | 1.93%   |
| Intel + ASPEED           | 13        | 0.64%   |
| Intel + AMD              | 8         | 0.4%    |
| AMD + Nvidia             | 3         | 0.15%   |
| 1 x VIA                  | 2         | 0.1%    |
| Intel + Matrox           | 2         | 0.1%    |
| 2 x AMD                  | 1         | 0.05%   |
| 1 x XGI                  | 1         | 0.05%   |
| 1 x Trident Microsystems | 1         | 0.05%   |
| 1 x SiS                  | 1         | 0.05%   |
| Nvidia + ASPEED          | 1         | 0.05%   |
| AMD + ASPEED             | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1707      | 84.63%  |
| Unknown     | 236       | 11.7%   |
| Proprietary | 74        | 3.67%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1906      | 94.08%  |
| 1.01-2.0   | 34        | 1.68%   |
| 0.01-0.5   | 29        | 1.43%   |
| 3.01-4.0   | 19        | 0.94%   |
| 7.01-8.0   | 13        | 0.64%   |
| 0.51-1.0   | 11        | 0.54%   |
| 5.01-6.0   | 9         | 0.44%   |
| 2.01-3.0   | 4         | 0.2%    |
| 8.01-16.0  | 1         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 42        | 11.83%  |
| AU Optronics            | 38        | 10.7%   |
| Samsung Electronics     | 36        | 10.14%  |
| Dell                    | 23        | 6.48%   |
| Goldstar                | 20        | 5.63%   |
| Chimei Innolux          | 20        | 5.63%   |
| Apple                   | 20        | 5.63%   |
| BOE                     | 17        | 4.79%   |
| BenQ                    | 17        | 4.79%   |
| Lenovo                  | 15        | 4.23%   |
| Acer                    | 11        | 3.1%    |
| Ancor Communications    | 10        | 2.82%   |
| Hewlett-Packard         | 9         | 2.54%   |
| Iiyama                  | 8         | 2.25%   |
| Eizo                    | 8         | 2.25%   |
| Sharp                   | 6         | 1.69%   |
| LG Electronics          | 6         | 1.69%   |
| Fujitsu Siemens         | 6         | 1.69%   |
| NEC Computers           | 5         | 1.41%   |
| AOC                     | 5         | 1.41%   |
| InfoVision              | 4         | 1.13%   |
| Philips                 | 3         | 0.85%   |
| PANDA                   | 3         | 0.85%   |
| Idek Iiyama             | 3         | 0.85%   |
| HannStar                | 2         | 0.56%   |
| Belinea                 | 2         | 0.56%   |
| ASUSTek Computer        | 2         | 0.56%   |
| Unknown                 | 2         | 0.56%   |
| WYT                     | 1         | 0.28%   |
| TRU                     | 1         | 0.28%   |
| Toshiba                 | 1         | 0.28%   |
| Panasonic               | 1         | 0.28%   |
| Mi                      | 1         | 0.28%   |
| Medion                  | 1         | 0.28%   |
| LTM                     | 1         | 0.28%   |
| LG Philips              | 1         | 0.28%   |
| JDI                     | 1         | 0.28%   |
| CSO                     | 1         | 0.28%   |
| Chi Mei Optoelectronics | 1         | 0.28%   |
| CHD                     | 1         | 0.28%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                 | 5         | 1.36%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch           | 4         | 1.08%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch | 3         | 0.81%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch          | 3         | 0.81%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch              | 3         | 0.81%   |
| Fujitsu Siemens B24-9 WE FUS08C3 1920x1200 520x320mm 24.0-inch       | 3         | 0.81%   |
| BOE LCD Monitor BOE05E0 1366x768 280x160mm 12.7-inch                 | 3         | 0.81%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch       | 3         | 0.81%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch       | 3         | 0.81%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch        | 3         | 0.81%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch        | 3         | 0.81%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 290x170mm 13.2-inch              | 2         | 0.54%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch    | 2         | 0.54%   |
| Samsung Electronics C32JG5x SAM0FDE 2560x1440 700x390mm 31.5-inch    | 2         | 0.54%   |
| PANDA LCD Monitor NCP002D 1920x1080 340x190mm 15.3-inch              | 2         | 0.54%   |
| LG Display LCD Monitor LGD057E 1920x1080 340x190mm 15.3-inch         | 2         | 0.54%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch         | 2         | 0.54%   |
| LG Display LCD Monitor LGD04A3 1366x768 280x160mm 12.7-inch          | 2         | 0.54%   |
| LG Display LCD Monitor LGD045E 1366x768 310x170mm 13.9-inch          | 2         | 0.54%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch         | 2         | 0.54%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch          | 2         | 0.54%   |
| LG Display LCD Monitor LGD0353 1366x768 350x190mm 15.7-inch          | 2         | 0.54%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch             | 2         | 0.54%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch              | 2         | 0.54%   |
| Hewlett-Packard LP2475w HWP26F9 1920x1200 540x350mm 25.3-inch        | 2         | 0.54%   |
| Hewlett-Packard LP2475w HWP26F8 1920x1200 540x350mm 25.3-inch        | 2         | 0.54%   |
| Hewlett-Packard LA2405 HWP284B 1920x1200 520x320mm 24.0-inch         | 2         | 0.54%   |
| Goldstar W2261 GSM56CF 1920x1080 530x300mm 24.0-inch                 | 2         | 0.54%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch           | 2         | 0.54%   |
| Goldstar LG HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch             | 2         | 0.54%   |
| Goldstar E2441 GSM581F 1920x1080 530x300mm 24.0-inch                 | 2         | 0.54%   |
| Eizo EV2450 ENC2530 1920x1080 530x300mm 24.0-inch                    | 2         | 0.54%   |
| Dell U2414H DELA0A2 1920x1080 530x300mm 24.0-inch                    | 2         | 0.54%   |
| Dell LCD Monitor U2412M 3840x1200                                    | 2         | 0.54%   |
| Dell LCD Monitor U2412M                                              | 2         | 0.54%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch     | 2         | 0.54%   |
| BOE LCD Monitor BOE0900 1920x1080 340x190mm 15.3-inch                | 2         | 0.54%   |
| BOE LCD Monitor BOE08EE 1920x1080 310x170mm 13.9-inch                | 2         | 0.54%   |
| BenQ GW2765 BNQ78D6 2560x1440 600x340mm 27.2-inch                    | 2         | 0.54%   |
| BenQ GW2260 BNQ78C4 1920x1080 480x270mm 21.7-inch                    | 2         | 0.54%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 134       | 38.07%  |
| 1366x768 (WXGA)    | 55        | 15.63%  |
| 2560x1440 (QHD)    | 31        | 8.81%   |
| 3840x2160 (4K)     | 28        | 7.95%   |
| 1920x1200 (WUXGA)  | 25        | 7.1%    |
| 1680x1050 (WSXGA+) | 11        | 3.13%   |
| 1280x800 (WXGA)    | 11        | 3.13%   |
| 1280x1024 (SXGA)   | 11        | 3.13%   |
| 1600x900 (HD+)     | 10        | 2.84%   |
| 1440x900 (WXGA+)   | 9         | 2.56%   |
| 3440x1440          | 4         | 1.14%   |
| 2560x1600          | 3         | 0.85%   |
| 2560x1080          | 3         | 0.85%   |
| Unknown            | 3         | 0.85%   |
| 3840x1200          | 2         | 0.57%   |
| 3200x1800 (QHD+)   | 2         | 0.57%   |
| 2880x1800          | 2         | 0.57%   |
| 1024x768 (XGA)     | 2         | 0.57%   |
| 9600x2160          | 1         | 0.28%   |
| 720x1280           | 1         | 0.28%   |
| 3840x1080          | 1         | 0.28%   |
| 3600x1080          | 1         | 0.28%   |
| 3000x2000          | 1         | 0.28%   |
| 1920x540           | 1         | 0.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 69        | 19.49%  |
| 15      | 54        | 15.25%  |
| 24      | 43        | 12.15%  |
| 27      | 42        | 11.86%  |
| 12      | 26        | 7.34%   |
| Unknown | 26        | 7.34%   |
| 23      | 17        | 4.8%    |
| 21      | 14        | 3.95%   |
| 17      | 9         | 2.54%   |
| 11      | 8         | 2.26%   |
| 22      | 7         | 1.98%   |
| 19      | 7         | 1.98%   |
| 14      | 7         | 1.98%   |
| 34      | 5         | 1.41%   |
| 31      | 5         | 1.41%   |
| 25      | 3         | 0.85%   |
| 20      | 3         | 0.85%   |
| 32      | 2         | 0.56%   |
| 46      | 1         | 0.28%   |
| 39      | 1         | 0.28%   |
| 29      | 1         | 0.28%   |
| 26      | 1         | 0.28%   |
| 18      | 1         | 0.28%   |
| 16      | 1         | 0.28%   |
| 6       | 1         | 0.28%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 102       | 28.9%   |
| 501-600     | 100       | 28.33%  |
| 201-300     | 65        | 18.41%  |
| Unknown     | 26        | 7.37%   |
| 401-500     | 25        | 7.08%   |
| 351-400     | 14        | 3.97%   |
| 601-700     | 11        | 3.12%   |
| 701-800     | 7         | 1.98%   |
| 801-900     | 1         | 0.28%   |
| 101-200     | 1         | 0.28%   |
| 1001-1500   | 1         | 0.28%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 237       | 69.91%  |
| 16/10   | 56        | 16.52%  |
| Unknown | 25        | 7.37%   |
| 5/4     | 8         | 2.36%   |
| 21/9    | 5         | 1.47%   |
| 3/2     | 4         | 1.18%   |
| 4/3     | 3         | 0.88%   |
| 6/5     | 1         | 0.29%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 61        | 17.23%  |
| 201-250        | 58        | 16.38%  |
| 301-350        | 43        | 12.15%  |
| 91-100         | 37        | 10.45%  |
| 61-70          | 26        | 7.34%   |
| Unknown        | 26        | 7.34%   |
| 251-300        | 25        | 7.06%   |
| 101-110        | 18        | 5.08%   |
| 71-80          | 14        | 3.95%   |
| 351-500        | 13        | 3.67%   |
| 151-200        | 12        | 3.39%   |
| 51-60          | 8         | 2.26%   |
| 121-130        | 7         | 1.98%   |
| 141-150        | 2         | 0.56%   |
| 501-1000       | 2         | 0.56%   |
| 1-40           | 1         | 0.28%   |
| 131-140        | 1         | 0.28%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 109       | 31.41%  |
| 121-160       | 100       | 28.82%  |
| 101-120       | 66        | 19.02%  |
| 161-240       | 34        | 9.8%    |
| Unknown       | 26        | 7.49%   |
| More than 240 | 11        | 3.17%   |
| 1-50          | 1         | 0.29%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1664      | 82.25%  |
| 1     | 324       | 16.02%  |
| 2     | 33        | 1.63%   |
| 3     | 2         | 0.1%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1609      | 58.4%   |
| Realtek Semiconductor             | 622       | 22.58%  |
| Broadcom                          | 155       | 5.63%   |
| Qualcomm Atheros                  | 125       | 4.54%   |
| AMD                               | 25        | 0.91%   |
| IMC Networks                      | 17        | 0.62%   |
| Mellanox Technologies             | 16        | 0.58%   |
| Ralink Technology                 | 14        | 0.51%   |
| Ericsson Business Mobile Networks | 13        | 0.47%   |
| Marvell Technology Group          | 12        | 0.44%   |
| TP-Link                           | 11        | 0.4%    |
| Edimax Technology                 | 10        | 0.36%   |
| Nvidia                            | 9         | 0.33%   |
| Sierra Wireless                   | 8         | 0.29%   |
| Ralink                            | 8         | 0.29%   |
| American Megatrends               | 8         | 0.29%   |
| U-Blox                            | 7         | 0.25%   |
| MediaTek                          | 7         | 0.25%   |
| D-Link System                     | 7         | 0.25%   |
| Chelsio Communications            | 6         | 0.22%   |
| Google                            | 5         | 0.18%   |
| Emulex                            | 5         | 0.18%   |
| IBM                               | 4         | 0.15%   |
| Dell                              | 4         | 0.15%   |
| ASUSTek Computer                  | 4         | 0.15%   |
| Aquantia                          | 4         | 0.15%   |
| Huawei Technologies               | 3         | 0.11%   |
| Samsung Electronics               | 2         | 0.07%   |
| Qualcomm Atheros Communications   | 2         | 0.07%   |
| NetXen Incorporated               | 2         | 0.07%   |
| Insyde Software                   | 2         | 0.07%   |
| ICS Advent                        | 2         | 0.07%   |
| Hewlett-Packard                   | 2         | 0.07%   |
| Fibocom                           | 2         | 0.07%   |
| Dresden Elektronik                | 2         | 0.07%   |
| Apple                             | 2         | 0.07%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.04%   |
| Xiaomi                            | 1         | 0.04%   |
| ULi Electronics                   | 1         | 0.04%   |
| T & A Mobile Phones               | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 547       | 15.98%  |
| Intel I211 Gigabit Network Connection                                         | 345       | 10.08%  |
| Intel I210 Gigabit Network Connection                                         | 270       | 7.89%   |
| Intel I350 Gigabit Network Connection                                         | 137       | 4%      |
| Intel Ethernet Controller I225-V                                              | 101       | 2.95%   |
| Intel 82574L Gigabit Network Connection                                       | 85        | 2.48%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 73        | 2.13%   |
| Intel Ethernet Controller I226-V                                              | 60        | 1.75%   |
| Intel 82580 Gigabit Network Connection                                        | 47        | 1.37%   |
| Intel 82583V Gigabit Network Connection                                       | 37        | 1.08%   |
| Intel 82576 Gigabit Network Connection                                        | 37        | 1.08%   |
| Intel Wireless 3165                                                           | 36        | 1.05%   |
| Intel Wi-Fi 6 AX200                                                           | 36        | 1.05%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 35        | 1.02%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 34        | 0.99%   |
| Intel Wireless 7265                                                           | 33        | 0.96%   |
| Realtek RTL8125 2.5GbE Controller                                             | 32        | 0.93%   |
| Intel Ethernet Connection I217-LM                                             | 32        | 0.93%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 32        | 0.93%   |
| Intel Ethernet Connection I354                                                | 30        | 0.88%   |
| Intel Ethernet Connection X553 1GbE                                           | 28        | 0.82%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 27        | 0.79%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 27        | 0.79%   |
| Intel Wireless 8265 / 8275                                                    | 25        | 0.73%   |
| AMD XGMAC 10GbE Controller                                                    | 25        | 0.73%   |
| Intel Ethernet Connection I219-LM                                             | 24        | 0.7%    |
| Intel Ethernet Connection (2) I219-V                                          | 23        | 0.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 23        | 0.67%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 22        | 0.64%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 22        | 0.64%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 22        | 0.64%   |
| Intel Wireless 8260                                                           | 20        | 0.58%   |
| Intel Ethernet Connection (2) I219-LM                                         | 20        | 0.58%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 19        | 0.55%   |
| Intel Wireless 7260                                                           | 19        | 0.55%   |
| Intel Ethernet Connection (7) I219-LM                                         | 19        | 0.55%   |
| Intel Wireless 3160                                                           | 17        | 0.5%    |
| Intel Ethernet Connection X552 10 GbE SFP+                                    | 17        | 0.5%    |
| Intel Ethernet Connection (7) I219-V                                          | 17        | 0.5%    |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                          | 16        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 366       | 54.06%  |
| Qualcomm Atheros                | 111       | 16.4%   |
| Realtek Semiconductor           | 72        | 10.64%  |
| Broadcom                        | 45        | 6.65%   |
| IMC Networks                    | 17        | 2.51%   |
| Ralink Technology               | 14        | 2.07%   |
| TP-Link                         | 11        | 1.62%   |
| Edimax Technology               | 10        | 1.48%   |
| Ralink                          | 8         | 1.18%   |
| MediaTek                        | 7         | 1.03%   |
| Sierra Wireless                 | 6         | 0.89%   |
| ASUSTek Computer                | 4         | 0.59%   |
| Qualcomm Atheros Communications | 2         | 0.3%    |
| Qualcomm Technologies           | 1         | 0.15%   |
| Micro Star International        | 1         | 0.15%   |
| Dell                            | 1         | 0.15%   |
| Accton Technology               | 1         | 0.15%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Intel Wireless 3165                                             | 36        | 5.29%   |
| Intel Wi-Fi 6 AX200                                             | 36        | 5.29%   |
| Intel Wireless 7265                                             | 33        | 4.85%   |
| Intel Wireless 8265 / 8275                                      | 25        | 3.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                    | 23        | 3.38%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)  | 22        | 3.23%   |
| Intel Gemini Lake PCH CNVi WiFi                                 | 22        | 3.23%   |
| Intel Wireless 8260                                             | 20        | 2.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter      | 19        | 2.79%   |
| Intel Wireless 7260                                             | 19        | 2.79%   |
| Intel Wireless 3160                                             | 17        | 2.5%    |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card            | 16        | 2.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 15        | 2.2%    |
| Intel Centrino Ultimate-N 6300                                  | 15        | 2.2%    |
| Intel Wireless-AC 9260                                          | 13        | 1.91%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                | 12        | 1.76%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                          | 11        | 1.62%   |
| Intel Centrino Advanced-N 6235                                  | 11        | 1.62%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter      | 10        | 1.47%   |
| Intel Wi-Fi 6 AX201                                             | 10        | 1.47%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 10        | 1.47%   |
| Broadcom BCM43224 802.11a/b/g/n                                 | 10        | 1.47%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter | 9         | 1.32%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                | 9         | 1.32%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)  | 9         | 1.32%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter        | 7         | 1.03%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                      | 7         | 1.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter      | 7         | 1.03%   |
| Intel Cannon Lake PCH CNVi WiFi                                 | 7         | 1.03%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter    | 7         | 1.03%   |
| Broadcom BCM4321 802.11a/b/g/n                                  | 7         | 1.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter             | 6         | 0.88%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                | 6         | 0.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                               | 6         | 0.88%   |
| Sierra Wireless EM7455                                          | 5         | 0.73%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter        | 5         | 0.73%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection   | 5         | 0.73%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection           | 5         | 0.73%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                        | 5         | 0.73%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]  | 5         | 0.73%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 1421      | 63.32%  |
| Realtek Semiconductor       | 597       | 26.6%   |
| Broadcom                    | 119       | 5.3%    |
| AMD                         | 25        | 1.11%   |
| Qualcomm Atheros            | 17        | 0.76%   |
| Marvell Technology Group    | 12        | 0.53%   |
| Nvidia                      | 9         | 0.4%    |
| American Megatrends         | 8         | 0.36%   |
| Google                      | 5         | 0.22%   |
| Emulex                      | 4         | 0.18%   |
| D-Link System               | 4         | 0.18%   |
| Aquantia                    | 4         | 0.18%   |
| Samsung Electronics         | 2         | 0.09%   |
| Insyde Software             | 2         | 0.09%   |
| ICS Advent                  | 2         | 0.09%   |
| Chelsio Communications      | 2         | 0.09%   |
| Apple                       | 2         | 0.09%   |
| Xiaomi                      | 1         | 0.04%   |
| T & A Mobile Phones         | 1         | 0.04%   |
| SysKonnect                  | 1         | 0.04%   |
| Standard Microsystems [SMC] | 1         | 0.04%   |
| QLogic                      | 1         | 0.04%   |
| National Semiconductor      | 1         | 0.04%   |
| JMicron Technology          | 1         | 0.04%   |
| Digital Equipment           | 1         | 0.04%   |
| Davicom Semiconductor       | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 547       | 20.59%  |
| Intel I211 Gigabit Network Connection                                         | 345       | 12.98%  |
| Intel I210 Gigabit Network Connection                                         | 270       | 10.16%  |
| Intel I350 Gigabit Network Connection                                         | 137       | 5.16%   |
| Intel Ethernet Controller I225-V                                              | 101       | 3.8%    |
| Intel 82574L Gigabit Network Connection                                       | 85        | 3.2%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 73        | 2.75%   |
| Intel Ethernet Controller I226-V                                              | 60        | 2.26%   |
| Intel 82580 Gigabit Network Connection                                        | 47        | 1.77%   |
| Intel 82583V Gigabit Network Connection                                       | 37        | 1.39%   |
| Intel 82576 Gigabit Network Connection                                        | 37        | 1.39%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 35        | 1.32%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 34        | 1.28%   |
| Intel Ethernet Connection I217-LM                                             | 32        | 1.2%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 32        | 1.2%    |
| Realtek RTL8125 2.5GbE Controller                                             | 31        | 1.17%   |
| Intel Ethernet Connection I354                                                | 30        | 1.13%   |
| Intel Ethernet Connection X553 1GbE                                           | 28        | 1.05%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 27        | 1.02%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 27        | 1.02%   |
| AMD XGMAC 10GbE Controller                                                    | 25        | 0.94%   |
| Intel Ethernet Connection I219-LM                                             | 24        | 0.9%    |
| Intel Ethernet Connection (2) I219-V                                          | 23        | 0.87%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 22        | 0.83%   |
| Intel Ethernet Connection (2) I219-LM                                         | 20        | 0.75%   |
| Intel Ethernet Connection (7) I219-LM                                         | 19        | 0.72%   |
| Intel Ethernet Connection X552 10 GbE SFP+                                    | 17        | 0.64%   |
| Intel Ethernet Connection (7) I219-V                                          | 17        | 0.64%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 15        | 0.56%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 15        | 0.56%   |
| Intel Ethernet Controller X550                                                | 14        | 0.53%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 13        | 0.49%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 13        | 0.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 12        | 0.45%   |
| Intel I350 Gigabit Fiber Network Connection                                   | 11        | 0.41%   |
| Intel Ethernet Connection I217-V                                              | 11        | 0.41%   |
| Intel Ethernet Connection (4) I219-V                                          | 11        | 0.41%   |
| Intel 82579V Gigabit Network Connection                                       | 11        | 0.41%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 11        | 0.41%   |
| Intel 82577LM Gigabit Network Connection                                      | 10        | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1958      | 73.28%  |
| WiFi     | 632       | 23.65%  |
| Unknown  | 54        | 2.02%   |
| Modem    | 28        | 1.05%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1869      | 89.64%  |
| WiFi     | 205       | 9.83%   |
| Unknown  | 10        | 0.48%   |
| Modem    | 1         | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 475       | 23.3%   |
| 4     | 395       | 19.37%  |
| 3     | 322       | 15.79%  |
| 6     | 240       | 11.77%  |
| 1     | 238       | 11.67%  |
| 5     | 161       | 7.9%    |
| 8     | 90        | 4.41%   |
| 10    | 33        | 1.62%   |
| 7     | 24        | 1.18%   |
| 9     | 21        | 1.03%   |
| 0     | 19        | 0.93%   |
| 12    | 11        | 0.54%   |
| 14    | 4         | 0.2%    |
| 20    | 2         | 0.1%    |
| 11    | 2         | 0.1%    |
| 17    | 1         | 0.05%   |
| 16    | 1         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1637      | 77.99%  |
| Yes  | 462       | 22.01%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 249       | 59.86%  |
| Apple                           | 29        | 6.97%   |
| IMC Networks                    | 27        | 6.49%   |
| Qualcomm Atheros Communications | 26        | 6.25%   |
| Broadcom                        | 25        | 6.01%   |
| Realtek Semiconductor           | 23        | 5.53%   |
| Foxconn / Hon Hai               | 9         | 2.16%   |
| ASUSTek Computer                | 7         | 1.68%   |
| Lite-On Technology              | 4         | 0.96%   |
| Cambridge Silicon Radio         | 4         | 0.96%   |
| MediaTek                        | 3         | 0.72%   |
| Dell                            | 3         | 0.72%   |
| Hewlett-Packard                 | 2         | 0.48%   |
| Alps Electric                   | 2         | 0.48%   |
| USI                             | 1         | 0.24%   |
| Micro Star International        | 1         | 0.24%   |
| Unknown                         | 1         | 0.24%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 110       | 26.38%  |
| Intel AX200 Bluetooth                                       | 37        | 8.87%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 35        | 8.39%   |
| Intel AX201 Bluetooth                                       | 20        | 4.8%    |
| Intel Centrino Bluetooth Wireless Transceiver               | 15        | 3.6%    |
| Realtek Bluetooth Adapter                                   | 13        | 3.12%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 13        | 3.12%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 13        | 3.12%   |
| Apple Bluetooth Host Controller                             | 12        | 2.88%   |
| Intel Wireless-AC 3168 Bluetooth                            | 10        | 2.4%    |
| Intel AX210 Bluetooth                                       | 9         | 2.16%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 9         | 2.16%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 9         | 2.16%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 8         | 1.92%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 8         | 1.92%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip        | 6         | 1.44%   |
| IMC Networks Realtek Bluetooth Adapter                      | 4         | 0.96%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 4         | 0.96%   |
| Realtek  Bluetooth 4.2 Adapter                              | 3         | 0.72%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 3         | 0.72%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 3         | 0.72%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 3         | 0.72%   |
| MediaTek RZ608 Bluetooth Adapter                            | 3         | 0.72%   |
| Lite-On Atheros AR3012 Bluetooth                            | 3         | 0.72%   |
| ASUS USB-BT500                                              | 3         | 0.72%   |
| Apple Broadcom Built-in Bluetooth                           | 3         | 0.72%   |
| Realtek Bluetooth 4.2 Adapter                               | 2         | 0.48%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 2         | 0.48%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 2         | 0.48%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3012 Bluetooth Adapter | 2         | 0.48%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 2         | 0.48%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 2         | 0.48%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 2         | 0.48%   |
| Broadcom BCM2045 Bluetooth                                  | 2         | 0.48%   |
| Apple Bluetooth USB Host Controller                         | 2         | 0.48%   |
| Apple Bluetooth HCI                                         | 2         | 0.48%   |
| USI Qualcomm WCN685x Bluetooth Adapter                      | 1         | 0.24%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 1         | 0.24%   |
| Realtek RTL8821A Bluetooth                                  | 1         | 0.24%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 0.24%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1092      | 71.37%  |
| AMD                                          | 267       | 17.45%  |
| Nvidia                                       | 97        | 6.34%   |
| C-Media Electronics                          | 15        | 0.98%   |
| Logitech                                     | 7         | 0.46%   |
| Zoran Co. Personal Media Division (Nogatech) | 5         | 0.33%   |
| GN Netcom                                    | 5         | 0.33%   |
| Texas Instruments                            | 4         | 0.26%   |
| JMTek                                        | 4         | 0.26%   |
| VIA Technologies                             | 3         | 0.2%    |
| Tenx Technology                              | 3         | 0.2%    |
| Creative Labs                                | 3         | 0.2%    |
| Realtek Semiconductor                        | 2         | 0.13%   |
| Kingston Technology                          | 2         | 0.13%   |
| Corsair                                      | 2         | 0.13%   |
| Audient                                      | 2         | 0.13%   |
| ZOOM                                         | 1         | 0.07%   |
| Yamaha                                       | 1         | 0.07%   |
| ULi Electronics                              | 1         | 0.07%   |
| Trust                                        | 1         | 0.07%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.07%   |
| RME                                          | 1         | 0.07%   |
| Phison Electronics                           | 1         | 0.07%   |
| Native Instruments                           | 1         | 0.07%   |
| M-Audio                                      | 1         | 0.07%   |
| Lenovo                                       | 1         | 0.07%   |
| Hewlett-Packard                              | 1         | 0.07%   |
| Generalplus Technology                       | 1         | 0.07%   |
| ESS Technology                               | 1         | 0.07%   |
| DSEA A/S                                     | 1         | 0.07%   |
| Creative Technology                          | 1         | 0.07%   |
| Blue Microphones                             | 1         | 0.07%   |
| AudioQuest                                   | 1         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 119       | 6.61%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 119       | 6.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 84        | 4.67%   |
| AMD Kabini HDMI/DP Audio                                                                          | 84        | 4.67%   |
| AMD FCH Azalia Controller                                                                         | 72        | 4%      |
| AMD Family 17h/19h HD Audio Controller                                                            | 69        | 3.84%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 67        | 3.72%   |
| Intel Jasper Lake HD Audio                                                                        | 65        | 3.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 65        | 3.61%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 53        | 2.95%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 51        | 2.83%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 49        | 2.72%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 46        | 2.56%   |
| Intel Cannon Lake PCH cAVS                                                                        | 42        | 2.33%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 39        | 2.17%   |
| Intel 8 Series HD Audio Controller                                                                | 39        | 2.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 36        | 2%      |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 33        | 1.83%   |
| Intel Broadwell-U Audio Controller                                                                | 32        | 1.78%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 30        | 1.67%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 28        | 1.56%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 26        | 1.45%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 25        | 1.39%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 23        | 1.28%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 23        | 1.28%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 22        | 1.22%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 21        | 1.17%   |
| Intel 200 Series PCH HD Audio                                                                     | 21        | 1.17%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 20        | 1.11%   |
| Intel Alder Lake-N HD Graphics SGPC                                                               | 19        | 1.06%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 18        | 1%      |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 18        | 1%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 15        | 0.83%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 12        | 0.67%   |
| Intel Elkhart Lake High Density Audio bus interface                                               | 11        | 0.61%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 10        | 0.56%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 10        | 0.56%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 10        | 0.56%   |
| AMD Wrestler HDMI Audio                                                                           | 9         | 0.5%    |
| Nvidia MCP79 High Definition Audio                                                                | 8         | 0.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 376       | 18.63%  |
| Unknown                      | 271       | 13.43%  |
| Crucial                      | 231       | 11.45%  |
| Kingston                     | 222       | 11%     |
| SK hynix                     | 203       | 10.06%  |
| Micron Technology            | 165       | 8.18%   |
| G.Skill                      | 92        | 4.56%   |
| Corsair                      | 68        | 3.37%   |
| Unknown                      | 68        | 3.37%   |
| Transcend                    | 50        | 2.48%   |
| Unknown (ABCD)               | 44        | 2.18%   |
| A-DATA Technology            | 39        | 1.93%   |
| ATP                          | 27        | 1.34%   |
| Nanya Technology             | 24        | 1.19%   |
| Ramaxel Technology           | 19        | 0.94%   |
| Hewlett-Packard              | 16        | 0.79%   |
| Apacer                       | 13        | 0.64%   |
| Elpida                       | 9         | 0.45%   |
| Toshiba                      | 7         | 0.35%   |
| Kimtigo                      | 6         | 0.3%    |
| Shenzhen Jinge Information   | 5         | 0.25%   |
| Patriot                      | 5         | 0.25%   |
| Innodisk                     | 4         | 0.2%    |
| Wodposit                     | 3         | 0.15%   |
| Avant                        | 3         | 0.15%   |
| Unknown (AB)                 | 2         | 0.1%    |
| Unknown (0x7F7F7F94FFFFFFFF) | 2         | 0.1%    |
| Unknown (09C7)               | 2         | 0.1%    |
| Timetec                      | 2         | 0.1%    |
| Tigo                         | 2         | 0.1%    |
| Teikon                       | 2         | 0.1%    |
| SK_Hynix                     | 2         | 0.1%    |
| PNY                          | 2         | 0.1%    |
| HPE                          | 2         | 0.1%    |
| GeIL                         | 2         | 0.1%    |
| 48spaces                     | 2         | 0.1%    |
| 019400B300CE                 | 2         | 0.1%    |
| Vasekey                      | 1         | 0.05%   |
| Unknown (8A5D)               | 1         | 0.05%   |
| Unknown (8A02)               | 1         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown                                                        | 68        | 3.2%    |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                    | 51        | 2.4%    |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 44        | 2.07%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 21        | 0.99%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 18        | 0.85%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 16        | 0.75%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s            | 14        | 0.66%   |
| Micron RAM 8KTF51264HZ-1G9P1 4GB SODIMM DDR3 1867MT/s          | 14        | 0.66%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 13        | 0.61%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 12        | 0.56%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 12        | 0.56%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 12        | 0.56%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 12        | 0.56%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 11        | 0.52%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s          | 11        | 0.52%   |
| ATP RAM X4G08QA8BNWESO-7-TO1 8GB SODIMM DDR4 3200MT/s          | 11        | 0.52%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 10        | 0.47%   |
| Micron RAM Module 8GB Row Of Chips LPDDR4 3200MT/s             | 10        | 0.47%   |
| G.Skill RAM F4-2400C16-8GRS 8GB SODIMM DDR4 2400MT/s           | 10        | 0.47%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s          | 9         | 0.42%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s        | 9         | 0.42%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s          | 9         | 0.42%   |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s                     | 8         | 0.38%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 8         | 0.38%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 8         | 0.38%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s           | 8         | 0.38%   |
| Crucial RAM CT102464BF160B.C16 8GB DIMM DDR3 1600MT/s          | 8         | 0.38%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                      | 7         | 0.33%   |
| Unknown RAM Module 4GB DIMM DDR2 800MT/s                       | 7         | 0.33%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                     | 7         | 0.33%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 7         | 0.33%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s         | 7         | 0.33%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s          | 7         | 0.33%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s          | 7         | 0.33%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s          | 7         | 0.33%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s         | 7         | 0.33%   |
| Samsung RAM M391B1G73QH0-YK0 8GB DIMM DDR3 1600MT/s            | 7         | 0.33%   |
| Samsung RAM M391A2K43BB1-CTD 16GB DIMM DDR4 3200MT/s           | 7         | 0.33%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1333MT/s            | 7         | 0.33%   |
| G.Skill RAM F4-2400C16-4GRS 4GB SODIMM DDR4 2400MT/s           | 7         | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 827       | 44.99%  |
| DDR4    | 756       | 41.13%  |
| DDR2    | 86        | 4.68%   |
| LPDDR4  | 64        | 3.48%   |
| Unknown | 37        | 2.01%   |
| SDRAM   | 25        | 1.36%   |
| DDR5    | 16        | 0.87%   |
| DDR     | 11        | 0.6%    |
| LPDDR3  | 8         | 0.44%   |
| LPDDR5  | 6         | 0.33%   |
| RAM     | 1         | 0.05%   |
| DRAM    | 1         | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 961       | 52.66%  |
| DIMM         | 813       | 44.55%  |
| Row Of Chips | 35        | 1.92%   |
| Unknown      | 8         | 0.44%   |
| Chip         | 6         | 0.33%   |
| FB-DIMM      | 2         | 0.11%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 715       | 36.87%  |
| 4096  | 611       | 31.51%  |
| 16384 | 285       | 14.7%   |
| 2048  | 239       | 12.33%  |
| 32768 | 46        | 2.37%   |
| 1024  | 36        | 1.86%   |
| 512   | 4         | 0.21%   |
| 256   | 2         | 0.1%    |
| 65536 | 1         | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 530       | 27.66%  |
| 2400    | 263       | 13.73%  |
| 1333    | 234       | 12.21%  |
| 2667    | 221       | 11.53%  |
| 3200    | 199       | 10.39%  |
| 2133    | 99        | 5.17%   |
| 667     | 63        | 3.29%   |
| 800     | 61        | 3.18%   |
| 1867    | 35        | 1.83%   |
| Unknown | 33        | 1.72%   |
| 2666    | 24        | 1.25%   |
| 1066    | 21        | 1.1%    |
| 1334    | 20        | 1.04%   |
| 1866    | 19        | 0.99%   |
| 1067    | 19        | 0.99%   |
| 2933    | 14        | 0.73%   |
| 4800    | 13        | 0.68%   |
| 3000    | 13        | 0.68%   |
| 6400    | 6         | 0.31%   |
| 4267    | 5         | 0.26%   |
| 3600    | 5         | 0.26%   |
| 533     | 4         | 0.21%   |
| 5600    | 2         | 0.1%    |
| 1033    | 2         | 0.1%    |
| 333     | 2         | 0.1%    |
| 65535   | 1         | 0.05%   |
| 5200    | 1         | 0.05%   |
| 3534    | 1         | 0.05%   |
| 3500    | 1         | 0.05%   |
| 2600    | 1         | 0.05%   |
| 1639    | 1         | 0.05%   |
| 1419    | 1         | 0.05%   |
| 975     | 1         | 0.05%   |
| 400     | 1         | 0.05%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart_bsd/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 3         | 42.86%  |
| Ricoh               | 1         | 14.29%  |
| QinHeng Electronics | 1         | 14.29%  |
| Prolific Technology | 1         | 14.29%  |
| Hewlett-Packard     | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart_bsd/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Brother MFC-7360N             | 2         | 28.57%  |
| Ricoh SP 112                  | 1         | 14.29%  |
| QinHeng CH340S                | 1         | 14.29%  |
| Prolific PL2305 Parallel Port | 1         | 14.29%  |
| HP HP LaserJet P2035 HP Print | 1         | 14.29%  |
| Brother HL-L2310D series      | 1         | 14.29%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart_bsd/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Canon       | 3         | 75%     |
| Seiko Epson | 1         | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart_bsd/scanner_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                             | 2         | 50%     |
| Seiko Epson WF-2860 Series EPSON Scanner USB2.0 Printer EPSON Utility USB2.0 Faxout | 1         | 25%     |
| Canon CanoScan LiDE 120                                                             | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 65        | 31.4%   |
| Bison Electronics                      | 25        | 12.08%  |
| Realtek Semiconductor                  | 13        | 6.28%   |
| IMC Networks                           | 13        | 6.28%   |
| Microdia                               | 12        | 5.8%    |
| Logitech                               | 10        | 4.83%   |
| Suyin                                  | 9         | 4.35%   |
| Sunplus Innovation Technology          | 9         | 4.35%   |
| Lite-On Technology                     | 9         | 4.35%   |
| Syntek                                 | 7         | 3.38%   |
| Apple                                  | 6         | 2.9%    |
| Lenovo                                 | 5         | 2.42%   |
| Alcor Micro                            | 4         | 1.93%   |
| Quanta                                 | 3         | 1.45%   |
| Z-Star Microelectronics                | 2         | 0.97%   |
| Silicon Motion                         | 2         | 0.97%   |
| Luxvisions Innotech Limited            | 2         | 0.97%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 0.97%   |
| ARC International                      | 2         | 0.97%   |
| Trust                                  | 1         | 0.48%   |
| Tripath Technology                     | 1         | 0.48%   |
| SunplusIT                              | 1         | 0.48%   |
| Ricoh                                  | 1         | 0.48%   |
| Pixart Imaging                         | 1         | 0.48%   |
| Intel                                  | 1         | 0.48%   |
| Cubeternet                             | 1         | 0.48%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 27        | 12.98%  |
| Bison Integrated Camera                  | 12        | 5.77%   |
| IMC Networks Integrated Camera           | 7         | 3.37%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 7         | 3.37%   |
| Lite-On Integrated Camera                | 6         | 2.88%   |
| Realtek USB 2.0 PC Camera                | 5         | 2.4%    |
| Microdia Integrated Webcam               | 5         | 2.4%    |
| Chicony FJ Camera                        | 5         | 2.4%    |
| Chicony HD Webcam                        | 4         | 1.92%   |
| Apple FaceTime HD Camera (Built-in)      | 4         | 1.92%   |
| Syntek Integrated Camera                 | 3         | 1.44%   |
| Suyin RGBIR Camera                       | 3         | 1.44%   |
| Chicony Integrated Camera [ThinkPad]     | 3         | 1.44%   |
| Bison ThinkPad Integrated Camera         | 3         | 1.44%   |
| Bison SunplusIT Integrated Camera        | 3         | 1.44%   |
| Alcor Micro USB 2.0 Camera               | 3         | 1.44%   |
| Syntek Lenovo EasyCamera                 | 2         | 0.96%   |
| Syntek EasyCamera                        | 2         | 0.96%   |
| Sunplus hama C-600 Pro Webcam            | 2         | 0.96%   |
| Realtek Integrated_Webcam_HD             | 2         | 0.96%   |
| Quanta HP TrueVision HD Camera           | 2         | 0.96%   |
| Microdia Integrated_Webcam_HD            | 2         | 0.96%   |
| Logitech Webcam C270                     | 2         | 0.96%   |
| Logitech HD Pro Webcam C920              | 2         | 0.96%   |
| Logitech C920 PRO HD Webcam              | 2         | 0.96%   |
| Logitech C920 HD Pro Webcam              | 2         | 0.96%   |
| Lite-On Realtek PC Camera                | 2         | 0.96%   |
| Lenovo Integrated Webcam [R5U877]        | 2         | 0.96%   |
| Lenovo Integrated Camera                 | 2         | 0.96%   |
| IMC Networks XHC Camera                  | 2         | 0.96%   |
| IMC Networks Realtek PC Camera           | 2         | 0.96%   |
| Chicony Integrated IR Camera             | 2         | 0.96%   |
| Chicony HP HD Webcam [Fixed]             | 2         | 0.96%   |
| Chicony HD WebCam (Acer)                 | 2         | 0.96%   |
| Chicony Chicony USB2.0 Camera            | 2         | 0.96%   |
| Bison SunplusIT INC. Integrated Camera   | 2         | 0.96%   |
| Bison Lenovo EasyCamera                  | 2         | 0.96%   |
| ARC International Camera                 | 2         | 0.96%   |
| Z-Star Venus USB2.0 Camera               | 1         | 0.48%   |
| Z-Star Lenovo USB 2.0 UVC Camera         | 1         | 0.48%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 27        | 36%     |
| Synaptics                  | 14        | 18.67%  |
| Upek                       | 11        | 14.67%  |
| LighTuning Technology      | 5         | 6.67%   |
| AuthenTec                  | 5         | 6.67%   |
| Shenzhen Goodix Technology | 4         | 5.33%   |
| Broadcom                   | 3         | 4%      |
| STMicroelectronics         | 2         | 2.67%   |
| Elan Microelectronics      | 2         | 2.67%   |
| Next Biometrics            | 1         | 1.33%   |
| DigitalPersona             | 1         | 1.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 10        | 13.33%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 10        | 13.33%  |
| Validity Sensors Synaptics WBDI                                              | 8         | 10.67%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 6         | 8%      |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 4         | 5.33%   |
| Shenzhen Goodix Fingerprint Reader                                           | 3         | 4%      |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 3         | 4%      |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 4%      |
| Validity Sensors VFS495 Fingerprint Reader                                   | 2         | 2.67%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 2         | 2.67%   |
| Validity Sensors Swipe Fingerprint Sensor                                    | 2         | 2.67%   |
| STMicroelectronics Fingerprint Reader                                        | 2         | 2.67%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 2         | 2.67%   |
| Elan Fingerprint Sensor                                                      | 2         | 2.67%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 1         | 1.33%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 1         | 1.33%   |
| Validity Sensors VFS Fingerprint sensor                                      | 1         | 1.33%   |
| Upek TCS5B Fingerprint sensor                                                | 1         | 1.33%   |
| Synaptics WBDI                                                               | 1         | 1.33%   |
| Synaptics TouchPad                                                           | 1         | 1.33%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 1         | 1.33%   |
| Shenzhen Goodix Fingerprint Reader SGX                                       | 1         | 1.33%   |
| Next Biometrics NB-2020-U Fingerprint Reader                                 | 1         | 1.33%   |
| DigitalPersona Fingerprint Reader                                            | 1         | 1.33%   |
| AuthenTec AES2660                                                            | 1         | 1.33%   |
| AuthenTec AES2550 Fingerprint Sensor                                         | 1         | 1.33%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 1         | 1.33%   |
| AuthenTec AES1660                                                            | 1         | 1.33%   |
| AuthenTec AES1600                                                            | 1         | 1.33%   |
| Unknown                                                                      | 1         | 1.33%   |

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
| 1     | 793       | 38.36%  |
| 0     | 748       | 36.19%  |
| 2     | 308       | 14.9%   |
| 3     | 140       | 6.77%   |
| 4     | 56        | 2.71%   |
| 5     | 18        | 0.87%   |
| 6     | 3         | 0.15%   |
| 7     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 1137      | 62.13%  |
| Bluetooth                | 194       | 10.6%   |
| Net/wireless             | 165       | 9.02%   |
| Card reader              | 118       | 6.45%   |
| Fingerprint reader       | 66        | 3.61%   |
| Firewire controller      | 41        | 2.24%   |
| Network                  | 28        | 1.53%   |
| Net/ethernet             | 28        | 1.53%   |
| Sound                    | 24        | 1.31%   |
| Graphics card            | 13        | 0.71%   |
| Modem                    | 5         | 0.27%   |
| Storage                  | 4         | 0.22%   |
| Storage/ide              | 2         | 0.11%   |
| Storage/ata              | 2         | 0.11%   |
| Storage/raid             | 1         | 0.05%   |
| Storage/nvme             | 1         | 0.05%   |
| Dvb card                 | 1         | 0.05%   |

