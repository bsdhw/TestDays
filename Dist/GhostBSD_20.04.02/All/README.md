GhostBSD 20.04.02 - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for GhostBSD 20.04.02.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/GhostBSD_20.04.02/Desktop/README.md) and [notebooks](/Dist/GhostBSD_20.04.02/Notebook/README.md).

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 146

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Jumper        | EZbook                      | Notebook    | [7d648bcdc7](https://bsd-hardware.info/?probe=7d648bcdc7) | Jan 17, 2022 |
| Acer          | Extensa 5635Z               | Notebook    | [d76873c5dd](https://bsd-hardware.info/?probe=d76873c5dd) | Jan 16, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [69fe175fb8](https://bsd-hardware.info/?probe=69fe175fb8) | Oct 30, 2021 |
| HP            | Pavilion g6                 | Notebook    | [9754bc2e72](https://bsd-hardware.info/?probe=9754bc2e72) | Oct 27, 2021 |
| Lenovo        | ThinkPad T500 2056Y2Z       | Notebook    | [88b86ecf8b](https://bsd-hardware.info/?probe=88b86ecf8b) | Sep 25, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [0ee3fe080c](https://bsd-hardware.info/?probe=0ee3fe080c) | Aug 30, 2021 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [31b995146e](https://bsd-hardware.info/?probe=31b995146e) | Aug 25, 2021 |
| Acer          | Aspire 5750                 | Notebook    | [2bc72bf29e](https://bsd-hardware.info/?probe=2bc72bf29e) | Aug 23, 2021 |
| Intel         | NUC6i7KYB H90766-402        | Mini pc     | [6f89733e13](https://bsd-hardware.info/?probe=6f89733e13) | Aug 16, 2021 |
| MSI           | H81M-P33                    | Desktop     | [6dcb3aa559](https://bsd-hardware.info/?probe=6dcb3aa559) | Aug 05, 2021 |
| Dell          | Latitude E5440              | Notebook    | [3f2e8586a7](https://bsd-hardware.info/?probe=3f2e8586a7) | Aug 05, 2021 |
| Dell          | Latitude E6430              | Notebook    | [4149fa5ec3](https://bsd-hardware.info/?probe=4149fa5ec3) | Aug 04, 2021 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [9fe86991b5](https://bsd-hardware.info/?probe=9fe86991b5) | Aug 04, 2021 |
| ASRock        | X570 Pro4                   | Desktop     | [011fb96fe0](https://bsd-hardware.info/?probe=011fb96fe0) | Aug 04, 2021 |
| Lenovo        | Legion Y7000P 81LD          | Notebook    | [7364ae3b3d](https://bsd-hardware.info/?probe=7364ae3b3d) | Aug 04, 2021 |
| ASRock        | Z77 Extreme6                | Desktop     | [2521c70747](https://bsd-hardware.info/?probe=2521c70747) | Aug 02, 2021 |
| Lenovo        | ThinkPad L512 44444XG       | Notebook    | [a6c8fbcb20](https://bsd-hardware.info/?probe=a6c8fbcb20) | Aug 01, 2021 |
| GPU Compan... | GWTN156-5                   | Notebook    | [bc44d767cc](https://bsd-hardware.info/?probe=bc44d767cc) | Jul 22, 2021 |
| Dell          | Latitude E5520              | Notebook    | [e0dd26220f](https://bsd-hardware.info/?probe=e0dd26220f) | Jul 21, 2021 |
| Apple         | MacBook5,1                  | Notebook    | [1e54d2fbdf](https://bsd-hardware.info/?probe=1e54d2fbdf) | Jul 05, 2021 |
| Apple         | MacBook5,1                  | Notebook    | [f5d7a16498](https://bsd-hardware.info/?probe=f5d7a16498) | Jul 05, 2021 |
| ASUSTek       | PRIME B350M-E               | Desktop     | [bde8057846](https://bsd-hardware.info/?probe=bde8057846) | Jun 29, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [668bf95221](https://bsd-hardware.info/?probe=668bf95221) | Jun 25, 2021 |
| Dell          | Latitude E6420              | Notebook    | [2e8b431cc6](https://bsd-hardware.info/?probe=2e8b431cc6) | Jun 25, 2021 |
| Lenovo        | ThinkPad T440 20B7S1860W    | Notebook    | [8552205176](https://bsd-hardware.info/?probe=8552205176) | Jun 22, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [9f82e215c3](https://bsd-hardware.info/?probe=9f82e215c3) | Jun 22, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [a2deab0991](https://bsd-hardware.info/?probe=a2deab0991) | Jun 15, 2021 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [10d9e99990](https://bsd-hardware.info/?probe=10d9e99990) | May 31, 2021 |
| Sony          | SVP1322M1EBI                | Notebook    | [23316d0f2b](https://bsd-hardware.info/?probe=23316d0f2b) | May 29, 2021 |
| Lenovo        | Board                       | Desktop     | [428f39cbff](https://bsd-hardware.info/?probe=428f39cbff) | May 21, 2021 |
| Lenovo        | ThinkPad T470 20HD000MUK    | Notebook    | [e27342ab94](https://bsd-hardware.info/?probe=e27342ab94) | May 13, 2021 |
| Lenovo        | ThinkPad X250 20CM003WMS    | Notebook    | [11fe52be5e](https://bsd-hardware.info/?probe=11fe52be5e) | May 13, 2021 |
| ASUSTek       | V-P7H55E                    | Desktop     | [7634d3b6ca](https://bsd-hardware.info/?probe=7634d3b6ca) | May 12, 2021 |
| ASUSTek       | V-P7H55E                    | Desktop     | [f2e42a5ca3](https://bsd-hardware.info/?probe=f2e42a5ca3) | May 10, 2021 |
| ASUSTek       | V-P7H55E                    | Desktop     | [0af6399c18](https://bsd-hardware.info/?probe=0af6399c18) | May 10, 2021 |
| Lenovo        | ThinkPad T430 2344C4U       | Notebook    | [0f001f65d2](https://bsd-hardware.info/?probe=0f001f65d2) | Apr 27, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [f8389b0546](https://bsd-hardware.info/?probe=f8389b0546) | Apr 24, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [cb09a1b771](https://bsd-hardware.info/?probe=cb09a1b771) | Apr 08, 2021 |
| Dell          | 0TP412                      | Desktop     | [1bc05b5951](https://bsd-hardware.info/?probe=1bc05b5951) | Apr 04, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [e4e3731289](https://bsd-hardware.info/?probe=e4e3731289) | Apr 01, 2021 |
| Acer          | Aspire E5-521G              | Notebook    | [e2b6dbfe40](https://bsd-hardware.info/?probe=e2b6dbfe40) | Apr 01, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | Desktop     | [ec9e43382e](https://bsd-hardware.info/?probe=ec9e43382e) | Mar 25, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [3e500c12a3](https://bsd-hardware.info/?probe=3e500c12a3) | Mar 24, 2021 |
| HP            | 1850                        | Desktop     | [3055c06d45](https://bsd-hardware.info/?probe=3055c06d45) | Mar 22, 2021 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [a64a4e0792](https://bsd-hardware.info/?probe=a64a4e0792) | Mar 19, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [a7a25be087](https://bsd-hardware.info/?probe=a7a25be087) | Mar 16, 2021 |
| Lenovo        | ThinkPad X250 20CM003WMS    | Notebook    | [c7f71901c3](https://bsd-hardware.info/?probe=c7f71901c3) | Mar 11, 2021 |
| Lenovo        | ThinkPad X250 20CM003WMS    | Notebook    | [803974a844](https://bsd-hardware.info/?probe=803974a844) | Mar 11, 2021 |
| Lenovo        | ThinkPad X250 20CM003WMS    | Notebook    | [196cd8a730](https://bsd-hardware.info/?probe=196cd8a730) | Mar 11, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [240171b234](https://bsd-hardware.info/?probe=240171b234) | Mar 08, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9ede3128c5](https://bsd-hardware.info/?probe=9ede3128c5) | Mar 07, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [39a46ce44e](https://bsd-hardware.info/?probe=39a46ce44e) | Mar 06, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [b1ee3da46f](https://bsd-hardware.info/?probe=b1ee3da46f) | Mar 06, 2021 |
| Gigabyte      | EG43M-S2H                   | Desktop     | [f6eaa55ada](https://bsd-hardware.info/?probe=f6eaa55ada) | Mar 06, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [50ac436475](https://bsd-hardware.info/?probe=50ac436475) | Mar 06, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [f27578615f](https://bsd-hardware.info/?probe=f27578615f) | Mar 05, 2021 |
| Lenovo        | ThinkPad T470 20HD000MUK    | Notebook    | [b85d23571e](https://bsd-hardware.info/?probe=b85d23571e) | Feb 23, 2021 |
| Acer          | Aspire XC-115               | Desktop     | [95f63df64d](https://bsd-hardware.info/?probe=95f63df64d) | Feb 21, 2021 |
| Lenovo        | Kabini CRB 31900058 STD     | Desktop     | [c08ca084b0](https://bsd-hardware.info/?probe=c08ca084b0) | Feb 21, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [3680c4cd75](https://bsd-hardware.info/?probe=3680c4cd75) | Feb 20, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [ade306695d](https://bsd-hardware.info/?probe=ade306695d) | Feb 20, 2021 |
| Acer          | Extensa 5635Z               | Notebook    | [837c6f28b4](https://bsd-hardware.info/?probe=837c6f28b4) | Feb 19, 2021 |
| Acer          | WG43M                       | Desktop     | [28a6795710](https://bsd-hardware.info/?probe=28a6795710) | Feb 15, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [9bbe1119a1](https://bsd-hardware.info/?probe=9bbe1119a1) | Feb 12, 2021 |
| MSI           | PRESTIGE X570 CREATION      | Desktop     | [e6fa5753b5](https://bsd-hardware.info/?probe=e6fa5753b5) | Feb 12, 2021 |
| MSI           | PRESTIGE X570 CREATION      | Desktop     | [fd798dae01](https://bsd-hardware.info/?probe=fd798dae01) | Feb 12, 2021 |
| Dell          | 030VXY A01                  | Desktop     | [23e7163f58](https://bsd-hardware.info/?probe=23e7163f58) | Feb 10, 2021 |
| Lenovo        | ThinkPad T470 20HD000MUK    | Notebook    | [39c8cd6d0c](https://bsd-hardware.info/?probe=39c8cd6d0c) | Feb 08, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [d6bc2b2c1d](https://bsd-hardware.info/?probe=d6bc2b2c1d) | Feb 08, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [5a0b61ac41](https://bsd-hardware.info/?probe=5a0b61ac41) | Feb 07, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [ffc0295ae1](https://bsd-hardware.info/?probe=ffc0295ae1) | Feb 07, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [13fdaa7c15](https://bsd-hardware.info/?probe=13fdaa7c15) | Feb 04, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [254e518190](https://bsd-hardware.info/?probe=254e518190) | Feb 03, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [cf41f72474](https://bsd-hardware.info/?probe=cf41f72474) | Jan 31, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [869d894f4f](https://bsd-hardware.info/?probe=869d894f4f) | Jan 30, 2021 |
| Dell          | Latitude 5480               | Notebook    | [9b38a72dd4](https://bsd-hardware.info/?probe=9b38a72dd4) | Jan 26, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [3e37c56f14](https://bsd-hardware.info/?probe=3e37c56f14) | Jan 23, 2021 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [fb318623f3](https://bsd-hardware.info/?probe=fb318623f3) | Jan 23, 2021 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [97a89d4eb0](https://bsd-hardware.info/?probe=97a89d4eb0) | Jan 23, 2021 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [806c954739](https://bsd-hardware.info/?probe=806c954739) | Jan 23, 2021 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | Notebook    | [3d18f3f8a9](https://bsd-hardware.info/?probe=3d18f3f8a9) | Jan 23, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [f6df3820b5](https://bsd-hardware.info/?probe=f6df3820b5) | Jan 18, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [3c41c474ad](https://bsd-hardware.info/?probe=3c41c474ad) | Jan 16, 2021 |
| Lenovo        | ThinkPad X380 Yoga 20LJ0... | Convertible | [9e58a182a8](https://bsd-hardware.info/?probe=9e58a182a8) | Jan 16, 2021 |
| MSI           | Z97 GAMING 5                | Desktop     | [9ef0da6093](https://bsd-hardware.info/?probe=9ef0da6093) | Jan 16, 2021 |
| HP            | OMEN by HP Laptop           | Notebook    | [14857eb6b7](https://bsd-hardware.info/?probe=14857eb6b7) | Jan 15, 2021 |
| ASUSTek       | X550LC                      | Notebook    | [f7c32488e9](https://bsd-hardware.info/?probe=f7c32488e9) | Jan 15, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [06cbb5cd5f](https://bsd-hardware.info/?probe=06cbb5cd5f) | Jan 15, 2021 |
| Dell          | Latitude 5280               | Notebook    | [c9bfb73262](https://bsd-hardware.info/?probe=c9bfb73262) | Jan 15, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [a9228fa7c3](https://bsd-hardware.info/?probe=a9228fa7c3) | Jan 15, 2021 |
| Dell          | 030VXY A01                  | Desktop     | [5af442bf61](https://bsd-hardware.info/?probe=5af442bf61) | Jan 15, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [a395c023bf](https://bsd-hardware.info/?probe=a395c023bf) | Jan 10, 2021 |
| Dell          | 0HY9JP A02                  | Desktop     | [b4d2af272e](https://bsd-hardware.info/?probe=b4d2af272e) | Jan 05, 2021 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [5124b24d30](https://bsd-hardware.info/?probe=5124b24d30) | Jan 04, 2021 |
| Dell          | Inspiron 5758               | Notebook    | [c096e37be5](https://bsd-hardware.info/?probe=c096e37be5) | Jan 03, 2021 |
| Fujitsu       | D3617-A1 S26361-D3617-A1    | Desktop     | [2a0187ef7a](https://bsd-hardware.info/?probe=2a0187ef7a) | Jan 02, 2021 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [5cd8e23152](https://bsd-hardware.info/?probe=5cd8e23152) | Dec 26, 2020 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [fdbd71db5e](https://bsd-hardware.info/?probe=fdbd71db5e) | Dec 26, 2020 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [c51c202b8d](https://bsd-hardware.info/?probe=c51c202b8d) | Dec 25, 2020 |
| ASUSTek       | PRIME A320M-C R2.0          | Desktop     | [4c24fe6fc4](https://bsd-hardware.info/?probe=4c24fe6fc4) | Dec 24, 2020 |
| HP            | 0B4Ch D                     | Desktop     | [bf0d7fe4f1](https://bsd-hardware.info/?probe=bf0d7fe4f1) | Dec 22, 2020 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | Desktop     | [a3a96da3fb](https://bsd-hardware.info/?probe=a3a96da3fb) | Dec 19, 2020 |
| Lenovo        | ThinkPad T450 20BV0064US    | Notebook    | [b397848c7e](https://bsd-hardware.info/?probe=b397848c7e) | Dec 16, 2020 |
| Toshiba       | Satellite C855              | Notebook    | [6bc78fc7fc](https://bsd-hardware.info/?probe=6bc78fc7fc) | Dec 16, 2020 |
| Panasonic     | CF-19AHNC8FN                | Notebook    | [04a42812bb](https://bsd-hardware.info/?probe=04a42812bb) | Dec 11, 2020 |
| Lenovo        | ThinkPad X220 42872VU       | Notebook    | [c843b5d271](https://bsd-hardware.info/?probe=c843b5d271) | Dec 10, 2020 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [464223cefe](https://bsd-hardware.info/?probe=464223cefe) | Dec 07, 2020 |
| Lenovo        | ThinkPad X380 Yoga 20LJ0... | Convertible | [a6b923675d](https://bsd-hardware.info/?probe=a6b923675d) | Dec 07, 2020 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [6c55fc2866](https://bsd-hardware.info/?probe=6c55fc2866) | Dec 05, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [53bf449015](https://bsd-hardware.info/?probe=53bf449015) | Dec 02, 2020 |
| Quanta        | 2AF5 011                    | Desktop     | [172f23efac](https://bsd-hardware.info/?probe=172f23efac) | Nov 29, 2020 |
| ASRock        | AB350 Gaming-ITX/ac         | Desktop     | [8afa16fc20](https://bsd-hardware.info/?probe=8afa16fc20) | Nov 29, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [5d5ecb38cd](https://bsd-hardware.info/?probe=5d5ecb38cd) | Nov 25, 2020 |
| MSI           | B450 GAMING PLUS            | Desktop     | [4cf3dd682b](https://bsd-hardware.info/?probe=4cf3dd682b) | Nov 24, 2020 |
| MSI           | B450 GAMING PLUS            | Desktop     | [edee76372b](https://bsd-hardware.info/?probe=edee76372b) | Nov 21, 2020 |
| Acer          | Aspire 7540                 | Notebook    | [65d215a03b](https://bsd-hardware.info/?probe=65d215a03b) | Nov 17, 2020 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [cc075b3932](https://bsd-hardware.info/?probe=cc075b3932) | Nov 15, 2020 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [6a0c640524](https://bsd-hardware.info/?probe=6a0c640524) | Nov 12, 2020 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [6060033216](https://bsd-hardware.info/?probe=6060033216) | Nov 12, 2020 |
| Apple         | MacBook6,1                  | Notebook    | [64b1b1910c](https://bsd-hardware.info/?probe=64b1b1910c) | Nov 01, 2020 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [dc33c84287](https://bsd-hardware.info/?probe=dc33c84287) | Oct 22, 2020 |
| Acer          | Aspire A315-42              | Notebook    | [1ac21e1660](https://bsd-hardware.info/?probe=1ac21e1660) | Oct 08, 2020 |
| Acer          | Aspire E1-532               | Notebook    | [10bff44534](https://bsd-hardware.info/?probe=10bff44534) | Oct 07, 2020 |
| HP            | Laptop 15-da0xxx            | Notebook    | [7faf1699d6](https://bsd-hardware.info/?probe=7faf1699d6) | Oct 04, 2020 |
| Fujitsu       | D2950-A1 S26361-D2950-A1    | Desktop     | [86e9866c03](https://bsd-hardware.info/?probe=86e9866c03) | Oct 02, 2020 |
| Fujitsu       | D2950-A1 S26361-D2950-A1    | Desktop     | [3b8f8a2033](https://bsd-hardware.info/?probe=3b8f8a2033) | Oct 02, 2020 |
| Lenovo        | ThinkPad T590 20N40016CD    | Notebook    | [1d9786ac9f](https://bsd-hardware.info/?probe=1d9786ac9f) | Aug 31, 2020 |
| Lenovo        | ThinkPad T590 20N40016CD    | Notebook    | [e505894bee](https://bsd-hardware.info/?probe=e505894bee) | Aug 29, 2020 |
| System76      | Lemur Pro                   | Notebook    | [0163d0f084](https://bsd-hardware.info/?probe=0163d0f084) | Aug 29, 2020 |
| Lenovo        | ThinkPad T430s 23539JM      | Notebook    | [facf6fa0f8](https://bsd-hardware.info/?probe=facf6fa0f8) | Aug 27, 2020 |
| ASUSTek       | K53SD                       | Notebook    | [975e9ccbe2](https://bsd-hardware.info/?probe=975e9ccbe2) | Aug 27, 2020 |
| Lenovo        | ThinkPad T530 239242U       | Notebook    | [7c8087322d](https://bsd-hardware.info/?probe=7c8087322d) | Aug 27, 2020 |
| Sony          | VGN-SZ3VWP_X                | Notebook    | [ace534d784](https://bsd-hardware.info/?probe=ace534d784) | Aug 10, 2020 |
| TUXEDO        | InfinityBook13V3            | Notebook    | [d508fb472b](https://bsd-hardware.info/?probe=d508fb472b) | Aug 10, 2020 |
| MSI           | H61M-P20                    | Desktop     | [fefac5637b](https://bsd-hardware.info/?probe=fefac5637b) | Aug 03, 2020 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [0073f8ff71](https://bsd-hardware.info/?probe=0073f8ff71) | Aug 02, 2020 |
| Gigabyte      | H67A-UD3H-B3                | Desktop     | [aa29eb9c75](https://bsd-hardware.info/?probe=aa29eb9c75) | Aug 01, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [b89da90904](https://bsd-hardware.info/?probe=b89da90904) | Aug 01, 2020 |
| Unknown       | SKYBAY                      | Desktop     | [34bb81770b](https://bsd-hardware.info/?probe=34bb81770b) | Jul 22, 2020 |
| ASRock        | X370 Gaming K4              | Desktop     | [4473708fd0](https://bsd-hardware.info/?probe=4473708fd0) | Jul 22, 2020 |
| ASRock        | X370 Gaming K4              | Desktop     | [174569bf55](https://bsd-hardware.info/?probe=174569bf55) | Jul 21, 2020 |
| ASRock        | A300M-STX                   | Desktop     | [f62a2ace5a](https://bsd-hardware.info/?probe=f62a2ace5a) | Jul 16, 2020 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [db7146b868](https://bsd-hardware.info/?probe=db7146b868) | Jul 14, 2020 |
| Dell          | Latitude E6420              | Notebook    | [324265fe3f](https://bsd-hardware.info/?probe=324265fe3f) | May 31, 2020 |
| Lenovo        | ThinkPad T430s 2352CTO      | Notebook    | [f4e8ffb5dc](https://bsd-hardware.info/?probe=f4e8ffb5dc) | May 27, 2020 |
| Lenovo        | ThinkPad T430s 2352CTO      | Notebook    | [59c5b6d6b9](https://bsd-hardware.info/?probe=59c5b6d6b9) | May 27, 2020 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 109       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| MATE             | 87        | 78.38%  |
| XFCE             | 15        | 13.51%  |
| KDE5             | 3         | 2.7%    |
| Metacity (Marco) | 2         | 1.8%    |
| openbox          | 1         | 0.9%    |
| i3               | 1         | 0.9%    |
| GNOME            | 1         | 0.9%    |
| Cinnamon         | 1         | 0.9%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 109       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 108       | 99.08%  |
| SDDM    | 1         | 0.92%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 50        | 44.25%  |
| Unknown | 28        | 24.78%  |
| C       | 11        | 9.73%   |
| de_DE   | 6         | 5.31%   |
| ru_RU   | 5         | 4.42%   |
| it_IT   | 2         | 1.77%   |
| fr_FR   | 2         | 1.77%   |
| en_GB   | 2         | 1.77%   |
| zh_CN   | 1         | 0.88%   |
| sk_SK   | 1         | 0.88%   |
| pt_BR   | 1         | 0.88%   |
| es_ES   | 1         | 0.88%   |
| en_NZ   | 1         | 0.88%   |
| en_AU   | 1         | 0.88%   |
| el_GR   | 1         | 0.88%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 78        | 71.56%  |
| BIOS | 31        | 28.44%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 102       | 92.73%  |
| Ufs  | 8         | 7.27%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 103       | 94.5%   |
| MBR  | 6         | 5.5%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 23        | 21.1%   |
| Dell                | 16        | 14.68%  |
| ASUSTek Computer    | 12        | 11.01%  |
| Hewlett-Packard     | 9         | 8.26%   |
| Acer                | 9         | 8.26%   |
| ASRock              | 7         | 6.42%   |
| MSI                 | 6         | 5.5%    |
| Gigabyte Technology | 6         | 5.5%    |
| Apple               | 3         | 2.75%   |
| Sony                | 2         | 1.83%   |
| Samsung Electronics | 2         | 1.83%   |
| Intel               | 2         | 1.83%   |
| Fujitsu             | 2         | 1.83%   |
| TUXEDO              | 1         | 0.92%   |
| Toshiba             | 1         | 0.92%   |
| System76            | 1         | 0.92%   |
| Quanta              | 1         | 0.92%   |
| Panasonic           | 1         | 0.92%   |
| Notebook            | 1         | 0.92%   |
| Jumper              | 1         | 0.92%   |
| Huanan              | 1         | 0.92%   |
| GPU Company         | 1         | 0.92%   |
| Unknown             | 1         | 0.92%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                                                  | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Dell Inspiron 3542                                                    | 3         | 2.75%   |
| MSI MS-7B86                                                           | 2         | 1.83%   |
| Lenovo ThinkPad T430s 2352CTO                                         | 2         | 1.83%   |
| Dell Latitude E6420                                                   | 2         | 1.83%   |
| TUXEDO InfinityBook13V3                                               | 1         | 0.92%   |
| Toshiba Satellite C855                                                | 1         | 0.92%   |
| System76 Lemur Pro                                                    | 1         | 0.92%   |
| Sony VGN-SZ3VWP_X                                                     | 1         | 0.92%   |
| Sony SVP1322M1EBI                                                     | 1         | 0.92%   |
| Samsung 550P5C/550P7C                                                 | 1         | 0.92%   |
| Samsung 3570R/370R/470R/450R/510R/4450RV                              | 1         | 0.92%   |
| Quanta 120-1333w                                                      | 1         | 0.92%   |
| Panasonic CF-19AHNC8FN                                                | 1         | 0.92%   |
| Notebook N85_N87,HJ,HJ1,HK1                                           | 1         | 0.92%   |
| MSI MS-7C36                                                           | 1         | 0.92%   |
| MSI MS-7917                                                           | 1         | 0.92%   |
| MSI MS-7817                                                           | 1         | 0.92%   |
| MSI MS-7788                                                           | 1         | 0.92%   |
| Lenovo Yoga 2 13 20344                                                | 1         | 0.92%   |
| Lenovo ThinkStation S10 6483CTO                                       | 1         | 0.92%   |
| Lenovo ThinkPad X380 Yoga 20LJ000WUK                                  | 1         | 0.92%   |
| Lenovo ThinkPad X250 20CM003WMS                                       | 1         | 0.92%   |
| Lenovo ThinkPad X220 42872VU                                          | 1         | 0.92%   |
| Lenovo ThinkPad X1 Yoga 3rd 20LDS1CG00                                | 1         | 0.92%   |
| Lenovo ThinkPad T590 20N40016CD                                       | 1         | 0.92%   |
| Lenovo ThinkPad T530 239242U                                          | 1         | 0.92%   |
| Lenovo ThinkPad T500 2056Y2Z                                          | 1         | 0.92%   |
| Lenovo ThinkPad T470 W10DG 20JNS0JU01                                 | 1         | 0.92%   |
| Lenovo ThinkPad T470 20HD000MUK                                       | 1         | 0.92%   |
| Lenovo ThinkPad T450 20BV0064US                                       | 1         | 0.92%   |
| Lenovo ThinkPad T440 20B7S1860W                                       | 1         | 0.92%   |
| Lenovo ThinkPad T430s 23539JM                                         | 1         | 0.92%   |
| Lenovo ThinkPad T430 2344C4U                                          | 1         | 0.92%   |
| Lenovo ThinkPad L512 44444XG                                          | 1         | 0.92%   |
| Lenovo ThinkCentre Edge72 3493DEG                                     | 1         | 0.92%   |
| Lenovo Legion Y7000P 81LD                                             | 1         | 0.92%   |
| Lenovo IdeaPad S145-15API 81UT                                        | 1         | 0.92%   |
| Lenovo IdeaPad 520-15IKB 81BF                                         | 1         | 0.92%   |
| Lenovo H515s 10126                                                    | 1         | 0.92%   |
| Jumper EZbook                                                         | 1         | 0.92%   |
| Intel NUC8i5BEH                                                       | 1         | 0.92%   |
| Intel NUC6i7KYB H90766-402                                            | 1         | 0.92%   |
| Huanan X79 INTEL (INTEL Xeon E5/Corei7 DMI2 - C600/C200 Cipset V2.49P | 1         | 0.92%   |
| HP Z400 Workstation                                                   | 1         | 0.92%   |
| HP Pavilion x360 Convertible                                          | 1         | 0.92%   |
| HP Pavilion g6                                                        | 1         | 0.92%   |
| HP OMEN by HP Laptop                                                  | 1         | 0.92%   |
| HP Laptop 15-db0xxx                                                   | 1         | 0.92%   |
| HP Laptop 15-da0xxx                                                   | 1         | 0.92%   |
| HP Laptop 14-dk0xxx                                                   | 1         | 0.92%   |
| HP Compaq Pro 6305 SFF                                                | 1         | 0.92%   |
| HP 255 G7 Notebook PC                                                 | 1         | 0.92%   |
| GPU Company GWTN156-5                                                 | 1         | 0.92%   |
| Gigabyte Z97-D3H                                                      | 1         | 0.92%   |
| Gigabyte Z370 AORUS Ultra Gaming                                      | 1         | 0.92%   |
| Gigabyte X470 AORUS ULTRA GAMING                                      | 1         | 0.92%   |
| Gigabyte H67A-UD3H-B3                                                 | 1         | 0.92%   |
| Gigabyte F2A68HM-DS2                                                  | 1         | 0.92%   |
| Gigabyte EG43M-S2H                                                    | 1         | 0.92%   |
| Fujitsu ESPRIMO P1500                                                 | 1         | 0.92%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 16        | 14.68%  |
| Acer Aspire             | 8         | 7.34%   |
| Dell Latitude           | 7         | 6.42%   |
| ASUS PRIME              | 5         | 4.59%   |
| Dell OptiPlex           | 4         | 3.67%   |
| Dell Inspiron           | 4         | 3.67%   |
| HP Laptop               | 3         | 2.75%   |
| MSI MS-7B86             | 2         | 1.83%   |
| Lenovo IdeaPad          | 2         | 1.83%   |
| HP Pavilion             | 2         | 1.83%   |
| ASUS TUF                | 2         | 1.83%   |
| ASRock X570             | 2         | 1.83%   |
| TUXEDO InfinityBook13V3 | 1         | 0.92%   |
| Toshiba Satellite       | 1         | 0.92%   |
| System76 Lemur          | 1         | 0.92%   |
| Sony VGN-SZ3VWP         | 1         | 0.92%   |
| Sony SVP1322M1EBI       | 1         | 0.92%   |
| Samsung 550P5C          | 1         | 0.92%   |
| Samsung 3570R           | 1         | 0.92%   |
| Quanta 120-1333w        | 1         | 0.92%   |
| Panasonic CF-19AHNC8FN  | 1         | 0.92%   |
| Notebook N85            | 1         | 0.92%   |
| MSI MS-7C36             | 1         | 0.92%   |
| MSI MS-7917             | 1         | 0.92%   |
| MSI MS-7817             | 1         | 0.92%   |
| MSI MS-7788             | 1         | 0.92%   |
| Lenovo Yoga             | 1         | 0.92%   |
| Lenovo ThinkStation     | 1         | 0.92%   |
| Lenovo ThinkCentre      | 1         | 0.92%   |
| Lenovo Legion           | 1         | 0.92%   |
| Lenovo H515s            | 1         | 0.92%   |
| Jumper EZbook           | 1         | 0.92%   |
| Intel NUC8i5BEH         | 1         | 0.92%   |
| Intel NUC6i7KYB         | 1         | 0.92%   |
| Huanan X79              | 1         | 0.92%   |
| HP Z400                 | 1         | 0.92%   |
| HP OMEN                 | 1         | 0.92%   |
| HP Compaq               | 1         | 0.92%   |
| HP 255                  | 1         | 0.92%   |
| GPU Company GWTN156-5   | 1         | 0.92%   |
| Gigabyte Z97-D3H        | 1         | 0.92%   |
| Gigabyte Z370           | 1         | 0.92%   |
| Gigabyte X470           | 1         | 0.92%   |
| Gigabyte H67A-UD3H-B3   | 1         | 0.92%   |
| Gigabyte F2A68HM-DS2    | 1         | 0.92%   |
| Gigabyte EG43M-S2H      | 1         | 0.92%   |
| Fujitsu ESPRIMO         | 1         | 0.92%   |
| Fujitsu CELSIUS         | 1         | 0.92%   |
| Dell Precision          | 1         | 0.92%   |
| ASUS Z170I              | 1         | 0.92%   |
| ASUS X550LC             | 1         | 0.92%   |
| ASUS ROG                | 1         | 0.92%   |
| ASUS MINIPC             | 1         | 0.92%   |
| ASUS K53SD              | 1         | 0.92%   |
| ASRock Z77              | 1         | 0.92%   |
| ASRock X370             | 1         | 0.92%   |
| ASRock B450             | 1         | 0.92%   |
| ASRock AB350            | 1         | 0.92%   |
| ASRock A300M-STX        | 1         | 0.92%   |
| Apple MacBookPro5       | 1         | 0.92%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 17        | 15.6%   |
| 2018 | 14        | 12.84%  |
| 2013 | 11        | 10.09%  |
| 2019 | 10        | 9.17%   |
| 2014 | 10        | 9.17%   |
| 2012 | 9         | 8.26%   |
| 2017 | 7         | 6.42%   |
| 2015 | 7         | 6.42%   |
| 2011 | 6         | 5.5%    |
| 2009 | 5         | 4.59%   |
| 2016 | 4         | 3.67%   |
| 2008 | 4         | 3.67%   |
| 2010 | 3         | 2.75%   |
| 2021 | 1         | 0.92%   |
| 2007 | 1         | 0.92%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 58        | 53.21%  |
| Desktop     | 45        | 41.28%  |
| Convertible | 3         | 2.75%   |
| Mini pc     | 3         | 2.75%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 108       | 99.08%  |
| Yes  | 1         | 0.92%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 45        | 41.28%  |
| 16.01-24.0  | 29        | 26.61%  |
| 4.01-8.0    | 20        | 18.35%  |
| 32.01-64.0  | 9         | 8.26%   |
| 24.01-32.0  | 3         | 2.75%   |
| 64.01-256.0 | 2         | 1.83%   |
| 2.01-3.0    | 1         | 0.92%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.51-1.0 | 50        | 45.45%  |
| 0.01-0.5 | 43        | 39.09%  |
| 1.01-2.0 | 9         | 8.18%   |
| 2.01-3.0 | 6         | 5.45%   |
| 3.01-4.0 | 2         | 1.82%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 63        | 57.27%  |
| 2      | 31        | 28.18%  |
| 3      | 4         | 3.64%   |
| 5      | 3         | 2.73%   |
| 4      | 3         | 2.73%   |
| 0      | 3         | 2.73%   |
| 6      | 2         | 1.82%   |
| 7      | 1         | 0.91%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 66        | 60.55%  |
| Yes       | 43        | 39.45%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 101       | 92.66%  |
| No        | 8         | 7.34%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 78        | 71.56%  |
| No        | 31        | 28.44%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 58        | 53.21%  |
| No        | 51        | 46.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 24        | 22.02%  |
| Germany     | 11        | 10.09%  |
| France      | 10        | 9.17%   |
| UK          | 9         | 8.26%   |
| Russia      | 8         | 7.34%   |
| Switzerland | 4         | 3.67%   |
| Spain       | 4         | 3.67%   |
| Poland      | 4         | 3.67%   |
| Norway      | 3         | 2.75%   |
| New Zealand | 3         | 2.75%   |
| Finland     | 3         | 2.75%   |
| Ukraine     | 2         | 1.83%   |
| Philippines | 2         | 1.83%   |
| Japan       | 2         | 1.83%   |
| Italy       | 2         | 1.83%   |
| Australia   | 2         | 1.83%   |
| UAE         | 1         | 0.92%   |
| Sweden      | 1         | 0.92%   |
| Serbia      | 1         | 0.92%   |
| Portugal    | 1         | 0.92%   |
| Netherlands | 1         | 0.92%   |
| Namibia     | 1         | 0.92%   |
| Malaysia    | 1         | 0.92%   |
| Luxembourg  | 1         | 0.92%   |
| Hungary     | 1         | 0.92%   |
| Hong Kong   | 1         | 0.92%   |
| Greece      | 1         | 0.92%   |
| Egypt       | 1         | 0.92%   |
| Czechia     | 1         | 0.92%   |
| Canada      | 1         | 0.92%   |
| Brazil      | 1         | 0.92%   |
| Argentina   | 1         | 0.92%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City            | Computers | Percent |
|-----------------|-----------|---------|
| Paris           | 3         | 2.7%    |
| London          | 3         | 2.7%    |
| Franconville    | 3         | 2.7%    |
| Chrusty         | 3         | 2.7%    |
| Berlin          | 3         | 2.7%    |
| Richmond        | 2         | 1.8%    |
| Oslo            | 2         | 1.8%    |
| Obninsk         | 2         | 1.8%    |
| Kyiv            | 2         | 1.8%    |
| JyvГ¤skylГ¤ | 2         | 1.8%    |
| Hamilton        | 2         | 1.8%    |
| Giessen         | 2         | 1.8%    |
| Eiken           | 2         | 1.8%    |
| Cologne         | 2         | 1.8%    |
| Clemmons        | 2         | 1.8%    |
| Atascadero      | 2         | 1.8%    |
| ЕЊta-ku       | 1         | 0.9%    |
| Zurich          | 1         | 0.9%    |
| Yokohama        | 1         | 0.9%    |
| Yaroslavl       | 1         | 0.9%    |
| Whittier        | 1         | 0.9%    |
| Wenatchee       | 1         | 0.9%    |
| Washington      | 1         | 0.9%    |
| Vidnoye         | 1         | 0.9%    |
| Veenendaal      | 1         | 0.9%    |
| Truro           | 1         | 0.9%    |
| Taita           | 1         | 0.9%    |
| Sydney          | 1         | 0.9%    |
| Swindon         | 1         | 0.9%    |
| Stiring-Wendel  | 1         | 0.9%    |
| St Petersburg   | 1         | 0.9%    |
| Sollentuna      | 1         | 0.9%    |
| Santo Tomas     | 1         | 0.9%    |
| Salem           | 1         | 0.9%    |
| Rome            | 1         | 0.9%    |
| Rochester       | 1         | 0.9%    |
| Riedstadt       | 1         | 0.9%    |
| Resistencia     | 1         | 0.9%    |
| Prague          | 1         | 0.9%    |
| Phoenix         | 1         | 0.9%    |
| Peoria          | 1         | 0.9%    |
| Palm Bay        | 1         | 0.9%    |
| Oshakati        | 1         | 0.9%    |
| Omaha           | 1         | 0.9%    |
| Moscow          | 1         | 0.9%    |
| Moncton         | 1         | 0.9%    |
| Milan           | 1         | 0.9%    |
| Marysville      | 1         | 0.9%    |
| Makati City     | 1         | 0.9%    |
| Madrid          | 1         | 0.9%    |
| Luxembourg      | 1         | 0.9%    |
| Lutz            | 1         | 0.9%    |
| Lorient         | 1         | 0.9%    |
| Lenzburg        | 1         | 0.9%    |
| Larnod          | 1         | 0.9%    |
| Kuala Lumpur    | 1         | 0.9%    |
| Krasnoyarsk     | 1         | 0.9%    |
| Huntingdon      | 1         | 0.9%    |
| Huddersfield    | 1         | 0.9%    |
| Heilbronn       | 1         | 0.9%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 34        | 46     | 20.86%  |
| WDC                 | 31        | 39     | 19.02%  |
| Seagate             | 17        | 23     | 10.43%  |
| Crucial             | 11        | 13     | 6.75%   |
| Toshiba             | 10        | 12     | 6.13%   |
| SanDisk             | 9         | 9      | 5.52%   |
| Kingston            | 8         | 8      | 4.91%   |
| Hitachi             | 7         | 7      | 4.29%   |
| Micron Technology   | 4         | 4      | 2.45%   |
| PNY                 | 3         | 5      | 1.84%   |
| HGST                | 3         | 3      | 1.84%   |
| A-DATA Technology   | 3         | 3      | 1.84%   |
| SK hynix            | 2         | 2      | 1.23%   |
| Plextor             | 2         | 2      | 1.23%   |
| Patriot             | 2         | 2      | 1.23%   |
| Maxtor              | 2         | 2      | 1.23%   |
| Gigabyte Technology | 2         | 2      | 1.23%   |
| Transcend           | 1         | 1      | 0.61%   |
| SPCC                | 1         | 1      | 0.61%   |
| Phison              | 1         | 2      | 0.61%   |
| OCZ                 | 1         | 1      | 0.61%   |
| Netac               | 1         | 1      | 0.61%   |
| LITEONIT            | 1         | 1      | 0.61%   |
| LDLC                | 1         | 1      | 0.61%   |
| KingSpec            | 1         | 1      | 0.61%   |
| Intel               | 1         | 1      | 0.61%   |
| HPT                 | 1         | 4      | 0.61%   |
| Goodram             | 1         | 1      | 0.61%   |
| Fujitsu             | 1         | 1      | 0.61%   |
| AMD                 | 1         | 1      | 0.61%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung SSD 860 QVO 1TB              | 5         | 2.86%   |
| Samsung SSD 850 EVO 250GB            | 3         | 1.71%   |
| WDC WDS240G2G0A-00JH30 240GB         | 2         | 1.14%   |
| WDC WD40EFRX-68N32N0 4TB             | 2         | 1.14%   |
| WDC WD2000JS-55MHB0 192GB            | 2         | 1.14%   |
| WDC WD10EZEX-21M2NA0 1TB             | 2         | 1.14%   |
| Toshiba Q300 480GB                   | 2         | 1.14%   |
| Toshiba HDWD120 2TB                  | 2         | 1.14%   |
| Seagate ST500DM002-1BD142 500GB      | 2         | 1.14%   |
| Seagate ST1000LM049-2GH172 1TB       | 2         | 1.14%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 1.14%   |
| Samsung SSD 970 EVO 250GB            | 2         | 1.14%   |
| Samsung SSD 860 EVO 500GB            | 2         | 1.14%   |
| Micron 1100 SATA 256GB               | 2         | 1.14%   |
| Maxtor STM3320613AS 320GB            | 2         | 1.14%   |
| Gigabyte GP-GSM2NE3100TNTD 1TB       | 2         | 1.14%   |
| Crucial CT250MX500SSD1 250GB         | 2         | 1.14%   |
| Crucial CT1000MX500SSD1 1TB          | 2         | 1.14%   |
| WDC WDS500G2B0A-00SM50 500GB         | 1         | 0.57%   |
| WDC WDS500G2B0A 500GB                | 1         | 0.57%   |
| WDC WDS120G2G0A-00JH30 120GB         | 1         | 0.57%   |
| WDC WDS100T3X0C-00SJG0 1TB           | 1         | 0.57%   |
| WDC WDS100T2B0C-00PXH0 1TB           | 1         | 0.57%   |
| WDC WDS100T1X0E-00AFY0 1TB           | 1         | 0.57%   |
| WDC WDS100T1B0A-00H9H0 1TB           | 1         | 0.57%   |
| WDC WD800BEVT-75ZCT2 80GB            | 1         | 0.57%   |
| WDC WD7500BPVT-80HXZT3 752GB         | 1         | 0.57%   |
| WDC WD6400BEVT-22A0RT0 640GB         | 1         | 0.57%   |
| WDC WD60EZRZ-00GZ5B1 6TB             | 1         | 0.57%   |
| WDC WD6003FFBX-68MU3N0 6TB           | 1         | 0.57%   |
| WDC WD5000LPLX-75ZNTT0 500GB         | 1         | 0.57%   |
| WDC WD5000AAVS-00ZTB0 500GB          | 1         | 0.57%   |
| WDC WD5000AAKX-60U6AA0 500GB         | 1         | 0.57%   |
| WDC WD5000AAKX-00ERMA0 500GB         | 1         | 0.57%   |
| WDC WD5000AAKS-60WWPA0 500GB         | 1         | 0.57%   |
| WDC WD3200LPVX-75V0TT0 320GB         | 1         | 0.57%   |
| WDC WD2500AAJS-75M0A0 250GB          | 1         | 0.57%   |
| WDC WD20SPZX-22UA7T0 2TB             | 1         | 0.57%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 1         | 0.57%   |
| WDC WD10SPZX-21Z10T0 1TB             | 1         | 0.57%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.57%   |
| WDC WD10EALX-009BA0 1TB              | 1         | 0.57%   |
| WDC PC SN520 SDAPMUW-128G-1101 128GB | 1         | 0.57%   |
| Transcend TS120GMTS820S 120GB        | 1         | 0.57%   |
| Toshiba THNSF5256GPUK 256GB          | 1         | 0.57%   |
| Toshiba RD400 256GB                  | 1         | 0.57%   |
| Toshiba MQ04ABF100 1TB               | 1         | 0.57%   |
| Toshiba MQ01ACF032 320GB             | 1         | 0.57%   |
| Toshiba MQ01ABD100 1TB               | 1         | 0.57%   |
| Toshiba KXG5AZNV256G 256GB           | 1         | 0.57%   |
| SPCC Solid State Disk 240GB          | 1         | 0.57%   |
| SK hynix SC311 SATA 512GB            | 1         | 0.57%   |
| SK hynix HFM256GDJTNG-8310A 256GB    | 1         | 0.57%   |
| Seagate ST9250410AS 250GB            | 1         | 0.57%   |
| Seagate ST500LM030-2E717D 500GB      | 1         | 0.57%   |
| Seagate ST500LM021-1KJ152 500GB      | 1         | 0.57%   |
| Seagate ST3500312CS 500GB            | 1         | 0.57%   |
| Seagate ST31500541AS 1.5TB           | 1         | 0.57%   |
| Seagate ST31000528AS 1TB             | 1         | 0.57%   |
| Seagate ST2000NM0008-2F3100 2TB      | 1         | 0.57%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 23        | 29     | 35.94%  |
| Seagate             | 17        | 23     | 26.56%  |
| Hitachi             | 7         | 7      | 10.94%  |
| Toshiba             | 5         | 5      | 7.81%   |
| Samsung Electronics | 5         | 6      | 7.81%   |
| HGST                | 3         | 3      | 4.69%   |
| Maxtor              | 2         | 2      | 3.13%   |
| HPT                 | 1         | 4      | 1.56%   |
| Fujitsu             | 1         | 1      | 1.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 22        | 29     | 27.85%  |
| Crucial             | 10        | 12     | 12.66%  |
| SanDisk             | 9         | 9      | 11.39%  |
| Kingston            | 7         | 7      | 8.86%   |
| WDC                 | 6         | 6      | 7.59%   |
| Micron Technology   | 4         | 4      | 5.06%   |
| PNY                 | 3         | 5      | 3.8%    |
| A-DATA Technology   | 3         | 3      | 3.8%    |
| Toshiba             | 2         | 2      | 2.53%   |
| Plextor             | 2         | 2      | 2.53%   |
| Patriot             | 2         | 2      | 2.53%   |
| Transcend           | 1         | 1      | 1.27%   |
| SPCC                | 1         | 1      | 1.27%   |
| SK hynix            | 1         | 1      | 1.27%   |
| OCZ                 | 1         | 1      | 1.27%   |
| Netac               | 1         | 1      | 1.27%   |
| LITEONIT            | 1         | 1      | 1.27%   |
| KingSpec            | 1         | 1      | 1.27%   |
| Goodram             | 1         | 1      | 1.27%   |
| AMD                 | 1         | 1      | 1.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 62        | 90     | 44.6%   |
| HDD  | 52        | 80     | 37.41%  |
| NVMe | 25        | 29     | 17.99%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 97        | 170    | 79.51%  |
| NVMe | 25        | 29     | 20.49%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 71        | 91     | 57.26%  |
| 0.51-1.0   | 35        | 53     | 28.23%  |
| 1.01-2.0   | 10        | 13     | 8.06%   |
| 3.01-4.0   | 4         | 4      | 3.23%   |
| 4.01-10.0  | 3         | 7      | 2.42%   |
| 2.01-3.0   | 1         | 2      | 0.81%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 33        | 29.46%  |
| 251-500    | 24        | 21.43%  |
| 1-20       | 23        | 20.54%  |
| 501-1000   | 11        | 9.82%   |
| 51-100     | 11        | 9.82%   |
| Unknown    | 8         | 7.14%   |
| 21-50      | 1         | 0.89%   |
| 1001-2000  | 1         | 0.89%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 95        | 84.82%  |
| 21-50   | 9         | 8.04%   |
| Unknown | 8         | 7.14%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                           | Computers | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| Maxtor STM3320613AS 320GB                       | 2         | 2      | 11.76%  |
| WDC WD6400BEVT-22A0RT0 640GB                    | 1         | 1      | 5.88%   |
| WDC WD5000AAKS-60WWPA0 500GB                    | 1         | 1      | 5.88%   |
| WDC WD3200LPVX-75V0TT0 320GB                    | 1         | 1      | 5.88%   |
| WDC WD10EZEX-21M2NA0 1TB                        | 1         | 1      | 5.88%   |
| Toshiba MQ01ACF032 320GB                        | 1         | 1      | 5.88%   |
| Seagate ST500LM021-1KJ152 500GB                 | 1         | 1      | 5.88%   |
| Seagate ST500DM002-1BD142 500GB                 | 1         | 1      | 5.88%   |
| Seagate ST31500541AS 1.5TB                      | 1         | 1      | 5.88%   |
| Samsung Electronics MZNTE128HMGR-000SO 128GB    | 1         | 1      | 5.88%   |
| Samsung Electronics HD103SJ 1TB                 | 1         | 2      | 5.88%   |
| OCZ AGILITY3 240GB                              | 1         | 1      | 5.88%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB | 1         | 1      | 5.88%   |
| Hitachi HTS547575A9E384 752GB                   | 1         | 1      | 5.88%   |
| Hitachi HTS543225L9A300 250GB                   | 1         | 1      | 5.88%   |
| Hitachi HTS541680J9SA00 80GB                    | 1         | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 23.53%  |
| Seagate             | 3         | 3      | 17.65%  |
| Hitachi             | 3         | 3      | 17.65%  |
| Samsung Electronics | 2         | 3      | 11.76%  |
| Maxtor              | 2         | 2      | 11.76%  |
| Toshiba             | 1         | 1      | 5.88%   |
| OCZ                 | 1         | 1      | 5.88%   |
| Micron Technology   | 1         | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 28.57%  |
| Seagate             | 3         | 3      | 21.43%  |
| Hitachi             | 3         | 3      | 21.43%  |
| Maxtor              | 2         | 2      | 14.29%  |
| Toshiba             | 1         | 1      | 7.14%   |
| Samsung Electronics | 1         | 2      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 15     | 81.25%  |
| SSD  | 3         | 3      | 18.75%  |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 99        | 177    | 85.34%  |
| Malfunc  | 16        | 18     | 13.79%  |
| Detected | 1         | 4      | 0.86%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 68        | 50.37%  |
| AMD                           | 33        | 24.44%  |
| Samsung Electronics           | 11        | 8.15%   |
| Nvidia                        | 4         | 2.96%   |
| SanDisk                       | 3         | 2.22%   |
| Phison Electronics            | 3         | 2.22%   |
| Toshiba                       | 2         | 1.48%   |
| ASMedia Technology            | 2         | 1.48%   |
| SK hynix                      | 1         | 0.74%   |
| Silicon Motion                | 1         | 0.74%   |
| OCZ Technology Group          | 1         | 0.74%   |
| Micron/Crucial Technology     | 1         | 0.74%   |
| Marvell Technology Group      | 1         | 0.74%   |
| Kingston Technology Company   | 1         | 0.74%   |
| Integrated Technology Express | 1         | 0.74%   |
| HighPoint Technologies        | 1         | 0.74%   |
| Adaptec                       | 1         | 0.74%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 27        | 17.76%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 9         | 5.92%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 8         | 5.26%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 8         | 5.26%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 8         | 5.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 7         | 4.61%   |
| AMD 400 Series Chipset SATA Controller                                                  | 6         | 3.95%   |
| Intel SATA Controller [RAID mode]                                                       | 5         | 3.29%   |
| Nvidia MCP79 AHCI Controller                                                            | 3         | 1.97%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 3         | 1.97%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 3         | 1.97%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 3         | 1.97%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3         | 1.97%   |
| Phison PS5013 E13 NVMe Controller                                                       | 2         | 1.32%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 2         | 1.32%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 2         | 1.32%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2         | 1.32%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2         | 1.32%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 2         | 1.32%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 2         | 1.32%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 2         | 1.32%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.32%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.32%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2         | 1.32%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2         | 1.32%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2         | 1.32%   |
| AMD FCH SATA Controller D                                                               | 2         | 1.32%   |
| Toshiba XG4 NVMe SSD Controller                                                         | 1         | 0.66%   |
| Toshiba unknown                                                                         | 1         | 0.66%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 1         | 0.66%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1         | 0.66%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 1         | 0.66%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1         | 0.66%   |
| SanDisk PC SN520 NVMe SSD                                                               | 1         | 0.66%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1         | 0.66%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1         | 0.66%   |
| Phison E12 NVMe Controller                                                              | 1         | 0.66%   |
| OCZ Group RD400/400A SSD                                                                | 1         | 0.66%   |
| Nvidia GeForce 7100/nForce 630i SATA                                                    | 1         | 0.66%   |
| Micron/Crucial NVMe Controller                                                          | 1         | 0.66%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 1         | 0.66%   |
| Kingston Company A2000 NVMe SSD                                                         | 1         | 0.66%   |
| Intel SSD 660P Series                                                                   | 1         | 0.66%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1         | 0.66%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1         | 0.66%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1         | 0.66%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 1         | 0.66%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 1         | 0.66%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1         | 0.66%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1         | 0.66%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1         | 0.66%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 1         | 0.66%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1         | 0.66%   |
| Integrated Express IT8213 IDE Controller                                                | 1         | 0.66%   |
| HighPoint RocketRAID 230x 4 Port SATA-II Controller                                     | 1         | 0.66%   |
| AMD X370 Series Chipset SATA Controller                                                 | 1         | 0.66%   |
| AMD 500 Series Chipset SATA Controller                                                  | 1         | 0.66%   |
| Adaptec AIC-7850T/7856T [AVA-2902/4/6 / AHA-2910]                                       | 1         | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 89        | 66.92%  |
| NVMe | 25        | 18.8%   |
| IDE  | 9         | 6.77%   |
| RAID | 8         | 6.02%   |
| SCSI | 2         | 1.5%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 76        | 69.72%  |
| AMD    | 33        | 30.28%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz            | 3         | 2.75%   |
| Intel Core i5-3320M CPU @ 2.60GHz            | 3         | 2.75%   |
| AMD Ryzen 7 3700X 8-Core Processor           | 3         | 2.75%   |
| AMD Ryzen 7 2700X Eight-Core Processor       | 3         | 2.75%   |
| AMD Ryzen 5 2600 Six-Core Processor          | 3         | 2.75%   |
| Intel Core i7-3520M CPU @ 2.90GHz            | 2         | 1.83%   |
| Intel Core i5-8350U CPU @ 1.70GHz            | 2         | 1.83%   |
| Intel Core i5-6300U CPU @ 2.40GHz            | 2         | 1.83%   |
| Intel Core i5-5300U CPU @ 2.30GHz            | 2         | 1.83%   |
| Intel Core i5-3230M CPU @ 2.60GHz            | 2         | 1.83%   |
| Intel Core i5-2520M CPU @ 2.50GH             | 2         | 1.83%   |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz         | 2         | 1.83%   |
| AMD A4-9125 RADEON R3, 4 COMPUTE CORES 2C+2G | 2         | 1.83%   |
| Intel Xeon CPU W3680 @ 3.33GHz               | 1         | 0.92%   |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz           | 1         | 0.92%   |
| Intel Xeon                                   | 1         | 0.92%   |
| Intel Unknown                                | 1         | 0.92%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz  | 1         | 0.92%   |
| Intel Pentium CPU G620 @ 2.60GHz             | 1         | 0.92%   |
| Intel Pentium 3558U @ 1.70GHz                | 1         | 0.92%   |
| Intel Genuine CPU                            | 1         | 0.92%   |
| Intel Core i7-8700 CPU @ 3.20GHz             | 1         | 0.92%   |
| Intel Core i7-8565U CPU @ 1.80GHz            | 1         | 0.92%   |
| Intel Core i7-8550U CPU @ 1.80GHz            | 1         | 0.92%   |
| Intel Core i7-6770HQ CPU @ 2.60GHz           | 1         | 0.92%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz           | 1         | 0.92%   |
| Intel Core i7-6500U CPU @ 2.50GHz            | 1         | 0.92%   |
| Intel Core i7-4790K CPU @ 4.00GHz            | 1         | 0.92%   |
| Intel Core i7-4500U CPU @ 1.80GHz            | 1         | 0.92%   |
| Intel Core i7-3770S CPU @ 3.10GHz            | 1         | 0.92%   |
| Intel Core i7-3770 CPU @ 3.40GHz             | 1         | 0.92%   |
| Intel Core i7-3720QM CPU @ 2.60GHz           | 1         | 0.92%   |
| Intel Core i7-3630QM CPU @ 2.40GHz           | 1         | 0.92%   |
| Intel Core i7-2670QM CPU @ 2.20GHz           | 1         | 0.92%   |
| Intel Core i7-2600K CPU                      | 1         | 0.92%   |
| Intel Core i5-8600K CPU @ 3.60GHz            | 1         | 0.92%   |
| Intel Core i5-8400T CPU @ 1.70GHz            | 1         | 0.92%   |
| Intel Core i5-8300H CPU @ 2.30GHz            | 1         | 0.92%   |
| Intel Core i5-8259U CPU @ 2.30GHz            | 1         | 0.92%   |
| Intel Core i5-8250U CPU @ 1.60GHz            | 1         | 0.92%   |
| Intel Core i5-7500 CPU @ 3.40GHz             | 1         | 0.92%   |
| Intel Core i5-7300U CPU @ 2.60GHz            | 1         | 0.92%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz           | 1         | 0.92%   |
| Intel Core i5-6600K CPU @ 3.50GHz            | 1         | 0.92%   |
| Intel Core i5-5200U CPU @ 2.20GHz            | 1         | 0.92%   |
| Intel Core i5-4570 CPU @ 3.20GHz             | 1         | 0.92%   |
| Intel Core i5-4440 CPU @ 3.10GHz             | 1         | 0.92%   |
| Intel Core i5-4310U CPU @ 2.00GHz            | 1         | 0.92%   |
| Intel Core i5-4300U CPU @ 1.90GHz            | 1         | 0.92%   |
| Intel Core i5-4210U CPU @ 1.70GHz            | 1         | 0.92%   |
| Intel Core i5-4200U CPU @ 1.60GHz            | 1         | 0.92%   |
| Intel Core i5-2520M CPU @ 2.50GHz            | 1         | 0.92%   |
| Intel Core i5-2500 CPU @ 3.30GH              | 1         | 0.92%   |
| Intel Core i5-2430M CPU @ 2.40GH             | 1         | 0.92%   |
| Intel Core i5-2410M CPU @ 2.30GHz            | 1         | 0.92%   |
| Intel Core i5-10210U CPU @ 1.60GHz           | 1         | 0.92%   |
| Intel Core i3-7100U CPU @ 2.40GHz            | 1         | 0.92%   |
| Intel Core i3-4160 CPU @ 3.60GHz             | 1         | 0.92%   |
| Intel Core i3-4010U CPU @ 1.70GHz            | 1         | 0.92%   |
| Intel Core i3-4005U CPU @ 1.70GHz            | 1         | 0.92%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 37        | 33.94%  |
| Intel Core i7           | 16        | 14.68%  |
| AMD Ryzen 5             | 9         | 8.26%   |
| AMD Ryzen 7             | 7         | 6.42%   |
| Intel Core i3           | 5         | 4.59%   |
| Intel Core 2 Duo        | 5         | 4.59%   |
| AMD Ryzen 3             | 4         | 3.67%   |
| Intel Xeon              | 3         | 2.75%   |
| AMD A6                  | 3         | 2.75%   |
| Other                   | 2         | 1.83%   |
| Intel Pentium           | 2         | 1.83%   |
| Intel Core 2 Quad       | 2         | 1.83%   |
| Intel Celeron           | 2         | 1.83%   |
| AMD E1                  | 2         | 1.83%   |
| AMD A4                  | 2         | 1.83%   |
| Intel Pentium Dual-Core | 1         | 0.92%   |
| Intel Genuine           | 1         | 0.92%   |
| Intel Core 2            | 1         | 0.92%   |
| AMD Ryzen 9             | 1         | 0.92%   |
| AMD Ryzen 3 PRO         | 1         | 0.92%   |
| AMD E2                  | 1         | 0.92%   |
| AMD Athlon X4           | 1         | 0.92%   |
| AMD A10                 | 1         | 0.92%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 46        | 42.2%   |
| 4       | 32        | 29.36%  |
| Unknown | 7         | 6.42%   |
| 16      | 6         | 5.5%    |
| 12      | 6         | 5.5%    |
| 8       | 6         | 5.5%    |
| 6       | 5         | 4.59%   |
| 32      | 1         | 0.92%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 106       | 97.25%  |
| 2      | 3         | 2.75%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 53        | 48.62%  |
| 1       | 49        | 44.95%  |
| Unknown | 7         | 6.42%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 18        | 16.51%  |
| Haswell     | 13        | 11.93%  |
| SandyBridge | 11        | 10.09%  |
| IvyBridge   | 11        | 10.09%  |
| Zen+        | 10        | 9.17%   |
| Penryn      | 10        | 9.17%   |
| Zen 2       | 8         | 7.34%   |
| Skylake     | 6         | 5.5%    |
| Zen         | 3         | 2.75%   |
| Excavator   | 3         | 2.75%   |
| Broadwell   | 3         | 2.75%   |
| Westmere    | 2         | 1.83%   |
| Puma        | 2         | 1.83%   |
| Piledriver  | 2         | 1.83%   |
| Zen 3       | 1         | 0.92%   |
| K10 Llano   | 1         | 0.92%   |
| K10         | 1         | 0.92%   |
| Jaguar      | 1         | 0.92%   |
| Goldmont    | 1         | 0.92%   |
| Core        | 1         | 0.92%   |
| Bobcat      | 1         | 0.92%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 60        | 48.78%  |
| Nvidia | 40        | 32.52%  |
| AMD    | 23        | 18.7%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 10        | 7.94%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 9         | 7.14%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 9         | 7.14%   |
| Intel HD Graphics 620                                                         | 5         | 3.97%   |
| Intel UHD Graphics 620                                                        | 4         | 3.17%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 4         | 3.17%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 3         | 2.38%   |
| Nvidia GM206 [GeForce GTX 960]                                                | 3         | 2.38%   |
| Nvidia GK107 [GeForce GTX 650]                                                | 3         | 2.38%   |
| Nvidia C79 [GeForce 9400M]                                                    | 3         | 2.38%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 3         | 2.38%   |
| Intel HD Graphics 5500                                                        | 3         | 2.38%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 3         | 2.38%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 2         | 1.59%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                            | 2         | 1.59%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                             | 2         | 1.59%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 2         | 1.59%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                        | 2         | 1.59%   |
| Intel HD Graphics 630                                                         | 2         | 1.59%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                      | 2         | 1.59%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                            | 1         | 0.79%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                         | 1         | 0.79%   |
| Nvidia TU104 [GeForce RTX 2080]                                               | 1         | 0.79%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 0.79%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 1         | 0.79%   |
| Nvidia GP107 [GeForce GTX 1050]                                               | 1         | 0.79%   |
| Nvidia GP104 [GeForce GTX 1080]                                               | 1         | 0.79%   |
| Nvidia GP104 [GeForce GTX 1070]                                               | 1         | 0.79%   |
| Nvidia GM206M [GeForce GTX 965M]                                              | 1         | 0.79%   |
| Nvidia GM108M [GeForce MX130]                                                 | 1         | 0.79%   |
| Nvidia GM107 [GeForce GTX 745]                                                | 1         | 0.79%   |
| Nvidia GM107 [GeForce 940MX]                                                  | 1         | 0.79%   |
| Nvidia GK208BM [GeForce 920M]                                                 | 1         | 0.79%   |
| Nvidia GK107M [GeForce GT 650M]                                               | 1         | 0.79%   |
| Nvidia GK107 [GeForce GT 740]                                                 | 1         | 0.79%   |
| Nvidia GK107 [GeForce GT 640]                                                 | 1         | 0.79%   |
| Nvidia GF119M [GeForce 610M]                                                  | 1         | 0.79%   |
| Nvidia GF108GLM [NVS 5200M]                                                   | 1         | 0.79%   |
| Nvidia GF108GL [Quadro 600]                                                   | 1         | 0.79%   |
| Nvidia GF100GL [Quadro 4000]                                                  | 1         | 0.79%   |
| Nvidia GA104 [GeForce RTX 3070]                                               | 1         | 0.79%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 1         | 0.79%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 1         | 0.79%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 1         | 0.79%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 1         | 0.79%   |
| Intel Iris Pro Graphics 580                                                   | 1         | 0.79%   |
| Intel HD Graphics 530                                                         | 1         | 0.79%   |
| Intel HD Graphics 500                                                         | 1         | 0.79%   |
| Intel Core Processor Integrated Graphics Controller                           | 1         | 0.79%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 1         | 0.79%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                              | 1         | 0.79%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                     | 1         | 0.79%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 1         | 0.79%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller     | 1         | 0.79%   |
| Intel 4 Series Chipset Integrated Graphics Controller                         | 1         | 0.79%   |
| AMD Wrestler [Radeon HD 7310]                                                 | 1         | 0.79%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                           | 1         | 0.79%   |
| AMD Sumo [Radeon HD 6520G]                                                    | 1         | 0.79%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                             | 1         | 0.79%   |
| AMD RV635/M86 [Mobility Radeon HD 3650]                                       | 1         | 0.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 44        | 40.37%  |
| 1 x Nvidia     | 26        | 23.85%  |
| 1 x AMD        | 20        | 18.35%  |
| Intel + Nvidia | 12        | 11.01%  |
| 2 x Intel      | 3         | 2.75%   |
| 2 x Nvidia     | 1         | 0.92%   |
| 2 x AMD        | 1         | 0.92%   |
| Intel + AMD    | 1         | 0.92%   |
| AMD + Nvidia   | 1         | 0.92%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 82        | 75.23%  |
| Proprietary | 27        | 24.77%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 70        | 64.22%  |
| 1.01-2.0   | 10        | 9.17%   |
| 3.01-4.0   | 8         | 7.34%   |
| 7.01-8.0   | 7         | 6.42%   |
| 0.51-1.0   | 7         | 6.42%   |
| 0.01-0.5   | 6         | 5.5%    |
| 2.01-3.0   | 1         | 0.92%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 13        | 12.87%  |
| LG Display           | 12        | 11.88%  |
| Chimei Innolux       | 10        | 9.9%    |
| AU Optronics         | 10        | 9.9%    |
| Dell                 | 7         | 6.93%   |
| Goldstar             | 6         | 5.94%   |
| Philips              | 4         | 3.96%   |
| BOE                  | 4         | 3.96%   |
| BenQ                 | 4         | 3.96%   |
| Lenovo               | 3         | 2.97%   |
| Hewlett-Packard      | 3         | 2.97%   |
| ViewSonic            | 2         | 1.98%   |
| LG Electronics       | 2         | 1.98%   |
| Iiyama               | 2         | 1.98%   |
| AOC                  | 2         | 1.98%   |
| ___                  | 1         | 0.99%   |
| WYT                  | 1         | 0.99%   |
| Vizio                | 1         | 0.99%   |
| Toshiba              | 1         | 0.99%   |
| Pixio                | 1         | 0.99%   |
| PANDA                | 1         | 0.99%   |
| Panasonic            | 1         | 0.99%   |
| OEM                  | 1         | 0.99%   |
| InfoVision           | 1         | 0.99%   |
| Idek Iiyama          | 1         | 0.99%   |
| IBM                  | 1         | 0.99%   |
| HannStar             | 1         | 0.99%   |
| CSO                  | 1         | 0.99%   |
| CHD                  | 1         | 0.99%   |
| ASUSTek Computer     | 1         | 0.99%   |
| Ancor Communications | 1         | 0.99%   |
| Acer                 | 1         | 0.99%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch      | 2         | 1.89%   |
| LG Display LCD Monitor LGD0456 1366x768 340x190mm 15.3-inch            | 2         | 1.89%   |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch            | 2         | 1.89%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch       | 2         | 1.89%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 340x190mm 15.3-inch          | 2         | 1.89%   |
| ___ MY TV LED TV ___0101 1920x1080                                     | 1         | 0.94%   |
| WYT MNT-ANALOG WYT0323 1280x1024 330x270mm 16.8-inch                   | 1         | 0.94%   |
| Vizio E320i-B2 VIZ1002 1360x768 700x400mm 31.7-inch                    | 1         | 0.94%   |
| ViewSonic VX3209-2K VSC328E 2560x1440 700x390mm 31.5-inch              | 1         | 0.94%   |
| ViewSonic LCD Monitor VA1938 Series                                    | 1         | 0.94%   |
| Toshiba TV TSB010F 1920x1080 890x500mm 40.2-inch                       | 1         | 0.94%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 470x300mm 22.0-inch   | 1         | 0.94%   |
| Samsung Electronics SyncMaster SAM010B 1280x1024 340x270mm 17.1-inch   | 1         | 0.94%   |
| Samsung Electronics SMBX2231 SAM076D 1920x1080 480x270mm 21.7-inch     | 1         | 0.94%   |
| Samsung Electronics SA300/SA350 SAM078F 1920x1080 480x270mm 21.7-inch  | 1         | 0.94%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x170mm 13.9-inch   | 1         | 0.94%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 330x210mm 15.4-inch   | 1         | 0.94%   |
| Samsung Electronics LCD Monitor SEC4542 1280x800 300x190mm 14.0-inch   | 1         | 0.94%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 340x190mm 15.3-inch   | 1         | 0.94%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 340x190mm 15.3-inch   | 1         | 0.94%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch   | 1         | 0.94%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 310x170mm 13.9-inch   | 1         | 0.94%   |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 1020x570mm 46.0-inch | 1         | 0.94%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 890x500mm 40.2-inch  | 1         | 0.94%   |
| Samsung Electronics LCD Monitor SAM02A4 1360x768                       | 1         | 0.94%   |
| Pixio PX247 PNS0247 1920x1080 520x310mm 23.8-inch                      | 1         | 0.94%   |
| Philips PHL BDM4065 PHL08E1 3840x2160 880x490mm 39.7-inch              | 1         | 0.94%   |
| Philips PHL 240V5 PHLC10A 1920x1080 530x300mm 24.0-inch                | 1         | 0.94%   |
| Philips LCD Monitor PHL 240V5 1920x1080                                | 1         | 0.94%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                     | 1         | 0.94%   |
| PANDA LCD Monitor NCP0040 1920x1080 340x190mm 15.3-inch                | 1         | 0.94%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch           | 1         | 0.94%   |
| OEM 32W_LCD_TV OEM3700 1920x540                                        | 1         | 0.94%   |
| LG Electronics LCD Monitor W1952 2806x900                              | 1         | 0.94%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                      | 1         | 0.94%   |
| LG Display LCD Monitor LGD05B3 1920x1080 290x170mm 13.2-inch           | 1         | 0.94%   |
| LG Display LCD Monitor LGD0558 1920x1080 310x170mm 13.9-inch           | 1         | 0.94%   |
| LG Display LCD Monitor LGD0533 1920x1080 340x190mm 15.3-inch           | 1         | 0.94%   |
| LG Display LCD Monitor LGD052D 1920x1080 290x170mm 13.2-inch           | 1         | 0.94%   |
| LG Display LCD Monitor LGD0430 1366x768 350x190mm 15.7-inch            | 1         | 0.94%   |
| LG Display LCD Monitor LGD042D 1920x1080 290x170mm 13.2-inch           | 1         | 0.94%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch            | 1         | 0.94%   |
| LG Display LCD Monitor LGD01CA 1600x900 380x210mm 17.1-inch            | 1         | 0.94%   |
| Lenovo V20-10 LEN65DC 1600x900 430x240mm 19.4-inch                     | 1         | 0.94%   |
| Lenovo LEN P27h-10 LEN61AF 2560x1440 600x340mm 27.2-inch               | 1         | 0.94%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch                | 1         | 0.94%   |
| InfoVision LCD Monitor IVO04E3 1366x768 280x160mm 12.7-inch            | 1         | 0.94%   |
| Iiyama PL2783Q IVM661F 2560x1440 600x340mm 27.2-inch                   | 1         | 0.94%   |
| Iiyama PL2492H IVM612F 1920x1080 530x300mm 24.0-inch                   | 1         | 0.94%   |
| Idek Iiyama LCD Monitor PL3270Q 5120x1440                              | 1         | 0.94%   |
| Idek Iiyama LCD Monitor PL3270Q                                        | 1         | 0.94%   |
| IBM LCD Monitor IBM2887 1680x1050 330x210mm 15.4-inch                  | 1         | 0.94%   |
| Hewlett-Packard LCD Monitor HWP4218 1600x900 440x250mm 19.9-inch       | 1         | 0.94%   |
| Hewlett-Packard LA2205 HWP2848 1680x1050 470x300mm 22.0-inch           | 1         | 0.94%   |
| Hewlett-Packard 22w HPN342E 1920x1080 480x270mm 21.7-inch              | 1         | 0.94%   |
| HannStar LCD Monitor HSD2469 1680x1050 470x300mm 22.0-inch             | 1         | 0.94%   |
| Goldstar W2261 GSM56CF 1920x1080 530x300mm 24.0-inch                   | 1         | 0.94%   |
| Goldstar W1934 GSM4B7A 1440x900 410x260mm 19.1-inch                    | 1         | 0.94%   |
| Goldstar LG ULTRAWIDE GSM76FA 2560x1080 800x340mm 34.2-inch            | 1         | 0.94%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch            | 1         | 0.94%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 34        | 32.38%  |
| 1366x768 (WXGA)    | 25        | 23.81%  |
| 1600x900 (HD+)     | 10        | 9.52%   |
| 3840x2160 (4K)     | 6         | 5.71%   |
| 2560x1440 (QHD)    | 6         | 5.71%   |
| 1680x1050 (WSXGA+) | 4         | 3.81%   |
| 1280x1024 (SXGA)   | 4         | 3.81%   |
| 2560x1080          | 3         | 2.86%   |
| Unknown            | 3         | 2.86%   |
| 3840x1600          | 2         | 1.9%    |
| 1360x768           | 2         | 1.9%    |
| 5120x1440          | 1         | 0.95%   |
| 3200x1080          | 1         | 0.95%   |
| 2880x1620          | 1         | 0.95%   |
| 2806x900           | 1         | 0.95%   |
| 1920x540           | 1         | 0.95%   |
| 1440x900 (WXGA+)   | 1         | 0.95%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 26        | 25.49%  |
| 13      | 16        | 15.69%  |
| Unknown | 9         | 8.82%   |
| 27      | 7         | 6.86%   |
| 21      | 6         | 5.88%   |
| 23      | 5         | 4.9%    |
| 19      | 5         | 4.9%    |
| 17      | 5         | 4.9%    |
| 24      | 4         | 3.92%   |
| 22      | 3         | 2.94%   |
| 12      | 3         | 2.94%   |
| 40      | 2         | 1.96%   |
| 34      | 2         | 1.96%   |
| 31      | 2         | 1.96%   |
| 65      | 1         | 0.98%   |
| 54      | 1         | 0.98%   |
| 39      | 1         | 0.98%   |
| 37      | 1         | 0.98%   |
| 32      | 1         | 0.98%   |
| 16      | 1         | 0.98%   |
| 14      | 1         | 0.98%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 41        | 40.59%  |
| 501-600     | 14        | 13.86%  |
| 401-500     | 13        | 12.87%  |
| Unknown     | 9         | 8.91%   |
| 201-300     | 7         | 6.93%   |
| 801-900     | 4         | 3.96%   |
| 601-700     | 4         | 3.96%   |
| 351-400     | 4         | 3.96%   |
| 701-800     | 3         | 2.97%   |
| 1001-1500   | 2         | 1.98%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 75        | 78.13%  |
| 16/10   | 7         | 7.29%   |
| Unknown | 6         | 6.25%   |
| 5/4     | 3         | 3.13%   |
| 21/9    | 3         | 3.13%   |
| 6/5     | 1         | 1.04%   |
| 32/9    | 1         | 1.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 91-100         | 23        | 22.55%  |
| 201-250        | 18        | 17.65%  |
| 81-90          | 14        | 13.73%  |
| Unknown        | 9         | 8.82%   |
| 301-350        | 7         | 6.86%   |
| 351-500        | 5         | 4.9%    |
| 151-200        | 5         | 4.9%    |
| 501-1000       | 4         | 3.92%   |
| 71-80          | 3         | 2.94%   |
| 61-70          | 3         | 2.94%   |
| 121-130        | 3         | 2.94%   |
| 101-110        | 3         | 2.94%   |
| More than 1000 | 2         | 1.96%   |
| 141-150        | 2         | 1.96%   |
| 131-140        | 1         | 0.98%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 33        | 32.67%  |
| 51-100        | 30        | 29.7%   |
| 121-160       | 20        | 19.8%   |
| Unknown       | 9         | 8.91%   |
| 161-240       | 6         | 5.94%   |
| 1-50          | 2         | 1.98%   |
| More than 240 | 1         | 0.99%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 81        | 72.97%  |
| 2     | 15        | 13.51%  |
| 0     | 15        | 13.51%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 58        | 35.8%   |
| Realtek Semiconductor             | 47        | 29.01%  |
| Qualcomm Atheros                  | 20        | 12.35%  |
| Broadcom                          | 13        | 8.02%   |
| TP-Link                           | 7         | 4.32%   |
| Nvidia                            | 4         | 2.47%   |
| Ericsson Business Mobile Networks | 3         | 1.85%   |
| Ralink                            | 2         | 1.23%   |
| Qualcomm                          | 2         | 1.23%   |
| Microchip Technology              | 1         | 0.62%   |
| Marvell Technology Group          | 1         | 0.62%   |
| Fibocom                           | 1         | 0.62%   |
| Edimax Technology                 | 1         | 0.62%   |
| ASUSTek Computer                  | 1         | 0.62%   |
| Aquantia                          | 1         | 0.62%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 33        | 16.75%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 5.58%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 4.06%   |
| Intel I211 Gigabit Network Connection                             | 8         | 4.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 3.05%   |
| Intel Wireless 8265 / 8275                                        | 6         | 3.05%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 2.54%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 2.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 2.03%   |
| Intel Wireless 7265                                               | 4         | 2.03%   |
| Intel Wireless 7260                                               | 4         | 2.03%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 2.03%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 3         | 1.52%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 1.52%   |
| Nvidia MCP79 Ethernet                                             | 3         | 1.52%   |
| Intel Wireless 8260                                               | 3         | 1.52%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 1.52%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 2         | 1.02%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 2         | 1.02%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2         | 1.02%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 2         | 1.02%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 1.02%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.02%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.02%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.02%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.02%   |
| Intel Centrino Ultimate-N 6300                                    | 2         | 1.02%   |
| Intel Centrino Advanced-N 6235                                    | 2         | 1.02%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 1.02%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 1.02%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2         | 1.02%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 2         | 1.02%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 1.02%   |
| TP-Link TP-LINK Wireless USB Adapter                              | 1         | 0.51%   |
| TP-Link TP-Link High Power Wireless USB Adapter                   | 1         | 0.51%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1         | 0.51%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1         | 0.51%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.51%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.51%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.51%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.51%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.51%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.51%   |
| Realtek Realtek Bluetooth 4.2 Adapter                             | 1         | 0.51%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter            | 1         | 0.51%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.51%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 0.51%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.51%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.51%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.51%   |
| Nvidia MCP73 Ethernet                                             | 1         | 0.51%   |
| Microchip HTC Hub Controller                                      | 1         | 0.51%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.51%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 0.51%   |
| Intel Wireless-AC 9260                                            | 1         | 0.51%   |
| Intel Wireless 3165                                               | 1         | 0.51%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 1         | 0.51%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 1         | 0.51%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 40        | 47.06%  |
| Qualcomm Atheros      | 17        | 20%     |
| Realtek Semiconductor | 12        | 14.12%  |
| TP-Link               | 7         | 8.24%   |
| Broadcom              | 5         | 5.88%   |
| Ralink                | 2         | 2.35%   |
| Edimax Technology     | 1         | 1.18%   |
| ASUSTek Computer      | 1         | 1.18%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 6         | 6.98%   |
| Intel Wireless 8265 / 8275                                     | 6         | 6.98%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4         | 4.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4         | 4.65%   |
| Intel Wireless 7265                                            | 4         | 4.65%   |
| Intel Wireless 7260                                            | 4         | 4.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 4.65%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 3         | 3.49%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 3.49%   |
| Intel Wireless 8260                                            | 3         | 3.49%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 3.49%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 2         | 2.33%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 2.33%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2         | 2.33%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 2.33%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 2.33%   |
| Intel Centrino Advanced-N 6235                                 | 2         | 2.33%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 2.33%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 2         | 2.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 2.33%   |
| TP-Link TP-LINK Wireless USB Adapter                           | 1         | 1.16%   |
| TP-Link TP-Link High Power Wireless USB Adapter                | 1         | 1.16%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 1.16%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 1.16%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.16%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 1.16%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 1.16%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 1.16%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 1.16%   |
| Realtek Realtek Bluetooth 4.2 Adapter                          | 1         | 1.16%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter         | 1         | 1.16%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 1.16%   |
| Intel Wireless-AC 9260                                         | 1         | 1.16%   |
| Intel Wireless 3165                                            | 1         | 1.16%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 1.16%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 1.16%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 1.16%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 1         | 1.16%   |
| Intel Centrino Wireless-N 100                                  | 1         | 1.16%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 1.16%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 1         | 1.16%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 1         | 1.16%   |
| ASUS ASUS Wireless USB adapter                                 | 1         | 1.16%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 42        | 40.38%  |
| Intel                    | 41        | 39.42%  |
| Broadcom                 | 9         | 8.65%   |
| Qualcomm Atheros         | 4         | 3.85%   |
| Nvidia                   | 4         | 3.85%   |
| Qualcomm                 | 2         | 1.92%   |
| Marvell Technology Group | 1         | 0.96%   |
| Aquantia                 | 1         | 0.96%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 33        | 31.13%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 10.38%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 7.55%   |
| Intel I211 Gigabit Network Connection                             | 8         | 7.55%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 4.72%   |
| Nvidia MCP79 Ethernet                                             | 3         | 2.83%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 2         | 1.89%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.89%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.89%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.89%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.89%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 1.89%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2         | 1.89%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.94%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.94%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.94%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.94%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.94%   |
| Nvidia MCP73 Ethernet                                             | 1         | 0.94%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.94%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 0.94%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.94%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.94%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.94%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.94%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.94%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.94%   |
| Intel 82576 Gigabit Network Connection                            | 1         | 0.94%   |
| Intel 82567V-2 Gigabit Network Connection                         | 1         | 0.94%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.94%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.94%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 0.94%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 1         | 0.94%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 0.94%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.94%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 1         | 0.94%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 0.94%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 101       | 54.59%  |
| WiFi     | 79        | 42.7%   |
| Modem    | 3         | 1.62%   |
| Unknown  | 2         | 1.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 99        | 61.49%  |
| WiFi     | 61        | 37.89%  |
| Modem    | 1         | 0.62%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 65        | 59.63%  |
| 1     | 41        | 37.61%  |
| 3     | 3         | 2.75%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 109       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 26        | 45.61%  |
| Broadcom                        | 7         | 12.28%  |
| Qualcomm Atheros Communications | 6         | 10.53%  |
| Realtek Semiconductor           | 4         | 7.02%   |
| Lite-On Technology              | 4         | 7.02%   |
| Apple                           | 3         | 5.26%   |
| Cambridge Silicon Radio         | 2         | 3.51%   |
| Alps Electric                   | 2         | 3.51%   |
| HTC (High Tech Computer)        | 1         | 1.75%   |
| Dell                            | 1         | 1.75%   |
| ASUSTek Computer                | 1         | 1.75%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                   | 15        | 26.32%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 4         | 7.02%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 3         | 5.26%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 3         | 5.26%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 3         | 5.26%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 3         | 5.26%   |
| Apple Bluetooth Host Controller                                      | 3         | 5.26%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                              | 2         | 3.51%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 2         | 3.51%   |
| Lite-On Atheros AR3012 Bluetooth                                     | 2         | 3.51%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 2         | 3.51%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 2         | 3.51%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2         | 3.51%   |
| Realtek  Bluetooth Adapter                                           | 1         | 1.75%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device          | 1         | 1.75%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 1         | 1.75%   |
| Intel AX200 Bluetooth                                                | 1         | 1.75%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1         | 1.75%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                          | 1         | 1.75%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                   | 1         | 1.75%   |
| Broadcom BCM2045B (BDC-2.1)                                          | 1         | 1.75%   |
| ASUS Realtek Bluetooth 4.0 + High Speed Chip                         | 1         | 1.75%   |
| Alps Electric UGTZ4 Bluetooth                                        | 1         | 1.75%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)                      | 1         | 1.75%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Intel                | 71        | 47.97%  |
| AMD                  | 35        | 23.65%  |
| Nvidia               | 29        | 19.59%  |
| Logitech             | 3         | 2.03%   |
| SteelSeries ApS      | 2         | 1.35%   |
| VIA Technologies     | 1         | 0.68%   |
| Nam Tai E&E Products | 1         | 0.68%   |
| JMTek                | 1         | 0.68%   |
| Focusrite-Novation   | 1         | 0.68%   |
| Creative Technology  | 1         | 0.68%   |
| Creative Labs        | 1         | 0.68%   |
| Corsair              | 1         | 0.68%   |
| C-Media Electronics  | 1         | 0.68%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                       | 12        | 6.59%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                   | 11        | 6.04%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller            | 11        | 6.04%   |
| Intel Haswell-ULT HD Audio Controller                                                 | 9         | 4.95%   |
| Intel 8 Series HD Audio Controller                                                    | 9         | 4.95%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                   | 8         | 4.4%    |
| AMD Starship/Matisse HD Audio Controller                                              | 7         | 3.85%   |
| AMD Family 17h/19h HD Audio Controller                                                | 7         | 3.85%   |
| AMD FCH Azalia Controller                                                             | 6         | 3.3%    |
| Nvidia GK107 HDMI Audio Controller                                                    | 5         | 2.75%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                   | 5         | 2.75%   |
| Nvidia GP107GL High Definition Audio Controller                                       | 4         | 2.2%    |
| Nvidia GP104 High Definition Audio Controller                                         | 4         | 2.2%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                        | 4         | 2.2%    |
| AMD Kabini HDMI/DP Audio                                                              | 4         | 2.2%    |
| Nvidia MCP79 High Definition Audio                                                    | 3         | 1.65%   |
| Nvidia GM206 High Definition Audio Controller                                         | 3         | 1.65%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                         | 3         | 1.65%   |
| Intel Wildcat Point-LP High Definition Audio Controller                               | 3         | 1.65%   |
| Intel Cannon Lake PCH cAVS                                                            | 3         | 1.65%   |
| Intel Broadwell-U Audio Controller                                                    | 3         | 1.65%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                      | 3         | 1.65%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                       | 3         | 1.65%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                      | 3         | 1.65%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                            | 3         | 1.65%   |
| SteelSeries ApS SteelSeries Arctis 7 Arctis 7 Chat Arctis 7 Game SteelSeries Arctis 7 | 2         | 1.1%    |
| Nvidia GP108 High Definition Audio Controller                                         | 2         | 1.1%    |
| Intel Cannon Point-LP High Definition Audio Controller                                | 2         | 1.1%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                   | 2         | 1.1%    |
| Intel 200 Series PCH HD Audio                                                         | 2         | 1.1%    |
| AMD SBx00 Azalia (Intel HDA)                                                          | 2         | 1.1%    |
| AMD Renoir Radeon High Definition Audio Controller                                    | 2         | 1.1%    |
| AMD High Definition Audio Controller                                                  | 2         | 1.1%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                          | 2         | 1.1%    |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller           | 1         | 0.55%   |
| Nvidia TU116 High Definition Audio Controller                                         | 1         | 0.55%   |
| Nvidia TU106 High Definition Audio Controller                                         | 1         | 0.55%   |
| Nvidia TU104 HD Audio Controller                                                      | 1         | 0.55%   |
| Nvidia MCP73 High Definition Audio                                                    | 1         | 0.55%   |
| Nvidia GF108 High Definition Audio Controller                                         | 1         | 0.55%   |
| Nvidia GF100 High Definition Audio Controller                                         | 1         | 0.55%   |
| Nvidia GA104 High Definition Audio Controller                                         | 1         | 0.55%   |
| Nam Tai E&E Products Sony SingStar USBMIC                                             | 1         | 0.55%   |
| Logitech Logitech USB Microphone                                                      | 1         | 0.55%   |
| Logitech HD Webcam C510                                                               | 1         | 0.55%   |
| Logitech H600 [Wireless Headset]                                                      | 1         | 0.55%   |
| JMTek Sharkoon 7.1 Sound Extension                                                    | 1         | 0.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                      | 1         | 0.55%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                               | 1         | 0.55%   |
| Intel Comet Lake PCH-LP cAVS                                                          | 1         | 0.55%   |
| Intel CM238 HD Audio Controller                                                       | 1         | 0.55%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                     | 1         | 0.55%   |
| Intel 9 Series Chipset Family HD Audio Controller                                     | 1         | 0.55%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                              | 1         | 0.55%   |
| Focusrite-Novation Scarlett Solo (3rd Gen.)                                           | 1         | 0.55%   |
| Creative Technology Sound Blaster Omni Surround 5.1                                   | 1         | 0.55%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                         | 1         | 0.55%   |
| Corsair Corsair VOID PRO Wireless Gaming Headset                                      | 1         | 0.55%   |
| C-Media Electronics USB Audio Class 1.0 and 2.0 Device                                | 1         | 0.55%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                      | 1         | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 30        | 22.39%  |
| SK hynix            | 22        | 16.42%  |
| Kingston            | 17        | 12.69%  |
| G.Skill             | 12        | 8.96%   |
| Unknown             | 11        | 8.21%   |
| Crucial             | 10        | 7.46%   |
| Corsair             | 8         | 5.97%   |
| Micron Technology   | 6         | 4.48%   |
| A-DATA Technology   | 4         | 2.99%   |
| Elpida              | 3         | 2.24%   |
| Nanya Technology    | 2         | 1.49%   |
| Unknown (ABCD)      | 1         | 0.75%   |
| Team                | 1         | 0.75%   |
| Smart               | 1         | 0.75%   |
| S                   | 1         | 0.75%   |
| Ramaxel Technology  | 1         | 0.75%   |
| Neo Forza           | 1         | 0.75%   |
| Goodram             | 1         | 0.75%   |
| Apacer              | 1         | 0.75%   |
| Unknown             | 1         | 0.75%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 4         | 2.92%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 2.92%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 2.19%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s              | 3         | 2.19%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s            | 3         | 2.19%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.46%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.46%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s            | 2         | 1.46%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s            | 2         | 1.46%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.46%   |
| Unknown SODIMM 4GB SODIMM 800MT/s                                | 1         | 0.73%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 0.73%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1         | 0.73%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 1         | 0.73%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.73%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                       | 1         | 0.73%   |
| Unknown RAM Module 2GB DIMM DDR3 1067MT/s                        | 1         | 0.73%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 1         | 0.73%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 1         | 0.73%   |
| Unknown RAM Module 1024MB SODIMM DDR                             | 1         | 0.73%   |
| Unknown RAM GD2.09293S.001 16GB SODIMM DDR4 2400MT/s             | 1         | 0.73%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2133MT/s | 1         | 0.73%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s             | 1         | 0.73%   |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s            | 1         | 0.73%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1067MT/s                     | 1         | 0.73%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.73%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.73%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.73%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.73%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.73%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s             | 1         | 0.73%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s             | 1         | 0.73%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.73%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.73%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.73%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 0.73%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s             | 1         | 0.73%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.73%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.73%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 1         | 0.73%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 0.73%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.73%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 0.73%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 0.73%   |
| Samsung RAM M471B1G73BH0-CK0 8GB SODIMM DDR3 1600MT/s            | 1         | 0.73%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 0.73%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 0.73%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 1         | 0.73%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2133MT/s            | 1         | 0.73%   |
| Samsung RAM M393B5170FH0 4GB DIMM DDR3 1600MT/s                  | 1         | 0.73%   |
| Samsung RAM M391B5273DH0-CH9 4GB DIMM DDR3 1333MT/s              | 1         | 0.73%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s              | 1         | 0.73%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 1600MT/s              | 1         | 0.73%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s              | 1         | 0.73%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 2667MT/s             | 1         | 0.73%   |
| Samsung RAM K4AAG165WA-BCTD 8GB SODIMM DDR4 2667MT/s             | 1         | 0.73%   |
| S RAM Module 4GB DIMM DDR3 1600MT/s                              | 1         | 0.73%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s          | 1         | 0.73%   |
| Neo Forza RAM NMSO480E82-2666E 8GB SODIMM DDR4 2667MT/s          | 1         | 0.73%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s             | 1         | 0.73%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 55        | 50%     |
| DDR4    | 46        | 41.82%  |
| DDR2    | 3         | 2.73%   |
| Unknown | 3         | 2.73%   |
| LPDDR4  | 1         | 0.91%   |
| LPDDR3  | 1         | 0.91%   |
| DDR     | 1         | 0.91%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 68        | 61.82%  |
| DIMM         | 41        | 37.27%  |
| Row Of Chips | 1         | 0.91%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 49        | 41.53%  |
| 4096  | 45        | 38.14%  |
| 16384 | 12        | 10.17%  |
| 2048  | 10        | 8.47%   |
| 32768 | 1         | 0.85%   |
| 1024  | 1         | 0.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 40        | 33.61%  |
| 2400    | 18        | 15.13%  |
| 2667    | 14        | 11.76%  |
| 1333    | 10        | 8.4%    |
| 3200    | 9         | 7.56%   |
| 2133    | 8         | 6.72%   |
| 1334    | 5         | 4.2%    |
| 1067    | 4         | 3.36%   |
| 800     | 4         | 3.36%   |
| Unknown | 2         | 1.68%   |
| 3600    | 1         | 0.84%   |
| 3066    | 1         | 0.84%   |
| 2666    | 1         | 0.84%   |
| 1867    | 1         | 0.84%   |
| 667     | 1         | 0.84%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| HP HP Laser 107w | 1         | 100%    |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 15        | 27.27%  |
| Acer                                   | 7         | 12.73%  |
| Suyin                                  | 4         | 7.27%   |
| Sunplus Innovation Technology          | 4         | 7.27%   |
| Realtek Semiconductor                  | 4         | 7.27%   |
| Microdia                               | 4         | 7.27%   |
| Alcor Micro                            | 4         | 7.27%   |
| Silicon Motion                         | 2         | 3.64%   |
| Quanta                                 | 2         | 3.64%   |
| Lite-On Technology                     | 2         | 3.64%   |
| Xiongmai                               | 1         | 1.82%   |
| Trust                                  | 1         | 1.82%   |
| Logitech                               | 1         | 1.82%   |
| Lenovo                                 | 1         | 1.82%   |
| Importek                               | 1         | 1.82%   |
| IMC Networks                           | 1         | 1.82%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.82%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Acer Integrated Camera                                         | 6         | 10.71%  |
| Chicony Integrated Camera (1280x720@30)                        | 3         | 5.36%   |
| Chicony Integrated Camera                                      | 3         | 5.36%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 2         | 3.57%   |
| Sunplus Laptop_Integrated_Webcam_FHD                           | 2         | 3.57%   |
| Microdia Integrated_Webcam_HD                                  | 2         | 3.57%   |
| Microdia Integrated Webcam                                     | 2         | 3.57%   |
| Chicony HD WebCam                                              | 2         | 3.57%   |
| Chicony Chicony USB2.0 Camera                                  | 2         | 3.57%   |
| Xiongmai web camera                                            | 1         | 1.79%   |
| Trust Trust USB Camera                                         | 1         | 1.79%   |
| Suyin Integrated_Webcam_HD                                     | 1         | 1.79%   |
| Suyin HD WebCam                                                | 1         | 1.79%   |
| Sunplus MTD camera                                             | 1         | 1.79%   |
| Sunplus Integrated_Webcam_HD                                   | 1         | 1.79%   |
| Silicon Motion WebCam SC-13HDL11939N                           | 1         | 1.79%   |
| Silicon Motion Realtek USB2.0 PC Camera                        | 1         | 1.79%   |
| Realtek Realtek USB2.0 PC Camera                               | 1         | 1.79%   |
| Realtek Lenovo EasyCamera                                      | 1         | 1.79%   |
| Realtek Integrated_Webcam_HD                                   | 1         | 1.79%   |
| Realtek Front Camera                                           | 1         | 1.79%   |
| Quanta VGA WebCam                                              | 1         | 1.79%   |
| Quanta HP TrueVision HD Camera                                 | 1         | 1.79%   |
| Logitech Webcam C310                                           | 1         | 1.79%   |
| Lite-On Integrated Camera                                      | 1         | 1.79%   |
| Lite-On HP TrueVision HD Camera                                | 1         | 1.79%   |
| Lenovo Integrated Webcam [R5U877]                              | 1         | 1.79%   |
| Importek TOSHIBA Web Camera - HD                               | 1         | 1.79%   |
| IMC Networks UVC VGA Webcam                                    | 1         | 1.79%   |
| Chicony USB2.0 HD UVC WebCam                                   | 1         | 1.79%   |
| Chicony Thinkpad T430 camera                                   | 1         | 1.79%   |
| Chicony Realtek DMFT - IR                                      | 1         | 1.79%   |
| Chicony Lenovo Integrated Camera (0.3MP)                       | 1         | 1.79%   |
| Chicony Lenovo EasyCamera                                      | 1         | 1.79%   |
| Chicony HP High Definition 1MP Webcam                          | 1         | 1.79%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 1.79%   |
| Alcor Micro USB 2.0 Web Camera                                 | 1         | 1.79%   |
| Alcor Micro USB 2.0 Camera                                     | 1         | 1.79%   |
| Alcor Micro HP WebCam-101                                      | 1         | 1.79%   |
| Alcor Micro Acer Integrated Webcam                             | 1         | 1.79%   |
| Acer ThinkPad Integrated Camera                                | 1         | 1.79%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Validity Sensors   | 5         | 41.67%  |
| Synaptics          | 3         | 25%     |
| Upek               | 2         | 16.67%  |
| STMicroelectronics | 1         | 8.33%   |
| Focal-systems.Corp | 1         | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 2         | 16.67%  |
| Validity Sensors Synaptics WBDI                        | 2         | 16.67%  |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 8.33%   |
| Upek TCS5B Fingerprint sensor                          | 1         | 8.33%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 8.33%   |
| Synaptics  WBDI                                        | 1         | 8.33%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 8.33%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 8.33%   |
| STMicroelectronics Fingerprint Reader                  | 1         | 8.33%   |
| Focal-systems.Corp FocalTech Fingerprint reader        | 1         | 8.33%   |

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


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 33        | 29.46%  |
| 2     | 27        | 24.11%  |
| 3     | 20        | 17.86%  |
| 0     | 19        | 16.96%  |
| 4     | 10        | 8.93%   |
| 5     | 3         | 2.68%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 64        | 33.16%  |
| Bluetooth                | 48        | 24.87%  |
| Card reader              | 26        | 13.47%  |
| Net/wireless             | 22        | 11.4%   |
| Fingerprint reader       | 12        | 6.22%   |
| Firewire controller      | 10        | 5.18%   |
| Network                  | 5         | 2.59%   |
| Storage                  | 4         | 2.07%   |
| Sound                    | 1         | 0.52%   |
| Modem                    | 1         | 0.52%   |

