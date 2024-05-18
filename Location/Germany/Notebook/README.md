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

Total: 497

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Apple         | MacBookPro5,5               | [ffd31a143f](https://bsd-hardware.info/?probe=ffd31a143f) | May 04, 2024 |
| HP            | 255 G8 Notebook PC          | [4878c18c8a](https://bsd-hardware.info/?probe=4878c18c8a) | May 01, 2024 |
| Deciso        | NetBoard-A20                | [c04565ec24](https://bsd-hardware.info/?probe=c04565ec24) | Apr 30, 2024 |
| System76      | Pangolin                    | [d47c9a5d44](https://bsd-hardware.info/?probe=d47c9a5d44) | Apr 26, 2024 |
| Lenovo        | ThinkPad T400 6474E18       | [fcd3339ec5](https://bsd-hardware.info/?probe=fcd3339ec5) | Apr 21, 2024 |
| Deciso        | NetBoard-A20                | [82519e798c](https://bsd-hardware.info/?probe=82519e798c) | Apr 18, 2024 |
| Unknown       | Unknown                     | [5886bb9659](https://bsd-hardware.info/?probe=5886bb9659) | Apr 18, 2024 |
| Lenovo        | ThinkPad T460 20FMA09CGE    | [c7219eb82e](https://bsd-hardware.info/?probe=c7219eb82e) | Apr 15, 2024 |
| Deciso        | NetBoard-A20                | [f6d9d3eaf2](https://bsd-hardware.info/?probe=f6d9d3eaf2) | Apr 03, 2024 |
| Apple         | MacBookAir7,2               | [a596a6f2fc](https://bsd-hardware.info/?probe=a596a6f2fc) | Mar 30, 2024 |
| Shuttle       | DS77U                       | [b065bf5918](https://bsd-hardware.info/?probe=b065bf5918) | Mar 27, 2024 |
| Fujitsu       | LIFEBOOK U727               | [76e6dff995](https://bsd-hardware.info/?probe=76e6dff995) | Mar 27, 2024 |
| Apple         | MacBookAir7,2               | [a5003ca56a](https://bsd-hardware.info/?probe=a5003ca56a) | Mar 25, 2024 |
| Deciso        | DEC2700 - OPNsense Appli... | [7617a6faa1](https://bsd-hardware.info/?probe=7617a6faa1) | Mar 19, 2024 |
| Dell          | Latitude D830               | [832440d0c3](https://bsd-hardware.info/?probe=832440d0c3) | Mar 17, 2024 |
| Google        | Cave                        | [d9df48c781](https://bsd-hardware.info/?probe=d9df48c781) | Mar 16, 2024 |
| Apple         | MacBookAir7,2               | [58cc0f695b](https://bsd-hardware.info/?probe=58cc0f695b) | Mar 14, 2024 |
| TULPAR        | A5 V20.3                    | [476d91b2cf](https://bsd-hardware.info/?probe=476d91b2cf) | Mar 13, 2024 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [4b52e91e24](https://bsd-hardware.info/?probe=4b52e91e24) | Mar 13, 2024 |
| Acer          | Aspire V5-573G              | [59445c5f19](https://bsd-hardware.info/?probe=59445c5f19) | Mar 12, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [0ceb5cfbf8](https://bsd-hardware.info/?probe=0ceb5cfbf8) | Mar 10, 2024 |
| Deciso        | NetBoard-A20                | [2e0ce432cb](https://bsd-hardware.info/?probe=2e0ce432cb) | Mar 07, 2024 |
| Deciso        | NetBoard-A20                | [7c73382c9d](https://bsd-hardware.info/?probe=7c73382c9d) | Feb 26, 2024 |
| Dell          | Latitude E5510              | [4155c54a6c](https://bsd-hardware.info/?probe=4155c54a6c) | Feb 19, 2024 |
| Dell          | Latitude E5510              | [1bc1ac66c3](https://bsd-hardware.info/?probe=1bc1ac66c3) | Feb 18, 2024 |
| Deciso        | NetBoard-A10                | [8403713b4f](https://bsd-hardware.info/?probe=8403713b4f) | Feb 10, 2024 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | [2a4911715a](https://bsd-hardware.info/?probe=2a4911715a) | Feb 07, 2024 |
| Apple         | MacBookPro11,1              | [c77173c2f3](https://bsd-hardware.info/?probe=c77173c2f3) | Feb 04, 2024 |
| Deciso        | NetBoard-A10                | [118bac872e](https://bsd-hardware.info/?probe=118bac872e) | Feb 03, 2024 |
| Apple         | MacBookPro8,2               | [95f19036db](https://bsd-hardware.info/?probe=95f19036db) | Feb 03, 2024 |
| TUXEDO        | Aura 15 Gen1                | [4768e0001d](https://bsd-hardware.info/?probe=4768e0001d) | Feb 01, 2024 |
| Dell          | Precision M4700             | [05a9a26c16](https://bsd-hardware.info/?probe=05a9a26c16) | Jan 24, 2024 |
| Unknown       | Unknown                     | [6fe553c729](https://bsd-hardware.info/?probe=6fe553c729) | Jan 21, 2024 |
| Unknown       | Unknown                     | [e85605ed72](https://bsd-hardware.info/?probe=e85605ed72) | Jan 21, 2024 |
| Apple         | MacBookAir4,1               | [f51a396e5e](https://bsd-hardware.info/?probe=f51a396e5e) | Jan 21, 2024 |
| Dell          | Latitude E7450              | [f2216c5d0f](https://bsd-hardware.info/?probe=f2216c5d0f) | Jan 21, 2024 |
| BESSTAR Te... | U820                        | [9d1b8fbbd5](https://bsd-hardware.info/?probe=9d1b8fbbd5) | Jan 18, 2024 |
| BESSTAR Te... | U820                        | [7e38f4e795](https://bsd-hardware.info/?probe=7e38f4e795) | Jan 18, 2024 |
| Apple         | MacBookAir4,1               | [b9653bc7d3](https://bsd-hardware.info/?probe=b9653bc7d3) | Jan 14, 2024 |
| Unknown       | Unknown                     | [4b22a105d7](https://bsd-hardware.info/?probe=4b22a105d7) | Jan 11, 2024 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [0f475f8e5d](https://bsd-hardware.info/?probe=0f475f8e5d) | Jan 10, 2024 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [6b21d0ae92](https://bsd-hardware.info/?probe=6b21d0ae92) | Jan 09, 2024 |
| HP            | Compaq 6510b (GM108UC#AB... | [7ed7da2383](https://bsd-hardware.info/?probe=7ed7da2383) | Jan 08, 2024 |
| Unknown       | Unknown                     | [c1d43f83f4](https://bsd-hardware.info/?probe=c1d43f83f4) | Jan 02, 2024 |
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
| Apple         | MacBookAir4,1               | [6eada6e49e](https://bsd-hardware.info/?probe=6eada6e49e) | Aug 28, 2021 |
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
| helloSystem 0.8.1    | 20        | 4.95%   |
| helloSystem 0.4.0    | 14        | 3.47%   |
| helloSystem 0.7.0    | 13        | 3.22%   |
| OpenBSD 6.8          | 12        | 2.97%   |
| helloSystem 0.5.0    | 12        | 2.97%   |
| FreeBSD 14.0         | 12        | 2.97%   |
| helloSystem 0.8.0    | 11        | 2.72%   |
| FreeBSD 12.2         | 10        | 2.48%   |
| OpenBSD 7.0          | 8         | 1.98%   |
| FreeBSD 14.0-CURRENT | 7         | 1.73%   |
| FreeBSD 13.2         | 7         | 1.73%   |
| FreeBSD 13.0-p4      | 7         | 1.73%   |
| OpenBSD 7.2          | 6         | 1.49%   |
| OpenBSD 6.9          | 6         | 1.49%   |
| helloSystem 0.6.0    | 6         | 1.49%   |
| GhostBSD 22.01.12    | 6         | 1.49%   |
| FreeBSD 12.1-p10     | 6         | 1.49%   |
| OPNsense 23.1.11     | 5         | 1.24%   |
| OPNsense 21.7.6      | 5         | 1.24%   |
| OpenBSD 6.7          | 5         | 1.24%   |
| NomadBSD 5806f915    | 5         | 1.24%   |
| GhostBSD 21.08.27    | 5         | 1.24%   |
| FreeBSD 13.0-CURRENT | 5         | 1.24%   |
| FreeBSD 13.0         | 5         | 1.24%   |
| FreeBSD 12.2-p2      | 5         | 1.24%   |
| FreeBSD 12.1-STABLE  | 5         | 1.24%   |
| OPNsense 21.1.2      | 4         | 0.99%   |
| NomadBSD 1.4         | 4         | 0.99%   |
| GhostBSD 20.04.02    | 4         | 0.99%   |
| FreeBSD 13.1-p5      | 4         | 0.99%   |
| FreeBSD 12.1-p5      | 4         | 0.99%   |
| FreeBSD 12.1         | 4         | 0.99%   |
| OPNsense 24.1.4      | 3         | 0.74%   |
| OPNsense 23.7.6      | 3         | 0.74%   |
| OPNsense 23.10.2     | 3         | 0.74%   |
| OPNsense 22.1.6      | 3         | 0.74%   |
| NomadBSD 20231013    | 3         | 0.74%   |
| NomadBSD 1.4-RC1     | 3         | 0.74%   |
| helloSystem 0.9.0    | 3         | 0.74%   |
| GhostBSD 24.01.1     | 3         | 0.74%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 117       | 33.43%  |
| helloSystem | 77        | 22%     |
| OPNsense    | 73        | 20.86%  |
| OpenBSD     | 36        | 10.29%  |
| GhostBSD    | 25        | 7.14%   |
| NomadBSD    | 17        | 4.86%   |
| NetBSD      | 2         | 0.57%   |
| MidnightBSD | 1         | 0.29%   |
| HardenedBSD | 1         | 0.29%   |
| FuryBSD     | 1         | 0.29%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| amd64  | 329       | 97.05%  |
| i386   | 9         | 2.65%   |
| macppc | 1         | 0.29%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Console       | 95        | 26.69%  |
| helloDesktop  | 82        | 23.03%  |
| MATE          | 33        | 9.27%   |
| XFCE          | 31        | 8.71%   |
| KDE5          | 27        | 7.58%   |
| fvwm          | 25        | 7.02%   |
| GNOME         | 18        | 5.06%   |
| Openbox       | 15        | 4.21%   |
| TWM           | 12        | 3.37%   |
| i3            | 5         | 1.4%    |
| AwesomeWM     | 4         | 1.12%   |
| Cinnamon      | 2         | 0.56%   |
| Picom         | 1         | 0.28%   |
| LXQt          | 1         | 0.28%   |
| LXDE          | 1         | 0.28%   |
| JWM           | 1         | 0.28%   |
| iwm           | 1         | 0.28%   |
| IceWM         | 1         | 0.28%   |
| Enlightenment | 1         | 0.28%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 239       | 69.88%  |
| Console | 101       | 29.53%  |
| Wayland | 2         | 0.58%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 150       | 42.02%  |
| SLiM    | 108       | 30.25%  |
| SDDM    | 36        | 10.08%  |
| LightDM | 36        | 10.08%  |
| XDM     | 13        | 3.64%   |
| GDM     | 11        | 3.08%   |
| Ly      | 3         | 0.84%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Notebooks | Percent |
|------------------|-----------|---------|
| Unknown          | 143       | 39.83%  |
| de_DE            | 65        | 18.11%  |
| C                | 65        | 18.11%  |
| en_US            | 64        | 17.83%  |
| de               | 8         | 2.23%   |
| en_GB            | 5         | 1.39%   |
| fr_FR            | 2         | 0.56%   |
| de_DE.ISO8859-1  | 2         | 0.56%   |
| pl_PL            | 1         | 0.28%   |
| en_IE            | 1         | 0.28%   |
| en_CA            | 1         | 0.28%   |
| en               | 1         | 0.28%   |
| de_DE.ISO8859-15 | 1         | 0.28%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 284       | 82.32%  |
| BIOS | 61        | 17.68%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 188       | 54.02%  |
| Ufs    | 97        | 27.87%  |
| Ffs    | 36        | 10.34%  |
| Cd9660 | 27        | 7.76%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 315       | 91.84%  |
| MBR     | 25        | 7.29%   |
| Unknown | 3         | 0.87%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 115       | 33.92%  |
| Dell                | 36        | 10.62%  |
| Deciso              | 30        | 8.85%   |
| Hewlett-Packard     | 22        | 6.49%   |
| Apple               | 22        | 6.49%   |
| Acer                | 15        | 4.42%   |
| Unknown             | 15        | 4.42%   |
| Fujitsu             | 13        | 3.83%   |
| TUXEDO              | 10        | 2.95%   |
| ASUSTek Computer    | 10        | 2.95%   |
| Shuttle             | 4         | 1.18%   |
| Notebook            | 4         | 1.18%   |
| Sony                | 3         | 0.88%   |
| MSI                 | 3         | 0.88%   |
| Toshiba             | 2         | 0.59%   |
| Tactus              | 2         | 0.59%   |
| Schenker            | 2         | 0.59%   |
| Samsung Electronics | 2         | 0.59%   |
| Panasonic           | 2         | 0.59%   |
| Medion              | 2         | 0.59%   |
| IBM                 | 2         | 0.59%   |
| Google              | 2         | 0.59%   |
| Gigabyte Technology | 2         | 0.59%   |
| BESSTAR Tech        | 2         | 0.59%   |
| Wortmann AG         | 1         | 0.29%   |
| TULPAR              | 1         | 0.29%   |
| System76            | 1         | 0.29%   |
| Packard Bell        | 1         | 0.29%   |
| MiTAC               | 1         | 0.29%   |
| Intel               | 1         | 0.29%   |
| Insyde              | 1         | 0.29%   |
| IGEL Technology     | 1         | 0.29%   |
| HUAWEI              | 1         | 0.29%   |
| HKC                 | 1         | 0.29%   |
| Hampoo              | 1         | 0.29%   |
| GPD                 | 1         | 0.29%   |
| CSL-Computer        | 1         | 0.29%   |
| Clevo               | 1         | 0.29%   |
| AMI                 | 1         | 0.29%   |
| Alienware           | 1         | 0.29%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 16        | 4.72%   |
| Deciso NetBoard-A10                 | 14        | 4.13%   |
| Deciso Netboard A20                 | 6         | 1.77%   |
| Deciso NetBoard-A20                 | 5         | 1.47%   |
| Deciso DEC2700 - OPNsense Appliance | 4         | 1.18%   |
| Apple MacBookAir5,1                 | 4         | 1.18%   |
| Dell Latitude E6540                 | 3         | 0.88%   |
| TUXEDO Pulse 15 Gen1                | 2         | 0.59%   |
| TUXEDO Pulse 14 Gen1                | 2         | 0.59%   |
| Shuttle DS437                       | 2         | 0.59%   |
| Lenovo ThinkPad X260 20F5S1H800     | 2         | 0.59%   |
| Lenovo ThinkPad X230 232578G        | 2         | 0.59%   |
| Lenovo ThinkPad T410s 291245G       | 2         | 0.59%   |
| Lenovo ThinkPad E490 20N8CTO1WW     | 2         | 0.59%   |
| HP ZBook 15 G4                      | 2         | 0.59%   |
| HP 255 G8 Notebook PC               | 2         | 0.59%   |
| Gigabyte GB-BSi5A-6200              | 2         | 0.59%   |
| Dell Latitude E6500                 | 2         | 0.59%   |
| Dell Latitude E6330                 | 2         | 0.59%   |
| Dell Latitude 5591                  | 2         | 0.59%   |
| BESSTAR Tech U820                   | 2         | 0.59%   |
| ASUS TUF Gaming FX505DT_FX505DT     | 2         | 0.59%   |
| Apple MacBookAir7,2                 | 2         | 0.59%   |
| Apple MacBook5,1                    | 2         | 0.59%   |
| Wortmann AG TERRA_MOBILE_1541       | 1         | 0.29%   |
| TUXEDO Pulse 15 Gen2                | 1         | 0.29%   |
| TUXEDO N13xWU                       | 1         | 0.29%   |
| TUXEDO InfinityBook S 15 Gen6       | 1         | 0.29%   |
| TUXEDO InfinityBook Pro 14 Gen6     | 1         | 0.29%   |
| TUXEDO Aura 15 Gen1                 | 1         | 0.29%   |
| TULPAR A5 V20.3                     | 1         | 0.29%   |
| Toshiba Satellite Pro L40           | 1         | 0.29%   |
| Toshiba Satellite C70-B             | 1         | 0.29%   |
| Tactus GeoFlex 110                  | 1         | 0.29%   |
| Tactus GeoBook 140                  | 1         | 0.29%   |
| System76 Pangolin                   | 1         | 0.29%   |
| Sony VPCM12M1E                      | 1         | 0.29%   |
| Sony VPCEJ1E1E                      | 1         | 0.29%   |
| Sony VGN-SZ3VWP_X                   | 1         | 0.29%   |
| Shuttle DS77U                       | 1         | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 94        | 27.73%  |
| Dell Latitude          | 25        | 7.37%   |
| Unknown                | 16        | 4.72%   |
| Deciso NetBoard-A10    | 14        | 4.13%   |
| Fujitsu LIFEBOOK       | 12        | 3.54%   |
| Lenovo IdeaPad         | 6         | 1.77%   |
| HP EliteBook           | 6         | 1.77%   |
| Deciso Netboard        | 6         | 1.77%   |
| Acer Aspire            | 6         | 1.77%   |
| TUXEDO Pulse           | 5         | 1.47%   |
| Deciso NetBoard-A20    | 5         | 1.47%   |
| Dell XPS               | 4         | 1.18%   |
| Dell Inspiron          | 4         | 1.18%   |
| Deciso DEC2700         | 4         | 1.18%   |
| Apple MacBookAir5      | 4         | 1.18%   |
| Lenovo Legion          | 3         | 0.88%   |
| HP Laptop              | 3         | 0.88%   |
| Dell Precision         | 3         | 0.88%   |
| Acer TravelMate        | 3         | 0.88%   |
| TUXEDO InfinityBook    | 2         | 0.59%   |
| Toshiba Satellite      | 2         | 0.59%   |
| Shuttle DS437          | 2         | 0.59%   |
| Lenovo ThinkBook       | 2         | 0.59%   |
| IBM ThinkPad           | 2         | 0.59%   |
| HP ZBook               | 2         | 0.59%   |
| HP ProBook             | 2         | 0.59%   |
| HP Compaq              | 2         | 0.59%   |
| HP 255                 | 2         | 0.59%   |
| Gigabyte GB-BSi5A-6200 | 2         | 0.59%   |
| BESSTAR Tech U820      | 2         | 0.59%   |
| ASUS TUF               | 2         | 0.59%   |
| Apple MacBookPro8      | 2         | 0.59%   |
| Apple MacBookPro11     | 2         | 0.59%   |
| Apple MacBookAir7      | 2         | 0.59%   |
| Apple MacBookAir4      | 2         | 0.59%   |
| Apple MacBook5         | 2         | 0.59%   |
| Acer Swift             | 2         | 0.59%   |
| Acer Extensa           | 2         | 0.59%   |
| Wortmann AG TERRA      | 1         | 0.29%   |
| TUXEDO N13xWU          | 1         | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 42        | 12.39%  |
| 2019    | 29        | 8.55%   |
| 2020    | 28        | 8.26%   |
| 2022    | 24        | 7.08%   |
| 2017    | 23        | 6.78%   |
| 2016    | 23        | 6.78%   |
| 2011    | 23        | 6.78%   |
| 2013    | 22        | 6.49%   |
| 2018    | 20        | 5.9%    |
| 2012    | 17        | 5.01%   |
| 2010    | 17        | 5.01%   |
| 2015    | 16        | 4.72%   |
| 2014    | 16        | 4.72%   |
| 2008    | 11        | 3.24%   |
| 2023    | 7         | 2.06%   |
| 2009    | 7         | 2.06%   |
| 2007    | 5         | 1.47%   |
| Unknown | 3         | 0.88%   |
| 2003    | 2         | 0.59%   |
| 2024    | 1         | 0.29%   |
| 2006    | 1         | 0.29%   |
| 2005    | 1         | 0.29%   |
| 2002    | 1         | 0.29%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 339       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 336       | 99.12%  |
| Yes  | 3         | 0.88%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 128       | 37.54%  |
| 16.01-24.0  | 88        | 25.81%  |
| 4.01-8.0    | 63        | 18.48%  |
| 32.01-64.0  | 25        | 7.33%   |
| 2.01-3.0    | 15        | 4.4%    |
| 3.01-4.0    | 6         | 1.76%   |
| 64.01-256.0 | 4         | 1.17%   |
| 24.01-32.0  | 3         | 0.88%   |
| 1.01-2.0    | 3         | 0.88%   |
| 0.51-1.0    | 3         | 0.88%   |
| 0.01-0.5    | 2         | 0.59%   |
| 0           | 1         | 0.29%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 195       | 56.36%  |
| 0.51-1.0   | 98        | 28.32%  |
| 1.01-2.0   | 31        | 8.96%   |
| 2.01-3.0   | 8         | 2.31%   |
| 4.01-8.0   | 6         | 1.73%   |
| Unknown    | 4         | 1.16%   |
| 0          | 2         | 0.58%   |
| 24.01-32.0 | 1         | 0.29%   |
| 16.01-24.0 | 1         | 0.29%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 245       | 70.61%  |
| 2      | 66        | 19.02%  |
| 0      | 27        | 7.78%   |
| 3      | 9         | 2.59%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 252       | 73.9%   |
| Yes       | 89        | 26.1%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 303       | 89.38%  |
| No        | 36        | 10.62%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 283       | 83.24%  |
| No        | 57        | 16.76%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 198       | 58.06%  |
| No        | 143       | 41.94%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Germany | 339       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Berlin            | 35        | 9.64%   |
| Munich            | 13        | 3.58%   |
| Frankfurt am Main | 13        | 3.58%   |
| Hamburg           | 9         | 2.48%   |
| Stuttgart         | 8         | 2.2%    |
| Nuremberg         | 7         | 1.93%   |
| Bedburg           | 6         | 1.65%   |
| Lübeck           | 5         | 1.38%   |
| Leipzig           | 5         | 1.38%   |
| Halle             | 5         | 1.38%   |
| Aachen            | 5         | 1.38%   |
| Essen             | 4         | 1.1%    |
| Cologne           | 4         | 1.1%    |
| Wuppertal         | 3         | 0.83%   |
| Wernigerode       | 3         | 0.83%   |
| Neuss             | 3         | 0.83%   |
| Münster          | 3         | 0.83%   |
| Markt Indersdorf  | 3         | 0.83%   |
| Ludwigsburg       | 3         | 0.83%   |
| Karlsruhe         | 3         | 0.83%   |
| Giessen           | 3         | 0.83%   |
| Darmstadt         | 3         | 0.83%   |
| Bonn              | 3         | 0.83%   |
| Blomberg          | 3         | 0.83%   |
| Bielefeld         | 3         | 0.83%   |
| Zwingenberg       | 2         | 0.55%   |
| Würzburg         | 2         | 0.55%   |
| Wissen            | 2         | 0.55%   |
| Reutlingen        | 2         | 0.55%   |
| Regensburg        | 2         | 0.55%   |
| Potsdam           | 2         | 0.55%   |
| Pleidelsheim      | 2         | 0.55%   |
| Oldenburg         | 2         | 0.55%   |
| Neuengors         | 2         | 0.55%   |
| Mainz             | 2         | 0.55%   |
| Lüneburg         | 2         | 0.55%   |
| Kornwestheim      | 2         | 0.55%   |
| Habichtswald      | 2         | 0.55%   |
| Gummersbach       | 2         | 0.55%   |
| Gifhorn           | 2         | 0.55%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 79        | 100    | 21.41%  |
| Transcend           | 40        | 50     | 10.84%  |
| WDC                 | 26        | 30     | 7.05%   |
| Crucial             | 25        | 31     | 6.78%   |
| SanDisk             | 23        | 25     | 6.23%   |
| Seagate             | 19        | 22     | 5.15%   |
| Kingston            | 17        | 20     | 4.61%   |
| Toshiba             | 16        | 36     | 4.34%   |
| NVMe                | 14        | 25     | 3.79%   |
| Intel               | 13        | 14     | 3.52%   |
| Apple               | 13        | 16     | 3.52%   |
| Intenso             | 11        | 12     | 2.98%   |
| Micron Technology   | 9         | 9      | 2.44%   |
| Hitachi             | 8         | 11     | 2.17%   |
| SK hynix            | 6         | 7      | 1.63%   |
| HGST                | 5         | 10     | 1.36%   |
| SPCC                | 4         | 5      | 1.08%   |
| OCZ                 | 4         | 7      | 1.08%   |
| KIOXIA              | 4         | 4      | 1.08%   |
| Hoodisk             | 4         | 4      | 1.08%   |
| Fujitsu             | 4         | 4      | 1.08%   |
| A-DATA Technology   | 3         | 4      | 0.81%   |
| PNY                 | 2         | 3      | 0.54%   |
| LITEON              | 2         | 2      | 0.54%   |
| Kston               | 2         | 2      | 0.54%   |
| Dogfish             | 2         | 2      | 0.54%   |
| Verbatim            | 1         | 3      | 0.27%   |
| Phison              | 1         | 1      | 0.27%   |
| Netac               | 1         | 1      | 0.27%   |
| MyDigitalSSD        | 1         | 1      | 0.27%   |
| Mushkin             | 1         | 1      | 0.27%   |
| Lenovo              | 1         | 1      | 0.27%   |
| Hewlett-Packard     | 1         | 1      | 0.27%   |
| Gigabyte Technology | 1         | 1      | 0.27%   |
| Generic             | 1         | 1      | 0.27%   |
| FORESEE             | 1         | 1      | 0.27%   |
| Corsair             | 1         | 1      | 0.27%   |
| China               | 1         | 1      | 0.27%   |
| BIWIN               | 1         | 1      | 0.27%   |
| 2-Power             | 1         | 1      | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Transcend TS256GMTE710T 256GB        | 10        | 2.61%   |
| Transcend TS256GMTE652T2 256GB       | 7         | 1.83%   |
| Transcend TS256GMTS952T2 256GB       | 6         | 1.57%   |
| Transcend TS128GMTE110S 128GB        | 5         | 1.31%   |
| Crucial CT1000MX500SSD1 1TB          | 5         | 1.31%   |
| Samsung SSD 860 EVO 500GB            | 4         | 1.04%   |
| Samsung SSD 850 EVO 500GB            | 4         | 1.04%   |
| Samsung SSD 850 EVO 250GB            | 4         | 1.04%   |
| Samsung SSD 840 EVO 250GB            | 4         | 1.04%   |
| Hoodisk SSD 128GB                    | 4         | 1.04%   |
| Apple SSD TS128E 121GB               | 4         | 1.04%   |
| Transcend TS240GMTS420S 240GB        | 3         | 0.78%   |
| SanDisk SSD PLUS 120GB               | 3         | 0.78%   |
| Samsung SSD 970 EVO Plus 1TB         | 3         | 0.78%   |
| Samsung SSD 860 EVO 250GB            | 3         | 0.78%   |
| NVMe Samsung SSD 980 1TB             | 3         | 0.78%   |
| Transcend TS64GSSD370S 64GB          | 2         | 0.52%   |
| Transcend TS512GMTS952T2 512GB       | 2         | 0.52%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB | 2         | 0.52%   |
| SPCC Solid State Disk 1TB            | 2         | 0.52%   |
| Seagate ST500LT012-1DG142 500GB      | 2         | 0.52%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 0.52%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 0.52%   |
| SanDisk SDSSDP064G 64GB              | 2         | 0.52%   |
| Samsung SSD 970 EVO Plus 250GB       | 2         | 0.52%   |
| Samsung SSD 970 EVO 500GB            | 2         | 0.52%   |
| Samsung SSD 870 EVO 250GB            | 2         | 0.52%   |
| Samsung SSD 840 PRO Series 256GB     | 2         | 0.52%   |
| Samsung SSD 840 EVO 120GB            | 2         | 0.52%   |
| Samsung PM9A1 NVMe 512GB             | 2         | 0.52%   |
| Samsung MZYLF128HCHP-000L2 128GB     | 2         | 0.52%   |
| Samsung MZVLB512HAJQ-000L7 512GB     | 2         | 0.52%   |
| Samsung MZALQ512HALU-000L2 512GB     | 2         | 0.52%   |
| Samsung MZ7LN256HCHP-000L7 256GB     | 2         | 0.52%   |
| NVMe WDC PC SN730 SDB 512GB          | 2         | 0.52%   |
| NVMe SAMSUNG MZVLW256 256GB          | 2         | 0.52%   |
| Micron 2200V_MTFDHBA512TCK 512GB     | 2         | 0.52%   |
| LITEON LCH-128V2S 128GB              | 2         | 0.52%   |
| Kingston SV300S37A240G 240GB         | 2         | 0.52%   |
| Kingston SA400S37480G 480GB          | 2         | 0.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 22     | 25.68%  |
| WDC                 | 17        | 20     | 22.97%  |
| NVMe                | 10        | 20     | 13.51%  |
| Hitachi             | 8         | 11     | 10.81%  |
| Toshiba             | 7         | 8      | 9.46%   |
| HGST                | 5         | 10     | 6.76%   |
| Fujitsu             | 4         | 4      | 5.41%   |
| Samsung Electronics | 2         | 2      | 2.7%    |
| Generic             | 1         | 1      | 1.35%   |
| Apple               | 1         | 1      | 1.35%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 53        | 63     | 24.88%  |
| SanDisk             | 23        | 25     | 10.8%   |
| Crucial             | 21        | 27     | 9.86%   |
| Transcend           | 18        | 24     | 8.45%   |
| Kingston            | 13        | 16     | 6.1%    |
| Intel               | 12        | 13     | 5.63%   |
| Apple               | 12        | 15     | 5.63%   |
| Intenso             | 11        | 12     | 5.16%   |
| Toshiba             | 5         | 11     | 2.35%   |
| WDC                 | 4         | 4      | 1.88%   |
| SK hynix            | 4         | 5      | 1.88%   |
| OCZ                 | 4         | 7      | 1.88%   |
| Micron Technology   | 4         | 4      | 1.88%   |
| Hoodisk             | 4         | 4      | 1.88%   |
| SPCC                | 3         | 3      | 1.41%   |
| NVMe                | 3         | 3      | 1.41%   |
| PNY                 | 2         | 3      | 0.94%   |
| LITEON              | 2         | 2      | 0.94%   |
| Kston               | 2         | 2      | 0.94%   |
| Dogfish             | 2         | 2      | 0.94%   |
| A-DATA Technology   | 2         | 2      | 0.94%   |
| Verbatim            | 1         | 3      | 0.47%   |
| Netac               | 1         | 1      | 0.47%   |
| MyDigitalSSD        | 1         | 1      | 0.47%   |
| Mushkin             | 1         | 1      | 0.47%   |
| Hewlett-Packard     | 1         | 1      | 0.47%   |
| FORESEE             | 1         | 1      | 0.47%   |
| Corsair             | 1         | 1      | 0.47%   |
| China               | 1         | 1      | 0.47%   |
| 2-Power             | 1         | 1      | 0.47%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 191       | 258    | 55.85%  |
| NVMe | 81        | 114    | 23.68%  |
| HDD  | 70        | 99     | 20.47%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 247       | 357    | 75.3%   |
| NVMe | 81        | 114    | 24.7%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 209       | 280    | 79.17%  |
| 0.51-1.0   | 37        | 48     | 14.02%  |
| 1.01-2.0   | 16        | 27     | 6.06%   |
| 3.01-4.0   | 1         | 1      | 0.38%   |
| 4.01-10.0  | 1         | 1      | 0.38%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 128       | 36.16%  |
| 1-20           | 80        | 22.6%   |
| 251-500        | 67        | 18.93%  |
| 51-100         | 29        | 8.19%   |
| 501-1000       | 25        | 7.06%   |
| 21-50          | 14        | 3.95%   |
| 1001-2000      | 7         | 1.98%   |
| Unknown        | 3         | 0.85%   |
| More than 3000 | 1         | 0.28%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 289       | 81.64%  |
| 21-50          | 28        | 7.91%   |
| 101-250        | 14        | 3.95%   |
| 51-100         | 14        | 3.95%   |
| 251-500        | 4         | 1.13%   |
| Unknown        | 3         | 0.85%   |
| More than 3000 | 1         | 0.28%   |
| 501-1000       | 1         | 0.28%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Toshiba THNSNK256GVN8 M.2 2280 256GB         | 2         | 8      | 6.06%   |
| Hitachi HTS545032B9A300 320GB                | 2         | 4      | 6.06%   |
| Hitachi HTS543225L9A300 250GB                | 2         | 2      | 6.06%   |
| HGST HTS541010A9E680 1TB                     | 2         | 3      | 6.06%   |
| WDC WD3200BEVT-22ZCT0 320GB                  | 1         | 1      | 3.03%   |
| WDC WD1600BEVS-07RST0 160GB                  | 1         | 1      | 3.03%   |
| WDC WD10SPZX-21Z10T0 1TB                     | 1         | 1      | 3.03%   |
| Toshiba MQ01ABD050 500GB                     | 1         | 1      | 3.03%   |
| Toshiba MK2018GAP 20GB                       | 1         | 1      | 3.03%   |
| SK hynix HFS256G39MND-2300A 256GB            | 1         | 1      | 3.03%   |
| Seagate ST9500420AS 500GB                    | 1         | 1      | 3.03%   |
| Seagate ST9320325AS 320GB                    | 1         | 1      | 3.03%   |
| Seagate ST9250410AS 250GB                    | 1         | 1      | 3.03%   |
| Seagate ST500LT012-1DG142 500GB              | 1         | 1      | 3.03%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 1      | 3.03%   |
| SanDisk SSD PLUS 480GB                       | 1         | 1      | 3.03%   |
| SanDisk SSD P4 64GB                          | 1         | 1      | 3.03%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 2      | 3.03%   |
| Micron Technology 1100 SATA 256GB            | 1         | 1      | 3.03%   |
| Kingston SV300S37A240G 240GB                 | 1         | 1      | 3.03%   |
| Kingston SNV425S264GB                        | 1         | 1      | 3.03%   |
| Intel SSDSC2KF256H6L 256GB                   | 1         | 1      | 3.03%   |
| Intel SSDSC2BF180A4L 180GB                   | 1         | 1      | 3.03%   |
| Hitachi HTS548040M9AT00 37GB                 | 1         | 1      | 3.03%   |
| Hitachi HTS545025B9SA02 250GB                | 1         | 2      | 3.03%   |
| Fujitsu MHW2160BH 160GB                      | 1         | 1      | 3.03%   |
| Crucial CT1000P1SSD8 1TB                     | 1         | 1      | 3.03%   |
| Corsair Force GT 120GB                       | 1         | 1      | 3.03%   |
| Apple SSD SM128C 121GB                       | 1         | 1      | 3.03%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 6         | 9      | 18.18%  |
| Seagate             | 5         | 5      | 15.15%  |
| Toshiba             | 4         | 10     | 12.12%  |
| WDC                 | 3         | 3      | 9.09%   |
| SanDisk             | 2         | 2      | 6.06%   |
| Kingston            | 2         | 2      | 6.06%   |
| Intel               | 2         | 2      | 6.06%   |
| HGST                | 2         | 3      | 6.06%   |
| SK hynix            | 1         | 1      | 3.03%   |
| Samsung Electronics | 1         | 2      | 3.03%   |
| Micron Technology   | 1         | 1      | 3.03%   |
| Fujitsu             | 1         | 1      | 3.03%   |
| Crucial             | 1         | 1      | 3.03%   |
| Corsair             | 1         | 1      | 3.03%   |
| Apple               | 1         | 1      | 3.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 6         | 9      | 31.58%  |
| Seagate | 5         | 5      | 26.32%  |
| WDC     | 3         | 3      | 15.79%  |
| Toshiba | 2         | 2      | 10.53%  |
| HGST    | 2         | 3      | 10.53%  |
| Fujitsu | 1         | 1      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 19        | 23     | 57.58%  |
| SSD  | 13        | 20     | 39.39%  |
| NVMe | 1         | 1      | 3.03%   |

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
| Works    | 281       | 402    | 85.41%  |
| Malfunc  | 33        | 44     | 10.03%  |
| Detected | 15        | 25     | 4.56%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 230       | 59.74%  |
| Samsung Electronics              | 46        | 11.95%  |
| AMD                              | 25        | 6.49%   |
| Transcend                        | 22        | 5.71%   |
| SanDisk                          | 12        | 3.12%   |
| Micron Technology                | 7         | 1.82%   |
| Toshiba                          | 6         | 1.56%   |
| Kingston Technology Company      | 6         | 1.56%   |
| Nvidia                           | 5         | 1.3%    |
| SK hynix                         | 4         | 1.04%   |
| Phison Electronics               | 4         | 1.04%   |
| Micron/Crucial Technology        | 4         | 1.04%   |
| KIOXIA                           | 3         | 0.78%   |
| ADATA Technology                 | 3         | 0.78%   |
| Silicon Motion                   | 2         | 0.52%   |
| Marvell Technology Group         | 2         | 0.52%   |
| ULi Electronics                  | 1         | 0.26%   |
| Silicon Integrated Systems [SiS] | 1         | 0.26%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.26%   |
| Lenovo                           | 1         | 0.26%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 31        | 7.6%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 28        | 6.86%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 26        | 6.37%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 25        | 6.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 22        | 5.39%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 18        | 4.41%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 14        | 3.43%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 13        | 3.19%   |
| Transcend NVMe PCIe SSD 110S/112S/120S/MTE300S/MTE400S/MTE652T2 (DRAM-less)            | 12        | 2.94%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 11        | 2.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 11        | 2.7%    |
| Transcend NVMe PCIe SSD 240S/MTE710T                                                   | 10        | 2.45%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 10        | 2.45%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 10        | 2.45%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 9         | 2.21%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 7         | 1.72%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 7         | 1.72%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                   | 5         | 1.23%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                             | 5         | 1.23%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 5         | 1.23%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                            | 5         | 1.23%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 5         | 1.23%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 5         | 1.23%   |
| Nvidia MCP79 AHCI Controller                                                           | 4         | 0.98%   |
| Toshiba XG5 NVMe SSD Controller                                                        | 3         | 0.74%   |
| Phison E12 NVMe Controller                                                             | 3         | 0.74%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                            | 3         | 0.74%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                             | 3         | 0.74%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 3         | 0.74%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 3         | 0.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 3         | 0.74%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 3         | 0.74%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 3         | 0.74%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 3         | 0.74%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 3         | 0.74%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 3         | 0.74%   |
| Toshiba XG6 NVMe SSD Controller                                                        | 2         | 0.49%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                                     | 2         | 0.49%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                                  | 2         | 0.49%   |
| Micron 2200S NVMe SSD [Cassandra]                                                      | 2         | 0.49%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 243       | 62.63%  |
| NVMe | 105       | 27.06%  |
| IDE  | 32        | 8.25%   |
| RAID | 8         | 2.06%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 276       | 81.42%  |
| AMD     | 62        | 18.29%  |
| PowerPC | 1         | 0.29%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| AMD Ryzen Embedded V1500B               | 19        | 5.57%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 11        | 3.23%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 10        | 2.93%   |
| AMD EPYC 3201 8-Core Processor          | 8         | 2.35%   |
| Intel CPU Version                       | 7         | 2.05%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 7         | 2.05%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 7         | 2.05%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 7         | 2.05%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 6         | 1.76%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 6         | 1.76%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 6         | 1.76%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 5         | 1.47%   |
| Intel Core i5-3317U CPU @ 1.70GHz       | 5         | 1.47%   |
| Intel Core i3-4005U CPU @ 1.70GHz       | 5         | 1.47%   |
| Intel Core 2 Duo                        | 5         | 1.47%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 5         | 1.47%   |
| Intel Core i5-4250U CPU @ 1.30GHz       | 4         | 1.17%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 4         | 1.17%   |
| Intel Core i5 CPU M 560 @ 2.67GHz       | 4         | 1.17%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 4         | 1.17%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 3         | 0.88%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 3         | 0.88%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 3         | 0.88%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 3         | 0.88%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 3         | 0.88%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 3         | 0.88%   |
| Intel Celeron CPU 1037U @ 1.80GHz       | 3         | 0.88%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 3         | 0.88%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 3         | 0.88%   |
| AMD EPYC 3101 4-Core Processor          | 3         | 0.88%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz    | 2         | 0.59%   |
| Intel Pentium 3558U @ 1.70GHz           | 2         | 0.59%   |
| Intel Genuine CPU                       | 2         | 0.59%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 2         | 0.59%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 2         | 0.59%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 2         | 0.59%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz      | 2         | 0.59%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz      | 2         | 0.59%   |
| Intel Core i7-4610M CPU @ 3.00GHz       | 2         | 0.59%   |
| Intel Core i7-2860QM CPU @ 2.50GHz      | 2         | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 111       | 32.74%  |
| Intel Core i7        | 63        | 18.58%  |
| Other                | 24        | 7.08%   |
| Intel Core 2 Duo     | 20        | 5.9%    |
| AMD Ryzen Embedded   | 19        | 5.6%    |
| Intel Core i3        | 15        | 4.42%   |
| Intel Celeron        | 15        | 4.42%   |
| AMD Ryzen 7          | 14        | 4.13%   |
| AMD EPYC             | 11        | 3.24%   |
| AMD Ryzen 5          | 9         | 2.65%   |
| Intel Pentium        | 7         | 2.06%   |
| Intel Atom           | 5         | 1.47%   |
| Intel Xeon           | 3         | 0.88%   |
| Intel Pentium M      | 3         | 0.88%   |
| Intel Genuine        | 3         | 0.88%   |
| AMD Ryzen 7 PRO      | 3         | 0.88%   |
| Intel Pentium Silver | 2         | 0.59%   |
| Intel Core m3        | 2         | 0.59%   |
| Intel Pentium Dual   | 1         | 0.29%   |
| Intel Pentium 4      | 1         | 0.29%   |
| Intel Core M         | 1         | 0.29%   |
| Intel Core 2 Solo    | 1         | 0.29%   |
| Intel Core 2         | 1         | 0.29%   |
| Intel Celeron M      | 1         | 0.29%   |
| AMD Ryzen 5 PRO      | 1         | 0.29%   |
| AMD GX               | 1         | 0.29%   |
| AMD E2               | 1         | 0.29%   |
| AMD A6               | 1         | 0.29%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 164       | 48.24%  |
| 4       | 79        | 23.24%  |
| 8       | 33        | 9.71%   |
| Unknown | 23        | 6.76%   |
| 16      | 15        | 4.41%   |
| 1       | 10        | 2.94%   |
| 12      | 7         | 2.06%   |
| 6       | 7         | 2.06%   |
| 10      | 2         | 0.59%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 327       | 96.18%  |
| 2       | 7         | 2.06%   |
| Unknown | 6         | 1.76%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 211       | 62.24%  |
| 1       | 97        | 28.61%  |
| Unknown | 31        | 9.14%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 49        | 14.41%  |
| Haswell       | 38        | 11.18%  |
| IvyBridge     | 33        | 9.71%   |
| Zen           | 31        | 9.12%   |
| SandyBridge   | 31        | 9.12%   |
| Skylake       | 22        | 6.47%   |
| Penryn        | 22        | 6.47%   |
| Unknown       | 21        | 6.18%   |
| Broadwell     | 19        | 5.59%   |
| Westmere      | 10        | 2.94%   |
| TigerLake     | 9         | 2.65%   |
| Core          | 9         | 2.65%   |
| Zen 2         | 7         | 2.06%   |
| Silvermont    | 7         | 2.06%   |
| Bonnell       | 5         | 1.47%   |
| Zen+          | 4         | 1.18%   |
| Zen 3         | 4         | 1.18%   |
| P6            | 4         | 1.18%   |
| Goldmont plus | 3         | 0.88%   |
| Goldmont      | 3         | 0.88%   |
| Puma          | 2         | 0.59%   |
| NetBurst      | 2         | 0.59%   |
| Piledriver    | 1         | 0.29%   |
| IceLake       | 1         | 0.29%   |
| Geode         | 1         | 0.29%   |
| CometLake     | 1         | 0.29%   |
| Bobcat        | 1         | 0.29%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 250       | 71.23%  |
| Nvidia                           | 59        | 16.81%  |
| AMD                              | 40        | 11.4%   |
| Trident Microsystems             | 1         | 0.28%   |
| Silicon Integrated Systems [SiS] | 1         | 0.28%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 33        | 9.04%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 29        | 7.95%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 25        | 6.85%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 19        | 5.21%   |
| Intel HD Graphics 5500                                                                   | 14        | 3.84%   |
| Intel UHD Graphics 620                                                                   | 12        | 3.29%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 12        | 3.29%   |
| Intel Core Processor Integrated Graphics Controller                                      | 11        | 3.01%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 10        | 2.74%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 2.47%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 9         | 2.47%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 8         | 2.19%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 8         | 2.19%   |
| Intel HD Graphics 620                                                                    | 8         | 2.19%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 7         | 1.92%   |
| AMD Lucienne                                                                             | 7         | 1.92%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 1.64%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 5         | 1.37%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 1.37%   |
| Nvidia C79 [GeForce 9400M]                                                               | 4         | 1.1%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 1.1%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 1.1%    |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 0.82%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                    | 3         | 0.82%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 0.82%   |
| Intel HD Graphics 6000                                                                   | 3         | 0.82%   |
| Intel HD Graphics 500                                                                    | 3         | 0.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 0.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 0.82%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 0.82%   |
| AMD Mars XTX [Radeon HD 8790M]                                                           | 3         | 0.82%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.55%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.55%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 2         | 0.55%   |
| Nvidia G98M [Quadro NVS 160M]                                                            | 2         | 0.55%   |
| Nvidia G84M [GeForce 8600M GT]                                                           | 2         | 0.55%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 0.55%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.55%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 0.55%   |
| Intel HD Graphics P630                                                                   | 2         | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 184       | 54.12%  |
| Other                    | 32        | 9.41%   |
| Intel + Nvidia           | 32        | 9.41%   |
| 1 x AMD                  | 28        | 8.24%   |
| 2 x Intel                | 26        | 7.65%   |
| 1 x Nvidia               | 24        | 7.06%   |
| Intel + AMD              | 8         | 2.35%   |
| AMD + Nvidia             | 4         | 1.18%   |
| 1 x Trident Microsystems | 1         | 0.29%   |
| 1 x SiS                  | 1         | 0.29%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 277       | 80.52%  |
| Unknown     | 47        | 13.66%  |
| Proprietary | 20        | 5.81%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 318       | 92.71%  |
| 0.01-0.5   | 12        | 3.5%    |
| 7.01-8.0   | 4         | 1.17%   |
| 3.01-4.0   | 4         | 1.17%   |
| 1.01-2.0   | 4         | 1.17%   |
| 5.01-6.0   | 1         | 0.29%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| LG Display           | 41        | 20%     |
| AU Optronics         | 37        | 18.05%  |
| Chimei Innolux       | 20        | 9.76%   |
| BOE                  | 17        | 8.29%   |
| Apple                | 17        | 8.29%   |
| Samsung Electronics  | 15        | 7.32%   |
| Lenovo               | 12        | 5.85%   |
| Sharp                | 6         | 2.93%   |
| Dell                 | 6         | 2.93%   |
| InfoVision           | 4         | 1.95%   |
| Goldstar             | 4         | 1.95%   |
| PANDA                | 3         | 1.46%   |
| AOC                  | 3         | 1.46%   |
| Unknown              | 3         | 1.46%   |
| LG Philips           | 2         | 0.98%   |
| Iiyama               | 2         | 0.98%   |
| BenQ                 | 2         | 0.98%   |
| Ancor Communications | 2         | 0.98%   |
| TRU                  | 1         | 0.49%   |
| Toshiba              | 1         | 0.49%   |
| Quanta Display       | 1         | 0.49%   |
| Panasonic            | 1         | 0.49%   |
| LTM                  | 1         | 0.49%   |
| JDI                  | 1         | 0.49%   |
| Hewlett-Packard      | 1         | 0.49%   |
| Eizo                 | 1         | 0.49%   |
| CSO                  | 1         | 0.49%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                 | 5         | 2.4%    |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch       | 4         | 1.92%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch | 3         | 1.44%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch          | 3         | 1.44%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch              | 3         | 1.44%   |
| BOE LCD Monitor BOE05E0 1366x768 280x160mm 12.7-inch                 | 3         | 1.44%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch       | 3         | 1.44%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch        | 3         | 1.44%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch        | 3         | 1.44%   |
| Unknown                                                              | 3         | 1.44%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 290x170mm 13.2-inch              | 2         | 0.96%   |
| PANDA LCD Monitor NCP002D 1920x1080 340x190mm 15.3-inch              | 2         | 0.96%   |
| LG Display LCD Monitor LGD057E 1920x1080 340x190mm 15.3-inch         | 2         | 0.96%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch         | 2         | 0.96%   |
| LG Display LCD Monitor LGD04A3 1366x768 280x160mm 12.7-inch          | 2         | 0.96%   |
| LG Display LCD Monitor LGD046F 1920x1080 350x190mm 15.7-inch         | 2         | 0.96%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch         | 2         | 0.96%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch          | 2         | 0.96%   |
| LG Display LCD Monitor LGD0353 1366x768 350x190mm 15.7-inch          | 2         | 0.96%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch             | 2         | 0.96%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch              | 2         | 0.96%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch     | 2         | 0.96%   |
| BOE LCD Monitor BOE0900 1920x1080 340x190mm 15.3-inch                | 2         | 0.96%   |
| BOE LCD Monitor BOE08EE 1920x1080 310x170mm 13.9-inch                | 2         | 0.96%   |
| AU Optronics LCD Monitor AUO8074 1280x800 330x210mm 15.4-inch        | 2         | 0.96%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 340x190mm 15.3-inch       | 2         | 0.96%   |
| Apple Color LCD APPA020 2560x1600 290x180mm 13.4-inch                | 2         | 0.96%   |
| Apple Color LCD APPA01B 1440x900 290x180mm 13.4-inch                 | 2         | 0.96%   |
| TRU LCD Monitor TRU235C 1366x768 260x140mm 11.6-inch                 | 1         | 0.48%   |
| Toshiba TV TSB0108 1360x768 890x500mm 40.2-inch                      | 1         | 0.48%   |
| Sharp LCD Monitor SHP14F9 1920x1200 290x180mm 13.4-inch              | 1         | 0.48%   |
| Sharp LCD Monitor SHP14BA 1920x1080 340x190mm 15.3-inch              | 1         | 0.48%   |
| Sharp LCD Monitor SHP143A 3840x2160 350x190mm 15.7-inch              | 1         | 0.48%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch              | 1         | 0.48%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch    | 1         | 0.48%   |
| Samsung Electronics S27C36x SAM7315 1920x1080 600x340mm 27.2-inch    | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC504B 1600x900 380x210mm 17.1-inch | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC3245 1280x800 330x210mm 15.4-inch | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC3157 1440x900 330x210mm 15.4-inch | 1         | 0.48%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 74        | 36.27%  |
| 1366x768 (WXGA)    | 56        | 27.45%  |
| 1280x800 (WXGA)    | 13        | 6.37%   |
| 3840x2160 (4K)     | 11        | 5.39%   |
| 1600x900 (HD+)     | 10        | 4.9%    |
| 2560x1440 (QHD)    | 8         | 3.92%   |
| 1440x900 (WXGA+)   | 8         | 3.92%   |
| 1920x1200 (WUXGA)  | 6         | 2.94%   |
| 2560x1600          | 4         | 1.96%   |
| 3200x1800 (QHD+)   | 2         | 0.98%   |
| 2880x1800          | 2         | 0.98%   |
| 1680x1050 (WSXGA+) | 2         | 0.98%   |
| 1024x768 (XGA)     | 2         | 0.98%   |
| 9600x2160          | 1         | 0.49%   |
| 720x1280           | 1         | 0.49%   |
| 3000x2000          | 1         | 0.49%   |
| 2560x1080          | 1         | 0.49%   |
| 1920x540           | 1         | 0.49%   |
| 1280x1024 (SXGA)   | 1         | 0.49%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 13      | 64        | 31.22%  |
| 15      | 58        | 28.29%  |
| 12      | 29        | 14.15%  |
| 11      | 9         | 4.39%   |
| 17      | 8         | 3.9%    |
| 14      | 8         | 3.9%    |
| 27      | 7         | 3.41%   |
| 24      | 7         | 3.41%   |
| Unknown | 6         | 2.93%   |
| 23      | 3         | 1.46%   |
| 40      | 1         | 0.49%   |
| 39      | 1         | 0.49%   |
| 34      | 1         | 0.49%   |
| 32      | 1         | 0.49%   |
| 26      | 1         | 0.49%   |
| 6       | 1         | 0.49%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 99        | 48.53%  |
| 201-300     | 69        | 33.82%  |
| 501-600     | 16        | 7.84%   |
| 351-400     | 7         | 3.43%   |
| Unknown     | 6         | 2.94%   |
| 801-900     | 2         | 0.98%   |
| 701-800     | 2         | 0.98%   |
| 601-700     | 1         | 0.49%   |
| 401-500     | 1         | 0.49%   |
| 101-200     | 1         | 0.49%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 151       | 76.65%  |
| 16/10   | 33        | 16.75%  |
| Unknown | 6         | 3.05%   |
| 4/3     | 3         | 1.52%   |
| 3/2     | 2         | 1.02%   |
| 5/4     | 1         | 0.51%   |
| 21/9    | 1         | 0.51%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 59        | 28.64%  |
| 91-100         | 38        | 18.45%  |
| 61-70          | 29        | 14.08%  |
| 101-110        | 21        | 10.19%  |
| 71-80          | 12        | 5.83%   |
| 51-60          | 9         | 4.37%   |
| 301-350        | 8         | 3.88%   |
| 201-250        | 7         | 3.4%    |
| 121-130        | 7         | 3.4%    |
| Unknown        | 6         | 2.91%   |
| 251-300        | 4         | 1.94%   |
| 351-500        | 2         | 0.97%   |
| 501-1000       | 2         | 0.97%   |
| 1-40           | 1         | 0.49%   |
| 141-150        | 1         | 0.49%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 99        | 49.01%  |
| 101-120       | 37        | 18.32%  |
| 161-240       | 24        | 11.88%  |
| 51-100        | 24        | 11.88%  |
| More than 240 | 11        | 5.45%   |
| Unknown       | 6         | 2.97%   |
| 1-50          | 1         | 0.5%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 194       | 56.23%  |
| 0     | 133       | 38.55%  |
| 2     | 17        | 4.93%   |
| 3     | 1         | 0.29%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 250       | 46.47%  |
| Realtek Semiconductor             | 106       | 19.7%   |
| Broadcom                          | 42        | 7.81%   |
| Qualcomm Atheros                  | 36        | 6.69%   |
| AMD                               | 30        | 5.58%   |
| Ericsson Business Mobile Networks | 12        | 2.23%   |
| Sierra Wireless                   | 10        | 1.86%   |
| Ralink Technology                 | 7         | 1.3%    |
| Edimax Technology                 | 6         | 1.12%   |
| Nvidia                            | 5         | 0.93%   |
| Google                            | 5         | 0.93%   |
| Marvell Technology Group          | 4         | 0.74%   |
| ASUSTek Computer                  | 3         | 0.56%   |
| TP-Link                           | 2         | 0.37%   |
| Ralink                            | 2         | 0.37%   |
| Qualcomm Technologies             | 2         | 0.37%   |
| MediaTek                          | 2         | 0.37%   |
| Hewlett-Packard                   | 2         | 0.37%   |
| Dell                              | 2         | 0.37%   |
| ULi Electronics                   | 1         | 0.19%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.19%   |
| Samsung Electronics               | 1         | 0.19%   |
| National Semiconductor            | 1         | 0.19%   |
| Micro Star International          | 1         | 0.19%   |
| JMicron Technology                | 1         | 0.19%   |
| Huawei Technologies               | 1         | 0.19%   |
| D-Link System                     | 1         | 0.19%   |
| Aquantia                          | 1         | 0.19%   |
| Apple                             | 1         | 0.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller      | 81        | 11.81%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 35        | 5.1%    |
| AMD XGMAC 10GbE Controller                                                  | 30        | 4.37%   |
| Intel I210 Gigabit Network Connection                                       | 24        | 3.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 23        | 3.35%   |
| Intel Wireless 7265                                                         | 18        | 2.62%   |
| Intel Wireless 8260                                                         | 17        | 2.48%   |
| Intel Wi-Fi 6 AX200                                                         | 16        | 2.33%   |
| Intel Wireless 8265 / 8275                                                  | 15        | 2.19%   |
| Intel I211 Gigabit Network Connection                                       | 15        | 2.19%   |
| Intel Centrino Ultimate-N 6300                                              | 15        | 2.19%   |
| Intel Ethernet Connection I219-LM                                           | 14        | 2.04%   |
| Intel Wireless 7260                                                         | 12        | 1.75%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 11        | 1.6%    |
| Intel Ethernet Connection I217-LM                                           | 9         | 1.31%   |
| Intel Ethernet Connection (3) I218-LM                                       | 9         | 1.31%   |
| Intel 82577LM Gigabit Network Connection                                    | 9         | 1.31%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 8         | 1.17%   |
| Intel Wi-Fi 6 AX201                                                         | 8         | 1.17%   |
| Broadcom BCM43224 802.11a/b/g/n                                             | 8         | 1.17%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                   | 7         | 1.02%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III | 7         | 1.02%   |
| Sierra Wireless EM7455                                                      | 6         | 0.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 6         | 0.87%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 6         | 0.87%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 6         | 0.87%   |
| Intel Ethernet Controller I225-V                                            | 6         | 0.87%   |
| Intel Ethernet Connection (4) I219-LM                                       | 6         | 0.87%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 5         | 0.73%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                     | 5         | 0.73%   |
| Intel Ethernet Connection (4) I219-V                                        | 5         | 0.73%   |
| Intel Centrino Advanced-N 6200                                              | 5         | 0.73%   |
| Google Nexus/Pixel Device (tether)                                          | 5         | 0.73%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                | 5         | 0.73%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 4         | 0.58%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                  | 4         | 0.58%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 4         | 0.58%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                            | 4         | 0.58%   |
| Nvidia MCP79 Ethernet                                                       | 4         | 0.58%   |
| Intel Wireless 3165                                                         | 4         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 194       | 61.39%  |
| Qualcomm Atheros         | 31        | 9.81%   |
| Broadcom                 | 31        | 9.81%   |
| Realtek Semiconductor    | 28        | 8.86%   |
| Sierra Wireless          | 7         | 2.22%   |
| Ralink Technology        | 7         | 2.22%   |
| Edimax Technology        | 6         | 1.9%    |
| ASUSTek Computer         | 3         | 0.95%   |
| TP-Link                  | 2         | 0.63%   |
| Ralink                   | 2         | 0.63%   |
| Qualcomm Technologies    | 2         | 0.63%   |
| MediaTek                 | 2         | 0.63%   |
| Micro Star International | 1         | 0.32%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 23        | 7.21%   |
| Intel Wireless 7265                                            | 18        | 5.64%   |
| Intel Wireless 8260                                            | 17        | 5.33%   |
| Intel Wi-Fi 6 AX200                                            | 16        | 5.02%   |
| Intel Wireless 8265 / 8275                                     | 15        | 4.7%    |
| Intel Centrino Ultimate-N 6300                                 | 15        | 4.7%    |
| Intel Wireless 7260                                            | 12        | 3.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 8         | 2.51%   |
| Intel Wi-Fi 6 AX201                                            | 8         | 2.51%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 8         | 2.51%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 7         | 2.19%   |
| Sierra Wireless EM7455                                         | 6         | 1.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 6         | 1.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6         | 1.88%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 6         | 1.88%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 5         | 1.57%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 5         | 1.57%   |
| Intel Centrino Advanced-N 6200                                 | 5         | 1.57%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 5         | 1.57%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 4         | 1.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4         | 1.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4         | 1.25%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 4         | 1.25%   |
| Intel Wireless 3165                                            | 4         | 1.25%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 4         | 1.25%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 4         | 1.25%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 4         | 1.25%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 4         | 1.25%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 4         | 1.25%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 3         | 0.94%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 3         | 0.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 0.94%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 3         | 0.94%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2         | 0.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 0.63%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 2         | 0.63%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 0.63%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 2         | 0.63%   |
| Ralink RT5572 Wireless Adapter                                 | 2         | 0.63%   |
| Ralink RT5370 Wireless Adapter                                 | 2         | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 167       | 49.41%  |
| Realtek Semiconductor    | 96        | 28.4%   |
| AMD                      | 30        | 8.88%   |
| Broadcom                 | 18        | 5.33%   |
| Qualcomm Atheros         | 8         | 2.37%   |
| Nvidia                   | 5         | 1.48%   |
| Google                   | 5         | 1.48%   |
| Marvell Technology Group | 4         | 1.18%   |
| Samsung Electronics      | 1         | 0.3%    |
| National Semiconductor   | 1         | 0.3%    |
| JMicron Technology       | 1         | 0.3%    |
| Aquantia                 | 1         | 0.3%    |
| Apple                    | 1         | 0.3%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 81        | 23.75%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 35        | 10.26%  |
| AMD XGMAC 10GbE Controller                                             | 30        | 8.8%    |
| Intel I210 Gigabit Network Connection                                  | 24        | 7.04%   |
| Intel I211 Gigabit Network Connection                                  | 15        | 4.4%    |
| Intel Ethernet Connection I219-LM                                      | 14        | 4.11%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 11        | 3.23%   |
| Intel Ethernet Connection I217-LM                                      | 9         | 2.64%   |
| Intel Ethernet Connection (3) I218-LM                                  | 9         | 2.64%   |
| Intel 82577LM Gigabit Network Connection                               | 9         | 2.64%   |
| Intel Ethernet Controller I225-V                                       | 6         | 1.76%   |
| Intel Ethernet Connection (4) I219-LM                                  | 6         | 1.76%   |
| Intel Ethernet Connection (4) I219-V                                   | 5         | 1.47%   |
| Google Nexus/Pixel Device (tether)                                     | 5         | 1.47%   |
| Nvidia MCP79 Ethernet                                                  | 4         | 1.17%   |
| Intel Ethernet Connection I219-V                                       | 4         | 1.17%   |
| Intel Ethernet Connection I218-LM                                      | 3         | 0.88%   |
| Intel Ethernet Connection (7) I219-LM                                  | 3         | 0.88%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3         | 0.88%   |
| Intel 82567LM Gigabit Network Connection                               | 3         | 0.88%   |
| Intel 82566MM Gigabit Network Connection                               | 3         | 0.88%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 3         | 0.88%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2         | 0.59%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 2         | 0.59%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 2         | 0.59%   |
| Intel Ethernet Connection I217-V                                       | 2         | 0.59%   |
| Intel Ethernet Connection (6) I219-V                                   | 2         | 0.59%   |
| Intel Ethernet Connection (10) I219-V                                  | 2         | 0.59%   |
| Intel 82579V Gigabit Network Connection                                | 2         | 0.59%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 2         | 0.59%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 0.59%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 2         | 0.59%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express               | 2         | 0.59%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 2         | 0.59%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 0.29%   |
| Realtek USB 2.5GbE Controller                                          | 1         | 0.29%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 0.29%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.29%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.29%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 303       | 49.43%  |
| WiFi     | 283       | 46.17%  |
| Unknown  | 15        | 2.45%   |
| Modem    | 12        | 1.96%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 234       | 56.66%  |
| WiFi     | 171       | 41.4%   |
| Unknown  | 7         | 1.69%   |
| Modem    | 1         | 0.24%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 232       | 68.24%  |
| 1     | 53        | 15.59%  |
| 6     | 21        | 6.18%   |
| 5     | 19        | 5.59%   |
| 3     | 10        | 2.94%   |
| 0     | 2         | 0.59%   |
| 8     | 1         | 0.29%   |
| 7     | 1         | 0.29%   |
| 4     | 1         | 0.29%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 297       | 86.84%  |
| Yes  | 45        | 13.16%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 104       | 52.26%  |
| Broadcom                        | 22        | 11.06%  |
| Apple                           | 20        | 10.05%  |
| Qualcomm Atheros Communications | 14        | 7.04%   |
| Realtek Semiconductor           | 11        | 5.53%   |
| Foxconn / Hon Hai               | 7         | 3.52%   |
| Lite-On Technology              | 4         | 2.01%   |
| Dell                            | 4         | 2.01%   |
| Hewlett-Packard                 | 3         | 1.51%   |
| USI                             | 2         | 1.01%   |
| IMC Networks                    | 2         | 1.01%   |
| Cambridge Silicon Radio         | 2         | 1.01%   |
| ASUSTek Computer                | 2         | 1.01%   |
| Alps Electric                   | 2         | 1.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                   | 49        | 24.38%  |
| Intel AX200 Bluetooth                                | 16        | 7.96%   |
| Intel AX201 Bluetooth                                | 13        | 6.47%   |
| Apple Bluetooth Host Controller                      | 11        | 5.47%   |
| Broadcom BCM2045B (BDC-2.1)                          | 9         | 4.48%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)       | 8         | 3.98%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]           | 8         | 3.98%   |
| Intel AX210 Bluetooth                                | 6         | 2.99%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                 | 6         | 2.99%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                | 4         | 1.99%   |
| Intel Wireless-AC 9260 Bluetooth Adapter             | 4         | 1.99%   |
| Intel Wireless-AC 3168 Bluetooth                     | 4         | 1.99%   |
| Apple Broadcom Built-in Bluetooth                    | 4         | 1.99%   |
| Realtek Bluetooth Adapter                            | 3         | 1.49%   |
| Realtek Bluetooth 4.2 Adapter                        | 3         | 1.49%   |
| Lite-On Atheros AR3012 Bluetooth                     | 3         | 1.49%   |
| Intel Centrino Bluetooth Wireless Transceiver        | 3         | 1.49%   |
| USI Qualcomm WCN685x Bluetooth Adapter               | 2         | 1%      |
| Realtek  Bluetooth 4.2 Adapter                       | 2         | 1%      |
| Qualcomm Atheros QCA9377 Bluetooth 4.1               | 2         | 1%      |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0               | 2         | 1%      |
| Qualcomm Atheros AR9462 Bluetooth                    | 2         | 1%      |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter         | 2         | 1%      |
| Foxconn / Hon Hai Bluetooth USB Module               | 2         | 1%      |
| Dell DW375 Bluetooth Module                          | 2         | 1%      |
| Dell Dell Wireless 380 Bluetooth 4.0 Module          | 2         | 1%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)  | 2         | 1%      |
| Realtek RTL8821A Bluetooth                           | 1         | 0.5%    |
| Realtek RTL8723B Bluetooth                           | 1         | 0.5%    |
| Realtek Bluetooth 4.0 + High Speed Chip              | 1         | 0.5%    |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE  | 1         | 0.5%    |
| Qualcomm Atheros Dell Wireless 1802 Bluetooth 4.0 LE | 1         | 0.5%    |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth        | 1         | 0.5%    |
| Qualcomm Atheros Bluetooth                           | 1         | 0.5%    |
| Lite-On Bluetooth USB Module                         | 1         | 0.5%    |
| Intel AX211 Bluetooth                                | 1         | 0.5%    |
| IMC Networks Bluetooth Module                        | 1         | 0.5%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter    | 1         | 0.5%    |
| HP Broadcom 2070 Bluetooth Combo                     | 1         | 0.5%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]        | 1         | 0.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 265       | 73.61%  |
| AMD                                          | 58        | 16.11%  |
| Nvidia                                       | 24        | 6.67%   |
| Realtek Semiconductor                        | 2         | 0.56%   |
| Logitech                                     | 2         | 0.56%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.28%   |
| ULi Electronics                              | 1         | 0.28%   |
| Texas Instruments                            | 1         | 0.28%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.28%   |
| Phison Electronics                           | 1         | 0.28%   |
| Lenovo                                       | 1         | 0.28%   |
| Hewlett-Packard                              | 1         | 0.28%   |
| GN Netcom                                    | 1         | 0.28%   |
| C-Media Electronics                          | 1         | 0.28%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 46        | 10.43%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 41        | 9.3%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 34        | 7.71%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 29        | 6.58%   |
| Intel 8 Series HD Audio Controller                                                                | 25        | 5.67%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 24        | 5.44%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 19        | 4.31%   |
| Intel Broadwell-U Audio Controller                                                                | 19        | 4.31%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 16        | 3.63%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 13        | 2.95%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 13        | 2.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 12        | 2.72%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 12        | 2.72%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 12        | 2.72%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 9         | 2.04%   |
| Intel Cannon Lake PCH cAVS                                                                        | 9         | 2.04%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 8         | 1.81%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 8         | 1.81%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 1.59%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 1.13%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 0.91%   |
| Nvidia MCP79 High Definition Audio                                                                | 4         | 0.91%   |
| Intel CM238 HD Audio Controller                                                                   | 4         | 0.91%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 0.68%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 0.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.68%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 0.68%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 3         | 0.68%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 0.68%   |
| AMD FCH Azalia Controller                                                                         | 3         | 0.68%   |
| Realtek Semiconductor USB Audio                                                                   | 2         | 0.45%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.45%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.45%   |
| Intel Jasper Lake HD Audio                                                                        | 2         | 0.45%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 0.45%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 2         | 0.45%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 0.45%   |
| Unknown                                                                                           | 2         | 0.45%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 1         | 0.23%   |
| ULi Electronics M5451 PCI AC-Link Controller Audio Device                                         | 1         | 0.23%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 97        | 27.32%  |
| SK hynix                     | 67        | 18.87%  |
| Kingston                     | 38        | 10.7%   |
| Micron Technology            | 34        | 9.58%   |
| Transcend                    | 29        | 8.17%   |
| Unknown                      | 24        | 6.76%   |
| Crucial                      | 19        | 5.35%   |
| Corsair                      | 9         | 2.54%   |
| Unknown                      | 9         | 2.54%   |
| Ramaxel Technology           | 8         | 2.25%   |
| Elpida                       | 6         | 1.69%   |
| Nanya Technology             | 5         | 1.41%   |
| G.Skill                      | 2         | 0.56%   |
| Unknown (ABCD)               | 1         | 0.28%   |
| Unknown (0x7F7F7F94FFFFFFFF) | 1         | 0.28%   |
| Team                         | 1         | 0.28%   |
| Qimonda                      | 1         | 0.28%   |
| Patriot                      | 1         | 0.28%   |
| ASint Technology             | 1         | 0.28%   |
| A-DATA Technology            | 1         | 0.28%   |
| 48spaces                     | 1         | 0.28%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s           | 19        | 5.18%   |
| Unknown                                                       | 9         | 2.45%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 7         | 1.91%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s        | 7         | 1.91%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s         | 7         | 1.91%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                  | 6         | 1.63%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s         | 6         | 1.63%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s         | 5         | 1.36%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s         | 5         | 1.36%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s         | 5         | 1.36%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s       | 5         | 1.36%   |
| Transcend RAM TS512MLH64V6HL 4GB SODIMM DDR4 2667MT/s         | 4         | 1.09%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 4         | 1.09%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s         | 4         | 1.09%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s         | 4         | 1.09%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s         | 4         | 1.09%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s         | 4         | 1.09%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s       | 4         | 1.09%   |
| Transcend RAM TS1GLH64V6B3 8GB SODIMM DDR4 1333MT/s           | 3         | 0.82%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 3         | 0.82%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 3         | 0.82%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s         | 3         | 0.82%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s        | 3         | 0.82%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s         | 3         | 0.82%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                    | 3         | 0.82%   |
| Corsair RAM CMSX8GX3M1A1600C10 8GB SODIMM DDR3 1600MT/s       | 3         | 0.82%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                    | 2         | 0.54%   |
| Transcend RAM TS1GLH64V6B 8GB SODIMM DDR4 1333MT/s            | 2         | 0.54%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                  | 2         | 0.54%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s          | 2         | 0.54%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s        | 2         | 0.54%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s        | 2         | 0.54%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s        | 2         | 0.54%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2400MT/s        | 2         | 0.54%   |
| Samsung RAM M471A1K43EB1-CWE 16GB SODIMM DDR4 3200MT/s        | 2         | 0.54%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s         | 2         | 0.54%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s         | 2         | 0.54%   |
| Ramaxel RAM RMT3020EC58E9F1333 4GB SODIMM DDR3 1333MT/s       | 2         | 0.54%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 0.54%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s          | 2         | 0.54%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 147       | 47.42%  |
| DDR4    | 114       | 36.77%  |
| DDR2    | 20        | 6.45%   |
| LPDDR4  | 6         | 1.94%   |
| LPDDR3  | 6         | 1.94%   |
| DDR     | 5         | 1.61%   |
| Unknown | 4         | 1.29%   |
| LPDDR5  | 3         | 0.97%   |
| SDRAM   | 2         | 0.65%   |
| RAM     | 1         | 0.32%   |
| DRAM    | 1         | 0.32%   |
| DDR5    | 1         | 0.32%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 289       | 93.53%  |
| Row Of Chips | 12        | 3.88%   |
| Chip         | 4         | 1.29%   |
| DIMM         | 3         | 0.97%   |
| Unknown      | 1         | 0.32%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 134       | 40.61%  |
| 4096  | 88        | 26.67%  |
| 2048  | 50        | 15.15%  |
| 16384 | 37        | 11.21%  |
| 1024  | 12        | 3.64%   |
| 32768 | 5         | 1.52%   |
| 512   | 2         | 0.61%   |
| 256   | 2         | 0.61%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 99        | 30.46%  |
| 2667    | 51        | 15.69%  |
| 3200    | 32        | 9.85%   |
| 1333    | 29        | 8.92%   |
| 2400    | 18        | 5.54%   |
| 1334    | 16        | 4.92%   |
| 2133    | 15        | 4.62%   |
| 667     | 14        | 4.31%   |
| 1867    | 10        | 3.08%   |
| 800     | 10        | 3.08%   |
| Unknown | 8         | 2.46%   |
| 1067    | 6         | 1.85%   |
| 4267    | 5         | 1.54%   |
| 6400    | 3         | 0.92%   |
| 1066    | 2         | 0.62%   |
| 975     | 2         | 0.62%   |
| 533     | 2         | 0.62%   |
| 5600    | 1         | 0.31%   |
| 2933    | 1         | 0.31%   |
| 1639    | 1         | 0.31%   |

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
| Chicony Electronics                    | 67        | 34.54%  |
| Bison Electronics                      | 25        | 12.89%  |
| Microdia                               | 13        | 6.7%    |
| Realtek Semiconductor                  | 12        | 6.19%   |
| IMC Networks                           | 12        | 6.19%   |
| Lite-On Technology                     | 10        | 5.15%   |
| Suyin                                  | 9         | 4.64%   |
| Sunplus Innovation Technology          | 8         | 4.12%   |
| Apple                                  | 8         | 4.12%   |
| Syntek                                 | 5         | 2.58%   |
| Lenovo                                 | 5         | 2.58%   |
| Alcor Micro                            | 4         | 2.06%   |
| Quanta                                 | 3         | 1.55%   |
| Silicon Motion                         | 2         | 1.03%   |
| Luxvisions Innotech Limited            | 2         | 1.03%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.03%   |
| Tripath Technology                     | 1         | 0.52%   |
| SunplusIT                              | 1         | 0.52%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.52%   |
| Ricoh                                  | 1         | 0.52%   |
| Pixart Imaging                         | 1         | 0.52%   |
| Logitech                               | 1         | 0.52%   |
| Cubeternet                             | 1         | 0.52%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 28        | 14.36%  |
| Bison Integrated Camera                  | 11        | 5.64%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 7         | 3.59%   |
| Lite-On Integrated Camera                | 6         | 3.08%   |
| Chicony FJ Camera                        | 6         | 3.08%   |
| Microdia Integrated Webcam               | 5         | 2.56%   |
| IMC Networks Integrated Camera           | 5         | 2.56%   |
| Chicony HD WebCam                        | 5         | 2.56%   |
| Realtek USB 2.0 PC Camera                | 4         | 2.05%   |
| Apple FaceTime HD Camera (Built-in)      | 4         | 2.05%   |
| Syntek Integrated Camera                 | 3         | 1.54%   |
| Suyin RGBIR Camera                       | 3         | 1.54%   |
| Microdia Integrated_Webcam_HD            | 3         | 1.54%   |
| Lite-On Realtek PC Camera                | 3         | 1.54%   |
| Chicony Integrated Camera [ThinkPad]     | 3         | 1.54%   |
| Bison ThinkPad Integrated Camera         | 3         | 1.54%   |
| Bison SunplusIT Integrated Camera        | 3         | 1.54%   |
| Alcor Micro USB 2.0 Camera               | 3         | 1.54%   |
| Syntek Lenovo EasyCamera                 | 2         | 1.03%   |
| Sunplus Integrated_Webcam_HD             | 2         | 1.03%   |
| Realtek Integrated_Webcam_HD             | 2         | 1.03%   |
| Quanta HP TrueVision HD Camera           | 2         | 1.03%   |
| Lenovo Integrated Webcam [R5U877]        | 2         | 1.03%   |
| Lenovo Integrated Camera                 | 2         | 1.03%   |
| IMC Networks XHC Camera                  | 2         | 1.03%   |
| IMC Networks Realtek PC Camera           | 2         | 1.03%   |
| Chicony Integrated IR Camera             | 2         | 1.03%   |
| Chicony HD WebCam (Acer)                 | 2         | 1.03%   |
| Chicony Chicony USB2.0 Camera            | 2         | 1.03%   |
| Bison SunplusIT INC. Integrated Camera   | 2         | 1.03%   |
| Bison Lenovo EasyCamera                  | 2         | 1.03%   |
| Apple FaceTime HD Camera                 | 2         | 1.03%   |
| Apple FaceTime Camera                    | 2         | 1.03%   |
| Tripath USB Camera                       | 1         | 0.51%   |
| Suyin Sony Visual Communication Camera   | 1         | 0.51%   |
| Suyin Integrated Webcam                  | 1         | 0.51%   |
| Suyin HP Webcam-101                      | 1         | 0.51%   |
| Suyin HP Integrated Webcam               | 1         | 0.51%   |
| Suyin Asus Integrated Webcam             | 1         | 0.51%   |
| Suyin Acer/Lenovo Webcam [CN0316]        | 1         | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 25        | 34.25%  |
| Upek                       | 11        | 15.07%  |
| Synaptics                  | 11        | 15.07%  |
| AuthenTec                  | 6         | 8.22%   |
| Shenzhen Goodix Technology | 5         | 6.85%   |
| LighTuning Technology      | 5         | 6.85%   |
| Elan Microelectronics      | 3         | 4.11%   |
| Broadcom                   | 3         | 4.11%   |
| STMicroelectronics         | 2         | 2.74%   |
| Next Biometrics            | 1         | 1.37%   |
| FocalTech Systems          | 1         | 1.37%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 10        | 13.7%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 10        | 13.7%   |
| Validity Sensors Synaptics WBDI                                              | 6         | 8.22%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 4         | 5.48%   |
| Shenzhen Goodix Fingerprint Reader                                           | 4         | 5.48%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 3         | 4.11%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 3         | 4.11%   |
| Elan Fingerprint Sensor                                                      | 3         | 4.11%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 4.11%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 2         | 2.74%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 2         | 2.74%   |
| Validity Sensors Swipe Fingerprint Sensor                                    | 2         | 2.74%   |
| STMicroelectronics Fingerprint Reader                                        | 2         | 2.74%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 2         | 2.74%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 2         | 2.74%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 1         | 1.37%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 1         | 1.37%   |
| Validity Sensors VFS Fingerprint sensor                                      | 1         | 1.37%   |
| Upek TCS5B Fingerprint sensor                                                | 1         | 1.37%   |
| Synaptics WBDI                                                               | 1         | 1.37%   |
| Synaptics TouchPad                                                           | 1         | 1.37%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 1         | 1.37%   |
| Shenzhen Goodix Fingerprint Reader SGX                                       | 1         | 1.37%   |
| Next Biometrics NB-2020-U Fingerprint Reader                                 | 1         | 1.37%   |
| FocalTech Systems Fingerprint Reader                                         | 1         | 1.37%   |
| AuthenTec AES2660                                                            | 1         | 1.37%   |
| AuthenTec AES2550 Fingerprint Sensor                                         | 1         | 1.37%   |
| AuthenTec AES1660                                                            | 1         | 1.37%   |
| AuthenTec AES1600                                                            | 1         | 1.37%   |
| Unknown                                                                      | 1         | 1.37%   |

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
| 1     | 105       | 29.91%  |
| 2     | 92        | 26.21%  |
| 0     | 67        | 19.09%  |
| 3     | 57        | 16.24%  |
| 4     | 20        | 5.7%    |
| 5     | 8         | 2.28%   |
| 7     | 1         | 0.28%   |
| 6     | 1         | 0.28%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 225       | 41.98%  |
| Bluetooth                | 73        | 13.62%  |
| Fingerprint reader       | 64        | 11.94%  |
| Card reader              | 57        | 10.63%  |
| Net/wireless             | 54        | 10.07%  |
| Firewire controller      | 23        | 4.29%   |
| Network                  | 10        | 1.87%   |
| Graphics card            | 9         | 1.68%   |
| Net/ethernet             | 6         | 1.12%   |
| Sound                    | 5         | 0.93%   |
| Modem                    | 4         | 0.75%   |
| Storage                  | 3         | 0.56%   |
| Storage/nvme             | 1         | 0.19%   |
| Storage/ide              | 1         | 0.19%   |
| Storage/ata              | 1         | 0.19%   |

