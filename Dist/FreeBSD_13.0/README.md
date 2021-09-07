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
| Unknown       | Unknown                     | Desktop     | [0c708350cd](https://bsd-hardware.info/?probe=0c708350cd) | Apr 17, 2021 |
| Unknown       | Unknown                     | Desktop     | [7b295345e6](https://bsd-hardware.info/?probe=7b295345e6) | Apr 17, 2021 |
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

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 127       | 90.71%  |
| arm64 | 8         | 5.71%   |
| i386  | 4         | 2.86%   |
| arm   | 1         | 0.71%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 42        | 30%     |
| XFCE          | 24        | 17.14%  |
| KDE5          | 24        | 17.14%  |
| GNOME         | 13        | 9.29%   |
| TWM           | 12        | 8.57%   |
| MATE          | 8         | 5.71%   |
| Openbox       | 4         | 2.86%   |
| i3            | 4         | 2.86%   |
| LXQt          | 2         | 1.43%   |
| Enlightenment | 2         | 1.43%   |
| AwesomeWM     | 2         | 1.43%   |
| GNUstep       | 1         | 0.71%   |
| Fluxbox       | 1         | 0.71%   |
| Cinnamon      | 1         | 0.71%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 97        | 69.29%  |
| Console | 42        | 30%     |
| Wayland | 1         | 0.71%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 79        | 56.43%  |
| SDDM    | 25        | 17.86%  |
| SLiM    | 12        | 8.57%   |
| GDM     | 11        | 7.86%   |
| LightDM | 8         | 5.71%   |
| XDM     | 4         | 2.86%   |
| Ly      | 1         | 0.71%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| C               | 95        | 67.86%  |
| en_US           | 12        | 8.57%   |
| Unknown         | 9         | 6.43%   |
| ru_RU           | 5         | 3.57%   |
| de_DE           | 5         | 3.57%   |
| fr_FR           | 4         | 2.86%   |
| nb_NO           | 3         | 2.14%   |
| en_GB           | 2         | 1.43%   |
| pt_PT           | 1         | 0.71%   |
| pl_PL           | 1         | 0.71%   |
| ja_JP           | 1         | 0.71%   |
| it_IT.ISO8859-1 | 1         | 0.71%   |
| es_ES           | 1         | 0.71%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 94        | 66.2%   |
| BIOS | 48        | 33.8%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 93        | 66.43%  |
| Ufs  | 47        | 33.57%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 126       | 90%     |
| MBR  | 14        | 10%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 25        | 17.86%  |
| Lenovo                  | 22        | 15.71%  |
| ASUSTek Computer        | 15        | 10.71%  |
| Hewlett-Packard         | 10        | 7.14%   |
| Gigabyte Technology     | 9         | 6.43%   |
| ASRock                  | 9         | 6.43%   |
| Unknown                 | 9         | 6.43%   |
| MSI                     | 6         | 4.29%   |
| Acer                    | 4         | 2.86%   |
| Toshiba                 | 3         | 2.14%   |
| Cisco Systems           | 3         | 2.14%   |
| Beckhoff Automation     | 3         | 2.14%   |
| Apple                   | 3         | 2.14%   |
| System76                | 2         | 1.43%   |
| Samsung Electronics     | 2         | 1.43%   |
| Raspberry Pi Foundation | 2         | 1.43%   |
| Pegatron                | 2         | 1.43%   |
| Notebook                | 2         | 1.43%   |
| Wistron                 | 1         | 0.71%   |
| Supermicro              | 1         | 0.71%   |
| Shuttle                 | 1         | 0.71%   |
| Medion                  | 1         | 0.71%   |
| Intel                   | 1         | 0.71%   |
| GVC                     | 1         | 0.71%   |
| Fujitsu                 | 1         | 0.71%   |
| EVGA                    | 1         | 0.71%   |
| Alienware               | 1         | 0.71%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 9         | 6.43%   |
| Cisco Systems UCSC-C240-M4L                | 2         | 1.43%   |
| Beckhoff Automation Industrial PC          | 2         | 1.43%   |
| ASUS TUF GAMING X570-PLUS                  | 2         | 1.43%   |
| ASUS All Series                            | 2         | 1.43%   |
| ASRock B450M Pro4                          | 2         | 1.43%   |
| Wistron ProLiant ML110 G6                  | 1         | 0.71%   |
| Toshiba TECRA M11                          | 1         | 0.71%   |
| Toshiba Satellite L50-C                    | 1         | 0.71%   |
| Toshiba PORTEGE X20W-D                     | 1         | 0.71%   |
| System76 Lemur Pro                         | 1         | 0.71%   |
| System76 Gazelle                           | 1         | 0.71%   |
| Supermicro X7SPA-HF                        | 1         | 0.71%   |
| Shuttle SH87R                              | 1         | 0.71%   |
| Samsung NC10                               | 1         | 0.71%   |
| Samsung 300E5M/300E5L                      | 1         | 0.71%   |
| RPi rpi                                    | 1         | 0.71%   |
| RPi Raspberry Pi                           | 1         | 0.71%   |
| Pegatron T12Ah                             | 1         | 0.71%   |
| Pegatron SAISHIAT2                         | 1         | 0.71%   |
| Notebook NL5xRU                            | 1         | 0.71%   |
| Notebook N7x0WU                            | 1         | 0.71%   |
| MSI MS-7C80                                | 1         | 0.71%   |
| MSI MS-7C02                                | 1         | 0.71%   |
| MSI MS-7B09                                | 1         | 0.71%   |
| MSI MS-7817                                | 1         | 0.71%   |
| MSI MS-7677                                | 1         | 0.71%   |
| MSI GL65 Leopard 10SFSK                    | 1         | 0.71%   |
| Medion MS-7616                             | 1         | 0.71%   |
| Lenovo Z51-70 80K6                         | 1         | 0.71%   |
| Lenovo ThinkStation P720 30BAS1HX00        | 1         | 0.71%   |
| Lenovo ThinkPad X380 Yoga 20LH000NPG       | 1         | 0.71%   |
| Lenovo ThinkPad X270 20HMS0NS00            | 1         | 0.71%   |
| Lenovo ThinkPad X270 20HMCTO1WW            | 1         | 0.71%   |
| Lenovo ThinkPad X230 2325A95               | 1         | 0.71%   |
| Lenovo ThinkPad X220 4291PU5               | 1         | 0.71%   |
| Lenovo ThinkPad X220 4291ON5               | 1         | 0.71%   |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9CTO1WW | 1         | 0.71%   |
| Lenovo ThinkPad T440p 20AW0049LL           | 1         | 0.71%   |
| Lenovo ThinkPad T420 4237A12               | 1         | 0.71%   |
| Lenovo ThinkPad T420 4236NHG               | 1         | 0.71%   |
| Lenovo ThinkPad T410 2516DCU               | 1         | 0.71%   |
| Lenovo ThinkPad S1 Yoga 12 20DKS0AA00      | 1         | 0.71%   |
| Lenovo ThinkPad P73 20QRCTO1WW             | 1         | 0.71%   |
| Lenovo ThinkPad Edge E320 1298RJ1          | 1         | 0.71%   |
| Lenovo ThinkPad E490 20N9001SBR            | 1         | 0.71%   |
| Lenovo ThinkPad E490 20N8CTO1WW            | 1         | 0.71%   |
| Lenovo ThinkPad E15 Gen 3 20YG006GGE       | 1         | 0.71%   |
| Lenovo ThinkPad E14 20RAS0F600             | 1         | 0.71%   |
| Lenovo Rescuer-15ISK 80RQ                  | 1         | 0.71%   |
| Lenovo G505 20240                          | 1         | 0.71%   |
| Intel NUC5i3RYB H41000-503                 | 1         | 0.71%   |
| HP Z220 CMT Workstation                    | 1         | 0.71%   |
| HP ProLiant MicroServer Gen8               | 1         | 0.71%   |
| HP ProLiant BL460c G6                      | 1         | 0.71%   |
| HP Pavilion Laptop 15-cc0xx                | 1         | 0.71%   |
| HP Laptop 17-by0xxx                        | 1         | 0.71%   |
| HP ENVY x2 Detachable PC 13                | 1         | 0.71%   |
| HP EliteOne 800 G1 AiO                     | 1         | 0.71%   |
| HP EliteBook 840 G3                        | 1         | 0.71%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo ThinkPad                | 18        | 12.86%  |
| Dell Latitude                  | 9         | 6.43%   |
| Unknown                        | 9         | 6.43%   |
| Dell Inspiron                  | 8         | 5.71%   |
| Dell Precision                 | 3         | 2.14%   |
| ASUS TUF                       | 3         | 2.14%   |
| HP ProLiant                    | 2         | 1.43%   |
| Gigabyte X570                  | 2         | 1.43%   |
| Dell Vostro                    | 2         | 1.43%   |
| Cisco Systems UCSC-C240-M4L    | 2         | 1.43%   |
| Beckhoff Automation Industrial | 2         | 1.43%   |
| ASUS All                       | 2         | 1.43%   |
| ASRock X570                    | 2         | 1.43%   |
| ASRock B450M                   | 2         | 1.43%   |
| Acer Aspire                    | 2         | 1.43%   |
| Wistron ProLiant               | 1         | 0.71%   |
| Toshiba TECRA                  | 1         | 0.71%   |
| Toshiba Satellite              | 1         | 0.71%   |
| Toshiba PORTEGE                | 1         | 0.71%   |
| System76 Lemur                 | 1         | 0.71%   |
| System76 Gazelle               | 1         | 0.71%   |
| Supermicro X7SPA-HF            | 1         | 0.71%   |
| Shuttle SH87R                  | 1         | 0.71%   |
| Samsung NC10                   | 1         | 0.71%   |
| Samsung 300E5M                 | 1         | 0.71%   |
| RPi rpi                        | 1         | 0.71%   |
| RPi Raspberry                  | 1         | 0.71%   |
| Pegatron T12Ah                 | 1         | 0.71%   |
| Pegatron SAISHIAT2             | 1         | 0.71%   |
| Notebook NL5xRU                | 1         | 0.71%   |
| Notebook N7x0WU                | 1         | 0.71%   |
| MSI MS-7C80                    | 1         | 0.71%   |
| MSI MS-7C02                    | 1         | 0.71%   |
| MSI MS-7B09                    | 1         | 0.71%   |
| MSI MS-7817                    | 1         | 0.71%   |
| MSI MS-7677                    | 1         | 0.71%   |
| MSI GL65                       | 1         | 0.71%   |
| Medion MS-7616                 | 1         | 0.71%   |
| Lenovo Z51-70                  | 1         | 0.71%   |
| Lenovo ThinkStation            | 1         | 0.71%   |
| Lenovo Rescuer-15ISK           | 1         | 0.71%   |
| Lenovo G505                    | 1         | 0.71%   |
| Intel NUC5i3RYB                | 1         | 0.71%   |
| HP Z220                        | 1         | 0.71%   |
| HP Pavilion                    | 1         | 0.71%   |
| HP Laptop                      | 1         | 0.71%   |
| HP ENVY                        | 1         | 0.71%   |
| HP EliteOne                    | 1         | 0.71%   |
| HP EliteBook                   | 1         | 0.71%   |
| HP Compaq                      | 1         | 0.71%   |
| HP All-in-One                  | 1         | 0.71%   |
| GVC EQUIUM                     | 1         | 0.71%   |
| Gigabyte X58A-UD5              | 1         | 0.71%   |
| Gigabyte X470                  | 1         | 0.71%   |
| Gigabyte H81M-S2PV             | 1         | 0.71%   |
| Gigabyte F2A75M-HD2            | 1         | 0.71%   |
| Gigabyte B85-HD3               | 1         | 0.71%   |
| Gigabyte B450M                 | 1         | 0.71%   |
| Gigabyte A320M-S2H             | 1         | 0.71%   |
| Fujitsu D3417-B2               | 1         | 0.71%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 28        | 20%     |
| 2019    | 21        | 15%     |
| 2018    | 16        | 11.43%  |
| 2021    | 10        | 7.14%   |
| 2012    | 10        | 7.14%   |
| 2015    | 9         | 6.43%   |
| 2013    | 8         | 5.71%   |
| Unknown | 8         | 5.71%   |
| 2016    | 6         | 4.29%   |
| 2011    | 6         | 4.29%   |
| 2014    | 4         | 2.86%   |
| 2008    | 4         | 2.86%   |
| 2017    | 3         | 2.14%   |
| 2010    | 3         | 2.14%   |
| 2009    | 3         | 2.14%   |
| 2007    | 1         | 0.71%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 66        | 47.14%  |
| Desktop        | 55        | 39.29%  |
| System on chip | 8         | 5.71%   |
| Server         | 5         | 3.57%   |
| All in one     | 3         | 2.14%   |
| Convertible    | 2         | 1.43%   |
| Mini pc        | 1         | 0.71%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 139       | 99.29%  |
| Yes  | 1         | 0.71%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 46        | 32.86%  |
| 16.01-24.0      | 26        | 18.57%  |
| 4.01-8.0        | 21        | 15%     |
| 32.01-64.0      | 18        | 12.86%  |
| 64.01-256.0     | 14        | 10%     |
| 2.01-3.0        | 4         | 2.86%   |
| 3.01-4.0        | 3         | 2.14%   |
| 24.01-32.0      | 3         | 2.14%   |
| 0.51-1.0        | 3         | 2.14%   |
| More than 256.0 | 1         | 0.71%   |
| 0.01-0.5        | 1         | 0.71%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 63        | 44.68%  |
| 0.51-1.0   | 37        | 26.24%  |
| 1.01-2.0   | 20        | 14.18%  |
| 3.01-4.0   | 6         | 4.26%   |
| 2.01-3.0   | 4         | 2.84%   |
| 4.01-8.0   | 3         | 2.13%   |
| 16.01-24.0 | 3         | 2.13%   |
| 0          | 3         | 2.13%   |
| 24.01-32.0 | 1         | 0.71%   |
| 8.01-16.0  | 1         | 0.71%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 74        | 52.11%  |
| 2      | 24        | 16.9%   |
| 3      | 14        | 9.86%   |
| 0      | 9         | 6.34%   |
| 4      | 6         | 4.23%   |
| 5      | 4         | 2.82%   |
| 7      | 3         | 2.11%   |
| 6      | 3         | 2.11%   |
| 12     | 2         | 1.41%   |
| 14     | 1         | 0.7%    |
| 13     | 1         | 0.7%    |
| 9      | 1         | 0.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 97        | 68.79%  |
| Yes       | 44        | 31.21%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 121       | 86.43%  |
| No        | 19        | 13.57%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 92        | 65.71%  |
| No        | 48        | 34.29%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 77        | 55%     |
| Yes       | 63        | 45%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 40        | 28.57%  |
| Germany     | 14        | 10%     |
| Russia      | 13        | 9.29%   |
| UK          | 9         | 6.43%   |
| Netherlands | 7         | 5%      |
| France      | 5         | 3.57%   |
| Brazil      | 4         | 2.86%   |
| Switzerland | 3         | 2.14%   |
| Ukraine     | 2         | 1.43%   |
| Thailand    | 2         | 1.43%   |
| Spain       | 2         | 1.43%   |
| Poland      | 2         | 1.43%   |
| Norway      | 2         | 1.43%   |
| Mexico      | 2         | 1.43%   |
| Japan       | 2         | 1.43%   |
| Iran        | 2         | 1.43%   |
| India       | 2         | 1.43%   |
| Guadeloupe  | 2         | 1.43%   |
| Finland     | 2         | 1.43%   |
| Colombia    | 2         | 1.43%   |
| Canada      | 2         | 1.43%   |
| Vietnam     | 1         | 0.71%   |
| Turkey      | 1         | 0.71%   |
| Sweden      | 1         | 0.71%   |
| Romania     | 1         | 0.71%   |
| Qatar       | 1         | 0.71%   |
| Portugal    | 1         | 0.71%   |
| New Zealand | 1         | 0.71%   |
| Nepal       | 1         | 0.71%   |
| Namibia     | 1         | 0.71%   |
| Lithuania   | 1         | 0.71%   |
| Italy       | 1         | 0.71%   |
| Ireland     | 1         | 0.71%   |
| Guatemala   | 1         | 0.71%   |
| Czechia     | 1         | 0.71%   |
| China       | 1         | 0.71%   |
| Chile       | 1         | 0.71%   |
| Austria     | 1         | 0.71%   |
| Argentina   | 1         | 0.71%   |
| Albania     | 1         | 0.71%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Lexington              | 5         | 3.52%   |
| Lübeck                | 3         | 2.11%   |
| Alphen aan den Rijn    | 3         | 2.11%   |
| Tehran                 | 2         | 1.41%   |
| Seattle                | 2         | 1.41%   |
| Salem                  | 2         | 1.41%   |
| Redmond                | 2         | 1.41%   |
| Ozersk                 | 2         | 1.41%   |
| Moscow                 | 2         | 1.41%   |
| Minneapolis            | 2         | 1.41%   |
| Menlo Park             | 2         | 1.41%   |
| Le Gosier              | 2         | 1.41%   |
| Kyiv                   | 2         | 1.41%   |
| Kirkland               | 2         | 1.41%   |
| Irkutsk                | 2         | 1.41%   |
| Helsinki               | 2         | 1.41%   |
| Chelyabinsk            | 2         | 1.41%   |
| Berlin                 | 2         | 1.41%   |
| Zurich                 | 1         | 0.7%    |
| Wenatchee              | 1         | 0.7%    |
| Weimar                 | 1         | 0.7%    |
| Wausau                 | 1         | 0.7%    |
| Warsaw                 | 1         | 0.7%    |
| Vostochnoe Degunino    | 1         | 0.7%    |
| Vilnius                | 1         | 0.7%    |
| Vancouver              | 1         | 0.7%    |
| Valladolid             | 1         | 0.7%    |
| Vacaville              | 1         | 0.7%    |
| Tuddal                 | 1         | 0.7%    |
| Trang                  | 1         | 0.7%    |
| The Bronx              | 1         | 0.7%    |
| Teteghem               | 1         | 0.7%    |
| São Paulo             | 1         | 0.7%    |
| São José dos Campos  | 1         | 0.7%    |
| Sundebru               | 1         | 0.7%    |
| Suginami-ku            | 1         | 0.7%    |
| Stuttgart              | 1         | 0.7%    |
| Scottsdale             | 1         | 0.7%    |
| Sarandë               | 1         | 0.7%    |
| San Vicent del Raspeig | 1         | 0.7%    |
| San Diego              | 1         | 0.7%    |
| San Antonio            | 1         | 0.7%    |
| Rugby                  | 1         | 0.7%    |
| Rostov-on-Don          | 1         | 0.7%    |
| Rionegro               | 1         | 0.7%    |
| Prague                 | 1         | 0.7%    |
| Porto União           | 1         | 0.7%    |
| Otjiwarongo            | 1         | 0.7%    |
| Orléans               | 1         | 0.7%    |
| Omsk                   | 1         | 0.7%    |
| Olin                   | 1         | 0.7%    |
| Oklahoma City          | 1         | 0.7%    |
| Nunoa                  | 1         | 0.7%    |
| Novosibirsk            | 1         | 0.7%    |
| Niagara Falls          | 1         | 0.7%    |
| New Delhi              | 1         | 0.7%    |
| Munich                 | 1         | 0.7%    |
| Montserrat             | 1         | 0.7%    |
| Montería              | 1         | 0.7%    |
| Monterrey              | 1         | 0.7%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 36        | 68     | 18.27%  |
| Seagate             | 33        | 96     | 16.75%  |
| WDC                 | 27        | 78     | 13.71%  |
| Toshiba             | 18        | 25     | 9.14%   |
| Kingston            | 14        | 16     | 7.11%   |
| Crucial             | 13        | 14     | 6.6%    |
| Hitachi             | 7         | 16     | 3.55%   |
| Intel               | 6         | 7      | 3.05%   |
| HGST                | 5         | 7      | 2.54%   |
| A-DATA Technology   | 5         | 5      | 2.54%   |
| SanDisk             | 4         | 4      | 2.03%   |
| SK Hynix            | 3         | 3      | 1.52%   |
| Phison              | 3         | 3      | 1.52%   |
| PNY                 | 2         | 2      | 1.02%   |
| PLEXTOR             | 2         | 2      | 1.02%   |
| Micron Technology   | 2         | 2      | 1.02%   |
| Corsair             | 2         | 2      | 1.02%   |
| Verbatim            | 1         | 1      | 0.51%   |
| TCSUNBOW            | 1         | 1      | 0.51%   |
| SPCC                | 1         | 1      | 0.51%   |
| Smartbuy            | 1         | 1      | 0.51%   |
| OWC                 | 1         | 1      | 0.51%   |
| MAXTOR              | 1         | 1      | 0.51%   |
| LITEONIT            | 1         | 1      | 0.51%   |
| Lenovo              | 1         | 1      | 0.51%   |
| KingSpec            | 1         | 1      | 0.51%   |
| KingDian            | 1         | 1      | 0.51%   |
| Intenso             | 1         | 1      | 0.51%   |
| Hewlett-Packard     | 1         | 2      | 0.51%   |
| Gigabyte Technology | 1         | 1      | 0.51%   |
| Fujitsu             | 1         | 2      | 0.51%   |
| Apple               | 1         | 1      | 0.51%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Seagate ST4000DM000-1F2168 4TB     | 4         | 1.72%   |
| Kingston SA400S37240G 240GB        | 4         | 1.72%   |
| Crucial CT500MX500SSD1 500GB       | 4         | 1.72%   |
| Toshiba MQ01ABD100 1TB             | 3         | 1.29%   |
| Samsung SSD 970 EVO Plus 250GB     | 3         | 1.29%   |
| Samsung SSD 970 EVO 500GB          | 3         | 1.29%   |
| Samsung SSD 860 EVO 500GB          | 3         | 1.29%   |
| Samsung MZVLB256HBHQ-000L7 256GB   | 3         | 1.29%   |
| WDC WD20EFRX-68EUZN0 2TB           | 2         | 0.86%   |
| Toshiba MG04SCA20EN 2TB            | 2         | 0.86%   |
| Toshiba DT01ACA100 1TB             | 2         | 0.86%   |
| Seagate ST8000VN004-2M2101 8TB     | 2         | 0.86%   |
| Seagate ST4000DM004-2CV104 4TB     | 2         | 0.86%   |
| Seagate ST2000NM0023 2TB           | 2         | 0.86%   |
| Seagate ST1000NM0023 1TB           | 2         | 0.86%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 0.86%   |
| Samsung SSD 970 EVO Plus 1TB       | 2         | 0.86%   |
| Samsung SSD 860 EVO 1TB            | 2         | 0.86%   |
| Samsung SSD 850 EVO 250GB          | 2         | 0.86%   |
| Kingston SVP200S37A60G 64GB        | 2         | 0.86%   |
| Kingston SMS200S3120G 120GB        | 2         | 0.86%   |
| Kingston SA400S37120G 120GB        | 2         | 0.86%   |
| Crucial CT120BX500SSD1 120GB       | 2         | 0.86%   |
| WDC WDS500G2B0C-00PXH0 500GB       | 1         | 0.43%   |
| WDC WDS500G2B0B-00YS70 500GB       | 1         | 0.43%   |
| WDC WDS240G2G0A-00JH30 240GB       | 1         | 0.43%   |
| WDC WDS120G2G0B-00EPW0 120GB       | 1         | 0.43%   |
| WDC WDS120G2G0A-00JH30 120GB       | 1         | 0.43%   |
| WDC WDS100T2B0B-00YS70 1TB         | 1         | 0.43%   |
| WDC WD80EMAZ-00WJTA0 8TB           | 1         | 0.43%   |
| WDC WD80EFZX-68UW8N0 8TB           | 1         | 0.43%   |
| WDC WD80EFAX-68LHPN0 8TB           | 1         | 0.43%   |
| WDC WD7500BPVT-80HXZT3 752GB       | 1         | 0.43%   |
| WDC WD5000LPVX-75V0TT0 500GB       | 1         | 0.43%   |
| WDC WD5000BEVT-75A0RT0 500GB       | 1         | 0.43%   |
| WDC WD5000AAKX-083CA0 500GB        | 1         | 0.43%   |
| WDC WD40EZRZ-22GXCB0 4TB           | 1         | 0.43%   |
| WDC WD40EZAZ-00SF3B0 4TB           | 1         | 0.43%   |
| WDC WD40EFRX-68N32N0 4TB           | 1         | 0.43%   |
| WDC WD3200BPVT-75ZEST0 320GB       | 1         | 0.43%   |
| WDC WD30EZRX-00AZ6B0 3TB           | 1         | 0.43%   |
| WDC WD30EFRX-68EUZN0 3TB           | 1         | 0.43%   |
| WDC WD2500BEVT-08A23T1 250GB       | 1         | 0.43%   |
| WDC WD20EARX-00PASB0 2TB           | 1         | 0.43%   |
| WDC WD1600BEVT-11ZCT0 160GB        | 1         | 0.43%   |
| WDC WD120EMFZ-11A6JA0 12TB         | 1         | 0.43%   |
| WDC WD120EMAZ-11BLFA0 12TB         | 1         | 0.43%   |
| WDC WD10SPZX-08Z10 1TB             | 1         | 0.43%   |
| WDC WD10SDRW-34A0XS0 1TB           | 1         | 0.43%   |
| WDC WD10JPLX-00MBPT1 1TB           | 1         | 0.43%   |
| WDC WD10EADS-00P8B0 1TB            | 1         | 0.43%   |
| WDC WD100EZAZ-11TDBA0 10TB         | 1         | 0.43%   |
| WDC WD1001FALS-00J7B0 1TB          | 1         | 0.43%   |
| WDC PC SN520 NVMe 256GB            | 1         | 0.43%   |
| Verbatim Vi550 S3 SSD 256GB        | 1         | 0.43%   |
| Toshiba THNSNK512GVN8 512GB        | 1         | 0.43%   |
| Toshiba MQ02ABD100H 1TB            | 1         | 0.43%   |
| Toshiba MQ01ABD100V 1TB            | 1         | 0.43%   |
| Toshiba MK5061GSY 500GB            | 1         | 0.43%   |
| Toshiba MK1234GSX 120GB            | 1         | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 33        | 96     | 38.82%  |
| WDC                 | 20        | 71     | 23.53%  |
| Toshiba             | 15        | 22     | 17.65%  |
| Hitachi             | 7         | 16     | 8.24%   |
| HGST                | 5         | 7      | 5.88%   |
| Samsung Electronics | 2         | 3      | 2.35%   |
| MAXTOR              | 1         | 1      | 1.18%   |
| Hewlett-Packard     | 1         | 2      | 1.18%   |
| Fujitsu             | 1         | 2      | 1.18%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 22        | 38     | 25.88%  |
| Crucial             | 13        | 14     | 15.29%  |
| Kingston            | 12        | 14     | 14.12%  |
| WDC                 | 5         | 5      | 5.88%   |
| Intel               | 5         | 6      | 5.88%   |
| SanDisk             | 4         | 4      | 4.71%   |
| A-DATA Technology   | 4         | 4      | 4.71%   |
| SK Hynix            | 2         | 2      | 2.35%   |
| Micron Technology   | 2         | 2      | 2.35%   |
| Verbatim            | 1         | 1      | 1.18%   |
| Toshiba             | 1         | 1      | 1.18%   |
| TCSUNBOW            | 1         | 1      | 1.18%   |
| SPCC                | 1         | 1      | 1.18%   |
| Smartbuy            | 1         | 1      | 1.18%   |
| PNY                 | 1         | 1      | 1.18%   |
| PLEXTOR             | 1         | 1      | 1.18%   |
| OWC                 | 1         | 1      | 1.18%   |
| LITEONIT            | 1         | 1      | 1.18%   |
| Lenovo              | 1         | 1      | 1.18%   |
| KingSpec            | 1         | 1      | 1.18%   |
| KingDian            | 1         | 1      | 1.18%   |
| Intenso             | 1         | 1      | 1.18%   |
| Gigabyte Technology | 1         | 1      | 1.18%   |
| Corsair             | 1         | 1      | 1.18%   |
| Apple               | 1         | 1      | 1.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 72        | 220    | 41.14%  |
| SSD  | 71        | 105    | 40.57%  |
| NVMe | 32        | 42     | 18.29%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 117       | 325    | 78.52%  |
| NVMe | 32        | 42     | 21.48%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 80        | 114    | 50.63%  |
| 0.51-1.0   | 38        | 82     | 24.05%  |
| 1.01-2.0   | 11        | 26     | 6.96%   |
| 3.01-4.0   | 9         | 28     | 5.7%    |
| 2.01-3.0   | 9         | 25     | 5.7%    |
| 4.01-10.0  | 8         | 36     | 5.06%   |
| 10.01-20.0 | 3         | 14     | 1.9%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 44        | 31.43%  |
| 251-500        | 26        | 18.57%  |
| 501-1000       | 17        | 12.14%  |
| 51-100         | 15        | 10.71%  |
| 21-50          | 14        | 10%     |
| 1-20           | 9         | 6.43%   |
| 1001-2000      | 8         | 5.71%   |
| More than 3000 | 3         | 2.14%   |
| 2001-3000      | 3         | 2.14%   |
| Unknown        | 1         | 0.71%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 117       | 83.57%  |
| 21-50          | 10        | 7.14%   |
| 51-100         | 4         | 2.86%   |
| 101-250        | 3         | 2.14%   |
| More than 3000 | 2         | 1.43%   |
| 251-500        | 2         | 1.43%   |
| 1001-2000      | 1         | 0.71%   |
| Unknown        | 1         | 0.71%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


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

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


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

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


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

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


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

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 114       | 327    | 79.17%  |
| Malfunc  | 27        | 34     | 18.75%  |
| Detected | 3         | 6      | 2.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 100       | 58.14%  |
| AMD                         | 23        | 13.37%  |
| Samsung Electronics         | 18        | 10.47%  |
| Broadcom / LSI              | 6         | 3.49%   |
| Phison Electronics          | 5         | 2.91%   |
| ASMedia Technology          | 5         | 2.91%   |
| Marvell Technology Group    | 4         | 2.33%   |
| Toshiba                     | 2         | 1.16%   |
| Sandisk                     | 2         | 1.16%   |
| Nvidia                      | 2         | 1.16%   |
| SK Hynix                    | 1         | 0.58%   |
| Lite-On Technology          | 1         | 0.58%   |
| Kingston Technology Company | 1         | 0.58%   |
| Hewlett-Packard             | 1         | 0.58%   |
| ADATA Technology            | 1         | 0.58%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 22        | 11.46%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 11        | 5.73%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 11        | 5.73%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 9         | 4.69%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 8         | 4.17%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 7         | 3.65%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6         | 3.13%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 6         | 3.13%   |
| AMD 400 Series Chipset SATA Controller                                           | 6         | 3.13%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 5         | 2.6%    |
| ASMedia ASM1062 Serial ATA Controller                                            | 5         | 2.6%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 4         | 2.08%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 1.56%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.56%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 3         | 1.56%   |
| Samsung NVMe Controller                                                          | 2         | 1.04%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 2         | 1.04%   |
| Phison E12 NVMe Controller                                                       | 2         | 1.04%   |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 1.04%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                            | 2         | 1.04%   |
| Intel SATA Controller [RAID mode]                                                | 2         | 1.04%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 1.04%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 2         | 1.04%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 1.04%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 2         | 1.04%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 1.04%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 2         | 1.04%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 1.04%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 2         | 1.04%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 1.04%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                     | 2         | 1.04%   |
| Toshiba unknown                                                                  | 1         | 0.52%   |
| Toshiba BG3 NVMe SSD Controller                                                  | 1         | 0.52%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 1         | 0.52%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 1         | 0.52%   |
| Sandisk PC SN520 NVMe SSD                                                        | 1         | 0.52%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 0.52%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.52%   |
| Phison E18 PCIe4 NVMe Controller                                                 | 1         | 0.52%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                     | 1         | 0.52%   |
| Marvell Group 88SE9123 PCIe SATA 6.0 Gb/s controller                             | 1         | 0.52%   |
| Lite-On M8Pe Series NVMe SSD                                                     | 1         | 0.52%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.52%   |
| Intel SSD 660P Series                                                            | 1         | 0.52%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 1         | 0.52%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 0.52%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 0.52%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 0.52%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                    | 1         | 0.52%   |
| Intel C620 Series Chipset Family IDE Redirection                                 | 1         | 0.52%   |
| Intel C600/X79 series chipset SATA RAID Controller                               | 1         | 0.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 0.52%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 1         | 0.52%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 1         | 0.52%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 1         | 0.52%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 1         | 0.52%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 1         | 0.52%   |
| Intel 82801IB (ICH9) 4 port SATA Controller [AHCI mode]                          | 1         | 0.52%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                           | 1         | 0.52%   |
| Intel 82801GR/GDH (ICH7R/ICH7DH) SATA Controller [RAID mode]                     | 1         | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 110       | 64.71%  |
| NVMe | 31        | 18.24%  |
| IDE  | 14        | 8.24%   |
| RAID | 11        | 6.47%   |
| SAS  | 4         | 2.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 107       | 76.43%  |
| AMD     | 24        | 17.14%  |
| ARM     | 7         | 5%      |
| Unknown | 2         | 1.43%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| ARM Cortex-A72 r0p3                   | 5         | 3.57%   |
| Intel Core i5-7200U CPU @ 2.50GHz     | 4         | 2.86%   |
| Intel Core i5-2520M CPU @ 2.50GHz     | 3         | 2.14%   |
| AMD Ryzen 7 2700 Eight-Core Processor | 3         | 2.14%   |
| Intel Core i7-9750H CPU @ 2.60GHz     | 2         | 1.43%   |
| Intel Core i7-8565U CPU @ 1.80GHz     | 2         | 1.43%   |
| Intel Core i7-7500U CPU @ 2.70GHz     | 2         | 1.43%   |
| Intel Core i7-6700 CPU @ 3.40GHz      | 2         | 1.43%   |
| Intel Core i5-8350U CPU @ 1.70GHz     | 2         | 1.43%   |
| Intel Core i5-8250U CPU @ 1.60GHz     | 2         | 1.43%   |
| Intel Core i5-5300U CPU @ 2.30GHz     | 2         | 1.43%   |
| Intel Core i5-4300M CPU @ 2.60GHz     | 2         | 1.43%   |
| Intel Core i5-10210U CPU @ 1.60GHz    | 2         | 1.43%   |
| Intel Core i3-4005U CPU @ 1.70GHz     | 2         | 1.43%   |
| AMD Ryzen 9 5900X 12-Core Processor   | 2         | 1.43%   |
| AMD Ryzen 9 3900X 12-Core Processor   | 2         | 1.43%   |
|                                       | 2         | 1.43%   |
| Intel Xeon Silver 4214 CPU @ 2.20GHz  | 1         | 0.71%   |
| Intel Xeon CPU X5650 @ 2.67GHz        | 1         | 0.71%   |
| Intel Xeon CPU X3440 @ 2.53GHz        | 1         | 0.71%   |
| Intel Xeon CPU E5520 @ 2.27GHz        | 1         | 0.71%   |
| Intel Xeon CPU E5-2650 v3 @ 2.30GHz   | 1         | 0.71%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz   | 1         | 0.71%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz   | 1         | 0.71%   |
| Intel Xeon CPU E3-1275 v5 @ 3.60GHz   | 1         | 0.71%   |
| Intel Processor 5Y70 CPU @ 1.10GHz    | 1         | 0.71%   |
| Intel Pentium M                       | 1         | 0.71%   |
| Intel Pentium II                      | 1         | 0.71%   |
| Intel Pentium CPU N3700 @ 1.60GHz     | 1         | 0.71%   |
| Intel Pentium CPU G630T @ 2.30GHz     | 1         | 0.71%   |
| Intel Pentium CPU G3420 @ 3.20GHz     | 1         | 0.71%   |
| Intel Pentium CPU G3220 @ 3.00GHz     | 1         | 0.71%   |
| Intel Pentium CPU G2020 @ 2.90GHz     | 1         | 0.71%   |
| Intel Pentium 4                       | 1         | 0.71%   |
| Intel Genuine CPU                     | 1         | 0.71%   |
| Intel CPU Version                     | 1         | 0.71%   |
| Intel Core i9-9900X CPU @ 3.50GHz     | 1         | 0.71%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz    | 1         | 0.71%   |
| Intel Core i7-6700K CPU @ 4.00GHz     | 1         | 0.71%   |
| Intel Core i7-6600U CPU @ 2.60GHz     | 1         | 0.71%   |
| Intel Core i7-4790S CPU @ 3.20GHz     | 1         | 0.71%   |
| Intel Core i7-4770T CPU @ 2.50GHz     | 1         | 0.71%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz    | 1         | 0.71%   |
| Intel Core i7-3770 CPU @ 3.40GHz      | 1         | 0.71%   |
| Intel Core i7-3632QM CPU @ 2.20GHz    | 1         | 0.71%   |
| Intel Core i7-3630QM CPU @ 2.40GHz    | 1         | 0.71%   |
| Intel Core i7-3610QE CPU @ 2.30GHz    | 1         | 0.71%   |
| Intel Core i7-10750H CPU @ 2.60GHz    | 1         | 0.71%   |
| Intel Core i7-10700K CPU @ 3.80GHz    | 1         | 0.71%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz    | 1         | 0.71%   |
| Intel Core i7-10510U CPU @ 1.80GHz    | 1         | 0.71%   |
| Intel Core i7 CPU M 620 @ 2.67GHz     | 1         | 0.71%   |
| Intel Core i7 CPU                     | 1         | 0.71%   |
| Intel Core i5-9300H CPU @ 2.40GHz     | 1         | 0.71%   |
| Intel Core i5-8365U CPU @ 1.60GHz     | 1         | 0.71%   |
| Intel Core i5-8265U CPU @ 1.60GHz     | 1         | 0.71%   |
| Intel Core i5-7300U CPU @ 2.60GHz     | 1         | 0.71%   |
| Intel Core i5-6500 CPU @ 3.20GHz      | 1         | 0.71%   |
| Intel Core i5-6440HQ CPU @ 2.60GHz    | 1         | 0.71%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz    | 1         | 0.71%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i5          | 36        | 25.71%  |
| Intel Core i7          | 24        | 17.14%  |
| Intel Core i3          | 11        | 7.86%   |
| AMD Ryzen 7            | 8         | 5.71%   |
| Intel Xeon             | 7         | 5%      |
| ARM Cortex             | 7         | 5%      |
| Intel Pentium          | 6         | 4.29%   |
| Intel Core 2 Duo       | 6         | 4.29%   |
| AMD Ryzen 9            | 6         | 4.29%   |
| Intel Celeron          | 5         | 3.57%   |
| Other                  | 4         | 2.86%   |
| Intel Atom             | 4         | 2.86%   |
| AMD Ryzen 5            | 3         | 2.14%   |
| Intel Xeon Silver      | 1         | 0.71%   |
| Intel Pentium M        | 1         | 0.71%   |
| Intel Pentium 4        | 1         | 0.71%   |
| Intel Genuine          | 1         | 0.71%   |
| Intel Core i9          | 1         | 0.71%   |
| Intel Core 2 Quad      | 1         | 0.71%   |
| AMD Ryzen Threadripper | 1         | 0.71%   |
| AMD Ryzen 3            | 1         | 0.71%   |
| AMD FX                 | 1         | 0.71%   |
| AMD Athlon X4          | 1         | 0.71%   |
| AMD Athlon             | 1         | 0.71%   |
| AMD A6                 | 1         | 0.71%   |
| AMD A4                 | 1         | 0.71%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 49        | 35%     |
| 4       | 43        | 30.71%  |
| Unknown | 15        | 10.71%  |
| 16      | 8         | 5.71%   |
| 8       | 6         | 4.29%   |
| 6       | 5         | 3.57%   |
| 24      | 4         | 2.86%   |
| 12      | 4         | 2.86%   |
| 32      | 2         | 1.43%   |
| 1       | 2         | 1.43%   |
| 20      | 1         | 0.71%   |
| 10      | 1         | 0.71%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 128       | 91.43%  |
| Unknown | 7         | 5%      |
| 2       | 5         | 3.57%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 79        | 56.43%  |
| 1       | 45        | 32.14%  |
| Unknown | 16        | 11.43%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 24        | 17.14%  |
| Haswell       | 14        | 10%     |
| Skylake       | 11        | 7.86%   |
| SandyBridge   | 10        | 7.14%   |
| Unknown       | 10        | 7.14%   |
| Westmere      | 9         | 6.43%   |
| IvyBridge     | 9         | 6.43%   |
| Zen+          | 6         | 4.29%   |
| Penryn        | 6         | 4.29%   |
| Broadwell     | 6         | 4.29%   |
| Zen 2         | 5         | 3.57%   |
| Zen           | 4         | 2.86%   |
| Zen 3         | 3         | 2.14%   |
| Silvermont    | 3         | 2.14%   |
| Nehalem       | 3         | 2.14%   |
| Bonnell       | 3         | 2.14%   |
| Piledriver    | 2         | 1.43%   |
| Jaguar        | 2         | 1.43%   |
| Core          | 2         | 1.43%   |
| CometLake     | 2         | 1.43%   |
| P6            | 1         | 0.71%   |
| NetBurst      | 1         | 0.71%   |
| IceLake       | 1         | 0.71%   |
| Goldmont plus | 1         | 0.71%   |
| Goldmont      | 1         | 0.71%   |
| Excavator     | 1         | 0.71%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 82        | 55.03%  |
| Nvidia                               | 39        | 26.17%  |
| AMD                                  | 21        | 14.09%  |
| Matrox Electronics Systems           | 6         | 4.03%   |
| NVidia / SGS Thomson (Joint Venture) | 1         | 0.67%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 9         | 5.84%   |
| Intel HD Graphics 620                                                         | 7         | 4.55%   |
| Intel HD Graphics 530                                                         | 6         | 3.9%    |
| Intel 3rd Gen Core processor Graphics Controller                              | 6         | 3.9%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 6         | 3.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 5         | 3.25%   |
| Intel UHD Graphics 620                                                        | 5         | 3.25%   |
| Intel HD Graphics 5500                                                        | 5         | 3.25%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)             | 4         | 2.6%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 4         | 2.6%    |
| Intel Core Processor Integrated Graphics Controller                           | 4         | 2.6%    |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 4         | 2.6%    |
| Nvidia GP108 [GeForce GT 1030]                                                | 3         | 1.95%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 3         | 1.95%   |
| Nvidia GT218 [GeForce 210]                                                    | 2         | 1.3%    |
| Nvidia GF119 [GeForce GT 610]                                                 | 2         | 1.3%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 2         | 1.3%    |
| Intel Skylake GT2 [HD Graphics 520]                                           | 2         | 1.3%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 2         | 1.3%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 2         | 1.3%    |
| Intel Haswell-ULT Integrated Graphics Controller                              | 2         | 1.3%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 2         | 1.3%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 2         | 1.3%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 2         | 1.3%    |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                      | 2         | 1.3%    |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                | 2         | 1.3%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 1         | 0.65%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                 | 1         | 0.65%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 1         | 0.65%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                         | 1         | 0.65%   |
| Nvidia TU104M [GeForce RTX 2070 SUPER Mobile / Max-Q]                         | 1         | 0.65%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                         | 1         | 0.65%   |
| Nvidia MCP7A [GeForce 9400]                                                   | 1         | 0.65%   |
| Nvidia GT218 [NVS 300]                                                        | 1         | 0.65%   |
| Nvidia GT216M [GeForce GT 330M]                                               | 1         | 0.65%   |
| Nvidia GT216M [GeForce GT 240M]                                               | 1         | 0.65%   |
| Nvidia GP108M [GeForce MX250]                                                 | 1         | 0.65%   |
| Nvidia GP108M [GeForce MX230]                                                 | 1         | 0.65%   |
| Nvidia GP107GL [Quadro P600]                                                  | 1         | 0.65%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                           | 1         | 0.65%   |
| Nvidia GM107M [GeForce GTX 960M]                                              | 1         | 0.65%   |
| Nvidia GM107M [GeForce GTX 860M]                                              | 1         | 0.65%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                         | 1         | 0.65%   |
| Nvidia GK208BM [GeForce 920M]                                                 | 1         | 0.65%   |
| Nvidia GK208B [GeForce GT 710]                                                | 1         | 0.65%   |
| Nvidia GF119 [GeForce GT 520]                                                 | 1         | 0.65%   |
| Nvidia GF110 [GeForce GTX 580]                                                | 1         | 0.65%   |
| Nvidia GF108M [GeForce GT 525M]                                               | 1         | 0.65%   |
| Nvidia GF108GLM [NVS 5200M]                                                   | 1         | 0.65%   |
| Nvidia GA104 [GeForce RTX 3070]                                               | 1         | 0.65%   |
| Nvidia GA102 [GeForce RTX 3080]                                               | 1         | 0.65%   |
| Nvidia G98M [GeForce G 103M]                                                  | 1         | 0.65%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                           | 1         | 0.65%   |
| Nvidia G96CM [GeForce 9600M GT]                                               | 1         | 0.65%   |
| Nvidia G92 [GeForce GT 330]                                                   | 1         | 0.65%   |
| Nvidia G84GL [Quadro FX 1700]                                                 | 1         | 0.65%   |
| Nvidia G72 [GeForce 7300 LE]                                                  | 1         | 0.65%   |
| Nvidia G72 [GeForce 7200 GS / 7300 SE]                                        | 1         | 0.65%   |
| Nvidia C79 [GeForce 9400M]                                                    | 1         | 0.65%   |
| NVidia / SGS Thomson (Joint Venture) Riva128                                  | 1         | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| 1 x Intel                                | 58        | 41.43%  |
| 1 x Nvidia                               | 24        | 17.14%  |
| 1 x AMD                                  | 16        | 11.43%  |
| Intel + Nvidia                           | 14        | 10%     |
| Other                                    | 9         | 6.43%   |
| 2 x Intel                                | 6         | 4.29%   |
| 1 x Matrox                               | 6         | 4.29%   |
| Intel + AMD                              | 3         | 2.14%   |
| 2 x AMD                                  | 2         | 1.43%   |
| 2 x Nvidia                               | 1         | 0.71%   |
| 1 x NVidia / SGS Thomson (Joint Venture) | 1         | 0.71%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 109       | 77.86%  |
| Proprietary | 21        | 15%     |
| Unknown     | 10        | 7.14%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 114       | 81.43%  |
| 7.01-8.0   | 6         | 4.29%   |
| 1.01-2.0   | 6         | 4.29%   |
| 3.01-4.0   | 4         | 2.86%   |
| 0.01-0.5   | 4         | 2.86%   |
| 0.51-1.0   | 3         | 2.14%   |
| 5.01-6.0   | 2         | 1.43%   |
| 8.01-16.0  | 1         | 0.71%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 14        | 15.05%  |
| LG Display           | 10        | 10.75%  |
| BOE                  | 10        | 10.75%  |
| Samsung Electronics  | 9         | 9.68%   |
| Goldstar             | 8         | 8.6%    |
| Dell                 | 6         | 6.45%   |
| Ancor Communications | 5         | 5.38%   |
| Hewlett-Packard      | 4         | 4.3%    |
| Chimei Innolux       | 4         | 4.3%    |
| AOC                  | 4         | 4.3%    |
| Sharp                | 3         | 3.23%   |
| InfoVision           | 2         | 2.15%   |
| Iiyama               | 2         | 2.15%   |
| BenQ                 | 2         | 2.15%   |
| Acer                 | 2         | 2.15%   |
| Sceptre Tech         | 1         | 1.08%   |
| LG Electronics       | 1         | 1.08%   |
| Lenovo               | 1         | 1.08%   |
| HannStar             | 1         | 1.08%   |
| Eizo                 | 1         | 1.08%   |
| CPT                  | 1         | 1.08%   |
| CKL                  | 1         | 1.08%   |
| Apple                | 1         | 1.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP1476 3840x2160 350x190mm 15.7-inch                | 1         | 1.08%   |
| Sharp LCD Monitor SHP1451 1920x1080 280x160mm 12.7-inch                | 1         | 1.08%   |
| Sharp LCD Monitor SHP143E 3840x2160 350x190mm 15.7-inch                | 1         | 1.08%   |
| Sceptre Tech Sceptre E20 SPT080D 1600x900 410x280mm 19.5-inch          | 1         | 1.08%   |
| Samsung Electronics SyncMaster SAM027D 1680x1050 430x270mm 20.0-inch   | 1         | 1.08%   |
| Samsung Electronics SyncMaster SAM0236 2560x1600 640x400mm 29.7-inch   | 1         | 1.08%   |
| Samsung Electronics SyncMaster SAM01BB 1280x1024 380x300mm 19.1-inch   | 1         | 1.08%   |
| Samsung Electronics S24E510C SAM0C61 1920x1080 520x300mm 23.6-inch     | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SEC3849 1366x768 310x170mm 13.9-inch   | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch   | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 340x190mm 15.3-inch   | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1210x680mm 54.6-inch | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SAM0D4F 1920x1080 1020x570mm 46.0-inch | 1         | 1.08%   |
| LG Electronics LCD Monitor LG Ultra HD 3840x2160                       | 1         | 1.08%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch           | 1         | 1.08%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch           | 1         | 1.08%   |
| LG Display LCD Monitor LGD03D3 1600x900 310x170mm 13.9-inch            | 1         | 1.08%   |
| LG Display LCD Monitor LGD03AB 1366x768 340x190mm 15.3-inch            | 1         | 1.08%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch            | 1         | 1.08%   |
| LG Display LCD Monitor LGD032C 1920x1080 340x190mm 15.3-inch           | 1         | 1.08%   |
| LG Display LCD Monitor LGD0314 1366x768 290x160mm 13.0-inch            | 1         | 1.08%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch            | 1         | 1.08%   |
| LG Display LCD Monitor LGD02D9 1920x1080 340x190mm 15.3-inch           | 1         | 1.08%   |
| LG Display LCD Monitor LGD0214 1600x900 350x190mm 15.7-inch            | 1         | 1.08%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch                | 1         | 1.08%   |
| InfoVision LCD Monitor IVO0536 1920x1080 290x170mm 13.2-inch           | 1         | 1.08%   |
| InfoVision LCD Monitor IVO04E5 1366x768 280x160mm 12.7-inch            | 1         | 1.08%   |
| Iiyama PLX2483H IVM6114 1920x1080 530x300mm 24.0-inch                  | 1         | 1.08%   |
| Iiyama PL2209HD IVM560B 1920x1080 480x270mm 21.7-inch                  | 1         | 1.08%   |
| Hewlett-Packard Z24nf HWP3209 1920x1080 530x300mm 24.0-inch            | 1         | 1.08%   |
| Hewlett-Packard LCD Monitor HPN401E 1920x1080 480x270mm 21.7-inch      | 1         | 1.08%   |
| Hewlett-Packard HPQ 800 AIO HWP1080 1920x1080 510x290mm 23.1-inch      | 1         | 1.08%   |
| Hewlett-Packard 24xw HWP3256 1920x1080 530x300mm 24.0-inch             | 1         | 1.08%   |
| HannStar HSD100IFW1 HSD03E9 1024x600 220x130mm 10.1-inch               | 1         | 1.08%   |
| Goldstar W2246 GSM5784 1920x1080 480x270mm 21.7-inch                   | 1         | 1.08%   |
| Goldstar LG ULTRAWIDE GSM5AFB 2560x1080 800x340mm 34.2-inch            | 1         | 1.08%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch             | 1         | 1.08%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch             | 1         | 1.08%   |
| Goldstar LG TV GSMC0A0 3840x2160                                       | 1         | 1.08%   |
| Goldstar LG FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch              | 1         | 1.08%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 600x340mm 27.2-inch                 | 1         | 1.08%   |
| Goldstar 22EA53 GSM59A4 1920x1080 480x270mm 21.7-inch                  | 1         | 1.08%   |
| Eizo CS2420 ENC2741 1920x1200 520x330mm 24.2-inch                      | 1         | 1.08%   |
| Dell U2412M DELA07B 1920x1200 520x320mm 24.0-inch                      | 1         | 1.08%   |
| Dell SE2717H/HX DELD0A1 1920x1080 600x340mm 27.2-inch                  | 1         | 1.08%   |
| Dell S2340M DELD05A 1920x1080 510x290mm 23.1-inch                      | 1         | 1.08%   |
| Dell P2415Q DELA0BE 3840x2160 530x300mm 24.0-inch                      | 1         | 1.08%   |
| Dell LCD Monitor U3011 2560x1600                                       | 1         | 1.08%   |
| Dell E1916H DELF065 1366x768 410x230mm 18.5-inch                       | 1         | 1.08%   |
| CPT LCD Monitor CPT04C4 1024x600 230x140mm 10.6-inch                   | 1         | 1.08%   |
| CKL LCD Monitor CKL0001 1920x1200 1150x650mm 52.0-inch                 | 1         | 1.08%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 340x190mm 15.3-inch       | 1         | 1.08%   |
| Chimei Innolux LCD Monitor CMN1509 1920x1080 340x190mm 15.3-inch       | 1         | 1.08%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 310x170mm 13.9-inch       | 1         | 1.08%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 280x160mm 12.7-inch       | 1         | 1.08%   |
| BOE LCD Monitor BOE0806 1920x1080 310x170mm 13.9-inch                  | 1         | 1.08%   |
| BOE LCD Monitor BOE07BD 1920x1080 310x170mm 13.9-inch                  | 1         | 1.08%   |
| BOE LCD Monitor BOE0742 1920x1080 310x170mm 13.9-inch                  | 1         | 1.08%   |
| BOE LCD Monitor BOE0729 1920x1080 340x190mm 15.3-inch                  | 1         | 1.08%   |
| BOE LCD Monitor BOE06E2 1920x1080 310x170mm 13.9-inch                  | 1         | 1.08%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 39        | 44.83%  |
| 1366x768 (WXGA)    | 15        | 17.24%  |
| 3840x2160 (4K)     | 10        | 11.49%  |
| 1920x1200 (WUXGA)  | 5         | 5.75%   |
| 1600x900 (HD+)     | 5         | 5.75%   |
| 1280x800 (WXGA)    | 4         | 4.6%    |
| 2560x1600          | 2         | 2.3%    |
| 2560x1440 (QHD)    | 2         | 2.3%    |
| 1024x600           | 2         | 2.3%    |
| 2560x1080          | 1         | 1.15%   |
| 1680x1050 (WSXGA+) | 1         | 1.15%   |
| 1280x1024 (SXGA)   | 1         | 1.15%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 23        | 25.56%  |
| 13      | 12        | 13.33%  |
| 24      | 9         | 10%     |
| 27      | 6         | 6.67%   |
| 21      | 6         | 6.67%   |
| 12      | 6         | 6.67%   |
| Unknown | 6         | 6.67%   |
| 23      | 4         | 4.44%   |
| 17      | 3         | 3.33%   |
| 19      | 2         | 2.22%   |
| 14      | 2         | 2.22%   |
| 10      | 2         | 2.22%   |
| 54      | 1         | 1.11%   |
| 52      | 1         | 1.11%   |
| 46      | 1         | 1.11%   |
| 34      | 1         | 1.11%   |
| 32      | 1         | 1.11%   |
| 31      | 1         | 1.11%   |
| 29      | 1         | 1.11%   |
| 20      | 1         | 1.11%   |
| 18      | 1         | 1.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 32        | 36.36%  |
| 501-600     | 17        | 19.32%  |
| 201-300     | 13        | 14.77%  |
| 401-500     | 9         | 10.23%  |
| Unknown     | 6         | 6.82%   |
| 351-400     | 4         | 4.55%   |
| 1001-1500   | 3         | 3.41%   |
| 701-800     | 2         | 2.27%   |
| 601-700     | 2         | 2.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 66        | 79.52%  |
| 16/10   | 9         | 10.84%  |
| Unknown | 5         | 6.02%   |
| 5/4     | 1         | 1.2%    |
| 3/2     | 1         | 1.2%    |
| 21/9    | 1         | 1.2%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 91-100         | 19        | 21.35%  |
| 201-250        | 14        | 15.73%  |
| 81-90          | 12        | 13.48%  |
| 61-70          | 6         | 6.74%   |
| 301-350        | 6         | 6.74%   |
| Unknown        | 6         | 6.74%   |
| 351-500        | 4         | 4.49%   |
| 251-300        | 4         | 4.49%   |
| 101-110        | 4         | 4.49%   |
| 151-200        | 3         | 3.37%   |
| 121-130        | 3         | 3.37%   |
| More than 1000 | 2         | 2.25%   |
| 71-80          | 2         | 2.25%   |
| 41-50          | 2         | 2.25%   |
| 141-150        | 1         | 1.12%   |
| 501-1000       | 1         | 1.12%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 25        | 28.09%  |
| 121-160       | 23        | 25.84%  |
| 51-100        | 23        | 25.84%  |
| 161-240       | 7         | 7.87%   |
| Unknown       | 6         | 6.74%   |
| More than 240 | 3         | 3.37%   |
| 1-50          | 2         | 2.25%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 70        | 50%     |
| 0     | 58        | 41.43%  |
| 2     | 10        | 7.14%   |
| 3     | 2         | 1.43%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 82        | 42.05%  |
| Realtek Semiconductor    | 58        | 29.74%  |
| Qualcomm Atheros         | 24        | 12.31%  |
| Broadcom                 | 15        | 7.69%   |
| Ralink Technology        | 2         | 1.03%   |
| Nvidia                   | 2         | 1.03%   |
| Mellanox Technologies    | 2         | 1.03%   |
| Marvell Technology Group | 2         | 1.03%   |
| Edimax Technology        | 2         | 1.03%   |
| Xiaomi                   | 1         | 0.51%   |
| Ralink                   | 1         | 0.51%   |
| Qualcomm                 | 1         | 0.51%   |
| NetGear                  | 1         | 0.51%   |
| IMC Networks             | 1         | 0.51%   |
| ADMtek                   | 1         | 0.51%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 45        | 18.91%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 8         | 3.36%   |
| Intel I211 Gigabit Network Connection                                         | 8         | 3.36%   |
| Intel Wireless 8265 / 8275                                                    | 7         | 2.94%   |
| Intel Wi-Fi 6 AX200                                                           | 7         | 2.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 7         | 2.94%   |
| Intel Wireless-AC 9260                                                        | 6         | 2.52%   |
| Intel Wireless 7265                                                           | 5         | 2.1%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 5         | 2.1%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 4         | 1.68%   |
| Intel 82574L Gigabit Network Connection                                       | 4         | 1.68%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 3         | 1.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 3         | 1.26%   |
| Intel Wireless 3160                                                           | 3         | 1.26%   |
| Intel I350 Gigabit Network Connection                                         | 3         | 1.26%   |
| Intel I210 Gigabit Network Connection                                         | 3         | 1.26%   |
| Intel Ethernet Connection I217-LM                                             | 3         | 1.26%   |
| Intel Ethernet Connection (4) I219-V                                          | 3         | 1.26%   |
| Intel Ethernet Connection (2) I219-V                                          | 3         | 1.26%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3         | 1.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 3         | 1.26%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 3         | 1.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 0.84%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 2         | 0.84%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 2         | 0.84%   |
| Realtek RTL8125 2.5GbE Controller                                             | 2         | 0.84%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 2         | 0.84%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2         | 0.84%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 2         | 0.84%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 2         | 0.84%   |
| Nvidia MCP79 Ethernet                                                         | 2         | 0.84%   |
| Mellanox MT27500 Family [ConnectX-3]                                          | 2         | 0.84%   |
| Intel Wireless 8260                                                           | 2         | 0.84%   |
| Intel Wireless 3165                                                           | 2         | 0.84%   |
| Intel Ethernet Connection (7) I219-V                                          | 2         | 0.84%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 2         | 0.84%   |
| Intel Centrino Ultimate-N 6300                                                | 2         | 0.84%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 2         | 0.84%   |
| Intel 82577LM Gigabit Network Connection                                      | 2         | 0.84%   |
| Intel 82577LC Gigabit Network Connection                                      | 2         | 0.84%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2         | 0.84%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                | 2         | 0.84%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 0.84%   |
| Broadcom BCM43142 802.11b/g/n                                                 | 2         | 0.84%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                          | 1         | 0.42%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.42%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 0.42%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 1         | 0.42%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 1         | 0.42%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 0.42%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1         | 0.42%   |
| Ralink RT2500 Wireless 802.11bg                                               | 1         | 0.42%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                        | 1         | 0.42%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1         | 0.42%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 1         | 0.42%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 0.42%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1         | 0.42%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 1         | 0.42%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1         | 0.42%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 1         | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 56        | 56%     |
| Qualcomm Atheros      | 18        | 18%     |
| Broadcom              | 10        | 10%     |
| Realtek Semiconductor | 9         | 9%      |
| Ralink Technology     | 2         | 2%      |
| Edimax Technology     | 2         | 2%      |
| Ralink                | 1         | 1%      |
| NetGear               | 1         | 1%      |
| IMC Networks          | 1         | 1%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 7         | 6.93%   |
| Intel Wi-Fi 6 AX200                                                     | 7         | 6.93%   |
| Intel Wireless-AC 9260                                                  | 6         | 5.94%   |
| Intel Wireless 7265                                                     | 5         | 4.95%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 4.95%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 3.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 2.97%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 2.97%   |
| Intel Wireless 3160                                                     | 3         | 2.97%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 2.97%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 2.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.98%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 1.98%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 1.98%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 2         | 1.98%   |
| Intel Wireless 8260                                                     | 2         | 1.98%   |
| Intel Wireless 3165                                                     | 2         | 1.98%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 1.98%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 1.98%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.98%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 2         | 1.98%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 1.98%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 1.98%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.99%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.99%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 1         | 0.99%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.99%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.99%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.99%   |
| Ralink RT2500 Wireless 802.11bg                                         | 1         | 0.99%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.99%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.99%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                        | 1         | 0.99%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.99%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]             | 1         | 0.99%   |
| Intel Wireless 7260                                                     | 1         | 0.99%   |
| Intel WiFi Link 5100                                                    | 1         | 0.99%   |
| Intel Ultimate N WiFi Link 5300                                         | 1         | 0.99%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 0.99%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 0.99%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 0.99%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 0.99%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 0.99%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 0.99%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 0.99%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]                    | 1         | 0.99%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 1         | 0.99%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                      | 1         | 0.99%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 1         | 0.99%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 53        | 41.41%  |
| Intel                    | 53        | 41.41%  |
| Qualcomm Atheros         | 8         | 6.25%   |
| Broadcom                 | 7         | 5.47%   |
| Nvidia                   | 2         | 1.56%   |
| Marvell Technology Group | 2         | 1.56%   |
| Xiaomi                   | 1         | 0.78%   |
| Qualcomm                 | 1         | 0.78%   |
| ADMtek                   | 1         | 0.78%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 45        | 33.83%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 8         | 6.02%   |
| Intel I211 Gigabit Network Connection                                         | 8         | 6.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 7         | 5.26%   |
| Intel 82574L Gigabit Network Connection                                       | 4         | 3.01%   |
| Intel I350 Gigabit Network Connection                                         | 3         | 2.26%   |
| Intel I210 Gigabit Network Connection                                         | 3         | 2.26%   |
| Intel Ethernet Connection I217-LM                                             | 3         | 2.26%   |
| Intel Ethernet Connection (4) I219-V                                          | 3         | 2.26%   |
| Intel Ethernet Connection (2) I219-V                                          | 3         | 2.26%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3         | 2.26%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 2         | 1.5%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 2         | 1.5%    |
| Nvidia MCP79 Ethernet                                                         | 2         | 1.5%    |
| Intel Ethernet Connection (7) I219-V                                          | 2         | 1.5%    |
| Intel 82577LM Gigabit Network Connection                                      | 2         | 1.5%    |
| Intel 82577LC Gigabit Network Connection                                      | 2         | 1.5%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2         | 1.5%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                          | 1         | 0.75%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                        | 1         | 0.75%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1         | 0.75%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 1         | 0.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1         | 0.75%   |
| Qualcomm ALCATEL Composite RNDIS Interface                                    | 1         | 0.75%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1         | 0.75%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                          | 1         | 0.75%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                             | 1         | 0.75%   |
| Intel Ethernet Controller I225-V                                              | 1         | 0.75%   |
| Intel Ethernet Connection I219-LM                                             | 1         | 0.75%   |
| Intel Ethernet Connection (6) I219-LM                                         | 1         | 0.75%   |
| Intel Ethernet Connection (4) I219-LM                                         | 1         | 0.75%   |
| Intel Ethernet Connection (3) I219-LM                                         | 1         | 0.75%   |
| Intel Ethernet Connection (3) I218-V                                          | 1         | 0.75%   |
| Intel Ethernet Connection (3) I218-LM                                         | 1         | 0.75%   |
| Intel Ethernet Connection (2) I218-V                                          | 1         | 0.75%   |
| Intel Ethernet Connection (10) I219-LM                                        | 1         | 0.75%   |
| Intel 82573L Gigabit Ethernet Controller                                      | 1         | 0.75%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 1         | 0.75%   |
| Intel 82567LM Gigabit Network Connection                                      | 1         | 0.75%   |
| Broadcom NetXtreme II BCM57711E 10-Gigabit PCIe                               | 1         | 0.75%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 1         | 0.75%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 1         | 0.75%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 1         | 0.75%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                       | 1         | 0.75%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 1         | 0.75%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 1         | 0.75%   |
| ADMtek NC100 Network Everywhere Fast Ethernet 10/100                          | 1         | 0.75%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 122       | 55.71%  |
| WiFi     | 93        | 42.47%  |
| Unknown  | 4         | 1.83%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 112       | 62.57%  |
| WiFi     | 67        | 37.43%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 89        | 63.57%  |
| 1     | 32        | 22.86%  |
| 0     | 9         | 6.43%   |
| 4     | 5         | 3.57%   |
| 3     | 5         | 3.57%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 121       | 85.82%  |
| Yes  | 20        | 14.18%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 39        | 61.9%   |
| Qualcomm Atheros Communications | 6         | 9.52%   |
| Broadcom                        | 5         | 7.94%   |
| Apple                           | 4         | 6.35%   |
| Realtek Semiconductor           | 3         | 4.76%   |
| Lite-On Technology              | 1         | 1.59%   |
| IMC Networks                    | 1         | 1.59%   |
| Foxconn / Hon Hai               | 1         | 1.59%   |
| Dell                            | 1         | 1.59%   |
| Cambridge Silicon Radio         | 1         | 1.59%   |
| ASUSTek Computer                | 1         | 1.59%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 15        | 23.81%  |
| Intel AX200 Bluetooth                                       | 7         | 11.11%  |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 6         | 9.52%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 4         | 6.35%   |
| Intel AX201 Bluetooth                                       | 3         | 4.76%   |
| Apple Bluetooth Host Controller                             | 3         | 4.76%   |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 3.17%   |
| Intel Wireless-AC 3168 Bluetooth                            | 2         | 3.17%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 3.17%   |
| Realtek  Bluetooth Adapter                                  | 1         | 1.59%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 1         | 1.59%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 1.59%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 1.59%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 1.59%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 1.59%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 1.59%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 1.59%   |
| IMC Networks Bluetooth Module                               | 1         | 1.59%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 1         | 1.59%   |
| Dell DW375 Bluetooth Module                                 | 1         | 1.59%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 1         | 1.59%   |
| Broadcom BCM43142 Bluetooth 4.0                             | 1         | 1.59%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 1         | 1.59%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 1         | 1.59%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 1         | 1.59%   |
| Broadcom BCM2045 Bluetooth                                  | 1         | 1.59%   |
| ASUS BT-253 Bluetooth Adapter                               | 1         | 1.59%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1         | 1.59%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 94        | 59.87%  |
| AMD                                  | 27        | 17.2%   |
| Nvidia                               | 26        | 16.56%  |
| Thesycon Systemsoftware & Consulting | 1         | 0.64%   |
| Texas Instruments                    | 1         | 0.64%   |
| SteelSeries ApS                      | 1         | 0.64%   |
| Realtek Semiconductor                | 1         | 0.64%   |
| Lenovo                               | 1         | 0.64%   |
| Ensoniq                              | 1         | 0.64%   |
| Creative Labs                        | 1         | 0.64%   |
| Corsair                              | 1         | 0.64%   |
| C-Media Electronics                  | 1         | 0.64%   |
| BEHRINGER International              | 1         | 0.64%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                                     | Computers | Percent |
|-----------------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                           | 14        | 7.57%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                                | 9         | 4.86%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                                       | 8         | 4.32%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                                       | 8         | 4.32%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                                  | 8         | 4.32%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                                       | 8         | 4.32%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                          | 7         | 3.78%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                                   | 6         | 3.24%   |
| Intel Broadwell-U Audio Controller                                                                        | 6         | 3.24%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                           | 6         | 3.24%   |
| AMD Starship/Matisse HD Audio Controller                                                                  | 6         | 3.24%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                                | 6         | 3.24%   |
| Intel Comet Lake PCH-LP cAVS                                                                              | 4         | 2.16%   |
| Intel Cannon Point-LP High Definition Audio Controller                                                    | 4         | 2.16%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                            | 4         | 2.16%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                                       | 4         | 2.16%   |
| Nvidia High Definition Audio Controller                                                                   | 3         | 1.62%   |
| Nvidia GP108 High Definition Audio Controller                                                             | 3         | 1.62%   |
| Nvidia GF119 HDMI Audio Controller                                                                        | 3         | 1.62%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                                   | 3         | 1.62%   |
| Intel Cannon Lake PCH cAVS                                                                                | 3         | 1.62%   |
| AMD FCH Azalia Controller                                                                                 | 3         | 1.62%   |
| Nvidia TU116 High Definition Audio Controller                                                             | 2         | 1.08%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                            | 2         | 1.08%   |
| Nvidia TU104 HD Audio Controller                                                                          | 2         | 1.08%   |
| Nvidia MCP79 High Definition Audio                                                                        | 2         | 1.08%   |
| Nvidia GT216 HDMI Audio Controller                                                                        | 2         | 1.08%   |
| Intel Haswell-ULT HD Audio Controller                                                                     | 2         | 1.08%   |
| Intel Comet Lake PCH cAVS                                                                                 | 2         | 1.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                                | 2         | 1.08%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                         | 2         | 1.08%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                          | 2         | 1.08%   |
| Intel 8 Series HD Audio Controller                                                                        | 2         | 1.08%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                                                | 2         | 1.08%   |
| AMD Renoir Radeon High Definition Audio Controller                                                        | 2         | 1.08%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                              | 2         | 1.08%   |
| Thesycon Systemsoftware & Consulting Topping DX3 Pro Audio Control                                        | 1         | 0.54%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                         | 1         | 0.54%   |
| SteelSeries ApS Arctis Pro Wireless Arctis Pro Wireless Chat Arctis Pro Wireless Game Arctis Pro Wireless | 1         | 0.54%   |
| Realtek Semiconductor TX-384Khz Hifi Type-C Audio                                                         | 1         | 0.54%   |
| Nvidia GP107GL High Definition Audio Controller                                                           | 1         | 0.54%   |
| Nvidia GP106 High Definition Audio Controller                                                             | 1         | 0.54%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                                     | 1         | 0.54%   |
| Nvidia GF110 High Definition Audio Controller                                                             | 1         | 0.54%   |
| Nvidia GF108 High Definition Audio Controller                                                             | 1         | 0.54%   |
| Nvidia GA104 High Definition Audio Controller                                                             | 1         | 0.54%   |
| Nvidia GA102 High Definition Audio Controller                                                             | 1         | 0.54%   |
| Lenovo Lenovo ThinkPad OneLink Pro Dock                                                                   | 1         | 0.54%   |
| Intel Lewisburg MROM 0                                                                                    | 1         | 0.54%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                                 | 1         | 0.54%   |
| Intel CM238 HD Audio Controller                                                                           | 1         | 0.54%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                              | 1         | 0.54%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                         | 1         | 0.54%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller         | 1         | 0.54%   |
| Intel 200 Series PCH HD Audio                                                                             | 1         | 0.54%   |
| Ensoniq 5880B / Creative Labs CT5880                                                                      | 1         | 0.54%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                                             | 1         | 0.54%   |
| Corsair Corsair VOID PRO Wireless Gaming Headset                                                          | 1         | 0.54%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                         | 1         | 0.54%   |
| BEHRINGER International UMC202HD 192k                                                                     | 1         | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 31        | 21.68%  |
| SK Hynix            | 23        | 16.08%  |
| Kingston            | 20        | 13.99%  |
| Unknown             | 16        | 11.19%  |
| Crucial             | 14        | 9.79%   |
| Micron Technology   | 11        | 7.69%   |
| Corsair             | 9         | 6.29%   |
| Ramaxel Technology  | 4         | 2.8%    |
| G.Skill             | 3         | 2.1%    |
| Team                | 2         | 1.4%    |
| Smart               | 2         | 1.4%    |
| Transcend           | 1         | 0.7%    |
| Silicon Power       | 1         | 0.7%    |
| Qimonda             | 1         | 0.7%    |
| PUSKILL             | 1         | 0.7%    |
| Neo Forza           | 1         | 0.7%    |
| GOODRAM             | 1         | 0.7%    |
| AMD                 | 1         | 0.7%    |
| A-DATA Technology   | 1         | 0.7%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s   | 3         | 1.99%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s              | 2         | 1.32%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 2         | 1.32%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 2         | 1.32%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 2         | 1.32%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s  | 2         | 1.32%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s   | 2         | 1.32%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s   | 2         | 1.32%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s   | 2         | 1.32%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s | 2         | 1.32%   |
| Crucial RAM CT8G4SFS824A.C8BD1 8GB SODIMM DDR4 2400MT/s | 2         | 1.32%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s   | 2         | 1.32%   |
| Unknown SODIMM 1GB SODIMM DDR2 533MT/s                  | 1         | 0.66%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s               | 1         | 0.66%   |
| Unknown RAM Module 8GB DIMM DDR3 1067MT/s               | 1         | 0.66%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s             | 1         | 0.66%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s               | 1         | 0.66%   |
| Unknown RAM Module 4GB DIMM 400MT/s                     | 1         | 0.66%   |
| Unknown RAM Module 2GB SODIMM 667MT/s                   | 1         | 0.66%   |
| Unknown RAM Module 2GB DIMM SDRAM                       | 1         | 0.66%   |
| Unknown RAM Module 2GB DIMM DDR3 1332MT/s               | 1         | 0.66%   |
| Unknown RAM Module 2GB DIMM DDR 800MT/s                 | 1         | 0.66%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                | 1         | 0.66%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                | 1         | 0.66%   |
| Unknown RAM Module 16GB DIMM DDR4 2133MT/s              | 1         | 0.66%   |
| Unknown RAM 2G-08-10-12-1333 2GB DIMM DDR3 1333MT/s     | 1         | 0.66%   |
| Transcend RAM TS2GSH64V1B 16GB SODIMM DDR4 2133MT/s     | 1         | 0.66%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3200MT/s      | 1         | 0.66%   |
| Team RAM TEAMGROUP-UD4-3200 32GB DIMM DDR4 3200MT/s     | 1         | 0.66%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s   | 1         | 0.66%   |
| Smart RAM SF464128CKHIWDFSEG 4GB SODIMM DDR4 2133MT/s   | 1         | 0.66%   |
| SK Hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s    | 1         | 0.66%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1067MT/s            | 1         | 0.66%   |
| SK Hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s    | 1         | 0.66%   |
| SK Hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 1         | 0.66%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 1         | 0.66%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s  | 1         | 0.66%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s  | 1         | 0.66%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s  | 1         | 0.66%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s  | 1         | 0.66%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s  | 1         | 0.66%   |
| SK Hynix RAM HMA82GU6AFR8N-UH 16GB DIMM DDR4 2400MT/s   | 1         | 0.66%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s | 1         | 0.66%   |
| SK Hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s | 1         | 0.66%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s  | 1         | 0.66%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s  | 1         | 0.66%   |
| Silicon Power RAM DCLT4GN128O 4GB DIMM DDR3 1333MT/s    | 1         | 0.66%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s             | 1         | 0.66%   |
| Samsung RAM Module 2GB SODIMM DDR3 1067MT/s             | 1         | 0.66%   |
| Samsung RAM Module 16GB DIMM DDR3 1600MT/s              | 1         | 0.66%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 1067MT/s   | 1         | 0.66%   |
| Samsung RAM M471B5673DZ1-CF8 2GB SODIMM DDR3 1066MT/s   | 1         | 0.66%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s   | 1         | 0.66%   |
| Samsung RAM M471B5273CM0-CH9 4GB SODIMM DDR3 1333MT/s   | 1         | 0.66%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s   | 1         | 0.66%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1333MT/s   | 1         | 0.66%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s   | 1         | 0.66%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s   | 1         | 0.66%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s   | 1         | 0.66%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s  | 1         | 0.66%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 58        | 44.62%  |
| DDR3    | 57        | 43.85%  |
| DDR2    | 6         | 4.62%   |
| DDR     | 4         | 3.08%   |
| LPDDR3  | 2         | 1.54%   |
| Unknown | 2         | 1.54%   |
| SDRAM   | 1         | 0.77%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 77        | 59.69%  |
| DIMM         | 50        | 38.76%  |
| Row Of Chips | 2         | 1.55%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 46        | 34.07%  |
| 4096  | 38        | 28.15%  |
| 16384 | 22        | 16.3%   |
| 2048  | 17        | 12.59%  |
| 32768 | 8         | 5.93%   |
| 1024  | 4         | 2.96%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 37        | 27.01%  |
| 2667    | 16        | 11.68%  |
| 2400    | 16        | 11.68%  |
| 2133    | 15        | 10.95%  |
| 1333    | 13        | 9.49%   |
| 3200    | 9         | 6.57%   |
| 1067    | 7         | 5.11%   |
| 800     | 4         | 2.92%   |
| 667     | 4         | 2.92%   |
| 2933    | 3         | 2.19%   |
| 3000    | 2         | 1.46%   |
| 1334    | 2         | 1.46%   |
| 533     | 2         | 1.46%   |
| 3600    | 1         | 0.73%   |
| 2666    | 1         | 0.73%   |
| 1332    | 1         | 0.73%   |
| 1066    | 1         | 0.73%   |
| 975     | 1         | 0.73%   |
| 400     | 1         | 0.73%   |
| Unknown | 1         | 0.73%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart_bsd/printer_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 50%     |
| Canon       | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart_bsd/printer_model.svg)


