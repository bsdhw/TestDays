helloSystem 0.6.0 - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for helloSystem 0.6.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/helloSystem_0.6.0/Desktop/README.md) and [notebooks](/Dist/helloSystem_0.6.0/Notebook/README.md).

Full-feature report is available here: https://bsd-hardware.info/?view=trends

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
| HP            | EliteBook 2560p             | Notebook    | [41c04c8449](https://bsd-hardware.info/?probe=41c04c8449) | Nov 26, 2021 |
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
| Dell          | Studio 1747                 | Notebook    | [ed704cde92](https://bsd-hardware.info/?probe=ed704cde92) | Oct 20, 2021 |
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
| eMachines     | eM350                       | Notebook    | [c268dd82de](https://bsd-hardware.info/?probe=c268dd82de) | Jul 04, 2021 |
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
| amd64 | 124       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 123       | 98.4%   |
| XFCE         | 1         | 0.8%    |
| GNOME        | 1         | 0.8%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 124       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| SLiM | 124       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 121       | 97.58%  |
| ru_RU   | 1         | 0.81%   |
| de_DE   | 1         | 0.81%   |
| Unknown | 1         | 0.81%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 104       | 83.2%   |
| BIOS | 21        | 16.8%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 124       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 124       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 24        | 19.35%  |
| ASUSTek Computer    | 20        | 16.13%  |
| Hewlett-Packard     | 15        | 12.1%   |
| Dell                | 12        | 9.68%   |
| ASRock              | 8         | 6.45%   |
| Gigabyte Technology | 6         | 4.84%   |
| MSI                 | 5         | 4.03%   |
| Acer                | 5         | 4.03%   |
| Intel               | 4         | 3.23%   |
| Apple               | 4         | 3.23%   |
| Toshiba             | 3         | 2.42%   |
| Itautec             | 2         | 1.61%   |
| T-bao               | 1         | 0.81%   |
| Sony                | 1         | 0.81%   |
| Shuttle             | 1         | 0.81%   |
| Semp Toshiba        | 1         | 0.81%   |
| Sapphire            | 1         | 0.81%   |
| Positivo            | 1         | 0.81%   |
| Philco              | 1         | 0.81%   |
| PCPartner           | 1         | 0.81%   |
| Medion              | 1         | 0.81%   |
| Kraftway            | 1         | 0.81%   |
| Gateway             | 1         | 0.81%   |
| Fujitsu             | 1         | 0.81%   |
| eMachines           | 1         | 0.81%   |
| Chuwi               | 1         | 0.81%   |
| Acidanthera         | 1         | 0.81%   |
| Unknown             | 1         | 0.81%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 2         | 1.61%   |
| Toshiba Satellite S55t-B                   | 1         | 0.81%   |
| Toshiba PORTEGE M780                       | 1         | 0.81%   |
| Toshiba dynabook RX3 SM240E/3HD            | 1         | 0.81%   |
| T-bao MINI PC                              | 1         | 0.81%   |
| Sony SVS1511AJB                            | 1         | 0.81%   |
| Shuttle SH61R                              | 1         | 0.81%   |
| Semp Toshiba STI NA 1401                   | 1         | 0.81%   |
| Sapphire EDGE-FT1M1 E450 1AOVU044          | 1         | 0.81%   |
| Positivo C14CR01                           | 1         | 0.81%   |
| Philco 10B                                 | 1         | 0.81%   |
| PCPartner DREAMSYS                         | 1         | 0.81%   |
| MSI MS-7C91                                | 1         | 0.81%   |
| MSI MS-7B93                                | 1         | 0.81%   |
| MSI MS-7A40                                | 1         | 0.81%   |
| MSI MS-7592                                | 1         | 0.81%   |
| MSI MS-16F1                                | 1         | 0.81%   |
| Medion H61H2-LM3                           | 1         | 0.81%   |
| Lenovo Yoga 3 Pro-1370 80HE                | 1         | 0.81%   |
| Lenovo ThinkPad Yoga 11e 20DAS0AE00        | 1         | 0.81%   |
| Lenovo ThinkPad X250 20CLS2A11K            | 1         | 0.81%   |
| Lenovo ThinkPad X230 2325IG2               | 1         | 0.81%   |
| Lenovo ThinkPad X230 23062S2               | 1         | 0.81%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWA003CD | 1         | 0.81%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A70066UK   | 1         | 0.81%   |
| Lenovo ThinkPad W520 4276CTO               | 1         | 0.81%   |
| Lenovo ThinkPad T450s 20BX001PUS           | 1         | 0.81%   |
| Lenovo ThinkPad T440p 20AW007QMS           | 1         | 0.81%   |
| Lenovo ThinkPad T430u 3352AA5              | 1         | 0.81%   |
| Lenovo ThinkPad T420 4180EE8               | 1         | 0.81%   |
| Lenovo ThinkPad SL 2746M3C                 | 1         | 0.81%   |
| Lenovo ThinkPad R500 2718W92               | 1         | 0.81%   |
| Lenovo ThinkPad L440 20ASS0FP00            | 1         | 0.81%   |
| Lenovo ThinkPad 13 20GJCTO1WW              | 1         | 0.81%   |
| Lenovo ThinkCentre M83 10AHS35Q00          | 1         | 0.81%   |
| Lenovo ThinkCentre E73z 10BD004RRU         | 1         | 0.81%   |
| Lenovo S20-30 Touch 20434                  | 1         | 0.81%   |
| Lenovo IdeaPad Z360                        | 1         | 0.81%   |
| Lenovo IdeaPad S145-15IWL 81MV             | 1         | 0.81%   |
| Lenovo G500s 20245                         | 1         | 0.81%   |
| Lenovo G500 20236                          | 1         | 0.81%   |
| Lenovo B590 62743PG                        | 1         | 0.81%   |
| Kraftway KW10T                             | 1         | 0.81%   |
| Itautec Infoway w7530                      | 1         | 0.81%   |
| Itautec Infoway ST-4344                    | 1         | 0.81%   |
| Intel NUC8i7BEH                            | 1         | 0.81%   |
| Intel NUC5i3RYH                            | 1         | 0.81%   |
| Intel H81                                  | 1         | 0.81%   |
| Intel H61                                  | 1         | 0.81%   |
| HP [AH877AV] _ Currency Bulk P             | 1         | 0.81%   |
| HP ProLiant ML350 G5                       | 1         | 0.81%   |
| HP Presario CQ43                           | 1         | 0.81%   |
| HP Pavilion dm4                            | 1         | 0.81%   |
| HP Laptop 15-db0xxx                        | 1         | 0.81%   |
| HP EliteDesk 800 G2 SFF                    | 1         | 0.81%   |
| HP EliteBook 840 G5                        | 1         | 0.81%   |
| HP EliteBook 2560p                         | 1         | 0.81%   |
| HP Compaq Elite 8300 USDT                  | 1         | 0.81%   |
| HP Compaq Elite 8300 SFF                   | 1         | 0.81%   |
| HP 260-p026                                | 1         | 0.81%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 15        | 12.1%   |
| Dell Inspiron       | 4         | 3.23%   |
| Acer Aspire         | 4         | 3.23%   |
| Dell OptiPlex       | 3         | 2.42%   |
| Dell Latitude       | 3         | 2.42%   |
| ASUS TUF            | 3         | 2.42%   |
| Lenovo ThinkCentre  | 2         | 1.61%   |
| Lenovo IdeaPad      | 2         | 1.61%   |
| Itautec Infoway     | 2         | 1.61%   |
| HP EliteBook        | 2         | 1.61%   |
| HP Compaq           | 2         | 1.61%   |
| Unknown             | 2         | 1.61%   |
| Toshiba Satellite   | 1         | 0.81%   |
| Toshiba PORTEGE     | 1         | 0.81%   |
| Toshiba dynabook    | 1         | 0.81%   |
| T-bao MINI          | 1         | 0.81%   |
| Sony SVS1511AJB     | 1         | 0.81%   |
| Shuttle SH61R       | 1         | 0.81%   |
| Semp Toshiba STI    | 1         | 0.81%   |
| Sapphire EDGE-FT1M1 | 1         | 0.81%   |
| Positivo C14CR01    | 1         | 0.81%   |
| Philco 10B          | 1         | 0.81%   |
| PCPartner DREAMSYS  | 1         | 0.81%   |
| MSI MS-7C91         | 1         | 0.81%   |
| MSI MS-7B93         | 1         | 0.81%   |
| MSI MS-7A40         | 1         | 0.81%   |
| MSI MS-7592         | 1         | 0.81%   |
| MSI MS-16F1         | 1         | 0.81%   |
| Medion H61H2-LM3    | 1         | 0.81%   |
| Lenovo Yoga         | 1         | 0.81%   |
| Lenovo S20-30       | 1         | 0.81%   |
| Lenovo G500s        | 1         | 0.81%   |
| Lenovo G500         | 1         | 0.81%   |
| Lenovo B590         | 1         | 0.81%   |
| Kraftway KW10T      | 1         | 0.81%   |
| Intel NUC8i7BEH     | 1         | 0.81%   |
| Intel NUC5i3RYH     | 1         | 0.81%   |
| Intel H81           | 1         | 0.81%   |
| Intel H61           | 1         | 0.81%   |
| HP [AH877AV]        | 1         | 0.81%   |
| HP ProLiant         | 1         | 0.81%   |
| HP Presario         | 1         | 0.81%   |
| HP Pavilion         | 1         | 0.81%   |
| HP Laptop           | 1         | 0.81%   |
| HP EliteDesk        | 1         | 0.81%   |
| HP 260-p026         | 1         | 0.81%   |
| HP 24-g038ur        | 1         | 0.81%   |
| HP 15               | 1         | 0.81%   |
| HP 14               | 1         | 0.81%   |
| Gigabyte H410M      | 1         | 0.81%   |
| Gigabyte H270M-DS3H | 1         | 0.81%   |
| Gigabyte G41MT-S2   | 1         | 0.81%   |
| Gigabyte F2A78M-DS2 | 1         | 0.81%   |
| Gigabyte B450       | 1         | 0.81%   |
| Gigabyte 990FXA-UD3 | 1         | 0.81%   |
| Gateway DX4840      | 1         | 0.81%   |
| Fujitsu D3220-A1    | 1         | 0.81%   |
| eMachines eM350     | 1         | 0.81%   |
| Dell Studio         | 1         | 0.81%   |
| Dell Precision      | 1         | 0.81%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 17        | 13.71%  |
| 2021 | 15        | 12.1%   |
| 2020 | 13        | 10.48%  |
| 2013 | 12        | 9.68%   |
| 2011 | 11        | 8.87%   |
| 2012 | 10        | 8.06%   |
| 2018 | 9         | 7.26%   |
| 2010 | 9         | 7.26%   |
| 2015 | 8         | 6.45%   |
| 2016 | 6         | 4.84%   |
| 2014 | 6         | 4.84%   |
| 2017 | 4         | 3.23%   |
| 2009 | 2         | 1.61%   |
| 2008 | 1         | 0.81%   |
| 2007 | 1         | 0.81%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 61        | 49.19%  |
| Desktop     | 57        | 45.97%  |
| Convertible | 2         | 1.61%   |
| Mini pc     | 2         | 1.61%   |
| All in one  | 2         | 1.61%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 124       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 42        | 33.6%   |
| 4.01-8.0    | 39        | 31.2%   |
| 16.01-24.0  | 29        | 23.2%   |
| 32.01-64.0  | 10        | 8%      |
| 64.01-256.0 | 3         | 2.4%    |
| 3.01-4.0    | 1         | 0.8%    |
| 2.01-3.0    | 1         | 0.8%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 68        | 54.4%   |
| 0.51-1.0 | 44        | 35.2%   |
| 1.01-2.0 | 11        | 8.8%    |
| 3.01-4.0 | 2         | 1.6%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 81        | 64.29%  |
| 2      | 23        | 18.25%  |
| 3      | 11        | 8.73%   |
| 4      | 7         | 5.56%   |
| 0      | 3         | 2.38%   |
| 5      | 1         | 0.79%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 74        | 59.68%  |
| Yes       | 50        | 40.32%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 114       | 91.94%  |
| No        | 10        | 8.06%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 84        | 67.74%  |
| No        | 40        | 32.26%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 75        | 60.48%  |
| Yes       | 49        | 39.52%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 15        | 12.1%   |
| Brazil      | 12        | 9.68%   |
| Russia      | 11        | 8.87%   |
| Germany     | 11        | 8.87%   |
| Italy       | 6         | 4.84%   |
| Ukraine     | 5         | 4.03%   |
| Spain       | 5         | 4.03%   |
| China       | 5         | 4.03%   |
| UK          | 4         | 3.23%   |
| Poland      | 4         | 3.23%   |
| Mexico      | 4         | 3.23%   |
| South Korea | 3         | 2.42%   |
| Netherlands | 3         | 2.42%   |
| Canada      | 3         | 2.42%   |
| Australia   | 3         | 2.42%   |
| New Zealand | 2         | 1.61%   |
| India       | 2         | 1.61%   |
| Chile       | 2         | 1.61%   |
| Bulgaria    | 2         | 1.61%   |
| Venezuela   | 1         | 0.81%   |
| Turkey      | 1         | 0.81%   |
| Thailand    | 1         | 0.81%   |
| Taiwan      | 1         | 0.81%   |
| Syria       | 1         | 0.81%   |
| Switzerland | 1         | 0.81%   |
| Slovakia    | 1         | 0.81%   |
| Singapore   | 1         | 0.81%   |
| Peru        | 1         | 0.81%   |
| Lithuania   | 1         | 0.81%   |
| Libya       | 1         | 0.81%   |
| Japan       | 1         | 0.81%   |
| Hungary     | 1         | 0.81%   |
| Hong Kong   | 1         | 0.81%   |
| Guatemala   | 1         | 0.81%   |
| Greece      | 1         | 0.81%   |
| France      | 1         | 0.81%   |
| Finland     | 1         | 0.81%   |
| Denmark     | 1         | 0.81%   |
| Czechia     | 1         | 0.81%   |
| Cuba        | 1         | 0.81%   |
| Colombia    | 1         | 0.81%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Tula de Allende    | 2         | 1.59%   |
| Santiago           | 2         | 1.59%   |
| Marlborough        | 2         | 1.59%   |
| Maraba             | 2         | 1.59%   |
| Kyiv               | 2         | 1.59%   |
| Hobart             | 2         | 1.59%   |
| Guangzhou          | 2         | 1.59%   |
| Barcelona          | 2         | 1.59%   |
| Yeongdong-gun      | 1         | 0.79%   |
| Yekaterinburg      | 1         | 0.79%   |
| Xiamen             | 1         | 0.79%   |
| Wolgast            | 1         | 0.79%   |
| Wellington         | 1         | 0.79%   |
| Warrenton          | 1         | 0.79%   |
| Voronezh           | 1         | 0.79%   |
| Ufa                | 1         | 0.79%   |
| Tyumen             | 1         | 0.79%   |
| Tripoli            | 1         | 0.79%   |
| Torre del Mar      | 1         | 0.79%   |
| The Hague          | 1         | 0.79%   |
| Tampa              | 1         | 0.79%   |
| Taito              | 1         | 0.79%   |
| Stuttgart          | 1         | 0.79%   |
| Stralsund          | 1         | 0.79%   |
| Stara Zagora       | 1         | 0.79%   |
| Stade              | 1         | 0.79%   |
| St Petersburg      | 1         | 0.79%   |
| Sofia              | 1         | 0.79%   |
| Singapore          | 1         | 0.79%   |
| Siedlce            | 1         | 0.79%   |
| Sherwood Park      | 1         | 0.79%   |
| Shepetivka         | 1         | 0.79%   |
| Seoul              | 1         | 0.79%   |
| Seattle            | 1         | 0.79%   |
| S??o Paulo         | 1         | 0.79%   |
| Rzesz??w           | 1         | 0.79%   |
| Rostov-on-Don      | 1         | 0.79%   |
| Rome               | 1         | 0.79%   |
| Rio de Janeiro     | 1         | 0.79%   |
| Riehen             | 1         | 0.79%   |
| Richmond           | 1         | 0.79%   |
| Reriutaba          | 1         | 0.79%   |
| Redmond            | 1         | 0.79%   |
| Qingdao            | 1         | 0.79%   |
| Pruszcz Gdanski    | 1         | 0.79%   |
| Pistoia            | 1         | 0.79%   |
| Pilsen             | 1         | 0.79%   |
| Olympia            | 1         | 0.79%   |
| Old Town           | 1         | 0.79%   |
| Oegstgeest         | 1         | 0.79%   |
| Odessa             | 1         | 0.79%   |
| Obninsk            | 1         | 0.79%   |
| Nughedu San Nicolo | 1         | 0.79%   |
| Nogent-sur-Marne   | 1         | 0.79%   |
| Nieuwegein         | 1         | 0.79%   |
| Newtownabbey       | 1         | 0.79%   |
| New Plymouth       | 1         | 0.79%   |
| Mykolayiv          | 1         | 0.79%   |
| Munich             | 1         | 0.79%   |
| Moscow             | 1         | 0.79%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 31        | 36     | 18.45%  |
| Seagate             | 29        | 34     | 17.26%  |
| Samsung Electronics | 25        | 31     | 14.88%  |
| Toshiba             | 12        | 16     | 7.14%   |
| Kingston            | 9         | 13     | 5.36%   |
| Crucial             | 8         | 11     | 4.76%   |
| Hitachi             | 7         | 9      | 4.17%   |
| SanDisk             | 6         | 6      | 3.57%   |
| Intel               | 3         | 3      | 1.79%   |
| HGST                | 3         | 3      | 1.79%   |
| Corsair             | 3         | 3      | 1.79%   |
| A-DATA Technology   | 3         | 5      | 1.79%   |
| SPCC                | 2         | 2      | 1.19%   |
| Smartbuy            | 2         | 2      | 1.19%   |
| PLEXTOR             | 2         | 2      | 1.19%   |
| KingSpec            | 2         | 2      | 1.19%   |
| China               | 2         | 2      | 1.19%   |
| Apacer              | 2         | 2      | 1.19%   |
| Verbatim            | 1         | 1      | 0.6%    |
| Transcend           | 1         | 1      | 0.6%    |
| Silicon Motion      | 1         | 1      | 0.6%    |
| PNY                 | 1         | 1      | 0.6%    |
| Patriot             | 1         | 1      | 0.6%    |
| OCZ                 | 1         | 1      | 0.6%    |
| Micron Technology   | 1         | 1      | 0.6%    |
| LITEONIT            | 1         | 1      | 0.6%    |
| LITEON              | 1         | 1      | 0.6%    |
| Lexar               | 1         | 1      | 0.6%    |
| Leven               | 1         | 1      | 0.6%    |
| Hewlett-Packard     | 1         | 1      | 0.6%    |
| GOODRAM             | 1         | 1      | 0.6%    |
| Gigabyte Technology | 1         | 1      | 0.6%    |
| FORESEE             | 1         | 1      | 0.6%    |
| Apple               | 1         | 1      | 0.6%    |
| AMD                 | 1         | 1      | 0.6%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Seagate ST9500325AS 500GB          | 3         | 1.61%   |
| Samsung SSD 860 EVO 500GB          | 3         | 1.61%   |
| Samsung SSD 860 EVO 1TB            | 3         | 1.61%   |
| WDC WDS100T2B0C-00PXH0 1TB         | 2         | 1.08%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 2         | 1.08%   |
| Toshiba MQ01ABF050 500GB           | 2         | 1.08%   |
| Toshiba MQ01ABD100 1TB             | 2         | 1.08%   |
| Toshiba DT01ACA100 1TB             | 2         | 1.08%   |
| Seagate ST9500420AS 500GB          | 2         | 1.08%   |
| Seagate ST3500312CS 500GB          | 2         | 1.08%   |
| Seagate ST1000LM048-2E7172 1TB     | 2         | 1.08%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 1.08%   |
| SanDisk SDSSDA240G 240GB           | 2         | 1.08%   |
| SanDisk SD5SE2256G1002E 256GB      | 2         | 1.08%   |
| Samsung SSD 970 EVO Plus 500GB     | 2         | 1.08%   |
| Samsung SSD 850 EVO 250GB          | 2         | 1.08%   |
| Samsung MZ7TE128HMGR-000L1 128GB   | 2         | 1.08%   |
| Samsung HD322HJ 320GB              | 2         | 1.08%   |
| Kingston SA400S37960G 960GB        | 2         | 1.08%   |
| Hitachi HTS545025B9A300 250GB      | 2         | 1.08%   |
| Crucial CT250MX500SSD1 250GB       | 2         | 1.08%   |
| China SATA SSD 120GB               | 2         | 1.08%   |
| WDC WDS250G2X0C-00L350 250GB       | 1         | 0.54%   |
| WDC WDS240G2G0A-00JH30 240GB       | 1         | 0.54%   |
| WDC WD800JD-00LSA0 80GB            | 1         | 0.54%   |
| WDC WD5000LPCX-00VHAT0 500GB       | 1         | 0.54%   |
| WDC WD5000BPKT-00PK4T0 500GB       | 1         | 0.54%   |
| WDC WD5000BEKT-60KA9T0 500GB       | 1         | 0.54%   |
| WDC WD5000AAVS-00ZTB0 500GB        | 1         | 0.54%   |
| WDC WD5000AAKX-08ERMA0 500GB       | 1         | 0.54%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 1         | 0.54%   |
| WDC WD5000AAKS-08V0A0 500GB        | 1         | 0.54%   |
| WDC WD5000AAKS-00V1A0 500GB        | 1         | 0.54%   |
| WDC WD40EZRZ-22GXCB0 4TB           | 1         | 0.54%   |
| WDC WD3200BEVT-80A0RT0 320GB       | 1         | 0.54%   |
| WDC WD3200AAKS-00UU3A0 320GB       | 1         | 0.54%   |
| WDC WD30EZRZ-00WN9B0 3TB           | 1         | 0.54%   |
| WDC WD3003FZEX-00Z4SA0 3TB         | 1         | 0.54%   |
| WDC WD2500JD-75HBB0 250GB          | 1         | 0.54%   |
| WDC WD2500BEVS-22UST0 250GB        | 1         | 0.54%   |
| WDC WD2500BEVS-08VAT2 250GB        | 1         | 0.54%   |
| WDC WD20SMZW-11YFCS0 2TB           | 1         | 0.54%   |
| WDC WD1600BPVT-11JJ5T0 160GB       | 1         | 0.54%   |
| WDC WD1600BEVT-22ZCT0 160GB        | 1         | 0.54%   |
| WDC WD1600AAJS-00WAA0 160GB        | 1         | 0.54%   |
| WDC WD1600AAJS-00V4A0 160GB        | 1         | 0.54%   |
| WDC WD1200BEVS-07RST0 120GB        | 1         | 0.54%   |
| WDC WD10SPZX-22Z10T0 1TB           | 1         | 0.54%   |
| WDC WD10JMVW-11AJGS0 1TB           | 1         | 0.54%   |
| WDC WD10EZRX-00A8LB0 1TB           | 1         | 0.54%   |
| WDC WD10EZEX-75WN4A1 1TB           | 1         | 0.54%   |
| WDC WD10EFRX-68FYTN0 1TB           | 1         | 0.54%   |
| WDC WD1002FAEX-00Y9A0 1TB          | 1         | 0.54%   |
| Verbatim Vi550 S3 SSD 128GB        | 1         | 0.54%   |
| Transcend TS120GMTS420S 120GB      | 1         | 0.54%   |
| Toshiba MQ02ABD100H 1TB            | 1         | 0.54%   |
| Toshiba MQ01UBD100 1TB             | 1         | 0.54%   |
| Toshiba MQ01ABD050 500GB           | 1         | 0.54%   |
| Toshiba MK5061GSYN 500GB           | 1         | 0.54%   |
| Toshiba MK3261GSYN 320GB           | 1         | 0.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 29        | 34     | 34.52%  |
| WDC                 | 28        | 32     | 33.33%  |
| Toshiba             | 12        | 16     | 14.29%  |
| Hitachi             | 7         | 9      | 8.33%   |
| Samsung Electronics | 4         | 6      | 4.76%   |
| HGST                | 3         | 3      | 3.57%   |
| Hewlett-Packard     | 1         | 1      | 1.19%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 18     | 22.86%  |
| Kingston            | 9         | 13     | 12.86%  |
| Crucial             | 8         | 11     | 11.43%  |
| SanDisk             | 6         | 6      | 8.57%   |
| Smartbuy            | 2         | 2      | 2.86%   |
| PLEXTOR             | 2         | 2      | 2.86%   |
| KingSpec            | 2         | 2      | 2.86%   |
| Intel               | 2         | 2      | 2.86%   |
| Corsair             | 2         | 2      | 2.86%   |
| China               | 2         | 2      | 2.86%   |
| Apacer              | 2         | 2      | 2.86%   |
| WDC                 | 1         | 1      | 1.43%   |
| Verbatim            | 1         | 1      | 1.43%   |
| Transcend           | 1         | 1      | 1.43%   |
| SPCC                | 1         | 1      | 1.43%   |
| PNY                 | 1         | 1      | 1.43%   |
| Patriot             | 1         | 1      | 1.43%   |
| OCZ                 | 1         | 1      | 1.43%   |
| Micron Technology   | 1         | 1      | 1.43%   |
| LITEONIT            | 1         | 1      | 1.43%   |
| LITEON              | 1         | 1      | 1.43%   |
| Lexar               | 1         | 1      | 1.43%   |
| Leven               | 1         | 1      | 1.43%   |
| GOODRAM             | 1         | 1      | 1.43%   |
| FORESEE             | 1         | 1      | 1.43%   |
| Apple               | 1         | 1      | 1.43%   |
| AMD                 | 1         | 1      | 1.43%   |
| A-DATA Technology   | 1         | 2      | 1.43%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 69        | 101    | 46.62%  |
| SSD  | 63        | 80     | 42.57%  |
| NVMe | 16        | 18     | 10.81%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 113       | 181    | 87.6%   |
| NVMe | 16        | 18     | 12.4%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 94        | 127    | 66.67%  |
| 0.51-1.0   | 34        | 38     | 24.11%  |
| 1.01-2.0   | 7         | 8      | 4.96%   |
| 2.01-3.0   | 4         | 6      | 2.84%   |
| 3.01-4.0   | 2         | 2      | 1.42%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 76        | 59.38%  |
| 101-250    | 27        | 21.09%  |
| 251-500    | 17        | 13.28%  |
| 501-1000   | 5         | 3.91%   |
| 51-100     | 2         | 1.56%   |
| 21-50      | 1         | 0.78%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 124       | 100%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                           | Computers | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| Seagate ST9500420AS 500GB                       | 2         | 2      | 5.88%   |
| Samsung Electronics HD322HJ 320GB               | 2         | 2      | 5.88%   |
| WDC WD5000AAKX-08ERMA0 500GB                    | 1         | 1      | 2.94%   |
| WDC WD5000AAKX-00ERMA0 500GB                    | 1         | 1      | 2.94%   |
| WDC WD5000AAKS-08V0A0 500GB                     | 1         | 1      | 2.94%   |
| WDC WD5000AAKS-00V1A0 500GB                     | 1         | 1      | 2.94%   |
| WDC WD3200BPVT-22JJ5T0 320GB                    | 1         | 1      | 2.94%   |
| WDC WD3200BEVT-80A0RT0 320GB                    | 1         | 1      | 2.94%   |
| WDC WD3200AAKS-00UU3A0 320GB                    | 1         | 1      | 2.94%   |
| WDC WD10JMVW-11AJGS0 1TB                        | 1         | 1      | 2.94%   |
| Toshiba MQ01UBD100 1TB                          | 1         | 1      | 2.94%   |
| Toshiba MQ01ABF050 500GB                        | 1         | 2      | 2.94%   |
| Toshiba MQ01ABD050 500GB                        | 1         | 1      | 2.94%   |
| Toshiba MK5061GSYN 500GB                        | 1         | 1      | 2.94%   |
| Toshiba MK3261GSYN 320GB                        | 1         | 2      | 2.94%   |
| Toshiba DT01ACA100 1TB                          | 1         | 2      | 2.94%   |
| Seagate ST9500325AS 500GB                       | 1         | 1      | 2.94%   |
| Seagate ST9320325AS 320GB                       | 1         | 1      | 2.94%   |
| Seagate ST750LM022 HN-M750MBB 752GB             | 1         | 1      | 2.94%   |
| Seagate ST500LM021-1KJ152 500GB                 | 1         | 1      | 2.94%   |
| Seagate ST500DM002-1BD142 500GB                 | 1         | 1      | 2.94%   |
| Seagate ST3500413AS 500GB                       | 1         | 1      | 2.94%   |
| Seagate ST320LT012-9WS14C 320GB                 | 1         | 1      | 2.94%   |
| Seagate ST1000LM048-2E7172 1TB                  | 1         | 1      | 2.94%   |
| Seagate ST1000LM024 HN-M101MBB 1TB              | 1         | 1      | 2.94%   |
| SanDisk SDSSDA240G 240GB                        | 1         | 1      | 2.94%   |
| SanDisk SD5SE2256G1002E 256GB                   | 1         | 1      | 2.94%   |
| Samsung Electronics HD161HJ 160GB               | 1         | 1      | 2.94%   |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB | 1         | 1      | 2.94%   |
| Hitachi HTS541080G9SA00 80GB                    | 1         | 1      | 2.94%   |
| HGST HTS541010A9E680 1TB                        | 1         | 1      | 2.94%   |
| Corsair Force GT 120GB                          | 1         | 1      | 2.94%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 11     | 33.33%  |
| WDC                 | 8         | 8      | 24.24%  |
| Toshiba             | 6         | 9      | 18.18%  |
| SanDisk             | 2         | 2      | 6.06%   |
| Samsung Electronics | 2         | 3      | 6.06%   |
| Micron Technology   | 1         | 1      | 3.03%   |
| Hitachi             | 1         | 1      | 3.03%   |
| HGST                | 1         | 1      | 3.03%   |
| Corsair             | 1         | 1      | 3.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 11     | 37.93%  |
| WDC                 | 8         | 8      | 27.59%  |
| Toshiba             | 6         | 9      | 20.69%  |
| Samsung Electronics | 2         | 3      | 6.9%    |
| Hitachi             | 1         | 1      | 3.45%   |
| HGST                | 1         | 1      | 3.45%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 28        | 33     | 87.5%   |
| SSD  | 4         | 4      | 12.5%   |

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
| Works    | 101       | 160    | 74.81%  |
| Malfunc  | 32        | 37     | 23.7%   |
| Detected | 1         | 1      | 0.74%   |
| Failed   | 1         | 1      | 0.74%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 95        | 66.9%   |
| AMD                        | 26        | 18.31%  |
| Samsung Electronics        | 6         | 4.23%   |
| Sandisk                    | 3         | 2.11%   |
| Phison Electronics         | 3         | 2.11%   |
| ASMedia Technology         | 3         | 2.11%   |
| Silicon Motion             | 1         | 0.7%    |
| Realtek Semiconductor      | 1         | 0.7%    |
| Lite-On IT Corp. / Plextor | 1         | 0.7%    |
| JMicron Technology         | 1         | 0.7%    |
| Hewlett-Packard            | 1         | 0.7%    |
| ADATA Technology           | 1         | 0.7%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 16        | 9.88%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 16        | 9.88%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 7         | 4.32%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 7         | 4.32%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 6         | 3.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 6         | 3.7%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 5         | 3.09%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5         | 3.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 5         | 3.09%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5         | 3.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4         | 2.47%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 4         | 2.47%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3         | 1.85%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3         | 1.85%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3         | 1.85%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 3         | 1.85%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3         | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3         | 1.85%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3         | 1.85%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3         | 1.85%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3         | 1.85%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 2         | 1.23%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2         | 1.23%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 2         | 1.23%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2         | 1.23%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2         | 1.23%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2         | 1.23%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2         | 1.23%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1         | 0.62%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1         | 0.62%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1         | 0.62%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1         | 0.62%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1         | 0.62%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1         | 0.62%   |
| Phison E12 NVMe Controller                                                              | 1         | 0.62%   |
| Lite-On IT Corp. / Plextor M6e PCI Express SSD [Marvell 88SS9183]                       | 1         | 0.62%   |
| JMicron JMB361 AHCI/IDE                                                                 | 1         | 0.62%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                 | 1         | 0.62%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1         | 0.62%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 1         | 0.62%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 1         | 0.62%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1         | 0.62%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1         | 0.62%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 1         | 0.62%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 1         | 0.62%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 1         | 0.62%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1         | 0.62%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 1         | 0.62%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]           | 1         | 0.62%   |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile              | 1         | 0.62%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 1         | 0.62%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5)  | 1         | 0.62%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3)  | 1         | 0.62%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 0.62%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 0.62%   |
| HP Smart Array E200i (SAS Controller)                                                   | 1         | 0.62%   |
| HP Smart Array Controller                                                               | 1         | 0.62%   |
| AMD X370 Series Chipset SATA Controller                                                 | 1         | 0.62%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 1         | 0.62%   |
| AMD FCH SATA Controller D                                                               | 1         | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 104       | 74.29%  |
| NVMe | 16        | 11.43%  |
| IDE  | 16        | 11.43%  |
| RAID | 4         | 2.86%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 97        | 78.23%  |
| AMD    | 27        | 21.77%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-3317U CPU @ 1.70GHz           | 3         | 2.42%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 3         | 2.42%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 2         | 1.61%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 2         | 1.61%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 1.61%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 1.61%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 2         | 1.61%   |
| Intel Core i3-6100U CPU @ 2.30GHz           | 2         | 1.61%   |
| Intel Core i3-6100T CPU @ 3.20GHz           | 2         | 1.61%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 2         | 1.61%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 2         | 1.61%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 2         | 1.61%   |
| AMD FX-8350 Eight-Core Processor            | 2         | 1.61%   |
| Intel Xeon CPU W3680 @ 3.33GHz              | 1         | 0.81%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 1         | 0.81%   |
| Intel Xeon                                  | 1         | 0.81%   |
| Intel Processor 5Y70 CPU @ 1.10GHz          | 1         | 0.81%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1         | 0.81%   |
| Intel Pentium CPU N3530 @ 2.16GHz           | 1         | 0.81%   |
| Intel Pentium CPU G3420 @ 3.20GHz           | 1         | 0.81%   |
| Intel Pentium CPU B960 @ 2.20GHz            | 1         | 0.81%   |
| Intel Pentium CPU 5405U @ 2.30GHz           | 1         | 0.81%   |
| Intel Genuine CPU 2160 @ 1.80GHz            | 1         | 0.81%   |
| Intel Genuine CPU                           | 1         | 0.81%   |
| Intel CPU Version                           | 1         | 0.81%   |
| Intel Core m3-8100Y CPU @ 1.10GHz           | 1         | 0.81%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 1         | 0.81%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1         | 0.81%   |
| Intel Core i7-8559U CPU @ 2.70GHz           | 1         | 0.81%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.81%   |
| Intel Core i7-4712MQ CPU @ 2.30GHz          | 1         | 0.81%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1         | 0.81%   |
| Intel Core i7-3632QM CPU @ 2.20GHz          | 1         | 0.81%   |
| Intel Core i7-3517U CPU @ 1.90GHz           | 1         | 0.81%   |
| Intel Core i7-2860QM CPU @ 2.50GHz          | 1         | 0.81%   |
| Intel Core i7-2640M CPU @ 2.80GH            | 1         | 0.81%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 1         | 0.81%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1         | 0.81%   |
| Intel Core i5-8350U CPU @ 1.70GHz           | 1         | 0.81%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 0.81%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 1         | 0.81%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 1         | 0.81%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1         | 0.81%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 1         | 0.81%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1         | 0.81%   |
| Intel Core i5-4570S CPU @ 2.90GHz           | 1         | 0.81%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1         | 0.81%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1         | 0.81%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 1         | 0.81%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 1         | 0.81%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 0.81%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 1         | 0.81%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 0.81%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1         | 0.81%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 1         | 0.81%   |
| Intel Core i5-2320 CPU @ 3.00GHz            | 1         | 0.81%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 1         | 0.81%   |
| Intel Core i5 CPU M 460 @ 2.53GHz           | 1         | 0.81%   |
| Intel Core i5 CPU M 450 @ 2.40GHz           | 1         | 0.81%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 1         | 0.81%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 33        | 26.61%  |
| Intel Core i3           | 20        | 16.13%  |
| Intel Core i7           | 15        | 12.1%   |
| Intel Core 2 Duo        | 6         | 4.84%   |
| Intel Celeron           | 5         | 4.03%   |
| AMD Ryzen 5             | 5         | 4.03%   |
| Other                   | 4         | 3.23%   |
| Intel Pentium           | 4         | 3.23%   |
| AMD Ryzen 7             | 4         | 3.23%   |
| AMD FX                  | 4         | 3.23%   |
| Intel Xeon              | 3         | 2.42%   |
| Intel Atom              | 3         | 2.42%   |
| AMD Ryzen 9             | 3         | 2.42%   |
| Intel Genuine           | 2         | 1.61%   |
| AMD Ryzen 3             | 2         | 1.61%   |
| AMD E                   | 2         | 1.61%   |
| Intel Pentium Dual-Core | 1         | 0.81%   |
| Intel Core m3           | 1         | 0.81%   |
| Intel Core 2 Quad       | 1         | 0.81%   |
| AMD Ryzen 5 PRO         | 1         | 0.81%   |
| AMD Phenom II X6        | 1         | 0.81%   |
| AMD Phenom II X4        | 1         | 0.81%   |
| AMD C-60                | 1         | 0.81%   |
| AMD A6                  | 1         | 0.81%   |
| AMD A4                  | 1         | 0.81%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 66        | 53.23%  |
| 4       | 28        | 22.58%  |
| 12      | 6         | 4.84%   |
| 6       | 6         | 4.84%   |
| 8       | 5         | 4.03%   |
| 16      | 4         | 3.23%   |
| Unknown | 4         | 3.23%   |
| 24      | 3         | 2.42%   |
| 1       | 2         | 1.61%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 121       | 97.58%  |
| 2      | 3         | 2.42%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 66        | 53.23%  |
| 1       | 54        | 43.55%  |
| Unknown | 4         | 3.23%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| IvyBridge   | 17        | 13.71%  |
| KabyLake    | 14        | 11.29%  |
| Haswell     | 14        | 11.29%  |
| SandyBridge | 13        | 10.48%  |
| Westmere    | 10        | 8.06%   |
| Penryn      | 8         | 6.45%   |
| Zen 2       | 6         | 4.84%   |
| Zen         | 5         | 4.03%   |
| Skylake     | 5         | 4.03%   |
| Broadwell   | 5         | 4.03%   |
| Piledriver  | 4         | 3.23%   |
| Zen+        | 3         | 2.42%   |
| Silvermont  | 3         | 2.42%   |
| Bobcat      | 3         | 2.42%   |
| Nehalem     | 2         | 1.61%   |
| K10         | 2         | 1.61%   |
| Excavator   | 2         | 1.61%   |
| Core        | 2         | 1.61%   |
| Bonnell     | 2         | 1.61%   |
| Zen 3       | 1         | 0.81%   |
| TigerLake   | 1         | 0.81%   |
| CometLake   | 1         | 0.81%   |
| Bulldozer   | 1         | 0.81%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 72        | 54.55%  |
| Nvidia | 34        | 25.76%  |
| AMD    | 26        | 19.7%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                            | 15        | 11.36%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 10        | 7.58%   |
| Intel Core Processor Integrated Graphics Controller                         | 5         | 3.79%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 5         | 3.79%   |
| Nvidia GF119 [GeForce GT 610]                                               | 4         | 3.03%   |
| Intel HD Graphics 5500                                                      | 4         | 3.03%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 4         | 3.03%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3         | 2.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3         | 2.27%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 3         | 2.27%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2         | 1.52%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 2         | 1.52%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 2         | 1.52%   |
| Intel UHD Graphics 620                                                      | 2         | 1.52%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 2         | 1.52%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 2         | 1.52%   |
| Intel HD Graphics 630                                                       | 2         | 1.52%   |
| Intel HD Graphics 620                                                       | 2         | 1.52%   |
| Intel HD Graphics 530                                                       | 2         | 1.52%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller     | 2         | 1.52%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2         | 1.52%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 2         | 1.52%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                    | 2         | 1.52%   |
| AMD Oland PRO [Radeon R7 240/340]                                           | 2         | 1.52%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 2         | 1.52%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1         | 0.76%   |
| Nvidia GT218M [GeForce 310M]                                                | 1         | 0.76%   |
| Nvidia GT215 [GeForce GT 220]                                               | 1         | 0.76%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1         | 0.76%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1         | 0.76%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1         | 0.76%   |
| Nvidia GP104 [GeForce GTX 1060 3GB]                                         | 1         | 0.76%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1         | 0.76%   |
| Nvidia GK107M [GeForce GT 640M LE]                                          | 1         | 0.76%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1         | 0.76%   |
| Nvidia GK104 [GeForce GTX 680]                                              | 1         | 0.76%   |
| Nvidia GF108M [GeForce GT 420M]                                             | 1         | 0.76%   |
| Nvidia GF108GLM [Quadro 1000M]                                              | 1         | 0.76%   |
| Nvidia GF108 [GeForce GT 530]                                               | 1         | 0.76%   |
| Nvidia GF108 [GeForce GT 440]                                               | 1         | 0.76%   |
| Nvidia GF106M [GeForce GTX 460M]                                            | 1         | 0.76%   |
| Nvidia GF106GLM [Quadro 2000M]                                              | 1         | 0.76%   |
| Nvidia G98M [GeForce G 105M]                                                | 1         | 0.76%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 1         | 0.76%   |
| Nvidia G92 [GeForce GT 330]                                                 | 1         | 0.76%   |
| Nvidia G84M [GeForce 8600M GT]                                              | 1         | 0.76%   |
| Intel UHD Graphics 615                                                      | 1         | 0.76%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 1         | 0.76%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1         | 0.76%   |
| Intel HD Graphics 5300                                                      | 1         | 0.76%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1         | 0.76%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                            | 1         | 0.76%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1         | 0.76%   |
| Intel Coffee Lake UHD 610 Graphics Controller                               | 1         | 0.76%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 1         | 0.76%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1         | 0.76%   |
| AMD Wrestler [Radeon HD 6320]                                               | 1         | 0.76%   |
| AMD Wrestler [Radeon HD 6310]                                               | 1         | 0.76%   |
| AMD Wrestler [Radeon HD 6290]                                               | 1         | 0.76%   |
| AMD Venus PRO [Radeon HD 8850M / R9 M265X]                                  | 1         | 0.76%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 59        | 47.58%  |
| 1 x Nvidia     | 28        | 22.58%  |
| 1 x AMD        | 24        | 19.35%  |
| Intel + Nvidia | 6         | 4.84%   |
| 2 x Intel      | 5         | 4.03%   |
| Intel + AMD    | 2         | 1.61%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 103       | 83.06%  |
| Proprietary | 12        | 9.68%   |
| Unknown     | 9         | 7.26%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 94        | 75.2%   |
| 0.01-0.5   | 9         | 7.2%    |
| 1.01-2.0   | 7         | 5.6%    |
| 3.01-4.0   | 6         | 4.8%    |
| 7.01-8.0   | 3         | 2.4%    |
| 5.01-6.0   | 3         | 2.4%    |
| 0.51-1.0   | 3         | 2.4%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 13        | 14.29%  |
| Samsung Electronics     | 11        | 12.09%  |
| AU Optronics            | 10        | 10.99%  |
| Chimei Innolux          | 7         | 7.69%   |
| Hewlett-Packard         | 6         | 6.59%   |
| BOE                     | 6         | 6.59%   |
| Lenovo                  | 5         | 5.49%   |
| InfoVision              | 3         | 3.3%    |
| Iiyama                  | 3         | 3.3%    |
| Dell                    | 3         | 3.3%    |
| BenQ                    | 3         | 3.3%    |
| Ancor Communications    | 3         | 3.3%    |
| Philips                 | 2         | 2.2%    |
| Goldstar                | 2         | 2.2%    |
| Apple                   | 2         | 2.2%    |
| Acer                    | 2         | 2.2%    |
| Vizio                   | 1         | 1.1%    |
| ViewSonic               | 1         | 1.1%    |
| Medion                  | 1         | 1.1%    |
| Haier                   | 1         | 1.1%    |
| Fujitsu Siemens         | 1         | 1.1%    |
| Eizo                    | 1         | 1.1%    |
| Chi Mei Optoelectronics | 1         | 1.1%    |
| ASUSTek Computer        | 1         | 1.1%    |
| AOC                     | 1         | 1.1%    |
| ALP                     | 1         | 1.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0385 1366x768 310x170mm 13.9-inch              | 2         | 2.2%    |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 2         | 2.2%    |
| InfoVision LCD Monitor IVO03F4 1024x600 220x130mm 10.1-inch              | 2         | 2.2%    |
| Iiyama PLE2407HDS IVM560D 1920x1080 520x300mm 23.6-inch                  | 2         | 2.2%    |
| Vizio LCD Monitor VIZ0022 1920x540 480x270mm 21.7-inch                   | 1         | 1.1%    |
| ViewSonic VX2458-mhd VSC0437 1920x1080 520x290mm 23.4-inch               | 1         | 1.1%    |
| Samsung Electronics T22D390 SAM0B69 1920x1080 480x270mm 21.7-inch        | 1         | 1.1%    |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                         | 1         | 1.1%    |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                         | 1         | 1.1%    |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 520x320mm 24.0-inch      | 1         | 1.1%    |
| Samsung Electronics LCD Monitor SEC5742 1366x768 310x170mm 13.9-inch     | 1         | 1.1%    |
| Samsung Electronics LCD Monitor SEC414C 1366x768 310x170mm 13.9-inch     | 1         | 1.1%    |
| Samsung Electronics LCD Monitor SEC3942 1366x768 310x170mm 13.9-inch     | 1         | 1.1%    |
| Samsung Electronics LCD Monitor SEC334A 1366x768 340x190mm 15.3-inch     | 1         | 1.1%    |
| Samsung Electronics LCD Monitor SEC3143 1366x768 310x180mm 14.1-inch     | 1         | 1.1%    |
| Samsung Electronics LCD Monitor SDC434A 3200x1800 290x170mm 13.2-inch    | 1         | 1.1%    |
| Samsung Electronics LCD Monitor SAM4A75 1024x768 300x230mm 14.9-inch     | 1         | 1.1%    |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                  | 1         | 1.1%    |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                   | 1         | 1.1%    |
| Medion MD21281 MED3947 1366x768 410x230mm 18.5-inch                      | 1         | 1.1%    |
| LG Display LCD Monitor LGD11F9 1280x800 290x180mm 13.4-inch              | 1         | 1.1%    |
| LG Display LCD Monitor LGD048C 1920x1080 290x170mm 13.2-inch             | 1         | 1.1%    |
| LG Display LCD Monitor LGD0470 1920x1080 350x190mm 15.7-inch             | 1         | 1.1%    |
| LG Display LCD Monitor LGD0419 2560x1440 310x170mm 13.9-inch             | 1         | 1.1%    |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch              | 1         | 1.1%    |
| LG Display LCD Monitor LGD03AB 1366x768 340x190mm 15.3-inch              | 1         | 1.1%    |
| LG Display LCD Monitor LGD0323 1920x1080 350x190mm 15.7-inch             | 1         | 1.1%    |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 1         | 1.1%    |
| LG Display LCD Monitor LGD021D 1600x900 380x210mm 17.1-inch              | 1         | 1.1%    |
| Lenovo LEN-M73Z-D LEN00A0 1600x900 440x240mm 19.7-inch                   | 1         | 1.1%    |
| Lenovo LEN-E73Z-D LEN00A1 1600x900 440x240mm 19.7-inch                   | 1         | 1.1%    |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                    | 1         | 1.1%    |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch                 | 1         | 1.1%    |
| Lenovo LCD Monitor LEN4050 1280x800 330x210mm 15.4-inch                  | 1         | 1.1%    |
| InfoVision LCD Monitor IVO057F 1920x1080 310x170mm 13.9-inch             | 1         | 1.1%    |
| Iiyama PL2409HD IVM560C 1920x1080 520x290mm 23.4-inch                    | 1         | 1.1%    |
| Hewlett-Packard ZR22w HWP2867 1920x1080 480x270mm 21.7-inch              | 1         | 1.1%    |
| Hewlett-Packard LCD Monitor HWP4267 1920x1080 530x300mm 24.0-inch        | 1         | 1.1%    |
| Hewlett-Packard E243m HPN3465 1920x1080 530x300mm 24.0-inch              | 1         | 1.1%    |
| Hewlett-Packard 2310 HWP288F 1920x1080 510x290mm 23.1-inch               | 1         | 1.1%    |
| Hewlett-Packard 2009 HWP2827 1600x900 440x250mm 19.9-inch                | 1         | 1.1%    |
| Hewlett-Packard 19ka HWP3328 1366x768 410x230mm 18.5-inch                | 1         | 1.1%    |
| Haier HT-20216B(C) HAI2031 1920x1080 480x270mm 21.7-inch                 | 1         | 1.1%    |
| Goldstar L1553S GSM3BB0 1024x768 300x230mm 14.9-inch                     | 1         | 1.1%    |
| Goldstar D2342P GSM5840 1920x1080 510x290mm 23.1-inch                    | 1         | 1.1%    |
| Fujitsu Siemens E19-5 FUS07CD 1280x1024 380x300mm 19.1-inch              | 1         | 1.1%    |
| Eizo EV2316W ENC2394 1920x1080 510x290mm 23.1-inch                       | 1         | 1.1%    |
| Dell U3415W DELA0AA 3440x1440 800x330mm 34.1-inch                        | 1         | 1.1%    |
| Dell E228WFP DELD014 1680x1050 470x300mm 22.0-inch                       | 1         | 1.1%    |
| Dell 1708FP DEL4024 1280x1024 340x270mm 17.1-inch                        | 1         | 1.1%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 340x190mm 15.3-inch         | 1         | 1.1%    |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 340x190mm 15.3-inch          | 1         | 1.1%    |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch          | 1         | 1.1%    |
| Chimei Innolux LCD Monitor CMN1492 1366x768 310x170mm 13.9-inch          | 1         | 1.1%    |
| Chimei Innolux LCD Monitor CMN1482 1600x900 310x170mm 13.9-inch          | 1         | 1.1%    |
| Chimei Innolux LCD Monitor CMN1348 1920x1080 280x160mm 12.7-inch         | 1         | 1.1%    |
| Chimei Innolux LCD Monitor CMN1124 1920x1080 260x140mm 11.6-inch         | 1         | 1.1%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 1         | 1.1%    |
| BOE LCD Monitor BOE0757 1366x768 340x190mm 15.3-inch                     | 1         | 1.1%    |
| BOE LCD Monitor BOE06D3 1366x768 340x190mm 15.3-inch                     | 1         | 1.1%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 34        | 37.36%  |
| 1920x1080 (FHD)    | 29        | 31.87%  |
| 1600x900 (HD+)     | 6         | 6.59%   |
| 1920x1200 (WUXGA)  | 3         | 3.3%    |
| 1680x1050 (WSXGA+) | 3         | 3.3%    |
| 1280x800 (WXGA)    | 3         | 3.3%    |
| 2560x1440 (QHD)    | 2         | 2.2%    |
| 1280x1024 (SXGA)   | 2         | 2.2%    |
| 1024x768 (XGA)     | 2         | 2.2%    |
| 1024x600           | 2         | 2.2%    |
| 3840x2160 (4K)     | 1         | 1.1%    |
| 3440x1440          | 1         | 1.1%    |
| 3200x1800 (QHD+)   | 1         | 1.1%    |
| 1920x540           | 1         | 1.1%    |
| 1360x768           | 1         | 1.1%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 18        | 19.78%  |
| 13      | 17        | 18.68%  |
| 24      | 8         | 8.79%   |
| 23      | 8         | 8.79%   |
| 12      | 6         | 6.59%   |
| 21      | 5         | 5.49%   |
| 18      | 5         | 5.49%   |
| 19      | 4         | 4.4%    |
| 11      | 4         | 4.4%    |
| 22      | 3         | 3.3%    |
| 14      | 3         | 3.3%    |
| 10      | 3         | 3.3%    |
| 17      | 2         | 2.2%    |
| Unknown | 2         | 2.2%    |
| 42      | 1         | 1.1%    |
| 34      | 1         | 1.1%    |
| 27      | 1         | 1.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 33        | 36.26%  |
| 201-300     | 19        | 20.88%  |
| 501-600     | 17        | 18.68%  |
| 401-500     | 16        | 17.58%  |
| 351-400     | 2         | 2.2%    |
| Unknown     | 2         | 2.2%    |
| 701-800     | 1         | 1.1%    |
| 901-1000    | 1         | 1.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 76        | 84.44%  |
| 16/10 | 9         | 10%     |
| 5/4   | 2         | 2.22%   |
| 4/3   | 2         | 2.22%   |
| 21/9  | 1         | 1.11%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 22        | 24.18%  |
| 81-90          | 16        | 17.58%  |
| 91-100         | 13        | 14.29%  |
| 101-110        | 7         | 7.69%   |
| 61-70          | 6         | 6.59%   |
| 141-150        | 6         | 6.59%   |
| 51-60          | 4         | 4.4%    |
| 151-200        | 4         | 4.4%    |
| 41-50          | 3         | 3.3%    |
| 71-80          | 2         | 2.2%    |
| 251-300        | 2         | 2.2%    |
| Unknown        | 2         | 2.2%    |
| 351-500        | 1         | 1.1%    |
| 301-350        | 1         | 1.1%    |
| 121-130        | 1         | 1.1%    |
| 501-1000       | 1         | 1.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 35        | 38.46%  |
| 101-120       | 32        | 35.16%  |
| 121-160       | 16        | 17.58%  |
| 161-240       | 5         | 5.49%   |
| Unknown       | 2         | 2.2%    |
| More than 240 | 1         | 1.1%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 88        | 70.97%  |
| 0     | 33        | 26.61%  |
| 2     | 3         | 2.42%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 62        | 35.23%  |
| Intel                             | 55        | 31.25%  |
| Qualcomm Atheros                  | 20        | 11.36%  |
| Broadcom                          | 18        | 10.23%  |
| JMicron Technology                | 3         | 1.7%    |
| Ericsson Business Mobile Networks | 3         | 1.7%    |
| Ralink Technology                 | 2         | 1.14%   |
| Ralink                            | 2         | 1.14%   |
| Marvell Technology Group          | 2         | 1.14%   |
| Huawei Technologies               | 2         | 1.14%   |
| Xiaomi                            | 1         | 0.57%   |
| Sierra Wireless                   | 1         | 0.57%   |
| IMC Networks                      | 1         | 0.57%   |
| Google                            | 1         | 0.57%   |
| Belkin Components                 | 1         | 0.57%   |
| ASUSTek Computer                  | 1         | 0.57%   |
| Aquantia                          | 1         | 0.57%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 43        | 19.91%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 10        | 4.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 8         | 3.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 7         | 3.24%   |
| Intel Wireless 7265                                                            | 7         | 3.24%   |
| Intel I211 Gigabit Network Connection                                          | 6         | 2.78%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 4         | 1.85%   |
| Intel Wireless 7260                                                            | 4         | 1.85%   |
| Intel Ethernet Connection I217-LM                                              | 4         | 1.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 3         | 1.39%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 3         | 1.39%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 3         | 1.39%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 3         | 1.39%   |
| Intel Wireless 8265 / 8275                                                     | 3         | 1.39%   |
| Intel Ethernet Connection (7) I219-V                                           | 3         | 1.39%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 3         | 1.39%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                             | 3         | 1.39%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 0.93%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 2         | 0.93%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 0.93%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 2         | 0.93%   |
| Intel Ethernet Connection I217-V                                               | 2         | 0.93%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 0.93%   |
| Intel Ethernet Connection (3) I218-V                                           | 2         | 0.93%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 2         | 0.93%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                   | 2         | 0.93%   |
| Intel Centrino Ultimate-N 6300                                                 | 2         | 0.93%   |
| Intel Centrino Advanced-N 6235                                                 | 2         | 0.93%   |
| Intel 82577LC Gigabit Network Connection                                       | 2         | 0.93%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III    | 2         | 0.93%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 2         | 0.93%   |
| Broadcom BCM43142 802.11b/g/n                                                  | 2         | 0.93%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.46%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                                  | 1         | 0.46%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                       | 1         | 0.46%   |
| Realtek RTL8723DE Wireless Network Adapter                                     | 1         | 0.46%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 1         | 0.46%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.46%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                          | 1         | 0.46%   |
| Ralink RT3072 Wireless Adapter                                                 | 1         | 0.46%   |
| Ralink MT7601U Wireless Adapter                                                | 1         | 0.46%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                      | 1         | 0.46%   |
| Ralink RT2561/RT61 rev B 802.11g                                               | 1         | 0.46%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                               | 1         | 0.46%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 1         | 0.46%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                 | 1         | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.46%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.46%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.46%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.46%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 1         | 0.46%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.46%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.46%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1         | 0.46%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 1         | 0.46%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.46%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.46%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                            | 1         | 0.46%   |
| Intel Wireless 8260                                                            | 1         | 0.46%   |
| Intel Wireless 3160                                                            | 1         | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 36        | 40.45%  |
| Realtek Semiconductor | 16        | 17.98%  |
| Qualcomm Atheros      | 16        | 17.98%  |
| Broadcom              | 13        | 14.61%  |
| Ralink Technology     | 2         | 2.25%   |
| Ralink                | 2         | 2.25%   |
| Sierra Wireless       | 1         | 1.12%   |
| IMC Networks          | 1         | 1.12%   |
| Belkin Components     | 1         | 1.12%   |
| ASUSTek Computer      | 1         | 1.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 7         | 7.53%   |
| Intel Wireless 7265                                                         | 7         | 7.53%   |
| Realtek RTL8188EE Wireless Network Adapter                                  | 4         | 4.3%    |
| Intel Wireless 7260                                                         | 4         | 4.3%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 3         | 3.23%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 3         | 3.23%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 3         | 3.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 3         | 3.23%   |
| Intel Wireless 8265 / 8275                                                  | 3         | 3.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 3         | 3.23%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                          | 3         | 3.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 2         | 2.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 2         | 2.15%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                            | 2         | 2.15%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                | 2         | 2.15%   |
| Intel Centrino Ultimate-N 6300                                              | 2         | 2.15%   |
| Intel Centrino Advanced-N 6235                                              | 2         | 2.15%   |
| Broadcom BCM43142 802.11b/g/n                                               | 2         | 2.15%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                               | 1         | 1.08%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                    | 1         | 1.08%   |
| Realtek RTL8723DE Wireless Network Adapter                                  | 1         | 1.08%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                       | 1         | 1.08%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                       | 1         | 1.08%   |
| Ralink RT3072 Wireless Adapter                                              | 1         | 1.08%   |
| Ralink MT7601U Wireless Adapter                                             | 1         | 1.08%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                   | 1         | 1.08%   |
| Ralink RT2561/RT61 rev B 802.11g                                            | 1         | 1.08%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                            | 1         | 1.08%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 1         | 1.08%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)              | 1         | 1.08%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 1         | 1.08%   |
| Intel Wireless 8260                                                         | 1         | 1.08%   |
| Intel Wireless 3160                                                         | 1         | 1.08%   |
| Intel WiFi Link 5100                                                        | 1         | 1.08%   |
| Intel Wi-Fi 6 AX201                                                         | 1         | 1.08%   |
| Intel Wi-Fi 6 AX200                                                         | 1         | 1.08%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                     | 1         | 1.08%   |
| Intel Centrino Wireless-N 6150                                              | 1         | 1.08%   |
| Intel Centrino Wireless-N 2200                                              | 1         | 1.08%   |
| Intel Centrino Wireless-N 135                                               | 1         | 1.08%   |
| Intel Centrino Wireless-N 105                                               | 1         | 1.08%   |
| Intel Centrino WiMAX 6150                                                   | 1         | 1.08%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                    | 1         | 1.08%   |
| IMC Networks Realtek RTL8191SU Wireless LAN 802.11n USB 2.0 Network Adapter | 1         | 1.08%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                          | 1         | 1.08%   |
| Broadcom BCM4331 802.11a/b/g/n                                              | 1         | 1.08%   |
| Broadcom BCM43228 802.11a/b/g/n                                             | 1         | 1.08%   |
| Broadcom BCM43225 802.11b/g/n                                               | 1         | 1.08%   |
| Broadcom BCM43224 802.11a/b/g/n                                             | 1         | 1.08%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                      | 1         | 1.08%   |
| Broadcom BCM4321 802.11a/b/g/n                                              | 1         | 1.08%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                         | 1         | 1.08%   |
| Belkin Components F5D7050 Wireless G Adapter v4000 [Zydas ZD1211B]          | 1         | 1.08%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                   | 1         | 1.08%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 53        | 44.92%  |
| Intel                    | 39        | 33.05%  |
| Qualcomm Atheros         | 10        | 8.47%   |
| Broadcom                 | 7         | 5.93%   |
| JMicron Technology       | 3         | 2.54%   |
| Marvell Technology Group | 2         | 1.69%   |
| Xiaomi                   | 1         | 0.85%   |
| Huawei Technologies      | 1         | 0.85%   |
| Google                   | 1         | 0.85%   |
| Aquantia                 | 1         | 0.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 43        | 36.44%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 10        | 8.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 8         | 6.78%   |
| Intel I211 Gigabit Network Connection                                          | 6         | 5.08%   |
| Intel Ethernet Connection I217-LM                                              | 4         | 3.39%   |
| Intel Ethernet Connection (7) I219-V                                           | 3         | 2.54%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 1.69%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 2         | 1.69%   |
| Intel Ethernet Connection I217-V                                               | 2         | 1.69%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 1.69%   |
| Intel Ethernet Connection (3) I218-V                                           | 2         | 1.69%   |
| Intel 82577LC Gigabit Network Connection                                       | 2         | 1.69%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 2         | 1.69%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.85%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.85%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.85%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.85%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 1         | 0.85%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.85%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.85%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1         | 0.85%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.85%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.85%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                            | 1         | 0.85%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.85%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.85%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.85%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 0.85%   |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 0.85%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 0.85%   |
| Intel Ethernet Connection (11) I219-V                                          | 1         | 0.85%   |
| Intel 82583V Gigabit Network Connection                                        | 1         | 0.85%   |
| Intel 82574L Gigabit Network Connection                                        | 1         | 0.85%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 0.85%   |
| Huawei USB Composite Device                                                    | 1         | 0.85%   |
| Google Nexus/Pixel Device (tether)                                             | 1         | 0.85%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                 | 1         | 0.85%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 1         | 0.85%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                        | 1         | 0.85%   |
| Broadcom NetXtreme BCM5705_2 Gigabit Ethernet                                  | 1         | 0.85%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 1         | 0.85%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]              | 1         | 0.85%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 114       | 55.88%  |
| WiFi     | 85        | 41.67%  |
| Unknown  | 3         | 1.47%   |
| Modem    | 2         | 0.98%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 111       | 60.99%  |
| WiFi     | 68        | 37.36%  |
| Unknown  | 2         | 1.1%    |
| Modem    | 1         | 0.55%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 70        | 56.45%  |
| 1     | 52        | 41.94%  |
| 3     | 2         | 1.61%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 122       | 97.6%   |
| Yes  | 3         | 2.4%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 20        | 40.82%  |
| Broadcom                        | 7         | 14.29%  |
| Apple                           | 7         | 14.29%  |
| Realtek Semiconductor           | 6         | 12.24%  |
| Qualcomm Atheros Communications | 2         | 4.08%   |
| Foxconn / Hon Hai               | 2         | 4.08%   |
| Cambridge Silicon Radio         | 2         | 4.08%   |
| Ralink                          | 1         | 2.04%   |
| Hewlett-Packard                 | 1         | 2.04%   |
| ASUSTek Computer                | 1         | 2.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 13        | 26.53%  |
| Apple Apple Broadcom Built-in Bluetooth                     | 4         | 8.16%   |
| Realtek  Bluetooth Adapter                                  | 2         | 4.08%   |
| Realtek  Bluetooth 4.0 Adapter                              | 2         | 4.08%   |
| Intel Wireless-AC 3168 Bluetooth                            | 2         | 4.08%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 4.08%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2         | 4.08%   |
| Broadcom BCM43142 Bluetooth 4.0                             | 2         | 4.08%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 4.08%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 2         | 4.08%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 2.04%   |
| Realtek Bluetooth Radio                                     | 1         | 2.04%   |
| Ralink RT3290 Bluetooth                                     | 1         | 2.04%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 2.04%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 2.04%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 1         | 2.04%   |
| Intel AX201 Bluetooth                                       | 1         | 2.04%   |
| Intel AX200 Bluetooth                                       | 1         | 2.04%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 2.04%   |
| Foxconn / Hon Hai Broadcom Bluetooth 4.0 USB                | 1         | 2.04%   |
| Foxconn / Hon Hai Atheros AR3012 Bluetooth                  | 1         | 2.04%   |
| Broadcom Broadcom Bluetooth 4.0                             | 1         | 2.04%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter            | 1         | 2.04%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 1         | 2.04%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 1         | 2.04%   |
| Apple Bluetooth HCI                                         | 1         | 2.04%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 95        | 56.21%  |
| AMD                     | 33        | 19.53%  |
| Nvidia                  | 26        | 15.38%  |
| C-Media Electronics     | 5         | 2.96%   |
| Texas Instruments       | 3         | 1.78%   |
| Logitech                | 2         | 1.18%   |
| XMOS                    | 1         | 0.59%   |
| Plantronics             | 1         | 0.59%   |
| Hewlett-Packard         | 1         | 0.59%   |
| Creative Labs           | 1         | 0.59%   |
| BEHRINGER International | 1         | 0.59%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 20        | 10%     |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 11        | 5.5%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10        | 5%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 10        | 5%      |
| AMD SBx00 Azalia (Intel HDA)                                               | 8         | 4%      |
| Intel Sunrise Point-LP HD Audio                                            | 7         | 3.5%    |
| AMD Starship/Matisse HD Audio Controller                                   | 6         | 3%      |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 6         | 3%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 2.5%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 2.5%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 2.5%    |
| Intel Broadwell-U Audio Controller                                         | 5         | 2.5%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 2.5%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5         | 2.5%    |
| Nvidia GF119 HDMI Audio Controller                                         | 4         | 2%      |
| Nvidia GF108 High Definition Audio Controller                              | 4         | 2%      |
| Intel 8 Series HD Audio Controller                                         | 4         | 2%      |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4         | 2%      |
| Texas Instruments PCM2902 Audio Codec                                      | 3         | 1.5%    |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 1.5%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3         | 1.5%    |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 1.5%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 1.5%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 1.5%    |
| AMD Wrestler HDMI Audio                                                    | 3         | 1.5%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3         | 1.5%    |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 3         | 1.5%    |
| Nvidia High Definition Audio Controller                                    | 2         | 1%      |
| Nvidia GM206 High Definition Audio Controller                              | 2         | 1%      |
| Nvidia GK104 HDMI Audio Controller                                         | 2         | 1%      |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 1%      |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 1%      |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2         | 1%      |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 1%      |
| Intel 200 Series PCH HD Audio                                              | 2         | 1%      |
| C-Media Electronics CM108 Audio Controller                                 | 2         | 1%      |
| AMD High Definition Audio Controller                                       | 2         | 1%      |
| AMD FCH Azalia Controller                                                  | 2         | 1%      |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 1%      |
| XMOS retrieving string failed                                              | 1         | 0.5%    |
| Plantronics Plantronics Blackwire 325.1                                    | 1         | 0.5%    |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 0.5%    |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.5%    |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.5%    |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.5%    |
| Nvidia GP102 HDMI Audio Controller                                         | 1         | 0.5%    |
| Nvidia GF106 High Definition Audio Controller                              | 1         | 0.5%    |
| Logitech HD Webcam C910                                                    | 1         | 0.5%    |
| Logitech HD Webcam C510                                                    | 1         | 0.5%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 0.5%    |
| Intel Comet Lake PCH cAVS                                                  | 1         | 0.5%    |
| Hewlett-Packard E243m                                                      | 1         | 0.5%    |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 1         | 0.5%    |
| C-Media Electronics CM102-A+/102S+ Audio Controller                        | 1         | 0.5%    |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1         | 0.5%    |
| C-Media Electronics Audio Adapter                                          | 1         | 0.5%    |
| BEHRINGER International UMC202HD 192k                                      | 1         | 0.5%    |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1         | 0.5%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1         | 0.5%    |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 1         | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 24        | 15.89%  |
| SK Hynix            | 23        | 15.23%  |
| Kingston            | 20        | 13.25%  |
| Unknown             | 15        | 9.93%   |
| Micron Technology   | 11        | 7.28%   |
| Crucial             | 10        | 6.62%   |
| Nanya Technology    | 6         | 3.97%   |
| Team                | 5         | 3.31%   |
| Unknown             | 5         | 3.31%   |
| G.Skill             | 4         | 2.65%   |
| Corsair             | 4         | 2.65%   |
| Smart               | 3         | 1.99%   |
| Ramaxel Technology  | 3         | 1.99%   |
| Elpida              | 3         | 1.99%   |
| A-DATA Technology   | 3         | 1.99%   |
| Transcend           | 2         | 1.32%   |
| Teikon              | 2         | 1.32%   |
| Patriot             | 2         | 1.32%   |
| Smart Brazil        | 1         | 0.66%   |
| SHARETRONIC         | 1         | 0.66%   |
| PKI/Kingston        | 1         | 0.66%   |
| Hikvision           | 1         | 0.66%   |
| ASint Technology    | 1         | 0.66%   |
| Apacer              | 1         | 0.66%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown                                                      | 5         | 3.21%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 2         | 1.28%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s          | 2         | 1.28%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 1.28%   |
| SK Hynix RAM HMT451S6BCFR8A-PB 4GB DIMM DDR3 1600MT/s        | 2         | 1.28%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 1.28%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 1.28%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1333MT/s        | 2         | 1.28%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s        | 2         | 1.28%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1333MT/s        | 2         | 1.28%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 2         | 1.28%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s        | 2         | 1.28%   |
| Nanya RAM NT2GC64B8HA1NS-BE 2GB SODIMM DDR3 1067MT/s         | 2         | 1.28%   |
| Micron RAM 8ATF1G64HZ-2G3H1 8GB SODIMM DDR4 2400MT/s         | 2         | 1.28%   |
| Crucial RAM Module 8GB SODIMM DDR3 1600MT/s                  | 2         | 1.28%   |
| Crucial RAM CT8G4DFS8266.M8FD 8GB DIMM DDR4 2667MT/s         | 2         | 1.28%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                  | 1         | 0.64%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                         | 1         | 0.64%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                  | 1         | 0.64%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                  | 1         | 0.64%   |
| Unknown RAM Module 4GB SODIMM DDR3                           | 1         | 0.64%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                   | 1         | 0.64%   |
| Unknown RAM Module 4GB FB-DIMM DDR2 667MT/s                  | 1         | 0.64%   |
| Unknown RAM Module 4GB DIMM DDR3 800MT/s                     | 1         | 0.64%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                    | 1         | 0.64%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                     | 1         | 0.64%   |
| Unknown RAM Module 4GB DIMM 400MT/s                          | 1         | 0.64%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 1         | 0.64%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                         | 1         | 0.64%   |
| Transcend RAM Module 2GB DIMM DDR3 1333MT/s                  | 1         | 0.64%   |
| Transcend RAM JM1333KSN-4G 4GB DIMM DDR3 1333MT/s            | 1         | 0.64%   |
| Teikon RAM TMT451S6BFR8A-PBHC 4GB SODIMM DDR3 1333MT/s       | 1         | 0.64%   |
| Teikon RAM TMT41GS6BFR8A-PBSC 8GB SODIMM DDR3 1600MT/s       | 1         | 0.64%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2667MT/s           | 1         | 0.64%   |
| Team RAM TEAMGROUP-SD3-1066 4GB SODIMM DDR3 1067MT/s         | 1         | 0.64%   |
| Team RAM Elite-1333 4GB SODIMM DDR3 1333MT/s                 | 1         | 0.64%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s        | 1         | 0.64%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s        | 1         | 0.64%   |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s        | 1         | 0.64%   |
| Smart Brazil RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2133MT/s | 1         | 0.64%   |
| SK Hynix RAM Module 8GB SODIMM DDR4 2400MT/s                 | 1         | 0.64%   |
| SK Hynix RAM Module 8GB Row Of Chips LPDDR3 1600MT/s         | 1         | 0.64%   |
| SK Hynix RAM Module 2GB SODIMM DDR3 1600MT/s                 | 1         | 0.64%   |
| SK Hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s         | 1         | 0.64%   |
| SK Hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.64%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.64%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 0.64%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 0.64%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s         | 1         | 0.64%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.64%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 1         | 0.64%   |
| SK Hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.64%   |
| SK Hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1333MT/s       | 1         | 0.64%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 1         | 0.64%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s       | 1         | 0.64%   |
| SK Hynix RAM HMA81GS6MFR8N-UH 8GB SODIMM DDR4 2400MT/s       | 1         | 0.64%   |
| SHARETRONIC RAM Module 2GB SODIMM DDR3 1600MT/s              | 1         | 0.64%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s                    | 1         | 0.64%   |
| Samsung RAM Module 2GB DIMM DDR3 400MT/s                     | 1         | 0.64%   |
| Samsung RAM Module 16GB DIMM DDR3 1333MT/s                   | 1         | 0.64%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 72        | 59.02%  |
| DDR4    | 35        | 28.69%  |
| DDR2    | 6         | 4.92%   |
| Unknown | 4         | 3.28%   |
| LPDDR3  | 2         | 1.64%   |
| SDRAM   | 1         | 0.82%   |
| LPDDR4  | 1         | 0.82%   |
| DDR     | 1         | 0.82%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 65        | 53.28%  |
| DIMM         | 53        | 43.44%  |
| Row Of Chips | 2         | 1.64%   |
| FB-DIMM      | 1         | 0.82%   |
| Chip         | 1         | 0.82%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 60        | 43.48%  |
| 8192  | 38        | 27.54%  |
| 2048  | 29        | 21.01%  |
| 16384 | 9         | 6.52%   |
| 32768 | 1         | 0.72%   |
| 1024  | 1         | 0.72%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 45        | 33.83%  |
| 1333    | 28        | 21.05%  |
| 2400    | 10        | 7.52%   |
| 1067    | 10        | 7.52%   |
| 2667    | 9         | 6.77%   |
| 2133    | 7         | 5.26%   |
| 3200    | 5         | 3.76%   |
| 667     | 4         | 3.01%   |
| 2666    | 2         | 1.5%    |
| 1334    | 2         | 1.5%    |
| 1066    | 2         | 1.5%    |
| 800     | 2         | 1.5%    |
| 400     | 2         | 1.5%    |
| 4267    | 1         | 0.75%   |
| 3000    | 1         | 0.75%   |
| 1200    | 1         | 0.75%   |
| 533     | 1         | 0.75%   |
| Unknown | 1         | 0.75%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Brother Industries    | 2         | 66.67%  |
| Lexmark International | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Lexmark International SINDOH A603_A608 Print | 1         | 33.33%  |
| Brother HL-L2310D series                     | 1         | 33.33%  |
| Brother DCP-J100                             | 1         | 33.33%  |

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
| Chicony Electronics                    | 15        | 26.79%  |
| Acer                                   | 6         | 10.71%  |
| IMC Networks                           | 5         | 8.93%   |
| Sunplus Innovation Technology          | 4         | 7.14%   |
| Realtek Semiconductor                  | 4         | 7.14%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 7.14%   |
| Microdia                               | 3         | 5.36%   |
| Z-Star Microelectronics                | 2         | 3.57%   |
| Suyin                                  | 2         | 3.57%   |
| Apple                                  | 2         | 3.57%   |
| Tripath Technology                     | 1         | 1.79%   |
| Syntek                                 | 1         | 1.79%   |
| Logitech                               | 1         | 1.79%   |
| Lite-On Technology                     | 1         | 1.79%   |
| Lenovo                                 | 1         | 1.79%   |
| Importek                               | 1         | 1.79%   |
| Hewlett-Packard                        | 1         | 1.79%   |
| Foxconn / Hon Hai                      | 1         | 1.79%   |
| ALi                                    | 1         | 1.79%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 7         | 12.5%   |
| Acer Integrated Camera                                         | 3         | 5.36%   |
| Realtek Realtek USB2.0 PC Camera                               | 2         | 3.57%   |
| Realtek Integrated_Webcam_HD                                   | 2         | 3.57%   |
| IMC Networks XHC Camera                                        | 2         | 3.57%   |
| Z-Star Integrated Camera                                       | 1         | 1.79%   |
| Z-Star A4 TECH USB2.0 PC Camera J                              | 1         | 1.79%   |
| Tripath 2M Front Camera                                        | 1         | 1.79%   |
| Syntek EasyCamera                                              | 1         | 1.79%   |
| Suyin Integrated_Webcam_HD                                     | 1         | 1.79%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)    | 1         | 1.79%   |
| Sunplus Lenovo EasyCamera                                      | 1         | 1.79%   |
| Sunplus Laptop_Integrated_Webcam_FHD                           | 1         | 1.79%   |
| Sunplus Integrated Camera                                      | 1         | 1.79%   |
| Sunplus HP Universal Camera                                    | 1         | 1.79%   |
| Microdia Laptop_Integrated_Webcam_2M                           | 1         | 1.79%   |
| Microdia Integrated Webcam HD                                  | 1         | 1.79%   |
| Microdia Dell Laptop Integrated Webcam HD                      | 1         | 1.79%   |
| Logitech Webcam C270                                           | 1         | 1.79%   |
| Lite-On Integrated Camera                                      | 1         | 1.79%   |
| Lenovo Integrated Webcam                                       | 1         | 1.79%   |
| Importek HP Webcam                                             | 1         | 1.79%   |
| IMC Networks USB2.0 UVC HD Webcam                              | 1         | 1.79%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 1         | 1.79%   |
| IMC Networks 2M Integrated Webcam                              | 1         | 1.79%   |
| HP Premium Starter Webcam                                      | 1         | 1.79%   |
| Foxconn / Hon Hai USB2.0 Camera                                | 1         | 1.79%   |
| Chicony WebCam                                                 | 1         | 1.79%   |
| Chicony USB2.0 HD UVC WebCam                                   | 1         | 1.79%   |
| Chicony TOSHIBA Web Camera - HD                                | 1         | 1.79%   |
| Chicony Lenovo Integrated Camera (0.3MP)                       | 1         | 1.79%   |
| Chicony Lenovo EasyCamera                                      | 1         | 1.79%   |
| Chicony HP Display Camera                                      | 1         | 1.79%   |
| Chicony Asus 720p CMOS webcam                                  | 1         | 1.79%   |
| Chicony 1.3M Webcam                                            | 1         | 1.79%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam-101           | 1         | 1.79%   |
| Cheng Uei Precision Industry (Foxlink) HP Universal Camera     | 1         | 1.79%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 1.79%   |
| Cheng Uei Precision Industry (Foxlink) HP Integrated Webcam    | 1         | 1.79%   |
| Apple FaceTime HD Camera (Built-in)                            | 1         | 1.79%   |
| Apple FaceTime HD Camera                                       | 1         | 1.79%   |
| ALi WebCam                                                     | 1         | 1.79%   |
| Acer ThinkPad Integrated Camera                                | 1         | 1.79%   |
| Acer Lenovo EasyCamera                                         | 1         | 1.79%   |
| Acer HD Webcam                                                 | 1         | 1.79%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 6         | 46.15%  |
| Upek                  | 3         | 23.08%  |
| AuthenTec             | 3         | 23.08%  |
| Elan Microelectronics | 1         | 7.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 30.77%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 23.08%  |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 7.69%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 7.69%   |
| Elan ELAN WBF Fingerprint Sensor                                           | 1         | 7.69%   |
| AuthenTec AuthenTec Inc. AES1660                                           | 1         | 7.69%   |
| AuthenTec AES2810                                                          | 1         | 7.69%   |
| AuthenTec AES1600                                                          | 1         | 7.69%   |

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
| 1     | 46        | 37.1%   |
| 0     | 32        | 25.81%  |
| 2     | 30        | 24.19%  |
| 3     | 11        | 8.87%   |
| 4     | 5         | 4.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 76        | 49.35%  |
| Card reader              | 22        | 14.29%  |
| Net/wireless             | 21        | 13.64%  |
| Fingerprint reader       | 13        | 8.44%   |
| Firewire controller      | 8         | 5.19%   |
| Bluetooth                | 5         | 3.25%   |
| Sound                    | 3         | 1.95%   |
| Storage                  | 2         | 1.3%    |
| Network                  | 2         | 1.3%    |
| Net/ethernet             | 2         | 1.3%    |
