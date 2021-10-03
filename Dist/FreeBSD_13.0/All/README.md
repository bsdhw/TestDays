FreeBSD 13.0 - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for FreeBSD 13.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/FreeBSD_13.0/Desktop/README.md) and [notebooks](/Dist/FreeBSD_13.0/Notebook/README.md).

Full-feature report is available here: https://bsd-hardware.info/?view=trends&rel=freebsd-13.0

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
| Supermicro    | X7SPA-HF                    | Desktop     | [d65e453ea7](https://bsd-hardware.info/?probe=d65e453ea7) | Oct 03, 2021 |
| MSI           | H81M-P33                    | Desktop     | [fd498893fb](https://bsd-hardware.info/?probe=fd498893fb) | Oct 03, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [0bfcd11255](https://bsd-hardware.info/?probe=0bfcd11255) | Oct 03, 2021 |
| ASUSTek       | H81M-E                      | Desktop     | [0cc0d2dcb1](https://bsd-hardware.info/?probe=0cc0d2dcb1) | Oct 01, 2021 |
| ASUSTek       | H81M-E                      | Desktop     | [76866f2db7](https://bsd-hardware.info/?probe=76866f2db7) | Oct 01, 2021 |
| ASUSTek       | H81M-E                      | Desktop     | [319470ebbd](https://bsd-hardware.info/?probe=319470ebbd) | Oct 01, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [1c4cf7c21c](https://bsd-hardware.info/?probe=1c4cf7c21c) | Sep 30, 2021 |
| Apple         | MacBookPro13,2              | Notebook    | [0bf74dea55](https://bsd-hardware.info/?probe=0bf74dea55) | Sep 30, 2021 |
| Supermicro    | X7SPA-HF                    | Desktop     | [18cd64ae96](https://bsd-hardware.info/?probe=18cd64ae96) | Sep 26, 2021 |
| MSI           | H81M-P33                    | Desktop     | [8a8d67b8b1](https://bsd-hardware.info/?probe=8a8d67b8b1) | Sep 26, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [fb056a1840](https://bsd-hardware.info/?probe=fb056a1840) | Sep 26, 2021 |
| ASUSTek       | H81M-E                      | Desktop     | [137654a2f8](https://bsd-hardware.info/?probe=137654a2f8) | Sep 24, 2021 |
| ASUSTek       | H81M-E                      | Desktop     | [dec23f7ff8](https://bsd-hardware.info/?probe=dec23f7ff8) | Sep 23, 2021 |
| Dell          | Latitude E7450              | Notebook    | [4f1e40ad63](https://bsd-hardware.info/?probe=4f1e40ad63) | Sep 21, 2021 |
| Supermicro    | X7SPA-HF                    | Desktop     | [6b68e14399](https://bsd-hardware.info/?probe=6b68e14399) | Sep 19, 2021 |
| MSI           | H81M-P33                    | Desktop     | [60ec488627](https://bsd-hardware.info/?probe=60ec488627) | Sep 19, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [c2d07d370e](https://bsd-hardware.info/?probe=c2d07d370e) | Sep 19, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [22c1aefeab](https://bsd-hardware.info/?probe=22c1aefeab) | Sep 19, 2021 |
| Lenovo        | G40-70 20369                | Notebook    | [ef8eafa662](https://bsd-hardware.info/?probe=ef8eafa662) | Sep 18, 2021 |
| Unknown       | Unknown                     | Desktop     | [392cf6ec24](https://bsd-hardware.info/?probe=392cf6ec24) | Sep 17, 2021 |
| Unknown       | Unknown                     | Desktop     | [198c4264f9](https://bsd-hardware.info/?probe=198c4264f9) | Sep 16, 2021 |
| Unknown       | Unknown                     | Desktop     | [d05c3ba858](https://bsd-hardware.info/?probe=d05c3ba858) | Sep 15, 2021 |
| Unknown       | Unknown                     | Desktop     | [062602e8db](https://bsd-hardware.info/?probe=062602e8db) | Sep 15, 2021 |
| Intel         | NUC5CPYB H61145-413         | Mini pc     | [072047d3e5](https://bsd-hardware.info/?probe=072047d3e5) | Sep 12, 2021 |
| Supermicro    | X7SPA-HF                    | Desktop     | [4d1aa99478](https://bsd-hardware.info/?probe=4d1aa99478) | Sep 12, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [8055702eac](https://bsd-hardware.info/?probe=8055702eac) | Sep 12, 2021 |
| MSI           | H81M-P33                    | Desktop     | [a8feb1807d](https://bsd-hardware.info/?probe=a8feb1807d) | Sep 12, 2021 |
| ASUSTek       | TP300LD                     | Notebook    | [e9d8f7de51](https://bsd-hardware.info/?probe=e9d8f7de51) | Sep 09, 2021 |
| ASUSTek       | VX7SX                       | Notebook    | [6ca36a455d](https://bsd-hardware.info/?probe=6ca36a455d) | Sep 09, 2021 |
| Unknown       | Unknown                     | Desktop     | [5933c93a5b](https://bsd-hardware.info/?probe=5933c93a5b) | Sep 09, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [30424125f5](https://bsd-hardware.info/?probe=30424125f5) | Sep 08, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [76da651584](https://bsd-hardware.info/?probe=76da651584) | Sep 08, 2021 |
| Supermicro    | X7SPA-HF                    | Desktop     | [b1677cb485](https://bsd-hardware.info/?probe=b1677cb485) | Sep 05, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [33392e3299](https://bsd-hardware.info/?probe=33392e3299) | Sep 05, 2021 |
| MSI           | H81M-P33                    | Desktop     | [ad52aa4ea5](https://bsd-hardware.info/?probe=ad52aa4ea5) | Sep 05, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [5147f5734d](https://bsd-hardware.info/?probe=5147f5734d) | Sep 04, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [2e8b641cc4](https://bsd-hardware.info/?probe=2e8b641cc4) | Sep 04, 2021 |
| Apple         | MacBookPro5,1               | Notebook    | [2cba98f24b](https://bsd-hardware.info/?probe=2cba98f24b) | Sep 04, 2021 |
| Dell          | Latitude E6530              | Notebook    | [8dbff835d2](https://bsd-hardware.info/?probe=8dbff835d2) | Sep 02, 2021 |
| Apple         | Mac-F2268CC8                | All in one  | [28bf815655](https://bsd-hardware.info/?probe=28bf815655) | Aug 30, 2021 |
| Supermicro    | X7SPA-HF                    | Desktop     | [1d408ec8df](https://bsd-hardware.info/?probe=1d408ec8df) | Aug 29, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [37fe7a021f](https://bsd-hardware.info/?probe=37fe7a021f) | Aug 29, 2021 |
| MSI           | H81M-P33                    | Desktop     | [90f439a559](https://bsd-hardware.info/?probe=90f439a559) | Aug 29, 2021 |
| Medion        | MS-7616                     | Desktop     | [98f0e21e6c](https://bsd-hardware.info/?probe=98f0e21e6c) | Aug 26, 2021 |
| Medion        | MS-7616                     | Desktop     | [663b50102d](https://bsd-hardware.info/?probe=663b50102d) | Aug 26, 2021 |
| HP            | 18E6                        | All in one  | [20d70ad9ba](https://bsd-hardware.info/?probe=20d70ad9ba) | Aug 26, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [70dc185964](https://bsd-hardware.info/?probe=70dc185964) | Aug 25, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [0b02720fcc](https://bsd-hardware.info/?probe=0b02720fcc) | Aug 23, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [3e088c942b](https://bsd-hardware.info/?probe=3e088c942b) | Aug 22, 2021 |
| Supermicro    | X7SPA-HF                    | Desktop     | [0db2178b94](https://bsd-hardware.info/?probe=0db2178b94) | Aug 22, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [eee5ea8171](https://bsd-hardware.info/?probe=eee5ea8171) | Aug 22, 2021 |
| MSI           | H81M-P33                    | Desktop     | [ceb4fcb174](https://bsd-hardware.info/?probe=ceb4fcb174) | Aug 22, 2021 |
| Supermicro    | X7SPA-HF                    | Desktop     | [9fa08ee32f](https://bsd-hardware.info/?probe=9fa08ee32f) | Aug 15, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [3f15cbe8cc](https://bsd-hardware.info/?probe=3f15cbe8cc) | Aug 15, 2021 |
| MSI           | H81M-P33                    | Desktop     | [8a9a281ee1](https://bsd-hardware.info/?probe=8a9a281ee1) | Aug 15, 2021 |
| Cisco Syst... | UCSC-C240-M3L 74-10443-0... | Desktop     | [adf41eedab](https://bsd-hardware.info/?probe=adf41eedab) | Aug 13, 2021 |
| Cisco Syst... | UCSC-C240-M3L 74-10443-0... | Desktop     | [4dd5f1c0c6](https://bsd-hardware.info/?probe=4dd5f1c0c6) | Aug 12, 2021 |
| Cisco Syst... | UCSC-C240-M3L 74-10443-0... | Desktop     | [1c835c20cb](https://bsd-hardware.info/?probe=1c835c20cb) | Aug 09, 2021 |
| Supermicro    | X7SPA-HF                    | Desktop     | [b972923c8d](https://bsd-hardware.info/?probe=b972923c8d) | Aug 08, 2021 |
| MSI           | H81M-P33                    | Desktop     | [5ae84c8d07](https://bsd-hardware.info/?probe=5ae84c8d07) | Aug 08, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [e51135c93a](https://bsd-hardware.info/?probe=e51135c93a) | Aug 08, 2021 |
| Samsung       | 300E5M/300E5L               | Notebook    | [ae874102c3](https://bsd-hardware.info/?probe=ae874102c3) | Aug 04, 2021 |
| Lenovo        | G505 20240                  | Notebook    | [16e6ec4054](https://bsd-hardware.info/?probe=16e6ec4054) | Aug 02, 2021 |
| Supermicro    | X7SPA-HF                    | Desktop     | [048bfd8f45](https://bsd-hardware.info/?probe=048bfd8f45) | Aug 01, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [faeca32de9](https://bsd-hardware.info/?probe=faeca32de9) | Aug 01, 2021 |
| MSI           | H81M-P33                    | Desktop     | [062450ca66](https://bsd-hardware.info/?probe=062450ca66) | Aug 01, 2021 |
| Lenovo        | ThinkPad T410 2516DCU       | Notebook    | [c3aa245b5d](https://bsd-hardware.info/?probe=c3aa245b5d) | Jul 27, 2021 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [38910aa754](https://bsd-hardware.info/?probe=38910aa754) | Jul 25, 2021 |
| Supermicro    | X7SPA-HF                    | Desktop     | [692320f986](https://bsd-hardware.info/?probe=692320f986) | Jul 25, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [ca4e2c4a94](https://bsd-hardware.info/?probe=ca4e2c4a94) | Jul 25, 2021 |
| Dell          | Inspiron N4030              | Notebook    | [d6feef8717](https://bsd-hardware.info/?probe=d6feef8717) | Jul 23, 2021 |
| Dell          | Inspiron N4030              | Notebook    | [9a3c3705d0](https://bsd-hardware.info/?probe=9a3c3705d0) | Jul 23, 2021 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [586c14dd63](https://bsd-hardware.info/?probe=586c14dd63) | Jul 23, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [389bf7ae4b](https://bsd-hardware.info/?probe=389bf7ae4b) | Jul 23, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [fc6688138c](https://bsd-hardware.info/?probe=fc6688138c) | Jul 23, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [89a9db74f9](https://bsd-hardware.info/?probe=89a9db74f9) | Jul 21, 2021 |
| Lenovo        | ThinkPad T410 2516DCU       | Notebook    | [04b19bd02a](https://bsd-hardware.info/?probe=04b19bd02a) | Jul 21, 2021 |
| Dell          | Inspiron 5758               | Notebook    | [7542ae751d](https://bsd-hardware.info/?probe=7542ae751d) | Jul 20, 2021 |
| Cisco Syst... | UCSC-C240-M4L 74-12420-0... | Server      | [0d51f6e407](https://bsd-hardware.info/?probe=0d51f6e407) | Jul 19, 2021 |
| Supermicro    | X7SPA-HF                    | Desktop     | [d041bb0182](https://bsd-hardware.info/?probe=d041bb0182) | Jul 18, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [9cdc6262f6](https://bsd-hardware.info/?probe=9cdc6262f6) | Jul 18, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [8f8cc52f23](https://bsd-hardware.info/?probe=8f8cc52f23) | Jul 17, 2021 |
| Dell          | 0HD5W2 A00                  | Desktop     | [8315a3b948](https://bsd-hardware.info/?probe=8315a3b948) | Jul 17, 2021 |
| Dell          | 0HD5W2 A00                  | Desktop     | [8780a9eb26](https://bsd-hardware.info/?probe=8780a9eb26) | Jul 17, 2021 |
| Cisco Syst... | UCSC-C240-M3L 74-10443-0... | Desktop     | [fb1c3af983](https://bsd-hardware.info/?probe=fb1c3af983) | Jul 16, 2021 |
| Cisco Syst... | UCSC-C240-M3L 74-10443-0... | Desktop     | [9d729e0508](https://bsd-hardware.info/?probe=9d729e0508) | Jul 13, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [85e94a1288](https://bsd-hardware.info/?probe=85e94a1288) | Jul 13, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [5038f75992](https://bsd-hardware.info/?probe=5038f75992) | Jul 13, 2021 |
| Supermicro    | X7SPA-HF                    | Desktop     | [d859525592](https://bsd-hardware.info/?probe=d859525592) | Jul 11, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [708d1e2608](https://bsd-hardware.info/?probe=708d1e2608) | Jul 11, 2021 |
| Lenovo        | ThinkPad X230 2325A95       | Notebook    | [94d66a0677](https://bsd-hardware.info/?probe=94d66a0677) | Jul 10, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [08641f83e8](https://bsd-hardware.info/?probe=08641f83e8) | Jul 07, 2021 |
| Acer          | Aspire A515-54G             | Notebook    | [08cafd05b1](https://bsd-hardware.info/?probe=08cafd05b1) | Jul 06, 2021 |
| Pegatron      | IPPCR-SS                    | Desktop     | [86b2e85d24](https://bsd-hardware.info/?probe=86b2e85d24) | Jul 05, 2021 |
| Dell          | 0HD5W2 A00                  | Desktop     | [9fe5dd4b75](https://bsd-hardware.info/?probe=9fe5dd4b75) | Jul 04, 2021 |
| Dell          | 0HD5W2 A00                  | Desktop     | [e85afd7989](https://bsd-hardware.info/?probe=e85afd7989) | Jul 04, 2021 |
| Supermicro    | X7SPA-HF                    | Desktop     | [e24689b692](https://bsd-hardware.info/?probe=e24689b692) | Jul 04, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [c62837354b](https://bsd-hardware.info/?probe=c62837354b) | Jul 04, 2021 |
| Lenovo        | Rescuer-15ISK 80RQ          | Notebook    | [46d0d10dd8](https://bsd-hardware.info/?probe=46d0d10dd8) | Jul 03, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [7360fb3199](https://bsd-hardware.info/?probe=7360fb3199) | Jul 03, 2021 |
| Cisco Syst... | UCSC-C240-M4L 74-12420-0... | Server      | [2c38eae6bc](https://bsd-hardware.info/?probe=2c38eae6bc) | Jul 02, 2021 |
| Cisco Syst... | UCSC-C240-M4L 74-12420-0... | Server      | [c339174f12](https://bsd-hardware.info/?probe=c339174f12) | Jul 02, 2021 |
| Samsung       | NC10                        | Notebook    | [d33644912a](https://bsd-hardware.info/?probe=d33644912a) | Jun 28, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [c1a27ca913](https://bsd-hardware.info/?probe=c1a27ca913) | Jun 27, 2021 |
| Supermicro    | X7SPA-HF                    | Desktop     | [1e5ccb0c3c](https://bsd-hardware.info/?probe=1e5ccb0c3c) | Jun 27, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [96d46d6f38](https://bsd-hardware.info/?probe=96d46d6f38) | Jun 27, 2021 |
| Dell          | Vostro 5481                 | Notebook    | [bb318fbc50](https://bsd-hardware.info/?probe=bb318fbc50) | Jun 26, 2021 |
| Toshiba       | PORTEGE X20W-D              | Convertible | [1e5dc453f6](https://bsd-hardware.info/?probe=1e5dc453f6) | Jun 25, 2021 |
| Supermicro    | X7SPA-HF                    | Desktop     | [ac70749f81](https://bsd-hardware.info/?probe=ac70749f81) | Jun 20, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [d6c3fe4058](https://bsd-hardware.info/?probe=d6c3fe4058) | Jun 20, 2021 |
| MSI           | H81M-P33                    | Desktop     | [2a26234f71](https://bsd-hardware.info/?probe=2a26234f71) | Jun 20, 2021 |
| Lenovo        | ThinkPad T420 4236NHG       | Notebook    | [ea00bc1f1f](https://bsd-hardware.info/?probe=ea00bc1f1f) | Jun 20, 2021 |
| HP            | ENVY x2 Detachable PC 13    | Notebook    | [8c78180ff9](https://bsd-hardware.info/?probe=8c78180ff9) | Jun 20, 2021 |
| HP            | ENVY x2 Detachable PC 13    | Notebook    | [2e7a8b5be3](https://bsd-hardware.info/?probe=2e7a8b5be3) | Jun 20, 2021 |
| Wistron       | ProLiant ML110 G6           | Desktop     | [8f336c0fa3](https://bsd-hardware.info/?probe=8f336c0fa3) | Jun 19, 2021 |
| Wistron       | ProLiant ML110 G6           | Desktop     | [dc619f203f](https://bsd-hardware.info/?probe=dc619f203f) | Jun 19, 2021 |
| Dell          | Inspiron 15-7579            | Notebook    | [4b8b5f7918](https://bsd-hardware.info/?probe=4b8b5f7918) | Jun 19, 2021 |
| LG Electro... | E500-GP01A9                 | Notebook    | [80052d6cdc](https://bsd-hardware.info/?probe=80052d6cdc) | Jun 15, 2021 |
| Dell          | 00NH4P A09                  | Server      | [1098796c5f](https://bsd-hardware.info/?probe=1098796c5f) | Jun 14, 2021 |
| Raspberry ... | rpi                         | Desktop     | [692d412c0c](https://bsd-hardware.info/?probe=692d412c0c) | Jun 14, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [c066194e27](https://bsd-hardware.info/?probe=c066194e27) | Jun 13, 2021 |
| ASUSTek       | P5K SE/EPU                  | Desktop     | [60d9b24b69](https://bsd-hardware.info/?probe=60d9b24b69) | Jun 13, 2021 |
| Supermicro    | X7SPA-HF                    | Desktop     | [197b4515ad](https://bsd-hardware.info/?probe=197b4515ad) | Jun 13, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [4af3098758](https://bsd-hardware.info/?probe=4af3098758) | Jun 13, 2021 |
| MSI           | H81M-P33                    | Desktop     | [48d5da63d6](https://bsd-hardware.info/?probe=48d5da63d6) | Jun 13, 2021 |
| Unknown       | Unknown                     | Soc         | [ce45b72607](https://bsd-hardware.info/?probe=ce45b72607) | Jun 11, 2021 |
| Dell          | Latitude E4300              | Notebook    | [1150e00893](https://bsd-hardware.info/?probe=1150e00893) | Jun 10, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [9a7adb8860](https://bsd-hardware.info/?probe=9a7adb8860) | Jun 06, 2021 |
| Supermicro    | X7SPA-HF                    | Desktop     | [84abffd607](https://bsd-hardware.info/?probe=84abffd607) | Jun 06, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [65893eaa25](https://bsd-hardware.info/?probe=65893eaa25) | Jun 06, 2021 |
| MSI           | H81M-P33                    | Desktop     | [54636fa78f](https://bsd-hardware.info/?probe=54636fa78f) | Jun 06, 2021 |
| Lenovo        | ThinkPad X220 4291ON5       | Notebook    | [66743a51cc](https://bsd-hardware.info/?probe=66743a51cc) | Jun 04, 2021 |
| Lenovo        | ThinkPad T420 4237A12       | Notebook    | [dc29d714d9](https://bsd-hardware.info/?probe=dc29d714d9) | Jun 02, 2021 |
| Sony          | SVF1421DSGW                 | Notebook    | [64f3f02018](https://bsd-hardware.info/?probe=64f3f02018) | Jun 01, 2021 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [0b3c9a332d](https://bsd-hardware.info/?probe=0b3c9a332d) | May 31, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [a87473149b](https://bsd-hardware.info/?probe=a87473149b) | May 31, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [82d464f2a8](https://bsd-hardware.info/?probe=82d464f2a8) | May 31, 2021 |
| System76      | Gazelle                     | Notebook    | [f9c37f2c8d](https://bsd-hardware.info/?probe=f9c37f2c8d) | May 30, 2021 |
| HP            | Pavilion Laptop 15-cc0xx    | Notebook    | [9dd5a9eeef](https://bsd-hardware.info/?probe=9dd5a9eeef) | May 30, 2021 |
| Supermicro    | X7SPA-HF                    | Desktop     | [f8036fdef4](https://bsd-hardware.info/?probe=f8036fdef4) | May 30, 2021 |
| MSI           | H81M-P33                    | Desktop     | [9ff6febdba](https://bsd-hardware.info/?probe=9ff6febdba) | May 30, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [aabcf92dd5](https://bsd-hardware.info/?probe=aabcf92dd5) | May 30, 2021 |
| Dell          | Vostro 5568                 | Notebook    | [84a1925fc9](https://bsd-hardware.info/?probe=84a1925fc9) | May 29, 2021 |
| Gigabyte      | B85-HD3                     | Desktop     | [331da3091c](https://bsd-hardware.info/?probe=331da3091c) | May 28, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [337a8b5a3d](https://bsd-hardware.info/?probe=337a8b5a3d) | May 28, 2021 |
| MSI           | X399 GAMING PRO CARBON A... | Desktop     | [20052b0d55](https://bsd-hardware.info/?probe=20052b0d55) | May 27, 2021 |
| ASUSTek       | P7H55-M/USB3                | Desktop     | [87068a97be](https://bsd-hardware.info/?probe=87068a97be) | May 26, 2021 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [2247c7130f](https://bsd-hardware.info/?probe=2247c7130f) | May 26, 2021 |
| HP            | 1790                        | Desktop     | [59e472fb01](https://bsd-hardware.info/?probe=59e472fb01) | May 24, 2021 |
| Lenovo        | ThinkPad X220 4291PU5       | Notebook    | [c6d626c350](https://bsd-hardware.info/?probe=c6d626c350) | May 24, 2021 |
| HP            | 1790                        | Desktop     | [3a4e33eb4d](https://bsd-hardware.info/?probe=3a4e33eb4d) | May 24, 2021 |
| Acer          | Aspire E5-571P              | Notebook    | [7c8c842fa7](https://bsd-hardware.info/?probe=7c8c842fa7) | May 24, 2021 |
| ASUSTek       | 1015PX                      | Notebook    | [c6e717c1e9](https://bsd-hardware.info/?probe=c6e717c1e9) | May 24, 2021 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | Desktop     | [f035aab141](https://bsd-hardware.info/?probe=f035aab141) | May 24, 2021 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [4d15a3ffe3](https://bsd-hardware.info/?probe=4d15a3ffe3) | May 23, 2021 |
| Dell          | Latitude D620               | Notebook    | [1bd280a155](https://bsd-hardware.info/?probe=1bd280a155) | May 23, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [951c3e534c](https://bsd-hardware.info/?probe=951c3e534c) | May 23, 2021 |
| Supermicro    | X7SPA-HF                    | Desktop     | [d76f0d88b2](https://bsd-hardware.info/?probe=d76f0d88b2) | May 23, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [9589f37f30](https://bsd-hardware.info/?probe=9589f37f30) | May 23, 2021 |
| MSI           | H81M-P33                    | Desktop     | [67ce92aee6](https://bsd-hardware.info/?probe=67ce92aee6) | May 23, 2021 |
| MSI           | H61I-E35/W8                 | Desktop     | [d07ad10827](https://bsd-hardware.info/?probe=d07ad10827) | May 22, 2021 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [80cf566074](https://bsd-hardware.info/?probe=80cf566074) | May 21, 2021 |
| Notebook      | N7x0WU                      | Notebook    | [70760365d0](https://bsd-hardware.info/?probe=70760365d0) | May 20, 2021 |
| Dell          | Latitude E6410              | Notebook    | [c0115917d2](https://bsd-hardware.info/?probe=c0115917d2) | May 19, 2021 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [89ca4554ca](https://bsd-hardware.info/?probe=89ca4554ca) | May 18, 2021 |
| ASRock        | J3455-ITX                   | Desktop     | [c9218ee21d](https://bsd-hardware.info/?probe=c9218ee21d) | May 17, 2021 |
| Supermicro    | X7SPA-HF                    | Desktop     | [3d35e6b890](https://bsd-hardware.info/?probe=3d35e6b890) | May 16, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [9e4c7bf061](https://bsd-hardware.info/?probe=9e4c7bf061) | May 16, 2021 |
| MSI           | H81M-P33                    | Desktop     | [3f3f826118](https://bsd-hardware.info/?probe=3f3f826118) | May 16, 2021 |
| MSI           | GL65 Leopard 10SFSK         | Notebook    | [a40e426983](https://bsd-hardware.info/?probe=a40e426983) | May 15, 2021 |
| Dell          | Latitude E5550              | Notebook    | [dca8ba9d37](https://bsd-hardware.info/?probe=dca8ba9d37) | May 13, 2021 |
| ASUSTek       | G750JM                      | Notebook    | [37be4ea27a](https://bsd-hardware.info/?probe=37be4ea27a) | May 13, 2021 |
| Lenovo        | 1037 NO DPK                 | Server      | [ffaa30bc08](https://bsd-hardware.info/?probe=ffaa30bc08) | May 12, 2021 |
| Apple         | MacBookPro6,2               | Notebook    | [0ab44e95df](https://bsd-hardware.info/?probe=0ab44e95df) | May 12, 2021 |
| EVGA          | X299 FTW K                  | Desktop     | [c4862c598a](https://bsd-hardware.info/?probe=c4862c598a) | May 11, 2021 |
| HP            | ProLiant BL460c G6          | Server      | [2b539fcf18](https://bsd-hardware.info/?probe=2b539fcf18) | May 11, 2021 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | Desktop     | [a9a897258e](https://bsd-hardware.info/?probe=a9a897258e) | May 11, 2021 |
| Notebook      | NL5xRU                      | Notebook    | [792fb07dd9](https://bsd-hardware.info/?probe=792fb07dd9) | May 10, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [8d78068ca7](https://bsd-hardware.info/?probe=8d78068ca7) | May 09, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [add2c1bcba](https://bsd-hardware.info/?probe=add2c1bcba) | May 09, 2021 |
| Supermicro    | X7SPA-HF                    | Desktop     | [dfb015cf64](https://bsd-hardware.info/?probe=dfb015cf64) | May 09, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [cbfba11dfe](https://bsd-hardware.info/?probe=cbfba11dfe) | May 09, 2021 |
| MSI           | H81M-P33                    | Desktop     | [6a9b635e7c](https://bsd-hardware.info/?probe=6a9b635e7c) | May 09, 2021 |
| Shuttle       | FH87                        | Desktop     | [bf5457ff02](https://bsd-hardware.info/?probe=bf5457ff02) | May 09, 2021 |
| Acer          | Predator PH517-61           | Notebook    | [9e03a76684](https://bsd-hardware.info/?probe=9e03a76684) | May 08, 2021 |
| Dell          | Latitude 5500               | Notebook    | [2538b038ed](https://bsd-hardware.info/?probe=2538b038ed) | May 08, 2021 |
| Toshiba       | TECRA M11                   | Notebook    | [6357d0d51f](https://bsd-hardware.info/?probe=6357d0d51f) | May 08, 2021 |
| HP            | Laptop 17-by0xxx            | Notebook    | [10af242f8b](https://bsd-hardware.info/?probe=10af242f8b) | May 07, 2021 |
| HP            | Laptop 17-by0xxx            | Notebook    | [b0b4ca9f27](https://bsd-hardware.info/?probe=b0b4ca9f27) | May 07, 2021 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [87e5651fd1](https://bsd-hardware.info/?probe=87e5651fd1) | May 06, 2021 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | Notebook    | [d5adf152a7](https://bsd-hardware.info/?probe=d5adf152a7) | May 05, 2021 |
| Gigabyte      | X58A-UD5                    | Desktop     | [24502c7f7b](https://bsd-hardware.info/?probe=24502c7f7b) | May 04, 2021 |
| ASRock        | Z170M Extreme4              | Desktop     | [e2d2bb7f28](https://bsd-hardware.info/?probe=e2d2bb7f28) | May 04, 2021 |
| ASUSTek       | TUF GAMING X570-PRO         | Desktop     | [4d7013aeab](https://bsd-hardware.info/?probe=4d7013aeab) | May 04, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [cbbf4f86cd](https://bsd-hardware.info/?probe=cbbf4f86cd) | May 03, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [7fc73d2db3](https://bsd-hardware.info/?probe=7fc73d2db3) | May 03, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [87c4175f48](https://bsd-hardware.info/?probe=87c4175f48) | May 03, 2021 |
| Pegatron      | T12Ah                       | Notebook    | [ce8d45af17](https://bsd-hardware.info/?probe=ce8d45af17) | May 03, 2021 |
| Supermicro    | X7SPA-HF                    | Desktop     | [7b8ebcef12](https://bsd-hardware.info/?probe=7b8ebcef12) | May 02, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [7033f42e70](https://bsd-hardware.info/?probe=7033f42e70) | May 02, 2021 |
| MSI           | H81M-P33                    | Desktop     | [96111749b8](https://bsd-hardware.info/?probe=96111749b8) | May 02, 2021 |
| Lenovo        | ThinkPad T440p 20AW0049L... | Notebook    | [7660f9b6db](https://bsd-hardware.info/?probe=7660f9b6db) | May 02, 2021 |
| ASUSTek       | Z97-K                       | Desktop     | [d8ecc7077a](https://bsd-hardware.info/?probe=d8ecc7077a) | May 02, 2021 |
| GVC           | DR 738                      | Desktop     | [9ff0fb7df4](https://bsd-hardware.info/?probe=9ff0fb7df4) | May 01, 2021 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [2713d38658](https://bsd-hardware.info/?probe=2713d38658) | May 01, 2021 |
| Beckhoff A... | CB3056 G4                   | Desktop     | [120665d4d3](https://bsd-hardware.info/?probe=120665d4d3) | Apr 30, 2021 |
| HP            | Laptop 17-by0xxx            | Notebook    | [47221a4d1d](https://bsd-hardware.info/?probe=47221a4d1d) | Apr 30, 2021 |
| Dell          | 0FJ030                      | Desktop     | [91418a4965](https://bsd-hardware.info/?probe=91418a4965) | Apr 30, 2021 |
| Dell          | 0FJ030                      | Desktop     | [7bee24ee8a](https://bsd-hardware.info/?probe=7bee24ee8a) | Apr 30, 2021 |
| Intel         | NUC5i3RYB H41000-503        | Mini pc     | [1653ea52ce](https://bsd-hardware.info/?probe=1653ea52ce) | Apr 29, 2021 |
| HP            | Laptop 17-by0xxx            | Notebook    | [14cf64712f](https://bsd-hardware.info/?probe=14cf64712f) | Apr 29, 2021 |
| Lenovo        | ThinkPad X380 Yoga 20LH0... | Convertible | [6ec28a973a](https://bsd-hardware.info/?probe=6ec28a973a) | Apr 28, 2021 |
| Dell          | Latitude E5420              | Notebook    | [32f03aa888](https://bsd-hardware.info/?probe=32f03aa888) | Apr 27, 2021 |
| Dell          | Latitude E5420              | Notebook    | [4b4cd45ac7](https://bsd-hardware.info/?probe=4b4cd45ac7) | Apr 26, 2021 |
| Dell          | Latitude E5420              | Notebook    | [6457b99e73](https://bsd-hardware.info/?probe=6457b99e73) | Apr 26, 2021 |
| Dell          | Precision 5510              | Notebook    | [063d746a48](https://bsd-hardware.info/?probe=063d746a48) | Apr 25, 2021 |
| Dell          | Precision 5510              | Notebook    | [6bb3b7aa11](https://bsd-hardware.info/?probe=6bb3b7aa11) | Apr 25, 2021 |
| HP            | Compaq Presario CQ71        | Notebook    | [258ef16ace](https://bsd-hardware.info/?probe=258ef16ace) | Apr 25, 2021 |
| Supermicro    | X7SPA-HF                    | Desktop     | [39d9a85a18](https://bsd-hardware.info/?probe=39d9a85a18) | Apr 25, 2021 |
| MSI           | H81M-P33                    | Desktop     | [e0660a37f5](https://bsd-hardware.info/?probe=e0660a37f5) | Apr 25, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [1ee72db86e](https://bsd-hardware.info/?probe=1ee72db86e) | Apr 25, 2021 |
| ASUSTek       | SABERTOOTH Z97 MARK 2       | Desktop     | [8055ed41df](https://bsd-hardware.info/?probe=8055ed41df) | Apr 25, 2021 |
| Gigabyte      | F2A75M-HD2                  | Desktop     | [18a74377ac](https://bsd-hardware.info/?probe=18a74377ac) | Apr 25, 2021 |
| Dell          | Inspiron 3793               | Notebook    | [c784e7b290](https://bsd-hardware.info/?probe=c784e7b290) | Apr 25, 2021 |
| Fujitsu       | D3417-B2 S26361-D3417-B2    | Desktop     | [9a0602d408](https://bsd-hardware.info/?probe=9a0602d408) | Apr 25, 2021 |
| Dell          | Inspiron N5050              | Notebook    | [2939c4cb17](https://bsd-hardware.info/?probe=2939c4cb17) | Apr 24, 2021 |
| Lenovo        | ThinkPad E14 20RAS0F600     | Notebook    | [94d082c57c](https://bsd-hardware.info/?probe=94d082c57c) | Apr 24, 2021 |
| HP            | Laptop 17-by0xxx            | Notebook    | [4f4a6b1ab0](https://bsd-hardware.info/?probe=4f4a6b1ab0) | Apr 24, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [ab8235808d](https://bsd-hardware.info/?probe=ab8235808d) | Apr 23, 2021 |
| Toshiba       | Satellite L50-C             | Notebook    | [9cf9861053](https://bsd-hardware.info/?probe=9cf9861053) | Apr 23, 2021 |
| Pegatron      | T12Ah                       | Notebook    | [5de4060089](https://bsd-hardware.info/?probe=5de4060089) | Apr 23, 2021 |
| Dell          | Precision 5520              | Notebook    | [7d5f7b5033](https://bsd-hardware.info/?probe=7d5f7b5033) | Apr 23, 2021 |
| Toshiba       | Satellite L50-C             | Notebook    | [94b2e5d5ff](https://bsd-hardware.info/?probe=94b2e5d5ff) | Apr 23, 2021 |
| Alienware     | M15x                        | Notebook    | [0b60c1cb25](https://bsd-hardware.info/?probe=0b60c1cb25) | Apr 22, 2021 |
| Lenovo        | ThinkPad E490 20N9001SBR    | Notebook    | [852a900303](https://bsd-hardware.info/?probe=852a900303) | Apr 22, 2021 |
| Lenovo        | ThinkPad Edge E320 1298R... | Notebook    | [6a96e2c5b1](https://bsd-hardware.info/?probe=6a96e2c5b1) | Apr 22, 2021 |
| Lenovo        | ThinkPad X270 20HMCTO1WW    | Notebook    | [7c7573eb45](https://bsd-hardware.info/?probe=7c7573eb45) | Apr 22, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [6251043541](https://bsd-hardware.info/?probe=6251043541) | Apr 22, 2021 |
| Lenovo        | ThinkPad X270 20HMS0NS00    | Notebook    | [72fb01f474](https://bsd-hardware.info/?probe=72fb01f474) | Apr 22, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [2b97986de1](https://bsd-hardware.info/?probe=2b97986de1) | Apr 21, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [a932c6d687](https://bsd-hardware.info/?probe=a932c6d687) | Apr 21, 2021 |
| Dell          | 0MWYPT A02                  | Desktop     | [92d895d2d4](https://bsd-hardware.info/?probe=92d895d2d4) | Apr 21, 2021 |
| ASRock        | J4105-ITX                   | Desktop     | [66eee76b50](https://bsd-hardware.info/?probe=66eee76b50) | Apr 21, 2021 |
| HP            | 8430 1000                   | All in one  | [0d21e083f4](https://bsd-hardware.info/?probe=0d21e083f4) | Apr 20, 2021 |
| Dell          | Latitude 5580               | Notebook    | [f967516613](https://bsd-hardware.info/?probe=f967516613) | Apr 20, 2021 |
| ASRock        | H110M-STX                   | Desktop     | [c98cb0e438](https://bsd-hardware.info/?probe=c98cb0e438) | Apr 19, 2021 |
| Dell          | Latitude E6440              | Notebook    | [3a656ded12](https://bsd-hardware.info/?probe=3a656ded12) | Apr 19, 2021 |
| Dell          | Latitude E6440              | Notebook    | [68f57531cb](https://bsd-hardware.info/?probe=68f57531cb) | Apr 19, 2021 |
| System76      | Lemur Pro                   | Notebook    | [0bd96ef663](https://bsd-hardware.info/?probe=0bd96ef663) | Apr 19, 2021 |
| Supermicro    | X7SPA-HF                    | Desktop     | [418cc1382c](https://bsd-hardware.info/?probe=418cc1382c) | Apr 18, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [be1821da8a](https://bsd-hardware.info/?probe=be1821da8a) | Apr 18, 2021 |
| MSI           | H81M-P33                    | Desktop     | [3a81fe2ee4](https://bsd-hardware.info/?probe=3a81fe2ee4) | Apr 18, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [ce7b152e96](https://bsd-hardware.info/?probe=ce7b152e96) | Apr 17, 2021 |
| Unknown       | Unknown                     | Desktop     | [48090193c1](https://bsd-hardware.info/?probe=48090193c1) | Apr 17, 2021 |
| Unknown       | Unknown                     | Desktop     | [1c4a81b9a5](https://bsd-hardware.info/?probe=1c4a81b9a5) | Apr 17, 2021 |
| Unknown       | Unknown                     | Desktop     | [7b295345e6](https://bsd-hardware.info/?probe=7b295345e6) | Apr 17, 2021 |
| Unknown       | Unknown                     | Desktop     | [0c708350cd](https://bsd-hardware.info/?probe=0c708350cd) | Apr 17, 2021 |
| ASUSTek       | Q500A                       | Notebook    | [c52b593262](https://bsd-hardware.info/?probe=c52b593262) | Apr 17, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [9dfe1dae23](https://bsd-hardware.info/?probe=9dfe1dae23) | Apr 16, 2021 |
| ASRock        | AM1H-ITX                    | Desktop     | [917ee44fe9](https://bsd-hardware.info/?probe=917ee44fe9) | Apr 15, 2021 |
| Beckhoff A... | CB3163 G5                   | Desktop     | [25df932cdf](https://bsd-hardware.info/?probe=25df932cdf) | Apr 14, 2021 |
| Beckhoff A... | CX51x0 G2                   | Desktop     | [ab8247d8b5](https://bsd-hardware.info/?probe=ab8247d8b5) | Apr 14, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [270bd22b8d](https://bsd-hardware.info/?probe=270bd22b8d) | Apr 14, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [431eaac648](https://bsd-hardware.info/?probe=431eaac648) | Apr 14, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [9050866fb2](https://bsd-hardware.info/?probe=9050866fb2) | Apr 12, 2021 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 137       | 89.54%  |
| arm64 | 11        | 7.19%   |
| i386  | 4         | 2.61%   |
| arm   | 1         | 0.65%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 45        | 29.41%  |
| XFCE          | 26        | 16.99%  |
| KDE5          | 25        | 16.34%  |
| TWM           | 14        | 9.15%   |
| GNOME         | 14        | 9.15%   |
| MATE          | 9         | 5.88%   |
| Openbox       | 6         | 3.92%   |
| i3            | 4         | 2.61%   |
| LXQt          | 2         | 1.31%   |
| Enlightenment | 2         | 1.31%   |
| Cinnamon      | 2         | 1.31%   |
| AwesomeWM     | 2         | 1.31%   |
| GNUstep       | 1         | 0.65%   |
| Fluxbox       | 1         | 0.65%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 107       | 69.93%  |
| Console | 45        | 29.41%  |
| Wayland | 1         | 0.65%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 85        | 55.56%  |
| SDDM    | 27        | 17.65%  |
| SLiM    | 13        | 8.5%    |
| GDM     | 13        | 8.5%    |
| LightDM | 9         | 5.88%   |
| XDM     | 5         | 3.27%   |
| Ly      | 1         | 0.65%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| C               | 105       | 68.63%  |
| en_US           | 14        | 9.15%   |
| Unknown         | 9         | 5.88%   |
| ru_RU           | 5         | 3.27%   |
| de_DE           | 5         | 3.27%   |
| fr_FR           | 4         | 2.61%   |
| nb_NO           | 3         | 1.96%   |
| en_GB           | 2         | 1.31%   |
| uk_UA           | 1         | 0.65%   |
| pt_PT           | 1         | 0.65%   |
| pl_PL           | 1         | 0.65%   |
| ja_JP           | 1         | 0.65%   |
| it_IT.ISO8859-1 | 1         | 0.65%   |
| es_ES           | 1         | 0.65%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 105       | 67.31%  |
| BIOS | 51        | 32.69%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 103       | 67.32%  |
| Ufs  | 50        | 32.68%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 138       | 90.2%   |
| MBR  | 15        | 9.8%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 27        | 17.65%  |
| Lenovo                  | 24        | 15.69%  |
| ASUSTek Computer        | 19        | 12.42%  |
| Unknown                 | 12        | 7.84%   |
| Hewlett-Packard         | 10        | 6.54%   |
| Gigabyte Technology     | 9         | 5.88%   |
| ASRock                  | 9         | 5.88%   |
| MSI                     | 6         | 3.92%   |
| Apple                   | 4         | 2.61%   |
| Acer                    | 4         | 2.61%   |
| Toshiba                 | 3         | 1.96%   |
| Cisco Systems           | 3         | 1.96%   |
| Beckhoff Automation     | 3         | 1.96%   |
| System76                | 2         | 1.31%   |
| Samsung Electronics     | 2         | 1.31%   |
| Raspberry Pi Foundation | 2         | 1.31%   |
| Pegatron                | 2         | 1.31%   |
| Notebook                | 2         | 1.31%   |
| Intel                   | 2         | 1.31%   |
| Wistron                 | 1         | 0.65%   |
| Supermicro              | 1         | 0.65%   |
| Shuttle                 | 1         | 0.65%   |
| Medion                  | 1         | 0.65%   |
| GVC                     | 1         | 0.65%   |
| Fujitsu                 | 1         | 0.65%   |
| EVGA                    | 1         | 0.65%   |
| Alienware               | 1         | 0.65%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 12        | 7.84%   |
| ASUS All Series                            | 3         | 1.96%   |
| Cisco Systems UCSC-C240-M4L                | 2         | 1.31%   |
| Beckhoff Automation Industrial PC          | 2         | 1.31%   |
| ASUS TUF GAMING X570-PLUS                  | 2         | 1.31%   |
| ASRock B450M Pro4                          | 2         | 1.31%   |
| Wistron ProLiant ML110 G6                  | 1         | 0.65%   |
| Toshiba TECRA M11                          | 1         | 0.65%   |
| Toshiba Satellite L50-C                    | 1         | 0.65%   |
| Toshiba PORTEGE X20W-D                     | 1         | 0.65%   |
| System76 Lemur Pro                         | 1         | 0.65%   |
| System76 Gazelle                           | 1         | 0.65%   |
| Supermicro X7SPA-HF                        | 1         | 0.65%   |
| Shuttle SH87R                              | 1         | 0.65%   |
| Samsung NC10                               | 1         | 0.65%   |
| Samsung 300E5M/300E5L                      | 1         | 0.65%   |
| RPi rpi                                    | 1         | 0.65%   |
| RPi Raspberry Pi                           | 1         | 0.65%   |
| Pegatron T12Ah                             | 1         | 0.65%   |
| Pegatron SAISHIAT2                         | 1         | 0.65%   |
| Notebook NL5xRU                            | 1         | 0.65%   |
| Notebook N7x0WU                            | 1         | 0.65%   |
| MSI MS-7C80                                | 1         | 0.65%   |
| MSI MS-7C02                                | 1         | 0.65%   |
| MSI MS-7B09                                | 1         | 0.65%   |
| MSI MS-7817                                | 1         | 0.65%   |
| MSI MS-7677                                | 1         | 0.65%   |
| MSI GL65 Leopard 10SFSK                    | 1         | 0.65%   |
| Medion MS-7616                             | 1         | 0.65%   |
| Lenovo Z51-70 80K6                         | 1         | 0.65%   |
| Lenovo ThinkStation P720 30BAS1HX00        | 1         | 0.65%   |
| Lenovo ThinkPad X380 Yoga 20LH000NPG       | 1         | 0.65%   |
| Lenovo ThinkPad X270 20HMS0NS00            | 1         | 0.65%   |
| Lenovo ThinkPad X270 20HMCTO1WW            | 1         | 0.65%   |
| Lenovo ThinkPad X230 2325A95               | 1         | 0.65%   |
| Lenovo ThinkPad X220 4291PU5               | 1         | 0.65%   |
| Lenovo ThinkPad X220 4291ON5               | 1         | 0.65%   |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9CTO1WW | 1         | 0.65%   |
| Lenovo ThinkPad T440p 20AW0049LL           | 1         | 0.65%   |
| Lenovo ThinkPad T420 4237A12               | 1         | 0.65%   |
| Lenovo ThinkPad T420 4236NHG               | 1         | 0.65%   |
| Lenovo ThinkPad T410 2516DCU               | 1         | 0.65%   |
| Lenovo ThinkPad S1 Yoga 12 20DKS0AA00      | 1         | 0.65%   |
| Lenovo ThinkPad P73 20QRCTO1WW             | 1         | 0.65%   |
| Lenovo ThinkPad Edge E320 1298RJ1          | 1         | 0.65%   |
| Lenovo ThinkPad E490 20N9001SBR            | 1         | 0.65%   |
| Lenovo ThinkPad E490 20N8CTO1WW            | 1         | 0.65%   |
| Lenovo ThinkPad E15 Gen 3 20YG006GGE       | 1         | 0.65%   |
| Lenovo ThinkPad E14 20RAS0F600             | 1         | 0.65%   |
| Lenovo Rescuer-15ISK 80RQ                  | 1         | 0.65%   |
| Lenovo IdeaPad 320-15AST 80XV              | 1         | 0.65%   |
| Lenovo G505 20240                          | 1         | 0.65%   |
| Lenovo G40-70 20369                        | 1         | 0.65%   |
| Intel NUC5i3RYB H41000-503                 | 1         | 0.65%   |
| Intel NUC5CPYB H61145-413                  | 1         | 0.65%   |
| HP Z220 CMT Workstation                    | 1         | 0.65%   |
| HP ProLiant MicroServer Gen8               | 1         | 0.65%   |
| HP ProLiant BL460c G6                      | 1         | 0.65%   |
| HP Pavilion Laptop 15-cc0xx                | 1         | 0.65%   |
| HP Laptop 17-by0xxx                        | 1         | 0.65%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo ThinkPad                | 18        | 11.76%  |
| Unknown                        | 12        | 7.84%   |
| Dell Latitude                  | 10        | 6.54%   |
| Dell Inspiron                  | 8         | 5.23%   |
| Dell Precision                 | 3         | 1.96%   |
| ASUS TUF                       | 3         | 1.96%   |
| ASUS All                       | 3         | 1.96%   |
| HP ProLiant                    | 2         | 1.31%   |
| Gigabyte X570                  | 2         | 1.31%   |
| Dell Vostro                    | 2         | 1.31%   |
| Cisco Systems UCSC-C240-M4L    | 2         | 1.31%   |
| Beckhoff Automation Industrial | 2         | 1.31%   |
| ASRock X570                    | 2         | 1.31%   |
| ASRock B450M                   | 2         | 1.31%   |
| Acer Aspire                    | 2         | 1.31%   |
| Wistron ProLiant               | 1         | 0.65%   |
| Toshiba TECRA                  | 1         | 0.65%   |
| Toshiba Satellite              | 1         | 0.65%   |
| Toshiba PORTEGE                | 1         | 0.65%   |
| System76 Lemur                 | 1         | 0.65%   |
| System76 Gazelle               | 1         | 0.65%   |
| Supermicro X7SPA-HF            | 1         | 0.65%   |
| Shuttle SH87R                  | 1         | 0.65%   |
| Samsung NC10                   | 1         | 0.65%   |
| Samsung 300E5M                 | 1         | 0.65%   |
| RPi rpi                        | 1         | 0.65%   |
| RPi Raspberry                  | 1         | 0.65%   |
| Pegatron T12Ah                 | 1         | 0.65%   |
| Pegatron SAISHIAT2             | 1         | 0.65%   |
| Notebook NL5xRU                | 1         | 0.65%   |
| Notebook N7x0WU                | 1         | 0.65%   |
| MSI MS-7C80                    | 1         | 0.65%   |
| MSI MS-7C02                    | 1         | 0.65%   |
| MSI MS-7B09                    | 1         | 0.65%   |
| MSI MS-7817                    | 1         | 0.65%   |
| MSI MS-7677                    | 1         | 0.65%   |
| MSI GL65                       | 1         | 0.65%   |
| Medion MS-7616                 | 1         | 0.65%   |
| Lenovo Z51-70                  | 1         | 0.65%   |
| Lenovo ThinkStation            | 1         | 0.65%   |
| Lenovo Rescuer-15ISK           | 1         | 0.65%   |
| Lenovo IdeaPad                 | 1         | 0.65%   |
| Lenovo G505                    | 1         | 0.65%   |
| Lenovo G40-70                  | 1         | 0.65%   |
| Intel NUC5i3RYB                | 1         | 0.65%   |
| Intel NUC5CPYB                 | 1         | 0.65%   |
| HP Z220                        | 1         | 0.65%   |
| HP Pavilion                    | 1         | 0.65%   |
| HP Laptop                      | 1         | 0.65%   |
| HP ENVY                        | 1         | 0.65%   |
| HP EliteOne                    | 1         | 0.65%   |
| HP EliteBook                   | 1         | 0.65%   |
| HP Compaq                      | 1         | 0.65%   |
| HP All-in-One                  | 1         | 0.65%   |
| GVC EQUIUM                     | 1         | 0.65%   |
| Gigabyte X58A-UD5              | 1         | 0.65%   |
| Gigabyte X470                  | 1         | 0.65%   |
| Gigabyte H81M-S2PV             | 1         | 0.65%   |
| Gigabyte F2A75M-HD2            | 1         | 0.65%   |
| Gigabyte B85-HD3               | 1         | 0.65%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 29        | 18.95%  |
| 2019    | 23        | 15.03%  |
| 2018    | 19        | 12.42%  |
| 2021    | 13        | 8.5%    |
| 2015    | 10        | 6.54%   |
| 2012    | 10        | 6.54%   |
| Unknown | 10        | 6.54%   |
| 2013    | 8         | 5.23%   |
| 2011    | 7         | 4.58%   |
| 2016    | 6         | 3.92%   |
| 2014    | 4         | 2.61%   |
| 2008    | 4         | 2.61%   |
| 2017    | 3         | 1.96%   |
| 2010    | 3         | 1.96%   |
| 2009    | 3         | 1.96%   |
| 2007    | 1         | 0.65%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 74        | 48.37%  |
| Desktop        | 59        | 38.56%  |
| System on chip | 8         | 5.23%   |
| Server         | 5         | 3.27%   |
| All in one     | 3         | 1.96%   |
| Convertible    | 2         | 1.31%   |
| Mini pc        | 2         | 1.31%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 152       | 99.35%  |
| Yes  | 1         | 0.65%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 51        | 33.33%  |
| 16.01-24.0      | 31        | 20.26%  |
| 4.01-8.0        | 22        | 14.38%  |
| 32.01-64.0      | 18        | 11.76%  |
| 64.01-256.0     | 14        | 9.15%   |
| 2.01-3.0        | 5         | 3.27%   |
| 3.01-4.0        | 3         | 1.96%   |
| 24.01-32.0      | 3         | 1.96%   |
| 0.51-1.0        | 3         | 1.96%   |
| More than 256.0 | 1         | 0.65%   |
| 1.01-2.0        | 1         | 0.65%   |
| 0.01-0.5        | 1         | 0.65%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 70        | 45.45%  |
| 0.51-1.0   | 42        | 27.27%  |
| 1.01-2.0   | 21        | 13.64%  |
| 3.01-4.0   | 6         | 3.9%    |
| 2.01-3.0   | 4         | 2.6%    |
| 4.01-8.0   | 3         | 1.95%   |
| 16.01-24.0 | 3         | 1.95%   |
| 0          | 3         | 1.95%   |
| 24.01-32.0 | 1         | 0.65%   |
| 8.01-16.0  | 1         | 0.65%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 81        | 52.26%  |
| 2      | 27        | 17.42%  |
| 3      | 14        | 9.03%   |
| 0      | 11        | 7.1%    |
| 4      | 6         | 3.87%   |
| 5      | 5         | 3.23%   |
| 7      | 3         | 1.94%   |
| 6      | 3         | 1.94%   |
| 12     | 2         | 1.29%   |
| 14     | 1         | 0.65%   |
| 13     | 1         | 0.65%   |
| 9      | 1         | 0.65%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 105       | 68.18%  |
| Yes       | 49        | 31.82%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 130       | 84.97%  |
| No        | 23        | 15.03%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 101       | 66.01%  |
| No        | 52        | 33.99%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 83        | 54.25%  |
| Yes       | 70        | 45.75%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 44        | 28.76%  |
| Russia      | 15        | 9.8%    |
| Germany     | 14        | 9.15%   |
| UK          | 9         | 5.88%   |
| Netherlands | 7         | 4.58%   |
| France      | 5         | 3.27%   |
| Brazil      | 4         | 2.61%   |
| Ukraine     | 3         | 1.96%   |
| Switzerland | 3         | 1.96%   |
| Japan       | 3         | 1.96%   |
| India       | 3         | 1.96%   |
| Canada      | 3         | 1.96%   |
| Thailand    | 2         | 1.31%   |
| Spain       | 2         | 1.31%   |
| Poland      | 2         | 1.31%   |
| Norway      | 2         | 1.31%   |
| Mexico      | 2         | 1.31%   |
| Iran        | 2         | 1.31%   |
| Guadeloupe  | 2         | 1.31%   |
| Finland     | 2         | 1.31%   |
| Colombia    | 2         | 1.31%   |
| Vietnam     | 1         | 0.65%   |
| Turkey      | 1         | 0.65%   |
| Sweden      | 1         | 0.65%   |
| Slovakia    | 1         | 0.65%   |
| Romania     | 1         | 0.65%   |
| Qatar       | 1         | 0.65%   |
| Portugal    | 1         | 0.65%   |
| New Zealand | 1         | 0.65%   |
| Nepal       | 1         | 0.65%   |
| Namibia     | 1         | 0.65%   |
| Lithuania   | 1         | 0.65%   |
| Italy       | 1         | 0.65%   |
| Ireland     | 1         | 0.65%   |
| Hungary     | 1         | 0.65%   |
| Guatemala   | 1         | 0.65%   |
| Czechia     | 1         | 0.65%   |
| China       | 1         | 0.65%   |
| Chile       | 1         | 0.65%   |
| Austria     | 1         | 0.65%   |
| Australia   | 1         | 0.65%   |
| Argentina   | 1         | 0.65%   |
| Albania     | 1         | 0.65%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Lexington              | 5         | 3.23%   |
| Seattle                | 4         | 2.58%   |
| Moscow                 | 3         | 1.94%   |
| Lübeck                | 3         | 1.94%   |
| Alphen aan den Rijn    | 3         | 1.94%   |
| Tehran                 | 2         | 1.29%   |
| Salem                  | 2         | 1.29%   |
| Redmond                | 2         | 1.29%   |
| Ozersk                 | 2         | 1.29%   |
| Minneapolis            | 2         | 1.29%   |
| Menlo Park             | 2         | 1.29%   |
| Le Gosier              | 2         | 1.29%   |
| Kyiv                   | 2         | 1.29%   |
| Kirkland               | 2         | 1.29%   |
| Irkutsk                | 2         | 1.29%   |
| Helsinki               | 2         | 1.29%   |
| Chelyabinsk            | 2         | 1.29%   |
| Berlin                 | 2         | 1.29%   |
| Zurich                 | 1         | 0.65%   |
| Wenatchee              | 1         | 0.65%   |
| Weimar                 | 1         | 0.65%   |
| Wausau                 | 1         | 0.65%   |
| Warsaw                 | 1         | 0.65%   |
| Vostochnoe Degunino    | 1         | 0.65%   |
| Vilnius                | 1         | 0.65%   |
| Vancouver              | 1         | 0.65%   |
| Valladolid             | 1         | 0.65%   |
| Vadodara               | 1         | 0.65%   |
| Vacaville              | 1         | 0.65%   |
| Tyumen                 | 1         | 0.65%   |
| Tuddal                 | 1         | 0.65%   |
| Trang                  | 1         | 0.65%   |
| The Bronx              | 1         | 0.65%   |
| Teteghem               | 1         | 0.65%   |
| Tatab??nya             | 1         | 0.65%   |
| São Paulo             | 1         | 0.65%   |
| São José dos Campos  | 1         | 0.65%   |
| Sydney                 | 1         | 0.65%   |
| Sundebru               | 1         | 0.65%   |
| Suginami-ku            | 1         | 0.65%   |
| Stuttgart              | 1         | 0.65%   |
| St. Catharines         | 1         | 0.65%   |
| Scottsdale             | 1         | 0.65%   |
| Sarandë               | 1         | 0.65%   |
| San Vicent del Raspeig | 1         | 0.65%   |
| San Diego              | 1         | 0.65%   |
| San Antonio            | 1         | 0.65%   |
| Rugby                  | 1         | 0.65%   |
| Rostov-on-Don          | 1         | 0.65%   |
| Rionegro               | 1         | 0.65%   |
| Prague                 | 1         | 0.65%   |
| Porto União           | 1         | 0.65%   |
| Otjiwarongo            | 1         | 0.65%   |
| Orléans               | 1         | 0.65%   |
| Omsk                   | 1         | 0.65%   |
| Olin                   | 1         | 0.65%   |
| Oklahoma City          | 1         | 0.65%   |
| Nunoa                  | 1         | 0.65%   |
| Novosibirsk            | 1         | 0.65%   |
| Niagara Falls          | 1         | 0.65%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 37        | 71     | 17.54%  |
| Seagate             | 34        | 99     | 16.11%  |
| WDC                 | 31        | 95     | 14.69%  |
| Toshiba             | 19        | 26     | 9%      |
| Kingston            | 17        | 19     | 8.06%   |
| Crucial             | 15        | 16     | 7.11%   |
| Intel               | 7         | 8      | 3.32%   |
| Hitachi             | 7         | 17     | 3.32%   |
| HGST                | 5         | 7      | 2.37%   |
| A-DATA Technology   | 5         | 5      | 2.37%   |
| SanDisk             | 4         | 4      | 1.9%    |
| SK Hynix            | 3         | 3      | 1.42%   |
| Phison              | 3         | 3      | 1.42%   |
| PNY                 | 2         | 2      | 0.95%   |
| PLEXTOR             | 2         | 2      | 0.95%   |
| Micron Technology   | 2         | 2      | 0.95%   |
| Corsair             | 2         | 2      | 0.95%   |
| VMware              | 1         | 1      | 0.47%   |
| Verbatim            | 1         | 1      | 0.47%   |
| TCSUNBOW            | 1         | 1      | 0.47%   |
| SPCC                | 1         | 1      | 0.47%   |
| Smartbuy            | 1         | 1      | 0.47%   |
| OWC                 | 1         | 1      | 0.47%   |
| MAXTOR              | 1         | 1      | 0.47%   |
| LITEONIT            | 1         | 1      | 0.47%   |
| Lenovo              | 1         | 1      | 0.47%   |
| KingSpec            | 1         | 1      | 0.47%   |
| KingDian            | 1         | 1      | 0.47%   |
| Intenso             | 1         | 1      | 0.47%   |
| Hewlett-Packard     | 1         | 2      | 0.47%   |
| Gigabyte Technology | 1         | 1      | 0.47%   |
| Fujitsu             | 1         | 2      | 0.47%   |
| Apple               | 1         | 1      | 0.47%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Crucial CT500MX500SSD1 500GB       | 5         | 2.01%   |
| Seagate ST4000DM000-1F2168 4TB     | 4         | 1.61%   |
| Kingston SA400S37240G 240GB        | 4         | 1.61%   |
| Toshiba MQ01ABD100 1TB             | 3         | 1.2%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 1.2%    |
| Samsung SSD 970 EVO Plus 250GB     | 3         | 1.2%    |
| Samsung SSD 970 EVO 500GB          | 3         | 1.2%    |
| Samsung SSD 860 EVO 500GB          | 3         | 1.2%    |
| Samsung MZVLB256HBHQ-000L7 256GB   | 3         | 1.2%    |
| Kingston SA400S37120G 120GB        | 3         | 1.2%    |
| WDC WDS500G2B0C-00PXH0 500GB       | 2         | 0.8%    |
| WDC WD20EFRX-68EUZN0 2TB           | 2         | 0.8%    |
| Toshiba MG04SCA20EN 2TB            | 2         | 0.8%    |
| Toshiba DT01ACA100 1TB             | 2         | 0.8%    |
| Seagate ST8000VN004-2M2101 8TB     | 2         | 0.8%    |
| Seagate ST4000DM004-2CV104 4TB     | 2         | 0.8%    |
| Seagate ST2000NM0023 2TB           | 2         | 0.8%    |
| Seagate ST1000NM0023 1TB           | 2         | 0.8%    |
| Samsung SSD 970 EVO Plus 1TB       | 2         | 0.8%    |
| Samsung SSD 860 EVO 1TB            | 2         | 0.8%    |
| Samsung SSD 850 EVO 250GB          | 2         | 0.8%    |
| Kingston SVP200S37A60G 64GB        | 2         | 0.8%    |
| Kingston SMS200S3120G 120GB        | 2         | 0.8%    |
| Crucial CT120BX500SSD1 120GB       | 2         | 0.8%    |
| WDC WDS500G2B0B-00YS70 500GB       | 1         | 0.4%    |
| WDC WDS250G2B0A 250GB              | 1         | 0.4%    |
| WDC WDS240G2G0A-00JH30 240GB       | 1         | 0.4%    |
| WDC WDS120G2G0B-00EPW0 120GB       | 1         | 0.4%    |
| WDC WDS120G2G0A-00JH30 120GB       | 1         | 0.4%    |
| WDC WDS100T2B0B-00YS70 1TB         | 1         | 0.4%    |
| WDC WD80EMAZ-00WJTA0 8TB           | 1         | 0.4%    |
| WDC WD80EFZX-68UW8N0 8TB           | 1         | 0.4%    |
| WDC WD80EFAX-68LHPN0 8TB           | 1         | 0.4%    |
| WDC WD7500BPVT-80HXZT3 752GB       | 1         | 0.4%    |
| WDC WD6003FZBX-00K5WB0 6TB         | 1         | 0.4%    |
| WDC WD5000LPVX-75V0TT0 500GB       | 1         | 0.4%    |
| WDC WD5000BEVT-75A0RT0 500GB       | 1         | 0.4%    |
| WDC WD5000AAKX-083CA0 500GB        | 1         | 0.4%    |
| WDC WD40EZRZ-22GXCB0 4TB           | 1         | 0.4%    |
| WDC WD40EZAZ-00SF3B0 4TB           | 1         | 0.4%    |
| WDC WD40EFRX-68N32N0 4TB           | 1         | 0.4%    |
| WDC WD3200BPVT-75ZEST0 320GB       | 1         | 0.4%    |
| WDC WD30EZRX-00AZ6B0 3TB           | 1         | 0.4%    |
| WDC WD30EFRX-68EUZN0 3TB           | 1         | 0.4%    |
| WDC WD2500BEVT-08A23T1 250GB       | 1         | 0.4%    |
| WDC WD20SPZX-22UA7T0 2TB           | 1         | 0.4%    |
| WDC WD20EARX-00PASB0 2TB           | 1         | 0.4%    |
| WDC WD1600BEVT-11ZCT0 160GB        | 1         | 0.4%    |
| WDC WD120EMFZ-11A6JA0 12TB         | 1         | 0.4%    |
| WDC WD120EMAZ-11BLFA0 12TB         | 1         | 0.4%    |
| WDC WD10SPZX-08Z10 1TB             | 1         | 0.4%    |
| WDC WD10SDRW-34A0XS0 1TB           | 1         | 0.4%    |
| WDC WD10JPVX-22JC3T0 1TB           | 1         | 0.4%    |
| WDC WD10JPLX-00MBPT1 1TB           | 1         | 0.4%    |
| WDC WD10EADS-00P8B0 1TB            | 1         | 0.4%    |
| WDC WD102KRYZ-01A5AB0 10TB         | 1         | 0.4%    |
| WDC WD100EZAZ-11TDBA0 10TB         | 1         | 0.4%    |
| WDC WD1001FALS-00J7B0 1TB          | 1         | 0.4%    |
| WDC PC SN520 NVMe 256GB            | 1         | 0.4%    |
| VMware Virtual disk 112GB          | 1         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 34        | 99     | 37.78%  |
| WDC                 | 23        | 85     | 25.56%  |
| Toshiba             | 16        | 23     | 17.78%  |
| Hitachi             | 7         | 17     | 7.78%   |
| HGST                | 5         | 7      | 5.56%   |
| Samsung Electronics | 2         | 3      | 2.22%   |
| MAXTOR              | 1         | 1      | 1.11%   |
| Hewlett-Packard     | 1         | 2      | 1.11%   |
| Fujitsu             | 1         | 2      | 1.11%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 22        | 40     | 23.91%  |
| Crucial             | 15        | 16     | 16.3%   |
| Kingston            | 14        | 16     | 15.22%  |
| WDC                 | 6         | 7      | 6.52%   |
| Intel               | 6         | 7      | 6.52%   |
| SanDisk             | 4         | 4      | 4.35%   |
| A-DATA Technology   | 4         | 4      | 4.35%   |
| SK Hynix            | 2         | 2      | 2.17%   |
| Micron Technology   | 2         | 2      | 2.17%   |
| VMware              | 1         | 1      | 1.09%   |
| Verbatim            | 1         | 1      | 1.09%   |
| Toshiba             | 1         | 1      | 1.09%   |
| TCSUNBOW            | 1         | 1      | 1.09%   |
| SPCC                | 1         | 1      | 1.09%   |
| Smartbuy            | 1         | 1      | 1.09%   |
| PNY                 | 1         | 1      | 1.09%   |
| PLEXTOR             | 1         | 1      | 1.09%   |
| OWC                 | 1         | 1      | 1.09%   |
| LITEONIT            | 1         | 1      | 1.09%   |
| Lenovo              | 1         | 1      | 1.09%   |
| KingSpec            | 1         | 1      | 1.09%   |
| KingDian            | 1         | 1      | 1.09%   |
| Intenso             | 1         | 1      | 1.09%   |
| Gigabyte Technology | 1         | 1      | 1.09%   |
| Corsair             | 1         | 1      | 1.09%   |
| Apple               | 1         | 1      | 1.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 78        | 115    | 41.27%  |
| HDD  | 77        | 239    | 40.74%  |
| NVMe | 34        | 45     | 17.99%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 127       | 354    | 78.88%  |
| NVMe | 34        | 45     | 21.12%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 89        | 126    | 52.35%  |
| 0.51-1.0   | 40        | 89     | 23.53%  |
| 1.01-2.0   | 12        | 27     | 7.06%   |
| 3.01-4.0   | 9         | 31     | 5.29%   |
| 4.01-10.0  | 9         | 44     | 5.29%   |
| 2.01-3.0   | 8         | 23     | 4.71%   |
| 10.01-20.0 | 3         | 14     | 1.76%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 47        | 30.72%  |
| 251-500        | 30        | 19.61%  |
| 501-1000       | 19        | 12.42%  |
| 51-100         | 16        | 10.46%  |
| 21-50          | 14        | 9.15%   |
| 1-20           | 12        | 7.84%   |
| 1001-2000      | 8         | 5.23%   |
| More than 3000 | 3         | 1.96%   |
| 2001-3000      | 3         | 1.96%   |
| Unknown        | 1         | 0.65%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 129       | 84.31%  |
| 21-50          | 10        | 6.54%   |
| 101-250        | 4         | 2.61%   |
| 51-100         | 4         | 2.61%   |
| More than 3000 | 2         | 1.31%   |
| 251-500        | 2         | 1.31%   |
| 1001-2000      | 1         | 0.65%   |
| Unknown        | 1         | 0.65%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WDS120G2G0A-00JH30 120GB                     | 1         | 1      | 3.13%   |
| WDC WD7500BPVT-80HXZT3 752GB                     | 1         | 1      | 3.13%   |
| WDC WD5000BEVT-75A0RT0 500GB                     | 1         | 1      | 3.13%   |
| WDC WD5000AAKX-083CA0 500GB                      | 1         | 1      | 3.13%   |
| WDC WD3200BPVT-75ZEST0 320GB                     | 1         | 1      | 3.13%   |
| WDC WD2500BEVT-08A23T1 250GB                     | 1         | 1      | 3.13%   |
| WDC WD20EARX-00PASB0 2TB                         | 1         | 1      | 3.13%   |
| WDC WD10EADS-00P8B0 1TB                          | 1         | 1      | 3.13%   |
| Toshiba THNSNK512GVN8 512GB                      | 1         | 1      | 3.13%   |
| Toshiba MQ02ABD100H 1TB                          | 1         | 1      | 3.13%   |
| Seagate ST9640320AS 640GB                        | 1         | 1      | 3.13%   |
| Seagate ST9250827AS 250GB                        | 1         | 1      | 3.13%   |
| Seagate ST500LT012-9WS142 500GB                  | 1         | 1      | 3.13%   |
| Seagate ST380013AS 80GB                          | 1         | 2      | 3.13%   |
| Seagate ST3250620AS 250GB                        | 1         | 1      | 3.13%   |
| Seagate ST31500341AS 1.5TB                       | 1         | 1      | 3.13%   |
| Seagate ST31000524AS 1TB                         | 1         | 1      | 3.13%   |
| Seagate ST1000LM014-1EJ164 1TB                   | 1         | 1      | 3.13%   |
| Samsung Electronics SSD PM841 2.5-inch 7mm 256GB | 1         | 1      | 3.13%   |
| Samsung Electronics SSD 840 EVO 120GB            | 1         | 1      | 3.13%   |
| Samsung Electronics HM160HI 160GB                | 1         | 1      | 3.13%   |
| PLEXTOR PX-128M5S 128GB                          | 1         | 1      | 3.13%   |
| MAXTOR STM3160815AS 160GB                        | 1         | 1      | 3.13%   |
| Intel SSDSCKKF256G8H 256GB                       | 1         | 1      | 3.13%   |
| Intel SSDSC2BB120G6R 120GB                       | 1         | 1      | 3.13%   |
| Hitachi HTS545032B9A300 320GB                    | 1         | 1      | 3.13%   |
| Hitachi HTS543225A7A384 250GB                    | 1         | 1      | 3.13%   |
| Hitachi HTS541612J9SA00 120GB                    | 1         | 1      | 3.13%   |
| Hitachi HDS721010CLA332 1TB                      | 1         | 1      | 3.13%   |
| HGST HDN726060ALE614 6TB                         | 1         | 2      | 3.13%   |
| Crucial CT250MX200SSD1 250GB                     | 1         | 1      | 3.13%   |
| Corsair Force 3 SSD 180GB                        | 1         | 1      | 3.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 8      | 24.14%  |
| Seagate             | 6         | 9      | 20.69%  |
| Hitachi             | 4         | 4      | 13.79%  |
| Samsung Electronics | 3         | 3      | 10.34%  |
| Toshiba             | 2         | 2      | 6.9%    |
| Intel               | 2         | 2      | 6.9%    |
| PLEXTOR             | 1         | 1      | 3.45%   |
| MAXTOR              | 1         | 1      | 3.45%   |
| HGST                | 1         | 2      | 3.45%   |
| Crucial             | 1         | 1      | 3.45%   |
| Corsair             | 1         | 1      | 3.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 7      | 30%     |
| Seagate             | 6         | 9      | 30%     |
| Hitachi             | 4         | 4      | 20%     |
| Toshiba             | 1         | 1      | 5%      |
| Samsung Electronics | 1         | 1      | 5%      |
| MAXTOR              | 1         | 1      | 5%      |
| HGST                | 1         | 2      | 5%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 19        | 25     | 67.86%  |
| SSD  | 9         | 9      | 32.14%  |

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
| Works    | 124       | 358    | 80%     |
| Malfunc  | 27        | 34     | 17.42%  |
| Detected | 4         | 7      | 2.58%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 106       | 56.68%  |
| AMD                         | 25        | 13.37%  |
| Samsung Electronics         | 19        | 10.16%  |
| Broadcom / LSI              | 6         | 3.21%   |
| ASMedia Technology          | 6         | 3.21%   |
| Phison Electronics          | 5         | 2.67%   |
| Marvell Technology Group    | 4         | 2.14%   |
| Sandisk                     | 3         | 1.6%    |
| VMware                      | 2         | 1.07%   |
| Toshiba                     | 2         | 1.07%   |
| Nvidia                      | 2         | 1.07%   |
| Kingston Technology Company | 2         | 1.07%   |
| SK Hynix                    | 1         | 0.53%   |
| Lite-On Technology          | 1         | 0.53%   |
| Hewlett-Packard             | 1         | 0.53%   |
| Apple                       | 1         | 0.53%   |
| ADATA Technology            | 1         | 0.53%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 24        | 11.48%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 12        | 5.74%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 11        | 5.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 10        | 4.78%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 9         | 4.31%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 7         | 3.35%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6         | 2.87%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 6         | 2.87%   |
| AMD 400 Series Chipset SATA Controller                                           | 6         | 2.87%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 5         | 2.39%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 5         | 2.39%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 5         | 2.39%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 4         | 1.91%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 1.44%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.44%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 3         | 1.44%   |
| Unknown                                                                          | 3         | 1.44%   |
| VMware SATA AHCI controller                                                      | 2         | 0.96%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 2         | 0.96%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 0.96%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 2         | 0.96%   |
| Phison E12 NVMe Controller                                                       | 2         | 0.96%   |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 0.96%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                            | 2         | 0.96%   |
| Intel SATA Controller [RAID mode]                                                | 2         | 0.96%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 0.96%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 2         | 0.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 0.96%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 0.96%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 2         | 0.96%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 0.96%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 2         | 0.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 2         | 0.96%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 0.96%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                     | 2         | 0.96%   |
| VMware PVSCSI SCSI Controller                                                    | 1         | 0.48%   |
| Toshiba unknown                                                                  | 1         | 0.48%   |
| Toshiba BG3 NVMe SSD Controller                                                  | 1         | 0.48%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 1         | 0.48%   |
| Sandisk PC SN520 NVMe SSD                                                        | 1         | 0.48%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 0.48%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.48%   |
| Phison E18 PCIe4 NVMe Controller                                                 | 1         | 0.48%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                     | 1         | 0.48%   |
| Marvell Group 88SE9123 PCIe SATA 6.0 Gb/s controller                             | 1         | 0.48%   |
| Lite-On M8Pe Series NVMe SSD                                                     | 1         | 0.48%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.48%   |
| Intel SSD 660P Series                                                            | 1         | 0.48%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 1         | 0.48%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 0.48%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 0.48%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 0.48%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                    | 1         | 0.48%   |
| Intel C620 Series Chipset Family IDE Redirection                                 | 1         | 0.48%   |
| Intel C600/X79 series chipset SATA RAID Controller                               | 1         | 0.48%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 1         | 0.48%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 1         | 0.48%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 1         | 0.48%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 1         | 0.48%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 1         | 0.48%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 119       | 64.32%  |
| NVMe | 35        | 18.92%  |
| IDE  | 14        | 7.57%   |
| RAID | 12        | 6.49%   |
| SAS  | 5         | 2.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 115       | 75.16%  |
| AMD     | 26        | 16.99%  |
| ARM     | 8         | 5.23%   |
| Unknown | 3         | 1.96%   |
| Unknown | 1         | 0.65%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| ARM Cortex-A72 r0p3                   | 6         | 3.92%   |
| Intel Core i5-7200U CPU @ 2.50GHz     | 4         | 2.61%   |
| Intel Core i5-5300U CPU @ 2.30GHz     | 3         | 1.96%   |
| Intel Core i5-2520M CPU @ 2.50GHz     | 3         | 1.96%   |
| AMD Ryzen 7 2700 Eight-Core Processor | 3         | 1.96%   |
|                                       | 3         | 1.96%   |
| Intel Core i7-9750H CPU @ 2.60GHz     | 2         | 1.31%   |
| Intel Core i7-8565U CPU @ 1.80GHz     | 2         | 1.31%   |
| Intel Core i7-7500U CPU @ 2.70GHz     | 2         | 1.31%   |
| Intel Core i7-6700 CPU @ 3.40GHz      | 2         | 1.31%   |
| Intel Core i7-4510U CPU @ 2.00GHz     | 2         | 1.31%   |
| Intel Core i7-10750H CPU @ 2.60GHz    | 2         | 1.31%   |
| Intel Core i5-8350U CPU @ 1.70GHz     | 2         | 1.31%   |
| Intel Core i5-8250U CPU @ 1.60GHz     | 2         | 1.31%   |
| Intel Core i5-4300M CPU @ 2.60GHz     | 2         | 1.31%   |
| Intel Core i5-10210U CPU @ 1.60GHz    | 2         | 1.31%   |
| Intel Core i3-4005U CPU @ 1.70GHz     | 2         | 1.31%   |
| AMD Ryzen 9 5900X 12-Core Processor   | 2         | 1.31%   |
| AMD Ryzen 9 3900X 12-Core Processor   | 2         | 1.31%   |
| Unknown Implementer Processor r0p0    | 1         | 0.65%   |
| Intel Xeon Silver 4214 CPU @ 2.20GHz  | 1         | 0.65%   |
| Intel Xeon CPU X5650 @ 2.67GHz        | 1         | 0.65%   |
| Intel Xeon CPU X3440 @ 2.53GHz        | 1         | 0.65%   |
| Intel Xeon CPU E5520 @ 2.27GHz        | 1         | 0.65%   |
| Intel Xeon CPU E5-2650 v3 @ 2.30GHz   | 1         | 0.65%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz   | 1         | 0.65%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz   | 1         | 0.65%   |
| Intel Xeon CPU E3-1275 v5 @ 3.60GHz   | 1         | 0.65%   |
| Intel Processor 5Y70 CPU @ 1.10GHz    | 1         | 0.65%   |
| Intel Pentium M                       | 1         | 0.65%   |
| Intel Pentium II                      | 1         | 0.65%   |
| Intel Pentium CPU N3700 @ 1.60GHz     | 1         | 0.65%   |
| Intel Pentium CPU G630T @ 2.30GHz     | 1         | 0.65%   |
| Intel Pentium CPU G3420 @ 3.20GHz     | 1         | 0.65%   |
| Intel Pentium CPU G3220 @ 3.00GHz     | 1         | 0.65%   |
| Intel Pentium CPU G2020 @ 2.90GHz     | 1         | 0.65%   |
| Intel Pentium 4                       | 1         | 0.65%   |
| Intel Genuine CPU                     | 1         | 0.65%   |
| Intel CPU Version                     | 1         | 0.65%   |
| Intel Core i9-9900X CPU @ 3.50GHz     | 1         | 0.65%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz    | 1         | 0.65%   |
| Intel Core i7-6700K CPU @ 4.00GHz     | 1         | 0.65%   |
| Intel Core i7-6600U CPU @ 2.60GHz     | 1         | 0.65%   |
| Intel Core i7-4790S CPU @ 3.20GHz     | 1         | 0.65%   |
| Intel Core i7-4770T CPU @ 2.50GHz     | 1         | 0.65%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz    | 1         | 0.65%   |
| Intel Core i7-3770 CPU @ 3.40GHz      | 1         | 0.65%   |
| Intel Core i7-3632QM CPU @ 2.20GHz    | 1         | 0.65%   |
| Intel Core i7-3630QM CPU @ 2.40GHz    | 1         | 0.65%   |
| Intel Core i7-3610QE CPU @ 2.30GHz    | 1         | 0.65%   |
| Intel Core i7-2670QM CPU @ 2.20GHz    | 1         | 0.65%   |
| Intel Core i7-10700K CPU @ 3.80GHz    | 1         | 0.65%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz    | 1         | 0.65%   |
| Intel Core i7-10510U CPU @ 1.80GHz    | 1         | 0.65%   |
| Intel Core i7 CPU M 620 @ 2.67GHz     | 1         | 0.65%   |
| Intel Core i7 CPU                     | 1         | 0.65%   |
| Intel Core i5-9300H CPU @ 2.40GHz     | 1         | 0.65%   |
| Intel Core i5-8365U CPU @ 1.60GHz     | 1         | 0.65%   |
| Intel Core i5-8265U CPU @ 1.60GHz     | 1         | 0.65%   |
| Intel Core i5-7300U CPU @ 2.60GHz     | 1         | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i5          | 39        | 25.49%  |
| Intel Core i7          | 28        | 18.3%   |
| Intel Core i3          | 11        | 7.19%   |
| AMD Ryzen 7            | 9         | 5.88%   |
| ARM Cortex             | 8         | 5.23%   |
| Other                  | 7         | 4.58%   |
| Intel Xeon             | 7         | 4.58%   |
| Intel Pentium          | 6         | 3.92%   |
| Intel Core 2 Duo       | 6         | 3.92%   |
| Intel Celeron          | 6         | 3.92%   |
| AMD Ryzen 9            | 6         | 3.92%   |
| Intel Atom             | 4         | 2.61%   |
| AMD Ryzen 5            | 3         | 1.96%   |
| Intel Xeon Silver      | 1         | 0.65%   |
| Intel Pentium M        | 1         | 0.65%   |
| Intel Pentium 4        | 1         | 0.65%   |
| Intel Genuine          | 1         | 0.65%   |
| Intel Core i9          | 1         | 0.65%   |
| Intel Core 2 Quad      | 1         | 0.65%   |
| AMD Ryzen Threadripper | 1         | 0.65%   |
| AMD Ryzen 3            | 1         | 0.65%   |
| AMD FX                 | 1         | 0.65%   |
| AMD Athlon X4          | 1         | 0.65%   |
| AMD Athlon             | 1         | 0.65%   |
| AMD A6                 | 1         | 0.65%   |
| AMD A4                 | 1         | 0.65%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 55        | 35.95%  |
| 4       | 45        | 29.41%  |
| Unknown | 18        | 11.76%  |
| 16      | 9         | 5.88%   |
| 8       | 6         | 3.92%   |
| 6       | 6         | 3.92%   |
| 24      | 4         | 2.61%   |
| 12      | 4         | 2.61%   |
| 32      | 2         | 1.31%   |
| 1       | 2         | 1.31%   |
| 20      | 1         | 0.65%   |
| 10      | 1         | 0.65%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 139       | 90.85%  |
| Unknown | 9         | 5.88%   |
| 2       | 5         | 3.27%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 85        | 55.56%  |
| 1       | 49        | 32.03%  |
| Unknown | 19        | 12.42%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 24        | 15.69%  |
| Haswell       | 17        | 11.11%  |
| Unknown       | 13        | 8.5%    |
| Skylake       | 12        | 7.84%   |
| SandyBridge   | 11        | 7.19%   |
| Westmere      | 9         | 5.88%   |
| IvyBridge     | 9         | 5.88%   |
| Broadwell     | 7         | 4.58%   |
| Zen+          | 6         | 3.92%   |
| Zen 2         | 6         | 3.92%   |
| Penryn        | 6         | 3.92%   |
| Zen           | 4         | 2.61%   |
| Silvermont    | 4         | 2.61%   |
| Zen 3         | 3         | 1.96%   |
| Nehalem       | 3         | 1.96%   |
| CometLake     | 3         | 1.96%   |
| Bonnell       | 3         | 1.96%   |
| Piledriver    | 2         | 1.31%   |
| Jaguar        | 2         | 1.31%   |
| Excavator     | 2         | 1.31%   |
| Core          | 2         | 1.31%   |
| P6            | 1         | 0.65%   |
| NetBurst      | 1         | 0.65%   |
| IceLake       | 1         | 0.65%   |
| Goldmont plus | 1         | 0.65%   |
| Goldmont      | 1         | 0.65%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 89        | 54.27%  |
| Nvidia                               | 43        | 26.22%  |
| AMD                                  | 23        | 14.02%  |
| Matrox Electronics Systems           | 6         | 3.66%   |
| VMware                               | 2         | 1.22%   |
| NVidia / SGS Thomson (Joint Venture) | 1         | 0.61%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 5.33%   |
| Intel HD Graphics 620                                                                    | 7         | 4.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6         | 3.55%   |
| Intel HD Graphics 5500                                                                   | 6         | 3.55%   |
| Intel HD Graphics 530                                                                    | 6         | 3.55%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 3.55%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6         | 3.55%   |
| Intel UHD Graphics 620                                                                   | 5         | 2.96%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 4         | 2.37%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 2.37%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 2.37%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 2.37%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 2.37%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 3         | 1.78%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.78%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 1.18%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 1.18%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 2         | 1.18%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 1.18%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 1.18%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.18%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.18%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 1.18%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.18%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.18%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 1.18%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 1.18%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 2         | 1.18%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 1.18%   |
| AMD Renoir                                                                               | 2         | 1.18%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 2         | 1.18%   |
| Unknown                                                                                  | 2         | 1.18%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.59%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.59%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.59%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.59%   |
| Nvidia TU104M [GeForce RTX 2070 SUPER Mobile / Max-Q]                                    | 1         | 0.59%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 1         | 0.59%   |
| Nvidia MCP7A [GeForce 9400]                                                              | 1         | 0.59%   |
| Nvidia GT218 [NVS 300]                                                                   | 1         | 0.59%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.59%   |
| Nvidia GT216M [GeForce GT 240M]                                                          | 1         | 0.59%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.59%   |
| Nvidia GP108M [GeForce MX230]                                                            | 1         | 0.59%   |
| Nvidia GP107GL [Quadro P600]                                                             | 1         | 0.59%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1         | 0.59%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.59%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 0.59%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                    | 1         | 0.59%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.59%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 0.59%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 1         | 0.59%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.59%   |
| Nvidia GF116M [GeForce GT 560M]                                                          | 1         | 0.59%   |
| Nvidia GF110 [GeForce GTX 580]                                                           | 1         | 0.59%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 1         | 0.59%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 1         | 0.59%   |
| Nvidia GA104 [GeForce RTX 3070]                                                          | 1         | 0.59%   |
| Nvidia GA102 [GeForce RTX 3080]                                                          | 1         | 0.59%   |
| Nvidia G98M [GeForce G 103M]                                                             | 1         | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| 1 x Intel                                | 63        | 41.18%  |
| 1 x Nvidia                               | 25        | 16.34%  |
| 1 x AMD                                  | 17        | 11.11%  |
| Intel + Nvidia                           | 16        | 10.46%  |
| Other                                    | 10        | 6.54%   |
| 2 x Intel                                | 6         | 3.92%   |
| 1 x Matrox                               | 6         | 3.92%   |
| Intel + AMD                              | 3         | 1.96%   |
| 2 x AMD                                  | 2         | 1.31%   |
| 1 x VMware                               | 2         | 1.31%   |
| 2 x Nvidia                               | 1         | 0.65%   |
| 1 x NVidia / SGS Thomson (Joint Venture) | 1         | 0.65%   |
| AMD + Nvidia                             | 1         | 0.65%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 117       | 76.47%  |
| Proprietary | 25        | 16.34%  |
| Unknown     | 11        | 7.19%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 125       | 81.7%   |
| 7.01-8.0   | 6         | 3.92%   |
| 1.01-2.0   | 6         | 3.92%   |
| 0.01-0.5   | 5         | 3.27%   |
| 3.01-4.0   | 4         | 2.61%   |
| 0.51-1.0   | 3         | 1.96%   |
| 5.01-6.0   | 2         | 1.31%   |
| 2.01-3.0   | 1         | 0.65%   |
| 8.01-16.0  | 1         | 0.65%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 15        | 14.85%  |
| BOE                  | 11        | 10.89%  |
| Samsung Electronics  | 10        | 9.9%    |
| LG Display           | 10        | 9.9%    |
| Goldstar             | 9         | 8.91%   |
| Dell                 | 6         | 5.94%   |
| Chimei Innolux       | 5         | 4.95%   |
| Ancor Communications | 5         | 4.95%   |
| Sharp                | 4         | 3.96%   |
| Hewlett-Packard      | 4         | 3.96%   |
| AOC                  | 4         | 3.96%   |
| InfoVision           | 3         | 2.97%   |
| Sceptre Tech         | 2         | 1.98%   |
| Iiyama               | 2         | 1.98%   |
| BenQ                 | 2         | 1.98%   |
| Acer                 | 2         | 1.98%   |
| LG Electronics       | 1         | 0.99%   |
| Lenovo               | 1         | 0.99%   |
| HannStar             | 1         | 0.99%   |
| Eizo                 | 1         | 0.99%   |
| CPT                  | 1         | 0.99%   |
| CKL                  | 1         | 0.99%   |
| Apple                | 1         | 0.99%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP14D1 1920x1200 340x210mm 15.7-inch                | 1         | 0.99%   |
| Sharp LCD Monitor SHP1476 3840x2160 350x190mm 15.7-inch                | 1         | 0.99%   |
| Sharp LCD Monitor SHP1451 1920x1080 280x160mm 12.7-inch                | 1         | 0.99%   |
| Sharp LCD Monitor SHP143E 3840x2160 350x190mm 15.7-inch                | 1         | 0.99%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch         | 1         | 0.99%   |
| Sceptre Tech Sceptre E20 SPT080D 1600x900 410x280mm 19.5-inch          | 1         | 0.99%   |
| Samsung Electronics SyncMaster SAM027D 1680x1050 430x270mm 20.0-inch   | 1         | 0.99%   |
| Samsung Electronics SyncMaster SAM0236 2560x1600 640x400mm 29.7-inch   | 1         | 0.99%   |
| Samsung Electronics SyncMaster SAM01BB 1280x1024 380x300mm 19.1-inch   | 1         | 0.99%   |
| Samsung Electronics S24E510C SAM0C61 1920x1080 520x300mm 23.6-inch     | 1         | 0.99%   |
| Samsung Electronics LCD Monitor SEC3849 1366x768 310x170mm 13.9-inch   | 1         | 0.99%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 340x190mm 15.3-inch  | 1         | 0.99%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch   | 1         | 0.99%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 340x190mm 15.3-inch   | 1         | 0.99%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1210x680mm 54.6-inch | 1         | 0.99%   |
| Samsung Electronics LCD Monitor SAM0D4F 1920x1080 1020x570mm 46.0-inch | 1         | 0.99%   |
| LG Electronics LCD Monitor LG Ultra HD 3840x2160                       | 1         | 0.99%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch           | 1         | 0.99%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch           | 1         | 0.99%   |
| LG Display LCD Monitor LGD03D3 1600x900 310x170mm 13.9-inch            | 1         | 0.99%   |
| LG Display LCD Monitor LGD03AB 1366x768 340x190mm 15.3-inch            | 1         | 0.99%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch            | 1         | 0.99%   |
| LG Display LCD Monitor LGD032C 1920x1080 340x190mm 15.3-inch           | 1         | 0.99%   |
| LG Display LCD Monitor LGD0314 1366x768 290x160mm 13.0-inch            | 1         | 0.99%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch            | 1         | 0.99%   |
| LG Display LCD Monitor LGD02D9 1920x1080 340x190mm 15.3-inch           | 1         | 0.99%   |
| LG Display LCD Monitor LGD0214 1600x900 350x190mm 15.7-inch            | 1         | 0.99%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch                | 1         | 0.99%   |
| InfoVision LCD Monitor IVO0536 1920x1080 290x170mm 13.2-inch           | 1         | 0.99%   |
| InfoVision LCD Monitor IVO0533 1366x768 290x160mm 13.0-inch            | 1         | 0.99%   |
| InfoVision LCD Monitor IVO04E5 1366x768 280x160mm 12.7-inch            | 1         | 0.99%   |
| Iiyama PLX2483H IVM6114 1920x1080 530x300mm 24.0-inch                  | 1         | 0.99%   |
| Iiyama PL2209HD IVM560B 1920x1080 480x270mm 21.7-inch                  | 1         | 0.99%   |
| Hewlett-Packard Z24nf HWP3209 1920x1080 530x300mm 24.0-inch            | 1         | 0.99%   |
| Hewlett-Packard LCD Monitor HPN401E 1920x1080 480x270mm 21.7-inch      | 1         | 0.99%   |
| Hewlett-Packard HPQ 800 AIO HWP1080 1920x1080 510x290mm 23.1-inch      | 1         | 0.99%   |
| Hewlett-Packard 24xw HWP3256 1920x1080 530x300mm 24.0-inch             | 1         | 0.99%   |
| HannStar HSD100IFW1 HSD03E9 1024x600 220x130mm 10.1-inch               | 1         | 0.99%   |
| Goldstar W2246 GSM5784 1920x1080 480x270mm 21.7-inch                   | 1         | 0.99%   |
| Goldstar W2052 GSM4E88 1680x1050 470x300mm 22.0-inch                   | 1         | 0.99%   |
| Goldstar LG ULTRAWIDE GSM5AFB 2560x1080 800x340mm 34.2-inch            | 1         | 0.99%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch             | 1         | 0.99%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch             | 1         | 0.99%   |
| Goldstar LG TV GSMC0A0 3840x2160                                       | 1         | 0.99%   |
| Goldstar LG FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch              | 1         | 0.99%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 600x340mm 27.2-inch                 | 1         | 0.99%   |
| Goldstar 22EA53 GSM59A4 1920x1080 480x270mm 21.7-inch                  | 1         | 0.99%   |
| Eizo CS2420 ENC2741 1920x1200 520x330mm 24.2-inch                      | 1         | 0.99%   |
| Dell U2412M DELA07B 1920x1200 520x320mm 24.0-inch                      | 1         | 0.99%   |
| Dell SE2717H/HX DELD0A1 1920x1080 600x340mm 27.2-inch                  | 1         | 0.99%   |
| Dell S2340M DELD05A 1920x1080 510x290mm 23.1-inch                      | 1         | 0.99%   |
| Dell P2415Q DELA0BE 3840x2160 530x300mm 24.0-inch                      | 1         | 0.99%   |
| Dell LCD Monitor U3011 2560x1600                                       | 1         | 0.99%   |
| Dell E1916H DELF065 1366x768 410x230mm 18.5-inch                       | 1         | 0.99%   |
| CPT LCD Monitor CPT04C4 1024x600 230x140mm 10.6-inch                   | 1         | 0.99%   |
| CKL LCD Monitor CKL0001 1920x1200 1150x650mm 52.0-inch                 | 1         | 0.99%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 340x190mm 15.3-inch        | 1         | 0.99%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 340x190mm 15.3-inch       | 1         | 0.99%   |
| Chimei Innolux LCD Monitor CMN1509 1920x1080 340x190mm 15.3-inch       | 1         | 0.99%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 310x170mm 13.9-inch       | 1         | 0.99%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 41        | 43.16%  |
| 1366x768 (WXGA)    | 18        | 18.95%  |
| 3840x2160 (4K)     | 10        | 10.53%  |
| 1920x1200 (WUXGA)  | 6         | 6.32%   |
| 1600x900 (HD+)     | 5         | 5.26%   |
| 1280x800 (WXGA)    | 4         | 4.21%   |
| 2560x1600          | 2         | 2.11%   |
| 2560x1440 (QHD)    | 2         | 2.11%   |
| 2560x1080          | 2         | 2.11%   |
| 1680x1050 (WSXGA+) | 2         | 2.11%   |
| 1024x600           | 2         | 2.11%   |
| 1280x1024 (SXGA)   | 1         | 1.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 26        | 26.53%  |
| 13      | 15        | 15.31%  |
| 24      | 9         | 9.18%   |
| 27      | 6         | 6.12%   |
| 21      | 6         | 6.12%   |
| 12      | 6         | 6.12%   |
| Unknown | 6         | 6.12%   |
| 23      | 4         | 4.08%   |
| 17      | 3         | 3.06%   |
| 29      | 2         | 2.04%   |
| 19      | 2         | 2.04%   |
| 14      | 2         | 2.04%   |
| 10      | 2         | 2.04%   |
| 54      | 1         | 1.02%   |
| 52      | 1         | 1.02%   |
| 46      | 1         | 1.02%   |
| 34      | 1         | 1.02%   |
| 32      | 1         | 1.02%   |
| 31      | 1         | 1.02%   |
| 22      | 1         | 1.02%   |
| 20      | 1         | 1.02%   |
| 18      | 1         | 1.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 37        | 38.54%  |
| 501-600     | 17        | 17.71%  |
| 201-300     | 14        | 14.58%  |
| 401-500     | 10        | 10.42%  |
| Unknown     | 6         | 6.25%   |
| 351-400     | 4         | 4.17%   |
| 601-700     | 3         | 3.13%   |
| 1001-1500   | 3         | 3.13%   |
| 701-800     | 2         | 2.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 71        | 78.02%  |
| 16/10   | 11        | 12.09%  |
| Unknown | 5         | 5.49%   |
| 21/9    | 2         | 2.2%    |
| 5/4     | 1         | 1.1%    |
| 3/2     | 1         | 1.1%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 91-100         | 21        | 21.65%  |
| 201-250        | 15        | 15.46%  |
| 81-90          | 14        | 14.43%  |
| 301-350        | 7         | 7.22%   |
| 61-70          | 6         | 6.19%   |
| Unknown        | 6         | 6.19%   |
| 351-500        | 4         | 4.12%   |
| 251-300        | 4         | 4.12%   |
| 101-110        | 4         | 4.12%   |
| 71-80          | 3         | 3.09%   |
| 151-200        | 3         | 3.09%   |
| 121-130        | 3         | 3.09%   |
| More than 1000 | 2         | 2.06%   |
| 41-50          | 2         | 2.06%   |
| 141-150        | 1         | 1.03%   |
| 111-120        | 1         | 1.03%   |
| 501-1000       | 1         | 1.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 28        | 28.87%  |
| 121-160       | 26        | 26.8%   |
| 51-100        | 25        | 25.77%  |
| 161-240       | 7         | 7.22%   |
| Unknown       | 6         | 6.19%   |
| More than 240 | 3         | 3.09%   |
| 1-50          | 2         | 2.06%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 76        | 49.67%  |
| 0     | 64        | 41.83%  |
| 2     | 11        | 7.19%   |
| 3     | 2         | 1.31%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 87        | 41.23%  |
| Realtek Semiconductor    | 66        | 31.28%  |
| Qualcomm Atheros         | 26        | 12.32%  |
| Broadcom                 | 16        | 7.58%   |
| Ralink Technology        | 2         | 0.95%   |
| Nvidia                   | 2         | 0.95%   |
| Mellanox Technologies    | 2         | 0.95%   |
| Marvell Technology Group | 2         | 0.95%   |
| Edimax Technology        | 2         | 0.95%   |
| Xiaomi                   | 1         | 0.47%   |
| Ralink                   | 1         | 0.47%   |
| Qualcomm                 | 1         | 0.47%   |
| NetGear                  | 1         | 0.47%   |
| IMC Networks             | 1         | 0.47%   |
| ADMtek                   | 1         | 0.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 50        | 19.46%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 9         | 3.5%    |
| Intel I211 Gigabit Network Connection                                         | 8         | 3.11%   |
| Intel Wireless 8265 / 8275                                                    | 7         | 2.72%   |
| Intel Wi-Fi 6 AX200                                                           | 7         | 2.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 7         | 2.72%   |
| Intel Wireless-AC 9260                                                        | 6         | 2.33%   |
| Intel Wireless 7265                                                           | 6         | 2.33%   |
| Intel 82574L Gigabit Network Connection                                       | 6         | 2.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 5         | 1.95%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 5         | 1.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 4         | 1.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 3         | 1.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 3         | 1.17%   |
| Intel Wireless 3160                                                           | 3         | 1.17%   |
| Intel I350 Gigabit Network Connection                                         | 3         | 1.17%   |
| Intel I210 Gigabit Network Connection                                         | 3         | 1.17%   |
| Intel Ethernet Connection I217-LM                                             | 3         | 1.17%   |
| Intel Ethernet Connection (4) I219-V                                          | 3         | 1.17%   |
| Intel Ethernet Connection (2) I219-V                                          | 3         | 1.17%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3         | 1.17%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 3         | 1.17%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 3         | 1.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 0.78%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 2         | 0.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 0.78%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 2         | 0.78%   |
| Realtek RTL8125 2.5GbE Controller                                             | 2         | 0.78%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 2         | 0.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2         | 0.78%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 2         | 0.78%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 2         | 0.78%   |
| Nvidia MCP79 Ethernet                                                         | 2         | 0.78%   |
| Mellanox MT27500 Family [ConnectX-3]                                          | 2         | 0.78%   |
| Intel Wireless 8260                                                           | 2         | 0.78%   |
| Intel Wireless 7260                                                           | 2         | 0.78%   |
| Intel Wireless 3165                                                           | 2         | 0.78%   |
| Intel Ethernet Connection (7) I219-V                                          | 2         | 0.78%   |
| Intel Ethernet Connection (3) I218-LM                                         | 2         | 0.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 2         | 0.78%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 2         | 0.78%   |
| Intel Centrino Ultimate-N 6300                                                | 2         | 0.78%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 2         | 0.78%   |
| Intel 82577LM Gigabit Network Connection                                      | 2         | 0.78%   |
| Intel 82577LC Gigabit Network Connection                                      | 2         | 0.78%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2         | 0.78%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                | 2         | 0.78%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                   | 2         | 0.78%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 0.78%   |
| Broadcom BCM43142 802.11b/g/n                                                 | 2         | 0.78%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                          | 1         | 0.39%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 1         | 0.39%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 1         | 0.39%   |
| Realtek Realtek Bluetooth Adapter                                             | 1         | 0.39%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 0.39%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1         | 0.39%   |
| Ralink RT2500 Wireless 802.11bg                                               | 1         | 0.39%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                        | 1         | 0.39%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1         | 0.39%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 1         | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 59        | 53.64%  |
| Qualcomm Atheros      | 20        | 18.18%  |
| Realtek Semiconductor | 13        | 11.82%  |
| Broadcom              | 11        | 10%     |
| Ralink Technology     | 2         | 1.82%   |
| Edimax Technology     | 2         | 1.82%   |
| Ralink                | 1         | 0.91%   |
| NetGear               | 1         | 0.91%   |
| IMC Networks          | 1         | 0.91%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 7         | 6.31%   |
| Intel Wi-Fi 6 AX200                                                     | 7         | 6.31%   |
| Intel Wireless-AC 9260                                                  | 6         | 5.41%   |
| Intel Wireless 7265                                                     | 6         | 5.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 4.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 4.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 3.6%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 2.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 2.7%    |
| Intel Wireless 3160                                                     | 3         | 2.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 2.7%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 2.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.8%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.8%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.8%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 1.8%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 2         | 1.8%    |
| Intel Wireless 8260                                                     | 2         | 1.8%    |
| Intel Wireless 7260                                                     | 2         | 1.8%    |
| Intel Wireless 3165                                                     | 2         | 1.8%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 1.8%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.8%    |
| Intel Centrino Ultimate-N 6300                                          | 2         | 1.8%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.8%    |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 2         | 1.8%    |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 2         | 1.8%    |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 1.8%    |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 1.8%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 1         | 0.9%    |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.9%    |
| Realtek Realtek Bluetooth Adapter                                       | 1         | 0.9%    |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.9%    |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.9%    |
| Ralink RT2500 Wireless 802.11bg                                         | 1         | 0.9%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.9%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.9%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter                        | 1         | 0.9%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.9%    |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]             | 1         | 0.9%    |
| Intel WiFi Link 5100                                                    | 1         | 0.9%    |
| Intel Ultimate N WiFi Link 5300                                         | 1         | 0.9%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 0.9%    |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 0.9%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 0.9%    |
| Intel Centrino Wireless-N 2230                                          | 1         | 0.9%    |
| Intel Centrino Advanced-N 6235                                          | 1         | 0.9%    |
| Intel Centrino Advanced-N 6200                                          | 1         | 0.9%    |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]                    | 1         | 0.9%    |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                      | 1         | 0.9%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 1         | 0.9%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 59        | 43.07%  |
| Intel                    | 56        | 40.88%  |
| Qualcomm Atheros         | 8         | 5.84%   |
| Broadcom                 | 7         | 5.11%   |
| Nvidia                   | 2         | 1.46%   |
| Marvell Technology Group | 2         | 1.46%   |
| Xiaomi                   | 1         | 0.73%   |
| Qualcomm                 | 1         | 0.73%   |
| ADMtek                   | 1         | 0.73%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 50        | 35.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 9         | 6.34%   |
| Intel I211 Gigabit Network Connection                                         | 8         | 5.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 7         | 4.93%   |
| Intel 82574L Gigabit Network Connection                                       | 6         | 4.23%   |
| Intel I350 Gigabit Network Connection                                         | 3         | 2.11%   |
| Intel I210 Gigabit Network Connection                                         | 3         | 2.11%   |
| Intel Ethernet Connection I217-LM                                             | 3         | 2.11%   |
| Intel Ethernet Connection (4) I219-V                                          | 3         | 2.11%   |
| Intel Ethernet Connection (2) I219-V                                          | 3         | 2.11%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3         | 2.11%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 2         | 1.41%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 2         | 1.41%   |
| Nvidia MCP79 Ethernet                                                         | 2         | 1.41%   |
| Intel Ethernet Connection (7) I219-V                                          | 2         | 1.41%   |
| Intel Ethernet Connection (3) I218-LM                                         | 2         | 1.41%   |
| Intel 82577LM Gigabit Network Connection                                      | 2         | 1.41%   |
| Intel 82577LC Gigabit Network Connection                                      | 2         | 1.41%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2         | 1.41%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                          | 1         | 0.7%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                        | 1         | 0.7%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1         | 0.7%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 1         | 0.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1         | 0.7%    |
| Qualcomm ALCATEL Composite RNDIS Interface                                    | 1         | 0.7%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1         | 0.7%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                          | 1         | 0.7%    |
| Marvell Group 88E8001 Gigabit Ethernet Controller                             | 1         | 0.7%    |
| Intel Ethernet Controller I225-V                                              | 1         | 0.7%    |
| Intel Ethernet Connection I219-LM                                             | 1         | 0.7%    |
| Intel Ethernet Connection (6) I219-LM                                         | 1         | 0.7%    |
| Intel Ethernet Connection (4) I219-LM                                         | 1         | 0.7%    |
| Intel Ethernet Connection (3) I219-LM                                         | 1         | 0.7%    |
| Intel Ethernet Connection (3) I218-V                                          | 1         | 0.7%    |
| Intel Ethernet Connection (2) I218-V                                          | 1         | 0.7%    |
| Intel Ethernet Connection (10) I219-LM                                        | 1         | 0.7%    |
| Intel 82573L Gigabit Ethernet Controller                                      | 1         | 0.7%    |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 1         | 0.7%    |
| Intel 82567LM Gigabit Network Connection                                      | 1         | 0.7%    |
| Broadcom NetXtreme II BCM57711E 10-Gigabit PCIe                               | 1         | 0.7%    |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 1         | 0.7%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 1         | 0.7%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 1         | 0.7%    |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                       | 1         | 0.7%    |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 1         | 0.7%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 1         | 0.7%    |
| ADMtek NC100 Network Everywhere Fast Ethernet 10/100                          | 1         | 0.7%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 131       | 55.27%  |
| WiFi     | 102       | 43.04%  |
| Unknown  | 4         | 1.69%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 120       | 62.5%   |
| WiFi     | 72        | 37.5%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 93        | 60.78%  |
| 1     | 40        | 26.14%  |
| 0     | 10        | 6.54%   |
| 4     | 5         | 3.27%   |
| 3     | 5         | 3.27%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 132       | 85.71%  |
| Yes  | 22        | 14.29%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 41        | 58.57%  |
| Qualcomm Atheros Communications | 7         | 10%     |
| Broadcom                        | 5         | 7.14%   |
| Realtek Semiconductor           | 4         | 5.71%   |
| Apple                           | 4         | 5.71%   |
| IMC Networks                    | 2         | 2.86%   |
| ASUSTek Computer                | 2         | 2.86%   |
| VMware                          | 1         | 1.43%   |
| Lite-On Technology              | 1         | 1.43%   |
| Foxconn / Hon Hai               | 1         | 1.43%   |
| Dell                            | 1         | 1.43%   |
| Cambridge Silicon Radio         | 1         | 1.43%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 16        | 22.86%  |
| Intel AX200 Bluetooth                                       | 7         | 10%     |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 6         | 8.57%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 4         | 5.71%   |
| Intel AX201 Bluetooth                                       | 4         | 5.71%   |
| Apple Bluetooth Host Controller                             | 3         | 4.29%   |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 2.86%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 2         | 2.86%   |
| Intel Wireless-AC 3168 Bluetooth                            | 2         | 2.86%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 2.86%   |
| VMware Virtual Bluetooth Adapter                            | 1         | 1.43%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 1         | 1.43%   |
| Realtek  Bluetooth Adapter                                  | 1         | 1.43%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 1.43%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 1.43%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 1.43%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 1.43%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 1.43%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 1.43%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 1.43%   |
| IMC Networks Bluetooth Module                               | 1         | 1.43%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 1         | 1.43%   |
| Dell DW375 Bluetooth Module                                 | 1         | 1.43%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 1         | 1.43%   |
| Broadcom BCM43142 Bluetooth 4.0                             | 1         | 1.43%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 1         | 1.43%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 1         | 1.43%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 1         | 1.43%   |
| Broadcom BCM2045 Bluetooth                                  | 1         | 1.43%   |
| ASUS BT-270 Bluetooth Adapter                               | 1         | 1.43%   |
| ASUS BT-253 Bluetooth Adapter                               | 1         | 1.43%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1         | 1.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 101       | 59.76%  |
| AMD                                  | 29        | 17.16%  |
| Nvidia                               | 28        | 16.57%  |
| VMware                               | 1         | 0.59%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.59%   |
| Texas Instruments                    | 1         | 0.59%   |
| SteelSeries ApS                      | 1         | 0.59%   |
| Realtek Semiconductor                | 1         | 0.59%   |
| Lenovo                               | 1         | 0.59%   |
| Ensoniq                              | 1         | 0.59%   |
| Creative Labs                        | 1         | 0.59%   |
| Corsair                              | 1         | 0.59%   |
| C-Media Electronics                  | 1         | 0.59%   |
| BEHRINGER International              | 1         | 0.59%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                                     | Computers | Percent |
|-----------------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                           | 15        | 7.43%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                                | 10        | 4.95%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                                       | 9         | 4.46%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                                       | 8         | 3.96%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                                  | 8         | 3.96%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                                       | 8         | 3.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                          | 7         | 3.47%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                                   | 7         | 3.47%   |
| Intel Broadwell-U Audio Controller                                                                        | 7         | 3.47%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                           | 6         | 2.97%   |
| AMD Starship/Matisse HD Audio Controller                                                                  | 6         | 2.97%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                                | 6         | 2.97%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                                       | 5         | 2.48%   |
| Intel Haswell-ULT HD Audio Controller                                                                     | 4         | 1.98%   |
| Intel Comet Lake PCH-LP cAVS                                                                              | 4         | 1.98%   |
| Intel Cannon Point-LP High Definition Audio Controller                                                    | 4         | 1.98%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                            | 4         | 1.98%   |
| Intel 8 Series HD Audio Controller                                                                        | 4         | 1.98%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                            | 3         | 1.49%   |
| Nvidia High Definition Audio Controller                                                                   | 3         | 1.49%   |
| Nvidia GP108 High Definition Audio Controller                                                             | 3         | 1.49%   |
| Nvidia GF119 HDMI Audio Controller                                                                        | 3         | 1.49%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                                   | 3         | 1.49%   |
| Intel Comet Lake PCH cAVS                                                                                 | 3         | 1.49%   |
| Intel Cannon Lake PCH cAVS                                                                                | 3         | 1.49%   |
| AMD Renoir Radeon High Definition Audio Controller                                                        | 3         | 1.49%   |
| AMD FCH Azalia Controller                                                                                 | 3         | 1.49%   |
| Nvidia TU116 High Definition Audio Controller                                                             | 2         | 0.99%   |
| Nvidia TU104 HD Audio Controller                                                                          | 2         | 0.99%   |
| Nvidia MCP79 High Definition Audio                                                                        | 2         | 0.99%   |
| Nvidia GT216 HDMI Audio Controller                                                                        | 2         | 0.99%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                                | 2         | 0.99%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                         | 2         | 0.99%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                          | 2         | 0.99%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                                                | 2         | 0.99%   |
| AMD High Definition Audio Controller                                                                      | 2         | 0.99%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                          | 2         | 0.99%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                              | 2         | 0.99%   |
| VMware HD Audio Controller                                                                                | 1         | 0.5%    |
| Thesycon Systemsoftware & Consulting Topping DX3 Pro Audio Control                                        | 1         | 0.5%    |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                         | 1         | 0.5%    |
| SteelSeries ApS Arctis Pro Wireless Arctis Pro Wireless Chat Arctis Pro Wireless Game Arctis Pro Wireless | 1         | 0.5%    |
| Realtek Semiconductor TX-384Khz Hifi Type-C Audio                                                         | 1         | 0.5%    |
| Nvidia GP107GL High Definition Audio Controller                                                           | 1         | 0.5%    |
| Nvidia GP106 High Definition Audio Controller                                                             | 1         | 0.5%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                                     | 1         | 0.5%    |
| Nvidia GF116 High Definition Audio Controller                                                             | 1         | 0.5%    |
| Nvidia GF110 High Definition Audio Controller                                                             | 1         | 0.5%    |
| Nvidia GF108 High Definition Audio Controller                                                             | 1         | 0.5%    |
| Nvidia GA104 High Definition Audio Controller                                                             | 1         | 0.5%    |
| Nvidia GA102 High Definition Audio Controller                                                             | 1         | 0.5%    |
| Lenovo Lenovo ThinkPad OneLink Pro Dock                                                                   | 1         | 0.5%    |
| Intel Lewisburg MROM 0                                                                                    | 1         | 0.5%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                                 | 1         | 0.5%    |
| Intel CM238 HD Audio Controller                                                                           | 1         | 0.5%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                              | 1         | 0.5%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                         | 1         | 0.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller         | 1         | 0.5%    |
| Intel 200 Series PCH HD Audio                                                                             | 1         | 0.5%    |
| Ensoniq 5880B / Creative Labs CT5880                                                                      | 1         | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 33        | 21.15%  |
| SK Hynix            | 27        | 17.31%  |
| Kingston            | 23        | 14.74%  |
| Unknown             | 17        | 10.9%   |
| Crucial             | 15        | 9.62%   |
| Micron Technology   | 12        | 7.69%   |
| Corsair             | 10        | 6.41%   |
| Ramaxel Technology  | 4         | 2.56%   |
| G.Skill             | 3         | 1.92%   |
| Team                | 2         | 1.28%   |
| Smart               | 2         | 1.28%   |
| Transcend           | 1         | 0.64%   |
| Silicon Power       | 1         | 0.64%   |
| Qimonda             | 1         | 0.64%   |
| PUSKILL             | 1         | 0.64%   |
| Neo Forza           | 1         | 0.64%   |
| GOODRAM             | 1         | 0.64%   |
| AMD                 | 1         | 0.64%   |
| A-DATA Technology   | 1         | 0.64%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 3         | 1.82%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s  | 3         | 1.82%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s   | 3         | 1.82%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s              | 2         | 1.21%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s  | 2         | 1.21%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 2         | 1.21%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 2         | 1.21%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s   | 2         | 1.21%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s   | 2         | 1.21%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s   | 2         | 1.21%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s   | 2         | 1.21%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s | 2         | 1.21%   |
| Crucial RAM CT8G4SFS824A.C8BD1 8GB SODIMM DDR4 2400MT/s | 2         | 1.21%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s   | 2         | 1.21%   |
| Unknown SODIMM 1GB SODIMM DDR2 533MT/s                  | 1         | 0.61%   |
| Unknown RAM Module 8GB SODIMM DDR4 2133MT/s             | 1         | 0.61%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s               | 1         | 0.61%   |
| Unknown RAM Module 8GB DIMM DDR3 1067MT/s               | 1         | 0.61%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s             | 1         | 0.61%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s               | 1         | 0.61%   |
| Unknown RAM Module 4GB DIMM 400MT/s                     | 1         | 0.61%   |
| Unknown RAM Module 2GB SODIMM 667MT/s                   | 1         | 0.61%   |
| Unknown RAM Module 2GB DIMM SDRAM                       | 1         | 0.61%   |
| Unknown RAM Module 2GB DIMM DDR3 1332MT/s               | 1         | 0.61%   |
| Unknown RAM Module 2GB DIMM DDR 800MT/s                 | 1         | 0.61%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                | 1         | 0.61%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                | 1         | 0.61%   |
| Unknown RAM Module 16GB DIMM DDR4 2133MT/s              | 1         | 0.61%   |
| Unknown RAM 2G-08-10-12-1333 2GB DIMM DDR3 1333MT/s     | 1         | 0.61%   |
| Transcend RAM TS2GSH64V1B 16GB SODIMM DDR4 2133MT/s     | 1         | 0.61%   |
| Team RAM TEAMGROUP-UD4-3200 32GB DIMM DDR4 3200MT/s     | 1         | 0.61%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s     | 1         | 0.61%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s   | 1         | 0.61%   |
| Smart RAM SF464128CKHIWDFSEG 4GB SODIMM DDR4 2133MT/s   | 1         | 0.61%   |
| SK Hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s    | 1         | 0.61%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s            | 1         | 0.61%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1067MT/s            | 1         | 0.61%   |
| SK Hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s    | 1         | 0.61%   |
| SK Hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 1         | 0.61%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 1         | 0.61%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s  | 1         | 0.61%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s  | 1         | 0.61%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s  | 1         | 0.61%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s  | 1         | 0.61%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s  | 1         | 0.61%   |
| SK Hynix RAM HMA82GU6AFR8N-UH 16GB DIMM DDR4 2400MT/s   | 1         | 0.61%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s | 1         | 0.61%   |
| SK Hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s | 1         | 0.61%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s  | 1         | 0.61%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s  | 1         | 0.61%   |
| Silicon Power RAM DCLT4GN128O 4GB DIMM DDR3 1333MT/s    | 1         | 0.61%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s             | 1         | 0.61%   |
| Samsung RAM Module 2GB SODIMM DDR3 1067MT/s             | 1         | 0.61%   |
| Samsung RAM Module 16GB DIMM DDR3 1600MT/s              | 1         | 0.61%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 1067MT/s   | 1         | 0.61%   |
| Samsung RAM M471B5673DZ1-CF8 2GB SODIMM DDR3 1066MT/s   | 1         | 0.61%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s   | 1         | 0.61%   |
| Samsung RAM M471B5273CM0-CH9 4GB SODIMM DDR3 1333MT/s   | 1         | 0.61%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s   | 1         | 0.61%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1333MT/s   | 1         | 0.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 63        | 45%     |
| DDR4    | 61        | 43.57%  |
| DDR2    | 6         | 4.29%   |
| DDR     | 4         | 2.86%   |
| LPDDR3  | 3         | 2.14%   |
| Unknown | 2         | 1.43%   |
| SDRAM   | 1         | 0.71%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 86        | 61.87%  |
| DIMM         | 51        | 36.69%  |
| Row Of Chips | 2         | 1.44%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 54        | 36.24%  |
| 4096  | 41        | 27.52%  |
| 16384 | 23        | 15.44%  |
| 2048  | 19        | 12.75%  |
| 32768 | 8         | 5.37%   |
| 1024  | 4         | 2.68%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 42        | 28.38%  |
| 2667    | 16        | 10.81%  |
| 2400    | 16        | 10.81%  |
| 2133    | 16        | 10.81%  |
| 1333    | 14        | 9.46%   |
| 3200    | 11        | 7.43%   |
| 1067    | 7         | 4.73%   |
| 800     | 4         | 2.7%    |
| 667     | 4         | 2.7%    |
| 3000    | 3         | 2.03%   |
| 2933    | 3         | 2.03%   |
| 1334    | 3         | 2.03%   |
| 533     | 2         | 1.35%   |
| 3600    | 1         | 0.68%   |
| 2666    | 1         | 0.68%   |
| 1332    | 1         | 0.68%   |
| 1066    | 1         | 0.68%   |
| 975     | 1         | 0.68%   |
| 400     | 1         | 0.68%   |
| Unknown | 1         | 0.68%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 50%     |
| Canon       | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model               | Computers | Percent |
|---------------------|-----------|---------|
| Seiko Epson Printer | 1         | 50%     |
| Canon LBP2900       | 1         | 50%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 110 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 18        | 28.57%  |
| IMC Networks                  | 8         | 12.7%   |
| Realtek Semiconductor         | 7         | 11.11%  |
| Microdia                      | 7         | 11.11%  |
| Sunplus Innovation Technology | 6         | 9.52%   |
| Suyin                         | 4         | 6.35%   |
| Logitech                      | 3         | 4.76%   |
| Syntek                        | 2         | 3.17%   |
| Acer                          | 2         | 3.17%   |
| Z-Star Microelectronics       | 1         | 1.59%   |
| Valve Software                | 1         | 1.59%   |
| Silicon Motion                | 1         | 1.59%   |
| Quanta                        | 1         | 1.59%   |
| Lite-On Technology            | 1         | 1.59%   |
| Lenovo                        | 1         | 1.59%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Chicony Integrated Camera                 | 4         | 6.35%   |
| IMC Networks Integrated Camera            | 3         | 4.76%   |
| Sunplus Integrated_Webcam_HD              | 2         | 3.17%   |
| Realtek Integrated_Webcam_HD              | 2         | 3.17%   |
| Microdia Integrated Webcam                | 2         | 3.17%   |
| Chicony Lenovo Integrated Camera (0.3MP)  | 2         | 3.17%   |
| Chicony HD WebCam                         | 2         | 3.17%   |
| Chicony Chicony USB2.0 Camera             | 2         | 3.17%   |
| Z-Star Namuga 1.3M Webcam                 | 1         | 1.59%   |
| Valve Software 3D Camera                  | 1         | 1.59%   |
| Syntek Lenovo EasyCamera                  | 1         | 1.59%   |
| Syntek EasyCamera                         | 1         | 1.59%   |
| Suyin Integrated Camera                   | 1         | 1.59%   |
| Suyin HP Webcam-101                       | 1         | 1.59%   |
| Suyin Asus Integrated Webcam              | 1         | 1.59%   |
| Suyin Acer Crystal Eye webcam             | 1         | 1.59%   |
| Sunplus Laptop_Integrated_Webcam_FHD      | 1         | 1.59%   |
| Sunplus Laptop Integrated Webcam HD       | 1         | 1.59%   |
| Sunplus Integrated Camera                 | 1         | 1.59%   |
| Sunplus Dell HD Webcam                    | 1         | 1.59%   |
| Silicon Motion Web Camera                 | 1         | 1.59%   |
| Realtek USB 2 Webcam                      | 1         | 1.59%   |
| Realtek Realtek PC Camera                 | 1         | 1.59%   |
| Realtek Lenovo EasyCamera                 | 1         | 1.59%   |
| Realtek Integrated Webcam HD              | 1         | 1.59%   |
| Realtek HP 2.0MP High Definition Webcam   | 1         | 1.59%   |
| Quanta HD Webcam                          | 1         | 1.59%   |
| Microdia Laptop_Integrated_Webcam_2M      | 1         | 1.59%   |
| Microdia Laptop_Integrated_Webcam_0.3M    | 1         | 1.59%   |
| Microdia Integrated_Webcam_HD             | 1         | 1.59%   |
| Microdia Integrated Webcam HD             | 1         | 1.59%   |
| Microdia Dell Laptop Integrated Webcam HD | 1         | 1.59%   |
| Logitech Webcam C270                      | 1         | 1.59%   |
| Logitech HD Webcam C615                   | 1         | 1.59%   |
| Logitech HD Pro Webcam C920               | 1         | 1.59%   |
| Lite-On HP TrueVision HD Camera           | 1         | 1.59%   |
| Lenovo Integrated Webcam [R5U877]         | 1         | 1.59%   |
| IMC Networks UVC VGA Webcam               | 1         | 1.59%   |
| IMC Networks USB2.0 UVC HD Webcam         | 1         | 1.59%   |
| IMC Networks USB2.0 UVC 2M WebCam         | 1         | 1.59%   |
| IMC Networks USB2.0 HD UVC WebCam         | 1         | 1.59%   |
| IMC Networks EasyCamera                   | 1         | 1.59%   |
| Chicony USB2.0 HD UVC WebCam              | 1         | 1.59%   |
| Chicony TOSHIBA Web Camera - HD           | 1         | 1.59%   |
| Chicony Realtek DMFT - RGB                | 1         | 1.59%   |
| Chicony Lenovo EasyCamera                 | 1         | 1.59%   |
| Chicony HP Wide Vision HD Camera          | 1         | 1.59%   |
| Chicony HP Universal Camera               | 1         | 1.59%   |
| Chicony HP TrueVision HD Camera           | 1         | 1.59%   |
| Chicony Chicony USB 2.0 Camera            | 1         | 1.59%   |
| Acer Lenovo EasyCamera                    | 1         | 1.59%   |
| Acer Integrated Camera                    | 1         | 1.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 25%     |
| Synaptics                  | 3         | 25%     |
| Shenzhen Goodix Technology | 3         | 25%     |
| Upek                       | 1         | 8.33%   |
| Broadcom                   | 1         | 8.33%   |
| AuthenTec                  | 1         | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                                              | 2         | 16.67%  |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 1         | 8.33%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 1         | 8.33%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 1         | 8.33%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 1         | 8.33%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 1         | 8.33%   |
| Shenzhen Goodix  FingerPrint Device                                          | 1         | 8.33%   |
| Shenzhen Goodix Fingerprint Reader                                           | 1         | 8.33%   |
| Shenzhen Goodix FingerPrint                                                  | 1         | 8.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 8.33%   |
| AuthenTec AuthenTec Inc. AES1660                                             | 1         | 8.33%   |

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
| 1     | 56        | 36.6%   |
| 0     | 42        | 27.45%  |
| 2     | 32        | 20.92%  |
| 3     | 16        | 10.46%  |
| 4     | 5         | 3.27%   |
| 6     | 1         | 0.65%   |
| 5     | 1         | 0.65%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 86        | 45.74%  |
| Net/wireless             | 33        | 17.55%  |
| Bluetooth                | 21        | 11.17%  |
| Card reader              | 14        | 7.45%   |
| Firewire controller      | 13        | 6.91%   |
| Fingerprint reader       | 12        | 6.38%   |
| Sound                    | 2         | 1.06%   |
| Network                  | 2         | 1.06%   |
| Net/ethernet             | 2         | 1.06%   |
| Storage/nvme             | 1         | 0.53%   |
| Storage/ide              | 1         | 0.53%   |
| Storage                  | 1         | 0.53%   |

