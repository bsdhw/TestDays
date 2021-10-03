GhostBSD 20.04.02 - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for GhostBSD 20.04.02.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/GhostBSD_20.04.02/Desktop/README.md) and [notebooks](/Dist/GhostBSD_20.04.02/Notebook/README.md).

Full-feature report is available here: https://bsd-hardware.info/?view=trends&rel=ghostbsd-20.04.02

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

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
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

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 106       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| MATE             | 84        | 77.78%  |
| XFCE             | 15        | 13.89%  |
| KDE5             | 3         | 2.78%   |
| Metacity (Marco) | 2         | 1.85%   |
| openbox          | 1         | 0.93%   |
| i3               | 1         | 0.93%   |
| GNOME            | 1         | 0.93%   |
| Cinnamon         | 1         | 0.93%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 106       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 105       | 99.06%  |
| SDDM    | 1         | 0.94%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 47        | 43.12%  |
| Unknown | 28        | 25.69%  |
| C       | 10        | 9.17%   |
| de_DE   | 6         | 5.5%    |
| ru_RU   | 5         | 4.59%   |
| it_IT   | 2         | 1.83%   |
| fr_FR   | 2         | 1.83%   |
| en_GB   | 2         | 1.83%   |
| zh_CN   | 1         | 0.92%   |
| sk_SK   | 1         | 0.92%   |
| pt_BR   | 1         | 0.92%   |
| es_ES   | 1         | 0.92%   |
| en_NZ   | 1         | 0.92%   |
| en_AU   | 1         | 0.92%   |
| el_GR   | 1         | 0.92%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 75        | 70.75%  |
| BIOS | 31        | 29.25%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 101       | 94.39%  |
| Ufs  | 6         | 5.61%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 100       | 94.34%  |
| MBR  | 6         | 5.66%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 23        | 21.7%   |
| Dell                | 16        | 15.09%  |
| ASUSTek Computer    | 12        | 11.32%  |
| Acer                | 9         | 8.49%   |
| Hewlett-Packard     | 8         | 7.55%   |
| ASRock              | 7         | 6.6%    |
| MSI                 | 6         | 5.66%   |
| Gigabyte Technology | 6         | 5.66%   |
| Apple               | 3         | 2.83%   |
| Sony                | 2         | 1.89%   |
| Intel               | 2         | 1.89%   |
| Fujitsu             | 2         | 1.89%   |
| TUXEDO              | 1         | 0.94%   |
| Toshiba             | 1         | 0.94%   |
| System76            | 1         | 0.94%   |
| Samsung Electronics | 1         | 0.94%   |
| Quanta              | 1         | 0.94%   |
| Panasonic           | 1         | 0.94%   |
| Notebook            | 1         | 0.94%   |
| Huanan              | 1         | 0.94%   |
| GPU Company         | 1         | 0.94%   |
| Unknown             | 1         | 0.94%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                                                  | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Dell Inspiron 3542                                                    | 3         | 2.83%   |
| MSI MS-7B86                                                           | 2         | 1.89%   |
| Lenovo ThinkPad T430s 2352CTO                                         | 2         | 1.89%   |
| Dell Latitude E6420                                                   | 2         | 1.89%   |
| TUXEDO InfinityBook13V3                                               | 1         | 0.94%   |
| Toshiba Satellite C855                                                | 1         | 0.94%   |
| System76 Lemur Pro                                                    | 1         | 0.94%   |
| Sony VGN-SZ3VWP_X                                                     | 1         | 0.94%   |
| Sony SVP1322M1EBI                                                     | 1         | 0.94%   |
| Samsung 3570R/370R/470R/450R/510R/4450RV                              | 1         | 0.94%   |
| Quanta 120-1333w                                                      | 1         | 0.94%   |
| Panasonic CF-19AHNC8FN                                                | 1         | 0.94%   |
| Notebook N85_N87,HJ,HJ1,HK1                                           | 1         | 0.94%   |
| MSI MS-7C36                                                           | 1         | 0.94%   |
| MSI MS-7917                                                           | 1         | 0.94%   |
| MSI MS-7817                                                           | 1         | 0.94%   |
| MSI MS-7788                                                           | 1         | 0.94%   |
| Lenovo Yoga 2 13 20344                                                | 1         | 0.94%   |
| Lenovo ThinkStation S10 6483CTO                                       | 1         | 0.94%   |
| Lenovo ThinkPad X380 Yoga 20LJ000WUK                                  | 1         | 0.94%   |
| Lenovo ThinkPad X250 20CM003WMS                                       | 1         | 0.94%   |
| Lenovo ThinkPad X220 42872VU                                          | 1         | 0.94%   |
| Lenovo ThinkPad X1 Yoga 3rd 20LDS1CG00                                | 1         | 0.94%   |
| Lenovo ThinkPad T590 20N40016CD                                       | 1         | 0.94%   |
| Lenovo ThinkPad T530 239242U                                          | 1         | 0.94%   |
| Lenovo ThinkPad T500 2056Y2Z                                          | 1         | 0.94%   |
| Lenovo ThinkPad T470 W10DG 20JNS0JU01                                 | 1         | 0.94%   |
| Lenovo ThinkPad T470 20HD000MUK                                       | 1         | 0.94%   |
| Lenovo ThinkPad T450 20BV0064US                                       | 1         | 0.94%   |
| Lenovo ThinkPad T440 20B7S1860W                                       | 1         | 0.94%   |
| Lenovo ThinkPad T430s 23539JM                                         | 1         | 0.94%   |
| Lenovo ThinkPad T430 2344C4U                                          | 1         | 0.94%   |
| Lenovo ThinkPad L512 44444XG                                          | 1         | 0.94%   |
| Lenovo ThinkCentre Edge72 3493DEG                                     | 1         | 0.94%   |
| Lenovo Legion Y7000P 81LD                                             | 1         | 0.94%   |
| Lenovo IdeaPad S145-15API 81UT                                        | 1         | 0.94%   |
| Lenovo IdeaPad 520-15IKB 81BF                                         | 1         | 0.94%   |
| Lenovo H515s 10126                                                    | 1         | 0.94%   |
| Intel NUC8i5BEH                                                       | 1         | 0.94%   |
| Intel NUC6i7KYB H90766-402                                            | 1         | 0.94%   |
| Huanan X79 INTEL (INTEL Xeon E5/Corei7 DMI2 - C600/C200 Cipset V2.49P | 1         | 0.94%   |
| HP Z400 Workstation                                                   | 1         | 0.94%   |
| HP Pavilion x360 Convertible                                          | 1         | 0.94%   |
| HP OMEN by HP Laptop                                                  | 1         | 0.94%   |
| HP Laptop 15-db0xxx                                                   | 1         | 0.94%   |
| HP Laptop 15-da0xxx                                                   | 1         | 0.94%   |
| HP Laptop 14-dk0xxx                                                   | 1         | 0.94%   |
| HP Compaq Pro 6305 SFF                                                | 1         | 0.94%   |
| HP 255 G7 Notebook PC                                                 | 1         | 0.94%   |
| GPU Company GWTN156-5                                                 | 1         | 0.94%   |
| Gigabyte Z97-D3H                                                      | 1         | 0.94%   |
| Gigabyte Z370 AORUS Ultra Gaming                                      | 1         | 0.94%   |
| Gigabyte X470 AORUS ULTRA GAMING                                      | 1         | 0.94%   |
| Gigabyte H67A-UD3H-B3                                                 | 1         | 0.94%   |
| Gigabyte F2A68HM-DS2                                                  | 1         | 0.94%   |
| Gigabyte EG43M-S2H                                                    | 1         | 0.94%   |
| Fujitsu ESPRIMO P1500                                                 | 1         | 0.94%   |
| Fujitsu CELSIUS W580                                                  | 1         | 0.94%   |
| Dell Precision WorkStation T3400                                      | 1         | 0.94%   |
| Dell OptiPlex 9020                                                    | 1         | 0.94%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 16        | 15.09%  |
| Acer Aspire             | 8         | 7.55%   |
| Dell Latitude           | 7         | 6.6%    |
| ASUS PRIME              | 5         | 4.72%   |
| Dell OptiPlex           | 4         | 3.77%   |
| Dell Inspiron           | 4         | 3.77%   |
| HP Laptop               | 3         | 2.83%   |
| MSI MS-7B86             | 2         | 1.89%   |
| Lenovo IdeaPad          | 2         | 1.89%   |
| ASUS TUF                | 2         | 1.89%   |
| ASRock X570             | 2         | 1.89%   |
| TUXEDO InfinityBook13V3 | 1         | 0.94%   |
| Toshiba Satellite       | 1         | 0.94%   |
| System76 Lemur          | 1         | 0.94%   |
| Sony VGN-SZ3VWP         | 1         | 0.94%   |
| Sony SVP1322M1EBI       | 1         | 0.94%   |
| Samsung 3570R           | 1         | 0.94%   |
| Quanta 120-1333w        | 1         | 0.94%   |
| Panasonic CF-19AHNC8FN  | 1         | 0.94%   |
| Notebook N85            | 1         | 0.94%   |
| MSI MS-7C36             | 1         | 0.94%   |
| MSI MS-7917             | 1         | 0.94%   |
| MSI MS-7817             | 1         | 0.94%   |
| MSI MS-7788             | 1         | 0.94%   |
| Lenovo Yoga             | 1         | 0.94%   |
| Lenovo ThinkStation     | 1         | 0.94%   |
| Lenovo ThinkCentre      | 1         | 0.94%   |
| Lenovo Legion           | 1         | 0.94%   |
| Lenovo H515s            | 1         | 0.94%   |
| Intel NUC8i5BEH         | 1         | 0.94%   |
| Intel NUC6i7KYB         | 1         | 0.94%   |
| Huanan X79              | 1         | 0.94%   |
| HP Z400                 | 1         | 0.94%   |
| HP Pavilion             | 1         | 0.94%   |
| HP OMEN                 | 1         | 0.94%   |
| HP Compaq               | 1         | 0.94%   |
| HP 255                  | 1         | 0.94%   |
| GPU Company GWTN156-5   | 1         | 0.94%   |
| Gigabyte Z97-D3H        | 1         | 0.94%   |
| Gigabyte Z370           | 1         | 0.94%   |
| Gigabyte X470           | 1         | 0.94%   |
| Gigabyte H67A-UD3H-B3   | 1         | 0.94%   |
| Gigabyte F2A68HM-DS2    | 1         | 0.94%   |
| Gigabyte EG43M-S2H      | 1         | 0.94%   |
| Fujitsu ESPRIMO         | 1         | 0.94%   |
| Fujitsu CELSIUS         | 1         | 0.94%   |
| Dell Precision          | 1         | 0.94%   |
| ASUS Z170I              | 1         | 0.94%   |
| ASUS X550LC             | 1         | 0.94%   |
| ASUS ROG                | 1         | 0.94%   |
| ASUS MINIPC             | 1         | 0.94%   |
| ASUS K53SD              | 1         | 0.94%   |
| ASRock Z77              | 1         | 0.94%   |
| ASRock X370             | 1         | 0.94%   |
| ASRock B450             | 1         | 0.94%   |
| ASRock AB350            | 1         | 0.94%   |
| ASRock A300M-STX        | 1         | 0.94%   |
| Apple MacBookPro5       | 1         | 0.94%   |
| Apple MacBook6          | 1         | 0.94%   |
| Apple MacBook5          | 1         | 0.94%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 24        | 22.64%  |
| 2019 | 19        | 17.92%  |
| 2018 | 14        | 13.21%  |
| 2012 | 8         | 7.55%   |
| 2017 | 6         | 5.66%   |
| 2014 | 6         | 5.66%   |
| 2013 | 6         | 5.66%   |
| 2009 | 6         | 5.66%   |
| 2016 | 4         | 3.77%   |
| 2015 | 3         | 2.83%   |
| 2011 | 3         | 2.83%   |
| 2021 | 2         | 1.89%   |
| 2010 | 2         | 1.89%   |
| 2008 | 2         | 1.89%   |
| 2007 | 1         | 0.94%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 55        | 51.89%  |
| Desktop     | 45        | 42.45%  |
| Convertible | 3         | 2.83%   |
| Mini pc     | 3         | 2.83%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 105       | 99.06%  |
| Yes  | 1         | 0.94%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 44        | 41.51%  |
| 16.01-24.0  | 29        | 27.36%  |
| 4.01-8.0    | 18        | 16.98%  |
| 32.01-64.0  | 9         | 8.49%   |
| 24.01-32.0  | 3         | 2.83%   |
| 64.01-256.0 | 2         | 1.89%   |
| 2.01-3.0    | 1         | 0.94%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.51-1.0 | 49        | 45.79%  |
| 0.01-0.5 | 41        | 38.32%  |
| 1.01-2.0 | 9         | 8.41%   |
| 2.01-3.0 | 6         | 5.61%   |
| 3.01-4.0 | 2         | 1.87%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 62        | 57.94%  |
| 2      | 31        | 28.97%  |
| 3      | 4         | 3.74%   |
| 5      | 3         | 2.8%    |
| 4      | 3         | 2.8%    |
| 6      | 2         | 1.87%   |
| 7      | 1         | 0.93%   |
| 0      | 1         | 0.93%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 65        | 61.32%  |
| Yes       | 41        | 38.68%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 99        | 93.4%   |
| No        | 7         | 6.6%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 75        | 70.75%  |
| No        | 31        | 29.25%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 56        | 52.83%  |
| No        | 50        | 47.17%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 23        | 21.7%   |
| Germany     | 11        | 10.38%  |
| France      | 10        | 9.43%   |
| Russia      | 8         | 7.55%   |
| UK          | 7         | 6.6%    |
| Switzerland | 4         | 3.77%   |
| Spain       | 4         | 3.77%   |
| Poland      | 4         | 3.77%   |
| Norway      | 3         | 2.83%   |
| New Zealand | 3         | 2.83%   |
| Finland     | 3         | 2.83%   |
| Ukraine     | 2         | 1.89%   |
| Philippines | 2         | 1.89%   |
| Japan       | 2         | 1.89%   |
| Italy       | 2         | 1.89%   |
| Australia   | 2         | 1.89%   |
| UAE         | 1         | 0.94%   |
| Sweden      | 1         | 0.94%   |
| Serbia      | 1         | 0.94%   |
| Portugal    | 1         | 0.94%   |
| Netherlands | 1         | 0.94%   |
| Namibia     | 1         | 0.94%   |
| Malaysia    | 1         | 0.94%   |
| Luxembourg  | 1         | 0.94%   |
| Hungary     | 1         | 0.94%   |
| Hong Kong   | 1         | 0.94%   |
| Greece      | 1         | 0.94%   |
| Egypt       | 1         | 0.94%   |
| Czechia     | 1         | 0.94%   |
| Canada      | 1         | 0.94%   |
| Brazil      | 1         | 0.94%   |
| Argentina   | 1         | 0.94%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Paris          | 3         | 2.8%    |
| Franconville   | 3         | 2.8%    |
| Chrusty        | 3         | 2.8%    |
| Berlin         | 3         | 2.8%    |
| Richmond       | 2         | 1.87%   |
| Oslo           | 2         | 1.87%   |
| Obninsk        | 2         | 1.87%   |
| Kyiv           | 2         | 1.87%   |
| Jyväskylä    | 2         | 1.87%   |
| Hamilton       | 2         | 1.87%   |
| Giessen        | 2         | 1.87%   |
| Eiken          | 2         | 1.87%   |
| Cologne        | 2         | 1.87%   |
| Clemmons       | 2         | 1.87%   |
| Atascadero     | 2         | 1.87%   |
| Ōta-ku        | 1         | 0.93%   |
| Zurich         | 1         | 0.93%   |
| Yokohama       | 1         | 0.93%   |
| Yaroslavl      | 1         | 0.93%   |
| Wenatchee      | 1         | 0.93%   |
| Washington     | 1         | 0.93%   |
| Vidnoye        | 1         | 0.93%   |
| Veenendaal     | 1         | 0.93%   |
| Truro          | 1         | 0.93%   |
| Taita          | 1         | 0.93%   |
| Sydney         | 1         | 0.93%   |
| Swindon        | 1         | 0.93%   |
| Stiring-Wendel | 1         | 0.93%   |
| St Petersburg  | 1         | 0.93%   |
| Sollentuna     | 1         | 0.93%   |
| Santo Tomas    | 1         | 0.93%   |
| Salem          | 1         | 0.93%   |
| Rochester      | 1         | 0.93%   |
| Riedstadt      | 1         | 0.93%   |
| Resistencia    | 1         | 0.93%   |
| Prague         | 1         | 0.93%   |
| Phoenix        | 1         | 0.93%   |
| Peoria         | 1         | 0.93%   |
| Palm Bay       | 1         | 0.93%   |
| Oshakati       | 1         | 0.93%   |
| Omaha          | 1         | 0.93%   |
| Moscow         | 1         | 0.93%   |
| Moncton        | 1         | 0.93%   |
| Milan          | 1         | 0.93%   |
| Marysville     | 1         | 0.93%   |
| Makati City    | 1         | 0.93%   |
| Madrid         | 1         | 0.93%   |
| Luxembourg     | 1         | 0.93%   |
| Lutz           | 1         | 0.93%   |
| Lorient        | 1         | 0.93%   |
| London         | 1         | 0.93%   |
| Lenzburg       | 1         | 0.93%   |
| Larnod         | 1         | 0.93%   |
| Kuala Lumpur   | 1         | 0.93%   |
| Krasnoyarsk    | 1         | 0.93%   |
| Huntingdon     | 1         | 0.93%   |
| Huddersfield   | 1         | 0.93%   |
| Heilbronn      | 1         | 0.93%   |
| Hamburg        | 1         | 0.93%   |
| Grajewo        | 1         | 0.93%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 34        | 45     | 21.12%  |
| WDC                 | 31        | 39     | 19.25%  |
| Seagate             | 17        | 23     | 10.56%  |
| Crucial             | 11        | 13     | 6.83%   |
| Toshiba             | 10        | 12     | 6.21%   |
| SanDisk             | 9         | 9      | 5.59%   |
| Kingston            | 7         | 7      | 4.35%   |
| Hitachi             | 7         | 7      | 4.35%   |
| Micron Technology   | 4         | 4      | 2.48%   |
| HGST                | 3         | 3      | 1.86%   |
| A-DATA Technology   | 3         | 3      | 1.86%   |
| SK Hynix            | 2         | 2      | 1.24%   |
| PNY                 | 2         | 4      | 1.24%   |
| PLEXTOR             | 2         | 2      | 1.24%   |
| Patriot             | 2         | 2      | 1.24%   |
| MAXTOR              | 2         | 2      | 1.24%   |
| Gigabyte Technology | 2         | 2      | 1.24%   |
| Transcend           | 1         | 1      | 0.62%   |
| SPCC                | 1         | 1      | 0.62%   |
| Phison              | 1         | 2      | 0.62%   |
| OCZ                 | 1         | 1      | 0.62%   |
| Netac               | 1         | 1      | 0.62%   |
| LITEONIT            | 1         | 1      | 0.62%   |
| LDLC                | 1         | 1      | 0.62%   |
| KingSpec            | 1         | 1      | 0.62%   |
| Intel               | 1         | 1      | 0.62%   |
| HPT                 | 1         | 4      | 0.62%   |
| GOODRAM             | 1         | 1      | 0.62%   |
| Fujitsu             | 1         | 1      | 0.62%   |
| AMD                 | 1         | 1      | 0.62%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung SSD 860 QVO 1TB              | 5         | 2.89%   |
| Samsung SSD 850 EVO 250GB            | 3         | 1.73%   |
| WDC WDS240G2G0A-00JH30 240GB         | 2         | 1.16%   |
| WDC WD40EFRX-68N32N0 4TB             | 2         | 1.16%   |
| WDC WD2000JS-55MHB0 192GB            | 2         | 1.16%   |
| WDC WD10EZEX-21M2NA0 1TB             | 2         | 1.16%   |
| Toshiba Q300 480GB                   | 2         | 1.16%   |
| Toshiba HDWD120 2TB                  | 2         | 1.16%   |
| Seagate ST500DM002-1BD142 500GB      | 2         | 1.16%   |
| Seagate ST1000LM049-2GH172 1TB       | 2         | 1.16%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 1.16%   |
| Samsung SSD 970 EVO 250GB            | 2         | 1.16%   |
| Samsung SSD 860 EVO 500GB            | 2         | 1.16%   |
| Micron 1100 SATA 256GB               | 2         | 1.16%   |
| MAXTOR STM3320613AS 320GB            | 2         | 1.16%   |
| Gigabyte GP-GSM2NE3100TNTD 1TB       | 2         | 1.16%   |
| Crucial CT250MX500SSD1 250GB         | 2         | 1.16%   |
| Crucial CT1000MX500SSD1 1TB          | 2         | 1.16%   |
| WDC WDS500G2B0A-00SM50 500GB         | 1         | 0.58%   |
| WDC WDS500G2B0A 500GB                | 1         | 0.58%   |
| WDC WDS120G2G0A-00JH30 120GB         | 1         | 0.58%   |
| WDC WDS100T3X0C-00SJG0 1TB           | 1         | 0.58%   |
| WDC WDS100T2B0C-00PXH0 1TB           | 1         | 0.58%   |
| WDC WDS100T1X0E-00AFY0 1TB           | 1         | 0.58%   |
| WDC WDS100T1B0A-00H9H0 1TB           | 1         | 0.58%   |
| WDC WD800BEVT-75ZCT2 80GB            | 1         | 0.58%   |
| WDC WD7500BPVT-80HXZT3 752GB         | 1         | 0.58%   |
| WDC WD6400BEVT-22A0RT0 640GB         | 1         | 0.58%   |
| WDC WD60EZRZ-00GZ5B1 6TB             | 1         | 0.58%   |
| WDC WD6003FFBX-68MU3N0 6TB           | 1         | 0.58%   |
| WDC WD5000LPLX-75ZNTT0 500GB         | 1         | 0.58%   |
| WDC WD5000AAVS-00ZTB0 500GB          | 1         | 0.58%   |
| WDC WD5000AAKX-60U6AA0 500GB         | 1         | 0.58%   |
| WDC WD5000AAKX-00ERMA0 500GB         | 1         | 0.58%   |
| WDC WD5000AAKS-60WWPA0 500GB         | 1         | 0.58%   |
| WDC WD3200LPVX-75V0TT0 320GB         | 1         | 0.58%   |
| WDC WD2500AAJS-75M0A0 250GB          | 1         | 0.58%   |
| WDC WD20SPZX-22UA7T0 2TB             | 1         | 0.58%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 1         | 0.58%   |
| WDC WD10SPZX-21Z10T0 1TB             | 1         | 0.58%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.58%   |
| WDC WD10EALX-009BA0 1TB              | 1         | 0.58%   |
| WDC PC SN520 SDAPMUW-128G-1101 128GB | 1         | 0.58%   |
| Transcend TS120GMTS820S 120GB        | 1         | 0.58%   |
| Toshiba THNSF5256GPUK 256GB          | 1         | 0.58%   |
| Toshiba RD400 256GB                  | 1         | 0.58%   |
| Toshiba MQ04ABF100 1TB               | 1         | 0.58%   |
| Toshiba MQ01ACF032 320GB             | 1         | 0.58%   |
| Toshiba MQ01ABD100 1TB               | 1         | 0.58%   |
| Toshiba KXG5AZNV256G 256GB           | 1         | 0.58%   |
| SPCC Solid State Disk 240GB          | 1         | 0.58%   |
| SK Hynix SC311 SATA 512GB            | 1         | 0.58%   |
| SK Hynix HFM256GDJTNG-8310A 256GB    | 1         | 0.58%   |
| Seagate ST9250410AS 250GB            | 1         | 0.58%   |
| Seagate ST500LM030-2E717D 500GB      | 1         | 0.58%   |
| Seagate ST500LM021-1KJ152 500GB      | 1         | 0.58%   |
| Seagate ST3500312CS 500GB            | 1         | 0.58%   |
| Seagate ST31500541AS 1.5TB           | 1         | 0.58%   |
| Seagate ST31000528AS 1TB             | 1         | 0.58%   |
| Seagate ST2000NM0008-2F3100 2TB      | 1         | 0.58%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 23        | 29     | 35.94%  |
| Seagate             | 17        | 23     | 26.56%  |
| Hitachi             | 7         | 7      | 10.94%  |
| Toshiba             | 5         | 5      | 7.81%   |
| Samsung Electronics | 5         | 6      | 7.81%   |
| HGST                | 3         | 3      | 4.69%   |
| MAXTOR              | 2         | 2      | 3.13%   |
| HPT                 | 1         | 4      | 1.56%   |
| Fujitsu             | 1         | 1      | 1.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 22        | 28     | 28.57%  |
| Crucial             | 10        | 12     | 12.99%  |
| SanDisk             | 9         | 9      | 11.69%  |
| WDC                 | 6         | 6      | 7.79%   |
| Kingston            | 6         | 6      | 7.79%   |
| Micron Technology   | 4         | 4      | 5.19%   |
| A-DATA Technology   | 3         | 3      | 3.9%    |
| Toshiba             | 2         | 2      | 2.6%    |
| PNY                 | 2         | 4      | 2.6%    |
| PLEXTOR             | 2         | 2      | 2.6%    |
| Patriot             | 2         | 2      | 2.6%    |
| Transcend           | 1         | 1      | 1.3%    |
| SPCC                | 1         | 1      | 1.3%    |
| SK Hynix            | 1         | 1      | 1.3%    |
| OCZ                 | 1         | 1      | 1.3%    |
| Netac               | 1         | 1      | 1.3%    |
| LITEONIT            | 1         | 1      | 1.3%    |
| KingSpec            | 1         | 1      | 1.3%    |
| GOODRAM             | 1         | 1      | 1.3%    |
| AMD                 | 1         | 1      | 1.3%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 61        | 87     | 44.2%   |
| HDD  | 52        | 80     | 37.68%  |
| NVMe | 25        | 29     | 18.12%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 96        | 167    | 79.34%  |
| NVMe | 25        | 29     | 20.66%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 70        | 88     | 56.91%  |
| 0.51-1.0   | 35        | 53     | 28.46%  |
| 1.01-2.0   | 10        | 13     | 8.13%   |
| 3.01-4.0   | 4         | 4      | 3.25%   |
| 4.01-10.0  | 3         | 7      | 2.44%   |
| 10.01-20.0 | 1         | 2      | 0.81%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 33        | 30.28%  |
| 251-500    | 24        | 22.02%  |
| 1-20       | 22        | 20.18%  |
| 501-1000   | 11        | 10.09%  |
| 51-100     | 11        | 10.09%  |
| Unknown    | 6         | 5.5%    |
| 21-50      | 1         | 0.92%   |
| 1001-2000  | 1         | 0.92%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 94        | 86.24%  |
| 21-50   | 9         | 8.26%   |
| Unknown | 6         | 5.5%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                           | Computers | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| MAXTOR STM3320613AS 320GB                       | 2         | 2      | 11.76%  |
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

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 23.53%  |
| Seagate             | 3         | 3      | 17.65%  |
| Hitachi             | 3         | 3      | 17.65%  |
| Samsung Electronics | 2         | 3      | 11.76%  |
| MAXTOR              | 2         | 2      | 11.76%  |
| Toshiba             | 1         | 1      | 5.88%   |
| OCZ                 | 1         | 1      | 5.88%   |
| Micron Technology   | 1         | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 28.57%  |
| Seagate             | 3         | 3      | 21.43%  |
| Hitachi             | 3         | 3      | 21.43%  |
| MAXTOR              | 2         | 2      | 14.29%  |
| Toshiba             | 1         | 1      | 7.14%   |
| Samsung Electronics | 1         | 2      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


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

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 98        | 174    | 85.22%  |
| Malfunc  | 16        | 18     | 13.91%  |
| Detected | 1         | 4      | 0.87%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 66        | 51.16%  |
| AMD                           | 31        | 24.03%  |
| Samsung Electronics           | 11        | 8.53%   |
| Nvidia                        | 4         | 3.1%    |
| Phison Electronics            | 3         | 2.33%   |
| Toshiba                       | 2         | 1.55%   |
| Sandisk                       | 2         | 1.55%   |
| SK Hynix                      | 1         | 0.78%   |
| Silicon Motion                | 1         | 0.78%   |
| OCZ Technology Group          | 1         | 0.78%   |
| Micron/Crucial Technology     | 1         | 0.78%   |
| Marvell Technology Group      | 1         | 0.78%   |
| Kingston Technology Company   | 1         | 0.78%   |
| Integrated Technology Express | 1         | 0.78%   |
| HighPoint Technologies        | 1         | 0.78%   |
| ASMedia Technology            | 1         | 0.78%   |
| Adaptec                       | 1         | 0.78%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 26        | 17.81%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 9         | 6.16%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 8         | 5.48%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 8         | 5.48%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 7         | 4.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 7         | 4.79%   |
| AMD 400 Series Chipset SATA Controller                                                  | 6         | 4.11%   |
| Intel SATA Controller [RAID mode]                                                       | 5         | 3.42%   |
| Nvidia MCP79 AHCI Controller                                                            | 3         | 2.05%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 3         | 2.05%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 3         | 2.05%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3         | 2.05%   |
| Phison PS5013 E13 NVMe Controller                                                       | 2         | 1.37%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 2         | 1.37%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 2         | 1.37%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2         | 1.37%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2         | 1.37%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 2         | 1.37%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 2         | 1.37%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 2         | 1.37%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.37%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.37%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2         | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2         | 1.37%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 2         | 1.37%   |
| AMD FCH SATA Controller D                                                               | 2         | 1.37%   |
| Toshiba XG4 NVMe SSD Controller                                                         | 1         | 0.68%   |
| Toshiba unknown                                                                         | 1         | 0.68%   |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 1         | 0.68%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1         | 0.68%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 1         | 0.68%   |
| Sandisk PC SN520 NVMe SSD                                                               | 1         | 0.68%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1         | 0.68%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1         | 0.68%   |
| Phison E12 NVMe Controller                                                              | 1         | 0.68%   |
| OCZ Group RD400/400A SSD                                                                | 1         | 0.68%   |
| Nvidia GeForce 7100/nForce 630i SATA                                                    | 1         | 0.68%   |
| Micron/Crucial NVMe Controller                                                          | 1         | 0.68%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 1         | 0.68%   |
| Kingston Company A2000 NVMe SSD                                                         | 1         | 0.68%   |
| Intel SSD 660P Series                                                                   | 1         | 0.68%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1         | 0.68%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1         | 0.68%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 1         | 0.68%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 1         | 0.68%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1         | 0.68%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1         | 0.68%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1         | 0.68%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 1         | 0.68%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1         | 0.68%   |
| Integrated Express IT8213 IDE Controller                                                | 1         | 0.68%   |
| HighPoint RocketRAID 230x 4 Port SATA-II Controller                                     | 1         | 0.68%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1         | 0.68%   |
| AMD X370 Series Chipset SATA Controller                                                 | 1         | 0.68%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 1         | 0.68%   |
| Adaptec AIC-7850T/7856T [AVA-2902/4/6 / AHA-2910]                                       | 1         | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 86        | 67.19%  |
| NVMe | 24        | 18.75%  |
| RAID | 8         | 6.25%   |
| IDE  | 8         | 6.25%   |
| SCSI | 2         | 1.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 74        | 69.81%  |
| AMD    | 32        | 30.19%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz            | 3         | 2.83%   |
| Intel Core i5-3320M CPU @ 2.60GHz            | 3         | 2.83%   |
| AMD Ryzen 7 3700X 8-Core Processor           | 3         | 2.83%   |
| AMD Ryzen 7 2700X Eight-Core Processor       | 3         | 2.83%   |
| AMD Ryzen 5 2600 Six-Core Processor          | 3         | 2.83%   |
| Intel Core i7-3520M CPU @ 2.90GHz            | 2         | 1.89%   |
| Intel Core i5-8350U CPU @ 1.70GHz            | 2         | 1.89%   |
| Intel Core i5-6300U CPU @ 2.40GHz            | 2         | 1.89%   |
| Intel Core i5-5300U CPU @ 2.30GHz            | 2         | 1.89%   |
| Intel Core i5-3230M CPU @ 2.60GHz            | 2         | 1.89%   |
| Intel Core i5-2520M CPU @ 2.50GH             | 2         | 1.89%   |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz         | 2         | 1.89%   |
| AMD A4-9125 RADEON R3, 4 COMPUTE CORES 2C+2G | 2         | 1.89%   |
| Intel Xeon CPU W3680 @ 3.33GHz               | 1         | 0.94%   |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz           | 1         | 0.94%   |
| Intel Xeon                                   | 1         | 0.94%   |
| Intel Unknown                                | 1         | 0.94%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz  | 1         | 0.94%   |
| Intel Pentium CPU G620 @ 2.60GHz             | 1         | 0.94%   |
| Intel Pentium 3558U @ 1.70GHz                | 1         | 0.94%   |
| Intel Genuine CPU                            | 1         | 0.94%   |
| Intel Core i7-8700 CPU @ 3.20GHz             | 1         | 0.94%   |
| Intel Core i7-8565U CPU @ 1.80GHz            | 1         | 0.94%   |
| Intel Core i7-8550U CPU @ 1.80GHz            | 1         | 0.94%   |
| Intel Core i7-6770HQ CPU @ 2.60GHz           | 1         | 0.94%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz           | 1         | 0.94%   |
| Intel Core i7-6500U CPU @ 2.50GHz            | 1         | 0.94%   |
| Intel Core i7-4790K CPU @ 4.00GHz            | 1         | 0.94%   |
| Intel Core i7-4500U CPU @ 1.80GHz            | 1         | 0.94%   |
| Intel Core i7-3770S CPU @ 3.10GHz            | 1         | 0.94%   |
| Intel Core i7-3770 CPU @ 3.40GHz             | 1         | 0.94%   |
| Intel Core i7-3720QM CPU @ 2.60GHz           | 1         | 0.94%   |
| Intel Core i7-2670QM CPU @ 2.20GHz           | 1         | 0.94%   |
| Intel Core i7-2600K CPU                      | 1         | 0.94%   |
| Intel Core i5-8600K CPU @ 3.60GHz            | 1         | 0.94%   |
| Intel Core i5-8400T CPU @ 1.70GHz            | 1         | 0.94%   |
| Intel Core i5-8300H CPU @ 2.30GHz            | 1         | 0.94%   |
| Intel Core i5-8259U CPU @ 2.30GHz            | 1         | 0.94%   |
| Intel Core i5-8250U CPU @ 1.60GHz            | 1         | 0.94%   |
| Intel Core i5-7500 CPU @ 3.40GHz             | 1         | 0.94%   |
| Intel Core i5-7300U CPU @ 2.60GHz            | 1         | 0.94%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz           | 1         | 0.94%   |
| Intel Core i5-6600K CPU @ 3.50GHz            | 1         | 0.94%   |
| Intel Core i5-5200U CPU @ 2.20GHz            | 1         | 0.94%   |
| Intel Core i5-4570 CPU @ 3.20GHz             | 1         | 0.94%   |
| Intel Core i5-4440 CPU @ 3.10GHz             | 1         | 0.94%   |
| Intel Core i5-4310U CPU @ 2.00GHz            | 1         | 0.94%   |
| Intel Core i5-4300U CPU @ 1.90GHz            | 1         | 0.94%   |
| Intel Core i5-4210U CPU @ 1.70GHz            | 1         | 0.94%   |
| Intel Core i5-4200U CPU @ 1.60GHz            | 1         | 0.94%   |
| Intel Core i5-2520M CPU @ 2.50GHz            | 1         | 0.94%   |
| Intel Core i5-2500 CPU @ 3.30GH              | 1         | 0.94%   |
| Intel Core i5-2430M CPU @ 2.40GH             | 1         | 0.94%   |
| Intel Core i5-2410M CPU @ 2.30GHz            | 1         | 0.94%   |
| Intel Core i5-10210U CPU @ 1.60GHz           | 1         | 0.94%   |
| Intel Core i3-7100U CPU @ 2.40GHz            | 1         | 0.94%   |
| Intel Core i3-4160 CPU @ 3.60GHz             | 1         | 0.94%   |
| Intel Core i3-4010U CPU @ 1.70GHz            | 1         | 0.94%   |
| Intel Core i3-4005U CPU @ 1.70GHz            | 1         | 0.94%   |
| Intel Core i3-2330M CPU @ 2.20GHz            | 1         | 0.94%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 37        | 34.91%  |
| Intel Core i7           | 15        | 14.15%  |
| AMD Ryzen 5             | 9         | 8.49%   |
| AMD Ryzen 7             | 7         | 6.6%    |
| Intel Core i3           | 5         | 4.72%   |
| Intel Core 2 Duo        | 5         | 4.72%   |
| AMD Ryzen 3             | 4         | 3.77%   |
| Intel Xeon              | 3         | 2.83%   |
| Other                   | 2         | 1.89%   |
| Intel Pentium           | 2         | 1.89%   |
| Intel Core 2 Quad       | 2         | 1.89%   |
| AMD E1                  | 2         | 1.89%   |
| AMD A6                  | 2         | 1.89%   |
| AMD A4                  | 2         | 1.89%   |
| Intel Pentium Dual-Core | 1         | 0.94%   |
| Intel Genuine           | 1         | 0.94%   |
| Intel Core 2            | 1         | 0.94%   |
| Intel Celeron           | 1         | 0.94%   |
| AMD Ryzen 9             | 1         | 0.94%   |
| AMD Ryzen 3 PRO         | 1         | 0.94%   |
| AMD E2                  | 1         | 0.94%   |
| AMD Athlon X4           | 1         | 0.94%   |
| AMD A10                 | 1         | 0.94%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 45        | 42.45%  |
| 4       | 30        | 28.3%   |
| Unknown | 7         | 6.6%    |
| 16      | 6         | 5.66%   |
| 12      | 6         | 5.66%   |
| 8       | 6         | 5.66%   |
| 6       | 5         | 4.72%   |
| 32      | 1         | 0.94%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 103       | 97.17%  |
| 2      | 3         | 2.83%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 52        | 49.06%  |
| 1       | 47        | 44.34%  |
| Unknown | 7         | 6.6%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 18        | 16.98%  |
| Haswell     | 13        | 12.26%  |
| SandyBridge | 11        | 10.38%  |
| Zen+        | 10        | 9.43%   |
| Penryn      | 10        | 9.43%   |
| IvyBridge   | 10        | 9.43%   |
| Zen 2       | 8         | 7.55%   |
| Skylake     | 6         | 5.66%   |
| Zen         | 3         | 2.83%   |
| Excavator   | 3         | 2.83%   |
| Broadwell   | 3         | 2.83%   |
| Westmere    | 2         | 1.89%   |
| Puma        | 2         | 1.89%   |
| Piledriver  | 2         | 1.89%   |
| Zen 3       | 1         | 0.94%   |
| K10         | 1         | 0.94%   |
| Jaguar      | 1         | 0.94%   |
| Core        | 1         | 0.94%   |
| Bobcat      | 1         | 0.94%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 58        | 48.74%  |
| Nvidia | 39        | 32.77%  |
| AMD    | 22        | 18.49%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 10        | 8.2%    |
| Intel Haswell-ULT Integrated Graphics Controller                              | 9         | 7.38%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 8         | 6.56%   |
| Intel HD Graphics 620                                                         | 5         | 4.1%    |
| Intel UHD Graphics 620                                                        | 4         | 3.28%   |
| AMD Picasso                                                                   | 4         | 3.28%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 3         | 2.46%   |
| Nvidia GM206 [GeForce GTX 960]                                                | 3         | 2.46%   |
| Nvidia GK107 [GeForce GTX 650]                                                | 3         | 2.46%   |
| Nvidia C79 [GeForce 9400M]                                                    | 3         | 2.46%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 3         | 2.46%   |
| Intel HD Graphics 5500                                                        | 3         | 2.46%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 3         | 2.46%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 2         | 1.64%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                            | 2         | 1.64%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                             | 2         | 1.64%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 2         | 1.64%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 2         | 1.64%   |
| Intel HD Graphics 630                                                         | 2         | 1.64%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                      | 2         | 1.64%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                            | 1         | 0.82%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                         | 1         | 0.82%   |
| Nvidia TU104 [GeForce RTX 2080]                                               | 1         | 0.82%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 0.82%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 1         | 0.82%   |
| Nvidia GP107 [GeForce GTX 1050]                                               | 1         | 0.82%   |
| Nvidia GP104 [GeForce GTX 1080]                                               | 1         | 0.82%   |
| Nvidia GP104 [GeForce GTX 1070]                                               | 1         | 0.82%   |
| Nvidia GM206M [GeForce GTX 965M]                                              | 1         | 0.82%   |
| Nvidia GM108M [GeForce MX130]                                                 | 1         | 0.82%   |
| Nvidia GM107 [GeForce GTX 745]                                                | 1         | 0.82%   |
| Nvidia GM107 [GeForce 940MX]                                                  | 1         | 0.82%   |
| Nvidia GK208BM [GeForce 920M]                                                 | 1         | 0.82%   |
| Nvidia GK107 [GeForce GT 740]                                                 | 1         | 0.82%   |
| Nvidia GK107 [GeForce GT 640]                                                 | 1         | 0.82%   |
| Nvidia GF119M [GeForce 610M]                                                  | 1         | 0.82%   |
| Nvidia GF108GLM [NVS 5200M]                                                   | 1         | 0.82%   |
| Nvidia GF108GL [Quadro 600]                                                   | 1         | 0.82%   |
| Nvidia GF100GL [Quadro 4000]                                                  | 1         | 0.82%   |
| Nvidia GA104 [GeForce RTX 3070]                                               | 1         | 0.82%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 1         | 0.82%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 1         | 0.82%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 1         | 0.82%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 1         | 0.82%   |
| Intel Iris Pro Graphics 580                                                   | 1         | 0.82%   |
| Intel HD Graphics 530                                                         | 1         | 0.82%   |
| Intel Core Processor Integrated Graphics Controller                           | 1         | 0.82%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 1         | 0.82%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                      | 1         | 0.82%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                              | 1         | 0.82%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 1         | 0.82%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller     | 1         | 0.82%   |
| Intel 4 Series Chipset Integrated Graphics Controller                         | 1         | 0.82%   |
| AMD Wrestler [Radeon HD 7310]                                                 | 1         | 0.82%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                           | 1         | 0.82%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                             | 1         | 0.82%   |
| AMD RV635/M86 [Mobility Radeon HD 3650]                                       | 1         | 0.82%   |
| AMD Renoir                                                                    | 1         | 0.82%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 1         | 0.82%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                           | 1         | 0.82%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 43        | 40.57%  |
| 1 x Nvidia     | 26        | 24.53%  |
| 1 x AMD        | 19        | 17.92%  |
| Intel + Nvidia | 11        | 10.38%  |
| 2 x Intel      | 3         | 2.83%   |
| 2 x Nvidia     | 1         | 0.94%   |
| 2 x AMD        | 1         | 0.94%   |
| Intel + AMD    | 1         | 0.94%   |
| AMD + Nvidia   | 1         | 0.94%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 79        | 74.53%  |
| Proprietary | 27        | 25.47%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 67        | 63.21%  |
| 1.01-2.0   | 10        | 9.43%   |
| 3.01-4.0   | 8         | 7.55%   |
| 7.01-8.0   | 7         | 6.6%    |
| 0.51-1.0   | 7         | 6.6%    |
| 0.01-0.5   | 6         | 5.66%   |
| 2.01-3.0   | 1         | 0.94%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 12        | 12.24%  |
| LG Display           | 12        | 12.24%  |
| Chimei Innolux       | 10        | 10.2%   |
| AU Optronics         | 9         | 9.18%   |
| Dell                 | 7         | 7.14%   |
| Goldstar             | 6         | 6.12%   |
| Philips              | 4         | 4.08%   |
| BOE                  | 4         | 4.08%   |
| BenQ                 | 4         | 4.08%   |
| Lenovo               | 3         | 3.06%   |
| Hewlett-Packard      | 3         | 3.06%   |
| ViewSonic            | 2         | 2.04%   |
| LG Electronics       | 2         | 2.04%   |
| Iiyama               | 2         | 2.04%   |
| AOC                  | 2         | 2.04%   |
| WYT                  | 1         | 1.02%   |
| Vizio                | 1         | 1.02%   |
| Toshiba              | 1         | 1.02%   |
| Pixio                | 1         | 1.02%   |
| PANDA                | 1         | 1.02%   |
| Panasonic            | 1         | 1.02%   |
| OEM                  | 1         | 1.02%   |
| InfoVision           | 1         | 1.02%   |
| Idek Iiyama          | 1         | 1.02%   |
| IBM                  | 1         | 1.02%   |
| HannStar             | 1         | 1.02%   |
| CSO                  | 1         | 1.02%   |
| CHD                  | 1         | 1.02%   |
| ASUSTek Computer     | 1         | 1.02%   |
| Ancor Communications | 1         | 1.02%   |
| Acer                 | 1         | 1.02%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch      | 2         | 1.94%   |
| LG Display LCD Monitor LGD0456 1366x768 340x190mm 15.3-inch            | 2         | 1.94%   |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch            | 2         | 1.94%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch       | 2         | 1.94%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 340x190mm 15.3-inch          | 2         | 1.94%   |
| WYT MNT-ANALOG WYT0323 1280x1024 330x270mm 16.8-inch                   | 1         | 0.97%   |
| Vizio E320i-B2 VIZ1002 1360x768 700x400mm 31.7-inch                    | 1         | 0.97%   |
| ViewSonic VX3209-2K VSC328E 2560x1440 700x390mm 31.5-inch              | 1         | 0.97%   |
| ViewSonic LCD Monitor VA1938 Series                                    | 1         | 0.97%   |
| Toshiba TV TSB010F 1920x1080 890x500mm 40.2-inch                       | 1         | 0.97%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 470x300mm 22.0-inch   | 1         | 0.97%   |
| Samsung Electronics SyncMaster SAM010B 1280x1024 340x270mm 17.1-inch   | 1         | 0.97%   |
| Samsung Electronics SMBX2231 SAM076D 1920x1080 480x270mm 21.7-inch     | 1         | 0.97%   |
| Samsung Electronics SA300/SA350 SAM078F 1920x1080 480x270mm 21.7-inch  | 1         | 0.97%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x170mm 13.9-inch   | 1         | 0.97%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 330x210mm 15.4-inch   | 1         | 0.97%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 310x170mm 13.9-inch   | 1         | 0.97%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 340x190mm 15.3-inch   | 1         | 0.97%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch   | 1         | 0.97%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 340x190mm 15.3-inch   | 1         | 0.97%   |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 1210x680mm 54.6-inch | 1         | 0.97%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 890x500mm 40.2-inch  | 1         | 0.97%   |
| Samsung Electronics LCD Monitor SAM02A4 1360x768                       | 1         | 0.97%   |
| Pixio PX247 PNS0247 1920x1080 520x310mm 23.8-inch                      | 1         | 0.97%   |
| Philips PHL BDM4065 PHL08E1 3840x2160 880x490mm 39.7-inch              | 1         | 0.97%   |
| Philips PHL 240V5 PHLC10A 1920x1080 530x300mm 24.0-inch                | 1         | 0.97%   |
| Philips LCD Monitor PHL 240V5 1920x1080                                | 1         | 0.97%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                     | 1         | 0.97%   |
| PANDA LCD Monitor NCP0040 1920x1080 340x190mm 15.3-inch                | 1         | 0.97%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch           | 1         | 0.97%   |
| OEM 32W_LCD_TV OEM3700 1920x540                                        | 1         | 0.97%   |
| LG Electronics LCD Monitor W1952 2806x900                              | 1         | 0.97%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                      | 1         | 0.97%   |
| LG Display LCD Monitor LGD05B3 1920x1080 290x170mm 13.2-inch           | 1         | 0.97%   |
| LG Display LCD Monitor LGD0558 1920x1080 310x170mm 13.9-inch           | 1         | 0.97%   |
| LG Display LCD Monitor LGD0533 1920x1080 340x190mm 15.3-inch           | 1         | 0.97%   |
| LG Display LCD Monitor LGD052D 1920x1080 290x170mm 13.2-inch           | 1         | 0.97%   |
| LG Display LCD Monitor LGD0430 1366x768 350x190mm 15.7-inch            | 1         | 0.97%   |
| LG Display LCD Monitor LGD042D 1920x1080 290x170mm 13.2-inch           | 1         | 0.97%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch            | 1         | 0.97%   |
| LG Display LCD Monitor LGD01CA 1600x900 380x210mm 17.1-inch            | 1         | 0.97%   |
| Lenovo V20-10 LEN65DC 1600x900 430x240mm 19.4-inch                     | 1         | 0.97%   |
| Lenovo LEN P27h-10 LEN61AF 2560x1440 600x340mm 27.2-inch               | 1         | 0.97%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch                | 1         | 0.97%   |
| InfoVision LCD Monitor IVO04E3 1366x768 280x160mm 12.7-inch            | 1         | 0.97%   |
| Iiyama PL2783Q IVM661F 2560x1440 600x340mm 27.2-inch                   | 1         | 0.97%   |
| Iiyama PL2492H IVM612F 1920x1080 530x300mm 24.0-inch                   | 1         | 0.97%   |
| Idek Iiyama LCD Monitor PL3270Q 5120x1440                              | 1         | 0.97%   |
| Idek Iiyama LCD Monitor PL3270Q                                        | 1         | 0.97%   |
| IBM LCD Monitor IBM2887 1680x1050 330x210mm 15.4-inch                  | 1         | 0.97%   |
| Hewlett-Packard LCD Monitor HWP4218 1600x900 440x250mm 19.9-inch       | 1         | 0.97%   |
| Hewlett-Packard LA2205 HWP2848 1680x1050 470x300mm 22.0-inch           | 1         | 0.97%   |
| Hewlett-Packard 22w HPN342E 1920x1080 480x270mm 21.7-inch              | 1         | 0.97%   |
| HannStar LCD Monitor HSD2469 1680x1050 470x300mm 22.0-inch             | 1         | 0.97%   |
| Goldstar W2261 GSM56CF 1920x1080 530x300mm 24.0-inch                   | 1         | 0.97%   |
| Goldstar W1934 GSM4B7A 1440x900 410x260mm 19.1-inch                    | 1         | 0.97%   |
| Goldstar LG ULTRAWIDE GSM76FA 2560x1080 800x340mm 34.2-inch            | 1         | 0.97%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch            | 1         | 0.97%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch             | 1         | 0.97%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch              | 1         | 0.97%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 33        | 32.35%  |
| 1366x768 (WXGA)    | 24        | 23.53%  |
| 1600x900 (HD+)     | 9         | 8.82%   |
| 3840x2160 (4K)     | 6         | 5.88%   |
| 2560x1440 (QHD)    | 6         | 5.88%   |
| 1680x1050 (WSXGA+) | 4         | 3.92%   |
| 1280x1024 (SXGA)   | 4         | 3.92%   |
| 2560x1080          | 3         | 2.94%   |
| Unknown            | 3         | 2.94%   |
| 3840x1600          | 2         | 1.96%   |
| 1360x768           | 2         | 1.96%   |
| 5120x1440          | 1         | 0.98%   |
| 3200x1080          | 1         | 0.98%   |
| 2880x1620          | 1         | 0.98%   |
| 2806x900           | 1         | 0.98%   |
| 1920x540           | 1         | 0.98%   |
| 1440x900 (WXGA+)   | 1         | 0.98%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 25        | 25.25%  |
| 13      | 17        | 17.17%  |
| Unknown | 8         | 8.08%   |
| 27      | 7         | 7.07%   |
| 21      | 6         | 6.06%   |
| 23      | 5         | 5.05%   |
| 19      | 5         | 5.05%   |
| 24      | 4         | 4.04%   |
| 17      | 4         | 4.04%   |
| 22      | 3         | 3.03%   |
| 12      | 3         | 3.03%   |
| 40      | 2         | 2.02%   |
| 31      | 2         | 2.02%   |
| 65      | 1         | 1.01%   |
| 54      | 1         | 1.01%   |
| 39      | 1         | 1.01%   |
| 37      | 1         | 1.01%   |
| 34      | 1         | 1.01%   |
| 32      | 1         | 1.01%   |
| 28      | 1         | 1.01%   |
| 16      | 1         | 1.01%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 41        | 41.84%  |
| 501-600     | 14        | 14.29%  |
| 401-500     | 13        | 13.27%  |
| Unknown     | 8         | 8.16%   |
| 201-300     | 6         | 6.12%   |
| 601-700     | 5         | 5.1%    |
| 801-900     | 4         | 4.08%   |
| 351-400     | 3         | 3.06%   |
| 701-800     | 2         | 2.04%   |
| 1001-1500   | 2         | 2.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 74        | 78.72%  |
| 16/10   | 6         | 6.38%   |
| Unknown | 6         | 6.38%   |
| 5/4     | 3         | 3.19%   |
| 21/9    | 3         | 3.19%   |
| 6/5     | 1         | 1.06%   |
| 32/9    | 1         | 1.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 91-100         | 22        | 22.22%  |
| 201-250        | 18        | 18.18%  |
| 81-90          | 14        | 14.14%  |
| Unknown        | 8         | 8.08%   |
| 301-350        | 7         | 7.07%   |
| 151-200        | 5         | 5.05%   |
| 351-500        | 4         | 4.04%   |
| 501-1000       | 4         | 4.04%   |
| 71-80          | 3         | 3.03%   |
| 61-70          | 3         | 3.03%   |
| 101-110        | 3         | 3.03%   |
| More than 1000 | 2         | 2.02%   |
| 141-150        | 2         | 2.02%   |
| 121-130        | 2         | 2.02%   |
| 251-300        | 1         | 1.01%   |
| 131-140        | 1         | 1.01%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 31        | 31.63%  |
| 51-100        | 30        | 30.61%  |
| 121-160       | 20        | 20.41%  |
| Unknown       | 8         | 8.16%   |
| 161-240       | 6         | 6.12%   |
| 1-50          | 2         | 2.04%   |
| More than 240 | 1         | 1.02%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 78        | 72.9%   |
| 0     | 15        | 14.02%  |
| 2     | 14        | 13.08%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 56        | 35.67%  |
| Realtek Semiconductor             | 45        | 28.66%  |
| Qualcomm Atheros                  | 20        | 12.74%  |
| Broadcom                          | 13        | 8.28%   |
| TP-Link                           | 7         | 4.46%   |
| Nvidia                            | 4         | 2.55%   |
| Ericsson Business Mobile Networks | 3         | 1.91%   |
| Qualcomm                          | 2         | 1.27%   |
| Ralink                            | 1         | 0.64%   |
| Microchip Technology              | 1         | 0.64%   |
| Marvell Technology Group          | 1         | 0.64%   |
| Fibocom                           | 1         | 0.64%   |
| Edimax Technology                 | 1         | 0.64%   |
| ASUSTek Computer                  | 1         | 0.64%   |
| Aquantia                          | 1         | 0.64%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 32        | 16.67%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 5.73%   |
| Intel I211 Gigabit Network Connection                             | 8         | 4.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 3.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 3.13%   |
| Intel Wireless 8265 / 8275                                        | 6         | 3.13%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 2.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 2.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 2.08%   |
| Intel Wireless 7265                                               | 4         | 2.08%   |
| Intel Wireless 7260                                               | 4         | 2.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 2.08%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 3         | 1.56%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 1.56%   |
| Nvidia MCP79 Ethernet                                             | 3         | 1.56%   |
| Intel Wireless 8260                                               | 3         | 1.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 1.56%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 2         | 1.04%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 2         | 1.04%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2         | 1.04%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 2         | 1.04%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 1.04%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.04%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.04%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.04%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.04%   |
| Intel Centrino Ultimate-N 6300                                    | 2         | 1.04%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 1.04%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 1.04%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2         | 1.04%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 2         | 1.04%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 1.04%   |
| TP-Link TP-LINK Wireless USB Adapter                              | 1         | 0.52%   |
| TP-Link TP-Link High Power Wireless USB Adapter                   | 1         | 0.52%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1         | 0.52%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1         | 0.52%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.52%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.52%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.52%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.52%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.52%   |
| Realtek Realtek Bluetooth 4.2 Adapter                             | 1         | 0.52%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter            | 1         | 0.52%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 0.52%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.52%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.52%   |
| Nvidia MCP73 Ethernet                                             | 1         | 0.52%   |
| Microchip HTC Hub Controller                                      | 1         | 0.52%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.52%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 0.52%   |
| Intel Wireless-AC 9260                                            | 1         | 0.52%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 1         | 0.52%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 1         | 0.52%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.52%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.52%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.52%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 38        | 46.34%  |
| Qualcomm Atheros      | 17        | 20.73%  |
| Realtek Semiconductor | 12        | 14.63%  |
| TP-Link               | 7         | 8.54%   |
| Broadcom              | 5         | 6.1%    |
| Ralink                | 1         | 1.22%   |
| Edimax Technology     | 1         | 1.22%   |
| ASUSTek Computer      | 1         | 1.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 6         | 7.23%   |
| Intel Wireless 8265 / 8275                                     | 6         | 7.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4         | 4.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4         | 4.82%   |
| Intel Wireless 7265                                            | 4         | 4.82%   |
| Intel Wireless 7260                                            | 4         | 4.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 4.82%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 3         | 3.61%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 3.61%   |
| Intel Wireless 8260                                            | 3         | 3.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 3.61%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 2         | 2.41%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 2.41%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2         | 2.41%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 2.41%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 2.41%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 2.41%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 2         | 2.41%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 2.41%   |
| TP-Link TP-LINK Wireless USB Adapter                           | 1         | 1.2%    |
| TP-Link TP-Link High Power Wireless USB Adapter                | 1         | 1.2%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 1.2%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 1.2%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.2%    |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 1.2%    |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 1.2%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 1.2%    |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 1.2%    |
| Realtek Realtek Bluetooth 4.2 Adapter                          | 1         | 1.2%    |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter         | 1         | 1.2%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 1.2%    |
| Intel Wireless-AC 9260                                         | 1         | 1.2%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 1.2%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 1.2%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 1.2%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 1         | 1.2%    |
| Intel Centrino Wireless-N 100                                  | 1         | 1.2%    |
| Intel Centrino Advanced-N 6235                                 | 1         | 1.2%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 1.2%    |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 1         | 1.2%    |
| Broadcom BCM43224 802.11a/b/g/n                                | 1         | 1.2%    |
| ASUS ASUS Wireless USB adapter                                 | 1         | 1.2%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 41        | 40.2%   |
| Realtek Semiconductor    | 40        | 39.22%  |
| Broadcom                 | 9         | 8.82%   |
| Qualcomm Atheros         | 4         | 3.92%   |
| Nvidia                   | 4         | 3.92%   |
| Qualcomm                 | 2         | 1.96%   |
| Marvell Technology Group | 1         | 0.98%   |
| Aquantia                 | 1         | 0.98%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 32        | 30.77%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 10.58%  |
| Intel I211 Gigabit Network Connection                             | 8         | 7.69%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 6.73%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 4.81%   |
| Nvidia MCP79 Ethernet                                             | 3         | 2.88%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 2         | 1.92%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.92%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.92%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.92%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.92%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 1.92%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2         | 1.92%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.96%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.96%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.96%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.96%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.96%   |
| Nvidia MCP73 Ethernet                                             | 1         | 0.96%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.96%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 0.96%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.96%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.96%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.96%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.96%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.96%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.96%   |
| Intel 82576 Gigabit Network Connection                            | 1         | 0.96%   |
| Intel 82567V-2 Gigabit Network Connection                         | 1         | 0.96%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.96%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.96%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 0.96%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 1         | 0.96%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 0.96%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.96%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 1         | 0.96%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 0.96%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 99        | 55%     |
| WiFi     | 76        | 42.22%  |
| Modem    | 3         | 1.67%   |
| Unknown  | 2         | 1.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 97        | 62.18%  |
| WiFi     | 58        | 37.18%  |
| Modem    | 1         | 0.64%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 63        | 59.43%  |
| 1     | 40        | 37.74%  |
| 3     | 3         | 2.83%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 106       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 24        | 43.64%  |
| Broadcom                        | 7         | 12.73%  |
| Qualcomm Atheros Communications | 6         | 10.91%  |
| Realtek Semiconductor           | 4         | 7.27%   |
| Lite-On Technology              | 4         | 7.27%   |
| Apple                           | 3         | 5.45%   |
| Cambridge Silicon Radio         | 2         | 3.64%   |
| Alps Electric                   | 2         | 3.64%   |
| HTC (High Tech Computer)        | 1         | 1.82%   |
| Dell                            | 1         | 1.82%   |
| ASUSTek Computer                | 1         | 1.82%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                   | 14        | 25.45%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 4         | 7.27%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 3         | 5.45%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 3         | 5.45%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 3         | 5.45%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 3         | 5.45%   |
| Apple Bluetooth Host Controller                                      | 3         | 5.45%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                              | 2         | 3.64%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 2         | 3.64%   |
| Lite-On Atheros AR3012 Bluetooth                                     | 2         | 3.64%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 2         | 3.64%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2         | 3.64%   |
| Realtek  Bluetooth Adapter                                           | 1         | 1.82%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device          | 1         | 1.82%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 1         | 1.82%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 1         | 1.82%   |
| Intel AX200 Bluetooth                                                | 1         | 1.82%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1         | 1.82%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                          | 1         | 1.82%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                   | 1         | 1.82%   |
| Broadcom BCM2045B (BDC-2.1)                                          | 1         | 1.82%   |
| ASUS Realtek Bluetooth 4.0 + High Speed Chip                         | 1         | 1.82%   |
| Alps Electric UGTZ4 Bluetooth                                        | 1         | 1.82%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)                      | 1         | 1.82%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Intel                | 69        | 47.59%  |
| AMD                  | 34        | 23.45%  |
| Nvidia               | 29        | 20%     |
| Logitech             | 3         | 2.07%   |
| SteelSeries ApS      | 2         | 1.38%   |
| VIA Technologies     | 1         | 0.69%   |
| Nam Tai E&E Products | 1         | 0.69%   |
| JMTek                | 1         | 0.69%   |
| Focusrite-Novation   | 1         | 0.69%   |
| Creative Technology  | 1         | 0.69%   |
| Creative Labs        | 1         | 0.69%   |
| Corsair              | 1         | 0.69%   |
| C-Media Electronics  | 1         | 0.69%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                       | 12        | 6.74%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller            | 11        | 6.18%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                   | 10        | 5.62%   |
| Intel Haswell-ULT HD Audio Controller                                                 | 9         | 5.06%   |
| Intel 8 Series HD Audio Controller                                                    | 9         | 5.06%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                   | 8         | 4.49%   |
| AMD Starship/Matisse HD Audio Controller                                              | 7         | 3.93%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                   | 7         | 3.93%   |
| Nvidia GK107 HDMI Audio Controller                                                    | 5         | 2.81%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                   | 5         | 2.81%   |
| AMD FCH Azalia Controller                                                             | 5         | 2.81%   |
| Nvidia GP107GL High Definition Audio Controller                                       | 4         | 2.25%   |
| Nvidia GP104 High Definition Audio Controller                                         | 4         | 2.25%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                        | 4         | 2.25%   |
| AMD Kabini HDMI/DP Audio                                                              | 4         | 2.25%   |
| Nvidia MCP79 High Definition Audio                                                    | 3         | 1.69%   |
| Nvidia GM206 High Definition Audio Controller                                         | 3         | 1.69%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                         | 3         | 1.69%   |
| Intel Wildcat Point-LP High Definition Audio Controller                               | 3         | 1.69%   |
| Intel Cannon Lake PCH cAVS                                                            | 3         | 1.69%   |
| Intel Broadwell-U Audio Controller                                                    | 3         | 1.69%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                      | 3         | 1.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                       | 3         | 1.69%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                      | 3         | 1.69%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                            | 3         | 1.69%   |
| SteelSeries ApS SteelSeries Arctis 7 Arctis 7 Chat Arctis 7 Game SteelSeries Arctis 7 | 2         | 1.12%   |
| Nvidia GP108 High Definition Audio Controller                                         | 2         | 1.12%   |
| Intel Cannon Point-LP High Definition Audio Controller                                | 2         | 1.12%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                   | 2         | 1.12%   |
| Intel 200 Series PCH HD Audio                                                         | 2         | 1.12%   |
| AMD SBx00 Azalia (Intel HDA)                                                          | 2         | 1.12%   |
| AMD Renoir Radeon High Definition Audio Controller                                    | 2         | 1.12%   |
| AMD High Definition Audio Controller                                                  | 2         | 1.12%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                          | 2         | 1.12%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller           | 1         | 0.56%   |
| Nvidia TU116 High Definition Audio Controller                                         | 1         | 0.56%   |
| Nvidia TU106 High Definition Audio Controller                                         | 1         | 0.56%   |
| Nvidia TU104 HD Audio Controller                                                      | 1         | 0.56%   |
| Nvidia MCP73 High Definition Audio                                                    | 1         | 0.56%   |
| Nvidia GF108 High Definition Audio Controller                                         | 1         | 0.56%   |
| Nvidia GF100 High Definition Audio Controller                                         | 1         | 0.56%   |
| Nvidia GA104 High Definition Audio Controller                                         | 1         | 0.56%   |
| Nam Tai E&E Products Sony SingStar USBMIC                                             | 1         | 0.56%   |
| Logitech Logitech USB Microphone                                                      | 1         | 0.56%   |
| Logitech HD Webcam C510                                                               | 1         | 0.56%   |
| Logitech H600 [Wireless Headset]                                                      | 1         | 0.56%   |
| JMTek Sharkoon 7.1 Sound Extension                                                    | 1         | 0.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                      | 1         | 0.56%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                               | 1         | 0.56%   |
| Intel Comet Lake PCH-LP cAVS                                                          | 1         | 0.56%   |
| Intel CM238 HD Audio Controller                                                       | 1         | 0.56%   |
| Intel 9 Series Chipset Family HD Audio Controller                                     | 1         | 0.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                              | 1         | 0.56%   |
| Focusrite-Novation Scarlett Solo (3rd Gen.)                                           | 1         | 0.56%   |
| Creative Technology Sound Blaster Omni Surround 5.1                                   | 1         | 0.56%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                         | 1         | 0.56%   |
| Corsair Corsair VOID PRO Wireless Gaming Headset                                      | 1         | 0.56%   |
| C-Media Electronics USB Audio Class 1.0 and 2.0 Device                                | 1         | 0.56%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                      | 1         | 0.56%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]               | 1         | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 29        | 22.31%  |
| SK Hynix            | 22        | 16.92%  |
| Kingston            | 17        | 13.08%  |
| G.Skill             | 12        | 9.23%   |
| Unknown             | 11        | 8.46%   |
| Crucial             | 10        | 7.69%   |
| Corsair             | 8         | 6.15%   |
| Micron Technology   | 6         | 4.62%   |
| Elpida              | 3         | 2.31%   |
| A-DATA Technology   | 3         | 2.31%   |
| Nanya Technology    | 2         | 1.54%   |
| Team                | 1         | 0.77%   |
| Smart               | 1         | 0.77%   |
| S                   | 1         | 0.77%   |
| Ramaxel Technology  | 1         | 0.77%   |
| Neo Forza           | 1         | 0.77%   |
| GOODRAM             | 1         | 0.77%   |
| Apacer              | 1         | 0.77%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s        | 4         | 3.01%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s         | 4         | 3.01%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s        | 3         | 2.26%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s           | 3         | 2.26%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s         | 3         | 2.26%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s         | 2         | 1.5%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s         | 2         | 1.5%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s         | 2         | 1.5%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s         | 2         | 1.5%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s         | 2         | 1.5%    |
| Unknown SODIMM 4GB SODIMM 800MT/s                             | 1         | 0.75%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                   | 1         | 0.75%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                     | 1         | 0.75%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                       | 1         | 0.75%   |
| Unknown RAM Module 2GB SODIMM DDR3                            | 1         | 0.75%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                    | 1         | 0.75%   |
| Unknown RAM Module 2GB DIMM DDR3 1067MT/s                     | 1         | 0.75%   |
| Unknown RAM Module 2GB DIMM 800MT/s                           | 1         | 0.75%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                   | 1         | 0.75%   |
| Unknown RAM Module 1024MB SODIMM DDR                          | 1         | 0.75%   |
| Unknown RAM GD2.09293S.001 16GB SODIMM DDR4 2400MT/s          | 1         | 0.75%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s          | 1         | 0.75%   |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s         | 1         | 0.75%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1067MT/s                  | 1         | 0.75%   |
| SK Hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s          | 1         | 0.75%   |
| SK Hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 0.75%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 0.75%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 0.75%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s        | 1         | 0.75%   |
| SK Hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s          | 1         | 0.75%   |
| SK Hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1333MT/s          | 1         | 0.75%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 1         | 0.75%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 0.75%   |
| SK Hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 0.75%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s        | 1         | 0.75%   |
| SK Hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s          | 1         | 0.75%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 1         | 0.75%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 1         | 0.75%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                | 1         | 0.75%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s         | 1         | 0.75%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s         | 1         | 0.75%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s         | 1         | 0.75%   |
| Samsung RAM M471B1G73BH0-CK0 8GB SODIMM DDR3 1600MT/s         | 1         | 0.75%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s         | 1         | 0.75%   |
| Samsung RAM M471A1K43BB1-CTD 8192MB SODIMM DDR4 2667MT/s      | 1         | 0.75%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s         | 1         | 0.75%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2133MT/s         | 1         | 0.75%   |
| Samsung RAM M393B5170FH0 4GB DIMM DDR3 1600MT/s               | 1         | 0.75%   |
| Samsung RAM M391B5273DH0-CH9 4GB DIMM DDR3 1333MT/s           | 1         | 0.75%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s           | 1         | 0.75%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 1600MT/s           | 1         | 0.75%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s           | 1         | 0.75%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 2667MT/s          | 1         | 0.75%   |
| Samsung RAM K4AAG165WA-BCTD 8GB SODIMM DDR4 2667MT/s          | 1         | 0.75%   |
| S RAM Module 4GB DIMM DDR3 1600MT/s                           | 1         | 0.75%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s       | 1         | 0.75%   |
| Neo Forza RAM NMSO480E82-2666E 8GB SODIMM DDR4 2667MT/s       | 1         | 0.75%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s          | 1         | 0.75%   |
| Nanya RAM NT2GT72U8PD0BY-3C 2GB DIMM DDR2 667MT/s             | 1         | 0.75%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 0.75%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 53        | 49.53%  |
| DDR4    | 46        | 42.99%  |
| DDR2    | 3         | 2.8%    |
| Unknown | 3         | 2.8%    |
| LPDDR3  | 1         | 0.93%   |
| DDR     | 1         | 0.93%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 65        | 60.75%  |
| DIMM         | 41        | 38.32%  |
| Row Of Chips | 1         | 0.93%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 49        | 42.61%  |
| 4096  | 42        | 36.52%  |
| 16384 | 12        | 10.43%  |
| 2048  | 10        | 8.7%    |
| 32768 | 1         | 0.87%   |
| 1024  | 1         | 0.87%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 37        | 31.9%   |
| 2400    | 18        | 15.52%  |
| 2667    | 14        | 12.07%  |
| 1333    | 11        | 9.48%   |
| 3200    | 9         | 7.76%   |
| 2133    | 7         | 6.03%   |
| 1334    | 4         | 3.45%   |
| 1067    | 4         | 3.45%   |
| 800     | 4         | 3.45%   |
| Unknown | 2         | 1.72%   |
| 3600    | 1         | 0.86%   |
| 3066    | 1         | 0.86%   |
| 2666    | 1         | 0.86%   |
| 1867    | 1         | 0.86%   |
| 1400    | 1         | 0.86%   |
| 667     | 1         | 0.86%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart_bsd/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart_bsd/printer_model.svg)


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

