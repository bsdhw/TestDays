BSD in Poland - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for BSD in Poland.

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

Total: 148

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| HP            | Unknown                     | [babd844cfb](https://bsd-hardware.info/?probe=babd844cfb) | Jan 04, 2025 |
| HP            | Unknown                     | [54cd46759e](https://bsd-hardware.info/?probe=54cd46759e) | Jan 03, 2025 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [1f7a60f418](https://bsd-hardware.info/?probe=1f7a60f418) | Dec 13, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [b6aaae01ed](https://bsd-hardware.info/?probe=b6aaae01ed) | Nov 29, 2024 |
| HP            | 255 G7 Notebook PC          | [9422dbf997](https://bsd-hardware.info/?probe=9422dbf997) | Nov 22, 2024 |
| HP            | OMEN by Transcend Gaming... | [213d36f877](https://bsd-hardware.info/?probe=213d36f877) | Nov 10, 2024 |
| Lenovo        | ThinkPad X280 20KES2VQ00    | [d864971168](https://bsd-hardware.info/?probe=d864971168) | Oct 30, 2024 |
| Dell          | Vostro 5490                 | [32de340e28](https://bsd-hardware.info/?probe=32de340e28) | Sep 23, 2024 |
| Unknown       | Unknown                     | [7dbe7b6eaf](https://bsd-hardware.info/?probe=7dbe7b6eaf) | Aug 19, 2024 |
| Lenovo        | ThinkPad X230 23255RG       | [b79ae8b113](https://bsd-hardware.info/?probe=b79ae8b113) | Aug 18, 2024 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | [ed6539c0d5](https://bsd-hardware.info/?probe=ed6539c0d5) | Aug 03, 2024 |
| Unknown       | Unknown                     | [207a85a15d](https://bsd-hardware.info/?probe=207a85a15d) | Aug 02, 2024 |
| Dell          | XPS 13 9343                 | [f7837f7b55](https://bsd-hardware.info/?probe=f7837f7b55) | Jul 28, 2024 |
| Dell          | XPS 13 9343                 | [9053a69af6](https://bsd-hardware.info/?probe=9053a69af6) | Jul 28, 2024 |
| Apple         | MacBookPro11,4              | [6bade1eaf8](https://bsd-hardware.info/?probe=6bade1eaf8) | Jul 26, 2024 |
| Dell          | XPS 13 9343                 | [c979e064f1](https://bsd-hardware.info/?probe=c979e064f1) | Jul 25, 2024 |
| HP            | Pavilion dv7                | [5178909b84](https://bsd-hardware.info/?probe=5178909b84) | Jul 21, 2024 |
| Deciso        | NetBoard-A10_Gen.3          | [b9206448e2](https://bsd-hardware.info/?probe=b9206448e2) | Jul 17, 2024 |
| IGEL Techn... | M350C                       | [79957869db](https://bsd-hardware.info/?probe=79957869db) | Jul 12, 2024 |
| Lenovo        | M30-70 20446                | [fd24cae390](https://bsd-hardware.info/?probe=fd24cae390) | Jun 26, 2024 |
| Lenovo        | M30-70 20446                | [e9a1a61239](https://bsd-hardware.info/?probe=e9a1a61239) | Jun 26, 2024 |
| Lenovo        | M30-70 20446                | [babc2efc9e](https://bsd-hardware.info/?probe=babc2efc9e) | Jun 26, 2024 |
| Lenovo        | M30-70 20446                | [0251872176](https://bsd-hardware.info/?probe=0251872176) | Jun 26, 2024 |
| Apple         | MacBookPro11,4              | [3988badee2](https://bsd-hardware.info/?probe=3988badee2) | Jun 11, 2024 |
| Deciso        | NetBoard-A10_Gen.3          | [e2a13da073](https://bsd-hardware.info/?probe=e2a13da073) | Jun 06, 2024 |
| Sony          | SVF1521G6EW                 | [b977d6f1e0](https://bsd-hardware.info/?probe=b977d6f1e0) | Jun 02, 2024 |
| Fujitsu       | LIFEBOOK S751               | [4edc2b9cba](https://bsd-hardware.info/?probe=4edc2b9cba) | May 26, 2024 |
| Unknown       | Unknown                     | [6016137c6c](https://bsd-hardware.info/?probe=6016137c6c) | Apr 24, 2024 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [7ae4c9320c](https://bsd-hardware.info/?probe=7ae4c9320c) | Apr 23, 2024 |
| ASUSTek       | X550CA                      | [ff92192d22](https://bsd-hardware.info/?probe=ff92192d22) | Mar 19, 2024 |
| Lenovo        | G580 20150                  | [1a072e681a](https://bsd-hardware.info/?probe=1a072e681a) | Mar 15, 2024 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | [ba0295b8ea](https://bsd-hardware.info/?probe=ba0295b8ea) | Mar 05, 2024 |
| Lenovo        | ThinkPad X230 23254S6       | [cae99ac427](https://bsd-hardware.info/?probe=cae99ac427) | Mar 03, 2024 |
| Lenovo        | ThinkPad X220 4291H77       | [2fe3ff7e06](https://bsd-hardware.info/?probe=2fe3ff7e06) | Dec 18, 2023 |
| HP            | Laptop 15s-eq3xxx           | [f2aa7b3ebf](https://bsd-hardware.info/?probe=f2aa7b3ebf) | Nov 25, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [05bf5fb9f4](https://bsd-hardware.info/?probe=05bf5fb9f4) | Nov 07, 2023 |
| HP            | Laptop 15s-eq3xxx           | [5a7e4222f1](https://bsd-hardware.info/?probe=5a7e4222f1) | Oct 21, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [b192196423](https://bsd-hardware.info/?probe=b192196423) | Oct 08, 2023 |
| Dell          | XPS 9320                    | [d80b3d5a54](https://bsd-hardware.info/?probe=d80b3d5a54) | Sep 14, 2023 |
| Lenovo        | ThinkPad X200 7458WNZ       | [3ac1d60240](https://bsd-hardware.info/?probe=3ac1d60240) | Aug 12, 2023 |
| HP            | EliteBook 840 G5            | [6496fe0cfe](https://bsd-hardware.info/?probe=6496fe0cfe) | Aug 03, 2023 |
| ASUSTek       | X555LD                      | [9c0c41b663](https://bsd-hardware.info/?probe=9c0c41b663) | Jul 30, 2023 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | [386a80104d](https://bsd-hardware.info/?probe=386a80104d) | Jul 19, 2023 |
| Unknown       | Unknown                     | [13c087ef5e](https://bsd-hardware.info/?probe=13c087ef5e) | Jul 03, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [1aff07438c](https://bsd-hardware.info/?probe=1aff07438c) | Jun 28, 2023 |
| Dell          | Latitude E4310              | [9cdd4909fe](https://bsd-hardware.info/?probe=9cdd4909fe) | Jun 24, 2023 |
| Samsung       | R530/R730/R540              | [b007264caa](https://bsd-hardware.info/?probe=b007264caa) | Jun 11, 2023 |
| Unknown       | Unknown                     | [9afa1aea18](https://bsd-hardware.info/?probe=9afa1aea18) | Jun 10, 2023 |
| Lenovo        | ThinkPad T480 20L6S5VP4C    | [b891388109](https://bsd-hardware.info/?probe=b891388109) | Jun 07, 2023 |
| Deciso        | NetBoard-A20                | [48a63a2328](https://bsd-hardware.info/?probe=48a63a2328) | Jun 02, 2023 |
| Unknown       | Unknown                     | [3b4be5b07a](https://bsd-hardware.info/?probe=3b4be5b07a) | May 24, 2023 |
| Google        | Sentry                      | [107124dd66](https://bsd-hardware.info/?probe=107124dd66) | May 22, 2023 |
| Unknown       | Unknown                     | [2a2b4272f9](https://bsd-hardware.info/?probe=2a2b4272f9) | May 20, 2023 |
| Packard Be... | EasyNote LJ65               | [36d3e7aaf7](https://bsd-hardware.info/?probe=36d3e7aaf7) | May 19, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [526906c806](https://bsd-hardware.info/?probe=526906c806) | May 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [8aede62ca8](https://bsd-hardware.info/?probe=8aede62ca8) | May 14, 2023 |
| Lenovo        | ThinkPad T500 205663G       | [d706da9400](https://bsd-hardware.info/?probe=d706da9400) | May 06, 2023 |
| Medion        | E15302                      | [f47f32e1cc](https://bsd-hardware.info/?probe=f47f32e1cc) | Apr 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [add8280600](https://bsd-hardware.info/?probe=add8280600) | Apr 11, 2023 |
| Fujitsu       | CELSIUS H920                | [0551eecbcc](https://bsd-hardware.info/?probe=0551eecbcc) | Apr 06, 2023 |
| Fujitsu       | CELSIUS H920                | [e6300dc691](https://bsd-hardware.info/?probe=e6300dc691) | Mar 31, 2023 |
| Lenovo        | ThinkPad T540p 20BFS10W0... | [30c5fc2625](https://bsd-hardware.info/?probe=30c5fc2625) | Mar 29, 2023 |
| Acer          | Aspire F5-573G              | [a8f794f3fb](https://bsd-hardware.info/?probe=a8f794f3fb) | Mar 24, 2023 |
| ASUSTek       | X71Vn                       | [6e96ea55ee](https://bsd-hardware.info/?probe=6e96ea55ee) | Mar 22, 2023 |
| Lenovo        | ThinkPad A275 20KCS07010    | [4d6daf66c1](https://bsd-hardware.info/?probe=4d6daf66c1) | Mar 18, 2023 |
| HP            | EliteBook 850 G2            | [653dbe54a4](https://bsd-hardware.info/?probe=653dbe54a4) | Mar 18, 2023 |
| Dell          | Latitude D630               | [da1fa73418](https://bsd-hardware.info/?probe=da1fa73418) | Mar 14, 2023 |
| Lenovo        | ThinkPad X200 74591P0       | [882cc7fc62](https://bsd-hardware.info/?probe=882cc7fc62) | Mar 13, 2023 |
| Dell          | Latitude E5450              | [4bb2040221](https://bsd-hardware.info/?probe=4bb2040221) | Mar 11, 2023 |
| Lenovo        | ThinkPad T530 24297XG       | [97d9b10c8a](https://bsd-hardware.info/?probe=97d9b10c8a) | Feb 24, 2023 |
| HP            | Notebook                    | [8d8e5c294a](https://bsd-hardware.info/?probe=8d8e5c294a) | Feb 06, 2023 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | [bccdd2f331](https://bsd-hardware.info/?probe=bccdd2f331) | Jan 30, 2023 |
| HP            | EliteBook 840 G3            | [92c676e033](https://bsd-hardware.info/?probe=92c676e033) | Jan 26, 2023 |
| HP            | Laptop 15-bs0xx             | [7bd5f0c2e9](https://bsd-hardware.info/?probe=7bd5f0c2e9) | Jan 22, 2023 |
| Intel         | H81U                        | [08d2539153](https://bsd-hardware.info/?probe=08d2539153) | Jan 18, 2023 |
| Intel         | H81U                        | [fe47328dd0](https://bsd-hardware.info/?probe=fe47328dd0) | Jan 17, 2023 |
| Dell          | Latitude E6430              | [45f592a66f](https://bsd-hardware.info/?probe=45f592a66f) | Jan 06, 2023 |
| Dell          | Latitude E6430              | [1c4bec17bb](https://bsd-hardware.info/?probe=1c4bec17bb) | Jan 06, 2023 |
| Google        | Lars                        | [4130b19cfa](https://bsd-hardware.info/?probe=4130b19cfa) | Dec 03, 2022 |
| HP            | SpectreXT Pro 13-b000 PC    | [f45ea42873](https://bsd-hardware.info/?probe=f45ea42873) | Oct 16, 2022 |
| Lenovo        | G50-30 80G0                 | [da4bd87fee](https://bsd-hardware.info/?probe=da4bd87fee) | Sep 17, 2022 |
| Deciso        | NetBoard-A10                | [3547d9da9c](https://bsd-hardware.info/?probe=3547d9da9c) | Sep 01, 2022 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | [2e7d570822](https://bsd-hardware.info/?probe=2e7d570822) | Aug 20, 2022 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | [7afa139f4f](https://bsd-hardware.info/?probe=7afa139f4f) | Aug 20, 2022 |
| Lenovo        | ThinkPad T495 20NJ0010PB    | [078888676a](https://bsd-hardware.info/?probe=078888676a) | Jul 13, 2022 |
| Dell          | Latitude 5410               | [3334ff3727](https://bsd-hardware.info/?probe=3334ff3727) | Jun 06, 2022 |
| Lenovo        | ThinkPad X200 745969G       | [e973d1e806](https://bsd-hardware.info/?probe=e973d1e806) | Mar 18, 2022 |
| Dell          | Inspiron 5502               | [9e440b5500](https://bsd-hardware.info/?probe=9e440b5500) | Mar 13, 2022 |
| Dell          | Vostro 3550                 | [4bc5573cf5](https://bsd-hardware.info/?probe=4bc5573cf5) | Mar 02, 2022 |
| Dell          | Latitude E6430              | [fdde41404d](https://bsd-hardware.info/?probe=fdde41404d) | Feb 24, 2022 |
| Lenovo        | ThinkPad X200 745969G       | [a4341268d0](https://bsd-hardware.info/?probe=a4341268d0) | Feb 23, 2022 |
| Dell          | Vostro 3550                 | [11bed21472](https://bsd-hardware.info/?probe=11bed21472) | Feb 21, 2022 |
| Lenovo        | ThinkPad X200 745969G       | [c024d383e7](https://bsd-hardware.info/?probe=c024d383e7) | Feb 13, 2022 |
| Lenovo        | G580 20150                  | [478714c7c9](https://bsd-hardware.info/?probe=478714c7c9) | Feb 07, 2022 |
| Lenovo        | ThinkPad X200 745969G       | [f107f7c1b1](https://bsd-hardware.info/?probe=f107f7c1b1) | Feb 06, 2022 |
| Lenovo        | G500s 20245                 | [41f9f804ac](https://bsd-hardware.info/?probe=41f9f804ac) | Feb 04, 2022 |
| Dell          | Vostro 3550                 | [0b290f2ac3](https://bsd-hardware.info/?probe=0b290f2ac3) | Feb 02, 2022 |
| Lenovo        | ThinkPad X200 745969G       | [f8476c0ea7](https://bsd-hardware.info/?probe=f8476c0ea7) | Feb 01, 2022 |
| Dell          | Vostro 3550                 | [97ef0862c2](https://bsd-hardware.info/?probe=97ef0862c2) | Feb 01, 2022 |
| Dell          | Latitude E6430              | [e18a4bc564](https://bsd-hardware.info/?probe=e18a4bc564) | Jan 10, 2022 |
| Dell          | Inspiron N5110              | [19be37f181](https://bsd-hardware.info/?probe=19be37f181) | Jan 09, 2022 |
| Acer          | Aspire 5742G                | [b77a4ee97c](https://bsd-hardware.info/?probe=b77a4ee97c) | Dec 30, 2021 |
| Acer          | Aspire 5742G                | [b650885b00](https://bsd-hardware.info/?probe=b650885b00) | Dec 24, 2021 |
| Dell          | Latitude E5470              | [18470afd9d](https://bsd-hardware.info/?probe=18470afd9d) | Dec 19, 2021 |
| Dell          | G15 5510                    | [2da7a07664](https://bsd-hardware.info/?probe=2da7a07664) | Dec 07, 2021 |
| Dell          | G15 5510                    | [8846b3fd69](https://bsd-hardware.info/?probe=8846b3fd69) | Nov 27, 2021 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [7330a6f958](https://bsd-hardware.info/?probe=7330a6f958) | Nov 20, 2021 |
| Dell          | G15 5510                    | [e9d432bc06](https://bsd-hardware.info/?probe=e9d432bc06) | Nov 12, 2021 |
| Dell          | G15 5510                    | [91750755e4](https://bsd-hardware.info/?probe=91750755e4) | Nov 12, 2021 |
| Acer          | Aspire 5742G                | [0513869be8](https://bsd-hardware.info/?probe=0513869be8) | Nov 09, 2021 |
| Dell          | Latitude E6430              | [46f2ef2432](https://bsd-hardware.info/?probe=46f2ef2432) | Nov 08, 2021 |
| Dell          | Latitude E6430              | [d31f35bb29](https://bsd-hardware.info/?probe=d31f35bb29) | Oct 15, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [fc1eda0998](https://bsd-hardware.info/?probe=fc1eda0998) | Oct 08, 2021 |
| ASUSTek       | X555LB                      | [e3443d9f27](https://bsd-hardware.info/?probe=e3443d9f27) | Oct 02, 2021 |
| IBM           | ThinkPad X41 2525FAG        | [63a34dc807](https://bsd-hardware.info/?probe=63a34dc807) | Sep 14, 2021 |
| Lenovo        | Unknown                     | [e16ce5e864](https://bsd-hardware.info/?probe=e16ce5e864) | Aug 08, 2021 |
| Fujitsu Si... | AMILO PRO V3515             | [77676fbcfc](https://bsd-hardware.info/?probe=77676fbcfc) | Jul 18, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [668bf95221](https://bsd-hardware.info/?probe=668bf95221) | Jun 25, 2021 |
| Lenovo        | ThinkPad T440 20B7S1860W    | [8552205176](https://bsd-hardware.info/?probe=8552205176) | Jun 22, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [9f82e215c3](https://bsd-hardware.info/?probe=9f82e215c3) | Jun 22, 2021 |
| Dell          | Vostro 3560                 | [ce9d5f9a46](https://bsd-hardware.info/?probe=ce9d5f9a46) | Jun 18, 2021 |
| Acer          | Aspire V3-571G              | [a9fe2f5aad](https://bsd-hardware.info/?probe=a9fe2f5aad) | Jun 16, 2021 |
| Dell          | Latitude 5400               | [1bb6c1f63f](https://bsd-hardware.info/?probe=1bb6c1f63f) | Jun 15, 2021 |
| Dell          | Latitude E6440              | [8fa2c1f5c4](https://bsd-hardware.info/?probe=8fa2c1f5c4) | Jun 13, 2021 |
| Dell          | Latitude E6440              | [77f259babe](https://bsd-hardware.info/?probe=77f259babe) | Jun 12, 2021 |
| Dell          | Latitude E6410              | [211fe874fd](https://bsd-hardware.info/?probe=211fe874fd) | May 22, 2021 |
| Dell          | Latitude E6440              | [3a656ded12](https://bsd-hardware.info/?probe=3a656ded12) | Apr 19, 2021 |
| Dell          | Latitude E6440              | [68f57531cb](https://bsd-hardware.info/?probe=68f57531cb) | Apr 19, 2021 |
| Dell          | Latitude E6440              | [a332efd9d9](https://bsd-hardware.info/?probe=a332efd9d9) | Mar 15, 2021 |
| HP            | ENVY dv7                    | [4637a9eeff](https://bsd-hardware.info/?probe=4637a9eeff) | Feb 14, 2021 |
| Dell          | Latitude E5430 vPro         | [bee421a110](https://bsd-hardware.info/?probe=bee421a110) | Feb 06, 2021 |
| Dell          | Latitude E5430 vPro         | [e8157ac6a3](https://bsd-hardware.info/?probe=e8157ac6a3) | Feb 06, 2021 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | [3d18f3f8a9](https://bsd-hardware.info/?probe=3d18f3f8a9) | Jan 23, 2021 |
| Lenovo        | ThinkPad X200s 7470A98      | [41f36aa8b6](https://bsd-hardware.info/?probe=41f36aa8b6) | Dec 19, 2020 |
| Unknown       | Spring Peak                 | [b61f5c268a](https://bsd-hardware.info/?probe=b61f5c268a) | Dec 15, 2020 |
| PC Special... | Recoil II                   | [343eec31b5](https://bsd-hardware.info/?probe=343eec31b5) | Dec 06, 2020 |
| Panasonic     | CFMX4-1                     | [761d21f21a](https://bsd-hardware.info/?probe=761d21f21a) | Dec 06, 2020 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [dce3ba8c99](https://bsd-hardware.info/?probe=dce3ba8c99) | Nov 18, 2020 |
| Lenovo        | ThinkPad W520 4284W5L       | [2664153a6e](https://bsd-hardware.info/?probe=2664153a6e) | Oct 29, 2020 |
| Lenovo        | ThinkPad X230 23254S6       | [f4ac5ddaa4](https://bsd-hardware.info/?probe=f4ac5ddaa4) | Oct 25, 2020 |
| HP            | 635                         | [3b21406e87](https://bsd-hardware.info/?probe=3b21406e87) | Oct 23, 2020 |
| Lenovo        | ThinkPad T480 20L6S4GR02    | [6c2d8a57ea](https://bsd-hardware.info/?probe=6c2d8a57ea) | Oct 19, 2020 |
| Lenovo        | ThinkPad W520 4284W5L       | [01d2c090de](https://bsd-hardware.info/?probe=01d2c090de) | Oct 03, 2020 |
| Dell          | Latitude XT2                | [19456100cf](https://bsd-hardware.info/?probe=19456100cf) | Jul 16, 2020 |
| Dell          | Latitude XT2                | [160725773f](https://bsd-hardware.info/?probe=160725773f) | Jul 16, 2020 |
| Sony          | SVF1521K1EB                 | [fe29d4e002](https://bsd-hardware.info/?probe=fe29d4e002) | Jun 29, 2020 |
| Lenovo        | ThinkPad W520 4284W5L       | [9ba8051e48](https://bsd-hardware.info/?probe=9ba8051e48) | Jun 09, 2020 |
| Dell          | Latitude E7240              | [1de87c0000](https://bsd-hardware.info/?probe=1de87c0000) | May 30, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| helloSystem 0.8.1    | 20        | 16.13%  |
| OpenBSD 7.0          | 5         | 4.03%   |
| FreeBSD 14.0-CURRENT | 5         | 4.03%   |
| OpenBSD 7.3          | 4         | 3.23%   |
| OpenBSD 7.1          | 4         | 3.23%   |
| helloSystem 0.7.0    | 4         | 3.23%   |
| GhostBSD 20.04.02    | 4         | 3.23%   |
| FreeBSD 13.2         | 4         | 3.23%   |
| FreeBSD 12.2         | 4         | 3.23%   |
| helloSystem 0.5.0    | 3         | 2.42%   |
| FreeBSD 14.1         | 3         | 2.42%   |
| FreeBSD 12.1         | 3         | 2.42%   |
| OPNsense 22.7.10     | 2         | 1.61%   |
| OpenBSD 6.8          | 2         | 1.61%   |
| helloSystem 0.9.0    | 2         | 1.61%   |
| helloSystem 0.8.2    | 2         | 1.61%   |
| helloSystem 0.8.0    | 2         | 1.61%   |
| helloSystem 0.6.0    | 2         | 1.61%   |
| FreeBSD 14.2         | 2         | 1.61%   |
| FreeBSD 13.0-p5      | 2         | 1.61%   |
| FreeBSD 13.0-p4      | 2         | 1.61%   |
| FreeBSD 13.0-p2      | 2         | 1.61%   |
| OPNsense 24.7.1      | 1         | 0.81%   |
| OPNsense 24.4.1      | 1         | 0.81%   |
| OPNsense 24.1.8      | 1         | 0.81%   |
| OPNsense 24.1.6      | 1         | 0.81%   |
| OPNsense 24.1.10     | 1         | 0.81%   |
| OPNsense 23.4        | 1         | 0.81%   |
| OPNsense 23.1.9      | 1         | 0.81%   |
| OPNsense 23.1.7      | 1         | 0.81%   |
| OPNsense 23.1.11     | 1         | 0.81%   |
| OPNsense 22.7.3      | 1         | 0.81%   |
| OpenBSD 7.5          | 1         | 0.81%   |
| OpenBSD 7.4          | 1         | 0.81%   |
| OpenBSD 7.2          | 1         | 0.81%   |
| OpenBSD 6.9          | 1         | 0.81%   |
| NomadBSD 5806f915    | 1         | 0.81%   |
| NomadBSD 1.3.1       | 1         | 0.81%   |
| helloSystem 0.4.0    | 1         | 0.81%   |
| GhostBSD 24.07.3     | 1         | 0.81%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 36        | 33.64%  |
| helloSystem | 35        | 32.71%  |
| OpenBSD     | 14        | 13.08%  |
| OPNsense    | 10        | 9.35%   |
| GhostBSD    | 9         | 8.41%   |
| NomadBSD    | 2         | 1.87%   |
| DragonFly   | 1         | 0.93%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 105       | 98.13%  |
| i386  | 2         | 1.87%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 39        | 35.78%  |
| XFCE         | 13        | 11.93%  |
| Console      | 13        | 11.93%  |
| MATE         | 11        | 10.09%  |
| fvwm         | 10        | 9.17%   |
| i3           | 7         | 6.42%   |
| KDE5         | 6         | 5.5%    |
| Openbox      | 4         | 3.67%   |
| TWM          | 3         | 2.75%   |
| GNOME        | 2         | 1.83%   |
| KDE          | 1         | 0.92%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 93        | 85.32%  |
| Console | 16        | 14.68%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 45        | 41.28%  |
| Console | 42        | 38.53%  |
| SDDM    | 10        | 9.17%   |
| LightDM | 10        | 9.17%   |
| XDM     | 2         | 1.83%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang           | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 34        | 30.91%  |
| C              | 24        | 21.82%  |
| en_US          | 22        | 20%     |
| pl_PL          | 21        | 19.09%  |
| fr_FR          | 6         | 5.45%   |
| pl             | 1         | 0.91%   |
| en_IE.US-ASCII | 1         | 0.91%   |
| en             | 1         | 0.91%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 91        | 84.26%  |
| BIOS | 17        | 15.74%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Zfs     | 63        | 58.88%  |
| Ufs     | 16        | 14.95%  |
| Ffs     | 14        | 13.08%  |
| Cd9660  | 13        | 12.15%  |
| Hammer2 | 1         | 0.93%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 93        | 86.92%  |
| MBR     | 13        | 12.15%  |
| Unknown | 1         | 0.93%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 40        | 37.38%  |
| Dell                | 21        | 19.63%  |
| Hewlett-Packard     | 13        | 12.15%  |
| Unknown             | 5         | 4.67%   |
| ASUSTek Computer    | 4         | 3.74%   |
| Deciso              | 3         | 2.8%    |
| Acer                | 3         | 2.8%    |
| Sony                | 2         | 1.87%   |
| Google              | 2         | 1.87%   |
| Fujitsu             | 2         | 1.87%   |
| Apple               | 2         | 1.87%   |
| Samsung Electronics | 1         | 0.93%   |
| PC Specialist       | 1         | 0.93%   |
| Panasonic           | 1         | 0.93%   |
| Packard Bell        | 1         | 0.93%   |
| Notebook            | 1         | 0.93%   |
| Medion              | 1         | 0.93%   |
| Intel               | 1         | 0.93%   |
| IGEL Technology     | 1         | 0.93%   |
| IBM                 | 1         | 0.93%   |
| Fujitsu Siemens     | 1         | 0.93%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 7         | 6.54%   |
| Lenovo ThinkPad X200 745969G               | 5         | 4.67%   |
| Lenovo G580 20150                          | 2         | 1.87%   |
| Dell Latitude E6430                        | 2         | 1.87%   |
| Apple MacBookPro11,4                       | 2         | 1.87%   |
| Sony SVF1521K1EB                           | 1         | 0.93%   |
| Sony SVF1521G6EW                           | 1         | 0.93%   |
| Samsung R530/R730/R540                     | 1         | 0.93%   |
| PC Specialist Recoil II                    | 1         | 0.93%   |
| Panasonic CFMX4-1                          | 1         | 0.93%   |
| Packard Bell EasyNote LJ65                 | 1         | 0.93%   |
| Notebook N85_N87,HJ,HJ1,HK1                | 1         | 0.93%   |
| Medion E15302                              | 1         | 0.93%   |
| Lenovo V15 G2 ALC 82KD                     | 1         | 0.93%   |
| Lenovo ThinkPad X280 20KES2VQ00            | 1         | 0.93%   |
| Lenovo ThinkPad X260 20F5S10W0H            | 1         | 0.93%   |
| Lenovo ThinkPad X230 23255RG               | 1         | 0.93%   |
| Lenovo ThinkPad X230 23254S6               | 1         | 0.93%   |
| Lenovo ThinkPad X220 4291H77               | 1         | 0.93%   |
| Lenovo ThinkPad X220 4286CTO               | 1         | 0.93%   |
| Lenovo ThinkPad X200s 7470A98              | 1         | 0.93%   |
| Lenovo ThinkPad X200 74591P0               | 1         | 0.93%   |
| Lenovo ThinkPad X200 7458WNZ               | 1         | 0.93%   |
| Lenovo ThinkPad X1 Extreme 2nd 20QV001CPB  | 1         | 0.93%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW00FSUS | 1         | 0.93%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW006FSP | 1         | 0.93%   |
| Lenovo ThinkPad W520 4284W5L               | 1         | 0.93%   |
| Lenovo ThinkPad T540p 20BFS10W03           | 1         | 0.93%   |
| Lenovo ThinkPad T530 24297XG               | 1         | 0.93%   |
| Lenovo ThinkPad T500 205663G               | 1         | 0.93%   |
| Lenovo ThinkPad T495 20NJ0010PB            | 1         | 0.93%   |
| Lenovo ThinkPad T480 20L6S5VP4C            | 1         | 0.93%   |
| Lenovo ThinkPad T480 20L6S4GR02            | 1         | 0.93%   |
| Lenovo ThinkPad T470 W10DG 20JNS0JU01      | 1         | 0.93%   |
| Lenovo ThinkPad T440 20B7S1860W            | 1         | 0.93%   |
| Lenovo ThinkPad T14s Gen 1 20UH0019PB      | 1         | 0.93%   |
| Lenovo ThinkPad T14s Gen 1 20T1S0Q200      | 1         | 0.93%   |
| Lenovo ThinkPad T14 Gen 1 20S1SFJH09       | 1         | 0.93%   |
| Lenovo ThinkPad A275 20KCS07010            | 1         | 0.93%   |
| Lenovo M30-70 20446                        | 1         | 0.93%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 30        | 28.04%  |
| Dell Latitude         | 13        | 12.15%  |
| Unknown               | 7         | 6.54%   |
| HP EliteBook          | 3         | 2.8%    |
| Dell Vostro           | 3         | 2.8%    |
| Acer Aspire           | 3         | 2.8%    |
| Lenovo IdeaPad        | 2         | 1.87%   |
| Lenovo G580           | 2         | 1.87%   |
| HP Laptop             | 2         | 1.87%   |
| Dell XPS              | 2         | 1.87%   |
| Dell Inspiron         | 2         | 1.87%   |
| Deciso NetBoard-A10   | 2         | 1.87%   |
| Apple MacBookPro11    | 2         | 1.87%   |
| Sony SVF1521K1EB      | 1         | 0.93%   |
| Sony SVF1521G6EW      | 1         | 0.93%   |
| Samsung R530          | 1         | 0.93%   |
| PC Specialist Recoil  | 1         | 0.93%   |
| Panasonic CFMX4-1     | 1         | 0.93%   |
| Packard Bell EasyNote | 1         | 0.93%   |
| Notebook N85          | 1         | 0.93%   |
| Medion E15302         | 1         | 0.93%   |
| Lenovo V15            | 1         | 0.93%   |
| Lenovo M30-70         | 1         | 0.93%   |
| Lenovo Legion         | 1         | 0.93%   |
| Lenovo G500s          | 1         | 0.93%   |
| Lenovo G50-30         | 1         | 0.93%   |
| Intel H81U            | 1         | 0.93%   |
| IGEL M350C            | 1         | 0.93%   |
| IBM ThinkPad          | 1         | 0.93%   |
| HP SpectreXT          | 1         | 0.93%   |
| HP Pavilion           | 1         | 0.93%   |
| HP OMEN               | 1         | 0.93%   |
| HP Notebook           | 1         | 0.93%   |
| HP ENVY               | 1         | 0.93%   |
| HP 635                | 1         | 0.93%   |
| HP 255                | 1         | 0.93%   |
| Google Sentry         | 1         | 0.93%   |
| Google Lars           | 1         | 0.93%   |
| Fujitsu Siemens AMILO | 1         | 0.93%   |
| Fujitsu LIFEBOOK      | 1         | 0.93%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2012 | 12        | 11.21%  |
| 2019 | 10        | 9.35%   |
| 2018 | 9         | 8.41%   |
| 2013 | 9         | 8.41%   |
| 2022 | 8         | 7.48%   |
| 2020 | 8         | 7.48%   |
| 2009 | 8         | 7.48%   |
| 2017 | 7         | 6.54%   |
| 2016 | 7         | 6.54%   |
| 2011 | 6         | 5.61%   |
| 2014 | 5         | 4.67%   |
| 2010 | 5         | 4.67%   |
| 2021 | 4         | 3.74%   |
| 2015 | 3         | 2.8%    |
| 2023 | 2         | 1.87%   |
| 2006 | 2         | 1.87%   |
| 2024 | 1         | 0.93%   |
| 2008 | 1         | 0.93%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 107       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 104       | 97.2%   |
| Yes  | 3         | 2.8%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 35        | 32.71%  |
| 4.01-8.0   | 31        | 28.97%  |
| 16.01-24.0 | 30        | 28.04%  |
| 32.01-64.0 | 6         | 5.61%   |
| 3.01-4.0   | 3         | 2.8%    |
| 2.01-3.0   | 2         | 1.87%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 63        | 58.33%  |
| 0.51-1.0  | 33        | 30.56%  |
| 1.01-2.0  | 8         | 7.41%   |
| 2.01-3.0  | 3         | 2.78%   |
| 8.01-16.0 | 1         | 0.93%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 71        | 64.55%  |
| 2      | 25        | 22.73%  |
| 0      | 11        | 10%     |
| 3      | 3         | 2.73%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 81        | 75%     |
| Yes       | 27        | 25%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 93        | 86.92%  |
| No        | 14        | 13.08%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 100       | 93.46%  |
| No        | 7         | 6.54%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 73        | 66.36%  |
| No        | 37        | 33.64%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Poland  | 107       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Warsaw                    | 17        | 15.32%  |
| Wroclaw                   | 12        | 10.81%  |
| Krakow                    | 12        | 10.81%  |
| Gdansk                    | 9         | 8.11%   |
| Katowice                  | 3         | 2.7%    |
| Chrusty                   | 3         | 2.7%    |
| Zgierz                    | 2         | 1.8%    |
| Szczecin                  | 2         | 1.8%    |
| Poznan                    | 2         | 1.8%    |
| Lublin                    | 2         | 1.8%    |
| Lodz                      | 2         | 1.8%    |
| Jarosław                 | 2         | 1.8%    |
| Grudziądz                | 2         | 1.8%    |
| Gdynia                    | 2         | 1.8%    |
| ЕљwiД™tochЕ‚owice | 1         | 0.9%    |
| Wloszczowa                | 1         | 0.9%    |
| Wloszakowice              | 1         | 0.9%    |
| Wieliczka                 | 1         | 0.9%    |
| Torun                     | 1         | 0.9%    |
| Świnoujście             | 1         | 0.9%    |
| Swilcza                   | 1         | 0.9%    |
| Starogard Gdański        | 1         | 0.9%    |
| Rybnik                    | 1         | 0.9%    |
| Reda                      | 1         | 0.9%    |
| Radom                     | 1         | 0.9%    |
| Pruszcz Gdanski           | 1         | 0.9%    |
| Pobiedziska               | 1         | 0.9%    |
| Piaseczno                 | 1         | 0.9%    |
| Pacierzow                 | 1         | 0.9%    |
| Ostrołęka               | 1         | 0.9%    |
| Opole                     | 1         | 0.9%    |
| Nowy Sącz                | 1         | 0.9%    |
| Mosina                    | 1         | 0.9%    |
| Miedziana Gora            | 1         | 0.9%    |
| Lochowo                   | 1         | 0.9%    |
| Lipie                     | 1         | 0.9%    |
| Leszno                    | 1         | 0.9%    |
| Ledziny                   | 1         | 0.9%    |
| Krasnik                   | 1         | 0.9%    |
| Koszalin                  | 1         | 0.9%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 22        | 29     | 19.13%  |
| Seagate             | 12        | 13     | 10.43%  |
| WDC                 | 9         | 10     | 7.83%   |
| GOODRAM             | 8         | 8      | 6.96%   |
| Transcend           | 6         | 7      | 5.22%   |
| Kingston            | 6         | 8      | 5.22%   |
| Crucial             | 6         | 11     | 5.22%   |
| SK hynix            | 5         | 5      | 4.35%   |
| A-DATA Technology   | 5         | 5      | 4.35%   |
| Toshiba             | 4         | 5      | 3.48%   |
| Hitachi             | 4         | 4      | 3.48%   |
| SanDisk             | 3         | 3      | 2.61%   |
| NVMe                | 3         | 5      | 2.61%   |
| Plextor             | 2         | 2      | 1.74%   |
| Micron Technology   | 2         | 3      | 1.74%   |
| Intel               | 2         | 2      | 1.74%   |
| HGST                | 2         | 3      | 1.74%   |
| Apple               | 2         | 2      | 1.74%   |
| SPCC                | 1         | 1      | 0.87%   |
| PNY                 | 1         | 1      | 0.87%   |
| Patriot             | 1         | 1      | 0.87%   |
| LITEONIT            | 1         | 1      | 0.87%   |
| LITEON              | 1         | 1      | 0.87%   |
| Kston               | 1         | 1      | 0.87%   |
| KIOXIA              | 1         | 1      | 0.87%   |
| Gigabyte Technology | 1         | 1      | 0.87%   |
| China               | 1         | 1      | 0.87%   |
| BIWIN               | 1         | 1      | 0.87%   |
| Apacer              | 1         | 5      | 0.87%   |
| Advantech           | 1         | 1      | 0.87%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Samsung HM321HI 320GB                | 6         | 5.04%   |
| Crucial CT500MX500SSD1 500GB         | 3         | 2.52%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 1.68%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 1.68%   |
| GOODRAM SSDPR-CX400-512-G2 512GB     | 2         | 1.68%   |
| Apple SSD SM0256G 256GB              | 2         | 1.68%   |
| WDC WDS250G2B0B-00YS70 250GB         | 1         | 0.84%   |
| WDC WD7500BPKT-22PK4T0 752GB         | 1         | 0.84%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 1         | 0.84%   |
| WDC WD3200BEKT-75PVMT1 320GB         | 1         | 0.84%   |
| WDC WD3200BEKT-22PVMT0 320GB         | 1         | 0.84%   |
| WDC WD1200BEVS-07RST0 120GB          | 1         | 0.84%   |
| WDC WD1200BEVS-07LAT0 120GB          | 1         | 0.84%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 1         | 0.84%   |
| WDC PC SN530 NVMe 512GB              | 1         | 0.84%   |
| Transcend TS512GMTS952T2 512GB       | 1         | 0.84%   |
| Transcend TS32GMSA370 32GB           | 1         | 0.84%   |
| Transcend TS256GMTE712A 256GB        | 1         | 0.84%   |
| Transcend TS256GMTE652T2 256GB       | 1         | 0.84%   |
| Transcend TS128GMSA370 128GB         | 1         | 0.84%   |
| Transcend TS120GMTS420S 120GB        | 1         | 0.84%   |
| Toshiba MK6461GSYN 640GB             | 1         | 0.84%   |
| Toshiba MK1252GSX 120GB              | 1         | 0.84%   |
| Toshiba KXG6AZNV1T02 1TB             | 1         | 0.84%   |
| Toshiba KBG40ZNS256G NVMe 256GB      | 1         | 0.84%   |
| SPCC Solid State Disk 512GB          | 1         | 0.84%   |
| SK hynix SC210 mSATA 256GB           | 1         | 0.84%   |
| SK hynix SC210 mSATA 128GB           | 1         | 0.84%   |
| SK hynix HFS128G39TNF-N3A0A 128GB    | 1         | 0.84%   |
| SK hynix HFM512GDHTNG-8310A 512GB    | 1         | 0.84%   |
| SK hynix BC511 NVMe 256GB            | 1         | 0.84%   |
| Seagate ST9500420AS 500GB            | 1         | 0.84%   |
| Seagate ST9500325AS 500GB            | 1         | 0.84%   |
| Seagate ST9320320AS 320GB            | 1         | 0.84%   |
| Seagate ST9250410AS 250GB            | 1         | 0.84%   |
| Seagate ST9160821AS 160GB            | 1         | 0.84%   |
| Seagate ST9160412AS 160GB            | 1         | 0.84%   |
| Seagate ST500LT012-1DG142 500GB      | 1         | 0.84%   |
| Seagate ST500LM000-1EJ162 500GB      | 1         | 0.84%   |
| SanDisk SDSSDP128G 128GB             | 1         | 0.84%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 13     | 36.36%  |
| WDC                 | 6         | 7      | 18.18%  |
| Samsung Electronics | 6         | 6      | 18.18%  |
| Hitachi             | 4         | 4      | 12.12%  |
| Toshiba             | 2         | 3      | 6.06%   |
| HGST                | 2         | 3      | 6.06%   |
| NVMe                | 1         | 1      | 3.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 15     | 13.56%  |
| GOODRAM             | 8         | 8      | 13.56%  |
| Kingston            | 6         | 8      | 10.17%  |
| Crucial             | 5         | 10     | 8.47%   |
| Transcend           | 4         | 4      | 6.78%   |
| A-DATA Technology   | 4         | 4      | 6.78%   |
| SK hynix            | 3         | 3      | 5.08%   |
| SanDisk             | 3         | 3      | 5.08%   |
| Plextor             | 2         | 2      | 3.39%   |
| Micron Technology   | 2         | 3      | 3.39%   |
| Apple               | 2         | 2      | 3.39%   |
| WDC                 | 1         | 1      | 1.69%   |
| SPCC                | 1         | 1      | 1.69%   |
| Patriot             | 1         | 1      | 1.69%   |
| NVMe                | 1         | 1      | 1.69%   |
| LITEONIT            | 1         | 1      | 1.69%   |
| LITEON              | 1         | 1      | 1.69%   |
| Kston               | 1         | 1      | 1.69%   |
| Intel               | 1         | 1      | 1.69%   |
| Gigabyte Technology | 1         | 1      | 1.69%   |
| China               | 1         | 1      | 1.69%   |
| Apacer              | 1         | 5      | 1.69%   |
| Advantech           | 1         | 1      | 1.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 54        | 78     | 50.94%  |
| HDD  | 31        | 37     | 29.25%  |
| NVMe | 21        | 26     | 19.81%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 77        | 115    | 78.57%  |
| NVMe | 21        | 26     | 21.43%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 64        | 88     | 76.19%  |
| 0.51-1.0   | 16        | 21     | 19.05%  |
| 1.01-2.0   | 3         | 4      | 3.57%   |
| 3.01-4.0   | 1         | 2      | 1.19%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 35        | 31.82%  |
| 1-20       | 22        | 20%     |
| 251-500    | 21        | 19.09%  |
| 51-100     | 16        | 14.55%  |
| 501-1000   | 8         | 7.27%   |
| 21-50      | 7         | 6.36%   |
| Unknown    | 1         | 0.91%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 94        | 85.45%  |
| 21-50   | 6         | 5.45%   |
| 51-100  | 6         | 5.45%   |
| 101-250 | 3         | 2.73%   |
| Unknown | 1         | 0.91%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                           | Notebooks | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| WDC WD3200BEKT-22PVMT0 320GB                    | 1         | 1      | 6.25%   |
| WDC WD1200BEVS-07LAT0 120GB                     | 1         | 1      | 6.25%   |
| Toshiba MK1252GSX 120GB                         | 1         | 1      | 6.25%   |
| SK hynix SC210 mSATA 256GB                      | 1         | 1      | 6.25%   |
| SK hynix SC210 mSATA 128GB                      | 1         | 1      | 6.25%   |
| Seagate ST9500420AS 500GB                       | 1         | 2      | 6.25%   |
| Seagate ST9160821AS 160GB                       | 1         | 1      | 6.25%   |
| Seagate ST9160412AS 160GB                       | 1         | 1      | 6.25%   |
| Seagate ST500LM000-1EJ162 500GB                 | 1         | 1      | 6.25%   |
| Seagate ST1000LM024 HN-M101MBB 1TB              | 1         | 1      | 6.25%   |
| Micron Technology MTFDDAT128MAM-1J2 128GB       | 1         | 1      | 6.25%   |
| Micron Technology MTFDDAK256TBN-1AR1ZABHA 256GB | 1         | 1      | 6.25%   |
| Kingston SV300S37A240G 240GB                    | 1         | 1      | 6.25%   |
| Intel SSDSC2BW180A4 180GB                       | 1         | 1      | 6.25%   |
| Hitachi HTS543232A7A384 320GB                   | 1         | 1      | 6.25%   |
| Crucial CT500MX500SSD1 500GB                    | 1         | 2      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 5         | 6      | 31.25%  |
| WDC               | 2         | 2      | 12.5%   |
| SK hynix          | 2         | 2      | 12.5%   |
| Micron Technology | 2         | 2      | 12.5%   |
| Toshiba           | 1         | 1      | 6.25%   |
| Kingston          | 1         | 1      | 6.25%   |
| Intel             | 1         | 1      | 6.25%   |
| Hitachi           | 1         | 1      | 6.25%   |
| Crucial           | 1         | 2      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 6      | 55.56%  |
| WDC     | 2         | 2      | 22.22%  |
| Toshiba | 1         | 1      | 11.11%  |
| Hitachi | 1         | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 10     | 53.33%  |
| SSD  | 7         | 8      | 46.67%  |

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
| Works    | 83        | 118    | 82.18%  |
| Malfunc  | 15        | 18     | 14.85%  |
| Detected | 3         | 5      | 2.97%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 80        | 67.23%  |
| Samsung Electronics       | 12        | 10.08%  |
| AMD                       | 6         | 5.04%   |
| SK hynix                  | 4         | 3.36%   |
| SanDisk                   | 4         | 3.36%   |
| Transcend                 | 2         | 1.68%   |
| Phison Electronics        | 2         | 1.68%   |
| KIOXIA                    | 2         | 1.68%   |
| VIA Technologies          | 1         | 0.84%   |
| Toshiba                   | 1         | 0.84%   |
| Silicon Motion            | 1         | 0.84%   |
| Realtek Semiconductor     | 1         | 0.84%   |
| Micron/Crucial Technology | 1         | 0.84%   |
| Micron Technology         | 1         | 0.84%   |
| Biwin Storage Technology  | 1         | 0.84%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 16        | 13.01%  |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 12        | 9.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 8         | 6.5%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 7         | 5.69%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 5.69%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 6         | 4.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 4.07%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 4.07%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 5         | 4.07%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 3         | 2.44%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 2.44%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 2.44%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 2         | 1.63%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 1.63%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 2         | 1.63%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 2         | 1.63%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 1.63%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 2         | 1.63%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1         | 0.81%   |
| VIA VT8237A SATA 2-Port Controller                                             | 1         | 0.81%   |
| Transcend NVMe PCIe SSD 220S/240S/MTE710T                                      | 1         | 0.81%   |
| Transcend NVMe PCIe SSD 110S/112S/120S/MTE300S/MTE400S/MTE652T2 (DRAM-less)    | 1         | 0.81%   |
| Toshiba XG6 NVMe SSD Controller                                                | 1         | 0.81%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 1         | 0.81%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 1         | 0.81%   |
| SK hynix BC511 NVMe SSD                                                        | 1         | 0.81%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 0.81%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1         | 0.81%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 1         | 0.81%   |
| SanDisk PC SN520 x2 M.2 2242 NVMe SSD                                          | 1         | 0.81%   |
| SanDisk IX SN530 NVMe SSD (DRAM-less)                                          | 1         | 0.81%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 1         | 0.81%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                              | 1         | 0.81%   |
| Phison PS5021-E21 PCIe4 NVMe Controller (DRAM-less)                            | 1         | 0.81%   |
| Phison E12 NVMe Controller                                                     | 1         | 0.81%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1         | 0.81%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 1         | 0.81%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 0.81%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 0.81%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 0.81%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 80        | 67.8%   |
| NVMe | 29        | 24.58%  |
| RAID | 5         | 4.24%   |
| IDE  | 4         | 3.39%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 95        | 88.79%  |
| AMD    | 12        | 11.21%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 7         | 6.54%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 3         | 2.8%    |
| Intel Core i5-3320M CPU @ 2.60GHz           | 3         | 2.8%    |
| Intel Core i5-2520M CPU @ 2.50GHz           | 3         | 2.8%    |
| Intel Core i5-10210U CPU @ 1.60GHz          | 3         | 2.8%    |
| Intel Core i7-5600U CPU @ 2.60GHz           | 2         | 1.87%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz          | 2         | 1.87%   |
| Intel Core i7-3720QM CPU @ 2.60GHz          | 2         | 1.87%   |
| Intel Core i5-9300H CPU @ 2.40GHz           | 2         | 1.87%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 1.87%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 1.87%   |
| Intel Core i3-5010U CPU @ 2.10GHz           | 2         | 1.87%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 2         | 1.87%   |
| Intel Core 2 Duo                            | 2         | 1.87%   |
| Intel Celeron CPU 3855U @ 1.60GHz           | 2         | 1.87%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 2         | 1.87%   |
| AMD Ryzen Embedded V1500B                   | 2         | 1.87%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 0.93%   |
| Intel Pentium M processor                   | 1         | 0.93%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 0.93%   |
| Intel Pentium CPU B960 @ 2.20GHz            | 1         | 0.93%   |
| Intel Pentium CPU 2117U @ 1.80GHz           | 1         | 0.93%   |
| Intel Genuine CPU                           | 1         | 0.93%   |
| Intel Core i7-9750HF CPU @ 2.60GHz          | 1         | 0.93%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 0.93%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 0.93%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 0.93%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 1         | 0.93%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz          | 1         | 0.93%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 0.93%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 0.93%   |
| Intel Core i7-3610QM CPU @ 2.30GHz          | 1         | 0.93%   |
| Intel Core i7-2820QM CPU @ 2.30GHz          | 1         | 0.93%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 1         | 0.93%   |
| Intel Core i7-10610U CPU @ 1.80GHz          | 1         | 0.93%   |
| Intel Core i5-8365U CPU @ 1.60GHz           | 1         | 0.93%   |
| Intel Core i5-8350U CPU @ 1.70GHz           | 1         | 0.93%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 0.93%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 1         | 0.93%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz          | 1         | 0.93%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 36        | 33.64%  |
| Intel Core i7           | 18        | 16.82%  |
| Intel Core i3           | 12        | 11.21%  |
| Intel Core 2 Duo        | 12        | 11.21%  |
| Other                   | 6         | 5.61%   |
| Intel Celeron           | 5         | 4.67%   |
| AMD Ryzen Embedded      | 3         | 2.8%    |
| Intel Pentium           | 2         | 1.87%   |
| AMD Ryzen 3             | 2         | 1.87%   |
| Intel Pentium Silver    | 1         | 0.93%   |
| Intel Pentium M         | 1         | 0.93%   |
| Intel Pentium Dual-Core | 1         | 0.93%   |
| Intel Genuine           | 1         | 0.93%   |
| Intel Celeron M         | 1         | 0.93%   |
| AMD Ryzen 7 PRO         | 1         | 0.93%   |
| AMD Ryzen 7             | 1         | 0.93%   |
| AMD Ryzen 5 PRO         | 1         | 0.93%   |
| AMD EPYC                | 1         | 0.93%   |
| AMD E                   | 1         | 0.93%   |
| AMD Athlon              | 1         | 0.93%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 54        | 50.47%  |
| 4       | 31        | 28.97%  |
| Unknown | 10        | 9.35%   |
| 8       | 5         | 4.67%   |
| 12      | 2         | 1.87%   |
| 6       | 2         | 1.87%   |
| 1       | 2         | 1.87%   |
| 16      | 1         | 0.93%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 101       | 94.39%  |
| Unknown | 6         | 5.61%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 71        | 66.36%  |
| 1       | 24        | 22.43%  |
| Unknown | 12        | 11.21%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 17        | 15.89%  |
| IvyBridge     | 15        | 14.02%  |
| Penryn        | 11        | 10.28%  |
| Haswell       | 11        | 10.28%  |
| SandyBridge   | 10        | 9.35%   |
| Broadwell     | 9         | 8.41%   |
| Skylake       | 6         | 5.61%   |
| Zen+          | 4         | 3.74%   |
| Westmere      | 4         | 3.74%   |
| Zen           | 3         | 2.8%    |
| TigerLake     | 3         | 2.8%    |
| Unknown       | 3         | 2.8%    |
| P6            | 2         | 1.87%   |
| Core          | 2         | 1.87%   |
| Zen 3         | 1         | 0.93%   |
| Zen 2         | 1         | 0.93%   |
| Silvermont    | 1         | 0.93%   |
| Goldmont plus | 1         | 0.93%   |
| Excavator     | 1         | 0.93%   |
| CometLake     | 1         | 0.93%   |
| Bobcat        | 1         | 0.93%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 88        | 68.75%  |
| Nvidia           | 25        | 19.53%  |
| AMD              | 14        | 10.94%  |
| VIA Technologies | 1         | 0.78%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 14        | 10.85%  |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 10        | 7.75%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 10        | 7.75%   |
| Intel HD Graphics 5500                                                        | 8         | 6.2%    |
| Intel Haswell-ULT Integrated Graphics Controller                              | 6         | 4.65%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 4         | 3.1%    |
| Intel UHD Graphics 620                                                        | 4         | 3.1%    |
| Intel Skylake GT2 [HD Graphics 520]                                           | 4         | 3.1%    |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 4         | 3.1%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 4         | 3.1%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 3         | 2.33%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 3         | 2.33%   |
| Intel HD Graphics 620                                                         | 3         | 2.33%   |
| Intel Core Processor Integrated Graphics Controller                           | 3         | 2.33%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 3         | 2.33%   |
| Nvidia GK208M [GeForce GT 740M]                                               | 2         | 1.55%   |
| Intel HD Graphics 510                                                         | 2         | 1.55%   |
| Intel Crystal Well Integrated Graphics Controller                             | 2         | 1.55%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 2         | 1.55%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 2         | 1.55%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                             | 1         | 0.78%   |
| Nvidia GT216M [GeForce GT 240M]                                               | 1         | 0.78%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 1         | 0.78%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 1         | 0.78%   |
| Nvidia GM108M [GeForce 940M]                                                  | 1         | 0.78%   |
| Nvidia GM108M [GeForce 840M]                                                  | 1         | 0.78%   |
| Nvidia GM107M [GeForce GTX 860M]                                              | 1         | 0.78%   |
| Nvidia GM107 [GeForce 940MX]                                                  | 1         | 0.78%   |
| Nvidia GK104GLM [Quadro K3000M]                                               | 1         | 0.78%   |
| Nvidia GF108M [NVS 5400M]                                                     | 1         | 0.78%   |
| Nvidia GF108M [GeForce GT 635M]                                               | 1         | 0.78%   |
| Nvidia GF108M [GeForce GT 525M]                                               | 1         | 0.78%   |
| Nvidia GF108M [GeForce GT 420M]                                               | 1         | 0.78%   |
| Nvidia GF108GLM [NVS 5200M]                                                   | 1         | 0.78%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 1         | 0.78%   |
| Nvidia G96CM [GeForce 9650M GT]                                               | 1         | 0.78%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                               | 1         | 0.78%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 1         | 0.78%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 1         | 0.78%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 1         | 0.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 52        | 48.6%   |
| Intel + Nvidia | 19        | 17.76%  |
| 2 x Intel      | 12        | 11.21%  |
| 1 x AMD        | 9         | 8.41%   |
| 1 x Nvidia     | 6         | 5.61%   |
| Intel + AMD    | 5         | 4.67%   |
| Other          | 3         | 2.8%    |
| 1 x VIA        | 1         | 0.93%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 92        | 85.19%  |
| Proprietary | 10        | 9.26%   |
| Unknown     | 6         | 5.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 96        | 88.89%  |
| 3.01-4.0   | 3         | 2.78%   |
| 0.51-1.0   | 3         | 2.78%   |
| 0.01-0.5   | 3         | 2.78%   |
| 1.01-2.0   | 2         | 1.85%   |
| 5.01-6.0   | 1         | 0.93%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 20        | 23.26%  |
| BOE                     | 10        | 11.63%  |
| Lenovo                  | 9         | 10.47%  |
| AU Optronics            | 9         | 10.47%  |
| Samsung Electronics     | 8         | 9.3%    |
| Chimei Innolux          | 8         | 9.3%    |
| Chi Mei Optoelectronics | 4         | 4.65%   |
| InfoVision              | 3         | 3.49%   |
| Apple                   | 2         | 2.33%   |
| AOC                     | 2         | 2.33%   |
| Sharp                   | 1         | 1.16%   |
| Philips                 | 1         | 1.16%   |
| PANDA                   | 1         | 1.16%   |
| KTC                     | 1         | 1.16%   |
| JDI                     | 1         | 1.16%   |
| Iiyama                  | 1         | 1.16%   |
| Dell                    | 1         | 1.16%   |
| CSO                     | 1         | 1.16%   |
| BOE Technology Group    | 1         | 1.16%   |
| BenQ                    | 1         | 1.16%   |
| Acer                    | 1         | 1.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch                  | 6         | 6.9%    |
| LG Display LCD Monitor LGD039F 1366x768 350x190mm 15.7-inch              | 3         | 3.45%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 2         | 2.3%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 2         | 2.3%    |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 2         | 2.3%    |
| Apple Color LCD APPA02E 2880x1800 330x210mm 15.4-inch                    | 2         | 2.3%    |
| Sharp LCD Monitor SHP1421 3200x1800 290x170mm 13.2-inch                  | 1         | 1.15%   |
| Samsung Electronics LS24AG30x SAM7178 1920x1080 530x300mm 24.0-inch      | 1         | 1.15%   |
| Samsung Electronics LF27T370F SAM711E 1920x1080 600x340mm 27.2-inch      | 1         | 1.15%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x170mm 13.9-inch     | 1         | 1.15%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 300x190mm 14.0-inch     | 1         | 1.15%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 340x190mm 15.3-inch     | 1         | 1.15%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch     | 1         | 1.15%   |
| Samsung Electronics LCD Monitor SDC4163 3456x2160 290x180mm 13.4-inch    | 1         | 1.15%   |
| Samsung Electronics LCD Monitor SDC324A 1366x768 290x170mm 13.2-inch     | 1         | 1.15%   |
| Philips PHL 275S1 PHL094B 2560x1440 600x340mm 27.2-inch                  | 1         | 1.15%   |
| PANDA LCD Monitor NCP006E 1920x1080 340x190mm 15.3-inch                  | 1         | 1.15%   |
| LG Display LCD Monitor LGD0533 1920x1080 340x190mm 15.3-inch             | 1         | 1.15%   |
| LG Display LCD Monitor LGD04E2 1366x768 340x190mm 15.3-inch              | 1         | 1.15%   |
| LG Display LCD Monitor LGD0408 1920x1080 280x160mm 12.7-inch             | 1         | 1.15%   |
| LG Display LCD Monitor LGD03D3 1600x900 310x170mm 13.9-inch              | 1         | 1.15%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch              | 1         | 1.15%   |
| LG Display LCD Monitor LGD0368 1366x768 310x170mm 13.9-inch              | 1         | 1.15%   |
| LG Display LCD Monitor LGD033E 1366x768 310x170mm 13.9-inch              | 1         | 1.15%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch              | 1         | 1.15%   |
| LG Display LCD Monitor LGD02F1 1366x768 340x190mm 15.3-inch              | 1         | 1.15%   |
| LG Display LCD Monitor LGD02EA 1366x768 310x170mm 13.9-inch              | 1         | 1.15%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 1         | 1.15%   |
| LG Display LCD Monitor LGD02AD 1366x768 340x190mm 15.3-inch              | 1         | 1.15%   |
| LG Display LCD Monitor LGD0283 1920x1080 380x220mm 17.3-inch             | 1         | 1.15%   |
| LG Display LCD Monitor LGD0250 1366x768 350x190mm 15.7-inch              | 1         | 1.15%   |
| LG Display LCD Monitor LGD024D 1366x768 290x170mm 13.2-inch              | 1         | 1.15%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch                 | 1         | 1.15%   |
| Lenovo LCD Monitor LEN4053 1680x1050 330x210mm 15.4-inch                 | 1         | 1.15%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch                  | 1         | 1.15%   |
| KTC M-9005L11-D KTC1990 1280x1024 340x270mm 17.1-inch                    | 1         | 1.15%   |
| JDI LAM125M007D JDI1402 1920x1080 280x160mm 12.7-inch                    | 1         | 1.15%   |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch             | 1         | 1.15%   |
| InfoVision LCD Monitor IVO0533 1366x768 290x170mm 13.2-inch              | 1         | 1.15%   |
| InfoVision LCD Monitor IVO04E6 1920x1080 280x160mm 12.7-inch             | 1         | 1.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 30        | 36.14%  |
| 1366x768 (WXGA)    | 28        | 33.73%  |
| 1280x800 (WXGA)    | 8         | 9.64%   |
| 1600x900 (HD+)     | 4         | 4.82%   |
| 2560x1440 (QHD)    | 3         | 3.61%   |
| 2880x1800          | 2         | 2.41%   |
| 5760x2160          | 1         | 1.2%    |
| 3840x2400          | 1         | 1.2%    |
| 3456x2160          | 1         | 1.2%    |
| 3200x1800 (QHD+)   | 1         | 1.2%    |
| 1680x1050 (WSXGA+) | 1         | 1.2%    |
| 1440x900 (WXGA+)   | 1         | 1.2%    |
| 1280x1024 (SXGA)   | 1         | 1.2%    |
| Unknown            | 1         | 1.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 30        | 35.71%  |
| 13      | 23        | 27.38%  |
| 12      | 16        | 19.05%  |
| 27      | 4         | 4.76%   |
| 17      | 4         | 4.76%   |
| 24      | 2         | 2.38%   |
| 14      | 2         | 2.38%   |
| Unknown | 2         | 2.38%   |
| 23      | 1         | 1.19%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 48        | 57.83%  |
| 201-300     | 23        | 27.71%  |
| 501-600     | 7         | 8.43%   |
| 351-400     | 3         | 3.61%   |
| Unknown     | 2         | 2.41%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 60        | 76.92%  |
| 16/10   | 14        | 17.95%  |
| Unknown | 2         | 2.56%   |
| 5/4     | 1         | 1.28%   |
| 3/2     | 1         | 1.28%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 21        | 25%     |
| 91-100         | 20        | 23.81%  |
| 61-70          | 16        | 19.05%  |
| 101-110        | 10        | 11.9%   |
| 71-80          | 4         | 4.76%   |
| 301-350        | 4         | 4.76%   |
| 201-250        | 3         | 3.57%   |
| 121-130        | 2         | 2.38%   |
| Unknown        | 2         | 2.38%   |
| 141-150        | 1         | 1.19%   |
| 131-140        | 1         | 1.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 41        | 49.4%   |
| 101-120       | 19        | 22.89%  |
| 51-100        | 13        | 15.66%  |
| 161-240       | 5         | 6.02%   |
| More than 240 | 3         | 3.61%   |
| Unknown       | 2         | 2.41%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 81        | 72.97%  |
| 0     | 20        | 18.02%  |
| 2     | 10        | 9.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 80        | 47.62%  |
| Realtek Semiconductor             | 38        | 22.62%  |
| Qualcomm Atheros                  | 20        | 11.9%   |
| Broadcom                          | 12        | 7.14%   |
| Dell                              | 3         | 1.79%   |
| AMD                               | 3         | 1.79%   |
| Qualcomm Atheros Communications   | 2         | 1.19%   |
| VIA Technologies                  | 1         | 0.6%    |
| Van Ooijen Technische Informatica | 1         | 0.6%    |
| TP-Link                           | 1         | 0.6%    |
| Sierra Wireless                   | 1         | 0.6%    |
| Ralink Technology                 | 1         | 0.6%    |
| OnePlus Technology (Shenzhen)     | 1         | 0.6%    |
| Marvell Technology Group          | 1         | 0.6%    |
| IMC Networks                      | 1         | 0.6%    |
| Ericsson Business Mobile Networks | 1         | 0.6%    |
| Atheros                           | 1         | 0.6%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 30        | 14.08%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 10        | 4.69%   |
| Intel 82567LM Gigabit Network Connection                               | 10        | 4.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 7         | 3.29%   |
| Intel Ultimate N WiFi Link 5300                                        | 6         | 2.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 5         | 2.35%   |
| Intel Wireless 8265 / 8275                                             | 5         | 2.35%   |
| Intel Wireless 7265                                                    | 5         | 2.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4         | 1.88%   |
| Intel Wireless 8260                                                    | 4         | 1.88%   |
| Intel Wireless 7260                                                    | 4         | 1.88%   |
| Intel I211 Gigabit Network Connection                                  | 4         | 1.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 4         | 1.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 3         | 1.41%   |
| Intel Wireless 3165                                                    | 3         | 1.41%   |
| Intel Wi-Fi 6 AX201                                                    | 3         | 1.41%   |
| Intel Ethernet Connection I219-LM                                      | 3         | 1.41%   |
| Intel Ethernet Connection I218-LM                                      | 3         | 1.41%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 1.41%   |
| Intel Ethernet Connection (3) I218-LM                                  | 3         | 1.41%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 3         | 1.41%   |
| AMD XGMAC 10GbE Controller                                             | 3         | 1.41%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 2         | 0.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 2         | 0.94%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 2         | 0.94%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 2         | 0.94%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 2         | 0.94%   |
| Intel Wi-Fi 6 AX200                                                    | 2         | 0.94%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 2         | 0.94%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                | 2         | 0.94%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 0.94%   |
| Intel Ethernet Connection (10) I219-V                                  | 2         | 0.94%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                          | 2         | 0.94%   |
| Intel Centrino Advanced-N 6235                                         | 2         | 0.94%   |
| Intel Centrino Advanced-N 6200                                         | 2         | 0.94%   |
| Intel 82577LM Gigabit Network Connection                               | 2         | 0.94%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                            | 2         | 0.94%   |
| Broadcom BCM43142 802.11b/g/n                                          | 2         | 0.94%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 2         | 0.94%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 68        | 62.96%  |
| Qualcomm Atheros                | 17        | 15.74%  |
| Broadcom                        | 8         | 7.41%   |
| Realtek Semiconductor           | 7         | 6.48%   |
| Qualcomm Atheros Communications | 2         | 1.85%   |
| Dell                            | 2         | 1.85%   |
| TP-Link                         | 1         | 0.93%   |
| Ralink Technology               | 1         | 0.93%   |
| IMC Networks                    | 1         | 0.93%   |
| Atheros                         | 1         | 0.93%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 7         | 6.42%   |
| Intel Ultimate N WiFi Link 5300                                               | 6         | 5.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 5         | 4.59%   |
| Intel Wireless 8265 / 8275                                                    | 5         | 4.59%   |
| Intel Wireless 7265                                                           | 5         | 4.59%   |
| Intel Wireless 8260                                                           | 4         | 3.67%   |
| Intel Wireless 7260                                                           | 4         | 3.67%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 4         | 3.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 3         | 2.75%   |
| Intel Wireless 3165                                                           | 3         | 2.75%   |
| Intel Wi-Fi 6 AX201                                                           | 3         | 2.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 3         | 2.75%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 2         | 1.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2         | 1.83%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 2         | 1.83%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 2         | 1.83%   |
| Intel Wi-Fi 6 AX200                                                           | 2         | 1.83%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                       | 2         | 1.83%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                       | 2         | 1.83%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                 | 2         | 1.83%   |
| Intel Centrino Advanced-N 6235                                                | 2         | 1.83%   |
| Intel Centrino Advanced-N 6200                                                | 2         | 1.83%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                   | 2         | 1.83%   |
| Broadcom BCM43142 802.11b/g/n                                                 | 2         | 1.83%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 2         | 1.83%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1         | 0.92%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                   | 1         | 0.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.92%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 0.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.92%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1         | 0.92%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 0.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1         | 0.92%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1         | 0.92%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 0.92%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1         | 0.92%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 0.92%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                     | 1         | 0.92%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                             | 1         | 0.92%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 0.92%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 50        | 51.55%  |
| Realtek Semiconductor         | 34        | 35.05%  |
| Broadcom                      | 4         | 4.12%   |
| Qualcomm Atheros              | 3         | 3.09%   |
| AMD                           | 3         | 3.09%   |
| VIA Technologies              | 1         | 1.03%   |
| OnePlus Technology (Shenzhen) | 1         | 1.03%   |
| Marvell Technology Group      | 1         | 1.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 30        | 30.3%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 10        | 10.1%   |
| Intel 82567LM Gigabit Network Connection                               | 10        | 10.1%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4         | 4.04%   |
| Intel I211 Gigabit Network Connection                                  | 4         | 4.04%   |
| Intel Ethernet Connection I219-LM                                      | 3         | 3.03%   |
| Intel Ethernet Connection I218-LM                                      | 3         | 3.03%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 3.03%   |
| Intel Ethernet Connection (3) I218-LM                                  | 3         | 3.03%   |
| AMD XGMAC 10GbE Controller                                             | 3         | 3.03%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 2         | 2.02%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 2.02%   |
| Intel Ethernet Connection (10) I219-V                                  | 2         | 2.02%   |
| Intel 82577LM Gigabit Network Connection                               | 2         | 2.02%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1         | 1.01%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 1.01%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 1.01%   |
| OnePlus (Shenzhen) Android Remote NDIS Device                          | 1         | 1.01%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 1         | 1.01%   |
| Intel I210 Gigabit Network Connection                                  | 1         | 1.01%   |
| Intel Ethernet Controller I225-V                                       | 1         | 1.01%   |
| Intel Ethernet Connection I219-V                                       | 1         | 1.01%   |
| Intel Ethernet Connection (7) I219-V                                   | 1         | 1.01%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 1.01%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 1.01%   |
| Intel Ethernet Connection (10) I219-LM                                 | 1         | 1.01%   |
| Intel 82579V Gigabit Network Connection                                | 1         | 1.01%   |
| Intel 82574L Gigabit Network Connection                                | 1         | 1.01%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express               | 1         | 1.01%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                        | 1         | 1.01%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 1         | 1.01%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1         | 1.01%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 100       | 50.51%  |
| Ethernet | 93        | 46.97%  |
| Modem    | 3         | 1.52%   |
| Unknown  | 2         | 1.01%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 74        | 56.92%  |
| Ethernet | 56        | 43.08%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 84        | 78.5%   |
| 1     | 14        | 13.08%  |
| 6     | 3         | 2.8%    |
| 3     | 3         | 2.8%    |
| 5     | 2         | 1.87%   |
| 0     | 1         | 0.93%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 107       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 40        | 54.79%  |
| Broadcom                        | 11        | 15.07%  |
| Realtek Semiconductor           | 4         | 5.48%   |
| IMC Networks                    | 4         | 5.48%   |
| Foxconn / Hon Hai               | 4         | 5.48%   |
| Qualcomm Atheros Communications | 3         | 4.11%   |
| Dell                            | 2         | 2.74%   |
| Apple                           | 2         | 2.74%   |
| Lite-On Technology              | 1         | 1.37%   |
| Hewlett-Packard                 | 1         | 1.37%   |
| ASUSTek Computer                | 1         | 1.37%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                       | 18        | 24.66%  |
| Intel AX201 Bluetooth                                    | 6         | 8.22%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 5         | 6.85%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]       | 5         | 6.85%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 3         | 4.11%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter         | 3         | 4.11%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]               | 3         | 4.11%   |
| Intel AX200 Bluetooth                                    | 2         | 2.74%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter        | 2         | 2.74%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth            | 2         | 2.74%   |
| Apple Bluetooth Host Controller                          | 2         | 2.74%   |
| Realtek Wireless Bluetooth Adapter                       | 1         | 1.37%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                  | 1         | 1.37%   |
| Realtek  Bluetooth 4.2 Adapter                           | 1         | 1.37%   |
| Realtek Bluetooth Adapter                                | 1         | 1.37%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                   | 1         | 1.37%   |
| Qualcomm Atheros Dell Wireless 1601 Bluetooth Device     | 1         | 1.37%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                    | 1         | 1.37%   |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS              | 1         | 1.37%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 1         | 1.37%   |
| Intel AX211 Bluetooth                                    | 1         | 1.37%   |
| Intel AX210 Bluetooth                                    | 1         | 1.37%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS         | 1         | 1.37%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011]   | 1         | 1.37%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter               | 1         | 1.37%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device | 1         | 1.37%   |
| Foxconn / Hon Hai Bluetooth USB Module                   | 1         | 1.37%   |
| Dell DW375 Bluetooth Module                              | 1         | 1.37%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module              | 1         | 1.37%   |
| Broadcom BCM43142A0 Bluetooth Module                     | 1         | 1.37%   |
| Broadcom BCM43142A0 Bluetooth 4.0                        | 1         | 1.37%   |
| Broadcom BCM2045B (BDC-2.1)                              | 1         | 1.37%   |
| ASUS BT-253 Bluetooth Adapter                            | 1         | 1.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 93        | 79.49%  |
| AMD                   | 12        | 10.26%  |
| Nvidia                | 9         | 7.69%   |
| VIA Technologies      | 1         | 0.85%   |
| Realtek Semiconductor | 1         | 0.85%   |
| Kingston Technology   | 1         | 0.85%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 17        | 11.72%  |
| Intel Sunrise Point-LP HD Audio                                            | 13        | 8.97%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 12        | 8.28%   |
| Intel Broadwell-U Audio Controller                                         | 9         | 6.21%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 9         | 6.21%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 8         | 5.52%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 8         | 5.52%   |
| Intel Haswell-ULT HD Audio Controller                                      | 6         | 4.14%   |
| Intel 8 Series HD Audio Controller                                         | 6         | 4.14%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5         | 3.45%   |
| Intel Comet Lake PCH-LP cAVS                                               | 4         | 2.76%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 2.76%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 2.76%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 2.76%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 2.07%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 2.07%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 2.07%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 2.07%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 2.07%   |
| Intel Crystal Well HD Audio Controller                                     | 2         | 1.38%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1         | 0.69%   |
| Realtek Semiconductor TX 384kb Hifi Type_C Audio                           | 1         | 0.69%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.69%   |
| Nvidia GA107 High Definition Audio Controller                              | 1         | 0.69%   |
| Nvidia AD107 High Definition Audio Controller                              | 1         | 0.69%   |
| Kingston Technology HyperX 7.1 Audio                                       | 1         | 0.69%   |
| Intel Raptor Lake High Definition Audio Controller                         | 1         | 0.69%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 0.69%   |
| Intel CM238 HD Audio Controller                                            | 1         | 0.69%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 0.69%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 0.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 0.69%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 0.69%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1         | 0.69%   |
| AMD Wrestler HDMI Audio                                                    | 1         | 0.69%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 0.69%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 0.69%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1         | 0.69%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 29        | 26.13%  |
| SK hynix            | 25        | 22.52%  |
| Kingston            | 11        | 9.91%   |
| Micron Technology   | 10        | 9.01%   |
| Unknown             | 8         | 7.21%   |
| Ramaxel Technology  | 5         | 4.5%    |
| GOODRAM             | 5         | 4.5%    |
| Unknown             | 4         | 3.6%    |
| Transcend           | 3         | 2.7%    |
| Elpida              | 3         | 2.7%    |
| Nanya Technology    | 2         | 1.8%    |
| Corsair             | 2         | 1.8%    |
| A-DATA Technology   | 2         | 1.8%    |
| SHARETRONIC         | 1         | 0.9%    |
| G.Skill             | 1         | 0.9%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Unknown                                                   | 4         | 3.36%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 3         | 2.52%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s       | 2         | 1.68%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s              | 2         | 1.68%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 2         | 1.68%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 2         | 1.68%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s    | 2         | 1.68%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s    | 2         | 1.68%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s    | 2         | 1.68%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s     | 2         | 1.68%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s     | 2         | 1.68%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s     | 2         | 1.68%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 2         | 1.68%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 2         | 1.68%   |
| Samsung RAM M471B1G73BH0-CK0 8GB SODIMM DDR3 1600MT/s     | 2         | 1.68%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s     | 2         | 1.68%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s | 2         | 1.68%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s     | 2         | 1.68%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s               | 1         | 0.84%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s               | 1         | 0.84%   |
| Unknown RAM Module 512MB SODIMM DDR                       | 1         | 0.84%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s               | 1         | 0.84%   |
| Unknown RAM Module 4GB SODIMM DDR3                        | 1         | 0.84%   |
| Unknown RAM Module 4096MB SODIMM DDR3                     | 1         | 0.84%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                | 1         | 0.84%   |
| Unknown RAM Module 2GB SODIMM DDR                         | 1         | 0.84%   |
| Unknown RAM Module 1GB SODIMM DRAM 533MT/s                | 1         | 0.84%   |
| Transcend RAM AQD-SD3L4GN16-S G 4GB SODIMM DDR3 1600MT/s  | 1         | 0.84%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s              | 1         | 0.84%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2400MT/s             | 1         | 0.84%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 0.84%   |
| SK hynix RAM HMT425S6MFR6A-PB 2GB SODIMM DDR3 1600MT/s    | 1         | 0.84%   |
| SK hynix RAM HMT41GS6DFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 1         | 0.84%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1333MT/s    | 1         | 0.84%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s    | 1         | 0.84%   |
| SK hynix RAM HMT112S6TFR8C-H9 1GB SODIMM DDR3 1066MT/s    | 1         | 0.84%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s   | 1         | 0.84%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2400MT/s   | 1         | 0.84%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s    | 1         | 0.84%   |
| SK hynix RAM H9CCNNN8JTBLAR-NUD 2GB LPDDR3 1867MT/s       | 1         | 0.84%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 49        | 52.69%  |
| DDR4    | 33        | 35.48%  |
| LPDDR4  | 3         | 3.23%   |
| LPDDR3  | 2         | 2.15%   |
| SDRAM   | 1         | 1.08%   |
| DRAM    | 1         | 1.08%   |
| DDR5    | 1         | 1.08%   |
| DDR2    | 1         | 1.08%   |
| DDR     | 1         | 1.08%   |
| Unknown | 1         | 1.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 86        | 92.47%  |
| Row Of Chips | 3         | 3.23%   |
| Unknown      | 2         | 2.15%   |
| DIMM         | 1         | 1.08%   |
| Chip         | 1         | 1.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 35        | 34.31%  |
| 4096  | 31        | 30.39%  |
| 2048  | 19        | 18.63%  |
| 16384 | 11        | 10.78%  |
| 1024  | 5         | 4.9%    |
| 512   | 1         | 0.98%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 32        | 29.91%  |
| 2667    | 12        | 11.21%  |
| 2400    | 10        | 9.35%   |
| 3200    | 9         | 8.41%   |
| 1333    | 9         | 8.41%   |
| 1334    | 8         | 7.48%   |
| 2133    | 5         | 4.67%   |
| 800     | 5         | 4.67%   |
| 1067    | 4         | 3.74%   |
| 1867    | 3         | 2.8%    |
| Unknown | 3         | 2.8%    |
| 4267    | 2         | 1.87%   |
| 1066    | 2         | 1.87%   |
| 5600    | 1         | 0.93%   |
| 2048    | 1         | 0.93%   |
| 533     | 1         | 0.93%   |

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
| Chicony Electronics                    | 29        | 42.03%  |
| Realtek Semiconductor                  | 8         | 11.59%  |
| Microdia                               | 8         | 11.59%  |
| Bison Electronics                      | 6         | 8.7%    |
| IMC Networks                           | 3         | 4.35%   |
| Syntek                                 | 2         | 2.9%    |
| Ricoh                                  | 2         | 2.9%    |
| Luxvisions Innotech Limited            | 2         | 2.9%    |
| Lite-On Technology                     | 2         | 2.9%    |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.9%    |
| Suyin                                  | 1         | 1.45%   |
| Sunplus Innovation Technology          | 1         | 1.45%   |
| Quanta                                 | 1         | 1.45%   |
| Logitech                               | 1         | 1.45%   |
| DigiTech                               | 1         | 1.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                             | 6         | 8.57%   |
| Realtek Lenovo EasyCamera                             | 3         | 4.29%   |
| Realtek Integrated_Webcam_HD                          | 3         | 4.29%   |
| Microdia Integrated Webcam                            | 3         | 4.29%   |
| Chicony Realtek DMFT RGB                              | 3         | 4.29%   |
| Chicony Integrated Camera [ThinkPad]                  | 3         | 4.29%   |
| Chicony Integrated Camera (1280x720@30)               | 3         | 4.29%   |
| Microdia Integrated_Webcam_HD                         | 2         | 2.86%   |
| Lite-On Integrated Camera                             | 2         | 2.86%   |
| IMC Networks Integrated Camera                        | 2         | 2.86%   |
| Bison Lenovo EasyCamera                               | 2         | 2.86%   |
| Bison Integrated Camera                               | 2         | 2.86%   |
| Syntek Lenovo EasyCamera                              | 1         | 1.43%   |
| Syntek Integrated Camera                              | 1         | 1.43%   |
| Suyin Acer/HP Integrated Webcam [CN0314]              | 1         | 1.43%   |
| Sunplus Integrated_Webcam_HD                          | 1         | 1.43%   |
| Ricoh Integrated Webcam                               | 1         | 1.43%   |
| Ricoh HD Webcam                                       | 1         | 1.43%   |
| Realtek HD WebCam                                     | 1         | 1.43%   |
| Realtek Front Camera                                  | 1         | 1.43%   |
| Quanta Realtek DMFT RGB                               | 1         | 1.43%   |
| Microdia Laptop_Integrated_Webcam_HD                  | 1         | 1.43%   |
| Microdia Integrated HD Webcam                         | 1         | 1.43%   |
| Microdia Dell Integrated HD Webcam                    | 1         | 1.43%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera   | 1         | 1.43%   |
| Luxvisions Innotech Limited HP True Vision FHD Camera | 1         | 1.43%   |
| Logitech HD Pro Webcam C920                           | 1         | 1.43%   |
| IMC Networks EasyCamera                               | 1         | 1.43%   |
| DigiTech WebCam SCB-0350M                             | 1         | 1.43%   |
| Chicony USB2.0 VGA UVC WebCam                         | 1         | 1.43%   |
| Chicony USB2.0 HD UVC WebCam                          | 1         | 1.43%   |
| Chicony ThinkPad T490 Webcam                          | 1         | 1.43%   |
| Chicony Realtek DMFT IR                               | 1         | 1.43%   |
| Chicony Lenovo Integrated Camera (0.3MP)              | 1         | 1.43%   |
| Chicony Lenovo EasyCamera                             | 1         | 1.43%   |
| Chicony HP Integrated Webcam                          | 1         | 1.43%   |
| Chicony HP HD Webcam [Fixed]                          | 1         | 1.43%   |
| Chicony HP HD Webcam                                  | 1         | 1.43%   |
| Chicony HP HD Camera                                  | 1         | 1.43%   |
| Chicony HD WebCam                                     | 1         | 1.43%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 7         | 31.82%  |
| Validity Sensors           | 4         | 18.18%  |
| AuthenTec                  | 4         | 18.18%  |
| Broadcom                   | 3         | 13.64%  |
| Shenzhen Goodix Technology | 2         | 9.09%   |
| STMicroelectronics         | 1         | 4.55%   |
| Elan Microelectronics      | 1         | 4.55%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 4         | 18.18%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 13.64%  |
| AuthenTec AES2810                                                            | 3         | 13.64%  |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 2         | 9.09%   |
| Validity Sensors Fingerprint scanner                                         | 2         | 9.09%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 2         | 9.09%   |
| Shenzhen Goodix Fingerprint Reader                                           | 2         | 9.09%   |
| Synaptics WBDI                                                               | 1         | 4.55%   |
| STMicroelectronics Fingerprint Reader                                        | 1         | 4.55%   |
| Elan Fingerprint Sensor                                                      | 1         | 4.55%   |
| AuthenTec AES2660                                                            | 1         | 4.55%   |

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
| 1     | 36        | 32.73%  |
| 2     | 34        | 30.91%  |
| 3     | 20        | 18.18%  |
| 0     | 12        | 10.91%  |
| 5     | 3         | 2.73%   |
| 4     | 3         | 2.73%   |
| 6     | 2         | 1.82%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 85        | 47.22%  |
| Bluetooth                | 23        | 12.78%  |
| Fingerprint reader       | 21        | 11.67%  |
| Card reader              | 21        | 11.67%  |
| Net/wireless             | 14        | 7.78%   |
| Graphics card            | 8         | 4.44%   |
| Firewire controller      | 3         | 1.67%   |
| Sound                    | 2         | 1.11%   |
| Network                  | 2         | 1.11%   |
| Modem                    | 1         | 0.56%   |

