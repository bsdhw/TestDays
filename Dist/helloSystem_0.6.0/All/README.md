helloSystem 0.6.0 - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for helloSystem 0.6.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/helloSystem_0.6.0/Desktop/README.md) and [notebooks](/Dist/helloSystem_0.6.0/Notebook/README.md).

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

Total: 174

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T470s 20HGS3RV0... | Notebook    | [271f4b1030](https://bsd-hardware.info/?probe=271f4b1030) | Jul 27, 2024 |
| Lenovo        | ThinkPad T470s 20HGS3RV0... | Notebook    | [a5fe1bd04d](https://bsd-hardware.info/?probe=a5fe1bd04d) | Jul 27, 2024 |
| ASUSTek       | X555LAB                     | Notebook    | [cc126b0787](https://bsd-hardware.info/?probe=cc126b0787) | Jun 06, 2024 |
| Toshiba       | Satellite C55-A             | Notebook    | [f27ea283cf](https://bsd-hardware.info/?probe=f27ea283cf) | Oct 12, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [a7fe22ce82](https://bsd-hardware.info/?probe=a7fe22ce82) | May 13, 2023 |
| HP            | 3048h                       | Desktop     | [3f43816a5d](https://bsd-hardware.info/?probe=3f43816a5d) | Nov 25, 2022 |
| Lenovo        | ThinkPad X61s 76693KG       | Notebook    | [445446cc28](https://bsd-hardware.info/?probe=445446cc28) | Jul 18, 2022 |
| Apple         | MacBookPro3,1               | Notebook    | [912d02aec2](https://bsd-hardware.info/?probe=912d02aec2) | Apr 28, 2022 |
| ASUSTek       | P6-P8H61E                   | Desktop     | [540f66f678](https://bsd-hardware.info/?probe=540f66f678) | Mar 29, 2022 |
| HP            | Pavilion dv6                | Notebook    | [dee0853f4b](https://bsd-hardware.info/?probe=dee0853f4b) | Mar 17, 2022 |
| Dell          | 0GXM1W A00                  | Desktop     | [c4d10a26fd](https://bsd-hardware.info/?probe=c4d10a26fd) | Mar 04, 2022 |
| Intel         | H81                         | Desktop     | [dd19abd47d](https://bsd-hardware.info/?probe=dd19abd47d) | Feb 25, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [478714c7c9](https://bsd-hardware.info/?probe=478714c7c9) | Feb 07, 2022 |
| Sony          | VPCEB1J1E                   | Notebook    | [04c5ee02da](https://bsd-hardware.info/?probe=04c5ee02da) | Feb 05, 2022 |
| Dell          | 014GRG A03                  | Desktop     | [8e0a22c065](https://bsd-hardware.info/?probe=8e0a22c065) | Jan 28, 2022 |
| Dell          | 014GRG A03                  | Desktop     | [5996ba19b1](https://bsd-hardware.info/?probe=5996ba19b1) | Jan 27, 2022 |
| Dell          | 014GRG A03                  | Desktop     | [223d955a90](https://bsd-hardware.info/?probe=223d955a90) | Jan 26, 2022 |
| Dell          | 05DN3X A00                  | Desktop     | [e0e63e69ef](https://bsd-hardware.info/?probe=e0e63e69ef) | Jan 23, 2022 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [bb6cc55d53](https://bsd-hardware.info/?probe=bb6cc55d53) | Jan 23, 2022 |
| Dell          | 05DN3X A00                  | Desktop     | [460ea5c41d](https://bsd-hardware.info/?probe=460ea5c41d) | Jan 23, 2022 |
| Toshiba       | Satellite L50-A             | Notebook    | [94b87158aa](https://bsd-hardware.info/?probe=94b87158aa) | Jan 21, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [53b106bbb6](https://bsd-hardware.info/?probe=53b106bbb6) | Jan 16, 2022 |
| Sony          | VPCYB45JB                   | Notebook    | [cd18905620](https://bsd-hardware.info/?probe=cd18905620) | Jan 09, 2022 |
| Lenovo        | G550 2958                   | Notebook    | [21407195e3](https://bsd-hardware.info/?probe=21407195e3) | Jan 07, 2022 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [f1fe3fe225](https://bsd-hardware.info/?probe=f1fe3fe225) | Dec 30, 2021 |
| Acer          | Aspire E1-421               | Notebook    | [b2aea3de1b](https://bsd-hardware.info/?probe=b2aea3de1b) | Dec 21, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [350def9eca](https://bsd-hardware.info/?probe=350def9eca) | Dec 19, 2021 |
| Lenovo        | ThinkPad T440p 20AW007QM... | Notebook    | [9efeb9ee24](https://bsd-hardware.info/?probe=9efeb9ee24) | Dec 16, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [d8bcea438a](https://bsd-hardware.info/?probe=d8bcea438a) | Dec 15, 2021 |
| Apple         | Mac-F2218EA9                | All in one  | [34ba809dc2](https://bsd-hardware.info/?probe=34ba809dc2) | Dec 14, 2021 |
| ASUSTek       | X502CA                      | Notebook    | [45f61ab19e](https://bsd-hardware.info/?probe=45f61ab19e) | Dec 14, 2021 |
| Apple         | Mac-F2218EA9                | All in one  | [e77489ad74](https://bsd-hardware.info/?probe=e77489ad74) | Dec 14, 2021 |
| ASUSTek       | H110M-K                     | Desktop     | [2921401f70](https://bsd-hardware.info/?probe=2921401f70) | Dec 12, 2021 |
| Dell          | Inspiron 3195               | Convertible | [8bbd2c16f7](https://bsd-hardware.info/?probe=8bbd2c16f7) | Dec 11, 2021 |
| HP            | 8054                        | Desktop     | [de953100f6](https://bsd-hardware.info/?probe=de953100f6) | Dec 10, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [a064edad4b](https://bsd-hardware.info/?probe=a064edad4b) | Dec 10, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [a9423b3232](https://bsd-hardware.info/?probe=a9423b3232) | Dec 09, 2021 |
| Acer          | Aspire 5749Z                | Notebook    | [60a25af38c](https://bsd-hardware.info/?probe=60a25af38c) | Dec 09, 2021 |
| Philco        | 10B                         | Notebook    | [a27148f35d](https://bsd-hardware.info/?probe=a27148f35d) | Dec 06, 2021 |
| Positivo      | C14CR01                     | Notebook    | [a33c158f9f](https://bsd-hardware.info/?probe=a33c158f9f) | Dec 05, 2021 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [35b01f0f56](https://bsd-hardware.info/?probe=35b01f0f56) | Dec 05, 2021 |
| ASUSTek       | UX31A                       | Notebook    | [9febab6c01](https://bsd-hardware.info/?probe=9febab6c01) | Dec 05, 2021 |
| Lenovo        | ThinkPad 13 20GJCTO1WW      | Notebook    | [e4b923d500](https://bsd-hardware.info/?probe=e4b923d500) | Dec 02, 2021 |
| ASUSTek       | X540LA                      | Notebook    | [0680188ca4](https://bsd-hardware.info/?probe=0680188ca4) | Dec 01, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [812c7f3e36](https://bsd-hardware.info/?probe=812c7f3e36) | Nov 29, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [bc3b65334e](https://bsd-hardware.info/?probe=bc3b65334e) | Nov 29, 2021 |
| Dell          | Inspiron 3195               | Convertible | [5680c947ae](https://bsd-hardware.info/?probe=5680c947ae) | Nov 26, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [ef35dd084e](https://bsd-hardware.info/?probe=ef35dd084e) | Nov 26, 2021 |
| Dell          | Inspiron 3195               | Convertible | [909ab22d27](https://bsd-hardware.info/?probe=909ab22d27) | Nov 25, 2021 |
| HP            | 0A80h                       | Desktop     | [1e1153ee69](https://bsd-hardware.info/?probe=1e1153ee69) | Nov 22, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [8fe8caf37d](https://bsd-hardware.info/?probe=8fe8caf37d) | Nov 21, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [afd0cf45c6](https://bsd-hardware.info/?probe=afd0cf45c6) | Nov 21, 2021 |
| Dell          | Inspiron 5566               | Notebook    | [7c6b2f2013](https://bsd-hardware.info/?probe=7c6b2f2013) | Nov 14, 2021 |
| Toshiba       | STI NA 1401                 | Notebook    | [bbbf661ee8](https://bsd-hardware.info/?probe=bbbf661ee8) | Nov 14, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [12a360ddd1](https://bsd-hardware.info/?probe=12a360ddd1) | Nov 14, 2021 |
| Toshiba       | PORTEGE M780                | Notebook    | [2ac9bea1e6](https://bsd-hardware.info/?probe=2ac9bea1e6) | Nov 13, 2021 |
| T-bao         | MINI PC V1.0                | Desktop     | [4ee7de3597](https://bsd-hardware.info/?probe=4ee7de3597) | Nov 12, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [04cc56305c](https://bsd-hardware.info/?probe=04cc56305c) | Nov 11, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [a1ece36be8](https://bsd-hardware.info/?probe=a1ece36be8) | Nov 11, 2021 |
| Dell          | Studio 1747                 | Notebook    | [b0a51ac0af](https://bsd-hardware.info/?probe=b0a51ac0af) | Nov 11, 2021 |
| Dell          | Studio 1747                 | Notebook    | [7ab6b58d69](https://bsd-hardware.info/?probe=7ab6b58d69) | Nov 11, 2021 |
| Acer          | Aspire 5742G                | Notebook    | [0513869be8](https://bsd-hardware.info/?probe=0513869be8) | Nov 09, 2021 |
| Lenovo        | ThinkPad T450s 20BX001PU... | Notebook    | [748312bfbf](https://bsd-hardware.info/?probe=748312bfbf) | Nov 07, 2021 |
| Itautec       | ST 4344 ST-4344 Padrao 0... | Desktop     | [ec13cb0829](https://bsd-hardware.info/?probe=ec13cb0829) | Nov 07, 2021 |
| Shuttle       | FH61R                       | Desktop     | [a231590743](https://bsd-hardware.info/?probe=a231590743) | Nov 07, 2021 |
| ASUSTek       | K52Jc                       | Notebook    | [fc919c73e3](https://bsd-hardware.info/?probe=fc919c73e3) | Nov 07, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [7e27b1bc46](https://bsd-hardware.info/?probe=7e27b1bc46) | Nov 07, 2021 |
| Intel         | H81                         | Desktop     | [7f07aecffc](https://bsd-hardware.info/?probe=7f07aecffc) | Nov 07, 2021 |
| HP            | 14                          | Notebook    | [e0c8e95e52](https://bsd-hardware.info/?probe=e0c8e95e52) | Nov 07, 2021 |
| Lenovo        | ThinkPad W520 4276CTO       | Notebook    | [9082353a69](https://bsd-hardware.info/?probe=9082353a69) | Nov 06, 2021 |
| Lenovo        | ThinkPad T420 4180EE8       | Notebook    | [5303c12fe5](https://bsd-hardware.info/?probe=5303c12fe5) | Nov 05, 2021 |
| ASRock        | X370 Gaming X               | Desktop     | [2a874a33dd](https://bsd-hardware.info/?probe=2a874a33dd) | Nov 05, 2021 |
| Lenovo        | SHARKBAY No DPK             | Desktop     | [b9ad64f354](https://bsd-hardware.info/?probe=b9ad64f354) | Nov 04, 2021 |
| Gigabyte      | F2A78M-DS2                  | Desktop     | [45576fddfa](https://bsd-hardware.info/?probe=45576fddfa) | Nov 02, 2021 |
| Lenovo        | IdeaPad Z360                | Notebook    | [796bd6482f](https://bsd-hardware.info/?probe=796bd6482f) | Nov 02, 2021 |
| Dell          | 0M5DCD A02                  | Desktop     | [4ff4198768](https://bsd-hardware.info/?probe=4ff4198768) | Nov 02, 2021 |
| Lenovo        | ThinkPad T430u 3352AA5      | Notebook    | [8619bcca35](https://bsd-hardware.info/?probe=8619bcca35) | Nov 01, 2021 |
| Gateway       | DX4840                      | Desktop     | [1d2e9e175c](https://bsd-hardware.info/?probe=1d2e9e175c) | Nov 01, 2021 |
| Apple         | MacBookAir5,1               | Notebook    | [b354b2bd4e](https://bsd-hardware.info/?probe=b354b2bd4e) | Oct 31, 2021 |
| HP            | Presario CQ43               | Notebook    | [b97d9ff563](https://bsd-hardware.info/?probe=b97d9ff563) | Oct 30, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [e25f042400](https://bsd-hardware.info/?probe=e25f042400) | Oct 30, 2021 |
| Unknown       | Intel X79                   | Desktop     | [044908e7c3](https://bsd-hardware.info/?probe=044908e7c3) | Oct 30, 2021 |
| Chuwi         | MiniBook                    | Notebook    | [4ce05f93a8](https://bsd-hardware.info/?probe=4ce05f93a8) | Oct 28, 2021 |
| Dell          | Precision M4600             | Notebook    | [2f848fd2c0](https://bsd-hardware.info/?probe=2f848fd2c0) | Oct 27, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [9f8010bdbe](https://bsd-hardware.info/?probe=9f8010bdbe) | Oct 25, 2021 |
| Sony          | SVS1511AJB                  | Notebook    | [a366b5fab3](https://bsd-hardware.info/?probe=a366b5fab3) | Oct 24, 2021 |
| Sony          | SVS1511AJB                  | Notebook    | [2333f62192](https://bsd-hardware.info/?probe=2333f62192) | Oct 24, 2021 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [9959c0900a](https://bsd-hardware.info/?probe=9959c0900a) | Oct 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [9996e06a3d](https://bsd-hardware.info/?probe=9996e06a3d) | Oct 22, 2021 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [b106820e47](https://bsd-hardware.info/?probe=b106820e47) | Oct 21, 2021 |
| Acer          | RS880M05                    | Desktop     | [4718f0cb0c](https://bsd-hardware.info/?probe=4718f0cb0c) | Oct 21, 2021 |
| Apple         | MacBookPro4,1               | Notebook    | [10861818b2](https://bsd-hardware.info/?probe=10861818b2) | Oct 20, 2021 |
| Apple         | Mac-F221BEC8                | Desktop     | [cb2cc35e6c](https://bsd-hardware.info/?probe=cb2cc35e6c) | Oct 19, 2021 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [3cf20ca77c](https://bsd-hardware.info/?probe=3cf20ca77c) | Oct 19, 2021 |
| Dell          | 0VRWRC A00                  | Desktop     | [9b4defb194](https://bsd-hardware.info/?probe=9b4defb194) | Oct 19, 2021 |
| HP            | Unknown                     | Notebook    | [ad95186d17](https://bsd-hardware.info/?probe=ad95186d17) | Oct 19, 2021 |
| Dell          | Studio 1747                 | Notebook    | [ca939fbe2f](https://bsd-hardware.info/?probe=ca939fbe2f) | Oct 19, 2021 |
| HP            | 3398                        | Desktop     | [892f19c9bd](https://bsd-hardware.info/?probe=892f19c9bd) | Oct 18, 2021 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [0cdd3497f6](https://bsd-hardware.info/?probe=0cdd3497f6) | Oct 18, 2021 |
| HP            | 15                          | Notebook    | [e3f26d7245](https://bsd-hardware.info/?probe=e3f26d7245) | Oct 18, 2021 |
| Gigabyte      | G41MT-S2                    | Desktop     | [2847d63db0](https://bsd-hardware.info/?probe=2847d63db0) | Oct 18, 2021 |
| ASUSTek       | P5P43TD PRO                 | Desktop     | [2870e26de1](https://bsd-hardware.info/?probe=2870e26de1) | Oct 17, 2021 |
| Acidanther... | Mac-42FD25EABCABB274 iMa... | All in one  | [951eb91342](https://bsd-hardware.info/?probe=951eb91342) | Oct 17, 2021 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [48169f1d3c](https://bsd-hardware.info/?probe=48169f1d3c) | Oct 16, 2021 |
| Intel         | NUC8BEB J72688-308          | Mini pc     | [f2f7fc6463](https://bsd-hardware.info/?probe=f2f7fc6463) | Oct 15, 2021 |
| Lenovo        | SHARKBAY No DPK             | Desktop     | [14dcd924b5](https://bsd-hardware.info/?probe=14dcd924b5) | Oct 13, 2021 |
| Lenovo        | ThinkPad L440 20ASS0FP00    | Notebook    | [d92e6e3c21](https://bsd-hardware.info/?probe=d92e6e3c21) | Oct 11, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [abf8bb08a6](https://bsd-hardware.info/?probe=abf8bb08a6) | Oct 11, 2021 |
| ASUSTek       | U33Jc                       | Notebook    | [07f11b6604](https://bsd-hardware.info/?probe=07f11b6604) | Oct 10, 2021 |
| Medion        | H61H2-LM3                   | Desktop     | [67ed0f639c](https://bsd-hardware.info/?probe=67ed0f639c) | Oct 10, 2021 |
| MSI           | MS-16F1                     | Notebook    | [72b9db306a](https://bsd-hardware.info/?probe=72b9db306a) | Oct 09, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [e24f67a603](https://bsd-hardware.info/?probe=e24f67a603) | Oct 08, 2021 |
| Lenovo        | S20-30 Touch 20434          | Notebook    | [141a393d54](https://bsd-hardware.info/?probe=141a393d54) | Oct 08, 2021 |
| MSI           | G41M-P25                    | Desktop     | [21eec496b4](https://bsd-hardware.info/?probe=21eec496b4) | Oct 08, 2021 |
| Lenovo        | ThinkPad X250 20CLS2A11K    | Notebook    | [e47f4113bf](https://bsd-hardware.info/?probe=e47f4113bf) | Oct 08, 2021 |
| ASRock        | A320M-DGS                   | Desktop     | [11cf5c923a](https://bsd-hardware.info/?probe=11cf5c923a) | Oct 08, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [d09f63f257](https://bsd-hardware.info/?probe=d09f63f257) | Oct 07, 2021 |
| Acer          | Aspire 5741                 | Notebook    | [fd4e40a8d9](https://bsd-hardware.info/?probe=fd4e40a8d9) | Oct 07, 2021 |
| Intel         | H61                         | Desktop     | [6ce71c1b9e](https://bsd-hardware.info/?probe=6ce71c1b9e) | Oct 06, 2021 |
| Lenovo        | ThinkPad R500 2718W92       | Notebook    | [384f10861a](https://bsd-hardware.info/?probe=384f10861a) | Oct 05, 2021 |
| ASUSTek       | UX21A                       | Notebook    | [fe08d28d4c](https://bsd-hardware.info/?probe=fe08d28d4c) | Oct 05, 2021 |
| Itautec       | Infoway w7530               | Notebook    | [a376201681](https://bsd-hardware.info/?probe=a376201681) | Oct 05, 2021 |
| HP            | 3397                        | Desktop     | [4c71aae5bf](https://bsd-hardware.info/?probe=4c71aae5bf) | Oct 05, 2021 |
| HP            | 81BA                        | All in one  | [c2204a3dd2](https://bsd-hardware.info/?probe=c2204a3dd2) | Oct 04, 2021 |
| ASRock        | B365M-ITX/ac                | Desktop     | [1c8820a6d0](https://bsd-hardware.info/?probe=1c8820a6d0) | Oct 04, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f02ef8c047](https://bsd-hardware.info/?probe=f02ef8c047) | Oct 04, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [43388a27a4](https://bsd-hardware.info/?probe=43388a27a4) | Oct 04, 2021 |
| Dell          | Latitude E4300              | Notebook    | [fdb3de3036](https://bsd-hardware.info/?probe=fdb3de3036) | Oct 03, 2021 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [bd312d1c88](https://bsd-hardware.info/?probe=bd312d1c88) | Oct 03, 2021 |
| HP            | ProLiant ML350 G5           | Desktop     | [4d525cba3e](https://bsd-hardware.info/?probe=4d525cba3e) | Oct 03, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [748b6d14f4](https://bsd-hardware.info/?probe=748b6d14f4) | Oct 02, 2021 |
| Toshiba       | dynabook RX3 SM240E/3HD     | Notebook    | [2fe863dff4](https://bsd-hardware.info/?probe=2fe863dff4) | Oct 01, 2021 |
| Toshiba       | Satellite S55t-B            | Notebook    | [445fe665b8](https://bsd-hardware.info/?probe=445fe665b8) | Oct 01, 2021 |
| HP            | Pavilion dm4                | Notebook    | [bb5a564a50](https://bsd-hardware.info/?probe=bb5a564a50) | Sep 30, 2021 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [9b14548c15](https://bsd-hardware.info/?probe=9b14548c15) | Sep 21, 2021 |
| Sapphire      | EDGE-FT1M1 E450 1AOVU044    | Desktop     | [ea8fefdf4e](https://bsd-hardware.info/?probe=ea8fefdf4e) | Sep 20, 2021 |
| Dell          | 0MGK50 A02                  | Desktop     | [9d2959b4f1](https://bsd-hardware.info/?probe=9d2959b4f1) | Sep 20, 2021 |
| HP            | 81B4 01                     | Desktop     | [179504116d](https://bsd-hardware.info/?probe=179504116d) | Sep 20, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [790d020ebe](https://bsd-hardware.info/?probe=790d020ebe) | Sep 19, 2021 |
| Lenovo        | G500s 20245                 | Notebook    | [88cd1ca7bd](https://bsd-hardware.info/?probe=88cd1ca7bd) | Sep 18, 2021 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [9b046b157e](https://bsd-hardware.info/?probe=9b046b157e) | Sep 17, 2021 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [0f6e7e26fc](https://bsd-hardware.info/?probe=0f6e7e26fc) | Sep 11, 2021 |
| HP            | 3397                        | Desktop     | [5d95b75768](https://bsd-hardware.info/?probe=5d95b75768) | Sep 06, 2021 |
| Kraftway      | KW10T                       | Notebook    | [4810842d82](https://bsd-hardware.info/?probe=4810842d82) | Sep 06, 2021 |
| Medion        | H61H2-LM3                   | Desktop     | [eb81abe401](https://bsd-hardware.info/?probe=eb81abe401) | Sep 02, 2021 |
| ASRock        | Z390 Pro4                   | Desktop     | [ecbf097bc5](https://bsd-hardware.info/?probe=ecbf097bc5) | Sep 02, 2021 |
| Dell          | Latitude 3540               | Notebook    | [2583b22e8d](https://bsd-hardware.info/?probe=2583b22e8d) | Aug 29, 2021 |
| Dell          | Latitude 3540               | Notebook    | [de97e0b2fc](https://bsd-hardware.info/?probe=de97e0b2fc) | Aug 29, 2021 |
| ASUSTek       | TUF B360M-PLUS GAMING S     | Desktop     | [33ba0b7c38](https://bsd-hardware.info/?probe=33ba0b7c38) | Aug 29, 2021 |
| Itautec       | Infoway w7530               | Notebook    | [d91ec24ce0](https://bsd-hardware.info/?probe=d91ec24ce0) | Aug 29, 2021 |
| Toshiba       | Satellite S55t-B            | Notebook    | [5aaacec4ad](https://bsd-hardware.info/?probe=5aaacec4ad) | Aug 23, 2021 |
| Toshiba       | Satellite S55t-B            | Notebook    | [d74035a8e7](https://bsd-hardware.info/?probe=d74035a8e7) | Aug 23, 2021 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [5fe1a9e521](https://bsd-hardware.info/?probe=5fe1a9e521) | Aug 16, 2021 |
| ASUSTek       | Q505UAR                     | Convertible | [b745dee7d6](https://bsd-hardware.info/?probe=b745dee7d6) | Aug 14, 2021 |
| Lenovo        | ThinkPad X230 23062S2       | Notebook    | [bceadf5c66](https://bsd-hardware.info/?probe=bceadf5c66) | Aug 05, 2021 |
| PCPartner     | MILANO-P Rev.00             | Desktop     | [ef8217ac30](https://bsd-hardware.info/?probe=ef8217ac30) | Aug 01, 2021 |
| Intel         | NUC5i3RYB K23918-501        | Mini pc     | [1c3ec31075](https://bsd-hardware.info/?probe=1c3ec31075) | Jul 28, 2021 |
| Lenovo        | ThinkPad SL 2746M3C         | Notebook    | [aa10433581](https://bsd-hardware.info/?probe=aa10433581) | Jul 28, 2021 |
| ASUSTek       | H110M-PLUS                  | Desktop     | [d0f2da9c41](https://bsd-hardware.info/?probe=d0f2da9c41) | Jul 21, 2021 |
| Lenovo        | ThinkPad X230 2325IG2       | Notebook    | [158ecc5e0b](https://bsd-hardware.info/?probe=158ecc5e0b) | Jul 14, 2021 |
| Gigabyte      | H110-D3A-CF                 | Desktop     | [2c390b4301](https://bsd-hardware.info/?probe=2c390b4301) | Jul 09, 2021 |
| Gigabyte      | H110-D3A-CF                 | Desktop     | [aea3a11daf](https://bsd-hardware.info/?probe=aea3a11daf) | Jul 08, 2021 |
| eMachines     | eM350                       | Notebook    | [94579b896e](https://bsd-hardware.info/?probe=94579b896e) | Jul 04, 2021 |
| Lenovo        | B590 62743PG                | Notebook    | [2400297995](https://bsd-hardware.info/?probe=2400297995) | Jul 03, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [6cf3337855](https://bsd-hardware.info/?probe=6cf3337855) | Jul 01, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [e7a0dfcecf](https://bsd-hardware.info/?probe=e7a0dfcecf) | Jun 28, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [ceb18e38a3](https://bsd-hardware.info/?probe=ceb18e38a3) | Jun 28, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [1a35d2f6ab](https://bsd-hardware.info/?probe=1a35d2f6ab) | Jun 26, 2021 |
| eMachines     | eM350                       | Notebook    | [52198cfd80](https://bsd-hardware.info/?probe=52198cfd80) | Jun 22, 2021 |
| eMachines     | eM350                       | Notebook    | [60b4338ace](https://bsd-hardware.info/?probe=60b4338ace) | Jun 22, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [bb13e61de1](https://bsd-hardware.info/?probe=bb13e61de1) | Jun 21, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [0e448af5f5](https://bsd-hardware.info/?probe=0e448af5f5) | Jun 18, 2021 |
| Dell          | Latitude 7280               | Notebook    | [8fd335f46f](https://bsd-hardware.info/?probe=8fd335f46f) | Jun 18, 2021 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [b0b67667d3](https://bsd-hardware.info/?probe=b0b67667d3) | Jun 16, 2021 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 141       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 139       | 97.89%  |
| XFCE         | 1         | 0.7%    |
| KDE5         | 1         | 0.7%    |
| GNOME        | 1         | 0.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 141       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| SLiM | 141       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 137       | 97.16%  |
| de_DE   | 2         | 1.42%   |
| ru_RU   | 1         | 0.71%   |
| Unknown | 1         | 0.71%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 115       | 80.99%  |
| BIOS | 27        | 19.01%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 141       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 141       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 29        | 20.57%  |
| ASUSTek Computer    | 21        | 14.89%  |
| Hewlett-Packard     | 17        | 12.06%  |
| Dell                | 15        | 10.64%  |
| ASRock              | 8         | 5.67%   |
| Gigabyte Technology | 7         | 4.96%   |
| Apple               | 6         | 4.26%   |
| Toshiba             | 5         | 3.55%   |
| MSI                 | 5         | 3.55%   |
| Acer                | 5         | 3.55%   |
| Intel               | 4         | 2.84%   |
| Sony                | 3         | 2.13%   |
| Itautec             | 2         | 1.42%   |
| T-bao               | 1         | 0.71%   |
| Shuttle             | 1         | 0.71%   |
| Semp Toshiba        | 1         | 0.71%   |
| Sapphire            | 1         | 0.71%   |
| Positivo            | 1         | 0.71%   |
| Philco              | 1         | 0.71%   |
| Medion              | 1         | 0.71%   |
| Kraftway            | 1         | 0.71%   |
| Gateway             | 1         | 0.71%   |
| Fujitsu             | 1         | 0.71%   |
| eMachines           | 1         | 0.71%   |
| Chuwi               | 1         | 0.71%   |
| Acidanthera         | 1         | 0.71%   |
| Unknown             | 1         | 0.71%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 2         | 1.42%   |
| Toshiba Satellite S55t-B                   | 1         | 0.71%   |
| Toshiba Satellite L50-A                    | 1         | 0.71%   |
| Toshiba Satellite C55-A                    | 1         | 0.71%   |
| Toshiba PORTEGE M780                       | 1         | 0.71%   |
| Toshiba dynabook RX3 SM240E/3HD            | 1         | 0.71%   |
| T-bao MINI PC                              | 1         | 0.71%   |
| Sony VPCYB45JB                             | 1         | 0.71%   |
| Sony VPCEB1J1E                             | 1         | 0.71%   |
| Sony SVS1511AJB                            | 1         | 0.71%   |
| Shuttle SH61R                              | 1         | 0.71%   |
| Semp Toshiba STI NA 1401                   | 1         | 0.71%   |
| Sapphire EDGE-FT1M1 E450 1AOVU044          | 1         | 0.71%   |
| Positivo C14CR01                           | 1         | 0.71%   |
| Philco 10B                                 | 1         | 0.71%   |
| MSI MS-7C91                                | 1         | 0.71%   |
| MSI MS-7B93                                | 1         | 0.71%   |
| MSI MS-7A40                                | 1         | 0.71%   |
| MSI MS-7592                                | 1         | 0.71%   |
| MSI MS-16F1                                | 1         | 0.71%   |
| Medion H61H2-LM3                           | 1         | 0.71%   |
| Lenovo Yoga 3 Pro-1370 80HE                | 1         | 0.71%   |
| Lenovo ThinkPad Yoga 11e 20DAS0AE00        | 1         | 0.71%   |
| Lenovo ThinkPad X61s 76693KG               | 1         | 0.71%   |
| Lenovo ThinkPad X250 20CLS2A11K            | 1         | 0.71%   |
| Lenovo ThinkPad X230 2325IG2               | 1         | 0.71%   |
| Lenovo ThinkPad X230 23062S2               | 1         | 0.71%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWA003CD | 1         | 0.71%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A70066UK   | 1         | 0.71%   |
| Lenovo ThinkPad W520 4276CTO               | 1         | 0.71%   |
| Lenovo ThinkPad T470s 20HGS3RV00           | 1         | 0.71%   |
| Lenovo ThinkPad T450s 20BX001PUS           | 1         | 0.71%   |
| Lenovo ThinkPad T440p 20AW007QMS           | 1         | 0.71%   |
| Lenovo ThinkPad T430u 3352AA5              | 1         | 0.71%   |
| Lenovo ThinkPad T420 4180EE8               | 1         | 0.71%   |
| Lenovo ThinkPad SL 2746M3C                 | 1         | 0.71%   |
| Lenovo ThinkPad R500 2718W92               | 1         | 0.71%   |
| Lenovo ThinkPad L440 20ASS0FP00            | 1         | 0.71%   |
| Lenovo ThinkPad 13 20GJCTO1WW              | 1         | 0.71%   |
| Lenovo ThinkCentre M83 10AHS35Q00          | 1         | 0.71%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 17        | 12.06%  |
| Dell OptiPlex       | 5         | 3.55%   |
| Dell Inspiron       | 4         | 2.84%   |
| Acer Aspire         | 4         | 2.84%   |
| Toshiba Satellite   | 3         | 2.13%   |
| Lenovo IdeaPad      | 3         | 2.13%   |
| HP Compaq           | 3         | 2.13%   |
| Dell Latitude       | 3         | 2.13%   |
| ASUS TUF            | 3         | 2.13%   |
| Lenovo ThinkCentre  | 2         | 1.42%   |
| Itautec Infoway     | 2         | 1.42%   |
| HP Pavilion         | 2         | 1.42%   |
| HP EliteBook        | 2         | 1.42%   |
| Dell Studio         | 2         | 1.42%   |
| Unknown             | 2         | 1.42%   |
| Toshiba PORTEGE     | 1         | 0.71%   |
| Toshiba dynabook    | 1         | 0.71%   |
| T-bao MINI          | 1         | 0.71%   |
| Sony VPCYB45JB      | 1         | 0.71%   |
| Sony VPCEB1J1E      | 1         | 0.71%   |
| Sony SVS1511AJB     | 1         | 0.71%   |
| Shuttle SH61R       | 1         | 0.71%   |
| Semp Toshiba STI    | 1         | 0.71%   |
| Sapphire EDGE-FT1M1 | 1         | 0.71%   |
| Positivo C14CR01    | 1         | 0.71%   |
| Philco 10B          | 1         | 0.71%   |
| MSI MS-7C91         | 1         | 0.71%   |
| MSI MS-7B93         | 1         | 0.71%   |
| MSI MS-7A40         | 1         | 0.71%   |
| MSI MS-7592         | 1         | 0.71%   |
| MSI MS-16F1         | 1         | 0.71%   |
| Medion H61H2-LM3    | 1         | 0.71%   |
| Lenovo Yoga         | 1         | 0.71%   |
| Lenovo S20-30       | 1         | 0.71%   |
| Lenovo G580         | 1         | 0.71%   |
| Lenovo G550         | 1         | 0.71%   |
| Lenovo G500s        | 1         | 0.71%   |
| Lenovo G500         | 1         | 0.71%   |
| Lenovo B590         | 1         | 0.71%   |
| Kraftway KW10T      | 1         | 0.71%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2013 | 18        | 12.77%  |
| 2012 | 15        | 10.64%  |
| 2019 | 14        | 9.93%   |
| 2011 | 13        | 9.22%   |
| 2010 | 13        | 9.22%   |
| 2020 | 10        | 7.09%   |
| 2015 | 10        | 7.09%   |
| 2014 | 10        | 7.09%   |
| 2021 | 8         | 5.67%   |
| 2018 | 7         | 4.96%   |
| 2016 | 7         | 4.96%   |
| 2009 | 6         | 4.26%   |
| 2017 | 5         | 3.55%   |
| 2008 | 3         | 2.13%   |
| 2007 | 2         | 1.42%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 74        | 52.48%  |
| Desktop     | 61        | 43.26%  |
| Convertible | 2         | 1.42%   |
| Mini pc     | 2         | 1.42%   |
| All in one  | 2         | 1.42%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 141       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 50        | 35.21%  |
| 4.01-8.0    | 46        | 32.39%  |
| 16.01-24.0  | 31        | 21.83%  |
| 32.01-64.0  | 10        | 7.04%   |
| 64.01-256.0 | 3         | 2.11%   |
| 3.01-4.0    | 1         | 0.7%    |
| 2.01-3.0    | 1         | 0.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 81        | 57.04%  |
| 0.51-1.0 | 47        | 33.1%   |
| 1.01-2.0 | 11        | 7.75%   |
| 3.01-4.0 | 2         | 1.41%   |
| 2.01-3.0 | 1         | 0.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 93        | 65.03%  |
| 2      | 26        | 18.18%  |
| 3      | 12        | 8.39%   |
| 4      | 8         | 5.59%   |
| 0      | 3         | 2.1%    |
| 5      | 1         | 0.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 78        | 55.32%  |
| Yes       | 63        | 44.68%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 132       | 93.62%  |
| No        | 9         | 6.38%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 97        | 68.79%  |
| No        | 44        | 31.21%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 83        | 58.87%  |
| Yes       | 58        | 41.13%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 22        | 15.6%   |
| Brazil      | 14        | 9.93%   |
| Germany     | 12        | 8.51%   |
| Russia      | 11        | 7.8%    |
| Ukraine     | 6         | 4.26%   |
| Spain       | 6         | 4.26%   |
| Poland      | 6         | 4.26%   |
| Italy       | 6         | 4.26%   |
| China       | 5         | 3.55%   |
| Australia   | 5         | 3.55%   |
| UK          | 4         | 2.84%   |
| Netherlands | 4         | 2.84%   |
| Mexico      | 4         | 2.84%   |
| Canada      | 3         | 2.13%   |
| South Korea | 2         | 1.42%   |
| New Zealand | 2         | 1.42%   |
| India       | 2         | 1.42%   |
| Chile       | 2         | 1.42%   |
| Bulgaria    | 2         | 1.42%   |
| Venezuela   | 1         | 0.71%   |
| Turkey      | 1         | 0.71%   |
| Thailand    | 1         | 0.71%   |
| Taiwan      | 1         | 0.71%   |
| Syria       | 1         | 0.71%   |
| Switzerland | 1         | 0.71%   |
| Slovakia    | 1         | 0.71%   |
| Singapore   | 1         | 0.71%   |
| Peru        | 1         | 0.71%   |
| Lithuania   | 1         | 0.71%   |
| Libya       | 1         | 0.71%   |
| Japan       | 1         | 0.71%   |
| Israel      | 1         | 0.71%   |
| Hungary     | 1         | 0.71%   |
| Hong Kong   | 1         | 0.71%   |
| Guatemala   | 1         | 0.71%   |
| Greece      | 1         | 0.71%   |
| France      | 1         | 0.71%   |
| Finland     | 1         | 0.71%   |
| Denmark     | 1         | 0.71%   |
| Czechia     | 1         | 0.71%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Harrisburg        | 3         | 2.08%   |
| Tula de Allende   | 2         | 1.39%   |
| Santiago          | 2         | 1.39%   |
| Nampa             | 2         | 1.39%   |
| Marlborough       | 2         | 1.39%   |
| Maraba            | 2         | 1.39%   |
| Kyiv              | 2         | 1.39%   |
| Hobart            | 2         | 1.39%   |
| Guangzhou         | 2         | 1.39%   |
| Frankfurt am Main | 2         | 1.39%   |
| Ernakulam         | 2         | 1.39%   |
| Barcelona         | 2         | 1.39%   |
| Yeongdong-gun     | 1         | 0.69%   |
| Yekaterinburg     | 1         | 0.69%   |
| Xiamen            | 1         | 0.69%   |
| Wroclaw           | 1         | 0.69%   |
| Wolgast           | 1         | 0.69%   |
| Wellington        | 1         | 0.69%   |
| Warrenton         | 1         | 0.69%   |
| Voronezh          | 1         | 0.69%   |
| Ufa               | 1         | 0.69%   |
| Tyumen            | 1         | 0.69%   |
| Tripoli           | 1         | 0.69%   |
| Torre del Mar     | 1         | 0.69%   |
| The Hague         | 1         | 0.69%   |
| Tampa             | 1         | 0.69%   |
| Taito             | 1         | 0.69%   |
| Stuttgart         | 1         | 0.69%   |
| Stralsund         | 1         | 0.69%   |
| Stara Zagora      | 1         | 0.69%   |
| Stade             | 1         | 0.69%   |
| St Petersburg     | 1         | 0.69%   |
| Sofia             | 1         | 0.69%   |
| Sitriyya          | 1         | 0.69%   |
| Singapore         | 1         | 0.69%   |
| Siedlce           | 1         | 0.69%   |
| Sherwood Park     | 1         | 0.69%   |
| Shepetivka        | 1         | 0.69%   |
| Seoul             | 1         | 0.69%   |
| Seattle           | 1         | 0.69%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 36        | 43     | 18.85%  |
| WDC                 | 34        | 40     | 17.8%   |
| Samsung Electronics | 27        | 33     | 14.14%  |
| Toshiba             | 16        | 20     | 8.38%   |
| Crucial             | 10        | 13     | 5.24%   |
| Kingston            | 9         | 13     | 4.71%   |
| Hitachi             | 9         | 11     | 4.71%   |
| SanDisk             | 6         | 6      | 3.14%   |
| Intel               | 3         | 3      | 1.57%   |
| HGST                | 3         | 3      | 1.57%   |
| Corsair             | 3         | 3      | 1.57%   |
| China               | 3         | 3      | 1.57%   |
| A-DATA Technology   | 3         | 5      | 1.57%   |
| SPCC                | 2         | 2      | 1.05%   |
| Smartbuy            | 2         | 2      | 1.05%   |
| Plextor             | 2         | 2      | 1.05%   |
| OCZ                 | 2         | 2      | 1.05%   |
| KingSpec            | 2         | 3      | 1.05%   |
| Gigabyte Technology | 2         | 2      | 1.05%   |
| Apacer              | 2         | 2      | 1.05%   |
| Verbatim            | 1         | 1      | 0.52%   |
| Transcend           | 1         | 1      | 0.52%   |
| Silicon Motion      | 1         | 1      | 0.52%   |
| PNY                 | 1         | 1      | 0.52%   |
| Patriot             | 1         | 1      | 0.52%   |
| Micron Technology   | 1         | 1      | 0.52%   |
| LITEONIT            | 1         | 1      | 0.52%   |
| LITEON              | 1         | 1      | 0.52%   |
| Lexar               | 1         | 1      | 0.52%   |
| Leven               | 1         | 1      | 0.52%   |
| Hewlett-Packard     | 1         | 1      | 0.52%   |
| GOODRAM             | 1         | 1      | 0.52%   |
| FORESEE             | 1         | 1      | 0.52%   |
| Apple               | 1         | 1      | 0.52%   |
| AMD                 | 1         | 1      | 0.52%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB | 4         | 1.9%    |
| Toshiba MQ01ABF050 500GB           | 3         | 1.42%   |
| Toshiba MQ01ABD100 1TB             | 3         | 1.42%   |
| Seagate ST9500325AS 500GB          | 3         | 1.42%   |
| Samsung SSD 860 EVO 500GB          | 3         | 1.42%   |
| Samsung SSD 860 EVO 1TB            | 3         | 1.42%   |
| WDC WDS100T2B0C-00PXH0 1TB         | 2         | 0.95%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 2         | 0.95%   |
| Toshiba DT01ACA100 1TB             | 2         | 0.95%   |
| Seagate ST9500420AS 500GB          | 2         | 0.95%   |
| Seagate ST500LT012-1DG142 500GB    | 2         | 0.95%   |
| Seagate ST3500312CS 500GB          | 2         | 0.95%   |
| Seagate ST1000LM048-2E7172 1TB     | 2         | 0.95%   |
| SanDisk SDSSDA240G 240GB           | 2         | 0.95%   |
| SanDisk SD5SE2256G1002E 256GB      | 2         | 0.95%   |
| Samsung SSD 970 EVO Plus 500GB     | 2         | 0.95%   |
| Samsung SSD 850 EVO 250GB          | 2         | 0.95%   |
| Samsung MZ7TE128HMGR-000L1 128GB   | 2         | 0.95%   |
| Samsung HD322HJ 320GB              | 2         | 0.95%   |
| Kingston SA400S37960G 960GB        | 2         | 0.95%   |
| Hitachi HTS545025B9A300 250GB      | 2         | 0.95%   |
| Crucial CT500MX500SSD1 500GB       | 2         | 0.95%   |
| Crucial CT250MX500SSD1 250GB       | 2         | 0.95%   |
| China SATA SSD 120GB               | 2         | 0.95%   |
| WDC WDS500G2B0A-00SM50 500GB       | 1         | 0.47%   |
| WDC WDS250G2X0C-00L350 250GB       | 1         | 0.47%   |
| WDC WDS240G2G0A-00JH30 240GB       | 1         | 0.47%   |
| WDC WD800JD-00LSA0 80GB            | 1         | 0.47%   |
| WDC WD5000LPCX-00VHAT0 500GB       | 1         | 0.47%   |
| WDC WD5000BPKT-00PK4T0 500GB       | 1         | 0.47%   |
| WDC WD5000BEKT-60KA9T0 500GB       | 1         | 0.47%   |
| WDC WD5000AAVS-00ZTB0 500GB        | 1         | 0.47%   |
| WDC WD5000AAKX-08ERMA0 500GB       | 1         | 0.47%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 1         | 0.47%   |
| WDC WD5000AAKS-08V0A0 500GB        | 1         | 0.47%   |
| WDC WD5000AAKS-00V1A0 500GB        | 1         | 0.47%   |
| WDC WD40EZRZ-22GXCB0 4TB           | 1         | 0.47%   |
| WDC WD40EFRX-68N32N0 4TB           | 1         | 0.47%   |
| WDC WD3200BEVT-80A0RT0 320GB       | 1         | 0.47%   |
| WDC WD3200AAKS-00UU3A0 320GB       | 1         | 0.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 36        | 43     | 36%     |
| WDC                 | 30        | 35     | 30%     |
| Toshiba             | 16        | 20     | 16%     |
| Hitachi             | 9         | 11     | 9%      |
| Samsung Electronics | 5         | 7      | 5%      |
| HGST                | 3         | 3      | 3%      |
| Hewlett-Packard     | 1         | 1      | 1%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 17        | 19     | 22.08%  |
| Crucial             | 10        | 13     | 12.99%  |
| Kingston            | 9         | 13     | 11.69%  |
| SanDisk             | 6         | 6      | 7.79%   |
| China               | 3         | 3      | 3.9%    |
| WDC                 | 2         | 2      | 2.6%    |
| Smartbuy            | 2         | 2      | 2.6%    |
| Plextor             | 2         | 2      | 2.6%    |
| OCZ                 | 2         | 2      | 2.6%    |
| KingSpec            | 2         | 3      | 2.6%    |
| Intel               | 2         | 2      | 2.6%    |
| Corsair             | 2         | 2      | 2.6%    |
| Apacer              | 2         | 2      | 2.6%    |
| Verbatim            | 1         | 1      | 1.3%    |
| Transcend           | 1         | 1      | 1.3%    |
| SPCC                | 1         | 1      | 1.3%    |
| PNY                 | 1         | 1      | 1.3%    |
| Patriot             | 1         | 1      | 1.3%    |
| Micron Technology   | 1         | 1      | 1.3%    |
| LITEONIT            | 1         | 1      | 1.3%    |
| LITEON              | 1         | 1      | 1.3%    |
| Lexar               | 1         | 1      | 1.3%    |
| Leven               | 1         | 1      | 1.3%    |
| GOODRAM             | 1         | 1      | 1.3%    |
| Gigabyte Technology | 1         | 1      | 1.3%    |
| FORESEE             | 1         | 1      | 1.3%    |
| Apple               | 1         | 1      | 1.3%    |
| AMD                 | 1         | 1      | 1.3%    |
| A-DATA Technology   | 1         | 2      | 1.3%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 82        | 120    | 49.1%   |
| SSD  | 69        | 88     | 41.32%  |
| NVMe | 16        | 18     | 9.58%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 130       | 208    | 89.04%  |
| NVMe | 16        | 18     | 10.96%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 105       | 143    | 64.42%  |
| 0.51-1.0   | 42        | 46     | 25.77%  |
| 1.01-2.0   | 8         | 9      | 4.91%   |
| 2.01-3.0   | 4         | 6      | 2.45%   |
| 3.01-4.0   | 3         | 3      | 1.84%   |
| 4.01-10.0  | 1         | 1      | 0.61%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 86        | 59.31%  |
| 101-250    | 32        | 22.07%  |
| 251-500    | 17        | 11.72%  |
| 501-1000   | 7         | 4.83%   |
| 51-100     | 2         | 1.38%   |
| 21-50      | 1         | 0.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 141       | 100%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                           | Computers | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| Seagate ST9500420AS 500GB                       | 2         | 2      | 5%      |
| Samsung Electronics HD322HJ 320GB               | 2         | 2      | 5%      |
| WDC WD5000AAKX-08ERMA0 500GB                    | 1         | 1      | 2.5%    |
| WDC WD5000AAKX-00ERMA0 500GB                    | 1         | 1      | 2.5%    |
| WDC WD5000AAKS-08V0A0 500GB                     | 1         | 1      | 2.5%    |
| WDC WD5000AAKS-00V1A0 500GB                     | 1         | 1      | 2.5%    |
| WDC WD3200BPVT-22JJ5T0 320GB                    | 1         | 1      | 2.5%    |
| WDC WD3200BEVT-80A0RT0 320GB                    | 1         | 1      | 2.5%    |
| WDC WD3200AAKS-00UU3A0 320GB                    | 1         | 1      | 2.5%    |
| WDC WD10JMVW-11AJGS0 1TB                        | 1         | 1      | 2.5%    |
| Toshiba MQ01UBD100 1TB                          | 1         | 1      | 2.5%    |
| Toshiba MQ01ABF050 500GB                        | 1         | 2      | 2.5%    |
| Toshiba MQ01ABD050 500GB                        | 1         | 1      | 2.5%    |
| Toshiba MK5061GSYN 500GB                        | 1         | 1      | 2.5%    |
| Toshiba MK3261GSYN 320GB                        | 1         | 2      | 2.5%    |
| Toshiba MK1252GSX 120GB                         | 1         | 1      | 2.5%    |
| Toshiba DT01ACA100 1TB                          | 1         | 2      | 2.5%    |
| Seagate ST9500325AS 500GB                       | 1         | 1      | 2.5%    |
| Seagate ST9320325AS 320GB                       | 1         | 1      | 2.5%    |
| Seagate ST750LM022 HN-M750MBB 752GB             | 1         | 1      | 2.5%    |
| Seagate ST500LT012-9WS142 500GB                 | 1         | 1      | 2.5%    |
| Seagate ST500LT012-1DG142 500GB                 | 1         | 1      | 2.5%    |
| Seagate ST500LM021-1KJ152 500GB                 | 1         | 1      | 2.5%    |
| Seagate ST500DM002-1BD142 500GB                 | 1         | 1      | 2.5%    |
| Seagate ST3500413AS 500GB                       | 1         | 1      | 2.5%    |
| Seagate ST320LT012-9WS14C 320GB                 | 1         | 1      | 2.5%    |
| Seagate ST1000LM048-2E7172 1TB                  | 1         | 1      | 2.5%    |
| Seagate ST1000LM024 HN-M101MBB 1TB              | 1         | 1      | 2.5%    |
| SanDisk SDSSDA240G 240GB                        | 1         | 1      | 2.5%    |
| SanDisk SD5SE2256G1002E 256GB                   | 1         | 1      | 2.5%    |
| Samsung Electronics HD161HJ 160GB               | 1         | 1      | 2.5%    |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB | 1         | 1      | 2.5%    |
| Hitachi HTS722020K9SA00 200GB                   | 1         | 1      | 2.5%    |
| Hitachi HTS541616J9SA00 160GB                   | 1         | 1      | 2.5%    |
| Hitachi HTS541080G9SA00 80GB                    | 1         | 1      | 2.5%    |
| HGST HTS541010A9E680 1TB                        | 1         | 1      | 2.5%    |
| Corsair Force GT 120GB                          | 1         | 1      | 2.5%    |
| China SH00M128GB                                | 1         | 1      | 2.5%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 13     | 31.58%  |
| WDC                 | 8         | 8      | 21.05%  |
| Toshiba             | 7         | 10     | 18.42%  |
| Hitachi             | 3         | 3      | 7.89%   |
| SanDisk             | 2         | 2      | 5.26%   |
| Samsung Electronics | 2         | 3      | 5.26%   |
| Micron Technology   | 1         | 1      | 2.63%   |
| HGST                | 1         | 1      | 2.63%   |
| Corsair             | 1         | 1      | 2.63%   |
| China               | 1         | 1      | 2.63%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 13     | 36.36%  |
| WDC                 | 8         | 8      | 24.24%  |
| Toshiba             | 7         | 10     | 21.21%  |
| Hitachi             | 3         | 3      | 9.09%   |
| Samsung Electronics | 2         | 3      | 6.06%   |
| HGST                | 1         | 1      | 3.03%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 32        | 38     | 86.49%  |
| SSD  | 5         | 5      | 13.51%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Hitachi HTS545025B9A300 250GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 114       | 180    | 74.03%  |
| Malfunc  | 37        | 43     | 24.03%  |
| Detected | 2         | 2      | 1.3%    |
| Failed   | 1         | 1      | 0.65%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 110       | 68.75%  |
| AMD                        | 28        | 17.5%   |
| Samsung Electronics        | 6         | 3.75%   |
| SanDisk                    | 3         | 1.88%   |
| Phison Electronics         | 3         | 1.88%   |
| ASMedia Technology         | 3         | 1.88%   |
| Silicon Motion             | 1         | 0.63%   |
| Realtek Semiconductor      | 1         | 0.63%   |
| Nvidia                     | 1         | 0.63%   |
| Lite-On IT Corp. / Plextor | 1         | 0.63%   |
| JMicron Technology         | 1         | 0.63%   |
| Hewlett-Packard            | 1         | 0.63%   |
| ADATA Technology           | 1         | 0.63%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 18        | 9.84%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 16        | 8.74%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 9         | 4.92%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 8         | 4.37%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 7         | 3.83%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 7         | 3.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 6         | 3.28%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 2.73%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5         | 2.73%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 5         | 2.73%   |
| AMD 400 Series Chipset SATA Controller                                         | 5         | 2.73%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 2.19%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 4         | 2.19%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 4         | 2.19%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3         | 1.64%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3         | 1.64%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 1.64%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 1.64%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 1.64%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 3         | 1.64%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 1.64%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3         | 1.64%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 1.64%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 3         | 1.64%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 3         | 1.64%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 2         | 1.09%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 2         | 1.09%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.09%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 2         | 1.09%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 2         | 1.09%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 2         | 1.09%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2         | 1.09%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 1         | 0.55%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 1         | 0.55%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.55%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 0.55%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                              | 1         | 0.55%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 1         | 0.55%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1         | 0.55%   |
| Phison E12 NVMe Controller                                                     | 1         | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 121       | 75.63%  |
| IDE  | 19        | 11.88%  |
| NVMe | 16        | 10%     |
| RAID | 4         | 2.5%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 112       | 79.43%  |
| AMD    | 29        | 20.57%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-3317U CPU @ 1.70GHz           | 3         | 2.13%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 3         | 2.13%   |
| Intel CPU Version                           | 2         | 1.42%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 2         | 1.42%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2         | 1.42%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 2         | 1.42%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 1.42%   |
| Intel Core i5-4570S CPU @ 2.90GHz           | 2         | 1.42%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 1.42%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 1.42%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 2         | 1.42%   |
| Intel Core i3-6100U CPU @ 2.30GHz           | 2         | 1.42%   |
| Intel Core i3-6100T CPU @ 3.20GHz           | 2         | 1.42%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 2         | 1.42%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 2         | 1.42%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 2         | 1.42%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 2         | 1.42%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz       | 2         | 1.42%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 2         | 1.42%   |
| AMD FX-8350 Eight-Core Processor            | 2         | 1.42%   |
| AMD E-450 APU with Radeon HD Graphics       | 2         | 1.42%   |
| Intel Xeon CPU W3680 @ 3.33GHz              | 1         | 0.71%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 1         | 0.71%   |
| Intel Xeon                                  | 1         | 0.71%   |
| Intel Processor 5Y70 CPU @ 1.10GHz          | 1         | 0.71%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1         | 0.71%   |
| Intel Pentium CPU N3530 @ 2.16GHz           | 1         | 0.71%   |
| Intel Pentium CPU B960 @ 2.20GHz            | 1         | 0.71%   |
| Intel Pentium CPU 5405U @ 2.30GHz           | 1         | 0.71%   |
| Intel Genuine CPU 2160 @ 1.80GHz            | 1         | 0.71%   |
| Intel Genuine CPU                           | 1         | 0.71%   |
| Intel Core m3-8100Y CPU @ 1.10GHz           | 1         | 0.71%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 1         | 0.71%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1         | 0.71%   |
| Intel Core i7-8559U CPU @ 2.70GHz           | 1         | 0.71%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.71%   |
| Intel Core i7-4712MQ CPU @ 2.30GHz          | 1         | 0.71%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 0.71%   |
| Intel Core i7-3632QM CPU @ 2.20GHz          | 1         | 0.71%   |
| Intel Core i7-3517U CPU @ 1.90GHz           | 1         | 0.71%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 37        | 26.24%  |
| Intel Core i3           | 23        | 16.31%  |
| Intel Core i7           | 18        | 12.77%  |
| Intel Core 2 Duo        | 9         | 6.38%   |
| Intel Celeron           | 6         | 4.26%   |
| Other                   | 5         | 3.55%   |
| AMD Ryzen 5             | 5         | 3.55%   |
| AMD FX                  | 5         | 3.55%   |
| AMD Ryzen 7             | 4         | 2.84%   |
| Intel Xeon              | 3         | 2.13%   |
| Intel Pentium           | 3         | 2.13%   |
| Intel Atom              | 3         | 2.13%   |
| AMD Ryzen 9             | 3         | 2.13%   |
| AMD E                   | 3         | 2.13%   |
| Intel Genuine           | 2         | 1.42%   |
| Intel Core 2 Quad       | 2         | 1.42%   |
| AMD Ryzen 3             | 2         | 1.42%   |
| Intel Pentium Dual-Core | 1         | 0.71%   |
| Intel Core m3           | 1         | 0.71%   |
| AMD Ryzen 5 PRO         | 1         | 0.71%   |
| AMD Phenom II X6        | 1         | 0.71%   |
| AMD Phenom II X4        | 1         | 0.71%   |
| AMD C-60                | 1         | 0.71%   |
| AMD A6                  | 1         | 0.71%   |
| AMD A4                  | 1         | 0.71%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 74        | 52.48%  |
| 4       | 33        | 23.4%   |
| Unknown | 7         | 4.96%   |
| 12      | 6         | 4.26%   |
| 8       | 6         | 4.26%   |
| 6       | 6         | 4.26%   |
| 16      | 4         | 2.84%   |
| 24      | 3         | 2.13%   |
| 1       | 2         | 1.42%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 136       | 96.45%  |
| 2      | 5         | 3.55%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 75        | 53.19%  |
| 1       | 59        | 41.84%  |
| Unknown | 7         | 4.96%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| IvyBridge   | 20        | 14.18%  |
| KabyLake    | 16        | 11.35%  |
| Haswell     | 16        | 11.35%  |
| SandyBridge | 14        | 9.93%   |
| Westmere    | 11        | 7.8%    |
| Penryn      | 11        | 7.8%    |
| Zen 2       | 6         | 4.26%   |
| Zen         | 5         | 3.55%   |
| Skylake     | 5         | 3.55%   |
| Piledriver  | 5         | 3.55%   |
| Broadwell   | 5         | 3.55%   |
| Core        | 4         | 2.84%   |
| Bobcat      | 4         | 2.84%   |
| Zen+        | 3         | 2.13%   |
| Silvermont  | 3         | 2.13%   |
| Nehalem     | 3         | 2.13%   |
| K10         | 2         | 1.42%   |
| Excavator   | 2         | 1.42%   |
| Bonnell     | 2         | 1.42%   |
| Zen 3       | 1         | 0.71%   |
| TigerLake   | 1         | 0.71%   |
| CometLake   | 1         | 0.71%   |
| Bulldozer   | 1         | 0.71%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 84        | 55.26%  |
| Nvidia | 40        | 26.32%  |
| AMD    | 28        | 18.42%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                            | 17        | 11.11%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 11        | 7.19%   |
| Intel Core Processor Integrated Graphics Controller                         | 6         | 3.92%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 5         | 3.27%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 5         | 3.27%   |
| Nvidia GK208B [GeForce GT 710]                                              | 4         | 2.61%   |
| Nvidia GF119 [GeForce GT 610]                                               | 4         | 2.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4         | 2.61%   |
| Intel HD Graphics 5500                                                      | 4         | 2.61%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 3         | 1.96%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 3         | 1.96%   |
| Intel HD Graphics 620                                                       | 3         | 1.96%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 3         | 1.96%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3         | 1.96%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 3         | 1.96%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2         | 1.31%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 2         | 1.31%   |
| Nvidia G84M [GeForce 8600M GT]                                              | 2         | 1.31%   |
| Intel UHD Graphics 620                                                      | 2         | 1.31%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 2         | 1.31%   |
| Intel HD Graphics 630                                                       | 2         | 1.31%   |
| Intel HD Graphics 530                                                       | 2         | 1.31%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller     | 2         | 1.31%   |
| AMD Wrestler [Radeon HD 6320]                                               | 2         | 1.31%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                    | 2         | 1.31%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 2         | 1.31%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 2         | 1.31%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1         | 0.65%   |
| Nvidia GT218M [GeForce 310M]                                                | 1         | 0.65%   |
| Nvidia GT218 [GeForce 210]                                                  | 1         | 0.65%   |
| Nvidia GT215 [GeForce GT 220]                                               | 1         | 0.65%   |
| Nvidia GT200 [GeForce GTX 260]                                              | 1         | 0.65%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1         | 0.65%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1         | 0.65%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1         | 0.65%   |
| Nvidia GP104 [GeForce GTX 1060 3GB]                                         | 1         | 0.65%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1         | 0.65%   |
| Nvidia GK208M [GeForce GT 740M]                                             | 1         | 0.65%   |
| Nvidia GK107M [GeForce GT 640M LE]                                          | 1         | 0.65%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1         | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 67        | 47.18%  |
| 1 x Nvidia     | 32        | 22.54%  |
| 1 x AMD        | 26        | 18.31%  |
| Intel + Nvidia | 8         | 5.63%   |
| 2 x Intel      | 7         | 4.93%   |
| Intel + AMD    | 2         | 1.41%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 118       | 83.69%  |
| Proprietary | 13        | 9.22%   |
| Unknown     | 10        | 7.09%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 108       | 76.06%  |
| 0.01-0.5   | 10        | 7.04%   |
| 1.01-2.0   | 8         | 5.63%   |
| 3.01-4.0   | 6         | 4.23%   |
| 0.51-1.0   | 4         | 2.82%   |
| 7.01-8.0   | 3         | 2.11%   |
| 5.01-6.0   | 3         | 2.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 15        | 14.02%  |
| Samsung Electronics     | 12        | 11.21%  |
| AU Optronics            | 11        | 10.28%  |
| Chimei Innolux          | 8         | 7.48%   |
| BOE                     | 7         | 6.54%   |
| Lenovo                  | 6         | 5.61%   |
| Hewlett-Packard         | 6         | 5.61%   |
| Dell                    | 5         | 4.67%   |
| Chi Mei Optoelectronics | 4         | 3.74%   |
| InfoVision              | 3         | 2.8%    |
| Iiyama                  | 3         | 2.8%    |
| Goldstar                | 3         | 2.8%    |
| BenQ                    | 3         | 2.8%    |
| Ancor Communications    | 3         | 2.8%    |
| Philips                 | 2         | 1.87%   |
| Apple                   | 2         | 1.87%   |
| Acer                    | 2         | 1.87%   |
| Vizio                   | 1         | 0.93%   |
| ViewSonic               | 1         | 0.93%   |
| SGT                     | 1         | 0.93%   |
| Medion                  | 1         | 0.93%   |
| KTC                     | 1         | 0.93%   |
| Hitachi                 | 1         | 0.93%   |
| Haier                   | 1         | 0.93%   |
| Fujitsu Siemens         | 1         | 0.93%   |
| Eizo                    | 1         | 0.93%   |
| ASUSTek Computer        | 1         | 0.93%   |
| AOC                     | 1         | 0.93%   |
| ALP                     | 1         | 0.93%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 3         | 2.78%   |
| LG Display LCD Monitor LGD0385 1366x768 310x170mm 13.9-inch              | 2         | 1.85%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 2         | 1.85%   |
| InfoVision LCD Monitor IVO03F4 1024x600 220x130mm 10.1-inch              | 2         | 1.85%   |
| Iiyama PLE2407HDS IVM560D 1920x1080 520x300mm 23.6-inch                  | 2         | 1.85%   |
| Vizio LCD Monitor VIZ0022 1920x540 480x270mm 21.7-inch                   | 1         | 0.93%   |
| ViewSonic VX2458-mhd VSC0437 1920x1080 520x290mm 23.4-inch               | 1         | 0.93%   |
| SGT YSD SGT1700 1280x1024 380x210mm 17.1-inch                            | 1         | 0.93%   |
| Samsung Electronics T22D390 SAM0B69 1920x1080 480x270mm 21.7-inch        | 1         | 0.93%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                         | 1         | 0.93%   |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                         | 1         | 0.93%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 520x320mm 24.0-inch      | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SEC5742 1366x768 310x170mm 13.9-inch     | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SEC414C 1366x768 310x170mm 13.9-inch     | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SEC3942 1366x768 310x170mm 13.9-inch     | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 340x190mm 15.3-inch     | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SEC3143 1366x768 310x180mm 14.1-inch     | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SDC4445 1366x768 340x190mm 15.3-inch     | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SDC434A 3200x1800 290x170mm 13.2-inch    | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SAM4A75 1024x768 300x230mm 14.9-inch     | 1         | 0.93%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                  | 1         | 0.93%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                   | 1         | 0.93%   |
| Medion MD21281 MED3947 1366x768 410x230mm 18.5-inch                      | 1         | 0.93%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 340x190mm 15.3-inch            | 1         | 0.93%   |
| LG Display LCD Monitor LGD11F9 1280x800 290x180mm 13.4-inch              | 1         | 0.93%   |
| LG Display LCD Monitor LGD048C 1920x1080 290x170mm 13.2-inch             | 1         | 0.93%   |
| LG Display LCD Monitor LGD0470 1920x1080 350x190mm 15.7-inch             | 1         | 0.93%   |
| LG Display LCD Monitor LGD045C 1366x768 340x190mm 15.3-inch              | 1         | 0.93%   |
| LG Display LCD Monitor LGD0419 2560x1440 310x170mm 13.9-inch             | 1         | 0.93%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch              | 1         | 0.93%   |
| LG Display LCD Monitor LGD03AB 1366x768 340x190mm 15.3-inch              | 1         | 0.93%   |
| LG Display LCD Monitor LGD0323 1920x1080 350x190mm 15.7-inch             | 1         | 0.93%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 1         | 0.93%   |
| LG Display LCD Monitor LGD021D 1600x900 380x210mm 17.1-inch              | 1         | 0.93%   |
| Lenovo LEN-M73Z-D LEN00A0 1600x900 440x240mm 19.7-inch                   | 1         | 0.93%   |
| Lenovo LEN-E73Z-D LEN00A1 1600x900 440x240mm 19.7-inch                   | 1         | 0.93%   |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                    | 1         | 0.93%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch                 | 1         | 0.93%   |
| Lenovo LCD Monitor LEN4050 1280x800 330x210mm 15.4-inch                  | 1         | 0.93%   |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch                  | 1         | 0.93%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 42        | 39.25%  |
| 1920x1080 (FHD)    | 33        | 30.84%  |
| 1600x900 (HD+)     | 7         | 6.54%   |
| 1280x1024 (SXGA)   | 4         | 3.74%   |
| 1920x1200 (WUXGA)  | 3         | 2.8%    |
| 1680x1050 (WSXGA+) | 3         | 2.8%    |
| 1280x800 (WXGA)    | 3         | 2.8%    |
| 3840x2160 (4K)     | 2         | 1.87%   |
| 2560x1440 (QHD)    | 2         | 1.87%   |
| 1024x768 (XGA)     | 2         | 1.87%   |
| 1024x600           | 2         | 1.87%   |
| 3440x1440          | 1         | 0.93%   |
| 3200x1800 (QHD+)   | 1         | 0.93%   |
| 1920x540           | 1         | 0.93%   |
| 1360x768           | 1         | 0.93%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 24        | 22.43%  |
| 13      | 18        | 16.82%  |
| 23      | 10        | 9.35%   |
| 24      | 9         | 8.41%   |
| 18      | 6         | 5.61%   |
| 12      | 6         | 5.61%   |
| 21      | 5         | 4.67%   |
| 17      | 5         | 4.67%   |
| 11      | 5         | 4.67%   |
| 19      | 4         | 3.74%   |
| 22      | 3         | 2.8%    |
| 14      | 3         | 2.8%    |
| 10      | 3         | 2.8%    |
| Unknown | 2         | 1.87%   |
| 52      | 1         | 0.93%   |
| 42      | 1         | 0.93%   |
| 34      | 1         | 0.93%   |
| 27      | 1         | 0.93%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 40        | 37.74%  |
| 501-600     | 20        | 18.87%  |
| 201-300     | 20        | 18.87%  |
| 401-500     | 17        | 16.04%  |
| 351-400     | 4         | 3.77%   |
| Unknown     | 2         | 1.89%   |
| 701-800     | 1         | 0.94%   |
| 1001-1500   | 1         | 0.94%   |
| 901-1000    | 1         | 0.94%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 90        | 85.71%  |
| 16/10 | 9         | 8.57%   |
| 5/4   | 3         | 2.86%   |
| 4/3   | 2         | 1.9%    |
| 21/9  | 1         | 0.95%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 25        | 23.36%  |
| 81-90          | 17        | 15.89%  |
| 91-100         | 15        | 14.02%  |
| 101-110        | 11        | 10.28%  |
| 141-150        | 8         | 7.48%   |
| 61-70          | 6         | 5.61%   |
| 51-60          | 5         | 4.67%   |
| 151-200        | 4         | 3.74%   |
| 41-50          | 3         | 2.8%    |
| 121-130        | 3         | 2.8%    |
| 71-80          | 2         | 1.87%   |
| 251-300        | 2         | 1.87%   |
| Unknown        | 2         | 1.87%   |
| More than 1000 | 1         | 0.93%   |
| 351-500        | 1         | 0.93%   |
| 301-350        | 1         | 0.93%   |
| 501-1000       | 1         | 0.93%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 45        | 42.45%  |
| 101-120       | 35        | 33.02%  |
| 121-160       | 18        | 16.98%  |
| 161-240       | 5         | 4.72%   |
| Unknown       | 2         | 1.89%   |
| More than 240 | 1         | 0.94%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 99        | 69.72%  |
| 0     | 37        | 26.06%  |
| 2     | 6         | 4.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 68        | 33.01%  |
| Intel                             | 62        | 30.1%   |
| Qualcomm Atheros                  | 27        | 13.11%  |
| Broadcom                          | 22        | 10.68%  |
| Marvell Technology Group          | 4         | 1.94%   |
| Ralink Technology                 | 3         | 1.46%   |
| Ralink                            | 3         | 1.46%   |
| JMicron Technology                | 3         | 1.46%   |
| Ericsson Business Mobile Networks | 3         | 1.46%   |
| Huawei Technologies               | 2         | 0.97%   |
| Xiaomi                            | 1         | 0.49%   |
| TP-Link                           | 1         | 0.49%   |
| Sierra Wireless                   | 1         | 0.49%   |
| Nvidia                            | 1         | 0.49%   |
| IMC Networks                      | 1         | 0.49%   |
| Google                            | 1         | 0.49%   |
| Belkin Components                 | 1         | 0.49%   |
| ASUSTek Computer                  | 1         | 0.49%   |
| Aquantia                          | 1         | 0.49%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 47        | 18.95%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 10        | 4.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 9         | 3.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 7         | 2.82%   |
| Intel Wireless 7265                                                            | 7         | 2.82%   |
| Intel I211 Gigabit Network Connection                                          | 6         | 2.42%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 5         | 2.02%   |
| Intel Ethernet Connection I217-LM                                              | 5         | 2.02%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 4         | 1.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 4         | 1.61%   |
| Intel Wireless 8265 / 8275                                                     | 4         | 1.61%   |
| Intel Wireless 7260                                                            | 4         | 1.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 3         | 1.21%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 3         | 1.21%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 3         | 1.21%   |
| Intel Ethernet Connection (7) I219-V                                           | 3         | 1.21%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 3         | 1.21%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                   | 3         | 1.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 0.81%   |
| Ralink MT7601U Wireless Adapter                                                | 2         | 0.81%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 0.81%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 2         | 0.81%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 0.81%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 0.81%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 2         | 0.81%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.81%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 2         | 0.81%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 2         | 0.81%   |
| Intel Ethernet Connection I217-V                                               | 2         | 0.81%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 0.81%   |
| Intel Ethernet Connection (3) I218-V                                           | 2         | 0.81%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 2         | 0.81%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                   | 2         | 0.81%   |
| Intel Centrino Ultimate-N 6300                                                 | 2         | 0.81%   |
| Intel Centrino Advanced-N 6235                                                 | 2         | 0.81%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 2         | 0.81%   |
| Intel 82577LC Gigabit Network Connection                                       | 2         | 0.81%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III    | 2         | 0.81%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 2         | 0.81%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                         | 2         | 0.81%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 39        | 37.5%   |
| Qualcomm Atheros      | 20        | 19.23%  |
| Realtek Semiconductor | 18        | 17.31%  |
| Broadcom              | 16        | 15.38%  |
| Ralink Technology     | 3         | 2.88%   |
| Ralink                | 3         | 2.88%   |
| TP-Link               | 1         | 0.96%   |
| Sierra Wireless       | 1         | 0.96%   |
| IMC Networks          | 1         | 0.96%   |
| Belkin Components     | 1         | 0.96%   |
| ASUSTek Computer      | 1         | 0.96%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 6.48%   |
| Intel Wireless 7265                                                     | 7         | 6.48%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 5         | 4.63%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 3.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 3.7%    |
| Intel Wireless 8265 / 8275                                              | 4         | 3.7%    |
| Intel Wireless 7260                                                     | 4         | 3.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 2.78%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 2.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 2.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 2.78%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter            | 3         | 2.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.85%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 1.85%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 1.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 1.85%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 1.85%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 1.85%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 1.85%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.85%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 2         | 1.85%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 2         | 1.85%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 1.85%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 1.85%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 1         | 0.93%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 0.93%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.93%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.93%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 0.93%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                   | 1         | 0.93%   |
| Ralink RT3072 Wireless Adapter                                          | 1         | 0.93%   |
| Ralink RT3592 Wireless 802.11abgn 2T/2R PCIe                            | 1         | 0.93%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.93%   |
| Ralink RT2561/RT61 rev B 802.11g                                        | 1         | 0.93%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.93%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 1         | 0.93%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.93%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.93%   |
| Intel Wireless 8260                                                     | 1         | 0.93%   |
| Intel Wireless 3160                                                     | 1         | 0.93%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 58        | 42.65%  |
| Intel                    | 44        | 32.35%  |
| Qualcomm Atheros         | 14        | 10.29%  |
| Broadcom                 | 8         | 5.88%   |
| Marvell Technology Group | 4         | 2.94%   |
| JMicron Technology       | 3         | 2.21%   |
| Xiaomi                   | 1         | 0.74%   |
| Nvidia                   | 1         | 0.74%   |
| Huawei Technologies      | 1         | 0.74%   |
| Google                   | 1         | 0.74%   |
| Aquantia                 | 1         | 0.74%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 47        | 34.56%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 10        | 7.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 9         | 6.62%   |
| Intel I211 Gigabit Network Connection                                          | 6         | 4.41%   |
| Intel Ethernet Connection I217-LM                                              | 5         | 3.68%   |
| Intel Ethernet Connection (7) I219-V                                           | 3         | 2.21%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 1.47%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 1.47%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 1.47%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 2         | 1.47%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 1.47%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 2         | 1.47%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 2         | 1.47%   |
| Intel Ethernet Connection I217-V                                               | 2         | 1.47%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 1.47%   |
| Intel Ethernet Connection (3) I218-V                                           | 2         | 1.47%   |
| Intel 82577LC Gigabit Network Connection                                       | 2         | 1.47%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 2         | 1.47%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.74%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.74%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.74%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.74%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.74%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 1         | 0.74%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.74%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1         | 0.74%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.74%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                            | 1         | 0.74%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.74%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.74%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.74%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.74%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 0.74%   |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 0.74%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 0.74%   |
| Intel Ethernet Connection (11) I219-V                                          | 1         | 0.74%   |
| Intel 82583V Gigabit Network Connection                                        | 1         | 0.74%   |
| Intel 82574L Gigabit Network Connection                                        | 1         | 0.74%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 1         | 0.74%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 0.74%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 132       | 56.41%  |
| WiFi     | 98        | 41.88%  |
| Modem    | 2         | 0.85%   |
| Unknown  | 2         | 0.85%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 126       | 61.17%  |
| WiFi     | 77        | 37.38%  |
| Unknown  | 2         | 0.97%   |
| Modem    | 1         | 0.49%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 82        | 58.16%  |
| 1     | 57        | 40.43%  |
| 3     | 2         | 1.42%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 138       | 97.18%  |
| Yes  | 4         | 2.82%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 23        | 39.66%  |
| Broadcom                        | 8         | 13.79%  |
| Apple                           | 8         | 13.79%  |
| Realtek Semiconductor           | 6         | 10.34%  |
| Cambridge Silicon Radio         | 4         | 6.9%    |
| Qualcomm Atheros Communications | 3         | 5.17%   |
| Foxconn / Hon Hai               | 3         | 5.17%   |
| Ralink                          | 1         | 1.72%   |
| Hewlett-Packard                 | 1         | 1.72%   |
| ASUSTek Computer                | 1         | 1.72%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 14        | 24.14%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 4         | 6.9%    |
| Apple Bluetooth Host Controller                             | 4         | 6.9%    |
| Realtek Bluetooth Adapter                                   | 2         | 3.45%   |
| Realtek Bluetooth 4.0 Adapter                               | 2         | 3.45%   |
| Intel Wireless-AC 3168 Bluetooth                            | 2         | 3.45%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 3.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 2         | 3.45%   |
| Broadcom BCM43142 Bluetooth 4.0                             | 2         | 3.45%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 3.45%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 2         | 3.45%   |
| Realtek Wireless Bluetooth Adapter                          | 1         | 1.72%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 1.72%   |
| Ralink RT3290 Bluetooth                                     | 1         | 1.72%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 1.72%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 1.72%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 1.72%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 1         | 1.72%   |
| Intel AX201 Bluetooth                                       | 1         | 1.72%   |
| Intel AX200 Bluetooth                                       | 1         | 1.72%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 1.72%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth             | 1         | 1.72%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth               | 1         | 1.72%   |
| Foxconn / Hon Hai Atheros AR3012 Bluetooth                  | 1         | 1.72%   |
| Broadcom Bluetooth 4.0                                      | 1         | 1.72%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter            | 1         | 1.72%   |
| Broadcom BCM2046 Bluetooth Device                           | 1         | 1.72%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 1         | 1.72%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 1         | 1.72%   |
| Apple Broadcom Built-in Bluetooth                           | 1         | 1.72%   |
| Apple Bluetooth HCI                                         | 1         | 1.72%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 108       | 57.45%  |
| AMD                     | 36        | 19.15%  |
| Nvidia                  | 28        | 14.89%  |
| C-Media Electronics     | 5         | 2.66%   |
| Texas Instruments       | 3         | 1.6%    |
| Logitech                | 2         | 1.06%   |
| Creative Labs           | 2         | 1.06%   |
| XMOS                    | 1         | 0.53%   |
| Plantronics             | 1         | 0.53%   |
| Hewlett-Packard         | 1         | 0.53%   |
| BEHRINGER International | 1         | 0.53%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 23        | 10.27%  |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 12        | 5.36%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 11        | 4.91%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11        | 4.91%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 10        | 4.46%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8         | 3.57%   |
| Intel Sunrise Point-LP HD Audio                                            | 8         | 3.57%   |
| AMD Starship/Matisse HD Audio Controller                                   | 6         | 2.68%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 6         | 2.68%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 2.23%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 2.23%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 2.23%   |
| Intel 8 Series HD Audio Controller                                         | 5         | 2.23%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 2.23%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5         | 2.23%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4         | 1.79%   |
| Nvidia GF119 HDMI Audio Controller                                         | 4         | 1.79%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 1.79%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 1.79%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 4         | 1.79%   |
| AMD Wrestler HDMI Audio                                                    | 4         | 1.79%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4         | 1.79%   |
| Texas Instruments PCM2902 Audio Codec                                      | 3         | 1.34%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 1.34%   |
| Nvidia High Definition Audio Controller                                    | 3         | 1.34%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 1.34%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 1.34%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 1.34%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3         | 1.34%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 3         | 1.34%   |
| Nvidia GM206 High Definition Audio Controller                              | 2         | 0.89%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2         | 0.89%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 0.89%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2         | 0.89%   |
| Intel 200 Series PCH HD Audio                                              | 2         | 0.89%   |
| C-Media Electronics CM108 Audio Controller                                 | 2         | 0.89%   |
| AMD High Definition Audio Controller                                       | 2         | 0.89%   |
| AMD FCH Azalia Controller                                                  | 2         | 0.89%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 0.89%   |
| XMOS USB Audio                                                             | 1         | 0.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 30        | 17.34%  |
| SK hynix                     | 27        | 15.61%  |
| Kingston                     | 21        | 12.14%  |
| Unknown                      | 18        | 10.4%   |
| Micron Technology            | 13        | 7.51%   |
| Crucial                      | 11        | 6.36%   |
| Nanya Technology             | 6         | 3.47%   |
| Team                         | 5         | 2.89%   |
| Unknown                      | 5         | 2.89%   |
| Ramaxel Technology           | 4         | 2.31%   |
| G.Skill                      | 4         | 2.31%   |
| Corsair                      | 4         | 2.31%   |
| Teikon                       | 3         | 1.73%   |
| Smart                        | 3         | 1.73%   |
| Elpida                       | 3         | 1.73%   |
| A-DATA Technology            | 3         | 1.73%   |
| Transcend                    | 2         | 1.16%   |
| Patriot                      | 2         | 1.16%   |
| Apacer                       | 2         | 1.16%   |
| Unknown (0x7F7F7F94FFFFFFFF) | 1         | 0.58%   |
| Smart Brazil                 | 1         | 0.58%   |
| SHARETRONIC                  | 1         | 0.58%   |
| RZX                          | 1         | 0.58%   |
| PKI/Kingston                 | 1         | 0.58%   |
| Hikvision                    | 1         | 0.58%   |
| ASint Technology             | 1         | 0.58%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Unknown                                                         | 5         | 2.81%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                      | 3         | 1.69%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3200MT/s              | 2         | 1.12%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 2         | 1.12%   |
| SK hynix RAM HMT451S6BCFR8A-PB 4GB DIMM DDR3 1600MT/s           | 2         | 1.12%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 2         | 1.12%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s          | 2         | 1.12%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s          | 2         | 1.12%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s           | 2         | 1.12%   |
| Samsung RAM M471B5273DH0-CK0 8GB SODIMM DDR3 1600MT/s           | 2         | 1.12%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s           | 2         | 1.12%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s           | 2         | 1.12%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s           | 2         | 1.12%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s           | 2         | 1.12%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1333MT/s             | 2         | 1.12%   |
| Ramaxel RAM RMR5030MN68F9F1600 4GB DIMM DDR3 1600MT/s           | 2         | 1.12%   |
| Nanya RAM NT2GC64B8HA1NS-BE 2GB SODIMM DDR3 1067MT/s            | 2         | 1.12%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s           | 2         | 1.12%   |
| Micron RAM 8ATF1G64HZ-2G3H1 8GB SODIMM DDR4 2400MT/s            | 2         | 1.12%   |
| Crucial RAM Module 8GB SODIMM DDR3 1600MT/s                     | 2         | 1.12%   |
| Crucial RAM CT8G4DFS8266.M8FD 8GB DIMM DDR4 2667MT/s            | 2         | 1.12%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.56%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                            | 1         | 0.56%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.56%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                     | 1         | 0.56%   |
| Unknown RAM Module 4GB SODIMM DDR3                              | 1         | 0.56%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                      | 1         | 0.56%   |
| Unknown RAM Module 4GB FB-DIMM DDR2 667MT/s                     | 1         | 0.56%   |
| Unknown RAM Module 4GB DIMM DDR3 800MT/s                        | 1         | 0.56%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                       | 1         | 0.56%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                        | 1         | 0.56%   |
| Unknown RAM Module 4GB DIMM 400MT/s                             | 1         | 0.56%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                            | 1         | 0.56%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                            | 1         | 0.56%   |
| Unknown RAM Module 2GB SODIMM DDR3                              | 1         | 0.56%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                            | 1         | 0.56%   |
| Unknown (0x7F7F7F94FFFFFFFF) RAM Module 2GB SODIMM DDR2 667MT/s | 1         | 0.56%   |
| Transcend RAM Module 2GB DIMM DDR3 1333MT/s                     | 1         | 0.56%   |
| Transcend RAM JM1333KSN-4G 4GB DIMM DDR3 1333MT/s               | 1         | 0.56%   |
| Teikon RAM TMT451S6BFR8A-PBHC 4GB SODIMM DDR3 1333MT/s          | 1         | 0.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 84        | 60.43%  |
| DDR4    | 37        | 26.62%  |
| DDR2    | 8         | 5.76%   |
| Unknown | 5         | 3.6%    |
| LPDDR3  | 2         | 1.44%   |
| SDRAM   | 1         | 0.72%   |
| LPDDR4  | 1         | 0.72%   |
| DDR     | 1         | 0.72%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 78        | 56.12%  |
| DIMM         | 57        | 41.01%  |
| Row Of Chips | 2         | 1.44%   |
| FB-DIMM      | 1         | 0.72%   |
| Chip         | 1         | 0.72%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 66        | 41.25%  |
| 8192  | 43        | 26.88%  |
| 2048  | 37        | 23.13%  |
| 16384 | 10        | 6.25%   |
| 32768 | 3         | 1.88%   |
| 1024  | 1         | 0.63%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 50        | 32.68%  |
| 1333    | 29        | 18.95%  |
| 2400    | 11        | 7.19%   |
| 1067    | 11        | 7.19%   |
| 2667    | 9         | 5.88%   |
| 2133    | 7         | 4.58%   |
| 1334    | 7         | 4.58%   |
| 667     | 6         | 3.92%   |
| 3200    | 5         | 3.27%   |
| 2666    | 3         | 1.96%   |
| 1066    | 2         | 1.31%   |
| 800     | 2         | 1.31%   |
| 400     | 2         | 1.31%   |
| Unknown | 2         | 1.31%   |
| 4267    | 1         | 0.65%   |
| 3000    | 1         | 0.65%   |
| 2933    | 1         | 0.65%   |
| 1867    | 1         | 0.65%   |
| 1866    | 1         | 0.65%   |
| 1200    | 1         | 0.65%   |
| 533     | 1         | 0.65%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Brother Industries | 2         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| Brother HL-L2310D series | 1         | 50%     |
| Brother DCP-J100         | 1         | 50%     |

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
| Chicony Electronics                    | 17        | 26.56%  |
| Bison Electronics                      | 9         | 14.06%  |
| Realtek Semiconductor                  | 5         | 7.81%   |
| IMC Networks                           | 5         | 7.81%   |
| Sunplus Innovation Technology          | 4         | 6.25%   |
| Microdia                               | 4         | 6.25%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 6.25%   |
| Z-Star Microelectronics                | 2         | 3.13%   |
| Suyin                                  | 2         | 3.13%   |
| Importek                               | 2         | 3.13%   |
| Apple                                  | 2         | 3.13%   |
| Tripath Technology                     | 1         | 1.56%   |
| Syntek                                 | 1         | 1.56%   |
| Logitech                               | 1         | 1.56%   |
| Lite-On Technology                     | 1         | 1.56%   |
| Lenovo                                 | 1         | 1.56%   |
| Hewlett-Packard                        | 1         | 1.56%   |
| Foxconn / Hon Hai                      | 1         | 1.56%   |
| ALi                                    | 1         | 1.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 8         | 12.5%   |
| Bison Integrated Camera                                     | 4         | 6.25%   |
| Bison Lenovo EasyCamera                                     | 3         | 4.69%   |
| Realtek USB 2.0 PC Camera                                   | 2         | 3.13%   |
| IMC Networks XHC Camera                                     | 2         | 3.13%   |
| Z-Star Integrated Camera                                    | 1         | 1.56%   |
| Z-Star A4 TECH USB2.0 PC Camera J                           | 1         | 1.56%   |
| Tripath 2M Front Camera                                     | 1         | 1.56%   |
| Syntek EasyCamera                                           | 1         | 1.56%   |
| Suyin Integrated_Webcam_HD                                  | 1         | 1.56%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 1.56%   |
| Sunplus Lenovo EasyCamera                                   | 1         | 1.56%   |
| Sunplus Laptop_Integrated_Webcam_FHD                        | 1         | 1.56%   |
| Sunplus Integrated Camera                                   | 1         | 1.56%   |
| Sunplus HP Universal Camera                                 | 1         | 1.56%   |
| Realtek USB Camera                                          | 1         | 1.56%   |
| Realtek Integrated_Webcam_HD                                | 1         | 1.56%   |
| Realtek Dell EasyCamera                                     | 1         | 1.56%   |
| Microdia Webcam                                             | 1         | 1.56%   |
| Microdia Laptop_Integrated_Webcam_2M                        | 1         | 1.56%   |
| Microdia Integrated Webcam HD                               | 1         | 1.56%   |
| Microdia Dell Laptop Integrated Webcam HD                   | 1         | 1.56%   |
| Logitech Webcam C270                                        | 1         | 1.56%   |
| Lite-On Integrated Camera                                   | 1         | 1.56%   |
| Lenovo Integrated Webcam                                    | 1         | 1.56%   |
| Importek TOSHIBA HD Web Camera                              | 1         | 1.56%   |
| Importek HP Webcam                                          | 1         | 1.56%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 1         | 1.56%   |
| IMC Networks USB 2.0 UVC HD Webcam                          | 1         | 1.56%   |
| IMC Networks 2M Integrated Webcam                           | 1         | 1.56%   |
| HP Premium Starter Webcam                                   | 1         | 1.56%   |
| Foxconn / Hon Hai USB2.0 Camera                             | 1         | 1.56%   |
| Chicony WebCam                                              | 1         | 1.56%   |
| Chicony USB2.0 HD UVC WebCam                                | 1         | 1.56%   |
| Chicony USB Video Device                                    | 1         | 1.56%   |
| Chicony Sony Visual Communication Camera                    | 1         | 1.56%   |
| Chicony Lenovo Integrated Camera (0.3MP)                    | 1         | 1.56%   |
| Chicony Lenovo EasyCamera                                   | 1         | 1.56%   |
| Chicony HP Display Camera                                   | 1         | 1.56%   |
| Chicony Asus 720p CMOS webcam                               | 1         | 1.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 7         | 46.67%  |
| Upek                  | 3         | 20%     |
| AuthenTec             | 3         | 20%     |
| STMicroelectronics    | 1         | 6.67%   |
| Elan Microelectronics | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 26.67%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 20%     |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 6.67%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 6.67%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 6.67%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 6.67%   |
| Elan Fingerprint Sensor                                                    | 1         | 6.67%   |
| AuthenTec AES2810                                                          | 1         | 6.67%   |
| AuthenTec AES1660                                                          | 1         | 6.67%   |
| AuthenTec AES1600                                                          | 1         | 6.67%   |

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
| 1     | 51        | 36.17%  |
| 0     | 36        | 25.53%  |
| 2     | 35        | 24.82%  |
| 3     | 14        | 9.93%   |
| 4     | 5         | 3.55%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 86        | 48.59%  |
| Card reader              | 26        | 14.69%  |
| Net/wireless             | 23        | 12.99%  |
| Fingerprint reader       | 15        | 8.47%   |
| Firewire controller      | 10        | 5.65%   |
| Bluetooth                | 8         | 4.52%   |
| Sound                    | 3         | 1.69%   |
| Storage                  | 2         | 1.13%   |
| Network                  | 2         | 1.13%   |
| Net/ethernet             | 2         | 1.13%   |

