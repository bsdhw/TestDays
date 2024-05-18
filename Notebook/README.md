BSD - Tested Hardware & Statistics (Notebooks)
----------------------------------------------

A project to collect tested hardware configurations for BSD.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This report is for real hardware. Report for virtual hardware: [TestDays_VE](https://github.com/bsdhw/TestDays_VE)

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

Total: 4637

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Acer          | TravelMate B118-M           | [68d9d26fe5](https://bsd-hardware.info/?probe=68d9d26fe5) | May 09, 2024 |
| Acer          | TravelMate B118-M           | [216637ad84](https://bsd-hardware.info/?probe=216637ad84) | May 08, 2024 |
| Lenovo        | ThinkPad T530 2394EE9       | [9bc81955aa](https://bsd-hardware.info/?probe=9bc81955aa) | May 08, 2024 |
| Lenovo        | ThinkPad T530 2394EE9       | [651bd2de24](https://bsd-hardware.info/?probe=651bd2de24) | May 08, 2024 |
| Alienware     | Area-51m A00                | [53d5d4eb1e](https://bsd-hardware.info/?probe=53d5d4eb1e) | May 07, 2024 |
| Unknown       | X133                        | [524b7e6d8e](https://bsd-hardware.info/?probe=524b7e6d8e) | May 07, 2024 |
| Dell          | XPS 13 9360                 | [c9ad91fc61](https://bsd-hardware.info/?probe=c9ad91fc61) | May 07, 2024 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [b97dcbade6](https://bsd-hardware.info/?probe=b97dcbade6) | May 07, 2024 |
| Lenovo        | ThinkPad W520 4284GZ1       | [0990e7253e](https://bsd-hardware.info/?probe=0990e7253e) | May 07, 2024 |
| Acer          | Aspire R3-131T              | [dec4102ec0](https://bsd-hardware.info/?probe=dec4102ec0) | May 07, 2024 |
| Deciso        | NetBoard-A10                | [3ae8150618](https://bsd-hardware.info/?probe=3ae8150618) | May 06, 2024 |
| Dell          | Precision 7560              | [62956576cd](https://bsd-hardware.info/?probe=62956576cd) | May 06, 2024 |
| Lenovo        | ThinkPad X240 20AMS3FY00    | [1dc74d60e6](https://bsd-hardware.info/?probe=1dc74d60e6) | May 06, 2024 |
| Apple         | MacBookPro8,1               | [23e113910f](https://bsd-hardware.info/?probe=23e113910f) | May 05, 2024 |
| Apple         | MacBookPro8,1               | [55560acf02](https://bsd-hardware.info/?probe=55560acf02) | May 05, 2024 |
| Lenovo        | ThinkPad L420 7827W27       | [5231c79a27](https://bsd-hardware.info/?probe=5231c79a27) | May 05, 2024 |
| Apple         | MacBook4,1                  | [5916d9274d](https://bsd-hardware.info/?probe=5916d9274d) | May 05, 2024 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [f67c0c6b18](https://bsd-hardware.info/?probe=f67c0c6b18) | May 05, 2024 |
| Micro Comp... | Venus series                | [11184b32bb](https://bsd-hardware.info/?probe=11184b32bb) | May 05, 2024 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [89a61aca01](https://bsd-hardware.info/?probe=89a61aca01) | May 04, 2024 |
| Lenovo        | ThinkPad T15p Gen 1 20TN... | [5f31e6dc7e](https://bsd-hardware.info/?probe=5f31e6dc7e) | May 04, 2024 |
| Apple         | MacBookPro5,5               | [ffd31a143f](https://bsd-hardware.info/?probe=ffd31a143f) | May 04, 2024 |
| Panasonic     | CF-54-1                     | [00de332c2c](https://bsd-hardware.info/?probe=00de332c2c) | May 04, 2024 |
| Dell          | Latitude 7390               | [b9b511f4d6](https://bsd-hardware.info/?probe=b9b511f4d6) | May 04, 2024 |
| HP            | ZBook 17 G2                 | [8558fc6b60](https://bsd-hardware.info/?probe=8558fc6b60) | May 04, 2024 |
| Chuwi         | GemiBook Pro                | [2656d00123](https://bsd-hardware.info/?probe=2656d00123) | May 03, 2024 |
| Dell          | Precision 3571              | [d8015bf7e8](https://bsd-hardware.info/?probe=d8015bf7e8) | May 03, 2024 |
| MSI           | GE75 Raider 10SFS           | [227924f274](https://bsd-hardware.info/?probe=227924f274) | May 03, 2024 |
| Panasonic     | CF-52PFPBSFQ                | [48423bbece](https://bsd-hardware.info/?probe=48423bbece) | May 03, 2024 |
| Lenovo        | B40-30 80F1                 | [98be66c2e6](https://bsd-hardware.info/?probe=98be66c2e6) | May 03, 2024 |
| MSI           | GE75 Raider 10SFS           | [cda74e2f91](https://bsd-hardware.info/?probe=cda74e2f91) | May 02, 2024 |
| Dell          | Inspiron 15-3552            | [0a47152038](https://bsd-hardware.info/?probe=0a47152038) | May 02, 2024 |
| Dell          | Precision 7560              | [2f6e45641d](https://bsd-hardware.info/?probe=2f6e45641d) | May 02, 2024 |
| Apple         | PowerBook6,8                | [fa66040f75](https://bsd-hardware.info/?probe=fa66040f75) | May 02, 2024 |
| ASUSTek       | X202E                       | [0ed385a36d](https://bsd-hardware.info/?probe=0ed385a36d) | May 02, 2024 |
| Apple         | MacBookAir6,2               | [a9ec0cba48](https://bsd-hardware.info/?probe=a9ec0cba48) | May 02, 2024 |
| Dell          | Latitude 7490               | [e55889ef1e](https://bsd-hardware.info/?probe=e55889ef1e) | May 02, 2024 |
| Micro Comp... | Venus series                | [0fe27dcf5d](https://bsd-hardware.info/?probe=0fe27dcf5d) | May 01, 2024 |
| HP            | 255 G8 Notebook PC          | [4878c18c8a](https://bsd-hardware.info/?probe=4878c18c8a) | May 01, 2024 |
| Lenovo        | ThinkPad E490 20N9S48S00    | [f70fb4bd81](https://bsd-hardware.info/?probe=f70fb4bd81) | May 01, 2024 |
| Deciso        | NetBoard-A20                | [c04565ec24](https://bsd-hardware.info/?probe=c04565ec24) | Apr 30, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [49d6f53542](https://bsd-hardware.info/?probe=49d6f53542) | Apr 30, 2024 |
| Dell          | XPS 13 9360                 | [26185f189e](https://bsd-hardware.info/?probe=26185f189e) | Apr 30, 2024 |
| Unknown       | Unknown                     | [3c24648eb3](https://bsd-hardware.info/?probe=3c24648eb3) | Apr 30, 2024 |
| Deciso        | NetBoard-A20                | [1b9bcc1b41](https://bsd-hardware.info/?probe=1b9bcc1b41) | Apr 30, 2024 |
| Lenovo        | ThinkPad T470 20HES18R05    | [9b76000646](https://bsd-hardware.info/?probe=9b76000646) | Apr 30, 2024 |
| HP            | EliteBook 2560p             | [bb6303ed5b](https://bsd-hardware.info/?probe=bb6303ed5b) | Apr 29, 2024 |
| Acer          | Aspire 5551                 | [ee15a7d2b5](https://bsd-hardware.info/?probe=ee15a7d2b5) | Apr 29, 2024 |
| Lenovo        | ThinkPad T410 2537N24       | [04370189ed](https://bsd-hardware.info/?probe=04370189ed) | Apr 29, 2024 |
| DFI           | Unknown                     | [1348838d15](https://bsd-hardware.info/?probe=1348838d15) | Apr 28, 2024 |
| Apple         | MacBookAir6,2               | [26a2dbed23](https://bsd-hardware.info/?probe=26a2dbed23) | Apr 28, 2024 |
| Apple         | MacBookAir6,2               | [126d9918f3](https://bsd-hardware.info/?probe=126d9918f3) | Apr 28, 2024 |
| Apple         | MacBookAir6,2               | [5bb2644b89](https://bsd-hardware.info/?probe=5bb2644b89) | Apr 28, 2024 |
| Lenovo        | ThinkPad A485 20MU000VUS    | [0323476838](https://bsd-hardware.info/?probe=0323476838) | Apr 28, 2024 |
| Lenovo        | ThinkPad T430 2347GZU       | [f49f1b3ac2](https://bsd-hardware.info/?probe=f49f1b3ac2) | Apr 28, 2024 |
| Lenovo        | Legion Y7000P 81HC          | [3dff76a9dd](https://bsd-hardware.info/?probe=3dff76a9dd) | Apr 27, 2024 |
| HP            | ZBook 15 G6                 | [95aadf59d9](https://bsd-hardware.info/?probe=95aadf59d9) | Apr 27, 2024 |
| ASUSTek       | K43E                        | [19049c7899](https://bsd-hardware.info/?probe=19049c7899) | Apr 27, 2024 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [1c5398a208](https://bsd-hardware.info/?probe=1c5398a208) | Apr 26, 2024 |
| Apple         | MacBookAir6,2               | [2b066c44b9](https://bsd-hardware.info/?probe=2b066c44b9) | Apr 26, 2024 |
| Apple         | MacBookAir6,2               | [a206641c60](https://bsd-hardware.info/?probe=a206641c60) | Apr 26, 2024 |
| System76      | Pangolin                    | [d47c9a5d44](https://bsd-hardware.info/?probe=d47c9a5d44) | Apr 26, 2024 |
| Panasonic     | CFSX4-1                     | [58c0214ae8](https://bsd-hardware.info/?probe=58c0214ae8) | Apr 25, 2024 |
| Apple         | MacBookPro10,1              | [ae0802fcda](https://bsd-hardware.info/?probe=ae0802fcda) | Apr 25, 2024 |
| Dell          | Latitude 7490               | [510590d1c7](https://bsd-hardware.info/?probe=510590d1c7) | Apr 24, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [bf89bc5c69](https://bsd-hardware.info/?probe=bf89bc5c69) | Apr 24, 2024 |
| HP            | ProBook 440 G2              | [459837155f](https://bsd-hardware.info/?probe=459837155f) | Apr 24, 2024 |
| Unknown       | Unknown                     | [6016137c6c](https://bsd-hardware.info/?probe=6016137c6c) | Apr 24, 2024 |
| Lenovo        | ThinkPad X280 20KFCTO1WW    | [d76cb40918](https://bsd-hardware.info/?probe=d76cb40918) | Apr 23, 2024 |
| Lenovo        | ThinkPad X220 429135G       | [b681d0b406](https://bsd-hardware.info/?probe=b681d0b406) | Apr 23, 2024 |
| Deciso        | NetBoard-A20                | [0546076798](https://bsd-hardware.info/?probe=0546076798) | Apr 23, 2024 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [7ae4c9320c](https://bsd-hardware.info/?probe=7ae4c9320c) | Apr 23, 2024 |
| Lenovo        | ThinkPad X260 20F5S2GM00    | [8a37e6930f](https://bsd-hardware.info/?probe=8a37e6930f) | Apr 23, 2024 |
| Panasonic     | CF-53AAGHYDM                | [3eac3d5a68](https://bsd-hardware.info/?probe=3eac3d5a68) | Apr 23, 2024 |
| Deciso        | NetBoard-A20                | [c64fcd31dd](https://bsd-hardware.info/?probe=c64fcd31dd) | Apr 23, 2024 |
| ASUSTek       | K43E                        | [cf2e60227c](https://bsd-hardware.info/?probe=cf2e60227c) | Apr 22, 2024 |
| Lenovo        | ThinkBook 16 G5+ APH 21K... | [428f8cd2c7](https://bsd-hardware.info/?probe=428f8cd2c7) | Apr 22, 2024 |
| Apple         | MacBookAir4,1               | [a6e153110d](https://bsd-hardware.info/?probe=a6e153110d) | Apr 22, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [4f57a0fe86](https://bsd-hardware.info/?probe=4f57a0fe86) | Apr 22, 2024 |
| Notebook      | NV4XMB,ME,MZ                | [bf1d7a54d1](https://bsd-hardware.info/?probe=bf1d7a54d1) | Apr 22, 2024 |
| Lenovo        | ThinkPad T440 20B7S01V00    | [3008b64c82](https://bsd-hardware.info/?probe=3008b64c82) | Apr 22, 2024 |
| Dell          | Precision 7680              | [4987815b22](https://bsd-hardware.info/?probe=4987815b22) | Apr 21, 2024 |
| Lenovo        | B51-30 80LK                 | [c1435ee19d](https://bsd-hardware.info/?probe=c1435ee19d) | Apr 21, 2024 |
| Lenovo        | ThinkPad T400 6474E18       | [fcd3339ec5](https://bsd-hardware.info/?probe=fcd3339ec5) | Apr 21, 2024 |
| Lenovo        | ThinkPad T530 23942U1       | [a3b075c680](https://bsd-hardware.info/?probe=a3b075c680) | Apr 21, 2024 |
| HP            | OMEN by Laptop              | [e2bce481c8](https://bsd-hardware.info/?probe=e2bce481c8) | Apr 21, 2024 |
| Lenovo        | ThinkPad X230 Tablet 343... | [2400099ef5](https://bsd-hardware.info/?probe=2400099ef5) | Apr 19, 2024 |
| Lenovo        | ThinkPad X230 Tablet 343... | [0a6e2a3b33](https://bsd-hardware.info/?probe=0a6e2a3b33) | Apr 18, 2024 |
| Deciso        | NetBoard-A20                | [82519e798c](https://bsd-hardware.info/?probe=82519e798c) | Apr 18, 2024 |
| Deciso        | NetBoard-A10                | [c2e1f3af3b](https://bsd-hardware.info/?probe=c2e1f3af3b) | Apr 18, 2024 |
| Unknown       | Unknown                     | [5886bb9659](https://bsd-hardware.info/?probe=5886bb9659) | Apr 18, 2024 |
| F-Plus Mob... | FLAPTOP r                   | [150e135ba6](https://bsd-hardware.info/?probe=150e135ba6) | Apr 18, 2024 |
| SLIMBOOK      | PROX14-AMD                  | [b874667e73](https://bsd-hardware.info/?probe=b874667e73) | Apr 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | [20d7b596db](https://bsd-hardware.info/?probe=20d7b596db) | Apr 17, 2024 |
| Lenovo        | IdeaPad 500S-14ISK 80Q3     | [ec41825788](https://bsd-hardware.info/?probe=ec41825788) | Apr 17, 2024 |
| Apple         | MacBookPro8,1               | [6778d6844d](https://bsd-hardware.info/?probe=6778d6844d) | Apr 17, 2024 |
| LG Electro... | 17Z90Q-K.AAC7U1             | [8e3f536127](https://bsd-hardware.info/?probe=8e3f536127) | Apr 16, 2024 |
| Apple         | MacBookAir6,2               | [fc810b38b1](https://bsd-hardware.info/?probe=fc810b38b1) | Apr 16, 2024 |
| Samsung       | 340XAA/350XAA/550XAA        | [0de254980a](https://bsd-hardware.info/?probe=0de254980a) | Apr 16, 2024 |
| Lenovo        | ThinkPad T460 20FMA09CGE    | [c7219eb82e](https://bsd-hardware.info/?probe=c7219eb82e) | Apr 15, 2024 |
| ASUSTek       | VivoBook S14 X430UA         | [12764b3dba](https://bsd-hardware.info/?probe=12764b3dba) | Apr 14, 2024 |
| Lenovo        | ThinkPad E550 20DF005VRT    | [5c50bf1b60](https://bsd-hardware.info/?probe=5c50bf1b60) | Apr 14, 2024 |
| Dell          | Latitude 7490               | [38f6023f20](https://bsd-hardware.info/?probe=38f6023f20) | Apr 14, 2024 |
| Dell          | Vostro 3350                 | [abe739e6c2](https://bsd-hardware.info/?probe=abe739e6c2) | Apr 13, 2024 |
| Timi          | TM1612                      | [c139dfdf05](https://bsd-hardware.info/?probe=c139dfdf05) | Apr 13, 2024 |
| Apple         | MacBookAir7,2               | [a818576415](https://bsd-hardware.info/?probe=a818576415) | Apr 13, 2024 |
| HUAWEI        | MRGFG-XX                    | [94b19fd1c0](https://bsd-hardware.info/?probe=94b19fd1c0) | Apr 13, 2024 |
| Lenovo        | ThinkPad E490 20N9S48S00    | [a755c9e288](https://bsd-hardware.info/?probe=a755c9e288) | Apr 13, 2024 |
| ASUSTek       | N76VZ                       | [c1af06bf99](https://bsd-hardware.info/?probe=c1af06bf99) | Apr 12, 2024 |
| Lenovo        | ThinkBook 16 G6+ IMH 21L... | [7ae1277ce9](https://bsd-hardware.info/?probe=7ae1277ce9) | Apr 12, 2024 |
| HP            | ProBook 645 G3              | [ea10ac1f83](https://bsd-hardware.info/?probe=ea10ac1f83) | Apr 12, 2024 |
| Sony          | VGN-FZ4000E                 | [f3d6322ab6](https://bsd-hardware.info/?probe=f3d6322ab6) | Apr 12, 2024 |
| Lenovo        | ThinkPad T400 6475FA4       | [4318a318e5](https://bsd-hardware.info/?probe=4318a318e5) | Apr 11, 2024 |
| Dell          | Latitude 7490               | [e2af0367f5](https://bsd-hardware.info/?probe=e2af0367f5) | Apr 11, 2024 |
| Acer          | Aspire A314-35              | [6d4fa8616c](https://bsd-hardware.info/?probe=6d4fa8616c) | Apr 09, 2024 |
| System76      | Pangolin                    | [faa2fc0480](https://bsd-hardware.info/?probe=faa2fc0480) | Apr 09, 2024 |
| System76      | Pangolin                    | [e6feb0adcc](https://bsd-hardware.info/?probe=e6feb0adcc) | Apr 09, 2024 |
| Dell          | Latitude E5530 non-vPro     | [227f0ffb18](https://bsd-hardware.info/?probe=227f0ffb18) | Apr 09, 2024 |
| Apple         | MacBookAir7,2               | [d8288ba73a](https://bsd-hardware.info/?probe=d8288ba73a) | Apr 09, 2024 |
| Lenovo        | ThinkPad S5-S531 20B0000... | [cf65a95f23](https://bsd-hardware.info/?probe=cf65a95f23) | Apr 08, 2024 |
| Lenovo        | ThinkPad S5-S531 20B0000... | [bea4d85189](https://bsd-hardware.info/?probe=bea4d85189) | Apr 08, 2024 |
| Unknown       | Unknown                     | [ac12463cc2](https://bsd-hardware.info/?probe=ac12463cc2) | Apr 08, 2024 |
| Lenovo        | ThinkPad T470 20HES18R05    | [e081ad3727](https://bsd-hardware.info/?probe=e081ad3727) | Apr 08, 2024 |
| Apple         | MacBookAir7,2               | [435faeda9e](https://bsd-hardware.info/?probe=435faeda9e) | Apr 07, 2024 |
| Apple         | MacBookAir7,2               | [a26013b913](https://bsd-hardware.info/?probe=a26013b913) | Apr 05, 2024 |
| F-Plus Mob... | FLAPTOP r                   | [21768f1b7a](https://bsd-hardware.info/?probe=21768f1b7a) | Apr 04, 2024 |
| Unknown       | AHP958                      | [69cf299159](https://bsd-hardware.info/?probe=69cf299159) | Apr 04, 2024 |
| Dell          | XPS 15 7590                 | [1458ea15f4](https://bsd-hardware.info/?probe=1458ea15f4) | Apr 04, 2024 |
| Lenovo        | ThinkPad X260 20F60093US    | [3b7eee9621](https://bsd-hardware.info/?probe=3b7eee9621) | Apr 04, 2024 |
| Deciso        | NetBoard-A20                | [f6d9d3eaf2](https://bsd-hardware.info/?probe=f6d9d3eaf2) | Apr 03, 2024 |
| Samsung       | 100NZC                      | [2b36397928](https://bsd-hardware.info/?probe=2b36397928) | Apr 03, 2024 |
| Acer          | Aspire V5-431               | [9abe9b5007](https://bsd-hardware.info/?probe=9abe9b5007) | Apr 03, 2024 |
| Deciso        | NetBoard-A10                | [659c975065](https://bsd-hardware.info/?probe=659c975065) | Apr 02, 2024 |
| Dell          | Latitude E5540              | [108e2acb98](https://bsd-hardware.info/?probe=108e2acb98) | Apr 01, 2024 |
| Lenovo        | ThinkPad W530 2447GH2       | [0cb3f41765](https://bsd-hardware.info/?probe=0cb3f41765) | Apr 01, 2024 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [0ae72ec0ff](https://bsd-hardware.info/?probe=0ae72ec0ff) | Mar 31, 2024 |
| Deciso        | NetBoard-A20                | [0b84a8b2a6](https://bsd-hardware.info/?probe=0b84a8b2a6) | Mar 31, 2024 |
| Shuttle       | DS77U                       | [1d7eca66fe](https://bsd-hardware.info/?probe=1d7eca66fe) | Mar 31, 2024 |
| ASUSTek       | K43E                        | [f35f5d82f5](https://bsd-hardware.info/?probe=f35f5d82f5) | Mar 31, 2024 |
| Dell          | Latitude 5480               | [ba2a2a829e](https://bsd-hardware.info/?probe=ba2a2a829e) | Mar 31, 2024 |
| Apple         | MacBookAir3,1               | [b6dc892e24](https://bsd-hardware.info/?probe=b6dc892e24) | Mar 31, 2024 |
| Apple         | MacBookAir3,1               | [4a80e4b570](https://bsd-hardware.info/?probe=4a80e4b570) | Mar 31, 2024 |
| Apple         | MacBookAir7,2               | [a596a6f2fc](https://bsd-hardware.info/?probe=a596a6f2fc) | Mar 30, 2024 |
| Lenovo        | V15 G3 IAP 82TT             | [202a277c32](https://bsd-hardware.info/?probe=202a277c32) | Mar 29, 2024 |
| HUAWEI        | BOHB-WAX9                   | [b46f6ead5d](https://bsd-hardware.info/?probe=b46f6ead5d) | Mar 28, 2024 |
| Acer          | Aspire 4730Z                | [18c48b4f53](https://bsd-hardware.info/?probe=18c48b4f53) | Mar 28, 2024 |
| Toshiba       | Satellite C645              | [a5d1838130](https://bsd-hardware.info/?probe=a5d1838130) | Mar 28, 2024 |
| Shuttle       | DS77U                       | [b065bf5918](https://bsd-hardware.info/?probe=b065bf5918) | Mar 27, 2024 |
| Acer          | Aspire 7730Z                | [7ee3036a24](https://bsd-hardware.info/?probe=7ee3036a24) | Mar 27, 2024 |
| Fujitsu       | LIFEBOOK U727               | [76e6dff995](https://bsd-hardware.info/?probe=76e6dff995) | Mar 27, 2024 |
| Lenovo        | N22 80S6                    | [7f8b876a83](https://bsd-hardware.info/?probe=7f8b876a83) | Mar 26, 2024 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | [6891d04d9b](https://bsd-hardware.info/?probe=6891d04d9b) | Mar 26, 2024 |
| Apple         | MacBookAir7,2               | [a5003ca56a](https://bsd-hardware.info/?probe=a5003ca56a) | Mar 25, 2024 |
| Lenovo        | G510 20238                  | [faf771068a](https://bsd-hardware.info/?probe=faf771068a) | Mar 25, 2024 |
| Dell          | Latitude 5580               | [b1969a4408](https://bsd-hardware.info/?probe=b1969a4408) | Mar 25, 2024 |
| MSI           | MS-N014                     | [372cc157f0](https://bsd-hardware.info/?probe=372cc157f0) | Mar 24, 2024 |
| Micro Comp... | Venus series                | [8733a604dc](https://bsd-hardware.info/?probe=8733a604dc) | Mar 24, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [0fbac8264b](https://bsd-hardware.info/?probe=0fbac8264b) | Mar 23, 2024 |
| eMachines     | E525                        | [3c06a422b8](https://bsd-hardware.info/?probe=3c06a422b8) | Mar 23, 2024 |
| HP            | OMEN Laptop 15-ek0xxx       | [f4dde6ddf5](https://bsd-hardware.info/?probe=f4dde6ddf5) | Mar 22, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [25a92fc367](https://bsd-hardware.info/?probe=25a92fc367) | Mar 22, 2024 |
| Deciso        | NetBoard-A20                | [f5341b37b3](https://bsd-hardware.info/?probe=f5341b37b3) | Mar 21, 2024 |
| Deciso        | OPNsense Appliance          | [8283ee7c1b](https://bsd-hardware.info/?probe=8283ee7c1b) | Mar 21, 2024 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [6e8c7ec804](https://bsd-hardware.info/?probe=6e8c7ec804) | Mar 21, 2024 |
| Deciso        | DEC2700 - OPNsense Appli... | [7617a6faa1](https://bsd-hardware.info/?probe=7617a6faa1) | Mar 19, 2024 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [db1d3cd098](https://bsd-hardware.info/?probe=db1d3cd098) | Mar 19, 2024 |
| ASUSTek       | X550CA                      | [ff92192d22](https://bsd-hardware.info/?probe=ff92192d22) | Mar 19, 2024 |
| HP            | ZBook 17 G2                 | [8a5397997e](https://bsd-hardware.info/?probe=8a5397997e) | Mar 18, 2024 |
| ASUSTek       | K52JT                       | [c774d0e3a0](https://bsd-hardware.info/?probe=c774d0e3a0) | Mar 18, 2024 |
| HP            | EliteBook 8470p             | [51841c9dfd](https://bsd-hardware.info/?probe=51841c9dfd) | Mar 17, 2024 |
| Dell          | Latitude D830               | [832440d0c3](https://bsd-hardware.info/?probe=832440d0c3) | Mar 17, 2024 |
| Google        | Cave                        | [d9df48c781](https://bsd-hardware.info/?probe=d9df48c781) | Mar 16, 2024 |
| Apple         | MacBookPro11,1              | [58369a2ff3](https://bsd-hardware.info/?probe=58369a2ff3) | Mar 16, 2024 |
| Lenovo        | G580 20150                  | [1a072e681a](https://bsd-hardware.info/?probe=1a072e681a) | Mar 15, 2024 |
| Lenovo        | ThinkPad X220 429147U       | [0644799933](https://bsd-hardware.info/?probe=0644799933) | Mar 15, 2024 |
| Acer          | Aspire 4730Z                | [c2025d1b60](https://bsd-hardware.info/?probe=c2025d1b60) | Mar 15, 2024 |
| Lenovo        | IdeaPad 500-14ISK 80NS      | [34ab895e86](https://bsd-hardware.info/?probe=34ab895e86) | Mar 15, 2024 |
| Maibenben     | MaiBook M                   | [48e337257c](https://bsd-hardware.info/?probe=48e337257c) | Mar 14, 2024 |
| Apple         | MacBookAir7,2               | [58cc0f695b](https://bsd-hardware.info/?probe=58cc0f695b) | Mar 14, 2024 |
| ASUSTek       | K43E                        | [1bcbc3c82b](https://bsd-hardware.info/?probe=1bcbc3c82b) | Mar 14, 2024 |
| Dell          | Inspiron 15 3511            | [7ac9f4bd85](https://bsd-hardware.info/?probe=7ac9f4bd85) | Mar 14, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | [e97bd00aad](https://bsd-hardware.info/?probe=e97bd00aad) | Mar 13, 2024 |
| TULPAR        | A5 V20.3                    | [476d91b2cf](https://bsd-hardware.info/?probe=476d91b2cf) | Mar 13, 2024 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [4b52e91e24](https://bsd-hardware.info/?probe=4b52e91e24) | Mar 13, 2024 |
| Acer          | Aspire V5-573G              | [59445c5f19](https://bsd-hardware.info/?probe=59445c5f19) | Mar 12, 2024 |
| Framework     | Laptop                      | [2c49c1b561](https://bsd-hardware.info/?probe=2c49c1b561) | Mar 12, 2024 |
| Lenovo        | ThinkPad T420 4236JY2       | [0111e4442e](https://bsd-hardware.info/?probe=0111e4442e) | Mar 11, 2024 |
| Acer          | Nitro AN16-41               | [6ffc9c7b00](https://bsd-hardware.info/?probe=6ffc9c7b00) | Mar 11, 2024 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [6b569c8620](https://bsd-hardware.info/?probe=6b569c8620) | Mar 11, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [93771fbea1](https://bsd-hardware.info/?probe=93771fbea1) | Mar 11, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [322c6ac646](https://bsd-hardware.info/?probe=322c6ac646) | Mar 11, 2024 |
| MSI           | Bravo 15 C7VFKP             | [4efb48cb1c](https://bsd-hardware.info/?probe=4efb48cb1c) | Mar 11, 2024 |
| Lenovo        | ThinkPad X260 20F60097US    | [5fa2016fc1](https://bsd-hardware.info/?probe=5fa2016fc1) | Mar 11, 2024 |
| Acer          | Aspire A514-54              | [926fbd1fcf](https://bsd-hardware.info/?probe=926fbd1fcf) | Mar 11, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [0ceb5cfbf8](https://bsd-hardware.info/?probe=0ceb5cfbf8) | Mar 10, 2024 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [fd60868096](https://bsd-hardware.info/?probe=fd60868096) | Mar 10, 2024 |
| Deciso        | NetBoard-A20                | [1840f71538](https://bsd-hardware.info/?probe=1840f71538) | Mar 10, 2024 |
| Dell          | Latitude E6220              | [5a42aa442f](https://bsd-hardware.info/?probe=5a42aa442f) | Mar 09, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [637e2678c5](https://bsd-hardware.info/?probe=637e2678c5) | Mar 09, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [f6e67c7e6e](https://bsd-hardware.info/?probe=f6e67c7e6e) | Mar 09, 2024 |
| HP            | Compaq Presario C700        | [ae4a5bc366](https://bsd-hardware.info/?probe=ae4a5bc366) | Mar 09, 2024 |
| Deciso        | NetBoard-A20                | [2e0ce432cb](https://bsd-hardware.info/?probe=2e0ce432cb) | Mar 07, 2024 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [7158ba18d1](https://bsd-hardware.info/?probe=7158ba18d1) | Mar 07, 2024 |
| Dell          | XPS 13 9305                 | [7cc4588e07](https://bsd-hardware.info/?probe=7cc4588e07) | Mar 07, 2024 |
| Dell          | Latitude 7220 Rugged Ext... | [d882577127](https://bsd-hardware.info/?probe=d882577127) | Mar 07, 2024 |
| Google        | Droid                       | [47f0dcc73c](https://bsd-hardware.info/?probe=47f0dcc73c) | Mar 06, 2024 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | [ba0295b8ea](https://bsd-hardware.info/?probe=ba0295b8ea) | Mar 05, 2024 |
| HUAWEI        | CREFG-XX                    | [b16b7180ee](https://bsd-hardware.info/?probe=b16b7180ee) | Mar 05, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop S560... | [fa7a3ad31d](https://bsd-hardware.info/?probe=fa7a3ad31d) | Mar 05, 2024 |
| Lenovo        | ThinkPad T490 20N3S4PX02    | [0dc4820d7e](https://bsd-hardware.info/?probe=0dc4820d7e) | Mar 05, 2024 |
| Lenovo        | ThinkPad T490 20N3S4PX02    | [c3f8fdaebb](https://bsd-hardware.info/?probe=c3f8fdaebb) | Mar 05, 2024 |
| Lenovo        | ThinkPad T480s 20L8S45W0... | [6c6fcc3427](https://bsd-hardware.info/?probe=6c6fcc3427) | Mar 04, 2024 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [a716cc542a](https://bsd-hardware.info/?probe=a716cc542a) | Mar 04, 2024 |
| Maibenben     | MaiBook X series            | [2a58491971](https://bsd-hardware.info/?probe=2a58491971) | Mar 03, 2024 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [3653895b8e](https://bsd-hardware.info/?probe=3653895b8e) | Mar 03, 2024 |
| Dell          | Inspiron 5559               | [2010f287bf](https://bsd-hardware.info/?probe=2010f287bf) | Mar 03, 2024 |
| ASUSTek       | K52JT                       | [c5462e962c](https://bsd-hardware.info/?probe=c5462e962c) | Mar 03, 2024 |
| Toshiba       | Satellite P300              | [3ecfa61763](https://bsd-hardware.info/?probe=3ecfa61763) | Mar 03, 2024 |
| Lenovo        | ThinkPad X230 23254S6       | [cae99ac427](https://bsd-hardware.info/?probe=cae99ac427) | Mar 03, 2024 |
| Acer          | Aspire A715-75G             | [415aa43c5c](https://bsd-hardware.info/?probe=415aa43c5c) | Mar 02, 2024 |
| Apple         | MacBookPro8,3               | [89647876db](https://bsd-hardware.info/?probe=89647876db) | Mar 02, 2024 |
| Lenovo        | ThinkPad T480s 20L8S45W0... | [b35f962bce](https://bsd-hardware.info/?probe=b35f962bce) | Mar 01, 2024 |
| HP            | Notebook                    | [15839305ee](https://bsd-hardware.info/?probe=15839305ee) | Mar 01, 2024 |
| ASUSTek       | X550EA                      | [42b10a3b6a](https://bsd-hardware.info/?probe=42b10a3b6a) | Mar 01, 2024 |
| Panasonic     | CFSX4-1                     | [5821783809](https://bsd-hardware.info/?probe=5821783809) | Mar 01, 2024 |
| Lenovo        | ThinkPad T495 20NJ0000US    | [052c7d6fdf](https://bsd-hardware.info/?probe=052c7d6fdf) | Mar 01, 2024 |
| Deciso        | NetBoard-A10                | [7f1440d0dd](https://bsd-hardware.info/?probe=7f1440d0dd) | Feb 28, 2024 |
| Itautec       | Infoway                     | [35399f6e75](https://bsd-hardware.info/?probe=35399f6e75) | Feb 28, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [9c88473675](https://bsd-hardware.info/?probe=9c88473675) | Feb 27, 2024 |
| Lenovo        | B40-30 80F1                 | [9e435212e2](https://bsd-hardware.info/?probe=9e435212e2) | Feb 27, 2024 |
| Deciso        | NetBoard-A20                | [7c73382c9d](https://bsd-hardware.info/?probe=7c73382c9d) | Feb 26, 2024 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [4d63500465](https://bsd-hardware.info/?probe=4d63500465) | Feb 26, 2024 |
| IP3 Techno... | ARN39E                      | [e6405ae506](https://bsd-hardware.info/?probe=e6405ae506) | Feb 26, 2024 |
| Apple         | MacBookPro12,1              | [736c13e863](https://bsd-hardware.info/?probe=736c13e863) | Feb 25, 2024 |
| Dell          | Precision M4800             | [2fb6088a6c](https://bsd-hardware.info/?probe=2fb6088a6c) | Feb 25, 2024 |
| Dell          | Precision M4800             | [8b92089beb](https://bsd-hardware.info/?probe=8b92089beb) | Feb 25, 2024 |
| ASUSTek       | X550EA                      | [a49aa7d3d8](https://bsd-hardware.info/?probe=a49aa7d3d8) | Feb 24, 2024 |
| Acer          | Aspire A315-22              | [809d582231](https://bsd-hardware.info/?probe=809d582231) | Feb 24, 2024 |
| Lenovo        | G50-80 80E5                 | [518698bce2](https://bsd-hardware.info/?probe=518698bce2) | Feb 24, 2024 |
| Lenovo        | ThinkPad X220 4290KV8       | [9bc55d7f8a](https://bsd-hardware.info/?probe=9bc55d7f8a) | Feb 23, 2024 |
| Dell          | Inspiron 5559               | [ac72a9a34a](https://bsd-hardware.info/?probe=ac72a9a34a) | Feb 23, 2024 |
| HP            | ProBook 450 G3              | [8e96322919](https://bsd-hardware.info/?probe=8e96322919) | Feb 22, 2024 |
| HP            | ProBook 430 G4              | [9d55da54e7](https://bsd-hardware.info/?probe=9d55da54e7) | Feb 22, 2024 |
| Dell          | Latitude E7250              | [ffc8dcf395](https://bsd-hardware.info/?probe=ffc8dcf395) | Feb 22, 2024 |
| Deciso        | NetBoard-A10                | [0b83b42575](https://bsd-hardware.info/?probe=0b83b42575) | Feb 22, 2024 |
| Lenovo        | XiaoXinAir 14+ ACN 2021 ... | [5702ec8e8e](https://bsd-hardware.info/?probe=5702ec8e8e) | Feb 22, 2024 |
| Dell          | Latitude E6540              | [92ba9b26e1](https://bsd-hardware.info/?probe=92ba9b26e1) | Feb 21, 2024 |
| Deciso        | NetBoard-A10                | [85eddb97a1](https://bsd-hardware.info/?probe=85eddb97a1) | Feb 21, 2024 |
| HP            | Laptop 15-bs0xx             | [d64816723d](https://bsd-hardware.info/?probe=d64816723d) | Feb 20, 2024 |
| Infinix       | INBook X1                   | [dd3185320b](https://bsd-hardware.info/?probe=dd3185320b) | Feb 20, 2024 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [3cd6bbf6be](https://bsd-hardware.info/?probe=3cd6bbf6be) | Feb 19, 2024 |
| Dell          | Precision 7520              | [bd40dd5305](https://bsd-hardware.info/?probe=bd40dd5305) | Feb 19, 2024 |
| Intel         | Jasper Lake Client Platf... | [6a041adf7a](https://bsd-hardware.info/?probe=6a041adf7a) | Feb 19, 2024 |
| Lenovo        | ThinkPad T410 2518A37       | [b2515cf7fb](https://bsd-hardware.info/?probe=b2515cf7fb) | Feb 19, 2024 |
| Dell          | Latitude E5510              | [4155c54a6c](https://bsd-hardware.info/?probe=4155c54a6c) | Feb 19, 2024 |
| Dell          | Latitude E5510              | [1bc1ac66c3](https://bsd-hardware.info/?probe=1bc1ac66c3) | Feb 18, 2024 |
| Dell          | Latitude E6430              | [1f9f417c2f](https://bsd-hardware.info/?probe=1f9f417c2f) | Feb 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [a7aada8678](https://bsd-hardware.info/?probe=a7aada8678) | Feb 17, 2024 |
| Deciso        | NetBoard-A20                | [ebbe4a0d21](https://bsd-hardware.info/?probe=ebbe4a0d21) | Feb 17, 2024 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [fb1f5f8545](https://bsd-hardware.info/?probe=fb1f5f8545) | Feb 16, 2024 |
| Dell          | Vostro 15-3568              | [cc65de13e8](https://bsd-hardware.info/?probe=cc65de13e8) | Feb 16, 2024 |
| Dell          | Latitude E7470              | [3a08bc08be](https://bsd-hardware.info/?probe=3a08bc08be) | Feb 15, 2024 |
| Google        | Ultima                      | [732adeb5e4](https://bsd-hardware.info/?probe=732adeb5e4) | Feb 15, 2024 |
| Shuttle       | NC02U                       | [d559b380f0](https://bsd-hardware.info/?probe=d559b380f0) | Feb 14, 2024 |
| Dell          | Inspiron 3558               | [e0e665c1b5](https://bsd-hardware.info/?probe=e0e665c1b5) | Feb 13, 2024 |
| Lenovo        | ThinkPad T470 20HES0EV0A    | [05ecc99fe8](https://bsd-hardware.info/?probe=05ecc99fe8) | Feb 13, 2024 |
| MSI           | MS-N014                     | [f731e6df0a](https://bsd-hardware.info/?probe=f731e6df0a) | Feb 13, 2024 |
| Lenovo        | ThinkPad T450 20BU000GUS    | [e1d99a4966](https://bsd-hardware.info/?probe=e1d99a4966) | Feb 13, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [5306df5921](https://bsd-hardware.info/?probe=5306df5921) | Feb 12, 2024 |
| Notebook      | N960Kx                      | [4e83c12f96](https://bsd-hardware.info/?probe=4e83c12f96) | Feb 12, 2024 |
| Sony          | Unknown                     | [c0013719ab](https://bsd-hardware.info/?probe=c0013719ab) | Feb 12, 2024 |
| Sony          | Unknown                     | [a17ecdd804](https://bsd-hardware.info/?probe=a17ecdd804) | Feb 12, 2024 |
| Lenovo        | ThinkPad T410 2522WAR       | [caccf07908](https://bsd-hardware.info/?probe=caccf07908) | Feb 12, 2024 |
| Unknown       | Unknown                     | [2af11d5bbf](https://bsd-hardware.info/?probe=2af11d5bbf) | Feb 11, 2024 |
| Lenovo        | Yoga 900S-12ISK 80ML        | [47f57b0893](https://bsd-hardware.info/?probe=47f57b0893) | Feb 11, 2024 |
| Lenovo        | Yoga 900S-12ISK 80ML        | [5315513827](https://bsd-hardware.info/?probe=5315513827) | Feb 11, 2024 |
| Deciso        | NetBoard-A10                | [8403713b4f](https://bsd-hardware.info/?probe=8403713b4f) | Feb 10, 2024 |
| Dell          | Latitude 7490               | [32828d5d84](https://bsd-hardware.info/?probe=32828d5d84) | Feb 10, 2024 |
| HP            | ProBook 440 G8 Notebook ... | [977c74f4c0](https://bsd-hardware.info/?probe=977c74f4c0) | Feb 08, 2024 |
| Unknown       | Unknown                     | [f5ad3c2512](https://bsd-hardware.info/?probe=f5ad3c2512) | Feb 08, 2024 |
| Micro Comp... | Venus series                | [20e602834b](https://bsd-hardware.info/?probe=20e602834b) | Feb 08, 2024 |
| Micro Comp... | Venus series                | [3a2455558f](https://bsd-hardware.info/?probe=3a2455558f) | Feb 08, 2024 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | [2a4911715a](https://bsd-hardware.info/?probe=2a4911715a) | Feb 07, 2024 |
| Lenovo        | ThinkPad T480 20L6SDA400    | [4934e88205](https://bsd-hardware.info/?probe=4934e88205) | Feb 07, 2024 |
| Panasonic     | CF-52VDA131M                | [1ebdac9598](https://bsd-hardware.info/?probe=1ebdac9598) | Feb 07, 2024 |
| Deciso        | NetBoard-A10                | [6cfe3230e8](https://bsd-hardware.info/?probe=6cfe3230e8) | Feb 07, 2024 |
| Lenovo        | ThinkPad Helix 2nd 20CHS... | [5b06b87ef0](https://bsd-hardware.info/?probe=5b06b87ef0) | Feb 06, 2024 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [e7c9d50432](https://bsd-hardware.info/?probe=e7c9d50432) | Feb 05, 2024 |
| Unknown       | Unknown                     | [eec243257a](https://bsd-hardware.info/?probe=eec243257a) | Feb 05, 2024 |
| Apple         | MacBookPro11,1              | [c77173c2f3](https://bsd-hardware.info/?probe=c77173c2f3) | Feb 04, 2024 |
| ASUSTek       | K52F                        | [bc31c4707c](https://bsd-hardware.info/?probe=bc31c4707c) | Feb 04, 2024 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [6a78256797](https://bsd-hardware.info/?probe=6a78256797) | Feb 04, 2024 |
| Deciso        | NetBoard-A10                | [118bac872e](https://bsd-hardware.info/?probe=118bac872e) | Feb 03, 2024 |
| Panasonic     | CF-52PGNBX2M                | [401aeae642](https://bsd-hardware.info/?probe=401aeae642) | Feb 03, 2024 |
| ASUSTek       | F8Vr                        | [2f3b6a6089](https://bsd-hardware.info/?probe=2f3b6a6089) | Feb 03, 2024 |
| Micro Comp... | Venus series                | [2fbda08743](https://bsd-hardware.info/?probe=2fbda08743) | Feb 03, 2024 |
| Micro Comp... | Venus series                | [e7693b7781](https://bsd-hardware.info/?probe=e7693b7781) | Feb 03, 2024 |
| ASUSTek       | K52F                        | [9022031518](https://bsd-hardware.info/?probe=9022031518) | Feb 03, 2024 |
| Apple         | MacBookPro8,2               | [95f19036db](https://bsd-hardware.info/?probe=95f19036db) | Feb 03, 2024 |
| Deciso        | Netboard A20                | [53a429612f](https://bsd-hardware.info/?probe=53a429612f) | Feb 02, 2024 |
| Acer          | Aspire A315-22              | [0bd7a59dfe](https://bsd-hardware.info/?probe=0bd7a59dfe) | Feb 02, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [0e644c21cc](https://bsd-hardware.info/?probe=0e644c21cc) | Feb 02, 2024 |
| Dell          | XPS 15 9530                 | [f9481e59b6](https://bsd-hardware.info/?probe=f9481e59b6) | Feb 01, 2024 |
| Lenovo        | V14 G2 ITL 82NM             | [952fa413fe](https://bsd-hardware.info/?probe=952fa413fe) | Feb 01, 2024 |
| TUXEDO        | Aura 15 Gen1                | [4768e0001d](https://bsd-hardware.info/?probe=4768e0001d) | Feb 01, 2024 |
| Apple         | MacBookPro14,1              | [c8d68d0eec](https://bsd-hardware.info/?probe=c8d68d0eec) | Feb 01, 2024 |
| Acer          | TravelMate P645-SG          | [5765a3732f](https://bsd-hardware.info/?probe=5765a3732f) | Jan 31, 2024 |
| Acer          | TravelMate P645-SG          | [32dc9a4b1b](https://bsd-hardware.info/?probe=32dc9a4b1b) | Jan 31, 2024 |
| ASUSTek       | K50IJ                       | [b5cc2ab7ff](https://bsd-hardware.info/?probe=b5cc2ab7ff) | Jan 31, 2024 |
| Lenovo        | ThinkBook 14 G6 IRL 21KG    | [a1fc491614](https://bsd-hardware.info/?probe=a1fc491614) | Jan 31, 2024 |
| ASUSTek       | K50IJ                       | [a952b43f14](https://bsd-hardware.info/?probe=a952b43f14) | Jan 31, 2024 |
| Lenovo        | V14 G2 ITL 82NM             | [b66edf2033](https://bsd-hardware.info/?probe=b66edf2033) | Jan 31, 2024 |
| Razer         | Blade 14 (2022) - RZ09-0... | [a2d3483ef9](https://bsd-hardware.info/?probe=a2d3483ef9) | Jan 30, 2024 |
| Fujitsu       | LIFEBOOK LH772              | [afe4fb6608](https://bsd-hardware.info/?probe=afe4fb6608) | Jan 30, 2024 |
| Fujitsu       | LIFEBOOK LH772              | [491823db1e](https://bsd-hardware.info/?probe=491823db1e) | Jan 30, 2024 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [e747b9066e](https://bsd-hardware.info/?probe=e747b9066e) | Jan 29, 2024 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [7e24e6c0f2](https://bsd-hardware.info/?probe=7e24e6c0f2) | Jan 29, 2024 |
| HP            | OMEN by Laptop 17-ck0xxx    | [8cad8e084d](https://bsd-hardware.info/?probe=8cad8e084d) | Jan 28, 2024 |
| Lenovo        | ThinkPad T460 20FMS1VA1D    | [03d11c45e9](https://bsd-hardware.info/?probe=03d11c45e9) | Jan 28, 2024 |
| Acer          | Nitro AN515-54              | [94f04895fe](https://bsd-hardware.info/?probe=94f04895fe) | Jan 27, 2024 |
| Panasonic     | CFSX4-1                     | [d998c9373a](https://bsd-hardware.info/?probe=d998c9373a) | Jan 25, 2024 |
| Intel         | H81U                        | [9b68a7c006](https://bsd-hardware.info/?probe=9b68a7c006) | Jan 25, 2024 |
| Dell          | Precision M4700             | [05a9a26c16](https://bsd-hardware.info/?probe=05a9a26c16) | Jan 24, 2024 |
| Intel         | H81U                        | [c36eaa9c79](https://bsd-hardware.info/?probe=c36eaa9c79) | Jan 24, 2024 |
| HP            | ZBook 17 G2                 | [db2c57b081](https://bsd-hardware.info/?probe=db2c57b081) | Jan 24, 2024 |
| Acer          | Nitro AN515-54              | [28539d7eb4](https://bsd-hardware.info/?probe=28539d7eb4) | Jan 24, 2024 |
| Lenovo        | Legion Y9000X 2020 81TH     | [3711b11e8a](https://bsd-hardware.info/?probe=3711b11e8a) | Jan 23, 2024 |
| Acer          | TravelMate B115-M           | [d7a78aa2cf](https://bsd-hardware.info/?probe=d7a78aa2cf) | Jan 22, 2024 |
| ASUSTek       | X555LAB                     | [c396fcc8d9](https://bsd-hardware.info/?probe=c396fcc8d9) | Jan 22, 2024 |
| HP            | ProBook 650 G1              | [50888a6e05](https://bsd-hardware.info/?probe=50888a6e05) | Jan 22, 2024 |
| Unknown       | Unknown                     | [6fe553c729](https://bsd-hardware.info/?probe=6fe553c729) | Jan 21, 2024 |
| Unknown       | Unknown                     | [e85605ed72](https://bsd-hardware.info/?probe=e85605ed72) | Jan 21, 2024 |
| Dell          | Latitude 7320 Detachable    | [d29b86c141](https://bsd-hardware.info/?probe=d29b86c141) | Jan 21, 2024 |
| Apple         | MacBookAir4,1               | [f51a396e5e](https://bsd-hardware.info/?probe=f51a396e5e) | Jan 21, 2024 |
| Dell          | Latitude E7450              | [f2216c5d0f](https://bsd-hardware.info/?probe=f2216c5d0f) | Jan 21, 2024 |
| Samsung       | 340XAA/350XAA/550XAA        | [2065609a0c](https://bsd-hardware.info/?probe=2065609a0c) | Jan 19, 2024 |
| Samsung       | 340XAA/350XAA/550XAA        | [62abffe402](https://bsd-hardware.info/?probe=62abffe402) | Jan 19, 2024 |
| BESSTAR Te... | U820                        | [9d1b8fbbd5](https://bsd-hardware.info/?probe=9d1b8fbbd5) | Jan 18, 2024 |
| BESSTAR Te... | U820                        | [7e38f4e795](https://bsd-hardware.info/?probe=7e38f4e795) | Jan 18, 2024 |
| Dell          | Latitude 7320 Detachable    | [b1f9acd523](https://bsd-hardware.info/?probe=b1f9acd523) | Jan 18, 2024 |
| Dell          | Latitude 7480               | [d9b4d836e7](https://bsd-hardware.info/?probe=d9b4d836e7) | Jan 17, 2024 |
| Lenovo        | ThinkPad W520 4284GZ1       | [32bc5e823d](https://bsd-hardware.info/?probe=32bc5e823d) | Jan 17, 2024 |
| Lenovo        | ThinkPad X220 42912Z1       | [1abc94b4b1](https://bsd-hardware.info/?probe=1abc94b4b1) | Jan 17, 2024 |
| Lenovo        | G50-80 80E5                 | [2330f23f1a](https://bsd-hardware.info/?probe=2330f23f1a) | Jan 16, 2024 |
| Dell          | Precision 7510              | [b5d52d8750](https://bsd-hardware.info/?probe=b5d52d8750) | Jan 16, 2024 |
| Razer         | Blade 16 - RZ09-0483        | [d81973c8bc](https://bsd-hardware.info/?probe=d81973c8bc) | Jan 16, 2024 |
| HP            | Mini 210-1000               | [f25c646418](https://bsd-hardware.info/?probe=f25c646418) | Jan 16, 2024 |
| Star Labs     | StarBook                    | [1e903acb93](https://bsd-hardware.info/?probe=1e903acb93) | Jan 16, 2024 |
| LG Electro... | 16UD70R-G.AX59B             | [0b08d5b203](https://bsd-hardware.info/?probe=0b08d5b203) | Jan 16, 2024 |
| HP            | Mini 210-1000               | [fb086c3baa](https://bsd-hardware.info/?probe=fb086c3baa) | Jan 15, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [20090cb5c6](https://bsd-hardware.info/?probe=20090cb5c6) | Jan 15, 2024 |
| Deciso        | NetBoard-A20                | [76f9a185fe](https://bsd-hardware.info/?probe=76f9a185fe) | Jan 15, 2024 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [fcc009f8ba](https://bsd-hardware.info/?probe=fcc009f8ba) | Jan 15, 2024 |
| Samsung       | N150/N210/N220              | [92c052e0d7](https://bsd-hardware.info/?probe=92c052e0d7) | Jan 14, 2024 |
| Lenovo        | ThinkPad E490 20N9S2H000    | [d2cef66241](https://bsd-hardware.info/?probe=d2cef66241) | Jan 14, 2024 |
| Dell          | Latitude 7490               | [e2c44b78da](https://bsd-hardware.info/?probe=e2c44b78da) | Jan 14, 2024 |
| Apple         | MacBookAir4,1               | [b9653bc7d3](https://bsd-hardware.info/?probe=b9653bc7d3) | Jan 14, 2024 |
| Dell          | Latitude 7490               | [ed2a38e9f5](https://bsd-hardware.info/?probe=ed2a38e9f5) | Jan 13, 2024 |
| Micro Comp... | Venus series                | [fc242d0e50](https://bsd-hardware.info/?probe=fc242d0e50) | Jan 13, 2024 |
| Dell          | Latitude E5420              | [eabdd44efe](https://bsd-hardware.info/?probe=eabdd44efe) | Jan 13, 2024 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [d08f6339ae](https://bsd-hardware.info/?probe=d08f6339ae) | Jan 12, 2024 |
| Unknown       | Unknown                     | [4b22a105d7](https://bsd-hardware.info/?probe=4b22a105d7) | Jan 11, 2024 |
| Lenovo        | ThinkPad T14s Gen 4 21F6... | [79707e220e](https://bsd-hardware.info/?probe=79707e220e) | Jan 11, 2024 |
| ASUSTek       | X441UV                      | [6cdd70da49](https://bsd-hardware.info/?probe=6cdd70da49) | Jan 11, 2024 |
| Dell          | Inspiron 1525               | [e6c13bf584](https://bsd-hardware.info/?probe=e6c13bf584) | Jan 11, 2024 |
| HP            | 255 G7 Notebook PC          | [2c7e743906](https://bsd-hardware.info/?probe=2c7e743906) | Jan 10, 2024 |
| Deciso        | NetBoard-A20                | [aaadb904c1](https://bsd-hardware.info/?probe=aaadb904c1) | Jan 10, 2024 |
| HP            | 255 G7 Notebook PC          | [ef0d0a61f8](https://bsd-hardware.info/?probe=ef0d0a61f8) | Jan 10, 2024 |
| Dell          | Inspiron 1525               | [fa7b4f0216](https://bsd-hardware.info/?probe=fa7b4f0216) | Jan 10, 2024 |
| Rembrandt     | ARB928                      | [47621d7796](https://bsd-hardware.info/?probe=47621d7796) | Jan 10, 2024 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [0f475f8e5d](https://bsd-hardware.info/?probe=0f475f8e5d) | Jan 10, 2024 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [6b21d0ae92](https://bsd-hardware.info/?probe=6b21d0ae92) | Jan 09, 2024 |
| Dell          | Inspiron 14-3452            | [47ac3f7eaa](https://bsd-hardware.info/?probe=47ac3f7eaa) | Jan 09, 2024 |
| HP            | Pavilion g7                 | [25ccdb00f6](https://bsd-hardware.info/?probe=25ccdb00f6) | Jan 09, 2024 |
| HP            | Compaq 6510b (GM108UC#AB... | [7ed7da2383](https://bsd-hardware.info/?probe=7ed7da2383) | Jan 08, 2024 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [dab1edae0c](https://bsd-hardware.info/?probe=dab1edae0c) | Jan 08, 2024 |
| Lenovo        | ThinkPad L450 20DSS1S402    | [40b8a056f7](https://bsd-hardware.info/?probe=40b8a056f7) | Jan 07, 2024 |
| Unknown       | Unknown                     | [d840a2f953](https://bsd-hardware.info/?probe=d840a2f953) | Jan 07, 2024 |
| Dell          | Inspiron 5555               | [1449593b79](https://bsd-hardware.info/?probe=1449593b79) | Jan 07, 2024 |
| Dell          | XPS 15 9530                 | [13f09671ce](https://bsd-hardware.info/?probe=13f09671ce) | Jan 07, 2024 |
| HP            | Pavilion g6                 | [77f3d49b2e](https://bsd-hardware.info/?probe=77f3d49b2e) | Jan 06, 2024 |
| ASUSTek       | X551MA                      | [63dc88d57d](https://bsd-hardware.info/?probe=63dc88d57d) | Jan 06, 2024 |
| ASUSTek       | X551MA                      | [91eda59c82](https://bsd-hardware.info/?probe=91eda59c82) | Jan 06, 2024 |
| Deciso        | NetBoard-A20                | [cfcb03c18a](https://bsd-hardware.info/?probe=cfcb03c18a) | Jan 05, 2024 |
| Lenovo        | ThinkPad 11e 20D90020US     | [7d7f564886](https://bsd-hardware.info/?probe=7d7f564886) | Jan 05, 2024 |
| Apple         | MacBook5,1                  | [90346c6fe3](https://bsd-hardware.info/?probe=90346c6fe3) | Jan 04, 2024 |
| Lenovo        | G50-80 80E5                 | [a678ec59e8](https://bsd-hardware.info/?probe=a678ec59e8) | Jan 04, 2024 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [5c583e5a9d](https://bsd-hardware.info/?probe=5c583e5a9d) | Jan 04, 2024 |
| Lenovo        | ThinkPad X250 20CMS01M00    | [1f52525bb9](https://bsd-hardware.info/?probe=1f52525bb9) | Jan 04, 2024 |
| ASUSTek       | X441UV                      | [29b63ed6a8](https://bsd-hardware.info/?probe=29b63ed6a8) | Jan 04, 2024 |
| ASUSTek       | X555LB                      | [45a80466a3](https://bsd-hardware.info/?probe=45a80466a3) | Jan 04, 2024 |
| Dell          | XPS 15 7590                 | [67a65520e6](https://bsd-hardware.info/?probe=67a65520e6) | Jan 03, 2024 |
| Lenovo        | ThinkPad E495 20NE000BSP    | [9ed586661c](https://bsd-hardware.info/?probe=9ed586661c) | Jan 03, 2024 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [7ac885382c](https://bsd-hardware.info/?probe=7ac885382c) | Jan 03, 2024 |
| HP            | Laptop 15t-dy100            | [61130d2b74](https://bsd-hardware.info/?probe=61130d2b74) | Jan 03, 2024 |
| Unknown       | Unknown                     | [c1d43f83f4](https://bsd-hardware.info/?probe=c1d43f83f4) | Jan 02, 2024 |
| Lenovo        | ThinkPad T490s 20NX000MU... | [1271688c43](https://bsd-hardware.info/?probe=1271688c43) | Jan 02, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | [2ab7b9d6b2](https://bsd-hardware.info/?probe=2ab7b9d6b2) | Jan 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [77d8cc2e7c](https://bsd-hardware.info/?probe=77d8cc2e7c) | Jan 02, 2024 |
| Samsung       | R510/P510                   | [920e7e2d14](https://bsd-hardware.info/?probe=920e7e2d14) | Dec 31, 2023 |
| Dell          | Vostro V130                 | [44e78243c2](https://bsd-hardware.info/?probe=44e78243c2) | Dec 30, 2023 |
| Dell          | Vostro 5470                 | [56472e8f51](https://bsd-hardware.info/?probe=56472e8f51) | Dec 30, 2023 |
| HP            | EliteBook 2540p             | [c915c03729](https://bsd-hardware.info/?probe=c915c03729) | Dec 30, 2023 |
| Deciso        | NetBoard-A10                | [1545839e21](https://bsd-hardware.info/?probe=1545839e21) | Dec 29, 2023 |
| Deciso        | NetBoard-A10                | [66f7dd1f06](https://bsd-hardware.info/?probe=66f7dd1f06) | Dec 29, 2023 |
| Panasonic     | CFSX4-1                     | [e54393775b](https://bsd-hardware.info/?probe=e54393775b) | Dec 29, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [f34b5d84dd](https://bsd-hardware.info/?probe=f34b5d84dd) | Dec 28, 2023 |
| Deciso        | Netboard A20                | [c545672f6f](https://bsd-hardware.info/?probe=c545672f6f) | Dec 28, 2023 |
| Toshiba       | Satellite P300              | [4ddf360812](https://bsd-hardware.info/?probe=4ddf360812) | Dec 27, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | [0a2c02f944](https://bsd-hardware.info/?probe=0a2c02f944) | Dec 27, 2023 |
| Rembrandt     | ARB928                      | [c9a9bfd4aa](https://bsd-hardware.info/?probe=c9a9bfd4aa) | Dec 27, 2023 |
| Apple         | MacBookPro7,1               | [f43cf3565a](https://bsd-hardware.info/?probe=f43cf3565a) | Dec 27, 2023 |
| Acer          | Aspire E5-574               | [8b71e16af3](https://bsd-hardware.info/?probe=8b71e16af3) | Dec 27, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | [4b1250f831](https://bsd-hardware.info/?probe=4b1250f831) | Dec 26, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | [533a831b97](https://bsd-hardware.info/?probe=533a831b97) | Dec 26, 2023 |
| Apple         | MacBookAir6,2               | [47fdb04811](https://bsd-hardware.info/?probe=47fdb04811) | Dec 25, 2023 |
| Lenovo        | ThinkPad X131e 33672T9      | [93f964da45](https://bsd-hardware.info/?probe=93f964da45) | Dec 25, 2023 |
| AMI           | Intel                       | [df557e3915](https://bsd-hardware.info/?probe=df557e3915) | Dec 25, 2023 |
| Lenovo        | ThinkPad T480 20L6S8LW00    | [b6c3c05155](https://bsd-hardware.info/?probe=b6c3c05155) | Dec 25, 2023 |
| Lenovo        | ThinkPad X250 20CLS8Q601    | [2c52684baa](https://bsd-hardware.info/?probe=2c52684baa) | Dec 25, 2023 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [a740494857](https://bsd-hardware.info/?probe=a740494857) | Dec 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [278ab700ae](https://bsd-hardware.info/?probe=278ab700ae) | Dec 24, 2023 |
| Dell          | Inspiron MM061              | [7e4cee9689](https://bsd-hardware.info/?probe=7e4cee9689) | Dec 24, 2023 |
| IGEL Techn... | H830C                       | [da070c0348](https://bsd-hardware.info/?probe=da070c0348) | Dec 24, 2023 |
| eMachines     | eM350                       | [00d1d0c359](https://bsd-hardware.info/?probe=00d1d0c359) | Dec 23, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [7ca1ae0c93](https://bsd-hardware.info/?probe=7ca1ae0c93) | Dec 23, 2023 |
| Dell          | Precision 5510              | [4bad5ad995](https://bsd-hardware.info/?probe=4bad5ad995) | Dec 23, 2023 |
| Dell          | Precision 7720              | [a30d05e373](https://bsd-hardware.info/?probe=a30d05e373) | Dec 23, 2023 |
| Lenovo        | ThinkPad T480 20L6S8LW00    | [32c06c5669](https://bsd-hardware.info/?probe=32c06c5669) | Dec 23, 2023 |
| TULPAR        | A5 V20.3                    | [89b65e7036](https://bsd-hardware.info/?probe=89b65e7036) | Dec 23, 2023 |
| Dell          | Latitude E7240              | [f2229124bf](https://bsd-hardware.info/?probe=f2229124bf) | Dec 22, 2023 |
| Lenovo        | ThinkPad A485 20MU000VUS    | [98663cbfef](https://bsd-hardware.info/?probe=98663cbfef) | Dec 22, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [85ec93f4cd](https://bsd-hardware.info/?probe=85ec93f4cd) | Dec 22, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [34f3eb8059](https://bsd-hardware.info/?probe=34f3eb8059) | Dec 22, 2023 |
| HP            | ProBook 455 G7              | [11764c4c5e](https://bsd-hardware.info/?probe=11764c4c5e) | Dec 20, 2023 |
| Clevo         | W240BU                      | [19bb603cab](https://bsd-hardware.info/?probe=19bb603cab) | Dec 20, 2023 |
| Apple         | PowerBook3,5                | [53313e58d8](https://bsd-hardware.info/?probe=53313e58d8) | Dec 20, 2023 |
| Deciso        | NetBoard-A10                | [c728132d77](https://bsd-hardware.info/?probe=c728132d77) | Dec 20, 2023 |
| Lenovo        | ThinkPad T490s 20NYS4HL1... | [97fb2e025e](https://bsd-hardware.info/?probe=97fb2e025e) | Dec 20, 2023 |
| Apple         | MacBookPro9,2               | [851f118bd5](https://bsd-hardware.info/?probe=851f118bd5) | Dec 19, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [02bf1d2cd4](https://bsd-hardware.info/?probe=02bf1d2cd4) | Dec 19, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [5281bb9e20](https://bsd-hardware.info/?probe=5281bb9e20) | Dec 19, 2023 |
| Dell          | Latitude E7240              | [7d5e8bcb8a](https://bsd-hardware.info/?probe=7d5e8bcb8a) | Dec 19, 2023 |
| Lenovo        | ThinkPad X220 4291H77       | [2fe3ff7e06](https://bsd-hardware.info/?probe=2fe3ff7e06) | Dec 18, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E0T    | [4bc98299dd](https://bsd-hardware.info/?probe=4bc98299dd) | Dec 18, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YV... | [10fb96c00d](https://bsd-hardware.info/?probe=10fb96c00d) | Dec 18, 2023 |
| Deciso        | NetBoard-A10                | [ae676079d7](https://bsd-hardware.info/?probe=ae676079d7) | Dec 17, 2023 |
| HP            | Stream Notebook PC 11       | [1eb8cc9d76](https://bsd-hardware.info/?probe=1eb8cc9d76) | Dec 17, 2023 |
| Apple         | MacBookAir5,2               | [2c652aa0a1](https://bsd-hardware.info/?probe=2c652aa0a1) | Dec 16, 2023 |
| CSL-Comput... | C15 v3                      | [dd93594896](https://bsd-hardware.info/?probe=dd93594896) | Dec 16, 2023 |
| Lenovo        | ThinkPad P1 20MD002MUS      | [c0dcfec41d](https://bsd-hardware.info/?probe=c0dcfec41d) | Dec 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [7a5e6024cd](https://bsd-hardware.info/?probe=7a5e6024cd) | Dec 15, 2023 |
| Dell          | XPS 13 9370                 | [b6845a3e54](https://bsd-hardware.info/?probe=b6845a3e54) | Dec 15, 2023 |
| Apple         | MacBookPro10,2              | [e1867819f3](https://bsd-hardware.info/?probe=e1867819f3) | Dec 15, 2023 |
| Toshiba       | Portable PC                 | [bee6ea8f18](https://bsd-hardware.info/?probe=bee6ea8f18) | Dec 15, 2023 |
| Dell          | Latitude E6220              | [372070b2f2](https://bsd-hardware.info/?probe=372070b2f2) | Dec 15, 2023 |
| Google        | Kohaku                      | [0b945d8f38](https://bsd-hardware.info/?probe=0b945d8f38) | Dec 15, 2023 |
| Acer          | V5-131                      | [76e88ee5df](https://bsd-hardware.info/?probe=76e88ee5df) | Dec 14, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [c197b26909](https://bsd-hardware.info/?probe=c197b26909) | Dec 14, 2023 |
| Dell          | Latitude 3420               | [3767d653b9](https://bsd-hardware.info/?probe=3767d653b9) | Dec 14, 2023 |
| Dell          | Latitude E6540              | [77a9b10ab9](https://bsd-hardware.info/?probe=77a9b10ab9) | Dec 13, 2023 |
| Google        | Lindar rev3                 | [2e748fc42c](https://bsd-hardware.info/?probe=2e748fc42c) | Dec 13, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F6... | [a7fcca51be](https://bsd-hardware.info/?probe=a7fcca51be) | Dec 13, 2023 |
| ASUSTek       | K52JT                       | [1dc348adc0](https://bsd-hardware.info/?probe=1dc348adc0) | Dec 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [d81a233601](https://bsd-hardware.info/?probe=d81a233601) | Dec 12, 2023 |
| Dell          | Inspiron 5559               | [09f5b25e72](https://bsd-hardware.info/?probe=09f5b25e72) | Dec 12, 2023 |
| Dell          | Latitude E6510              | [86c4864c0a](https://bsd-hardware.info/?probe=86c4864c0a) | Dec 11, 2023 |
| Dell          | Latitude E6510              | [dc2d54a168](https://bsd-hardware.info/?probe=dc2d54a168) | Dec 11, 2023 |
| Dell          | Inspiron 5423               | [9368c19a35](https://bsd-hardware.info/?probe=9368c19a35) | Dec 11, 2023 |
| Deciso        | NetBoard-A20                | [06e5f53429](https://bsd-hardware.info/?probe=06e5f53429) | Dec 10, 2023 |
| Google        | Parrot                      | [c10a95cbcc](https://bsd-hardware.info/?probe=c10a95cbcc) | Dec 10, 2023 |
| Google        | Parrot                      | [3a69ea2682](https://bsd-hardware.info/?probe=3a69ea2682) | Dec 10, 2023 |
| Unknown       | Unknown                     | [426e43d7f2](https://bsd-hardware.info/?probe=426e43d7f2) | Dec 08, 2023 |
| Dell          | Latitude 7414               | [2d57c22982](https://bsd-hardware.info/?probe=2d57c22982) | Dec 08, 2023 |
| Dell          | Precision 7560              | [13f7324bd9](https://bsd-hardware.info/?probe=13f7324bd9) | Dec 07, 2023 |
| Dell          | Precision 7560              | [5d3e6e3bd4](https://bsd-hardware.info/?probe=5d3e6e3bd4) | Dec 07, 2023 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | [b5bbc08efe](https://bsd-hardware.info/?probe=b5bbc08efe) | Dec 07, 2023 |
| Lenovo        | ThinkPad P70 20ESS1L600     | [2e3870f2ee](https://bsd-hardware.info/?probe=2e3870f2ee) | Dec 07, 2023 |
| HP            | ZBook 17 G2                 | [406d7a0572](https://bsd-hardware.info/?probe=406d7a0572) | Dec 07, 2023 |
| HP            | EliteBook 840 G6            | [7476cc6440](https://bsd-hardware.info/?probe=7476cc6440) | Dec 06, 2023 |
| Apple         | MacBookAir7,2               | [3784a39a41](https://bsd-hardware.info/?probe=3784a39a41) | Dec 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [7a1ab6fd47](https://bsd-hardware.info/?probe=7a1ab6fd47) | Dec 06, 2023 |
| Sony          | VJS122C11L                  | [7d100c8e2c](https://bsd-hardware.info/?probe=7d100c8e2c) | Dec 06, 2023 |
| Lenovo        | ThinkPad W520 4270CTO       | [e63bc464f2](https://bsd-hardware.info/?probe=e63bc464f2) | Dec 05, 2023 |
| HP            | ZBook 17 G2                 | [cc4538374c](https://bsd-hardware.info/?probe=cc4538374c) | Dec 05, 2023 |
| Acer          | AOD260                      | [f8d6bb3095](https://bsd-hardware.info/?probe=f8d6bb3095) | Dec 05, 2023 |
| Dell          | Latitude E6330              | [7e0a01e9ad](https://bsd-hardware.info/?probe=7e0a01e9ad) | Dec 05, 2023 |
| Wortmann      | TERRA_MOBILE_1541           | [63f1a71855](https://bsd-hardware.info/?probe=63f1a71855) | Dec 04, 2023 |
| Lenovo        | ThinkPad T430s 23532QG      | [b456c01e0f](https://bsd-hardware.info/?probe=b456c01e0f) | Dec 04, 2023 |
| Deciso        | OPNsense Appliance          | [cb6b022d45](https://bsd-hardware.info/?probe=cb6b022d45) | Dec 04, 2023 |
| ASUSTek       | X555LB                      | [0df52370a2](https://bsd-hardware.info/?probe=0df52370a2) | Dec 04, 2023 |
| HP            | Pavilion g7                 | [4c1bc19902](https://bsd-hardware.info/?probe=4c1bc19902) | Dec 03, 2023 |
| Acidanther... | MacBookPro16,3              | [322ea11f6c](https://bsd-hardware.info/?probe=322ea11f6c) | Dec 03, 2023 |
| Deciso        | NetBoard-A20                | [18364861b5](https://bsd-hardware.info/?probe=18364861b5) | Dec 03, 2023 |
| Toshiba       | Satellite C50-B             | [34db2bdd7d](https://bsd-hardware.info/?probe=34db2bdd7d) | Dec 03, 2023 |
| Lenovo        | ThinkPad X280 20KES5M300    | [28d67ab74a](https://bsd-hardware.info/?probe=28d67ab74a) | Dec 02, 2023 |
| ASUSTek       | X555LB                      | [e96bb84b37](https://bsd-hardware.info/?probe=e96bb84b37) | Dec 02, 2023 |
| Star Labs     | LabTop                      | [e8dcf01d78](https://bsd-hardware.info/?probe=e8dcf01d78) | Dec 02, 2023 |
| Intel         | H81U                        | [b74cca91df](https://bsd-hardware.info/?probe=b74cca91df) | Dec 01, 2023 |
| Samsung       | N150P/N210P/N220P           | [b394563830](https://bsd-hardware.info/?probe=b394563830) | Nov 30, 2023 |
| Unknown       | Unknown                     | [7d3416a30f](https://bsd-hardware.info/?probe=7d3416a30f) | Nov 30, 2023 |
| Deciso        | DEC2700 - OPNsense Appli... | [e98e7bcab5](https://bsd-hardware.info/?probe=e98e7bcab5) | Nov 29, 2023 |
| Lenovo        | ThinkPad T450 20BV000BUS    | [ae4c6d7097](https://bsd-hardware.info/?probe=ae4c6d7097) | Nov 29, 2023 |
| Unknown       | Unknown                     | [ac008cef96](https://bsd-hardware.info/?probe=ac008cef96) | Nov 28, 2023 |
| Dell          | Precision 5510              | [3a7b2ae214](https://bsd-hardware.info/?probe=3a7b2ae214) | Nov 28, 2023 |
| Unknown       | Unknown                     | [ddb77f8341](https://bsd-hardware.info/?probe=ddb77f8341) | Nov 28, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | [1096dc8160](https://bsd-hardware.info/?probe=1096dc8160) | Nov 27, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | [1bfc57a019](https://bsd-hardware.info/?probe=1bfc57a019) | Nov 27, 2023 |
| Dell          | Inspiron N5010              | [b32ded6bb9](https://bsd-hardware.info/?probe=b32ded6bb9) | Nov 27, 2023 |
| Dell          | Inspiron 7558               | [b34a8742d5](https://bsd-hardware.info/?probe=b34a8742d5) | Nov 26, 2023 |
| Unknown       | Unknown                     | [55339dbfab](https://bsd-hardware.info/?probe=55339dbfab) | Nov 26, 2023 |
| Google        | Kohaku                      | [94c3c0f6b7](https://bsd-hardware.info/?probe=94c3c0f6b7) | Nov 26, 2023 |
| Google        | Kohaku                      | [198b445c4e](https://bsd-hardware.info/?probe=198b445c4e) | Nov 26, 2023 |
| Lenovo        | IdeaPad 320-15IKB Touch ... | [3517ce2745](https://bsd-hardware.info/?probe=3517ce2745) | Nov 26, 2023 |
| Lenovo        | IdeaPad 320-15IKB Touch ... | [5f336b9d93](https://bsd-hardware.info/?probe=5f336b9d93) | Nov 26, 2023 |
| HP            | Laptop 15s-eq3xxx           | [f2aa7b3ebf](https://bsd-hardware.info/?probe=f2aa7b3ebf) | Nov 25, 2023 |
| Dell          | Latitude E5540              | [d12acc0425](https://bsd-hardware.info/?probe=d12acc0425) | Nov 25, 2023 |
| Dell          | Latitude 5480               | [639ffb1573](https://bsd-hardware.info/?probe=639ffb1573) | Nov 25, 2023 |
| Apple         | MacBookAir4,1               | [4661b8933c](https://bsd-hardware.info/?probe=4661b8933c) | Nov 25, 2023 |
| Dell          | Inspiron 7558               | [aad8d359f3](https://bsd-hardware.info/?probe=aad8d359f3) | Nov 24, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [a44d6afa76](https://bsd-hardware.info/?probe=a44d6afa76) | Nov 24, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [b67644f2b3](https://bsd-hardware.info/?probe=b67644f2b3) | Nov 24, 2023 |
| Lenovo        | G50-80 80E5                 | [e0d8200dfa](https://bsd-hardware.info/?probe=e0d8200dfa) | Nov 24, 2023 |
| Acer          | Aspire E5-574               | [b11a972371](https://bsd-hardware.info/?probe=b11a972371) | Nov 24, 2023 |
| Google        | Dragonair                   | [713cf1bc38](https://bsd-hardware.info/?probe=713cf1bc38) | Nov 24, 2023 |
| HP            | Notebook                    | [aff6430eb2](https://bsd-hardware.info/?probe=aff6430eb2) | Nov 24, 2023 |
| Lenovo        | ThinkPad A485 20MU000VUS    | [8f21b7d70f](https://bsd-hardware.info/?probe=8f21b7d70f) | Nov 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [9762745c92](https://bsd-hardware.info/?probe=9762745c92) | Nov 23, 2023 |
| Dell          | Latitude E5440              | [629fba28cc](https://bsd-hardware.info/?probe=629fba28cc) | Nov 23, 2023 |
| Lenovo        | ThinkPad X260 20F5S2GM00    | [b5be73085a](https://bsd-hardware.info/?probe=b5be73085a) | Nov 23, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [0d706d98b4](https://bsd-hardware.info/?probe=0d706d98b4) | Nov 23, 2023 |
| Fujitsu       | LIFEBOOK E752               | [1da7551908](https://bsd-hardware.info/?probe=1da7551908) | Nov 23, 2023 |
| Acer          | JM11-MS                     | [0490895189](https://bsd-hardware.info/?probe=0490895189) | Nov 23, 2023 |
| Dell          | Latitude 7490               | [e860d3dbcf](https://bsd-hardware.info/?probe=e860d3dbcf) | Nov 23, 2023 |
| Acer          | Aspire E5-574               | [a4eded7a52](https://bsd-hardware.info/?probe=a4eded7a52) | Nov 22, 2023 |
| HP            | Laptop 14-fq0xxx            | [4c5aa5c3ea](https://bsd-hardware.info/?probe=4c5aa5c3ea) | Nov 22, 2023 |
| Acidanther... | MacBookPro16,3              | [5f89fa2cd2](https://bsd-hardware.info/?probe=5f89fa2cd2) | Nov 22, 2023 |
| Deciso        | NetBoard-A10                | [2ea96f8806](https://bsd-hardware.info/?probe=2ea96f8806) | Nov 21, 2023 |
| Toshiba       | Satellite C40-A             | [0c545b75e9](https://bsd-hardware.info/?probe=0c545b75e9) | Nov 21, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [19dfa9e36a](https://bsd-hardware.info/?probe=19dfa9e36a) | Nov 21, 2023 |
| Toshiba       | Satellite C40-A             | [cecd389c82](https://bsd-hardware.info/?probe=cecd389c82) | Nov 21, 2023 |
| Dell          | XPS 13 9360                 | [9b3cb9cbd6](https://bsd-hardware.info/?probe=9b3cb9cbd6) | Nov 21, 2023 |
| Unknown       | Unknown                     | [ff855b549e](https://bsd-hardware.info/?probe=ff855b549e) | Nov 20, 2023 |
| Lenovo        | ThinkPad T470 20HES0EV0A    | [96562d6513](https://bsd-hardware.info/?probe=96562d6513) | Nov 20, 2023 |
| Lenovo        | ThinkPad T450 20BV000BUS    | [fdb7c00df7](https://bsd-hardware.info/?probe=fdb7c00df7) | Nov 20, 2023 |
| Lenovo        | ThinkPad T470 20HES0EV0A    | [5caaad73bd](https://bsd-hardware.info/?probe=5caaad73bd) | Nov 19, 2023 |
| Lenovo        | ThinkPad W530 24411M9       | [0272396725](https://bsd-hardware.info/?probe=0272396725) | Nov 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [2c33e6e9e7](https://bsd-hardware.info/?probe=2c33e6e9e7) | Nov 19, 2023 |
| Dell          | Latitude 5440               | [9daa44aacf](https://bsd-hardware.info/?probe=9daa44aacf) | Nov 18, 2023 |
| Panasonic     | CF-31-5                     | [8771ab6139](https://bsd-hardware.info/?probe=8771ab6139) | Nov 18, 2023 |
| Lenovo        | ThinkPad T60 8744HDG        | [fc54b10db3](https://bsd-hardware.info/?probe=fc54b10db3) | Nov 18, 2023 |
| Dell          | Precision 5520              | [45f5e399a4](https://bsd-hardware.info/?probe=45f5e399a4) | Nov 18, 2023 |
| HP            | Notebook                    | [c583c221c7](https://bsd-hardware.info/?probe=c583c221c7) | Nov 17, 2023 |
| TUXEDO        | Pulse 15 Gen2               | [9061ad4228](https://bsd-hardware.info/?probe=9061ad4228) | Nov 17, 2023 |
| Toshiba       | Satellite P300              | [ece5171a1d](https://bsd-hardware.info/?probe=ece5171a1d) | Nov 17, 2023 |
| HP            | Notebook                    | [5d2df329aa](https://bsd-hardware.info/?probe=5d2df329aa) | Nov 17, 2023 |
| Acer          | Aspire ES1-572              | [2aa8175a33](https://bsd-hardware.info/?probe=2aa8175a33) | Nov 17, 2023 |
| Dell          | Precision 7720              | [65a0287ad6](https://bsd-hardware.info/?probe=65a0287ad6) | Nov 16, 2023 |
| Dell          | Inspiron 1525               | [984f5f2f4b](https://bsd-hardware.info/?probe=984f5f2f4b) | Nov 16, 2023 |
| Lenovo        | ThinkPad X230 2320A5U       | [48f8b6a93a](https://bsd-hardware.info/?probe=48f8b6a93a) | Nov 16, 2023 |
| Unknown       | Unknown                     | [8854b07e12](https://bsd-hardware.info/?probe=8854b07e12) | Nov 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [918706e110](https://bsd-hardware.info/?probe=918706e110) | Nov 15, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [0e4ea9ccbf](https://bsd-hardware.info/?probe=0e4ea9ccbf) | Nov 15, 2023 |
| Dell          | G5 5505                     | [088aea32c0](https://bsd-hardware.info/?probe=088aea32c0) | Nov 15, 2023 |
| Apple         | MacBookPro7,1               | [97267cbee9](https://bsd-hardware.info/?probe=97267cbee9) | Nov 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [ed79ea60c4](https://bsd-hardware.info/?probe=ed79ea60c4) | Nov 13, 2023 |
| Dell          | Inspiron 3442               | [3f63ee5447](https://bsd-hardware.info/?probe=3f63ee5447) | Nov 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [0fd2711a56](https://bsd-hardware.info/?probe=0fd2711a56) | Nov 12, 2023 |
| OnLogic       | HX401                       | [b000c6d264](https://bsd-hardware.info/?probe=b000c6d264) | Nov 12, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [b85df96058](https://bsd-hardware.info/?probe=b85df96058) | Nov 11, 2023 |
| ASUSTek       | K56CB                       | [8d4f2c439a](https://bsd-hardware.info/?probe=8d4f2c439a) | Nov 11, 2023 |
| Panasonic     | CFSX4-1                     | [f0f418db58](https://bsd-hardware.info/?probe=f0f418db58) | Nov 11, 2023 |
| Lenovo        | ThinkPad X270 20HN006CUS    | [dc8d596ea1](https://bsd-hardware.info/?probe=dc8d596ea1) | Nov 11, 2023 |
| Fujitsu       | LIFEBOOK E752               | [ee95b41634](https://bsd-hardware.info/?probe=ee95b41634) | Nov 10, 2023 |
| Lenovo        | ThinkPad X260 20F6006XUK    | [823bdd1b43](https://bsd-hardware.info/?probe=823bdd1b43) | Nov 10, 2023 |
| Lenovo        | ThinkPad E14 20RA0016RT     | [83b87dac52](https://bsd-hardware.info/?probe=83b87dac52) | Nov 10, 2023 |
| Panasonic     | CF-54-1                     | [c530bdbd88](https://bsd-hardware.info/?probe=c530bdbd88) | Nov 10, 2023 |
| Lenovo        | ThinkPad T480 20L6S5VP00    | [5eb914094b](https://bsd-hardware.info/?probe=5eb914094b) | Nov 09, 2023 |
| Dell          | Precision 7560              | [a0e5297849](https://bsd-hardware.info/?probe=a0e5297849) | Nov 09, 2023 |
| Gateway       | NV79                        | [2a7dd49956](https://bsd-hardware.info/?probe=2a7dd49956) | Nov 09, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [d87ea88953](https://bsd-hardware.info/?probe=d87ea88953) | Nov 09, 2023 |
| Unknown       | Unknown                     | [5092a67813](https://bsd-hardware.info/?probe=5092a67813) | Nov 08, 2023 |
| Unknown       | Unknown                     | [251cf99325](https://bsd-hardware.info/?probe=251cf99325) | Nov 08, 2023 |
| Toshiba       | Satellite P300              | [9d4170e2d2](https://bsd-hardware.info/?probe=9d4170e2d2) | Nov 08, 2023 |
| Dell          | Inspiron 5570               | [1f6c70fd78](https://bsd-hardware.info/?probe=1f6c70fd78) | Nov 07, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [05bf5fb9f4](https://bsd-hardware.info/?probe=05bf5fb9f4) | Nov 07, 2023 |
| HP            | Pavilion g6                 | [6e2c3d13a4](https://bsd-hardware.info/?probe=6e2c3d13a4) | Nov 07, 2023 |
| Dell          | Precision 7720              | [45614f0ff9](https://bsd-hardware.info/?probe=45614f0ff9) | Nov 06, 2023 |
| Unknown       | Unknown                     | [61c7e94f23](https://bsd-hardware.info/?probe=61c7e94f23) | Nov 06, 2023 |
| Unknown       | Unknown                     | [316be7bb33](https://bsd-hardware.info/?probe=316be7bb33) | Nov 06, 2023 |
| Dell          | Latitude E6540              | [a26912fd0d](https://bsd-hardware.info/?probe=a26912fd0d) | Nov 06, 2023 |
| Dell          | Inspiron N4050              | [9bc3c5e163](https://bsd-hardware.info/?probe=9bc3c5e163) | Nov 05, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [4f9885c454](https://bsd-hardware.info/?probe=4f9885c454) | Nov 05, 2023 |
| ASUSTek       | K56CB                       | [7d6d03a42b](https://bsd-hardware.info/?probe=7d6d03a42b) | Nov 05, 2023 |
| Dell          | Precision 7720              | [ef59e0f80d](https://bsd-hardware.info/?probe=ef59e0f80d) | Nov 05, 2023 |
| Lenovo        | Z50-70 20354                | [641e875b3b](https://bsd-hardware.info/?probe=641e875b3b) | Nov 04, 2023 |
| Dell          | XPS 13 9360                 | [c7d016caa9](https://bsd-hardware.info/?probe=c7d016caa9) | Nov 04, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | [a9448cf3b5](https://bsd-hardware.info/?probe=a9448cf3b5) | Nov 04, 2023 |
| LG Electro... | 16UD70R-G.AX59B             | [a7df4f645f](https://bsd-hardware.info/?probe=a7df4f645f) | Nov 04, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [19514dd0bd](https://bsd-hardware.info/?probe=19514dd0bd) | Nov 03, 2023 |
| Dell          | Inspiron 1525               | [538444f1d2](https://bsd-hardware.info/?probe=538444f1d2) | Nov 02, 2023 |
| Dell          | Precision 7720              | [cc321f8dea](https://bsd-hardware.info/?probe=cc321f8dea) | Nov 01, 2023 |
| Apple         | MacBookPro7,1               | [91d07ef080](https://bsd-hardware.info/?probe=91d07ef080) | Nov 01, 2023 |
| Lenovo        | ThinkPad T480 20L5000WUS    | [4dcf84c76c](https://bsd-hardware.info/?probe=4dcf84c76c) | Oct 31, 2023 |
| Shuttle       | DS437                       | [45c2e3460c](https://bsd-hardware.info/?probe=45c2e3460c) | Oct 30, 2023 |
| Panasonic     | CFSX4-1                     | [32b7f19d78](https://bsd-hardware.info/?probe=32b7f19d78) | Oct 30, 2023 |
| Panasonic     | CFSX4-1                     | [522298f90a](https://bsd-hardware.info/?probe=522298f90a) | Oct 29, 2023 |
| TUXEDO        | Aura 15 Gen1                | [7a6b4537f3](https://bsd-hardware.info/?probe=7a6b4537f3) | Oct 29, 2023 |
| HP            | Pavilion g6                 | [6aee98fb1a](https://bsd-hardware.info/?probe=6aee98fb1a) | Oct 29, 2023 |
| Dell          | Vostro 3500                 | [875b045b38](https://bsd-hardware.info/?probe=875b045b38) | Oct 29, 2023 |
| HP            | ZBook 15 G3                 | [74c3cbd1a3](https://bsd-hardware.info/?probe=74c3cbd1a3) | Oct 29, 2023 |
| Lenovo        | Z50-70 20354                | [f3d9534b2d](https://bsd-hardware.info/?probe=f3d9534b2d) | Oct 28, 2023 |
| Lenovo        | ThinkPad T520 42405FG       | [e6aca7e0c8](https://bsd-hardware.info/?probe=e6aca7e0c8) | Oct 28, 2023 |
| Toshiba       | Satellite P300              | [49d23c8fda](https://bsd-hardware.info/?probe=49d23c8fda) | Oct 28, 2023 |
| Toshiba       | Satellite P300              | [a133633304](https://bsd-hardware.info/?probe=a133633304) | Oct 28, 2023 |
| Lenovo        | ThinkPad X230 23205UG       | [f204abc5fc](https://bsd-hardware.info/?probe=f204abc5fc) | Oct 28, 2023 |
| Deciso        | OPNsense Appliance          | [9508bd06f5](https://bsd-hardware.info/?probe=9508bd06f5) | Oct 28, 2023 |
| IBM           | ThinkPad R51 2889W11        | [26d2e55032](https://bsd-hardware.info/?probe=26d2e55032) | Oct 28, 2023 |
| Datto         | Unknown                     | [8b59510085](https://bsd-hardware.info/?probe=8b59510085) | Oct 27, 2023 |
| Panasonic     | CF-C2CEAZXCM                | [a871fb0596](https://bsd-hardware.info/?probe=a871fb0596) | Oct 27, 2023 |
| Lenovo        | ThinkPad X270 20HN006CUS    | [aa85ff898d](https://bsd-hardware.info/?probe=aa85ff898d) | Oct 26, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [09cf753c7a](https://bsd-hardware.info/?probe=09cf753c7a) | Oct 26, 2023 |
| Deciso        | NetBoard-A10                | [d0ee609c75](https://bsd-hardware.info/?probe=d0ee609c75) | Oct 25, 2023 |
| Toshiba       | Unknown                     | [de44a16738](https://bsd-hardware.info/?probe=de44a16738) | Oct 24, 2023 |
| Lenovo        | G50-30 80G0                 | [e2dad0b43a](https://bsd-hardware.info/?probe=e2dad0b43a) | Oct 24, 2023 |
| Deciso        | OPNsense Appliance          | [d9f0644c56](https://bsd-hardware.info/?probe=d9f0644c56) | Oct 24, 2023 |
| Lenovo        | ThinkPad T490 20N3X50500    | [364c7828be](https://bsd-hardware.info/?probe=364c7828be) | Oct 24, 2023 |
| Panasonic     | CF-52PFPBSFQ                | [4a97ab307a](https://bsd-hardware.info/?probe=4a97ab307a) | Oct 22, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [1f76a6c28c](https://bsd-hardware.info/?probe=1f76a6c28c) | Oct 22, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [6569410f91](https://bsd-hardware.info/?probe=6569410f91) | Oct 22, 2023 |
| Seco          | UDOO x86                    | [260f8194ed](https://bsd-hardware.info/?probe=260f8194ed) | Oct 22, 2023 |
| Lenovo        | ThinkPad T430 2347GZU       | [88ae89f787](https://bsd-hardware.info/?probe=88ae89f787) | Oct 22, 2023 |
| Panasonic     | CF-53AAGHYDM                | [6f29731875](https://bsd-hardware.info/?probe=6f29731875) | Oct 22, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [7a57e0a112](https://bsd-hardware.info/?probe=7a57e0a112) | Oct 21, 2023 |
| ASUSTek       | 1000HE                      | [249959fd2c](https://bsd-hardware.info/?probe=249959fd2c) | Oct 21, 2023 |
| Matsushita... | CF-51RCVDNLM                | [ec5aff8b6b](https://bsd-hardware.info/?probe=ec5aff8b6b) | Oct 21, 2023 |
| Matsushita... | CF-48V4KNDQM                | [625f272fcd](https://bsd-hardware.info/?probe=625f272fcd) | Oct 21, 2023 |
| HP            | Laptop 15s-eq3xxx           | [5a7e4222f1](https://bsd-hardware.info/?probe=5a7e4222f1) | Oct 21, 2023 |
| ASUSTek       | N73SV                       | [31fff3e92b](https://bsd-hardware.info/?probe=31fff3e92b) | Oct 21, 2023 |
| Lenovo        | ThinkPad T410 2518C3U       | [e4b35a3ff6](https://bsd-hardware.info/?probe=e4b35a3ff6) | Oct 21, 2023 |
| Dell          | G16 7630                    | [deb5f3bd32](https://bsd-hardware.info/?probe=deb5f3bd32) | Oct 21, 2023 |
| ASUSTek       | N73SV                       | [30726f25a0](https://bsd-hardware.info/?probe=30726f25a0) | Oct 21, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [965e71ac80](https://bsd-hardware.info/?probe=965e71ac80) | Oct 21, 2023 |
| Dell          | Latitude 5490               | [eeab525ffd](https://bsd-hardware.info/?probe=eeab525ffd) | Oct 20, 2023 |
| Lenovo        | ThinkPad T410 2537N24       | [fd75aab1c6](https://bsd-hardware.info/?probe=fd75aab1c6) | Oct 20, 2023 |
| Panasonic     | CFSX4-1                     | [d3ad63aa13](https://bsd-hardware.info/?probe=d3ad63aa13) | Oct 19, 2023 |
| Unknown       | Unknown                     | [363b63c1a1](https://bsd-hardware.info/?probe=363b63c1a1) | Oct 18, 2023 |
| Acer          | Aspire 5336                 | [ebfed0efbc](https://bsd-hardware.info/?probe=ebfed0efbc) | Oct 18, 2023 |
| Intel         | H81U                        | [9ed05368b5](https://bsd-hardware.info/?probe=9ed05368b5) | Oct 18, 2023 |
| Dell          | Inspiron 5559               | [0ae4cee8b3](https://bsd-hardware.info/?probe=0ae4cee8b3) | Oct 17, 2023 |
| Unknown       | Unknown                     | [ea04f97748](https://bsd-hardware.info/?probe=ea04f97748) | Oct 17, 2023 |
| Apple         | MacBook5,2                  | [5f364ec930](https://bsd-hardware.info/?probe=5f364ec930) | Oct 17, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [b08dc9fc91](https://bsd-hardware.info/?probe=b08dc9fc91) | Oct 16, 2023 |
| Dell          | Latitude 3440               | [3e6826570c](https://bsd-hardware.info/?probe=3e6826570c) | Oct 16, 2023 |
| ASUSTek       | N552VX                      | [f927cf5ba4](https://bsd-hardware.info/?probe=f927cf5ba4) | Oct 16, 2023 |
| ASUSTek       | X455LD                      | [e61ce1bc9a](https://bsd-hardware.info/?probe=e61ce1bc9a) | Oct 15, 2023 |
| Acer          | Aspire E5-575G              | [f38d89e6c0](https://bsd-hardware.info/?probe=f38d89e6c0) | Oct 15, 2023 |
| Lenovo        | ThinkPad T480 20L5000UUS    | [20fe904881](https://bsd-hardware.info/?probe=20fe904881) | Oct 15, 2023 |
| Acer          | Aspire E5-575G              | [0aa91c2a5c](https://bsd-hardware.info/?probe=0aa91c2a5c) | Oct 15, 2023 |
| Fujitsu       | LIFEBOOK E744               | [72a9b731f6](https://bsd-hardware.info/?probe=72a9b731f6) | Oct 14, 2023 |
| Deciso        | Netboard A20                | [879efbe255](https://bsd-hardware.info/?probe=879efbe255) | Oct 14, 2023 |
| Deciso        | NetBoard-A20                | [7ed49c5f2f](https://bsd-hardware.info/?probe=7ed49c5f2f) | Oct 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [0f3cd5aa25](https://bsd-hardware.info/?probe=0f3cd5aa25) | Oct 13, 2023 |
| ASUSTek       | X455LD                      | [b1a7a3f656](https://bsd-hardware.info/?probe=b1a7a3f656) | Oct 13, 2023 |
| Acer          | Aspire ES1-571              | [f3036a27e5](https://bsd-hardware.info/?probe=f3036a27e5) | Oct 13, 2023 |
| IBM           | ThinkPad R51 2889W11        | [45836fafc3](https://bsd-hardware.info/?probe=45836fafc3) | Oct 12, 2023 |
| Toshiba       | Satellite C55-A             | [f27ea283cf](https://bsd-hardware.info/?probe=f27ea283cf) | Oct 12, 2023 |
| Lenovo        | ThinkPad X250 20CM004VFR    | [e4ab2acd8d](https://bsd-hardware.info/?probe=e4ab2acd8d) | Oct 11, 2023 |
| Lenovo        | G550 2958                   | [6dfadd1ff2](https://bsd-hardware.info/?probe=6dfadd1ff2) | Oct 11, 2023 |
| Apple         | MacBook5,1                  | [518658e176](https://bsd-hardware.info/?probe=518658e176) | Oct 11, 2023 |
| Apple         | MacBookPro9,2               | [c88d8880ea](https://bsd-hardware.info/?probe=c88d8880ea) | Oct 11, 2023 |
| ASUSTek       | K45VM                       | [054a6c3902](https://bsd-hardware.info/?probe=054a6c3902) | Oct 11, 2023 |
| Dell          | Precision 7550              | [a21e06c16c](https://bsd-hardware.info/?probe=a21e06c16c) | Oct 11, 2023 |
| Deciso        | NetBoard-A20                | [b9c11f29c9](https://bsd-hardware.info/?probe=b9c11f29c9) | Oct 10, 2023 |
| Deciso        | NetBoard-A10                | [12b5a57360](https://bsd-hardware.info/?probe=12b5a57360) | Oct 10, 2023 |
| Deciso        | NetBoard-A20                | [ddffd0a126](https://bsd-hardware.info/?probe=ddffd0a126) | Oct 10, 2023 |
| Unknown       | Unknown                     | [9c6c7f9d6b](https://bsd-hardware.info/?probe=9c6c7f9d6b) | Oct 10, 2023 |
| Dell          | Latitude D830               | [4cf27e5d29](https://bsd-hardware.info/?probe=4cf27e5d29) | Oct 09, 2023 |
| Dell          | Inspiron 13 5320            | [43c1b405d0](https://bsd-hardware.info/?probe=43c1b405d0) | Oct 09, 2023 |
| Unknown       | Unknown                     | [57e5ab8786](https://bsd-hardware.info/?probe=57e5ab8786) | Oct 08, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [b192196423](https://bsd-hardware.info/?probe=b192196423) | Oct 08, 2023 |
| Dell          | Vostro 3700                 | [8262e3923f](https://bsd-hardware.info/?probe=8262e3923f) | Oct 08, 2023 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | [5be3eb1296](https://bsd-hardware.info/?probe=5be3eb1296) | Oct 08, 2023 |
| Unknown       | Unknown                     | [1f7ab105e3](https://bsd-hardware.info/?probe=1f7ab105e3) | Oct 08, 2023 |
| Lenovo        | ThinkPad E580 20KS001JUK    | [0aac5f52c9](https://bsd-hardware.info/?probe=0aac5f52c9) | Oct 08, 2023 |
| Lenovo        | ThinkPad T410 2518C3U       | [36daf066ca](https://bsd-hardware.info/?probe=36daf066ca) | Oct 08, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [c646a3b663](https://bsd-hardware.info/?probe=c646a3b663) | Oct 07, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2AD0... | [ac6742bd0f](https://bsd-hardware.info/?probe=ac6742bd0f) | Oct 07, 2023 |
| Timi          | A34R                        | [3cd3f35eaa](https://bsd-hardware.info/?probe=3cd3f35eaa) | Oct 07, 2023 |
| Timi          | A34R                        | [03f00603f7](https://bsd-hardware.info/?probe=03f00603f7) | Oct 07, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2AD0... | [3e15173331](https://bsd-hardware.info/?probe=3e15173331) | Oct 07, 2023 |
| Apple         | MacBookPro6,2               | [85e94bd511](https://bsd-hardware.info/?probe=85e94bd511) | Oct 06, 2023 |
| Deciso        | Netboard A20                | [c549fc9540](https://bsd-hardware.info/?probe=c549fc9540) | Oct 05, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | [88e8c64b6f](https://bsd-hardware.info/?probe=88e8c64b6f) | Oct 04, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [aecfeaa518](https://bsd-hardware.info/?probe=aecfeaa518) | Oct 04, 2023 |
| ASUSTek       | K73E                        | [ce5fcbdc3e](https://bsd-hardware.info/?probe=ce5fcbdc3e) | Oct 04, 2023 |
| Lenovo        | ThinkPad X230 2325J67       | [bfbc6beca8](https://bsd-hardware.info/?probe=bfbc6beca8) | Oct 04, 2023 |
| Dell          | Latitude 5591               | [8f6ca1e82a](https://bsd-hardware.info/?probe=8f6ca1e82a) | Oct 03, 2023 |
| Lenovo        | ThinkPad X260 20F6006XUK    | [25fecdaad5](https://bsd-hardware.info/?probe=25fecdaad5) | Oct 03, 2023 |
| HP            | ZBook 17 G2                 | [4e12d36770](https://bsd-hardware.info/?probe=4e12d36770) | Oct 03, 2023 |
| Lenovo        | B40-30 80F1                 | [00c5e6adda](https://bsd-hardware.info/?probe=00c5e6adda) | Oct 03, 2023 |
| Platform      | ARB938                      | [141d043221](https://bsd-hardware.info/?probe=141d043221) | Oct 02, 2023 |
| Google        | Auron_Paine                 | [d202b4dd6f](https://bsd-hardware.info/?probe=d202b4dd6f) | Oct 02, 2023 |
| Google        | Auron_Paine                 | [1c44cf70e8](https://bsd-hardware.info/?probe=1c44cf70e8) | Oct 02, 2023 |
| Apple         | MacBookPro7,1               | [070c5dab4f](https://bsd-hardware.info/?probe=070c5dab4f) | Oct 02, 2023 |
| ASUSTek       | K40IN                       | [6b58792f5e](https://bsd-hardware.info/?probe=6b58792f5e) | Oct 02, 2023 |
| Deciso        | NetBoard-A10                | [5524017014](https://bsd-hardware.info/?probe=5524017014) | Oct 01, 2023 |
| Apple         | MacBookPro9,1               | [9b9f826560](https://bsd-hardware.info/?probe=9b9f826560) | Oct 01, 2023 |
| Google        | Auron_Paine                 | [021624028a](https://bsd-hardware.info/?probe=021624028a) | Oct 01, 2023 |
| Dell          | Inspiron 5559               | [7a6b97e997](https://bsd-hardware.info/?probe=7a6b97e997) | Oct 01, 2023 |
| Acer          | TravelMate 5730             | [dffc2e116d](https://bsd-hardware.info/?probe=dffc2e116d) | Sep 30, 2023 |
| Unknown       | Unknown                     | [7cfd3d40eb](https://bsd-hardware.info/?probe=7cfd3d40eb) | Sep 30, 2023 |
| Deciso        | Netboard A20                | [3877143e37](https://bsd-hardware.info/?probe=3877143e37) | Sep 29, 2023 |
| ASUSTek       | 1005PXD                     | [1b05e8cf1b](https://bsd-hardware.info/?probe=1b05e8cf1b) | Sep 29, 2023 |
| Apple         | MacBookPro9,1               | [b0aca42c84](https://bsd-hardware.info/?probe=b0aca42c84) | Sep 29, 2023 |
| MSI           | CX62 6QD                    | [68b8b9f531](https://bsd-hardware.info/?probe=68b8b9f531) | Sep 29, 2023 |
| MSI           | CX62 6QD                    | [e732d89b06](https://bsd-hardware.info/?probe=e732d89b06) | Sep 29, 2023 |
| Apple         | MacBookPro7,1               | [714516a696](https://bsd-hardware.info/?probe=714516a696) | Sep 29, 2023 |
| Apple         | MacBookPro9,1               | [cac0950717](https://bsd-hardware.info/?probe=cac0950717) | Sep 29, 2023 |
| ASUSTek       | K40IN                       | [3c69dd7003](https://bsd-hardware.info/?probe=3c69dd7003) | Sep 29, 2023 |
| ASUSTek       | K40IN                       | [f98d4be34d](https://bsd-hardware.info/?probe=f98d4be34d) | Sep 29, 2023 |
| Dell          | Latitude 5591               | [c30943def8](https://bsd-hardware.info/?probe=c30943def8) | Sep 28, 2023 |
| Dell          | Latitude E6430              | [bec165c243](https://bsd-hardware.info/?probe=bec165c243) | Sep 27, 2023 |
| Panasonic     | CFSX4-1                     | [86abd76c4e](https://bsd-hardware.info/?probe=86abd76c4e) | Sep 27, 2023 |
| Lenovo        | ThinkPad T16 Gen 2 21HHC... | [74d0396f87](https://bsd-hardware.info/?probe=74d0396f87) | Sep 27, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | [0c56aeb6b5](https://bsd-hardware.info/?probe=0c56aeb6b5) | Sep 27, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D60... | [231aedbf9e](https://bsd-hardware.info/?probe=231aedbf9e) | Sep 25, 2023 |
| Dell          | Latitude 3410               | [1bd71b0bf0](https://bsd-hardware.info/?probe=1bd71b0bf0) | Sep 24, 2023 |
| TUXEDO        | Aura 15 Gen1                | [b31f8c12f8](https://bsd-hardware.info/?probe=b31f8c12f8) | Sep 24, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [5cd50ed5b5](https://bsd-hardware.info/?probe=5cd50ed5b5) | Sep 24, 2023 |
| GPD           | G1619-04                    | [30ad9b72b5](https://bsd-hardware.info/?probe=30ad9b72b5) | Sep 23, 2023 |
| Intel         | Milstead Platform           | [04e544d5f1](https://bsd-hardware.info/?probe=04e544d5f1) | Sep 22, 2023 |
| Dell          | Latitude E7470              | [11cf3b211c](https://bsd-hardware.info/?probe=11cf3b211c) | Sep 22, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [de1bdf0601](https://bsd-hardware.info/?probe=de1bdf0601) | Sep 21, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [8a3d3b3d0d](https://bsd-hardware.info/?probe=8a3d3b3d0d) | Sep 21, 2023 |
| Dell          | G16 7630                    | [4e39a5ebdf](https://bsd-hardware.info/?probe=4e39a5ebdf) | Sep 21, 2023 |
| Lenovo        | ThinkPad P50 20EN0012US     | [a1945198c6](https://bsd-hardware.info/?probe=a1945198c6) | Sep 21, 2023 |
| Panasonic     | CFSX4-1                     | [398d7a6f26](https://bsd-hardware.info/?probe=398d7a6f26) | Sep 20, 2023 |
| HP            | ZBook 17 G2                 | [f29233649e](https://bsd-hardware.info/?probe=f29233649e) | Sep 20, 2023 |
| Dell          | XPS 13 7390                 | [6bb6186f22](https://bsd-hardware.info/?probe=6bb6186f22) | Sep 19, 2023 |
| Lenovo        | ThinkPad L390 20NRS00Q00    | [b9885ea126](https://bsd-hardware.info/?probe=b9885ea126) | Sep 17, 2023 |
| Lenovo        | ThinkPad T470 20HES0HU00    | [a64fe205a9](https://bsd-hardware.info/?probe=a64fe205a9) | Sep 17, 2023 |
| Unknown       | Unknown                     | [5aebf0e729](https://bsd-hardware.info/?probe=5aebf0e729) | Sep 16, 2023 |
| Lenovo        | ThinkPad T480s 20L7S24F0... | [bb7eb8b380](https://bsd-hardware.info/?probe=bb7eb8b380) | Sep 15, 2023 |
| Lenovo        | ThinkPad Edge E531 68852... | [cc3bef6a45](https://bsd-hardware.info/?probe=cc3bef6a45) | Sep 15, 2023 |
| Deciso        | NetBoard-A20                | [0c65fb5e8c](https://bsd-hardware.info/?probe=0c65fb5e8c) | Sep 15, 2023 |
| Dell          | XPS 9320                    | [d80b3d5a54](https://bsd-hardware.info/?probe=d80b3d5a54) | Sep 14, 2023 |
| Dell          | Latitude E6420              | [b90b748742](https://bsd-hardware.info/?probe=b90b748742) | Sep 14, 2023 |
| eMachines     | G640                        | [c05619033c](https://bsd-hardware.info/?probe=c05619033c) | Sep 14, 2023 |
| Platform      | ARB938                      | [17b7c850c4](https://bsd-hardware.info/?probe=17b7c850c4) | Sep 14, 2023 |
| Alienware     | m15                         | [609d2ce1ce](https://bsd-hardware.info/?probe=609d2ce1ce) | Sep 14, 2023 |
| HP            | Pavilion dv5                | [b7dad77d0d](https://bsd-hardware.info/?probe=b7dad77d0d) | Sep 14, 2023 |
| Deciso        | NetBoard-A10                | [0068732d33](https://bsd-hardware.info/?probe=0068732d33) | Sep 13, 2023 |
| GPU Compan... | GWTC116-2                   | [03a8809fe4](https://bsd-hardware.info/?probe=03a8809fe4) | Sep 13, 2023 |
| ASUSTek       | N751JK                      | [67d1f42d7c](https://bsd-hardware.info/?probe=67d1f42d7c) | Sep 13, 2023 |
| GPU Compan... | GWTC116-2                   | [7ba189ff8a](https://bsd-hardware.info/?probe=7ba189ff8a) | Sep 13, 2023 |
| OEGStone      | doceo 510                   | [9f3b47e30f](https://bsd-hardware.info/?probe=9f3b47e30f) | Sep 13, 2023 |
| HP            | ProBook 4530s               | [0b47c15c42](https://bsd-hardware.info/?probe=0b47c15c42) | Sep 12, 2023 |
| Lenovo        | ThinkPad X140e 20BMS03E0... | [54b04ea958](https://bsd-hardware.info/?probe=54b04ea958) | Sep 12, 2023 |
| HP            | ProBook 4530s               | [4b6daa1f1c](https://bsd-hardware.info/?probe=4b6daa1f1c) | Sep 12, 2023 |
| HP            | Mini 110-3100               | [14f75b6704](https://bsd-hardware.info/?probe=14f75b6704) | Sep 11, 2023 |
| HP            | ZBook 17 G2                 | [e2d694053a](https://bsd-hardware.info/?probe=e2d694053a) | Sep 10, 2023 |
| Acer          | Monserrat                   | [9c79dbac8b](https://bsd-hardware.info/?probe=9c79dbac8b) | Sep 10, 2023 |
| Acer          | AOHAPPY2                    | [d615a8daba](https://bsd-hardware.info/?probe=d615a8daba) | Sep 10, 2023 |
| Acer          | AOHAPPY2                    | [6f5db06303](https://bsd-hardware.info/?probe=6f5db06303) | Sep 10, 2023 |
| HP            | OMEN by Laptop              | [f0fc4f47b8](https://bsd-hardware.info/?probe=f0fc4f47b8) | Sep 10, 2023 |
| Lenovo        | ThinkPad SL 2746N8G         | [07eda65608](https://bsd-hardware.info/?probe=07eda65608) | Sep 09, 2023 |
| Lenovo        | ThinkPad T480s 20L8S3LR0... | [cbac96a24f](https://bsd-hardware.info/?probe=cbac96a24f) | Sep 09, 2023 |
| Lenovo        | ThinkPad X61 Tablet 7762... | [252fc12d3b](https://bsd-hardware.info/?probe=252fc12d3b) | Sep 09, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [0f92b89ffb](https://bsd-hardware.info/?probe=0f92b89ffb) | Sep 09, 2023 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [1d5aff2e2a](https://bsd-hardware.info/?probe=1d5aff2e2a) | Sep 08, 2023 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | [d331bd9a11](https://bsd-hardware.info/?probe=d331bd9a11) | Sep 08, 2023 |
| Lenovo        | IdeaPad 1 11ADA05 82GV      | [d9d6fc45f8](https://bsd-hardware.info/?probe=d9d6fc45f8) | Sep 08, 2023 |
| HP            | Pavilion g7                 | [4870da3b0e](https://bsd-hardware.info/?probe=4870da3b0e) | Sep 07, 2023 |
| ReachingTe... | DreamQuest Pro 2022         | [2e6af170b9](https://bsd-hardware.info/?probe=2e6af170b9) | Sep 07, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [cbde759aa2](https://bsd-hardware.info/?probe=cbde759aa2) | Sep 07, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [22ec8197cc](https://bsd-hardware.info/?probe=22ec8197cc) | Sep 07, 2023 |
| Apple         | MacBookPro9,2               | [e011df1d78](https://bsd-hardware.info/?probe=e011df1d78) | Sep 07, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [68efc7ef8d](https://bsd-hardware.info/?probe=68efc7ef8d) | Sep 06, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [f42dfa2992](https://bsd-hardware.info/?probe=f42dfa2992) | Sep 06, 2023 |
| Unknown       | Unknown                     | [516b89740b](https://bsd-hardware.info/?probe=516b89740b) | Sep 06, 2023 |
| Unknown       | Unknown                     | [084127fd8b](https://bsd-hardware.info/?probe=084127fd8b) | Sep 06, 2023 |
| LG Electro... | 16U70Q-K.AAS7U1             | [82e3b2e5f8](https://bsd-hardware.info/?probe=82e3b2e5f8) | Sep 06, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [67e9eafa7e](https://bsd-hardware.info/?probe=67e9eafa7e) | Sep 05, 2023 |
| Lenovo        | ThinkPad X240 20AMA1Y3UK    | [8277297743](https://bsd-hardware.info/?probe=8277297743) | Sep 05, 2023 |
| Lenovo        | ThinkPad X61 Tablet 7762... | [00dd1bd84e](https://bsd-hardware.info/?probe=00dd1bd84e) | Sep 04, 2023 |
| HP            | G62                         | [b4777b6ba5](https://bsd-hardware.info/?probe=b4777b6ba5) | Sep 04, 2023 |
| HP            | EliteBook 8570p             | [cfecf51114](https://bsd-hardware.info/?probe=cfecf51114) | Sep 04, 2023 |
| Toshiba       | QOSMIO X775                 | [d92a05ab1d](https://bsd-hardware.info/?probe=d92a05ab1d) | Sep 04, 2023 |
| ASUSTek       | K40IN                       | [00a4f6e5a0](https://bsd-hardware.info/?probe=00a4f6e5a0) | Sep 04, 2023 |
| Shuttle       | DS67U                       | [55c2922a25](https://bsd-hardware.info/?probe=55c2922a25) | Sep 04, 2023 |
| Samsung       | 270E5J/2570EJ               | [3feb685296](https://bsd-hardware.info/?probe=3feb685296) | Sep 03, 2023 |
| Lenovo        | ThinkPad X260 20F6006XUK    | [e4f0ac6bb9](https://bsd-hardware.info/?probe=e4f0ac6bb9) | Sep 03, 2023 |
| Lenovo        | ThinkPad X260 20F6006XUK    | [4bce25bd89](https://bsd-hardware.info/?probe=4bce25bd89) | Sep 03, 2023 |
| HP            | EliteBook 8570p             | [d240fba8b7](https://bsd-hardware.info/?probe=d240fba8b7) | Sep 03, 2023 |
| ASUSTek       | 1005PXD                     | [8dac93d19d](https://bsd-hardware.info/?probe=8dac93d19d) | Sep 03, 2023 |
| ASUSTek       | K40IN                       | [df0a3f55c2](https://bsd-hardware.info/?probe=df0a3f55c2) | Sep 03, 2023 |
| Lenovo        | ThinkPad P50 20EN0012US     | [9d1b9e7af6](https://bsd-hardware.info/?probe=9d1b9e7af6) | Sep 03, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [1bfe26df6e](https://bsd-hardware.info/?probe=1bfe26df6e) | Sep 02, 2023 |
| Fujitsu       | LIFEBOOK S935               | [a6cfe011fe](https://bsd-hardware.info/?probe=a6cfe011fe) | Sep 02, 2023 |
| Apple         | MacBookPro7,1               | [d49b8413db](https://bsd-hardware.info/?probe=d49b8413db) | Sep 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [9b322dc202](https://bsd-hardware.info/?probe=9b322dc202) | Sep 02, 2023 |
| MSI           | CX62 6QD                    | [4356e5b30f](https://bsd-hardware.info/?probe=4356e5b30f) | Sep 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [044910f579](https://bsd-hardware.info/?probe=044910f579) | Sep 01, 2023 |
| HP            | EliteBook 8540w             | [5e44dfed67](https://bsd-hardware.info/?probe=5e44dfed67) | Sep 01, 2023 |
| Deciso        | NetBoard-A10                | [f95d1da00c](https://bsd-hardware.info/?probe=f95d1da00c) | Sep 01, 2023 |
| Panasonic     | CFSX4-1                     | [8f54654916](https://bsd-hardware.info/?probe=8f54654916) | Sep 01, 2023 |
| HP            | 2000                        | [6d9c442ae6](https://bsd-hardware.info/?probe=6d9c442ae6) | Aug 31, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [0ebdda5146](https://bsd-hardware.info/?probe=0ebdda5146) | Aug 31, 2023 |
| Deciso        | NetBoard-A20                | [bf4ed827a5](https://bsd-hardware.info/?probe=bf4ed827a5) | Aug 31, 2023 |
| Acer          | Aspire A515-55              | [fcbd8a3f31](https://bsd-hardware.info/?probe=fcbd8a3f31) | Aug 31, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [a308c3a87b](https://bsd-hardware.info/?probe=a308c3a87b) | Aug 31, 2023 |
| Deciso        | NetBoard-A20                | [0119402f80](https://bsd-hardware.info/?probe=0119402f80) | Aug 30, 2023 |
| Toshiba       | Satellite S55t-B            | [c2ed5fa6bd](https://bsd-hardware.info/?probe=c2ed5fa6bd) | Aug 30, 2023 |
| Dell          | Latitude E4310              | [7645de3654](https://bsd-hardware.info/?probe=7645de3654) | Aug 30, 2023 |
| HP            | EliteBook 8570p             | [0dda7a609c](https://bsd-hardware.info/?probe=0dda7a609c) | Aug 29, 2023 |
| HP            | Pavilion dv3500             | [0c3f84b285](https://bsd-hardware.info/?probe=0c3f84b285) | Aug 29, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [e74ef1d37c](https://bsd-hardware.info/?probe=e74ef1d37c) | Aug 29, 2023 |
| Fujitsu       | FMVA0803D                   | [36528b957c](https://bsd-hardware.info/?probe=36528b957c) | Aug 28, 2023 |
| Lenovo        | ThinkPad T490 20RYS06R00    | [978cd1d6bc](https://bsd-hardware.info/?probe=978cd1d6bc) | Aug 28, 2023 |
| Lenovo        | ThinkPad T450 20BV000BUS    | [f0fb53394d](https://bsd-hardware.info/?probe=f0fb53394d) | Aug 28, 2023 |
| Lenovo        | ThinkPad T430 2347GR2       | [dc8ad6c7c5](https://bsd-hardware.info/?probe=dc8ad6c7c5) | Aug 28, 2023 |
| Lenovo        | ThinkPad T430 2347GR2       | [c8c17a9db2](https://bsd-hardware.info/?probe=c8c17a9db2) | Aug 28, 2023 |
| Toshiba       | Satellite S55t-B            | [eb85f0b975](https://bsd-hardware.info/?probe=eb85f0b975) | Aug 27, 2023 |
| Dell          | Latitude 7280               | [c858f191cf](https://bsd-hardware.info/?probe=c858f191cf) | Aug 27, 2023 |
| Lenovo        | ThinkPad X230 2325IB1       | [41fbf7d1ca](https://bsd-hardware.info/?probe=41fbf7d1ca) | Aug 26, 2023 |
| Fujitsu       | FMVA0803D                   | [8ce6118bf4](https://bsd-hardware.info/?probe=8ce6118bf4) | Aug 26, 2023 |
| IGEL Techn... | H830C                       | [da76c18be6](https://bsd-hardware.info/?probe=da76c18be6) | Aug 26, 2023 |
| IGEL Techn... | H830C                       | [9d25214ddb](https://bsd-hardware.info/?probe=9d25214ddb) | Aug 26, 2023 |
| Dell          | G5 5590                     | [2e496efada](https://bsd-hardware.info/?probe=2e496efada) | Aug 26, 2023 |
| Dell          | G5 5590                     | [fd4f457391](https://bsd-hardware.info/?probe=fd4f457391) | Aug 26, 2023 |
| HP            | ENVY Notebook 13-ab0XX      | [3d96f4d5b4](https://bsd-hardware.info/?probe=3d96f4d5b4) | Aug 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [c8e95f3772](https://bsd-hardware.info/?probe=c8e95f3772) | Aug 26, 2023 |
| Getac         | V110G2                      | [884803a6bd](https://bsd-hardware.info/?probe=884803a6bd) | Aug 25, 2023 |
| Dell          | Latitude E6420              | [a085ba3865](https://bsd-hardware.info/?probe=a085ba3865) | Aug 25, 2023 |
| NVN-ED01      | Unknown                     | [dba43e889a](https://bsd-hardware.info/?probe=dba43e889a) | Aug 25, 2023 |
| Lenovo        | ThinkPad P50 20EN0009MS     | [4b3fcfa17e](https://bsd-hardware.info/?probe=4b3fcfa17e) | Aug 25, 2023 |
| ASUSTek       | S500CA                      | [019366a664](https://bsd-hardware.info/?probe=019366a664) | Aug 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [f1a43ebe23](https://bsd-hardware.info/?probe=f1a43ebe23) | Aug 24, 2023 |
| Deciso        | NetBoard-A20                | [e9e295eae3](https://bsd-hardware.info/?probe=e9e295eae3) | Aug 24, 2023 |
| Dell          | Inspiron 15-7568            | [9e555f0b24](https://bsd-hardware.info/?probe=9e555f0b24) | Aug 24, 2023 |
| Dell          | Latitude 7490               | [0b05de2297](https://bsd-hardware.info/?probe=0b05de2297) | Aug 24, 2023 |
| Datto         | Unknown                     | [418eab5eaa](https://bsd-hardware.info/?probe=418eab5eaa) | Aug 23, 2023 |
| ASUSTek       | N751JK                      | [3ac93594a2](https://bsd-hardware.info/?probe=3ac93594a2) | Aug 20, 2023 |
| Lenovo        | ThinkPad T450 20BUS0370P    | [c32aad1b1f](https://bsd-hardware.info/?probe=c32aad1b1f) | Aug 20, 2023 |
| Lenovo        | ThinkPad T450 20BUS0370P    | [5fefc051e1](https://bsd-hardware.info/?probe=5fefc051e1) | Aug 20, 2023 |
| MSI           | Sword 17 A11UD              | [4b101af84b](https://bsd-hardware.info/?probe=4b101af84b) | Aug 19, 2023 |
| Deciso        | NetBoard-A20                | [c38eb6b9bd](https://bsd-hardware.info/?probe=c38eb6b9bd) | Aug 19, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0UD0... | [3c3610a93f](https://bsd-hardware.info/?probe=3c3610a93f) | Aug 19, 2023 |
| Lenovo        | ThinkPad T495s 20QKS1812... | [0238ea2cab](https://bsd-hardware.info/?probe=0238ea2cab) | Aug 19, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [26995b5321](https://bsd-hardware.info/?probe=26995b5321) | Aug 19, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [27cf2b3e46](https://bsd-hardware.info/?probe=27cf2b3e46) | Aug 19, 2023 |
| Apple         | MacBookAir7,2               | [29fc7f6f45](https://bsd-hardware.info/?probe=29fc7f6f45) | Aug 19, 2023 |
| Acer          | Aspire A515-56              | [301a7c7b63](https://bsd-hardware.info/?probe=301a7c7b63) | Aug 19, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [1bc7f67754](https://bsd-hardware.info/?probe=1bc7f67754) | Aug 18, 2023 |
| ASUSTek       | N751JK                      | [3b430afdad](https://bsd-hardware.info/?probe=3b430afdad) | Aug 18, 2023 |
| ASUSTek       | N751JK                      | [66449212d1](https://bsd-hardware.info/?probe=66449212d1) | Aug 18, 2023 |
| Star Labs     | Lite                        | [eabab74d7b](https://bsd-hardware.info/?probe=eabab74d7b) | Aug 18, 2023 |
| Dell          | Latitude 5591               | [972da999fb](https://bsd-hardware.info/?probe=972da999fb) | Aug 18, 2023 |
| HP            | EliteBook 8570p             | [434ec73823](https://bsd-hardware.info/?probe=434ec73823) | Aug 18, 2023 |
| Dell          | Latitude 3420               | [0e171f3f87](https://bsd-hardware.info/?probe=0e171f3f87) | Aug 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [9beb5f6126](https://bsd-hardware.info/?probe=9beb5f6126) | Aug 17, 2023 |
| ASUSTek       | X553MA                      | [7334765d8a](https://bsd-hardware.info/?probe=7334765d8a) | Aug 16, 2023 |
| Acer          | Aspire A315-59              | [9a8ad54cd3](https://bsd-hardware.info/?probe=9a8ad54cd3) | Aug 16, 2023 |
| ASUSTek       | GL753VD                     | [8ccbffdd73](https://bsd-hardware.info/?probe=8ccbffdd73) | Aug 15, 2023 |
| Lenovo        | IdeaPad Slim 9 14ITL5 82... | [be7bd4b126](https://bsd-hardware.info/?probe=be7bd4b126) | Aug 15, 2023 |
| Lenovo        | ThinkPad T460p 20FXS06A1... | [378d093019](https://bsd-hardware.info/?probe=378d093019) | Aug 15, 2023 |
| ASUSTek       | N751JK                      | [664ee85747](https://bsd-hardware.info/?probe=664ee85747) | Aug 15, 2023 |
| Dell          | Latitude 5591               | [a599361016](https://bsd-hardware.info/?probe=a599361016) | Aug 13, 2023 |
| Unknown       | Unknown                     | [4176afcb0d](https://bsd-hardware.info/?probe=4176afcb0d) | Aug 13, 2023 |
| Fujitsu Si... | LIFEBOOK P1610              | [bb055a94f0](https://bsd-hardware.info/?probe=bb055a94f0) | Aug 12, 2023 |
| Lenovo        | ThinkPad X200 7458WNZ       | [3ac1d60240](https://bsd-hardware.info/?probe=3ac1d60240) | Aug 12, 2023 |
| MSI           | Modern 14 B11SBL            | [1e02b41824](https://bsd-hardware.info/?probe=1e02b41824) | Aug 12, 2023 |
| Lenovo        | ThinkPad T60 1951CZ1        | [46766bc381](https://bsd-hardware.info/?probe=46766bc381) | Aug 11, 2023 |
| ASUSTek       | N751JK                      | [46a6b88b33](https://bsd-hardware.info/?probe=46a6b88b33) | Aug 11, 2023 |
| ASUSTek       | 1001P                       | [ac53dba211](https://bsd-hardware.info/?probe=ac53dba211) | Aug 11, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [2db86b4dff](https://bsd-hardware.info/?probe=2db86b4dff) | Aug 11, 2023 |
| ASUSTek       | 1001P                       | [2424d8acdc](https://bsd-hardware.info/?probe=2424d8acdc) | Aug 11, 2023 |
| Acer          | Aspire V3-371               | [21c262aadb](https://bsd-hardware.info/?probe=21c262aadb) | Aug 09, 2023 |
| Acer          | Aspire V3-371               | [68bceee682](https://bsd-hardware.info/?probe=68bceee682) | Aug 09, 2023 |
| Notebook      | N7x0WU                      | [418b98798e](https://bsd-hardware.info/?probe=418b98798e) | Aug 09, 2023 |
| Notebook      | N7x0WU                      | [60d49b408a](https://bsd-hardware.info/?probe=60d49b408a) | Aug 09, 2023 |
| Apple         | MacBookAir4,2               | [b1c97a3a9d](https://bsd-hardware.info/?probe=b1c97a3a9d) | Aug 09, 2023 |
| MSI           | Modern 14 B11SBL            | [ba3ab230dc](https://bsd-hardware.info/?probe=ba3ab230dc) | Aug 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [9693a5fc69](https://bsd-hardware.info/?probe=9693a5fc69) | Aug 08, 2023 |
| Apple         | MacBookAir4,2               | [4fdd124b61](https://bsd-hardware.info/?probe=4fdd124b61) | Aug 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [9c01814bdc](https://bsd-hardware.info/?probe=9c01814bdc) | Aug 07, 2023 |
| MSI           | Modern 14 B11SBL            | [48483213f9](https://bsd-hardware.info/?probe=48483213f9) | Aug 06, 2023 |
| Dell          | Inspiron 14-3467            | [5db7e9b7a1](https://bsd-hardware.info/?probe=5db7e9b7a1) | Aug 05, 2023 |
| Compaq        | Presario CQ-17              | [f97feb2db0](https://bsd-hardware.info/?probe=f97feb2db0) | Aug 04, 2023 |
| ASUSTek       | ROG Strix G513QC_G513QC     | [b90e62e27d](https://bsd-hardware.info/?probe=b90e62e27d) | Aug 04, 2023 |
| Apple         | MacBookPro11,1              | [4a2c98005b](https://bsd-hardware.info/?probe=4a2c98005b) | Aug 04, 2023 |
| Samsung       | Q210                        | [2e25c6d2ec](https://bsd-hardware.info/?probe=2e25c6d2ec) | Aug 03, 2023 |
| Samsung       | Q210                        | [d3c5ab902d](https://bsd-hardware.info/?probe=d3c5ab902d) | Aug 03, 2023 |
| HP            | EliteBook 840 G5            | [6496fe0cfe](https://bsd-hardware.info/?probe=6496fe0cfe) | Aug 03, 2023 |
| Chuwi         | CoreBook X                  | [2854f97c81](https://bsd-hardware.info/?probe=2854f97c81) | Aug 01, 2023 |
| Unknown       | Unknown                     | [09d17597cf](https://bsd-hardware.info/?probe=09d17597cf) | Aug 01, 2023 |
| Unknown       | Unknown                     | [2a2e7a98e3](https://bsd-hardware.info/?probe=2a2e7a98e3) | Aug 01, 2023 |
| Deciso        | NetBoard-A10                | [65667b2f29](https://bsd-hardware.info/?probe=65667b2f29) | Aug 01, 2023 |
| Lenovo        | IdeaPad S210 Touch 20257    | [1e372622c1](https://bsd-hardware.info/?probe=1e372622c1) | Jul 31, 2023 |
| Deciso        | NetBoard-A20                | [9bd5d8fd54](https://bsd-hardware.info/?probe=9bd5d8fd54) | Jul 31, 2023 |
| Lenovo        | ThinkPad X270 20HNA04GCD    | [6547f4a73b](https://bsd-hardware.info/?probe=6547f4a73b) | Jul 31, 2023 |
| Deciso        | NetBoard-A10                | [42fcdacbf7](https://bsd-hardware.info/?probe=42fcdacbf7) | Jul 31, 2023 |
| Lenovo        | ThinkPad X230 23202DG       | [f8ade878ce](https://bsd-hardware.info/?probe=f8ade878ce) | Jul 30, 2023 |
| ASUSTek       | X555LD                      | [9c0c41b663](https://bsd-hardware.info/?probe=9c0c41b663) | Jul 30, 2023 |
| Acer          | Aspire E5-511               | [93faaaff91](https://bsd-hardware.info/?probe=93faaaff91) | Jul 30, 2023 |
| HP            | EliteBook 8570p             | [2619fadb11](https://bsd-hardware.info/?probe=2619fadb11) | Jul 29, 2023 |
| Fujitsu Si... | AMILO Li3710                | [7a5d32eb7f](https://bsd-hardware.info/?probe=7a5d32eb7f) | Jul 29, 2023 |
| HP            | Notebook                    | [360790274a](https://bsd-hardware.info/?probe=360790274a) | Jul 29, 2023 |
| Apple         | MacBookPro9,2               | [53e133857b](https://bsd-hardware.info/?probe=53e133857b) | Jul 29, 2023 |
| HP            | Pavilion g6                 | [bdd2349f1c](https://bsd-hardware.info/?probe=bdd2349f1c) | Jul 28, 2023 |
| Dell          | Latitude 5480               | [e1521ed9d2](https://bsd-hardware.info/?probe=e1521ed9d2) | Jul 26, 2023 |
| Dell          | Inspiron 3180               | [e97b5d9219](https://bsd-hardware.info/?probe=e97b5d9219) | Jul 25, 2023 |
| Lenovo        | ThinkPad T410 2522NP6       | [194b8efa98](https://bsd-hardware.info/?probe=194b8efa98) | Jul 25, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [1b3ba2b86a](https://bsd-hardware.info/?probe=1b3ba2b86a) | Jul 25, 2023 |
| Deciso        | Netboard A20                | [9030d92418](https://bsd-hardware.info/?probe=9030d92418) | Jul 25, 2023 |
| ASUSTek       | 1015PX                      | [b0745153e4](https://bsd-hardware.info/?probe=b0745153e4) | Jul 24, 2023 |
| Panasonic     | CFSX4-1                     | [461ad23cc9](https://bsd-hardware.info/?probe=461ad23cc9) | Jul 24, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [60dac781b2](https://bsd-hardware.info/?probe=60dac781b2) | Jul 24, 2023 |
| Lenovo        | B590 20208                  | [ce1aade2c0](https://bsd-hardware.info/?probe=ce1aade2c0) | Jul 24, 2023 |
| Panasonic     | CFSX4-1                     | [1ac1ddd084](https://bsd-hardware.info/?probe=1ac1ddd084) | Jul 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [173fe60308](https://bsd-hardware.info/?probe=173fe60308) | Jul 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [26e44ab6e6](https://bsd-hardware.info/?probe=26e44ab6e6) | Jul 23, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [020e17c2f8](https://bsd-hardware.info/?probe=020e17c2f8) | Jul 23, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [56fc67d3eb](https://bsd-hardware.info/?probe=56fc67d3eb) | Jul 22, 2023 |
| NOBLEX        | SF20BA                      | [a6a17eb5ca](https://bsd-hardware.info/?probe=a6a17eb5ca) | Jul 21, 2023 |
| Panasonic     | CF-F9JYFNDR                 | [be7b261f26](https://bsd-hardware.info/?probe=be7b261f26) | Jul 21, 2023 |
| HP            | EliteBook 8570p             | [9f4f71236e](https://bsd-hardware.info/?probe=9f4f71236e) | Jul 21, 2023 |
| Lenovo        | ThinkPad T440s 20ARS1BK0... | [01f4886e09](https://bsd-hardware.info/?probe=01f4886e09) | Jul 21, 2023 |
| Lenovo        | ThinkPad T520 42435GG       | [f3aa06579e](https://bsd-hardware.info/?probe=f3aa06579e) | Jul 20, 2023 |
| ASUSTek       | 900                         | [2e55f5d4cc](https://bsd-hardware.info/?probe=2e55f5d4cc) | Jul 20, 2023 |
| Acer          | Aspire 4736Z                | [bccf97f694](https://bsd-hardware.info/?probe=bccf97f694) | Jul 20, 2023 |
| Toshiba       | Satellite L655              | [67080aeb1d](https://bsd-hardware.info/?probe=67080aeb1d) | Jul 20, 2023 |
| Dell          | Precision 5550              | [4c9dd227a7](https://bsd-hardware.info/?probe=4c9dd227a7) | Jul 20, 2023 |
| ASUSTek       | 1015PX                      | [dc06c76cf9](https://bsd-hardware.info/?probe=dc06c76cf9) | Jul 19, 2023 |
| MSI           | Sword 17 A11UD              | [c9852c1ee3](https://bsd-hardware.info/?probe=c9852c1ee3) | Jul 19, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | [5fcffa5bd6](https://bsd-hardware.info/?probe=5fcffa5bd6) | Jul 19, 2023 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | [386a80104d](https://bsd-hardware.info/?probe=386a80104d) | Jul 19, 2023 |
| IBM           | ThinkPad T43 1871F1G        | [d6fbc6ebfb](https://bsd-hardware.info/?probe=d6fbc6ebfb) | Jul 18, 2023 |
| ASUSTek       | K42Jr                       | [256168572a](https://bsd-hardware.info/?probe=256168572a) | Jul 18, 2023 |
| Deciso        | NetBoard-A20                | [c4a85b9853](https://bsd-hardware.info/?probe=c4a85b9853) | Jul 18, 2023 |
| Samsung       | 100NZB                      | [5515e88fc1](https://bsd-hardware.info/?probe=5515e88fc1) | Jul 17, 2023 |
| Samsung       | RC530/RC730                 | [b76e5e8a87](https://bsd-hardware.info/?probe=b76e5e8a87) | Jul 17, 2023 |
| Lenovo        | ThinkPad W530 2447GW3       | [57b4bfc1bf](https://bsd-hardware.info/?probe=57b4bfc1bf) | Jul 17, 2023 |
| Lenovo        | ThinkPad X395 20NLCTO1WW    | [826ba238d8](https://bsd-hardware.info/?probe=826ba238d8) | Jul 16, 2023 |
| Lenovo        | ThinkPad X395 20NLCTO1WW    | [0273f2f271](https://bsd-hardware.info/?probe=0273f2f271) | Jul 16, 2023 |
| Lenovo        | B590 20208                  | [f734b93999](https://bsd-hardware.info/?probe=f734b93999) | Jul 16, 2023 |
| HP            | Laptop 15s-eq3xxx           | [ff4dbbacdf](https://bsd-hardware.info/?probe=ff4dbbacdf) | Jul 15, 2023 |
| Lenovo        | ThinkPad R14 Gen 4 21E5A... | [e0fc7135e5](https://bsd-hardware.info/?probe=e0fc7135e5) | Jul 15, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [d4265533e2](https://bsd-hardware.info/?probe=d4265533e2) | Jul 15, 2023 |
| HP            | EliteBook 6930p             | [12124d8753](https://bsd-hardware.info/?probe=12124d8753) | Jul 15, 2023 |
| Sony          | VPCX115KX                   | [9dab449a23](https://bsd-hardware.info/?probe=9dab449a23) | Jul 15, 2023 |
| Deciso        | Netboard A20                | [e82dfa5520](https://bsd-hardware.info/?probe=e82dfa5520) | Jul 14, 2023 |
| 10ZiG Tech... | 5900q                       | [3c3668fcd2](https://bsd-hardware.info/?probe=3c3668fcd2) | Jul 14, 2023 |
| Lenovo        | ThinkPad T470s 20HGS3AX0... | [785b9af1f4](https://bsd-hardware.info/?probe=785b9af1f4) | Jul 13, 2023 |
| Deciso        | NetBoard-A10                | [535720220a](https://bsd-hardware.info/?probe=535720220a) | Jul 13, 2023 |
| HP            | Laptop 14-cf2xxx            | [91965a9c00](https://bsd-hardware.info/?probe=91965a9c00) | Jul 13, 2023 |
| Lenovo        | G550 2958                   | [bc36695565](https://bsd-hardware.info/?probe=bc36695565) | Jul 13, 2023 |
| Tactus        | GeoBook 140                 | [4b7383c876](https://bsd-hardware.info/?probe=4b7383c876) | Jul 11, 2023 |
| HONOR         | NMH-WCX9                    | [f573d1d5c4](https://bsd-hardware.info/?probe=f573d1d5c4) | Jul 11, 2023 |
| ASUSTek       | X541UVK                     | [17f58b70e4](https://bsd-hardware.info/?probe=17f58b70e4) | Jul 10, 2023 |
| Getac         | F110G2                      | [b7b9efc38d](https://bsd-hardware.info/?probe=b7b9efc38d) | Jul 09, 2023 |
| Lenovo        | ThinkPad X250 20CLS13Q06    | [c318ab3cc7](https://bsd-hardware.info/?probe=c318ab3cc7) | Jul 09, 2023 |
| Lenovo        | ThinkPad T480s 20L8S45W0... | [80ac9dddda](https://bsd-hardware.info/?probe=80ac9dddda) | Jul 08, 2023 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | [4274ca291e](https://bsd-hardware.info/?probe=4274ca291e) | Jul 08, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | [7119cd7ae3](https://bsd-hardware.info/?probe=7119cd7ae3) | Jul 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [03e83e60ca](https://bsd-hardware.info/?probe=03e83e60ca) | Jul 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [3096d8532a](https://bsd-hardware.info/?probe=3096d8532a) | Jul 07, 2023 |
| HP            | EliteBook 8570p             | [44b85aad5e](https://bsd-hardware.info/?probe=44b85aad5e) | Jul 07, 2023 |
| Lenovo        | ThinkPad T590 20N4001PUS    | [9e3b26b01b](https://bsd-hardware.info/?probe=9e3b26b01b) | Jul 06, 2023 |
| Dell          | Latitude E6420              | [3151e6d3bb](https://bsd-hardware.info/?probe=3151e6d3bb) | Jul 05, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [2519fb81d6](https://bsd-hardware.info/?probe=2519fb81d6) | Jul 05, 2023 |
| Dell          | G3 3579                     | [8d9b29f231](https://bsd-hardware.info/?probe=8d9b29f231) | Jul 05, 2023 |
| Dell          | G3 3579                     | [f6fc15b1f4](https://bsd-hardware.info/?probe=f6fc15b1f4) | Jul 05, 2023 |
| Deciso        | Netboard A20                | [dd0a39a4d0](https://bsd-hardware.info/?probe=dd0a39a4d0) | Jul 05, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1HL0... | [f7b57506f0](https://bsd-hardware.info/?probe=f7b57506f0) | Jul 04, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | [f74b33bc25](https://bsd-hardware.info/?probe=f74b33bc25) | Jul 03, 2023 |
| HP            | Compaq Presario CQ61        | [d070292855](https://bsd-hardware.info/?probe=d070292855) | Jul 03, 2023 |
| Unknown       | Unknown                     | [13c087ef5e](https://bsd-hardware.info/?probe=13c087ef5e) | Jul 03, 2023 |
| Unknown       | Unknown                     | [ae2bb37185](https://bsd-hardware.info/?probe=ae2bb37185) | Jul 03, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | [f9f815c60e](https://bsd-hardware.info/?probe=f9f815c60e) | Jul 02, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | [39e46fd477](https://bsd-hardware.info/?probe=39e46fd477) | Jul 02, 2023 |
| ASUSTek       | 1005PXD                     | [246032ee65](https://bsd-hardware.info/?probe=246032ee65) | Jul 02, 2023 |
| Unknown       | Unknown                     | [3725d44c33](https://bsd-hardware.info/?probe=3725d44c33) | Jul 01, 2023 |
| Lenovo        | ThinkPad T60 20076PU        | [cb47bfef12](https://bsd-hardware.info/?probe=cb47bfef12) | Jun 30, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [1aff07438c](https://bsd-hardware.info/?probe=1aff07438c) | Jun 28, 2023 |
| HP            | EliteBook 840 G3            | [17834256ca](https://bsd-hardware.info/?probe=17834256ca) | Jun 28, 2023 |
| Deciso        | NetBoard-A10                | [2eff359d8f](https://bsd-hardware.info/?probe=2eff359d8f) | Jun 28, 2023 |
| HP            | EliteBook 8570p             | [03c29939fc](https://bsd-hardware.info/?probe=03c29939fc) | Jun 28, 2023 |
| Deciso        | DEC2700 - OPNsense Appli... | [aedd3a8255](https://bsd-hardware.info/?probe=aedd3a8255) | Jun 28, 2023 |
| HP            | EliteBook 8570p             | [748ae83ba1](https://bsd-hardware.info/?probe=748ae83ba1) | Jun 27, 2023 |
| Dell          | XPS 13 9360                 | [648c09752f](https://bsd-hardware.info/?probe=648c09752f) | Jun 27, 2023 |
| HP            | EliteBook 850 G5            | [4bae8cd192](https://bsd-hardware.info/?probe=4bae8cd192) | Jun 27, 2023 |
| Deciso        | OPNsense Appliance          | [be0008eb2a](https://bsd-hardware.info/?probe=be0008eb2a) | Jun 26, 2023 |
| Dell          | Latitude 3420               | [057f065baa](https://bsd-hardware.info/?probe=057f065baa) | Jun 26, 2023 |
| Lenovo        | ThinkPad T440p 20AW000BU... | [9a7628d17b](https://bsd-hardware.info/?probe=9a7628d17b) | Jun 26, 2023 |
| Dell          | Inspiron 5570               | [a6e959358f](https://bsd-hardware.info/?probe=a6e959358f) | Jun 25, 2023 |
| HP            | EliteBook 8570p             | [e7dfbf94d0](https://bsd-hardware.info/?probe=e7dfbf94d0) | Jun 25, 2023 |
| Dell          | Latitude E4310              | [9cdd4909fe](https://bsd-hardware.info/?probe=9cdd4909fe) | Jun 24, 2023 |
| HP            | Laptop 15-bs1xx             | [dc0d876d7b](https://bsd-hardware.info/?probe=dc0d876d7b) | Jun 24, 2023 |
| HP            | Laptop 15-ra0xx             | [8c31502b68](https://bsd-hardware.info/?probe=8c31502b68) | Jun 24, 2023 |

...


System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| helloSystem 0.8.1    | 243       | 6.62%   |
| helloSystem 0.7.0    | 226       | 6.16%   |
| helloSystem 0.8.0    | 134       | 3.65%   |
| helloSystem 0.5.0    | 116       | 3.16%   |
| FreeBSD 13.1         | 115       | 3.13%   |
| FreeBSD 13.0         | 111       | 3.02%   |
| helloSystem 0.4.0    | 92        | 2.51%   |
| OpenBSD 6.8          | 91        | 2.48%   |
| FreeBSD 14.0-CURRENT | 75        | 2.04%   |
| FreeBSD 13.2         | 74        | 2.02%   |
| helloSystem 0.6.0    | 72        | 1.96%   |
| FreeBSD 14.0         | 63        | 1.72%   |
| helloSystem 0.9.0    | 60        | 1.63%   |
| FreeBSD 12.2         | 59        | 1.61%   |
| GhostBSD 20.04.02    | 58        | 1.58%   |
| OpenBSD 7.2          | 56        | 1.53%   |
| OpenBSD 6.9          | 55        | 1.5%    |
| OpenBSD 7.3          | 52        | 1.42%   |
| OpenBSD 7.0          | 51        | 1.39%   |
| OpenBSD 7.1          | 41        | 1.12%   |
| FreeBSD 13.1-p5      | 41        | 1.12%   |
| OpenBSD 7.4          | 38        | 1.04%   |
| FreeBSD 13.0-p4      | 35        | 0.95%   |
| NomadBSD 1.3.2       | 34        | 0.93%   |
| helloSystem 0.8.2    | 34        | 0.93%   |
| FreeBSD 12.2-p2      | 34        | 0.93%   |
| NomadBSD 5806f915    | 32        | 0.87%   |
| FreeBSD 13.0-CURRENT | 31        | 0.84%   |
| GhostBSD 21.08.27    | 29        | 0.79%   |
| FreeBSD 13.0-STABLE  | 28        | 0.76%   |
| FreeBSD 12.1         | 28        | 0.76%   |
| NomadBSD 20221130    | 27        | 0.74%   |
| FreeBSD 12.1-p8      | 26        | 0.71%   |
| FreeBSD 13.0-p5      | 25        | 0.68%   |
| OpenBSD 6.7          | 23        | 0.63%   |
| GhostBSD 24.01.1     | 23        | 0.63%   |
| FreeBSD 14.0-p6      | 23        | 0.63%   |
| FreeBSD 13.0-p3      | 23        | 0.63%   |
| FreeBSD 12.2-p4      | 23        | 0.63%   |
| FreeBSD 12.1-p10     | 23        | 0.63%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 1166      | 37.43%  |
| helloSystem | 916       | 29.41%  |
| OpenBSD     | 326       | 10.47%  |
| OPNsense    | 290       | 9.31%   |
| GhostBSD    | 212       | 6.81%   |
| NomadBSD    | 134       | 4.3%    |
| NetBSD      | 35        | 1.12%   |
| HardenedBSD | 7         | 0.22%   |
| DragonFly   | 7         | 0.22%   |
| FuryBSD     | 6         | 0.19%   |
| FuguIta     | 5         | 0.16%   |
| MidnightBSD | 4         | 0.13%   |
| OS108       | 2         | 0.06%   |
| MyBee       | 2         | 0.06%   |
| pfSense     | 1         | 0.03%   |
| PC-BSD      | 1         | 0.03%   |
| LibertyBSD  | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| amd64  | 2906      | 96.67%  |
| i386   | 93        | 3.09%   |
| macppc | 5         | 0.17%   |
| arm64  | 2         | 0.07%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| helloDesktop  | 1026      | 32.08%  |
| Console       | 478       | 14.95%  |
| XFCE          | 338       | 10.57%  |
| KDE5          | 277       | 8.66%   |
| MATE          | 253       | 7.91%   |
| fvwm          | 183       | 5.72%   |
| Openbox       | 146       | 4.57%   |
| GNOME         | 132       | 4.13%   |
| TWM           | 108       | 3.38%   |
| i3            | 87        | 2.72%   |
| LXQt          | 26        | 0.81%   |
| Cinnamon      | 24        | 0.75%   |
| AwesomeWM     | 17        | 0.53%   |
| Fluxbox       | 12        | 0.38%   |
| Enlightenment | 9         | 0.28%   |
| DWM           | 9         | 0.28%   |
| xinitrc       | 8         | 0.25%   |
| LXDE          | 8         | 0.25%   |
| Lumina        | 5         | 0.16%   |
| ICEWM         | 5         | 0.16%   |
| Picom         | 4         | 0.13%   |
| GNUstep       | 4         | 0.13%   |
| CTWM          | 4         | 0.13%   |
| spectrwm      | 3         | 0.09%   |
| iwm           | 3         | 0.09%   |
| Budgie        | 3         | 0.09%   |
| X-Cinnamon    | 2         | 0.06%   |
| Window Maker  | 2         | 0.06%   |
| sway          | 2         | 0.06%   |
| StumpWM       | 2         | 0.06%   |
| Mutter        | 2         | 0.06%   |
| KDE           | 2         | 0.06%   |
| Hyprland      | 2         | 0.06%   |
| Awesome       | 2         | 0.06%   |
| Xfwm4         | 1         | 0.03%   |
| wlroots       | 1         | 0.03%   |
| Wayfire       | 1         | 0.03%   |
| sdorfehs      | 1         | 0.03%   |
| Potato        | 1         | 0.03%   |
| KDE6          | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2503      | 82.25%  |
| Console | 489       | 16.07%  |
| Wayland | 51        | 1.68%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 1207      | 38.42%  |
| Console | 1086      | 34.56%  |
| LightDM | 331       | 10.53%  |
| SDDM    | 322       | 10.25%  |
| XDM     | 93        | 2.96%   |
| GDM     | 86        | 2.74%   |
| Ly      | 14        | 0.45%   |
| PCDM    | 2         | 0.06%   |
| WDM     | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| en_US           | 974       | 30.53%  |
| Unknown         | 921       | 28.87%  |
| C               | 686       | 21.5%   |
| ru_RU           | 95        | 2.98%   |
| fr_FR           | 81        | 2.54%   |
| de_DE           | 70        | 2.19%   |
| en              | 51        | 1.6%    |
| en_GB           | 39        | 1.22%   |
| es_ES           | 34        | 1.07%   |
| zh_CN           | 25        | 0.78%   |
| pl_PL           | 21        | 0.66%   |
| pt_BR           | 19        | 0.6%    |
| it_IT           | 18        | 0.56%   |
| en_CA           | 8         | 0.25%   |
| de              | 8         | 0.25%   |
| zh_TW           | 7         | 0.22%   |
| en_AU           | 7         | 0.22%   |
| ru              | 6         | 0.19%   |
| pt              | 6         | 0.19%   |
| nl_NL           | 6         | 0.19%   |
| fi_FI           | 6         | 0.19%   |
| cs_CZ           | 6         | 0.19%   |
| ja_JP           | 5         | 0.16%   |
| en_NZ           | 5         | 0.16%   |
| uk_UA           | 4         | 0.13%   |
| tr_TR           | 4         | 0.13%   |
| nb_NO           | 4         | 0.13%   |
| es              | 4         | 0.13%   |
| en_US.ISO8859-1 | 4         | 0.13%   |
| ko_KR           | 3         | 0.09%   |
| es_AR           | 3         | 0.09%   |
| en_US.US-ASCII  | 3         | 0.09%   |
| de_CH           | 3         | 0.09%   |
| sv_SE           | 2         | 0.06%   |
| pt_PT           | 2         | 0.06%   |
| jp_JP           | 2         | 0.06%   |
| it              | 2         | 0.06%   |
| hu_HU           | 2         | 0.06%   |
| fr              | 2         | 0.06%   |
| es_MX           | 2         | 0.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 2448      | 80.39%  |
| BIOS | 597       | 19.61%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Zfs     | 1692      | 54.23%  |
| Ufs     | 739       | 23.69%  |
| Cd9660  | 349       | 11.19%  |
| Ffs     | 332       | 10.64%  |
| Hammer2 | 6         | 0.19%   |
| Xfs     | 1         | 0.03%   |
| Nfs     | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 2690      | 88.55%  |
| MBR     | 310       | 10.2%   |
| Unknown | 30        | 0.99%   |
| BSD     | 8         | 0.26%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 970       | 32.3%   |
| Dell                | 444       | 14.79%  |
| Hewlett-Packard     | 300       | 9.99%   |
| ASUSTek Computer    | 210       | 6.99%   |
| Acer                | 164       | 5.46%   |
| Apple               | 136       | 4.53%   |
| Deciso              | 95        | 3.16%   |
| Unknown             | 69        | 2.3%    |
| Toshiba             | 64        | 2.13%   |
| Samsung Electronics | 53        | 1.76%   |
| Sony                | 36        | 1.2%    |
| MSI                 | 35        | 1.17%   |
| Fujitsu             | 33        | 1.1%    |
| Google              | 29        | 0.97%   |
| Intel               | 25        | 0.83%   |
| Panasonic           | 21        | 0.7%    |
| TUXEDO              | 19        | 0.63%   |
| Notebook            | 19        | 0.63%   |
| HUAWEI              | 18        | 0.6%    |
| System76            | 16        | 0.53%   |
| IBM                 | 15        | 0.5%    |
| LG Electronics      | 10        | 0.33%   |
| Timi                | 9         | 0.3%    |
| Shuttle             | 9         | 0.3%    |
| Packard Bell        | 9         | 0.3%    |
| Framework           | 9         | 0.3%    |
| Alienware           | 9         | 0.3%    |
| Fujitsu Siemens     | 8         | 0.27%   |
| Star Labs           | 7         | 0.23%   |
| eMachines           | 7         | 0.23%   |
| Gigabyte Technology | 6         | 0.2%    |
| Gateway             | 6         | 0.2%    |
| SLIMBOOK            | 5         | 0.17%   |
| Razer               | 5         | 0.17%   |
| Medion              | 5         | 0.17%   |
| Datto               | 5         | 0.17%   |
| Clevo               | 5         | 0.17%   |
| Chuwi               | 5         | 0.17%   |
| GPD                 | 4         | 0.13%   |
| F-Plus Mobile       | 4         | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 86        | 2.86%   |
| Deciso NetBoard-A20                 | 27        | 0.9%    |
| Deciso NetBoard-A10                 | 27        | 0.9%    |
| Deciso Netboard A20                 | 24        | 0.8%    |
| Intel H81U                          | 12        | 0.4%    |
| HP Notebook                         | 10        | 0.33%   |
| Dell Latitude E6420                 | 10        | 0.33%   |
| HP EliteBook 840 G3                 | 9         | 0.3%    |
| Dell XPS 13 9360                    | 9         | 0.3%    |
| Dell Latitude E7240                 | 9         | 0.3%    |
| Dell Latitude E6430                 | 9         | 0.3%    |
| Deciso OPNsense Appliance           | 9         | 0.3%    |
| Apple MacBookPro9,2                 | 9         | 0.3%    |
| Framework Laptop                    | 8         | 0.27%   |
| Dell Inspiron 3442                  | 8         | 0.27%   |
| Deciso DEC2700 - OPNsense Appliance | 8         | 0.27%   |
| Apple MacBook5,1                    | 8         | 0.27%   |
| Apple MacBook4,1                    | 8         | 0.27%   |
| Dell Inspiron 3542                  | 7         | 0.23%   |
| Apple MacBookPro8,1                 | 7         | 0.23%   |
| Apple MacBookAir7,2                 | 7         | 0.23%   |
| Apple MacBookAir6,2                 | 7         | 0.23%   |
| Lenovo ThinkPad X200 745969G        | 6         | 0.2%    |
| HP Pavilion g6                      | 6         | 0.2%    |
| HP Pavilion dv6                     | 6         | 0.2%    |
| HP 2000                             | 6         | 0.2%    |
| Dell Latitude E6540                 | 6         | 0.2%    |
| Dell Latitude E5570                 | 6         | 0.2%    |
| Dell Latitude 7490                  | 6         | 0.2%    |
| Dell Inspiron 15-3567               | 6         | 0.2%    |
| TUXEDO Pulse 15 Gen1                | 5         | 0.17%   |
| Lenovo ThinkPad X220 4286CTO        | 5         | 0.17%   |
| HP Pavilion Notebook                | 5         | 0.17%   |
| Dell Precision M4800                | 5         | 0.17%   |
| Dell Latitude E5470                 | 5         | 0.17%   |
| Dell Latitude 7280                  | 5         | 0.17%   |
| Dell Latitude 5400                  | 5         | 0.17%   |
| Dell Inspiron 3521                  | 5         | 0.17%   |
| Dell Inspiron 15 7000 Gaming        | 5         | 0.17%   |
| Apple MacBookPro6,2                 | 5         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 746       | 24.84%  |
| Dell Latitude       | 202       | 6.73%   |
| Dell Inspiron       | 116       | 3.86%   |
| Acer Aspire         | 109       | 3.63%   |
| Lenovo IdeaPad      | 93        | 3.1%    |
| Unknown             | 86        | 2.86%   |
| HP EliteBook        | 57        | 1.9%    |
| HP Pavilion         | 52        | 1.73%   |
| Dell Precision      | 45        | 1.5%    |
| Toshiba Satellite   | 43        | 1.43%   |
| HP ProBook          | 42        | 1.4%    |
| HP Laptop           | 37        | 1.23%   |
| Dell XPS            | 37        | 1.23%   |
| ASUS VivoBook       | 28        | 0.93%   |
| Deciso NetBoard-A20 | 27        | 0.9%    |
| Deciso NetBoard-A10 | 27        | 0.9%    |
| Fujitsu LIFEBOOK    | 26        | 0.87%   |
| Lenovo Legion       | 24        | 0.8%    |
| Dell Vostro         | 24        | 0.8%    |
| Deciso Netboard     | 24        | 0.8%    |
| Lenovo Yoga         | 17        | 0.57%   |
| HP Compaq           | 16        | 0.53%   |
| HP ZBook            | 14        | 0.47%   |
| ASUS ASUS           | 14        | 0.47%   |
| IBM ThinkPad        | 13        | 0.43%   |
| Apple MacBookPro8   | 13        | 0.43%   |
| Acer TravelMate     | 13        | 0.43%   |
| Intel H81U          | 12        | 0.4%    |
| HP OMEN             | 11        | 0.37%   |
| Apple MacBookPro9   | 11        | 0.37%   |
| Apple MacBookPro11  | 11        | 0.37%   |
| Apple MacBook5      | 11        | 0.37%   |
| Lenovo ThinkBook    | 10        | 0.33%   |
| HP Notebook         | 10        | 0.33%   |
| ASUS ZenBook        | 10        | 0.33%   |
| Apple MacBookPro5   | 10        | 0.33%   |
| Acer Nitro          | 10        | 0.33%   |
| TUXEDO Pulse        | 9         | 0.3%    |
| Framework Laptop    | 9         | 0.3%    |
| Deciso OPNsense     | 9         | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 288       | 9.59%   |
| 2021    | 258       | 8.59%   |
| 2019    | 244       | 8.13%   |
| 2011    | 214       | 7.13%   |
| 2013    | 207       | 6.89%   |
| 2022    | 203       | 6.76%   |
| 2018    | 200       | 6.66%   |
| 2016    | 189       | 6.29%   |
| 2015    | 189       | 6.29%   |
| 2012    | 184       | 6.13%   |
| 2017    | 152       | 5.06%   |
| 2010    | 147       | 4.9%    |
| 2014    | 142       | 4.73%   |
| 2009    | 105       | 3.5%    |
| 2008    | 86        | 2.86%   |
| 2023    | 77        | 2.56%   |
| 2007    | 48        | 1.6%    |
| 2006    | 27        | 0.9%    |
| Unknown | 13        | 0.43%   |
| 2005    | 9         | 0.3%    |
| 2024    | 8         | 0.27%   |
| 2004    | 5         | 0.17%   |
| 2003    | 5         | 0.17%   |
| 2002    | 3         | 0.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 3003      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2949      | 98.2%   |
| Yes  | 54        | 1.8%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 1104      | 36.2%   |
| 16.01-24.0  | 711       | 23.31%  |
| 4.01-8.0    | 683       | 22.39%  |
| 32.01-64.0  | 185       | 6.07%   |
| 2.01-3.0    | 141       | 4.62%   |
| 3.01-4.0    | 79        | 2.59%   |
| 64.01-256.0 | 45        | 1.48%   |
| 24.01-32.0  | 37        | 1.21%   |
| 0.51-1.0    | 32        | 1.05%   |
| 1.01-2.0    | 23        | 0.75%   |
| 0.01-0.5    | 9         | 0.3%    |
| 0           | 1         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Notebooks | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 1674      | 54.19%  |
| 0.51-1.0    | 871       | 28.2%   |
| 1.01-2.0    | 309       | 10%     |
| 2.01-3.0    | 94        | 3.04%   |
| Unknown     | 40        | 1.29%   |
| 4.01-8.0    | 33        | 1.07%   |
| 0           | 25        | 0.81%   |
| 8.01-16.0   | 21        | 0.68%   |
| 3.01-4.0    | 11        | 0.36%   |
| 24.01-32.0  | 4         | 0.13%   |
| 16.01-24.0  | 4         | 0.13%   |
| 32.01-64.0  | 2         | 0.06%   |
| 64.01-256.0 | 1         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2201      | 70.82%  |
| 2      | 557       | 17.92%  |
| 0      | 265       | 8.53%   |
| 3      | 73        | 2.35%   |
| 4      | 11        | 0.35%   |
| 58     | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2215      | 73.1%   |
| Yes       | 815       | 26.9%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2542      | 84.62%  |
| No        | 462       | 15.38%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2779      | 92.29%  |
| No        | 232       | 7.71%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2008      | 66.1%   |
| No        | 1030      | 33.9%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 578       | 19.09%  |
| Germany     | 339       | 11.2%   |
| Russia      | 217       | 7.17%   |
| France      | 157       | 5.19%   |
| UK          | 125       | 4.13%   |
| Brazil      | 114       | 3.77%   |
| Canada      | 98        | 3.24%   |
| Poland      | 90        | 2.97%   |
| China       | 82        | 2.71%   |
| Spain       | 78        | 2.58%   |
| Italy       | 78        | 2.58%   |
| Netherlands | 72        | 2.38%   |
| Australia   | 57        | 1.88%   |
| Switzerland | 51        | 1.68%   |
| Indonesia   | 51        | 1.68%   |
| India       | 47        | 1.55%   |
| Ukraine     | 44        | 1.45%   |
| Sweden      | 39        | 1.29%   |
| Austria     | 34        | 1.12%   |
| Hungary     | 31        | 1.02%   |
| Czechia     | 30        | 0.99%   |
| Romania     | 29        | 0.96%   |
| Japan       | 29        | 0.96%   |
| Mexico      | 27        | 0.89%   |
| Finland     | 26        | 0.86%   |
| Turkey      | 25        | 0.83%   |
| Norway      | 25        | 0.83%   |
| Argentina   | 24        | 0.79%   |
| Bulgaria    | 22        | 0.73%   |
| Portugal    | 20        | 0.66%   |
| Belgium     | 19        | 0.63%   |
| Taiwan      | 17        | 0.56%   |
| Denmark     | 17        | 0.56%   |
| Vietnam     | 15        | 0.5%    |
| Greece      | 15        | 0.5%    |
| Colombia    | 15        | 0.5%    |
| Philippines | 13        | 0.43%   |
| New Zealand | 13        | 0.43%   |
| Lithuania   | 12        | 0.4%    |
| Chile       | 12        | 0.4%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 85        | 2.58%   |
| Berlin            | 35        | 1.06%   |
| St Petersburg     | 29        | 0.88%   |
| Paris             | 29        | 0.88%   |
| Vienna            | 28        | 0.85%   |
| Montreal          | 27        | 0.82%   |
| Brooklyn          | 23        | 0.7%    |
| Zurich            | 22        | 0.67%   |
| Sydney            | 21        | 0.64%   |
| Jakarta           | 20        | 0.61%   |
| Warsaw            | 16        | 0.49%   |
| Saint-Laurent     | 16        | 0.49%   |
| Amsterdam         | 16        | 0.49%   |
| Budapest          | 15        | 0.46%   |
| Seattle           | 14        | 0.43%   |
| Rome              | 14        | 0.43%   |
| Kyiv              | 14        | 0.43%   |
| Portland          | 13        | 0.39%   |
| Munich            | 13        | 0.39%   |
| Madrid            | 13        | 0.39%   |
| Frankfurt am Main | 13        | 0.39%   |
| Wroclaw           | 12        | 0.36%   |
| Sao Paulo         | 12        | 0.36%   |
| Milan             | 12        | 0.36%   |
| Los Angeles       | 12        | 0.36%   |
| London            | 12        | 0.36%   |
| Riga              | 11        | 0.33%   |
| New York          | 11        | 0.33%   |
| Istanbul          | 11        | 0.33%   |
| Dublin            | 11        | 0.33%   |
| Sofia             | 10        | 0.3%    |
| Bucharest         | 10        | 0.3%    |
| Vancouver         | 9         | 0.27%   |
| Shanghai          | 9         | 0.27%   |
| Krakow            | 9         | 0.27%   |
| Hamburg           | 9         | 0.27%   |
| Chicago           | 9         | 0.27%   |
| Athens            | 9         | 0.27%   |
| Yekaterinburg     | 8         | 0.24%   |
| Vilnius           | 8         | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 578       | 780    | 17.28%  |
| WDC                 | 391       | 514    | 11.69%  |
| Seagate             | 283       | 363    | 8.46%   |
| Toshiba             | 236       | 324    | 7.06%   |
| Kingston            | 212       | 261    | 6.34%   |
| SanDisk             | 162       | 196    | 4.84%   |
| Crucial             | 162       | 219    | 4.84%   |
| Transcend           | 148       | 225    | 4.43%   |
| Hitachi             | 126       | 149    | 3.77%   |
| Intel               | 110       | 134    | 3.29%   |
| NVMe                | 97        | 130    | 2.9%    |
| SK hynix            | 74        | 87     | 2.21%   |
| HGST                | 64        | 151    | 1.91%   |
| Apple               | 57        | 63     | 1.7%    |
| A-DATA Technology   | 55        | 73     | 1.64%   |
| Micron Technology   | 53        | 64     | 1.58%   |
| Fujitsu             | 28        | 37     | 0.84%   |
| SPCC                | 27        | 34     | 0.81%   |
| PNY                 | 27        | 37     | 0.81%   |
| Gigabyte Technology | 20        | 26     | 0.6%    |
| KIOXIA              | 19        | 19     | 0.57%   |
| KingSpec            | 19        | 23     | 0.57%   |
| China               | 19        | 21     | 0.57%   |
| Phison              | 18        | 26     | 0.54%   |
| Intenso             | 18        | 19     | 0.54%   |
| LITEON              | 17        | 24     | 0.51%   |
| FORESEE             | 15        | 17     | 0.45%   |
| SSSTC               | 13        | 15     | 0.39%   |
| Patriot             | 13        | 17     | 0.39%   |
| OCZ                 | 13        | 17     | 0.39%   |
| Hewlett-Packard     | 12        | 15     | 0.36%   |
| Corsair             | 12        | 13     | 0.36%   |
| Apacer              | 11        | 15     | 0.33%   |
| Silicon Motion      | 10        | 11     | 0.3%    |
| OWC                 | 10        | 11     | 0.3%    |
| Lexar               | 10        | 18     | 0.3%    |
| GOODRAM             | 9         | 9      | 0.27%   |
| Netac               | 8         | 8      | 0.24%   |
| LITEONIT            | 8         | 8      | 0.24%   |
| UMIS                | 7         | 7      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB        | 44        | 1.27%   |
| Transcend TS256GMTS952T2 256GB     | 36        | 1.04%   |
| Seagate ST1000LM035-1RK172 1TB     | 33        | 0.95%   |
| Toshiba MQ01ABD100 1TB             | 29        | 0.84%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 28        | 0.81%   |
| Samsung SSD 860 EVO 500GB          | 28        | 0.81%   |
| Toshiba MQ01ABF050 500GB           | 27        | 0.78%   |
| Samsung SSD 850 EVO 250GB          | 24        | 0.69%   |
| Transcend TS256GMTE652T2 256GB     | 23        | 0.67%   |
| Crucial CT500MX500SSD1 500GB       | 22        | 0.64%   |
| Kingston SA400S37120G 120GB        | 20        | 0.58%   |
| Transcend TS256GMTE710T 256GB      | 18        | 0.52%   |
| Samsung SSD 860 EVO 250GB          | 18        | 0.52%   |
| HGST HTS721010A9E630 1TB           | 18        | 0.52%   |
| Crucial CT1000MX500SSD1 1TB        | 17        | 0.49%   |
| Samsung SSD 850 EVO 500GB          | 16        | 0.46%   |
| Seagate ST9500325AS 500GB          | 15        | 0.43%   |
| Seagate ST500LT012-1DG142 500GB    | 15        | 0.43%   |
| Kingston SA400S37480G 480GB        | 15        | 0.43%   |
| HGST HTS725050A7E630 500GB         | 15        | 0.43%   |
| WDC WDS240G2G0A-00JH30 240GB       | 14        | 0.4%    |
| Toshiba MQ04ABF100 1TB             | 14        | 0.4%    |
| Seagate ST500LT012-9WS142 500GB    | 14        | 0.4%    |
| Kingston SV300S37A120G 120GB       | 14        | 0.4%    |
| Crucial CT240BX500SSD1 240GB       | 14        | 0.4%    |
| Samsung SSD 860 EVO 1TB            | 13        | 0.38%   |
| Samsung SSD 970 EVO Plus 1TB       | 12        | 0.35%   |
| Intel SSDPEKKF256G8L 256GB         | 12        | 0.35%   |
| Crucial CT480BX500SSD1 480GB       | 12        | 0.35%   |
| Transcend TS128GMTE110S 128GB      | 11        | 0.32%   |
| Seagate ST9500420AS 500GB          | 11        | 0.32%   |
| SanDisk SSD PLUS 240GB             | 11        | 0.32%   |
| Samsung SSD 840 EVO 250GB          | 11        | 0.32%   |
| Samsung MZVLW256HEHP-000L7 256GB   | 11        | 0.32%   |
| WDC WD1600BEVT-22ZCT0 160GB        | 10        | 0.29%   |
| Seagate ST9320423AS 320GB          | 10        | 0.29%   |
| Seagate ST1000LM049-2GH172 1TB     | 10        | 0.29%   |
| Hitachi HTS547550A9E384 500GB      | 10        | 0.29%   |
| WDC WD10JPVX-22JC3T0 1TB           | 9         | 0.26%   |
| WDC WD10JPCX-24UE4T0 1TB           | 9         | 0.26%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                                 | Notebooks | Drives | Percent |
|----------------------------------------|-----------|--------|---------|
| Seagate                                | 281       | 361    | 26.71%  |
| WDC                                    | 252       | 328    | 23.95%  |
| Toshiba                                | 169       | 226    | 16.06%  |
| Hitachi                                | 126       | 149    | 11.98%  |
| NVMe                                   | 70        | 92     | 6.65%   |
| HGST                                   | 64        | 151    | 6.08%   |
| Samsung Electronics                    | 35        | 39     | 3.33%   |
| Fujitsu                                | 27        | 35     | 2.57%   |
| Apple                                  | 7         | 7      | 0.67%   |
| Generic                                | 4         | 4      | 0.38%   |
| JetFlash                               | 3         | 3      | 0.29%   |
| Product:              USB Flash Memory | 2         | 2      | 0.19%   |
| Lexar                                  | 2         | 3      | 0.19%   |
| Verbatim                               | 1         | 1      | 0.1%    |
| USB                                    | 1         | 1      | 0.1%    |
| UFD 2.0                                | 1         | 1      | 0.1%    |
| SMI                                    | 1         | 1      | 0.1%    |
| OPENBSD                                | 1         | 1      | 0.1%    |
| Maxtor                                 | 1         | 1      | 0.1%    |
| LDLC F6+                               | 1         | 1      | 0.1%    |
| IBM/Hitachi                            | 1         | 1      | 0.1%    |
| HPE                                    | 1         | 5      | 0.1%    |
| General                                | 1         | 1      | 0.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 335       | 447    | 20.77%  |
| Kingston            | 177       | 220    | 10.97%  |
| SanDisk             | 161       | 195    | 9.98%   |
| Crucial             | 136       | 180    | 8.43%   |
| Transcend           | 92        | 153    | 5.7%    |
| Intel               | 67        | 86     | 4.15%   |
| WDC                 | 66        | 88     | 4.09%   |
| Apple               | 50        | 56     | 3.1%    |
| A-DATA Technology   | 36        | 49     | 2.23%   |
| Toshiba             | 31        | 42     | 1.92%   |
| SK hynix            | 31        | 32     | 1.92%   |
| Micron Technology   | 27        | 34     | 1.67%   |
| SPCC                | 25        | 31     | 1.55%   |
| PNY                 | 25        | 35     | 1.55%   |
| NVMe                | 24        | 27     | 1.49%   |
| KingSpec            | 19        | 23     | 1.18%   |
| China               | 19        | 21     | 1.18%   |
| LITEON              | 16        | 23     | 0.99%   |
| Intenso             | 16        | 17     | 0.99%   |
| Gigabyte Technology | 15        | 18     | 0.93%   |
| Patriot             | 13        | 17     | 0.81%   |
| OCZ                 | 13        | 17     | 0.81%   |
| Corsair             | 12        | 13     | 0.74%   |
| Apacer              | 11        | 15     | 0.68%   |
| OWC                 | 10        | 11     | 0.62%   |
| Hewlett-Packard     | 10        | 13     | 0.62%   |
| GOODRAM             | 9         | 9      | 0.56%   |
| Netac               | 8         | 8      | 0.5%    |
| LITEONIT            | 8         | 8      | 0.5%    |
| Lexar               | 8         | 15     | 0.5%    |
| FORESEE             | 8         | 10     | 0.5%    |
| Team                | 7         | 9      | 0.43%   |
| Plextor             | 6         | 7      | 0.37%   |
| Hoodisk             | 6         | 7      | 0.37%   |
| Dogfish             | 6         | 8      | 0.37%   |
| Phison              | 5         | 6      | 0.31%   |
| Kston               | 5         | 7      | 0.31%   |
| Zheino              | 4         | 7      | 0.25%   |
| Mushkin             | 4         | 4      | 0.25%   |
| MidasForce          | 4         | 5      | 0.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1460      | 2082   | 46.9%   |
| HDD  | 990       | 1414   | 31.8%   |
| NVMe | 663       | 893    | 21.3%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2255      | 3496   | 77.28%  |
| NVMe | 663       | 893    | 22.72%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Notebooks | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 1810      | 2572   | 74.39%  |
| 0.51-1.0        | 519       | 738    | 21.33%  |
| 1.01-2.0        | 91        | 124    | 3.74%   |
| 3.01-4.0        | 4         | 52     | 0.16%   |
| 4.01-10.0       | 4         | 4      | 0.16%   |
| More than 100.0 | 2         | 2      | 0.08%   |
| 2.01-3.0        | 2         | 3      | 0.08%   |
| 0               | 1         | 1      | 0.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1009      | 31.61%  |
| 1-20           | 720       | 22.56%  |
| 251-500        | 655       | 20.52%  |
| 501-1000       | 287       | 8.99%   |
| 51-100         | 255       | 7.99%   |
| 21-50          | 175       | 5.48%   |
| 1001-2000      | 59        | 1.85%   |
| Unknown        | 25        | 0.78%   |
| More than 3000 | 4         | 0.13%   |
| 2001-3000      | 3         | 0.09%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 2593      | 83.11%  |
| 21-50          | 267       | 8.56%   |
| 51-100         | 100       | 3.21%   |
| 101-250        | 92        | 2.95%   |
| 251-500        | 28        | 0.9%    |
| Unknown        | 25        | 0.8%    |
| 501-1000       | 13        | 0.42%   |
| More than 3000 | 1         | 0.03%   |
| 1001-2000      | 1         | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB              | 11        | 12     | 2.17%   |
| Seagate ST500LT012-9WS142 500GB     | 11        | 15     | 2.17%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 9         | 13     | 1.78%   |
| HGST HTS725050A7E630 500GB          | 9         | 15     | 1.78%   |
| Toshiba MQ01ABF050 500GB            | 8         | 10     | 1.58%   |
| Seagate ST9500420AS 500GB           | 8         | 10     | 1.58%   |
| Seagate ST9500325AS 500GB           | 8         | 14     | 1.58%   |
| Seagate ST500LT012-1DG142 500GB     | 8         | 8      | 1.58%   |
| Hitachi HTS541612J9SA00 120GB       | 8         | 8      | 1.58%   |
| Seagate ST500LM021-1KJ152 500GB     | 7         | 8      | 1.38%   |
| Seagate ST9320423AS 320GB           | 6         | 6      | 1.19%   |
| Seagate ST9320325AS 320GB           | 5         | 5      | 0.99%   |
| Seagate ST320LT007-9ZV142 320GB     | 5         | 5      | 0.99%   |
| Seagate ST1000LM035-1RK172 1TB      | 5         | 6      | 0.99%   |
| Hitachi HTS547550A9E384 500GB       | 5         | 6      | 0.99%   |
| Hitachi HTS545050B9A300 500GB       | 5         | 6      | 0.99%   |
| HGST HTS541010A9E680 1TB            | 5         | 6      | 0.99%   |
| Toshiba MK3261GSYN 320GB            | 4         | 6      | 0.79%   |
| Seagate ST9250315AS 250GB           | 4         | 6      | 0.79%   |
| Kingston SV300S37A120G 120GB        | 4         | 4      | 0.79%   |
| Intel SSDSC2BF180A4L 180GB          | 4         | 4      | 0.79%   |
| Hitachi HTS545050A7E380 500GB       | 4         | 4      | 0.79%   |
| Hitachi HTS545032B9A300 320GB       | 4         | 6      | 0.79%   |
| HGST HTS721010A9E630 1TB            | 4         | 24     | 0.79%   |
| WDC WD10JPVX-60JC3T0 1TB            | 3         | 3      | 0.59%   |
| Toshiba MQ01ABD075 752GB            | 3         | 3      | 0.59%   |
| Toshiba MQ01ABD032 320GB            | 3         | 4      | 0.59%   |
| SSSTC CVB-8D128-HP 128GB            | 3         | 3      | 0.59%   |
| Seagate ST9160412AS 160GB           | 3         | 3      | 0.59%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 3         | 3      | 0.59%   |
| Seagate ST500LM000-1EJ162 500GB     | 3         | 3      | 0.59%   |
| Seagate ST320LT020-9YG142 320GB     | 3         | 4      | 0.59%   |
| SanDisk SSD PLUS 240GB              | 3         | 3      | 0.59%   |
| Samsung Electronics HM160HI 160GB   | 3         | 3      | 0.59%   |
| Micron Technology 1100 SATA 256GB   | 3         | 3      | 0.59%   |
| Kingston SA400S37240G 240GB         | 3         | 3      | 0.59%   |
| Hitachi HTS545025B9SA02 250GB       | 3         | 5      | 0.59%   |
| Hitachi HTS542525K9A300 250GB       | 3         | 3      | 0.59%   |
| WDC WD6400BEVT-22A0RT0 640GB        | 2         | 2      | 0.4%    |
| WDC WD3200BPVT-80JJ5T0 320GB        | 2         | 2      | 0.4%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 122       | 158    | 24.4%   |
| Toshiba             | 76        | 102    | 15.2%   |
| Hitachi             | 69        | 79     | 13.8%   |
| WDC                 | 58        | 62     | 11.6%   |
| Samsung Electronics | 33        | 39     | 6.6%    |
| Kingston            | 24        | 26     | 4.8%    |
| HGST                | 24        | 55     | 4.8%    |
| Intel               | 20        | 23     | 4%      |
| SanDisk             | 10        | 11     | 2%      |
| Micron Technology   | 8         | 8      | 1.6%    |
| Crucial             | 8         | 12     | 1.6%    |
| SK hynix            | 6         | 6      | 1.2%    |
| Fujitsu             | 6         | 9      | 1.2%    |
| Apple               | 6         | 6      | 1.2%    |
| A-DATA Technology   | 4         | 11     | 0.8%    |
| SSSTC               | 3         | 3      | 0.6%    |
| OCZ                 | 3         | 3      | 0.6%    |
| Corsair             | 3         | 3      | 0.6%    |
| LITEON              | 2         | 2      | 0.4%    |
| Fanxiang            | 2         | 2      | 0.4%    |
| China               | 2         | 3      | 0.4%    |
| Transcend           | 1         | 1      | 0.2%    |
| SMI                 | 1         | 1      | 0.2%    |
| ShiJi               | 1         | 1      | 0.2%    |
| Patriot             | 1         | 1      | 0.2%    |
| Netac               | 1         | 1      | 0.2%    |
| Lenovo              | 1         | 1      | 0.2%    |
| Kston               | 1         | 1      | 0.2%    |
| KingSpec            | 1         | 1      | 0.2%    |
| IBM/Hitachi         | 1         | 1      | 0.2%    |
| Hewlett-Packard     | 1         | 2      | 0.2%    |
| AGI                 | 1         | 1      | 0.2%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 122       | 158    | 33.52%  |
| Toshiba             | 72        | 92     | 19.78%  |
| Hitachi             | 69        | 79     | 18.96%  |
| WDC                 | 56        | 60     | 15.38%  |
| HGST                | 24        | 55     | 6.59%   |
| Samsung Electronics | 12        | 14     | 3.3%    |
| Fujitsu             | 6         | 9      | 1.65%   |
| Apple               | 2         | 2      | 0.55%   |
| IBM/Hitachi         | 1         | 1      | 0.27%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 351       | 470    | 72.07%  |
| SSD  | 129       | 158    | 26.49%  |
| NVMe | 7         | 7      | 1.44%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| SanDisk pSSD 16GB                 | 3         | 3      | 33.33%  |
| Transcend TS128GMTE110S 128GB     | 1         | 1      | 11.11%  |
| Samsung Electronics HM500JJ 500GB | 1         | 1      | 11.11%  |
| Samsung Electronics HM250JI 250GB | 1         | 1      | 11.11%  |
| Intel SSDSCKKF512G8 SATA 512GB    | 1         | 1      | 11.11%  |
| HPE MK000480GWUGF 480GB           | 1         | 1      | 11.11%  |
| Hitachi HTS545025B9A300 250GB     | 1         | 1      | 11.11%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 3         | 3      | 33.33%  |
| Samsung Electronics | 2         | 2      | 22.22%  |
| Transcend           | 1         | 1      | 11.11%  |
| Intel               | 1         | 1      | 11.11%  |
| HPE                 | 1         | 1      | 11.11%  |
| Hitachi             | 1         | 1      | 11.11%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 2327      | 3573   | 78.96%  |
| Malfunc  | 484       | 635    | 16.42%  |
| Detected | 127       | 172    | 4.31%   |
| Failed   | 9         | 9      | 0.31%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 2151      | 64.02%  |
| Samsung Electronics                     | 301       | 8.96%   |
| AMD                                     | 273       | 8.13%   |
| SanDisk                                 | 125       | 3.72%   |
| SK hynix                                | 56        | 1.67%   |
| Transcend                               | 54        | 1.61%   |
| Kingston Technology Company             | 47        | 1.4%    |
| Toshiba                                 | 39        | 1.16%   |
| Phison Electronics                      | 38        | 1.13%   |
| Nvidia                                  | 35        | 1.04%   |
| Micron Technology                       | 35        | 1.04%   |
| Micron/Crucial Technology               | 30        | 0.89%   |
| KIOXIA                                  | 30        | 0.89%   |
| Silicon Motion                          | 26        | 0.77%   |
| ADATA Technology                        | 19        | 0.57%   |
| Solid State Storage Technology          | 15        | 0.45%   |
| Marvell Technology Group                | 12        | 0.36%   |
| Realtek Semiconductor                   | 9         | 0.27%   |
| Silicon Integrated Systems [SiS]        | 8         | 0.24%   |
| MAXIO Technology (Hangzhou)             | 8         | 0.24%   |
| Union Memory (Shenzhen)                 | 7         | 0.21%   |
| Shenzhen Unionmemory Information System | 7         | 0.21%   |
| Lenovo                                  | 7         | 0.21%   |
| Shenzhen Longsys Electronics            | 6         | 0.18%   |
| JMicron Technology                      | 5         | 0.15%   |
| Biwin Storage Technology                | 5         | 0.15%   |
| INNOGRIT                                | 3         | 0.09%   |
| VIA Technologies                        | 2         | 0.06%   |
| ULi Electronics                         | 1         | 0.03%   |
| Seagate Technology                      | 1         | 0.03%   |
| Netac Technology                        | 1         | 0.03%   |
| Lite-On Technology                      | 1         | 0.03%   |
| Broadcom / LSI                          | 1         | 0.03%   |
| ASMedia Technology                      | 1         | 0.03%   |
| Apple                                   | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 285       | 7.91%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 270       | 7.49%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 232       | 6.44%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 215       | 5.97%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 164       | 4.55%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 143       | 3.97%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 135       | 3.75%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 112       | 3.11%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 110       | 3.05%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 77        | 2.14%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 77        | 2.14%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 61        | 1.69%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 59        | 1.64%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 56        | 1.55%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 54        | 1.5%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 53        | 1.47%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 50        | 1.39%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 40        | 1.11%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 39        | 1.08%   |
| Intel Comet Lake SATA AHCI Controller                                            | 39        | 1.08%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 38        | 1.05%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 37        | 1.03%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 34        | 0.94%   |
| Transcend NVMe PCIe SSD 110S/112S/120S/MTE300S/MTE400S/MTE652T2 (DRAM-less)      | 33        | 0.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 32        | 0.89%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 30        | 0.83%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 30        | 0.83%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 30        | 0.83%   |
| Nvidia MCP79 AHCI Controller                                                     | 29        | 0.8%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 29        | 0.8%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 26        | 0.72%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 26        | 0.72%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 26        | 0.72%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                 | 24        | 0.67%   |
| Intel Volume Management Device NVMe RAID Controller                              | 23        | 0.64%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 21        | 0.58%   |
| Transcend NVMe PCIe SSD 240S/MTE710T                                             | 20        | 0.55%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 20        | 0.55%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 20        | 0.55%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 19        | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2202      | 63.75%  |
| NVMe | 836       | 24.2%   |
| IDE  | 273       | 7.9%    |
| RAID | 142       | 4.11%   |
| SAS  | 1         | 0.03%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 2544      | 84.57%  |
| AMD          | 454       | 15.09%  |
| PowerPC      | 3         | 0.1%    |
| Unknown      | 3         | 0.1%    |
| 11th         | 2         | 0.07%   |
| ARM          | 1         | 0.03%   |
| 123456789ABC | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz       | 67        | 2.21%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 55        | 1.82%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 54        | 1.78%   |
| Intel CPU Version                       | 47        | 1.55%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 42        | 1.39%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 40        | 1.32%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 40        | 1.32%   |
| AMD Ryzen Embedded V1500B               | 40        | 1.32%   |
| AMD EPYC 3201 8-Core Processor          | 40        | 1.32%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 38        | 1.26%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 37        | 1.22%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 37        | 1.22%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 31        | 1.02%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 30        | 0.99%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 30        | 0.99%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 28        | 0.93%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 27        | 0.89%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 26        | 0.86%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 25        | 0.83%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 23        | 0.76%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 23        | 0.76%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 23        | 0.76%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 23        | 0.76%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 22        | 0.73%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 22        | 0.73%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 22        | 0.73%   |
| Intel Core 2 Duo                        | 22        | 0.73%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 21        | 0.69%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 20        | 0.66%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 19        | 0.63%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 19        | 0.63%   |
| Intel Core i3-6006U CPU @ 2.00GHz       | 19        | 0.63%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 19        | 0.63%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 18        | 0.59%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 18        | 0.59%   |
| Intel Core i3-4005U CPU @ 1.70GHz       | 18        | 0.59%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 17        | 0.56%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 17        | 0.56%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 16        | 0.53%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 16        | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 896       | 29.72%  |
| Intel Core i7           | 605       | 20.07%  |
| Other                   | 234       | 7.76%   |
| Intel Core i3           | 207       | 6.87%   |
| Intel Core 2 Duo        | 173       | 5.74%   |
| Intel Celeron           | 172       | 5.7%    |
| AMD Ryzen 7             | 93        | 3.08%   |
| AMD Ryzen 5             | 69        | 2.29%   |
| Intel Atom              | 63        | 2.09%   |
| Intel Pentium           | 59        | 1.96%   |
| AMD EPYC                | 55        | 1.82%   |
| AMD Ryzen Embedded      | 41        | 1.36%   |
| Intel Pentium M         | 24        | 0.8%    |
| Intel Xeon              | 20        | 0.66%   |
| Intel Genuine           | 20        | 0.66%   |
| AMD A6                  | 20        | 0.66%   |
| Intel Core 2            | 19        | 0.63%   |
| AMD Ryzen 7 PRO         | 19        | 0.63%   |
| AMD Ryzen 3             | 16        | 0.53%   |
| AMD E1                  | 13        | 0.43%   |
| Intel Pentium Silver    | 12        | 0.4%    |
| AMD Ryzen 9             | 12        | 0.4%    |
| AMD Ryzen 5 PRO         | 12        | 0.4%    |
| Intel Pentium Dual      | 11        | 0.36%   |
| AMD A4                  | 11        | 0.36%   |
| AMD E                   | 10        | 0.33%   |
| AMD A8                  | 10        | 0.33%   |
| Intel Pentium Dual-Core | 9         | 0.3%    |
| AMD A10                 | 9         | 0.3%    |
| Intel Core m3           | 8         | 0.27%   |
| Intel Core i9           | 7         | 0.23%   |
| AMD E2                  | 7         | 0.23%   |
| AMD Athlon              | 6         | 0.2%    |
| Intel Core M            | 5         | 0.17%   |
| Intel Celeron M         | 5         | 0.17%   |
| AMD C-50                | 5         | 0.17%   |
| Intel Pentium 4         | 4         | 0.13%   |
| Intel Core Duo          | 4         | 0.13%   |
| Intel Celeron Dual-Core | 4         | 0.13%   |
| Intel 686-class         | 4         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1508      | 49.97%  |
| 4       | 755       | 25.02%  |
| Unknown | 237       | 7.85%   |
| 8       | 182       | 6.03%   |
| 16      | 100       | 3.31%   |
| 6       | 86        | 2.85%   |
| 1       | 79        | 2.62%   |
| 12      | 50        | 1.66%   |
| 10      | 10        | 0.33%   |
| 20      | 6         | 0.2%    |
| 32      | 2         | 0.07%   |
| 24      | 1         | 0.03%   |
| 22      | 1         | 0.03%   |
| 5       | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 2897      | 96.02%  |
| Unknown | 73        | 2.42%   |
| 2       | 47        | 1.56%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1912      | 63.37%  |
| 1       | 823       | 27.28%  |
| Unknown | 282       | 9.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 492       | 16.32%  |
| IvyBridge       | 287       | 9.52%   |
| Haswell         | 265       | 8.79%   |
| SandyBridge     | 261       | 8.66%   |
| Skylake         | 213       | 7.07%   |
| Penryn          | 168       | 5.57%   |
| Broadwell       | 162       | 5.37%   |
| Unknown         | 154       | 5.11%   |
| Westmere        | 119       | 3.95%   |
| Zen             | 114       | 3.78%   |
| Core            | 99        | 3.28%   |
| TigerLake       | 86        | 2.85%   |
| Silvermont      | 76        | 2.52%   |
| Bonnell         | 71        | 2.36%   |
| Zen 2           | 58        | 1.92%   |
| Zen+            | 53        | 1.76%   |
| Zen 3           | 45        | 1.49%   |
| P6              | 40        | 1.33%   |
| CometLake       | 39        | 1.29%   |
| Goldmont plus   | 33        | 1.09%   |
| Excavator       | 28        | 0.93%   |
| Bobcat          | 24        | 0.8%    |
| Goldmont        | 21        | 0.7%    |
| Puma            | 18        | 0.6%    |
| IceLake         | 18        | 0.6%    |
| Jaguar          | 17        | 0.56%   |
| K10             | 11        | 0.36%   |
| Piledriver      | 9         | 0.3%    |
| NetBurst        | 7         | 0.23%   |
| Nehalem         | 7         | 0.23%   |
| K10 Llano       | 7         | 0.23%   |
| K8 Hammer       | 5         | 0.17%   |
| Steamroller     | 3         | 0.1%    |
| K8 & K10 hybrid | 3         | 0.1%    |
| Geode           | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2310      | 67.68%  |
| Nvidia                           | 583       | 17.08%  |
| AMD                              | 505       | 14.8%   |
| Silicon Integrated Systems [SiS] | 6         | 0.18%   |
| Silicon Motion                   | 3         | 0.09%   |
| VIA Technologies                 | 2         | 0.06%   |
| Trident Microsystems             | 1         | 0.03%   |
| S3 Graphics                      | 1         | 0.03%   |
| Matrox Electronics Systems       | 1         | 0.03%   |
| ATI                              | 1         | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 267       | 7.52%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 245       | 6.9%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 189       | 5.32%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 148       | 4.17%   |
| Intel HD Graphics 5500                                                                   | 135       | 3.8%    |
| Intel UHD Graphics 620                                                                   | 118       | 3.32%   |
| Intel HD Graphics 620                                                                    | 111       | 3.13%   |
| Intel Core Processor Integrated Graphics Controller                                      | 93        | 2.62%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 90        | 2.54%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 76        | 2.14%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 72        | 2.03%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 65        | 1.83%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 64        | 1.8%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 60        | 1.69%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 60        | 1.69%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 59        | 1.66%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 56        | 1.58%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 53        | 1.49%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 47        | 1.32%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 42        | 1.18%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 42        | 1.18%   |
| Intel HD Graphics 530                                                                    | 39        | 1.1%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 39        | 1.1%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 33        | 0.93%   |
| AMD Lucienne                                                                             | 32        | 0.9%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 29        | 0.82%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 29        | 0.82%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 28        | 0.79%   |
| Intel HD Graphics 630                                                                    | 27        | 0.76%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 25        | 0.7%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 24        | 0.68%   |
| Nvidia C79 [GeForce 9400M]                                                               | 22        | 0.62%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 22        | 0.62%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 22        | 0.62%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 21        | 0.59%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 19        | 0.54%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 17        | 0.48%   |
| Nvidia GP108M [GeForce MX150]                                                            | 15        | 0.42%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 15        | 0.42%   |
| Intel HD Graphics 500                                                                    | 15        | 0.42%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1611      | 53.29%  |
| Intel + Nvidia           | 376       | 12.44%  |
| 1 x AMD                  | 361       | 11.94%  |
| 2 x Intel                | 245       | 8.1%    |
| 1 x Nvidia               | 167       | 5.52%   |
| Other                    | 100       | 3.31%   |
| Intel + AMD              | 82        | 2.71%   |
| AMD + Nvidia             | 41        | 1.36%   |
| 2 x AMD                  | 19        | 0.63%   |
| 1 x SiS                  | 6         | 0.2%    |
| 2 x Nvidia               | 5         | 0.17%   |
| 1 x Silicon Motion       | 3         | 0.1%    |
| 1 x VIA                  | 2         | 0.07%   |
| 2 x Intel + 1 x Nvidia   | 1         | 0.03%   |
| 1 x Trident Microsystems | 1         | 0.03%   |
| 1 x S3 Graphics          | 1         | 0.03%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.03%   |
| AMD + Matrox             | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2655      | 87.16%  |
| Unknown     | 202       | 6.63%   |
| Proprietary | 189       | 6.2%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2665      | 87.12%  |
| 0.01-0.5   | 188       | 6.15%   |
| 1.01-2.0   | 77        | 2.52%   |
| 0.51-1.0   | 56        | 1.83%   |
| 3.01-4.0   | 39        | 1.27%   |
| 7.01-8.0   | 14        | 0.46%   |
| 5.01-6.0   | 14        | 0.46%   |
| 2.01-3.0   | 4         | 0.13%   |
| 8.01-16.0  | 2         | 0.07%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 423       | 19.48%  |
| LG Display              | 373       | 17.18%  |
| Chimei Innolux          | 265       | 12.21%  |
| BOE                     | 264       | 12.16%  |
| Samsung Electronics     | 180       | 8.29%   |
| Lenovo                  | 115       | 5.3%    |
| Apple                   | 83        | 3.82%   |
| Sharp                   | 52        | 2.4%    |
| Chi Mei Optoelectronics | 43        | 1.98%   |
| Dell                    | 34        | 1.57%   |
| InfoVision              | 31        | 1.43%   |
| Goldstar                | 22        | 1.01%   |
| Hewlett-Packard         | 20        | 0.92%   |
| PANDA                   | 18        | 0.83%   |
| LG Philips              | 18        | 0.83%   |
| AOC                     | 17        | 0.78%   |
| CSO                     | 15        | 0.69%   |
| BenQ                    | 15        | 0.69%   |
| Philips                 | 13        | 0.6%    |
| Acer                    | 13        | 0.6%    |
| HannStar                | 12        | 0.55%   |
| Ancor Communications    | 11        | 0.51%   |
| LGD                     | 9         | 0.41%   |
| Panasonic               | 7         | 0.32%   |
| CPT                     | 7         | 0.32%   |
| JDI                     | 6         | 0.28%   |
| Iiyama                  | 6         | 0.28%   |
| BOE Technology Group    | 6         | 0.28%   |
| Unknown                 | 6         | 0.28%   |
| ViewSonic               | 5         | 0.23%   |
| Toshiba                 | 5         | 0.23%   |
| IBM                     | 5         | 0.23%   |
| Sceptre Tech            | 4         | 0.18%   |
| HKC                     | 4         | 0.18%   |
| Fujitsu Siemens         | 4         | 0.18%   |
| TMX                     | 3         | 0.14%   |
| Sony                    | 3         | 0.14%   |
| Lenovo Group Limited    | 3         | 0.14%   |
| Eizo                    | 3         | 0.14%   |
| CTO                     | 3         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 27        | 1.23%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 19        | 0.87%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch         | 14        | 0.64%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 12        | 0.55%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch          | 12        | 0.55%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch           | 12        | 0.55%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch     | 11        | 0.5%    |
| Lenovo LCD Monitor LEN40B1 1600x900 350x190mm 15.7-inch                  | 11        | 0.5%    |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch                  | 10        | 0.46%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch                  | 10        | 0.46%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch                  | 10        | 0.46%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch           | 10        | 0.46%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch     | 9         | 0.41%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch                 | 9         | 0.41%   |
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch                  | 9         | 0.41%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch         | 9         | 0.41%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch            | 9         | 0.41%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch            | 9         | 0.41%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch            | 9         | 0.41%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch           | 9         | 0.41%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch            | 9         | 0.41%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch             | 8         | 0.37%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch             | 8         | 0.37%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch              | 8         | 0.37%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch                  | 8         | 0.37%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch                | 8         | 0.37%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 310x170mm 13.9-inch         | 8         | 0.37%   |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                    | 8         | 0.37%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 340x190mm 15.3-inch           | 8         | 0.37%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch           | 8         | 0.37%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch     | 7         | 0.32%   |
| Panasonic LCD Monitor MEI96A2 3840x2160 380x210mm 17.1-inch              | 7         | 0.32%   |
| LG Display LCD Monitor LGD046F 1920x1080 350x190mm 15.7-inch             | 7         | 0.32%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch              | 7         | 0.32%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 340x190mm 15.3-inch          | 7         | 0.32%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 310x170mm 13.9-inch         | 7         | 0.32%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 310x170mm 13.9-inch          | 7         | 0.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 7         | 0.32%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 310x170mm 13.9-inch           | 7         | 0.32%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch            | 7         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 773       | 36.58%  |
| 1366x768 (WXGA)    | 703       | 33.27%  |
| 1280x800 (WXGA)    | 119       | 5.63%   |
| 1600x900 (HD+)     | 115       | 5.44%   |
| 3840x2160 (4K)     | 64        | 3.03%   |
| 2560x1440 (QHD)    | 59        | 2.79%   |
| 1440x900 (WXGA+)   | 48        | 2.27%   |
| 1920x1200 (WUXGA)  | 37        | 1.75%   |
| 1024x600           | 35        | 1.66%   |
| 2560x1600          | 24        | 1.14%   |
| 1680x1050 (WSXGA+) | 16        | 0.76%   |
| 1280x1024 (SXGA)   | 14        | 0.66%   |
| 3200x1800 (QHD+)   | 12        | 0.57%   |
| 2880x1800          | 12        | 0.57%   |
| 2256x1504          | 9         | 0.43%   |
| 2560x1080          | 8         | 0.38%   |
| 1024x768 (XGA)     | 7         | 0.33%   |
| Unknown            | 6         | 0.28%   |
| 3440x1440          | 5         | 0.24%   |
| 2160x1440          | 4         | 0.19%   |
| 1920x540           | 4         | 0.19%   |
| 3840x2400          | 3         | 0.14%   |
| 3000x2000          | 3         | 0.14%   |
| 1400x1050          | 3         | 0.14%   |
| 5760x2160          | 2         | 0.09%   |
| 2240x1400          | 2         | 0.09%   |
| 2160x1350          | 2         | 0.09%   |
| 1360x768           | 2         | 0.09%   |
| 1280x854           | 2         | 0.09%   |
| 9600x2160          | 1         | 0.05%   |
| 720x1280           | 1         | 0.05%   |
| 7040x1440          | 1         | 0.05%   |
| 5760x1080          | 1         | 0.05%   |
| 5440x1080          | 1         | 0.05%   |
| 4480x1080          | 1         | 0.05%   |
| 3840x1600          | 1         | 0.05%   |
| 3840x1200          | 1         | 0.05%   |
| 3840x1080          | 1         | 0.05%   |
| 3520x1080          | 1         | 0.05%   |
| 3456x2160          | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 730       | 33.8%   |
| 13      | 671       | 31.06%  |
| 12      | 195       | 9.03%   |
| 17      | 90        | 4.17%   |
| 14      | 84        | 3.89%   |
| 11      | 75        | 3.47%   |
| 24      | 52        | 2.41%   |
| 27      | 46        | 2.13%   |
| Unknown | 43        | 1.99%   |
| 23      | 33        | 1.53%   |
| 10      | 32        | 1.48%   |
| 21      | 18        | 0.83%   |
| 19      | 15        | 0.69%   |
| 34      | 9         | 0.42%   |
| 18      | 9         | 0.42%   |
| 31      | 8         | 0.37%   |
| 9       | 7         | 0.32%   |
| 40      | 5         | 0.23%   |
| 16      | 5         | 0.23%   |
| 22      | 4         | 0.19%   |
| 64      | 3         | 0.14%   |
| 29      | 3         | 0.14%   |
| 26      | 3         | 0.14%   |
| 20      | 3         | 0.14%   |
| 42      | 2         | 0.09%   |
| 39      | 2         | 0.09%   |
| 54      | 1         | 0.05%   |
| 49      | 1         | 0.05%   |
| 48      | 1         | 0.05%   |
| 46      | 1         | 0.05%   |
| 43      | 1         | 0.05%   |
| 37      | 1         | 0.05%   |
| 35      | 1         | 0.05%   |
| 33      | 1         | 0.05%   |
| 32      | 1         | 0.05%   |
| 28      | 1         | 0.05%   |
| 8       | 1         | 0.05%   |
| 6       | 1         | 0.05%   |
| 5       | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 1222      | 56.81%  |
| 201-300     | 571       | 26.55%  |
| 501-600     | 120       | 5.58%   |
| 351-400     | 97        | 4.51%   |
| 401-500     | 43        | 2%      |
| Unknown     | 43        | 2%      |
| 601-700     | 20        | 0.93%   |
| 701-800     | 11        | 0.51%   |
| 801-900     | 9         | 0.42%   |
| 1001-1500   | 8         | 0.37%   |
| 101-200     | 4         | 0.19%   |
| 901-1000    | 2         | 0.09%   |
| 1-100       | 1         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1627      | 80.5%   |
| 16/10   | 260       | 12.86%  |
| 3/2     | 44        | 2.18%   |
| Unknown | 41        | 2.03%   |
| 4/3     | 16        | 0.79%   |
| 21/9    | 14        | 0.69%   |
| 5/4     | 13        | 0.64%   |
| 6/5     | 1         | 0.05%   |
| 3.88    | 1         | 0.05%   |
| 3.18    | 1         | 0.05%   |
| 11/10   | 1         | 0.05%   |
| 1.96    | 1         | 0.05%   |
| 0.46    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 637       | 29.49%  |
| 91-100         | 555       | 25.69%  |
| 61-70          | 189       | 8.75%   |
| 101-110        | 169       | 7.82%   |
| 71-80          | 108       | 5%      |
| 201-250        | 94        | 4.35%   |
| 121-130        | 78        | 3.61%   |
| 51-60          | 74        | 3.43%   |
| 301-350        | 51        | 2.36%   |
| Unknown        | 43        | 1.99%   |
| 41-50          | 37        | 1.71%   |
| 111-120        | 25        | 1.16%   |
| 351-500        | 21        | 0.97%   |
| 151-200        | 19        | 0.88%   |
| 141-150        | 14        | 0.65%   |
| 251-300        | 13        | 0.6%    |
| 501-1000       | 13        | 0.6%    |
| 131-140        | 9         | 0.42%   |
| 1-40           | 6         | 0.28%   |
| More than 1000 | 5         | 0.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 935       | 43.77%  |
| 101-120       | 629       | 29.45%  |
| 51-100        | 258       | 12.08%  |
| 161-240       | 198       | 9.27%   |
| More than 240 | 68        | 3.18%   |
| Unknown       | 43        | 2.01%   |
| 1-50          | 5         | 0.23%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2091      | 67.54%  |
| 0     | 796       | 25.71%  |
| 2     | 197       | 6.36%   |
| 3     | 11        | 0.36%   |
| 4     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 2002      | 42.4%   |
| Realtek Semiconductor                  | 1160      | 24.57%  |
| Qualcomm Atheros                       | 568       | 12.03%  |
| Broadcom                               | 341       | 7.22%   |
| AMD                                    | 96        | 2.03%   |
| Marvell Technology Group               | 65        | 1.38%   |
| TP-Link                                | 44        | 0.93%   |
| Ralink Technology                      | 38        | 0.8%    |
| Sierra Wireless                        | 36        | 0.76%   |
| Ericsson Business Mobile Networks      | 35        | 0.74%   |
| Samsung Electronics                    | 31        | 0.66%   |
| Nvidia                                 | 28        | 0.59%   |
| Ralink                                 | 26        | 0.55%   |
| MediaTek                               | 26        | 0.55%   |
| Edimax Technology                      | 25        | 0.53%   |
| Xiaomi                                 | 19        | 0.4%    |
| Dell                                   | 18        | 0.38%   |
| JMicron Technology                     | 15        | 0.32%   |
| Google                                 | 14        | 0.3%    |
| Hewlett-Packard                        | 11        | 0.23%   |
| Huawei Technologies                    | 10        | 0.21%   |
| D-Link System                          | 9         | 0.19%   |
| Silicon Integrated Systems [SiS]       | 8         | 0.17%   |
| NetGear                                | 8         | 0.17%   |
| D-Link                                 | 7         | 0.15%   |
| ASUSTek Computer                       | 7         | 0.15%   |
| Apple                                  | 7         | 0.15%   |
| Qualcomm Atheros Communications        | 6         | 0.13%   |
| Qualcomm                               | 6         | 0.13%   |
| Qualcomm Technologies                  | 5         | 0.11%   |
| OPPO Electronics                       | 4         | 0.08%   |
| Lenovo                                 | 3         | 0.06%   |
| Fibocom                                | 3         | 0.06%   |
| VIA Technologies                       | 2         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.04%   |
| Realtek                                | 2         | 0.04%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.04%   |
| Novatel Wireless                       | 2         | 0.04%   |
| Motorola PCS                           | 2         | 0.04%   |
| BUFFALO                                | 2         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 752       | 12.57%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 240       | 4.01%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 229       | 3.83%   |
| Intel Wireless 8265 / 8275                                              | 175       | 2.93%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 168       | 2.81%   |
| Intel Wireless 7265                                                     | 141       | 2.36%   |
| Intel Wireless 8260                                                     | 135       | 2.26%   |
| Intel Wireless 7260                                                     | 135       | 2.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 101       | 1.69%   |
| Intel Wi-Fi 6 AX200                                                     | 101       | 1.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 100       | 1.67%   |
| AMD XGMAC 10GbE Controller                                              | 95        | 1.59%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 90        | 1.5%    |
| Intel Ethernet Connection I219-LM                                       | 81        | 1.35%   |
| Intel I210 Gigabit Network Connection                                   | 76        | 1.27%   |
| Intel Wi-Fi 6 AX201                                                     | 73        | 1.22%   |
| Intel Ethernet Connection (4) I219-LM                                   | 73        | 1.22%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 63        | 1.05%   |
| Intel Ethernet Connection (3) I218-LM                                   | 62        | 1.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 59        | 0.99%   |
| Intel 82577LM Gigabit Network Connection                                | 57        | 0.95%   |
| Intel Ethernet Connection I218-LM                                       | 56        | 0.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 55        | 0.92%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 51        | 0.85%   |
| Intel Wireless 3165                                                     | 48        | 0.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 47        | 0.79%   |
| Intel I211 Gigabit Network Connection                                   | 47        | 0.79%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 46        | 0.77%   |
| Intel Centrino Ultimate-N 6300                                          | 44        | 0.74%   |
| Intel Ethernet Connection I217-LM                                       | 43        | 0.72%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 43        | 0.72%   |
| Intel Ethernet Connection (4) I219-V                                    | 42        | 0.7%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 41        | 0.69%   |
| Intel 82567LM Gigabit Network Connection                                | 41        | 0.69%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 39        | 0.65%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 39        | 0.65%   |
| Intel Centrino Advanced-N 6200                                          | 38        | 0.64%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 34        | 0.57%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 33        | 0.55%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 33        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1733      | 56.58%  |
| Qualcomm Atheros                | 501       | 16.36%  |
| Realtek Semiconductor           | 323       | 10.55%  |
| Broadcom                        | 264       | 8.62%   |
| TP-Link                         | 44        | 1.44%   |
| Ralink Technology               | 38        | 1.24%   |
| Sierra Wireless                 | 26        | 0.85%   |
| Ralink                          | 26        | 0.85%   |
| Edimax Technology               | 25        | 0.82%   |
| MediaTek                        | 23        | 0.75%   |
| Dell                            | 9         | 0.29%   |
| NetGear                         | 8         | 0.26%   |
| D-Link System                   | 8         | 0.26%   |
| D-Link                          | 7         | 0.23%   |
| ASUSTek Computer                | 7         | 0.23%   |
| Qualcomm Atheros Communications | 6         | 0.2%    |
| Qualcomm Technologies           | 5         | 0.16%   |
| BUFFALO                         | 2         | 0.07%   |
| Atheros                         | 2         | 0.07%   |
| ZyXEL Communications            | 1         | 0.03%   |
| Sagem                           | 1         | 0.03%   |
| Micro Star International        | 1         | 0.03%   |
| Mercucys                        | 1         | 0.03%   |
| IMC Networks                    | 1         | 0.03%   |
| AboCom Systems                  | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 175       | 5.64%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 168       | 5.41%   |
| Intel Wireless 7265                                                     | 141       | 4.54%   |
| Intel Wireless 8260                                                     | 135       | 4.35%   |
| Intel Wireless 7260                                                     | 135       | 4.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 101       | 3.25%   |
| Intel Wi-Fi 6 AX200                                                     | 101       | 3.25%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 100       | 3.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 90        | 2.9%    |
| Intel Wi-Fi 6 AX201                                                     | 73        | 2.35%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 63        | 2.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 59        | 1.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 55        | 1.77%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 51        | 1.64%   |
| Intel Wireless 3165                                                     | 48        | 1.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 47        | 1.51%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 46        | 1.48%   |
| Intel Centrino Ultimate-N 6300                                          | 43        | 1.39%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 43        | 1.39%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 41        | 1.32%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 39        | 1.26%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 39        | 1.26%   |
| Intel Centrino Advanced-N 6200                                          | 38        | 1.22%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 34        | 1.1%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 33        | 1.06%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 33        | 1.06%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 32        | 1.03%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 32        | 1.03%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 31        | 1%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 31        | 1%      |
| Intel Wireless 3160                                                     | 31        | 1%      |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 30        | 0.97%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 30        | 0.97%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 29        | 0.93%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 29        | 0.93%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 28        | 0.9%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 28        | 0.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 26        | 0.84%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 26        | 0.84%   |
| Intel WiFi Link 5100                                                    | 26        | 0.84%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 1109      | 40.71%  |
| Realtek Semiconductor                  | 1012      | 37.15%  |
| Qualcomm Atheros                       | 147       | 5.4%    |
| Broadcom                               | 141       | 5.18%   |
| AMD                                    | 95        | 3.49%   |
| Marvell Technology Group               | 65        | 2.39%   |
| Samsung Electronics                    | 31        | 1.14%   |
| Nvidia                                 | 28        | 1.03%   |
| Xiaomi                                 | 19        | 0.7%    |
| JMicron Technology                     | 15        | 0.55%   |
| Google                                 | 10        | 0.37%   |
| Silicon Integrated Systems [SiS]       | 7         | 0.26%   |
| Qualcomm                               | 6         | 0.22%   |
| Apple                                  | 5         | 0.18%   |
| OPPO Electronics                       | 4         | 0.15%   |
| Huawei Technologies                    | 4         | 0.15%   |
| MediaTek                               | 3         | 0.11%   |
| Lenovo                                 | 3         | 0.11%   |
| VIA Technologies                       | 2         | 0.07%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.07%   |
| Realtek                                | 2         | 0.07%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.07%   |
| Novatel Wireless                       | 2         | 0.07%   |
| Motorola PCS                           | 2         | 0.07%   |
| T & A Mobile Phones                    | 1         | 0.04%   |
| National Semiconductor                 | 1         | 0.04%   |
| Microsoft                              | 1         | 0.04%   |
| ICS Advent                             | 1         | 0.04%   |
| HMD Global                             | 1         | 0.04%   |
| Attansic                               | 1         | 0.04%   |
| Aquantia                               | 1         | 0.04%   |
| 3Com                                   | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 752       | 27.34%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 240       | 8.72%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 229       | 8.32%   |
| AMD XGMAC 10GbE Controller                                             | 95        | 3.45%   |
| Intel Ethernet Connection I219-LM                                      | 81        | 2.94%   |
| Intel I210 Gigabit Network Connection                                  | 76        | 2.76%   |
| Intel Ethernet Connection (4) I219-LM                                  | 73        | 2.65%   |
| Intel Ethernet Connection (3) I218-LM                                  | 62        | 2.25%   |
| Intel 82577LM Gigabit Network Connection                               | 57        | 2.07%   |
| Intel Ethernet Connection I218-LM                                      | 56        | 2.04%   |
| Intel I211 Gigabit Network Connection                                  | 47        | 1.71%   |
| Intel Ethernet Connection I217-LM                                      | 43        | 1.56%   |
| Intel Ethernet Connection (4) I219-V                                   | 42        | 1.53%   |
| Intel 82567LM Gigabit Network Connection                               | 41        | 1.49%   |
| Intel Ethernet Connection (2) I219-LM                                  | 29        | 1.05%   |
| Nvidia MCP79 Ethernet                                                  | 27        | 0.98%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 24        | 0.87%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 24        | 0.87%   |
| Intel 82566MM Gigabit Network Connection                               | 22        | 0.8%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 21        | 0.76%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 20        | 0.73%   |
| Intel Ethernet Controller I225-V                                       | 20        | 0.73%   |
| Intel Ethernet Connection I219-V                                       | 20        | 0.73%   |
| Intel Ethernet Connection (6) I219-V                                   | 19        | 0.69%   |
| Intel 82574L Gigabit Network Connection                                | 18        | 0.65%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 16        | 0.58%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 16        | 0.58%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 16        | 0.58%   |
| Intel Ethernet Connection (6) I219-LM                                  | 16        | 0.58%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 16        | 0.58%   |
| Intel Ethernet Connection (7) I219-LM                                  | 15        | 0.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 14        | 0.51%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 14        | 0.51%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 14        | 0.51%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 13        | 0.47%   |
| Intel Ethernet Connection (3) I218-V                                   | 12        | 0.44%   |
| Intel 82573L Gigabit Ethernet Controller                               | 12        | 0.44%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 11        | 0.4%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 11        | 0.4%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 11        | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2779      | 50.99%  |
| Ethernet | 2542      | 46.64%  |
| Modem    | 66        | 1.21%   |
| Unknown  | 63        | 1.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1861      | 51.04%  |
| Ethernet | 1761      | 48.3%   |
| Modem    | 13        | 0.36%   |
| Unknown  | 11        | 0.3%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2234      | 74.17%  |
| 1     | 546       | 18.13%  |
| 6     | 88        | 2.92%   |
| 3     | 72        | 2.39%   |
| 5     | 41        | 1.36%   |
| 0     | 19        | 0.63%   |
| 4     | 6         | 0.2%    |
| 8     | 4         | 0.13%   |
| 10    | 1         | 0.03%   |
| 7     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2796      | 91.4%   |
| Yes  | 263       | 8.6%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1113      | 54.75%  |
| Broadcom                        | 190       | 9.35%   |
| Qualcomm Atheros Communications | 136       | 6.69%   |
| Apple                           | 126       | 6.2%    |
| Realtek Semiconductor           | 120       | 5.9%    |
| IMC Networks                    | 69        | 3.39%   |
| Foxconn / Hon Hai               | 66        | 3.25%   |
| Lite-On Technology              | 55        | 2.71%   |
| Dell                            | 41        | 2.02%   |
| Hewlett-Packard                 | 29        | 1.43%   |
| Cambridge Silicon Radio         | 18        | 0.89%   |
| Alps Electric                   | 18        | 0.89%   |
| ASUSTek Computer                | 17        | 0.84%   |
| Ralink                          | 10        | 0.49%   |
| Skylight Digital                | 6         | 0.3%    |
| USI                             | 3         | 0.15%   |
| TP-Link                         | 2         | 0.1%    |
| Toshiba                         | 2         | 0.1%    |
| Taiyo Yuden                     | 2         | 0.1%    |
| Fujitsu                         | 2         | 0.1%    |
| Creative Technology             | 2         | 0.1%    |
| Shenzhen Goodix Technology      | 1         | 0.05%   |
| Ralink Technology               | 1         | 0.05%   |
| Opticis                         | 1         | 0.05%   |
| MediaTek                        | 1         | 0.05%   |
| Esel International              | 1         | 0.05%   |
| Askey Computer                  | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 558       | 27.37%  |
| Intel AX201 Bluetooth                                       | 154       | 7.55%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 128       | 6.28%   |
| Intel AX200 Bluetooth                                       | 97        | 4.76%   |
| Apple Bluetooth Host Controller                             | 67        | 3.29%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 64        | 3.14%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 57        | 2.8%    |
| Intel AX210 Bluetooth                                       | 44        | 2.16%   |
| Realtek Bluetooth Adapter                                   | 42        | 2.06%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 34        | 1.67%   |
| Intel Wireless-AC 3168 Bluetooth                            | 33        | 1.62%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 30        | 1.47%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 29        | 1.42%   |
| Apple Broadcom Built-in Bluetooth                           | 28        | 1.37%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 27        | 1.32%   |
| Intel AX211 Bluetooth                                       | 23        | 1.13%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 22        | 1.08%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 19        | 0.93%   |
| Lite-On Atheros AR3012 Bluetooth                            | 18        | 0.88%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 18        | 0.88%   |
| Realtek  Bluetooth 4.2 Adapter                              | 17        | 0.83%   |
| Dell DW375 Bluetooth Module                                 | 17        | 0.83%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 17        | 0.83%   |
| IMC Networks Realtek Bluetooth Adapter                      | 16        | 0.78%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 16        | 0.78%   |
| Realtek Bluetooth 4.0 Adapter                               | 15        | 0.74%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 15        | 0.74%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 15        | 0.74%   |
| Apple Built-in iSight (no firmware loaded)                  | 15        | 0.74%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 13        | 0.64%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 13        | 0.64%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 12        | 0.59%   |
| Alps Electric UGTZ4 Bluetooth                               | 12        | 0.59%   |
| Realtek RTL8723B Bluetooth                                  | 11        | 0.54%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 11        | 0.54%   |
| Ralink RT3290 Bluetooth                                     | 10        | 0.49%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 10        | 0.49%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 10        | 0.49%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 10        | 0.49%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 10        | 0.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2463      | 74.23%  |
| AMD                                          | 493       | 14.86%  |
| Nvidia                                       | 238       | 7.17%   |
| Lenovo                                       | 17        | 0.51%   |
| C-Media Electronics                          | 11        | 0.33%   |
| Realtek Semiconductor                        | 10        | 0.3%    |
| Logitech                                     | 9         | 0.27%   |
| Silicon Integrated Systems [SiS]             | 8         | 0.24%   |
| GN Netcom                                    | 8         | 0.24%   |
| Texas Instruments                            | 7         | 0.21%   |
| ASUSTek Computer                             | 5         | 0.15%   |
| Zoran Co. Personal Media Division (Nogatech) | 4         | 0.12%   |
| SteelSeries ApS                              | 4         | 0.12%   |
| Plantronics                                  | 4         | 0.12%   |
| Creative Technology                          | 4         | 0.12%   |
| Kingston Technology                          | 3         | 0.09%   |
| Generalplus Technology                       | 3         | 0.09%   |
| VIA Technologies                             | 2         | 0.06%   |
| Microsoft                                    | 2         | 0.06%   |
| JMTek                                        | 2         | 0.06%   |
| ESS Technology                               | 2         | 0.06%   |
| CMX Systems                                  | 2         | 0.06%   |
| Cambridge Silicon Radio                      | 2         | 0.06%   |
| XMOS                                         | 1         | 0.03%   |
| ULi Electronics                              | 1         | 0.03%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.03%   |
| Sony                                         | 1         | 0.03%   |
| RODE Microphones                             | 1         | 0.03%   |
| PS Audio                                     | 1         | 0.03%   |
| Phison Electronics                           | 1         | 0.03%   |
| M-Audio                                      | 1         | 0.03%   |
| Hewlett-Packard                              | 1         | 0.03%   |
| Elitegroup Computer Systems (ECS)            | 1         | 0.03%   |
| DSEA A/S                                     | 1         | 0.03%   |
| Conexant Systems                             | 1         | 0.03%   |
| Cambridge Audio                              | 1         | 0.03%   |
| Blue Microphones                             | 1         | 0.03%   |
| Apogee Electronics                           | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 400       | 9.88%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 308       | 7.61%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 264       | 6.52%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 226       | 5.58%   |
| Intel 8 Series HD Audio Controller                                                                | 187       | 4.62%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 186       | 4.59%   |
| Intel Broadwell-U Audio Controller                                                                | 162       | 4%      |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 155       | 3.83%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 127       | 3.14%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 121       | 2.99%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 115       | 2.84%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 101       | 2.5%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 87        | 2.15%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 84        | 2.08%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 77        | 1.9%    |
| Intel Cannon Lake PCH cAVS                                                                        | 74        | 1.83%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 74        | 1.83%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 67        | 1.66%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 66        | 1.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 62        | 1.53%   |
| AMD FCH Azalia Controller                                                                         | 60        | 1.48%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 47        | 1.16%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 45        | 1.11%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 43        | 1.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 40        | 0.99%   |
| AMD Kabini HDMI/DP Audio                                                                          | 40        | 0.99%   |
| Intel Comet Lake PCH cAVS                                                                         | 36        | 0.89%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 35        | 0.86%   |
| Intel CM238 HD Audio Controller                                                                   | 33        | 0.82%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 33        | 0.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 32        | 0.79%   |
| Nvidia MCP79 High Definition Audio                                                                | 30        | 0.74%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 28        | 0.69%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 26        | 0.64%   |
| Unknown                                                                                           | 24        | 0.59%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 23        | 0.57%   |
| AMD High Definition Audio Controller                                                              | 22        | 0.54%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 21        | 0.52%   |
| AMD Wrestler HDMI Audio                                                                           | 20        | 0.49%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 18        | 0.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 873       | 26.8%   |
| SK hynix            | 666       | 20.44%  |
| Micron Technology   | 335       | 10.28%  |
| Kingston            | 274       | 8.41%   |
| Unknown             | 230       | 7.06%   |
| Crucial             | 150       | 4.6%    |
| Transcend           | 115       | 3.53%   |
| Unknown             | 96        | 2.95%   |
| Elpida              | 82        | 2.52%   |
| Ramaxel Technology  | 70        | 2.15%   |
| A-DATA Technology   | 53        | 1.63%   |
| Nanya Technology    | 43        | 1.32%   |
| Corsair             | 37        | 1.14%   |
| Smart               | 34        | 1.04%   |
| G.Skill             | 22        | 0.68%   |
| Team                | 16        | 0.49%   |
| Unknown (ABCD)      | 14        | 0.43%   |
| 48spaces            | 11        | 0.34%   |
| PNY                 | 9         | 0.28%   |
| Apacer              | 9         | 0.28%   |
| Teikon              | 8         | 0.25%   |
| GOODRAM             | 8         | 0.25%   |
| Patriot             | 6         | 0.18%   |
| High Bridge         | 6         | 0.18%   |
| Avant               | 6         | 0.18%   |
| ASint Technology    | 6         | 0.18%   |
| Smart Brazil        | 5         | 0.15%   |
| Neo Forza           | 5         | 0.15%   |
| SHARETRONIC         | 4         | 0.12%   |
| Goldkey             | 4         | 0.12%   |
| Magnum Tech         | 3         | 0.09%   |
| GSkill              | 3         | 0.09%   |
| V-GeN               | 2         | 0.06%   |
| Toshiba             | 2         | 0.06%   |
| Super Talent        | 2         | 0.06%   |
| Silicon Power       | 2         | 0.06%   |
| Sesame              | 2         | 0.06%   |
| Qimonda             | 2         | 0.06%   |
| PUSKILL             | 2         | 0.06%   |
| Multilaser          | 2         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Unknown                                                     | 96        | 2.76%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s         | 58        | 1.67%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s       | 54        | 1.55%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 53        | 1.53%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 46        | 1.32%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 46        | 1.32%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 45        | 1.3%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                  | 39        | 1.12%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s      | 37        | 1.07%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s       | 33        | 0.95%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s       | 32        | 0.92%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 30        | 0.86%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s       | 27        | 0.78%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s       | 27        | 0.78%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s       | 27        | 0.78%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s       | 25        | 0.72%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s       | 22        | 0.63%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s       | 22        | 0.63%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s       | 22        | 0.63%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s       | 21        | 0.6%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 20        | 0.58%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 19        | 0.55%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s     | 19        | 0.55%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s       | 18        | 0.52%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s       | 18        | 0.52%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s       | 17        | 0.49%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 17        | 0.49%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                  | 16        | 0.46%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s       | 16        | 0.46%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s       | 16        | 0.46%   |
| Unknown RAM Module 2GB SODIMM DDR2                          | 15        | 0.43%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s       | 15        | 0.43%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 15        | 0.43%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s       | 15        | 0.43%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 14        | 0.4%    |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 14        | 0.4%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s      | 14        | 0.4%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s      | 14        | 0.4%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 14        | 0.4%    |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s       | 14        | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 1265      | 46.08%  |
| DDR4    | 978       | 35.63%  |
| DDR2    | 203       | 7.4%    |
| LPDDR3  | 83        | 3.02%   |
| LPDDR4  | 60        | 2.19%   |
| Unknown | 35        | 1.28%   |
| DDR5    | 31        | 1.13%   |
| DDR     | 31        | 1.13%   |
| LPDDR5  | 25        | 0.91%   |
| SDRAM   | 22        | 0.8%    |
| DRAM    | 9         | 0.33%   |
| RAM     | 2         | 0.07%   |
| SRAM    | 1         | 0.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| SODIMM          | 2514      | 91.02%  |
| Row Of Chips    | 154       | 5.58%   |
| Chip            | 54        | 1.96%   |
| Unknown         | 22        | 0.8%    |
| DIMM            | 17        | 0.62%   |
| Proprietary Car | 1         | 0.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 1041      | 34.15%  |
| 4096  | 995       | 32.64%  |
| 2048  | 511       | 16.77%  |
| 16384 | 306       | 10.04%  |
| 1024  | 109       | 3.58%   |
| 32768 | 60        | 1.97%   |
| 512   | 16        | 0.52%   |
| 256   | 6         | 0.2%    |
| 128   | 2         | 0.07%   |
| 65536 | 1         | 0.03%   |
| 2560  | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 822       | 27.72%  |
| 2667    | 391       | 13.19%  |
| 3200    | 280       | 9.44%   |
| 1333    | 260       | 8.77%   |
| 2400    | 254       | 8.57%   |
| 2133    | 170       | 5.73%   |
| 1334    | 156       | 5.26%   |
| 667     | 128       | 4.32%   |
| 1067    | 84        | 2.83%   |
| Unknown | 80        | 2.7%    |
| 1867    | 75        | 2.53%   |
| 800     | 74        | 2.5%    |
| 4267    | 29        | 0.98%   |
| 533     | 24        | 0.81%   |
| 4800    | 22        | 0.74%   |
| 1066    | 21        | 0.71%   |
| 6400    | 19        | 0.64%   |
| 975     | 13        | 0.44%   |
| 5600    | 9         | 0.3%    |
| 4266    | 8         | 0.27%   |
| 3733    | 6         | 0.2%    |
| 2048    | 6         | 0.2%    |
| 1866    | 5         | 0.17%   |
| 1200    | 4         | 0.13%   |
| 4000    | 3         | 0.1%    |
| 1639    | 3         | 0.1%    |
| 333     | 3         | 0.1%    |
| 2933    | 2         | 0.07%   |
| 2666    | 2         | 0.07%   |
| 400     | 2         | 0.07%   |
| 266     | 2         | 0.07%   |
| 166     | 2         | 0.07%   |
| 7500    | 1         | 0.03%   |
| 2800    | 1         | 0.03%   |
| 1596    | 1         | 0.03%   |
| 666     | 1         | 0.03%   |
| 200     | 1         | 0.03%   |
| 100     | 1         | 0.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| ELGIN               | 2         | 33.33%  |
| Samsung Electronics | 1         | 16.67%  |
| Prolific Technology | 1         | 16.67%  |
| Hewlett-Packard     | 1         | 16.67%  |
| Brother Industries  | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| ELGIN L42PRO                       | 2         | 33.33%  |
| Samsung ML-1610 Mono Laser Printer | 1         | 16.67%  |
| Prolific PL2305 Parallel Port      | 1         | 16.67%  |
| HP LaserJet 1020                   | 1         | 16.67%  |
| Brother HL-L2340D series           | 1         | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 120 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 605       | 28.99%  |
| Bison Electronics                      | 234       | 11.21%  |
| IMC Networks                           | 203       | 9.73%   |
| Microdia                               | 185       | 8.86%   |
| Realtek Semiconductor                  | 174       | 8.34%   |
| Sunplus Innovation Technology          | 118       | 5.65%   |
| Lite-On Technology                     | 73        | 3.5%    |
| Suyin                                  | 70        | 3.35%   |
| Quanta                                 | 51        | 2.44%   |
| Syntek                                 | 49        | 2.35%   |
| Cheng Uei Precision Industry (Foxlink) | 47        | 2.25%   |
| Apple                                  | 43        | 2.06%   |
| Luxvisions Innotech Limited            | 31        | 1.49%   |
| Silicon Motion                         | 30        | 1.44%   |
| Lenovo                                 | 28        | 1.34%   |
| Alcor Micro                            | 25        | 1.2%    |
| ALi                                    | 16        | 0.77%   |
| Z-Star Microelectronics                | 15        | 0.72%   |
| Ricoh                                  | 12        | 0.57%   |
| Logitech                               | 11        | 0.53%   |
| Importek                               | 11        | 0.53%   |
| Shenzhen Kingcome Optoelectronic       | 8         | 0.38%   |
| Supreme Electronics                    | 6         | 0.29%   |
| Primax Electronics                     | 4         | 0.19%   |
| Jiangxi Shinetech Optical              | 4         | 0.19%   |
| Intel                                  | 4         | 0.19%   |
| USB Camera                             | 3         | 0.14%   |
| Tripath Technology                     | 3         | 0.14%   |
| OmniVision Technologies                | 3         | 0.14%   |
| DigiTech                               | 3         | 0.14%   |
| Unknown (3730304233435731375051)       | 2         | 0.1%    |
| Unknown                                | 2         | 0.1%    |
| Pixart Imaging                         | 2         | 0.1%    |
| Genesys Logic                          | 2         | 0.1%    |
| Cubeternet                             | 2         | 0.1%    |
| Y Media                                | 1         | 0.05%   |
| SunplusIT                              | 1         | 0.05%   |
| SIMPLO Technology                      | 1         | 0.05%   |
| Nanchang BYD Electronics               | 1         | 0.05%   |
| Goodong Industry                       | 1         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 189       | 8.97%   |
| Bison Integrated Camera                       | 108       | 5.13%   |
| IMC Networks Integrated Camera                | 65        | 3.08%   |
| Microdia Integrated_Webcam_HD                 | 60        | 2.85%   |
| Lite-On Integrated Camera                     | 48        | 2.28%   |
| Chicony Lenovo Integrated Camera (0.3MP)      | 44        | 2.09%   |
| Realtek Integrated_Webcam_HD                  | 43        | 2.04%   |
| Chicony HD Webcam                             | 43        | 2.04%   |
| Microdia Integrated Webcam                    | 41        | 1.95%   |
| Sunplus Integrated_Webcam_HD                  | 40        | 1.9%    |
| Realtek USB 2.0 PC Camera                     | 29        | 1.38%   |
| Chicony Integrated Camera (1280x720@30)       | 27        | 1.28%   |
| Bison Lenovo EasyCamera                       | 27        | 1.28%   |
| IMC Networks Realtek PC Camera                | 24        | 1.14%   |
| Apple FaceTime HD Camera                      | 24        | 1.14%   |
| IMC Networks EasyCamera                       | 22        | 1.04%   |
| Bison SunplusIT Integrated Camera             | 22        | 1.04%   |
| Chicony Integrated Camera [ThinkPad]          | 20        | 0.95%   |
| Syntek Lenovo EasyCamera                      | 18        | 0.85%   |
| Realtek USB Camera                            | 17        | 0.81%   |
| Chicony Integrated IR Camera                  | 17        | 0.81%   |
| Bison ThinkPad Integrated Camera              | 17        | 0.81%   |
| Lenovo Integrated Webcam [R5U877]             | 16        | 0.76%   |
| Syntek Integrated Camera                      | 15        | 0.71%   |
| Luxvisions Innotech Limited Integrated Camera | 15        | 0.71%   |
| Chicony Realtek DMFT RGB                      | 15        | 0.71%   |
| Chicony HP HD Webcam [Fixed]                  | 14        | 0.66%   |
| Chicony FJ Camera                             | 14        | 0.66%   |
| Sunplus Laptop_Integrated_Webcam_FHD          | 13        | 0.62%   |
| Chicony EasyCamera                            | 13        | 0.62%   |
| Chicony Chicony USB2.0 Camera                 | 13        | 0.62%   |
| Bison Lenovo Integrated Webcam                | 13        | 0.62%   |
| Syntek EasyCamera                             | 12        | 0.57%   |
| Microdia Laptop_Integrated_Webcam_HD          | 12        | 0.57%   |
| IMC Networks Realtek DMFT RGB                 | 12        | 0.57%   |
| Chicony Lenovo EasyCamera                     | 12        | 0.57%   |
| Apple FaceTime HD Camera (Built-in)           | 12        | 0.57%   |
| Suyin Acer/HP Integrated Webcam [CN0314]      | 11        | 0.52%   |
| Microdia Integrated Webcam HD                 | 11        | 0.52%   |
| Microdia Dell Laptop Integrated Webcam HD     | 11        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 216       | 36.36%  |
| Synaptics                  | 114       | 19.19%  |
| Upek                       | 63        | 10.61%  |
| Shenzhen Goodix Technology | 49        | 8.25%   |
| AuthenTec                  | 48        | 8.08%   |
| STMicroelectronics         | 31        | 5.22%   |
| Elan Microelectronics      | 23        | 3.87%   |
| Broadcom                   | 19        | 3.2%    |
| LighTuning Technology      | 15        | 2.53%   |
| FocalTech Systems          | 10        | 1.68%   |
| Fingerprint Cards          | 3         | 0.51%   |
| Samsung Electronics        | 2         | 0.34%   |
| Next Biometrics            | 1         | 0.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 73        | 12.29%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 60        | 10.1%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 50        | 8.42%   |
| Shenzhen Goodix Fingerprint Reader                                           | 36        | 6.06%   |
| Validity Sensors Synaptics WBDI                                              | 35        | 5.89%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 34        | 5.72%   |
| STMicroelectronics Fingerprint Reader                                        | 31        | 5.22%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 26        | 4.38%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 22        | 3.7%    |
| Elan Fingerprint Sensor                                                      | 20        | 3.37%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 19        | 3.2%    |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 18        | 3.03%   |
| AuthenTec AES2810                                                            | 15        | 2.53%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 12        | 2.02%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 8         | 1.35%   |
| Shenzhen Goodix  Fingerprint Device                                          | 8         | 1.35%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 8         | 1.35%   |
| AuthenTec AES1660                                                            | 8         | 1.35%   |
| Validity Sensors VFS491                                                      | 7         | 1.18%   |
| FocalTech Systems Fingerprint Reader                                         | 7         | 1.18%   |
| AuthenTec AES1600                                                            | 7         | 1.18%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 6         | 1.01%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                     | 6         | 1.01%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 6         | 1.01%   |
| Validity Sensors Fingerprint scanner                                         | 5         | 0.84%   |
| Shenzhen Goodix Fingerprint Reader SGX                                       | 5         | 0.84%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                            | 4         | 0.67%   |
| Validity Sensors VFS451 Fingerprint Reader                                   | 4         | 0.67%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint   | 4         | 0.67%   |
| Validity Sensors Swipe Fingerprint Sensor                                    | 4         | 0.67%   |
| Synaptics WBDI Fingerprint Reader USB 086                                    | 4         | 0.67%   |
| Synaptics WBDI                                                               | 4         | 0.67%   |
| Validity Sensors VFS101 Fingerprint Reader                                   | 3         | 0.51%   |
| Validity Sensors VFS Fingerprint sensor                                      | 3         | 0.51%   |
| Upek TCS5B Fingerprint sensor                                                | 3         | 0.51%   |
| Synaptics UWP WBDI Device                                                    | 3         | 0.51%   |
| Fingerprint Cards FPC Fingerprint Reader                                     | 3         | 0.51%   |
| Elan WBF Fingerprint Sensor                                                  | 3         | 0.51%   |
| AuthenTec AES2660                                                            | 3         | 0.51%   |
| Synaptics Fingerprint reader [HP G6]                                         | 2         | 0.34%   |

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
| 1     | 1023      | 32.37%  |
| 2     | 917       | 29.02%  |
| 3     | 498       | 15.76%  |
| 0     | 451       | 14.27%  |
| 4     | 196       | 6.2%    |
| 5     | 54        | 1.71%   |
| 6     | 14        | 0.44%   |
| 7     | 5         | 0.16%   |
| 9     | 1         | 0.03%   |
| 8     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 2075      | 42.18%  |
| Bluetooth                | 717       | 14.58%  |
| Net/wireless             | 580       | 11.79%  |
| Card reader              | 547       | 11.12%  |
| Fingerprint reader       | 505       | 10.27%  |
| Firewire controller      | 193       | 3.92%   |
| Graphics card            | 84        | 1.71%   |
| Sound                    | 56        | 1.14%   |
| Storage                  | 51        | 1.04%   |
| Network                  | 45        | 0.91%   |
| Net/ethernet             | 24        | 0.49%   |
| Modem                    | 24        | 0.49%   |
| Storage/ata              | 9         | 0.18%   |
| Storage/raid             | 3         | 0.06%   |
| Storage/nvme             | 2         | 0.04%   |
| Storage/ide              | 2         | 0.04%   |
| Dvb card                 | 2         | 0.04%   |

