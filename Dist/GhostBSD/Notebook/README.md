GhostBSD - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------

A project to collect tested hardware configurations for GhostBSD.

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

Total: 429

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Dell          | Latitude 5520               | [3d736273f2](https://bsd-hardware.info/?probe=3d736273f2) | Jan 03, 2026 |
| Dell          | Latitude 5520               | [cced2f8275](https://bsd-hardware.info/?probe=cced2f8275) | Jan 03, 2026 |
| HP            | EliteBook 840 14 inch G9... | [eb83aa2496](https://bsd-hardware.info/?probe=eb83aa2496) | Jan 01, 2026 |
| Lenovo        | ThinkPad T440p 20AN0069U... | [8b6c965d1a](https://bsd-hardware.info/?probe=8b6c965d1a) | Dec 31, 2025 |
| Dell          | Inspiron 7570               | [a2828cbfd3](https://bsd-hardware.info/?probe=a2828cbfd3) | Dec 30, 2025 |
| Dell          | Latitude 7480               | [29771b2eb5](https://bsd-hardware.info/?probe=29771b2eb5) | Dec 28, 2025 |
| HP            | EliteBook Folio 9470m       | [e5cd4a5c15](https://bsd-hardware.info/?probe=e5cd4a5c15) | Dec 28, 2025 |
| ASUSTek       | X550MD                      | [99a920a6c2](https://bsd-hardware.info/?probe=99a920a6c2) | Dec 28, 2025 |
| ASUSTek       | X550MD                      | [02b8060e38](https://bsd-hardware.info/?probe=02b8060e38) | Dec 27, 2025 |
| Lenovo        | ThinkPad P50 20EN0008GE     | [b3d69c9aa9](https://bsd-hardware.info/?probe=b3d69c9aa9) | Dec 25, 2025 |
| Lenovo        | ThinkPad T480 20L6S9UJ0Y    | [6799072e37](https://bsd-hardware.info/?probe=6799072e37) | Dec 21, 2025 |
| Lenovo        | ThinkPad T480 20L6S9UJ0Y    | [e523952624](https://bsd-hardware.info/?probe=e523952624) | Dec 21, 2025 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [f83dfc4109](https://bsd-hardware.info/?probe=f83dfc4109) | Dec 21, 2025 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [d811e53da8](https://bsd-hardware.info/?probe=d811e53da8) | Dec 21, 2025 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | [ffcb3248bd](https://bsd-hardware.info/?probe=ffcb3248bd) | Dec 14, 2025 |
| Dynabook      | TECRA A65-M                 | [840b58a6a7](https://bsd-hardware.info/?probe=840b58a6a7) | Dec 13, 2025 |
| Dell          | Latitude 5410               | [0754c58554](https://bsd-hardware.info/?probe=0754c58554) | Dec 13, 2025 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [28e7de1846](https://bsd-hardware.info/?probe=28e7de1846) | Dec 08, 2025 |
| Dell          | Precision 3561              | [54c5a30bf4](https://bsd-hardware.info/?probe=54c5a30bf4) | Dec 08, 2025 |
| Dell          | Precision 3561              | [fcedc4b737](https://bsd-hardware.info/?probe=fcedc4b737) | Dec 08, 2025 |
| Dell          | Latitude 5520               | [a8c5ee2142](https://bsd-hardware.info/?probe=a8c5ee2142) | Dec 08, 2025 |
| Dell          | Latitude 5520               | [05c34d8bb3](https://bsd-hardware.info/?probe=05c34d8bb3) | Dec 08, 2025 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [36459b9771](https://bsd-hardware.info/?probe=36459b9771) | Dec 08, 2025 |
| Dell          | Latitude E5470              | [a7cb7055f2](https://bsd-hardware.info/?probe=a7cb7055f2) | Nov 08, 2025 |
| Acer          | Aspire One 721              | [0eaa05c265](https://bsd-hardware.info/?probe=0eaa05c265) | Nov 04, 2025 |
| Dell          | Inspiron 5559               | [99739a132e](https://bsd-hardware.info/?probe=99739a132e) | Oct 08, 2025 |
| Maibenben     | Perfectum Series            | [e978b41d08](https://bsd-hardware.info/?probe=e978b41d08) | Oct 08, 2025 |
| Maibenben     | Perfectum Series            | [6bc4e3e498](https://bsd-hardware.info/?probe=6bc4e3e498) | Oct 07, 2025 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | [eca4ec1a99](https://bsd-hardware.info/?probe=eca4ec1a99) | Sep 30, 2025 |
| Apple         | MacBookPro13,3              | [49878f209a](https://bsd-hardware.info/?probe=49878f209a) | Sep 24, 2025 |
| HP            | EliteBook Folio 9470m       | [4db41bab3d](https://bsd-hardware.info/?probe=4db41bab3d) | Sep 17, 2025 |
| HP            | EliteBook Folio 9470m       | [de941693ae](https://bsd-hardware.info/?probe=de941693ae) | Sep 17, 2025 |
| Lenovo        | ThinkPad T420 4236PGG       | [a29d54028d](https://bsd-hardware.info/?probe=a29d54028d) | Sep 12, 2025 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [be8b97c582](https://bsd-hardware.info/?probe=be8b97c582) | Sep 09, 2025 |
| Lenovo        | ThinkPad T580 20LAS1KA00    | [89a15e05f2](https://bsd-hardware.info/?probe=89a15e05f2) | Sep 09, 2025 |
| Toshiba       | Satellite C800D             | [34b6824adf](https://bsd-hardware.info/?probe=34b6824adf) | Aug 31, 2025 |
| Acer          | Aspire V5-552               | [4fa113dd6b](https://bsd-hardware.info/?probe=4fa113dd6b) | Aug 28, 2025 |
| Lenovo        | ThinkPad T495 20NKS0VS00    | [d5e5e1f2f8](https://bsd-hardware.info/?probe=d5e5e1f2f8) | Aug 26, 2025 |
| Lenovo        | ThinkPad T430 2347H76       | [84bb1f6dc9](https://bsd-hardware.info/?probe=84bb1f6dc9) | Aug 02, 2025 |
| Lenovo        | G550 2958                   | [7c91a69398](https://bsd-hardware.info/?probe=7c91a69398) | Jul 19, 2025 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [afc0b4763b](https://bsd-hardware.info/?probe=afc0b4763b) | Jul 12, 2025 |
| TongFang      | GX4HRXL                     | [62273ded61](https://bsd-hardware.info/?probe=62273ded61) | Jul 07, 2025 |
| HP            | Pavilion 15                 | [752aebbc02](https://bsd-hardware.info/?probe=752aebbc02) | Jul 06, 2025 |
| TongFang      | GX4HRXL                     | [b54a0dfd0b](https://bsd-hardware.info/?probe=b54a0dfd0b) | Jul 04, 2025 |
| Lenovo        | ThinkPad E450 20DDA01N00    | [1b5cdf08d1](https://bsd-hardware.info/?probe=1b5cdf08d1) | Jul 03, 2025 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [358f4cfd1b](https://bsd-hardware.info/?probe=358f4cfd1b) | Jun 28, 2025 |
| Lenovo        | ThinkPad X140e 20BLS0030... | [91a25e5e00](https://bsd-hardware.info/?probe=91a25e5e00) | Jun 11, 2025 |
| Lenovo        | ThinkPad T480 20L6S01Q0L    | [dec1fd17c7](https://bsd-hardware.info/?probe=dec1fd17c7) | May 30, 2025 |
| Apple         | MacBookAir7,2               | [90aebce5fd](https://bsd-hardware.info/?probe=90aebce5fd) | May 30, 2025 |
| Apple         | MacBookAir7,2               | [90d94c1634](https://bsd-hardware.info/?probe=90d94c1634) | May 30, 2025 |
| Lenovo        | ThinkPad L460 20FVS09Y00    | [c2a9872e05](https://bsd-hardware.info/?probe=c2a9872e05) | May 21, 2025 |
| Lenovo        | Edge 2-1580 80QF            | [1149223c0f](https://bsd-hardware.info/?probe=1149223c0f) | May 18, 2025 |
| MSI           | Bravo 15 A4DDR              | [ec1b01599f](https://bsd-hardware.info/?probe=ec1b01599f) | Apr 29, 2025 |
| Acer          | Aspire A715-72G             | [732e17bbc7](https://bsd-hardware.info/?probe=732e17bbc7) | Apr 27, 2025 |
| ASUSTek       | K54C                        | [edee4fc655](https://bsd-hardware.info/?probe=edee4fc655) | Apr 27, 2025 |
| Lenovo        | ThinkPad T410s 2912WAV      | [a95acc5b5c](https://bsd-hardware.info/?probe=a95acc5b5c) | Apr 13, 2025 |
| Acer          | Aspire S3-391               | [a7147a8af2](https://bsd-hardware.info/?probe=a7147a8af2) | Apr 09, 2025 |
| Acer          | Aspire A715-72G             | [b96f13784f](https://bsd-hardware.info/?probe=b96f13784f) | Apr 03, 2025 |
| Lenovo        | ThinkPad X140e 20BLS0030... | [09033922c5](https://bsd-hardware.info/?probe=09033922c5) | Mar 31, 2025 |
| Dell          | XPS 13 9360                 | [31f9120390](https://bsd-hardware.info/?probe=31f9120390) | Mar 28, 2025 |
| HUAWEI        | BOHK-WAX9X                  | [38343a4b77](https://bsd-hardware.info/?probe=38343a4b77) | Mar 27, 2025 |
| Lenovo        | ThinkPad E14 Gen 6 21M3C... | [c97f313465](https://bsd-hardware.info/?probe=c97f313465) | Mar 25, 2025 |
| Lenovo        | Legion S7 15ACH6 82K8       | [cc3cc39541](https://bsd-hardware.info/?probe=cc3cc39541) | Mar 21, 2025 |
| HP            | EliteBook 820 G2            | [0e727af2b4](https://bsd-hardware.info/?probe=0e727af2b4) | Mar 10, 2025 |
| Lenovo        | ThinkPad W550s 20E2000QU... | [8e2f33a68c](https://bsd-hardware.info/?probe=8e2f33a68c) | Mar 07, 2025 |
| Lenovo        | ThinkPad W550s 20E2000QU... | [0243819ad2](https://bsd-hardware.info/?probe=0243819ad2) | Mar 07, 2025 |
| HUAWEI        | MACHR-WX9                   | [b5535a2385](https://bsd-hardware.info/?probe=b5535a2385) | Mar 05, 2025 |
| HP            | EliteBook 820 G2            | [ed0e3bf954](https://bsd-hardware.info/?probe=ed0e3bf954) | Mar 05, 2025 |
| HP            | Laptop 15s-eq1xxx           | [cac24c9711](https://bsd-hardware.info/?probe=cac24c9711) | Mar 05, 2025 |
| Lenovo        | ThinkPad T530 2394AG9       | [5c28f10554](https://bsd-hardware.info/?probe=5c28f10554) | Mar 04, 2025 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [84a91bc1c5](https://bsd-hardware.info/?probe=84a91bc1c5) | Mar 03, 2025 |
| Dell          | Vostro 15 3510              | [d47e0cff38](https://bsd-hardware.info/?probe=d47e0cff38) | Feb 25, 2025 |
| Toshiba       | Satellite L50-C             | [9d0d1b266c](https://bsd-hardware.info/?probe=9d0d1b266c) | Feb 20, 2025 |
| HP            | ProBook 4310s               | [134569627f](https://bsd-hardware.info/?probe=134569627f) | Feb 20, 2025 |
| HP            | Dev One Notebook PC         | [8d9ec6acdb](https://bsd-hardware.info/?probe=8d9ec6acdb) | Feb 15, 2025 |
| Apple         | MacBookPro11,2              | [3e1c40aa06](https://bsd-hardware.info/?probe=3e1c40aa06) | Feb 06, 2025 |
| Acer          | TravelMate P648-G3-M        | [a36092b332](https://bsd-hardware.info/?probe=a36092b332) | Feb 04, 2025 |
| Lenovo        | ThinkPad Edge E531 68855... | [abbd058fa0](https://bsd-hardware.info/?probe=abbd058fa0) | Jan 21, 2025 |
| Lenovo        | ThinkPad L380 20M6S2FU00    | [8cb99e3fe8](https://bsd-hardware.info/?probe=8cb99e3fe8) | Jan 20, 2025 |
| Lenovo        | ThinkPad T490 20N3S4PX00    | [4954bab835](https://bsd-hardware.info/?probe=4954bab835) | Jan 07, 2025 |
| Dell          | Inspiron 3476               | [3dc38e6815](https://bsd-hardware.info/?probe=3dc38e6815) | Jan 03, 2025 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [c6697164fc](https://bsd-hardware.info/?probe=c6697164fc) | Jan 02, 2025 |
| HUAWEI        | KPL-W0X                     | [51514fe0c0](https://bsd-hardware.info/?probe=51514fe0c0) | Dec 28, 2024 |
| HUAWEI        | KPL-W0X                     | [7d9a498768](https://bsd-hardware.info/?probe=7d9a498768) | Dec 28, 2024 |
| Lenovo        | ThinkPad T430 2342CTO       | [10ab9145d9](https://bsd-hardware.info/?probe=10ab9145d9) | Dec 24, 2024 |
| Dell          | XPS 9320                    | [659b5961cc](https://bsd-hardware.info/?probe=659b5961cc) | Dec 23, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [aa6a6969b9](https://bsd-hardware.info/?probe=aa6a6969b9) | Dec 12, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [cfc56b5602](https://bsd-hardware.info/?probe=cfc56b5602) | Dec 11, 2024 |
| HP            | 250 G3                      | [102fa9b597](https://bsd-hardware.info/?probe=102fa9b597) | Dec 04, 2024 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [7a03bbeb04](https://bsd-hardware.info/?probe=7a03bbeb04) | Nov 25, 2024 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [36ab98d9df](https://bsd-hardware.info/?probe=36ab98d9df) | Nov 25, 2024 |
| Dell          | Latitude E5440              | [289f3c134f](https://bsd-hardware.info/?probe=289f3c134f) | Nov 24, 2024 |
| Samsung       | 530XBB                      | [9d6127f039](https://bsd-hardware.info/?probe=9d6127f039) | Nov 18, 2024 |
| Lenovo        | Legion Slim 5 16IRH8 83D... | [ab3ba2edf5](https://bsd-hardware.info/?probe=ab3ba2edf5) | Nov 18, 2024 |
| Lenovo        | Legion Slim 5 16IRH8 83D... | [2a9c5b1e5c](https://bsd-hardware.info/?probe=2a9c5b1e5c) | Nov 18, 2024 |
| Notebook      | NL40_50CU                   | [9b197cd6fc](https://bsd-hardware.info/?probe=9b197cd6fc) | Nov 18, 2024 |
| Notebook      | NL40_50CU                   | [88b9892dd2](https://bsd-hardware.info/?probe=88b9892dd2) | Nov 18, 2024 |
| Toshiba       | Satellite L655              | [dc1b79d2f5](https://bsd-hardware.info/?probe=dc1b79d2f5) | Nov 13, 2024 |
| Toshiba       | Satellite L655              | [8a36444ca1](https://bsd-hardware.info/?probe=8a36444ca1) | Nov 13, 2024 |
| Lenovo        | ThinkPad T470p 20J6003DG... | [aa3a0567b3](https://bsd-hardware.info/?probe=aa3a0567b3) | Nov 07, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [3eedf19995](https://bsd-hardware.info/?probe=3eedf19995) | Oct 30, 2024 |
| HP            | 250 15.6 inch G9 Noteboo... | [4a1456a0fa](https://bsd-hardware.info/?probe=4a1456a0fa) | Oct 22, 2024 |
| HP            | EliteBook 820 G3            | [5ac0371f28](https://bsd-hardware.info/?probe=5ac0371f28) | Oct 18, 2024 |
| HP            | EliteBook 820 G3            | [553b42ed1a](https://bsd-hardware.info/?probe=553b42ed1a) | Oct 18, 2024 |
| Dell          | Inspiron 13-7368            | [2dc255b034](https://bsd-hardware.info/?probe=2dc255b034) | Oct 17, 2024 |
| HP            | Unknown                     | [254f5a847c](https://bsd-hardware.info/?probe=254f5a847c) | Oct 17, 2024 |
| Dell          | XPS 13 7390                 | [425f5093f7](https://bsd-hardware.info/?probe=425f5093f7) | Oct 13, 2024 |
| HP            | 250 15.6 inch G9 Noteboo... | [29ab309c41](https://bsd-hardware.info/?probe=29ab309c41) | Oct 12, 2024 |
| HP            | 250 15.6 inch G9 Noteboo... | [1b0b42530b](https://bsd-hardware.info/?probe=1b0b42530b) | Oct 11, 2024 |
| HP            | 250 15.6 inch G9 Noteboo... | [1c29a0f0a3](https://bsd-hardware.info/?probe=1c29a0f0a3) | Oct 11, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [1b5dcf47fe](https://bsd-hardware.info/?probe=1b5dcf47fe) | Oct 07, 2024 |
| Notebook      | NL40_50CU                   | [680cd09351](https://bsd-hardware.info/?probe=680cd09351) | Oct 06, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | [869d37ac5e](https://bsd-hardware.info/?probe=869d37ac5e) | Oct 04, 2024 |
| Dell          | G3 3579                     | [1725db4da9](https://bsd-hardware.info/?probe=1725db4da9) | Sep 27, 2024 |
| Notebook      | NL40_50CU                   | [95fbcd46d1](https://bsd-hardware.info/?probe=95fbcd46d1) | Sep 26, 2024 |
| Lenovo        | Yoga 900S-12ISK 80ML        | [8836aa08ec](https://bsd-hardware.info/?probe=8836aa08ec) | Sep 23, 2024 |
| Dell          | Vostro 5490                 | [32de340e28](https://bsd-hardware.info/?probe=32de340e28) | Sep 23, 2024 |
| Dell          | Latitude E6540              | [14fbf15794](https://bsd-hardware.info/?probe=14fbf15794) | Sep 13, 2024 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [c6c35c6a96](https://bsd-hardware.info/?probe=c6c35c6a96) | Sep 05, 2024 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [cd17d71b66](https://bsd-hardware.info/?probe=cd17d71b66) | Sep 05, 2024 |
| Lenovo        | Yoga 900S-12ISK 80ML        | [ce0404f7c9](https://bsd-hardware.info/?probe=ce0404f7c9) | Aug 31, 2024 |
| Lenovo        | Yoga 900S-12ISK 80ML        | [a0abac7ab7](https://bsd-hardware.info/?probe=a0abac7ab7) | Aug 21, 2024 |
| Fujitsu       | LIFEBOOK U727               | [d3eb2cd128](https://bsd-hardware.info/?probe=d3eb2cd128) | Aug 14, 2024 |
| HP            | Pavilion 17                 | [ae76b7e522](https://bsd-hardware.info/?probe=ae76b7e522) | Aug 10, 2024 |
| HP            | EliteBook 840 G6            | [9ae98f134a](https://bsd-hardware.info/?probe=9ae98f134a) | Aug 09, 2024 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [3d93b160f7](https://bsd-hardware.info/?probe=3d93b160f7) | Jul 25, 2024 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [b671ec6c8d](https://bsd-hardware.info/?probe=b671ec6c8d) | Jul 21, 2024 |
| HP            | Compaq Presario CQ71        | [88a0868c03](https://bsd-hardware.info/?probe=88a0868c03) | Jul 18, 2024 |
| F-Plus Mob... | FLAPTOP r                   | [a82831432b](https://bsd-hardware.info/?probe=a82831432b) | Jun 25, 2024 |
| ASUSTek       | UX410UAR                    | [263af3de44](https://bsd-hardware.info/?probe=263af3de44) | May 23, 2024 |
| Dell          | Inspiron 1545               | [e123332fb8](https://bsd-hardware.info/?probe=e123332fb8) | May 16, 2024 |
| Dell          | Inspiron 1545               | [d5f43a27aa](https://bsd-hardware.info/?probe=d5f43a27aa) | May 12, 2024 |
| Dell          | Inspiron 1545               | [3c3432b2c0](https://bsd-hardware.info/?probe=3c3432b2c0) | May 11, 2024 |
| Infinix       | INBook X1                   | [847a9cb112](https://bsd-hardware.info/?probe=847a9cb112) | May 10, 2024 |
| Acer          | TravelMate B118-M           | [68d9d26fe5](https://bsd-hardware.info/?probe=68d9d26fe5) | May 09, 2024 |
| Alienware     | Area-51m A00                | [53d5d4eb1e](https://bsd-hardware.info/?probe=53d5d4eb1e) | May 07, 2024 |
| Unknown       | X133                        | [524b7e6d8e](https://bsd-hardware.info/?probe=524b7e6d8e) | May 07, 2024 |
| Dell          | XPS 13 9360                 | [c9ad91fc61](https://bsd-hardware.info/?probe=c9ad91fc61) | May 07, 2024 |
| Lenovo        | ThinkPad X240 20AMS3FY00    | [1dc74d60e6](https://bsd-hardware.info/?probe=1dc74d60e6) | May 06, 2024 |
| Dell          | Latitude 7390               | [b9b511f4d6](https://bsd-hardware.info/?probe=b9b511f4d6) | May 04, 2024 |
| MSI           | GE75 Raider 10SFS           | [cda74e2f91](https://bsd-hardware.info/?probe=cda74e2f91) | May 02, 2024 |
| ASUSTek       | X202E                       | [0ed385a36d](https://bsd-hardware.info/?probe=0ed385a36d) | May 02, 2024 |
| HP            | 255 G8 Notebook PC          | [4878c18c8a](https://bsd-hardware.info/?probe=4878c18c8a) | May 01, 2024 |
| Dell          | XPS 13 9360                 | [26185f189e](https://bsd-hardware.info/?probe=26185f189e) | Apr 30, 2024 |
| HP            | EliteBook 2560p             | [bb6303ed5b](https://bsd-hardware.info/?probe=bb6303ed5b) | Apr 29, 2024 |
| Lenovo        | ThinkPad X220 429135G       | [b681d0b406](https://bsd-hardware.info/?probe=b681d0b406) | Apr 23, 2024 |
| F-Plus Mob... | FLAPTOP r                   | [150e135ba6](https://bsd-hardware.info/?probe=150e135ba6) | Apr 18, 2024 |
| Dell          | Latitude 7490               | [38f6023f20](https://bsd-hardware.info/?probe=38f6023f20) | Apr 14, 2024 |
| Dell          | Vostro 3350                 | [abe739e6c2](https://bsd-hardware.info/?probe=abe739e6c2) | Apr 13, 2024 |
| HP            | ProBook 645 G3              | [ea10ac1f83](https://bsd-hardware.info/?probe=ea10ac1f83) | Apr 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [a26013b913](https://bsd-hardware.info/?probe=a26013b913) | Apr 05, 2024 |
| Dell          | Latitude E5540              | [108e2acb98](https://bsd-hardware.info/?probe=108e2acb98) | Apr 01, 2024 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [0ae72ec0ff](https://bsd-hardware.info/?probe=0ae72ec0ff) | Mar 31, 2024 |
| HP            | OMEN Laptop 15-ek0xxx       | [f4dde6ddf5](https://bsd-hardware.info/?probe=f4dde6ddf5) | Mar 22, 2024 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [db1d3cd098](https://bsd-hardware.info/?probe=db1d3cd098) | Mar 19, 2024 |
| Google        | Cave                        | [d9df48c781](https://bsd-hardware.info/?probe=d9df48c781) | Mar 16, 2024 |
| Dell          | XPS 13 9305                 | [7cc4588e07](https://bsd-hardware.info/?probe=7cc4588e07) | Mar 07, 2024 |
| HP            | Notebook                    | [15839305ee](https://bsd-hardware.info/?probe=15839305ee) | Mar 01, 2024 |
| Dell          | Inspiron 5559               | [ac72a9a34a](https://bsd-hardware.info/?probe=ac72a9a34a) | Feb 23, 2024 |
| Dell          | Latitude E6540              | [92ba9b26e1](https://bsd-hardware.info/?probe=92ba9b26e1) | Feb 21, 2024 |
| Dell          | Latitude 7490               | [32828d5d84](https://bsd-hardware.info/?probe=32828d5d84) | Feb 10, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [0e644c21cc](https://bsd-hardware.info/?probe=0e644c21cc) | Feb 02, 2024 |
| TUXEDO        | Aura 15 Gen1                | [4768e0001d](https://bsd-hardware.info/?probe=4768e0001d) | Feb 01, 2024 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [e747b9066e](https://bsd-hardware.info/?probe=e747b9066e) | Jan 29, 2024 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [7e24e6c0f2](https://bsd-hardware.info/?probe=7e24e6c0f2) | Jan 29, 2024 |
| ASUSTek       | X555LAB                     | [c396fcc8d9](https://bsd-hardware.info/?probe=c396fcc8d9) | Jan 22, 2024 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [d08f6339ae](https://bsd-hardware.info/?probe=d08f6339ae) | Jan 12, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | [2ab7b9d6b2](https://bsd-hardware.info/?probe=2ab7b9d6b2) | Jan 02, 2024 |
| HP            | EliteBook 2540p             | [c915c03729](https://bsd-hardware.info/?probe=c915c03729) | Dec 30, 2023 |
| Lenovo        | ThinkPad T480 20L6S8LW00    | [b6c3c05155](https://bsd-hardware.info/?probe=b6c3c05155) | Dec 25, 2023 |
| Lenovo        | ThinkPad T480 20L6S8LW00    | [32c06c5669](https://bsd-hardware.info/?probe=32c06c5669) | Dec 23, 2023 |
| Apple         | MacBookPro9,2               | [851f118bd5](https://bsd-hardware.info/?probe=851f118bd5) | Dec 19, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [5281bb9e20](https://bsd-hardware.info/?probe=5281bb9e20) | Dec 19, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [d81a233601](https://bsd-hardware.info/?probe=d81a233601) | Dec 12, 2023 |
| Dell          | Inspiron 5559               | [09f5b25e72](https://bsd-hardware.info/?probe=09f5b25e72) | Dec 12, 2023 |
| Dell          | Latitude E6330              | [7e0a01e9ad](https://bsd-hardware.info/?probe=7e0a01e9ad) | Dec 05, 2023 |
| Dell          | Inspiron 7558               | [b34a8742d5](https://bsd-hardware.info/?probe=b34a8742d5) | Nov 26, 2023 |
| Dell          | Inspiron 7558               | [aad8d359f3](https://bsd-hardware.info/?probe=aad8d359f3) | Nov 24, 2023 |
| Dell          | Latitude E5440              | [629fba28cc](https://bsd-hardware.info/?probe=629fba28cc) | Nov 23, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [19dfa9e36a](https://bsd-hardware.info/?probe=19dfa9e36a) | Nov 21, 2023 |
| Dell          | Precision 5520              | [45f5e399a4](https://bsd-hardware.info/?probe=45f5e399a4) | Nov 18, 2023 |
| HP            | Notebook                    | [c583c221c7](https://bsd-hardware.info/?probe=c583c221c7) | Nov 17, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [0fd2711a56](https://bsd-hardware.info/?probe=0fd2711a56) | Nov 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [d87ea88953](https://bsd-hardware.info/?probe=d87ea88953) | Nov 09, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [05bf5fb9f4](https://bsd-hardware.info/?probe=05bf5fb9f4) | Nov 07, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [19514dd0bd](https://bsd-hardware.info/?probe=19514dd0bd) | Nov 03, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [965e71ac80](https://bsd-hardware.info/?probe=965e71ac80) | Oct 21, 2023 |
| Dell          | Latitude 5490               | [eeab525ffd](https://bsd-hardware.info/?probe=eeab525ffd) | Oct 20, 2023 |
| ASUSTek       | N552VX                      | [f927cf5ba4](https://bsd-hardware.info/?probe=f927cf5ba4) | Oct 16, 2023 |
| Fujitsu       | LIFEBOOK E744               | [72a9b731f6](https://bsd-hardware.info/?probe=72a9b731f6) | Oct 14, 2023 |
| Lenovo        | ThinkPad T410 2518C3U       | [36daf066ca](https://bsd-hardware.info/?probe=36daf066ca) | Oct 08, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2AD0... | [ac6742bd0f](https://bsd-hardware.info/?probe=ac6742bd0f) | Oct 07, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2AD0... | [3e15173331](https://bsd-hardware.info/?probe=3e15173331) | Oct 07, 2023 |
| Apple         | MacBookPro7,1               | [070c5dab4f](https://bsd-hardware.info/?probe=070c5dab4f) | Oct 02, 2023 |
| ASUSTek       | K40IN                       | [6b58792f5e](https://bsd-hardware.info/?probe=6b58792f5e) | Oct 02, 2023 |
| Acer          | TravelMate 5730             | [dffc2e116d](https://bsd-hardware.info/?probe=dffc2e116d) | Sep 30, 2023 |
| Apple         | MacBookPro9,1               | [b0aca42c84](https://bsd-hardware.info/?probe=b0aca42c84) | Sep 29, 2023 |
| MSI           | CX62 6QD                    | [68b8b9f531](https://bsd-hardware.info/?probe=68b8b9f531) | Sep 29, 2023 |
| TUXEDO        | Aura 15 Gen1                | [b31f8c12f8](https://bsd-hardware.info/?probe=b31f8c12f8) | Sep 24, 2023 |
| Lenovo        | ThinkPad T470 20HES0HU00    | [a64fe205a9](https://bsd-hardware.info/?probe=a64fe205a9) | Sep 17, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [0f92b89ffb](https://bsd-hardware.info/?probe=0f92b89ffb) | Sep 09, 2023 |
| Dell          | Inspiron 15-7568            | [9e555f0b24](https://bsd-hardware.info/?probe=9e555f0b24) | Aug 24, 2023 |
| Dell          | Latitude 7490               | [0b05de2297](https://bsd-hardware.info/?probe=0b05de2297) | Aug 24, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [26995b5321](https://bsd-hardware.info/?probe=26995b5321) | Aug 19, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [1bc7f67754](https://bsd-hardware.info/?probe=1bc7f67754) | Aug 18, 2023 |
| Samsung       | Q210                        | [2e25c6d2ec](https://bsd-hardware.info/?probe=2e25c6d2ec) | Aug 03, 2023 |
| Samsung       | Q210                        | [d3c5ab902d](https://bsd-hardware.info/?probe=d3c5ab902d) | Aug 03, 2023 |
| ASUSTek       | X555LD                      | [9c0c41b663](https://bsd-hardware.info/?probe=9c0c41b663) | Jul 30, 2023 |
| Dell          | Inspiron 3180               | [e97b5d9219](https://bsd-hardware.info/?probe=e97b5d9219) | Jul 25, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [020e17c2f8](https://bsd-hardware.info/?probe=020e17c2f8) | Jul 23, 2023 |
| Toshiba       | Satellite L655              | [67080aeb1d](https://bsd-hardware.info/?probe=67080aeb1d) | Jul 20, 2023 |
| MSI           | Sword 17 A11UD              | [c9852c1ee3](https://bsd-hardware.info/?probe=c9852c1ee3) | Jul 19, 2023 |
| Lenovo        | ThinkPad W530 2447GW3       | [57b4bfc1bf](https://bsd-hardware.info/?probe=57b4bfc1bf) | Jul 17, 2023 |
| Lenovo        | ThinkPad X395 20NLCTO1WW    | [826ba238d8](https://bsd-hardware.info/?probe=826ba238d8) | Jul 16, 2023 |
| Lenovo        | ThinkPad X395 20NLCTO1WW    | [0273f2f271](https://bsd-hardware.info/?probe=0273f2f271) | Jul 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [03e83e60ca](https://bsd-hardware.info/?probe=03e83e60ca) | Jul 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [3096d8532a](https://bsd-hardware.info/?probe=3096d8532a) | Jul 07, 2023 |
| Dell          | G3 3579                     | [8d9b29f231](https://bsd-hardware.info/?probe=8d9b29f231) | Jul 05, 2023 |
| Dell          | G3 3579                     | [f6fc15b1f4](https://bsd-hardware.info/?probe=f6fc15b1f4) | Jul 05, 2023 |
| HP            | 15                          | [4664b4c93f](https://bsd-hardware.info/?probe=4664b4c93f) | Jun 11, 2023 |
| Dell          | Inspiron 3180               | [cb769078b4](https://bsd-hardware.info/?probe=cb769078b4) | Jun 10, 2023 |
| Dell          | Inspiron 5593               | [8bedc249ea](https://bsd-hardware.info/?probe=8bedc249ea) | Jun 10, 2023 |
| Dell          | Inspiron 7548               | [c80bb80e8f](https://bsd-hardware.info/?probe=c80bb80e8f) | Jun 10, 2023 |
| Dell          | Inspiron 5559               | [fe5f99c4b0](https://bsd-hardware.info/?probe=fe5f99c4b0) | Jun 06, 2023 |
| Dell          | Inspiron 5559               | [330c08c388](https://bsd-hardware.info/?probe=330c08c388) | Jun 01, 2023 |
| Dell          | Inspiron 5559               | [53cf3cea13](https://bsd-hardware.info/?probe=53cf3cea13) | Jun 01, 2023 |
| Dell          | Inspiron 5559               | [23cad3f06e](https://bsd-hardware.info/?probe=23cad3f06e) | May 28, 2023 |
| Acer          | Nitro AN515-57              | [c39ea00de5](https://bsd-hardware.info/?probe=c39ea00de5) | May 25, 2023 |
| HP            | ProBook 455 G3              | [b6a6c91115](https://bsd-hardware.info/?probe=b6a6c91115) | May 21, 2023 |
| Lenovo        | ThinkPad 11e 20DAS0S300     | [44d30cfcf6](https://bsd-hardware.info/?probe=44d30cfcf6) | May 21, 2023 |
| Dell          | Inspiron 5559               | [dca662fc41](https://bsd-hardware.info/?probe=dca662fc41) | May 16, 2023 |
| MSI           | GE62 6QC                    | [7c3fd3c9ca](https://bsd-hardware.info/?probe=7c3fd3c9ca) | May 08, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [95695f78c5](https://bsd-hardware.info/?probe=95695f78c5) | May 08, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [692b42afcd](https://bsd-hardware.info/?probe=692b42afcd) | Apr 08, 2023 |
| Dell          | Inspiron 5547               | [4f4f6e06d7](https://bsd-hardware.info/?probe=4f4f6e06d7) | Mar 29, 2023 |
| Unknown       | Unknown                     | [2a50573c9f](https://bsd-hardware.info/?probe=2a50573c9f) | Mar 29, 2023 |
| MouseCompu... | X5-aR5CEZAR-WA              | [b960dc3bde](https://bsd-hardware.info/?probe=b960dc3bde) | Mar 25, 2023 |
| MouseCompu... | X5-aR5CEZAR-WA              | [4cd1097c65](https://bsd-hardware.info/?probe=4cd1097c65) | Mar 24, 2023 |
| Dell          | Inspiron 5559               | [705ac0b37f](https://bsd-hardware.info/?probe=705ac0b37f) | Mar 18, 2023 |
| Dell          | Inspiron 5559               | [dcab531d1e](https://bsd-hardware.info/?probe=dcab531d1e) | Mar 18, 2023 |
| Star Labs     | StarBook                    | [80f6445f54](https://bsd-hardware.info/?probe=80f6445f54) | Mar 10, 2023 |
| Fujitsu       | FMVA532BSJ                  | [695e38d0ea](https://bsd-hardware.info/?probe=695e38d0ea) | Mar 10, 2023 |
| Lenovo        | ThinkPad T430 2349S31       | [2b13f68cd6](https://bsd-hardware.info/?probe=2b13f68cd6) | Feb 28, 2023 |
| Lenovo        | ThinkPad T460 20FMS06V00    | [7d7fa2bbc9](https://bsd-hardware.info/?probe=7d7fa2bbc9) | Feb 22, 2023 |
| Lenovo        | ThinkPad T460 20FMS3320G    | [c85f94d574](https://bsd-hardware.info/?probe=c85f94d574) | Feb 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [a9928bd16e](https://bsd-hardware.info/?probe=a9928bd16e) | Feb 10, 2023 |
| HP            | 650                         | [48099613ec](https://bsd-hardware.info/?probe=48099613ec) | Feb 05, 2023 |
| Lenovo        | ThinkPad P50 20EN0008GE     | [8cb09e34ec](https://bsd-hardware.info/?probe=8cb09e34ec) | Feb 04, 2023 |
| TUXEDO        | Aura 15 Gen1                | [e6ad419f5e](https://bsd-hardware.info/?probe=e6ad419f5e) | Jan 20, 2023 |
| Lenovo        | B50-80 80EW                 | [fa42e2faf7](https://bsd-hardware.info/?probe=fa42e2faf7) | Jan 20, 2023 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [32207ea5d9](https://bsd-hardware.info/?probe=32207ea5d9) | Dec 19, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | [3a9623cfb4](https://bsd-hardware.info/?probe=3a9623cfb4) | Dec 16, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | [0314add226](https://bsd-hardware.info/?probe=0314add226) | Dec 16, 2022 |
| Lenovo        | B50-80 80EW                 | [9551c57fc3](https://bsd-hardware.info/?probe=9551c57fc3) | Dec 14, 2022 |
| Apple         | MacBookPro14,1              | [ddeb9befdf](https://bsd-hardware.info/?probe=ddeb9befdf) | Dec 03, 2022 |
| HP            | Laptop 14s-fq0xxx           | [920a2fe2e9](https://bsd-hardware.info/?probe=920a2fe2e9) | Nov 30, 2022 |
| HP            | Laptop 14s-fq0xxx           | [9618eb0cbe](https://bsd-hardware.info/?probe=9618eb0cbe) | Nov 29, 2022 |
| Acer          | Aspire 5251                 | [c9eb0051ed](https://bsd-hardware.info/?probe=c9eb0051ed) | Nov 16, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [45316a9769](https://bsd-hardware.info/?probe=45316a9769) | Nov 07, 2022 |
| HP            | Laptop 15-da0xxx            | [72d95a4938](https://bsd-hardware.info/?probe=72d95a4938) | Nov 03, 2022 |
| Dell          | Latitude 5591               | [40957fa567](https://bsd-hardware.info/?probe=40957fa567) | Oct 31, 2022 |
| Acer          | Aspire E1-570               | [3d62c50607](https://bsd-hardware.info/?probe=3d62c50607) | Oct 20, 2022 |
| Dell          | Latitude 5591               | [04f53f51c8](https://bsd-hardware.info/?probe=04f53f51c8) | Oct 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | [a773a82ff4](https://bsd-hardware.info/?probe=a773a82ff4) | Oct 11, 2022 |
| Dell          | Latitude 5591               | [eda94b6c48](https://bsd-hardware.info/?probe=eda94b6c48) | Oct 11, 2022 |
| Dell          | XPS M1330                   | [d84548dd9b](https://bsd-hardware.info/?probe=d84548dd9b) | Sep 11, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [4f31f81571](https://bsd-hardware.info/?probe=4f31f81571) | Sep 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [fc259fcf3e](https://bsd-hardware.info/?probe=fc259fcf3e) | Aug 30, 2022 |
| HP            | Unknown                     | [7bd69ee984](https://bsd-hardware.info/?probe=7bd69ee984) | Aug 29, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [692e2f0837](https://bsd-hardware.info/?probe=692e2f0837) | Aug 20, 2022 |
| Lenovo        | ThinkPad 11e 4th Gen 20H... | [ba1ea734b1](https://bsd-hardware.info/?probe=ba1ea734b1) | Aug 19, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [c9bda4b49d](https://bsd-hardware.info/?probe=c9bda4b49d) | Aug 14, 2022 |
| Dell          | Inspiron 1545               | [e1a29d8008](https://bsd-hardware.info/?probe=e1a29d8008) | Aug 14, 2022 |
| Dell          | Inspiron 15-3567            | [cdc6bc6ef8](https://bsd-hardware.info/?probe=cdc6bc6ef8) | Aug 03, 2022 |
| Acer          | Aspire E5-521G              | [dcc5d3116f](https://bsd-hardware.info/?probe=dcc5d3116f) | Jul 29, 2022 |
| Lenovo        | IdeaPad Y580 20132          | [3df3bd2f62](https://bsd-hardware.info/?probe=3df3bd2f62) | Jul 22, 2022 |
| Dell          | Inspiron 15-3567            | [15c5d9fdd9](https://bsd-hardware.info/?probe=15c5d9fdd9) | Jul 17, 2022 |
| Dell          | Inspiron 3505               | [ead2595782](https://bsd-hardware.info/?probe=ead2595782) | Jul 17, 2022 |
| Dell          | XPS 13 7390                 | [d9efb0425b](https://bsd-hardware.info/?probe=d9efb0425b) | Jul 15, 2022 |
| Dell          | XPS 13 7390                 | [6e85a064f0](https://bsd-hardware.info/?probe=6e85a064f0) | Jul 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [b09ba0c799](https://bsd-hardware.info/?probe=b09ba0c799) | Jul 12, 2022 |
| HP            | Laptop 15-da0xxx            | [0434c94fad](https://bsd-hardware.info/?probe=0434c94fad) | Jul 09, 2022 |
| Lenovo        | ThinkPad T470 20HD000MUK    | [866724656a](https://bsd-hardware.info/?probe=866724656a) | Jul 06, 2022 |
| Star Labs     | LabTop                      | [390c4c4d55](https://bsd-hardware.info/?probe=390c4c4d55) | Jul 03, 2022 |
| Dell          | XPS 13 7390                 | [3c2e2da462](https://bsd-hardware.info/?probe=3c2e2da462) | Jul 02, 2022 |
| Dell          | XPS 13 7390                 | [b870cd3698](https://bsd-hardware.info/?probe=b870cd3698) | Jul 01, 2022 |
| System76      | Gazelle                     | [7e2dbb0a5b](https://bsd-hardware.info/?probe=7e2dbb0a5b) | Jun 28, 2022 |
| System76      | Gazelle                     | [8cb2a30786](https://bsd-hardware.info/?probe=8cb2a30786) | Jun 28, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [bb3de13b1a](https://bsd-hardware.info/?probe=bb3de13b1a) | Jun 23, 2022 |
| ASUSTek       | X202E                       | [bdbe613858](https://bsd-hardware.info/?probe=bdbe613858) | Jun 22, 2022 |
| HP            | EliteBook 830 G5            | [03cb6c6c7f](https://bsd-hardware.info/?probe=03cb6c6c7f) | Jun 09, 2022 |
| Dell          | Latitude 7490               | [22224f46f4](https://bsd-hardware.info/?probe=22224f46f4) | Jun 02, 2022 |
| TUXEDO        | Aura 15 Gen1                | [115de395dd](https://bsd-hardware.info/?probe=115de395dd) | May 17, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [d2334d7be3](https://bsd-hardware.info/?probe=d2334d7be3) | May 14, 2022 |
| Acer          | Aspire A715-42G             | [6dce802641](https://bsd-hardware.info/?probe=6dce802641) | May 10, 2022 |
| Dell          | Latitude 7490               | [0d5b872ec1](https://bsd-hardware.info/?probe=0d5b872ec1) | May 02, 2022 |
| Dell          | Latitude 7490               | [03c97fe4d9](https://bsd-hardware.info/?probe=03c97fe4d9) | May 02, 2022 |
| Dell          | Precision 7730              | [bdb3e3d4ce](https://bsd-hardware.info/?probe=bdb3e3d4ce) | Apr 30, 2022 |
| Dell          | Latitude 7490               | [1586880dd7](https://bsd-hardware.info/?probe=1586880dd7) | Apr 30, 2022 |
| ASUSTek       | X550CC                      | [ece6d63cfb](https://bsd-hardware.info/?probe=ece6d63cfb) | Apr 25, 2022 |
| Dell          | Latitude E5450              | [ca5eb083f9](https://bsd-hardware.info/?probe=ca5eb083f9) | Apr 16, 2022 |
| Notebook      | N13xWU                      | [8986953acd](https://bsd-hardware.info/?probe=8986953acd) | Mar 22, 2022 |
| Notebook      | N7x0WU                      | [b80f84aef1](https://bsd-hardware.info/?probe=b80f84aef1) | Mar 22, 2022 |
| Notebook      | N8xEJEK                     | [9a62677ea8](https://bsd-hardware.info/?probe=9a62677ea8) | Mar 22, 2022 |
| Dell          | Latitude E6500              | [5fad69bbf0](https://bsd-hardware.info/?probe=5fad69bbf0) | Mar 22, 2022 |
| Dell          | Latitude E6510              | [a040a1a04b](https://bsd-hardware.info/?probe=a040a1a04b) | Mar 22, 2022 |
| Dell          | Latitude E6530              | [9bc5fc70a7](https://bsd-hardware.info/?probe=9bc5fc70a7) | Mar 22, 2022 |
| Lenovo        | ThinkPad X201 32492EU       | [4a5ba4f3e4](https://bsd-hardware.info/?probe=4a5ba4f3e4) | Mar 13, 2022 |
| Lenovo        | ThinkPad T450 20BUS0VH08    | [bc2860431e](https://bsd-hardware.info/?probe=bc2860431e) | Feb 17, 2022 |
| Jumper        | EZbook                      | [35869ff0db](https://bsd-hardware.info/?probe=35869ff0db) | Feb 14, 2022 |
| Lenovo        | G500s 20245                 | [41f9f804ac](https://bsd-hardware.info/?probe=41f9f804ac) | Feb 04, 2022 |
| Dell          | Vostro 3550                 | [0b290f2ac3](https://bsd-hardware.info/?probe=0b290f2ac3) | Feb 02, 2022 |
| MSI           | GE75 Raider 10SFS           | [48b172bfe8](https://bsd-hardware.info/?probe=48b172bfe8) | Jan 25, 2022 |
| MSI           | GF63 Thin 10SCSR            | [5b9c617dc8](https://bsd-hardware.info/?probe=5b9c617dc8) | Jan 22, 2022 |
| Apple         | MacBookPro11,4              | [6d580e8270](https://bsd-hardware.info/?probe=6d580e8270) | Jan 21, 2022 |
| Dell          | Latitude E6540              | [f13972c935](https://bsd-hardware.info/?probe=f13972c935) | Jan 21, 2022 |
| Fujitsu       | CELSIUS H780                | [a173366c78](https://bsd-hardware.info/?probe=a173366c78) | Jan 21, 2022 |
| Jumper        | EZbook                      | [7d648bcdc7](https://bsd-hardware.info/?probe=7d648bcdc7) | Jan 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [cf360a6098](https://bsd-hardware.info/?probe=cf360a6098) | Jan 16, 2022 |
| Acer          | Extensa 5635Z               | [d76873c5dd](https://bsd-hardware.info/?probe=d76873c5dd) | Jan 16, 2022 |
| HP            | Laptop 15-dw2xxx            | [a6d7796cea](https://bsd-hardware.info/?probe=a6d7796cea) | Jan 13, 2022 |
| Dell          | Latitude 5510               | [a620d284cb](https://bsd-hardware.info/?probe=a620d284cb) | Jan 12, 2022 |
| Dell          | Inspiron N5110              | [19be37f181](https://bsd-hardware.info/?probe=19be37f181) | Jan 09, 2022 |
| Dell          | Latitude E5450              | [c2ef231757](https://bsd-hardware.info/?probe=c2ef231757) | Jan 04, 2022 |
| ASUSTek       | TUF GAMING FX504GD_FX80G... | [259b5cc7b2](https://bsd-hardware.info/?probe=259b5cc7b2) | Dec 28, 2021 |
| ASUSTek       | X202E                       | [7f4e6f4541](https://bsd-hardware.info/?probe=7f4e6f4541) | Dec 05, 2021 |
| Fujitsu       | LIFEBOOK A555               | [c501c5c75e](https://bsd-hardware.info/?probe=c501c5c75e) | Dec 04, 2021 |
| Samsung       | 530XBB                      | [41d5f95889](https://bsd-hardware.info/?probe=41d5f95889) | Dec 03, 2021 |
| Alienware     | m15 R4                      | [a724a7d7c7](https://bsd-hardware.info/?probe=a724a7d7c7) | Nov 29, 2021 |
| Lenovo        | ThinkPad T520 4243E51       | [82f5612822](https://bsd-hardware.info/?probe=82f5612822) | Nov 29, 2021 |
| Sony          | SVP13225SCBI                | [03ef84679c](https://bsd-hardware.info/?probe=03ef84679c) | Nov 27, 2021 |
| Dell          | Latitude 5510               | [3da78c9445](https://bsd-hardware.info/?probe=3da78c9445) | Nov 24, 2021 |
| Acer          | TravelMate B117-M           | [4f02660d9c](https://bsd-hardware.info/?probe=4f02660d9c) | Nov 14, 2021 |
| Toshiba       | Satellite C855-1U4          | [4107fc9eee](https://bsd-hardware.info/?probe=4107fc9eee) | Nov 14, 2021 |
| Dell          | Latitude D630               | [7e3a92badc](https://bsd-hardware.info/?probe=7e3a92badc) | Nov 02, 2021 |
| HP            | EliteBook Folio 1040 G3     | [d23636abb2](https://bsd-hardware.info/?probe=d23636abb2) | Oct 31, 2021 |
| Samsung       | 550P5C/550P7C               | [69fe175fb8](https://bsd-hardware.info/?probe=69fe175fb8) | Oct 30, 2021 |
| HP            | Pavilion g6                 | [9754bc2e72](https://bsd-hardware.info/?probe=9754bc2e72) | Oct 27, 2021 |
| MSI           | Modern 14 A10M              | [84838cd532](https://bsd-hardware.info/?probe=84838cd532) | Oct 07, 2021 |
| MSI           | Modern 14 A10M              | [db33045561](https://bsd-hardware.info/?probe=db33045561) | Oct 07, 2021 |
| Acer          | Aspire A315-56              | [03ca802f4b](https://bsd-hardware.info/?probe=03ca802f4b) | Oct 02, 2021 |
| MSI           | Modern 14 A10M              | [277d8118da](https://bsd-hardware.info/?probe=277d8118da) | Sep 30, 2021 |
| Lenovo        | Flex 2-15 20405             | [76ea6529ac](https://bsd-hardware.info/?probe=76ea6529ac) | Sep 26, 2021 |
| MSI           | Modern 14 A10M              | [103ccaf452](https://bsd-hardware.info/?probe=103ccaf452) | Sep 25, 2021 |
| Lenovo        | ThinkPad X220 4290W42       | [8be5183e21](https://bsd-hardware.info/?probe=8be5183e21) | Sep 25, 2021 |
| Lenovo        | ThinkPad T500 2056Y2Z       | [88b86ecf8b](https://bsd-hardware.info/?probe=88b86ecf8b) | Sep 25, 2021 |
| HUAWEI        | HLY-WX9XX                   | [bd5b726e52](https://bsd-hardware.info/?probe=bd5b726e52) | Sep 19, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [2a54a0c338](https://bsd-hardware.info/?probe=2a54a0c338) | Sep 14, 2021 |
| Lenovo        | ThinkPad T400 6474E18       | [2dd5b5869f](https://bsd-hardware.info/?probe=2dd5b5869f) | Sep 13, 2021 |
| HP            | EliteBook 8570p             | [27f01061f2](https://bsd-hardware.info/?probe=27f01061f2) | Sep 12, 2021 |
| Lenovo        | ThinkPad X250 20CL001GZA    | [ecd69774c0](https://bsd-hardware.info/?probe=ecd69774c0) | Sep 06, 2021 |
| System76      | Kudu                        | [c10fc12e40](https://bsd-hardware.info/?probe=c10fc12e40) | Sep 05, 2021 |
| Acer          | Aspire 5750                 | [2bc72bf29e](https://bsd-hardware.info/?probe=2bc72bf29e) | Aug 23, 2021 |
| Dell          | Latitude E5440              | [3f2e8586a7](https://bsd-hardware.info/?probe=3f2e8586a7) | Aug 05, 2021 |
| Dell          | Latitude E6430              | [4149fa5ec3](https://bsd-hardware.info/?probe=4149fa5ec3) | Aug 04, 2021 |
| Lenovo        | Legion Y7000P 81LD          | [7364ae3b3d](https://bsd-hardware.info/?probe=7364ae3b3d) | Aug 04, 2021 |
| Lenovo        | ThinkPad L512 44444XG       | [a6c8fbcb20](https://bsd-hardware.info/?probe=a6c8fbcb20) | Aug 01, 2021 |
| GPU Compan... | GWTN156-5                   | [bc44d767cc](https://bsd-hardware.info/?probe=bc44d767cc) | Jul 22, 2021 |
| Dell          | Latitude E5520              | [e0dd26220f](https://bsd-hardware.info/?probe=e0dd26220f) | Jul 21, 2021 |
| Apple         | MacBook5,1                  | [1e54d2fbdf](https://bsd-hardware.info/?probe=1e54d2fbdf) | Jul 05, 2021 |
| Apple         | MacBook5,1                  | [f5d7a16498](https://bsd-hardware.info/?probe=f5d7a16498) | Jul 05, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [668bf95221](https://bsd-hardware.info/?probe=668bf95221) | Jun 25, 2021 |
| Dell          | Latitude E6420              | [2e8b431cc6](https://bsd-hardware.info/?probe=2e8b431cc6) | Jun 25, 2021 |
| Lenovo        | ThinkPad T440 20B7S1860W    | [8552205176](https://bsd-hardware.info/?probe=8552205176) | Jun 22, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [9f82e215c3](https://bsd-hardware.info/?probe=9f82e215c3) | Jun 22, 2021 |
| Dell          | Inspiron 3542               | [a2deab0991](https://bsd-hardware.info/?probe=a2deab0991) | Jun 15, 2021 |
| Sony          | SVP1322M1EBI                | [23316d0f2b](https://bsd-hardware.info/?probe=23316d0f2b) | May 29, 2021 |
| Lenovo        | ThinkPad T470 20HD000MUK    | [e27342ab94](https://bsd-hardware.info/?probe=e27342ab94) | May 13, 2021 |
| Lenovo        | ThinkPad X250 20CM003WMS    | [11fe52be5e](https://bsd-hardware.info/?probe=11fe52be5e) | May 13, 2021 |
| Lenovo        | ThinkPad T430 2344C4U       | [0f001f65d2](https://bsd-hardware.info/?probe=0f001f65d2) | Apr 27, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | [f8389b0546](https://bsd-hardware.info/?probe=f8389b0546) | Apr 24, 2021 |
| HP            | Laptop 15-da0xxx            | [cb09a1b771](https://bsd-hardware.info/?probe=cb09a1b771) | Apr 08, 2021 |
| Apple         | MacBookPro8,1               | [e4e3731289](https://bsd-hardware.info/?probe=e4e3731289) | Apr 01, 2021 |
| Acer          | Aspire E5-521G              | [e2b6dbfe40](https://bsd-hardware.info/?probe=e2b6dbfe40) | Apr 01, 2021 |
| HP            | 255 G7 Notebook PC          | [3e500c12a3](https://bsd-hardware.info/?probe=3e500c12a3) | Mar 24, 2021 |
| Lenovo        | ThinkPad X250 20CM003WMS    | [196cd8a730](https://bsd-hardware.info/?probe=196cd8a730) | Mar 11, 2021 |
| Acer          | Aspire F5-573G              | [240171b234](https://bsd-hardware.info/?probe=240171b234) | Mar 08, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [9ede3128c5](https://bsd-hardware.info/?probe=9ede3128c5) | Mar 07, 2021 |
| HP            | Laptop 15-db0xxx            | [b1ee3da46f](https://bsd-hardware.info/?probe=b1ee3da46f) | Mar 06, 2021 |
| Apple         | MacBookPro5,5               | [50ac436475](https://bsd-hardware.info/?probe=50ac436475) | Mar 06, 2021 |
| Acer          | Extensa 5635Z               | [837c6f28b4](https://bsd-hardware.info/?probe=837c6f28b4) | Feb 19, 2021 |
| Lenovo        | ThinkPad T470 20HD000MUK    | [39c8cd6d0c](https://bsd-hardware.info/?probe=39c8cd6d0c) | Feb 08, 2021 |
| Apple         | MacBookPro5,5               | [254e518190](https://bsd-hardware.info/?probe=254e518190) | Feb 03, 2021 |
| Dell          | Latitude 5480               | [9b38a72dd4](https://bsd-hardware.info/?probe=9b38a72dd4) | Jan 26, 2021 |
| HP            | Laptop 17-ca1xxx            | [fb318623f3](https://bsd-hardware.info/?probe=fb318623f3) | Jan 23, 2021 |
| HP            | Laptop 17-ca1xxx            | [97a89d4eb0](https://bsd-hardware.info/?probe=97a89d4eb0) | Jan 23, 2021 |
| HP            | Laptop 17-ca1xxx            | [806c954739](https://bsd-hardware.info/?probe=806c954739) | Jan 23, 2021 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | [3d18f3f8a9](https://bsd-hardware.info/?probe=3d18f3f8a9) | Jan 23, 2021 |
| Dell          | Inspiron 3542               | [3c41c474ad](https://bsd-hardware.info/?probe=3c41c474ad) | Jan 16, 2021 |
| Lenovo        | ThinkPad X380 Yoga 20LJ0... | [9e58a182a8](https://bsd-hardware.info/?probe=9e58a182a8) | Jan 16, 2021 |
| HP            | OMEN by HP Laptop           | [14857eb6b7](https://bsd-hardware.info/?probe=14857eb6b7) | Jan 15, 2021 |
| ASUSTek       | X550LC                      | [f7c32488e9](https://bsd-hardware.info/?probe=f7c32488e9) | Jan 15, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | [06cbb5cd5f](https://bsd-hardware.info/?probe=06cbb5cd5f) | Jan 15, 2021 |
| Dell          | Latitude 5280               | [c9bfb73262](https://bsd-hardware.info/?probe=c9bfb73262) | Jan 15, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | [a395c023bf](https://bsd-hardware.info/?probe=a395c023bf) | Jan 10, 2021 |
| Dell          | Inspiron 5758               | [c096e37be5](https://bsd-hardware.info/?probe=c096e37be5) | Jan 03, 2021 |
| HP            | Laptop 14-dk0xxx            | [5cd8e23152](https://bsd-hardware.info/?probe=5cd8e23152) | Dec 26, 2020 |
| HP            | Laptop 14-dk0xxx            | [fdbd71db5e](https://bsd-hardware.info/?probe=fdbd71db5e) | Dec 26, 2020 |
| Lenovo        | Yoga 2 13 20344             | [c51c202b8d](https://bsd-hardware.info/?probe=c51c202b8d) | Dec 25, 2020 |
| Lenovo        | ThinkPad T450 20BV0064US    | [b397848c7e](https://bsd-hardware.info/?probe=b397848c7e) | Dec 16, 2020 |
| Toshiba       | Satellite C855              | [6bc78fc7fc](https://bsd-hardware.info/?probe=6bc78fc7fc) | Dec 16, 2020 |
| Panasonic     | CF-19AHNC8FN                | [04a42812bb](https://bsd-hardware.info/?probe=04a42812bb) | Dec 11, 2020 |
| Lenovo        | ThinkPad X220 42872VU       | [c843b5d271](https://bsd-hardware.info/?probe=c843b5d271) | Dec 10, 2020 |
| Lenovo        | ThinkPad X380 Yoga 20LJ0... | [a6b923675d](https://bsd-hardware.info/?probe=a6b923675d) | Dec 07, 2020 |
| Sony          | VPCCB17FG                   | [d8a67b4a30](https://bsd-hardware.info/?probe=d8a67b4a30) | Dec 06, 2020 |
| Sony          | VPCCB17FG                   | [7fc23a57bb](https://bsd-hardware.info/?probe=7fc23a57bb) | Nov 25, 2020 |
| Acer          | Aspire 7540                 | [65d215a03b](https://bsd-hardware.info/?probe=65d215a03b) | Nov 17, 2020 |
| Apple         | MacBook6,1                  | [64b1b1910c](https://bsd-hardware.info/?probe=64b1b1910c) | Nov 01, 2020 |
| Acer          | Aspire A315-42              | [1ac21e1660](https://bsd-hardware.info/?probe=1ac21e1660) | Oct 08, 2020 |
| Acer          | Aspire E1-532               | [10bff44534](https://bsd-hardware.info/?probe=10bff44534) | Oct 07, 2020 |
| HP            | Laptop 15-da0xxx            | [7faf1699d6](https://bsd-hardware.info/?probe=7faf1699d6) | Oct 04, 2020 |
| Lenovo        | ThinkPad T590 20N40016CD    | [1d9786ac9f](https://bsd-hardware.info/?probe=1d9786ac9f) | Aug 31, 2020 |
| Lenovo        | ThinkPad T590 20N40016CD    | [e505894bee](https://bsd-hardware.info/?probe=e505894bee) | Aug 29, 2020 |
| System76      | Lemur Pro                   | [0163d0f084](https://bsd-hardware.info/?probe=0163d0f084) | Aug 29, 2020 |
| Lenovo        | ThinkPad T430s 23539JM      | [facf6fa0f8](https://bsd-hardware.info/?probe=facf6fa0f8) | Aug 27, 2020 |
| ASUSTek       | K53SD                       | [975e9ccbe2](https://bsd-hardware.info/?probe=975e9ccbe2) | Aug 27, 2020 |
| Lenovo        | ThinkPad T530 239242U       | [7c8087322d](https://bsd-hardware.info/?probe=7c8087322d) | Aug 27, 2020 |
| Sony          | VGN-SZ3VWP_X                | [ace534d784](https://bsd-hardware.info/?probe=ace534d784) | Aug 10, 2020 |
| TUXEDO        | InfinityBook13V3            | [d508fb472b](https://bsd-hardware.info/?probe=d508fb472b) | Aug 10, 2020 |
| Dell          | Inspiron 3542               | [b89da90904](https://bsd-hardware.info/?probe=b89da90904) | Aug 01, 2020 |
| ASUSTek       | G750JS                      | [8214170523](https://bsd-hardware.info/?probe=8214170523) | Aug 01, 2020 |
| ASUSTek       | G750JS                      | [60b904f003](https://bsd-hardware.info/?probe=60b904f003) | Aug 01, 2020 |
| Dell          | Latitude E6420              | [324265fe3f](https://bsd-hardware.info/?probe=324265fe3f) | May 31, 2020 |
| Lenovo        | ThinkPad T430s 2352CTO      | [f4e8ffb5dc](https://bsd-hardware.info/?probe=f4e8ffb5dc) | May 27, 2020 |
| Lenovo        | ThinkPad T430s 2352CTO      | [59c5b6d6b9](https://bsd-hardware.info/?probe=59c5b6d6b9) | May 27, 2020 |
| Dell          | Precision M4700             | [a7761ee829](https://bsd-hardware.info/?probe=a7761ee829) | May 25, 2020 |
| Lenovo        | G570 20079                  | [6a1b7867f0](https://bsd-hardware.info/?probe=6a1b7867f0) | May 16, 2020 |
| Lenovo        | G570 20079                  | [25fd1154c0](https://bsd-hardware.info/?probe=25fd1154c0) | May 08, 2020 |
| Lenovo        | G570 20079                  | [0370bc0522](https://bsd-hardware.info/?probe=0370bc0522) | May 02, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| GhostBSD 20.04.02      | 59        | 17.56%  |
| GhostBSD 21.08.27      | 29        | 8.63%   |
| GhostBSD 24.01.1       | 25        | 7.44%   |
| GhostBSD 25.02-R14.3p2 | 23        | 6.85%   |
| GhostBSD 23.10.1       | 22        | 6.55%   |
| GhostBSD 24.10.1       | 20        | 5.95%   |
| GhostBSD 24.07.3       | 13        | 3.87%   |
| GhostBSD 22.01.12      | 13        | 3.87%   |
| GhostBSD 25.01-R14.2p1 | 12        | 3.57%   |
| GhostBSD 23.06.01      | 11        | 3.27%   |
| GhostBSD 22.06.18      | 11        | 3.27%   |
| GhostBSD 25.02-R14.3p4 | 8         | 2.38%   |
| GhostBSD 25.01-R14.2p3 | 8         | 2.38%   |
| GhostBSD 25.01-R14.2p2 | 6         | 1.79%   |
| GhostBSD 24.04.1       | 6         | 1.79%   |
| GhostBSD 23.02.02      | 6         | 1.79%   |
| GhostBSD 23.07.13      | 4         | 1.19%   |
| GhostBSD 24.07.1       | 3         | 0.89%   |
| GhostBSD 23.07.29      | 3         | 0.89%   |
| GhostBSD 23.06.05      | 3         | 0.89%   |
| GhostBSD 22.06.26      | 3         | 0.89%   |
| GhostBSD 23.09.16      | 2         | 0.6%    |
| GhostBSD 23.09.06      | 2         | 0.6%    |
| GhostBSD 23.07.20      | 2         | 0.6%    |
| GhostBSD 23.05.22      | 2         | 0.6%    |
| GhostBSD 23.04.23      | 2         | 0.6%    |
| GhostBSD 23.03.17      | 2         | 0.6%    |
| GhostBSD 22.11.22      | 2         | 0.6%    |
| GhostBSD 22.11.02      | 2         | 0.6%    |
| GhostBSD 22.08.23      | 2         | 0.6%    |
| GhostBSD 22.08.06      | 2         | 0.6%    |
| GhostBSD 22.07.16      | 2         | 0.6%    |
| GhostBSD 24.07.2       | 1         | 0.3%    |
| GhostBSD 23.10.09      | 1         | 0.3%    |
| GhostBSD 23.09.29      | 1         | 0.3%    |
| GhostBSD 23.07.04      | 1         | 0.3%    |
| GhostBSD 23.06.22      | 1         | 0.3%    |
| GhostBSD 23.05.18      | 1         | 0.3%    |
| GhostBSD 23.04.02      | 1         | 0.3%    |
| GhostBSD 23.01.13      | 1         | 0.3%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| GhostBSD | 307       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 307       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| MATE         | 246       | 78.59%  |
| XFCE         | 48        | 15.34%  |
| KDE5         | 9         | 2.88%   |
| KDE          | 2         | 0.64%   |
| Cinnamon     | 2         | 0.64%   |
| pekwm        | 1         | 0.32%   |
| i3           | 1         | 0.32%   |
| helloDesktop | 1         | 0.32%   |
| GNOME        | 1         | 0.32%   |
| dwm          | 1         | 0.32%   |
| Console      | 1         | 0.32%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 305       | 99.35%  |
| Wayland | 1         | 0.33%   |
| Console | 1         | 0.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 302       | 98.37%  |
| SDDM    | 4         | 1.3%    |
| Console | 1         | 0.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 139       | 43.71%  |
| C       | 103       | 32.39%  |
| Unknown | 18        | 5.66%   |
| de_DE   | 14        | 4.4%    |
| es_ES   | 11        | 3.46%   |
| ru_RU   | 6         | 1.89%   |
| pt_BR   | 5         | 1.57%   |
| en_GB   | 5         | 1.57%   |
| pl_PL   | 4         | 1.26%   |
| it_IT   | 3         | 0.94%   |
| sk_SK   | 2         | 0.63%   |
| fr_FR   | 2         | 0.63%   |
| zh_CN   | 1         | 0.31%   |
| sv_SE   | 1         | 0.31%   |
| pt_PT   | 1         | 0.31%   |
| nl_NL   | 1         | 0.31%   |
| en_NZ   | 1         | 0.31%   |
| el_GR   | 1         | 0.31%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 253       | 82.41%  |
| BIOS | 54        | 17.59%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Zfs  | 299       | 95.83%  |
| Ufs  | 13        | 4.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 302       | 98.37%  |
| MBR     | 3         | 0.98%   |
| Unknown | 2         | 0.65%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 100       | 32.57%  |
| Dell                | 64        | 20.85%  |
| Hewlett-Packard     | 38        | 12.38%  |
| ASUSTek Computer    | 21        | 6.84%   |
| Acer                | 17        | 5.54%   |
| Apple               | 10        | 3.26%   |
| MSI                 | 8         | 2.61%   |
| Toshiba             | 5         | 1.63%   |
| Notebook            | 5         | 1.63%   |
| Fujitsu             | 5         | 1.63%   |
| Sony                | 4         | 1.3%    |
| Samsung Electronics | 4         | 1.3%    |
| HUAWEI              | 4         | 1.3%    |
| System76            | 3         | 0.98%   |
| TUXEDO              | 2         | 0.65%   |
| Star Labs           | 2         | 0.65%   |
| F-Plus Mobile       | 2         | 0.65%   |
| Alienware           | 2         | 0.65%   |
| Unknown             | 2         | 0.65%   |
| TongFang            | 1         | 0.33%   |
| Panasonic           | 1         | 0.33%   |
| MouseComputer       | 1         | 0.33%   |
| Maibenben           | 1         | 0.33%   |
| Jumper              | 1         | 0.33%   |
| Infinix             | 1         | 0.33%   |
| GPU Company         | 1         | 0.33%   |
| Google              | 1         | 0.33%   |
| Dynabook            | 1         | 0.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 4         | 1.3%    |
| Dell XPS 13 9360                         | 3         | 0.98%   |
| Dell Latitude 7490                       | 3         | 0.98%   |
| Dell Inspiron 3542                       | 3         | 0.98%   |
| MSI Modern 14 A10M                       | 2         | 0.65%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS       | 2         | 0.65%   |
| Lenovo Yoga 900S-12ISK 80ML              | 2         | 0.65%   |
| Lenovo ThinkPad T430s 2352CTO            | 2         | 0.65%   |
| HP Notebook                              | 2         | 0.65%   |
| HP EliteBook Folio 9470m                 | 2         | 0.65%   |
| F-Plus Mobile FLAPTOP r                  | 2         | 0.65%   |
| Dell XPS 13 7390                         | 2         | 0.65%   |
| Dell Latitude E6540                      | 2         | 0.65%   |
| Dell Latitude E6420                      | 2         | 0.65%   |
| Dell Latitude E5440                      | 2         | 0.65%   |
| Dell Latitude 5520                       | 2         | 0.65%   |
| Dell G3 3579                             | 2         | 0.65%   |
| ASUS ZenBook UX325UA_UM325UA             | 2         | 0.65%   |
| ASUS X202E                               | 2         | 0.65%   |
| TUXEDO InfinityBook13V3                  | 1         | 0.33%   |
| TUXEDO Aura 15 Gen1                      | 1         | 0.33%   |
| Toshiba Satellite L655                   | 1         | 0.33%   |
| Toshiba Satellite L50-C                  | 1         | 0.33%   |
| Toshiba Satellite C855-1U4               | 1         | 0.33%   |
| Toshiba Satellite C855                   | 1         | 0.33%   |
| Toshiba Satellite C800D                  | 1         | 0.33%   |
| TongFang GX4HRXL                         | 1         | 0.33%   |
| System76 Lemur Pro                       | 1         | 0.33%   |
| System76 Kudu                            | 1         | 0.33%   |
| System76 Gazelle                         | 1         | 0.33%   |
| Star Labs StarBook                       | 1         | 0.33%   |
| Star Labs LabTop                         | 1         | 0.33%   |
| Sony VPCCB17FG                           | 1         | 0.33%   |
| Sony VGN-SZ3VWP_X                        | 1         | 0.33%   |
| Sony SVP1322M1EBI                        | 1         | 0.33%   |
| Sony SVP13225SCBI                        | 1         | 0.33%   |
| Samsung Q210                             | 1         | 0.33%   |
| Samsung 550P5C/550P7C                    | 1         | 0.33%   |
| Samsung 530XBB                           | 1         | 0.33%   |
| Samsung 3570R/370R/470R/450R/510R/4450RV | 1         | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 76        | 24.76%  |
| Dell Latitude           | 29        | 9.45%   |
| Dell Inspiron           | 18        | 5.86%   |
| Acer Aspire             | 12        | 3.91%   |
| HP EliteBook            | 11        | 3.58%   |
| Lenovo IdeaPad          | 9         | 2.93%   |
| Dell XPS                | 8         | 2.61%   |
| HP Laptop               | 6         | 1.95%   |
| Toshiba Satellite       | 5         | 1.63%   |
| Lenovo Yoga             | 5         | 1.63%   |
| Lenovo Legion           | 4         | 1.3%    |
| Dell Precision          | 4         | 1.3%    |
| ASUS VivoBook           | 4         | 1.3%    |
| Unknown                 | 4         | 1.3%    |
| HP ProBook              | 3         | 0.98%   |
| HP Pavilion             | 3         | 0.98%   |
| HP OMEN                 | 3         | 0.98%   |
| Fujitsu LIFEBOOK        | 3         | 0.98%   |
| Dell Vostro             | 3         | 0.98%   |
| Acer TravelMate         | 3         | 0.98%   |
| MSI Modern              | 2         | 0.65%   |
| HP Notebook             | 2         | 0.65%   |
| HP 255                  | 2         | 0.65%   |
| HP 250                  | 2         | 0.65%   |
| F-Plus Mobile FLAPTOP   | 2         | 0.65%   |
| Dell G3                 | 2         | 0.65%   |
| ASUS ZenBook            | 2         | 0.65%   |
| ASUS X202E              | 2         | 0.65%   |
| Apple MacBookPro9       | 2         | 0.65%   |
| Apple MacBookPro11      | 2         | 0.65%   |
| TUXEDO InfinityBook13V3 | 1         | 0.33%   |
| TUXEDO Aura             | 1         | 0.33%   |
| TongFang GX4HRXL        | 1         | 0.33%   |
| System76 Lemur          | 1         | 0.33%   |
| System76 Kudu           | 1         | 0.33%   |
| System76 Gazelle        | 1         | 0.33%   |
| Star Labs StarBook      | 1         | 0.33%   |
| Star Labs LabTop        | 1         | 0.33%   |
| Sony VPCCB17FG          | 1         | 0.33%   |
| Sony VGN-SZ3VWP         | 1         | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 43        | 14.01%  |
| 2021 | 27        | 8.79%   |
| 2022 | 26        | 8.47%   |
| 2013 | 26        | 8.47%   |
| 2018 | 24        | 7.82%   |
| 2019 | 19        | 6.19%   |
| 2016 | 19        | 6.19%   |
| 2014 | 17        | 5.54%   |
| 2015 | 16        | 5.21%   |
| 2012 | 15        | 4.89%   |
| 2011 | 15        | 4.89%   |
| 2023 | 14        | 4.56%   |
| 2017 | 13        | 4.23%   |
| 2024 | 9         | 2.93%   |
| 2009 | 8         | 2.61%   |
| 2010 | 7         | 2.28%   |
| 2008 | 6         | 1.95%   |
| 2025 | 2         | 0.65%   |
| 2007 | 1         | 0.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 307       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 303       | 98.7%   |
| Yes  | 4         | 1.3%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 138       | 44.66%  |
| 16.01-24.0  | 101       | 32.69%  |
| 4.01-8.0    | 42        | 13.59%  |
| 32.01-64.0  | 15        | 4.85%   |
| 24.01-32.0  | 8         | 2.59%   |
| 64.01-256.0 | 4         | 1.29%   |
| 2.01-3.0    | 1         | 0.32%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.51-1.0   | 130       | 41.67%  |
| 0.01-0.5   | 120       | 38.46%  |
| 1.01-2.0   | 35        | 11.22%  |
| 2.01-3.0   | 21        | 6.73%   |
| 4.01-8.0   | 5         | 1.6%    |
| 24.01-32.0 | 1         | 0.32%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 199       | 63.58%  |
| 0      | 67        | 21.41%  |
| 2      | 44        | 14.06%  |
| 3      | 3         | 0.96%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 219       | 70.87%  |
| Yes       | 90        | 29.13%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 246       | 79.87%  |
| No        | 62        | 20.13%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 305       | 99.35%  |
| No        | 2         | 0.65%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 247       | 80.46%  |
| No        | 60        | 19.54%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 68        | 22.08%  |
| Germany      | 36        | 11.69%  |
| UK           | 19        | 6.17%   |
| Spain        | 16        | 5.19%   |
| France       | 13        | 4.22%   |
| Russia       | 11        | 3.57%   |
| Poland       | 11        | 3.57%   |
| Canada       | 11        | 3.57%   |
| Italy        | 8         | 2.6%    |
| Switzerland  | 7         | 2.27%   |
| India        | 7         | 2.27%   |
| Indonesia    | 6         | 1.95%   |
| Bulgaria     | 6         | 1.95%   |
| Japan        | 5         | 1.62%   |
| Taiwan       | 4         | 1.3%    |
| Portugal     | 4         | 1.3%    |
| New Zealand  | 4         | 1.3%    |
| Finland      | 4         | 1.3%    |
| Brazil       | 4         | 1.3%    |
| Belgium      | 4         | 1.3%    |
| Sweden       | 3         | 0.97%   |
| Slovenia     | 3         | 0.97%   |
| Slovakia     | 3         | 0.97%   |
| Netherlands  | 3         | 0.97%   |
| China        | 3         | 0.97%   |
| Austria      | 3         | 0.97%   |
| Turkey       | 2         | 0.65%   |
| South Africa | 2         | 0.65%   |
| Philippines  | 2         | 0.65%   |
| Norway       | 2         | 0.65%   |
| Mauritius    | 2         | 0.65%   |
| Lithuania    | 2         | 0.65%   |
| Hungary      | 2         | 0.65%   |
| Hong Kong    | 2         | 0.65%   |
| Greece       | 2         | 0.65%   |
| Belarus      | 2         | 0.65%   |
| Australia    | 2         | 0.65%   |
| Argentina    | 2         | 0.65%   |
| Vietnam      | 1         | 0.32%   |
| Ukraine      | 1         | 0.32%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Zurich         | 6         | 1.87%   |
| Edgware        | 6         | 1.87%   |
| Bedburg        | 6         | 1.87%   |
| Sofia          | 4         | 1.25%   |
| Jakarta        | 4         | 1.25%   |
| Indian Trail   | 4         | 1.25%   |
| Saratov        | 3         | 0.93%   |
| Rome           | 3         | 0.93%   |
| Paris          | 3         | 0.93%   |
| New York       | 3         | 0.93%   |
| Madrid         | 3         | 0.93%   |
| Lebanon        | 3         | 0.93%   |
| Franconville   | 3         | 0.93%   |
| Cologne        | 3         | 0.93%   |
| Chrusty        | 3         | 0.93%   |
| Bonn           | 3         | 0.93%   |
| Bengaluru      | 3         | 0.93%   |
| Zaragoza       | 2         | 0.62%   |
| Yokohama       | 2         | 0.62%   |
| Winnipeg       | 2         | 0.62%   |
| Whittier       | 2         | 0.62%   |
| Wezeren        | 2         | 0.62%   |
| Valencia       | 2         | 0.62%   |
| Tomball        | 2         | 0.62%   |
| Taipei         | 2         | 0.62%   |
| Taichung       | 2         | 0.62%   |
| Stuttgart      | 2         | 0.62%   |
| Stiring-Wendel | 2         | 0.62%   |
| Skiatook       | 2         | 0.62%   |
| Roslindale     | 2         | 0.62%   |
| Oslo           | 2         | 0.62%   |
| Nuremberg      | 2         | 0.62%   |
| Novo Mesto     | 2         | 0.62%   |
| Moscow         | 2         | 0.62%   |
| Milan          | 2         | 0.62%   |
| London         | 2         | 0.62%   |
| Lisbon         | 2         | 0.62%   |
| Jarosław      | 2         | 0.62%   |
| Giessen        | 2         | 0.62%   |
| Cloppenburg    | 2         | 0.62%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 61        | 74     | 20.82%  |
| WDC                 | 34        | 36     | 11.6%   |
| Kingston            | 27        | 27     | 9.22%   |
| Toshiba             | 20        | 25     | 6.83%   |
| Seagate             | 20        | 24     | 6.83%   |
| Crucial             | 18        | 24     | 6.14%   |
| SK hynix            | 17        | 21     | 5.8%    |
| SanDisk             | 15        | 15     | 5.12%   |
| Intel               | 11        | 11     | 3.75%   |
| HGST                | 7         | 7      | 2.39%   |
| Hitachi             | 5         | 5      | 1.71%   |
| Apple               | 5         | 5      | 1.71%   |
| A-DATA Technology   | 5         | 5      | 1.71%   |
| Micron Technology   | 4         | 4      | 1.37%   |
| Transcend           | 3         | 3      | 1.02%   |
| Phison              | 3         | 4      | 1.02%   |
| Team                | 2         | 2      | 0.68%   |
| Star Drive          | 2         | 2      | 0.68%   |
| SSSTC               | 2         | 2      | 0.68%   |
| PNY                 | 2         | 2      | 0.68%   |
| Patriot             | 2         | 2      | 0.68%   |
| LITEONIT            | 2         | 2      | 0.68%   |
| KingSpec            | 2         | 2      | 0.68%   |
| GOODRAM             | 2         | 2      | 0.68%   |
| Fujitsu             | 2         | 2      | 0.68%   |
| China               | 2         | 2      | 0.68%   |
| XUM                 | 1         | 1      | 0.34%   |
| Verbatim            | 1         | 1      | 0.34%   |
| SPCC                | 1         | 1      | 0.34%   |
| Silicon Motion      | 1         | 1      | 0.34%   |
| ShiJi               | 1         | 1      | 0.34%   |
| Plextor             | 1         | 1      | 0.34%   |
| Netac               | 1         | 1      | 0.34%   |
| MidasForce          | 1         | 1      | 0.34%   |
| LITEON              | 1         | 1      | 0.34%   |
| Lexar               | 1         | 2      | 0.34%   |
| Intenso             | 1         | 1      | 0.34%   |
| Innodisk            | 1         | 1      | 0.34%   |
| Hewlett-Packard     | 1         | 1      | 0.34%   |
| Gigabyte Technology | 1         | 1      | 0.34%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB            | 6         | 2.01%   |
| Samsung SSD 870 EVO 500GB              | 4         | 1.34%   |
| Kingston SA400S37120G 120GB            | 4         | 1.34%   |
| WDC WDS500G2B0A-00SM50 500GB           | 3         | 1%      |
| WDC WD10JPVX-22JC3T0 1TB               | 3         | 1%      |
| SK hynix SKHynix_HFS512GDE9X081N 512GB | 3         | 1%      |
| Seagate ST1000LM035-1RK172 1TB         | 3         | 1%      |
| Samsung SSD 860 QVO 1TB                | 3         | 1%      |
| Samsung SSD 860 EVO 500GB              | 3         | 1%      |
| Samsung SSD 850 EVO 250GB              | 3         | 1%      |
| Toshiba MQ01ACF032 320GB               | 2         | 0.67%   |
| Toshiba MQ01ABF050 500GB               | 2         | 0.67%   |
| Toshiba KXG50ZNV512G NVMe 512GB        | 2         | 0.67%   |
| Toshiba KBG40ZNT512G MEMORY 512GB      | 2         | 0.67%   |
| Star Drive PCIe SSD 960GB              | 2         | 0.67%   |
| SK hynix SC311 SATA 512GB              | 2         | 0.67%   |
| SK hynix HFS256G39TND-N210A 256GB      | 2         | 0.67%   |
| SK hynix HFM512GD3JX013N 512GB         | 2         | 0.67%   |
| Seagate ST500LT012-9WS142 500GB        | 2         | 0.67%   |
| Seagate ST500LM021-1KJ152 500GB        | 2         | 0.67%   |
| Seagate ST1000LM049-2GH172 1TB         | 2         | 0.67%   |
| SanDisk SSD U100 16GB                  | 2         | 0.67%   |
| SanDisk SSD PLUS 1000GB                | 2         | 0.67%   |
| SanDisk SDSSDH3512G 512GB              | 2         | 0.67%   |
| Samsung SSD 860 PRO 512GB              | 2         | 0.67%   |
| Samsung SSD 860 EVO M.2 500GB          | 2         | 0.67%   |
| Samsung SSD 860 EVO 1TB                | 2         | 0.67%   |
| Samsung PM981 NVMe 256GB               | 2         | 0.67%   |
| Samsung MZNTE128HMGR-000SO 128GB       | 2         | 0.67%   |
| Kingston SV300S37A240G 240GB           | 2         | 0.67%   |
| Kingston SV300S37A120G 120GB           | 2         | 0.67%   |
| Kingston SA400S37960G 960GB            | 2         | 0.67%   |
| Kingston RBUSNS8154P3512GJ 512GB       | 2         | 0.67%   |
| KingSpec Q-720 720GB                   | 2         | 0.67%   |
| Intel SSDPEKNW512G8 512GB              | 2         | 0.67%   |
| Intel SSDPEKKF256G8L 256GB             | 2         | 0.67%   |
| Hitachi HTS541612J9SA00 120GB          | 2         | 0.67%   |
| HGST HTS545050A7E380 500GB             | 2         | 0.67%   |
| HGST HTS541010A9E680 1TB               | 2         | 0.67%   |
| Crucial CT480BX500SSD1 480GB           | 2         | 0.67%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 21        | 22     | 31.82%  |
| Seagate             | 20        | 24     | 30.3%   |
| Toshiba             | 8         | 8      | 12.12%  |
| HGST                | 7         | 7      | 10.61%  |
| Hitachi             | 5         | 5      | 7.58%   |
| Samsung Electronics | 2         | 2      | 3.03%   |
| Fujitsu             | 2         | 2      | 3.03%   |
| Apple               | 1         | 1      | 1.52%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 39        | 48     | 24.22%  |
| Kingston            | 23        | 23     | 14.29%  |
| Crucial             | 16        | 21     | 9.94%   |
| SanDisk             | 15        | 15     | 9.32%   |
| SK hynix            | 9         | 9      | 5.59%   |
| WDC                 | 7         | 7      | 4.35%   |
| Toshiba             | 5         | 7      | 3.11%   |
| Intel               | 5         | 5      | 3.11%   |
| Apple               | 4         | 4      | 2.48%   |
| Transcend           | 3         | 3      | 1.86%   |
| A-DATA Technology   | 3         | 3      | 1.86%   |
| Team                | 2         | 2      | 1.24%   |
| PNY                 | 2         | 2      | 1.24%   |
| Patriot             | 2         | 2      | 1.24%   |
| Micron Technology   | 2         | 2      | 1.24%   |
| LITEONIT            | 2         | 2      | 1.24%   |
| KingSpec            | 2         | 2      | 1.24%   |
| GOODRAM             | 2         | 2      | 1.24%   |
| China               | 2         | 2      | 1.24%   |
| XUM                 | 1         | 1      | 0.62%   |
| Verbatim            | 1         | 1      | 0.62%   |
| SSSTC               | 1         | 1      | 0.62%   |
| SPCC                | 1         | 1      | 0.62%   |
| ShiJi               | 1         | 1      | 0.62%   |
| Plextor             | 1         | 1      | 0.62%   |
| Phison              | 1         | 1      | 0.62%   |
| Netac               | 1         | 1      | 0.62%   |
| MidasForce          | 1         | 1      | 0.62%   |
| LITEON              | 1         | 1      | 0.62%   |
| Lexar               | 1         | 2      | 0.62%   |
| Innodisk            | 1         | 1      | 0.62%   |
| Fanxiang            | 1         | 2      | 0.62%   |
| Dell                | 1         | 2      | 0.62%   |
| Apacer              | 1         | 1      | 0.62%   |
| Acer                | 1         | 1      | 0.62%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 146       | 180    | 54.28%  |
| HDD  | 63        | 71     | 23.42%  |
| NVMe | 60        | 80     | 22.3%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 196       | 251    | 76.56%  |
| NVMe | 60        | 80     | 23.44%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 142       | 167    | 67.62%  |
| 0.51-1.0   | 58        | 73     | 27.62%  |
| 1.01-2.0   | 10        | 11     | 4.76%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 94        | 29.28%  |
| 101-250    | 83        | 25.86%  |
| 251-500    | 60        | 18.69%  |
| 501-1000   | 29        | 9.03%   |
| 51-100     | 22        | 6.85%   |
| 21-50      | 18        | 5.61%   |
| Unknown    | 12        | 3.74%   |
| 1001-2000  | 3         | 0.93%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 283       | 89.56%  |
| 21-50   | 15        | 4.75%   |
| Unknown | 12        | 3.8%    |
| 101-250 | 3         | 0.95%   |
| 51-100  | 3         | 0.95%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                           | Notebooks | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ACF032 320GB                        | 2         | 2      | 4.76%   |
| SK hynix HFS256G39TND-N210A 256GB               | 2         | 2      | 4.76%   |
| Seagate ST500LT012-9WS142 500GB                 | 2         | 3      | 4.76%   |
| Seagate ST500LM021-1KJ152 500GB                 | 2         | 2      | 4.76%   |
| Kingston SA400S37240G 240GB                     | 2         | 2      | 4.76%   |
| Hitachi HTS541612J9SA00 120GB                   | 2         | 2      | 4.76%   |
| HGST HTS545050A7E380 500GB                      | 2         | 2      | 4.76%   |
| HGST HTS541010A9E680 1TB                        | 2         | 2      | 4.76%   |
| WDC WD6400BEVT-22A0RT0 640GB                    | 1         | 1      | 2.38%   |
| WDC WD3200LPVX-75V0TT0 320GB                    | 1         | 1      | 2.38%   |
| WDC WD10JPVX-60JC3T0 1TB                        | 1         | 1      | 2.38%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB            | 1         | 1      | 2.38%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB            | 1         | 1      | 2.38%   |
| Toshiba MQ01ABD100 1TB                          | 1         | 1      | 2.38%   |
| Toshiba MK1252GSX 120GB                         | 1         | 1      | 2.38%   |
| SK hynix HFS256G39MND-2300A 256GB               | 1         | 1      | 2.38%   |
| ShiJi SSD 512GB                                 | 1         | 1      | 2.38%   |
| Seagate ST9250827AS 250GB                       | 1         | 1      | 2.38%   |
| Seagate ST500LM000-1EJ162 500GB                 | 1         | 2      | 2.38%   |
| Seagate ST1000LM035-1RK172 1TB                  | 1         | 2      | 2.38%   |
| Seagate ST1000LM024 HN-M101MBB 1TB              | 1         | 1      | 2.38%   |
| SanDisk SSD PLUS 1000GB                         | 1         | 1      | 2.38%   |
| Samsung Electronics SSD 980 500GB               | 1         | 1      | 2.38%   |
| Samsung Electronics SSD 870 EVO 500GB           | 1         | 1      | 2.38%   |
| Samsung Electronics SSD 840 PRO Series 256GB    | 1         | 1      | 2.38%   |
| Samsung Electronics MZNTE128HMGR-000SO 128GB    | 1         | 1      | 2.38%   |
| Samsung Electronics HM320JI 320GB               | 1         | 1      | 2.38%   |
| Patriot Inferno 60GB SSD                        | 1         | 1      | 2.38%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB | 1         | 1      | 2.38%   |
| Intel SSDSC2BF180A5L 180GB                      | 1         | 1      | 2.38%   |
| Intel SSDSC2BF180A4L 180GB                      | 1         | 1      | 2.38%   |
| Hitachi HTS543225L9A300 250GB                   | 1         | 1      | 2.38%   |
| HGST HTS721010A9E630 1TB                        | 1         | 1      | 2.38%   |
| Fanxiang S101 512GB                             | 1         | 2      | 2.38%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 11     | 19.05%  |
| Toshiba             | 6         | 6      | 14.29%  |
| Samsung Electronics | 5         | 5      | 11.9%   |
| HGST                | 5         | 5      | 11.9%   |
| WDC                 | 3         | 3      | 7.14%   |
| SK hynix            | 3         | 3      | 7.14%   |
| Hitachi             | 3         | 3      | 7.14%   |
| Kingston            | 2         | 2      | 4.76%   |
| Intel               | 2         | 2      | 4.76%   |
| ShiJi               | 1         | 1      | 2.38%   |
| SanDisk             | 1         | 1      | 2.38%   |
| Patriot             | 1         | 1      | 2.38%   |
| Micron Technology   | 1         | 1      | 2.38%   |
| Fanxiang            | 1         | 2      | 2.38%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 11     | 33.33%  |
| HGST                | 5         | 5      | 20.83%  |
| Toshiba             | 4         | 4      | 16.67%  |
| WDC                 | 3         | 3      | 12.5%   |
| Hitachi             | 3         | 3      | 12.5%   |
| Samsung Electronics | 1         | 1      | 4.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 23        | 27     | 56.1%   |
| SSD  | 17        | 18     | 41.46%  |
| NVMe | 1         | 1      | 2.44%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Intel SSDSCKKF512G8 SATA 512GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| Intel  | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 213       | 282    | 83.53%  |
| Malfunc  | 39        | 46     | 15.29%  |
| Detected | 2         | 2      | 0.78%   |
| Failed   | 1         | 1      | 0.39%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 201       | 56.62%  |
| Samsung Electronics                     | 39        | 10.99%  |
| AMD                                     | 25        | 7.04%   |
| SK hynix                                | 16        | 4.51%   |
| SanDisk                                 | 16        | 4.51%   |
| Phison Electronics                      | 9         | 2.54%   |
| Toshiba                                 | 8         | 2.25%   |
| Micron Technology                       | 8         | 2.25%   |
| Kingston Technology Company             | 6         | 1.69%   |
| Nvidia                                  | 5         | 1.41%   |
| Micron/Crucial Technology               | 5         | 1.41%   |
| Silicon Motion                          | 3         | 0.85%   |
| MAXIO Technology (Hangzhou)             | 3         | 0.85%   |
| KIOXIA                                  | 3         | 0.85%   |
| Shenzhen Longsys Electronics            | 2         | 0.56%   |
| ADATA Technology                        | 2         | 0.56%   |
| Solid State Storage Technology          | 1         | 0.28%   |
| Shenzhen Unionmemory Information System | 1         | 0.28%   |
| Shenzhen Techwinsemi Technology         | 1         | 0.28%   |
| Biwin Storage Technology                | 1         | 0.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                                              | Notebooks | Percent |
|--------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                                                 | 35        | 9.49%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                                                   | 28        | 7.59%   |
| AMD FCH SATA Controller [AHCI mode]                                                                                | 22        | 5.96%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                                                     | 17        | 4.61%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                                                      | 16        | 4.34%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                                                       | 16        | 4.34%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller                                       | 16        | 4.34%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                                                 | 14        | 3.79%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                                               | 9         | 2.44%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                                                        | 8         | 2.17%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                                                  | 8         | 2.17%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                                              | 8         | 2.17%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                                              | 7         | 1.9%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                                               | 6         | 1.63%   |
| Intel Comet Lake SATA AHCI Controller                                                                              | 5         | 1.36%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                                                         | 4         | 1.08%   |
| Nvidia MCP79 AHCI Controller                                                                                       | 4         | 1.08%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                                                        | 4         | 1.08%   |
| Intel Tiger Lake-LP SATA Controller                                                                                | 4         | 1.08%   |
| Intel SSD 660P Series                                                                                              | 4         | 1.08%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                                                      | 4         | 1.08%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                                                   | 4         | 1.08%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]                                     | 4         | 1.08%   |
| Toshiba BG3 x2 NVMe SSD Controller (DRAM-less)                                                                     | 3         | 0.81%   |
| SK hynix BC511 NVMe SSD                                                                                            | 3         | 0.81%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                                                  | 3         | 0.81%   |
| Samsung NVMe SSD Controller SM951/PM951                                                                            | 3         | 0.81%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                                                     | 3         | 0.81%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                                                | 3         | 0.81%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                                           | 3         | 0.81%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                                                         | 3         | 0.81%   |
| Intel Tiger Lake SATA AHCI Controller                                                                              | 3         | 0.81%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                                                     | 3         | 0.81%   |
| Toshiba XG5 NVMe SSD Controller                                                                                    | 2         | 0.54%   |
| Toshiba XG4 NVMe SSD Controller                                                                                    | 2         | 0.54%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                                                                 | 2         | 0.54%   |
| Shenzhen Longsys FORESEE XP1000 / Lexar Professional CFexpress Type B Gold series, NM620 PCIe NVME SSD (DRAM-less) | 2         | 0.54%   |
| Sandisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                                                       | 2         | 0.54%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)                                          | 2         | 0.54%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                                                      | 2         | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 208       | 58.76%  |
| NVMe | 116       | 32.77%  |
| RAID | 19        | 5.37%   |
| IDE  | 11        | 3.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 247       | 80.46%  |
| AMD    | 60        | 19.54%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz       | 8         | 2.61%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 6         | 1.95%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 5         | 1.63%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 5         | 1.63%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 5         | 1.63%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 5         | 1.63%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 4         | 1.3%    |
| Intel Core i7-8550U CPU @ 1.80GHz       | 4         | 1.3%    |
| Intel Core i7-6500U CPU @ 2.50GHz       | 4         | 1.3%    |
| Intel Core i7-5500U CPU @ 2.40GHz       | 4         | 1.3%    |
| Intel Core i7-3520M CPU @ 2.90GHz       | 4         | 1.3%    |
| Intel Core i7-10510U CPU @ 1.80GHz      | 4         | 1.3%    |
| Intel Core i5-8350U CPU @ 1.70GHz       | 4         | 1.3%    |
| Intel Core i5-8250U CPU @ 1.60GHz       | 4         | 1.3%    |
| Intel Core i5-5200U CPU @ 2.20GHz       | 4         | 1.3%    |
| Intel Core i5-4200U CPU @ 1.60GHz       | 4         | 1.3%    |
| Intel Core 2 Duo                        | 4         | 1.3%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 4         | 1.3%    |
| AMD Ryzen 7 5800H with Radeon Graphics  | 4         | 1.3%    |
| Intel CPU Version                       | 3         | 0.98%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 3         | 0.98%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 3         | 0.98%   |
| Intel Core i7-2620M CPU @ 2.70GHz       | 3         | 0.98%   |
| Intel Core i5-8300H CPU @ 2.30GHz       | 3         | 0.98%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 3         | 0.98%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 3         | 0.98%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 3         | 0.98%   |
| Intel Core i5-3337U CPU @ 1.80GHz       | 3         | 0.98%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 3         | 0.98%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 3         | 0.98%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 3         | 0.98%   |
| Intel Core i3-3217U CPU @ 1.80GHz       | 3         | 0.98%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 3         | 0.98%   |
| Intel 11th Gen Core i5-1145G7 @ 2.60GHz | 3         | 0.98%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 3         | 0.98%   |
| Intel Core m7-6Y75 CPU @ 1.20GHz        | 2         | 0.65%   |
| Intel Core i9-10980HK CPU @ 2.40GHz     | 2         | 0.65%   |
| Intel Core i7-8850H CPU @ 2.60GHz       | 2         | 0.65%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz      | 2         | 0.65%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 2         | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 90        | 29.32%  |
| Intel Core i7           | 77        | 25.08%  |
| Other                   | 24        | 7.82%   |
| Intel Core i3           | 20        | 6.51%   |
| AMD Ryzen 7             | 18        | 5.86%   |
| AMD Ryzen 5             | 18        | 5.86%   |
| Intel Core 2 Duo        | 14        | 4.56%   |
| Intel Celeron           | 8         | 2.61%   |
| Intel Pentium           | 5         | 1.63%   |
| AMD Ryzen 7 PRO         | 5         | 1.63%   |
| AMD A6                  | 4         | 1.3%    |
| Intel Core i9           | 3         | 0.98%   |
| Intel Core m7           | 2         | 0.65%   |
| AMD Ryzen 3             | 2         | 0.65%   |
| AMD E1                  | 2         | 0.65%   |
| AMD A4                  | 2         | 0.65%   |
| AMD A10                 | 2         | 0.65%   |
| Intel Xeon              | 1         | 0.33%   |
| Intel Pentium Dual-Core | 1         | 0.33%   |
| Intel Genuine           | 1         | 0.33%   |
| Intel Core m3           | 1         | 0.33%   |
| Intel Core 2            | 1         | 0.33%   |
| Intel Celeron Dual-Core | 1         | 0.33%   |
| AMD Ryzen 9             | 1         | 0.33%   |
| AMD Ryzen 5 PRO         | 1         | 0.33%   |
| AMD Ryzen 3 PRO         | 1         | 0.33%   |
| AMD PRO A10             | 1         | 0.33%   |
| AMD Athlon              | 1         | 0.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 141       | 45.93%  |
| 4       | 92        | 29.97%  |
| 8       | 26        | 8.47%   |
| 6       | 14        | 4.56%   |
| 16      | 12        | 3.91%   |
| Unknown | 11        | 3.58%   |
| 12      | 9         | 2.93%   |
| 1       | 2         | 0.65%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 303       | 98.7%   |
| 2      | 4         | 1.3%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 224       | 72.96%  |
| 1       | 72        | 23.45%  |
| Unknown | 11        | 3.58%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 61        | 19.87%  |
| IvyBridge     | 31        | 10.1%   |
| Skylake       | 30        | 9.77%   |
| Haswell       | 26        | 8.47%   |
| Unknown       | 21        | 6.84%   |
| SandyBridge   | 17        | 5.54%   |
| Broadwell     | 17        | 5.54%   |
| Penryn        | 15        | 4.89%   |
| Zen 3         | 14        | 4.56%   |
| TigerLake     | 12        | 3.91%   |
| Zen+          | 10        | 3.26%   |
| Zen 2         | 9         | 2.93%   |
| Westmere      | 7         | 2.28%   |
| IceLake       | 5         | 1.63%   |
| Excavator     | 5         | 1.63%   |
| Core          | 5         | 1.63%   |
| CometLake     | 5         | 1.63%   |
| Silvermont    | 4         | 1.3%    |
| Piledriver    | 2         | 0.65%   |
| K10           | 2         | 0.65%   |
| Goldmont plus | 2         | 0.65%   |
| Goldmont      | 2         | 0.65%   |
| Zen           | 1         | 0.33%   |
| Puma          | 1         | 0.33%   |
| K10 Llano     | 1         | 0.33%   |
| Jaguar        | 1         | 0.33%   |
| Bobcat        | 1         | 0.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 231       | 62.94%  |
| AMD    | 71        | 19.35%  |
| Nvidia | 65        | 17.71%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 27        | 7.24%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                     | 19        | 5.09%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                  | 19        | 5.09%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 19        | 5.09%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 17        | 4.56%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                  | 16        | 4.29%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 10        | 2.68%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                   | 10        | 2.68%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 10        | 2.68%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 10        | 2.68%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 10        | 2.68%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]               | 8         | 2.14%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 8         | 2.14%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 7         | 1.88%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 7         | 1.88%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 6         | 1.61%   |
| Intel Skylake-H GT2 [HD Graphics 530]                                     | 6         | 1.61%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 6         | 1.61%   |
| Intel Core Processor Integrated Graphics Controller                       | 6         | 1.61%   |
| AMD Lucienne                                                              | 6         | 1.61%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 5         | 1.34%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 4         | 1.07%   |
| AMD Barcelo                                                               | 4         | 1.07%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 3         | 0.8%    |
| Nvidia C79 [GeForce 9400M]                                                | 3         | 0.8%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 3         | 0.8%    |
| Intel Skylake-Y GT2 [HD Graphics 515]                                     | 3         | 0.8%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 3         | 0.8%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 3         | 0.8%    |
| Intel Kaby Lake-H GT2 [HD Graphics 630]                                   | 3         | 0.8%    |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 3         | 0.8%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 3         | 0.8%    |
| AMD HawkPoint1                                                            | 3         | 0.8%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 2         | 0.54%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 2         | 0.54%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 2         | 0.54%   |
| Nvidia GM108M [GeForce MX130]                                             | 2         | 0.54%   |
| Nvidia GM108M [GeForce 940MX]                                             | 2         | 0.54%   |
| Nvidia GK107GLM [Quadro K1000M]                                           | 2         | 0.54%   |
| Nvidia GF108GLM [NVS 5200M]                                               | 2         | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 165       | 53.57%  |
| 1 x AMD        | 56        | 18.18%  |
| Intel + Nvidia | 46        | 14.94%  |
| 1 x Nvidia     | 15        | 4.87%   |
| 2 x Intel      | 11        | 3.57%   |
| Intel + AMD    | 9         | 2.92%   |
| AMD + Nvidia   | 4         | 1.3%    |
| 2 x AMD        | 2         | 0.65%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 295       | 95.47%  |
| Proprietary | 14        | 4.53%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 267       | 85.58%  |
| 0.01-0.5   | 16        | 5.13%   |
| 1.01-2.0   | 12        | 3.85%   |
| 0.51-1.0   | 9         | 2.88%   |
| 3.01-4.0   | 4         | 1.28%   |
| 5.01-6.0   | 3         | 0.96%   |
| 7.01-8.0   | 1         | 0.32%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 62        | 20.6%   |
| LG Display              | 49        | 16.28%  |
| Chimei Innolux          | 44        | 14.62%  |
| BOE                     | 42        | 13.95%  |
| Samsung Electronics     | 26        | 8.64%   |
| Lenovo                  | 10        | 3.32%   |
| Sharp                   | 8         | 2.66%   |
| InfoVision              | 7         | 2.33%   |
| Apple                   | 7         | 2.33%   |
| PANDA                   | 4         | 1.33%   |
| Iiyama                  | 4         | 1.33%   |
| Dell                    | 4         | 1.33%   |
| CSO                     | 4         | 1.33%   |
| Chi Mei Optoelectronics | 4         | 1.33%   |
| Philips                 | 3         | 1%      |
| Panasonic               | 3         | 1%      |
| BenQ                    | 3         | 1%      |
| HKC                     | 2         | 0.66%   |
| Goldstar                | 2         | 0.66%   |
| ___                     | 1         | 0.33%   |
| Unknown                 | 1         | 0.33%   |
| LG Philips              | 1         | 0.33%   |
| JDI                     | 1         | 0.33%   |
| IBM                     | 1         | 0.33%   |
| Hewlett-Packard         | 1         | 0.33%   |
| HannStar                | 1         | 0.33%   |
| Fujitsu Siemens         | 1         | 0.33%   |
| CSW                     | 1         | 0.33%   |
| BOE Technology Group    | 1         | 0.33%   |
| AOC                     | 1         | 0.33%   |
| Ancor Communications    | 1         | 0.33%   |
| Unknown                 | 1         | 0.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Panasonic LCD Monitor MEI96A2 2880x1620 340x190mm 15.3-inch           | 3         | 0.99%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch          | 3         | 0.99%   |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch           | 3         | 0.99%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 290x160mm 13.0-inch        | 3         | 0.99%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch         | 3         | 0.99%   |
| Sharp LCD Monitor SHP1481 1920x1080 290x170mm 13.2-inch               | 2         | 0.66%   |
| Sharp LCD Monitor SHP1457 2560x1440 280x160mm 12.7-inch               | 2         | 0.66%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch  | 2         | 0.66%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 300x170mm 13.6-inch  | 2         | 0.66%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch  | 2         | 0.66%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 290x170mm 13.2-inch | 2         | 0.66%   |
| Philips PHL 241B8Q PHL0929 1920x1080 530x300mm 24.0-inch              | 2         | 0.66%   |
| LG Display LCD Monitor LGD0456 1366x768 340x190mm 15.3-inch           | 2         | 0.66%   |
| LG Display LCD Monitor LGD039F 1366x768 350x190mm 15.7-inch           | 2         | 0.66%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch           | 2         | 0.66%   |
| LG Display LCD Monitor LGD01E9 1920x1080 350x190mm 15.7-inch          | 2         | 0.66%   |
| InfoVision LCD Monitor IVO0489 1366x768 260x140mm 11.6-inch           | 2         | 0.66%   |
| HKC LCD Monitor HKC3D05 1920x1080 340x190mm 15.3-inch                 | 2         | 0.66%   |
| CSO LCD Monitor CSO1402 2880x1800 300x190mm 14.0-inch                 | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 340x190mm 15.3-inch      | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 340x190mm 15.3-inch      | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN15BD 1366x768 340x190mm 15.3-inch       | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 310x170mm 13.9-inch      | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch      | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 310x170mm 13.9-inch       | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 310x170mm 13.9-inch       | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch       | 2         | 0.66%   |
| BOE LCD Monitor BOE08D5 1920x1080 340x190mm 15.3-inch                 | 2         | 0.66%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 340x190mm 15.3-inch        | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch         | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch        | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO35EC 1366x768 340x190mm 15.3-inch         | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 310x170mm 13.9-inch        | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO305C 1366x768 260x140mm 11.6-inch         | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch        | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch        | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 340x190mm 15.3-inch        | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 340x190mm 15.3-inch         | 2         | 0.66%   |
| ___ MY TV LED TV ___0101 1920x1080                                    | 1         | 0.33%   |
| Unknown LCD Monitor Sharp 3840x2160                                   | 1         | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 141       | 48.45%  |
| 1366x768 (WXGA)    | 83        | 28.52%  |
| 1600x900 (HD+)     | 14        | 4.81%   |
| 2560x1440 (QHD)    | 12        | 4.12%   |
| 3840x2160 (4K)     | 7         | 2.41%   |
| 1920x1200 (WUXGA)  | 7         | 2.41%   |
| 1280x800 (WXGA)    | 7         | 2.41%   |
| 2880x1800          | 6         | 2.06%   |
| 1440x900 (WXGA+)   | 4         | 1.37%   |
| 1680x1050 (WSXGA+) | 3         | 1.03%   |
| 9600x2160          | 1         | 0.34%   |
| 3840x1600          | 1         | 0.34%   |
| 3200x1800 (QHD+)   | 1         | 0.34%   |
| 3000x2000          | 1         | 0.34%   |
| 2560x1600          | 1         | 0.34%   |
| 2240x1400          | 1         | 0.34%   |
| 1280x1024 (SXGA)   | 1         | 0.34%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 119       | 39.4%   |
| 13      | 97        | 32.12%  |
| 12      | 16        | 5.3%    |
| 17      | 15        | 4.97%   |
| 14      | 11        | 3.64%   |
| 24      | 9         | 2.98%   |
| 11      | 9         | 2.98%   |
| 27      | 6         | 1.99%   |
| 23      | 5         | 1.66%   |
| 31      | 3         | 0.99%   |
| Unknown | 3         | 0.99%   |
| 21      | 2         | 0.66%   |
| 16      | 2         | 0.66%   |
| 40      | 1         | 0.33%   |
| 39      | 1         | 0.33%   |
| 37      | 1         | 0.33%   |
| 22      | 1         | 0.33%   |
| 19      | 1         | 0.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 189       | 62.79%  |
| 201-300     | 64        | 21.26%  |
| 501-600     | 20        | 6.64%   |
| 351-400     | 15        | 4.98%   |
| 401-500     | 4         | 1.33%   |
| 801-900     | 3         | 1%      |
| 601-700     | 3         | 1%      |
| Unknown     | 3         | 1%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 241       | 86.69%  |
| 16/10   | 29        | 10.43%  |
| 3/2     | 3         | 1.08%   |
| Unknown | 2         | 0.72%   |
| 5/4     | 1         | 0.36%   |
| 4/3     | 1         | 0.36%   |
| 21/9    | 1         | 0.36%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 91        | 30.13%  |
| 81-90          | 86        | 28.48%  |
| 101-110        | 25        | 8.28%   |
| 71-80          | 22        | 7.28%   |
| 61-70          | 16        | 5.3%    |
| 201-250        | 16        | 5.3%    |
| 121-130        | 14        | 4.64%   |
| 51-60          | 9         | 2.98%   |
| 301-350        | 6         | 1.99%   |
| 111-120        | 5         | 1.66%   |
| 351-500        | 3         | 0.99%   |
| 501-1000       | 3         | 0.99%   |
| Unknown        | 3         | 0.99%   |
| 251-300        | 1         | 0.33%   |
| 151-200        | 1         | 0.33%   |
| 141-150        | 1         | 0.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 145       | 48.33%  |
| 101-120       | 67        | 22.33%  |
| 51-100        | 38        | 12.67%  |
| 161-240       | 37        | 12.33%  |
| More than 240 | 10        | 3.33%   |
| Unknown       | 3         | 1%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 255       | 81.47%  |
| 2     | 29        | 9.27%   |
| 0     | 29        | 9.27%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 208       | 42.98%  |
| Realtek Semiconductor                  | 123       | 25.41%  |
| Qualcomm Atheros                       | 52        | 10.74%  |
| Broadcom                               | 29        | 5.99%   |
| TP-Link                                | 10        | 2.07%   |
| Sierra Wireless                        | 7         | 1.45%   |
| Ericsson Business Mobile Networks      | 6         | 1.24%   |
| Samsung Electronics                    | 4         | 0.83%   |
| Ralink Technology                      | 4         | 0.83%   |
| MediaTek                               | 4         | 0.83%   |
| Marvell Technology Group               | 4         | 0.83%   |
| Edimax Technology                      | 4         | 0.83%   |
| Qualcomm                               | 3         | 0.62%   |
| Nvidia                                 | 3         | 0.62%   |
| ASUSTek Computer                       | 3         | 0.62%   |
| Qualcomm Technologies                  | 2         | 0.41%   |
| NetGear                                | 2         | 0.41%   |
| Hewlett-Packard                        | 2         | 0.41%   |
| Xiaomi                                 | 1         | 0.21%   |
| Suzhou Motorcomm Electronic Technology | 1         | 0.21%   |
| Ralink                                 | 1         | 0.21%   |
| Qualcomm Atheros Communications        | 1         | 0.21%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.21%   |
| Mercucys                               | 1         | 0.21%   |
| Lenovo                                 | 1         | 0.21%   |
| Huawei Technologies                    | 1         | 0.21%   |
| Google                                 | 1         | 0.21%   |
| Generic                                | 1         | 0.21%   |
| Fibocom                                | 1         | 0.21%   |
| Dell                                   | 1         | 0.21%   |
| D-Link                                 | 1         | 0.21%   |
| Apple                                  | 1         | 0.21%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 80        | 13.01%  |
| Intel Wireless 8265 / 8275                                             | 26        | 4.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 26        | 4.23%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 21        | 3.41%   |
| Intel Wireless 7265                                                    | 20        | 3.25%   |
| Intel Ethernet Connection (4) I219-LM                                  | 17        | 2.76%   |
| Intel Wi-Fi 6 AX200                                                    | 15        | 2.44%   |
| Intel Wireless 8260                                                    | 14        | 2.28%   |
| Intel Wireless 7260                                                    | 13        | 2.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 12        | 1.95%   |
| Intel Wi-Fi 6 AX201                                                    | 11        | 1.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 10        | 1.63%   |
| Intel Ethernet Connection I219-LM                                      | 10        | 1.63%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 9         | 1.46%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 8         | 1.3%    |
| Intel Wireless 3165                                                    | 8         | 1.3%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 8         | 1.3%    |
| Intel Cannon Lake PCH CNVi WiFi                                        | 8         | 1.3%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 7         | 1.14%   |
| Intel Ethernet Connection (3) I218-LM                                  | 7         | 1.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 6         | 0.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 6         | 0.98%   |
| Intel Ethernet Connection I218-LM                                      | 6         | 0.98%   |
| Intel Centrino Ultimate-N 6300                                         | 6         | 0.98%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 6         | 0.98%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 5         | 0.81%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 5         | 0.81%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 5         | 0.81%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 5         | 0.81%   |
| Intel Wireless 3160                                                    | 5         | 0.81%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 4         | 0.65%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 4         | 0.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 4         | 0.65%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 4         | 0.65%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 4         | 0.65%   |
| Intel 82577LM Gigabit Network Connection                               | 4         | 0.65%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 4         | 0.65%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 3         | 0.49%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 3         | 0.49%   |
| Sierra Wireless EM7455                                                 | 3         | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 198       | 57.73%  |
| Realtek Semiconductor           | 43        | 12.54%  |
| Qualcomm Atheros                | 42        | 12.24%  |
| Broadcom                        | 22        | 6.41%   |
| TP-Link                         | 10        | 2.92%   |
| Sierra Wireless                 | 5         | 1.46%   |
| Ralink Technology               | 4         | 1.17%   |
| MediaTek                        | 4         | 1.17%   |
| Edimax Technology               | 4         | 1.17%   |
| ASUSTek Computer                | 3         | 0.87%   |
| Qualcomm Technologies           | 2         | 0.58%   |
| NetGear                         | 2         | 0.58%   |
| Ralink                          | 1         | 0.29%   |
| Qualcomm Atheros Communications | 1         | 0.29%   |
| Mercucys                        | 1         | 0.29%   |
| D-Link                          | 1         | 0.29%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 26        | 7.54%   |
| Intel Wireless 7265                                            | 20        | 5.8%    |
| Intel Wi-Fi 6 AX200                                            | 15        | 4.35%   |
| Intel Wireless 8260                                            | 14        | 4.06%   |
| Intel Wireless 7260                                            | 13        | 3.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 12        | 3.48%   |
| Intel Wi-Fi 6 AX201                                            | 11        | 3.19%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 10        | 2.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 9         | 2.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 8         | 2.32%   |
| Intel Wireless 3165                                            | 8         | 2.32%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 8         | 2.32%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 8         | 2.32%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 7         | 2.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 6         | 1.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 1.74%   |
| Intel Centrino Ultimate-N 6300                                 | 6         | 1.74%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 6         | 1.74%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 5         | 1.45%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 5         | 1.45%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 5         | 1.45%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 5         | 1.45%   |
| Intel Wireless 3160                                            | 5         | 1.45%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 4         | 1.16%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 1.16%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 4         | 1.16%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 4         | 1.16%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 4         | 1.16%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 3         | 0.87%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 3         | 0.87%   |
| Sierra Wireless EM7455                                         | 3         | 0.87%   |
| Ralink RT5370 Wireless Adapter                                 | 3         | 0.87%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 3         | 0.87%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 3         | 0.87%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 3         | 0.87%   |
| Intel Centrino Advanced-N 6235                                 | 3         | 0.87%   |
| Intel Centrino Advanced-N 6200                                 | 3         | 0.87%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 3         | 0.87%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 3         | 0.87%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 3         | 0.87%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 102       | 40.48%  |
| Intel                                  | 102       | 40.48%  |
| Qualcomm Atheros                       | 17        | 6.75%   |
| Broadcom                               | 12        | 4.76%   |
| Samsung Electronics                    | 4         | 1.59%   |
| Marvell Technology Group               | 4         | 1.59%   |
| Qualcomm                               | 3         | 1.19%   |
| Nvidia                                 | 3         | 1.19%   |
| Xiaomi                                 | 1         | 0.4%    |
| Suzhou Motorcomm Electronic Technology | 1         | 0.4%    |
| OnePlus Technology (Shenzhen)          | 1         | 0.4%    |
| Lenovo                                 | 1         | 0.4%    |
| Apple                                  | 1         | 0.4%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 80        | 31.5%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 26        | 10.24%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 21        | 8.27%   |
| Intel Ethernet Connection (4) I219-LM                                  | 17        | 6.69%   |
| Intel Ethernet Connection I219-LM                                      | 10        | 3.94%   |
| Intel Ethernet Connection (3) I218-LM                                  | 7         | 2.76%   |
| Intel Ethernet Connection I218-LM                                      | 6         | 2.36%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 4         | 1.57%   |
| Intel 82577LM Gigabit Network Connection                               | 4         | 1.57%   |
| Qualcomm FP3                                                           | 3         | 1.18%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 3         | 1.18%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 3         | 1.18%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 3         | 1.18%   |
| Nvidia MCP79 Ethernet                                                  | 3         | 1.18%   |
| Intel Ethernet Connection (7) I219-LM                                  | 3         | 1.18%   |
| Intel Ethernet Connection (6) I219-LM                                  | 3         | 1.18%   |
| Intel Ethernet Connection (13) I219-LM                                 | 3         | 1.18%   |
| Intel 82567LM Gigabit Network Connection                               | 3         | 1.18%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 0.79%   |
| Intel Ethernet Connection (6) I219-V                                   | 2         | 0.79%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 0.79%   |
| Intel Ethernet Connection (3) I218-V                                   | 2         | 0.79%   |
| Intel Ethernet Connection (10) I219-LM                                 | 2         | 0.79%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 2         | 0.79%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 0.79%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 2         | 0.79%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 2         | 0.79%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 1         | 0.39%   |
| Suzhou Motorcomm Electronic YT6801 Gigabit Ethernet Controller         | 1         | 0.39%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 0.39%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.39%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.39%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1         | 0.39%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.39%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 0.39%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 1         | 0.39%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                          | 1         | 0.39%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1         | 0.39%   |
| OnePlus (Shenzhen) Android Remote NDIS Device                          | 1         | 0.39%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                | 1         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 308       | 53.94%  |
| Ethernet | 247       | 43.26%  |
| Unknown  | 9         | 1.58%   |
| Modem    | 7         | 1.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 195       | 59.27%  |
| Ethernet | 131       | 39.82%  |
| Modem    | 3         | 0.91%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 233       | 75.9%   |
| 1     | 70        | 22.8%   |
| 3     | 4         | 1.3%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 307       | 99.68%  |
| Yes  | 1         | 0.32%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 157       | 62.55%  |
| Realtek Semiconductor           | 22        | 8.76%   |
| Qualcomm Atheros Communications | 13        | 5.18%   |
| Broadcom                        | 11        | 4.38%   |
| Lite-On Technology              | 10        | 3.98%   |
| Apple                           | 9         | 3.59%   |
| IMC Networks                    | 7         | 2.79%   |
| Dell                            | 6         | 2.39%   |
| Foxconn / Hon Hai               | 3         | 1.2%    |
| USI                             | 2         | 0.8%    |
| Toshiba                         | 2         | 0.8%    |
| Hewlett-Packard                 | 2         | 0.8%    |
| ASUSTek Computer                | 2         | 0.8%    |
| Alps Electric                   | 2         | 0.8%    |
| Skylight Digital                | 1         | 0.4%    |
| MediaTek                        | 1         | 0.4%    |
| Cambridge Silicon Radio         | 1         | 0.4%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 79        | 31.47%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 24        | 9.56%   |
| Intel AX201 Bluetooth                                       | 20        | 7.97%   |
| Intel AX200 Bluetooth                                       | 15        | 5.98%   |
| Realtek Bluetooth Adapter                                   | 10        | 3.98%   |
| Intel AX210 Bluetooth                                       | 8         | 3.19%   |
| Apple Bluetooth Host Controller                             | 7         | 2.79%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 5         | 1.99%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 5         | 1.99%   |
| Realtek  Bluetooth 4.2 Adapter                              | 4         | 1.59%   |
| Realtek Bluetooth 4.2 Adapter                               | 4         | 1.59%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 4         | 1.59%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 3         | 1.2%    |
| Qualcomm Atheros AR9462 Bluetooth                           | 3         | 1.2%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 3         | 1.2%    |
| Lite-On Atheros AR3012 Bluetooth                            | 3         | 1.2%    |
| USI Qualcomm WCN685x Bluetooth Adapter                      | 2         | 0.8%    |
| Toshiba Realtek Bluetooth 4.0 + High Speed Chip             | 2         | 0.8%    |
| Realtek Bluetooth 4.0 Adapter                               | 2         | 0.8%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.1                      | 2         | 0.8%    |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 2         | 0.8%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 2         | 0.8%    |
| Intel Wireless-AC 3168 Bluetooth                            | 2         | 0.8%    |
| Intel AX211 Bluetooth                                       | 2         | 0.8%    |
| IMC Networks Realtek Bluetooth Adapter                      | 2         | 0.8%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 2         | 0.8%    |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 2         | 0.8%    |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 0.8%    |
| Apple Broadcom Built-in Bluetooth                           | 2         | 0.8%    |
| Skylight Digital Realtek Bluetooth Adapter                  | 1         | 0.4%    |
| Realtek RTL8723B Bluetooth                                  | 1         | 0.4%    |
| Realtek Bluetooth 4.0 + High Speed Chip                     | 1         | 0.4%    |
| Qualcomm Atheros AR9462 Bluetooth 3.0 + HS Adapter          | 1         | 0.4%    |
| Qualcomm Atheros AR3012 Bluetooth                           | 1         | 0.4%    |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 0.4%    |
| MediaTek Wireless_Device                                    | 1         | 0.4%    |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS                 | 1         | 0.4%    |
| Lite-On Broadcom Bluetooth 4.0 USB                          | 1         | 0.4%    |
| Lite-On Bluetooth USB Module                                | 1         | 0.4%    |
| Lite-On Atheros Bluetooth                                   | 1         | 0.4%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 243       | 68.45%  |
| AMD                   | 64        | 18.03%  |
| Nvidia                | 24        | 6.76%   |
| Lenovo                | 4         | 1.13%   |
| C-Media Electronics   | 3         | 0.85%   |
| Logitech              | 2         | 0.56%   |
| Focusrite-Novation    | 2         | 0.56%   |
| Trust                 | 1         | 0.28%   |
| SteelSeries ApS       | 1         | 0.28%   |
| RODE Microphones      | 1         | 0.28%   |
| Realtek Semiconductor | 1         | 0.28%   |
| No brand              | 1         | 0.28%   |
| Microsoft             | 1         | 0.28%   |
| Kingston Technology   | 1         | 0.28%   |
| GN Netcom             | 1         | 0.28%   |
| DSEA A/S              | 1         | 0.28%   |
| Creative Technology   | 1         | 0.28%   |
| Corsair               | 1         | 0.28%   |
| Cambridge Audio       | 1         | 0.28%   |
| Unknown               | 1         | 0.28%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 52        | 11.5%   |
| AMD Ryzen HD Audio Controller                                              | 46        | 10.18%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 32        | 7.08%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 23        | 5.09%   |
| Intel Haswell-ULT HD Audio Controller                                      | 19        | 4.2%    |
| Intel 8 Series HD Audio Controller                                         | 19        | 4.2%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 18        | 3.98%   |
| Intel Broadwell-U Audio Controller                                         | 18        | 3.98%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 16        | 3.54%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 12        | 2.65%   |
| Intel Comet Lake PCH-LP cAVS                                               | 11        | 2.43%   |
| Intel Cannon Lake PCH cAVS                                                 | 11        | 2.43%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 11        | 2.43%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 10        | 2.21%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8         | 1.77%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 7         | 1.55%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7         | 1.55%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 7         | 1.55%   |
| AMD Radeon High Definition Audio Controller                                | 7         | 1.55%   |
| AMD FCH Azalia Controller                                                  | 6         | 1.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 1.11%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 5         | 1.11%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 5         | 1.11%   |
| Nvidia MCP79 High Definition Audio                                         | 4         | 0.88%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 0.88%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 4         | 0.88%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 0.88%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3         | 0.66%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 0.66%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 0.66%   |
| Intel CM238 HD Audio Controller                                            | 3         | 0.66%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 3         | 0.66%   |
| AMD High Definition Audio Controller                                       | 3         | 0.66%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 0.44%   |
| Nvidia TU104 HD Audio Controller                                           | 2         | 0.44%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 0.44%   |
| Lenovo Lenovo USB-C Mini Dock                                              | 2         | 0.44%   |
| Intel Crystal Well HD Audio Controller                                     | 2         | 0.44%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 0.44%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 2         | 0.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 123       | 31.38%  |
| SK hynix            | 105       | 26.79%  |
| Micron Technology   | 46        | 11.73%  |
| Kingston            | 25        | 6.38%   |
| Crucial             | 24        | 6.12%   |
| Unknown             | 13        | 3.32%   |
| Elpida              | 10        | 2.55%   |
| Ramaxel Technology  | 8         | 2.04%   |
| Unknown             | 8         | 2.04%   |
| Corsair             | 4         | 1.02%   |
| A-DATA Technology   | 4         | 1.02%   |
| Unknown (ABCD)      | 3         | 0.77%   |
| Transcend           | 3         | 0.77%   |
| GOODRAM             | 2         | 0.51%   |
| G.Skill             | 2         | 0.51%   |
| Apacer              | 2         | 0.51%   |
| Timetec             | 1         | 0.26%   |
| Team                | 1         | 0.26%   |
| Smart Modular       | 1         | 0.26%   |
| Smart               | 1         | 0.26%   |
| Silicon Power       | 1         | 0.26%   |
| Neo Forza           | 1         | 0.26%   |
| Nanya Technology    | 1         | 0.26%   |
| GSkill              | 1         | 0.26%   |
| AMD                 | 1         | 0.26%   |
| 09490000802C        | 1         | 0.26%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 11        | 2.72%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s            | 9         | 2.22%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 1.98%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 8         | 1.98%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 1.98%   |
| Unknown                                                          | 8         | 1.98%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 1.73%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 1.73%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 7         | 1.73%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 1.48%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3200MT/s            | 5         | 1.23%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 1.23%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 1.23%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 5         | 1.23%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.99%   |
| Samsung RAM M471B5273DH0-CK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.99%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 4         | 0.99%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.99%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s            | 4         | 0.99%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.99%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 3         | 0.74%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR 667MT/s             | 3         | 0.74%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 0.74%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.74%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 0.74%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.74%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 0.74%   |
| Samsung RAM M471A2G44AM0-CWE 16GiB SODIMM DDR4 3200MT/s          | 3         | 0.74%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.74%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.74%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3                     | 3         | 0.74%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 3         | 0.74%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 3         | 0.74%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 2         | 0.49%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                     | 2         | 0.49%   |
| SK hynix RAM Module 4GB SODIMM LPDDR3 1600MT/s                   | 2         | 0.49%   |
| SK hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.49%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 2         | 0.49%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 0.49%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 137       | 44.19%  |
| DDR3    | 129       | 41.61%  |
| LPDDR3  | 12        | 3.87%   |
| DDR2    | 9         | 2.9%    |
| LPDDR4  | 8         | 2.58%   |
| DDR5    | 6         | 1.94%   |
| LPDDR5  | 4         | 1.29%   |
| DDR     | 2         | 0.65%   |
| Unknown | 2         | 0.65%   |
| SDRAM   | 1         | 0.32%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 283       | 90.42%  |
| Row Of Chips | 24        | 7.67%   |
| Chip         | 3         | 0.96%   |
| DIMM         | 2         | 0.64%   |
| Unknown      | 1         | 0.32%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 140       | 40.35%  |
| 4096  | 121       | 34.87%  |
| 16384 | 52        | 14.99%  |
| 2048  | 25        | 7.2%    |
| 32768 | 7         | 2.02%   |
| 49152 | 1         | 0.29%   |
| 1024  | 1         | 0.29%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 93        | 27.35%  |
| 3200    | 67        | 19.71%  |
| 2400    | 43        | 12.65%  |
| 2667    | 37        | 10.88%  |
| 2133    | 19        | 5.59%   |
| 1333    | 17        | 5%      |
| 1334    | 15        | 4.41%   |
| 800     | 8         | 2.35%   |
| 1867    | 7         | 2.06%   |
| 667     | 6         | 1.76%   |
| 1067    | 5         | 1.47%   |
| 5600    | 4         | 1.18%   |
| Unknown | 4         | 1.18%   |
| 6400    | 3         | 0.88%   |
| 4800    | 2         | 0.59%   |
| 4266    | 2         | 0.59%   |
| 975     | 2         | 0.59%   |
| 7467    | 1         | 0.29%   |
| 4267    | 1         | 0.29%   |
| 3733    | 1         | 0.29%   |
| 1639    | 1         | 0.29%   |
| 1200    | 1         | 0.29%   |
| 1066    | 1         | 0.29%   |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 61        | 24.5%   |
| Microdia                               | 29        | 11.65%  |
| Bison Electronics                      | 28        | 11.24%  |
| IMC Networks                           | 25        | 10.04%  |
| Realtek Semiconductor                  | 21        | 8.43%   |
| Sunplus Innovation Technology          | 18        | 7.23%   |
| Lite-On Technology                     | 10        | 4.02%   |
| Quanta                                 | 9         | 3.61%   |
| Suyin                                  | 8         | 3.21%   |
| Luxvisions Innotech Limited            | 8         | 3.21%   |
| Syntek                                 | 5         | 2.01%   |
| Alcor Micro                            | 5         | 2.01%   |
| Silicon Motion                         | 3         | 1.2%    |
| Logitech                               | 3         | 1.2%    |
| Cheng Uei Precision Industry (Foxlink) | 3         | 1.2%    |
| Shenzhen Kingcome Optoelectronic       | 2         | 0.8%    |
| Ricoh                                  | 2         | 0.8%    |
| Lenovo                                 | 2         | 0.8%    |
| Apple                                  | 2         | 0.8%    |
| USB Camera                             | 1         | 0.4%    |
| OmniVision Technologies                | 1         | 0.4%    |
| Jiangxi Shinetech Optical              | 1         | 0.4%    |
| Intel                                  | 1         | 0.4%    |
| Importek                               | 1         | 0.4%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 21        | 8.43%   |
| Bison Integrated Camera                              | 13        | 5.22%   |
| Sunplus Integrated_Webcam_HD                         | 11        | 4.42%   |
| Microdia Integrated_Webcam_HD                        | 11        | 4.42%   |
| IMC Networks Integrated Camera                       | 9         | 3.61%   |
| Microdia Integrated Webcam                           | 8         | 3.21%   |
| Lite-On Integrated Camera                            | 5         | 2.01%   |
| Chicony HD WebCam                                    | 5         | 2.01%   |
| Realtek USB 2.0 PC Camera                            | 4         | 1.61%   |
| Realtek Integrated_Webcam_HD                         | 4         | 1.61%   |
| Luxvisions Innotech Limited Integrated Camera        | 4         | 1.61%   |
| Chicony USB2.0 HD UVC WebCam                         | 4         | 1.61%   |
| Syntek Integrated Camera                             | 3         | 1.2%    |
| Realtek Integrated Webcam HD                         | 3         | 1.2%    |
| Quanta HP TrueVision HD Camera                       | 3         | 1.2%    |
| Microdia Laptop_Integrated_Webcam_HD                 | 3         | 1.2%    |
| Microdia Integrated Webcam HD                        | 3         | 1.2%    |
| IMC Networks Realtek PC Camera                       | 3         | 1.2%    |
| IMC Networks EasyCamera                              | 3         | 1.2%    |
| Bison ThinkPad Integrated Camera                     | 3         | 1.2%    |
| Bison SunplusIT Integrated Camera                    | 3         | 1.2%    |
| Suyin Integrated_Webcam_HD                           | 2         | 0.8%    |
| Suyin Acer/HP Integrated Webcam [CN0314]             | 2         | 0.8%    |
| Sunplus Laptop_Integrated_Webcam_FHD                 | 2         | 0.8%    |
| Realtek Lenovo EasyCamera                            | 2         | 0.8%    |
| Realtek Front Camera                                 | 2         | 0.8%    |
| Quanta VGA WebCam                                    | 2         | 0.8%    |
| Microdia USB Camera                                  | 2         | 0.8%    |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 2         | 0.8%    |
| Logitech HD Pro Webcam C920                          | 2         | 0.8%    |
| Lenovo Integrated Webcam [R5U877]                    | 2         | 0.8%    |
| IMC Networks USB 2.0 UVC HD Webcam                   | 2         | 0.8%    |
| IMC Networks Realtek DMFT RGB                        | 2         | 0.8%    |
| IMC Networks Lenovo EasyCamera                       | 2         | 0.8%    |
| Chicony USB2.0 VGA UVC WebCam                        | 2         | 0.8%    |
| Chicony thinkpad t430s camera                        | 2         | 0.8%    |
| Chicony Realtek DMFT RGB                             | 2         | 0.8%    |
| Chicony Lenovo Integrated Camera (0.3MP)             | 2         | 0.8%    |
| Chicony Lenovo EasyCamera                            | 2         | 0.8%    |
| Chicony Integrated HP HD Webcam                      | 2         | 0.8%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 22        | 31.88%  |
| Synaptics                  | 17        | 24.64%  |
| Shenzhen Goodix Technology | 7         | 10.14%  |
| Elan Microelectronics      | 6         | 8.7%    |
| Upek                       | 4         | 5.8%    |
| FocalTech Systems          | 3         | 4.35%   |
| STMicroelectronics         | 2         | 2.9%    |
| LighTuning Technology      | 2         | 2.9%    |
| AuthenTec                  | 2         | 2.9%    |
| Samsung Electronics        | 1         | 1.45%   |
| Next Biometrics            | 1         | 1.45%   |
| Fingerprint Cards          | 1         | 1.45%   |
| Broadcom                   | 1         | 1.45%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 9         | 13.04%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 8         | 11.59%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 5         | 7.25%   |
| Shenzhen Goodix Fingerprint Reader                                           | 5         | 7.25%   |
| Elan Fingerprint Sensor                                                      | 5         | 7.25%   |
| Validity Sensors Synaptics WBDI                                              | 4         | 5.8%    |
| Validity Sensors VFS495 Fingerprint Reader                                   | 3         | 4.35%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 3         | 4.35%   |
| FocalTech Systems Fingerprint Reader                                         | 3         | 4.35%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                            | 2         | 2.9%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 2         | 2.9%    |
| STMicroelectronics Fingerprint Reader                                        | 2         | 2.9%    |
| Shenzhen Goodix  Fingerprint Device                                          | 2         | 2.9%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 2         | 2.9%    |
| Validity Sensors VFS491                                                      | 1         | 1.45%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint   | 1         | 1.45%   |
| Upek TCS5B Fingerprint sensor                                                | 1         | 1.45%   |
| Synaptics WBDI                                                               | 1         | 1.45%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 1         | 1.45%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                     | 1         | 1.45%   |
| Synaptics Fingerprint reader [HP G6]                                         | 1         | 1.45%   |
| Samsung CanvasBio Fingerprint Reader                                         | 1         | 1.45%   |
| Next Biometrics NB-2020-U Fingerprint Reader                                 | 1         | 1.45%   |
| Fingerprint Cards FPC Fingerprint Reader                                     | 1         | 1.45%   |
| Elan WBF Fingerprint Sensor                                                  | 1         | 1.45%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 1.45%   |
| AuthenTec AES2810                                                            | 1         | 1.45%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 1         | 1.45%   |

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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 111       | 34.91%  |
| 1     | 73        | 22.96%  |
| 3     | 64        | 20.13%  |
| 4     | 33        | 10.38%  |
| 0     | 26        | 8.18%   |
| 5     | 11        | 3.46%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 223       | 36.38%  |
| Bluetooth                | 162       | 26.43%  |
| Net/wireless             | 71        | 11.58%  |
| Fingerprint reader       | 67        | 10.93%  |
| Card reader              | 54        | 8.81%   |
| Firewire controller      | 14        | 2.28%   |
| Network                  | 10        | 1.63%   |
| Storage                  | 5         | 0.82%   |
| Sound                    | 4         | 0.65%   |
| Net/ethernet             | 3         | 0.49%   |

