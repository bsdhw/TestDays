BSD in Sweden - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for BSD in Sweden.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Sweden/Desktop/README.md) and [notebooks](/Location/Sweden/Notebook/README.md).

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

Total: 217

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| CWWK          | MINIPC-G12                  | Desktop     | [4806dc7d9a](https://bsd-hardware.info/?probe=4806dc7d9a) | Apr 29, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [692df89c1f](https://bsd-hardware.info/?probe=692df89c1f) | Apr 26, 2023 |
| AZW           | GK55                        | Desktop     | [31a99b9d2a](https://bsd-hardware.info/?probe=31a99b9d2a) | Apr 25, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [a4bc168937](https://bsd-hardware.info/?probe=a4bc168937) | Apr 22, 2023 |
| AZW           | GK55                        | Desktop     | [cc5a32800f](https://bsd-hardware.info/?probe=cc5a32800f) | Apr 14, 2023 |
| HP            | 1998                        | Desktop     | [bc67c37f5f](https://bsd-hardware.info/?probe=bc67c37f5f) | Apr 04, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING       | Desktop     | [ebbd75883c](https://bsd-hardware.info/?probe=ebbd75883c) | Mar 17, 2023 |
| DFI           | CM100-C                     | Desktop     | [c34832095b](https://bsd-hardware.info/?probe=c34832095b) | Mar 15, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [23f9004191](https://bsd-hardware.info/?probe=23f9004191) | Mar 13, 2023 |
| AMI           | MNHO-048                    | Desktop     | [ebd90b78c1](https://bsd-hardware.info/?probe=ebd90b78c1) | Mar 12, 2023 |
| AMI           | MNHO-048                    | Desktop     | [52cdeb023e](https://bsd-hardware.info/?probe=52cdeb023e) | Mar 12, 2023 |
| PC Engines    | APU3                        | Desktop     | [c8008161b0](https://bsd-hardware.info/?probe=c8008161b0) | Mar 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [e4b77410c6](https://bsd-hardware.info/?probe=e4b77410c6) | Mar 08, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [31ed952f9c](https://bsd-hardware.info/?probe=31ed952f9c) | Mar 06, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [732a635016](https://bsd-hardware.info/?probe=732a635016) | Mar 06, 2023 |
| Supermicro    | X11SSH-LN4F                 | Server      | [7ab6080dfe](https://bsd-hardware.info/?probe=7ab6080dfe) | Feb 24, 2023 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [d04d402809](https://bsd-hardware.info/?probe=d04d402809) | Feb 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [44ac3b2832](https://bsd-hardware.info/?probe=44ac3b2832) | Feb 13, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [96fa5325d1](https://bsd-hardware.info/?probe=96fa5325d1) | Feb 11, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [d49da87ce9](https://bsd-hardware.info/?probe=d49da87ce9) | Feb 07, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [a98d28355d](https://bsd-hardware.info/?probe=a98d28355d) | Feb 05, 2023 |
| Star Labs     | StarBook                    | Notebook    | [d222f381b0](https://bsd-hardware.info/?probe=d222f381b0) | Jan 23, 2023 |
| Star Labs     | StarBook                    | Notebook    | [045d4bb6e8](https://bsd-hardware.info/?probe=045d4bb6e8) | Jan 23, 2023 |
| ASUSTek       | EB1035                      | All in one  | [7e39e23232](https://bsd-hardware.info/?probe=7e39e23232) | Jan 21, 2023 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [c2100f1789](https://bsd-hardware.info/?probe=c2100f1789) | Jan 14, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [3d2101dc79](https://bsd-hardware.info/?probe=3d2101dc79) | Jan 14, 2023 |
| HP            | 82A1                        | Desktop     | [2d7d9105f7](https://bsd-hardware.info/?probe=2d7d9105f7) | Jan 13, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [b53cd12326](https://bsd-hardware.info/?probe=b53cd12326) | Jan 12, 2023 |
| Gigabyte      | G31M-ES2C                   | Desktop     | [8353660219](https://bsd-hardware.info/?probe=8353660219) | Jan 08, 2023 |
| ASRock        | E3C226D2I                   | Desktop     | [5dfcf8051d](https://bsd-hardware.info/?probe=5dfcf8051d) | Jan 06, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [21c60a4db8](https://bsd-hardware.info/?probe=21c60a4db8) | Jan 04, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [7a86ed2309](https://bsd-hardware.info/?probe=7a86ed2309) | Jan 01, 2023 |
| Lenovo        | IdeaPad L340-17IWL 81M0     | Notebook    | [22c4a06468](https://bsd-hardware.info/?probe=22c4a06468) | Dec 31, 2022 |
| Lenovo        | 30D9 SDK0J40700 WIN 3258... | Desktop     | [ac867149f2](https://bsd-hardware.info/?probe=ac867149f2) | Dec 31, 2022 |
| CompuLab      | SBC-fit-PC4                 | Mini pc     | [c781bd46dc](https://bsd-hardware.info/?probe=c781bd46dc) | Dec 30, 2022 |
| Unknown       | Unknown                     | Desktop     | [b4d44b0018](https://bsd-hardware.info/?probe=b4d44b0018) | Dec 26, 2022 |
| ACMA          | X8SIE                       | Desktop     | [01898b2ffb](https://bsd-hardware.info/?probe=01898b2ffb) | Dec 21, 2022 |
| PC Engines    | APU3                        | Desktop     | [5597cca988](https://bsd-hardware.info/?probe=5597cca988) | Dec 17, 2022 |
| Supermicro    | X10SLL-F                    | Server      | [7d80c62813](https://bsd-hardware.info/?probe=7d80c62813) | Dec 09, 2022 |
| Supermicro    | X10SLL-F                    | Server      | [b2720b8b88](https://bsd-hardware.info/?probe=b2720b8b88) | Dec 08, 2022 |
| ACMA          | X8SIE                       | Desktop     | [361e4ccc04](https://bsd-hardware.info/?probe=361e4ccc04) | Dec 05, 2022 |
| ACMA          | X8SIE                       | Desktop     | [532b81e55f](https://bsd-hardware.info/?probe=532b81e55f) | Nov 29, 2022 |
| ACMA          | X8SIE                       | Desktop     | [d0112d027b](https://bsd-hardware.info/?probe=d0112d027b) | Nov 28, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [e850e0ae9c](https://bsd-hardware.info/?probe=e850e0ae9c) | Nov 28, 2022 |
| Toshiba       | TECRA Z40-C-12Z             | Notebook    | [149e5c3de3](https://bsd-hardware.info/?probe=149e5c3de3) | Nov 28, 2022 |
| Intel         | CRESCENTBAY                 | Desktop     | [bd1f1fa769](https://bsd-hardware.info/?probe=bd1f1fa769) | Nov 26, 2022 |
| Gigabyte      | G31M-ES2C                   | Desktop     | [2959091a59](https://bsd-hardware.info/?probe=2959091a59) | Nov 25, 2022 |
| Lenovo        | ThinkServer RS140           | Desktop     | [0dd05e08aa](https://bsd-hardware.info/?probe=0dd05e08aa) | Nov 12, 2022 |
| Lenovo        | ThinkServer RS140           | Desktop     | [b2b1509adf](https://bsd-hardware.info/?probe=b2b1509adf) | Nov 11, 2022 |
| MSI           | Z370I GAMING PRO CARBON ... | Desktop     | [dd9f7679b5](https://bsd-hardware.info/?probe=dd9f7679b5) | Nov 09, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [970443066b](https://bsd-hardware.info/?probe=970443066b) | Nov 07, 2022 |
| Cisco         | ASA5515 A0                  | Desktop     | [7f848d7c57](https://bsd-hardware.info/?probe=7f848d7c57) | Oct 22, 2022 |
| ASUSTek       | P5L-VM 1394                 | Desktop     | [d7c3749eba](https://bsd-hardware.info/?probe=d7c3749eba) | Oct 13, 2022 |
| HP            | 8103 A01                    | Mini pc     | [f187229469](https://bsd-hardware.info/?probe=f187229469) | Oct 09, 2022 |
| Dell          | 05KX61 A04                  | Server      | [f1232f79c4](https://bsd-hardware.info/?probe=f1232f79c4) | Sep 25, 2022 |
| HP            | Unknown                     | Notebook    | [7bd69ee984](https://bsd-hardware.info/?probe=7bd69ee984) | Aug 29, 2022 |
| AOpen         | iBTMx-DS R1.04 55DED10A0... | Desktop     | [a480263c28](https://bsd-hardware.info/?probe=a480263c28) | Aug 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [e5efeb3781](https://bsd-hardware.info/?probe=e5efeb3781) | Aug 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [9d1eb045e5](https://bsd-hardware.info/?probe=9d1eb045e5) | Aug 20, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [efd9ee1d33](https://bsd-hardware.info/?probe=efd9ee1d33) | Aug 10, 2022 |
| ASUSTek       | CM6731_CM6431_CM6331        | Desktop     | [6e40b41bc3](https://bsd-hardware.info/?probe=6e40b41bc3) | Aug 04, 2022 |
| Gigabyte      | Z87M-D3H                    | Desktop     | [59ae6fc283](https://bsd-hardware.info/?probe=59ae6fc283) | Jul 26, 2022 |
| HP            | ProBook 4730s               | Notebook    | [e70725dd32](https://bsd-hardware.info/?probe=e70725dd32) | Jul 23, 2022 |
| Supermicro    | X11SSV-M4                   | Desktop     | [444d9ed75e](https://bsd-hardware.info/?probe=444d9ed75e) | Jul 04, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [ea22a644f6](https://bsd-hardware.info/?probe=ea22a644f6) | Jul 04, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [dfd321896a](https://bsd-hardware.info/?probe=dfd321896a) | Jun 14, 2022 |
| PC Engines    | APU                         | Desktop     | [f41e59d78b](https://bsd-hardware.info/?probe=f41e59d78b) | Jun 11, 2022 |
| Supermicro    | X11SSH-LN4F                 | Server      | [d3ba57cf29](https://bsd-hardware.info/?probe=d3ba57cf29) | Jun 01, 2022 |
| MSI           | MS-7369                     | Desktop     | [c2c6bd80e8](https://bsd-hardware.info/?probe=c2c6bd80e8) | May 13, 2022 |
| Dell          | 05Y15N A06                  | Server      | [047ecc3a64](https://bsd-hardware.info/?probe=047ecc3a64) | May 13, 2022 |
| Intel         | CRESCENTBAY                 | Desktop     | [0d11258d3a](https://bsd-hardware.info/?probe=0d11258d3a) | Apr 22, 2022 |
| HP            | 8103 A01                    | Mini pc     | [b3d4d3c2db](https://bsd-hardware.info/?probe=b3d4d3c2db) | Apr 16, 2022 |
| Shuttle       | SH570                       | Desktop     | [08e2af8890](https://bsd-hardware.info/?probe=08e2af8890) | Apr 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [2e4a7843ab](https://bsd-hardware.info/?probe=2e4a7843ab) | Apr 14, 2022 |
| ASUSTek       | UX305UA                     | Notebook    | [3fb1786193](https://bsd-hardware.info/?probe=3fb1786193) | Apr 04, 2022 |
| Dell          | 0GFKVD A00                  | Server      | [2b14dd2a23](https://bsd-hardware.info/?probe=2b14dd2a23) | Mar 29, 2022 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [04e77555a2](https://bsd-hardware.info/?probe=04e77555a2) | Mar 24, 2022 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | Desktop     | [23055a27d9](https://bsd-hardware.info/?probe=23055a27d9) | Mar 23, 2022 |
| Lenovo        | ThinkPad T460s 20FAS4KH0... | Notebook    | [dbb0e378d5](https://bsd-hardware.info/?probe=dbb0e378d5) | Mar 17, 2022 |
| AOpen         | iBTMx-DS R1.04 55DED10A0... | Desktop     | [8faec8e7ed](https://bsd-hardware.info/?probe=8faec8e7ed) | Mar 10, 2022 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [a2c59d02ee](https://bsd-hardware.info/?probe=a2c59d02ee) | Mar 08, 2022 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [099edf57ae](https://bsd-hardware.info/?probe=099edf57ae) | Mar 08, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [1daab68f1f](https://bsd-hardware.info/?probe=1daab68f1f) | Mar 04, 2022 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [8016115ff1](https://bsd-hardware.info/?probe=8016115ff1) | Feb 24, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [5d39002367](https://bsd-hardware.info/?probe=5d39002367) | Feb 21, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [807a29112e](https://bsd-hardware.info/?probe=807a29112e) | Feb 19, 2022 |
| Gigabyte      | G31M-ES2C                   | Desktop     | [5f27a360e4](https://bsd-hardware.info/?probe=5f27a360e4) | Feb 10, 2022 |
| Gigabyte      | Z68X-UD7-B3                 | Desktop     | [37cc045649](https://bsd-hardware.info/?probe=37cc045649) | Jan 28, 2022 |
| MSI           | MS-7C56                     | Desktop     | [962ac1c7b0](https://bsd-hardware.info/?probe=962ac1c7b0) | Jan 20, 2022 |
| Gigabyte      | Z68X-UD7-B3                 | Desktop     | [082da3ef7f](https://bsd-hardware.info/?probe=082da3ef7f) | Jan 19, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [26ccd8e3c5](https://bsd-hardware.info/?probe=26ccd8e3c5) | Jan 16, 2022 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [e0e7b21668](https://bsd-hardware.info/?probe=e0e7b21668) | Jan 09, 2022 |
| ASUSTek       | P8H77-I                     | Desktop     | [e15d67e8db](https://bsd-hardware.info/?probe=e15d67e8db) | Jan 08, 2022 |
| ASRock        | E3C226D2I                   | Desktop     | [a31265ae13](https://bsd-hardware.info/?probe=a31265ae13) | Jan 07, 2022 |
| ASUSTek       | P8H77-I                     | Desktop     | [27960088a3](https://bsd-hardware.info/?probe=27960088a3) | Jan 05, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [1684618e22](https://bsd-hardware.info/?probe=1684618e22) | Jan 01, 2022 |
| HP            | ProLiant DL360 G5           | Server      | [8eaea61913](https://bsd-hardware.info/?probe=8eaea61913) | Dec 29, 2021 |
| Lenovo        | ThinkServer RS140           | Desktop     | [e28b542e9e](https://bsd-hardware.info/?probe=e28b542e9e) | Dec 23, 2021 |
| HP            | ProLiant DL360p Gen8        | Server      | [fda420b944](https://bsd-hardware.info/?probe=fda420b944) | Dec 20, 2021 |
| HPE           | ProLiant DL380 Gen10        | Server      | [d1e6144816](https://bsd-hardware.info/?probe=d1e6144816) | Dec 20, 2021 |
| Intel         | DH61AG AAG81491-600         | Desktop     | [fd9659a9fe](https://bsd-hardware.info/?probe=fd9659a9fe) | Dec 15, 2021 |
| ASUSTek       | Rampage Formula             | Desktop     | [34633c2ca8](https://bsd-hardware.info/?probe=34633c2ca8) | Dec 02, 2021 |
| MSI           | MS-7C56                     | Desktop     | [d4e3f14ad4](https://bsd-hardware.info/?probe=d4e3f14ad4) | Nov 23, 2021 |
| Lenovo        | ThinkPad T420 4236MBG       | Notebook    | [0391bf9ea4](https://bsd-hardware.info/?probe=0391bf9ea4) | Nov 14, 2021 |
| Dell          | 0N28XX A02                  | Server      | [b640c5a644](https://bsd-hardware.info/?probe=b640c5a644) | Nov 10, 2021 |
| ASUSTek       | K52Jc                       | Notebook    | [92b975763f](https://bsd-hardware.info/?probe=92b975763f) | Nov 08, 2021 |
| ASUSTek       | K52Jc                       | Notebook    | [fc919c73e3](https://bsd-hardware.info/?probe=fc919c73e3) | Nov 07, 2021 |
| Google        | Grunt                       | Notebook    | [aa07a1dd40](https://bsd-hardware.info/?probe=aa07a1dd40) | Nov 05, 2021 |
| Google        | Grunt                       | Notebook    | [c87e033731](https://bsd-hardware.info/?probe=c87e033731) | Nov 01, 2021 |
| AMI           | PEISIA E3845 VER1.0         | Desktop     | [a6b7ceeada](https://bsd-hardware.info/?probe=a6b7ceeada) | Oct 20, 2021 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [4fdd90135a](https://bsd-hardware.info/?probe=4fdd90135a) | Oct 20, 2021 |
| Google        | Grunt                       | Notebook    | [e6d4421a4d](https://bsd-hardware.info/?probe=e6d4421a4d) | Oct 16, 2021 |
| Google        | Grunt                       | Notebook    | [ee9b2d7ad3](https://bsd-hardware.info/?probe=ee9b2d7ad3) | Oct 15, 2021 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [f57ea5540f](https://bsd-hardware.info/?probe=f57ea5540f) | Oct 13, 2021 |
| Google        | Grunt                       | Notebook    | [e76c73d9a3](https://bsd-hardware.info/?probe=e76c73d9a3) | Oct 11, 2021 |
| Acer          | Aspire A315-56              | Notebook    | [03ca802f4b](https://bsd-hardware.info/?probe=03ca802f4b) | Oct 02, 2021 |
| Gigabyte      | Z87M-D3H                    | Desktop     | [8cb8c4dbf4](https://bsd-hardware.info/?probe=8cb8c4dbf4) | Oct 01, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [1ef37663db](https://bsd-hardware.info/?probe=1ef37663db) | Sep 01, 2021 |
| Dell          | 0M877N A01                  | Server      | [1585126252](https://bsd-hardware.info/?probe=1585126252) | Aug 18, 2021 |
| Lenovo        | 3098 0B98401 PRO            | Desktop     | [4737978dbf](https://bsd-hardware.info/?probe=4737978dbf) | Aug 18, 2021 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [bd4b0f0700](https://bsd-hardware.info/?probe=bd4b0f0700) | Aug 17, 2021 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [04d9692802](https://bsd-hardware.info/?probe=04d9692802) | Aug 09, 2021 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [24df2da075](https://bsd-hardware.info/?probe=24df2da075) | Aug 08, 2021 |
| PC Engines    | apu4                        | Desktop     | [815567b75c](https://bsd-hardware.info/?probe=815567b75c) | Aug 02, 2021 |
| PC Engines    | apu4                        | Desktop     | [77fa195d5e](https://bsd-hardware.info/?probe=77fa195d5e) | Aug 02, 2021 |
| Lenovo        | ThinkPad X250 20CLS4JH00    | Notebook    | [89a74889ae](https://bsd-hardware.info/?probe=89a74889ae) | Aug 02, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [c577b93feb](https://bsd-hardware.info/?probe=c577b93feb) | Jul 24, 2021 |
| Lenovo        | ThinkPad T400 2767WSB       | Notebook    | [36ce1d1e00](https://bsd-hardware.info/?probe=36ce1d1e00) | Jul 24, 2021 |
| ASUSTek       | P8H77-I                     | Desktop     | [52e8a39fb1](https://bsd-hardware.info/?probe=52e8a39fb1) | Jul 19, 2021 |
| Lenovo        | ThinkPad T420 4236MBG       | Notebook    | [5b43300a93](https://bsd-hardware.info/?probe=5b43300a93) | Jul 13, 2021 |
| Protectli     | FW4B Ver                    | Desktop     | [452a8558c0](https://bsd-hardware.info/?probe=452a8558c0) | Jul 09, 2021 |
| Dell          | 05XGC8 A01                  | Desktop     | [b9841b1272](https://bsd-hardware.info/?probe=b9841b1272) | Jul 08, 2021 |
| Unknown       | Unknown                     | Desktop     | [935263c5a0](https://bsd-hardware.info/?probe=935263c5a0) | Jul 03, 2021 |
| HP            | 82A1                        | Desktop     | [dba57fb77f](https://bsd-hardware.info/?probe=dba57fb77f) | Jun 30, 2021 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [18e34c37cd](https://bsd-hardware.info/?probe=18e34c37cd) | Jun 28, 2021 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [3d717eec8f](https://bsd-hardware.info/?probe=3d717eec8f) | Jun 25, 2021 |
| Dell          | 0P03DX A03                  | Desktop     | [b2f0c90d79](https://bsd-hardware.info/?probe=b2f0c90d79) | Jun 24, 2021 |
| Microsoft     | Surface Pro 7               | Tablet      | [1b8d66e5f0](https://bsd-hardware.info/?probe=1b8d66e5f0) | Jun 22, 2021 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [5091db2ace](https://bsd-hardware.info/?probe=5091db2ace) | Jun 16, 2021 |
| MSI           | Z97 GAMING 3                | Desktop     | [c6d7626b29](https://bsd-hardware.info/?probe=c6d7626b29) | Jun 12, 2021 |
| ASRock        | X99 WS                      | Desktop     | [201a7417a5](https://bsd-hardware.info/?probe=201a7417a5) | Jun 11, 2021 |
| Dell          | 0NR282 A00                  | Server      | [f3854ba6e8](https://bsd-hardware.info/?probe=f3854ba6e8) | Jun 07, 2021 |
| Sony          | SVP1322M1EBI                | Notebook    | [23316d0f2b](https://bsd-hardware.info/?probe=23316d0f2b) | May 29, 2021 |
| PC Engines    | APU2                        | Desktop     | [2070f50252](https://bsd-hardware.info/?probe=2070f50252) | May 26, 2021 |
| ASUSTek       | Z87-DELUXE/DUAL             | Desktop     | [69a811cae5](https://bsd-hardware.info/?probe=69a811cae5) | May 25, 2021 |
| ASUSTek       | SABERTOOTH Z87              | Desktop     | [586a4db247](https://bsd-hardware.info/?probe=586a4db247) | May 20, 2021 |
| ASUSTek       | SABERTOOTH Z87              | Desktop     | [eb0c02a451](https://bsd-hardware.info/?probe=eb0c02a451) | May 19, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [62b9ea2794](https://bsd-hardware.info/?probe=62b9ea2794) | May 14, 2021 |
| Dell          | Latitude 5500               | Notebook    | [2538b038ed](https://bsd-hardware.info/?probe=2538b038ed) | May 08, 2021 |
| ASRock        | X99 WS                      | Desktop     | [eb20367455](https://bsd-hardware.info/?probe=eb20367455) | May 05, 2021 |
| Dell          | 0NR282 A00                  | Server      | [09082703f8](https://bsd-hardware.info/?probe=09082703f8) | Apr 29, 2021 |
| Dell          | 03X6X0 A01                  | Server      | [9f13074b78](https://bsd-hardware.info/?probe=9f13074b78) | Apr 24, 2021 |
| ASUSTek       | All Series                  | Desktop     | [ef6afe88d7](https://bsd-hardware.info/?probe=ef6afe88d7) | Apr 17, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [ad564817c9](https://bsd-hardware.info/?probe=ad564817c9) | Apr 11, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [0712c3048c](https://bsd-hardware.info/?probe=0712c3048c) | Apr 11, 2021 |
| Dell          | 09T7VV A05                  | Server      | [668c05619b](https://bsd-hardware.info/?probe=668c05619b) | Apr 09, 2021 |
| Dell          | 09T7VV A05                  | Server      | [917ab2c4e6](https://bsd-hardware.info/?probe=917ab2c4e6) | Apr 06, 2021 |
| Shuttle       | FH170                       | Desktop     | [d36fccf7b7](https://bsd-hardware.info/?probe=d36fccf7b7) | Apr 01, 2021 |
| Dell          | 0F0XJ6 A02                  | Server      | [052c1899c8](https://bsd-hardware.info/?probe=052c1899c8) | Mar 29, 2021 |
| Dell          | 0F0XJ6 A02                  | Server      | [806c6f796e](https://bsd-hardware.info/?probe=806c6f796e) | Mar 29, 2021 |
| MSI           | IONA                        | Desktop     | [5f857882ff](https://bsd-hardware.info/?probe=5f857882ff) | Mar 25, 2021 |
| Unknown       | Unknown                     | Desktop     | [93ef7a4b6e](https://bsd-hardware.info/?probe=93ef7a4b6e) | Mar 22, 2021 |
| ASUSTek       | All Series                  | Desktop     | [c5bc64e4e9](https://bsd-hardware.info/?probe=c5bc64e4e9) | Mar 22, 2021 |
| ASUSTek       | All Series                  | Desktop     | [700ff7d378](https://bsd-hardware.info/?probe=700ff7d378) | Mar 22, 2021 |
| HP            | 8054                        | Desktop     | [1db522699a](https://bsd-hardware.info/?probe=1db522699a) | Mar 21, 2021 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [ddc66bc2fb](https://bsd-hardware.info/?probe=ddc66bc2fb) | Mar 20, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [a5833ca2c9](https://bsd-hardware.info/?probe=a5833ca2c9) | Mar 18, 2021 |
| HP            | 8053                        | Desktop     | [b7ebdfe456](https://bsd-hardware.info/?probe=b7ebdfe456) | Mar 17, 2021 |
| ASUSTek       | P8H67-M                     | Desktop     | [e95d6c6972](https://bsd-hardware.info/?probe=e95d6c6972) | Mar 17, 2021 |
| Lenovo        | ThinkPad X395 20NL001SMX    | Notebook    | [cd016e96ee](https://bsd-hardware.info/?probe=cd016e96ee) | Mar 17, 2021 |
| ADI           | MinnowBoard Turbot          | Desktop     | [ebd85cee04](https://bsd-hardware.info/?probe=ebd85cee04) | Mar 14, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [93c9f14bf0](https://bsd-hardware.info/?probe=93c9f14bf0) | Mar 12, 2021 |
| Dell          | 0XCR8D A02                  | Desktop     | [af5d6a85ef](https://bsd-hardware.info/?probe=af5d6a85ef) | Mar 09, 2021 |
| Dell          | 00V62H A00                  | Desktop     | [a9f921e29b](https://bsd-hardware.info/?probe=a9f921e29b) | Mar 03, 2021 |
| Intel         | DQ67SW AAG12527-306         | Desktop     | [a4fb7ae326](https://bsd-hardware.info/?probe=a4fb7ae326) | Mar 02, 2021 |
| Unknown       | Unknown                     | Desktop     | [b00dc0301a](https://bsd-hardware.info/?probe=b00dc0301a) | Feb 27, 2021 |
| Lenovo        | 3098 0B98401 PRO            | Desktop     | [da62664934](https://bsd-hardware.info/?probe=da62664934) | Feb 23, 2021 |
| Dell          | Latitude E7240              | Notebook    | [e42e579971](https://bsd-hardware.info/?probe=e42e579971) | Feb 22, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [7968c7d2dd](https://bsd-hardware.info/?probe=7968c7d2dd) | Feb 16, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [f8bdec0105](https://bsd-hardware.info/?probe=f8bdec0105) | Feb 14, 2021 |
| Lenovo        | 3098 0B98401 PRO            | Desktop     | [5ca10a4860](https://bsd-hardware.info/?probe=5ca10a4860) | Feb 14, 2021 |
| Lenovo        | 3098 0B98401 PRO            | Desktop     | [263a74d1ce](https://bsd-hardware.info/?probe=263a74d1ce) | Feb 12, 2021 |
| ASUSTek       | S551LN                      | Notebook    | [42792115e3](https://bsd-hardware.info/?probe=42792115e3) | Feb 11, 2021 |
| Toshiba       | Satellite L450              | Notebook    | [eb44256bfe](https://bsd-hardware.info/?probe=eb44256bfe) | Feb 11, 2021 |
| Lenovo        | 3098 0B98401 PRO            | Desktop     | [508b3afc1c](https://bsd-hardware.info/?probe=508b3afc1c) | Feb 09, 2021 |
| Lenovo        | 3098 0B98401 PRO            | Desktop     | [8b9f162f70](https://bsd-hardware.info/?probe=8b9f162f70) | Feb 09, 2021 |
| Deciso        | Netboard A10 V2.1           | Desktop     | [dfb0240726](https://bsd-hardware.info/?probe=dfb0240726) | Feb 05, 2021 |
| PC Engines    | APU2                        | Desktop     | [8983ab6689](https://bsd-hardware.info/?probe=8983ab6689) | Feb 03, 2021 |
| HP            | 1905                        | Desktop     | [72ab5653d3](https://bsd-hardware.info/?probe=72ab5653d3) | Feb 03, 2021 |
| Microsoft     | Surface Go 2                | Tablet      | [69c8123ec6](https://bsd-hardware.info/?probe=69c8123ec6) | Feb 01, 2021 |
| HP            | 8103 A01                    | Mini pc     | [da8a373d43](https://bsd-hardware.info/?probe=da8a373d43) | Jan 30, 2021 |
| ADI           | MinnowBoard Turbot          | Desktop     | [137ff14192](https://bsd-hardware.info/?probe=137ff14192) | Jan 29, 2021 |
| Unknown       | Unknown                     | Desktop     | [920259bf95](https://bsd-hardware.info/?probe=920259bf95) | Jan 28, 2021 |
| HP            | 8103 A01                    | Mini pc     | [55c7d22c4d](https://bsd-hardware.info/?probe=55c7d22c4d) | Jan 28, 2021 |
| HP            | ProLiant DL380 Gen9         | Server      | [c2bb148e8a](https://bsd-hardware.info/?probe=c2bb148e8a) | Jan 28, 2021 |
| Dell          | 06G98X A02                  | Server      | [b062e0f4e4](https://bsd-hardware.info/?probe=b062e0f4e4) | Jan 28, 2021 |
| Dell          | 0WCJNT A06                  | Server      | [4710d6000d](https://bsd-hardware.info/?probe=4710d6000d) | Jan 28, 2021 |
| ASUSTek       | All Series                  | Desktop     | [7ebe6eee38](https://bsd-hardware.info/?probe=7ebe6eee38) | Jan 25, 2021 |
| ADI           | MinnowBoard Turbot          | Desktop     | [e2fbc5f326](https://bsd-hardware.info/?probe=e2fbc5f326) | Jan 21, 2021 |
| ADI           | MinnowBoard Turbot          | Desktop     | [0b8e4d0630](https://bsd-hardware.info/?probe=0b8e4d0630) | Jan 21, 2021 |
| Dell          | 00V62H A00                  | Desktop     | [bd3877826c](https://bsd-hardware.info/?probe=bd3877826c) | Jan 20, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [3a9d5d1a1d](https://bsd-hardware.info/?probe=3a9d5d1a1d) | Jan 20, 2021 |
| PC Engines    | APU2                        | Desktop     | [ecf35d22c4](https://bsd-hardware.info/?probe=ecf35d22c4) | Jan 12, 2021 |
| Lenovo        | ThinkPad X201 3680FAG       | Notebook    | [1ba69078df](https://bsd-hardware.info/?probe=1ba69078df) | Dec 06, 2020 |
| PC Engines    | APU2                        | Desktop     | [2e6256a0ab](https://bsd-hardware.info/?probe=2e6256a0ab) | Nov 23, 2020 |
| PC Engines    | APU2                        | Desktop     | [65de6946d3](https://bsd-hardware.info/?probe=65de6946d3) | Nov 23, 2020 |
| PC Engines    | APU2                        | Desktop     | [b4f5d7d344](https://bsd-hardware.info/?probe=b4f5d7d344) | Nov 16, 2020 |
| HP            | ProLiant ML30 Gen9          | Desktop     | [ecaec68cdb](https://bsd-hardware.info/?probe=ecaec68cdb) | Oct 27, 2020 |
| Intel         | NUC5CPYB                    | Mini pc     | [1ec5c12f0b](https://bsd-hardware.info/?probe=1ec5c12f0b) | Oct 27, 2020 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [547b36ea62](https://bsd-hardware.info/?probe=547b36ea62) | Aug 19, 2020 |
| Lenovo        | ThinkPad W520 4284GN2       | Notebook    | [acb3ad955f](https://bsd-hardware.info/?probe=acb3ad955f) | Aug 06, 2020 |
| Lenovo        | ThinkPad L560 20F10032MS    | Notebook    | [bf2b792b64](https://bsd-hardware.info/?probe=bf2b792b64) | Aug 06, 2020 |
| Wistron       | ProLiant ML110 G6           | Desktop     | [0d2e0f44c1](https://bsd-hardware.info/?probe=0d2e0f44c1) | Aug 06, 2020 |
| Lenovo        | ThinkPad L560 20F10032MS    | Notebook    | [0aa6a9a921](https://bsd-hardware.info/?probe=0aa6a9a921) | Aug 06, 2020 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | Desktop     | [6245f1e175](https://bsd-hardware.info/?probe=6245f1e175) | Aug 06, 2020 |
| Unknown       | Unknown                     | Desktop     | [4e3b87cc6c](https://bsd-hardware.info/?probe=4e3b87cc6c) | Jun 01, 2020 |
| Gigabyte      | Z170X-UD5 TH-CF             | Desktop     | [2fc2952380](https://bsd-hardware.info/?probe=2fc2952380) | May 25, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| OPNsense 21.1     | 11        | 6.11%   |
| OPNsense 22.7.10  | 9         | 5%      |
| OPNsense 21.7.7   | 6         | 3.33%   |
| OPNsense 21.1.3   | 6         | 3.33%   |
| OpenBSD 6.8       | 6         | 3.33%   |
| OPNsense 21.1.5   | 5         | 2.78%   |
| OPNsense 21.1.2   | 5         | 2.78%   |
| OpenBSD 7.0       | 5         | 2.78%   |
| helloSystem 0.5.0 | 5         | 2.78%   |
| OPNsense 22.7.8   | 4         | 2.22%   |
| OPNsense 21.1.8   | 4         | 2.22%   |
| OPNsense 23.1.6   | 3         | 1.67%   |
| OPNsense 23.1.3   | 3         | 1.67%   |
| OPNsense 22.7.9   | 3         | 1.67%   |
| OPNsense 22.7.2   | 3         | 1.67%   |
| OPNsense 22.1.8   | 3         | 1.67%   |
| OPNsense 21.7.3   | 3         | 1.67%   |
| OPNsense 21.7.1   | 3         | 1.67%   |
| OPNsense 20.7.8   | 3         | 1.67%   |
| OpenBSD 6.9       | 3         | 1.67%   |
| helloSystem 0.8.0 | 3         | 1.67%   |
| helloSystem 0.7.0 | 3         | 1.67%   |
| FreeBSD 13.1-p5   | 3         | 1.67%   |
| FreeBSD 13.0-p7   | 3         | 1.67%   |
| FreeBSD 12.1-p8   | 3         | 1.67%   |
| OPNsense 23.1.2   | 2         | 1.11%   |
| OPNsense 23.1.1   | 2         | 1.11%   |
| OPNsense 23.1     | 2         | 1.11%   |
| OPNsense 22.7.7   | 2         | 1.11%   |
| OPNsense 22.7.6   | 2         | 1.11%   |
| OPNsense 22.1.9   | 2         | 1.11%   |
| OPNsense 22.1.6   | 2         | 1.11%   |
| OPNsense 22.1.3   | 2         | 1.11%   |
| OPNsense 22.1.1   | 2         | 1.11%   |
| OPNsense 21.7.6   | 2         | 1.11%   |
| OPNsense 21.7     | 2         | 1.11%   |
| OPNsense 21.1.7   | 2         | 1.11%   |
| OPNsense 21.1.6   | 2         | 1.11%   |
| OpenBSD 6.7       | 2         | 1.11%   |
| helloSystem 0.4.0 | 2         | 1.11%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 91        | 59.09%  |
| FreeBSD     | 27        | 17.53%  |
| OpenBSD     | 16        | 10.39%  |
| helloSystem | 14        | 9.09%   |
| GhostBSD    | 4         | 2.6%    |
| pfSense     | 1         | 0.65%   |
| FuryBSD     | 1         | 0.65%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| amd64  | 153       | 99.35%  |
| octeon | 1         | 0.65%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 105       | 67.31%  |
| helloDesktop | 15        | 9.62%   |
| fvwm         | 12        | 7.69%   |
| KDE5         | 10        | 6.41%   |
| MATE         | 5         | 3.21%   |
| XFCE         | 2         | 1.28%   |
| i3           | 2         | 1.28%   |
| xfwm         | 1         | 0.64%   |
| TWM          | 1         | 0.64%   |
| Mutter       | 1         | 0.64%   |
| LXQt         | 1         | 0.64%   |
| AwesomeWM    | 1         | 0.64%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 106       | 68.83%  |
| X11     | 48        | 31.17%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 119       | 75.8%   |
| SLiM    | 15        | 9.55%   |
| SDDM    | 10        | 6.37%   |
| LightDM | 7         | 4.46%   |
| GDM     | 4         | 2.55%   |
| XDM     | 2         | 1.27%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang           | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 107       | 68.59%  |
| en_US          | 24        | 15.38%  |
| C              | 15        | 9.62%   |
| sv_SE          | 4         | 2.56%   |
| sv_SE.US-ASCII | 1         | 0.64%   |
| sv             | 1         | 0.64%   |
| en_GB          | 1         | 0.64%   |
| en_CA          | 1         | 0.64%   |
| en_BE          | 1         | 0.64%   |
| en             | 1         | 0.64%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 131       | 83.97%  |
| BIOS | 25        | 16.03%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Ufs    | 79        | 50.97%  |
| Zfs    | 56        | 36.13%  |
| Ffs    | 16        | 10.32%  |
| Cd9660 | 4         | 2.58%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 141       | 89.81%  |
| MBR  | 16        | 10.19%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Dell                       | 19        | 12.34%  |
| Lenovo                     | 18        | 11.69%  |
| Hewlett-Packard            | 17        | 11.04%  |
| ASUSTek Computer           | 16        | 10.39%  |
| Unknown                    | 9         | 5.84%   |
| PC Engines                 | 8         | 5.19%   |
| Intel                      | 7         | 4.55%   |
| Gigabyte Technology        | 7         | 4.55%   |
| AMI                        | 7         | 4.55%   |
| Supermicro                 | 5         | 3.25%   |
| MSI                        | 5         | 3.25%   |
| Microsoft                  | 3         | 1.95%   |
| ASRock                     | 3         | 1.95%   |
| Toshiba                    | 2         | 1.3%    |
| Techvision                 | 2         | 1.3%    |
| Shuttle                    | 2         | 1.3%    |
| HPE                        | 2         | 1.3%    |
| Fujitsu                    | 2         | 1.3%    |
| Deciso                     | 2         | 1.3%    |
| ZOTAC                      | 1         | 0.65%   |
| Wistron                    | 1         | 0.65%   |
| Star Labs                  | 1         | 0.65%   |
| Sony                       | 1         | 0.65%   |
| ShenZhen MinWin Technology | 1         | 0.65%   |
| Protectli                  | 1         | 0.65%   |
| Google                     | 1         | 0.65%   |
| Fujitsu Siemens            | 1         | 0.65%   |
| DFI                        | 1         | 0.65%   |
| CWWK                       | 1         | 0.65%   |
| CompuLab                   | 1         | 0.65%   |
| Cisco                      | 1         | 0.65%   |
| AZW                        | 1         | 0.65%   |
| Apple                      | 1         | 0.65%   |
| AOpen                      | 1         | 0.65%   |
| ADI                        | 1         | 0.65%   |
| ACMA                       | 1         | 0.65%   |
| Acer                       | 1         | 0.65%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 10        | 6.49%   |
| AMI Aptio CRB                          | 5         | 3.25%   |
| PC Engines APU2                        | 4         | 2.6%    |
| HP t730 Thin Client                    | 3         | 1.95%   |
| ASUS All Series                        | 3         | 1.95%   |
| Techvision TVI7309X                    | 2         | 1.3%    |
| Supermicro X10SLL-F                    | 2         | 1.3%    |
| Supermicro Super Server                | 2         | 1.3%    |
| PC Engines apu4                        | 2         | 1.3%    |
| Microsoft Surface Pro 7                | 2         | 1.3%    |
| Intel CRESCENTBAY                      | 2         | 1.3%    |
| Dell PowerEdge R210 II                 | 2         | 1.3%    |
| Dell PowerEdge R210                    | 2         | 1.3%    |
| Dell OptiPlex 9020                     | 2         | 1.3%    |
| ZOTAC ZBOX-CI329NANO                   | 1         | 0.65%   |
| Wistron ProLiant ML110 G6              | 1         | 0.65%   |
| Toshiba TECRA Z40-C-12Z                | 1         | 0.65%   |
| Toshiba Satellite L450                 | 1         | 0.65%   |
| Supermicro SYS-1019S-MP                | 1         | 0.65%   |
| Star Labs StarBook                     | 1         | 0.65%   |
| Sony SVP1322M1EBI                      | 1         | 0.65%   |
| Shuttle SH570                          | 1         | 0.65%   |
| Shuttle DH170                          | 1         | 0.65%   |
| ShenZhen MinWin MW-NANO-APL-4L         | 1         | 0.65%   |
| Protectli FW4B                         | 1         | 0.65%   |
| PC Engines APU3                        | 1         | 0.65%   |
| PC Engines APU                         | 1         | 0.65%   |
| MSI WC776AA-UUW HPE-110sc              | 1         | 0.65%   |
| MSI MS-7C56                            | 1         | 0.65%   |
| MSI MS-7B43                            | 1         | 0.65%   |
| MSI MS-7918                            | 1         | 0.65%   |
| MSI MS-7369                            | 1         | 0.65%   |
| Microsoft Surface Go 2                 | 1         | 0.65%   |
| Lenovo V130-15IGM 81HL                 | 1         | 0.65%   |
| Lenovo ThinkPad X395 20NL001SMX        | 1         | 0.65%   |
| Lenovo ThinkPad X250 20CLS4JH00        | 1         | 0.65%   |
| Lenovo ThinkPad X201 3680FAG           | 1         | 0.65%   |
| Lenovo ThinkPad W520 4284GN2           | 1         | 0.65%   |
| Lenovo ThinkPad T470s W10DG 20JTS0W800 | 1         | 0.65%   |
| Lenovo ThinkPad T460s 20FAS4KH02       | 1         | 0.65%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Dell PowerEdge                 | 11        | 7.14%   |
| Unknown                        | 10        | 6.49%   |
| Lenovo ThinkPad                | 9         | 5.84%   |
| Dell OptiPlex                  | 5         | 3.25%   |
| AMI Aptio                      | 5         | 3.25%   |
| PC Engines APU2                | 4         | 2.6%    |
| Lenovo ThinkCentre             | 4         | 2.6%    |
| HP ProLiant                    | 4         | 2.6%    |
| Microsoft Surface              | 3         | 1.95%   |
| HP t730                        | 3         | 1.95%   |
| HP EliteDesk                   | 3         | 1.95%   |
| Dell Latitude                  | 3         | 1.95%   |
| ASUS All                       | 3         | 1.95%   |
| Techvision TVI7309X            | 2         | 1.3%    |
| Supermicro X10SLL-F            | 2         | 1.3%    |
| Supermicro Super               | 2         | 1.3%    |
| PC Engines apu4                | 2         | 1.3%    |
| Lenovo IdeaPad                 | 2         | 1.3%    |
| Intel CRESCENTBAY              | 2         | 1.3%    |
| HPE ProLiant                   | 2         | 1.3%    |
| ZOTAC ZBOX-CI329NANO           | 1         | 0.65%   |
| Wistron ProLiant               | 1         | 0.65%   |
| Toshiba TECRA                  | 1         | 0.65%   |
| Toshiba Satellite              | 1         | 0.65%   |
| Supermicro SYS-1019S-MP        | 1         | 0.65%   |
| Star Labs StarBook             | 1         | 0.65%   |
| Sony SVP1322M1EBI              | 1         | 0.65%   |
| Shuttle SH570                  | 1         | 0.65%   |
| Shuttle DH170                  | 1         | 0.65%   |
| ShenZhen MinWin MW-NANO-APL-4L | 1         | 0.65%   |
| Protectli FW4B                 | 1         | 0.65%   |
| PC Engines APU3                | 1         | 0.65%   |
| PC Engines APU                 | 1         | 0.65%   |
| MSI WC776AA-UUW                | 1         | 0.65%   |
| MSI MS-7C56                    | 1         | 0.65%   |
| MSI MS-7B43                    | 1         | 0.65%   |
| MSI MS-7918                    | 1         | 0.65%   |
| MSI MS-7369                    | 1         | 0.65%   |
| Lenovo V130-15IGM              | 1         | 0.65%   |
| Lenovo Legion                  | 1         | 0.65%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 17        | 11.04%  |
| 2014    | 17        | 11.04%  |
| 2016    | 16        | 10.39%  |
| 2017    | 15        | 9.74%   |
| 2018    | 13        | 8.44%   |
| 2019    | 12        | 7.79%   |
| 2010    | 11        | 7.14%   |
| 2021    | 10        | 6.49%   |
| 2015    | 9         | 5.84%   |
| 2012    | 8         | 5.19%   |
| 2022    | 7         | 4.55%   |
| 2013    | 6         | 3.9%    |
| 2009    | 6         | 3.9%    |
| 2023    | 2         | 1.3%    |
| 2011    | 2         | 1.3%    |
| 2007    | 1         | 0.65%   |
| 2006    | 1         | 0.65%   |
| Unknown | 1         | 0.65%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Desktop    | 88        | 57.14%  |
| Notebook   | 32        | 20.78%  |
| Server     | 19        | 12.34%  |
| Mini pc    | 11        | 7.14%   |
| Tablet     | 3         | 1.95%   |
| All in one | 1         | 0.65%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 142       | 92.21%  |
| Yes  | 12        | 7.79%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 54        | 34.39%  |
| 4.01-8.0        | 37        | 23.57%  |
| 16.01-24.0      | 29        | 18.47%  |
| 32.01-64.0      | 15        | 9.55%   |
| 64.01-256.0     | 6         | 3.82%   |
| 24.01-32.0      | 5         | 3.18%   |
| 2.01-3.0        | 5         | 3.18%   |
| More than 256.0 | 3         | 1.91%   |
| 3.01-4.0        | 2         | 1.27%   |
| 1.01-2.0        | 1         | 0.64%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 83        | 52.53%  |
| 0.51-1.0    | 45        | 28.48%  |
| 1.01-2.0    | 17        | 10.76%  |
| 4.01-8.0    | 4         | 2.53%   |
| 2.01-3.0    | 3         | 1.9%    |
| 3.01-4.0    | 2         | 1.27%   |
| 24.01-32.0  | 2         | 1.27%   |
| 64.01-256.0 | 2         | 1.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 108       | 68.35%  |
| 2      | 16        | 10.13%  |
| 3      | 10        | 6.33%   |
| 0      | 10        | 6.33%   |
| 6      | 3         | 1.9%    |
| 4      | 3         | 1.9%    |
| 11     | 2         | 1.27%   |
| 18     | 1         | 0.63%   |
| 12     | 1         | 0.63%   |
| 10     | 1         | 0.63%   |
| 9      | 1         | 0.63%   |
| 8      | 1         | 0.63%   |
| 5      | 1         | 0.63%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 125       | 80.65%  |
| Yes       | 30        | 19.35%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 144       | 93.51%  |
| No        | 10        | 6.49%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 100       | 64.52%  |
| Yes       | 55        | 35.48%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 117       | 75.48%  |
| Yes       | 38        | 24.52%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Sweden  | 154       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Stockholm             | 23        | 13.45%  |
| Malmo                 | 13        | 7.6%    |
| Bromma                | 6         | 3.51%   |
| LinkГ¶ping          | 5         | 2.92%   |
| VÃ¤sterÃ¥s        | 4         | 2.34%   |
| UmeГҐ               | 4         | 2.34%   |
| Gothenburg            | 4         | 2.34%   |
| Taby                  | 3         | 1.75%   |
| Sollentuna            | 3         | 1.75%   |
| Piteå                | 3         | 1.75%   |
| JГ¶nkГ¶ping       | 3         | 1.75%   |
| Henan                 | 3         | 1.75%   |
| Bandhagen             | 3         | 1.75%   |
| Västerås            | 2         | 1.17%   |
| Umeå                 | 2         | 1.17%   |
| Tyreso Strand         | 2         | 1.17%   |
| Tumba                 | 2         | 1.17%   |
| Solleftea             | 2         | 1.17%   |
| Örebro               | 2         | 1.17%   |
| Lund                  | 2         | 1.17%   |
| Landskrona            | 2         | 1.17%   |
| Kungsbacka            | 2         | 1.17%   |
| Helsingborg           | 2         | 1.17%   |
| Enskede-Arsta-Vantoer | 2         | 1.17%   |
| Г…hus              | 1         | 0.58%   |
| Г„lvГ¤ngen       | 1         | 0.58%   |
| Vaxjo                 | 1         | 0.58%   |
| Varekil               | 1         | 0.58%   |
| Uppsala               | 1         | 0.58%   |
| Upplands Vasby        | 1         | 0.58%   |
| UmeÃ¥               | 1         | 0.58%   |
| Ulricehamn            | 1         | 0.58%   |
| Trosa                 | 1         | 0.58%   |
| Trelleborg            | 1         | 0.58%   |
| Trangsund             | 1         | 0.58%   |
| Torsby                | 1         | 0.58%   |
| SГ¶dertГ¤lje      | 1         | 0.58%   |
| Sundsvall             | 1         | 0.58%   |
| Sundbyberg            | 1         | 0.58%   |
| Stroemstad            | 1         | 0.58%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 36        | 50     | 18.85%  |
| Seagate             | 21        | 46     | 10.99%  |
| WDC                 | 19        | 28     | 9.95%   |
| Kingston            | 19        | 21     | 9.95%   |
| Intel               | 16        | 31     | 8.38%   |
| Hoodisk             | 12        | 17     | 6.28%   |
| SanDisk             | 8         | 10     | 4.19%   |
| Toshiba             | 7         | 16     | 3.66%   |
| Crucial             | 7         | 15     | 3.66%   |
| NVMe                | 5         | 6      | 2.62%   |
| Micron Technology   | 4         | 7      | 2.09%   |
| Transcend           | 3         | 3      | 1.57%   |
| Hitachi             | 3         | 3      | 1.57%   |
| Hewlett-Packard     | 3         | 7      | 1.57%   |
| SK hynix            | 2         | 2      | 1.05%   |
| Phison              | 2         | 2      | 1.05%   |
| OCZ                 | 2         | 3      | 1.05%   |
| Innodisk            | 2         | 3      | 1.05%   |
| HPE                 | 2         | 14     | 1.05%   |
| Apacer              | 2         | 2      | 1.05%   |
| A-DATA Technology   | 2         | 2      | 1.05%   |
| XrayDisk            | 1         | 1      | 0.52%   |
| Supermicro          | 1         | 1      | 0.52%   |
| Star Drive          | 1         | 1      | 0.52%   |
| PNY                 | 1         | 1      | 0.52%   |
| MARVELL             | 1         | 2      | 0.52%   |
| LITEONIT            | 1         | 1      | 0.52%   |
| LITEON              | 1         | 1      | 0.52%   |
| KingSpec            | 1         | 1      | 0.52%   |
| HGST                | 1         | 4      | 0.52%   |
| Fordisk             | 1         | 1      | 0.52%   |
| Fanxiang            | 1         | 1      | 0.52%   |
| Dell                | 1         | 2      | 0.52%   |
| Corsair             | 1         | 1      | 0.52%   |
| Apple               | 1         | 1      | 0.52%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Kingston SA400S37120G 120GB    | 4         | 1.91%   |
| SanDisk SDSA6MM-032G-1006 32GB | 3         | 1.44%   |
| Samsung SSD 860 QVO 1TB        | 3         | 1.44%   |
| Kingston SA400S37240G 240GB    | 3         | 1.44%   |
| Hoodisk SSD 64GB               | 3         | 1.44%   |
| Hoodisk SSD 16GB               | 3         | 1.44%   |
| Hoodisk SSD 128GB              | 3         | 1.44%   |
| WDC WD5000AZLX-60K2TA0 500GB   | 2         | 0.96%   |
| Toshiba HDWQ140 4TB            | 2         | 0.96%   |
| Seagate ST2000DM008-2FR102 2TB | 2         | 0.96%   |
| Seagate ST1000DM010-2EP102 1TB | 2         | 0.96%   |
| Samsung SSD 970 EVO 500GB      | 2         | 0.96%   |
| Samsung SSD 870 EVO 250GB      | 2         | 0.96%   |
| Samsung SSD 860 EVO 250GB      | 2         | 0.96%   |
| Samsung SSD 840 EVO 120GB      | 2         | 0.96%   |
| Samsung HD501LJ 500GB          | 2         | 0.96%   |
| Phison SATA SSD 16GB           | 2         | 0.96%   |
| NVMe KBG40ZPZ256G TOS 256GB    | 2         | 0.96%   |
| Kingston SV300S37A240G 240GB   | 2         | 0.96%   |
| Intel SSDSC2CT120A3 120GB      | 2         | 0.96%   |
| Intel SSDSC2BW240A4 240GB      | 2         | 0.96%   |
| Hoodisk SSD 32GB               | 2         | 0.96%   |
| HP RAID 1(1+0) 128GB           | 2         | 0.96%   |
| Crucial CT256MX100SSD1 256GB   | 2         | 0.96%   |
| Apacer 64GB SATA Flash Drive   | 2         | 0.96%   |
| XrayDisk SSD 64GB              | 1         | 0.48%   |
| WDC WDS250G2B0C-00PXH0 250GB   | 1         | 0.48%   |
| WDC WDS250G2B0A-00SM50 250GB   | 1         | 0.48%   |
| WDC WDS240G2G0A-00JH30 240GB   | 1         | 0.48%   |
| WDC WDS120G1G0A-00SS50 120GB   | 1         | 0.48%   |
| WDC WD82PURZ-85TEUY0 8TB       | 1         | 0.48%   |
| WDC WD6400BPVT-60HXZT1 640GB   | 1         | 0.48%   |
| WDC WD6400AARS-00Y5B1 640GB    | 1         | 0.48%   |
| WDC WD5000AAKS-07V0A0 500GB    | 1         | 0.48%   |
| WDC WD5000AACS-00ZUB0 500GB    | 1         | 0.48%   |
| WDC WD40EZRZ-22GXCB0 4TB       | 1         | 0.48%   |
| WDC WD40EFRX-68N32N0 4TB       | 1         | 0.48%   |
| WDC WD3200BEKT-08PVMT1 320GB   | 1         | 0.48%   |
| WDC WD2500AAJS-60B4A0 250GB    | 1         | 0.48%   |
| WDC WD20EFRX-68EUZN0 2TB       | 1         | 0.48%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 44     | 37.74%  |
| WDC                 | 13        | 20     | 24.53%  |
| Samsung Electronics | 6         | 9      | 11.32%  |
| Toshiba             | 5         | 13     | 9.43%   |
| NVMe                | 3         | 4      | 5.66%   |
| Hitachi             | 3         | 3      | 5.66%   |
| HPE                 | 1         | 8      | 1.89%   |
| HGST                | 1         | 4      | 1.89%   |
| Hewlett-Packard     | 1         | 5      | 1.89%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 26        | 34     | 21.31%  |
| Kingston            | 18        | 20     | 14.75%  |
| Intel               | 14        | 28     | 11.48%  |
| Hoodisk             | 12        | 17     | 9.84%   |
| SanDisk             | 8         | 10     | 6.56%   |
| Crucial             | 7         | 15     | 5.74%   |
| Micron Technology   | 4         | 7      | 3.28%   |
| WDC                 | 3         | 5      | 2.46%   |
| Toshiba             | 2         | 3      | 1.64%   |
| SK hynix            | 2         | 2      | 1.64%   |
| Phison              | 2         | 2      | 1.64%   |
| OCZ                 | 2         | 3      | 1.64%   |
| NVMe                | 2         | 2      | 1.64%   |
| Innodisk            | 2         | 3      | 1.64%   |
| Hewlett-Packard     | 2         | 2      | 1.64%   |
| Apacer              | 2         | 2      | 1.64%   |
| XrayDisk            | 1         | 1      | 0.82%   |
| Transcend           | 1         | 1      | 0.82%   |
| Supermicro          | 1         | 1      | 0.82%   |
| Seagate             | 1         | 1      | 0.82%   |
| PNY                 | 1         | 1      | 0.82%   |
| MARVELL             | 1         | 2      | 0.82%   |
| LITEONIT            | 1         | 1      | 0.82%   |
| LITEON              | 1         | 1      | 0.82%   |
| KingSpec            | 1         | 1      | 0.82%   |
| HPE                 | 1         | 6      | 0.82%   |
| Fordisk             | 1         | 1      | 0.82%   |
| Dell                | 1         | 2      | 0.82%   |
| Corsair             | 1         | 1      | 0.82%   |
| Apple               | 1         | 1      | 0.82%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 106       | 176    | 63.47%  |
| HDD  | 41        | 110    | 24.55%  |
| NVMe | 20        | 21     | 11.98%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 131       | 286    | 86.75%  |
| NVMe | 20        | 21     | 13.25%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 117       | 180    | 70.91%  |
| 0.51-1.0   | 26        | 39     | 15.76%  |
| 3.01-4.0   | 9         | 26     | 5.45%   |
| 1.01-2.0   | 8         | 22     | 4.85%   |
| 4.01-10.0  | 5         | 19     | 3.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 71        | 44.94%  |
| 51-100         | 21        | 13.29%  |
| 1-20           | 19        | 12.03%  |
| 251-500        | 17        | 10.76%  |
| 21-50          | 17        | 10.76%  |
| 501-1000       | 7         | 4.43%   |
| 1001-2000      | 4         | 2.53%   |
| More than 3000 | 2         | 1.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 136       | 86.62%  |
| 21-50     | 17        | 10.83%  |
| 251-500   | 2         | 1.27%   |
| 101-250   | 1         | 0.64%   |
| 1001-2000 | 1         | 0.64%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Intel SSDSC2CT120A3 120GB                    | 2         | 2      | 6.9%    |
| WDC WD6400AARS-00Y5B1 640GB                  | 1         | 1      | 3.45%   |
| WDC WD40EFRX-68N32N0 4TB                     | 1         | 2      | 3.45%   |
| WDC WD2500AAJS-60B4A0 250GB                  | 1         | 2      | 3.45%   |
| WDC WD20EFRX-68EUZN0 2TB                     | 1         | 2      | 3.45%   |
| WDC WD20EARX-00ZUDB0 2TB                     | 1         | 1      | 3.45%   |
| WDC WD2002FYPS-02W3B0 2TB                    | 1         | 1      | 3.45%   |
| WDC WD10EAVS-00D7B0 1TB                      | 1         | 1      | 3.45%   |
| SK hynix HFS128G32MND-2200A 128GB            | 1         | 1      | 3.45%   |
| Seagate ST9640320AS 640GB                    | 1         | 1      | 3.45%   |
| Seagate ST9500420AS 500GB                    | 1         | 1      | 3.45%   |
| Seagate ST9320423AS 320GB                    | 1         | 1      | 3.45%   |
| Seagate ST750LM022 HN-M750MBB 752GB          | 1         | 1      | 3.45%   |
| Seagate ST2000DM008-2FR102 2TB               | 1         | 1      | 3.45%   |
| Seagate ST100FN0021 100GB                    | 1         | 1      | 3.45%   |
| Seagate ST1000LM049-2GH172 1TB               | 1         | 1      | 3.45%   |
| Seagate ST1000DM010-2EP102 1TB               | 1         | 1      | 3.45%   |
| Seagate ST1000DM003-1ER162 1TB               | 1         | 1      | 3.45%   |
| Samsung Electronics SSD 970 EVO 500GB        | 1         | 1      | 3.45%   |
| Samsung Electronics MZNTE128HMGR-000SO 128GB | 1         | 1      | 3.45%   |
| Samsung Electronics HM250JI 250GB            | 1         | 1      | 3.45%   |
| Samsung Electronics HD321KJ 320GB            | 1         | 1      | 3.45%   |
| Kingston SV300S37A120G 120GB                 | 1         | 1      | 3.45%   |
| Kingston SMS200S3120G 120GB                  | 1         | 1      | 3.45%   |
| Intel SSDSC2CT060A3 64GB                     | 1         | 2      | 3.45%   |
| Intel SSDSC2BA400G4 400GB                    | 1         | 1      | 3.45%   |
| Intel SSDSA2M080G2GC 80GB                    | 1         | 1      | 3.45%   |
| Hitachi HTS725025A9A364 250GB                | 1         | 1      | 3.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 9      | 30.77%  |
| WDC                 | 5         | 10     | 19.23%  |
| Intel               | 5         | 6      | 19.23%  |
| Samsung Electronics | 4         | 4      | 15.38%  |
| Kingston            | 2         | 2      | 7.69%   |
| SK hynix            | 1         | 1      | 3.85%   |
| Hitachi             | 1         | 1      | 3.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 8      | 46.67%  |
| WDC                 | 5         | 10     | 33.33%  |
| Samsung Electronics | 2         | 2      | 13.33%  |
| Hitachi             | 1         | 1      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 21     | 56%     |
| SSD  | 10        | 11     | 40%     |
| NVMe | 1         | 1      | 4%      |

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
| Works    | 124       | 255    | 77.02%  |
| Malfunc  | 25        | 33     | 15.53%  |
| Detected | 12        | 19     | 7.45%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 116       | 63.74%  |
| AMD                         | 23        | 12.64%  |
| Samsung Electronics         | 8         | 4.4%    |
| Broadcom / LSI              | 7         | 3.85%   |
| Marvell Technology Group    | 5         | 2.75%   |
| SanDisk                     | 3         | 1.65%   |
| Hewlett-Packard             | 3         | 1.65%   |
| Silicon Motion              | 2         | 1.1%    |
| KIOXIA                      | 2         | 1.1%    |
| ASMedia Technology          | 2         | 1.1%    |
| VIA Technologies            | 1         | 0.55%   |
| Transcend                   | 1         | 0.55%   |
| Seagate Technology          | 1         | 0.55%   |
| Realtek Semiconductor       | 1         | 0.55%   |
| Phison Electronics          | 1         | 0.55%   |
| Nvidia                      | 1         | 0.55%   |
| Kingston Technology Company | 1         | 0.55%   |
| Dell                        | 1         | 0.55%   |
| ADATA Technology            | 1         | 0.55%   |
| Adaptec                     | 1         | 0.55%   |
| 3ware                       | 1         | 0.55%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 18        | 8.41%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 11        | 5.14%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 11        | 5.14%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 8         | 3.74%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 7         | 3.27%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 6         | 2.8%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5         | 2.34%   |
| Intel SATA Controller [RAID mode]                                                       | 4         | 1.87%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 4         | 1.87%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 4         | 1.87%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 4         | 1.87%   |
| AMD FCH IDE Controller                                                                  | 4         | 1.87%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3         | 1.4%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 3         | 1.4%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3         | 1.4%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3         | 1.4%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 3         | 1.4%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 3         | 1.4%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 3         | 1.4%    |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                            | 3         | 1.4%    |
| Unknown                                                                                 | 3         | 1.4%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2         | 0.93%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 0.93%   |
| Samsung NVMe SSD Controller 980                                                         | 2         | 0.93%   |
| KIOXIA NVMe SSD Controller BG4                                                          | 2         | 0.93%   |
| Intel SSD 660P Series                                                                   | 2         | 0.93%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 2         | 0.93%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2         | 0.93%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                           | 2         | 0.93%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                            | 2         | 0.93%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2         | 0.93%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 2         | 0.93%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2         | 0.93%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 2         | 0.93%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 2         | 0.93%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 2         | 0.93%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                              | 2         | 0.93%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 0.93%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 0.93%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2         | 0.93%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 122       | 63.87%  |
| NVMe | 25        | 13.09%  |
| IDE  | 23        | 12.04%  |
| RAID | 14        | 7.33%   |
| SAS  | 7         | 3.66%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 127       | 81.94%  |
| AMD     | 27        | 17.42%  |
| Unknown | 1         | 0.65%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| AMD GX-412TC SOC                         | 7         | 4.49%   |
| Intel Celeron CPU J1900 @ 1.99GHz        | 5         | 3.21%   |
| Intel Core i7-4770K CPU @ 3.50GHz        | 3         | 1.92%   |
| Intel Core i5-6500 CPU @ 3.20GHz         | 3         | 1.92%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 3         | 1.92%   |
| Intel Celeron N5105 @ 2.00GHz            | 3         | 1.92%   |
| Intel Atom CPU E3845 @ 1.91GHz           | 3         | 1.92%   |
| AMD RX-427BB with AMD Radeon R7 Graphics | 3         | 1.92%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz      | 2         | 1.28%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 2         | 1.28%   |
| Intel Core i5-8265U CPU @ 1.60GHz        | 2         | 1.28%   |
| Intel Core i5-6300U CPU @ 2.40GHz        | 2         | 1.28%   |
| Intel Core i5-6200U CPU @ 2.30GHz        | 2         | 1.28%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 2         | 1.28%   |
| Intel Core i5-4200U CPU @ 1.60GHz        | 2         | 1.28%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz       | 2         | 1.28%   |
| Intel Core i5 CPU M 540 @ 2.53GHz        | 2         | 1.28%   |
| Intel Core i3-6100 CPU @ 3.70GHz         | 2         | 1.28%   |
| Intel Celeron J4125 CPU @ 2.00GHz        | 2         | 1.28%   |
| Intel Celeron CPU J3160 @ 1.60GHz        | 2         | 1.28%   |
| AMD Ryzen 9 3900X 12-Core Processor      | 2         | 1.28%   |
| AMD Ryzen 7 1700 Eight-Core Processor    | 2         | 1.28%   |
| Intel Xeon Silver 4116 CPU @ 2.10GHz     | 1         | 0.64%   |
| Intel Xeon Silver 4114 CPU @ 2.20GHz     | 1         | 0.64%   |
| Intel Xeon Silver 4110 CPU @ 2.10GHz     | 1         | 0.64%   |
| Intel Xeon E-2224 CPU @ 3.40GHz          | 1         | 0.64%   |
| Intel Xeon CPU X5680 @ 3.33GHz           | 1         | 0.64%   |
| Intel Xeon CPU X3470 @ 2.93GHz           | 1         | 0.64%   |
| Intel Xeon CPU X3450 @ 2.67GHz           | 1         | 0.64%   |
| Intel Xeon CPU X3440 @ 2.53GHz           | 1         | 0.64%   |
| Intel Xeon CPU X3430 @ 2.40GHz           | 1         | 0.64%   |
| Intel Xeon CPU E5450 @ 3.00GHz           | 1         | 0.64%   |
| Intel Xeon CPU E5-2630 0 @ 2.30GHz       | 1         | 0.64%   |
| Intel Xeon CPU E5-2623 v4 @ 2.60GHz      | 1         | 0.64%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz      | 1         | 0.64%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz       | 1         | 0.64%   |
| Intel Xeon CPU E31240 @ 3.30GHz          | 1         | 0.64%   |
| Intel Xeon CPU E31220 @ 3.10GHz          | 1         | 0.64%   |
| Intel Xeon CPU E3-1515M v5 @ 2.80GHz     | 1         | 0.64%   |
| Intel Xeon CPU E3-1270 v3 @ 3.50GHz      | 1         | 0.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 40        | 25.64%  |
| Intel Xeon              | 24        | 15.38%  |
| Intel Celeron           | 19        | 12.18%  |
| Intel Core i7           | 17        | 10.9%   |
| AMD GX                  | 10        | 6.41%   |
| Other                   | 9         | 5.77%   |
| Intel Core i3           | 7         | 4.49%   |
| Intel Xeon Silver       | 3         | 1.92%   |
| Intel Pentium           | 3         | 1.92%   |
| Intel Core 2 Duo        | 3         | 1.92%   |
| Intel Atom              | 3         | 1.92%   |
| AMD Ryzen 7             | 3         | 1.92%   |
| Intel Core 2 Quad       | 2         | 1.28%   |
| AMD Ryzen 9             | 2         | 1.28%   |
| Intel Pentium Dual-Core | 1         | 0.64%   |
| Intel Core m3           | 1         | 0.64%   |
| Intel Core 2            | 1         | 0.64%   |
| AMD Ryzen Threadripper  | 1         | 0.64%   |
| AMD Ryzen Embedded      | 1         | 0.64%   |
| AMD Ryzen 5 PRO         | 1         | 0.64%   |
| AMD G                   | 1         | 0.64%   |
| AMD FX                  | 1         | 0.64%   |
| AMD Athlon 64 X2        | 1         | 0.64%   |
| AMD Athlon              | 1         | 0.64%   |
| AMD A4                  | 1         | 0.64%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 83        | 53.21%  |
| 2       | 43        | 27.56%  |
| 6       | 7         | 4.49%   |
| Unknown | 7         | 4.49%   |
| 8       | 6         | 3.85%   |
| 24      | 4         | 2.56%   |
| 16      | 4         | 2.56%   |
| 12      | 1         | 0.64%   |
| 10      | 1         | 0.64%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 145       | 94.16%  |
| 2       | 6         | 3.9%    |
| Unknown | 3         | 1.95%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 82        | 52.56%  |
| 2       | 67        | 42.95%  |
| Unknown | 7         | 4.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Haswell       | 23        | 14.74%  |
| Skylake       | 20        | 12.82%  |
| KabyLake      | 13        | 8.33%   |
| Silvermont    | 12        | 7.69%   |
| SandyBridge   | 11        | 7.05%   |
| Unknown       | 9         | 5.77%   |
| Puma          | 8         | 5.13%   |
| Penryn        | 7         | 4.49%   |
| IvyBridge     | 7         | 4.49%   |
| Broadwell     | 6         | 3.85%   |
| Westmere      | 5         | 3.21%   |
| Nehalem       | 5         | 3.21%   |
| Zen           | 4         | 2.56%   |
| Goldmont plus | 4         | 2.56%   |
| Core          | 4         | 2.56%   |
| Steamroller   | 3         | 1.92%   |
| Jaguar        | 3         | 1.92%   |
| IceLake       | 3         | 1.92%   |
| Zen 2         | 2         | 1.28%   |
| Piledriver    | 2         | 1.28%   |
| Zen+          | 1         | 0.64%   |
| K8 Hammer     | 1         | 0.64%   |
| Goldmont      | 1         | 0.64%   |
| Excavator     | 1         | 0.64%   |
| Bobcat        | 1         | 0.64%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 89        | 59.73%  |
| Nvidia                     | 20        | 13.42%  |
| Matrox Electronics Systems | 17        | 11.41%  |
| AMD                        | 17        | 11.41%  |
| ASPEED Technology          | 6         | 4.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 5.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 8         | 5.3%    |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 6         | 3.97%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 3.97%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 3.97%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 6         | 3.97%   |
| Intel HD Graphics 530                                                                    | 5         | 3.31%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 2.65%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 2.65%   |
| Intel JasperLake [UHD Graphics]                                                          | 4         | 2.65%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 2.65%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 2.65%   |
| Matrox Electronics Systems MGA G200EH                                                    | 3         | 1.99%   |
| Matrox Electronics Systems G200eR2                                                       | 3         | 1.99%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.99%   |
| Intel HD Graphics 620                                                                    | 3         | 1.99%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.99%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.99%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 3         | 1.99%   |
| Nvidia GT215 [GeForce GT 240]                                                            | 2         | 1.32%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 1.32%   |
| Matrox Electronics Systems MGA G200eH3                                                   | 2         | 1.32%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller                 | 2         | 1.32%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 2         | 1.32%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.32%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2         | 1.32%   |
| Intel Iris Plus Graphics G4 (Ice Lake)                                                   | 2         | 1.32%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.32%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 1.32%   |
| AMD ES1000                                                                               | 2         | 1.32%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 1.32%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.66%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.66%   |
| Nvidia GP108M [GeForce MX230]                                                            | 1         | 0.66%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.66%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 0.66%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1         | 0.66%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1         | 0.66%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.66%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1         | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 80        | 51.28%  |
| 1 x Nvidia     | 17        | 10.9%   |
| 1 x Matrox     | 17        | 10.9%   |
| 1 x AMD        | 16        | 10.26%  |
| Other          | 12        | 7.69%   |
| 1 x ASPEED     | 5         | 3.21%   |
| 2 x Intel      | 3         | 1.92%   |
| Intel + Nvidia | 3         | 1.92%   |
| Intel + AMD    | 2         | 1.28%   |
| Intel + ASPEED | 1         | 0.64%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 127       | 81.94%  |
| Unknown     | 16        | 10.32%  |
| Proprietary | 12        | 7.74%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 139       | 90.26%  |
| 1.01-2.0   | 5         | 3.25%   |
| 5.01-6.0   | 3         | 1.95%   |
| 0.51-1.0   | 3         | 1.95%   |
| 3.01-4.0   | 2         | 1.3%    |
| 7.01-8.0   | 1         | 0.65%   |
| 8.01-16.0  | 1         | 0.65%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 8         | 15.38%  |
| Samsung Electronics     | 7         | 13.46%  |
| Hewlett-Packard         | 6         | 11.54%  |
| Chimei Innolux          | 6         | 11.54%  |
| Dell                    | 4         | 7.69%   |
| Philips                 | 3         | 5.77%   |
| Iiyama                  | 2         | 3.85%   |
| AU Optronics            | 2         | 3.85%   |
| AOC                     | 2         | 3.85%   |
| Ancor Communications    | 2         | 3.85%   |
| Panasonic               | 1         | 1.92%   |
| LG Electronics          | 1         | 1.92%   |
| Lenovo Group Limited    | 1         | 1.92%   |
| Lenovo                  | 1         | 1.92%   |
| InfoVision              | 1         | 1.92%   |
| Goldstar                | 1         | 1.92%   |
| Gigabyte Technology     | 1         | 1.92%   |
| Chi Mei Optoelectronics | 1         | 1.92%   |
| BOE                     | 1         | 1.92%   |
| Acer                    | 1         | 1.92%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics S24D390 SAM0B65 1920x1080 520x290mm 23.4-inch    | 2         | 3.57%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x170mm 12.2-inch         | 2         | 3.57%   |
| Iiyama PL2779QQ IVM6641 3840x2160 600x330mm 27.0-inch                | 2         | 3.57%   |
| Dell UP2715K DEL40B6 848x480 600x340mm 27.2-inch                     | 2         | 3.57%   |
| AOC 2350 AOC2350 1920x1080 510x290mm 23.1-inch                       | 2         | 3.57%   |
| Samsung Electronics S24E650 SAM0CC1 1920x1200 520x320mm 24.0-inch    | 1         | 1.79%   |
| Samsung Electronics LCD Monitor SyncMaster                           | 1         | 1.79%   |
| Samsung Electronics LCD Monitor SEC4542 1280x800 300x190mm 14.0-inch | 1         | 1.79%   |
| Samsung Electronics LCD Monitor SE790C 3440x1440                     | 1         | 1.79%   |
| Samsung Electronics LCD Monitor S23E650 3840x1080                    | 1         | 1.79%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch    | 1         | 1.79%   |
| Philips PHL BDM3270 PHL08E7 2560x1440 710x400mm 32.1-inch            | 1         | 1.79%   |
| Philips PHL 276E8V PHLC18F 3840x2160 600x340mm 27.2-inch             | 1         | 1.79%   |
| Philips PHL 221B6Q PHL08DF 1920x1080 480x270mm 21.7-inch             | 1         | 1.79%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch         | 1         | 1.79%   |
| LG Electronics LCD Monitor LX20D 1600x1200                           | 1         | 1.79%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch         | 1         | 1.79%   |
| LG Display LCD Monitor LGD0569 1920x1080 310x170mm 13.9-inch         | 1         | 1.79%   |
| LG Display LCD Monitor LGD04A7 1920x1080 340x190mm 15.3-inch         | 1         | 1.79%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x170mm 13.9-inch          | 1         | 1.79%   |
| LG Display LCD Monitor LGD027B 1600x900 380x210mm 17.1-inch          | 1         | 1.79%   |
| LG Display LCD Monitor LGD0213 1600x900 310x170mm 13.9-inch          | 1         | 1.79%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch              | 1         | 1.79%   |
| Lenovo Group Limited LCD Monitor 1920x1080                           | 1         | 1.79%   |
| InfoVision LCD Monitor IVO04E3 1366x768 280x160mm 12.7-inch          | 1         | 1.79%   |
| Iiyama PL2888UH IVM7104 3840x2160 620x340mm 27.8-inch                | 1         | 1.79%   |
| Hewlett-Packard Z27n G2 HPN348A 2560x1440 600x340mm 27.2-inch        | 1         | 1.79%   |
| Hewlett-Packard w2216 HWP280C 1680x1050 470x290mm 21.7-inch          | 1         | 1.79%   |
| Hewlett-Packard LCD Monitor Z24n 1920x1200                           | 1         | 1.79%   |
| Hewlett-Packard LCD Monitor E241i 1920x1200                          | 1         | 1.79%   |
| Hewlett-Packard L2335 HWP2615 1920x1200 500x310mm 23.2-inch          | 1         | 1.79%   |
| Hewlett-Packard E243i HPN3463 1920x1200 520x320mm 24.0-inch          | 1         | 1.79%   |
| Hewlett-Packard E242 HWP326E 1920x1200 520x320mm 24.0-inch           | 1         | 1.79%   |
| Goldstar 22EN33 GSM597C 1920x1080 480x270mm 21.7-inch                | 1         | 1.79%   |
| Gigabyte Technology M28U GBT2800 3840x2160 630x360mm 28.6-inch       | 1         | 1.79%   |
| Dell UP2715K DEL40B8 3840x2160 600x340mm 27.2-inch                   | 1         | 1.79%   |
| Dell U3415W DELA0AA 3440x1440 800x330mm 34.1-inch                    | 1         | 1.79%   |
| Dell U2718Q DELA0EC 3840x2160 610x350mm 27.7-inch                    | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 340x190mm 15.3-inch     | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 340x190mm 15.3-inch      | 1         | 1.79%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 14        | 26.92%  |
| 1920x1200 (WUXGA)  | 6         | 11.54%  |
| 1366x768 (WXGA)    | 6         | 11.54%  |
| 3840x2160 (4K)     | 5         | 9.62%   |
| 2560x1440 (QHD)    | 4         | 7.69%   |
| 1600x900 (HD+)     | 4         | 7.69%   |
| 3840x1080          | 2         | 3.85%   |
| 3440x1440          | 2         | 3.85%   |
| 2736x1824          | 2         | 3.85%   |
| Unknown            | 2         | 3.85%   |
| 2880x1620          | 1         | 1.92%   |
| 1920x1280          | 1         | 1.92%   |
| 1680x1050 (WSXGA+) | 1         | 1.92%   |
| 1600x1200          | 1         | 1.92%   |
| 1440x900 (WXGA+)   | 1         | 1.92%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 9         | 18.75%  |
| Unknown | 7         | 14.58%  |
| 27      | 5         | 10.42%  |
| 24      | 4         | 8.33%   |
| 23      | 4         | 8.33%   |
| 13      | 4         | 8.33%   |
| 21      | 3         | 6.25%   |
| 12      | 3         | 6.25%   |
| 17      | 2         | 4.17%   |
| 14      | 2         | 4.17%   |
| 34      | 1         | 2.08%   |
| 32      | 1         | 2.08%   |
| 28      | 1         | 2.08%   |
| 11      | 1         | 2.08%   |
| 10      | 1         | 2.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 12        | 25%     |
| 501-600     | 11        | 22.92%  |
| 201-300     | 8         | 16.67%  |
| Unknown     | 7         | 14.58%  |
| 601-700     | 3         | 6.25%   |
| 401-500     | 3         | 6.25%   |
| 701-800     | 2         | 4.17%   |
| 351-400     | 2         | 4.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 27        | 61.36%  |
| Unknown | 7         | 15.91%  |
| 16/10   | 6         | 13.64%  |
| 3/2     | 3         | 6.82%   |
| 21/9    | 1         | 2.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 91-100         | 9         | 19.15%  |
| 201-250        | 7         | 14.89%  |
| Unknown        | 7         | 14.89%  |
| 81-90          | 5         | 10.64%  |
| 301-350        | 5         | 10.64%  |
| 61-70          | 3         | 6.38%   |
| 351-500        | 3         | 6.38%   |
| 251-300        | 3         | 6.38%   |
| 51-60          | 2         | 4.26%   |
| 121-130        | 2         | 4.26%   |
| 71-80          | 1         | 2.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 13        | 26.53%  |
| 101-120       | 10        | 20.41%  |
| 51-100        | 9         | 18.37%  |
| Unknown       | 7         | 14.29%  |
| 161-240       | 6         | 12.24%  |
| More than 240 | 2         | 4.08%   |
| 1-50          | 2         | 4.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 108       | 68.79%  |
| 1     | 39        | 24.84%  |
| 2     | 9         | 5.73%   |
| 3     | 1         | 0.64%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 120       | 55.56%  |
| Realtek Semiconductor    | 46        | 21.3%   |
| Broadcom                 | 23        | 10.65%  |
| Qualcomm Atheros         | 8         | 3.7%    |
| TP-Link                  | 2         | 0.93%   |
| Ralink Technology        | 2         | 0.93%   |
| Sierra Wireless          | 1         | 0.46%   |
| Senao                    | 1         | 0.46%   |
| NetXen Incorporated      | 1         | 0.46%   |
| Microsoft                | 1         | 0.46%   |
| Mellanox Technologies    | 1         | 0.46%   |
| MediaTek                 | 1         | 0.46%   |
| Marvell Technology Group | 1         | 0.46%   |
| JMicron Technology       | 1         | 0.46%   |
| IMC Networks             | 1         | 0.46%   |
| Hewlett-Packard          | 1         | 0.46%   |
| Google                   | 1         | 0.46%   |
| Edimax Technology        | 1         | 0.46%   |
| Chelsio Communications   | 1         | 0.46%   |
| Apple                    | 1         | 0.46%   |
| AMD                      | 1         | 0.46%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 40        | 14.87%  |
| Intel I210 Gigabit Network Connection                                         | 20        | 7.43%   |
| Intel I211 Gigabit Network Connection                                         | 19        | 7.06%   |
| Intel 82574L Gigabit Network Connection                                       | 9         | 3.35%   |
| Intel I350 Gigabit Network Connection                                         | 8         | 2.97%   |
| Intel Ethernet Connection I217-LM                                             | 8         | 2.97%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 8         | 2.97%   |
| Intel 82580 Gigabit Network Connection                                        | 7         | 2.6%    |
| Intel Wireless 7260                                                           | 5         | 1.86%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 5         | 1.86%   |
| Intel Wireless 8260                                                           | 4         | 1.49%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 4         | 1.49%   |
| Intel Ethernet Controller I226-V                                              | 4         | 1.49%   |
| Intel Ethernet Connection (2) I219-LM                                         | 4         | 1.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 4         | 1.49%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 4         | 1.49%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 3         | 1.12%   |
| Intel Ethernet Connection I219-LM                                             | 3         | 1.12%   |
| Intel Ethernet Connection I217-V                                              | 3         | 1.12%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 3         | 1.12%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 3         | 1.12%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 3         | 1.12%   |
| Broadcom BCM43228 802.11a/b/g/n                                               | 3         | 1.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 0.74%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2         | 0.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2         | 0.74%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 2         | 0.74%   |
| Intel Wireless 7265                                                           | 2         | 0.74%   |
| Intel Wireless 3165                                                           | 2         | 0.74%   |
| Intel Wi-Fi 6 AX200                                                           | 2         | 0.74%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                               | 2         | 0.74%   |
| Intel Ethernet Controller I225-V                                              | 2         | 0.74%   |
| Intel Ethernet Connection (2) I219-V                                          | 2         | 0.74%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 2         | 0.74%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 2         | 0.74%   |
| Intel Centrino Advanced-N 6200                                                | 2         | 0.74%   |
| Intel 82583V Gigabit Network Connection                                       | 2         | 0.74%   |
| Intel 82577LM Gigabit Network Connection                                      | 2         | 0.74%   |
| Intel 82576NS Gigabit Network Connection                                      | 2         | 0.74%   |
| Intel 82576 Gigabit Network Connection                                        | 2         | 0.74%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 33        | 55%     |
| Realtek Semiconductor | 8         | 13.33%  |
| Qualcomm Atheros      | 6         | 10%     |
| Broadcom              | 5         | 8.33%   |
| TP-Link               | 2         | 3.33%   |
| Ralink Technology     | 2         | 3.33%   |
| Sierra Wireless       | 1         | 1.67%   |
| Senao                 | 1         | 1.67%   |
| IMC Networks          | 1         | 1.67%   |
| Edimax Technology     | 1         | 1.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                             | 5         | 8.2%    |
| Intel Wireless 8260                                             | 4         | 6.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter             | 3         | 4.92%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                 | 3         | 4.92%   |
| Broadcom BCM43228 802.11a/b/g/n                                 | 3         | 4.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 2         | 3.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                | 2         | 3.28%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)  | 2         | 3.28%   |
| Intel Wireless 7265                                             | 2         | 3.28%   |
| Intel Wireless 3165                                             | 2         | 3.28%   |
| Intel Wi-Fi 6 AX200                                             | 2         | 3.28%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                 | 2         | 3.28%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 2         | 3.28%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                    | 2         | 3.28%   |
| Intel Centrino Advanced-N 6200                                  | 2         | 3.28%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter              | 2         | 3.28%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                    | 1         | 1.64%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                          | 1         | 1.64%   |
| Sierra Wireless EM7345 4G LTE                                   | 1         | 1.64%   |
| Senao EUB9801 802.11abgn Wireless Adapter [Ralink RT3572]       | 1         | 1.64%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter        | 1         | 1.64%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter        | 1         | 1.64%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                          | 1         | 1.64%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                         | 1         | 1.64%   |
| Ralink RT5370 Wireless Adapter                                  | 1         | 1.64%   |
| Ralink RT2870/RT3070 Wireless Adapter                           | 1         | 1.64%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter | 1         | 1.64%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter      | 1         | 1.64%   |
| Intel Wireless-AC 9260                                          | 1         | 1.64%   |
| Intel Wireless 8265 / 8275                                      | 1         | 1.64%   |
| Intel WiFi Link 5100                                            | 1         | 1.64%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                          | 1         | 1.64%   |
| Intel Gemini Lake PCH CNVi WiFi                                 | 1         | 1.64%   |
| Intel Comet Lake PCH-LP CNVi WiFi                               | 1         | 1.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                        | 1         | 1.64%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card            | 1         | 1.64%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]  | 1         | 1.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 102       | 59.65%  |
| Realtek Semiconductor    | 44        | 25.73%  |
| Broadcom                 | 18        | 10.53%  |
| Qualcomm Atheros         | 2         | 1.17%   |
| Microsoft                | 1         | 0.58%   |
| Marvell Technology Group | 1         | 0.58%   |
| JMicron Technology       | 1         | 0.58%   |
| Apple                    | 1         | 0.58%   |
| AMD                      | 1         | 0.58%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 40        | 19.8%   |
| Intel I210 Gigabit Network Connection                                         | 20        | 9.9%    |
| Intel I211 Gigabit Network Connection                                         | 19        | 9.41%   |
| Intel 82574L Gigabit Network Connection                                       | 9         | 4.46%   |
| Intel I350 Gigabit Network Connection                                         | 8         | 3.96%   |
| Intel Ethernet Connection I217-LM                                             | 8         | 3.96%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 8         | 3.96%   |
| Intel 82580 Gigabit Network Connection                                        | 7         | 3.47%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 5         | 2.48%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 4         | 1.98%   |
| Intel Ethernet Controller I226-V                                              | 4         | 1.98%   |
| Intel Ethernet Connection (2) I219-LM                                         | 4         | 1.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 4         | 1.98%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 4         | 1.98%   |
| Intel Ethernet Connection I219-LM                                             | 3         | 1.49%   |
| Intel Ethernet Connection I217-V                                              | 3         | 1.49%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 3         | 1.49%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 3         | 1.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2         | 0.99%   |
| Intel Ethernet Controller I225-V                                              | 2         | 0.99%   |
| Intel Ethernet Connection (2) I219-V                                          | 2         | 0.99%   |
| Intel 82583V Gigabit Network Connection                                       | 2         | 0.99%   |
| Intel 82577LM Gigabit Network Connection                                      | 2         | 0.99%   |
| Intel 82576NS Gigabit Network Connection                                      | 2         | 0.99%   |
| Intel 82576 Gigabit Network Connection                                        | 2         | 0.99%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 2         | 0.99%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                | 2         | 0.99%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1         | 0.5%    |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 0.5%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 1         | 0.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1         | 0.5%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 1         | 0.5%    |
| Microsoft RTL8153B GigE [Surface Ethernet Adapter]                            | 1         | 0.5%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1         | 0.5%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                        | 1         | 0.5%    |
| Intel NM10/ICH7 Family LAN Controller                                         | 1         | 0.5%    |
| Intel Ethernet Connection I219-V                                              | 1         | 0.5%    |
| Intel Ethernet Connection I218-V                                              | 1         | 0.5%    |
| Intel Ethernet Connection I218-LM                                             | 1         | 0.5%    |
| Intel Ethernet Connection (7) I219-V                                          | 1         | 0.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 144       | 70.24%  |
| WiFi     | 55        | 26.83%  |
| Unknown  | 5         | 2.44%   |
| Modem    | 1         | 0.49%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 133       | 83.65%  |
| WiFi     | 26        | 16.35%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 54        | 34.18%  |
| 4     | 27        | 17.09%  |
| 1     | 24        | 15.19%  |
| 3     | 20        | 12.66%  |
| 6     | 13        | 8.23%   |
| 5     | 9         | 5.7%    |
| 8     | 4         | 2.53%   |
| 7     | 4         | 2.53%   |
| 13    | 1         | 0.63%   |
| 9     | 1         | 0.63%   |
| 0     | 1         | 0.63%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 148       | 94.27%  |
| Yes  | 9         | 5.73%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 21        | 55.26%  |
| Cambridge Silicon Radio | 4         | 10.53%  |
| Broadcom                | 3         | 7.89%   |
| IMC Networks            | 2         | 5.26%   |
| Hewlett-Packard         | 2         | 5.26%   |
| Dell                    | 2         | 5.26%   |
| Apple                   | 2         | 5.26%   |
| Realtek Semiconductor   | 1         | 2.63%   |
| Lite-On Technology      | 1         | 2.63%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                      | 11        | 28.95%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)     | 4         | 10.53%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 3         | 7.89%   |
| Intel Wireless-AC 3168 Bluetooth                        | 2         | 5.26%   |
| Intel AX201 Bluetooth                                   | 2         | 5.26%   |
| Broadcom BCM2045B (BDC-2.1)                             | 2         | 5.26%   |
| Realtek Bluetooth Adapter                               | 1         | 2.63%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth              | 1         | 2.63%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                | 1         | 2.63%   |
| Intel AX210 Bluetooth                                   | 1         | 2.63%   |
| Intel AX200 Bluetooth                                   | 1         | 2.63%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip    | 1         | 2.63%   |
| IMC Networks Qualcomm Atheros AR3012 Bluetooth 4.0 + HS | 1         | 2.63%   |
| HP Broadcom 2070 Bluetooth Combo                        | 1         | 2.63%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter              | 1         | 2.63%   |
| Dell Wireless 355C Bluetooth 2.0 + EDR module           | 1         | 2.63%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module             | 1         | 2.63%   |
| Broadcom Bluetooth 4.0 Adapter                          | 1         | 2.63%   |
| Apple Broadcom Built-in Bluetooth                       | 1         | 2.63%   |
| Apple Bluetooth Host Controller                         | 1         | 2.63%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 86        | 66.67%  |
| AMD                     | 20        | 15.5%   |
| Nvidia                  | 17        | 13.18%  |
| Realtek Semiconductor   | 1         | 0.78%   |
| Philips (or NXP)        | 1         | 0.78%   |
| Lenovo                  | 1         | 0.78%   |
| Hewlett-Packard         | 1         | 0.78%   |
| GN Netcom               | 1         | 0.78%   |
| BEHRINGER International | 1         | 0.78%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 10        | 6.41%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 10        | 6.41%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 9         | 5.77%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 8         | 5.13%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 7         | 4.49%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7         | 4.49%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 3.85%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 3.85%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5         | 3.21%   |
| AMD FCH Azalia Controller                                                                         | 5         | 3.21%   |
| Intel Jasper Lake HD Audio                                                                        | 4         | 2.56%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 1.92%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.92%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 1.92%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 1.92%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 1.92%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.92%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 3         | 1.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 1.92%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 1.92%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 3         | 1.92%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.92%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 1.92%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 1.28%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.28%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.28%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 1.28%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 1.28%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2         | 1.28%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 1.28%   |
| Realtek Semiconductor Microphone(Attila) Microphone(Attila) Microphone(Attila)                    | 1         | 0.64%   |
| Philips (or NXP) Philips SHG7980                                                                  | 1         | 0.64%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.64%   |
| Nvidia MCP65 High Definition Audio                                                                | 1         | 0.64%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.64%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.64%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 0.64%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.64%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.64%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 27        | 17.53%  |
| SK hynix            | 24        | 15.58%  |
| Kingston            | 20        | 12.99%  |
| Corsair             | 19        | 12.34%  |
| Unknown             | 16        | 10.39%  |
| Micron Technology   | 14        | 9.09%   |
| Crucial             | 7         | 4.55%   |
| G.Skill             | 5         | 3.25%   |
| Unknown             | 4         | 2.6%    |
| Hewlett-Packard     | 3         | 1.95%   |
| Elpida              | 3         | 1.95%   |
| Kimtigo             | 2         | 1.3%    |
| HPE                 | 2         | 1.3%    |
| Transcend           | 1         | 0.65%   |
| Toshiba             | 1         | 0.65%   |
| Tigo                | 1         | 0.65%   |
| Smart Modular       | 1         | 0.65%   |
| Ramaxel Technology  | 1         | 0.65%   |
| GSkill              | 1         | 0.65%   |
| ASint Technology    | 1         | 0.65%   |
| Apacer              | 1         | 0.65%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                 | 6         | 3.64%   |
| Corsair RAM CML8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s         | 4         | 2.42%   |
| Unknown                                                     | 4         | 2.42%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s      | 3         | 1.82%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 2         | 1.21%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s        | 2         | 1.21%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 2         | 1.21%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 2         | 1.21%   |
| Samsung RAM Module 4GB DIMM DDR4 2133MT/s                   | 2         | 1.21%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s       | 2         | 1.21%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s       | 2         | 1.21%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s       | 2         | 1.21%   |
| Kingston RAM 9965525-116.A00LF 8GB DIMM DDR3 1600MT/s       | 2         | 1.21%   |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s              | 2         | 1.21%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                        | 1         | 0.61%   |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s                  | 1         | 0.61%   |
| Unknown RAM Module 4096MB DIMM DDR3 1332MT/s                | 1         | 0.61%   |
| Unknown RAM Module 2GB SODIMM DDR3                          | 1         | 0.61%   |
| Unknown RAM Module 2GB DIMM SDRAM                           | 1         | 0.61%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                    | 1         | 0.61%   |
| Unknown RAM Module 2GB DIMM 800MT/s                         | 1         | 0.61%   |
| Unknown RAM Module 2048MB DIMM DDR3 1332MT/s                | 1         | 0.61%   |
| Unknown RAM Module 1GB DIMM SDRAM                           | 1         | 0.61%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                    | 1         | 0.61%   |
| Unknown RAM Module 1GB DIMM DDR2 333MT/s                    | 1         | 0.61%   |
| Unknown RAM Module 16GB DIMM DDR4 2133MT/s                  | 1         | 0.61%   |
| Unknown RAM Module 1024MB DIMM DDR3 1332MT/s                | 1         | 0.61%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s         | 1         | 0.61%   |
| Toshiba RAM 8HTF12864HDY-800G1 2048MB SODIMM 800MT/s        | 1         | 0.61%   |
| Toshiba RAM 64T128020EDL2.5C2 2048MB SODIMM 800MT/s         | 1         | 0.61%   |
| Tigo RAM 1600Mhz-4G 4GB DIMM DDR3 1600MT/s                  | 1         | 0.61%   |
| Smart Modular RAM Module 4GB DIMM DDR3 1333MT/s             | 1         | 0.61%   |
| SK hynix RAM HYMP151F72CP4N3-Y5 4096MB FB-DIMM DDR2 667MT/s | 1         | 0.61%   |
| SK hynix RAM HMT451U7AFR8C-PB 4GB DIMM DDR3 1600MT/s        | 1         | 0.61%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.61%   |
| SK hynix RAM HMT41GU7AFR8A-PB 8GB DIMM DDR3 1600MT/s        | 1         | 0.61%   |
| SK hynix RAM HMT41GU6AFR8A-PB 8GB DIMM DDR3 1600MT/s        | 1         | 0.61%   |
| SK hynix RAM HMT351U7EFR8C-RD 4GB DIMM DDR3                 | 1         | 0.61%   |
| SK hynix RAM HMT351U7CFR8A-H9 4GB DIMM DDR3 1333MT/s        | 1         | 0.61%   |
| SK hynix RAM HMT351U7BFR8A-H9 4GB DIMM DDR3 1333MT/s        | 1         | 0.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 77        | 55.8%   |
| DDR4    | 47        | 34.06%  |
| DDR2    | 7         | 5.07%   |
| Unknown | 3         | 2.17%   |
| SDRAM   | 2         | 1.45%   |
| LPDDR3  | 1         | 0.72%   |
| DRAM    | 1         | 0.72%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 78        | 56.12%  |
| SODIMM       | 57        | 41.01%  |
| FB-DIMM      | 2         | 1.44%   |
| Row Of Chips | 1         | 0.72%   |
| Chip         | 1         | 0.72%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 57        | 38.78%  |
| 8192  | 45        | 30.61%  |
| 16384 | 20        | 13.61%  |
| 2048  | 14        | 9.52%   |
| 1024  | 8         | 5.44%   |
| 32768 | 3         | 2.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 46        | 32.17%  |
| 1333    | 28        | 19.58%  |
| 2667    | 13        | 9.09%   |
| 2133    | 12        | 8.39%   |
| 3200    | 10        | 6.99%   |
| 2400    | 10        | 6.99%   |
| 800     | 6         | 4.2%    |
| 667     | 5         | 3.5%    |
| 2666    | 4         | 2.8%    |
| Unknown | 4         | 2.8%    |
| 1334    | 2         | 1.4%    |
| 1867    | 1         | 0.7%    |
| 1332    | 1         | 0.7%    |
| 333     | 1         | 0.7%    |

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


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Chicony Electronics   | 9         | 36%     |
| Bison Electronics     | 5         | 20%     |
| Realtek Semiconductor | 2         | 8%      |
| Microdia              | 2         | 8%      |
| IMC Networks          | 2         | 8%      |
| Syntek                | 1         | 4%      |
| Suyin                 | 1         | 4%      |
| Quanta                | 1         | 4%      |
| Logitech              | 1         | 4%      |
| Lenovo                | 1         | 4%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Bison Integrated Camera                  | 4         | 16%     |
| Syntek EasyCamera                        | 1         | 4%      |
| Suyin Asus Integrated Webcam             | 1         | 4%      |
| Realtek Integrated_Webcam_HD             | 1         | 4%      |
| Realtek Front Camera                     | 1         | 4%      |
| Quanta VGA WebCam                        | 1         | 4%      |
| Microdia REDRAGON Live Camera Audio      | 1         | 4%      |
| Microdia Integrated Webcam               | 1         | 4%      |
| Logitech Webcam C270                     | 1         | 4%      |
| Lenovo Integrated Webcam                 | 1         | 4%      |
| IMC Networks HP TrueVision HD Camera     | 1         | 4%      |
| IMC Networks EasyCamera                  | 1         | 4%      |
| Chicony USB2.0 HD UVC WebCam             | 1         | 4%      |
| Chicony USB 2.0 VGA UVC WebCam           | 1         | 4%      |
| Chicony TOSHIBA Web Camera - FHD         | 1         | 4%      |
| Chicony ThinkPad T490 Webcam             | 1         | 4%      |
| Chicony Realtek DMFT RGB                 | 1         | 4%      |
| Chicony Lenovo Integrated Camera (0.3MP) | 1         | 4%      |
| Chicony Integrated HP HD Webcam          | 1         | 4%      |
| Chicony Integrated Camera                | 1         | 4%      |
| Chicony Camera                           | 1         | 4%      |
| Bison ThinkPad P50 Integrated Camera     | 1         | 4%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 3         | 33.33%  |
| Upek             | 2         | 22.22%  |
| AuthenTec        | 2         | 22.22%  |
| Synaptics        | 1         | 11.11%  |
| Broadcom         | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 2         | 22.22%  |
| Validity Sensors VFS471 Fingerprint Reader                                   | 1         | 11.11%  |
| Validity Sensors VFS451 Fingerprint Reader                                   | 1         | 11.11%  |
| Validity Sensors VFS Fingerprint sensor                                      | 1         | 11.11%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 1         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 11.11%  |
| AuthenTec AES2810                                                            | 1         | 11.11%  |
| AuthenTec AES2501 Fingerprint Sensor                                         | 1         | 11.11%  |

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
| 1     | 61        | 39.1%   |
| 0     | 50        | 32.05%  |
| 2     | 32        | 20.51%  |
| 3     | 8         | 5.13%   |
| 4     | 3         | 1.92%   |
| 5     | 2         | 1.28%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 93        | 65.96%  |
| Net/wireless             | 13        | 9.22%   |
| Fingerprint reader       | 7         | 4.96%   |
| Card reader              | 7         | 4.96%   |
| Bluetooth                | 6         | 4.26%   |
| Firewire controller      | 4         | 2.84%   |
| Sound                    | 3         | 2.13%   |
| Graphics card            | 3         | 2.13%   |
| Storage/ata              | 2         | 1.42%   |
| Network                  | 2         | 1.42%   |
| Net/ethernet             | 1         | 0.71%   |