| Model               | Computers | Percent |
|---------------------|-----------|---------|
| Seiko Epson Printer | 1         | 50%     |
| Canon LBP2900       | 1         | 50%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart_bsd/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart_bsd/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 110 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart_bsd/camera_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 18        | 32.14%  |
| Microdia                      | 7         | 12.5%   |
| Realtek Semiconductor         | 6         | 10.71%  |
| IMC Networks                  | 6         | 10.71%  |
| Sunplus Innovation Technology | 5         | 8.93%   |
| Suyin                         | 3         | 5.36%   |
| Logitech                      | 3         | 5.36%   |
| Z-Star Microelectronics       | 1         | 1.79%   |
| Valve Software                | 1         | 1.79%   |
| Syntek                        | 1         | 1.79%   |
| Silicon Motion                | 1         | 1.79%   |
| Quanta                        | 1         | 1.79%   |
| Lite-On Technology            | 1         | 1.79%   |
| Lenovo                        | 1         | 1.79%   |
| Acer                          | 1         | 1.79%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Chicony Integrated Camera                 | 4         | 7.14%   |
| IMC Networks Integrated Camera            | 3         | 5.36%   |
| Realtek Integrated_Webcam_HD              | 2         | 3.57%   |
| Microdia Integrated Webcam                | 2         | 3.57%   |
| Chicony Lenovo Integrated Camera (0.3MP)  | 2         | 3.57%   |
| Chicony HD WebCam                         | 2         | 3.57%   |
| Chicony Chicony USB2.0 Camera             | 2         | 3.57%   |
| Z-Star Namuga 1.3M Webcam                 | 1         | 1.79%   |
| Valve Software 3D Camera                  | 1         | 1.79%   |
| Syntek Lenovo EasyCamera                  | 1         | 1.79%   |
| Suyin Integrated Camera                   | 1         | 1.79%   |
| Suyin HP Webcam-101                       | 1         | 1.79%   |
| Suyin Acer Crystal Eye webcam             | 1         | 1.79%   |
| Sunplus Laptop_Integrated_Webcam_FHD      | 1         | 1.79%   |
| Sunplus Laptop Integrated Webcam HD       | 1         | 1.79%   |
| Sunplus Integrated_Webcam_HD              | 1         | 1.79%   |
| Sunplus Integrated Camera                 | 1         | 1.79%   |
| Sunplus Dell HD Webcam                    | 1         | 1.79%   |
| Silicon Motion Web Camera                 | 1         | 1.79%   |
| Realtek USB 2 Webcam                      | 1         | 1.79%   |
| Realtek Lenovo EasyCamera                 | 1         | 1.79%   |
| Realtek Integrated Webcam HD              | 1         | 1.79%   |
| Realtek HP 2.0MP High Definition Webcam   | 1         | 1.79%   |
| Quanta HD Webcam                          | 1         | 1.79%   |
| Microdia Laptop_Integrated_Webcam_2M      | 1         | 1.79%   |
| Microdia Laptop_Integrated_Webcam_0.3M    | 1         | 1.79%   |
| Microdia Integrated_Webcam_HD             | 1         | 1.79%   |
| Microdia Integrated Webcam HD             | 1         | 1.79%   |
| Microdia Dell Laptop Integrated Webcam HD | 1         | 1.79%   |
| Logitech Webcam C270                      | 1         | 1.79%   |
| Logitech HD Webcam C615                   | 1         | 1.79%   |
| Logitech HD Pro Webcam C920               | 1         | 1.79%   |
| Lite-On HP TrueVision HD Camera           | 1         | 1.79%   |
| Lenovo Integrated Webcam [R5U877]         | 1         | 1.79%   |
| IMC Networks UVC VGA Webcam               | 1         | 1.79%   |
| IMC Networks USB2.0 UVC HD Webcam         | 1         | 1.79%   |
| IMC Networks EasyCamera                   | 1         | 1.79%   |
| Chicony USB2.0 HD UVC WebCam              | 1         | 1.79%   |
| Chicony TOSHIBA Web Camera - HD           | 1         | 1.79%   |
| Chicony Realtek DMFT - RGB                | 1         | 1.79%   |
| Chicony Lenovo EasyCamera                 | 1         | 1.79%   |
| Chicony HP Wide Vision HD Camera          | 1         | 1.79%   |
| Chicony HP Universal Camera               | 1         | 1.79%   |
| Chicony HP TrueVision HD Camera           | 1         | 1.79%   |
| Chicony Chicony USB 2.0 Camera            | 1         | 1.79%   |
| Acer Integrated Camera                    | 1         | 1.79%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 27.27%  |
| Synaptics                  | 3         | 27.27%  |
| Shenzhen Goodix Technology | 2         | 18.18%  |
| Upek                       | 1         | 9.09%   |
| Broadcom                   | 1         | 9.09%   |
| AuthenTec                  | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                                              | 2         | 18.18%  |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 1         | 9.09%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 1         | 9.09%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 1         | 9.09%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 1         | 9.09%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 1         | 9.09%   |
| Shenzhen Goodix  FingerPrint Device                                          | 1         | 9.09%   |
| Shenzhen Goodix Fingerprint Reader                                           | 1         | 9.09%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 9.09%   |
| AuthenTec AuthenTec Inc. AES1660                                             | 1         | 9.09%   |

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
| 1     | 50        | 35.71%  |
| 0     | 39        | 27.86%  |
| 2     | 31        | 22.14%  |
| 3     | 14        | 10%     |
| 4     | 5         | 3.57%   |
| 5     | 1         | 0.71%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 79        | 46.47%  |
| Net/wireless             | 28        | 16.47%  |
| Bluetooth                | 21        | 12.35%  |
| Firewire controller      | 13        | 7.65%   |
| Fingerprint reader       | 11        | 6.47%   |
| Card reader              | 11        | 6.47%   |
| Network                  | 2         | 1.18%   |
| Net/ethernet             | 2         | 1.18%   |
| Storage/ide              | 1         | 0.59%   |
| Storage                  | 1         | 0.59%   |
| Sound                    | 1         | 0.59%   |