![Camera Vendor](./All/images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 15        | 28.85%  |
| Acer                                   | 7         | 13.46%  |
| Suyin                                  | 4         | 7.69%   |
| Sunplus Innovation Technology          | 4         | 7.69%   |
| Realtek Semiconductor                  | 4         | 7.69%   |
| Microdia                               | 4         | 7.69%   |
| Quanta                                 | 2         | 3.85%   |
| Lite-On Technology                     | 2         | 3.85%   |
| Alcor Micro                            | 2         | 3.85%   |
| Xiongmai                               | 1         | 1.92%   |
| Trust                                  | 1         | 1.92%   |
| Silicon Motion                         | 1         | 1.92%   |
| Logitech                               | 1         | 1.92%   |
| Lenovo                                 | 1         | 1.92%   |
| Importek                               | 1         | 1.92%   |
| IMC Networks                           | 1         | 1.92%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.92%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Acer Integrated Camera                                         | 6         | 11.32%  |
| Chicony Integrated Camera (1280x720@30)                        | 3         | 5.66%   |
| Chicony Integrated Camera                                      | 3         | 5.66%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 2         | 3.77%   |
| Sunplus Laptop_Integrated_Webcam_FHD                           | 2         | 3.77%   |
| Microdia Integrated_Webcam_HD                                  | 2         | 3.77%   |
| Microdia Integrated Webcam                                     | 2         | 3.77%   |
| Chicony HD WebCam                                              | 2         | 3.77%   |
| Chicony Chicony USB2.0 Camera                                  | 2         | 3.77%   |
| Xiongmai web camera                                            | 1         | 1.89%   |
| Trust Trust USB Camera                                         | 1         | 1.89%   |
| Suyin Integrated_Webcam_HD                                     | 1         | 1.89%   |
| Suyin HD WebCam                                                | 1         | 1.89%   |
| Sunplus MTD camera                                             | 1         | 1.89%   |
| Sunplus Integrated_Webcam_HD                                   | 1         | 1.89%   |
| Silicon Motion Realtek USB2.0 PC Camera                        | 1         | 1.89%   |
| Realtek Realtek USB2.0 PC Camera                               | 1         | 1.89%   |
| Realtek Lenovo EasyCamera                                      | 1         | 1.89%   |
| Realtek Integrated_Webcam_HD                                   | 1         | 1.89%   |
| Realtek Front Camera                                           | 1         | 1.89%   |
| Quanta VGA WebCam                                              | 1         | 1.89%   |
| Quanta HP TrueVision HD Camera                                 | 1         | 1.89%   |
| Logitech Webcam C310                                           | 1         | 1.89%   |
| Lite-On Integrated Camera                                      | 1         | 1.89%   |
| Lite-On HP TrueVision HD Camera                                | 1         | 1.89%   |
| Lenovo Integrated Webcam [R5U877]                              | 1         | 1.89%   |
| Importek TOSHIBA Web Camera - HD                               | 1         | 1.89%   |
| IMC Networks UVC VGA Webcam                                    | 1         | 1.89%   |
| Chicony USB2.0 HD UVC WebCam                                   | 1         | 1.89%   |
| Chicony Thinkpad T430 camera                                   | 1         | 1.89%   |
| Chicony Realtek DMFT - IR                                      | 1         | 1.89%   |
| Chicony Lenovo Integrated Camera (0.3MP)                       | 1         | 1.89%   |
| Chicony Lenovo EasyCamera                                      | 1         | 1.89%   |
| Chicony HP High Definition 1MP Webcam                          | 1         | 1.89%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 1.89%   |
| Alcor Micro USB 2.0 Camera                                     | 1         | 1.89%   |
| Alcor Micro Acer Integrated Webcam                             | 1         | 1.89%   |
| Acer ThinkPad Integrated Camera                                | 1         | 1.89%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


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

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


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

![Unsupported Devices](./All/images/pie_chart_bsd/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 33        | 30.28%  |
| 2     | 26        | 23.85%  |
| 3     | 19        | 17.43%  |
| 0     | 18        | 16.51%  |
| 4     | 10        | 9.17%   |
| 5     | 3         | 2.75%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 62        | 32.98%  |
| Bluetooth                | 46        | 24.47%  |
| Card reader              | 25        | 13.3%   |
| Net/wireless             | 22        | 11.7%   |
| Fingerprint reader       | 12        | 6.38%   |
| Firewire controller      | 10        | 5.32%   |
| Network                  | 5         | 2.66%   |
| Storage                  | 4         | 2.13%   |
| Sound                    | 1         | 0.53%   |
| Modem                    | 1         | 0.53%   |

