BSD in France - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for BSD in France.

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

Total: 294

| Vendor    | Model                       | Probe                                                     | Date         |
|-----------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo    | ThinkBook 15 G2 ITL 20VE    | [c6697164fc](https://bsd-hardware.info/?probe=c6697164fc) | Jan 02, 2025 |
| HUAWEI    | KPL-W0X                     | [51514fe0c0](https://bsd-hardware.info/?probe=51514fe0c0) | Dec 28, 2024 |
| HUAWEI    | KPL-W0X                     | [7d9a498768](https://bsd-hardware.info/?probe=7d9a498768) | Dec 28, 2024 |
| HUAWEI    | KPL-W0X                     | [ac7b8b09f0](https://bsd-hardware.info/?probe=ac7b8b09f0) | Dec 24, 2024 |
| Lenovo    | ThinkBook 15 G2 ITL 20VE    | [aa6a6969b9](https://bsd-hardware.info/?probe=aa6a6969b9) | Dec 12, 2024 |
| Lenovo    | ThinkBook 15 G2 ITL 20VE    | [cfc56b5602](https://bsd-hardware.info/?probe=cfc56b5602) | Dec 11, 2024 |
| Deciso    | Netboard A20                | [7a9c98faa1](https://bsd-hardware.info/?probe=7a9c98faa1) | Dec 08, 2024 |
| Alienware | m15 R6                      | [9060b1741b](https://bsd-hardware.info/?probe=9060b1741b) | Dec 08, 2024 |
| Notebook  | N7x0WU                      | [d9312fac72](https://bsd-hardware.info/?probe=d9312fac72) | Dec 05, 2024 |
| Dell      | Precision 7730              | [57ea84435b](https://bsd-hardware.info/?probe=57ea84435b) | Nov 29, 2024 |
| Lenovo    | Legion Pro 5 16IRX9 83DF    | [3fa8964010](https://bsd-hardware.info/?probe=3fa8964010) | Nov 18, 2024 |
| Lenovo    | ThinkPad X270 W10DG 20K5... | [317947a879](https://bsd-hardware.info/?probe=317947a879) | Nov 16, 2024 |
| Dell      | Precision M4800             | [437d5c965b](https://bsd-hardware.info/?probe=437d5c965b) | Nov 15, 2024 |
| Dell      | Precision M4800             | [b586c78d26](https://bsd-hardware.info/?probe=b586c78d26) | Nov 15, 2024 |
| Sony      | SVS1312J3EW                 | [3451ac064b](https://bsd-hardware.info/?probe=3451ac064b) | Nov 02, 2024 |
| Sony      | SVS1312J3EW                 | [c96da35c3f](https://bsd-hardware.info/?probe=c96da35c3f) | Oct 28, 2024 |
| Unknown   | Unknown                     | [43c3d622d9](https://bsd-hardware.info/?probe=43c3d622d9) | Oct 21, 2024 |
| Gigabyte  | AORUS 16X ASG               | [0a05bfa1e3](https://bsd-hardware.info/?probe=0a05bfa1e3) | Oct 08, 2024 |
| HP        | EliteBook 840 G3            | [b4f6d6a1f9](https://bsd-hardware.info/?probe=b4f6d6a1f9) | Oct 03, 2024 |
| HP        | EliteBook 840 G3            | [56d22f4ec1](https://bsd-hardware.info/?probe=56d22f4ec1) | Oct 03, 2024 |
| Sony      | VGN-FZ19VN                  | [a5e398c41f](https://bsd-hardware.info/?probe=a5e398c41f) | Sep 28, 2024 |
| Dell      | System XPS L702X            | [5a0e1971a2](https://bsd-hardware.info/?probe=5a0e1971a2) | Sep 26, 2024 |
| HP        | EliteBook 8440p             | [4ca237f74c](https://bsd-hardware.info/?probe=4ca237f74c) | Sep 24, 2024 |
| Lenovo    | ThinkPad P17 Gen 1 20SN0... | [5c1dfe489a](https://bsd-hardware.info/?probe=5c1dfe489a) | Sep 08, 2024 |
| HP        | EliteBook 8440p             | [d2e93eb2d7](https://bsd-hardware.info/?probe=d2e93eb2d7) | Aug 11, 2024 |
| Unknown   | Unknown                     | [462a87d038](https://bsd-hardware.info/?probe=462a87d038) | Jul 24, 2024 |
| Unknown   | Unknown                     | [341bc14d4f](https://bsd-hardware.info/?probe=341bc14d4f) | Jul 22, 2024 |
| Apple     | MacBookPro14,1              | [41adaa07be](https://bsd-hardware.info/?probe=41adaa07be) | Jun 30, 2024 |
| Deciso    | NetBoard-A20                | [a6261fd253](https://bsd-hardware.info/?probe=a6261fd253) | Jun 20, 2024 |
| Notebook  | W740SU                      | [31be7db967](https://bsd-hardware.info/?probe=31be7db967) | Jun 09, 2024 |
| Dell      | Precision 7520              | [48232bd1d6](https://bsd-hardware.info/?probe=48232bd1d6) | Jun 06, 2024 |
| Notebook  | N7x0WU                      | [61e6b811dd](https://bsd-hardware.info/?probe=61e6b811dd) | Jun 06, 2024 |
| Lenovo    | ThinkPad E14 Gen 5 21JK0... | [f07fafed9c](https://bsd-hardware.info/?probe=f07fafed9c) | Jun 04, 2024 |
| Apple     | MacBookAir6,2               | [a9ec0cba48](https://bsd-hardware.info/?probe=a9ec0cba48) | May 02, 2024 |
| Dell      | Latitude 7490               | [e55889ef1e](https://bsd-hardware.info/?probe=e55889ef1e) | May 02, 2024 |
| Apple     | MacBookAir6,2               | [26a2dbed23](https://bsd-hardware.info/?probe=26a2dbed23) | Apr 28, 2024 |
| Apple     | MacBookAir6,2               | [126d9918f3](https://bsd-hardware.info/?probe=126d9918f3) | Apr 28, 2024 |
| Apple     | MacBookAir6,2               | [5bb2644b89](https://bsd-hardware.info/?probe=5bb2644b89) | Apr 28, 2024 |
| Apple     | MacBookAir6,2               | [2b066c44b9](https://bsd-hardware.info/?probe=2b066c44b9) | Apr 26, 2024 |
| Apple     | MacBookAir6,2               | [a206641c60](https://bsd-hardware.info/?probe=a206641c60) | Apr 26, 2024 |
| Lenovo    | ThinkPad X280 20KFCTO1WW    | [d76cb40918](https://bsd-hardware.info/?probe=d76cb40918) | Apr 23, 2024 |
| Lenovo    | ThinkPad X220 429135G       | [b681d0b406](https://bsd-hardware.info/?probe=b681d0b406) | Apr 23, 2024 |
| Apple     | MacBookAir6,2               | [fc810b38b1](https://bsd-hardware.info/?probe=fc810b38b1) | Apr 16, 2024 |
| ASUSTek   | VivoBook S14 X430UA         | [12764b3dba](https://bsd-hardware.info/?probe=12764b3dba) | Apr 14, 2024 |
| Dell      | Latitude 7490               | [38f6023f20](https://bsd-hardware.info/?probe=38f6023f20) | Apr 14, 2024 |
| Deciso    | NetBoard-A20                | [0b84a8b2a6](https://bsd-hardware.info/?probe=0b84a8b2a6) | Mar 31, 2024 |
| Apple     | MacBookPro11,1              | [58369a2ff3](https://bsd-hardware.info/?probe=58369a2ff3) | Mar 16, 2024 |
| Lenovo    | ThinkPad X220 429147U       | [0644799933](https://bsd-hardware.info/?probe=0644799933) | Mar 15, 2024 |
| Lenovo    | ThinkPad T420 4236JY2       | [0111e4442e](https://bsd-hardware.info/?probe=0111e4442e) | Mar 11, 2024 |
| Dell      | Precision 7520              | [bd40dd5305](https://bsd-hardware.info/?probe=bd40dd5305) | Feb 19, 2024 |
| Intel     | Jasper Lake Client Platf... | [6a041adf7a](https://bsd-hardware.info/?probe=6a041adf7a) | Feb 19, 2024 |
| Dell      | Latitude E6430              | [1f9f417c2f](https://bsd-hardware.info/?probe=1f9f417c2f) | Feb 18, 2024 |
| Lenovo    | ThinkPad T470 20HES0EV0A    | [05ecc99fe8](https://bsd-hardware.info/?probe=05ecc99fe8) | Feb 13, 2024 |
| Apple     | MacBookPro14,1              | [c8d68d0eec](https://bsd-hardware.info/?probe=c8d68d0eec) | Feb 01, 2024 |
| Acer      | TravelMate P645-SG          | [5765a3732f](https://bsd-hardware.info/?probe=5765a3732f) | Jan 31, 2024 |
| Acer      | TravelMate P645-SG          | [32dc9a4b1b](https://bsd-hardware.info/?probe=32dc9a4b1b) | Jan 31, 2024 |
| Lenovo    | ThinkBook 14 G6 IRL 21KG    | [a1fc491614](https://bsd-hardware.info/?probe=a1fc491614) | Jan 31, 2024 |
| Dell      | Precision 7510              | [b5d52d8750](https://bsd-hardware.info/?probe=b5d52d8750) | Jan 16, 2024 |
| Razer     | Blade 16 - RZ09-0483        | [d81973c8bc](https://bsd-hardware.info/?probe=d81973c8bc) | Jan 16, 2024 |
| Samsung   | N150/N210/N220              | [92c052e0d7](https://bsd-hardware.info/?probe=92c052e0d7) | Jan 14, 2024 |
| HP        | Pavilion g7                 | [25ccdb00f6](https://bsd-hardware.info/?probe=25ccdb00f6) | Jan 09, 2024 |
| ASUSTek   | VivoBook_ASUSLaptop X160... | [77d8cc2e7c](https://bsd-hardware.info/?probe=77d8cc2e7c) | Jan 02, 2024 |
| Dell      | Vostro V130                 | [44e78243c2](https://bsd-hardware.info/?probe=44e78243c2) | Dec 30, 2023 |
| Dell      | Latitude 7414               | [2d57c22982](https://bsd-hardware.info/?probe=2d57c22982) | Dec 08, 2023 |
| HP        | Pavilion g7                 | [4c1bc19902](https://bsd-hardware.info/?probe=4c1bc19902) | Dec 03, 2023 |
| Lenovo    | ThinkPad T470 20HES0EV0A    | [96562d6513](https://bsd-hardware.info/?probe=96562d6513) | Nov 20, 2023 |
| Lenovo    | ThinkPad T470 20HES0EV0A    | [5caaad73bd](https://bsd-hardware.info/?probe=5caaad73bd) | Nov 19, 2023 |
| Dell      | Latitude 5440               | [9daa44aacf](https://bsd-hardware.info/?probe=9daa44aacf) | Nov 18, 2023 |
| Lenovo    | ThinkPad X260 20F6006XUK    | [823bdd1b43](https://bsd-hardware.info/?probe=823bdd1b43) | Nov 10, 2023 |
| Dell      | Precision 7560              | [a0e5297849](https://bsd-hardware.info/?probe=a0e5297849) | Nov 09, 2023 |
| ASUSTek   | N73SV                       | [31fff3e92b](https://bsd-hardware.info/?probe=31fff3e92b) | Oct 21, 2023 |
| ASUSTek   | N73SV                       | [30726f25a0](https://bsd-hardware.info/?probe=30726f25a0) | Oct 21, 2023 |
| Lenovo    | ThinkPad X1 Carbon 3rd 2... | [0f3cd5aa25](https://bsd-hardware.info/?probe=0f3cd5aa25) | Oct 13, 2023 |
| Lenovo    | ThinkPad X260 20F6006XUK    | [25fecdaad5](https://bsd-hardware.info/?probe=25fecdaad5) | Oct 03, 2023 |
| ASUSTek   | ZenBook UX333FA_UX333FA     | [d331bd9a11](https://bsd-hardware.info/?probe=d331bd9a11) | Sep 08, 2023 |
| ASUSTek   | ASUS TUF Dash F15 FX517Z... | [cbde759aa2](https://bsd-hardware.info/?probe=cbde759aa2) | Sep 07, 2023 |
| ASUSTek   | ASUS TUF Dash F15 FX517Z... | [22ec8197cc](https://bsd-hardware.info/?probe=22ec8197cc) | Sep 07, 2023 |
| Unknown   | Unknown                     | [516b89740b](https://bsd-hardware.info/?probe=516b89740b) | Sep 06, 2023 |
| Unknown   | Unknown                     | [084127fd8b](https://bsd-hardware.info/?probe=084127fd8b) | Sep 06, 2023 |
| Lenovo    | ThinkPad X260 20F6006XUK    | [e4f0ac6bb9](https://bsd-hardware.info/?probe=e4f0ac6bb9) | Sep 03, 2023 |
| Lenovo    | ThinkPad X260 20F6006XUK    | [4bce25bd89](https://bsd-hardware.info/?probe=4bce25bd89) | Sep 03, 2023 |
| Deciso    | NetBoard-A20                | [bf4ed827a5](https://bsd-hardware.info/?probe=bf4ed827a5) | Aug 31, 2023 |
| Getac     | V110G2                      | [884803a6bd](https://bsd-hardware.info/?probe=884803a6bd) | Aug 25, 2023 |
| Lenovo    | ThinkPad T460p 20FXS06A1... | [378d093019](https://bsd-hardware.info/?probe=378d093019) | Aug 15, 2023 |
| Unknown   | Unknown                     | [4176afcb0d](https://bsd-hardware.info/?probe=4176afcb0d) | Aug 13, 2023 |
| Lenovo    | ThinkPad T60 1951CZ1        | [46766bc381](https://bsd-hardware.info/?probe=46766bc381) | Aug 11, 2023 |
| Notebook  | N7x0WU                      | [418b98798e](https://bsd-hardware.info/?probe=418b98798e) | Aug 09, 2023 |
| Notebook  | N7x0WU                      | [60d49b408a](https://bsd-hardware.info/?probe=60d49b408a) | Aug 09, 2023 |
| Chuwi     | CoreBook X                  | [2854f97c81](https://bsd-hardware.info/?probe=2854f97c81) | Aug 01, 2023 |
| Deciso    | NetBoard-A20                | [c4a85b9853](https://bsd-hardware.info/?probe=c4a85b9853) | Jul 18, 2023 |
| HP        | Stream Laptop 14-ds0xxx     | [81bbc73e72](https://bsd-hardware.info/?probe=81bbc73e72) | Jun 18, 2023 |
| Unknown   | Unknown                     | [422b9d51a7](https://bsd-hardware.info/?probe=422b9d51a7) | Jun 06, 2023 |
| Dell      | System XPS L702X            | [f56d7090f9](https://bsd-hardware.info/?probe=f56d7090f9) | May 28, 2023 |
| Deciso    | NetBoard-A20                | [0c5fd49340](https://bsd-hardware.info/?probe=0c5fd49340) | May 25, 2023 |
| Dell      | System XPS L702X            | [857016be75](https://bsd-hardware.info/?probe=857016be75) | May 24, 2023 |
| HP        | EliteBook 8570p             | [b5f17b6bf8](https://bsd-hardware.info/?probe=b5f17b6bf8) | May 23, 2023 |
| Deciso    | NetBoard-A20                | [313796fd3e](https://bsd-hardware.info/?probe=313796fd3e) | May 18, 2023 |
| Alienware | 17 R4                       | [df734c8e64](https://bsd-hardware.info/?probe=df734c8e64) | May 14, 2023 |
| Notebook  | N7x0WU                      | [7a646e185a](https://bsd-hardware.info/?probe=7a646e185a) | May 09, 2023 |
| Lenovo    | G500 20236                  | [e7387bfd6e](https://bsd-hardware.info/?probe=e7387bfd6e) | Apr 23, 2023 |
| Dell      | Latitude 7410               | [d5c047907d](https://bsd-hardware.info/?probe=d5c047907d) | Apr 19, 2023 |
| Deciso    | NetBoard-A20                | [33ca458105](https://bsd-hardware.info/?probe=33ca458105) | Mar 30, 2023 |
| Intel     | H81U                        | [af9a6469c9](https://bsd-hardware.info/?probe=af9a6469c9) | Mar 24, 2023 |
| Lenovo    | G500 20236                  | [55dc82af1c](https://bsd-hardware.info/?probe=55dc82af1c) | Mar 20, 2023 |
| Acer      | Swift SF314-56              | [94c7da1b3f](https://bsd-hardware.info/?probe=94c7da1b3f) | Mar 13, 2023 |
| Sony      | VGN-FZ19VN                  | [73809d943a](https://bsd-hardware.info/?probe=73809d943a) | Mar 13, 2023 |
| Dell      | Precision 7720              | [01f5f21b76](https://bsd-hardware.info/?probe=01f5f21b76) | Mar 12, 2023 |
| Intel     | Jasper Lake Client Platf... | [88de48013c](https://bsd-hardware.info/?probe=88de48013c) | Mar 10, 2023 |
| Intel     | Jasper Lake Client Platf... | [de93a79b7d](https://bsd-hardware.info/?probe=de93a79b7d) | Mar 10, 2023 |
| Lenovo    | ThinkPad T495 20NKS0HN1N    | [af190c38e9](https://bsd-hardware.info/?probe=af190c38e9) | Mar 10, 2023 |
| Lenovo    | ThinkPad T470 20HES0EV0A    | [dd6c3fa0f7](https://bsd-hardware.info/?probe=dd6c3fa0f7) | Mar 10, 2023 |
| Fujitsu   | CELSIUS H730                | [d2292bbcda](https://bsd-hardware.info/?probe=d2292bbcda) | Mar 10, 2023 |
| Fujitsu   | CELSIUS H730                | [223879138d](https://bsd-hardware.info/?probe=223879138d) | Mar 10, 2023 |
| HP        | EliteBook 2530p             | [e70d97f7d6](https://bsd-hardware.info/?probe=e70d97f7d6) | Mar 09, 2023 |
| Dell      | Latitude D620               | [8b3ad4e8b9](https://bsd-hardware.info/?probe=8b3ad4e8b9) | Mar 09, 2023 |
| Dell      | Latitude D620               | [d42a8ee079](https://bsd-hardware.info/?probe=d42a8ee079) | Mar 09, 2023 |
| Lenovo    | ThinkPad L14 Gen 3 21C5C... | [2ab690000c](https://bsd-hardware.info/?probe=2ab690000c) | Feb 25, 2023 |
| Lenovo    | ThinkPad L14 Gen 3 21C5C... | [ae0dc68ba6](https://bsd-hardware.info/?probe=ae0dc68ba6) | Feb 25, 2023 |
| Lenovo    | ThinkPad L14 Gen 3 21C5C... | [aef791947c](https://bsd-hardware.info/?probe=aef791947c) | Feb 23, 2023 |
| Lenovo    | ThinkPad X280 20KFCTO1WW    | [3dae7e3ebb](https://bsd-hardware.info/?probe=3dae7e3ebb) | Feb 23, 2023 |
| Lenovo    | ThinkPad L14 Gen 3 21C5C... | [6669622646](https://bsd-hardware.info/?probe=6669622646) | Feb 23, 2023 |
| Deciso    | NetBoard-A20                | [d23ae47425](https://bsd-hardware.info/?probe=d23ae47425) | Feb 23, 2023 |
| Deciso    | NetBoard-A20                | [ffc9e123b4](https://bsd-hardware.info/?probe=ffc9e123b4) | Feb 14, 2023 |
| Lenovo    | ThinkPad P15 Gen 2i 20YQ... | [78a978a8d4](https://bsd-hardware.info/?probe=78a978a8d4) | Feb 06, 2023 |
| Toshiba   | PORTEGE Z930                | [5462140da0](https://bsd-hardware.info/?probe=5462140da0) | Feb 05, 2023 |
| Lenovo    | G500 20236                  | [081d22fbe2](https://bsd-hardware.info/?probe=081d22fbe2) | Jan 24, 2023 |
| Lenovo    | G500 20236                  | [a35053ad38](https://bsd-hardware.info/?probe=a35053ad38) | Jan 24, 2023 |
| Toshiba   | PORTEGE Z930                | [476203ee86](https://bsd-hardware.info/?probe=476203ee86) | Jan 23, 2023 |
| Toshiba   | PORTEGE Z930                | [4af2cc1909](https://bsd-hardware.info/?probe=4af2cc1909) | Jan 23, 2023 |
| Dell      | Latitude E6400              | [dcc804a61f](https://bsd-hardware.info/?probe=dcc804a61f) | Jan 22, 2023 |
| Dell      | Latitude E6400              | [9dd8d0184f](https://bsd-hardware.info/?probe=9dd8d0184f) | Jan 22, 2023 |
| Dell      | Precision 5540              | [683769b797](https://bsd-hardware.info/?probe=683769b797) | Jan 19, 2023 |
| Lenovo    | ThinkPad T480 20L5CTO1WW    | [4014cc42ed](https://bsd-hardware.info/?probe=4014cc42ed) | Jan 08, 2023 |
| Deciso    | Netboard A20                | [3ff47d2ce0](https://bsd-hardware.info/?probe=3ff47d2ce0) | Jan 06, 2023 |
| Lenovo    | ThinkPad X280 20KFCTO1WW    | [a9b3805c0b](https://bsd-hardware.info/?probe=a9b3805c0b) | Jan 01, 2023 |
| Lenovo    | ThinkPad T440p 20AWS0Y40... | [ce2b20b3a9](https://bsd-hardware.info/?probe=ce2b20b3a9) | Dec 13, 2022 |
| Lenovo    | ThinkPad T440p 20AWS0Y40... | [7463e05c88](https://bsd-hardware.info/?probe=7463e05c88) | Dec 12, 2022 |
| Apple     | MacBookPro14,1              | [5234a39100](https://bsd-hardware.info/?probe=5234a39100) | Dec 10, 2022 |
| Apple     | MacBookPro14,1              | [ddeb9befdf](https://bsd-hardware.info/?probe=ddeb9befdf) | Dec 03, 2022 |
| Panasonic | CF-31-5                     | [7047afaaf4](https://bsd-hardware.info/?probe=7047afaaf4) | Nov 30, 2022 |
| Medion    | E15415                      | [e467080570](https://bsd-hardware.info/?probe=e467080570) | Nov 13, 2022 |
| Dell      | Precision M4500             | [ab63467f38](https://bsd-hardware.info/?probe=ab63467f38) | Nov 03, 2022 |
| Deciso    | NetBoard-A20                | [9c133326c9](https://bsd-hardware.info/?probe=9c133326c9) | Nov 03, 2022 |
| Intel     | H81U                        | [b0e1f80338](https://bsd-hardware.info/?probe=b0e1f80338) | Oct 24, 2022 |
| Dell      | Precision M4500             | [66ded228ea](https://bsd-hardware.info/?probe=66ded228ea) | Oct 20, 2022 |
| Intel     | H81U                        | [9b212d2264](https://bsd-hardware.info/?probe=9b212d2264) | Oct 13, 2022 |
| Lenovo    | ThinkPad T590 20N4CTO1WW    | [442a743538](https://bsd-hardware.info/?probe=442a743538) | Oct 08, 2022 |
| Toshiba   | NB300                       | [c18ae50101](https://bsd-hardware.info/?probe=c18ae50101) | Oct 03, 2022 |
| TUXEDO    | Aura 15 Gen1                | [e83d522905](https://bsd-hardware.info/?probe=e83d522905) | Oct 03, 2022 |
| Dell      | Precision M4500             | [6b987b43b1](https://bsd-hardware.info/?probe=6b987b43b1) | Oct 03, 2022 |
| Dell      | Inspiron 5515               | [dca437b993](https://bsd-hardware.info/?probe=dca437b993) | Jul 01, 2022 |
| ASUSTek   | K53TA                       | [6ce39c5e61](https://bsd-hardware.info/?probe=6ce39c5e61) | Jun 27, 2022 |
| HP        | EliteBook 8440p             | [25d5a77b59](https://bsd-hardware.info/?probe=25d5a77b59) | Jun 17, 2022 |
| Alienware | M18xR2                      | [6d55881f6a](https://bsd-hardware.info/?probe=6d55881f6a) | Jun 15, 2022 |
| Apple     | MacBook5,1                  | [8ba77d7208](https://bsd-hardware.info/?probe=8ba77d7208) | Jun 13, 2022 |
| Acer      | Aspire E5-571               | [4be2393c8d](https://bsd-hardware.info/?probe=4be2393c8d) | Jun 11, 2022 |
| Lenovo    | ThinkPad T14 Gen 1 20S0C... | [56111732fd](https://bsd-hardware.info/?probe=56111732fd) | Jun 07, 2022 |
| Lenovo    | ThinkPad T14 Gen 1 20S0C... | [aeec87e07f](https://bsd-hardware.info/?probe=aeec87e07f) | Jun 06, 2022 |
| Dell      | Latitude 7490               | [18215740d1](https://bsd-hardware.info/?probe=18215740d1) | Jun 05, 2022 |
| Lenovo    | ThinkPad T590 20N4CTO1WW    | [f3ad761457](https://bsd-hardware.info/?probe=f3ad761457) | Jun 04, 2022 |
| Dell      | Latitude 7490               | [22224f46f4](https://bsd-hardware.info/?probe=22224f46f4) | Jun 02, 2022 |
| Acer      | Aspire E5-576               | [138e9fdeb4](https://bsd-hardware.info/?probe=138e9fdeb4) | May 31, 2022 |
| TUXEDO    | Aura 15 Gen1                | [20814a930a](https://bsd-hardware.info/?probe=20814a930a) | May 18, 2022 |
| TUXEDO    | Aura 15 Gen1                | [115de395dd](https://bsd-hardware.info/?probe=115de395dd) | May 17, 2022 |
| TUXEDO    | InfinityBook13V3            | [fd081a3636](https://bsd-hardware.info/?probe=fd081a3636) | May 17, 2022 |
| Lenovo    | ThinkPad X250 20CLS4WV08    | [0419c52079](https://bsd-hardware.info/?probe=0419c52079) | May 11, 2022 |
| Intel     | H81U                        | [550699602e](https://bsd-hardware.info/?probe=550699602e) | May 11, 2022 |
| Intel     | H81U                        | [04646d1cc7](https://bsd-hardware.info/?probe=04646d1cc7) | May 05, 2022 |
| Dell      | Latitude 7490               | [0d5b872ec1](https://bsd-hardware.info/?probe=0d5b872ec1) | May 02, 2022 |
| Dell      | Latitude 7490               | [03c97fe4d9](https://bsd-hardware.info/?probe=03c97fe4d9) | May 02, 2022 |
| Dell      | Precision 7730              | [bdb3e3d4ce](https://bsd-hardware.info/?probe=bdb3e3d4ce) | Apr 30, 2022 |
| Dell      | Latitude 7490               | [1586880dd7](https://bsd-hardware.info/?probe=1586880dd7) | Apr 30, 2022 |
| Dell      | Studio 1555                 | [6da8f97bcd](https://bsd-hardware.info/?probe=6da8f97bcd) | Apr 22, 2022 |
| Dell      | Latitude E5450              | [ca5eb083f9](https://bsd-hardware.info/?probe=ca5eb083f9) | Apr 16, 2022 |
| Deciso    | Netboard A20                | [0829d5a85d](https://bsd-hardware.info/?probe=0829d5a85d) | Apr 06, 2022 |
| HP        | EliteBook 2530p             | [e5c8017afb](https://bsd-hardware.info/?probe=e5c8017afb) | Mar 12, 2022 |
| Lenovo    | Flex 2-15 20405             | [3b77055bd4](https://bsd-hardware.info/?probe=3b77055bd4) | Mar 07, 2022 |
| Dell      | Latitude E5440              | [b0314f9200](https://bsd-hardware.info/?probe=b0314f9200) | Feb 26, 2022 |
| Lenovo    | Legion 5 15ARH05 82B5       | [1a13b7bfd1](https://bsd-hardware.info/?probe=1a13b7bfd1) | Feb 16, 2022 |
| Lenovo    | Flex 2-15 20405             | [1e8904f4fc](https://bsd-hardware.info/?probe=1e8904f4fc) | Feb 15, 2022 |
| Lenovo    | Flex 2-15 20405             | [b77b926f9b](https://bsd-hardware.info/?probe=b77b926f9b) | Feb 13, 2022 |
| Deciso    | NetBoard-A20                | [4d8f19ba12](https://bsd-hardware.info/?probe=4d8f19ba12) | Feb 11, 2022 |
| Deciso    | NetBoard-A20                | [a6b7d2d5e8](https://bsd-hardware.info/?probe=a6b7d2d5e8) | Feb 06, 2022 |
| Deciso    | Netboard A20                | [8cd43fcfd1](https://bsd-hardware.info/?probe=8cd43fcfd1) | Feb 03, 2022 |
| ASUSTek   | 1015PEM                     | [efea0efb2b](https://bsd-hardware.info/?probe=efea0efb2b) | Jan 31, 2022 |
| Apple     | MacBook4,1                  | [e89404ebed](https://bsd-hardware.info/?probe=e89404ebed) | Jan 29, 2022 |
| Lenovo    | Legion Y540-15IRH 81SX      | [384d2f888b](https://bsd-hardware.info/?probe=384d2f888b) | Jan 18, 2022 |
| HP        | EliteBook 2530p             | [42eb986a58](https://bsd-hardware.info/?probe=42eb986a58) | Jan 11, 2022 |
| Dell      | Latitude E5450              | [a05fbe1c26](https://bsd-hardware.info/?probe=a05fbe1c26) | Jan 05, 2022 |
| Dell      | Latitude E5450              | [c2ef231757](https://bsd-hardware.info/?probe=c2ef231757) | Jan 04, 2022 |
| ASUSTek   | S550CA                      | [1263a5fb37](https://bsd-hardware.info/?probe=1263a5fb37) | Dec 29, 2021 |
| Samsung   | R720                        | [620195d4aa](https://bsd-hardware.info/?probe=620195d4aa) | Dec 20, 2021 |
| HP        | Compaq 15                   | [1e8b1ce39b](https://bsd-hardware.info/?probe=1e8b1ce39b) | Dec 20, 2021 |
| Lenovo    | G500 20236                  | [350def9eca](https://bsd-hardware.info/?probe=350def9eca) | Dec 19, 2021 |
| Lenovo    | ThinkPad T590 20N4CTO1WW    | [4147a5824d](https://bsd-hardware.info/?probe=4147a5824d) | Dec 16, 2021 |
| HP        | ProBook 650 G5              | [d4ffc24c6f](https://bsd-hardware.info/?probe=d4ffc24c6f) | Dec 15, 2021 |
| Lenovo    | ThinkPad T590 20N4CTO1WW    | [eb69e83fbf](https://bsd-hardware.info/?probe=eb69e83fbf) | Dec 09, 2021 |
| Google    | Terra                       | [9ba239a4a3](https://bsd-hardware.info/?probe=9ba239a4a3) | Oct 10, 2021 |
| Lenovo    | ThinkPad X220 4290W42       | [8be5183e21](https://bsd-hardware.info/?probe=8be5183e21) | Sep 25, 2021 |
| Lenovo    | ThinkPad T500 2056Y2Z       | [88b86ecf8b](https://bsd-hardware.info/?probe=88b86ecf8b) | Sep 25, 2021 |
| MSI       | P65 Creator 8RE             | [2684b5021c](https://bsd-hardware.info/?probe=2684b5021c) | Sep 18, 2021 |
| Lenovo    | ThinkPad E14 Gen 3 20Y7C... | [8611fbfd97](https://bsd-hardware.info/?probe=8611fbfd97) | Sep 14, 2021 |
| Apple     | MacBookPro8,2               | [5f78c3411f](https://bsd-hardware.info/?probe=5f78c3411f) | Sep 13, 2021 |
| Lenovo    | ThinkPad P14s Gen 1 20Y1... | [d028fc63d4](https://bsd-hardware.info/?probe=d028fc63d4) | Aug 29, 2021 |
| Lenovo    | ThinkPad P14s Gen 1 20Y1... | [76f004bd26](https://bsd-hardware.info/?probe=76f004bd26) | Aug 26, 2021 |
| Fujitsu   | LIFEBOOK NH570              | [51b5325c85](https://bsd-hardware.info/?probe=51b5325c85) | Aug 13, 2021 |
| Lenovo    | G500 20236                  | [d15eff8bcc](https://bsd-hardware.info/?probe=d15eff8bcc) | Jul 21, 2021 |
| Lenovo    | ThinkPad T420 42368A3       | [0a3b5c9c27](https://bsd-hardware.info/?probe=0a3b5c9c27) | Jul 12, 2021 |
| Notebook  | W510LU                      | [3d6de69bda](https://bsd-hardware.info/?probe=3d6de69bda) | Jul 02, 2021 |
| Lenovo    | G500 20236                  | [7ae63d4c6c](https://bsd-hardware.info/?probe=7ae63d4c6c) | Jun 27, 2021 |
| Dell      | Vostro 5481                 | [bb318fbc50](https://bsd-hardware.info/?probe=bb318fbc50) | Jun 26, 2021 |
| Lenovo    | ThinkPad T450s 20BWS0L60... | [6ea6f6ffe7](https://bsd-hardware.info/?probe=6ea6f6ffe7) | Jun 20, 2021 |
| Lenovo    | ThinkPad X250 20CLS7WY04    | [b60f4a19ee](https://bsd-hardware.info/?probe=b60f4a19ee) | Jun 06, 2021 |
| Apple     | MacBookPro8,2               | [193936b5ca](https://bsd-hardware.info/?probe=193936b5ca) | May 30, 2021 |
| Lenovo    | ThinkPad T450s 20BWS0L60... | [ac567bd12d](https://bsd-hardware.info/?probe=ac567bd12d) | May 28, 2021 |
| Lenovo    | ThinkPad A485 20MVS0FD00    | [2f1ba02130](https://bsd-hardware.info/?probe=2f1ba02130) | May 28, 2021 |
| Acer      | Aspire E5-571P              | [7c8c842fa7](https://bsd-hardware.info/?probe=7c8c842fa7) | May 24, 2021 |
| Lenovo    | ThinkPad T590 20N4CTO1WW    | [7c642e5e7d](https://bsd-hardware.info/?probe=7c642e5e7d) | Apr 30, 2021 |
| Lenovo    | ThinkPad T590 20N4CTO1WW    | [2e2e69cb9e](https://bsd-hardware.info/?probe=2e2e69cb9e) | Apr 29, 2021 |
| Lenovo    | ThinkPad T430 23495P8       | [2c985c22ef](https://bsd-hardware.info/?probe=2c985c22ef) | Apr 10, 2021 |
| Lenovo    | ThinkPad T420 4236NUG       | [4ff3fa22ff](https://bsd-hardware.info/?probe=4ff3fa22ff) | Apr 07, 2021 |
| Lenovo    | ThinkPad X220 4290EE8       | [f46976d85d](https://bsd-hardware.info/?probe=f46976d85d) | Mar 29, 2021 |
| Lenovo    | ThinkPad T490 20N20009FR    | [e1f691ac78](https://bsd-hardware.info/?probe=e1f691ac78) | Mar 29, 2021 |
| Lenovo    | ThinkPad T590 20N4CTO1WW    | [dec8aa97f5](https://bsd-hardware.info/?probe=dec8aa97f5) | Mar 26, 2021 |
| Lenovo    | ThinkPad T590 20N4CTO1WW    | [83ed58b4d0](https://bsd-hardware.info/?probe=83ed58b4d0) | Mar 26, 2021 |
| HP        | Pavilion Gaming Laptop 1... | [3cb0e979f8](https://bsd-hardware.info/?probe=3cb0e979f8) | Mar 26, 2021 |
| MSI       | MS-N033                     | [650f6a1b70](https://bsd-hardware.info/?probe=650f6a1b70) | Mar 21, 2021 |
| Dell      | Inspiron 7566               | [183ac9b791](https://bsd-hardware.info/?probe=183ac9b791) | Mar 17, 2021 |
| Dell      | Inspiron 7566               | [b4a35aa7b0](https://bsd-hardware.info/?probe=b4a35aa7b0) | Mar 17, 2021 |
| SECO      | UDOO x86                    | [f8310915b6](https://bsd-hardware.info/?probe=f8310915b6) | Mar 13, 2021 |
| HP        | EliteBook 820 G1            | [565343b334](https://bsd-hardware.info/?probe=565343b334) | Mar 13, 2021 |
| Lenovo    | ThinkPad T400 6475P1G       | [6a0907b5e8](https://bsd-hardware.info/?probe=6a0907b5e8) | Mar 06, 2021 |
| Clevo     | W240EU/W250EUQ/W270EUQ      | [17ed006376](https://bsd-hardware.info/?probe=17ed006376) | Mar 05, 2021 |
| HP        | EliteBook 820 G1            | [de98cd5952](https://bsd-hardware.info/?probe=de98cd5952) | Mar 04, 2021 |
| HP        | EliteBook 820 G1            | [03c5808adf](https://bsd-hardware.info/?probe=03c5808adf) | Mar 04, 2021 |
| Dell      | Latitude 5280               | [b84364959d](https://bsd-hardware.info/?probe=b84364959d) | Mar 04, 2021 |
| Lenovo    | IdeaPad S145-15API 81UT     | [1f226262cc](https://bsd-hardware.info/?probe=1f226262cc) | Mar 04, 2021 |
| ASUSTek   | X550LC                      | [e056f1c77c](https://bsd-hardware.info/?probe=e056f1c77c) | Mar 03, 2021 |
| Lenovo    | ThinkPad X280 20KFCTO1WW    | [9bdf9ecec8](https://bsd-hardware.info/?probe=9bdf9ecec8) | Feb 25, 2021 |
| Lenovo    | IdeaPad S145-15API 81UT     | [7def696a61](https://bsd-hardware.info/?probe=7def696a61) | Feb 22, 2021 |
| Lenovo    | IdeaPad S145-15API 81UT     | [0dc468c860](https://bsd-hardware.info/?probe=0dc468c860) | Feb 22, 2021 |
| ASUSTek   | X751LN                      | [fe7d72b06a](https://bsd-hardware.info/?probe=fe7d72b06a) | Feb 21, 2021 |
| ASUSTek   | X751LN                      | [a88cfd7fdd](https://bsd-hardware.info/?probe=a88cfd7fdd) | Feb 21, 2021 |
| Gigabyte  | P15FR7                      | [c65b4d297a](https://bsd-hardware.info/?probe=c65b4d297a) | Feb 21, 2021 |
| Lenovo    | ThinkPad X1 Carbon 4th 2... | [71cfece3a7](https://bsd-hardware.info/?probe=71cfece3a7) | Feb 18, 2021 |
| ASUSTek   | X75VC                       | [4a0982db2b](https://bsd-hardware.info/?probe=4a0982db2b) | Feb 15, 2021 |
| Clevo     | W240EU/W250EUQ/W270EUQ      | [4f646f53e9](https://bsd-hardware.info/?probe=4f646f53e9) | Feb 14, 2021 |
| Lenovo    | ThinkPad T580 20LAS2TG00    | [d5a1c088b3](https://bsd-hardware.info/?probe=d5a1c088b3) | Feb 13, 2021 |
| ASUSTek   | E200HA                      | [5781a8b561](https://bsd-hardware.info/?probe=5781a8b561) | Feb 12, 2021 |
| Lenovo    | G500 20236                  | [9b149fcd68](https://bsd-hardware.info/?probe=9b149fcd68) | Feb 12, 2021 |
| Dell      | Latitude 3410               | [465dd01c0d](https://bsd-hardware.info/?probe=465dd01c0d) | Feb 11, 2021 |
| Dell      | Latitude E6230              | [696e95fc08](https://bsd-hardware.info/?probe=696e95fc08) | Feb 10, 2021 |
| ASUSTek   | X550LC                      | [b3cf6f9142](https://bsd-hardware.info/?probe=b3cf6f9142) | Feb 09, 2021 |
| Lenovo    | IdeaPad S145-15API 81UT     | [7e5ce355e7](https://bsd-hardware.info/?probe=7e5ce355e7) | Feb 08, 2021 |
| Dell      | Latitude 5280               | [73fca8b178](https://bsd-hardware.info/?probe=73fca8b178) | Feb 08, 2021 |
| Lenovo    | ThinkPad T420 42368A3       | [5d7840d28e](https://bsd-hardware.info/?probe=5d7840d28e) | Feb 07, 2021 |
| Dell      | Latitude 3410               | [f81c1e338f](https://bsd-hardware.info/?probe=f81c1e338f) | Feb 07, 2021 |
| Lenovo    | ThinkPad P50 20EQS0U60C     | [d8cf9e878e](https://bsd-hardware.info/?probe=d8cf9e878e) | Jan 19, 2021 |
| ASUSTek   | X550LC                      | [f7c32488e9](https://bsd-hardware.info/?probe=f7c32488e9) | Jan 15, 2021 |
| Lenovo    | IdeaPad S145-15API 81UT     | [06cbb5cd5f](https://bsd-hardware.info/?probe=06cbb5cd5f) | Jan 15, 2021 |
| Dell      | Latitude 5280               | [c9bfb73262](https://bsd-hardware.info/?probe=c9bfb73262) | Jan 15, 2021 |
| Dell      | Latitude 5400               | [f242897c33](https://bsd-hardware.info/?probe=f242897c33) | Jan 13, 2021 |
| Dell      | Latitude 5490               | [3fba47b07f](https://bsd-hardware.info/?probe=3fba47b07f) | Jan 12, 2021 |
| ASUSTek   | N75SF                       | [7efb6557a2](https://bsd-hardware.info/?probe=7efb6557a2) | Jan 10, 2021 |
| Lenovo    | IdeaPad S145-15API 81UT     | [9ccf63e228](https://bsd-hardware.info/?probe=9ccf63e228) | Jan 09, 2021 |
| Lenovo    | IdeaPad S145-15API 81UT     | [e18df4623a](https://bsd-hardware.info/?probe=e18df4623a) | Jan 09, 2021 |
| Dell      | Latitude 5280               | [1ae6e6ee2d](https://bsd-hardware.info/?probe=1ae6e6ee2d) | Jan 05, 2021 |
| ASUSTek   | X102BA                      | [893b9111c6](https://bsd-hardware.info/?probe=893b9111c6) | Dec 27, 2020 |
| Apple     | PowerBook5,8                | [96f550a537](https://bsd-hardware.info/?probe=96f550a537) | Dec 24, 2020 |
| Clevo     | W240EU/W250EUQ/W270EUQ      | [2544123f79](https://bsd-hardware.info/?probe=2544123f79) | Dec 06, 2020 |
| Dell      | Latitude 5280               | [d1be72cc7e](https://bsd-hardware.info/?probe=d1be72cc7e) | Nov 21, 2020 |
| Dell      | Latitude 5280               | [fd4e8756b4](https://bsd-hardware.info/?probe=fd4e8756b4) | Nov 21, 2020 |
| Lenovo    | ThinkPad X1 Carbon 6th 2... | [9b6b24708e](https://bsd-hardware.info/?probe=9b6b24708e) | Nov 03, 2020 |
| Lenovo    | ThinkPad X1 Carbon 5th 2... | [7c8972f650](https://bsd-hardware.info/?probe=7c8972f650) | Oct 29, 2020 |
| Lenovo    | ThinkPad X230 2325AJ9       | [176044b6b8](https://bsd-hardware.info/?probe=176044b6b8) | Oct 21, 2020 |
| Lenovo    | ThinkPad S5-S540 20B3001... | [7e6cb69989](https://bsd-hardware.info/?probe=7e6cb69989) | Oct 21, 2020 |
| Lenovo    | ThinkPad W540 20BG001KUK    | [1b1327ac93](https://bsd-hardware.info/?probe=1b1327ac93) | Oct 21, 2020 |
| ASUSTek   | X102BA                      | [47e04c9378](https://bsd-hardware.info/?probe=47e04c9378) | Oct 19, 2020 |
| ASUSTek   | UX305FA                     | [4ecb1e9cd3](https://bsd-hardware.info/?probe=4ecb1e9cd3) | Sep 25, 2020 |
| Lenovo    | ThinkPad W540 20BG001KUK    | [986575086d](https://bsd-hardware.info/?probe=986575086d) | Sep 05, 2020 |
| Lenovo    | ThinkPad W540 20BG001KUK    | [f95de56bcd](https://bsd-hardware.info/?probe=f95de56bcd) | Sep 03, 2020 |
| TUXEDO    | InfinityBook13V3            | [d508fb472b](https://bsd-hardware.info/?probe=d508fb472b) | Aug 10, 2020 |
| Sony      | VGN-AR630E                  | [b417df513f](https://bsd-hardware.info/?probe=b417df513f) | Aug 07, 2020 |
| MSI       | P65 Creator 8RE             | [4031d186c2](https://bsd-hardware.info/?probe=4031d186c2) | Aug 06, 2020 |
| Lenovo    | ThinkPad X280 20KFCTO1WW    | [82de136ad3](https://bsd-hardware.info/?probe=82de136ad3) | Aug 06, 2020 |
| Lenovo    | ThinkPad W540 20BG001KUK    | [f3e2acbb66](https://bsd-hardware.info/?probe=f3e2acbb66) | Jul 31, 2020 |
| Lenovo    | ThinkPad W540 20BG001KUK    | [7ae8c247e9](https://bsd-hardware.info/?probe=7ae8c247e9) | Jul 31, 2020 |
| Lenovo    | ThinkPad T590 20N4CTO1WW    | [90e2b57f16](https://bsd-hardware.info/?probe=90e2b57f16) | Jun 14, 2020 |
| Lenovo    | ThinkPad T590 20N4CTO1WW    | [9ad34ffa59](https://bsd-hardware.info/?probe=9ad34ffa59) | Jun 14, 2020 |
| Dell      | Latitude E6420              | [7c8a68918a](https://bsd-hardware.info/?probe=7c8a68918a) | May 27, 2020 |
| Lenovo    | ThinkPad X1 Carbon 5th 2... | [bb2fcf8d92](https://bsd-hardware.info/?probe=bb2fcf8d92) | May 25, 2020 |
| HP        | ZBook 15                    | [3e9076f244](https://bsd-hardware.info/?probe=3e9076f244) | May 23, 2020 |
| HP        | ZBook 15                    | [23ec663f87](https://bsd-hardware.info/?probe=23ec663f87) | May 23, 2020 |
| Lenovo    | ThinkPad T495 20NJCTO1WW    | [fa71e5839a](https://bsd-hardware.info/?probe=fa71e5839a) | May 23, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| helloSystem 0.8.1    | 8         | 3.54%   |
| OpenBSD 6.8          | 7         | 3.1%    |
| helloSystem 0.4.0    | 7         | 3.1%    |
| FreeBSD 14.0-p6      | 7         | 3.1%    |
| FreeBSD 13.1         | 7         | 3.1%    |
| OpenBSD 7.1          | 6         | 2.65%   |
| OpenBSD 7.0          | 6         | 2.65%   |
| NomadBSD 1.3.2       | 6         | 2.65%   |
| helloSystem 0.7.0    | 6         | 2.65%   |
| NomadBSD 20221130    | 5         | 2.21%   |
| GhostBSD 20.04.02    | 5         | 2.21%   |
| FreeBSD 13.1-p7      | 5         | 2.21%   |
| FreeBSD 13.0         | 5         | 2.21%   |
| NomadBSD 1.4         | 4         | 1.77%   |
| helloSystem 0.8.0    | 4         | 1.77%   |
| FreeBSD 12.2-p2      | 4         | 1.77%   |
| OpenBSD 7.2          | 3         | 1.33%   |
| OpenBSD 6.9          | 3         | 1.33%   |
| FreeBSD 14.1-p6      | 3         | 1.33%   |
| FreeBSD 14.1         | 3         | 1.33%   |
| FreeBSD 13.2         | 3         | 1.33%   |
| FreeBSD 13.1-p3      | 3         | 1.33%   |
| FreeBSD 13.0-STABLE  | 3         | 1.33%   |
| FreeBSD 12.2-p4      | 3         | 1.33%   |
| FreeBSD 12.2         | 3         | 1.33%   |
| OPNsense 24.7.8      | 2         | 0.88%   |
| OPNsense 23.1.11     | 2         | 0.88%   |
| OPNsense 22.7.6      | 2         | 0.88%   |
| OPNsense 22.10       | 2         | 0.88%   |
| OPNsense 22.1        | 2         | 0.88%   |
| OpenBSD 6.7          | 2         | 0.88%   |
| NetBSD 10.0_RC3      | 2         | 0.88%   |
| helloSystem 0.9.0    | 2         | 0.88%   |
| GhostBSD 24.10.1     | 2         | 0.88%   |
| GhostBSD 24.01.1     | 2         | 0.88%   |
| GhostBSD 22.01.12    | 2         | 0.88%   |
| FreeBSD 14.0-RC4     | 2         | 0.88%   |
| FreeBSD 14.0-CURRENT | 2         | 0.88%   |
| FreeBSD 13.2-p3      | 2         | 0.88%   |
| FreeBSD 13.2-p2      | 2         | 0.88%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 83        | 44.39%  |
| helloSystem | 25        | 13.37%  |
| OpenBSD     | 24        | 12.83%  |
| OPNsense    | 18        | 9.63%   |
| NomadBSD    | 17        | 9.09%   |
| GhostBSD    | 12        | 6.42%   |
| NetBSD      | 6         | 3.21%   |
| HardenedBSD | 1         | 0.53%   |
| FuryBSD     | 1         | 0.53%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| amd64  | 168       | 97.11%  |
| i386   | 4         | 2.31%   |
| macppc | 1         | 0.58%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 35        | 18.04%  |
| XFCE         | 33        | 17.01%  |
| Console      | 26        | 13.4%   |
| KDE5         | 20        | 10.31%  |
| fvwm         | 16        | 8.25%   |
| Openbox      | 15        | 7.73%   |
| MATE         | 14        | 7.22%   |
| GNOME        | 11        | 5.67%   |
| TWM          | 8         | 4.12%   |
| i3           | 6         | 3.09%   |
| xinitrc      | 3         | 1.55%   |
| AwesomeWM    | 3         | 1.55%   |
| X-Cinnamon   | 1         | 0.52%   |
| sway         | 1         | 0.52%   |
| LXDE         | 1         | 0.52%   |
| iwm          | 1         | 0.52%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 147       | 83.52%  |
| Console | 28        | 15.91%  |
| Wayland | 1         | 0.57%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 69        | 37.3%   |
| SLiM    | 57        | 30.81%  |
| SDDM    | 25        | 13.51%  |
| LightDM | 17        | 9.19%   |
| XDM     | 12        | 6.49%   |
| GDM     | 5         | 2.7%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| Unknown         | 57        | 30.48%  |
| fr_FR           | 48        | 25.67%  |
| C               | 37        | 19.79%  |
| en_US           | 35        | 18.72%  |
| de_DE           | 3         | 1.6%    |
| fr              | 2         | 1.07%   |
| en_US.ISO8859-1 | 2         | 1.07%   |
| en_GB           | 2         | 1.07%   |
| en              | 1         | 0.53%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 139       | 78.98%  |
| BIOS | 37        | 21.02%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 96        | 53.04%  |
| Ufs    | 50        | 27.62%  |
| Ffs    | 24        | 13.26%  |
| Cd9660 | 11        | 6.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 147       | 83.52%  |
| MBR     | 26        | 14.77%  |
| Unknown | 2         | 1.14%   |
| BSD     | 1         | 0.57%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 50        | 28.9%   |
| Dell                | 33        | 19.08%  |
| ASUSTek Computer    | 15        | 8.67%   |
| Hewlett-Packard     | 11        | 6.36%   |
| Apple               | 11        | 6.36%   |
| Deciso              | 7         | 4.05%   |
| Intel               | 5         | 2.89%   |
| Acer                | 5         | 2.89%   |
| TUXEDO              | 3         | 1.73%   |
| Toshiba             | 3         | 1.73%   |
| Sony                | 3         | 1.73%   |
| Notebook            | 3         | 1.73%   |
| Alienware           | 3         | 1.73%   |
| Unknown             | 3         | 1.73%   |
| Samsung Electronics | 2         | 1.16%   |
| MSI                 | 2         | 1.16%   |
| HUAWEI              | 2         | 1.16%   |
| Gigabyte Technology | 2         | 1.16%   |
| Fujitsu             | 2         | 1.16%   |
| SECO                | 1         | 0.58%   |
| Razer               | 1         | 0.58%   |
| Panasonic           | 1         | 0.58%   |
| Medion              | 1         | 0.58%   |
| Google              | 1         | 0.58%   |
| Getac               | 1         | 0.58%   |
| Clevo               | 1         | 0.58%   |
| Chuwi               | 1         | 0.58%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Intel H81U                               | 4         | 2.31%   |
| Deciso NetBoard-A20                      | 4         | 2.31%   |
| Apple MacBookAir6,2                      | 4         | 2.31%   |
| Dell Precision M4500                     | 3         | 1.73%   |
| Deciso Netboard A20                      | 3         | 1.73%   |
| Unknown                                  | 3         | 1.73%   |
| TUXEDO InfinityBook13V3                  | 2         | 1.16%   |
| Toshiba PORTEGE Z930                     | 2         | 1.16%   |
| HUAWEI KPL-W0X                           | 2         | 1.16%   |
| Dell Precision 7730                      | 2         | 1.16%   |
| Dell Latitude 3410                       | 2         | 1.16%   |
| Apple MacBookPro14,1                     | 2         | 1.16%   |
| TUXEDO Aura 15 Gen1                      | 1         | 0.58%   |
| Toshiba NB300                            | 1         | 0.58%   |
| Sony VGN-FZ19VN                          | 1         | 0.58%   |
| Sony VGN-AR630E                          | 1         | 0.58%   |
| Sony SVS1312J3EW                         | 1         | 0.58%   |
| SECO UDOO x86                            | 1         | 0.58%   |
| Samsung R720                             | 1         | 0.58%   |
| Samsung N150/N210/N220                   | 1         | 0.58%   |
| Razer Blade 16 - RZ09-0483               | 1         | 0.58%   |
| Panasonic CF-31-5                        | 1         | 0.58%   |
| Notebook W740SU                          | 1         | 0.58%   |
| Notebook W510LU                          | 1         | 0.58%   |
| Notebook N7x0WU                          | 1         | 0.58%   |
| MSI P65 Creator 8RE                      | 1         | 0.58%   |
| MSI MS-N033                              | 1         | 0.58%   |
| Medion E15415                            | 1         | 0.58%   |
| Lenovo ThinkPad X280 20KFCTO1WW          | 1         | 0.58%   |
| Lenovo ThinkPad X270 W10DG 20K5S1P100    | 1         | 0.58%   |
| Lenovo ThinkPad X260 20F6006XUK          | 1         | 0.58%   |
| Lenovo ThinkPad X250 20CLS7WY04          | 1         | 0.58%   |
| Lenovo ThinkPad X250 20CLS4WV08          | 1         | 0.58%   |
| Lenovo ThinkPad X230 2325AJ9             | 1         | 0.58%   |
| Lenovo ThinkPad X220 429147U             | 1         | 0.58%   |
| Lenovo ThinkPad X220 429135G             | 1         | 0.58%   |
| Lenovo ThinkPad X220 4290W42             | 1         | 0.58%   |
| Lenovo ThinkPad X220 4290EE8             | 1         | 0.58%   |
| Lenovo ThinkPad X1 Carbon 6th 20KHS1TG00 | 1         | 0.58%   |
| Lenovo ThinkPad X1 Carbon 5th 20HRCTO1WW | 1         | 0.58%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 42        | 24.28%  |
| Dell Latitude           | 16        | 9.25%   |
| Dell Precision          | 11        | 6.36%   |
| HP EliteBook            | 5         | 2.89%   |
| Intel H81U              | 4         | 2.31%   |
| Deciso NetBoard-A20     | 4         | 2.31%   |
| Apple MacBookAir6       | 4         | 2.31%   |
| Lenovo Legion           | 3         | 1.73%   |
| Deciso Netboard         | 3         | 1.73%   |
| Acer Aspire             | 3         | 1.73%   |
| Unknown                 | 3         | 1.73%   |
| TUXEDO InfinityBook13V3 | 2         | 1.16%   |
| Toshiba PORTEGE         | 2         | 1.16%   |
| Lenovo ThinkBook        | 2         | 1.16%   |
| HUAWEI KPL-W0X          | 2         | 1.16%   |
| HP Pavilion             | 2         | 1.16%   |
| Dell Vostro             | 2         | 1.16%   |
| Dell Inspiron           | 2         | 1.16%   |
| ASUS VivoBook           | 2         | 1.16%   |
| Apple MacBookPro14      | 2         | 1.16%   |
| TUXEDO Aura             | 1         | 0.58%   |
| Toshiba NB300           | 1         | 0.58%   |
| Sony VGN-FZ19VN         | 1         | 0.58%   |
| Sony VGN-AR630E         | 1         | 0.58%   |
| Sony SVS1312J3EW        | 1         | 0.58%   |
| SECO UDOO               | 1         | 0.58%   |
| Samsung R720            | 1         | 0.58%   |
| Samsung N150            | 1         | 0.58%   |
| Razer Blade             | 1         | 0.58%   |
| Panasonic CF-31-5       | 1         | 0.58%   |
| Notebook W740SU         | 1         | 0.58%   |
| Notebook W510LU         | 1         | 0.58%   |
| Notebook N7x0WU         | 1         | 0.58%   |
| MSI P65                 | 1         | 0.58%   |
| MSI MS-N033             | 1         | 0.58%   |
| Medion E15415           | 1         | 0.58%   |
| Lenovo IdeaPad          | 1         | 0.58%   |
| Lenovo G500             | 1         | 0.58%   |
| Lenovo Flex             | 1         | 0.58%   |
| Intel Jasper            | 1         | 0.58%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 22        | 12.72%  |
| 2020    | 17        | 9.83%   |
| 2021    | 14        | 8.09%   |
| 2022    | 13        | 7.51%   |
| 2018    | 13        | 7.51%   |
| 2013    | 13        | 7.51%   |
| 2011    | 13        | 7.51%   |
| 2015    | 11        | 6.36%   |
| 2016    | 9         | 5.2%    |
| 2010    | 9         | 5.2%    |
| 2014    | 8         | 4.62%   |
| 2024    | 6         | 3.47%   |
| 2023    | 6         | 3.47%   |
| 2017    | 5         | 2.89%   |
| 2012    | 4         | 2.31%   |
| 2009    | 3         | 1.73%   |
| 2008    | 3         | 1.73%   |
| 2007    | 2         | 1.16%   |
| 2006    | 1         | 0.58%   |
| Unknown | 1         | 0.58%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 173       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 171       | 98.84%  |
| Yes  | 2         | 1.16%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 58        | 32.77%  |
| 16.01-24.0  | 44        | 24.86%  |
| 4.01-8.0    | 29        | 16.38%  |
| 32.01-64.0  | 19        | 10.73%  |
| 2.01-3.0    | 9         | 5.08%   |
| 64.01-256.0 | 6         | 3.39%   |
| 3.01-4.0    | 5         | 2.82%   |
| 24.01-32.0  | 4         | 2.26%   |
| 1.01-2.0    | 2         | 1.13%   |
| 0.51-1.0    | 1         | 0.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 89        | 48.9%   |
| 0.51-1.0   | 51        | 28.02%  |
| 1.01-2.0   | 24        | 13.19%  |
| 2.01-3.0   | 7         | 3.85%   |
| Unknown    | 6         | 3.3%    |
| 8.01-16.0  | 4         | 2.2%    |
| 32.01-64.0 | 1         | 0.55%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 113       | 62.78%  |
| 2      | 31        | 17.22%  |
| 0      | 29        | 16.11%  |
| 3      | 5         | 2.78%   |
| 4      | 2         | 1.11%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 136       | 77.27%  |
| Yes       | 40        | 22.73%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 147       | 84.48%  |
| No        | 27        | 15.52%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 158       | 91.33%  |
| No        | 15        | 8.67%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 113       | 64.2%   |
| No        | 63        | 35.8%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| France  | 173       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Paris                    | 31        | 15.42%  |
| Franconville             | 7         | 3.48%   |
| Colombes                 | 7         | 3.48%   |
| Bordeaux                 | 6         | 2.99%   |
| Urcuit                   | 4         | 1.99%   |
| Melun                    | 4         | 1.99%   |
| Mâcon                   | 4         | 1.99%   |
| Noyon                    | 3         | 1.49%   |
| Noisy-le-Grand           | 3         | 1.49%   |
| Marcq-en-Baroeul         | 3         | 1.49%   |
| Fontenay-sous-Bois       | 3         | 1.49%   |
| Carry-le-Rouet           | 3         | 1.49%   |
| Stiring-Wendel           | 2         | 1%      |
| Saint-Raphaël           | 2         | 1%      |
| Saint-Germain-en-Laye    | 2         | 1%      |
| Saint-Denis              | 2         | 1%      |
| Rosny-sous-Bois          | 2         | 1%      |
| Rennes                   | 2         | 1%      |
| Le Pecq                  | 2         | 1%      |
| Dijon                    | 2         | 1%      |
| Courbevoie               | 2         | 1%      |
| Colmar                   | 2         | 1%      |
| Asnieres-sur-Seine       | 2         | 1%      |
| Argenteuil               | 2         | 1%      |
| Villeneuve-Saint-Georges | 1         | 0.5%    |
| Villemomble              | 1         | 0.5%    |
| Villejuif                | 1         | 0.5%    |
| Villefrancoeur           | 1         | 0.5%    |
| Villefontaine            | 1         | 0.5%    |
| Vertou                   | 1         | 0.5%    |
| Tulle                    | 1         | 0.5%    |
| Tournon-sur-RhÃ´ne     | 1         | 0.5%    |
| Toulouse                 | 1         | 0.5%    |
| St-Malo                  | 1         | 0.5%    |
| Soisy-sur-Seine          | 1         | 0.5%    |
| Sartrouville             | 1         | 0.5%    |
| Sarcelles                | 1         | 0.5%    |
| Samatan                  | 1         | 0.5%    |
| Sallanches               | 1         | 0.5%    |
| Saint-Saulge             | 1         | 0.5%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 31        | 43     | 17.32%  |
| Crucial             | 17        | 21     | 9.5%    |
| Toshiba             | 16        | 26     | 8.94%   |
| Seagate             | 15        | 29     | 8.38%   |
| WDC                 | 11        | 18     | 6.15%   |
| Transcend           | 11        | 18     | 6.15%   |
| SanDisk             | 11        | 14     | 6.15%   |
| Kingston            | 11        | 14     | 6.15%   |
| Micron Technology   | 7         | 12     | 3.91%   |
| China               | 7         | 7      | 3.91%   |
| Intel               | 6         | 9      | 3.35%   |
| NVMe                | 5         | 5      | 2.79%   |
| HGST                | 5         | 8      | 2.79%   |
| Apple               | 5         | 6      | 2.79%   |
| SK hynix            | 4         | 4      | 2.23%   |
| Fujitsu             | 3         | 4      | 1.68%   |
| Phison              | 2         | 2      | 1.12%   |
| Hitachi             | 2         | 2      | 1.12%   |
| SPCC                | 1         | 1      | 0.56%   |
| Patriot             | 1         | 1      | 0.56%   |
| Lexar               | 1         | 2      | 0.56%   |
| LDLC F6+            | 1         | 1      | 0.56%   |
| Integral            | 1         | 1      | 0.56%   |
| Generic             | 1         | 1      | 0.56%   |
| FORESEE             | 1         | 2      | 0.56%   |
| EMTEC               | 1         | 1      | 0.56%   |
| BHT                 | 1         | 1      | 0.56%   |
| AirDisk             | 1         | 1      | 0.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Transcend TS256GMTS952T2 256GB       | 5         | 2.7%    |
| China MSATA 32GB SSD                 | 4         | 2.16%   |
| Apple SSD SD0128F 121GB              | 4         | 2.16%   |
| Seagate ST1000LM035-1RK172 1TB       | 3         | 1.62%   |
| Kingston SA400S37240G 240GB          | 3         | 1.62%   |
| Crucial CT1000P1SSD8 1TB             | 3         | 1.62%   |
| WDC WD3200BPVT-80JJ5T0 320GB         | 2         | 1.08%   |
| Transcend TS256GMTS430S 256GB        | 2         | 1.08%   |
| Toshiba MK2556GSY 250GB              | 2         | 1.08%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB  | 2         | 1.08%   |
| Samsung SSD 970 EVO Plus 2TB         | 2         | 1.08%   |
| Samsung SSD 950 PRO 512GB            | 2         | 1.08%   |
| Samsung SSD 860 EVO M.2 1TB          | 2         | 1.08%   |
| Samsung SSD 860 EVO 250GB            | 2         | 1.08%   |
| Samsung SSD 850 EVO 250GB            | 2         | 1.08%   |
| NVMe WDC PC SN720 SDA 512GB          | 2         | 1.08%   |
| Intel SSDPEKKF256G8L 256GB           | 2         | 1.08%   |
| HGST HTS725050A7E630 500GB           | 2         | 1.08%   |
| HGST HTS721010A9E630 1TB             | 2         | 1.08%   |
| Crucial CT960M500SSD1 960GB          | 2         | 1.08%   |
| Crucial CT250MX500SSD1 250GB         | 2         | 1.08%   |
| Crucial CT1050MX300SSD1 1TB          | 2         | 1.08%   |
| Crucial CT1000MX500SSD1 1TB          | 2         | 1.08%   |
| China SH00M240GB                     | 2         | 1.08%   |
| WDC WDS240G2G0B-00EPW0 240GB         | 1         | 0.54%   |
| WDC WDS240G2G0A-00JH30 240GB         | 1         | 0.54%   |
| WDC WDS120G2G0B-00EPW0 120GB         | 1         | 0.54%   |
| WDC WD3200BEVT-75ZCT2 320GB          | 1         | 0.54%   |
| WDC WD20SMZW-11JW8S1 2TB             | 1         | 0.54%   |
| WDC WD20SDRW-11VUUS0 2TB             | 1         | 0.54%   |
| WDC WD10SPZX-21Z10T0 1TB             | 1         | 0.54%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.54%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 1         | 0.54%   |
| WDC PC SN520 SDAPMUW-128G-1101 128GB | 1         | 0.54%   |
| Transcend TS256GMTS800 256GB         | 1         | 0.54%   |
| Transcend TS256GMTE712A 256GB        | 1         | 0.54%   |
| Transcend TS256GMTE710T 256GB        | 1         | 0.54%   |
| Transcend TS128GMTS400 128GB         | 1         | 0.54%   |
| Toshiba THNSNJ256GCSY 256GB          | 1         | 0.54%   |
| Toshiba THNSNF128GMCS 128GB          | 1         | 0.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 29     | 29.41%  |
| Toshiba             | 11        | 16     | 21.57%  |
| WDC                 | 6         | 8      | 11.76%  |
| NVMe                | 5         | 5      | 9.8%    |
| HGST                | 5         | 8      | 9.8%    |
| Fujitsu             | 3         | 4      | 5.88%   |
| Hitachi             | 2         | 2      | 3.92%   |
| Samsung Electronics | 1         | 1      | 1.96%   |
| Lexar               | 1         | 2      | 1.96%   |
| LDLC F6+            | 1         | 1      | 1.96%   |
| Generic             | 1         | 1      | 1.96%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 19        | 25     | 21.11%  |
| Crucial             | 12        | 12     | 13.33%  |
| SanDisk             | 11        | 14     | 12.22%  |
| Transcend           | 9         | 16     | 10%     |
| Kingston            | 9         | 11     | 10%     |
| China               | 7         | 7      | 7.78%   |
| Apple               | 5         | 6      | 5.56%   |
| Toshiba             | 4         | 8      | 4.44%   |
| WDC                 | 3         | 6      | 3.33%   |
| Micron Technology   | 3         | 8      | 3.33%   |
| SPCC                | 1         | 1      | 1.11%   |
| SK hynix            | 1         | 1      | 1.11%   |
| Patriot             | 1         | 1      | 1.11%   |
| Intel               | 1         | 1      | 1.11%   |
| Integral            | 1         | 1      | 1.11%   |
| FORESEE             | 1         | 2      | 1.11%   |
| EMTEC               | 1         | 1      | 1.11%   |
| BHT                 | 1         | 1      | 1.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 81        | 122    | 49.09%  |
| HDD  | 48        | 77     | 29.09%  |
| NVMe | 36        | 55     | 21.82%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 122       | 199    | 77.22%  |
| NVMe | 36        | 55     | 22.78%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 95        | 148    | 70.9%   |
| 0.51-1.0   | 33        | 43     | 24.63%  |
| 1.01-2.0   | 6         | 8      | 4.48%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 66        | 35.87%  |
| 1-20       | 32        | 17.39%  |
| 251-500    | 28        | 15.22%  |
| 501-1000   | 21        | 11.41%  |
| 21-50      | 20        | 10.87%  |
| 51-100     | 10        | 5.43%   |
| 1001-2000  | 6         | 3.26%   |
| Unknown    | 1         | 0.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 141       | 78.33%  |
| 21-50    | 18        | 10%     |
| 101-250  | 13        | 7.22%   |
| 51-100   | 5         | 2.78%   |
| 501-1000 | 2         | 1.11%   |
| Unknown  | 1         | 0.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                             | Notebooks | Drives | Percent |
|---------------------------------------------------|-----------|--------|---------|
| WDC WD3200BPVT-80JJ5T0 320GB                      | 2         | 2      | 9.52%   |
| WDC WDS240G2G0A-00JH30 240GB                      | 1         | 1      | 4.76%   |
| WDC WD10JPVX-22JC3T0 1TB                          | 1         | 1      | 4.76%   |
| Toshiba MQ01ABD075 752GB                          | 1         | 1      | 4.76%   |
| Toshiba MQ01ABD050 500GB                          | 1         | 2      | 4.76%   |
| Toshiba MK3261GSY 320GB                           | 1         | 1      | 4.76%   |
| Toshiba MK1629GSGF 160GB                          | 1         | 3      | 4.76%   |
| Seagate ST9320423AS 320GB                         | 1         | 3      | 4.76%   |
| Seagate ST9320325AS 320GB                         | 1         | 1      | 4.76%   |
| Seagate ST320LT012-9WS14C 320GB                   | 1         | 7      | 4.76%   |
| Seagate ST320LT007-9ZV142 320GB                   | 1         | 1      | 4.76%   |
| Seagate ST3160212AS 160GB                         | 1         | 1      | 4.76%   |
| Seagate ST1000LM014-1EJ164 1TB                    | 1         | 1      | 4.76%   |
| SanDisk SD7UB3Q256G1001 256GB                     | 1         | 1      | 4.76%   |
| Samsung Electronics SSD 840 EVO 500GB             | 1         | 2      | 4.76%   |
| Micron Technology C400 RealSSD 2.5-inch 7mm 256GB | 1         | 1      | 4.76%   |
| Kingston SUV500MS480G 480GB                       | 1         | 1      | 4.76%   |
| HGST HTS725050A7E630 500GB                        | 1         | 1      | 4.76%   |
| HGST HTS545050A7E660 500GB                        | 1         | 2      | 4.76%   |
| Crucial CT525MX300SSD1 528GB                      | 1         | 1      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 14     | 28.57%  |
| WDC                 | 4         | 4      | 19.05%  |
| Toshiba             | 4         | 7      | 19.05%  |
| HGST                | 2         | 3      | 9.52%   |
| SanDisk             | 1         | 1      | 4.76%   |
| Samsung Electronics | 1         | 2      | 4.76%   |
| Micron Technology   | 1         | 1      | 4.76%   |
| Kingston            | 1         | 1      | 4.76%   |
| Crucial             | 1         | 1      | 4.76%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 14     | 40%     |
| Toshiba | 4         | 7      | 26.67%  |
| WDC     | 3         | 3      | 20%     |
| HGST    | 2         | 3      | 13.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 27     | 70%     |
| SSD  | 6         | 7      | 30%     |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 127       | 213    | 83.01%  |
| Malfunc  | 20        | 34     | 13.07%  |
| Detected | 6         | 7      | 3.92%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 119       | 60.41%  |
| Samsung Electronics            | 18        | 9.14%   |
| AMD                            | 16        | 8.12%   |
| SanDisk                        | 7         | 3.55%   |
| Micron/Crucial Technology      | 7         | 3.55%   |
| SK hynix                       | 5         | 2.54%   |
| Phison Electronics             | 4         | 2.03%   |
| Micron Technology              | 4         | 2.03%   |
| Marvell Technology Group       | 4         | 2.03%   |
| Transcend                      | 3         | 1.52%   |
| Toshiba                        | 2         | 1.02%   |
| KIOXIA                         | 2         | 1.02%   |
| Kingston Technology Company    | 2         | 1.02%   |
| Solid State Storage Technology | 1         | 0.51%   |
| Realtek Semiconductor          | 1         | 0.51%   |
| Nvidia                         | 1         | 0.51%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.51%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 16        | 7.62%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 12        | 5.71%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 12        | 5.71%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 12        | 5.71%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 11        | 5.24%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 10        | 4.76%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 9         | 4.29%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 7         | 3.33%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 6         | 2.86%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 5         | 2.38%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5         | 2.38%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 5         | 2.38%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 4         | 1.9%    |
| Marvell Group 88SS9183 PCIe SSD Controller                                       | 4         | 1.9%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 1.43%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                        | 3         | 1.43%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                 | 3         | 1.43%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 1.43%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 1.43%   |
| Intel Comet Lake RAID Controller                                                 | 3         | 1.43%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 1.43%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 1.43%   |
| Transcend NVMe PCIe SSD 220S/240S/MTE710T                                        | 2         | 0.95%   |
| SK hynix BC511 NVMe SSD                                                          | 2         | 0.95%   |
| Sandisk WD PC SN740 NVMe SSD 512GB (DRAM-less)                                   | 2         | 0.95%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 2         | 0.95%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                      | 2         | 0.95%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 2         | 0.95%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 2         | 0.95%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                             | 2         | 0.95%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 2         | 0.95%   |
| Micron 2200S NVMe SSD [Cassandra]                                                | 2         | 0.95%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 2         | 0.95%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 0.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 0.95%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 0.95%   |
| Transcend NVMe PCIe SSD 110S/112S/120S/MTE300S/MTE400S/MTE652T2 (DRAM-less)      | 1         | 0.48%   |
| Toshiba XG6 NVMe SSD Controller                                                  | 1         | 0.48%   |
| Toshiba XG4 NVMe SSD Controller                                                  | 1         | 0.48%   |
| Solid State Storage CA6-8D512 NVMe SSD M.2                                       | 1         | 0.48%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 120       | 60.61%  |
| NVMe | 55        | 27.78%  |
| RAID | 14        | 7.07%   |
| IDE  | 9         | 4.55%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 149       | 85.63%  |
| AMD     | 24        | 13.79%  |
| PowerPC | 1         | 0.57%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-5300U CPU @ 2.30GHz             | 5         | 2.87%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 5         | 2.87%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 2.3%    |
| Intel Core i5-4250U CPU @ 1.30GHz             | 4         | 2.3%    |
| AMD EPYC 3201 8-Core Processor                | 4         | 2.3%    |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 1.72%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 1.72%   |
| Intel Core i5 CPU M 560 @ 2.67GH              | 3         | 1.72%   |
| Intel Core i3-4010U CPU @ 1.70GHz             | 3         | 1.72%   |
| AMD EPYC 3101 4-Core Processor                | 3         | 1.72%   |
| Intel Core i9-14900HX                         | 2         | 1.15%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1.15%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.15%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 1.15%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 1.15%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 1.15%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 2         | 1.15%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 2         | 1.15%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.15%   |
| Intel Core i5-7360U CPU @ 2.30GHz             | 2         | 1.15%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 2         | 1.15%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 1.15%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.15%   |
| Intel Core i5-3437U CPU @ 1.90GHz             | 2         | 1.15%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 1.15%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 2         | 1.15%   |
| Intel Core i3-4025U CPU @ 1.90GHz             | 2         | 1.15%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 1.15%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 1.15%   |
| Intel Celeron CPU N3160 @ 1.60GHz             | 2         | 1.15%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 1.15%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 1.15%   |
| PowerPC 7447A (Revision 0x105)                | 1         | 0.57%   |
| Intel Xeon W-11855M CPU @ 3.20GHz             | 1         | 0.57%   |
| Intel Xeon E-2176M CPU @ 2.70GHz              | 1         | 0.57%   |
| Intel Pentium M                               | 1         | 0.57%   |
| Intel CPU Version                             | 1         | 0.57%   |
| Intel Core M-5Y10c CPU @ 0.80GHz              | 1         | 0.57%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 1         | 0.57%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 53        | 30.46%  |
| Intel Core i7    | 42        | 24.14%  |
| Intel Core i3    | 14        | 8.05%   |
| Other            | 13        | 7.47%   |
| Intel Core 2 Duo | 9         | 5.17%   |
| Intel Celeron    | 8         | 4.6%    |
| AMD EPYC         | 7         | 4.02%   |
| Intel Atom       | 4         | 2.3%    |
| AMD Ryzen 7 PRO  | 4         | 2.3%    |
| AMD Ryzen 7      | 4         | 2.3%    |
| AMD Ryzen 5      | 3         | 1.72%   |
| Intel Xeon       | 2         | 1.15%   |
| Intel Core i9    | 2         | 1.15%   |
| AMD A4           | 2         | 1.15%   |
| Intel Pentium M  | 1         | 0.57%   |
| Intel Core M     | 1         | 0.57%   |
| Intel Core 2     | 1         | 0.57%   |
| AMD Ryzen 5 PRO  | 1         | 0.57%   |
| AMD E2           | 1         | 0.57%   |
| AMD E1           | 1         | 0.57%   |
| AMD A6           | 1         | 0.57%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 78        | 44.83%  |
| 4       | 54        | 31.03%  |
| 8       | 12        | 6.9%    |
| Unknown | 11        | 6.32%   |
| 6       | 6         | 3.45%   |
| 16      | 5         | 2.87%   |
| 12      | 3         | 1.72%   |
| 32      | 2         | 1.15%   |
| 1       | 2         | 1.15%   |
| 10      | 1         | 0.57%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 166       | 95.95%  |
| Unknown | 5         | 2.89%   |
| 2       | 2         | 1.16%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 122       | 70.11%  |
| 1       | 40        | 22.99%  |
| Unknown | 12        | 6.9%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 37        | 21.26%  |
| Haswell       | 23        | 13.22%  |
| Unknown       | 16        | 9.2%    |
| IvyBridge     | 15        | 8.62%   |
| SandyBridge   | 12        | 6.9%    |
| Skylake       | 11        | 6.32%   |
| Zen           | 10        | 5.75%   |
| Broadwell     | 9         | 5.17%   |
| Penryn        | 8         | 4.6%    |
| Westmere      | 6         | 3.45%   |
| Silvermont    | 4         | 2.3%    |
| Zen+          | 3         | 1.72%   |
| Zen 2         | 3         | 1.72%   |
| Core          | 3         | 1.72%   |
| Bonnell       | 3         | 1.72%   |
| TigerLake     | 2         | 1.15%   |
| K10 Llano     | 2         | 1.15%   |
| Jaguar        | 2         | 1.15%   |
| Zen 3         | 1         | 0.57%   |
| P6            | 1         | 0.57%   |
| Goldmont plus | 1         | 0.57%   |
| Excavator     | 1         | 0.57%   |
| CometLake     | 1         | 0.57%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 131       | 67.18%  |
| Nvidia | 40        | 20.51%  |
| AMD    | 24        | 12.31%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 17        | 8.42%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 13        | 6.44%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11        | 5.45%   |
| Intel HD Graphics 5500                                                                   | 8         | 3.96%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 3.47%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 3.47%   |
| Intel UHD Graphics 620                                                                   | 6         | 2.97%   |
| Intel HD Graphics 620                                                                    | 6         | 2.97%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 2.97%   |
| Intel HD Graphics 630                                                                    | 4         | 1.98%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 1.98%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.98%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.98%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 3         | 1.49%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 1.49%   |
| Intel Raptor Lake-S UHD Graphics                                                         | 3         | 1.49%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 3         | 1.49%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 1.49%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.49%   |
| Intel HD Graphics 530                                                                    | 3         | 1.49%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 1.49%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 3         | 1.49%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 1.49%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 1.49%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.99%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.99%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 2         | 0.99%   |
| Nvidia AD106M [GeForce RTX 4070 Max-Q / Mobile]                                          | 2         | 0.99%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 0.99%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 0.99%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.99%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.99%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.99%   |
| Intel Iris Plus Graphics 640                                                             | 2         | 0.99%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 2         | 0.99%   |
| AMD Lucienne                                                                             | 2         | 0.99%   |
| Nvidia TU117GLM [T1200 Laptop GPU]                                                       | 1         | 0.5%    |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.5%    |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 0.5%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 94        | 53.71%  |
| Intel + Nvidia           | 24        | 13.71%  |
| 1 x AMD                  | 19        | 10.86%  |
| 1 x Nvidia               | 15        | 8.57%   |
| 2 x Intel                | 11        | 6.29%   |
| Other                    | 7         | 4%      |
| 2 x AMD                  | 2         | 1.14%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.57%   |
| Intel + AMD              | 1         | 0.57%   |
| AMD + Nvidia             | 1         | 0.57%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 149       | 84.66%  |
| Proprietary | 15        | 8.52%   |
| Unknown     | 12        | 6.82%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 152       | 87.36%  |
| 0.51-1.0   | 6         | 3.45%   |
| 0.01-0.5   | 4         | 2.3%    |
| 7.01-8.0   | 3         | 1.72%   |
| 5.01-6.0   | 3         | 1.72%   |
| 3.01-4.0   | 3         | 1.72%   |
| 1.01-2.0   | 2         | 1.15%   |
| 8.01-16.0  | 1         | 0.57%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 26        | 18.44%  |
| LG Display              | 19        | 13.48%  |
| Chimei Innolux          | 17        | 12.06%  |
| BOE                     | 13        | 9.22%   |
| Samsung Electronics     | 11        | 7.8%    |
| Apple                   | 11        | 7.8%    |
| Chi Mei Optoelectronics | 5         | 3.55%   |
| Iiyama                  | 4         | 2.84%   |
| Goldstar                | 4         | 2.84%   |
| Dell                    | 4         | 2.84%   |
| Sharp                   | 3         | 2.13%   |
| Philips                 | 3         | 2.13%   |
| Lenovo                  | 3         | 2.13%   |
| CSO                     | 3         | 2.13%   |
| ViewSonic               | 2         | 1.42%   |
| LGD                     | 2         | 1.42%   |
| HUAWEI                  | 2         | 1.42%   |
| Unknown                 | 1         | 0.71%   |
| Nvidia                  | 1         | 0.71%   |
| IBM                     | 1         | 0.71%   |
| Hewlett-Packard         | 1         | 0.71%   |
| CPT                     | 1         | 0.71%   |
| BOE Technology Group    | 1         | 0.71%   |
| ASUSTek Computer        | 1         | 0.71%   |
| Acer                    | 1         | 0.71%   |
| Unknown                 | 1         | 0.71%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                     | 4         | 2.84%   |
| Goldstar 24GM77 GSM5A91 1920x1080 530x300mm 24.0-inch                    | 3         | 2.13%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 3         | 2.13%   |
| Philips PHL 241B8Q PHL0929 1920x1080 530x300mm 24.0-inch                 | 2         | 1.42%   |
| LGD LCD Monitor 1600x900                                                 | 2         | 1.42%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 2         | 1.42%   |
| Iiyama PL2474H IVM6146 1920x1080 520x290mm 23.4-inch                     | 2         | 1.42%   |
| HUAWEI AD80HW HWV2402 1920x1080 530x300mm 24.0-inch                      | 2         | 1.42%   |
| Dell SE2417HGX DELD0F7 1920x1080 520x290mm 23.4-inch                     | 2         | 1.42%   |
| Chimei Innolux LCD Monitor CMN1343 1920x1080 280x160mm 12.7-inch         | 2         | 1.42%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 2         | 1.42%   |
| BOE LCD Monitor BOE0700 1920x1080 340x190mm 15.3-inch                    | 2         | 1.42%   |
| AU Optronics LCD Monitor AUO34ED 1920x1080 340x190mm 15.3-inch           | 2         | 1.42%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch            | 2         | 1.42%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch           | 2         | 1.42%   |
| AU Optronics LCD Monitor AUO113D 1920x1080 310x170mm 13.9-inch           | 2         | 1.42%   |
| Apple Color LCD APPA034 2880x1800 290x180mm 13.4-inch                    | 2         | 1.42%   |
| ViewSonic VA2223-FHD VSC9239 1920x1080 480x270mm 21.7-inch               | 1         | 0.71%   |
| ViewSonic TD2420 SERIES VSC452D 1920x1080 520x290mm 23.4-inch            | 1         | 0.71%   |
| Unknown LCD Monitor Sharp 3840x2160                                      | 1         | 0.71%   |
| Sharp LCD Monitor SHP14B9 3840x2160 340x190mm 15.3-inch                  | 1         | 0.71%   |
| Sharp LCD Monitor SHP1416 1366x768 310x170mm 13.9-inch                   | 1         | 0.71%   |
| Sharp LCD Monitor SHP13F9 3200x1800 350x190mm 15.7-inch                  | 1         | 0.71%   |
| Samsung Electronics SyncMaster SAM027E 1680x1050 470x300mm 22.0-inch     | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SEC544E 1024x600 220x130mm 10.1-inch     | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x170mm 13.9-inch     | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch    | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 300x190mm 14.0-inch     | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SEC3659 1600x900 340x190mm 15.3-inch     | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 340x190mm 15.3-inch     | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch     | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 340x190mm 15.3-inch     | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch     | 1         | 0.71%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch        | 1         | 0.71%   |
| Philips PHL 439P1 PHL0973 3840x2160 940x530mm 42.5-inch                  | 1         | 0.71%   |
| Nvidia LCD Monitor Default Flat Panel 1440x900                           | 1         | 0.71%   |
| LG Display LCD Monitor LGD7001 1366x768 340x190mm 15.3-inch              | 1         | 0.71%   |
| LG Display LCD Monitor LGD06B8 1920x1080 340x190mm 15.3-inch             | 1         | 0.71%   |
| LG Display LCD Monitor LGD063F 1920x1080 380x210mm 17.1-inch             | 1         | 0.71%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch             | 1         | 0.71%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 53        | 40.77%  |
| 1366x768 (WXGA)    | 35        | 26.92%  |
| 1600x900 (HD+)     | 8         | 6.15%   |
| 1440x900 (WXGA+)   | 6         | 4.62%   |
| 3840x2160 (4K)     | 5         | 3.85%   |
| 2560x1440 (QHD)    | 4         | 3.08%   |
| 1280x800 (WXGA)    | 4         | 3.08%   |
| 2560x1600          | 3         | 2.31%   |
| 1024x600           | 3         | 2.31%   |
| 2880x1800          | 2         | 1.54%   |
| 1920x1200 (WUXGA)  | 2         | 1.54%   |
| 1680x1050 (WSXGA+) | 2         | 1.54%   |
| 3200x1800 (QHD+)   | 1         | 0.77%   |
| 1440x960           | 1         | 0.77%   |
| 1400x1050          | 1         | 0.77%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 13      | 42        | 30.43%  |
| 15      | 35        | 25.36%  |
| 12      | 15        | 10.87%  |
| 17      | 7         | 5.07%   |
| Unknown | 7         | 5.07%   |
| 24      | 6         | 4.35%   |
| 23      | 6         | 4.35%   |
| 14      | 4         | 2.9%    |
| 27      | 3         | 2.17%   |
| 21      | 3         | 2.17%   |
| 10      | 3         | 2.17%   |
| 11      | 2         | 1.45%   |
| 42      | 1         | 0.72%   |
| 31      | 1         | 0.72%   |
| 22      | 1         | 0.72%   |
| 18      | 1         | 0.72%   |
| 9       | 1         | 0.72%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 65        | 47.45%  |
| 201-300     | 37        | 27.01%  |
| 501-600     | 13        | 9.49%   |
| 351-400     | 7         | 5.11%   |
| Unknown     | 7         | 5.11%   |
| 401-500     | 5         | 3.65%   |
| 601-700     | 2         | 1.46%   |
| 901-1000    | 1         | 0.73%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 95        | 77.87%  |
| 16/10   | 15        | 12.3%   |
| Unknown | 7         | 5.74%   |
| 3/2     | 4         | 3.28%   |
| 4/3     | 1         | 0.82%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 42        | 30.66%  |
| 91-100         | 29        | 21.17%  |
| 61-70          | 15        | 10.95%  |
| 201-250        | 15        | 10.95%  |
| 121-130        | 7         | 5.11%   |
| Unknown        | 7         | 5.11%   |
| 101-110        | 5         | 3.65%   |
| 41-50          | 4         | 2.92%   |
| 71-80          | 3         | 2.19%   |
| 301-350        | 3         | 2.19%   |
| 51-60          | 2         | 1.46%   |
| 111-120        | 2         | 1.46%   |
| 351-500        | 1         | 0.73%   |
| 141-150        | 1         | 0.73%   |
| 501-1000       | 1         | 0.73%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 64        | 47.41%  |
| 101-120       | 34        | 25.19%  |
| 51-100        | 16        | 11.85%  |
| 161-240       | 10        | 7.41%   |
| Unknown       | 7         | 5.19%   |
| More than 240 | 4         | 2.96%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 117       | 64.29%  |
| 0     | 46        | 25.27%  |
| 2     | 16        | 8.79%   |
| 3     | 3         | 1.65%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 126       | 47.55%  |
| Realtek Semiconductor             | 57        | 21.51%  |
| Qualcomm Atheros                  | 27        | 10.19%  |
| Broadcom                          | 17        | 6.42%   |
| AMD                               | 7         | 2.64%   |
| Marvell Technology Group          | 5         | 1.89%   |
| Xiaomi                            | 3         | 1.13%   |
| TP-Link                           | 3         | 1.13%   |
| Sierra Wireless                   | 3         | 1.13%   |
| Dell                              | 3         | 1.13%   |
| Edimax Technology                 | 2         | 0.75%   |
| Apple                             | 2         | 0.75%   |
| Samsung Electronics               | 1         | 0.38%   |
| Sagem                             | 1         | 0.38%   |
| Ralink Technology                 | 1         | 0.38%   |
| Ralink                            | 1         | 0.38%   |
| Qualcomm                          | 1         | 0.38%   |
| Nvidia                            | 1         | 0.38%   |
| MediaTek                          | 1         | 0.38%   |
| Huawei Technologies               | 1         | 0.38%   |
| Hewlett-Packard                   | 1         | 0.38%   |
| Ericsson Business Mobile Networks | 1         | 0.38%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 40        | 11.63%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 15        | 4.36%   |
| Intel Wireless 8265 / 8275                                             | 14        | 4.07%   |
| Intel Wireless 7265                                                    | 11        | 3.2%    |
| Intel Wireless 8260                                                    | 10        | 2.91%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 10        | 2.91%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 7         | 2.03%   |
| Intel Wireless 7260                                                    | 7         | 2.03%   |
| Intel Ethernet Connection (3) I218-LM                                  | 7         | 2.03%   |
| AMD XGMAC 10GbE Controller                                             | 7         | 2.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 6         | 1.74%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 6         | 1.74%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 6         | 1.74%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 6         | 1.74%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 5         | 1.45%   |
| Intel Wi-Fi 6 AX200                                                    | 5         | 1.45%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 5         | 1.45%   |
| Intel I210 Gigabit Network Connection                                  | 5         | 1.45%   |
| Intel Ethernet Connection I217-LM                                      | 5         | 1.45%   |
| Intel Ethernet Connection (4) I219-V                                   | 5         | 1.45%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 5         | 1.45%   |
| Intel Ethernet Connection (4) I219-LM                                  | 4         | 1.16%   |
| Intel Centrino Advanced-N 6235                                         | 4         | 1.16%   |
| Intel 82567LM Gigabit Network Connection                               | 4         | 1.16%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 3         | 0.87%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 3         | 0.87%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 3         | 0.87%   |
| Intel Wireless 3165                                                    | 3         | 0.87%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 3         | 0.87%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 3         | 0.87%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                | 3         | 0.87%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 3         | 0.87%   |
| Intel Ethernet Controller I225-V                                       | 3         | 0.87%   |
| Intel Ethernet Connection I219-LM                                      | 3         | 0.87%   |
| Intel Ethernet Connection (6) I219-V                                   | 3         | 0.87%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3         | 0.87%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 3         | 0.87%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 2         | 0.58%   |
| Sierra Wireless EM7305 Modem                                           | 2         | 0.58%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 115       | 65.34%  |
| Qualcomm Atheros      | 24        | 13.64%  |
| Broadcom              | 14        | 7.95%   |
| Realtek Semiconductor | 11        | 6.25%   |
| TP-Link               | 3         | 1.7%    |
| Edimax Technology     | 2         | 1.14%   |
| Dell                  | 2         | 1.14%   |
| Sierra Wireless       | 1         | 0.57%   |
| Sagem                 | 1         | 0.57%   |
| Ralink Technology     | 1         | 0.57%   |
| Ralink                | 1         | 0.57%   |
| MediaTek              | 1         | 0.57%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 14        | 7.91%   |
| Intel Wireless 7265                                            | 11        | 6.21%   |
| Intel Wireless 8260                                            | 10        | 5.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 10        | 5.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 7         | 3.95%   |
| Intel Wireless 7260                                            | 7         | 3.95%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 6         | 3.39%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 6         | 3.39%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 6         | 3.39%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 5         | 2.82%   |
| Intel Wi-Fi 6 AX200                                            | 5         | 2.82%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 5         | 2.82%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 5         | 2.82%   |
| Intel Centrino Advanced-N 6235                                 | 4         | 2.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 3         | 1.69%   |
| Intel Wireless 3165                                            | 3         | 1.69%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 3         | 1.69%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 3         | 1.69%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 3         | 1.69%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 3         | 1.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 1.69%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 2         | 1.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 1.13%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 1.13%   |
| Intel WiFi Link 5100                                           | 2         | 1.13%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 1.13%   |
| Intel Raptor Lake-S PCH CNVi WiFi                              | 2         | 1.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 1.13%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 2         | 1.13%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 1.13%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 2         | 1.13%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 2         | 1.13%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter             | 2         | 1.13%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 2         | 1.13%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 0.56%   |
| Sierra Wireless EM7345 4G LTE                                  | 1         | 0.56%   |
| Sagem XG-76NA / XG-760N 802.11b/g Wireless adapter             | 1         | 0.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.56%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                   | 1         | 0.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 80        | 50.63%  |
| Realtek Semiconductor    | 48        | 30.38%  |
| Qualcomm Atheros         | 7         | 4.43%   |
| AMD                      | 7         | 4.43%   |
| Marvell Technology Group | 5         | 3.16%   |
| Broadcom                 | 4         | 2.53%   |
| Xiaomi                   | 3         | 1.9%    |
| Samsung Electronics      | 1         | 0.63%   |
| Qualcomm                 | 1         | 0.63%   |
| Nvidia                   | 1         | 0.63%   |
| Apple                    | 1         | 0.63%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 40        | 25.16%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 15        | 9.43%   |
| Intel Ethernet Connection (3) I218-LM                                  | 7         | 4.4%    |
| AMD XGMAC 10GbE Controller                                             | 7         | 4.4%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 6         | 3.77%   |
| Intel I210 Gigabit Network Connection                                  | 5         | 3.14%   |
| Intel Ethernet Connection I217-LM                                      | 5         | 3.14%   |
| Intel Ethernet Connection (4) I219-V                                   | 5         | 3.14%   |
| Intel Ethernet Connection (4) I219-LM                                  | 4         | 2.52%   |
| Intel 82567LM Gigabit Network Connection                               | 4         | 2.52%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 3         | 1.89%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 3         | 1.89%   |
| Intel Ethernet Controller I225-V                                       | 3         | 1.89%   |
| Intel Ethernet Connection I219-LM                                      | 3         | 1.89%   |
| Intel Ethernet Connection (6) I219-V                                   | 3         | 1.89%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3         | 1.89%   |
| Intel Ethernet Connection I219-V                                       | 2         | 1.26%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 1.26%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2         | 1.26%   |
| Intel Ethernet Connection (5) I219-LM                                  | 2         | 1.26%   |
| Intel Ethernet Connection (23) I219-V                                  | 2         | 1.26%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 0.63%   |
| Realtek USB 2.5GbE Controller                                          | 1         | 0.63%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 0.63%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 0.63%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.63%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.63%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.63%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.63%   |
| Qualcomm ALCATEL RNDIS Interface                                       | 1         | 0.63%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 0.63%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 1         | 0.63%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                | 1         | 0.63%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1         | 0.63%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 1         | 0.63%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                   | 1         | 0.63%   |
| Intel Ethernet Connection I217-V                                       | 1         | 0.63%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 0.63%   |
| Intel Ethernet Connection (3) I218-V                                   | 1         | 0.63%   |
| Intel Ethernet Connection (23) I219-LM                                 | 1         | 0.63%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 158       | 50.48%  |
| Ethernet | 147       | 46.96%  |
| Unknown  | 5         | 1.6%    |
| Modem    | 3         | 0.96%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 108       | 51.92%  |
| WiFi     | 100       | 48.08%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 128       | 73.56%  |
| 1     | 30        | 17.24%  |
| 6     | 8         | 4.6%    |
| 3     | 7         | 4.02%   |
| 0     | 1         | 0.57%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 153       | 85.47%  |
| Yes  | 26        | 14.53%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 80        | 68.97%  |
| Broadcom                        | 8         | 6.9%    |
| Apple                           | 8         | 6.9%    |
| Qualcomm Atheros Communications | 5         | 4.31%   |
| Realtek Semiconductor           | 3         | 2.59%   |
| IMC Networks                    | 3         | 2.59%   |
| Foxconn / Hon Hai               | 3         | 2.59%   |
| Dell                            | 3         | 2.59%   |
| TP-Link                         | 1         | 0.86%   |
| Hewlett-Packard                 | 1         | 0.86%   |
| Creative Technology             | 1         | 0.86%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                        | 36        | 31.03%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)            | 11        | 9.48%   |
| Intel AX201 Bluetooth                                     | 11        | 9.48%   |
| Intel AX200 Bluetooth                                     | 5         | 4.31%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                  | 4         | 3.45%   |
| Intel AX211 Bluetooth                                     | 4         | 3.45%   |
| Apple Broadcom Built-in Bluetooth                         | 4         | 3.45%   |
| Intel Centrino Bluetooth Wireless Transceiver             | 3         | 2.59%   |
| Intel AX210 Bluetooth                                     | 3         | 2.59%   |
| Broadcom BCM2045B (BDC-2.1)                               | 3         | 2.59%   |
| Apple Bluetooth Host Controller                           | 3         | 2.59%   |
| Realtek Bluetooth Adapter                                 | 2         | 1.72%   |
| Intel Wireless-AC 3168 Bluetooth                          | 2         | 1.72%   |
| Foxconn / Hon Hai Bluetooth USB Module                    | 2         | 1.72%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module               | 2         | 1.72%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                | 2         | 1.72%   |
| TP-Link Bluetooth 5.0 USB Adapter                         | 1         | 0.86%   |
| Realtek  Bluetooth 4.2 Adapter                            | 1         | 0.86%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                    | 1         | 0.86%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                    | 1         | 0.86%   |
| Qualcomm Atheros Dell Wireless 1601 Bluetooth Device      | 1         | 0.86%   |
| Qualcomm Atheros Bluetooth                                | 1         | 0.86%   |
| Qualcomm Atheros AR3011 Bluetooth                         | 1         | 0.86%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1               | 1         | 0.86%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS          | 1         | 0.86%   |
| IMC Networks Bluetooth Radio                              | 1         | 0.86%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]             | 1         | 0.86%   |
| Foxconn / Hon Hai Bluetooth 5.2 Adapter [MediaTek MT7922] | 1         | 0.86%   |
| Dell DW375 Bluetooth Module                               | 1         | 0.86%   |
| Creative Creative Bluetooth Audio W2                      | 1         | 0.86%   |
| Broadcom BCM43142A0 Bluetooth Module                      | 1         | 0.86%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]        | 1         | 0.86%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]          | 1         | 0.86%   |
| Apple Built-in iSight (no firmware loaded)                | 1         | 0.86%   |
| Unknown                                                   | 1         | 0.86%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 146       | 70.19%  |
| AMD                 | 27        | 12.98%  |
| Nvidia              | 22        | 10.58%  |
| Logitech            | 3         | 1.44%   |
| Lenovo              | 3         | 1.44%   |
| GN Netcom           | 2         | 0.96%   |
| ASUSTek Computer    | 2         | 0.96%   |
| Texas Instruments   | 1         | 0.48%   |
| Kingston Technology | 1         | 0.48%   |
| DSEA A/S            | 1         | 0.48%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 21        | 8.24%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 17        | 6.67%   |
| Intel 8 Series HD Audio Controller                                                                | 17        | 6.67%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 14        | 5.49%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 12        | 4.71%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 12        | 4.71%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 9         | 3.53%   |
| Intel Broadwell-U Audio Controller                                                                | 9         | 3.53%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 2.75%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 2.35%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 2.35%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 2.35%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 2.35%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 2.35%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 2.35%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 2.35%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 1.96%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 5         | 1.96%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.57%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 4         | 1.57%   |
| Intel CM238 HD Audio Controller                                                                   | 4         | 1.57%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 1.57%   |
| AMD FCH Azalia Controller                                                                         | 4         | 1.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 1.18%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 1.18%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 3         | 1.18%   |
| Intel Raptor Lake High Definition Audio Controller                                                | 3         | 1.18%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.18%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 1.18%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 0.78%   |
| Nvidia AD106M High Definition Audio Controller                                                    | 2         | 0.78%   |
| Logitech H600 [Wireless Headset]                                                                  | 2         | 0.78%   |
| Lenovo Realtek USB Audio                                                                          | 2         | 0.78%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 0.78%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 0.78%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 0.78%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.78%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 0.78%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 2         | 0.78%   |
| Texas Instruments PCM2706 stereo audio DAC                                                        | 1         | 0.39%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 53        | 28.96%  |
| SK hynix            | 38        | 20.77%  |
| Micron Technology   | 20        | 10.93%  |
| Unknown             | 13        | 7.1%    |
| Crucial             | 10        | 5.46%   |
| Kingston            | 9         | 4.92%   |
| Elpida              | 8         | 4.37%   |
| Transcend           | 6         | 3.28%   |
| Corsair             | 4         | 2.19%   |
| Ramaxel Technology  | 3         | 1.64%   |
| Nanya Technology    | 3         | 1.64%   |
| Unknown             | 3         | 1.64%   |
| G.Skill             | 2         | 1.09%   |
| A-DATA Technology   | 2         | 1.09%   |
| V-Color             | 1         | 0.55%   |
| Unknown (ABCD)      | 1         | 0.55%   |
| SHARETRONIC         | 1         | 0.55%   |
| Patriot             | 1         | 0.55%   |
| Kllisre             | 1         | 0.55%   |
| CSX                 | 1         | 0.55%   |
| Avant               | 1         | 0.55%   |
| 48spaces            | 1         | 0.55%   |
| 2B0B00000000        | 1         | 0.55%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                  | 5         | 2.49%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 4         | 1.99%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s       | 4         | 1.99%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 4         | 1.99%   |
| Unknown RAM Module 2GB SODIMM DDR2                          | 3         | 1.49%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s         | 3         | 1.49%   |
| Transcend RAM TS1GLH64V6B3 8GB SODIMM DDR4 1333MT/s         | 3         | 1.49%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 3         | 1.49%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s      | 3         | 1.49%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s      | 3         | 1.49%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s      | 3         | 1.49%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 3         | 1.49%   |
| Unknown                                                     | 3         | 1.49%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                  | 2         | 1%      |
| Unknown RAM Module 1GB SODIMM DDR2                          | 2         | 1%      |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 2         | 1%      |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 2         | 1%      |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s     | 2         | 1%      |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 2         | 1%      |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s     | 2         | 1%      |
| Samsung RAM M471B5773CHS-CK0 2GB DDR3 1600MT/s              | 2         | 1%      |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s       | 2         | 1%      |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s       | 2         | 1%      |
| Samsung RAM M471A5244BB0-CRC 4GB Row Of Chips DDR4 2400MT/s | 2         | 1%      |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s      | 2         | 1%      |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2400MT/s      | 2         | 1%      |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s       | 2         | 1%      |
| Samsung RAM M425R2GA3BB0-CWMOD 16GB SODIMM DDR5 5600MT/s    | 2         | 1%      |
| Micron RAM Module 4GB SODIMM LPDDR3 2133MT/s                | 2         | 1%      |
| Elpida RAM Module 4096MB SODIMM DDR3 1600MT/s               | 2         | 1%      |
| Crucial RAM CT204864BF160B.C16 16GB SODIMM DDR3 1600MT/s    | 2         | 1%      |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s     | 2         | 1%      |
| Corsair RAM CMSX8GX4M1A2400C16 8GB SODIMM DDR4 2400MT/s     | 2         | 1%      |
| A-DATA RAM AO1P32NCST2-BZ6SHD 16384MB SODIMM DDR4 3200MT/s  | 2         | 1%      |
| V-Color RAM TN48G24S817-VHA/R 8GB SODIMM DDR4 2400MT/s      | 1         | 0.5%    |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                 | 1         | 0.5%    |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                 | 1         | 0.5%    |
| Unknown RAM Module 8192MB SODIMM DDR4 2400MT/s              | 1         | 0.5%    |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                 | 1         | 0.5%    |
| Unknown RAM Module 4GB SODIMM 533MT/s                       | 1         | 0.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 64        | 42.38%  |
| DDR3    | 61        | 40.4%   |
| DDR2    | 10        | 6.62%   |
| LPDDR3  | 7         | 4.64%   |
| DDR5    | 5         | 3.31%   |
| Unknown | 2         | 1.32%   |
| LPDDR5  | 1         | 0.66%   |
| LPDDR4  | 1         | 0.66%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 142       | 91.61%  |
| Row Of Chips | 7         | 4.52%   |
| Chip         | 3         | 1.94%   |
| Unknown      | 3         | 1.94%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 56        | 32.94%  |
| 4096  | 55        | 32.35%  |
| 16384 | 30        | 17.65%  |
| 2048  | 21        | 12.35%  |
| 32768 | 5         | 2.94%   |
| 1024  | 3         | 1.76%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 45        | 27.95%  |
| 2667    | 22        | 13.66%  |
| 3200    | 19        | 11.8%   |
| 2400    | 16        | 9.94%   |
| 1333    | 13        | 8.07%   |
| 2133    | 12        | 7.45%   |
| 1334    | 10        | 6.21%   |
| 5600    | 4         | 2.48%   |
| 1867    | 4         | 2.48%   |
| Unknown | 4         | 2.48%   |
| 667     | 3         | 1.86%   |
| 975     | 2         | 1.24%   |
| 800     | 2         | 1.24%   |
| 6400    | 1         | 0.62%   |
| 4800    | 1         | 0.62%   |
| 1200    | 1         | 0.62%   |
| 1067    | 1         | 0.62%   |
| 533     | 1         | 0.62%   |

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
| Chicony Electronics                    | 38        | 32.2%   |
| Microdia                               | 12        | 10.17%  |
| Sunplus Innovation Technology          | 11        | 9.32%   |
| Bison Electronics                      | 11        | 9.32%   |
| IMC Networks                           | 10        | 8.47%   |
| Realtek Semiconductor                  | 9         | 7.63%   |
| Syntek                                 | 5         | 4.24%   |
| Lite-On Technology                     | 5         | 4.24%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 4.24%   |
| Quanta                                 | 3         | 2.54%   |
| Suyin                                  | 2         | 1.69%   |
| Alcor Micro                            | 2         | 1.69%   |
| Z-Star Microelectronics                | 1         | 0.85%   |
| SIMPLO Technology                      | 1         | 0.85%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.85%   |
| Foxconn / Hon Hai                      | 1         | 0.85%   |
| Apple                                  | 1         | 0.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                             | 14        | 11.76%  |
| Bison Integrated Camera                               | 7         | 5.88%   |
| Microdia Integrated_Webcam_HD                         | 6         | 5.04%   |
| Sunplus Integrated_Webcam_HD                          | 5         | 4.2%    |
| Syntek Integrated Camera                              | 4         | 3.36%   |
| Realtek Integrated_Webcam_HD                          | 4         | 3.36%   |
| Microdia Integrated Webcam                            | 4         | 3.36%   |
| Chicony HD WebCam                                     | 4         | 3.36%   |
| Lite-On Integrated Camera                             | 3         | 2.52%   |
| Chicony Lenovo Integrated Camera (0.3MP)              | 3         | 2.52%   |
| Realtek USB Camera                                    | 2         | 1.68%   |
| IMC Networks USB2.0 HD UVC WebCam                     | 2         | 1.68%   |
| IMC Networks Realtek PC Camera                        | 2         | 1.68%   |
| IMC Networks Integrated Camera                        | 2         | 1.68%   |
| IMC Networks EasyCamera                               | 2         | 1.68%   |
| Chicony TOSHIBA Web Camera - HD                       | 2         | 1.68%   |
| Chicony Realtek DMFT RGB                              | 2         | 1.68%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam   | 2         | 1.68%   |
| Bison SunplusIT Integrated Camera                     | 2         | 1.68%   |
| Z-Star Webcam                                         | 1         | 0.84%   |
| Syntek Lenovo EasyCamera                              | 1         | 0.84%   |
| Suyin USB 2.0 Camera                                  | 1         | 0.84%   |
| Suyin Laptop_Integrated_Webcam_FHD                    | 1         | 0.84%   |
| Sunplus Laptop_Integrated_Webcam_HD                   | 1         | 0.84%   |
| Sunplus Laptop_Integrated_Webcam_FHD                  | 1         | 0.84%   |
| Sunplus Integrated HD Webcam                          | 1         | 0.84%   |
| Sunplus Hy HD Camera                                  | 1         | 0.84%   |
| Sunplus Dell Integrated Webcam                        | 1         | 0.84%   |
| Sunplus Asus Webcam                                   | 1         | 0.84%   |
| SIMPLO USB 2.0 Camera                                 | 1         | 0.84%   |
| Shenzhen Kingcome Optoelectronic USB2.0 HD UVC WebCam | 1         | 0.84%   |
| Realtek USB 2.0 PC Camera                             | 1         | 0.84%   |
| Realtek Integrated_Webcam_FHD                         | 1         | 0.84%   |
| Realtek Integrated Webcam HD                          | 1         | 0.84%   |
| Quanta Realtek DMFT RGB                               | 1         | 0.84%   |
| Quanta Integrated Webcam                              | 1         | 0.84%   |
| Quanta HD WebCam                                      | 1         | 0.84%   |
| Microdia Integrated_Webcam_FHD                        | 1         | 0.84%   |
| Microdia Dell Integrated HD Webcam                    | 1         | 0.84%   |
| Lite-On Realtek DMFT RGB                              | 1         | 0.84%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 13        | 34.21%  |
| Synaptics                  | 8         | 21.05%  |
| AuthenTec                  | 5         | 13.16%  |
| Elan Microelectronics      | 4         | 10.53%  |
| Shenzhen Goodix Technology | 3         | 7.89%   |
| LighTuning Technology      | 3         | 7.89%   |
| Upek                       | 1         | 2.63%   |
| Broadcom                   | 1         | 2.63%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 6         | 15.79%  |
| Elan Fingerprint Sensor                                                      | 4         | 10.53%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 3         | 7.89%   |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 3         | 7.89%   |
| Shenzhen Goodix Fingerprint Reader                                           | 3         | 7.89%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 2         | 5.26%   |
| Validity Sensors Synaptics WBDI                                              | 2         | 5.26%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 2         | 5.26%   |
| AuthenTec AES2810                                                            | 2         | 5.26%   |
| AuthenTec AES1660                                                            | 2         | 5.26%   |
| Validity Sensors VFS491                                                      | 1         | 2.63%   |
| Validity Sensors VFS451 Fingerprint Reader                                   | 1         | 2.63%   |
| Validity Sensors VFS Fingerprint sensor                                      | 1         | 2.63%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 1         | 2.63%   |
| Synaptics UWP WBDI Device                                                    | 1         | 2.63%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 1         | 2.63%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 1         | 2.63%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 2.63%   |
| AuthenTec AES2550 Fingerprint Sensor                                         | 1         | 2.63%   |

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
| 2     | 57        | 30.65%  |
| 1     | 56        | 30.11%  |
| 3     | 30        | 16.13%  |
| 0     | 19        | 10.22%  |
| 4     | 17        | 9.14%   |
| 6     | 4         | 2.15%   |
| 5     | 2         | 1.08%   |
| 7     | 1         | 0.54%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 131       | 41.19%  |
| Bluetooth                | 59        | 18.55%  |
| Net/wireless             | 34        | 10.69%  |
| Fingerprint reader       | 32        | 10.06%  |
| Card reader              | 27        | 8.49%   |
| Firewire controller      | 14        | 4.4%    |
| Sound                    | 6         | 1.89%   |
| Graphics card            | 5         | 1.57%   |
| Storage                  | 4         | 1.26%   |
| Storage/raid             | 3         | 0.94%   |
| Network                  | 2         | 0.63%   |
| Net/ethernet             | 1         | 0.31%   |

