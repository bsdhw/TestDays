BSD in Germany - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for BSD in Germany.

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

Total: 453

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| HP            | EliteBook 2540p             | [c915c03729](https://bsd-hardware.info/?probe=c915c03729) | Dec 30, 2023 |
| Deciso        | NetBoard-A10                | [66f7dd1f06](https://bsd-hardware.info/?probe=66f7dd1f06) | Dec 29, 2023 |
| Lenovo        | ThinkPad T480 20L6S8LW00    | [b6c3c05155](https://bsd-hardware.info/?probe=b6c3c05155) | Dec 25, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [7ca1ae0c93](https://bsd-hardware.info/?probe=7ca1ae0c93) | Dec 23, 2023 |
| Lenovo        | ThinkPad T480 20L6S8LW00    | [32c06c5669](https://bsd-hardware.info/?probe=32c06c5669) | Dec 23, 2023 |
| CSL-Comput... | C15 v3                      | [dd93594896](https://bsd-hardware.info/?probe=dd93594896) | Dec 16, 2023 |
| Dell          | XPS 13 9370                 | [b6845a3e54](https://bsd-hardware.info/?probe=b6845a3e54) | Dec 15, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [c197b26909](https://bsd-hardware.info/?probe=c197b26909) | Dec 14, 2023 |
| Dell          | Latitude E6540              | [77a9b10ab9](https://bsd-hardware.info/?probe=77a9b10ab9) | Dec 13, 2023 |
| HP            | EliteBook 840 G6            | [7476cc6440](https://bsd-hardware.info/?probe=7476cc6440) | Dec 06, 2023 |
| Apple         | MacBookAir7,2               | [3784a39a41](https://bsd-hardware.info/?probe=3784a39a41) | Dec 06, 2023 |
| Wortmann      | TERRA_MOBILE_1541           | [63f1a71855](https://bsd-hardware.info/?probe=63f1a71855) | Dec 04, 2023 |
| Unknown       | Unknown                     | [7d3416a30f](https://bsd-hardware.info/?probe=7d3416a30f) | Nov 30, 2023 |
| Deciso        | DEC2700 - OPNsense Appli... | [e98e7bcab5](https://bsd-hardware.info/?probe=e98e7bcab5) | Nov 29, 2023 |
| Unknown       | Unknown                     | [55339dbfab](https://bsd-hardware.info/?probe=55339dbfab) | Nov 26, 2023 |
| Unknown       | Unknown                     | [ff855b549e](https://bsd-hardware.info/?probe=ff855b549e) | Nov 20, 2023 |
| Panasonic     | CF-31-5                     | [8771ab6139](https://bsd-hardware.info/?probe=8771ab6139) | Nov 18, 2023 |
| TUXEDO        | Pulse 15 Gen2               | [9061ad4228](https://bsd-hardware.info/?probe=9061ad4228) | Nov 17, 2023 |
| Dell          | Inspiron 1525               | [984f5f2f4b](https://bsd-hardware.info/?probe=984f5f2f4b) | Nov 16, 2023 |
| Unknown       | Unknown                     | [61c7e94f23](https://bsd-hardware.info/?probe=61c7e94f23) | Nov 06, 2023 |
| Unknown       | Unknown                     | [316be7bb33](https://bsd-hardware.info/?probe=316be7bb33) | Nov 06, 2023 |
| Dell          | Latitude E6540              | [a26912fd0d](https://bsd-hardware.info/?probe=a26912fd0d) | Nov 06, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [4f9885c454](https://bsd-hardware.info/?probe=4f9885c454) | Nov 05, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | [a9448cf3b5](https://bsd-hardware.info/?probe=a9448cf3b5) | Nov 04, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [19514dd0bd](https://bsd-hardware.info/?probe=19514dd0bd) | Nov 03, 2023 |
| Lenovo        | ThinkPad X230 23205UG       | [f204abc5fc](https://bsd-hardware.info/?probe=f204abc5fc) | Oct 28, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [09cf753c7a](https://bsd-hardware.info/?probe=09cf753c7a) | Oct 26, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [7a57e0a112](https://bsd-hardware.info/?probe=7a57e0a112) | Oct 21, 2023 |
| Unknown       | Unknown                     | [363b63c1a1](https://bsd-hardware.info/?probe=363b63c1a1) | Oct 18, 2023 |
| ASUSTek       | N552VX                      | [f927cf5ba4](https://bsd-hardware.info/?probe=f927cf5ba4) | Oct 16, 2023 |
| Fujitsu       | LIFEBOOK E744               | [72a9b731f6](https://bsd-hardware.info/?probe=72a9b731f6) | Oct 14, 2023 |
| Deciso        | Netboard A20                | [879efbe255](https://bsd-hardware.info/?probe=879efbe255) | Oct 14, 2023 |
| Lenovo        | ThinkPad X250 20CM004VFR    | [e4ab2acd8d](https://bsd-hardware.info/?probe=e4ab2acd8d) | Oct 11, 2023 |
| Unknown       | Unknown                     | [57e5ab8786](https://bsd-hardware.info/?probe=57e5ab8786) | Oct 08, 2023 |
| Unknown       | Unknown                     | [1f7ab105e3](https://bsd-hardware.info/?probe=1f7ab105e3) | Oct 08, 2023 |
| Dell          | Latitude 5591               | [8f6ca1e82a](https://bsd-hardware.info/?probe=8f6ca1e82a) | Oct 03, 2023 |
| Deciso        | NetBoard-A10                | [5524017014](https://bsd-hardware.info/?probe=5524017014) | Oct 01, 2023 |
| Unknown       | Unknown                     | [7cfd3d40eb](https://bsd-hardware.info/?probe=7cfd3d40eb) | Sep 30, 2023 |
| Dell          | Latitude 5591               | [c30943def8](https://bsd-hardware.info/?probe=c30943def8) | Sep 28, 2023 |
| TUXEDO        | Aura 15 Gen1                | [b31f8c12f8](https://bsd-hardware.info/?probe=b31f8c12f8) | Sep 24, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [de1bdf0601](https://bsd-hardware.info/?probe=de1bdf0601) | Sep 21, 2023 |
| Alienware     | m15                         | [609d2ce1ce](https://bsd-hardware.info/?probe=609d2ce1ce) | Sep 14, 2023 |
| Deciso        | NetBoard-A10                | [0068732d33](https://bsd-hardware.info/?probe=0068732d33) | Sep 13, 2023 |
| HP            | ProBook 4530s               | [0b47c15c42](https://bsd-hardware.info/?probe=0b47c15c42) | Sep 12, 2023 |
| HP            | ProBook 4530s               | [4b6daa1f1c](https://bsd-hardware.info/?probe=4b6daa1f1c) | Sep 12, 2023 |
| Lenovo        | ThinkPad SL 2746N8G         | [07eda65608](https://bsd-hardware.info/?probe=07eda65608) | Sep 09, 2023 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [1d5aff2e2a](https://bsd-hardware.info/?probe=1d5aff2e2a) | Sep 08, 2023 |
| Deciso        | NetBoard-A10                | [f95d1da00c](https://bsd-hardware.info/?probe=f95d1da00c) | Sep 01, 2023 |
| Dell          | Latitude 5591               | [972da999fb](https://bsd-hardware.info/?probe=972da999fb) | Aug 18, 2023 |
| Dell          | Latitude 5591               | [a599361016](https://bsd-hardware.info/?probe=a599361016) | Aug 13, 2023 |
| Unknown       | Unknown                     | [09d17597cf](https://bsd-hardware.info/?probe=09d17597cf) | Aug 01, 2023 |
| Unknown       | Unknown                     | [2a2e7a98e3](https://bsd-hardware.info/?probe=2a2e7a98e3) | Aug 01, 2023 |
| Deciso        | NetBoard-A10                | [65667b2f29](https://bsd-hardware.info/?probe=65667b2f29) | Aug 01, 2023 |
| Deciso        | NetBoard-A20                | [9bd5d8fd54](https://bsd-hardware.info/?probe=9bd5d8fd54) | Jul 31, 2023 |
| Deciso        | NetBoard-A10                | [42fcdacbf7](https://bsd-hardware.info/?probe=42fcdacbf7) | Jul 31, 2023 |
| Lenovo        | ThinkPad X230 23202DG       | [f8ade878ce](https://bsd-hardware.info/?probe=f8ade878ce) | Jul 30, 2023 |
| HP            | Notebook                    | [360790274a](https://bsd-hardware.info/?probe=360790274a) | Jul 29, 2023 |
| Lenovo        | ThinkPad T520 42435GG       | [f3aa06579e](https://bsd-hardware.info/?probe=f3aa06579e) | Jul 20, 2023 |
| Samsung       | RC530/RC730                 | [b76e5e8a87](https://bsd-hardware.info/?probe=b76e5e8a87) | Jul 17, 2023 |
| Deciso        | NetBoard-A10                | [535720220a](https://bsd-hardware.info/?probe=535720220a) | Jul 13, 2023 |
| Tactus        | GeoBook 140                 | [4b7383c876](https://bsd-hardware.info/?probe=4b7383c876) | Jul 11, 2023 |
| Lenovo        | ThinkPad X250 20CLS13Q06    | [c318ab3cc7](https://bsd-hardware.info/?probe=c318ab3cc7) | Jul 09, 2023 |
| Unknown       | Unknown                     | [3725d44c33](https://bsd-hardware.info/?probe=3725d44c33) | Jul 01, 2023 |
| Deciso        | NetBoard-A10                | [2eff359d8f](https://bsd-hardware.info/?probe=2eff359d8f) | Jun 28, 2023 |
| Lenovo        | ThinkPad T430 2347A45       | [6969cd9e1a](https://bsd-hardware.info/?probe=6969cd9e1a) | Jun 20, 2023 |
| Lenovo        | ThinkPad T430 2347A45       | [461a92a1a2](https://bsd-hardware.info/?probe=461a92a1a2) | Jun 20, 2023 |
| Dell          | Latitude E6520              | [98868960d5](https://bsd-hardware.info/?probe=98868960d5) | Jun 18, 2023 |
| Samsung       | NC210/NC110                 | [06f5a9210b](https://bsd-hardware.info/?probe=06f5a9210b) | Jun 17, 2023 |
| Apple         | MacBook7,1                  | [6412e6fb23](https://bsd-hardware.info/?probe=6412e6fb23) | Jun 16, 2023 |
| Lenovo        | ThinkPad T530 2429AP0       | [ddf37e7b17](https://bsd-hardware.info/?probe=ddf37e7b17) | Jun 13, 2023 |
| Samsung       | NC210/NC110                 | [dad27d6099](https://bsd-hardware.info/?probe=dad27d6099) | Jun 13, 2023 |
| HP            | 15                          | [4664b4c93f](https://bsd-hardware.info/?probe=4664b4c93f) | Jun 11, 2023 |
| Toshiba       | Satellite C70-B             | [cf9ed85e65](https://bsd-hardware.info/?probe=cf9ed85e65) | Jun 05, 2023 |
| Toshiba       | Satellite C70-B             | [fc66ebba25](https://bsd-hardware.info/?probe=fc66ebba25) | Jun 05, 2023 |
| Deciso        | NetBoard-A10                | [ab3919bc32](https://bsd-hardware.info/?probe=ab3919bc32) | Jun 04, 2023 |
| Tactus        | GeoFlex 110                 | [df93ad7e83](https://bsd-hardware.info/?probe=df93ad7e83) | May 27, 2023 |
| Lenovo        | ThinkPad T560 20FJS03Q00    | [a2110471aa](https://bsd-hardware.info/?probe=a2110471aa) | May 18, 2023 |
| Deciso        | NetBoard-A10                | [37ee98e0b6](https://bsd-hardware.info/?probe=37ee98e0b6) | May 09, 2023 |
| Apple         | MacBook5,1                  | [da07885adb](https://bsd-hardware.info/?probe=da07885adb) | May 09, 2023 |
| Apple         | MacBook5,1                  | [a5a1ca2ee6](https://bsd-hardware.info/?probe=a5a1ca2ee6) | May 02, 2023 |
| Deciso        | NetBoard-A10                | [79c36f752c](https://bsd-hardware.info/?probe=79c36f752c) | Apr 28, 2023 |
| Apple         | MacBook5,1                  | [52174cc0ba](https://bsd-hardware.info/?probe=52174cc0ba) | Apr 27, 2023 |
| Apple         | MacBook5,1                  | [4c7f33d6a9](https://bsd-hardware.info/?probe=4c7f33d6a9) | Apr 25, 2023 |
| Dell          | Latitude 7280               | [254acb5df8](https://bsd-hardware.info/?probe=254acb5df8) | Apr 20, 2023 |
| Lenovo        | ThinkPad X201 3626WNP       | [d642970071](https://bsd-hardware.info/?probe=d642970071) | Apr 19, 2023 |
| Unknown       | Unknown                     | [c221bccd5d](https://bsd-hardware.info/?probe=c221bccd5d) | Apr 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 34487... | [cec90ddd1b](https://bsd-hardware.info/?probe=cec90ddd1b) | Apr 08, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [f3ac765863](https://bsd-hardware.info/?probe=f3ac765863) | Apr 08, 2023 |
| IGEL Techn... | M340C                       | [6c8b2b7af7](https://bsd-hardware.info/?probe=6c8b2b7af7) | Apr 05, 2023 |
| Lenovo        | ThinkPad X220 4291AN9       | [1646bb53ab](https://bsd-hardware.info/?probe=1646bb53ab) | Mar 25, 2023 |
| Lenovo        | ThinkPad X230 232578G       | [edf47cb2d4](https://bsd-hardware.info/?probe=edf47cb2d4) | Mar 21, 2023 |
| Lenovo        | ThinkPad T61 7659CA1        | [bba228ddc9](https://bsd-hardware.info/?probe=bba228ddc9) | Mar 20, 2023 |
| ASUSTek       | G750JS                      | [bb6117addd](https://bsd-hardware.info/?probe=bb6117addd) | Mar 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [6d9c564a33](https://bsd-hardware.info/?probe=6d9c564a33) | Mar 17, 2023 |
| Lenovo        | ThinkPad X61s 7667WQS       | [f1351003d1](https://bsd-hardware.info/?probe=f1351003d1) | Mar 17, 2023 |
| Acer          | Aspire V3-112P              | [104c10f9b0](https://bsd-hardware.info/?probe=104c10f9b0) | Mar 14, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | [d9d7368322](https://bsd-hardware.info/?probe=d9d7368322) | Mar 13, 2023 |
| Lenovo        | ZIUS6                       | [d387825f01](https://bsd-hardware.info/?probe=d387825f01) | Mar 12, 2023 |
| Dell          | Latitude E6330              | [5c60cd3d04](https://bsd-hardware.info/?probe=5c60cd3d04) | Mar 12, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2BR0... | [56fa0d4656](https://bsd-hardware.info/?probe=56fa0d4656) | Mar 11, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [1a2543f92f](https://bsd-hardware.info/?probe=1a2543f92f) | Mar 06, 2023 |
| Deciso        | NetBoard-A10                | [ca59a5e6f4](https://bsd-hardware.info/?probe=ca59a5e6f4) | Feb 28, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | [59e609fbb2](https://bsd-hardware.info/?probe=59e609fbb2) | Feb 26, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | [d8ba5b3157](https://bsd-hardware.info/?probe=d8ba5b3157) | Feb 19, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | [820596f359](https://bsd-hardware.info/?probe=820596f359) | Feb 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [63b73012e6](https://bsd-hardware.info/?probe=63b73012e6) | Feb 18, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | [9137c7933c](https://bsd-hardware.info/?probe=9137c7933c) | Feb 13, 2023 |
| Shuttle       | DS437T                      | [9a16ad9fec](https://bsd-hardware.info/?probe=9a16ad9fec) | Feb 12, 2023 |
| Alienware     | m15                         | [3ab3e4b671](https://bsd-hardware.info/?probe=3ab3e4b671) | Feb 12, 2023 |
| MSI           | GF76 12UE                   | [371f734e07](https://bsd-hardware.info/?probe=371f734e07) | Feb 10, 2023 |
| Notebook      | NV4XMB,ME,MZ                | [8a2bba8635](https://bsd-hardware.info/?probe=8a2bba8635) | Feb 05, 2023 |
| Lenovo        | ThinkPad P50 20EN0008GE     | [8cb09e34ec](https://bsd-hardware.info/?probe=8cb09e34ec) | Feb 04, 2023 |
| Lenovo        | G70-70 80HW006AGE           | [a52e13cf4e](https://bsd-hardware.info/?probe=a52e13cf4e) | Feb 04, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | [c0a6490fc8](https://bsd-hardware.info/?probe=c0a6490fc8) | Feb 03, 2023 |
| Lenovo        | ThinkPad T460 20FMS04200    | [3178015cd3](https://bsd-hardware.info/?probe=3178015cd3) | Feb 02, 2023 |
| Apple         | MacBookAir5,1               | [eeed92ab62](https://bsd-hardware.info/?probe=eeed92ab62) | Jan 29, 2023 |
| HP            | Laptop 14s-fq1xxx           | [1603f38c4c](https://bsd-hardware.info/?probe=1603f38c4c) | Jan 28, 2023 |
| Fujitsu       | LIFEBOOK S935               | [5c07c1a47e](https://bsd-hardware.info/?probe=5c07c1a47e) | Jan 24, 2023 |
| Dell          | XPS 13 9310                 | [7319560506](https://bsd-hardware.info/?probe=7319560506) | Jan 24, 2023 |
| Medion        | S14409                      | [9a44efb64c](https://bsd-hardware.info/?probe=9a44efb64c) | Jan 23, 2023 |
| Lenovo        | ThinkPad T440p 20AN007FG... | [0883806434](https://bsd-hardware.info/?probe=0883806434) | Jan 22, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | [ab38c51298](https://bsd-hardware.info/?probe=ab38c51298) | Jan 22, 2023 |
| Deciso        | NetBoard-A10                | [624bfd62b5](https://bsd-hardware.info/?probe=624bfd62b5) | Jan 15, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [ced6c29193](https://bsd-hardware.info/?probe=ced6c29193) | Jan 14, 2023 |
| Apple         | MacBookAir5,1               | [0d398d5c59](https://bsd-hardware.info/?probe=0d398d5c59) | Dec 27, 2022 |
| Deciso        | NetBoard-A10                | [b09ff8826c](https://bsd-hardware.info/?probe=b09ff8826c) | Dec 26, 2022 |
| Tactus        | GeoFlex 110                 | [955c355b47](https://bsd-hardware.info/?probe=955c355b47) | Dec 23, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [b38d32b139](https://bsd-hardware.info/?probe=b38d32b139) | Dec 23, 2022 |
| Acer          | Aspire ES1-533              | [570b96d0f7](https://bsd-hardware.info/?probe=570b96d0f7) | Dec 23, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [af2a9d1a42](https://bsd-hardware.info/?probe=af2a9d1a42) | Dec 20, 2022 |
| Unknown       | Unknown                     | [364b3758b6](https://bsd-hardware.info/?probe=364b3758b6) | Dec 20, 2022 |
| Acer          | Swift SF114-34              | [0be43b76d1](https://bsd-hardware.info/?probe=0be43b76d1) | Dec 11, 2022 |
| Dell          | Latitude D610               | [6ef8d8137b](https://bsd-hardware.info/?probe=6ef8d8137b) | Nov 24, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [4c83122cc0](https://bsd-hardware.info/?probe=4c83122cc0) | Nov 14, 2022 |
| Google        | Akemi                       | [2d8e99f0c2](https://bsd-hardware.info/?probe=2d8e99f0c2) | Nov 12, 2022 |
| Deciso        | NetBoard-A20                | [61157ac2b6](https://bsd-hardware.info/?probe=61157ac2b6) | Nov 10, 2022 |
| Deciso        | NetBoard-A10                | [1fc6403341](https://bsd-hardware.info/?probe=1fc6403341) | Nov 08, 2022 |
| Acer          | JM11-MS                     | [3ff8b20107](https://bsd-hardware.info/?probe=3ff8b20107) | Oct 29, 2022 |
| Fujitsu       | LIFEBOOK E752               | [06e6c07e90](https://bsd-hardware.info/?probe=06e6c07e90) | Oct 25, 2022 |
| Dell          | Latitude 5591               | [58b577382a](https://bsd-hardware.info/?probe=58b577382a) | Oct 23, 2022 |
| Alienware     | m15                         | [3304a767ba](https://bsd-hardware.info/?probe=3304a767ba) | Oct 22, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | [17d766d55a](https://bsd-hardware.info/?probe=17d766d55a) | Oct 08, 2022 |
| HP            | 255 G8 Notebook PC          | [f9851a3257](https://bsd-hardware.info/?probe=f9851a3257) | Oct 01, 2022 |
| Tactus        | GeoFlex 110                 | [0b93b5f915](https://bsd-hardware.info/?probe=0b93b5f915) | Sep 28, 2022 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | [b2024820d1](https://bsd-hardware.info/?probe=b2024820d1) | Sep 26, 2022 |
| Gigabyte      | GB-BSi5A-6200               | [c947635b8f](https://bsd-hardware.info/?probe=c947635b8f) | Sep 25, 2022 |
| Gigabyte      | GB-BSi5A-6200               | [533c7f35f1](https://bsd-hardware.info/?probe=533c7f35f1) | Sep 25, 2022 |
| IBM           | ThinkPad T40 23737CG        | [dfc9b64da2](https://bsd-hardware.info/?probe=dfc9b64da2) | Sep 25, 2022 |
| Fujitsu       | LIFEBOOK A532               | [91e0f723ea](https://bsd-hardware.info/?probe=91e0f723ea) | Sep 18, 2022 |
| Deciso        | DEC2700 - OPNsense Appli... | [eee7bdda02](https://bsd-hardware.info/?probe=eee7bdda02) | Sep 15, 2022 |
| Lenovo        | ThinkPad X270 20HMS2LL00    | [12f6a8866f](https://bsd-hardware.info/?probe=12f6a8866f) | Sep 14, 2022 |
| Deciso        | DEC2700 - OPNsense Appli... | [9e6bd1263d](https://bsd-hardware.info/?probe=9e6bd1263d) | Sep 13, 2022 |
| Deciso        | Netboard A20                | [164274c6b4](https://bsd-hardware.info/?probe=164274c6b4) | Aug 22, 2022 |
| Lenovo        | ThinkPad T480 20L50000GE    | [cd7d7d83ba](https://bsd-hardware.info/?probe=cd7d7d83ba) | Aug 20, 2022 |
| Samsung       | NC210/NC110                 | [6c697b3312](https://bsd-hardware.info/?probe=6c697b3312) | Aug 13, 2022 |
| TUXEDO        | Pulse 14 Gen1               | [5edf8a1bef](https://bsd-hardware.info/?probe=5edf8a1bef) | Aug 09, 2022 |
| ASUSTek       | F6A                         | [6626d18284](https://bsd-hardware.info/?probe=6626d18284) | Aug 08, 2022 |
| Apple         | MacBook6,1                  | [55ab4bc8d6](https://bsd-hardware.info/?probe=55ab4bc8d6) | Jul 29, 2022 |
| Shuttle       | DS437                       | [d7b076918a](https://bsd-hardware.info/?probe=d7b076918a) | Jul 07, 2022 |
| Shuttle       | DS437                       | [9fe84a8c9d](https://bsd-hardware.info/?probe=9fe84a8c9d) | Jul 07, 2022 |
| Lenovo        | IdeaPad S12 20021,2959      | [c1bf998d6a](https://bsd-hardware.info/?probe=c1bf998d6a) | Jul 07, 2022 |
| Deciso        | NetBoard-A10                | [681bb27fbc](https://bsd-hardware.info/?probe=681bb27fbc) | Jul 04, 2022 |
| Apple         | MacBook6,1                  | [a6d3cf9a30](https://bsd-hardware.info/?probe=a6d3cf9a30) | Jun 20, 2022 |
| Dell          | Latitude 5521               | [2c9d24a69e](https://bsd-hardware.info/?probe=2c9d24a69e) | Jun 19, 2022 |
| Lenovo        | ThinkPad T420 4236MY0       | [94095d4c11](https://bsd-hardware.info/?probe=94095d4c11) | Jun 06, 2022 |
| TUXEDO        | Aura 15 Gen1                | [727f9708b4](https://bsd-hardware.info/?probe=727f9708b4) | May 24, 2022 |
| HP            | 255 G8 Notebook PC          | [004e039a23](https://bsd-hardware.info/?probe=004e039a23) | May 19, 2022 |
| HP            | 255 G8 Notebook PC          | [555a7733b7](https://bsd-hardware.info/?probe=555a7733b7) | May 19, 2022 |
| TUXEDO        | Aura 15 Gen1                | [1c84f0f722](https://bsd-hardware.info/?probe=1c84f0f722) | May 19, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [86866ce217](https://bsd-hardware.info/?probe=86866ce217) | May 17, 2022 |
| Deciso        | OPNsense Appliance          | [70c9fd07ac](https://bsd-hardware.info/?probe=70c9fd07ac) | May 09, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [5259bc1933](https://bsd-hardware.info/?probe=5259bc1933) | May 08, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [a69f0fefca](https://bsd-hardware.info/?probe=a69f0fefca) | May 07, 2022 |
| Acer          | Aspire E1-570G              | [7fd31252a2](https://bsd-hardware.info/?probe=7fd31252a2) | May 04, 2022 |
| HP            | EliteBook 820 G2            | [3997ff79e4](https://bsd-hardware.info/?probe=3997ff79e4) | May 03, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [f02e4345ff](https://bsd-hardware.info/?probe=f02e4345ff) | Apr 30, 2022 |
| Deciso        | DEC2700 - OPNsense Appli... | [22b192afca](https://bsd-hardware.info/?probe=22b192afca) | Apr 28, 2022 |
| Apple         | MacBookPro3,1               | [912d02aec2](https://bsd-hardware.info/?probe=912d02aec2) | Apr 28, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [30e267dd51](https://bsd-hardware.info/?probe=30e267dd51) | Apr 27, 2022 |
| Lenovo        | B570 1068FQG                | [a0d1f01226](https://bsd-hardware.info/?probe=a0d1f01226) | Apr 22, 2022 |
| AMI           | Intel                       | [db87d63d35](https://bsd-hardware.info/?probe=db87d63d35) | Apr 15, 2022 |
| AMI           | Intel                       | [8dc710d126](https://bsd-hardware.info/?probe=8dc710d126) | Apr 14, 2022 |
| Dell          | Latitude E6440              | [eea29a3895](https://bsd-hardware.info/?probe=eea29a3895) | Apr 12, 2022 |
| Apple         | MacBook5,1                  | [41d62dde7d](https://bsd-hardware.info/?probe=41d62dde7d) | Apr 10, 2022 |
| Apple         | MacBook5,1                  | [c5f7b5499a](https://bsd-hardware.info/?probe=c5f7b5499a) | Apr 10, 2022 |
| Acer          | Swift SF114-32              | [7bc748ce7c](https://bsd-hardware.info/?probe=7bc748ce7c) | Apr 08, 2022 |
| Dell          | Precision M4800             | [7a7968204a](https://bsd-hardware.info/?probe=7a7968204a) | Apr 06, 2022 |
| TUXEDO        | Aura 15 Gen1                | [e72b47b6de](https://bsd-hardware.info/?probe=e72b47b6de) | Apr 04, 2022 |
| Lenovo        | ThinkPad X260 20F5A28AUK    | [f53c625efd](https://bsd-hardware.info/?probe=f53c625efd) | Mar 30, 2022 |
| Fujitsu       | LIFEBOOK A544               | [e363c95c1c](https://bsd-hardware.info/?probe=e363c95c1c) | Mar 29, 2022 |
| Dell          | Latitude E6540              | [41e5f63a69](https://bsd-hardware.info/?probe=41e5f63a69) | Mar 26, 2022 |
| Dell          | Latitude E6540              | [0ac0f8f1d8](https://bsd-hardware.info/?probe=0ac0f8f1d8) | Mar 26, 2022 |
| Notebook      | N13xWU                      | [8986953acd](https://bsd-hardware.info/?probe=8986953acd) | Mar 22, 2022 |
| Notebook      | N7x0WU                      | [b80f84aef1](https://bsd-hardware.info/?probe=b80f84aef1) | Mar 22, 2022 |
| Notebook      | N8xEJEK                     | [9a62677ea8](https://bsd-hardware.info/?probe=9a62677ea8) | Mar 22, 2022 |
| Dell          | Latitude E6500              | [5fad69bbf0](https://bsd-hardware.info/?probe=5fad69bbf0) | Mar 22, 2022 |
| Dell          | Latitude E6510              | [a040a1a04b](https://bsd-hardware.info/?probe=a040a1a04b) | Mar 22, 2022 |
| Dell          | Latitude E6530              | [9bc5fc70a7](https://bsd-hardware.info/?probe=9bc5fc70a7) | Mar 22, 2022 |
| Deciso        | Netboard A20                | [8ded6d9af6](https://bsd-hardware.info/?probe=8ded6d9af6) | Mar 21, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [0dbac1ca61](https://bsd-hardware.info/?probe=0dbac1ca61) | Mar 19, 2022 |
| Toshiba       | Satellite Pro L40           | [5ff92a5bb3](https://bsd-hardware.info/?probe=5ff92a5bb3) | Mar 19, 2022 |
| Toshiba       | Satellite Pro L40           | [71a7b43ec6](https://bsd-hardware.info/?probe=71a7b43ec6) | Mar 19, 2022 |
| Dell          | Latitude E6540              | [e0576dd008](https://bsd-hardware.info/?probe=e0576dd008) | Mar 13, 2022 |
| AEWIN         | CB-7979                     | [ec1e865bbd](https://bsd-hardware.info/?probe=ec1e865bbd) | Mar 07, 2022 |
| Dell          | Latitude 5591               | [d4d653fba8](https://bsd-hardware.info/?probe=d4d653fba8) | Feb 22, 2022 |
| Lenovo        | ThinkPad X240 20AMS2QD0C    | [ae597455a4](https://bsd-hardware.info/?probe=ae597455a4) | Feb 13, 2022 |
| MiTAC         | 5033                        | [54df5c9e9e](https://bsd-hardware.info/?probe=54df5c9e9e) | Feb 10, 2022 |
| ASUSTek       | X555LA                      | [28b3002182](https://bsd-hardware.info/?probe=28b3002182) | Feb 10, 2022 |
| ASUSTek       | X555LA                      | [9aa18b2e33](https://bsd-hardware.info/?probe=9aa18b2e33) | Feb 09, 2022 |
| Apple         | MacBookPro4,1               | [d852363467](https://bsd-hardware.info/?probe=d852363467) | Feb 08, 2022 |
| Apple         | MacBookPro4,1               | [f05ce66a9a](https://bsd-hardware.info/?probe=f05ce66a9a) | Feb 08, 2022 |
| Lenovo        | ThinkPad T440p 20AWS3RH0... | [a6c02e440b](https://bsd-hardware.info/?probe=a6c02e440b) | Feb 05, 2022 |
| GPD           | G1621-02                    | [1970f517fd](https://bsd-hardware.info/?probe=1970f517fd) | Jan 30, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [b1d702812e](https://bsd-hardware.info/?probe=b1d702812e) | Jan 26, 2022 |
| MSI           | GT75VR 7RF                  | [db276eaa53](https://bsd-hardware.info/?probe=db276eaa53) | Jan 25, 2022 |
| Apple         | MacBookPro11,4              | [6d580e8270](https://bsd-hardware.info/?probe=6d580e8270) | Jan 21, 2022 |
| Dell          | Latitude E6540              | [f13972c935](https://bsd-hardware.info/?probe=f13972c935) | Jan 21, 2022 |
| Fujitsu       | CELSIUS H780                | [a173366c78](https://bsd-hardware.info/?probe=a173366c78) | Jan 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [c36023a724](https://bsd-hardware.info/?probe=c36023a724) | Jan 17, 2022 |
| Acer          | TravelMate 8481TG           | [fae71f7e35](https://bsd-hardware.info/?probe=fae71f7e35) | Jan 15, 2022 |
| MSI           | GT75VR 7RF                  | [cca6cc3c0b](https://bsd-hardware.info/?probe=cca6cc3c0b) | Jan 07, 2022 |
| Apple         | MacBook5,1                  | [f0aeeb7f3c](https://bsd-hardware.info/?probe=f0aeeb7f3c) | Jan 05, 2022 |
| Dell          | Latitude 3400               | [41bf32aff1](https://bsd-hardware.info/?probe=41bf32aff1) | Jan 02, 2022 |
| Lenovo        | ThinkPad X220 4293AF4       | [8c7992e557](https://bsd-hardware.info/?probe=8c7992e557) | Jan 01, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [42b4bcbcc2](https://bsd-hardware.info/?probe=42b4bcbcc2) | Dec 27, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [695d7201d4](https://bsd-hardware.info/?probe=695d7201d4) | Dec 27, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [2e1c585715](https://bsd-hardware.info/?probe=2e1c585715) | Dec 21, 2021 |
| Unknown       | Unknown                     | [aa872042e3](https://bsd-hardware.info/?probe=aa872042e3) | Dec 15, 2021 |
| ASUSTek       | 1005P                       | [4c43bd561f](https://bsd-hardware.info/?probe=4c43bd561f) | Dec 14, 2021 |
| Intel         | SharkBay Platform           | [383d1e31c9](https://bsd-hardware.info/?probe=383d1e31c9) | Dec 14, 2021 |
| Unknown       | Unknown                     | [8c3ba89ddd](https://bsd-hardware.info/?probe=8c3ba89ddd) | Dec 12, 2021 |
| Lenovo        | ThinkPad T430s 2356JH4      | [0b6ab3ba1b](https://bsd-hardware.info/?probe=0b6ab3ba1b) | Dec 09, 2021 |
| Dell          | Precision M4300             | [08fe78379d](https://bsd-hardware.info/?probe=08fe78379d) | Dec 08, 2021 |
| Deciso        | Netboard A20                | [593d123f0c](https://bsd-hardware.info/?probe=593d123f0c) | Dec 07, 2021 |
| Lenovo        | ThinkPad T430s 2356JH4      | [b1377872cd](https://bsd-hardware.info/?probe=b1377872cd) | Dec 03, 2021 |
| Unknown       | Unknown                     | [5d1a3bbfe3](https://bsd-hardware.info/?probe=5d1a3bbfe3) | Nov 30, 2021 |
| Shuttle       | DS437                       | [b5d1bcffdb](https://bsd-hardware.info/?probe=b5d1bcffdb) | Nov 29, 2021 |
| Lenovo        | ThinkPad X240 20AMS2QDOC    | [66cfdd2419](https://bsd-hardware.info/?probe=66cfdd2419) | Nov 27, 2021 |
| Shuttle       | DS437                       | [687fc514ba](https://bsd-hardware.info/?probe=687fc514ba) | Nov 27, 2021 |
| Shuttle       | DS437                       | [e65a62f5a5](https://bsd-hardware.info/?probe=e65a62f5a5) | Nov 27, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [8b178d13c7](https://bsd-hardware.info/?probe=8b178d13c7) | Nov 22, 2021 |
| Alienware     | m15                         | [20afd3904b](https://bsd-hardware.info/?probe=20afd3904b) | Nov 21, 2021 |
| Lenovo        | ThinkPad X220 42915CG       | [d8628f80c0](https://bsd-hardware.info/?probe=d8628f80c0) | Nov 19, 2021 |
| Shuttle       | DS437                       | [0dc3d4619e](https://bsd-hardware.info/?probe=0dc3d4619e) | Nov 17, 2021 |
| Acer          | TravelMate B117-M           | [4f02660d9c](https://bsd-hardware.info/?probe=4f02660d9c) | Nov 14, 2021 |
| Lenovo        | ThinkPad W520 4276CTO       | [9082353a69](https://bsd-hardware.info/?probe=9082353a69) | Nov 06, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [1d261120d3](https://bsd-hardware.info/?probe=1d261120d3) | Nov 06, 2021 |
| Lenovo        | ThinkPad T420 4180EE8       | [5303c12fe5](https://bsd-hardware.info/?probe=5303c12fe5) | Nov 05, 2021 |
| Apple         | MacBookAir5,1               | [10d629e1a0](https://bsd-hardware.info/?probe=10d629e1a0) | Nov 04, 2021 |
| BESSTAR Te... | U820                        | [3bd9cd5b98](https://bsd-hardware.info/?probe=3bd9cd5b98) | Nov 03, 2021 |
| Lenovo        | IdeaPad Z360                | [796bd6482f](https://bsd-hardware.info/?probe=796bd6482f) | Nov 02, 2021 |
| BESSTAR Te... | U820                        | [1a39d8a6e3](https://bsd-hardware.info/?probe=1a39d8a6e3) | Nov 02, 2021 |
| Apple         | MacBookAir5,1               | [b354b2bd4e](https://bsd-hardware.info/?probe=b354b2bd4e) | Oct 31, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [d910c79d75](https://bsd-hardware.info/?probe=d910c79d75) | Oct 24, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [d8a6d0daf3](https://bsd-hardware.info/?probe=d8a6d0daf3) | Oct 18, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | [b4ba704356](https://bsd-hardware.info/?probe=b4ba704356) | Oct 17, 2021 |
| Lenovo        | ThinkPad X230 23254G7       | [06c6a282ca](https://bsd-hardware.info/?probe=06c6a282ca) | Oct 16, 2021 |
| Dell          | Inspiron 3493               | [ed41c18cfc](https://bsd-hardware.info/?probe=ed41c18cfc) | Oct 16, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [be42957ecd](https://bsd-hardware.info/?probe=be42957ecd) | Oct 10, 2021 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | [5b08c1de3d](https://bsd-hardware.info/?probe=5b08c1de3d) | Oct 06, 2021 |
| ASUSTek       | UX305FA                     | [decf219ff2](https://bsd-hardware.info/?probe=decf219ff2) | Sep 30, 2021 |
| Lenovo        | ThinkPad X230 2325O76       | [b8729e39e1](https://bsd-hardware.info/?probe=b8729e39e1) | Sep 29, 2021 |
| Unknown       | Unknown                     | [27f807ae11](https://bsd-hardware.info/?probe=27f807ae11) | Sep 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [d9762d6c2d](https://bsd-hardware.info/?probe=d9762d6c2d) | Sep 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [0d00ce5de9](https://bsd-hardware.info/?probe=0d00ce5de9) | Sep 22, 2021 |
| Lenovo        | ThinkPad T400 6474E18       | [2dd5b5869f](https://bsd-hardware.info/?probe=2dd5b5869f) | Sep 13, 2021 |
| Dell          | XPS 15 9570                 | [ee8980fec1](https://bsd-hardware.info/?probe=ee8980fec1) | Sep 07, 2021 |
| Dell          | Latitude 3540               | [2583b22e8d](https://bsd-hardware.info/?probe=2583b22e8d) | Aug 29, 2021 |
| Dell          | Latitude 3540               | [de97e0b2fc](https://bsd-hardware.info/?probe=de97e0b2fc) | Aug 29, 2021 |
| Apple         | MacBookAir7,2               | [6eada6e49e](https://bsd-hardware.info/?probe=6eada6e49e) | Aug 28, 2021 |
| Dell          | Latitude 5591               | [f0ee8a7da0](https://bsd-hardware.info/?probe=f0ee8a7da0) | Aug 25, 2021 |
| Acer          | Aspire ES1-132              | [43c82b1b16](https://bsd-hardware.info/?probe=43c82b1b16) | Aug 22, 2021 |
| Insyde        | Braswell                    | [6c8e94b016](https://bsd-hardware.info/?probe=6c8e94b016) | Aug 19, 2021 |
| Dell          | Latitude 5591               | [c21b6fde68](https://bsd-hardware.info/?probe=c21b6fde68) | Aug 12, 2021 |
| Deciso        | Netboard A20                | [5be914e123](https://bsd-hardware.info/?probe=5be914e123) | Aug 03, 2021 |
| Lenovo        | ThinkPad L512 44444XG       | [a6c8fbcb20](https://bsd-hardware.info/?probe=a6c8fbcb20) | Aug 01, 2021 |
| Sony          | VPCEJ1E1E                   | [c471fb3f82](https://bsd-hardware.info/?probe=c471fb3f82) | Aug 01, 2021 |
| Lenovo        | G550 2958                   | [86880c29cf](https://bsd-hardware.info/?probe=86880c29cf) | Jul 31, 2021 |
| Lenovo        | G550 2958                   | [4fe522eaf3](https://bsd-hardware.info/?probe=4fe522eaf3) | Jul 31, 2021 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [38910aa754](https://bsd-hardware.info/?probe=38910aa754) | Jul 25, 2021 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [3348992bef](https://bsd-hardware.info/?probe=3348992bef) | Jul 23, 2021 |
| Fujitsu       | LIFEBOOK E780               | [71b543094c](https://bsd-hardware.info/?probe=71b543094c) | Jul 22, 2021 |
| MSI           | MS-1613                     | [795e61c1a3](https://bsd-hardware.info/?probe=795e61c1a3) | Jul 21, 2021 |
| Unknown       | Unknown                     | [a37195bcb8](https://bsd-hardware.info/?probe=a37195bcb8) | Jul 15, 2021 |
| Lenovo        | ThinkPad X230 2325A95       | [94d66a0677](https://bsd-hardware.info/?probe=94d66a0677) | Jul 10, 2021 |
| Lenovo        | ThinkPad X230 232578G       | [a8c497b58b](https://bsd-hardware.info/?probe=a8c497b58b) | Jul 09, 2021 |
| Lenovo        | ThinkPad T510 4384FF3       | [25e208721d](https://bsd-hardware.info/?probe=25e208721d) | Jul 02, 2021 |
| Fujitsu       | LIFEBOOK E780               | [2e8c2afe50](https://bsd-hardware.info/?probe=2e8c2afe50) | Jun 20, 2021 |
| Apple         | MacBookAir6,1               | [46bf9edc63](https://bsd-hardware.info/?probe=46bf9edc63) | Jun 17, 2021 |
| Apple         | MacBookAir6,1               | [dbda48cff7](https://bsd-hardware.info/?probe=dbda48cff7) | Jun 17, 2021 |
| HP            | ProBook 640 G1              | [937ed102d1](https://bsd-hardware.info/?probe=937ed102d1) | Jun 12, 2021 |
| ASUSTek       | UX330UAK                    | [430c90b88d](https://bsd-hardware.info/?probe=430c90b88d) | Jun 12, 2021 |
| Unknown       | Unknown                     | [1f2d078d2e](https://bsd-hardware.info/?probe=1f2d078d2e) | Jun 01, 2021 |
| Deciso        | Netboard A20                | [f4a0f0941b](https://bsd-hardware.info/?probe=f4a0f0941b) | May 26, 2021 |
| Unknown       | Unknown                     | [b4b6cfff1f](https://bsd-hardware.info/?probe=b4b6cfff1f) | May 24, 2021 |
| Lenovo        | ThinkPad SL510 28477MG      | [bdbd2d0a05](https://bsd-hardware.info/?probe=bdbd2d0a05) | May 20, 2021 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | [2be8cf963c](https://bsd-hardware.info/?probe=2be8cf963c) | May 02, 2021 |
| HP            | Compaq Presario CQ71        | [258ef16ace](https://bsd-hardware.info/?probe=258ef16ace) | Apr 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [6e8891f184](https://bsd-hardware.info/?probe=6e8891f184) | Apr 24, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [7ec73fe36d](https://bsd-hardware.info/?probe=7ec73fe36d) | Apr 23, 2021 |
| Lenovo        | ThinkPad W541 20EGS04800    | [91d2cd471c](https://bsd-hardware.info/?probe=91d2cd471c) | Apr 16, 2021 |
| Clevo         | W55xEU                      | [229587fbd5](https://bsd-hardware.info/?probe=229587fbd5) | Apr 16, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [403a237513](https://bsd-hardware.info/?probe=403a237513) | Apr 14, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [270bd22b8d](https://bsd-hardware.info/?probe=270bd22b8d) | Apr 14, 2021 |
| Apple         | MacBookPro8,1               | [5d3d014284](https://bsd-hardware.info/?probe=5d3d014284) | Apr 12, 2021 |
| Apple         | MacBookPro8,1               | [ffcc46ea0b](https://bsd-hardware.info/?probe=ffcc46ea0b) | Apr 12, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [bd88655975](https://bsd-hardware.info/?probe=bd88655975) | Apr 10, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [2376cf30b2](https://bsd-hardware.info/?probe=2376cf30b2) | Apr 03, 2021 |
| Dell          | Latitude 5591               | [dadf2c296f](https://bsd-hardware.info/?probe=dadf2c296f) | Mar 30, 2021 |
| TUXEDO        | Unknown                     | [35aa6590c6](https://bsd-hardware.info/?probe=35aa6590c6) | Mar 29, 2021 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [c5e824b558](https://bsd-hardware.info/?probe=c5e824b558) | Mar 29, 2021 |
| Lenovo        | ThinkPad X220 4291IR6       | [3e9aab9818](https://bsd-hardware.info/?probe=3e9aab9818) | Mar 25, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [dc40b42864](https://bsd-hardware.info/?probe=dc40b42864) | Mar 22, 2021 |
| Packard Be... | EasyNote MH36               | [2a98cae4e8](https://bsd-hardware.info/?probe=2a98cae4e8) | Mar 13, 2021 |
| Fujitsu       | LIFEBOOK A555               | [bcb99d0f09](https://bsd-hardware.info/?probe=bcb99d0f09) | Mar 13, 2021 |
| Fujitsu       | LIFEBOOK A555               | [ee894449af](https://bsd-hardware.info/?probe=ee894449af) | Mar 13, 2021 |
| Acer          | Aspire 4810T                | [14af887195](https://bsd-hardware.info/?probe=14af887195) | Mar 11, 2021 |
| HP            | EliteBook 2760p             | [5707fc27ce](https://bsd-hardware.info/?probe=5707fc27ce) | Mar 11, 2021 |
| Clevo         | W55xEU                      | [e51ee3b14c](https://bsd-hardware.info/?probe=e51ee3b14c) | Mar 08, 2021 |
| Dell          | Latitude E6500              | [d25dacc162](https://bsd-hardware.info/?probe=d25dacc162) | Mar 07, 2021 |
| Clevo         | W55xEU                      | [d874753fe2](https://bsd-hardware.info/?probe=d874753fe2) | Mar 07, 2021 |
| Lenovo        | 3000 N200 0769AP2           | [6b81593de9](https://bsd-hardware.info/?probe=6b81593de9) | Mar 06, 2021 |
| Dell          | Latitude 5591               | [e570513187](https://bsd-hardware.info/?probe=e570513187) | Mar 05, 2021 |
| Dell          | Latitude 5400               | [b9d1f08bcf](https://bsd-hardware.info/?probe=b9d1f08bcf) | Mar 04, 2021 |
| Fujitsu       | LIFEBOOK E754               | [d3d033f879](https://bsd-hardware.info/?probe=d3d033f879) | Mar 03, 2021 |
| Fujitsu       | LIFEBOOK E736               | [845c584693](https://bsd-hardware.info/?probe=845c584693) | Mar 03, 2021 |
| Acer          | Extensa 5630                | [6a1b523efb](https://bsd-hardware.info/?probe=6a1b523efb) | Mar 03, 2021 |
| Hampoo        | B3W6_NA123C Reserved        | [bc138c0580](https://bsd-hardware.info/?probe=bc138c0580) | Feb 27, 2021 |
| Fujitsu       | LIFEBOOK E780               | [57506cbdcf](https://bsd-hardware.info/?probe=57506cbdcf) | Feb 26, 2021 |
| Dell          | Latitude 5591               | [0424bf31ca](https://bsd-hardware.info/?probe=0424bf31ca) | Feb 25, 2021 |
| Lenovo        | ThinkPad T520 4242A16       | [49dacee7d0](https://bsd-hardware.info/?probe=49dacee7d0) | Feb 23, 2021 |
| Lenovo        | Z50-70 20354                | [d3d9dc620f](https://bsd-hardware.info/?probe=d3d9dc620f) | Feb 23, 2021 |
| Unknown       | Unknown                     | [eaa6a36e6e](https://bsd-hardware.info/?probe=eaa6a36e6e) | Feb 22, 2021 |
| Lenovo        | ThinkPad T450 20BUS08800    | [d783b3b4dd](https://bsd-hardware.info/?probe=d783b3b4dd) | Feb 22, 2021 |
| Dell          | Latitude 5424 Rugged        | [b94ae57278](https://bsd-hardware.info/?probe=b94ae57278) | Feb 22, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [7f8c483af1](https://bsd-hardware.info/?probe=7f8c483af1) | Feb 21, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [a9604cfdb8](https://bsd-hardware.info/?probe=a9604cfdb8) | Feb 19, 2021 |
| Lenovo        | V130-15IKB 81HN             | [893c17f73a](https://bsd-hardware.info/?probe=893c17f73a) | Feb 19, 2021 |
| Lenovo        | V130-15IKB 81HN             | [d0f504fad2](https://bsd-hardware.info/?probe=d0f504fad2) | Feb 19, 2021 |
| Lenovo        | ZIUS6                       | [1c239bac92](https://bsd-hardware.info/?probe=1c239bac92) | Feb 18, 2021 |
| Clevo         | W55xEU                      | [a66041bae0](https://bsd-hardware.info/?probe=a66041bae0) | Feb 17, 2021 |
| Dell          | Latitude E6330              | [abe1869a95](https://bsd-hardware.info/?probe=abe1869a95) | Feb 17, 2021 |
| Lenovo        | U310                        | [ccec69b736](https://bsd-hardware.info/?probe=ccec69b736) | Feb 16, 2021 |
| Lenovo        | U310                        | [83805a17c5](https://bsd-hardware.info/?probe=83805a17c5) | Feb 16, 2021 |
| Lenovo        | U310                        | [111385095d](https://bsd-hardware.info/?probe=111385095d) | Feb 16, 2021 |
| Apple         | MacBookAir4,2               | [7d8419c918](https://bsd-hardware.info/?probe=7d8419c918) | Feb 16, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | [19f307ff6d](https://bsd-hardware.info/?probe=19f307ff6d) | Feb 16, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [5a393bc680](https://bsd-hardware.info/?probe=5a393bc680) | Feb 15, 2021 |
| Medion        | P6812                       | [c2c592bca8](https://bsd-hardware.info/?probe=c2c592bca8) | Feb 15, 2021 |
| Medion        | P6812                       | [afa43a6aab](https://bsd-hardware.info/?probe=afa43a6aab) | Feb 15, 2021 |
| Fujitsu       | LIFEBOOK E780               | [0f5e891a5d](https://bsd-hardware.info/?probe=0f5e891a5d) | Feb 14, 2021 |
| Lenovo        | ThinkPad T430 2349GCG       | [6da4116499](https://bsd-hardware.info/?probe=6da4116499) | Feb 13, 2021 |
| Lenovo        | ThinkPad T430 2349GCG       | [d212f58dd2](https://bsd-hardware.info/?probe=d212f58dd2) | Feb 13, 2021 |
| Dell          | Latitude 7380               | [1aa2a3a541](https://bsd-hardware.info/?probe=1aa2a3a541) | Feb 12, 2021 |
| Dell          | Latitude 7380               | [4814701c0e](https://bsd-hardware.info/?probe=4814701c0e) | Feb 12, 2021 |
| Clevo         | W55xEU                      | [796ad51947](https://bsd-hardware.info/?probe=796ad51947) | Feb 11, 2021 |
| Clevo         | W55xEU                      | [c28a6397b5](https://bsd-hardware.info/?probe=c28a6397b5) | Feb 11, 2021 |
| Lenovo        | ThinkPad X260 20F5S1H800    | [ca369843a9](https://bsd-hardware.info/?probe=ca369843a9) | Feb 09, 2021 |
| Lenovo        | ThinkPad X220 42915CG       | [0bc3ba767e](https://bsd-hardware.info/?probe=0bc3ba767e) | Feb 06, 2021 |
| Acer          | Extensa 5220                | [5d6a8a51d0](https://bsd-hardware.info/?probe=5d6a8a51d0) | Feb 06, 2021 |
| Acer          | Extensa 5220                | [c443decee1](https://bsd-hardware.info/?probe=c443decee1) | Feb 06, 2021 |
| Fujitsu       | LIFEBOOK E753               | [37245aca21](https://bsd-hardware.info/?probe=37245aca21) | Feb 03, 2021 |
| Unknown       | Unknown                     | [95e264ef56](https://bsd-hardware.info/?probe=95e264ef56) | Feb 02, 2021 |
| Lenovo        | ThinkPad SL510 2847Q9G      | [12e9632d4b](https://bsd-hardware.info/?probe=12e9632d4b) | Jan 31, 2021 |
| Clevo         | W55xEU                      | [ecacada83f](https://bsd-hardware.info/?probe=ecacada83f) | Jan 29, 2021 |
| Clevo         | W55xEU                      | [e17285783e](https://bsd-hardware.info/?probe=e17285783e) | Jan 29, 2021 |
| Fujitsu       | LIFEBOOK E753               | [9a615ebaf8](https://bsd-hardware.info/?probe=9a615ebaf8) | Jan 24, 2021 |
| HP            | Laptop 17-ca1xxx            | [ecf07ad5fe](https://bsd-hardware.info/?probe=ecf07ad5fe) | Jan 24, 2021 |
| HP            | Laptop 17-ca1xxx            | [fb318623f3](https://bsd-hardware.info/?probe=fb318623f3) | Jan 23, 2021 |
| HP            | Laptop 17-ca1xxx            | [97a89d4eb0](https://bsd-hardware.info/?probe=97a89d4eb0) | Jan 23, 2021 |
| HP            | Laptop 17-ca1xxx            | [806c954739](https://bsd-hardware.info/?probe=806c954739) | Jan 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [5f469ceeb9](https://bsd-hardware.info/?probe=5f469ceeb9) | Jan 20, 2021 |
| TUXEDO        | Pulse 14 Gen1               | [5359b4dee9](https://bsd-hardware.info/?probe=5359b4dee9) | Jan 18, 2021 |
| Dell          | Inspiron 3542               | [3c41c474ad](https://bsd-hardware.info/?probe=3c41c474ad) | Jan 16, 2021 |
| Lenovo        | ThinkPad X201 3626HMG       | [a0b1fd0ca5](https://bsd-hardware.info/?probe=a0b1fd0ca5) | Jan 12, 2021 |
| Lenovo        | ThinkPad X201 3626HMG       | [f384858fd6](https://bsd-hardware.info/?probe=f384858fd6) | Jan 12, 2021 |
| Dell          | XPS 15 7590                 | [6cd195aa69](https://bsd-hardware.info/?probe=6cd195aa69) | Jan 05, 2021 |
| Dell          | XPS 15 7590                 | [50ca36db01](https://bsd-hardware.info/?probe=50ca36db01) | Jan 05, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [1ffaf5420c](https://bsd-hardware.info/?probe=1ffaf5420c) | Jan 03, 2021 |
| Apple         | MacBookPro10,2              | [1b0cc7506e](https://bsd-hardware.info/?probe=1b0cc7506e) | Jan 03, 2021 |
| Apple         | MacBookPro10,2              | [e43a26be8d](https://bsd-hardware.info/?probe=e43a26be8d) | Jan 01, 2021 |
| HP            | Laptop 14-dk0xxx            | [5cd8e23152](https://bsd-hardware.info/?probe=5cd8e23152) | Dec 26, 2020 |
| HP            | Laptop 14-dk0xxx            | [fdbd71db5e](https://bsd-hardware.info/?probe=fdbd71db5e) | Dec 26, 2020 |
| HP            | 655                         | [ae2de01d19](https://bsd-hardware.info/?probe=ae2de01d19) | Dec 26, 2020 |
| Lenovo        | ThinkPad X240 20AMS0RR00    | [0f9b8d2e3b](https://bsd-hardware.info/?probe=0f9b8d2e3b) | Dec 22, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [7e80ced15e](https://bsd-hardware.info/?probe=7e80ced15e) | Dec 16, 2020 |
| Lenovo        | ThinkPad X230 23244A9       | [d2e3890c19](https://bsd-hardware.info/?probe=d2e3890c19) | Dec 16, 2020 |
| Lenovo        | ThinkPad X230 23244A9       | [7aaf6835e2](https://bsd-hardware.info/?probe=7aaf6835e2) | Dec 16, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [1952513db8](https://bsd-hardware.info/?probe=1952513db8) | Dec 15, 2020 |
| Lenovo        | ThinkPad T420 4180AJ3       | [683eca8c23](https://bsd-hardware.info/?probe=683eca8c23) | Dec 11, 2020 |
| Lenovo        | ThinkPad X250 20CLS02000    | [cbd9f8a13c](https://bsd-hardware.info/?probe=cbd9f8a13c) | Dec 09, 2020 |
| Dell          | Latitude 2100               | [899ce6ffe4](https://bsd-hardware.info/?probe=899ce6ffe4) | Dec 08, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [16206c4970](https://bsd-hardware.info/?probe=16206c4970) | Dec 07, 2020 |
| Lenovo        | ThinkPad T460 20FMS78014    | [c811e29e6c](https://bsd-hardware.info/?probe=c811e29e6c) | Nov 30, 2020 |
| Dell          | Latitude E6440              | [f9278127a1](https://bsd-hardware.info/?probe=f9278127a1) | Nov 27, 2020 |
| Lenovo        | ThinkPad T420 4236N2G       | [1565d5d570](https://bsd-hardware.info/?probe=1565d5d570) | Nov 24, 2020 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [0738824c51](https://bsd-hardware.info/?probe=0738824c51) | Nov 22, 2020 |
| Lenovo        | ThinkPad T460 20FN003LGE    | [1b7b105e5c](https://bsd-hardware.info/?probe=1b7b105e5c) | Nov 08, 2020 |
| Lenovo        | V130-15IKB 81HN             | [d20a8be7d4](https://bsd-hardware.info/?probe=d20a8be7d4) | Nov 03, 2020 |
| Lenovo        | ThinkPad T520 4243FS9       | [242cd8a6e7](https://bsd-hardware.info/?probe=242cd8a6e7) | Nov 02, 2020 |
| Dell          | Precision M4800             | [8afb8e7443](https://bsd-hardware.info/?probe=8afb8e7443) | Oct 29, 2020 |
| Schenker      | N13xWU                      | [c23a22a72d](https://bsd-hardware.info/?probe=c23a22a72d) | Oct 29, 2020 |
| HUAWEI        | MACH-WX9                    | [2a1b806f39](https://bsd-hardware.info/?probe=2a1b806f39) | Oct 29, 2020 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [26c750117f](https://bsd-hardware.info/?probe=26c750117f) | Oct 28, 2020 |
| IBM           | ThinkPad X41 2525F8G        | [c58f946d2a](https://bsd-hardware.info/?probe=c58f946d2a) | Oct 22, 2020 |
| Lenovo        | ThinkPad Edge E531 68852... | [e6b45d36e5](https://bsd-hardware.info/?probe=e6b45d36e5) | Oct 20, 2020 |
| Lenovo        | ThinkPad X240 20AMS2QD0C    | [fdc7310ca7](https://bsd-hardware.info/?probe=fdc7310ca7) | Oct 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [857f9809b7](https://bsd-hardware.info/?probe=857f9809b7) | Oct 19, 2020 |
| Lenovo        | ThinkPad X270 20HNA004CD    | [79160b17c4](https://bsd-hardware.info/?probe=79160b17c4) | Oct 19, 2020 |
| Apple         | PowerBook6,7                | [7ac5f5530a](https://bsd-hardware.info/?probe=7ac5f5530a) | Oct 19, 2020 |
| Alienware     | m15                         | [8f8cf7d956](https://bsd-hardware.info/?probe=8f8cf7d956) | Oct 19, 2020 |
| Unknown       | Unknown                     | [fd77b4658f](https://bsd-hardware.info/?probe=fd77b4658f) | Oct 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [ee1f866775](https://bsd-hardware.info/?probe=ee1f866775) | Oct 13, 2020 |
| Lenovo        | ThinkPad X220 4291OQ6       | [ed0340e006](https://bsd-hardware.info/?probe=ed0340e006) | Oct 04, 2020 |
| ASUSTek       | N56VJ                       | [9fb23e0394](https://bsd-hardware.info/?probe=9fb23e0394) | Sep 22, 2020 |
| Lenovo        | ThinkPad T460 20FMS78014    | [53e545fcb9](https://bsd-hardware.info/?probe=53e545fcb9) | Sep 17, 2020 |
| Acer          | TravelMate 270              | [56a5581907](https://bsd-hardware.info/?probe=56a5581907) | Sep 17, 2020 |
| HP            | nx9010 (DN775T)             | [b7c0cb252f](https://bsd-hardware.info/?probe=b7c0cb252f) | Sep 16, 2020 |
| Lenovo        | ThinkPad X61 7673AG4        | [650e00a14a](https://bsd-hardware.info/?probe=650e00a14a) | Sep 14, 2020 |
| Panasonic     | CF-C1BD06EFG                | [3e876bada1](https://bsd-hardware.info/?probe=3e876bada1) | Sep 02, 2020 |
| Lenovo        | ThinkPad T460 20FMS78014    | [d78837860f](https://bsd-hardware.info/?probe=d78837860f) | Aug 23, 2020 |
| HKC           | NT11T                       | [1988c603c9](https://bsd-hardware.info/?probe=1988c603c9) | Aug 22, 2020 |
| Acer          | E1-510                      | [c65d08aa57](https://bsd-hardware.info/?probe=c65d08aa57) | Aug 20, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [3032cd9409](https://bsd-hardware.info/?probe=3032cd9409) | Aug 20, 2020 |
| HP            | Compaq Presario CQ71        | [b34e70d7d4](https://bsd-hardware.info/?probe=b34e70d7d4) | Aug 20, 2020 |
| Lenovo        | ThinkPad T450 20BUS08800    | [359cd8cf1b](https://bsd-hardware.info/?probe=359cd8cf1b) | Aug 11, 2020 |
| Sony          | VGN-SZ3VWP_X                | [ace534d784](https://bsd-hardware.info/?probe=ace534d784) | Aug 10, 2020 |
| HP            | ZBook 15 G4                 | [a8953b4964](https://bsd-hardware.info/?probe=a8953b4964) | Aug 03, 2020 |
| HP            | ZBook 15 G4                 | [a97053c5d4](https://bsd-hardware.info/?probe=a97053c5d4) | Aug 03, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [20f3e760eb](https://bsd-hardware.info/?probe=20f3e760eb) | Aug 03, 2020 |
| Lenovo        | ThinkPad T480 20L5000BMD    | [6259248178](https://bsd-hardware.info/?probe=6259248178) | Jul 31, 2020 |
| Dell          | Precision M4800             | [adbaced1b1](https://bsd-hardware.info/?probe=adbaced1b1) | Jul 30, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [ac13b0591f](https://bsd-hardware.info/?probe=ac13b0591f) | Jul 27, 2020 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [2e8c0ef401](https://bsd-hardware.info/?probe=2e8c0ef401) | Jul 21, 2020 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [ff2a0edd8a](https://bsd-hardware.info/?probe=ff2a0edd8a) | Jul 21, 2020 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [de1425a34c](https://bsd-hardware.info/?probe=de1425a34c) | Jul 19, 2020 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [5b8fe1f4f7](https://bsd-hardware.info/?probe=5b8fe1f4f7) | Jul 19, 2020 |
| Schenker      | N13xWU                      | [225afaa47f](https://bsd-hardware.info/?probe=225afaa47f) | Jul 15, 2020 |
| Dell          | Latitude E6440              | [a59bcf04fe](https://bsd-hardware.info/?probe=a59bcf04fe) | Jul 13, 2020 |
| Dell          | Inspiron 7773               | [0b335f5918](https://bsd-hardware.info/?probe=0b335f5918) | Jul 12, 2020 |
| Schenker      | SCHENKER_COMPACT15_17_SC... | [95434cbf80](https://bsd-hardware.info/?probe=95434cbf80) | Jul 07, 2020 |
| Lenovo        | G50-45 80E3                 | [56d1b97dc1](https://bsd-hardware.info/?probe=56d1b97dc1) | Jun 11, 2020 |
| Lenovo        | ThinkPad T450s 20BWS16X0... | [f83f765ab3](https://bsd-hardware.info/?probe=f83f765ab3) | Jun 06, 2020 |
| Schenker      | SCHENKER_COMPACT15_17_SC... | [96fcd8fc28](https://bsd-hardware.info/?probe=96fcd8fc28) | May 28, 2020 |
| Fujitsu       | LIFEBOOK A357               | [b02640458b](https://bsd-hardware.info/?probe=b02640458b) | May 26, 2020 |
| Lenovo        | ThinkPad T410 2537H21       | [0087b62853](https://bsd-hardware.info/?probe=0087b62853) | May 25, 2020 |
| HP            | EliteBook 8560w             | [c240e3a1ea](https://bsd-hardware.info/?probe=c240e3a1ea) | May 25, 2020 |
| TUXEDO        | N13xWU                      | [9649f2d700](https://bsd-hardware.info/?probe=9649f2d700) | May 25, 2020 |
| TUXEDO        | N13xWU                      | [7230dca5a8](https://bsd-hardware.info/?probe=7230dca5a8) | May 25, 2020 |
| Sony          | VPCM12M1E                   | [1e5d0a4d7a](https://bsd-hardware.info/?probe=1e5d0a4d7a) | May 25, 2020 |
| Lenovo        | ThinkPad T410s 291245G      | [6394ae37a8](https://bsd-hardware.info/?probe=6394ae37a8) | May 25, 2020 |
| Lenovo        | ThinkPad T410s 291245G      | [b453d7ac18](https://bsd-hardware.info/?probe=b453d7ac18) | May 25, 2020 |
| Lenovo        | ThinkPad X260 20F5S1H800    | [85567202a8](https://bsd-hardware.info/?probe=85567202a8) | May 23, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| helloSystem 0.8.1    | 17        | 4.62%   |
| helloSystem 0.4.0    | 14        | 3.8%    |
| helloSystem 0.7.0    | 13        | 3.53%   |
| OpenBSD 6.8          | 12        | 3.26%   |
| helloSystem 0.5.0    | 12        | 3.26%   |
| helloSystem 0.8.0    | 11        | 2.99%   |
| FreeBSD 12.2         | 10        | 2.72%   |
| OpenBSD 7.0          | 8         | 2.17%   |
| FreeBSD 14.0-CURRENT | 7         | 1.9%    |
| FreeBSD 13.2         | 7         | 1.9%    |
| FreeBSD 13.0-p4      | 7         | 1.9%    |
| OpenBSD 7.2          | 6         | 1.63%   |
| OpenBSD 6.9          | 6         | 1.63%   |
| helloSystem 0.6.0    | 6         | 1.63%   |
| GhostBSD 22.01.12    | 6         | 1.63%   |
| FreeBSD 12.1-p10     | 6         | 1.63%   |
| OPNsense 23.1.11     | 5         | 1.36%   |
| OPNsense 21.7.6      | 5         | 1.36%   |
| OpenBSD 6.7          | 5         | 1.36%   |
| NomadBSD 5806f915    | 5         | 1.36%   |
| GhostBSD 21.08.27    | 5         | 1.36%   |
| FreeBSD 13.0-CURRENT | 5         | 1.36%   |
| FreeBSD 13.0         | 5         | 1.36%   |
| FreeBSD 12.2-p2      | 5         | 1.36%   |
| FreeBSD 12.1-STABLE  | 5         | 1.36%   |
| OPNsense 21.1.2      | 4         | 1.09%   |
| NomadBSD 1.4         | 4         | 1.09%   |
| GhostBSD 20.04.02    | 4         | 1.09%   |
| FreeBSD 14.0         | 4         | 1.09%   |
| FreeBSD 13.1-p5      | 4         | 1.09%   |
| FreeBSD 12.1-p5      | 4         | 1.09%   |
| FreeBSD 12.1         | 4         | 1.09%   |
| OPNsense 23.7.6      | 3         | 0.82%   |
| OPNsense 22.1.6      | 3         | 0.82%   |
| NomadBSD 20231013    | 3         | 0.82%   |
| NomadBSD 1.4-RC1     | 3         | 0.82%   |
| GhostBSD 23.10.1     | 3         | 0.82%   |
| FreeBSD 13.1-p2      | 3         | 0.82%   |
| FreeBSD 13.1         | 3         | 0.82%   |
| FreeBSD 12.2-p3      | 3         | 0.82%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 102       | 31.78%  |
| helloSystem | 74        | 23.05%  |
| OPNsense    | 65        | 20.25%  |
| OpenBSD     | 35        | 10.9%   |
| GhostBSD    | 23        | 7.17%   |
| NomadBSD    | 17        | 5.3%    |
| NetBSD      | 2         | 0.62%   |
| MidnightBSD | 1         | 0.31%   |
| HardenedBSD | 1         | 0.31%   |
| FuryBSD     | 1         | 0.31%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| amd64  | 302       | 96.79%  |
| i386   | 9         | 2.88%   |
| macppc | 1         | 0.32%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Console       | 85        | 25.99%  |
| helloDesktop  | 79        | 24.16%  |
| MATE          | 30        | 9.17%   |
| XFCE          | 28        | 8.56%   |
| fvwm          | 25        | 7.65%   |
| KDE5          | 23        | 7.03%   |
| GNOME         | 16        | 4.89%   |
| Openbox       | 14        | 4.28%   |
| TWM           | 10        | 3.06%   |
| i3            | 4         | 1.22%   |
| AwesomeWM     | 4         | 1.22%   |
| Cinnamon      | 2         | 0.61%   |
| Picom         | 1         | 0.31%   |
| LXQt          | 1         | 0.31%   |
| LXDE          | 1         | 0.31%   |
| JWM           | 1         | 0.31%   |
| iwm           | 1         | 0.31%   |
| IceWM         | 1         | 0.31%   |
| Enlightenment | 1         | 0.31%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 224       | 71.11%  |
| Console | 89        | 28.25%  |
| Wayland | 2         | 0.63%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 137       | 41.77%  |
| SLiM    | 103       | 31.4%   |
| LightDM | 33        | 10.06%  |
| SDDM    | 29        | 8.84%   |
| XDM     | 12        | 3.66%   |
| GDM     | 11        | 3.35%   |
| Ly      | 3         | 0.91%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Notebooks | Percent |
|------------------|-----------|---------|
| Unknown          | 134       | 40.73%  |
| en_US            | 64        | 19.45%  |
| de_DE            | 56        | 17.02%  |
| C                | 54        | 16.41%  |
| de               | 7         | 2.13%   |
| en_GB            | 5         | 1.52%   |
| fr_FR            | 2         | 0.61%   |
| de_DE.ISO8859-1  | 2         | 0.61%   |
| pl_PL            | 1         | 0.3%    |
| en_IE            | 1         | 0.3%    |
| en_CA            | 1         | 0.3%    |
| en               | 1         | 0.3%    |
| de_DE.ISO8859-15 | 1         | 0.3%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 257       | 81.07%  |
| BIOS | 60        | 18.93%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 168       | 52.34%  |
| Ufs    | 93        | 28.97%  |
| Ffs    | 35        | 10.9%   |
| Cd9660 | 25        | 7.79%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 288       | 91.14%  |
| MBR     | 25        | 7.91%   |
| Unknown | 3         | 0.95%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 111       | 35.58%  |
| Dell                | 32        | 10.26%  |
| Deciso              | 25        | 8.01%   |
| Hewlett-Packard     | 20        | 6.41%   |
| Apple               | 18        | 5.77%   |
| Acer                | 14        | 4.49%   |
| Unknown             | 14        | 4.49%   |
| Fujitsu             | 12        | 3.85%   |
| TUXEDO              | 10        | 3.21%   |
| ASUSTek Computer    | 10        | 3.21%   |
| Notebook            | 4         | 1.28%   |
| Sony                | 3         | 0.96%   |
| Shuttle             | 3         | 0.96%   |
| MSI                 | 3         | 0.96%   |
| Toshiba             | 2         | 0.64%   |
| Tactus              | 2         | 0.64%   |
| Schenker            | 2         | 0.64%   |
| Samsung Electronics | 2         | 0.64%   |
| Panasonic           | 2         | 0.64%   |
| Medion              | 2         | 0.64%   |
| IBM                 | 2         | 0.64%   |
| Gigabyte Technology | 2         | 0.64%   |
| Wortmann AG         | 1         | 0.32%   |
| Packard Bell        | 1         | 0.32%   |
| MiTAC               | 1         | 0.32%   |
| Intel               | 1         | 0.32%   |
| Insyde              | 1         | 0.32%   |
| IGEL Technology     | 1         | 0.32%   |
| HUAWEI              | 1         | 0.32%   |
| HKC                 | 1         | 0.32%   |
| Hampoo              | 1         | 0.32%   |
| GPD                 | 1         | 0.32%   |
| Google              | 1         | 0.32%   |
| CSL-Computer        | 1         | 0.32%   |
| Clevo               | 1         | 0.32%   |
| BESSTAR Tech        | 1         | 0.32%   |
| AMI                 | 1         | 0.32%   |
| Alienware           | 1         | 0.32%   |
| AEWIN               | 1         | 0.32%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 15        | 4.81%   |
| Deciso NetBoard-A10                        | 13        | 4.17%   |
| Deciso Netboard A20                        | 6         | 1.92%   |
| Apple MacBookAir5,1                        | 4         | 1.28%   |
| Dell Latitude E6540                        | 3         | 0.96%   |
| Deciso DEC2700 - OPNsense Appliance        | 3         | 0.96%   |
| TUXEDO Pulse 15 Gen1                       | 2         | 0.64%   |
| TUXEDO Pulse 14 Gen1                       | 2         | 0.64%   |
| Shuttle DS437                              | 2         | 0.64%   |
| Lenovo ThinkPad X260 20F5S1H800            | 2         | 0.64%   |
| Lenovo ThinkPad X230 232578G               | 2         | 0.64%   |
| Lenovo ThinkPad T410s 291245G              | 2         | 0.64%   |
| Lenovo ThinkPad E490 20N8CTO1WW            | 2         | 0.64%   |
| HP ZBook 15 G4                             | 2         | 0.64%   |
| Gigabyte GB-BSi5A-6200                     | 2         | 0.64%   |
| Dell Latitude E6500                        | 2         | 0.64%   |
| Dell Latitude E6330                        | 2         | 0.64%   |
| Dell Latitude 5591                         | 2         | 0.64%   |
| Deciso NetBoard-A20                        | 2         | 0.64%   |
| ASUS TUF Gaming FX505DT_FX505DT            | 2         | 0.64%   |
| Apple MacBookAir7,2                        | 2         | 0.64%   |
| Apple MacBook5,1                           | 2         | 0.64%   |
| Wortmann AG TERRA_MOBILE_1541              | 1         | 0.32%   |
| TUXEDO Pulse 15 Gen2                       | 1         | 0.32%   |
| TUXEDO N13xWU                              | 1         | 0.32%   |
| TUXEDO InfinityBook S 15 Gen6              | 1         | 0.32%   |
| TUXEDO InfinityBook Pro 14 Gen6            | 1         | 0.32%   |
| TUXEDO Aura 15 Gen1                        | 1         | 0.32%   |
| Toshiba Satellite Pro L40                  | 1         | 0.32%   |
| Toshiba Satellite C70-B                    | 1         | 0.32%   |
| Tactus GeoFlex 110                         | 1         | 0.32%   |
| Tactus GeoBook 140                         | 1         | 0.32%   |
| Sony VPCM12M1E                             | 1         | 0.32%   |
| Sony VPCEJ1E1E                             | 1         | 0.32%   |
| Sony VGN-SZ3VWP_X                          | 1         | 0.32%   |
| Shuttle DS437T                             | 1         | 0.32%   |
| Schenker SCHENKER_COMPACT15_17_SCO15_17M19 | 1         | 0.32%   |
| Schenker N13xWU                            | 1         | 0.32%   |
| Samsung RC530/RC730                        | 1         | 0.32%   |
| Samsung NC210/NC110                        | 1         | 0.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 91        | 29.17%  |
| Dell Latitude          | 22        | 7.05%   |
| Unknown                | 15        | 4.81%   |
| Deciso NetBoard-A10    | 13        | 4.17%   |
| Fujitsu LIFEBOOK       | 11        | 3.53%   |
| Lenovo IdeaPad         | 6         | 1.92%   |
| HP EliteBook           | 6         | 1.92%   |
| Deciso Netboard        | 6         | 1.92%   |
| TUXEDO Pulse           | 5         | 1.6%    |
| Acer Aspire            | 5         | 1.6%    |
| Dell XPS               | 4         | 1.28%   |
| Dell Inspiron          | 4         | 1.28%   |
| Apple MacBookAir5      | 4         | 1.28%   |
| HP Laptop              | 3         | 0.96%   |
| Deciso DEC2700         | 3         | 0.96%   |
| Acer TravelMate        | 3         | 0.96%   |
| TUXEDO InfinityBook    | 2         | 0.64%   |
| Toshiba Satellite      | 2         | 0.64%   |
| Shuttle DS437          | 2         | 0.64%   |
| Lenovo ThinkBook       | 2         | 0.64%   |
| Lenovo Legion          | 2         | 0.64%   |
| IBM ThinkPad           | 2         | 0.64%   |
| HP ZBook               | 2         | 0.64%   |
| HP ProBook             | 2         | 0.64%   |
| Gigabyte GB-BSi5A-6200 | 2         | 0.64%   |
| Dell Precision         | 2         | 0.64%   |
| Deciso NetBoard-A20    | 2         | 0.64%   |
| ASUS TUF               | 2         | 0.64%   |
| Apple MacBookAir7      | 2         | 0.64%   |
| Apple MacBook5         | 2         | 0.64%   |
| Acer Swift             | 2         | 0.64%   |
| Acer Extensa           | 2         | 0.64%   |
| Wortmann AG TERRA      | 1         | 0.32%   |
| TUXEDO N13xWU          | 1         | 0.32%   |
| TUXEDO Aura            | 1         | 0.32%   |
| Tactus GeoFlex         | 1         | 0.32%   |
| Tactus GeoBook         | 1         | 0.32%   |
| Sony VPCM12M1E         | 1         | 0.32%   |
| Sony VPCEJ1E1E         | 1         | 0.32%   |
| Sony VGN-SZ3VWP        | 1         | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 33        | 10.58%  |
| 2020    | 28        | 8.97%   |
| 2019    | 25        | 8.01%   |
| 2018    | 25        | 8.01%   |
| 2022    | 24        | 7.69%   |
| 2011    | 23        | 7.37%   |
| 2017    | 21        | 6.73%   |
| 2016    | 20        | 6.41%   |
| 2013    | 19        | 6.09%   |
| 2012    | 17        | 5.45%   |
| 2014    | 16        | 5.13%   |
| 2010    | 16        | 5.13%   |
| 2015    | 13        | 4.17%   |
| 2008    | 11        | 3.53%   |
| 2009    | 6         | 1.92%   |
| 2007    | 4         | 1.28%   |
| 2023    | 3         | 0.96%   |
| Unknown | 3         | 0.96%   |
| 2003    | 2         | 0.64%   |
| 2006    | 1         | 0.32%   |
| 2005    | 1         | 0.32%   |
| 2002    | 1         | 0.32%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 312       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 310       | 99.36%  |
| Yes  | 2         | 0.64%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 116       | 36.94%  |
| 16.01-24.0  | 84        | 26.75%  |
| 4.01-8.0    | 60        | 19.11%  |
| 32.01-64.0  | 22        | 7.01%   |
| 2.01-3.0    | 14        | 4.46%   |
| 3.01-4.0    | 5         | 1.59%   |
| 64.01-256.0 | 3         | 0.96%   |
| 1.01-2.0    | 3         | 0.96%   |
| 0.51-1.0    | 3         | 0.96%   |
| 0.01-0.5    | 2         | 0.64%   |
| 24.01-32.0  | 1         | 0.32%   |
| 0           | 1         | 0.32%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 181       | 56.74%  |
| 0.51-1.0   | 90        | 28.21%  |
| 1.01-2.0   | 28        | 8.78%   |
| 4.01-8.0   | 6         | 1.88%   |
| 2.01-3.0   | 6         | 1.88%   |
| Unknown    | 4         | 1.25%   |
| 0          | 2         | 0.63%   |
| 24.01-32.0 | 1         | 0.31%   |
| 16.01-24.0 | 1         | 0.31%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 228       | 71.47%  |
| 2      | 63        | 19.75%  |
| 0      | 19        | 5.96%   |
| 3      | 9         | 2.82%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 229       | 72.93%  |
| Yes       | 85        | 27.07%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 280       | 89.74%  |
| No        | 32        | 10.26%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 263       | 84.03%  |
| No        | 50        | 15.97%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 180       | 57.32%  |
| No        | 134       | 42.68%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Germany | 312       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Berlin            | 31        | 9.34%   |
| Frankfurt am Main | 13        | 3.92%   |
| Munich            | 12        | 3.61%   |
| Hamburg           | 9         | 2.71%   |
| Nuremberg         | 6         | 1.81%   |
| Bedburg           | 6         | 1.81%   |
| Stuttgart         | 5         | 1.51%   |
| Leipzig           | 5         | 1.51%   |
| Halle             | 5         | 1.51%   |
| Aachen            | 5         | 1.51%   |
| Lübeck           | 4         | 1.2%    |
| Essen             | 4         | 1.2%    |
| Cologne           | 4         | 1.2%    |
| Wuppertal         | 3         | 0.9%    |
| Wernigerode       | 3         | 0.9%    |
| Neuss             | 3         | 0.9%    |
| Münster          | 3         | 0.9%    |
| Markt Indersdorf  | 3         | 0.9%    |
| Ludwigsburg       | 3         | 0.9%    |
| Giessen           | 3         | 0.9%    |
| Darmstadt         | 3         | 0.9%    |
| Bonn              | 3         | 0.9%    |
| Blomberg          | 3         | 0.9%    |
| Bielefeld         | 3         | 0.9%    |
| Zwingenberg       | 2         | 0.6%    |
| Wissen            | 2         | 0.6%    |
| Reutlingen        | 2         | 0.6%    |
| Regensburg        | 2         | 0.6%    |
| Potsdam           | 2         | 0.6%    |
| Pleidelsheim      | 2         | 0.6%    |
| Neuengors         | 2         | 0.6%    |
| Mainz             | 2         | 0.6%    |
| Lüneburg         | 2         | 0.6%    |
| Kornwestheim      | 2         | 0.6%    |
| Karlsruhe         | 2         | 0.6%    |
| Habichtswald      | 2         | 0.6%    |
| Gummersbach       | 2         | 0.6%    |
| Gifhorn           | 2         | 0.6%    |
| Erlangen          | 2         | 0.6%    |
| Dresden           | 2         | 0.6%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 74        | 94     | 21.45%  |
| Transcend           | 36        | 43     | 10.43%  |
| WDC                 | 25        | 29     | 7.25%   |
| SanDisk             | 22        | 24     | 6.38%   |
| Crucial             | 22        | 28     | 6.38%   |
| Seagate             | 19        | 21     | 5.51%   |
| Toshiba             | 15        | 35     | 4.35%   |
| Kingston            | 15        | 18     | 4.35%   |
| NVMe                | 14        | 25     | 4.06%   |
| Intel               | 13        | 13     | 3.77%   |
| Apple               | 11        | 11     | 3.19%   |
| Intenso             | 10        | 11     | 2.9%    |
| Micron Technology   | 9         | 9      | 2.61%   |
| Hitachi             | 8         | 11     | 2.32%   |
| SK hynix            | 6         | 7      | 1.74%   |
| HGST                | 5         | 10     | 1.45%   |
| SPCC                | 4         | 5      | 1.16%   |
| OCZ                 | 4         | 7      | 1.16%   |
| KIOXIA              | 4         | 4      | 1.16%   |
| Hoodisk             | 4         | 4      | 1.16%   |
| Fujitsu             | 4         | 4      | 1.16%   |
| A-DATA Technology   | 3         | 4      | 0.87%   |
| LITEON              | 2         | 2      | 0.58%   |
| Kston               | 2         | 2      | 0.58%   |
| Verbatim            | 1         | 3      | 0.29%   |
| PNY                 | 1         | 1      | 0.29%   |
| Phison              | 1         | 1      | 0.29%   |
| Netac               | 1         | 1      | 0.29%   |
| MyDigitalSSD        | 1         | 1      | 0.29%   |
| Mushkin             | 1         | 1      | 0.29%   |
| Lenovo              | 1         | 1      | 0.29%   |
| Gigabyte Technology | 1         | 1      | 0.29%   |
| FORESEE             | 1         | 1      | 0.29%   |
| Dogfish             | 1         | 1      | 0.29%   |
| Corsair             | 1         | 1      | 0.29%   |
| China               | 1         | 1      | 0.29%   |
| BIWIN               | 1         | 1      | 0.29%   |
| 2-Power             | 1         | 1      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Transcend TS256GMTE652T2 256GB       | 7         | 1.96%   |
| Transcend TS256GMTS952T2 256GB       | 6         | 1.68%   |
| Transcend TS256GMTE710T 256GB        | 6         | 1.68%   |
| Transcend TS128GMTE110S 128GB        | 5         | 1.4%    |
| Samsung SSD 860 EVO 500GB            | 4         | 1.12%   |
| Samsung SSD 840 EVO 250GB            | 4         | 1.12%   |
| Hoodisk SSD 128GB                    | 4         | 1.12%   |
| Apple SSD TS128E 121GB               | 4         | 1.12%   |
| Transcend TS240GMTS420S 240GB        | 3         | 0.84%   |
| SanDisk SSD PLUS 120GB               | 3         | 0.84%   |
| Samsung SSD 970 EVO Plus 1TB         | 3         | 0.84%   |
| Samsung SSD 850 EVO 500GB            | 3         | 0.84%   |
| Samsung SSD 850 EVO 250GB            | 3         | 0.84%   |
| NVMe Samsung SSD 980 1TB             | 3         | 0.84%   |
| Crucial CT1000MX500SSD1 1TB          | 3         | 0.84%   |
| Transcend TS64GSSD370S 64GB          | 2         | 0.56%   |
| Transcend TS512GMTS952T2 512GB       | 2         | 0.56%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB | 2         | 0.56%   |
| SPCC Solid State Disk 1TB            | 2         | 0.56%   |
| Seagate ST500LT012-1DG142 500GB      | 2         | 0.56%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 0.56%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 0.56%   |
| SanDisk SDSSDP064G 64GB              | 2         | 0.56%   |
| Samsung SSD 970 EVO Plus 250GB       | 2         | 0.56%   |
| Samsung SSD 970 EVO 500GB            | 2         | 0.56%   |
| Samsung SSD 870 EVO 250GB            | 2         | 0.56%   |
| Samsung SSD 840 PRO Series 256GB     | 2         | 0.56%   |
| Samsung SSD 840 EVO 120GB            | 2         | 0.56%   |
| Samsung PM9A1 NVMe 512GB             | 2         | 0.56%   |
| Samsung MZYLF128HCHP-000L2 128GB     | 2         | 0.56%   |
| Samsung MZVLB512HAJQ-000L7 512GB     | 2         | 0.56%   |
| Samsung MZALQ512HALU-000L2 512GB     | 2         | 0.56%   |
| Samsung MZ7LN256HCHP-000L7 256GB     | 2         | 0.56%   |
| NVMe WDC PC SN730 SDB 512GB          | 2         | 0.56%   |
| NVMe SAMSUNG MZVLW256 256GB          | 2         | 0.56%   |
| Micron 2200V_MTFDHBA512TCK 512GB     | 2         | 0.56%   |
| LITEON LCH-128V2S 128GB              | 2         | 0.56%   |
| Kingston SV300S37A240G 240GB         | 2         | 0.56%   |
| Kingston SA400S37480G 480GB          | 2         | 0.56%   |
| Kingston SA400S37120G 120GB          | 2         | 0.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 21     | 26.76%  |
| WDC                 | 16        | 19     | 22.54%  |
| NVMe                | 10        | 20     | 14.08%  |
| Hitachi             | 8         | 11     | 11.27%  |
| Toshiba             | 6         | 7      | 8.45%   |
| HGST                | 5         | 10     | 7.04%   |
| Fujitsu             | 4         | 4      | 5.63%   |
| Samsung Electronics | 2         | 2      | 2.82%   |
| Apple               | 1         | 1      | 1.41%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 48        | 57     | 24.24%  |
| SanDisk             | 22        | 24     | 11.11%  |
| Crucial             | 19        | 25     | 9.6%    |
| Transcend           | 18        | 22     | 9.09%   |
| Kingston            | 12        | 15     | 6.06%   |
| Intel               | 12        | 12     | 6.06%   |
| Intenso             | 10        | 11     | 5.05%   |
| Apple               | 10        | 10     | 5.05%   |
| Toshiba             | 5         | 11     | 2.53%   |
| WDC                 | 4         | 4      | 2.02%   |
| SK hynix            | 4         | 5      | 2.02%   |
| OCZ                 | 4         | 7      | 2.02%   |
| Micron Technology   | 4         | 4      | 2.02%   |
| Hoodisk             | 4         | 4      | 2.02%   |
| SPCC                | 3         | 3      | 1.52%   |
| NVMe                | 3         | 3      | 1.52%   |
| LITEON              | 2         | 2      | 1.01%   |
| Kston               | 2         | 2      | 1.01%   |
| A-DATA Technology   | 2         | 2      | 1.01%   |
| Verbatim            | 1         | 3      | 0.51%   |
| PNY                 | 1         | 1      | 0.51%   |
| Netac               | 1         | 1      | 0.51%   |
| MyDigitalSSD        | 1         | 1      | 0.51%   |
| Mushkin             | 1         | 1      | 0.51%   |
| FORESEE             | 1         | 1      | 0.51%   |
| Dogfish             | 1         | 1      | 0.51%   |
| Corsair             | 1         | 1      | 0.51%   |
| China               | 1         | 1      | 0.51%   |
| 2-Power             | 1         | 1      | 0.51%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 179       | 235    | 55.76%  |
| NVMe | 75        | 107    | 23.36%  |
| HDD  | 67        | 95     | 20.87%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 233       | 330    | 75.65%  |
| NVMe | 75        | 107    | 24.35%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 199       | 259    | 79.6%   |
| 0.51-1.0   | 34        | 44     | 13.6%   |
| 1.01-2.0   | 15        | 25     | 6%      |
| 3.01-4.0   | 1         | 1      | 0.4%    |
| 4.01-10.0  | 1         | 1      | 0.4%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 118       | 36.2%   |
| 1-20           | 78        | 23.93%  |
| 251-500        | 62        | 19.02%  |
| 51-100         | 26        | 7.98%   |
| 501-1000       | 20        | 6.13%   |
| 21-50          | 13        | 3.99%   |
| 1001-2000      | 5         | 1.53%   |
| Unknown        | 3         | 0.92%   |
| More than 3000 | 1         | 0.31%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 265       | 81.04%  |
| 21-50          | 26        | 7.95%   |
| 51-100         | 14        | 4.28%   |
| 101-250        | 13        | 3.98%   |
| 251-500        | 4         | 1.22%   |
| Unknown        | 3         | 0.92%   |
| More than 3000 | 1         | 0.31%   |
| 501-1000       | 1         | 0.31%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Toshiba THNSNK256GVN8 M.2 2280 256GB         | 2         | 8      | 6.45%   |
| Hitachi HTS545032B9A300 320GB                | 2         | 4      | 6.45%   |
| Hitachi HTS543225L9A300 250GB                | 2         | 2      | 6.45%   |
| HGST HTS541010A9E680 1TB                     | 2         | 3      | 6.45%   |
| WDC WD3200BEVT-22ZCT0 320GB                  | 1         | 1      | 3.23%   |
| WDC WD1600BEVS-07RST0 160GB                  | 1         | 1      | 3.23%   |
| WDC WD10SPZX-21Z10T0 1TB                     | 1         | 1      | 3.23%   |
| Toshiba MK2018GAP 20GB                       | 1         | 1      | 3.23%   |
| SK hynix HFS256G39MND-2300A 256GB            | 1         | 1      | 3.23%   |
| Seagate ST9500420AS 500GB                    | 1         | 1      | 3.23%   |
| Seagate ST9320325AS 320GB                    | 1         | 1      | 3.23%   |
| Seagate ST9250410AS 250GB                    | 1         | 1      | 3.23%   |
| Seagate ST500LT012-1DG142 500GB              | 1         | 1      | 3.23%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 1      | 3.23%   |
| SanDisk SSD PLUS 480GB                       | 1         | 1      | 3.23%   |
| SanDisk SSD P4 64GB                          | 1         | 1      | 3.23%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 1      | 3.23%   |
| Micron Technology 1100 SATA 256GB            | 1         | 1      | 3.23%   |
| Kingston SV300S37A240G 240GB                 | 1         | 1      | 3.23%   |
| Kingston SNV425S264GB                        | 1         | 1      | 3.23%   |
| Intel SSDSC2KF256H6L 256GB                   | 1         | 1      | 3.23%   |
| Intel SSDSC2BF180A4L 180GB                   | 1         | 1      | 3.23%   |
| Hitachi HTS548040M9AT00 37GB                 | 1         | 1      | 3.23%   |
| Hitachi HTS545025B9SA02 250GB                | 1         | 2      | 3.23%   |
| Fujitsu MHW2160BH 160GB                      | 1         | 1      | 3.23%   |
| Crucial CT1000P1SSD8 1TB                     | 1         | 1      | 3.23%   |
| Corsair Force GT 120GB                       | 1         | 1      | 3.23%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 6         | 9      | 19.35%  |
| Seagate             | 5         | 5      | 16.13%  |
| WDC                 | 3         | 3      | 9.68%   |
| Toshiba             | 3         | 9      | 9.68%   |
| SanDisk             | 2         | 2      | 6.45%   |
| Kingston            | 2         | 2      | 6.45%   |
| Intel               | 2         | 2      | 6.45%   |
| HGST                | 2         | 3      | 6.45%   |
| SK hynix            | 1         | 1      | 3.23%   |
| Samsung Electronics | 1         | 1      | 3.23%   |
| Micron Technology   | 1         | 1      | 3.23%   |
| Fujitsu             | 1         | 1      | 3.23%   |
| Crucial             | 1         | 1      | 3.23%   |
| Corsair             | 1         | 1      | 3.23%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 6         | 9      | 33.33%  |
| Seagate | 5         | 5      | 27.78%  |
| WDC     | 3         | 3      | 16.67%  |
| HGST    | 2         | 3      | 11.11%  |
| Toshiba | 1         | 1      | 5.56%   |
| Fujitsu | 1         | 1      | 5.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 18        | 22     | 58.06%  |
| SSD  | 12        | 18     | 38.71%  |
| NVMe | 1         | 1      | 3.23%   |

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
| Works    | 262       | 371    | 85.06%  |
| Malfunc  | 31        | 41     | 10.06%  |
| Detected | 15        | 25     | 4.87%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 217       | 61.65%  |
| Samsung Electronics              | 43        | 12.22%  |
| AMD                              | 24        | 6.82%   |
| Transcend                        | 17        | 4.83%   |
| SanDisk                          | 11        | 3.13%   |
| Toshiba                          | 6         | 1.7%    |
| Micron Technology                | 6         | 1.7%    |
| Phison Electronics               | 4         | 1.14%   |
| Nvidia                           | 4         | 1.14%   |
| Kingston Technology Company      | 4         | 1.14%   |
| SK hynix                         | 3         | 0.85%   |
| Micron/Crucial Technology        | 3         | 0.85%   |
| KIOXIA                           | 3         | 0.85%   |
| Silicon Motion                   | 2         | 0.57%   |
| ADATA Technology                 | 2         | 0.57%   |
| ULi Electronics                  | 1         | 0.28%   |
| Silicon Integrated Systems [SiS] | 1         | 0.28%   |
| Lenovo                           | 1         | 0.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 30        | 8.04%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 25        | 6.7%    |
| AMD FCH SATA Controller [AHCI mode]                                                    | 24        | 6.43%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 23        | 6.17%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 21        | 5.63%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 18        | 4.83%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 14        | 3.75%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 13        | 3.49%   |
| Transcend NVMe PCIe SSD 110S/112S/120S/MTE300S/MTE400S/MTE652T2 (DRAM-less)            | 11        | 2.95%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 10        | 2.68%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 9         | 2.41%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 9         | 2.41%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 9         | 2.41%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 8         | 2.14%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 7         | 1.88%   |
| Transcend NVMe PCIe SSD 240S/MTE710T                                                   | 6         | 1.61%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 6         | 1.61%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                   | 5         | 1.34%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 5         | 1.34%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                            | 5         | 1.34%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 5         | 1.34%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                             | 4         | 1.07%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 4         | 1.07%   |
| Toshiba XG5 NVMe SSD Controller                                                        | 3         | 0.8%    |
| Phison E12 NVMe Controller                                                             | 3         | 0.8%    |
| Nvidia MCP79 AHCI Controller                                                           | 3         | 0.8%    |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                            | 3         | 0.8%    |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                             | 3         | 0.8%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 3         | 0.8%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 3         | 0.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 3         | 0.8%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 3         | 0.8%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 3         | 0.8%    |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 3         | 0.8%    |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 3         | 0.8%    |
| Toshiba XG6 NVMe SSD Controller                                                        | 2         | 0.54%   |
| Micron 2200S NVMe SSD [Cassandra]                                                      | 2         | 0.54%   |
| Kingston Company NV2 NVMe SSD SM2267XT                                                 | 2         | 0.54%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 2         | 0.54%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 2         | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 228       | 63.87%  |
| NVMe | 92        | 25.77%  |
| IDE  | 30        | 8.4%    |
| RAID | 7         | 1.96%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 259       | 83.01%  |
| AMD     | 52        | 16.67%  |
| PowerPC | 1         | 0.32%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| AMD Ryzen Embedded V1500B               | 17        | 5.43%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 10        | 3.19%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 10        | 3.19%   |
| Intel CPU Version                       | 7         | 2.24%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 7         | 2.24%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 7         | 2.24%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 7         | 2.24%   |
| AMD EPYC 3201 8-Core Processor          | 7         | 2.24%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 6         | 1.92%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 6         | 1.92%   |
| Intel Core i5-3317U CPU @ 1.70GHz       | 5         | 1.6%    |
| Intel Core i3-4005U CPU @ 1.70GHz       | 5         | 1.6%    |
| AMD Ryzen 7 4800H with Radeon Graphics  | 5         | 1.6%    |
| Intel Core i5-6200U CPU @ 2.30GHz       | 4         | 1.28%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 4         | 1.28%   |
| Intel Core i5-4250U CPU @ 1.30GHz       | 4         | 1.28%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 4         | 1.28%   |
| Intel Core i5 CPU M 560 @ 2.67GHz       | 4         | 1.28%   |
| Intel Core 2 Duo                        | 4         | 1.28%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 3         | 0.96%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 3         | 0.96%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 3         | 0.96%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 3         | 0.96%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 3         | 0.96%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 3         | 0.96%   |
| Intel Celeron CPU 1037U @ 1.80GHz       | 3         | 0.96%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 3         | 0.96%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 3         | 0.96%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz    | 2         | 0.64%   |
| Intel Pentium 3558U @ 1.70GHz           | 2         | 0.64%   |
| Intel Genuine CPU                       | 2         | 0.64%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 2         | 0.64%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 2         | 0.64%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 2         | 0.64%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz      | 2         | 0.64%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz      | 2         | 0.64%   |
| Intel Core i7-4610M CPU @ 3.00GHz       | 2         | 0.64%   |
| Intel Core i7-2860QM CPU @ 2.50GHz      | 2         | 0.64%   |
| Intel Core i7-2677M CPU @ 1.80GHz       | 2         | 0.64%   |
| Intel Core i5-8400H CPU @ 2.50GHz       | 2         | 0.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 104       | 33.33%  |
| Intel Core i7        | 60        | 19.23%  |
| Other                | 23        | 7.37%   |
| Intel Core 2 Duo     | 17        | 5.45%   |
| AMD Ryzen Embedded   | 17        | 5.45%   |
| Intel Core i3        | 14        | 4.49%   |
| Intel Celeron        | 14        | 4.49%   |
| AMD Ryzen 7          | 12        | 3.85%   |
| AMD EPYC             | 8         | 2.56%   |
| Intel Pentium        | 7         | 2.24%   |
| AMD Ryzen 5          | 7         | 2.24%   |
| Intel Atom           | 5         | 1.6%    |
| Intel Xeon           | 3         | 0.96%   |
| Intel Pentium M      | 3         | 0.96%   |
| Intel Genuine        | 3         | 0.96%   |
| Intel Pentium Silver | 2         | 0.64%   |
| AMD Ryzen 7 PRO      | 2         | 0.64%   |
| Intel Pentium Dual   | 1         | 0.32%   |
| Intel Pentium 4      | 1         | 0.32%   |
| Intel Core m3        | 1         | 0.32%   |
| Intel Core M         | 1         | 0.32%   |
| Intel Core 2 Solo    | 1         | 0.32%   |
| Intel Core 2         | 1         | 0.32%   |
| Intel Celeron M      | 1         | 0.32%   |
| AMD Ryzen 5 PRO      | 1         | 0.32%   |
| AMD GX               | 1         | 0.32%   |
| AMD E2               | 1         | 0.32%   |
| AMD A6               | 1         | 0.32%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 153       | 48.88%  |
| 4       | 73        | 23.32%  |
| 8       | 31        | 9.9%    |
| Unknown | 21        | 6.71%   |
| 16      | 12        | 3.83%   |
| 1       | 10        | 3.19%   |
| 6       | 7         | 2.24%   |
| 12      | 5         | 1.6%    |
| 10      | 1         | 0.32%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 301       | 96.17%  |
| 2       | 6         | 1.92%   |
| Unknown | 6         | 1.92%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 198       | 63.46%  |
| 1       | 85        | 27.24%  |
| Unknown | 29        | 9.29%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 47        | 15.06%  |
| Haswell       | 36        | 11.54%  |
| IvyBridge     | 32        | 10.26%  |
| SandyBridge   | 28        | 8.97%   |
| Zen           | 26        | 8.33%   |
| Penryn        | 20        | 6.41%   |
| Skylake       | 19        | 6.09%   |
| Broadwell     | 17        | 5.45%   |
| Unknown       | 15        | 4.81%   |
| Westmere      | 9         | 2.88%   |
| TigerLake     | 9         | 2.88%   |
| Core          | 8         | 2.56%   |
| Zen 2         | 7         | 2.24%   |
| Silvermont    | 7         | 2.24%   |
| Bonnell       | 5         | 1.6%    |
| Zen+          | 4         | 1.28%   |
| Zen 3         | 4         | 1.28%   |
| P6            | 4         | 1.28%   |
| Goldmont plus | 3         | 0.96%   |
| Goldmont      | 3         | 0.96%   |
| Puma          | 2         | 0.64%   |
| NetBurst      | 2         | 0.64%   |
| Piledriver    | 1         | 0.32%   |
| IceLake       | 1         | 0.32%   |
| Geode         | 1         | 0.32%   |
| CometLake     | 1         | 0.32%   |
| Bobcat        | 1         | 0.32%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 235       | 72.31%  |
| Nvidia                           | 53        | 16.31%  |
| AMD                              | 35        | 10.77%  |
| Trident Microsystems             | 1         | 0.31%   |
| Silicon Integrated Systems [SiS] | 1         | 0.31%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 32        | 9.55%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 26        | 7.76%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 22        | 6.57%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 17        | 5.07%   |
| Intel HD Graphics 5500                                                                   | 13        | 3.88%   |
| Intel UHD Graphics 620                                                                   | 12        | 3.58%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 12        | 3.58%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 10        | 2.99%   |
| Intel Core Processor Integrated Graphics Controller                                      | 10        | 2.99%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 2.69%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 9         | 2.69%   |
| Intel HD Graphics 620                                                                    | 8         | 2.39%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 7         | 2.09%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 1.79%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 6         | 1.79%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 6         | 1.79%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 5         | 1.49%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 1.49%   |
| AMD Lucienne                                                                             | 5         | 1.49%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 1.19%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 1.19%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 0.9%    |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                    | 3         | 0.9%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 0.9%    |
| Nvidia C79 [GeForce 9400M]                                                               | 3         | 0.9%    |
| Intel HD Graphics 500                                                                    | 3         | 0.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 0.9%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 0.9%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 0.9%    |
| AMD Mars XTX [Radeon HD 8790M]                                                           | 3         | 0.9%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.6%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.6%    |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 2         | 0.6%    |
| Nvidia G98M [Quadro NVS 160M]                                                            | 2         | 0.6%    |
| Nvidia G84M [GeForce 8600M GT]                                                           | 2         | 0.6%    |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 0.6%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.6%    |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 0.6%    |
| Intel HD Graphics P630                                                                   | 2         | 0.6%    |
| Intel HD Graphics 6000                                                                   | 2         | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 174       | 55.59%  |
| Intel + Nvidia           | 30        | 9.58%   |
| Other                    | 27        | 8.63%   |
| 1 x AMD                  | 25        | 7.99%   |
| 2 x Intel                | 24        | 7.67%   |
| 1 x Nvidia               | 21        | 6.71%   |
| Intel + AMD              | 7         | 2.24%   |
| AMD + Nvidia             | 3         | 0.96%   |
| 1 x Trident Microsystems | 1         | 0.32%   |
| 1 x SiS                  | 1         | 0.32%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 258       | 81.39%  |
| Unknown     | 42        | 13.25%  |
| Proprietary | 17        | 5.36%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 293       | 92.72%  |
| 0.01-0.5   | 11        | 3.48%   |
| 7.01-8.0   | 4         | 1.27%   |
| 3.01-4.0   | 4         | 1.27%   |
| 1.01-2.0   | 4         | 1.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| LG Display           | 39        | 20.21%  |
| AU Optronics         | 36        | 18.65%  |
| Chimei Innolux       | 18        | 9.33%   |
| BOE                  | 16        | 8.29%   |
| Apple                | 15        | 7.77%   |
| Samsung Electronics  | 14        | 7.25%   |
| Lenovo               | 12        | 6.22%   |
| Sharp                | 6         | 3.11%   |
| Dell                 | 6         | 3.11%   |
| InfoVision           | 4         | 2.07%   |
| Goldstar             | 4         | 2.07%   |
| PANDA                | 3         | 1.55%   |
| AOC                  | 3         | 1.55%   |
| Iiyama               | 2         | 1.04%   |
| BenQ                 | 2         | 1.04%   |
| Ancor Communications | 2         | 1.04%   |
| Unknown              | 2         | 1.04%   |
| TRU                  | 1         | 0.52%   |
| Toshiba              | 1         | 0.52%   |
| Panasonic            | 1         | 0.52%   |
| LTM                  | 1         | 0.52%   |
| LG Philips           | 1         | 0.52%   |
| JDI                  | 1         | 0.52%   |
| Hewlett-Packard      | 1         | 0.52%   |
| Eizo                 | 1         | 0.52%   |
| CSO                  | 1         | 0.52%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                  | 5         | 2.58%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch  | 3         | 1.55%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch           | 3         | 1.55%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch               | 3         | 1.55%   |
| BOE LCD Monitor BOE05E0 1366x768 280x160mm 12.7-inch                  | 3         | 1.55%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch        | 3         | 1.55%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch        | 3         | 1.55%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch         | 3         | 1.55%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch         | 3         | 1.55%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 290x170mm 13.2-inch               | 2         | 1.03%   |
| PANDA LCD Monitor NCP002D 1920x1080 340x190mm 15.3-inch               | 2         | 1.03%   |
| LG Display LCD Monitor LGD057E 1920x1080 340x190mm 15.3-inch          | 2         | 1.03%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch          | 2         | 1.03%   |
| LG Display LCD Monitor LGD04A3 1366x768 280x160mm 12.7-inch           | 2         | 1.03%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch          | 2         | 1.03%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch           | 2         | 1.03%   |
| LG Display LCD Monitor LGD0353 1366x768 350x190mm 15.7-inch           | 2         | 1.03%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch              | 2         | 1.03%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch               | 2         | 1.03%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch      | 2         | 1.03%   |
| BOE LCD Monitor BOE0900 1920x1080 340x190mm 15.3-inch                 | 2         | 1.03%   |
| BOE LCD Monitor BOE08EE 1920x1080 310x170mm 13.9-inch                 | 2         | 1.03%   |
| AU Optronics LCD Monitor AUO8074 1280x800 330x210mm 15.4-inch         | 2         | 1.03%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 340x190mm 15.3-inch        | 2         | 1.03%   |
| Unknown                                                               | 2         | 1.03%   |
| TRU LCD Monitor TRU235C 1366x768 260x140mm 11.6-inch                  | 1         | 0.52%   |
| Toshiba TV TSB0108 1360x768 700x390mm 31.5-inch                       | 1         | 0.52%   |
| Sharp LCD Monitor SHP14F9 1920x1200 290x180mm 13.4-inch               | 1         | 0.52%   |
| Sharp LCD Monitor SHP14BA 1920x1080 340x190mm 15.3-inch               | 1         | 0.52%   |
| Sharp LCD Monitor SHP143A 3840x2160 350x190mm 15.7-inch               | 1         | 0.52%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch               | 1         | 0.52%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch     | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC504B 1600x900 380x210mm 17.1-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC3245 1280x800 330x210mm 15.4-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC3157 1440x900 330x210mm 15.4-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC3143 1366x768 310x180mm 14.1-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 340x190mm 15.3-inch | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 340x190mm 15.3-inch  | 1         | 0.52%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 67        | 35.26%  |
| 1366x768 (WXGA)    | 54        | 28.42%  |
| 1280x800 (WXGA)    | 12        | 6.32%   |
| 3840x2160 (4K)     | 11        | 5.79%   |
| 1600x900 (HD+)     | 10        | 5.26%   |
| 2560x1440 (QHD)    | 8         | 4.21%   |
| 1440x900 (WXGA+)   | 7         | 3.68%   |
| 1920x1200 (WUXGA)  | 6         | 3.16%   |
| 3200x1800 (QHD+)   | 2         | 1.05%   |
| 2880x1800          | 2         | 1.05%   |
| 2560x1600          | 2         | 1.05%   |
| 1024x768 (XGA)     | 2         | 1.05%   |
| 9600x2160          | 1         | 0.53%   |
| 720x1280           | 1         | 0.53%   |
| 3000x2000          | 1         | 0.53%   |
| 2560x1080          | 1         | 0.53%   |
| 1920x540           | 1         | 0.53%   |
| 1680x1050 (WSXGA+) | 1         | 0.53%   |
| 1280x1024 (SXGA)   | 1         | 0.53%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 13      | 61        | 31.77%  |
| 15      | 54        | 28.13%  |
| 12      | 27        | 14.06%  |
| 17      | 8         | 4.17%   |
| 11      | 8         | 4.17%   |
| 24      | 7         | 3.65%   |
| 14      | 7         | 3.65%   |
| 27      | 6         | 3.13%   |
| Unknown | 5         | 2.6%    |
| 23      | 3         | 1.56%   |
| 39      | 1         | 0.52%   |
| 34      | 1         | 0.52%   |
| 32      | 1         | 0.52%   |
| 31      | 1         | 0.52%   |
| 26      | 1         | 0.52%   |
| 6       | 1         | 0.52%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 94        | 48.96%  |
| 201-300     | 64        | 33.33%  |
| 501-600     | 15        | 7.81%   |
| 351-400     | 7         | 3.65%   |
| Unknown     | 5         | 2.6%    |
| 701-800     | 2         | 1.04%   |
| 601-700     | 2         | 1.04%   |
| 801-900     | 1         | 0.52%   |
| 401-500     | 1         | 0.52%   |
| 101-200     | 1         | 0.52%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 143       | 77.72%  |
| 16/10   | 29        | 15.76%  |
| Unknown | 5         | 2.72%   |
| 4/3     | 3         | 1.63%   |
| 3/2     | 2         | 1.09%   |
| 5/4     | 1         | 0.54%   |
| 21/9    | 1         | 0.54%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 55        | 28.5%   |
| 91-100         | 36        | 18.65%  |
| 61-70          | 27        | 13.99%  |
| 101-110        | 19        | 9.84%   |
| 71-80          | 12        | 6.22%   |
| 51-60          | 8         | 4.15%   |
| 301-350        | 7         | 3.63%   |
| 201-250        | 7         | 3.63%   |
| 121-130        | 7         | 3.63%   |
| Unknown        | 5         | 2.59%   |
| 251-300        | 4         | 2.07%   |
| 351-500        | 3         | 1.55%   |
| 1-40           | 1         | 0.52%   |
| 141-150        | 1         | 0.52%   |
| 501-1000       | 1         | 0.52%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 92        | 48.94%  |
| 101-120       | 36        | 19.15%  |
| 51-100        | 23        | 12.23%  |
| 161-240       | 21        | 11.17%  |
| More than 240 | 11        | 5.85%   |
| Unknown       | 5         | 2.66%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 181       | 56.92%  |
| 0     | 119       | 37.42%  |
| 2     | 17        | 5.35%   |
| 3     | 1         | 0.31%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 232       | 47.44%  |
| Realtek Semiconductor             | 95        | 19.43%  |
| Qualcomm Atheros                  | 35        | 7.16%   |
| Broadcom                          | 33        | 6.75%   |
| AMD                               | 25        | 5.11%   |
| Ericsson Business Mobile Networks | 12        | 2.45%   |
| Sierra Wireless                   | 8         | 1.64%   |
| Ralink Technology                 | 7         | 1.43%   |
| Google                            | 5         | 1.02%   |
| Edimax Technology                 | 5         | 1.02%   |
| Nvidia                            | 4         | 0.82%   |
| Marvell Technology Group          | 4         | 0.82%   |
| ASUSTek Computer                  | 3         | 0.61%   |
| TP-Link                           | 2         | 0.41%   |
| Ralink                            | 2         | 0.41%   |
| MediaTek                          | 2         | 0.41%   |
| Hewlett-Packard                   | 2         | 0.41%   |
| Dell                              | 2         | 0.41%   |
| ULi Electronics                   | 1         | 0.2%    |
| Silicon Integrated Systems [SiS]  | 1         | 0.2%    |
| Samsung Electronics               | 1         | 0.2%    |
| Qualcomm Technologies             | 1         | 0.2%    |
| National Semiconductor            | 1         | 0.2%    |
| Micro Star International          | 1         | 0.2%    |
| JMicron Technology                | 1         | 0.2%    |
| Huawei Technologies               | 1         | 0.2%    |
| D-Link System                     | 1         | 0.2%    |
| Aquantia                          | 1         | 0.2%    |
| Apple                             | 1         | 0.2%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 74        | 11.8%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 34        | 5.42%   |
| AMD XGMAC 10GbE Controller                                                  | 25        | 3.99%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 23        | 3.67%   |
| Intel I210 Gigabit Network Connection                                       | 22        | 3.51%   |
| Intel Wireless 7265                                                         | 17        | 2.71%   |
| Intel Wireless 8265 / 8275                                                  | 15        | 2.39%   |
| Intel Wireless 8260                                                         | 15        | 2.39%   |
| Intel Wi-Fi 6 AX200                                                         | 15        | 2.39%   |
| Intel Centrino Ultimate-N 6300                                              | 15        | 2.39%   |
| Intel I211 Gigabit Network Connection                                       | 14        | 2.23%   |
| Intel Wireless 7260                                                         | 12        | 1.91%   |
| Intel Ethernet Connection I219-LM                                           | 12        | 1.91%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 11        | 1.75%   |
| Intel Ethernet Connection I217-LM                                           | 9         | 1.44%   |
| Intel 82577LM Gigabit Network Connection                                    | 9         | 1.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 8         | 1.28%   |
| Intel Wi-Fi 6 AX201                                                         | 8         | 1.28%   |
| Intel Ethernet Connection (3) I218-LM                                       | 8         | 1.28%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III | 7         | 1.12%   |
| Broadcom BCM43224 802.11a/b/g/n                                             | 7         | 1.12%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 6         | 0.96%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                      | 6         | 0.96%   |
| Intel Ethernet Connection (4) I219-LM                                       | 6         | 0.96%   |
| Sierra Wireless EM7455                                                      | 5         | 0.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 5         | 0.8%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 5         | 0.8%    |
| Intel Wireless-AC 9260                                                      | 5         | 0.8%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 5         | 0.8%    |
| Intel Ethernet Connection (4) I219-V                                        | 5         | 0.8%    |
| Google Nexus/Pixel Device (tether)                                          | 5         | 0.8%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 4         | 0.64%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                  | 4         | 0.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 4         | 0.64%   |
| Intel Wireless 3165                                                         | 4         | 0.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                            | 4         | 0.64%   |
| Intel Centrino Advanced-N 6200                                              | 4         | 0.64%   |
| Intel Cannon Lake PCH CNVi WiFi                                             | 4         | 0.64%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]              | 4         | 0.64%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                            | 3         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 185       | 63.36%  |
| Qualcomm Atheros         | 30        | 10.27%  |
| Broadcom                 | 25        | 8.56%   |
| Realtek Semiconductor    | 23        | 7.88%   |
| Ralink Technology        | 7         | 2.4%    |
| Sierra Wireless          | 6         | 2.05%   |
| Edimax Technology        | 5         | 1.71%   |
| ASUSTek Computer         | 3         | 1.03%   |
| TP-Link                  | 2         | 0.68%   |
| Ralink                   | 2         | 0.68%   |
| MediaTek                 | 2         | 0.68%   |
| Qualcomm Technologies    | 1         | 0.34%   |
| Micro Star International | 1         | 0.34%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 23        | 7.85%   |
| Intel Wireless 7265                                            | 17        | 5.8%    |
| Intel Wireless 8265 / 8275                                     | 15        | 5.12%   |
| Intel Wireless 8260                                            | 15        | 5.12%   |
| Intel Wi-Fi 6 AX200                                            | 15        | 5.12%   |
| Intel Centrino Ultimate-N 6300                                 | 15        | 5.12%   |
| Intel Wireless 7260                                            | 12        | 4.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 8         | 2.73%   |
| Intel Wi-Fi 6 AX201                                            | 8         | 2.73%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 7         | 2.39%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6         | 2.05%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 6         | 2.05%   |
| Sierra Wireless EM7455                                         | 5         | 1.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 5         | 1.71%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 5         | 1.71%   |
| Intel Wireless-AC 9260                                         | 5         | 1.71%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 5         | 1.71%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 4         | 1.37%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4         | 1.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4         | 1.37%   |
| Intel Wireless 3165                                            | 4         | 1.37%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 4         | 1.37%   |
| Intel Centrino Advanced-N 6200                                 | 4         | 1.37%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 4         | 1.37%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 4         | 1.37%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3         | 1.02%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 3         | 1.02%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 3         | 1.02%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 3         | 1.02%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 1.02%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 3         | 1.02%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 3         | 1.02%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2         | 0.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 0.68%   |
| Ralink RT5572 Wireless Adapter                                 | 2         | 0.68%   |
| Ralink RT5370 Wireless Adapter                                 | 2         | 0.68%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 2         | 0.68%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 2         | 0.68%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 0.68%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 155       | 50.32%  |
| Realtek Semiconductor    | 88        | 28.57%  |
| AMD                      | 25        | 8.12%   |
| Broadcom                 | 14        | 4.55%   |
| Qualcomm Atheros         | 8         | 2.6%    |
| Google                   | 5         | 1.62%   |
| Nvidia                   | 4         | 1.3%    |
| Marvell Technology Group | 4         | 1.3%    |
| Samsung Electronics      | 1         | 0.32%   |
| National Semiconductor   | 1         | 0.32%   |
| JMicron Technology       | 1         | 0.32%   |
| Aquantia                 | 1         | 0.32%   |
| Apple                    | 1         | 0.32%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 74        | 23.87%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 34        | 10.97%  |
| AMD XGMAC 10GbE Controller                                        | 25        | 8.06%   |
| Intel I210 Gigabit Network Connection                             | 22        | 7.1%    |
| Intel I211 Gigabit Network Connection                             | 14        | 4.52%   |
| Intel Ethernet Connection I219-LM                                 | 12        | 3.87%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 3.55%   |
| Intel Ethernet Connection I217-LM                                 | 9         | 2.9%    |
| Intel 82577LM Gigabit Network Connection                          | 9         | 2.9%    |
| Intel Ethernet Connection (3) I218-LM                             | 8         | 2.58%   |
| Intel Ethernet Connection (4) I219-LM                             | 6         | 1.94%   |
| Intel Ethernet Connection (4) I219-V                              | 5         | 1.61%   |
| Google Nexus/Pixel Device (tether)                                | 5         | 1.61%   |
| Nvidia MCP79 Ethernet                                             | 3         | 0.97%   |
| Intel Ethernet Connection I219-V                                  | 3         | 0.97%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.97%   |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 0.97%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.97%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 0.97%   |
| Intel 82566MM Gigabit Network Connection                          | 3         | 0.97%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 3         | 0.97%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.65%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.65%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 0.65%   |
| Intel Ethernet Controller I225-V                                  | 2         | 0.65%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.65%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.65%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 0.65%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.65%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 0.65%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 0.65%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.32%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.32%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.32%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.32%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.32%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.32%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.32%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.32%   |
| Nvidia MCP89 Ethernet                                             | 1         | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 280       | 49.3%   |
| WiFi     | 263       | 46.3%   |
| Unknown  | 13        | 2.29%   |
| Modem    | 12        | 2.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 219       | 56.3%   |
| WiFi     | 162       | 41.65%  |
| Unknown  | 7         | 1.8%    |
| Modem    | 1         | 0.26%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 217       | 69.33%  |
| 1     | 49        | 15.65%  |
| 6     | 17        | 5.43%   |
| 5     | 17        | 5.43%   |
| 3     | 8         | 2.56%   |
| 0     | 2         | 0.64%   |
| 8     | 1         | 0.32%   |
| 7     | 1         | 0.32%   |
| 4     | 1         | 0.32%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 274       | 86.98%  |
| Yes  | 41        | 13.02%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 98        | 54.14%  |
| Broadcom                        | 21        | 11.6%   |
| Apple                           | 16        | 8.84%   |
| Qualcomm Atheros Communications | 14        | 7.73%   |
| Realtek Semiconductor           | 8         | 4.42%   |
| Foxconn / Hon Hai               | 7         | 3.87%   |
| Lite-On Technology              | 3         | 1.66%   |
| Dell                            | 3         | 1.66%   |
| IMC Networks                    | 2         | 1.1%    |
| Hewlett-Packard                 | 2         | 1.1%    |
| Cambridge Silicon Radio         | 2         | 1.1%    |
| ASUSTek Computer                | 2         | 1.1%    |
| Alps Electric                   | 2         | 1.1%    |
| USI                             | 1         | 0.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 46        | 25.41%  |
| Intel AX200 Bluetooth                                       | 15        | 8.29%   |
| Intel AX201 Bluetooth                                       | 12        | 6.63%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 9         | 4.97%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 8         | 4.42%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 8         | 4.42%   |
| Apple Bluetooth Host Controller                             | 7         | 3.87%   |
| Intel AX210 Bluetooth                                       | 5         | 2.76%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 5         | 2.76%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 4         | 2.21%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 4         | 2.21%   |
| Intel Wireless-AC 3168 Bluetooth                            | 4         | 2.21%   |
| Lite-On Atheros AR3012 Bluetooth                            | 3         | 1.66%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 3         | 1.66%   |
| Apple Broadcom Built-in Bluetooth                           | 3         | 1.66%   |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 1.1%    |
| Realtek Bluetooth 4.2 Adapter                               | 2         | 1.1%    |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 2         | 1.1%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 2         | 1.1%    |
| Qualcomm Atheros AR9462 Bluetooth                           | 2         | 1.1%    |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 2         | 1.1%    |
| Foxconn / Hon Hai Bluetooth USB Module                      | 2         | 1.1%    |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 2         | 1.1%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2         | 1.1%    |
| USI Qualcomm WCN685x Bluetooth Adapter                      | 1         | 0.55%   |
| Realtek RTL8821A Bluetooth                                  | 1         | 0.55%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 0.55%   |
| Realtek Bluetooth Adapter                                   | 1         | 0.55%   |
| Realtek Bluetooth 4.0 + High Speed Chip                     | 1         | 0.55%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 0.55%   |
| Qualcomm Atheros Dell Wireless 1802 Bluetooth 4.0 LE        | 1         | 0.55%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 0.55%   |
| Qualcomm Atheros Bluetooth                                  | 1         | 0.55%   |
| Intel AX211 Bluetooth                                       | 1         | 0.55%   |
| IMC Networks Bluetooth Module                               | 1         | 0.55%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 1         | 0.55%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 0.55%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter                  | 1         | 0.55%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 0.55%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device             | 1         | 0.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 249       | 75.45%  |
| AMD                                          | 50        | 15.15%  |
| Nvidia                                       | 20        | 6.06%   |
| Realtek Semiconductor                        | 2         | 0.61%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.3%    |
| ULi Electronics                              | 1         | 0.3%    |
| Texas Instruments                            | 1         | 0.3%    |
| Silicon Integrated Systems [SiS]             | 1         | 0.3%    |
| Phison Electronics                           | 1         | 0.3%    |
| Logitech                                     | 1         | 0.3%    |
| Lenovo                                       | 1         | 0.3%    |
| Hewlett-Packard                              | 1         | 0.3%    |
| GN Netcom                                    | 1         | 0.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 39        | 9.75%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 37        | 9.25%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 33        | 8.25%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 26        | 6.5%    |
| Intel 8 Series HD Audio Controller                                                                | 22        | 5.5%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 21        | 5.25%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 17        | 4.25%   |
| Intel Broadwell-U Audio Controller                                                                | 17        | 4.25%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 14        | 3.5%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 13        | 3.25%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 13        | 3.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 12        | 3%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 11        | 2.75%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 10        | 2.5%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 9         | 2.25%   |
| Intel Cannon Lake PCH cAVS                                                                        | 9         | 2.25%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 8         | 2%      |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 1.75%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 1.75%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 1.25%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1%      |
| Intel CM238 HD Audio Controller                                                                   | 4         | 1%      |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 0.75%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 0.75%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 0.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 0.75%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 0.75%   |
| AMD FCH Azalia Controller                                                                         | 3         | 0.75%   |
| Realtek Semiconductor USB Audio                                                                   | 2         | 0.5%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.5%    |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.5%    |
| Intel Jasper Lake HD Audio                                                                        | 2         | 0.5%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 0.5%    |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 2         | 0.5%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 0.5%    |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 1         | 0.25%   |
| ULi Electronics M5451 PCI AC-Link Controller Audio Device                                         | 1         | 0.25%   |
| Texas Instruments PCM2900 Audio Codec                                                             | 1         | 0.25%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 1         | 0.25%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 90        | 27.78%  |
| SK hynix                     | 62        | 19.14%  |
| Kingston                     | 35        | 10.8%   |
| Micron Technology            | 30        | 9.26%   |
| Unknown                      | 24        | 7.41%   |
| Transcend                    | 24        | 7.41%   |
| Crucial                      | 14        | 4.32%   |
| Unknown                      | 9         | 2.78%   |
| Ramaxel Technology           | 8         | 2.47%   |
| Corsair                      | 8         | 2.47%   |
| Elpida                       | 6         | 1.85%   |
| Nanya Technology             | 5         | 1.54%   |
| G.Skill                      | 2         | 0.62%   |
| Unknown (ABCD)               | 1         | 0.31%   |
| Unknown (0x7F7F7F94FFFFFFFF) | 1         | 0.31%   |
| Team                         | 1         | 0.31%   |
| Patriot                      | 1         | 0.31%   |
| ASint Technology             | 1         | 0.31%   |
| A-DATA Technology            | 1         | 0.31%   |
| 48spaces                     | 1         | 0.31%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s           | 14        | 4.18%   |
| Unknown                                                       | 9         | 2.69%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 7         | 2.09%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s        | 7         | 2.09%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s         | 7         | 2.09%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                  | 6         | 1.79%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s         | 6         | 1.79%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s         | 5         | 1.49%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s         | 5         | 1.49%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s         | 5         | 1.49%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s       | 5         | 1.49%   |
| Transcend RAM TS512MLH64V6HL 4GB SODIMM DDR4 2667MT/s         | 4         | 1.19%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 4         | 1.19%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s         | 4         | 1.19%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s         | 4         | 1.19%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s         | 4         | 1.19%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s         | 4         | 1.19%   |
| Transcend RAM TS1GLH64V6B3 8GB SODIMM DDR4 1333MT/s           | 3         | 0.9%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 3         | 0.9%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 3         | 0.9%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s         | 3         | 0.9%    |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s        | 3         | 0.9%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s         | 3         | 0.9%    |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s       | 3         | 0.9%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                    | 2         | 0.6%    |
| Transcend RAM TS1GLH64V6B 8GB SODIMM DDR4 1333MT/s            | 2         | 0.6%    |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s        | 2         | 0.6%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s        | 2         | 0.6%    |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s        | 2         | 0.6%    |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2400MT/s        | 2         | 0.6%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s         | 2         | 0.6%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s         | 2         | 0.6%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s         | 2         | 0.6%    |
| Ramaxel RAM RMT3020EC58E9F1333 4GB SODIMM DDR3 1333MT/s       | 2         | 0.6%    |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 0.6%    |
| Micron RAM 16KTF1G64HZ-1G6P1 8GB SODIMM DDR3 1600MT/s         | 2         | 0.6%    |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s         | 2         | 0.6%    |
| Kingston RAM CBD26D4S9S8K1C-8 8GB SODIMM DDR4 2667MT/s        | 2         | 0.6%    |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s        | 2         | 0.6%    |
| Kingston RAM 99U5428-042.A00G 4096MB SODIMM DDR3 1334MT/s     | 2         | 0.6%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 137       | 48.41%  |
| DDR4    | 103       | 36.4%   |
| DDR2    | 18        | 6.36%   |
| LPDDR4  | 6         | 2.12%   |
| LPDDR3  | 5         | 1.77%   |
| DDR     | 5         | 1.77%   |
| Unknown | 4         | 1.41%   |
| SDRAM   | 2         | 0.71%   |
| RAM     | 1         | 0.35%   |
| LPDDR5  | 1         | 0.35%   |
| DRAM    | 1         | 0.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 264       | 93.62%  |
| Row Of Chips | 12        | 4.26%   |
| Chip         | 4         | 1.42%   |
| DIMM         | 2         | 0.71%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 122       | 40.8%   |
| 4096  | 78        | 26.09%  |
| 2048  | 48        | 16.05%  |
| 16384 | 33        | 11.04%  |
| 1024  | 10        | 3.34%   |
| 32768 | 4         | 1.34%   |
| 512   | 2         | 0.67%   |
| 256   | 2         | 0.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 89        | 30.17%  |
| 2667    | 46        | 15.59%  |
| 1333    | 28        | 9.49%   |
| 3200    | 27        | 9.15%   |
| 2400    | 18        | 6.1%    |
| 1334    | 16        | 5.42%   |
| 2133    | 14        | 4.75%   |
| 667     | 13        | 4.41%   |
| 1867    | 9         | 3.05%   |
| 800     | 9         | 3.05%   |
| Unknown | 8         | 2.71%   |
| 4267    | 5         | 1.69%   |
| 1067    | 5         | 1.69%   |
| 1066    | 2         | 0.68%   |
| 533     | 2         | 0.68%   |
| 6400    | 1         | 0.34%   |
| 2933    | 1         | 0.34%   |
| 1639    | 1         | 0.34%   |
| 975     | 1         | 0.34%   |

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
| Chicony Electronics                    | 63        | 34.62%  |
| Bison Electronics                      | 23        | 12.64%  |
| Realtek Semiconductor                  | 12        | 6.59%   |
| Microdia                               | 12        | 6.59%   |
| IMC Networks                           | 11        | 6.04%   |
| Suyin                                  | 9         | 4.95%   |
| Lite-On Technology                     | 9         | 4.95%   |
| Sunplus Innovation Technology          | 8         | 4.4%    |
| Apple                                  | 6         | 3.3%    |
| Syntek                                 | 5         | 2.75%   |
| Lenovo                                 | 5         | 2.75%   |
| Alcor Micro                            | 4         | 2.2%    |
| Quanta                                 | 3         | 1.65%   |
| Silicon Motion                         | 2         | 1.1%    |
| Luxvisions Innotech Limited            | 2         | 1.1%    |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.1%    |
| Tripath Technology                     | 1         | 0.55%   |
| SunplusIT                              | 1         | 0.55%   |
| Ricoh                                  | 1         | 0.55%   |
| Pixart Imaging                         | 1         | 0.55%   |
| Logitech                               | 1         | 0.55%   |
| Cubeternet                             | 1         | 0.55%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 26        | 14.21%  |
| Bison Integrated Camera                  | 10        | 5.46%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 7         | 3.83%   |
| Lite-On Integrated Camera                | 6         | 3.28%   |
| Microdia Integrated Webcam               | 5         | 2.73%   |
| IMC Networks Integrated Camera           | 5         | 2.73%   |
| Chicony FJ Camera                        | 5         | 2.73%   |
| Realtek USB 2.0 PC Camera                | 4         | 2.19%   |
| Chicony HD Webcam                        | 4         | 2.19%   |
| Apple FaceTime HD Camera (Built-in)      | 4         | 2.19%   |
| Syntek Integrated Camera                 | 3         | 1.64%   |
| Suyin RGBIR Camera                       | 3         | 1.64%   |
| Chicony Integrated Camera [ThinkPad]     | 3         | 1.64%   |
| Bison ThinkPad Integrated Camera         | 3         | 1.64%   |
| Bison SunplusIT Integrated Camera        | 3         | 1.64%   |
| Alcor Micro USB 2.0 Camera               | 3         | 1.64%   |
| Syntek Lenovo EasyCamera                 | 2         | 1.09%   |
| Realtek Integrated_Webcam_HD             | 2         | 1.09%   |
| Quanta HP TrueVision HD Camera           | 2         | 1.09%   |
| Microdia Integrated_Webcam_HD            | 2         | 1.09%   |
| Lite-On Realtek PC Camera                | 2         | 1.09%   |
| Lenovo Integrated Webcam [R5U877]        | 2         | 1.09%   |
| Lenovo Integrated Camera                 | 2         | 1.09%   |
| IMC Networks XHC Camera                  | 2         | 1.09%   |
| IMC Networks Realtek PC Camera           | 2         | 1.09%   |
| Chicony Integrated IR Camera             | 2         | 1.09%   |
| Chicony HD WebCam (Acer)                 | 2         | 1.09%   |
| Chicony Chicony USB2.0 Camera            | 2         | 1.09%   |
| Bison SunplusIT INC. Integrated Camera   | 2         | 1.09%   |
| Bison Lenovo EasyCamera                  | 2         | 1.09%   |
| Tripath USB Camera                       | 1         | 0.55%   |
| Suyin Sony Visual Communication Camera   | 1         | 0.55%   |
| Suyin Integrated Webcam                  | 1         | 0.55%   |
| Suyin HP Webcam-101                      | 1         | 0.55%   |
| Suyin HP Integrated Webcam               | 1         | 0.55%   |
| Suyin Asus Integrated Webcam             | 1         | 0.55%   |
| Suyin Acer/Lenovo Webcam [CN0316]        | 1         | 0.55%   |
| SunplusIT USB camera                     | 1         | 0.55%   |
| Sunplus MTD camera                       | 1         | 0.55%   |
| Sunplus Laptop_Integrated_Webcam_FHD     | 1         | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 24        | 35.29%  |
| Upek                       | 11        | 16.18%  |
| Synaptics                  | 11        | 16.18%  |
| LighTuning Technology      | 5         | 7.35%   |
| AuthenTec                  | 5         | 7.35%   |
| Shenzhen Goodix Technology | 4         | 5.88%   |
| Broadcom                   | 3         | 4.41%   |
| STMicroelectronics         | 2         | 2.94%   |
| Elan Microelectronics      | 2         | 2.94%   |
| Next Biometrics            | 1         | 1.47%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 10        | 14.71%  |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 9         | 13.24%  |
| Validity Sensors Synaptics WBDI                                              | 6         | 8.82%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 4         | 5.88%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 3         | 4.41%   |
| Shenzhen Goodix Fingerprint Reader                                           | 3         | 4.41%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 3         | 4.41%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 4.41%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 2         | 2.94%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 2         | 2.94%   |
| Validity Sensors Swipe Fingerprint Sensor                                    | 2         | 2.94%   |
| STMicroelectronics Fingerprint Reader                                        | 2         | 2.94%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 2         | 2.94%   |
| Elan Fingerprint Sensor                                                      | 2         | 2.94%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 1         | 1.47%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 1         | 1.47%   |
| Validity Sensors VFS Fingerprint sensor                                      | 1         | 1.47%   |
| Upek TCS5B Fingerprint sensor                                                | 1         | 1.47%   |
| Synaptics WBDI                                                               | 1         | 1.47%   |
| Synaptics TouchPad                                                           | 1         | 1.47%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 1         | 1.47%   |
| Shenzhen Goodix Fingerprint Reader SGX                                       | 1         | 1.47%   |
| Next Biometrics NB-2020-U Fingerprint Reader                                 | 1         | 1.47%   |
| AuthenTec AES2660                                                            | 1         | 1.47%   |
| AuthenTec AES2550 Fingerprint Sensor                                         | 1         | 1.47%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 1         | 1.47%   |
| AuthenTec AES1660                                                            | 1         | 1.47%   |
| AuthenTec AES1600                                                            | 1         | 1.47%   |
| Unknown                                                                      | 1         | 1.47%   |

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
| 1     | 97        | 30.12%  |
| 2     | 82        | 25.47%  |
| 0     | 61        | 18.94%  |
| 3     | 54        | 16.77%  |
| 4     | 19        | 5.9%    |
| 5     | 7         | 2.17%   |
| 7     | 1         | 0.31%   |
| 6     | 1         | 0.31%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 212       | 42.66%  |
| Bluetooth                | 66        | 13.28%  |
| Fingerprint reader       | 59        | 11.87%  |
| Card reader              | 54        | 10.87%  |
| Net/wireless             | 47        | 9.46%   |
| Firewire controller      | 20        | 4.02%   |
| Network                  | 9         | 1.81%   |
| Graphics card            | 9         | 1.81%   |
| Net/ethernet             | 6         | 1.21%   |
| Sound                    | 5         | 1.01%   |
| Modem                    | 4         | 0.8%    |
| Storage                  | 3         | 0.6%    |
| Storage/nvme             | 1         | 0.2%    |
| Storage/ide              | 1         | 0.2%    |
| Storage/ata              | 1         | 0.2%    |

